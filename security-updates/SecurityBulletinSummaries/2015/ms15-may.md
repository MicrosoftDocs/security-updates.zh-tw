---
TOCTitle: 'MS15-MAY'
Title: 2015 年 5 月 Microsoft 資訊安全公告摘要
ms:assetid: 'ms15-may'
ms:contentKeyID: 65633666
ms:date: '05/22/2015'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms15-may(v=Security.10)'
---

2015 年 5 月 Microsoft 資訊安全公告摘要
=======================================

發行日期：2015 年 5 月 12 日

**版本：** 1.0

此公告摘要列出 2015 年 5 月發行之資訊安全公告。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://technet.microsoft.com/zh-tw/security/dd252948.aspx)。

Microsoft 也會提供資訊協助客戶排定每月資訊安全更新以及任何非安全性更新的優先順序，其中這些非安全性更新的發行日期與每月安全性更新的發行日期相同。請參閱**＜其他資訊＞**一節。

提要
----

下表依嚴重性摘要說明本月份資訊安全公告。

如需受影響之軟體的詳細資料，請參閱下節**＜受影響的軟體＞**。

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
<td style="border:1px solid black;"><strong>公告 ID</strong></td>
<td style="border:1px solid black;"><strong>公告標題與提要</strong></td>
<td style="border:1px solid black;"><strong>最高的嚴重性等級<br />
和弱點影響</strong></td>
<td style="border:1px solid black;"><strong>重新啟動需求</strong></td>
<td style="border:1px solid black;"><strong>已知<br />
問題</strong></td>
<td style="border:1px solid black;"><strong>受影響的軟體</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 積存安全性更新 (3049563)</strong> <br />
此安全性更新可解決 Internet Explorer 中的弱點。其中最嚴重的弱點，可能在使用者以 Internet Explorer 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用這些弱點的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-044">MS15-044</a></td>
<td style="border:1px solid black;"><strong>Microsoft 字型驅動程式中的弱點可能會允許遠端執行程式碼 (3057110)</strong><br />
此安全性更新可以解決 Microsoft Windows、Microsoft.NET Framework、Microsoft Office、Microsoft Lync 和 Microsoft Silverlight 中的弱點。如果使用者開啟蓄意製作的文件，或是造訪內嵌 TrueType 字型的不受信任網頁，這些弱點中最嚴重者可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3057110">3057110</a></td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework、<br />
Microsoft Office、<br />
Microsoft Lync、<br />
Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-045">MS15-045</a></td>
<td style="border:1px solid black;"><strong>Windows 筆記本中的弱點可能會允許遠端執行程式碼 (3046002)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果使用者開啟蓄意製作的筆記本檔案，則這些弱點可能會允許遠端執行程式碼。設定為具有較少使用者權限的使用者帳戶所受到的影響，可能會比利用系統管理使用者權限進行操作的使用者帳戶小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-046">MS15-046</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 的弱點可能會允許遠端執行程式碼 (3057181)<br />
</strong>此安全性更新可解決 Microsoft Office 中的弱點。如果使用者開啟蓄意製作的 Microsoft Office 檔案，最嚴重的弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者，能以目前使用者的權限層級執行任意程式碼。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-047">MS15-047</a></td>
<td style="border:1px solid black;"><strong>Microsoft SharePoint Server 中的弱點可能會允許遠端執行程式碼 (3058083)<br />
</strong>此安全性更新可解決 Microsoft Office 伺服器軟體中的弱點。如果通過驗證的攻擊者傳送蓄意製作的頁面內容給 SharePoint Server，這些弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者，將能夠以目標 SharePoint 網站上 W3WP 服務帳戶的安全性層級執行任意程式碼。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft 伺服器軟體</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-048">MS15-048</a></td>
<td style="border:1px solid black;"><strong>.NET Framework 中的弱點可能會允許權限提高 (3057134)</strong><br />
這個安全性更新可解決 Microsoft .NET Framework 中的弱點。如果使用者安裝蓄意製作的局部信任應用程式，則最嚴重的弱點可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-049">MS15-049</a></td>
<td style="border:1px solid black;"><strong>Silverlight 中的弱點可能會允許權限提高 (3058985)</strong><br />
此安全性更新可解決 Microsoft Silverlight 中的弱點。如果在受影響的系統上執行蓄意製作的 Silverlight 應用程式，此弱點可能會允許權限提高。若要利用此弱點，攻擊者首先必須登入系統，或引誘登入的使用者執行蓄意製作的應用程式。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">不需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Silverlight</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-050">MS15-050</a></td>
<td style="border:1px solid black;"><strong>服務控制管理員中的弱點可能會允許權限提高 (3055642)</strong><br />
此安全性更新可解決 Windows 服務控制管理員 (SCM) 中的弱點，而此弱點是在 SCM 不當確認虛擬層級時導致的。如果攻擊者可以先登入系統，然後執行蓄意製作的應用程式，而其設計在於提高權限，則此弱點可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-051">MS15-051</a></td>
<td style="border:1px solid black;"><strong>Windows 核心模式驅動程式中的弱點可能會允許權限提高 (3057191)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者在本機登入，並在核心模式中執行任意程式碼，則其中更嚴重的弱點可能會允許權限提高。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。攻擊者必須具備有效的登入認證且可以登入本機，才能利用這個弱點。無法從遠端利用此弱點，匿名使用者也無法這樣做。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-052">MS15-052</a></td>
<td style="border:1px solid black;"><strong>Windows 核心中的弱點可能允許安全性功能略過 (3050514)</strong><br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者登入受影響的系統，並執行蓄意製作的應用程式，則此弱點可能會允許資訊安全功能略過。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
資訊安全功能略過</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3050514">3050514</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-053">MS15-053</a></td>
<td style="border:1px solid black;"><strong>JScript 和 VBScript 指令碼引擎中的弱點可能會允許資訊安全功能略過 (3057263)<br />
</strong>此安全性更新可在 Microsoft Windows 解決 VBScript 與 JScript 指令碼引擎中的 ASLR 資訊安全功能略過。攻擊者可以使用其中一個 ASLR 略過與另一個弱點 (如遠端執行程式碼弱點) 搭配，在目標系統上更可靠地執行任意程式碼。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
資訊安全功能略過</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-054">MS15-054</a></td>
<td style="border:1px solid black;"><strong>Microsoft Management Console 檔案格式中的弱點可能會允許阻斷服務 (3051768)</strong><br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果遠端未經驗證的攻擊者引誘使用者開啟一個共用，其中包含蓄意製作的 .msc 檔案，則此弱點可能會允許阻斷服務。不過，攻擊者無法強制使用者造訪共用或檢視檔案。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
阻斷服務 (DoS)</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-055">MS15-055</a></td>
<td style="border:1px solid black;"><strong>Schannel 中的弱點可能會允許資訊洩漏 (3061518)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。當安全通道 (Schannel) 允許在加密的 TLS 工作階段中使用長度為 512 位元的弱式 Diffie-Hellman 暫時 (DHE) 金鑰時，此弱點可能會允許資訊洩漏。允許 512 位元 DHE 金鑰會使 DHE 金鑰交換變弱，因而容易遭到各種攻擊。伺服器需要支援 512 位元 DHE 金鑰長度，攻擊才會成功；在 Windows 伺服器的預設設定中，最小可允許的 DHE 金鑰長度為 1024 位元。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
資訊洩漏</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3061518">3061518</a></td>
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
<td style="border:1px solid black;"><strong>公告 ID</strong></td>
<td style="border:1px solid black;"><strong>弱點標題</strong></td>
<td style="border:1px solid black;"><strong>CVE ID</strong></td>
<td style="border:1px solid black;"><strong>較早軟體版本的<br />
弱點評估</strong></td>
<td style="border:1px solid black;"><strong>較早軟體版本的<br />
弱點評估</strong></td>
<td style="border:1px solid black;"><strong>阻絕服務<br />
弱點評估</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1658">CVE-2015 -1658</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">VBScript ASLR 略過</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1684">CVE-2015 -1684</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer ASLR 略過</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1685">CVE-2015 -1685</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">VBScript 和 JScript ASLR 略過</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1686">CVE-2015 -1686</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1688">CVE-2015 -1688</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1689">CVE-2015 -1689</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1691">CVE-2015 -1691</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 剪貼簿資訊洩漏弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1692">CVE-2015 -1692</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1694">CVE-2015 -1694</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1703">CVE-2015 -1703</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1704">CVE-2015 -1704</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1705">CVE-2015 -1705</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1706">CVE-2015 -1706</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1708">CVE-2015 -1708</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1709">CVE-2015 -1709</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1710">CVE-2015 -1710</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1711">CVE-2015 -1711</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1712">CVE-2015 -1712</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1713">CVE-2015 -1713</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1714">CVE-2015 -1714</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1717">CVE-2015 -1717</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1718">CVE-2015 -1718</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-044">MS15-044</a></td>
<td style="border:1px solid black;">OpenType 字型剖析弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1670">CVE-2015 -1670</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-044">MS15-044</a></td>
<td style="border:1px solid black;">TrueType 字型剖析弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1671">CVE-2015 -1671</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-045">MS15-045</a></td>
<td style="border:1px solid black;">Windows 筆記本遠端執行程式碼弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1675">CVE-2015 -1675</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-045">MS15-045</a></td>
<td style="border:1px solid black;">Windows 筆記本遠端執行程式碼弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1695">CVE-2015 -1695</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-045">MS15-045</a></td>
<td style="border:1px solid black;">Windows 筆記本遠端執行程式碼弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1696">CVE-2015 -1696</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-045">MS15-045</a></td>
<td style="border:1px solid black;">Windows 筆記本遠端執行程式碼弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1697">CVE-2015 -1697</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-045">MS15-045</a></td>
<td style="border:1px solid black;">Windows 筆記本遠端執行程式碼弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1698">CVE-2015 -1698</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-045">MS15-045</a></td>
<td style="border:1px solid black;">Windows 筆記本遠端執行程式碼弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1699">CVE-2015 -1699</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-046">MS15-046</a></td>
<td style="border:1px solid black;">Microsoft Office 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1682">CVE-2015 -1682</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-046">MS15-046</a></td>
<td style="border:1px solid black;">Microsoft Office 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1683">CVE-2015 -1683</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-047">MS15-047</a></td>
<td style="border:1px solid black;">Microsoft SharePoint 頁面內容弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1700">CVE-2015 -1700</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-048">MS15-048</a></td>
<td style="border:1px solid black;">.NET XML 解密阻斷服務弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1672">CVE-2015 -1672</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-048">MS15-048</a></td>
<td style="border:1px solid black;">Windows Forms 權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1673">CVE-2015 -1673</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-049">MS15-049</a></td>
<td style="border:1px solid black;">Microsoft Silverlight 瀏覽器應用程式外用弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1715">CVE-2015 -1715</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-050">MS15-050</a></td>
<td style="border:1px solid black;">服務控制管理員權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1702">CVE-2015 -1702</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-051">MS15-051</a></td>
<td style="border:1px solid black;">Microsoft Windows 核心記憶體洩露弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1676">CVE-2015 -1676</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-051">MS15-051</a></td>
<td style="border:1px solid black;">Microsoft Windows 核心記憶體洩露弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1677">CVE-2015 -1677</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-051">MS15-051</a></td>
<td style="border:1px solid black;">Microsoft Windows 核心記憶體洩露弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1678">CVE-2015 -1678</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-051">MS15-051</a></td>
<td style="border:1px solid black;">Microsoft Windows 核心記憶體洩露弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1679">CVE-2015 -1679</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-051">MS15-051</a></td>
<td style="border:1px solid black;">Microsoft Windows 核心記憶體洩露弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1680">CVE-2015 -1680</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-051">MS15-051</a></td>
<td style="border:1px solid black;">Win32k 權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1701">CVE-2015 -1701</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">0 - 已偵測到利用</td>
<td style="border:1px solid black;">永久</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-052">MS15-052</a></td>
<td style="border:1px solid black;">Windows 核心資訊安全功能略過弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1674">CVE-2015 -1674</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-053">MS15-053</a></td>
<td style="border:1px solid black;">VBScript ASLR 略過</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1684">CVE-2015 -1684</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-053">MS15-053</a></td>
<td style="border:1px solid black;">VBScript 和 JScript ASLR 略過</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1686">CVE-2015 -1686</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-054">MS15-054</a></td>
<td style="border:1px solid black;">Microsoft Management Console 檔案格式阻斷服務弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1681">CVE-2015 -1681</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">暫時</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-055">MS15-055</a></td>
<td style="border:1px solid black;">SChannel 資訊洩漏弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1716">CVE-2015 -1716</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
</tbody>
</table>
  
受影響的軟體  
------------
  
下表依據主要的軟體類別和嚴重性依序列出公告。
  
請用這些表格來瞭解可能需要安裝的安全性更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的安全性更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。
  
**注意**：一項弱點，可能需要安裝數個資訊安全更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
### Windows 作業系統及元件 (表格 2 之 1)

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-043**](https://technet.microsoft.com/zh-tw/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-tw/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/zh-tw/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/zh-tw/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/zh-tw/library/security/ms15-050)

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
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3049563)  
(中度)  
Internet Explorer 7  
(3049563)  
(中度)  
Internet Explorer 8  
(3049563)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3045171)  
(重大)  
Microsoft .NET Framework 3.0 Service Pack 2 (英文)  
(3048073)  
(重大)  
Microsoft .NET Framework 4  
(3048074)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1 (英文)  
(3023211)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2 (英文)  
(3023220)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2 (英文)  
(3035488)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(沒有更新；請參閱附註)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3049563)  
(中度)  
Internet Explorer 7  
(3049563)  
(中度)  
Internet Explorer 8  
(3049563)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3045171)  
(重大)  
Microsoft .NET Framework 3.0 Service Pack 2 (英文)  
(3048073)  
(重大)  
Microsoft .NET Framework 4  
(3048074)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2 (英文)  
(3023220)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2 (英文)  
(3035488)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(沒有更新；請參閱附註)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3049563)  
(中度)  
Internet Explorer 7  
(3049563)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(3045171)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2 (英文)  
(3023220)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2 (英文)  
(3035488)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(沒有更新；請參閱附註)  
(重要)

</td>
</tr>
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
[**MS15-043**](https://technet.microsoft.com/zh-tw/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-tw/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/zh-tw/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/zh-tw/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/zh-tw/library/security/ms15-050)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
Internet Explorer 7  
(3049563)  
(重大)  
Internet Explorer 8  
(3049563)  
(重大)  
Internet Explorer 9  
(3049563)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3045171)  
(重大)  
Microsoft .NET Framework 3.0 Service Pack 2 (英文)  
(3048068)  
(重大)  
Microsoft .NET Framework 4  
(3048074)  
(重大)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3048077)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3046002)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2 (英文)  
(3023213)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2 (英文)  
(3035485)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3055642)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3049563)  
(重大)  
Internet Explorer 8  
(3049563)  
(重大)  
Internet Explorer 9  
(3049563)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3045171)  
(重大)  
Microsoft .NET Framework 3.0 Service Pack 2 (英文)  
(3048068)  
(重大)  
Microsoft .NET Framework 4  
(3048074)  
(重大)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3048077)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3046002)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2 (英文)  
(3023213)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2 (英文)  
(3035485)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3055642)  
(重要)

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
[**MS15-043**](https://technet.microsoft.com/zh-tw/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-tw/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/zh-tw/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/zh-tw/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/zh-tw/library/security/ms15-050)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
</tr>
<tr>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3049563)  
(中度)  
Internet Explorer 8  
(3049563)  
(中度)  
Internet Explorer 9  
(3049563)  
(中度)

</td>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2  
(3045171)  
(重大)  
Microsoft .NET Framework 3.0 Service Pack 2 (英文)  
(3048068)  
(重大)  
Microsoft .NET Framework 4  
(3048074)  
(重大)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3048077)  
(重大)

</td>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2  
(3046002)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2 (英文)  
(3023213)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2 (英文)  
(3035485)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
(重要)

</td>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2  
(3055642)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3049563)  
(中度)  
Internet Explorer 8  
(3049563)  
(中度)  
Internet Explorer 9  
(3049563)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3045171)  
(重大)  
Microsoft .NET Framework 3.0 Service Pack 2 (英文)  
(3048068)  
(重大)  
Microsoft .NET Framework 4  
(3048074)  
(重大)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3048077)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3046002)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2 (英文)  
(3023213)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2 (英文)  
(3035485)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3055642)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3049563)  
(中度)

</td>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2  
(3045171)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2 (英文)  
(3023213)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2 (英文)  
(3035485)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)

</td>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2  
(3055642)  
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
[**MS15-043**](https://technet.microsoft.com/zh-tw/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-tw/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/zh-tw/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/zh-tw/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/zh-tw/library/security/ms15-050)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
Internet Explorer 8  
(3049563)  
(重大)  
Internet Explorer 9  
(3049563)  
(重大)  
Internet Explorer 10  
(3049563)  
(重大)  
Internet Explorer 11  
(3049563)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3045171)  
(重大)  
Microsoft .NET Framework 3.5.1  
(3048070)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3046002)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3023215)  
(重要)  
Microsoft .NET Framework 3.5.1  
(3032655)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3055642)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3049563)  
(重大)  
Internet Explorer 9  
(3049563)  
(重大)  
Internet Explorer 10  
(3049563)  
(重大)  
Internet Explorer 11  
(3049563)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3045171)  
(重大)  
Microsoft .NET Framework 3.5.1  
(3048070)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3046002)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3023215)  
(重要)  
Microsoft .NET Framework 3.5.1  
(3032655)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3055642)  
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
[**MS15-043**](https://technet.microsoft.com/zh-tw/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-tw/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/zh-tw/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/zh-tw/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/zh-tw/library/security/ms15-050)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3049563)  
(中度)  
Internet Explorer 9  
(3049563)  
(中度)  
Internet Explorer 10  
(3049563)  
(中度)  
Internet Explorer 11  
(3049563)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3045171)  
(重大)  
Microsoft .NET Framework 3.5.1  
(3048070)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3046002)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3023215)  
(重要)  
Microsoft .NET Framework 3.5.1  
(3032655)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3055642)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3049563)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3045171)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3023215)  
(重要)  
Microsoft .NET Framework 3.5.1  
(3032655)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3055642)  
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
[**MS15-043**](https://technet.microsoft.com/zh-tw/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-tw/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/zh-tw/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/zh-tw/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/zh-tw/library/security/ms15-050)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
Internet Explorer 10  
(3049563)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3045171)  
(重大)  
Microsoft .NET Framework 3.5  
(3048071)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3046002)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023217)  
(重要)  
Microsoft .NET Framework 3.5  
(3035486)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023223)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035489)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3055642)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 x64 系統

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3049563)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3045171)  
(重大)  
Microsoft .NET Framework 3.5  
(3048071)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3046002)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023217)  
(重要)  
Microsoft .NET Framework 3.5  
(3035486)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023223)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035489)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3055642)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3049563)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3045171)  
(重大)  
Microsoft .NET Framework 3.5  
(3048072)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3046002)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023219)  
(重要)  
Microsoft .NET Framework 3.5  
(3035487)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3023222)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3032663)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3055642)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 x64 系統

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3049563)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3045171)  
(重大)  
Microsoft .NET Framework 3.5  
(3048072)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3046002)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023219)  
(重要)  
Microsoft .NET Framework 3.5  
(3035487)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3023222)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3032663)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3055642)  
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
[**MS15-043**](https://technet.microsoft.com/zh-tw/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-tw/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/zh-tw/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/zh-tw/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/zh-tw/library/security/ms15-050)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3049563)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3045171)  
(重大)  
Microsoft .NET Framework 3.5  
(3048071)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3046002)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023217)  
(重要)  
Microsoft .NET Framework 3.5  
(3035486)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023223)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035489)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3055642)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3049563)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3045171)  
(重大)  
Microsoft .NET Framework 3.5  
(3048072)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3046002)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023219)  
(重要)  
Microsoft .NET Framework 3.5  
(3035487)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3023222)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3032663)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3055642)  
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
[**MS15-043**](https://technet.microsoft.com/zh-tw/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-tw/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/zh-tw/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/zh-tw/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/zh-tw/library/security/ms15-050)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
Internet Explorer 10  
(3049563)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT  
(3045171)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT  
(3046002)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023223)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035489)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3055642)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3049563)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3045171)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3046002)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1/4.5.2  
(3023222)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3032663)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3055642)  
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
[**MS15-043**](https://technet.microsoft.com/zh-tw/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-tw/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/zh-tw/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/zh-tw/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/zh-tw/library/security/ms15-050)

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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3045171)  
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
(3055642)  
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
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3045171)  
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
(3055642)  
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
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3045171)  
(重大)  
Microsoft .NET Framework 3.5.1  
(3048070)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3023215)  
(重要)  
Microsoft .NET Framework 3.5.1  
(3032655)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3055642)  
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
Windows Server 2012 (Server Core 安裝)  
(3045171)  
(重大)  
Microsoft .NET Framework 3.5  
(3048071)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023217)  
(重要)  
Microsoft .NET Framework 3.5  
(3035486)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023223)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035489)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3055642)  
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
Windows Server 2012 R2 (Server Core 安裝)  
(3045171)  
(重大)  
Microsoft .NET Framework 3.5  
(3048072)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023219)  
(重要)  
Microsoft .NET Framework 3.5  
(3035487)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3023222)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3032663)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3055642)  
(重要)

</td>
</tr>
</table>
 
**MS15-044 注释**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

這些更新也可供 Microsoft .NET Framework 4.6 RC 使用，但僅能透過 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得。

**MS15-043、MS15-044 和 MS15-045 的附註**

Windows Technical Preview 和 Windows Server Technical Preview 會受影響。建議執行這些作業系統的客戶透過 [Windows Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-tw) 套用此更新。

**MS15-050 的附註**

Windows Server 2003 受到影響，但是未對其發行更新。請參閱公告，了解詳細資訊。

** **

### Windows 作業系統及元件 (表格 2 之 2)

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-051**](https://technet.microsoft.com/zh-tw/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/zh-tw/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/zh-tw/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/zh-tw/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/zh-tw/library/security/ms15-055)

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
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
JScript 5.6 和 VBScript 5.6   
(3050946)  
(重要)  
JScript 5.7 和 VBScript 5.7   
(3050945)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
JScript 5.6 和 VBScript 5.6   
(3050946)  
(重要)  
JScript 5.7 和 VBScript 5.7   
(3050945)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
JScript 5.6 和 VBScript 5.6   
(3050946)  
(重要)  
JScript 5.7 和 VBScript 5.7   
(3050945)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(3061518)  
(重要)

</td>
</tr>
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
[**MS15-051**](https://technet.microsoft.com/zh-tw/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/zh-tw/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/zh-tw/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/zh-tw/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/zh-tw/library/security/ms15-055)

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
Windows Vista Service Pack 2  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
JScript 5.7 和 VBScript 5.7   
(3050945)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
JScript 5.7 和 VBScript 5.7   
(3050945)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3061518)  
(重要)

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
[**MS15-051**](https://technet.microsoft.com/zh-tw/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/zh-tw/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/zh-tw/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/zh-tw/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/zh-tw/library/security/ms15-055)

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
32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
JScript 5.7 和 VBScript 5.7   
(3050945)  
(重要)

</td>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
JScript 5.7 和 VBScript 5.7   
(3050945)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
JScript 5.7 和 VBScript 5.7   
(3050945)  
(重要)

</td>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2  
(3061518)  
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
[**MS15-051**](https://technet.microsoft.com/zh-tw/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/zh-tw/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/zh-tw/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/zh-tw/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/zh-tw/library/security/ms15-055)

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
Windows 7 32 位元系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3061518)  
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
[**MS15-051**](https://technet.microsoft.com/zh-tw/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/zh-tw/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/zh-tw/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/zh-tw/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/zh-tw/library/security/ms15-055)

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
Windows Server 2008 R2 x64 系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3061518)  
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
[**MS15-051**](https://technet.microsoft.com/zh-tw/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/zh-tw/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/zh-tw/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/zh-tw/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/zh-tw/library/security/ms15-055)

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
Windows 8 32 位元系統

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3050514)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 x64 系統

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3050514)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3050514)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 x64 系統

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3050514)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3061518)  
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
[**MS15-051**](https://technet.microsoft.com/zh-tw/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/zh-tw/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/zh-tw/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/zh-tw/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/zh-tw/library/security/ms15-055)

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
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3050514)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3050514)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3061518)  
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
[**MS15-051**](https://technet.microsoft.com/zh-tw/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/zh-tw/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/zh-tw/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/zh-tw/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/zh-tw/library/security/ms15-055)

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
Windows RT

</td>
<td style="border:1px solid black;">
Windows RT  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3050514)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3050514)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3061518)  
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
[**MS15-051**](https://technet.microsoft.com/zh-tw/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/zh-tw/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/zh-tw/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/zh-tw/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/zh-tw/library/security/ms15-055)

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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
JScript 5.7 和 VBScript 5.7   
(3050945)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
JScript 5.7 和 VBScript 5.7   
(3050945)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
JScript 5.8 和 VBScript 5.8   
(3050941)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3050514)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3050514)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3061518)  
(重要)

</td>
</tr>
</table>
 
**MS15-053 和 MS15-054 的附註：**

Windows Technical Preview 和 Windows Server Technical Preview 會受影響。建議執行這些作業系統的客戶透過 [Windows Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-tw) 套用此更新。

 

### Microsoft 伺服器軟體

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/zh-tw/library/security/ms15-046)

</td>
<td style="border:1px solid black;">
[**MS15-047**](https://technet.microsoft.com/zh-tw/library/security/ms15-047)

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
Microsoft SharePoint Server 2007 Service Pack 3 (32 位元版本)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (32 位元版本)  
(2760412)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 位元版本)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 位元版本)  
(2760412)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/zh-tw/library/security/ms15-046)

</td>
<td style="border:1px solid black;">
[**MS15-047**](https://technet.microsoft.com/zh-tw/library/security/ms15-047)

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
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 2  
(3017815)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 2  
(3017815)  
(重要)  
Microsoft SharePoint Server 2010 Service Pack 2  
(2956192)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/zh-tw/library/security/ms15-046)

</td>
<td style="border:1px solid black;">
[**MS15-047**](https://technet.microsoft.com/zh-tw/library/security/ms15-047)

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
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1  
(3039736)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1  
(3054792)  
(重要)

</td>
</tr>
</table>
 
**MS15-046 的附註**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

 

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
[**MS15-044**](https://technet.microsoft.com/zh-tw/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/zh-tw/library/security/ms15-046)

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
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2883029)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2965282)  
(重要)

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
[**MS15-044**](https://technet.microsoft.com/zh-tw/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/zh-tw/library/security/ms15-046)

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
Microsoft Office 2010 Service Pack 2 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(2881073)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(2965311)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(2999412)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(2965242)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (32 位元版本)  
(2965240)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (32 位元版本)  
(2999420)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 位元版本)  
(2965237)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(2881073)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(2965311)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(2999412)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(2965242)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (64 位元版本)  
(2965240)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (64 位元版本)  
(2999420)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 位元版本)  
(2965237)  
(重要)

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
[**MS15-044**](https://technet.microsoft.com/zh-tw/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/zh-tw/library/security/ms15-046)

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
Microsoft Office 2013 Service Pack 1 (32 位元版本)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 位元版本)  
(2975808)  
(重要)  
Microsoft Excel 2013 Service Pack 1 (32 位元版本)  
(2986216)  
(重要)  
Microsoft PowerPoint 2013 Service Pack 1 (32 位元版本)  
(2975816)  
(重要)  
Microsoft Word 2013 Service Pack 1 (32 位元版本)  
(2965307)  
(重要)

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
Microsoft Office 2013 Service Pack 1 (64 位元版本)  
(2975808)  
(重要)  
Microsoft Excel 2013 Service Pack 1 (64 位元版本)  
(2986216)  
(重要)  
Microsoft PowerPoint 2013 Service Pack 1 (64 位元版本)  
(2975816)  
(重要)  
Microsoft Word 2013 Service Pack 1 (64 位元版本)  
(2965307)  
(重要)

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
[**MS15-044**](https://technet.microsoft.com/zh-tw/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/zh-tw/library/security/ms15-046)

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
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1  
(2975808)  
(重要)  
Microsoft Excel 2013 RT Service Pack 1  
(2986216)  
(重要)  
Microsoft PowerPoint 2013 RT Service Pack 1  
(2975816)  
(重要)  
Microsoft Word 2013 RT Service Pack 1  
(2965307)  
(重要)

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
[**MS15-044**](https://technet.microsoft.com/zh-tw/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/zh-tw/library/security/ms15-046)

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
Microsoft Office for Mac 2011  
(3048688)  
(重要)  
Microsoft Excel for Mac 2011  
(3048688)  
(重要)  
Microsoft PowerPoint for Mac 2011  
(3048688)  
(重要)  
Microsoft Word for Mac 2011  
(3048688)  
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
[**MS15-044**](https://technet.microsoft.com/zh-tw/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/zh-tw/library/security/ms15-046)

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
Microsoft PowerPoint Viewer

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer  
(2956195)  
(重要)

</td>
</tr>
</table>
 
**MS15-044 和 MS15-046 的附註**

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
[**MS15-046**](https://technet.microsoft.com/zh-tw/library/security/ms15-046)

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
(2965233)  
(重要)  
Excel Services  
(2956194)  
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
[**MS15-046**](https://technet.microsoft.com/zh-tw/library/security/ms15-046)

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
(3023055)  
(重要)  
Excel Services  
(3039725)  
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
[**MS15-046**](https://technet.microsoft.com/zh-tw/library/security/ms15-046)

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
(2956140)  
(重要)  
Microsoft Excel Web Apps 2010 Service Pack 2  
(2956193)  
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
[**MS15-046**](https://technet.microsoft.com/zh-tw/library/security/ms15-046)

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
(3039748)  
(重要)

</td>
</tr>
</table>
 
**MS15-046 的附註**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

 

### Microsoft 通訊平台和軟體

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Live Meeting 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-tw/library/security/ms15-044)

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
(3051467)  
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
[**MS15-044**](https://technet.microsoft.com/zh-tw/library/security/ms15-044)

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
(3051464)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 位元)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 位元)  
(3051464)  
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
(3051465)  
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
(3051466)  
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
[**MS15-044**](https://technet.microsoft.com/zh-tw/library/security/ms15-044)

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

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (32 位元)  
(Skype for Business)  
(3039779)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (32 位元)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (32 位元)  
(Skype for Business Basic)  
(3039779)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (64 位元)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (64 位元)  
(Skype for Business)  
(3039779)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (64 位元)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (64 位元)  
(Skype for Business Basic)  
(3039779)  
(重大)

</td>
</tr>
</table>
 
**MS15-044 的附註**

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
[**MS15-044**](https://technet.microsoft.com/zh-tw/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-049**](https://technet.microsoft.com/zh-tw/library/security/ms15-049)

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
Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
安裝在 Mac 上的 Microsoft Silverlight 5  
(3056819)  
(重大)  
安裝在 Mac 上的 Microsoft Silverlight 5 Developer Runtime  
(3056819)  
(重大)  
安裝在所有受支援版本的 Microsoft Windows 用戶端上的 Microsoft Silverlight 5  
(3056819)  
(重大)  
安裝在所有受支援的 Microsoft Windows 用戶端版本上的 Microsoft Silverlight 5 Developer Runtime  
(3056819)  
(重大)  
安裝在所有受支援的 Microsoft Windows 伺服器版本上的 Microsoft Silverlight 5  
(3056819)  
(重大)  
安裝在所有受支援的 Microsoft Windows 伺服器版本上的 Microsoft Silverlight 5 Developer Runtime  
(3056819)  
(重大)

</td>
<td style="border:1px solid black;">
安裝在 Mac 上的 Microsoft Silverlight 5  
(3056819)  
(重要)  
安裝在 Mac 上的 Microsoft Silverlight 5 Developer Runtime  
(3056819)  
(重要)  
安裝在所有受支援版本的 Microsoft Windows 用戶端上的 Microsoft Silverlight 5  
(3056819)  
(重要)  
安裝在所有受支援的 Microsoft Windows 用戶端版本上的 Microsoft Silverlight 5 Developer Runtime  
(3056819)  
(重要)  
安裝在所有受支援的 Microsoft Windows 伺服器版本上的 Microsoft Silverlight 5  
(3056819)  
(重要)  
安裝在所有受支援的 Microsoft Windows 伺服器版本上的 Microsoft Silverlight 5 Developer Runtime  
(3056819)  
(重要)

</td>
</tr>
</table>
 
**MS15-044 的附註**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

 

偵測與部署工具及指南
--------------------

有幾項資源可協助系統管理員部署資訊安全更新。

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機與遠端系統是否有遺漏的安全性更新或常見的安全性錯誤設定。

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

[更新管理安全性指南](http://technet.microsoft.com/zh-tw/library/bb466251.aspx) (英文) 提供您有關套用資訊安全更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他資訊安全問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得，您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-tw) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的資訊安全更新。如需更多資訊，請參閱 [Microsoft 知識庫文章 913086](https://support.microsoft.com/zh-tw/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](http://technet.microsoft.com/zh-tw/security/cc136632.aspx)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

### 支援

所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](https://support.microsoft.com/zh-tw/lifecycle)。

適用於 IT 專業人員的安全性解決方案：[安全性疑難排解與支援](http://technet.microsoft.com/zh-tw/security/bb980617)

協助保護您執行 Windows 的電腦免於受到病毒和惡意程式碼攻擊：[病毒解決方案與資訊安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-tw)

根據您所在國家/地區的當地支援：[國際支援](http://support.microsoft.com/common/international.aspx?ln=zh-tw)

### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

### 修訂

-   V1.0 (2015 年 5 月 12 日)：公告摘要發行。

*頁面產生時間：2015-05-19 13:28Z-07:00。*
