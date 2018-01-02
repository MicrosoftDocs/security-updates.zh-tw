---
TOCTitle: Windows Server Update Services 讀我檔案
Title: Windows Server Update Services 讀我檔案
ms:assetid: '4244109a-395a-4ff8-9989-ea55ab0964a3'
ms:contentKeyID: 18126152
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc720505(v=WS.10)'
---

Windows Server Update Services 讀我檔案
=======================================

本文件描述會影響 Windows Server Update Services (WSUS) 的已知問題，其中包含安裝 WSUS 的建議及需求。

| ![](images/Cc720505.note(WS.10).gif)附註                                                                                          |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 如果需要本文件的可下載複本，請至 Microsoft 下載中心下載，網址是 [http://go.microsoft.com/fwlink/?LinkId=48126](http://go.microsoft.com/fwlink/?linkid=48126)。 |

在您開始前
----------

#### 問題 1：必須安裝 IIS

Microsoft® Windows Server™ Update Services (WSUS) 需要安裝網際網路資訊服務 (IIS)。但是，在 Microsoft Windows Server 2003 和 Microsoft Windows® 2000 Server 上，依預設不會安裝 IIS，因此 Windows Server Update Services 安裝程式可能無法繼續執行，並會顯示錯誤訊息，表示尚未安裝 IIS。

安裝 IIS：

1.  開啟 \[控制台\]。
2.  按兩下 \[新增或移除程式\]。
3.  按一下 \[新增/移除 Windows 元件\]。
4.  在 \[元件\] 清單中，按一下 \[Application Server\]。
5.  按一下 \[詳細資料\]。
6.  選取 \[ASP.NET\] 核取方塊。\[啟用網路 COM+ 存取\] 及 \[網際網路資訊服務 (IIS)\] 將會自動選取。
7.  選取 \[網際網路資訊服務 (IIS)\]，然後按一下 \[詳細資料\]，以檢視 IIS 選用元件的清單。
8.  選取所有要安裝的選用元件。\[全球資訊網服務\] 選用元件包含重要的子元件，例如動態伺服器網頁元件和遠端管理 (HTML)。若要檢視並選取這些子元件，請按一下 \[全球資訊網服務\]，然後按一下 \[詳細資料\]。按一下 \[確定\]，直到返回 \[Windows 元件精靈\]。
9.  按一下 \[下一步\]，並且完成 \[Windows 元件精靈\]。
10. 安裝 IIS 之後，請執行 Windows Server Update Services 安裝程式。

#### 問題 2：如果伺服器是執行 Windows 2000 Server，則 IIS 中至少要有一個網站，才能安裝 WSUS

如果執行安裝程式時，IIS 中沒有任何網站，Windows Server Update Services 安裝程式可能無法建立網站。例如，如果 IIS 中只有一個 Software Update Services (SUS) 1.0 站台，而您在安裝 WSUS 之前就已經將它刪除，就可能會發生這種情況。

在此情況下，您需要使用 \[網際網路資訊服務 (IIS) 管理員\] 嵌入式管理單元來建立新網站。建立完畢後，您在 WSUS 安裝期間可以選取此站台或指定新站台。

如果您已經嘗試安裝 WSUS，而安裝程式因沒有站台而失敗，則請開啟 IIS 管理員嵌入式管理單元，並且刪除 \[網站 \#1\]。之後，遵循先前描述的步驟，並且再次執行安裝程式。

#### 問題 3：安裝必要元件

#### 軟體需求

下表顯示每個受支援作業系統所需的軟體。執行 WSUS 安裝程式前，請先確定 WSUS 伺服器滿足此需求清單。如果在完成安裝時，其中的任何更新要求重新啟動電腦，則應該先執行重新啟動，再安裝 WSUS。

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
請參閱＜問題 1：必須安裝 IIS＞。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">所有作業系統</td>
<td style="border:1px solid black;">幕後智慧型傳送服務 (BITS) 2.0</td>
<td style="border:1px solid black;">如果是 Windows Server 2003 作業系統，請造訪下載中心　(http://go.microsoft.com/fwlink/?LinkId=47251)，參閱<a href="http://go.microsoft.com/fwlink/?linkid=47251">幕後智慧型傳送服務 (BITS) 2.0 與 WinHTTP 5.1 Windows Server 2003 的更新</a> (KB842773) (英文)。
如果是 Windows Server 2000 作業系統，請造訪下載中心 (http://go.microsoft.com/fwlink/?LinkId=46794)，參閱<a href="http://go.microsoft.com/fwlink/?linkid=46794">幕後智慧型傳送服務 (BITS) 2.0 與 WinHTTP 5.1 Windows 2000 的更新</a> (KB842773) (英文)。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003</td>
<td style="border:1px solid black;">適用於 Windows Server 2003 的 Microsoft .NET Framework 1.1 Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47358">適用於 Windows Server 2003 的 Microsoft .NET Framework 1.1 Service Pack 1</a>(英文)
或者，也可以移至 <a href="http://go.microsoft.com/fwlink/?linkid=47370">Windows Update</a>，掃瞄尋找重大更新與 Service Pack；安裝適用於 Windows Server 2003 的 Microsoft .NET Framework 1.1 Service Pack 1。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003</td>
<td style="border:1px solid black;">完全與 Microsoft SQL 相容的資料庫軟體</td>
<td style="border:1px solid black;">N/A</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">完全與 Microsoft SQL 相容的資料庫軟體</td>
<td style="border:1px solid black;">如果您不是使用 Microsoft SQL Server 2000，則可安裝 Microsoft SQL Server 2000 Desktop Engine (MSDE 2000)。這需要數個步驟完成。如需相關資訊，請參閱以下＜在 Windows 2000 上安裝 MSDE＞。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Microsoft Internet Explorer 6.0 Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47359">Internet Explorer 6 Service Pack 1</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Microsoft .NET Framework 1.1 版可轉散發套件</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47369">Microsoft .NET Framework Version 1.1 版可轉散發套件</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Microsoft .NET Framework 1.1 Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47368">Microsoft .NET Framework 1.1 Service Pack 1</a>
或者，也可以移至 <a href="http://go.microsoft.com/fwlink/?linkid=47370">Windows Update</a>，掃瞄尋找重大更新與 Service Pack；安裝適用於 Windows Server 2000 的 Microsoft .NET Framework 1.1 Service Pack 1。</td>
</tr>
</tbody>
</table>
 

除了這些需求以外，如有必要，WSUS 可能會在您的伺服器上安裝或設定 ASP.NET 1.1 版。(WSUS 安裝程式會設定 ASP.NET)。

#### 在 Windows 2000 上安裝 MSDE 2000

如果 WSUS 是在 Windows 2000 上使用，而且沒有 Microsoft SQL Server 2000 的存取權，則應該先安裝 Microsoft SQL Server 2000 Desktop Engine (MSDE)，再執行 WSUS 安裝程式。如果您已在 WSUS 伺服器上安裝 MSDE，則無須針對 WSUS 設定特殊例項。您只要在 WSUS 安裝程序期間指出現有的例項名稱即可。

在 Windows 2000 Server 上安裝 MSDE 時，有四個步驟。首先，必須下載 MSDE 封存，並展開至 WSUS 伺服器上的資料夾。接下來，使用命令提示字元和命令列選項執行 MSDE 安裝程式、設定 SA 密碼，並指派 WSUS 為例項名稱。然後，當 MSDE 安裝完成時，應確認 WSUS 例項正以 NT 服務的方式執行。最後，您必須將安全性更新新增到 MSDE，以保護 WSUS 伺服器。

#### 步驟 1：下載並展開 MSDE 封存

您必須下載 MSDE 封存，並展開至 WSUS 伺服器上的資料夾。請參閱 [Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Release A](http://go.microsoft.com/fwlink/?linkid=47366)。

#### 步驟 2：安裝 MSDE

使用命令提示字元和命令列選項執行 MSDE 安裝程式、設定 SA 密碼，並指派 WSUS 為例項名稱。當 MSDE 安裝完成時，應確認 WSUS 例項正以 NT 服務的方式執行。

若要安裝 MSDE、設定 SA 密碼及指派例項名稱：

1.  在命令提示字元中，瀏覽至＜步驟 1：下載並展開 MSDE 封存＞所指定的 MSDE 安裝資料夾。
2.  輸入下列字元：**setup sapwd="密碼" instancename=WSUS**
    其中「密碼」是這個 MSDE 例項上的 SA 帳戶的強式密碼，而 **instancename** 是資料庫例項的名稱。另外，您也可以使用 WSUS 資料庫的預設例項名稱 (而不使用 "WSUS")。如果您選擇要這樣做，則不需要在命令列參數中輸入 **instancename=WSUS**。這項命令會啟動 MSDE 安裝程式、設定 SA 密碼，並將這個 MSDE 例項的名稱設定為您所指定的任意值。

#### 步驟 3：確認已安裝 MSDE 的 WSUS 例項。

您應確認可以看到 MSDE 的 WSUS 例項。

1.  按一下 \[開始\]，再按一下 \[執行\]。
2.  在 \[開啟\] 方塊中輸入 **services.msc**，然後按一下 \[確定\]。

向下捲動服務清單，並確認名為 MSSQL$WSUS (如果您使用 "WSUS" 當做例項名稱) 或 MSSQLSERVER (如果您使用預設的例項名稱) 的服務存在。

#### 步驟 4：啟動 MSDE 例項。

MSDE 安裝結束時，您必須啟動例項。如果您使用 "WSUS" 當做例項名稱，則要啟動 "MSSQL$WSUS"。如果您使用預設的例項名稱，則要啟動 MSSQLSERVER。除非啟動此服務，否則 WSUS 無法使用資料庫例項。

#### 步驟 5：更新 MSDE

您必須下載並安裝公告 [MS03-031：SQL Server 累積安全性補充程式](http://go.microsoft.com/fwlink/?linkid=47364)中描述的安全性更新。

若要下載安全性更新，請參閱 [SQL Server 2000 (32 位元) 安全性修補程式 MS03-031](http://go.microsoft.com/fwlink/?linkid=47363)。

#### 問題 4：最低磁碟空間需求

下列是安裝 Windows Server Update Services 的最低磁碟空間需求：

-   系統磁碟分割上至少要有 1 GB
-   存放資料庫檔案的磁碟區至少要有 2 GB
-   6 GB，視內容投影數目而定

#### 問題 5：您必須先使用 \[新增或移除程式\] 解除安裝舊版 WSUS，才能安裝最新版本

如果您計畫在已安裝 Windows Update Services Beta 1 或 Beta 2 的伺服器上安裝 Windows Server Update Services，則必須先在 \[控制台\] 中使用 \[新增或移除程式\] 解除安裝舊版。

#### 問題 6：WSUS 需要 SQL Server 啟用巢狀觸發程序選項

此選項依預設為啟用，但 SQL Server 系統管理員可以將其關閉。

如果您打算使用 SQL Server 資料庫當做 Windows Server Update Services 資料存放區，則 SQL Server 系統管理員應確認伺服器上已啟用巢狀觸發程序選項，然後 WSUS 系統管理員才能安裝 WSUS，並在安裝期間指定該資料庫。

WSUS 安裝程式會開啟 RECURSIVE\_TRIGGERS 選項 (此為資料庫特定選項)，但是並不會啟用巢狀觸發程序選項 (此為伺服器全域選項)。

若要查看巢狀觸發程序是否已啟用，請使用下列命令：

**sp\_configure 'nested triggers'**

若要在 SQL Server 上啟用巢狀觸發程序選項，請在執行 SQL Server 的電腦上，利用批次檔執行下列命令：

**sp\_configure 'nested triggers', 1**

**GO**

**RECONFIGURE**

**GO**

#### 問題 7：WSUS 安裝程式命令列參數

您可以執行 WSUS 的自動安裝。如需命令列參數的相關資訊，請參閱[部署 Microsoft Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=41777) 中的＜附錄 A：自動安裝＞(英文)。

已知問題
--------

#### 問題 1：IIS 鎖定精靈

如果您是在執行 Windows 2000 Server 的電腦上執行網際網路資訊服務 (IIS)，請從 Microsoft TechNet 的 \[IIS Lockdown Tool\] (IIS 鎖定工具) 頁面安裝最新版本的 IIS 鎖定精靈 (其中包含 URLScan)。Microsoft 強烈建議您安裝這個工具，以協助保護 IIS 伺服器的安全。IIS 鎖定精靈的運作方式是藉由關閉不需要的 IIS 功能，從而降低安全性風險。

| ![](images/Cc720505.note(WS.10).gif)附註                                                               |
|-------------------------------------------------------------------------------------------------------------------------------------|
| WSUS 安裝程式不會安裝這些元件。您必須自行手動安裝。您無需在執行 Windows Server 2003 的電腦上安裝 IIS 鎖定，因為該功能已內建於其中。 |

#### 問題 2：不支援在資料庫中直接變更 WSUS 設定

Windows Server Update Services 會將其設定資料儲存於資料庫中 (MSDE 或 SQL Server)。不過，不支援直接存取資料庫來變更設定資料。系統管理員不應嘗試採用此方法來修改 WSUS 設定。受支援的 WSUS 設定變更方法是使用 WSUS 控台或呼叫 WSUS API。

#### 問題 3：您必須啟用動態指令碼處理，才能存取 WSUS 系統管理站台

在系統管理員的工作站上，您必須將 Internet Explorer 設定為允許動態指令碼處理，然後才能使用 Internet Explorer 存取 WSUS 系統管理站台。

#### 問題 4：IIS 在 WSUS 安裝期間會重新啟動

Windows Server Update Services 安裝程式會無預警地重新啟動 IIS。這可能會影響到組織內的現有網站。

#### 問題 5：變更 WSUS 或 SMS 管理點 (MP) 虛擬目錄存取

依預設，Windows Server Update Services 的內容虛擬目錄會設定為匿名存取。如果您將這項設定變更為需要驗證，則用戶端將收到驗證錯誤，並在存取時遭到拒絕，而無法下載更新。這是一個已知的問題，Winhttp.dll 需要隱含驗證時，卻使用錯誤的驗證環境，因而導致驗證質詢失敗。若要避免這個問題，請確定 WSUS 伺服器和 SMS MP 已設定為可匿名存取 IIS 虛擬目錄。

#### 問題 6：當在 Windows Small Business Server 2003 上安裝 WSUS 時，必須修改預設網站 WSUS 的 vroot 存取設定，以便允許 WSUS 用戶端自行從伺服器進行更新

WSUS 伺服器會在預設網站 (連接埠 80) 的主目錄下安裝 SelfUpdate 和 ClientWebService 這兩個 vroot 和一些檔案。這可讓用戶端透過預設網站自行更新。在 Windows Small Business Server 2003 上，依預設是將預設網站設定為拒絕存取該伺服器以外的任何 IP 或 localhost。這表示，系統拒絕用戶端存取 SelfUpdate 和 ClientWebService 等 vroot，因此用戶端無法自行更新。若要將存取權授予用戶端，以便用戶端自行更新，請在預設網站的 SelfUpdate 和 ClientWebService vroot 上完成下列步驟。

1.  依序按一下 vroot \[內容\]、\[目錄安全性\]、\[IP 位址及網域名稱限制\] 及 \[編輯\]。
2.  選取 \[授予存取權\]，再按一下 \[確定\]。關閉所有內容頁面。

#### 問題 7：在 Small Business Server 上安裝 WSUS - 整合問題

-   如果 Windows Small Business Server 2003 使用 ISA Proxy 伺服器來存取網際網路，則必須在 \[設定\] 的使用者介面中手動輸入下列項目：Proxy 伺服器設定、Proxy 伺服器名稱及連接埠。
-   如果 ISA 採用 Windows 驗證，則應以「網域\\使用者」格式 (此使用者屬於 Internet Users 群組) 輸入 Proxy 伺服器認證。

#### 問題 8：將某個電腦群組中的電腦移動至其他群組時，可能最多需要一個小時，才能從系統管理主控台看到該電腦出現在新群組中

第一次將電腦指派至目標群組時，會使用群組資訊修改此電腦上的資料。該資料會定期或每小時重新整理一次。因此，將電腦從某個電腦群組移動至其他群組時，最多可能需要一個小時，才能在用戶端上重新整理該資訊，並在 WSUS 系統管理主控台上顯示為已變更。

#### 問題 9：如果在成員伺服器上安裝 WSUS，然後要將成員伺服器升級為網域控制站，應先解除安裝 WSUS

如果在成員伺服器上安裝 WSUS，然後要將成員伺服器升級為網域控制站，則需執行下列步驟：

1.  解除安裝 WSUS。
2.  將伺服器升級為網域控制站。
3.  重新安裝 WSUS。

#### 問題 10：如果要將 WSUS 伺服器從網域控制站降級為成員伺服器，應先解除安裝 WSUS

如果在網域控制站執行 WSUS 伺服器，並要將網域控制站降級為成員伺服器，則需完成下列步驟：

1.  解除安裝 WSUS 並保留資料庫。
2.  建立稱為 ASPNET 的使用者帳戶。
3.  在命令提示字元中輸入 **aspnet\_regiis -i**。
4.  重新安裝 WSUS 並使用保留的資料庫。

#### 問題 11：如果在安裝 WSUS 之後才安裝 .NET Framework 1.0 或 2.0，則不會出現 WSUS 系統管理主控台

這是因為 .NET Framework 1.0 已向 IIS 登錄，而且該 WSUS 伺服器需要 .NET Framework 1.1。若要解決此問題，請開啟 aspnet\_regiis.exe 並執行下列命令，其中*網站識別碼*是下列登錄機碼中所包含的值：

HKLM\\Software\\Microsoft\\WindowsUpdateServices\\Server\\Setup\\IISTargetWebsiteIndex

-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;網站識別碼&gt;\\ROOT\\ReportingWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;網站識別碼&gt;\\ROOT\\ClientWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;網站識別碼&gt;\\ROOT\\SimpleAuthWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;網站識別碼&gt;\\ROOT\\WSUSAdmin
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;網站識別碼&gt;\\ROOT\\AdministrationWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;網站識別碼&gt;\\ROOT\\ServrSyncWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;網站識別碼&gt;\\ROOT\\DssAuthWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;網站識別碼&gt;\\ROOT\\Content

#### 問題 12：遠端 SQL 限制

若執行資料庫軟體的電腦不是 WSUS 應用程式其他部分所在的電腦，則 WSUS 僅提供有限的支援。

-   在遠端 SQL 配對中，您不能使用 Windows 2000 Server 作為前端電腦。
-   設定為網域控制站的伺服器不能當作遠端 SQL 配對的前端或後端。
-   您不能在後端電腦上使用 WMSDE 或 MSDE 作為資料庫軟體。
-   如果終端機服務已安裝在遠端伺服器上，而且以應用程式模式執行，則遠端 SQL Server (做為 WSUS 資料庫使用) 的安裝程式會失敗。在終端機服務伺服器上安裝 SQL Server 時，您必須執行下列操作：
    1.  執行安裝程式之前，請先開啟命令提示字元，並輸入：**change user /install**
    2.  執行 SQL Server 安裝程式。
    3.  執行安裝程式之後，在命令提示字元中輸入：**change user /execute**
-   您必須同時是前端與後端電腦的本機系統管理員安全性群組的成員，才能安裝遠端 SQL Server WSUS 資料庫。
-   如需遠端 SQL 問題的相關資訊，請參閱[部署 Microsoft Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=41777) 中的＜附錄 C：遠端 SQL＞(英文)。

#### 問題 13：複本下游伺服器擁有的核准可能比上層的上游伺服器來得少

複本下游伺服器擁有的核准可能比上層的上游伺服器來得少。這是因為，內容在上游伺服器上完成下載前，安裝核准將不會傳遞到下游伺服器。

#### 問題 14：如果同步處理失敗，請重試同步處理

如果同步處理失敗，您可能會收到錯誤訊息。如果發生這種狀況，您應先嘗試同步處理。

#### 問題 15：嘗試存取 WSUS 管理主控台時，出現 System.IO.FileNotFoundException 錯誤訊息

如果看到下列錯誤訊息，您可能需要調整網路服務或 ASP.NET 帳戶的權限：

System.IO.FileNotFoundException:找不到檔案或組件名稱 *xxxxxx*.dll 或其相依性的其中之一

其中 *xxxx* 是隨機名稱。

若要在 Windows Server 2003 作業系統中解決此問題，請將 %systemroot%\\Temp 的讀取/寫入權限授予 Network Service 帳戶。在 Windows 2000 Server 中，請將 %systemroot%\\Temp 的讀取/寫入權限授予 ASP.NET 帳戶。

#### 問題 16：SQL 安全性更新 MS03-031 (KB815495)

即使實際上在用戶端上的安裝是失敗的，這項更新在 WSUS 伺服器仍可能顯示為已安裝。這可能會導致封裝再提供給用戶端。您可以取消核准伺服器上的這項更新，以解決此問題。

#### 問題 17：IIS 設定在 RTM 升級期間遺失。

如果在安裝有舊版 WSUS (例如 RC) 的伺服器上安裝 WSUS RTM，WSUS RTM 將會解除安裝較舊版本，然後再安裝新版本。這表示，IIS 中與 WSUS 相關聯的 vroot 及檔案將會刪除。

如果是在預設網站上安裝 WSUS，則會遺失任何針對 WSUS vroot 所做的 WSUS 相關設定。例如，如果您已為了保護 WSUS 而針對 SSL 設定 WSUS vroot，則在安裝 WSUS 的 RTM 版本後，需要重新設定一次。附註：您將會在 WSUS 主控台收到 SSL 未啟用的通知。

如果您是在預設網站以外的網站上安裝 WSUS，則會遺失 WSUS 網站層級的所有其他設定。

#### 問題 18：使用主機標頭

如果想在 IIS 中為預設網站 (WSUS 網站) 指派主機標頭值，則您需要新增 \[全未指派\] 或一個已指派的 IP 位址新增到 IP 位址清單，但不指派主機標頭值給預設網站。這也應該新增至非預設網站中

**警告**：如此可能會破壞 Windows® SharePoint® Services 與 Exchange 的功能。

#### 問題 19：在已啟用 Internet Explorer 增強的電腦上，WSUS 主控台的 URL 需要新增至 \[信任的網站\] 清單及 \[近端內部網路\] 內容區域

如果您在電腦上啟用了 Internet Explorer 增強 (也就是「Microsoft Windows Server 2003 Internet Explorer 增強式安全性設定」元件)，但未將該 WSUS 主控台加入 \[信任的網站\] 及 \[近端內部網路\] 內容區域，則每次當您在 WSUS 主控台中開啟網頁時，都會提示您輸入使用者認證。

若要將 WSUS 主控台加入 \[近端內部網路\] 及 \[信任的網站\] 內容區域：

1.  開啟 \[網際網路選項\] (例如，按一下 \[開始\]，指向 \[控制台\]，然後按一下 \[網際網路選項\])。
2.  在 \[安全性\] 索引標籤上，按一下 \[近端內部網路\]，按一下 \[網站\]，按一下 \[進階\]，新增 URL (http://*WSUSServername*/WSUSAdmin)，然後按一下 \[確定\]。
3.  按一下 \[信任的網站\]，按一下 \[網站\]，新增 WSUS 主控台 URL，按一下 \[確定\]，然後再按一下 \[確定\] 來結束 \[網際網路選項\]。

#### 問題 20：從 WSUS 候選版本升級失敗

從 WSUS 候選版本升級時可能會失敗，因為自行更新樹狀目錄發生問題。如果在嘗試升級的同時，有多個用戶端自行更新，就可能發生這種狀況。

若要解決這個問題：

1.  中斷 WSUS 伺服器與網路的連線，確保用戶端無法連線到 WSUS 伺服器。
2.  在命令提示字元上輸入：**iisrestart /reset**，然後按下 ENTER。
3.  執行升級。

#### 問題 21：來自於 SUS 1.0 的一些核准無法遷移到 WSUS。

從 SUS 1.0 遷移到 WSUS 時，SUS 1.0 伺服器上的一些核准將無法遷移到 WSUS 伺服器。這是因為 WSUS 無法使用 SUS 1.0 可用的一些更新。此外，因為 WSUS 比 SUS 支援較多更新，所以在遷移程序結束後，WSUS 伺服器上可能有尚未獲准的重要更新。

Microsoft 強烈建議您，從 SUS 1.0 遷移之後，請檢視 WSUS 伺服器上尚未獲准的更新集。

如需從 SUS 1.0 遷移至 WSUS 的相關資訊，請參閱[從 Software Update Services 遷移至 Windows Server Update Services 入門逐步指南](http://go.microsoft.com/fwlink/?linkid=48042) (英文)，網址是 http://go.microsoft.com/fwlink/?LinkId=48042。

#### 問題 22：如果已從 WMSDE 遷移至 SQL Server，請在升級至 WSUS 2.0 Service Pack 1 之前，修正此登錄項目

如果您計畫將 WSUS 2.0 升級至 Service Pack 1，而且已將 WMSDE 安裝遷移至 SQL Server (無論是遠端或本機)，請務必要變更下列登錄項目：

HKLM\\Software\\Microsoft\\Update Services\\Server\\Setup\\WmsdeInstalled

值應從 1 變更為 0。

#### 問題 23：將遠端 SQL 安裝遷移至 WSUS 2.0 Service Pack 1

使用遠端 SQL 設定遷移至 WSUS 2.0 Service Pack 1 時，請執行下列步驟：

1) 在前端執行安裝套件，但是不使用參數，並選擇升級。

2) 在後端執行安裝套件，但是不使用切換參數，並選擇升級。

#### 著作權

本文件中所含的資訊代表 Microsoft Corporation 截至發行日期為止，目前對於所討論問題持有的觀點。由於 Microsoft 必須因應千變萬化的市場情況，因此不應將本文件解讀為 Microsoft 的承諾，且 Microsoft 無法保證任何資訊在發行後的正確性。

本文件僅供參考。MICROSOFT 對於本文件中的資訊不做任何明示、暗示或法定形式的保證。

使用者有責任遵守所有適用的著作權法。在不限制任何依著作權本得享有之權利，未經 Microsoft Corporation 書面許可，貴用戶不得為任何目的使用任何形式或方法 (電子形式、機械形式、影印、記錄或其他方式) 複製或傳送本文件的任何部分，也不得將本文件的任何部分儲存或放入檢索系統 (retrieval system)。

Microsoft 可能擁有此文件所提及內容中所含之專利權、專利申請案、商標、著作權或其他智慧財產權。除非 Microsoft 書面授權合約所明示規定者外，提供本文件並不授予 貴用戶上述專利權、商標、著作權或其他智慧財產權。

除非另有註明，此處所描述之範例公司、組織、產品、網域名稱、電子郵件位址、標誌、人員、地點及事件均屬虛構，並非影射任何真實的公司、組織、產品、網域名稱、電子郵件位址、標誌、人員、地點及事件。

© 2005 Microsoft Corporation.著作權所有，並保留一切權利。

Microsoft、SQL Server、Windows 和 Windows Server 是 Microsoft Corporation 在美國及/或其他國家/地區的註冊商標或商標。

本文件所提及實際的公司及產品名稱可能為其個別擁有者的商標。
