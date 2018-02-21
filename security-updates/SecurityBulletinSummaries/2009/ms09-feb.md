---
TOCTitle: 'MS09-FEB'
Title: 2009 年 2 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms09-feb'
ms:contentKeyID: 61237692
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms09-feb(v=Security.10)'
---

2009 年 2 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2009年2月11日

**版本:** 1.0

此公告摘要列出 2009 年 2 月份發行之安全性公告。

發行 2009 年 2 月份公告之後，此公告摘要將取代原先於 2009 年 2 月 5 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](http://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2009 年 2 月 11 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。 立即註冊參加 [2 月份安全性公告網路廣播](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032395122)。 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](http://www.microsoft.com/taiwan/security/bulletins/default.mspx)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性、高優先順序更新的優先順序，其中這些非安全性、高優先順序更新的發行日期與每月安全性更新的發行日期相同。 請參閱＜其他資訊＞一節。

### 公告資訊

提要
----

<span></span>
下表依嚴重性摘要說明本月份安全性公告。

如需受影響的軟體之詳細資料，請參閱下節＜受影響的軟體及下載位置＞。

 
<p> </p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >公告編號</th>
<th style="border:1px solid black;" >公告標題與提要</th>
<th style="border:1px solid black;" >最高的嚴重性等級與安全性影響</th>
<th style="border:1px solid black;" >重新開機需求</th>
<th style="border:1px solid black;" >受影響的軟體</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-002">MS09-002</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 積存安全性更新 (961260)</strong><br />
<br />
這個安全性更新可解決兩項未公開報告的弱點。 如果使用者使用 Internet Explorer 檢視蓄意製作的網頁，這些弱點可能會允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-003">MS09-003</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange 中的弱點可能會允許遠端執行程式碼 (959239)</strong><br />
<br />
這個安全性更新可解決 Microsoft Exchange Server 中兩項未公開報告的弱點。 第一弱點是當蓄意製作的 TNEF 訊息被傳送至 Microsoft Exchange Server 時，可能會允許遠端執行程式碼。 成功利用此弱點的攻擊者可以 Exchange Server 的 服務帳戶權限，取得受影響系統的完整控制權。 第二弱點是當蓄意製作的 MAPI 命令被傳送至 Microsoft Exchange Server 時，可能會導致拒絕服務。 成功利用此弱點的攻擊者可造成使用 EMSMDB32 提供者的 Microsoft Exchange System Attendant 服務及其他服務停止回應。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Exchange Server</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-004">MS09-004</a></td>
<td style="border:1px solid black;"><strong>Microsoft SQL Server 中的弱點可能會允許遠端執行程式碼 (959420)</strong><br />
<br />
這個安全性更新可解決 Microsoft SQL Server 中一項未公開報告的弱點。 如果不信任的使用者存取受影響的系統，或如果受影響的系統發生 SQL 插入式攻擊時，此弱點可能會允許遠端執行程式碼。 安裝 SQL Server 7.0 Service Pack 4、SQL Server 2005 Service Pack 3 和 SQL Server 2008 的系統不受此問題影響。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft SQL Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-005">MS09-005</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Visio 的弱點可能會允許遠端執行程式碼 (957634)</strong><br />
<br />
此安全性更新可解決 Microsoft Office Visio 中三項未公開報告的弱點，該弱點可在使用者開啟蓄意製作的 Visio 檔案時，允許從遠端執行程式碼。 成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>
  
弱點索引  
--------
  
<span></span>
下表提供本月所述每個弱點的利用性評估。 弱點皆根據公告編號和 CVE 編號依序列出。
  
**我該如何使用這個表格？**
  
請用這個表格來瞭解您可能需要安裝的每個安全性更新，與 30 天內已發行的可利用程式碼受影響之可能性。 您應該檢閱下列的每個評估，按照特定的設定，將部署以優先次序排序。 如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](http://technet.microsoft.com/en-us/security/cc998259.aspx)。
  
| 公告編號                                                            | 公告標題                                                       | CVE ID                                                                           | 弱點索引評估                                                                                            | 主要重點           |  
|---------------------------------------------------------------------|----------------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|--------------------|  
| [MS09-002](http://technet.microsoft.com/security/bulletin/ms09-002) | Internet Explorer 積存安全性更新 (961260)                      | [CVE-2009-0075](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0075) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | 左側的等級只是範例 |  
| [MS09-002](http://technet.microsoft.com/security/bulletin/ms09-002) | Internet Explorer 積存安全性更新 (961260)                      | [CVE-2009-0076](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0076) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | 左側的等級只是範例 |  
| [MS09-003](http://technet.microsoft.com/security/bulletin/ms09-003) | Microsoft Exchange 中的弱點可能會允許遠端執行程式碼 (959239)   | [CVE-2009-0098](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0098) |                                                                                                         |                    |  
| [MS09-003](http://technet.microsoft.com/security/bulletin/ms09-003) | Microsoft Exchange 中的弱點可能會允許遠端執行程式碼 (959239)   | [CVE-2009-0099](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0099) |                                                                                                         |                    |  
| [MS09-004](http://technet.microsoft.com/security/bulletin/ms09-004) | Microsoft SQL Server 中的弱點可能會允許遠端執行程式碼 (959420) | [CVE-2008-5416](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-5416) |                                                                                                         |                    |  
| [MS09-005](http://technet.microsoft.com/security/bulletin/ms09-005) | Microsoft Office Visio 的弱點可能會允許遠端執行程式碼 (957634) | [CVE-2009-0095](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0095) |                                                                                                         |                    |  
| [MS09-005](http://technet.microsoft.com/security/bulletin/ms09-005) | Microsoft Office Visio 的弱點可能會允許遠端執行程式碼 (957634) | [CVE-2009-0096](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0096) |                                                                                                         |                    |  
| [MS09-005](http://technet.microsoft.com/security/bulletin/ms09-005) | Microsoft Office Visio 的弱點可能會允許遠端執行程式碼 (957634) | [CVE-2009-0097](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0097) |                                                                                                         |                    |
  
受影響的軟體及下載位置  
----------------------
  
<span></span>
下表依據主要的軟體類別和嚴重性依序列出公告。
  
**我該如何使用這些表格？**
  
請用這些表格來瞭解可能需要安裝的安全性更新有哪些。 您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的安全性更新。 若軟體程式或更新出現在清單中，則相關可用軟體更新也會以超連結方式提供，也會列出軟體更新的嚴重性等級。
  
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
</tr>
<tr>
<th colspan="3">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-002**](http://technet.microsoft.com/security/bulletin/ms09-002)
</td>
<td style="border:1px solid black;">
[**MS09-004**](http://technet.microsoft.com/security/bulletin/ms09-004)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
無
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
不適用
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2000 Desktop Engine (WMSDE)(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=218809d6-a9fb-408b-a34d-ab2ac786994c)  
(KB960082)  
(重要)  
[Microsoft SQL Server 2000 Desktop Engine (WMSDE)(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=218809d6-a9fb-408b-a34d-ab2ac786994c)  
(KB960082)  
(重要)

</td>
</tr>
<tr>
<th colspan="3">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-002**](http://technet.microsoft.com/security/bulletin/ms09-002)
</td>
<td style="border:1px solid black;">
[**MS09-004**](http://technet.microsoft.com/security/bulletin/ms09-004)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 及 Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=8cd902ec-e018-4b61-80f9-825d973f998e)  
(重大)  
[Windows Internet Explorer 7(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=8cd902ec-e018-4b61-80f9-825d973f998e)  
(重大)

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
[Windows Internet Explorer 7(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=dd3e2236-9cc0-478e-a46c-981ef685c0e3)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-002**](http://technet.microsoft.com/security/bulletin/ms09-002)
</td>
<td style="border:1px solid black;">
[**MS09-004**](http://technet.microsoft.com/security/bulletin/ms09-004)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/security/bulletin/rating)
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
[Windows Internet Explorer 7(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=e52aa1fd-e694-4322-b3ff-6abc1b4a16fe)  
(中度)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2000 Desktop Engine (WMSDE)(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=218809d6-a9fb-408b-a34d-ab2ac786994c)  
(KB960082)  
(重要)  
[Windows Internal Database (WYukon) Service Pack 2(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=16925be5-98d0-446b-9bbc-d9a2d335c69e)  
(KB960089)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=edbf1566-b96b-4c7d-98fe-b15f8e766792)  
(中度)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2000 Desktop Engine (WMSDE)(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=218809d6-a9fb-408b-a34d-ab2ac786994c)  
(KB960082)  
(重要)  
[Windows Internal Database (WYukon) x64 Edition Service Pack 2 (中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=05c5c265-cfd7-4364-b323-77650b7f1e67)  
(KB960089)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP1 for Itanium-based Systems 和 Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5ce78797-d1c0-40d4-84e1-1004389833be)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="3">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-002**](http://technet.microsoft.com/security/bulletin/ms09-002)
</td>
<td style="border:1px solid black;">
[**MS09-004**](http://technet.microsoft.com/security/bulletin/ms09-004)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 和 Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=5f9fa4b6-85a4-43bc-b84f-6bd847799650)  
(重大)  
[Windows Internet Explorer 7(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=5f9fa4b6-85a4-43bc-b84f-6bd847799650)  
(重大)

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
[Windows Internet Explorer 7(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=e9a8c94b-b9d2-4d64-855f-b5f02ce3dfb5)  
(重大)  
[Windows Internet Explorer 7(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=e9a8c94b-b9d2-4d64-855f-b5f02ce3dfb5)  
(重大)

</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-002**](http://technet.microsoft.com/security/bulletin/ms09-002)
</td>
<td style="border:1px solid black;">
[**MS09-004**](http://technet.microsoft.com/security/bulletin/ms09-004)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/security/bulletin/rating)
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
[Windows Internet Explorer 7(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=2491dbf2-7cd3-44f1-bfad-77e6f760a25c)\*\*  
(中度)  
[Windows Internet Explorer 7(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=2491dbf2-7cd3-44f1-bfad-77e6f760a25c)\*\*  
(中度)

</td>
<td style="border:1px solid black;">
[Windows Internal Database (WYukon) Service Pack 2(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=16925be5-98d0-446b-9bbc-d9a2d335c69e)\*  
(KB960089)  
(重要)  
[Windows Internal Database (WYukon) Service Pack 2(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=16925be5-98d0-446b-9bbc-d9a2d335c69e)\*  
(KB960089)  
(重要)

</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=794373cc-2dce-4ef5-af50-7804c622c230)\*\*  
(中度)  
[Windows Internet Explorer 7(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=794373cc-2dce-4ef5-af50-7804c622c230)\*\*  
(中度)

</td>
<td style="border:1px solid black;">
[Windows Internal Database (WYukon) x64 Edition Service Pack 2(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=05c5c265-cfd7-4364-b323-77650b7f1e67)\*  
(KB960089)  
(重要)  
[Windows Internal Database (WYukon) x64 Edition Service Pack 2(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=05c5c265-cfd7-4364-b323-77650b7f1e67)\*  
(KB960089)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=11985325-4b33-4077-82cf-6afc7a71c510)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
</table>
 
**Windows Server 2008 注意事項**

**\*Windows Server 2008 Server Core 安裝會受影響。** 對於受支援的 Windows Server 2008 版本，無論 Windows Server 2008 是否使用 Server Core 安裝選項，這個更新均以相同的嚴重性等級套用。 如需這個安裝選項的詳細資訊，請參閱 [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**\*\*Windows Server 2008 Server Core 安裝不受影響。** 如果 Windows Server 2008 是使用 Server Core 安裝選項所安裝，則這項更新解決的弱點並不會影響受支援的 Windows Server 2008 版本。 如需這個安裝選項的詳細資訊，請參閱 [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**MS09-004 的注意事項**

另請參閱＜Microsoft 伺服器軟體＞小節，瞭解更多更新檔案。 本公告涉及 Windows 作業系統和元件與 Microsoft 伺服器軟體。

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
Microsoft Exchange Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-003**](http://technet.microsoft.com/security/bulletin/ms09-003)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange 2000 Server
</td>
<td style="border:1px solid black;">
[已安裝 2004 年 8 月發行之更新彙總套件的 Microsoft Exchange 2000 Server Service Pack 3(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=805dc856-ea60-477d-be40-6ac535a7e7e5)  
(KB959897)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2003
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2003 Service Pack 2(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=1d9f0956-88bd-4e13-a86b-b1c8d4782f71)  
(KB959897)  
(重大) [Microsoft Exchange Server 2003 Service Pack 2(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=1d9f0956-88bd-4e13-a86b-b1c8d4782f71)  
(KB959897)  
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2007 Service Pack 1(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=93cb3f66-ae72-4356-bdbf-35029cff6df1)\*  
(KB959241)  
(重大)  
[Microsoft Exchange Server 2007 Service Pack 1(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=93cb3f66-ae72-4356-bdbf-35029cff6df1)\*  
(KB959241)  
(重大)

</td>
</tr>
</table>
 
**MS09-003 的注意事項**

\* 包括 32 位元和 x64 的版本

 
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
[**MS09-004**](http://technet.microsoft.com/security/bulletin/ms09-004)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
GDR 更新：  
[SQL Server 2000 Service Pack 4(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=d5bb816a-6e1a-47cb-92be-51c565ee184c)  
(KB960082)  
(重要)  
QFE 更新：  
[SQL Server 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=a93f3cfe-18c9-4218-a551-13bf415e418a)  
(KB960083)  
(重要)  
GDR 更新：  
[SQL Server 2000 Service Pack 4(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=d5bb816a-6e1a-47cb-92be-51c565ee184c)  
(KB960082)  
(重要)  
QFE 更新：  
[SQL Server 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=a93f3cfe-18c9-4218-a551-13bf415e418a)  
(KB960083)  
(重要)

</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2000 Itanium Edition Service Pack 4
</td>
<td style="border:1px solid black;">
GDR 更新：  
[SQL Server 2000 Itanium Edition Service Pack 4(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=d5bb816a-6e1a-47cb-92be-51c565ee184c)  
(KB960082)  
(重要)  
QFE 更新：  
[SQL Server 2000 Itanium Edition Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=a93f3cfe-18c9-4218-a551-13bf415e418a)  
(KB960083)  
(重要)  
GDR 更新：  
[SQL Server 2000 Itanium Edition Service Pack 4(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=d5bb816a-6e1a-47cb-92be-51c565ee184c)  
(KB960082)  
(重要)  
QFE 更新：  
[SQL Server 2000 Itanium Edition Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=a93f3cfe-18c9-4218-a551-13bf415e418a)  
(KB960083)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 Service Pack 2
</td>
<td style="border:1px solid black;">
GDR 更新：  
[SQL Server 2005 Service Pack 2(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e)  
(KB960089)  
(重要)  
QFE 更新：  
[SQL Server 2005 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a)  
(KB960090)  
(重要)  
GDR 更新：  
[SQL Server 2005 Service Pack 2(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e)  
(KB960089)  
(重要)  
QFE 更新：  
[SQL Server 2005 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a)  
(KB960090)  
(重要)

</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
GDR 更新：  
[SQL Server 2005 x64 Edition Service Pack 2(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e)  
(KB960089)  
(重要)  
QFE 更新：  
[SQL Server 2005 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a)  
(KB960090)  
(重要)  
GDR 更新：  
[SQL Server 2005 x64 Edition Service Pack 2(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e)  
(KB960089)  
(重要)  
QFE 更新：  
[SQL Server 2005 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a)  
(KB960090)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2
</td>
<td style="border:1px solid black;">
GDR 更新：  
[適用於 Itanium 型系統的 Windows Server 2003 SP2(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e)  
(KB960089)  
(重要)  
QFE 更新：  
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a)  
(KB960090)  
(重要)  
GDR 更新：  
[適用於 Itanium 型系統的 Windows Server 2003 SP2(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e)  
(KB960089)  
(重要)  
QFE 更新：  
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a)  
(KB960090)  
(重要)

</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Service Pack 4
</td>
<td style="border:1px solid black;">
GDR 更新：  
[Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Service Pack 4(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=d5bb816a-6e1a-47cb-92be-51c565ee184c)  
(KB960082)  
(重要)  
QFE 更新：  
[Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=a93f3cfe-18c9-4218-a551-13bf415e418a)  
(KB960083)  
(重要)  
GDR 更新：  
[Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Service Pack 4(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=d5bb816a-6e1a-47cb-92be-51c565ee184c)  
(KB960082)  
(重要)  
QFE 更新：  
[Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=a93f3cfe-18c9-4218-a551-13bf415e418a)  
(KB960083)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 Express Edition Service Pack 2
</td>
<td style="border:1px solid black;">
GDR 更新：  
[SQL Server 2005 Express Edition Service Pack 2(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e)  
(KB960089)  
(重要)  
QFE 更新：  
[SQL Server 2005 Express Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a)  
(KB960090)  
(重要)  
GDR 更新：  
[SQL Server 2005 Express Edition Service Pack 2(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e)  
(KB960089)  
(重要)  
QFE 更新：  
[SQL Server 2005 Express Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a)  
(KB960090)  
(重要)

</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 Express Edition with Advanced Services Service Pack 2
</td>
<td style="border:1px solid black;">
GDR 更新：  
[SQL Server 2005 Express Edition with Advanced Services Service Pack 2(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e)  
(KB960089)  
(重要)  
QFE 更新：  
[SQL Server 2005 Express Edition with Advanced Services Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a)  
(KB960090)  
(重要)  
GDR 更新：  
[SQL Server 2005 Express Edition with Advanced Services Service Pack 2(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e)  
(KB960089)  
(重要)  
QFE 更新：  
[SQL Server 2005 Express Edition with Advanced Services Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a)  
(KB960090)  
(重要)

</td>
</tr>
</table>
 
**MS09-004 的注意事項**

另請參閱＜Microsoft 作業系統與元件＞一節，瞭解更多更新檔案。 本公告涉及 Windows 作業系統和元件與 Microsoft 伺服器軟體。

#### Microsoft Office 套件及軟體

 
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
Microsoft Office Visio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-005**](http://technet.microsoft.com/security/bulletin/ms09-005)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Visio 2002
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2002 Service Pack 2(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=a30cef3f-9eaf-45bd-9a25-4b65302362cb)  
(KB955654)  
(重要)  
[Microsoft Office Visio 2002 Service Pack 2(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=a30cef3f-9eaf-45bd-9a25-4b65302362cb)  
(KB955654)  
(重要)

</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Visio 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2003 Service Pack 3(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=c9cb589e-1a37-485d-8402-7f42bcd7a1a9)  
(KB955655)  
(重要)  
[Microsoft Office Visio 2003 Service Pack 3(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=c9cb589e-1a37-485d-8402-7f42bcd7a1a9)  
(KB955655)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Visio 2007
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2007 Service Pack 1(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=4b711e89-8de2-4f17-8afc-691e0604ff82)  
(KB957831)  
(重要)  
[Microsoft Office Visio 2007 Service Pack 1(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=4b711e89-8de2-4f17-8afc-691e0604ff82)  
(KB957831)  
(重要)

</td>
</tr>
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

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。 現已推出新版的 SMS，System Center Configuration Manager 2007；另請參閱 [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)。如需更多有關系統管理員如何能使用 SMS 2003 部署安全性更新的資訊，請參閱 [SMS 2003 安全性修補程式管理](http://www.microsoft.com/taiwan/smserver/evaluation/capabilities/patch.htm) 。 SMS 2.0 使用者也可以利用 [SMS 軟體更新服務功能套件](http://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/suspack/default.htm)來協助部署安全性更新。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server](http://www.microsoft.com/taiwan/smserver/)。

**注意：**SMS 使用 Microsoft Baseline Security Analyzer 及 Microsoft Office Detection Tool，為安全性公告更新的偵測及部署作業提供相當廣泛的支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可以用 Elevated Rights Deployment Tool (隨 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/taiwan/smserver/downloads/2003/adminpack.htm) 和 [SMS 管理功能套件](http://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/adminpack/default.htm) 提供) 來安裝這些更新。

**Update Compatibility Evaluator 和應用程式相容性工具組**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。 這可能會觸發不相容性，而拉長部署安全性更新的時間。 您可以使用 [Application Compatibility Toolkit 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 隨附的 [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 元件，針對所安裝的應用程式，簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Microsoft Windows Vista、Windows Update、Microsoft 安全性更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非安全性、高優先順序更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](http://support.microsoft.com/kb/894199)： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。 其中也包括所有 Windows 的內容。
-   [適用於 Microsoft 產品 (除了 Microsoft Windows 以外) 的全新、修訂版以及已發行的更新](http://technet.microsoft.com/en-us/wsus/bb466214.aspx)。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的安全性保護，Microsoft 將在每月發行安全性更新之前，提前向重要安全性軟體提供者提供弱點資訊。 安全性軟體提供者可利用此弱點資訊，透過其安全性軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。 如果要判斷是否有安全性軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://www.microsoft.com/taiwan/security/default.mspx/msrc/mapp/partners.mspx)上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 安全性策略與社群

**更新程式管理策略**

[更新管理安全性指南](http://www.microsoft.com/taiwan/technet/security/topics/patchmanagement.mspx)提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](http://support.microsoft.com/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](http://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](http://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 [TippingPoint](http://www.tippingpoint.com/) 和 [Zero Day Initiative](http://www.zerodayinitiative.com/) 回報 MS09-002 中描述的問題
-   感謝 Sam Thomas (<http://eshu.co.uk/>) 與 [TippingPoint](http://www.tippingpoint.com/) 和 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 MS09-002 中描述的問題
-   感謝 [VoIPshield Systems](http://www.voipshield.com) 的 Bogdan Materna 回報 MS09-003 中描述的問題
-   感謝 [SEC Consult Vulnerability Lab](http://www.sec-consult.com/) 的 Bernhard Mueller 回報 MS09-004 中描述的問題
-   感謝 Fortinet 公司 [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com/) 的 Bing Liu 回報 MS09-005 中描述的多個問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可電洽 1-866-PCSAFETY [Microsoft 產品支援服務](http://go.microsoft.com/fwlink/?linkid=21131)以取得技術支援。 與安全性更新有關的支援電話不另外收費。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與安全性更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](http://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2009 年 2 月 11 日)： 公告摘要發行。

*Built at 2014-04-18T01:50:00Z-07:00*
