---
TOCTitle: 'MS08-APR'
Title: 2008 年 4 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms08-apr'
ms:contentKeyID: 61237677
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms08-apr(v=Security.10)'
---

2008 年 4 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2008年4月9日

**版本:** 1.0

此公告摘要列出 2008 年 4 月份所發行的安全性公告。

發行 2008 年 4 月份公告之後，此公告摘要將取代原先於 2008 年 4 月 3 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](http://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2008 年 4 月 9 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。 [立即註冊參加 4 月份安全性公告網路廣播。](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357219&eventcategory=4&culture=en-us&countrycode=us) 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](http://www.microsoft.com/taiwan/security/bulletins/default.mspx)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性、高優先順序更新的優先順序，其中這些非安全性、高優先順序更新的發行日期與每月安全性更新的發行日期相同。 請參閱＜其他資訊＞一節。

### 公告資訊

#### 提要

本月份安全性公告依嚴重性列出如下：

重大 (5)
--------

<span></span>

| 公告編號               | Microsoft 安全性公告 MS08-018                                                                                                                                                                                                                                                                                                                                        |
|------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**Microsoft Project 中的弱點可能會允許遠端執行程式碼**](http://technet.microsoft.com/security/bulletin/ms08-018)                                                                                                                                                                                                                                                    |
| **提要**               | 此安全性更新可解決 Microsoft Office Project 中一項未公開報告的弱點，該弱點可在使用者開啟蓄意製作的 Project 檔案時，允許從遠端執行程式碼。 成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級：** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                        |
| **弱點的影響**         | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                       |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新不需要重新開機。                                                                                                                                                                                                                                                                     |
| **受影響的軟體**       | **Microsoft Office。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                          |

| 公告編號               | Microsoft 安全性公告 MS08-021                                                                                                                                                                                                                                                      |
|------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**GDI 中的弱點可能會允許遠端執行程式碼 (948590)**](http://technet.microsoft.com/security/bulletin/ms08-021)                                                                                                                                                                       |
| **提要**               | 這個安全性更新可解決 GDI 中兩項未公開報告的弱點。 如果使用者開啟蓄意製作的 EMF 或 WMF 影像檔案，利用上述弱點可能會允許遠端執行程式碼。 成功利用這類弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 |
| **最高的嚴重性等級：** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                      |
| **弱點的影響**         | 遠端執行程式碼                                                                                                                                                                                                                                                                     |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 本更新程式需要重新開機。                                                                                                                                                                                 |
| **受影響的軟體**       | **Microsoft Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                       |

| 公告編號               | Microsoft 安全性公告 MS08-022                                                                                                                                                                                                    |
|------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**VBScript 與 JScript 指令碼引擎中的弱點可能會允許遠端執行程式碼 (944338)**](http://technet.microsoft.com/security/bulletin/ms08-022)                                                                                           |
| **提要**               | 這個安全性更新可解決 Windows 的 VBScript 與 JScript 指令碼引擎中一項未公開報告的弱點。 成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 |
| **最高的嚴重性等級：** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                    |
| **弱點的影響**         | 遠端執行程式碼                                                                                                                                                                                                                   |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 本更新程式需要重新開機。                                                                                                                               |
| **受影響的軟體**       | **Microsoft Windows。 **如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                     |

| 公告編號               | Microsoft 安全性公告 MS08-023                                                                                                                                                                                                                                                               |
|------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**ActiveX Kill Bit (刪除位元) 的安全性更新 (948881)**](http://technet.microsoft.com/security/bulletin/ms08-023)                                                                                                                                                                            |
| **提要**               | 這個安全性更新可解決一項未公開報告的 Microsoft 產品弱點。 此更新還包含 Yahoo! 音樂點唱機產品的 Kill Bit (刪除位元)。 如果使用者使用 Internet Explorer 檢視蓄意製作的網頁，此弱點可能會允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級：** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                               |
| **弱點的影響**         | 遠端執行程式碼                                                                                                                                                                                                                                                                              |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新可能需要重新啟動電腦。                                                                                                                                                                                      |
| **受影響的軟體**       | **Microsoft Windows、Internet Explorer。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                             |

| 公告編號               | Microsoft 安全性公告 MS08-024                                                                                                                                                                                     |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**Internet Explorer 積存安全性更新 (947864)**](http://technet.microsoft.com/security/bulletin/ms08-024)                                                                                                          |
| **提要**               | 這個安全性更新可解決一項未公開報告的弱點。 如果使用者使用 Internet Explorer 檢視蓄意製作的網頁，此弱點可能會允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級：** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                     |
| **弱點的影響**         | 遠端執行程式碼                                                                                                                                                                                                    |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 本更新程式需要重新開機。                                                                                                                |
| **受影響的軟體**       | **Microsoft Windows、Internet Explorer。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                   |

重要 (3)
--------

<span></span>

| 公告編號               | Microsoft 安全性公告 MS08-020                                                                                                                                                 |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**DNS 用戶端中的弱點可能會允許偽造 (945553)**](http://technet.microsoft.com/security/bulletin/ms08-020)                                                                      |
| **提要**               | 這個安全性更新能解決一項未公開報告的弱點。 此偽造弱點存在於 Windows DNS 用戶端且可能會允許攻擊者傳送蓄意製作的回應給 DNS 要求，以偽造或者重新導向來自合法位置的網際網路流量。 |
| **最高的嚴重性等級：** | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                 |
| **弱點的影響**         | 偽造                                                                                                                                                                          |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 本更新程式需要重新開機。                                                                            |
| **受影響的軟體**       | **Microsoft Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                  |

| 公告編號               | Microsoft 安全性公告 MS08-025                                                                                                                                                             |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**Windows 核心中的弱點可能會允許權限提高 (941693)**](http://technet.microsoft.com/security/bulletin/ms08-025)                                                                            |
| **提要**               | 這個安全性更新可解決 Windows 核心中一項未公開報告的弱點。 成功利用此弱點的本機攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來能在系統上安裝程式；檢視、變更或刪除資料；或建立新帳戶。 |
| **最高的嚴重性等級：** | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                             |
| **弱點的影響**         | 權限提高                                                                                                                                                                                  |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 本更新程式需要重新開機。                                                                                        |
| **受影響的軟體**       | **Microsoft Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                              |

| 公告編號               | Microsoft 安全性公告 MS08-019                                                                                                                                                                                                                                                                                                                                    |
|------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**Microsoft Visio 中的弱點可能會允許遠端執行程式碼 (949032)**](http://technet.microsoft.com/security/bulletin/ms08-019)                                                                                                                                                                                                                                         |
| **提要**               | 此安全性更新可解決 Microsoft Office Visio 中一項未公開報告的弱點，該弱點可在使用者開啟蓄意製作的 Visio 檔案時，允許從遠端執行程式碼。 成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級：** | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                    |
| **弱點的影響**         | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                   |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新不需要重新開機。                                                                                                                                                                                                                                                                 |
| **受影響的軟體**       | **Microsoft Office。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                      |

受影響的軟體及下載位置
----------------------

<span></span>
**我該如何使用這個表格？**

請用這個表格來瞭解可能需要安裝的安全性更新有哪些。 您應該查看此處列出的每一種軟體程式或元件，看看是否有需要的安全性更新。 若軟體程式或更新出現在清單中，則相關可用軟體更新也會以超連結方式提供，也會列出軟體更新的嚴重性等級。

**注意：**一項弱點可能需要安裝數個安全性更新才能妥善解決。 請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。

#### Windows 作業系統與元件

 
<p> </p>
<table style="border:1px solid black;">
<caption>Microsoft Windows 2000</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告編號</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-021"><strong>MS08-021</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-022"><strong>MS08-022</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-023"><strong>MS08-023</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-024"><strong>MS08-024</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-020"><strong>MS08-020</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-025"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最高的嚴重性等級：</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Windows 2000 Service Pack 4</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=caac000a-22b6-48cb-aa00-1a0bfe886de2">Microsoft Windows 2000 Service Pack 4</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=8e3ff44f-145b-4a68-9ad4-4a55d74b216e">VBScript 5.1 與 JScript 5.1</a><br />
(重大)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=8e3ff44f-145b-4a68-9ad4-4a55d74b216e">VBScript 5.6 與 JScript 5.6</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=0395451f-b719-4f71-a7b4-403d0c7e8fcc">Microsoft Internet Explorer 5.01 Service Pack 4</a><br />
(重大)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=ba6d3aeb-e35a-47cc-bace-7bd9d58a9d3f">Microsoft Internet Explorer 6 Service Pack 1</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=b051ae04-fe81-440d-9136-d6b239ca954e">Microsoft Internet Explorer 5.01 Service Pack 4</a><br />
(重大)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=75d2dc78-e3a4-4ff6-9e2d-bf1935003e8e">Microsoft Internet Explorer 6 Service Pack 1</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=41326ade-96b6-47ce-9291-d4e3039471c4">Microsoft Windows 2000 Service Pack 4</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=8db9f328-da0e-4fb8-96c4-6d368b47c224">Microsoft Windows 2000 Service Pack 4</a><br />
(重要)</td>
</tr>
</tbody>
</table>
 

 
<p> </p>
<table style="border:1px solid black;">
<caption>Windows XP</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告編號</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-021"><strong>MS08-021</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-022"><strong>MS08-022</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-023"><strong>MS08-023</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-024"><strong>MS08-024</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-020"><strong>MS08-020</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-025"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最高的嚴重性等級：</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP Service Pack 2</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=c2763dd8-a03e-4a48-aa86-a7ec00250a7a">Windows XP Service Pack 2</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=c0124698-3b94-4474-9473-22a2f39a4a56">VBScript 5.6 與 JScript 5.6</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=9dbf002f-fe53-4cc7-a430-35f45c520d10">Windows XP Service Pack 2</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=36c641ad-953f-4b09-ba1c-9c383295e180">Microsoft Internet Explorer 6</a><br />
(重大)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=e771efe8-8881-4f23-b5b0-15651a390ba9">Windows Internet Explorer 7</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=893f4cef-0395-4c44-ba28-7a10b6e7dd48">Windows XP Service Pack 2</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=0e937f65-abd0-46dd-8883-5bfd70ea1178">Windows XP Service Pack 2</a><br />
(重要)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=166f2ab5-913c-47a9-86fe-b814797b751e">Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2 (英文下載更新程式)</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=87b80ae3-e299-4d15-a135-3b1bcf943652">VBScript 5.6 與 JScript 5.6(英文下載更新程式)</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=01400970-df68-4daf-aa39-2fc4f969974c">Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=85beacc0-8ca2-4ded-9c24-23348d05c735">Microsoft Internet Explorer 6</a><br />
(重大)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=9364bf81-6505-4788-958d-a4bd29dc98ad">Windows Internet Explorer 7</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=8fdd1207-6e93-4c43-bacc-fe3623a6ebe7">Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2(英文下載更新程式)</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=a29bbd13-761f-44fa-8948-e1a8c244bd7a">Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2(英文下載更新程式)</a><br />
(重要)</td>
</tr>
</tbody>
</table>
 

 
<p> </p>
<table style="border:1px solid black;">
<caption>Windows Server 2003</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告編號</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-021"><strong>MS08-021</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-022"><strong>MS08-022</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-023"><strong>MS08-023</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-024"><strong>MS08-024</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-020"><strong>MS08-020</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-025"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最高的嚴重性等級：</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 Service Pack 1 與 Windows Server 2003 Service Pack 2</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=bee91d80-d49a-4d3d-82d6-d5aa63f54979">Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=88518aa6-e334-4529-aa63-0bf2ef417ce3">VBScript 5.6 與 JScript 5.6</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=ad384fea-53be-4be3-8acb-1cd23a7f5405">Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2</a><br />
(中度)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=0444b76e-93fa-43c2-b1bc-a5c054529eb5">Microsoft Internet Explorer 6</a><br />
(重大)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=9acd2a03-5530-49c8-9ea1-0bfaf259700d">Windows Internet Explorer 7</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=214bd8f5-6eb2-414c-b013-c516a306d692">Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=d3b855a6-4648-4771-826d-11a151828eac">Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2</a><br />
(重要)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=e3dde449-e062-4ce0-a9f4-433bff23e224">Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=12cefefc-8553-4dca-9850-c653371de61e">VBScript 5.6 與 JScript 5.6</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=ffc5c893-cb24-4875-b0a7-6d5c7aa4d642">Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2</a><br />
(中度)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=5ebb5ef9-615f-4cab-bac5-6f45f1b94952">Microsoft Internet Explorer 6</a><br />
(重大)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=a9e406aa-33e2-49b8-ab54-4a7328e46147">Windows Internet Explorer 7</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=fd123394-a5d6-4b55-be74-2938f52ce922">Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=320fd100-35e1-4345-9399-796393235cbc">Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2</a><br />
(重要)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">適用於 Itanium 型系統的 Windows Server 2003 SP1 和適用於 Itanium 型系統的 Windows Server 2003 SP2</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=7886a802-f2b5-489c-b14b-631f4c4c0742">適用於 Itanium 型系統的 Windows Server 2003 SP1 和適用於 Itanium 型系統的 Windows Server 2003 SP2 (中文下載更新程式)</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=fe22a828-cca4-4b51-bbd5-995c65fead21">VBScript 5.6 與 JScript 5.6 (中文下載更新程式)</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=94cf78d3-b6c3-41bc-993e-3af3be0d70f1">適用於 Itanium 型系統的 Windows Server 2003 SP1 和適用於 Itanium 型系統的 Windows Server 2003 SP2 (中文下載更新程式)</a><br />
(中度)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=63da8040-fda2-42c7-8543-26ad6f9811f2">Microsoft Internet Explorer 6</a><br />
(重大)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?familyid=75a05d3a-92a0-4a00-95d4-e2b2f6755180">Windows Internet Explorer 7 (中文下載更新程式)</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=e0e63f03-904d-47ee-94fc-51a8dea668eb">適用於 Itanium 型系統的 Windows Server 2003 SP1 和適用於 Itanium 型系統的 Windows Server 2003 SP2 (中文下載更新程式)</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=126426a7-be38-4327-89db-02d99d76589d">適用於 Itanium 型系統的 Windows Server 2003 SP1 和適用於 Itanium 型系統的 Windows Server 2003 SP2 (中文下載更新程式)</a><br />
(重要)</td>
</tr>
</tbody>
</table>
 

 
<p> </p>
<table style="border:1px solid black;">
<caption>Windows Vista</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告編號</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-021"><strong>MS08-021</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-022"><strong>MS08-022</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-023"><strong>MS08-023</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-024"><strong>MS08-024</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-020"><strong>MS08-020</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-025"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最高的嚴重性等級：</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Vista 和 Windows Vista Service Pack 1</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=9b51deb8-3873-4146-977f-7e3d0840a4c5">Windows Vista 和 Windows Vista Service Pack 1</a><br />
(重大)</td>
<td style="border:1px solid black;">無</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=d7f14001-7f42-4ca0-9193-cdf061179b59">Windows Vista 和 Windows Vista Service Pack 1</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=d4e24966-6530-463a-9ee2-f6a9d000f998">Windows Internet Explorer 7</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=8203d303-c855-4579-9bbf-b06ddf5c1b87">Windows Vista</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=9640cd8b-d749-4ddd-8af9-b298cebed969">Windows Vista 和 Windows Vista Service Pack 1</a><br />
(重要)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=4ad6dcd1-6ea5-43bf-8bee-a5f507beadc6">Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1</a><br />
(重大)</td>
<td style="border:1px solid black;">無</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=d33462b6-7391-482d-babe-fb4cd0beaa21">Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=295cf8f2-265e-4570-b708-21033337fe05">Windows Internet Explorer 7</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=73f3a234-3973-4467-be7e-69efa7ee978c">Windows Vista x64 Edition</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=d56bb4fe-304e-45e0-95f2-fde2f47b2a04">Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1</a><br />
(重要)</td>
</tr>
</tbody>
</table>
 

 
<p> </p>
<table style="border:1px solid black;">
<caption>Windows Server 2008</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告編號</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-021"><strong>MS08-021</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-022"><strong>MS08-022</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-023"><strong>MS08-023</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-024"><strong>MS08-024</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-020"><strong>MS08-020</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-025"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最高的嚴重性等級：</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">適用於 32 位元系統的 Windows Server 2008</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=006d5c47-53e6-4ee1-932c-497611804938">適用於 32 位元系統的 Windows Server 2008</a><br />
(重大)</td>
<td style="border:1px solid black;">無</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=95691924-2813-4a86-9e11-99d853f8e606">適用於 32 位元系統的 Windows Server 2008</a><br />
(輕微)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=e57b4d94-19ad-4818-8311-a3f94be01a4b">Windows Internet Explorer 7</a><br />
(重大)</td>
<td style="border:1px solid black;">無</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=4497333c-9418-4b91-83dc-0155735421c0">適用於 32 位元系統的 Windows Server 2008</a><br />
(重要)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">適用於 x64 系統的 Windows Server 2008</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=8909f144-655b-4f07-916f-fd967f1efb2b">適用於 x64 型系統的 Windows Server 2008</a><br />
(重大)</td>
<td style="border:1px solid black;">無</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=920ae29b-19d0-4089-ac79-f2da824a2256">適用於 x64 型系統的 Windows Server 2008</a><br />
(輕微)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=93e9f52a-c7d0-4033-9c12-740665a219af">Windows Internet Explorer 7</a><br />
(重大)</td>
<td style="border:1px solid black;">無</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=5aefc7a6-79a4-45a2-b534-35d0ec400dda">適用於 x64 型系統的 Windows Server 2008</a><br />
(重要)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">適用於 Itanium 系統的 Windows Server 2008</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=b7771a4a-4e4f-48d1-8551-bb8b778ca5a7">適用於 Itanium 型系統的 Windows Server 2008</a><br />
(重大)</td>
<td style="border:1px solid black;">無</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=66df79ac-8364-4922-9688-ebc7ec76d89f">適用於 Itanium 型系統的 Windows Server 2008 (英文下載更新程式)</a><br />
(輕微)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=acf948e8-c4a9-40da-b282-f5e584e77b05">Windows Internet Explorer 7 (英文下載更新程式)</a><br />
(重大)</td>
<td style="border:1px solid black;">無</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=3080c26b-7456-41ef-8668-28f15bc7b8ce">適用於 Itanium 型系統的 Windows Server 2008</a><br />
(重要)</td>
</tr>
</tbody>
</table>
 

#### Microsoft Office 套件及軟體

 
<p> </p>
<table style="border:1px solid black;">
<caption>Microsoft Project</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告編號</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-018"><strong>MS08-018</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-019"><strong>MS08-019</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最高的嚴重性等級：</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Project 2000 Service Release 1</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=fbe46241-b9da-40c6-803d-42eb6234be77">Project 2000 Service Release 1</a><br />
(KB949043)<br />
(重大)</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Project 2002 Service Pack 1</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=07a90718-6597-426d-9dca-a336d60c01b8">Project 2002 Service Pack 1</a><br />
(KB949005)<br />
(重要)</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Project 2003 Service Pack 2</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=aaba07d6-e972-4e85-bccd-406aa2c4a4f4">Project 2003 Service Pack 2</a><br />
(KB948962)<br />
(重要)</td>
<td style="border:1px solid black;">無</td>
</tr>
</tbody>
</table>

 
<p> </p>
<table style="border:1px solid black;">
<caption>Microsoft Office XP、Microsoft Office 2003 和 2007 Microsoft Office System</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告編號</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=115454"><strong>MS08-018</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=115455"><strong>MS08-019</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最高的嚴重性等級：</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Office XP Service Pack 3</td>
<td style="border:1px solid black;">無</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=0056a936-def5-40fa-bcfc-0ab0dd5c3964">Visio 2002 Service Pack 3</a><br />
(KB947896)<br />
(重要)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Office 2003 Service Pack 2</td>
<td style="border:1px solid black;">無</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=18af0ce6-99a0-4471-8d26-9700a8a8e631">Visio 2003 Service Pack 2</a><br />
(KB947650)<br />
(重要)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Office 2003 Service Pack 3</td>
<td style="border:1px solid black;">無</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=18af0ce6-99a0-4471-8d26-9700a8a8e631">Visio 2003 Service Pack 3</a><br />
(KB947650)<br />
(重要)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">2007 Microsoft Office System</td>
<td style="border:1px solid black;">無</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=0510a1bb-b464-452c-900f-7f4e58ed9c7e">Visio 2007</a><br />
(KB947590)<br />
(重要)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">2007 Microsoft Office System Service Pack 1</td>
<td style="border:1px solid black;">無</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=0510a1bb-b464-452c-900f-7f4e58ed9c7e">Visio 2007 Service Pack 1</a><br />
(KB947590)<br />
(重要)</td>
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

-   感謝韓國的 [National Cyber Security Center](http://www.ncsc.go.kr/eng/) 回報 MS08-018 中描述的問題
-   感謝一位匿名的發現者回報 MS08-019 中描述的問題
-   感謝一位匿名的發現者回報 MS08-019 中描述另一項問題
-   感謝 [Trusteer](http://www.trusteer.com/) 的 Amit Klein 回報 MS08-020 中描述的問題
-   感謝 [Scanit](http://www.scanit.be/) 的 Alla Berzroutchko 回報 MS08-020 中描述的問題
-   感謝 [Nominet UK](http://www.nominet.org.uk/) 的 Roy Arends 回報 MS08-020 中描述的問題
-   感謝 [iDefense Labs](http://labs.idefense.com/) 的 Jun Mao 回報 MS08-021 中描述的問題
-   感謝 [Zero Day Initiative](http://www.zerodayinitiative.com/) 的 Sebastian Apelt 回報 MS08-021 中描述的問題
-   感謝 [SkyRecon](http://www.skyrecon.com/) 的 Thomas Garnier 回報 MS08-021 中描述的問題
-   感謝 Yamata Li 回報 MS08-021 中描述的問題
-   感謝[賽門鐵克](http://www.symantec.com/)的 Peter Ferrie 回報 MS08-022 中描述的問題
-   感謝匿名的研究人員與 [iDefense VCP](http://labs.idefense.com/vcp/) 合作回報 MS08-023 中描述的問題
-   感謝 [Secunia](http://secunia.com/) 的 Carsten Eiram 回報 MS08-024 中描述的問題
-   感謝 [SkyRecon](http://www.skyrecon.com/) 的 Thomas Garnier 回報 MS08-025 中描述的問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可電洽 1-866-PCSAFETY [Microsoft 產品支援服務](http://go.microsoft.com/fwlink/?linkid=21131)以取得技術支援。 與安全性更新有關的支援電話不另外收費。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與安全性更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](http://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2008 年 4 月 9 日)： 公告摘要發行。

*Built at 2014-04-18T01:50:00Z-07:00*
