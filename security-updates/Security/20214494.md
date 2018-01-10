---
TOCTitle: '強化 Microsoft Windows NT 4.0'
Title: '強化 Microsoft Windows NT 4.0'
ms:assetid: 'a72dc2af-e2c0-4e49-a476-8dfe316b8568'
ms:contentKeyID: 20214494
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc750829(v=TechNet.10)'
---

Windows NT 4.0 與 Windows 98 降低安全性威脅指南
===============================================

### 第 4 章：強化 Microsoft Windows NT 4.0

發佈日期: 2004 年 9 月 13 日 | 更新日期: 2006 年 3 月 30 日

Microsoft® Windows NT® 4.0 版缺乏一些較新版 Microsoft Windows® 作業系統才有的加強安全性功能。即使如此，它還是擁有一些非常有用的功能與技巧，可以讓您充分改善系統安全性。本章將詳述這些主題，並說明如何使用這些功能來強化 Windows NT 4.0 系統工作站和伺服器。

這些主題包括如何進行以下作業：

-   安裝最初的作業系統和補充程式基礎安裝。

-   強化開機程序。

-   安裝目錄服務用戶端增益集。

-   使用系統原則以及安全性設定管理員。

-   選擇 Windows NT LAN Manager (NTLM) 驗證等級。

-   定義有效密碼原則。

-   使用帳戶及密碼鎖定。

-   強化檔案系統。

-   強化服務。

-   進行其他強化措施。

##### 本頁內容

[](#edaa)[Windows NT 主機安全性設計](#edaa)
[](#ecaa)[實作](#ecaa)
[](#ebaa)[測試解決方案](#ebaa)
[](#eaaa)[總結](#eaaa)

### Windows NT 主機安全性設計

強化 Windows  NT 4.0 作業系統之前，需要先評估瞭解幾個課題。

#### 安裝最初的作業系統和補充程式基礎安裝

強化 Windows  NT 系統最關鍵的第一個步驟，就是為基礎作業系統安裝最新的安全性補充程式。如第 6 章＜補充程式管理＞所述，這個步驟最好包括在平時的補充程式管理過程中進行。首先要進行清查，確認每部電腦的版本等級。您可以利用 Microsoft Baseline Security Analyzer (MBSA) 或 Microsoft Systems Management Server (SMS)，從本機或遠端掃描 Windows NT 4.0 系統。完成清查後必須檢視清查結果，以確保每部 Windows NT 系統都已經安裝所需的基礎更新。這些更新包括：

-   Windows NT 4.0 Service Pack 6a，這是 Windows NT 4.0 最新的 Service Pack，其中包括一套經迴歸測試的完整修正程式，可以一次安裝完成。

-   Windows NT 4.0 Service Pack 6a 後續安全性彙總套件。這個 SRP 含有數項更新，都是原始 SP6a 發佈後才發佈的，必需先安裝這個彙總套件，才能從 Windows Update 安裝後續的更新。

-   一套最新的安全性補充程式。Microsoft 發佈 SRP 之後便沒有再為 Windows NT 4.0 發佈整合的 SRP 或 Service Pack。但是作業系統的個別元件、Microsoft Internet Explorer，以及附加公用程式 (例如，路由及遠端存取服務 (RRAS) 和 Internet Information Services (IIS)) 等都有更新。您可以從 Microsoft TechNet 取得最新的補充程式清單，或到 Windows Update 手動檢視可用的補充程式清單。

-   更新版本的 Internet Explorer。目前使用的版本為 Internet Explorer 6.0 Service Pack 1 (SP1)，其中包括了從 Windows NT 隨附的最早 Internet Explorer 版本開始至今，所發行的數百個安全性修正程式及加強功能。您可以根據環境選擇直接從 Microsoft 網站下載 Internet Explorer、訂購光碟，或利用 Internet Explorer Administration Kit 為多部電腦進行安裝。

#### 強化開機程序

系統安裝了完整且正確的更基本補充程式組之後，接下來要提升系統開機時間的安全性。這段防護工作有兩個層面：將開機功能表的等候時間設為零，避免攻擊者使用其他作業系統開機，並用內建的 Syskey 公用程式加密安全性帳戶管理員 (SAM) 資料庫中的資料。

Windows NT Server 會將使用者帳戶資訊 (包括使用者帳戶密碼的衍生資料) 儲存於登錄裡的安全區域，這個區域受到存取控制和模糊化 (Obfuscation) 加密功能的保護。登錄裡的帳戶資訊只有 Administrators 群組的成員才能存取。Windows NT Server 與其他的作業系統一樣，會允許系統管理員存取系統所有資源。若是需要再加強安全性，可以為帳戶密碼衍生資訊使用增強式加密，提供另一層的保護，預防系統管理員有心或無意間使用登錄程式介面存取密碼衍生資料。Syskey 也可以保護 SAM 資料不受各種離線攻擊，例如用另一個作業系統開機並存取 SAM 檔案。

Syskey 會產生隨機的加密金鑰來加密 SAM 資料。加密完成後，開機時必須先載入金鑰才能解開記憶體裡的 SAM 資料。Syskey 有三種作業模式，如圖 4.1 所示：

-   在模式 1 (\[將啟動金鑰存放在本機上\]) 中，加密金鑰會經過超級加密後存在本機電腦。開機時，加密金鑰會解密並載入，讓電腦不需要系統管理員介入即可重新開機。

-   在模式 2 (\[密碼啟動\] 按鈕及相關文字欄位) 中，會用系統管理員指定的密碼片語為金鑰進行超級加密。開機時，系統管理員必須在主控台輸入密碼片語，才能完成開機程序， 不輸入密碼片語就不能開機。

-   在模式 3 (\[將啟動金鑰存放在軟式磁片\] 按鈕) 中，隨機產生的 Syskey 金鑰會存於磁片裡，開機時必需插入磁片才能完成開機程序。這張磁片必須存放於安全的地方。

![](images/Cc750829.nt980401(zh-tw,TechNet.10).gif)

**圖 4.1 Syskey 的模式選擇對話方塊**

Trey 選擇在所有執行 Windows NT 的電腦上實作 Syskey 保護措施 (Windows 2000、Microsoft Windows Server™ 2003 以及 Windows XP 中會預設啟用 Syskey)。Trey 在大部份的伺服器以及全部的工作站上都設定使用 Syskey 的模式 1；選擇廣泛使用這個模式的原因是該模式能夠兼顧安全性與便利性。在高價值伺服器上，Trey 則選用了每次重新開機都需要系統管理員輸入密碼的模式 2。最後，由於模式 3 需要為每部電腦個別存放開機磁片，所以 Trey 選擇不在任何系統上使用這個模式。

#### 安裝目錄服務用戶端增益集

Windows NT 4.0 系統只能加入 Windows NT 網域，如果是 Microsoft Adtive Directory® 目錄服務網域，則 Windows 98 與 Windows NT 僅能透過網路基本輸入輸出系統 (NetBIOS) 以原生模式加入該網域。Windows 2000 與 Windows Server 2003 會模擬 Windows NT 主要網域控制站，因此具有 NetBIOS 相容能力。雖然 Active Directory 提供了可轉移的雙向信任，但是 Windows NT 4.0 還是只能利用明確的單向信任，不論系統用的是 Active Domain 網域控制站或是 Windows NT BDC 都一樣。

因此即使不使用 Windows NT 式網域，還是可以使用加入目錄服務用戶端增益集的方式，讓執行 Windows NT 與 Windows 98 的系統加入 Active Directory 網域。DSClient 能讓這些系統加入 Active Directory 網域。有了這個軟體，這些系統便可以利用 Active Directory 的許多功能，例如在樹系中使用可轉移的信任關係。可轉移的信任關係可以讓授權的使用者存取同樹系中任何網域裡的適用資源。DSClient 2003 的更新隨附在 Windows NT 4.0 SP6a 及 Internet Explorer 6 SP1 中，Windows 2000 隨附的 DSClient 版本也需要 SP6，但是可以使用 Internet Explorer 4.01 或以上版本 (如需更多關於在 Windows 98 上使用 DSClient 的需求資訊，請參閱第 5 章＜強化 Microsoft Windows 98＞。)

安裝之後 DSClient 並不會支援所有 Active Directory 功能，特別是不支援 Kerberos 驗證、群組原則應用，或使用服務或使用者主要名稱 (UPN) 進行驗證。不過 DSClient 支援下列 Active Directory 功能：

-   Active Directory 服務介面 (ADSI)。ADSI 為支援 Active Directory 的指令碼及程式提供一般的程式設計 API。在 Windows NT 上，許多原先不能夠經由指令碼控制的目錄作業，均可透過 ADSI 編寫指令碼控制。

-   分散式檔案系統 (DFS) 容錯用戶端。DFS 容錯及容錯移轉檔案共用提供與 Active Directory 整合的分散式檔案共用資源。

-   Active Directory Windows 通訊錄 (WAB) 內容頁。從 \[搜尋\] 功能表中存取的使用者物件頁面，可以讓授權使用者更新使用者物件的內容 (例如住址及電話號碼)。

-   NTLM 第 2 版驗證方式。NTLM 提供較佳的驗證功能，其驗證安全性僅次於 Kerberos。

-   站台感知。如果正確設定網域名稱系統，且於 Active Directory 中註冊站台，則使用 DSClient 的系統可以感知 Active Directory 站台，並會使用本機站台的網域控制站 (甚至可以進行修改密碼的作業)。如需更多關於 DSClient 影響登入及密碼變更行為的資訊，請參閱 Microsoft 知識庫文件編號 249841＜Windows  98 Active Directory 用戶端擴充功能如何使用 Active Directory 站台資訊＞(英文)，網址為：<http://support.microsoft.com/?kbid=249841>。

-   在 Active Directory 中搜尋物件。使用者可以從 \[搜尋\] 功能表尋找 Active Directory 中的印表機和使用者。

-   降低對 PDC 的依存性。用戶端可以連上網域內的任何網域控制站進行密碼變更。

#### 使用系統原則與安全性設定系統管理員。

系統原則是自 Windows 95 及 Windows NT 4.0 開始才發展出的設定管理措施。這些措施本身並不能加強系統安全性，但可以讓您限制特定資源的存取，加強其他的安全性措施，進而預防使用者有意或無心跳過原則及限制。正確設計並套用這些原則後，原則就會在確保舊系統完整性的方面發揮重要的功能。事實上，由於這些措施效果極佳，因此 Microsoft 將之擴充，建立了 Windows 2000 和更新版中的群組原則物件 (GPO)。

系統原則就是套用於 **HKEY\_CURRENT\_USER** 及 **HKEY\_LOCAL\_MACHINE** 登錄區的一組限制。當使用者登入電腦時，就會根據使用者帳戶名稱、網域中的通用群組成員資格和本機原則設定，開始一連串的原則檢查，並套用找到的原則。系統原則是用於 Windows NT 網域實作，並輔助其他網域相關功能 (例如使用者設定檔)。

請務必瞭解系統原則與使用者設定檔之間的差別。使用者設定檔就是於 **HKEY\_CURRENT\_USER** (Windows NT 系統存於 Ntuser.dat，Windows 98 系統存於 User.dat) 之下載入的使用者特定的設定目錄、檔案、捷徑與登錄區集合。這些設定控制了桌面外觀、瀏覽器「我的最愛」項目與書籤，以及其他使用者設定的作業系統與應用程式選項。相反地，系統原則是一組額外的登錄項目，在找出並載入作用中的使用者設定後才會套用到電腦。這些項目會指出目前使用者不應該存取的作業系統功能。

##### 應用系統原則

Microsoft 的《Microsoft Windows  NT 4.0 設定檔與原則指南》(英文) 白皮書中詳細說明了使用者設定檔與系統原則、使用方式以及如何相輔相成 (如需取得此白皮書，請參閱＜其他資訊＞章節)。

系統原則能讓您更精確地控制舊版桌面與使用者介面。如果您已經熟悉 Windows 2000 的群組原則，就代表您已經瞭解系統原則的基本功能。簡單來說，系統原則能讓您進行以下作業：

-   指定允許使用者登入前顯示的畫面或免責聲明，例如顯示任何適用的合法使用政策等等。

-   防止登入對話方塊顯示任何有安全性顧慮的資訊，例如前一位登入的使用者帳戶名稱或關機按鈕。

-   指定登入指令檔、快取漫遊設定檔、慢速網路偵測、啟動畫面以及 \[歡迎\] 提示的行為。

-   指定 \[開始\] 功能表上多個共用資料夾的位置，包括能夠確保特定程式每次登入時都會執行的 \[啟動\] 資料夾。

-   限制桌面的外觀：背景、圖示、顏色以及 \[開始\] 功能表上可用的命令。

-   指定各種檔案系統相關功能的行為，如殼層延伸、唯讀檔案存取時間更新以及長檔名等。

-   限制網路資源和可用磁碟機代號的存取，以及 Windows 檔案總管中磁碟機對應的能力。如需更多資訊，請參閱知識庫文件編號 156698＜使用系統原則禁止網路資源存取＞(英文)，網址為：[http://support.micrisoft.com/?kbid=156698](http://support.microsoft.com/?kbid=156698)，以及編號 220955＜用系統原則隱藏特定磁碟機代號＞(英文)，網址為：<http://support.microsoft.com/?kbid=220955>。

-   限制建立隱藏的檔案共用。

-   指定並限制印表機、簡易網路管理通訊協定 (SNMP) 及 RRAS 設定。

-   限制殼層啟動特定執行檔。

-   限制啟用登錄編輯程式與命令提示字元。

系統原則與群組原則有許多相似之處，但也有一些重要的限制與差異：

-   系統原則沒有階層式架構。因為 Windows NT 網域模型的平面特性，所以無法像在 Active Directory 下使用群組原則一般，定義重疊而相輔的系統原則。您可以為個別使用者、預設使用者、群組、個別電腦及預設電腦定義原則。本章的下個部分將會說明這些原則是如何套用的。

-   系統原則會直接變更所對應的登錄區， 原則在因故 (例如被另一原則取代) 變更之前會一直保持有效。Active Directory 的群組原則會變更登錄的特定部份，Windows 會用這個部份的設定覆寫一般的登錄項目。系統原則這種直接寫入登錄的方式稱為指定 (tattoo)，也代表系統原則不能對管理的設定做任何假定。

系統原則是使用系統原則編輯器 (SPE) 公用程式與管理範本檔案 (.adm) 建立的。這些範本檔案提供了 SPE 類別和子類別、登錄機碼與數值，用來控制各種特殊設定、選項、限制以及預設值。您也可以建立自訂的範本檔案，加入 SPE 隨附的預設範本內未涵蓋的登錄設定。

執行 SPE 並建立一組將和特定使用者、群組、電腦或預設使用者或電腦產生關連的設定後，就會產生名為 Ntconfig.pol 的原則檔案。Windows NT 系統預設會從網域控制站上的 NETLOGON 共用下載合適的原則檔案。原則檔案應該要存放在 PDC 的 NETLOGON 共用上，這裡的內容會透過目錄複寫器服務複製到 BDC 上。執行 Windows NT 的電腦可以從登入的網域控制站下載所有合適的原則。不論網域控制站是 Windows NT、Windows 2000 或 Windows Server 2003，以上行為都會相同，因為 Windows 2000、Windows XP 及 WIndows Server 2003 用戶端會略過 NETLOGON 共用裡的原則檔案，優先選擇整合於 Active Directory 的 GPO。

Windows NT 載入及套用系統原則的方式為：

1.  如果存在特定使用者原則，就會載入原則並修改登錄，然後原則處理會跳至步驟 4。

2.  如果有預設使用者原則存在，就會加以載入並套用。

3.  如果有群組原則存在，就會以適用的遞增優先順序載入並套用。如果某個群組原則與預設使用者原則衝突，會以群組原則為優先，除非該原則設定為「忽略」。

4.  如果有特定電腦原則存在，就會載入原則並修改登錄，然後原則處理會跳至步驟 6。

5.  如果有預設電腦原則存在，就會載入原則並修改登錄。

6.  原則套用完畢。

Windows NT 預設會下載並套用系統原則。這個行為的說明可以在知識庫文件編號 168231＜無法在 Windows NT 中套用系統原則＞中找到，網址為：<http://support.microsoft.com/?kbid=168231>。這個行為是受下列登錄值控制的：

**HKEY\_LOCAL\_MACHINE\\System\\CurrentControlSet**
**\\Control\\Update\\UpdateMode** (REG\_DWORD)

-   登錄值 **0** 會停用系統原則套用。

-   預設登錄值 **1** 會啟用自動模式。如前所述，Windows 會在進行驗證的網域控制站上尋找 Ntconfig.pol 系統原則檔案。

-   登錄值 **2** 會開啟手動模式。Windows 會先檢查同機碼中的 **NetworkPath** (REG\_SZ) 值，並在該位置尋找原則檔案。

確保系統原則作用正確是很重要的。知識庫文件編號 154120＜為 Windows NT 4.0 使用者設定檔及系統原則偵錯＞(英文) (<http://support.microsoft.com/?kbid=154120>) 說明如何用檢查版本取代 Userenv.dll，以建立可以為原則套用偵錯的記錄檔。這個程序可用於所有 Windows NT 4.0 及其所有 Service Pack 版本，包括 Terminal Server 版本。

雖然說預設的系統原則行為依存於作用中的 Windows NT 網域架構，但執行 Windows 2000、執行 Windows NT 的單機電腦以及本機使用者帳戶資料庫中的使用者，還是能夠使用系統原則。知識庫文件編號 168579＜如何設定本機系統原則＞(英文) (<http://support.microsoft.com/?kbid=168579>) 中有詳細指導，說明設定 Windows NT 系統為本機帳戶資料庫中的使用者提供系統原則的兩種方式。如果您是在 Windows NT 網域裡使用執行 Windows 2000、Windows XP 或 Windows Server 2003 的電腦，請參閱知識庫文件編號 274478＜Windows NT 4.0 網域或工作群組中的 Windows 2000 Professional 用戶端群組原則＞(英文) (<http://support.microsoft.com/?kbid=274478>)，其中說明了讓 Windows NT 網域控制站散發 Windows 2000 相容原則所需的程序。

##### 規劃系統原則部署時的考量

在進行原則開發與部署時，請務必注意系統原則的相關複雜性，以確保最高的安全性。

-   因為 Windows NT 4.0 的系統原則實作方式有許多錯誤，請務必更新至 SP3 (最低限度)，確保已經在系統上安裝所有重要的系統原則相關補充程式。一般而言，這不會有問題 (除非有支援應用程式的特殊需求)，因為其他的安全性需求會要求您將所有 Windows NT 系統更新為 SP6a。

-   系統原則需要最多兩次登入及登出，以確定找到、下載並套用系統原則。

-   因為原則並不會自動從電腦上移除，請為您的系統管理員帳戶建立特定群組原則。這個原則設定最低限度應該去除系統管理員重新取得所需權限的限制，還原所有受限的功能是常見的系統管理員群組原則。

-   小心閱讀原則中的每項設定，確認沒有誤解設定中任何雙重否定的意義。有些設定必須先啟用，才能關閉特定的行為。

-   請小心檢查系統原則檔案的位置。這些檔案應該位於 NETLOGON 共用中，NETLOGON 共用的位置會因主要網域控制站執行 Windows NT 4.0、WIndows 2000 或 Windows Server 2003 而有所不同。

-   請務必確認您的目錄複寫服務功能正常，在 PDC 上的 NETLOGON 共用內容也正確複製到所有 BDC。

-   也請確認每次更新並部署新原則時，原則檔案的修改時間是否隨之更新。部分使用舊版 Service Pack 的用戶端會快取原則檔，然後以修改時間判斷是否要更新檔案。較好的方法是確保所有執行 Windows NT 的電腦至少都更新為 SP3，更新為 SP6a 則更佳。

-   如果混合使用 Windows NT 4.0 及 Windows 2000 或 Windows Server 2003 網域控制站，可以建立複寫服務，橋接 Windows NT 的目錄複寫服務及 Windows 2000 的檔案複寫服務。如需更多關於這個程序的資訊，請參閱知識庫文件編號 317368＜如何：使用 Lbridge.cmd 在 Windows 2000 和 Windows NT 4.0 網域控制站之間複寫系統原則＞(英文)，網址為：<http://support.microsoft.com/?kbid=317368>。

-   至於在 Windows NT 4.0 Terminal Server Edition 上使用系統原則，則另有一些需要更深究的問題存在。如需更多資訊，請參閱知識庫文件編號 192794＜如何為 Terminal Server 套用系統原則＞(英文)，網址為：<http://support.microsoft.com/?kbid=192794>。

請務必記得，系統原則並不足以取代真正應用登錄及檔案系統存取控制清單 (ACL)，您也不能因此跳過其他系統強化措施。舉例來說，假設某個系統的原則限制使用者只能執行 Microsoft Office 應用程式二進位檔案。使用者可以利用 Office 標準的 \[檔案\] 功能表建立新資料夾、將可執行檔 (如 cmd.exe 或任何登錄編輯程式) 複製到可寫入的位置，然後將檔案重新命名為系統原則允許的執行檔名稱，避開原則的限制。

部署系統原則時，必須考量幾個特別的弱點區域，才能使用其他安全性措施補足：

-   系統原則中所有受限制的執行檔都要以完整路徑明確指出，而非依靠預設搜尋路徑。

-   請考慮限制使用 Windows 檔案總管中的 \[工具\] 及 \[檢視\] 功能表， 這些功能表中的選項可以用來避開系統原則的限制。

-   即使無法存取 **RegEdt32** 與 **RegEdit**，還是能夠執行登錄檔案 (.reg)，因為預設的副檔名關連還是存在。

-   預設搜尋路徑內不應該有任何使用者可寫入的目錄 (例如暫存檔目錄與設定檔目錄)。

-   登錄中的 World SID 也不應該讓使用者任意存取。強烈建議您考慮將權限限制為查詢、列舉及讀取。不過這個設定可能會破壞舊應用程式的功能，需要重覆測試才能找出維持功能所需的特定權限。

-   仔細檢查系統目錄裡的所有可執行檔。即使移除了這些檔案的**執行**權限，只要使用者擁有**讀取**權限，就能夠將檔案複製到可以寫入的位置再嘗試執行。

##### 安全性設定管理員

安全性設定管理員 (SCM) 最初是為 Windows 2000 所設計，後來 Microsoft 讓 Windows NT 4.0 SP4 或更新版本都能加以使用。您可以從 SP6a 光碟或是 Microsoft FTP 站台下載取得 SCM。SCM 最主要的工具就是安全性設定編輯器 (SCE)，可以讓您建立並管理安全性範本與系統原則。

使用 SCE 可以執行一些有用的工作， 例如：

-   為執行 Windows NT 的電腦建立指定稽核、使用者權限以及安全性設定的安全性範本。

-   自動將範本套用至網域中的一或多部電腦。

-   掃描一或多部電腦，評估與特定範本間的相符程度。

依照預設，安裝 SCE 時會在 %winnt%\\security\\templates 資料夾新增一組範本。每個範本都是為特定的安全性環境及電腦類型所設計的：

基本範本 (Basic\*4.inf) 會為目標電腦套用標準的安全性設定，其中包括了六星期的密碼使用期限，以及一組基本的登錄機碼、檔案系統與使用者權限。

相容範本 (Comp\*4.inf) 會為電腦套用較基本範本稍強的安全性設定。不過，這組範本會將與較舊版用戶端或應用程式衝突的安全性設定關閉。這組範本的目的是在不引發應用程式相容性問題的前題下提升安全性。

高安全性範本 (HiSec\*.inf) 會為電腦套用更多的安全性原則，包括最短密碼長度由七個字元增為八個，並套用一組限制較多的登錄與檔案系統權限。需要檔案系統、登錄權限或指派使用者權限設定的舊版應用程式，可能會和這組範本衝突。

安全範本 (Secur\*.inf) 是安全性最高的範本，但會啟用伺服器訊息區 (SMB) 簽章等功能，尚未做類似設定的 Windows 95/98 用戶端，與進行這類設定的電腦之間的互通性會受影響。

**表 4.1：Windows NT SCE 工具組隨附的預先定義範本**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >安全性等級</th>
<th style="border:1px solid black;" >保護目標</th>
<th style="border:1px solid black;" >使用檔案</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">基本的安全性</td>
<td style="border:1px solid black;">主要/備份網域控制站</td>
<td style="border:1px solid black;">BasicDC4.inf</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">成員伺服器</td>
<td style="border:1px solid black;">BasicSv4.inf</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">工作站</td>
<td style="border:1px solid black;">BasicWk4.inf</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">較佳的安全性 (同時保持良好的應用程式相容性)</td>
<td style="border:1px solid black;">主要/備份網域控制站</td>
<td style="border:1px solid black;">CompDC4.inf</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">成員伺服器</td>
<td style="border:1px solid black;">CompDC4.inf</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">工作站</td>
<td style="border:1px solid black;">CompWS4.inf</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">高安全性 (較低的應用程式相容性)</td>
<td style="border:1px solid black;">成員伺服器或網域控制站</td>
<td style="border:1px solid black;">HiSecDC4.inf</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">工作站</td>
<td style="border:1px solid black;">HiSecWS4.inf</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">高安全性 (與 Windows 98 之間連接能力較低)</td>
<td style="border:1px solid black;">成員伺服器或網域控制站</td>
<td style="border:1px solid black;">SecurDC4.inf</td>
</tr>
</tbody>
</table>
  
因為 SCM 是為 Windows 2000 所設計的，所以介面與群組原則的介面非常相似， 其中包括將整合的 Windows NT ACL 編輯器更新為 Windows 2000 所用的 ACL 編輯器。因為 SCM 需要 Windows 2000 的 ACL 繼承模型，而這個模型會動態套用繼承的 ACL，所以這個改變對整個系統的 ACL 行為都有重大影響。新的子系統不會將存取控制項目 (ACE) 從父物件複製到子物件，而會參照**允許繼承權限**原則，判斷原則是否啟用。新的繼承系統除了用於一般 Windows 檔案總管裡的 ACL 編輯器，也用於 SCM 所套用的原則。但是，這個繼承系統並不會直接由登錄編輯程式 (regedt32.exe) 存取，因此 SCM 所套用變更登錄中 ACL 的原則能夠建立登錄編輯程式無法控制的 ACL。如需更多關於新版 ACL 編輯器系統及其影響 (包括停用該系統，同時也會停用 SCM) 的資訊，請參閱知識庫文件編號 195509＜安裝 SP4 的安全性設定管理員會變更 Windows NT 4.0 ACL 編緝器＞(英文)，網址為：<http://support.microsoft.com/?kbid=195509>。
  
SCM 可以讓您設定下列功能：
  
-   帳戶原則，包括密碼及帳戶鎖定原則選項。
  
-   本機原則，包括稽核、使用者權限指派以及安全性原則選項。
  
-   事件記錄檔原則。
  
-   能夠鎖定指定群組成員資格的限制群組。
  
-   提供各個服務及傳輸設定選項的系統服務。
  
-   登錄權限。
  
-   檔案系統權限。
  
SCM 的 GUI 提供了已定義原則的清單，儲存在 %winnt%\\security\\templates 資料夾中。這個圖形使用者介面 (GUI) 可以讓您定義、編輯並維護多個適用於各個舊系統的原則，同時也能分析系統並比較與特定原則範本的相容性。
  
SCM 與 Active Directory 原則之間最主要的差異，就是 Windows NT 無法在一群相關電腦上自動部署原則範本，您必須設法將設定範本發佈到所要的電腦。發佈需要以手動方式或使用指令碼進行，配合其他的機制以確保定期自動套用原則。
  
使用 SCM 在所有系統上製作並部署下列基本帳戶原則變更：
  
-   使用 SCM 將來賓帳戶停用並重新命名 (透過 \[本機原則\] | \[安全性選項\] | \[變更來賓帳戶名稱\] 設定)。就算已經停用，也請確認使用增強式密碼。定期稽核以確認帳戶不屬於 Domain Guests 外的任何群組，Domain Guests 群組除了本帳戶外，也不應該有其他任何成員。
  
-   將系統管理員帳戶重新命名為較不明顯的名字 (使用 \[本機原則\] | \[安全性選項\] | \[變更系統管理員密碼\] 進行設定)，然後另外建立名稱為 Administrator 但不具備任何權限的帳戶做為誘餌。請為這個誘餌帳戶設定增強式密碼並停用帳戶，和處理來賓帳戶的方式一樣。請不要在備註欄標示這是誘餌帳戶，這樣一來建立這個帳戶也沒有意義了。您可能也需要定期稽核這個帳戶，以確保它未被加入任何群組；另外也記得檢查嘗試進入這個帳戶的記錄。雖然這個措施無法預防網路內部的攻擊者用公開的 SID 找出真正的系統管理員帳戶，還是能延緩外部業餘攻擊者的攻擊嘗試，讓您提早得到警告。
  
-   禁止為匿名使用者 (Null 工作階段) 列舉帳戶名稱和檔案共用。Windows 預設會允許遠端系統無憑證連結並列舉這些資訊。這是常見的一種攻擊途徑。在 \[本機原則\] 節點下的 \[安全性原則\] 物件中，選用 \[禁止匿名者列舉帳戶名稱和共用\] 設定。
  
#### 選擇 NTLM 驗證層級
  
在 SP4 之前的 Windows NT 4.0 用戶端使用的是 NTLMv1 驗證，這個驗證方式已被證實含有設計上的缺陷，可能會遭到攻擊者攔截解密。NTLM 驗證是為了接替能力更有限的 LAN Manager (LM) 驗證協定而設計的，LM 協定需要將所有的密碼資訊儲存在較弱的 LM 雜湊中 (稍後將再加以說明)， 但是 LM 雜湊很容易破解，容易導致密碼外洩。
  
LM、NTLM 以及 NTLMv2 用於驗證下列作業：
  
-   加入網域。
  
-   Active Directory 樹系之間的驗證作業。
  
-   Windows NT 4.0 網域的驗證作業。
  
-   執行 Windows NT 4.0 或 Windows 98 且做為檔案或列印伺服器的電腦所需的驗證作業。
  
-   非網域成員的伺服器的驗證作業。
  
因為 Trey 混合使用執行 Windows Server 2003 (做為網域控制站)、Windows 98 與 Windows NT 4.0 電腦，因此選用的 NTLM 驗證層級需要在讓現有用戶端正常作業的前提下，提供最佳的安全性。Windows NT、Windows 2000 以及 Windows Server 2003 支援 6 個層級的 LM 相容性，由 **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control**  
**\\LSA\\LMCompatibilityLevel** 登錄機碼所控制：
  
-   **0 (傳送 LM 與 NTLM 回應)**。這個設定有最高的互通性，因為用戶端可以使用 LM 或任何版本的 NTLM 進行驗證， 不過這個設定會允許網路進行不安全的 LM 通訊。
  
-   **1 (傳送 LM 與 NTLM，使用 NTLMv2 工作階段安全性進行交涉)**。這個設定的安全性較高，但是在 Windows 98 上需要使用 DSClient 軟體。選用這個設定時，只要雙方都支援，就可以使用 NTLMv2 進行交涉。這個設定最適合用於部署階段；所有使用 DSClient 的電腦都會使用 NTLMv2，同時使用較舊版 Windows 的用戶端也能夠進行驗證。
  
-   **2 (僅傳送 NTLM 回應)**。這個設定會讓未安裝 DSClient 的 Windows 98 用戶端無法使用，因為伺服器不會回應來自執行 Windows 98 且未修改電腦的 LM 要求。
  
-   **3 (僅傳送 NTLMv2 回應)**。當所有執行 Windows NT 4.0 SP4 之前版本的電腦都安裝 DSClient 時，才能使用這個設定。
  
-   **4 (僅傳送 NTLMv2 回應，拒絕 LM)**。與前一設定大致相同，不同處是收到 LM 驗證要求時也不會送出 NTLMv2 回應。
  
-   **5 (僅傳送 NTLMv2 回應，拒絕 LM 與 NTLM)**。與前一設定大致相同，不同處是會一併忽略 NTLM 要求。這個設定只適合所有電腦都使用 Windows 2000 或更新版本 (或安裝了 DSClient 的 Windows 98) 的網路。
  
##### 升級 Windows 98 的 NTLM 驗證
  
DSClient 擴充功能讓 Windows 98 系統也可以使用 NTLMv2 驗證。依照預設，NTLMv2 工作階段安全性加密的最大金鑰長度為 56 位元。要啟用 128 位元 NTLMv2 支援，必須先安裝 Internet Explorer 4 或更新版本，並確認已安裝設定 128 位元支援。這些準備工作必須在安裝 DSClient 之前先做好。
  
將 DSClient 軟體發佈至用戶端電腦後，還可以限制驗證時使用的 LM 協定系列版本。您必須在所有的網域控制站及任何提供遠端驗證帳戶的伺服器上設定這些限制。
  
##### 升級 Windows NT 4.0 的 NTLM 驗證
  
Windows NT 4.0 SP4 與更新版本能夠選擇性使用及回應 LM、NTLM 以及 NTLMv2 驗證要求。這個設定需要在登錄新增機碼 (詳見後面實作章節)。Trey 要在 Windows NT 系統上將相容性層級設為 5 (僅允許 NTLMv2)，但等到所有 Windows 98 系統都安裝 DSClient 擴充功能後才進行這個變更。
  
##### 升級 Windows 2000 和 Windows Server 2003 的 NTLM 驗證
  
Trey 的 IT 系統管理員在公司的網域控制站建立了新的 GPO，為電腦及網域控制站設定 NTLM 驗證層級，並將其指派給 Domain Controllers 組織單位 (OU)。他們的做法是修改 **電腦組態\\Windows 設定\\安全性設定\\本機原則\\安全性選項\\LAN Manager 驗證層級**的設定。請確認在網域控制站使用**網域控制站**原則，在 Active Directory 成員使用**網域**原則，且在單機電腦上或是 Windows NT 網域成員電腦上使用本機原則。
  
將 DSClient 完全部署至所有 Windows 98 系統後，就可以將 LM 驗證層級變更為 **3**、**4** 或 **5**，這些層級都不允許使用 LM 驗證。在此之前，所有使用較早期 Windows 版本且未安裝 DSClient 的系統都無法存取任何網路資料。
  
因為 Trey 的環境中包含了 Windows 98 用戶端，這些用戶端都已經安裝了 DSClient 擴充功能，因此 Trey 在 Windows NT 電腦 (Windows NT、Windows 2000 及 Windows XP) 上將層級設為 **5**，且在執行 Windows 98 的電腦上將層級設為 **3**。否則，在*不*使用 Windows 98 的電腦上設定高於 **3** 的層級，沒有 DSClient 擴充功能的電腦就無法驗證。
  
如需更多關於確保本設定能夠用於混用 Windows 2000 及 Windows NT 4.0 網路的 Hotfix 資訊，請參閱知識庫文件編號 305379＜Windows  NT 4.0 網域中 Windows  2000 電腦 NTLM 2 層級大於 2 時的驗證問題＞(英文)，網址為：<http://support.microsoft.com/?kbid=305379>。
  
Windows 系統會建立稱為安全通道的通訊管道，在信任的網域裡驗證電腦帳戶與使用者帳戶。安全通道可以預防攔截式攻擊，也讓用戶端能夠存取信任的網域裡的帳戶資料庫。安全通道可以數位加密或簽章，但所有的網域控制站必須執行 Windows NT 4.0 SP6a 或更新版本。由於安全通道簽章不但會影響網域裡的所有用戶端，也會影響信任網域裡的用戶端，啟用這個功能之前請三思。
  
#### 定義有效密碼及鎖定原則
  
最基本的安全準則之一是避免傳輸或儲存純文字密碼。以純文字儲存的密碼安全性極低，只要檢視 SAM 檔案或探查網路工作階段，即可取得密碼。現在的 Windows 驗證協定使用稱為雜湊的加密演算法保護所有驗證憑證的傳輸，並在使用者輸入密碼時開始加密儲存。不過，還是必須定義控制密碼長度和強度，以及在鎖定帳戶前允許登入失敗次數的相關原則。
  
Microsoft 資訊安全指導套件 (Security Guidance Kit, SGK) 可以從 <http://www.microsoft.com/security/guidance/order/default.mspx> 取得，其中有參考文件，可以幫助您選擇、實作增強性密碼及帳戶鎖定原則。另外《帳戶密碼與原則》白皮書 ([http://www.microsoft.com/technet/prodtechnol/windowsserver2003/  
technologies/security/bpactlck.mspx](http://www.microsoft.com/technet/prodtechnol/windowsserver2003/technologies/security/bpactlck.mspx)) 中可以找到更多相關導引。
  
#### 強化檔案系統
  
在強化開機程序的同時，也必須提升組織裡執行 Windows NT 4.0 電腦中檔案系統及儲存裝置的安全性。
  
第一個關鍵步驟是確認所有執行 Windows NT 4.0 的電腦都使用 NTFS 檔案系統。除了 Windows NT、Windows 98 及後續版本提供的共用層級權限外，NTFS 還提供檔案與資料夾使用權限。使用 NTFS 權限可以限制使用者只能讀取其他使用者的檔案，也讓得以實際存取主控台的攻擊者更難偷取或修改資料 (必須用另一作業系統開機)。Windows NT 包含一個命令，可以在不造成破壞的前提下將 檔案配置表 (FAT) 或 FAT32 磁碟區轉換為 NTFS 格式，不過轉換時需要獨佔存取該磁碟區。
  
使用轉換公用程式將磁碟區轉換成 NTFS 後，預設套用的權限為**任何人：完全控制**。因為這個使用權限過於寬鬆，請務必再做調整。現有的 NTFS 系統權限也可能太過寬鬆。
  
美國國家安全局 (NSA) 為 Windows NT 伺服器與工作站開發了一組建議權限，可以在《*強化 Microsoft Windows  NT 網路指南*》中找到。您可以用指令碼配合 xcacls 工具手動套用這些建議 (請參閱知識庫文件編號 318754＜如何：使用 Xcacls.exe 修改 NTFS 權限＞(英文)，網址為 <http://support.microsoft.com/?kbid=318754>)，或使用預先定義的 SCM 範本。該指南第 11 與第 13 章所述的建議涵蓋廣泛，請務必參照指南，依照說明加以實作。
  
#### 強化服務
  
有幾項設定變更是針對安全服務與帳戶的，這些變更通常都適用於所有的 Windows NT 環境。
  
在 Windows NT 4.0 SP3 的許多改良之中，其中一項是建立 Authenticated Users 安全性群組。這個群組是用來取代 Everyone 安全性主體，在不論驗證狀態為何均禁止任何使用者或程序存取檔案與服務時加以使用。除非真的需要允許匿名連接，否則請將建立及管理的每個檔案 ACL 都替換成這個群組。這對大部份的服務來說並不是必要的，例如 IIS 就會將所有匿名要求對應至指定的帳戶。不過協力廠商的應用程式需要仔細測試，因為它們可能需要加入 Everyone 群組。
  
除了 Authenticated Users 群組外，您也需要在伺服器上使用以下登錄機碼停用匿名連接登錄，並限制匿名使用者列舉網域使用者帳戶清單及共用清單：
  
**HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\LSA**
  
**RestrictAnonymous** (REG\_DWORD)
  
-   數值 **0** 會停用這個限制，並允許匿名使用者 (Null 工作階段) 列舉使用者清單及共用清單。
  
-   數值 **1** 會啟用這個限制；不允許 Null 工作階段列舉使用者清單或共用清單。
  
**RestrictNullSessAccess** (REG\_DWORD)
  
-   數值 **0** 會停用這個限制，並允許匿名使用者 (Null 工作階段) 連接至登錄。
  
-   數值 **1** 會啟用這個限制；不允許 Null 工作階段連接至登錄。
  
知識庫文件編號 143474＜限制匿名使用者可用的資訊＞(英文) (<http://support.microsoft.com/?kbid=143474>) 說明如何使用 Authenticated Users 群組配合手動登錄編輯，完全禁止匿名連接登錄或列舉使用者與共用。知識庫文件編號 153183＜如何限制從遠端電腦存取登錄＞(<http://support.microsoft.com/?kbid=153183>) 提供了限制驗證的使用者遠端存取登錄的相關資訊。
  
另一項必須做的重要變更 (在網域控制站尤其重要) 就是充分保護目錄複寫服務 (DRS)。這個服務讓指定的目錄內容可以複製到多個不同的伺服器，這是確保系統原則及其他重要檔案傳播至所有網域控制站的重要服務， 在維護重要應用程式的檔案服務負載平衡方面也非常有用。
  
按一下 \[網域伺服器管理員\] 中的 \[複寫\] 按鈕，可以設定複寫連線的設定。每個複寫合作關係中，都有一個匯出者 (來源) 和一個匯入者 (目標)。每個合作關係的細節，都必需在連線的兩端各自做好設定 (類似網域間建立信任關係的方式)。
  
依照預設，DRS 會使用本機系統帳戶，請馬上修改這個設定。為 DRS 建立個別的網域使用者帳戶，就能在所有的電腦上使用相同的帳戶，請不要使用本機帳戶。建立帳戶後，可以使用服務管理員確認 DRS 是以這個帳戶的身份執行，而非本機系統帳戶。
  
在 Windows NT 系統上，有許多預設啟用的服務可以停用以減少電腦的威脅；其他的服務可以設定以無權限的帳戶執行，而不使用本機系統帳戶。如需更多關於維護 DRS 安全及停用不需要的服務 (包括一整套根據不同電腦角色建議的設定) 資訊，請參閱 Microsoft TechNet 網站上的＜*Microsoft NT 4.0 安全性、稽核和控制技術參考*＞(英文) 第 10 章，網址為：[http://www.microsoft.com/technet/prodtechnol/winntas  
/maintain/nt4sac/sacch10.mspx](http://www.microsoft.com/technet/prodtechnol/winntas/maintain/nt4sac/sacch10.mspx)。
  
#### 其他強化措施
  
在不同的環境下，可能有其他合適的強化措施。
  
##### 停用自動產生 8.3 檔名
  
Windows NT 支援 8.3 檔名格式，以相容於舊版的 16 位元應用程式。8.3 檔名格式允許最長八個字元的檔名，也就是說攻擊者只需要八個字元即可參照至檔名可能長達 20 個字元的檔案。舉例來說，名為 Thisisalongfilename.doc 的檔案，可以使用其 8.3 格式檔名 (Thisis~1.doc) 加以參照。如果您不使用 16 位元的應用程式，就可以關閉這項功能。在 NTFS 磁碟分割中停用簡短名稱產生功能，也可以提升目錄列舉的效能。
  
具有長檔名的資料檔和應用程式一般不容易成為攻擊目標，但攻擊者卻可以利用簡短的檔名存取具有長檔名的檔案。如果攻擊者可以存取檔案系統，則能夠存取資料或執行應用程式。
  
您可以透過下列登錄項目控制這個設定：**HKEY\_LOCAL\_MACHINE\\System\\CurrentControlSet\\Control\\FileSystem\\NtfsDisable8dot3NameCreation**
  
如果您在做了這項修改的電腦上儲存檔名超過 8.3 格式允許長度的檔案，那麼組織中其他電腦上的 16 位元應用程式將無法存取這些檔案。在已經有自動產生的 8.3 名稱格式檔案的現有伺服器上套用這項設定，並不能移除已經產生的檔名。如果要移除現有的 8.3 檔名，必須將這些檔案複製到該伺服器外，從原始位置刪除這些檔案，再將它們複製回原來位置。
  
##### 停用自動執行
  
自動執行功能會在媒體插入光碟機後，自動讀取內容， 因此會自動執行媒體中程式的安裝檔，或播放媒體中的聲音。為了防止將 CD 或 DVD 放入電腦時可能自動執行惡意程式，群組原則會停用所有磁碟機的自動執行功能。
  
如果能夠實際存取系統的攻擊者，將啟用自動執行的媒體方入電腦，系統將會啟動在目前登入的使用者內容中執行的惡意程式碼。
  
您可以透過下列登錄項目控制這個設定：**HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet**  
**\\Services\\CDROM\\Autorun**
  
修改這個設定後，在電腦光碟機中放入自動執行的光碟時，不會啟動自動執行功能。
  
##### 移除 OS/2 及 POSIX 子系統
  
OS/2 是 Microsoft 具保護模式、虛擬記憶體及多工能力的作業系統系列，用於配備 Intel 80286 及 80386 處理器的個人電腦。Portable Operating System Interface for UNIX (POSIX) 是一項美國電機電子工程師學會 (IEEE) 標準，定義了一套作業系統服務。如果伺服器需要與 OS/2 用戶端做大量互動，就需要 OS/2 子系統；要執行使用 POSIX 服務的應用程式，則必需使用 POSIX 子系統。
  
這些子系統有可能會造成程度輕微的安全性風險，因為有的程序有可能會在登入後持續執行。也就是說，如果使用者啟動了某項程序後登出，那麼下一個登入系統的使用者可能可以存取先前使用者的程序， 而先前使用者啟動的程序可能還保留該使用者的系統權限。
  
要停用這些子系統，請將這些子系統所需的二進位檔與下列登錄項目一同刪除：
  
-   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft**  
    **\\OS/2 Subsystem for NT** 登錄機碼及子機碼。
  
-   **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet**  
    **\\Control\\Session Manager\\Environment\\OS2LibPath** 登錄機碼。
  
-   POSIX 以及 **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\**  
    **Control\\SessionManager\\Environment\\Subsystems** 登錄機碼的 OS/2 子機碼。
  
-   **\\winnt\\system32\\os2** 目錄及子目錄。
  
依存於 OS/2 或 POSIX 子系統的應用程式也無法再運作。
  
##### 提升物件保護層級
  
Windows NT 核心程式在某些情況下可能允許呼叫者變更核心物件的屬性。在某些情況下，這可能會讓惡意的呼叫者提高權限。
  
您可以透過下列登錄項目控制這個設定：
  
-   **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet**  
    **\\Control\\Session Manager\\EnhancedSecurityLevel**
  
這項變更僅會允許核心模式程式碼在目前的程序中變更核心物件的屬性，
  
對使用者模式應用程式並沒有任何影響。
  
##### 禁止使用者新增印表機驅動程式
  
Windows NT 預設會允許使用者安裝額外的印表機驅動程式。在某些情況下，這可能會讓惡意或設計不良的驅動程式提升權限。
  
您可以透過下列登錄項目控制這個設定：
  
-   **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet**  
    **\\Control\\Print\\Providers\\LanMan Print Services**  
    **\\Servers\\AddPrinterDrivers**
  
這項變更僅會允許 Printer Operators 和 Administrator 群組的成員新增印表機驅動程式，
  
對使用者模式應用程式並沒有任何影響。
  
##### 確認停用系統管理員自動登入
  
Windows NT 可以設定在電腦重新開機時自動登入系統管理員的帳戶。如此不但將主控台曝露在外，還會建立新的登錄機碼，以純文字格式儲存系統管理員的密碼。知識庫文件編號 97597＜如何啟用 Windows NT 3.x 和 4.0 的自動登入＞(<http://support.microsoft.com/?kbid=97597>) 中有這個設定的相關說明。
  
您可以透過下列登錄項目控制這個設定：
  
-   **HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\WindowsNT**  
    **\\CurrentVersion\\Winlogon\\AutoAdminLogon**
  
-   **HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\WindowsNT**  
    **\\CurrentVersion\\Winlogon\\DefaultPassword**
  
對使用者模式應用程式並沒有任何影響。
  
##### 停用 Novell 用戶端通知
  
密碼變更時，Windows NT 預設會通知 Novell 網路用戶端 (FPNWCLNT.DLL)，但除非安裝了用戶端，否則不會安裝這個動態函式庫 (DLL)。也因此攻擊者可以設計一個替代 DLL，攔截所有使用者的密碼變更事件。
  
若要停用這個行為，請確認 **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet**  
**\\Control\\LSA\\Notification Packages** 登錄機碼中沒有 FPNWCLNT 這個值。
  
使用 Netware 的環境中會停用 Windows 與 Netware 間的密碼同步處理。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 實作
  
#### 實作必要條件
  
您必需先依第 2 章＜Trey Research 安全性風險管理法則應用案例＞所述，建立起基本的 Trey Research 基礎結構，下列的實作細節才會起作用。
  
#### 實作概觀
  
實作這個解決方案，需要進行下列動作：
  
-   建立基礎安裝並為作業系統安裝補充程式
  
-   啟用 Syskey
  
-   減少開機延遲時間
  
-   安裝 SCM
  
-   載入 SCM 嵌入式管理單元
  
-   套用 Trey 原則範本
  
-   防止系統儲存 LM 密碼雜湊
  
-   設定 NTLM 驗證層級
  
-   將伺服器磁碟區轉換成 NTFS
  
-   進行其他強化措施
  
#### 建立作業系統基礎安裝
  
每次架設新電腦或在現有系統上重新安裝作業系統時，都必需安裝正確的安全性補充程式，以確保電腦有足夠的安全性。第 6 章＜補充程式管理＞會深入討論補充程式管理這個複雜的主題；但是如果要保護執行 Windows NT 的電腦，就必須先經過新系統基礎安裝這道程序。組織中每部執行 Windows NT 的電腦都應該安裝下列補充程式：
  
-   Windows NT 4.0 Service Pack 6a (SP6a)，這是 Windows NT 4.0 最新的 Service Pack， 其中包括一套經過反覆測試的完整修正程式，可以一次安裝完成。Windows NT 4.0 SP6a 發佈後，美國已經修改了出口密碼編譯軟體的相關法令。升級為高加密版本的 SP6a，可能可以提升您 Windows NT 4.0 系統的加密能力。只要在標準加密版本的系統上安裝高加密版本的 SP6a，就會自動升級整個作業系統。Windows NT 4.0 Service Pack 6a 可由此取得：[http://www.microsoft.com/ntserver/nts/downloads  
    /recommended/sp6/128bitx86/](http://www.microsoft.com/ntserver/nts/downloads/recommended/sp6/128bitx86/)。
  
**檢查 Windows NT 4.0 的加密版本**
  
1.  以系統管理員的身份登入執行 Windows NT 4.0 的目標電腦。
  
2.  用 Windows 檔案總管開啟 \\winnt\\system32 資料夾。
  
3.  找出 Schannel.dll 檔案，選取後按一下 \[檔案\]，然後再按一下 \[內容\]。
  
4.  按一下 \[版本\] 索引標籤。
  
5.  檢視 \[描述\] 欄的內容。
  
    如果內容為 Export Version，那麼您使用的是標準加密版本；如果是 U.S. domestic version，則代表您使用的是高加密版本。
  
    -   Windows NT 4.0 Service Pack 6a 後續安全性彙總套件 (SRP) 含有數個原始 SP6a 發佈後才發佈的補充程式，必須先安裝這個彙總套件，才能從 Windows Update 安裝後續的補充程式。以上資訊在知識庫文件編號 299444＜Windows NT 4.0 Service Pack 6a 後續安全性彙總套件 (SRP)＞(英文) (<http://support.microsoft.com/?kbid=299444>) 中有相關說明。安全性彙總套件可以從 [http://download.microsoft.com/download  
        /winntsp/Patch/q299444/NT4/  
        EN-US/Q299444i.exe](http://download.microsoft.com/download/winntsp/patch/q299444/nt4/en-us/q299444i.exe) 下載。
  
    -   Microsoft 發佈 SRP 之後便沒有再為 Windows NT 4.0 發佈整合的 SRP 或 Service Pack。但是作業系統的個別元件、Internet Explorer，以及附加公用程式 (例如，路由及遠端存取服務 (RRAS) 和 Internet Information Services (IIS)) 等都有更新。您可以從 Microsoft TechNet 取得最新的補充程式清單，或到 Windows Update 手動檢視可用的補充程式清單。
  
    -   目前版本為 Internet Explorer 6.0 Service Pack 1 (SP1)，可從 <http://www.microsoft.com/windows/ie/> 取得，其中包含有數百個安全性及功能性更新。您可以根據環境選擇直接從 Microsoft 網站下載 Internet Explorer、訂購光碟，或利用 Internet Explorer Administration Kit (<http://www.microsoft.com/windows/ieak/>) 為多部電腦進行安裝。
  
因為 Windows NT 上市已久，Trey 的 IT 人員已經為所有執行 Windows NT 的電腦安裝了 SP6a 和 SRP。可是，由於缺乏一致的政策確保其他需要的 Microsoft 補充程式都正確安裝，因此公司開始採用第 6 章＜補充程式管理＞所述的補充程式管理方式。
  
#### 啟用 Syskey
  
您必須啟用 Syskey，讓電腦 SAM 進行加密保護。Trey 選擇為公司裡所有執行 Windows NT 的電腦、伺服器與工作站套用這個措施。
  
**啟用 Syskey**
  
1.  以系統管理員的身份登入執行 Windows NT 4.0 的目標電腦。
  
2.  從命令提示字元或使用 \[執行\] 命令，啟動 Rdisk.exe 公用程式。
  
3.  Rdisk 啟動後，按一下 \[Update Repair Info\] 按鈕，然後在出現提示時按一下 \[Yes\]。
  
4.  修復資訊更新完成後，請在軟碟機插入空白磁片，然後按一下 \[Repair Disk Utility\] 對話方塊中的 \[Yes\]。
  
5.  5. 按一下 \[OK\] 確認要建立修復磁片。
  
6.  磁片建立完畢後，按一下 \[OK\] 確認安全性警告，然後按一下 \[Exit\] 關閉 Rdisk 公用程式。
  
7.  啟動 Syskey.exe 公用程式。
  
8.  當 \[設定 Windows NT 帳戶資料庫安全性\] 視窗出現時，按一下 \[啟用加密\] 按鈕，然後按一下 \[確定\]。
  
9.  按一下確認對話方塊中的 \[確定\]。
  
10. 在 \[帳戶資料庫金鑰\] 對話方塊裡，按一下 \[將啟動金鑰存放在本機上\] (請見圖 4.1)，然後按一下 \[確定\]。
  
11. \[成功\] 對話方塊出現時，按一下 \[確定\]。
  
12. 重新啟動電腦。
  
    **注意：**在網域控制站上，Rdisk 所蒐集的修復資料可能超過一片磁片的容量，但相同的資料也會存在 **%systemroot%\\repair** 目錄中。最新版的 ERD 可以在 Syskey 發生問題時迅速恢復正常作業。如需更多關於 Rdisk /s 命令的資訊，請參閱知識庫文件編號 122857＜Windows NT 中的 RDISK /S 及 RDISK /S- 選項＞(英文)，網址為：<http://support.microsoft.com/?kbid=122857>。
  
    **注意：**如需更多關於 Syskey 如何保護 SAM 資料不受攻擊的資訊，請參閱知識庫文件編號 143475＜Windows NT「系統金鑰」可讓「安全性帳戶管理員」(SAM) 受到堅固加密技術的保護＞，網址為：<http://support.microsoft.com/?kbid=143475>。
  
#### 減少開機延遲時間
  
這裡說明如何變更開機延遲時間值。
  
**減少開機延遲時間**
  
1.  以系統管理員的身份開啟命令提示字元。
  
2.  切換至系統磁碟區的根目錄 (通常是 C:\\)。
  
3.  使用 **attrib** 命令重設 **Boot.ini** 檔案的唯讀、隱藏以及系統屬性：
  
    ```  
 attrib –s –h –r boot.ini   
```
  
4.  以文字編輯程式 (如 \[記事本\]) 開啟 **Boot.ini** 檔案。
  
5.  找出 **timeout=30** 那一行，然後將 **timeout** 值設改成 **0**。
  
6.  儲存檔案，然後關閉文字編輯程式。
  
7.  使用 **attrib** 命令還原 **Boot.ini** 檔案的唯讀、隱藏以及系統屬性：
  
    ```  
 attrib +s +h +r boot.ini   
```
  
#### 安裝 SCM
  
下列程序說明如何安裝 SCM 工具。只要是執行 Windows NT 4.0 SP4 或更新版本的電腦就可以使用 SCM，不論是伺服器還是工作站版本。為了方便使用，Trey 的 IT 人員在個人工作站上安裝了 SCM，以直接對網域裡任何 Windows NT 4.0 電腦執行 SCM。
  
**安裝 SCM 軟體**
  
1.  以系統管理員的身份開啟 Windows 檔案總管。
  
2.  建立 C:\\temp (如果原本不存在)。
  
3.  從 [http://www.microsoft.com/ntserver/nts  
    /downloads/recommended/scm/default.asp](http://www.microsoft.com/ntserver/nts/downloads/recommended/scm/default.asp) 下載 SCM 安裝程式並存到 C:\\Temp。
  
4.  打開 C:\\Temp 然後按兩下 **Scesp4i.exe** 應用程式。
  
5.  安裝程式提示時，指定暫存檔案路徑 C:\\Temp\\scminstall 放置解壓縮支援檔案，然後按一下 \[確定\]。
  
6.  以檔案總管開啟 C:\\Temp\\scminstall。
  
7.  按兩下 **Mssce** 公用程式，安裝 SCE 以及 GUI 版 SCE 所需的 Microsoft Management Console (MMC) 工具。安裝程式會自動將 SCM 元件放置在電腦裡正確的安裝位置。
  
#### 載入 SCM 嵌入式管理單元
  
在工作站或伺服器上安裝 SCM 後，可以直接啟動。以下程序說明如何將 SCM 嵌入式管理單元載入 MMC。
  
**載入 SCM 嵌入式管理單元**
  
1.  以系統管理員的身份登入已安裝 SCM 的電腦。
  
2.  啟動 MMC。
  
3.  選擇 \[主控台\]，然後選擇 \[新增/移除嵌入式管理單元\]。
  
4.  **按一下** \[新增\]。
  
5.  選擇 \[安全性設定管理員\]。
  
6.  按一下 \[確定\]，然後再按一下 \[確定\]。
  
#### 套用 Trey 原則範本
  
以下程序說明如何用 SCE GUI 以及命令列介面 (CLI) 工具套用 Trey 原則範本。Trey 決定使用 Comp\* 系列範本，因為這組範本提供了回溯相容性與安全性之間最佳的平衡點。
  
**若要用 SCE GUI 自訂原則範本**
  
1.  登入測試用的 Windows NT 4.0 工作站。
  
2.  備份 %systemroot%\\security\\templates\\compws4.inf 以及 %systemroot%\\security\\templates\\compdc4.inf 兩個檔案。
  
3.  以 \[記事本\] 開啟 %systemroot%\\security\\templates\\compws4.inf。
  
4.  搜尋含有 **MACHINE\\System\\CurrentControlSet\\Services\\Rdr\\Parameters\\EnableSecuritySignature** 的一行。
  
5.  修改內容，將 **EnableSecuritySignature**的值改成 **1**。
  
6.  儲存檔案，然後關閉 \[記事本\] 。
  
7.  以 \[記事本\] 開啟 %systemroot%\\security\\templates\\compdc4.inf。
  
8.  為新檔案重複步驟 4 至 6。
  
**從 SCE GUI 套用原則範本**
  
1.  以系統管理員的身份啟動安全性設定管理員。
  
2.  選擇 \[安全性設定管理員\] 節點。
  
3.  選擇 \[設定\] 節點。
  
4.  選擇預設設定檔目錄 (%systemroot%\\security\\templates) 以顯示設定檔範本。
  
5.  選擇要使用的設定檔 (compws4.inf 或 compdc4.inf)。
  
6.  熟悉一下原則範本裡的各個物件和設定。
  
7.  選擇 \[安全性設定管理員\] 節點。
  
8.  在 \[資料庫\] 節點上按一下滑鼠右鍵，然後選取 \[匯入設定\]。
  
9.  選擇對應的原則範本，然後按一下 \[確定\]。
  
10. 在 \[資料庫\] 節點上按一下滑鼠右鍵，然後選取 \[立即設定系統\]。
  
11. 按一下 \[確定\] 接受預設的記錄檔路徑。
  
12. 等待原則套用完畢，然後檢視記錄檔結果。
  
13. 關閉記錄檔。
  
14. 關閉 MMC。
  
**從命令列套用原則範本**
  
1.  登入目標電腦。
  
2.  開啟命令提示。
  
3.  執行以下命令：
  
    secedit /configure /cfg c:\\winnt\\security\\templates\\treysec.inf /overwrite
  
4.  檢查結果。
  
5.  關閉命令提示字元。
  
#### 避免儲存 LM 密碼雜湊
  
以下程序說明如何使用原則或直接編輯登錄方式，設定您的網域控制站，避免儲存 LM 密碼雜湊。
  
**在 Windows 2000 SP2 或更新版本、Windows XP 或 Windows Server 2003 上使用群組原則或本機原則防止儲存 LM 雜湊**
  
1.  開啟群組原則編輯器。
  
2.  展開 \[電腦設定\]、\[Windows 設定\]、\[安全性設定\] 以及 \[本機原則\]，然後按一下 \[安全性選項\]。
  
3.  在可用的原則清單中，按兩下 \[網路安全性：下次密碼變更時不儲存 LAN Manager 雜湊數值\]。
  
4.  按一下 \[已啟用\]，然後按一下 \[確定\]。
  
5.  重新開機，然後變更您的密碼。
  
#### 設定 NTLM 驗證層級
  
以下程序說明如何設定網域控制站所使用的 NTLM 驗證層級。
  
**在 Windows 2000、Windows XP 或 Windows Server 2003 上使用群組原則設定 NTLM 層級**
  
1.  以系統管理員的身份登入網域控制站。
  
2.  啟動 \[Active Directory 使用者和電腦\]。
  
3.  開啟群組原則編輯器。
  
4.  以滑鼠右鍵按一下要套用 NTLM 驗證層級設定的網域，然後選擇 \[內容\]。
  
5.  在 \[內容\] 對話方塊中，按一下 \[群組原則\] 索引標籤。
  
6.  按一下 \[新增\] 按鈕建立新的群組原則物件 (GPO)。
  
7.  輸入 **NTLM 驗證層級**，然後按 ENTER。
  
8.  按一下 \[編輯\] 按鈕。
  
9.  展開 \[電腦設定\]、\[Windows 設定\]、\[安全性設定\] 以及 \[本機原則\]，然後按一下 \[安全性選項\]。
  
10. 在可用的原則清單裡，按兩下 \[網路安全性：LAN Manager 驗證層級\]。
  
11. 選擇 \[僅傳送 NTLMv2 回應\\拒絕 LM\]，這個選項在混用 Windows 98 和 Windows NT 的網路中可以提供適當的安全性與相容性。
  
12. **按一下** \[確定 (OK)\]。
  
13. 關閉群組原則編輯器。
  
14. 在網域的 \[內容\] 對話方塊中，用滑鼠右鍵按一下 NTLM 驗證內容 GPO，然後選擇 \[不可強制覆蓋\] 命令。
  
15. **按一下** \[關閉\]。
  
**在 Windows NT 4.0 SP3 或更新版本上經由登錄項目設定 NTLM 層級**
  
1.  啟動登錄編輯程式 (Regedt32.exe)。
  
2.  搜尋 **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet**  
    **\\Control\\Lsa**，然後在此機碼上按一下。
  
3.  在 \[編輯\] 功能表裡，按一下 \[新增值\]。
  
4.  在 \[資料類型\] 欄選用 \[DWORD 數值\]。
  
5.  在 \[數值名稱\] 中輸入 **LMCompatibilityLevel**，然後按一下 \[確定\]。
  
6.  在 \[資料\] 中輸入**十進位**值 **3** (或想要使用的層級)。
  
7.  離開登錄編輯程式。
  
8.  重新啟動電腦。
  
**在 Windows 98 上使用登錄機碼設定 NTLM 層級**
  
1.  啟動登錄編輯程式 (Regedt32.exe)。
  
2.  在登錄中搜尋並選取下列子機碼：  
    **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet**  
    **\\Control**。
  
3.  在 \[編輯\] 功能表中，指向 \[新增\]，然後按一下 \[機碼\]。
  
4.  輸入 **Lsa** 然後按一下 ENTER。
  
5.  在 \[編輯\] 功能表中，指向 \[新增\]，再按一下 \[DWORD 值\]。
  
6.  輸入 **LMCompatibilityLevel**，然後按 ENTER。
  
7.  在 \[編輯\] 功能表上按一下 \[新增值\]，然後加入下列登錄值：
  
    -   **數值名稱**：LMCompatibility
  
    -   **資料類型**：REG\_DWORD
  
    -   **數值** ：3
  
8.  離開登錄編輯程式。
  
9.  重新啟動電腦。
  
#### 將磁碟區轉換成 NTFS
  
以下程序說明如何將 FAT 磁碟區轉換成 NTFS。
  
**將 FAT 磁碟區轉換成 NTFS**
  
1.  以系統管理員的身份開啟命令提示字元。
  
2.  用 **convert** 命令指定要轉換哪個磁碟機：
  
    convert d: /fs:ntfs
  
3.  如果出現提示，請重新開機讓轉換公用程式能夠取得該磁碟機的獨佔存取權。
  
    如果您轉換的是系統磁碟分割、含有命令直譯器目前使用工作目錄的磁碟區，或是應用程式尚有檔案開啟的磁碟區，就必需重新開機。
  
    **注意：**知識庫文件編號 214579＜如何使用 Convert.exe 將分割轉換成 NTFS 檔案系統＞(英文) (<http://support.microsoft.com/?kbid=214579>) 中有 **convert** 命令及其運作方式的詳細說明。
  
#### 進行其他強化措施
  
以下程序說明了實作其他強化措施所需的步驟。
  
##### 停用自動產生 8.3 檔名
  
這個程序會停用自動為 16 位元應用程式產生 8.3 格式檔名的功能。
  
**停用自動產生 8.3 檔名**
  
1.  啟動登錄編輯程式 (Regedt32.exe)。
  
2.  搜尋並選擇以下機碼：**HKEY\_LOCAL\_MACHINE\\System\\CurrentControlSet**  
    **\\Control\\FileSystem**
  
3.  如果 **NtfsDisable8dot3NameCreation** 數值不存在，請按一下 \[編輯\] 功能表中的 \[新增值\]，輸入 **NtfsDisable8dot3NameCreation** 並確認類型為 REG\_DWORD。然後按一下 ENTER。
  
4.  選取 **NtfsDisable8dot3NameCreation** 。
  
5.  在 \[編輯\] 功能表上按一下 \[修改\]。
  
6.  輸入 **1** (或想要的層級)，然後按一下 \[確定\]。
  
7.  離開登錄編輯程式。
  
    **注意：**Trey 需要照常執行一些 16 位元應用程式， 但這些應用程式只用於網域中一個子集的電腦上。所有檔案與列印伺服器都已經套用這項變更；其他不需要執行 16 位元應用程式的成員伺服器與工作站也套用了這個設定。
  
##### 停用自動執行
  
這個程序會停用光碟機的自動執行功能。
  
**停用自動執行**
  
1.  啟動登錄編輯程式 (Regedt32.exe)。
  
2.  搜尋並選取以下機碼：**HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet**  
    **\\Services\\CDROM**
  
3.  在 \[編輯\] 功能表裡，按一下 \[新增值\]。
  
4.  輸入 **Autorun** 並確認類型為 REG\_DWORD。然後按一下 ENTER。
  
5.  在 \[編輯\] 功能表上按一下 \[修改\]。
  
6.  輸入 **0** (或想要的層級)，然後按一下 \[確定\]。
  
7.  離開登錄編輯程式。
  
##### 移除 OS/2 及 POSIX 子系統
  
這個程序會停用 OS/2 及 POSIX 相容性子系統。
  
**停用 OS/2 與 POSIX**
  
1.  啟動登錄編輯程式 (Regedt32.exe)。
  
2.  搜尋並刪除下列機碼：**HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet**  
    **\\Control\\SessionManager\\Environment\\OS2LibPath**
  
3.  如果 **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet**  
    **\\Control\\Session Manager\\Subsystems** 機碼已存在，請搜尋並刪除其中的 OS/2 及 POSIX 子機碼。
  
4.  如果 **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet**  
    **\\Control\\Session Manager\\Environment\\Subsystems** 機碼存在，請搜尋並刪除其中的 POSIX 及 OS/2 子機碼 (如果存在)。
  
5.  搜尋並刪除下列機碼：**HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft**  
    **\\OS/2 Subsystem for NT**
  
6.  離開登錄編輯程式。
  
7.  開啟 Windows 檔案總管。
  
8.  刪除 \\winnt\\system32\\os2 目錄及其下所有子目錄。
  
9.  重新啟動電腦。
  
##### 提升物件保護層級
  
這個程序會提升核心物件的保護層級。
  
**提升物件保護層級**
  
1.  啟動登錄編輯程式 (Regedt32.exe)。
  
2.  搜尋並選取以下機碼：**HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet**  
    **\\Control\\Session Manager**
  
3.  在 \[編輯\] 功能表裡，按一下 \[新增值\]。
  
4.  輸入 **EnhancedSecurityLevel** 並確認其類型為 REG\_DWORD。然後按一下 ENTER。
  
5.  在 \[編輯\] 功能表上按一下 \[修改\]。
  
6.  輸入 **1** (或想要的層級)，然後按一下 \[確定\]。
  
7.  離開登錄編輯程式。
  
##### 禁止使用者新增印表機驅動程式
  
這個程序會停用一般使用者新增印表機驅動程式的能力。
  
**禁止一般使用者新增印表機驅動程式**
  
1.  啟動登錄編輯程式 (Regedt32.exe)。
  
2.  搜尋並選取下列機碼：**HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Print\\Providers\\LanMan Print Services\\Servers**
  
3.  在 \[編輯\] 功能表裡，按一下 \[新增值\]。
  
4.  輸入 **AddPrinterDrivers** 並確認類型為 REG\_DWORD。然後按一下 ENTER。
  
5.  在 \[編輯\] 功能表上按一下 \[修改\]。
  
6.  輸入 **1** (或想要的層級)，然後按一下 \[確定\]。
  
7.  離開登錄編輯程式。
  
##### 確認停用系統管理員自動登入
  
這個程序會停用系統管理員帳戶的自動登入功能。
  
**停用系統管理員的自動登入 (預設為停用)**
  
1.  啟動登錄編輯程式 (Regedt32.exe)。
  
2.  搜尋並選取下列機碼：**HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\WindowsNT\\CurrentVersion\\Winlogon**
  
3.  搜尋並按一下以下數值 (如果存在)：**AutoAdminLogon**。
  
4.  在 \[編輯\] 功能表上按一下 \[修改\]。
  
5.  輸入 **0** (或想要的層級)，然後按一下 \[確定\]。
  
6.  如果 **DefaultPassword** 數值存在，請將之刪除。
  
7.  離開登錄編輯程式。
  
##### 停用 Novell 用戶端通知
  
這個程序會停用密碼變更時自動對 Novell 網路用戶端發出通知訊息。
  
**停用預設 Novell 用戶端密碼變更通知**
  
1.  啟動登錄編輯程式 (Regedt32.exe)。
  
2.  搜尋並選取下列機碼： **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Lsa**
  
3.  搜尋並選取下列數值：**Notification Packages**。
  
4.  在 \[編輯\] 功能表上按一下 \[修改\]。
  
5.  確認 **FPNWCLNT** 數值並不包含在內，然後按一下 \[確定\]。
  
6.  離開登錄編輯程式。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 測試解決方案
  
完成 Trey 案例的實作後，可以開始驗證實作是否可以達成要求。
  
#### 驗證
  
您可以利用下表中的資訊測試 Trey 案例，並驗證依照本指南進行的實作。
  
**表 4.2：驗證測試**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >說明</th>
<th style="border:1px solid black;" >測試步驟</th>
<th style="border:1px solid black;" >預測結果</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">驗證 Internet Explorer 6 SP1 安裝</td>
<td style="border:1px solid black;">啟動 Internet Explorer。在 [說明] 功能表按一下 [關於 Internet Explorer]。</td>
<td style="border:1px solid black;">版本訊息應該顯示 6.0.2800.xxxx。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">驗證 Windows NT 4.0 (SP6a) 安裝</td>
<td style="border:1px solid black;">執行系統管理工具群組裡的 Windows NT 診斷小程式，然後選擇 [版本] 索引標籤。</td>
<td style="border:1px solid black;">版本資訊應該顯示 SP6a。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">驗證開機程序</td>
<td style="border:1px solid black;"><em>模式 1</em> (將啟動金鑰存放在本機上，此設定套用於 Trey 大部份的伺服器與所有的工作站上)。
開機時，加密金鑰會解密並載入，讓電腦不需要系統管理員介入即可重新開機。  
<em>模式 2</em> (<strong>密碼啟動</strong>按鈕及相關文字欄位，此設定套用於高價值伺服器上)。
開機時，系統管理員必須在主控台輸入密碼片語，才能完成開機程序，</td>
<td style="border:1px solid black;">用戶端登入成功。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">驗證 DSClient 安裝成功</td>
<td style="border:1px solid black;">按一下 [開始]，然後按一下 [搜尋] 及 [人員]。</td>
<td style="border:1px solid black;">如果能夠搜尋 Active Directory，就代表 DSClient 安裝成功。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">驗證系統原則</td>
<td style="border:1px solid black;">試著存取系統原則限制的資源。
詳細檢查系統原則的位置，原則通常存放在 C:\Winnt\system32\repl\import\scripts 資料夾。</td>
<td style="border:1px solid black;">無法存取受限資源。
系統原則應該存放於前述位置。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">驗證 NTLMv2 驗證方式</td>
<td style="border:1px solid black;">設定網域控制站要求 NTLMv2 驗證。</td>
<td style="border:1px solid black;">用戶端登入成功。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">驗證安全性設定管理員</td>
<td style="border:1px solid black;">建立並自動套用安全性範本到網域裡一或多部電腦。
檢查 %winnt%\security\templates 資料夾中的範本。</td>
<td style="border:1px solid black;">能夠強化成員伺服器及工作站。
範本應該位於前述位置。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">檢查長檔名產生</td>
<td style="border:1px solid black;">新建檔名超過 8.3 格式長度的檔案。</td>
<td style="border:1px solid black;">無法以 8.3 格式存取該檔案。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">驗證自動執行功能</td>
<td style="border:1px solid black;">將支援自動執行的光碟放入電腦的光碟機。</td>
<td style="border:1px solid black;">在光碟機中放入支援自動執行的光碟後，自動執行也沒有動作。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">驗證 OS/2 或 POSIX 子系統是否停止運作</td>
<td style="border:1px solid black;">一名使用者啟動了程序後登出，下一個登入系統的使用者有可能存取前一位使用者的程序。</td>
<td style="border:1px solid black;">依存於 OS/2 或 POSIX 子系統的應用程式也無法再運作。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">驗證物件保護層級</td>
<td style="border:1px solid black;">惡意使用者嘗試在各種情況下變更核心物件屬性。</td>
<td style="border:1px solid black;">系統應不會允許惡意呼叫者提升權限。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">禁止使用者新增印表機驅動程式</td>
<td style="border:1px solid black;">惡意使用者嘗試利用新增某些印表機驅動程式來提高權限。</td>
<td style="border:1px solid black;">Printer Operators 及 Administrator 群組的成員可以新增印表機驅動程式。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">驗證系統管理員自動登入功能已停用</td>
<td style="border:1px solid black;">電腦重新開機後，嘗試以系統管理員身份自動登入。</td>
<td style="border:1px solid black;">系統管理員自動登入應該已停用。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">驗證開機延遲時間</td>
<td style="border:1px solid black;">重新開機並留意開機延遲時間。</td>
<td style="border:1px solid black;">延遲時間應該已從 30 秒減為 0 秒。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">檢驗 SCM 安裝</td>
<td style="border:1px solid black;">按一下 [開始]，再按 [執行]，輸入 <strong>mmc</strong>，然後按下 ENTER。</td>
<td style="border:1px solid black;">應該可以使用 SCM Microsoft 管理主控台。</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[回到頁首](#mainsection)
  
### 總結
  
雖然 Windows NT 並不具備所有現代化的安全性功能，但是還是有許多能夠緩和威脅與安全性風險的功能和技術。從最初作業系統與補充程式基礎安裝，到強化開機程序、部署目錄服務用戶端增益集、有效率地使用系統原則控制重要的安全性問題 (例如 NTLM 驗證和密碼的產生)，再到檔案系統和服務的強化，以及最後的額外強化措施，證明在 Windows NT 上，還是有許多作業系統層級的設定可以幫助提升安全性。
  
#### 其他資訊
  
-   Windows NT 4.0 Service Pack 6a 可以從 [http://www.microsoft.com/ntserver/nts/downloads  
    /recommended/SP6/allSP6.asp](http://www.microsoft.com/ntserver/nts/downloads/recommended/sp6/allsp6.asp) 取得。
  
-   Windows NT Server Service Pack 6a 常見問題集包含了安全性相關的資訊，可以從 <http://www.microsoft.com/ntserver/support/faqs/sp6faq.asp> 取得。
  
-   Windows NT 4.0 Service Pack 6a 後續安全性彙總套件可以從 [http://www.microsoft.com/ntserver/nts/downloads  
    /critical/q299444/default.asp](http://www.microsoft.com/ntserver/nts/downloads/critical/q299444/default.asp) 取得。
  
-   Internet Explorer 管理組件可以從 <http://www.microsoft.com/windows/ieak/> 取得。
  
-   Windows 95/98 及 Windows NT 的 Active Directory 用戶端擴充功能可以從 [http://www.microsoft.com/windows2000/server/  
    evaluation/news/bulletins/adextension.asp](http://www.microsoft.com/windows2000/server/evaluation/news/bulletins/adextension.asp) 取得。
  
-   《Microsoft Windows  NT 4.0 設定檔與原則指南》(英文) 白皮書可以從 <http://www.microsoft.com/ntserver/docs/prof_policies.doc> 取得。
  
-   關於系統原則編輯器的資訊，可以從 MSDN 的＜如何使用系統原則編輯器＞(英文) 找到，網址為：<http://msdn.microsoft.com/library/en-us/policy/policy/using_the_system_policy_editor.asp>。
  
-   安全性設定管理員可以從 Microsoft FTP 伺服器取得，網址為：[http://www.microsoft.com/ntserver  
    /techresources/security/securconfig.asp](http://www.microsoft.com/ntserver/techresources/security/securconfig.asp)。
  
-   完整的 Windows NT 4.0 SCM 指南可以從 <http://www.microsoft.com/ntserver/docs/scm-nt4.doc> 取得。
  
-   美國國家安全局的《強化 Microsoft Windows  NT 網路指南》(英文) 可以從 [www.nsa.gov/snac/downloads\_winnt.cfm](http://www.nsa.gov/snac/downloads_winnt.cfm) 取得。
  
[](#mainsection)[回到頁首](#mainsection)
