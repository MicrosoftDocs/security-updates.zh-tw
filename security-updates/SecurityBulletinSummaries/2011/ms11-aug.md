---
TOCTitle: 'MS11-AUG'
Title: 2011 年 8 月份 Microsoft 安全性公告摘要
ms:assetid: 'ms11-aug'
ms:contentKeyID: 61237714
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms11-aug(v=Security.10)'
---

2011 年 8 月份 Microsoft 安全性公告摘要
=======================================

發行: 2011年8月9日 | 更新: 2011年10月26日

**版本:** 1.2

此公告摘要列出 2011 年 8 月份發行之安全性公告。

發行 2011 年 8 月份安全性公告之後，此公告摘要將取代原先於 2011 年 8 月 4 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](http://go.microsoft.com/fwlink/?linkid=217213)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2011 年 8 月 10 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。[立即註冊參加 8 月份安全性公告網路廣播](https://msevents.microsoft.com/cui/eventdetail.aspx?culture=en-us&eventid=1032487857)。在這個日期後，此網路廣播將可隨選取得。如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](http://go.microsoft.com/fwlink/?linkid=217214) (英文)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性更新的優先順序，其中這些非安全性更新的發行日期與每月安全性更新的發行日期相同。請參閱＜其他資訊＞一節。

### 公告資訊

提要
----

<span></span>
下表依嚴重性摘要說明本月份安全性公告。

如需受影響的軟體之詳細資料，請參閱下節＜受影響的軟體及下載位置＞。

 
<p> </p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >公告編號</th>
<th style="border:1px solid black;" >公告標題與提要</th>
<th style="border:1px solid black;" >最高的嚴重性等級與弱點影響</th>
<th style="border:1px solid black;" >重新開機需求</th>
<th style="border:1px solid black;" >受影響的軟體</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 積存安全性更新 (2559049)</strong><br />
<br />
這個安全性更新可解決 Internet Explorer 中五項未公開報告的弱點，以及兩項公開揭露的弱點。最嚴重的弱點可能會在使用者以 Internet Explorer 檢視蓄意製作的網頁時，允許遠端執行程式碼。成功利用這類任一弱點的攻擊者可以取得與本機使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221812">MS11-058</a></td>
<td style="border:1px solid black;"><strong>DNS 伺服器中的弱點可能會允許遠端執行程式碼 (2562485)</strong><br />
<br />
這個安全性更新可解決 Windows DNS 伺服器 中兩項未公開報告的弱點。如果攻擊者註冊網域、建立 NAPTR DNS 資源記錄、然後再將蓄意製作的 NAPTR 查詢傳送至目標 DNS 伺服器，則這些弱點中較嚴重者可能會允許遠端執行程式碼。未啟用 DNS 角色的伺服器不會受到影響。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221539">MS11-059</a></td>
<td style="border:1px solid black;"><strong>Data Access Components 中的弱點可能會允許遠端執行程式碼 (2560656)</strong><br />
<br />
這個安全性更新可解決 Microsoft Windows 中一項未公開報告的弱點。如果使用者開啟與蓄意製作之程式庫檔案位於相同網路目錄的正常 Excel 檔案 (例如 .xlsx 檔)，此弱點可能會允許遠端執行程式碼。成功利用此弱點的攻擊者可以取得與登入使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=223425">MS11-060</a></td>
<td style="border:1px solid black;"><strong>Microsoft Visio 中的弱點可能會允許遠端執行程式碼 (2560978)</strong><br />
<br />
這個安全性更新可解決 Microsoft Visio 中兩項未公開報告的弱點。如果使用者開啟蓄意製作的 Visio 檔案，此弱點可能會允許遠端執行程式碼。成功利用此弱點的攻擊者可以取得與登入使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217099">MS11-061</a></td>
<td style="border:1px solid black;"><strong>遠端桌面網路存取中的弱點可能會允許權限提高 (2546250)</strong><br />
<br />
這個安全性更新可解決遠端桌面 Web 存取中一項未公開報告的弱點。此弱點是會導致權限提高的跨網站指令碼 (XSS) 弱點，可讓攻擊者使用目標使用者的權限在網站上執行任意命令。Internet Explorer 8 與 Internet Explorer 9 的 XSS 篩選器可防止其使用者在網際網路區域中瀏覽至遠端桌面 Web 存取伺服器時遭受此攻擊。依照預設，針對內部網路區域並不會啟用 Internet Explorer 8 和 Internet Explorer 9 中的 XSS 篩選器。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=223669">MS11-062</a></td>
<td style="border:1px solid black;"><strong>遠端存取服務 NDISTAPI 驅動程式中的弱點可能會允許權限提高</strong> <strong>(2566454)</strong><br />
<br />
這個安全性更新可解決所有 Windows XP 和 Windows Server 2003 受支援版本中一項未公開報告的弱點。對於所有受支援版本的 Windows XP 和 Windows Server 2003，此安全性更新的等級為「重要」。Windows Vista、Windows Server 2008、Windows 7 和 Windows Server 2008 R2 不受此弱點影響。<br />
<br />
如果攻擊者登入受影響的系統、執行蓄意製作的應用程式來利用此弱點，然後取得受影響系統之完整控制權，則此弱點可能會允許權限提高。攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項弱點。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221864">MS11-063</a></td>
<td style="border:1px solid black;"><strong>Windows Client/Server Run-time Subsystem 中的弱點可能會允許權限提高 (2567680)</strong><br />
<br />
這個安全性更新可解決 Microsoft Windows 中一項未公開報告的弱點。如果攻擊者登入受影響的系統並執行蓄意製作的應用程式，以傳送裝置事件訊息至完整性較高的處理序，則此弱點可能會允許權限提高。攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項弱點。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221808">MS11-064</a></td>
<td style="border:1px solid black;"><strong>TCP/IP 堆疊中的弱點可能會允許拒絕服務 (2563894)</strong><br />
<br />
這個安全性更新可解決 Microsoft Windows 中兩項未公開報告的弱點。如果攻擊者傳送一連串蓄意製作的「網際網路控制訊息通訊協定」(ICMP) 訊息至目標系統，或傳送蓄意製作的 URL 要求至提供網路內容且啟用 URL 式服務品質 (QoS) 功能的伺服器，則這些弱點可能會允許拒絕服務。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
阻絕服務</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221880">MS11-065</a></td>
<td style="border:1px solid black;"><strong>遠端桌面通訊協定中的弱點可能會允許拒絕服務 (2570222)</strong><br />
<br />
此安全性更新可解決遠端桌面通訊協定中一項未公開報告的弱點。如果受影響的系統收到一連串蓄意製作的 RDP 封包，則此弱點可能會允許拒絕服務。Microsoft 已接獲消息，指出有人利用這個弱點進行有限且目標式的攻擊。依據預設，所有 Windows 作業系統上均未啟用遠端桌面通訊協定 (RDP)。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
阻絕服務</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221536">MS11-066</a></td>
<td style="border:1px solid black;"><strong>Microsoft 圖表控制項中的弱點可能會導致資訊洩漏 (2567943)</strong><br />
<br />
這個安全性更新可解決 ASP.NET 圖表控制項中一項未公開報告的弱點。如果攻擊者傳送蓄意製作的 GET 要求至裝載圖表控制項的受影響伺服器，則此弱點可能會導致資訊洩漏。請注意，這個弱點不會直接允許攻擊者執行程式碼或提高攻擊者的使用者權限，但能用來取得可進一步破壞受影響系統的資訊。只有使用 Microsoft 圖表控制項的 Web 應用程式才會受此問題影響。.NET Framework 的預設安裝不會受影響。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
資訊洩漏</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft .NET Framework、<br />
Microsoft 開發者工具</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=223643">MS11-067</a></td>
<td style="border:1px solid black;"><strong>Microsoft Report Viewer 中的弱點可能會導致資訊洩漏 (2578230)</strong><br />
<br />
這個安全性更新可解決 Microsoft Report Viewer 中一項未公開報告的弱點。如果使用者檢視蓄意製作的網頁，則此弱點便可能允許資訊洩漏。但是，攻擊者並不能強迫使用者造訪網站， 而是引誘使用者自行前往。一般的做法是設法讓使用者按一下電子郵件訊息或 Instant Messenger 訊息中通往易受影響網站的連結。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
資訊洩漏</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft 開發者工具</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=223578">MS11-068</a></td>
<td style="border:1px solid black;"><strong>Windows 核心中的弱點可能會允許拒絕服務 (2556532)</strong><br />
<br />
這個安全性更新可解決 Microsoft Windows 中一項未公開報告的弱點。如果使用者造訪內含蓄意製作檔案的網路共用 (或是造訪的網站指向內含蓄意製作檔案的網路共用)，則此弱點可能會允許拒絕服務。但是，攻擊者並不能強迫使用者造訪這類網路共用或網站， 而是必須引誘使用者自行前往，一般的作法是設法讓使用者按下電子郵件或 Instant Messenger 訊息中的連結。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">中度</a><br />
阻絕服務</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221537">MS11-069</a></td>
<td style="border:1px solid black;"><strong>NET Framework 中的弱點可能會導致資訊洩漏 (2567951)</strong><br />
<br />
這個安全性更新可解決 Microsoft .NET Framework 中一項未公開報告的弱點。如果使用者使用可執行 XAML 瀏覽器應用程式 (XBAP) 的網頁瀏覽器檢視蓄意製作的網頁，則此弱點可能會導致資訊洩漏。在網頁式攻擊的案例中，攻擊者可架設一個網站，並在其中包含利用此弱點的網頁。此外，受侵害的網站以及接受或存放使用者提供之內容或廣告的網站裡，也可能包含蓄意製作以利用本弱點的內容。但是，攻擊者無法強迫使用者造訪網站， 而是引誘使用者自行前往。一般的做法是設法讓使用者按一下電子郵件或 Instant Messenger 訊息中通往攻擊者網站的連結。Windows .NET 應用程式也可能使用這個弱點，以略過程式碼存取安全性 (CAS) 限制。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">中度</a><br />
資訊洩漏</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft .NET Framework</td>
</tr>
</tbody>
</table>
  
弱點索引  
--------
  
<span></span>
下表提供本月所述每個弱點的利用性評估。弱點皆根據公告編號和 CVE 編號依序列出。僅包含安全性公告中，嚴重性等級為「重大」或「重要」的弱點。
  
**我該如何使用這個表格？**
  
您可以運用此表格，針對您可能需要安裝的每一項安全性更新，瞭解弱點在安全性公告發行 30 日內遭成功利用而導致程式碼執行與拒絕服務的可能性。請根據您特定的組態設定，檢閱下列各項評估，決定部署本月份更新的優先次序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](http://technet.microsoft.com/zh-tw/security/cc998259.aspx)。
  
在下方欄位中，「最新軟體版本」意指受影響軟體，「較舊軟體版本」意指受影響軟體所有較舊的支援版本，如公告中的「受影響的軟體」或「不受影響的軟體」表格裡所示。

 
<p> </p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >公告編號</th>
<th style="border:1px solid black;" >弱點標題</th>
<th style="border:1px solid black;" >CVE ID</th>
<th style="border:1px solid black;" >最新軟體版本的程式碼執行弱點評估</th>
<th style="border:1px solid black;" >較舊軟體版本的程式碼執行弱點評估</th>
<th style="border:1px solid black;" >拒絕服務弱點評估</th>
<th style="border:1px solid black;" >主要重點</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td style="border:1px solid black;">視窗開啟競爭條件弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1257">CVE-2011-1257</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">暫時</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td style="border:1px solid black;">事件處理常式資訊洩漏弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1960">CVE-2011-1960</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">3</a> – 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">3</a> – 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊洩漏的弱點</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td style="border:1px solid black;">Telnet 處理常式遠端執行程式碼弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1961">CVE-2011-1961</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td style="border:1px solid black;">XSLT 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1963">CVE-2011-1963</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">暫時</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td style="border:1px solid black;">Style 物件記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1964">CVE-2011-1964</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">暫時</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221812">MS11-058</a></td>
<td style="border:1px solid black;">DNS NAPTR 查詢弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1966">CVE-2011-1966</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">3</a> – 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">3</a> – 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221812">MS11-058</a></td>
<td style="border:1px solid black;">DNS 未初始化的記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1970">CVE-2011-1970</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">3</a> – 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">3</a> – 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">這是一項拒絕服務的弱點</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221539">MS11-059</a></td>
<td style="border:1px solid black;">Data Access Components 不安全程式庫載入弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1975">CVE-2011-1975</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=223425">MS11-060</a></td>
<td style="border:1px solid black;">pStream Release RCE 弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1972">CVE-2011-1972</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">暫時</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=223425">MS11-060</a></td>
<td style="border:1px solid black;">Move Around the Block RCE 弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1979">CVE-2011-1979</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">暫時</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217099">MS11-061</a></td>
<td style="border:1px solid black;">遠端桌面 Web 存取弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1263">CVE-2011-1263</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=223669">MS11-062</a></td>
<td style="border:1px solid black;">NDISTAPI 權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1974">CVE-2011-1974</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221864">MS11-063</a></td>
<td style="border:1px solid black;">CSRSS 弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1967">CVE-2011-1967</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221808">MS11-064</a></td>
<td style="border:1px solid black;">ICMP 拒絕服務弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1871">CVE-2011-1871</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">3</a> – 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">3</a> – 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">這是一項拒絕服務的弱點</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221808">MS11-064</a></td>
<td style="border:1px solid black;">TCP/IP QOS 拒絕服務弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1965">CVE-2011-1965</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">3</a> – 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">這是一項拒絕服務的弱點</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221880">MS11-065</a></td>
<td style="border:1px solid black;">遠端桌面通訊協定弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1968">CVE-2011-1968</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">3</a> – 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">我們已接獲消息，指出有人利用此弱點進行有限的目標式攻擊<br />
<br />
這是一項拒絕服務的弱點</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221536">MS11-066</a></td>
<td style="border:1px solid black;">圖表控制項資訊洩漏弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1977">CVE-2011-1977</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">3</a> – 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊洩漏的弱點</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=223643">MS11-067</a></td>
<td style="border:1px solid black;">Report Viewer 控制項 XSS 弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1976">CVE-2011-1976</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">3</a> – 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊洩漏的弱點</td>
</tr>
</tbody>
</table>
  
受影響的軟體及下載位置  
----------------------
  
<span></span>
下表依據主要的軟體類別和嚴重性依序列出公告。
  
**我該如何使用這些表格？**
  
請用這些表格來瞭解可能需要安裝的安全性更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的安全性更新。若軟體程式或更新出現在清單中，則相關可用軟體更新也會以超連結方式提供，也會列出軟體更新的嚴重性等級。
  
**注意**：一項弱點，可能需要安裝數個安全性更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
#### Windows 作業系統與元件
  
**表 1**

 
<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="7">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-057**](http://go.microsoft.com/fwlink/?linkid=221946)
</td>
<td style="border:1px solid black;">
[**MS11-058**](http://go.microsoft.com/fwlink/?linkid=221812)
</td>
<td style="border:1px solid black;">
[**MS11-059**](http://go.microsoft.com/fwlink/?linkid=221539)
</td>
<td style="border:1px solid black;">
[**MS11-061**](http://go.microsoft.com/fwlink/?linkid=217099)
</td>
<td style="border:1px solid black;">
[**MS11-062**](http://go.microsoft.com/fwlink/?linkid=223669)
</td>
<td style="border:1px solid black;">
[**MS11-063**](http://go.microsoft.com/fwlink/?linkid=221864)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
無
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
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=90312c78-1fbd-4143-b2e6-ae5c48af6f57)  
(重大)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=a771c93b-55a4-456f-a315-d0d1f2696960)  
(重大)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=5feb8ed7-99d2-4dd6-986f-57a7fd0c6f19)  
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
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=6bc1f0ac-223d-4b0b-86cd-2ba3863955c4)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=0231c103-c0cb-4705-9d92-5356b8cbb265)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=23d77f3b-13f8-49f3-9c3c-27ad217cd59e)  
(重大)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=acb14d82-a801-4ec7-84cc-9f131009ebcb)  
(重大)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=272c813b-bd39-4e63-9fa7-c5b8ed0b08d7)  
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
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d5ee6787-408d-4870-af70-9338158b161b)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=09276f6e-e3f4-4b7e-996e-4ec376c103e1)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-057**](http://go.microsoft.com/fwlink/?linkid=221946)
</td>
<td style="border:1px solid black;">
[**MS11-058**](http://go.microsoft.com/fwlink/?linkid=221812)
</td>
<td style="border:1px solid black;">
[**MS11-059**](http://go.microsoft.com/fwlink/?linkid=221539)
</td>
<td style="border:1px solid black;">
[**MS11-061**](http://go.microsoft.com/fwlink/?linkid=217099)
</td>
<td style="border:1px solid black;">
[**MS11-062**](http://go.microsoft.com/fwlink/?linkid=223669)
</td>
<td style="border:1px solid black;">
[**MS11-063**](http://go.microsoft.com/fwlink/?linkid=221864)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性** **等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
無
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
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=26b5fb48-346a-49f1-840f-03f218a41c20)  
(重要)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=042552ad-f46a-4bfc-9e5c-58f095eba1de)  
(重大)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=648596fc-fd97-438a-97be-d5d590f1c561)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c2d4aa38-9241-465d-8d65-aba73e936d0f)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8de0f2db-aa09-48cd-a13b-e26a973e9cdc)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=870fdfdd-16bf-42a2-a23b-ed6045438d5e)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=9c3d14d8-6716-4423-91a9-a05373227237)  
(重要)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=c9e283d8-d4a2-41e2-a73c-92fae957ba3d)  
(重大)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=470d56d1-5789-42cc-a088-a2c8ac934ab3)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2db4098a-f4f9-4211-b55d-5d0df1409c43)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8f208407-4bb3-41fe-b0d6-fc8a5e30e667)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=31af27b8-7b73-4090-94bd-2fb89d3970fc)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=64496a87-2225-402a-a94a-a8e92b17ac83)  
(重要)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=5aa3a493-4188-48a9-a549-cf9ba01ed32a)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=1934acfa-5637-4ae9-9e9a-fc7e58930b7a)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=ef140089-d022-4ee8-9cc4-7fb25295a39d)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=410c72d8-3b78-4c4a-ad61-acb7f854ffc2)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-057**](http://go.microsoft.com/fwlink/?linkid=221946)
</td>
<td style="border:1px solid black;">
[**MS11-058**](http://go.microsoft.com/fwlink/?linkid=221812)
</td>
<td style="border:1px solid black;">
[**MS11-059**](http://go.microsoft.com/fwlink/?linkid=221539)
</td>
<td style="border:1px solid black;">
[**MS11-061**](http://go.microsoft.com/fwlink/?linkid=217099)
</td>
<td style="border:1px solid black;">
[**MS11-062**](http://go.microsoft.com/fwlink/?linkid=223669)
</td>
<td style="border:1px solid black;">
[**MS11-063**](http://go.microsoft.com/fwlink/?linkid=221864)
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
無
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=66ddc7ce-5280-494d-bb3c-dab06e27fb5c)  
(重大)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=a080f36e-c24f-40ac-bb40-b26cb31bcae3)  
(重大)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=c82417ec-232f-4f84-ba2c-0ffad77e9bb5)  
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
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8f25ced5-ef86-4b9d-91fb-443c9a2c1458)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=3f119902-8398-4814-8229-9eb9f0980e87)  
(重大)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=704c1c9c-d1c1-40cb-97a7-fbb1f195f9f8)  
(重大)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=a6ff7b27-bc21-4945-8b2e-757b6f83fa58)  
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
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d5b8ff09-237e-49f1-a566-e323ca11fbc3)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-057**](http://go.microsoft.com/fwlink/?linkid=221946)
</td>
<td style="border:1px solid black;">
[**MS11-058**](http://go.microsoft.com/fwlink/?linkid=221812)
</td>
<td style="border:1px solid black;">
[**MS11-059**](http://go.microsoft.com/fwlink/?linkid=221539)
</td>
<td style="border:1px solid black;">
[**MS11-061**](http://go.microsoft.com/fwlink/?linkid=217099)
</td>
<td style="border:1px solid black;">
[**MS11-062**](http://go.microsoft.com/fwlink/?linkid=223669)
</td>
<td style="border:1px solid black;">
[**MS11-063**](http://go.microsoft.com/fwlink/?linkid=221864)
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
無
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=da9c98d1-973c-44d9-aee5-f5c4a8e8c0e1)\*\*  
(重大)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d65ae4cc-d82a-42da-829f-d9479e23b7a5)\*\*  
(重大)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=70065bd0-7c97-4ffc-828f-2cc245d04429)\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ac2d5122-6f9b-46f5-9840-77aa7ff84308)\*  
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
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1fbaabb9-8601-4760-813d-aeedfdcafb8b)\*  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=9facff69-618f-4a64-8665-5dd6cde07de9)\*\*  
(重大)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=00f28d81-3714-403c-bcd7-55f2ac97f75b)\*\*  
(重大)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=9ce60689-ca85-4c9f-af96-a73b1e43c10b)\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5f605f6f-3854-403d-878b-637626aef78f)\*  
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
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2e7253d8-fdc7-4563-9714-21ca3c77e4b1)\*  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=01885624-cfb1-4918-abef-ab0ea765cb04)  
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
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=fe37eb6d-b1fa-496c-a0d3-19a6d35a6cb9)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-057**](http://go.microsoft.com/fwlink/?linkid=221946)
</td>
<td style="border:1px solid black;">
[**MS11-058**](http://go.microsoft.com/fwlink/?linkid=221812)
</td>
<td style="border:1px solid black;">
[**MS11-059**](http://go.microsoft.com/fwlink/?linkid=221539)
</td>
<td style="border:1px solid black;">
[**MS11-061**](http://go.microsoft.com/fwlink/?linkid=217099)
</td>
<td style="border:1px solid black;">
[**MS11-062**](http://go.microsoft.com/fwlink/?linkid=223669)
</td>
<td style="border:1px solid black;">
[**MS11-063**](http://go.microsoft.com/fwlink/?linkid=221864)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=7019de24-8c58-4565-ada1-ca8755115096)  
(重大)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=12292081-23f7-4968-8cd7-17aaef2aed6a)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6bc168d9-6664-41fb-914f-dbd7514a4b0e)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=f4551b77-eb09-448a-9dc5-66de846035e7)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=fcdb872f-2ee2-4f74-b7ae-1b82daf66761)  
(重大)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=ef664114-6582-49d3-b332-078a7d075337)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=aafeff2d-db9a-4b3b-b620-be4ec5f5bdcc)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=0fc9a501-523d-4cbb-8d99-a773089afc4c)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-057**](http://go.microsoft.com/fwlink/?linkid=221946)
</td>
<td style="border:1px solid black;">
[**MS11-058**](http://go.microsoft.com/fwlink/?linkid=221812)
</td>
<td style="border:1px solid black;">
[**MS11-059**](http://go.microsoft.com/fwlink/?linkid=221539)
</td>
<td style="border:1px solid black;">
[**MS11-061**](http://go.microsoft.com/fwlink/?linkid=217099)
</td>
<td style="border:1px solid black;">
[**MS11-062**](http://go.microsoft.com/fwlink/?linkid=223669)
</td>
<td style="border:1px solid black;">
[**MS11-063**](http://go.microsoft.com/fwlink/?linkid=221864)
</td>
</tr>
<tr class="alternateRow">
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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=14fe68eb-2aa6-4a59-b9d8-deeae5236af2)\*\*  
(重大)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=dd709da2-4cb1-482f-88eb-dfab4d3c59c6)\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6a86e2cf-4e7d-4012-88c3-6957a3842dd3)\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=c29deec3-4672-4658-a550-dce244434cd4)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=777f3bbe-094c-411d-879d-34a5a20ae7f3)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=2f4043df-c07c-4611-b06a-7fcbb7416e7d)\*  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 和適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=82403fd3-ed75-4ea8-aa3f-ed9dda75612a)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2 和適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=1d6b8036-d38f-408a-a36c-027553faefc1)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2 和適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b420cae3-de30-4c6c-8ed9-7431ad7ab4da)  
(重要)
</td>
</tr>
</table>
 
**Windows Server 2008 和 Windows Server 2008 R2 注意事項**

**\*會影響 Server Core 安裝。**無論上述受支援的 Windows Server 2008 或 Windows Server 2008 R2 版本是否使用 Server Core 安裝選項安裝，這個更新均以相同的嚴重性等級套用。如需此安裝選項的詳細資訊，請參閱 TechNet 文章：[管理 Server Core 安裝](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (英文) 和[維護 Server Core 安裝](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 和 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**\*\*Server Core 安裝不受影響。**如果 Windows Server 2008 或 Windows Server 2008 R2 是使用 Server Core 安裝選項所安裝，則這項更新解決的弱點並不會影響受支援的 Windows Server 2008 或 Windows Server 2008 R2。如需此安裝選項的詳細資訊，請參閱 TechNet 文章：[管理 Server Core 安裝](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (英文) 和[維護 Server Core 安裝](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 和 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**表 2**

 
<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="6">
Windows XP
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-064**](http://go.microsoft.com/fwlink/?linkid=221808)
</td>
<td style="border:1px solid black;">
[**MS11-065**](http://go.microsoft.com/fwlink/?linkid=221880)
</td>
<td style="border:1px solid black;">
[**MS11-066**](http://go.microsoft.com/fwlink/?linkid=221536)
</td>
<td style="border:1px solid black;">
[**MS11-068**](http://go.microsoft.com/fwlink/?linkid=223578)
</td>
<td style="border:1px solid black;">
[**MS11-069**](http://go.microsoft.com/fwlink/?linkid=221537)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=c07e1630-43ba-491e-bd59-9eb53105986c)  
(中度)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc)  
(KB2539631)  
(中度)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(中度)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=797a01dc-39fb-4511-832a-42d2975133f5)  
(中度)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc)  
(KB2539631)  
(中度)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(中度)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-064**](http://go.microsoft.com/fwlink/?linkid=221808)
</td>
<td style="border:1px solid black;">
[**MS11-065**](http://go.microsoft.com/fwlink/?linkid=221880)
</td>
<td style="border:1px solid black;">
[**MS11-066**](http://go.microsoft.com/fwlink/?linkid=221536)
</td>
<td style="border:1px solid black;">
[**MS11-068**](http://go.microsoft.com/fwlink/?linkid=223578)
</td>
<td style="border:1px solid black;">
[**MS11-069**](http://go.microsoft.com/fwlink/?linkid=221537)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=694ba1a6-7512-497d-a572-646a6e07b13b)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc)  
(KB2539631)  
(中度)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(中度)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=308da543-d49d-4591-8bbc-d65c524bb0ad)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc)  
(KB2539631)  
(中度)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(中度)
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
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=3b459bf0-7844-4740-895c-d149d56e781f)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc)  
(KB2539631)  
(中度)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(中度)
</td>
</tr>
<tr>
<th colspan="6">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-064**](http://go.microsoft.com/fwlink/?linkid=221808)
</td>
<td style="border:1px solid black;">
[**MS11-065**](http://go.microsoft.com/fwlink/?linkid=221880)
</td>
<td style="border:1px solid black;">
[**MS11-066**](http://go.microsoft.com/fwlink/?linkid=221536)
</td>
<td style="border:1px solid black;">
[**MS11-068**](http://go.microsoft.com/fwlink/?linkid=223578)
</td>
<td style="border:1px solid black;">
[**MS11-069**](http://go.microsoft.com/fwlink/?linkid=221537)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=114c2835-921a-4d3e-be91-dfd217fd26a9)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9713b7b8-f260-440d-a994-845f17683fe9)  
(中度)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834)  
(KB2539633)  
(中度)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(中度)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0fcee476-8d7e-49a7-b6ea-89043304a653)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4d67ec00-e86a-49b6-a9a2-85b2520fa4bb)  
(中度)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834)  
(KB2539633)  
(中度)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(中度)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-064**](http://go.microsoft.com/fwlink/?linkid=221808)
</td>
<td style="border:1px solid black;">
[**MS11-065**](http://go.microsoft.com/fwlink/?linkid=221880)
</td>
<td style="border:1px solid black;">
[**MS11-066**](http://go.microsoft.com/fwlink/?linkid=221536)
</td>
<td style="border:1px solid black;">
[**MS11-068**](http://go.microsoft.com/fwlink/?linkid=223578)
</td>
<td style="border:1px solid black;">
[**MS11-069**](http://go.microsoft.com/fwlink/?linkid=221537)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c01d9132-af5f-4039-8195-95f6761f2d0e)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)\*\*<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=da219735-b8b7-4f97-b8a8-7c253838de6b)\*\*\*  
(中度)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834)\*\*  
(KB2539633)  
(中度)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)\*\*<sup>[1]</sup>
(KB2539636)  
(中度)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=70797adb-d693-4102-9e7c-ba1ea8fb07d0)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)\*\*<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8e077af5-5823-4377-a997-44b022a694d8)\*\*\*  
(中度)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834)\*\*  
(KB2539633)  
(中度)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)\*\*<sup>[1]</sup>
(KB2539636)  
(中度)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9babf81a-8b21-42ae-a65c-f414793516ab)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=560efa6f-c956-47cb-a2f4-a1f45278b7cd)  
(中度)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834)  
(KB2539633)  
(中度)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(中度)
</td>
</tr>
<tr>
<th colspan="6">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-064**](http://go.microsoft.com/fwlink/?linkid=221808)
</td>
<td style="border:1px solid black;">
[**MS11-065**](http://go.microsoft.com/fwlink/?linkid=221880)
</td>
<td style="border:1px solid black;">
[**MS11-066**](http://go.microsoft.com/fwlink/?linkid=221536)
</td>
<td style="border:1px solid black;">
[**MS11-068**](http://go.microsoft.com/fwlink/?linkid=223578)
</td>
<td style="border:1px solid black;">
[**MS11-069**](http://go.microsoft.com/fwlink/?linkid=221537)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=814bbdfa-7cbc-40e5-8ca3-8fed9d13ff00)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6c8dd72b-abf8-4e1f-aafc-777c1a3ef3db)  
(中度)
</td>
<td style="border:1px solid black;">
僅適用於 32 位元系統的 Windows 7：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=b8c628c6-5dcc-4c8f-b379-e2249a44f12c)  
(KB2539634)  
(中度)  
僅適用於 32 位元系統的 Windows 7：  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(中度)  
僅適用於 32 位元系統的 Windows 7 Service Pack 1：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=e1f84749-77bb-42bf-a539-fb647cacff8b)  
(KB2539635)  
(中度)  
僅適用於 32 位元系統的 Windows 7 Service Pack 1：  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(中度)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=085ee785-b6ad-4c68-835a-e17bc8f12a53)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=d90c07c1-3c07-4989-825c-fb8453541a0e)  
(中度)
</td>
<td style="border:1px solid black;">
僅適用於 x64 型系統的 Windows 7：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=b8c628c6-5dcc-4c8f-b379-e2249a44f12c)  
(KB2539634)  
(中度)  
僅適用於 x64 型系統的 Windows 7：  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(中度)  
僅適用於 x64 型系統的 Windows 7 Service Pack 1：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=e1f84749-77bb-42bf-a539-fb647cacff8b)  
(KB2539635)  
(中度)  
僅適用於 x64 型系統的 Windows 7 Service Pack 1：  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(中度)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-064**](http://go.microsoft.com/fwlink/?linkid=221808)
</td>
<td style="border:1px solid black;">
[**MS11-065**](http://go.microsoft.com/fwlink/?linkid=221880)
</td>
<td style="border:1px solid black;">
[**MS11-066**](http://go.microsoft.com/fwlink/?linkid=221536)
</td>
<td style="border:1px solid black;">
[**MS11-068**](http://go.microsoft.com/fwlink/?linkid=223578)
</td>
<td style="border:1px solid black;">
[**MS11-069**](http://go.microsoft.com/fwlink/?linkid=221537)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=9fd2b4ba-d98e-4ad6-99f2-c471335042d3)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
僅適用於 x64 型系統的 Windows Server 2008 R2：  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(重要)  
僅適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1：  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)\*<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=67cccd09-5b82-4546-884a-d2a9e2400820)\*\*\*  
(中度)
</td>
<td style="border:1px solid black;">
僅適用於 x64 型系統的 Windows Server 2008 R2：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=b8c628c6-5dcc-4c8f-b379-e2249a44f12c)\*  
(KB2539634)  
(中度)  
僅適用於 x64 型系統的 Windows Server 2008 R2：  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(中度)  
僅適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=e1f84749-77bb-42bf-a539-fb647cacff8b)\*  
(KB2539635)  
(中度)  
僅適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1：  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)\*<sup>[1]</sup>
(KB2539636)  
(中度)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 和適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2 和適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=93752c8f-5461-4e6f-9cab-6401b985ef17)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2 和適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=a1edf843-9a2a-4334-a95f-78e75a9b3ef1)  
(中度)
</td>
<td style="border:1px solid black;">
僅適用於 Itanium 型系統的 Windows Server 2008 R2：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=b8c628c6-5dcc-4c8f-b379-e2249a44f12c)  
(KB2539634)  
(中度)  
僅適用於 Itanium 型系統的 Windows Server 2008 R2：  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(中度)  
僅適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=e1f84749-77bb-42bf-a539-fb647cacff8b)  
(KB2539635)  
(中度)  
僅適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1：  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(中度)
</td>
</tr>
</table>
 
**Windows Server 2008 和 Windows Server 2008 R2 注意事項**

**\*會影響 Server Core 安裝。**無論上述受支援的 Windows Server 2008 或 Windows Server 2008 R2 版本是否使用 Server Core 安裝選項安裝，這個更新均以相同的嚴重性等級套用。如需此安裝選項的詳細資訊，請參閱 TechNet 文章：[管理 Server Core 安裝](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (英文) 和[維護 Server Core 安裝](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 和 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**\*\*Server Core 安裝不受影響。**如果 Windows Server 2008 或 Windows Server 2008 R2 是使用 Server Core 安裝選項所安裝，則這項更新解決的弱點並不會影響受支援的 Windows Server 2008 或 Windows Server 2008 R2。如需此安裝選項的詳細資訊，請參閱 TechNet 文章：[管理 Server Core 安裝](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (英文) 和[維護 Server Core 安裝](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 和 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**\*\*\*Server Core 安裝不受影響。** 如果 Windows Server 2008 或 Windows Server 2008 R2 是使用 Server Core 安裝選項所安裝，即使受到此弱點影響的檔案可能會出現在系統上，這項更新解決的弱點並不會影響受支援的 Windows Server 2008 或 Windows Server 2008 R2 版本。但是我們仍會將此更新提供給具有受影響之檔案的使用者，因為相較於您系統上目前的檔案，此更新檔案較新 (其版本號碼較高)。如需此安裝選項的詳細資訊，請參閱 TechNet 文章：[管理 Server Core 安裝](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (英文) 和[維護 Server Core 安裝](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 和 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**MS11-066 注意事項**

<sup>[1]</sup>**.NET Framework 4 Client Profile 不受影響。**可在兩個設定檔中使用 .NET Framework 第 4 版可轉散發套件： .NET Framework 4 和 .NET Framework 4 Client Profile。.NET Framework 4 Client Profile 是 .NET Framework 4 的子集。此更新所解決的弱點只會影響到 .NET Framework 4 ，而不會影響到 .NET Framework 4 Client Profile。如需詳細資訊，請參閱 MSDN 文章：[安裝 .NET Framework](http://msdn.microsoft.com/zh-tw/library/5a4x27ek.aspx)。

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

**MS11-069 注意事項**

<sup>[1]</sup>**.NET Framework 4 和 .NET Framework 4 Client Profile 會受到影響。**可在兩個設定檔中使用 .NET Framework 第 4 版可轉散發套件： .NET Framework 4 和 .NET Framework 4 Client Profile。.NET Framework 4 Client Profile 是 .NET Framework 4 的子集。此更新所解決的弱點會同時影響到 .NET Framework 4 和 .NET Framework 4 Client Profile。如需詳細資訊，請參閱 MSDN 文章：[安裝 .NET Framework](http://msdn.microsoft.com/zh-tw/library/5a4x27ek.aspx)。

#### Microsoft Office 套件及軟體

 
<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Visio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-060**](http://go.microsoft.com/fwlink/?linkid=223425)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=866d64b3-7147-4b5f-80fe-4d3317f140df)  
(KB2553009)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a0eeabde-5a92-45ae-aef6-81b7bdb4e0cd)  
(KB2553010)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2010 和 Microsoft Visio 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2010 和 Microsoft Visio 2010 Service Pack 1 (32 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=6da236c2-0ef5-4c13-8393-673b70298a77)  
(KB2553008)  
(重要)  
[Microsoft Visio 2010 和 Microsoft Visio 2010 Service Pack 1 (64 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=b7f5f2a9-116a-41ef-a19e-a7dd0947d2cb)  
(KB2553008)  
(重要)
</td>
</tr>
</table>
 

#### Microsoft 開發者工具和軟體

 
<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="3">
圖表控制項
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-066**](http://go.microsoft.com/fwlink/?linkid=221536)
</td>
<td style="border:1px solid black;">
[**MS11-067**](http://go.microsoft.com/fwlink/?linkid=223643)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Microsoft .NET Framework 3.5 Service Pack 1 的圖表控制項
</td>
<td style="border:1px solid black;">
[適用於 Microsoft .NET Framework 3.5 Service Pack 1 的圖表控制項](https://www.microsoft.com/download/details.aspx?familyid=8a80cc03-0db9-4446-9ce6-159ad02cab52)  
(KB2500170)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Visual Studio 和 Microsoft Report Viewer
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-066**](http://go.microsoft.com/fwlink/?linkid=221536)
</td>
<td style="border:1px solid black;">
[**MS11-067**](http://go.microsoft.com/fwlink/?linkid=223643)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2005 Service Pack 1
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=59231988-5413-4238-a3aa-32a127871430)  
(KB2548826)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Report Viewer 2005 Service Pack 1 Redistributable Package
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2005 Service Pack 1 Redistributable Package](https://www.microsoft.com/download/details.aspx?familyid=28bf2ae0-9e21-4201-b7f1-a207abc2866f)  
(KB2579115)  
(重要)
</td>
</tr>
</table>
 
**MS11-066 注意事項**

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和安全性更新。如需更多資訊，請參閱 [TechNet 更新管理中心](http://go.microsoft.com/fwlink/?linkid=69903) (英文)。[TechNet 資訊安全技術中心](http://go.microsoft.com/fwlink/?linkid=21171)提供 Microsoft 產品安全性的其他資訊。消費者可以造訪[在家上網的安全性](http://go.microsoft.com/fwlink/?linkid=85102)網站，只要按一下 \[最新安全性更新\] 即可在此網站取得此資訊。

安全性更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 以及 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) 取得。安全性更新也可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得。您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。

對於 Microsoft Office for Mac 的客戶，Microsoft AutoUpdate for Mac 可協助您保持最新的 Microsoft 軟體。如需使用 Microsoft AutoUpdate for Mac 的詳細資訊，請參閱[自動檢查軟體更新](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea) (英文)。

最後，您可以從 [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) 下載安全性更新。Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括安全性更新、驅動程式和 Service Pack。只要以安全性公告編號 (例如：MS07-036) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](http://go.microsoft.com/fwlink/?linkid=97900)。

**偵測與部署指南**

Microsoft 針對安全性更新提供偵測和部署指南。本指南所含之建議和資訊，能幫助 IT 專業人員瞭解如何使用用於安全性更新的偵測和部署的各種工具。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 961747](http://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少安全性更新以及一般安全性設定錯誤的狀況。如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速而可靠地將 Microsoft Windows 2000 作業系統及更新版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 適用的最新重大更新與安全性更新部署到 Microsoft Windows 2000 及更新版本的作業系統中。

如需更多關於利用 Windows Server Update Services 部署安全性更新的資訊，請造訪 [Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/default.aspx) (英文)。

**System Center Configuration Manager 2007**

Configuration Manager 2007 軟體更新管理可簡化遞送和管理企業中 IT 系統更新的繁複作業。IT 系統管理員可以使用 Configuration Manager 2007 遞送 Microsoft 產品更新給各種裝置，包括桌上型電腦、筆記型電腦、伺服器及行動裝置。

Configuration Manager 2007 中的自動弱點評估會找出更新需求並報告建議動作。Configuration Manager 2007 中的軟體更新管理是建置在 Microsoft Windows Software Update Services (WSUS) 上，經過時間考驗，為全球 IT 系統管理員所熟悉的更新基礎架構。如需更多有關系統管理員如何使用 Configuration Manager 2007 來部署更新的資訊，請參閱[軟體更新管理](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx) (英文)。如需更多有關 Configuration Manager 的資訊，請造訪 [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx)。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。

**注意：**System Management Server 2003 自 2010 年 1 月 12 日起不受主流支援。如需更多有關產品生命週期的資訊，請造訪 [Microsoft 支援週期](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle)。現已推出新版的 SMS：System Center Configuration Manager 2007；請參閱前段的＜System Center Configuration Manager 2007＞一節。

如需更多有關系統管理員如何使用 SMS 2003 來部署安全性更新的資訊，請參閱 [Microsoft Systems Management Server 2003 的案例與程序： 軟體發佈和補充程式管理](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en) (英文)。如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server 技術中心 (TechCenter)](http://technet.microsoft.com/zh-tw/systemcenter/bb545936.aspx)。

**注意** ：SMS 使用 Microsoft Baseline Security Analyzer 提供廣泛的安全性公告更新偵測與部署支援。不過這些工具可能無法偵測部分的軟體更新。在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](http://go.microsoft.com/fwlink/?linkid=33341) (英文)。某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。系統管理員可使用 Elevated Rights Deployment Tool (隨附於 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)) 來安裝這些更新。

**Update Compatibility Evaluator 和應用程式相容性工具組**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。這可能會觸發不相容性，而拉長部署安全性更新的時間。您可以使用 [Application Compatibility Toolkit](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 隨附的 [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 元件，針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Microsoft Windows Vista、Windows Update、Microsoft 安全性更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非安全性更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](http://support.microsoft.com/kb/894199)： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](http://technet.microsoft.com/en-us/wsus/bb456965.aspx)。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的安全性保護，Microsoft 將在每月發行安全性更新之前，提前向重要安全性軟體提供者提供弱點資訊。安全性軟體提供者可利用此弱點資訊，透過其安全性軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有安全性軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://go.microsoft.com/fwlink/?linkid=215201) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 安全性策略與社群

**更新程式管理策略**

[更新管理安全性指南](http://go.microsoft.com/fwlink/?linkid=21168) (英文) 提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   消費性平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](http://support.microsoft.com/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員安全性社群](http://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](http://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 [Opera Software ASA](http://www.opera.com/) 的 Yngve N. Pettersen 回報 MS11-057 中描述的一個問題
-   感謝 [Lostmon Lords](http://lostmon.blogspot.com) 回報 MS11-057 中描述的一個問題
-   感謝 [Security Professionals Network Inc.](http://www.sec-pro.net/) 的 Makoto Shiotsuki 回報 MS11-057 中描述的一個問題
-   感謝匿名的研究人員與 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 MS11-057 中描述的一個問題
-   感謝 [Harmony Security](http://www.harmonysecurity.com/) 的 Stephen Fewer 與 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 MS11-057 中描述的兩個問題
-   感謝 [Google Inc.](http://www.google.com/) 的 Michal Zalewski 協助我們進行 ms11-057 中所述之深度防禦變更
-   感謝 Grischa Zengel ([Zengel Medizintechnik GmbH](http://www.zmt.info/)) 回報 MS11-058 中描述的一個問題
-   感謝 [Baidu Security Team](http://www.baidu.com) 的 Linlin Zhao 回報 MS11-060 中描述的兩個問題
-   感謝 Sven Taute 回報 MS11-061 中描述的一個問題
-   感謝 的 Lufeng Li 回報 MS11-062 中描述的一個問題
-   感謝 Winsider Seminars & Solutions Inc. 的 Alex Ionescu 回報 MS11-063 中描述的一個問題
-   感謝 Context Information Security 的 Nico Leidecker 和 James Forshaw 回報 MS11-066 中描述的一個問題
-   感謝 [Gotham Digital Science](http://www.gdssecurity.com/) 的 Adam Bixby 回報 MS11-067 中描述的一個問題
-   感謝 [Qihoo 360 Security Center](http://www.360.cn/) 的 Zheng Wenbin 回報 MS11-068 中描述的一個問題
-   感謝 Michael J. Liu 回報 MS11-069 中描述的一個問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 支援週期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可洽詢[安全性支援](http://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 以取得技術支援。與安全性更新有關的支援電話不另外收費。如需更多可用支援選項的資訊，請參閱 [Microsoft 技術支援](http://support.microsoft.com/)。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。與安全性更新有關的支援電話不另外收費。如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[國際化支援](http://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2011 年 8 月 9 日)： 公告摘要發行。
-   V1.1 (2011 年 8 月 10 日)： 針對 MS11-059，更正＜提要＞一節中的重新開機需求資訊。針對 MS11-065，更正＜弱點索引＞中 CVE-2011-1968 的主要重點。針對 MS11-068，修訂 Windows Server 2008 和 Windows Server 2008 R2 的 Server Core 標註。
-   V1.2 (2011 年 10 月 26 日)： 針對 MS11-066 和 MS11-069，更正 x64 型系統 Windows Server 2008 R2 上 .NET Framework 4 的 Server Core 安裝適用性。

*Built at 2014-04-18T01:50:00Z-07:00*
