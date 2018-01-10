---
TOCTitle: Baseline Security Analyzer
Title: Baseline Security Analyzer
ms:assetid: '13deb362-eeaf-478c-898d-d1748b98ee88'
ms:contentKeyID: 20214359
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Dd548176(v=TechNet.10)'
---

Baseline Security Analyzer
==========================

![](images/Dd548176.community-sm(zh-tw,TechNet.10).gif)**本頁索引**

　　![](images/Dd548176.arrow_px_down(zh-tw,TechNet.10).gif)[客戶問題](#ba)
　　![](images/Dd548176.arrow_px_down(zh-tw,TechNet.10).gif)[MBSA 功能](#bb)
　　![](images/Dd548176.arrow_px_down(zh-tw,TechNet.10).gif)[作業模式](#bc)
　　![](images/Dd548176.arrow_px_down(zh-tw,TechNet.10).gif)[弱點檢查說明](#bd)
　　![](images/Dd548176.arrow_px_down(zh-tw,TechNet.10).gif)[其他資源](#be) 

**白皮書**
作業系統
Microsoft Corporation
發行日期：2002 年 4 月

Microsoft® Baseline Security Analyzer (MBSA) 是一種工具，可以讓個別的家庭或公司使用者或系統管理員掃描一部或多部 Windows® 系統電腦，檢查是否有一般的安全性組態錯誤。MBSA 會掃描 Windows 系統電腦，並且檢查作業系統和其他已安裝的元件 (例如 Windows 2000 Server 的 Internet Information Services (IIS) 和 SQL Server™) 有沒有安全性組態錯誤，以及是否具備最新的安全性 Hotfix 和修補套件。MBSA 是 Microsoft「策略技術保護專案」(Strategic Technology Protection Program) 所發展的成果。 
若要下載 Microsoft Baseline Security Analyzer (MBSA)，請按一下[這裡](http://support.microsoft.com/directory/article.asp?id=kb;en-us;q320454&)。 

[](#mainsection)[回到頁首](#mainsection)

### 客戶問題

![](images/Dd548176.MBSAWP01(zh-tw,TechNet.10).gif)

電腦安全性、安全性弱點和威脅不僅是資訊技術人員關切的事，也是任何電腦使用者的隱憂。大部分公司和許多家庭使用者都是以「全天候連線」的方式連線到 Internet – 這種連線方式也讓他們自己暴露於病毒、駭客及服務阻斷攻擊的潛在威脅之下。 
來自「Code Red」和「Nimda」這類病毒的攻擊正不斷增加，對於全球的企業生產力造成了驚人的破壞。維護連線到 Internet 之系統的安全，是在這個數位時代從事商務的基本考量。 

**策略技術保護專案**

Microsoft 相信每家公司不論大小，在進行線上商務的時候都應該要有而且也應該期盼安全的體驗。由於最近的病毒案例愈來愈複雜，整個運算產業都需要強化對 IT 系統和資料的保護程度。這就是 Microsoft 為何要發起「策略技術保護專案」(STPP) 的原因。STPP 是 Microsoft 為對業界提供保護其 Windows 網路所需的工具和資訊，在人力與資源上前所未有的動員。 
每家企業和每個人都應該能在 Internet 和他們的網路上安全地工作、通訊和交易。在 STPP 中，為回應客戶對於找出安全性組態錯誤之有效方法的直接需求，Microsoft 特別開發了這個 Microsoft Baseline Security Analyzer (MBSA)。 
MBSA 的設計可以評估多部 Windows 系統電腦是否有弱點，並且判斷它們是否有最新的安全性相關套件和 Hotfix。依據您的特定需求，MBSA 可提供： 

-   使用者 – 個別公司或家庭使用者可以啟動 MBSA 工具來掃描單一電腦並且取得安全性的評估、報告和建議改正動作的清單。 

-   系統管理員 – 除了掃描單一電腦之外，系統管理員還可以使用 MBSA 工具來掃描他們網路上的多部電腦。 

除了存取 Microsoft 網站來判斷有哪些安全性修檔和修補套件可用之外，它不會與 Microsoft 有任何互動。MBSA 在您電腦上執行的掃描會確保您系統資訊的安全和隱私性。沒有任何資訊會傳送到 Microsoft 或在 Internet 上傳送。這項初始檢查可確保您獲得安全性修正檔和修補套件資料庫的最新、最精確的版本。 

[](#mainsection)[回到頁首](#mainsection)

### MBSA 功能

MBSA 的設計可以掃描執行 Windows NT® 4、Windows 2000、Windows XP Professional (商用版) 和 Windows XP Home Edition (家用版) 的電腦。MBSA 可以從任何執行 Windows 2000 Professional、Windows 2000 Server、Windows XP Home (家用版) 或 Windows XP Professional (商用版) 的電腦執行。在未來的版本中，MBSA 將可以掃描 Windows .NET Server 電腦，或從它上面執行。 

#### MBSA 和 HFNetChk 工具

![](images/Dd548176.MBSAWP02(zh-tw,TechNet.10).gif)

MBSA 會使用 HFNetChk 工具來識別系統是否已套用了安全性更新檔。HFNetChk 是藉由參考 Microsoft 不斷更新的可延伸標記語言 (XML) 安全性 Hotfix 資料庫來執行這項工作。 
這個 XML 資料庫含有每項 Microsoft 產品可用之 Hotfix 的相關資訊。這個檔案含有安全性公告的名稱和標題，以及各種產品專屬安全性 Hotfix 的詳細資料，包括：每個 Hotfix 套件中的檔案及檔案版本與 總和檢查碼、Hotfix 安裝套件所套用的登錄機碼、哪些套件取代哪些套件的相關資訊、相關 Microsoft 知識庫文件編號，等等。 

**MBSA 勝過 HFNetChk 的地方**

MBSA 是 HFNetChk 功能的超集。HFNetChk 只能處理 Hotfix 和 Service Pack，而 MBSA 則提供了易於使用的介面和額外的能力。這些能力包括檢查 Windows 桌面和伺服器是否為一般安全性最佳措施 (例如強式密碼)、掃描執行 IIS 和 SQL Server 的伺服器有沒有一般安全性組態錯誤，以及檢查 Microsoft Office、Outlook 和 Internet Explorer 中有沒有設定錯誤的安全性區域設定。MBSA 也提供了一次掃描整個電腦網域的能力。Microsoft 建議客戶使用 MBSA 工具，因為它的功能可以為客戶增強和提供超越 HFNetChk 工具本身所能提供的額外功能和最佳措施。 

**MBSA 和 HFNetChk 報告選項？**

HFNetChk 工具設計上是從命令行使用，而 MBSA 則屬於 GUI 架構的設計。客戶在對 HFNetChk 的輸出與 MBSA 進行比較時應該要小心。HFNetChk 工具有許多可以配合它一起使用的參數，其中有些會影響 HFNetChk 產生的輸出。如果是從 .BAT 檔案呼叫 HFNetChk，或者使用了不同於 MBSA 的參數，可能會報告不同的結果。在未來的 MBSA 版本裡將可設定這些參數。 

#### MBSA 取代 Microsoft Personal Security Advisor

MBSA 工具的設計目標就是要取代 Microsoft Personal Security Advisor (MPSA) 工具。MBSA 工具比 MPSA 工具更具有彈性，因為它一次可以掃描多部電腦，而且還會檢查其他已安裝軟體 (例如 SQL Server) 的相關修補套件。

##### Windows 作業系統的弱點

操作一個安全的系統，最重要的部分還是在於最新的安全性修補套件。所以瞭解系統已經套用了哪些修補套件就變得非常重要，而更重要的，是知道哪些還沒有套用。 
當您第一次執行 MBSA 工具時，它必須取得這個 XML 檔的複本，才能讓這個工具找到每一產品適用的 Hotfix。1 Microsoft 下載中心網站有這個 XML 檔案的壓縮版 (數位簽署的 .cab 檔案)。MBSA 會下載這個 .cab 檔案，驗證簽署2，然後將這個 .cab 檔解壓縮到執行 MBSA 的本機電腦上。請注意，.cab 檔案是類似 .zip 檔的壓縮檔。 
在解壓縮 .CAB 檔案之後，MBSA 會掃描您的電腦 (或選取的電腦) 來判斷您所執行的作業系統、Service Pack 以及各種程式。然後 MBSA 會解析這個 XML 檔並且找出適合您所安裝之軟體組合的安全性修補套件。 
MBSA 為了判斷指定電腦上安已經安裝了哪些修補套件，會對下列三個項目進行評估：修補套件所安裝的登錄機碼、檔案版本，以及修補套件所安裝之每一檔案的總和檢查碼。 
在預設組態中，MBSA 會將 XML 子集產生的檔案詳細資料及登錄機碼與所掃描電腦上的檔案與登錄詳細資料進行比對。如果電腦上的任何檔案或登錄機碼詳細資料與 XML 檔案中儲存的資訊不相符，相關的安全性修補套件就會被識別為未安裝，並且將結果顯示在安全性報告中。與這個修補套件相關的特定 Microsoft 知識庫文件編號也會顯示在螢幕上。 
一般而言，MBSA 會掃描 Windows 作業系統 (Windows NT 4、Windows 2000、Windows XP) 中的安全性問題，例如「Guest」帳戶狀態、檔案系統類型、可用的檔案共用、系統管理員群組的成員等。每一作業系統檢查的說明以及修正所發現問題的指示也會顯示在安全性報告中。這些檢查更詳細的說明已列在本文附件中。 

##### Hotfix

MBSA 不僅會掃描 Windows 的 Hotfix，也會掃描其他產品相關的 Hotfix。MBSA 會掃描適用於下列產品的 Hotfix： 
Windows NT 4.0 

-   Windows 2000 

-   Windows XP 

-   所有系統服務，包括 IIS 4.0 和 5.0 

-   SQL Server 7.0 和 2000 (包括 Microsoft Data Engine) 

-   Internet Explorer 5.01 和更新版本 

##### 簡單密碼

MBSA 在掃描期間會檢查電腦是否使用了空白或簡單密碼。這個工具會檢查目標電腦上有沒有下列密碼： 

-   密碼為空白 

-   密碼 = 使用者名稱 (帳戶名稱) 

-   密碼 = 電腦名稱 

-   密碼 = 「password」 

-   密碼 = 「admin」 

-   密碼 = 「Administrator」 

MBSA 會嘗試使用每一個密碼來變更目標電腦上的密碼。如果作業成功，就表示該帳戶是使用那個密碼。MBSA 不會永久性地重設或變更這個密碼，但是它會報告說您的密碼太容易被猜中了。 
必須注意的是，依電腦上使用者帳戶數目的多寡，這項檢查可能會花很長的時間。系統管理員在掃描網路上的網域控制站之前，應該先停用這項檢查。 
注意 如果啟用了對電腦登入/登出事件的稽核，這項檢查可能會在安全性記錄檔中產生事件記錄項目。 

#### Internet Information Server

這個檢查群組會掃描 IIS 4.0 和 5.0 中的安全性問題，例如電腦上是否有範例應用程式和某些虛擬目錄存在。這個工具也會檢查可以協助系統管理員設定和保護 IIS 伺服器的 IIS Lockdown 工具是否已在電腦上執行。每一 IIS 檢查的說明以及修正所發現問題的指示也會顯示在安全性報告中。 

#### Microsoft SQL Server

這個檢查群組會掃描 SQL Server 7.0 和 SQL Server 2000 中的安全性問題，例如驗證模式類型、sa 帳戶密碼狀態和 SQL 服務帳戶成員資格。每一 SQL Server 檢查的說明以及修正所發現問題的指示也會顯示在安全性報告中。 

[](#mainsection)[回到頁首](#mainsection)

### 作業模式

![](images/Dd548176.MBSAWP03(zh-tw,TechNet.10).gif)

**單一電腦**

在 MBSA 最簡單的作業模式裡，它可以掃描單一電腦。這種模式的典型案例就是「自我掃描」。當您選擇 \[Pick a computer to scan\] 動作時，您可以輸入想要掃描的電腦名稱或是 IP 位址。根據預設，當您選擇這個選項時，所顯示的電腦名稱將會是執行這個工具的本機電腦。 

**多部電腦**

如果您選擇 \[Pick Multiple Computers to Scan\]，就可以掃描多部電腦。您可以輸入網域名稱來掃描整個網域，也可以指定 IP 位址的範圍來掃描在這個範圍中找到的所有 Windows 架構電腦。

**要求系統管理員存取權限**

要掃描電腦，必須擁有系統管理員存取權限。在「自我掃描」的情況中，執行 MBSA 的帳戶必須是系統管理員，或者是本機系統管理員群組的成員。在掃描多部電腦的情況中，您必須是每一部電腦的系統管理員，或者是網域的系統管理員。 

**檢視安全性報告**

每次掃描電腦或電腦群組時，就會針對掃描的每部電腦產生一份報告，並且儲存在執行 MBSA 的電腦上。這些報告的位置會列在螢幕的上方 (儲存在使用者設定檔資料夾下)。安全性報告是以 XML 格式儲存。 
您可以很容易地依據電腦名稱、掃描日期、IP 位址或安全性評估來排序這些報告。這項功能可以讓您在一段時間之後很容易地對安全性掃描進行比對。 

[](#mainsection)[回到頁首](#mainsection)

### 弱點檢查說明

![](images/Dd548176.MBSAWP04(zh-tw,TechNet.10).gif)

#### 系統管理員群組成員資格 

這項檢查會識別並且列出屬於本機系統管理員群組的個別使用者帳戶。如果偵測到兩個以上的系統管理員帳戶，這個工具就會列出這些帳戶的名稱，並且將檢查標示為一項潛在弱點。一般而言，最好是儘量減少系統管理員的人數，因為系統管理員必定會擁有電腦的完整控制權。 

#### 稽核

這項檢查會判斷所掃描的電腦上是否啟用了稽核。Microsoft Windows 有一項稽核功能，可以追蹤和記錄系統上的特定事件，例如成功及失敗的登入嘗試。藉由監視系統的事件記錄檔，可以協助找出潛在的安全性問題和惡意的活動。 

#### 自動登入

這項檢查會判斷所掃描的電腦上是否啟用了自動登入功能，以及登入密碼是以加密方式儲存在登錄中還是以純文字方式儲存。如果啟用了自動登入而且登入密碼是以純文字儲存，安全性報告就會將它反映為重大弱點。如果啟用了自動登入而且登入密碼是以加密方式儲存在登錄中，安全性報告就會將它標示為潛在弱點。 

**注意** 如果您看到「Error Reading Registry」(讀取登錄時發生錯誤) 的訊息，可能是您沒有啟用遠端登錄服務。 
自動登入會將您的登入名稱和密碼儲存在登錄中，可以讓您自動登入 Windows 2000 或 Windows NT，而不需要在登入使用者介面中輸入使用者名稱和密碼。但是，自動登入也可能會讓其他使用者存取您的檔案，以及用您的名稱在系統上從事惡意的動作 (例如，可以實際接觸電腦的任何人都可以啟動作業系統並且自動登入)。如果您啟用了自動登入而且不想變更它，請確定您沒有在電腦上儲存任何敏感的資訊。因為任何能實際接觸您電腦的人都可以使用這項自動登入功能，所以您應該只在信任而且安全的環境下才使用這項功能。 
您可以將用於自動登入的密碼以純文字方式儲存在登錄中，也可以將它加密作為本機安全性授權 (LSA) 密碼。 

#### 檢查不需要的服務 

這項檢查會判斷所掃描的電腦是否啟用了 services.txt 檔案中包含的服務。這個 services.txt 檔案是所掃描電腦上不應該執行之服務的可設定清單。這個檔案是由 MBSA 安裝，並且儲存在這個工具的安裝資料夾中。工具的使用者應該設定這個 services.txt 檔案，將要對每部所掃描電腦執行檢查的特定服務加入檔案。由工具預設安裝的 services.txt 檔案含有下列服務： 
MSFTPSVC (FTP)
TlntSvr (Telnet)
RasMan (遠端存取服務管理員)
W3SVC (WWW)
SMTPSVC (SMTP) 
在 Microsoft Windows XP、Windows 2000 和 Windows NT 4.0 中，服務是於電腦執行作業系統時在幕後執行的程式。它並不需要使用者登入。這些服務是用來執行一些與使用者無關的工作，例如等候內送傳真的傳真服務。 

#### 網域控制站 

這項檢查會識別所掃描的電腦是否為網域控制站。 
對於 Windows XP、Windows 2000 或 Windows NT 網域而言，網域控制站是在網域中驗證網域登入和維護安全性原則與安全性帳戶主資料庫的伺服器。網域控制站會管理使用者存取網路，包括登入、驗證，以及存取目錄和共用資源。網域控制站也存有所有網域使用者帳戶，包括主要系統管理員帳戶。基於這些原因，網域控制站應被視為需要加強保護的重要資源。您應該驗證是否真的需要這部電腦作為網域控制站，並且已採取適當步驟來保護這部電腦的存取。 

#### 檔案系統 

這項檢查會判斷您在每個硬碟上使用的是哪種檔案系統，以確定它是否為 NTFS 檔案系統。NTFS 是一種可以讓您控制或限制對個別檔案或目錄存取的安全檔案系統。例如，如果您希望讓同事能夠檢視您的檔案，但是不將檔案變更，可以使用 NTFS 提供的存取控制清單 (ACL) 來達成這個目的。 
**注意** 如果要順利執行這項檢查，必須使用管理磁碟共用將磁碟機共用。

#### Guest 帳戶 

這項檢查會判斷所掃描的電腦上是否啟用了內建的 Guest 帳戶。 
Guest 帳戶是個內建帳戶，當使用者在電腦或網域中沒有帳戶，或在電腦網域信任的任何網域中，可以用它來登入執行 Windows 2000 或 Windows NT 的電腦。在使用簡單檔案共用的 Windows XP 電腦上，所有從網路連線的使用者都會對應到 Guest 帳戶做為安全性模型的一部分。如果在 Windows NT、Windows 2000 和 Windows XP 電腦 (不是使用簡單檔案共用) 上啟用了 Guest 帳戶，就會在安全性報告中將它標示為弱點。如果在使用簡單檔案共用的 Windows XP 電腦上啟用了 Guest 帳戶，則不會被標示為弱點。 

#### IIS 上的 MSADC 和 Scripts 虛擬目錄 

這項檢查會判斷所掃描的 Internet Information Services (IIS) 電腦上是否安裝了 MSADC (簡單資料存取指令碼) 和 Scripts 虛擬目錄。這些目錄通常含有一些應該移除 (如非必要) 以降低電腦受攻擊面的指令碼。 
IIS Lockdown 工具會關閉 IIS 中非必要的功能 (例如上面這個)，以降低電腦暴露給攻擊者的機會。 

#### IISADMPWD 虛擬目錄

這項檢查會判斷所掃描的電腦上是否安裝了 IISADMPWD 目錄。IIS 4.0 可以讓使用者變更他們的 Windows 密碼，也會通知使用者他們的密碼即將屆期。IISADMPWD 虛擬目錄是安裝為 IIS 4.0 中預設網站的一部分，它所包含的檔案是由這項功能使用。這項功能是實作為 \\System32\\Inetsrv\\Iisadmpwd 目錄中的一組 .htr 檔案和一個名為 Ism.dll 的 ISAPI 擴充程式。 

#### 網域控制站上的 IIS

這項檢查會判斷 Internet Information Services (IIS) 是否在做為網域控制站的系統上執行。除非正被掃描的電腦是 Small Business Server，否則這種情況會在掃描報告中被標示為重大弱點。 
建議您不要在網域控制站上執行 IIS Web 伺服器。網域控制站含有敏感的資料 (例如使用者帳戶資訊)，所以不應該在其他角色中使用。如果在網域控制站上執行 Web 伺服器，將會增加保護伺服器和防止攻擊的複雜程度。 

#### IIS Lockdown 工具

這項檢查會判斷 IIS Lockdown 工具 2.1 版 (Microsoft Security Tool Kit 的一部分) 是否已在掃描的電腦上執行。IIS Lockdown 工具是以關閉 IIS 中不必要功能的方式運作，藉以降低攻擊者可以利用的攻擊面。 

#### IIS 記錄功能 

這項檢查會判斷是否已啟用 Internet Information Services (IIS) 記錄功能，是否使用了 W3C 擴充記錄檔格式。 
IIS 記錄功能超越了 Windows 事件記錄或效能監視功能的範圍。記錄的資訊可以包含像是誰造訪過您的網站、造訪者檢視了些什麼，以及這些資訊上次是什麼時候被檢視的。您可以監視對您的網站、虛擬資料夾或檔案的存取嘗試 (不論成功與否)，包括讀取或寫入檔案這類的事件。您可以針對任何站台、虛擬資料夾或檔案，選擇要稽核哪些事件。只要定期檢視這些檔案，您就可以察覺伺服器或站台上哪些區域可能遭到攻擊或者有其他安全性問題。您可以針對個別網站啟用記錄功能和選擇記錄檔格式。啟用記錄功能時，是針對網站的所有資料夾啟用，但是您可以針對特定的目錄停用它。 

#### IIS 上層路徑

這項檢查會判斷所掃描的電腦上是否啟用了 ASPEnableParentPaths 設定。啟用 IIS 上的上層路徑之後，Active Server Pages (ASP) 網頁就可以使用目前目錄的上層目錄相對路徑 – 也就是，使用 .. 語法的路徑。 

#### IIS 範例應用程式

這項檢查會判斷電腦上是否安裝了下列 IIS 範例檔案目錄： 

-   \\Inetpub\\iissamples 

-   \\Winnt\\help\\iishelp 

-   \\Program Files\\common files\\system\\msadc 

這些範例應用程式通常是隨同 IIS 說明動態 HTML (DHTML) 和 Active Server Pages (ASP) 指令檔一起安裝的，用來提供線上文件。 

#### Internet Explorer 安全性區域

這項檢查會列出掃描的電腦上每一位本機使用者對於 IE 區域的目前和建議安全性設定。 
**注意** 具有自訂設定的區域也許會比工具建議的設定更安全。工具雖然會報告每一個區域使用的自訂設定，但是它無法判斷這些設定是否比建議的設定更安全。 
**注意** 如果您看到「Error Reading Registry」(讀取登錄時發生錯誤) 的訊息，可能是您沒有啟用遠端登錄服務。 
Microsoft Internet Explorer Web 內容區域會將 Internet 或 Intranet 區分為具有不同安全性層級的區域。這項能力可以讓您依據網站的來源，對瀏覽器設定全域預設設定，允許信任網站上的所有內容，或不允許某些內容類型 (例如 Java Applet 或 ActiveX® 控制項)。 
Internet Explorer 瀏覽軟體有四個預先定義的 Web 內容區域：Internet、近端內部網路、信任的網站和限制的網站。在 \[Internet 選項\] 對話方塊中，您可以依據您對網站信任的程度，對每個區域設定您想要的安全性選項，然後從任何區域 (Internet 除外) 新增或移除網站。在公司的環境中，系統管理員可以為使用者設定區域。他們也可以新增或移除 (事先) 他們信任或不信任之軟體發行者的驗證憑證，讓使用者在使用Internet 時不需要再對安全性做決定。 
對於每一個安全性區域，您可以選擇高、中、低或自訂安全性設定。Microsoft 建議對不確定信任程度區域中的網站使用高設定值。自訂選項為進階使用者和系統管理員提供了更多對於所有安全性選項的控制，包括下列： 

-   存取檔案、ActiveX 控制項和指令檔 

-   賦予 Java Applet 的功能等級 

-   使用 Secure Socket Layer (SSL) 驗證指定網站身份 

-   使用 NTLM 驗證的密碼保護 (依據伺服器所在區域，Internet Explorer 可以自動傳送密碼資訊、提示使用者輸入使用者及密碼資訊，或是拒絕任何登入要求) 

#### 本機帳戶密碼 

這項檢查會找出使用空白或簡單密碼的任何本機使用者帳戶。這項檢查不會在網域控制站上執行。基於安全性理由，Windows XP、Windows 2000 和 Windows NT 作業系統全部都要求以密碼驗證使用者。不過，任何系統的安全性必須同時依賴技術與原則 – 也就是設定和管理系統的方式。這項檢查會列舉所有使用者帳戶並且檢查是否為下列密碼： 

-   密碼為空白 

-   密碼與使用者帳戶名稱相同 

-   密碼與電腦名稱相同 

-   密碼使用「password」這個單字 

-   密碼使用單字「admin」或「administrator」

這項檢查也會通知您目前有哪些帳戶已被停用，或目前已被鎖住。 

#### Sysadmin 角色的成員

這項檢查會判斷 Sysadmin 角色的成員數目，並且將結果顯示在安全性報告中。 
SQL Server 角色是用來將具有相同作業權限的登入群組在一起。Sysadmin 這個固定伺服器角色會將系統管理員權限授予它的所有成員。 
注意 如果您看到「No permissions to access database」(沒有存取資料庫的權限) 的錯誤訊息，您可能沒有 MASTER 資料庫的使用權限。

#### Office 巨集保護

這項檢查會逐一依據個別使用者判斷 Microsoft Office XP、Office 2000 和 Office 97 巨集保護的程度。PowerPoint、Word、Excel 和 Outlook 都是 MBSA 要檢查的項目。 
巨集會自動進行重複性的工作，它們是能夠節省時間的工具，但是也可以在使用者開啟含有惡意巨集的受感染文件時用來傳送病毒。開啟或共用受感染的文件可以讓惡意的巨集散佈到系統上的其他文件，或散佈到其他使用者。 

#### 作業系統版本 

這項檢查會判斷所掃描的電腦上執行的是哪一種作業系統。Windows XP 和 Windows 2000 會針對全部或您的商務運作引入新的可靠性與可用性等級，例如對於檔案使用權限的小範圍控制。 

#### Outlook 安全性區域

這項檢查會逐一依據個別使用者判斷 Microsoft Outlook 2002、Outlook 2000 和 Outlook 98 中下列區域的安全性層級： 

-   近端內部網路區域 

-   信任的網站區域 

-   限制的網站區域 

-   Internet 區域 

大部分電子郵件程式都允許使用者在電子郵件訊息內包含 HTML 內容 (例如網頁)。這樣雖然很方便，但是也有安全性的風險。Outlook 允許您設定安全性層級，讓您能夠保護系統不會遭受可能內嵌於網頁中的任何有害指令碼的侵害。 

#### 密碼到期 

這項檢查會判斷是否有任何本機使用者帳戶擁有永遠不會到期的密碼。密碼應該定期變更以緩和針對密碼的攻擊。每一個擁有永遠不會到期密碼的本機使用者帳戶都會列出來。 

#### 限制匿名使用者

這項檢查會判斷所掃描的電腦上是否使用了 RestrictAnonymous 登錄機碼來限制匿名連線。 
匿名使用者可以列出某些類型的系資訊，包括使用者名稱和詳細資料、帳戶原則及共用名稱。希望加強安全性的使用者可以限制這項功能，讓匿名使用者無法存取資訊。 

#### 限制 CmdExec 權限只授予 Sysadmin

這項檢查可確保 CmdExec 權限僅限於授予 Sysadmin。擁有 CmdExec 權限的所有其他帳戶都會列在安全性報告上。 
SQL Server 代理程式是 Windows XP、Windows 2000 和 Windows NT 上一項可以執行作業、監視 SQL Server 和傳送警示的服務。使用 SQL Server 代理程式，您可以使用指令碼編寫的工作步驟自動執行某些管理工作。作業 (Job) 是指由 SQL Server 代理程式依序執行的一系列特定作業。一項作業可以執行多種活動，包括執行 Transact-SQL 指令檔、命令列應用程式以及 Microsoft ActiveX 指令檔。您可以建立作業來執行時常要重複或排程的工作，而且它們會藉由警示自動通知使用者作業的狀態。 

#### Service Pack 和 Hotfix

Service Pack 是針對各種客戶報告的 Microsoft 產品問題，經過詳細測試的更新檔集合。它通常會修正一些產品上市後所發生的產品問題。Service Pack 是累積性的 - 每個新的 Service Pack 都會包含先前 Service Pack 中的所有修正檔，再加上新的修正檔。它們是設計用來確保平台與新發行軟體和驅動程式的相容性，並且含有修正客戶或內部測試所發現問題的更新檔。 
另一方面，Hotfix 則是一種過渡性的更新檔，通常用來改正某一項特定的錯誤或安全性弱點。在某個 Service Pack 有效期間內提供的所有 Hotfix 都會包含在後續的 Service Pack 裡。這個工具所識別的每個安全性 Hotfix，都有包含這個修正程式詳細資訊的相關 Microsoft 安全性公告。這項檢查的結果會找出缺少哪些 Hotfix，並且提供 Microsoft 網站的連結讓您檢視每一安全性公告的詳細內容。 

這個工具會透過檢查來確保您擁有下列產品和元件的最新 Service Pack 和安全性 Hotfix： 

-   Windows NT 4.0、Windows 2000、Windows XP  

-   IIS 4.0、IIS 5.0 

-   SQL 7、SQL 2000 

-   Internet Explorer 5.01+ 

 這項檢查是從 Microsoft.com 取得執行所需的資訊，它會在每次執行時從 Microsoft.com 下載這些資訊。如果它無法連線到 Microsoft.com，它就會使用本機電腦快取的資料庫版本。 

#### 共用

這項檢查會判斷所掃描的電腦上是否有任何共用的資料夾。掃描報告會列出電腦上的所有共用 (包括系統管理共用)，以及它們的共用層級和 NTFS 層級使用權限。 
您應該關閉共用 (除非確有必要)，或透過共用層級和 NTFS 層級使用權限將存取權限制給特定的使用者，藉此保護這些共用。 

#### SQL Server 本機帳戶密碼

這項檢查會判斷是否有任何本機 SQL Server 帳戶擁有簡單密碼 (例如空白密碼)。這項檢查會列舉所有使用者帳戶並且檢查是否為下列密碼： 

-   密碼為空白 

-   密碼與使用者帳戶名稱相同 

-   密碼與電腦名稱相同 

-   密碼使用「password」這個單字 

-   密碼使用「sa」這個單字 

-   密碼使用單字「admin」或「administrator」 

這項檢查也會通知您目前有哪些帳戶已被停用，或目前已被鎖住。 

#### SQL Server 驗證模式 

這項檢查會判斷所掃描的 SQL Server 上使用的驗證模式。 
Microsoft SQL Server 提供了兩種保護伺服器存取的模式：Windows 驗證模式和混合模式。 
在 Windows 驗證模式中，Microsoft SQL Server 完全依賴 Windows 的使用者驗證。然後准許 Windows 使用者或群組存取 SQL Server。在混合模式中，使用者可能會由 Windows 或 SQL Server 驗證。由 SQL Server 驗證的使用者，其使用者名稱與密碼配對是在 SQL Server 內維護。Microsoft 強烈建議一定要使用 Windows 驗證模式。 

**Windows 驗證模式 **

這個安全性模式可以讓 SQL Server 和其他應用程式一樣依賴 Windows 來驗證使用者。用這種模式對伺服器所做的的連線稱為信任的連線。 
使用 Windows 驗證模式時，資料庫管理員可以授予使用者登入 SQL Server 的權限，讓他們存取執行 SQL Server 的電腦。Windows 安全識別碼 (SID) 是用來追蹤 Windows 驗證的使用者。由於已經使用了 Windows SID，資料庫管理員就可以將存取權直接授予 Windows 使用者或群組。 
**混合模式 **

在 SQL Server 中，當用戶端和伺服器能夠使用 NTLM 或 Kerberos 登入驗證通訊協定時，混合模式是依賴 Windows 來驗證使用者。如果任何一方能夠使用標準 Windows 登入，SQL Server 會要求使用者名稱和密碼配對，並且將這個配對與它系統資料表中儲存的配對進行比較。依賴使用者名稱與密碼配對的連線稱為不信任連線。 
提供混合模式是基於兩個理由：1) 與舊版 SQL Server 之間的回溯相容性，和 2) 當 SQL Server 安裝於 Windows 95 和 Windows 98 作業系統上的相容性 (Windows 95 或 Windows 98 –系統電腦做為伺服器時不支援信任連線)。 

#### Sysadmin 角色中 SQL Server BUILTIN\\Administrators

這項檢查會判斷內建的系統管理員群組是否被列為 Sysadmin 角色中的成員。 
**注意** 如果您看到「No permissions to access database」(沒有存取資料庫的權限) 的錯誤訊息，您可能沒有 MASTER 資料庫的使用權限。 
SQL Server 角色是其他安全性帳戶集合的安全性帳戶。當您管理使用權限時，可以將它視為單一的單位。角色可以包含 SQL Server 登入使用權限、其他角色以及 Windows 使用者帳戶或群組。 
固定伺服器角色擁有全伺服器的範圍。它們存在於資料庫之外。固定伺服器角色的每一個成員都能新增其他登入到這個角色。根據預設，**Windows BUILTIN\\Administrators** 群組 (本機系統管理員群組) 的所有成員都是 **sysadmin** 角色的成員，也會授予他們所有資料庫的完整權限。 

#### SQL Server 目錄存取 

這項檢查會驗證下列 SQL Server 目錄是否僅限 SQL 服務帳戶和本機系統管理員存取： 

-   Program Files\\Microsoft SQL Server\\MSSQL$InstanceName\\Binn 

-   Program Files\\Microsoft SQL Server\\MSSQL$InstanceName\\Data 

-   Program Files\\Microsoft SQL Server\\MSSQL\\Binn 

-   Program Files\\Microsoft SQL Server\\MSSQL\\Data 

這個工具會掃描上述每個資料夾的存取控制清單 (ACL) 並且列舉 ACL 中包含的使用者。如果任何其他使用者 (SQL 服務帳戶和系統管理員以外的使用者) 擁有讀取或修改這些資料夾的存取權，工具就會在安全性報告中將這項檢查標示為弱點。 

#### SQL Server 顯露 sa 帳戶密碼

這項檢查會判斷 SQL Server 7.0 和 SQL Server 2000 sa 帳戶密碼是否是以純文字方式寫入 %temp%\\sqlstp.log and %temp%\\setup.iss 檔案中。 
如果您是使用 SQL Server 驗證 (也稱為標準安全性) 安裝 SQL Server 7.0 Service Pack，系統管理員 (sa) 密碼會以純文字格式儲存在 %winnt% 目錄中的 Setup.iss 檔案以及 Temp 目錄中的 Sqlstp.log 檔案中。 
注意 Microsoft 建議您使用 Windows NT 安全性驗證來安裝 SQL Server 7.0 Service Pack 以避免這種問題。如果要順利進行這項檢查，您必須將磁碟機共用。 

#### SQL Server Guest 帳戶

這項檢查會判斷 SQL Server Guest 帳戶是否擁有資料庫 (master、tempdb 和 msdb 除外) 存取權。這個帳戶可以存取的所有資料庫都會列在安全性報告中。 
注意 如果您看到「No permissions to access database」(沒有存取資料庫的權限) 的錯誤訊息，您可能沒有 MASTER 資料庫的使用權限。 
在 SQL Server 中，使用者登入帳戶必須以下列中一種方式授予資料庫及其物件的存取權： 

-   登入帳戶可以指定成資料庫使用者。 

-   登入帳戶可以使用資料庫中的 Guest 帳戶。

-   Windows 群組登入可以對應為資料庫角色。做為這個群組成員的個別 Windows 帳戶就可以連線到資料庫。  

db\_owner 或 db\_accessadmin 資料庫角色的成員或 Sysadmin 固定伺服器角色，可以建立資料庫使用者帳戶角色。帳戶可以包含一些參數：SQL Server 登入 ID、資料庫使用者名稱 (選擇性)，以及最多一個角色名稱 (選擇性)。資料庫使用者名稱不一定要和使用者登入 ID 相同。如果沒有提供資料庫使用者名稱，使用者的登入 ID 和資料庫使用者名稱將是相同的。建立資料庫使用者之後，就可以視需要將使用者指定為許多角色。如果沒有提供角色名稱，這個資料庫使用者只是 Public 角色的成員。 
db\_owner, db\_accessadmin 的成員或 sysadmin 角色也可以建立 Guest 帳戶。Guest 帳戶可以讓任何有效的 SQL Server 登入帳戶存取資料庫，即使它們沒有資料庫使用者帳戶也可以。根據預設，Guest 帳戶會繼承指派給 Public 角色的任何權限；但是，這些權限可以變更成比 Public 角色更高或更低的權限。 

#### 網域控制站上的 SQL Server 

這項檢查會判斷 SQL Server 是否在做為網域控制站的系統上執行。建議您不要在網域控制站上執行 SQL Server。網域控制站含有敏感的資料 (例如使用者帳戶資訊)，所以不應該在其他角色中使用。如果在網域控制站上執行 SQL Server 資料庫，將會增加保護伺服器和防止攻擊所涉及的複雜性。 

#### SQL Server 登錄機碼安全性 

這項檢查會確保 Everyone 群組對於下列登錄機碼限制為讀取權限： 
**HKLM\\Software\\Microsoft\\Microsoft SQL Server
HKLM\\Software\\Microsoft\\MSSQLServer **
如果 **Everyone** 群組對這些機碼擁有超過讀取的權限，就會在安全性報告中將它標示為重大弱點。 

#### SQL Server 服務帳戶 

這項檢查會判斷所掃描的電腦上 SQL Server 服務帳戶是否為本機或網域系統管理員群組的成員，是否有任何 SQL Server 服務帳戶是在 LocalSystem 內容下執行。 
所掃描電腦上的 MSSQLServer 和 SQLServerAgent 服務帳戶都會被檢查。 
**注意** 如果您看到「No permissions to access database」(沒有存取資料庫的權限) 的錯誤訊息，您可能沒有 MASTER 資料庫的使用權限。 

[](#mainsection)[回到頁首](#mainsection)

### 其他資源

#### Microsoft 安全性策略和方案

-   Microsoft Security 網站： <http://www.microsoft.com/taiwan/security/>

-   Microsoft Strategic Technology Protection Program
     [http://www.microsoft.com/security/mstpp.asp ](http://www.microsoft.com/security/mstpp.asp)

-   Best Practices for Enterprise Security <http://www.microsoft.com/technet/archive/security/bestprac/bpent/bpentsec.mspx> 

-   Microsoft Security Response Center Security Bulletin Severity Rating System <http://www.microsoft.com/technet/security/bulletin/rating.mspx> 

-   「CSI/FBI Computer Crimes and Security Survey 2001」Computer Security Institute 
    <http://www.gocsi.com/> 

-   Microsoft Internet Security and Acceleration (ISA) Server information
    [http://www.microsoft.com/taiwan/ISAServer/](http://www.microsoft.com/taiwan/isaserver/)[ ](http://www.microsoft.com/technet/columns/security/essays/noarch.asp)

-   The 10 Immutable Laws of Security
    [http://www.microsoft.com/technet/archive/community/columns/security/
    essays/10imlaws.mspx](http://www.microsoft.com/technet/archive/community/columns/security/essays/10imlaws.mspx)

-   The 10 Immutable Laws of Security Administration
    [http://www.microsoft.com/technet/archive/community/columns/security/
    essays/10imlaws.mspx](http://www.microsoft.com/technet/archive/community/columns/security/essays/10imlaws.mspx) 

#### 尋找可以協助 Microsoft 安全性方案的夥伴

-   Microsoft Certified Providers Directory
    [http://mcspreferral.microsoft.com/ ](http://mcspreferral.microsoft.com/)

-   Microsoft Consulting Services
    [http://www.microsoft.com/BUSINESS/services/mcs.asp ](http://www.microsoft.com/business/services/mcs.asp)

© 2002 Microsoft® Corporation.All rights reserved. 
本文件中所包含的資訊，代表 Microsoft Corporation 於發行日前針對該事件的觀點。由於 Microsoft 必須反應市場條件的變更，因此不應解釋為 Microsoft 的承諾。在發行日之後，Microsoft 不保證文件中任何資訊的正確性。 
此白皮書僅供參考使用。MICROSOFT 對於本文件中各項資訊，不作任何明示或默示的保證。 
使用者必須依從所有適用的版權相關法律規則。在未取得 Microsoft Corporation 書面許可的情況下，不得任意複製本文件、將文件存放於擷取系統中，或者透過任何方式或手段傳輸本文件 (電子、機械、影印、記錄等等)。 
本文件中可能述及 Microsoft 的專利、專利應用程式、商標、版權或其他智慧財產權。除非取得 Microsoft 明確書面授權聲明，否則本文件並未授與這些專利、商標、版權或其他智慧財產的授權。 
Microsoft、ActiveX、Windows、Windows 標誌和 Windows NT 都是 Microsoft Corporation 在美國和 (或) 其他國家的註冊商標或商標。 
本書所提的真實公司和產品名稱，可能係其專屬公司的商標。 
1 MBSA 每次執行時會嘗試連線到 Internet，以便從 Microsoft 下載 CAB/XML 檔案。如果沒有 Internet 連線，它會在這個工具的安裝資料夾中尋找 CAB/XML 檔案的本機複本。每次掃描時如果成功地下載了這個檔案，就會將本機複本儲存在電腦上，以備後續掃描無法連線到 Internet 時使用。對於永遠不連線到 Internet 的電腦，使用者可以從 Microsoft 下載中心網站單獨下載這個檔案，然後將它複製到執行這個工具的電腦上。 
2 .CAB 檔案是由 Microsoft Corporation 數位簽署的。MBSA 工具會驗證數位簽名來確保檔案的真實性，以及它有沒有被偽造的或毀損的檔案所取代。只有 Microsoft 安全性應變中心 (Microsoft Security Response Center) 裡的少數成員能數位簽署這個檔案。 
3 指定網域或 IP 位址的範圍時，MBSA 會嘗試並且 Ping 這個群組中的所有電腦。這個工具會列出哪些電腦沒有辦法 Ping 到，並且繼續對已回應的電腦進行掃描。 

[](#mainsection)[回到頁首](#mainsection)
