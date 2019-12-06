---
TOCTitle: 'MS08-AUG'
Title: 2008 年 8 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms08-aug'
ms:contentKeyID: 61237678
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms08-aug(v=Security.10)'
---

2008 年 8 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2008年8月13日

**版本:** 1.0

此公告摘要列出 2008 年 8 月份發行之安全性公告。

發行 2008 年 8 月份公告之後，此公告摘要將取代原先於 2008 年 8 月 7 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](http://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2008 年 8 月 13 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。 [立即註冊參加 8 月份安全性公告網路廣播](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032374631&culture=en-us)。 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](http://www.microsoft.com/taiwan/security/bulletins/default.mspx)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性、高優先順序更新的優先順序，其中這些非安全性、高優先順序更新的發行日期與每月安全性更新的發行日期相同。 請參閱＜其他資訊＞一節。

### 公告資訊

#### 提要

本月份安全性公告依嚴重性列出如下：

重大 (6)
--------

<span></span>

| 公告編號             | Microsoft 安全性公告 MS08-046                                                                                                                                                                                                                                                                                                                                                             |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Microsoft Windows 影像色彩管理系統中的弱點可能會允許遠端執行程式碼 (952954)**](http://technet.microsoft.com/security/bulletin/ms08-046)                                                                                                                                                                                                                                                |
| **提要**             | 此更新程式解決 Microsoft 影像色彩管理 (ICM) 系統中未公開報告的弱點，該弱點可能會在目前使用者的環境中允許遠端執行程式碼。 如果使用者以系統管理的使用者權限登入，成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                             |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                                            |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 本更新程式需要重新開機。                                                                                                                                                                                                                                                                                        |
| **受影響的軟體**     | **Microsoft Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                                              |

| 公告編號             | Microsoft 安全性公告 MS08-045                                                                                                                                                                                                               |
|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Internet Explorer 積存安全性更新 (953838)**](http://technet.microsoft.com/security/bulletin/ms08-045)                                                                                                                                    |
| **提要**             | 這個安全性更新可解決五項未公開報告的弱點，以及一項已公開揭露的弱點。 如果使用者使用 Internet Explorer 檢視蓄意製作的網頁，這些弱點均會允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                               |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                              |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 本更新程式需要重新開機。                                                                                                                                          |
| **受影響的軟體**     | **Microsoft Windows、Internet Explorer。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                             |

| 公告編號             | Microsoft 安全性公告 MS08-041                                                                                                                                                                                                                     |
|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Microsoft Access 的 Snapshot Viewer 的 ActiveX 控制項弱點可能會允許遠端執行程式碼 (955617)**](http://technet.microsoft.com/security/bulletin/ms08-041)                                                                                         |
| **提要**             | 此安全性更新可解決 Microsoft Access 中 Snapshot Viewer 的 ActiveX 控制項中未公開報告的弱點。 攻擊者可蓄意製作網頁以利用此弱點。 當使用者檢視網頁時，此弱點可能會允許遠端執行程式碼。 成功利用此弱點的攻擊者可以取得與登入使用者相同的使用者權限。 |
| **最高的嚴重性等級** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                     |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                    |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新不需要重新開機。                                                                                                                                                  |
| **受影響的軟體**     | **Microsoft Office：** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                       |

| 公告編號             | Microsoft 安全性公告 MS08-043                                                                                                                                                                                                                                                                                                                                    |
|----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Microsoft Excel 中的弱點可能會允許遠端執行程式碼 (954066)**](http://technet.microsoft.com/security/bulletin/ms08-043)                                                                                                                                                                                                                                         |
| **提要**             | 此安全性更新可解決 Microsoft Office Excel 中四項未公開報告的弱點，該弱點可在使用者開啟蓄意製作的 Excel 檔案時，允許遠端執行程式碼。 成功利用這類弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                    |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                   |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新不需要重新開機。                                                                                                                                                                                                                                                                 |
| **受影響的軟體**     | **Microsoft Office：** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                      |

| 公告編號             | Microsoft 安全性公告 MS08-051                                                                                                                                                                                                                                                                                                                                                                                        |
|----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Microsoft PowerPoint 中的弱點可能會允許遠端執行程式碼 (949785)**](http://technet.microsoft.com/security/bulletin/ms08-051)                                                                                                                                                                                                                                                                                        |
| **提要**             | 此安全性更新可解決 Microsoft Office PowerPoint 和 Microsoft Office PowerPoint Viewer 中三項未公開報告的弱點，這些弱點可在使用者開啟蓄意製作的 PowerPoint 檔案時，允許從遠端執行程式碼。 成功利用這些弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                        |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                                                                       |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新不需要重新開機。                                                                                                                                                                                                                                                                                                                     |
| **受影響的軟體**     | **Microsoft Office：** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                                                                          |

| 公告編號             | Microsoft 安全性公告 MS08-044                                                                                                                                                                                        |
|----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Microsoft Office 篩選器的弱點可能會允許遠端執行程式碼 (924090)**](http://technet.microsoft.com/security/bulletin/ms08-044)                                                                                        |
| **提要**             | 這個安全性更新可解決五項未公開報告的弱點。 如果使用者使用 Microsoft Office 檢視蓄意製作的影像檔，這些弱點可能會允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                        |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                       |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新不需要重新開機。                                                                                                                     |
| **受影響的軟體**     | **Microsoft Office：** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                          |

重要 (5)
--------

<span></span>

| 公告編號             | Microsoft 安全性公告 MS08-047                                                                                                                                                                                                                                                                                                                                                  |
|----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**IPsec 原則處理中的弱點可能會導致資訊洩漏 (953733)**](http://technet.microsoft.com/security/bulletin/ms08-047)                                                                                                                                                                                                                                                               |
| **提要**             | 此更新可解決特定 Windows 網際網路通訊協定安全性 (IPsec) 規則套用方式中一項未公開報告的弱點。 此弱點可能導致系統忽略純文字的 IPsec 原則及傳輸網路流量。 隨後將洩露網路上要加密的資訊。 檢視網路流量的攻擊者就可以檢視流量的內容，而且或許能進一步修改流量內容。 請注意，這個弱點不會直接允許攻擊者執行程式碼或提升權限， 但可能會用來收集可以進一步破壞受影響系統或網路的資訊。 |
| **最高的嚴重性等級** | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                  |
| **弱點的影響**       | 資訊洩漏                                                                                                                                                                                                                                                                                                                                                                       |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 本更新程式需要重新開機。                                                                                                                                                                                                                                                                             |
| **受影響的軟體**     | **Microsoft Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                                   |

| 公告編號             | Microsoft 安全性公告 MS08-049                                                                                                                                                                                                                           |
|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**事件系統中的弱點可能會允許遠端執行程式碼 (950974)**](http://technet.microsoft.com/security/bulletin/ms08-049)                                                                                                                                        |
| **提要**             | 這個安全性更新可解決 Microsoft Windows 事件系統中兩個未公開報告的弱點，該弱點可能允許遠端執行程式碼。 成功利用這類弱點的攻擊者可以取得受影響系統的完整控制權。 接下來，攻擊者就能安裝程式，檢視、變更或刪除資料，或是建立具有完整系統管理權限的新帳戶。 |
| **最高的嚴重性等級** | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                           |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                          |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 本更新程式需要重新開機。                                                                                                                                                      |
| **受影響的軟體**     | **Microsoft Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                            |

| 公告編號             | Microsoft 安全性公告 MS08-048                                                                                                                                                                                                                  |
|----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**適用於 Outlook Express 和 Windows Mail 的安全性更新 (951066)**](http://technet.microsoft.com/security/bulletin/ms08-048)                                                                                                                    |
| **提要**             | 這個安全性更新可解決 Outlook Express 和 Windows Mail 中一項未公開報告的弱點。 如果使用者使用 Internet Explorer 造訪蓄意製作的網頁，此弱點可能會允許資訊洩漏。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                  |
| **弱點的影響**       | 資訊洩漏                                                                                                                                                                                                                                       |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新可能需要重新啟動電腦。                                                                                                                                         |
| **受影響的軟體**     | **Microsoft Windows、Outlook Express、Windows Mail。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                    |

| 公告編號             | Microsoft 安全性公告 MS08-050                                                                                                                                                                                                                                                                                                                     |
|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Windows Messenger 中的弱點可能會導致資訊洩漏 (955702)**](http://technet.microsoft.com/security/bulletin/ms08-050)                                                                                                                                                                                                                              |
| **提要**             | 此安全性更新解決了受支援版本 Windows Messenger 中一項公開報告的弱點。 由於這個弱點存在，ActiveX 控制項的指令碼處理可能洩漏已登入使用者的資訊。 攻擊者可能會在已登入使用者不知情的情況下，變更狀態、取得連絡人資訊，以及啟動音效和視訊聊天工作階段。 攻擊者也可能擷取使用者的登入帳號，然後從遠端登入該使用者的 Messenger 用戶端，假扮為該使用者。 |
| **最高的嚴重性等級** | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                     |
| **弱點的影響**       | 資訊洩漏                                                                                                                                                                                                                                                                                                                                          |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 本更新程式需要重新開機。                                                                                                                                                                                                                                                |
| **受影響的軟體**     | **Microsoft Windows、Windows Messenger。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                   |

| 公告編號             | Microsoft 安全性公告 MS08-042                                                                                                                                                                                                                                                                                                                                |
|----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Microsoft Word 的弱點可能會允許遠端執行程式碼 (955048)**](http://technet.microsoft.com/security/bulletin/ms08-042)                                                                                                                                                                                                                                        |
| **提要**             | 這個安全性更新可解決 Microsoft Word 中已公開報告的一項弱點。 如果使用者開啟蓄意製作的 Word 檔案，此弱點可能會允許遠端執行程式碼。 成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                               |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新不需要重新開機。                                                                                                                                                                                                                                                             |
| **受影響的軟體**     | **Microsoft Office：** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                  |

受影響的軟體及下載位置
----------------------

<span></span>
**我該如何使用這個表格？**

請用這個表格來瞭解可能需要安裝的安全性更新有哪些。 您應該查看此處列出的每一種軟體程式或元件，看看是否有需要的安全性更新。 若軟體程式或更新出現在清單中，則相關可用軟體更新也會以超連結方式提供，也會列出軟體更新的嚴重性等級。

**注意**：一項弱點，可能需要安裝數個安全性更新才能妥善解決。 請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。

#### Windows 作業系統

 
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
</tr>
<tr>
<th colspan="7">
Microsoft Windows 2000
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-046**](http://technet.microsoft.com/security/bulletin/ms08-046)
</td>
<td style="border:1px solid black;">
[**MS08-045**](http://technet.microsoft.com/security/bulletin/ms08-045)
</td>
<td style="border:1px solid black;">
[**MS08-047**](http://technet.microsoft.com/security/bulletin/ms08-047)
</td>
<td style="border:1px solid black;">
[**MS08-049**](http://technet.microsoft.com/security/bulletin/ms08-049)
</td>
<td style="border:1px solid black;">
[**MS08-048**](http://technet.microsoft.com/security/bulletin/ms08-048)
</td>
<td style="border:1px solid black;">
[**MS08-050**](http://technet.microsoft.com/security/bulletin/ms08-050)
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
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=db455d17-435f-46d7-b2dd-5babb5a1eeb3)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=1557b93b-ecba-4f42-b89d-db0ee067d65b)  
(重大)  
[Microsoft Internet Explorer 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=aa780735-5928-4c46-89a4-63a814954796)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=1b2ad648-7dc9-407a-99f6-f39922746027)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 5.5 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=6257bfae-35f0-4c0e-b960-bca7aa6f86f7)  
(重要)  
[Microsoft Outlook Express 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=dab178f7-c282-41f4-acb1-a86e6aa4c91b)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Messenger 5.1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774)  
(KB899283)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-046**](http://technet.microsoft.com/security/bulletin/ms08-046)
</td>
<td style="border:1px solid black;">
[**MS08-045**](http://technet.microsoft.com/security/bulletin/ms08-045)
</td>
<td style="border:1px solid black;">
[**MS08-047**](http://technet.microsoft.com/security/bulletin/ms08-047)
</td>
<td style="border:1px solid black;">
[**MS08-049**](http://technet.microsoft.com/security/bulletin/ms08-049)
</td>
<td style="border:1px solid black;">
[**MS08-048**](http://technet.microsoft.com/security/bulletin/ms08-048)
</td>
<td style="border:1px solid black;">
[**MS08-050**](http://technet.microsoft.com/security/bulletin/ms08-050)
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
[Windows XP Service Pack 2 與 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=d313f42c-f43f-48ea-82ef-3bc33077c7fa)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=69af2f30-138e-4b15-ab8d-4fce44cc0bc2)  
(重大)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=8e2125c7-52cb-4052-82a3-2d3c6a953752)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 與 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=01a34aa4-a456-4efc-a93a-c3c682b0181c)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=91469f2f-461c-4a67-8738-d42520427f6b)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Messenger 4.7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=8f588f7e-c4ed-42a0-b157-54b1eda60474)  
(KB946648)  
(重要)  
[Windows Messenger 5.1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774)  
(KB899283)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2 (英文下載更新程式)](https://www.microsoft.com/download/details.aspx?familyid=3150c6b8-f50b-4b84-a7ce-c8daf77c080c)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6 (英文下載更新程式)](https://www.microsoft.com/download/details.aspx?familyid=4780b89e-9735-4d3f-8def-34e7337ff604)  
(重大)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=39b41e4b-3237-409d-a818-ab0517c5e7cf)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=246b2686-e330-47a2-b4d4-68f218ad4021)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6 (英文下載更新程式)](https://www.microsoft.com/download/details.aspx?familyid=2220aece-79d2-426f-90ec-24a17470567a)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Messenger 4.7 (英文下載更新程式)](https://www.microsoft.com/download/details.aspx?familyid=a5fc5457-832f-4ee8-be60-4cc8518d1c10)  
(KB946648)  
(重要)  
[Windows Messenger 5.1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774)  
(KB899283)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-046**](http://technet.microsoft.com/security/bulletin/ms08-046)
</td>
<td style="border:1px solid black;">
[**MS08-045**](http://technet.microsoft.com/security/bulletin/ms08-045)
</td>
<td style="border:1px solid black;">
[**MS08-047**](http://technet.microsoft.com/security/bulletin/ms08-047)
</td>
<td style="border:1px solid black;">
[**MS08-049**](http://technet.microsoft.com/security/bulletin/ms08-049)
</td>
<td style="border:1px solid black;">
[**MS08-048**](http://technet.microsoft.com/security/bulletin/ms08-048)
</td>
<td style="border:1px solid black;">
[**MS08-050**](http://technet.microsoft.com/security/bulletin/ms08-050)
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
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=828d8fdc-8534-4621-85a5-08aec255496f)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=0617a5dd-dce9-4de0-b0a0-ce38efe13524)  
(重大)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=b3c2e2fd-1cb9-491b-937c-053dd59a65bf)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=92a3d08f-c117-4b24-bc78-2b913d270df6)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=30f2244a-f6fd-4fc1-a871-abf6958cb660)  
(輕微)
</td>
<td style="border:1px solid black;">
[Windows Messenger 4.7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=302315a8-ccb2-47c2-9104-b8e1d1f49aa0)  
(KB954723)  
(中度)  
[Windows Messenger 5.1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774)  
(KB899283)  
(中度)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0a13776f-d543-41df-b904-d51e368c81cc)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=32a63f52-9fe6-48e3-bb4e-7d4dda5e0a90)  
(重大)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=88a26b76-f7df-45c9-8ed0-7d3cd71c1987)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows 2003 Server x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=6bfbb6d8-5106-4adf-83cb-35ffc6e8eaf8)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=3287f006-cbb2-4c6d-820c-32833e08035a)  
(輕微)
</td>
<td style="border:1px solid black;">
[Windows Messenger 4.7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=be94d138-7d7b-489e-baa6-e214950be6b9)  
(KB954723)  
(中度)  
[Windows Messenger 5.1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774)  
(KB899283)  
(中度)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP1 for Itanium-based Systems 和 Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP1 和適用於 Itanium 型系統的 Windows Server 2003 SP2(英文下載更新程式)](https://www.microsoft.com/download/details.aspx?familyid=9566493f-4260-4072-947a-527887d2cd63)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6 (英文下載更新程式)](https://www.microsoft.com/download/details.aspx?familyid=1855997e-a3be-46b1-a0bc-bb55eb0045fe)  
(重大)  
[Windows Internet Explorer 7 (英文下載更新程式)](https://www.microsoft.com/download/details.aspx?familyid=97d0d37d-5d76-4bc3-8cbd-1e3976c82acf)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP1 和適用於 Itanium 型系統的 Windows Server 2003 SP2 (英文下載更新程式)](https://www.microsoft.com/download/details.aspx?familyid=45356565-697f-41b3-9879-3edd11dbcb7e)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6 (英文下載更新程式)](https://www.microsoft.com/download/details.aspx?familyid=c8570e40-355b-4a9b-933d-53ae021cbda5)  
(輕微)
</td>
<td style="border:1px solid black;">
[Windows Messenger 4.7 (英文下載更新程式)](https://www.microsoft.com/download/details.aspx?familyid=e4b72618-536b-4a21-bd91-d91be9ca24e5)  
(KB954723)  
(中度)  
[Windows Messenger 5.1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774)  
(KB899283)  
(中度)
</td>
</tr>
<tr>
<th colspan="7">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-046**](http://technet.microsoft.com/security/bulletin/ms08-046)
</td>
<td style="border:1px solid black;">
[**MS08-045**](http://technet.microsoft.com/security/bulletin/ms08-045)
</td>
<td style="border:1px solid black;">
[**MS08-047**](http://technet.microsoft.com/security/bulletin/ms08-047)
</td>
<td style="border:1px solid black;">
[**MS08-049**](http://technet.microsoft.com/security/bulletin/ms08-049)
</td>
<td style="border:1px solid black;">
[**MS08-048**](http://technet.microsoft.com/security/bulletin/ms08-048)
</td>
<td style="border:1px solid black;">
[**MS08-050**](http://technet.microsoft.com/security/bulletin/ms08-050)
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
不適用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=13cba012-dd20-48f9-8e44-e4cb104c4cad)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=3f21a8a2-9861-4fef-9d1e-caf5f7822c1a)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=6418c78f-f008-4028-beb1-5a5ea8e797a1)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Mail](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=3851bcf8-f971-4d38-b27f-97396854aac0)  
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
不適用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=ead919c2-d548-47b7-9cd6-80f991266428)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=aa04a754-fbfb-42a7-89d2-14373e3f4742)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=e03ccfb0-3ea3-4c59-adcf-9882d7086013)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Mail](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=3bf7eb8a-b347-4661-be2d-682adc713769)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-046**](http://technet.microsoft.com/security/bulletin/ms08-046)
</td>
<td style="border:1px solid black;">
[**MS08-045**](http://technet.microsoft.com/security/bulletin/ms08-045)
</td>
<td style="border:1px solid black;">
[**MS08-047**](http://technet.microsoft.com/security/bulletin/ms08-047)
</td>
<td style="border:1px solid black;">
[**MS08-049**](http://technet.microsoft.com/security/bulletin/ms08-049)
</td>
<td style="border:1px solid black;">
[**MS08-048**](http://technet.microsoft.com/security/bulletin/ms08-048)
</td>
<td style="border:1px solid black;">
[**MS08-050**](http://technet.microsoft.com/security/bulletin/ms08-050)
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
不適用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=4b52ff2f-d2f5-4c20-b6cf-86d86c56b0f8)\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=c3363df6-39dc-4910-9ce5-66553155378e)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=0640f95e-1eee-4dd1-b4dd-2b82b7e984b9)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Mail](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=dc3c4b63-acd3-4469-8d47-e0562d99ee65)\*\*  
(輕微)
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
不適用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=df9814a6-5be0-4ac1-a767-a0eae8d5ee5d)\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=39dd1722-412b-469d-a475-b6513764838c)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=51a93538-5e94-4f81-a6e0-d497a7b4899d)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Mail](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=5f973f54-2322-4b41-8c1a-3e712c0da8ae)\*\*  
(輕微)
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
不適用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7 (英文下載更新程式)](https://www.microsoft.com/download/details.aspx?familyid=ffc3cfcb-73fe-4a6d-9595-e9d7a5b3d3f7)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 (英文下載更新程式)](https://www.microsoft.com/download/details.aspx?familyid=e9c6cd46-30ad-46ee-9c8b-d0b446e660c4)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 (英文下載更新程式)](https://www.microsoft.com/download/details.aspx?familyid=390da130-749d-4890-aad7-be91e15b32bb)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Mail (英文下載更新程式)](https://www.microsoft.com/download/details.aspx?familyid=9226cd85-1445-4976-a126-757c5d142ffd)  
(輕微)
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
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="6">
Microsoft Office 套件、系統和元件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-041**](http://technet.microsoft.com/security/bulletin/ms08-041)
</td>
<td style="border:1px solid black;">
[**MS08-043**](http://technet.microsoft.com/security/bulletin/ms08-043)
</td>
<td style="border:1px solid black;">
[**MS08-051**](http://technet.microsoft.com/security/bulletin/ms08-051)
</td>
<td style="border:1px solid black;">
[**MS08-044**](http://technet.microsoft.com/security/bulletin/ms08-044)
</td>
<td style="border:1px solid black;">
[**MS08-042**](http://technet.microsoft.com/security/bulletin/ms08-042)
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
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works 8
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
[Microsoft Works 8](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=458985c3-9c6f-4049-81cd-0d0389c81f11)  
(KB955428)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Access 2000 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=54e4031d-298f-480c-88d5-0ad3b2b62ba9)  
(KB955441)  
(重大)
</td>
<td style="border:1px solid black;">
[Excel 2000 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=4bf8688e-e5b9-4e53-a1a1-8cf1acfdb80b)  
(KB951582)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2000 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=e7c044d8-778a-4985-b25b-4f7f6e4abadd)  
(KB949007)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2000 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=3ab323ec-9f92-453c-b7c7-9a95a9efcaea)  
(KB921595)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Access 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=34b655f8-1922-4246-94ca-ed381c3e3b13)  
(KB955440)  
(重大)
</td>
<td style="border:1px solid black;">
[Excel 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=9bbf7550-f5c4-4b9b-bd86-1e7be6c42eb5)  
(KB951551)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=f8921074-7985-4d42-ac2b-d2f3b1d466ba)  
(KB948995)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=bf566ce6-23da-45e5-9c2b-c47331d30e79)  
(KB921596)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Word 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=c7146dfc-e1be-4d13-877b-1d9bcacc4a64)  
(KB954463)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 2 和 Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Access 2003 Service Pack 2 和 Microsoft Office Access 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=fd698517-a504-427d-9e5f-fde8f102142c)  
(KB955439)  
(重大)
</td>
<td style="border:1px solid black;">
[Excel 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=fc612e9a-bdf3-4952-8ada-0de5a50973f0)  
(KB951548)  
(重要)  
[Excel 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=fc612e9a-bdf3-4952-8ada-0de5a50973f0)  
(KB951548)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=7a7c21f0-5e0e-4dee-9710-1ce3d565913f)  
(KB948988)  
(重要)  
[Microsoft Office PowerPoint 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=7a7c21f0-5e0e-4dee-9710-1ce3d565913f)  
(KB948988)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=e0df2f6e-1102-461d-829f-5f3e2d7eb4b3)  
(KB921598)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Word 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=13a37b76-9fec-426f-8176-3c95f934efe0)  
(KB954464)  
(重要)  
[Microsoft Word 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=13a37b76-9fec-426f-8176-3c95f934efe0)  
(KB954464)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System 和 2007 Microsoft Office System Service Pack 1
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Excel 2007](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=2753e8d6-e156-49ef-af2d-4c521c808ffd)  
(KB951546)  
(重要)  
[Excel 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=2753e8d6-e156-49ef-af2d-4c521c808ffd)  
(KB951546)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2007](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=55fd618a-e9c5-4f1e-b9a5-b2e47ec98ef1)  
(KB951338)  
(重要)  
[Microsoft Office PowerPoint 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=55fd618a-e9c5-4f1e-b9a5-b2e47ec98ef1)  
(KB951338)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="6">
其他 Office 軟體
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-041**](http://technet.microsoft.com/security/bulletin/ms08-041)
</td>
<td style="border:1px solid black;">
[**MS08-043**](http://technet.microsoft.com/security/bulletin/ms08-043)
</td>
<td style="border:1px solid black;">
[**MS08-051**](http://technet.microsoft.com/security/bulletin/ms08-051)
</td>
<td style="border:1px solid black;">
[**MS08-044**](http://technet.microsoft.com/security/bulletin/ms08-044)
</td>
<td style="border:1px solid black;">
[**MS08-042**](http://technet.microsoft.com/security/bulletin/ms08-042)
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
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Project 2002
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
[Microsoft Project 2002 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=bf566ce6-23da-45e5-9c2b-c47331d30e79)  
(KB921596)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Access 的 Snapshot Viewer
</td>
<td style="border:1px solid black;">
Microsoft Access 的 Snapshot Viewer\*
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
Microsoft Office PowerPoint Viewer 2003
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint Viewer 2003](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=911c8872-dec8-4b8e-9708-93dcabd3e036)  
(KB949041)  
(重要)
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
Microsoft Office Excel Viewer 和 Microsoft Office Excel Viewer 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 2003](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=d7ed9e75-15f2-4950-98b3-93023ba0f4c1)  
(KB951589)  
(重要)  
[Microsoft Office Excel Viewer 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=d7ed9e75-15f2-4950-98b3-93023ba0f4c1)  
(KB951589)  
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel Viewer
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=b574d906-7f09-49b0-80bf-e84dee8c4583)  
(KB955472)  
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Converter Pack
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
[Microsoft Office Converter Pack (英文下載更新程式)](https://www.microsoft.com/download/details.aspx?familyid=199b08c7-6d79-4930-8f0c-31034629c485)  
(KB925256)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats 和 Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats Service Pack 1
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=7afdae9b-9c74-4af7-9844-0e54221ea3b9)  
(KB951596)  
(重要)  
[Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=7afdae9b-9c74-4af7-9844-0e54221ea3b9)  
(KB951596)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=84ce5d58-0010-4945-bce9-67a41f898f2f) (KB954038)  
(重要)  
[Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=84ce5d58-0010-4945-bce9-67a41f898f2f) (KB954038)  
(重要)
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
Microsoft Office SharePoint Server 2007 和 Microsoft Office SharePoint Server 2007 Service Pack 1
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=a7731749-b026-4765-808a-e151b990f0e1)  
(KB953397)  
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=a7731749-b026-4765-808a-e151b990f0e1)  
(KB953397)  
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 x64 Edition 和 Microsoft Office SharePoint Server 2007 x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 x64 Edition](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=fc95ab88-2d31-44e1-a702-7cb10e83695b)  
(KB953397)  
(重要)  
[Microsoft Office SharePoint Server 2007 x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=fc95ab88-2d31-44e1-a702-7cb10e83695b)  
(KB953397)  
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
</tr>
<tr>
<th colspan="6">
Microsoft Office for Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-041**](http://technet.microsoft.com/security/bulletin/ms08-041)
</td>
<td style="border:1px solid black;">
[**MS08-043**](http://technet.microsoft.com/security/bulletin/ms08-043)
</td>
<td style="border:1px solid black;">
[**MS08-051**](http://technet.microsoft.com/security/bulletin/ms08-051)
</td>
<td style="border:1px solid black;">
[**MS08-044**](http://technet.microsoft.com/security/bulletin/ms08-044)
</td>
<td style="border:1px solid black;">
[**MS08-042**](http://technet.microsoft.com/security/bulletin/ms08-042)
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
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac (英文下載更新程式)](https://www.microsoft.com/download/details.aspx?familyid=ebd3af0c-3f62-4d18-bf45-881655683bd5)  
(KB956343)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac (英文下載更新程式)](https://www.microsoft.com/download/details.aspx?familyid=ebd3af0c-3f62-4d18-bf45-881655683bd5)  
(KB953824)  
(重要)
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
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac (英文下載更新程式)](https://www.microsoft.com/download/details.aspx?familyid=9515c70d-be80-4ade-856a-ea542f7d84e1)  
(KB956344)  
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
</tr>
</table>
 
**\*Microsoft Access 的 Snapshot Viewer (MS08-041) 注意事項：** Microsoft 目前正針對這個受影響軟體開發更新，並會盡快發行安全性更新。 當安全性更新發行時，Microsoft 將會同時更新安全性公告及其公告摘要。

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和安全性更新。 如需更多資訊，請參閱 [TechNet 更新管理中心](http://www.microsoft.com/taiwan/technet/updatemanagement/default.mspx) 。 [TechNet Security Center](http://www.microsoft.com/taiwan/technet/security/default.mspx) 提供 Microsoft 產品安全性的其他資訊。 消費者可以造訪[在家上網的安全性](http://www.microsoft.com/taiwan/athome/security/default.mspx)網站，只要按一下 \[最新安全性更新\] 即可在此網站取得此資訊。

安全性更新可以從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)、[Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)及 [Office Update](http://office.microsoft.com/zh-tw/downloads/default.aspx)取得。 安全性更新也可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得。 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。

最後，您可以從 [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) 下載安全性更新。 Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括安全性更新、驅動程式和 Service Pack。 只要以安全性公告編號 (例如，"MS07-036") 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。 如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](http://go.microsoft.com/fwlink/?linkid=97900)。

**偵測與部署指南**

Microsoft 已提供本月安全性更新之偵測與部署指南。 此指南還能幫助 IT 專業人員瞭解如何使用各項工具來協助部署安全性更新，像是 Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office Detection Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool (加強版安全性更新清查工具，ESUIT)。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 910723](http://support.microsoft.com/kb/910723)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少安全性更新以及一般安全性設定錯誤的狀況。 如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) 網站 (英文)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速可靠地將 Windows 2000 作業系統及更新系統版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 等最新的重大更新與安全性更新部署到 Windows 2000 及更新作業系統版本中。

如需更多關於利用 Windows Server Update Services 部署安全性更新的資訊，請造訪 [Windows Server Update Services](http://www.microsoft.com/taiwan/windowsserversystem/updateservices/evaluation/overview.mspx) 網站。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。 現已推出新版的 SMS，System Center Configuration Manager 2007；另請參閱 [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)。如需更多有關系統管理員如何能使用 SMS 2003 部署安全性更新的資訊，請參閱 [SMS 2003 安全性修補程式管理](http://www.microsoft.com/taiwan/smserver/evaluation/capabilities/patch.htm) 。 SMS 2.0 使用者也可以利用 [SMS 軟體更新服務功能套件](http://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/suspack/default.htm)來協助部署安全性更新。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server](http://www.microsoft.com/taiwan/smserver/)。

**注意：**SMS 使用 Microsoft Baseline Security Analyzer 及 Microsoft Office Detection Tool，為安全性公告更新的偵測及部署作業提供相當廣泛的支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可以用 Elevated Rights Deployment Tool (隨 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/taiwan/smserver/downloads/2003/adminpack.htm) 和 [SMS 管理功能套件](http://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/adminpack/default.htm) 提供) 來安裝這些更新。

**Update Compatibility Evaluator 和應用程式相容性工具組**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。 這可能會觸發不相容性，而拉長部署安全性更新的時間。 您可以使用 [Application Compatibility Toolkit 5.0](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 隨附的 [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 元件，針對所安裝的應用程式，簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Microsoft Windows Vista、Windows Update、Microsoft 安全性更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非安全性、高優先順序更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](http://support.microsoft.com/kb/894199)： Software Update Services 與 Windows Server Update Services 的說明內容在 2008 年有所變動。其中也包括所有 Windows 的內容。
-   [適用於 Microsoft 產品 (除了 Microsoft Windows 以外) 的全新、修訂版以及已發行的更新](http://technet.microsoft.com/en-us/wsus/bb466214.aspx)。

#### 安全性策略與社群

**更新程式管理策略**

[更新管理安全性指南](http://www.microsoft.com/taiwan/technet/security/topics/patchmanagement.mspx) 提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](http://support.microsoft.com/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](http://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](http://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 [ISC/SANS](http://isc.sans.org/) 回報 MS08-042 中描述的問題
-   感謝 [VeriSign iDefense](http://www.idefense.com/vcp) VCP 回報 MS08-043 中描述的問題
-   感謝 [TippingPoint](http://www.tippingpoint.com/) 和 [Zero Day Initiative](http://www.zerodayinitiative.com/) 回報 MS08-043 中描述的問題
-   感謝 Jeremy Funk 回報 MS08-043 中描述的問題
-   感謝 [NGS Software](http://www.nextgenss.com/) 的 Shaun Colley 回報 MS08-044 中描述的問題
-   感謝 [Zero Day Initiative (ZDI)](http://www.zerodayinitiative.com/) 回報 MS08-044 中描述的問題
-   感謝匿名研究人員與 [iDefense VCP](http://labs.idefense.com/) 合作回報 MS08-044 中描述的問題
-   感謝 Damian Put 與 [iDefense VCP](http://labs.idefense.com/) 合作回報 MS08-044 中描述的問題
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Yamata Li 回報 MS08-045 中描述的問題
-   感謝 [Google Security Team](http://www.google.com/) 的 Tavis Ormandy 回報 MS08-045 中描述的問題
-   感謝 Sam Thomas 與 [TippingPoint](http://www.tippingpoint.com/) 及 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 MS08-045 中描述的問題
-   感謝 [TippingPoint](http://www.tippingpoint.com/) 和 [Zero Day Initiative](http://www.zerodayinitiative.com/) 回報 MS08-045 中描述的問題
-   感謝 [VeriSign iDefense Labs](http://labs.idefense.com/) 的 Jun Mao 回報 MS08-046 中描述的問題
-   感謝 [Core Security Technologies](http://www.coresecurity.com/) 的 Jorge Luis Alvarez Medina 回報 MS08-048 中描述的問題
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Yamata Li 回報 MS08-049 中描述的問題
-   感謝 [Fortinet Security Response Team](http://www.fortinet.com/) 的 Haifei Li (cocoruder) 回報 MS08-050 中描述的問題
-   感謝 [Reversemode.com](http://reversemode.com/) 的 Ruben Santamarta 與 [iDefense Labs](http://labs.idefense.com/) 合作回報 MS08-051 中描述的問題
-   感謝 [Venustech](http://www.venustech.com.cn/) 的 ADLab 回報 MS08-051 中描述的問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可電洽 1-866-PCSAFETY [Microsoft 產品支援服務](http://go.microsoft.com/fwlink/?linkid=21131)以取得技術支援。 與安全性更新有關的支援電話不另外收費。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與安全性更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](http://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2008 年 8 月 13 日)： 公告摘要發行。

*Built at 2014-04-18T01:50:00Z-07:00*
