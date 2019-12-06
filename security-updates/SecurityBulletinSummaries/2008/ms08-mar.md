---
TOCTitle: 'MS08-MAR'
Title: 2008 年 3 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms08-mar'
ms:contentKeyID: 61237684
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms08-mar(v=Security.10)'
---

2008 年 3 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2008年3月12日

**版本:** 1.0

此公告摘要列出 2008 年 3 月份所發行之安全性公告。

發行 2008 年 3 月份公告之後，此公告摘要將取代原先於 2008 年 3 月 6 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](https://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2008 年 3 月 12 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。 [立即註冊參加 3 月份安全性公告網路廣播。](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357217&eventcategory=4&culture=en-us&countrycode=us) 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](https://www.microsoft.com/taiwan/security/bulletins/default.mspx)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性、高優先順序更新的優先順序，其中這些非安全性、高優先順序更新的發行日期與每月安全性更新的發行日期相同。 請參閱＜其他資訊＞一節。

### 公告資訊

#### 提要

本月份安全性公告依嚴重性列出如下：

重大 (4)
--------

<span></span>
| 公告編號             | Microsoft 安全性公告 MS08-014                                                                                                                                                                                                                                                                                                                                              |
|----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Microsoft Excel 中的弱點可能會允許遠端執行程式碼 (949029)**](https://technet.microsoft.com/security/bulletin/ms08-014)                                                                                                                                                                                                                                                   |
| **提要**             | 此安全性更新可解決 Microsoft Office Excel 中數個未公開報告和公開報告的弱點，該弱點可在使用者開啟蓄意製作的 Excel 檔案時，允許遠端執行程式碼。 成功利用這類弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重大](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                              |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                             |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新不需要重新啟動電腦。                                                                                                                                                                                                                                                                       |
| **受影響的軟體**     | **Microsoft Office：** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                                |

| 公告編號             | Microsoft 安全性公告 MS08-015                                                                                                                                                                                                                                                                                                                                                           |
|----------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Microsoft Outlook 中的弱點可能會允許遠端執行程式碼 (949031)**](https://technet.microsoft.com/security/bulletin/ms08-015)                                                                                                                                                                                                                                                              |
| **提要**             | 這個安全性更新可解決 Microsoft Office Outlook 中一項未公開報告的弱點。 當 Outlook 收到一蓄意製作的 mailto URI，此弱點可能會允許遠端執行程式碼。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 光是透過 Outlook 預覽窗格檢視電子郵件，並不會導致這個弱點遭到利用。 |
| **最高的嚴重性等級** | [重大](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                           |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                                          |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新不需要重新啟動電腦。                                                                                                                                                                                                                                                                                    |
| **受影響的軟體**     | **Microsoft Office：**如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                                             |

| 公告編號             | Microsoft 安全性公告 MS08-016                                                                                                                                                                                                                                                                                                                                 |
|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Microsoft Office 的弱點可能會允許遠端執行程式碼 (949030)**](https://technet.microsoft.com/security/bulletin/ms08-016)                                                                                                                                                                                                                                       |
| **提要**             | 這個安全性更新可解決 Microsoft Office 中兩項未公開報告的弱點，該弱點可在使用者開啟格式錯誤的 Office 檔案時，允許從遠端執行程式碼。 成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重大](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                 |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新不需要重新啟動電腦。                                                                                                                                                                                                                                                          |
| **受影響的軟體**     | **Microsoft Office：** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                   |

| 公告編號             | Microsoft 安全性公告 MS08-017                                                                                                                                                                                                                                                                                                                                          |
|----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Microsoft Office Web 元件的弱點可能會允許遠端執行程式碼 (933103)**](https://technet.microsoft.com/security/bulletin/ms08-017)                                                                                                                                                                                                                                        |
| **提要**             | 這個重大的更新程式可解決 Microsoft Office Web 元件中兩項未公開報告的弱點。 如果使用者檢視蓄意製作的網頁，這些弱點可能會允許遠端執行程式碼。 成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重大](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                          |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                         |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新可能需要重新啟動電腦。                                                                                                                                                                                                                                                                 |
| **受影響的軟體**     | **Microsoft Office Web 元件。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                   |

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
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-014**](https://technet.microsoft.com/security/bulletin/ms08-014)
</td>
<td style="border:1px solid black;">
[**MS08-015**](https://technet.microsoft.com/security/bulletin/ms08-015)
</td>
<td style="border:1px solid black;">
[**MS08-016**](https://technet.microsoft.com/security/bulletin/ms08-016)
</td>
<td style="border:1px solid black;">
[**MS08-017**](https://technet.microsoft.com/security/bulletin/ms08-017)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最高的嚴重性等級**
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
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<th colspan="5">
Office 套件及軟體
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?familyid=72735aa1-e22c-40ed-8c79-38fba89979aa)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=72735aa1-e22c-40ed-8c79-38fba89979aa)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=9f25922c-d3c2-4ef1-b164-8a21a77d29aa)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=f7f90c30-1bfd-406b-a77f-612443e30185)
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
Microsoft Office Excel 2002 Service Pack 3
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=907f96d5-d1e9-4471-b41c-3ac811e63038)
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
Microsoft Office Excel 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=296e5f2c-f594-41c8-a20a-3e4c40ae3948)
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
Microsoft Office Excel Viewer 2003
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=280bb2ac-b21a-46b5-8751-5a50fbebf107)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=9f25922c-d3c2-4ef1-b164-8a21a77d29aa)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel Viewer 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=9f25922c-d3c2-4ef1-b164-8a21a77d29aa)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Excel 2007
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=e7634cb5-9531-4284-9554-4168fc488e0c)
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
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=e9251d71-9098-4125-ae91-7d4c83ea58ad)
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
Microsoft Office Outlook 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=714a49cd-5bca-4719-96a1-e1077f279533)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Outlook 2002 Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=59853687-d885-4059-9460-ee403855dbd8)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Outlook 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=fccc7c4c-8496-4682-bd46-6590503c1bf2)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Outlook 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=fccc7c4c-8496-4682-bd46-6590503c1bf2)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Outlook 2007
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=4e2baf00-88eb-4eb6-961a-54245b363c21)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=95dceb37-b35f-46db-b280-db0f3b298aa9)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=95dceb37-b35f-46db-b280-db0f3b298aa9)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=8fe8c32a-6d7a-482b-97c6-42562f089ee4)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="5">
其他軟體
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Web Components 2000  
(KB931660)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?familyid=806c654a-35e3-4385-855a-4b803249bfcf)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Components 2000  
(KB932031)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=f54d2a5e-c0ed-4f70-9746-38dd61c8e9d7)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Web Components 2000  
(KB933367)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=d71b23fa-a873-406d-bad7-e38e565dee39)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Components 2000  
(KB933369)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=2fe10ccd-40cb-4090-b83d-eae3d4eca174)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Web Components 2000  
(KB939714)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?familyid=e0993e49c0a811d2973d00c04f79e4b3)  
**<sup>[2]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Components 2000  
(KB939714)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?familyid=12b7d09a92ab4596996670799837d961)  
**<sup>[3]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Web Components 2000  
(KB941305)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?familyid=71de76ba-b62c-4a7a-a78a-9317f5255b13)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Components 2000  
(KB948257)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?familyid=526d87bd-c3da-412e-8765-c15987ae9b01)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Visual Studio .NET 2002 Service Pack 1  
(KB933367)
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
</tr>
<tr>
<td style="border:1px solid black;">
Visual Studio .NET 2003 Service Pack 1  
(KB933369)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft BizTalk Server 2000  
(KB939714)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft BizTalk Server 2002  
(KB939714)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Commerce Server 2000  
(KB941305)
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
</tr>
<tr>
<td style="border:1px solid black;">
Internet Security and Acceleration Server 2000 Service Pack 2  
(KB948257)
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
</tr>
</table>
 
**注意：**

**<sup>[1]</sup>** 已針對此軟體提供了安全性更新程式。 請參閱表格中受影響的軟體或元件，以及相關的安全性公告以獲得詳細資訊。** **

**<sup>[2]</sup>**這個安全性更新與 Microsoft BizTalk Server 2000 有關。請參閱相關的安全性公告以瞭解詳細資料。

**<sup>[3]</sup>**這個安全性更新與 Microsoft BizTalk Server 2002 有關。請參閱相關的安全性公告以瞭解詳細資料。

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和安全性更新。 如需更多資訊，請參閱 [TechNet 更新管理中心](https://www.microsoft.com/taiwan/technet/updatemanagement/default.mspx) 。 [TechNet Security Center](https://www.microsoft.com/taiwan/technet/security/default.mspx) 提供 Microsoft 產品安全性的其他資訊。 消費者可以造訪[在家上網的安全性](https://www.microsoft.com/taiwan/athome/security/default.mspx)網站，只要按一下 \[最新安全性更新\] 即可在此網站取得此資訊。

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

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。 現已推出新版的 SMS，System Center Configuration Manager 2007；另請參閱 [System Center Configuration Manager 2007](https://technet.microsoft.com/en-us/library/bb735860.aspx)。如需更多有關系統管理員如何能使用 SMS 2003 部署安全性更新的資訊，請參閱 [SMS 2003 安全性修補程式管理](https://www.microsoft.com/taiwan/smserver/evaluation/capabilities/patch.htm) 。 SMS 2.0 使用者也可以利用 [SMS 軟體更新服務功能套件](https://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/suspack/default.htm)來協助部署安全性更新。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server](https://www.microsoft.com/taiwan/smserver)。

**注意：**SMS 使用 Microsoft Baseline Security Analyzer 及 Microsoft Office Detection Tool，為安全性公告更新的偵測及部署作業提供相當廣泛的支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](https://go.microsoft.com/fwlink/?linkid=33341)。 某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可以用 Elevated Rights Deployment Tool (隨 [SMS 2003 Administration Feature Pack](https://www.microsoft.com/taiwan/smserver/downloads/2003/adminpack.htm) 和 [SMS 管理功能套件](https://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/adminpack/default.htm) 提供) 來安裝這些更新。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非安全性、高優先順序更新

本月份：

-   Microsoft 已在 Microsoft Update (MU) 和 Windows Server Update Services (WSUS) 上發行了兩個「非安全性」的高優先順序更新。
-   Microsoft 已在 Windows Update (WU) 及 WSUS 上針對 Windows 發行三個「非安全性」高優先順序更新。

請注意，此資訊僅與 Microsoft Update、Windows Update 和 Windows Server Update Services 上，與本安全性公告摘要同日發行的「非安全性」高優先順序更新有關。 於其他日期發行的「非安全性」更新相關資訊並未包含在內。

#### 安全性策略與社群

**更新程式管理策略**

[更新管理安全性指南](https://www.microsoft.com/taiwan/technet/security/topics/patchmanagement.mspx) 提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](https://support.microsoft.com/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](https://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](https://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 [SAIC](https://www.saic.com/) 的 Mike Scott 回報 MS08-014 中描述的問題
-   感謝 [VeriSign](https://www.verisign.com/) 的 Matt Richard 回報 MS08-014 中描述的問題
-   感謝 [iDefense Labs](https://labs.idefense.com/) 的 Greg MacManus 回報 MS08-014 中描述的問題
-   感謝 [JFE Systems](https://www.jfe-systems.com/) 的 Yoshiya Sasaki 回報 MS08-014 中描述的問題
-   感謝 [Fortinet](https://www.fortinet.com/) 的 Bing Liu 回報 MS08-014 中描述的問題
-   感謝 [iDefense Labs](https://labs.idefense.com/) 回報 MS08-014 中描述的問題
-   感謝 [TippingPoint DVLabs](https://dvlabs.tippingpoint.com/) 的 Cody Pierce 回報 MS08-014 中描述的問題
-   感謝 [Websense Security Labs](https://www.websense.com/) 的 Moti Joseph 和 Dan Hubbard 回報 MS08-014 中描述的問題
-   感謝 [iDefense Labs](https://labs.idefense.com/) 的 Greg MacManus 回報 MS08-015 中描述的問題
-   感謝與 [Zero Day Initiative (ZDI)](https://www.zerodayinitiative.com/) 合作的 Arnaud Dovi 回報 MS06-016 中描述的問題
-   感謝一位匿名的發現者回報 MS06-016 中描述的問題
-   感謝 [VigilantMinds Inc.](https://www.vigilantminds.com/) 的 Chris Ries 回報 MS08-017 中描述的問題
-   感謝 [NCNIPC](https://www.nipc.org.cn/) 的 Xiao Hui 回報 MS08-017 中描述的問題
-   感謝 [Finjan](https://www.finjan.com/) 的 Yuval Ben-Itzhak 回報 MS08-017 中描述的問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可電洽 1-866-PCSAFETY [Microsoft 產品支援服務](https://go.microsoft.com/fwlink/?linkid=21131)以取得技術支援。 與安全性更新有關的支援電話不另外收費。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與安全性更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](https://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2008 年 3 月 12 日)： 公告摘要發行。

*Built at 2014-04-18T01:50:00Z-07:00*
