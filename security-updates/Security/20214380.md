---
TOCTitle: 強化 Windows Server 2003 憑證服務伺服器
Title: 強化 Windows Server 2003 憑證服務伺服器
ms:assetid: 'a2682720-aff6-4b03-a667-9ecb04664844'
ms:contentKeyID: 20214380
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Dd548197(v=TechNet.10)'
---

強化 Windows Server 2003 憑證服務伺服器
=======================================

### Overview

發佈日期: 2003 年 12 月 31 日 | 更新日期: 2006 年 4 月 26 日

##### 本頁內容

[](#emaa)[本單元內容](#emaa)
[](#elaa)[目標](#elaa)
[](#ekaa)[適用於](#ekaa)
[](#ejaa)[如何使用本單元](#ejaa)
[](#eiaa)[概觀](#eiaa)
[](#ehaa)[稽核原則設定](#ehaa)
[](#egaa)[使用者權限指派](#egaa)
[](#efaa)[安全性選項](#efaa)
[](#eeaa)[事件記錄設定](#eeaa)
[](#edaa)[系統服務](#edaa)
[](#ecaa)[其他登錄設定](#ecaa)
[](#ebaa)[其他安全性設定](#ebaa)
[](#eaaa)[總結](#eaaa)

### 本單元內容

本單元將說明為保障執行 Microsoft 憑證服務的 Microsoft® Windows Server™ 2003 作業系統所設計的安全性範本設定。單元中將假設伺服器已套用了成員伺服器基準線，同時將詳細描述透過憑證服務伺服器專用範本所套用的安全性設定。本單元還考量到安全性範本所定義以外，其他仍需要套用的安全性設定。這些額外設定是建立完整強化型憑證服務伺服器時的必要項目。

[](#mainsection)[回到頁首](#mainsection)

### 目標

-   透過此單元即可：

-   強化執行憑證服務的 Windows Server 2003 伺服器。

-   瞭解同一部伺服器所套用多份安全性範本之間的互動。

-   調查憑證服務伺服器的安全性設定。

[](#mainsection)[回到頁首](#mainsection)

### 適用於

本單元適用於下列產品及技術：

-   Windows Server 2003

-   Microsoft 憑證服務

[](#mainsection)[回到頁首](#mainsection)

### 如何使用本單元

請使用本單元來瞭解 Windows 2003 憑證服務伺服器應該套用的安全性設定。單元中會結合使用角色特定安全性範本與基準線安全性範本。您可由 [http://go.microsoft.com/fwlink/?LinkId=14846](http://go.microsoft.com/fwlink/?linkid=14846) 中的《Windows Server 2003 Security Guide》(英文) 取得這些安全性範本。

若要充分瞭解此單元：

-   **請參閱＜Windows 2003 安全性簡介＞。** 本單元將說明《Windows Server 2003 Security Guide》(英文) 的用途與內容。

-   **請參閱＜建立 Windows Server 2003 成員伺服器的基準線＞。** 本單元將示範使用組織單位階層和「群組原則」，將成員伺服器基準線套用至多部伺服器。

[](#mainsection)[回到頁首](#mainsection)

### 概觀

本單元將提供可保障環境中 Microsoft 憑證服務伺服器之作業系統的完整指引。儘管本單元包括了完成此項工作的所有必要資訊，但是指引內容並未提供在環境中建立安全的憑證服務基礎結構、或部署憑證授權單位的詳細資訊。這些主題將在 Microsoft Windows Server 2003 產品說明文件，即 *Windows Server 2003 Resource Kit* 中深入探討，而 Microsoft 網站上與該類主題相關的白皮書內亦會予以探討。如需其他資訊，請參閱同系列指引：*《Securing Wireless LANs — a Windows Server 2003 Certificate Services Solution》(英文)*，網址是：[http://go.microsoft.com/fwlink/?LinkId=14843](http://go.microsoft.com/fwlink/?linkid=14843)。

Windows Server 2003 出廠時已設定為安全狀態的預設值。若要提高本單元的可用性，此處僅提供已從「成員伺服器基準線原則」(MSBP) 完成修改的設定。如需關於 MSBP 設定的資訊，請參閱＜建立 Windows Server 2003 成員伺服器的基準線＞單元。如需關於所有預設設定的資訊，請參閱同系列指南的《Threats and Countermeasures:Security Settings in Windows Server 2003 and Windows XP》(英文)。

環境中的一些憑證服務伺服器必須先安裝 Microsoft Internet Information Services (IIS)，才能發佈憑證授權單位 (CA) 憑證與憑證撤銷清單 (CRL)。IIS 也可以用來裝載憑證服務伺服器 Web 註冊頁，讓非 Microsoft Windows® 作業系統用戶端進行憑證註冊。要想實際使用本單元的資訊，必須徹底瞭解 IIS 安裝的程序，詳細資訊請見＜強化 Windows Server 2003 IIS 伺服器＞單元。

此外，如果您的 CA 有安裝 IIS，則在設定本單元所詳述伺服器角色的指定設定之前，必須先為憑證服務伺服器套用為＜強化 Windows Server 2003 IIS 伺服器＞開發的安全性設定範本。

**注意：**在較簡單的環境中，正在發行的 CA 伺服器可用來裝載 Web 伺服器、CA 憑證，以及 CRL 下載點。但是請考慮使用自身環境中的另一部 Web 伺服器，以提高 CA 的安全性。

IIS 可用來裝載憑證伺服器註冊頁，以及為非 Windows 用戶端發佈 CA 憑證與 CRL 下載點。 Microsoft 建議您不要在根憑證授權單位 (CA) 伺服器上安裝 IIS。如果可行，您也應該避免在環境中正在發行或任何中繼 CA 上執行 IIS。將 CA 憑證與 CRL 的 Web 下載點裝載於 CA 伺服器以外的其他伺服器上，是比較安全的做法。有許多需要擷取 CRL、或 CA 鏈結資訊的憑證使用者 (內部與外部)，根本不必要允許他們存取 CA 。如果下載點安裝在 CA 本身，這樣根本就無法達到限制目的。

**注意：**憑證服務角色的設定規則僅針對「企業用戶端」環境進行測試。因此，此處將不討論為大多數的其他伺服器角色所指定的 IPSec 篩選器，與拒絕服務 (DoS) 資訊。

[](#mainsection)[回到頁首](#mainsection)

### 稽核原則設定

本指引中所定義「企業用戶端」環境憑證服務伺服器的稽核原則設定，將會透過 MSBP 來進行設定。如需關於 MSBP 的更多資訊，請參閱此單元，＜建立 Windows Server 2003 成員伺服器的基準線＞。MSBP 設定可確保所有的憑證服務伺服器，都會登入所有相關安全性稽核資訊。

[](#mainsection)[回到頁首](#mainsection)

### 使用者權限指派

本指引中所定義「企業用戶端」環境憑證服務伺服器的使用者權限指派，也將會透過 MSBP 進行設定。如需關於 MSBP 的更多資訊，請參閱此單元，＜建立 Windows Server 2003 成員伺服器的基準線＞。MSBP 設定，可確保整個企業內憑證服務伺服器的適當存取權限，都會統一設定。

[](#mainsection)[回到頁首](#mainsection)

### 安全性選項

群組原則的「安全性選項」區段是用來啟用、或停用電腦的安全性設定，例如，資料的數位簽章、Administrator 和 Guest 帳戶名稱、軟碟機和光碟機存取、驅動程式安裝行為、登入提示等項目。

「安全性選項」設定可在 Windows Server 2003 的下列位置、使用「群組原則物件編輯器」進行設定：

電腦設定\\Windows 設定\\安全性設定\\本機原則\\安全性選項

本段落在下面表格中，包括本指引所定義「企業用戶端」環境憑證服務伺服器角色的安全性選項設定。

#### 裝置：光碟機的存取僅限於登入本機的使用者

**表 1：設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >預設成員伺服器</th>
<th style="border:1px solid black;" >企業用戶端</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">停用</td>
<td style="border:1px solid black;">啟用</td>
</tr>
</tbody>
</table>
  
\[裝置：光碟機存取只限於登入本機的使用者\] 設定，會判定本機和遠端使用者是否可同時存取光碟機。啟用此設定僅允許互動式登入的使用者從光碟機存取媒體。然而啟用此設定且無人登入時，使用者可經由網路來存取光碟機。
  
每次有人登入該伺服器的本機主控台時，經由網路連線到憑證服務伺服器的使用者就不能使用該伺服器上的任何光碟機。我們建議您，不要為系統啟用這個設定來供作網路使用者的 CD 點唱機。然而，如果啟用這個設定，即可以防止攻擊者從這些伺服器的光碟機執行惡意程式。在 CA 上，系統管理員可能會使用光碟機將敏感的金鑰資訊複製到伺服器 (或從其中複製)；這項設定可防止本機登入系統管理員以外的人存取這份資料。基於這個理由，這項設定在本指引中所定義 \[企業用戶端\] 環境裡將設定為 \[啟用\]。
  
#### 裝置：軟碟機存取只限於登入本機的使用者
  
**表 2：設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >成員伺服器預設值</th>
<th style="border:1px solid black;" >企業用戶端</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">停用</td>
<td style="border:1px solid black;">啟用</td>
</tr>
</tbody>
</table>
  
\[裝置：軟碟機存取只限於登入本機的使用者\] 設定能判定本機和遠端使用者是否可同時存取軟碟機。啟用此設定僅允許互動式登入的使用者存取軟碟機。但是啟用這項設定且無人進行互動式登入時，使用者便可經由網路來存取軟碟機。
  
只要有人登入該伺服器的本機主控台時，經由網路連線到憑證服務伺服器的使用者就不能使用該伺服器中的任何軟碟機。然而，如果啟用這個設定，就可以防止攻擊者從這些伺服器的軟碟機執行惡意程式。在 CA 上，系統管理員可能會使用軟碟機將需保密的金鑰資訊複製到伺服器 (或從其中複製) — 這項設定可防止除了本機登入系統管理員的其他所有人存取這份資料。基於這項理由，這項設定在本指引中所定義 \[企業用戶端\] 環境裡將設定為 \[啟用\]。
  
#### 系統密碼編譯：進行加密、雜湊編碼和簽章時使用 FIPS 相容的方法
  
**表 3：設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >成員伺服器預設值</th>
<th style="border:1px solid black;" >企業用戶端</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">停用</td>
<td style="border:1px solid black;">啟用</td>
</tr>
</tbody>
</table>
  
\[系統密碼編譯：使用 FIPS 相容方法於加密，雜湊，以及簽章\] 此一設定能指出 TLS/SSL (Transport Layer Security/Secure Sockets Layer) 安全性提供者是否僅支援 TLS\_RSA\_WITH\_3DES\_EDE\_CBC\_SHA cipher suite。若是指定此選項，就表示提供者僅支援 TLS 通訊協定作為用戶端與伺服器 (若適用)。
  
TLS/SSL 安全性提供者使用下列項目：
  
-   用於 TLS 傳輸加密的 Triple DES (Data Encryption Standard) 加密演算。
  
-   用於 TLS 金鑰交換與驗證的 RSA (Rivest，Shamir，Adelman) 公開金鑰演算 (RSA 是由 RSA Data Security, Inc. 開發的公開金鑰加密技術)。
  
-   符合 TLS 雜湊要求的 SHA — 1 雜湊演算。
  
如果使用 EFS (Encrypting File System Service)，TLS/SSL 安全性提供者就只能支援 Triple DES 加密演算來加密 Windows NTFS 檔案系統可支援的檔案資料。根據預設，EFS 會使用 DESX 演算來加密檔案資料。
  
啟用此設定，可確保符合這個環境伺服器角色的電腦將會為數位加密、雜湊與簽章使用最有效的可用演算。這個設定可降低未經授權使用者滲透數位加密、或簽章資料的風險。基於這項理由，此設定在本指引中所定義 \[企業用戶端\] 環境裡將設定為 \[啟用\]。
  
**注意：**啟用此設定時，用戶端將無法與不支援透過數位加密、或簽章通訊協定進行這些演算的伺服器進行通訊不支援這些演算的網路用戶端將無法使用要求其進行網路通訊的伺服器。例如，許多 Apache 類 Web 伺服器就不會設定成支援 TLS。如果啟用此設定，您將同時需要開啟 Internet Explorer \[工具\] 功能表的 \[網際網路選項\] 對話方塊，將 Internet Explorer 設定成使用 TLS。按一下 \[網際網路選項\] 對話方塊中的 \[進階\] 索引標籤，捲動到 \[設定\] 清單底部，再按一下 \[使用 TLS 1.0\] 核取方塊。您也可以透過群組原則、或使用 Internet Explorer Administrators Kit，來完成這個設定。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 事件記錄設定
  
本指引中所定義「企業用戶端」環境憑證服務伺服器的事件日誌設定，也將會透過 MSBP 進行設定。如需關於 MSBP 的更多資訊，請參閱單元＜建立 Windows Server 2003 成員伺服器的基準線＞。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 系統服務
  
任何服務或應用程式都可能成為攻擊位置，因此，您應該停用或移除不必要的服務或可執行檔。使用 MSBP 時，這些選擇性服務與其他非必要的服務都會停用。
  
執行 Windows Server 2003 的電腦上還經常啟用其他的服務以提供憑證服務伺服器功能，不過這些屬於必要性服務。這些服務的使用與安全性常常成為爭論主題。基於這項理由，本單元對這個伺服器角色所提出的建議可能就不適用於您的環境。請依需求來調整憑證服務伺服器群組原則建議，以便符合組織的要求。
  
系統服務設定可在 Windows Server 2003 的下列位置、使用「群組原則物件編輯器」進行設定：
  
電腦設定\\Windows 設定\\安全性設定\\系統服務\\
  
下面表格包括本指引所定義「企業用戶端」環境憑證服務伺服器角色的增量原則服務設定。
  
#### 憑證服務
  
**表 4：設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >服務名稱</th>
<th style="border:1px solid black;" >成員伺服器預設值</th>
<th style="border:1px solid black;" >企業用戶端</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">CertSvc</td>
<td style="border:1px solid black;">尚未定義</td>
<td style="border:1px solid black;">自動</td>
</tr>
</tbody>
</table>
  
\[憑證服務\] 是 Windows Server 2003 核心作業系統的一部份，可讓公司擔任自己憑證授權單位 (CA) 角色。這項服務是憑證服務伺服器正常運作的必要條件。這些服務是用來發出、管理像是 S/MIME (Secure/Multipurpose Internet Mail Extensions)、SSL、EFS、IPSec 等應用程式與智慧卡登入的數位憑證。Windows Server 2003 支援多層級的 CA 階層，以及交叉認證信任網路，其中包括離線與線上 CA。
  
若是停用這項服務，將會造成無法接受憑證要求，同時也無法發行 CRL 與 Delta CRL。若是長期停用此服務，則會造成 CRL 過期，以及現有憑證的驗證程序失敗。基於這些理由，這些服務的設定在本指引所定義企業用戶端環境中會設定為 \[自動\]。
  
#### 電腦瀏覽器
  
**表 5：設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >服務名稱</th>
<th style="border:1px solid black;" >成員伺服器預設值</th>
<th style="border:1px solid black;" >企業用戶端</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">瀏覽器</td>
<td style="border:1px solid black;">自動</td>
<td style="border:1px solid black;">停用</td>
</tr>
</tbody>
</table>
  
\[電腦瀏覽器\] 服務會維護網路中的最新電腦清單，並將這份清單提供給發出要求的程式。Windows 電腦會使用 \[電腦瀏覽器\] 服務來檢視網路網域和資源。
  
指定作為瀏覽器的電腦，會維護包含該網路所使用全部共用資源的瀏覽清單。較早版本的 Windows 應用程式，例如網路上的芳鄰、NET VIEW 命令與 Windows NT® Explorer 都需要用到瀏覽功能。例如，在執行 Windows 95 電腦上開啟網路上的芳鄰時，將會顯示網域和電腦清單，其中內容是該電腦從指定作為瀏覽器的電腦的瀏覽清單複製所得。
  
一部電腦在瀏覽環境中可能需要執行好幾種不同的角色。在某些情況下，例如指定作為特定瀏覽器角色的電腦執行失敗或關機時，瀏覽器 (或可能的瀏覽器) 可能就會變更成不同的作業角色。
  
如果停用 \[電腦瀏覽器\] 服務，就會造成瀏覽器清單無法更新或維護，並將無法啟動明確依賴此項服務的服務。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 其他登錄設定
  
另外還要建立憑證服務伺服器安全性範本檔案的其他登錄值項目，該範本未定義於本指引中所定義「企業用戶端」環境的「系統管理範本」(.adm) 檔案。此類 .adm 檔案可定義 Windows Server 2003 的系統原則，以及桌面、Shell 和安全性設定。
  
這些其他的登錄設定可透過安全性範本來自動完成這些變更。如果移除了相關環境的原則，此類設定並不會自動移除，而必須使用像是 Regedt32.exe 的登錄編輯工具來手動變更。
  
登錄設定可在 Windows Server 2003 的下列位置、使用「群組原則物件編輯器」進行設定：
  
MACHINE\\SYSTEM\\CurrentControlSet\\Services\\CertSvc\\Configuration
  
下面表格中所包含的機碼和子機碼的登錄路徑，可用來稽核本指引「企業用戶端」環境所定義憑證服務伺服器角色設定的所有變更。
  
**表 6：登錄稽核 SACL**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >UI 稽核路徑</th>
<th style="border:1px solid black;" >企業用戶端</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">MACHINE\SYSTEM\CurrentControlSet\Services\Certsvc\<br />
Configuration (以及全部的子機碼)</td>
<td style="border:1px solid black;">失敗；Everyone 完全控制；&lt;未繼承&gt; 特殊</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">MACHINE\SYSTEM\CurrentControlSet\Services\Certsvc\<br />
Configuration (以及全部的子機碼)</td>
<td style="border:1px solid black;">成功；Everyone；特殊：設定數值、建立子機碼、建立連結、刪除、變更權限、取得擁有權；&lt;未繼承&gt; 特殊</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[回到頁首](#mainsection)
  
### 其他安全性設定
  
下面設定可透過「群組原則」指派。但是本指引並未包含下面設定，因為每部伺服器可能會使用不同的資料庫與日誌安裝。例如憑證服務伺服器可能裝有 C:\\、D:\\ 和 E:\\ 磁碟機。下面段落內容中將詳細說明如何手動實作這些設定。
  
#### 檔案系統 ACL
  
可以存取目標檔案的未授權使用者，很容易就可以從本機、或透過網路來檢視、變更或刪除無法用存取控制清單 (ACL) 保護的檔案。ACL 可協助保護這些檔案。加密則提供更多的保護，對僅提供單一使用者存取的檔案來說也是一種可用選項。
  
下面表格包括執行本指引所定義「企業用戶端」環境憑證服務伺服器之 Windows Server 2003 系統的系統 ACL。在此環境下，憑證服務伺服器會將憑證資料庫目錄從 D:\\ 磁碟機安裝到 D:\\CertSrv，並將資料庫日誌儲存到預設資料夾 %SystemRoot%\\system32\\CertLog。您也可以移動實體上個別已鏡像處理磁碟機內的日誌，例如，E:\\ 中的資料夾 E:\\CertLog。將資料庫與日誌分別存放到不同磁碟機並不屬於安全性要求項目，但是我們仍建議您將這些項目放置在個別的實體磁碟裝置，增進使磁碟免遭損壞的保護效果，以及提昇效能。根據預設，憑證服務預設的安裝資料夾 %SystemRoot%\\system32\\CertLog 與 %SystemRoot%\\system32\\CertSrv 已設定正確的 ACL。下面表格中列出了這些項目。
  
**表 7：檔案系統 ACL**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >UI ACL 路徑</th>
<th style="border:1px solid black;" >企業用戶端</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">%SystemRoot%\system32\CertLog (傳播到全部的子資料夾)</td>
<td style="border:1px solid black;">Administrators (完全控制) SYSTEM (完全控制)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemRoot%\system32\CertSrv (傳播到全部的子資料夾)</td>
<td style="border:1px solid black;">Administrators (完全控制) SYSTEM (完全控制) 使用者 (讀取和執行、列出資料夾內容與讀取)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">D:\CertLog</td>
<td style="border:1px solid black;">Administrators (完全控制) SYSTEM (完全控制)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">D:\CertSrv</td>
<td style="border:1px solid black;">Administrators (完全控制) SYSTEM (完全控制) 使用者 (讀取和執行、列出資料夾內容與讀取)</td>
</tr>
</tbody>
</table>
  
由於 CA 的安全性敏感特質，上面表格所列出的憑證服務資料夾將會啟用檔案稽核。下面列出稽核項目的設定方式：
  
**表 10.8：憑証服務檔案與登錄稽核**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >檔案路徑或登錄路徑</th>
<th style="border:1px solid black;" >稽核類型</th>
<th style="border:1px solid black;" >稽核設定</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">%SystemRoot%\system32\CertLog</td>
<td style="border:1px solid black;">失敗</td>
<td style="border:1px solid black;">Everyone (完全控制)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemRoot%\system32\CertSrv</td>
<td style="border:1px solid black;">成功</td>
<td style="border:1px solid black;">Everyone (修改)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">D:\CertSrv</td>
<td style="border:1px solid black;">成功</td>
<td style="border:1px solid black;">Everyone (修改)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">D:\CertLog</td>
<td style="border:1px solid black;">成功</td>
<td style="border:1px solid black;">Everyone (修改)</td>
</tr>
</tbody>
</table>
  
這些設定的使用目的，是為了稽核任何使用者所造成的所有失敗存取類型 (讀取或修改)，同時稽核任何使用者所造成的任何成功修改。
  
#### 保護眾所皆知帳戶
  
Windows Server 2003 已內建一些無法刪除、但可以重新更名的使用者帳戶。在 Windows Server 2003 中最為知名的兩個內建帳戶就是 **Guest** 與 **Administrator**。
  
根據預設，成員伺服器與網域控制站的 **Guest** 帳戶是停用狀態。您不應該變更這項設定。內建的 **Administrator** 則應該重新命名、並改變說明，以協助防止攻擊者使用眾所皆知的帳戶來滲透遠端伺服器。
  
許多惡意程式碼的變種在第一次嘗試滲透伺服器時，就是使用此內建系統管理員帳戶。因為現在發行的攻擊工具會指定內建 Administrator 帳戶的安全性識別元 (SID) 來判斷其真正名稱、向伺服器發動攻擊行動，所以最近這幾年來，這項設定變更的效果已經降低許多。安全性識別元 (SID) 值是唯一的，可用來識別網路中的每個使用者、群組、電腦帳戶與登入工作階段。這個內建帳戶的 SID 是無法變更的。將本機系統管理員帳戶重新更名成唯一名稱，可以讓作業群組更容易監控此帳戶所遭受的企圖攻擊行為。
  
請完成下列步驟來保障伺服器的眾所皆知帳戶：
  
1.  為每個網域和伺服器的 **Administrator** 與 **Guest** 帳戶重新更名，並將其密碼變更成長的複雜值。
  
2.  每個伺服器上使用不同的名稱及密碼。如果所有網域及伺服器上都使用相同的帳戶名稱與密碼，攻擊者在取得一個成員伺服器的存取權限後，就可以使用相同帳戶名稱與密碼來存取所有其他伺服器。
  
3.  將帳戶說明變更成不同於預設值的說明，以協助防止帳戶易於識破。
  
4.  將這些變更記錄在安全位置。
  
**注意：**內建的系統管理員帳戶可以透過「群組原則」來重新命名。本指引中的參考用安全性範本並未設定這項設定，因為您應該選擇您環境的唯一名稱。\[帳戶：重新命名系統管理員帳戶\] 設定可設定在本指南定義的三個環境中，重新命名系統管理員帳戶。這項設定屬於 GPO 安全性選項設定的一部份。
  
#### 保護服務帳戶
  
除非絕對必要，否則不設定在網域帳戶的安全性內容下執行服務。如果伺服器實體已遭滲透，網域帳戶密碼就會很容易透過傾印 LSA (Local Security Authority) 機密而洩漏出去。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 總結
  
本單元已說明 Windows Server 2003 的伺服器強化設定，也就是建議用來保障本指引所定義「企業用戶端」環境的憑證服務伺服器的設定。所討論到的設定是透過「群組原則」完成設定與套用。指定與 MSBP 配合的「群組原則物件」(GPO) 會連結到包含憑證服務伺服器的適當組織單位 (OU)，以便在這些伺服器所提供服務的基礎上再提供其他的安全性。
  
#### 其他資訊
  
下列資訊來源是本產品公開發行當時，與本指南詳載的 Windows Server 2003 和憑證服務伺服器角色相關的最新主題。
  
如需取得公開金鑰基礎結構 (PKI) 概念與 Windows 2000 憑證服務的詳細介紹，請由下列網址取得《An Introduction to the Windows 2000 Public — Key Infrastructure》(英文)<http://www.microsoft.com/technet/prodtechnol/windows2000serv/evaluate/featfunc/pkiintro.asp>。
  
如需取得有關 Windows Server 2003 與 Windows XP 之 PKI 功能的詳細說明，請由下列網址取得《PKI Enhancements in Windows XP Professional and Windows Server 2003》(英文)：[http://www.microsoft.com/technet/treeview/default.asp?url=/technet/prodtechnol/winxppro/Plan/PKIEnh.asp](http://www.microsoft.com/technet/treeview/default.asp?url=/technet/prodtechnol/winxppro/plan/pkienh.asp)。
  
如需更多有關金鑰 PKI 概念的背景說明，請由下列網址參閱有關《Public Key Infrastructure》(英文) 的 TechNet 資訊： [http://www.microsoft.com/technet/prodtechnol/windowsserver2003/proddocs/entserver/SE\_PKI.asp](http://www.microsoft.com/technet/prodtechnol/windowsserver2003/proddocs/entserver/se_pki.asp)。
  
[](#mainsection)[回到頁首](#mainsection)
