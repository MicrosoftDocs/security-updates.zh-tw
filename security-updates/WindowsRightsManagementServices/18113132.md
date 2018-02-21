---
TOCTitle: 安裝具有 Service Pack 1 的 RMS
Title: 安裝具有 Service Pack 1 的 RMS
ms:assetid: 'dab20175-a690-43f8-b943-768d289daa0d'
ms:contentKeyID: 18113132
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc747689(v=WS.10)'
---

安裝具有 Service Pack 1 的 RMS
==============================

若要執行此程序，您必須以您正在存取的電腦上 Administrators 群組成員的網域使用者帳號，在本機登入管理網站。Domain Admins 群組的成員也可以執行此程序。兼顧安全性的最佳作法是，使用 **\[執行身分\]** 來執行此程序。

您安裝 RMS 的電腦必須是網域中的成員伺服器，或者是網域控制站。您無法在工作群組中的獨立式伺服器上部署 RMS。

> [!Important]  
> 在您完成首部根憑證伺服器的安裝和提供之前，請不要在任何其他伺服器上提供 RMS。如需相關指示，請參閱本主題後面的＜[提供首部根憑證伺服器](https://technet.microsoft.com/debc42f3-74ff-4c99-b7a4-4921fccdabc2)＞、＜[提供授權伺服器](https://technet.microsoft.com/4d67b898-0ba9-4eef-ab7d-ee0ca55a688e)＞或＜[新增伺服器至叢集](https://technet.microsoft.com/db635238-5528-4bec-9cc6-8244e2b3d733)＞。

> [!Important]  
> RMS SP1 可以安裝在目前正在執行之前 RMS 版本的伺服器上。但是，如果您已經解除委任 RMS，則必須先使用 \[新增或移除程式\] 完全移除 RMS，然後才能嘗試安裝 RMS SP1。

安裝具有 Service Pack 1 的 RMS
------------------------------

#### 安裝具有 Service Pack 1 的 RMS

1.  在您想要安裝 RMS SP1 的伺服器上，以本機 Administrators 群組成員的網域帳號登入。

2.  當 **\[歡迎使用\]** 對話方塊出現時，檢視要安裝的軟體清單，然後按一下 **\[下一步\]**。

3.  在 **\[授權合約\]** 對話方塊中，檢視合約內容，選取 **\[我同意\]**，然後按一下 **\[下一步\]**。

4.  在 **\[資料夾\]** 中，接受預設的資料夾或指定新的資料夾，然後按一下 **\[下一步\]**。

5.  在 **\[確認安裝\]** 對話方塊中，按一下 **\[安裝\]** 開始安裝。

6.  當 **\[安裝完成\]** 對話方塊出現時，按一下 **\[關閉\]**。

    > [!Note]  
	> 如果出現 \[正在重新啟動應用程式\] 錯誤訊息，請在 Microsoft Internet Explorer 中重新整理 **\[通用管理\]** 頁面。 

您也可以在命令提示下安裝 RMS。如需相關指示，請參閱本主題後面的＜[RMS 伺服器命令提示字元安裝](https://technet.microsoft.com/b55b1e2a-dd14-4168-a37f-9cdedbec660b)＞。
