---
TOCTitle: '如何在小型企業環境中，設定 Windows XP SP2 網路保護技術'
Title: '如何在小型企業環境中，設定 Windows XP SP2 網路保護技術'
ms:assetid: 'c74175c6-46bd-4fd2-976f-9b89daf37348'
ms:contentKeyID: 20214503
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc875819(v=TechNet.10)'
---

如何在小型企業環境中，設定 Windows XP SP2 網路保護技術
======================================================

發佈日期: 2004 年 12 月 10 日 | 更新日期: 2006 年 10 月 26 日

##### 本頁內容

[](#ehaa)[簡介](#ehaa)
[](#egaa)[開始之前](#egaa)
[](#efaa)[套用安全性補充程式](#efaa)
[](#eeaa)[更新現有的群組原則物件](#eeaa)
[](#edaa)[設定群組原則物件](#edaa)
[](#ecaa)[關於 Internet Explorer 的安全性設定](#ecaa)
[](#ebaa)[以 GPUpdate 套用新的設定](#ebaa)
[](#eaaa)[相關資訊](#eaaa)

### 簡介

Active Directory® 目錄服務提供一種方式，讓您集中管理小型企業中工作站和伺服器的安全性設定。這項服務讓您以更安全、更輕鬆的方式管理工作站環境。

本文所討論的主題，是執行 Microsoft® Windows® XP Service Pack 2 (SP2) 之工作站的集中管理。實施方式則完全依賴 Active Directory 將群組原則物件 (GPO) 套用於工作站，以進行安全性設定的管理。

#### 本文件的目的

不同的組織有不同的安全性需求。不論客戶對安全性需求是多麼嚴格，都能利用本文所闡述的概念來管理工作站安全性。

[](#mainsection)[回到頁首](#mainsection)

### 開始之前

您必須先登入為 Domain Admins 群組的成員才能完成下列程序。

**附註** 若您無法對工作站或伺服器進行變更，可能是因為「群組原則」的關係。在這種情況下，您必須在「群組原則」層級進行變更。

請完成本文件的各項工作，以使用「群組原則」來設定 Windows XP SP2 網路防護技術：

-   套用安全性補充程式

-   更新現有的群組原則物件 (GPO)

-   設定資訊安全中心設定

-   設定 Windows 防火牆設定

-   設定 Internet Explorer 設定

-   設定網際網路通訊管理設定

-   使用 GPUpdate 套用設定

[](#mainsection)[回到頁首](#mainsection)

### 套用安全性補充程式

Microsoft 建議您將最新的安全性補充程式和 Service Pack 套用至 Windows 工作站和伺服器。套用補充程式之前，最好備份您的電腦或重要檔案。

**附註** 本文所提及的部份功能和部份必要安全性功能，是由較新的補充程式/Hotfix 所提供。若網域控制站的版本不夠新，可能沒有 GPO 中的 Windows XP SP2 工作站所需要的系統管理範本。沒有系統管理範本就無法使用新的 SP2 安全性功能。

[](#mainsection)[回到頁首](#mainsection)

### 更新現有的群組原則物件

在 Active Directory 中管理 GPO 的最好方式，請參閱 Microsoft 網站上的「[介紹群組原則管理主控台](http://www.microsoft.com/taiwan/windowsserver2003/gpmc/gpmcintro.mspx)」(中文)，網址是 http://www.microsoft.com/taiwan/windowsserver2003/gpmc/gpmcintro.mspx。這是以「群組原則物件編輯器」(GPOE) 嵌入式管理單元來使用 Microsoft Management Console (MMC) 的另一種方式。

GPMC 也使用「群組原則物件編輯器」來編輯 GPO。

1.  在 GPMC 中，連按兩下您要以新的系統管理範本加以更新的 GPO。這時 GPO 會在 GPOE 中開啟。

2.  按一下 **\[確定\]**，再按 **\[完成\]**。這個動作會套用至新範本。

3.  對每個 GPO 重複上述動作。

[](#mainsection)[回到頁首](#mainsection)

### 設定群組原則物件

執行下列程序，在您的環境中設定 GPO。

#### 設定資訊安全中心設定

在「群組原則」的控制下，可以在每部工作站上啟用「資訊安全中心」。如果有安裝「資訊安全中心」，則會通知工作站使用者有關 Windows 防火牆、防毒和「自動化更新」設定的狀態。依預設，「群組原則」不會啟用這項功能。

1.  開啟 GPMC，連按兩下您要使用的 GPO，將「資訊安全中心」實施於每部工作站上。

2.  在選取的 GPO 中，依序開啟 **\[電腦設定\]**、**\[系統管理範本\]**、**\[Windows 元件\]** 以及 **\[資訊安全中心\]**。

3.  連按兩下 **\[開啟資訊安全中心 (僅適用於網域 PC)\]**。

4.  啟用此設定。

5.  按一下 **\[確定\]**。

#### 設定 Windows 防火牆設定

這一節說明 GPO 中的「Windows 防火牆」設定，以及小型企業環境的建議設定。

1.  在選取的 GPO 中，依序開啟 **\[電腦設定\]**、**\[系統管理範本\]**、**\[網路\]**、**\[網路連線\]**、**\[Windows 防火牆\]** 以及 **\[網域設定檔\]**。

2.  連按兩下每項設定，並根據下表的資訊進行設定。

    **附註** 在您啟用網域設定檔中的 **\[定義程式例外\]** 之後，必須先輸入允許連線至電腦的所有程式，才能按一下 **\[確定\]**。

**表 1. 適用於小型企業的 Windows 防火牆建議設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >設定</th>
<th style="border:1px solid black;" >說明</th>
<th style="border:1px solid black;" >網域設定檔</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">保護所有網路連線</td>
<td style="border:1px solid black;">指定為所有網路連線啟用「Windows 防火牆」。</td>
<td style="border:1px solid black;">已啟用。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">不允許例外</td>
<td style="border:1px solid black;">指定丟棄所有來路不明的流量，包括例外的流量。</td>
<td style="border:1px solid black;">尚未設定。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">定義程式例外</td>
<td style="border:1px solid black;">以程式檔案名稱定義例外的流量。</td>
<td style="border:1px solid black;">已啟用，並在網路上的 Windows XP SP2 型電腦所使用的程式 (應用程式和服務) 進行設定。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">允許本機程式例外</td>
<td style="border:1px solid black;">啟用本機程式例外設定。</td>
<td style="border:1px solid black;">已停用。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">允許遠端管理例外</td>
<td style="border:1px solid black;">啟用使用工具的遠端設定。</td>
<td style="border:1px solid black;">已停用，除非您要使用 MMC 嵌入式管理單元來進行電腦的遠端管理。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">允許檔案和列印共用例外</td>
<td style="border:1px solid black;">指定是否允許檔案和列印共用流量。</td>
<td style="border:1px solid black;">已停用。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">允許 ICMP 例外</td>
<td style="border:1px solid black;">指定所允許的 ICMP 訊息類型。</td>
<td style="border:1px solid black;">已停用。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">允許遠端桌上型電腦例外</td>
<td style="border:1px solid black;">指定電腦是否能接受來自遠端桌上型電腦的連線要求。</td>
<td style="border:1px solid black;">已啟用。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">允許 UPnP 架構例外</td>
<td style="border:1px solid black;">指定電腦是否能接收來路不明的 UPnP 訊息。</td>
<td style="border:1px solid black;">已停用。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">禁止通知</td>
<td style="border:1px solid black;">停用通知。</td>
<td style="border:1px solid black;">已停用。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">允許記錄</td>
<td style="border:1px solid black;">啟用流量記錄並設定記錄檔設定。</td>
<td style="border:1px solid black;">尚未設定。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">禁止對多點傳播或廣播要求發出單點傳播回應</td>
<td style="border:1px solid black;">丟棄因回應多點傳播或廣播要求訊息而收到的單點傳播封包。</td>
<td style="border:1px solid black;">已啟用。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">定義連接埠例外</td>
<td style="border:1px solid black;">指定 TCP 和 UDP 例外的流量。</td>
<td style="border:1px solid black;">已停用。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">允許本機連接埠例外</td>
<td style="border:1px solid black;">允許本機連接埠例外設定。</td>
<td style="border:1px solid black;">已停用。</td>
</tr>
</tbody>
</table>
  
如需詳細資料，請參閱「[如何在小型企業環境中，使用群組原則設定 Windows 防火牆](http://www.microsoft.com/technet/security/smallbusiness/prodtech/windowsxp/fwgrppol.mspx)」(英文)，網址是 www.microsoft.com/technet/security/smallbusiness/prodtech/windowsxp/fwgrppol.mspx。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 關於 Internet Explorer 的安全性設定
  
安全性原則設定允許您管理可能會影響 Internet Explorer 安全性的特定狀況。在大部份的情況下，您會想要防止特定的行為，因此請確實啟用安全性功能。Microsoft 建議您採用 Internet Explorer 6，因為其最新功能會增加瀏覽器所提供的安全性。
  
#### 安全性區域
  
Internet Explorer 將網站區分為四個安全性區域，每個區域提供不同的安全性層級。這些安全性區域為 \[網際網路\]、\[近端內部網路\]、\[信任的網站\] 和 \[限制的網站\]。每個區域的安全性都能獨立設定為從「高」到「低」的層級。Internet Explorer 也讓使用者自訂每個安全性區域的安全性選項。Microsoft 已為每個區域定義預設的安全性設定。下表提供每個安全性區域的說明，以及 Microsoft 對每個區域的預設安全性設定。
  
**表 2. 安全性區域的說明和預設的安全性設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >安全性區域</th>
<th style="border:1px solid black;" >預設安全性層級</th>
<th style="border:1px solid black;" >說明</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">網際網路區域</td>
<td style="border:1px solid black;">中</td>
<td style="border:1px solid black;">[網際網路] 區域包含所有未包括在其他區域內的網站。<br />
<br />
<strong>附註</strong> 可能會發生來自網際網路的威脅。Microsoft 極力保護使用者不受來自網際網路的威脅，因此您無法將安全性層級設定為「低」，即使使用進階的 <strong>[自訂層級]</strong> 按鈕也是如此。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">近端內部網路區域</td>
<td style="border:1px solid black;">中-低</td>
<td style="border:1px solid black;">這個區域的所有網站都應位於防火牆內。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">信任的網站區域</td>
<td style="border:1px solid black;">低</td>
<td style="border:1px solid black;">[信任的網站] 區域內的網站可以執行較為廣泛的作業，並提示使用者儘量不要作出安全性決策。只有當您確定網站內容不會對電腦造成損害時，才將該網站新增到這個區域中。<br />
對於 [信任的網站] 區域，Microsoft 強烈建議您使用超文字傳輸通訊協定 (HTTP) 或安全性 (HTTPS) 通訊協定，以保護網站連線的安全性。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">限制的網站區域</td>
<td style="border:1px solid black;">高</td>
<td style="border:1px solid black;">這個區域允許您新增您認為不值得信任的網站。這個區域會控制並限制網站功能，但不會封鎖網站的存取。網站可由使用者新增，或是由群組原則強制執行。若要封鎖網站的存取，必須使用支援此項功能的 Proxy 伺服器。</td>
</tr>
</tbody>
</table>
  
#### 增加安全性
  
每個安全性區域都包含 30 多種以上可單獨修改的設定，以增加特定功能。大部份的設定都提供啟用、停用或提示等三種選項。Microsoft 建議客戶在所有安全性區域中，限制使用者提示選項設定的次數。強烈的資訊安全性原則會限制使用者權限，並禁止使用者採取會削弱安全性的行動。每個安全性區域的設定都應個別定義及設定—不建議您對所有區域都採用相同的定義。下表提供不同的安全性區域中，幾項預設設定的「採樣」(sampling)。這些設定和其他設定都能加以修改，以符合組織的需求。
  
**表 3. 安全性區域原則設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >安全性區域</th>
<th style="border:1px solid black;" >原則設定</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">網際網路區域</td>
<td style="border:1px solid black;">使用快顯封鎖程式 = 啟用<br />
自動提示 ActiveX 控制項 = 停用<br />
下載簽署的 ActiveX 控制項 = 提示<br />
檔案下載 = 啟用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">近端內部網路區域</td>
<td style="border:1px solid black;">使用快顯封鎖程式 = 停用<br />
自動提示 ActiveX 控制項 = 啟用<br />
下載簽署的 ActiveX 控制項 = 提示<br />
檔案下載 = 啟用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">信任的網站區域</td>
<td style="border:1px solid black;">使用快顯封鎖程式 = 停用<br />
自動提示 ActiveX 控制項 = 啟用<br />
下載簽署的 ActiveX 控制項 = 啟用<br />
檔案下載 = 啟用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">限制的網站區域</td>
<td style="border:1px solid black;">使用快顯封鎖程式 = 啟用<br />
自動提示 ActiveX 控制項 = 停用<br />
下載簽署的 ActiveX 控制項 = 停用<br />
檔案下載 = 停用</td>
</tr>
</tbody>
</table>
 

ActiveX® 是功能強大的延伸性網頁開發平台，可豐富使用者的線上經驗。許多企業客戶都將 ActiveX 控制項用於內部特定業務應用程式，因此 Internet Explorer 上的 ActiveX 必須加以啟用。您的安全性標準和所接受的使用原則可能會要求停用網際網路區域的 ActiveX。不管是以「群組原則」或是將安全性區域控制項設定為「高」以關閉 ActiveX 控制項，都會使網站無法正常運作。Microsoft 建議組織定義此問題的處理原則，並根據企業的審核程序，訂定允許存取的策略。

ActiveX 具有在瀏覽器主控台上執行命令的能力，因此確實是一項值得注意的安全性考量。建議只允許從信任的網站上執行 ActiveX。

如需有關安全性區域和設定選項的詳細說明，請參閱「[設定安全性區域](http://www.microsoft.com/windows/ie/using/howto/security/setup.mspx)」(英文)，網址是 www.microsoft.com/windows/ie/using/howto/security/setup.mspx。

#### 隱私權/Cookies

有些網站為提供更強大的個人化線上經驗，會將資訊儲存在您電腦上的小型文字檔中。這種檔案稱為 Cookies。Internet Explorer 6 配備多項機制，可控制 Cookies 的使用。

Cookies 有多種不同的類型。第一方 Cookies 只能由發行網站讀取，其他網站則無法讀取。另一種類型稱為協力廠商 Cookies，是由網站實體用來記錄訪客資料。協力廠商 Cookie 則是由多個網站共同使用。所包含的資料範圍從使用者 ID、密碼到郵遞區號。

-   **第一方 Cookies**。只能由發行網站讀取。

-   **協力廠商 Cookies**。可由多個網站讀取和寫入。

使用者可能不知道，自己對儲存於 Cookies 中的資料是否有控制權。即使只是按一下核取方塊，選擇要記住帳單地址，就可能在第一方或協力廠商 Cookie 中留下不必要的資料。

每個組織都必須決定 Cookies 專屬的處理原則。Microsoft 建議將安全性層級至少設定為「**中**」。此項設定會封鎖隱私權原則不夠嚴謹的協力廠商 Cookies、封鎖會在沒有暗示同意下使用個人識別資訊的協力廠商 Cookies，同時限制在沒有暗示同意下使用個人識別資訊的第一方 Cookies。如果將安全性層級設定為「**高**」，則會限制所有 Cookies，其他設定則會在特定情況下允許所有 Cookies。如果將安全性層級設定為「**低**」，則會無條件允許所有的 Cookies。

您可以新增要略過整體設定的網站。新增網站的選項為 **\[自動封鎖\]** 或 **\[自動允許\]**。不論您選擇的安全性層級為何，都能新增網站。「群組原則」不僅可用來強制使用 Cookies 設定，也能用於網站上。

**附註** Cookies 無法在每個安全性區域中加以控制。設定值會套用於這四個安全性區域上。

#### 快顯封鎖程式

快顯封鎖程式會封鎖大部份不必要的快顯視窗。使用者按下連結時所開啟的快顯視窗則不會被封鎖。您可以設定每個安全性區域的快顯封鎖程式，讓相同網站在不同的安全性區域中分別遭到封鎖或是被允許。「群組原則」可用來在每個安全性區域中強制執行快顯封鎖程式，並新增所允許的網站清單。

不斷出現且數量龐大的快顯視窗會變得相當累贅，使得瀏覽器根本無法使用。每次封鎖快顯視窗時，都會註記在 Internet Explorer 工具列上。

**附註** 快顯封鎖程式可以在每個安全性區域中加以控制，但是允許的網站則會同時新增到這四個區域中。

#### 網際網路程式

Internet Explorer 可設定為啟動其他程式來傳送電子郵件、管理連絡人或檢視網頁來源。例如，當使用者按一下網頁上的電子郵件地址時，Internet Explorer 就會開啟所定義的電子郵件程式，並載入已註明地址的外寄電子郵件。這項功能讓您不需另外開啟程式並手動輸入電子郵件地址，就能輕鬆傳送電子郵件。但是，這項新增功能也伴隨著潛在的風險。如果組織的標準應用程式變更了任何一個相關聯的程式，使用者將會遇到非預期的行為或功能。「群組原則」可用來強制採用此程式清單的設定，在一定程度上保證不啟動您不想要的程式。

#### 附加元件

附加元件是一種小程式，可用來執行特定功能，並由網頁根據需要載入。「工具列和瀏覽器輔助物件」(BHO) 為另一種類型的程式，可安裝額外的按鈕和功能，以便從瀏覽器內部延伸其功能。Microsoft 建議組織定義可接受的工具列和 BHO 清單，並使用「群組原則」來強制採用這些設定。

許多開發人員都使用 ActiveX 平台來建立工具，以提高生產力或增強功能。Microsoft 鼓勵開發社群繼續提供這些附加元件，但也瞭解這些附加元件必須從信任的來源加以部署。Internet Explorer 6 所提供的 Authenticode 可以利用數位簽章來驗證附加元件的驗證性。Microsoft 建議組織在 \[網際網路\] 區域內，只允許有簽章的附加元件。\[近端內部網路\] 區域內的網站不需要 Authenticode 簽章，因為這些附加元件應由信任的內部開發人員所開發。

#### 為 Internet Explorer 6 設定群組原則

Internet Explorer 6 所有的安全性功能都可由「群組原則」加以設定並確保安全性。有多種以 GPO 為基礎的安全性設定可用來管理各種 IE 元件，因此在本文中，我們只把重點放在四種主要的分支上 (即下列程序中的 a、b、c 和 d)。「群組原則物件編輯器」提供這四種分支下，所有設定之衍生結果的詳細資料。請仔細閱讀每項說明，並在實作前，先測試所需設定的有效性。

1.  開啟群組原則管理主控台。

2.  建立新的群組原則物件 (GPO)；例如，Internet Explorer 6。

3.  Internet Explorer 原則係包含在以下「群組原則物件編輯器」之原則樹狀目錄的四種分支中。在這四種分支中設定每個原則物件，以符合組織的需求。

    1.  **\[電腦設定\]**、**\[系統管理範本\]**、**\[Windows 元件\]**、**\[Internet Explorer\]**

        這個分支還有其他安全性原則，可用來鎖定瀏覽器本身之外的安全性設定。其中最實用的原則之一就是 **\[安全性區域：不允許使用者變更原則\]**。GPO 預設為停用此原則。若啟用這項原則，則會阻止使用者變更瀏覽器設定中的任何安全性設定。Microsoft 建議將此設定值變更為 **\[已啟用\]**。這些設定經「群組原則」設定之後，即使本機「系統管理員」也無法加以變更。其他還有多項可加以啟用的原則，有些與安全性有關，有些則無關。啟用這些原則之前，請仔細閱讀相關說明。

    2.  **\[電腦設定\]**、**\[系統管理範本\]**、**\[系統\]**、**\[網際網路通訊設定\]**

        這些分支適用於 Window XP SP2。其中包含 20 種新的原則，涵蓋範圍從網頁發佈功能到多媒體支援。**\[關閉網際網路檔案關聯服務\]** 原則可以在使用者從網站下載內容之後，避免瀏覽器開啟與副檔名相關聯的應用程式。這項功能就如同作業系統以 Notepad.exe 開啟副檔名為 .txt 的檔案一樣。另一項 **\[關閉透過 HTTP 進行列印\]** 原則可用來限制使用者透過使用 HTTP 的網際網路/內部網路進行列印。這項原則並不會影響使用者自行架設 HTTP 印表機的能力。啟用這些原則之前，請仔細閱讀相關說明。

    3.  **\[使用者設定\]**、**\[Windows 設定\]**、**\[Internet Explorer 維護\]**、**\[安全性\]**、**\[程式\]**

        這兩節包含會影響瀏覽器安全性的設定/原則。其中所包含的使用者層級設定，可以在個別的瀏覽器安全性/隱私權設定中找到。建議您使用 Microsoft 最基本的預設值，但是還需要進一步設定，以符合組織需求。

        **附註** 網站可以新增至 \[網際網路\] 以外的所有區域中。仔細挑選您要新增至 \[近端內部網路\]、\[信任\] 和 \[限制\] 區域的網站，因為這些網站會套用至以 GPO 連結的所有工作站和伺服器。

    4.  **\[使用者設定\]**、**\[系統管理範本\]**、**\[Windows 元件\]**、**\[Internet Explorer\]**

        此分支所包含的詳細設定會限制使用者對瀏覽器設定進行變更，但非完全禁止此動作。這些設定會套用至「網際網路暫存檔」控制項等項目以及首頁的變更。此分支包含許多設定選項，Microsoft 建議系統管理員將這些選項套用至實際執行環境之前，先閱讀相關說明並測試可能造成的影響。

4.  在您完成原則編輯器的工作之後，請將新的 GPO 連結至您所有的網域與 Windows 工作站和伺服器。

5.  根據會受到此 GPO 影響的群組、使用者和電腦，設定 GPO 的**安全性篩選**。有些原則是專為電腦所設計，有些原則僅適用於使用者。

[](#mainsection)[回到頁首](#mainsection)

### 以 GPUpdate 套用新的設定

GPUpdate 公用程式可重新整理以 Active Directory 為基礎的「群組原則」設定。設定「群組原則」之後，您可以等候一段標準重新整理循環時間，讓設定套用到用戶端電腦。依預設，此重新整理循環時間為每隔 90 分鐘，並隨機偏移增減 30 分鐘。此程序能夠將測試原則更快速地推進工作站。

若要在標準循環時間之間重新整理「群組原則」，請依照下列步驟使用 GPUpdate 公用程式：

1.  從 Windows XP SP2 桌面，按一下 **\[開始\]**\]，然後按 **\[執行\]**。

2.  在 **\[開啟\]** 方塊中，鍵入 **cmd**，然後按一下 **\[確定\]**。這時會出現命令提示字元視窗。

3.  在命令提示字元中，鍵入 **GPUpdate**，然後按一下 **\[確定\]**。您會看到下列螢幕擷取畫面所顯示的訊息：

    [![](images/Cc875819.XPNPT01(zh-tw,TechNet.10).gif)](https://technet.microsoft.com/zh-tw/cc875819.xpnpt01_big(zh-tw,technet.10).gif)

    若要關閉命令提示字元，請鍵入 **exit**，然後按下 ENTER 鍵。

[](#mainsection)[回到頁首](#mainsection)

### 相關資訊

如需安全性相關術語的定義，請參閱下列連結：

-   位於 Microsoft 網站的「[Microsoft 資訊安全辭彙](http://www.microsoft.com/security/glossary.mspx)」(英文)，網址是 http://go.microsoft.com/fwlink/?linkid=35468。

如需有關 Windows XP SP2 網路防護的詳細資訊，請參閱下列連結：

-   "「[Microsoft Windows XP Service Pack 2 中的功能變更，第 2 章：網路保護技術](http://www.microsoft.com/taiwan/technet/prodtechnol/winxppro/maintain/sp2netwk.mspx)」(中文)，位於 Microsoft TechNet 網站中，網址是 http://www.microsoft.com/taiwan/technet/prodtechnol/winxppro/maintain/sp2netwk.mspx。

-   "「[在管理環境中使用 Windows XP Professional Service Pack 2：控制網際網路的通訊](http://go.microsoft.com/fwlink/?linkid=35489)」(英文)，位於 Microsoft TechNet Web 網站中，網址是 http://go.microsoft.com/fwlink/?linkid=35489。

-   位於 Microsoft 下載中心網站的「[部署 Microsoft Windows XP Service Pack 2 的 Windows 防火牆設定](http://go.microsoft.com/fwlink/?linkid=35303)」(英文)，網址是 http://go.microsoft.com/fwlink/?linkid=35303。

如需有關 Windows XP SP2 安全性的詳細資訊，請參閱下列連結：

-   位於 Microsoft 下載中心網站的「[*Windows XP 安全性指南*](http://go.microsoft.com/fwlink/?linkid=35309)」(英文)，網址是 http://go.microsoft.com/fwlink/?linkid=35309。

-   [*《Windows XP 安全性指南，附錄 A：應考量的金鑰設定 (中文) 》*](http://www.microsoft.com/taiwan/technet/security/prodtech/windowsxp/secwinxp/xpsgapxa.mspx)，位於 Microsoft TechNet 網站中，網址是 http://www.microsoft.com/taiwan/technet/security/prodtech/windowsxp/secwinxp/xpsgapxa.mspx。

如需有關「群組原則」的詳細資訊，請參閱下列連結：

-   "位於 Microsoft 下載中心網站的「[在 Microsoft Windows Server 中疑難排解群組原則](http://go.microsoft.com/fwlink/?linkid=35481)」(英文)，網址是 http://go.microsoft.com/fwlink/?linkid=35481。

-   位於 Microsoft Windows Server System 網站的「[使用群組原則管理主控台進行企業管理](http://www.microsoft.com/taiwan/windowsserver2003/gpmc/default.mspx)」(中文)，網址是 http://www.microsoft.com/taiwan/windowsserver2003/gpmc/default.mspx。

**下載**

[取得「如何在小型企業環境中，設定 Windows XP SP2 網路保護技術」](http://go.microsoft.com/fwlink/?linkid=70393) (英文)

[](#mainsection)[回到頁首](#mainsection)
