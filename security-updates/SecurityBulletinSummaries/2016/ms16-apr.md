---
TOCTitle: 'MS16-APR'
Title: 2016 年 4 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms16-apr'
ms:contentKeyID: 72785290
ms:date: '09/09/2017'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms16-apr(v=Security.10)'
---

2016 年 4 月份 Microsoft 資訊安全公告摘要
=========================================

發行日期：2016 年 4 月 12 日 | 更新日期：2017 年 9 月 12 日

**版本：**4.0

此公告摘要列出 2016 年 4 月份所發行的資訊安全公告。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知的詳細資訊，請造訪 [Microsoft 技術安全性通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性更新的優先順序，其中這些非安全性更新的發行日期與每月安全性更新的發行日期相同。請參閱**＜其他資訊＞**一節。

提要
----

下表依嚴重性摘要說明本月份資訊安全公告。

如需受影響軟體的詳細資訊，請參閱下一節**＜受影響的軟體＞**。

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
<td style="border:1px solid black;"><strong>最高嚴重性分級<br />
與弱點影響</strong></td>
<td style="border:1px solid black;"><strong>重新啟動需求</strong></td>
<td style="border:1px solid black;"><strong>已知<br />
問題</strong></td>
<td style="border:1px solid black;"><strong>受影響的軟體</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=746891">MS16-037</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 累積安全性更新 (3148531)<br />
</strong>這個安全性更新可解決 Internet Explorer 中的弱點。如果使用者使用 Internet Explorer 檢視蓄意製作的網頁，最嚴重的弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者可以取得與本機使用者相同的使用者權限。如果目前使用者以系統管理的使用者權限登入，則攻擊者即可取得受影響系統的控制權。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=746894">MS16-038</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 累積安全性更新 (3148532)<br />
</strong>這個安全性更新可解決 Microsoft Edge 中的弱點。其中最嚴重的弱點，可能在使用者以 Microsoft Edge 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用這些弱點的攻擊者可以取得與本機使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=746883">MS16-039</a></td>
<td style="border:1px solid black;"><strong>Microsoft 圖形元件的安全性更新 (3148522)</strong><br />
此安全性更新可以解決 Microsoft Windows、Microsoft .NET Framework、Microsoft Office、商務用 Skype 和 Microsoft Lync 中的弱點。如果使用者開啟蓄意製作的文件，或是造訪包含蓄意內嵌字型的網頁，最嚴重的弱點可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3148522">3148522</a></td>
<td style="border:1px solid black;">Microsoft Windows、Microsoft .NET Framework、<br />
Microsoft Office、商務用 Skype、<br />
Microsoft Lync。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=746897">MS16-040</a></td>
<td style="border:1px solid black;"><strong>Microsoft XML Core Services 的安全性更新 (3148541)</strong><br />
這個安全性更新可解決 Microsoft Windows 中的弱點。如果使用者按一下能讓攻擊者遠端執行惡意程式碼以控制使用者系統而蓄意製作的連結，該弱點將允許遠端程式碼執行。但在所有情況下，攻擊者都無法強迫使用者按一下蓄意製作的連結。攻擊者必須引誘使用者按一下連結，一般是藉助電子郵件的附件或 Instant Messenger 訊息。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=746929">MS16-041</a></td>
<td style="border:1px solid black;"><strong>.NET Framework 的安全性更新 (3148789)</strong><br />
這個安全性更新可解決 Microsoft .Net Framework 中的弱點。如果具有本機系統存取權的攻擊者執行惡意應用程式，此弱點可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=746928">MS16-042</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 的安全性更新 (3148775)</strong><br />
這個安全性更新可解決 Microsoft Office 中的弱點。如果使用者開啟蓄意製作的 Microsoft Office 檔案，最嚴重的弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者，能以目前使用者的權限層級執行任意程式碼。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3148775">3148775</a></td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft Office Services 和 Web 應用程式</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=747040">MS16-044</a></td>
<td style="border:1px solid black;"><strong>Windows OLE 的安全性更新 (3146706)</strong><br />
這個安全性更新可解決 Microsoft Windows 中的弱點。如果 Windows OLE 無法正確地驗證使用者輸入，這個弱點可能允許遠端執行程式碼。攻擊者可利用弱點來執行惡意程式碼。然而，攻擊者必須先引誘使用者從網頁或電子郵件訊息中開啟蓄意製作的檔案或程式。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3146706">3146706</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=733440">MS16-045</a></td>
<td style="border:1px solid black;"><strong>Windows Hyper-V 的安全性更新 (3143118)</strong><br />
這個安全性更新可解決 Microsoft Windows 中的弱點。如果客體作業系統上通過驗證的攻擊者執行蓄意製作的應用程式，造成 Hyper-V 主機作業系統執行任意程式碼，則最嚴重的弱點可能會允許遠端執行程式碼。尚未啟用 Hyper-V 角色的客戶不會受到影響。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=746896">MS16-046</a></td>
<td style="border:1px solid black;"><strong>Secondary Logon 的安全性更新 (3148538)</strong><br />
這個安全性更新可解決 Microsoft Windows 中的弱點。成功利用此弱點的攻擊者能以系統管理員身分執行任意程式碼。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=746885">MS16-047</a></td>
<td style="border:1px solid black;"><strong>SAM 和 LSAD 遠端通訊協定的安全性更新 (3148527)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者發動攔截式 (MiTM) 攻擊，這項弱點可能會允許權限提高。攻擊者便可強迫降低 SAM 和 LSAD 通道的驗證層級並模擬已驗證的使用者。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=746886">MS16-048</a></td>
<td style="border:1px solid black;"><strong>CSRSS 的安全性更新 (3148528)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者登入目標系統，並執行蓄意製作的應用程式，則此弱點可能會允許資訊安全功能略過。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
安全性功能略過</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3146723">3146723</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=746932">MS16-049</a></td>
<td style="border:1px solid black;"><strong>HTTP.sys 的安全性更新 (3148795)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者將蓄意製作的 HTTP 封包傳送給目標系統，這個弱點可能會允許阻斷服務。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
阻斷服務</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=785154">MS16-050</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player 的安全性更新 (3154132)</strong><br />
此安全性更新可解決安裝於所有受支援版本的 Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1 和 Windows 10 上之 Adobe Flash Player 中的弱點。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
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

下表提供本月所述每個弱點的利用性評估。這些弱點按照公告識別碼和 CVE ID 列出。只會列出公告上達到「重大」或「重要」嚴重性等級的弱點。

**如何使用此表格？**

您可以運用此表格，針對您可能需要安裝的每一項安全性更新，了解弱點在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務 (DoS) 的可能性。請根據您特定的組態設定，檢閱下列各項評估，決定部署本月份更新的優先順序。如需關於這些等級意義的更多資訊，以及決定等級方式的詳細資訊，請參閱 [Microsoft 弱點入侵指數](https://technet.microsoft.com/zh-tw/security/cc998259)。

在下方欄位中，「最新軟體版本」意指受影響軟體，「較舊軟體版本」意指受影響軟體所有較舊的支援版本，如公告中的「受影響的軟體」或「不受影響的軟體」表格裡所示。

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**CVE ID**                    

</td>
<td style="border:1px solid black;">
**弱點標題**

</td>
<td style="border:1px solid black;">
**最新軟體版本的  
弱點評估**

</td>
<td style="border:1px solid black;">
**較舊軟體版本的  
弱點評估**

</td>
<td style="border:1px solid black;">
**阻斷服務  
弱點評估**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-037：Internet Explorer 的累積安全性更新 (3148531)**](https://go.microsoft.com/fwlink/?linkid=746891)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0154](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0154)

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
[CVE-2016-0159](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0159)

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
[CVE-2016-0160](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0160)

</td>
<td style="border:1px solid black;">
DLL 載入遠端執行程式碼弱點

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
[CVE-2016-0162](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0162)

</td>
<td style="border:1px solid black;">
Internet Explorer 資訊洩漏弱點

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
[CVE-2016-0164](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0164)

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
[CVE-2016-0166](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0166)

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
<td style="border:1px solid black;" colspan="5">
[**MS16-038：Microsoft Edge 的累積安全性更新 (3148532)**](https://go.microsoft.com/fwlink/?linkid=746894)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0154](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0154)

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
[CVE-2016-0155](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0155)

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
[CVE-2016-0156](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0156)

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
[CVE-2016-0157](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0157)

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
[CVE-2016-0158](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0158)

</td>
<td style="border:1px solid black;">
Microsoft Edge 權限提高弱點

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
[CVE-2016-0161](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0161)

</td>
<td style="border:1px solid black;">
Microsoft Edge 權限提高弱點

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
[**MS16-039：Microsoft 圖形元件的安全性更新 (3148522)**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0143](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0143)

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
[CVE-2016-0145](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0145)

</td>
<td style="border:1px solid black;">
圖形記憶體損毀弱點

</td>
<td style="border:1px solid black;">
2 - 遭到利用的可能性較小

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
[CVE-2016-0165](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0165)

</td>
<td style="border:1px solid black;">
Win32k 權限提高弱點

</td>
<td style="border:1px solid black;">
0 - 已偵測到利用

</td>
<td style="border:1px solid black;">
0 - 已偵測到利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0167](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0167)

</td>
<td style="border:1px solid black;">
Win32k 權限提高弱點

</td>
<td style="border:1px solid black;">
0 - 已偵測到利用

</td>
<td style="border:1px solid black;">
0 - 已偵測到利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-040：Microsoft XML Core Services 的安全性更新 (3148541)**](https://go.microsoft.com/fwlink/?linkid=746897)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0147](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0147)

</td>
<td style="border:1px solid black;">
MSXML 3.0 遠端執行程式碼弱點

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
[**MS16-041：.NET Framework 的安全性更新 (3148789)**](https://go.microsoft.com/fwlink/?linkid=746929)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0148](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0148)

</td>
<td style="border:1px solid black;">
.NET Framework 遠端執行程式碼弱點

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
[**MS16-042：Microsoft Office 的安全性更新 (3148775)**](https://go.microsoft.com/fwlink/?linkid=746928)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0122](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0122)

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
[CVE-2016-0127](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0127)

</td>
<td style="border:1px solid black;">
Microsoft Office 記憶體損毀弱點

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
[CVE-2016-0136](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0136)

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
[CVE-2016-0139](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0139)

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
[**MS16-044：Windows OLE 的安全性更新 (3146706)**](https://go.microsoft.com/fwlink/?linkid=747040)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0153](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0153)

</td>
<td style="border:1px solid black;">
Windows OLE 遠端執行程式碼弱點

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
[**MS16-045：Windows Hyper-V 的安全性更新 (3143118)**](https://go.microsoft.com/fwlink/?linkid=733440)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0088](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0088)

</td>
<td style="border:1px solid black;">
Hyper-V 遠端執行程式碼弱點

</td>
<td style="border:1px solid black;">
4 - 不受影響

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
[CVE-2016-0089](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0089)

</td>
<td style="border:1px solid black;">
Hyper-V 資訊洩漏弱點

</td>
<td style="border:1px solid black;">
4 - 不受影響

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
[CVE-2016-0090](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0090)

</td>
<td style="border:1px solid black;">
Hyper-V 資訊洩漏弱點

</td>
<td style="border:1px solid black;">
4 - 不受影響

</td>
<td style="border:1px solid black;">
3 - 不太可能遭到利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-046：Secondary Logon 的安全性更新 (3148538)**](https://go.microsoft.com/fwlink/?linkid=746896)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0135](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0135)

</td>
<td style="border:1px solid black;">
Secondary Logon 權限提高弱點

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS16-047：SAM 和 LSAD 遠端通訊協定的安全性更新 (3148527)**](https://go.microsoft.com/fwlink/?linkid=746885)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0128](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0128)

</td>
<td style="border:1px solid black;">
Windows SAM 和 LSAD 降級弱點

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
[**MS16-048：CSRSS 的安全性更新 (3148528)**](https://go.microsoft.com/fwlink/?linkid=746886)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0151](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0151)

</td>
<td style="border:1px solid black;">
Windows CSRSS 資訊安全功能略過弱點

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
[**MS16-049：HTTP.sys 的安全性更新 (3148795)**](https://go.microsoft.com/fwlink/?linkid=746932)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0150](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0150)

</td>
<td style="border:1px solid black;">
HTTP.sys 阻斷服務 (DoS) 弱點

</td>
<td style="border:1px solid black;">
3 - 不太可能遭到利用

</td>
<td style="border:1px solid black;">
4 - 不受影響

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-050：Adobe Flash Player 的安全性更新 3154132**](https://go.microsoft.com/fwlink/?linkid=785154)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-10](https://helpx.adobe.com/tw/security/products/flash-player/apsb16-10.html)

</td>
<td style="border:1px solid black;">
請參閱 [Adobe 資訊安全公告 APSB16-10](https://helpx.adobe.com/tw/security/products/flash-player/apsb16-10.html) 了解弱點嚴重性以及更新優先順序等級。

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
 

受影響的軟體
------------

下表依據主要的軟體類別和嚴重性依序列出公告。

請用這些表格來了解可能需要安裝的安全性更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的安全性更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。

**注意** 一項弱點，可能需要安裝數個安全性更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。

 

### Windows 作業系統及元件 (表格 2 之 1)

 
<p></p>
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
[**MS16-037**](https://go.microsoft.com/fwlink/?linkid=746891)

</td>
<td style="border:1px solid black;">
[**MS16-038**](https://go.microsoft.com/fwlink/?linkid=746894)

</td>
<td style="border:1px solid black;">
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-040**](https://go.microsoft.com/fwlink/?linkid=746897)

</td>
<td style="border:1px solid black;">
[**MS16-041**](https://go.microsoft.com/fwlink/?linkid=746929)

</td>
<td style="border:1px solid black;">
[**MS16-044**](https://go.microsoft.com/fwlink/?linkid=747040)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4014661)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3145739)  
(重大)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3142041)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3143693)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3146706)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4014661)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3145739)  
(重大)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3142041)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3143693)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3146706)  
(重要)

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
[**MS16-037**](https://go.microsoft.com/fwlink/?linkid=746891)

</td>
<td style="border:1px solid black;">
[**MS16-038**](https://go.microsoft.com/fwlink/?linkid=746894)

</td>
<td style="border:1px solid black;">
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-040**](https://go.microsoft.com/fwlink/?linkid=746897)

</td>
<td style="border:1px solid black;">
[**MS16-041**](https://go.microsoft.com/fwlink/?linkid=746929)

</td>
<td style="border:1px solid black;">
[**MS16-044**](https://go.microsoft.com/fwlink/?linkid=747040)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**中度**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(4014661)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3145739)  
(重大)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3142041)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3143693)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3146706)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(4014661)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3145739)  
(重大)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3142041)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3143693)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3146706)  
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
(3145739)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3146706)  
(重要)

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
[**MS16-037**](https://go.microsoft.com/fwlink/?linkid=746891)

</td>
<td style="border:1px solid black;">
[**MS16-038**](https://go.microsoft.com/fwlink/?linkid=746894)

</td>
<td style="border:1px solid black;">
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-040**](https://go.microsoft.com/fwlink/?linkid=746897)

</td>
<td style="border:1px solid black;">
[**MS16-041**](https://go.microsoft.com/fwlink/?linkid=746929)

</td>
<td style="border:1px solid black;">
[**MS16-044**](https://go.microsoft.com/fwlink/?linkid=747040)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4014661)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3145739)  
(重大)  
Microsoft .NET Framework 3.5.1  
(3142042)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6/4.6.1  
(3143693)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3146706)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4014661)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3145739)  
(重大)  
Microsoft .NET Framework 3.5.1  
(3142042)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6/4.6.1  
(3143693)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3146706)  
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
[**MS16-037**](https://go.microsoft.com/fwlink/?linkid=746891)

</td>
<td style="border:1px solid black;">
[**MS16-038**](https://go.microsoft.com/fwlink/?linkid=746894)

</td>
<td style="border:1px solid black;">
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-040**](https://go.microsoft.com/fwlink/?linkid=746897)

</td>
<td style="border:1px solid black;">
[**MS16-041**](https://go.microsoft.com/fwlink/?linkid=746929)

</td>
<td style="border:1px solid black;">
[**MS16-044**](https://go.microsoft.com/fwlink/?linkid=747040)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**中度**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(4014661)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3145739)  
(重大)  
Microsoft .NET Framework 3.5.1  
(3142042)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6/4.6.1  
(3143693)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3146706)  
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
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3145739)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3146706)  
(重要)

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
[**MS16-037**](https://go.microsoft.com/fwlink/?linkid=746891)

</td>
<td style="border:1px solid black;">
[**MS16-038**](https://go.microsoft.com/fwlink/?linkid=746894)

</td>
<td style="border:1px solid black;">
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-040**](https://go.microsoft.com/fwlink/?linkid=746897)

</td>
<td style="border:1px solid black;">
[**MS16-041**](https://go.microsoft.com/fwlink/?linkid=746929)

</td>
<td style="border:1px solid black;">
[**MS16-044**](https://go.microsoft.com/fwlink/?linkid=747040)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4014661)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3145739)  
(重大)  
Microsoft .NET Framework 3.5  
(3142045)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3146706)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4014661)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3145739)  
(重大)  
Microsoft .NET Framework 3.5  
(3142045)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3146706)  
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
[**MS16-037**](https://go.microsoft.com/fwlink/?linkid=746891)

</td>
<td style="border:1px solid black;">
[**MS16-038**](https://go.microsoft.com/fwlink/?linkid=746894)

</td>
<td style="border:1px solid black;">
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-040**](https://go.microsoft.com/fwlink/?linkid=746897)

</td>
<td style="border:1px solid black;">
[**MS16-041**](https://go.microsoft.com/fwlink/?linkid=746929)

</td>
<td style="border:1px solid black;">
[**MS16-044**](https://go.microsoft.com/fwlink/?linkid=747040)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**中度**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(4014661)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3145739)  
(重大)  
Microsoft .NET Framework 3.5  
(3142043)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3146706)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(4014661)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3145739)  
(重大)  
Microsoft .NET Framework 3.5  
(3142045)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3146706)  
(重要)

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
[**MS16-037**](https://go.microsoft.com/fwlink/?linkid=746891)

</td>
<td style="border:1px solid black;">
[**MS16-038**](https://go.microsoft.com/fwlink/?linkid=746894)

</td>
<td style="border:1px solid black;">
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-040**](https://go.microsoft.com/fwlink/?linkid=746897)

</td>
<td style="border:1px solid black;">
[**MS16-041**](https://go.microsoft.com/fwlink/?linkid=746929)

</td>
<td style="border:1px solid black;">
[**MS16-044**](https://go.microsoft.com/fwlink/?linkid=747040)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4014661)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3145739)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3146706)  
(重要)

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
[**MS16-037**](https://go.microsoft.com/fwlink/?linkid=746891)

</td>
<td style="border:1px solid black;">
[**MS16-038**](https://go.microsoft.com/fwlink/?linkid=746894)

</td>
<td style="border:1px solid black;">
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-040**](https://go.microsoft.com/fwlink/?linkid=746897)

</td>
<td style="border:1px solid black;">
[**MS16-041**](https://go.microsoft.com/fwlink/?linkid=746929)

</td>
<td style="border:1px solid black;">
[**MS16-044**](https://go.microsoft.com/fwlink/?linkid=747040)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(3147461)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3147461)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3147461)  
(重大)  
Microsoft .NET Framework 3.5  
(3147461)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3147461)  
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
(3147461)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3147461)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3147461)  
(重大)  
Microsoft .NET Framework 3.5  
(3147461)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3147461)  
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
(3147458)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3147458)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3147458)  
(重大)  
Microsoft .NET Framework 3.5  
(3147458)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3147458)  
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
(3147458)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3147458)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3147458)  
(重大)  
Microsoft .NET Framework 3.5  
(3147458)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3147458)  
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
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1703 版  
(4038788)  
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
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1703 版  
(4038788)  
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
<td style="border:1px solid black;" colspan="7">
**Server Core 安裝選項**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-037**](https://go.microsoft.com/fwlink/?linkid=746891)

</td>
<td style="border:1px solid black;">
[**MS16-038**](https://go.microsoft.com/fwlink/?linkid=746894)

</td>
<td style="border:1px solid black;">
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-040**](https://go.microsoft.com/fwlink/?linkid=746897)

</td>
<td style="border:1px solid black;">
[**MS16-041**](https://go.microsoft.com/fwlink/?linkid=746929)

</td>
<td style="border:1px solid black;">
[**MS16-044**](https://go.microsoft.com/fwlink/?linkid=747040)

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
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(3145739)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3146706)  
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
(3145739)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3146706)  
(重要)

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
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3145739)  
(重大)  
Microsoft .NET Framework 3.5.1  
(3142042)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6/4.6.1  
(3143693)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3146706)  
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
Windows Server 2012 (Server Core 安裝)  
(3145739)  
(重大)  
Microsoft .NET Framework 3.5  
(3142043)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3146706)  
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
Windows Server 2012 R2 (Server Core 安裝)  
(3145739)  
(重大)  
Microsoft .NET Framework 3.5  
(3142045)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3146706)  
(重要)

</td>
</tr>
</table>
 
**MS16-039 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，了解其他受影響的軟體。

### Windows 作業系統及元件 (表格 2 之 2)

 
<p></p>
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
[**MS16-045**](https://go.microsoft.com/fwlink/?linkid=733440)

</td>
<td style="border:1px solid black;">
[**MS16-046**](https://go.microsoft.com/fwlink/?linkid=746896)

</td>
<td style="border:1px solid black;">
[**MS16-047**](https://go.microsoft.com/fwlink/?linkid=746885)

</td>
<td style="border:1px solid black;">
[**MS16-048**](https://go.microsoft.com/fwlink/?linkid=746886)

</td>
<td style="border:1px solid black;">
[**MS16-049**](https://go.microsoft.com/fwlink/?linkid=746932)

</td>
<td style="border:1px solid black;">
[**MS16-050**](https://go.microsoft.com/fwlink/?linkid=785154)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3149090)  
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3149090)  
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
[**MS16-045**](https://go.microsoft.com/fwlink/?linkid=733440)

</td>
<td style="border:1px solid black;">
[**MS16-046**](https://go.microsoft.com/fwlink/?linkid=746896)

</td>
<td style="border:1px solid black;">
[**MS16-047**](https://go.microsoft.com/fwlink/?linkid=746885)

</td>
<td style="border:1px solid black;">
[**MS16-048**](https://go.microsoft.com/fwlink/?linkid=746886)

</td>
<td style="border:1px solid black;">
[**MS16-049**](https://go.microsoft.com/fwlink/?linkid=746932)

</td>
<td style="border:1px solid black;">
[**MS16-050**](https://go.microsoft.com/fwlink/?linkid=785154)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3149090)  
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
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3149090)  
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
(3149090)  
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
[**MS16-045**](https://go.microsoft.com/fwlink/?linkid=733440)

</td>
<td style="border:1px solid black;">
[**MS16-046**](https://go.microsoft.com/fwlink/?linkid=746896)

</td>
<td style="border:1px solid black;">
[**MS16-047**](https://go.microsoft.com/fwlink/?linkid=746885)

</td>
<td style="border:1px solid black;">
[**MS16-048**](https://go.microsoft.com/fwlink/?linkid=746886)

</td>
<td style="border:1px solid black;">
[**MS16-049**](https://go.microsoft.com/fwlink/?linkid=746932)

</td>
<td style="border:1px solid black;">
[**MS16-050**](https://go.microsoft.com/fwlink/?linkid=785154)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
適用於 32 位元系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3149090)  
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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3149090)  
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
[**MS16-045**](https://go.microsoft.com/fwlink/?linkid=733440)

</td>
<td style="border:1px solid black;">
[**MS16-046**](https://go.microsoft.com/fwlink/?linkid=746896)

</td>
<td style="border:1px solid black;">
[**MS16-047**](https://go.microsoft.com/fwlink/?linkid=746885)

</td>
<td style="border:1px solid black;">
[**MS16-048**](https://go.microsoft.com/fwlink/?linkid=746886)

</td>
<td style="border:1px solid black;">
[**MS16-049**](https://go.microsoft.com/fwlink/?linkid=746932)

</td>
<td style="border:1px solid black;">
[**MS16-050**](https://go.microsoft.com/fwlink/?linkid=785154)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3149090)  
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
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3149090)  
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
[**MS16-045**](https://go.microsoft.com/fwlink/?linkid=733440)

</td>
<td style="border:1px solid black;">
[**MS16-046**](https://go.microsoft.com/fwlink/?linkid=746896)

</td>
<td style="border:1px solid black;">
[**MS16-047**](https://go.microsoft.com/fwlink/?linkid=746885)

</td>
<td style="border:1px solid black;">
[**MS16-048**](https://go.microsoft.com/fwlink/?linkid=746886)

</td>
<td style="border:1px solid black;">
[**MS16-049**](https://go.microsoft.com/fwlink/?linkid=746932)

</td>
<td style="border:1px solid black;">
[**MS16-050**](https://go.microsoft.com/fwlink/?linkid=785154)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

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
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3149090)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3146723)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3135456)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3149090)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3146723)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
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
[**MS16-045**](https://go.microsoft.com/fwlink/?linkid=733440)

</td>
<td style="border:1px solid black;">
[**MS16-046**](https://go.microsoft.com/fwlink/?linkid=746896)

</td>
<td style="border:1px solid black;">
[**MS16-047**](https://go.microsoft.com/fwlink/?linkid=746885)

</td>
<td style="border:1px solid black;">
[**MS16-048**](https://go.microsoft.com/fwlink/?linkid=746886)

</td>
<td style="border:1px solid black;">
[**MS16-049**](https://go.microsoft.com/fwlink/?linkid=746932)

</td>
<td style="border:1px solid black;">
[**MS16-050**](https://go.microsoft.com/fwlink/?linkid=785154)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**中度**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3135456)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3149090)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3146723)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3135456)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3149090)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3146723)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
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
[**MS16-045**](https://go.microsoft.com/fwlink/?linkid=733440)

</td>
<td style="border:1px solid black;">
[**MS16-046**](https://go.microsoft.com/fwlink/?linkid=746896)

</td>
<td style="border:1px solid black;">
[**MS16-047**](https://go.microsoft.com/fwlink/?linkid=746885)

</td>
<td style="border:1px solid black;">
[**MS16-048**](https://go.microsoft.com/fwlink/?linkid=746886)

</td>
<td style="border:1px solid black;">
[**MS16-049**](https://go.microsoft.com/fwlink/?linkid=746932)

</td>
<td style="border:1px solid black;">
[**MS16-050**](https://go.microsoft.com/fwlink/?linkid=785154)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

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
不適用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3149090)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3146723)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
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
[**MS16-045**](https://go.microsoft.com/fwlink/?linkid=733440)

</td>
<td style="border:1px solid black;">
[**MS16-046**](https://go.microsoft.com/fwlink/?linkid=746896)

</td>
<td style="border:1px solid black;">
[**MS16-047**](https://go.microsoft.com/fwlink/?linkid=746885)

</td>
<td style="border:1px solid black;">
[**MS16-048**](https://go.microsoft.com/fwlink/?linkid=746886)

</td>
<td style="border:1px solid black;">
[**MS16-049**](https://go.microsoft.com/fwlink/?linkid=746932)

</td>
<td style="border:1px solid black;">
[**MS16-050**](https://go.microsoft.com/fwlink/?linkid=785154)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(3147461)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3147461)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3147461)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3147461)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3147461)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3147461)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3147461)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3147461)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3147461)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
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
(3147458)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3147458)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3147458)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3147458)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
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
(3147458)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3147458)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3147458)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3147458)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
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
[**MS16-045**](https://go.microsoft.com/fwlink/?linkid=733440)

</td>
<td style="border:1px solid black;">
[**MS16-046**](https://go.microsoft.com/fwlink/?linkid=746896)

</td>
<td style="border:1px solid black;">
[**MS16-047**](https://go.microsoft.com/fwlink/?linkid=746885)

</td>
<td style="border:1px solid black;">
[**MS16-048**](https://go.microsoft.com/fwlink/?linkid=746886)

</td>
<td style="border:1px solid black;">
[**MS16-049**](https://go.microsoft.com/fwlink/?linkid=746932)

</td>
<td style="border:1px solid black;">
[**MS16-050**](https://go.microsoft.com/fwlink/?linkid=785154)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3149090)  
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
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3149090)  
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
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)  
(3149090)  
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)  
(3135456)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)  
(3149090)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)  
(3146723)  
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
Windows Server 2012 R2  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)  
(3135456)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)  
(3149090)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)  
(3146723)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

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
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3114542)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 Service Pack 3  
(3114892)  
(重要)  
Microsoft Word 2007 Service Pack 3  
(3114983)  
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
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(3114566)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(3114990)  
(重大)  
Microsoft Excel 2010 Service Pack 2 (32 位元版本)  
(3114888)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 位元版本)  
(3114993)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3114566)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3114990)  
(重大)  
Microsoft Excel 2010 Service Pack 2 (64 位元版本)  
(3114888)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 位元版本)  
(3114993)  
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
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

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
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Microsoft Excel 2013 Service Pack 1 (32 位元版本)  
(3114947)  
(重要)  
Microsoft Word 2013 Service Pack 1 (32 位元版本)  
(3114937)  
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
Microsoft Excel 2013 Service Pack 1 (64 位元版本)  
(3114947)  
(重要)  
Microsoft Word 2013 Service Pack 1 (64 位元版本)  
(3114937)  
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
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

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
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Microsoft Excel 2013 RT Service Pack 1  
(3114947)  
(重要)  
Microsoft Word 2013 RT Service Pack 1  
(3114937)  
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
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (32 位元版本)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (32 位元版本)  
(3114964)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 位元版本)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (64 位元版本)  
(3114964)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office for Mac 2011**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Microsoft Word for Mac 2011  
(3154208)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2016 for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Microsoft Word 2016 for Mac  
(3142577)  
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
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(3114982)  
(重大)  
Microsoft Office 相容性套件 Service Pack 3  
(3114895)  
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
(3114898)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3114985)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3114987)  
(重大)

</td>
</tr>
</table>
 
**MS16-039 和 MS16-042 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，了解其他受影響的軟體。

### Microsoft Office Services 和 Web Apps

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (32 位元版本)

</td>
<td style="border:1px solid black;">
Excel Services  
(3114897)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 位元版本)

</td>
<td style="border:1px solid black;">
Excel Services  
(3114897)  
(重要)

</td>
</tr>
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
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Excel Services  
(3114871)  
(重要)  
Word Automation Services  
(3114988)  
(重大)

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
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3114927)  
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
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3114994)  
(重大)

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
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3114934)  
(重大)

</td>
</tr>
</table>
 
**MS16-042 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，了解其他受影響的軟體。

### Microsoft 通訊平台和軟體

 
<p></p>
<table style="border:1px solid black;">
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
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
商務用 Skype 2016 (32 位元版本)

</td>
<td style="border:1px solid black;">
商務用 Skype 2016 (32 位元版本)  
(3114960)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
商務用 Skype 基本版 2016 (32 位元版本)

</td>
<td style="border:1px solid black;">
商務用 Skype 基本版 2016 (32 位元版本)  
(3114960)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
商務用 Skype 2016 (64 位元版本)

</td>
<td style="border:1px solid black;">
商務用 Skype 2016 (64 位元版本)  
(3114960)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
商務用 Skype 基本版 2016 (64 位元版本)

</td>
<td style="border:1px solid black;">
商務用 Skype 基本版 2016 (64 位元版本)  
(3114960)  
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
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(3114944)  
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
(3114944)  
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
(3114944)  
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
(3114944)  
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
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 位元)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 位元)  
(3144427)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 位元)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 位元)  
(3144427)  
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
(3144428)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(系統管理員層級安裝)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(系統管理員層級安裝)  
(3144429)  
(重大)

</td>
</tr>
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
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console

</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console  
(3144432)  
(重大)

</td>
</tr>
</table>
 
**MS16-039 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，了解其他受影響的軟體。

偵測與部署工具及指南
--------------------

有幾項資源可協助系統管理員部署安全性更新。

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，查看是否遺漏安全性更新以及是否存在一般安全設定錯誤。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 可協助系統管理員發佈安全性更新。

應用程式相容性工具組隨附的 Update Compatibility Evaluator 元件可針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

如需上述工具以及其他可使用工具的詳細資訊，請參閱 [IT 專業人員的資訊安全工具](https://technet.microsoft.com/zh-tw/security/cc297183)。 

致謝
----

Microsoft 了解資訊安全業界所做的努力，其盡責地揭露弱點來協助我們保護客戶。請參閱[致謝](https://technet.microsoft.com/zh-tw/library/security/mt674627.aspx) (英文) 以取得詳細資訊。

其他資訊
--------

### Microsoft Windows 惡意軟體移除工具

針對每個月第二個星期二發行的公告，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 及下載中心發行更新版本的 Microsoft Windows 惡意軟體移除工具。不定期資訊安全公告發行不提供更新版本的 Microsoft Windows 惡意軟體移除工具。

### MU、WU 及 WSUS 上的非安全性更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [Microsoft 知識庫文章 894199](https://support.microsoft.com/zh-tw/kb/894199)：說明 Software Update Services 和 Windows Server Update Services 的內容變更。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](https://technet.microsoft.com/zh-tw/wsus/bb456965)。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的安全性保護，Microsoft 將在每月發行安全性更新之前，提前向重要安全性軟體提供者提供弱點資訊。安全性軟體提供者可利用此弱點資訊，透過其安全性軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](https://go.microsoft.com/fwlink/?linkid=215201) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

### 安全性策略與社群

**更新程式管理策略**

[更新管理資訊安全指南](https://go.microsoft.com/fwlink/?linkid=21168) (英文) 提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他資訊安全問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得，您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 映像檔的方式，取得本月份 Windows Update 提供的安全性更新。如需詳細資訊，請參閱 [Microsoft 知識庫文章 913086](https://support.microsoft.com/zh-tw/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全社群](https://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

### 支援

所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要了解您軟體版本的支援週期，請造訪 [Microsoft 支援週期網站](https://go.microsoft.com/fwlink/?linkid=21742)。

適用於 IT 專業人員的安全性解決方案：[TechNet 安全性疑難排解與支援](https://technet.microsoft.com/zh-tw/security/bb980617)

協助保護您執行 Windows 的電腦免於受到病毒和惡意程式碼攻擊：[病毒解決方案與資訊安全中心](https://support.microsoft.com/zh-tw/contactus/cu_sc_virsec_master)

您所在國家/地區的當地支援：[多語系支援](https://support.microsoft.com/zh-tw/common/international.aspx)

### 免責聲明

Microsoft 知識庫中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

### 修訂

-   V1.0 (2016 年 4 月 12 日)：公告摘要發行。
-   V1.1 (2016 年 4 月 13 日)：新增已知問題參考至 MS16-039 的「提要」表格。如需詳細資訊，請參閱 [Microsoft 知識庫文章 3148522](https://support.microsoft.com/zh-tw/kb/3148522)。新增已知問題參考至 MS16-042 的「提要」表格。如需詳細資訊，請參閱 [Microsoft 知識庫文章 3148775](https://support.microsoft.com/zh-tw/kb/3148775)。
-   V1.2 (2016 年 5 月 11 日)：新增已知問題參考至 MS16-044 的「提要」表格。如需詳細資訊，請參閱 [Microsoft 知識庫文章 3146706](https://support.microsoft.com/zh-tw/kb/3146706)。新增已知問題參考至 MS16-042 的「提要」表格。如需詳細資訊，請參閱 [Microsoft 知識庫文章 3146723](https://support.microsoft.com/zh-tw/kb/3146723)。
-   V2.0 (2016 年 6 月 14 日)：已為 MS16-039 修訂公告摘要，宣佈 Microsoft 已針對 Microsoft Lync 2010 和 Microsoft Lync 2010 Attendee 的受影響版本重新發行安全性更新 3144427。此重新發行可解決客戶在下載更新 3144427 時可能會遇到的問題。建議執行 Microsoft Lync 2010 的客戶安裝更新，以取得完整的保護，以免受到此弱點損害。如需詳細資訊，請參閱 [Microsoft 知識庫文章 3144427](https://support.microsoft.com/zh-tw/kb/3144427)。
-   V3.0 (2017 年 4 月 11 日)：已為 MS16-037 修訂公告摘要，宣告為 CVE-2016-0162 發行新的 Internet Explorer 累積更新 (4014661)。此更新為原先版本的追加更新，旨在徹底解決 CVE-2016-0162。Microsoft 建議執行受影響軟體的客戶安裝此安全性更新，以取得完整的保護，以免受到此公告所述的弱點損害。如需詳細資訊，請參閱 [Microsoft 知識庫文章 4014661](https://support.microsoft.com/zh-tw/kb/4014661)。
-   V4.0 (2017 年 9 月 12 日)：針對 MS16-039，已修訂「Windows 作業系統和元件受影響的軟體」表格，以包含 32 位元系統 Windows 10 1703 版和 x64 型系統 Windows 10 1703 版，因為它們也受到 CVE-2016-0165 的影響。Microsoft 建議執行 Windows 10 1703 版的客戶安裝更新 4038788，以取得保護，避免因為此弱點而受害。

*頁面產生時間：2017 年 9 月 6 日 13:50-07:00。*
