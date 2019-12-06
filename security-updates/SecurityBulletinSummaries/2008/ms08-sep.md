---
TOCTitle: 'MS08-SEP'
Title: 2008 年 9 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms08-sep'
ms:contentKeyID: 61237688
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms08-sep(v=Security.10)'
---

2008 年 9 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2008年9月10日 | 更新: 2008年12月22日

**版本:** 3.0

此公告摘要列出 2008 年 9 月份發行之安全性公告。

發行 2008 年 9 月份公告之後，此公告摘要將取代原先於 2008 年 9 月 4 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](http://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2008 年 9 月 10 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。 [立即註冊參加 9 月份安全性公告網路廣播](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374633&eventcategory=4&culture=en-us&countrycode=us)。 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](http://www.microsoft.com/taiwan/security/bulletins/default.mspx)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性、高優先順序更新的優先順序，其中這些非安全性、高優先順序更新的發行日期與每月安全性更新的發行日期相同。 請參閱＜其他資訊＞一節。

### 公告資訊

#### 提要

本月份安全性公告依嚴重性列出如下：

重大 (4)
--------

<span></span>

| 公告編號             | Microsoft 安全性公告 MS08-054                                                                                                                                                                                                                                                                                                                                                                                 |
|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Windows Media Player 中的弱點可能會允許遠端執行程式碼 (954154)**](http://technet.microsoft.com/security/bulletin/ms08-054)                                                                                                                                                                                                                                                                                 |
| **提要**             | 此安全性更新可解決 Windows Media Player 中一項未公開報告的弱點，該弱點可在從 Windows Media Server 串流蓄意製作的音訊檔時允許遠端執行程式碼。 如果使用者以系統管理的使用者權限登入，成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                 |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                                                                |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新不需要重新開機。                                                                                                                                                                                                                                                                                                              |
| **受影響的軟體**     | **Microsoft Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                                                                  |

| 公告編號             | Microsoft 安全性公告 MS08-052                                                                                                                                                                                                                                       |
|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**GDI+ 中的弱點可能會允許遠端執行程式碼 (954593)**](http://technet.microsoft.com/security/bulletin/ms08-052)                                                                                                                                                       |
| **提要**             | 這個安全性更新可解決 Microsoft Windows GDI+ 中數個未公開報告的弱點。 如果使用者使用受影響的軟體檢視特製影像檔，或者瀏覽內含特製內容的網站，那麼這些弱點可能會允許遠端執行程式碼‧。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                       |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                      |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 本更新程式需要重新開機。                                                                                                                                                                  |
| **受影響的軟體**     | **Microsoft Windows、Internet Explorer、.NET Framework、Office、SQL Server、Visual Studio.** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                   |

| 公告編號             | Microsoft 安全性公告 MS08-053                                                                                                                                                                                                                                                                                                                                                                                |
|----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Windows Media Encoder 9 中的弱點可能會允許遠端執行程式碼 (954156)**](http://technet.microsoft.com/security/bulletin/ms08-053)                                                                                                                                                                                                                                                                             |
| **提要**             | 這個安全性更新可解決 Windows Media Encoder 9 Series 中一項未公開報告的弱點。 如果使用者檢視蓄意製作的網頁，此弱點可能會允許遠端執行程式碼。 如果使用者以系統管理的使用者權限登入，成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                                                               |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新可能需要重新啟動電腦。                                                                                                                                                                                                                                                                                                       |
| **受影響的軟體**     | **Microsoft Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                                                                 |

| 公告編號             | Microsoft 安全性公告 MS08-055                                                                                                                                                                                                                                                                                                                                      |
|----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Microsoft Office 中的弱點可能會允許遠端執行程式碼 (955047)**](http://technet.microsoft.com/security/bulletin/ms08-055)                                                                                                                                                                                                                                          |
| **提要**             | 這個安全性更新可解決 Microsoft Office 中一項未公開報告的弱點。 如果使用者按一下蓄意製作的 OneNote URL，此弱點便可能允許遠端執行程式碼。 成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重大](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                      |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                     |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 在多數的情況下，此更新不需要重新開機。                                                                                                                                                                                                                                                   |
| **受影響的軟體**     | **Microsoft Office：** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                        |

受影響的軟體及下載位置
----------------------

<span></span>
**我該如何使用這個表格？**

請用這個表格來瞭解可能需要安裝的安全性更新有哪些。 您應該查看此處列出的每一種軟體程式或元件，看看是否有需要的安全性更新。 若軟體程式或更新出現在清單中，則相關可用軟體更新也會以超連結方式提供，也會列出軟體更新的嚴重性等級。

**注意**：一項弱點，可能需要安裝數個安全性更新才能妥善解決。 請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。

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
</tr>
<tr>
<th colspan="4">
Microsoft Windows 2000
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-054**](http://technet.microsoft.com/security/bulletin/ms08-054)
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-053**](http://technet.microsoft.com/security/bulletin/ms08-053)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=a860d2d9-653d-4ddb-bbff-323d3ccdb866)  
(KB938464)  
(重大)  
[Microsoft .NET Framework 1.0 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=c7cbcd19-acc1-4a89-adfa-99b2f431510d)  
(KB947739)  
(無嚴重性等級)  
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=6013f866-3ea1-4672-b1bf-e516204c3a7a)  
(KB947742)  
(無嚴重性等級)  
[Microsoft .NET Framework 2.0](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=7f1cd013-2c4b-4582-9114-cb840a96124a)  
(KB947746)  
(無嚴重性等級)  
[Microsoft .NET Framework 2.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=215b73a3-46ab-44a8-a0fb-6d37bd1c39b8)  
(KB947748)  
(無嚴重性等級)
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=0cabfbc0-db5d-4a6a-a4cd-e6df89ac2b25)  
(重大)
</td>
</tr>
<tr>
<th colspan="4">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-054**](http://technet.microsoft.com/security/bulletin/ms08-054)
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-053**](http://technet.microsoft.com/security/bulletin/ms08-053)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 及 Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=d5891180-5dd1-49ec-bcc6-3030a544202c)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 與 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=e0bd6fbe-f46e-4961-9a79-49ec77d39439)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=57bcb3c2-49d3-4f18-8d03-36abd03d7403)  
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=caf8a45e-a9f8-4e91-98fd-87eddbeae64c)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c5d26771-1f49-4bbf-902c-bf92e527cadb)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](https://www.microsoft.com/download/details.aspx?familyid=18efea9e-b103-46de-90d9-5e295854cec3)  
(重大)  
[Windows Media Encoder 9 Series x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=ebc1737c-6e78-4244-a1b2-a56d031f16e9)  
(重大)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-054**](http://technet.microsoft.com/security/bulletin/ms08-054)
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-053**](http://technet.microsoft.com/security/bulletin/ms08-053)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 與 Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=ac03f138-eca4-46e1-9782-e811820e547f)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=54ce1080-94cf-4e4f-8e09-a7dbab2757c5)  
(中度)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=93f1451b-5b62-47e5-8f0c-b720b957999a)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](https://www.microsoft.com/download/details.aspx?familyid=c83011cd-90b8-494c-9cad-fa055e101992)  
(中度)  
[Windows Media Encoder 9 Series x64 Edition](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=d8f1b782-136b-443f-b5f2-63aa4d1fd94a)  
(中度)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP1 for Itanium-based Systems 和 Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP1 和適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=14e99f8a-cdd4-40d7-8cfc-73ae6bd6dfad)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="4">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-054**](http://technet.microsoft.com/security/bulletin/ms08-054)
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-053**](http://technet.microsoft.com/security/bulletin/ms08-053)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 和 Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=2f4118fd-1ffb-46da-b922-cd4ca4f9d84e)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=16f3ad21-ed77-4c32-93df-3b650b2b32a5)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=99beebc4-553a-46f8-8245-e3d932306c93)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=334352e7-d41f-494f-866d-f1f1745ffd17)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=aa47d016-f5c9-4586-8876-f1f4f255f54d)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=99beebc4-553a-46f8-8245-e3d932306c93)  
(重大)  
[Windows Media Encoder 9 Series x64 Edition](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=54d1279a-7f26-4727-a39d-5505bcd4fc53)  
(重大)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-054**](http://technet.microsoft.com/security/bulletin/ms08-054)
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-053**](http://technet.microsoft.com/security/bulletin/ms08-053)
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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=72fc6028-6af4-44ec-8d2a-28c53807d6bc)\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=23bd3be5-cc66-46f8-9420-49d65d8afe1d)\*  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=5434ca66-5a6b-4517-92fb-72dea0a172ec)\*  
(中度)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=3906512b-26db-473e-b522-3883ff34a21c)\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=7f1e0f05-6c9d-4ad1-9b19-50ee4fa7bd7e)\*  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=5434ca66-5a6b-4517-92fb-72dea0a172ec)\*  
(中度)  
[Windows Media Encoder 9 Series x64 Edition](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=e30f9427-26d0-4e86-b9b8-bc637c3b5734)\*  
(中度)
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
[適用於 Itanium 型系統的 Windows Server 2008](https://www.microsoft.com/download/details.aspx?familyid=5159bdba-3825-4816-a2be-ab035332b9e2)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
</table>
 
**\*\*Windows Server 2008 Server Core 安裝不受影響。** 如果 Windows Server 2008 是使用 Server Core 安裝選項所安裝，即使受到這些弱點影響的檔案可能會出現在系統上，這項更新解決的弱點並不會影響受支援的 Windows Server 2008 版本。 但是我們仍會將此更新提供給具有受影響之檔案的使用者，因為相較於您系統上目前的檔案，此更新檔案較新 (其版本號碼較高)。 如需這個安裝選項的詳細資訊，請參閱 [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

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
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-055**](http://technet.microsoft.com/security/bulletin/ms08-055)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=ef3de64c-fc17-4500-9da4-a3bba97fda6d)  
(KB953405)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=ef3de64c-fc17-4500-9da4-a3bba97fda6d)  
(KB953405)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 2 和 Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=e9f8e309-d721-4bab-b485-5eede8d49eb8)  
(KB954478)  
(重要)  
[Microsoft Office 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=e9f8e309-d721-4bab-b485-5eede8d49eb8)  
(KB954478)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e670ad22-d3c1-41f7-ba30-6a67139feaa3)  
(KB953404)  
(重要)  
[Microsoft Office 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=e670ad22-d3c1-41f7-ba30-6a67139feaa3)  
(KB953404)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System 和 2007 Microsoft Office System Service Pack 1
</td>
<td style="border:1px solid black;">
[2007 Microsoft Office System](https://www.microsoft.com/download/details.aspx?familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)  
(重要)  
[2007 Microsoft Office System Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)  
(重要)
</td>
<td style="border:1px solid black;">
[2007 Microsoft Office System](https://www.microsoft.com/download/details.aspx?familyid=fb457536-26c5-428b-97e4-1fc13718266e)  
(KB951944)  
(重要)  
[2007 Microsoft Office System Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=fb457536-26c5-428b-97e4-1fc13718266e)  
(KB951944)  
(重要)
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
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-055**](http://technet.microsoft.com/security/bulletin/ms08-055)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Project 2002 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Project 2002 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=ef3de64c-fc17-4500-9da4-a3bba97fda6d)  
(KB953405)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2002 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2002 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=a6d9d3ef-f087-4f61-9ec1-522b7d4b9c48)  
(KB954479)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Word Viewer、Microsoft Word Viewer 2003、Microsoft Word Viewer 2003 Service Pack 3、Microsoft Office Excel Viewer 2003、Microsoft Office Excel Viewer 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word Viewer、Microsoft Word Viewer 2003、Microsoft Word Viewer 2003 Service Pack 3、Microsoft Office Excel Viewer 2003、Microsoft Office Excel Viewer 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=e9f8e309-d721-4bab-b485-5eede8d49eb8)  
(KB954478)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office PowerPoint Viewer 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint Viewer 2003](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=cd503f08-1831-45ff-bdf4-dd918ca40505)  
(KB956500)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel Viewer、Microsoft Office PowerPoint Viewer 2007、Microsoft Office PowerPoint Viewer 2007 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer、Microsoft Office PowerPoint Viewer 2007、Microsoft Office PowerPoint Viewer 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)\*\*\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats 和 Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats 和 Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)\*\*\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Expression Web 和 Microsoft Expression Web 2
</td>
<td style="border:1px solid black;">
[Microsoft Expression Web 和 Microsoft Expression Web 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)\*\*\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Groove 2007 和 Microsoft Office Groove 2007 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Groove 2007 和 Microsoft Office Groove 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)\*\*\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Works
</td>
<td style="border:1px solid black;">
[Microsoft Works 8](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=eb0d224e-a517-40d9-9fc6-2345fa12a841)  
(KB956483)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Digital Image Suite 2006
</td>
<td style="border:1px solid black;">
[Microsoft Digital Image Suite 2006](https://www.microsoft.com/download/details.aspx?familyid=04afd760-8173-4069-9e82-d3bf053d9eae)  
(KB955992)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office OneNote 2007
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office OneNote 2007](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=8ac3576c-7873-4ac6-8bbc-033f6a7bb395)  
(KB950130)  
(重大)  
[Microsoft Office OneNote 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=8ac3576c-7873-4ac6-8bbc-033f6a7bb395)  
(KB950130)  
(重大)
</td>
</tr>
</table>
 
\*適用於此受影響軟體的更新與適用於 Microsoft Office XP Service Pack 3 的更新相同。

\*\*適用於此受影響軟體的更新與適用於 Microsoft Office 2003 Service Pack 2 和 Microsoft Office 2003 Service Pack 3 的更新相同。

\*\*\*適用於此受影響軟體的更新與適用於 2007 Microsoft Office System 和 2007 Microsoft Office System Service Pack 1 的更新相同。

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
Microsoft SQL Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
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
SQL Server 2000 Reporting Services Service Pack 2
</td>
<td style="border:1px solid black;">
GDR 更新：  
不適用  
QFE 更新：  
[SQL Server 2000 Reporting Services Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=5f9e7f78-7439-414b-a9dc-a779b89427db)  
(KB954609)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 Service Pack 2
</td>
<td style="border:1px solid black;">
GDR 更新：  
[SQL Server 2005 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=4603c722-2468-4adb-b945-2ed0458b8f47)  
(KB954606)  
(重大)  
QFE 更新：  
[SQL Server 2005 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=5148b887-f323-4adb-9721-61e1c0cfd213)  
(KB954607)  
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
GDR 更新：  
[SQL Server 2005 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=4603c722-2468-4adb-b945-2ed0458b8f47)  
(KB954606)  
(重大)  
QFE 更新：  
[SQL Server 2005 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=5148b887-f323-4adb-9721-61e1c0cfd213)  
(KB954607)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 系統 Service Pack 2 的 SQL Server 2005
</td>
<td style="border:1px solid black;">
GDR 更新：  
[適用於 Itanium 系統 Service Pack 2 的 SQL Server 2005](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=4603c722-2468-4adb-b945-2ed0458b8f47)  
(KB954606)  
(重大)  
QFE 更新：  
[適用於 Itanium 系統 Service Pack 2 的 SQL Server 2005](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=5148b887-f323-4adb-9721-61e1c0cfd213)  
(KB954607)  
(重大)
</td>
</tr>
</table>
 

#### Microsoft 開發者工具和軟體

 
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
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
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
Microsoft Visual Studio .NET 2002 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2002 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=7848a652-4025-44bb-9c98-37a078b56d01)  
(KB947736)  
(無嚴重性等級)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=9bc1e8f8-6c30-4aa0-90f5-fbb0ad5fd90e)  
(KB947737)  
(無嚴重性等級)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2005 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=a7bf790b-3249-4ee8-9440-fa911ebbc08a)  
(KB947738)  
(無嚴重性等級)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2008
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=a8c80b29-6d00-4949-a005-5d706122919a)  
(KB952241)  
(無嚴重性等級)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Report Viewer 2005 Service Pack 1 Redistributable Package
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2005 Service Pack 1 Redistributable Package](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=82833f27-081d-4b72-83ef-2836360a904d)  
(KB954765)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Report Viewer 2008 Redistributable Package
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2008 Redistributable Package](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=6ae0aa19-3e6c-474c-9d57-05b2347456b1)  
(KB954766)  
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual FoxPro 8.0 Service Pack 1
</td>
<td style="border:1px solid black;">
安裝在 Microsoft Windows 2000 Service Pack 4 上的 [Microsoft Visual FoxPro 8.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=1f4371b9-b8be-4455-94d2-2304ee340543)  
(KB955368)  
(無嚴重性等級)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual FoxPro 9.0 Service Pack 1
</td>
<td style="border:1px solid black;">
安裝在 Microsoft Windows 2000 Service Pack 4 上的 [Microsoft Visual FoxPro 9.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=49b21e30-722d-446e-9020-aceb3870db69)  
(KB955369)  
(無嚴重性等級)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual FoxPro 9.0 Service Pack 2
</td>
<td style="border:1px solid black;">
安裝在 Microsoft Windows 2000 Service Pack 4 上的 [Microsoft Visual FoxPro 9.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=36957f47-9d8b-477d-bd60-5959e5a2eafa)  
(KB955370)  
(無嚴重性等級)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Platform SDK Redistributable： GDI+
</td>
<td style="border:1px solid black;">
[Microsoft Platform SDK Redistributable： GDI+](https://www.microsoft.com/download/details.aspx?familyid=6a63ab9c-df12-4d41-933c-be590feaa05a)  
(無嚴重性等級)
</td>
</tr>
</table>
 

#### Microsoft 安全性軟體

 
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
Microsoft Forefront Security
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
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
Microsoft Forefront Client Security 1.0
</td>
<td style="border:1px solid black;">
安裝在 Microsoft Windows 2000 Service Pack 4 上的 [Microsoft Forefront Client Security 1.0  
](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=1eb1a79f-44ca-499e-90bb-ac51894e9d1e)(KB957177)  
(重要)
</td>
</tr>
</table>
 

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和安全性更新。 如需更多資訊，請參閱 [TechNet 更新管理中心](http://www.microsoft.com/taiwan/technet/updatemanagement/default.mspx) (英文)。 [TechNet Security Center](http://www.microsoft.com/taiwan/technet/security/default.mspx) 提供 Microsoft 產品安全性的其他資訊。 消費者可以造訪[在家上網的安全性](http://www.microsoft.com/taiwan/athome/security/default.mspx)網站，只要按一下 \[最新安全性更新\] 即可在此網站取得此資訊。

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

**注意：**SMS 使用 Microsoft Baseline Security Analyzer 及 Microsoft Office Detection Tool，為安全性公告更新的偵測及部署作業提供相當廣泛的支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](http://msdn.microsoft.com/library/default.asp?url=/library/en-us/snmp/snmp/snmp_functions.asp)。 某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可以用 Elevated Rights Deployment Tool (隨 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/taiwan/smserver/downloads/2003/adminpack.htm) (英文) 和 [SMS 管理功能套件](http://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/adminpack/default.htm) (英文) 提供) 來安裝這些更新。

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

[更新管理安全性指南](http://www.microsoft.com/taiwan/technet/security/topics/patchmanagement.mspx) (英文) 提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](http://support.microsoft.com/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](http://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](http://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 [VeriSign iDefense Labs](http://labs.idefense.com/) 的 Greg MacManus 回報 MS08-052 中描述的問題
-   感謝 Fortinet 公司 [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com/) 的 Bing Liu 回報 MS08-052 中描述的問題
-   感謝 [NGSSoftware](http://www.ngssoftware.com/) 的 Peter Winter-Smith 和 Ivan Fratric，與 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 MS08-052 中描述的問題
-   感謝 [Assurent Secure Technologies 的 Vulnerability Research Team](http://www.assurent.com/) 回報 MS08-052 中描述的問題
-   感謝匿名的研究人員和 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 MS08-052 中描述的問題
-   感謝 Nguyen Minh Duc 和 Le Manh Tung 以及[河內技術大學 ( 越南) Bach Khoa 網際網路資訊安全中心 (BKIS)](http://security.bkis.vn/)，合作回報 MS08-053 中描述的問題
-   感謝 [Insomnia Security](http://www.insomniasec.com/) 的 Brett Moore 回報 MS08-055 中描述的問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可電洽 1-866-PCSAFETY [Microsoft 產品支援服務](http://go.microsoft.com/fwlink/?linkid=21131)以取得技術支援。 與安全性更新有關的支援電話不另外收費。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與安全性更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](http://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2008 年 9 月 10 日)： 公告摘要發行。
-   V2.0 (2008 年 9 月 11 日)： 針對 MS08-052 更新公告摘要，將 Microsoft Office Project 2002 Service Pack 2、所有適用於 Microsoft Office 2003 的 Office Viewer 軟體，以及所有適用於 2007 Microsoft Office System 的 Office Viewer 軟體新增為受影響的軟體。
-   V2.1 (2008 年 9 月 17 日)： 更新公告摘要，將受影響的軟體表中的 Microsoft Office Project 2002 Service Pack 2 變更為 Microsoft Office Project 2002 Service Pack 1。這僅是名稱變更。 二進位檔案或偵測則保持不變。
-   V2.2 (2008 年 11 月 05 日)： 更新公告摘要，針對 MS08-052 公告，將「Microsoft Visio 2003 Viewer、Microsoft Visio 2007 Viewer、Microsoft Visio 2007 Viewer Service Pack 1 為受影響軟體」描述文字加以移除。
-   V3.0 (2008 年 12 月 22 日)： 公告摘要已更新，針對 MS08-052，將 Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats 和 Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats Service Pack 1、Microsoft Expression Web 和 Microsoft Expression Web 2，以及 Microsoft Office Groove 2007 和 Microsoft Office Groove 2007 Service Pack 1 加入為受影響的軟體。

*Built at 2014-04-18T01:50:00Z-07:00*
