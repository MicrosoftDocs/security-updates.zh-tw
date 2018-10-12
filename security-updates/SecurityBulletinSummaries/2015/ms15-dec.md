---
TOCTitle: 'MS15-DEC'
Title: 2015 年 12 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms15-dec'
ms:contentKeyID: 72045332
ms:date: '12/21/2015'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms15-dec(v=Security.10)'
---

2015 年 12 月份 Microsoft 資訊安全公告摘要
==========================================

發行日期：2015 年 12 月 8 日 | 更新日期：2015 年 12 月 16 日

**版本：** 1.2

此公告摘要列出 2015 年 12 月份發行之資訊安全公告。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://technet.microsoft.com/zh-tw/security/dd252948.aspx)。

Microsoft 也會提供資訊協助客戶排定每月資訊安全更新以及任何非資訊安全更新的優先順序，其中這些非資訊安全更新的發行日期與每月資訊安全更新的發行日期相同。請參閱**＜其他資訊＞**一節。

提要
----

下表依嚴重性摘要說明本月份資訊安全公告。

如需受影響的軟體之詳細資料，請參閱下節**＜受影響的軟體＞**。

<p></p>
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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-124">MS15-124</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 累積安全性更新 (3116180)</strong> <br />
此安全性更新可解決 Internet Explorer 中的弱點。其中最嚴重的弱點，可能在使用者以 Internet Explorer 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用這些弱點的攻擊者可以取得與本機使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3104002">3104002</a></td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-125">MS15-125</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 的累積安全性更新 (3116184)<br />
</strong>此安全性更新可解決 Microsoft Edge 中的弱點。其中最嚴重的弱點，可能在使用者以 Microsoft Edge 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用這些弱點的攻擊者可以取得與本機使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-126">MS15-126</a></td>
<td style="border:1px solid black;"><strong>用來解決遠端執行程式碼的 JScript 和 VBScript 累積安全性更新 (3116178)<br />
</strong>這個安全性更新可解決 Microsoft Windows 的 VBScript 指令碼引擎中的弱點。如果攻擊者針對這些經由 Internet Explorer 引起的弱點來設計並架設蓄意製作的網站 (或利用遭到入侵的網站或接受或主控使用者提供之內容或廣告的網站)，然後引誘使用者檢視該網站，則較嚴重的弱點可能會允許遠端執行程式碼。攻擊者也可以嵌入 ActiveX 控制項，該控制項在使用 Internet Explorer 轉譯引擎來引導使用者前往蓄意製作之網站的應用程式或 Microsoft Office 文件中標示為「安全的初始化」。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-127">MS15-127</a></td>
<td style="border:1px solid black;"><strong>用來解決遠端執行程式碼的 Microsoft Windows DNS 安全性更新 (3100465)</strong> <br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者傳送蓄意製作的要求到 DNS 伺服器，這項弱點可允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-128">MS15-128</a></td>
<td style="border:1px solid black;"><strong>用來解決遠端執行程式碼的 Microsoft 圖形元件的安全性更新 (3104503)</strong> <br />
此安全性更新可以解決 Microsoft Windows、.NET Framework、Microsoft Office、商務用 Skype、Microsoft Lync 和 Silverlight 中的弱點。如果使用者開啟蓄意製作的文件，或是造訪包含蓄意內嵌字型的網頁，此弱點可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework、<br />
Microsoft Office、<br />
商務用 Skype、Microsoft Lync、<br />
Silverlight</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-129">MS15-129</a></td>
<td style="border:1px solid black;"><strong>用來解決遠端執行程式碼的 Silverlight 安全性更新 (3106614)</strong> <br />
此安全性更新可解決 Microsoft Silverlight 中的弱點。如果 Microsoft Silverlight 未正確處理會導致讀取和寫入存取違規的特定開啟和關閉要求，這些弱點最嚴重時會允許遠端程式碼執行。如果要利用此弱點，攻擊者會架設包含蓄意製作的 Silverlight 應用程式的網站，然後引誘使用者造訪受侵害的網站。攻擊者也可能利用包含蓄意製作的內容的網站，包括接受或裝載使用者提供內容或廣告的網站。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">不需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-130">MS15-130</a></td>
<td style="border:1px solid black;"><strong>用來解決遠端執行程式碼的 Microsoft Uniscribe 安全性更新 (3108670)</strong><br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果使用者開啟蓄意製作的文件，或是造訪包含蓄意製作字型的不受信任網頁，此弱點可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-131">MS15-131</a></td>
<td style="border:1px solid black;"><strong>用來解決遠端執行程式碼的 Microsoft Office 安全性更新 (3116111)</strong><br />
此安全性更新可解決 Microsoft Office 中的弱點。如果使用者開啟蓄意製作的 Microsoft Office 檔案，最嚴重的弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者，能以目前使用者的權限層級執行任意程式碼。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-132">MS15-132</a></td>
<td style="border:1px solid black;"><strong>用來解決遠端執行程式碼的 Microsoft Windows 安全性更新 (3116162)</strong><br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者存取本機系統並執行蓄意製作的應用程式，則這些弱點可能會允許遠端程式碼執行。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-133">MS15-133</a></td>
<td style="border:1px solid black;"><strong>用來解決權限提高的 Windows PGM 安全性更新 (3116130)</strong><br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者登入目標系統並執行蓄意製作的應用程式，此弱點就可能會允許權限提高，透過使用競爭情況的方式，導致參考已釋放的記憶體位置。必須安裝 Microsoft Message Queuing (MSMQ) 且 Windows Pragmatic General Multicast (PGM) 通訊協定特別為有弱點的系統啟用。MSMQ 並未顯示在預設的設定中，如果已安裝，即可使用 PGM 通訊協定，但是預設為停用。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-134">MS15-134</a></td>
<td style="border:1px solid black;"><strong>用來解決遠端執行程式碼的 Windows Media Center 安全性更新 (3108669)</strong> <br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果 Windows Media Center 開啟參考惡意程式碼的蓄意製作 Media Center 連結 (.mcl) 檔案，則更嚴重的弱點可能會允許遠端執行程式碼。成功利用此弱點的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-135">MS15-135</a></td>
<td style="border:1px solid black;"><strong>用來解決權限提高的 Windows 核心模式驅動程式安全性更新 (3119075)</strong><br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者登入目標系統並執行蓄意製作的應用程式，弱點就可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
弱點入侵指數  
------------
  
下表提供本月所述每個弱點的利用性評估。會依序按公告編號及 CVE ID 的順序列出弱點。只會包含公告中嚴重性等級為「重大」或「重要」的弱點。
  
**我該如何使用這個表格？**
  
您可以運用此表格，針對您可能需要安裝的每一項安全性更新，瞭解弱點在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務 (DoS) 的可能性。請根據您特定的組態設定，檢閱下列各項評估，決定部署本月份更新的優先次序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](http://technet.microsoft.com/zh-tw/security/cc998259)。
  
在下方欄位中，「最新軟體版本」意指受影響軟體，「較舊軟體版本」意指受影響軟體所有較舊的支援版本，如公告中的「受影響的軟體」或「不受影響的軟體」表格裡所示。

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**CVE ID**                    

</td>
<td style="border:1px solid black;">
**弱點標題**

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS15-124：Internet Explorer 積存安全性更新 (3116180)**](https://technet.microsoft.com/zh-tw/library/security/ms15-124)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6083](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6083)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6134](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6134)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6135](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6135)

</td>
<td style="border:1px solid black;">
指令碼引擎資訊洩漏弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6136](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6136)

</td>
<td style="border:1px solid black;">
指令碼引擎記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6138](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6138)

</td>
<td style="border:1px solid black;">
Internet Explorer XSS 篩選略過弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6139](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6139)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器權限提高弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6140](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6140)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6141](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6141)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6142](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6142)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6143](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6143)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6144](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6144)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器 XSS 篩選略過弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6145](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6145)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6146](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6146)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6147](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6147)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6148](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6148)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6149](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6149)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6150](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6150)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6151](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6151)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6152](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6152)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6153](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6153)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6154](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6154)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6155](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6155)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6156](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6156)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6157](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6157)

</td>
<td style="border:1px solid black;">
Internet Explorer 資訊洩漏弱點

</td>
<td style="border:1px solid black;">
2 - 遭到利用的可能性較小

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
[CVE-2015-6158](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6158)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6159](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6159)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6160](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6160)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6161](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6161)

</td>
<td style="border:1px solid black;">
Internet Explorer ASLR 略過

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6162](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6162)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6164](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6164)

</td>
<td style="border:1px solid black;">
Internet Explorer XSS 篩選略過弱點

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS15-125：Microsoft Edge 的累積安全性更新 (3116184)**](https://technet.microsoft.com/zh-tw/library/security/ms15-125)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6139](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6139)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器權限提高弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6140](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6140)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6142](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6142)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6148](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6148)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6151](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6151)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6153](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6153)

</td>
<td style="border:1px solid black;">
Microsoft Edge 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6154](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6154)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6155](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6155)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6158](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6158)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6159](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6159)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6161](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6161)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器 ASLR 略過

</td>
<td style="border:1px solid black;">
2 - 遭到利用的可能性較小

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
[CVE-2015-6168](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6168)

</td>
<td style="border:1px solid black;">
Microsoft Edge 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6169](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6169)

</td>
<td style="border:1px solid black;">
Microsoft Edge 詐騙弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6170](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6170)

</td>
<td style="border:1px solid black;">
Microsoft Edge 權限提高弱點

</td>
<td style="border:1px solid black;">
2 - 遭到利用的可能性較小

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
[CVE-2015-6176](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6176)

</td>
<td style="border:1px solid black;">
Microsoft Edge XSS 篩選略過弱點

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS15-126：用來解決遠端執行程式碼的 JScript 和 VBScript 累積安全性更新 (3116178)**](https://technet.microsoft.com/zh-tw/library/security/ms15-126)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6135](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6135)

</td>
<td style="border:1px solid black;">
指令碼引擎資訊洩漏弱點

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;">
[CVE-2015-6136](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6136)

</td>
<td style="border:1px solid black;">
指令碼引擎記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS15-127：用來解決遠端執行程式碼的 Microsoft Windows DNS 安全性更新 (3100465)**](https://technet.microsoft.com/zh-tw/library/security/ms15-127)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6125](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6125)

</td>
<td style="border:1px solid black;">
Windows DNS 釋放後使用弱點

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS15-128：用來解決遠端執行程式碼的 Microsoft 圖形元件的安全性更新 (3104503)**](https://technet.microsoft.com/zh-tw/library/security/ms15-128)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6106](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6106)

</td>
<td style="border:1px solid black;">
圖形記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6107](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6107)

</td>
<td style="border:1px solid black;">
圖形記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6108](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6108)

</td>
<td style="border:1px solid black;">
圖形記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS15-129：用來解決遠端執行程式碼的 Silverlight 安全性更新 (3106614)**](https://technet.microsoft.com/zh-tw/library/security/ms15-129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6114](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6114)

</td>
<td style="border:1px solid black;">
Microsoft Silverlight 資訊洩漏弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6165](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6165)

</td>
<td style="border:1px solid black;">
Microsoft Silverlight 資訊洩漏弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6166](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6166)

</td>
<td style="border:1px solid black;">
Microsoft Silverlight 遠端程式碼執行弱點

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS15-130：用來解決遠端執行程式碼的 Microsoft Uniscribe 安全性更新 (3108670)**](https://technet.microsoft.com/zh-tw/library/security/ms15-130)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6130](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6130)

</td>
<td style="border:1px solid black;">
Windows 整數反向溢位弱點

</td>
<td style="border:1px solid black;">
4 - 不受影響

</td>
<td style="border:1px solid black;">
3 - 不太可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS15-131：用來解決遠端執行程式碼的 Microsoft Office 安全性更新 (3116111)**](https://technet.microsoft.com/zh-tw/library/security/ms15-131)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6040](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6040)

</td>
<td style="border:1px solid black;">
Microsoft Office 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6118](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6118)

</td>
<td style="border:1px solid black;">
Microsoft Office 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6122](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6122)

</td>
<td style="border:1px solid black;">
Microsoft Office 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6124](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6124)

</td>
<td style="border:1px solid black;">
Microsoft Office 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6172](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6172)

</td>
<td style="border:1px solid black;">
Microsoft Office RCE 弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6177](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6177)

</td>
<td style="border:1px solid black;">
Microsoft Office 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS15-132：用來解決遠端執行程式碼的 Microsoft Windows 安全性更新 (3116162)**](https://technet.microsoft.com/zh-tw/library/security/ms15-132)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6128](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6128)

</td>
<td style="border:1px solid black;">
Windows 程式庫載入遠端程式碼執行弱點

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;">
[CVE-2015-6132](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6132)

</td>
<td style="border:1px solid black;">
Windows 程式庫載入遠端程式碼執行弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6133](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6133)

</td>
<td style="border:1px solid black;">
Windows 程式庫載入遠端程式碼執行弱點

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS15-133：用來解決權限提高的 Windows PGM 安全性更新 (3116130)**](https://technet.microsoft.com/zh-tw/library/security/ms15-133)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6126](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6126)

</td>
<td style="border:1px solid black;">
Windows PGM UAF 權限提高弱點

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS15-134：用來解決權限提高的 Windows PGM 安全性更新 (3116130)**](https://technet.microsoft.com/zh-tw/library/security/ms15-134)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6127](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6127)

</td>
<td style="border:1px solid black;">
Windows Media Center 資訊洩漏弱點

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;">
[CVE-2015-6131](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6131)

</td>
<td style="border:1px solid black;">
Media Center 媒體櫃剖析 RCE 弱點

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS15-135：用來解決權限提高的 Windows 核心模式驅動程式安全性更新 (3119075)**](https://technet.microsoft.com/zh-tw/library/security/ms15-135)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6171](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6171)

</td>
<td style="border:1px solid black;">
Windows 核心記憶體權限提升弱點

</td>
<td style="border:1px solid black;">
3 - 不太可能遭到利用

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
[CVE-2015-6173](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6173)

</td>
<td style="border:1px solid black;">
Windows 核心記憶體權限提升弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6174](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6174)

</td>
<td style="border:1px solid black;">
Windows 核心記憶體權限提升弱點

</td>
<td style="border:1px solid black;">
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
[CVE-2015-6175](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6175)

</td>
<td style="border:1px solid black;">
Windows 核心記憶體權限提升弱點

</td>
<td style="border:1px solid black;">
0 - 已偵測到利用

</td>
<td style="border:1px solid black;">
4 - 不受影響

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
</table>
 

受影響的軟體
------------

下表依據主要的軟體類別和嚴重性依序列出公告。

請用這些表格來瞭解可能需要安裝的資訊安全更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的資訊安全更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。

**注意**：一項弱點，可能需要安裝數個資訊安全更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。

 

### Windows 作業系統及元件 (表格 2 之 1)

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-124**](https://technet.microsoft.com/zh-tw/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/zh-tw/library/security/ms15-125)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/zh-tw/library/security/ms15-126)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/zh-tw/library/security/ms15-127)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-tw/library/security/ms15-128)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3104002)  
(重大)  
Internet Explorer 8  
(3104002)  
(重大)  
Internet Explorer 9  
(3104002)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3105579)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3109094)  
(重大)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3099860)  
(重大)  
Microsoft .NET Framework 4  
(3099866)  
(重大)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3099869)  
(重大)  
Microsoft .NET Framework 4.6  
(3099874)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3104002)  
(重大)  
Internet Explorer 8  
(3104002)  
(重大)  
Internet Explorer 9  
(3104002)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3105579)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3109094)  
(重大)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3099860)  
(重大)  
Microsoft .NET Framework 4  
(3099866)  
(重大)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3099869)  
(重大)  
Microsoft .NET Framework 4.6  
(3099874)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-124**](https://technet.microsoft.com/zh-tw/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/zh-tw/library/security/ms15-125)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/zh-tw/library/security/ms15-126)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/zh-tw/library/security/ms15-127)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-tw/library/security/ms15-128)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3104002)  
(中度)  
Internet Explorer 8  
(3104002)  
(中度)  
Internet Explorer 9  
(3104002)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3105579)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3100465)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3109094)  
(重大)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3099860)  
(重大)  
Microsoft .NET Framework 4  
(3099866)  
(重大)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3099869)  
(重大)  
Microsoft .NET Framework 4.6  
(3099874)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3104002)  
(中度)  
Internet Explorer 8  
(3104002)  
(中度)  
Internet Explorer 9  
(3104002)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3105579)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3100465)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3109094)  
(重大)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3099860)  
(重大)  
Microsoft .NET Framework 4  
(3099866)  
(重大)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3099869)  
(重大)  
Microsoft .NET Framework 4.6  
(3099874)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3104002)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3105579)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3109094)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-124**](https://technet.microsoft.com/zh-tw/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/zh-tw/library/security/ms15-125)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/zh-tw/library/security/ms15-126)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/zh-tw/library/security/ms15-127)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-tw/library/security/ms15-128)

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
**無**

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3104002)  
(重大)  
Internet Explorer 9  
(3104002)  
(重大)  
Internet Explorer 10  
(3104002)  
(重大)  
Internet Explorer 11  
(3104002)  
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
Windows 7 32 位元系統 Service Pack 1  
(3109094)  
(重大)  
Microsoft .NET Framework 3.5.1  
(3099862)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3104002)  
(重大)  
Internet Explorer 9  
(3104002)  
(重大)  
Internet Explorer 10  
(3104002)  
(重大)  
Internet Explorer 11  
(3104002)  
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
Windows 7 x64 系統 Service Pack 1  
(3109094)  
(重大)  
Microsoft .NET Framework 3.5.1  
(3099862)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-124**](https://technet.microsoft.com/zh-tw/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/zh-tw/library/security/ms15-125)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/zh-tw/library/security/ms15-126)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/zh-tw/library/security/ms15-127)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-tw/library/security/ms15-128)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3104002)  
(中度)  
Internet Explorer 9  
(3104002)  
(中度)  
Internet Explorer 10  
(3104002)  
(中度)  
Internet Explorer 11  
(3104002)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3100465)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3109094)  
(重大)  
Microsoft .NET Framework 3.5.1  
(3099862)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3104002)  
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
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3109094)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-124**](https://technet.microsoft.com/zh-tw/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/zh-tw/library/security/ms15-125)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/zh-tw/library/security/ms15-126)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/zh-tw/library/security/ms15-127)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-tw/library/security/ms15-128)

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
**無**

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 32 位元系統

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3104002)  
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
Windows 8 32 位元系統  
(3109094)  
(重大)  
Microsoft .NET Framework 3.5  
(3099863)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3104002)  
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
適用於 x64 型系統的 Windows 8  
(3109094)  
(重大)  
Microsoft .NET Framework 3.5  
(3099863)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3104002)  
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
Windows 8.1 32 位元系統  
(3109094)  
(重大)  
Microsoft .NET Framework 3.5  
(3099864)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3104002)  
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
適用於 x64 型系統的 Windows 8.1  
(3109094)  
(重大)  
Microsoft .NET Framework 3.5  
(3099864)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-124**](https://technet.microsoft.com/zh-tw/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/zh-tw/library/security/ms15-125)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/zh-tw/library/security/ms15-126)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/zh-tw/library/security/ms15-127)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-tw/library/security/ms15-128)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3104002)  
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
(3100465)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3109094)  
(重大)  
Microsoft .NET Framework 3.5  
(3099863)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3104002)  
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
(3100465)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3109094)  
(重大)  
Microsoft .NET Framework 3.5  
(3099864)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-124**](https://technet.microsoft.com/zh-tw/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/zh-tw/library/security/ms15-125)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/zh-tw/library/security/ms15-126)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/zh-tw/library/security/ms15-127)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-tw/library/security/ms15-128)

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
**無**

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3104002)  
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
Windows RT  
(3109094)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3104002)  
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
Windows RT 8.1  
(3109094)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-124**](https://technet.microsoft.com/zh-tw/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/zh-tw/library/security/ms15-125)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/zh-tw/library/security/ms15-126)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/zh-tw/library/security/ms15-127)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-tw/library/security/ms15-128)

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
**無**

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 32 位元系統

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3116869)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3116869)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 10 32 位元系統  
(3116869)  
(重大)  
Microsoft .NET Framework 3.5  
(3116869)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3116869)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3116869)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3116869)  
(重大)  
Microsoft .NET Framework 3.5  
(3116869)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3116900)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3116900)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3116900)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3116900)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3116900)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3116900)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Server Core 安裝選項**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-124**](https://technet.microsoft.com/zh-tw/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/zh-tw/library/security/ms15-125)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/zh-tw/library/security/ms15-126)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/zh-tw/library/security/ms15-127)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-tw/library/security/ms15-128)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
VBScript 5.7  
(3105579)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3100465)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3109094)  
(重大)

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
VBScript 5.7  
(3105579)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3100465)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3109094)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.8  
(3105578)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(Server Core 安裝)  
(3100465)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(Server Core 安裝)  
(3109094)  
(重大)  
Microsoft .NET Framework 3.5.1  
(3099862)  
(重大)

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
Windows Server 2012  
(Server Core 安裝)  
(3100465)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)  
(3109094)  
(重大)  
Microsoft .NET Framework 3.5  
(3099863)  
(重大)

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
Windows Server 2012 R2  
(Server Core 安裝)  
(3100465)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)  
(3109094)  
(重大)  
Microsoft .NET Framework 3.5  
(3099864)  
(重大)

</td>
</tr>
</table>
 
**MS15-128 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

 

### Windows 作業系統及元件 (表格 2 之 2)

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-130**](https://technet.microsoft.com/zh-tw/library/security/ms15-130)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/zh-tw/library/security/ms15-132)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/zh-tw/library/security/ms15-133)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/zh-tw/library/security/ms15-134)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/zh-tw/library/security/ms15-135)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3108371)  
(重要)  
Windows Vista Service Pack 2  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3109094)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3108371)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3109094)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Server 2008**

</td>
<td style="border:1px solid black;" colspan="3">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-130**](https://technet.microsoft.com/zh-tw/library/security/ms15-130)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/zh-tw/library/security/ms15-132)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/zh-tw/library/security/ms15-133)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/zh-tw/library/security/ms15-134)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/zh-tw/library/security/ms15-135)

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
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3108371)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3109094)  
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
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3108371)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3109094)  
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
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3108371)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3109103)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3109094)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-130**](https://technet.microsoft.com/zh-tw/library/security/ms15-130)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/zh-tw/library/security/ms15-132)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/zh-tw/library/security/ms15-133)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/zh-tw/library/security/ms15-134)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/zh-tw/library/security/ms15-135)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3108670)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3108371)  
(重要)  
Windows 7 32 位元系統 Service Pack 1  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3109103)

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3109094)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3108670)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3108371)  
(重要)  
Windows 7 x64 系統 Service Pack 1  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3109103)

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3109094)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-130**](https://technet.microsoft.com/zh-tw/library/security/ms15-130)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/zh-tw/library/security/ms15-132)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/zh-tw/library/security/ms15-133)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/zh-tw/library/security/ms15-134)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/zh-tw/library/security/ms15-135)

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
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
Windows Server 2008 R2 x64 系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3108670)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3108371)  
(重要)  
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3109094)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3108670)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3108371)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3109094)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-130**](https://technet.microsoft.com/zh-tw/library/security/ms15-130)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/zh-tw/library/security/ms15-132)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/zh-tw/library/security/ms15-133)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/zh-tw/library/security/ms15-134)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/zh-tw/library/security/ms15-135)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 32 位元系統

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3108347)  
(重要)  
Windows 8 32 位元系統  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3109094)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(3108347)  
(重要)  
適用於 x64 型系統的 Windows 8  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(3109094)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3108347)  
(重要)  
Windows 8.1 32 位元系統  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3109094)  
(重要)

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
(3108347)  
(重要)  
適用於 x64 型系統的 Windows 8.1  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3109094)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-130**](https://technet.microsoft.com/zh-tw/library/security/ms15-130)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/zh-tw/library/security/ms15-132)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/zh-tw/library/security/ms15-133)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/zh-tw/library/security/ms15-134)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/zh-tw/library/security/ms15-135)

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
**無**

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
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3108347)  
(重要)  
Windows Server 2012  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3109094)  
(重要)

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
(3108347)  
(重要)  
Windows Server 2012 R2  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3109094)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-130**](https://technet.microsoft.com/zh-tw/library/security/ms15-130)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/zh-tw/library/security/ms15-132)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/zh-tw/library/security/ms15-133)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/zh-tw/library/security/ms15-134)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/zh-tw/library/security/ms15-135)

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
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT  
(3108347)  
(重要)  
Windows RT  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT  
(3109094)  
(重要)

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
(3108347)  
(重要)  
Windows RT 8.1  
(3108381)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3109094)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-130**](https://technet.microsoft.com/zh-tw/library/security/ms15-130)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/zh-tw/library/security/ms15-132)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/zh-tw/library/security/ms15-133)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/zh-tw/library/security/ms15-134)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/zh-tw/library/security/ms15-135)

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
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 32 位元系統

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 10 32 位元系統  
(3116869)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 32 位元系統  
(3116869)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 10 32 位元系統  
(3116869)  
(重要)

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
(3116869)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3116869)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3116869)  
(重要)

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
(3116900)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3116900)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3116900)  
(重要)

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
(3116900)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3116900)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3116900)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Server Core 安裝選項**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-130**](https://technet.microsoft.com/zh-tw/library/security/ms15-130)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/zh-tw/library/security/ms15-132)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/zh-tw/library/security/ms15-133)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/zh-tw/library/security/ms15-134)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/zh-tw/library/security/ms15-135)

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
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3109094)  
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
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3109094)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(Server Core 安裝)  
(3108670)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(Server Core 安裝)  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(Server Core 安裝)  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(Server Core 安裝)  
(3109094)  
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
Windows Server 2012  
(Server Core 安裝)  
(3108347)  
(重要)  
Windows Server 2012  
(Server Core 安裝)  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)  
(3109094)  
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
Windows Server 2012 R2  
(Server Core 安裝)  
(3108347)  
(重要)  
Windows Server 2012 R2  
(Server Core 安裝)  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)  
(3109094)  
(重要)

</td>
</tr>
</table>
 
 

### Microsoft Office 套件及軟體

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-tw/library/security/ms15-128)

</td>
<td style="border:1px solid black;">
[**MS15-131**](https://technet.microsoft.com/zh-tw/library/security/ms15-131)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3085616)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3085549)  
(重要)  
Microsoft Excel 2007 Service Pack 3  
(3114422)  
(重要)  
Microsoft Word 2007 Service Pack 3  
(3114458)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-tw/library/security/ms15-128)

</td>
<td style="border:1px solid black;">
[**MS15-131**](https://technet.microsoft.com/zh-tw/library/security/ms15-131)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(3085612)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(3085528)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(3114403)  
(重大)  
Microsoft Excel 2010 Service Pack 2 (32 位元版本)  
(3114415)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 位元版本)  
(3101532)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3085612)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3085528)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3114403)  
(重大)  
Microsoft Excel 2010 Service Pack 2 (64 位元版本)  
(3114415)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 位元版本)  
(3101532)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-tw/library/security/ms15-128)

</td>
<td style="border:1px solid black;">
[**MS15-131**](https://technet.microsoft.com/zh-tw/library/security/ms15-131)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 位元版本)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 Service Pack 1 (32 位元版本)  
(3114342)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 位元版本)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 Service Pack 1 (64 位元版本)  
(3114342)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-tw/library/security/ms15-128)

</td>
<td style="border:1px solid black;">
[**MS15-131**](https://technet.microsoft.com/zh-tw/library/security/ms15-131)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Word 2016 (32 位元版本)  
(3114382)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Word 2016 (64 位元版本)  
(3114382)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-tw/library/security/ms15-128)

</td>
<td style="border:1px solid black;">
[**MS15-131**](https://technet.microsoft.com/zh-tw/library/security/ms15-131)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 RT Service Pack 1  
(3114342)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-tw/library/security/ms15-128)

</td>
<td style="border:1px solid black;">
[**MS15-131**](https://technet.microsoft.com/zh-tw/library/security/ms15-131)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Excel for Mac 2011  
(3119517)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 for Mac  
(3119518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**其他 Office 軟體**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-tw/library/security/ms15-128)

</td>
<td style="border:1px solid black;">
[**MS15-131**](https://technet.microsoft.com/zh-tw/library/security/ms15-131)

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
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 相容性套件 Service Pack 3

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Office 相容性套件 Service Pack 3  
(3114457)  
(重大)  
Microsoft Office 相容性套件 Service Pack 3  
(3114431)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3114433)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3114478)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
</table>
 
**MS15-128 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

 

### Microsoft 通訊平台和軟體

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Live Meeting 2007 Console**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-tw/library/security/ms15-128)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console

</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console  
(3115875)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Lync 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-tw/library/security/ms15-128)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 位元)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 位元)  
(3115871)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 位元)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 位元)  
(3115871)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(使用者層次安裝)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(使用者層次安裝)  
(3115872)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(系統管理員層次安裝)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(系統管理員層次安裝)  
(3115873)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Lync 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-tw/library/security/ms15-128)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (32 位元)  
(商務用 Skype)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (32 位元)  
(商務用 Skype)  
(3114351)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (32 位元)  
(商務用 Skype 基本版)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (32 位元)  
(商務用 Skype 基本版)  
(3114351)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (64 位元)  
(商務用 Skype)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (64 位元)  
(商務用 Skype)  
(3114351)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (64 位元)  
(商務用 Skype 基本版)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (64 位元)  
(商務用 Skype 基本版)  
(3114351)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**商務用 Skype 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-tw/library/security/ms15-128)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
商務用 Skype 2016 (32 位元)

</td>
<td style="border:1px solid black;">
商務用 Skype 2016 (32 位元)  
(3114372)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
商務用 Skype 基本版 2016 (32 位元)

</td>
<td style="border:1px solid black;">
商務用 Skype 基本版 2016 (32 位元)  
(3114372)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
商務用 Skype 2016 (64 位元)

</td>
<td style="border:1px solid black;">
商務用 Skype 2016 (64 位元)  
(3114372)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
商務用 Skype 基本版 2016 (64 位元)

</td>
<td style="border:1px solid black;">
商務用 Skype 基本版 2016 (64 位元)  
(3114372)  
(重大)

</td>
</tr>
</table>
 
**MS15-128 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

 

### Microsoft 開發者工具和軟體

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Silverlight**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-tw/library/security/ms15-128)

</td>
<td style="border:1px solid black;">
[**MS15-129**](https://technet.microsoft.com/zh-tw/library/security/ms15-129)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
安裝在 Mac 上的 Microsoft Silverlight 5  
(3106614)  
(重大)  
安裝在 Mac 上的 Microsoft Silverlight 5 Developer Runtime  
(3106614)  
(重大)  
安裝在所有受支援版本的 Microsoft Windows 用戶端上的 Microsoft Silverlight 5  
(3106614)  
(重大)  
安裝在所有受支援的 Microsoft Windows 用戶端版本上的 Microsoft Silverlight 5 Developer Runtime  
(3106614)  
(重大)  
安裝在所有受支援的 Microsoft Windows 伺服器版本上的 Microsoft Silverlight 5  
(3106614)  
(重大)  
安裝在所有受支援的 Microsoft Windows 伺服器版本上的 Microsoft Silverlight 5 Developer Runtime  
(3106614)  
(重大)

</td>
<td style="border:1px solid black;">
安裝在 Mac 上的 Microsoft Silverlight 5  
(3106614)  
(重大)  
安裝在 Mac 上的 Microsoft Silverlight 5 Developer Runtime  
(3106614)  
(重大)  
安裝在所有受支援版本的 Microsoft Windows 用戶端上的 Microsoft Silverlight 5  
(3106614)  
(重大)  
安裝在所有受支援的 Microsoft Windows 用戶端版本上的 Microsoft Silverlight 5 Developer Runtime  
(3106614)  
(重大)  
安裝在所有受支援的 Microsoft Windows 伺服器版本上的 Microsoft Silverlight 5  
(3106614)  
(重大)  
安裝在所有受支援的 Microsoft Windows 伺服器版本上的 Microsoft Silverlight 5 Developer Runtime  
(3106614)  
(重大)

</td>
</tr>
</table>
 
**MS15-128 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

偵測與部署工具及指南
--------------------

有幾項資源可協助系統管理員部署資訊安全更新。

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，查看是否遺漏安全性更新及一般資訊安全設定錯誤的狀況。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 可協助系統管理員發佈安全性更新。

應用程式相容性工具組隨附的 Update Compatibility Evaluator 元件可針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

如需上述工具以及其他可使用工具的詳細資訊，請參閱 [IT 專業人員的資訊安全工具](http://technet.microsoft.com/zh-tw/security/cc297183)。

致謝
----

Microsoft 了解資訊安全業界所做的努力，其盡責地透露弱點來協助我們保護客戶。請參閱[致謝](https://technet.microsoft.com/zh-tw/library/security/dn903755.aspx) (英文) 以取得詳細資訊。

其他資訊
--------

### Microsoft Windows 惡意軟體移除工具 (英文)

針對每個月第二個星期二發行的公告，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 及下載中心發行更新版本的 Microsoft Windows 惡意軟體移除工具。不定期資訊安全公告發行不提供更新版本的 Microsoft Windows 惡意軟體移除工具。

### MU、WU 及 WSUS 上的非資訊安全更新

如需在 Windows Update 和 Microsoft Update 上發行的非資訊安全更新之相關資訊，請參閱：

-   [Microsoft 知識庫文章 894199](https://support.microsoft.com/zh-tw/kb/894199)：Software Update Services 與 Windows Server Update Services 的說明內容有所變動。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](http://technet.microsoft.com/zh-tw/windowsserver/bb332157.aspx)。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的資訊安全保護，Microsoft 將在每月發行安全性更新之前，提前向重要資訊安全軟體提供者提供弱點資訊。資訊安全軟體提供者可利用此弱點，透過其資訊安全軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://technet.microsoft.com/zh-tw/security/dn467918) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

### 安全性策略與社群

**更新程式管理策略**

[更新管理資訊安全指南](http://technet.microsoft.com/zh-tw/library/bb466251.aspx) (英文) 提供您有關套用資訊安全更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他資訊安全更新**

其他資訊安全問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得，您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-tw) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](https://support.microsoft.com/zh-tw/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](http://technet.microsoft.com/zh-tw/security/cc136632.aspx)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

### 支援

所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](https://support.microsoft.com/zh-tw/lifecycle)。

適用於 IT 專業人員的安全性解決方案：[TechNet 安全性疑難排解與支援](http://technet.microsoft.com/zh-tw/security/bb980617)

協助保護您的 Windows 電腦免於病毒和惡意軟體攻擊：[病毒解決方案與資訊安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-tw)

您所在國家/地區的當地支援：[多語系支援](http://support.microsoft.com/common/international.aspx?ln=zh-tw)

### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

### 修訂

-   V1.0 (2015 年 12 月 8 日)：公告摘要發行。
-   V1.1 (2015 年 12 月 9 日)：修訂公告摘要以修正 CVE-2015-6124 的弱點入侵性評估。這只是資訊的變更。
-   V1.2 (2015 年 12 月 16 日)：修訂公告摘要，新增已知問題至 3104002 的「提要」表格。若要解決該問題，請安裝 Hotfix 3125446。如需詳細資訊，請參閱 [Microsoft 知識庫文章 3104002](https://support.microsoft.com/zh-tw/kb/3104002)。

*頁面產生時間：2015-12-16 17:23:00-08:00。*
