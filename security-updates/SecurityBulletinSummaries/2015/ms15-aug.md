---
TOCTitle: 'MS15-AUG'
Title: 2015 年 8 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms15-aug'
ms:contentKeyID: 68236026
ms:date: '12/04/2015'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms15-aug(v=Security.10)'
---

2015 年 8 月份 Microsoft 資訊安全公告摘要
=========================================

發行日期：2015 年 8 月 11 日 | 更新日期：2015 年 12 月 1 日

**版本：** 3.1

此公告摘要列出 2015 年 8 月份發行之資訊安全公告。

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 積存安全性更新 (3082442)</strong> <br />
此安全性更新可解決 Internet Explorer 中的弱點。其中最嚴重的弱點，可能在使用者以 Internet Explorer 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用這些弱點的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;"><strong>Microsoft 圖形元件中的弱點可能會允許遠端執行程式碼 (3078662)</strong><br />
此安全性更新可以解決 Microsoft Windows、Microsoft.NET Framework、Microsoft Office、Microsoft Lync 和 Microsoft Silverlight 中的弱點。如果使用者開啟蓄意製作的文件，或是造訪內嵌 TrueType 或 OpenType 字型的不受信任網頁，這些弱點中最嚴重者可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework、<br />
Microsoft Office、<br />
Microsoft Lync、<br />
Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-081">MS15-081</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 的弱點可能會允許遠端執行程式碼 (3080790)<br />
</strong>此安全性更新可解決 Microsoft Office 中的弱點。如果使用者開啟蓄意製作的 Microsoft Office 檔案，最嚴重的弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者，能以目前使用者的權限層級執行任意程式碼。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3080790">3080790</a></td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-082">MS15-082</a></td>
<td style="border:1px solid black;"><strong>RDP 中的弱點會允許遠端程式碼執行 (3080348)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者先將蓄意製作的動態連結程式庫 (DLL) 檔案放在目標使用者目前的工作目錄，然後說服使用者開啟遠端桌面通訊協定 (RDP) 檔案，或將原本設計來載入受信任 DLL 檔案的程式，改為載入了攻擊者蓄意製作的 DLL 檔案，最嚴重的弱點可能會允許遠端程式碼執行。成功利用這些弱點的攻擊者就可以完全控制受影響的系統。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3080348">3080348</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-083">MS15-083</a></td>
<td style="border:1px solid black;"><strong>伺服器訊息區中的弱點可能會允許遠端執行程式碼 (3073921)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者傳送蓄意製作的字串到 SMB 伺服器錯誤記錄，這項弱點可允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-084">MS15-084</a></td>
<td style="border:1px solid black;"><strong>XML Core Services 中的弱點可能會允許資訊洩漏 (3080129)</strong><br />
此安全性更新可解決 Microsoft Windows 和 Microsoft Office 中的弱點。這些弱點可能會藉由當使用者按一下蓄意製作的連結時暴露記憶體位址，或明確地允許使用安全通訊端層 (SSL) 2.0 來允許資訊洩漏。但在所有情況下，攻擊者都無法強迫使用者按一下蓄意製作的連結。攻擊者必須引誘使用者按一下連結，一般是藉助電子郵件的附件或 Instant Messenger 訊息。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
資訊洩漏</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3076895">3076895</a></td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-085">MS15-085</a></td>
<td style="border:1px solid black;"><strong>Mount Manager 中的弱點可能會允許權限提高 (3082487)</strong><br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者將惡意的 USB 裝置插入目標系統，該弱點可能會允許權限提高。接著，攻擊者可以惡意的二進位檔寫入磁碟並予以執行。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3071756">3071756</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-086">MS15-086</a></td>
<td style="border:1px solid black;"><strong>System Center Operations Manager 中的弱點可能會允許權限提高 (3075158)</strong><br />
本安全性更新可解決 Microsoft System Center Operations Manager 中的弱點。如果使用者透過蓄意製作的 URL 造訪受影響的網站，此弱點可能會允許權限提高。攻擊者並無法強迫使用者造訪這類網站，而是引誘使用者自行前往。一般的做法是設法讓使用者點選電子郵件或 Instant Messenger 訊息中連往受影響網站的連結。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">不需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft 伺服器軟體</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-087">MS15-087</a></td>
<td style="border:1px solid black;"><strong>UDDI 服務中的弱點可能會允許權限提高 (3082459)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者將惡意的指令碼插入網頁搜尋參數來設計跨網站指令碼 (XSS) 案例，該弱點可能會允許權限提高。使用者必須造訪蓄意製作的網頁，惡意的指令碼才能執行。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">不需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft 伺服器軟體</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-088">MS15-088</a></td>
<td style="border:1px solid black;"><strong>不安全的命令列參數傳遞可能會允許資訊洩漏 (3082458)</strong><br />
此安全性更新有助於解決 Microsoft Windows、Internet Explorer 及 Microsoft Office 中的資訊洩漏弱點。如果要利用這項弱點，攻擊者必須先使用 Internet Explorer 中的另一項弱點在沙箱化程序中執行程式碼。接著，攻擊者可以使用不安全的命令列參數來執行記事本、Visio、PowerPoint、Excel 或 Word，讓資訊洩漏生效。若要避免受此弱點的影響，客戶必須套用本安全公告所提供的更新，以及 <a href="https://technet.microsoft.com/zh-tw/library/security/ms15-079">MS15-079</a> 所提供的 Internet Explorer 更新。同樣地，執行受影響之 Microsoft Office 產品的客戶也必須安裝 <a href="https://technet.microsoft.com/zh-tw/library/security/ms15-081">MS15-081</a> 所提供的適用更新。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
資訊洩漏</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-089">MS15-089</a></td>
<td style="border:1px solid black;"><strong>WebDAV 中的弱點可能會導致資訊洩漏 (3076949)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者利用啟用安全通訊端層 (SSL) 2.0 的 WebDAV 伺服器強制執行加密 SSL 2.0 工作階段，並使用攔截式 (MiTM) 攻擊來解密加密流量的部分內容，此弱點可能會導致資訊洩漏。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
資訊洩漏</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-090">MS15-090</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows 雲端中的弱點可能會允許權限提高 (3060716)</strong> <br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者登入受影響的系統並執行蓄意製作的應用程式，或說服使用者開啟會叫用容易遭受攻擊之沙箱應用程式的蓄意製作檔案，讓攻擊者得以逸出沙箱，這些弱點可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3060716">3060716</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-091">MS15-091</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 的累積安全性更新 (3084525)<br />
</strong>此安全性更新可解決 Microsoft Edge 中的弱點。其中最嚴重的弱點，可能在使用者以 Microsoft Edge 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用這些弱點的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-092">MS15-092</a></td>
<td style="border:1px solid black;"><strong>.NET Framework 中的弱點可能會允許權限提高 (3086251)<br />
</strong>這個安全性更新可解決 Microsoft .NET Framework 中的弱點。如果使用者執行蓄意製作的 .NET 應用程式，這些弱點可能會允許權限提高。不過，在所有情況下，攻擊者都無法強迫使用者執行應用程式，他們必須說服使用者。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-093">MS15-093</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 安全性更新 (3088903)</strong><br />
此安全性更新可解決 Internet Explorer 中的弱點。如果使用者使用 Internet Explorer 檢視蓄意製作的網頁，此弱點可能會允許遠端執行程式碼。成功利用此弱點的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
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
<td style="border:1px solid black;"><strong>公告識別碼</strong></td>
<td style="border:1px solid black;"><strong>弱點標題</strong></td>
<td style="border:1px solid black;"><strong>CVE ID</strong></td>
<td style="border:1px solid black;"><strong>較早軟體版本的<br />
弱點評估</strong></td>
<td style="border:1px solid black;"><strong>較早軟體版本的<br />
弱點評估</strong></td>
<td style="border:1px solid black;"><strong>阻斷服務<br />
弱點評估</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">不安全的命令列參數傳遞弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2423">CVE-2015-2423</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2441">CVE-2015-2441</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2442">CVE-2015-2442</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2443">CVE-2015-2443</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2444">CVE-2015-2444</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">ASLR 略過</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2445">CVE-2015-2445</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2446">CVE-2015-2446</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2447">CVE-2015-2447</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2448">CVE-2015-2448</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">ASLR 略過</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2449">CVE-2015-2449</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2450">CVE-2015-2450</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2451">CVE-2015-2451</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2452">CVE-2015-2452</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">Microsoft Office 圖形元件遠端程式碼執行弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2431">CVE-2015-2431</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">OpenType 字型剖析弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2432">CVE-2015-2432</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">核心 ASLR 略過弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2433">CVE-2015-2433</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">TrueType 字型剖析弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2435">CVE-2015-2435</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">Windows CSRSS 權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2453">CVE-2015-2453</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">Windows KMD 資訊安全功能略過弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2454">CVE-2015-2454</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">TrueType 字型剖析弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2455">CVE-2015-2455</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">TrueType 字型剖析弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2456">CVE-2015-2456</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">OpenType 字型剖析弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2458">CVE-2015-2458</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">OpenType 字型剖析弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2459">CVE-2015-2459</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">OpenType 字型剖析弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2460">CVE-2015-2460</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">OpenType 字型剖析弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2461">CVE-2015-2461</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">OpenType 字型剖析弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2462">CVE-2015-2462</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">TrueType 字型剖析弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2463">CVE-2015-2463</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">TrueType 字型剖析弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2464">CVE-2015-2464</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">Windows Shell 資訊安全功能略過弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2465">CVE-2015-2465</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-081">MS15-081</a></td>
<td style="border:1px solid black;">Microsoft Office 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1642">CVE-2015-1642</a></td>
<td style="border:1px solid black;">0 - 已偵測到利用</td>
<td style="border:1px solid black;">0 - 已偵測到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-081">MS15-081</a></td>
<td style="border:1px solid black;">不安全的命令列參數傳遞弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2423">CVE-2015-2423</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-081">MS15-081</a></td>
<td style="border:1px solid black;">Microsoft Office 遠端程式碼執行弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2466">CVE-2015-2466</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-081">MS15-081</a></td>
<td style="border:1px solid black;">Microsoft Office 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2467">CVE-2015-2467</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-081">MS15-081</a></td>
<td style="border:1px solid black;">Microsoft Office 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2468">CVE-2015-2468</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-081">MS15-081</a></td>
<td style="border:1px solid black;">Microsoft Office 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2469">CVE-2015-2469</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-081">MS15-081</a></td>
<td style="border:1px solid black;">Microsoft Office 整數反向溢位弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2470">CVE-2015-2470</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-081">MS15-081</a></td>
<td style="border:1px solid black;">Microsoft Office 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2477">CVE-2015-2477</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-082">MS15-082</a></td>
<td style="border:1px solid black;">遠端桌面工作階段主機偽造弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2472">CVE-2015-2472</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-082">MS15-082</a></td>
<td style="border:1px solid black;">遠端桌面通訊協定 DLL 設置遠端程式碼執行弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2473">CVE-2015-2473</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-083">MS15-083</a></td>
<td style="border:1px solid black;">伺服器訊息區記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2474">CVE-2015-2474</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-084">MS15-084</a></td>
<td style="border:1px solid black;">MSXML 資訊洩漏弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2434">CVE-2015-2434</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-084">MS15-084</a></td>
<td style="border:1px solid black;">MSXML 資訊洩漏弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2440">CVE-2015-2440</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-084">MS15-084</a></td>
<td style="border:1px solid black;">MSXML 資訊洩漏弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2471">CVE-2015-2471</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-085">MS15-085</a></td>
<td style="border:1px solid black;">Mount Manager 中的權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1769">CVE-2015-1769</a></td>
<td style="border:1px solid black;">0 - 已偵測到利用</td>
<td style="border:1px solid black;">0 - 已偵測到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-086">MS15-086</a></td>
<td style="border:1px solid black;">System Center Operations Manager 網頁主控台 XSS 弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2420">CVE-2015-2420</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-087">MS15-087</a></td>
<td style="border:1px solid black;">UDDI 服務權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2475">CVE-2015-2475</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-088">MS15-088</a></td>
<td style="border:1px solid black;">不安全的命令列參數傳遞弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2423">CVE-2015-2423</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619309">MS15-089</a></td>
<td style="border:1px solid black;">WebDAV 用戶端資訊洩漏弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2476">CVE-2015-2476</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-090">MS15-090</a></td>
<td style="border:1px solid black;">Windows 物件管理員權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2428">CVE-2015-2428</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-090">MS15-090</a></td>
<td style="border:1px solid black;">Windows 登錄權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2429">CVE-2015-2429</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-090">MS15-090</a></td>
<td style="border:1px solid black;">Windows 檔案系統權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2430">CVE-2015-2430</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-091">MS15-091</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2441">CVE-2015-2441</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-091">MS15-091</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2442">CVE-2015-2442</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-091">MS15-091</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2446">CVE-2015-2446</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-091">MS15-091</a></td>
<td style="border:1px solid black;">ASLR 略過</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2449">CVE-2015-2449</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-092">MS15-092</a></td>
<td style="border:1px solid black;">RyuJIT 最佳化權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2479">CVE-2015-2479</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-092">MS15-092</a></td>
<td style="border:1px solid black;">RyuJIT 最佳化權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2480">CVE-2015-2480</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-092">MS15-092</a></td>
<td style="border:1px solid black;">RyuJIT 最佳化權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2481">CVE-2015-2481</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-093">MS15-093</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2502">CVE-2015-2502</a></td>
<td style="border:1px solid black;">0 - 已偵測到利用</td>
<td style="border:1px solid black;">0 - 已偵測到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
</tbody>
</table>
  
受影響的軟體  
------------
  
下表依據主要的軟體類別和嚴重性依序列出公告。
  
請用這些表格來瞭解可能需要安裝的資訊安全更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的資訊安全更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。
  
**注意**：一項弱點，可能需要安裝數個資訊安全更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
### Windows 作業系統及元件 (表格 3 之 1)

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[<strong>MS15-079</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-079)

</td>
<td style="border:1px solid black;">
[<strong>MS15-080</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[<strong>MS15-082</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-082)

</td>
<td style="border:1px solid black;">
[<strong>MS15-083</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-083)

</td>
<td style="border:1px solid black;">
[<strong>MS15-084</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-084)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3078071)  
(重大)  
Internet Explorer 8  
(3078071)  
(重大)  
Internet Explorer 9  
(3078071)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3078601)  
(重大)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3072303)  
(重大)  
Microsoft .NET Framework 4  
(3072309)  
(重大)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3072310)  
(重大)  
Microsoft .NET Framework 4.6  
(3072311)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3075220)  
(重要)  
Windows Vista Service Pack 2  
(3075221)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3073921)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3078071)  
(重大)  
Internet Explorer 8  
(3078071)  
(重大)  
Internet Explorer 9  
(3078071)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3078601)  
(重大)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3072303)  
(重大)  
Microsoft .NET Framework 4  
(3072309)  
(重大)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3072310)  
(重大)  
Microsoft .NET Framework 4.6  
(3072311)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3075220)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3075221)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3073921)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
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
[<strong>MS15-079</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-079)

</td>
<td style="border:1px solid black;">
[<strong>MS15-080</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[<strong>MS15-082</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-082)

</td>
<td style="border:1px solid black;">
[<strong>MS15-083</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-083)

</td>
<td style="border:1px solid black;">
[<strong>MS15-084</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-084)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>中度</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3078071)  
(中度)  
Internet Explorer 8  
(3078071)  
(中度)  
Internet Explorer 9  
(3078071)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3078601)  
(重大)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3072303)  
(重大)  
Microsoft .NET Framework 4  
(3072309)  
(重大)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3072310)  
(重大)  
Microsoft .NET Framework 4.6  
(3072311)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3073921)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3078071)  
(中度)  
Internet Explorer 8  
(3078071)  
(中度)  
Internet Explorer 9  
(3078071)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3078601)  
(重大)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3072303)  
(重大)  
Microsoft .NET Framework 4  
(3072309)  
(重大)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3072310)  
(重大)  
Microsoft .NET Framework 4.6  
(3072311)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3073921)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3078071)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3078601)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3073921)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
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
[<strong>MS15-079</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-079)

</td>
<td style="border:1px solid black;">
[<strong>MS15-080</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[<strong>MS15-082</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-082)

</td>
<td style="border:1px solid black;">
[<strong>MS15-083</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-083)

</td>
<td style="border:1px solid black;">
[<strong>MS15-084</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-084)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3078071)  
(重大)  
Internet Explorer 9  
(3078071)  
(重大)  
Internet Explorer 10  
(3078071)  
(重大)  
Internet Explorer 11  
(3078071)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3078601)  
(重大)  
Microsoft .NET Framework 3.5.1  
(3072305)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3075220)  
(重要)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3075222)  
(重要)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3075226)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3078071)  
(重大)  
Internet Explorer 9  
(3078071)  
(重大)  
Internet Explorer 10  
(3078071)  
(重大)  
Internet Explorer 11  
(3078071)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3078601)  
(重大)  
Microsoft .NET Framework 3.5.1  
(3072305)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3075220)  
(重要)  
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3075222)  
(重要)  
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3075226)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
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
[<strong>MS15-079</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-079)

</td>
<td style="border:1px solid black;">
[<strong>MS15-080</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[<strong>MS15-082</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-082)

</td>
<td style="border:1px solid black;">
[<strong>MS15-083</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-083)

</td>
<td style="border:1px solid black;">
[<strong>MS15-084</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-084)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>中度</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3078071)  
(中度)  
Internet Explorer 9  
(3078071)  
(中度)  
Internet Explorer 10  
(3078071)  
(中度)  
Internet Explorer 11  
(3078071)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3078601)  
(重大)  
Microsoft .NET Framework 3.5.1  
(3072305)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3075220)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3075222)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3075226)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3078071)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3078601)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
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
[<strong>MS15-079</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-079)

</td>
<td style="border:1px solid black;">
[<strong>MS15-080</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[<strong>MS15-082</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-082)

</td>
<td style="border:1px solid black;">
[<strong>MS15-083</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-083)

</td>
<td style="border:1px solid black;">
[<strong>MS15-084</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-084)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 32 位元系統

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3078071)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3078601)  
(重大)  
Microsoft .NET Framework 3.5  
(3072306)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3078071)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(3078601)  
(重大)  
Microsoft .NET Framework 3.5  
(3072306)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3078071)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3078601)  
(重大)  
Microsoft .NET Framework 3.5  
(3072307)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3078071)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3078601)  
(重大)  
Microsoft .NET Framework 3.5  
(3072307)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
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
[<strong>MS15-079</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-079)

</td>
<td style="border:1px solid black;">
[<strong>MS15-080</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[<strong>MS15-082</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-082)

</td>
<td style="border:1px solid black;">
[<strong>MS15-083</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-083)

</td>
<td style="border:1px solid black;">
[<strong>MS15-084</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-084)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>中度</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3078071)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3078601)  
(重大)  
Microsoft .NET Framework 3.5  
(3072306)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3078071)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3078601)  
(重大)  
Microsoft .NET Framework 3.5  
(3072307)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
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
[<strong>MS15-079</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-079)

</td>
<td style="border:1px solid black;">
[<strong>MS15-080</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[<strong>MS15-082</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-082)

</td>
<td style="border:1px solid black;">
[<strong>MS15-083</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-083)

</td>
<td style="border:1px solid black;">
[<strong>MS15-084</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-084)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3078071)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT  
(3078601)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3078071)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3078601)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
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
[<strong>MS15-079</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-079)

</td>
<td style="border:1px solid black;">
[<strong>MS15-080</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[<strong>MS15-082</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-082)

</td>
<td style="border:1px solid black;">
[<strong>MS15-083</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-083)

</td>
<td style="border:1px solid black;">
[<strong>MS15-084</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-084)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
Windows 10 32 位元系統

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3081436)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 10 32 位元系統  
(3081436)  
(重大)  
Microsoft .NET Framework 3.5  
(3081436)  
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
適用於 x64 型系統的 Windows 10

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3081436)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3081436)  
(重大)  
Microsoft .NET Framework 3.5  
(3081436)  
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
<td style="border:1px solid black;" colspan="6">
**Server Core 安裝選項**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[<strong>MS15-079</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-079)

</td>
<td style="border:1px solid black;">
[<strong>MS15-080</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[<strong>MS15-082</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-082)

</td>
<td style="border:1px solid black;">
[<strong>MS15-083</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-083)

</td>
<td style="border:1px solid black;">
[<strong>MS15-084</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-084)

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
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
(3078601)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3073921)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
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
(3078601)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3073921)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
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
(3078601)  
(重大)  
Microsoft .NET Framework 3.5.1  
(3072305)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
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
(3078601)  
(重大)  
Microsoft .NET Framework 3.5  
(3072306)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
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
(3078601)  
(重大)  
Microsoft .NET Framework 3.5  
(3072307)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
(重要)

</td>
</tr>
</table>
 
**MS15-080 和 MS15-084 的附註**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

### Windows 作業系統及元件 (表格 3 之 2)

 
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
[<strong>MS15-085</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-085)

</td>
<td style="border:1px solid black;">
[<strong>MS15-087</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-087)

</td>
<td style="border:1px solid black;">
[<strong>MS15-088</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-088)

</td>
<td style="border:1px solid black;">
[<strong>MS15-089</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-089)

</td>
<td style="border:1px solid black;">
[<strong>MS15-090</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-090)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3046017)  
(重要)  
Windows Vista Service Pack 2  
(3079757)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3046017)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3079757)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3060716)  
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
[<strong>MS15-085</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-085)

</td>
<td style="border:1px solid black;">
[<strong>MS15-087</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-087)

</td>
<td style="border:1px solid black;">
[<strong>MS15-088</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-088)

</td>
<td style="border:1px solid black;">
[<strong>MS15-089</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-089)

</td>
<td style="border:1px solid black;">
[<strong>MS15-090</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-090)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3073893)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3046017)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3079757)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3073893)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3046017)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3079757)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3046017)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3079757)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3060716)  
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
[<strong>MS15-085</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-085)

</td>
<td style="border:1px solid black;">
[<strong>MS15-087</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-087)

</td>
<td style="border:1px solid black;">
[<strong>MS15-088</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-088)

</td>
<td style="border:1px solid black;">
[<strong>MS15-089</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-089)

</td>
<td style="border:1px solid black;">
[<strong>MS15-090</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-090)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3046017)  
(重要)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3079757)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3046017)  
(重要)  
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3079757)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3060716)  
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
[<strong>MS15-085</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-085)

</td>
<td style="border:1px solid black;">
[<strong>MS15-087</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-087)

</td>
<td style="border:1px solid black;">
[<strong>MS15-088</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-088)

</td>
<td style="border:1px solid black;">
[<strong>MS15-089</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-089)

</td>
<td style="border:1px solid black;">
[<strong>MS15-090</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-090)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3046017)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3079757)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3046017)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3079757)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3060716)  
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
[<strong>MS15-085</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-085)

</td>
<td style="border:1px solid black;">
[<strong>MS15-087</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-087)

</td>
<td style="border:1px solid black;">
[<strong>MS15-088</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-088)

</td>
<td style="border:1px solid black;">
[<strong>MS15-089</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-089)

</td>
<td style="border:1px solid black;">
[<strong>MS15-090</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-090)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 32 位元系統

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3046017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(3046017)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3046017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3046017)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3060716)  
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
[<strong>MS15-085</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-085)

</td>
<td style="border:1px solid black;">
[<strong>MS15-087</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-087)

</td>
<td style="border:1px solid black;">
[<strong>MS15-088</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-088)

</td>
<td style="border:1px solid black;">
[<strong>MS15-089</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-089)

</td>
<td style="border:1px solid black;">
[<strong>MS15-090</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-090)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3046017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3046017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3060716)  
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
[<strong>MS15-085</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-085)

</td>
<td style="border:1px solid black;">
[<strong>MS15-087</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-087)

</td>
<td style="border:1px solid black;">
[<strong>MS15-088</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-088)

</td>
<td style="border:1px solid black;">
[<strong>MS15-089</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-089)

</td>
<td style="border:1px solid black;">
[<strong>MS15-090</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-090)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Windows RT  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT  
(3046017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3046017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3060716)  
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
[<strong>MS15-085</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-085)

</td>
<td style="border:1px solid black;">
[<strong>MS15-087</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-087)

</td>
<td style="border:1px solid black;">
[<strong>MS15-088</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-088)

</td>
<td style="border:1px solid black;">
[<strong>MS15-089</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-089)

</td>
<td style="border:1px solid black;">
[<strong>MS15-090</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-090)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
Windows 10 32 位元系統

</td>
<td style="border:1px solid black;">
Windows 10 32 位元系統  
(3081436)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 10 32 位元系統  
(3081436)  
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
適用於 x64 型系統的 Windows 10

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3081436)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3081436)  
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
<td style="border:1px solid black;" colspan="6">
**Server Core 安裝選項**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[<strong>MS15-085</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-085)

</td>
<td style="border:1px solid black;">
[<strong>MS15-087</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-087)

</td>
<td style="border:1px solid black;">
[<strong>MS15-088</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-088)

</td>
<td style="border:1px solid black;">
[<strong>MS15-089</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-089)

</td>
<td style="border:1px solid black;">
[<strong>MS15-090</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-090)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3073893)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3046017)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3079757)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3073893)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3046017)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3079757)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3046017)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3079757)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3046017)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3046017)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3060716)  
(重要)

</td>
</tr>
</table>
 
**MS15-087 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

### Windows 作業系統及元件 (表格 3 之 3)

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[<strong>MS15-091</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-091)

</td>
<td style="border:1px solid black;">
[<strong>MS15-092</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-092)

</td>
<td style="border:1px solid black;">
[<strong>MS15-093</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-093)

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
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
Microsoft .NET Framework 4.6  
(3083186)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087985)  
(重大)  
Internet Explorer 8  
(3087985)  
(重大)  
Internet Explorer 9  
(3087985)  
(重大)

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
Microsoft .NET Framework 4.6  
(3083186)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087985)  
(重大)  
Internet Explorer 8  
(3087985)  
(重大)  
Internet Explorer 9  
(3087985)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[<strong>MS15-091</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-091)

</td>
<td style="border:1px solid black;">
[<strong>MS15-092</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-092)

</td>
<td style="border:1px solid black;">
[<strong>MS15-093</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-093)

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
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>中度</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
Microsoft .NET Framework 4.6  
(3083186)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087985)  
(中度)  
Internet Explorer 8  
(3087985)  
(中度)  
Internet Explorer 9  
(3087985)  
(中度)

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
Microsoft .NET Framework 4.6  
(3083186)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087985)  
(中度)  
Internet Explorer 8  
(3087985)  
(中度)  
Internet Explorer 9  
(3087985)  
(中度)

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
Internet Explorer 7  
(3087985)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[<strong>MS15-091</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-091)

</td>
<td style="border:1px solid black;">
[<strong>MS15-092</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-092)

</td>
<td style="border:1px solid black;">
[<strong>MS15-093</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-093)

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
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083186)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3087985)  
(重大)  
Internet Explorer 9  
(3087985)  
(重大)  
Internet Explorer 10  
(3087985)  
(重大)  
Internet Explorer 11  
(3087985)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083186)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3087985)  
(重大)  
Internet Explorer 9  
(3087985)  
(重大)  
Internet Explorer 10  
(3087985)  
(重大)  
Internet Explorer 11  
(3087985)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[<strong>MS15-091</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-091)

</td>
<td style="border:1px solid black;">
[<strong>MS15-092</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-092)

</td>
<td style="border:1px solid black;">
[<strong>MS15-093</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-093)

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
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>中度</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083186)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3087985)  
(中度)  
Internet Explorer 9  
(3087985)  
(中度)  
Internet Explorer 10  
(3087985)  
(中度)  
Internet Explorer 11  
(3087985)  
(中度)

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
Internet Explorer 8  
(3087985)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[<strong>MS15-091</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-091)

</td>
<td style="border:1px solid black;">
[<strong>MS15-092</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-092)

</td>
<td style="border:1px solid black;">
[<strong>MS15-093</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-093)

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
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
Microsoft .NET Framework 4.6  
(3083184)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3087985)  
(重大)

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
Microsoft .NET Framework 4.6  
(3083184)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3087985)  
(重大)

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
Microsoft .NET Framework 4.6  
(3083185)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3087985)  
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
Microsoft .NET Framework 4.6  
(3083185)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3087985)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[<strong>MS15-091</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-091)

</td>
<td style="border:1px solid black;">
[<strong>MS15-092</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-092)

</td>
<td style="border:1px solid black;">
[<strong>MS15-093</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-093)

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
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>中度</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
Microsoft .NET Framework 4.6  
(3083184)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3087985)  
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
Microsoft .NET Framework 4.6  
(3083185)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3087985)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[<strong>MS15-091</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-091)

</td>
<td style="border:1px solid black;">
[<strong>MS15-092</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-092)

</td>
<td style="border:1px solid black;">
[<strong>MS15-093</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-093)

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
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
Microsoft .NET Framework 4.6  
(3083184)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3087985)  
(重大)

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
Microsoft .NET Framework 4.6  
(3083185)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3087985)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[<strong>MS15-091</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-091)

</td>
<td style="border:1px solid black;">
[<strong>MS15-092</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-092)

</td>
<td style="border:1px solid black;">
[<strong>MS15-093</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-093)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 32 位元系統

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3081436)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3081436)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3081444)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3081436)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3081436)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3081444)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Server Core 安裝選項**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[<strong>MS15-091</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-091)

</td>
<td style="border:1px solid black;">
[<strong>MS15-092</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-092)

</td>
<td style="border:1px solid black;">
[<strong>MS15-093</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-093)

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
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
Microsoft .NET Framework 4.6  
(3083186)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

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
Microsoft .NET Framework 4.6  
(3083186)  
(重要)

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
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083186)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

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
Microsoft .NET Framework 4.6  
(3083184)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

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
Microsoft .NET Framework 4.6  
(3083185)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
</table>
 
### Microsoft 伺服器軟體

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft System Center 2012 Operations Manager**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;" colspan="2">
[<strong>MS15-086</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-086)

</td>
<td style="border:1px solid black;">
[<strong>MS15-087</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-087)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;" colspan="2">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft System Center 2012 Operations Manager

</td>
<td style="border:1px solid black;" colspan="2">
Microsoft System Center 2012 Operations Manager  
(安裝更新彙總套件 8)  
(3071089)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft System Center 2012 Operations Manager Service Pack 1

</td>
<td style="border:1px solid black;" colspan="2">
Microsoft System Center 2012 Operations Manager Service Pack 1  
(安裝更新彙總套件 10)  
(3071088)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft System Center 2012 Operations Manager R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**公告編號**

</td>
<td style="border:1px solid black;">
[<strong>MS15-086</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-086)

</td>
<td style="border:1px solid black;">
[<strong>MS15-087</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-087)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
Microsoft System Center 2012 Operations Manager R2

</td>
<td style="border:1px solid black;">
Microsoft System Center 2012 Operations Manager R2  
(安裝更新彙總套件 7)  
(3064919)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft BizTalk Server**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**公告編號**

</td>
<td style="border:1px solid black;">
[<strong>MS15-086</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-086)

</td>
<td style="border:1px solid black;">
[<strong>MS15-087</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-087)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
Microsoft BizTalk Server 2010

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft BizTalk Server 2010  
(3087119)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
Microsoft BizTalk Server 2013

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft BizTalk Server 2013  
(3087119)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
Microsoft BizTalk Server 2013 R2

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft BizTalk Server 2013 R2  
(3087119)  
(重要)

</td>
</tr>
</table>
 
**MS15-087 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

### Microsoft Office 套件及軟體

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[<strong>MS15-080</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[<strong>MS15-081</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-081)

</td>
<td style="border:1px solid black;">
[<strong>MS15-084</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-084)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3054890)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2687409)  
(重要)  
Microsoft Office 2007 Service Pack 3  
(3054888)  
(重大)  
Microsoft Office 2007 Service Pack 3  
(2596650)  
(重大)  
Microsoft Office 2007 Service Pack 3  
(2837610)  
(重要)  
Microsoft Excel 2007 Service Pack 3  
(3054992)  
(重要)  
Microsoft PowerPoint 2007 Service Pack 3  
(3055051)  
(重要)  
Microsoft Visio 2007 Service Pack 3  
(2965280)  
(重要)  
Microsoft Word 2007 Service Pack 3  
(3055052)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 5.0  
(2825645)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[<strong>MS15-080</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[<strong>MS15-081</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-081)

</td>
<td style="border:1px solid black;">
[<strong>MS15-084</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-084)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(3054846)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(2965310)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(3055037)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(2553313)  
(重大)  
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(2598244)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (32 位元版本)  
(3055044)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (32 位元版本)  
(3055033)  
(重要)  
Microsoft Visio 2010 Service Pack 2 (32 位元版本)  
(3054876)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 位元版本)  
(3055039)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3054846)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(2965310)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3055037)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(2553313)  
(重大)  
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(2598244)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (64 位元版本)  
(3055044)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (64 位元版本)  
(3055033)  
(重要)  
Microsoft Visio 2010 Service Pack 2 (64 位元版本)  
(3054876)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 位元版本)  
(3055039)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[<strong>MS15-080</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[<strong>MS15-081</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-081)

</td>
<td style="border:1px solid black;">
[<strong>MS15-084</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-084)

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
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

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
(3039734)  
(重要)  
Microsoft Office 2013 Service Pack 1 (32 位元版本)  
(3039798)  
(重大)  
Microsoft Office 2013 Service Pack 1 (32 位元版本)  
(3054816)  
(重要)  
Microsoft Excel 2013 Service Pack 1 (32 位元版本)  
(3054991)  
(重要)  
Microsoft PowerPoint 2013 Service Pack 1 (32 位元版本)  
(3055029)  
(重要)  
Microsoft Visio 2013 Service Pack 1 (32 位元版本)  
(3054929)  
(重要)  
Microsoft Word 2013 Service Pack 1 (32 位元版本)  
(3055030)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

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
(3039734)  
(重要)  
Microsoft Office 2013 Service Pack 1 (64 位元版本)  
(3039798)  
(重大)  
Microsoft Office 2013 Service Pack 1 (64 位元版本)  
(3054816)  
(重要)  
Microsoft Excel 2013 Service Pack 1 (64 位元版本)  
(3054991)  
(重要)  
Microsoft PowerPoint 2013 Service Pack 1 (64 位元版本)  
(3055029)  
(重要)  
Microsoft Visio 2013 Service Pack 1 (64 位元版本)  
(3054929)  
(重要)  
Microsoft Word 2013 Service Pack 1 (64 位元版本)  
(3055030)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[<strong>MS15-080</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[<strong>MS15-081</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-081)

</td>
<td style="border:1px solid black;">
[<strong>MS15-084</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-084)

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
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

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
(3039798)  
(重大)  
Microsoft Office 2013 RT Service Pack 1  
(3054816)  
(重要)  
Microsoft Excel 2013 RT Service Pack 1  
(3054991)  
(重要)  
Microsoft PowerPoint 2013 RT Service Pack 1  
(3055029)  
(重要)  
Microsoft Visio 2013 RT Service Pack 1  
(3054929)  
(重要)  
Microsoft Word 2013 RT Service Pack 1  
(3055030)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[<strong>MS15-080</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[<strong>MS15-081</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-081)

</td>
<td style="border:1px solid black;">
[<strong>MS15-084</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-084)

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
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

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
Microsoft Office 2016 (32 位元版本)  
(3085538)  
(重大)  
Microsoft Visio 2016 (32 位元版本)  
(2920708)  
(重要)  
Microsoft Word 2016 (32 位元版本)  
(2920691)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

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
Microsoft Office 2016 (64 位元版本)  
(3085538)  
(重大)  
Microsoft Visio 2016 (64 位元版本)  
(2920708)  
(重要)  
Microsoft Word 2016 (64 位元版本)  
(2920691)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[<strong>MS15-080</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[<strong>MS15-081</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-081)

</td>
<td style="border:1px solid black;">
[<strong>MS15-084</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-084)

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
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

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
(3081349)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2016

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2016  
(3082420)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**其他 Office 軟體**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[<strong>MS15-080</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[<strong>MS15-081</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-081)

</td>
<td style="border:1px solid black;">
[<strong>MS15-084</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-084)

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
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
(2986254)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3055053)  
(重要)  
Microsoft Word Viewer  
(3055054)  
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
Microsoft XML Core Services 5.0  
(2825645)  
(重要)

</td>
</tr>
</table>
 
**MS15-080、MS15-081 及 MS15-084 的附註**

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
[<strong>MS15-081</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-081)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3054960)  
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
[<strong>MS15-081</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-081)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3054858)  
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
[<strong>MS15-081</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-081)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3054974)  
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
[<strong>MS15-081</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-081)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重要</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3055003)  
(重要)

</td>
</tr>
</table>
 
**MS15-081 注意事項**

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
[<strong>MS15-080</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-080)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console

</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console  
(3075591)  
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
[<strong>MS15-080</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-080)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 位元)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 位元)  
(3075593)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 位元)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 位元)  
(3075593)  
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
(3075592)  
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
(3075590)  
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
[<strong>MS15-080</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-080)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (32 位元)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (32 位元)  
(商務用 Skype)  
(3055014)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (32 位元)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (32 位元)  
(商務用 Skype 基本版)  
(3055014)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (64 位元)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (64 位元)  
(商務用 Skype)  
(3055014)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (64 位元)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (64 位元)  
(商務用 Skype 基本版)  
(3055014)  
(重大)

</td>
</tr>
</table>
 
**MS15-080 注意事項**

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
[<strong>MS15-080</strong>](https://technet.microsoft.com/zh-tw/library/security/ms15-080)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[<strong>重大</strong>](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
安裝在 Mac 上的 Microsoft Silverlight 5  
(3080333)  
(重大)  
安裝在 Mac 上的 Microsoft Silverlight 5 Developer Runtime  
(3080333)  
(重大)  
安裝在所有受支援版本的 Microsoft Windows 用戶端上的 Microsoft Silverlight 5  
(3080333)  
(重大)  
安裝在所有受支援的 Microsoft Windows 用戶端版本上的 Microsoft Silverlight 5 Developer Runtime  
(3080333)  
(重大)  
安裝在所有受支援的 Microsoft Windows 伺服器版本上的 Microsoft Silverlight 5  
(3080333)  
(重大)  
安裝在所有受支援的 Microsoft Windows 伺服器版本上的 Microsoft Silverlight 5 Developer Runtime  
(3080333)  
(重大)

</td>
</tr>
</table>
 
**MS15-080 注意事項**

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

協助保護您的 Widows 電腦免於病毒和惡意軟體攻擊：[病毒解決方案與資訊安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-tw)

您所在國家/地區的當地支援：[多語系支援](http://support.microsoft.com/common/international.aspx?ln=zh-tw)

### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

### 修訂

-   V1.0 (2015 年 8 月 11 日)：公告摘要發行。
-   V2.0 (2015 年 8 月 18 日)：修訂公告摘要，將不定期發行的公告 MS15-093 新增至 8 月份資訊安全公告的發行中。此額外公告可解決 Internet Explorer 中的弱點。請參閱 MS15-093 了解更多資訊。
-   V3.0 (2015 年 10 月 13 日)：對於 MS15-081，修訂公告摘要，宣佈 Microsoft Office 2016、Microsoft Visio 2016 和 Microsoft Word 2016 的更新套件已可使用。執行 Microsoft Office 2016、Microsoft Visio 2016 或 Microsoft Word 2016 的客戶應套用適用的更新以防止受到 MS15-081 中討論的弱點影響。大部分客戶都已啟用自動更新，因此不必採取任何行動，因為系統會自動下載和安裝更新。
-   V3.1 (2015 年 12 月 1 日)：修訂公告摘要，通知客戶 Microsoft 知識庫文章中已新增已知問題文件，其內容關於 MS15-085 (3071756) 與 MS15-090 (3060716) 的更新。請參閱＜提要＞表格以取得連結。

*頁面產生時間：2015-12-01 10:00Z-08:00。*
