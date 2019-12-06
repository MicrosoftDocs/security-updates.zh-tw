---
TOCTitle: 'MS13-OCT'
Title: 2013 年 10 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms13-oct'
ms:contentKeyID: 61237749
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms13-oct(v=Security.10)'
---

2013 年 10 月份 Microsoft 資訊安全公告摘要
==========================================

發行: 2013年10月8日 | 更新: 2013年11月28日

**版本:** 1.2

此公告摘要列出 2013 年 10 月份發行之資訊安全公告。

發行 2013 年 10 月份資訊安全公告之後，此公告摘要將取代原先於 2013 年 10 月 3 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 資訊安全公告預先通知](https://technet.microsoft.com/zh-tw/security/gg309152.aspx)。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術資訊安全通知](https://technet.microsoft.com/zh-tw/security/dd252948.aspx)。

Microsoft 將利用網路廣播於 2013 年 10 月 9 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。[立即註冊參加 10 月份資訊安全公告網路廣播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032557381&culture=zh-tw)。

Microsoft 也會提供資訊協助客戶排定每月資訊安全更新以及任何非資訊安全更新的優先順序，其中這些非資訊安全更新的發行日期與每月資訊安全更新的發行日期相同。請參閱**＜其他資訊＞**一節。

### 公告資訊

#### 提要

下表依嚴重性摘要說明本月份資訊安全公告。

如需受影響的軟體之詳細資料，請參閱下節＜受影響的軟體＞。

<p></p> 
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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-080">MS13-080</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer</strong> <strong>積存資訊安全更新</strong> <strong>(2879017)</strong><br />
<br />
此資訊安全更新可解決 Internet Explorer 中一項公開揭露的資訊安全風險和八項未公開報告的資訊安全風險。最嚴重的資訊安全風險可能會在使用者以 Internet Explorer 檢視蓄意製作的網頁時，允許遠端執行程式碼。成功利用其中最嚴重的資訊安全風險的攻擊者，可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/rating">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-081">MS13-081</a></td>
<td style="border:1px solid black;"><strong>Windows</strong> <strong>核心模式驅動程式中的資訊安全風險可能會允許遠端執行程式碼</strong> <strong>(2870008)</strong><br />
<br />
這個資訊安全更新可解決 Microsoft Windows 中七項未公開報告的資訊安全風險。如果使用者檢視內嵌 OpenType 或 TrueType 字型檔案的共用內容，則其中最嚴重的資訊安全風險可能會允許遠端執行程式碼。成功利用這類資訊安全風險的攻擊者可以取得受影響系統的完整控制權。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/rating">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-082">MS13-082</a></td>
<td style="border:1px solid black;"><strong>.NET Framework</strong> <strong>中的資訊安全風險可能會允許遠端執行程式碼</strong> <strong>(2878890)</strong><br />
<br />
這個資訊安全更新可解決 Microsoft .NET Framework 中兩項未公開報告的資訊安全風險，以及一項公開揭露的資訊安全風險。如果使用者使用能具現化 XBAP 應用程式的瀏覽器來造訪包含蓄意製作之 OpenType 字型 (OTF) 檔案的網站，這些資訊安全風險最嚴重可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/rating">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-083">MS13-083</a></td>
<td style="border:1px solid black;"><strong>Windows</strong> <strong>通用控制項程式庫中的資訊安全風險可能會允許遠端執行程式碼</strong> <strong>(2864058)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果攻擊者將蓄意製作的 Web 要求傳送至受影響系統上執行的 ASP.NET Web 應用程式，此資訊安全風險可能會允許遠端執行程式碼。攻擊者可以利用此資訊安全風險，不經驗證就執行任意程式碼。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/rating">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-084">MS13-084</a></td>
<td style="border:1px solid black;"><strong>Microsoft SharePoint Server</strong> <strong>中的資訊安全風險可能會允許遠端執行程式碼</strong> <strong>(2885089)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Office Server 軟體中兩項未公開報告的資訊安全風險。如果使用者在受影響的 Microsoft SharePoint Server、Microsoft Office Services 或 Web Apps 版本中開啟蓄意製作的 Office 檔案，最嚴重的資訊安全風險可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft 伺服器軟體</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-085">MS13-085</a></td>
<td style="border:1px solid black;"><strong>Microsoft Excel</strong> <strong>中的資訊安全風險可能會允許遠端執行程式碼</strong> <strong>(2885080)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Office 中兩項未公開報告的資訊安全風險。如果使用者以受影響版本的 Microsoft Excel 或其他受影響的 Microsoft Office 軟體，開啟蓄意製作的 Office 檔案時，此資訊安全風險可能會允許遠端執行程式碼。成功利用此資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-086">MS13-086</a></td>
<td style="border:1px solid black;"><strong>Microsoft Word</strong> <strong>中的資訊安全風險可能會允許遠端執行程式碼</strong> <strong>(2885084)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Office 中兩項未公開報告的資訊安全風險。如果在受影響的 Microsoft Word 版本和其他受影響的 Microsoft Office 軟體中開啟蓄意製作的檔案，這些資訊安全風險可能會允許遠端執行程式碼。成功利用此資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-087">MS13-087</a></td>
<td style="border:1px solid black;"><strong>Silverlight</strong> <strong>中的資訊安全風險可能會允許資訊洩漏</strong> <strong>(2890788)</strong><br />
<br />
這個資訊安全更新可解決 Microsoft Silverlight 中一項未公開報告的資訊安全風險。如果攻擊者架設一個網站，並在其中包含蓄意製作的 Silverlight 應用程式來利用此資訊安全風險，然後引誘使用者檢視此網站，則此資訊安全風險便可能允許資訊洩漏。攻擊者也可能利用受侵害的網站，以及接受或裝載使用者提供內容或廣告的網站。這類網站可能含有蓄意製作並可利用此資訊安全風險的內容。但是，在所有情況下，攻擊者都無法強迫使用者造訪網站， 而一般的做法是讓使用者點選電子郵件訊息或 Instant Messenger 訊息中連往攻擊者網站的連結，以引誘使用者造訪網站。攻擊者也可能使用橫幅廣告或其他方式來顯示蓄意製作的網頁內容，以便將內容傳遞到受影響的系統。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
資訊洩漏</td>
<td style="border:1px solid black;">不需要重新開機</td>
<td style="border:1px solid black;">Microsoft Silverlight</td>
</tr>
</tbody>
</table>
  
資訊安全風險入侵指數  
--------------------
  

下表提供本月所述每個資訊安全風險的利用性評估。資訊安全風險皆根據公告編號和 CVE 編號依序列出。僅包含資訊安全公告中，嚴重性等級為「重大」或「重要」的資訊安全風險。
  
**我該如何使用這個表格？**
  
您可以運用此表格，針對您可能需要安裝的每一項資訊安全更新，瞭解資訊安全風險在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務 (DoS) 的可能性。請根據您特定的組態設定，檢閱下列各項評估，決定部署本月份更新的優先次序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 資訊安全風險索引](https://technet.microsoft.com/security/cc998259)。
  
在下方欄位中，「最新軟體版本」意指受影響軟體，「較舊軟體版本」意指受影響軟體所有較舊的支援版本，如公告中的「受影響的軟體」或「不受影響的軟體」表格裡所示。

<p></p> 
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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-080">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3872">CVE-2013-3872</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-080">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3873">CVE-2013-3873</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-080">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3874">CVE-2013-3874</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-080">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3875">CVE-2013-3875</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-080">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3882">CVE-2013-3882</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-080">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3885">CVE-2013-3885</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-080">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3886">CVE-2013-3886</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-080">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3893">CVE-2013-3893</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這項資訊安全風險已經公開揭露。<br />
<br />
Microsoft 已發現嘗試透過 Internet Explorer 8 和 Internet Explorer 9 利用此資訊安全風險的目標式攻擊。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-080">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3897">CVE-2013-3897</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">Microsoft 已發現嘗試透過 Internet Explorer 8 利用此資訊安全風險的目標式攻擊。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-081">MS13-081</a></td>
<td style="border:1px solid black;">OpenType 字型剖析資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3128">CVE-2013-3128</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">此資訊安全風險也會影響 <a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-082">MS13-082</a><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-067">https://go.microsoft.com/fwlink/?LinkId=293350</a>。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-081">MS13-081</a></td>
<td style="border:1px solid black;">Windows USB 描述元資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3200">CVE-2013-3200</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-081">MS13-081</a></td>
<td style="border:1px solid black;">Win32k 釋放後使用資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3879">CVE-2013-3879</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-081">MS13-081</a></td>
<td style="border:1px solid black;">應用程式容器權限提高資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3880">CVE-2013-3880</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">暫時</td>
<td style="border:1px solid black;">這是一個可能會導致權限提高的資訊洩漏資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-081">MS13-081</a></td>
<td style="border:1px solid black;">Win32k NULL 分頁資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3881">CVE-2013-3881</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-081">MS13-081</a></td>
<td style="border:1px solid black;">DirectX 圖形核心子系統重覆擷取資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3888">CVE-2013-3888</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-081">MS13-081</a></td>
<td style="border:1px solid black;">TrueType 字型 CMAP表格資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3894">CVE-2013-3894</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-082">MS13-082</a></td>
<td style="border:1px solid black;">OpenType 字型剖析資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3128">CVE-2013-3128</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">此資訊安全風險也會影響 <a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-081">MS13-081</a><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-067">https://go.microsoft.com/fwlink/?LinkId=293350</a>。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-082">MS13-082</a></td>
<td style="border:1px solid black;">實體擴充資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3860">CVE-2013-3860</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">這是一項阻斷服務 (DoS) 的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-082">MS13-082</a></td>
<td style="border:1px solid black;">JSON 剖析資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3861">CVE-2013-3861</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">這是一項阻斷服務 (DoS) 的資訊安全風險。<br />
<br />
這項資訊安全風險已經公開揭露。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-083">MS13-083</a></td>
<td style="border:1px solid black;">Comctl32 整數溢位資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3195">CVE-2013-3195</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-084">MS13-084</a></td>
<td style="border:1px solid black;">Microsoft Excel 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3889">CVE-2013-3889</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">此資訊安全風險也會影響 <a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-085">MS13-085</a><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-067">https://go.microsoft.com/fwlink/?LinkId=293350</a>。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-084">MS13-084</a></td>
<td style="border:1px solid black;">參數插入資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3895">CVE-2013-3895</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-085">MS13-085</a></td>
<td style="border:1px solid black;">Microsoft Excel 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3889">CVE-2013-3889</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">此資訊安全風險也會影響 <a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-084">MS13-084</a><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-067">https://go.microsoft.com/fwlink/?LinkId=293350</a>。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-085">MS13-085</a></td>
<td style="border:1px solid black;">Microsoft Excel 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3890">CVE-2013-3890</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-086">MS13-086</a></td>
<td style="border:1px solid black;">記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3891">CVE-2013-3891</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-086">MS13-086</a></td>
<td style="border:1px solid black;">記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3892">CVE-2013-3892</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-087">MS13-087</a></td>
<td style="border:1px solid black;">Silverlight 資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3896">CVE-2013-3896</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個可能會導致資訊安全功能略過的資訊洩漏資訊安全風險。</td>
</tr>
</tbody>
</table>
  
受影響的軟體  
------------
  

下表依據主要的軟體類別和嚴重性依序列出公告。
  
**我該如何使用這些表格？**
  
請用這些表格來瞭解可能需要安裝的資訊安全更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的資訊安全更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。
  
**注意**：一項資訊安全風險，可能需要安裝數個資訊安全更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
#### Windows 作業系統與元件

<p></p>
<table style="border:1px solid black;">
<tr>
<th colspan="5">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-080**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-083)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2879017)  
(重大)  
Internet Explorer 7   
(2879017)  
(重大)  
Internet Explorer 8   
(2879017)  
(重大)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2847311)  
(重大)  
Windows XP Service Pack 3  
(2862330)  
(重要)  
Windows XP Service Pack 3  
(2862335)  
(重要)  
Windows XP Service Pack 3  
(2868038)  
(重要)  
Windows XP Service Pack 3  
(2883150)  
(重大)  
Windows XP Service Pack 3  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863239)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861189)  
(重大)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)  
Microsoft .NET Framework 4  
(2861188)  
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
Internet Explorer 6   
(2879017)  
(重大)  
Internet Explorer 7   
(2879017)  
(重大)  
Internet Explorer 8   
(2879017)  
(重大)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2847311)  
(重大)  
Windows XP Professional x64 Edition Service Pack 2  
(2862330)  
(重要)  
Windows XP Professional x64 Edition Service Pack 2  
(2862335)  
(重要)  
Windows XP Professional x64 Edition Service Pack 2  
(2868038)  
(重要)  
Windows XP Professional x64 Edition Service Pack 2  
(2883150)  
(重大)  
Windows XP Professional x64 Edition Service Pack 2  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863239)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861189)  
(重大)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)  
Microsoft .NET Framework 4  
(2861188)  
(重大)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2864058)  
(重大)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-080**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-083)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2879017)  
(中度)  
Internet Explorer 7  
(2879017)  
(中度)  
Internet Explorer 8  
(2879017)  
(中度)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2847311)  
(重大)  
Windows Server 2003 Service Pack 2  
(2862330)  
(重要)  
Windows Server 2003 Service Pack 2  
(2862335)  
(重要)  
Windows Server 2003 Service Pack 2  
(2868038)  
(重要)  
Windows Server 2003 Service Pack 2  
(2883150)  
(重大)  
Windows Server 2003 Service Pack 2  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863239)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861189)  
(重大)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)  
Microsoft .NET Framework 4  
(2861188)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2864058)  
(無嚴重性等級)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2879017)  
(中度)  
Internet Explorer 7  
(2879017)  
(中度)  
Internet Explorer 8  
(2879017)  
(中度)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2847311)  
(重大)  
Windows Server 2003 x64 Edition Service Pack 2  
(2862330)  
(重要)  
Windows Server 2003 x64 Edition Service Pack 2  
(2862335)  
(重要)  
Windows Server 2003 x64 Edition Service Pack 2  
(2868038)  
(重要)  
Windows Server 2003 x64 Edition Service Pack 2  
(2883150)  
(重大)  
Windows Server 2003 x64 Edition Service Pack 2  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863239)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861189)  
(重大)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)  
Microsoft .NET Framework 4  
(2861188)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2864058)  
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2879017)  
(中度)  
Internet Explorer 7  
(2879017)  
(中度)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(2847311)  
(重大)  
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(2862330)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(2862335)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(2868038)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(2883150)  
(重大)  
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863239)  
(重要)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(2864058)  
(重大)
</td>
</tr>
<tr>
<th colspan="5">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-080**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-083)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(重大)  
Internet Explorer 8  
(2879017)  
(重大)  
Internet Explorer 9   
(2879017)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2847311)  
(重大)  
Windows Vista Service Pack 2  
(2855844)  
(重大)  
Windows Vista Service Pack 2  
(2862330)  
(重要)  
Windows Vista Service Pack 2  
(2862335)  
(重要)  
Windows Vista Service Pack 2  
(2864202)  
(重要)  
Windows Vista Service Pack 2  
(2868038)  
(重要)  
Windows Vista Service Pack 2  
(2876284)  
(重要)  
Windows Vista Service Pack 2  
(2883150)  
(重大)  
Windows Vista Service Pack 2  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863253)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861190)  
(重大)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)  
Microsoft .NET Framework 4  
(2861188)  
(重大)  
Microsoft .NET Framework 4.5  
(2861193)  
(重大)  
Microsoft .NET Framework 4.5  
(2861208)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2864058)  
(無嚴重性等級)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(重大)  
Internet Explorer 8  
(2879017)  
(重大)  
Internet Explorer 9   
(2879017)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2847311)  
(重大)  
Windows Vista x64 Edition Service Pack 2  
(2855844)  
(重大)  
Windows Vista x64 Edition Service Pack 2  
(2862330)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(2862335)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(2864202)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(2868038)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(2876284)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(2883150)  
(重大)  
Windows Vista x64 Edition Service Pack 2  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863253)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861190)  
(重大)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)  
Microsoft .NET Framework 4  
(2861188)  
(重大)  
Microsoft .NET Framework 4.5  
(2861193)  
(重大)  
Microsoft .NET Framework 4.5  
(2861208)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2864058)  
(重大)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-080**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-083)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(中度)  
Internet Explorer 8  
(2879017)  
(中度)  
Internet Explorer 9   
(2879017)  
(中度)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2847311)  
(重大)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2855844)  
(重大)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2862330)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2862335)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2864202)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2868038)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2876284)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2883150)  
(重大)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863253)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861190)  
(重大)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)  
Microsoft .NET Framework 4  
(2861188)  
(重大)  
Microsoft .NET Framework 4.5  
(2861193)  
(重大)  
Microsoft .NET Framework 4.5  
(2861208)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2864058)  
(無嚴重性等級)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(中度)  
Internet Explorer 8  
(2879017)  
(中度)  
Internet Explorer 9   
(2879017)  
(中度)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2847311)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2855844)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2862330)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2862335)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2864202)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2868038)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2876284)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2883150)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863253)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861190)  
(重大)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)  
Microsoft .NET Framework 4  
(2861188)  
(重大)  
Microsoft .NET Framework 4.5  
(2861193)  
(重大)  
Microsoft .NET Framework 4.5  
(2861208)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2864058)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(中度)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2847311)  
(重大)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2862330)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2862335)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2864202)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2868038)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2876284)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2883150)  
(重大)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863253)  
(重要)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2864058)  
(重大)
</td>
</tr>
<tr>
<th colspan="5">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-080**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-083)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
(重大)  
Internet Explorer 9   
(2879017)  
(重大)  
Internet Explorer 10   
(2879017)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2847311)  
(重大)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2855844)  
(重大)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2862330)  
(重要)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2862335)  
(重要)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2864202)  
(重要)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2868038)  
(重要)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2876284)  
(重要)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2883150)  
(重大)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861191)  
(重大)  
Microsoft .NET Framework 3.5.1  
(2861698)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)  
Microsoft .NET Framework 4.5  
(2861208)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2864058)  
(無嚴重性等級)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
(重大)  
Internet Explorer 9   
(2879017)  
(重大)  
Internet Explorer 10   
(2879017)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2847311)  
(重大)  
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2855844)  
(重大)  
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2862330)  
(重要)  
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2862335)  
(重要)  
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2864202)  
(重要)  
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2868038)  
(重要)  
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2876284)  
(重要)  
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2883150)  
(重大)  
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861191)  
(重大)  
Microsoft .NET Framework 3.5.1  
(2861698)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)  
Microsoft .NET Framework 4.5  
(2861208)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2864058)  
(重大)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-080**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-083)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
(中度)  
Internet Explorer 9   
(2879017)  
(中度)  
Internet Explorer 10   
(2879017)  
(中度)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2847311)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2855844)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2862330)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2862335)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2864202)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2868038)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2876284)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2883150)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861191)  
(重大)  
Microsoft .NET Framework 3.5.1  
(2861698)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)  
Microsoft .NET Framework 4.5  
(2861208)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2864058)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
(中度)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2847311)  
(重大)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2855844)  
(重大)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2862330)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2862335)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2864202)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2868038)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2876284)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2883150)  
(重大)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861698)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2864058)  
(重大)
</td>
</tr>
<tr>
<th colspan="5">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-080**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-083)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2879017)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8  
(2847311)  
(重大)  
適用於 32 位元系統的 Windows 8  
(2862330)  
(重要)  
適用於 32 位元系統的 Windows 8  
(2862335)  
(重要)  
適用於 32 位元系統的 Windows 8  
(2863725)  
(重要)  
適用於 32 位元系統的 Windows 8  
(2864202)  
(重要)  
適用於 32 位元系統的 Windows 8  
(2868038)  
(重要)  
適用於 32 位元系統的 Windows 8  
(2883150)  
(重大)  
適用於 32 位元系統的 Windows 8  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
(重大)  
Microsoft .NET Framework 3.5  
(2861704)  
(重要)  
Microsoft .NET Framework 3.5  
(2863243)  
(重要)  
Microsoft .NET Framework 4.5  
(2861702)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8  
(2864058)  
(無嚴重性等級)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 8
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2879017)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 8  
(2847311)  
(重大)  
適用於 64 位元系統的 Windows 8  
(2862330)  
(重要)  
適用於 64 位元系統的 Windows 8  
(2862335)  
(重要)  
適用於 64 位元系統的 Windows 8  
(2863725)  
(重要)  
適用於 64 位元系統的 Windows 8  
(2864202)  
(重要)  
適用於 64 位元系統的 Windows 8  
(2868038)  
(重要)  
適用於 64 位元系統的 Windows 8  
(2883150)  
(重大)  
適用於 64 位元系統的 Windows 8  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
(重大)  
Microsoft .NET Framework 3.5  
(2861704)  
(重要)  
Microsoft .NET Framework 3.5  
(2863243)  
(重要)  
Microsoft .NET Framework 4.5  
(2861702)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 8  
(2864058)  
(重大)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-080**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-083)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2879017)  
(中度)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2847311)  
(重大)  
Windows Server 2012  
(2862330)  
(重要)  
Windows Server 2012  
(2862335)  
(重要)  
Windows Server 2012  
(2863725)  
(重要)  
Windows Server 2012  
(2864202)  
(重要)  
Windows Server 2012  
(2868038)  
(重要)  
Windows Server 2012  
(2883150)  
(重大)  
Windows Server 2012  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
(重大)  
Microsoft .NET Framework 3.5  
(2861704)  
(重要)  
Microsoft .NET Framework 3.5  
(2863243)  
(重要)  
Microsoft .NET Framework 4.5  
(2861702)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2864058)  
(重大)
</td>
</tr>
<tr>
<th colspan="5">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-080**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-083)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2879017)  
(重大)
</td>
<td style="border:1px solid black;">
Windows RT  
(2847311)  
(重大)  
Windows RT  
(2862330)  
(重要)  
Windows RT  
(2862335)  
(重要)  
Windows RT  
(2863725)  
(重要)  
Windows RT  
(2864202)  
(重要)  
Windows RT  
(2868038)  
(重要)  
Windows RT  
(2883150)  
(重大)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5  
(2861702)  
(重要)
</td>
<td style="border:1px solid black;">
Windows RT  
(2864058)  
(無嚴重性等級)
</td>
</tr>
<tr>
<th colspan="5">
Windows 8.1
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-080**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-083)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
**無**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>   
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 8.1
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>   
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2012 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-080**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-083)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
**無**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>   
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="5">
Windows RT 8.1
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-080**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-083)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
**無**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT 8.1
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>   
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="5">
Server Core 安裝選項
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-080**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-083)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2847311)  
(重大)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2862330)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2862335)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2864202)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2876284)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2883150)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2864058)  
(無嚴重性等級)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2847311)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2862330)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2862335)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2864202)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2876284)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2883150)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2864058)  
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(2847311)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(2862330)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(2862335)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(2864202)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(2876284)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(2883150)  
(重大)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861698)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)  
Microsoft .NET Framework 4.5  
(2861208)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(2864058)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(2847311)  
(重大)  
Windows Server 2012 (Server Core 安裝)  
(2862330)  
(重要)  
Windows Server 2012 (Server Core 安裝)  
(2862335)  
(重要)  
Windows Server 2012 (Server Core 安裝)  
(2863725)  
(重要)  
Windows Server 2012 (Server Core 安裝)  
(2864202)  
(重要)  
Windows Server 2012 (Server Core 安裝)  
(2883150)  
(重大)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
(重大)  
Microsoft .NET Framework 3.5  
(2861704)  
(重要)  
Microsoft .NET Framework 3.5  
(2863243)  
(重要)  
Microsoft .NET Framework 4.5  
(2861702)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(2864058)  
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
</table>
 
**MS13-080** **注意事項**

<sup>[1]</sup>對於 Internet Explorer 11，客戶必須套用 Windows RT 8.1、Windows 8.1 和 Windows Server 2012 R2 更新彙總套件： 2013 年 10 月 (2883200)。請注意，2883200 更新彙總套件包含資訊安全和非資訊安全變更。如需更多資訊及可用的下載連結，請參閱 [Microsoft 知識庫文件編號 2883200](https://support.microsoft.com/kb/2883200?ln=zh-tw)。

#### Microsoft Office 套件及軟體

<p></p> 
<table style="border:1px solid black;">
<tr>
<th colspan="3">
Microsoft Office 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-085**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-085)
</td>
<td style="border:1px solid black;">
[**MS13-086**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-086)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
Microsoft Word 2003 Service Pack 3  
(2826020)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office 2007
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-085**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-085)
</td>
<td style="border:1px solid black;">
[**MS13-086**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-086)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 Service Pack 3  
(2827324)  
(重要)  
Microsoft Office 2007 Service Pack 3  
(2760585)  
(重要)  
Microsoft Office 2007 Service Pack 3  
(2760591)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Word 2007 Service Pack 3  
(2827330)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-085**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-085)
</td>
<td style="border:1px solid black;">
[**MS13-086**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-086)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32 位元版本)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 1 (32 位元版本)  
(2826033)  
(重要)  
Microsoft Office 2010 Service Pack 1 (32 位元版本)  
(2826023)  
(重要)  
Microsoft Office 2010 Service Pack 1 (32 位元版本)  
(2826035)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64 位元版本)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 1 (64 位元版本)  
(2826033)  
(重要)  
Microsoft Office 2010 Service Pack 1 (64 位元版本)  
(2826023)  
(重要)  
Microsoft Office 2010 Service Pack 1 (64 位元版本)  
(2826035)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2 (32 位元版本)  
(2826033)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(2826023)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(2826035)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2 (64 位元版本)  
(2826033)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(2826023)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(2826035)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-085**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-085)
</td>
<td style="border:1px solid black;">
[**MS13-086**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-086)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 (32 位元版本)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 (32 位元版本)  
(2827238)  
(重要)  
Microsoft Office 2013 (32 位元版本)  
(2817623)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2013 (64 位元版本)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 (64 位元版本)  
(2827238)  
(重要)  
Microsoft Office 2013 (64 位元版本)  
(2817623)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT  
(2827238)  
(重要)  
Microsoft Office 2013 RT  
(2817623)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-085**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-085)
</td>
<td style="border:1px solid black;">
[**MS13-086**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-086)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011  
(2889496)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="3">
其他 Microsoft Office 軟體
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-085**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-085)
</td>
<td style="border:1px solid black;">
[**MS13-086**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-086)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 相容性套件 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office 相容性套件 Service Pack 3  
(2827326)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Office 相容性套件 Service Pack 3  
(2827329)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Excel Viewer
</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(2827328)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
</table>
 

#### Microsoft 伺服器軟體

<p></p> 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft SharePoint Server 2007
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-084**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-084)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (32 位元版本)
</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3 (wssloc) (32 位元版本)  
(2596741)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 位元版本)
</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3 (wssloc) (64 位元版本)  
(2596741)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft SharePoint Server 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-084**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-084)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 1 (wssloc)  
(2589365)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 2 (wssloc)  
(2589365)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft SharePoint Server 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-084**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-084)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 (pptserver)  
(2760561)  
(重要)
</td>
</tr>
</table>
 
**MS13-084** **注意事項**

另請參閱＜受影響的軟體＞一節中的其他軟體類別，以取得相同公告編號裡的更多更新檔案。本公告涉及多個軟體分類。

#### Microsoft Office Services 和 Web Apps

<p></p> 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft SharePoint Server 2007
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-084**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-084)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (32 位元版本)
</td>
<td style="border:1px solid black;">
Excel Services  
(2827327)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 位元版本)
</td>
<td style="border:1px solid black;">
Excel Services  
(2827327)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft SharePoint Server 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-084**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-084)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Excel Services  
(2826029)  
(重要)  
Word Automation Services  
(2826022)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Excel Services  
(2826029)  
(重要)  
Word Automation Services  
(2826022)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft SharePoint Server 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-084**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-084)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
Excel Services  
(2752002)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
Word Automation Services  
(2826036)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Office Web Apps 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-084**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-084)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 Service Pack 1  
(2826030)  
(重要)  
Microsoft Excel Web App 2010 Service Pack 1  
(2826028)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 Service Pack 2  
(2826030)  
(重要)  
Microsoft Excel Web App 2010 Service Pack 2  
(2826028)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Office Web Apps 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-084**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-084)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013
</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(2827222)  
(重要)
</td>
</tr>
</table>
 
**MS13-084** **注意事項**

另請參閱＜受影響的軟體＞一節中的其他軟體類別，以取得相同公告編號裡的更多更新檔案。本公告涉及多個軟體分類。

#### Microsoft 開發者工具和軟體

<p></p> 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Silverlight
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-087**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-087)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
安裝在 Mac 上的 Microsoft Silverlight 5  
(2890788)  
(重要)  
安裝在 Mac 上的 Microsoft Silverlight 5 Developer Runtime  
(2890788)  
(重要)  
安裝在 Microsoft Windows 用戶端所有受支援版本上的 Microsoft Silverlight 5  
(2890788)  
(重要)  
安裝在所有受支援版本之 Microsoft Windows 用戶端上的 Microsoft Silverlight 5 Developer Runtime  
(2890788)  
(重要)  
安裝在 Microsoft Windows 伺服器所有受支援版本上的 Microsoft Silverlight 5  
(2890788)  
(重要)  
安裝在所有受支援版本之 Microsoft Windows 伺服器上的 Microsoft Silverlight 5 Developer Runtime  
(2890788)  
(重要)
</td>
</tr>
</table>
 

偵測與部署工具及指南
--------------------


有幾項資源可協助系統管理員部署資訊安全更新。

-   Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，查看是否遺漏資訊安全更新及一般資訊安全設定錯誤的狀況。
-   Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 可協助系統管理員散佈資訊安全更新。
-   應用程式相容性工具組隨附的 Update Compatibility Evaluator 元件可針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

如需上述工具以及其他可使用工具的詳細資訊，請參閱 [IT專業人員的資訊安全工具](https://technet.microsoft.com/security/cc297183)。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

針對每個月第二個星期二發行的公告，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 及下載中心發行更新版本的 Microsoft Windows 惡意軟體移除工具。不定期資訊安全公告發行不提供更新版本的 Microsoft Windows 惡意軟體移除工具。

#### MU、WU 及 WSUS 上的非資訊安全更新

如需在 Windows Update 和 Microsoft Update 上發行的非資訊安全更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](https://support.microsoft.com/kb/894199?ln=zh-tw)
-   ： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](https://technet.microsoft.com/wsus/bb456965)
-   。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的資訊安全保護，Microsoft 將在每月發行資訊安全更新之前，提前向重要資訊安全軟體提供者提供資訊安全風險資訊。資訊安全軟體提供者可利用此資訊安全風險資訊，透過其資訊安全軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](https://technet.microsoft.com/zh-tw/security/dn467918) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 資訊安全策略與社群

**更新程式管理策略**

[更新管理資訊安全指南](https://technet.microsoft.com/zh-tw/library/bb466251(zh-tw).aspx) (英文) 提供您有關套用資訊安全更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他資訊安全更新**

其他資訊安全問題的更新可由下列位置取得：

-   資訊安全更新可以從 [Microsoft 下載中心](https://www.microsoft.com/zh-tw/download/search.aspx?q=security%20update)取得， 您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。
-   消費性平台的更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以資訊安全和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的資訊安全更新。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](https://support.microsoft.com/kb/913086?ln=zh-tw)。

**IT** **專業人員資訊安全社群**

在 [IT 專業人員資訊安全社群](https://technet.microsoft.com/zh-tw/security/cc136632.aspx)上，學習如何提升資訊安全以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類資訊安全議題的討論。

#### 感謝

Microsoft [感謝](https://technet.microsoft.com/zh-tw/security/gg309157.aspx)下列人士協助我們一同保護我們的客戶：

**MS13-080**

-   感謝 [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com) 與 [HP](https://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3872)
-   感謝 Yenteasy Security Research 的 Jose A Vazquez 和 [HP](https://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作，回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3873)
-   感謝 Amol Naik 與 [HP](https://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3874)
-   感謝匿名的研究人員與 [VeriSign iDefense Labs](https://labs.idefense.com/) 合作，回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3874)
-   感謝 Yenteasy Security Research 的 Jose A Vazquez 和 [VeriSign iDefense Labs](https://labs.idefense.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3875)
-   感謝 [Google Security Team](https://www.google.com/) 的 Ivan Fratric 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3882)
-   感謝 Yenteasy Security Research 的 Jose A. Vazquez 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3882)
-   感謝 Yenteasy Security Research 的 Jose A. Vazquez 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3885)
-   感謝 Yenteasy Security Research 的 Jose A Vazquez 和 [VeriSign iDefense Labs](https://labs.idefense.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3886)
-   感謝 [LAC Co.](https://www.lac.co.jp/) 的 Yoshihiro Ishikawa 協助我們解決 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3893)
-   感謝 Hoodie22 與荷蘭國家網路安全中心 (National Cyber Security Centre) 合作，協助我們解決 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3897)
-   感謝 Trustwave SpiderLabs Team 的 Daniel Chechik 協助我們解決 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3897)
-   感謝 [IOprotect GmbH](https://ioprotect.ch/) 的 Renato Ettisberger 協助我們解決 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3897)

**MS13-081**

-   感謝匿名的研究人員與 [HP](https://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作，回報 OpenType 字型剖析資訊安全風險 (CVE-2013-3128)
-   感謝 [NCC 小組](https://www.nccgroup.com/)的 Andy Davis 回報 Windows USB 描述元資訊安全風險 (CVE-2013-3200)
-   感謝 ANSSI 的 Lucas Bouillot 回報 Windows USB 描述元資訊安全風險 (CVE-2013-3200)
-   感謝 [Endgame](https://www.endgame.com/) 的 Seth Gibson 和 Dan Zentner 回報 Win32k NULL 分頁資訊安全風險 (CVE-2013-3881)
-   感謝 ZombiE 與[HP 的](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作，回報 TrueType 字型 CMAP 表格資訊安全風險 (CVE-2013-3895)

**MS13-082**

-   感謝匿名的研究人員與 [HP](https://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作，回報 OpenType 字型剖析資訊安全風險 (CVE-2013-3128)
-   感謝 [Context Information Security](https://www.contextis.com/) 的 James Forshaw 回報實體擴充資訊安全風險 (CVE-2013-3860)

**MS13-083**

-   感謝孙晓山回報 Comctl32 整數溢位資訊安全風險 (CVE-2013-3195)

**MS13-084**

-   感謝 [Google Security Team](https://www.google.com/) 的 Mateusz Jurczyk、Ivan Fratric 和 Ben Hawkes 回報 Microsoft Excel 記憶體損毀資訊安全風險 (CVE-2013-3889)
-   感謝 Nutan kumar panda 回報參數插入資訊安全風險 (CVE-2013-3895)
-   感謝 [National Institutes of Health](https://nih.gov/) 的 Ari Elias-Bachrach 和 Angela Kelso 協助我們進行本公告所包含之深度防禦變更

**MS13-085**

-   感謝 [Google Security Team](https://www.google.com/) 的 Mateusz Jurczyk、Ivan Fratric 和 Ben Hawkes 回報 Microsoft Excel 記憶體損毀資訊安全風險 (CVE-2013-3889)
-   感謝 [Google Security Team](https://www.google.com/) 的 Mateusz Jurczyk、Ivan Fratric 和 Ben Hawkes 回報 Microsoft Excel 記憶體損毀資訊安全風險 (CVE-2013-3890)

**MS13-086**

-   感謝 Yuhong Bao 回報記憶體損毀資訊安全風險 (CVE-2013-3891)
-   感謝 [Google Security Team](https://www.google.com/) 的 Mateusz Jurczyk、Ivan Fratric 和 Ben Hawkes 回報記憶體損毀資訊安全風險 (CVE-2013-3892)

**MS13-087**

-   感謝 Vitaliy Toropov 回報 Silverlight 資訊安全風險 (CVE-2013-3896)

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 支援週期](https://support.microsoft.com/default.aspx?scid=fh;%5bln%5d;lifecycle?ln=zh-tw)。
-   IT 專業人員的資訊安全解決方案： [TechNet 資訊安全疑難排解與支援](https://technet.microsoft.com/security/bb980617)
-   協助保護您的 Windows 電腦免於病毒和惡意軟體攻擊： [病毒解決方案與資訊安全中心](https://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-tw)
-   您所在國家/地區的當地支援： [國際支援](https://support.microsoft.com/common/international.aspx?ln=zh-tw)

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2013 年 10 月 8 日)： 公告摘要發行。
-   V1.1 (2013 年 10 月 10 日)： 對於 MS13-080，移除資訊安全風險入侵指數中的 CVE-2013-3871 資訊安全風險評估。由於發生文件錯誤，因此導致原本的資訊安全風險入侵指數中納入了上述 CVE。CVE-2013-3871 已排定於未來的資訊安全更新中解決。這只是資訊的變更。對於 MS13-082，修訂此公告的目的，是說明 Windows Server 2012 Server Core 安裝會受到 2861194 更新中指出的資訊安全風險影響。偵測邏輯或資訊安全更新檔案沒有變更。已成功更新系統的客戶不必採取任何行動。
-   V1.2 (2013 年 11 月 28 日)： 針對 MS13-084，更正 Microsoft Office Web Apps Server 2013 (2827222) 更新的產品名稱。

*Built at 2014-04-18T01:50:00Z-07:00*
