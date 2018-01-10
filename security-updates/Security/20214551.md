---
TOCTitle: '概觀 - 降低 Windows NT 4.0 與 Windows 98 安全性威脅'
Title: '概觀 - 降低 Windows NT 4.0 與 Windows 98 安全性威脅'
ms:assetid: 'f114078a-7e91-4269-88f0-445520350634'
ms:contentKeyID: 20214551
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc751251(v=TechNet.10)'
---

Windows NT 4.0 與 Windows 98 降低安全性威脅指南
===============================================

### 概觀

發佈日期: 2004 年 9 月 13 日 | 更新日期: 2006 年 3 月 30 日

本指南說明如何識別網路中如果包含執行 Microsoft® Windows NT® 4.0 與 Windows® 98 作業系統的電腦時的安全性問題，並為各組織提供升級上述作業系統前，最合適完善的強化策略。

##### 本頁內容

[](#edaa)[誰應該閱讀本指南](#edaa)
[](#ecaa)[內容規劃](#ecaa)
[](#ebaa)[歡迎您提供意見](#ebaa)
[](#eaaa)[顧問與支援服務](#eaaa)

### 誰應該閱讀本指南

本指南的預期讀者包括系統架構設計師、IT 經理與系統管理員、技術決策者，以及需要保護仍使用 Windows NT 4.0 與 Windows 98 作業系統的基礎結構之顧問人員。

[](#mainsection)[回到頁首](#mainsection)

### 內容規劃

**《Microsoft Windows NT 4.0 與 Windows® 98 降低安全性威脅指南》**提供舊版 Windows 作業系統網路與電腦的強化程序。組織中可能有各種電腦組合，包括執行 Windows NT 4.0 (Workstation、Server 及 Advanced Server) 和 Windows 98 作業系統，也可能有較新版本的 Windows 用戶端或伺服器。本指南著重討論適用 Active Directory 目錄服務網域環境中的 Windows NT 4.0 Workstation、Windows 98 用戶端和 Windows NT 4.0 成員伺服器，以幫助提高其安全性的保護措施。

本指南分為兩個部分，共有八章。第一部分由第 1 章＜簡介＞和第 2 章＜Trey Research 安全性風險管理法則應用案例＞所組成，這兩章都適用於所有層級的執行人員與 IT 管理者。

#### 第 1 章：簡介

第 1 章提供執行摘要、介紹舊作業系統安全性相關挑戰和優勢、指明本指南的推薦讀者、列出讀者的先決條件，並提供本指南中各章和解決方案案例的概觀。

#### 第 2 章：Trey Research 安全性風險管理法則應用案例

本章詳細介紹了用於開發本指南中建議的公司案例，並說明 IT 管理人員如何評估網路基礎結構的安全性風險和弱點。本案例中的虛擬公司 Trey Research 總部設於西雅圖，在美國幾個州都有辦事處。本章也說明 IT 管理人員如何識別並按照優先順序排列各個組織的風險和弱點，從而找出安全性需求，並據此建立行動計畫降低安全性威脅。

本指南的第二部分由六章組成，其中提供的規定資訊適用於 IT 系統管理員與技術管理員。每章都以討論設計原則與選項開頭，然後再介紹為目標案例選擇的特定強化措施。

#### 第 3 章：網路安全性與強化

第 3 章說明網路安全性弱點，以及強化網路元件 (包括用戶端與伺服器電腦) 以避免受侵害的程序。本章討論如何分割網路、強化傳輸控制通訊協定/網際網路通訊協定 (TCP/IP) 堆疊，以及如何使用個人防火牆以保護用戶端。

#### 第 4 章：強化 Windows NT 4.0

第 4 章說明如何透過建立系統基準並應用特定強化措施，以強化 Windows NT 4.0 (Workstation 與 Server)。它說明了實體安全性的重要性與方法，以及將安全性原則應用在檔案、列印、網路和應用程式伺服器的程序。本章會討論各種安全性方法的折衷辦法，並以對 Trey Research 最有利的強化原則詳細說明作為結束。

#### 第 5 章：強化 Windows 98

第 5 章說明如何強化 Windows 98 用戶端與應用程式，並說明在執行 Windows 98 的電腦上套用補充程式、更新及安全性原則的方法。

#### 第 6 章：補充程式管理

第 6 章說明如何及時發現最新更新，並在整個組織中迅速、可靠地實作，並確保整個組織均已部署最新更新。它說明了補充程式管理實作的折衷辦法，並以對 Trey Research 補充程式管理系統的詳細說明作為結束。

#### 第 7 章：防毒

第 7 章說明防毒軟體與原則的重要性，並說明用戶端及伺服器類型防毒解決方案的安全性與支援性。

#### 第 8 章：結論

最後一章提供整本指南中討論的強化程序之簡短摘要。

[](#mainsection)[回到頁首](#mainsection)

### 歡迎您提供意見

Microsoft 歡迎您對此資料提供回饋。我們尤其感謝您針對下列問題提供任何意見：

-   提供的資訊有多大的幫助？

-   逐步的處理程序是否正確？

-   各章節內容是否易讀且有趣？

-   整體而言，您對於本指南的評價為何？

請將您的意見傳送到 [secwish@microsoft.com](mailto:secwish@microsoft.com?subject=windowsxpsecurityguide)。我們期待收到您的意見。

[](#mainsection)[回到頁首](#mainsection)

### 顧問與支援服務

有多種可用服務可協助組織保護安全性。使用下列連結有助您找到所需服務：

關於 Microsoft 黃金級認證夥伴、Microsoft 授權技術教育訓練中心、Microsoft 認證夥伴，以及使用 Microsoft 技術的獨立軟體廠商 (ISV) 的產品，請到 Microsoft 資源目錄進行搜尋，網址是：[http://directory.microsoft.com/resourcedirectory/Solutions.aspx](http://directory.microsoft.com/resourcedirectory/solutions.aspx)。

若要尋找組織所需的適當顧問與支援服務，請造訪 Microsoft 技術支援服務：[http://support.microsoft.com/default.aspx?scid=fh;EN-US;msservices](http://support.microsoft.com/default.aspx?scid=fh;en-us;msservices)。

**下載完整的解決方案**
[Windows NT 4.0 與 Windows 98 降低安全性威脅指南](http://go.microsoft.com/fwlink/?linkid=32049)

[](#mainsection)[回到頁首](#mainsection)
