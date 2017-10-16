---
TOCTitle: 'MS07-JUL'
Title: 2007 年 7 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms07-jul'
ms:contentKeyID: 61237670
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms07-jul(v=Security.10)'
---

Security Bulletin Summary

2007 年 7 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2007年7月11日

**版本:** 1.0

此公告摘要列出 2007 年 7 月份發行之安全性公告。

發行 2007 年 7 月份公告之後，此公告摘要將取代原先於 2007 年 7 月 5 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](http://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2007 年 7 月 11 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。 [立即註冊參加 7 月份安全性公告網路廣播](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032343783&eventcategory=4&culture=en-us&countrycode=us)。 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](http://technet.microsoft.com/security/bulletin/summary)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性、高優先順序更新的優先順序，其中這些非安全性、高優先順序更新的發行日期與每月安全性更新的發行日期相同。 請參閱＜其他資訊＞一節。

### 公告資訊

#### 提要

本月份安全性公告依嚴重性列出如下：

重大 (3)
--------

<span></span>
| 公告編號             | Microsoft 安全性公告 MS07-036                                                                                                                                                                                                                             |
|----------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Microsoft Excel 中的弱點可能會允許遠端執行程式碼 (936542)**](http://technet.microsoft.com/security/bulletin/ms07-036)                                                                                                                                  |
| **提要**             | 除了調查期間識別的其他安全性問題以外，此重大更新可解決一項公開揭發的弱點和兩項未公開報告的弱點。 如果使用者開啟蓄意製作的 Excel 檔案，上述弱點可能會允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                             |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                            |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新程式不需要重新開機。                                                                                                                                                      |
| **受影響的軟體**     | **Office、Excel**。 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                  |

| 公告編號             | Microsoft 安全性公告 MS07-039                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Windows Active Directory 中的弱點可能會允許遠端執行程式碼 (926122)**](http://technet.microsoft.com/security/bulletin/ms07-039)                                                                                                                                                                                                                                                                                                                                                  |
| **提要**             | 這個重大安全性更新可解決在 Windows 2000 Server 和 Windows Server 2003 上實作 Active Directory 的一項未公開報告的弱點，此弱點可能會允許遠端執行程式碼，或發生拒絕服務的情況。 嘗試利用此弱點進行的攻擊，其最可能的結果是導致拒絕服務狀態。 但是，也可能導致遠端執行程式碼。 在 Windows Server 2003 上，攻擊者必須擁有有效的登入認證，才能利用這項弱點。 成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來能在系統上安裝程式；檢視、變更或刪除資料；或建立新帳戶。 |
| **最高的嚴重性等級** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新需要重新啟動電腦。                                                                                                                                                                                                                                                                                                                                                                                 |
| **受影響的軟體**     | **Windows**。 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                                                                                                                                                 |

| 公告編號             | Microsoft 安全性公告 MS07-040                                                                                                                                                                                                                                                 |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**.NET Framework 中的弱點可能會允許遠端執行程式碼 (931212)**](http://technet.microsoft.com/security/bulletin/ms07-040)                                                                                                                                                       |
| **提要**             | 此更新可解決三項未公開報告的弱點。 這些弱點中的兩項可允許在安裝有 .NET Framework 的用戶端系統從遠端執行程式碼，一項可允許從執行 ASP.NET 的 Web 伺服器洩漏資訊。在所有遠端執行程式碼的情況下，系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                 |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新需要重新啟動電腦。                                                                                                                                                                            |
| **受影響的軟體**     | **.NET Framework**。 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                     |

重要 (2)
--------

<span></span>

| 公告編號             | Microsoft 安全性公告 MS07-037                                                                                                                                                                                                                                                     |
|----------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Microsoft Office Publisher 中的弱點可能會允許遠端執行程式碼 (936548)**](http://technet.microsoft.com/security/bulletin/ms07-037)                                                                                                                                               |
| **提要**             | 這個重要的安全性更新能解決一項公開揭發的弱點。 如果使用者檢視蓄意製作的 Microsoft Office Publisher 檔案，此弱點可能會允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 要利用此項弱點發動攻擊，必須要有使用者的互動才能奏效。 |
| **最高的嚴重性等級** | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                     |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                    |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新不需要重新開機。                                                                                                                                                                                  |
| **受影響的軟體**     | **Office、Publisher**。 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                      |

| 公告編號             | Microsoft 安全性公告 MS07-041                                                                                                                                                                                                                                                                                                                   |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Microsoft Internet Information Services 的弱點可能會允許遠端執行程式碼 (939373)**](http://technet.microsoft.com/security/bulletin/ms07-041)                                                                                                                                                                                                  |
| **提要**             | 這個重要安全性更新能解決一項未公開報告的弱點。 若攻擊者對 Windows XP Professional Service Pack 2 上 Internet Information Services (IIS) 5.1 所控制的網頁傳送蓄意製作的 URL 要求時，此弱點可能會允許遠端執行程式碼。IIS 5.1 非屬 Windows XP Professional Service Pack 2 預設安裝中的部分。成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 |
| **最高的嚴重性等級** | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                   |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                  |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新需要重新啟動電腦。                                                                                                                                                                                                                                              |
| **受影響的軟體**     | **Windows XP Professional**。 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                              |

中度 (1)
--------

<span></span>
| 公告編號             | Microsoft 安全性公告 MS07-038                                                                                                            |
|----------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Windows Vista 防火牆中的弱點可能會導致資訊洩漏 (935807)**](http://technet.microsoft.com/security/bulletin/ms07-038)                   |
| **提要**             | 這個中度安全性更新可解決一項未公開報告的弱點。 此弱點可能會允許來路不明的網路輸入流量存取網路介面。 攻擊者可能能夠收集受影響主機的資訊。 |
| **最高的嚴重性等級** | [中度](http://technet.microsoft.com/security/bulletin/rating)                                                                            |
| **弱點的影響**       | 資訊洩漏                                                                                                                                 |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新需要重新啟動電腦。                                       |
| **受影響的軟體**     | **Windows** **Vista**。 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                             |

受影響的軟體及下載位置
----------------------

<span></span>
**我該如何使用這個表格？**

請用這個表格來瞭解可能需要安裝的安全性更新有哪些。 您應該查看此處列出的每一種軟體程式或元件，看看是否有需要的安全性更新。 在列出的軟體程式或元件旁邊，會附註弱點的影響等級，同時也會列出可用軟體更新的超連結。

**注意**：一項弱點，可能需要安裝數個安全性更新才能妥善解決。 請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。

**受影響的軟體及下載位置**

 
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
[**MS07-036**](http://www.microsoft.com/taiwan.technet/security/bulletin/ms07-036.mspx)
</td>
<td style="border:1px solid black;">
[**MS07-037**](http://www.microsoft.com/taiwan.technet/security/bulletin/ms07-037.mspx)
</td>
<td style="border:1px solid black;">
[**MS07-038**](http://technet.microsoft.com/security/bulletin/ms07-038)
</td>
<td style="border:1px solid black;">
[**MS07-039**](http://technet.microsoft.com/security/bulletin/ms07-039)
</td>
<td style="border:1px solid black;">
[**MS07-040**](http://technet.microsoft.com/security/bulletin/ms07-040)
</td>
<td style="border:1px solid black;">
[**MS07-041**](http://technet.microsoft.com/security/bulletin/ms07-041)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最高的嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/security/bulletin/rating)
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
<th colspan="7">
受影響的 Windows 軟體
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 2000 Service Pack 4
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
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 2000 Server Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=812e62c5-6e19-4b3b-8a10-861b871e1b41)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 2
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
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
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
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=fccbfe90-f838-47df-8310-352e2fb47132)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition
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
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
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
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=28e84603-8159-4429-aaff-a1020531e84f)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=28e84603-8159-4429-aaff-a1020531e84f)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=107902f9-be94-457f-a936-519efbd64779)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=107902f9-be94-457f-a936-519efbd64779)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP1 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=e5e5b425-fe7d-49d5-973f-f3fd7a1e04eb)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=e5e5b425-fe7d-49d5-973f-f3fd7a1e04eb)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
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
[中度](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=e9b64746-6afa-4a30-833d-e058e000c821)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中度](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=0df5d190-3ad7-42d5-8629-43c47ec450cb)
</td>
<td style="border:1px solid black;">
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
Microsoft .NET Framework 1.0  
(KB928367)
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
[重大](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=91d7afe4-069b-4ce8-976e-9a01345a8603)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft .NET Framework 1.0  
(KB930494)
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
[重大](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=829a2c5b-11ec-4ed7-91ab-6961034147bc)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1  
(KB928366)
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
[重大](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=281fb2cd-c715-4f05-a01f-0455d2d9ebfb)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1  
(KB933854)
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
[重大](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=2495e656-1e0a-4b83-90da-821e68067a71)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1  
(KB929729)
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
[重大](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=7eea368d-7b82-4583-8537-30351718a4e9)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0  
(KB928365)
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
[重大](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=ba3ceb78-8e1b-4c38-adfd-e8bc95ae548d)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0  
(KB929916)
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
[重大](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=cbc9f3cf-c3c3-45c4-82e3-e11398bc2cd2)
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
Excel 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
[重大](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=83d94d8e-dda6-4d74-b40d-476c2f0a3af4)
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
Excel 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=9d93c0ce-5124-4234-ba84-3c27005e010f)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Excel 2003 Viewer
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=11f42977-8828-494a-a183-d1aba827b708)
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
Excel 2007
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=9ab28283-0320-4527-b033-5e80ef32cd34)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Word、Excel 及 PowerPoint 2007 檔案格式的 Microsoft Office 相容性套件
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=e592ae5b-09ac-4f5b-b457-a54c9850ad4a)
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
Publisher 2007
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=25d272e7-f2dd-4342-92be-7ebc2e770b44)
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

**<sup>[1]</sup>** 已針對此作業系統提供了安全性更新程式。 請參閱表格中受影響的軟體或元件，以及相關的安全性公告以獲得詳細資訊。** **

** **

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和安全性更新。 如需更多資訊，請參閱 [TechNet 更新管理中心](http://go.microsoft.com/fwlink/?linkid=69903) 。 [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) 提供 Microsoft 產品安全性的其他資訊。 消費者可以造訪[在家上網的安全性](http://www.microsoft.com/taiwan/athome/security/default.mspx)網站，只要按一下 \[最新安全性更新\] 即可在此網站取得此資訊。

安全性更新可以從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)、[Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)及 [Office Update](http://go.microsoft.com/fwlink/?linkid=21135)取得。 安全性更新也可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得。 您也可以利用 "security\_patch" 關鍵字搜尋輕易地找到安全性更新。 最後，您可以從 Windows Update 目錄下載安全性更新。 如需有關 Windows Update 目錄的詳細資訊，請參閱 Microsoft [知識庫文件編號 323166](http://support.microsoft.com/kb/323166)。

**偵測與部署指南**

Microsoft 已提供本月安全性更新之偵測與部署指南。 此指南還能幫助 IT 專業人員瞭解如何使用各項工具來協助部署安全性更新，像是 Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office Detection Tool、Microsoft Systems Management Server (SMS)、加強版安全性更新盤點工具 (Extended Security Update Inventory Tool) 和企業更新掃描工具 (EST)。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 910723](http://support.microsoft.com/kb/910723)。

**Microsoft Baseline Security Analyzer 和Enterprise 合約** **更新掃描工具**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少安全性更新以及一般安全性設定錯誤的狀況。 如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) 網站 (英文)。

當 MBSA 1.2.1 無法支援偵測特定安全性更新時，Microsoft 會針對該安全性更新，發行特定版本的企業更新掃描工具 (EST)。 如需更多有關 EST 的資訊，請造訪[企業更新掃描工具](http://support.microsoft.com/default.aspx?id=894193)。

**注意：**2007 年 10 月 9 日之後，我們將不再更新 MBSA 1.2.1 使用的 MSSecure.XML 檔案。 在此之後，MBSA 1.2.1 使用的 MSSecure.XML 檔案將不會加入新的安全性更新，也不會有新版的企業掃描工具發行。 如需更多資訊，請造訪 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) (英文)。

**Software Update Services**

Microsoft Software Update Services (SUS) 能讓系統管理員以迅速可靠的方式，針對 Windows 2000 和 Windows Server 2003 伺服器以及執行 Windows 2000 Professional 或 Windows XP Professional 的桌面系統，部署最新的重要更新程式及安全性更新程式。

如果想進一步瞭解如何透過「軟體更新服務」來部署這個安全性更新，請造訪[軟體更新服務](http://go.microsoft.com/fwlink/?linkid=21133)網站。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速可靠地將 Windows 2000 作業系統及更新系統版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 等最新的重大更新與安全性更新部署到 Windows 2000 及更新作業系統版本中。

如需更多關於利用 Windows Server Update Services 部署安全性更新的資訊，請造訪 [Windows Server Update Services](http://www.microsoft.com/taiwan/windowsserversystem/updateservices/evaluation/overview.mspx) 網站。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。 如需更多關於系統管理員如何使用 SMS 2003 部署安全性更新的資訊，請瀏覽 [SMS 2003 的安全性補充程式管理](http://go.microsoft.com/fwlink/?linkid=22939)網站。 SMS 2.0 使用者也可以利用 [SMS 軟體更新服務功能套件](http://go.microsoft.com/fwlink/?linkid=33340)來協助部署安全性更新。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158)。

**注意：**SMS 使用 Microsoft Baseline Security Analyzer 及 Microsoft Office Detection Tool，為安全性公告更新的偵測及部署作業提供相當廣泛的支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可以用 Elevated Rights Deployment Tool (隨 [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) (英文) 和 [SMS 管理功能套件](http://go.microsoft.com/fwlink/?linkid=21161) (英文) 提供) 來安裝這些更新。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

請注意，此工具並非透過 Software Update Services (SUS) 散佈。

#### MU、WU、WSUS 及 SUS 上的非安全性、高優先順序更新

本月份：

-   Microsoft 已在 Microsoft Update (MU) 和 Windows Server Update Services (WSUS) 上發行了四個「非安全性」的高優先順序更新。
-   Microsoft 已在 Windows Update (WU) 和 Software Update Services (SUS) 上針對 Windows 發行了一個「非安全性」的高優先順序更新。

請注意，此資訊僅與 Microsoft Update、 Windows Update、Windows Server Update Services 和 Software Update Services 上，與本安全性公告摘要同日發行的「非安全性」高優先順序更新有關。 於其他日期發行的「非安全性」更新相關資訊並未包含在內。

#### 安全性策略與社群

**更新程式管理策略**

[修補程式管理安全性指南](http://go.microsoft.com/fwlink/?linkid=21168)提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用 "security\_patch" 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](http://support.microsoft.com/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](http://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](http://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 [OWASP](http://www.owasp.org/) 的 Dinis Cruz 回報 [MS07-040](http://technet.microsoft.com/security/bulletin/ms07-040) 中描述的問題。
-   感謝 [Security Assessment](http://www.smsiinc.com/) 的 Paul Craig 回報 [MS07-040](http://technet.microsoft.com/security/bulletin/ms07-040) 中描述的問題。
-   感謝 [Sumatra](http://www.sumatra.nl/) 的 Jeroen Frijters 回報 [MS07-040](http://technet.microsoft.com/security/bulletin/ms07-040) 中描述的問題。
-   感謝 [ProCheckUp](http://www.procheckup.com/) 與 [UK CPNI](http://www.cpni.gov.uk/) 原本回報 [MS07-040](http://technet.microsoft.com/security/bulletin/ms07-040) 中描述的問題。
-   感謝 [Portcullis Computer Security Ltd.](http://www.portcullis-security.com/) 的 Ferruh T. Mavituna 協助 Microsoft 解決 [MS07-040](http://technet.microsoft.com/security/bulletin/ms07-040) 中描述的問題並提供該問題之額外相關資訊。
-   感謝 [TrueSec](http://www.truesec.com/) 的 Johannes Gumbel 協助 Microsoft 解決 [MS07-040](http://technet.microsoft.com/security/bulletin/ms07-040) 中描述的問題並提供該問題之額外相關資訊。
-   感謝 [NGSSoftware](http://www.nextgenss.com/) 的 Peter Winter-Smith 回報 [MS07-039](http://technet.microsoft.com/security/bulletin/ms07-039) 中描述的問題。
-   感謝 [IBM Internet Security Systems x-Force](http://xforce.iss.net/) 的 Neel Mehta 回報 [MS07-039](http://technet.microsoft.com/security/bulletin/ms07-039) 中的描述的問題。
-   感謝 [eEye](http://www.eeye.com/) 回報 [MS07-037](http://technet.microsoft.com/security/bulletin/ms07-037) 中描述的問題。
-   感謝[賽門鐵克](http://www.symantec.com/)的 Jim Hoagland 和 Ollie Whitehouse 回報 [MS07-038](http://technet.microsoft.com/security/bulletin/ms07-038) 中描述的問題。
-   感謝 [Watchfire](http://www.watchfire.com/) 的 Jonathan Afek 和 Adi Sharabani 協助 Microsoft 解決 [MS07-041](http://technet.microsoft.com/security/bulletin/ms07-041) 中描述的問題並提供該問題之額外相關資訊。
-   感謝 [NGSSoftware](http://www.nextgenss.com/) 的 Peter Winter-Smith 協助 Microsoft 解決 [MS07-041](http://technet.microsoft.com/security/bulletin/ms07-041) 中描述的問題並提供該問題之額外相關資訊。

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可電洽 1-866-PCSAFETY [Microsoft 產品支援服務](http://go.microsoft.com/fwlink/?linkid=21131)以取得技術支援。 與安全性更新有關的支援電話不另外收費。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與安全性更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](http://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2007 年 7 月 11 日)： 公告摘要發行。

*Built at 2014-04-18T01:50:00Z-07:00*
