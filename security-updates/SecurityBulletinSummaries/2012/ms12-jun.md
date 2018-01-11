---
TOCTitle: 'MS12-JUN'
Title: 2012 年 6 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms12-jun'
ms:contentKeyID: 61237732
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms12-jun(v=Security.10)'
---

2012 年 6 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2012年6月13日

**版本:** 1.0

此公告摘要列出 2012 年 6 月份所發行之資訊安全公告。

發行 2012 年 6 月份資訊安全公告之後，此公告摘要將取代原先於 2012 年 6 月 7 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 資訊安全公告預先通知](http://technet.microsoft.com/zh-tw/security/gg309152.aspx)。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術資訊安全通知](http://technet.microsoft.com/zh-tw/security/dd252948.aspx)。

Microsoft 將利用網路廣播於 2012 年 6 月 13 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。立即註冊參加 6 月份資訊安全公告網路廣播。在這個日期後，此網路廣播將可隨選取得。如需更多資訊，請參閱 [Microsoft 資訊安全公告摘要和網路廣播](http://technet.microsoft.com/zh-tw/security/bulletinarchive?y=2012&m=6) (英文)。

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-036">MS12-036</a></td>
<td style="border:1px solid black;">遠端桌面中的資訊安全風險可能會允許遠端執行程式碼 (2685939) <br />
<br />
此資訊安全更新可解決遠端桌面通訊協定中一項未公開報告的資訊安全風險。如果攻擊者傳送蓄意製作的 RDP 封包序列到受影響的系統，則此資訊安全風險可能會允許遠端執行程式碼。依據預設，所有 Windows 作業系統上均未啟用遠端桌面通訊協定 (RDP)。未啟用的 RDP 的系統則無風險。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-037">MS12-037</a></td>
<td style="border:1px solid black;">Internet Explorer 積存資訊安全更新 (2699988) <br />
<br />
此資訊安全更新可解決 Internet Explorer 中一項公開揭露的資訊安全風險和十二項未公開報告的資訊安全風險。最嚴重的資訊安全風險可能會在使用者以 Internet Explorer 檢視蓄意製作的網頁時，允許遠端執行程式碼。成功利用這類任一資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-038">MS12-038</a></td>
<td style="border:1px solid black;">.NET Framework 中的資訊安全風險可能會允許遠端執行程式碼 (2706726) <br />
<br />
這個資訊安全更新可解決 Microsoft .NET Framework 中一項未公開報告的資訊安全風險。如果使用者使用可執行 XAML 瀏覽器應用程式 (XBAP) 的網頁瀏覽器檢視蓄意製作的網頁，此資訊安全風險就可能允許在用戶端系統上遠端執行程式碼。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。Windows .NET 應用程式也可能使用這個資訊安全風險，以略過程式碼存取安全性 (CAS) 限制。在網頁瀏覽攻擊的案例中，攻擊者可架設一個網站，並在其中包含用來利用此資訊安全風險的網頁。此外，受侵害的網站以及接受或存放使用者提供之內容或廣告的網站裡，也可能包含蓄意製作以利用本資訊安全風險的內容。但是，在所有情況下，攻擊者無法強迫使用者造訪這類網站， 而是引誘使用者自行前往。一般的做法是設法讓使用者按一下電子郵件或 Instant Messenger 訊息中連往攻擊者網站的連結。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-039">MS12-039</a></td>
<td style="border:1px solid black;"><strong><em>Lync</em></strong> 中的<strong><em>資訊安全風險</em><em></em></strong>可能會允許遠端執行程式碼 (2707956) <br />
<br />
此資訊安全更新可解決 Microsoft Lync 中一項公開揭露的資訊安全風險和三項未公開報告的資訊安全風險。最嚴重的資訊安全風險可能會在使用者檢視包含蓄意製作的 TrueType 字型之共用內容時，允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Lync</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-040">MS12-040</a></td>
<td style="border:1px solid black;">在 Microsoft Dynamics AX Enterprise Portal 中的資訊安全風險可能會允許權限提高 (2709100) <br />
<br />
這個資訊安全更新可解決 Microsoft Dynamics AX Enterprise Portal 中一項未公開報告的資訊安全風險。如果使用者點選蓄意製作的 URL 或造訪蓄意製作的網站，則此資訊安全風險可能會允許權限提高。若是電子郵件攻擊，攻擊者可能會將包含蓄意製作的 URL 之電子郵件訊息傳送給目標 Microsoft Dynamics AX Enterprise Portal 網站的使用者，並引誘使用者點選蓄意製作的 URL，以利用這項資訊安全風險。瀏覽至網際網路區域中的 Microsoft Dynamics AX Enterprise Portal 網站之 Internet Explorer 8 和 Internet Explorer 9 使用者，存在最高風險。依照預設，Internet Explorer 8 和 Internet Explorer 9 中的 XSS 篩選器可在網際網路區域中防止此類攻擊。然而，針對內部網路區域並不會啟用 Internet Explorer 8 和 Internet Explorer 9 中的 XSS 篩選器。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Dynamics AX</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-041">MS12-041</a></td>
<td style="border:1px solid black;">Windows 核心模式驅動程式中的資訊安全風險可能會允許權限提高 (2709162) <br />
<br />
這個資訊安全更新可解決 Microsoft Windows 中五個未公開報告的資訊安全風險。如果攻擊者登入系統並執行蓄意製作的應用程式，則這些資訊安全風險可能允許權限提高。攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這些資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-042">MS12-042</a></td>
<td style="border:1px solid black;">Windows 核心中的資訊安全風險可能會允許權限提高 (2711167) <br />
<br />
這個資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險和一項公開揭露的資訊安全風險。如果攻擊者登入受影響的系統，並執行蓄意製作的應用程式來利用資訊安全風險，則此資訊安全風險可能會允許權限提高。攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項資訊安全風險。匿名或遠端使用者無法利用這個資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
資訊安全風險入侵指數  
--------------------
  
<span></span>
下表提供本月所述每個資訊安全風險的利用性評估。資訊安全風險皆根據公告編號和 CVE 編號依序列出。僅包含資訊安全公告中，嚴重性等級為「重大」或「重要」的資訊安全風險。
  
我該如何使用這個表格？
  
您可以運用此表格，針對您可能需要安裝的每一項資訊安全更新，瞭解資訊安全風險在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務 (DoS) 的可能性。請根據您特定的組態設定，檢閱下列各項評估，決定部署本月份更新的優先次序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 資訊安全風險索引](http://technet.microsoft.com/security/cc998259.aspx)。
  
在下方欄位中，「最新軟體版本」意指受影響軟體，「較舊軟體版本」意指受影響軟體所有較舊的支援版本，如公告中的「受影響的軟體」或「不受影響的軟體」表格裡所示。
  
| 公告編號                                                                  | 資訊安全風險標題                                  | CVE ID                                                                           | 最新軟體版本的資訊安全風險評估                                                                      | 較舊軟體版本的資訊安全風險評估                                                                      | 阻斷服務 (DoS) 資訊安全風險評估 | 主要重點                           |  
|---------------------------------------------------------------------------|---------------------------------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|---------------------------------|------------------------------------|  
| [MS12-036](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-036) | 遠端桌面通訊協定資訊安全風險                      | [CVE-2012-0173](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0173) | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | 永久                            | (無)                               |  
| [MS12-037](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-037) | Center 項目遠端執行程式碼資訊安全風險             | [CVE-2012-1523](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1523) | 不受影響                                                                                            | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | 暫時                            | (無)                               |  
| [MS12-037](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-037) | HTML 清理資訊安全風險                             | [CVE-2012-1858](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1858) | [3](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | [3](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 不適用                          | 這是一個資訊洩漏資訊安全風險。     |  
| [MS12-037](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-037) | Null 位元組資訊洩漏資訊安全風險                   | [CVE-2012-1873](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1873) | [3](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | [3](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 不適用                          | 這是一個資訊洩漏資訊安全風險。     |  
| [MS12-037](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-037) | 開發人員工具列遠端執行程式碼資訊安全風險          | [CVE-2012-1874](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1874) | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | [3](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 暫時                            | (無)                               |  
| [MS12-037](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-037) | 相同 ID 內容遠端執行程式碼資訊安全風險            | [CVE-2012-1875](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1875) | 不受影響                                                                                            | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | 暫時                            | (無)                               |  
| [MS12-037](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-037) | Col 項目遠端執行程式碼資訊安全風險                | [CVE-2012-1876](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1876) | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | 暫時                            | (無)                               |  
| [MS12-037](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-037) | Title 元素變更遠端執行程式碼資訊安全風險          | [CVE-2012-1877](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1877) | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | 暫時                            | (無)                               |  
| [MS12-037](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-037) | OnBeforeDeactivate 事件遠端執行程式碼資訊安全風險 | [CVE-2012-1878](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1878) | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | 暫時                            | (無)                               |  
| [MS12-037](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-037) | insertAdjacentText 遠端執行程式碼資訊安全風險     | [CVE-2012-1879](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1879) | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | 暫時                            | (無)                               |  
| [MS12-037](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-037) | insertRow 遠端執行程式碼資訊安全風險              | [CVE-2012-1880](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1880) | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | 暫時                            | (無)                               |  
| [MS12-037](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-037) | OnRowsInserted 事件遠端執行程式碼資訊安全風險     | [CVE-2012-1881](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1881) | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | 暫時                            | (無)                               |  
| [MS12-038](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-038) | .NET Framework 記憶體存取資訊安全風險             | [CVE-2012-1855](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1855) | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | 不適用                          | (無)                               |  
| [MS12-039](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-039) | TrueType 字型剖析資訊安全風險                     | [CVE-2011-3402](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3402) | [3](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 不受影響                                                                                            | 永久                            | 這項資訊安全風險已經遭到公開揭發。 |  
| [MS12-039](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-039) | TrueType 字型剖析資訊安全風險                     | [CVE-2012-0159](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0159) | [3](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 不受影響                                                                                            | 永久                            | (無)                               |  
| [MS12-039](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-039) | Lync 不安全程式庫載入資訊安全風險                 | [CVE-2012-1849](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1849) | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | 不受影響                                                                                            | 不適用                          | (無)                               |  
| [MS12-039](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-039) | HTML 清理資訊安全風險                             | [CVE-2012-1858](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1858) | [3](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | [3](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 不適用                          | 這是一個資訊洩漏資訊安全風險。     |  
| [MS12-040](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-040) | Dynamic AX Enterprise Portal XSS 資訊安全風險     | [CVE-2012-1857](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1857) | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | 不受影響                                                                                            | 不適用                          | (無)                               |  
| [MS12-041](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-041) | 字串單元類別名稱處理資訊安全風險                  | [CVE-2012-1864](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1864) | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | 永久                            | (無)                               |  
| [MS12-041](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-041) | 字串單元類別名稱處理資訊安全風險                  | [CVE-2012-1865](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1865) | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | 永久                            | (無)                               |  
| [MS12-041](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-041) | 剪貼簿格式單元名稱處理資訊安全風險                | [CVE-2012-1866](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1866) | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | 永久                            | (無)                               |  
| [MS12-041](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-041) | 字型資源 Refcount 整數溢位資訊安全風險            | [CVE-2012-1867](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1867) | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | 永久                            | (無)                               |  
| [MS12-041](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-041) | Win32k.sys 競爭狀況資訊安全風險                   | [CVE-2012-1868](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1868) | 不受影響                                                                                            | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | 永久                            | (無)                               |  
| [MS12-042](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-042) | 使用者模式排程器記憶體損毀資訊安全風險            | [CVE-2012-0217](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0217) | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | 不受影響                                                                                            | 永久                            | (無)                               |  
| [MS12-042](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-042) | BIOS ROM 損毀資訊安全風險                         | [CVE-2012-1515](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1515) | 不受影響                                                                                            | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | 永久                            | 這項資訊安全風險已經遭到公開揭發。 |
  
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
<th colspan="6">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
公告 編號
</td>
<td style="border:1px solid black;">
[MS12-036](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-036)
</td>
<td style="border:1px solid black;">
[MS12-037](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-037)
</td>
<td style="border:1px solid black;">
[MS12-038](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-038)
</td>
<td style="border:1px solid black;">
[MS12-041](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-041)
</td>
<td style="border:1px solid black;">
[MS12-042](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-042)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[中度](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重大](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重大](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=fd2216eb-283b-4a23-b259-018a7fa5fe47)  
(KB2685939)  
(中度)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=7f222e05-2a8d-4099-851f-2044811f7425)  
(KB2699988)  
(重大)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=07c75ac6-f92a-4204-aa58-bdf8c033df9e)  
(KB2699988)  
(重大)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5bc1656f-cf1d-4f77-a078-a8602401b8e1)  
(KB2699988)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f)  
(KB2686828)  
(重大)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=a399bd47-ffe1-4476-932c-9c119496222a)  
(KB2709162)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=0efff733-4c8d-4fce-8de3-28465c6b762b)  
(KB2707511)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6e354955-32ae-447c-b16f-960acc01773b)  
(KB2685939)  
(中度)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=57e8bf9d-97c3-4166-a5d4-6b0c99afc6a1)  
(KB2699988)  
(重大)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4b35e90b-145d-44c2-a8bc-4f9108d46fa1)  
(KB2699988)  
(重大)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=0a386b16-74f7-4d36-93d0-75e7da9bf9b5)  
(KB2699988)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f)  
(KB2686828)  
(重大)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bdb356db-bd36-4159-8e64-ecdb3dfc61bf)  
(KB2709162)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-036](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-036)
</td>
<td style="border:1px solid black;">
[MS12-037](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-037)
</td>
<td style="border:1px solid black;">
[MS12-038](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-038)
</td>
<td style="border:1px solid black;">
[MS12-041](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-041)
</td>
<td style="border:1px solid black;">
[MS12-042](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-042)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
彙總 嚴重性等級
</td>
<td style="border:1px solid black;">
[重大](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[中度](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重大](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=%208e856fec-9f05-49b7-91b6-11c2636a2f1d)  
(KB2685939)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=b1dcc826-7e96-464b-830e-39946e7802aa)  
(KB2699988)  
(中度)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=de828031-1ace-43df-80f2-db7d503fb0a2)  
(KB2699988)  
(中度)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=4e6e5589-b767-4e8a-b8b3-df7b97e002e5)  
(KB2699988)  
(中度)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f)  
(KB2686828)  
(重大)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e0b39b00-d7db-4008-8310-1258e84a72a2)  
(KB2709162)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=855611a1-91ad-4d22-8c1c-fdcd6af4cef0)  
(KB2707511)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9b63fa4d-b42e-43ca-9f2c-cf60c37731a5)  
(KB2685939)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=b060e03b-e63e-446b-9cfd-ea4e1e9383a6)  
(KB2699988)  
(中度)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a36f7ffe-d537-4f9e-b676-22a24f50c089)  
(KB2699988)  
(中度)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=b1acb2f0-63ba-4524-94cf-42b3534e21e7)  
(KB2699988)  
(中度)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f)  
(KB2686828)  
(重大)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ed7359ce-13e8-42b2-956d-e8be534583aa)  
(KB2709162)  
(重要)
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
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=7dfdc5dc-54b0-49e3-bf5a-bbc40b0f159f)  
(KB2685939)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=893667c4-ef9f-48d3-ab18-a0df51bd3dcc)  
(KB2699988)  
(中度)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=30a9d518-8067-44f4-90fd-09fec8a0c883)  
(KB2699988)  
(中度)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f)  
(KB2686828)  
(重大)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=2317c8d9-cae8-497b-952e-78eb4a6d585c)  
(KB2709162)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="6">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-036](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-036)
</td>
<td style="border:1px solid black;">
[MS12-037](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-037)
</td>
<td style="border:1px solid black;">
[MS12-038](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-038)
</td>
<td style="border:1px solid black;">
[MS12-041](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-041)
</td>
<td style="border:1px solid black;">
[MS12-042](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-042)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[中度](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重大](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重大](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=%20f55b62bf-0571-4888-9061-3f7cc75d7f17)  
(KB2685939)  
(中度)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=16f4404e-e6d6-4bde-af15-3bb692412213)  
(KB2699988)  
(重大)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=610e753a-21db-43e6-bc42-3e1227fa4bb1)  
(KB2699988)  
(重大)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=828fdb71-747b-481d-9683-895325331478)  
(KB2699988)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b)  
(KB2686833)  
(重大)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9188f1eb-b568-4a99-9b39-745c760a693d)  
(KB2709162)  
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
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ab06290c-4f57-4349-8abd-a382b9044631)  
(KB2685939)  
(中度)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=993c5bc4-8903-4c8c-bbc9-da2e47d959f9)  
(KB2699988)  
(重大)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=87100a7e-7feb-4a18-b7aa-04fdd2d6ef52)  
(KB2699988)  
(重大)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7b551d67-e0f1-498a-ac4f-06376a0fcf18)  
(KB2699988)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b)  
(KB2686833)  
(重大)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4b94ae42-2882-444c-ad5e-74e34b805006)  
(KB2709162)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-036](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-036)
</td>
<td style="border:1px solid black;">
[MS12-037](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-037)
</td>
<td style="border:1px solid black;">
[MS12-038](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-038)
</td>
<td style="border:1px solid black;">
[MS12-041](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-041)
</td>
<td style="border:1px solid black;">
[MS12-042](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-042)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[重大](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[中度](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重大](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d8dcb487-0df7-46f4-8726-bd58e2722812)  
(KB2685939)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e7f9ad40-d515-4224-90ff-4bd4bff9180f)  
(KB2699988)  
(中度)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c4eaeff8-7b7a-4418-a479-09b2146df2bf)  
(KB2699988)  
(中度)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=a20c839c-ce3b-46a5-becb-588de404878d)  
(KB2699988)  
(中度)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b)  
(KB2686833)  
(重大)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6398a156-9618-4ca4-95bc-d36ecacf0745)  
(KB2709162)  
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
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=40c16540-7839-412c-b474-892292a96fa5)  
(KB2685939)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=7420c9f3-8f7e-4823-aaba-b14b957408d8)  
(KB2699988)  
(中度)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=fd5308b7-7430-4713-922c-f06c46886fad)  
(KB2699988)  
(中度)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=1a737d87-0689-470b-8fc0-8c874af18794)  
(KB2699988)  
(中度)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b)  
(KB2686833)  
(重大)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bc4412ee-8cb8-42e9-96fe-0be49af149b2)  
(KB2709162)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c4b8af1c-b483-4aed-9be5-b0f1698b2c28)  
(KB2685939)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=472842c4-5fe7-4d4c-a927-05be030b5b4e)  
(KB2699988)  
(中度)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b)  
(KB2686833)  
(重大)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=098607b3-9424-4440-8832-fc1de010977e)  
(KB2709162)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="6">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-036](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-036)
</td>
<td style="border:1px solid black;">
[MS12-037](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-037)
</td>
<td style="border:1px solid black;">
[MS12-038](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-038)
</td>
<td style="border:1px solid black;">
[MS12-041](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-041)
</td>
<td style="border:1px solid black;">
[MS12-042](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-042)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
彙總嚴重性 等級
</td>
<td style="border:1px solid black;">
[重大](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重大](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重大](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=e8549243-e6bf-4007-9bc3-d9c2a24936ef)  
(KB2685939)  
(中度)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=595e72c3-f195-4f93-b24e-afe444abd628)  
(KB2699988)  
(重大)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=48ca08c8-78cc-4b09-a0ec-bcd208668620)  
(KB2699988)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236)  
(KB2686830)  
(重大)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=605f64bd-0615-47d8-bb32-6bc3e80da4a7)  
(KB2709162)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=e8549243-e6bf-4007-9bc3-d9c2a24936ef)  
(KB2685939)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=595e72c3-f195-4f93-b24e-afe444abd628)  
(KB2699988)  
(重大)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=48ca08c8-78cc-4b09-a0ec-bcd208668620)  
(KB2699988)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b)  
(KB2686831)  
(重大)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=605f64bd-0615-47d8-bb32-6bc3e80da4a7)  
(KB2709162)  
(重要)
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
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=7f0f54e4-b9d9-45d8-bc58-05d7e7b75f07)  
(KB2685939)  
(中度)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=30feb2fe-b19b-4d02-8c5b-4499dd6905d1)  
(KB2699988)  
(重大)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=bf8dbfee-573b-4d45-a752-90e1d485e503)  
(KB2699988)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236)  
(KB2686830)  
(重大)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=3c77ca1f-2eec-4f95-a769-973b75af184c)  
(KB2709162)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=c2b47091-534f-41c3-a229-b5a9ec4b64bb)  
(KB2709715)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7f0f54e4-b9d9-45d8-bc58-05d7e7b75f07)  
(KB2685939)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=30feb2fe-b19b-4d02-8c5b-4499dd6905d1)  
(KB2699988)  
(重大)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=bf8dbfee-573b-4d45-a752-90e1d485e503)  
(KB2699988)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b)  
(KB2686831)  
(重大)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3c77ca1f-2eec-4f95-a769-973b75af184c)  
(KB2709162)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=c2b47091-534f-41c3-a229-b5a9ec4b64bb)  
(KB2709715)  
(重要)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-036](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-036)
</td>
<td style="border:1px solid black;">
[MS12-037](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-037)
</td>
<td style="border:1px solid black;">
[MS12-038](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-038)
</td>
<td style="border:1px solid black;">
[MS12-041](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-041)
</td>
<td style="border:1px solid black;">
[MS12-042](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-042)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[重大](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[中度](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重大](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=12740f33-579c-4a75-bec0-9a69e9c64266)  
(KB2685939)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=30feb2fe-b19b-4d02-8c5b-4499dd6905d1)  
(KB2699988)  
(中度)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7c0c8b04-b749-4c6c-8b9f-244abc5f8ecf)  
(KB2699988)  
(中度)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236)  
(KB2686830)  
(重大)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=34d16819-4a2f-42e2-a4f9-88995719cbe8)  
(KB2709162)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=1696726a-ed04-4c0e-b9b6-3ac4ac775c4c)  
(KB2709715)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=12740f33-579c-4a75-bec0-9a69e9c64266)  
(KB2685939)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=30feb2fe-b19b-4d02-8c5b-4499dd6905d1)  
(KB2699988)  
(中度)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7c0c8b04-b749-4c6c-8b9f-244abc5f8ecf)  
(KB2699988)  
(中度)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b)  
(KB2686831)  
(重大)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=34d16819-4a2f-42e2-a4f9-88995719cbe8)  
(KB2709162)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1696726a-ed04-4c0e-b9b6-3ac4ac775c4c)  
(KB2709715)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=8ecc5d12-9921-4d04-a04c-d69e8f4349dc)  
(KB2685939)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=40302688-fcda-489c-87c4-480d3b9d754c)  
(KB2699988)  
(中度)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236)  
(KB2686830)  
(重大)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=039ddfe1-3ce5-48d8-8cb4-65481da3f29c)  
(KB2709162)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=8ecc5d12-9921-4d04-a04c-d69e8f4349dc)  
(KB2685939)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=40302688-fcda-489c-87c4-480d3b9d754c)  
(KB2699988)  
(中度)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b)  
(KB2686831)  
(重大)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=039ddfe1-3ce5-48d8-8cb4-65481da3f29c)  
(KB2709162)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="6">
Server Core 安裝選項
</th>
</tr>
<tr>
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-036](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-036)
</td>
<td style="border:1px solid black;">
[MS12-037](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-037)
</td>
<td style="border:1px solid black;">
[MS12-038](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-038)
</td>
<td style="border:1px solid black;">
[MS12-041](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-041)
</td>
<td style="border:1px solid black;">
[MS12-042](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-042)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[重大](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[重大](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d8dcb487-0df7-46f4-8726-bd58e2722812)  
(KB2685939)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6398a156-9618-4ca4-95bc-d36ecacf0745)  
(KB2709162)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=40c16540-7839-412c-b474-892292a96fa5)  
(KB2685939)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bc4412ee-8cb8-42e9-96fe-0be49af149b2)  
(KB2709162)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=12740f33-579c-4a75-bec0-9a69e9c64266)  
(KB2685939)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b)  
(KB2686831)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=34d16819-4a2f-42e2-a4f9-88995719cbe8)  
(KB2709162)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=1696726a-ed04-4c0e-b9b6-3ac4ac775c4c)  
(KB2709715)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=12740f33-579c-4a75-bec0-9a69e9c64266)  
(KB2685939)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b)  
(KB2686831)  
(重大)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=34d16819-4a2f-42e2-a4f9-88995719cbe8)  
(KB2709162)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1696726a-ed04-4c0e-b9b6-3ac4ac775c4c)  
(KB2709715)  
(重要)
</td>
</tr>
</table>
 
MS12-038 ***注意事項***

<sup>[1]</sup>.NET Framework 4 和 .NET Framework 4 Client Profile 會受到影響。可在兩個設定檔中使用 .NET Framework 第 4 版可轉散發套件： .NET Framework 4 和 .NET Framework 4 Client Profile。.NET Framework 4 Client Profile 是 .NET Framework 4 的子集。此更新所解決的資訊安全風險會同時影響到 .NET Framework 4 和 .NET Framework 4 Client Profile。如需詳細資訊，請參閱 MSDN 文章：安裝 .NET Framework。

#### Microsoft Office 套件及軟體

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Office 軟體
</th>
</tr>
<tr>
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-039](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-039)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=0571a2c5-30e4-42b3-bd34-9da23be7b392)<sup>[1]</sup>   
(KB2598361)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=181bbd45-9128-4c26-af1e-fadfd83ff756)<sup>[1]</sup>   
(KB2596744)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=181bbd45-9128-4c26-af1e-fadfd83ff756)<sup>[1]</sup>   
(KB2596744)  
(重要)
</td>
</tr>
</table>
 
MS12-039 ***注意事項***

<sup>[1]</sup>這些 Microsoft Office 更新適用於所有受支援的 Microsoft Office 套件，以及其他含有易受影響之共用 Office 元件的 Microsoft Office 軟體。這些軟體包括 (但不限於) 受支援版本的 Microsoft Visio 和 Microsoft Project。

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

#### Microsoft 開發者工具和軟體

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Visual Basic for Applications
</th>
</tr>
<tr>
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-039](http://technet.microsoft.com/zh-tw/security)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Basic for Applications
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
Microsoft Visual Basic for Applications SDK<sup>[2]</sup><sup>[3]</sup>
(重要)
</td>
</tr>
</table>
 
MS12-039 注意事項

<sup>[1]</sup>此更新套件適用於支援版本的 Microsoft Visual Basic for Applications Runtime (Vbe6.dll)，僅可以從 Microsoft 下載中心取得。

<sup>[2]</sup>支援的 VBA SDK 版本包含 Microsoft Visual Basic for Applications SDK 6.3、Microsoft Visual Basic for Applications SDK 6.4 及 Microsoft Visual Basic for Applications SDK 6.5。

<sup>[3]</sup>可解決本公告描述之資訊安全風險的 Visual Basic for Applications SDK 更新版本目前由 Summit Software Company 開放給獨立軟體廠商 (ISV)。

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

#### Microsoft Enterprise Resource Planning (ERP) 解決方案

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Dynamics ERP
</th>
</tr>
<tr>
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-040](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-040)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Dynamics AX 2012
</td>
<td style="border:1px solid black;">
[Microsoft Dynamics AX 2012 Enterprise Portal](http://www.microsoft.com/downloads/details.aspx?familyid=45df362d-8fed-4d99-91c1-81c61878300a)<sup>[1]</sup>
(KB2706738)  
(重要)  
[Microsoft Dynamics AX 2012 Enterprise Portal](http://www.microsoft.com/downloads/details.aspx?familyid=780ddcef-19da-44c4-beca-d10b652cd22a)<sup>[1]</sup>
(KB2710639)  
(重要)  
[Microsoft Dynamics AX 2012 Enterprise Portal](http://www.microsoft.com/downloads/details.aspx?familyid=41dc5958-c224-40f9-89c2-179607a8ee2a)<sup>[1]</sup>
(KB2711239)  
(重要)
</td>
</tr>
</table>
 
MS12-040 注意事項

<sup>[1]</sup>此更新只能從 Microsoft 下載中心及 Microsoft Dynamics CustomerSource 和 Microsoft Dynamics PartnerSource 網站中取得。

#### Microsoft 通訊平台和軟體

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Communicator
</th>
</tr>
<tr>
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-039](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-039)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Communicator 2007 R2
</td>
<td style="border:1px solid black;">
[Microsoft Communicator 2007 R2](http://www.microsoft.com/downloads/details.aspx?familyid=515d6dba-4c6a-48bb-a06a-d99c5742676d)  
(KB2708980)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Lync
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-039](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-039)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 位元)
</td>
<td style="border:1px solid black;">
[Microsoft Lync 2010 (32 位元)](http://www.microsoft.com/downloads/details.aspx?familyid=f27546af-c390-4ee8-a55e-fd56848c2394)  
(KB2693282)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 位元)
</td>
<td style="border:1px solid black;">
[Microsoft Lync 2010 (64 位元)](http://www.microsoft.com/downloads/details.aspx?familyid=0fd94d10-fe84-4c84-a387-91afe24fb5b8)  
(KB2693282)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(系統管理員層級安裝)  
(KB2696031)  
(重要)  
[Microsoft Lync 2010 Attendee](http://www.microsoft.com/downloads/details.aspx?familyid=ef3101fa-f4ac-4a96-9aae-dfc5c6d0934d)<sup>[1]</sup>
(使用者層級安裝)  
(KB2693283)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendant (32 位元)
</td>
<td style="border:1px solid black;">
[Microsoft Lync 2010 Attendant (32 位元)](http://www.microsoft.com/downloads/details.aspx?familyid=00c4a9c6-5f01-47fe-9d15-65ec3459469b)  
(KB2702444)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendant (64 位元)
</td>
<td style="border:1px solid black;">
[Microsoft Lync 2010 Attendant (64 位元)](http://www.microsoft.com/downloads/details.aspx?familyid=e96bd908-87bb-4d8a-a2e4-f9f47cea045d)  
(KB2702444)  
(重要)
</td>
</tr>
</table>
 
MS12-039 注意事項

<sup>[1]</sup>這個更新程式僅可以從 Microsoft 下載中心取得。

偵測與部署工具及指南
--------------------

<span></span>
資訊安全中心

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和資訊安全更新。如需更多資訊，請參閱 [TechNet 更新管理中心](http://technet.microsoft.com/zh-tw/updatemanagement/default.aspx) (英文)。TechNet 資訊安全技術中心提供 Microsoft 產品安全性的其他資訊。消費者可以造訪在家上網的安全性網站，只要按一下 \[最新資訊安全更新\] 即可在此網站取得此資訊。

資訊安全更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 以及 [Windows Update](http://www.update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-tw) 取得。資訊安全更新也可以從 [Microsoft 下載中心](http://www.microsoft.com/downloads/results.aspx?displaylang=en&freetext=security%20update)取得。您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。

對於 Microsoft Office for Mac 的客戶，Microsoft AutoUpdate for Mac 可協助您保持最新的 Microsoft 軟體。如需使用 Microsoft AutoUpdate for Mac 的詳細資訊，請參閱自動檢查軟體更新 (英文)。

最後，您可以從 [Microsoft Update Catalog](http://catalog.update.microsoft.com/v7/site/) 下載資訊安全更新。Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括資訊安全更新、驅動程式和 Service Pack。只要以資訊安全公告編號 (例如：MS07-036) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](http://catalog.update.microsoft.com/v7/site/faq.aspx)。

偵測與部署指南

Microsoft 針對資訊安全更新提供偵測和部署指南。本指南所含之建議和資訊，能幫助 IT 專業人員瞭解如何使用用於資訊安全更新的偵測和部署的各種工具。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 961747](http://support.microsoft.com/kb/961747?ln=zh-tw)。

Microsoft Baseline Security Analyzer

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少資訊安全更新以及一般資訊安全設定錯誤的狀況。如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](http://technet.microsoft.com/zh-tw/security/cc184924.aspx)。

Windows Server Update Services

透過 Windows Server Update Services (WSUS)，系統管理員可迅速而可靠地將 Microsoft Windows 2000 作業系統及更新版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 適用的最新重大更新與資訊安全更新部署到 Microsoft Windows 2000 及更新版本的作業系統中。

如需更多關於利用 Windows Server Update Services 部署資訊安全更新的資訊，請造訪 [Windows Server Update Services](http://technet.microsoft.com/zh-tw/wsus/default.aspx) (英文)。

System Center Configuration Manager

System Center Configuration Manager 軟體更新管理可簡化遞送和管理企業中 IT 系統更新的繁複作業。IT 系統管理員可以使用 System Center Configuration Manager 遞送 Microsoft 產品更新給各種裝置，包括桌上型電腦、筆記型電腦、伺服器及行動裝置。

System Center Configuration Manager 中的自動資訊安全風險評估會找出更新需求並報告建議動作。System Center Configuration Manager 中的軟體更新管理是建置在 Microsoft Windows Software Update Services (WSUS) 上，經過時間考驗，為全球 IT 系統管理員所熟悉的更新基礎架構。如需更多有關系統管理員如何使用 System Center Configuration Manager 來部署更新的資訊，請參閱軟體更新管理 (英文)。如需更多有關 System Center Configuration Manager 的資訊，請造訪 [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx)。

Systems Management Server 2003

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。透過 SMS，系統管理員能判斷有哪些 Windows 系統需要資訊安全更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。

注意：System Management Server 2003 自 2010 年 1 月 12 日起不受主流支援。如需更多有關產品生命週期的資訊，請造訪 [Microsoft 支援週期](http://support.microsoft.com/common/international.aspx?rdpath=dm;zh-tw;lifecycle?ln=zh-tw)。現已推出新版的 SMS，System Center Configuration Manager；請參閱前段的＜System Center Configuration Manager＞一節。

如需更多有關系統管理員如何使用 SMS 2003 來部署資訊安全更新的資訊，請參閱 [Microsoft Systems Management Server 2003 的案例與程序： 軟體發佈和補充程式管理](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en) (英文)。如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server 技術中心 (TechCenter)](http://technet.microsoft.com/zh-tw/systemcenter/bb545936.aspx)。

注意 ：SMS 使用 Microsoft Baseline Security Analyzer 提供廣泛的資訊安全公告更新偵測與部署支援。不過這些工具可能無法偵測部分的軟體更新。在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。如需關於此程序的詳細資訊，請參閱使用 SMS 軟體發佈功能部署軟體更新 (英文)。某些資訊安全更新程式在電腦重新啟動之後，會需要系統管理員的權限。系統管理員可使用 Elevated Rights Deployment Tool (隨附於 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)) 來安裝這些更新。

Update Compatibility Evaluator 和 Application Compatibility Toolkit

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

更新程式管理策略

[更新管理資訊安全指南](http://technet.microsoft.com/zh-tw/library/bb466251(zh-tw).aspx) (英文) 提供您有關套用資訊安全更新的 Microsoft 最佳實作建議的其他資訊。

取得其他資訊安全更新

其他資訊安全問題的更新可由下列位置取得：

-   資訊安全更新可以從 [Microsoft 下載中心](http://www.microsoft.com/downloads/results.aspx?displaylang=en&freetext=security%20update)取得， 您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。
-   消費性平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的資訊安全更新。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](http://support.microsoft.com/kb/913086?ln=zh-tw)。

IT 專業人員資訊安全社群

在 [IT 專業人員資訊安全社群](http://technet.microsoft.com/zh-tw/security/cc136632.aspx)上，學習如何提升資訊安全以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類資訊安全議題的討論。

#### 感謝

Microsoft [感謝](http://technet.microsoft.com/zh-tw/security/gg309157.aspx)下列人士協助我們一同保護我們的客戶：

-   感謝匿名的研究人員與 [VeriSign iDefense Labs](http://labs.idefense.com/) 合作回報 MS12-037 中描述的一項問題
-   感謝 [IBM Security Systems - Application Security](http://blog.watchfire.com/) 的 Adi Cohen 回報 MS12-037 中描述的一項問題
-   感謝 Masato Kinugawa 回報 MS12-037 中描述的一項問題
-   感謝 LinkedIn 的 Roman Shafigullin 回報 MS12-037 中描述的一項問題
-   感謝 [VulnHunt](http://www.vulnhunt.com/) 的 Code Audit Labs 回報 MS12-037 中描述的一項問題
-   感謝 [VulnHunt](http://www.vulnhunt.com/) 的 Dark Son 回報 MS12-037 中描述的一項問題
-   感謝 [Qihoo 360 Security Center](http://www.360.cn/) 協助我們解決 MS12-037 中描述的一項問題
-   感謝 McAfee Labs 的 Yichong Lin 協助我們解決 MS12-037 中描述的一項問題
-   感謝 [Google Inc.](http://www.google.com/) 協助我們解決 MS12-037 中描述的一項問題
-   感謝 [VUPEN Security](http://www.vupen.com/) 與 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 MS12-037 中描述的一項問題
-   感謝匿名的研究人員與 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 MS12-037 中描述的一項問題
-   感謝匿名的研究人員與 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 MS12-037 中描述的一項問題
-   感謝匿名的研究人員與 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 MS12-037 中描述的一項問題
-   感謝匿名的研究人員與 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 MS12-037 中描述的一項問題
-   感謝匿名的研究人員與 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 MS12-037 中描述的一項問題
-   感謝 Vitaliy Toropov 與 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 MS12-038 中描述的一項問題
-   感謝 [Huawei](http://www.huawei.com/) 的 Haowen Bai 回報 MS12-039 中描述的一項問題
-   感謝 Finian Mackin 回報 MS12-040 中描述的一項問題
-   感謝 [Azimuth Security](http://www.azimuthsecurity.com/) 的 Tarjei Mandt 回報 MS12-041 中描述的三項問題
-   感謝 [Google Inc.](http://www.google.com/) 的 [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org/) 回報 MS12-041 中描述的一項問題
-   感謝 [Bromium](http://www.bromium.com/) 的 Rafal Wojtczuk 和 [SUSE](http://www.suse.com/) 的 Jan Beulich 回報 MS12-042 中描述的一項問題
-   感謝 Secunia SVCRP 的 hamburgers maccoy 回報 MS12-039 中描述的一項問題
-   感謝 [IBM Security Systems - Application Security](http://blog.watchfire.com/) 的 Adi Cohen 回報 MS12-039 中描述的一項問題
-   感謝 Alin Rad Pop 與 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 MS12-039 中描述的一項問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 支援週期](http://support.microsoft.com/default.aspx?scid=fh;%5bln%5d;lifecycle)。
-   IT 專業人員的資訊安全解決方案： [TechNet 資訊安全疑難排解與支援](http://technet.microsoft.com/security/bb980617.aspx)
-   協助保護您的 Widows 電腦免於病毒和惡意軟體攻擊： [病毒解決方案與資訊安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-tw)
-   您所在國家/地區的當地支援： [國際支援](http://support.microsoft.com/common/international.aspx?ln=zh-tw)

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2012 年 6 月 13 日)： 公告摘要發行。

*Built at 2014-04-18T01:50:00Z-07:00*
