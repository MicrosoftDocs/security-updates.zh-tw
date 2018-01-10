---
TOCTitle: 介紹 Windows XP 安全性指南
Title: 介紹 Windows XP 安全性指南
ms:assetid: '01ef3338-2f29-4b6e-b80f-d40728dc964d'
ms:contentKeyID: 20214409
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Dd548227(v=TechNet.10)'
---

介紹 Windows XP 安全性指南
==========================

### Overview

發佈日期: 2003 年 12 月 31 日 | 更新日期: 2006 年 4 月 26 日

##### 本頁內容

[](#eoaa)[本單元內容](#eoaa)
[](#enaa)[目標](#enaa)
[](#emaa)[適用於](#emaa)
[](#elaa)[如何使用本單元](#elaa)
[](#ekaa)[執行摘要](#ekaa)
[](#ejaa)[誰應該閱讀本指南](#ejaa)
[](#eiaa)[獲得安全、保持安全](#eiaa)
[](#ehaa)[本指南的遠景](#ehaa)
[](#egaa)[單元概觀](#egaa)
[](#efaa)[下載內容](#efaa)
[](#eeaa)[技能與整備](#eeaa)
[](#edaa)[需求](#edaa)
[](#ecaa)[樣式慣例](#ecaa)
[](#ebaa)[總結](#ebaa)
[](#eaaa)[其他資訊](#eaaa)

### 本單元內容

歡迎使用《Windows XP 安全性指南》。本指南為您提供您最佳資訊，幫助您評估並應付您環境中 Microsoft® Windows® XP Professional 作業系統加上 Service Pack (SP) 1 特定的安全性風險。本指南中的各單元提供關於隨地設定 Windows XP 中增強型安全性設定和功能，以解決環境中發現的威脅之詳細資訊。如果您是 Windows XP 環境相關的顧問、設計師或系統工程師，本指南正是專為您設計的。

相關指引已經過 Microsoft 工程小組、顧問、技術支援工程師的評閱和核准，並透過客戶和合作夥伴，因此內容：

-   經過證明 - 以實地經驗為基礎

-   有權威 - 提供最棒的建議

-   正確 - 通過技術驗證和測試

-   行動化 - 提供邁向成功的步驟

-   相關聯 - 提供真實世界的安全性考量

與在各種環境下實作 Windows XP Professional、Microsoft Windows Server™ 2003 作業系統 和 Windows 2000 的顧問及系統工程師合作，建立了最新的最佳作法來保障本指南將詳細介紹的用戶端和伺服器。

[](#mainsection)[回到頁首](#mainsection)

### 目標

透過此單元即可：

-   了解本指南中的原始構想，以及誰應該閱讀。

-   簡短說明每一單元的內容。

-   找出並下載補充材料，例如範本、指令碼和其他工具等。

-   指出實作本指南中的建議所需之硬體。

[](#mainsection)[回到頁首](#mainsection)

### 適用於

本單元適用於下列產品及技術：

-   Microsoft Windows XP Professional 加 SP1

[](#mainsection)[回到頁首](#mainsection)

### 如何使用本單元

本指南涵蓋安全性的逐步指示、程序和建議，提供工作清單，幫助您將組織內執行 Windows XP Professional 電腦的按 全性變換到更高層的狀態。如果您希望更深入探討此資料背後的概念，請參考下列資源：《威脅與因應對策：Windows Server 2003 及 Windows XP 中的安全性設定》、*Microsoft Windows XP Resource Kit、Microsoft Windows Server 2003 Resource Kit、Microsoft Windows Security Resource Kit*，以及 Microsoft TechNet。

若要充分瞭解此單元：

-   請參閱《Windows Server 2003 安全性指南》的＜在 Windows Server 2003 環境中設定網域基礎結構＞單元。這將讓您對本單元中 Microsoft Active Directory® 內容的安全性建議有更廣泛的了解。

[](#mainsection)[回到頁首](#mainsection)

### 執行摘要

無論您的環境為何，都強烈建議您不可輕忽安全性議題。許多組織之所以沒有真正了解資訊技術 (IT) 環境的重要性，主要是因為未考慮到實際的間接成本。一旦您環境中的伺服器遭到嚴重攻擊，整個組織都可能受害。倘若您公司網站遭到攻擊，造成網站癱瘓，導致收益或客戶信心明顯流失，就有可能會造成企業利益的崩垮。因此在評估安全性成本時，應該將與任何攻擊相關的間接成本，以及失去 IT 功能的成本一併納入考慮。

而與安全性有關的弱點、風險和曝光度分析，能夠告訴您網路環境中所有電腦系統在安全性和可用性之間所必須作的取捨。本指南記載了 Windows XP 具備的重要安全性因應對策、所處理的漏洞，以及實作每一因應對策潛在的負面後果 (如果有的話)。

本指南接著會提供在三種常見的環境中強化這些系統的特定建議：一個是只包括 Windows XP 的企業環境；一個是相當重視安全性問題，因而可以接受功能和管理方面巨大損失的環境；而另一個是只包括 Windows XP Professional 的獨立環境。這些環境在整本指南中分別稱為：企業用戶端、高安全性和獨立。所定義的設定將可用於 Windows 2000、Windows Server 2003 及獨立環境，而且仍保有一定程度的功能可允許一般應用程式正常運作。

本指南經過特別編排方便存取，方便您能迅速找出所需資訊，判斷哪種設定較適合您組織內執行 Windows XP 的電腦。本指南的主要目標群是雖然針對企業客戶，但大部份內容仍適用於任何規模的組織。

為了充分利用此資料，建議閱讀整本指南。製作本指南的團隊小組希望您會覺得當中的資料有所幫助、富教育性外，還很有趣。如需進一步的資訊，您也可以參考同系列的指南《威脅與因應對策：Windows Server 2003 及 Windows XP 中的安全性設定》，可在此處下載：http://go.microsoft.com/fwlink/?LinkId=15159

[](#mainsection)[回到頁首](#mainsection)

### 誰應該閱讀本指南

本指南主要是針對在企業環境中，負責替 Windows XP 工作站規劃應用程式或基礎結構進行開發和部署工作的顧問、安全性專家、系統架構設計師和 IT 專業人員。本指南並不適用家庭使用者。本指南針對工作職責如下的個人而設計：

-   在組織中負責推動工作站架構工作的系統架構設計師和規劃師。

-   專門在跨組織的各平台提供安全性的 IT 安全性專家。

-   需要靠 IT 桌上型或膝上型電腦支援關鍵商業目標和需求的商業分析家和商業決策者 (BDM)。

-   需要有企業客戶和合作夥伴知識轉移工具的 Microsoft 服務和合作夥伴顧問。

[](#mainsection)[回到頁首](#mainsection)

### 獲得安全、保持安全

Microsoft 在 2001 年推出了一個名為「策略性技術保護計畫 (Strategic Technology Protection Program，STPP)」的行動。此計畫的目標在於整合首重安全性的 Microsoft 產品、服務和支援。Microsoft 將維護安全環境的程序分成兩個相關的階段：獲得安全，然後保持安全。

#### 獲得安全

第一個階段叫做「獲得安全」。若要協助您的組織達成適當層級的安全性，請遵循 Microsoft 在本指南和其他安全性指南中所提供的「獲得安全」建議。如需其他資源的連結，請參閱本單元中稍後的＜其他資訊＞一節。

#### 保持安全

第二個階段叫做「保持安全」。建立一個最初就具備安全能力的環境是一回事。然而，一旦環境開始執行運作，要歷時維護環境的安全性、針對威脅採取預防行動，並在威脅發生的時候有效的回應完全又是另外一回事。若要協助您的組織達成適當層級的安全性，請遵循 Microsoft Security Tool Kit (可從線上存取) 中所提供的「保持安全」建議。有關 Microsoft Security Tool Kit 的詳細資訊，請參閱本單元中稍後的＜其他資訊＞一節。

[](#mainsection)[回到頁首](#mainsection)

### 本指南的遠景

本指南把重點放在如何針對執行 Windows XP Professional 的桌上型和膝上型電腦，來建立和維護安全的環境，而不是針對家庭使用者而設計。本指南將闡釋如何保障環境安全的各個不同階段，以及每一設定對桌上型和膝上型電腦解決了什麼樣的問題。內容涵蓋企業、高安全性和獨立環境。

#### 企業

企業環境是由一個 Windows 2000 或 Windows Server 2003 Active Directory 目錄服務網域所組成。在此環境中的用戶端將採用套用至容器、站台、網域和組織單位 (OU) 的「群組原則」進行管理。「群組原則」提供一套集中化的方法來管理跨環境的安全性原則。

#### 高安全性

高安全性環境包括用戶端的高安全性設定。當套用高安全性設定時，使用者的能力會侷限為只能進行必要工作所需的特定功能。存取權僅限於認可的應用程式、服務和基礎結構環境。

#### 獨立環境

獨立環境是由擁有一些不能加入網域的電腦或者其電腦屬於 Microsoft Windows NT® 4.0 網域成員的該些組織所組成。這些用戶端都必須使用「本機原則」設定加以設定。獨立電腦的管理工作比使用 Active Directory 的網域來管理使用者帳戶及原則所具備的挑戰性還高很多。

[](#mainsection)[回到頁首](#mainsection)

### 單元概觀

Windows XP 以最佳的安全性和隱私功能，提供了有史以來最可靠的 Windows 版本。Windows XP 中整體的安全性已經過改善，來幫助確保您的組織能夠在安全且可靠的電腦環境中運作。《Windows XP 安全性指南》包括七個單元。這些單元探討的是建立這類環境所牽涉的程序。每一單元都是以端對端程序為基礎建構而成，以保障您環境內執行 Windows XP 的電腦的安全。

#### 介紹 Windows XP 安全性

本單元涵蓋指南的概觀，其中包括目標群的描述、在指南內探討的問題，以及本指南的整體目標。

#### 設定 Active Directory 網域基礎結構

群組原則可用來管理 Windows Server 2003 及 Windows 2000 網域內的使用者和電腦環境。本單元探討將群組原則套用至 Windows XP 用戶端之前，必須在您的網域內進行的預備步驟。

群組原則設定乃存在網域控制站上的「群組原則物件 (GPO)」中。GPO 與 Active Directory 結構當中的容器、站台、網域和組織單位 (OU) 相連結。由於群組原則與 Active Directory 如此緊密地整合，因此在實作群組原則之前，先對 Active Directory 結構和安全性含意有基本的了解是很重要的。群組原則是保衛 Windows XP 不可或缺的工具，而且可用在從中央位置跨網路套用及維護一致的安全性原則。

#### Windows XP 用戶端的安全性設定

本單元涵蓋可在 Windows 2000 或 Windows Server 2003 Active Directory 網域，經由「群組原則」設定的 Windows 用戶端安全性設定。並未針對所有可用的設定提供指引 - 僅針對該些套用建議組態將可保障環境防範最近的威脅，並同時能讓使用者在他們的電腦上進行正常工作的設定提供指引。進行的設定應該以您的組織安全性目標為主。

#### Windows XP 的系統管理範本

在本單元中，將討論到可使用「系統管理範本」加入 Windows XP 的設定。「系統管理範本」乃是 Unicode 檔，可用來設定掌控許多服務、應用程式和操作系統元件之行為的登錄設定。Windows XP 附隨五種「系統管理範本」，其中包含超過 600 種設定。

#### 保障獨立 Windows XP 用戶端的安全

本單元將探討獨立 Windows XP 用戶端的設定。雖然建議將 Windows XP 部署在 Active Directory 網域基礎結構中，但這不一定永遠可行。本單元提供將建議設定套用至不屬於 Windows 2000 或 Windows Server 2003 網域成員的 Windows XP 用戶端的相關指引。

#### Windows XP 用戶端的軟體限制原則

本單元提供了軟體限制原則的基本概觀。軟體限制原則提供系統管理員一個原則導向的機制，用以識別和限制可在其網域中執行的軟體。系統管理員可利用軟體限制原則阻止不想要的程式，以及病毒、特洛伊木馬程式，或其他惡意程式碼等的執行。軟體限制原則完全與 Active Directory 和群組原則整合。軟體限制原則可用在沒有 Windows Server 2003 網域基礎結構的環境中，只套用到本機電腦。

[](#mainsection)[回到頁首](#mainsection)

### 下載內容

本指南中包含了一組安全性範本、指令碼和額外的工具，方便您的組織評估、測試和實作在本指南中建議的因應對策。安全性範本是可匯入網域架構的群組原則，或使用「安全性設定及分析」嵌入式管理單元從本機套用的文字檔。這些程序都詳述在《Windows Server 2003 安全性指南》的＜在 Windows Server 2003 環境中設定網域基礎結構＞單元。

包含在本指南中的指令碼可用來將這些建議實作在獨立工作站上。另一個叫做「Windows XP 安全性指南設定」的 Microsoft Excel 活頁簿，則記載了包含在每一安全性範本中的設定 (詳見 [http://go.microsoft.com/fwlink/?LinkId=14840](http://go.microsoft.com/fwlink/?linkid=14840))。這些工具和範本都包含在內含本指南的自解壓縮 WinZip 保存檔中。當您從此保存檔解壓縮檔案時，會在您指定的位置建立下列資料夾結構：

-   Windows XP Security Guide - 包含您目前正在閱讀的 Portable Document Format (PDF) 檔，以及與此資料相關的「測試指南」、「遞送指南」和「支援指南」。

-   Windows XP Security Guide\\Tools and Templates - 包含任何本指南隨附的項目子目錄。

-   Windows XP Security Guide\\Tools and Templates\\Security Guide\\Security Templates - 包含在本指南＜設定 Active Directory 網域基礎結構＞和＜Windows XP 用戶端的安全性設定＞單元所討論到的所有安全性範本。

-   Windows XP Security Guide\\Tools and Templates\\Security Guide\\Administrative Templates - 包含在本指南＜Windows XP 的系統管理範本＞單元中所討論到的所有系統管理範本。

-   Windows XP Security Guide\\Tools and Templates\\Security Guide\\Checklists \_- 包含實作本指南中所建議之設定的檢查清單。

-   Windows XP Security Guide\\Tools and Templates\\Security Guide\\Stand Alone Clients - 包含用於實作本指南＜保障獨立 Windows XP 用戶端的安全＞單元討論到的加強型獨立電腦的所有範例指令碼和範本。

-   Windows XP Security Guide\\Tools and Templates\\Test Guide - 包含與測試指南相關的工具。

-   Windows XP Security Guide\\Tools and Templates\\Test Guide - 包含與遞送指南相關的工具。

[](#mainsection)[回到頁首](#mainsection)

### 技能與整備

下列的知識和技能是在企業中負責開發、部署和保護 Windows XP 用戶端安全性的系統管理員或架構設計師其必備的條件。

-   Microsoft 認證系統工程師 (MCSE) 2000 認證以及兩年以上或相當的安全性相關經驗。

-   對公司網域及 Active Directory 環境的深入了解。

-   精通管理工具；包括 Microsoft Management Console (MMC)、secedit、gpupdate 和 gpresult。

-   群組原則相關管理經驗。

-   在企業環境內部署應用程式和用戶端相關經驗。

[](#mainsection)[回到頁首](#mainsection)

### 需求

《Windows XP 安全性指南》的硬體需求為：

-   配備 300 MHz 或更快的處理器時脈；至少需要 233 MHz (單一或雙處理器系統)；Intel Pentium/Celeron 系列，或 AMD K6/Athlon/Duron 系列，或相容處理器的個人電腦。

-   至少 128 MB 或以上的 RAM (最少支援 64 MB，可能會限制效能和部份功能)。

-   作業系統最少有 1.5 GB 的可用硬碟空間。

-   Super VGA (800 × 600) 或更高解析度的顯示卡和顯示器。

-   用戶端上有光碟機或 DVD 磁碟機。

-   鍵盤和 Microsoft 滑鼠或相容的指標裝置。

[](#mainsection)[回到頁首](#mainsection)

### 樣式慣例

本指南採用下列樣式慣例和術語。

**\[表 1\]：樣式慣例**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >元素</th>
<th style="border:1px solid black;" >含意</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>粗體字型</strong></td>
<td style="border:1px solid black;">正如此所示鍵入的字元，包括命令和參數。使用者介面的指示型文字項目也以粗體表示。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>斜體字型</em></td>
<td style="border:1px solid black;">提供有特定值的變數預留位置。例如，Filename.ext 可指第一個討論案例的任何有效檔案名稱。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>重要事項</strong></td>
<td style="border:1px solid black;">警告讀者完成工作不可或缺的補充資訊。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">等寬字型</td>
<td style="border:1px solid black;">程式碼範例。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemRoot%</td>
<td style="border:1px solid black;">安裝 Windows 作業系統的資料夾。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>注意</strong></td>
<td style="border:1px solid black;">警告讀者的補充資訊。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Screen Para</td>
<td style="border:1px solid black;">出現在螢幕上的訊息及命令列命令都是使用這種字型。</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[回到頁首](#mainsection)
  
### 總結
  
本單元已向您介紹《Windows XP 安全性指南》，並概述了當中的各個單元。現在您既已了解整本指南的編排方式，當準備好充分利用 Windows XP 內建的重要安全性選項。有效、成功地安全性操作需要在本指南所涵蓋的所有領域投下心力，而不是只有單一方面的改進。有鑑於此，強烈建議您實作本指南中建議的所有程序。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 其他資訊
  
下列資訊來源是本指南公開發行當時，與保障 Windows XP Professional 安全性相關的最新主題。
  
如需有關可在 Microsoft Windows XP 上設定的安全性設定詳細資訊，請參閱同系列指南《Threats and Countermeasures Guide (英文)》：[http://go.microsoft.com/fwlink/?LinkId=15159](http://go.microsoft.com/fwlink/?linkid=15159)。
  
有關 Microsoft Operations Framework (MOF) 如何能夠在您的企業中協助您的詳細資訊，請參閱：<http://www.microsoft.com/business/services/mcsmof.asp>。
  
有關 Microsoft Strategic Technology Protection Program 的資訊，請參閱：<http://microsoft.com/security/mstpp.asp>。
  
有關 Microsoft Security Notification Service 的資訊，請參閱：<http://www.microsoft.com/technet/treeview/default.asp?url=/technet/security/bulletin/notify.asp>。
  
有關資料復原和保護的詳細資訊，請參閱：<http://www.microsoft.com/windowsxp/pro/techinfo/administration/recovery/default.asp>。
  
[](#mainsection)[回到頁首](#mainsection)
