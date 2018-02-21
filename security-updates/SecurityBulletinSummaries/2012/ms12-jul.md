---
TOCTitle: 'MS12-JUL'
Title: 2012 年 7 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms12-jul'
ms:contentKeyID: 61237731
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms12-jul(v=Security.10)'
---

2012 年 7 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2012年7月10日 | 更新: 2012年12月18日

**版本:** 5.1

此公告摘要列出 2012 年 7 月份所發行之資訊安全公告。

發行 2012 年 7 月份資訊安全公告之後，此公告摘要將取代原先於 2012 年 7 月 5 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 資訊安全公告預先通知](http://technet.microsoft.com/zh-tw/security/gg309152.aspx)。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術資訊安全通知](http://technet.microsoft.com/zh-tw/security/dd252948.aspx)。

Microsoft 將利用網路廣播於 2012 年 7 月 11 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。[立即註冊參加 7 月份資訊安全公告網路廣播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032518600)。在這個日期後，此網路廣播將可隨選取得。如需更多資訊，請參閱 [Microsoft 資訊安全公告摘要和網路廣播](http://technet.microsoft.com/zh-tw/security/bulletinarchive?y=2012&m=12) (英文)。

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-043"><strong>MS12-043</strong></a></td>
<td style="border:1px solid black;"><strong>Microsoft XML Core Services</strong> <strong>中的資訊安全風險可能會允許遠端執行程式碼</strong> <strong>(2722479)</strong> <br />
<br />
這個資訊安全更新可解決 Microsoft XML Core Services 中一項公開揭露的資訊安全風險。如果使用者使用 Internet Explorer 檢視蓄意製作的網頁，此資訊安全風險可能會允許遠端執行程式碼。攻擊者並無法強迫使用者造訪這類網站， 而是引誘使用者自行前往。一般的做法是設法讓使用者按一下電子郵件或 Instant Messenger 訊息中連往攻擊者網站的連結。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Office、<br />
Microsoft 開發者工具、<br />
Microsoft 伺服器軟體</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-044"><strong>MS12-044</strong></a></td>
<td style="border:1px solid black;"><strong>Internet Explorer</strong> <strong>積存資訊安全更新</strong> <strong>(2719177)</strong> <br />
<br />
本資訊安全更新可解決 Internet Explorer 中兩項未公開報告的資訊安全風險。如果使用者使用 Internet Explorer 檢視蓄意製作的網頁，這些資訊安全風險可能會允許遠端執行程式碼。成功利用這類任一資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-045"><strong>MS12-045</strong></a></td>
<td style="border:1px solid black;"><strong>Microsoft</strong> <strong>Data Access</strong> <strong>Components</strong> <strong>中的資訊安全風險可能會允許遠端執行程式碼</strong> <strong>(2698365)</strong> <br />
<br />
此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果使用者檢視蓄意製作的網頁，此資訊安全風險可能會允許遠端執行程式碼。成功利用此資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-046"><strong>MS12-046</strong></a></td>
<td style="border:1px solid black;"><strong>Visual Basic for Applications</strong> <strong>中的<em>資訊安全風險</em>可能允許遠端執行程式碼</strong> <strong>(2707960)</strong> <br />
<br />
這個資訊安全更新可解決 Microsoft Visual Basic for Applications 中一項已公開揭露的資訊安全風險。如果使用者開啟與蓄意製作之動態連結程式庫 (DLL) 檔案位於相同目錄的合法 Microsoft Office 檔案 (例如 .docx 檔)，則這個資訊安全風險可能會允許遠端執行程式碼。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。如果使用者以系統管理的使用者權限登入，則攻擊者即可取得受影響系統的完整控制權。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft 開發者工具</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-047"><strong>MS12-047</strong></a></td>
<td style="border:1px solid black;"><strong>Windows</strong> <strong>核心模式驅動程式中的資訊安全風險可能會允許權限提高</strong> <strong>(2718523)</strong> <br />
<br />
這個資訊安全更新可解決 Microsoft Windows 中一項公開揭露和一項未公開報告的資訊安全風險。如果攻擊者登入系統並執行蓄意製作的應用程式，則這些資訊安全風險可能允許權限提高。攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-048"><strong>MS12-048</strong></a></td>
<td style="border:1px solid black;"><strong>Windows Shell</strong> <strong>中的資訊安全風險可能會允許遠端執行程式碼</strong> <strong>(2691442)</strong> <br />
<br />
此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果使用者開啟包含蓄意製作之名稱的檔案或目錄，此資訊安全風險可能會允許遠端執行程式碼。成功利用此資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-049"><strong>MS12-049</strong></a></td>
<td style="border:1px solid black;"><strong>TLS</strong> <strong>中的資訊安全風險可能會導致資訊洩漏</strong> <strong>(2655992)</strong> <br />
<br />
此資訊安全更新可解決 TLS 中一項公開揭露的資訊安全風險。如果攻擊者攔截受影響系統所服務的加密網站流量，則此資訊安全風險可能會導致資訊洩漏。未使用 CBC 模式的所有加密套件不受影響。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
資訊洩漏</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-050"><strong>MS12-050</strong></a></td>
<td style="border:1px solid black;"><strong>SharePoint</strong> <strong>中的資訊安全風險可能會允許提高權限</strong> <strong>(2695502)</strong> <br />
<br />
此資訊安全更新可解決 Microsoft SharePoint 和 Windows SharePoint Services 中一項公開揭露的資訊安全風險和五項未公開報告的資訊安全風險。如果使用者點選會將使用者帶到目標 SharePoint 網站之蓄意製作的 URL，則最嚴重的資訊安全風險可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft 伺服器軟體</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-051"><strong>MS12-051</strong></a></td>
<td style="border:1px solid black;"><strong>Microsoft Office for Mac</strong> <strong>中的資訊安全風險可能會允許權限提高</strong> <strong>(2721015)</strong> <br />
<br />
這個資訊安全更新可解決 Microsoft Office for Mac 中一項已公開揭露的資訊安全風險。如果攻擊者將惡意可執行檔放到受影響的系統上，稍後另一名使用者登入並執行該惡意可執行檔，則該資訊安全風險可能會允許權限提高。攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">不需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>
  
資訊安全風險入侵指數  
--------------------
  
<span></span>
下表提供本月所述每個資訊安全風險的利用性評估。資訊安全風險皆根據公告編號和 CVE 編號依序列出。僅包含資訊安全公告中，嚴重性等級為「重大」或「重要」的資訊安全風險。
  
**我該如何使用這個表格？**
  
您可以運用此表格，針對您可能需要安裝的每一項資訊安全更新，瞭解資訊安全風險在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務 (DoS) 的可能性。請根據您特定的組態設定，檢閱下列各項評估，決定部署本月份更新的優先次序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 資訊安全風險索引](http://technet.microsoft.com/security/cc998259.aspx)。
  
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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-043"><strong>MS12-043</strong></a></td>
<td style="border:1px solid black;">MSXML 未初始化的記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1889">CVE-2012-1889</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">此資訊安全風險已經遭到公開揭發。<br />
<br />
Microsoft 已發現少數嘗試利用此資訊安全風險、目標明確的攻擊。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-044"><strong>MS12-044</strong></a></td>
<td style="border:1px solid black;">快取物件遠端執行程式碼資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1522">CVE-2012-1522</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">暫時</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-044"><strong>MS12-044</strong></a></td>
<td style="border:1px solid black;">屬性移除遠端執行程式碼資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1524">CVE-2012-1524</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">暫時</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-045"><strong>MS12-045</strong></a></td>
<td style="border:1px solid black;">ADO 快取大小堆積溢位 RCE 安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1891">CVE-2012-1891</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">暫時</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-046"><strong>MS12-046</strong></a></td>
<td style="border:1px solid black;">Visual Basic for Applications 不安全程式庫載入資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1854">CVE-2012-1854</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">此資訊安全風險已經遭到公開揭發。<br />
<br />
Microsoft 已發現少數嘗試利用此資訊安全風險、目標明確的攻擊。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-047"><strong>MS12-047</strong></a></td>
<td style="border:1px solid black;">鍵盤配置資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1890">CVE-2012-1890</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">暫時</td>
<td style="border:1px solid black;">此資訊安全風險已經遭到公開揭發。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-047"><strong>MS12-047</strong></a></td>
<td style="border:1px solid black;">Win32k 不正確的類型處理資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1893">CVE-2012-1893</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-048"><strong>MS12-048</strong></a></td>
<td style="border:1px solid black;">命令插入資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0175">CVE-2012-0175</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-049"><strong>MS12-049</strong></a></td>
<td style="border:1px solid black;">TLS 通訊協定資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1870">CVE-2012-1870</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">此資訊安全風險已經遭到公開揭發。<br />
<br />
這是一個資訊洩漏的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-050"><strong>MS12-050</strong></a></td>
<td style="border:1px solid black;">HTML 清理資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1858">CVE-2012-1858</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">此資訊安全風險已經遭到公開揭發。<br />
<br />
這是一個資訊洩漏的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-050"><strong>MS12-050</strong></a></td>
<td style="border:1px solid black;">XSS scriptresx.ashx 資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1859">CVE-2012-1859</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-050"><strong>MS12-050</strong></a></td>
<td style="border:1px solid black;">使用者名稱的 SharePoint 指令碼資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1861">CVE-2012-1861</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-050"><strong>MS12-050</strong></a></td>
<td style="border:1px solid black;">SharePoint 反映式清單參數資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1863">CVE-2012-1863</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-051"><strong>MS12-051</strong></a></td>
<td style="border:1px solid black;">Office for Mac 不當資料夾權限資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1894">CVE-2012-1894</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">此資訊安全風險已經遭到公開揭發。</td>
</tr>
</tbody>
</table>
  
受影響的軟體及下載位置  
----------------------
  
<span></span>
下表依據主要的軟體類別和嚴重性依序列出公告。
  
**我該如何使用這些表格？**
  
請用這些表格來瞭解可能需要安裝的資訊安全更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的資訊安全更新。若軟體程式或更新出現在清單中，則相關可用軟體更新也會以超連結方式提供，也會列出軟體更新的嚴重性等級。
  
**注意**：一項資訊安全風險，可能需要安裝數個資訊安全更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
#### Windows 作業系統與元件

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="7">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-043)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-044)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-045)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-048)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-049)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=017f1ed7-eed4-4de3-aca1-93fb25058866)  
(KB2719985)  
(重大)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
(重大)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=017f1ed7-eed4-4de3-aca1-93fb25058866)  
(KB2719985)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Data Access Components 2.8 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=496e93ac-fcce-458f-839b-25ff1ab22fde)  
(KB2698365)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=a4bc78fb-3927-4059-ae1c-35c369e39203)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=405ce29a-7c97-44de-aed9-4c90cbdaaf1b)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=8324496f-aca4-4a86-833d-c22341e71cd3)  
(KB2655992)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=d27bd5e9-a3a6-411e-bc50-2b03d64fb50c)  
(KB2719985)  
(重大)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(重大)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=aaf10833-0487-4026-805b-97543140b1fd)  
(KB2721693)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Data Access Components 2.8 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=64f8d1a4-4a9d-4ee0-8a66-d157d516afb5)  
(KB2698365)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=94029b68-5b7b-4d0e-b175-cfc2b0eba91a)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=36fc4c85-fa93-4c6b-b93a-94460e9ba23b)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5f268365-9c18-4fc7-b11e-b1f19c4a5a2a)  
(KB2655992)  
(重要)
</td>
</tr>
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
[**MS12-043**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-043)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-044)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-045)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-047)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-048)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-049)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=b7321c17-0e8e-4217-8da6-4c270dbfc802)  
(KB2719985)  
(中度)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
(中度)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=3b56ba48-b74c-4681-8e17-715dc5d45e2c)  
(KB2721693)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Data Access Components 2.8 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=465ef3d0-df59-4f73-a06d-49a81286c01f)  
(KB2698365)  
(中度)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d53bd571-ad30-41c7-8c5f-f217097770f5)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1f058336-4a6a-47d0-ad6f-276dc381d1db)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b13e2388-01f3-46bf-97b4-612e2778477a)  
(KB2655992)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=2b24d755-f96f-47d6-b286-2bfd4e278dcc)  
(KB2719985)  
(中度)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(中度)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=aaf10833-0487-4026-805b-97543140b1fd)  
(KB2721693)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Data Access Components 2.8 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d1955b23-5931-4891-9c11-401efcb6c05c)  
(KB2698365)  
(中度)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5f261883-daec-4af3-8bc1-46da9c164de7)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5b6d6227-8695-4ecb-86e1-bb264f954898)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a0bd0591-62f8-40d1-93fa-7f0afc4fc09c)  
(KB2655992)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=eab0f4c6-3f2e-435d-aef7-d9230295ab15)  
(KB2719985)  
(中度)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=77f45630-288e-46dd-8cb7-c59b07a4bde4)  
(KB2721691)  
(中度)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=68eb373e-2c1e-40db-8ad0-0a369a96255b)  
(KB2721693)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Data Access Components 2.8 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e46047d5-9a2d-48c4-b1c8-3db884c25b5c)  
(KB2698365)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=60c57c8b-6d56-42de-ab1e-e4e3258c7818)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=563399b3-cb19-40e9-ba9d-0079032c8cee)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=b91df558-5446-4858-92af-50cfbab27ff5)  
(KB2655992)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-043)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-044)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-045)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-047)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-048)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-049)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=f8ccdb90-66bd-471a-9c78-825d1140b5ac)  
(KB2719985)  
(重大)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
(重大)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=f8ccdb90-66bd-471a-9c78-825d1140b5ac)  
(KB2719985)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=b6a75978-0c11-49fb-8aa7-c47efb3bf4e8)  
(KB2719177)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=0c43c093-296e-4e12-b995-4f9e3f00cbe0)  
(KB2698365)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3c957f8a-8f32-4a12-ade9-10a7e2984e88)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2e9a4aeb-3f34-483c-ba3a-3141164e9e8a)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7286a6e2-9c31-493f-aae3-776f72e85503)  
(KB2655992)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=e8553934-a202-4033-b9c5-27bc4207469d)  
(KB2719985)  
(重大)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(重大)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e8553934-a202-4033-b9c5-27bc4207469d)  
(KB2719985)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=8470af29-68e2-4fd2-bc30-3c9188e65c59)  
(KB2719177)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=4d9b91c9-a412-4344-b934-0d2fbd9526fd)  
(KB2698365)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7300636f-aefd-46bf-a7ba-780d6f939b4f)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=fe8467e2-8b37-4ec2-ba9f-324918f1f045)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c62ec513-887c-4a42-a3cc-3e92631526ed)  
(KB2655992)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-043)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-044)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-045)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-047)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-048)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-049)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=42a869b9-085a-450a-b69e-f634d01075dd)  
(KB2719985)  
(中度)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
(中度)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=42a869b9-085a-450a-b69e-f634d01075dd)  
(KB2719985)  
(中度)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=4009dd66-b6d0-4c14-acde-f52d75d8f9d1)  
(KB2719177)  
(中度)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=a8ed6a19-c128-46e5-ae38-5fa9f843ba0d)  
(KB2698365)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ed201422-7c65-4c20-a825-8cecab1aeebc)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6d873c5a-57dc-4792-942e-124ce1a4ec2b)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=97030267-6b19-46ae-84ce-0bb1f91ab951)  
(KB2655992)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7b2d780-cc92-4f3e-b5a2-9f2ac66b6f1c)  
(KB2719985)  
(中度)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(中度)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7b2d780-cc92-4f3e-b5a2-9f2ac66b6f1c)  
(KB2719985)  
(中度)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=b609981c-fda8-4085-ae8d-5b760ad4e73f)  
(KB2719177)  
(中度)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=043464e4-9572-419b-a03a-ca11bf918052)  
(KB2698365)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8e1a27c9-6495-4030-8a46-264afd78a5a1)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d49e3e7e-910a-4069-b0b0-0987bb9fdde2)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8a5f6e84-5e5b-42c3-a5b7-65defdb0665f)  
(KB2655992)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=359a86d6-e94a-4de5-83d9-6b0273115bff)  
(KB2719985)  
(中度)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=77f45630-288e-46dd-8cb7-c59b07a4bde4)  
(KB2721691)  
(中度)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=359a86d6-e94a-4de5-83d9-6b0273115bff)  
(KB2719985)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=00638d5e-6156-4c1b-a131-3d1fff514bdb)  
(KB2698365)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=76f640b8-5aab-4880-9d74-22e2a5086342)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ca890b4d-124f-4293-b8d0-69f6302b5189)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e886c5f4-7f38-4c90-905b-a682e6a8ffd0)  
(KB2655992)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-043)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-044)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-045)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-047)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-048)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-049)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=d8a4817c-481c-4ed2-980a-21623f0ca6d2)  
(KB2719985)  
(重大)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
(重大)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=d8a4817c-481c-4ed2-980a-21623f0ca6d2)  
(KB2719985)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=0be922a4-6b8a-4017-bc31-1cadd8cdb472)  
(KB2719177)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=ed997ae7-2e45-4620-bcbe-a5006aaca448)  
(KB2698365)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=b4bed780-b120-43a1-900e-89b3be7da8b1)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=8ab3eadf-9437-4323-8323-87dfd23245fd)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=da706b4e-7c22-4929-96d3-f8b0fa10f043)  
(KB2655992)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=d8a4817c-481c-4ed2-980a-21623f0ca6d2)  
(KB2719985)  
(重大)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
(重大)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=d8a4817c-481c-4ed2-980a-21623f0ca6d2)  
(KB2719985)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=0be922a4-6b8a-4017-bc31-1cadd8cdb472)  
(KB2719177)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=ed997ae7-2e45-4620-bcbe-a5006aaca448)  
(KB2698365)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=b4bed780-b120-43a1-900e-89b3be7da8b1)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=8ab3eadf-9437-4323-8323-87dfd23245fd)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=da706b4e-7c22-4929-96d3-f8b0fa10f043)  
(KB2655992)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=e1962879-1725-4d60-933f-eb351bee56bc)  
(KB2719985)  
(重大)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(重大)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e1962879-1725-4d60-933f-eb351bee56bc)  
(KB2719985)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=739e4f24-8433-4dc9-a106-a70ae4040606)  
(KB2719177)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=4040c290-bf41-4e14-8269-da95ee06d8e7)  
(KB2698365)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=3efb0de1-252b-4b72-86f3-e747f8fa2229)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=f518f273-b3b9-4cbf-b820-05a1adc79342)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=07518fb7-031f-4fa0-836c-8f33c247868b)  
(KB2655992)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=e1962879-1725-4d60-933f-eb351bee56bc)  
(KB2719985)  
(重大)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(重大)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e1962879-1725-4d60-933f-eb351bee56bc)  
(KB2719985)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=739e4f24-8433-4dc9-a106-a70ae4040606)  
(KB2719177)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=4040c290-bf41-4e14-8269-da95ee06d8e7)  
(KB2698365)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3efb0de1-252b-4b72-86f3-e747f8fa2229)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=f518f273-b3b9-4cbf-b820-05a1adc79342)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=07518fb7-031f-4fa0-836c-8f33c247868b)  
(KB2655992)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-043)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-044)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-045)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-047)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-048)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-049)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=f75a3d2d-8322-40a6-b735-faeb8b4873b6)  
(KB2719985)  
(中度)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(中度)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=f75a3d2d-8322-40a6-b735-faeb8b4873b6)  
(KB2719985)  
(中度)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=91e8ecf8-4f6d-4e86-bc6b-617749090190)  
(KB2719177)  
(中度)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e749883d-221a-411a-9c85-759d50cefa9d)  
(KB2698365)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=73a9ff32-4009-4fd4-a82b-1e22c09d3087)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=d16fa6b9-43aa-4d0f-a230-52664e972ab9)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=c9ef728f-abef-4076-bb13-7488af471aa4)  
(KB2655992)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=f75a3d2d-8322-40a6-b735-faeb8b4873b6)  
(KB2719985)  
(中度)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(中度)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=f75a3d2d-8322-40a6-b735-faeb8b4873b6)  
(KB2719985)  
(中度)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=91e8ecf8-4f6d-4e86-bc6b-617749090190)  
(KB2719177)  
(中度)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e749883d-221a-411a-9c85-759d50cefa9d)  
(KB2698365)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=73a9ff32-4009-4fd4-a82b-1e22c09d3087)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d16fa6b9-43aa-4d0f-a230-52664e972ab9)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=c9ef728f-abef-4076-bb13-7488af471aa4)  
(KB2655992)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=a745388e-9fef-412e-8d00-9195af506cf5)  
(KB2719985)  
(中度)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=77f45630-288e-46dd-8cb7-c59b07a4bde4)  
(KB2721691)  
(中度)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=a745388e-9fef-412e-8d00-9195af506cf5)  
(KB2719985)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=eeab7dbb-f6ca-44bd-a172-c07fc5803fd6)  
(KB2698365)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=772f2975-065d-44f3-adf8-82188bd43196)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=c9c3b471-4a81-4a44-93ad-674650454c53)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=49e182b5-4499-42a1-8180-9bb920e154cb)  
(KB2655992)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=a745388e-9fef-412e-8d00-9195af506cf5)  
(KB2719985)  
(中度)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=77f45630-288e-46dd-8cb7-c59b07a4bde4)  
(KB2721691)  
(中度)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=a745388e-9fef-412e-8d00-9195af506cf5)  
(KB2719985)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=eeab7dbb-f6ca-44bd-a172-c07fc5803fd6)  
(KB2698365)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=772f2975-065d-44f3-adf8-82188bd43196)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=c9c3b471-4a81-4a44-93ad-674650454c53)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=49e182b5-4499-42a1-8180-9bb920e154cb)  
(KB2655992)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-043)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-044)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-045)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-047)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-048)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-049)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
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
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 8
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
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
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-043)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-044)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-045)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-047)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-048)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-049)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
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
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="7">
Server Core 安裝選項
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-043)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-044)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-045)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-047)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-048)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-049)
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
無
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2
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
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ed201422-7c65-4c20-a825-8cecab1aeebc)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6d873c5a-57dc-4792-942e-124ce1a4ec2b)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=97030267-6b19-46ae-84ce-0bb1f91ab951)  
(KB2655992)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2
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
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8e1a27c9-6495-4030-8a46-264afd78a5a1)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d49e3e7e-910a-4069-b0b0-0987bb9fdde2)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8a5f6e84-5e5b-42c3-a5b7-65defdb0665f)  
(KB2655992)  
(重要)
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
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=73a9ff32-4009-4fd4-a82b-1e22c09d3087)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=d16fa6b9-43aa-4d0f-a230-52664e972ab9)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=c9ef728f-abef-4076-bb13-7488af471aa4)  
(KB2655992)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1
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
[適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=73a9ff32-4009-4fd4-a82b-1e22c09d3087)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d16fa6b9-43aa-4d0f-a230-52664e972ab9)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=c9ef728f-abef-4076-bb13-7488af471aa4)  
(KB2655992)  
(重要)
</td>
</tr>
</table>
 
**MS12-043** **注意事項**

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

#### Microsoft Office 套件及軟體

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="5">
Microsoft Office 套件和元件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-043)
</td>
<td style="border:1px solid black;">
[**MS12-046**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-046)
</td>
<td style="border:1px solid black;">
[**MS12-050**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-050)
</td>
<td style="border:1px solid black;">
[**MS12-051**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-051)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=c4c925b8-df99-4d4f-b939-878d77d64514)  
(KB2687627)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=d49c4893-d867-4d16-90f5-354eb4757d90)<sup>[1]</sup>
(KB2687626)  
(重要)
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
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=181bbd45-9128-4c26-af1e-fadfd83ff756)<sup>[1]</sup>
(KB2596744)  
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
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=181bbd45-9128-4c26-af1e-fadfd83ff756)<sup>[1]</sup>
(KB2596744)  
(重要)
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
Microsoft Office 2010 (32 位元版本)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 (32 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=a7cc8fdc-1c64-434f-87a6-72ddcc356654)  
(KB2598243)  
(重要)  
[Microsoft Office 2010 (32 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=3050c06c-3cfc-4ce7-83cd-017d0922d597)  
(KB2553447)  
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
Microsoft Office 2010 Service Pack 1 (32 位元版本)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 Service Pack 1 (32 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=a7cc8fdc-1c64-434f-87a6-72ddcc356654)  
(KB2598243)  
(重要)  
[Microsoft Office 2010 Service Pack 1 (32 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=3050c06c-3cfc-4ce7-83cd-017d0922d597)  
(KB2553447)  
(重要)
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
Microsoft Office 2010 (64 位元版本)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 (64 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=ab442918-8184-4c7c-84b0-5a3635fdb005)  
(KB2598243)  
(重要)  
[Microsoft Office 2010 (64 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=0a8af868-abf7-4aeb-813a-418a04b31608)  
(KB2553447)  
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
Microsoft Office 2010 Service Pack 1 (64 位元版本)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 Service Pack 1 (64 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=ab442918-8184-4c7c-84b0-5a3635fdb005)  
(KB2598243)  
(重要)  
[Microsoft Office 2010 Service Pack 1 (64 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=0a8af868-abf7-4aeb-813a-418a04b31608)  
(KB2553447)  
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
<th colspan="5">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-043)
</td>
<td style="border:1px solid black;">
[**MS12-046**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-046)
</td>
<td style="border:1px solid black;">
[**MS12-050**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-050)
</td>
<td style="border:1px solid black;">
[**MS12-051**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-051)
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
無
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
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
[Microsoft Office for Mac 2011](http://www.microsoft.com/downloads/details.aspx?familyid=877700ed-3d03-4d46-a77b-5063d8f7d2e3)  
(KB2721015)  
(重要)
</td>
</tr>
<tr>
<th colspan="5">
其他 Microsoft Office 軟體
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-043)
</td>
<td style="border:1px solid black;">
[**MS12-046**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-046)
</td>
<td style="border:1px solid black;">
[**MS12-050**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-050)
</td>
<td style="border:1px solid black;">
[**MS12-051**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-051)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Word Viewer
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
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
Microsoft Office 相容性套件 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
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
<td style="border:1px solid black;">
Microsoft Office 相容性套件 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
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
Microsoft Groove 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6)  
(KB2687497)(重大)
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
Microsoft Groove 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6)  
(KB2687497)(重大)
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
Microsoft InfoPath 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=da8fa3b6-5d01-49e1-a1ce-e3f47ace102b)  
(KB2596666)  
(重要)  
[Microsoft InfoPath 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a0c826bc-aef8-4833-8471-1824a405c59f)  
(KB2596786)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft InfoPath 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2007 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=da8fa3b6-5d01-49e1-a1ce-e3f47ace102b)  
(KB2596666)  
(重要)  
[Microsoft InfoPath 2007 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=a0c826bc-aef8-4833-8471-1824a405c59f)  
(KB2596786)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft InfoPath 2010 (32 位元版本)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 (32 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=698e6369-253b-4dbe-b6cd-7ea5ea09e043)  
(KB2553431)  
(重要)  
[Microsoft InfoPath 2010 (32 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=036b2482-0fb4-46f0-9c38-8bae6d0d669b)  
(KB2553322)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft InfoPath 2010 Service Pack 1 (32 位元版本)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 Service Pack 1 (32 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=698e6369-253b-4dbe-b6cd-7ea5ea09e043)  
(KB2553431)  
(重要)  
[Microsoft InfoPath 2010 Service Pack 1 (32 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=036b2482-0fb4-46f0-9c38-8bae6d0d669b)  
(KB2553322)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft InfoPath 2010 (64 位元版本)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 (64 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=3bf373aa-b4ad-4e1a-9578-800485ece148)  
(KB2553431)  
(重要)  
[Microsoft InfoPath 2010 (64 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=e24337cb-83b4-424f-bc4d-0d43437228a2)  
(KB2553322)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft InfoPath 2010 Service Pack 1 (64 位元版本)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 Service Pack 1 (64 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=3bf373aa-b4ad-4e1a-9578-800485ece148)  
(KB2553431)  
(重要)  
[Microsoft InfoPath 2010 Service Pack 1 (64 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=e24337cb-83b4-424f-bc4d-0d43437228a2)  
(KB2553322)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
</table>
 
**MS12-043** **注意事項**

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

**MS12-046** **注意事*項***

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

<sup>[1]</sup>這些 Microsoft Office 更新適用於所有受支援的 Microsoft Office 套件，以及其他含有易受影響之共用 Office 元件的 Microsoft Office 軟體。這些軟體包括 (但不限於) 受支援版本的 Microsoft Visio 和 Microsoft Project。

**MS12-050** **注意事項**

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

#### Microsoft 伺服器軟體

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="3">
Microsoft Office SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-043)
</td>
<td style="border:1px solid black;">
[**MS12-050**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-050)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 2 (32 位元版本)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6)  
(KB2687497)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 2 (coreserver) (32 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=4073d6e1-32f0-44a8-ae55-3c140ebc09d2)<sup>[1]</sup>
(KB2596663)  
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (xlsrvwfe) (32 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=d9091923-67c7-4535-b44c-40a5292a94d9)<sup>[1]</sup>
(KB2596942)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 3 (32 位元版本)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6)  
(KB2687497)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 3 (coreserver) (32 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=4073d6e1-32f0-44a8-ae55-3c140ebc09d2)<sup>[1]</sup>
(KB2596663)  
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 3 (xlsrvwfe) (32 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=d9091923-67c7-4535-b44c-40a5292a94d9)<sup>[1]</sup>
(KB2596942)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 2 (64 位元版本)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 2 (coreserver) (64 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=b1acb373-0041-4883-8834-90a72ac04c91)<sup>[1]</sup>
(KB2596663)  
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (xlsrvwfe) (64 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=723a5553-8610-49bf-99c0-bd94926bdc0b)<sup>[1]</sup>
(KB2596942)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 3 (64 位元版本)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 3 (coreserver) (64 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=b1acb373-0041-4883-8834-90a72ac04c91)<sup>[1]</sup>
(KB2596663)  
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (xlsrvwfe) (64 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=723a5553-8610-49bf-99c0-bd94926bdc0b)<sup>[1]</sup>
(KB2596942)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2010 (wosrv)](http://www.microsoft.com/downloads/details.aspx?familyid=59cbb3d0-4ba5-4f89-b54c-ae9aa2aa3b41)  
(KB2553424)  
(重要)  
[Microsoft SharePoint Server 2010 (coreserverloc)](http://www.microsoft.com/downloads/details.aspx?familyid=8a853489-a3ec-4be2-8093-6a992f9c8368)  
(KB2553194)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2010 Service Pack 1 (wosrv)](http://www.microsoft.com/downloads/details.aspx?familyid=59cbb3d0-4ba5-4f89-b54c-ae9aa2aa3b41)  
(KB2553424)  
(重要)  
[Microsoft SharePoint Server 2010 Service Pack 1 (coreserverloc)](http://www.microsoft.com/downloads/details.aspx?familyid=8a853489-a3ec-4be2-8093-6a992f9c8368)  
(KB2553194)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Groove Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-043)
</td>
<td style="border:1px solid black;">
[**MS12-050**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-050)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Groove Server 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Groove Server 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Groove Server 2010
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Groove Server 2010](http://www.microsoft.com/downloads/details.aspx?familyid=e2346078-fc93-4355-bc83-0d0dc1cd4b2f)  
(KB2589325)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Groove Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Groove Server 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=e2346078-fc93-4355-bc83-0d0dc1cd4b2f)  
(KB2589325)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows SharePoint Services 和 Microsoft SharePoint Foundation
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-043)
</td>
<td style="border:1px solid black;">
[**MS12-050**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-050)
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
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 2.0
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 2.0](http://www.microsoft.com/downloads/details.aspx?familyid=7a54f510-0782-44c4-848a-8ef90d332e61)<sup>[2]</sup>
(KB2760604)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 2 (32 位元版本)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 Service Pack 2 (32 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=61b9f234-3d9c-41d4-854d-30ca5e6fd2a6)  
(KB2596911)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 2 (64 位元版本)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 Service Pack 2 (64 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=24265175-635f-4846-afcc-f692d4710707)  
(KB2596911)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010](http://www.microsoft.com/downloads/details.aspx?familyid=4d610646-a0bd-492c-9077-fb2c92588c14)  
(KB2553365)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=4d610646-a0bd-492c-9077-fb2c92588c14)  
(KB2553365)  
(重要)
</td>
</tr>
</table>
 
**MS12-043** **注意事項**

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

**MS12-050注意事項**

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

<sup>[1]</sup>對於支援的 Microsoft Office SharePoint Server 2007 版本，除了安裝適用於 Microsoft Office SharePoint 2007 的資訊安全更新套件外 (KB2596663 和 KB2596942)，客戶還需安裝適用於 Microsoft Windows SharePoint Services 3.0 的資訊安全更新 (KB2596911)，以避免受本公告中所述的資訊安全風險影響。

<sup>[2]</sup>這個更新程式只能從 Microsoft 下載中心取得。

#### Microsoft Office Web Apps

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Office Web Apps
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS12-050**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-050)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps 2010](http://www.microsoft.com/downloads/details.aspx?familyid=f2d1c371-d617-4792-966e-14ae9ed6b8a1)  
(KB2598239)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=f2d1c371-d617-4792-966e-14ae9ed6b8a1)  
(KB2598239)
</td>
</tr>
</table>
 
**MS12-050** **注意事項**

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

#### Microsoft 開發者工具和軟體

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="3">
Microsoft Expression Web
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-043)
</td>
<td style="border:1px solid black;">
[**MS12-046**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-046)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Expression Web Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Expression Web 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Visual Basic for Applications
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-043)
</td>
<td style="border:1px solid black;">
[**MS12-046**](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-046)
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
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Basic for Applications
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Visual Basic for Applications](http://www.microsoft.com/downloads/details.aspx?familyid=ea7c5762-586f-4e38-ad63-43eb05e79f4d)<sup>[1]</sup>
(KB2688865)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Basic for Applications SDK
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
Microsoft Visual Basic for Applications SDK<sup>[2]</sup><sup>[3]</sup>
(重要)
</td>
</tr>
</table>
 
**MS12-043** **注意事項**

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

**MS12-046** **注意事*項***

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

<sup>[1]</sup>此更新套件適用於支援版本的 Microsoft Visual Basic for Applications Runtime (Vbe6.dll)，僅可以從 Microsoft 下載中心取得。

<sup>[2]</sup>支援的 VBA SDK 版本包含 Microsoft Visual Basic for Applications SDK 6.3、Microsoft Visual Basic for Applications SDK 6.4 及 Microsoft Visual Basic for Applications SDK 6.5。

<sup>[3]</sup>可解決本公告描述之資訊安全風險的 Visual Basic for Applications SDK 更新版本目前由 Summit Software Company 開放給獨立軟體廠商 (ISV)。

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和資訊安全更新。如需更多資訊，請參閱 [TechNet 更新管理中心](http://technet.microsoft.com/zh-tw/updatemanagement/default.aspx) (英文)。[TechNet 資訊安全技術中心](http://technet.microsoft.com/zh-tw/security/default.aspx)提供 Microsoft 產品資訊安全的其他資訊。消費者可以造訪[在家上網的安全性](http://technet.microsoft.com/zh-tw/security/default.aspx)網站，只要按一下 \[最新資訊安全更新\] 即可在此網站取得此資訊。

資訊安全更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 以及 [Windows Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-hk) 取得。資訊安全更新也可以從 [Microsoft 下載中心](http://www.microsoft.com/zh-tw/download/search.aspx?q=security%20update)取得。您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。

對於 Microsoft Office for Mac 的客戶，Microsoft AutoUpdate for Mac 可協助您保持最新的 Microsoft 軟體。如需使用 Microsoft AutoUpdate for Mac 的詳細資訊，請參閱[自動檢查軟體更新](http://mac2.microsoft.com/help/office/14/zh-tw/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea) (英文)。

最後，您可以從 [Microsoft Update Catalog](http://catalog.update.microsoft.com/v7/site/install.aspx) 下載資訊安全更新。Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括資訊安全更新、驅動程式和 Service Pack。只要以資訊安全公告編號 (例如：MS07-036) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](http://catalog.update.microsoft.com/v7/site/faq.aspx)。

**偵測與部署指南**

Microsoft 針對資訊安全更新提供偵測和部署指南。本指南所含之建議和資訊，能幫助 IT 專業人員瞭解如何使用用於資訊安全更新的偵測和部署的各種工具。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 961747](http://support.microsoft.com/kb/961747?ln=zh-tw)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少資訊安全更新以及一般資訊安全設定錯誤的狀況。如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](http://technet.microsoft.com/zh-tw/security/cc184924.aspx)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速而可靠地將 Microsoft Windows 2000 作業系統及更新版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 適用的最新重大更新與資訊安全更新部署到 Microsoft Windows 2000 及更新版本的作業系統中。

如需更多關於利用 Windows Server Update Services 部署資訊安全更新的資訊，請造訪 [Windows Server Update Services](http://technet.microsoft.com/zh-tw/wsus/default.aspx) (英文)。

**System Center** **Configuration Manager**

System Center Configuration Manager 軟體更新管理可簡化遞送和管理企業中 IT 系統更新的繁複作業。IT 系統管理員可以使用 System Center Configuration Manager 遞送 Microsoft 產品更新給各種裝置，包括桌上型電腦、筆記型電腦、伺服器及行動裝置。

System Center Configuration Manager 中的自動資訊安全風險評估會找出更新需求並報告建議動作。System Center Configuration Manager 中的軟體更新管理是建置在 Microsoft Windows Software Update Services (WSUS) 上，經過時間考驗，為全球 IT 系統管理員所熟悉的更新基礎架構。如需更多有關系統管理員如何使用 System Center Configuration Manager 來部署更新的資訊，請參閱[軟體更新管理](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx) (英文)。如需更多有關 System Center Configuration Manager 的資訊，請造訪 [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx)。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。透過 SMS，系統管理員能判斷有哪些 Windows 系統需要資訊安全更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。

**注意：**System Management Server 2003 自 2010 年 1 月 12 日起不受主流支援。如需更多有關產品生命週期的資訊，請造訪 [Microsoft 支援週期](http://support.microsoft.com/common/international.aspx?rdpath=dm;zh-tw;lifecycle?ln=zh-tw)。現已推出新版的 SMS，System Center Configuration Manager；請參閱前段的＜System Center Configuration Manager＞一節。

如需更多有關系統管理員如何使用 SMS 2003 來部署資訊安全更新的資訊，請參閱 [Microsoft Systems Management Server 2003 的案例與程序： 軟體發佈和補充程式管理](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en) (英文)。如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server 技術中心 (TechCenter)](http://technet.microsoft.com/zh-tw/systemcenter/bb545936.aspx)。

**注意**：SMS 使用 Microsoft Baseline Security Analyzer 提供廣泛的資訊安全公告更新偵測與部署支援。不過這些工具可能無法偵測部分的軟體更新。在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](http://technet.microsoft.com/zh-tw/library/cc917507.aspx) (英文)。某些資訊安全更新程式在電腦重新啟動之後，會需要系統管理員的權限。系統管理員可使用 Elevated Rights Deployment Tool (隨附於 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)) 來安裝這些更新。

**Update Compatibility Evaluator** **和** **Application Compatibility Toolkit**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。這可能會觸發不相容性，而拉長部署資訊安全更新的時間。您可以使用 [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 隨附的 [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 元件，針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Windows Vista、Windows Update、Microsoft 資訊安全更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非資訊安全更新

如需在 Windows Update 和 Microsoft Update 上發行的非資訊安全更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](http://support.microsoft.com/kb/894199?ln=zh-tw)
-   ： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](http://technet.microsoft.com/zh-tw/wsus/bb456965.aspx)
-   。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的資訊安全保護，Microsoft 將在每月發行資訊安全更新之前，提前向重要資訊安全軟體提供者提供資訊安全風險資訊。資訊安全軟體提供者可利用此資訊安全風險資訊，透過其資訊安全軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://www.microsoft.com/security/msrc/collaboration/mapp.aspx) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 資訊安全策略與社群

**更新程式管理策略**

[更新管理資訊安全指南](http://technet.microsoft.com/zh-tw/library/bb466251(zh-tw).aspx) (英文) 提供您有關套用資訊安全更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他資訊安全更新**

其他資訊安全問題的更新可由下列位置取得：

-   資訊安全更新可以從 [Microsoft 下載中心](http://www.microsoft.com/zh-tw/download/search.aspx?q=security%20update)取得， 您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。
-   消費性平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以資訊安全和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的資訊安全更新。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](http://support.microsoft.com/kb/913086?ln=zh-tw)。

**IT** **專業人員資訊安全社群**

在 [IT 專業人員資訊安全社群](http://technet.microsoft.com/zh-tw/security/cc136632.aspx)上，學習如何提升資訊安全以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類資訊安全議題的討論。

#### 感謝

Microsoft [感謝](http://technet.microsoft.com/zh-tw/security/gg309157.aspx)下列人士協助我們一同保護我們的客戶：

-   感謝 [Google Security Team](http://www.google.com/) 與我們合作解決 MS12-043 中描述的問題
-   感謝 [Qihoo 360 Security Center](http://www.360.cn/) 回報 MS12-043 中描述的一項問題
-   感謝 spa-s3c.blogspot.com 的 Jose A. Vazquez 與 [VeriSign iDefense Labs](http://labs.idefense.com/) 合作，回報 MS12-044 中描述的一項問題
-   感謝 Omair 與 [VeriSign iDefense Labs](http://labs.idefense.com/) 合作，回報 MS12-044 中描述的一項問題
-   感謝匿名的研究人員與 [TippingPoint](http://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 MS12-045 中描述的一項問題
-   感謝 [Huawei Security Labs](http://www.huawei.com/) 的 Bai Haowen 回報 MS12-046 中描述的一項問題
-   感謝 [Core Security Technologies](http://www.coresecurity.com/) 的 Nicolas Economou 回報 MS12-047 中描述的一項問題
-   感謝 [Qihoo 360 Security Center](http://www.360.cn/) 回報 MS12-047 中描述的一項問題
-   感謝 Neusoft Corporation 的 Lufeng Li 與 [Secunia Research](http://secunia.com/) 合作，回報 MS12-047 中描述的一項問題
-   感謝 [IBM Security Systems - Application Security](http://blog.watchfire.com/) 的 Adi Cohen 回報 MS12-048 中描述的一項問題
-   感謝 [IBM Security Systems - Application Security](http://blog.watchfire.com/) 的 Adi Cohen 回報 MS12-050 中描述的一項問題
-   感謝 [Salesforce.com Product Security 團隊](https://trust.salesforce.com/)的 Yang Yang 回報 MS12-050 中描述的一項問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 支援週期](http://support.microsoft.com/default.aspx?scid=fh;%5bln%5d;lifecycle)。
-   IT 專業人員的資訊安全解決方案： [TechNet 資訊安全疑難排解與支援](http://technet.microsoft.com/security/bb980617.aspx)
-   協助保護您的 Widows 電腦免於病毒和惡意軟體攻擊： [病毒解決方案與資訊安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-tw)
-   您所在國家/地區的當地支援： [國際支援](http://support.microsoft.com/common/international.aspx?ln=zh-tw)

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2012 年 7 月 10 日)： 公告摘要發行。
-   V1.1 (2012 年 7 月 10 日)： 從＜資訊安全風險入侵指數＞中移除 CVE-2012-1860，因為此資訊安全風險的嚴重性等級為「中度」。＜資訊安全風險入侵指數＞僅包含資訊安全公告中嚴重性等級為「重大」或「重要」的資訊安全風險。
-   V2.0 (2012 年 8 月 15 日)： 針對 MS12-043 新增 Microsoft XML Core Services 5.0 的下載連結。
-   V3.0 (2012 年 10 月 9 日)： 針對 MS12-043，新增安裝於受支援版本之 Windows 8 和 Windows Server 2012 上的 Microsoft XML Core Services 4.0 至受影響的軟體。請參閱 MS12-043 公告以瞭解詳細資訊。
-   V4.0 (2012 年 11 月 13 日)： 針對 MS12-046，以適用於 Microsoft Office 2003 Service Pack 3 的更新取代 KB2598361 更新。請參閱 MS12-046 公告，以取得詳細資料。
-   V5.0 (2012 年 12 月 12 日)： 在 MS12-043 中，針對 Microsoft Office 2003 Service Pack 3 上安裝的 Microsoft XML Core Services 5.0，以 KB2687627 更新取代 KB2687324 更新，而針對所有受影響版本之 Microsoft Groove 2007、Microsoft Groove Server 2007 及 Microsoft Office SharePoint Server 2007 上安裝的 Microsoft XML Core Services 5.0，以 KB2687497 更新取代 KB2596679 更新。詳細資料請參閱 MS12-043 公告。
-   V5.1 (2012 年 12 月 18 日)： 針對 MS12-050 修訂公告摘要，宣佈提供 Microsoft Windows SharePoint Services 2.0 的一項更新。這個更新程式只能從 Microsoft 下載中心取得。

*Built at 2014-04-18T01:50:00Z-07:00*
