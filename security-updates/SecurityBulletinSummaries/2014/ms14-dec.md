---
TOCTitle: 'MS14-DEC'
Title: 2014 年 12 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms14-dec'
ms:contentKeyID: 63745964
ms:date: '12/11/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms14-dec(v=Security.10)'
---

2014 年 12 月份 Microsoft 資訊安全公告摘要
==========================================

發行日期：2014 年 12 月 9 日

**版本：** 1.0

此公告摘要列出 2014 年 12 月份發行之資訊安全公告。

發行 2014 年 12 月份資訊安全公告之後，此公告摘要將取代原先於 2014 年 12 月 4 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 資訊安全公告預先通知](https://technet.microsoft.com/zh-tw/security/gg309152.aspx)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](https://technet.microsoft.com/zh-tw/security/dd252948.aspx)。

Microsoft 也會提供資訊協助客戶排定每月資訊安全更新以及任何非資訊安全更新的優先順序，其中這些非資訊安全更新的發行日期與每月資訊安全更新的發行日期相同。請參閱**＜其他資訊＞**一節。

提要
----

下表依嚴重性摘要說明本月份資訊安全公告。

如需受影響的軟體之詳細資料，請參閱下節＜**受影響的軟體**＞。

<p></p> 
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告編號</strong></td>
<td style="border:1px solid black;"><strong>公告標題與提要</strong></td>
<td style="border:1px solid black;"><strong>最高的嚴重性等級與資訊安全風險影響</strong></td>
<td style="border:1px solid black;"><strong>重新開機需求</strong></td>
<td style="border:1px solid black;"><strong>受影響的軟體</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518104">MS14-075</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange Server 中的資訊安全風險可能會允許提高權限 (3009712)<br />
<br />
</strong>這個資訊安全更新可解決 Microsoft Exchange Server 中四項未公開報告的資訊安全風險。如果使用者點選會將使用者帶到目標 Outlook Web App 網站之蓄意製作的 URL，則最嚴重的資訊安全風險可能會允許權限提高。攻擊者並不能強迫使用者造訪蓄意製作的網站，而是引誘使用者自行前往。一般的做法是設法讓使用者點選電子郵件訊息中或 Instant Messenger 訊息中連往攻擊者網站的 連結，然後引誘他們點選蓄意製作的 URL。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Exchange</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 積存安全性更新 (3008923)<br />
<br />
</strong>本資訊安全更新可解決 Internet Explorer 中十四項未公開報告的資訊安全風險。其中最嚴重的資訊安全風險，可能在使用者以 Internet Explorer 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用這些資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=519132">MS14-081</a></td>
<td style="border:1px solid black;"><strong>Microsoft Word 和 Microsoft Office Web Apps 中的資訊安全風險可能會允許遠端執行程式碼 (3017301)<br />
<br />
</strong>此資訊安全更新可解決 Microsoft Word 和 Microsoft Office Web Apps 中兩項未公開報告的資訊安全風險。如果攻擊者說服使用者在受影響的 Microsoft Office 軟體版本中開啟或預覽蓄意製作的 Microsoft Word 檔案，資訊安全風險可能會允許遠端執行程式碼。成功利用這些資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。如果目前的使用者以系統管理的使用者權限登入，攻擊者接下來就能安裝程式，並檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=519135">MS14-082</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 中的資訊安全風險可能會允許遠端執行程式碼 (3017349)<br />
<br />
</strong>這個資訊安全更新可解決 Microsoft Office 中一項未公開報告的資訊安全風險。如果使用者在受影響版本的 Microsoft Office 中開啟蓄意製作的檔案，此資訊安全風險可能會允許遠端執行程式碼。成功利用此資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=519133">MS14-083</a></td>
<td style="border:1px solid black;"><strong>Microsoft Excel 中的資訊安全風險可能會允許遠端執行程式碼 (3017347)<br />
<br />
</strong>這個資訊安全更新可解決 Microsoft Excel 中兩項未公開報告的資訊安全風險。如果攻擊者說服使用者在受影響的 Microsoft Office 軟體版本中開啟或預覽蓄意製作的 Microsoft Excel 檔案，資訊安全風險可能會允許遠端執行程式碼。成功利用這些資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。如果目前的使用者以系統管理的使用者權限登入，攻擊者接下來就能安裝程式，並檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=519131">MS14-084</a></td>
<td style="border:1px solid black;"><strong>VBScript 指令碼引擎中的資訊安全風險可能允許遠端執行程式碼 (3016711)<br />
<br />
</strong>這個資訊安全更新可解決 Microsoft Windows 的 VBScript 指令碼引擎中一項未公開報告的資訊安全風險。如果使用者造訪蓄意製作的網站，此資訊安全風險可能會允許遠端執行程式碼。成功利用此資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。如果使目前用者以系統管理的使用者權限登入，成功利用此資訊安全風險的攻擊者可以取得受影響系統的完整控制權。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=519129">MS14-085</a></td>
<td style="border:1px solid black;"><strong>Microsoft Graphics Component 中的資訊安全風險可能會允許資訊洩漏 (3013126)<br />
<br />
</strong>此資訊安全更新可解決 Microsoft Windows 中一項公開揭露的資訊安全風險。如果使用者瀏覽至含有蓄意製作之 JPEG 內容的網站，則此資訊安全風險便可能允許資訊洩漏。攻擊者可能使用此資訊洩漏資訊安全風險取得該系統的資訊，之後與其他攻擊合併侵入系統。資訊洩漏資訊安全風險本身不允許執行任意程式碼。不過，攻擊者可能會合併使用此資訊洩漏資訊安全風險與另一個資訊安全風險，以規避「位址空間配置隨機載入 (ASLR)」這類的資訊安全功能。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
資訊洩漏</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
 
  
資訊安全風險入侵指數  
--------------------
  
下表提供本月所述每個資訊安全風險的利用性評估。會依序按公告編號及 CVE ID 的順序列出資訊安全風險。只會包含公告中嚴重性等級為「重大」或「重要」的資訊安全風險。
  
**我該如何使用這個表格？**
  
您可以運用此表格，針對您可能需要安裝的每一項資訊安全更新，瞭解資訊安全風險在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務 (DoS) 的可能性。請根據您特定的組態設定，檢閱下列各項評估，決定部署本月份更新的優先次序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](https://technet.microsoft.com/zh-tw/security/cc998259)。
  
在下方欄位中，「最新軟體版本」意指受影響軟體，「較舊軟體版本」意指受影響軟體所有較舊的支援版本，如公告中的「受影響的軟體」或「不受影響的軟體」表格裡所示。
  
<p></p>
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
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告編號</strong></td>
<td style="border:1px solid black;"><strong>資訊安全風險標題</strong></td>
<td style="border:1px solid black;"><strong>CVE ID</strong></td>
<td style="border:1px solid black;"><strong>最新軟體版本的資訊安全風險評估</strong></td>
<td style="border:1px solid black;"><strong>較舊軟體版本的資訊安全風險評估</strong></td>
<td style="border:1px solid black;"><strong>阻斷服務 (DoS) 資訊安全風險評估</strong></td>
<td style="border:1px solid black;"><strong>主要重點</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518104">MS14-075</a></td>
<td style="border:1px solid black;">Outlook Web App 語彙基元偽造資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6319">CVE-2014-6319</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊洩漏的資訊安全風險。此資訊安全風險可以用於在社交工程攻擊中進行詐騙。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518104">MS14-075</a></td>
<td style="border:1px solid black;">OWA XSS 資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6325">CVE-2014-6325</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是權限提高的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518104">MS14-075</a></td>
<td style="border:1px solid black;">OWA XSS 資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6326">CVE-2014-6326</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是權限提高的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518104">MS14-075</a></td>
<td style="border:1px solid black;">Exchange URL 重新導向資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6336">CVE-2014-6336</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊洩漏的資訊安全風險。此資訊安全風險可以用於在社交工程攻擊中進行詐騙。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6327">CVE-2014-6327</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是遠端執行程式碼的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer XSS 篩選略過資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6328">CVE-2014-6328</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊安全功能略過之資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6329">CVE-2014-6329</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是遠端執行程式碼的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6330">CVE-2014-6330</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是遠端執行程式碼的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">VBScript 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6363">CVE-2014-6363</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是遠端執行程式碼的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer XSS 篩選略過資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6365">CVE-2014-6365</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊安全功能略過之資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6366">CVE-2014-6366</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是遠端執行程式碼的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer ASLR 略過資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6368">CVE-2014-6368</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊安全功能略過之資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6369">CVE-2014-6369</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是遠端執行程式碼的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6373">CVE-2014-6373</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是遠端執行程式碼的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6374">CVE-2014-6374</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是遠端執行程式碼的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6375">CVE-2014-6375</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是遠端執行程式碼的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6376">CVE-2014-6376</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是遠端執行程式碼的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-8966">CVE-2014-8966</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是遠端執行程式碼的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=519132">MS14-081</a></td>
<td style="border:1px solid black;">無效索引遠端執行程式碼資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6356">CVE-2014-6356</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是遠端執行程式碼的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=519132">MS14-081</a></td>
<td style="border:1px solid black;">釋放後使用 Word 遠端執行程式碼資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6357">CVE-2014-6357</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是遠端執行程式碼的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=519135">MS14-082</a></td>
<td style="border:1px solid black;">Microsoft Office 元件釋放後使用資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6364">CVE-2014-6364</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是遠端執行程式碼的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=519133">MS14-083</a></td>
<td style="border:1px solid black;">Excel 資訊安全風險中的全域可用遠端執行程式碼</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6360">CVE-2014-6360</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是遠端執行程式碼的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=519133">MS14-083</a></td>
<td style="border:1px solid black;">Excel 無效指標遠端執行程式碼資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6361">CVE-2014-6361</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是遠端執行程式碼的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=519131">MS14-084</a></td>
<td style="border:1px solid black;">VBScript 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6363">CVE-2014-6363</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是遠端執行程式碼的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=519129">MS14-085</a></td>
<td style="border:1px solid black;">圖形元件資訊洩漏資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6355">CVE-2014-6355</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊洩漏的資訊安全風險。</td>
</tr>
</tbody>
</table>
  
 
  
受影響的軟體  
------------
  
下表依據主要的軟體類別和嚴重性依序列出公告。
  
請用這些表格來瞭解可能需要安裝的資訊安全更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的資訊安全更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。
  
**注意**：一項資訊安全風險，可能需要安裝數個資訊安全更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
### Windows 作業系統與元件

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-080**](https://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](https://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](https://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3008923)  
(中度)  
Internet Explorer 7  
(3008923)  
(中度)  
Internet Explorer 8  
(3008923)  
(中度)

</td>
<td style="border:1px solid black;">
VBScript 5.6  
(3012168)  
(中度)  
VBScript 5.7  
(3012172)  
(中度)  
VBScript 5.8  
(3012176)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3008923)  
(中度)  
Internet Explorer 7  
(3008923)  
(中度)  
Internet Explorer 8  
(3008923)  
(中度)

</td>
<td style="border:1px solid black;">
VBScript 5.6  
(3012168)  
(中度)  
VBScript 5.7  
(3012172)  
(中度)  
VBScript 5.8  
(3012176)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3008923)  
(中度)  
Internet Explorer 7  
(3008923)  
(中度)

</td>
<td style="border:1px solid black;">
VBScript 5.6  
(3012168)  
(中度)  
VBScript 5.7  
(3012172)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-080**](https://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](https://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](https://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3008923)  
(重大)  
Internet Explorer 8  
(3008923)  
(重大)  
Internet Explorer 9  
(3008923)  
(重大)

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3012172)  
(重大)  
VBScript 5.8  
(僅適用於含有 IE8 的系統)<sup>[1]</sup>
(3012176)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3008923)  
(重大)  
Internet Explorer 8  
(3008923)  
(重大)  
Internet Explorer 9  
(3008923)  
(重大)

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3012172)  
(重大)  
VBScript 5.8  
(僅適用於含有 IE8 的系統)<sup>[1]</sup>
(3012176)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-080**](https://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](https://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](https://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3008923)  
(中度)  
Internet Explorer 8  
(3008923)  
(中度)  
Internet Explorer 9  
(3008923)  
(中度)

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3012172)  
(中度)  
VBScript 5.8  
(僅適用於含有 IE8 的系統)<sup>[1]</sup>
(3012176)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3008923)  
(中度)  
Internet Explorer 8  
(3008923)  
(中度)  
Internet Explorer 9  
(3008923)  
(中度)

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3012172)  
(中度)  
VBScript 5.8  
(僅適用於含有 IE8 的系統)<sup>[1]</sup>
(3012176)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3008923)  
(中度)

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3012172)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-080**](https://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](https://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](https://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3008923)  
(重大)  
Internet Explorer 9  
(3008923)  
(重大)  
Internet Explorer 10  
(3008923)  
(重大)  
Internet Explorer 11  
(3008923)  
(重大)

</td>
<td style="border:1px solid black;">
VBScript 5.8  
(僅適用於含有 IE8 的系統)<sup>[1]</sup>
(3012176)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3008923)  
(重大)  
Internet Explorer 9  
(3008923)  
(重大)  
Internet Explorer 10  
(3008923)  
(重大)  
Internet Explorer 11  
(3008923)  
(重大)

</td>
<td style="border:1px solid black;">
VBScript 5.8  
(僅適用於含有 IE8 的系統)<sup>[1]</sup>
(3012176)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-080**](https://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](https://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](https://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3008923)  
(中度)  
Internet Explorer 9  
(3008923)  
(中度)  
Internet Explorer 10  
(3008923)  
(中度)  
Internet Explorer 11  
(3008923)  
(中度)

</td>
<td style="border:1px solid black;">
VBScript 5.8  
(僅適用於含有 IE8 的系統)<sup>[1]</sup>
(3012176)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3008923)  
(中度)

</td>
<td style="border:1px solid black;">
VBScript 5.8  
(僅適用於含有 IE8 的系統)<sup>[1]</sup>
(3012176)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-080**](https://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](https://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](https://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 32 位元系統

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3008923)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3008923)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3008923)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3008923)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-080**](https://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](https://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](https://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3008923)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3008923)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-080**](https://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](https://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](https://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3008923)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3008923)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Server Core 安裝選項**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-080**](https://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](https://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](https://go.microsoft.com/fwlink/?linkid=519129)

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
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
VBScript 5.7  
(3012172)  
(無嚴重性等級)<sup>[2]</sup>
VBScript 5.8  
(3012176)  
(無嚴重性等級)<sup>[2]</sup>

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3013126)  
(重要)

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
VBScript 5.7  
(3012172)  
(無嚴重性等級)<sup>[2]</sup>
VBScript 5.8  
(3012176)  
(無嚴重性等級)<sup>[2]</sup>

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3013126)  
(重要)

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
VBScript 5.8  
(3012176)  
(無嚴重性等級)<sup>[2]</sup>

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3013126)  
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
(3013126)  
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
(3013126)  
(重要)

</td>
</tr>
</table>
 
**MS14-080 注意事項**

Windows Technical Preview 和 Windows Server Technical Preview 會受影響。建議執行這些作業系統的客戶套用更新，您可以透過 [Windows Update](https://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-tw) 取得更新。

**MS14-084 注意事項**

VBScript 5.8 的更新適用於 Windows Technical Preview 和 Windows Server Technical Preview，並透過 Internet Explorer 積存更新 3008923 ([MS14-080](https://go.microsoft.com/fwlink/?linkid=521659)) 提供。建議執行 Preview 版本的客戶套用更新，您可以透過 [Windows Update](https://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-tw) 取得更新。

<sup>[1]</sup>適用於已安裝 Internet Explorer 8 的系統。系統執行 Internet Explorer 9 或更新版本的客戶應該套用 Internet Explorer 積存更新 ([MS14-080](https://go.microsoft.com/fwlink/?linkid=521659)) (同時解決此公告所討論的資訊安全風險)。

<sup>[2]</sup>對指定的軟體而言，嚴重性等級並不適用，因為 MS14-084 討論之資訊安全風險透過 Internet Explorer 的已知攻擊行為會受到封鎖。不過，Microsoft 仍建議此軟體的客戶套用此資訊安全更新，以做為深度防禦措施，協助防範未來任何可能的新攻擊模式。

 

### Microsoft 伺服器軟體

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-075**](https://go.microsoft.com/fwlink/?linkid=518104)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3  
(2996150)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-075**](https://go.microsoft.com/fwlink/?linkid=518104)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3  
(2986475)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1  
(3011140)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 積存更新 6  
(3011140)  
(重要)

</td>
</tr>
</table>
 
 

### Microsoft Office 套件及軟體

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-081**](https://go.microsoft.com/fwlink/?linkid=519132)

</td>
<td style="border:1px solid black;">
[**MS14-082**](https://go.microsoft.com/fwlink/?linkid=519135)

</td>
<td style="border:1px solid black;">
[**MS14-083**](https://go.microsoft.com/fwlink/?linkid=519133)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Word 2007 Service Pack 3  
(2920793)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2596927)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 Service Pack 3  
(2984942)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-081**](https://go.microsoft.com/fwlink/?linkid=519132)

</td>
<td style="border:1px solid black;">
[**MS14-082**](https://go.microsoft.com/fwlink/?linkid=519135)

</td>
<td style="border:1px solid black;">
[**MS14-083**](https://go.microsoft.com/fwlink/?linkid=519133)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(2899518)  
(重大)  
Microsoft Word 2010 Service Pack 2 (32 位元版本)  
(2899519)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(2553154)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2 (32 位元版本)  
(2910902)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(2899518)  
(重大)  
Microsoft Word 2010 Service Pack 2 (64 位元版本)  
(2899519)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(2553154)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2 (64 位元版本)  
(2910902)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2013 和 Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-081**](https://go.microsoft.com/fwlink/?linkid=519132)

</td>
<td style="border:1px solid black;">
[**MS14-082**](https://go.microsoft.com/fwlink/?linkid=519135)

</td>
<td style="border:1px solid black;">
[**MS14-083**](https://go.microsoft.com/fwlink/?linkid=519133)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 (32 位元版本)  
(2910916)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (32 位元版本)  
(2726958)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 (32 位元版本)  
(2910929)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 Service Pack 1 (32 位元版本)  
(2910916)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 位元版本)  
(2726958)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (32 位元版本)  
(2910929)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 (64 位元版本)  
(2910916)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (64 位元版本)  
(2726958)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 (64 位元版本)  
(2910929)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 Service Pack 1 (64 位元版本)  
(2910916)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 位元版本)  
(2726958)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (64 位元版本)  
(2910929)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 RT  
(2910916)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT  
(2726958)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT  
(2910929)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 RT Service Pack 1  
(2910916)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1  
(2726958)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT Service Pack 1  
(2910929)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-081**](https://go.microsoft.com/fwlink/?linkid=519132)

</td>
<td style="border:1px solid black;">
[**MS14-082**](https://go.microsoft.com/fwlink/?linkid=519135)

</td>
<td style="border:1px solid black;">
[**MS14-083**](https://go.microsoft.com/fwlink/?linkid=519133)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011  
(3018888)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**其他 Office 軟體**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-081**](https://go.microsoft.com/fwlink/?linkid=519132)

</td>
<td style="border:1px solid black;">
[**MS14-082**](https://go.microsoft.com/fwlink/?linkid=519135)

</td>
<td style="border:1px solid black;">
[**MS14-083**](https://go.microsoft.com/fwlink/?linkid=519133)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2920729)  
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
Microsoft Office 相容性套件 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 相容性套件 Service Pack 3  
(2920792)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Office 相容性套件 Service Pack 3  
(2920790)  
(重要)

</td>
</tr>
</table>
 
**MS14-081 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

 

### Microsoft Office Services 和 Web Apps

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-081**](https://go.microsoft.com/fwlink/?linkid=519132)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2899581)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-081**](https://go.microsoft.com/fwlink/?linkid=519132)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2883050)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2883050)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-081**](https://go.microsoft.com/fwlink/?linkid=519132)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 Service Pack 2  
(2910892)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-081**](https://go.microsoft.com/fwlink/?linkid=519132)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(2889851)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(2889851)  
(重要)

</td>
</tr>
</table>
 
**MS14-081 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

 

偵測與部署工具及指南
--------------------

有幾項資源可協助系統管理員部署資訊安全更新。

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，查看是否遺漏資訊安全更新及一般資訊安全設定錯誤的狀況。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 可協助系統管理員散佈資訊安全更新。

應用程式相容性工具組隨附的 Update Compatibility Evaluator 元件可針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

如需上述工具以及其他可使用工具的詳細資訊，請參閱 [IT專業人員的資訊安全工具](https://technet.microsoft.com/zh-tw/security/cc297183)。

感謝
----

Microsoft 了解資訊安全業界所做的努力，其盡責地透露資訊安全風險來協助我們保護客戶。請參閱[感謝](https://technet.microsoft.com/zh-tw/library/security/dn820091.aspx) (英文) 以取得詳細資訊。

其他資訊
--------

### Microsoft Windows 惡意軟體移除工具 (英文)

針對每個月第二個星期二發行的公告，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 及下載中心發行更新版本的 Microsoft Windows 惡意軟體移除工具。不定期資訊安全公告發行不提供更新版本的 Microsoft Windows 惡意軟體移除工具。

### MU、WU 及 WSUS 上的非資訊安全更新

如需在 Windows Update 和 Microsoft Update 上發行的非資訊安全更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](https://support.microsoft.com/kb/894199/zh-tw)：Software Update Services 與 Windows Server Update Services 的說明內容有所變動。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](https://technet.microsoft.com/zh-tw/windowsserver/bb332157.aspx)。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的資訊安全保護，Microsoft 將在每月發行資訊安全更新之前，提前向重要資訊安全軟體提供者提供資訊安全風險資訊。資訊安全軟體提供者可利用此資訊安全風險資訊，透過其資訊安全軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](https://technet.microsoft.com/zh-tw/security/dn467918) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

### 安全性策略與社群

**更新程式管理策略**

[更新管理安全性指南](https://technet.microsoft.com/zh-tw/library/bb466251.aspx) (英文) 提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他資訊安全更新**

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](https://www.microsoft.com/downloads/results.aspx?displaylang=zh-tw&freetext=security%20update)取得，您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。
-   客戶平台的更新可從 [Microsoft Update](https://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-tw) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](https://support.microsoft.com/kb/913086/zh-tw)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](https://technet.microsoft.com/zh-tw/security/cc136632.aspx)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

### 支援

所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](https://go.microsoft.com/fwlink/?linkid=21742)。

IT 專業人員的資訊安全解決方案：[TechNet 資訊安全疑難排解與支援](https://technet.microsoft.com/zh-tw/security/bb980617)

協助保護您的 Windows 電腦免於病毒和惡意軟體攻擊：[病毒解決方案與資訊安全中心](https://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-tw)

您所在國家/地區的當地支援：[國際支援](https://support.microsoft.com/common/international.aspx?ln=zh-tw)

### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

### 日期

-   V1.0 (2014 年 12 月 9 日)：公告摘要發行。

*頁面產生時間：2014-12-04 13:31Z-08:00。*
