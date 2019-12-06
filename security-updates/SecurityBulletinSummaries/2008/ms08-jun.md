---
TOCTitle: 'MS08-JUN'
Title: 2008 年 6 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms08-jun'
ms:contentKeyID: 61237683
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms08-jun(v=Security.10)'
---

2008 年 6 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2008年6月11日 | 更新: 2008年6月11日

**版本:** 1.1

本公告摘要列出 2008 年 6 月份發行之安全性公告。

發行 2008 年 6 月份公告之後，此公告摘要將取代原先於 2008 年 6 月 5 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](https://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2008 年 6 月 11 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。 [立即註冊參力 6 月份安全性公告網路廣播](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357225&eventcategory=4&culture=en-us&countrycode=us)。 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](https://www.microsoft.com/taiwan/security/bulletins/default.mspx)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性、高優先順序更新的優先順序，其中這些非安全性、高優先順序更新的發行日期與每月安全性更新的發行日期相同。 請參閱＜其他資訊＞一節。

### 公告資訊

#### 提要

本月份安全性公告依嚴重性列出如下：

重大 (3)
--------

<span></span>

| 公告編號               | Microsoft 安全性公告 MS08-030                                                                                                                                                                                                                          |
|------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**Bluetooth 堆疊中的弱點可能會允許遠端執行程式碼 (951376)**](https://technet.microsoft.com/security/bulletin/ms08-030)                                                                                                                                 |
| **提要**               | 此安全性更新可解決一項未公開報告的弱點，該弱點存在於 Windows 的 Bluetooth 堆疊中，可能會允許遠端執行程式碼。 成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 |
| **最高的嚴重性等級：** | [重大](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                          |
| **弱點的影響**         | 遠端執行程式碼                                                                                                                                                                                                                                         |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新可能需要重新啟動電腦。                                                                                                                                                 |
| **受影響的軟體**       | **Microsoft Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                           |

| 公告編號               | Microsoft 安全性公告 MS08-031                                                                                                                                                                                                                                                                                                                                 |
|------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**Internet Explorer 積存安全性更新 (950759)**](https://technet.microsoft.com/security/bulletin/ms08-031)                                                                                                                                                                                                                                                      |
| **提要**               | 此安全性更新可解決一項未公開報告的弱點，以及一項已公開揭露的弱點。 如果使用者使用 Internet Explorer 檢視蓄意製作的網頁，那麼這個未公開報告的弱點可能會允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 如果使用者使用 Internet Explorer 檢視蓄意製作的網頁，那麼這個未公開報告的弱點可能會導致資訊洩漏。 |
| **最高的嚴重性等級：** | [重大](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                 |
| **弱點的影響**         | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 本更新程式需要重新開機。                                                                                                                                                                                                                                                            |
| **受影響的軟體**       | **Microsoft Windows、Internet Explorer。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                               |

| 公告編號               | Microsoft 安全性公告 MS08-033                                                                                                                                                                                                                                                                                                                                      |
|------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**DirectX 中的弱點可能會允許遠端執行程式碼 (951698)**](https://technet.microsoft.com/security/bulletin/ms08-033)                                                                                                                                                                                                                                                   |
| **提要**               | 這個安全性更新可解決 Microsoft DirectX 中兩項未公開報告的弱點，這些弱點可在使用者開啟蓄意製作的媒體檔案時，允許從遠端執行程式碼。 成功利用上述任一弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級：** | [重大](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                      |
| **弱點的影響**         | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                     |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新可能需要重新啟動電腦。                                                                                                                                                                                                                                                             |
| **受影響的軟體**       | **Microsoft Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                       |

重要 (3)
--------

<span></span>

| 公告編號               | Microsoft 安全性公告 MS08-034                                                                                                                                                                                                                 |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**WINS 中的弱點可能會允許權限提高 (948745)**](https://technet.microsoft.com/security/bulletin/ms08-034)                                                                                                                                       |
| **提要**               | 本安全性更新能解決一項未公開報告的弱點，該弱點存在於 Windows 網際網路名稱服務 (WINS) 中，可能會允許權限提高。 成功利用此弱點的本機攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來能在系統上安裝程式；檢視、變更或刪除資料；或建立新帳戶。 |
| **最高的嚴重性等級：** | [重要](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                 |
| **弱點的影響**         | 權限提高                                                                                                                                                                                                                                      |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 本更新程式需要重新開機。                                                                                                                                            |
| **受影響的軟體**       | **Microsoft Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                  |

| 公告編號               | Microsoft 安全性公告 MS08-035                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**Active Directory 中的弱點可能會允許拒絕服務 (953235)**](https://technet.microsoft.com/security/bulletin/ms08-035)                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **提要**               | 這個安全性更新可解決一項未公開報告的弱點，該弱點存在於在以下系統中實作 Active Directory 的情況下：Microsoft Windows 2000 Server、Windows Server 2003 與 Windows Server 2008；安裝於 XP Professional 與 Windows Server 2003 的 Active Directory 應用程式模式；以及安裝於 Windows Server 2008 的 Active Directory 輕量型目錄服務 (AD LDS)。攻擊者可利用此弱點造成拒絕服務的情況發生。 在 Windows XP Professional、Windows Server 2003 及 Windows Server 2008 上，攻擊者必須擁有有效的登入認證，才能利用這項弱點。 成功利用此弱點的攻擊者可使該系統停止回應，或自動重新啟動。 |
| **最高的嚴重性等級：** | [重要](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **弱點的影響**         | 拒絕服務                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 本更新程式需要重新開機。                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **受影響的軟體**       | **Microsoft Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |

| 公告編號               | Microsoft 安全性公告 MS08-036                                                                                                                                                                                                                                                                                                                |
|------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**Pragmatic General Multicast (PGM) 中的弱點可能會允許拒絕服務 (950762)**](https://technet.microsoft.com/security/bulletin/ms08-036)                                                                                                                                                                                                         |
| **提要**               | 這個安全性更新可解決 Pragmatic General Multicast (PGM) 通訊協定中的兩項未公開報告的弱點，如果受影響的系統收到格式錯誤的 PGM 封包，則可能導致拒絕服務發生。 成功利用此弱點的攻擊者可讓使用者的系統變得無回應，並且必須重新啟動才能還原各項功能。 請注意拒絕服務弱點不會讓攻擊者執行程式碼或提高其使用者權限，但會導致受影響系統停止接受要求。 |
| **最高的嚴重性等級：** | [重要](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                |
| **弱點的影響**         | 拒絕服務                                                                                                                                                                                                                                                                                                                                     |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 本更新程式需要重新開機。                                                                                                                                                                                                                                           |
| **受影響的軟體**       | **Microsoft Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                 |

中度 (1)
--------

<span></span>

| 公告編號               | Microsoft 安全性公告 MS08-032                                                                                                                                                                                                                                                                                                  |
|------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**           | [**ActiveX Kill Bits (刪除位元) 的積存安全性更新 (950760)**](https://technet.microsoft.com/security/bulletin/ms08-032)                                                                                                                                                                                                          |
| **提要**               | 這個安全性更新可解決 Microsoft Speech API 的一項公開報告的弱點。 如果使用者使用 Internet Explorer 檢視蓄意製作的網頁，而且啟用 Windows 的語音辨識功能，此弱點可能會允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 此更新還包含 BackWeb 製作的軟體 Kill Bit (刪除位元)。 |
| **最高的嚴重性等級：** | [中度](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                  |
| **弱點的影響**         | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                 |
| **偵測**               | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新可能需要重新啟動電腦。                                                                                                                                                                                                                         |
| **受影響的軟體**       | **Microsoft Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                   |

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-030"><strong>MS08-030</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-031"><strong>MS08-031</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-033"><strong>MS08-033</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-034"><strong>MS08-034</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-035"><strong>MS08-035</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-036"><strong>MS08-036</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-032"><strong>MS08-032</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>公告最高嚴重性等級</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>中度</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Windows 2000 Service Pack 4</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=88990b23-d37f-4d02-a5a3-2ee389ade53c">Microsoft Internet Explorer 5.01 Service Pack 4</a><br />
(重要)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=4c47cf8a-8100-4d43-855a-f225a3492b19">Microsoft Internet Explorer 6 Service Pack 1</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=65640123-a9e4-455c-a51a-9df28bd2d412">DirectX 7.0</a><br />
(重大)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=c6a28d45-13cf-48c4-8f89-3417d552e90b">DirectX 8.1</a><br />
(重大)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?familyid=4dc47e04-5e95-4636-a814-3f912d961461">DirectX 9.0、DirectX 9.0b 或 DirectX 9.0c</a><br />
(重大)</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=cedfd988-232c-4cba-ac65-beb54b8946e0">Microsoft Windows 2000 Service Pack 4</a><br />
(中度)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Windows 2000 Server Service Pack 4</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=aa8aa79f-c2cc-440c-9e5c-089143e6f814">Microsoft Windows 2000 Server Service Pack 4</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=53438880-9ea9-4975-9b85-2a1d3d232793">Active Directory</a><br />
(KB949014)<br />
(重要)</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
</tbody>
</table>

 
<p> </p>
<table style="border:1px solid black;">
<caption>Windows XP</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告編號</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-030"><strong>MS08-030</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-031"><strong>MS08-031</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-033"><strong>MS08-033</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-034"><strong>MS08-034</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-035"><strong>MS08-035</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-036"><strong>MS08-036</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-032"><strong>MS08-032</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>公告最高嚴重性等級</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>中度</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP Service Pack 2 及 Windows XP Service Pack 3</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=980bb421-950f-4825-8039-44cc961a47b8">Windows XP Service Pack 2 及 Windows XP Service Pack 3</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=cc325017-3a48-4475-90e4-0c79a002fce3">Microsoft Internet Explorer 6</a><br />
(重大)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=fbc31bde-0bf5-490c-96a8-071310d9464a">Windows Internet Explorer 7</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=7aaa6427-1e22-4566-960c-836a3b9e5f36">DirectX 9.0、DirectX 9.0b 或 DirectX 9.0c</a><br />
(重大)</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=36b14a81-5979-4e38-9ba3-ed83dfc17adf">Windows XP Service Pack 2 及 Windows XP Service Pack 3</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=2d8957c2-e473-4dca-8d68-19fdaea36e26">Windows XP Service Pack 2 及 Windows XP Service Pack 3</a><br />
(中度)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows XP Professional Service Pack 2 與 Windows XP Professional Service Pack 3</td>
<td style="border:1px solid black;">(請參閱「Windows XP Service Pack 2 與 Windows XP Service Pack 3」這一列)</td>
<td style="border:1px solid black;">(請參閱「Windows XP Service Pack 2 與 Windows XP Service Pack 3」這一列)</td>
<td style="border:1px solid black;">(請參閱「Windows XP Service Pack 2 與 Windows XP Service Pack 3」這一列)</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=7d6aec31-cfb4-470c-983e-78c6a3ebabfe">ADAM</a><br />
(KB949269)<br />
(中度)</td>
<td style="border:1px solid black;">(請參閱 Windows XP Service Pack 2 與 Windows XP Service Pack 3 這一列)</td>
<td style="border:1px solid black;">(請參閱 Windows XP Service Pack 2 與 Windows XP Service Pack 3 這一列)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=81ab56ca-933f-4974-a393-290a54c30a78">Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=c8783cfe-9da5-4842-ab3a-1e2be4fafc47">Microsoft Internet Explorer 6</a><br />
(重大)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=19c0ccdc-95c9-4151-96b6-4f49b594ebe0">Windows Internet Explorer 7</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=5e8e7e9d-828d-442c-acac-8d91e80dfb36">DirectX 9.0、DirectX 9.0b 或 DirectX 9.0c</a><br />
(重大)</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=ef2e0b48-1bde-4ccc-8f40-2918c2568b2b">ADAM</a><br />
(KB949269)<br />
(中度)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=9e9d24ee-8183-428c-8067-168a8d85eaa1">Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=62874096-7d17-4116-9795-4756e2fb6dae">Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2</a><br />
(中度)</td>
</tr>
</tbody>
</table>
 

 
<p> </p>
<table style="border:1px solid black;">
<caption>Windows Server 2003</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告編號</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-030"><strong>MS08-030</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-031"><strong>MS08-031</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-033"><strong>MS08-033</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-034"><strong>MS08-034</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-035"><strong>MS08-035</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-036"><strong>MS08-036</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-032"><strong>MS08-032</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>公告最高嚴重性等級</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>中度</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 Service Pack 1 與 Windows Server 2003 Service Pack 2</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=286aada6-a358-41f1-b81a-8de39b9f908a">Microsoft Internet Explorer 6</a><br />
(中度)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=a1ae9ad2-8329-4c96-b950-7534b3287eaa">Windows Internet Explorer 7</a><br />
(中度)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=2274ecb2-2802-47e2-84fd-6621fcb17758">DirectX 9.0、DirectX 9.0b 或 DirectX 9.0c</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=08fc90d5-23aa-4327-8aef-16bc5170769d">Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=a4aed117-3c76-4d80-b50e-8e07e2ef2f7d">Active Directory</a><br />
(KB949014)<br />
(中度)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=0a983ffb-4f5a-4b78-9bf5-813dcc5df8d3">ADAM</a><br />
(KB949269)<br />
(中度)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=1e8e2faf-009f-403b-a5fe-a47cf014db3a">Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=dadead99-09cb-4f2b-850d-e98a627cb9f8">Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2</a><br />
(輕微)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=6604569a-3db0-47e7-bd30-7dfba8145386">Microsoft Internet Explorer 6</a><br />
(中度)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=fb0c70b4-ce9f-43d6-875a-3cfd0d3a2681">Windows Internet Explorer 7</a><br />
(中度)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=5ba63bb7-ed6d-4c59-88b3-456eda07e190">DirectX 9.0、DirectX 9.0b 或 DirectX 9.0c</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=71675ae8-d60a-4834-b358-2d8e761e62fc">Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=8298a6e4-d3e2-48ea-ac29-aa4dc5a8ec77">Active Directory</a><br />
(KB949014)<br />
(中度)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=334252db-4a7a-4161-bb71-2a20c0b5bd93">ADAM</a><br />
(KB949269)<br />
(中度)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=78bf92d8-63c4-4596-8425-8fcfea7f5582">Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=84f9b533-b0cb-46d1-b4a8-5c9469abbd22">Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2</a><br />
(輕微)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 SP1 for Itanium-based Systems 和 Windows Server 2003 SP2 for Itanium-based Systems</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=0262beb8-1eb5-4c2d-a50a-0c6c6e0c1f61">Microsoft Internet Explorer 6</a><br />
(中度)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?familyid=28d2913c-1c6b-4671-9892-de08698cd5a6">Windows Internet Explorer 7</a><br />
(中度)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=be71c002-2f64-49e9-9f4b-ba99c4f3caf6">DirectX 9.0、DirectX 9.0b 或 DirectX 9.0c</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=87affdc9-d9fe-413c-af30-f3d3b671ec72">適用於 Itanium 型系統的 Windows Server 2003 SP1 和適用於 Itanium 型系統的 Windows Server 2003 SP2</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=f6bf4b85-b91d-4378-a356-cd11f12cbbfd">Active Directory</a><br />
(KB949014)<br />
(中度)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=5b7e94fa-22ed-4f7c-b452-647b2e620113">適用於 Itanium 型系統的 Windows Server 2003 SP1 和適用於 Itanium 型系統的 Windows Server 2003 SP2</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=ac35ce19-d761-4529-9f55-1e1b5b2447ad">適用於 Itanium 型系統的 Windows Server 2003 SP1 和適用於 Itanium 型系統的 Windows Server 2003 SP2</a><br />
(輕微)</td>
</tr>
</tbody>
</table>
 

 
<p> </p>
<table style="border:1px solid black;">
<caption>Windows Vista</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告編號</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-030"><strong>MS08-030</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-031"><strong>MS08-031</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-033"><strong>MS08-033</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-034"><strong>MS08-034</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-035"><strong>MS08-035</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-036"><strong>MS08-036</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-032"><strong>MS08-032</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>公告最高嚴重性等級</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>中度</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Vista 和 Windows Vista Service Pack 1</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=6524debe-be50-44d1-8543-af0bfaf086ad">Windows Vista 和 Windows Vista Service Pack 1 (中文下載更新程式)</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=6d68b39d-157f-4c3d-ac76-bc5a9386db59">Windows Internet Explorer 7 (中文下載更新程式)</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=4d4b305b-57f8-448d-92fa-3dcdd1f42ed7">DirectX 10.0 (中文下載更新程式)</a><br />
(重大)</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=ef2d2a4b-4831-41be-b5d0-8df5b01fd205">Windows Vista 和 Windows Vista Service Pack 1 (中文下載更新程式)</a><br />
(中度)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=4af6575e-b061-45a6-b3d8-ecb32d76b2d3">Windows Vista 和 Windows Vista Service Pack 1 (中文下載更新程式)</a><br />
(中度)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=6adee8b9-3455-4f3b-8bdd-2585c8ff83b8">Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1 (中文下載更新程式)</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=4cf92235-861e-4b74-bee3-8e977c8688d9">Windows Internet Explorer 7 (中文下載更新程式)</a><br />
(重大)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=b040cfad-2290-44f4-8f5a-5d1ed98a7265">DirectX 10.0 (中文下載更新程式)</a><br />
(重大)</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=0839fcf4-85ca-445e-896b-f634b10b6700">Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1 (中文下載更新程式)</a><br />
(中度)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=67576acb-9cb6-4c76-9a72-dc5e5556b658">Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1 (中文下載更新程式)</a><br />
(中度)</td>
</tr>
</tbody>
</table>
 

 
<p> </p>
<table style="border:1px solid black;">
<caption>Windows Server 2008</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告編號</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-030"><strong>MS08-030</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-031"><strong>MS08-031</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-033"><strong>MS08-033</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-034"><strong>MS08-034</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-035"><strong>MS08-035</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-036"><strong>MS08-036</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-032"><strong>MS08-032</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>公告最高嚴重性等級</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重大</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>中度</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">適用於 32 位元系統的 Windows Server 2008</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=a8922e7e-9264-4e09-b8ad-c5420fed8690">Windows Internet Explorer 7</a><br />
(中度)<strong>**</strong></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=c0c495f8-2a35-4638-a635-1e55dd15e062">DirectX 10.0</a><br />
(重大)<strong>**</strong></td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=2981156e-2e2f-469e-91be-da127d50f3fc">Active Directory</a><br />
(KB949014)<br />
(中度)<strong>*</strong><br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?familyid=2981156e-2e2f-469e-91be-da127d50f3fc">AD LDS</a><br />
(KB949014)<br />
(中度)<strong>*</strong></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=0466a6e7-fdca-4647-af62-449e5f20d1e4">適用於 32 位元系統的 Windows Server 2008</a><br />
(中度)<strong>**</strong></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=8a507fba-8c93-4952-91e4-98e9e7affbd2">適用於 32 位元系統的 Windows Server 2008</a><br />
(輕微)<strong>*</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">適用於 x64 系統的 Windows Server 2008</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=05b0e838-24d7-4387-b069-2604bbcc43b9">Windows Internet Explorer 7</a><br />
(中度)<strong>**</strong></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=0b70fc2e-4e80-4ae8-8682-41ea04c24e4e">DirectX 10.0</a><br />
(重大)<strong>**</strong></td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=b5cfe6f4-c5ba-4be9-a6b8-9381c40c85aa">Active Directory</a><br />
(KB949014)<br />
(中度)<strong>*</strong><br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?familyid=b5cfe6f4-c5ba-4be9-a6b8-9381c40c85aa">AD LDS</a><br />
(KB949014)<br />
(中度)<strong>*</strong></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=304898e6-21a7-476f-b9ed-7ac0d88a91e2">適用於 x64 型系統的 Windows Server 2008</a><br />
(中度)<strong>**</strong></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&amp;familyid=1a11499d-a008-407f-9084-a5189fa27015">適用於 x64 型系統的 Windows Server 2008</a><br />
(輕微)<strong>*</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">適用於 Itanium 系統的 Windows Server 2008</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=640e1865-ebcc-4d69-a770-fd360020da1e">Windows Internet Explorer 7</a><br />
(中度)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=80ec83e0-cfb8-4a5e-9254-6679a7225b83">DirectX 10.0</a><br />
(重大)</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=8907783b-e3fe-40b2-9fc8-4937e7d58b7e">適用於 Itanium 型系統的 Windows Server 2008</a><br />
(中度)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=59b1689c-e723-4d87-973e-4beac107a6f7">適用於 Itanium 型系統的 Windows Server 2008</a><br />
(輕微)</td>
</tr>
</tbody>
</table>
 

**\*Windows Server 2008 Server Core 安裝會受影響。** 對於受支援的 Windows Server 2008 版本，無論 Windows Server 2008 是否使用 Server Core 安裝選項，這個更新均以相同的嚴重性等級套用。 如需這個安裝選項的詳細資訊，請參閱 [Server Core](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 版本；請參閱[比較 Server Core 安裝選項](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**\*\*Windows Server 2008 Server Core 安裝不受影響。** 如果 Windows Server 2008 是使用 Server Core 安裝選項所安裝，則這項更新解決的弱點並不會影響受支援的 Windows Server 2008 版本。 如需這個安裝選項的詳細資訊，請參閱 [Server Core](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 版本；請參閱[比較 Server Core 安裝選項](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和安全性更新。 如需更多資訊，請參閱 [TechNet 更新管理中心](https://www.microsoft.com/taiwan/technet/updatemanagement/default.mspx)。 [TechNet Security Center](https://www.microsoft.com/taiwan/technet/security/default.mspx) 提供 Microsoft 產品安全性的其他資訊。 消費者可以造訪[在家上網的安全性](https://www.microsoft.com/taiwan/athome/security/default.mspx)網站，只要按一下 \[最新安全性更新\] 即可在此網站取得此資訊。

安全性更新可以從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)、[Windows Update](https://go.microsoft.com/fwlink/?linkid=21130)及 [Office Update](https://office.microsoft.com/zh-tw/downloads/default.aspx)取得。 安全性更新也可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得。 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。

最後，您可以從 [Microsoft Update Catalog](https://go.microsoft.com/fwlink/?linkid=96155) 下載安全性更新。 Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括安全性更新、驅動程式和 Service Pack。 只要以安全性公告編號 (例如，"MS07-036") 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。 如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](https://go.microsoft.com/fwlink/?linkid=97900)。

**偵測與部署指南**

Microsoft 已提供本月安全性更新之偵測與部署指南。 此指南還能幫助 IT 專業人員瞭解如何使用各項工具來協助部署安全性更新，像是 Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office Detection Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool (加強版安全性更新清查工具，ESUIT)。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 910723](https://support.microsoft.com/kb/910723)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少安全性更新以及一般安全性設定錯誤的狀況。 如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134) 網站 (英文)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速可靠地將 Windows 2000 作業系統及更新系統版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 等最新的重大更新與安全性更新部署到 Windows 2000 及更新作業系統版本中。

如需更多關於利用 Windows Server Update Services 部署安全性更新的資訊，請造訪 [Windows Server Update Services](https://www.microsoft.com/taiwan/windowsserversystem/updateservices/evaluation/overview.mspx) 網站。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。 現已推出新版的 SMS，System Center Configuration Manager 2007；另請參閱 [System Center Configuration Manager 2007](https://technet.microsoft.com/en-us/library/bb735860.aspx)。如需更多有關系統管理員如何能使用 SMS 2003 部署安全性更新的資訊，請參閱 [SMS 2003 安全性修補程式管理](https://www.microsoft.com/taiwan/smserver/evaluation/capabilities/patch.htm) (英文)。 SMS 2.0 使用者也可以利用 [SMS 軟體更新服務功能套件](https://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/suspack/default.htm)來協助部署安全性更新。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server](https://www.microsoft.com/taiwan/smserver/)。

**注意：**SMS 使用 Microsoft Baseline Security Analyzer 及 Microsoft Office Detection Tool，為安全性公告更新的偵測及部署作業提供相當廣泛的支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](https://go.microsoft.com/fwlink/?linkid=33341)。 某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可以用 Elevated Rights Deployment Tool (隨 [SMS 2003 Administration Feature Pack](https://www.microsoft.com/taiwan/smserver/downloads/2003/adminpack.htm) 和 [SMS 管理功能套件](https://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/adminpack/default.htm) 提供) 來安裝這些更新。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非安全性、高優先順序更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](https://support.microsoft.com/kb/894199)： Software Update Services 與 Windows Server Update Services 的說明內容在 2008 年有所變動。其中也包括所有 Windows 的內容。
-   [適用於 Microsoft 產品 (除了 Microsoft Windows 以外) 的全新、修訂版以及已發行的更新](https://technet.microsoft.com/en-us/wsus/bb466214.aspx)。

#### 安全性策略與社群

**更新程式管理策略**

[更新程式管理安全性指南](https://www.microsoft.com/taiwan/technet/security/topics/patchmanagement.mspx)提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](https://support.microsoft.com/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](https://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](https://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 Sebastian Apelt、Peter Vreugdenhil 和 匿名的研究人員與 [Tipping Point](https://www.tippingpoint.com/) 及 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 MS08-031 中描述的問題。
-   感謝 [IBM Internet Security Systems X-Force](https://xforce.iss.net/) 研究人員 Mark Dowd 回報 MS08-033 中描述的問題
-   感謝匿名的研究人員與 [Tipping Point](https://www.tippingpoint.com/) 及 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 MS08-033 中描述的問題。
-   感謝 [Securify](https://www.securify.com/) 的 Alex Matthews 回報 MS08-035 中描述的問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可電洽 1-866-PCSAFETY [Microsoft 產品支援服務](https://go.microsoft.com/fwlink/?linkid=21131)以取得技術支援。 與安全性更新有關的支援電話不另外收費。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與安全性更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](https://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2008 年 6 月 11 日)： 公告摘要發行。
-   V1.1 (2008 年 6 月 12 日)： 更正 Windows XP 的「受影響的軟體」表格，針對 MS08-030、MS08-031、MS08-032、MS08-033 及 MS08-036，說明適用於 Windows XP Service Pack 2 與 Windows XP Service Pack 3 的項目。

*Built at 2014-04-18T01:50:00Z-07:00*
