---
TOCTitle: 'MS15-MAR'
Title: 2015 年 3 月份 Microsoft 安全性公告摘要
ms:assetid: 'ms15-mar'
ms:contentKeyID: 64978259
ms:date: '03/12/2015'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms15-mar(v=Security.10)'
---

2015 年 3 月份 Microsoft 安全性公告摘要
=======================================

發行日期：2015 年 3 月 10 日

**版本：** 1.0

此公告摘要列出 2015 年 3 月份所發行的安全性公告。

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
和資訊安全風險影響</strong></td>
<td style="border:1px solid black;"><strong>重新啟動需求</strong></td>
<td style="border:1px solid black;"><strong>已知<br />
問題</strong></td>
<td style="border:1px solid black;"><strong>受影響的<br />
軟體</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 積存安全性更新 (3032359)</strong> <br />
此安全性更新可解決 Internet Explorer 中的資訊安全風險。其中最嚴重的資訊安全風險，可能在使用者以 Internet Explorer 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用這些資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-019">MS15-019</a></td>
<td style="border:1px solid black;"><strong>VBScript 指令碼引擎中的資訊安全風險可能允許遠端執行程式碼 (3040297)</strong> <br />
這個資訊安全更新可解決 Microsoft Windows 的 VBScript 指令碼引擎中一項資訊安全風險。如果使用者造訪蓄意製作的網站，此資訊安全風險可能會允許遠端執行程式碼。成功利用這個弱點的攻擊者可以取得與目前使用者相同的使用者權限。如果使目前用者以系統管理的使用者權限登入，成功利用此資訊安全風險的攻擊者可以取得受影響系統的完整控制權。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-020">MS15-020</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows 中的資訊安全風險可能會允許遠端執行程式碼 (3041836)</strong><br />
此安全性更新可解決 Microsoft Windows 中的資訊安全風險。如果攻擊者成功引誘使用者瀏覽蓄意製作的網站、開啟蓄意製作的檔案，或在包含蓄意製作的 DLL 檔案的工作目錄中開啟檔案，此資訊安全風險可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-021">MS15-021</a></td>
<td style="border:1px solid black;"><strong>Adobe 字型驅動程式中的資訊安全風險可能會允許遠端執行程式碼 (3032323)</strong> <br />
此安全性更新可解決 Microsoft Windows 中的資訊安全風險。其中最嚴重的資訊安全風險，可能會在使用者檢視蓄意製作的檔案或網站時，允許遠端執行程式碼。成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-022">MS15-022</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 的弱點可能會允許遠端執行程式碼 (3038999)</strong> <br />
此安全性更新可解決 Microsoft Office 中的資訊安全風險。如果使用者開啟蓄意製作的 Microsoft Office 檔案，最嚴重的資訊安全風險可能會允許遠端執行程式碼。成功利用這些資訊安全風險的攻擊者，能以目前使用者的權限層級執行任意程式碼。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/kb/3038999/zh-tw">3038999</a></td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft 伺服器軟體</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-023">MS15-023</a></td>
<td style="border:1px solid black;"><strong>核心模式驅動程式中的資訊安全風險可能會允許權限提高 (3034344) </strong><br />
此安全性更新可解決 Microsoft Windows 中的資訊安全風險。如果攻擊者登入系統並執行蓄意製作的應用程式以提高權限，則最嚴重的資訊安全風險可能會允許提高權限。接下來，攻擊者就能安裝程式，檢視、變更或刪除資料，或是建立具有完整系統管理權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-024">MS15-024</a></td>
<td style="border:1px solid black;"><strong>PNG 處理程序中的資訊安全風險可能會導致資訊洩漏 (3035132)</strong> <br />
此安全性更新可解決 Microsoft Windows 中的資訊安全風險。如果攻擊者引誘使用者瀏覽包含蓄意製作的 PNG 影像的網站，則此資訊安全風險可能會允許資訊洩漏。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
資訊洩漏</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-025">MS15-025</a></td>
<td style="border:1px solid black;"><strong>Windows 核心中的資訊安全風險可能會允許權限提高 (3038680)</strong> <br />
此安全性更新可解決 Microsoft Windows 中的資訊安全風險。如果攻擊者登入受影響的系統並執行蓄意製作的應用程式，則最嚴重的資訊安全風險可能會允許權限提高。成功利用此資訊安全風險的攻擊者可在已登入受影響系統的其他使用者帳戶的安全性內容中，執行任意程式碼。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或可能建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/kb/3038680/zh-tw">3038680</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-026">MS15-026</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange Server 中的資訊安全風險可能會允許提高權限 (3040856)</strong> <br />
此安全性更新可解決 Microsoft Exchange Server 中的資訊安全風險。如果使用者點選會將使用者帶到目標 Outlook Web App 網站之蓄意製作的 URL，則最嚴重的資訊安全風險可能會允許權限提高。攻擊者並不能強迫使用者造訪蓄意製作的網站，而是引誘使用者自行前往。一般的做法是設法讓使用者點選即時訊息或電子郵件訊息中連往攻擊者網站的連結，然後引誘他們點選蓄意製作的 URL。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">不需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Exchange</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-027">MS15-027</a></td>
<td style="border:1px solid black;"><strong>NETLOGON 中的資訊安全風險可能會允許詐騙 (3002657)</strong><br />
此安全性更新可解決 Microsoft Windows 中的資訊安全風險。如果登入加入網域之系統的攻擊者執行蓄意製作的應用程式，從而與其他加入網域之系統建立連線以模擬使用者或系統，則此資訊安全風險可能會允許詐騙。攻擊者必須登入加入網域的系統，並且能夠觀察網路流量。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
偽造</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-028">MS15-028</a></td>
<td style="border:1px solid black;"><strong>Windows 工作排程器中的資訊安全風險可能允許資訊安全功能略過 (3030377) </strong><br />
此安全性更新可解決 Microsoft Windows 中的資訊安全風險。此資訊安全風險可允許權限受限的使用者在受影響的系統上，利用工作排程器來執行他們無權執行的檔案。成功利用這項資訊安全風險的攻擊者可略過 ACL 檢查，並執行特殊權限的可執行檔。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
資訊安全功能略過</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-029">MS15-029</a></td>
<td style="border:1px solid black;"><strong>Windows Photo 解碼器元件中的資訊安全風險可能會允許資訊洩漏 (3035126)</strong> <br />
此安全性更新可解決 Microsoft Windows 中的資訊安全風險。如果使用者瀏覽的網站含有蓄意製作的 JPEG XR (.JXR) 影像，則此資訊安全風險便可能允許資訊洩漏。這個資訊安全風險不會直接允許攻擊者執行程式碼或提升使用權限，但能用來取得資訊，因而進一步破壞受影響系統。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
資訊洩漏</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-030">MS15-030</a></td>
<td style="border:1px solid black;"><strong>遠端桌面通訊協定中的資訊安全風險可能會允許阻斷服務 (DoS) (3039976)</strong><br />
此安全性更新可解決 Microsoft Windows 中的資訊安全風險。如果攻擊者建立多個無法正確釋放記憶體中物件的遠端桌面通訊協定 (RDP) 工作階段，此資訊安全風險可能會允許阻斷服務。依照預設，RDP 並未在任何 Windows 作業系統上啟用。未啟用 RDP 的系統都沒有受到弱點影響的風險。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
阻斷服務 (DoS)</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-031">MS15-031</a></td>
<td style="border:1px solid black;"><strong>Schannel 中的資訊安全風險可能允許資訊安全功能略過 (3046049)<br />
</strong>這個安全性更新可以解決 Microsoft Windows 中利用公開揭露之 FREAK 技術的資訊安全風險，這個業界普遍面臨的問題並不是只有 Windows 作業系統才會發生。資訊安全風險讓攔截式 (MiTM) 攻擊者可在 TLS 連線中強制將 RSA 金鑰的金鑰長度降級至「匯出」等級的長度。任何使用 Schannel 連接至內含不安全加密套件之遠端 TLS 伺服器的 Windows 系統都會受到影響。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
資訊安全功能略過</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/kb/3046049/zh-tw">3046049</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
資訊安全風險入侵指數  
--------------------
  
下表提供本月所述每個資訊安全風險的利用性評估。會依序按公告編號及 CVE ID 的順序列出資訊安全風險。只會包含公告中嚴重性等級為「重大」或「重要」的資訊安全風險。
  
**我該如何使用這個表格？**
  
您可以運用此表格，針對您可能需要安裝的每一項安全性更新，瞭解資訊安全風險在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務 (DoS) 的可能性。請根據您特定的組態設定，檢閱下列各項評估，決定部署本月份更新的優先次序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](http://technet.microsoft.com/zh-tw/security/cc998259)。
  
在下方欄位中，「最新軟體版本」意指受影響軟體，「較舊軟體版本」意指受影響軟體所有較舊的支援版本，如公告中的「受影響的軟體」或「不受影響的軟體」表格裡所示。
  
<p></p>
<table style="width:100%;">
<colgroup>
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告 ID</strong></td>
<td style="border:1px solid black;"><strong>資訊安全風險標題</strong></td>
<td style="border:1px solid black;"><strong>CVE ID</strong></td>
<td style="border:1px solid black;"><strong>最新軟體版本的<br />
資訊安全風險評估</strong></td>
<td style="border:1px solid black;"><strong>較早軟體版本的<br />
資訊安全風險評估</strong></td>
<td style="border:1px solid black;"><strong>阻絕服務<br />
資訊安全風險評估</strong></td>
<td style="border:1px solid black;"><strong>主要重點</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;">VBScript 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0032">CVE-2015-0032</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0056">CVE-2015-0056</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer 權限提高資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0072">CVE-2015-0072</a></td>
<td style="border:1px solid black;">0 - 已偵測到利用</td>
<td style="border:1px solid black;">0 - 已偵測到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">此資訊安全風險已經公開揭發。<br />
<br />
這是權限提高的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0099">CVE-2015-0099</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0100">CVE-2015-0100</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1622">CVE-2015 -1622</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1623">CVE-2015 -1623</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1624">CVE-2015 -1624</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1625">CVE-2015 -1625</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">此資訊安全風險已經公開揭發。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1626">CVE-2015 -1626</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer 權限提高資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1627">CVE-2015 -1627</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是權限提高的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1634">CVE-2015 -1634</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-019">MS15-019</a></td>
<td style="border:1px solid black;">VBScript 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0032">CVE-2015-0032</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-020">MS15-020</a></td>
<td style="border:1px solid black;">WTS 遠端執行程式碼資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0081">CVE-2015-0081</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-020">MS15-020</a></td>
<td style="border:1px solid black;">DLL 設置遠端執行程式碼資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0096">CVE-2015-0096</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-021">MS15-021</a></td>
<td style="border:1px solid black;">Adobe 字型驅動程式阻斷服務資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0074">CVE-2015-0074</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">這是一項阻斷服務 (DoS) 的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-021">MS15-021</a></td>
<td style="border:1px solid black;">Adobe 字型驅動程式資訊洩漏資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0087">CVE-2015-0087</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">這是一個資訊洩漏的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-021">MS15-021</a></td>
<td style="border:1px solid black;">Adobe 字型驅動程式遠端執行程式碼資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0088">CVE-2015-0088</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-021">MS15-021</a></td>
<td style="border:1px solid black;">Adobe 字型驅動程式資訊洩漏資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0089">CVE-2015-0089</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊洩漏的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-021">MS15-021</a></td>
<td style="border:1px solid black;">Adobe 字型驅動程式遠端執行程式碼資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0090">CVE-2015-0090</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-021">MS15-021</a></td>
<td style="border:1px solid black;">Adobe 字型驅動程式遠端執行程式碼資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0091">CVE-2015-0091</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-021">MS15-021</a></td>
<td style="border:1px solid black;">Adobe 字型驅動程式遠端執行程式碼資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0092">CVE-2015-0092</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-021">MS15-021</a></td>
<td style="border:1px solid black;">Adobe 字型驅動程式遠端執行程式碼資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0093">CVE-2015-0093</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-022">MS15-022</a></td>
<td style="border:1px solid black;">Microsoft Office 元件釋放後使用資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0085">CVE-2015-0085</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-022">MS15-022</a></td>
<td style="border:1px solid black;">Microsoft Office 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0086">CVE-2015-0086</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-022">MS15-022</a></td>
<td style="border:1px solid black;">Microsoft Word 本機區域遠端執行程式碼資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0097">CVE-2015-0097</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-022">MS15-022</a></td>
<td style="border:1px solid black;">Microsoft SharePoint XSS 資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1633">CVE-2015 -1633</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是權限提高的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-022">MS15-022</a></td>
<td style="border:1px solid black;">Microsoft SharePoint XSS 資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1636">CVE-2015 -1636</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是權限提高的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-023">MS15-023</a></td>
<td style="border:1px solid black;">Microsoft Windows 核心記憶體洩露資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0077">CVE-2015-0077</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊洩漏的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-023">MS15-023</a></td>
<td style="border:1px solid black;">Win32k 權限提高資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0078">CVE-2015-0078</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是權限提高的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-023">MS15-023</a></td>
<td style="border:1px solid black;">Microsoft Windows 核心記憶體洩露資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0094">CVE-2015-0094</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊洩漏的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-023">MS15-023</a></td>
<td style="border:1px solid black;">Microsoft Windows 核心記憶體洩露資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0095">CVE-2015-0095</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">這是一個資訊洩漏的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-024">MS15-024</a></td>
<td style="border:1px solid black;">格式錯誤的 PNG 剖析資訊洩漏資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0080">CVE-2015-0080</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊洩漏的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-025">MS15-025</a></td>
<td style="border:1px solid black;">登錄虛擬化權限提高資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0073">CVE-2015-0073</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是權限提高的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-025">MS15-025</a></td>
<td style="border:1px solid black;">模擬層級檢查權限提高資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0075">CVE-2015-0075</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是權限提高的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-026">MS15-026</a></td>
<td style="border:1px solid black;">OWA 修改 Canary 參數跨網站指令碼資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1628">CVE-2015 -1628</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是權限提高的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-026">MS15-026</a></td>
<td style="border:1px solid black;">ExchangeDLP 跨網站指令碼資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1629">CVE-2015 -1629</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是權限提高的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-026">MS15-026</a></td>
<td style="border:1px solid black;">稽核報告跨網站指令碼資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1630">CVE-2015 -1630</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是權限提高的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-026">MS15-026</a></td>
<td style="border:1px solid black;">Exchange 仿造會議邀請偽造資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1631">CVE-2015 -1631</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個偽造資訊安全風險</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-026">MS15-026</a></td>
<td style="border:1px solid black;">Exchange 錯誤訊息跨網站指令碼資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1632">CVE-2015 -1632</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是權限提高的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-027">MS15-027</a></td>
<td style="border:1px solid black;">NETLOGON 偽造資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0005">CVE-2015-0005</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個偽造資訊安全風險</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-028">MS15-028</a></td>
<td style="border:1px solid black;">工作排程器資訊安全功能略過資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0084">CVE-2015-0084</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊安全功能略過的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-029">MS15-029</a></td>
<td style="border:1px solid black;">JPEG XR 剖析器資訊洩漏資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0076">CVE-2015-0076</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊洩漏的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-030">MS15-030</a></td>
<td style="border:1px solid black;">遠端桌面通訊協定 (RDP) 阻斷服務資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0079">CVE-2015-0079</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一項阻斷服務 (DoS) 的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-031">MS15-031</a></td>
<td style="border:1px solid black;">Schannel 資訊安全功能略過資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1637">CVE-2015 -1637</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">此資訊安全風險已經公開揭發。<br />
<br />
這是一個資訊安全功能略過的資訊安全風險。</td>
</tr>
</tbody>
</table>
 

受影響的軟體
------------

下表依據主要的軟體類別和嚴重性依序列出公告。

請用這些表格來瞭解可能需要安裝的安全性更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的安全性更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。

**注意**：一項資訊安全風險，可能需要安裝數個資訊安全更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。

### Windows 作業系統及元件 (表格 2 之 1)

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-018**](https://technet.microsoft.com/zh-tw/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/zh-tw/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/zh-tw/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/zh-tw/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/zh-tw/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/zh-tw/library/security/ms15-024)

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
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3032359)  
(中度)  
Internet Explorer 7  
(3032359)  
(中度)  
Internet Explorer 8  
(3032359)  
(中度)

</td>
<td style="border:1px solid black;">
VBScript 5.6  
(3030403)  
(中度)  
VBScript 5.7  
(3030398)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3033889)  
(重大)  
Windows Server 2003 Service Pack 2  
(3039066)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3032323)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3032359)  
(中度)  
Internet Explorer 7  
(3032359)  
(中度)  
Internet Explorer 8  
(3032359)  
(中度)

</td>
<td style="border:1px solid black;">
VBScript 5.6  
(3030403)  
(中度)  
VBScript 5.7  
(3030398)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3033889)  
(重大)  
Windows Server 2003 x64 Edition Service Pack 2  
(3039066)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3032323)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Itanium 系統 (含 SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3032359)  
(中度)  
Internet Explorer 7  
(3032359)  
(中度)

</td>
<td style="border:1px solid black;">
VBScript 5.6  
(3030403)  
(中度)  
VBScript 5.7  
(3030398)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Itanium 系統 (含 SP2)  
(3033889)  
(重大)  
Windows Server 2003 Itanium 系統 (含 SP2)  
(3039066)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Itanium 系統 (含 SP2)  
(3032323)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Itanium 系統 (含 SP2)  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Itanium 系統 (含 SP2)  
(3035132)  
(重要)

</td>
</tr>
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
[**MS15-018**](https://technet.microsoft.com/zh-tw/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/zh-tw/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/zh-tw/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/zh-tw/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/zh-tw/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/zh-tw/library/security/ms15-024)

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
(3032359)  
(重大)  
Internet Explorer 8  
(3032359)  
(重大)  
Internet Explorer 9  
(3032359)  
(重大)

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3030398)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3033889)  
(重大)  
Windows Vista Service Pack 2  
(3039066)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3032323)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3032359)  
(重大)  
Internet Explorer 8  
(3032359)  
(重大)  
Internet Explorer 9  
(3032359)  
(重大)

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3030398)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3033889)  
(重大)  
Windows Vista x64 Edition Service Pack 2  
(3039066)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3032323)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3035132)  
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
[**MS15-018**](https://technet.microsoft.com/zh-tw/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/zh-tw/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/zh-tw/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/zh-tw/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/zh-tw/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/zh-tw/library/security/ms15-024)

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
(3032359)  
(中度)  
Internet Explorer 8  
(3032359)  
(中度)  
Internet Explorer 9  
(3032359)  
(中度)

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3030398)  
(中度)

</td>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2  
(3033889)  
(重大)  
32 位元系統的 Windows Server 2008 Service Pack 2  
(3039066)  
(重大)

</td>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2  
(3032323)  
(重大)

</td>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3032359)  
(中度)  
Internet Explorer 8  
(3032359)  
(中度)  
Internet Explorer 9  
(3032359)  
(中度)

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3030398)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3033889)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3039066)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3032323)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3032359)  
(中度)

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3030398)  
(中度)

</td>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2  
(3033889)  
(重大)  
Itanium 系統的 Windows Server 2008 Service Pack 2  
(3039066)  
(重大)

</td>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2  
(3032323)  
(重大)

</td>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2  
(3035132)  
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
[**MS15-018**](https://technet.microsoft.com/zh-tw/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/zh-tw/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/zh-tw/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/zh-tw/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/zh-tw/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/zh-tw/library/security/ms15-024)

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
(3032359)  
(重大)  
Internet Explorer 9  
(3032359)  
(重大)  
Internet Explorer 10  
(3032359)  
(重大)  
Internet Explorer 11  
(3032359)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3033889)  
(重大)  
Windows 7 32 位元系統 Service Pack 1  
(3039066)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3032323)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3032359)  
(重大)  
Internet Explorer 9  
(3032359)  
(重大)  
Internet Explorer 10  
(3032359)  
(重大)  
Internet Explorer 11  
(3032359)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3033889)  
(重大)  
Windows 7 x64 系統 Service Pack 1  
(3039066)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3032323)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3035132)  
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
[**MS15-018**](https://technet.microsoft.com/zh-tw/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/zh-tw/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/zh-tw/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/zh-tw/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/zh-tw/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/zh-tw/library/security/ms15-024)

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
(3032359)  
(中度)  
Internet Explorer 9  
(3032359)  
(中度)  
Internet Explorer 10  
(3032359)  
(中度)  
Internet Explorer 11  
(3032359)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3033889)  
(重大)  
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3039066)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3032323)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3032359)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3033889)  
(重大)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3039066)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3032323)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-018**](https://technet.microsoft.com/zh-tw/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/zh-tw/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/zh-tw/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/zh-tw/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/zh-tw/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/zh-tw/library/security/ms15-024)

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
(3032359)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3033889)  
(重大)  
Windows 8 32 位元系統  
(3039066)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3032323)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 x64 系統

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3032359)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3033889)  
(重大)  
Windows 8 x64 系統  
(3039066)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3032323)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3032359)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3033889)  
(重大)  
Windows 8.1 32 位元系統  
(3039066)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3032323)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 x64 系統

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3032359)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3033889)  
(重大)  
Windows 8.1 x64 系統  
(3039066)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3032323)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3035132)  
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
[**MS15-018**](https://technet.microsoft.com/zh-tw/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/zh-tw/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/zh-tw/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/zh-tw/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/zh-tw/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/zh-tw/library/security/ms15-024)

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
(3032359)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3033889)  
(重大)  
Windows Server 2012  
(3039066)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3032323)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3032359)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3033889)  
(重大)  
Windows Server 2012 R2  
(3039066)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3032323)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-018**](https://technet.microsoft.com/zh-tw/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/zh-tw/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/zh-tw/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/zh-tw/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/zh-tw/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/zh-tw/library/security/ms15-024)

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
(3032359)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT  
(3033889)  
(重大)  
Windows RT  
(3039066)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT  
(3032323)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3032359)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3033889)  
(重大)  
Windows RT 8.1  
(3039066)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3032323)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3035132)  
(重要)

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
[**MS15-018**](https://technet.microsoft.com/zh-tw/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/zh-tw/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/zh-tw/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/zh-tw/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/zh-tw/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/zh-tw/library/security/ms15-024)

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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3030398)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3033889)  
(重大)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3039066)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3032323)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3035132)  
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
VBScript 5.7  
(3030398)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3033889)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3039066)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3032323)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3035132)  
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
VBScript 5.8  
(3030630)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3033889)  
(重大)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3039066)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3032323)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3035132)  
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
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3033889)  
(重大)  
Windows Server 2012 (Server Core 安裝)  
(3039066)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3032323)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3035132)  
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
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3033889)  
(重大)  
Windows Server 2012 R2 (Server Core 安裝)  
(3039066)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3032323)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3035132)  
(重要)

</td>
</tr>
</table>
 
**MS15-018、MS15-019、MS15-020、MS15-021 和 MS15-023 注意事項**

Windows Technical Preview 和 Windows Server Technical Preview 會受影響。建議執行這些作業系統的客戶透過 [Windows Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-tw) 套用此更新。

** **

### Windows 作業系統及元件 (表格 2 之 2)

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-025**](https://technet.microsoft.com/zh-tw/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/zh-tw/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/zh-tw/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/zh-tw/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/zh-tw/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/zh-tw/library/security/ms15-031)

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
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3033395)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3002657)  
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
Windows Server 2003 Service Pack 2  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3033395)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3002657)  
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
Windows Server 2003 x64 Edition Service Pack 2  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Itanium 系統 (含 SP2)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Itanium 系統 (含 SP2)  
(3033395)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Itanium 系統 (含 SP2)  
(3002657)  
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
Windows Server 2003 Itanium 系統 (含 SP2)  
(3046049)  
(重要)

</td>
</tr>
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
[**MS15-025**](https://technet.microsoft.com/zh-tw/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/zh-tw/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/zh-tw/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/zh-tw/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/zh-tw/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/zh-tw/library/security/ms15-031)

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
Windows Vista Service Pack 2  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3046049)  
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
[**MS15-025**](https://technet.microsoft.com/zh-tw/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/zh-tw/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/zh-tw/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/zh-tw/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/zh-tw/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/zh-tw/library/security/ms15-031)

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
**無**

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
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2  
(3002657)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3002657)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2  
(3002657)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2  
(3046049)  
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
[**MS15-025**](https://technet.microsoft.com/zh-tw/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/zh-tw/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/zh-tw/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/zh-tw/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/zh-tw/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/zh-tw/library/security/ms15-031)

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
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3035017)  
(重要)  
Windows 7 32 位元系統 Service Pack 1  
(3036493)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3035017)  
(重要)  
Windows 7 x64 系統 Service Pack 1  
(3036493)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3046049)  
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
[**MS15-025**](https://technet.microsoft.com/zh-tw/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/zh-tw/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/zh-tw/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/zh-tw/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/zh-tw/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/zh-tw/library/security/ms15-031)

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
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3002657)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3002657)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-025**](https://technet.microsoft.com/zh-tw/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/zh-tw/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/zh-tw/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/zh-tw/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/zh-tw/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/zh-tw/library/security/ms15-031)

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
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3035017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 x64 系統

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3035017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3035017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 x64 系統

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3035017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3046049)  
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
[**MS15-025**](https://technet.microsoft.com/zh-tw/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/zh-tw/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/zh-tw/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/zh-tw/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/zh-tw/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/zh-tw/library/security/ms15-031)

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
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3002657)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3035017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3002657)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3035017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-025**](https://technet.microsoft.com/zh-tw/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/zh-tw/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/zh-tw/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/zh-tw/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/zh-tw/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/zh-tw/library/security/ms15-031)

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
Windows RT  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3046049)  
(重要)

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
[**MS15-025**](https://technet.microsoft.com/zh-tw/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/zh-tw/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/zh-tw/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/zh-tw/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/zh-tw/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/zh-tw/library/security/ms15-031)

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
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3002657)  
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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3002657)  
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
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3002657)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3002657)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3035017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3002657)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3035017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3046049)  
(重要)

</td>
</tr>
</table>
 
**MS15-031 注意事項**

Windows Technical Preview 和 Windows Server Technical Preview 會受影響。建議執行這些作業系統的客戶透過 [Windows Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-tw) 套用此更新。

 

### Microsoft 伺服器軟體

 
<p></p>
<table style="border:1px solid black;">
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
[**MS15-022**](https://technet.microsoft.com/zh-tw/library/security/ms15-022)

</td>
<td style="border:1px solid black;">
[**MS15-026**](https://technet.microsoft.com/zh-tw/library/security/ms15-026)

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
(3040856)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 積存更新 7

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 積存更新 7  
(3040856)  
(重要)

</td>
</tr>
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
[**MS15-022**](https://technet.microsoft.com/zh-tw/library/security/ms15-022)

</td>
<td style="border:1px solid black;">
[**MS15-026**](https://technet.microsoft.com/zh-tw/library/security/ms15-026)

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
Microsoft SharePoint Server 2007 Service Pack 3 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (32 位元版本)  
(2881068)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 位元版本)  
(2881068)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3 (32 位元版本)  
(2881068)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3 (64 位元版本)  
(2881068)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

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
[**MS15-022**](https://technet.microsoft.com/zh-tw/library/security/ms15-022)

</td>
<td style="border:1px solid black;">
[**MS15-026**](https://technet.microsoft.com/zh-tw/library/security/ms15-026)

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
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 2 (wssloc)  
(2956208)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2 (wssloc)  
(2956208)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

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
[**MS15-022**](https://technet.microsoft.com/zh-tw/library/security/ms15-022)

</td>
<td style="border:1px solid black;">
[**MS15-026**](https://technet.microsoft.com/zh-tw/library/security/ms15-026)

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
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 (sts)  
(2956175)  
(重要)  
Microsoft SharePoint Foundation 2013 (wssloc)  
(2956183)  
(重要)  
Microsoft SharePoint Foundation 2013 (smsloc)  
(2760508)  
(重要)  
Microsoft SharePoint Server 2013 (acsrvloc)  
(2956180)  
(重要)  
Microsoft SharePoint Server 2013 (coreserverloc)  
(2956153)  
(重要)  
Microsoft SharePoint Server 2013 (eduloc)  
(2760554)  
(重要)  
Microsoft SharePoint Server 2013 (ifsloc)  
(2880473)  
(重要)  
Microsoft SharePoint Server 2013 (lpsrvloc)  
(2737989)  
(重要)  
Microsoft SharePoint Server 2013 (ppsmaloc)  
(2881078)  
(重要)  
Microsoft SharePoint Server 2013 (vsrvloc)  
(2956181)  
(重要)  
Microsoft SharePoint Server 2013 (wasrvloc)  
(2760361)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1 (sts)  
(2956175)  
(重要)  
Microsoft SharePoint Foundation 2013 Service Pack 1 (wssloc)  
(2956183)  
(重要)  
Microsoft SharePoint Foundation 2013 Service Pack 1 (smsloc)  
(2760508)  
(重要)  
Microsoft SharePoint Server 2013 Service Pack 1 (acsrvloc)  
(2956180)  
(重要)  
Microsoft SharePoint Server 2013 Service Pack 1 (coreserverloc)  
(2956153)  
(重要)  
Microsoft SharePoint Server 2013 Service Pack 1 (eduloc)  
(2760554)  
(重要)  
Microsoft SharePoint Server 2013 Service Pack 1 (ifsloc)  
(2880473)  
(重要)  
Microsoft SharePoint Server 2013 Service Pack 1 (lpsrvloc)  
(2737989)  
(重要)  
Microsoft SharePoint Server 2013 Service Pack 1 (ppsmaloc)  
(2881078)  
(重要)  
Microsoft SharePoint Server 2013 Service Pack 1 (vsrvloc)  
(2956181)  
(重要)  
Microsoft SharePoint Server 2013 Service Pack 1 (wasrvloc)  
(2760361)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
</table>
 
**MS15-022 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

 

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
[**MS15-022**](https://technet.microsoft.com/zh-tw/library/security/ms15-022)

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
(2984939)  
(重要)  
Microsoft Excel 2007 Service Pack 3  
(2956103)  
(重要)  
Microsoft PowerPoint 2007 Service Pack 3  
(2899580)  
(重要)  
Microsoft Word 2007 Service Pack 3  
(2956109)  
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
[**MS15-022**](https://technet.microsoft.com/zh-tw/library/security/ms15-022)

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
(2956076)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(2956138)  
(重大)  
Microsoft Office 2010 Service Pack 2 (32 位元版本) (oart)  
(2883100)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 位元版本) (oartconv)  
(2889839)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (32 位元版本)  
(2956142)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (32 位元版本)  
(2920812)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 位元版本)  
(2956139)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(2956076)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(2956138)  
(重大)  
Microsoft Office 2010 Service Pack 2 (64 位元版本) (oart)  
(2883100)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 位元版本) (oartconv)  
(2889839)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (64 位元版本)  
(2956142)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (64 位元版本)  
(2920812)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 位元版本)  
(2956139)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013 和 Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-022**](https://technet.microsoft.com/zh-tw/library/security/ms15-022)

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
Microsoft Office 2013 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (32 位元版本)  
(2956151)  
(重要)  
Microsoft Word 2013 (32 位元版本)  
(2956163)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (64 位元版本)  
(2956151)  
(重要)  
Microsoft Word 2013 (64 位元版本)  
(2956163)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 位元版本)  
(2956151)  
(重要)  
Microsoft Word 2013 Service Pack 1 (32 位元版本)  
(2956163)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 位元版本)  
(2956151)  
(重要)  
Microsoft Word 2013 Service Pack 1 (64 位元版本)  
(2956163)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT  
(2956151)  
(重要)  
Microsoft Word 2013 RT  
(2956163)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1  
(2956151)  
(重要)  
Microsoft Word 2013 RT Service Pack 1  
(2956163)  
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
[**MS15-022**](https://technet.microsoft.com/zh-tw/library/security/ms15-022)

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
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2956188)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(2956189)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 相容性套件 Service Pack 3 (wordconv)  
(2956107)  
(重大)  
Microsoft Office 相容性套件 Service Pack 3 (xlconv)  
(2956106)  
(重要)

</td>
</tr>
</table>
 
**MS15-022 注意事項**

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
[**MS15-022**](https://technet.microsoft.com/zh-tw/library/security/ms15-022)

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
Word Automation Services (wdsrv)  
(2956136)  
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
[**MS15-022**](https://technet.microsoft.com/zh-tw/library/security/ms15-022)

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
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Excel Services (xlsrvloc)  
(2956143)  
(重要)  
Word Automation Services (wdsrvloc)  
(2920731)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Excel Services (xlsrvloc)  
(2956143)  
(重要)  
Word Automation Services (wdsrvloc)  
(2920731)  
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
[**MS15-022**](https://technet.microsoft.com/zh-tw/library/security/ms15-022)

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
Microsoft Web Applications 2010 Service Pack 2 (wacloc2010)  
(2956069)  
(重大)  
Microsoft Office Web Apps Server 2010 Service Pack 2 (wacloc2010)  
(2956069)  
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
[**MS15-022**](https://technet.microsoft.com/zh-tw/library/security/ms15-022)

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
Microsoft Office Web Apps 2013

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(wacserver2013)  
(2956158)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(wacserver2013)  
(2956158)  
(重大)

</td>
</tr>
</table>
 
**MS15-022 注意事項**

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

Microsoft 了解資訊安全業界所做的努力，其盡責地透露資訊安全風險來協助我們保護客戶。請參閱[致謝](https://technet.microsoft.com/zh-tw/library/security/dn903755.aspx) (英文) 以取得詳細資訊。

其他資訊
--------

### Microsoft Windows 惡意軟體移除工具 (英文)

針對每個月第二個星期二發行的公告，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 及下載中心發行更新版本的 Microsoft Windows 惡意軟體移除工具。不定期資訊安全公告發行不提供更新版本的 Microsoft Windows 惡意軟體移除工具。

### MU、WU 及 WSUS 上的非安全性更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [Microsoft 知識庫文章 894199](https://support.microsoft.com/kb/894199/zh-tw)：Software Update Services 與 Windows Server Update Services 的說明內容有所變動。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](http://technet.microsoft.com/zh-tw/windowsserver/bb332157.aspx)。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的資訊安全保護，Microsoft 將在每月發行安全性更新之前，提前向重要資訊安全軟體提供者提供資訊安全風險資訊。資訊安全軟體提供者可利用此資訊安全風險資訊，透過其資訊安全軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://technet.microsoft.com/zh-tw/security/dn467918) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

### 安全性策略與社群

**更新程式管理策略**

[更新管理安全性指南](http://technet.microsoft.com/zh-tw/library/bb466251.aspx) (英文) 提供您有關套用資訊安全更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他資訊安全問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得，您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-tw) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的資訊安全更新。如需更多資訊，請參閱 [Microsoft 知識庫文章 913086](https://support.microsoft.com/kb/913086/zh-tw)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](http://technet.microsoft.com/zh-tw/security/cc136632.aspx)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

### 支援

所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](http://go.microsoft.com/fwlink/?linkid=21742)。

適用於 IT 專業人員的安全性解決方案：[安全性疑難排解與支援](http://technet.microsoft.com/zh-tw/security/bb980617)

協助保護您執行 Windows 的電腦免於受到病毒和惡意程式碼攻擊：[病毒解決方案與資訊安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-tw)

根據您所在國家/地區的當地支援：[國際化支援](http://support.microsoft.com/common/international.aspx?ln=zh-tw)

### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

### 修訂

-   V1.0 (2015 年 3 月 10 日)：公告摘要發行。

*頁面產生時間：2015-03-10 9:05Z-07:00。*
