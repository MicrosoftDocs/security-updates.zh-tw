---
TOCTitle: 'MS08-OCT'
Title: 2008 年 10 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms08-oct'
ms:contentKeyID: 61237687
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms08-oct(v=Security.10)'
---

2008 年 10 月份 Microsoft 資訊安全公告摘要
==========================================

發行: 2008年10月15日 | 更新: 2008年10月24日

**版本:** 3.0

此公告摘要列出 2008 年 10 月份發行之安全性公告。

發行 2008 年 10 月份公告之後，此公告摘要將取代原先於 2008 年 10 月 9 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](http://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2008 年 10 月 15 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。 [立即註冊參加 10 月份安全性公告網路廣播](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374639)。 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](http://technet.microsoft.com/security/bulletin/summary)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性、高優先順序更新的優先順序，其中這些非安全性、高優先順序更新的發行日期與每月安全性更新的發行日期相同。 請參閱＜其他資訊＞一節。

### 公告資訊

#### 提要

本月份安全性公告依嚴重性列出如下：

重大 (5)
--------

<span></span>

| 公告編號               | Microsoft 安全性公告 MS08-067                                                                                                                                                                                                                                                                                                                                                  |
|------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**Server 服務中的弱點可能會允許遠端執行程式碼 (958644)**](http://technet.microsoft.com/security/bulletin/ms08-067)                                                                                                                                                                                                                                                            |
| **提要**               | 這個安全性更新可解決 Server 服務中一項未公開報告的弱點。 如果使用者在受影響的系統上收到蓄意製作的 RPC 要求，則該弱點可能會允許遠端執行程式碼。 在 Microsoft Windows 2000、Windows XP、Windows Server 2003 系統上，攻擊者可以利用此弱點，不經驗證就執行任意程式碼。 此弱點也可能用來製作蠕蟲攻擊。 防火牆的最佳實作和標準預設防火牆設定有助於防止網路資源受到來自企業外的攻擊。 |
| **最高的嚴重性等級：** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                  |
| **弱點的影響**         | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                                 |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 本更新程式需要重新開機。                                                                                                                                                                                                                                                                             |
| **受影響的軟體**       | **Microsoft Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                                   |

| 公告編號               | Microsoft 安全性公告 MS08-060                                                                                                                                                                                                                                                                                                                                                                        |
|------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**Active Directory 中的弱點可能會允許遠端執行程式碼 (957280)**](http://technet.microsoft.com/security/bulletin/ms08-060)                                                                                                                                                                                                                                                                            |
| **提要**               | 這個安全性更新可解決在 Microsoft Windows 2000 Server 上實作 Active Directory 的一項未公開報告的弱點。 如果攻擊者獲得存取受影響網路的權限，則弱點可能會允許遠端執行程式碼。 此弱點僅會影響設為網域控制站的 Microsoft Windows 2000 Server。 如果 Microsoft Windows 2000 Server 沒有升級為網域控制站，將不會接聽輕量型目錄存取通訊協定 (LDAP) 或 LDAP over SSL (LDAPS) 查詢，因此不會暴露於這個弱點下。 |
| **最高的嚴重性等級：** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                        |
| **弱點的影響**         | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                                                       |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 本更新程式需要重新開機。                                                                                                                                                                                                                                                                                                   |
| **受影響的軟體**       | **Microsoft Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                                                         |

| 公告編號               | Microsoft 安全性公告 MS08-058                                                                                                                                                                                                                       |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**Internet Explorer 積存安全性更新 (956390)**](http://technet.microsoft.com/security/bulletin/ms08-058)                                                                                                                                            |
| **提要**               | 這個安全性更新可解決五項未公開報告的弱點，以及一項已公開揭露的弱點。 如果使用者使用 Internet Explorer 檢視蓄意製作的網頁，弱點可能會允許資訊洩漏或遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級：** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                       |
| **弱點的影響**         | 遠端執行程式碼                                                                                                                                                                                                                                      |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 本更新程式需要重新開機。                                                                                                                                                  |
| **受影響的軟體**       | **Microsoft Windows、Internet Explorer。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                     |

| 公告編號               | Microsoft 安全性公告 MS08-059                                                                                                                                                                                                                                                                                              |
|------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**Host Integration Server RPC 服務中的弱點允許遠端執行程式碼 (956695)**](http://technet.microsoft.com/security/bulletin/ms08-059)                                                                                                                                                                                         |
| **提要**               | 這個安全性更新可解決 Microsoft Host Integration Server 中一項未公開報告的弱點。 如果攻擊者傳送蓄意製作的遠端程序呼叫 (RPC) 要求到受影響的系統，則弱點可能會允許遠端執行程式碼。 遵循最佳做法並將 SNA RPC 服務帳戶設定為具有較少使用者權限的使用者，其受影響的程度比將 SNA RPC 服務帳戶設定為擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級：** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                              |
| **弱點的影響**         | 遠端執行程式碼                                                                                                                                                                                                                                                                                                             |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新可能需要重新啟動電腦。                                                                                                                                                                                                                     |
| **受影響的軟體**       | **Microsoft Host Integration Server。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                               |

| 公告編號               | Microsoft 安全性公告 MS08-057                                                                                                                                                                                                                                                                                                                                    |
|------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**Microsoft Excel 中的弱點可能會允許遠端執行程式碼 (956416)**](http://technet.microsoft.com/security/bulletin/ms08-057)                                                                                                                                                                                                                                         |
| **提要**               | 此安全性更新可解決 Microsoft Office Excel 中三項未公開報告的弱點，該弱點可在使用者開啟蓄意製作的 Excel 檔案時，允許遠端執行程式碼。 成功利用這類弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級：** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                    |
| **弱點的影響**         | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                   |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新不需要重新開機。                                                                                                                                                                                                                                                                 |
| **受影響的軟體**       | **Microsoft Office。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                      |

重要 (6)
--------

<span></span>

| 公告編號               | Microsoft 安全性公告 MS08-066                                                                                                                                                                                         |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**Microsoft 附屬功能驅動程式中的弱點可能會允許權限提高 (956803)**](http://technet.microsoft.com/security/bulletin/ms08-066)                                                                                          |
| **提要**               | 這個安全性更新可解決 Microsoft 附屬功能驅動程式中一項未公開報告的弱點。 成功利用此弱點的本機攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 |
| **最高的嚴重性等級：** | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                         |
| **弱點的影響**         | 權限提高                                                                                                                                                                                                              |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 本更新程式需要重新開機。                                                                                                                    |
| **受影響的軟體**       | **Microsoft Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                          |

| 公告編號               | Microsoft 安全性公告 MS08-061                                                                                                                                         |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**Windows 核心中的弱點可能會允許權限提高 (954211)**](http://technet.microsoft.com/security/bulletin/ms08-061)                                                        |
| **提要**               | 這個安全性更新可解決在 Windows 核心中一項公開揭發和二項未公開報告的弱點。 成功利用這類弱點的攻擊者可以取得受影響系統的完整控制權。 遠端或匿名使用者無法利用這個弱點。 |
| **最高的嚴重性等級：** | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                         |
| **弱點的影響**         | 權限提高                                                                                                                                                              |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 本更新程式需要重新開機。                                                                    |
| **受影響的軟體**       | **Microsoft Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                          |

| 公告編號               | Microsoft 安全性公告 MS08-062                                                                                                                                                                                             |
|------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**Windows 網際網路列印服務中的弱點可能會允許遠端執行程式碼 (953155)**](http://technet.microsoft.com/security/bulletin/ms08-062)                                                                                          |
| **提要**               | 這個更新程式可以在允許遠端執行程式碼的 Windows 網際網路列印服務中，解決一項未公開報告的弱點。 成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來能在系統上安裝程式；檢視、變更或刪除資料；或建立新帳戶。 |
| **最高的嚴重性等級：** | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                             |
| **弱點的影響**         | 遠端執行程式碼                                                                                                                                                                                                            |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 本更新程式需要重新開機。                                                                                                                        |
| **受影響的軟體**       | **Microsoft Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                              |

| 公告編號               | Microsoft 安全性公告 MS08-063                                                                                                                                                                                                                    |
|------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**SMB 中的弱點可能會允許遠端執行程式碼 (957095)**](http://technet.microsoft.com/security/bulletin/ms08-063)                                                                                                                                     |
| **提要**               | 這個安全性更新解決在 Microsoft 伺服器訊息區 (SMB) 通訊協定中一項未公開報告的弱點。 該弱點可能會允許正在共用檔案或資料夾的伺服器遠端執行程式碼。 成功地利用這些弱點的攻擊者可以安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 |
| **最高的嚴重性等級：** | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                    |
| **弱點的影響**         | 遠端執行程式碼                                                                                                                                                                                                                                   |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 本更新程式需要重新開機。                                                                                                                                               |
| **受影響的軟體**       | **Microsoft Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                     |

| 公告編號               | Microsoft 安全性公告 MS08-064                                                                                                                                                                                                                                                                   |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**Virtual Address Descriptor 操作中的弱點可能會允許權限提高 (956841)**](http://technet.microsoft.com/security/bulletin/ms08-064)                                                                                                                                                               |
| **提要**               | 這個安全性更新可解決 Virtual Address Descriptor 中一項未公開報告的弱點。 如果使用者執行蓄意製作的應用程式，則弱點可能會允許權限提高。 經驗證的攻擊者成功利用這個弱點後，即可在受影響的系統上提高權限。 接下來，攻擊者就能安裝程式，檢視、變更或刪除資料，或是建立具有完整系統管理權限的新帳戶。 |
| **最高的嚴重性等級：** | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                   |
| **弱點的影響**         | 權限提高                                                                                                                                                                                                                                                                                        |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 本更新程式需要重新開機。                                                                                                                                                                                              |
| **受影響的軟體**       | **Microsoft Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                    |

| 公告編號               | Microsoft 安全性公告 MS08-065                                                                                                                                                   |
|------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**訊息佇列中的弱點可能會允許遠端執行程式碼 (951071)**](http://technet.microsoft.com/security/bulletin/ms08-065)                                                                |
| **提要**               | 這個安全性更新可解決在 Microsoft Windows 2000 系統上之訊息佇列服務 (MSMQ) 中一項未公開報告的弱點。 此弱點可能會允許啟用 MSMQ 服務的 Microsoft Windows 2000 系統遠端執行程式碼。 |
| **最高的嚴重性等級：** | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                   |
| **弱點的影響**         | 遠端執行程式碼                                                                                                                                                                  |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 本更新程式需要重新開機。                                                                              |
| **受影響的軟體**       | **Microsoft Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                    |

中度 (1)
--------

<span></span>

| 公告編號               | Microsoft 安全性公告 MS08-056                                                                                                                                                                                                                                                  |
|------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**Microsoft Office 中的弱點可能會允許資訊洩漏 (957699)**](http://technet.microsoft.com/security/bulletin/ms08-056)                                                                                                                                                            |
| **提要**               | 這個安全性更新可解決 Microsoft Office 中一項未公開報告的弱點。 如果使用者按一下蓄意製作的 OneNote URL，此弱點便可能允許資訊洩漏。 成功地利用此弱點的攻擊者可在使用者的瀏覽器中注入用戶端指令碼，而指令碼可能會偽造內容、洩漏資訊、在受影響的網站上採取使用者可能會採取的行為。 |
| **最高的嚴重性等級：** | [中度](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                  |
| **弱點的影響**         | 資訊洩漏                                                                                                                                                                                                                                                                       |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新不需要重新開機。                                                                                                                                                                               |
| **受影響的軟體**       | **Microsoft Office。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                    |

弱點索引
--------

<span></span>
**我該如何使用這個表格？**

請用這個表格來瞭解您可能需要安裝的每個安全性更新，已發行的可利用程式碼受影響之可能性。 您應該檢閱下列的每個評估，按照特定的設定，將部署以優先次序排序。 如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](http://technet.microsoft.com/en-us/security/cc998259.aspx)。

| 公告編號                                                            | 公告標題                                                                                                                      | CVE ID        | 弱點索引評估                                                                                        | 主要重點                                                                                                                                                                                                                                                                                                                          |
|---------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|---------------|-----------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [MS08-056](http://technet.microsoft.com/security/bulletin/ms08-056) | [Microsoft Office 中的弱點可能會允許資訊洩漏 (957699)](http://technet.microsoft.com/security/bulletin/ms08-056)               | CVE-2008-4020 | [2 - 可能撰寫出偶爾可利用此漏洞的程式碼](http://technet.microsoft.com/en-us/security/cc998259.aspx) | 能夠建立可利用的程式碼。 但是，嚴重性影響受限於弱點僅允許在特定的 Web 應用程式案例中，於對話進行偽造。 因此，攻擊者可能很少會注意到這個項目。                                                                                                                                                                                     |
| [MS08-057](http://technet.microsoft.com/security/bulletin/ms08-057) | [Microsoft Excel 中的弱點可能會允許遠端執行程式碼 (956416)](http://technet.microsoft.com/security/bulletin/ms08-057)          | CVE-2008-4019 | [1 - 可能撰寫出可持續利用此漏洞的程式碼](http://technet.microsoft.com/en-us/security/cc998259.aspx) |                                                                                                                                                                                                                                                                                                                                   |
| [MS08-057](http://technet.microsoft.com/security/bulletin/ms08-057) | [Microsoft Excel 中的弱點可能會允許遠端執行程式碼 (956416)](http://technet.microsoft.com/security/bulletin/ms08-057)          | CVE-2008-3471 | [2 - 可能撰寫出偶爾可利用此漏洞的程式碼](http://technet.microsoft.com/en-us/security/cc998259.aspx) |                                                                                                                                                                                                                                                                                                                                   |
| [MS08-057](http://technet.microsoft.com/security/bulletin/ms08-057) | [Microsoft Excel 中的弱點可能會允許遠端執行程式碼 (956416)](http://technet.microsoft.com/security/bulletin/ms08-057)          | CVE-2008-3477 | [2 - 可能撰寫出偶爾可利用此漏洞的程式碼](http://technet.microsoft.com/en-us/security/cc998259.aspx) |                                                                                                                                                                                                                                                                                                                                   |
| [MS08-058](http://technet.microsoft.com/security/bulletin/ms08-058) | [Internet Explorer 積存安全性更新 (956390)](http://technet.microsoft.com/security/bulletin/ms08-058)                          | CVE-2008-2947 | (公開於公告發行)                                                                                    |                                                                                                                                                                                                                                                                                                                                   |
| [MS08-058](http://technet.microsoft.com/security/bulletin/ms08-058) | [Internet Explorer 積存安全性更新 (956390)](http://technet.microsoft.com/security/bulletin/ms08-058)                          | CVE-2008-3472 | [1 - 可能撰寫出可持續利用此漏洞的程式碼](http://technet.microsoft.com/en-us/security/cc998259.aspx) |                                                                                                                                                                                                                                                                                                                                   |
| [MS08-058](http://technet.microsoft.com/security/bulletin/ms08-058) | [Internet Explorer 積存安全性更新 (956390)](http://technet.microsoft.com/security/bulletin/ms08-058)                          | CVE-2008-3473 | [1 - 可能撰寫出可持續利用此漏洞的程式碼](http://technet.microsoft.com/en-us/security/cc998259.aspx) |                                                                                                                                                                                                                                                                                                                                   |
| [MS08-058](http://technet.microsoft.com/security/bulletin/ms08-058) | [Internet Explorer 積存安全性更新 (956390)](http://technet.microsoft.com/security/bulletin/ms08-058)                          | CVE-2008-3475 | [2 - 可能撰寫出偶爾可利用此漏洞的程式碼](http://technet.microsoft.com/en-us/security/cc998259.aspx) |                                                                                                                                                                                                                                                                                                                                   |
| [MS08-058](http://technet.microsoft.com/security/bulletin/ms08-058) | [Internet Explorer 積存安全性更新 (956390)](http://technet.microsoft.com/security/bulletin/ms08-058)                          | CVE-2008-3474 | [3 - 不太可能被利用的程式碼](http://technet.microsoft.com/en-us/security/cc998259.aspx)             |                                                                                                                                                                                                                                                                                                                                   |
| [MS08-058](http://technet.microsoft.com/security/bulletin/ms08-058) | [Internet Explorer 積存安全性更新 (956390)](http://technet.microsoft.com/security/bulletin/ms08-058)                          | CVE-2008-3476 | [3 - 不太可能被利用的程式碼](http://technet.microsoft.com/en-us/security/cc998259.aspx)             |                                                                                                                                                                                                                                                                                                                                   |
| [MS08-059](http://technet.microsoft.com/security/bulletin/ms08-059) | [Host Integration Server 服務中的弱點允許遠端執行程式碼 (956695)](http://technet.microsoft.com/security/bulletin/ms08-059)    | CVE-2008-3466 | [1 - 可能撰寫出可持續利用此漏洞的程式碼](http://technet.microsoft.com/en-us/security/cc998259.aspx) | 雖然只有少數特定的企業類型客戶會安裝 Host Integration Server，但還是能建立可利用的程式碼。                                                                                                                                                                                                                                        |
| [MS08-060](http://technet.microsoft.com/security/bulletin/ms08-060) | [Active Directory 中的弱點可能會允許遠端執行程式碼 (957280)](http://technet.microsoft.com/security/bulletin/ms08-060)         | CVE-2008-4023 | [2 - 可能撰寫出偶爾可利用此漏洞的程式碼](http://technet.microsoft.com/en-us/security/cc998259.aspx) | 觸發弱點可能會導致拒絕服務的情況。 但是，由於無法控制所需的寫入位址，因此很難建立可利用程式碼來利用遠端執行程式碼。                                                                                                                                                                                                               |
| [MS08-061](http://technet.microsoft.com/security/bulletin/ms08-061) | [Windows 核心中的弱點可能會允許權限提高 (954211)](http://technet.microsoft.com/security/bulletin/ms08-061)                    | CVE-2008-2250 | [1 - 可能撰寫出可持續利用此漏洞的程式碼](http://technet.microsoft.com/en-us/security/cc998259.aspx) |                                                                                                                                                                                                                                                                                                                                   |
| [MS08-061](http://technet.microsoft.com/security/bulletin/ms08-061) | [Windows 核心中的弱點可能會允許權限提高 (954211)](http://technet.microsoft.com/security/bulletin/ms08-061)                    | CVE-2008-2252 | [1 - 可能撰寫出可持續利用此漏洞的程式碼](http://technet.microsoft.com/en-us/security/cc998259.aspx) | 在多處理器系統中能夠建立可利用的程式碼。                                                                                                                                                                                                                                                                                          |
| [MS08-061](http://technet.microsoft.com/security/bulletin/ms08-061) | [Windows 核心中的弱點可能會允許權限提高 (954211)](http://technet.microsoft.com/security/bulletin/ms08-061)                    | CVE-2008-2251 | [3 - 不太可能被利用的程式碼](http://technet.microsoft.com/en-us/security/cc998259.aspx)             | 觸發弱點是有可能的，但是要成功建立可利用程式碼則非常困難。                                                                                                                                                                                                                                                                        |
| [MS08-062](http://technet.microsoft.com/security/bulletin/ms08-062) | [Windows 網際網路列印服務中的弱點可能會允許遠端執行程式碼 (953155)](http://technet.microsoft.com/security/bulletin/ms08-062)  | CVE-2008-1446 | [1 - 可能撰寫出可持續利用此漏洞的程式碼](http://technet.microsoft.com/en-us/security/cc998259.aspx) | 在有限且目標明確的攻擊中發現持續利用此漏洞的程式碼。 當網際網路印刷通訊協定 (IPP) 服務依照預設啟用時，使用 IIS 存取這項服務也要依照預設在所有平台上提供驗證。                                                                                                                                                                     |
| [MS08-063](http://technet.microsoft.com/security/bulletin/ms08-063) | [SMB 中的弱點可能會允許遠端執行程式碼 (957095)](http://technet.microsoft.com/security/bulletin/ms08-063)                      | CVE-2008-4038 | [2 - 可能撰寫出偶爾可利用此漏洞的程式碼](http://technet.microsoft.com/en-us/security/cc998259.aspx) |                                                                                                                                                                                                                                                                                                                                   |
| [MS08-064](http://technet.microsoft.com/security/bulletin/ms08-064) | [Virtual Address Descriptor 操作中的弱點可能會允許權限提高 (956841)](http://technet.microsoft.com/security/bulletin/ms08-064) | CVE-2008-4036 | [2 - 可能撰寫出偶爾可利用此漏洞的程式碼](http://technet.microsoft.com/en-us/security/cc998259.aspx) |                                                                                                                                                                                                                                                                                                                                   |
| [MS08-065](http://technet.microsoft.com/security/bulletin/ms08-065) | [訊息佇列中的弱點可能會允許遠端執行程式碼 (951071)](http://technet.microsoft.com/security/bulletin/ms08-065)                  | CVE-2008-3479 | [3 - 不太可能被利用的程式碼](http://technet.microsoft.com/en-us/security/cc998259.aspx)             | 資訊洩漏為可能會發生的情況，但是不一定有可能從記憶體取得有用的內容。 記憶體損毀問題可以觸發，但是遠端執行程式碼很難取得。                                                                                                                                                                                                         |
| [MS08-066](http://technet.microsoft.com/security/bulletin/ms08-066) | [Microsoft 附屬功能驅動程式中的弱點可能會允許權限提高 (956803)](http://technet.microsoft.com/security/bulletin/ms08-066)      | CVE-2008-3464 | [1 - 可能撰寫出可持續利用此漏洞的程式碼](http://technet.microsoft.com/en-us/security/cc998259.aspx) |                                                                                                                                                                                                                                                                                                                                   |
| [MS08-067](http://technet.microsoft.com/security/bulletin/ms08-067) | [Server 服務中的弱點可能會允許遠端執行程式碼 (958644)](http://technet.microsoft.com/security/bulletin/ms08-067)               | CVE-2008-4250 | [1 - 可能撰寫出可持續利用此漏洞的程式碼](http://technet.microsoft.com/en-us/security/cc998259.aspx) | 在有限且目標明確的攻擊中發現持續利用此漏洞的程式碼 (受影響系統為 Windowx XP)。 雖然這項服務在所有受影響的平台上都是預設啟用，但攻擊目標主要是 Microsoft Windows 2000、Windows XP、Windows Server 2003。Windows Vista、Windows Server 2008、Windows 7 Beta 等平台都要求驗證，而且驗證後尚有 ASLR、DEP 增強功能，使得攻擊較為困難。 |

受影響的軟體及下載位置
----------------------

<span></span>
**我該如何使用這個表格？**

請用這個表格來瞭解可能需要安裝的安全性更新有哪些。 您應該查看此處列出的每一種軟體程式或元件，看看是否有需要的安全性更新。 若軟體程式或更新出現在清單中，則相關可用軟體更新也會以超連結方式提供，也會列出軟體更新的嚴重性等級。

**注意：**一項弱點可能需要安裝數個安全性更新才能妥善解決。 請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。

#### Windows 作業系統與元件

 
<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="10">
Microsoft Windows 2000
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-067**](http://technet.microsoft.com/security/bulletin/ms08-067)
</td>
<td style="border:1px solid black;">
[**MS08-060**](http://technet.microsoft.com/security/bulletin/ms08-060)
</td>
<td style="border:1px solid black;">
[**MS08-058**](http://technet.microsoft.com/security/bulletin/ms08-058)
</td>
<td style="border:1px solid black;">
[**MS08-066**](http://technet.microsoft.com/security/bulletin/ms08-066)
</td>
<td style="border:1px solid black;">
[**MS08-061**](http://technet.microsoft.com/security/bulletin/ms08-061)
</td>
<td style="border:1px solid black;">
[**MS08-062**](http://technet.microsoft.com/security/bulletin/ms08-062)
</td>
<td style="border:1px solid black;">
[**MS08-063**](http://technet.microsoft.com/security/bulletin/ms08-063)
</td>
<td style="border:1px solid black;">
[**MS08-064**](http://technet.microsoft.com/security/bulletin/ms08-064)
</td>
<td style="border:1px solid black;">
[**MS08-065**](http://technet.microsoft.com/security/bulletin/ms08-065)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告最高嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=e22eb3ae-1295-4fe2-9775-6f43c5c2aed3)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server Service Pack 4 上的 Active Directory (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=8ed7bb9a-4b26-49d7-8c14-60226d2bc20d)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=257c0478-56dd-42eb-a90e-607d01613db7)  
(重大)  
[Microsoft Internet Explorer 6 Service Pack 1 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=02390258-08e9-4b75-960d-be081b749558)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=3a6165a6-d7e7-4526-9291-290caf0639b4)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=8163d1f6-feb5-4f39-8134-3ed42326b822)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=9ed29c3a-0682-4586-bbc2-a73deaa18e4c)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=899e2728-2433-4ccb-a195-05b5d65e5469)  
(重要)
</td>
</tr>
<tr>
<th colspan="10">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-067**](http://technet.microsoft.com/security/bulletin/ms08-067)
</td>
<td style="border:1px solid black;">
[**MS08-060**](http://technet.microsoft.com/security/bulletin/ms08-060)
</td>
<td style="border:1px solid black;">
[**MS08-058**](http://technet.microsoft.com/security/bulletin/ms08-058)
</td>
<td style="border:1px solid black;">
[**MS08-066**](http://technet.microsoft.com/security/bulletin/ms08-066)
</td>
<td style="border:1px solid black;">
[**MS08-061**](http://technet.microsoft.com/security/bulletin/ms08-061)
</td>
<td style="border:1px solid black;">
[**MS08-062**](http://technet.microsoft.com/security/bulletin/ms08-062)
</td>
<td style="border:1px solid black;">
[**MS08-063**](http://technet.microsoft.com/security/bulletin/ms08-063)
</td>
<td style="border:1px solid black;">
[**MS08-064**](http://technet.microsoft.com/security/bulletin/ms08-064)
</td>
<td style="border:1px solid black;">
[**MS08-065**](http://technet.microsoft.com/security/bulletin/ms08-065)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告最高嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 及 Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 及 Windows XP Service Pack 3 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=0d5f9b6e-9265-44b9-a376-2067b73d6a03)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=a7f0f47b-b1ee-4516-9fbf-bf8e579963d0)  
(重大)  
[Windows Internet Explorer 7 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=4e73de2b-05e6-4901-9bac-46d8f469e635)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 及 Windows XP Service Pack 3 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=b16d9dac-c430-4dd8-a1e5-9a614801f1d9)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 及 Windows XP Service Pack 3 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=7718bf14-c26c-43f3-be67-4c79ab5b2607)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 及 Windows XP Service Pack 3 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=e7ef571f-c9e8-4e14-95a3-3eeaec55b784)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 及 Windows XP Service Pack 3 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=2f7e5981-6eef-4f08-86c0-c6a7607ea5d0)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 及 Windows XP Service Pack 3 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=25997b73-a640-49c1-b19e-768a18bbe22c)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4c16a372-7bf8-4571-b982-dac6b2992b25)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=234c05fb-988b-4e02-aab6-bb23e447df3d)  
(重大)  
[Windows Internet Explorer 7 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=ccf7a3e3-ec30-4b95-9a86-00032301513c)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5b607efc-c6fb-4079-8478-e4f3262386d3)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b06d3a02-b6e4-4d40-913a-3759a31f20f3)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3ae4b913-bff0-4974-b198-828ca10d2a87)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4e1675eb-6b06-48e9-9765-23a2c7737bdc)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=50fae854-0bde-46f8-9444-b9e0d9bfecad)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="10">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-067**](http://technet.microsoft.com/security/bulletin/ms08-067)
</td>
<td style="border:1px solid black;">
[**MS08-060**](http://technet.microsoft.com/security/bulletin/ms08-060)
</td>
<td style="border:1px solid black;">
[**MS08-058**](http://technet.microsoft.com/security/bulletin/ms08-058)
</td>
<td style="border:1px solid black;">
[**MS08-066**](http://technet.microsoft.com/security/bulletin/ms08-066)
</td>
<td style="border:1px solid black;">
[**MS08-061**](http://technet.microsoft.com/security/bulletin/ms08-061)
</td>
<td style="border:1px solid black;">
[**MS08-062**](http://technet.microsoft.com/security/bulletin/ms08-062)
</td>
<td style="border:1px solid black;">
[**MS08-063**](http://technet.microsoft.com/security/bulletin/ms08-063)
</td>
<td style="border:1px solid black;">
[**MS08-064**](http://technet.microsoft.com/security/bulletin/ms08-064)
</td>
<td style="border:1px solid black;">
[**MS08-065**](http://technet.microsoft.com/security/bulletin/ms08-065)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告最高嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 與 Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=f26d395d-2459-4e40-8c92-3de1c52c390d)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=ae8d22d5-20aa-471d-a423-f54c9d75febe)  
(中度)  
[Windows Internet Explorer 7 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=feaf2adf-7892-4dbf-a147-db4d5dbe52f3)  
(輕微)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=ee88ff2d-1b12-4f4c-a081-9f27a6fba074)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=6e696762-d652-4a8f-ab8f-622f9746c320)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=437a9b68-6a0c-48c8-9348-0d6fda48aa21)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=dbbebb3f-f1c7-402c-bd16-6f88da0d042c)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=e8ef3d5f-dd8e-4945-92cd-9d3e30b16667)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=c04d2afb-f9d0-4e42-9e1f-4b944a2de400)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=07fc88c4-2571-4a4d-b573-ae576798ab4c)  
(中度)  
[Windows Internet Explorer 7 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=319dba34-07ca-47f9-a1e9-20df2df7966b)  
(輕微)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=ab4d94d3-458c-4946-ab7f-03a279629d25)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=57ca28ea-e5e1-4191-a3d6-84aa90a3d668)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=d3df6508-a568-449d-ac97-fbf3f97b98ef)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=989ac6f1-515c-467d-a200-2aabe66d9319)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=c2e754f9-086a-494c-bc19-5feed7df8b65)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP1 for Itanium-based Systems 和 Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP1 和適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=ab590756-f11f-43c9-9dcc-a85a43077acf)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=b68937af-f04a-4d1e-9d7f-ec92af5194de)  
(中度)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=47381d91-4a14-4a09-96b3-3345155df52d)  
(輕微)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP1 和適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=63234f85-6e5d-4ef6-b7cf-d1d2c78a5517)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP1 和適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=1e6c3f81-85bb-48e6-a5af-635a7e540c93)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP1 和適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=748f54f1-40b9-407c-9819-909061b53743)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP1 和適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=91589cfb-15ba-4dd2-9e3b-107899fbcba6)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP1 和適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=5a3832ec-3f8f-42c1-a603-b1330d527547)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="10">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-067**](http://technet.microsoft.com/security/bulletin/ms08-067)
</td>
<td style="border:1px solid black;">
[**MS08-060**](http://technet.microsoft.com/security/bulletin/ms08-060)
</td>
<td style="border:1px solid black;">
[**MS08-058**](http://technet.microsoft.com/security/bulletin/ms08-058)
</td>
<td style="border:1px solid black;">
[**MS08-066**](http://technet.microsoft.com/security/bulletin/ms08-066)
</td>
<td style="border:1px solid black;">
[**MS08-061**](http://technet.microsoft.com/security/bulletin/ms08-061)
</td>
<td style="border:1px solid black;">
[**MS08-062**](http://technet.microsoft.com/security/bulletin/ms08-062)
</td>
<td style="border:1px solid black;">
[**MS08-063**](http://technet.microsoft.com/security/bulletin/ms08-063)
</td>
<td style="border:1px solid black;">
[**MS08-064**](http://technet.microsoft.com/security/bulletin/ms08-064)
</td>
<td style="border:1px solid black;">
[**MS08-065**](http://technet.microsoft.com/security/bulletin/ms08-065)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告最高嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 和 Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=18fdff67-c723-42bd-ac5c-cac7d8713b21)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=4756e04b-6e1c-4d78-a3c0-17f6b4b97975)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=3483b400-cedc-441f-ba8e-594e3df89190)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=9b5995df-a3b8-4e81-b118-9bb057e19884)  
(無嚴重性等級)
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=72dd6015-25d1-45f4-a769-88ac43074b44)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=b4212db5-093e-497d-b999-2e3780f9f7c2)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=a976999d-264f-4e6a-9bd6-3ad9d214a4bd)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=bd19c72b-4f83-47ab-93be-d2c286e732c4)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=905ab030-14a5-4a3d-aa11-e8f957f6a1ea)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=4a0fcf4b-eb8e-456a-b934-400ae18248ee)  
(無嚴重性等級)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=f793af16-5464-4db1-a42b-1c5f17c538ed)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=c20808cb-c30a-4b53-91e5-810eb6b4b2e3)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="10">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-067**](http://technet.microsoft.com/security/bulletin/ms08-067)
</td>
<td style="border:1px solid black;">
[**MS08-060**](http://technet.microsoft.com/security/bulletin/ms08-060)
</td>
<td style="border:1px solid black;">
[**MS08-058**](http://technet.microsoft.com/security/bulletin/ms08-058)
</td>
<td style="border:1px solid black;">
[**MS08-066**](http://technet.microsoft.com/security/bulletin/ms08-066)
</td>
<td style="border:1px solid black;">
[**MS08-061**](http://technet.microsoft.com/security/bulletin/ms08-061)
</td>
<td style="border:1px solid black;">
[**MS08-062**](http://technet.microsoft.com/security/bulletin/ms08-062)
</td>
<td style="border:1px solid black;">
[**MS08-063**](http://technet.microsoft.com/security/bulletin/ms08-063)
</td>
<td style="border:1px solid black;">
[**MS08-064**](http://technet.microsoft.com/security/bulletin/ms08-064)
</td>
<td style="border:1px solid black;">
[**MS08-065**](http://technet.microsoft.com/security/bulletin/ms08-065)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告最高嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=25c17b07-1efe-43d7-9b01-3dfdf1ce0bd7)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=ec73f416-2204-42d6-8932-c96578ac819f)\*\*  
(輕微)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=8b97114a-71aa-47a2-b9e7-f4e158c18c80)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=3d6290d8-1745-4bc0-9ca9-eeb1ad0be4a5)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=cf6744e6-b54c-40f6-a78d-7ba9453133c0)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=ec9eeb82-0497-4c55-94bb-9a47cb3521b4)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=7b12018e-0cc1-4136-a68c-be4e1633c8df)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=baacd1c2-9764-4fea-bd4d-c49791974fef)\*\*  
(輕微)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=6e641db2-90c8-458f-9795-3e46b70a5203)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=a33c833c-d5c5-4e37-8f89-7b9079f92e59)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=223236e8-7b19-4b47-8a90-bfc35eb9318a)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=0bc178b8-f8ae-4f41-8f88-fb6a75be1bca)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 系統的 Windows Server 2008
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008](http://www.microsoft.com/downloads/details.aspx?familyid=2bcf89ef-6446-406c-9c53-222e0f0baf7a)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=250a45dd-7eae-4440-bd10-02a703940976)  
(輕微)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008](http://www.microsoft.com/downloads/details.aspx?familyid=b6546e1c-bf7b-4354-8574-6c16fa707de0)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008](http://www.microsoft.com/downloads/details.aspx?familyid=31783e88-76e2-4bc6-b4ae-308443c6d223)  
(無嚴重性等級)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008](http://www.microsoft.com/downloads/details.aspx?familyid=077b697c-04a0-45bd-b08c-331d5c30cb47)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008](http://www.microsoft.com/downloads/details.aspx?familyid=0af72663-4945-4916-8c55-090ba4d82793)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="10">
Windows 7 Beta
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-067**](http://technet.microsoft.com/security/bulletin/ms08-067)
</td>
<td style="border:1px solid black;">
[**MS08-060**](http://technet.microsoft.com/security/bulletin/ms08-060)
</td>
<td style="border:1px solid black;">
[**MS08-058**](http://technet.microsoft.com/security/bulletin/ms08-058)
</td>
<td style="border:1px solid black;">
[**MS08-066**](http://technet.microsoft.com/security/bulletin/ms08-066)
</td>
<td style="border:1px solid black;">
[**MS08-061**](http://technet.microsoft.com/security/bulletin/ms08-061)
</td>
<td style="border:1px solid black;">
[**MS08-062**](http://technet.microsoft.com/security/bulletin/ms08-062)
</td>
<td style="border:1px solid black;">
[**MS08-063**](http://technet.microsoft.com/security/bulletin/ms08-063)
</td>
<td style="border:1px solid black;">
[**MS08-064**](http://technet.microsoft.com/security/bulletin/ms08-064)
</td>
<td style="border:1px solid black;">
[**MS08-065**](http://technet.microsoft.com/security/bulletin/ms08-065)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告最高嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Beta
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 Beta](http://www.microsoft.com/downloads/details.aspx?familyid=e877d9c1-3e7c-4551-a899-c3fcc5175bb6)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Beta
</td>
<td style="border:1px solid black;">
[Windows 7 Beta x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=0fa96b25-90e3-46ab-bcd5-051f4b2b881b)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 系統的 Windows 7 Beta
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows 7 Beta](http://www.microsoft.com/downloads/details.aspx?familyid=66646156-f3e6-48d7-be22-de1772dd1884)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
</table>
 
**\*Windows Server 2008 Server Core 安裝會受影響。** 對於受支援的 Windows Server 2008 版本，無論 Windows Server 2008 是否使用 Server Core 安裝選項，這個更新均以相同的嚴重性等級套用。 如需這個安裝選項的詳細資訊，請參閱 [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**\*\*Windows Server 2008 Server Core 安裝不受影響。** 如果 Windows Server 2008 是使用 Server Core 安裝選項所安裝，則這項更新解決的弱點並不會影響受支援的 Windows Server 2008 版本。 如需這個安裝選項的詳細資訊，請參閱 [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

#### Microsoft Office 套件及軟體

 
<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="3">
Microsoft Office 套件、系統和元件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-057**](http://technet.microsoft.com/security/bulletin/ms08-057)
</td>
<td style="border:1px solid black;">
[**MS08-056**](http://technet.microsoft.com/security/bulletin/ms08-056)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告最高嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
[Excel 2000 Service Pack 3 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=1b2740e0-ecdd-48ca-84e0-eb187c31eb16)  
(KB955461)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Excel 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=27cedef1-c47c-472c-a343-cd9b4ebc2bba)  
(KB955464)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=b1aee2d5-bfa0-40e3-91b6-98bf65524e8c)  
(KB956464)  
(中度)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 2 和 Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Excel 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=4df27e8a-d803-483b-a700-0177d71bf368)  
(KB955466)  
(重要)  
[Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=4df27e8a-d803-483b-a700-0177d71bf368)  
(KB955466)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
2007 Microsoft Office System 和 2007 Microsoft Office System Service Pack 1
</td>
<td style="border:1px solid black;">
[Excel 2007](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=2765bbc0-ea2e-4b6e-822c-222ee8e5021f)  
(KB955470)  
(重要)  
[Excel 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=2765bbc0-ea2e-4b6e-822c-222ee8e5021f)  
(KB955470)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office for Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-057**](http://technet.microsoft.com/security/bulletin/ms08-057)
</td>
<td style="border:1px solid black;">
[**MS08-056**](http://technet.microsoft.com/security/bulletin/ms08-056)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告最高嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=ba4fa21a-7e01-4ef8-9b9f-9d51d00ef094)  
(KB958312)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=e70c5ae0-2858-46de-81f8-dcd1786656b7)  
(KB958267)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=2a8d9a3b-b8a4-43b6-82a6-a2e7d16ae11d)  
(KB958304)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="3">
其他 Office 軟體
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-057**](http://technet.microsoft.com/security/bulletin/ms08-057)
</td>
<td style="border:1px solid black;">
[**MS08-056**](http://technet.microsoft.com/security/bulletin/ms08-056)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告最高嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 2003 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=9769ce08-5207-4c63-b7b9-536266ad6b2b)  
(KB955468)  
(重要)  
[Microsoft Office Excel Viewer 2003 Service Pack 3 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=9769ce08-5207-4c63-b7b9-536266ad6b2b)  
(KB955468)  
(重要)  
[Microsoft Office Excel Viewer](http://www.microsoft.com/downloads/details.aspx?familyid=83c88444-75b8-44d1-b280-3671394ade45)  
(KB955935)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Word、Excel 及 PowerPoint 2007 檔案格式的 Microsoft Office 相容性套件
</td>
<td style="border:1px solid black;">
[Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=9a7be004-5903-4101-90c5-c0d5f8722af9)  
(KB955936)  
(重要)  
[Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats Service Pack 1 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=9a7be004-5903-4101-90c5-c0d5f8722af9)  
(KB955936)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=5c29e646-504c-4455-9d35-9a1bed6d7535)\*  
(KB955937)  
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5c29e646-504c-4455-9d35-9a1bed6d7535)\*  
(KB955937)  
(重要)  
[Microsoft Office SharePoint Server 2007 x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=3c21c405-2c9e-45d0-be4d-8ccd093af31f)\*  
(KB955937)  
(重要)  
[Microsoft Office SharePoint Server 2007 x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3c21c405-2c9e-45d0-be4d-8ccd093af31f)\*  
(KB955937)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
</table>
 
\*此更新適用的伺服器必須已安裝 Excel Services，例如 Microsoft Office SharePoint Server 2007 Enterprise 和 Microsoft Office SharePoint Server 2007 For Internet Sites 的預設設定。 Microsoft Office SharePoint Server 2007 Standard 不包含 Excel Services。

#### Microsoft 伺服器軟體

 
<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Host Integration Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-059**](http://technet.microsoft.com/security/bulletin/ms08-059)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告最高嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Host Integration Server 2000
</td>
<td style="border:1px solid black;">
[Microsoft Host Integration Server 2000 Service Pack 2 (伺服器)](http://www.microsoft.com/downloads/details.aspx?familyid=11cca58b-59a4-4e93-9eb1-19b07c290a10)  
(重大)  
[Microsoft Host Integration Server 2000 Administrator Client](http://www.microsoft.com/downloads/details.aspx?familyid=41b49291-1231-4e23-aef7-818207453d56)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Host Integration Server 2004
</td>
<td style="border:1px solid black;">
[Microsoft Host Integration Server 2004 (伺服器)](http://www.microsoft.com/downloads/details.aspx?familyid=9ca255ed-9334-4848-af94-49ef3078cdc0)  
(重大)  
[Microsoft Host Integration Server 2004 Service Pack 1 (伺服器)](http://www.microsoft.com/downloads/details.aspx?familyid=eca756a1-ca56-4481-b23c-53c159a4e08c)  
(重大)  
[Microsoft Host Integration Server 2004 (用戶端)](http://www.microsoft.com/downloads/details.aspx?familyid=92cb54e7-f4ff-40a4-99cb-6257c4d8d4cd)  
(重大)  
[Microsoft Host Integration Server 2004 Service Pack 1 (用戶端)](http://www.microsoft.com/downloads/details.aspx?familyid=d776515c-09aa-4a04-876d-606bfc26a006)  
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Host Integration Server 2006
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Microsoft Host Integration Server 2006](http://www.microsoft.com/downloads/details.aspx?familyid=1ae79da3-ec17-4d4b-8011-d777a237ac93)  
(重大)  
[適用於 x64 型系統的 Microsoft Host Integration Server 2006](http://www.microsoft.com/downloads/details.aspx?familyid=05da4540-4976-458a-a612-7385d78695a2)  
(重大)
</td>
</tr>
</table>
 

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和安全性更新。 如需更多資訊，請參閱 [TechNet 更新管理中心](http://www.microsoft.com/taiwan/technet/updatemanagement/default.mspx) 。 [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) 提供 Microsoft 產品安全性的其他資訊。 消費者可以造訪[在家上網的安全性](http://go.microsoft.com/fwlink/?linkid=85102)網站，只要按一下 \[最新安全性更新\] 即可在此網站取得此資訊。

安全性更新可以從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)、[Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)及 [Office Update](http://go.microsoft.com/fwlink/?linkid=21135)取得。 安全性更新也可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得。 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。

最後，您可以從 [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) 下載安全性更新。 Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括安全性更新、驅動程式和 Service Pack。 只要以安全性公告編號 (例如，"MS07-036") 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。 如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](http://go.microsoft.com/fwlink/?linkid=97900)。

**偵測與部署指南**

Microsoft 已提供本月安全性更新之偵測與部署指南。 此指南還能幫助 IT 專業人員瞭解如何使用各項工具來協助部署安全性更新，像是 Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office Detection Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool (加強版安全性更新清查工具，ESUIT)。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 910723](http://support.microsoft.com/kb/910723)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少安全性更新以及一般安全性設定錯誤的狀況。 如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) 網站 (英文)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速可靠地將 Windows 2000 作業系統及更新系統版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 等最新的重大更新與安全性更新部署到 Windows 2000 及更新作業系統版本中。

如需更多關於利用 Windows Server Update Services 部署安全性更新的資訊，請造訪 [Windows Server Update Services](http://www.microsoft.com/taiwan/windowsserversystem/updateservices/evaluation/overview.mspx) 網站。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。 現已推出新版的 SMS，System Center Configuration Manager 2007；另請參閱 [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)。如需更多有關系統管理員如何能使用 SMS 2003 部署安全性更新的資訊，請參閱 [SMS 2003 安全性修補程式管理](http://go.microsoft.com/fwlink/?linkid=22939) (英文)。 SMS 2.0 使用者也可以利用 [SMS 軟體更新服務功能套件](http://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/suspack/default.htm)來協助部署安全性更新。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158)。

**注意：**SMS 使用 Microsoft Baseline Security Analyzer 及 Microsoft Office Detection Tool，為安全性公告更新的偵測及部署作業提供相當廣泛的支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可以用 Elevated Rights Deployment Tool (隨 [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) (英文) 和 [SMS 管理功能套件](http://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/adminpack/default.htm) (英文) 提供) 來安裝這些更新。

**Update Compatibility Evaluator 和 Application Compatibility Toolkit**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。 這可能會觸發不相容性，而拉長部署安全性更新的時間。 您可以使用 [Application Compatibility Toolkit 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 隨附的 [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 元件，針對所安裝的應用程式，簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Microsoft Windows Vista、Windows Update、Microsoft 安全性更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非安全性、高優先順序更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [icrosoft 知識庫文件編號 894199](http://support.microsoft.com/kb/894199)： Software Update Services 與 Windows Server Update Services 的說明內容在 2008 年有所變動。其中也包括所有 Windows 的內容。
-   [適用於 Microsoft 產品 (除了 Microsoft Windows 以外) 的全新、修訂版以及已發行的更新](http://technet.microsoft.com/en-us/wsus/bb466214.aspx)。

#### 安全性策略與社群

**更新程式管理策略**

[更新程式管理安全性指南](http://www.microsoft.com/taiwan/technet/security/topics/patchmanagement.mspx)提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](http://support.microsoft.com/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](http://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](http://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 [NetAgent Co.,Ltd](http://www.netagent.co.jp/) 回報 MS08-056 中描述的問題
-   感謝 [iDefense](http://labs.idefense.com/) 的 Joshua J. Drake 回報 MS08-057 中描述的問題。
-   感謝 Wushi 與 [TippingPoint](http://www.tippingpoint.com/) 及 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 MS08-057 中描述的問題
-   感謝 [Labo Skopia](http://www.laboskopia.com/) 的 Lionel d'Hauenens 與 [iDefense VCP](http://labs.idefense.com/) 合作，共同回到 MS08-057 中描述的問題 。
-   感謝 David Bloom 回報 MS08-058 中描述的問題
-   感謝 Gregory Rubin 回報 MS08-058 中描述的問題
-   感謝 [Ivan Fratric](http://ifsec.blogspot.com/) 與 [TippingPoint](http://www.tippingpoint.com/) 及 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 MS08-058 中描述的問題
-   感謝 [n.runs](http://www.nruns.com/) 的 Thierry Zoller 回報 MS08-058 中描述的問題
-   感謝 [Composica](http://www.composica.com/) 的 Lee Dagon 回報 MS08-058 中描述的問題
-   感謝 [Harmony Security](http://www.harmonysecurity.com/) 的 Stephen Fewer 與 [iDefense VCP](http://labs.idefense.com/) 合作回報 MS08-059 中描述的問題
-   感謝 [nCircle](http://www.ncircle.com/) 的 Paul Miseiko 回報 MS08-060 中描述的問題
-   感謝 [iShadow](http://www.ishadow.com/) 的 Paul Catonfor 回報 MS08-061 中描述的問題
-   感謝 [SkyRecon](http://www.skyrecon.com/) 的 Thomas Garnier 回報 MS08-061 中描述的問題
-   感謝[CERT/CC](http://www.cert.org/) 回報 MS08-062 中描述的問題
-   感謝 [Codenomicon](http://www.codenomicon.com/) 的 Joshua Morin 回報 MS08-063 中描述的問題
-   感謝 [TippingPoint DVLabs](http://dvlabs.tippingpoint.com) 的 Cody Pierce 和 Aaron Portnoy 回報 MS08-065 中描述的問題
-   感謝 [SkyRecon](http://www.skyrecon.com/) 的 Fabien Le Mentec 回報 MS08-066 中描述的問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可電洽 1-866-PCSAFETY [Microsoft 產品支援服務](http://go.microsoft.com/fwlink/?linkid=21131)以取得技術支援。 與安全性更新有關的支援電話不另外收費。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與安全性更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](http://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2008 年 10 月 15 日)： 公告摘要發行。
-   V2.0 (2008 年 10 月 16 日)： 移除適用於 Itanium 型系統之 Windows Server 2008 的嚴重性等級 (MS08-062)。
-   V2.1 (2008 年 10 月 16 日)： 更新 Microsoft 安全性公告 MS08-062 的提要。
-   V3.0 (2008 年 10 月 24 日)： 新增 Microsoft 安全性公告 MS08-067：Server 服務中的弱點可能會允許遠端執行程式碼 (958644)。

*Built at 2014-04-18T01:50:00Z-07:00*
