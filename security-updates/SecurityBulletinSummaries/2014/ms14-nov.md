---
TOCTitle: 'MS14-NOV'
Title: 2014 年 11 月份 Microsoft 安全性公告摘要
ms:assetid: 'ms14-nov'
ms:contentKeyID: 63355204
ms:date: '11/25/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms14-nov(v=Security.10)'
---

2014 年 11 月份 Microsoft 安全性公告摘要
========================================

發行日期：2014 年 11 月 11 日 | 已更新： 2014 年 11 月 18 日

**版本：** 2.0

此公告摘要列出 2014 年 11 月份發行之安全性公告。

發行 2014 年 11 月份資訊安全公告之後，此公告摘要將取代原先於 2014 年 11 月 6 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 資訊安全公告預先通知](https://technet.microsoft.com/zh-tw/security/gg309152.aspx)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](https://technet.microsoft.com/zh-tw/security/dd252948.aspx)。

Microsoft 也會提供資訊協助客戶排定每月資訊安全更新以及任何非資訊安全更新的優先順序，其中這些非資訊安全更新的發行日期與每月資訊安全更新的發行日期相同。請參閱**＜其他資訊＞**一節。

提要
----

下表依嚴重性摘要說明本月份安全性公告。

如需受影響之軟體的詳細資料，請參閱下節**＜受影響的軟體＞**。

<p></p>
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告編號</strong></td>
<td style="border:1px solid black;"><strong>公告標題與提要</strong></td>
<td style="border:1px solid black;"><strong>最高的嚴重性等級與弱點影響</strong></td>
<td style="border:1px solid black;"><strong>重新開機需求</strong></td>
<td style="border:1px solid black;"><strong>受影響的軟體</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms14-064">MS14-064</a></td>
<td style="border:1px solid black;"><strong>Windows OLE 中的資訊安全風險可能會允許遠端執行程式碼 (3011443)</strong><br />
<br />
這個資訊安全更新可解決 Microsoft Windows 物件連結與嵌入 (OLE) 中兩項未公開報告的資訊安全風險。其中最嚴重的資訊安全風險，可能在使用者以 Internet Explorer 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用這些資訊安全風險的攻擊者，能以目前使用者的權限層級執行任意程式碼。如果目前的使用者以系統管理的使用者權限登入，攻擊者接下來就能安裝程式，並檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms14-065">MS14-065</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 積存安全性更新 (3003057)<br />
<br />
</strong>本資訊安全更新可解決 Internet Explorer 中十七項未公開報告的資訊安全風險。其中最嚴重的資訊安全風險，可能在使用者以 Internet Explorer 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用這些資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms14-066">MS14-066</a></td>
<td style="border:1px solid black;"><strong>Schannel 中的資訊安全風險可能會允許遠端執行程式碼 (2992611)<br />
<br />
</strong>這個資訊安全更新可解決 Windows 中 Microsoft 安全通道 (Schannel) 資訊安全套件一項未公開報告的資訊安全風險。如果攻擊者傳送蓄意製作的封包到 Windows 伺服器，這項資訊安全風險可允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms14-067">MS14-067</a></td>
<td style="border:1px solid black;"><strong>XML Core Services 中的資訊安全風險可能會允許遠端執行程式碼 (2993958)</strong><br />
<br />
這個安全性更新可解決 Microsoft Windows 中一項未公開報告的弱點。如果登入的使用者造訪蓄意製作之網站，且該網站係透過 Internet Explorer 叫用 Microsoft XML Core Services (MSXML)，則此資訊安全風險可能會允許遠端執行程式碼。但是，攻擊者無法強迫使用者造訪這類網站，而是引誘使用者自行前往。一般的做法是設法讓使用者按一下電子郵件訊息或 Instant Messenger 要求中通往攻擊者網站的連結。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms14-068">MS14-068</a></td>
<td style="border:1px solid black;"><strong>Kerberos 中的資訊安全風險可能會允許權限提高 (3011780)<br />
</strong><br />
此資訊安全更新可解決 Microsoft Windows Kerberos KDC 中一項未公開報告的資訊安全風險，該資訊安全風險可允許攻擊者將未經授權的網域使用者帳戶權限，提高到網域管理員帳戶的權限。攻擊者可使用這些提高的權限入侵網域中的任何電腦，包括網域控制站。攻擊者必須擁有有效的網域認證，才能利用這項資訊安全風險。擁有具備網域認證之標準使用者帳戶的使用者可從遠端使用受影響的元件；僅具備本機帳戶認證的使用者無法使用。發行此資訊安全公告時，Microsoft 已發現有嘗試利用此資訊安全風險、有限且目標明確的攻擊。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms14-069">MS14-069</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 中的資訊安全風險可能會允許遠端執行程式碼 (3009710)<br />
<br />
</strong>此資訊安全更新可解決 Microsoft Office 中三項未公開報告的資訊安全風險。如果在受影響版本的 Microsoft Office 2007 中開啟蓄意製作的檔案，則這些資訊安全風險可能會允許遠端執行程式碼。成功利用此資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms14-070">MS14-070</a></td>
<td style="border:1px solid black;"><strong>TCP/IP 中的資訊安全風險可能會允許權限提高 (2989935)<br />
<br />
</strong>此資訊安全更新可解決在處理輸入/輸出控制 (IOCTL) 期間，TCP/IP 中發生的一項公開報告的資訊安全風險。如果攻擊者登入系統並執行蓄意製作的應用程式，則這個資訊安全風險可能允許權限提高。成功利用這個資訊安全風險的攻擊者，能以其他程序的權限層級執行任意程式碼。若此程序以系統管理員的權限執行，攻擊者便可安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms14-071">MS14-071</a></td>
<td style="border:1px solid black;"><strong>Windows 音訊服務中的資訊安全風險可能會允許權限提高 (3005607)<br />
<br />
</strong>這個資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果應用程式使用 Microsoft Windows 音訊服務，此資訊安全風險可能允許提高權限。此資訊安全風險本身不會允許執行任意程式碼。此資訊安全風險必須搭配其他允許遠端執行程式碼的資訊安全風險使用。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms14-072">MS14-072</a></td>
<td style="border:1px solid black;"><strong>.NET Framework 中的資訊安全風險可能會允許權限提高 (3005210)<br />
<br />
</strong>這個資訊安全更新可解決 Microsoft .NET Framework 中一項未公開報告的資訊安全風險。如果攻擊者將蓄意製作的資料傳送至受影響的工作站或使用 .NET Remoting 的伺服器，則此資訊安全風險可能會允許權限提高。只有經蓄意製作以使用 .NET Remoting 的自訂應用程式會使系統受到此資訊安全風險的影響。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms14-073">MS14-073</a></td>
<td style="border:1px solid black;"><strong>Microsoft SharePoint Foundation 中的資訊安全風險可能會允許權限提高 (3000431)<br />
<br />
</strong>此資訊安全更新可解決 Microsoft SharePoint Server 中一項未公開報告的資訊安全風險。成功利用此資訊安全風險且經過驗證的攻擊者，能在目前的 SharePoint 網站上以使用者的權限層級執行任意程式碼。在網頁式攻擊案例中，攻擊者可能架設一個為了利用這些資訊安全風險而蓄意製作的網站，然後引誘使用者檢視該網站。攻擊者也可能利用受侵害的網站，以及接受或裝載使用者提供內容或廣告的網站。這些網站可能含有蓄意製作以利用此類資訊安全風險的內容。但是，攻擊者無法強迫使用者檢視受攻擊者控制的內容，而是引誘使用者自行前往。一般的做法是設法讓使用者點選電子郵件訊息或 Instant Messenger 中通往攻擊者網站的連結，或設法讓他們開啟經由電子郵件傳送的附件。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft 伺服器軟體</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms14-074">MS14-074</a></td>
<td style="border:1px solid black;"><strong>遠端桌面通訊協定中的資訊安全風險可能會允許略過資訊安全功能 (3003743)<br />
<br />
</strong>這個資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。遠端桌面通訊協定 (RDP) 無法正確地記錄稽核事件時，這個資訊安全風險可能允許略過資訊安全功能。依照預設，RDP 並未在任何 Windows 作業系統上啟用。未啟用的 RDP 的系統則無風險。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
資訊安全功能略過</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">MS14-075</td>
<td style="border:1px solid black;">發行日期未定</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms14-076">MS14-076</a></td>
<td style="border:1px solid black;"><strong>Internet Information Services (IIS) 中的資訊安全風險可能會允許略過資訊安全功能 (2982998)<br />
<br />
</strong>此資訊安全更新解決了 Microsoft Internet Information Services (IIS) 中一項未公開報告的資訊安全風險，該資訊安全風險可略過「IP 和網域限制」資訊安全功能。若成功利用此資訊安全風險，可能會導致限制或封鎖網域的用戶端無法存取限制的網路資源。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
資訊安全功能略過</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms14-077">MS14-077</a></td>
<td style="border:1px solid black;"><strong>Active Directory Federation Services 中的資訊安全風險可能允許資訊洩漏 (3003381)<br />
<br />
</strong>這個資訊安全更新可解決 Active Directory Federation Services (AD FS) 中一項未公開報告的資訊安全風險。如果使用者從應用程式登出後持續開啟瀏覽器，且攻擊者在使用者登出後立即在瀏覽器中重新開啟應用程式。則此資訊安全風險可能會允許資訊洩露。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
資訊洩漏</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms14-078">MS14-078</a></td>
<td style="border:1px solid black;"><strong>IME (日文) 中的資訊安全風險可能會允許權限提高 (2992719)<br />
<br />
</strong>這個資訊安全更新可解決 Microsoft 輸入法 (IME) (日文) 中一項未公開報告的資訊安全風險。此資訊安全風險可能會讓已安裝受影響版本的 Microsoft IME (日文) 系統內根據應用程式沙箱原則的沙箱逸出。成功利用此資訊安全風險的攻擊者可逸出具有資訊安全風險的應用程式之沙箱，並且以登入的使用者權限存取受影響的系統。如果以系統管理權限登入受影響的系統，攻擊者便可安裝程式；檢視、變更或刪除資料；或以完整的系統管理權限建立新帳戶。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">中度</a><br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms14-079">MS14-079</a></td>
<td style="border:1px solid black;"><strong>核心模式驅動程式中的資訊安全風險可能會允許阻斷服務 (3002885)<br />
<br />
</strong>這個資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果攻擊者在網路共用上放置蓄意製作的 TrueType 字型，且使用者後續在 Windows 檔案總管中的該處瀏覽，則此資訊安全風險可能會允許阻斷服務 (DoS)。在網頁式攻擊的案例中，攻擊者可架設一個網站，並在其中包含用來利用此資訊安全風險的網頁。此外，受侵害的網站以及接受或存放使用者提供之內容或廣告的網站裡，也可能包含蓄意製作以利用本資訊安全風險的內容。但是，攻擊者無法強迫使用者造訪這類網站，而是引誘使用者自行前往。一般的做法是設法讓使用者點選電子郵件或 Instant Messenger 訊息中連往攻擊者網站的連結。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">中度</a><br />
阻斷服務 (DoS)</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
 
  
弱點索引  
--------
  
下表提供本月所述每個弱點的利用性評估。會依序按公告編號及 CVE ID 的順序列出資訊安全風險。只會包含公告中嚴重性等級為「重大」或「重要」的資訊安全風險。
  
您可以運用此表格，針對您可能需要安裝的每一項資訊安全更新，瞭解資訊安全風險在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務 (DoS) 的可能性。請根據您特定的組態設定，檢閱下列各項評估，決定部署本月份更新的優先次序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](https://technet.microsoft.com/zh-tw/security/cc998259)。
  
在下方欄位中，「最新軟體版本」意指受影響軟體，「較舊軟體版本」意指受影響軟體所有較舊的支援版本，如公告中的「受影響的軟體」或「不受影響的軟體」表格裡所示。

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
**弱點標題**

</td>
<td style="border:1px solid black;">
**CVE ID**

</td>
<td style="border:1px solid black;" colspan="2">
**最新軟體版本的資訊安全風險評估**

</td>
<td style="border:1px solid black;" colspan="2">
**較舊軟體版本的資訊安全風險評估**

</td>
<td style="border:1px solid black;">
**阻斷服務 (DoS) 資訊安全風險評估**

</td>
<td style="border:1px solid black;">
**主要重點**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-064](https://technet.microsoft.com/zh-tw/library/security/ms14-064)

</td>
<td style="border:1px solid black;">
Windows OLE Automation 陣列遠端執行程式碼資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6332](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6332)

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
(無)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-064](https://technet.microsoft.com/zh-tw/library/security/ms14-064)

</td>
<td style="border:1px solid black;">
Windows OLE 遠端執行程式碼資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6352](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6352)

</td>
<td style="border:1px solid black;" colspan="2">
0 - 已偵測到利用

</td>
<td style="border:1px solid black;" colspan="2">
0 - 已偵測到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft 已發現有嘗試利用此資訊安全風險的有限攻擊。  
此資訊安全風險最初是在 Microsoft 資訊安全摘要報告 [3010060](https://technet.microsoft.com/zh-tw/library/security/3010060.aspx) 中提出。

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-065](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-4143](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4143)

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
(無)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-065](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Internet Explorer 剪貼簿資訊洩漏資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6323](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6323)

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
這是一個資訊洩漏的資訊安全風險。

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-065](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6337](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6337)

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
(無)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-065](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Internet Explorer ASLR 略過資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6339](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6339)

</td>
<td style="border:1px solid black;" colspan="2">
不受影響

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
這是一個資訊安全功能略過之資訊安全風險。

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-065](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Internet Explorer 跨網域資訊洩漏資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6340](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6340)

</td>
<td style="border:1px solid black;" colspan="2">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;" colspan="2">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
這是一個資訊洩漏的資訊安全風險。

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-065](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6341](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6341)

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
(無)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-065](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6342](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6342)

</td>
<td style="border:1px solid black;" colspan="2">
不受影響

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
(無)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-065](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6343](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6343)

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
(無)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-065](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6344](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6344)

</td>
<td style="border:1px solid black;" colspan="2">
不受影響

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
(無)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-065](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Internet Explorer 跨網域資訊洩漏資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6345](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6345)

</td>
<td style="border:1px solid black;" colspan="2">
不受影響

</td>
<td style="border:1px solid black;" colspan="2">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
這是一個資訊洩漏的資訊安全風險。

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-065](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Internet Explorer 跨網域資訊洩漏資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6346](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6346)

</td>
<td style="border:1px solid black;" colspan="2">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;" colspan="2">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
這是一個資訊洩漏的資訊安全風險。

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-065](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6347](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6347)

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;" colspan="2">
不受影響

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
(無)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-065](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6348](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6348)

</td>
<td style="border:1px solid black;" colspan="2">
不受影響

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
(無)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-065](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Internet Explorer 權限提高資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6349](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6349)

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
這是權限提高的資訊安全風險。

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-065](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Internet Explorer 權限提高資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6350](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6350)

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
這是權限提高的資訊安全風險。

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-065](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6351](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6351)

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
(無)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-065](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6353](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6353)

</td>
<td style="border:1px solid black;" colspan="2">
不受影響

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
(無)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-066](https://technet.microsoft.com/zh-tw/library/security/ms14-066)

</td>
<td style="border:1px solid black;">
Microsoft Schannel 遠端執行程式碼資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6321](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6321)

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
永久

</td>
<td style="border:1px solid black;">
(無)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-067](https://technet.microsoft.com/zh-tw/library/security/ms14-067)

</td>
<td style="border:1px solid black;">
MSXML 遠端執行程式碼資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-4118](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4118)

</td>
<td style="border:1px solid black;" colspan="2">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;" colspan="2">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
(無)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-068](https://technet.microsoft.com/zh-tw/library/security/ms14-068)

</td>
<td style="border:1px solid black;">
Kerberos 總和檢查碼資訊安全風險

</td>
<td style="border:1px solid black;" colspan="2">
[CVE-2014-6324](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6324)

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
0 - 已偵測到利用

</td>
<td style="border:1px solid black;" colspan="2">
不適用

</td>
<td style="border:1px solid black;">
這是權限提高的資訊安全風險。  
Microsoft 已發現有嘗試利用此資訊安全風險、有限且目標明確的攻擊。

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-069](https://technet.microsoft.com/zh-tw/library/security/ms14-069)

</td>
<td style="border:1px solid black;">
Microsoft Office 重複刪除遠端執行程式碼資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6333](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6333)

</td>
<td style="border:1px solid black;" colspan="2">
不受影響

</td>
<td style="border:1px solid black;" colspan="2">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
(無)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-069](https://technet.microsoft.com/zh-tw/library/security/ms14-069)

</td>
<td style="border:1px solid black;">
Microsoft Office 錯誤索引遠端執行程式碼資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6334](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6334)

</td>
<td style="border:1px solid black;" colspan="2">
不受影響

</td>
<td style="border:1px solid black;" colspan="2">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
(無)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-069](https://technet.microsoft.com/zh-tw/library/security/ms14-069)

</td>
<td style="border:1px solid black;">
Microsoft Office 無效指標遠端執行程式碼資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6335](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6335)

</td>
<td style="border:1px solid black;" colspan="2">
不受影響

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
(無)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-070](https://technet.microsoft.com/zh-tw/library/security/ms14-070)

</td>
<td style="border:1px solid black;">
TCP/IP 權限提高資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-4076](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4076)

</td>
<td style="border:1px solid black;" colspan="2">
不受影響

</td>
<td style="border:1px solid black;" colspan="2">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
永久

</td>
<td style="border:1px solid black;">
這是權限提高的資訊安全風險。

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-071](https://technet.microsoft.com/zh-tw/library/security/ms14-071)

</td>
<td style="border:1px solid black;">
Windows 音訊服務資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6322](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6322)

</td>
<td style="border:1px solid black;" colspan="2">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;" colspan="2">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
這是權限提高的資訊安全風險。

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-072](https://technet.microsoft.com/zh-tw/library/security/ms14-072)

</td>
<td style="border:1px solid black;">
TypeFilterLevel 資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-4149](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4149)

</td>
<td style="border:1px solid black;" colspan="2">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;" colspan="2">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
這是權限提高的資訊安全風險。

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-073](https://technet.microsoft.com/zh-tw/library/security/ms14-073)

</td>
<td style="border:1px solid black;">
SharePoint 權限提高資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-4116](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4116)

</td>
<td style="border:1px solid black;" colspan="2">
不受影響

</td>
<td style="border:1px solid black;" colspan="2">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
這是權限提高的資訊安全風險。

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-074](https://technet.microsoft.com/zh-tw/library/security/ms14-074)

</td>
<td style="border:1px solid black;">
遠端桌面通訊協定 (RDP) 無法稽核資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6318](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6318)

</td>
<td style="border:1px solid black;" colspan="2">
3 - 不太可能遭到利用

</td>
<td style="border:1px solid black;" colspan="2">
3 - 不太可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
這是一個資訊安全功能略過之資訊安全風險。

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-076](https://technet.microsoft.com/zh-tw/library/security/ms14-076)

</td>
<td style="border:1px solid black;">
IIS 資訊安全功能略過資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-4078](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4078)

</td>
<td style="border:1px solid black;" colspan="2">
3 - 不太可能遭到利用

</td>
<td style="border:1px solid black;" colspan="2">
3 - 不太可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
這是一個資訊安全功能略過之資訊安全風險。

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-077](https://technet.microsoft.com/zh-tw/library/security/ms14-077)

</td>
<td style="border:1px solid black;">
Active Directory Federation Services 資訊洩露資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6331](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6331)

</td>
<td style="border:1px solid black;" colspan="2">
3 - 不太可能遭到利用

</td>
<td style="border:1px solid black;" colspan="2">
3 - 不太可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
這是一個資訊洩漏的資訊安全風險。

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-078](https://technet.microsoft.com/zh-tw/library/security/ms14-078)

</td>
<td style="border:1px solid black;">
Microsoft IME (日文) 權限提高資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-4077](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4077)

</td>
<td style="border:1px solid black;" colspan="2">
不受影響

</td>
<td style="border:1px solid black;" colspan="2">
0 - 已偵測到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
這是權限提高的資訊安全風險。

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-079](https://technet.microsoft.com/zh-tw/library/security/ms14-079)

</td>
<td style="border:1px solid black;">
Windows 核心模式驅動程式中阻斷服務 (DoS) 資訊安全風險

</td>
<td style="border:1px solid black;">
[CVE-2014-6317](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6317)

</td>
<td style="border:1px solid black;" colspan="2">
3 - 不太可能遭到利用

</td>
<td style="border:1px solid black;" colspan="2">
3 - 不太可能遭到利用

</td>
<td style="border:1px solid black;">
永久

</td>
<td style="border:1px solid black;">
這是一項阻斷服務 (DoS) 的資訊安全風險。

</td>
</tr>
</table>
 
 

受影響的軟體
------------

下表依據主要的軟體類別和嚴重性依序列出公告。

請用這些表格來瞭解可能需要安裝的安全性更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的安全性更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。

**注意**：一項資訊安全風險，可能需要安裝數個資訊安全更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。

### Windows 作業系統與元件

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://technet.microsoft.com/zh-tw/library/security/ms14-064)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://technet.microsoft.com/zh-tw/library/security/ms14-066)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://technet.microsoft.com/zh-tw/library/security/ms14-067)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://technet.microsoft.com/zh-tw/library/security/ms14-068)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://technet.microsoft.com/zh-tw/library/security/ms14-070)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://technet.microsoft.com/zh-tw/library/security/ms14-071)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://technet.microsoft.com/zh-tw/library/security/ms14-072)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://technet.microsoft.com/zh-tw/library/security/ms14-074)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://technet.microsoft.com/zh-tw/library/security/ms14-076)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://technet.microsoft.com/zh-tw/library/security/ms14-077)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://technet.microsoft.com/zh-tw/library/security/ms14-078)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://technet.microsoft.com/zh-tw/library/security/ms14-079)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**普通**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
[**普通**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**普通**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3006226)  
(重大)

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3003057)  
(中度)  
Internet Explorer 7  
(3003057)  
(中度)  
Internet Explorer 8  
(3003057)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2992611)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3011780)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2989935)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2978114)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2978124)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2991963)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3002885)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3006226)  
(重大)

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3003057)  
(中度)  
Internet Explorer 7  
(3003057)  
(中度)  
Internet Explorer 8  
(3003057)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2992611)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3011780)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2989935)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2978124)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2991963)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3002885)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems  
(3006226)  
(重大)

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3003057)  
(中度)  
Internet Explorer 7  
(3003057)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems  
(2992611)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems  
(3011780)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems  
(2989935)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2978124)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems  
(2991963)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems  
(3002885)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://technet.microsoft.com/zh-tw/library/security/ms14-064)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://technet.microsoft.com/zh-tw/library/security/ms14-066)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://technet.microsoft.com/zh-tw/library/security/ms14-067)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://technet.microsoft.com/zh-tw/library/security/ms14-068)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://technet.microsoft.com/zh-tw/library/security/ms14-070)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://technet.microsoft.com/zh-tw/library/security/ms14-071)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://technet.microsoft.com/zh-tw/library/security/ms14-072)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://technet.microsoft.com/zh-tw/library/security/ms14-074)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://technet.microsoft.com/zh-tw/library/security/ms14-076)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://technet.microsoft.com/zh-tw/library/security/ms14-077)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://technet.microsoft.com/zh-tw/library/security/ms14-078)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://technet.microsoft.com/zh-tw/library/security/ms14-079)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**普通**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**普通**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3006226)  
(重大)  
Windows Vista Service Pack 2  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3003057)  
(重大)  
Internet Explorer 8  
(3003057)  
(重大)  
Internet Explorer 9  
(3003057)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2992611)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2993958)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3011780)  
(無嚴重性等級)<sup>[1]</sup>

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2978116)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2991963)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3002885)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3006226)  
(重大)  
Windows Vista x64 Edition Service Pack 2  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3003057)  
(重大)  
Internet Explorer 8  
(3003057)  
(重大)  
Internet Explorer 9  
(3003057)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2992611)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2993958)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3011780)  
(無嚴重性等級)<sup>[1]</sup>

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2978116)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2991963)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3002885)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://technet.microsoft.com/zh-tw/library/security/ms14-064)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://technet.microsoft.com/zh-tw/library/security/ms14-066)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://technet.microsoft.com/zh-tw/library/security/ms14-067)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://technet.microsoft.com/zh-tw/library/security/ms14-068)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://technet.microsoft.com/zh-tw/library/security/ms14-070)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://technet.microsoft.com/zh-tw/library/security/ms14-071)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://technet.microsoft.com/zh-tw/library/security/ms14-072)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://technet.microsoft.com/zh-tw/library/security/ms14-074)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://technet.microsoft.com/zh-tw/library/security/ms14-076)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://technet.microsoft.com/zh-tw/library/security/ms14-077)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://technet.microsoft.com/zh-tw/library/security/ms14-078)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://technet.microsoft.com/zh-tw/library/security/ms14-079)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**普通**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**普通**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**普通**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3006226)  
(重大)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3003057)  
(中度)  
Internet Explorer 8  
(3003057)  
(中度)  
Internet Explorer 9  
(3003057)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2992611)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3011780)  
(重大)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2978116)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Active Directory Federation Services 2.0  
(3003381)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2991963)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3002885)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3006226)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3003057)  
(中度)  
Internet Explorer 8  
(3003057)  
(中度)  
Internet Explorer 9  
(3003057)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2992611)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3011780)  
(重大)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2978116)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Active Directory Federation Services 2.0  
(3003381)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2991963)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3002885)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3006226)  
(重大)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3003057)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2992611)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3011780)  
(重大)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2978116)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2991963)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3002885)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://technet.microsoft.com/zh-tw/library/security/ms14-064)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://technet.microsoft.com/zh-tw/library/security/ms14-066)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://technet.microsoft.com/zh-tw/library/security/ms14-067)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://technet.microsoft.com/zh-tw/library/security/ms14-068)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://technet.microsoft.com/zh-tw/library/security/ms14-070)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://technet.microsoft.com/zh-tw/library/security/ms14-071)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://technet.microsoft.com/zh-tw/library/security/ms14-072)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://technet.microsoft.com/zh-tw/library/security/ms14-074)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://technet.microsoft.com/zh-tw/library/security/ms14-076)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://technet.microsoft.com/zh-tw/library/security/ms14-077)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://technet.microsoft.com/zh-tw/library/security/ms14-078)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://technet.microsoft.com/zh-tw/library/security/ms14-079)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**普通**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**普通**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3006226)  
(重大)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3003057)  
(重大)  
Internet Explorer 9  
(3003057)  
(重大)  
Internet Explorer 10  
(3003057)  
(重大)  
Internet Explorer 11  
(3003057)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2992611)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2993958)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3011780)  
(無嚴重性等級)<sup>[1]</sup>

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2978120)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2991963)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3002885)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3006226)  
(重大)  
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3003057)  
(重大)  
Internet Explorer 9  
(3003057)  
(重大)  
Internet Explorer 10  
(3003057)  
(重大)  
Internet Explorer 11  
(3003057)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2992611)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2993958)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3011780)  
(無嚴重性等級)<sup>[1]</sup>

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2978120)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2991963)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3002885)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://technet.microsoft.com/zh-tw/library/security/ms14-064)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://technet.microsoft.com/zh-tw/library/security/ms14-066)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://technet.microsoft.com/zh-tw/library/security/ms14-067)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://technet.microsoft.com/zh-tw/library/security/ms14-068)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://technet.microsoft.com/zh-tw/library/security/ms14-070)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://technet.microsoft.com/zh-tw/library/security/ms14-071)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://technet.microsoft.com/zh-tw/library/security/ms14-072)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://technet.microsoft.com/zh-tw/library/security/ms14-074)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://technet.microsoft.com/zh-tw/library/security/ms14-076)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://technet.microsoft.com/zh-tw/library/security/ms14-077)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://technet.microsoft.com/zh-tw/library/security/ms14-078)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://technet.microsoft.com/zh-tw/library/security/ms14-079)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**普通**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**普通**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**普通**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3006226)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3003057)  
(中度)  
Internet Explorer 9  
(3003057)  
(中度)  
Internet Explorer 10  
(3003057)  
(中度)  
Internet Explorer 11  
(3003057)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2992611)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3011780)  
(重大)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2978120)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Active Directory Federation Services 2.0  
(3003381)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2991963)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3002885)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3006226)  
(重大)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3003057)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2992611)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3011780)  
(重大)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2978120)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2991963)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3002885)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://technet.microsoft.com/zh-tw/library/security/ms14-064)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://technet.microsoft.com/zh-tw/library/security/ms14-066)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://technet.microsoft.com/zh-tw/library/security/ms14-067)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://technet.microsoft.com/zh-tw/library/security/ms14-068)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://technet.microsoft.com/zh-tw/library/security/ms14-070)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://technet.microsoft.com/zh-tw/library/security/ms14-071)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://technet.microsoft.com/zh-tw/library/security/ms14-072)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://technet.microsoft.com/zh-tw/library/security/ms14-074)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://technet.microsoft.com/zh-tw/library/security/ms14-076)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://technet.microsoft.com/zh-tw/library/security/ms14-077)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://technet.microsoft.com/zh-tw/library/security/ms14-078)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://technet.microsoft.com/zh-tw/library/security/ms14-079)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**普通**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 32 位元系統

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3006226)  
(重大)  
Windows 8 32 位元系統  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3003057)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(2992611)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(2993958)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3011780)  
(無嚴重性等級)<sup>[1]</sup>

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2978121)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978127)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Internet Information Services 8.0  
(2982998)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3002885)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(3006226)  
(重大)  
適用於 x64 型系統的 Windows 8  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3003057)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(2992611)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(2993958)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(3011780)  
(無嚴重性等級)<sup>[1]</sup>

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2978121)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978127)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Internet Information Services 8.0  
(2982998)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(3002885)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3006226)  
(重大)  
Windows 8.1 32 位元系統  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3003057)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(2992611)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(2993958)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3011780)  
(無嚴重性等級)<sup>[1]</sup>

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2978122)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978126)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Internet Information Services 8.5  
(2982998)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3002885)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3006226)  
(重大)  
適用於 x64 型系統的 Windows 8.1  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3003057)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(2992611)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(2993958)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3011780)  
(無嚴重性等級)<sup>[1]</sup>

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2978122)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978126)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Internet Information Services 8.5  
(2982998)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3002885)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://technet.microsoft.com/zh-tw/library/security/ms14-064)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://technet.microsoft.com/zh-tw/library/security/ms14-066)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://technet.microsoft.com/zh-tw/library/security/ms14-067)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://technet.microsoft.com/zh-tw/library/security/ms14-068)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://technet.microsoft.com/zh-tw/library/security/ms14-070)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://technet.microsoft.com/zh-tw/library/security/ms14-071)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://technet.microsoft.com/zh-tw/library/security/ms14-072)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://technet.microsoft.com/zh-tw/library/security/ms14-074)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://technet.microsoft.com/zh-tw/library/security/ms14-076)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://technet.microsoft.com/zh-tw/library/security/ms14-077)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://technet.microsoft.com/zh-tw/library/security/ms14-078)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://technet.microsoft.com/zh-tw/library/security/ms14-079)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**普通**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**普通**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3006226)  
(重大)  
Windows Server 2012  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3003057)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2992611)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3011780)  
(重大)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2978121)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978127)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Internet Information Services 8.0  
(2982998)  
(重要)

</td>
<td style="border:1px solid black;">
Active Directory Federation Services 2.1  
(3003381)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3002885)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3006226)  
(重大)  
Windows Server 2012 R2  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3003057)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2992611)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3011780)  
(重大)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2978122)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978126)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Internet Information Services 8.5  
(2982998)  
(重要)

</td>
<td style="border:1px solid black;">
Active Directory Federation Services 3.0  
(3003381)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3002885)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://technet.microsoft.com/zh-tw/library/security/ms14-064)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://technet.microsoft.com/zh-tw/library/security/ms14-066)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://technet.microsoft.com/zh-tw/library/security/ms14-067)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://technet.microsoft.com/zh-tw/library/security/ms14-068)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://technet.microsoft.com/zh-tw/library/security/ms14-070)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://technet.microsoft.com/zh-tw/library/security/ms14-071)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://technet.microsoft.com/zh-tw/library/security/ms14-072)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://technet.microsoft.com/zh-tw/library/security/ms14-074)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://technet.microsoft.com/zh-tw/library/security/ms14-076)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://technet.microsoft.com/zh-tw/library/security/ms14-077)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://technet.microsoft.com/zh-tw/library/security/ms14-078)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://technet.microsoft.com/zh-tw/library/security/ms14-079)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
[**普通**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Windows RT  
(3006226)  
(重大)  
Windows RT  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3003057)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT  
(2992611)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT  
(2993958)  
(重大)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978127)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT  
(3002885)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3006226)  
(重大)  
Windows RT 8.1  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3003057)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2992611)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2993958)  
(重大)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1/4.5.2  
(2978126)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3002885)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Server Core 安裝選項**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://technet.microsoft.com/zh-tw/library/security/ms14-064)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://technet.microsoft.com/zh-tw/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://technet.microsoft.com/zh-tw/library/security/ms14-066)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://technet.microsoft.com/zh-tw/library/security/ms14-067)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://technet.microsoft.com/zh-tw/library/security/ms14-068)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://technet.microsoft.com/zh-tw/library/security/ms14-070)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://technet.microsoft.com/zh-tw/library/security/ms14-071)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://technet.microsoft.com/zh-tw/library/security/ms14-072)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://technet.microsoft.com/zh-tw/library/security/ms14-074)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://technet.microsoft.com/zh-tw/library/security/ms14-076)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://technet.microsoft.com/zh-tw/library/security/ms14-077)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://technet.microsoft.com/zh-tw/library/security/ms14-078)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://technet.microsoft.com/zh-tw/library/security/ms14-079)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**普通**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**普通**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3006226)  
(重大)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2992611)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3011780)  
(重大)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2991963)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3002885)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3006226)  
(重大)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝) (2992611)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝) (2993958)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3011780)  
(重大)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2991963)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3002885)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3006226)  
(重大)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(2992611)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3011780)  
(重大)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2978120)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(2991963)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3002885)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3006226)  
(重大)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(2992611)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝) (2993958)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3011780)  
(重大)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2978121)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978127)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝) (3003743)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝) (3002885)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3006226)  
(重大)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(2992611)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3011780)  
(重大)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2978122)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978126)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Active Directory Federation Services 3.0  
(3003381)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3002885)  
(中度)

</td>
</tr>
</table>
 
**MS14-064、MS14-065 和 MS14-067 注意事項**

Windows Technical Preview 和 Windows Server Technical Preview 會受影響。建議執行這些作業系統的客戶套用更新，您可以透過 [Windows Update](https://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-tw) 取得更新。

**MS14-068 注意事項**

Windows Technical Preview 和 Windows Server Technical Preview 會受影響。 建議執行這些作業系統的客戶套用更新，您可以透過 [Windows Update](https://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-tw) 取得更新。

<sup>[1]</sup>嚴重性等級不適用此作業系統，因為不會出現此公告中指出的資訊安全風險。此更新提供其他[深度防禦](https://technet.microsoft.com/zh-tw/library/security/dn848375.aspx)強化，但無法解決任何已知的資訊安全風險。

**MS14-078 注意事項**

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
[**MS14-069**](https://technet.microsoft.com/zh-tw/library/security/ms14-069)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://technet.microsoft.com/zh-tw/library/security/ms14-078)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**普通**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Word 2007 Service Pack 3  
(2899527)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 IME (日文)  
(2889913)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**其他 Microsoft Office 軟體**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-069**](https://technet.microsoft.com/zh-tw/library/security/ms14-069)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://technet.microsoft.com/zh-tw/library/security/ms14-078)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2899553)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 相容性套件 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 相容性套件 Service Pack 3  
(2899526)  
(重要)

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
</table>
 
**MS14-078 注意事項**

本公告會跨越多個軟體類別。請參閱本節其他資料表，以了解其他受影響的軟體。

 

### Microsoft 伺服器軟體

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
[**MS14-073**](https://technet.microsoft.com/zh-tw/library/security/ms14-073)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 2  
(2889838)  
(重要)

</td>
</tr>
</table>
 
 

偵測與部署工具及指南
--------------------

有幾項資源可協助系統管理員部署資訊安全更新。

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，查看是否遺漏資訊安全更新及一般資訊安全設定錯誤的狀況。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 可協助系統管理員散佈資訊安全更新。

應用程式相容性工具組隨附的 Update Compatibility Evaluator 元件可針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

如需上述工具以及其他可使用工具的詳細資訊，請參閱 [IT專業人員的資訊安全工具](https://technet.microsoft.com/zh-tw/security/cc297183)。

感謝
----

Microsoft 了解資訊安全業界所做的努力，其盡責地透露資訊安全風險來協助我們保護客戶。請參閱[認可](https://technet.microsoft.com/zh-tw/library/security/dn820091.aspx) (英文) 以取得詳細資訊。

其他資訊
--------

### Microsoft Windows 惡意軟體移除工具 (英文)

針對每個月第二個星期二發行的公告，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 及下載中心發行更新版本的 Microsoft Windows 惡意軟體移除工具。不定期資訊安全公告發行不提供更新版本的 Microsoft Windows 惡意軟體移除工具。

### MU、WU 及 WSUS 上的非資訊安全更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](https://support.microsoft.com/kb/894199/zh-tw)：Software Update Services 與 Windows Server Update Services 的說明內容有所變動。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](https://technet.microsoft.com/zh-tw/windowsserver/bb332157.aspx)。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的安全性保護，Microsoft 將在每月發行安全性更新之前，提前向重要安全性軟體提供者提供弱點資訊。安全性軟體提供者可利用此弱點資訊，透過其安全性軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](https://technet.microsoft.com/zh-tw/security/dn467918) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

### 安全性策略與社群

**更新程式管理策略**

[更新管理安全性指南](https://technet.microsoft.com/zh-tw/library/bb466251.aspx) (英文) 提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他資訊安全問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](https://www.microsoft.com/downloads/results.aspx?displaylang=zh-tw&freetext=security%20update)取得，您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](https://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-tw) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](https://support.microsoft.com/kb/913086/zh-tw)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](https://technet.microsoft.com/zh-tw/security/cc136632.aspx)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

### 支援

所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](https://go.microsoft.com/fwlink/?linkid=21742)。

IT 專業人員的資訊安全解決方案：[TechNet 資訊安全疑難排解與支援](https://technet.microsoft.com/zh-tw/security/bb980617)

協助保護您的 Windows 電腦免於病毒和惡意軟體攻擊：[病毒解決方案與資訊安全中心](https://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-tw)

您所在國家/地區的當地支援：[國際支援](https://support.microsoft.com/common/international.aspx?ln=zh-tw)

### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

### 日期

-   V1.0 (2014 年 11 月 11 日)：公告摘要發行。
-   V2.0 (2014 年 11 月 18 日)： 修訂佈告摘要，是為了記錄不定期發行的 MS14-068 以及 MS14-066 安全公告，宣佈重新提供執行 Windows Server 2008 R2 和 Windows Server 2012 系統的 2992611 更新。

*頁面產生時間：2014-11-18 6:52Z-08:00。*
