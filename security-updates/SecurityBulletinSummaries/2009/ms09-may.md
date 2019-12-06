---
TOCTitle: 'MS09-MAY'
Title: 2009 年 5 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms09-may'
ms:contentKeyID: 61237697
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms09-may(v=Security.10)'
---

2009 年 5 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2009年5月12日 | 更新: 2009年6月10日

**版本:** 2.0

此公告摘要列出 2009 年 5 月份發行之安全性公告。

發行 2009 年 5 月份公告之後，此公告摘要將取代原先於 2009 年 5 月 7 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](http://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2009 年 5 月 13 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。 [立即註冊參加 5 月份安全性公告網路廣播](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?culture=en-us&eventid=1032395223)。 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](http://www.microsoft.com/taiwan/security/bulletins/default.mspx)。

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
<th style="border:1px solid black;" >最高的嚴重性等級與弱點影響</th>
<th style="border:1px solid black;" >重新開機需求</th>
<th style="border:1px solid black;" >受影響的軟體</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office PowerPoint 的弱點可能會允許遠端執行程式碼 (957634)</strong><br />
<br />
此安全性更新可解決 Microsoft Office PowerPoint 中一項已公開揭發和幾項未公開報告的弱點，這些弱點可在使用者開啟蓄意製作的 PowerPoint 檔案時，允許從遠端執行程式碼。 成功利用這些弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
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

 
<p> </p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >公告編號</th>
<th style="border:1px solid black;" >公告標題</th>
<th style="border:1px solid black;" >CVE ID</th>
<th style="border:1px solid black;" >弱點索引評估</th>
<th style="border:1px solid black;" >主要重點</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint 的弱點可能會允許遠端執行程式碼 (957634)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0220">CVE-2009-0220</a></td>
<td style="border:1px solid black;">對於未使用 /GS 編譯的 Office 版本：<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">編譯 Office 2003 Service Pack 3 和 Office 較新版本時所建置的 /GS 保護，是這個弱點的一個緩和因素，可將這類系統的風險等級大幅降低為 <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - 不太可能撰寫出可利用此漏洞的程式碼。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint 的弱點可能會允許遠端執行程式碼 (957634)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0221">CVE-2009-0221</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出偶爾可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint 的弱點可能會允許遠端執行程式碼 (957634)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0222">CVE-2009-0222</a></td>
<td style="border:1px solid black;">對於未使用 /GS 編譯的 Office 版本：<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">編譯 Office 2003 Service Pack 3 和 Office 較新版本時所建置的 /GS 保護，是這個弱點的一個緩和因素，可將這類系統的風險等級大幅降低為 <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - 不太可能撰寫出可利用此漏洞的程式碼。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint 的弱點可能會允許遠端執行程式碼 (957634)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0223">CVE-2009-0223</a></td>
<td style="border:1px solid black;">對於未使用 /GS 編譯的 Office 版本：<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">編譯 Office 2003 Service Pack 3 和 Office 較新版本時所建置的 /GS 保護，是這個弱點的一個緩和因素，可將這類系統的風險等級大幅降低為 <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - 不太可能撰寫出可利用此漏洞的程式碼。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint 的弱點可能會允許遠端執行程式碼 (957634)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0224">CVE-2009-0224</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能撰寫出偶爾可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint 的弱點可能會允許遠端執行程式碼 (957634)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0225">CVE-2009-0225</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能撰寫出偶爾可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint 的弱點可能會允許遠端執行程式碼 (957634)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0226">CVE-2009-0226</a></td>
<td style="border:1px solid black;">對於未使用 /GS 編譯的 Office 版本：<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">編譯 Office 2003 Service Pack 3 和 Office 較新版本時所建置的 /GS 保護，是這個弱點的一個緩和因素，可將這類系統的風險等級大幅降低為 <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - 不太可能撰寫出可利用此漏洞的程式碼。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint 的弱點可能會允許遠端執行程式碼 (957634)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0227">CVE-2009-0227</a></td>
<td style="border:1px solid black;">對於未使用 /GS 編譯的 Office 版本：<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">編譯 Office 2003 Service Pack 3 和 Office 較新版本時所建置的 /GS 保護，是這個弱點的一個緩和因素，可將這類系統的風險等級大幅降低為 <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - 不太可能撰寫出可利用此漏洞的程式碼。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint 的弱點可能會允許遠端執行程式碼 (957634)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0556">CVE-2009-0556</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><strong>此弱點目前在網際網路生態系統中遭到利用。</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint 的弱點可能會允許遠端執行程式碼 (957634)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1128">CVE-2009-1128</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint 的弱點可能會允許遠端執行程式碼 (957634)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1129">CVE-2009-1129</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint 的弱點可能會允許遠端執行程式碼 (957634)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1130">CVE-2009-1130</a></td>
<td style="border:1px solid black;">對於未使用 /GS 編譯的 Office 版本：<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">編譯 Office 2003 Service Pack 3 和 Office 較新版本時所建置的 /GS 保護，是這個弱點的一個緩和因素，可將這類系統的風險等級大幅降低為 <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - 不太可能撰寫出可利用此漏洞的程式碼。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint 的弱點可能會允許遠端執行程式碼 (957634)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1131">CVE-2009-1131</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint 的弱點可能會允許遠端執行程式碼 (957634)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1137">CVE-2009-1137</a></td>
<td style="border:1px solid black;">對於未使用 /GS 編譯的 Office 版本：<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">編譯 Office 2003 Service Pack 3 和 Office 較新版本時所建置的 /GS 保護，是這個弱點的一個緩和因素，可將這類系統的風險等級大幅降低為 <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - 不太可能撰寫出可利用此漏洞的程式碼。</td>
</tr>
</tbody>
</table>
  
受影響的軟體及下載位置  
----------------------
  
<span></span>
下表依據主要的軟體類別和嚴重性依序列出公告。
  
**我該如何使用這些表格？**
  
請用這些表格來瞭解可能需要安裝的安全性更新有哪些。 您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的安全性更新。 若軟體程式或更新出現在清單中，則相關可用軟體更新也會以超連結方式提供，也會列出軟體更新的嚴重性等級。
  
**注意**：一項弱點，可能需要安裝數個安全性更新才能妥善解決。 請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
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
Microsoft Office 套件、系統和元件  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-017**](http://technet.microsoft.com/security/bulletin/ms09-017)
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
Microsoft Office 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2000 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=f443312a-ac74-4ebc-a4ac-7a756aa67894)  
(KB957790)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=a24ec7ab-c1c7-4ddb-8b6e-107f1af67f49)  
(KB957781)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=ccfa978b-3340-40db-a45d-c880ba36b106)  
(KB957784)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
2007 Microsoft Office System Service Pack 1 和 2007 Microsoft Office System Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2007 Service Pack 1 和 Microsoft Office PowerPoint 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=11f8380f-ffb6-4c22-a89c-3dc55d0f9834)\*  
(KB957789)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Office for Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-017**](http://technet.microsoft.com/security/bulletin/ms09-017)
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
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=5557bfb7-ebb4-4c42-8042-41e830c4e550)  
(KB969661)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=58326da2-eb75-4b42-b1bc-e70319defb58)  
(KB971822)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=9d6d9eaa-8442-4184-8886-faab2803bde6)  
(KB971824)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
其他 Office 軟體
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-017**](http://technet.microsoft.com/security/bulletin/ms09-017)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
PowerPoint Viewer
</td>
<td style="border:1px solid black;">
[PowerPoint Viewer 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=6a57e6ed-bd24-406f-87bb-117391e083e0)  
(KB969615)  
(重要)  
[PowerPoint Viewer 2007 Service Pack 1 和 PowerPoint Viewer 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=141b8338-5c52-4326-a9e4-d2f2d8940d9c)  
(KB970059)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Word、Excel 及 PowerPoint 2007 檔案格式的 Microsoft Office 相容性套件
</td>
<td style="border:1px solid black;">
[Microsoft Office Word、Excel 及 PowerPoint 2007 檔案格式相容性套件 Service Pack 1 和 Microsoft Office Word、Excel 及 PowerPoint 2007 檔案格式相容性套件 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=e1d3a4c3-538a-4f98-8d60-250803a80e2a)  
(KB969618)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Works 8.5
</td>
<td style="border:1px solid black;">
[Microsoft Works 8.5](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=628280fe-e035-4274-85f2-393d9bad543c)  
(KB967043)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works 9
</td>
<td style="border:1px solid black;">
[Microsoft Works 9](https://www.microsoft.com/download/details.aspx?familyid=f6fa110e-45c6-450f-ae47-c89a06e3f762)  
(KB967044)  
(重要)
</td>
</tr>
</table>
 
**MS09-017 的注意事項**

Microsoft 已重新發行 MS09-017，以提供安全性更新套件給 Microsoft Office 2004 for Mac、Microsoft Office 2008 for Mac、Open XML File Format Converter for Mac、Microsoft Works 8.5 及 Microsoft Works 9。安裝這些軟體的客戶需要立即套用這項更新。

MS09-017 首次發行時，這些安全性更新套件尚未開發完成。 當時 Microsoft 發布 MS09-017，是因為在定期公告發布期內完成了完整的產品系列更新套件，可為大部分承擔風險的客戶解決問題。 目前版本的 MS09-017 現在涵蓋了受到此公告中所討論弱點影響之軟體的完整更新範圍。

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和安全性更新。 如需更多資訊，請參閱 [TechNet 更新管理中心](http://www.microsoft.com/taiwan/technet/updatemanagement/default.mspx) 。 [TechNet Security Center](http://www.microsoft.com/taiwan/technet/security/default.mspx) 提供 Microsoft 產品安全性的其他資訊。 消費者可以造訪[在家上網的安全性](http://www.microsoft.com/taiwan/athome/security/default.mspx)網站，只要按一下 \[最新安全性更新\] 即可在此網站取得此資訊。

安全性更新可以從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)、[Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)及 [Office Update](http://office.microsoft.com/zh-tw/downloads/default.aspx)取得。 安全性更新也可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得。 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。

最後，您可以從 [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) 下載安全性更新。 Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括安全性更新、驅動程式和 Service Pack。 只要以安全性公告編號 (例如：MS07-036) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。 如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](http://go.microsoft.com/fwlink/?linkid=97900)。

**偵測與部署指南**

Microsoft 已提供本月安全性更新之偵測與部署指南。 此指南還能幫助 IT 專業人員瞭解如何使用各項工具來協助部署安全性更新，像是 Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office Detection Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool (加強版安全性更新清查工具，ESUIT)。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 910723](http://support.microsoft.com/kb/910723/zh-tw)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少安全性更新以及一般安全性設定錯誤的狀況。 如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) 網站 (英文)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速可靠地將 Windows 2000 作業系統及更新系統版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 等最新的重大更新與安全性更新部署到 Windows 2000 及更新作業系統版本中。

如需更多關於利用 Windows Server Update Services 部署安全性更新的資訊，請造訪 [Windows Server Update Services](http://www.microsoft.com/taiwan/windowsserversystem/updateservices/evaluation/overview.mspx) 網站。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。 現已推出新版的 SMS，System Center Configuration Manager 2007；另請參閱 [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)。如需更多有關系統管理員如何能使用 SMS 2003 部署安全性更新的資訊，請參閱 [SMS 2003 安全性修補程式管理](http://www.microsoft.com/taiwan/smserver/evaluation/capabilities/patch.htm) (英文)。 SMS 2.0 使用者也可以利用 [SMS 軟體更新服務功能套件](http://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/suspack/default.htm)來協助部署安全性更新。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server](http://www.microsoft.com/taiwan/smserver/)。

**注意：**SMS 使用 Microsoft Baseline Security Analyzer 及 Microsoft Office Detection Tool，為安全性公告更新的偵測及部署作業提供相當廣泛的支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可以用 Elevated Rights Deployment Tool (隨 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/taiwan/smserver/downloads/2003/adminpack.htm) (英文) 和 [SMS 管理功能套件](http://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/adminpack/default.htm) (英文) 提供) 來安裝這些更新。

**Update Compatibility Evaluator 和應用程式相容性工具組**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。 這可能會觸發不相容性，而拉長部署安全性更新的時間。 您可以使用 [Application Compatibility Toolkit 5.0](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 隨附的 [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 元件，針對所安裝的應用程式，簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Microsoft Windows Vista、Windows Update、Microsoft 安全性更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非安全性、高優先順序更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](http://support.microsoft.com/kb/894199/zh-tw)： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。 其中也包括所有 Windows 的內容。
-   [適用於 Microsoft 產品 (除了 Microsoft Windows 以外) 的全新、修訂版以及已發行的更新](http://technet.microsoft.com/en-us/wsus/dd573344.aspx)。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的安全性保護，Microsoft 將在每月發行安全性更新之前，提前向重要安全性軟體提供者提供弱點資訊。 安全性軟體提供者可利用此弱點資訊，透過其安全性軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。 如果要判斷是否有安全性軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://www.microsoft.com/security/msrc/mapp/partners.mspx)上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 安全性策略與社群

**更新程式管理策略**

[更新管理安全性指南](http://www.microsoft.com/taiwan/technet/security/topics/patchmanagement.mspx) (英文) 提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](http://support.microsoft.com/kb/913086/zh-tw)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](http://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](http://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝某匿名的研究人員與[VeriSign iDefense Labs](http://labs.idefense.com/) 合作，回報 MS09-017 中描述的兩個問題
-   感謝 [VeriSign iDefense Labs](http://labs.idefense.com/) 的 Sean Larsson 回報 MS09-017 中描述的兩個問題
-   感謝 [VUPEN Security](http://www.vupen.com/) 的 Nicolas Joly 回報 MS09-017 中描述的問題
-   感謝 [VeriSign iDefense Labs](http://labs.idefense.com/) 的 Marsu Pilami 回報 MS09-017 中描述的幾個問題
-   感謝 [VUPEN Security](http://www.vupen.com/) 的 Nicolas Joly 回報 MS09-017 中描述的問題
-   感謝 Marsu Pilami 與 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 MS09-017 中描述的問題
-   感謝 [team509](http://www.team509.com/) 的 Ling 和 Wushi，與 [TippingPoint](http://www.tippingpoint.com/) 和 [Zero Day Initiative](http://www.zerodayinitiative.com/) 及 [VeriSign iDefense Labs](http://labs.idefense.com/) 的 Sean Larsson 合作，回報 MS09-017 中描述的問題
-   感謝 [Secunia](http://secunia.com/) 的 Carsten H. Eiram 回報 MS09-017 中描述的問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可洽詢[安全性支援](http://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 以取得技術支援。 與安全性更新有關的支援電話不另外收費。 如需更多可用支援選項的資訊，請參閱 [Microsoft 技術支援服務](http://support.microsoft.com/?ln=zh-tw)。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與安全性更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](http://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2009 年 5 月 13 日)： 公告摘要發行。
-   V1.1 (2009 年 5 月 12 日)： 移除 MS09-017 中，與安全性更新 KB969618 和 KB957789 有關的 Microsoft Office PowerPoint 2007 受支援版本的一個錯誤注意事項。
-   V2.0 (2009 年 6 月 10 日)： 修訂以宣佈重新發行 MS09-017。MS09-017 正重新發行，以提供安全性更新套件給 Microsoft Office 2004 for Mac、Microsoft Office 2008 for Mac、Open XML File Format Converter for Mac、Microsoft Works 8.5 及 Microsoft Works 9。目前安裝這些軟體的客戶需要立即套用這項更新。

*Built at 2014-04-18T01:50:00Z-07:00*
