---
TOCTitle: 'MS16-MAR'
Title: 2016 年 3 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms16-mar'
ms:contentKeyID: 72464257
ms:date: '03/31/2016'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms16-mar(v=Security.10)'
---

2016 年 3 月份 Microsoft 資訊安全公告摘要
=========================================

發行日期：2016 年 3 月 8 日 | 更新日期：2016 年 3 月 25 日

**版本：** 3.1

此公告摘要列出 2016 年 3 月份所發行的資訊安全公告。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://technet.microsoft.com/zh-tw/security/dd252948.aspx)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性更新的優先順序，其中這些非安全性更新的發行日期與每月安全性更新的發行日期相同。請參閱**＜其他資訊＞**一節。

提要
----

<span id="sectionToggle0"></span>
下表依嚴重性摘要說明本月份資訊安全公告。

如需受影響的軟體之詳細資料，請參閱下節**＜受影響的軟體＞**。

<table style="width:100%;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告識別碼</strong></td>
<td style="border:1px solid black;"><strong>公告標題與提要</strong></td>
<td style="border:1px solid black;"><strong>最高的嚴重性等級<br />
和弱點影響</strong></td>
<td style="border:1px solid black;"><strong>重新啟動需求</strong></td>
<td style="border:1px solid black;"><strong>已知<br />
問題</strong></td>
<td style="border:1px solid black;"><strong>受影響的軟體</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-023">MS16-023</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 積存安全性更新 (3142015)<br />
</strong>此安全性更新可解決 Internet Explorer 中的弱點。其中最嚴重的弱點，可能在使用者以 Internet Explorer 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用此弱點的攻擊者可以取得與目前使用者相同的使用者權限。如果目前的使用者以系統管理使用者權限登入，則成功利用此弱點的攻擊者可以取得受影響系統的控制權。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-024">MS16-024</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 的累積安全性更新 (3142019)<br />
</strong>此安全性更新可解決 Microsoft Edge 中的弱點。其中最嚴重的弱點，可能在使用者以 Microsoft Edge 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用這些弱點的攻擊者可以取得與本機使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-025">MS16-025</a></td>
<td style="border:1px solid black;"><strong>用來解決遠端執行程式碼的 Windows Library Loading 安全性更新 (3140709)</strong><br />
此安全性更新可解決 Microsoft Windows 中的弱點。當 Microsoft Windows 無法在載入某些程式庫之前正確地驗證載入時，此弱點可能會允許遠端程式碼。不過，攻擊者必須先存取本機系統才能執行惡意應用程式。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-026">MS16-026</a></td>
<td style="border:1px solid black;"><strong>用來解決遠端執行程式碼的圖形字體安全性更新 (3143148)</strong><br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者引誘使用者開啟蓄意製作的文件，或造訪包含蓄意製作的內嵌 OpenType 字型的網頁，則更嚴重的弱點可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-027">MS16-027</a></td>
<td style="border:1px solid black;"><strong>用來解決遠端執行程式碼的 Windows Media 安全性更新 (3143146)</strong><br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果使用者開啟網站上託管的蓄意製作之媒體內容，此弱點可能允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-028">MS16-028</a></td>
<td style="border:1px solid black;"><strong>用來解決遠端執行程式碼的 Microsoft Windows PDF 程式庫安全性更新 (3143081)</strong><br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果使用者開啟蓄意製作的 .pdf 檔案，此弱點可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-029">MS16-029</a></td>
<td style="border:1px solid black;"><strong>用來解決遠端執行程式碼的 Microsoft Office 安全性更新 (3141806)</strong><br />
此安全性更新可解決 Microsoft Office 中的弱點。如果使用者開啟蓄意製作的 Microsoft Office 檔案，最嚴重的弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者，能以目前使用者的權限層級執行任意程式碼。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft Office Services 和 Web Apps、<br />
Microsoft 伺服器軟體</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-030">MS16-030</a></td>
<td style="border:1px solid black;"><strong>用來解決遠端執行程式碼的 Windows OLE 安全性更新 (3143136)</strong><br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果 Windows OLE 無法正確地驗證使用者輸入，這些弱點可能允許遠端執行程式碼。攻擊者可利用弱點來執行惡意程式碼。然而，攻擊者必須先引誘使用者從網頁或電子郵件訊息中開啟蓄意製作的檔案或程式。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-031">MS16-031</a></td>
<td style="border:1px solid black;"><strong>用來解決權限提高的 Microsoft Windows 安全性更新 (3140410)</strong><br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者可登入系統並執行蓄意製作的應用程式，則弱點可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-032">MS16-032</a></td>
<td style="border:1px solid black;"><strong>用來解決權限提高的 Secondary Logon 安全性更新 (3143141)</strong><br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果 Windows Secondary Logon 服務無法正確管理記憶體中的要求處理程式，此弱點可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-033">MS16-033</a></td>
<td style="border:1px solid black;"><strong>用來解決權限提高的 Windows USB 大型存放裝置類別驅動程式的安全性更新 (3143142)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者擁有將蓄意製作的 USB 裝置插入系統的實體存取權，該弱點可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-034">MS16-034</a></td>
<td style="border:1px solid black;"><strong>用來解決權限提高的 Windows 核心模式驅動程式安全性更新 (3143145)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者登入系統並執行蓄意製作的應用程式，則這些弱點可能允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-035">MS16-035</a></td>
<td style="border:1px solid black;"><strong>解決資訊安全功能略過的 .NET Framework 安全性更新 (3141780)</strong><br />
這個安全性更新可解決 Microsoft .NET Framework 中的一個弱點。若未適當驗證已簽署 XML 文件的特定元素，.NET Framework 元件存在資訊安全功能略過弱點。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
資訊安全功能略過</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;"><a href="http://support.microsoft.com/zh-tw/kb/3135996">3135996</a><br />
<a href="http://support.microsoft.com/zh-tw/kb/3136000">3136000</a><br />
<a href="http://support.microsoft.com/zh-tw/kb/3149737">3149737</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3148821">3148821</a></td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-036">MS16-036</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player 的安全性更新 (3144756)</strong><br />
此安全性更新可解決安裝於 Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1 和 Windows 10 上之 Adobe Flash Player 中的弱點。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Adobe Flash Player</td>
</tr>
</tbody>
</table>
 

弱點入侵指數
------------

<span id="sectionToggle1"></span>
下表提供本月所述每個弱點的利用性評估。會依序按公告編號及 CVE ID 的順序列出弱點。只會包含公告中嚴重性等級為「重大」或「重要」的弱點。

**我該如何使用這個表格？**

您可以運用此表格，針對您可能需要安裝的每一項安全性更新，瞭解弱點在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務 (DoS) 的可能性。請根據您特定的組態設定，檢閱下列各項評估，決定部署本月份更新的優先次序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點入侵指數](http://technet.microsoft.com/zh-tw/security/cc998259)。

在下方欄位中，「最新軟體版本」意指受影響軟體，「較舊軟體版本」意指受影響軟體所有較舊的支援版本，如公告中的「受影響的軟體」或「不受影響的軟體」表格裡所示。

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**CVE ID**                    

</td>
<td style="border:1px solid black;">
**弱點標題**

</td>
<td style="border:1px solid black;" colspan="2">
**較早軟體版本的  
弱點評估**

</td>
<td style="border:1px solid black;">
**較早軟體版本的  
弱點評估**

</td>
<td style="border:1px solid black;">
**阻斷服務  
弱點評估**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-023：Internet Explorer 累積安全性更新 (3142015)**](https://technet.microsoft.com/zh-tw/library/security/ms16-023)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0102](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0102)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0103](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0103)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
4 - 不受影響

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0104](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0104)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
4 - 不受影響

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0105](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0105)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0106](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0106)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
4 - 不受影響

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0107](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0107)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0108](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0108)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0109](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0109)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0110](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0110)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0111](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0111)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0112](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0112)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0113](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0113)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0114](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0114)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-024：Microsoft Edge 的累積安全性更新 (3142019)**](https://technet.microsoft.com/zh-tw/library/security/ms16-024)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0102](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0102)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
4 - 不受影響

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0105](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0105)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
4 - 不受影響

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0109](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0109)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
4 - 不受影響

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0110](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0110)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
4 - 不受影響

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0111](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0111)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
4 - 不受影響

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0116](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0116)

</td>
<td style="border:1px solid black;">
Microsoft Edge 記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
4 - 不受影響

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0123](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0123)

</td>
<td style="border:1px solid black;">
Microsoft Edge 記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
4 - 不受影響

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0124](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0124)

</td>
<td style="border:1px solid black;">
Microsoft Edge 記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
4 - 不受影響

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0125](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0125)

</td>
<td style="border:1px solid black;">
Microsoft Edge 資訊洩漏弱點

</td>
<td style="border:1px solid black;" colspan="2">
3 - 不太可能遭到利用

</td>
<td style="border:1px solid black;">
4 - 不受影響

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0129](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0129)

</td>
<td style="border:1px solid black;">
Microsoft Edge 記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
4 - 不受影響

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0130](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0130)

</td>
<td style="border:1px solid black;">
Microsoft Edge 記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
4 - 不受影響

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-025：用來解決遠端執行程式碼的 Windows Library Loading 安全性更新 (3140709)**](https://technet.microsoft.com/zh-tw/library/security/ms16-025)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0100](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0100)

</td>
<td style="border:1px solid black;">
程式庫載入輸入的驗證遠端執行程式碼弱點

</td>
<td style="border:1px solid black;" colspan="2">
4 - 不受影響

</td>
<td style="border:1px solid black;">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-026：用來解決遠端執行程式碼的圖形字體安全性更新 (3143148)**](https://technet.microsoft.com/zh-tw/library/security/ms16-026)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0120](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0120)

</td>
<td style="border:1px solid black;">
OpenType 字型剖析弱點

</td>
<td style="border:1px solid black;" colspan="2">
3 - 不太可能遭到利用

</td>
<td style="border:1px solid black;">
3 - 不太可能遭到利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0121](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0121)

</td>
<td style="border:1px solid black;">
OpenType 字型剖析弱點

</td>
<td style="border:1px solid black;" colspan="2">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-027：用來解決遠端執行程式碼的 Windows Media 安全性更新 (3143146)**](https://technet.microsoft.com/zh-tw/library/security/ms16-027)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0098](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0098)

</td>
<td style="border:1px solid black;">
Windows Media 剖析遠端執行程式碼弱點

</td>
<td style="border:1px solid black;" colspan="2">
4 - 不受影響

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0101](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0101)

</td>
<td style="border:1px solid black;">
Windows Media 剖析遠端執行程式碼弱點

</td>
<td style="border:1px solid black;" colspan="2">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-028：用來解決遠端執行程式碼的 Microsoft Windows PDF 程式庫安全性更新 (3143081)**](https://technet.microsoft.com/zh-tw/library/security/ms16-028)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0117](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0117)

</td>
<td style="border:1px solid black;">
Windows 遠端執行程式碼弱點

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0118](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0118)

</td>
<td style="border:1px solid black;">
Windows 遠端執行程式碼弱點

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-029：用來解決遠端執行程式碼的 Microsoft Office 安全性更新 (3141806)**](https://technet.microsoft.com/zh-tw/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0021](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0021)

</td>
<td style="border:1px solid black;">
Microsoft Office 記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
4 - 不受影響

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0057](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0057)

</td>
<td style="border:1px solid black;">
Microsoft Office 資訊安全功能略過弱點

</td>
<td style="border:1px solid black;" colspan="2">
3 - 不太可能遭到利用

</td>
<td style="border:1px solid black;">
3 - 不太可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0134](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0134)

</td>
<td style="border:1px solid black;">
Microsoft Office 記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-030：用來解決遠端執行程式碼的 Windows OLE 安全性更新 (3143136)**](https://technet.microsoft.com/zh-tw/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0091](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0091)

</td>
<td style="border:1px solid black;">
Windows OLE 記憶體遠端執行程式碼弱點

</td>
<td style="border:1px solid black;" colspan="2">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0092](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0092)

</td>
<td style="border:1px solid black;">
Windows OLE 記憶體遠端執行程式碼弱點

</td>
<td style="border:1px solid black;" colspan="2">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-031：用來解決權限提高的 Microsoft Windows 安全性更新 (3140410)**](https://technet.microsoft.com/zh-tw/library/security/ms16-031)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0087](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0087)

</td>
<td style="border:1px solid black;">
Windows 權限提高弱點

</td>
<td style="border:1px solid black;" colspan="2">
4 - 不受影響

</td>
<td style="border:1px solid black;">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-032：用來解決權限提高的 Secondary Logon 安全性更新 (3143141)**](https://technet.microsoft.com/zh-tw/library/security/ms16-032)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0099](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0099)

</td>
<td style="border:1px solid black;">
Secondary Logon 權限提高弱點

</td>
<td style="border:1px solid black;" colspan="2">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-033：用來解決權限提高的 Windows USB 大型存放裝置類別驅動程式的安全性更新 (3143142)**](https://technet.microsoft.com/zh-tw/library/security/ms16-033)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0133](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0133)

</td>
<td style="border:1px solid black;">
USB 大型存放裝置權限提高弱點

</td>
<td style="border:1px solid black;" colspan="2">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-034：用來解決權限提高的 Windows 核心模式驅動程式安全性更新 (3143145)**](https://technet.microsoft.com/zh-tw/library/security/ms16-034)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0093](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0093)

</td>
<td style="border:1px solid black;">
Win32k 權限提高弱點

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0094](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0094)

</td>
<td style="border:1px solid black;">
Win32k 權限提高弱點

</td>
<td style="border:1px solid black;" colspan="2">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0095](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0095)

</td>
<td style="border:1px solid black;">
Win32k 權限提高弱點

</td>
<td style="border:1px solid black;" colspan="2">
4 - 不受影響

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0096](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0096)

</td>
<td style="border:1px solid black;">
Win32k 權限提高弱點

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-035：用來解決資訊安全功能略過的 .NET Framework 安全性更新 (3141780)**](https://technet.microsoft.com/zh-tw/library/security/ms16-035)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0132](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0132)

</td>
<td style="border:1px solid black;">
.NET XML 驗證資訊安全功能略過

</td>
<td style="border:1px solid black;" colspan="2">
3 - 不太可能遭到利用

</td>
<td style="border:1px solid black;">
3 - 不太可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-036：Adobe Flash Player 的安全性更新 (3144756)**](https://technet.microsoft.com/zh-tw/library/security/ms16-036)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-08](https://helpx.adobe.com/tw/security/products/flash-player/apsb16-08.html)

</td>
<td style="border:1px solid black;">
請參閱 [Adobe 資訊安全公告 APSB16-08](https://helpx.adobe.com/tw/security/products/flash-player/apsb16-08.html) 以了解弱點嚴重性和更新的優先順序級別。

</td>
<td style="border:1px solid black;" colspan="2">
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
 

受影響的軟體
------------

<span id="sectionToggle2"></span>
下表依據主要的軟體類別和嚴重性依序列出公告。

請用這些表格來瞭解可能需要安裝的安全性更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的安全性更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。

**注意**：一項弱點，可能需要安裝數個安全性更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。

 

### Windows 作業系統及元件 (表格 2 之 1)

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/zh-tw/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/zh-tw/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/zh-tw/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/zh-tw/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/zh-tw/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/zh-tw/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/zh-tw/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3139929)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3140709)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3140735)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3139940)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3139929)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3140709)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3140735)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3139940)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/zh-tw/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/zh-tw/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/zh-tw/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/zh-tw/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/zh-tw/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/zh-tw/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/zh-tw/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3139929)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3140709)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3140735)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3139940)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3139929)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3140709)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3140735)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3139940)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3140709)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3140735)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3139940)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/zh-tw/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/zh-tw/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/zh-tw/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/zh-tw/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/zh-tw/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/zh-tw/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/zh-tw/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3139929)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3140735)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3138910)  
(重大)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3138962)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3139940)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3139929)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows 7 Service Pack 1  
(3140735)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows 7 Service Pack 1  
(3138910)  
(重大)  
適用於 x64 系統的 Windows 7 Service Pack 1  
(3138962)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows 7 Service Pack 1  
(3139940)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/zh-tw/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/zh-tw/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/zh-tw/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/zh-tw/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/zh-tw/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/zh-tw/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/zh-tw/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3139929)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(3140735)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(3138910)  
(重大)  
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(3138962)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(3139940)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

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
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3140735)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3139940)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/zh-tw/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/zh-tw/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/zh-tw/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/zh-tw/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/zh-tw/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/zh-tw/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/zh-tw/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3139929)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3140735)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3138910)  
(重大)  
適用於 32 位元系統的 Windows 8.1  
(3138962)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3137513)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3139940)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3139929)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3140735)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3138910)  
(重大)  
適用於 x64 型系統的 Windows 8.1  
(3138962)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3137513)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3139940)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/zh-tw/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/zh-tw/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/zh-tw/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/zh-tw/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/zh-tw/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/zh-tw/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/zh-tw/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3139929)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3140735)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3138910)  
(重大)  
Windows Server 2012  
(3138962)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3137513)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3139940)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3139929)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3140735)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3138910)  
(重大)  
Windows Server 2012 R2  
(3138962)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3137513)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3139940)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/zh-tw/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/zh-tw/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/zh-tw/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/zh-tw/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/zh-tw/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/zh-tw/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/zh-tw/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3139929)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3140735)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3138910)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3137513)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3139940)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/zh-tw/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/zh-tw/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/zh-tw/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/zh-tw/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/zh-tw/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/zh-tw/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/zh-tw/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3140745)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3140745)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3140745)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3140745)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3140745)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3140745)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3140745)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3140745)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3140745)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3140745)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3140745)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3140745)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3140768)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3140768)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3140768)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3140768)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3140768)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3140768)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3140768)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3140768)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3140768)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3140768)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3140768)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3140768)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Server Core 安裝選項**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/zh-tw/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/zh-tw/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/zh-tw/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/zh-tw/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/zh-tw/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/zh-tw/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/zh-tw/library/security/ms16-030)

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
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3140709)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3140735)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3139940)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3140709)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3140735)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3139940)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)

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
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3140735)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3139940)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)

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
Windows Server 2012 (Server Core 安裝)  
(3140735)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3139940)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)

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
Windows Server 2012 R2 (Server Core 安裝)  
(3140735)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3137513)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3139940)  
(重要)

</td>
</tr>
</table>
 
 

### Windows 作業系統及元件 (表格 2 之 2)

 
<table style="border:1px solid black;">
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
[**MS16-031**](https://technet.microsoft.com/zh-tw/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/zh-tw/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/zh-tw/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/zh-tw/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/zh-tw/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/zh-tw/library/security/ms16-036)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
Windows Vista Service Pack 2  
(3140410)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3139914)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3139398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3139852)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3135982)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3135987)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3135996)  
(重要)  
Microsoft .NET Framework 4.6  
(3136000)  
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
Windows Vista x64 Edition Service Pack 2  
(3140410)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3139914)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3139398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3139852)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3135982)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3135987)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3135996)  
(重要)  
Microsoft .NET Framework 4.6  
(3136000)  
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
[**MS16-031**](https://technet.microsoft.com/zh-tw/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/zh-tw/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/zh-tw/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/zh-tw/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/zh-tw/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/zh-tw/library/security/ms16-036)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3140410)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3139914)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3139398)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3139852)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3135982)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3135987)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3135996)  
(重要)  
Microsoft .NET Framework 4.6  
(3136000)  
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
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3140410)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3139914)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3139398)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3139852)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3135982)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3135987)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3135996)  
(重要)  
Microsoft .NET Framework 4.6  
(3136000)  
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
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3140410)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3139914)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3139398)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3139852)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3135982)  
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
[**MS16-031**](https://technet.microsoft.com/zh-tw/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/zh-tw/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/zh-tw/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/zh-tw/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/zh-tw/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/zh-tw/library/security/ms16-036)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3140410)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3139914)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3139398)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3139852)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3135983)  
(重要)  
Microsoft .NET Framework 3.5.1  
(3135988)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3135996)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3136000)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows 7 Service Pack 1  
(3140410)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows 7 Service Pack 1  
(3139914)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows 7 Service Pack 1  
(3139398)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows 7 Service Pack 1  
(3139852)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3135983)  
(重要)  
Microsoft .NET Framework 3.5.1  
(3135988)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3135996)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3136000)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

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
[**MS16-031**](https://technet.microsoft.com/zh-tw/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/zh-tw/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/zh-tw/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/zh-tw/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/zh-tw/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/zh-tw/library/security/ms16-036)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(3140410)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(3139914)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(3139398)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(3139852)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3135983)  
(重要)  
Microsoft .NET Framework 3.5.1  
(3135988)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3135996)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3136000)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3140410)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3139914)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3139398)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3139852)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3135983)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-031**](https://technet.microsoft.com/zh-tw/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/zh-tw/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/zh-tw/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/zh-tw/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/zh-tw/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/zh-tw/library/security/ms16-036)

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
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3139914)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3139398)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3139852)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135985)  
(重要)  
Microsoft .NET Framework 3.5  
(3135991)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3135994)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3135998)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3139914)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3139398)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3139852)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135985)  
(重要)  
Microsoft .NET Framework 3.5  
(3135991)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3135994)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3135998)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
(重大)

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
[**MS16-031**](https://technet.microsoft.com/zh-tw/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/zh-tw/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/zh-tw/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/zh-tw/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/zh-tw/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/zh-tw/library/security/ms16-036)

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
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3139914)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3139398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3139852)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135984)  
(重要)  
Microsoft .NET Framework 3.5  
(3135989)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3135995)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3135997)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3139914)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3139398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3139852)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135985)  
(重要)  
Microsoft .NET Framework 3.5  
(3135991)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3135994)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3135998)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-031**](https://technet.microsoft.com/zh-tw/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/zh-tw/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/zh-tw/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/zh-tw/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/zh-tw/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/zh-tw/library/security/ms16-036)

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
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3139914)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3139398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3139852)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3135994)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3135998)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-031**](https://technet.microsoft.com/zh-tw/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/zh-tw/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/zh-tw/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/zh-tw/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/zh-tw/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/zh-tw/library/security/ms16-036)

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
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3140745)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3140745)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3140745)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3140745)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3140745)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3140745)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3140745)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3140745)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3140745)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3140745)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3140768)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3140768)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3140768)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3140768)  
(重要)  
Microsoft .NET Framework 4.6.1  
(3140768)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3140768)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3140768)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3140768)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3140768)  
(重要)  
Microsoft .NET Framework 4.6.1  
(3140768)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
(重大)

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
[**MS16-031**](https://technet.microsoft.com/zh-tw/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/zh-tw/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/zh-tw/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/zh-tw/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/zh-tw/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/zh-tw/library/security/ms16-036)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3140410)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3139914)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3139398)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3139852)  
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
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3140410)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3139914)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3139398)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3139852)  
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
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)  
(3140410)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)  
(3139914)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)  
(3139398)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)  
(3139852)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3135983)  
(重要)  
Microsoft .NET Framework 3.5.1  
(3135988)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3135996)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)  
(3139914)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)  
(3139398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)  
(3139852)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135984)  
(重要)  
Microsoft .NET Framework 3.5  
(3135989)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3135995)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3135997)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)  
(3139914)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)  
(3139398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)  
(3139852)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135985)  
(重要)  
Microsoft .NET Framework 3.5  
(3135991)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3135994)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3135998)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
</table>
 
 

### Microsoft Office 套件及軟體

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-029**](https://technet.microsoft.com/zh-tw/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2956110)  
(重要)  
Microsoft InfoPath 2007 Service Pack 3  
(3114426)  
(重要)  
Microsoft Outlook 2007 Service Pack 3  
(2880510)  
(重要)  
Microsoft Word 2007 Service Pack 3  
(3114901)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-029**](https://technet.microsoft.com/zh-tw/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(2956063)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(3114873)  
(重要)  
Microsoft InfoPath 2010 Service Pack 2 (32 位元版本)  
(3114414)  
(重要)  
Microsoft Outlook 2010 Service Pack 2 (32 位元版本)  
(3114883)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 位元版本)  
(3114878)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3114873)  
(重要)  
Microsoft InfoPath 2010 Service Pack 2 (64 位元版本)  
(3114414)  
(重要)  
Microsoft Outlook 2010 Service Pack 2 (64 位元版本)  
(3114883)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 位元版本)  
(3114878)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-029**](https://technet.microsoft.com/zh-tw/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 位元版本)  
(3039746)  
(重要)  
Microsoft InfoPath 2013 Service Pack 1 (32 位元版本)  
(3114833)  
(重要)  
Microsoft Outlook 2013 Service Pack 1 (32 位元版本)  
(3114829)  
(重要)  
Microsoft Word 2013 Service Pack 1 (32 位元版本)  
(3114824)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft InfoPath 2013 Service Pack 1 (64 位元版本)  
(3114833)  
(重要)  
Microsoft Outlook 2013 Service Pack 1 (64 位元版本)  
(3114829)  
(重要)  
Microsoft Word 2013 Service Pack 1 (64 位元版本)  
(3114824)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-029**](https://technet.microsoft.com/zh-tw/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Outlook 2013 RT Service Pack 1  
(3114829)  
(重要)  
Microsoft Word 2013 RT Service Pack 1  
(3114824)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-029**](https://technet.microsoft.com/zh-tw/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2016 (32 位元版本)  
(3114690)  
(重要)  
Microsoft Outlook 2016 (32 位元版本)  
(3114861)  
(重要)  
Microsoft Word 2016 (32 位元版本)  
(3114855)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Outlook 2016 (64 位元版本)  
(3114861)  
(重要)  
Microsoft Word 2016 (64 位元版本)  
(3114855)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office for Mac 2011**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-029**](https://technet.microsoft.com/zh-tw/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Word for Mac 2011  
(3138328)<sup>[1]</sup>
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2016 for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-029**](https://technet.microsoft.com/zh-tw/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Word 2016 for Mac  
(3138327)<sup>[1]</sup>
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**其他 Office 軟體**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-029**](https://technet.microsoft.com/zh-tw/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 相容性套件 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 相容性套件 Service Pack 3  
(3114900)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3114812)  
(重要)

</td>
</tr>
</table>
 
**MS16-029 注意事項**

<sup>[1]</sup>自 2016 年 3 月 16 日起，適用於 Microsoft Office 2016 for Mac 的 3138327 更新及適用於 Microsoft Office for Mac 2011 的 3138328 更新已可供使用。請注意，適用於 Microsoft Outlook 2016 for Mac 的 3138327 更新尚未於 3 月 16 日發行。我們會在更新可供使用時立即發行，並將透過公告修訂通知使用者。如需詳細資訊，請參閱 [Microsoft 知識庫文章 3138327](https://support.microsoft.com/zh-tw/kb/3138327) 和 [Microsoft 知識庫文章 3138328](https://support.microsoft.com/zh-tw/kb/3138328)。

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

 

### Microsoft Office Services 和 Web Apps

 
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
[**MS16-029**](https://technet.microsoft.com/zh-tw/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3114866)  
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
[**MS16-029**](https://technet.microsoft.com/zh-tw/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3114814)  
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
[**MS16-029**](https://technet.microsoft.com/zh-tw/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3114880)  
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
[**MS16-029**](https://technet.microsoft.com/zh-tw/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3114821)  
(重要)

</td>
</tr>
</table>
 
**MS16-029 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

偵測與部署工具及指南
--------------------

<span id="sectionToggle3"></span>
有幾項資源可協助系統管理員部署安全性更新。

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，查看是否遺漏安全性更新及一般資訊安全設定錯誤的狀況。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 可協助系統管理員發佈安全性更新。

應用程式相容性工具組隨附的 Update Compatibility Evaluator 元件可針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

如需上述工具以及其他可使用工具的詳細資訊，請參閱 [IT 專業人員的資訊安全工具](http://technet.microsoft.com/zh-tw/security/cc297183)。

致謝
----

<span id="sectionToggle4"></span>
Microsoft 了解資訊安全業界所做的努力，其盡責地透露弱點來協助我們保護客戶。請參閱[致謝](https://technet.microsoft.com/zh-tw/library/security/dn903755.aspx) (英文) 以取得詳細資訊。

其他資訊
--------

<span id="sectionToggle5"></span>
### Microsoft Windows 惡意軟體移除工具 (英文)

針對每個月第二個星期二發行的公告，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 及下載中心發行更新版本的 Microsoft Windows 惡意軟體移除工具。不定期資訊安全公告發行不提供更新版本的 Microsoft Windows 惡意軟體移除工具。

### MU、WU 及 WSUS 上的非安全性更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [Microsoft 知識庫文章 894199](https://support.microsoft.com/zh-tw/kb/894199)：Software Update Services 與 Windows Server Update Services 的說明內容有所變動。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](http://technet.microsoft.com/zh-tw/windowsserver/bb332157.aspx)。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的資訊安全保護，Microsoft 將在每月發行安全性更新之前，提前向重要資訊安全軟體提供者提供弱點資訊。資訊安全軟體提供者可利用此弱點，透過其資訊安全軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://technet.microsoft.com/zh-tw/security/dn467918) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

### 安全性策略與社群

**更新程式管理策略**

[更新管理資訊安全指南](http://technet.microsoft.com/zh-tw/library/bb466251.aspx) (英文) 提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他資訊安全問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得，您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-tw) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。如需更多資訊，請參閱 [Microsoft 知識庫文章編號 913086](https://support.microsoft.com/zh-tw/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](http://technet.microsoft.com/zh-tw/security/cc136632.aspx)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

### 支援

所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](https://support.microsoft.com/zh-tw/lifecycle)。

適用於 IT 專業人員的安全性解決方案：[TechNet 安全性疑難排解與支援](http://technet.microsoft.com/zh-tw/security/bb980617)

協助保護您的 Widows 電腦免於病毒和惡意軟體攻擊：[病毒解決方案與資訊安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-tw)

您所在國家/地區的當地支援：[多語系支援](http://support.microsoft.com/common/international.aspx?ln=zh-tw)

### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

### 修訂

-   V1.0 (2016 年 3 月 8 日)：公告摘要發行。
-   V2.0 (2016 年 3 月 10 日)：修訂公告摘要，以記錄不定期發行的 MS16-036。
-   V2.1 (2016 年 3 月 10 日)：新增已知問題參考至 MS16-035 的「提要」表格。如需詳細資訊，請參閱 [Microsoft 知識庫文章 3148821](https://support.microsoft.com/zh-tw/kb/3148821)。
-   V2.2 (2016 年 3 月 15 日)：新增已知問題參考至 MS16-035 的「提要」表格。如需詳細資訊，請參閱 [Microsoft 知識庫文章 3135996](http://support.microsoft.com/zh-tw/kb/3135996)、[Microsoft 知識庫文章 3136000](http://support.microsoft.com/zh-tw/kb/3136000) 及 [Microsoft 知識庫文章 3149737](http://support.microsoft.com/zh-tw/kb/3149737)。
-   V3.0 (2016 年 3 月 16 日)：針對 MS16-029，新增適用於 Microsoft Office 2016 for Mac 的 3138327 更新及適用於 Microsoft Office for Mac 2011 的 3138328 更新 (自 2016 年 3 月 16 日起已可供使用)。請注意，適用於 Microsoft Outlook 2016 for Mac 的 3138327 更新尚未於 3 月 16 日發行。我們會在更新可供使用時立即發行，並將透過公告修訂通知使用者。如需詳細資訊，請參閱 [Microsoft 知識庫文章 3138327](https://support.microsoft.com/zh-tw/kb/3138327) 和 [Microsoft 知識庫文章 3138328](https://support.microsoft.com/zh-tw/kb/3138328)。
-   V3.1 (2016年 3月 25日)：針對 MS16-028，從「Windows 作業系統和元件」 (表格 1，共 2 個表格) 中移除 Windows Server 2012 (Server Core 安裝)，因為 Windows Server 2012 不會受到影響。這只是資訊的變更。

*頁面產生時間：2016-03-25 11:32-07:00。*
