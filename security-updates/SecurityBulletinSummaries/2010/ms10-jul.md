---
TOCTitle: 'MS10-JUL'
Title: 2010 年 7 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms10-jul'
ms:contentKeyID: 61237706
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms10-jul(v=Security.10)'
---

2010 年 7 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2010年7月14日 | 更新: 2010年7月26日

**版本:** 1.1

此公告摘要列出 2010 年 7 月份發行之資訊安全公告。

發行 2010 年 7 月份公告之後，此公告摘要將取代原先於 2010 年 7 月 8 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 資訊安全公告預先通知](http://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2010 年 7 月 14 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。 [立即註冊參加 7 月份資訊安全公告網路廣播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032454299&culture=en-us)。 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 資訊安全公告摘要和網路廣播](http://technet.microsoft.com/security/bulletin/summary)。

Microsoft 也會提供資訊協助客戶排定每月資訊安全更新以及任何非安全性、高優先順序更新的優先順序，其中這些非安全性、高優先順序更新的發行日期與每月資訊安全更新的發行日期相同。 請參閱＜其他資訊＞一節。

### 公告資訊

提要
----

<span></span>
下表依嚴重性摘要說明本月份資訊安全公告。

如需受影響的軟體之詳細資料，請參閱下節＜受影響的軟體及下載位置＞。

 
<p> </p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >公告編號</th>
<th style="border:1px solid black;" >公告標題與提要</th>
<th style="border:1px solid black;" >最高的嚴重性等級與弱點影響</th>
<th style="border:1px solid black;" >重新開機需求</th>
<th style="border:1px solid black;" >受影響的軟體</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-042">MS10-042</a></td>
<td style="border:1px solid black;"><strong>說明及支援中心的弱點可能會允許遠端執行程式碼 (2229593)</strong><br />
<br />
此資訊安全更新可解決「Windows 說明及支援中心」功能 (隨附於支援版本的 Windows XP 和 Windows Server 2003) 中一項公開揭露弱點。如果使用者使用網頁瀏覽器檢視蓄意製作的網頁，或按下電子郵件訊息中蓄意製作的連結，此弱點可能會允許遠端執行程式碼。 無法透過電子郵件自動攻擊此弱點。 使用者必須按一下電子郵件訊息中所列的連結，攻擊才可成功進行。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-043">MS10-043</a></td>
<td style="border:1px solid black;"><strong>標準顯示驅動程式中的弱點可能會允許遠端執行程式碼 (2032276)</strong><br />
<br />
此資訊安全更新可解決標準顯示驅動程式 (cdd.dll) 中一項公開揭露的弱點。 雖然該弱點可能會允許執行程式碼，但是由於記憶體係隨機載入，所以成功執行程式碼的機會很低。 在多數案例中，較可能發生的情形是，成功利用此弱點的攻擊者會使受影響的系統停止回應並自動重新開機。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-044">MS10-044</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Access ActiveX 控制項的弱點可能會允許遠端執行程式碼 (982335)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Office Access ActiveX 控制項中兩項未公開報告的弱點。 如果使用者開啟蓄意製作的 Office 檔案，或檢視具現化 Access ActiveX 控制項的網頁，則這些弱點即可能允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-045">MS10-045</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Outlook 中的弱點可能會允許遠端執行程式碼 (978212)</strong><br />
<br />
這個資訊安全更新能解決一項未公開報告的弱點。 如果使用者使用受影響版本的 Microsoft Office Outlook 開啟蓄意製作的電子郵件附件，此弱點可能會允許遠端執行程式碼。 成功利用此弱點的攻擊者可以取得與本機使用者相同的使用者權限。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
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
下表提供本月所述每個弱點的利用性評估。 弱點根據遞減的弱點評估等級及 CVE 編號依序列出。 僅包含資訊安全公告中，嚴重性等級為「重大」或「重要」的弱點。
  
**我該如何使用這個表格？**
  
請用這個表格來瞭解您可能需要安裝的每個資訊安全更新，與 30 天內已發行的可利用程式碼受影響之可能性。 您應該檢閱下列的每個評估，按照特定的設定，將部署以優先次序排序。 如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](http://technet.microsoft.com/en-us/security/cc998259.aspx)。
  
| 公告編號                                                            | 弱點標題                       | CVE ID                                                                           | 弱點索引評估                                                                                            | 主要重點                                   |  
|---------------------------------------------------------------------|--------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|--------------------------------------------|  
| [MS10-045](http://technet.microsoft.com/security/bulletin/ms10-045) | Microsoft Outlook SMB 附件弱點 | [CVE-2010-0266](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0266) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                       |  
| [MS10-044](http://technet.microsoft.com/security/bulletin/ms10-044) | Access ActiveX 控制項弱點      | [CVE-2010-0814](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0814) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                       |  
| [MS10-044](http://technet.microsoft.com/security/bulletin/ms10-044) | ACCWIZ.dll 未初始化的變數弱點  | [CVE-2010-1881](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1881) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                       |  
| [MS10-042](http://technet.microsoft.com/security/bulletin/ms10-042) | 說明中心 URL 驗證弱點          | [CVE-2010-1885](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1885) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | **此弱點目前在網際網路生態系統中遭到利用** |  
| [MS10-043](http://technet.microsoft.com/security/bulletin/ms10-043) | 標準顯示驅動程式整數溢位弱點   | [CVE-2009-3678](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3678) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                       |
  
受影響的軟體及下載位置  
----------------------
  
<span></span>
下表依據主要的軟體類別和嚴重性依序列出公告。
  
**我該如何使用這些表格？**
  
請用這些表格來瞭解可能需要安裝的資訊安全更新有哪些。 您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的資訊安全更新。 若軟體程式或更新出現在清單中，則相關可用軟體更新也會以超連結方式提供，也會列出軟體更新的嚴重性等級。
  
**注意**：一項弱點，可能需要安裝數個資訊安全更新才能妥善解決。 請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
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
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-042**](http://technet.microsoft.com/security/bulletin/ms10-042)
</td>
<td style="border:1px solid black;">
[**MS10-043**](http://technet.microsoft.com/security/bulletin/ms10-043)
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
Windows XP Service Pack 2 及 Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 與 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=7c2122bb-0ecf-4467-a3ba-6fb862f603c5)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9232a336-9ded-4820-bac4-2d68877ee76c)  
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
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-042**](http://technet.microsoft.com/security/bulletin/ms10-042)
</td>
<td style="border:1px solid black;">
[**MS10-043**](http://technet.microsoft.com/security/bulletin/ms10-043)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**輕微**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=cd4363b2-d7a7-4fff-8bcd-6fd02bd1ac07)  
(輕微)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a6bafd3b-c921-466d-bee0-59a3fe126712)  
(輕微)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=b61cc2d5-8432-4681-aa2c-a8807ec1fcf4)  
(輕微)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="3">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-042**](http://technet.microsoft.com/security/bulletin/ms10-042)
</td>
<td style="border:1px solid black;">
[**MS10-043**](http://technet.microsoft.com/security/bulletin/ms10-043)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7
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
適用於 x64 型系統的 Windows 7
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=33ec8c0e-1617-46bf-bd7f-2ce750f89d7f)  
(重大)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-042**](http://technet.microsoft.com/security/bulletin/ms10-042)
</td>
<td style="border:1px solid black;">
[**MS10-043**](http://technet.microsoft.com/security/bulletin/ms10-043)
</td>
</tr>
<tr>
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
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?familyid=2a9998fc-beac-4ccf-aa61-4232106adae1)\*\*\*  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
</table>
 
**Windows Server 2008 R2 注意事項**

**\*\*\*Server Core 安裝不受影響。** 如果 Windows Server 2008 R2 是使用 Server Core 安裝選項所安裝，即使受到此弱點影響的檔案可能會出現在系統上，這項更新解決的弱點並不會影響受支援的 Windows Server 2008 R2 版本。 但是我們仍會將此更新提供給具有受影響之檔案的使用者，因為相較於您系統上目前的檔案，此更新檔案較新 (其版本號碼較高)。 如需此安裝選項的詳細資訊，請參閱 MSDN 文章：[伺服器核心](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英文) 以及[適用於 Windows Server 2008 R2 的伺服器核心](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 及 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

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
[**MS10-044**](http://technet.microsoft.com/security/bulletin/ms10-044)
</td>
<td style="border:1px solid black;">
[**MS10-045**](http://technet.microsoft.com/security/bulletin/ms10-045)
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
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office Outlook 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=daacf400-4aa3-4479-a60f-b8863ba1e16d)  
(KB980371)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Access 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=93768ac6-e6d7-4175-a6e3-666210494678)  
(KB981716)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Office Outlook 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=ef5b0048-96f1-43a6-9848-7f6adccd10b3)  
(KB980373)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System Service Pack 1 和 2007 Microsoft Office System Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Office Access 2007 Service Pack 1 和 Microsoft Office Access 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=af2862e2-da37-4cbe-8974-e517eb666f14)  
(KB979440)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Office Outlook 2007 Service Pack 1 和 Microsoft Office Outlook 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4e2e7c49-6665-4135-adbb-8e831a91d0fe)  
(KB980376)  
(重要)
</td>
</tr>
</table>
 

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和資訊安全更新。 如需更多資訊，請參閱 [TechNet 更新管理中心](http://go.microsoft.com/fwlink/?linkid=69903) (英文)。 [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) 提供 Microsoft 產品安全性的其他資訊。 消費者可以造訪[在家上網的安全性](http://www.microsoft.com/taiwan/protect/default.mspx)網站，只要按一下 \[最新資訊安全更新\] 即可在此網站取得此資訊。

資訊安全更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 以及 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) 取得。 資訊安全更新也可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得。 您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。

最後，您可以從 [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) 下載資訊安全更新。 Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括資訊安全更新、驅動程式和 Service Pack。 只要以資訊安全公告編號 (例如：MS07-036) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。 如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](http://go.microsoft.com/fwlink/?linkid=97900)。

**注意**：自 2009 年 8 月 1 日開始，Microsoft 已停止支援 Office Update 與 Office Update Inventory Tool。 若要繼續取得 Microsoft Office 產品的最新更新，請使用 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)。 如需更多資訊，請參閱[關於 Microsoft Office Update： 常見問題集](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx) (英文)。

**偵測與部署指南**

Microsoft 針對資訊安全更新提供偵測和部署指南。 本指南所含之建議和資訊，能幫助 IT 專業人員瞭解如何使用用於資訊安全更新的偵測和部署的各種工具。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 961747](http://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少資訊安全更新以及一般安全性設定錯誤的狀況。 如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) 網站 (英文)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速而可靠地將 Microsoft Windows 2000 作業系統及更新版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 適用的最新重大更新與資訊安全更新部署到 Microsoft Windows 2000 及更新版本的作業系統中。

如需更多關於利用 Windows Server Update Services 部署資訊安全更新的資訊，請造訪 [Windows Server Update Services](http://www.microsoft.com/taiwan/windowsserversystem/updateservices/evaluation/overview.mspx) 網站。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要資訊安全更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。 現已推出新版的 SMS，System Center Configuration Manager 2007；另請參閱 [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)。如需更多有關系統管理員如何能使用 SMS 2003 部署資訊安全更新的資訊，請參閱 [SMS 2003 安全性修補程式管理](http://go.microsoft.com/fwlink/?linkid=22939) (英文)。 SMS 2.0 使用者也可以使用資訊安全更新盤點工具 (Security Update Inventory Tool，SUIT) 來協助部署資訊安全更新。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158)。

**注意**：SMS 使用 Microsoft Baseline Security Analyzer 提供廣泛的資訊安全公告更新偵測與部署支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些資訊安全更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可使用 Elevated Rights Deployment Tool (隨 [SMS 2.0 Administration Feature Pack (英文)](http://go.microsoft.com/fwlink/?linkid=21161) 提供) 來安裝這些更新。

**Update Compatibility Evaluator 和應用程式相容性工具組**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。 這可能會觸發不相容性，而拉長部署資訊安全更新的時間。 您可以使用 [Application Compatibility Toolkit](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 隨附的 [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 元件，針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Microsoft Windows Vista、Windows Update、Microsoft 資訊安全更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非安全性、高優先順序更新

如需在 Windows Update 和 Microsoft Update 上發行的非資訊安全更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](http://support.microsoft.com/kb/894199)： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。 其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](http://technet.microsoft.com/en-us/wsus/bb456965.aspx)。 顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的安全性保護，Microsoft 將在每月發行資訊安全更新之前，提前向重要安全性軟體提供者提供弱點資訊。 安全性軟體提供者可利用此弱點資訊，透過其安全性軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。 如果要判斷是否有安全性軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://www.microsoft.com/security/msrc/mapp/partners.mspx)上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 安全性策略與社群

**更新程式管理策略**

[更新管理安全性指南](http://go.microsoft.com/fwlink/?linkid=21168) (英文) 提供您有關套用資訊安全更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他資訊安全更新**

其他安全性問題的更新可由下列位置取得：

-   資訊安全更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。
-   客戶平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的資訊安全更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](http://support.microsoft.com/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](http://technet.microsoft.com/zh-tw/security/cc136632.aspx)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](http://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 [Reactive Systems, Inc](http://www.reactive-systems.com/) 的 David Hansel 回報 MS10-043 中描述的問題
-   感謝匿名的研究人員與 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 MS10-044 中描述的問題
-   感謝 [IBM ISS X-Force](http://www.iss.net/) 的 Robert Freeman 回報 MS10-044 中描述的問題
-   感謝 Yorick Koster 及 [SSD/SecuriTeam Secure Disclosure program](http://www.beyondsecurity.com/ssd.html) 合作回報 MS10-045 中描述的問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可洽詢[安全性支援](http://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 以取得技術支援。 與資訊安全更新有關的支援電話不另外收費。 如需更多可用支援選項的資訊，請參閱 [Microsoft 技術支援服務](http://support.microsoft.com/?ln=zh-tw)。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與資訊安全更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](http://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2010 年 7 月 14 日)： 公告摘要發行。
-   V1.1 (2010 年 7 月 26 日)： 移除提及 Windows Embedded Standard 7 的 MS10-043 錯誤內容。

*Built at 2014-04-18T01:50:00Z-07:00*
