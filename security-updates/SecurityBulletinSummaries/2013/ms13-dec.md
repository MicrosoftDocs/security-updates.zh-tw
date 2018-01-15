---
TOCTitle: 'MS13-DEC'
Title: 2013 年 12 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms13-dec'
ms:contentKeyID: 61237741
ms:date: '05/14/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms13-dec(v=Security.10)'
---

2013 年 12 月份 Microsoft 資訊安全公告摘要
==========================================

發行日期： 2013 年 12 月 10 日

**版本：** 1.0

此公告摘要列出 2013 年 12 月份發行之資訊安全公告。

發行 2013 年 12 月份資訊安全公告之後，此公告摘要將取代原先於 2013 年 12 月 5 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 資訊安全公告預先通知](http://go.microsoft.com/fwlink/?linkid=217213)。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術資訊安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2013 年 12 月 11 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。[立即註冊參加 12 月份資訊安全公告網路廣播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032557386&culture=en-us)。

Microsoft 也會提供資訊協助客戶排定每月資訊安全更新以及任何非資訊安全更新的優先順序，其中這些非資訊安全更新的發行日期與每月資訊安全更新的發行日期相同。請參閱**＜其他資訊＞**一節。

提要
----

下表依嚴重性摘要說明本月份資訊安全公告。

如需受影響的軟體之詳細資料，請參閱下節＜**受影響的軟體**＞。

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
<td style="border:1px solid black;"><strong>最高的嚴重性等級與資訊安全風險影響</strong></td>
<td style="border:1px solid black;"><strong>重新開機需求</strong></td>
<td style="border:1px solid black;"><strong>受影響的軟體</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344108">MS13-096</a></td>
<td style="border:1px solid black;"><strong>Microsoft 圖形元件中的資訊安全風險可能會允許遠端執行程式碼 (2908005)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Windows、Microsoft Office 和 Microsoft Lync 中一項公開揭露的資訊安全風險。如果使用者檢視內含蓄意製作 TIFF 檔案的內容，則此資訊安全風險可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Office、<br />
Microsoft Lync</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 積存資訊安全更新 (2898785)</strong><br />
<br />
本資訊安全更新可解決 Internet Explorer 中七項未公開報告的資訊安全風險。最嚴重的資訊安全風險可能會在使用者以 Internet Explorer 檢視蓄意製作的網頁時，允許遠端執行程式碼。成功利用其中最嚴重的資訊安全風險的攻擊者，可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325389">MS13-098</a></td>
<td style="border:1px solid black;"><strong>Windows 中的資訊安全風險可能會允許遠端執行程式碼 (2893294)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果使用者或應用程式在受影響的系統上執行或安裝蓄意製作、已簽署的可攜式執行檔 (PE) 檔案，則此資訊安全風險可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344112">MS13-099</a></td>
<td style="border:1px solid black;"><strong>Microsoft Scripting Runtime 物件程式庫中的資訊安全風險可能會允許遠端執行程式碼 (2909158)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果攻擊者引誘使用者造訪蓄意製作的網站或主控蓄意製作內容的網站，此資訊安全風險可能會允許遠端執行程式碼。成功利用此資訊安全風險的攻擊者可以取得與本機使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329830">MS13-105</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange Server 中的資訊安全風險可能會允許遠端執行程式碼 (2915705)</strong><br />
<br />
這個資訊安全更新可解決 Microsoft Exchange Server 中三項公開揭露的資訊安全風險和一項未公開報告的資訊安全風險。其中最嚴重的資訊安全風險存在於 Microsoft Exchange Server 的 WebReady 文件檢視和資料遺失防止功能中。如果攻擊者將包含蓄意製作檔案的電子郵件傳送給使用受影響 Exchange Server 的使用者，這些資訊安全風險可能會允許使用 LocalService 帳戶的安全性層級遠端執行程式碼。LocalService 帳戶在本機系統擁有最低權限，在網路上提供匿名認證。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">不需要重新開機</td>
<td style="border:1px solid black;">Microsoft Exchange</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329771">MS13-100</a></td>
<td style="border:1px solid black;"><strong>Microsoft SharePoint Server 中的資訊安全風險可能會允許遠端執行程式碼 (2904244)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Office Server 軟體中多項未公開報告的資訊安全風險。如果通過驗證的攻擊者傳送蓄意製作的頁面內容給 SharePoint 伺服器，這些資訊安全風險可能會允許遠端執行程式碼。成功利用這些資訊安全風險的攻擊者，將能夠以目標 SharePoint 網站上 W3WP 服務帳戶的安全性層級執行任意程式碼。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft SharePoint</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></td>
<td style="border:1px solid black;"><strong>Windows 核心模式驅動程式中的資訊安全風險可能會允許權限提高 (2880430)</strong><br />
<br />
這個資訊安全更新可解決 Microsoft Windows 中五個未公開報告的資訊安全風險。如果攻擊者登入系統並執行蓄意製作的應用程式，則這些資訊安全風險中較嚴重者可能允許權限提高。攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344110">MS13-102</a></td>
<td style="border:1px solid black;"><strong>LRPC 用戶端中的資訊安全風險可能會允許權限提高 (2898715)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果攻擊者偽造 LRPC 伺服器並傳送蓄意製作的 LPC 連接埠訊息給任何 LRPC 用戶端，則該資訊安全風險可能會允許權限提高。成功利用此資訊安全風險的攻擊者便可安裝程式，檢視、變更或刪除資料，或建立具有完整系統管理員權限的新帳戶。攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329969">MS13-103</a></td>
<td style="border:1px solid black;"><strong>ASP.NET SignalR 中的資訊安全風險可能會允許權限提高 (2905244)</strong><br />
<br />
這個資訊安全更新可解決 ASP.NET SignalR 中一項未公開報告的資訊安全風險。如果攻擊者能將蓄意製作的 JavaScript 反射回目標使用者的瀏覽器，則此資訊安全風險可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">不需要重新開機</td>
<td style="border:1px solid black;">Microsoft 開發者工具</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=330934">MS13-104</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 中的資訊安全風險可能會允許資訊洩漏 (2909976)</strong><br />
<br />
這個資訊安全更新可解決 Microsoft Office 中一項未公開報告的資訊安全風險，該資訊安全風險可能會在使用者嘗試開啟存放在惡意網站上的 Office 檔案時洩漏資訊。成功利用此資訊安全風險的攻擊者，可能會探知在目標 SharePoint 或其他 Microsoft Office 伺服器網站上用來驗證目前使用者的存取 Token。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
資訊洩漏</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329967">MS13-106</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 共用元件中的資訊安全風險可能會允許略過安全性功能<br />
(2905238)</strong><br />
<br />
這個資訊安全更新可解決 Microsoft Office 共用元件中一項已公開揭露且目前遭到利用的資訊安全風險。如果使用者在能具現化 COM 元件的網頁瀏覽器 (例如 Internet Explorer) 中檢視蓄意製作的網頁，此資訊安全風險可能會允許略過安全性功能。在網頁瀏覽攻擊的案例中，成功利用此資訊安全風險的攻擊者可以略過位址空間隨機載入 (ASLR) 安全性功能，而此功能可協助保護使用者免於廣泛類別的資訊安全風險侵擾。略過安全性功能本身不會允許執行任意程式碼。但是，攻擊者可以搭配使用此 ASLR 略過資訊安全風險和其他資訊安全風險，例如搭配可利用 ASLR 略過的遠端執行程式碼資訊安全風險，即可執行任意程式碼。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
資訊安全功能略過</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>
  
 
  
資訊安全風險入侵指數  
--------------------
  
下表提供本月所述每個資訊安全風險的利用性評估。資訊安全風險皆根據公告編號和 CVE 編號依序列出。僅包含資訊安全公告中，嚴重性等級為「重大」或「重要」的資訊安全風險。
  
**我該如何使用這個表格？**
  
您可以運用此表格，針對您可能需要安裝的每一項資訊安全更新，瞭解資訊安全風險在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務 (DoS) 的可能性。請根據您特定的組態設定，檢閱下列各項評估，決定部署本月份更新的優先次序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 資訊安全風險索引](http://technet.microsoft.com/security/cc998259)。
  
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
<td style="border:1px solid black;"><strong>公告編號</strong></td>
<td style="border:1px solid black;"><strong>資訊安全風險標題</strong></td>
<td style="border:1px solid black;"><strong>CVE ID</strong></td>
<td style="border:1px solid black;"><strong>最新軟體版本的資訊安全風險評估</strong></td>
<td style="border:1px solid black;"><strong>較舊軟體版本的資訊安全風險評估</strong></td>
<td style="border:1px solid black;"><strong>阻斷服務 (DoS) 資訊安全風險評估</strong></td>
<td style="border:1px solid black;"><strong>主要重點</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344108">MS13-096</a></td>
<td style="border:1px solid black;">Microsoft 圖形元件記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3906">CVE-2013-3906</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">此資訊安全風險已經遭到公開揭發。<br />
<br />
Microsoft 已發現嘗試透過 Microsoft Office 產品利用這項資訊安全風險的目標式攻擊。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer 權限提高資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5045">CVE-2013-5045</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer 權限提高資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5046">CVE-2013-5046</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5047">CVE-2013-5047</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5048">CVE-2013-5048</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5049">CVE-2013-5049</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5051">CVE-2013-5051</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5052">CVE-2013-5052</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325389">MS13-098</a></td>
<td style="border:1px solid black;">WinVerifyTrust 簽章驗證資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3900">CVE-2013-3900</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">Microsoft 已發現有嘗試利用此資訊安全風險、目標明確的攻擊。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344112">MS13-099</a></td>
<td style="border:1px solid black;">Microsoft Scripting Runtime 物件程式庫中的釋放後使用資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5056">CVE-2013-5056</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329771">MS13-100</a></td>
<td style="border:1px solid black;">SharePoint 頁面內容資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5059">CVE-2013-5059</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></td>
<td style="border:1px solid black;">Win32k 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3899">CVE-2013-3899</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></td>
<td style="border:1px solid black;">Win32k 釋放後使用資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3902">CVE-2013-3902</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></td>
<td style="border:1px solid black;">TrueType 字型剖析資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3903">CVE-2013-3903</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></td>
<td style="border:1px solid black;">通訊埠類別驅動程式重覆擷取資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3907">CVE-2013-3907</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></td>
<td style="border:1px solid black;">Win32k 整數溢位資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5058">CVE-2013-5058</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">這是一項阻斷服務 (DoS) 的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344110">MS13-102</a></td>
<td style="border:1px solid black;">LRPC 用戶端緩衝區溢位資訊安全風險 </td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3878">CVE-2013-3878</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329969">MS13-103</a></td>
<td style="border:1px solid black;">SignalR XSS 資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5042">CVE-2013-5042</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=330934">MS13-104</a></td>
<td style="border:1px solid black;">Token 劫持資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5054">CVE-2013-5054</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊洩漏的資訊安全風險。<br />
<br />
Microsoft 已發現有嘗試利用此資訊安全風險、有限且目標明確的攻擊。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329830">MS13-105</a></td>
<td style="border:1px solid black;">MAC 停用資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1330">CVE-2013-1330</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">此資訊安全風險已經遭到公開揭發。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329830">MS13-105</a></td>
<td style="border:1px solid black;">Oracle Outside In 包含多項可能遭利用的資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5763">CVE-2013-5763</a><br />
<br />
與<br />
<br />
<a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5791">CVE-2013-5791</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">這類資訊安全風險已被公開揭發。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329830">MS13-105</a></td>
<td style="border:1px solid black;">OWA XSS 資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5072">CVE-2013-5072</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329967">MS13-106</a></td>
<td style="border:1px solid black;">HXDS ASLR 資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5057">CVE-2013-5057</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊安全功能略過之資訊安全風險。<br />
<br />
此資訊安全風險已經遭到公開揭發。<br />
<br />
Microsoft 已發現有嘗試利用此資訊安全風險、有限且目標明確的攻擊。</td>
</tr>
</tbody>
</table>
 

 

受影響的軟體
------------


下表依據主要的軟體類別和嚴重性依序列出公告。

**我該如何使用這些表格？**

請用這些表格來瞭解可能需要安裝的資訊安全更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的資訊安全更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。

**注意**：一項資訊安全風險，可能需要安裝數個資訊安全更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。

### Windows 作業系統與元件

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows XP**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](http://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](http://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](http://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](http://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](http://go.microsoft.com/fwlink/?linkid=344110)

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
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2898785)  
(重大)  
Internet Explorer 7   
(2898785)  
(重大)  
Internet Explorer 8   
(2898785)  
(重大)

</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.7  
(2892075)  
(重大)

</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2893984)  
(重要)

</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2898715)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2898785)  
(重大)  
Internet Explorer 7   
(2898785)  
(重大)  
Internet Explorer 8   
(2898785)  
(重大)

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.6  
(2892076)  
(重大)  
Windows Script 5.7   
(2892075)  
(重大)

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2893984)  
(重要)

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2898715)  
(重要)

</td>
</tr>
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
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](http://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](http://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](http://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](http://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](http://go.microsoft.com/fwlink/?linkid=344110)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2898785)  
(中度)  
Internet Explorer 7  
(2898785)  
(重要)  
Internet Explorer 8  
(2898785)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.6   
(2892076)  
(重大)  
Windows Script 5.7   
(2892075)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2893984)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2898715)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2898785)  
(中度)  
Internet Explorer 7  
(2898785)  
(重要)  
Internet Explorer 8  
(2898785)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.6   
(2892076)  
(重大)  
Windows Script 5.7   
(2892075)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2893984)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2898715)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2898785)  
(中度)  
Internet Explorer 7  
(2898785)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.6   
(2892076)  
(重大)  
Windows Script 5.7   
(2892075)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(2893984)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(2898715)  
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
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](http://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](http://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](http://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](http://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](http://go.microsoft.com/fwlink/?linkid=344110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(2901674)  
(重大)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2898785)  
(重大)  
Internet Explorer 8  
(2898785)  
(重大)  
Internet Explorer 9   
(2898785)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2893984)  
(中度)  
Windows Vista Service Pack 2  
(2887069)  
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
(2901674)  
(重大)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2898785)  
(重大)  
Internet Explorer 8  
(2898785)  
(重大)  
Internet Explorer 9   
(2898785)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2893984)  
(中度)  
Windows Vista x64 Edition Service Pack 2  
(2887069)  
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
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](http://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](http://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](http://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](http://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](http://go.microsoft.com/fwlink/?linkid=344110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(2901674)  
(重大)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2898785)  
(重要)  
Internet Explorer 8  
(2898785)  
(重要)  
Internet Explorer 9   
(2898785)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2893984)  
(中度)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2887069)  
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
(2901674)  
(重大)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2898785)  
(重要)  
Internet Explorer 8  
(2898785)  
(重要)  
Internet Explorer 9   
(2898785)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2893984)  
(中度)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2887069)  
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
(2901674)  
(重大)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2898785)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2893984)  
(中度)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2887069)  
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
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](http://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](http://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](http://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](http://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](http://go.microsoft.com/fwlink/?linkid=344110)

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
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 8  
(2898785)  
(重大)  
Internet Explorer 9   
(2898785)  
(重大)  
Internet Explorer 10   
(2898785)  
(重大)  
Internet Explorer 11   
(2898785)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2893984)  
(重要)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2887069)  
(重要)

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
Internet Explorer 8  
(2898785)  
(重大)  
Internet Explorer 9   
(2898785)  
(重大)  
Internet Explorer 10   
(2898785)  
(重大)  
Internet Explorer 11   
(2898785)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2893984)  
(重要)  
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2887069)  
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
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](http://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](http://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](http://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](http://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](http://go.microsoft.com/fwlink/?linkid=344110)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 8  
(2898785)  
(重要)  
Internet Explorer 9   
(2898785)  
(重要)  
Internet Explorer 10   
(2898785)  
(重要)  
Internet Explorer 11   
(2898785)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2893984)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2887069)  
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
不適用

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2898785)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2893984)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2887069)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

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
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](http://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](http://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](http://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](http://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](http://go.microsoft.com/fwlink/?linkid=344110)

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
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2898785)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8  
(2893984)  
(中度)  
適用於 32 位元系統的 Windows 8  
(2887069)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

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
Internet Explorer 10   
(2898785)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(2893984)  
(中度)  
適用於 x64 型系統的 Windows 8  
(2887069)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

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
Internet Explorer 11   
(2898785)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(2893984)  
(中度)

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
不適用

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2898785)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(2893984)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

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
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](http://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](http://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](http://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](http://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](http://go.microsoft.com/fwlink/?linkid=344110)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
不適用

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2898785)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2893984)  
(中度)  
Windows Server 2012  
(2887069)  
(重要)

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
不適用

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2898785)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2893984)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

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
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](http://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](http://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](http://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](http://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](http://go.microsoft.com/fwlink/?linkid=344110)

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
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

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
Internet Explorer 10   
(2898785)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT  
(2893984)  
(中度)  
Windows RT  
(2887069)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

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
Internet Explorer 11   
(2898785)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2893984)  
(中度)

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
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](http://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](http://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](http://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](http://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](http://go.microsoft.com/fwlink/?linkid=344110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2901674)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2893984)  
(中度)

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
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2901674)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2893984)  
(中度)

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
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(2893984)  
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
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(2893984)  
(中度)

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
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(2893294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(2893984)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
</table>
 
**MS13-096 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

 

### Microsoft Office 套件及軟體

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-104**](http://go.microsoft.com/fwlink/?linkid=330934)

</td>
<td style="border:1px solid black;">
[**MS13-106**](http://go.microsoft.com/fwlink/?linkid=329967)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Microsoft Office 2003 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3 (2850047)  
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
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-104**](http://go.microsoft.com/fwlink/?linkid=330934)

</td>
<td style="border:1px solid black;">
[**MS13-106**](http://go.microsoft.com/fwlink/?linkid=329967)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2817641)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2850022)  
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
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-104**](http://go.microsoft.com/fwlink/?linkid=330934)

</td>
<td style="border:1px solid black;">
[**MS13-106**](http://go.microsoft.com/fwlink/?linkid=329967)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32 位元版本)  
(2817670)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32 位元版本)  
(2850016)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(2817670)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(2850016)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64 位元版本)  
(2817670)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64 位元版本)  
(2850016)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(2817670)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(2850016)  
(重要)

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
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-104**](http://go.microsoft.com/fwlink/?linkid=330934)

</td>
<td style="border:1px solid black;">
[**MS13-106**](http://go.microsoft.com/fwlink/?linkid=329967)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 (32 位元版本)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (32 位元版本)  
(2850064)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 (64 位元版本)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (64 位元版本)  
(2850064)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT  
(2850064)  
(重要)

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
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-104**](http://go.microsoft.com/fwlink/?linkid=330934)

</td>
<td style="border:1px solid black;">
[**MS13-106**](http://go.microsoft.com/fwlink/?linkid=329967)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Microsoft Office 相容性套件 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 相容性套件 Service Pack 3  
(2817641)  
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
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2850047)  
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
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(2817641)  
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
Microsoft PowerPoint 2010 Viewer Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft PowerPoint 2010 Viewer Service Pack 1  
(2817670)  
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
Microsoft PowerPoint 2010 Viewer Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft PowerPoint 2010 Viewer Service Pack 2  
(2817670)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
</table>
 
**MS13-096 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

 

### Microsoft 伺服器軟體

<p></p> 
<table style="border:1px solid black;">
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
[**MS13-105**](http://go.microsoft.com/fwlink/?linkid=329830)

</td>
<td style="border:1px solid black;">
[**MS13-100**](http://go.microsoft.com/fwlink/?linkid=329771)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 (coreserverloc)  
(2850058)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS13-105**](http://go.microsoft.com/fwlink/?linkid=329830)

</td>
<td style="border:1px solid black;">
[**MS13-100**](http://go.microsoft.com/fwlink/?linkid=329771)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3  
(2903911)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS13-105**](http://go.microsoft.com/fwlink/?linkid=329830)

</td>
<td style="border:1px solid black;">
[**MS13-100**](http://go.microsoft.com/fwlink/?linkid=329771)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 2  
(2903903)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3  
(2905616)  
(重大)

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
[**MS13-105**](http://go.microsoft.com/fwlink/?linkid=329830)

</td>
<td style="border:1px solid black;">
[**MS13-100**](http://go.microsoft.com/fwlink/?linkid=329771)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 積存更新 2

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 積存更新 2  
(2880833)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 積存更新 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 積存更新 3  
(2880833)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
</table>
 
**MS13-100 注意事項**

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
[**MS13-100**](http://go.microsoft.com/fwlink/?linkid=329771)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Business Productivity Servers  
(2553298)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Business Productivity Servers  
(2553298)  
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
[**MS13-100**](http://go.microsoft.com/fwlink/?linkid=329771)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Microsoft Business Productivity Servers  
(2837629)  
(重要)  
Excel Services  
(2837631)  
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
[**MS13-100**](http://go.microsoft.com/fwlink/?linkid=329771)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(2910228)  
(重要)

</td>
</tr>
</table>
 
**MS13-100 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

 

### Microsoft 通訊平台和軟體

<p></p> 
<table style="border:1px solid black;">
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
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 位元)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 位元)  
(2899397)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 位元)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 位元)  
(2899397)  
(重要)

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
(2899393)  
(重要)

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
(2899395)  
(重要)

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
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 (32 位元)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 (32 位元)  
(2850057)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (32 位元)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (32 位元)  
(2850057)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 (64 位元)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 (64 位元)  
(2850057)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (64 位元)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013  
(64 位元)  
(2850057)  
(重要)

</td>
</tr>
</table>
 
**MS13-096 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

### Microsoft 開發者工具和軟體

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**ASP.NET**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS13-103**](http://go.microsoft.com/fwlink/?linkid=329969)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
ASP.NET SignalR

</td>
<td style="border:1px solid black;">
ASP.NET SignalR 1.1.x   
(2903919)  
(重要)  
ASP.NET SignalR 2.0.x   
(2903919)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Visual Studio Team Foundation Server**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS13-103**](http://go.microsoft.com/fwlink/?linkid=329969)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio Team Foundation Server 2013

</td>
<td style="border:1px solid black;">
Microsoft Visual Studio Team Foundation Server 2013   
(2903566)  
(重要)

</td>
</tr>
</table>
 
 

偵測與部署工具及指南
--------------------


有幾項資源可協助系統管理員部署資訊安全更新。

-   Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，查看是否遺漏資訊安全更新及一般資訊安全設定錯誤的狀況。
-   Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 可協助系統管理員散佈資訊安全更新。
-   應用程式相容性工具組隨附的 Update Compatibility Evaluator 元件可針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

如需上述工具以及其他可使用工具的詳細資訊，請參閱 [IT專業人員的資訊安全工具](http://technet.microsoft.com/security/cc297183)。 

感謝
----


Microsoft [感謝](http://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

**MS13-096**

-   感謝 McAfee Labs IPS Team 的 Haifei Li 回報 Microsoft 圖形元件記憶體損毀資訊安全風險 (CVE-2013-3906)

**MS13-097**

-   感謝 Context Information Security 的 James Forshaw 回報 Internet Explorer 權限提高資訊安全風險 (CVE-2013-5045)
-   感謝 Context Information Security 的 James Forshaw 回報 Internet Explorer 權限提高資訊安全風險 (CVE-2013-5046)
-   感謝 [HP 的](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 的 Abdul-Aziz Hariri 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-5047)
-   感謝匿名的研究人員與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-5048)
-   感謝 Jose Antonio Vazquez Gonzalez 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-5049)
-   感謝 [OUSPG](https://www.ee.oulu.fi/research/ouspg/) 的 Atte Kettunen 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-5051)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-5052)
-   感謝 Alex Inführ協助我們進行本公告中所含的 Internet Explorer XSS 篩選器的深度防禦變更

**MS13-098**

-   感謝 Kingsoft Internet Security Center @ [Kingsoft Internet Security Software Co.Ltd](http://www.ijinshan.com/) 回報 WinVerifyTrust 簽章驗證資訊安全風險 (CVE-2013-3900)

**MS13-101**

-   感謝 [Qihoo](http://www.360.cn/) 的 Renguang Yuan 回報 Win32k 記憶體損毀資訊安全風險 (CVE-2013-3899)
-   感謝匿名的研究人員與 [VeriSign iDefense Labs](http://labs.idefense.com/) 合作，回報 Win32k 記憶體損毀資訊安全風險 (CVE-2013-3899)
-   感謝 [F13 Laboratory](http://www.f13-labs.net/) 的 Ling Chuan Lee 回報 TrueType 字型剖析資訊安全風險 (CVE-2013-3903)
-   感謝 [Core Security Technologies](http://www.coresecurity.com/) 的 Nicolas Economou 回報 Win32k 整數溢位資訊安全風險 (CVE-2013-5058)

**MS13-102**

-   感謝 [Qihoo](http://www.360.cn/) 的 Renguang Yuan 回報 LRPC 用戶端緩衝區溢位資訊安全風險 (CVE-2013-3878)

**MS13-104**

-   感謝 [Adallom](http://www.adallom.com/) 的 Noam Liran 回報 Token 劫持資訊安全風險 (CVE-2013-5054)

**MS13-105**

-   感謝 [Minded Security](https://www.mindedsecurity.com/) 代表 [Criteo](http://www.criteo.com/) 回報 OWA XSS 資訊安全風險 (CVE-2013-5072)

其他資訊
--------


### Microsoft Windows 惡意軟體移除工具 (英文)

針對每個月第二個星期二發行的公告，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 及下載中心發行更新版本的 Microsoft Windows 惡意軟體移除工具。不定期資訊安全公告發行不提供更新版本的 Microsoft Windows 惡意軟體移除工具。

### MU、WU 及 WSUS 上的非資訊安全更新

如需在 Windows Update 和 Microsoft Update 上發行的非資訊安全更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](https://support.microsoft.com/kb/894199)： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](http://technet.microsoft.com/wsus/bb456965)。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的資訊安全保護，Microsoft 將在每月發行資訊安全更新之前，提前向重要資訊安全軟體提供者提供資訊安全風險資訊。資訊安全軟體提供者可利用此資訊安全風險資訊，透過其資訊安全軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://go.microsoft.com/fwlink/?linkid=215201) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

### 資訊安全策略與社群

**更新程式管理策略**

[更新管理資訊安全指南](http://go.microsoft.com/fwlink/?linkid=21168) (英文) 提供您有關套用資訊安全更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他資訊安全更新**

其他資訊安全問題的更新可由下列位置取得：

-   資訊安全更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。
-   消費性平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以資訊安全和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的資訊安全更新。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](https://support.microsoft.com/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全社群](http://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升資訊安全以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類資訊安全議題的討論。

### 支援

所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 支援週期](http://go.microsoft.com/fwlink/?linkid=21742)。

IT 專業人員的資訊安全解決方案： [TechNet 資訊安全疑難排解與支援](http://technet.microsoft.com/security/bb980617)

協助保護您的 Widows 電腦免於病毒和惡意軟體攻擊： [病毒解決方案與資訊安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master)

您所在國家/地區的當地支援： [國際支援](http://support.microsoft.com/common/international.aspx)

### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

### 修訂

-   V1.0 (2013 年 12 月 10 日)： 公告摘要發行。

 

*頁面產生時間：2014-05-09 17:27Z-07:00。*
