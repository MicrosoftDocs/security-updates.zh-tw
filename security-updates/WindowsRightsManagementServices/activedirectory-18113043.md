---
TOCTitle: 覆寫 Active Directory 服務探索
Title: 覆寫 Active Directory 服務探索
ms:assetid: '9d97e7fb-5b05-4853-ad7b-6cc82b9729f0'
ms:contentKeyID: 18113043
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc747614(v=WS.10)'
---

覆寫 Active Directory 服務探索
==============================

RMS 服務與用戶端會先查閱本機登錄，以探索服務的位置。如果登錄中的某些機碼沒有值，RMS 服務與用戶端會查閱 Active Directory，尋找服務連接點 (SCP)。這表示，如果您在伺服器或用戶端登錄中輸入某些機碼，就能覆寫預設的 Active Directory 探索設定。

| ![](images/Cc747614.note(WS.10).gif)附註                                   |
|---------------------------------------------------------------------------------------------------------|
| 如果您的 RMS 根叢集設定為 SCP 不在 Active Directory 中發佈，就能使用這些機碼將 RMS 用戶端指向正確位置。 |

本區段說明登錄項目，並提供如何建立這些項目的詳細資料。

覆寫適用於僅授權的叢集子註冊的服務探索
--------------------------------------

如果您是提供僅授權叢集，而且此叢集要向不同的根叢集子註冊 (而不是您在僅授權叢集的 Active Directory 樹系中部署的根叢集)，則您必須覆寫子註冊與帳號憑證服務的探索。

#### 登錄項目描述

下列登錄項目用於覆寫子註冊與帳號憑證服務。

-   **SubEnrollmentURL**。此項目指定授權伺服器要求其伺服器授權人憑證時所使用之根叢集的路徑。
-   **GicURL**。此項目指定此僅授權叢集的帳號憑證服務路徑。

#### 項目詳細資料

在執行 32 位元版本 Windows Server 2003 的電腦上，僅授權叢集子註冊之服務探索項目的完整登錄子機碼路徑為：

**HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\DRMS\\1.0**

在執行 64 位元版本 Windows Server 2003 的電腦上，僅授權叢集子註冊之服務探索項目的完整登錄子機碼路徑為：

**HKEY\_LOCAL\_MACHINE\\SoftwareWOW6432Node\\Microsoft\\DRMS\\1.0**

下表列出您可以新增以覆寫服務探索的項目。

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >名稱</th>
<th style="border:1px solid black;" >類型</th>
<th style="border:1px solid black;" >值</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">SubEnrollmentURL</td>
<td style="border:1px solid black;">字串</td>
<td style="border:1px solid black;">http (或 https)://<em>server_name</em>/_wmcs/certification/subenrollservice.asmx</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">GicURL</td>
<td style="border:1px solid black;">字串</td>
<td style="border:1px solid black;">http (或 https)://<em>server_name</em>/_wmcs/certification/certification.asmx</td>
</tr>
</tbody>
</table>
  
覆寫發佈的用戶端服務探索  
------------------------
  
如果您的使用者將從他們的電腦發佈內容，您可能會想依據企業使用的拓樸，來覆寫用於發佈的伺服器的位置。用於發佈之伺服器的位置，通常是由使用 Active Directory 的用戶端發現。用戶端會在用戶端電腦上新增合適的登錄機碼，來略過那些方法，而使用您在登錄項目值中指定的 URL。
  
| ![](images/Cc747614.note(WS.10).gif)附註                        |  
|----------------------------------------------------------------------------------------------|  
| 本區段列出的用戶端覆寫應建立為機碼，而非個別項目。這些機碼的值應建立於每一機碼的預設項目中。 |
  
#### 登錄機碼描述
  
下列登錄機碼可用於覆寫 RMS 叢集的自動探索。
  
-   **Activation**。此登錄機碼定義機器啟用服務的 URL。如果您是執行 RMS Service Pack 1 或更新版的用戶端，就不再使用此登錄項目。  
-   **EnterprisePublishing**。此登錄機碼定義 RMS 安裝的 URL，而您要此用戶端將此 RMS 安裝用於授權要求。  
-   **CloudPublishing**。此登錄機碼定義 Microsoft 所主控授權服務的 URL。用戶端無法存取 RMS 安裝，但可存取網際網路時，則可使用此授權服務。
  
#### 機碼詳細資料
  
用於發佈的用戶端服務探索項目的完整登錄子機碼路徑為：
  
**HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\MSDRM\\ServiceLocation\\**
  
下表列出您可在 RMS 用戶端電腦上新增以覆寫服務探索的登錄機碼。
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >名稱</th>
<th style="border:1px solid black;" >類型</th>
<th style="border:1px solid black;" >值</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">啟用</td>
<td style="border:1px solid black;">字串</td>
<td style="border:1px solid black;">http (或 https)://<em>RMS_cluster_name</em>/_wmcs/Certification，其中 <em>RMS_cluster_name</em> 是 RMS 叢集的名稱。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">EnterprisePublishing</td>
<td style="border:1px solid black;">字串</td>
<td style="border:1px solid black;">http (或 https)://<em>RMS_cluster_name</em>/_wmcs/Licensing，其中 <em>RMS_cluster_name</em> 是 RMS 叢集的名稱。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">CloudPublishing</td>
<td style="border:1px solid black;">字串</td>
<td style="border:1px solid black;">http (或 https)://<em>FQDN_cluster_name</em>/_wmcs/Licensing，其中 <em>FQDN_cluster_name</em> 是 RMS 叢集的完整網域名稱。</td>
</tr>
</tbody>
</table>
  
我們建議您使用 Systems Management Server 或群組原則來實作這些登錄機碼，以確保您企業中的所有用戶端都使用正確的發佈伺服器。
  
| ![](images/Cc747614.Caution(WS.10).gif)注意                     |  
|----------------------------------------------------------------------------------------------|  
| 若不正確地編輯登錄，將會對系統造成嚴重損害。在變更登錄前，您應先備份電腦上任何有價值的資料。 |
  
您可使用範例登錄檔 (.reg)，以在 RMS 叢集內每一伺服器上匯入適當的登錄機碼。
  
**若要在 RMS 叢集內每一伺服器上匯入適當的登錄機碼**  
1.  將下列範例登錄檔複製到 Notepad 中。
  
    `Windows Registry Editor Version 5.00`
  
    `[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MSDRM\ServiceLocation]`
  
    `[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MSDRM\ServiceLocation\Activation]`
  
    `@="http://<RMS_cluster_name>/_wmcs/certification"`
  
    `[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MSDRM\ServiceLocation\EnterprisePublishing]`
  
    `@="http://<RMS_cluster_name>/_wmcs/licensing"`
  
2.  將 &lt;RMS\_cluster\_name&gt; 取代為您的 RMS 叢集名稱。
  
3.  以 .reg 副檔名儲存檔案。
  
4.  在下檔案總管中按兩下檔案名稱。
  
5.  當 \[使用者帳戶控制\] 對話方塊出現，確認顯示的動作為所需動作後，再按一下 \[繼續\]。。出現提示詢問您是否要將資訊新增到登錄時，請按一下 \[是\]。
