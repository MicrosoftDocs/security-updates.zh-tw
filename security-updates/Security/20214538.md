---
TOCTitle: Windows XP 安全性指南概觀
Title: Windows XP 安全性指南概觀
ms:assetid: 'fb31fa9b-58c8-4b6c-aa93-f49128e79916'
ms:contentKeyID: 20214538
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc163061(v=TechNet.10)'
---

Windows XP 安全性指南
=====================

### 概觀

發佈日期: 2003 年 5 月 22 日 | 更新日期: 2006 年 7 月 26 日

任何 IT 環境的安全程度通常是最薄弱的一環。不幸的是，安全性專案經常會忽略掉用戶端作業系統。當您的組織在計畫實作 Microsoft® Windows® XP Professional Service Pack 2 (SP2) 時，請務必將用戶端作業系統的安全性納入部署計畫。

雖然 Windows XP 的預設安裝是相當安全的，但是您必須記住，您環境裡的用戶端在安全性、實用性與功能性上所具有的折衷關係。如能徹底理解這些折衷關係，則可讓您的組織在部署 Windows XP 時，將其安全性發揮到最大。

本指南提供有關在三種不同的環境中強化 Windows XP SP2 電腦的特別建議：

-   **企業用戶端 (EC)：** 此環境中的用戶端電腦是位於 Active Directory® 目錄服務網域中，並且只需要與執行 Windows 2000 或更新版本的 Windows 作業系統通訊。

-   **獨立 (SA) 用戶端：** 此環境中的用戶端電腦並非 Active Directory 網域的成員，可能需要與執行 Windows NT® 4.0 的系統通訊。

-   **專業安全性限制功能 (SSLF)：** 由於在此環境中安全性問題相當重要，因此大幅減少功能和降低可管理性是可以接受。例如，軍事和情報單位的電腦就是在這種環境中運作。

##### 本頁內容

[](#eeaa)[誰應該閱讀本指南](#eeaa)
[](#edaa)[內容規劃](#edaa)
[](#ecaa)[相關資源](#ecaa)
[](#ebaa)[歡迎您提供意見](#ebaa)
[](#eaaa)[顧問與支援服務](#eaaa)

### 誰應該閱讀本指南

本指南主要是針對在企業環境中，負責替 Windows XP 工作站規劃應用程式或基礎結構進行開發和部署工作的顧問、安全性專家、系統架構設計師和 IT 專業人員。本指南並不適用於家庭使用者。

安全性專家和 IT 架構設計師可能需要本指南中討論到的安全性設定的詳細資訊。這些資訊可以在同系列指南[威脅與因應對策：Windows Server 2003 和 Windows XP 中的安全性設定](http://go.microsoft.com/fwlink/?linkid=15159)中找到，網址為 http://go.microsoft.com/fwlink/?LinkId=15159。

[](#mainsection)[回到頁首](#mainsection)

### 內容規劃

Windows XP 提供目前最可靠的 Windows 用戶端作業系統版本，並具備改良的安全性和隱私權功能。Windows XP 的整體安全性已經過改善，以幫助確保您的組織能夠在更為安全可靠的運算環境中運作。《Windows XP 安全性指南》共有七個章節，第二章至第六章討論建立此種環境所需的程序。其中每一章中所討論的內容，都是以保護 Windows XP 電腦之安全為設計宗旨的端點對端點程序。

[![](images/Cc163061.default1(zh-tw,TechNet.10).gif)](https://technet.microsoft.com/zh-tw/cc163061.default1_big(zh-tw,technet.10).gif)

**圖 1 《Windows XP 安全性指南》的章節要點**

#### 第 1 章：Windows XP 安全性指南簡介

本章涵蓋本指南的概觀、目標讀者的描述、本指南內討論的問題，以及本指南的整體目標。

#### 第 2 章：設定 Active Directory 網域基礎結構

「群組原則」可用來管理 Windows Server 2003 及 Windows 2000 網域內的使用者和電腦環境。它是保護 Windows XP 不可或缺的工具，而且可用在從中央位置跨網路套用及維護一致的安全性原則。本章討論將「群組原則」套用至 Windows XP 用戶端電腦之前，必須在您的網域內進行的預備步驟。

群組原則設定乃存在網域控制站上的「群組原則物件」(GPO) 中。GPO 與 Active Directory 結構中的站台、網域和 OU 相連結。由於「群組原則」與 Active Directory 如此緊密地整合，因此在實作「群組原則」之前，先對 Active Directory 結構和安全性含意有基本的瞭解是很重要的。

#### 第 3 章：Windows XP 用戶端的安全性設定

本章說明可在 Windows 2000 或 Windows Server 2003 Active Directory 網域中，透過「群組原則」進行設定的 Windows XP 用戶端電腦安全性設定。本指南並未提供所有可用的設定，僅提供可保護環境免於最新威脅之設定。本指南也可讓使用者在他們的電腦上繼續執行日常工作。您的設定應該以組織的安全性目標為依據。

#### 第 4 章：Windows XP 的系統管理範本

在本章節中，將討論到可使用「系統管理範本」加入 Windows XP 的設定。「系統管理範本」乃是 Unicode 檔，可用來設定掌管多項服務、應用程式和作業系統元件之行為的登錄設定。有許多可用於 Windows XP 的系統管理範本，這些範本包含數百種設定。

#### 第 5 章：保護獨立 Windows XP 用戶端的安全

雖然本指南大部分著重於企業用戶端 (EC) 及專業安全性限制功能 (SSLF) 環境，但本章亦討論獨立 Windows XP 用戶端電腦的設定。Microsoft 建議在 Active Directory 網域基礎結構中部署 Windows XP，但 Microsoft 瞭解不是每個組織都能這麼做。本章將教導您如何將建議的設定套用到不是 Windows 2000 或 Windows Server 2003 網域成員的 Windows XP SP2 用戶端電腦上。

#### 第 6 章：Windows XP 用戶端的軟體限制原則

本章提供軟體限制原則的基本概觀，軟體限制原則提供系統管理員一個以原則為導向的機制，用以識別和限制可在其網域中執行的軟體。系統管理員可以使用軟體限制原則來阻止不想要的程式的執行，以及阻止病毒、特洛伊木馬程式或其他惡意程式碼的擴散。軟體限制原則和 Active Directory 及「群組原則」完全整合為一。當只套用於本機電腦上時，亦可在沒有 Windows Server 2003 網域基礎結構的環境中使用。

#### 第 7 章：結論

最後一章將對前幾章中討論的所有內容進行簡要的概述，以重申本指南的重點。

#### 附錄 A：應考量的金鑰設定

雖然本指南討論多種安全性因應措施和安全性設定，但您應該瞭解的是其中有幾點是特別重要的。本附錄討論會對執行 Windows XP SP2 的電腦安全性產生重大影響的設定。

#### 附錄 B：測試 Windows XP 安全性指南

本附錄說明《Windows XP 安全性指南》如何在實驗室環境中通過測試，以確保本指南符合預期。

[](#mainsection)[回到頁首](#mainsection)

### 相關資源

如需關於本章所述之安全性設定的進一步資訊，請下載同系列指南[威脅與因應對策：Windows Server 2003 和 Windows XP 中的安全性設定](http://go.microsoft.com/fwlink/?linkid=15159)，網址為 http://go.microsoft.com/fwlink/?LinkId=15159。

閱讀由 Microsoft Solutions for Security and Compliance 小組所提供的[其他安全性解決方案](http://www.microsoft.com/technet/community/columns/sectip/st0805.mspx) (英文)。

[](#mainsection)[回到頁首](#mainsection)

### 歡迎您提供意見

Microsoft Solutions for Security and Compliance (MSSC) 小組歡迎您對本指南及其他安全性解決方案提出意見。

您有任何意見嗎？ 請透過 [IT 專業人員安全性解決方案網誌](http://blogs.technet.com/secguide) (英文)告訴我們。

或者，以電子郵件將您的意見寄至 [SecWish@microsoft.com](mailto:secwish@microsoft.com?subject=windows%20xp%20安全性%20指南)。 我們通常會盡力對寄送至本信箱的意見作出回應。

我們期待收到您的意見。

[](#mainsection)[回到頁首](#mainsection)

### 顧問與支援服務

有多種可用服務可協助組織保護安全性。使用下列連結可幫助您找到所需服務：

關於 Microsoft 黃金級認證夥伴 (Microsoft Gold Certified Partners)、Microsoft 認證技術教育中心 (Microsoft Certified Technical Education Centers)、Microsoft 認證夥伴 (Microsoft Certified Partners)，以及採用 Microsoft 技術的獨立軟體廠商 (ISV) 的產品，請利用 [Microsoft 資源目錄](http://directory.microsoft.com/resourcedirectory/solutions.aspx)進行搜尋，網址是：http://directory.microsoft.com/resourcedirectory/Solutions.aspx。

若要尋找符合組織需求的顧問與支援服務，請造訪 [Microsoft 技術支援服務](http://support.microsoft.com/msservices)，網址是：http://support.microsoft.com/msservices。

[](#mainsection)[回到頁首](#mainsection)

##### 下載

[![](images/Cc163061.icon_exe(zh-tw,TechNet.10).gif)下載 Windows XP 安全性指南 (英文)](http://go.microsoft.com/fwlink/?linkid=14840)

[](#mainsection)[回到頁首](#mainsection)
