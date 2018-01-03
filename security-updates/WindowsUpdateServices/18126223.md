---
TOCTitle: 'WSUS (含 Service Pack 1) 的讀我檔案'
Title: 'WSUS (含 Service Pack 1) 的讀我檔案'
ms:assetid: '937ecfe9-e8e0-41ac-85f7-4b65956f3d1e'
ms:contentKeyID: 18126223
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc708486(v=WS.10)'
---

WSUS (含 Service Pack 1) 的讀我檔案
===================================

本文件描述會影響 Windows Server Update Services (含 Service Pack 1) (亦即 WSUS 含 SP1) 的已知問題。而在 WSUS SP1 資訊之後，即為原始 WSUS 讀我檔案附註中先前包含的所有資訊。這項資訊包含安裝 WSUS 的建議及需求。若要下載 WSUS (含 SP1)，請參閱 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=67516)。

WSUS (含 SP1) 的新功能
----------------------

WSUS (含 SP1) 這個 Service Pack 版本可以改善 WSUS 的安全性、可靠性、擴充性、相容性及效能。下列為新功能和加強功能：

-   Windows Vista 用戶端支援：WSUS (含 SP1) Server 可以更新執行 Windows Vista 的電腦。
-   更多用戶端語言支援：所有 Office 和 Windows Vista 語言的支援。
-   新版 WMSDE：WSUS (含 SP1) 會將 WMSDE 執行個體升級為 WMSDE SP4 (WSUS RTM 則使用 WMSDE SP3)。
-   效能提升：WSUS (含 SP1) 包含各種效能提升功能，可以加速使用者介面的回應時間。
-   所有 Hotfix：WSUS (含 SP1) 包含 WSUS RTM 之後所發行的所有變更及 Hotfix。
-   SQL Server 2005 的支援。

開始 WSUS (含 SP1) 升級之前
---------------------------

下列是 WSUS (含 SP1) 升級的特定問題。請注意，本主題原始版本的＜開始之前＞部份中所概述的問題及需求在本部份中並未被提及，但仍然有效。例如，原始＜開始之前＞部份中所概述的安裝需求仍然有效。

**附註**   將 SP1 套用至 WSUS 2.0 之後，即無法解除安裝 Service Pack。解除安裝 SP1 將會解除安裝整個產品。

**重要事項**   本文件包含如何修改登錄的相關資訊。請確定先備份再修改登錄。請確定您知道發生問題時要如何還原登錄。如需如何備份、還原及修改登錄的相關資訊，請參閱 Microsoft 知識庫中的下列文件：

[＜Microsoft Windows 登錄描述＞](http://support.microsoft.com/kb/256986) (http://support.microsoft.com/kb/256986/)

#### 問題 1：確定您有足夠的磁碟空間可以進行資料庫備份

當您從 WSUS RTM 升級時，WSUS (含 SP1) 安裝程式會自動建立 WSUS 資料庫的備份。您必須確定 WSUS 伺服器檔案系統有足夠的磁碟空間可以存放 WSUS 資料庫的備份，否則 WSUS (含 SP1) 安裝程式將會失敗。

**若要判定是否有足夠的磁碟空間**
1.  開啟 \[Windows 檔案總管\]，並且瀏覽至 WSUS 資料庫所在的資料夾。依預設，WSUS 會將資料庫安裝於：

    
        ```
2.  按住 **CTRL**，選取 \[SUSDB.MDF\] 和 \[SUSDB\_log.LDF\]，然後按一下滑鼠右鍵並選取 \[內容\]。

3.  在 \[檔案\] 對話方塊中，讀取 \[磁碟上的大小\] 中的值。您的磁碟至少要有這麼多可用磁碟空間才能安裝 WSUS (含 SP1)。

4.  從 \[開始\] 功能表中，按一下 \[我的電腦\]。請確定安裝 WSUS 的磁碟具有所需的可用磁碟空間。

如果因為某些原因導致 WSUS (含 SP1) 安裝程式失敗，請手動還原備份資料庫。如需還原 WSUS 資料庫的相關指示，請參閱 [WSUS 操作手冊](http://technet2.microsoft.com/windowsserver/en/library/05f2e884-ae62-4c90-9681-6c9f2f3c9fd91033.mspx)。

#### 問題 2：WSUS (含 SP1) 只會升級 WSUS RTM

您只能使用 WSUS (含 SP1) 來升級 WSUS RTM。目前不支援從 WSUS Release Candidate 進行升級。如果您已安裝 WSUS Release Candidate 或任何舊版 WSUS 組建，則必須先解除安裝這些組建，然後再執行 WSUS (含 SP1)。

#### 問題 3：進行 WSUS (含 SP1) 升級期間，將會在您的伺服器上停止 IIS 服務

進行升級程序期間，WSUS (含 SP1) 升級安裝程式 會在您的伺服器上停止網際網路資訊服務 (IIS) 服務。這表示在升級期間，由伺服器上的 IIS 安裝所控管的所有網站都將無法使用。升級結束時會自動啟動 IIS。

#### 問題 4：升級期間不應執行任何會呼叫 WSUS API 的應用程式

WSUS Application Interface (API) 呼叫會與 WSUS (含 SP1) 安裝程式相衝突，導致升級失敗 (您會收到訊息，要求您重新啟動伺服器以完成升級)。

#### 問題 5：升級為 WSUS (含 SP1) 時，您可能需要停用防毒程式

當您套用 WSUS (含 SP1) 來升級 WSUS 時，可能需要先停用防毒程式，才能成功執行升級或套用 Service Pack。停用防毒程式之後，請重新啟動 Windows Server 電腦，然後再套用升級或 Service Pack。此程序會防止鎖定更新程序需要存取的檔案。完成安裝之後，請務必重新啟用防毒程式。請造訪防毒程式廠商的網站，針對您的防毒程式和版本瞭解停用及重新啟用的確實步驟。

| ![](images/Cc708486.Caution(WS.10).gif)注意                                                                                                                                   |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 這項因應措施可能會使您的電腦或網路更容易遭受惡意使用者或病毒等惡意軟體攻擊。我們並不建議您採取這項因應措施，但是提供這份資訊，供您自行決定是否要執行這項因應措施。您必須自行承擔使用這項因應措施時的風險。 |

| ![](images/Cc708486.note(WS.10).gif)附註                                                                  |
|----------------------------------------------------------------------------------------------------------------------------------------|
| 防毒軟體是設計來保護您的電腦免受病毒攻擊。停用防毒軟體時，請勿下載或開啟來自不信任來源的檔案、造訪不信任的網站，或是開啟電子郵件附件。 |

#### 問題 6：如果您是使用 Proxy 伺服器，則 SP1 升級可能會清除 Proxy 設定的使用者名稱和密碼

如果您是使用 Proxy 伺服器，有時 SP1 升級可能會清除 Proxy 設定的使用者名稱和密碼。這可能會導致 Microsoft Server 的更新同步化產生 \[不正確的參數\] 錯誤。若要解決此問題，請重設 Proxy 設定的使用者名稱及密碼，然後重新同步化伺服器。

#### 問題 7：如何從失敗的升級復原，以便將 WSUS 伺服器還原至一致的狀態，然後再重試升級。

如果升級為 WSUS (含 SP1) 失敗，則可能會讓 WSUS 安裝處於不一致或無法使用的狀態。為了重試升級為 WSUS (含 SP1)，您需要讓 WSUS 安裝處於一致狀態。若要進行這項工作，您可以使用在升級程序一開始所建立的備份資料庫，將 WSUS 伺服器還原為升級前的狀態。

如果升級失敗，請遵循這些步驟重新嘗試升級為 WSUS (含 SP1)：

**若要重新嘗試升級為 WSUS (含 SP1)**
1.  檢視 WSUSSetup\_%timestamp%.log 檔的內容，以判定備份資料庫的位置。此檔案位於下列資料夾：

    -   %programfiles%\\Update Services\\LogFiles

2.  使用下列指令在 WSUS 電腦上還原備份資料庫：

    -   osql.exe -S &lt;DatabaseInstance&gt; -E -Q "USE master ALTER DATABASE SUSDB SET SINGLE\_USER WITH ROLLBACK IMMEDIATE RESTORE DATABASE SUSDB FROM DISK=N'&lt;PathToDatabaseBackup&gt;' WITH REPLACE ALTER DATABASE SUSDB SET MULTI\_USER"
    -   請記得使用您的安裝值取代 &lt;DatabaseInstance&gt; 和 &lt;PathToDatabaseBackup&gt;。
    -   至於 &lt;DatabaseInstance&gt;，請使用下列登錄機碼值：
    -   HKLM\\Software\\Microsoft\\Update Services\\Server\\Setup\\SqlServerName
    -   而&lt;PathToDatabaseBackup&gt; 則是使用您在步驟 1 中識別的值

3.  解除安裝 WSUS，但是在提示您移除 WSUS 資料庫、記錄檔和更新檔時，請加以保留。(請確定已取消選取 \[移除 Microsoft Windows Server Update Services\] 中的所有選項)。

4.  重新安裝 WSUS RTM (原始版本並非 WSUS (含 SP1))。當提示您重新安裝時，請使用現有的資料庫。這會讓您的 WSUS 系統回復成一致狀態。

5.  安裝 WSUS (含 SP1)。

**附註**    執行 WSUS (含 SP1) 的全新安裝時，您無法直接從上述步驟 1 使用備份資料庫。資料庫架構已變更，因此這個資料庫必須升級為 WSUS (含 SP1) 才能相容。

#### 問題 8：當已遷移 WMSDE 資料庫時，有時 WSUS (含 SP1) 升級可能會失敗

解決方式會視遷移到本機或遠端 SQL Server 而不同。

#### WMSDE 資料庫遷移到本機 SQL 2000 Server

您必須變更登錄機碼值，以便讓 WSUS (含 SP1) 安裝套件辨識沒有要更新的 WMSDE 資料庫。

如果已將 WMSDE 遷移到本機 SQL 2000 Server，則必須先進行下列登錄變更，再嘗試升級為 WSUS (含 SP1)：

-   將 下列登錄機碼值從 "1" 變更為 "0"：
    -   HKLM\\Software\\Microsoft\\Update Services\\Server\\Setup\\WmsdeInstalled  

#### WMSDE 資料庫遷移到遠端 SQL 2000 Server

您必須變更兩個登錄機碼值，以便讓 WSUS (含 SP1) 安裝套件辨識沒有要更新的 WMSDE 資料庫。您必須在後端伺服器上初始化更新，接著在前端伺服器上初始化更新。  

如果您已將 WMSDE 遷移到遠端 SQL Server，則必須先進行下列登錄變更，然後才能嘗試升級為 WSUS (含 SP1)：

1.  將下列登錄機碼值從 "1" 變更為 "0"：
    -   HKLM\\Software\\Microsoft\\Update Services\\Server\\Setup\\WmsdeInstalled 
2.  將下列登錄機碼值從 "0x80" 變更為 "0x20"
    -   HKLM\\Software\\Microsoft\\Update Services\\Server\\Setup\\InstallType 

更新這些登錄機碼值之後，請在後端伺服器上初始化升級，然後在前端伺服器上初始化升級。

#### 問題 9：WSUS (含 SP1) 不會更新設定為使用遠端 SQL 部署的 WSUS 伺服器

您必須同時在前後端伺服器上執行 WSUS (含 SP1) 安裝套件。

**若要在使用遠端 SQL 時升級為 WSUS (含 SP1)**
1.  在前端執行安裝套件但是不使用切換參數，並且選擇升級。

2.  在後端執行安裝套件但是不使用切換參數，並且選擇升級。

#### 問題 10：如果在升級為 WSUS (含 SP1) 之前就變更電腦名稱，可能會導致升級失敗

如果在安裝 WSUS RTM 之後及升級為 WSUS (含 SP1) 之前變更電腦名稱，WSUS (含 SP1) 升級可能會失敗。

使用下列指令碼移除並重新新增 ASPNET 和 WSUS Administrators 群組。然後再次執行升級。

        ```
| ![](images/Cc708486.note(WS.10).gif)附註         |
|-------------------------------------------------------------------------------|
| 您可能必須以實際內容存放位置的路徑來取代最後一行的 &lt;ContentDirectory&gt;。 |

WSUS 讀我檔案的原始內容如下
---------------------------

下列為 WSUS 讀我檔案的原始內容。WSUS (含 SP1) *並未*提及下列任何問題。此處併入這項內容方便您查閱。

在您開始前
----------

#### 問題 1：必須安裝 IIS

Microsoft® Windows Server™ Update 服務 (WSUS) 要求安裝網際網路資訊服務 (IIS)。但是，在 Microsoft Windows Server 2003 和 Microsoft Windows® 2000 Server 上依預設不會安裝 IIS，因此 Windows Server Update Services 安裝程式可能無法繼續進行，會顯示錯誤訊息表示尚未安裝 IIS。

安裝 IIS：

1.  開啟 \[控制台\]。
2.  連按兩下 \[新增或移除程式\]。
3.  按一下 \[新增/移除 Windows 元件\]。
4.  在 \[元件\] 清單中，按一下 \[Application Server\]。
5.  按一下 \[詳細資料\]。
6.  選取 \[ASP.NET\] 核取方塊。啟用 \[網路 COM+ 存取\]，\[網際網路資訊服務 (IIS)\] 將會被自動選取。
7.  選取 \[網際網路資訊服務 (IIS)\]，然後按一下 \[詳細資料\] 以檢視 IIS 選用元件的清單。
8.  選取所有要安裝的選用元件。World Wide Web 服務選用元件包含重要的子元件，例如動態伺服器網頁元件和遠端管理 (HTML)。若要檢視並選取這些子元件，請按一下 \[ World Wide Web 服務\]，然後按一下 \[詳細資料\]。按一下 \[確定\]，直到返回 \[Windows 元件精靈\]。
9.  按一下 \[下一步\]，並且完成 \[Windows 元件精靈\]。
10. 安裝 IIS 之後，請執行 Windows Server Update Services 安裝程式。

#### 問題 2：如果是執行 Windows 2000 Server 的伺服器，則 IIS 中至少要出現一個網站，才能安裝 WSUS

如果執行安裝程式時，IIS 中沒有出現任何網站，Windows Server Update Services 安裝程式可能無法建立網站。例如，如果有一個 Software Update Services (SUS) 1.0 站台是 IIS 中的唯一站台，而您在安裝 WSUS 之前就已經將它刪除，就可能會發生這種情況。

在此情況下，您需要使用網際網路資訊服務 (IIS) 管理員嵌入式管理單元來建立新網站。完成之後，您可以在 WSUS 安裝期間選取此站台或指定新站台。

如果您已經嘗試安裝 WSUS，而安裝程式因沒有站台存在而失敗，則請開啟 IIS 管理員嵌入式管理單元，並且刪除 "Web Site \#1" 站台。然後遵循先前描述的步驟，並且再次執行安裝程式。

#### 問題 3：安裝必要元件

#### 軟體需求

下表顯示每個受支援作業系統所需的軟體。執行 WSUS 安裝程式前，請先確定 WSUS 伺服器符合此需求清單。如果其中的任何更新要求在完成安裝時重新啟動電腦，則應該先執行重新啟動，再安裝 WSUS。

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >作業系統</th>
<th style="border:1px solid black;" >需求</th>
<th style="border:1px solid black;" >下載</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">所有作業系統</td>
<td style="border:1px solid black;">Microsoft Internet Information Services (IIS) 5.0</td>
<td style="border:1px solid black;">從作業系統安裝。
請參閱問題 1：必須安裝 IIS。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">所有作業系統</td>
<td style="border:1px solid black;">背景智慧型傳送服務 (BITS) 2.0</td>
<td style="border:1px solid black;">如果是 Windows Server 2003 作業系統，請參閱下載中心 (<a href="http://go.microsoft.com/fwlink/?linkid=47251">http://go.microsoft.com/fwlink/?LinkId=47251</a>) 的＜KB842773：Background Intelligent Transfer Service (BITS) 2.0 與 WinHTTP 5.1 Windows Server 2003 更新＞。
如果是 Windows Server 2000 作業系統，請參閱下載中心 (<a href="http://go.microsoft.com/fwlink/?linkid=46794">http://go.microsoft.com/fwlink/?LinkId=46794</a>) 的＜KB842773：Background Intelligent Transfer Service (BITS) 2.0 與 WinHTTP 5.1 Windows Server 2000 更新＞。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003</td>
<td style="border:1px solid black;">適用於 Windows Server 2003 的 Microsoft .NET Framework 1.1 Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47358">適用於 Windows Server 2003 的 Microsoft .NET Framework 1.1 Service Pack 1</a>
另外您也可以選擇造訪 <a href="http://go.microsoft.com/fwlink/?linkid=47370">Windows Update</a>檢查是否有重大更新和 Service Pack」；安裝適用於 Windows Server 2003 的 Microsoft .NET Framework 1.1 Service Pack 1。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003</td>
<td style="border:1px solid black;">100% 與 Microsoft SQL 相容的資料庫軟體</td>
<td style="border:1px solid black;">N/A</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">100% 與 Microsoft SQL 相容的資料庫軟體</td>
<td style="border:1px solid black;">如果您不是使用 Microsoft SQL Server 2000，則可安裝 Microsoft SQL Server 2000 Desktop Engine (MSDE 2000)。這需要數個步驟。如需相關資訊，請參閱下面的＜在 Windows 2000 上安裝 MSDE＞。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Microsoft Internet Explorer 6.0 Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47359">Internet Explorer 6 Service Pack 1</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Microsoft .NET Framework 1.1 版可轉散發套件</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47369">Microsoft .NET Framework 1.1 版可轉散發套件</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Microsoft .NET Framework 1.1 Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47368">Microsoft .NET Framework 1.1 Service Pack 1</a>
另外您也可以選擇造訪 <a href="http://go.microsoft.com/fwlink/?linkid=47370">Windows Update</a>檢查是否有重大更新和 Service Pack；安裝適用於 Windows Server 2000 的 Microsoft .NET Framework 1.1 Service Pack 1。</td>
</tr>
</tbody>
</table>
 

除了這些需求以外，如有必要，WSUS 可能會在您的伺服器上安裝或設定 ASP.NET 1.1 版。(WSUS 安裝程式會設定 ASP.NET)。

#### 在 Windows 2000 上安裝 MSDE 2000

如果您是針對 WSUS 使用 Windows 2000，而且沒有 Microsoft SQL Server 2000 的存取權，則應該先安裝 Microsoft SQL Server 2000 Desktop Engine (MSDE)，再執行 WSUS 安裝程式。如果您已在 WSUS 伺服器上安裝 MSDE，則無須針對 WSUS 設定特殊執行個體。您可以只在 WSUS 安裝程序期間指出現有的執行個體名稱即可。

要在 Windows 2000 Server 上安裝 MSDE 需遵循四個步驟。首先，必須下載 MSDE 封存並展開至 WSUS 伺服器上的資料夾。接下來使用命令提示字元和命令列選項來執行 MSDE 安裝程式、設定 SA 密碼，並指派 WSUS 作為執行個體名稱。然後當 MSDE 安裝完成時，應確認 WSUS 執行個體正當做 NT 服務執行中。最後，必須將安全性修補程式新增至 MSDE 以保護 WSUS 伺服器。

#### 步驟 1：下載並展開 MSDE 封存

您必須下載 MSDE 封存並展開至 WSUS 伺服器上的資料夾。請參閱 [Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Release A](http://go.microsoft.com/fwlink/?linkid=47366)。

#### 步驟 2：安裝 MSDE

使用命令提示字元和命令列選項來執行 MSDE 安裝程式、設定 SA 密碼，並指派 WSUS 作為執行個體名稱。當 MSDE 安裝完成時，應確認 WSUS 執行個體正當做 NT 服務執行中。

若要安裝 MSDE、設定 SA 密碼以及指派執行個體名稱：

1.  在命令提示字元中，瀏覽至＜步驟 1：下載並展開 MSDE 封存＞中所指定的 MSDE 安裝資料夾。
2.  鍵入下列字元：**setup sapwd="***password***" instancename=WSUS**
    其中 *password* 是這個 MSDE 執行個體上的 SA 帳戶的強式密碼，而 **instancename** 是資料庫執行個體的名稱。另外您也可以針對 WSUS 資料庫使用預設的執行個體名稱 (而不使用 "WSUS")。如果您選擇要這樣做，則不需要在命令列參數中鍵入 **instancename=WSUS**。這項命令會啟動 MSDE 安裝程式、設定 SA 密碼，並將這個 MSDE 執行個體的名稱設定為您所指定的任意值。

#### 步驟 3：確認已安裝 MSDE 的 WSUS 執行個體。

1.  按一下 \[開始\]，然後按一下 \[執行\]。
2.  在 \[開啟\] 方塊中鍵入 **services.msc**，然後按一下 \[確定\]。

向下捲動服務清單，並且確認名為 MSSQL$WSUS (如果您使用 "WSUS" 當做執行個體名稱) 或 MSSQLSERVER (如果您使用預設的執行個體名稱) 的服務存在。

#### 步驟 4：啟動 MSDE 執行個體。

MSDE 安裝結束時，您必須啟動執行個體。如果您使用 "WSUS" 當做執行個體名稱，則要啟動 "MSSQL$WSUS"。如果您使用預設的執行個體名稱，則要啟動 MSSQLSERVER。除非啟動此服務，否則 WSUS 無法使用資料庫執行個體。

#### 步驟 5：更新 MSDE

您必須下載並安裝公告 [MS03-031 中描述的安全性修補程式：SQL Server](http://go.microsoft.com/fwlink/?linkid=47364)的累計安全性修補程式。

若要下載安全性修補程式，請參閱 [SQL Server 2000 (32 位元) 安全性補充程式 MS03-031](http://go.microsoft.com/fwlink/?linkid=47363) (英文)。

#### 問題 4：最低磁碟空間需求

下列是安裝 Windows Server Update Services 的最低磁碟空間需求：

-   系統磁碟分割上至少要有 1 GB
-   存放資料庫檔案的磁碟區至少要有 2 GB
-   6 GB，視內容投影數目而定

#### 問題 5：您必須先使用 \[新增或移除程式\] 解除安裝舊版 WSUS，才能安裝最新版本

如果您計畫在已安裝 Windows Update Services Beta 1 或 Beta 2 的伺服器上安裝 Windows Server Update Services，則必須先在 \[控制台\] 中使用 \[新增或移除程式\] 解除安裝舊版。

#### 問題 6：WSUS 需要在 SQL Server 中開啟巢狀觸發程序選項

依預設開啟此選項，不過 SQL Server 系統管理員可以將它關閉。

如果您打算使用 SQL Server 資料庫當做 Windows Server Update Services 資料存放區，則 SQL Server 系統管理員應確認已在伺服器上開啟巢狀觸發程序選項，然後 WSUS 系統管理員才能安裝 WSUS 並在安裝期間指定資料庫。

WSUS 安裝程式會開啟 RECURSIVE\_TRIGGERS 選項 (此為資料庫特定選項)，但是並不會開啟巢狀觸發程序選項 (此為伺服器全域選項)。

若要查看是否已開啟巢狀觸發程序，請使用下列命令：

**sp\_configure 'nested triggers'**

若要在 SQL Server 上開啟巢狀觸發程序選項，請在執行 SQL Server 的電腦上從批次檔執行下列命令：

**sp\_configure 'nested triggers', 1**

**GO**

**RECONFIGURE**

**GO**

#### 問題 7：WSUS 安裝程式命令列參數

您可以執行 WSUS 的自動安裝。如需命令列參數的相關資訊，請參閱[部署 Microsoft Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=41777)中的＜附錄 A：自動安裝＞(英文)。

已知問題
--------

#### 問題 1：IIS 鎖定精靈

如果您是在執行 Windows 2000 Server 的電腦上執行網際網路資訊服務 (IIS)，請從 Microsoft TechNet 的 IIS 鎖定工具頁面安裝最新版本的 IIS 鎖定精靈 (其中包含 URLScan)。Microsoft 強烈建議您安裝這項工具，以協助保護 IIS 伺服器的安全。IIS 鎖定精靈的運作方式是藉由關閉不需要的 IIS 功能，從而降低安全性風險。

| ![](images/Cc708486.note(WS.10).gif)附註                                                               |
|-------------------------------------------------------------------------------------------------------------------------------------|
| WSUS 安裝程式不會安裝這些元件。您必須自行手動安裝。您無須在執行 Windows Server 2003 的電腦上安裝 IIS 鎖定，因為該功能已內建於其中。 |

#### 問題 2：不支援直接在資料庫中變更 WSUS 設定

Windows Server Update Services 會將其設定資料儲存於資料庫中 (MSDE 或 SQL Server)。但是不支援直接存取資料庫來變更設定資料。系統管理員不應該嘗試採用此方法來修改 WSUS 設定。變更 WSUS 設定受支援的方法為使用 WSUS 主控台或呼叫 WSUS API。

#### 問題 3：您必須啟用動態指令碼處理才能存取 WSUS 系統管理站台

在系統管理員的工作站上，您必須將 Internet Explorer 設定為允許動態指令碼處理，然後才能使用 Internet Explorer 來存取 WSUS 系統管理站台。

#### 問題 4：在 WSUS 安裝期間將會重新啟動 IIS

Windows Server Update Services 安裝程式重新啟動 IIS 前不會發出通知。這可能會影響組織內的現有網站。

#### 問題 5：變更 WSUS 或 SMS 管理點 (MP) 虛擬目錄存取

依預設，Windows Server Update Services 的內容虛擬目錄會設定為匿名存取。如果您將這項設定變更為需要驗證，則用戶端將收到驗證錯誤訊息，並在存取時遭到拒絕而無法下載更新。這是一個已知的問題，在需要隱含驗證時，Winhttp.dll 使用錯誤的驗證環境，因而導致驗證質詢失敗。若要避免這個問題，請確定 WSUS 伺服器和 SMS MP 已設定為可匿名存取 IIS 虛擬目錄。

#### 問題 6：當在 Windows Small Business Server 2003 上安裝 WSUS 時，必須修改預設網站 WSUS vroot 的存取設定，以便允許 WSUS 用戶端自行從伺服器進行更新

WSUS 伺服器會在預設網站 (連接埠 80) 的主目錄下安裝 SelfUpdate 和 ClientWebService 這兩個 vroot 和一些檔案。這可讓用戶端透過預設網站自行更新。依預設，在 Windows Small Business Server 2003 上是將預設網站設定為拒絕存取該伺服器以外的任何 IP 或 localhost。這表示系統拒絕用戶端存取 SelfUpdate 和 ClientWebService vroot，因此用戶端無法自行更新。若要授予用戶端存取權以便自行更新，請在預設網站的 SelfUpdate 和 ClientWebService vroot 上完成下列步驟。

1.  依序按一下 vroot \[內容\]、\[目錄安全設定\]、\[IP 位址及網域名稱限制\] 及 \[編輯\]。
2.  選取 \[授予存取權\]，再按一下 \[確定\]。關閉所有屬性頁。

#### 問題 7：在 Small Business Server 上安裝 WSUS - 整合問題

-   如果 Windows Small Business Server 2003 使用 ISA Proxy 伺服器來存取網際網路，則必須在 \[設定\] 使用者介面中手動輸入下列項目：Proxy 伺服器設定、Proxy 伺服器名稱及連接埠。
-   如果 ISA 採用 Windows 驗證，則應以「網域\\使用者」格式 (此使用者屬於 Internet Users 群組) 輸入 Proxy 伺服器認證。

#### 問題 8：將某個電腦群組中的電腦移動至其他群組時，可能最多需要一個小時，才能從系統管理主控台看到該電腦出現在新群組中

當電腦第一次指派至目標群組時，會根據群組資訊修改此電腦上的資料。該資料會定期或每小時重新整理一次。因此，將電腦從某個電腦群組移動至其他群組時，最多可能需要一個小時，才會在用戶端上重新整理該資訊並在 WSUS 系統管理主控台上顯示為已變更。

#### 問題 9：如果在成員伺服器上安裝 WSUS，然後要將成員伺服器升級為網域控制站，則應先解除安裝 WSUS

如果在成員伺服器上安裝 WSUS，然後要將成員伺服器升級為網域控制站，則需執行下列步驟：

1.  解除安裝 WSUS。
2.  將伺服器升級為網域控制站。
3.  重新安裝 WSUS。

#### 問題 10：如果要將 WSUS 伺服器從網域控制站降級為成員伺服器，則需先解除安裝 WSUS

如果在網域控制站執行 WSUS 伺服器，並要將網域控制站降級為成員伺服器，則需完成下列步驟：

1.  解除安裝 WSUS 並保留資料庫。
2.  建立稱為 ASPNET 的使用者帳戶。
3.  在命令提示字元中鍵入 **aspnet\_regiis -i**。
4.  重新安裝 WSUS 並使用保留的資料庫。

#### 問題 11：如果在安裝 WSUS 之後安裝 .NET Framework 1.0 或 2.0，則不會出現 WSUS 系統管理主控台

這是因為 .NET Framework 1.0 已向 IIS 註冊，而且該 WSUS 伺服器需要 .NET Framework 1.1。若要解決此問題，請開啟 aspnet\_regiis.exe 並執行下列命令，其中 *website id* 是下列登錄機碼中所包含的值：

HKLM\\Software\\Microsoft\\WindowsUpdateServices\\Server\\Setup\\IISTargetWebsiteIndex

-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*website id*&gt;\\ROOT\\ReportingWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*website id*&gt;\\ROOT\\ClientWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*website id*&gt;\\ROOT\\SimpleAuthWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*website id*&gt;\\ROOT\\WSUSAdmin
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*website id*&gt;\\ROOT\\AdministrationWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*website id*&gt;\\ROOT\\ServrSyncWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*website id*&gt;\\ROOT\\DssAuthWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*website id*&gt;\\ROOT\\Content

#### 問題 12：遠端 SQL 限制

若 WSUS 應用程式其他部分不是安裝在執行資料庫軟體的電腦上，則 WSUS 僅提供有限的支援。

-   在遠端 SQL 配對中，您不能使用 Windows 2000 Server 作為前端電腦。
-   您不能將設定為網域控制站的伺服器作為遠端 SQL 配對的前端或後端。
-   您不能在後端電腦上使用 WMSDE 或 MSDE 作為資料庫軟體。
-   如果終端機服務安裝於遠端伺服器上，而且在應用程式模式中執行，則安裝遠端 SQL Server (以當做 WSUS 資料庫使用) 會失敗。將 SQL Server 安裝至終端機服務伺服器時，您必須執行下列步驟：
    1.  執行安裝程式之前，請先開啟命令提示字元並且鍵入："change user /install"
    2.  執行 SQL Server 安裝程式。
    3.  執行安裝程式之後，在命令提示字元中鍵入："change user /execute"
-   您必須同時為前後端電腦的本機系統管理員安全性群組的成員，才能安裝遠端 SQL Server WSUS 資料庫。
-   如需遠端 SQL 問題的相關資訊，請參閱 [部署 Microsoft Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=41777) 中的＜附錄 C：遠端 SQL＞(英文)。

#### 問題 13：複本下游伺服器擁有的核准可能比上層的上游伺服器來得少

複本下游伺服器擁有的核准可能比上層的上游伺服器來得少。原因是除非內容完成在上游伺服器上的下載，否則安裝核准將不會傳遞到下游伺服器。

#### 問題 14：如果初始同步化失敗，請重試

如果同步化失敗，您的第一個疑難排解動作應該是再試一次同步處理將伺服器。如果後續同步化失敗，請使用 WSUS 操作手冊中的疑難排解資訊。

#### 問題 15：當您嘗試存取 WSUS 管理主控台時，出現 System.IO.FileNotFoundException 錯誤訊息

如果看到下列錯誤訊息，您可能需要調整網路服務或 ASP.NET 帳戶的權限：

System.IO.FileNotFoundException:找不到檔案或組件名稱 *xxxxxx*.dll 或其中一項相依性

其中 *xxxx* 是隨機名稱。

若要在 Windows Server 2003 作業系統中解決此問題，請授予 Network Service 帳戶對 %systemroot%\\Temp 的讀取/寫入權限。在 Windows 2000 Server 中，請授予 ASP.NET 帳戶對 %systemroot%\\Temp 的讀取/寫入權限。

#### 問題 16：SQL 安全性更新 MS03-031 (KB815495)

即使在用戶端上的安裝實際上是失敗的，這項更新在 WSUS 伺服器仍可能顯示為已安裝。這會導致封裝被退回用戶端。您可以取消核准在伺服器上的更新以解決此問題。

#### 問題 17：在 RTM 升級期間遺失 IIS 設定。

如果在舊版 WSUS (例如 RC) 的伺服器上安裝 WSUS RTM，WSUS RTM 將會解除安裝較舊版本，然後再安裝新版本。這表示在 IIS 中與 WSUS 相關聯的 vroot 及檔案將被刪除。

如果是在預設網站上安裝 WSUS，則會遺失任何針對 WSUS vroot 所做的 WSUS 相關設定。例如，如果為了保護 WUS，您曾針對 SSL 設定 WSUS vroot，則您將需要在安裝 WSUS 的 RTM 版本後，重新設定一次。附註：您將會在 WSUS 主控台收到未啟用 SSL 的通知。

如果您是在預設網站以外的網站上安裝 WSUS，則會遺失 WSUS 網站層級的所有其他設定。

#### 問題 18：使用主機標頭

如果想在 IIS 中指派主機標頭值到預設的網站 (WSUS 網站)，則您需要在不具有主機標頭值之預設網站的 IP 位址清單中，加入 \[全未指派\] 或一個已指派的 IP 位址。也應該將它加入非預設的網站中

**警告**：這可能會破壞 Microsoft SharePoint 和 Exchange 功能。

#### 問題 19：WSUS 主控台的 URL 需要加入至已啟用 Internet Explorer 堅固功能之電腦上的 \[信任的網站\] 清單及 \[近端內部網路\] 網頁內容區域

如果您在電腦上啟用了 Internet Explorer 堅固功能 (也就是「Microsoft Windows Server 2003 Internet Explorer 增強安全性設定」元件)，但未將該 WSUS 主控台加入 \[信任的網站\] 及 \[近端內部網路\] 網頁內容區域，則每次當您在 WSUS 主控台中開啟網頁時，都會提示您輸入使用者認證。

將 WSUS 主控台加入 \[近端內部網路\] 及 \[信任的網站\] 網頁內容區域：

1.  開啟 \[網際網路選項\] (例如，按一下 \[開始\]，指向 \[控制台\]，然後按一下 \[網際網路選項\])。
2.  在 \[安全性\] 索引標籤上，按一下 \[近端內部網路\]，按一下 \[網站\]，按一下 \[進階\]，新增 URL (http://*WSUSServername*/WSUSAdmin)，然後按一下 \[確定\]。
3.  按一下 \[信任的網站\]，按一下 \[網站\]，新增 WSUS 主控台 URL，按一下 \[確定\]，然後再按一下 \[確定\] 來結束 \[網際網路選項\]。

#### 著作權

本文件中所含的資訊代表 Microsoft Corporation 截至發行日期為止，目前對所討論問題持有的觀點。由於 Microsoft 必須因應千變萬化的市場情況，因此請不要將本文件解讀為 Microsoft 的承諾。Microsoft 無法保證文中任何資訊在發行後的準確性。

本文件僅供參考。MICROSOFT 對本文件中的資訊不提供任何明示、暗示或法定之擔保。

使用者有責任遵守所有適用之著作權法。在不限制任何依著作權本得享有之權利的情形下，未經 Microsoft Corporation 書面許可，貴用戶不得為任何目的使用任何形式或方法 (電子、機械、影印、錄音或其他方式) 複製或傳送本文件的任何部分，也不得將本文件的任何部分儲存或放入檢索系統。

Microsoft 可能擁有此文件所提及內容中所含之專利權、專利優先權、商標、著作權，或其他智慧財產權。除非 Microsoft 書面授權合約所明示規定者外，提供本文件並不授予 貴用戶上述專利權、商標、著作權或其他智慧財產權。

除非另有註明，此處所描述之範例公司、組織、產品、網域名稱、電子郵件位址、商標圖樣、人員、地點及事件均屬虛構，並非影射任何真實的公司、組織、產品、網域名稱、電子郵件位址、商標圖樣、人員、地點及事件。

© 2006 Microsoft Corporation.著作權所有並保留一切權利。

Microsoft、SQL Server、Windows 及 Windows Server 係 Microsoft Corporation 在美國及 (或) 其他國家 (地區) 中的註冊商標或商標。

本文件所提及之產品或公司的實際名稱可能為各擁有人所有之商標。
