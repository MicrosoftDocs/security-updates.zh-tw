---
TOCTitle: 'MS07-JUN'
Title: 2007 年 6 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms07-jun'
ms:contentKeyID: 61237671
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms07-jun(v=Security.10)'
---

2007 年 6 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2007年6月13日

**版本:** 1.0

此公告摘要列出 2007 年 6 月份發行之安全性公告。

發行 2007 年 6 月份公告之後，此公告摘要將取代原先於 2007 年 6 月 7 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](https://technet.microsoft.com/security/bulletin/advance)。

若要在 Microsoft 安全性公告發佈時收到自動通知，請訂閱 [Microsoft 技術安全性通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2007 年 6 月 14 日星期四(台灣地區：15：00 - 16：00)，解決這些公告上的客戶問題。 [立即註冊參力 6 月份安全性公告網路廣播](https://www.microsoft.com/taiwan/technet/webcast/msft061407vx.aspx)。 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](https://www.microsoft.com/taiwan/security/bulletins/default.mspx)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性、高優先順序更新的優先順序，其中這些非安全性、高優先順序更新的發行日期與每月安全性更新的發行日期相同。 請參閱＜其他資訊＞一節。

### 公告資訊

#### 提要

本月份安全性公告依嚴重性列出如下：

重大 (4)
--------

<span></span>

| 公告編號             | Microsoft 安全性公告 MS07-031                                                                                                                                                                                                                                                                                                                                                                                                                 |
|----------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Windows Schannel 安全性套件中的弱點可能會允許遠端執行程式碼 (935840)**](https://technet.microsoft.com/security/bulletin/ms07-031)                                                                                                                                                                                                                                                                                                           |
| **提要**             | 這個重大安全性更新可解決 Windows 安全通道 (Schannel) 安全性套件中一項未公開報告的弱點。 Schannel 安全性套件會執行安全通訊端層 (SSL) 和傳輸層安全性 (TLS) 網際網路標準驗證通訊協定。 如果使用者使用網際網路網頁瀏覽器檢視蓄意製作的網頁，或使用利用 SSL/TLS 的應用程式，此弱點可能會允許遠端執行程式碼。 但是，嘗試利用此弱點最可能的結果是導致網際網路網頁瀏覽器或應用程式結束。 在重新啟動系統前，系統無法使用 SSL 或 TLS 連線到網站或資源。 |
| **最高的嚴重性等級** | [重大](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                 |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新可能需要重新啟動電腦。                                                                                                                                                                                                                                                                                                                                        |
| **受影響的軟體**     | **Windows**。 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                                                                                                            |

| 公告編號             | Microsoft 安全性公告 MS07-033                                                                                                                                                                                                                                                                                                                                                                                     |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Internet Explorer 積存安全性更新 (933566)**](https://technet.microsoft.com/security/bulletin/ms07-033)                                                                                                                                                                                                                                                                                                          |
| **提要**             | 這個重大安全性更新可解決五項未公開報告的弱點，以及一項已公開揭露的弱點。 如果使用者使用 Internet Explorer 檢視蓄意製作的網頁，上述所有弱點 (僅一項除外) 可能會允許遠端執行程式碼。 其中一項弱點可能會允許偽造，同時也和蓄意製作的網頁相關。 在所有遠端執行程式碼的情況下，系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 在偽造的情形中，需要使用者互動，弱點才有可能遭到利用。 |
| **最高的嚴重性等級** | [重大](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                     |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                                                                    |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新可能需要重新啟動電腦。                                                                                                                                                                                                                                                                                                            |
| **受影響的軟體**     | **Windows、Internet Explorer**。 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                                                             |

| 公告編號             | Microsoft 安全性公告 MS07-034                                                                                                                                                                                                                                                                                                                                                                                          |
|----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Outlook Express 和 Windows Mail 積存安全性更新 (929123)**](https://technet.microsoft.com/security/bulletin/ms07-034)                                                                                                                                                                                                                                                                                                 |
| **提要**             | 這個重大安全性更新可解決兩項未公開報告的弱點，以及兩項公開揭露的弱點。 如果使用者在 Windows Vista 中使用 Windows Mail 檢視蓄意製作的電子郵件，其中一項弱點可能會允許遠端執行程式碼。 如果使用者使用 Internet Explorer 造訪蓄意製作的網頁，其他弱點可能會允許資訊洩漏，但這些弱點無法直接在 Outlook Express 起作用。 若為資訊洩漏弱點，系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重大](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                          |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                                                                         |
| **偵測**             | Microsoft Baseline Security Analyzer 和企業掃描工具可以偵測您的電腦系統是否需要此更新。 此更新可能需要重新啟動電腦。                                                                                                                                                                                                                                                                                                   |
| **受影響的軟體**     | **Windows、Outlook Express、Windows Mail**。 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                                                      |

| 公告編號             | Microsoft 安全性公告 MS07-035                                                                                                                                                                                                                                                                      |
|----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Win32 API 中的弱點可能會允許遠端執行程式碼 (935839)**](https://technet.microsoft.com/security/bulletin/ms07-035)                                                                                                                                                                                 |
| **提要**             | 這個重大安全性更新可解決 Win32 API 中一項未公開報告的弱點。 如果蓄意製作的應用程式在本機上使用受影響的 API，此弱點可能會允許遠端執行程式碼或提高權限。 因此，使用此 Win32 API 元件的應用程式可能會被用來當作此弱點的媒介。 例如，Internet Explorer 在剖析蓄意製作的網頁時會使用此 Win32 API 功能。 |
| **最高的嚴重性等級** | [重大](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                      |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                     |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新可能需要重新啟動電腦。                                                                                                                                                                                             |
| **受影響的軟體**     | **Windows**。 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                 |

重要 (1)
--------

<span></span>

| 公告編號             | Microsoft 安全性公告 MS07-030                                                                                                                                                                                                                                                                                            |
|----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Microsoft Visio 中的弱點可能會允許遠端執行程式碼 (927051)**](https://technet.microsoft.com/security/bulletin/ms07-031)                                                                                                                                                                                                 |
| **提要**             | 除了調查期間識別的其他安全性問題以外，此重要安全性更新可解決兩項未公開發現且盡責報告的弱點。 如果使用者開啟蓄意製作的 Visio 檔案，未公開報告的弱點可能會允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 如果要利用這些弱點發動攻擊，必須要有相當程度的使用者互動。 |
| **最高的嚴重性等級** | [重要](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                            |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                                           |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新可能需要重新啟動電腦。                                                                                                                                                                                                                   |
| **受影響的軟體**     | **Office、Visio**。 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                 |

中度 (1)
--------

<span></span>

| 公告編號             | Microsoft 安全性公告 MS07-032                                                                                                                               |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Windows Vista 中的弱點可能會導致資訊洩漏 (931213)**](https://technet.microsoft.com/security/bulletin/ms07-032)                                            |
| **提要**             | 這個中度安全性更新可解決一項未公開報告的弱點。 此弱點可能會允許未經授權的使用者存取本機使用者資訊資料存放區，包括包含在登錄及本機檔案系統中的系統管理密碼。 |
| **最高的嚴重性等級** | [中度](https://technet.microsoft.com/security/bulletin/rating)                                                                                               |
| **弱點的影響**       | 資訊洩漏                                                                                                                                                    |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新可能需要重新啟動電腦。                                                      |
| **受影響的軟體**     | **Windows**。 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                          |

受影響的軟體及下載位置
----------------------

<span></span>
**我該如何使用這個表格？**

請用這個表格來瞭解可能需要安裝的安全性更新有哪些。 您應該查看此處列出的每一種軟體程式或元件，看看是否有需要的安全性更新。 在列出的軟體程式或元件旁邊，會附註弱點的影響等級，同時也會列出可用軟體更新的超連結。

**注意**：一項弱點，可能需要安裝數個安全性更新才能妥善解決。 請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。

**受影響的軟體及下載位置**

 
<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
詳細資訊        
</th>
<th style="border:1px solid black;" >
詳細資訊        
</th>
<th style="border:1px solid black;" >
詳細資訊        
</th>
<th style="border:1px solid black;" >
詳細資訊        
</th>
<th style="border:1px solid black;" >
詳細資訊        
</th>
<th style="border:1px solid black;" >
詳細資訊        
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS07-030**](https://technet.microsoft.com/security/bulletin/ms07-031)
</td>
<td style="border:1px solid black;">
[**MS07-031**](https://technet.microsoft.com/security/bulletin/ms07-031)
</td>
<td style="border:1px solid black;">
[**MS07-032**](https://technet.microsoft.com/security/bulletin/ms07-032)
</td>
<td style="border:1px solid black;">
[**MS07-033**](https://technet.microsoft.com/security/bulletin/ms07-033)
</td>
<td style="border:1px solid black;">
[**MS07-034**](https://technet.microsoft.com/security/bulletin/ms07-034)
</td>
<td style="border:1px solid black;">
[**MS07-035**](https://technet.microsoft.com/security/bulletin/ms07-035)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最高的嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<th colspan="7">
受影響的 Windows 軟體
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=5b8e728c-cb9f-4176-93a0-bf42d6387f93)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=3918ac76-ebb6-4886-9a9e-808eafb96b1b)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=8615e6f3-415b-4c23-ba52-7eef70a11d77)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=27c7f1b9-2d1d-40cb-ad7e-bfedb6156a9c)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?familyid=7e994340-c616-4f66-845b-7eaf095e968a)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?familyid=0ba12191-1e6f-443b-9150-7ab8b2deb7c2)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?familyid=7e994340-c616-4f66-845b-7eaf095e968a)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?familyid=0ba12191-1e6f-443b-9150-7ab8b2deb7c2)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=39e6c6d2-7e6f-4992-a731-36f44fe2d87f)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=d554dff4-bcfb-4bbc-8fa0-af2f939d2610)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=39e6c6d2-7e6f-4992-a731-36f44fe2d87f)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=d554dff4-bcfb-4bbc-8fa0-af2f939d2610)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=da424772-079c-4351-9759-8886e0f1ba79)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=170473d8-6bb1-4fbd-8494-a059dbfdf182)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=da424772-079c-4351-9759-8886e0f1ba79)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=170473d8-6bb1-4fbd-8494-a059dbfdf182)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP1 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=028592ff-2b69-472e-b186-bd2cc76bdfa4)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?familyid=f5e45e3c-4cac-41a5-99f7-42c2c2c73e99)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=028592ff-2b69-472e-b186-bd2cc76bdfa4)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?familyid=f5e45e3c-4cac-41a5-99f7-42c2c2c73e99)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=cdf79d00-6f34-404b-8ad5-a2801ff35443)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=89dde3f4-4123-4c97-86d8-00a83462c34b)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="7">
受影響的 Windows 作業系統元件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 中的 Internet Explorer 5.01 Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=3b49f1ed-abe3-4dbd-a91d-973415658f6b)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 中的 Internet Explorer 6 Service Pack 1
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=5c958650-28d2-4dd0-96a8-dbfe79ce3f68)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 2 中的 Internet Explorer 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=60fb294e-a8e1-405e-a289-2d2723edf7ee)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2 的 Internet Explorer 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=086d6d6e-4703-4c6c-a7af-b6dafeeede5d)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 的 Internet Explorer 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=7ed19127-5c2d-48e4-a8d1-090dc69fd68b)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 的 Internet Explorer 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=1449eb5d-6e4c-4332-8cb6-ab9ee59c9a95)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Windows Server 2003 SP1 for Itanium-based Systems 和 Windows Server 2003 SP2 for Itanium-based Systems 的 Internet Explorer 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?familyid=b628a3cc-a70c-478a-a10c-eee254ee34ab)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=c2191703-8cbd-4959-9f84-e13f21173926)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Windows XP Professional x64 Edition 及 Windows XP Professional x64 Edition Service Pack 2 的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=69c526b8-8b07-42bc-9bed-e18deae21c8e)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=a074d9c0-1fed-4753-845e-073cfce99f45)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=744acb43-64da-48cc-ae69-9386b597eabc)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Windows Server 2003 SP1 for Itanium-based Systems 和 Windows Server 2003 SP2 for Itanium-based Systems 的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?familyid=069c1560-b5e5-4dfe-a18d-e0507d406028)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 中的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=77287386-48eb-4aa9-9537-626a3093aaf7)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition 中的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=77287386-48eb-4aa9-9537-626a3093aaf7)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 2 的 Outlook Express 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=27cca556-0872-4803-b610-4c895ceb99aa)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 中的 Outlook Express 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=1ea813bf-bddb-40f0-8960-b9debc8413e7)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2 中的 Outlook Express 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=1ea813bf-bddb-40f0-8960-b9debc8413e7)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 中的 Outlook Express 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[輕微](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=93808a74-035c-4ab7-9283-c693d7bd82be)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2 中的 Outlook Express 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[輕微](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=93808a74-035c-4ab7-9283-c693d7bd82be)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 中的 Outlook Express 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=f63323a9-e285-45e5-84bd-71ae9da126e3)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2 中的 Outlook Express 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=f63323a9-e285-45e5-84bd-71ae9da126e3)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP1 for Itanium-based Systems 中的 Outlook Express 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[輕微](https://www.microsoft.com/download/details.aspx?familyid=2e62e96e-6571-437d-a612-99175ac39025)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems 中的 Outlook Express 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[輕微](https://www.microsoft.com/download/details.aspx?familyid=2e62e96e-6571-437d-a612-99175ac39025)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 中的 Windows Mail
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=ee57de19-44ea-48f2-ae28-e76fd2018633)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 中的 Windows Mail
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=343db20f-7794-4423-b11d-885329fbdf78)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="7">
受影響的 Office 軟體
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Visio 2002 Service Pack 2
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=fc1d0483-27e8-4541-b81d-4a47973bea30)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Visio 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=c47f432e-8538-42fd-92c9-7e0f1d643e8e)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
</table>
 
**注意：**

**<sup>[1]</sup>** 已針對此作業系統提供了安全性更新程式。 請參閱表格中受影響的軟體或元件，以及相關的安全性公告以獲得詳細資訊。

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和安全性更新。 如需更多資訊，請參閱 [TechNet 更新管理中心](https://www.microsoft.com/taiwan/technet/updatemanagement/default.mspx)。 [TechNet 資訊安全中心](https://www.microsoft.com/taiwan/technet/security/default.mspx) 提供 Microsoft 產品安全性的其他資訊。 消費者可以造訪[在家上網的安全性](https://www.microsoft.com/taiwan/athome/security/default.mspx)網站，只要按一下 \[最新安全性更新\] 即可在此網站取得此資訊。

安全性更新可以從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)、[Windows Update](https://go.microsoft.com/fwlink/?linkid=21130)及 [Office Update](https://office.microsoft.com/zh-tw/downloads/default.aspx)取得。 安全性更新也可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得。 您也可以利用 "security\_patch" 關鍵字搜尋輕易地找到安全性更新。 最後，您可以從 Windows Update 目錄下載安全性更新。 如需有關 Windows Update 目錄的詳細資訊，請參閱 Microsoft [知識庫文件編號 323166](https://support.microsoft.com/kb/323166)。

**偵測與部署指南**

Microsoft 已提供本月安全性更新之偵測與部署指南。 此指南還能幫助 IT 專業人員瞭解如何使用各項工具來協助部署安全性更新，像是 Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office Detection Tool、Microsoft Systems Management Server (SMS)、加強版安全性更新盤點工具 (Extended Security Update Inventory Tool) 和企業更新掃描工具 (EST)。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 910723](https://support.microsoft.com/kb/910723)。

**Microsoft Baseline Security Analyzer 和企業** **更新掃描工具**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少安全性更新以及一般安全性設定錯誤的狀況。 如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134) 網站 (英文)。

當 MBSA 1.2.1 無法支援偵測特定安全性更新時，Microsoft 會針對該安全性更新，發行特定版本的企業更新掃描工具 (EST)。 如需更多有關 EST 的資訊，請造訪[企業更新掃描工具](https://support.microsoft.com/default.aspx?id=894193)。

**注意：**2007 年 10 月 9 日之後，我們將不再更新 MBSA 1.2.1 使用的 MSSecure.XML 檔案。 在此之後，MBSA 1.2.1 使用的 MSSecure.XML 檔案將不會加入新的安全性更新，也不會有新版的企業掃描工具發行。 如需更多資訊，請造訪 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134) (英文)。

**Software Update Services**

Microsoft Software Update Services (SUS) 能讓系統管理員以迅速可靠的方式，針對 Windows 2000 和 Windows Server 2003 伺服器以及執行 Windows 2000 Professional 或 Windows XP Professional 的桌面系統，部署最新的重要更新程式及安全性更新程式。

如果想進一步瞭解如何透過「軟體更新服務」來部署這個安全性更新，請造訪[軟體更新服務](https://go.microsoft.com/fwlink/?linkid=21133)網站。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速可靠地將 Windows 2000 作業系統及更新系統版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 等最新的重大更新與安全性更新部署到 Windows 2000 及更新作業系統版本中。

如需更多關於利用 Windows Server Update Services 部署安全性更新的資訊，請造訪 [Windows Server Update Services](https://www.microsoft.com/taiwan/windowsserversystem/updateservices/evaluation/overview.mspx) 網站。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。 如需更多關於系統管理員如何使用 SMS 2003 部署安全性更新的資訊，請瀏覽 [SMS 2003 的安全性補充程式管理](https://www.microsoft.com/taiwan/smserver/evaluation/capabilities/patch.htm)網站。 SMS 2.0 使用者也可以利用 [SMS 軟體更新服務功能套件](https://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/suspack/default.htm)來協助部署安全性更新。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server](https://www.microsoft.com/taiwan/smserver/)。

**注意：**SMS 使用 Microsoft Baseline Security Analyzer 及 Microsoft Office Detection Tool，為安全性公告更新的偵測及部署作業提供相當廣泛的支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](https://go.microsoft.com/fwlink/?linkid=33341)(英文)。 某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可以用 Elevated Rights Deployment Tool (隨 [SMS 2003 Administration Feature Pack](https://www.microsoft.com/taiwan/smserver/downloads/2003/adminpack.htm) 和 [SMS 管理功能套件](https://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/adminpack/default.htm) 提供) 來安裝這些更新。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

請注意，此工具並非透過 Software Update Services (SUS) 散佈。

#### MU、WU、WSUS 及 SUS 上的非安全性、高優先順序更新

本月份：

-   Microsoft 已在 Microsoft Update (MU) 和 Windows Server Update Services (WSUS) 上發行了七個「非安全性」的高優先順序更新。
-   Microsoft 並未在 Windows Update (WU) 和 Software Update Services (SUS) 上發行任何「非安全性」、高優先順序的 Windows 更新。

請注意，此資訊僅與 Microsoft Update、 Windows Update、Windows Server Update Services 和 Software Update Services 上，與本安全性公告摘要同日發行的「非安全性」高優先順序更新有關。 於其他日期發行的「非安全性」更新相關資訊並未包含在內。

#### 安全性策略與社群

**更新程式管理策略**

[修補程式管理安全性指南](https://go.microsoft.com/fwlink/?linkid=21168)提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用 "security\_patch" 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](https://support.microsoft.com/kb/913086)。

**IT 專業人員資訊安全區社群**

在 [IT 專業人員資訊安全區社群](https://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](https://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝匿名的研究人員與 [iDefense VCP](https://idefense.com/) 合作回報 [MS07-033](https://technet.microsoft.com/security/bulletin/ms07-033) 中描述的問題。
-   感謝 [ISS](https://www.iss.net/) 的 Tom Cross 協助 Microsoft 解決 [MS07-033](https://technet.microsoft.com/security/bulletin/ms07-033) 中描述的問題。
-   感謝匿名的研究人員和 [TippingPoint](https://www.tippingpoint.com/) 及 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 [MS07-033](https://technet.microsoft.com/security/bulletin/ms07-033) 中描述的問題。
-   感謝匿名的研究人員和 [TippingPoint](https://www.tippingpoint.com/) 及 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 [MS07-033](https://technet.microsoft.com/security/bulletin/ms07-033) 中描述的問題。
-   感謝 [CERT/CC](https://www.cert.org/certcc.html) 的 Will Dorman 回報 [MS07-033](https://technet.microsoft.com/security/bulletin/ms07-033) 中描述的問題。
-   感謝 [Fortinet Security Research](https://www.fortinet.com/) 的 Cocoruder 協助 Microsoft 解決 [MS07-033](https://technet.microsoft.com/security/bulletin/ms07-033) 中描述的問題。
-   感謝 Billy Rios 回報 [MS07-035](https://technet.microsoft.com/security/bulletin/ms07-035) 中描述的問題。
-   感謝 [COSEINC](https://www.coseinc.com/) 的 Thomas Lim 回報 [MS07-031](https://technet.microsoft.com/security/bulletin/ms07-031) 中描述的問題。
-   感謝 [SANS ISC](https://isc.sans.org/) 協助我們解決 [MS07-034](https://technet.microsoft.com/security/bulletin/ms07-034) 中描述的問題。
-   感謝 [WebAppSec JP](https://www.webappsec.jp/) 的 Yosuke Hasegawa 回報 [MS07-034](https://technet.microsoft.com/security/bulletin/ms07-034) 中的描述的問題。
-   感謝 Robbie Sohlman 回報 [MS07-032](https://technet.microsoft.com/security/bulletin/ms07-032) 中描述的問題。

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可電洽 1-866-PCSAFETY [Microsoft 產品支援服務](https://go.microsoft.com/fwlink/?linkid=21131)以取得技術支援。 與安全性更新有關的支援電話不另外收費。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與安全性更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](https://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2007 年 6 月 13 日)： 公告摘要發行。

*Built at 2014-04-18T01:50:00Z-07:00*
