---
TOCTitle: '第 2 章：設定 Active Directory 網域基礎結構'
Title: '第 2 章：設定 Active Directory 網域基礎結構'
ms:assetid: '620c0004-41a8-4d13-9a61-e6d879f9cc65'
ms:contentKeyID: 20214561
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc163071(v=TechNet.10)'
---

Windows XP 安全性指南
=====================

### 第 2 章：設定 Active Directory 網域基礎結構

更新日期: 2006 年 7 月 26 日

##### 本頁內容

[](#elaa)[概觀](#elaa)
[](#ekaa)[支援安全性管理的 OU 設計](#ekaa)
[](#ejaa)[支援安全性管理的 GPO 設計](#ejaa)
[](#eiaa)[網域層級的群組原則](#eiaa)
[](#ehaa)[密碼原則設定](#ehaa)
[](#egaa)[帳戶鎖定原則設定](#egaa)
[](#efaa)[使用者權限指派設定](#efaa)
[](#eeaa)[安全性選項設定](#eeaa)
[](#edaa)[Kerberos 原則](#edaa)
[](#ecaa)[OU 層級的群組原則](#ecaa)
[](#ebaa)[群組原則工具](#ebaa)
[](#eaaa)[總結](#eaaa)

### 概觀

群組原則是 Active Directory® 目錄服務的一項功能，可協助 Microsoft® Windows Server™ 2003 和 Microsoft Windows® 2000 Server 網域的變更與設定管理。然而，在您將群組原則套用至環境中的 Microsoft Windows XP Professional Service Pack 2 (SP2) 用戶端電腦之前，需要先在網域中執行特定的預備步驟。

群組原則設定存放在 Active Directory 資料庫的群組原則物件 (GPO) 中。GPO 與包含 Active Directory 站台、網域和組織單位 (OU) 的容器相連結。由於群組原則與 Active Directory 的整合相當緊密，因此在您實作群組原則之前，必須先瞭解 Active Directory 結構，以及不同的設計設定選項對於安全性所具有的涵義。如需更多關於 Active Directory 設計的資訊，請參閱《Windows Server 2003 安全性指南》第 3 章＜網域原則＞。

「群組原則」是保障 Windows XP 安全之不可或缺的工具。本章詳細說明如何從中央位置使用群組原則，以套用和維護整個網路一致的安全性原則。

本指南針對企業用戶端 (EC) 和專業安全性限制功能 (SSLF) 等兩種環境提供選項。本章建議的設定同時適用於桌上型和膝上型用戶端電腦，而由於這些設定屬於特殊情況，因此是套用在網域根目錄層級，而非 OU 層級。例如，Windows Server 2003 和 Windows 2000 Server 網域的密碼及帳戶鎖定原則，必須透過與該網域連結的 GPO 來設定。供兩種不同環境使用的基準線安全性範本檔案名稱如下：

-   EC-Domain.inf

-   SSLF-Domain.inf

[](#mainsection)[回到頁首](#mainsection)

### 支援安全性管理的 OU 設計

OU 是 Active Directory 網域當中的一個容器。OU 可能包括使用者、群組、電腦和其他 OU，即所謂的子 OU。您可以將 GPO 與 OU 連結，如此 GPO 設定便會套用到該 OU 及其子 OU 中所含的使用者和電腦。您可以委派系統管理授權給 OU 以方便管理。OU 不僅提供簡單的分類方法來區分使用者、電腦和其他安全性主體，也提供一種區隔系統管理界限的有效方法。Microsoft 建議組織應將使用者和電腦指派到不同的 OU，因為有些設定只能套用到使用者，而有些只能套用到電腦。

您可以使用 Microsoft Management Console (MMC) Active Directory 使用者和電腦嵌入式管理單元工具中的「委派精靈」，來委派對群組或個別 OU 的控制權。請參閱本章最後的＜其他資訊＞一節，即可連結至有關委派授權的說明文件。

OU 結構設計的主要目標，在於提供銜接無瑕的群組原則實作基礎，使其順利套用到 Active Directory 中所有的工作站，同時確保這些工作站符合貴組織的安全性標準。另外，OU 結構的設計必須針對組織內的特定使用者類型，提供適合的安全性設定。例如，准許開發人員在他們的工作站上進行一般使用者無權進行的工作。此外，膝上型電腦使用者的安全性需求，也可能會與桌上型電腦使用者略有差異。下圖繪示的簡單 OU 結構，足以因應本章所探討的群組原則。此 OU 的結構可能與您環境中的組織需求不太一樣。

![](images/Cc163071.XPSG0201(zh-tw,TechNet.10).gif)

**圖 2.1 Windows XP 電腦的 OU 結構**

#### 部門 OU

由於組織內部的安全性需求變化不定，您可能需要在環境中建立部門 OU。部門安全性設定可透過 GPO 套用到對應的部門 OU 中的電腦和使用者。

##### 安全的 XP 使用者 OU

此 OU 包含同時使用於 EC 和 SSLF 環境的使用者帳戶。套用到此 OU 的設定在第 4 章＜Windows XP 的系統管理範本＞的＜使用者設定＞一節中有探討。

##### Windows XP OU

此 OU 包含您環境中的各種 Windows XP 用戶端電腦的子 OU。本指南將針對桌上型和膝上型電腦進行說明。因此建立了「桌上型電腦 OU」和「膝上型電腦 OU」。

-   **桌上型電腦 OU**： 此 OU 包含與您的網路經常保持連線的桌上型電腦。套用到此 OU 的設定在第 3 章＜Windows XP 用戶端的安全性設定＞和第 4 章＜Windows XP 的系統管理範本＞中有詳細探討。

-   **膝上型電腦 OU**： 此 OU 包含不會與您的網路始終保持連線之行動使用者的膝上型電腦。第 3 章＜Windows XP 用戶端的安全性設定＞和第 4 章＜Windows XP 的系統管理範本＞將詳細探討套用到此 OU 的設定。

[](#mainsection)[回到頁首](#mainsection)

### 支援安全性管理的 GPO 設計

使用 GPO 讓特定原則設定、使用者權限和行為確實套用到 OU 中所有工作站和使用者。使用群組原則來替代手動設定，可於日後遇到其他變更時，輕鬆更新多個工作站或使用者。手動設定需要技術人員親自走訪每一台用戶端電腦，缺乏效率。此外，倘若以網域為主的 GPO 原則設定不同於在本機上套用的設定，則以網域為主的 GPO 原則設定將會覆寫在本機上套用的原則設定。

[![](images/Cc163071.XPSG0202(zh-tw,TechNet.10).gif)](https://technet.microsoft.com/zh-tw/cc163071.xpsg0202_big(zh-tw,technet.10).gif)

**圖 2.2 GPO 套用順序**

此圖從最低 (1) 到最高 (5)，依序顯示套用 GPO 至屬於子 OU 成員的電腦之順序。群組原則會先從每個 Windows XP 工作站的本機原則開始套用。在套用本機原則之後，接著會套用站台層級的所有 GPO，然後是網域層級。

對於以巢狀方式放置在數個 OU 層的 Windows XP 用戶端電腦而言，GPO 會從最高的 OU 層級開始套用，並依序套用到最低層級。最後一個 GPO 會從包含用戶端電腦的 OU 進行套用。這種從本機原則、站台、網域、父 OU 到子 OU 的 GPO 處理順序非常重要，因為在處理過程中較晚套用的 GPO 會覆寫先前套用的 GPO。使用者 GPO 也是以相同的方式套用。

在設計群組原則時，請考量下列事項。

-   系統管理員必須設定您連結多個 GPO 與 OU 的順序，否則將依照 GPO 與 OU 連結的預設順序套用原則。如果在多個原則中設定相同的設定，會優先採用該容器的原則清單中最高的原則。

-   您可以使用 \[已強制\] 選項來設定 GPO。如果您選取此選項，其他 GPO 則無法覆寫設定在此 GPO 中的設定。

    **注意：**在 Windows 2000 中，\[已強制\] 選項稱為 \[不可強制覆蓋\] 選項。

-   您可以使用 \[不要繼承原則\] 選項來設定 Active Directory、站台、網域或 OU。此選項會封鎖位於 Active Directory 較高階層的 GPO 之 GPO 設定，除非事先選取 \[已強制\] 選項。換句話說，\[已強制\] 選項的優先性高於 \[不要繼承原則\] 選項。

-   群組原則設定係套用到使用者和電腦，並且是根據使用者或電腦物件在 Active Directory 中的位置加以套用。在某些情況下，使用者物件可能需要根據電腦物件的位置來套用原則，而不是根據使用者物件的位置。群組原則回送功能讓系統管理員能夠根據使用者所登入的電腦來套用使用者群組原則設定。如需更多關於回送支援的資訊，請參閱本章結尾的＜其他資訊＞一節中收錄的「群組原則白皮書」。

下圖將初步的 OU 結構展開，以顯示如何能將 GPO 套用到屬於膝上型電腦 OU 和桌上型電腦 OU 的 Windows XP 用戶端電腦。

[![](images/Cc163071.XPSG0203(zh-tw,TechNet.10).gif)](https://technet.microsoft.com/zh-tw/cc163071.xpsg0203_big(zh-tw,technet.10).gif)

**圖 2.3 展開後的 OU 結構以容納 Windows XP 桌上型和膝上型電腦**

在前述範例中，膝上型電腦是「膝上型電腦 OU」的成員。第一個套用的原則是膝上型電腦上的本機安全性原則。由於在此範例中只有一個站台，因此站台層級未套用任何 GPO，故「網域 GPO」依序成為下一個套用的原則。最後套用「膝上型電腦 GPO」。

**注意：**由於桌上型電腦原則並未套用到任何膝上型電腦，因為它未連結到含有「膝上型電腦 OU」的階層內之任何 OU。此外，「安全的 XP 使用者 OU」沒有相對應的安全性範本 (.inf 檔)，因為它只含有系統管理範本的設定。

為顯示優先順序如何運作，在此假設一個範例案例，其中 \[允許透過終端機服務登入\] 的 Windows XP OU 原則設定套用到 **Administrators** 群組，而 \[允許透過終端機服務登入\] 的膝上型電腦 GPO 設定套用到 **Power Users** 和 **Administrators** 群組。在此範例中，帳戶屬於 **Power Users** 群組的使用者可透過「終端機服務」登入到膝上型電腦，因為膝上型電腦 OU 是 Windows XP OU 的子項。如果啟用 Windows XP GPO 中的 \[不可強制覆蓋\] 選項，則只有其帳戶屬於 **Administrators** 群組的人才能透過終端機服務登入用戶端電腦。

#### 安全性範本

安全性範本是包含安全性設定值的文字檔案。這類範本是 GPO 的子元件，其中所含的原則設定可以透過 MMC 群組原則物件編輯器嵌入式管理單元加以修改；安全性範本位於電腦設定\\Windows 設定\\安全性設定的資料夾下。您也以使用 MMC 安全性範本嵌入式管理單元或記事本之類的文字編輯器來修改這些檔案。Microsoft 建議您使用群組原則物件編輯器嵌入式管理單元來管理 GPO 中安全性範本的原則設定，而使用安全性範本嵌入式管理單元來管理獨立安全性範本中的原則設定。

範本檔案的某些部分包含特定的存取控制清單 (ACL)，其係由 Security Descriptor Definition Language (SDDL) 所定義。如需瞭解如何編輯安全性範本和 SDDL，請參閱本章結尾的＜其他資訊＞一節。

##### 安全性範本管理

請務必將生產環境的安全性範本存放於基礎結構中的安全位置。並限制只有負責實作群組原則的系統管理員有權存取安全性範本。Windows XP、Windows 2000 和 Windows Server 2003 內含的安全性範本預設存放在 **%SystemRoot%\\security\\templates** 資料夾中。如第 1 章所述，當您從本指南所附的 WinZip 保存檔執行 .msi 檔案時，本指南中收錄的安全性範本會被複製到 **\\Windows XP Security Guide Tools and Templates\\Security Templates** 資料夾中。(本指南的下載版本可從 http://go.microsoft.com/fwlink/?LinkId=14840 取得。) 您可能需要將安全性範本從該資料夾複製或移動到測試電腦上的新位置，以便針對貴組織的商業需求進行評估和細部調整。測試完成後，應將該安全性範本的最終版本移放到集中的位置，例如內建安全性範本的預設位置。

**% SystemRoot %\\security\\templates** 資料夾不會在跨網域控制站之間複寫。因此，您需要選擇一個網域控制站來保存安全性範本的主複本，這樣一來就不會碰到範本的版本控制問題。這個最佳作法可確保您修改的永遠都是範本的相同版本。

##### 匯入安全性範本

依下列程序執行步驟，以匯入安全性範本。

**將安全性範本匯入 GPO：**

1.  瀏覽至「群組原則物件編輯器」中的 \[Windows 設定\] 資料夾。

2.  展開 \[Windows 設定\] 資料夾並選取 \[安全性設定\]。

3.  以滑鼠右鍵按一下 \[安全性設定\] 資料夾，再按 \[匯入原則...\]。

4.  選取您要匯入的安全性範本，再按一下 \[開啟\]。該檔案中的設定便會匯入到 GPO 中。

#### 系統管理範本

名為「系統管理範本」的 Unicode 檔案中提供額外的安全性設定。這些檔案中所含的登錄設定，會影響 Windows XP 和其元件，以及其他應用程式如 Microsoft Office 2003。系統管理範本可同時包含電腦設定和使用者設定。電腦設定存放在 HKEY\_LOCAL\_MACHINE 登錄 Hive 中。使用者設定存放在 HKEY\_CURRENT\_USER 登錄 Hive 中。

##### 管理系統管理範本

如同安全性範本須存放在安全位置，生產環境中所使用的系統管理範本也必須儲存在基礎結構下的安全位置。只有負責實作群組原則的系統管理員有權存取該位置。Windows XP 和 Windows Server 2003 隨附的系統管理範本乃存放在 **%systemroot%\\inf** 目錄中。Office 2003 的其他範本則收錄在 *Office 2003 Resource Kit* 中。不可編輯由 Microsoft 提供的系統管理範本，因為它們可能會在 Service Pack 發行時有所變更。

##### 新增系統管理範本到原則中

除了 Windows XP 隨附的系統管理範本之外，您可能需要將 Office 2003 範本套用到 GPO，以便設定其中的 Office 2003 設定。或者，您可能已為貴組織建立了獨特的自訂系統管理範本。請依照下列程序，將系統管理範本新增到 GPO 中。

**新增系統管理範本到 GPO：**

1.  瀏覽至「群組原則物件編輯器」中的 \[系統管理範本\] 資料夾。

2.  以滑鼠右鍵按一下 \[系統管理範本\] 資料夾，並按 \[新增/移除範本\]。

3.  在 \[新增/移除範本\] 對話方塊中，按一下 \[新增\]。

4.  瀏覽至含有您的系統管理範本檔案的資料夾。

5.  選取您要新增的範本，按一下 \[開啟\]，然後按 \[關閉\]。

[](#mainsection)[回到頁首](#mainsection)

### 網域層級的群組原則

網域層級的群組原則包含套用到網域內所有電腦和使用者的設定。本指南建議您在新的 GPO 中設定網域層級設定，而不要在內建預設網域原則中進行設定。這項建議的理由在於，萬一本指南所述的變更導致問題發生時，此種設定方式能夠方便您還原預設設定。值得注意的是，某些應用程式會自動設定預設網域原則，而由該等應用程式所變更的原則設定，可能會與本指南中所述的網域原則 GPO 中定義的設定相衝突。不過，發生衝突的風險並不大，因為只是少部分設定在網域層級的設定。關於網域層級安全性的詳細探討，詳見 [*Windows Server 2003 安全性指南*](http://go.microsoft.com/fwlink/?linkid=14845)第 3 章＜網域原則＞，網址是：http://go.microsoft.com/fwlink/?LinkId=14845。

[](#mainsection)[回到頁首](#mainsection)

### 密碼原則設定

定期變更複雜密碼可降低密碼攻擊成功的可能性。密碼原則設定係控制密碼的複雜性和生命週期，並且只能透過群組原則設定在網域層級。如需瞭解如何在獨立電腦上的本機安全性帳戶管理員 (SAM) 中直接設定密碼原則，請參閱第 5 章＜保護獨立 Windows XP 用戶端的安全＞。

本節探討適用於 EC 和 SSLF 環境的各項密碼原則設定。

您可以在「群組原則物件編輯器」中的下列位置設定密碼原則設定：

**電腦設定\\Windows 設定\\安全性設定\\帳戶原則\\密碼原則**

下表歸納出針對本指南中定義的兩種安全環境提出的密碼原則設定建議。以下各節將提供更多關於各個設定的詳細資訊。

**表 2.1 密碼原則設定建議**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >設定</th>
<th style="border:1px solid black;" >網域控制站預設值</th>
<th style="border:1px solid black;" >EC</th>
<th style="border:1px solid black;" >SSLF</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">強制執行密碼歷程記錄</td>
<td style="border:1px solid black;">24 組密碼</td>
<td style="border:1px solid black;">24 組密碼</td>
<td style="border:1px solid black;">24 組密碼</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">密碼最長有效期</td>
<td style="border:1px solid black;">42 天</td>
<td style="border:1px solid black;">90 天</td>
<td style="border:1px solid black;">90 天</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">密碼最短有效期</td>
<td style="border:1px solid black;">1 天</td>
<td style="border:1px solid black;">1 天</td>
<td style="border:1px solid black;">1 天</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">最小密碼長度</td>
<td style="border:1px solid black;">7 個字元</td>
<td style="border:1px solid black;">8 個字元</td>
<td style="border:1px solid black;">12 個字元</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">密碼必須符合複雜性需求</td>
<td style="border:1px solid black;">已啟用</td>
<td style="border:1px solid black;">已啟用</td>
<td style="border:1px solid black;">已啟用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">使用可還原的加密來存放網域中所有使用者的密碼</td>
<td style="border:1px solid black;">已停用</td>
<td style="border:1px solid black;">已停用</td>
<td style="border:1px solid black;">已停用</td>
</tr>
</tbody>
</table>
  
#### 強制執行密碼歷程記錄
  
此原則設定係決定唯一新密碼的數目，該唯一新密碼必須與使用者帳戶建立關聯後，舊密碼才能重複使用。此原則設定的值必須介於 0 到 24 組密碼。Windows XP 的預設值為 0 組密碼，但網域的預設值則為 24 組密碼。為維護此原則設定的有效性，請使用 \[密碼最短有效期\] 設定，以防使用者重複變更其密碼。
  
請針對本指南中定義的兩種安全性環境，將 \[強制執行密碼歷程記錄\] 設定設為 \[24 組密碼\]。
  
#### 密碼最長有效期
  
此原則設定的值範圍介於 1 至 999 天。(您也可以將此值設定為 0，讓密碼永不過期。) 此原則設定係定義使用者可以使用密碼的期限。此原則設定的預設值為 42 天。大多數的密碼都可以破解，因此密碼變更得越頻繁，攻擊者破解密碼並竊用的機會就越小。不過，此值設得越小，相關服務支援要求的次數就越多。
  
請針對本指南中定義的兩種安全性環境，將 \[密碼最長有效期\] 設定設為 \[90 天\]。
  
#### 密碼最短有效期
  
此原則設定係決定密碼必須使用的天數，使用者需待此期限過後才能變更密碼。此原則設定值的範圍為 1 到 998 天。(您也可以將此值設定為 0，允許使用者立即變更密碼。) 此原則設定的預設值是 0 天。
  
\[密碼最短有效期\] 設定的值必須小於 \[密碼最長有效期\] 設定的值，除非 \[密碼最長有效期\] 設定值為 0，讓密碼永遠不會過期。如果 \[密碼最長有效期\] 設定的值設為 0，此原則設定的值即可設為 0 至 999 之間的任意值。
  
如果想要讓 \[強制執行密碼歷程記錄\] 設定生效，請將此值設為大於 0。如果 \[密碼最短有效期\] 設定值是 0，使用者即可重複循環使用密碼，以重複使用自己最喜歡的舊密碼。
  
請針對本指南中定義的兩種安全性環境，將 \[密碼最短有效期\] 設定值設為 1 天。此設定值可避免使用者重複使用相同的密碼，因為使用者必須等過了一天之後才能變更密碼。再者，也鼓勵使用者記住新密碼，因為他們必須使用至少一天才能重設。此外，如此設定能讓使用者無法規避 \[強制執行密碼歷程記錄\] 設定的限制。
  
#### 最小密碼長度
  
此原則設定係決定構成使用者帳戶密碼的最小字元數。對於如何為組織訂定最佳密碼長度的理論眾說紛紜，但或許「通關密語」的說法好過「密碼」。在 Microsoft Windows 2000 和較新的版本中，通關密語的長度可以很長，並且包含空格。因此，諸如 "I want to drink a $5 milkshake" 的短句會是有效的通關密語，比由隨機數字和字母組成的 8 或 10 個字元的字串更為牢靠，而且更容易記憶。重要的是讓使用者懂得妥善挑選和維護密碼，尤其須注意密碼的長度。
  
在 EC 環境中，務必將 \[最小密碼長度\] 設定的值設為 \[8 個字元\]。此原則設定的長度足以提供充分的安全性，同時又不算長到讓使用者難以記住的地步。在 SSLF 環境中，請將值設為 \[12個字元\]。
  
#### 密碼必須符合複雜性需求
  
此原則設定會檢查所有的新密碼，以確保其符合強式密碼的基本要求。此原則設定的值在 Windows XP 中預設為 \[已停用\]，但是在 Windows Server 2003 網域中設定為 \[已啟用\]。
  
密碼中每多增加一個字元，便會提高其複雜程度。例如，七個字元全部為小寫英文字母的密碼具有 267 (約 8 x 109 或 80 億) 種可能的組合。以每秒嘗試 1 百萬次 (多數密碼破解公用程式的能力) 來算，只需要 133 分鐘即可破解。七個字元且區分大小寫的英文字母密碼共有 527 種組合。七個字元、區分大小寫但不含標點符號的英數密碼共有 627 種組合。八個字元的密碼共有 268 (或 2 x 1011) 種可能的組合方式。雖然這個數字看似驚人，但是以每秒 1 百萬次嘗試來算，只需要 59 個小時即可跑完所有可能的密碼。請記住，這些嘗試時間會隨著使用 ALT 字元和其他特別鍵盤字元 (例如 ! 或 @) 而大幅增加。
  
適當使用密碼設定雖無法完全遏阻暴力攻擊，但可增加其困難度。
  
#### 使用可還原的加密來存放網域中所有使用者的密碼
  
此原則設定係決定作業系統是否以可還原的加密方式來儲存密碼，藉此支援需透過使用者密碼以供驗證的應用程式通訊協定。以可還原的加密方式儲存的密碼，基本上與純文字版的密碼相同。基於此原因，除非應用程式需求比保護密碼資訊還重要，否則切勿啟用此原則。此原則設定的預設值為 \[已停用\]。
  
在透過遠端存取或 Internet Authentication Service (IAS) 使用 Challenge-Handshake 驗證通訊協定 (CHAP) 時，必須啟用此原則設定。在 Microsoft Internet Information Services (IIS) 中使用「摘要式驗證」時，也需要用到此原則。
  
請確定 \[使用可還原的加密來存放網域中所有使用者的密碼\] 設定設為 \[已停用\]，亦即在 Windows Server 2003 的預設網域 GPO 和本機安全性原則中針對工作站和伺服器所作的設定。在本指南定義的兩種環境中，亦將此原則設定設為 \[已停用\]。
  
#### 防止使用者在非必要時變更密碼
  
除了本章稍早所述的密碼原則外，某些組織還必須對所有的使用者進行集中控管。本節將說明如何防止使用者在非必要時變更他們的密碼。
  
集中控管使用者密碼是精心設計之 Windows XP 安全性配置的基石。您可以使用「群組原則」來設定先前探討的密碼最短及最長使用期限。然而，使用者可藉由頻繁的密碼變更要求來規避您環境中的 \[強制執行密碼歷程記錄\] 設定。要求使用過長的密碼，也可能會因使用者忘記密碼而導致服務支援要求的數量增加。
  
使用者可以在密碼最短和最長使用期限設定的期間內變更他們的密碼。然而，在專業安全性限制功能環境安全性的設計下，使用者只能在密碼到達 42 天的最長使用期限後，經由作業系統提示才能變密碼。為達到此控制層級，系統管理員可按下 CTRL+ALT+DELETE 鍵，在畫面顯示的 \[Windows 安全性\] 對話方塊中停用 \[變更密碼...\] 按鈕。
  
您可以使用群組原則，針對整個網域實作此項設定，或藉由編輯登錄而針對一或多個特定使用者來實作此設定。如需關於此項設定的詳細資訊，請參閱 Microsoft 知識庫文件編號 324744 [如何防止使用者於非必要的情況下在 Windows Server 2003 變更密碼](http://support.microsoft.com/default.aspx?scid=324744) (英文)，網址是：http://support.microsoft.com/default.aspx?scid=324744。如果是 Windows 2000 網域，請參閱 Microsoft 知識庫文件編號 309799 [如何防止使用者於非必要的情況下在 Windows Server 2003 變更密碼](http://support.microsoft.com/default.aspx?scid=309799) (英文)，網址是：http://support.microsoft.com/default.aspx?scid=309799。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 帳戶鎖定原則設定
  
帳戶鎖定原則是一種 Active Directory 安全性功能，其會在指定期間內達到指定的嘗試登入失敗次數後，鎖定使用者帳戶並禁止登入。登入嘗試次數是由網域控制站追蹤。允許的嘗試次數和期間是以帳戶鎖定設定的設定值而定。亦可指定鎖定的持續時間。
  
這些原則設定可幫助防止攻擊者猜測使用者密碼，而且它們也降低了成功攻擊您網路環境的可能性。然而，啟用帳戶鎖定原則可能會造成網路使用者的支援需求增加。在您啟用下列設定以前，請確定貴組織是否願意承擔此額外的管理負荷。對於許多組織而言，經過改良且成本較低的解決方案，應會在疑似有人試圖猜測使用者帳戶密碼時，能夠自動掃描網域控制站的安全性事件日誌並產生系統管理警示。
  
您可以在「群組原則物件編輯器」中的下列位置設定帳戶鎖定原則設定：
  
**電腦設定\\Windows 設定\\安全性設定\\帳戶原則\\帳戶鎖定原則**
  
下表記載針對本指南中定義的兩種安全性環境所提供的帳戶鎖定原則設定建議。以下各節將提供更多關於各個設定的詳細資訊。
  
**表 2.2 帳戶鎖定原則設定建議**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >設定</th>
<th style="border:1px solid black;" >網域控制站預設值</th>
<th style="border:1px solid black;" >EC</th>
<th style="border:1px solid black;" >SSLF</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">帳戶鎖定時間</td>
<td style="border:1px solid black;">尚未定義</td>
<td style="border:1px solid black;">15 分鐘</td>
<td style="border:1px solid black;">15 分鐘</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">帳戶鎖定閾值</td>
<td style="border:1px solid black;">0 次不正確的登入嘗試</td>
<td style="border:1px solid black;">50 次不正確的登入嘗試</td>
<td style="border:1px solid black;">10 次不正確的登入嘗試</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">重設鎖定計數器的時間間隔</td>
<td style="border:1px solid black;">尚未定義</td>
<td style="border:1px solid black;">15 分鐘</td>
<td style="border:1px solid black;">15 分鐘</td>
</tr>
</tbody>
</table>
  
#### 帳戶鎖定時間
  
此原則設定係決定應經過多久的時間才能將帳戶解除鎖定，並讓使用者再次嘗試登入。其係藉由指定帳戶持續被鎖定的分鐘數加以控制。如果此原則設定的值設為 0，則鎖定帳戶將維持鎖定狀態直到系統管理員解除鎖定為止。此原則設定的 Windows XP 預設值為 \[尚未定義\]。
  
為減少服務支援要求的處理量並提供安全的基礎結構，請針對本指南中定義的 EC 和 SSLF 環境，將 \[帳戶鎖定時間\] 的值設為 **15** 分鐘。
  
雖然將此原則設定的值設為永不自動解除鎖定看似一勞永逸，但如此設定可能會讓服務台疲於接應支援要求，為使用者解除因疏忽而被鎖定的帳戶。建議的 15 分鐘設定值乃經過研判而定的合理時間，萬一使用者的帳戶被鎖定時，只要等候 15 分鐘即可再次登入。使用者也應瞭解此原則的設定方式，從而知道在急需重新存取電腦時，只需求助服務支援即可。
  
#### 帳戶鎖定閾值
  
此原則設定係決定使用在帳戶鎖定前可嘗試登入的次數。授權使用者可能會因打錯或記錯密碼，或在登入電腦後卻在另一台電腦上變更密碼等情形，使帳戶被鎖定。輸入錯誤密碼的電腦會持續嘗試驗證使用者，而因為其驗證的密碼並不正確，因此使用者帳戶到最後就會被鎖定。若要避免鎖定授權使用者，請將帳戶鎖定閾值設成較大的數字。此原則設定的預設值是 0 次不正確的登入嘗試，亦即停用帳戶鎖定功能。
  
針對 EC 環境和 SSLF 環境，將 \[帳戶鎖定閾值\] 設定的值分別設為 **50** 次和 **10** 次不正確的登入嘗試。
  
由於攻擊者有可能藉由觸發大量帳戶鎖定而利用此鎖定狀態形成拒絕服務 (DoS) 攻擊，貴組織應根據已確定的威脅和所需減輕的風險，決定是否使用此原則設定。對此設定需考量兩種選項。
  
-   將 \[帳戶鎖定閾值\] 的值設為 **0**，以確保帳戶不會被鎖定。此設定值將可防止試圖鎖定貴組織內部帳戶的 DoS 攻擊。同時也能減少服務支援處理量，因為使用者不會因為不小心而鎖定自己的帳戶。然而，此設定值無法防止暴力攻擊。應考量下列防禦措施：
  
    -   制定密碼原則，強制要求所有使用者設定由 8 個或更多字元組成的複雜密碼。
  
    -   建立強大的稽核機制，以便在環境中發生一連串帳戶鎖定情形時警告系統管理員。例如，稽核解決方案應負責監視安全性事件 539，亦即登入失敗。此事件表示帳戶在嘗試登入的當時被鎖定。
  
第二個選項是：
  
-   將 \[帳戶鎖定閾值\] 設定成適合的值，一方面容許使用者不小心多次打錯密碼，同時也能夠在遇到暴力密碼攻擊時鎖定帳戶。針對 EC 環境和 SSLF 環境分別設定 50 次和 10 次不正確的登入嘗試，應足以確保充分的安全性和可接受的使用性。如此設定將可避免意外的帳戶鎖定並減少服務支援處理量，但無法防止上述的 Dos 攻擊。
  
#### 重設鎖定計數器的時間間隔
  
此原則設定係決定在 \[帳戶鎖定閾值\] 重設為零之前的時間長度。此原則設定的預設值為 \[尚未定義\]。如已定義 \[帳戶鎖定閾值\]，則此重設時間必須小於或等於 \[帳戶鎖定時間\] 設定的值。
  
針對本指南中定義的 EC 和 SSLF 環境，將 \[重設鎖定計數器的時間間隔\] 設定值皆設為 **15** 分鐘。
  
要是您將此原則設定維持在預設值，或將其值設為過長的間隔，都可能讓您的環境容易遭受到 Dos 攻擊。惡意攻擊者可對組織內的所有使用者執行多次失敗的登入嘗試，而如本章先前所述，造成使用者的帳戶被鎖定。如未定義任何原則來重設帳戶鎖定，系統管理員就必須手動解除鎖定所有的帳戶。反過來說，如果對此原則設定設有合理的時間值，使用者只會被鎖定一段時間，之後所有帳戶就會自動解除鎖定。建議的 15 分鐘設定值乃經過研判為使用者較能夠接受的合理時間，且有助於將要求服務支援要求的數量降到最低。使用者也應瞭解此原則的設定方式，從而知道在急需重新存取電腦時，只需求助服務支援即可。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 使用者權限指派設定
  
使用者權限的說明詳見第 3 章＜Windows XP 用戶端的安全性設定＞。不過，\[將工作站加入網域\] 使用者權限需指派到所有的網域控制站，故於本章進行探討。關於成員伺服器和網域控制站設定的其他資訊，請參閱《Windows Server 2003 安全性指南》的第 4 章和第 5 章。
  
#### 將工作站加入網域
  
此原則設定能讓使用者將電腦新增到特定的網域中。
  
**表 2.3 使用者權限指派設定建議**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >設定</th>
<th style="border:1px solid black;" >網域控制站預設值</th>
<th style="border:1px solid black;" >EC</th>
<th style="border:1px solid black;" >SSLF</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">將工作站加入網域</td>
<td style="border:1px solid black;">Authenticated Users</td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">Administrators</td>
</tr>
</tbody>
</table>
  
為使 \[將工作站加入網域\] 設定生效，必須將其指派給 GPO 中的使用者，且該 GPO 必須套用到網域中所有的網域控制站。被授予此權限的使用者可以在網域中新增最多 10 個工作站。獲得指派而對 OU 或 Active Directory 中的電腦容器具有「建立電腦物件」權限的使用者，無論是否獲派「新增工作站到網域」的使用者權限，皆可加入網域中的電腦並無限新增電腦至網域。
  
根據預設，**Authenticated Users** 群組中的所有使用者能夠將最多 10 台電腦新增到 Active Directory 網域。這些新電腦帳戶建立在「電腦」容器中。
  
在 Active Directory 網域中，每個電腦帳戶都是完整的安全性主體，且具備授權和存取網域資源的能力。有些組織希望限制 Active Directory 環境中的電腦數量，以便進行一貫的追蹤、建置和管理工作。而允許使用者將工作站新增至網域，可能會對此管理有所妨礙。況且，此使用者權限允許使用者建立其他未授權的網域電腦，讓使用者能夠進行更難以追蹤的活動。
  
基於上述理由，\[將工作站加入網域\] 使用者權限應該只授予在本指南中定義的兩種環境內的 **Administrators** 群組。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 安全性選項設定
  
帳戶原則必須定義在連結至網域層級的 GPO 中，例如「預設網域原則」中的原則設定。即使套用到包含網域控制站的 OU 之 GPO 中設有不同的帳戶原則設定，網域控制站仍會固定從網域層級的 GPO 取得帳戶原則。
  
在網域層級應考量與帳戶原則類似的三個安全性選項設定。您可以在「群組原則物件編輯器」中的下列位置設定這些安全性選項設定：
  
**電腦設定\\Windows 設定\\安全性設定\\本機原則\\安全性選項**
  
下表歸納出針對本指南中定義的兩種安全環境提出的安全性選項設定建議。以下各節將提供更多關於各個設定的詳細資訊。
  
**表 2.4 安全性選項設定建議**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >設定</th>
<th style="border:1px solid black;" >網域成員預設值</th>
<th style="border:1px solid black;" >EC</th>
<th style="border:1px solid black;" >SSLF</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Microsoft 網路伺服器：當登入時數過期時，中斷用戶端連線</td>
<td style="border:1px solid black;">尚未定義</td>
<td style="border:1px solid black;">已啟用</td>
<td style="border:1px solid black;">已啟用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">網路存取：允許匿名 SID/名稱轉譯</td>
<td style="border:1px solid black;">尚未定義</td>
<td style="border:1px solid black;">已停用</td>
<td style="border:1px solid black;">已停用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">網路安全性：強制限制登入時數</td>
<td style="border:1px solid black;">已停用</td>
<td style="border:1px solid black;">已啟用</td>
<td style="border:1px solid black;">已啟用</td>
</tr>
</tbody>
</table>
  
#### Microsoft 網路伺服器：當登入時數過期時，中斷用戶端連線
  
此原則設定係決定是否要在連線到本機網路的使用者超過其使用者帳戶的有效登入時數時，中斷其連線。此原則設定會影響伺服器訊息區 (SMB) 元件。如果啟用此原則設定，會導致使用 SMB 服務的用戶端工作階段在用戶端的登入時數過期時強制中斷連線。如果停用此原則，則允許建立的用戶端工作階段在用戶端登入時數過期後仍繼續進行。啟用此原則設定時，請確定 \[網路安全性: 強制限制登入時數\] 也同時啟用。
  
**注意：**伺服器訊息區是 Windows 網路中共用資源的基礎。影響 SMB 的設定也會連帶影響共用資源，例如：資料夾和印表機。
  
如果貴組織已為使用者設定登入時數，啟用 \[Microsoft 網路伺服器: 當登入時數過期時，中斷用戶端連線\] 設定才有意義。否則超出登入時數而假設無法存取網路資源的使用者，可能實際上還可以透過在允許時數期間所建立的工作階段來存取該等資源。
  
如果貴組織未設定登入時數，即使啟用此原則設定，也不會有任何影響。如果啟用登入時數，則使用者工作階段將在其登入時數過期時終止。
  
#### 網路存取：允許匿名 SID/名稱轉譯
  
\[網路存取: 允許匿名 SID/名稱轉譯\] 設定係決定匿名使用者能否要求另一名使用者的 SID。如果在網域控制站上啟用此設定，則知道系統管理員 SID 屬性的使用者就能夠連繫同樣有啟用此原則的電腦，並使用該 SID 來取得系統管理員的帳戶資訊。該人員接著即可利用該帳戶來發動密碼猜測攻擊。在成員電腦上的預設設定是 \[已停用\]。不過，網域控制站的預設設定是 \[已啟用\]。若停用此原則設定，下列系統可能無法夠與 Windows 伺服器 2003 的網域連線：
  
-   Microsoft Windows NT® 4.0 架構的遠端存取服務伺服器。
  
-   在位於 Windows NT 3.*x* 網域或 Windows NT 4.0 網域內的 Windows 2000 電腦上執行的遠端存取服務伺服器。
  
-   在 Windows NT 3.*x* 或 Windows NT 4.0 電腦上執行的 Microsoft SQL Server。
  
-   在位於 Windows NT 3.*x* 網域或 Windows NT 4.0 網域內的 Windows 2000 電腦上執行 SQL Server。
  
-   位於 Windows NT 4.0 資源網域內的使用者，且該使用者想要將檔案、共用資料夾和登錄物件的存取權限，指派給位在包含 Windows Server 2003 網域控制站的帳戶網域中的使用者帳戶。
  
#### 網路安全性：強制限制登入時數
  
\[網路安全性: 強制限制登入時數\] 設定係決定是否要在連線到本機網路的使用者超過其使用者帳戶的有效登入時數時，中斷其連線。此原則設定會影響 SMB 元件。
  
如果您啟用此原則設定，當使用者的登入時數過期時，含 SMB 伺服器的用戶端電腦工作階段將中斷連線，在下次允許的存取時間來臨之間，該使用者將無法登入系統。如果停用此原則設定，在使用者的登入時數過期後，將會繼續維持已建立的用戶端工作階段。若要影響網域帳戶，此原則設定必須定義在與網域根目錄連結的 GPO 中。
  
[](#mainsection)[回到頁首](#mainsection)
  
### Kerberos 原則
  
Kerberos 5 版 驗證通訊協定的原則是在網域控制站上設定，而非網域的成員電腦。此原則係判定與 Kerberos 通訊協定相關的設定，例如票證最長存留期和強制執行。本機電腦原則中沒有 Kerberos 設定。在大多數環境中，這些設定的預設值都不應該變更。本指南並未提供對預設 Kerberos 原則的任何變更。如需更多關於這些設定的資訊，請參閱同系列指南[*威脅與因應對策：Windows Server 2003 及 Windows XP 中的安全性設定*](http://go.microsoft.com/fwlink/?linkid=15159)，網址是：http://go.microsoft.com/fwlink/?LinkId=15159。
  
[](#mainsection)[回到頁首](#mainsection)
  
### OU 層級的群組原則
  
包含在此 OU 層級的群組原則中的安全性設定應專門針對該 OU。這類設定包括電腦設定和使用者設定。為方便管理和改進安全性，在本指南中將軟體限制原則 (SRP) 一節與其他安全性設定分開探討。第 6 章＜Windows XP 用戶端的軟體限制原則＞提供有關 SRP 的詳細資訊。
  
#### 群組原則安全性設定
  
您需要為環境中的每個 Windows XP 電腦類別逐一建立 GPO。膝上型和桌上型電腦在本指南中劃分成不同的 OU，以便套用針對每個電腦類別自訂的 GPO。
  
#### 軟體限制原則設定
  
建立專用 GPO 以設定您環境中的 SRP 設定。將 SRP 設定與其餘群組原則設定區分開來有幾個重要的理由。其中一個理由是 SRP 在概念上有別於其他群組原則設定。未啟用或未停用選項，也未設定的值。不過，SRP 需要系統管理員識別所要支援的應用程式集、所要套用的限制，以及例外的處理方式等。另一個理由是在生產環境中實作 SRP 原則而發生災難性錯誤時，可加速迅速復原：系統管理員可暫時停用定義 SRP 設定的 GPO，而不致於影響任何其他安全性設定。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 群組原則工具
  
Windows  XP 隨附數種工具，可讓 GPO 的使用更加簡單。本節提供其中幾種工具的簡要概觀。如需更多關於這些工具的資訊，請參閱 Windows XP 的線上說明。
  
#### 強制更新群組原則
  
Active Directory 會定期更新群組原則，但您可以使用 GpUpdate (隨附在 Windows XP Professional 的一種命令列工具) 強制更新用戶端電腦上的版本。該工具必須在用戶端電腦本機執行。
  
若要使用此工具更新本機電腦，請在命令提示字元中執行如下：
  
```  
gpupdate /force  
```  
執行 GpUpdate 後，會顯示下列確認資訊：
  
```  
C:\\Documents and Settings\\administrator.MSSLAB&gt;gpupdate /force Refreshing Policy... User Policy Refresh has completed. Computer Policy Refresh has completed. To check for errors in policy processing, review the event log. C:\\Documents and Settings\\administrator.MSSLAB&gt;  
```  
對於使用者架構的群組原則，您必須先登出再重新登入用來測試原則的電腦。電腦原則應會立即更新。
  
若要查看其他的 Gpupdate 選項，請在命令提示字元中執行如下：
  
```  
gpupdate /?  
```  
#### 檢視原則結果組
  
Windows XP 隨附的兩項工具可讓您確定環境內的電腦所套用的原則、套用時間，以及套用的順序。
  
-   **RSoP 嵌入式管理單元**： 此工具 (RSoP.msc) 是一種 MMC 嵌入式管理單元工具，會顯示所有套用至電腦的原則之彙總設定。此工具可在本機或從遠端的另一台電腦執行。RSoP 工具會針對各項原則設定，顯示出電腦設定和來源 GPO。
  
-   **Gpresult**： 這是一種命令列工具，其係提供有關群組原則最近套用至電腦的時間、電腦所套用的 GPO，以及套用的順序等統計資料。此工具並提供任何有關透過篩選套用的 GPO 資訊。GpResult 工具可在用戶端電腦上透過遠端或本機使用。
  
#### 群組原則管理主控台
  
群組原則管理主控台 (GPMC) 是一種MMC 嵌入式管理單元，是搭配 Windows Server 2003 Service Pack 1 使用的選用元件。其用途在於管理所有與群組原則相關的工作。GPMC 可協助進行 GPO 應用方面的規劃、籌備、部署、報告、編寫和疑難排解。如需更多資訊，請瀏覽 [GPMC](http://www.microsoft.com/taiwan/windowsserver2003/gpmc/default.mspx) 網站，網址是：  
www.microsoft.com/taiwan/windowsserver2003/gpmc/default.mspx。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 總結
  
群組原則是一種以 Active Directory 為主的功能，供您用來控制 Windows Server 2003 和 Windows 2000 網域中的使用者及電腦環境。在將群組原則套用至您環境中的 Windows XP 桌上型電腦之前，您必須先在網域中執行特定的預備步驟。
  
群組原則設定儲存在您環境中的網域控制站上的群組原則物件 (GPO) 中，這些設定連結到位在 Active Directory 結構中的站台、網域和 OU。在實作群組原則之前，應先瞭解 Active Directory 結構以及其中所設定的不同設計選項所具有的安全性含義。
  
「群組原則」是保障 Windows XP 安全之不可或缺的工具。本章為您詳細說明如何從中央位置使用群組原則，以套用和維護整個網路一致的安全性原則。
  
此外，並介紹各種不同層級的群組原則，以及可在您環境中用來更新群組原則的特殊工具。
  
#### 其他資訊
  
下列連結提供更多與 Windows XP Professional 安全性有關的主題。
  
-   如需更多關於 Active Directory 管理和設計的資訊，請參閱白皮書[Active Directory 中委派系統管理的設計考量](http://go.microsoft.com/fwlink/?linkid=18349) (英文)，網址是：http://go.microsoft.com/fwlink/?LinkId=18349。
  
-   如需更多關於 Active Directory 設計的資訊，請參閱白皮書[管理 Windows 網路之 Active Directory 設計最佳實務](http://www.microsoft.com/technet/prodtechnol/windows2000serv/technologies/activedirectory/plan/bpaddsgn.mspx) (英文)，網址是：www.microsoft.com/technet/prodtechnol/windows2000serv/technologies/activedirectory/plan/bpaddsgn.mspx。
  
-   如需更多關於群組原則的資訊，請參閱白皮書[瞭解群組原則功能集步驟指南](http://www.microsoft.com/technet/prodtechnol/windowsserver2003/technologies/directory/activedirectory/stepbystep/gpfeat.mspx) (英文)，網址是：www.microsoft.com/technet/prodtechnol/windowsserver2003/technologies/directory/  
    activedirectory/stepbystep/gpfeat.mspx。  
    此外，請參閱[群組原則](http://www.microsoft.com/windowsserver2003/technologies/management/grouppolicy/default.mspx)首頁 (英文) ，網址是：www.microsoft.com/windowsserver2003/technologies/management/grouppolicy/default.mspx
  
-   如需更多關於 Windows XP 安全性的資訊，請參閱 [Microsoft Windows XP Professional Resource Kit 說明文件](http://www.microsoft.com/windowsxp/pro/techinfo/productdoc/resourcekit.asp) (英文)，網址是：www.microsoft.com/WindowsXP/pro/techinfo/productdoc/resourcekit.asp。
  
-   有關 Windows XP 安全性功能的概觀介紹，請參閱白皮書[Windows XP Professional 和 Windows XP Home Edition 的安全性新功能](http://www.microsoft.com/technet/prodtechnol/winxppro/evaluate/xpsec.mspx) (英文)，網址是：www.microsoft.com/technet/prodtechnol/winxppro/evaluate/xpsec.mspx。
  
-   如需更多關於系統管理範本的資訊，請參閱[實作已登錄的群組原則](http://www.microsoft.com/taiwan/technet/prodtechnol/windows2000serv/howto/default.mspx)，網址是：www.microsoft.com/taiwan/technet/prodtechnol/windows2000serv/howto/default.mspx。
  
-   如需更多關於群組原則管理主控台 (GPMC) 的資訊，請參閱 [GPMC](http://www.microsoft.com/taiwan/windowsserver2003/gpmc/default.mspx) 網站，網址是：www.microsoft.com/taiwan/windowsserver2003/gpmc/default.mspx。
  
-   如需關於群組更新工具 [Gpupdate](http://www.microsoft.com/resources/documentation/windows/xp/all/proddocs/en-us/refrgp.mspx) (英文) 的其他資訊，請參閱 www.microsoft.com/resources/documentation/windows/xp/all/proddocs/en-us/refrgp.mspx。
  
-   如需關於[原則結果組](http://www.microsoft.com/resources/documentation/windows/xp/all/proddocs/en-us/rspoverview.mspx) (RSoP) (英文) 工具的其他資訊，請參閱 www.microsoft.com/resources/documentation/windows/xp/all/proddocs/en-us/rspoverview.mspx。
  
-   如需關於群組原則結果工具 [Gpresult](http://www.microsoft.com/resources/documentation/windows/xp/all/proddocs/en-us/gpresult.mspx) (英文) 的資訊，請參閱 www.microsoft.com/resources/documentation/windows/xp/all/proddocs/en-us/gpresult.mspx。
  
-   如需關於如何在 Active Directory 中委派授權的資訊，請參閱 *Windows 2000 Resource Kit* 中有關規劃[分散式安全性](http://www.microsoft.com/resources/documentation/windows/2000/server/reskit/en-us/distrib/dsca_pt3_stbp.asp) (英文) 的部分，網址是：www.microsoft.com/resources/documentation/Windows/2000/server/reskit/en-us/distrib/  
    dsca\_pt3\_stbp.asp。
  
[](#mainsection)[回到頁首](#mainsection)
  
##### 下載
  
[![](images/Cc163071.icon_exe(zh-tw,TechNet.10).gif)下載 Windows XP 安全性指南 (英文)](http://go.microsoft.com/fwlink/?linkid=14840)
  
[](#mainsection)[回到頁首](#mainsection)
