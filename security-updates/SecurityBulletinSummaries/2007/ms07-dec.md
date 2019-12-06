---
TOCTitle: 'MS07-DEC'
Title: 2007 年 12 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms07-dec'
ms:contentKeyID: 61237667
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms07-dec(v=Security.10)'
---

2007 年 12 月份 Microsoft 資訊安全公告摘要
==========================================

發行: 2007年12月12日 | 更新: 2008年1月30日

**版本:** 1.2

此公告摘要列出 2007 年 12 月份發行之安全性公告。

發行 2007 年 12 月份公告之後，此公告摘要將取代原先於 2007 年 12 月 6 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](http://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2007 年 12 月 12 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。 [立即註冊參加 12 月份安全性公告網路廣播](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344696&eventcategory=4&culture=en-us&countrycode=us)。 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](http://www.microsoft.com/taiwan/security/bulletins/default.mspx)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性、高優先順序更新的優先順序，其中這些非安全性、高優先順序更新的發行日期與每月安全性更新的發行日期相同。 請參閱＜其他資訊＞一節。

### 公告資訊

#### 提要

本月份安全性公告依嚴重性列出如下：

重大 (3)
--------

<span></span>

| 公告編號             | Microsoft 安全性公告 MS07-064                                                                                                                                                                                                                                                                                                                                                                                                |
|----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**DirectX 中的弱點可能會允許遠端執行程式碼 (941568)**](http://technet.microsoft.com/security/bulletin/ms07-064)                                                                                                                                                                                                                                                                                                             |
| **提要**             | 這個重大安全性更新可解決 Microsoft DirectX 中兩項未公開報告的弱點。 如果使用者在 DirectX 中開啟用來串流媒體的蓄意製作檔案，則這些弱點可能會允許執行程式碼。 如果使用者以系統管理的使用者權限登入，成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                                                                               |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新將不需要重新啟動，除非在某些情況下。                                                                                                                                                                                                                                                                                                         |
| **受影響的軟體**     | **Windows、DirectX、DirectShow。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                                                                      |

| 公告編號             | Microsoft 安全性公告 MS07-068                                                                                                                                                                                                                         |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Windows Media 檔案格式中的弱點可能會允許遠端執行程式碼 (941569 及 944275)**](http://technet.microsoft.com/security/bulletin/ms07-068)                                                                                                              |
| **提要**             | 這個重大安全性更新可解決 Windows Media 格式中一項未公開報告的弱點。 如果使用者在 Windows Media Format Runtime 中檢視蓄意製作的檔案，此弱點可能會允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                         |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                        |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新將不需要重新啟動，除非在某些情況下。                                                                                                                                  |
| **受影響的軟體**     | **Windows、Windows Media Format Runtime。 **如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                      |

| 公告編號             | Microsoft 安全性公告 MS07-069                                                                                                                                                                                                               |
|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Internet Explorer 積存安全性更新 (942615)**](http://technet.microsoft.com/security/bulletin/ms07-069)                                                                                                                                    |
| **提要**             | 這個重大安全性更新可解決四項未公開報告的弱點。 如果使用者以 Internet Explorer 檢視蓄意製作的網頁，則對安全性方面造成的最嚴重影響可能會允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                               |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                              |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新需要重新啟動電腦。                                                                                                                                          |
| **受影響的軟體**     | **Windows、Internet Explorer。 **如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                       |

重要 (4)
--------

<span></span>

| 公告編號             | Microsoft 安全性公告 MS07-063                                                                                                                                                                 |
|----------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**SMBv2 中的弱點可能會允許遠端執行程式碼 (942624)**](http://technet.microsoft.com/security/bulletin/ms07-063)                                                                                |
| **提要**             | 這個重要安全性更新可解決伺服器訊息區第 2 版 (SMBv2) 中一項未公開報告的弱點。 這項弱點可能會允許攻擊者竄改透過 SMBv2 傳輸的資料，這麼一來可能會允許在與 SMBv2 通訊的網域設定中遠端執行程式碼。 |
| **最高的嚴重性等級** | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                 |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新需要重新啟動電腦。                                                                                            |
| **受影響的軟體**     | **Windows。 **如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                            |

| 公告編號             | Microsoft 安全性公告 MS07-065                                                                                                                                                                                                                                                                                                                                                                                 |
|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**訊息佇列中的弱點可能會允許遠端執行程式碼 (937894)**](http://technet.microsoft.com/security/bulletin/ms07-065)                                                                                                                                                                                                                                                                                              |
| **提要**             | 這個重要的安全性更新可解決 Message Queuing Service (MSMQ) 中未公開報告的弱點，也就是允許在 Microsoft Windows 2000 Server 的實作中遠端執行程式碼，或在 Microsoft Windows 2000 Professional 與 Windows XP 的實作中提高權限。 攻擊者必須具備有效的登入認證，才可以利用 Microsoft Windows 2000 Professional 與 Windows XP 上的提高權限弱點。 攻擊者接下來能在系統上安裝程式；檢視、變更或刪除資料；或建立新帳戶。 |
| **最高的嚴重性等級** | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                 |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                                                                |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新需要重新啟動電腦。                                                                                                                                                                                                                                                                                                            |
| **受影響的軟體**     | **Windows。 **如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                                                                            |

| 公告編號             | Microsoft 安全性公告 MS07-066                                                                                                                                                                                   |
|----------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Windows 核心中的弱點可能會允許權限提高 (943078)**](http://technet.microsoft.com/security/bulletin/ms07-066)                                                                                                  |
| **提要**             | 這個重要的安全性更新可解決 Windows 核心中一項未公開報告的弱點。 成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 接下來，攻擊者就能安裝程式，檢視、變更或刪除資料，或是建立具有完整系統管理權限的新帳戶。 |
| **最高的嚴重性等級** | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                   |
| **弱點的影響**       | 權限提高                                                                                                                                                                                                        |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新需要重新啟動電腦。                                                                                                              |
| **受影響的軟體**     | **Windows。 **如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                              |

| 公告編號             | Microsoft 安全性公告 MS07-067                                                                                                                                                                                                                                            |
|----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Macrovision 驅動程式中的弱點可能會允許本機提高權限 (944653)**](http://technet.microsoft.com/security/bulletin/ms07-067)                                                                                                                                               |
| **提要**             | 這個重要的安全性更新能解決一項公開揭發的弱點。 在 Macrovision 驅動程式以錯誤方式處理設定參數的方式中，存在本機提高權限的弱點。 成功利用此弱點的本機攻擊者可以取得系統的控制權。 接下來，攻擊者就能安裝程式，檢視、變更或刪除資料，或是建立具有完整系統管理權限的新帳戶。 |
| **最高的嚴重性等級** | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                            |
| **弱點的影響**       | 本機權限提高                                                                                                                                                                                                                                                             |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新需要重新啟動電腦。                                                                                                                                                                       |
| **受影響的軟體**     | **Windows。 **如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                       |

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
<th style="border:1px solid black;" >
詳細資訊        
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS07-063**](http://technet.microsoft.com/security/bulletin/ms07-063)
</td>
<td style="border:1px solid black;">
[**MS07-064**](http://technet.microsoft.com/security/bulletin/ms07-064)
</td>
<td style="border:1px solid black;">
[**MS07-065**](http://technet.microsoft.com/security/bulletin/ms07-065)
</td>
<td style="border:1px solid black;">
[**MS07-066**](http://technet.microsoft.com/security/bulletin/ms07-066)
</td>
<td style="border:1px solid black;">
[**MS07-067**](http://technet.microsoft.com/security/bulletin/ms07-067)
</td>
<td style="border:1px solid black;">
[**MS07-068**](http://technet.microsoft.com/security/bulletin/ms07-068)
</td>
<td style="border:1px solid black;">
[**MS07-069**](http://technet.microsoft.com/security/bulletin/ms07-069)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最高的嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
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
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<th colspan="8">
Windows 作業系統
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=bda9d0b4-f7cb-4d9d-b030-043d7437734b)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=09d4e6ae-5d19-4f11-bb7e-60cee8263bc8)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=c7d368d0-f7bf-4946-a4a6-3e88315e5317)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=5f4fa8e9-fcf2-4daf-93c0-8bb267da69aa)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=5f4fa8e9-fcf2-4daf-93c0-8bb267da69aa)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=0f84f5e2-1dd8-4882-b796-444ab70b6b02)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=0f84f5e2-1dd8-4882-b796-444ab70b6b02)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=1f416b71-783f-4cbc-9b85-9a9be7daa0d7)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=1f416b71-783f-4cbc-9b85-9a9be7daa0d7)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP1 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=9d22a9ee-cc08-4b2d-af4e-55d326f82761)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=9787619f-1297-411e-8b9c-3ad3e6a99797)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=05a9501c-4da3-4fa1-901e-99cb262e5e36)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=5f382050-8df6-43aa-82e9-8fad5ff8ecec)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<th colspan="8">
Windows 作業系統元件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 上的 DirectX 7.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=06196774-5a11-4525-b53c-8cb000738949)
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
Microsoft Windows 2000 Service Pack 4 上的 DirectX 8.1
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=ccb872bd-fc06-4a3f-ac70-3c9a42d57b37)
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
Microsoft Windows 2000 Service Pack 4 上的 DirectX 9.0\*
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=03b14ce0-5189-4803-8151-6ac5cb6a9179)
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
Windows XP Service Pack 2 上的 DirectX 9.0\*
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=04a8f8d3-69f9-4445-baab-f45616a6b9b7)
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
Windows XP Professional x64 Edition 與 Windows XP Professional x64 Edition Service Pack 2 中的 DirectX 9.0\*
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?familyid=f096c500-e765-4e75-8443-7ffec4ddf149)
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
Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 上的 DirectX 9.0\*
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=d80a295a-baf9-4981-8a28-1b4207ecc5f7)
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
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 上的 DirectX 9.0\*
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=378086ea-60b8-409f-970a-fcfd62025150)
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
適用於 Itanium 型系統的 Windows Server 2003 SP1 和適用於 Itanium 型系統的 Windows Server 2003 SP2 上的 DirectX 9.0\*
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?familyid=2e6ea4bb-9f4f-46fb-9d51-e20b15e61a89)
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
Windows Vista 上的 DirectX 10.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=bfa571bc-e43f-45e3-bc98-4086985c99aa)
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
Windows Vista x64 Edition 上的 DirectX 10.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=3d8803da-108b-4b9d-a039-84932dce8e42)
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
Microsoft Windows 2000 Service Pack 4 中的 Internet Explorer 5.01 Service Pack 4
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
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=b3bd16ea-5d69-4ae3-84b3-ab773052ceeb)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
安裝在 Microsoft Windows 2000 Service Pack 4 上的 Internet Explorer 6 Service Pack 1
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
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=bc8edf05-262a-4d1d-b196-4fc1a844970c)
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
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=6e4ebafc-34c3-4dc7-b712-152c611d3f0a)
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
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=f5a5af23-30fb-4e47-94bd-3b05b55c92f2)
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
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=bf466060-a585-4c2e-a48d-70e080c3bbe7)
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
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=074697f2-18c8-4521-bbf7-1d0e7395d27d)
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
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?familyid=b3f390a6-0361-4553-b627-5e7ad6bf5055)
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
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=b15a6506-02dd-43c2-aef4-e10c1c76ee97)
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
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=c092a6bb-8e62-4d90-bdb1-5f3a15968f75)
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
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=34759c10-16a5-42a2-974d-9d532fb5a0a7)
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
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=7dccce5a-7562-448b-a345-cf1cc758e35c)
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
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?familyid=8414f3fb-216a-4d46-b590-4c1f304dff91)
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
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=26d303da-bb2e-4555-96f1-becb0e277341)
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
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=c5e88e0b-a4c2-4690-91d9-326800030a16)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 上的 Windows Media Format Runtime 7.1 (KB941569)
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
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=eecdf2ce-9aa7-4f0c-b62b-2fa7a32f369e)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 上的 Windows Media Format Runtime 9 (KB941569)
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
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=eecdf2ce-9aa7-4f0c-b62b-2fa7a32f369e)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 2 上的 Windows Media Format Runtime 9 (KB941569)
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
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=bece702a-6e61-433e-8275-20f4e84f2c92)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 上的 Windows Media Format Runtime 9.5 (KB941569)
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
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=bece702a-6e61-433e-8275-20f4e84f2c92)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2 上的 Windows Media Format Runtime 9.5 (KB941569)
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
[重大](https://www.microsoft.com/download/details.aspx?familyid=81f20b45-dfc7-4ddf-a4b4-6c0e9476ed51)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 上的 Windows Media Format Runtime 9.5 (KB941569)
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
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=8fea7da8-a7f3-4786-97c2-fb5ea7018159)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 上的 Windows Media Format Runtime 9.5 (KB941569)
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
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=ffc69c76-02f1-4b15-8ec1-dab8c7e33bd4)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 上的 Windows Media Format Runtime 9.5 x64 Edition (KB941569)
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
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=ffc69c76-02f1-4b15-8ec1-dab8c7e33bd4)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2 上的 Windows Media Format Runtime 9.5 x64 Edition (KB941569)
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
[重大](https://www.microsoft.com/download/details.aspx?familyid=72d2ca0e-da81-45ee-9321-4970b80f4a5a)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 上的 Windows Media Format Runtime 11 (KB941569)
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
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=bece702a-6e61-433e-8275-20f4e84f2c92)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2 上的 Windows Media Format Runtime 11 (KB941569)
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
[重大](https://www.microsoft.com/download/details.aspx?familyid=1037b224-ac89-4efd-b189-6f3da77a88e6)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 上的 Windows Media Format Runtime 11 (KB941569)
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
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=9a98ef96-bc2e-42b7-9a24-c82c8fb379db)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 上的 Windows Media Format Runtime 11 (KB941569)
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
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=3ce02c95-d695-4f14-9fb3-30c83a9cfb9c)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 上的 Windows Media Services 9.1 (KB944275)
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
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=096711d4-ce01-45d0-9c2d-ebfa5c671b9f)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 上的 Windows Media Services 9.1 x64 Edition (KB944275)
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
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=23c23800-5aaa-455b-96bf-4ead4dfdd95d)
</td>
<td style="border:1px solid black;">
</td>
</tr>
</table>
 
**注意：**

**<sup>[1]</sup>** 已針對此作業系統提供了安全性更新程式。 請參閱表格中受影響的軟體或元件，以及相關的安全性公告以獲得詳細資訊。

\*包括 DirectX 9.0b 和 DirectX 9.0c

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

**注意：**2007 年 10 月 9 日之後，我們將不再更新 MBSA 1.2.1 使用的 MSSecure.XML 檔案。 在此之後，MBSA 1.2.1 使用的 MSSecure.XML 檔案將不會加入新的安全性更新，也不會有新版的企業掃描工具發行。 這不影響適用於 SMS 2.0 和 SMS 2003 的 Security Update Inventory Tool (安全性更新清查工具，SUIT) 以及 Extended Security Update Inventory Tool (加強版安全性更新清查工具，ESUIT)。如需更多資訊，請造訪 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) (英文)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速可靠地將 Windows 2000 作業系統及更新系統版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 等最新的重大更新與安全性更新部署到 Windows 2000 及更新作業系統版本中。

如需更多關於利用 Windows Server Update Services 部署安全性更新的資訊，請造訪 [Windows Server Update Services](http://www.microsoft.com/taiwan/windowsserversystem/updateservices/evaluation/overview.mspx) 網站。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。 如需更多關於系統管理員如何使用 SMS 2003 部署安全性更新的資訊，請瀏覽 [SMS 2003 的安全性補充程式管理](http://www.microsoft.com/taiwan/smserver/evaluation/capabilities/patch.htm)網站。 SMS 2.0 使用者也可以利用 [SMS 軟體更新服務功能套件](http://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/suspack/default.htm)來協助部署安全性更新。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server](http://www.microsoft.com/taiwan/smserver/)。

**注意：**SMS 使用 Microsoft Baseline Security Analyzer 及 Microsoft Office Detection Tool，為安全性公告更新的偵測及部署作業提供相當廣泛的支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可以用 Elevated Rights Deployment Tool (隨 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/taiwan/smserver/downloads/2003/adminpack.htm) 和 [SMS 管理功能套件](http://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/adminpack/default.htm) 提供) 來安裝這些更新。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非安全性、高優先順序更新

本月份：

-   Microsoft 已在 Microsoft Update (MU) 和 Windows Server Update Services (WSUS) 上發行四個「非安全性」高優先順序更新及 2007 Microsoft Office Service Pack 1。
-   Microsoft 已在 Windows Update (WU) 和 WSUS 上針對 Windows 和 Windows SharePoint Services 3.0 Service Pack 1 發行四個「非安全性」高優先順序更新。

請注意，此資訊僅與 Microsoft Update、Windows Update 和 Windows Server Update Services 上，與本安全性公告摘要同日發行的「非安全性」高優先順序更新有關。 於其他日期發行的「非安全性」更新相關資訊並未包含在內。

#### 安全性策略與社群

**更新程式管理策略**

[修補程式管理安全性指南](http://www.microsoft.com/taiwan/technet/security/topics/patchmanagement.mspx)提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](http://support.microsoft.com/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](http://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](http://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 [VeriSign iDefense Labs](http://labs.idefense.com/) 的 Jun Mao 協助我們解決 MS07-064 中所述之問題
-   感謝 [NGSSoftware](http://www.ngssoftware.com/) 的 Peter Winter Smith 協助我們解決 MS07-064 中所述之問題
-   感謝 [AhnLab](http://global.ahnlab.com/) 的 Jung-hyung Lee 協助我們處理 MS07-064 中所述之 DirectX 的深度防禦變更
-   感謝 [Zero Day Initiative](http://www.zerodayinitiative.com/) 協助我們解決 MS07-065 中所述之問題
-   感謝 [ADLABS](http://www.venustech.com.cn/) 的 Venustech 協助我們解決 MS07-065 中所述之問題
-   感謝 [SkyRecon](http://www.skyrecon.com/) 的 Thomas Garnier 回報 MS07-066 中描述的問題
-   感謝 [ISS X-Force](http://xforce.iss.net/) 的 Ryan Smith 協助我們解決 MS07-068 中所述之問題
-   感謝 Peter Vreugdenhil 與 [iDefense VCP](http://idefense.com/) 合作，共同回報 MS07-069 中描述的問題
-   感謝匿名的研究人員和 [TippingPoint](http://www.tippingpoint.com/) 及 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 MS07-069 中描述的問題。
-   感謝 Sam Thomas 與 [TippingPoint](http://www.tippingpoint.com/) 及 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 MS07-069 中描述的問題。
-   感謝 Peter Vreugdenhil 與 [TippingPoint](http://www.tippingpoint.com/) 及 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 MS07-069 中描述的問題。

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可電洽 1-866-PCSAFETY [Microsoft 產品支援服務](http://go.microsoft.com/fwlink/?linkid=21131)以取得技術支援。 與安全性更新有關的支援電話不另外收費。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與安全性更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](http://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2007 年 12 月 12 日)： 公告摘要發行。
-   V1.1 (2007 年 12 月 14 日)： 更新公告，以反映 MS07-065 和 MS-07-067 公告的提要變更。
-   V1.2 (2008 年 1 月 30 日)： 更新公告以反映 MS07-064 公告受影響軟體的變更。

*Built at 2014-04-18T01:50:00Z-07:00*
