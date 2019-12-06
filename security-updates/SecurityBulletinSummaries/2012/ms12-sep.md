---
TOCTitle: 'MS12-SEP'
Title: 2012 年 9 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms12-sep'
ms:contentKeyID: 61237738
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms12-sep(v=Security.10)'
---

2012 年 9 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2012年9月11日 | 更新: 2012年9月25日

**版本:** 2.0

此公告摘要列出 2012 年 9 月份所發行之資訊安全公告。

發行 2012 年 9 月份資訊安全公告之後，此公告摘要將取代原先於 2012 年 9 月 19 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 資訊安全公告預先通知](https://technet.microsoft.com/zh-tw/security/gg309152.aspx)。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術資訊安全通知](https://technet.microsoft.com/zh-tw/security/dd252948.aspx)。

Microsoft 將利用網路廣播於 2012 年 9 月 12 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。立即註冊參加 9 月份資訊安全公告網路廣播。在這個日期後，此網路廣播將可[隨選取得](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522555&culture=en-us)。

Microsoft 預定於太平洋時間 (美國與加拿大) 2012 年 9 月 21 日 12:00 PM 舉辦一場網路廣播，解答客戶對於此不定期資訊安全公告的問題。[立即註冊參加 9 月份資訊安全公告網路廣播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032529852&culture=en-us)。在這個日期後，此網路廣播將可[隨選取得](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032529852&culture=en-us)。

Microsoft 也會提供資訊協助客戶排定每月資訊安全更新以及任何非資訊安全更新的優先順序，其中這些非資訊安全更新的發行日期與每月資訊安全更新的發行日期相同。請參閱＜其他資訊＞一節。

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
<th style="border:1px solid black;" >最高的嚴重性等級與資訊安全風險影響</th>
<th style="border:1px solid black;" >重新開機需求</th>
<th style="border:1px solid black;" >受影響的軟體</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms12-063">MS12-063</a></td>
<td style="border:1px solid black;">Internet Explorer 積存資訊安全更新 (2744842) <br />
<br />
此資訊安全更新可解決 Internet Explorer 中一項公開揭露的資訊安全風險和四項未公開報告的資訊安全風險。最嚴重的資訊安全風險可能會在使用者以 Internet Explorer 檢視蓄意製作的網頁時，允許遠端執行程式碼。成功利用這類任一資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/rating">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、 <br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms12-061">MS12-061</a></td>
<td style="border:1px solid black;">Visual Studio Team Foundation Server 中的資訊安全風險可能會允許權限提高 (2719584) <br />
<br />
本資訊安全更新可解決 Visual Studio Team Foundation Server 中一項未公開報告的資訊安全風險。如果使用者點選電子郵件中蓄意製作的連結，或瀏覽用來利用此資訊安全風險的網頁，則此資訊安全風險可能會允許權限提高。但是，在所有情況下，攻擊者都無法強迫使用者執行上述動作， 而是引誘使用者自行前往。一般的做法是設法讓使用者點選電子郵件或 Instant Messenger 訊息中連往攻擊者網站的連結。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">不需重新開機</td>
<td style="border:1px solid black;">Microsoft 開發者工具</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms12-062">MS12-062</a></td>
<td style="border:1px solid black;">System Center Configuration Manager 中的資訊安全風險可能會允許權限提高 (2741528) <br />
<br />
本資訊安全更新可解決 Microsoft System Center Configuration Manager 中一項未公開報告的資訊安全風險。如果使用者透過蓄意製作的 URL 造訪受影響的網站，此資訊安全風險可能會允許權限提高。攻擊者並無法強迫使用者造訪這類網站， 而是引誘使用者自行前往。一般的做法是設法讓使用者按一下電子郵件或 Instant Messenger 訊息中連往攻擊者網站的連結。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">不需重新開機</td>
<td style="border:1px solid black;">Microsoft 伺服器軟體</td>
</tr>
</tbody>
</table>
  
資訊安全風險入侵指數  
--------------------
  
<span></span>
下表提供本月所述每個資訊安全風險的利用性評估。資訊安全風險皆根據公告編號和 CVE 編號依序列出。僅包含資訊安全公告中，嚴重性等級為「重大」或「重要」的資訊安全風險。
  
我該如何使用這個表格？
  
您可以運用此表格，針對您可能需要安裝的每一項資訊安全更新，瞭解資訊安全風險在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務 (DoS) 的可能性。請根據您特定的組態設定，檢閱下列各項評估，決定部署本月份更新的優先次序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 資訊安全風險索引](https://technet.microsoft.com/security/cc998259.aspx)。
  
在下方欄位中，「最新軟體版本」意指受影響軟體，「較舊軟體版本」意指受影響軟體所有較舊的支援版本，如公告中的「受影響的軟體」或「不受影響的軟體」表格裡所示。

 
<p> </p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >公告編號</th>
<th style="border:1px solid black;" >資訊安全風險標題</th>
<th style="border:1px solid black;" >CVE ID</th>
<th style="border:1px solid black;" >最新軟體版本的資訊安全風險評估</th>
<th style="border:1px solid black;" >較舊軟體版本的資訊安全風險評估</th>
<th style="border:1px solid black;" >阻斷服務 (DoS) 資訊安全風險評估</th>
<th style="border:1px solid black;" >主要重點</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms12-061">MS12-061</a></td>
<td style="border:1px solid black;">XSS 資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1892">CVE-2012-1892</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms12-062">MS12-062</a></td>
<td style="border:1px solid black;">反映式 XSS 資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2536">CVE-2012-2536</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms12-063">MS12-063</a></td>
<td style="border:1px solid black;">OnMove 釋放後使用資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1529">CVE-2012-1529</a></td>
<td style="border:1px solid black;">不受影響[1]</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">暫時</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms12-063">MS12-063</a></td>
<td style="border:1px solid black;">事件接聽程式釋放後使用資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2546">CVE-2012-2546</a></td>
<td style="border:1px solid black;">不受影響[1]</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">暫時</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms12-063">MS12-063</a></td>
<td style="border:1px solid black;">配置釋放後使用資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2548">CVE-2012-2548</a></td>
<td style="border:1px solid black;">不受影響[1]</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">暫時</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms12-063">MS12-063</a></td>
<td style="border:1px solid black;">cloneNode 釋放後使用資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2557">CVE-2012-2557</a></td>
<td style="border:1px solid black;">不受影響[1]</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">暫時</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms12-063">MS12-063</a></td>
<td style="border:1px solid black;">execCommand 釋放後使用資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4969">CVE-2012-4969</a></td>
<td style="border:1px solid black;">不受影響[1]</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">暫時</td>
<td style="border:1px solid black;">這項資訊安全風險已經遭到公開揭發。<br />
<br />
Microsoft 已發現嘗試利用此資訊安全風險的有限攻擊。</td>
</tr>
</tbody>
</table>
 

<sup>[1]</sup>Internet Explorer 10 不受這個資訊安全風險影響。

受影響的軟體及下載位置
----------------------

<span></span>
下表依據主要的軟體類別和嚴重性依序列出公告。

我該如何使用這些表格？

請用這些表格來瞭解可能需要安裝的資訊安全更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的資訊安全更新。若軟體程式或更新出現在清單中，則相關可用軟體更新也會以超連結方式提供，也會列出軟體更新的嚴重性等級。

注意：一項資訊安全風險，可能需要安裝數個資訊安全更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。

#### Windows 作業系統與元件

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Windows XP
</th>
</tr>
<tr>
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-063](https://technet.microsoft.com/zh-tw/security/bulletin/ms12-063)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[重大](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=967c9ef3-db48-4c2f-9a67-87851fd54962)  
(KB2744842)  
(重大)  
(英文更新連結程式)  
[Internet Explorer 6](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=967c9ef3-db48-4c2f-9a67-87851fd54962)  
(KB2744842)  
(重大)  
(中文更新連結程式)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=6ba78d4c-3657-4963-b2da-7a3763c6b5c9)  
(KB2744842)  
(重大)  
(英文更新連結程式)  
[Internet Explorer 7](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=6ba78d4c-3657-4963-b2da-7a3763c6b5c9)  
(KB2744842)  
(重大)  
(中文更新連結程式)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=ac71ffe3-f077-4753-a238-47a2e9623363)  
(KB2744842)  
(重大)  
(英文更新連結程式)  
[Internet Explorer 8](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=ac71ffe3-f077-4753-a238-47a2e9623363)  
(KB2744842)  
(重大)  
(中文更新連結程式)

</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=020b36c6-7050-4458-8762-bae35eb713cd)  
(KB2744842)  
(重大)  
(英文更新連結程式)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=1e2e412a-be97-407e-9f02-fc074db3bb07)  
(KB2744842)  
(重大)  
(英文更新連結程式)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c727d956-be3e-4cd2-913c-f26cb6c33227)  
(KB2744842)  
(重大)  
(英文更新連結程式)
</td>
</tr>
<tr>
<th colspan="2">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-063](https://technet.microsoft.com/zh-tw/security/bulletin/ms12-063)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
彙總 嚴重性等級
</td>
<td style="border:1px solid black;">
[中度](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=7aaaa15b-87d8-4afc-b183-8ce5becda026)  
(KB2744842)  
(中度)  
(英文更新連結程式)  
[Internet Explorer 6](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=7aaaa15b-87d8-4afc-b183-8ce5becda026)  
(KB2744842)  
(中度)  
(中文更新連結程式)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=aef34ce4-a6ce-4f5e-9892-0a7fbd90c3b4)  
(KB2744842)  
(中度)  
(英文更新連結程式)  
[Internet Explorer 7](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=aef34ce4-a6ce-4f5e-9892-0a7fbd90c3b4)  
(KB2744842)  
(中度)  
(中文更新連結程式)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d63e25ad-ab8c-425f-89cd-29cd2b7b69d6)  
(KB2744842)  
(中度)  
(英文更新連結程式)  
[Internet Explorer 8](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=d63e25ad-ab8c-425f-89cd-29cd2b7b69d6)  
(KB2744842)  
(中度)  
(中文更新連結程式)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=366feacb-16ad-455c-b2ad-5038f998c432)  
(KB2744842)  
(中度)  
(英文更新連結程式)  
[Internet Explorer 6](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=366feacb-16ad-455c-b2ad-5038f998c432)  
(KB2744842)  
(中度)  
(中文更新連結程式)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=baa47c53-2724-43ef-8590-d3733b47e75b)  
(KB2744842)  
(中度)  
(英文更新連結程式)  
[Internet Explorer 7](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=baa47c53-2724-43ef-8590-d3733b47e75b)  
(KB2744842)  
(中度)  
(中文更新連結程式)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=84144e56-f653-4c92-bf49-d44d9ba10489)  
(KB2744842)  
(中度)  
(英文更新連結程式)  
[Internet Explorer 8](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=84144e56-f653-4c92-bf49-d44d9ba10489)  
(KB2744842)  
(中度)  
(中文更新連結程式)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=c28d6dc3-c2f0-4505-a545-85b7a0e3e2dc)  
(KB2744842)  
(中度)  
(英文更新連結程式)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=86c28695-86a5-4c17-82d6-7f98b3162aa6)  
(KB2744842)  
(中度)  
(英文更新連結程式)
</td>
</tr>
<tr>
<th colspan="2">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-063](https://technet.microsoft.com/zh-tw/security/bulletin/ms12-063)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[重大](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=053546fc-ed41-43c2-b4f2-b76334314f5c)  
(KB2744842)  
(重大)  
(英文更新連結程式)  
[Internet Explorer 7](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=053546fc-ed41-43c2-b4f2-b76334314f5c)  
(KB2744842)  
(重大)  
(中文更新連結程式)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=0a5a446d-0a48-4eec-b424-87339b34a3be)  
(KB2744842)  
(重大)  
(英文更新連結程式)  
[Internet Explorer 8](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=0a5a446d-0a48-4eec-b424-87339b34a3be)  
(KB2744842)  
(重大)  
(中文更新連結程式)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=daba1ef1-62db-43db-9d5b-495aa2d3550f)  
(KB2744842)  
(重大)  
(英文更新連結程式)  
[Internet Explorer 9](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=daba1ef1-62db-43db-9d5b-495aa2d3550f)  
(KB2744842)  
(重大)  
(中文更新連結程式)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=cbe5681b-c28e-4a6a-9b97-0bfe44acf077)  
(KB2744842)  
(重大)  
(英文更新連結程式)  
[Internet Explorer 7](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=cbe5681b-c28e-4a6a-9b97-0bfe44acf077)  
(KB2744842)  
(重大)  
(中文更新連結程式)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=5642136e-68f6-42e8-b48e-1549733c6e7d)  
(KB2744842)  
(重大)  
(英文更新連結程式)  
[Internet Explorer 8](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=5642136e-68f6-42e8-b48e-1549733c6e7d)  
(KB2744842)  
(重大)  
(中文更新連結程式)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=aae496ef-fca2-4632-9a8f-2108722d2b28)  
(KB2744842)  
(重大)
  
(英文更新連結程式)  
[Internet Explorer 9](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=aae496ef-fca2-4632-9a8f-2108722d2b28)  
(KB2744842)  
(重大)
  
(中文更新連結程式)

</td>
</tr>
<tr>
<th colspan="2">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-063](https://technet.microsoft.com/zh-tw/security/bulletin/ms12-063)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[中度](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=df861b42-bcf2-4f7a-9019-f49e6725f5dc)  
(KB2744842)  
(中度)  
(英文更新連結程式)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=df861b42-bcf2-4f7a-9019-f49e6725f5dc)  
(KB2744842)  
(中度)
  
(中文更新連結程式)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=1d4f0f25-9539-4c38-babb-4af7f0f4c6cf)  
(KB2744842)  
(中度)
  
(英文更新連結程式)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=1d4f0f25-9539-4c38-babb-4af7f0f4c6cf)  
(KB2744842)  
(中度)
  
(中文更新連結程式)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=0b2965d7-e0b2-4035-a9e4-f6badb389098)  
(KB2744842)  
(中度)
  
(英文更新連結程式)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=0b2965d7-e0b2-4035-a9e4-f6badb389098)  
(KB2744842)  
(中度)
  
(中文更新連結程式)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=fa9878c0-b7e5-43ac-b1eb-679e62cf62fc)  
(KB2744842)  
(中度)  
(英文更新連結程式)  
[Internet Explorer 7](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=fa9878c0-b7e5-43ac-b1eb-679e62cf62fc)  
(KB2744842)  
(中度)
  
(中文更新連結程式)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=10bab7d4-0dd8-4fa7-b26c-715a68553707)  
(KB2744842)  
(中度)
  
(英文更新連結程式)  
[Internet Explorer 8](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=10bab7d4-0dd8-4fa7-b26c-715a68553707)  
(KB2744842)  
(中度)
  
(中文更新連結程式)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=612a94ef-0950-41e8-9875-a8f0e71eba6f)  
(KB2744842)  
(中度)
  
(英文更新連結程式)  
[Internet Explorer 9](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=612a94ef-0950-41e8-9875-a8f0e71eba6f)  
(KB2744842)  
(中度)
  
(中文更新連結程式)

</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=ded887a4-a06d-4447-b19d-19d0f4928523)  
(KB2744842)  
(中度)  
(英文更新連結程式)

</td>
</tr>
<tr>
<th colspan="2">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-063](https://technet.microsoft.com/zh-tw/security/bulletin/ms12-063)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[重大](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=93591461-39ff-4cbd-8df3-88cb80ed6255)  
(KB2744842)  
(重大)  
(英文更新連結程式)  
[Internet Explorer 8](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=93591461-39ff-4cbd-8df3-88cb80ed6255)  
(KB2744842)  
(重大)
  
(中文更新連結程式)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=b303f86a-df17-4961-b677-0c38bd6a86d3)  
(KB2744842)  
(重大)
  
(英文更新連結程式)  
[Internet Explorer 9](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=b303f86a-df17-4961-b677-0c38bd6a86d3)  
(KB2744842)  
(重大)
  
(中文更新連結程式)

</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=93591461-39ff-4cbd-8df3-88cb80ed6255)  
(KB2744842)  
(重大)  
(英文更新連結程式)  
[Internet Explorer 9](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=b303f86a-df17-4961-b677-0c38bd6a86d3)  
(KB2744842)  
(重大)
  
(中文更新連結程式)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=b303f86a-df17-4961-b677-0c38bd6a86d3)  
(KB2744842)  
(重大)
  
(英文更新連結程式)  
[Internet Explorer 9](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=b303f86a-df17-4961-b677-0c38bd6a86d3)  
(KB2744842)  
(重大)
  
(中文更新連結程式)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=e2083388-19a9-4754-9449-1dad2a7f7543)  
(KB2744842)  
(重大)  
(英文更新連結程式)  
[Internet Explorer 8](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=e2083388-19a9-4754-9449-1dad2a7f7543)  
(KB2744842)  
(重大)  
(中文更新連結程式)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=01045ee2-c7c4-4078-969f-905fd7e8774f)  
(KB2744842)  
(重大)  
(英文更新連結程式)  
[Internet Explorer 9](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=01045ee2-c7c4-4078-969f-905fd7e8774f)  
(KB2744842)  
(重大)
  
(中文更新連結程式)

</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=e2083388-19a9-4754-9449-1dad2a7f7543)  
(KB2744842)  
(重大)  
(英文更新連結程式)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=01045ee2-c7c4-4078-969f-905fd7e8774f)  
(KB2744842)  
(重大)
  
(英文更新連結程式)

</td>
</tr>
<tr>
<th colspan="2">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-063](https://technet.microsoft.com/zh-tw/security/bulletin/ms12-063)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[中度](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d46ec8ea-b8c8-42d9-a201-f36eb97b91b8)  
(KB2744842)  
(中度)  
(英文更新連結程式)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=c44a0253-fefc-4ce6-9cfd-396fdea71f8d)  
(KB2744842)  
(中度)
  
(英文更新連結程式)

</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d46ec8ea-b8c8-42d9-a201-f36eb97b91b8)  
(KB2744842)  
(中度)  
(英文更新連結程式)  
[Internet Explorer 8](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=d46ec8ea-b8c8-42d9-a201-f36eb97b91b8)  
(KB2744842)  
(中度)
  
(中文更新連結程式)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=c44a0253-fefc-4ce6-9cfd-396fdea71f8d)  
(KB2744842)  
(中度)
  
(英文更新連結程式)  
[Internet Explorer 9](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=c44a0253-fefc-4ce6-9cfd-396fdea71f8d)  
(KB2744842)  
(中度)
  
(中文更新連結程式)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c132173b-f869-47ec-bb70-6307081473fe)  
(KB2744842)  
(中度)  
(英文更新連結程式)

</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c132173b-f869-47ec-bb70-6307081473fe)  
(KB2744842)  
(中度)  
(英文更新連結程式)

</td>
</tr>
</table>
 

#### Microsoft 開發者工具和軟體

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Visual Studio Team Foundation Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-061](https://technet.microsoft.com/zh-tw/security/bulletin/ms12-061)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio Team Foundation Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio Team Foundation Server 2010 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=721c4a38-b255-4792-83a5-7526a680a79a)<sup>[1]</sup>   
(KB2719584)   
(重要)  
(英文更新連結程式)  
[Microsoft Visual Studio Team Foundation Server 2010 Service Pack 1](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=721c4a38-b255-4792-83a5-7526a680a79a)<sup>[1]</sup>   
(KB2719584)   
(重要)
  
(中文更新連結程式)

</td>
</tr>
</table>
 
MS12-061 注意事項

<sup>[1]</sup>本更新屬於積存性更新，並且取代指定軟體先前的積存性更新。

#### Microsoft 伺服器軟體

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft System Center Configuration Manager
</th>
</tr>
<tr>
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-062](https://technet.microsoft.com/zh-tw/security/bulletin/ms12-062)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Systems Management Server 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Systems Management Server 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=f3a3d8e1-d551-43b4-9d54-9536f30c074d)<sup>[1]</sup>   
(KB2733631)   
(重要)  
(英文更新連結程式)
  
[Microsoft Systems Management Server 2003 Service Pack 3](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=f3a3d8e1-d551-43b4-9d54-9536f30c074d)<sup>[1]</sup>   
(KB2733631)   
(重要)
  
(中文更新連結程式)

</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft System Center Configuration Manager 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft System Center Configuration Manager 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=89890c0e-118b-49ea-9fd1-6d23c674f9e8)<sup>[1]</sup>   
(KB2721642)   
(重要)  
(英文更新連結程式)  
[Microsoft System Center Configuration Manager 2007 Service Pack 2](https://www.microsoft.com/downloads/zh-tw/details.aspx?familyid=89890c0e-118b-49ea-9fd1-6d23c674f9e8)<sup>[1]</sup>   
(KB2721642)   
(重要)
  
(中文更新連結程式)

</td>
</tr>
</table>
 
MS12-062 注意事項

<sup>[1]</sup>這個更新程式僅可以從 Microsoft 下載中心取得。

偵測與部署工具及指南
--------------------

<span></span>
資訊安全中心

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和資訊安全更新。如需更多資訊，請參閱 [TechNet 更新管理中心](https://technet.microsoft.com/zh-tw/updatemanagement/default.aspx) (英文)。TechNet 資訊安全技術中心提供 Microsoft 產品資訊安全的其他資訊。一般消費者可造訪 [Microsoft Safety & Security Center](https://technet.microsoft.com/zh-tw/security/default.aspx) (英文)，並點選 \[Security Updates\] (資訊安全更新) 來取得上述資訊。

資訊安全更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 以及 [Windows Update](https://update.microsoft.com/windowsupdate/v6/default.aspx) 取得。資訊安全更新也可以從 [Microsoft 下載中心](https://www.microsoft.com/zh-tw/download/search.aspx?q=security%20update)取得。您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。

對於 Microsoft Office for Mac 的客戶，Microsoft AutoUpdate for Mac 可協助您保持最新的 Microsoft 軟體。如需使用 Microsoft AutoUpdate for Mac 的詳細資訊，請參閱自動檢查軟體更新 (英文)。

最後，您可以從 [Microsoft Update Catalog](https://catalog.update.microsoft.com/v7/site/) 下載資訊安全更新。Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括資訊安全更新、驅動程式和 Service Pack。只要以資訊安全公告編號 (例如：MS12-001) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](https://catalog.update.microsoft.com/v7/site/faq.aspx)。

偵測與部署指南

Microsoft 針對資訊安全更新提供偵測和部署指南。本指南所含之建議和資訊，能幫助 IT 專業人員瞭解如何使用用於資訊安全更新的偵測和部署的各種工具。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 961747](https://support.microsoft.com/kb/961747?ln=zh-tw)。

Microsoft Baseline Security Analyzer

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少資訊安全更新以及一般資訊安全設定錯誤的狀況。如需更多有關 MBSA 的資訊，請參閱 [Microsoft Baseline Security Analyzer](https://technet.microsoft.com/zh-tw/security/cc184924.aspx) (英文)。

Windows Server Update Services

透過 Windows Server Update Services (WSUS)，系統管理員可迅速而可靠地將 Microsoft Windows 2000 作業系統及更新版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 適用的最新重大更新與資訊安全更新部署到 Microsoft Windows 2000 及更新版本的作業系統中。

如需更多關於利用 Windows Server Update Services 部署資訊安全更新的資訊，請造訪 [Windows Server Update Services](https://technet.microsoft.com/wsus/default) (英文)。

System Center Configuration Manager

System Center Configuration Manager 軟體更新管理可簡化遞送和管理企業中 IT 系統更新的繁複作業。IT 系統管理員可以使用 System Center Configuration Manager 遞送 Microsoft 產品更新給各種裝置，包括桌上型電腦、筆記型電腦、伺服器及行動裝置。

System Center Configuration Manager 中的自動資訊安全風險評估會找出更新需求並報告建議動作。System Center Configuration Manager 中的軟體更新管理是建置在 Microsoft Windows Software Update Services (WSUS) 上，經過時間考驗，為全球 IT 系統管理員所熟悉的更新基礎架構。如需更多有關 System Center Configuration Manager 的資訊，請造訪 [System Center 技術資源](https://technet.microsoft.com/systemcenter/bb980621)。

Systems Management Server 2003

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。透過 SMS，系統管理員能判斷有哪些 Windows 系統需要資訊安全更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。

注意：System Management Server 2003 自 2010 年 1 月 12 日起不受主流支援。如需更多有關產品生命週期的資訊，請造訪 [Microsoft 支援週期](https://support.microsoft.com/common/international.aspx?rdpath=gp;%5bln%5d;lifecycle)。現已推出新版的 SMS，System Center Configuration Manager；請參閱前段的＜System Center Configuration Manager＞一節。

如需更多有關系統管理員如何使用 SMS 2003 來部署資訊安全更新的資訊，請參閱 [Microsoft Systems Management Server 2003 的案例與程序： 軟體發佈和補充程式管理](https://www.microsoft.com/download/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f) (英文)。如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server 技術中心 (TechCenter)](https://technet.microsoft.com/systemcenter/bb545936)。

注意 ：SMS 使用 Microsoft Baseline Security Analyzer 提供廣泛的資訊安全公告更新偵測與部署支援。不過這些工具可能無法偵測部分的軟體更新。在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。如需關於此程序的詳細資訊，請參閱使用 SMS 軟體發佈功能部署軟體更新 (英文)。某些資訊安全更新程式在電腦重新啟動之後，會需要系統管理員的權限。系統管理員可使用 Elevated Rights Deployment Tool (隨附於 [SMS 2003 Administration Feature Pack](https://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d)) 來安裝這些更新。

Update Compatibility Evaluator 和 Application Compatibility Toolkit

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。這可能會觸發不相容性，而拉長部署資訊安全更新的時間。您可以使用 [Application Compatibility Toolkit](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971) 隨附的 [Update Compatibility Evaluator](https://technet.microsoft.com/library/cc749197) 元件，針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Windows Vista、Windows Update、Microsoft 資訊安全更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### MU、WU 及 WSUS 上的非資訊安全更新

如需在 Windows Update 和 Microsoft Update 上發行的非資訊安全更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](https://support.microsoft.com/kb/894199?ln=zh-tw)
-   ： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](https://technet.microsoft.com/wsus/bb456965)
-   。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的資訊安全保護，Microsoft 將在每月發行資訊安全更新之前，提前向重要資訊安全軟體提供者提供資訊安全風險資訊。資訊安全軟體提供者可利用此資訊安全風險資訊，透過其資訊安全軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](https://www.microsoft.com/security/msrc/collaboration/mapp.aspx) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 資訊安全策略與社群

更新程式管理策略

[更新管理資訊安全指南](https://technet.microsoft.com/zh-tw/library/bb466251(zh-tw).aspx) (英文) 提供您有關套用資訊安全更新的 Microsoft 最佳實作建議的其他資訊。

取得其他資訊安全更新

其他資訊安全問題的更新可由下列位置取得：

-   資訊安全更新可以從 [Microsoft 下載中心](https://www.microsoft.com/zh-tw/download/search.aspx?q=security%20update)取得， 您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。
-   消費性平台的更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的資訊安全更新。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](https://support.microsoft.com/kb/913086?ln=zh-tw)。

IT 專業人員資訊安全社群

在 [IT 專業人員資訊安全社群](https://technet.microsoft.com/zh-tw/security/cc136632.aspx)上，學習如何提升資訊安全以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類資訊安全議題的討論。

#### 感謝

Microsoft [感謝](https://technet.microsoft.com/zh-tw/security/gg309157.aspx)下列人士協助我們一同保護我們的客戶：

-   感謝 INR Labs ([Network Intelligence India](https://niiconsulting.com/)) 的 Sunil Yadav 回報 MS12-061 中描述的一項問題
-   感謝 [Stratsec](https://www.stratsec.net/) 的 Andy Yang 回報 MS12-062 中描述的一項問題
-   感謝匿名的研究人員與 [VeriSign iDefense Labs](https://labs.idefense.com/) 合作回報 MS12-063 中描述的一項問題
-   感謝 [Rosario Valotta](https://sites.google.com/site/tentacoloviola) 回報 MS12-063 中描述的一項問題
-   感謝 [Harmony Security](https://www.harmonysecurity.com/) 的 Stephen Fewer 與 [TippingPoint](https://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/) 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作，回報 MS12-063 中描述的一項問題
-   感謝匿名的研究人員與 [TippingPoint](https://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/) 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作，回報 MS12-063 中描述的一項問題
-   感謝匿名的研究人員與 [TippingPoint](https://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/) 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作，回報 MS12-063 中描述的一項問題
-   感謝 [Mitre](https://www.mitre.org/) 協助我們解決 MS12-063 中描述的一項問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 支援週期](https://support.microsoft.com/common/international.aspx?rdpath=gp;%5bln%5d;lifecycle)。
-   IT 專業人員的資訊安全解決方案： [TechNet 資訊安全疑難排解與支援](https://technet.microsoft.com/security/bb980617.aspx)
-   協助保護您的 Windows 電腦免於病毒和惡意軟體攻擊： [病毒解決方案與資訊安全中心](https://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-tw)
-   您所在國家/地區的當地支援： [國際支援](https://support.microsoft.com/common/international.aspx?ln=zh-tw)

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2012 年 9 月 11 日)： 公告摘要發行。
-   V2.0 (2012 年 9 月 25 日)： 新增 Microsoft 資訊安全公告 MS12-063，Internet Explorer 積存資訊安全更新 (2744842)。另外還新增此不定期資訊安全公告的公告網路廣播連結。

*Built at 2014-04-18T01:50:00Z-07:00*
