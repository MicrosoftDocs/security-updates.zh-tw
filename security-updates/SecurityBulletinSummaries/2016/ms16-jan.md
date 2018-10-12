---
TOCTitle: 'MS16-JAN'
Title: 2016 年 1 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms16-jan'
ms:contentKeyID: 72150148
ms:date: '01/11/2016'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms16-jan(v=Security.10)'
---

2016 年 1 月份 Microsoft 資訊安全公告摘要
=========================================

發行日期：2016 年 1 月 12 日

**版本：** 1.0

此公告摘要列出 2016 年 1 月份發行之資訊安全公告。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://technet.microsoft.com/zh-tw/security/dd252948.aspx)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性更新的優先順序，其中這些非安全性更新的發行日期與每月安全性更新的發行日期相同。請參閱**＜其他資訊＞**一節。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=717999">MS16-001</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 累積安全性更新 (3124903)</strong> <br />
此安全性更新可解決 Internet Explorer 中的弱點。其中更嚴重的弱點，可能在使用者以 Internet Explorer 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用此弱點的攻擊者可以取得與目前使用者相同的使用者權限。如果目前的使用者以系統管理使用者權限登入，則成功利用此弱點的攻擊者可以取得受影響系統的控制權。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=718002">MS16-002</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 的累積安全性更新 (3124904)<br />
</strong>此安全性更新可解決 Microsoft Edge 中的弱點。如果使用者使用 Microsoft Edge 檢視蓄意製作的網頁，這些弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者可以取得與本機使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=718004">MS16-003</a></td>
<td style="border:1px solid black;"><strong>用來解決遠端執行程式碼的 JScript 和 VBScript 累積安全性更新 (3125540)<br />
</strong>這個安全性更新可解決 Microsoft Windows 的 VBScript 指令碼引擎中一項弱點。如果使用者造訪蓄意製作的網站，此弱點可能會允許遠端執行程式碼。成功利用此弱點的攻擊者可以取得與目前使用者相同的使用者權限。如果目前的使用者以系統管理使用者權限登入，則成功利用此弱點的攻擊者可以取得受影響系統的控制權。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=717998">MS16-004</a></td>
<td style="border:1px solid black;"><strong>用來解決遠端執行程式碼的 Microsoft Office 安全性更新 (3124585)</strong><br />
此安全性更新可解決 Microsoft Office 中的弱點。如果使用者開啟蓄意製作的 Microsoft Office 檔案，最嚴重的弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者，能以目前使用者的權限層級執行任意程式碼。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Visual Basic</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=718001">MS16-005</a></td>
<td style="border:1px solid black;"><strong>用來解決遠端執行程式碼問題的 Windows 核心模式驅動程式安全性更新 (3124584)</strong><br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果使用者造訪惡意網站，較嚴重的弱點可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=717994">MS16-006</a></td>
<td style="border:1px solid black;"><strong>用來解決遠端執行程式碼的 Silverlight 安全性更新 (3126036)</strong> <br />
此安全性更新可解決 Microsoft Silverlight 中的弱點。如果使用者瀏覽包含蓄意製作之 Silverlight 應用程式的被駭網站，此弱點可能允許遠端執行程式碼。攻擊者並不能強迫使用者造訪受侵害的網站，而是引誘使用者自行前往。一般的做法是設法讓使用者按一下電子郵件或即時訊息中通往攻擊者網站的連結。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">不需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=718006">MS16-007</a></td>
<td style="border:1px solid black;"><strong>用來解決遠端執行程式碼的 Microsoft Windows 安全性更新 (3124901)</strong><br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者可以登入目標系統並執行蓄意製作的應用程式，則最嚴重的弱點可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/en-us/kb/3124266">3124266</a><br />
<a href="https://support.microsoft.com/en-us/kb/3124263">3124263</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=718007">MS16-008</a></td>
<td style="border:1px solid black;"><strong>用來解決權限提高的 Windows 核心安全性更新 (3124605)</strong> <br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者登入受影響的系統，並執行蓄意製作的應用程式，則這些弱點可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=717997">MS16-010</a></td>
<td style="border:1px solid black;"><strong>解決詐騙的 Microsoft Exchange Server 安全性更新 (3124557)</strong><br />
此安全性更新可解決 Microsoft Exchange Server 中的弱點。這些弱點中最嚴重者會在 Outlook Web Access (OWA) 無法正確處理 Web 要求並清理使用者輸入和電子郵件內容時允許詐騙情況發生。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
偽造</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Exchange Server</td>
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
[**MS16-001：Internet Explorer 累積安全性更新 (3124903)**](http://go.microsoft.com/fwlink/?linkid=717999)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0002](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0002)

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
[CVE-2016-0005](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0005)

</td>
<td style="border:1px solid black;">
Internet Explorer 權限提高弱點

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
[**MS16-002：Microsoft Edge 的累積安全性更新 (3124904)**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0003](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0003)

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
[CVE-2016-0024](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0024)

</td>
<td style="border:1px solid black;">
指令碼引擎記憶體損毀弱點

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
<td style="border:1px solid black;" colspan="5">
[**MS16-003：用來解決遠端執行程式碼的 JScript 和 VBScript 累積安全性更新 (3125540)**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0002](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0002)

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
[**MS16-004：用來解決遠端執行程式碼的 Microsoft Office 安全性更新 (3124585)**](http://go.microsoft.com/fwlink/?linkid=717998)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6117](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6117)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint 資訊安全功能略過弱點

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
<td style="border:1px solid black;">
[CVE-2016-0010](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0010)

</td>
<td style="border:1px solid black;">
Microsoft Office 記憶體損毀弱點

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
[CVE-2016-0011](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0011)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint 資訊安全功能略過弱點

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
[CVE-2016-0012](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0012)

</td>
<td style="border:1px solid black;">
Microsoft Office ASLR 略過

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
[CVE-2016-0035](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0035)

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
<td style="border:1px solid black;" colspan="5">
[**MS16-005：用來解決權限提高的 Windows 核心模式驅動程式安全性更新 (3124584)**](http://go.microsoft.com/fwlink/?linkid=718001)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0008](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0008)

</td>
<td style="border:1px solid black;">
Windows GDI32.dll ASLR 略過弱點

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
[CVE-2016-0009](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0009)

</td>
<td style="border:1px solid black;">
Win32k 遠端執行程式碼弱點

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
[**MS16-006：用來解決遠端執行程式碼的 Silverlight 安全性更新 (3126036)**](http://go.microsoft.com/fwlink/?linkid=717994)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0034](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0034)

</td>
<td style="border:1px solid black;">
Silverlight 執行階段遠端執行程式碼弱點

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
[**MS16-007：用來解決遠端執行程式碼的 Microsoft Windows 安全性更新 (3124901)**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0014](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0014)

</td>
<td style="border:1px solid black;">
DLL 載入權限提高弱點

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
[CVE-2016-0015](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0015)

</td>
<td style="border:1px solid black;">
DirectShow 堆積損毀遠端執行程式碼弱點

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
[CVE-2016-0016](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0016)

</td>
<td style="border:1px solid black;">
DLL 載入遠端執行程式碼弱點

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
[CVE-2016-0018](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0018)

</td>
<td style="border:1px solid black;">
DLL 載入遠端執行程式碼弱點

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
[CVE-2016-0019](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0019)

</td>
<td style="border:1px solid black;">
Windows 遠端桌面通訊協定資訊安全略過弱點

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
[CVE-2016-0020](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0020)

</td>
<td style="border:1px solid black;">
MAPI DLL 載入權限提高弱點

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
[**MS16-008：用來解決權限提高的 Windows 核心安全性更新 (3124605)**](http://go.microsoft.com/fwlink/?linkid=718007)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0006](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0006)

</td>
<td style="border:1px solid black;">
Windows 掛接點權限提高弱點

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
[CVE-2016-0007](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0007)

</td>
<td style="border:1px solid black;">
Windows 掛接點權限提高弱點

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
[**MS16-010：解決詐騙的 Microsoft Exchange Server 安全性更新 (3124557)**](http://go.microsoft.com/fwlink/?linkid=717997)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0029](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0029)

</td>
<td style="border:1px solid black;">
Exchange 偽造弱點

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
[CVE-2016-0030](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0030)

</td>
<td style="border:1px solid black;">
Exchange 偽造弱點

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
[CVE-2016-0031](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0031)

</td>
<td style="border:1px solid black;">
Exchange 偽造弱點

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
[CVE-2016-0032](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0032)

</td>
<td style="border:1px solid black;">
Exchange 偽造弱點

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
</table>
 

受影響的軟體
------------

下表依據主要的軟體類別和嚴重性依序列出公告。

請用這些表格來瞭解可能需要安裝的安全性更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的安全性更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。

**注意**：一項弱點，可能需要安裝數個安全性更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。

 

### Windows 作業系統及元件 (表格 2 之 1)

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-001**](http://go.microsoft.com/fwlink/?linkid=717999)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/zh-tw/library/security/ms15-135)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3124275)  
(重大)  
Internet Explorer 8  
(3124275)  
(重大)  
Internet Explorer 9  
(3124275)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3124624)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3124000)  
(重大)  
Windows Vista Service Pack 2  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3124275)  
(重大)  
Internet Explorer 8  
(3124275)  
(重大)  
Internet Explorer 9  
(3124275)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3124624)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3124000)  
(重大)  
Windows Vista x64 Edition Service Pack 2  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-001**](https://technet.microsoft.com/zh-tw/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/zh-tw/library/security/ms15-135)

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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3124275)  
(中度)  
Internet Explorer 8  
(3124275)  
(中度)  
Internet Explorer 9  
(3124275)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3124624)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3124000)  
(重大)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3124275)  
(中度)  
Internet Explorer 8  
(3124275)  
(中度)  
Internet Explorer 9  
(3124275)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3124624)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3124000)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3124275)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3124624)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3124000)  
(重大)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-001**](https://technet.microsoft.com/zh-tw/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/zh-tw/library/security/ms15-135)

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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3124275)  
(重大)  
Internet Explorer 9  
(3124275)  
(重大)  
Internet Explorer 10  
(3124275)  
(重大)  
Internet Explorer 11  
(3124275)  
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
(3124000)  
(重大)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3124275)  
(重大)  
Internet Explorer 9  
(3124275)  
(重大)  
Internet Explorer 10  
(3124275)  
(重大)  
Internet Explorer 11  
(3124275)  
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
(3124000)  
(重大)  
適用於 x64 系統的 Windows 7 Service Pack 1  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-001**](https://technet.microsoft.com/zh-tw/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/zh-tw/library/security/ms15-135)

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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3124275)  
(中度)  
Internet Explorer 9  
(3124275)  
(中度)  
Internet Explorer 10  
(3124275)  
(中度)  
Internet Explorer 11  
(3124275)  
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
(3124000)  
(重大)  
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3124275)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3124000)  
(重大)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-001**](https://technet.microsoft.com/zh-tw/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/zh-tw/library/security/ms15-135)

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
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3124275)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3124275)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124275)  
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
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124275)  
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
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-001**](https://technet.microsoft.com/zh-tw/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/zh-tw/library/security/ms15-135)

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
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3124275)  
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
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124275)  
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
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-001**](https://technet.microsoft.com/zh-tw/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/zh-tw/library/security/ms15-135)

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
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3124275)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124275)  
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
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-001**](https://technet.microsoft.com/zh-tw/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/zh-tw/library/security/ms15-135)

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
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124266)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3124266)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3124266)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124266)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3124266)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3124266)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124263)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3124263)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3124263)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124263)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3124263)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3124263)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Server Core 安裝選項**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-001**](https://technet.microsoft.com/zh-tw/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/zh-tw/library/security/ms15-135)

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
(3124624)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3124000)  
(重大)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3124001)  
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
VBScript 5.7  
(3124624)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3124000)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3124001)  
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
VBScript 5.8  
(3124625)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)  
(3124000)  
(重大)  
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)  
(3124001)  
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
Windows Server 2012  
(Server Core 安裝)  
(3124001)  
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
Windows Server 2012 R2  
(Server Core 安裝)  
(3124001)  
(重要)

</td>
</tr>
</table>
 
 

### Windows 作業系統及元件 (表格 2 之 2)

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3121918)  
(重要)  
Windows Vista Service Pack 2  
(3109560)  
(重要)  
Windows Vista Service Pack 2  
(3110329)  
(重要)  
Windows Vista Service Pack 2  
(3108664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3121918)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3109560)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3110329)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3108664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3121918)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3109560)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3110329)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3108664)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3121918)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3109560)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3110329)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3108664)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3121918)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3109560)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3110329)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3108664)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3121918)  
(重要)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3109560)  
(重要)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3110329)  
(重要)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3121461)  
(重要)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3108664)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows 7 Service Pack 1  
(3121918)  
(重要)  
適用於 x64 系統的 Windows 7 Service Pack 1  
(3109560)  
(重要)  
適用於 x64 系統的 Windows 7 Service Pack 1  
(3110329)  
(重要)  
適用於 x64 系統的 Windows 7 Service Pack 1  
(3121461)  
(重要)  
適用於 x64 系統的 Windows 7 Service Pack 1  
(3108664)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows 7 Service Pack 1  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(3121918)  
(重要)  
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(3109560)  
(重要)  
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(3110329)  
(重要)  
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(3108664)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3121918)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3109560)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3110329)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3108664)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8  
(3121918)  
(重要)  
適用於 32 位元系統的 Windows 8  
(3109560)  
(重要)  
適用於 32 位元系統的 Windows 8  
(3110329)  
(重要)  
適用於 32 位元系統的 Windows 8  
(3121461)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(3121918)  
(重要)  
適用於 x64 型系統的 Windows 8  
(3109560)  
(重要)  
適用於 x64 型系統的 Windows 8  
(3110329)  
(重要)  
適用於 x64 型系統的 Windows 8  
(3121461)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3121918)  
(重要)  
適用於 32 位元系統的 Windows 8.1  
(3109560)  
(重要)  
適用於 32 位元系統的 Windows 8.1  
(3110329)  
(重要)  
適用於 32 位元系統的 Windows 8.1  
(3121461)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3121918)  
(重要)  
適用於 x64 型系統的 Windows 8.1  
(3109560)  
(重要)  
適用於 x64 型系統的 Windows 8.1  
(3110329)  
(重要)  
適用於 x64 型系統的 Windows 8.1  
(3121461)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3121918)  
(重要)  
Windows Server 2012  
(3109560)  
(重要)  
Windows Server 2012  
(3110329)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3121918)  
(重要)  
Windows Server 2012 R2  
(3109560)  
(重要)  
Windows Server 2012 R2  
(3110329)  
(重要)  
Windows Server 2012 R2  
(3121461)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Windows RT  
(3121918)  
(重要)  
Windows RT  
(3110329)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3121918)  
(重要)  
Windows RT 8.1  
(3110329)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3124266)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3124266)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3124266)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3124266)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3124263)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3124263)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3124263)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3124263)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Server Core 安裝選項**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3121918)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3121212)  
(重要)

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
(3121918)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3121212)  
(重要)

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
(3121918)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)  
(3121918)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)  
(3121918)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)  
(3121212)  
(重要)

</td>
</tr>
</table>
 
 

### Microsoft Office 套件及軟體

 
<p></p>
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
[**MS16-004**](https://technet.microsoft.com/zh-tw/library/security/ms15-131)

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
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2881067)  
(重要)  
Microsoft Office 2007 Service Pack 3  
(3114541)  
(重大)  
Microsoft Excel 2007 Service Pack 3  
(3114540)  
(重要)  
Microsoft PowerPoint 2007 Service Pack 3  
(3114429)  
(重要)  
Microsoft Visio 2007 Service Pack 3  
(3114421)  
(重要)  
Microsoft Word 2007 Service Pack 3  
(3114549)  
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
[**MS16-004**](https://technet.microsoft.com/zh-tw/library/security/ms15-131)

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
Microsoft Office 2010 Service Pack 2 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(2881029)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(3114553)  
(重大)  
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(3114554)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (32 位元版本)  
(3114564)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (32 位元版本)  
(3114396)  
(重要)  
Microsoft Visio 2010 Service Pack 2 (32 位元版本)  
(3114402)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 位元版本)  
(3114557)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3114553)  
(重大)  
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3114554)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3114564)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (64 位元版本)  
(3114564)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (64 位元版本)  
(3114396)  
(重要)  
Microsoft Visio 2010 Service Pack 2 (64 位元版本)  
(3114402)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 位元版本)  
(3114557)  
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
[**MS16-004**](https://technet.microsoft.com/zh-tw/library/security/ms15-131)

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
Microsoft Office 2013 Service Pack 1 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 位元版本)  
(3039794)  
(重要)  
Microsoft Office 2013 Service Pack 1 (32 位元版本)  
(3114486)  
(重大)  
Microsoft Excel 2013 Service Pack 1 (32 位元版本)  
(3114504)  
(重要)  
Microsoft PowerPoint 2013 Service Pack 1 (32 位元版本)  
(3114482)  
(重要)  
Microsoft Visio 2013 Service Pack 1 (32 位元版本)  
(3114489)  
(重要)  
Microsoft Word 2013 Service Pack 1 (32 位元版本)  
(3114494)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 位元版本)  
(3114486)  
(重大)  
Microsoft Excel 2013 Service Pack 1 (64 位元版本)  
(3114504)  
(重要)  
Microsoft PowerPoint 2013 Service Pack 1 (64 位元版本)  
(3114482)  
(重要)  
Microsoft Visio 2013 Service Pack 1 (64 位元版本)  
(3114489)  
(重要)  
Microsoft Word 2013 Service Pack 1 (64 位元版本)  
(3114494)  
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
[**MS16-004**](https://technet.microsoft.com/zh-tw/library/security/ms15-131)

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
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1  
(3114486)  
(重大)  
Microsoft Excel 2013 RT Service Pack 1  
(3114504)  
(重要)  
Microsoft PowerPoint 2013 RT Service Pack 1  
(3114482)  
(重要)  
Microsoft Word 2013 RT Service Pack 1  
(3114494)  
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
[**MS16-004**](https://technet.microsoft.com/zh-tw/library/security/ms15-131)

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
Microsoft Office 2016 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2016 (32 位元版本)  
(2920727)  
(重要)  
Microsoft Office 2016 (32 位元版本)  
(3114527)  
(重大)  
Microsoft Excel 2016 (32 位元版本)  
(3114520)  
(重要)  
Microsoft PowerPoint 2016 (32 位元版本)  
(3114518)  
(重要)  
Microsoft Visio 2016 (32 位元版本)  
(3114511)  
(重要)  
Microsoft Word 2016 (32 位元版本)  
(3114526)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 位元版本)  
(3114527)  
(重大)  
Microsoft Office 2016 (64 位元版本)  
(3114520)  
(重要)  
Microsoft Excel 2016 (64 位元版本)  
(3114520)  
(重要)  
Microsoft PowerPoint 2016 (64 位元版本)  
(3114518)  
(重要)  
Microsoft Visio 2016 (64 位元版本)  
(3114511)  
(重要)  
Microsoft Word 2016 (64 位元版本)  
(3114526)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-004**](https://technet.microsoft.com/zh-tw/library/security/ms15-131)

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
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Excel for Mac 2011  
(3133699)  
(重大)  
Microsoft PowerPoint for Mac 2011  
(3133699)  
(重大)  
Microsoft Word for Mac 2011  
(3133699)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 for Mac  
(3133711)  
(重大)  
Microsoft PowerPoint 2016 for Mac  
(3133711)  
(重大)  
Microsoft Word 2016 for Mac  
(3133711)  
(重大)

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
[**MS16-004**](https://technet.microsoft.com/zh-tw/library/security/ms15-131)

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
Microsoft Office 相容性套件 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 相容性套件 Service Pack 3  
(3114546)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3114547)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3114569)  
(重大)

</td>
</tr>
</table>
 
**MS16-004 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

 

### Microsoft 開發者工具和軟體

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Silverlight**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-006**](http://go.microsoft.com/fwlink/?linkid=717994)

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
Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
安裝在 Mac 上的 Microsoft Silverlight 5  
(3126036)  
(重大)  
安裝在 Mac 上的 Microsoft Silverlight 5 Developer 執行階段  
(3126036)  
(重大)  
安裝在所有受支援版本的 Microsoft Windows 用戶端上的 Microsoft Silverlight 5  
(3126036)  
(重大)  
安裝在所有受支援的 Microsoft Windows 用戶端版本上的 Microsoft Silverlight 5 Developer 執行階段  
(3126036)  
(重大)  
安裝在所有受支援的 Microsoft Windows 伺服器版本上的 Microsoft Silverlight 5  
(3126036)  
(重大)  
安裝在所有受支援的 Microsoft Windows 伺服器版本上的 Microsoft Silverlight 5 Developer 執行階段  
(3126036)  
(重大)

</td>
</tr>
</table>
 
 

### Microsoft 伺服器軟體

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Foundation 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-004**](https://technet.microsoft.com/zh-tw/library/security/ms15-131)

</td>
<td style="border:1px solid black;">
[**MS16-010**](http://go.microsoft.com/fwlink/?linkid=717997)

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
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1  
(3114503)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-004**](https://technet.microsoft.com/zh-tw/library/security/ms15-131)

</td>
<td style="border:1px solid black;">
[**MS16-010**](http://go.microsoft.com/fwlink/?linkid=717997)

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
Microsoft Exchange Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1  
(3124557)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 積存更新 10  
(3124557)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 積存更新 11  
(3124557)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-004**](https://technet.microsoft.com/zh-tw/library/security/ms15-131)

</td>
<td style="border:1px solid black;">
[**MS16-010**](http://go.microsoft.com/fwlink/?linkid=717997)

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
Microsoft Exchange Server 2016

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016  
(3124557)  
(重要)

</td>
</tr>
</table>
 
**MS16-004 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

### Microsoft Visual Basic 軟體

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Visual Basic 6.0 Runtime**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-004**](https://technet.microsoft.com/zh-tw/library/security/ms15-131)

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
Visual Basic 6.0 Runtime

</td>
<td style="border:1px solid black;">
Visual Basic 6.0 Runtime  
(3096896)  
(重要)

</td>
</tr>
</table>
 
**MS16-004 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

偵測與部署工具及指南
--------------------

有幾項資源可協助系統管理員部署安全性更新。

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

協助保護您的 Windows 電腦免於病毒和惡意軟體攻擊：[病毒解決方案與資訊安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-tw)

您所在國家/地區的當地支援：[多語系支援](http://support.microsoft.com/common/international.aspx?ln=zh-tw)

### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

### 修訂

-   V1.0 (2016 年 1 月 12 日)：公告摘要發行。

*頁面產生時間：2016-01-07 13:56:00-08:00。*
