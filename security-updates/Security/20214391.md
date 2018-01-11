---
TOCTitle: 如何在不受信任網路內的 Windows 2000 伺服器上停用 NetBIOS
Title: 如何在不受信任網路內的 Windows 2000 伺服器上停用 NetBIOS
ms:assetid: 'd42207e0-4cea-4c37-8c06-a102e2117e7a'
ms:contentKeyID: 20214391
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Dd548208(v=TechNet.10)'
---

如何在不受信任網路內的 Windows 2000 伺服器上停用 NetBIOS
========================================================

Overview

發佈日期: 2004 年 11 月 17 日 | 更新日期: 2006 年 5 月 31 日

##### 本頁內容

[](#efaa)[目標](#efaa)
[](#eeaa)[適用於](#eeaa)
[](#edaa)[如何使用本單元](#edaa)
[](#ecaa)[摘要](#ecaa)
[](#ebaa)[必須知道的事項](#ebaa)
[](#eaaa)[停用 SMB](#eaaa)

### 目標

透過本單元即可：

-   在不受信任網路內的伺服器上停用 NetBIOS。

[](#mainsection)[回到頁首](#mainsection)

### 適用於

本單元適用於下列產品及技術：

-   Microsoft® Windows® 2000 作業系統

[](#mainsection)[回到頁首](#mainsection)

### 如何使用本單元

使用本單元在不受信任網路內的伺服器上停用 NetBIOS，以減少伺服器的攻擊面。

[](#mainsection)[回到頁首](#mainsection)

### 摘要

本單元向您說明如何停用 NetBIOS，這是您應該特別針對位於不受信任網路內 (例如，可公開存取的 Web 伺服器或公司郵件閘道) 的伺服器套用的建議作法。如果您有伺服器位於不受信任的網路內，您應該考慮實作以下的變更，但請徹底加以測試，並確定您瞭解停用網路基本輸入/輸出系統 (NetBIOS) 對管理系統會有的挑戰。

**漏洞**

外圍網路內的伺服器都應該停用所有非必要的通訊協定，包括 NetBIOS 和伺服器訊息區 (SMB)。Web 伺服器和「網域名稱系統 (DNS)」伺服器並不需要 NetBIOS 或 SMB。這兩種通訊協定都應該要停用，以應付使用者列舉的威脅。使用者列舉是一種資訊收集的漏洞，攻擊者會在當中嘗試取得系統特定的資訊以計畫進一步的攻擊。

SMB 通訊協定會傳回有關電腦的大量資訊，甚至是傳給使用「Null」工作階段之未經驗證的使用者。可擷取的資訊包括網域和信任詳細資料、共用、使用者資訊 (包括群組和使用者權利)、登錄機碼和更多其他資訊。

**注意：**Null 工作階段可透過設定 **RestrictAnonymous** 登錄機碼加以封鎖。

**對策**

停用 NetBIOS 對於防止 SMB 通訊來說是不夠的。這是因為若沒有標準 NetBIOS 連接埠，SMB 會利用「傳輸控制通訊協定 (TCP)」連接埠 445，即稱作 SMB 直接主機。結果是必須採取明確的步驟分別停用 NetBIOS 和 SMB。

[](#mainsection)[回到頁首](#mainsection)

### 必須知道的事項

NetBIOS 會使用下列連接埠：

-   UDP/137 (NetBIOS 名稱服務)

-   UDP/138 (NetBIOS 資料包服務)

-   TCP/139 (NetBIOS 工作階段服務)

SMB 會使用下列連接埠：

-   TCP/139

-   TCP/445

在可從網際網路存取的伺服器上，您應該使用位於您區域網路連線內容中的「傳輸控制通訊協定/網際網路通訊協定 (TCP/IP)」內容對話方塊，透過移除 \[File and Printer Sharing for Microsoft Networks\] 和 \[Client for Microsoft Networks\] 來停用 SMB。

[](#mainsection)[回到頁首](#mainsection)

### 停用 SMB

-   **若要停用 SMB**

    1.  在 \[開始\] 功能表上，指向 \[設定\]，再按一下 \[網路和撥號連線\]。

    2.  在 \[網際網路面向連線 (Internet Facing Connection)\] 上按一下滑鼠右鍵，再按一下 \[內容\]。

    3.  選取 \[Client for Microsoft Networks\]，再按一下 \[解除安裝\]。

    4.  請遵循解除安裝步驟。

    5.  選取 \[File and Printer Sharing for Microsoft Networks\]，再按一下 \[解除安裝\]。

    6.  請遵循解除安裝步驟。

<!-- -->

-   **若要停用 NetBIOS over TCP/IP**

    1.  在桌面上的 \[我的電腦\] 按一下滑鼠右鍵，再按一下 \[管理\]。

    2.  展開 \[系統工具\]，再選取 \[裝置管理員\]。

    3.  在 \[裝置管理員\] 上按一下滑鼠右鍵，指向 \[檢視\]，再按一下 \[顯示隱藏的裝置\]。

    4.  展開 \[非隨插即用驅動程式\]。

    5.  在 \[NetBios over TCP/IP\] 上按一下滑鼠右鍵，再按一下 \[停用\]。

這會停用 TCP/445 和 UDP 445 上的 SMB 直接主機接聽程式。

**注意：**此程序會停用 nbt.sys 驅動程式。\[進階 TCP/IP 設定\] 對話方塊的 \[WINS\] 索引標籤包含了 \[停用 NetBIOS over TCP/IP\] 選項。選取此選項只會停用 NetBIOS 工作階段服務 (這會在 TCP 連接埠 139 上接聽)。這麼做並*不會* 完全停用 SMB。若要完全停用 SMB，請遵循上述的步驟。

**可能的影響**

沒有任何系統能夠經由 SMB 連線到伺服器。伺服器將無法存取網路上共用的資料夾。許多管理工具也將無法連線到伺服器。

[](#mainsection)[回到頁首](#mainsection)
