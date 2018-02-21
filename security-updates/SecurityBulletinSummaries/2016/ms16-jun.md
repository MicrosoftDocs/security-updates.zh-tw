---
TOCTitle: 'MS16-JUN'
Title: 2016 年 6 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms16-jun'
ms:contentKeyID: 73142190
ms:date: '06/27/2016'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms16-jun(v=Security.10)'
---



2016 年 6 月份 Microsoft 資訊安全公告摘要
=========================================

出版日期：2016 年 6 月 14 日 | 更新日期：2016 年 6 月 16 日

**版本：** 2.0

此公告摘要列出 2016 年 6 月份所發行的安全性公告。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://technet.microsoft.com/zh-tw/security/dd252948.aspx).。

Microsoft 也會提供資訊協助客戶排定每月資訊安全更新以及任何非安全性更新的優先順序，其中這些非安全性更新的發行日期與每月安全性更新的發行日期相同。請參閱**其他資訊**一節。

提要
----

下表摘要本月安全性公告，以嚴重性高低排序。

如需詳細資訊，請參閱下一節**受影響的軟體**。

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
<td style="border:1px solid black;"><strong>公告 識別碼</strong></td>
<td style="border:1px solid black;"><strong>公告標題與提要</strong></td>
<td style="border:1px solid black;"><strong>最高的嚴重性等級<br />
和弱點影響</strong></td>
<td style="border:1px solid black;"><strong>重新啟動需求</strong></td>
<td style="border:1px solid black;"><strong>已知<br />
問題</strong></td>
<td style="border:1px solid black;"><strong>受影響的軟體</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-063">MS16-063</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 累積安全性更新 (3163649)<br />
</strong>此安全性更新可解決 Internet Explorer 中的弱點。其中最嚴重的資訊安全風險，可能在使用者以 Internet Explorer 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用此弱點的攻擊者可取得與目前使用者相同的使用者權限。如果目前使用者是以管理使用者權限登入，攻擊者可控制受到影響的系統。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-068">MS16-068</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 的累積安全性更新 (3163656)<br />
</strong>此安全性更新可解決 Microsoft Edge 中的弱點。其中最嚴重的資訊安全風險，可能在使用者以 Microsoft Edge 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用此弱點的攻擊者可取得與目前使用者相同的使用者權限。在系統將帳戶設定為擁有較少使用者權限的客戶，相較於擁有管理使用者權限的使用者，受到影響較輕微。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-069">MS16-069</a></td>
<td style="border:1px solid black;"><strong>JScript 和 VBScript 的累積安全性更新 (3163640)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中 JScript 與 VBScript 指令碼引擎的弱點。如果使用者造訪蓄意製作的網站，這些弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者可取得與目前使用者相同的使用者權限。如果目前使用者是以管理使用者權限登入，成功利用這些弱點的攻擊者可控制受到影響的系統。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-070">MS16-070</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 的安全性更新 (3163610)<br />
</strong>此安全性更新可解決 Microsoft Office 中的弱點。如果使用者開啟蓄意製作的 Microsoft Office 檔案，最嚴重的資訊安全風險可能會允許遠端執行程式碼。成功利用此弱點的攻擊者可在目前使用者的內容中執行任意程式碼。在系統將帳戶設定為擁有較少使用者權限的客戶，相較於擁有管理使用者權限的使用者，受到影響較輕微。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office，<br />
Microsoft Office Services 和 Web Apps</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-071">MS16-071</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows DNS 伺服器的安全性更新 (3164065)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者傳送蓄意製作的要求至DNS 伺服器，此弱點可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-072">MS16-072</a></td>
<td style="border:1px solid black;"><strong>群組原則的安全性更新 (3163622)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者發動攔截式攻擊網域控制站與目標電腦上之間的流量，則這項弱點可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="http://support.microsoft.com/zh-tw/kb/3159398">3159398</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-073">MS16-073</a></td>
<td style="border:1px solid black;"><strong>Windows 核心模式驅動程式的安全性更新 (3164028)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者登入受影響的系統並執行蓄意製作的應用程式，則最嚴重的資訊安全風險可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-074">MS16-074</a></td>
<td style="border:1px solid black;"><strong>Microsoft 圖形元件的安全性更新 (3164036)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果使用者開啟蓄意製作的應用程式，則這些弱點中最嚴重者可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-075">MS16-075</a></td>
<td style="border:1px solid black;"><strong>Windows SMB Server (3164038) 的安全性更新<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者登入系統，並執行蓄意製作的應用程式，則這些資訊安全風險可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-076">MS16-076</a></td>
<td style="border:1px solid black;"><strong>Netlogon 的安全性更新 (3167691)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果在目標網路可存取網域控制站 (DC) 的攻擊者，執行蓄意製作的應用程式，以建立安全通道連至 DC 作為複製的網域控制站，則弱點可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-077">MS16-077</a></td>
<td style="border:1px solid black;"><strong>WPAD 的安全性更新 (3165191)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果 Web Proxy 自動探索 (WPAD) 協定在目標系統中使用易遭受攻擊的 Proxy 探索處理程序，則這些弱點可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-078">MS16-078</a></td>
<td style="border:1px solid black;"><strong>Windows Diagnostic Hub 的安全性更新 (3165479)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者登入受影響的系統，並執行蓄意製作的應用程式，則這項弱點可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-063">MS16-079</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange Server 的安全性更新 3160339)<br />
</strong>此安全性更新可解決 Microsoft Exchange Server 中的弱點。如果攻擊者傳送含有蓄意製作影像 URL 的 Outlook Web Access (OWA) 訊息，且訊息在沒有警告或篩選的情形下從攻擊者控制的 URL 載入，則最嚴重的弱點可能會導致資訊洩漏。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
資訊洩漏</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Exchange Server</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-080">MS16-080</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows PDF 的安全性更新 (3164302)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果使用者開啟蓄意製作的 PDF 檔案，較嚴重的資訊安全風險可能會允許遠端執行程式碼。成功利用此資訊安全風險的攻擊者可在目前使用者的內容中執行使用任意程式碼。不過，攻擊者無法強迫使用者開啟蓄意製作的 PDF 檔案。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-081">MS16-081</a></td>
<td style="border:1px solid black;"><strong>Active Directory 的安全性更新 (3160352)<br />
</strong>此安全性更新可解決 Active Directory 中的弱點。如果通過驗證的攻擊者建立多個電腦帳戶，這項弱點可能會阻斷服務。如果要利用此弱點，攻擊者必須擁有權限帳戶，可讓電腦聯結至網域。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
阻斷服務</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-082">MS16-082</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows 搜尋元件的安全性更新 (3165270)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者登入受影響的系統，並執行蓄意製作的應用程式，則這項弱點可能會允許阻斷服務。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
阻斷服務</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-083">MS16-083</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player 的安全性更新 (3167685)<br />
</strong>當安裝於所有受支援版本的Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1 和 Windows 10，此安全性更新可解決 Adobe Flash Player 中的弱點。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows<br />
Adobe Flash Player</td>
</tr>
</tbody>
</table>
 

弱點索引
--------

下表提供本月修正所各個弱點的評估。弱點先依公告識別碼排序，再依 CVE ID 排序。僅有在公告中嚴重性等級分為重大或重要的弱點列入本表。

**如何使用此表格？**

您可以運用此表格，針對您可能需要安裝的每一項安全性更新，瞭解資訊安全風險在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務 (DoS) 的可能性。檢視下列各項評估，依據您的設定排定本月的更新佈署優先順序。如需有關等級意義的詳細資訊，以及等級如何決定，請參閱 [Microsoft 弱點索引](http://technet.microsoft.com/zh-tw/security/cc998259)。

下方欄位「最新軟體版本」意指受影響軟體，「較舊軟體版本」意指受影響軟體所有較舊的支援版本，如公告中的「受影響的軟體」或「不受影響的軟體」表格裡所示。

 
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
**最新軟體版本  
的弱點評估**

</td>
<td style="border:1px solid black;">
**最新軟體版本  
的弱點評估**

</td>
<td style="border:1px solid black;">
**阻斷服務  
弱點評估**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-063：Internet Explorer 累積安全性更新 (3163649)**](https://technet.microsoft.com/zh-tw/library/security/ms16-063)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0199](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0199)

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
[CVE-2016-0200](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0200)

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
[CVE-2016-3202](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3202)

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
[CVE-2016-3205](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3205)

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
[CVE-2016-3206](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3206)

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
[CVE-2016-3207](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3207)

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
[CVE-2016-3210](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3210)

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
[CVE-2016-3211](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3211)

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
[CVE-2016-3212](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3212)

</td>
<td style="border:1px solid black;">
Internet Explorer XSS Filter 弱點

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
[CVE-2016-3213](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3213)

</td>
<td style="border:1px solid black;">
WPAD 權限提高弱點

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
[**MS16-068：Microsoft Edge 的累積安全性更新 (3163656)**](https://technet.microsoft.com/zh-tw/library/security/ms16-068)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3198](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3198)

</td>
<td style="border:1px solid black;">
Microsoft Edge 資訊安全功能略過

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
[CVE-2016-3199](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3199)

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
[CVE-2016-3201](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3201)

</td>
<td style="border:1px solid black;">
Windows PDF 資訊洩漏弱點

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
[CVE-2016-3202](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3202)

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
[CVE-2016-3203](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3203)

</td>
<td style="border:1px solid black;">
Windows PDF 遠端執行程式碼弱點

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
[CVE-2016-3214](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3214)

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
[CVE-2016-3215](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3215)

</td>
<td style="border:1px solid black;">
Windows PDF 資訊洩漏弱點

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
[CVE-2016-3222](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3222)

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
<td style="border:1px solid black;" colspan="5">
[**MS16-069：JScript 和 VBScript 的累積安全性更新 (3163640)**](https://technet.microsoft.com/zh-tw/library/security/ms16-069)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3205](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3205)

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
[CVE-2016-3206](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3206)

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
[CVE-2016-3207](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3207)

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
<td style="border:1px solid black;" colspan="5">
[**MS16-070：Microsoft Office 的安全性更新 (3163610)**](https://technet.microsoft.com/zh-tw/library/security/ms16-070)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0025](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0025)

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
[CVE-2016-3233](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3233)

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
[CVE-2016-3234](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3234)

</td>
<td style="border:1px solid black;">
Microsoft Office 資訊洩漏弱點

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
[CVE-2016-3235](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3235)

</td>
<td style="border:1px solid black;">
Microsoft Office OLE DLL Side Loading 弱點

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
[**MS16-071：Microsoft Windows DNS 伺服器的安全性更新 (3164065)**](https://technet.microsoft.com/zh-tw/library/security/ms16-071)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3227](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3227)

</td>
<td style="border:1px solid black;">
Windows DNS 伺服器釋放後使用弱點

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
[**MS16-072：群組原則的安全性更新 (3163622)**](https://technet.microsoft.com/zh-tw/library/security/ms16-072)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3223](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3223)

</td>
<td style="border:1px solid black;">
群組原則權限提高弱點

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
[**MS16-073：Windows 核心模式驅動程式的安全性更新 (3164028)**](https://technet.microsoft.com/zh-tw/library/security/ms16-073)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3218](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3218)

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
[CVE-2016-3221](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3221)

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
[CVE-2016-3232](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3232)

</td>
<td style="border:1px solid black;">
Windows Virtual PCI 資訊洩漏弱點

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
[**MS16-074：Microsoft 圖形元件的安全性更新 (3164036)**](https://technet.microsoft.com/zh-tw/library/security/ms16-074)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3216](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3216)

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
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3219](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3219)

</td>
<td style="border:1px solid black;">
Win32k 權限提高弱點

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
[CVE-2016-3220](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3220)

</td>
<td style="border:1px solid black;">
ATMFD.DLL 權限提高弱點

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
[**MS16-075：Windows SMB Server (3164038) 的安全性更新**](https://technet.microsoft.com/zh-tw/library/security/ms16-075)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3225](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3225)

</td>
<td style="border:1px solid black;">
Windows SMB Server 權限提高弱點

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
[**MS16-076：Netlogon 的安全性更新 (3167691)**](https://technet.microsoft.com/zh-tw/library/security/ms16-076)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3228](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3228)

</td>
<td style="border:1px solid black;">
Windows Netlogon 記憶體損毀遠端執行程式碼弱點

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
[**MS16-077：WPAD 的安全性更新 (3165191)**](https://technet.microsoft.com/zh-tw/library/security/ms16-077)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3213](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3213)

</td>
<td style="border:1px solid black;">
Windows WPAD 權限提高弱點

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
[CVE-2016-3236](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3236)

</td>
<td style="border:1px solid black;">
Windows WPAD Proxy 探索處理程序權限提高弱點

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
[**MS16-078：Windows Diagnostic Hub 的安全性更新 (3165479)**](https://technet.microsoft.com/zh-tw/library/security/ms16-078)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3231](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3231)

</td>
<td style="border:1px solid black;">
Windows Diagnostics Hub 權限提高弱點

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
[**MS16-079：Microsoft Exchange Server 的安全性更新 3160339)**](https://technet.microsoft.com/zh-tw/library/security/ms16-063)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0028](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0028)

</td>
<td style="border:1px solid black;">
Microsoft Exchange 資訊洩漏弱點

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
[**MS16-080：Microsoft Windows PDF 的安全性更新 (3164302)**](https://technet.microsoft.com/zh-tw/library/security/ms16-080)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3201](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3201)

</td>
<td style="border:1px solid black;">
Windows PDF 資訊洩漏弱點

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
[CVE-2016-3203](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3203)

</td>
<td style="border:1px solid black;">
Windows PDF 遠端執行程式碼弱點

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
[CVE-2016-3215](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3215)

</td>
<td style="border:1px solid black;">
Windows PDF 資訊洩漏弱點

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
[**MS16-081：Active Directory 的安全性更新 (3160352)**](https://technet.microsoft.com/zh-tw/library/security/ms16-081)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3226](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3226)

</td>
<td style="border:1px solid black;">
Active Directory 阻斷服務弱點

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS16-082：Microsoft Windows 搜尋元件的安全性更新 (3165270)**](https://technet.microsoft.com/zh-tw/library/security/ms16-067)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3230](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3230)

</td>
<td style="border:1px solid black;">
Windows 搜尋元件阻斷服務弱點

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS16-083：Adobe Flash Player 的安全性更新 (3167685)**](https://technet.microsoft.com/zh-tw/library/security/ms16-083)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-18](https://helpx.adobe.com/security/tw/products/flash-player/apsb16-18.html)

</td>
<td style="border:1px solid black;">
請參閱[Adobe 資訊安全公告 APSB16-18](https://helpx.adobe.com/security/tw/products/flash-player/apsb16-18.html) 了解弱點嚴重性以及更新優先順序等級。

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

請用這些表格來瞭解可能需要安裝的安全性更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的安全性更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。

**注意**一項弱點，可能需要安裝數個安全性更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。

 

### Windows 作業系統及元件 (表格 1 之 2)

 
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
[**MS16-063**](https://technet.microsoft.com/zh-tw/library/security/ms16-063)

</td>
<td style="border:1px solid black;">
[**MS16-068**](https://technet.microsoft.com/zh-tw/library/security/ms16-068)

</td>
<td style="border:1px solid black;">
[**MS16-069**](https://technet.microsoft.com/zh-tw/library/security/ms16-069)

</td>
<td style="border:1px solid black;">
[**MS16-071**](https://technet.microsoft.com/zh-tw/library/security/ms16-071)

</td>
<td style="border:1px solid black;">
[**MS16-072**](https://technet.microsoft.com/zh-tw/library/security/ms16-072)

</td>
<td style="border:1px solid black;">
[**MS16-073**](https://technet.microsoft.com/zh-tw/library/security/ms16-073)

</td>
<td style="border:1px solid black;">
[**MS16-074**](https://technet.microsoft.com/zh-tw/library/security/ms16-074)

</td>
<td style="border:1px solid black;">
[**MS16-075**](https://technet.microsoft.com/zh-tw/library/security/ms16-075)

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
Internet Explorer 9  
(3160005)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158364)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3164033)  
(重要)  
Windows Vista Service Pack 2  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3161561)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3160005)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158364)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3164033)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3161561)  
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
[**MS16-063**](https://technet.microsoft.com/zh-tw/library/security/ms16-063)

</td>
<td style="border:1px solid black;">
[**MS16-068**](https://technet.microsoft.com/zh-tw/library/security/ms16-068)

</td>
<td style="border:1px solid black;">
[**MS16-069**](https://technet.microsoft.com/zh-tw/library/security/ms16-069)

</td>
<td style="border:1px solid black;">
[**MS16-071**](https://technet.microsoft.com/zh-tw/library/security/ms16-071)

</td>
<td style="border:1px solid black;">
[**MS16-072**](https://technet.microsoft.com/zh-tw/library/security/ms16-072)

</td>
<td style="border:1px solid black;">
[**MS16-073**](https://technet.microsoft.com/zh-tw/library/security/ms16-073)

</td>
<td style="border:1px solid black;">
[**MS16-074**](https://technet.microsoft.com/zh-tw/library/security/ms16-074)

</td>
<td style="border:1px solid black;">
[**MS16-075**](https://technet.microsoft.com/zh-tw/library/security/ms16-075)

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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3160005)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158364)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3164033)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3161561)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3160005)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158364)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 Service Pack 2  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 Service Pack 2  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 Service Pack 2  
(3164033)  
(重要)  
適用於 64 位元系統的 Windows Server 2008 Service Pack 2  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 Service Pack 2  
(3161561)  
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
VBScript 5.7  
(3158364)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3164033)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3161561)  
(重要)

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
[**MS16-063**](https://technet.microsoft.com/zh-tw/library/security/ms16-063)

</td>
<td style="border:1px solid black;">
[**MS16-068**](https://technet.microsoft.com/zh-tw/library/security/ms16-068)

</td>
<td style="border:1px solid black;">
[**MS16-069**](https://technet.microsoft.com/zh-tw/library/security/ms16-069)

</td>
<td style="border:1px solid black;">
[**MS16-071**](https://technet.microsoft.com/zh-tw/library/security/ms16-071)

</td>
<td style="border:1px solid black;">
[**MS16-072**](https://technet.microsoft.com/zh-tw/library/security/ms16-072)

</td>
<td style="border:1px solid black;">
[**MS16-073**](https://technet.microsoft.com/zh-tw/library/security/ms16-073)

</td>
<td style="border:1px solid black;">
[**MS16-074**](https://technet.microsoft.com/zh-tw/library/security/ms16-074)

</td>
<td style="border:1px solid black;">
[**MS16-075**](https://technet.microsoft.com/zh-tw/library/security/ms16-075)

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
適用於 32 位元系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3160005)  
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
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3164033)  
(重要)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3161561)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3160005)  
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
適用於 64 位元系統的 Windows 7 Service Pack 1  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 7 Service Pack 1  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 7 Service Pack 1  
(3164033)  
(重要)  
適用於 64 位元系統的 Windows 7 Service Pack 1  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 7 Service Pack 1  
(3161561)  
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
[**MS16-063**](https://technet.microsoft.com/zh-tw/library/security/ms16-063)

</td>
<td style="border:1px solid black;">
[**MS16-068**](https://technet.microsoft.com/zh-tw/library/security/ms16-068)

</td>
<td style="border:1px solid black;">
[**MS16-069**](https://technet.microsoft.com/zh-tw/library/security/ms16-069)

</td>
<td style="border:1px solid black;">
[**MS16-071**](https://technet.microsoft.com/zh-tw/library/security/ms16-071)

</td>
<td style="border:1px solid black;">
[**MS16-072**](https://technet.microsoft.com/zh-tw/library/security/ms16-072)

</td>
<td style="border:1px solid black;">
[**MS16-073**](https://technet.microsoft.com/zh-tw/library/security/ms16-073)

</td>
<td style="border:1px solid black;">
[**MS16-074**](https://technet.microsoft.com/zh-tw/library/security/ms16-074)

</td>
<td style="border:1px solid black;">
[**MS16-075**](https://technet.microsoft.com/zh-tw/library/security/ms16-075)

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
適用於 64 位元系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3160005)  
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
適用於 64 位元系統的 Windows Server 2008 R2 Service Pack 1  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 R2 Service Pack 1  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 R2 Service Pack 1  
(3164033)  
(重要)  
適用於 64 位元系統的 Windows Server 2008 R2 Service Pack 1  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 R2 Service Pack 1  
(3161561)  
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
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3164033)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3161561)  
(重要)

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
[**MS16-063**](https://technet.microsoft.com/zh-tw/library/security/ms16-063)

</td>
<td style="border:1px solid black;">
[**MS16-068**](https://technet.microsoft.com/zh-tw/library/security/ms16-068)

</td>
<td style="border:1px solid black;">
[**MS16-069**](https://technet.microsoft.com/zh-tw/library/security/ms16-069)

</td>
<td style="border:1px solid black;">
[**MS16-071**](https://technet.microsoft.com/zh-tw/library/security/ms16-071)

</td>
<td style="border:1px solid black;">
[**MS16-072**](https://technet.microsoft.com/zh-tw/library/security/ms16-072)

</td>
<td style="border:1px solid black;">
[**MS16-073**](https://technet.microsoft.com/zh-tw/library/security/ms16-073)

</td>
<td style="border:1px solid black;">
[**MS16-074**](https://technet.microsoft.com/zh-tw/library/security/ms16-074)

</td>
<td style="border:1px solid black;">
[**MS16-075**](https://technet.microsoft.com/zh-tw/library/security/ms16-075)

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
適用於 32 位元系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3160005)  
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
適用於 32 位元系統的 Windows 8.1  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3164033)  
(重要)  
適用於 32 位元系統的 Windows 8.1  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3161561)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3160005)  
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
適用於 64 位元系統的 Windows 8.1  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 8.1  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 8.1  
(3164033)  
(重要)  
適用於 64 位元系統的 Windows 8.1  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 8.1  
(3161561)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-063**](https://technet.microsoft.com/zh-tw/library/security/ms16-063)

</td>
<td style="border:1px solid black;">
[**MS16-068**](https://technet.microsoft.com/zh-tw/library/security/ms16-068)

</td>
<td style="border:1px solid black;">
[**MS16-069**](https://technet.microsoft.com/zh-tw/library/security/ms16-069)

</td>
<td style="border:1px solid black;">
[**MS16-071**](https://technet.microsoft.com/zh-tw/library/security/ms16-071)

</td>
<td style="border:1px solid black;">
[**MS16-072**](https://technet.microsoft.com/zh-tw/library/security/ms16-072)

</td>
<td style="border:1px solid black;">
[**MS16-073**](https://technet.microsoft.com/zh-tw/library/security/ms16-073)

</td>
<td style="border:1px solid black;">
[**MS16-074**](https://technet.microsoft.com/zh-tw/library/security/ms16-074)

</td>
<td style="border:1px solid black;">
[**MS16-075**](https://technet.microsoft.com/zh-tw/library/security/ms16-075)

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
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3160005)  
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
(3161951)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3161664)  
(重要)  
Windows Server 2012  
(3164294)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3164033)  
(重要)  
Windows Server 2012  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3161561)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3160005)  
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
(3161951)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3161664)  
(重要)  
Windows Server 2012 R2  
(3164294)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3164033)  
(重要)  
Windows Server 2012 R2  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3161561)  
(重要)

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
[**MS16-063**](https://technet.microsoft.com/zh-tw/library/security/ms16-063)

</td>
<td style="border:1px solid black;">
[**MS16-068**](https://technet.microsoft.com/zh-tw/library/security/ms16-068)

</td>
<td style="border:1px solid black;">
[**MS16-069**](https://technet.microsoft.com/zh-tw/library/security/ms16-069)

</td>
<td style="border:1px solid black;">
[**MS16-071**](https://technet.microsoft.com/zh-tw/library/security/ms16-071)

</td>
<td style="border:1px solid black;">
[**MS16-072**](https://technet.microsoft.com/zh-tw/library/security/ms16-072)

</td>
<td style="border:1px solid black;">
[**MS16-073**](https://technet.microsoft.com/zh-tw/library/security/ms16-073)

</td>
<td style="border:1px solid black;">
[**MS16-074**](https://technet.microsoft.com/zh-tw/library/security/ms16-074)

</td>
<td style="border:1px solid black;">
[**MS16-075**](https://technet.microsoft.com/zh-tw/library/security/ms16-075)

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
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3160005)  
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
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3164033)  
(重要)  
Windows RT 8.1  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3161561)  
(重要)

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
[**MS16-063**](https://technet.microsoft.com/zh-tw/library/security/ms16-063)

</td>
<td style="border:1px solid black;">
[**MS16-068**](https://technet.microsoft.com/zh-tw/library/security/ms16-068)

</td>
<td style="border:1px solid black;">
[**MS16-069**](https://technet.microsoft.com/zh-tw/library/security/ms16-069)

</td>
<td style="border:1px solid black;">
[**MS16-071**](https://technet.microsoft.com/zh-tw/library/security/ms16-071)

</td>
<td style="border:1px solid black;">
[**MS16-072**](https://technet.microsoft.com/zh-tw/library/security/ms16-072)

</td>
<td style="border:1px solid black;">
[**MS16-073**](https://technet.microsoft.com/zh-tw/library/security/ms16-073)

</td>
<td style="border:1px solid black;">
[**MS16-074**](https://technet.microsoft.com/zh-tw/library/security/ms16-074)

</td>
<td style="border:1px solid black;">
[**MS16-075**](https://technet.microsoft.com/zh-tw/library/security/ms16-075)

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
適用於 32 位元系統的 Windows 10

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3163017)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3163017)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3163017)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 10

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3163017)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3163017)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 10  
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 10  
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 10  
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 10  
(3163017)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3163018)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3163018)  
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
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3163018)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3163018)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3163018)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 10 1511 版  
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 10 1511 版  
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 10 1511 版  
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 10 1511 版  
(3163018)  
(重要)

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
[**MS16-063**](https://technet.microsoft.com/zh-tw/library/security/ms16-063)

</td>
<td style="border:1px solid black;">
[**MS16-068**](https://technet.microsoft.com/zh-tw/library/security/ms16-068)

</td>
<td style="border:1px solid black;">
[**MS16-069**](https://technet.microsoft.com/zh-tw/library/security/ms16-069)

</td>
<td style="border:1px solid black;">
[**MS16-071**](https://technet.microsoft.com/zh-tw/library/security/ms16-071)

</td>
<td style="border:1px solid black;">
[**MS16-072**](https://technet.microsoft.com/zh-tw/library/security/ms16-072)

</td>
<td style="border:1px solid black;">
[**MS16-073**](https://technet.microsoft.com/zh-tw/library/security/ms16-073)

</td>
<td style="border:1px solid black;">
[**MS16-074**](https://technet.microsoft.com/zh-tw/library/security/ms16-074)

</td>
<td style="border:1px solid black;">
[**MS16-075**](https://technet.microsoft.com/zh-tw/library/security/ms16-075)

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
(3158364)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2(Server Core 安裝)  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2(Server Core 安裝)  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2(Server Core 安裝)  
(3164033)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2(Server Core 安裝)  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2(Server Core 安裝)  
(3161561)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 Service Pack 2  
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
(3158364)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3164033)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3161561)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
JScript 5.8 與 VBScript 5.8  
(3158363)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3164033)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3161561)  
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
Windows Server 2012(Server Core 安裝)  
(3161951)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 安裝)  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 安裝)  
(3161664)  
(重要)  
Windows Server 2012(Server Core 安裝)  
(3164294)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 安裝)  
(3164033)  
(重要)  
Windows Server 2012(Server Core 安裝)  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 安裝)  
(3161561)  
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
Windows Server 2012 R2(Server Core 安裝)  
(3161951)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 安裝)  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 安裝)  
(3161664)  
(重要)  
Windows Server 2012 R2(Server Core 安裝)  
(3164294)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 安裝)  
(3164033)  
(重要)  
Windows Server 2012 R2(Server Core 安裝)  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 安裝)  
(3161561)  
(重要)

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
[**MS16-076**](https://technet.microsoft.com/zh-tw/library/security/ms16-076)

</td>
<td style="border:1px solid black;">
[**MS16-077**](https://technet.microsoft.com/zh-tw/library/security/ms16-077)

</td>
<td style="border:1px solid black;">
[**MS16-078**](https://technet.microsoft.com/zh-tw/library/security/ms16-078)

</td>
<td style="border:1px solid black;">
[**MS16-080**](https://technet.microsoft.com/zh-tw/library/security/ms16-080)

</td>
<td style="border:1px solid black;">
[**MS16-081**](https://technet.microsoft.com/zh-tw/library/security/ms16-081)

</td>
<td style="border:1px solid black;">
[**MS16-082**](https://technet.microsoft.com/zh-tw/library/security/ms16-082)

</td>
<td style="border:1px solid black;">
[**MS16-083**](https://technet.microsoft.com/zh-tw/library/security/ms16-083)

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
Windows Vista Service Pack 2  
(3161949)  
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
Windows Vista x64 Edition Service Pack 2  
(3161949)  
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
[**MS16-076**](https://technet.microsoft.com/zh-tw/library/security/ms16-076)

</td>
<td style="border:1px solid black;">
[**MS16-077**](https://technet.microsoft.com/zh-tw/library/security/ms16-077)

</td>
<td style="border:1px solid black;">
[**MS16-078**](https://technet.microsoft.com/zh-tw/library/security/ms16-078)

</td>
<td style="border:1px solid black;">
[**MS16-080**](https://technet.microsoft.com/zh-tw/library/security/ms16-080)

</td>
<td style="border:1px solid black;">
[**MS16-081**](https://technet.microsoft.com/zh-tw/library/security/ms16-081)

</td>
<td style="border:1px solid black;">
[**MS16-082**](https://technet.microsoft.com/zh-tw/library/security/ms16-082)

</td>
<td style="border:1px solid black;">
[**MS16-083**](https://technet.microsoft.com/zh-tw/library/security/ms16-083)

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
**None**

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
**None**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3161561)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3161949)  
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
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 Service Pack 2  
(3161561)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 Service Pack 2  
(3161949)  
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
(3161561)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3161949)  
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
[**MS16-076**](https://technet.microsoft.com/zh-tw/library/security/ms16-076)

</td>
<td style="border:1px solid black;">
[**MS16-077**](https://technet.microsoft.com/zh-tw/library/security/ms16-077)

</td>
<td style="border:1px solid black;">
[**MS16-078**](https://technet.microsoft.com/zh-tw/library/security/ms16-078)

</td>
<td style="border:1px solid black;">
[**MS16-080**](https://technet.microsoft.com/zh-tw/library/security/ms16-080)

</td>
<td style="border:1px solid black;">
[**MS16-081**](https://technet.microsoft.com/zh-tw/library/security/ms16-081)

</td>
<td style="border:1px solid black;">
[**MS16-082**](https://technet.microsoft.com/zh-tw/library/security/ms16-082)

</td>
<td style="border:1px solid black;">
[**MS16-083**](https://technet.microsoft.com/zh-tw/library/security/ms16-083)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**None**

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
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3161949)  
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
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3161958)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 7 Service Pack 1  
(3161949)  
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
適用於 64 位元系統的 Windows 7 Service Pack 1  
(3161958)  
(重要)

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
[**MS16-076**](https://technet.microsoft.com/zh-tw/library/security/ms16-076)

</td>
<td style="border:1px solid black;">
[**MS16-077**](https://technet.microsoft.com/zh-tw/library/security/ms16-077)

</td>
<td style="border:1px solid black;">
[**MS16-078**](https://technet.microsoft.com/zh-tw/library/security/ms16-078)

</td>
<td style="border:1px solid black;">
[**MS16-080**](https://technet.microsoft.com/zh-tw/library/security/ms16-080)

</td>
<td style="border:1px solid black;">
[**MS16-081**](https://technet.microsoft.com/zh-tw/library/security/ms16-081)

</td>
<td style="border:1px solid black;">
[**MS16-082**](https://technet.microsoft.com/zh-tw/library/security/ms16-082)

</td>
<td style="border:1px solid black;">
[**MS16-083**](https://technet.microsoft.com/zh-tw/library/security/ms16-083)

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
**None**

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**None**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 R2 Service Pack 1  
(3161561)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 R2 Service Pack 1  
(3161949)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 R2 Service Pack 1  
(3160352)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 R2 Service Pack 1  
(3161958)  
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
(3161561)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3161949)  
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
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3161958)  
(重要)

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
[**MS16-076**](https://technet.microsoft.com/zh-tw/library/security/ms16-076)

</td>
<td style="border:1px solid black;">
[**MS16-077**](https://technet.microsoft.com/zh-tw/library/security/ms16-077)

</td>
<td style="border:1px solid black;">
[**MS16-078**](https://technet.microsoft.com/zh-tw/library/security/ms16-078)

</td>
<td style="border:1px solid black;">
[**MS16-080**](https://technet.microsoft.com/zh-tw/library/security/ms16-080)

</td>
<td style="border:1px solid black;">
[**MS16-081**](https://technet.microsoft.com/zh-tw/library/security/ms16-081)

</td>
<td style="border:1px solid black;">
[**MS16-082**](https://technet.microsoft.com/zh-tw/library/security/ms16-082)

</td>
<td style="border:1px solid black;">
[**MS16-083**](https://technet.microsoft.com/zh-tw/library/security/ms16-083)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**None**

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
(3161949)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3157569)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3161958)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 8.1  
(3161949)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 8.1  
(3157569)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 8.1  
(3161958)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-076**](https://technet.microsoft.com/zh-tw/library/security/ms16-076)

</td>
<td style="border:1px solid black;">
[**MS16-077**](https://technet.microsoft.com/zh-tw/library/security/ms16-077)

</td>
<td style="border:1px solid black;">
[**MS16-078**](https://technet.microsoft.com/zh-tw/library/security/ms16-078)

</td>
<td style="border:1px solid black;">
[**MS16-080**](https://technet.microsoft.com/zh-tw/library/security/ms16-080)

</td>
<td style="border:1px solid black;">
[**MS16-081**](https://technet.microsoft.com/zh-tw/library/security/ms16-081)

</td>
<td style="border:1px solid black;">
[**MS16-082**](https://technet.microsoft.com/zh-tw/library/security/ms16-082)

</td>
<td style="border:1px solid black;">
[**MS16-083**](https://technet.microsoft.com/zh-tw/library/security/ms16-083)

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
**None**

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
Windows Server 2012  
(3161561)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3161949)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3157569)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3160352)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3161958)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3162343)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3161949)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3157569)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3160352)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3161958)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
(中度)

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
[**MS16-076**](https://technet.microsoft.com/zh-tw/library/security/ms16-076)

</td>
<td style="border:1px solid black;">
[**MS16-077**](https://technet.microsoft.com/zh-tw/library/security/ms16-077)

</td>
<td style="border:1px solid black;">
[**MS16-078**](https://technet.microsoft.com/zh-tw/library/security/ms16-078)

</td>
<td style="border:1px solid black;">
[**MS16-080**](https://technet.microsoft.com/zh-tw/library/security/ms16-080)

</td>
<td style="border:1px solid black;">
[**MS16-081**](https://technet.microsoft.com/zh-tw/library/security/ms16-081)

</td>
<td style="border:1px solid black;">
[**MS16-082**](https://technet.microsoft.com/zh-tw/library/security/ms16-082)

</td>
<td style="border:1px solid black;">
[**MS16-083**](https://technet.microsoft.com/zh-tw/library/security/ms16-083)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
**None**

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
(3161949)  
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
Windows RT 8.1  
(3161958)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
(重大)

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
[**MS16-076**](https://technet.microsoft.com/zh-tw/library/security/ms16-076)

</td>
<td style="border:1px solid black;">
[**MS16-077**](https://technet.microsoft.com/zh-tw/library/security/ms16-077)

</td>
<td style="border:1px solid black;">
[**MS16-078**](https://technet.microsoft.com/zh-tw/library/security/ms16-078)

</td>
<td style="border:1px solid black;">
[**MS16-080**](https://technet.microsoft.com/zh-tw/library/security/ms16-080)

</td>
<td style="border:1px solid black;">
[**MS16-081**](https://technet.microsoft.com/zh-tw/library/security/ms16-081)

</td>
<td style="border:1px solid black;">
[**MS16-082**](https://technet.microsoft.com/zh-tw/library/security/ms16-082)

</td>
<td style="border:1px solid black;">
[**MS16-083**](https://technet.microsoft.com/zh-tw/library/security/ms16-083)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
**None**

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
**None**

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
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 10

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 10  
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 10  
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 10  
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 10  
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
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
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 10 1511 版  
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 10 1511 版  
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 10 1511 版  
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 10 1511 版  
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
(重大)

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
[**MS16-076**](https://technet.microsoft.com/zh-tw/library/security/ms16-076)

</td>
<td style="border:1px solid black;">
[**MS16-077**](https://technet.microsoft.com/zh-tw/library/security/ms16-077)

</td>
<td style="border:1px solid black;">
[**MS16-078**](https://technet.microsoft.com/zh-tw/library/security/ms16-078)

</td>
<td style="border:1px solid black;">
[**MS16-080**](https://technet.microsoft.com/zh-tw/library/security/ms16-080)

</td>
<td style="border:1px solid black;">
[**MS16-081**](https://technet.microsoft.com/zh-tw/library/security/ms16-081)

</td>
<td style="border:1px solid black;">
[**MS16-082**](https://technet.microsoft.com/zh-tw/library/security/ms16-082)

</td>
<td style="border:1px solid black;">
[**MS16-083**](https://technet.microsoft.com/zh-tw/library/security/ms16-083)

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
**None**

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**None**

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
(3161949)  
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
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3161949)  
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
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)  
(3161949)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)  
(3160352)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)  
(3161958)  
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
Windows Server 2012  
(Server Core 安裝)  
(3161561)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)  
(3161949)  
(重要)

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
(3160352)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)  
(3161958)  
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
Windows Server 2012 R2  
(Server Core 安裝)  
(3162343)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)  
(3161949)  
(重要)

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
(3160352)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)  
(3161958)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
</table>
 
 

### Microsoft Office 套裝軟體

 
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
[**MS16-070**](https://technet.microsoft.com/zh-tw/library/security/ms16-070)

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
Microsoft Excel 2007 Service Pack 3  
(3115107)  
(重要)  
Microsoft Visio 2007 Service Pack 3  
(3114740)  
(重要)  
Microsoft Word 2007 Service Pack 3  
(3115195)  
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
[**MS16-070**](https://technet.microsoft.com/zh-tw/library/security/ms16-070)

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
(3115198)  
(重大)  
Microsoft Excel 2010 Service Pack 2 (32 位元版本)  
(3115130)  
(重要)  
Microsoft Visio 2010 Service Pack 2 (32 位元版本)  
(3114872)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 位元版本)  
(3115243)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3115198)  
(重大)  
Microsoft Excel 2010 Service Pack 2 (64 位元版本)  
(3115130)  
(重要)  
Microsoft Visio 2010 Service Pack 2 (64 位元版本)  
(3114872)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 位元版本)  
(3115243)  
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
[**MS16-070**](https://technet.microsoft.com/zh-tw/library/security/ms16-070)

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
Microsoft Visio 2013 Service Pack 1 (32 位元版本)  
(3115020)  
(重要)  
Microsoft Word 2013 Service Pack 1 (32 位元版本)  
(3115173)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Visio 2013 Service Pack 1 (64 位元版本)  
(3115020)  
(重要)  
Microsoft Word 2013 Service Pack 1 (64 位元版本)  
(3115173)  
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
[**MS16-070**](https://technet.microsoft.com/zh-tw/library/security/ms16-070)

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
Microsoft Word 2013 RT Service Pack 1  
(3115173)  
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
[**MS16-070**](https://technet.microsoft.com/zh-tw/library/security/ms16-070)

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
Microsoft Word 2016 (32 位元版本)：

</td>
<td style="border:1px solid black;">
Microsoft Word 2016 (32 位元版本)：  
(3115144)  
(重要)  
Microsoft Visio 2016 (32 位元版本)  
(3115041)  
(重要)  
Microsoft Word 2016 (32 位元版本)  
(3115182)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word 2016 (64 位元版本)：

</td>
<td style="border:1px solid black;">
Microsoft Word 2016 (64 位元版本)：  
(3115144)  
(重要)  
Microsoft Visio 2016 (64 位元版本)  
(3115041)  
(重要)  
Microsoft Word 2016 (64 位元版本)  
(3115182)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office for Mac 2011 的系統需求**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-070**](https://technet.microsoft.com/zh-tw/library/security/ms16-070)

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
Microsoft Office for Mac 2011 的系統需求

</td>
<td style="border:1px solid black;">
Microsoft Word for Mac 2011  
(3165796)  
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
[**MS16-070**](https://technet.microsoft.com/zh-tw/library/security/ms16-070)

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
(3165798)  
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
[**MS16-070**](https://technet.microsoft.com/zh-tw/library/security/ms16-070)

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
(3115111)  
(重要)  
Microsoft Office 相容性套件 Service Pack 3  
(3115194)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2007 Service Pack 3  
(2596915)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 (32 位元版本)  
(2999465)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 (64 位元版本)  
(2999465)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3115187)  
(重要)

</td>
</tr>
</table>
 
**MS16-070 注意事項**

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
[**MS16-070**](https://technet.microsoft.com/zh-tw/library/security/ms16-070)

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
(3115196)  
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
[**MS16-070**](https://technet.microsoft.com/zh-tw/library/security/ms16-070)

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
(3115014)  
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
[**MS16-070**](https://technet.microsoft.com/zh-tw/library/security/ms16-070)

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
(3115244)  
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
[**MS16-070**](https://technet.microsoft.com/zh-tw/library/security/ms16-070)

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
Microsoft Office Web Apps Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3115170)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Office Online Server**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-070**](https://technet.microsoft.com/zh-tw/library/security/ms16-070)

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
Office Online Server

</td>
<td style="border:1px solid black;">
Office Online Server  
(3115134)  
(重要)

</td>
</tr>
</table>
 
**MS16-070 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

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
[**MS16-079**](https://technet.microsoft.com/zh-tw/library/security/ms16-063)

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
Microsoft Exchange Server 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3  
(3151086)  
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
[**MS16-079**](https://technet.microsoft.com/zh-tw/library/security/ms16-063)

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
Microsoft Exchange Server 2010 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3  
(3151097)  
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
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-079**](https://technet.microsoft.com/zh-tw/library/security/ms16-063)

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
Microsoft Exchange Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1  
(3150501)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累積更新 11

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累積更新 11  
(3150501)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累積更新 12

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累積更新 12  
(3150501)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-079**](https://technet.microsoft.com/zh-tw/library/security/ms16-063)

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
Microsoft Exchange Server 2016

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016  
(3150501)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016 累積更新 1

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016 累積更新 1  
(3150501)  
(重要)

</td>
</tr>
</table>
 

偵測與部署工具及指南
--------------------

有幾項資源可協助系統管理員部署安全性更新。

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機與遠端系統是否有遺漏的安全性更新或常見的安全性錯誤設定。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 可協助系統管理員發佈安全性更新。

應用程式相容性工具組隨附的 Update Compatibility Evaluator 元件可針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

如需上述工具以及其他可使用工具的詳細資訊，請參閱 [IT 專業人員的資訊安全工具](http://technet.microsoft.com/zh-tw/security/cc297183)。

致謝
----

Microsoft 了解資訊安全業界所做的努力，其盡責地透露弱點來協助我們保護客戶。請參閱[致謝](https://technet.microsoft.com/zh-tw/library/security/mt674627.aspx)以取得詳細資訊。

其他資訊
--------

### Microsoft Windows 惡意軟體移除工具

針對每個月第二個星期二發行的公告，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 及下載中心發行更新版本的 Microsoft Windows 惡意軟體移除工具。不定期資訊安全公告發行不提供更新版本的 Microsoft Windows 惡意軟體移除工具。

### MU、WU 及 WSUS 上的非安全性更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [Microsoft 知識庫文章 894199](https://support.microsoft.com/zh-tw/kb/894199)：說明 Software Update Services 和 Windows Server Update Services 的內容變更其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](http://technet.microsoft.com/zh-tw/windowsserver/bb332157.aspx)。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的資訊安全保護，Microsoft 將在每月發行安全性更新之前，提前向重要資訊安全軟體提供者提供資訊安全風險資訊。資訊安全軟體提供者可利用此弱點，透過其資訊安全軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://technet.microsoft.com/zh-tw/security/dn467918)(英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

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

適用於 IT 專業人員的安全性解決方案：[TechNet 安全性疑難排解與支援 (英文)](http://technet.microsoft.com/zh-tw/security/bb980617)

協助保護您執行 Windows 的電腦免於受到病毒和惡意程式碼攻擊：[病毒解決方案與資訊安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-tw)

根據您所在國家/地區的當地支援：[Micorsoft 技術支援](http://support.microsoft.com/common/international.aspx?ln=zh-tw)

### 免責聲明

Microsoft 知識庫提供的資訊係依「現況」提供，不做任何保證。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

### 修訂

-   V1.0 (2016 年 6 月 14 日)：公告摘要發行。
-   V1.1 (2016 年 6 月 15 日)：針對 MS16-072 新增已知問題至＜提要＞表格。MS16-072 中的更新會變更擷取使用者群組原則所需要的資訊安全內容。如需關於變更此原本設計行為的詳細資訊，請參閱 [Microsoft 知識庫文章 3163622](https://support.microsoft.com/zh-tw/kb/3163622)。針對 MS16-074 修訂＜提要＞以更正攻擊媒介說明。這僅是資訊變更。
-   V2.0 (2016 年 6 月 16 日)：修訂公告摘要，以記錄不定期發行的 MS16-083。

*頁面產生時間：2016-06-16 10:24-07:00。*
