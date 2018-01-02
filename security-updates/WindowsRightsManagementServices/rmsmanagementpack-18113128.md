---
TOCTitle: 匯入及使用 RMS Management Pack
Title: 匯入及使用 RMS Management Pack
ms:assetid: 'd9a73ef0-2f81-48c2-97cc-deb7bf477389'
ms:contentKeyID: 18113128
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc747688(v=WS.10)'
---

匯入及使用 RMS Management Pack
==============================

匯入及使用 RMS Management Pack
------------------------------

#### 匯入及使用 RMS Management Pack

1.  將 RMS Management Pack (RMS\_MOMPack.akm) 從 %ProgramFiles%\\Windows Rights Management Services\\Tools 資料夾複製到 Microsoft Operations Manager (MOM) 伺服器。

2.  開啟 MOM Administrator 主控台，然後根據下列步驟匯入 RMS Management Pack：

    1.  在 MOM Administrator 主控台的主控台樹狀目錄中，展開 **\[Rules\]** 項目，然後在 **\[Processing Rule Groups\]** 項目上按一下滑鼠右鍵。
    2.  在快顯功能表上按一下 **\[Import Management Pack\]**。此時會顯示 **\[Import Management Pack\]** 對話方塊。
    3.  按一下 **\[Browse\]**，然後選取 RMS\_MOMPack.akm。

3.  指定合併或取代選項。如需有關合併或取代選項的詳細資訊，請參閱 Microsoft 網站 (http://www.microsoft.com/) 上，有關＜匯出和匯入 Management Pack＞ 的部分。

    按一下 **\[Replace\]**。取代選項會使匯入的管理套件覆寫現有的處理規則群組，不保留使用者建議。如果您想要將此管理套件和現有的管理套件合併，您應該在測試環境中這樣做，然後當您在生產環境中部署管理套件時使用 **\[Replace\]** 選項。

4.  按一下 **\[Import\]** 以匯入管理套件。

5.  在 **MOM Administrator** 主控台中，選取 **\[Configuration\]** 項目，然後按一下 **\[Agent Managers\]** 資料夾。

6.  在您已經匯入 RMS Management Pack 的伺服器名稱上按一下滑鼠右鍵，然後按一下 **\[Scan Managed Computers Now\]**。