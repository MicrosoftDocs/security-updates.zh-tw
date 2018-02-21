---
TOCTitle: 'MS16-MAY'
Title: 2016 年 5 月 Microsoft 資訊安全公告摘要
ms:assetid: 'ms16-may'
ms:contentKeyID: 72963911
ms:date: '06/08/2016'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms16-may(v=Security.10)'
---

2016 年 5 月 Microsoft 資訊安全公告摘要
=======================================

發行日期：2016 年 5 月 10 日 | 更新日期：2016 年 5 月 25 日

**版本：** 2.1

此公告摘要列出 2016 年 5 月發行之資訊安全公告。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://technet.microsoft.com/zh-tw/security/dd252948.aspx)。

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-051">MS16-051</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 累積安全性更新 (3155533)<br />
</strong>此安全性更新可解決 Internet Explorer 中的弱點。其中最嚴重的弱點，可能在使用者以 Internet Explorer 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用這些弱點的攻擊者可以取得與本機使用者相同的使用者權限。如果目前使用者以系統管理的使用者權限登入，則攻擊者即可取得受影響系統的控制權。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-052">MS16-052</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 的累積安全性更新 (3155538)<br />
</strong>此安全性更新可解決 Microsoft Edge 中的弱點。其中最嚴重的弱點，可能在使用者以 Microsoft Edge 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用這些弱點的攻擊者可以取得與本機使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-053">MS16-053</a></td>
<td style="border:1px solid black;"><strong>JScript 和 VBScript 的累積安全性更新 (3156764)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中 JScript 與 VBScript 指令碼引擎的弱點。如果使用者造訪蓄意製作的網站，這些弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者可以取得與目前使用者相同的使用者權限。如果目前的使用者以系統管理使用者權限登入，則成功利用這些弱點的攻擊者可以取得受影響系統的控制權。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-054">MS16-054</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 的安全性更新 (3155544)<br />
</strong>此安全性更新可解決 Microsoft Office 中的弱點。如果使用者開啟蓄意製作的 Microsoft Office 檔案，此弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者，能以目前使用者的權限層級執行任意程式碼。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft Office Services 和 Web Apps</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-055">MS16-055</a></td>
<td style="border:1px solid black;"><strong>Microsoft 圖形元件的安全性更新 (3156754)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果使用者開啟蓄意製作的文件，或是造訪蓄意製作的網站，最嚴重的弱點可能會允許遠端執行程式碼。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-056">MS16-056</a></td>
<td style="border:1px solid black;"><strong>Windows 筆記本的安全性更新 (3156761)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果使用者開啟蓄意製作的筆記本檔案，此弱點可能會允許遠端執行程式碼。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-057">MS16-057</a></td>
<td style="border:1px solid black;"><strong>Windows Shell 的安全性更新 (3156987)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者成功說服使用者瀏覽至蓄意製作且可接受使用者提供之內容的網站，或開啟蓄意製作的內容，此弱點可允許遠端程式碼執行。成功利用此弱點的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-058">MS16-058</a></td>
<td style="border:1px solid black;"><strong>Windows IIS 的安全性更新 (3141083)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果具有本機系統存取權的攻擊者執行惡意應用程式，此弱點可能會允許遠端執行程式碼。成功利用此弱點的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-059">MS16-059</a></td>
<td style="border:1px solid black;"><strong>Windows Media Center 的安全性更新 (3150220)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果 Windows Media Center 開啟參考惡意程式碼的蓄意製作 Media Center 連結 (.mcl) 檔案，則此弱點可能會允許遠端執行程式碼。成功利用此弱點的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-060">MS16-060</a></td>
<td style="border:1px solid black;"><strong>Windows 核心的安全性更新 (3154846)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者登入受影響的系統，並執行蓄意製作的應用程式，則此弱點可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-061">MS16-061</a></td>
<td style="border:1px solid black;"><strong>Microsoft RPC 的安全性更新 (3155520)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果通過驗證的攻擊者對受影響主機提出錯誤格式的遠端程序呼叫 (RPC) 要求，則弱點可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-062">MS16-062</a></td>
<td style="border:1px solid black;"><strong>Windows 核心模式驅動程式的安全性更新 (3158222)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者登入受影響的系統並執行蓄意製作的應用程式，則較嚴重的弱點可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-064">MS16-064</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player 的安全性更新 (3157993)</strong><br />
此安全性更新可解決安裝於 Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1 和 Windows 10 上之 Adobe Flash Player 中的弱點。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Adobe Flash Player</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-065">MS16-065</a></td>
<td style="border:1px solid black;"><strong>.NET Framework 的安全性更新 (3156757)<br />
</strong>這個安全性更新可解決 Microsoft .NET Framework 中一項弱點。如果攻擊者將未加密的資料插入目標安全通道，並在目標用戶端與合法伺服器之間發動攔截式 (MiTM) 攻擊，該弱點可造成資訊洩漏。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
資訊洩漏</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3156757">3156757</a></td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-066">MS16-066</a></td>
<td style="border:1px solid black;"><strong>虛擬安全模式的安全性更新 (3155451)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者執行蓄意製作的應用程式，來略過 Windows 的程式碼完整性保護，則弱點可能會允許略過資訊安全功能。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
資訊安全功能略過</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-067">MS16-067</a></td>
<td style="border:1px solid black;"><strong>磁碟區管理員驅動程式的安全性更新 (3155784)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果透過 Microsoft RemoteFX 掛接到遠端桌面通訊協定 (RDP) 的 USB 磁碟，未正確與掛接使用者的工作階段相關聯，該弱點可造成資訊洩漏。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
資訊洩漏</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
弱點入侵指數  
------------
  
下表提供本月所述每個弱點的利用性評估。會依序按公告編號及 CVE ID 的順序列出弱點。只會包含公告中嚴重性等級為「重大」或「重要」的弱點。
  
**我該如何使用這個表格？**
  
您可以運用此表格，針對您可能需要安裝的每一項安全性更新，瞭解弱點在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務 (DoS) 的可能性。請根據您特定的組態設定，檢閱下列各項評估，決定部署本月份更新的優先次序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點入侵指數](http://technet.microsoft.com/zh-tw/security/cc998259)。
  
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
[**MS16-051：Internet Explorer 的累積安全性更新 (3155533)**](https://technet.microsoft.com/zh-tw/library/security/ms16-051)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0187](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0187)

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
[CVE-2016-0188](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0188)

</td>
<td style="border:1px solid black;">
Internet Explorer 資訊安全功能略過

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
[CVE-2016-0189](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0189)

</td>
<td style="border:1px solid black;">
指令碼引擎記憶體損毀弱點

</td>
<td style="border:1px solid black;">
0 - 已偵測到利用

</td>
<td style="border:1px solid black;">
0 - 已偵測到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0192](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0192)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

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
[CVE-2016-0194](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0194)

</td>
<td style="border:1px solid black;">
Internet Explorer 資訊洩漏弱點

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
[**MS16-052：Microsoft Edge 的累積安全性更新 (3155538)**](https://technet.microsoft.com/zh-tw/library/security/ms16-052)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0186](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0186)

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
<td style="border:1px solid black;">
[CVE-2016-0191](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0191)

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
<td style="border:1px solid black;">
[CVE-2016-0192](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0192)

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
[CVE-2016-0193](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0193)

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
[**MS16-053：JScript 和 VBScript 的累積安全性更新 (3156764)**](https://technet.microsoft.com/zh-tw/library/security/ms16-053)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0187](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0187)

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
[CVE-2016-0189](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0189)

</td>
<td style="border:1px solid black;">
指令碼引擎記憶體損毀弱點

</td>
<td style="border:1px solid black;">
0 - 已偵測到利用

</td>
<td style="border:1px solid black;">
0 - 已偵測到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-054：Microsoft Office 的安全性更新 (3155544)**](https://technet.microsoft.com/zh-tw/library/security/ms16-054)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0126](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0126)

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
[CVE-2016-0140](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0140)

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
[CVE-2016-0183](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0183)

</td>
<td style="border:1px solid black;">
Microsoft Office 圖形 RCE 弱點

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
[CVE-2016-0198](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0198)

</td>
<td style="border:1px solid black;">
Microsoft Office 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
1 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
1 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-055：Microsoft 圖形元件的安全性更新 (3156754)**](https://technet.microsoft.com/zh-tw/library/security/ms16-055)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0168](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0168)

</td>
<td style="border:1px solid black;">
Windows 圖形元件資訊洩漏弱點

</td>
<td style="border:1px solid black;">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
暫時

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0169](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0169)

</td>
<td style="border:1px solid black;">
Windows 圖形元件資訊洩漏弱點

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
暫時

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0170](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0170)

</td>
<td style="border:1px solid black;">
Windows 圖形元件 RCE 弱點

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
[CVE-2016-0184](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0184)

</td>
<td style="border:1px solid black;">
Direct3D 釋放後使用弱點

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
[CVE-2016-0195](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0195)

</td>
<td style="border:1px solid black;">
Windows 影像處理元件記憶體損毀弱點

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
[**MS16-056：Windows 筆記本的安全性更新 (3156761)**](https://technet.microsoft.com/zh-tw/library/security/ms16-056)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0182](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0182)

</td>
<td style="border:1px solid black;">
筆記本記憶體損毀弱點

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
<td style="border:1px solid black;" colspan="5">
[**MS16-057：Windows Shell 的安全性更新 (3156987)**](https://technet.microsoft.com/zh-tw/library/security/ms16-057)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0179](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0179)

</td>
<td style="border:1px solid black;">
Windows Shell 遠端執行程式碼弱點

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
[**MS16-058：Windows IIS 的安全性更新 (3141083)**](https://technet.microsoft.com/zh-tw/library/security/ms16-058)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0152](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0152)

</td>
<td style="border:1px solid black;">
Windows DLL 載入遠端執行程式碼弱點

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
[**MS16-059：Windows Media Center 的安全性更新 (3150220)**](https://technet.microsoft.com/zh-tw/library/security/ms16-059)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0185](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0185)

</td>
<td style="border:1px solid black;">
Windows Media Center 遠端執行程式碼弱點

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
[**MS16-060：Windows 核心的安全性更新 (3154846)**](https://technet.microsoft.com/zh-tw/library/security/ms16-060)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0180](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0180)

</td>
<td style="border:1px solid black;">
Windows 核心權限提高弱點

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
[**MS16-061：Microsoft RPC 的安全性更新 (3155520)**](https://technet.microsoft.com/zh-tw/library/security/ms16-061)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0178](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0178)

</td>
<td style="border:1px solid black;">
RPC 網路資料表現引擎遠端執行程式碼弱點

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
[**MS16-062：Windows 核心模式驅動程式的安全性更新 (3158222)**](https://technet.microsoft.com/zh-tw/library/security/ms16-062)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0171](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0171)

</td>
<td style="border:1px solid black;">
Win32k 權限提高弱點

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
[CVE-2016-0173](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0173)

</td>
<td style="border:1px solid black;">
Win32k 權限提高弱點

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
[CVE-2016-0174](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0174)

</td>
<td style="border:1px solid black;">
Win32k 權限提高弱點

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
[CVE-2016-0175](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0175)

</td>
<td style="border:1px solid black;">
Win32k 資訊洩漏弱點

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
[CVE-2016-0176](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0176)

</td>
<td style="border:1px solid black;">
Microsoft DirectX 圖形核心子系統權限提高弱點

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
[CVE-2016-0196](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0196)

</td>
<td style="border:1px solid black;">
Win32k 權限提高弱點

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
[CVE-2016-0197](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0197)

</td>
<td style="border:1px solid black;">
Microsoft DirectX 圖形核心子系統權限提高弱點

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
<td style="border:1px solid black;" colspan="5">
[**MS16-064：Adobe Flash Player 的安全性更新 (3157993)**](https://technet.microsoft.com/zh-tw/library/security/ms16-064)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-15](https://helpx.adobe.com/tw/security/products/flash-player/apsb16-15.html)

</td>
<td style="border:1px solid black;">
請參閱 [Adobe 資訊安全公告 APSB16-15](https://helpx.adobe.com/tw/security/products/flash-player/apsb16-15.html) 以了解弱點嚴重性和更新的優先順序級別。

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
<td style="border:1px solid black;" colspan="5">
[**MS16-065：.NET Framework 的安全性更新 (3156757)**](https://technet.microsoft.com/zh-tw/library/security/ms16-065)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0149](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0149)

</td>
<td style="border:1px solid black;">
TLS/SSL 資訊洩漏弱點

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
<td style="border:1px solid black;" colspan="5">
[**MS16-066：虛擬安全模式的安全性更新 (3155451)**](https://technet.microsoft.com/zh-tw/library/security/ms16-066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0181](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0181)

</td>
<td style="border:1px solid black;">
Hypervisor 程式碼完整性資訊安全功能略過

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
<td style="border:1px solid black;" colspan="5">
[**MS16-067：磁碟區管理員驅動程式的安全性更新 (3155784)**](https://technet.microsoft.com/zh-tw/library/security/ms16-067)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0190](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0190)

</td>
<td style="border:1px solid black;">
遠端桌面通訊協定的磁碟機重新導向資訊洩漏弱點

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
</table>
 

受影響的軟體
------------

下表依據主要的軟體類別和嚴重性依序列出公告。

請用這些表格來瞭解可能需要安裝的安全性更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的安全性更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。

**注意** 一項弱點，可能需要安裝數個安全性更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。

 

### Windows 作業系統及元件 (表格 2 之 1)

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/zh-tw/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/zh-tw/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/zh-tw/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/zh-tw/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/zh-tw/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/zh-tw/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/zh-tw/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/zh-tw/library/security/ms16-059)

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
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3154070)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3156013)  
(重大)  
Windows Vista Service Pack 2  
(3156016)  
(重大)  
Windows Vista Service Pack 2  
(3156019)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3155178)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3141083)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3150220)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3154070)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3156013)  
(重大)  
Windows Vista x64 Edition Service Pack 2  
(3156016)  
(重大)  
Windows Vista x64 Edition Service Pack 2  
(3156019)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3155178)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3141083)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3150220)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/zh-tw/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/zh-tw/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/zh-tw/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/zh-tw/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/zh-tw/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/zh-tw/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/zh-tw/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/zh-tw/library/security/ms16-059)

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
[**中度**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3154070)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3156013)  
(重大)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3156016)  
(重大)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3156019)  
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
(3141083)  
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
Internet Explorer 9  
(3154070)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3156013)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3156016)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3156019)  
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
(3141083)  
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
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3156013)  
(重大)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3156019)  
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
(3141083)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/zh-tw/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/zh-tw/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/zh-tw/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/zh-tw/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/zh-tw/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/zh-tw/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/zh-tw/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/zh-tw/library/security/ms16-059)

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
(3154070)  
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
(3156013)  
(重大)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3156016)  
(重大)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3156019)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3155178)  
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
(3150220)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3156013)  
(重大)  
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3156016)  
(重大)  
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3156019)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3155178)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3150220)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/zh-tw/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/zh-tw/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/zh-tw/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/zh-tw/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/zh-tw/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/zh-tw/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/zh-tw/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/zh-tw/library/security/ms16-059)

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
**無**

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
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3156013)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3156016)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3156019)  
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
(3156013)  
(重大)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3156016)  
(重大)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3156019)  
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
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/zh-tw/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/zh-tw/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/zh-tw/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/zh-tw/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/zh-tw/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/zh-tw/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/zh-tw/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/zh-tw/library/security/ms16-059)

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
**無**

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
(3154070)  
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
(3156013)  
(重大)  
適用於 32 位元系統的 Windows 8.1  
(3156016)  
(重大)  
適用於 32 位元系統的 Windows 8.1  
(3156019)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3155178)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3156059)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3150220)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
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
(3156013)  
(重大)  
適用於 x64 型系統的 Windows 8.1  
(3156016)  
(重大)  
適用於 x64 型系統的 Windows 8.1  
(3156019)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3155178)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3156059)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3150220)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/zh-tw/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/zh-tw/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/zh-tw/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/zh-tw/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/zh-tw/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/zh-tw/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/zh-tw/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/zh-tw/library/security/ms16-059)

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
**無**

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3154070)  
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
(3156013)  
(重大)  
Windows Server 2012  
(3156016)  
(重大)  
Windows Server 2012  
(3156019)  
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
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
(3156013)  
(重大)  
Windows Server 2012 R2  
(3156016)  
(重大)  
Windows Server 2012 R2  
(3156019)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3156059)  
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
<td style="border:1px solid black;" colspan="9">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/zh-tw/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/zh-tw/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/zh-tw/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/zh-tw/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/zh-tw/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/zh-tw/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/zh-tw/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/zh-tw/library/security/ms16-059)

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
**無**

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
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
(3156013)  
(重大)  
Windows RT 8.1  
(3156016)  
(重大)  
Windows RT 8.1  
(3156019)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3155178)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3156059)  
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
<td style="border:1px solid black;" colspan="9">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/zh-tw/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/zh-tw/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/zh-tw/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/zh-tw/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/zh-tw/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/zh-tw/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/zh-tw/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/zh-tw/library/security/ms16-059)

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
**無**

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3156387)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3156387)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3156387)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3156387)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3156387)  
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
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3156387)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3156387)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3156387)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3156387)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3156387)  
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
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3156421)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3156421)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3156421)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3156421)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3156421)  
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
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3156421)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3156421)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3156421)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3156421)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3156421)  
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
<td style="border:1px solid black;" colspan="9">
**Server Core 安裝選項**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/zh-tw/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/zh-tw/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/zh-tw/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/zh-tw/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/zh-tw/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/zh-tw/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/zh-tw/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/zh-tw/library/security/ms16-059)

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
[**中度**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3156013)  
(重大)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3156016)  
(重大)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3156019)  
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
(3141083)  
(重要)

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
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3156013)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3156016)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3156019)  
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
(3141083)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
JScript 5.8 和 VBScript 5.8  
(3155413)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3156013)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3156016)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3156019)  
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
(3156013)  
(重大)  
Windows Server 2012 (Server Core 安裝)  
(3156016)  
(重大)  
Windows Server 2012 (Server Core 安裝)  
(3156019)  
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
(3156013)  
(重大)  
Windows Server 2012 R2 (Server Core 安裝)  
(3156016)  
(重大)  
Windows Server 2012 R2 (Server Core 安裝)  
(3156019)  
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
</tr>
</table>
 
 

### Windows 作業系統及元件 (表格 2 之 2)

 
<p></p>
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
[**MS16-060**](https://technet.microsoft.com/zh-tw/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/zh-tw/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/zh-tw/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/zh-tw/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/zh-tw/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/zh-tw/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/zh-tw/library/security/ms16-067)

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
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3153199)  
(重要)  
Windows Vista Service Pack 2  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3142023)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(重要)  
Microsoft .NET Framework 4.6  
(3142037)  
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
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3153199)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3142023)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(重要)  
Microsoft .NET Framework 4.6  
(3142037)  
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
<td style="border:1px solid black;" colspan="8">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/zh-tw/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/zh-tw/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/zh-tw/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/zh-tw/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/zh-tw/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/zh-tw/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/zh-tw/library/security/ms16-067)

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
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3153199)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3142023)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(重要)  
Microsoft .NET Framework 4.6  
(3142037)  
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

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3153199)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3142023)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(重要)  
Microsoft .NET Framework 4.6  
(3142037)  
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
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3153199)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3142023)  
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
<td style="border:1px solid black;" colspan="8">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/zh-tw/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/zh-tw/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/zh-tw/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/zh-tw/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/zh-tw/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/zh-tw/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/zh-tw/library/security/ms16-067)

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
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
適用於 32 位元系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3153199)  
(重要)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3142024)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3142037)  
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
適用於 x64 型系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3153199)  
(重要)  
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3142024)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3142037)  
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
<td style="border:1px solid black;" colspan="8">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/zh-tw/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/zh-tw/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/zh-tw/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/zh-tw/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/zh-tw/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/zh-tw/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/zh-tw/library/security/ms16-067)

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
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3153199)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3142024)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3142037)  
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
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3153199)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3142024)  
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
<td style="border:1px solid black;" colspan="8">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/zh-tw/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/zh-tw/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/zh-tw/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/zh-tw/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/zh-tw/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/zh-tw/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/zh-tw/library/security/ms16-067)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
適用於 32 位元系統的 Windows 8.1  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3153704)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3153199)  
(重要)  
適用於 32 位元系統的 Windows 8.1  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142026)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142030)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3142036)  
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
適用於 x64 型系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3153704)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3153199)  
(重要)  
適用於 x64 型系統的 Windows 8.1  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142026)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142030)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3142036)  
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
<td style="border:1px solid black;" colspan="8">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/zh-tw/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/zh-tw/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/zh-tw/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/zh-tw/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/zh-tw/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/zh-tw/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/zh-tw/library/security/ms16-067)

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
[**中度**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
Windows Server 2012  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3153704)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3153199)  
(重要)  
Windows Server 2012  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(中度)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142025)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142032)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3142035)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3155784)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3153704)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3153199)  
(重要)  
Windows Server 2012 R2  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(中度)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142026)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142030)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3142036)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3155784)  
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
[**MS16-060**](https://technet.microsoft.com/zh-tw/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/zh-tw/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/zh-tw/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/zh-tw/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/zh-tw/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/zh-tw/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/zh-tw/library/security/ms16-067)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3153704)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3153199)  
(重要)  
Windows RT 8.1  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3142030)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3142036)  
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
<td style="border:1px solid black;" colspan="8">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/zh-tw/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/zh-tw/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/zh-tw/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/zh-tw/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/zh-tw/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/zh-tw/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/zh-tw/library/security/ms16-067)

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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3156387)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3156387)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3156387)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3156387)  
(重要)  
Microsoft .NET Framework 4.6  
(3156387)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3156387)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3156387)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3156387)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3156387)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3156387)  
(重要)  
Microsoft .NET Framework 4.6  
(3156387)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3156387)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3156421)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3156421)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3156421)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3156421)  
(重要)  
Microsoft .NET Framework 4.6.1  
(3156421)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3156421)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3156421)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3156421)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3156421)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3156421)  
(重要)  
Microsoft .NET Framework 4.6.1  
(3156421)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3156421)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

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
[**MS16-060**](https://technet.microsoft.com/zh-tw/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/zh-tw/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/zh-tw/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/zh-tw/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/zh-tw/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/zh-tw/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/zh-tw/library/security/ms16-067)

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
**無**

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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3153199)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3156017)  
(重要)

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
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3153199)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3156017)  
(重要)

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
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)  
(3153199)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3142024)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3142037)  
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
Windows Server 2012  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)  
(3153704)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)  
(3153199)  
(重要)  
Windows Server 2012  
(Server Core 安裝)  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142025)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142032)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3142035)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)  
(3155784)  
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
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)  
(3153704)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)  
(3153199)  
(重要)  
Windows Server 2012 R2  
(Server Core 安裝)  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142026)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142030)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3142036)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)  
(3155784)  
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
[**MS16-054**](https://technet.microsoft.com/zh-tw/library/security/ms16-054)

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
(2984938)  
(重要)  
Microsoft Office 2007 Service Pack 3  
(2984943)  
(重要)  
Microsoft Word 2007 Service Pack 3  
(3115116)  
(重大)

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
[**MS16-054**](https://technet.microsoft.com/zh-tw/library/security/ms16-054)

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
(3115121)  
(重大)  
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(3054984)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(3101520)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 位元版本)  
(3115123)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3115121)  
(重大)  
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3054984)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3101520)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 位元版本)  
(3115123)  
(重大)

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
[**MS16-054**](https://technet.microsoft.com/zh-tw/library/security/ms16-054)

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
(3115016)  
(重要)  
Microsoft Word 2013 Service Pack 1 (32 位元版本)  
(3115025)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 位元版本)  
(3115016)  
(重要)  
Microsoft Word 2013 Service Pack 1 (64 位元版本)  
(3115025)  
(重大)

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
[**MS16-054**](https://technet.microsoft.com/zh-tw/library/security/ms16-054)

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
(3115016)  
(重要)  
Microsoft Word 2013 RT Service Pack 1  
(3115025)  
(重大)

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
[**MS16-054**](https://technet.microsoft.com/zh-tw/library/security/ms16-054)

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
(3115103)  
(重要)  
Microsoft Word 2016 (32 位元版本)  
(3115094)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 位元版本)  
(3115103)  
(重要)  
Microsoft Word 2016 (64 位元版本)  
(3115094)  
(重大)

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
[**MS16-054**](https://technet.microsoft.com/zh-tw/library/security/ms16-054)

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
Microsoft Word for Mac 2011  
(3155776)  
(重大)

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
[**MS16-054**](https://technet.microsoft.com/zh-tw/library/security/ms16-054)

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
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Word 2016 for Mac  
(3155777)  
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
[**MS16-054**](https://technet.microsoft.com/zh-tw/library/security/ms16-054)

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
(3115115)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3115132)  
(重大)

</td>
</tr>
</table>
 
**MS16-054 注意事項**

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
[**MS16-054**](https://technet.microsoft.com/zh-tw/library/security/ms16-054)

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
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3115117)  
(重大)

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
[**MS16-054**](https://technet.microsoft.com/zh-tw/library/security/ms16-054)

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
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3115124)  
(重大)

</td>
</tr>
</table>
 
**MS16-054 注意事項**

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

Microsoft 了解資訊安全業界所做的努力，其盡責地透露弱點來協助我們保護客戶。請參閱[致謝](https://technet.microsoft.com/zh-tw/library/security/mt674627.aspx) (英文) 以取得詳細資訊。

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

協助保護您的 Widows 電腦免於病毒和惡意軟體攻擊：[病毒解決方案與資訊安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-tw)

您所在國家/地區的當地支援：[多語系支援](http://support.microsoft.com/common/international.aspx?ln=zh-tw)

### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

### 修訂

-   V1.0 (2016 年 5 月 10 日)：公告摘要發行。
-   V1.1 (2016 年 5 月 11 日)：修訂公告摘要以將 MS16-061 的弱點影響從權限提高變更為遠端執行程式碼，以及將 CVE 2016-0178 的標題變更為 RPC 網路資料表現引擎遠端執行程式碼弱點。這只是資訊的變更。
-   V1.2 (2016 年 5 月 13 日)：針對 MS16-067 修訂公告摘要，將 Windows 8.1 和 Windows RT 8.1 的弱點嚴重性等級變更為「不適用」，因為這些作業系統不會受到此公告中所描述之弱點的影響。已套用安全性更新 3155784 的客戶不必採取任何行動。這只是資訊的變更。
-   V2.0 (2016 年 5 月 13 日)：針對 MS16-064 修訂公告摘要，宣佈發行更新 3163207 以解決包含於 Adobe 資訊安全公告 APSB16-15 中的弱點。請注意，更新 3163207 會取代此公告中先前發行的更新 (更新 3157993)。Microsoft 強烈建議客戶安裝更新 3163207 以協助防止受到 Adobe 資訊安全公告 APSB16-15 中所描述之弱點的攻擊。
-   V2.1 (2016 年 5 月 25 日)：針對 MS16-065 新增「提要」表格上的已知問題。當您在 Lync Server 2010、Lync Server 2013 或商務用 Skype for Business Server 2015 的前端或 Standard Edition 伺服器上安裝 MS16-065 中的任何安全性更新後，許多會議樣式無法再讓內部使用者使用。如需如何解決此已知問題的詳細資訊，請參閱 [Microsoft 知識庫文章 3165438](https://support.microsoft.com/zh-tw/kb/3165438)。

*頁面產生時間：2016-05-25 12:52-07:00。*
