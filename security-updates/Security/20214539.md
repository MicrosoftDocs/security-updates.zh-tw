---
TOCTitle: 保障 Active Directory 管理群組和帳戶的安全
Title: 保障 Active Directory 管理群組和帳戶的安全
ms:assetid: 'c5c0c305-c887-4038-93b1-38e5de889b19'
ms:contentKeyID: 20214539
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc700835(v=TechNet.10)'
---

保障 Active Directory 管理群組和帳戶的安全
==========================================

##### 本頁內容

[](#ehaa)[簡介](#ehaa)
[](#egaa)[開始之前](#egaa)
[](#efaa)[建立 Domain Admins 認證的新使用者帳戶](#efaa)
[](#eeaa)[保護預設的 Administrator 帳戶](#eeaa)
[](#edaa)[保護 Guest 帳戶](#edaa)
[](#ecaa)[加強服務系統管理帳戶及群組的安全性](#ecaa)
[](#ebaa)[建立最佳的系統管理帳戶與群組實務](#ebaa)
[](#eaaa)[相關資訊](#eaaa)

### 簡介

確保網路安全的一項要務是管理對 Active Directory® 目錄服務有系統管理存取權的使用者及群組。取得 Active Directory 網域控制站系統管理存取權的惡意人士，可能破壞您網路的安全性。這些人士可能是取得系統管理密碼卻未經驗證的使用者，或者可能是受脅迫或不滿的合法系統管理員。此外，不是所有問題都是惡意企圖所造成的。一個取得系統管理存取權的使用者也可能因為不了解變更設定的分支而不慎造成問題。因此，小心管理擁有網域控制站的系統管理控制權的使用者及群組是很重要的。

預設的 Microsoft® Windows Server™ 2003 安全性設定足夠保護 Active Directory 帳戶免於多種類型的威脅。不過可強化系統管理帳戶的一些預設值，來加強您網路的安全性層級。

本指南提供逐步指示，教您如何：

-   利用 Domain Admins 認證建立新使用者帳戶

-   保護預設的 Administrator 帳戶

-   保護 Guest 帳戶

-   加強服務系統管理帳戶及群組的安全性

-   建立使用系統管理帳戶及群組的最佳實務。

請在管理網路時，使用本指南所講述的最佳實務。這樣有助降低未授權的使用者，取得 Active Directory 系統管理存取權、蓄意或意外複製、刪除機密資料、癱瘓您網路而損害您組織的風險。

**重要：**本文所有的逐步指示，均利用您安裝作業系統時預設出現的「開始」功能表來研發。如果您已修改您的「開始」功能表，步驟就可能稍微不同。

[](#mainsection)[回到頁首](#mainsection)

### 開始之前

在使用本指南保護您的系統管理群組及帳戶之前，首先完成《Security Guide Kit (英文)》中的＜Securing Windows Server 2003 Domain Controllers＞工作。

為了完成本指南提供的程序，您必須知道內建系統管理員帳戶的名稱及密碼，或是您網域控制站裡內建 Administrator 群組其中一個成員的帳戶名稱及密碼。請選定您作為網域控制站的網路伺服器 (或多個伺服器)。網域控制站是執行裝有 Active Directory 的 Windows Server 2003 的伺服器。

開始之前，您必須了解這些系統管理帳戶及群組，還有服務系統管理員和資料系統管理員如何分攤系統管理責任。若要檢視及管理 Active Directory 帳戶及群組，請按一下 \[開始\]，再選擇 \[系統管理工具\]，然後按一下 \[Active Directory 使用者和電腦\]。

#### 了解系統管理員帳戶及群組

在一個 Active Directory 網域的系統管理帳戶包括：

-   Administrator 帳戶，在網域第一個網域控制站安裝 Active Directory 時即建立。這是網域最強大的帳戶。在電腦安裝 Active Directory 的人在安裝時即建立帳戶密碼。

-   您後來新設在有系統管理特殊權限群組裡的帳戶，或是您直接指派系統管理特殊權限的帳戶。

Active Directory 網域的系統管理群組會依您安裝在網域的服務而有不同。特地用來管理 Active Directory 的群組包括：

-   \[Builtin\] 容器自動建立的系統管理群組。

-   \[User\] 容器自動建立的系統管理群組。

-   您後來新建立在另一個有系統管理特殊權限群組裡的群組，或是直接指派系統管理特殊權限的群組。

#### 了解服務管理員和資料管理員

Windows Server 2003 的 Active Directory 有兩種系統管理員責任。服務系統管理員負責維護及傳遞目錄服務，包括網域控制站管理及目錄服務設定。資料系統管理員負責維護儲存於目錄服務、網域成員伺服器及工作站的資料。

在小型組織裡這兩個角色可能由同一人執行，但重要的是要了解哪些預設帳戶及群組是服務系統管理員。服務系統管理帳戶及群組在您的網路環境有最廣泛的權力，需要最多的保護。它們負責目錄設定、安裝及軟體維護、網域控制站的作業系統 Service Pack 及更新的套用。

下表列出並簡述服務系統管理的預設群組和帳戶，以及它們的預設位置。\[Builtin\] 容器的群組不可移到另一個位置。

**預設服務系統管理員群組及帳戶**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >群組或帳戶名稱</th>
<th style="border:1px solid black;" >預設位置</th>
<th style="border:1px solid black;" >說明</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Enterprise Admins</td>
<td style="border:1px solid black;">[User] 容器</td>
<td style="border:1px solid black;">這個群組會自動新增到樹系每個網域的 Administrator 群組，以供完全存取所有網域控制站的設定。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Schema Admins</td>
<td style="border:1px solid black;">[User] 容器</td>
<td style="border:1px solid black;">這個群組擁有完全的 Active Directory 結構的系統管理存取權。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">[Builtin] 容器</td>
<td style="border:1px solid black;">這個群組可完全控制網域控制站和所有存在網域的目錄內容，也可變更網域所有系統管理群組的成員資格。是權力最大的服務系統管理群組。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Domain Admins</td>
<td style="border:1px solid black;">[User] 容器</td>
<td style="border:1px solid black;">這個群組會自動新增到樹系每個網域相對應的 Administrator 群組。這個群組可完全控制所有網域控制站和所有存在網域的目錄內容，也可修改網域系統管理員帳戶的成員資格。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Server Operators</td>
<td style="border:1px solid black;">[Builtin] 容器</td>
<td style="border:1px solid black;">依預設，這個內建群組沒有成員。它可執行維護工作，例如網域控制站的備份及還原。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Account Operators</td>
<td style="border:1px solid black;">[Builtin] 容器</td>
<td style="border:1px solid black;">依預設，這個內建群組沒有成員。它可建立及管理網域的使用者與群組，但不能管理服務系統管理員帳戶。最佳實務是不要新增會員到這個群組，也不要使用它來執行委派的系統管理。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Backup Operators</td>
<td style="border:1px solid black;">[Builtin] 容器</td>
<td style="border:1px solid black;">依預設，這個內建群組沒有成員。它能執行網域控制站的備份及還原作業。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">DS Restore Mode Administrator</td>
<td style="border:1px solid black;">未儲存在 Active Directory</td>
<td style="border:1px solid black;">這個特別帳戶在 Active Directory 安裝過程中建立，不同於 Active Directory 資料庫的 Administrator 帳戶。這個帳戶只用來啟動網域控制站的「目錄服務還原模式」。在「目錄服務還原模式」中，這個帳戶可完全存取系統及網域控制站的所有檔案。</td>
</tr>
</tbody>
</table>
  
列在這個表裡的帳戶及群組，以及這些群組的所有成員均受到幕後處理序的保護，這個處理序定期檢查及執行特別的安全性描述元，安全性描述元是一個含有受保護物件相關的安全性資訊的結構。這項處理序，會確保任何對系統管理帳戶或群組安全性描述元的未授權修改企圖，被受保護的設定覆寫。
  
這個安全性描述元存在於 AdminSDHolder 物件。這表示如果您要在其中一個服務管理員群組或裡面的成員帳戶修改權限，您就必須修改 **AdminSDHolder** 物件的安全性描述元，以便持續應用。修改時請小心，因為您也同時在變更所有受保護的系統管理員帳戶的預設設定。如需更多關於修改服務系統管理員帳戶權限的資訊，請參閱《[Best Practice Guide for Securing Active Directory Installations (英文)](http://go.microsoft.com/fwlink/?linkid=22342)》(Windows Server 2003)，位於 Microsoft 網站 [http://go.microsoft.com/fwlink/?LinkId=22342](http://go.microsoft.com/fwlink/?linkid=22342)。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 建立 Domain Admins 認證的新使用者帳戶
  
如果您在 Domain Admins 群組沒有預設 Administrator 帳戶以外的的使用者帳戶，請建立一個來執行本指南的工作。只有在您要執行需要 Domain Admin 認證的工作時，您會使用這個新帳戶作為網路的系統管理員。在您完成這些工作的執行之後，請登出這個帳戶。如果電腦在網域系統管理員登入時感染病毒，病毒會在網域系統管理員裡執行。如此，病毒就會利用系統管理員特殊權限來感染工作站及網路的其餘部分。請建立另一個使用者帳戶用以資料管理及日常使用，例如執行 Microsoft Office 和收發電子郵件，但不要將這個使用者帳戶放在 Domain Admins 群組。系統管理員帳戶的安全實務將在本文後面講述。
  
#### 需求
  
-   認證：Domain Admins (如果這是您建立的第一個系統管理帳戶，請使用預設 Administrator 帳戶登入)
  
-   工具：Active Directory 使用者和電腦
  
<!-- -->
  
-   **若要建立 Domain Admins 認證的新使用者帳戶**
  
    1.  請以 Domain Admins 群組成員登入，然後開啟「Active Directory 使用者和電腦」。
  
        **注意：** 本文的螢幕擷取檔案反映測試環境，資訊可能與您電腦顯示的資訊不同。
  
    2.  在 \[User\] 容器上按一下滑鼠右鍵，按一下 \[新增\]，然後再按一下 \[使用者\]。
  
        ![](images/Cc700835.sec_ad_admin_groups_01(zh-tw,TechNet.10).jpg)
  
    3.  鍵入 \[名字\]、\[姓氏\] 和 \[使用者登入名稱\]，然後按一下 \[下一步\]。如下面例子所示，您可能要遵循命名規格來命名系統管理員帳戶。舉例來說，您可決定附加「ALT」至系統管理使用者的名稱，作為系統管理帳戶的登入名稱。
  
        ![](images/Cc700835.sec_ad_admin_groups_02(zh-tw,TechNet.10).jpg)
  
    4.  請鍵入並確認使用者密碼，清除 \[使用者必須在下次登入時變更密碼\] 核取方塊，然後按一下 \[下一步\]。
  
        ![](images/Cc700835.sec_ad_admin_groups_03(zh-tw,TechNet.10).jpg)
  
    5.  請檢閱帳戶訊息，再按一下 \[完成\]。
  
    6.  選擇 \[User\] 容器之後，在詳細資料窗格 (右窗格) 按兩下 **Domain Admins** 群組。
  
        ![](images/Cc700835.sec_ad_admin_groups_05(zh-tw,TechNet.10).jpg)
  
    7.  按一下 \[成員\] 索引標籤。
  
        ![](images/Cc700835.sec_ad_admin_groups_05(zh-tw,TechNet.10).jpg)
  
    8.  按一下 \[新增\]，然後在 \[選擇使用者、連絡人或電腦\] 對話方塊，鍵入您剛剛建立的系統管理帳戶使用者登入名稱，再按一下 \[確定\]。
  
        ![](images/Cc700835.sec_ad_admin_groups_06(zh-tw,TechNet.10).jpg)
  
    9.  請確認您新帳戶呈現為 **Domain Admins** 群組的一員。
  
        ![](images/Cc700835.sec_ad_admin_groups_07(zh-tw,TechNet.10).jpg)
  
[](#mainsection)[回到頁首](#mainsection)
  
### 保護預設的 Administrator 帳戶
  
每個 Active Directory 的安裝在每一個網域都有一個名為 Administrator 的帳戶。不可刪除或鎖定這個帳戶。在 Windows Server 2003，Administrator 帳戶可停用，但是在您啟動電腦的安全模式時會自動重新啟用。
  
一個惡意使用者企圖闖進系統時，通常會先嘗試取得全能的 Administrator 帳戶密碼。因此請重新命名並變更 \[描述\] 來消除任何顯示它是 Administrator 帳戶的文字。此外，請建立一個沒有特別權限或使用者權限的誘餌使用者帳戶，命名為 Administrator。
  
永遠為這個 Administrator 帳戶建立一個又長又複雜的密碼。Administrator 和 DS 還原模式 Administrator 帳戶要使用不同的密碼。如需更多建立複雜密碼的資訊，請參閱《Security Guide Kit (英文)》中的＜Selecting Secure Passwords＞。
  
#### 重新命名預設 Administrator 帳戶
  
這項程序移除任何可警告攻擊者這個帳戶已提升特殊權限的明顯資訊。雖然攻擊者發現預設 Administrator 帳戶仍需要使用密碼，但是重新命名預設 Administrator 帳戶增加一層保護，避免提高特殊權限的攻擊。請使用和您其他使用者名稱同樣格式的虛擬姓名。請不要使用以下例子裡的虛擬姓名。
  
##### 需求
  
-   認證：Domain Admins
  
-   工具：Active Directory 使用者和電腦
  
<!-- -->
  
-   **若要重新命名預設 Administrator 帳戶**
  
    1.  以 Domain Admins 群組成員登入，然後開啟「Active Directory 使用者和電腦」。
  
    2.  在主控台樹狀目錄中 (左窗格) 按一下 \[使用者\]。
  
    3.  在詳細資料窗格 (右窗格) 的 \[Administrator\] 按一下滑鼠右鍵，然後再按一下 \[重新命名\]。
  
        ![](images/Cc700835.sec_ad_admin_groups_08(zh-tw,TechNet.10).jpg)
  
    4.  鍵入虛擬的姓名再按 Enter。
  
    5.  在 \[重新命名使用者\] 對話方塊中變更 \[全名\]、\[名字\]、\[姓氏\]、\[顯示名稱\]、\[使用者登入名稱\] 和 \[使用者登入名稱 (Windows 2000 前版)\] 來配合您的虛擬帳戶名稱，再按一下 \[確定\]。
  
        ![](images/Cc700835.sec_ad_admin_groups_09(zh-tw,TechNet.10).jpg)
  
    6.  在詳細資料窗格 (右窗格) 的新名稱按一下滑鼠右鍵，再按一下 \[內容\]。
  
    7.  在 \[一般\] 索引標籤中刪除 \[描述\] 中的「管理/電腦網域的內建帳戶」，再鍵入類似其他使用者帳戶的描述 (對多數組織而言，這裡可以空白)。
  
        ![](images/Cc700835.sec_ad_admin_groups_10(zh-tw,TechNet.10).jpg)
  
    8.  確認 \[帳戶\] 索引標籤的登入名稱是否正確。
  
        **注意：** 這個程序只變更預設 Administrator 帳戶的登入名稱和帳戶詳細資料，而這些都是別人設法列舉您系統上的帳戶清單之後就可看見的。這個程序不影響使用 DS 還原模式 Administrator 帳戶啟動「目錄服務還原模式」的能力，因為它們是兩個不同的帳戶。
  
#### 建立誘餌 Administrator 帳戶
  
在您隱藏預設 Administrator 帳戶時，這個程序增加一層額外的保護。這可引誘計畫攻擊 Administrator 帳戶密碼的攻擊者去攻擊一個沒有特別權限的帳戶。
  
##### 需求
  
-   認證：Domain Admins
  
-   工具：Active Directory 使用者和電腦
  
<!-- -->
  
-   **若要建立誘餌 Administrator 帳戶**
  
    1.  以 Domain Admins 群組成員登入，然後開啟「Active Directory 使用者和電腦」。
  
    2.  在 \[User\] 容器按一下滑鼠右鍵，按一下 \[新增\]，再按一下 \[使用者\]。
  
    3.  在 \[名字\] 和 \[使用者登入名稱\] 鍵入 **Administrator**，然後按一下 \[下一步\]。
  
        ![](images/Cc700835.sec_ad_admin_groups_11(zh-tw,TechNet.10).jpg)
  
    4.  鍵入及確認密碼。
  
    5.  清除 \[使用者必須在下次登入時變更密碼\] 核取方塊。
  
        ![](images/Cc700835.sec_ad_admin_groups_12(zh-tw,TechNet.10).jpg)
  
    6.  確認已經建立誘餌帳戶並按一下 \[完成\]。
  
        ![](images/Cc700835.sec_ad_admin_groups_13(zh-tw,TechNet.10).jpg)
  
    7.  在詳細資料窗格 (右窗格) 的 \[Administrator\] 按一下滑鼠右鍵，然後再按一下 \[內容\]。
  
    8.  在 \[一般\] 索引標籤的 \[描述\] 方塊鍵入「管理電腦/網域的內建帳戶」，然後按一下 \[確定\]。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 保護 Guest 帳戶
  
Guest 帳戶允許在您網域沒有帳戶的使用者，以來賓身分登入網域。這個帳戶預設停用，也應該保持停用，但是隱藏這個帳戶增加一層額外的保護避免未授權存取。請使用和您其他使用者名稱同樣格式的虛擬姓名。
  
#### 需求
  
-   認證：Domain Admins
  
-   工具：Active Directory 使用者和電腦
  
<!-- -->
  
-   **若要重新命名 Guest 帳戶**
  
    1.  以 Domain Admins 群組成員登入，然後開啟「Active Directory 使用者和電腦」。
  
    2.  在主控台樹狀目錄中 (左窗格) 按一下 \[使用者\]。
  
    3.  在詳細資料窗格 (右窗格) 的 \[Guest\] 按一下滑鼠右鍵，再按一下 \[變更名稱\]。
  
    4.  鍵入虛擬的姓名，再按一下 Enter。
  
    5.  在新名稱上按一下滑鼠右鍵，然後按一下 \[內容\]。
  
    6.  在 \[一般\] 索引標籤上，刪除 \[描述\] 中的「供來賓存取電腦/網域之用的內建帳戶」，並鍵入類似其他使用者帳戶的描述 (對多數組織而言，這裡可以空白)。
  
    7.  在 \[名字\] 和 \[姓氏\] 方塊鍵入虛擬名稱。
  
    8.  在 \[帳戶\] 索引標籤鍵入新的 \[使用者登入名稱\]，使用和您其他使用者帳戶名稱同樣格式的虛擬姓名，例如名字的第一個字母及姓氏。
  
    9.  在 \[使用者登入名稱 (Windows 2000 前版)\] 方塊鍵入同樣的新登入名稱，然後按一下 \[確定\]。
  
    10. 確認這個帳戶已停用。圖示上面應會顯現一個紅叉。如果已經停用，就在新名稱按一下滑鼠右鍵，再按一下 \[停用帳戶\]。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 加強服務系統管理帳戶及群組的安全性
  
在 Active Directory 建立一個受控制的組織單位 (OU) 樹狀子目錄，使用它推薦的安全性設定有助於提供一個安全的環境給服務系統管理員帳戶和工作站。
  
OU 是含有網域的容器，而這些網域可包含其他 OU、使用者、群組、電腦和其他物件。這些 OU 和子 OU 形成一個有網域的層級結構，主要用於群組物件的管理。
  
建立一個包含所有服務系統管理員帳戶，及它們使用的系統管理工作站的樹狀子目錄，您就可應用特定安全性和原則設定，達到最大的保護。
  
若要建立受控制的樹狀子目錄，請執行下列工作：
  
1.  建立受控制的樹狀子目錄的 OU 結構。
  
2.  設定受控制的樹狀子目錄 OU 的權限。
  
3.  將服務系統管理員群組移到受控制的樹狀子目錄。
  
4.  將服務系統管理員使用者帳戶移到受控制的樹狀子目錄。
  
5.  將服務系統管理員工作站帳戶移到受控制的樹狀子目錄。
  
6.  在受控制的樹狀子目錄 OU 啟用稽核。
  
#### 建立受控制的樹狀子目錄的 OU 結構
  
預建立樹狀子目錄，請建立三個 OU：
  
-   **Service Admins**，在網域根目錄之下，含有下列的兩個子 OU
  
    -   **Users and Groups**，含有系統管理使用者和群組帳戶。
  
    -   **Admin Workstations**，含有系統管理工作站。
  
##### 需求
  
-   認證：Domain Admins
  
-   工具：Active Directory 使用者和電腦
  
<!-- -->
  
-   **若要建立受控制的樹狀子目錄的 OU 結構**
  
    1.  以 Domain Admins 群組成員登入，然後開啟「Active Directory 使用者和電腦」。
  
    2.  在主控台樹狀目錄 (左窗格) 的網域名稱按一下滑鼠右鍵，指向 \[新增\]，然後再按一下 \[組織單位\]。
  
    3.  在 \[名稱\] 方塊鍵入 **Service Admins** ，並按一下 \[確定\]。
  
    4.  在主控台樹狀目錄 (左窗格) 的 \[Service Admins\] 按一下滑鼠右鍵，指向 \[新增\]，然後按一下 \[組織單位\]。
  
    5.  在 \[名稱\] 方塊鍵入 **Users and Groups**，並按一下 \[確定\]。
  
    6.  在主控台樹狀目錄 (左窗格) 的 \[Service Admins\] 按一下滑鼠右鍵，指向 \[新增\]，再按一下 \[組織單位\]。
  
    7.  在 \[名稱\] 方塊鍵入 **Admin Workstations** 並按一下 \[確定\]。
  
    8.  確認您的 OU 層級，類似下列的結構，\[Service Admins\] 在網域名稱底下的層級，而 \[Users and Groups\] 以及 \[Admin Workstation\] 在 \[Service Admins\] 底下的層級。
  
        ![](images/Cc700835.sec_ad_admin_groups_14(zh-tw,TechNet.10).jpg)
  
#### 設定受控制的樹狀子目錄 OU 的權限。
  
執行下列工作有助限制存取受控制的樹狀子目錄，以便只有服務系統管理員，能管理服務系統管理員群組和工作站的成員資格：
  
-   封鎖 Service Admins OU 的權限繼承，以便在網域樹狀高層所做的可繼承的權限變更，不會往下傳。
  
-   設定 Service Admins OU 的權限
  
##### 需求
  
-   認證：Domain Admins
  
-   工具：Active Directory 使用者和電腦
  
<!-- -->
  
-   **若要設定 Service Admins OU 的權限**
  
    1.  以 Domain Admins 群組成員登入，然後開啟「Active Directory 使用者和電腦」。
  
    2.  在 \[檢視\] 功能表，選擇 \[進階功能\]。
  
    3.  在 \[Service Admins\] OU 按一下滑鼠右鍵，然後再按一下 \[內容\]。
  
        ![](images/Cc700835.sec_ad_admin_groups_15(zh-tw,TechNet.10).jpg)
  
    4.  在 \[安全性\] 索引標籤按一下 \[進階\] 以檢視所有 OU 的權限項目。
  
        ![](images/Cc700835.sec_ad_admin_groups_16(zh-tw,TechNet.10).jpg)
  
    5.  清除 \[允許從父項繼承權限套用到這個物件和所有的子物件，包括明確定義於此的項目\] 核取方塊。
  
    6.  在 \[安全性\] 對話方塊按一下 \[移除\]。如此可移除從網域傳下來的權限。
  
        ![](images/Cc700835.sec_ad_admin_groups_17(zh-tw,TechNet.10).jpg)
  
    7.  移除其餘的權限。選擇所有其餘的權限項目再按一下 \[移除\]。
  
    8.  在下面表格名稱欄位所列的每一群組，新增一個權限項目來符合 \[存取權\] 和 \[適用於\] 欄位，如下圖所示。請按一下 \[新增\] 來新增項目，然後在 \[選擇使用者、電腦與群組\] 對話方塊按一下 \[進階\]。在展開的對話方塊按一下 \[立即尋找\]。在搜尋結果方塊選擇群組名稱，再按 \[確定\] 兩次。這時會出現 \[權限項目\] 對話方塊，您可於此選擇 \[存取權\] 與 \[適用於\] 項目來符合下表狀況。
  
        **Service Admins OU 的權限設定**

 
        <table style="border:1px solid black;">
        <colgroup>
        <col width="25%" />
        <col width="25%" />
        <col width="25%" />
        <col width="25%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th style="border:1px solid black;" >類別</th>
        <th style="border:1px solid black;" >名稱</th>
        <th style="border:1px solid black;" >存取權</th>
        <th style="border:1px solid black;" >適用於</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td style="border:1px solid black;">允許</td>
        <td style="border:1px solid black;">SYSTEM</td>
        <td style="border:1px solid black;">完全控制</td>
        <td style="border:1px solid black;">這項物件和所有子物件</td>
        </tr>
        <tr class="even">
        <td style="border:1px solid black;">允許</td>
        <td style="border:1px solid black;">Enterprise Admins</td>
        <td style="border:1px solid black;">完全控制</td>
        <td style="border:1px solid black;">這項物件和所有子物件</td>
        </tr>
        <tr class="odd">
        <td style="border:1px solid black;">允許</td>
        <td style="border:1px solid black;">Domain Admins</td>
        <td style="border:1px solid black;">完全控制</td>
        <td style="border:1px solid black;">這項物件和所有子物件</td>
        </tr>
        <tr class="even">
        <td style="border:1px solid black;">允許</td>
        <td style="border:1px solid black;">Administrators</td>
        <td style="border:1px solid black;">完全控制</td>
        <td style="border:1px solid black;">這項物件和所有子物件</td>
        </tr>
        <tr class="odd">
        <td style="border:1px solid black;">允許</td>
        <td style="border:1px solid black;">Windows 2000 前版相容性存取</td>
        <td style="border:1px solid black;">清單內容<br />
        讀取所有內容<br />
        讀取權限</td>
        <td style="border:1px solid black;">使用者物件</td>
        </tr>
        <tr class="even">
        <td style="border:1px solid black;">允許</td>
        <td style="border:1px solid black;">Windows 2000 前版相容性存取</td>
        <td style="border:1px solid black;">清單內容<br />
        讀取所有內容<br />
        讀取權限</td>
        <td style="border:1px solid black;">InetOrgPerson 物件</td>
        </tr>
        <tr class="odd">
        <td style="border:1px solid black;">允許</td>
        <td style="border:1px solid black;">Enterprise Domain Controllers</td>
        <td style="border:1px solid black;">清單內容<br />
        讀取所有內容<br />
        讀取權限</td>
        <td style="border:1px solid black;">這項物件和所有子物件</td>
        </tr>
        <tr class="even">
        <td style="border:1px solid black;">允許</td>
        <td style="border:1px solid black;">Authenticated Users</td>
        <td style="border:1px solid black;">清單內容<br />
        讀取所有內容<br />
        讀取權限</td>
        <td style="border:1px solid black;">這項物件和所有子物件</td>
        </tr>
        </tbody>
        </table>
  
#### 移動服務 Administrator 群組到「使用者與群組 OU」
  
將下列服務系統管理員群組從目前目錄的位置移動到您控制的樹狀子目錄的「使用者與群組 OU」：
  
-   Domain Admins 和任何巢狀子群組。
  
-   Enterprise Admins 和任何巢狀子群組。
  
-   Schema Admins 和任何巢狀子群組。
  
-   任何巢放在網域 Administrator、Server Operators、Backup Operators 或 Account Operators 群組的群組。
  
-   任何有委派權限可有效授權給其使用者服務系統管理員權限的群組。
  
不可將內建群組 (Administrators、Server Operators、Account Operators 與 Backup Operators)，從它們的預設容器移到受控制的樹狀子目錄。不過在 Windows Server 2003，內建群組依預設受到 AdminSDHolder 的保護。
  
如果您的組織沒有設定任何巢狀子目錄或將服務系統管理權限委派給任何群組，您就只需要移動 Domain Admins、Enterprise Admins 和 Schema Admins。
  
##### 需求
  
-   認證：Domain Admins
  
-   工具：Active Directory 使用者和電腦
  
<!-- -->
  
-   **若要將服務系統管理員群組移到「使用者與群組 OU」**
  
    1.  以 Domain Admins 群組成員登入，然後開啟「Active Directory 使用者和電腦」。
  
    2.  在主控台樹狀目錄中 (左窗格) 按一下 \[使用者\]。
  
    3.  在詳細資料窗格 (右窗格) 的 \[Domain Admins\] 按一下滑鼠右鍵，然後按一下 \[移動\]。
  
    4.  在 \[移動\] 方塊按兩下 \[Service Admins\]，按一下 \[Users and Grpous\]，再按一下 \[確定\]。
  
    5.  確認 Domain Admins 群組現在位於「使用者與群組 OU」。
  
        ![](images/Cc700835.sec_ad_admin_groups_18(zh-tw,TechNet.10).jpg)
  
    6.  在上列所有服務系統管理員群組重複這些程序。請注意，如果您在內建群組像是 Administrators，或您先前建立指派系統管理員權限的群組中有巢狀群組，它們的原本位置可能不是在 \[User\] 容器裡。
  
#### 移動 Service Administrator 使用者帳戶到「使用者與群組 OU」
  
將下列使用者帳戶從目前目錄的位置移動到您控制的樹狀子目錄的「使用者與群組 OU」：
  
-   列在「預設服務系統管理員群組和帳戶」表，是所有服務系統管理員群組成員的系統管理使用者帳戶。這包括網域 Administrator 帳戶 (您先前重新命名者)。
  
-   您在本指南前面程序中建立的誘餌系統管理員帳戶。
  
按照建議，每一個服務系統管理員應該有兩個帳戶：一個用在服務系統管理職責，另一個則用在資料管理和一般使用者存取。請將服務系統管理使用者帳戶，放置到您控制的樹狀子目錄的「使用者與群組 OU」。如果這些帳戶已經存在目錄中其他地方，請現在將它們移動到樹狀子目錄。那些系統管理員的一般使用者帳戶不應被放置到這個受控制的樹狀子目錄。一般使用者帳戶應該留在原本位置：在 \[User\] 容器或在您組織用來放使用者帳戶的 OU。
  
##### 需求
  
-   認證：Domain Admins
  
-   工具：Active Directory 使用者和電腦
  
<!-- -->
  
-   **若要將服務系統管理員帳戶移到使用者與群組 OU**
  
    1.  以 Domain Admins 群組成員登入，然後開啟「Active Directory 使用者和電腦」。
  
    2.  在主控台樹狀目錄中 (左窗格) 按一下 \[使用者\]。
  
    3.  在詳細資料窗格 (右窗格) 您重新命名的系統管理員帳戶的名稱，按一下滑鼠右鍵，再按一下 \[移動\]。
  
    4.  在 \[移動\] 方塊按兩下 \[Service Admins\]，按一下 \[Users and Grpous\]，再按一下 \[確定\]。
  
    5.  請確認帳戶現在是在「使用者與群組 OU」。
  
    6.  在上列所有服務系統管理員帳戶重複這些程序。請注意，如果您先前有建立系統管理員帳戶或其他 OU，它們的原本位置可能不是在 \[User\] 容器。
  
#### 將系統管理工作站帳戶移到 Admin 工作站 OU
  
請將系統管理員使用的工作站電腦帳戶移到 您控制的樹狀子目錄的 Admin Workstations OU。
  
**重要：**即使有些系統管理員會登入它們來執行管理工作，也請勿將任何網域控制站帳戶移出預設網域控制站 OU。移動這些帳戶會中斷網域控制站原則的持續應用，也沒有支援。
  
##### 需求
  
-   認證：Domain Admins
  
-   工具：Active Directory 使用者和電腦
  
<!-- -->
  
-   **若要將服務系統管理工作站帳戶移到 Admin Workstations OU**
  
    1.  以 Domain Admins 群組成員登入，然後開啟「Active Directory 使用者和電腦」。
  
    2.  在主控台樹狀目錄中 (左窗格) 按一下 \[電腦\]。
  
    3.  在詳細資料窗格 (右窗格) 系統管理員使用的工作站名稱按一下滑鼠右鍵，再按一下 \[移動\]。
  
    4.  在 \[移動\] 方塊按兩下 \[Service Admins\]，按一下 \[Admin Workstations\]，再按一下 \[確定\]。
  
    5.  請確認電腦帳戶現在是在「Admin Workstations OU」。
  
    6.  在所有系統管理工作站重複這些程序。
  
#### 啟用受控制的樹狀子目錄的稽核
  
稽核及追蹤服務系統管理員帳戶、工作站和原則的新增、刪除及變更，有助於識別不恰當或未授權的變更，這些經常是未授權而企圖存取您系統的行動指標。假設您已根據《Security Guide Kit (英文)》中的＜Securing Windows Server 2003 Domain Controllers (英文)＞的建議啟用您網域控制站的稽核，Service Admins OU 稽核的啟用會建立一個安全性稽核記錄來追蹤這些變更。監視安全性稽核記錄裡受控制的樹狀子目錄的變化，以及確認這些變化是否合法，皆有助於識別未經授權的使用。按一下 \[開始\] 來存取安全性稽核記錄，指向 \[系統管理工具\]，按一下 \[事件檢視器\]，再按一下 \[安全性\]。
  
##### 需求
  
-   認證：Domain Admins
  
-   工具：Active Directory 使用者和電腦
  
<!-- -->
  
-   **若要啟用受控制的樹狀子目錄的稽核**
  
    1.  以 Domain Admins 群組成員登入，然後開啟「Active Directory 使用者和電腦」。
  
    2.  在 \[檢視\] 功能表，選擇 \[進階功能\]。
  
    3.  在「Service Admins OU」按一下滑鼠右鍵，再按一下 \[內容\]。
  
    4.  在 \[安全性\] 索引標籤按一下 \[進階\]，然後選擇 \[稽核\] 索引標籤來檢視目前的 OU 稽核設定。請注意在這個例子裡，這兩個目前設定是從網域傳承下來。
  
        ![](images/Cc700835.sec_ad_admin_groups_19(zh-tw,TechNet.10).jpg)
  
    5.  按一下 \[新增\] 建立可應用於「Service Admins OU」和它的子 OU 的稽核項目。
  
    6.  在 \[輸入物件名稱以選取方塊\] 裡鍵入 **Everyone** ，再按一下 \[確定\]。
  
        ![](images/Cc700835.sec_ad_admin_groups_20(zh-tw,TechNet.10).jpg)
  
    7.  在 \[存取\] 方塊中如下表所示的存取項目選擇 \[成功\] 和 \[失敗\]，再按一下 \[確定\]。請注意在您選擇一些核取方塊時，會自動選擇其他存取項目。這些不可變更。
  
        ![](images/Cc700835.sec_ad_admin_groups_21(zh-tw,TechNet.10).jpg)
  
        **Service Admins OU 的稽核設定**

 
        <table style="border:1px solid black;">
        <colgroup>
        <col width="25%" />
        <col width="25%" />
        <col width="25%" />
        <col width="25%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th style="border:1px solid black;" >類別</th>
        <th style="border:1px solid black;" >名稱</th>
        <th style="border:1px solid black;" >存取權</th>
        <th style="border:1px solid black;" >適用於</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td style="border:1px solid black;">全部</td>
        <td style="border:1px solid black;">Everyone</td>
        <td style="border:1px solid black;">寫入所有內容</td>
        <td style="border:1px solid black;">這個物件和所有子物件</td>
        </tr>
        <tr class="even">
        <td style="border:1px solid black;">全部</td>
        <td style="border:1px solid black;">Everyone</td>
        <td style="border:1px solid black;">刪除</td>
        <td style="border:1px solid black;">這個物件和所有子物件</td>
        </tr>
        <tr class="odd">
        <td style="border:1px solid black;">全部</td>
        <td style="border:1px solid black;">Everyone</td>
        <td style="border:1px solid black;">刪除樹狀子目錄</td>
        <td style="border:1px solid black;">這個物件和所有子物件</td>
        </tr>
        <tr class="even">
        <td style="border:1px solid black;">全部</td>
        <td style="border:1px solid black;">Everyone</td>
        <td style="border:1px solid black;">修改權限</td>
        <td style="border:1px solid black;">這個物件和所有子物件</td>
        </tr>
        <tr class="odd">
        <td style="border:1px solid black;">全部</td>
        <td style="border:1px solid black;">Everyone</td>
        <td style="border:1px solid black;">修改擁有者</td>
        <td style="border:1px solid black;">這個物件和所有子物件</td>
        </tr>
        <tr class="even">
        <td style="border:1px solid black;">全部</td>
        <td style="border:1px solid black;">Everyone</td>
        <td style="border:1px solid black;">所有經過驗證的寫入</td>
        <td style="border:1px solid black;">這個物件和所有子物件</td>
        </tr>
        <tr class="odd">
        <td style="border:1px solid black;">全部</td>
        <td style="border:1px solid black;">Everyone</td>
        <td style="border:1px solid black;">所有延伸權利</td>
        <td style="border:1px solid black;">這個物件和所有子物件</td>
        </tr>
        <tr class="even">
        <td style="border:1px solid black;">全部</td>
        <td style="border:1px solid black;">Everyone</td>
        <td style="border:1px solid black;">建立所有子物件</td>
        <td style="border:1px solid black;">這個物件和所有子物件</td>
        </tr>
        <tr class="odd">
        <td style="border:1px solid black;">全部</td>
        <td style="border:1px solid black;">Everyone</td>
        <td style="border:1px solid black;">刪除所有子物件</td>
        <td style="border:1px solid black;">這個物件和所有子物件</td>
        </tr>
        </tbody>
        </table>
  
[](#mainsection)[回到頁首](#mainsection)
  
### 建立最佳的系統管理帳戶與群組實務
  
建立以下最佳實務，以使用系統管理帳戶與群組，有助於降低未授權使用者提升存取權限存取您的電腦及網路，或合法使用者因認識不全誤用他們的系統管理員權限，而意外中斷您網路的可能性：
  
-   限制服務系統管理員帳戶的數目
  
-   將系統管理使用者分為系統管理及使用者兩種帳戶
  
-   指派可信度高的人員
  
-   將系統管理員權限侷限於實際需求的權限
  
-   控制系統管理登入程序
  
-   保障服務系統管理員工作站
  
-   了解資料的委派
  
#### 限制服務系統管理員帳戶的數目
  
將服務系統管理員帳戶的成員資格保持在支援您組織所需的絕對最小值，是限制未授權使用的關鍵方法。對小型組織而言，一般有兩個 Domain Admins 成員的帳戶已足夠。限制這些成員資格可降低可能遭惡意使用者修改的系統管理帳戶數目。由服務系統管理員執行的工作應該限於變更 Acitve Directory 服務設定及重新設定網域控制站。
  
不要使用系統管理員帳戶處理日常系統管理工作，例如帳戶及成員伺服器管理，而要使用一般使用者帳戶。
  
若要使用一般使用者帳戶進行帳戶及成員伺服器管理，您可把要管理的物件放置在分開的 OU，再使您的一般使用者帳戶成為有權限處理那個 OU 的群組成員。
  
執行下列步驟需要 Domain Admins 認證：
  
1.  在網域樹狀目錄底下建立一個 OU 名稱為 \[資料\]。使用這個 OU 放置所有要由資料系統管理員管理的物件，例如一般使用者、它們的工作站及成員伺服器。
  
    **注意：** 您也可能至少要在「資料 OU」建立兩個 OU，一個名稱為「使用者」，而另一個名稱為「電腦」，然後將所有使用者和電腦帳戶從使用者和電腦容器移動到這些個別的 OU。將這些物件移到 OU 可讓您可運用群組原則。您也可建立您自己的 OU 模式以因應您對委派及群組原則應用的需求。
  
2.  在網域根目錄之下建立另一個 OU 名稱為 \[Data Admins\]。
  
3.  在 \[Data Admins\] OU 建立一個「網域本機安全性群組」，名稱取為 ***domain\_name*Data Admins** ，例如 Contoso Data Admins。這個群組的成員負責管理在「資料 OU」的資料。
  
4.  請按照下面在「資料 OU」修改現存的權限：
  
    -   移除所有授與 Account Operators 和 Print Operators 的權限。
  
    -   新增下列項目：

 
        <table style="border:1px solid black;">
        <colgroup>
        <col width="25%" />
        <col width="25%" />
        <col width="25%" />
        <col width="25%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th style="border:1px solid black;" >類別</th>
        <th style="border:1px solid black;" >名稱</th>
        <th style="border:1px solid black;" >存取權</th>
        <th style="border:1px solid black;" >適用於</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td style="border:1px solid black;">允許</td>
        <td style="border:1px solid black;">Data Admins</td>
        <td style="border:1px solid black;">完全控制</td>
        <td style="border:1px solid black;">這個物件和所有子物件</td>
        </tr>
        </tbody>
        </table>
  
5.  移除您為「資料 OU」網域系統管理員建立的一般使用者帳戶。
  
6.  新增這個帳戶到 ***domain\_name*Data Admins** 安全性群組。
  
7.  如果您稍後要委派資料管理給額外的系統管理員，請在「Data Admins OU」建立它們的使用者帳戶，並新增它們的使用者帳戶到 ***domain\_name*** **Data Admins** 安全性群組。
  
#### 將系統管理使用者的 Administrator 帳戶和使用者帳戶分開
  
為每一個擔任服務管理員角色的使用者建立兩個帳戶：一個是用在常態工作和資料管理的一般使用者帳戶，另一個是只用在執行服務系統管理工作的服務系統管理帳戶。服務系統管理帳戶不該有郵件功能或用來執行日常使用的應用程式，例如 Microsoft Office 或瀏覽網際網路。這兩個帳戶的密碼要永遠不同。這些預防措施可減少帳戶曝露到外界，也減少系統管理帳戶登入系統的時間。
  
#### 指派可信度高的人員
  
服務系統管理人員控制設定及目錄服務的運作。因此這個責任應該只給已展現負責的擁有權，也了解目錄操作的穩當可靠的使用者。他們應完全熟悉您組織的安全性及操作原則，並已表示願意加強那些原則。
  
#### 系統管理員權限只限於實際需要的權限
  
Active Directory 含有 Backup Operators 內建群組。這個群組的成員被視為服務系統管理員，因為這個群組的成員在網域控制站有特殊權限可本機登入及還原檔案，包括作業系統檔案。Active Directory 的 Backup Operator 群組成員資格，應該限於備份及還原網域控制站的個人。
  
所有成員伺服器也含有區域性的 Backup Operators 內建群組。負責在一個成員伺服器 (例如 Microsoft SQL Server) 備份應用程式的個人應該成為那個伺服器的本機 Backup Operators 群組成員。這些使用者不應該是 Active Directory 的 Backup Operators 群組成員。
  
在一個網域控制站專用的伺服器中，您可減低 Backup Operators 群組的成員數目。如果可能，應該有專用的網域控制站，但是在小型組織裡網域控制站可能也被用來執行其他應用程式。在這樣的情況下，就必須將服務系統管理員的責任託給負責在網域控制站備份應用程式的使用者，因為他們有特殊權限可在網域控制站還原檔案，包括系統檔案。
  
避免將 Account Operators 群組用在嚴格的委派「資料管理」工作，例如帳戶管理。預設目錄權限賦予這個群組修改、甚至刪除網域控制站的電腦帳戶的能力。依預設，Account Operators 群組沒有成員，且它的成員資格維持空白。
  
#### 控制系統管理登入程序
  
Administrators、Enterprise Admins 和 Domain Admins 群組的成員代表您網域最有權力的帳戶。為了將安全性風險降到最低，您可能要採取額外的步驟加強系統管理認證，例如要求以智慧卡做系統管理登入，或要求兩種分別由不同系統管理員持有的識別。這些額外的預防措施記載於《[Best Practice Guide for Securing Active Directory Installations (英文)](http://go.microsoft.com/fwlink/?linkid=22342)》(Windows Server 2003)，位於 Microsoft 網站 [http://go.microsoft.com/fwlink/?LinkId=22342](http://go.microsoft.com/fwlink/?linkid=22342)。
  
#### 保障服務系統管理員工作站
  
除了限制存取儲存於網域控制站的資源，您也可嚴格控制服務系統管理員用在系統管理的工作站來加強安全性。服務系統管理員應該只登入到管理良好的電腦，即是已套用所有安全性更新程式及安裝最新的防毒程式的電腦。如果您在管理不良的電腦使用服務系統管理員認證，萬一那台電腦遭到惡意人士的入侵，您就冒著洩漏認證資料的風險。
  
如需更多有關如何限制系統管理員只到特定工作站及額外預防措施，請參閱《[Best Practice Guide for Securing Active Directory Installations (英文)](http://go.microsoft.com/fwlink/?linkid=22342)》(Windows Server 2003)，位於如下 Microsoft 網站 [http://go.microsoft.com/fwlink/?LinkId=22342](http://go.microsoft.com/fwlink/?linkid=22342)。
  
#### 了解資料的委派
  
小型組織可能只有一兩位系統管理使用者，所以可不需要資料委派。不過隨著您組織的成長，您可能需要指定系統管理員及委派部分的資料管理給他們。資料系統管理員負責管理存在目錄及網域成員電腦的資料。資料系統管理員在設定及傳送目錄服務沒有控制權，只控制目錄裡的物件子集合。利用對目錄物件的權限，可將系統管理員帳戶控制權限制在目錄的特定區域。資料系統管理員也管理他們網域的成員電腦 (網域控制站以外)。他們管理本機資源，例如本機伺服器的印表機及檔案共用，而且他們也管理自己本身的群組及使用者帳戶。資料系統管理員能從管理工作站執行他們的所有責任，並且他們不需要實體存取網域控制站。
  
建立群組、授與這些群組恰當的使用者權限及將群組原則設定套用到這些群組成員，即可完成資料管理的委派。在這些步驟完成後，委派工作就只剩下新增使用者帳戶到建立的群組。這項操作的關鍵部分是基於最低特殊權限的原則來授與恰當存取權及套用恰當的原則，以將安全性提到最高，另一方面仍然允許系統管理員執行他們被委派的功能。
  
如需更多有關委派資料管理的資訊，請參閱《[Best Practices for Delegating Active Directory Administration (英文)](http://go.microsoft.com/fwlink/?linkid=22707)》，位於 Microsoft 網站 [http://go.microsoft.com/fwlink/?LinkId=22707](http://go.microsoft.com/fwlink/?linkid=22707)。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 相關資訊
  
-   如需關於確保 Active Directory 安全的詳細資訊，請參閱：
  
-   《Security Guide Kit (英文)》中的＜Securing Windows Server 2003 Domain Controllers＞。
  
-   《[Best Practice Guide for Securing Active Directory Installations (英文)](http://go.microsoft.com/fwlink/?linkid=22342)》(Windows Server 2003)，位於 Microsoft 網站 [http://go.microsoft.com/fwlink/?LinkId=22342](http://go.microsoft.com/fwlink/?linkid=22342)。
  
-   《[Best Practices for Delegating Active Directory Administration (英文)](http://go.microsoft.com/fwlink/?linkid=22707)，位於 Microsoft 網站 [http://go.microsoft.com/fwlink/?LinkId=22707](http://go.microsoft.com/fwlink/?linkid=22707)。
  
如需關於內建帳戶及從 Microsoft® Windows NT® 4.0 移轉到 Active Directory 的詳細資訊，請參閱：
  
-   《[Default Groups (英文)](http://go.microsoft.com/fwlink/?linkid=22706)》，位於 TechNet 網站 [http://go.microsoft.com/fwlink/?LinkId=22706](http://go.microsoft.com/fwlink/?linkid=22706)。
  
-   《[Migrating from Windows NT Server 4.0 to Windows Server 2003 (英文)](http://go.microsoft.com/fwlink/?linkid=22709)》，位於 Microsoft 網站 [http://go.microsoft.com/fwlink/?LinkId=22709](http://go.microsoft.com/fwlink/?linkid=22709)。
  
[](#mainsection)[回到頁首](#mainsection)
