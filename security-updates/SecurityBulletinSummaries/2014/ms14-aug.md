---
TOCTitle: 'MS14-AUG'
Title: 2014 年 8 月 Microsoft 資訊安全公告摘要
ms:assetid: 'ms14-aug'
ms:contentKeyID: 62757491
ms:date: '12/26/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms14-aug(v=Security.10)'
---

MSRC ppDocument 範本

2014 年 8 月 Microsoft 資訊安全公告摘要
=======================================

發行日期：2014 年 8 月 12 日 | 更新日期：2014 年 12 月 19 日

**版本：** 2.2

此公告摘要列出 2014 年 8 月發行的資訊安全公告。

發行 2014 年 8 月份資訊安全公告之後，此公告摘要將取代原先於 2014 年 8 月 7 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 資訊安全公告預先通知](http://go.microsoft.com/fwlink/?linkid=217213)。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術資訊安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播，於 2014 年 8 月 13 日太平洋時間早上 11 點 (美國與加拿大) 解答客戶對於這些公告的問題。若要檢視每月網路廣播和其他資訊安全公告網路廣播的連結，請參閱 [Microsoft 資訊安全公告網路廣播](http://technet.microsoft.com/security/dn756352)。

Microsoft 也會提供資訊協助客戶排定每月資訊安全更新以及任何非資訊安全更新的優先順序，其中這些非資訊安全更新的發行日期與每月資訊安全更新的發行日期相同。請參閱**＜其他資訊＞**一節。

提要
----

<span id="sectionToggle0"></span>
下表依嚴重性摘要說明本月份資訊安全公告。

如需受影響的軟體之詳細資料，請參閱下節＜**受影響的軟體**＞。

 
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 積存資訊安全更新 (2976627)<br />
<br />
</strong>此資訊安全更新可解決 Internet Explorer 中一項公開揭露的資訊安全風險，以及二十五項未公開報告的資訊安全風險。其中最嚴重的資訊安全風險，可能在使用者以 Internet Explorer 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用這些資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507337">MS14-043</a></td>
<td style="border:1px solid black;"><strong>Windows Media Center 中的資訊安全風險可能會允許遠端執行程式碼 (2978742)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果使用者開啟蓄意製作、可呼叫 Windows Media Center 資源的 Microsoft Office 檔案，此資訊安全風險可能會允許遠端執行程式碼。成功利用此資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402461">MS14-048</a></td>
<td style="border:1px solid black;"><strong>OneNote 中的資訊安全風險可能會允許遠端執行程式碼 (2977201)</strong><br />
<br />
此資訊安全更新可解決 Microsoft OneNote 中一項未公開報告的資訊安全風險。如果在受影響版本的 Microsoft OneNote 中開啟蓄意製作的檔案，此資訊安全風險可能會允許遠端執行程式碼。成功利用此資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507036">MS14-044</a></td>
<td style="border:1px solid black;"><strong>SQL Server 中的資訊安全風險可能會允許提高權限 (2984340)</strong><br />
<br />
這個安全性更新可解決 Microsoft SQL Server 中兩項未公開報告的資訊安全風險 (一個是在 SQL Server Master Data Services 中，另一個則在 SQL Server 關聯式資料庫管理系統中)。這些資訊安全風險較嚴重者除了影響 SQL Server Master Data Services 之外，同時如果使用者瀏覽了蓄意製作的網站，而該網站在使用者的 Internet Explorer 執行個體中放入用戶端指令碼，這時就可能允許提高權限。無論如何，攻擊者無法強迫使用者檢視受攻擊者控制的內容， 而是引誘使用者自行前往。一般的做法是設法讓使用者點選電子郵件訊息或 Instant Messenger 中通往攻擊者網站的連結，或設法讓他們開啟經由電子郵件傳送的附件。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft SQL Server</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507035">MS14-045</a></td>
<td style="border:1px solid black;"><strong>核心模式驅動程式中的資訊安全風險可能會允許權限提高 (2984615)</strong><br />
<br />
這個資訊安全更新可解決<strong></strong>Microsoft Windows 中三項未公開報告的資訊安全風險。如果攻擊者登入系統並執行蓄意製作的應用程式，則最嚴重的資訊安全風險可能會允許權限提高。攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這些資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=396822">MS14-049</a></td>
<td style="border:1px solid black;"><strong>Windows Installer 服務中的資訊安全風險可能會允許權限提高 (2962490)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Windows 中一項未公開揭露的資訊安全風險。如果攻擊者執行蓄意製作的應用程式，嘗試修復先前安裝的應用程式，則此資訊安全風險可能會允許權限提高。攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402463">MS14-050</a></td>
<td style="border:1px solid black;"><strong>在 Microsoft SharePoint Server 中的資訊安全風險可能會允許權限提高 (2977202)</strong><br />
<br />
這個資訊安全更新可解決 Microsoft .SharePoint Server 中一項未公開報告的資訊安全風險。成功利用此資訊安全風險且通過驗證的攻擊者，可在目前 SharePoint 網站上，以使用者的權限層級利用蓄意製作的應用程式來執行任意 JavaScript。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft 伺服器軟體</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507038">MS14-046</a></td>
<td style="border:1px solid black;"><strong>.NET Framework 中的資訊安全風險可能會允許資訊安全功能略過 (2984625)</strong><br />
<br />
這個資訊安全更新可解決 Microsoft .NET Framework 中一項未公開報告的資訊安全風險。如果使用者造訪蓄意製作的網站，此資訊安全風險可能會允許資訊安全功能略過。在網頁瀏覽攻擊的案例中，成功利用此資訊安全風險的攻擊者可以略過位址空間隨機載入 (ASLR) 安全性功能，而此功能可協助保護使用者免於廣泛類別的資訊安全風險侵擾。略過安全性功能本身不會允許執行任意程式碼。但是，攻擊者利用此 ASLR 略過資訊安全風險時，可能會搭配另一個利用 ASLR 略過來執行任意程式碼的資訊安全風險 (例如遠端執行程式碼資訊安全風險)。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
資訊安全功能略過</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507336">MS14-047</a></td>
<td style="border:1px solid black;"><strong>LRPC 中的資訊安全風險可能會允許資訊安全功能略過 (2978668)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果攻擊者利用此資訊安全風險搭配另一個會利用 ASLR 略過來執行任意程式碼的資訊安全風險 (例如遠端執行程式碼資訊安全風險)，此資訊安全風險可能會允許資訊安全功能略過。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
資訊安全功能略過</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
 
  
資訊安全風險入侵指數  
--------------------
  
<span id="sectionToggle1"></span>
下表提供本月所述每個資訊安全風險的利用性評估。資訊安全風險皆根據公告編號和 CVE 編號依序列出。僅包含資訊安全公告中，嚴重性等級為「重大」或「重要」的資訊安全風險。
  
我該如何使用這個表格？
  
您可以運用此表格，針對您可能需要安裝的每一項資訊安全更新，瞭解資訊安全風險在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務 (DoS) 的可能性。請根據您特定的組態設定，檢閱下列各項評估，決定部署本月份更新的優先次序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 資訊安全風險索引](http://technet.microsoft.com/security/cc998259)。
  
在下方欄位中，「最新軟體版本」意指受影響軟體，「較舊軟體版本」意指受影響軟體所有較舊的支援版本，如公告中的「受影響的軟體」或「不受影響的軟體」表格裡所示。
  
<table style="width:100%;">
<colgroup>
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
</colgroup>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507337">MS14-043</a></td>
<td style="border:1px solid black;">CSyncBasePlayer 釋放後使用資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4060">CVE-2014-4060</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507036">MS14-044</a></td>
<td style="border:1px solid black;">SQL Master Data Services XSS 資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1820">CVE-2014-1820</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507036">MS14-044</a></td>
<td style="border:1px solid black;">Microsoft SQL Server 堆疊溢位資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4061">CVE-2014-4061</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">這是一項阻斷服務 (DoS) 的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507035">MS14-045</a></td>
<td style="border:1px solid black;">Win32k 權限提高資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0318">CVE-2014-0318</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507035">MS14-045</a></td>
<td style="border:1px solid black;">字型 Double-Fetch 資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1819">CVE-2014-1819</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507035">MS14-045</a></td>
<td style="border:1px solid black;">Windows 核心集區配置資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4064">CVE-2014-4064</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊洩漏的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507038">MS14-046</a></td>
<td style="border:1px solid black;">.NET ASLR 資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4062">CVE-2014-4062</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊安全功能略過之資訊安全風險。<br />
<br />
本資訊安全公告初次發行時，Microsoft 尚未接到任何有關本資訊安全風險已公開用來攻擊客戶的消息。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507336">MS14-047</a></td>
<td style="border:1px solid black;">LRPC ASLR 略過資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0316">CVE-2014-0316</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">這是一個資訊安全功能略過之資訊安全風險。<br />
<br />
本資訊安全公告初次發行時，Microsoft 尚未接到任何有關本資訊安全風險已公開用來攻擊客戶的消息。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402461">MS14-048</a></td>
<td style="border:1px solid black;">OneNote 遠端執行程式碼資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2815">CVE-2014-2815</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=396822">MS14-049</a></td>
<td style="border:1px solid black;">Windows Installer 修復資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1814">CVE-2014-1814</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402463">MS14-050</a></td>
<td style="border:1px solid black;">SharePoint 頁面內容資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2816">CVE-2014-2816</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2774">CVE-2014-2774</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2784">CVE-2014-2784</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2796">CVE-2014-2796</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2808">CVE-2014-2808</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2810">CVE-2014-2810</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2811">CVE-2014-2811</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 權限提高資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2817">CVE-2014-2817</a></td>
<td style="border:1px solid black;">0 - 已偵測到利用</td>
<td style="border:1px solid black;">0 - 已偵測到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">Microsoft 已發現有嘗試利用此資訊安全風險的有限攻擊。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2818">CVE-2014-2818</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 權限提高資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2819">CVE-2014-2819</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">此資訊安全風險已經遭到公開揭發。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2820">CVE-2014-2820</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2821">CVE-2014-2821</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2822">CVE-2014-2822</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2823">CVE-2014-2823</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2824">CVE-2014-2824</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2825">CVE-2014-2825</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2826">CVE-2014-2826</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2827">CVE-2014-2827</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4050">CVE-2014-4050</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4051">CVE-2014-4051</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4052">CVE-2014-4052</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4055">CVE-2014-4055</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4056">CVE-2014-4056</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4057">CVE-2014-4057</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4058">CVE-2014-4058</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4063">CVE-2014-4063</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4067">CVE-2014-4067</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4145">CVE-2014-4145</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6354">CVE-2014-6354</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">無</td>
</tr>
</tbody>
</table>
  
受影響的軟體  
------------
  
<span id="sectionToggle2"></span>
下表依據主要的軟體類別和嚴重性依序列出公告。
  
**我該如何使用這些表格？**
  
請用這些表格來瞭解可能需要安裝的資訊安全更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的資訊安全更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。
  
**注意**：一項資訊安全風險，可能需要安裝數個資訊安全更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
**Windows 作業系統與元件**

 
<table style="border:1px solid black;">
<tr>
<th colspan="7">
Windows Server 2003
  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](http://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://go.microsoft.com/fwlink/?linkid=507336)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2976627)  
(中度)  
Internet Explorer 7  
(2976627)  
(中度)  
Internet Explorer 8  
(2976627)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2993651)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2918614)  
(重要)

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
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2976627)  
(中度)  
Internet Explorer 7  
(2976627)  
(中度)  
Internet Explorer 8  
(2976627)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2993651)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2918614)  
(重要)

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
適用於 Itanium 型系統的 Windows Server 2003 SP2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2976627)  
(中度)  
Internet Explorer 7  
(2976627)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(2993651)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](http://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://go.microsoft.com/fwlink/?linkid=507336)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2976627)  
(重大)  
Internet Explorer 8  
(2976627)  
(重大)  
Internet Explorer 9  
(2976627)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2993651)  
(重要)  
Windows Vista Service Pack 2  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2937608)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2943344)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2976627)  
(重大)  
Internet Explorer 8  
(2976627)  
(重大)  
Internet Explorer 9  
(2976627)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2993651)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2937608)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2943344)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](http://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://go.microsoft.com/fwlink/?linkid=507336)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2976627)  
(中度)  
Internet Explorer 8  
(2976627)  
(中度)  
Internet Explorer 9  
(2976627)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2993651)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2937608)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2943344)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2976627)  
(中度)  
Internet Explorer 8  
(2976627)  
(中度)  
Internet Explorer 9  
(2976627)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2993651)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2937608)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2943344)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2976627)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2993651)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2937608)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2943344)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](http://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://go.microsoft.com/fwlink/?linkid=507336)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2976627)  
(重大)  
Internet Explorer 9  
(2976627)  
(重大)  
Internet Explorer 10  
(2976627)  
(重大)  
Internet Explorer 11  
(2976627)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(所有版本，除了簡易版和家用入門版以外)  
(2978742)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2993651)  
(重要)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2937610)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2943357)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2978668)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2976627)  
(重大)  
Internet Explorer 9  
(2976627)  
(重大)  
Internet Explorer 10  
(2976627)  
(重大)  
Internet Explorer 11  
(2976627)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(所有版本，除了簡易版和家用入門版以外)  
(2978742)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2993651)  
(重要)  
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2937610)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2943357)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2978668)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](http://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://go.microsoft.com/fwlink/?linkid=507336)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2976627)  
(中度)  
Internet Explorer 9  
(2976627)  
(中度)  
Internet Explorer 10  
(2976627)  
(中度)  
Internet Explorer 11  
(2976627)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2993651)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2937610)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2943357)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2978668)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2976627)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2993651)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2937610)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2943357)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2978668)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](http://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://go.microsoft.com/fwlink/?linkid=507336)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2976627)  
(重大)

</td>
<td style="border:1px solid black;">
安裝在適用於 32 位元系統之 Windows 8 (僅限專業版) 上的 Windows Media Center  
(2978742)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8  
(2993651)  
(重要)  
適用於 32 位元系統的 Windows 8  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966825)  
(重要)  
Microsoft .NET Framework 3.5  
(2966827)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8  
(2978668)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2976627)  
(重大)

</td>
<td style="border:1px solid black;">
安裝在適用於 x64 型系統之 Windows 8 (僅限專業版) 上的 Windows Media Center  
(2978742)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(2993651)  
(重要)  
適用於 x64 型系統的 Windows 8  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966825)  
(重要)  
Microsoft .NET Framework 3.5  
(2966827)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(2978668)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2976627)  
(重大)

</td>
<td style="border:1px solid black;">
安裝在適用於 32 位元系統之 Windows 8.1 (僅限專業版) 上的 Windows Media Center  
(2978742)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(2993651)  
(重要)  
適用於 32 位元系統的 Windows 8.1  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966826)  
(重要)  
Microsoft .NET Framework 3.5  
(2966828)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(2978668)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2976627)  
(重大)

</td>
<td style="border:1px solid black;">
安裝在適用於 x64 型系統之 Windows 8.1 (僅限專業版) 上的 Windows Media Center  
(2978742)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(2993651)  
(重要)  
適用於 x64 型系統的 Windows 8.1  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966826)  
(重要)  
Microsoft .NET Framework 3.5  
(2966828)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(2978668)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](http://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://go.microsoft.com/fwlink/?linkid=507336)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2976627)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2993651)  
(重要)  
Windows Server 2012  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966825)  
(重要)  
Microsoft .NET Framework 3.5  
(2966827)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2978668)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2976627)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2993651)  
(重要)  
Windows Server 2012 R2  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966826)  
(重要)  
Microsoft .NET Framework 3.5  
(2966828)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2978668)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](http://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://go.microsoft.com/fwlink/?linkid=507336)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2976627)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT  
(2993651)  
(重要)  
Windows RT  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT  
(2978668)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2976627)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2993651)  
(重要)  
Windows RT 8.1  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2978668)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Server Core 安裝選項**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](http://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://go.microsoft.com/fwlink/?linkid=507336)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2993651)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2918614)  
(重要)

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
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2993651)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2918614)  
(重要)

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
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(2993651)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2937610)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2943357)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(2978668)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(2993651)  
(重要)  
Windows Server 2012 (Server Core 安裝)  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966825)  
(重要)  
Microsoft .NET Framework 3.5  
(2966827)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(2978668)  
(重要)

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
Windows Server 2012 R2 (Server Core 安裝)  
(2993651)  
(重要)  
Windows Server 2012 R2 (Server Core 安裝)  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966826)  
(重要)  
Microsoft .NET Framework 3.5  
(2966828)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(2978668)  
(重要)

</td>
</tr>
</table>
 
**MS14-043 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

 

**Microsoft Office 軟體**

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
**Microsoft Office 軟體**

</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-048**](http://go.microsoft.com/fwlink/?linkid=402461)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft OneNote 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft OneNote 2007 Service Pack 3  
(2596857)  
(重要)

</td>
</tr>
</table>
 
 

**Microsoft SQL Server**

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-044**](http://go.microsoft.com/fwlink/?linkid=507036)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Microsoft SQL Server 2008 Service Pack 3

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Microsoft SQL Server 2008 Service Pack 3  
(GDR)  
(2977321)  
(重要)  
適用於 32 位元系統的 Microsoft SQL Server 2008 Service Pack 3  
(QFE)  
(2977322)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Microsoft SQL Server 2008 Service Pack 3

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Microsoft SQL Server 2008 Service Pack 3  
(GDR)  
(2977321)  
(重要)  
適用於 x64 型系統的 Microsoft SQL Server 2008 Service Pack 3  
(QFE)  
(2977322)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Microsoft SQL Server 2008 Service Pack 3

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Microsoft SQL Server 2008 Service Pack 3  
(GDR)  
(2977321)  
(重要)  
適用於 Itanium 型系統的 Microsoft SQL Server 2008 Service Pack 3  
(QFE)  
(2977322)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Microsoft SQL Server 2008 R2 Service Pack 2

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Microsoft SQL Server 2008 R2 Service Pack 2  
(GDR)  
2977320)  
(重要)  
適用於 32 位元系統的 Microsoft SQL Server 2008 R2 Service Pack 2  
(QFE)  
(2977319)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Microsoft SQL Server 2008 R2 Service Pack 2

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Microsoft SQL Server 2008 R2 Service Pack 2  
(GDR)  
(2977320)  
(重要)  
適用於 x64 型系統的 Microsoft SQL Server 2008 R2 Service Pack 2  
(QFE)  
(2977319)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Microsoft SQL Server 2008 R2 Service Pack 2

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Microsoft SQL Server 2008 R2 Service Pack 2  
(GDR)  
(2977320)  
(重要)  
適用於 Itanium 型系統的 Microsoft SQL Server 2008 R2 Service Pack 2  
(QFE)  
(2977319)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2012**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Microsoft SQL Server 2012 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Microsoft SQL Server 2012 Service Pack 1  
(GDR)  
(2977326)  
(重要)  
適用於 32 位元系統的 Microsoft SQL Server 2012 Service Pack 1  
(QFE)  
(2977325)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Microsoft SQL Server 2012 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Microsoft SQL Server 2012 Service Pack 1  
(GDR)  
(2977326)  
(重要)  
適用於 x64 型系統的 Microsoft SQL Server 2012 Service Pack 1  
(QFE)  
(2977325)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2014**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Microsoft SQL Server 2014

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Microsoft SQL Server 2014  
(GDR)  
(2977315)  
(重要)  
適用於 x64 型系統的 Microsoft SQL Server 2014  
(QFE)  
(2977316)  
(重要)

</td>
</tr>
</table>
 
 

**Microsoft 伺服器軟體**

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-050**](http://go.microsoft.com/fwlink/?linkid=402463)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013  
(2880994)  
(重要)  
Microsoft SharePoint Foundation 2013  
(2880994)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1  
(2880994)  
(重要)  
Microsoft SharePoint Foundation 2013 Service Pack 1  
(2880994)  
(重要)

</td>
</tr>
</table>
 
 

**其他軟體**

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**適用於 Windows Vista 的 Windows Media Center TV Pack**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://go.microsoft.com/fwlink/?linkid=507337)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Windows Vista (32 位元版本) 的 Windows Media Center TV Pack

</td>
<td style="border:1px solid black;">
適用於 Windows Vista (32 位元版本) 的 Windows Media Center TV Pack  
(2978742)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Windows Vista (64 位元版本) 的 Windows Media Center TV Pack

</td>
<td style="border:1px solid black;">
適用於 Windows Vista (64 位元版本) 的 Windows Media Center TV Pack  
(2978742)  
(重大)

</td>
</tr>
</table>
 
**MS14-043 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

 

偵測與部署工具及指南
--------------------

<span id="sectionToggle3"></span>
有幾項資源可協助系統管理員部署資訊安全更新。

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，查看是否遺漏資訊安全更新及一般資訊安全設定錯誤的狀況。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 可協助系統管理員散佈資訊安全更新。

應用程式相容性工具組隨附的 Update Compatibility Evaluator 元件可針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

如需上述工具以及其他可使用工具的詳細資訊，請參閱 [IT專業人員的資訊安全工具](http://technet.microsoft.com/security/cc297183)。 

感謝
----

<span id="sectionToggle4"></span>
Microsoft [感謝](http://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

**MS14-043**

-   感謝 Alisa Esage (@alisaesage) 與 [HP](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 CSyncBasePlayer 釋放後使用資訊安全風險 (CVE-2014-4060)

**MS14-045**

-   感謝 [Qihoo 360](http://www.360.cn/) 的 Wang Yu 回報字型 Double-Fetch 資訊安全風險 (CVE-2014-1819)
-   感謝 Ilja Van Sprundel 回報 Windows 核心集區配置資訊安全風險 (CVE-2014-4064)

**MS14-047**

-   感謝 [Alex Ionescu](http://www.alex-ionescu.com/) 回報 LRPC ASLR 略過資訊安全風險 (CVE-2014-0316)

**MS14-048**

-   感謝 Eduardo Prado 與 Beyond Security 的[SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html) 計畫合作，回報 OneNote 遠端執行程式碼資訊安全風險 (CVE-2014-2815)

**MS14-049**

-   感謝 [Entisys](http://www.entisys.com/) 的 Denis Gundarev 回報 Windows Installer 修復資訊安全風險 (CVE-2012-4784)
-   感謝 [Stepfan Kanthak](http://home.arcor.de/skanthak/safer.html) 協助我們完成本公告中的深度防禦變更

**MS14-051**

-   感謝 [HP](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 的 AbdulAziz Hariri 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2774)
-   感謝 [Qihoo 360](http://www.360.cn/) 的 Yujie Wen 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2784)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2796)
-   感謝 [NSFOCUS Security Team](http://www.nsfocus.com/) 的 [Chen Zhang (demi6od)](https://github.com/demi6od) 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2808)
-   感謝 [NSFOCUS Security Team](http://www.nsfocus.com/) 的 [Chen Zhang (demi6od)](https://github.com/demi6od) 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2810)
-   感謝 IronRock 與 [VeriSign iDefense Labs](http://labs.idefense.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2811)
-   感謝 [Context Information Security](http://www.contextis.com/) 的 James Forshaw 回報 Internet Explorer 權限提高資訊安全風險 (CVE-2014-2817)
-   感謝 [HP](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 的 AbdulAziz Hariri 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2818)
-   感謝 [Team509](http://team509.com/) 的 Zeguang Zhao 和 [KeenTeam](http://www.k33nteam.org/) (@K33nTeam) 的 Liang Chen 與 [HP 的](http://www.hpenterprisesecurity.com/products) [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 權限提高資訊安全風險 (CVE-2014-2819)
-   感謝 Arthur Gerkis 與 [HP](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2820)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2821)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2822)
-   感謝 [NSFOCUS Security Team](http://www.nsfocus.com/) 的 [Chen Zhang (demi6od)](https://github.com/demi6od) 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2823)
-   感謝 [Qihoo 360](http://www.360.cn/) 的 Yuki Chen 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2824)
-   感謝 [NSFOCUS Security Team](http://www.nsfocus.com/) 的 [Chen Zhang (demi6od)](https://github.com/demi6od) 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2825)
-   感謝 [NSFOCUS Security Team](http://www.nsfocus.com/) 的 [Chen Zhang (demi6od)](https://github.com/demi6od) 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2826)
-   感謝 [HP](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 的 Simon Zuckerbraun 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2827)
-   感謝 [Omair](http://krash.in/) 與 [HP](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4050)
-   感謝 [Corelan](http://www.corelangcv.com/) 的 Peter 'corelanc0d3r' Van Eeckhoutte 與 [HP](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4051)
-   感謝匿名的研究人員與 [HP](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4052)
-   感謝 [HP](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 的 Simon Zuckerbraun 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4055)
-   感謝 [Corelan](http://www.corelangcv.com/) 的 Peter 'corelanc0d3r' Van Eeckhoutte 與 [HP](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4056)
-   感謝 [Trend Micro](http://www.trendmicro.com/) 的 Yuki Chen 與 [HP](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4057)
-   感謝 Sky 與 [HP](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4058)
-   感謝匿名的研究人員與 [HP](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4063)
-   感謝 [VulnHunt](http://www.vulnhunt.com/) 的 Wei Wang 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4067)
-   感謝 [lokihardt@ASRT](https://technet.microsoft.com/zh-TW/mailto:lokihardt@asrt) 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4067)
-   感謝 Omair 與 [HP](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4145)
-   感謝 Omair 與 [HP](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-6354)

其他資訊
--------

<span id="sectionToggle5"></span>
### Microsoft Windows 惡意軟體移除工具 (英文)

針對每個月第二個星期二發行的公告，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 及下載中心發行更新版本的 Microsoft Windows 惡意軟體移除工具。不定期資訊安全公告發行不提供更新版本的 Microsoft Windows 惡意軟體移除工具。

### MU、WU 及 WSUS 上的非資訊安全更新

如需在 Windows Update 和 Microsoft Update 上發行的非資訊安全更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](https://support.microsoft.com/kb/894199)： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](http://technet.microsoft.com/wsus/bb456965)。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的資訊安全保護，Microsoft 將在每月發行資訊安全更新之前，提前向重要資訊安全軟體提供者提供資訊安全風險資訊。資訊安全軟體提供者可利用此資訊安全風險資訊，透過其資訊安全軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://go.microsoft.com/fwlink/?linkid=215201) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

### 資訊安全策略與社群

**更新程式管理策略**

[更新管理資訊安全指南](http://go.microsoft.com/fwlink/?linkid=21168) (英文) 提供您有關套用資訊安全更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他資訊安全更新**

其他資訊安全問題的更新可由下列位置取得：

-   資訊安全更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。
-   消費性平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以資訊安全和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的資訊安全更新。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](https://support.microsoft.com/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全社群](http://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升資訊安全以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類資訊安全議題的討論。

### 支援

所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 支援週期](http://go.microsoft.com/fwlink/?linkid=21742)。

IT 專業人員的資訊安全解決方案： [TechNet 資訊安全疑難排解與支援](http://technet.microsoft.com/security/bb980617)

協助保護您的 Widows 電腦免於病毒和惡意軟體攻擊： [病毒解決方案與資訊安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master)

您所在國家/地區的當地支援： [國際支援](http://support.microsoft.com/common/international.aspx)

### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

### 修訂

-   V1.0 (2014 年 8 月 12 日)： 公告摘要發行。
-   V2.0 (2014 年 8 月 27 日)： 針對 MS14-045 重新發行公告，宣佈針對所有受支援的 Microsoft Windows 版本，以 2993651 更新取代 2982791 更新。請參閱公告內容以瞭解詳細資訊。
-   V 2.1 (2014 年 10 月 8 日)： 針對 MS14-051，為 CVE-2014-4145 新增「資訊安全風險入侵指數」的資訊安全風險評估。這項變更純屬資訊上的變更。
-   V2.2 (2014 年 12 月 19 日)：針對 MS14-051，為 CVE-2014-6354 新增「資訊安全風險入侵指數」的資訊安全風險評估。這項變更純屬資訊上的變更。

*頁面產生時間：2014-10-07 17:05Z-07:00。*
