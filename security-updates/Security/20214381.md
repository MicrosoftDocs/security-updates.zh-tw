---
TOCTitle: 強化 Windows Server 2003 堡壘主機
Title: 強化 Windows Server 2003 堡壘主機
ms:assetid: 'be5c75a8-7273-4530-b59a-603fc4b58126'
ms:contentKeyID: 20214381
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Dd548198(v=TechNet.10)'
---

強化 Windows Server 2003 堡壘主機
=================================

### Overview

發佈日期: 2003 年 12 月 31 日 | 更新日期: 2006 年 4 月 26 日

##### 本頁內容

[](#elaa)[本單元內容](#elaa)
[](#ekaa)[目標](#ekaa)
[](#ejaa)[適用於](#ejaa)
[](#eiaa)[如何使用本單元](#eiaa)
[](#ehaa)[概觀](#ehaa)
[](#egaa)[稽核原則設定](#egaa)
[](#efaa)[使用者權限指派](#efaa)
[](#eeaa)[安全性選項](#eeaa)
[](#edaa)[事件日誌設定](#edaa)
[](#ecaa)[系統服務](#ecaa)
[](#ebaa)[其他安全性設定](#ebaa)
[](#eaaa)[總結](#eaaa)

### 本單元內容

本單元說明特別針對堡壘主機的安全性設定範本。堡壘主機是位於外圍網路公用端，可供大家存取而具有安全性的電腦。堡壘主機通常用來當做網路伺服器、網域名稱系統 (DNS)伺服器、檔案傳輸通訊協定 (FTP) 伺服器、SMTP (Simple Mail Transport Protocol) 伺服器，和網路新聞傳輸通訊協定 (NNTP) 伺服器。本單元參考《Windows Server 2003 Security Guide》(英文) 中成員伺服器的基準線設定。本單元還考量到安全性範本所定義以外，其他仍需要套用的安全性設定。為了建立安全性全面強化的堡壘主機，所以需要這些額外的設定。本單元也包括如何使用「安全性設定和分析」工具，套用安全性範本的說明。

[](#mainsection)[回到頁首](#mainsection)

### 目標

透過此單元即可：

-   增強堡壘主機。

-   找出適當的堡壘主機安全性設定。

[](#mainsection)[回到頁首](#mainsection)

### 適用於

本單元適用於下列產品及技術：

-   Microsoft® Windows Server™ 2003 作業系統

-   堡壘主機

[](#mainsection)[回到頁首](#mainsection)

### 如何使用本單元

透過此單元即可瞭解您應該套用於堡壘主機的安全性設定，以及加強此類型獨立主機的功能。單元中會結合使用角色特定安全性範本與基準線安全性範本。這些安全性範本是出自《Windows Server 2003 Security Guide》(英文)，您可以在下列位置取得：[http://go.microsoft.com/fwlink/?LinkId=14846](http://go.microsoft.com/fwlink/?linkid=14846)。

若要充分瞭解此單元：

-   **請參閱單元＜Windows Server 2003 安全性簡介＞。** 本單元將說明《Windows Server 2003 Security Guide 》(英文) 的用途與內容。

-   **請參閱單元＜建立 Windows Server 2003 成員伺服器的基準線＞。** 本單元將示範使用組織單位階層和群組原則，將成員伺服器基準線套用至多部伺服器。

-   **使用隨附的 How To 文件**。使用本單元參考的下列教學文件：

    -   ＜如何使用 Windows Server 2003 套用群組原則和安全性範本＞

[](#mainsection)[回到頁首](#mainsection)

### 概觀

本單元焦點集中在加強環境中堡壘主機的功能。堡壘主機是一個可供大家存取，而具有安全性的電腦。堡壘主機位於周邊網路 (也稱為 DMZ 、非軍事區，和屏蔽式子網路) 的公用端。堡壘主機並未受到防火牆或篩選路由器的保護，使該主機完全暴露在受攻擊的風險中。因為這種暴露風險，所以在設計和設定堡壘主機時必須要投入大量的心力，將受到危害的機會減到最小。

堡壘主機通常用來當做網路伺服器、網域名稱伺服器 (DNS)、檔案傳輸通訊協定 (FTP) 伺服器、Simple Mail Transport Protocol (SMTP) 伺服器，和網路新聞傳輸通訊協定 (NNTP) 伺服器。在理想情況下，堡壘主機通常只專門用於執行其中一種功能，因為每個主機扮演的角色越多，就越可能忽略安全性弱點。確保單一堡壘主機上的單一服務安全較為容易。能夠負擔多重堡壘主機相關成本的組織，可以大幅受益於這種類型的網路結構。

設定堡壘主機的安全性與一般主機的設定大不相同。該主機會停用或移除所有不必要的服務、通訊協定、程式和網路介面，然後每個堡壘主機通常都設定來滿足特定角色。以這種方式增強堡壘主機的功能，可以限制攻擊的潛在方法。

本單元的下列章節會詳細說明增強安全性設定的各種變化，大多能有效地增強各種環境下的堡壘主機安全性。

#### 堡壘主機本機原則

不像本指引在稍早詳細說明的其他伺服器角色群組原則一樣，您無法在堡壘主機伺服器上套用「群組原則」，因為堡壘主機會設定為獨立主機，並且不屬於 Microsoft® Active Directory®目錄服務網域。因為該主機的高度暴露等級，在本指引所定義的三種環境中，針對堡壘主機伺服器只有規定一種指引等級。下面說明的安全性設定是基於＜建立 Windows Server 2003 成員伺服器的基準線＞單元，針對「高安全性」環境所定義的「成員伺服器基礎原則」(MSBP)。這些設定會包含在必須套用至每個堡壘主機之「堡壘主機本機原則」(BHLP) 的安全性範本中。

##### 套用「堡壘主機本機原則」

本指引所參考的 High Security-Bastion Host.inf 檔案可以用來設定 BHLP。還會啟用 SMTP 堡壘主機伺服器正常運作時需要的服務。套用 High Security-Bastion Host.inf 可以透過大幅縮減堡壘主機的受攻擊面，增強伺服器的安全性，但是便無法遠端管理堡壘主機。若要啟用任何進階功能，或是增加堡壘主機的管理功能，則必須要修改 BHLP。

若要套用安全性範本中所包含的所有安全性設定，就必須使用 **「安全性設定及分析」** 嵌入式管理單元，而非 **「本機電腦原則」** 嵌入式管理單元。您無法使用 **「本機電腦原則」** 嵌入式管理單元來匯入安全性範本，因為「系統服務」的安全性設定無法透過此嵌入式管理單元套用。

下列步驟詳細說明使用 **「安全性設定及分析」析** 嵌入式管理單元，匯入與套用 BHLP 安全性範本的程序。

**警告：**Microsoft 強烈建議您在套用 High Security-Bastion Host.inf 之前，執行堡壘主機伺服器的完整備份。在套用 High Security-Bastion Host.inf 安全性範本後，要將堡壘主機還原至原始設定非常的困難。請確定已設定安全性範本，以啟用您環境所需要的堡壘主機功能。

如果需要匯入、分析和套用安全性範本的逐步指引，請參閱＜如何使用Windows Server 2003 套用群組原則和安全性範本＞

完成這些步驟會將所有適當的安全性範本設定，套用至環境內堡壘主機的本機原則中。您必須重新啟動堡壘主機，所有設定才會生效。

下列章節將說明使用 BHLP 所套用的安全性設定。本單元只會記錄與 MSBP 中不同的設定。

[](#mainsection)[回到頁首](#mainsection)

### 稽核原則設定

堡壘主機的「BHLP 稽核原則」設定與 High Security-Member Server Baseline.inf 檔案中所指定的相同。若要取得更多有關 MSBP 的資訊，請參閱單元，＜建立 Windows Server 2003 成員伺服器的基準線＞。BHLP 設定確保所有相關的安全性稽核資訊，會記錄在所有的堡壘主機伺服器上。

[](#mainsection)[回到頁首](#mainsection)

### 使用者權限指派

堡壘主機的「BHLP 使用者權限指派」，是基於＜建立 Windows Server 2003 成員伺服器的基準線＞單元中，High Security-Member Server Baseline.inf 檔案所指定的項目。下列說明 BHLP 和 MSBP 的相異處。

#### 允許本機登入

**表 1：設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >成員伺服器預設值</th>
<th style="border:1px solid black;" >設定</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">允許本機登入</td>
<td style="border:1px solid black;">Administrators</td>
</tr>
</tbody>
</table>
  
\[允許本機登入\] 使用者權限讓使用者能夠在電腦上啟動互動式工作階段。限制能夠用來登入堡壘主機伺服器主控台的帳戶，可以避免伺服器檔案系統和系統服務受到未授權的存取。能夠登入伺服器主控台的使用者可以利用系統來危害伺服器安全性。
  
依預設值，會授權 **Account Operators**、**Backup Operators**、**Print Operators** 和 **Power Users** 群組可以用本機方式登入。將此權限只授與 **Administrators** 群組，限制只有高度信任的使用者，才能在堡壘主機伺服器上進行系統管理存取，提供更高等級的安全性。
  
#### 拒絕從網路存取這台電腦
  
**表 2：設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >成員伺服器預設值</th>
<th style="border:1px solid black;" >設定</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">SUPPORT_388945a0</td>
<td style="border:1px solid black;">ANONOYMOUS LOGON；內建 Administrator；Support_388945a0；Guest；所有非作業系統服務的帳戶</td>
</tr>
</tbody>
</table>
  
**注意：**安全性範本中並未包含ANONOYMOUS LOGON、內建 Administrator、Support\_388945a0、 Guest 和所有非作業系統服務的帳戶。這些帳戶和群組有唯一的安全性識別碼 (SID)。因此，必須手動將它們加入 BHLP 。
  
\[拒絕從網路存取這台電腦\] 使用者權限，會判斷拒絕那一個使用者從網路存取電腦。本設定會拒絕一些網路通訊協定，其中包括伺服器訊息區 (SMB) 的通訊協定、網路基本輸入/輸出系統 (NetBIOS)、共用網際網路檔案系統 (CIFS)，超文字傳輸通訊協定 (HTTP) 和加強元件物件模型 (COM+)。當使用者帳戶同時受限於兩種原則時，本設定會覆寫 \[從網路存取這台電腦\] 的設定。為其他群組設定本使用者權限，可以限制使用者在您的環境中，執行委派的系統管理工作能力。
  
在＜建立 Windows Server 2003 成員伺服器的基準線＞單元中，本指引建議您將 **Guests** 群組包含在指派此權限的使用者和群組清單中，以提供最高等級的安全性。不過依預設值，用來匿名存取 IIS 的 IUSR 帳戶是 **Guests** 群組成員。基於這些原因，**拒絕從網路存取這台電腦**設定會包含 **ANONOYMOUS LOGON；內建Administrator；Support\_388945a0；Guest；所有非作業系統服務的帳戶**，提供堡壘主機本指引所定義的「高安全性」環境。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 安全性選項
  
堡壘主機的「BHLP 安全性選項」設定，與＜建立 Windows Server 2003 成員伺服器的基準線＞單元之High Security-Member Server Baseline.inf 檔案中所指定的項目相同。這些 BHLP 設定確保在堡壘主機伺服器上，所有相關「安全性選項」設定的一致性。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 事件日誌設定
  
堡壘主機的「BHLP 事件記錄」設定，與＜建立 Windows Server 2003 伺服器的成員伺服器基礎＞單元之High Security-Member Server Baseline.inf 檔案中所指定的項目相同。這些 BHLP 設定確保在堡壘主機伺服器上，所有相關「事件日誌」設定的一致性。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 系統服務
  
堡壘主機伺服器原本就暴露在外界的攻擊風險中。因為此原因，必須最小化每個堡壘主機的受攻擊面。為了適當增強堡壘主機伺服器的功能，所有作業系統不需要的服務，以及所有堡壘主機角色在正常運作時不必要的服務，都應該要停用。本指引所參考的 High Security-Bastion Host.inf 安全性範本，會設定 BHLP 啟用SMTP堡壘主機伺服器正常運作時，所需要的服務。 BHLP 會啟用Internet Information Services Manager、HTTP SSL和SMTP服務。然而，您必須修改 BHLP 才能啟用任何其他功能。
  
停用的大量服務可能會產生許多可忽略之「事件日誌」警告。在某些案例中，啟用某些服務會減少「事件日誌」警告和錯誤訊息，並增加堡壘主機的管理性。然而，這也會增加每個堡壘主機的受攻擊面。
  
下列章節討論堡壘主機伺服器上應該停用的服務，以便在維護功能性的同時減少受攻擊面。只有在 High Security-Member Server Baseline.inf 檔案中尚未停用的服務，才會包含在這些章節中。
  
#### 自動更新
  
**表 3：設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >服務名稱</th>
<th style="border:1px solid black;" >設定</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Wuauserv</td>
<td style="border:1px solid black;">停用</td>
</tr>
</tbody>
</table>
  
\[自動更新\] 服務讓堡壘主機能夠下載並安裝Microsoft Windows® 作業系統重大更新。本服務自動提供堡壘主機最新的更新、驅動程式和增強軟體。您不再需要手動搜尋重大更新和資訊；作業系統會直接將它傳送到堡壘主機上。作業系統會辨識您是否在線上，並使用您的網際網路連線，在Windows Update服務中搜尋可套用的更新。服務在下載或安裝之前會通知您，或是自動為您安裝更新，這項操作取決於您的設定。
  
停止或停用 \[自動更新\] 服務會避免將重大更新自動下載至電腦中。在此案例中，您需要直接連線至 Windows Update 網站：<http://v4.windowsupdate.microsoft.com/en/default.asp>，來搜尋、下載和安裝任何可套用的重大修正程式。
  
本服務對堡壘主機的正常運作而言，並非必要服務。使用本機原則提供安全性，並將本服務的啟動模式，設定為只授與伺服器系統管理員存取權，可避免未經授權或惡意的使用者設定或操作服務。此外，停用此服務可以有效減少堡壘主機伺服器的受攻擊面。基於這些原因，在 BHLP 中 \[自動更新\] 會設定為 \[停用\]。
  
#### 幕後智慧型傳送服務
  
**表 4：設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >服務名稱</th>
<th style="border:1px solid black;" >設定</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">BITS</td>
<td style="border:1px solid black;">停用</td>
</tr>
</tbody>
</table>
  
**幕後智慧型傳送服務** (BITS) 是一個幕後檔案傳送機制和佇列管理員。BITS 在用戶端和 HTTP 伺服器之間以非同步方式傳輸檔案。BITS 會使用其他閒置的網路頻寬，接受傳送檔案的要求，因此不會影響其他與網路相關的活動 (像是瀏覽網路)。
  
停止本服務會使像是「自動更新」的功能無法自動下載程式和其他資訊，直到再次執行服務為止。如果透過「群組原則」設定此服務，表示電腦不會接收 Software Update Services (SUS) 的自動更新。停用此服務會造成任何明確依靠它的服務不傳送檔案，除非有透過其他方法 (像是 Internet Explorer) 傳送檔案的 fail-safe 機制。
  
本服務對堡壘主機的正常運作而言，並非必要服務。使用本機原則提供安全性，並將本服務的啟動模式，設定為只授與伺服器系統管理員存取權，可避免未經授權或惡意的使用者設定或操作服務。此外，停用此服務可以有效減少堡壘主機伺服器的受攻擊面。基於這些原因，在 BHLP 中已停用此服務。
  
#### 電腦瀏覽器
  
**表 5：設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >服務名稱</th>
<th style="border:1px solid black;" >設定</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">瀏覽器</td>
<td style="border:1px solid black;">停用</td>
</tr>
</tbody>
</table>
  
\[電腦瀏覽器\] 服務維護最新的網路電腦清單，並提供給要求的程式。要檢視網域和資源的 Windows 電腦會使用 \[電腦瀏覽器\] 服務。指定為瀏覽器的電腦會維護瀏覽清單，其中包含網路上所有的共用資源。較早版本的 Windows 應用程式，像是 My Network Places、NET VIEW 命令，和 Microsoft Windows NT® 作業系統Explorer，都需要瀏覽能力。例如，在執行 Windows 95 的電腦上開啟 My Network Places，會顯示網域和電腦清單，而該電腦是向指定為瀏覽器的電腦取得瀏覽清單的複本，才能完成這項操作。
  
停用 \[電腦瀏覽器\] 服務會造成停止更新或維護瀏覽器清單。停止此服務也會造成任何明確依靠它的服務執行失敗。
  
本服務對堡壘主機的正常運作而言，並非必要服務。使用本機原則提供安全性，並將服務的啟動模式，設定為只授與伺服器系統管理員存取權，可避免未經授權或惡意的使用者設定或操作服務。此外，停用此服務可以有效減少堡壘主機伺服器的受攻擊面。基於這些原因，在 BHLP 中 \[電腦瀏覽器\] 會設定為 \[停用\]。
  
#### DHCP用戶端
  
**表 6：設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >服務名稱</th>
<th style="border:1px solid black;" >設定</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Dhcp</td>
<td style="border:1px solid black;">停用</td>
</tr>
</tbody>
</table>
  
\[DHCP 用戶端\] 服務透過登錄並更新網際網路通訊協定 (IP) 位址和電腦的 DNS 名稱，來管理網路設定。當用戶端像是在網路上漫遊的使用者時，本服務讓您不需要手動變更 IP 設定。只要每個子網路都能夠存取動態主機設定通訊協定 (DHCP) 伺服器，不論用戶端重新連線至哪一個子網路，都會自動指定一個新的 IP 位址給用戶端。不需要手動設定 DNS 或 Windows 網際網路名稱服務 (WINS)。只要 DHCP 伺服器設定為發行這類資訊，就會強制用戶端使用這些服務設定。如果要在用戶端啟用此服務，只要選取 \[自動取得DNS伺服器位址\] 選項按鈕。啟用此服務不會造成重複的IP位址衝突。
  
停用 \[DHCP用戶端\] 服務會造成電腦停止接收動態IP位址，並且在DNS伺服器上不會登錄自動的動態DNS更新。停止此服務也會造成任何明確依靠它的服務執行失敗。
  
本服務對堡壘主機的正常運作而言，並非必要服務。使用本機原則提供安全性，並將本服務的啟動模式，設定為只授與伺服器系統管理員存取權，可避免未經授權或惡意的使用者設定或操作服務。此外，停用此服務可以有效減少堡壘主機伺服器的受攻擊面。基於這些原因，在 BHLP 中 \[DHCP用戶端\] 會設定為 \[停用\]。
  
#### Network Location Awareness (NLA)
  
**表格：設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >服務名稱</th>
<th style="border:1px solid black;" >設定</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">NLA</td>
<td style="border:1px solid black;">停用</td>
</tr>
</tbody>
</table>
  
\[Network Location Awareness(NLA)\] 服務會收集並儲存網路設定資訊，像是IP位址和網域名稱變更，以及位置變更資訊，然後當此資訊變更時會通知應用程式。
  
本服務對堡壘主機的正常運作而言，並非必要服務。使用本機原則提供安全性，並將服務的啟動模式，設定為只授與伺服器系統管理員存取權，可避免未經授權或惡意的使用者設定或操作服務。此外，停用此服務可以有效減少堡壘主機伺服器的受攻擊面。基於這些 原因，在 BHLP 中**Network Location Awareness (NLA)** 會設定為 \[停用\]。
  
#### NTLM安全性支援提供者
  
**表 8：設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >服務名稱</th>
<th style="border:1px solid black;" >設定</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">NtLmSsp</td>
<td style="border:1px solid black;">停用</td>
</tr>
</tbody>
</table>
  
\[NTLM 安全性支援提供者\] 服務提供遠端程序呼叫 (RPC) 程式 (使用傳輸而非具名管道) 的安全性，並且讓使用者能夠使用 NTLM 驗證通訊協定登入網路。NTLM 通訊協定驗證不使用 Kerberos 版本 5 驗證的用戶端。
  
停止或停用 \[NTLM 安全性支援提供者\] 服務會讓您無法登入使用 NTLM 驗證通訊協定的用戶端，或存取網路資源。 Microsoft Operations Manager (MOM) 和 Telnet 依靠此服務。
  
本服務對堡壘主機的正常運作而言，並非必要服務。使用本機原則提供安全性，並將服務的啟動模式，設定為只授與伺服器系統管理員存取權，可避免未經授權或惡意的使用者設定或操作服務。此外，停用此服務可以有效減少堡壘主機伺服器的受攻擊面。基於這些原因，在 BHLP 中 \[NTLM 安全性支援提供者\] 會設定為 \[停用\]。
  
#### 效能記錄和警告
  
**表 9：設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >服務名稱</th>
<th style="border:1px solid black;" >設定</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">SysmonLog</td>
<td style="border:1px solid black;">停用</td>
</tr>
</tbody>
</table>
  
\[效能記錄和警告\] 服務會根據預先設定的排程參數，收集本機或遠端電腦的效能資料，然後將資料寫入記錄中或觸發警告。\[效能記錄和警告\] 服務根據包含在命名記錄收集設定中的資訊，啟動和停止每個具名的效能資料收集。至少排程一個收集工作，才會執行此服務。
  
停止和停用 \[效能記錄和警告\] 服務會停止收集效能資訊、終止目前執行的資料收集工作，並且不會執行未來排程的收集工作。
  
本服務對堡壘主機的正常運作而言，並非必要服務。使用本機原則提供安全性，並將服務的啟動模式，設定為只授與伺服器系統管理員存取權，可避免未經授權或惡意的使用者設定或操作服務。此外，停用此服務可以有效減少堡壘主機伺服器的受攻擊面。基於這些原因，在 BHLP 中 \[效能記錄和警告\] 會設定為 \[停用\]。
  
#### 遠端系統管理服務
  
**表 10：設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >服務名稱</th>
<th style="border:1px solid black;" >設定</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">SrvcSurg</td>
<td style="border:1px solid black;">停用</td>
</tr>
</tbody>
</table>
  
當重新啟動伺服器時，\[遠端系統管理服務\] 會執行下列的「遠端系統管理工作」：
  
-   增加伺服器重新啟動計數。
  
-   產生自動簽署的憑證。
  
-   如果伺服器並未設定日期和時間，則發出警告。
  
-   如果並未設定「警告電子郵件」功能，則發出警告。
  
停止 \[遠端系統管理服務\] 可能會造成遠端伺服器系統管理工具的某些功能無法正常運作，像是遠端系統管理的網頁介面。停止此服務會造成任何明確依靠它的服務執行失敗。
  
本服務對堡壘主機的正常運作而言，並非必要服務。使用本機原則提供安全性，並將服務的啟動模式，設定為只授與伺服器系統管理員存取權，可避免未經授權或惡意的使用者設定或操作服務。此外，停用此服務可以有效減少堡壘主機伺服器的受攻擊面。基於這些原因，在 BHLP 中 \[遠端系統管理服務\] 會設定為 \[停用\]。
  
#### 遠端登錄服務
  
**表 11：設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >服務名稱</th>
<th style="border:1px solid black;" >設定</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">RemoteRegistry</td>
<td style="border:1px solid black;">停用</td>
</tr>
</tbody>
</table>
  
\[遠端登錄服務\] 讓遠端使用者可以修改網域控制站的登錄設定，提供遠端使用者所需的權限。依預設值，只有 **Administrators** 和 **Backup Operators** 群組中的使用者，才可以遠端存取登錄。Microsoft Baseline Security Analyzer (MBSA) 公用程式需要此服務。 MBSA 是允許您檢查組織中每台伺服器上，已經安裝那些補充程式的工具。
  
停止 \[遠端登錄服務\] 只允許您在本機電腦修改登錄。停用此服務會造成任何明確依靠它的服務執行失敗，但是不會影響本機電腦的登錄作業。其他電腦或裝置也不會再連線至您本機電腦的登錄。
  
本服務對堡壘主機的正常運作而言，並非必要服務。使用本機原則提供安全性，並將服務的啟動模式，設定為只授與伺服器系統管理員存取權，可避免未經授權或惡意的使用者設定或操作服務。此外，停用此服務可以有效減少堡壘主機伺服器的受攻擊面。基於這些原因，在 BHLP 中 \[遠端登錄服務\] 會設定為 \[停用\]。
  
#### 伺服器
  
**表 12：設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >服務名稱</th>
<th style="border:1px solid black;" >設定</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">lanmanserver</td>
<td style="border:1px solid black;">停用</td>
</tr>
</tbody>
</table>
  
\[伺服器\] 服務在網路上提供 RPC 支援、檔案、列印和具名管道的共用。此服務允許本機資源共用，像是磁碟機或印表機，如此一來網路上的其他使用者便可以存取這些資源。這服務也允許應用程式之間 (在其他電腦上執行，以及在您電腦上執行的應用程式) 的具名管道通訊，以提供 RPC 使用。具名管道通訊是針對一個處理程序輸出，用來當做另一個處理程序輸入所保留的記憶體。接受輸入的處理程序並不一定要是電腦本機程序。
  
停止 \[伺服器\] 服務會讓您無法在網路上與其他人共用電腦的檔案和印表機，並且也不會滿足RPC要求。停止此服務也會造成任何明確依靠它的服務執行失敗。
  
本服務對堡壘主機的正常運作而言，並非必要服務。使用本機原則提供安全性，並將服務的啟動模式，設定為只授與伺服器系統管理員存取權，可避免未經授權或惡意的使用者設定或操作服務。此外，停用此服務可以有效減少堡壘主機伺服器的受攻擊面。基於這些原因，在 BHLP 中 \[伺服器\] 會設定為 \[停用\]。
  
#### TCP/IP NetBIOS 輔助服務
  
**表 13：設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >服務名稱</th>
<th style="border:1px solid black;" >設定</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">LMHosts</td>
<td style="border:1px solid black;">停用</td>
</tr>
</tbody>
</table>
  
**TCP/IP NetBIOS 輔助服務** 在 TCP/IP (NetBT) 上提供網路基本輸入/輸出系統 (NetBIOS) 的支援，以及網路上用戶端的 NetBIOS 名稱解析；因此，讓使用者能夠共用檔案、列印和登入網路。傳輸控制通訊協定/網際網路通訊協定 (TCP/IP) NetBIOS 輔助服務藉由執行 DNS 名稱解析，提供 NetBT 服務的支援。
  
停止 \[TCP/IP NetBIOS 輔助服務\] 會讓 NetBT、重新導向器 (RDR)、伺服器 (SRV)、Netlogon 和信差服務用戶端無法共用檔案、印表機，並且使用者無法登入電腦。例如，網域「群組原則」將無法正常運作。停止此服務會造成任何明確依靠它的服務執行失敗。
  
本服務對堡壘主機的正常運作而言，並非必要服務。使用本機原則提供安全性，並將服務的啟動模式，設定為只授與伺服器系統管理員存取權，可避免未經授權或惡意的使用者設定或操作服務。此外，停用此服務可以有效減少堡壘主機伺服器的受攻擊面。基於這些原因，在 BHLP 中 \[TCP/IP NetBIOS 輔助服務\] 會設定為 \[停用\]。
  
#### 終端機服務
  
**表 14：設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >服務名稱</th>
<th style="border:1px solid black;" >設定</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">TermService</td>
<td style="border:1px solid black;">停用</td>
</tr>
</tbody>
</table>
  
\[終端機服務\] 提供多重工作階段環境，以允許用戶端裝置存取伺服器上執行的虛擬 Windows 桌面工作階段和 Windows 程式。\[終端機服務\] 允許使用者遠端進行伺服器系統管理。
  
停止或停用 \[終端機服務\] 會讓您無法從遠端進行電腦的系統管理工作，使管理與更新電腦變得困難。
  
本服務對堡壘主機的正常運作而言，並非必要服務。使用本機原則提供安全性，並將服務的啟動模式，設定為只授與伺服器系統管理員存取權，可避免未經授權或惡意的使用者設定或操作服務。此外，停用此服務可以有效減少堡壘主機伺服器的受攻擊面。基於這些原因，在 BHLP 中 \[終端機服務\] 會設定為 \[停用\]。
  
#### Windows Installer
  
**表 15：設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >服務名稱</th>
<th style="border:1px solid black;" >設定</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">MSIServer</td>
<td style="border:1px solid black;">停用</td>
</tr>
</tbody>
</table>
  
**Windows Installer** 服務透過套用在安裝程序期間集中定義的一組安裝規則，管理應用程式的安裝和移除。這些安裝規則定義已安裝應用程式的安裝和設定。此外，此服務也用來修改、修復或移除現有的應用程式。此服務的技術是由 Windows 作業系統之 **Windows Installer** 服務，和 (msi) 套件檔案格式 (用來保留關於應用程式設定和安裝的資訊) 所組成。
  
**Windows Installer** 並不只是一個安裝程式，也是個可延伸的軟體管理系統。該服務管理安裝、增益集、刪除軟體元件、監控檔案恢復性，以及使用復原維護基本檔案損毀修復。此外 **Windows Installer** 支援多重來源的安裝和執行軟體，想要安裝自訂應用程式的程式開發人員也可以自訂之。
  
設定 **Windows Installer** 用手動方式讓使用 installer 的應用程式啟動此服務。
  
停止此服務會造成依靠它的應用程式安裝、移除、修復和修改執行失敗。同時，一些在執行同時使用此服務的應用程式可能不會執行。停止此服務會造成任何明確依靠它的服務執行失敗。
  
本服務對堡壘主機的正常運作而言，並非必要服務。使用本機原則提供安全性，並將服務的啟動模式，設定為只授與伺服器系統管理員存取權，可避免未經授權或惡意的使用者設定或操作服務。此外，停用此服務可以有效減少堡壘主機伺服器的受攻擊面。基於這些原因，在 BHLP 中 **Windows Installer** 會設定為 \[停用\]。
  
#### Windows Management Instrumentation 驅動程式擴充功能
  
**表 16：設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >服務名稱</th>
<th style="border:1px solid black;" >設定</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">WMI</td>
<td style="border:1px solid black;">停用</td>
</tr>
</tbody>
</table>
  
\[Windows Management Instrumentation 驅動程式擴充\] 服務監控所有設定為發佈 WMI，或事件追蹤資訊的驅動程式和事件追蹤提供者。
  
本服務對堡壘主機的正常運作而言，並非必要服務。使用本機原則提供安全性，並將服務的啟動模式，設定為只授與伺服器系統管理員存取權，可避免未經授權或惡意的使用者設定或操作服務。此外，停用此服務可以有效減少堡壘主機伺服器的受攻擊面。基於這些原因，在 BHLP 中 \[Windows Management Instrumentation 驅動程式擴充\] 會設定為 \[停用\]。
  
#### WMI Performance Adapter
  
**表 17：設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >服務名稱</th>
<th style="border:1px solid black;" >設定</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">WMIApSrv</td>
<td style="border:1px solid black;">停用</td>
</tr>
</tbody>
</table>
  
**WMI Performance Adapter** 服務提供 WMI HiPerf 提供程式的效能程式庫資訊。今日需要提供效能計數器的應用程式和服務，可以使用兩種方式執行這項操作：撰寫 WMI 高效能提供程式，或撰寫效能程式庫。
  
**WMI Performance Adapter** 服務會將 WMI 高效能提供程式所提供的效能計數器，轉換為效能資料協助程式 (PDH) 能夠透過 Reverse Adapter 效能程式庫使用的計數器。如此一來，PDH 用戶端 (例如 Sysmon) 可以使用電腦上任何WMI高效能提供程式顯示的效能計數器。
  
如果停止 **WMI Performance Adapter** 服務，便無法使用WMI效能計數器。停止此服務會造成任何明確依靠它的服務執行失敗。
  
本服務對堡壘主機的正常運作而言，並非必要服務。使用本機原則提供安全性，並將服務的啟動模式，設定為只授與伺服器系統管理員存取權，可避免未經授權或惡意的使用者設定或操作服務。此外，停用此服務可以有效減少堡壘主機伺服器的受攻擊面。基於這些原因，在 BHLP 中 **WMI Performance Adapter** 會設定為 \[停用\]。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 其他安全性設定
  
透過 BHLP 套用的安全性設定，提供堡壘主機伺服器大量增強的安全性。然而，應該考慮到幾個額外的考量和程序。這些步驟無法透過本機原則執行，並且應該在所有堡壘主機伺服器上用手動方式完成。
  
#### 手動將唯一的安全性群組新增至使用者權利指派
  
大部份經由 MSBP 套用的「使用者權利指派」，在本指南隨附的安全性範本中，都有指定適當的安全性群組。然而，有些帳戶和安全性群組無法包含在範本中，因為它們的安全性識別碼 (SID) 是個別 Windows 2003 網域特定的識別碼。下列指定必須手動設定的使用者權利指派。
  
**警告：**下列表格包含內建 **Administrator** 帳戶的值。此帳戶不應該與內建**系統管理員**安全性群組混淆。如果 **Administrator** 安全性群組新增至下列任何拒絕存取使用者權利中，您需要登入本機以便修正此錯誤。
  
此外，可能會根據＜建立 Windows Server 2003 成員伺服器的基準線＞單元中說明的某些建議，重新命名內建的 **Administrator** 帳戶。當新增 **Administrator** 帳戶時，請確定已指定重新命名的帳戶。
  
**表 18：手動新增的使用者權利指派**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >成員伺服器預設值</th>
<th style="border:1px solid black;" >傳統用戶端</th>
<th style="border:1px solid black;" >企業用戶端</th>
<th style="border:1px solid black;" >高安全性</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">拒絕從網路存取這台電腦</td>
<td style="border:1px solid black;">內建 Administrator；Support_388945a0；Guest；所有非作業系統服務的帳戶</td>
<td style="border:1px solid black;">內建 Administrator；Support_388945a0；Guest；所有非作業系統服務的帳戶</td>
<td style="border:1px solid black;">內建 Administrator；Support_388945a0；Guest；所有非作業系統服務的帳戶</td>
</tr>
</tbody>
</table>
  
**重要：**所有非作業系統的服務帳戶，包含用在企業中特定應用程式的服務帳戶。並不包括作業系統使用的內建帳戶 (LOCAL SYSTEM、LOCAL SERVICE 或 NETWORK SERVICE 帳戶戶)。
  
#### 移除不必要的網路通訊協定和連結
  
可以在網際網路上直接存取的伺服器，特別是堡壘主機伺服器，應該停用所有不必要的通訊協定，以還擊使用者列舉的威脅。使用者列舉是利用收集資訊的一種攻擊類型，攻擊者嘗試取得系統特定的資訊，以計劃進一步的攻擊。
  
伺服器訊息區 (SMB) 通訊協定會傳回有關電腦的大量資訊，甚至會將資訊傳給使用 NULL 工作階段，並且未經驗證的使用者。可以擷取的資訊包括共用、使用者資訊 (包括群組和使用者權利)、登錄機碼和更多其他資訊。
  
停用 SMB 和 TCP/IP 上的 NetBIOS 可以藉由減少伺服器的受攻擊面，進而增強堡壘主機的安全性。雖然使用這種設定的伺服器在管理方面較為困難，並且無法存取網路上共用的資料夾，但是這些方法可以有效保護伺服器，不會輕易地受到危害。因此本指引建議您停用堡壘主機中，可經由網際網路存取之網路連線的 SMB 和 TCP/IP 上的NetBIOS。
  
-   **若要停用 SMB ：**
  
    1.  在 \[控制台\] 中，按兩下 \[網路連線\]。
  
    2.  用滑鼠右鍵按一下網際網路圖示的連線，然後按一下 \[內容\]。
  
    3.  在 \[內容\] 對話方塊中，請選取 \[Microsoft Networks 用戶端\]，然後按一下 \[解除安裝\]。
  
    4.  請遵循解除安裝步驟。
  
    5.  請選取 \[File and Printer Sharing for Microsoft Networks\]，然後按一下 \[解除安裝\]。
  
    6.  請遵循解除安裝步驟。
  
<!-- -->
  
-   **如果要停用 TCP/IP 上的 NetBIOS：**
  
    1.  在 \[控制台\] 中，按兩下 \[系統\]，再按一下 \[硬體\] 索引標籤，然後按一下 \[裝置管理員\] 按鈕。
  
    2.  在 \[檢視\] 功能表中，按一下 \[顯示隱藏裝置\]。
  
    3.  展開**非隨插即用驅動程式**。
  
    4.  用滑鼠右鍵按一下 \[Tcpip 上的 NetBIOS\]，然後按下 \[停用\]。
  
此程序會停用 TCP/445 和 UDP445 上的 SMB 直接主機接聽程式。
  
**注意：**此程序會停用 nbt.sys 驅動程式。\[進階 TCP/IP 設定\]對話方塊的 \[WINS \] 索引標籤包含 \[停用 TCP/IP 上的 NetBIOS\] 選項。選取此選項只會停用 **NetBIOS 工作階段服務** (接聽 TCP 連接埠 139)。這麼做*不會*完全停用 SMB。如果要執行這項操作，請使用上述步驟。
  
#### 保護眾所皆知帳戶
  
Windows Server 2003 有一些無法刪除，但是可以重新命名的內建使用者帳戶。在 Windows Server 2003 中最眾所皆知的兩個內建帳戶是 **Guest** 和 **Administrator**。
  
依預設值會停用伺服器上的 **Guest** 帳戶，並且不應該變更。應該重新命名內建的 **Administrator** 帳戶，並且變更說明以避免攻擊者使用眾所皆知的帳戶，危害遠端伺服器。
  
許多惡意程式碼的變形，一開始會嘗試使用內建的系統管理員帳戶來危害伺服器。此設定變更的值在過去幾年中已經減少，因為透過指定內建 **Administrator** 帳戶的安全性識別碼 (SID)，以判斷真實名稱，來嘗試破解伺服器的攻擊工具已經發行。安全性識別元 (SID) 值是唯一的，可用來識別網路中的每個使用者、群組、電腦帳戶與登入工作階段。不可能變更此內建帳戶的SID。將本機系統管理員帳戶重新更名成唯一名稱，可以讓作業群組更容易監控此帳戶所遭受的企圖攻擊行為。
  
-   **若要保障堡壘主機伺服器上眾所皆知帳戶的安全性：**
  
    1.  重新命名 **Administrator** 和 **Guest** 帳戶，然後在每個伺服器上將他們的密碼變更為較長而複雜的值。
  
    2.  每個伺服器上使用不同的名稱及密碼。如果在所有的伺服器上使用相同的帳戶名稱和密碼，則取得一台伺服器存取權的攻擊者，便可以使用相同的帳戶名稱和密碼，取得所有其他伺服器的存取權。
  
    3.  將帳戶說明變更成不同於預設值的說明，以協助防止帳戶易於識破。
  
    4.  將這些變更記錄在安全位置。
  
#### 錯誤報告
  
**表 19：設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >預設值</th>
<th style="border:1px solid black;" >傳統用戶端</th>
<th style="border:1px solid black;" >企業用戶端</th>
<th style="border:1px solid black;" >高安全性</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">報告錯誤</td>
<td style="border:1px solid black;">停用</td>
<td style="border:1px solid black;">停用</td>
<td style="border:1px solid black;">停用</td>
</tr>
</tbody>
</table>
  
\[錯誤報告\] 服務協助 Microsoft 追蹤並處理錯誤。您可以設定此服務產生作業系統錯誤、Windows 元件錯誤或程式錯誤的報告。啟用 \[錯誤報告\] 服務會造成這類錯誤經由網際網路回報給 Microsoft，或回報至內部企業檔案共用。
  
您只能夠在 Windows XP Professional 和Windows Server 2003 中使用此設定，在「群組原則物件編輯器」中設定此服務的路徑為：
  
電腦設定\\系統管理員範本\\系統\\錯誤報告
  
錯誤報告可能包含潛在的敏感資料，或甚至機密的企業資料。Microsoft 有關錯誤報告的隱私權原則，確保 Microsoft 不會不當使用這類資料，但是該資料是以純文字的超文字傳輸通訊協定 (HTTP) 進行傳輸，第三人可能會在網際網路上中途攔截並檢視這份資料。基於這些原因，本指引建議將 BHLP 中的 \[錯誤報告\] 設定，在三種本指引定義之安全性環境中，都設定為 \[停用\]。
  
#### 使用 IPSec 篩選器封鎖連接埠
  
「網際網路通訊協定安全性」(IPSec) 篩選器提供有效方法，可強化伺服器所需要的安全性層級。本指南建議，在本指南內定義的高安全性環境可以採用此指示，進一步減少伺服器的攻擊表面區域。
  
如需使用 IPSec 篩選器的詳細資訊，請參閱＜Additional Member Server Hardening Procedures＞ (英文) 單元。
  
下列表格列出在本指引定義的「高安全性」環境中，SMTP 堡壘主機上應該建立的所有 IPSec 篩選器。
  
**表 20：SMTP 堡壘主機 IPSec 網路流量圖**

 
<table style="border:1px solid black;">
<colgroup>
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >服務</th>
<th style="border:1px solid black;" >通訊協定</th>
<th style="border:1px solid black;" >來源連結埠</th>
<th style="border:1px solid black;" >目的地連接埠</th>
<th style="border:1px solid black;" >來源位址</th>
<th style="border:1px solid black;" >目的地位址</th>
<th style="border:1px solid black;" >動作</th>
<th style="border:1px solid black;" >鏡像</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">SMTP 伺服器</td>
<td style="border:1px solid black;">TCP</td>
<td style="border:1px solid black;">任何</td>
<td style="border:1px solid black;">25</td>
<td style="border:1px solid black;">任何</td>
<td style="border:1px solid black;">我</td>
<td style="border:1px solid black;">允許</td>
<td style="border:1px solid black;">是</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">DNS 用戶端</td>
<td style="border:1px solid black;">TCP</td>
<td style="border:1px solid black;">任何</td>
<td style="border:1px solid black;">53</td>
<td style="border:1px solid black;">我</td>
<td style="border:1px solid black;">DNS 伺服器</td>
<td style="border:1px solid black;">允許</td>
<td style="border:1px solid black;">是</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DNS 用戶端</td>
<td style="border:1px solid black;">UDP</td>
<td style="border:1px solid black;">任何</td>
<td style="border:1px solid black;">53</td>
<td style="border:1px solid black;">我</td>
<td style="border:1px solid black;">DNS 伺服器</td>
<td style="border:1px solid black;">允許</td>
<td style="border:1px solid black;">是</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">所有輸入的流量</td>
<td style="border:1px solid black;">任何</td>
<td style="border:1px solid black;">任何</td>
<td style="border:1px solid black;">任何</td>
<td style="border:1px solid black;">任何</td>
<td style="border:1px solid black;">我</td>
<td style="border:1px solid black;">封鎖</td>
<td style="border:1px solid black;">是</td>
</tr>
</tbody>
</table>
  
上面表格中所列出的所有規則在實作時應該進行鏡像處理。這樣可確保任何傳入到伺服器的網路資料傳輸，都將允許傳回到原始伺服器。
  
上述表格表示應該開啟，以便讓伺服器執行角色特定功能的基本連接埠。伺服器設定為靜態 IP 位址時，這些連接埠數量已經足夠。
  
**警告：**這些 IPSec 篩選器用途有相當大的限制，並且會大幅降低這些伺服器的管理性。您需要開啟額外的連接埠，以啟用監控、補充程式管理，和軟體更新能力。
  
IPSec 原則實作應該不會對伺服器效能造成明顯的影響。但是這些篩選器在實作之前，應該先執行測試，以便確認伺服器的必要功能和效能有維持正常運作。您也可能需要加入其他規則，以便支援其他的應用程式。
  
隨附在此指引中的是一個 .cmd 檔，能簡化堡壘主機規定的 IPSec 篩選器建立程序。**PacketFilters-SMTPBastionHost.cmd** 檔案使用 NETSH 命令建立適當的篩選器。
  
本指令碼不建立永續性篩選器。所以，必須啟動 IPSec 原則代理程式，伺服器才會受到保護。如需建立持續篩選器、或建立更進階 IPSec 篩選器指令碼的詳細資訊，請參閱＜Additional Member Server Hardening Procedures＞(英文) 單元。最後，本指令碼設定為不指派自己建立的 IPSec 原則。「IP 安全性原則管理」嵌入式管理單元可以用來檢驗已建立的 IPSec 篩選器，並指派 IPSec 原則讓它生效。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 總結
  
堡壘主機伺服器高度暴露在外界的攻擊風險中。必須盡可能保障它們的安全，以提供最大的可用性，並且將堡壘主機受到危害的影響減到最小。最安全的堡壘主機伺服器只限制高度信任的帳戶存取，並且在能夠完整執行功能的情況下，盡可能啟用最少的服務。
  
本單元說明規定的伺服器增強功能設定，以及用來保障堡壘主機伺服器安全的程序。可以透過本機「群組原則」套用其中許多設定。也提供設定和套用手動設定的步驟。
  
同時也提供建立和套用 IPSec 篩選器 (控制能夠與堡壘主機伺服器通訊的網路流量類型) 的詳細資訊。您可以修改這些篩選器，根據您環境中所執行之自訂角色的堡壘主機伺服器，封鎖特定類型的網路流量。
  
#### 其他資訊
  
下列資訊來源是在本產品公開發行時，與堡壘主機伺服器密切相關的最新可用主題，環境設定為執行 Windows Server 2003 的電腦。
  
如需有關建立私人網路的詳細資訊，請參閱在下列位置，由 Elizabeth D. Zwicky、Simon Cooper 和 Brent D. Chapman 所著作的《Firewalls and Virtual Private Networks》(英文)： <http://www.wiley.com/legacy/compbooks/press/0471348201_09.pdf>.
  
如需進一步有關防火牆和安全性的資訊，請參閱在下列位置，由 Chuck Semeria 所著作的《Internet Firewalls and Security-A Technology Overview》(英文)： <http://www.itmweb.com/essay534.htm>.
  
如需有關深度模型中進行防禦的資訊，請參閱在下列位置的《U.S. Military with Rod Powers》(英文)： <http://usmilitary.about.com/careers/usmilitary/library/glossary/d/bldef01834.htm>.
  
如需有關針對侵入者的保護資訊，請參閱在下列位置，由 Jay Beale 所著作的《Intruder Detection Checklist》(英文)： <http://www.cert.org/tech_tips/intruder_detection_checklist.html>.
  
如需有關增強堡壘主機功能的資訊，請參閱在下列位置，《Hardening Bastion Hosts 》(英文) 的＜SANS Info Sec Reading Room＞文件： <http://www.sans.org/rr/papers/index.php?id=420>.
  
如需進一步有關堡壘主機的資訊，請參閱在下列位置的《How Bastion Hosts Work》(英文)： <http://thor.info.uaic.ro/~busaco/teach/docs/intranets/ch16.htm>.
  
如需有關在 Windows Server 2003 中關閉「網際網路連線防火牆」的資訊，請參閱微軟知識庫的文件 《How To：Turn On the Internet Connection Firewall Feature in Windows Server 2003》(英文)，連結位置在： <http://support.microsoft.com/default.aspx?scid=317530>.
  
如需關於疑難排解「安全性設定和分析工具」的資訊，請參閱「知識庫」的文件《Problems After You Import Multiple Templates Into the Security Configuration and Analysis Tool》(英文)，連結位置在： <http://support.microsoft.com/default.aspx?scid=279125>。
  
[](#mainsection)[回到頁首](#mainsection)
