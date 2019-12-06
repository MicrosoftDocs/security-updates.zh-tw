---
TOCTitle: 'MS13-JUL'
Title: 2013 年 7 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms13-jul'
ms:contentKeyID: 61237744
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms13-jul(v=Security.10)'
---

2013 年 7 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2013年7月9日 | 更新: 2013年9月11日

**版本:** 3.0

此公告摘要列出 2013 年 7 月份發行之資訊安全公告。

發行 2013 年 7 月份資訊安全公告之後，此公告摘要將取代原先於 2013 年 7 月 4 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 資訊安全公告預先通知](http://technet.microsoft.com/zh-tw/security/gg309152.aspx)。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術資訊安全通知](http://technet.microsoft.com/zh-tw/security/dd252948.aspx)。

Microsoft 將利用網路廣播於 2013 年 7 月 10 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。[立即註冊參加 7 月份資訊安全公告網路廣播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032556406&culture=zh-tw)。在這個日期後，此網路廣播將可[隨選取得](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538733&culture=en-us)。

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-052">MS13-052</a></td>
<td style="border:1px solid black;"><strong>.NET Framework</strong> <strong>和</strong> <strong>Silverlight</strong> <strong>中的資訊安全風險可能會允許遠端執行程式碼</strong> <strong>(2861561)</strong> <br />
<br />
這個資訊安全更新可解決 Microsoft .NET Framework 和 Microsoft Silverlight 中五項未公開報告的資訊安全風險，以及兩項公開揭露的資訊安全風險。如果受信任的應用程式使用特定模式的程式碼，則其中最嚴重的資訊安全風險可能會允許遠端執行程式碼。成功利用此資訊安全風險的攻擊者可以取得與登入使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework、<br />
Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-053">MS13-053</a></td>
<td style="border:1px solid black;"><strong>Windows</strong> <strong>核心</strong>模<strong>式驅動程式中的資訊安全風險可能會允許遠端執行程式碼</strong> <strong>(2850851)<br />
<br />
</strong>此資訊安全更新可解決 Microsoft Windows 中兩項公開揭露和六項未公開報告的資訊安全風險。其中最嚴重的資訊安全風險可能會在使用者檢視內嵌 TrueType 字型檔案的共用內容時，允許遠端執行程式碼。成功利用此資訊安全風險的攻擊者可以取得受影響系統的完整控制權。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-054">MS13-054</a></td>
<td style="border:1px solid black;"><strong>GDI+</strong> <strong>中的資訊安全風險可能會允許遠端執行程式碼</strong> <strong>(2848295)<br />
<br />
</strong>此資訊安全更新可解決 Microsoft Windows、Microsoft Office、Microsoft Lync 及 Microsoft Visual Studio 中一項未公開報告的資訊安全風險。此資訊安全風險可能會在使用者檢視內嵌 TrueType 字型檔案的共用內容時，允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Office、<br />
Microsoft Visual Studio、<br />
Microsoft Lync</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055">MS13-055</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer</strong> <strong>積存資訊安全更新</strong> <strong>(2846071)  <br />
<br />
</strong>本資訊安全更新可解決 Internet Explorer 中十七項未公開報告的資訊安全風險。最嚴重的資訊安全風險可能會在使用者以 Internet Explorer 檢視蓄意製作的網頁時，允許遠端執行程式碼。成功利用其中最嚴重的資訊安全風險的攻擊者，可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-056">MS13-056</a></td>
<td style="border:1px solid black;"><strong>Microsoft DirectShow</strong> <strong>中的資訊安全風險可能會允許遠端執行程式碼</strong> <strong>(2845187)<br />
<br />
</strong>此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果使用者開啟蓄意製作的影像檔，此資訊安全風險可能會允許遠端執行程式碼。成功利用此資訊安全風險的攻擊者可以取得與本機使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-057">MS13-057</a></td>
<td style="border:1px solid black;"><strong>Windows Media Format Runtime</strong> <strong>中的資訊安全風險可能會允許遠端執行程式碼</strong> <strong>(2847883)<br />
<br />
</strong>此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果使用者開啟蓄意製作的媒體檔案，則此資訊安全風險可能會允許遠端執行程式碼。成功利用此資訊安全風險的攻擊者可以取得與本機使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-058">MS13-058</a></td>
<td style="border:1px solid black;"><strong>Windows Defender</strong> <strong>中的資訊安全風險可能會允許權限提高</strong> <strong>(2847927)<br />
<br />
</strong>此資訊安全更新可替適用於 Windows 7 的 Windows Defender 及安裝在 Windows Server 2008 R2 上的 Windows Defender 解決一項未公開報告的資訊安全風險。此資訊安全風險可能因 Windows Defender 使用的路徑名稱而允許權限提高。成功利用此資訊安全風險的攻擊者可執行任意程式碼，並取得受影響之系統的完整控制權。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。攻擊者必須擁有有效的登入認證，才能利用這項資訊安全風險。匿名使用者無法利用這個資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">不需要重新開機</td>
<td style="border:1px solid black;">Microsoft 資訊安全軟體</td>
</tr>
</tbody>
</table>
  
資訊安全風險入侵指數  
--------------------
  

下表提供本月所述每個資訊安全風險的利用性評估。資訊安全風險皆根據公告編號和 CVE 編號依序列出。僅包含資訊安全公告中，嚴重性等級為「重大」或「重要」的資訊安全風險。
  
**我該如何使用這個表格？**
  
您可以運用此表格，針對您可能需要安裝的每一項資訊安全更新，瞭解資訊安全風險在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務 (DoS) 的可能性。請根據您特定的組態設定，檢閱下列各項評估，決定部署本月份更新的優先次序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 資訊安全風險索引](http://technet.microsoft.com/security/cc998259)。
  
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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-052">MS13-052</a></td>
<td style="border:1px solid black;">TrueType 字型剖析資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3129">CVE-2013-3129</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-052">MS13-052</a></td>
<td style="border:1px solid black;">陣列存取違規資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3131">CVE-2013-3131</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">此資訊安全風險已經遭到公開揭發。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-052">MS13-052</a></td>
<td style="border:1px solid black;">委派反映略過資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3132">CVE-2013-3132</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-052">MS13-052</a></td>
<td style="border:1px solid black;">匿名方法插入資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3133">CVE-2013-3133</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-052">MS13-052</a></td>
<td style="border:1px solid black;">陣列配置資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3134">CVE-2013-3134</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">此資訊安全風險已經遭到公開揭發。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-052">MS13-052</a></td>
<td style="border:1px solid black;">委派序列化資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3171">CVE-2013-3171</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-052">MS13-052</a></td>
<td style="border:1px solid black;">Null 指標資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3178">CVE-2013-3178</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-053">MS13-053</a></td>
<td style="border:1px solid black;">Win32k 記憶體配置資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1300">CVE-2013-1300</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-053">MS13-053</a></td>
<td style="border:1px solid black;">Win32k 解除參照資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1340">CVE-2013-1340</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">這是最新軟體版本的一項阻斷服務 (DoS) 資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-053">MS13-053</a></td>
<td style="border:1px solid black;">Win32k 資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1345">CVE-2013-1345</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">這是最新軟體版本的一項阻斷服務 (DoS) 資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-053">MS13-053</a></td>
<td style="border:1px solid black;">TrueType 字型剖析資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3129">CVE-2013-3129</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-053">MS13-053</a></td>
<td style="border:1px solid black;">Win32k 資訊洩漏資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3167">CVE-2013-3167</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">這是一個可能會導致權限提高的資訊洩漏資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-053">MS13-053</a></td>
<td style="border:1px solid black;">Win32k 緩衝區覆寫資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3173">CVE-2013-3173</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-053">MS13-053</a></td>
<td style="border:1px solid black;">Win32k 讀取 AV 資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3660">CVE-2013-3660</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">此資訊安全風險已經遭到公開揭發。<br />
<br />
根據 Microsoft 的瞭解，有駭客已嘗試利用此資訊安全風險對明確目標施以攻擊，意圖提高自身權限。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-054">MS13-054</a></td>
<td style="border:1px solid black;">TrueType 字型剖析資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3129">CVE-2013-3129</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3115">CVE-2013-3115</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3143">CVE-2013-3143</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3144">CVE-2013-3144</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3145">CVE-2013-3145</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3146">CVE-2013-3146</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3147">CVE-2013-3147</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3148">CVE-2013-3148</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3149">CVE-2013-3149</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3150">CVE-2013-3150</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3151">CVE-2013-3151</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3152">CVE-2013-3152</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3153">CVE-2013-3153</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3161">CVE-2013-3161</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3162">CVE-2013-3162</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3163">CVE-2013-3163</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">Microsoft 已發現嘗試透過 Internet Explorer 8 利用此資訊安全風險的目標式攻擊。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3164">CVE-2013-3164</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055">MS13-055</a></td>
<td style="border:1px solid black;">Shift JIS 字元編碼資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3166">CVE-2013-3166</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊洩漏的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-056">MS13-056</a></td>
<td style="border:1px solid black;">DirectShow 任意記憶體覆寫資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3174">CVE-2013-3174</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">暫時</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-057">MS13-057</a></td>
<td style="border:1px solid black;">WMV 視訊解碼器遠端執行程式碼資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3127">CVE-2013-3127</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">暫時</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-058">MS13-058</a></td>
<td style="border:1px solid black;">Microsoft Windows 7 Defender 不當路徑名稱資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3154">CVE-2013-3154</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
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
<th colspan="7">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-052**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-052)
</td>
<td style="border:1px solid black;">
[**MS13-053**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-053)
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-054)
</td>
<td style="border:1px solid black;">
[**MS13-055**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055)
</td>
<td style="border:1px solid black;">
[**MS13-056**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-056)
</td>
<td style="border:1px solid black;">
[**MS13-057**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-057)
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
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.0 Service Pack 3  
(僅限 Media Center Edition 2005 Service Pack 3 和 Tablet PC Edition 2005 Service Pack 3)  
(2833951)  
(重要)  
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833940)  
(重大)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844285)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832411)  
(重大)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(重大)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(重大)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2850851)  
(重大)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(Windows GDI+)  
(2834886)  
(重大)  
Windows XP Service Pack 3  
(僅限 Windows XP Tablet PC Edition 2005)  
(筆記本)  
(2835364)  
(重大)
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2846071)  
(重大)  
Internet Explorer 7   
(2846071)  
(重大)  
Internet Explorer 8   
(2846071)  
(重大)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2845187)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Media Format Runtime 11<sup>[1]</sup>
(wmvdecod.dll)  
(僅 Media Center 版本)  
(2834904)  
(重大)  
Windows Media Format Runtime 9.5  
(wmvdmod.dll)  
(僅 Media Center 版本)  
(2834905)  
(重大)  
Windows Media Format Runtime 9  
(wmvdmod.dll)  
(2803821)  
(重大)  
Windows Media Format Runtime 9.5<sup>[2]</sup>
(wmvdmod.dll)  
(2834902)  
(重大)  
Windows Media Format Runtime 9.5<sup>[3]</sup>
(wmvdmod.dll)  
(2834903)  
(重大)  
Windows Media Format Runtime 11  
(wmvdecod.dll)  
(2834904)  
(重大)  
wmv9vcm.dll (轉碼器)  
(2845142)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833940)  
(重大)  
Microsoft .NET Framework 2.0 Service Pack 2(2844285)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832411)  
(重大)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(重大)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(重大)  
Microsoft .NET Framework 4<sup>[1]</sup>(2840628)  
(重要)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2850851)  
(重大)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(Windows GDI+)  
(2834886)  
(重大)
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2846071)  
(重大)  
Internet Explorer 7   
(2846071)  
(重大)  
Internet Explorer 8   
(2846071)  
(重大)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2845187)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Media Format Runtime 9.5  
(wmvdmod.dll)  
(2803821)  
(重大)  
Windows Media Format Runtime 9.5 x64  
(wmvdmod.dll)  
(2834902)  
(重大)  
Windows Media Format Runtime 11  
(wmvdecod.dll)  
(2834904)  
(重大)  
wmv9vcm.dll (轉碼器)  
(2845142)  
(重大)
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
[**MS13-052**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-052)
</td>
<td style="border:1px solid black;">
[**MS13-053**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-053)
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-054)
</td>
<td style="border:1px solid black;">
[**MS13-055**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055)
</td>
<td style="border:1px solid black;">
[**MS13-056**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-056)
</td>
<td style="border:1px solid black;">
[**MS13-057**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-057)
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
[**中度**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833949)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833940)  
(重大)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844285)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832411)  
(重大)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(重大)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(重大)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2850851)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(Windows GDI+)  
(2834886)  
(重大)
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2846071)  
(中度)  
Internet Explorer 7  
(2846071)  
(中度)  
Internet Explorer 8  
(2846071)  
(中度)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2845187)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Media Format Runtime 9.5  
(wmvdmod.dll)  
(2803821)  
(重大)  
wmv9vcm.dll (轉碼器)  
(2845142)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833940)  
(重大)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844285)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832411)  
(重大)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(重大)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(重大)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2850851)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(Windows GDI+)  
(2834886)  
(重大)
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2846071)  
(中度)  
Internet Explorer 7  
(2846071)  
(中度)  
Internet Explorer 8  
(2846071)  
(中度)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2845187)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Media Format Runtime 9.5  
(wmvdmod.dll)  
(2803821)  
(重大)  
Windows Media Format Runtime 9.5 x64  
(wmvdmod.dll)  
(2834902)  
(重大)  
Windows Media Format Runtime 11  
(wmvdmod.dll)  
(2834904)  
(重大)  
wmv9vcm.dll (轉碼器)  
(2845142)  
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833940)  
(重大)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844285)  
(重要)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(重大)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(2850851)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(Windows GDI+)  
(2834886)  
(重大)
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2846071)  
(中度)  
Internet Explorer 7  
(2846071)  
(中度)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(2845187)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
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
[**MS13-052**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-052)
</td>
<td style="border:1px solid black;">
[**MS13-053**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-053)
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-054)
</td>
<td style="border:1px solid black;">
[**MS13-055**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055)
</td>
<td style="border:1px solid black;">
[**MS13-056**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-056)
</td>
<td style="border:1px solid black;">
[**MS13-057**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-057)
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
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833947)  
(重大)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844287)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832412)  
(重大)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(重大)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(重大)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)  
Microsoft .NET Framework 4.5  
(2835622)  
(重大)  
Microsoft .NET Framework 4.5  
(2833957)  
(重大)  
Microsoft .NET Framework 4.5  
(2840642)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2850851)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(DirectWrite)  
(2835361)  
(重大)  
Windows Vista Service Pack 2  
(Windows GDI+)  
(2834886)  
(重大)  
Windows Vista Service Pack 2  
(筆記本)  
(2835364)  
(重大)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
(重大)  
Internet Explorer 8  
(2846071)  
(重大)  
Internet Explorer 9   
(2846071)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2845187)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Media Player 11  
(wmvdecod.dll)  
(2803821)  
(重大)  
wmv9vcm.dll (轉碼器)  
(2845142)  
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833947)  
(重大)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844287)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832412)  
(重大)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(重大)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(重大)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)  
Microsoft .NET Framework 4.5  
(2835622)  
(重大)  
Microsoft .NET Framework 4.5  
(2833957)  
(重大)  
Microsoft .NET Framework 4.5  
(2840642)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2850851)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(DirectWrite)  
(2835361)  
(重大)  
Windows Vista x64 Edition Service Pack 2  
(Windows GDI+)  
(2834886)  
(重大)  
Windows Vista x64 Edition Service Pack 2  
(筆記本)  
(2835364)  
(重大)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
(重大)  
Internet Explorer 8  
(2846071)  
(重大)  
Internet Explorer 9   
(2846071)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2845187)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Media Player 11  
(wmvdecod.dll)  
(2803821)  
(重大)  
wmv9vcm.dll (轉碼器)  
(2845142)  
(重大)
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
[**MS13-052**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-052)
</td>
<td style="border:1px solid black;">
[**MS13-053**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-053)
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-054)
</td>
<td style="border:1px solid black;">
[**MS13-055**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055)
</td>
<td style="border:1px solid black;">
[**MS13-056**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-056)
</td>
<td style="border:1px solid black;">
[**MS13-057**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-057)
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
[**中度**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833947)  
(重大)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844287)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832412)  
(重大)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(重大)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(重大)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)  
Microsoft .NET Framework 4.5  
(2835622)  
(重大)  
Microsoft .NET Framework 4.5  
(2833957)  
(重大)  
Microsoft .NET Framework 4.5  
(2840642)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2850851)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(DirectWrite)  
(2835361)  
(重大)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Windows GDI+)  
(2834886)  
(重大)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(筆記本)  
(2835364)  
(重大)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
(中度)  
Internet Explorer 8  
(2846071)  
(中度)  
Internet Explorer 9   
(2846071)  
(中度)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2845187)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Media Player 11\[4\]  
(wmvdecod.dll)  
(2803821)  
(重大)  
wmv9vcm.dll (轉碼器) \[5\]  
(2845142)  
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833947)  
(重大)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844287)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832412)  
(重大)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(重大)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(重大)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)  
Microsoft .NET Framework 4.5  
(2835622)  
(重大)  
Microsoft .NET Framework 4.5  
(2833957)  
(重大)  
Microsoft .NET Framework 4.5  
(2840642)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2850851)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(DirectWrite)  
(2835361)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Windows GDI+)  
(2834886)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(筆記本)  
(2835364)  
(重大)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
(中度)  
Internet Explorer 8  
(2846071)  
(中度)  
Internet Explorer 9   
(2846071)  
(中度)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2845187)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Media Player 11\[4\]  
(wmvdecod.dll)  
(2803821)  
(重大)  
wmv9vcm.dll (轉碼器) \[5\]  
(2845142)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833947)  
(重大)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844287)  
(重要)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(重大)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2850851)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(Windows GDI+)  
(2834886)  
(重大)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
(中度)
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
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-052**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-052)
</td>
<td style="border:1px solid black;">
[**MS13-053**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-053)
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-054)
</td>
<td style="border:1px solid black;">
[**MS13-055**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055)
</td>
<td style="border:1px solid black;">
[**MS13-056**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-056)
</td>
<td style="border:1px solid black;">
[**MS13-057**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-057)
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
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2832414)  
(重大)  
Microsoft .NET Framework 3.5.1  
(2833946)  
(重大)  
Microsoft .NET Framework 3.5.1  
(2840631)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2844286)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(重大)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)  
Microsoft .NET Framework 4.5  
(2833957)  
(重大)  
Microsoft .NET Framework 4.5  
(2840642)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2850851)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(DirectWrite)  
(2835361)  
(重大)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(Windows GDI+)  
(2834886)  
(重大)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(筆記本)  
(2835364)  
(重大)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2846071)  
(重大)  
Internet Explorer 9   
(2846071)  
(重大)  
Internet Explorer 10   
(2846071)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2845187)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Media Player 12  
(wmvdecod.dll)  
(2803821)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2832414)  
(重大)  
Microsoft .NET Framework 3.5.1  
(2833946)  
(重大)  
Microsoft .NET Framework 3.5.1  
(2840631)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2844286)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(重大)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)  
Microsoft .NET Framework 4.5  
(2833957)  
(重大)  
Microsoft .NET Framework 4.5  
(2840642)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2850851)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(DirectWrite)  
(2835361)  
(重大)  
適用於 x64 型系統的 Windows 7 Service Pack 1  
(Windows GDI+)  
(2834886)  
(重大)  
適用於 x64 型系統的 Windows 7 Service Pack 1  
(筆記本)  
(2835364)  
(重大)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2846071)  
(重大)  
Internet Explorer 9   
(2846071)  
(重大)  
Internet Explorer 10   
(2846071)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2845187)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Media Player 12  
(wmvdecod.dll)  
(2803821)  
(重大)
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
[**MS13-052**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-052)
</td>
<td style="border:1px solid black;">
[**MS13-053**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-053)
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-054)
</td>
<td style="border:1px solid black;">
[**MS13-055**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055)
</td>
<td style="border:1px solid black;">
[**MS13-056**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-056)
</td>
<td style="border:1px solid black;">
[**MS13-057**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-057)
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
[**中度**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2832414)  
(重大)  
Microsoft .NET Framework 3.5.1  
(2833946)  
(重大)  
Microsoft .NET Framework 3.5.1  
(2840631)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2844286)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(重大)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)  
Microsoft .NET Framework 4.5  
(2833957)  
(重大)  
Microsoft .NET Framework 4.5  
(2840642)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2850851)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(DirectWrite)  
(2835361)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(Windows GDI+)  
(2834886)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(筆記本)  
(2835364)  
(重大)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2846071)  
(中度)  
Internet Explorer 9   
(2846071)  
(中度)  
Internet Explorer 10   
(2846071)  
(中度)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2845187)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Media Player 12\[4\]  
(wmvdecod.dll)  
(2803821)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2833946)  
(重大)  
Microsoft .NET Framework 3.5.1  
(2840631)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2844286)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(重大)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2850851)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(DirectWrite)  
(2835361)  
(重大)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(Windows GDI+)  
(2834886)  
(重大)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2846071)  
(中度)
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
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-052**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-052)
</td>
<td style="border:1px solid black;">
[**MS13-053**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-053)
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-054)
</td>
<td style="border:1px solid black;">
[**MS13-055**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055)
</td>
<td style="border:1px solid black;">
[**MS13-056**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-056)
</td>
<td style="border:1px solid black;">
[**MS13-057**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-057)
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
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2832418)  
(重大)  
Microsoft .NET Framework 3.5  
(2833959)  
(重大)  
Microsoft .NET Framework 3.5  
(2840633)  
(重要)  
Microsoft .NET Framework 3.5  
(2844289)  
(重要)  
Microsoft .NET Framework 4.5  
(2833958)  
(重大)  
Microsoft .NET Framework 4.5  
(2840632)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8  
(2850851)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8  
(DirectWrite)  
(2835361)  
(重大)  
適用於 32 位元系統的 Windows 8  
(筆記本)  
(2835364)  
(重大)
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2846071)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8  
(2845187)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Media Player 12  
(wmvdecod.dll)  
(2803821)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 8
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2832418)  
(重大)  
Microsoft .NET Framework 3.5  
(2833959)  
(重大)  
Microsoft .NET Framework 3.5  
(2840633)  
(重要)  
Microsoft .NET Framework 3.5  
(2844289)  
(重要)  
Microsoft .NET Framework 4.5  
(2833958)  
(重大)  
Microsoft .NET Framework 4.5  
(2840632)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 8  
(2850851)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 8  
(DirectWrite)  
(2835361)  
(重大)  
適用於 64 位元系統的 Windows 8  
(筆記本)  
(2835364)  
(重大)
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2846071)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 8  
(2845187)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Media Player 12  
(wmvdecod.dll)  
(2803821)  
(重大)
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
[**MS13-052**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-052)
</td>
<td style="border:1px solid black;">
[**MS13-053**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-053)
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-054)
</td>
<td style="border:1px solid black;">
[**MS13-055**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055)
</td>
<td style="border:1px solid black;">
[**MS13-056**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-056)
</td>
<td style="border:1px solid black;">
[**MS13-057**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-057)
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
[**中度**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2832418)  
(重大)  
Microsoft .NET Framework 3.5  
(2833959)  
(重大)  
Microsoft .NET Framework 3.5  
(2840633)  
(重要)  
Microsoft .NET Framework 3.5  
(2844289)  
(重要)  
Microsoft .NET Framework 4.5  
(2833958)  
(重大)  
Microsoft .NET Framework 4.5  
(2840632)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2850851)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(DirectWrite)  
(2835361)  
(重大)  
Windows Server 2012  
(筆記本)  
(2835364)(重大)
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2846071)  
(中度)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2845187)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Media Player 12\[4\]  
(wmvdecod.dll)  
(2803821)  
(重大)
</td>
</tr>
<tr>
<th colspan="7">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-052**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-052)
</td>
<td style="border:1px solid black;">
[**MS13-053**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-053)
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-054)
</td>
<td style="border:1px solid black;">
[**MS13-055**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055)
</td>
<td style="border:1px solid black;">
[**MS13-056**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-056)
</td>
<td style="border:1px solid black;">
[**MS13-057**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-057)
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
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5  
(2833958)  
(重大)  
Microsoft .NET Framework 4.5  
(2840632)  
(重要)
</td>
<td style="border:1px solid black;">
Windows RT  
(2850851)  
(重大)
</td>
<td style="border:1px solid black;">
Windows RT  
(DirectWrite)  
(2835361)  
(重大)
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2846071)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
Windows Media Player 12  
(wmvdecod.dll)  
(2803821)  
(重大)
</td>
</tr>
<tr>
<th colspan="7">
Server Core 安裝選項
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-052**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-052)
</td>
<td style="border:1px solid black;">
[**MS13-053**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-053)
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-054)
</td>
<td style="border:1px solid black;">
[**MS13-055**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-055)
</td>
<td style="border:1px solid black;">
[**MS13-056**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-056)
</td>
<td style="border:1px solid black;">
[**MS13-057**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-057)
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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2850851)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(Windows GDI+)  
(2834886)  
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
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2850851)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(Windows GDI+)  
(2834886)  
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
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2833946)  
(重大)  
Microsoft .NET Framework 3.5.1  
(2840631)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2844286)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(重大)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)  
Microsoft .NET Framework 4.5  
(2833957)  
(重大)  
Microsoft .NET Framework 4.5  
(2840642)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(2850851)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(Windows GDI+)  
(2834886)  
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
Windows Server 2012 (Server Core 安裝)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2832418)  
(重大)  
Microsoft .NET Framework 3.5  
(2833959)  
(重大)  
Microsoft .NET Framework 3.5  
(2840633)  
(重要)  
Microsoft .NET Framework 3.5  
(2844289)  
(重要)  
Microsoft .NET Framework 4.5  
(2833958)  
(重大)  
Microsoft .NET Framework 4.5  
(2840632)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(2850851)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(DirectWrite)  
(2835361)  
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
</table>
 
**MS13-052** **注意事項**

<sup>[1]</sup>**.NET Framework 4** **和** **.NET Framework 4 Client Profile** **會受到影響。**可在兩個設定檔中使用 .NET Framework 第 4 版可轉散發套件： .NET Framework 4 和 .NET Framework 4 Client Profile。.NET Framework 4 Client Profile 是 .NET Framework 4 的子集。此更新所解決的資訊安全風險會同時影響到 .NET Framework 4 和 .NET Framework 4 Client Profile。如需詳細資訊，請參閱 MSDN 文章：[安裝 .NET Framework](http://msdn.microsoft.com/library/5a4x27ek)。

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

**MS13-053** **及** **MS13-055** **注意事項**

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

**MS13-054** **注意事項**

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

**MS13-057** **注意事項**

<sup>[1]</sup>此更新僅提供給已升級為 Windows Media Format Runtime 11 或 Windows Media Player 11 的系統。
<sup>[2]</sup>此更新僅提供給執行 Windows Media Format Runtime 9.5 NL 的系統。
<sup>[3]</sup>此更新僅提供給執行 Windows Media Format Runtime 9.5 L 的系統。
\[4\]此更新僅在選用「桌面體驗」功能啟用的情況下提供。
\[5\] 此更新僅在選用「桌面體驗」功能啟用且 wmv9vcm.dll 轉碼器存在的情況下提供。請參閱公告，了解詳細資訊。

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

#### Microsoft Office 套件及軟體


<p></p> 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Office 軟體
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-054)
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
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3  
(2817480)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2687309)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32 位元版本)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32 位元版本)  
(2687276)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64 位元版本)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64 位元版本)  
(2687276)  
(重要)
</td>
</tr>
</table>
 
**MS13-054** **注意事項**

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

#### Microsoft 開發者工具和軟體


<p></p> 
<table style="border:1px solid black;">
<tr>
<th colspan="3">
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-052**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-052)
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-054)
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
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003 Service Pack 1<sup>[1]</sup>
(2856545)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Silverlight
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
[**MS13-052**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-052)
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-054)
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
**無**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
安裝在 Mac 上的 Microsoft Silverlight 5  
(2847559)  
(重大)  
安裝在 Mac 上的 Microsoft Silverlight 5 Developer Runtime  
(2847559)  
(重大)  
安裝在 32 位元版本的 Microsoft Windows 用戶端的 Microsoft Silverlight 5  
(2847559)  
(重大)  
安裝在 x64 版本的 Microsoft Windows 用戶端的 Microsoft Silverlight 5  
(2847559)  
(重大)  
安裝在所有受支援版本之 Microsoft Windows 用戶端上的 Microsoft Silverlight 5 Developer Runtime  
(2847559)  
(重大)  
安裝在 32 位元版本的 Microsoft Windows 伺服器的 Microsoft Silverlight 5  
(2847559)  
(重大)  
安裝在 x64 版本的 Microsoft Windows 伺服器的 Microsoft Silverlight 5  
(2847559)  
(重大)  
安裝在所有受支援版本之 Microsoft Windows 伺服器上的 Microsoft Silverlight 5 Developer Runtime  
(2847559)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
</table>
 
**MS13-052** **注意事項**

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

**MS13-054** **注意事項**

<sup>[1]</sup>這個更新程式僅可以從 Microsoft 下載中心取得。

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

#### Microsoft 通訊平台和軟體


<p></p> 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Lync
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-054)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 位元)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 位元)  
(2843160)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 位元)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 位元)  
(2843160)  
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(使用者層級安裝)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(使用者層級安裝)  
(2843162)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(系統管理員層級安裝)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(系統管理員層級安裝)  
(2843163)  
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 (32 位元)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 (32 位元)  
(2817465)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (32 位元)
</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (32 位元)  
(2817465)  
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 (64 位元)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 (64 位元)  
(2817465)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (64 位元)
</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (64 位元)  
(2817465)  
(重大)
</td>
</tr>
</table>
 
**MS13-054** **注意事項**

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類 

#### Microsoft 資訊安全軟體


<p></p> 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
反間諜軟體
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-058**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-058)
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
適用於 Windows 7 (x86) 的 Windows Defender
</td>
<td style="border:1px solid black;">
適用於 Windows 7 (x86) 的 Windows Defender   
(2847927)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Windows 7 (x64) 的 Windows Defender
</td>
<td style="border:1px solid black;">
適用於 Windows 7 (x64) 的 Windows Defender   
(2847927)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
安裝在 Windows Server 2008 R2 (x64) 上的 Windows Defender
</td>
<td style="border:1px solid black;">
安裝在 Windows Server 2008 R2 (x64) 上的 Windows Defender   
(2847927)  
(重要)
</td>
</tr>
</table>
 

偵測與部署工具及指南
--------------------


**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和資訊安全更新。如需更多資訊，請參閱 [TechNet 更新管理中心](http://technet.microsoft.com/zh-tw/updatemanagement/default.aspx) (英文)。[TechNet 資訊安全技術中心](http://technet.microsoft.com/zh-tw/security/default.aspx)提供 Microsoft 產品資訊安全的其他資訊。一般消費者可造訪 [Microsoft Safety & Security Center](http://technet.microsoft.com/zh-tw/security/default.aspx) (英文)，並點選 \[Security Updates\] (資訊安全更新) 來取得上述資訊。

資訊安全更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 以及 [Windows Update](http://update.microsoft.com/windowsupdate/v6/default.aspx) 取得。資訊安全更新也可以從 [Microsoft 下載中心](http://www.microsoft.com/zh-tw/download/search.aspx?q=security%20update)取得。您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。

對於 Microsoft Office for Mac 的客戶，Microsoft AutoUpdate for Mac 可協助您保持最新的 Microsoft 軟體。如需使用 Microsoft AutoUpdate for Mac 的詳細資訊，請參閱[自動檢查軟體更新](http://mac2.microsoft.com/help/office/14/zh-tw/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea) (英文)。

最後，您可以從 [Microsoft Update Catalog](http://catalog.update.microsoft.com/v7/site/install.aspx) 下載資訊安全更新。Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括資訊安全更新、驅動程式和 Service Pack。只要以資訊安全公告編號 (例如：MS13-001) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](http://catalog.update.microsoft.com/v7/site/faq.aspx)。

**偵測與部署指南**

Microsoft 針對資訊安全更新提供偵測和部署指南。本指南所含之建議和資訊，能幫助 IT 專業人員瞭解如何使用用於資訊安全更新的偵測和部署的各種工具。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 961747](http://support.microsoft.com/kb/961747?ln=zh-tw)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少資訊安全更新以及一般資訊安全設定錯誤的狀況。如需更多有關 MBSA 的資訊，請參閱 [Microsoft Baseline Security Analyzer](http://technet.microsoft.com/zh-tw/security/cc184924.aspx) (英文)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速而可靠地將 Microsoft Windows 2000 作業系統及更新版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 適用的最新重大更新與資訊安全更新部署到 Microsoft Windows 2000 及更新版本的作業系統中。

如需更多關於利用 Windows Server Update Services 部署資訊安全更新的資訊，請造訪 [Windows Server Update Services](http://technet.microsoft.com/wsus/default) (英文)。

**System Center Configuration Manager**

System Center Configuration Manager 軟體更新管理可簡化遞送和管理企業中 IT 系統更新的繁複作業。IT 系統管理員可以使用 System Center Configuration Manager 遞送 Microsoft 產品更新給各種裝置，包括桌上型電腦、筆記型電腦、伺服器及行動裝置。

System Center Configuration Manager 中的自動資訊安全風險評估會找出更新需求並報告建議動作。System Center Configuration Manager 中的軟體更新管理是建置在 Microsoft Windows Software Update Services (WSUS) 上，經過時間考驗，為全球 IT 系統管理員所熟悉的更新基礎架構。如需更多有關 System Center Configuration Manager 的資訊，請造訪 [System Center 技術資源](http://technet.microsoft.com/systemcenter/bb980621)。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。透過 SMS，系統管理員能判斷有哪些 Windows 系統需要資訊安全更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。

**注意：**System Management Server 2003 自 2010 年 1 月 12 日起不受主流支援。如需更多有關產品生命週期的資訊，請造訪 [Microsoft 支援週期](http://support.microsoft.com/default.aspx?scid=fh;%5bln%5d;lifecycle?ln=zh-tw)。現已推出新版的 SMS，System Center Configuration Manager；請參閱前段的＜System Center Configuration Manager＞一節。

如需更多有關系統管理員如何使用 SMS 2003 來部署資訊安全更新的資訊，請參閱 [Microsoft Systems Management Server 2003 的案例與程序： 軟體發佈和補充程式管理](https://www.microsoft.com/download/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f) (英文)。如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server 技術中心 (TechCenter)](http://technet.microsoft.com/systemcenter/bb545936)。

**注意**：SMS 使用 Microsoft Baseline Security Analyzer 提供廣泛的資訊安全公告更新偵測與部署支援。不過這些工具可能無法偵測部分的軟體更新。在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](http://technet.microsoft.com/zh-tw/library/cc917507.aspx) (英文)。某些資訊安全更新程式在電腦重新啟動之後，會需要系統管理員的權限。系統管理員可使用 Elevated Rights Deployment Tool (隨附於 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d)) 來安裝這些更新。

**Update Compatibility Evaluator** **和** **Application Compatibility Toolkit**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。這可能會觸發不相容性，而拉長部署資訊安全更新的時間。您可以使用 [Application Compatibility Toolkit](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971) 隨附的 [Update Compatibility Evaluator](http://technet.microsoft.com/library/cc749197) 元件，針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Windows Vista、Windows Update、Microsoft 資訊安全更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

針對每個月第二個星期二發行的公告，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 及下載中心發行更新版本的 Microsoft Windows 惡意軟體移除工具。不定期資訊安全公告發行不提供更新版本的 Microsoft Windows 惡意軟體移除工具。

#### MU、WU 及 WSUS 上的非資訊安全更新

如需在 Windows Update 和 Microsoft Update 上發行的非資訊安全更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](http://support.microsoft.com/kb/894199?ln=zh-tw)
-   ： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](http://technet.microsoft.com/wsus/bb456965)
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

**MS13-052**

-   感謝 [F-13 Laboratory](http://www.f13-labs.net/) 的 Ling Chuan Lee 和 Lee Yee Chan 回報 TrueType 字型剖析資訊安全風險 (CVE-2013-3129)
-   感謝 Alon Fliess 回報陣列存取違規資訊安全風險 (CVE-2013-3131)
-   感謝 [Context Information Security](http://www.contextis.com/) 的 James Forshaw 回報委派反映略過資訊安全風險 (CVE-2013-3132)
-   感謝 [Context Information Security](http://www.contextis.com/) 的 James Forshaw 回報匿名方法插入資訊安全風險 (CVE-2013-3133)
-   感謝 [Context Information Security](http://www.contextis.com/) 的 James Forshaw 回報委派序列化資訊安全風險 (CVE-2013-3171)
-   感謝 Vitaliy Toropov 回報 Null 指標資訊安全風險 (CVE-2013-3178)

**MS13-053**

-   感謝 MWR Labs 的 Jon Butler 和 Nils 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 Win32k 記憶體配置資訊安全風險 (CVE-2013-1300)
-   感謝 [Dr.Web](http://drweb.com/) 的 Alexander Chizhov 回報 Win32k 解除參照資訊安全風險 (CVE-2013-1340)
-   感謝匿名的研究人員與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 Win32k 視窗控制資訊安全風險 (CVE-2013-1345)
-   感謝 [F13 Laboratory](http://www.f13-labs.net/) 的 Ling Chuan Lee 和 Lee Yee Chan 回報 TrueType 字型剖析資訊安全風險 (CVE-2013-3129)
-   感謝 [Tencent PC Manager](http://guanjia.qq.com/) 的Yinliang 回報 Win32k 資訊洩漏資訊安全風險 (CVE-2013-3167)
-   感謝 [Google Inc](http://www.google.com/) 的 [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org/) 回報 Win32k 緩衝區溢位資訊安全風險 (CVE-2013-3172)
-   感謝 [Qihoo 360 Security Center](http://www.360.cn/) 的 Wen Yujie 和 Guo Pengfei 回報 Win32k 緩衝區覆寫資訊安全風險 (CVE-2013-3173)

**MS13-054**

-   感謝 [F13 Laboratory](http://www.f13-labs.net/) 的 Ling Chuan Lee 和 Lee Yee Chan 回報 TrueType 字型剖析資訊安全風險 (CVE-2013-3129)

**MS13-055**

-   感謝 [Google Security Team](http://www.google.com/) 的 Ivan Fratric 和 Ben Hawkes 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3115)
-   感謝 SkyLined 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3143)
-   感謝 Simon Zuckerbraun 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3144)
-   感謝 Toan Pham Van 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3145)
-   感謝 Toan Pham Van 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3146)
-   感謝 [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com) 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3147)
-   感謝 Bluesea 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3148)
-   感謝 Bluesea 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3149)
-   感謝 [Omair](http://krash.in/) 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3150)
-   感謝 Toan Pham Van 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3151)
-   感謝匿名的研究人員與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3152)
-   感謝 e6af8de8b1d4b2b6d5ba2610cbf9cd38 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3153)
-   感謝 [Google Security Team](http://www.google.com/) 的 Ivan Fratric 和 Ben Hawkes 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3161)
-   感謝 [Google Security Team](http://www.google.com/) 的 Ivan Fratric 和 Ben Hawkes 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3162)
-   感謝 Jose Antonio Vazquez Gonzalez 與 [VeriSign iDefense Labs](http://labs.idefense.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3163)
-   感謝 [Security-Assessment.com](http://www.security-assessment.com/) 的 Scott Bell 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3164)
-   感謝 Masato Kinugawa 回報 Shift JIS 字元編碼資訊安全風險 (CVE-2013-3166)
-   感謝 IBM X-Force 的 Mark Yason 協助我們開發本公告提供的一項深度防禦變更 (CVE-2013-4015)

**MS13-056**

-   感謝 Andrés Gómez Ramírez 回報 DirectShow 任意記憶體覆寫資訊安全風險 - CVE-2013-3174

**MS13-057**

-   感謝匿名的研究人員與 [HP](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 WMV 視訊解碼器遠端執行程式碼資訊安全風險 (CVE-2013-3127)

**MS13-058**

-   感謝 [Reserve Bank of Australia](http://www.rba.gov.au/) 的 Alton Blom 回報 Microsoft Windows 7 Defender 不當路徑名稱資訊安全風險 (CVE-2013-3154)

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 支援週期](http://support.microsoft.com/default.aspx?scid=fh;%5bln%5d;lifecycle?ln=zh-tw)。
-   IT 專業人員的資訊安全解決方案： [TechNet 資訊安全疑難排解與支援](http://technet.microsoft.com/security/bb980617)
-   協助保護您的 Windows 電腦免於病毒和惡意軟體攻擊： [病毒解決方案與資訊安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-tw)
-   您所在國家/地區的當地支援： [國際支援](http://support.microsoft.com/common/international.aspx?ln=zh-tw)

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2013 年 7 月 9 日)： 公告摘要發行。
-   V1.1 (2013 年 7 月 9 日)： 針對 MS13-055，修訂＜資訊安全風險入侵指數＞中對於 CVE-2013-3163 的資訊安全風險評估。Microsoft 已發現嘗試透過 Internet Explorer 8 利用此資訊安全風險的目標式攻擊。
-   V2.0 (2013 年 8 月 13 日)： 針對 MS13-052，修訂公告以重新發行 2840628、2840632、2840642、2844285、2844286、2844287 和 2844289 更新。針對 MS13-057，修訂公告以重新發行 Windows 7 和 Windows 2008 R2 的 2803821 更新。客戶應安裝適用於本身系統的重新發行更新。請參閱其個別公告內容以瞭解詳細資訊。
-   V3.0 (2013 年 9 月 11 日)： 針對 MS13-057，修訂公告以重新發行適用於 Windows XP、Windows Server 2003、Windows Vista 和 Windows Server 2008 的資訊安全更新 2803821；適用於 Windows XP 和 Windows Server 2003 的資訊安全更新 2834902；適用於 Windows XP 的資訊安全更新 2834903；適用於 Windows XP 和 Windows Server 2003 的資訊安全更新 2834904；適用於 Windows XP 的資訊安全更新 2834905。Windows XP、Windows Server 2003、Windows Vista 和 Windows Server 2008 的客戶應安裝適用於本身系統的重新發行更新。請參閱公告內容以瞭解詳細資訊。

*Built at 2014-04-18T01:50:00Z-07:00*
