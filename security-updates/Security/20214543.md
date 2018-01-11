---
TOCTitle: 在 Windows 伺服器環境中建立 Windows 2000 Professional 用戶端的安全性
Title: 在 Windows 伺服器環境中建立 Windows 2000 Professional 用戶端的安全性
ms:assetid: 'ff560a26-f350-47b2-9e2c-e399a4524e62'
ms:contentKeyID: 20214543
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc875838(v=TechNet.10)'
---

在 Windows 伺服器環境中建立 Windows 2000 Professional 用戶端的安全性
====================================================================

### Overview

發佈日期: 2003 年 5 月 22 日 | 更新日期: 2006 年 4 月 13 日

##### 本頁內容

[](#elaa)[簡介](#elaa)
[](#ekaa)[開始之前](#ekaa)
[](#ejaa)[下載 Windows 2000 安全性範本](#ejaa)
[](#eiaa)[設定 Active Directory 網域基礎結構](#eiaa)
[](#ehaa)[建立新的群組原則物件和匯入安全性範本](#ehaa)
[](#egaa)[確認應用於桌上型與膝上型電腦的原則](#egaa)
[](#efaa)[驗證新的設定值](#efaa)
[](#eeaa)[安裝分散式防火牆軟體](#eeaa)
[](#edaa)[安裝防毒軟體](#edaa)
[](#ecaa)[維護目前的補充程式等級](#ecaa)
[](#ebaa)[將檔案系統轉換成 NTFS](#ebaa)
[](#eaaa)[相關資訊](#eaaa)

### 簡介

入侵者及惡意程式碼的威脅，例如病毒與蠕蟲，不斷地持續成長；因此很重要的是，不論規模大小的組織都必須立即採取行動，以建立桌上型電腦及膝上型電腦的安全性。病毒是一種會影響電腦檔案的侵入程式，此程式將具有自我複製能力的程式碼複本插入電腦檔案中，使其受到感染；而蠕蟲則是一種獨立運作的程式，跨過網路連線在電腦之間遊走。本文將告訴您如何在中小型企業的環境中，以 Microsoft Active Directory® 的目錄服務，執行《Microsoft® Windows® 2000 Security Hardening Guide (英文)》所建議的安全性方法。

本文的目標是要以明確、簡潔的指示，說明如何下載 Windows 2000 安全性範本、如何在網路上的網域主控台設定 Active Directory 網域基礎結構的組態，以及如何建立新的群組原則物件 (Group Policy Object，GPO) 匯入安全性範本，提高您的網路中所有電腦的安全性。同時也提供有關如何驗證新設定值、安裝分散式防火牆與防毒軟體、維護目前的補充程式等級、以及將電腦的檔案系統轉換為 NTFS等詳細資訊。

以下將概括列出本文所討論的主題與內容：

-   下載已預先設定好組態的安全性範本，自動變更您的系統使電腦更安全。

-   設定 Active Directory 網域基礎結構的組態，管理您的網路中所有執行 Microsoft Windows® 2000 Professional 電腦的安全性等級。

-   將原則應用在您的桌上型電腦及膝上型電腦。

-   驗證新的設定值。

-   安裝分散式防火牆軟體。

-   安裝防毒軟體。

-   將電腦的檔案系統轉換為 NTFS 格式，可以比 FAT 檔案系統提供更高的安全性等級。

-   使用安全性補充程式讓系統保持最新狀態。

這些建議將協助您確保系統中所有執行 Windows 2000 Professional Service Pack 4 的桌上型及膝上型電腦更為安全，可以免於目前大多數的安全性威脅，讓使用者的電腦更具效率及生產力。本文中除了詳細的逐步說明指南外，也將告訴您有關 Microsoft 提供給所有客戶 (包括家庭及企業使用者) 的最高安全性建議的詳細資訊。

**注意：**實作本指南的建議，有助於您的 Windows 2000 Professional 桌上型及膝上型電腦，與其他執行 Microsoft Windows® XP、Windows 2000、Windows Server™ 2003 的電腦溝通時更具有安全性。然而，Windows 2000 桌上型及膝上型電腦和其他執行 Microsoft Windows® 98 或 Microsoft Windows NT® 4.0 的電腦共用檔案、資料夾及印表機時，可能會有困難存在，因為 Windows 98 與 Windows NT 4.0 是較早期的作業系統，也比較難對付目前安全性的威脅。

**重要：**本文中所有逐步的指示說明，都是從安裝系統時預設出現的「開始」功能表所展開，如果您修改過「開始」功能表，步驟就會有稍許不同。

[](#mainsection)[回到頁首](#mainsection)

### 開始之前

在提供任何安全性建議的同時，本指南會努力找出增強型安全性與可用性之間的最佳平衡點。此處所提供的建議將於各種廣泛的環境中成功地部署 Windows 2000 Professional，但是在執行這些建議之前，必須特別注意幾個關鍵點。

本文並未特別說明在大型企業中可能需要的許多不同需求及組態。除此之外，可能也無法完全說明某些組織特定的安全性需求。

#### 符合 Service Pack 的需求

本文建議僅適用於執行 Windows 2000 Professional Service Pack 4 的電腦，因其屬於 Active Directory 網域的成員。如果 Service Pack 4 並未安裝於特定的電腦，或者您不確定是否已安裝，請造訪下列 Microsoft網站 [Windows Update (英文)](http://go.microsoft.com/fwlink/?linkid=22630) 頁面：[http://go.microsoft.com/fwlink/?LinkID=22630](http://go.microsoft.com/fwlink/?linkid=22630) 搜尋可使用的更新。如果 Service Pack 4 列出需更新的項目，在進行本文建議的程序之前，請先安裝更新程式。

##### 避免使用系統管理權限帳號

許多組織面臨一項共同的問題，就是使用者喜歡以系統管理認證執行他們的桌上型或膝上型電腦。最佳實務就是讓所有使用者帳戶都成為使用者群組的成員，不應該允許使用者例行地使用系統管理員群組的成員帳號登入系統；透過強制性的改變，使用者將無法再安裝未經核准的軟體，因為這些軟體可能會有病毒，或是其他具潛在危險性的程式碼。

執行這些需求極具挑戰性，但是使用具有標誌認證應用程式的 Windows 2000 Professional，將使執行變得容易許多。沒有系統管理權限的使用者，將無法正確執行尚未通過標誌驗證的應用程式。如果要搜尋標誌認證應用程式的清單，請在位於下列 Microsoft 網站上 [http://go.microsoft.com/fwlink/?LinkId=22382](http://go.microsoft.com/fwlink/?linkid=22382) 的 [Windows Catalog (英文)](http://go.microsoft.com/fwlink/?linkid=22382) 頁面，搜尋標示為 Designed for Windows 2000 的軟體。

系統管理員必須執行本文件的建議，但這些設定也提供一些功能，讓非 Administrators 群組的成員，能在日常工作中將其應用於桌上型或膝上型電腦。一旦執行了本文所建議的安全性設計，將可應用至所有登入桌上型或膝上型電腦的使用者，包括「本機系統管理員」在內。

[](#mainsection)[回到頁首](#mainsection)

### 下載 Windows 2000 安全性範本

安全性範本是含有安全性組態設定的檔案。如果要應用在系統上，需將安全性範本先匯入桌上型或膝上型電腦；以下程序將告訴您如何下載已預先設定組態的安全性範本，以建立桌上型或膝上型電腦的安全性。

此程序說明到何處取得 Windows 2000 安全性範本，以及如何將它安裝於您的電腦網路中的網域控制器上。確定範本是否已正確安裝，將使您有效地使用本文所提及之相關程序，以加強您電腦的安全性。

#### 需求

為完成此工作，您需要下列：

-   **認證**：您必須以 Domain Admins 群組的成員身份，登入網域控制站及成員電腦中。

-   **工具**：網頁瀏覽器、Windows 檔案總管。

<!-- -->

-   **若要下載安全性範本**

    1.  從成員電腦中，開啟網頁瀏覽器，巡覽至 Microsoft Download Center (英文) 網站 [http://go.microsoft.com/fwlink/?LinkId=22380](http://go.microsoft.com/fwlink/?linkid=22380) 的《[Windows 2000 Security Hardening Guide (英文)](http://go.microsoft.com/fwlink/?linkid=22380)》。

    2.  在網頁右邊灰色的 \[Windows 2000 Security Hardening Guide\] 方塊中，按一下 \[下載\]。

    3.  在 \[檔案下載\] 對話方塊中，按一下 \[存檔\]。

    4.  儲存位置的提示出現時，展開 \[儲存於:\] 下拉式清單方塊，按一下 \[桌上型電腦\]，再按一下 \[儲存\]。

    5.  在 \[下載完成\] 對話方塊中，按一下 \[關閉\]。

    6.  將下載的檔案 **W2KHG.exe** 複製到網站控制器的 \[我的文件\] 資料夾。

        **注意：** 逐步地將您電腦的檔案複製到網域控制站的步驟，會因為您的網路組態設定之不同而有所差異。您必須開啟一個新的檔案總管視窗，在網域控制站上指向共用的 C$，步驟為：依序按一下 \[開始\]，\[執行\]，然後鍵入 **\\\\Your\_Domain\_Controller\_Name\\c$**。

    7.  在網域控制站，按一下 \[開始\]，依序選取 \[程式集\]、\[附屬應用程式\]，再按一下 \[檔案總管\]。

    8.  使用檔案總管巡覽至 \[我的文件\] 資料夾，按二下 **W2KHG.exe** 檔案。

    9.  在 \[WinZip 解壓縮\] 對話方塊中，按一下 \[瀏覽\]。

    10. 按一下 \[My Documents\]，再按一下 \[確定\]。

    11. 在 \[WinZip 解壓縮\] 對話方塊中，按一下 \[解壓縮\]。

    12. 所有檔案都完成解壓縮之後，按一下 \[完成\]。

    13. 在 \[WinZip 解壓縮\] 視窗，按一下 \[關閉\]。

[](#mainsection)[回到頁首](#mainsection)

### 設定 Active Directory 網域基礎結構

群組原則是 Active Directory 的一項特性，有助於 Windows Server 2003、Windows 2000 Server 網域的變更與組態管理。然而，在您將群組原則套用至環境中的 Microsoft Windows 2000 Professional 用戶端之前，需要先在您的網域中進行特定的預備步驟。

請使用下列程序為您的電腦網路設定 Active Directory 基礎結構；建立這些結構之後，您就可以運用本文提到的相關程序，協助加強電腦的安全性。

#### 需求

為完成此工作，您需要下列：

-   **認證**：您必須以 Domain Admins 群組的成員身份，登入網域控制站。

-   **工具**：Active Directory 使用者及電腦嵌入式管理單元。

<!-- -->

-   **若要設定 Active Directory 網域基礎結構**
    使用嵌入式管理單元在網域中建立下列新的組織單元 (OU) 的子目錄：

    -   **安全的電腦 OU**： 此 OU 包括了系統環境中每一個作業系統的子 OU。

    -   **Windows 2000 OU**：此 OU 包括了系統環境中每一種類型的 Windows 2000 用戶端的子 OU。此處涵蓋了桌上型和膝上型用戶端的指南。

        **注意：**即使您依照本文的指示說明，將完全一樣的安全性設定應用於桌上型和膝上型電腦；但本指南亦提出如何為每一個系統建立個別的 OU，使您更容易針對系統中某個等級的用戶端電腦，建立特定的其他安全性組態。

    -   **桌上型電腦 OU**：此 OU 包含與您的公司網路經常保持連線的桌上型電腦。

    -   **膝上型電腦 OU**：此 OU 包含並未與您的公司網路始終保持連線之行動使用者的膝上型電腦。

下圖簡略列出所欲建立的 OU 結構：

![](images/Cc875838.sec_win2000_pro_server_env_01(zh-tw,TechNet.10).jpg)
1.  按一下 \[開始\]，按一下 \[設定\]，按一下 \[控制台\]，按兩下 \[系統管理工具\]，再按兩下 \[Active Directory 使用者及電腦\]。

2.  在網域的根容器，按一下滑鼠右鍵，滑鼠指標指向 \[新增\]，然後選取 \[組織單位\]。

    ![](images/Cc875838.sec_win2000_pro_server_env_02(zh-tw,TechNet.10).jpg)

    **注意：** 本文件的螢幕擷取畫面係顯示測試環境的資訊，與您的電腦所顯示的資訊未必相同。

3.  鍵入 **Secured Computers OU** 為新的 OU 命名，再按一下 \[確定\]。

4.  在 \[安全的電腦 OU\] 按一下滑鼠右鍵，滑鼠指標指向 \[新增\]，再選取 \[組織單位\]。

5.  鍵入 **Windows 2000 OU** 為新的 OU 命名，再按一下 \[確定\]。

6.  在 \[Windows 2000 OU\] 按一下滑鼠右鍵，滑鼠指標指向 \[新增\]，再選取 \[組織單位\]。

7.  鍵入 **Desktop OU** 為新的 OU 命名，再按一下 \[確定\]。

8.  在 \[Windows 2000 OU\] 按一下滑鼠右鍵，滑鼠指標指向 \[新增\]，再選取 \[組織單位\]。

9.  鍵入 **Laptop OU** 為新的 OU 命名，再按一下 \[確定\]。

10. 將所有執行 Windows 2000 的桌上型電腦，以拖曳方式從目前的 OU 位置搬移到新的 **Desktop OU**。

11. 將所有執行 Windows 2000 的膝上型型電腦，以拖曳方式從目前的 OU 位置搬移到新的 **Laptop OU**。

    **注意：**新電腦物件在 Active Directory 預設的新位置位於 \[Computer\] 容器中。

新的 OU 結構應該和下圖所顯示的一樣。

![](images/Cc875838.sec_win2000_pro_server_env_03(zh-tw,TechNet.10).jpg)
[](#mainsection)[回到頁首](#mainsection)

### 建立新的群組原則物件和匯入安全性範本

建立電腦安全性的下一個步驟，是要設定許多內建安全性的組態。然而這似乎是一項令人怯步的工作，以下將逐步說明如何使用內含於《Windows 2000 Security Hardening Guide (英文)》的 **W2KHG-baseline.inf** 與 **W2KHG-MemberWKS.inf** 檔案，來執行此項工作。

這些原則將設定組態，以確保只有有效的使用者可以連接到電腦，也只有系統管理員才可以在電腦上備份、儲存檔案，以及在系統上增加新的驅動程式。

使用下列程序建立新的 GPO (群組原則物件)，以便為網路上的桌上型電腦設定安全性的量值。GPO 讓您可以使用本文所提到的相關程序，以協助您加強電腦的安全性。

#### 需求

為完成此工作，您需要下列：

-   **認證**：您必須以 Domain Admins 群組的成員身份，登入網域控制站。

-   **工具**：Active Directory 使用者及電腦、命令提示字元。

<!-- -->

-   **若要為桌上型電腦建立 GPO**

    1.  如果需要的話，重新開啟「Active Directory 使用者及電腦」的嵌入式管理單元：依序按一下 \[開始\]、\[設定\]、\[控制台\]，按兩下 \[系統管理工具\]，再按兩下 \[Active Directory 使用者及電腦\]。

        1.  巡覽至 \[Desktop OU\]。

    2.  在 \[Desktop OU\] 按一下滑鼠右鍵，再選取 \[內容\]。

        ![](images/Cc875838.sec_win2000_pro_server_env_04(zh-tw,TechNet.10).jpg)

    3.  在 \[Desktop OU 內容\] 對話方塊中，按一下 \[群組原則\] 索引標籤，再按一下 \[新增\]。

    4.  鍵入 **2000 Desktop 原則** 為 GPO 命名，再按一下 \[編輯\]。

        ![](images/Cc875838.sec_win2000_pro_server_env_05(zh-tw,TechNet.10).jpg)

    5.  「群組原則物件編輯器」工具將開啟，並顯示您剛才在 \[群組原則物件連結\] 方塊中所建立的 GPO。

    6.  在 \[電腦組態\] 之下，展開 \[Windows 設定\] 資料夾，接著在 \[安全性設定\] 按一下滑鼠右鍵，然後選取 \[匯入原則\]。

        ![](images/Cc875838.sec_win2000_pro_server_env_06(zh-tw,TechNet.10).jpg)

    7.  在 \[匯入原則自\] 對話方塊下拉式清單方塊中展開 \[範本\] 資料夾，然後巡覽至 **\\My Documents\\Templates\\**。

    8.  選取 **W2KHG-baseline.inf** 安全性範本，按一下 \[開啟\]。

        **注意：**如果沒有看到 W2KHG-baseline.inf 檔案，您可能是將它儲存在別的位置，那麼就必須將這個 W2KHG.exe 自我解壓縮檔，再重新解壓縮一次。

        ![](images/Cc875838.sec_win2000_pro_server_env_07(zh-tw,TechNet.10).jpg)

    9.  重複上面的步驟 6，在 \[安全性設定\] 按一下滑鼠右鍵，再選取 \[匯入原則自\]。

    10. 選取 **W2KHG-MemberWKS.inf** 安全性範本，按一下 \[開啟\]。

        ![](images/Cc875838.sec_win2000_pro_server_env_08(zh-tw,TechNet.10).jpg)

    11. 關閉「群組原則物件編輯器」工具。

    12. 關閉 \[Desktop OU 內容\] 對話方塊。

使用下列程序建立新的 GPO (群組原則物件)，以便為網路上的膝上型電腦設定安全性的量值。GPO 讓您可以有效地使用本文所提到的相關程序，以協助您加強電腦的安全性。

-   **若要為膝上型電腦建立 GPO：**

    1.  如果需要的話，重新開啟「Active Directory 使用者及電腦」的嵌入式管理單元：依序按一下 \[開始\]、\[設定\]、\[控制台\]，按兩下 \[系統管理工具\]，再按兩下 \[Active Directory 使用者和電腦\]。

    2.  在 \[Laptop OU\] 按一下滑鼠右鍵，再選取 \[內容\]。

    3.  在 \[Laptop OU 內容\] 對話方塊中，按一下 \[群組原則\] 索引標籤，再按一下 \[新增\]。

    4.  鍵入 **2000 Laptop Policy** 為 GPO 命名，再按一下 \[編輯\]。

    5.  「群組原則物件編輯器」工具將開啟，並顯示您剛才在 \[群組原則物件連結\] 方塊中所建立的 GPO。

    6.  在 \[電腦設定\] 之下，展開 \[Windows 設定\] 資料夾，接著在 \[安全性設定\] 按一下滑鼠右鍵，然後選取 \[匯入原則\]。

    7.  在 \[匯入原則自\] 對話方塊下拉式清單方塊中展開 \[範本\] 資料夾，然後巡覽至 \\My Documents\\Templates\\

    8.  選取 **W2KHG-baseline.inf** 安全性範本，按一下 \[開啟\]。

        **注意：**如果沒有看到 W2KHG-baselin.inf 檔案，您可能是將它儲存在別的位置，那麼就必須將這個 W2KHG.exe 自我解壓縮檔，再重新解壓縮一次。

    9.  重複步驟 6，在 \[安全性設定\] 按一下滑鼠右鍵，再選取 \[匯入原則\]。

    10. 選取 **W2KHG-MemberWKS.inf** 安全性範本，按一下 \[開啟\]。

    11. 關閉「群組原則物件編輯器」工具。

    12. 關閉 \[Laptop OU 內容\] 對話方塊。

    13. 等到所有的網域控制站之間都複製完成，用戶端電腦不管是用哪一台網域控制站登入，都可以使用新的群組原則。

[](#mainsection)[回到頁首](#mainsection)

### 確認應用於桌上型與膝上型電腦的原則

您現在可以準備將安全性設定應用在桌上型或膝上型電腦，使用 secedit.exe 命令，可以確認此設定是否能應用於電腦。您可以使用下列程序強制更新群組原則，完成這些程序之後，再重新啟動系統，將可以確認您是否可以成功地應用這些安全性原則。

#### 需求

為完成此工作，您需要下列：

-   **認證**：您必須以 Domain Admins 群組的成員身份，登入桌上型或膝上型電腦。

-   **工具**：命令提示字元、secedit.exe。

<!-- -->

-   **若要強制更新群組原則**

    1.  按一下 \[開始\]，按一下 \[執行\]，鍵入 **cmd**，再按一下 \[確定\]。

    2.  在命令提示字元鍵入 **secedit/refreshpolicy machine\_policy /enforce**，再按一下 ENTER 鍵。

        ![](images/Cc875838.sec_win2000_pro_server_env_09(zh-tw,TechNet.10).jpg)

    3.  在「應用程式事件記錄檔」中，確認是否已成功下載此原則：依序按一下 \[開始\]、\[設定\]、\[控制台\]。

    4.  在 \[控制台\] 中，按兩下 \[系統管理工具\]。

    5.  在 \[系統管理工具\] 中，按兩下 \[事件檢視器\]。

    6.  在 \[事件檢視器\] 中，按一下 \[應用程式記錄檔\]，從中尋找最近以下列方式定義的事件：

        -   \[類型\] 為 Information。

        -   \[原始檔\] 為 SceCli。

        -   \[事件識別碼\] 號碼為 704。

    7.  如果連續按兩下此事件，您會看到一個和下面 \[事件內容\] 一樣的對話方塊：

        ![](images/Cc875838.sec_win2000_pro_server_env_10(zh-tw,TechNet.10).jpg)

    8.  重新啟動電腦。
        一旦系統重新啟動，就可以成功地應用安全性原則。在上圖中，\[事件\] 索引標籤上的 \[描述:\] 方塊，也指出：GPO 已經可以成功應用。

[](#mainsection)[回到頁首](#mainsection)

### 驗證新的設定值

下列的程序及資訊，可以讓您驗證最適切的安全性設定是否已應用於您系統中的本機電腦。請使用下列程序來檢視您機器上的本機電腦設定值，驗證這些設定值，可以進一步確認您的電腦已經有效地啟用正確的安全性設定。

#### 需求

為完成此工作，您需要下列：

-   **認證**：您必須以 Domain Admins 群組的成員身份登入。

-   **工具**：本機安全性原則 (Local Security Policy) 嵌入式管理單元、控制台。

<!-- -->

-   **若要在您的電腦上驗證安全性原則**

    1.  按一下 \[開始\]，按一下 \[設定\]，然後按一下 \[控制台\]。

    2.  在 \[控制台\] 中，按兩下 \[系統管理工具\]。

    3.  在 \[系統管理工具\] 中，按兩下 \[本機安全性原則\]。

    4.  在 \[本機安全性設定值\] 主控台樹狀目錄，展開 \[本機原則\] 資料夾，再按一下 \[安全性選項\] 資料夾。

        ![](images/Cc875838.sec_win2000_pro_server_env_11(zh-tw,TechNet.10).jpg)

    5.  在右邊 \[安全性選項\] 資料夾的詳細資料窗格中，檢視可應用的安全性選項原則設定值。

    6.  您只需要檢視少數的設定值，是否已經從原始數值變更為更新、更安全的設定；因此，請謹慎地檢視下列設定值：

        1.  檢視名稱為 \[匿名連線的其他限制\] 的原則，是否已經被設定成 \[拒絕缺乏明確匿名使用權限者的存取\]。

        2.  檢視名稱為 \[數位簽章伺服器通訊 (永遠)\] 的原則，是否已經被設定成 \[啟用\]。

        3.  檢視名稱為 \[防止系統維護電腦帳號密碼\] 的原則，是否已經被設定成 \[停用\]。

[](#mainsection)[回到頁首](#mainsection)

### 安裝分散式防火牆軟體

分散式防火牆軟體通常是指主機防火牆或個人的防火牆，可以在網路上協助預防攻擊者及蠕蟲侵入電腦系統。此技術的使用極為重要，因其可預防遠端或行動使用者傳送不明的惡意程式。分散式防火牆是一種安裝於個別系統的軟體，但卻使用集中式的存取原則。端視您所選取的軟體而定，主機防火牆所能提供的功能遠超過網路防火牆，例如：保護電腦不受間諜軟體及特洛伊木馬程式的威脅。特洛伊木馬程式是種惡意的應用程式軟體，其設計看起來似乎是正常的軟體，例如：特洛伊木馬程式可以模仿財務軟體的登入對話方塊，讓攻擊者收集到使用者的密碼。

Windows XP 含有一個內建的防火牆可提供此功能，稱為「網際網路連線防火牆」(ICF，Internet Connection Firewall)；Microsoft 原本設計 ICF 是給家庭使用者而非企業用戶，但對很多組織而言，ICF 卻提供了其他層級的保護來對付網路的攻擊，蠕蟲及拒絕服務攻擊等。如果您尚未準備將 Windows 2000 Professional 的電腦升級至 Windows XP，為這些電腦購置及部署分散式防火牆就顯得十分重要。

大部分協力廠商的防火牆可以保護電腦，不允許某些軟體侵犯使用者的隱私，或讓攻擊者濫用使用者的電腦。如果您要尋找更多有關軟體廠商所提供之常用的分散式防火牆產品，請造訪下列網站：

-   [Symantec](http://www.symantec.com/microsoft)，網站位於：<http://www.symantec.com/microsoft> (英文)。

-   [McAfee Security](http://www.networkassociates.com/us/products/home.htm)，網站位於：<http://www.networkassociates.com/us/products/home.htm> (英文)。

-   [ZoneAlarm](http://www.zonelabs.com/store/content/home.jsp)，網站位於：<http://www.zonelabs.com/store/content/home.jsp> (英文)。

-   [Tiny Personal Firewall](http://www.tinysoftware.com/home/tiny2?la=en)，網站位於：[http://www.tinysoftware.com/home/tiny2?la=EN](http://www.tinysoftware.com/home/tiny2?la=en) (英文)。

-   [Internet Security Systems](http://blackice.iss.net/)' BlackICE PC Protection，網站位於：[http://blackice.iss.net/](http://blackice.iss.net/.) (英文)。

[](#mainsection)[回到頁首](#mainsection)

### 安裝防毒軟體

電腦病毒是一種程式，未經過您的瞭解及核准就載入於您的系統中。病毒與其他形式的惡意軟體已存在多年，現在的病毒能夠自我複製，並透過網際網路及電子郵件等應用程式，在數小時內散播至全世界。

防毒軟體持續地掃瞄電腦偵測病毒，且將偵測到的病毒移除。安裝防毒軟體僅能解決部分的問題，隨時保持最新的防毒軟體病毒碼，對於維護桌上型與膝上型電腦的安全性也很重要。

教育使用者如何安全地使用電子郵件，是另一項預防病毒攻擊的重要步驟。使用者不應該隨意開啟電子郵件或電子郵件的附加檔案，除非他們原先已預期會收到郵件，而且可以驗證郵件來源沒有問題；確定所有電子郵件的附加檔案均以防毒軟體掃瞄過之後，才能開始執行這些檔案。

如果您要尋找更多有關軟體廠商提供的防毒軟體與 Windows 2000 相容性的詳細資訊，請參閱 Microsoft 網站上的《[List of Antivirus Software Vendors (英文)](http://go.microsoft.com/fwlink/?linkid=22381)》頁面，網址是 [http://go.microsoft.com/fwlink/?LinkId=22381](http://go.microsoft.com/fwlink/?linkid=22381)。

[](#mainsection)[回到頁首](#mainsection)

### 維護目前的補充程式等級

為了要確定您的桌上型與膝上型電腦不隨時保持安全性，Microsoft 強烈地建議您以 Windows 2000 發佈的所有安全性修補程式更新電腦；對 Windows 2000 而言，若您的電腦與網際網路連線，更新程式是很容易的事。使用下列程序，可以簡單地設定電腦從 Microsoft 自動下載及安裝最近的更新程式。

下列程序會將您的電腦設定成可接收自動更新，若您的電腦能夠接收自動更新，有助於保護系統以對付企圖透過網際網路入侵您網路上的電腦的新病毒與蠕蟲。

#### 需求

為完成此工作，您需要下列：

-   **認證**：您必須以 Domain Admins 群組的成員身份登入桌上型或用戶端電腦。

-   **工具**：控制台。

<!-- -->

-   **若要將您的電腦設定為自動更新**

    1.  按一下 \[開始\]，按一下 \[設定\]，然後按一下 \[控制台\]。

    2.  按兩下 \[自動更新\]。

    3.  選取標示為：\[將我的電腦保持在最新狀態\] 的核取方塊。啟動這個設定，在套用任何其他更新之前，Windows Update 軟體可以自動更新。

    4.  選取下列選項：\[自動下載更新，並在我指定的排程安裝它們\]。

    5.  選取一個要執行更新的日期與時間，然後按一下 \[確定\]，關閉 \[自動更新\] 視窗。

        ![](images/Cc875838.sec_win2000_pro_server_env_12(zh-tw,TechNet.10).jpg)

一旦啟用自動更新，新的更新就會依據您指定的排程，自動套用於電腦上。您可以任意設定自動下載的時間，不論白天或晚上，只要確定您的電腦是處於連線狀態 (為了避免速度降慢，Microsoft 建議您最好選擇不需使用電腦的時間進行下載，然而，電腦必須開著)。 如果設定自動更新於執行時必須先通知您，或者您忘了將電腦開機，您會看見一個通知汽球。按一下通知汽球即可檢視說明並安裝更新。

[](#mainsection)[回到頁首](#mainsection)

### 將檔案系統轉換成 NTFS

檔案系統是電腦組織目錄及檔案的方式。在安裝 Windows 2000 的過程中，電腦會被設定成使用 FAT32 或 NTFS 檔案系統。

FAT32 是較早期的技術，使用於先前的 Windows 版本；NTFS 檔案系統比起先前的 (FAT) 檔案系統，速度較快也較為安全。為了獲得作業系統最佳的效能與安全性，請使用 NTFS 保護您電腦上所有磁碟分割的檔案系統。下列有兩項程序，第一項先確認您電腦的檔案系統類型，接著 (如果有需要的話)，再將檔案系統轉換成 NTFS。

-   **若要檢查電腦的檔案系統類型**

    1.  按一下 \[開始\]功能表，再按一下 \[我的電腦\]。

    2.  在要檢查的「磁碟機代號」上面按一下滑鼠右鍵，然後按一下 \[內容\]。

    3.  檔案系統應該是 NTFS。如果不是，可以使用 convert.exe 公用程式，將 FAT6 或 FAT32 轉換成 NTFS。

        ![](images/Cc875838.sec_win2000_pro_server_env_13(zh-tw,TechNet.10).jpg)

重複此項程序，檢查並轉換電腦上所有硬碟的磁碟分割。即使安裝作業系統時，檔案系統被設定成 FAT32，您也可以輕易地將它轉換成 NTFS 以提供更加的安全性。

轉換檔案系統為 NTFS 時，請注意磁碟名稱，或稱為磁碟區標籤 (在上圖中的**磁碟機 C**)，並且完成下列步驟。

請執行下列程序將檔案系統轉換成 NTFS，因為 NTFS 將提供電腦較高等級的安全性。

-   **若要將檔案系統轉換成 NTFS**

    1.  按一下 \[開始\]，按一下 \[執行\]，鍵入 **cmd**，再按一下 \[確定\]。

    2.  在 \[命令提示字元\] 鍵入下列文字，其中 *drive letter* 是指您想要轉換的磁碟機：

        1.  **Convert** *drive letter***: /fs:ntfs**

    3.  接著將提示您輸入磁碟機目前的磁碟區標籤，請輸入先前已識別過的磁碟區標籤，再按一下 ENTER。

    4.  轉換完成後，鍵入 EXIT，再按一下 ENTER，關閉 \[命令提示字元\]。

        **注意：** 如果您想在已經安裝好作業系統的磁碟上進行轉換，可以先將轉換列入排程，於下一次重新啟動系統時立即進行轉換。若發生這種情況，鍵入 Y 然後重開機。

[](#mainsection)[回到頁首](#mainsection)

### 相關資訊

如需更多有關建立 Windows 2000 安全性的詳細資訊，請參閱下列文件：

-   《[Windows 2000 Security Hardening Guide (英文)](http://go.microsoft.com/fwlink/?linkid=22380)》，請造訪下列 Microsoft 網站下載完整的指南： [http://go.microsoft.com/fwlink/?LinkId=22380](http://go.microsoft.com/fwlink/?linkid=22380)

-   《[Guide to Securing Windows XP in Small and Medium Businesses (英文)](http://go.microsoft.com/fwlink/?linkid=19453)》網頁，位於下列 Microsoft 網站 <http://go.microsoft.com/fwlink/?linkid=19453>。

如需更多有關 Windows 2000 安全性的相關主題的詳細資訊，請參閱下列文件：

-   [Threats and Countermeasures Guide (英文)](http://go.microsoft.com/fwlink/?linkid=15159) 網頁，位於下列 Microsoft 網站 [http://go.microsoft.com/fwlink/?LinkID=15159](http://go.microsoft.com/fwlink/?linkid=15159)。

-   《Security Guidance Kit (英文)》內＜Selecting Secure Passwords＞文件中的＜Develop Password Policy Guidelines＞章節。

-   《Security Guidance Kit (英文)》內＜Enforcing Strong Password Usage Throughout Your Organization＞文件中的＜Enforce a Strong Password Policy on All Machines＞章節。

[](#mainsection)[回到頁首](#mainsection)
