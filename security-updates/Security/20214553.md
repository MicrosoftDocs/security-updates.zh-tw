---
TOCTitle: Windows 2000 Server 基準安全性檢查清單
Title: Windows 2000 Server 基準安全性檢查清單
ms:assetid: '9a82d8ee-d90f-49c2-9d24-e0e0d0a8e4d5'
ms:contentKeyID: 20214553
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc751389(v=TechNet.10)'
---

Windows 2000 Server 基準安全性檢查清單
======================================

　
本檢查清單中簡要說明執行安全防護時應採取的所有步驟，以保護本身執行 Windows 2000 Server 的電腦，或者在 Windows NT 或 Windows 2000 網域中執行此系統的電腦。這些步驟可套用於 Windows 2000 Server 和進階伺服器。

**重要事項** 本檢查清單的目的，是為執行 Windows 2000 Server 的電腦，提供設定基準安全性等級的指示。安全性設定可透過「安全性設定工具組」於本機伺服器套用與設定。可使用安全性設定工具組建立網域安全性原則，並透過「群組原則」散佈和套用。本指南簡要說明 Windows 2000 的建議安全性設定。使用安全性設定工具組設定企業安全性原則的逐步指南，位於 Microsoft TechNet 安全性網站上。

本檢查清單中包含有關登錄編輯的資訊。編輯登錄之前，請確定發生問題時，您能夠修復原有檔案。如需修復原有登錄的相關資訊，請於 Regedit.exe 檔案中查閱〈復原登錄〉說明主題，或者於 Regedt32.exe 檔案中查閱〈復原登錄機碼〉說明主題。

### Windows 2000 Server 設定步驟

![](images/Cc751389.BOX(zh-tw,TechNet.10).gif) 請確認所有磁碟分割磁區皆使用 NTFS 完成格式化

![](images/Cc751389.BOX(zh-tw,TechNet.10).gif) 請確認管理員帳戶具有強式密碼

![](images/Cc751389.BOX(zh-tw,TechNet.10).gif) 停用不必要的服務

![](images/Cc751389.BOX(zh-tw,TechNet.10).gif) 停用或刪除不必要的帳戶

![](images/Cc751389.BOX(zh-tw,TechNet.10).gif) 保護檔案和目錄
![](images/Cc751389.BOX(zh-tw,TechNet.10).gif) 確認來賓帳戶已停用

![](images/Cc751389.BOX(zh-tw,TechNet.10).gif) 保護登錄不可使用匿名方式存取

![](images/Cc751389.BOX(zh-tw,TechNet.10).gif) 套用適當的登錄 ACL

![](images/Cc751389.BOX(zh-tw,TechNet.10).gif) 限制存取公用本機安全性授權 (LSA) 資訊

![](images/Cc751389.BOX(zh-tw,TechNet.10).gif) 設定強式密碼原則

![](images/Cc751389.BOX(zh-tw,TechNet.10).gif) 設定帳戶鎖定原則

![](images/Cc751389.BOX(zh-tw,TechNet.10).gif) 設定管理員帳戶

![](images/Cc751389.BOX(zh-tw,TechNet.10).gif) 移除所有不必要的檔案共用

![](images/Cc751389.BOX(zh-tw,TechNet.10).gif) 在所有必要的檔案共用中設定適當的 ACL

![](images/Cc751389.BOX(zh-tw,TechNet.10).gif) 安裝防毒軟體和更新

![](images/Cc751389.BOX(zh-tw,TechNet.10).gif) 安裝最新的 Service Pack

![](images/Cc751389.BOX(zh-tw,TechNet.10).gif) 安裝適當的後置 Service Pack 安全性 Hotfix

Windows 2000 Server 組態檢查清單：進一步的詳細內容
--------------------------------------------------

### 確認所有磁碟分割磁區皆使用 NTFS 完成格式化

NTFS 分割磁區可提供 FAT、FAT32 或 FAT32x 檔案系統無法提供的存取控制和保護。確認伺服器上所有分割磁區皆使用 NTFS 格式化。如有必要，請使用 convert 公用程式以非破壞性的方法將 FAT 分割磁區轉換為 NTFS。

**警告** 如果您使用 convert 公用程式，則會將轉換磁碟的 ACL 設定為 Everyone：完整控制權。

### 請確認管理員帳戶具有強式密碼

Windows 2000 最多可允許 127 個字元的密碼。一般來說，密碼愈長愈不容易破解；而包含各種字元類型 (字母、數字、標點符號，以及使用數字鍵盤上 ALT 鍵和三位數鍵碼所產生的非列印 ASCII 字元) 的密碼又比純字母或字母與數字組成的密碼更不容易破解。為獲得最高的保護，請確認管理員帳戶密碼至少有九個字元長度，且前七個字元中至少包含一個標點符號或非列印式 ASCII 字元。此外，管理員帳戶密碼不應跨多重伺服器同步處理。每台伺服器應使用不同的密碼，以提升工作群組或網域的安全性。

### 停用不必要的服務

Windows 2000 Server 安裝完成後，應停用伺服器角色所有不必要的網路服務。應特別考量伺服器是否需要 IIS 元件，以及是否應為檔案和列印共用執行伺服器服務。

同時應避免於伺服器上安裝應用程式，除非對伺服器功能而言是絕對必要的。例如，請不要安裝電子郵件用戶端、辦公室產能工具，或者伺服器工作時不一定用得到的公用程式。

### 停用或刪除不必要的帳戶

您應於「電腦管理」嵌入式管理單元上重新檢視使用中帳戶清單 (包括使用者和應用程式清單)，並且停用非使用者帳戶，同時刪除不再需要的帳戶。

### 保護檔案和目錄

請參閱 Microsoft TechNet 安全性網站上的[《Default Access Control Settings in Windows 2000》](http://www.microsoft.com/technet/prodtechnol/windows2000serv/maintain/security/secdefs.mspx)文件，以取得預設 Windows 2000 檔案系統 ACL 的詳細內容，以及執行必要修改的方法。

### 確認來賓帳戶已停用

依照預設，Windows 2000 Server 系統中的來賓帳戶是停用狀態。如果來賓帳戶已啟用，請停用。

**保護登錄不可使用匿名方式存取**

預設使用權限未限制遠端存取登錄。只有管理員可以遠端存取登錄，因為 Windows 2000 登錄編輯程式依預設可支援遠端存取。要限制網路存取登錄：

1.  將下列索引鍵新增至登錄中：
 
    <table style="border:1px solid black;">
    <colgroup>
    <col width="50%" />
    <col width="50%" />
    </colgroup>
    <tbody>
    <tr class="odd">
    <td style="border:1px solid black;"><ul>
    <li><strong>Hive</strong></li>
    </ul></td>
    <td style="border:1px solid black;"><ul>
    <li>HKEY_LOCAL_MACHINE \SYSTEM</li>
    </ul></td>
    </tr>
    <tr class="even">
    <td style="border:1px solid black;"><ul>
    <li><strong>Key</strong></li>
    </ul></td>
    <td style="border:1px solid black;"><ul>
    <li>\CurrentControlSet\Control\SecurePipeServers</li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td style="border:1px solid black;"><ul>
    <li><strong>Value Name</strong></li>
    </ul></td>
    <td style="border:1px solid black;"><ul>
    <li>\winreg</li>
    </ul></td>
    </tr>
    </tbody>
    </table>
 

2.  選取 winreg，按一下 \[安全性\] 功能表，然後按一下 \[使用權限\]。
3.  將管理員使用權限設定為「完整控制權」，請確定未列出其他使用者或群組，然後按一下 \[確定\]。

在本索引鍵上設定的安全性權限 (ACL) 可定義哪些使用者或群組可連線至系統，以進行遠端登錄存取。此外，雖然 winreg 索引鍵上設定有 ACL，但 AllowedPaths 子機碼中仍包含 Everyone 群組成員可以存取的索引鍵清單。這樣可以讓特定系統功能正確運作，而不管經由 winreg 登錄機碼限制存取的方式，例如檢查印表機狀態。AllowedPaths 登錄機碼的預設安全性僅限由「管理員」管理這些路徑。AllowedPaths 索引鍵及其正確使用方法，皆記錄於「Microsoft 知識庫」文件 [Q155363](http://support.microsoft.com/support/kb/articles/q153/1/83.asp?id=153183&sd=tech) 中。

### 套用適當的登錄 ACL

請參閱 Microsoft TechNet 安全性網站上的[《Default Access Control Settings in Windows 2000》](http://www.microsoft.com/technet/prodtechnol/windows2000serv/maintain/security/secdefs.mspx)文件，以取得預設 Windows 2000 檔案系統 ACL 的詳細內容，以及執行必要修改的方法。

### 限制存取公用本機安全性授權 (LSA) 資訊

您必須能夠識別出系統中所有使用者。因此，應限制匿名使用者，以減少這些使用者取得有關「Windows NT 安全性子系統」LSA 元件的公用資訊量。LSA 可於本機電腦上處理安全性管理各個層面，其中包括存取和使用權限。若要實行這項限制，請建立並設定下列登錄項目：

 
<table style="border:1px solid black;">
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Hive</strong><br />
</td>
<td style="border:1px solid black;">HKEY_LOCAL_MACHINE \SYSTEM<br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Key</strong><br />
</td>
<td style="border:1px solid black;">CurrentControlSet\Control\LSA<br />
</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Value Name</strong><br />
</td>
<td style="border:1px solid black;">RestrictAnonymous<br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Type</strong><br />
</td>
<td style="border:1px solid black;">REG_DWORD<br />
</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Value</strong><br />
</td>
<td style="border:1px solid black;">1<br />
</td>
</tr>
</tbody>
</table>
 

### 設定強式密碼原則

使用「網域安全性原則」(或本機安全性原則) 嵌入管理單元，以加強有關接受密碼的系統原則。Microsoft 建議您進行下列變更：

-   至少將密碼長度設定為 8 個字元
-   設定適合網路的密碼使用最短期限 (一般為 1到 7 天)
-   設定適合網路的密碼使用最長期限 (一般不超過 42 天)
-   設定至少六個密碼記錄維護 (使用「記住密碼」選項)

### 設定帳戶鎖定原則

Windows 2000 包括帳戶鎖定功能，於管理員指定的登入失敗次數後，即停用該帳戶。要獲得最佳安全性，請設定於 3 到 5 次登入失敗後即啟動鎖定，30 分鐘後重設計數，並將鎖定期限設定為「永久」(直到系統管理者解除)。

[Windows NT Server Resource Kit](http://www.microsoft.com/mspress/books/1394.asp) 中包含一項工具，可供您調整部份無法透過正常管理工具存取的帳戶屬性。此工具「passprop.exe」可供您鎖定管理員帳戶：

-   「/adminlockout」參數可鎖定管理員帳戶

### 設定管理員帳戶

由於「管理員」帳戶已內建於所有 Windows 2000 版本中，因此可說是駭客皆知的攻擊目標。為了讓駭客難以攻擊管理員帳戶，請同時在各伺服器的本機管理員帳戶以及網域管理員帳戶中，執行下列內容：

-   將帳戶重新命名為不易辨識的名稱 (如 not "admin," "root," 等等。)
-   建立名為「管理員」但無使用權限的誘餌帳戶。定期掃描事件記錄，以找出是否有人嘗試使用此帳戶。
-   在真正的管理員帳戶中使用 passprop 公用程式啟動帳戶鎖定。
-   停用本機電腦的管理員帳戶。

### 移除所有不必要的檔案共用

應移除系統上所有不必要的檔案共用，以避免透露資訊，並防止駭客利用共用方式進入本機系統中。

### 在所有必要的檔案共用中設定適當的 ACL

依照預設，所有使用者都具備新建檔案共用的「完整控制權」使用權限。所有系統上需要的共用皆應設定 ACL，讓使用者都能具備適當的共用級存取權限 (如 Everyone = Read)。

**注意** 除了共用級使用權限以外，NTFS 檔案系統必須在個別檔案中用來設定 ACL。

### 安裝防毒軟體和更新

請務必安裝防毒軟體，並隨時於 Internet 和 Intranet 系統中下載最新的病毒碼。

Microsoft TechNet 安全性網站上還有更多安全性防毒資訊，網址為：

<http://www.microsoft.com/technet/security/topics/virus/default.mspx>

### 安裝最新的 Service Pack

每個 Windows Service Pack 都包含上一版 Service Pack 的所有安全性修訂。Microsoft 建議您隨時更新 Service Pack 版本，並於作業環境許可的情況下，為伺服器安裝正確的 Service Pack。目前的 Windows 2000 Service Pack、SP2 位於：

<http://www.microsoft.com/windows2000/downloads/servicepacks/sp2/>

Service Packs 亦可向「Microsoft 產品支援服務」取得。Microsoft 產品支援服務的連絡資訊，位於 <http://support.microsoft.com/support/contact/default.asp> 。

### 安裝適當的後置 Service Pack 安全性 Hotfix

Microsoft 透過[「安全性通知服務」](http://www.microsoft.com/technet/security/bulletin/notify.mspx)張貼安全性公告。若這些公告中建議安裝安全性 Hotfix，應立即下載 Hotfix 並安裝於您的伺服器上。

### 其他安全性設定

在 Windows 2000 系統中可用來維護伺服器安全的，還包括其他安全性功能，但未能於本文中一一介紹。這些安全性功能的相關資訊 (例如 Encrypting File System (EFS)、Kerberos、IPSEC、PKI 和 IE 安全性)，位於 Microsoft TechNet 安全性網站上：

<http://www.microsoft.com/technet/security/prodtech/win2000/default.mspx>

本檢查清單中提供的資訊呈如字面上所述，本公司不做任何保證。MICROSOFT 不承擔任何責任擔保，不論其為明示或默示者，其中包括適售性以及適合某特定用途之擔保責任。MICROSOFT CORPORATION 或其供應商對於任何損害絕不負責，包括直接、間接、意外、負面影響、損失業務利潤或特殊損害。即使 MICROSOFT CORPORATION 或其供應商已告知此類損害的可能性亦同。某些地區並不允許公司排除或限制自然影響或意外損害責任，因此前述的限制並不適用於這些地區。

[](#mainsection)[回到頁首](#mainsection)
