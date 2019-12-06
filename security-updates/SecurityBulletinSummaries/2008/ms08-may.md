---
TOCTitle: 'MS08-MAY'
Title: 2008 年 5 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms08-may'
ms:contentKeyID: 61237685
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms08-may(v=Security.10)'
---

2008 年 5 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2008年5月14日

**版本:** 1.0

此公告摘要列出 2008 年 5 月份發行之安全性公告。

發行 2008 年 5 月份公告之後，此公告摘要將取代原先於 2008 年 5 月 8 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](http://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2008 年 5 月 14 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。 [立即註冊參加 5 月份安全性公告網路廣播](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357221&eventcategory=4&culture=en-us&countrycode=us)。 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](http://www.microsoft.com/taiwan/security/bulletins/default.mspx)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性、高優先順序更新的優先順序，其中這些非安全性、高優先順序更新的發行日期與每月安全性更新的發行日期相同。 請參閱＜其他資訊＞一節。

### 公告資訊

#### 提要

本月份安全性公告依嚴重性列出如下：

重大 (3)
--------

<span></span>

| 公告編號               | Microsoft 安全性公告 MS08-026                                                                                                                                                                                                                                                                                                                                 |
|------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**Microsoft Word 中的弱點可能會允許遠端執行程式碼 (951207)**](http://technet.microsoft.com/security/bulletin/ms08-026)                                                                                                                                                                                                                                       |
| **提要**               | 這個安全性更新可解決 Microsoft Word 中數個未公開報告的弱點，這些弱點可在使用者開啟蓄意製作的 Word 檔案時，允許從遠端執行程式碼。 成功利用這類弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級：** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                 |
| **弱點的影響**         | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新不需要重新開機。                                                                                                                                                                                                                                                              |
| **受影響的軟體**       | **Microsoft Office。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                   |

| 公告編號               | Microsoft 安全性公告 MS08-027                                                                                                                                                                                                                                                                                                                                     |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**Microsoft Publisher 中的弱點可能會允許遠端執行程式碼 (951208)**](http://technet.microsoft.com/security/bulletin/ms08-027)                                                                                                                                                                                                                                      |
| **提要**               | 此安全性更新可解決 Microsoft Publisher 中一項未公開報告的弱點，該弱點可在使用者開啟蓄意製作的 Publisher 檔案時，允許從遠端執行程式碼。 成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級：** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                     |
| **弱點的影響**         | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                    |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新不需要重新開機。                                                                                                                                                                                                                                                                  |
| **受影響的軟體**       | **Microsoft Office。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                       |

| 公告編號               | Microsoft 安全性公告 MS08-028                                                                                                                                                                                                                                                                           |
|------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**Microsoft Jet 資料庫引擎的弱點可能會允許遠端執行程式碼 (950749)**](http://technet.microsoft.com/security/bulletin/ms08-028)                                                                                                                                                                          |
| **提要**               | 這個安全性更新可解決 Windows 中 Microsoft Jet 資料庫引擎 (Jet) 的安全性弱點。 成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級：** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                           |
| **弱點的影響**         | 遠端執行程式碼                                                                                                                                                                                                                                                                                          |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新可能需要重新啟動電腦。                                                                                                                                                                                                  |
| **受影響的軟體**       | **Microsoft Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                            |

中度 (1)
--------

<span></span>

| 公告編號               | Microsoft 安全性公告 MS08-029                                                                                                                                                                                                                                                                                   |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**Microsoft Malware Protection Engine 中的弱點可能會允許拒絕服務 (952044)**](http://technet.microsoft.com/security/bulletin/ms08-029)                                                                                                                                                                          |
| **提要**               | 此安全性更新可解決 Microsoft Malware Protection Engine 中兩項未公開報告的弱點。 攻擊者可蓄意製作檔案，以便在目標電腦系統收到該檔案且 Microsoft Malware Protection Engine 對其進行掃描時，允許拒絕服務，藉此利用任一弱點。 成功利用弱點的攻擊者將使 Microsoft Malware Protection Engine 停止回應並自動重新啟動。 |
| **最高的嚴重性等級：** | [中度](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                   |
| **弱點的影響**         | 拒絕服務                                                                                                                                                                                                                                                                                                        |
| **偵測**               | 受影響的軟體有內建的更新自動偵測與部署機制 此更新不需要重新開機。                                                                                                                                                                                                                                               |
| **受影響的軟體**       | **Windows Live OneCare、Microsoft Antigen、Microsoft Windows Defender、Microsoft Forefront Security。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                    |

受影響的軟體及下載位置
----------------------

<span></span>
**我該如何使用這個表格？**

請用這個表格來瞭解可能需要安裝的安全性更新有哪些。 您應該查看此處列出的每一種軟體程式或元件，看看是否有需要的安全性更新。 若軟體程式或更新出現在清單中，則相關可用軟體更新也會以超連結方式提供，也會列出軟體更新的嚴重性等級。

**注意：**一項弱點可能需要安裝數個安全性更新才能妥善解決。 請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。

#### Windows 作業系統與伺服器

 
<p> </p>
<table style="border:1px solid black;">
<caption>Microsoft Windows 2000</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告編號</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-028"><strong>MS08-028</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最高的嚴重性等級：</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Windows 2000 Service Pack 4</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=0de12d09-e675-4cf0-bc6f-e42eeb4784a1">Microsoft Jet 4.0 資料庫引擎</a><br />
(重大)</td>
</tr>
</tbody>
</table>
 

 
<p> </p>
<table style="border:1px solid black;">
<caption>Windows XP</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告編號</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-028"><strong>MS08-028</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最高的嚴重性等級：</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP Service Pack 2</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=3247433f-0aa9-49b8-9e40-c5463a95bcff">Microsoft Jet 4.0 資料庫引擎</a><br />
(重大)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows XP Professional x64 Edition</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=4915ebc4-5e7b-493e-b8c4-321d40d9a701">Microsoft Jet 4.0 資料庫引擎</a><br />
(重大)</td>
</tr>
</tbody>
</table>
 

 
<p> </p>
<table style="border:1px solid black;">
<caption>Windows Server 2003</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告編號</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-028"><strong>MS08-028</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最高的嚴重性等級：</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 Service Pack 1</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=86e3ed62-98f7-46ec-96ab-5e8c123b1288">Microsoft Jet 4.0 資料庫引擎</a><br />
(重大)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 x64 Edition</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=5dfc867b-74b7-4818-9fc2-d71e7c9d2e38">Microsoft Jet 4.0 資料庫引擎</a><br />
(重大)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 SP1 for Itanium-based Systems</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=3452119b-ba4c-4272-82ec-97396b2c2c3d">Microsoft Jet 4.0 資料庫引擎</a><br />
(重大)</td>
</tr>
</tbody>
</table>
 

#### Microsoft Office 套件及軟體

 
<p> </p>
<table style="border:1px solid black;">
<caption>Microsoft Office 套件、系統和元件</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告編號</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-026"><strong>MS08-026</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-027"><strong>MS08-027</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最高的嚴重性等級：</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Office 2000 Service Pack 3</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=9215ff71-38c0-416a-b89a-fe3474160f41">Microsoft Word 2000 Service Pack 3</a><br />
(KB950250)<br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=8675b9b6-fbf0-4ad2-9210-285e2cc10556">Microsoft Publisher 2000 Service Pack 3</a><br />
(KB950682)<br />
(重大)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Office XP Service Pack 3</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=b348a518-221e-4567-a797-999715a8b2ef">Microsoft Word 2002 Service Pack 3</a><br />
(KB950243)<br />
(重要)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=df623784-6e26-42c0-9e21-e7960b849e1e">Microsoft Publisher 2002 Service Pack 3</a><br />
(KB950129)<br />
(重要)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Office 2003 Service Pack 2</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=bc33d144-f917-47b8-961f-744ca847e14c">Microsoft Word 2003 Service Pack 2</a><br />
(KB950241)<br />
(重要)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=c18b060b-9828-4952-8e80-5328c0832d83">Microsoft Publisher 2003 Service Pack 2</a><br />
(KB950213)<br />
(重要)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Office 2003 Service Pack 3</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=bc33d144-f917-47b8-961f-744ca847e14c">Microsoft Word 2003 Service Pack 3</a><br />
(KB950241)<br />
(重要)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=c18b060b-9828-4952-8e80-5328c0832d83">Microsoft Publisher 2003 Service Pack 3</a><br />
(KB950213)<br />
(重要)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">2007 Microsoft Office System</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=071ceaa2-12e3-4401-9331-2a54a93e2550">Microsoft Word 2007</a><br />
(KB950113)<br />
(重要)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=e4b647c2-79a3-49e0-9b1d-741667fdbcca">Microsoft Publisher 2007</a><br />
(KB950114)<br />
(重要)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=071ceaa2-12e3-4401-9331-2a54a93e2550">Microsoft Outlook 2007</a><br />
(KB950113)<br />
(重大)</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">2007 Microsoft Office System Service Pack 1</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=071ceaa2-12e3-4401-9331-2a54a93e2550">Microsoft Word 2007 Service Pack 1</a><br />
(KB950113)<br />
(重要)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=e4b647c2-79a3-49e0-9b1d-741667fdbcca">Microsoft Publisher 2007 Service Pack 1</a><br />
(KB950114)<br />
(重要)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=071ceaa2-12e3-4401-9331-2a54a93e2550">Microsoft Outlook 2007 Service Pack 1</a><br />
(KB950113)<br />
(重大)</td>
<td style="border:1px solid black;">無</td>
</tr>
</tbody>
</table>

 
<p> </p>
<table style="border:1px solid black;">
<caption>Microsoft Office for Mac</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告編號</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-026"><strong>MS08-026</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最高的嚴重性等級：</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Office 2004 for Mac</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=99f54471-ccf9-4d94-a882-a05ecd128adc">Microsoft Office 2004 for Mac</a><br />
(KB952332)<br />
(重要)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Office 2008 for Mac</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=395d1487-a3a6-4106-a0f8-4d6e1d6d89d2">Microsoft Office 2008 for Mac</a><br />
(KB952331)<br />
(重要)</td>
</tr>
</tbody>
</table>
 

 
<p> </p>
<table style="border:1px solid black;">
<caption>其他 Microsoft Office 軟體</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告編號</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-026"><strong>MS08-026</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最高的嚴重性等級：</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Word Viewer</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=bce7ea31-2bf0-4930-aff9-837bcc82a682">Microsoft Word Viewer 2003</a><br />
(KB950625)<br />
(重要)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=bce7ea31-2bf0-4930-aff9-837bcc82a682">Microsoft Word Viewer 2003 Service Pack 3</a><br />
(KB950625)<br />
(重要)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Office 相容性套件</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=2d718f37-c5d1-4e15-a7e1-5a15fedef52f">Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats</a><br />
(KB951808)<br />
(重要)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=2d718f37-c5d1-4e15-a7e1-5a15fedef52f">Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats Service Pack 1</a><br />
(KB951808)<br />
(重要)</td>
</tr>
</tbody>
</table>
 

#### 其他 Microsoft 軟體

**注意：** 以下項目沒有相關的下載連結，因為所識別的軟體有內建的更新自動偵測與部署機制。

 
<p> </p>
<table style="border:1px solid black;">
<caption>Microsoft Anti-Malware</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告編號</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-029"><strong>MS08-029</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最高的嚴重性等級：</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>中度</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Live OneCare</td>
<td style="border:1px solid black;">Windows Live OneCare<br />
(中度)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Antigen</td>
<td style="border:1px solid black;">Microsoft Antigen for Exchange<br />
(中度)<br />
<br />
Microsoft Antigen for SMTP Gateway<br />
(中度)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Windows Defender</td>
<td style="border:1px solid black;">Microsoft Windows Defender<br />
(中度)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Forefront Security</td>
<td style="border:1px solid black;">Microsoft Forefront Client Security<br />
(中度)<br />
<br />
Microsoft Forefront Security for Exchange Server<br />
(中度)<br />
<br />
Microsoft Forefront Security for SharePoint<br />
(中度)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">獨立系統清理工具</td>
<td style="border:1px solid black;">Diagnostics and Recovery Toolset 6.0 中的獨立系統清理工具<br />
(輕微)</td>
</tr>
</tbody>
</table>
 

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

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。 現已推出新版的 SMS，System Center Configuration Manager 2007；另請參閱 [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)。如需更多有關系統管理員如何能使用 SMS 2003 部署安全性更新的資訊，請參閱 [SMS 2003 安全性修補程式管理](http://www.microsoft.com/taiwan/smserver/evaluation/capabilities/patch.htm) (英文)。 SMS 2.0 使用者也可以利用 [SMS 軟體更新服務功能套件](http://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/suspack/default.htm)來協助部署安全性更新。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server](http://www.microsoft.com/taiwan/smserver/)。

**注意：**SMS 使用 Microsoft Baseline Security Analyzer 及 Microsoft Office Detection Tool，為安全性公告更新的偵測及部署作業提供相當廣泛的支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可以用 Elevated Rights Deployment Tool (隨 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/taiwan/smserver/downloads/2003/adminpack.htm) (英文) 和 [SMS 管理功能套件](http://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/adminpack/default.htm) (英文) 提供) 來安裝這些更新。

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

-   感謝 Jun Mao 與 [iDefense Labs](http://labs.idefense.com/) 合作，回報 MS08-026 中描述的問題。
-   感謝 [team509](http://www.team509.com/) 的 wushi 與 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 MS08-026 中描述的問題。
-   感謝 [Fortinet Security Research](http://www.fortinet.com/) 的 Cocoruder 回報 MS08-027 中描述的問題。
-   感謝 [CERT/CC](http://www.cert.org/) 回報 MS08-028 中描述的問題。
-   感謝 [ISC/SANS](http://isc.sans.org/) 回報 MS08-028 中描述的問題。
-   感謝 [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/) 的 Aaron Portnoy 回報 MS08-028 中描述的問題。
-   感謝 [Nevis Labs](http://www.nevisnetworks.com) 的 SoWhat 回報 MS08-029 中描述的問題。

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可電洽 1-866-PCSAFETY [Microsoft 產品支援服務](http://go.microsoft.com/fwlink/?linkid=21131)以取得技術支援。 與安全性更新有關的支援電話不另外收費。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與安全性更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](http://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2008 年 5 月 14 日)： 公告摘要發行。

*Built at 2014-04-18T01:50:00Z-07:00*
