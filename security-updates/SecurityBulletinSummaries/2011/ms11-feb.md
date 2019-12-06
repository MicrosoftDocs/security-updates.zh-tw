---
TOCTitle: 'MS11-FEB'
Title: 2011 年 2 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms11-feb'
ms:contentKeyID: 61237716
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms11-feb(v=Security.10)'
---

2011 年 2 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2011年2月9日

**版本:** 1.0

此公告摘要列出 2011 年 2 月份發行之 資訊安全公告。

發行 2011 年 2 月份 資訊安全公告之後，此公告摘要將取代原先於 2011 年 2 月 3 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 資訊安全公告預先通知](http://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2011 年 2 月 8 日，太平洋時間早上 11 點 (美國與加拿大) 解答客戶對於這些公告的問題。 立即註冊參加 [2 月份 資訊安全公告網路廣播](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032455047&eventcategory=4)。 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 資訊安全公告摘要和網路廣播](http://www.microsoft.com/taiwan/security/bulletins/default.mspx)。

Microsoft 也會提供資訊協助客戶排定每月 資訊安全更新以及任何非 資訊安全更新的優先順序，其中這些非 資訊安全更新的發行日期與每月 資訊安全更新的發行日期相同。 請參閱＜其他資訊＞一節。

### 公告資訊

提要
----

<span></span>
下表依嚴重性摘要說明本月份 資訊安全公告。

如需受影響的軟體之詳細資料，請參閱下節＜受影響的軟體及下載位置＞。

 
<p> </p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >公告編號</th>
<th style="border:1px solid black;" >公告標題與提要</th>
<th style="border:1px solid black;" >最高的嚴重性等級與資訊安全風險影響</th>
<th style="border:1px solid black;" >重新開機需求</th>
<th style="border:1px solid black;" >受影響的軟體</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-003">MS11-003</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 積存 資訊安全更新 (2482017)</strong><br />
<br />
這個 資訊安全更新可解決 Internet Explorer 中兩項未公開報告的資訊安全風險，以及兩項公開揭露的資訊安全風險。 若使用者用 Internet Explorer 檢視蓄意製作的網頁，或使用者開啟合法 HTML 檔案但載入蓄意製作的程式庫檔案，這些資訊安全風險可能允許遠端執行程式碼。 成功利用這類任一資訊安全風險的攻擊者可以取得與本機使用者相同的使用者權限。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-006">MS11-006</a></td>
<td style="border:1px solid black;"><strong>Windows Shell 圖形處理的資訊安全風險可能會允許遠端執行程式碼 (2483185)</strong><br />
<br />
此 資訊安全更新可解決 Windows Shell 圖形處理器中一項公開揭露的資訊安全風險。 如果使用者檢視蓄意製作的縮圖影像，此資訊安全風險可能會允許遠端執行程式碼。 成功利用此資訊安全風險的攻擊者可以取得與登入使用者相同的使用者權限。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-007">MS11-007</a></td>
<td style="border:1px solid black;"><strong>OpenType 壓縮字型格式 (CFF) 驅動程式中的資訊安全風險可能會允許遠端執行程式碼 (2485376)</strong><br />
<br />
此 資訊安全更新可解決 Windows OpenType 壓縮字型格式 (CFF) 驅動程式中一項未公開報告的資訊安全風險。 如果使用者檢視以蓄意製作的 CFF 字型所呈現的內容，則該資訊安全風險可能會允許遠端執行程式碼。 但是，攻擊者無法強迫使用者檢視蓄意製作的內容， 而是引誘使用者自行前往某網站。一般的做法是設法讓使用者按一下電子郵件或 Instant Messenger 訊息中通往攻擊者網站的連結。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-004">MS11-004</a></td>
<td style="border:1px solid black;"><strong>Internet Information Services (IIS) FTP 服務的資訊安全風險可能允許遠端執行程式碼 (2489256)</strong><br />
<br />
此 資訊安全更新可解決 Microsoft Internet Information Services (IIS) FTP 服務中一個公開揭發的資訊安全風險。 若 FTP 伺服器收到一個蓄意製作的 FTP 命令，此資訊安全風險可能允許遠端執行程式碼。 依預設，FTP 服務不是安裝在 IIS 上。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-005">MS11-005</a></td>
<td style="border:1px solid black;"><strong>Active Directory 中的資訊安全風險可能會允許拒絕服務 (2478953)</strong><br />
<br />
此 資訊安全更新可解決 Active Directory 中一項公開揭露的資訊安全風險。 如果攻擊者傳送蓄意製作的封包到受影響的 Active Directory 伺服器，則此資訊安全風險可能會允許拒絕服務。 攻擊者必須在加入網域的電腦上擁有有效的本機系統管理員權限，才能利用這個資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
拒絕服務</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-008">MS11-008</a></td>
<td style="border:1px solid black;"><strong>Microsoft Visio 中的資訊安全風險可能會允許遠端執行程式碼 (2451879)</strong><br />
<br />
這個 資訊安全更新可解決 Microsoft Visio 中兩項未公開報告的資訊安全風險。 如果使用者開啟蓄意製作的 Visio 檔案，此資訊安全風險可能會允許遠端執行程式碼。 成功利用其中一項資訊安全風險的攻擊者可以取得與登入使用者相同的使用者權限。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-009">MS11-009</a></td>
<td style="border:1px solid black;"><strong>JScript 和 VBScript 指令碼引擎中的資訊安全風險可能會允許資訊洩漏 (2475792)</strong><br />
<br />
這個 資訊安全更新能解決 JScript 和 VBScript 指令碼引擎中一項未公開報告的資訊安全風險。 如果使用者造訪蓄意製作的網站，此資訊安全風險便可能允許資訊洩漏。 攻擊者並不能強迫使用者造訪這些網站。 而是引誘使用者自行前往。一般的做法是設法讓使用者按一下電子郵件或 Instant Messenger 訊息中通往攻擊者網站的連結。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
資訊洩漏</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-010">MS11-010</a></td>
<td style="border:1px solid black;"><strong>Windows Client/Server Run-time Subsystem 中的資訊安全風險可能會允許權限提高 (2476687)</strong><br />
<br />
這個 資訊安全更新可解決 Windows XP 和 Windows Server 2003 中 Microsoft Windows Client/Server Run-time Subsystem (CSRSS) 一個未公開報告的資訊安全風險。<br />
<br />
如果攻擊者登入使用者的系統並啟動一個蓄意製作的應用程式，並使其在攻擊者登出之後繼續執行以取得後續使用者的登入認證，這個資訊安全風險可能允許權限提高。 攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項資訊安全風險。 匿名或遠端使用者無法利用這個資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-011">MS11-011</a></td>
<td style="border:1px solid black;"><strong>Windows 核心中的資訊安全風險可能會允許權限提高 (2393802)</strong><br />
<br />
這個 資訊安全更新可解決 Microsoft Windows 中一項公開揭露的資訊安全風險和一項未公開報告的資訊安全風險。 如果攻擊者從本機登入並執行蓄意製作的應用程式，則可能會允許權限提高。 攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這些資訊安全風險。 遠端或匿名使用者無法利用這個資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-012">MS11-012</a></td>
<td style="border:1px solid black;"><strong>Windows 核心模式驅動程式中的資訊安全風險可能會允許權限提高 (2479628)</strong><br />
<br />
這個 資訊安全更新可解決 Microsoft Windows 中五個未公開報告的資訊安全風險。 如果攻擊者從本機登入並執行蓄意製作的應用程式，則可能會允許權限提高。 攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這些資訊安全風險。 遠端或匿名使用者無法利用這個資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-013">MS11-013</a></td>
<td style="border:1px solid black;"><strong>Kerberos 核心中的資訊安全風險可能會允許權限提高 (2496930)</strong><br />
<br />
這個 資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險和一項公開揭露的資訊安全風險。 如果攻擊者通過驗證並在一台加入網域的電腦本機上安裝一項惡意服務，最嚴重的狀況是這些資訊安全風險可能允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-014">MS11-014</a></td>
<td style="border:1px solid black;"><strong>本地安全性授權子系統服務中的資訊安全風險可能會允許本機權限提高 (2478960)</strong><br />
<br />
這個 資訊安全更新可解決 Windows XP 和 Windows Server 2003 本地安全性授權子系統服務 (LSASS) 中一個未公開報告的資訊安全風險。<br />
<br />
如果攻擊者登入系統並執行蓄意製作的應用程式，則這個資訊安全風險可能允許權限提高。 攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項資訊安全風險。 匿名或遠端使用者無法利用這個資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
資訊安全風險索引  
----------------
  
<span></span>
下表提供本月所述每個資訊安全風險的利用性評估。資訊安全風險根據遞減的資訊安全風險評估等級及 CVE 編號依序列出。 僅包含 資訊安全公告中，嚴重性等級為「重大」或「重要」的資訊安全風險。
  
**我該如何使用這個表格？**
  
請用這個表格來瞭解您可能需要安裝的每個 資訊安全更新，與 30 天內已發行的可利用程式碼受影響之可能性。 您應該檢閱下列的每個評估，按照特定的設定，將部署以優先次序排序。 如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft資訊安全風險索引](http://technet.microsoft.com/en-us/security/cc998259.aspx)。

 
<p> </p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >公告編號</th>
<th style="border:1px solid black;" >資訊安全風險標題</th>
<th style="border:1px solid black;" >CVE ID</th>
<th style="border:1px solid black;" >資訊安全風險索引評估</th>
<th style="border:1px solid black;" >主要重點</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-006">MS11-006</a></td>
<td style="border:1px solid black;">Windows Shell 圖形處理溢位資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3970">CVE-2010-3970</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><strong>這項資訊安全風險目前已公開揭露，且有可持續利用此漏洞的程式碼。</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-003">MS11-003</a></td>
<td style="border:1px solid black;">CSS 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3971">CVE-2010-3971</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><strong>這項資訊安全風險目前已公開揭露，並在網際網路生態系統中遭到利用</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-011">MS11-011</a></td>
<td style="border:1px solid black;">驅動程式與 Windows 核心不當互動資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-4398">CVE-2010-4398</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><strong>這項資訊安全風險已經公開揭露</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-010">MS11-010</a></td>
<td style="border:1px solid black;">CSRSS 權限提高資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0030">CVE-2011-0030</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-003">MS11-003</a></td>
<td style="border:1px solid black;">未初始化的記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0035">CVE-2011-0035</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-003">MS11-003</a></td>
<td style="border:1px solid black;">未初始化的記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0036">CVE-2011-0036</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-014">MS11-014</a></td>
<td style="border:1px solid black;">LSASS 長度驗證資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0039">CVE-2011-0039</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-013">MS11-013</a></td>
<td style="border:1px solid black;">Kerberos 未加密總和檢查碼資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0043">CVE-2011-0043</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><strong>這項資訊安全風險已經公開揭露</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-011">MS11-011</a></td>
<td style="border:1px solid black;">Windows 核心整數截斷資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0045">CVE-2011-0045</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-012">MS11-012</a></td>
<td style="border:1px solid black;">Win32k 不當使用者輸入驗證資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0086">CVE-2011-0086</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-012">MS11-012</a></td>
<td style="border:1px solid black;">Win32k 使用者輸入驗證不足資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0087">CVE-2011-0087</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-012">MS11-012</a></td>
<td style="border:1px solid black;">Win32k 視窗類別指標混淆資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0088">CVE-2011-0088</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-012">MS11-012</a></td>
<td style="border:1px solid black;">Win32k 視窗類別不當指標驗證資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0089">CVE-2011-0089</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-012">MS11-012</a></td>
<td style="border:1px solid black;">Win32k 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0090">CVE-2011-0090</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-013">MS11-013</a></td>
<td style="border:1px solid black;">Kerberos 偽造資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0091">CVE-2011-0091</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-008">MS11-008</a></td>
<td style="border:1px solid black;">Visio 物件記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0092">CVE-2011-0092</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-008">MS11-008</a></td>
<td style="border:1px solid black;">Visio 資料類型記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0093">CVE-2011-0093</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-004">MS11-004</a></td>
<td style="border:1px solid black;">IIS FTP 服務堆積緩衝區溢位資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3972">CVE-2010-3972</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 可能撰寫出偶爾可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><strong>這項資訊安全風險目前已公開揭露，並可能已有 PoC 程式碼</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-007">MS11-007</a></td>
<td style="border:1px solid black;">OpenType 字型編碼字元資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0033">CVE-2011-0033</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 可能撰寫出偶爾可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-009">MS11-009</a></td>
<td style="border:1px solid black;">指令碼引擎資訊洩漏資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0031">CVE-2011-0031</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">這是一個資訊洩漏的資訊安全風險</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-005">MS11-005</a></td>
<td style="border:1px solid black;">Active Directory SPN 驗證資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0040">CVE-2011-0040</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><strong>這項資訊安全風險已經公開揭露。</strong><br />
<br />
這是一項拒絕服務的資訊安全風險</td>
</tr>
</tbody>
</table>
 

受影響的軟體及下載位置
----------------------

<span></span>
下表依據主要的軟體類別和嚴重性依序列出公告。

**我該如何使用這些表格？**

請用這些表格來瞭解可能需要安裝的 資訊安全更新有哪些。 您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的 資訊安全更新。 若軟體程式或更新出現在清單中，則相關可用軟體更新也會以超連結方式提供，也會列出軟體更新的嚴重性等級。

**注意：**一項資訊安全風險可能需要安裝數個 資訊安全更新才能妥善解決。 請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。

#### Windows 作業系統與元件

 
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
<th colspan="12">
Windows XP
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-003**](http://technet.microsoft.com/security/bulletin/ms11-003)
</td>
<td style="border:1px solid black;">
[**MS11-006**](http://technet.microsoft.com/security/bulletin/ms11-006)
</td>
<td style="border:1px solid black;">
[**MS11-007**](http://technet.microsoft.com/security/bulletin/ms11-007)
</td>
<td style="border:1px solid black;">
[**MS11-004**](http://technet.microsoft.com/security/bulletin/ms11-004)
</td>
<td style="border:1px solid black;">
[**MS11-005**](http://technet.microsoft.com/security/bulletin/ms11-005)
</td>
<td style="border:1px solid black;">
[**MS11-009**](http://technet.microsoft.com/security/bulletin/ms11-009)
</td>
<td style="border:1px solid black;">
[**MS11-010**](http://technet.microsoft.com/security/bulletin/ms11-010)
</td>
<td style="border:1px solid black;">
[**MS11-011**](http://technet.microsoft.com/security/bulletin/ms11-011)
</td>
<td style="border:1px solid black;">
[**MS11-012**](http://technet.microsoft.com/security/bulletin/ms11-012)
</td>
<td style="border:1px solid black;">
[**MS11-013**](http://technet.microsoft.com/security/bulletin/ms11-013)
</td>
<td style="border:1px solid black;">
[**MS11-014**](http://technet.microsoft.com/security/bulletin/ms11-014)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
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
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=ae343de6-ec61-4891-b136-cfc4234d97d9)  
(重大)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=85bf88b7-2dd9-4204-8492-b2c1d8d2264e)  
(重大)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c72fbb97-2313-45f6-842d-99db373822dd)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=bbea7ead-6c5c-4da8-aa03-a40325fd2de3)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=f86e9e64-801a-431a-b24e-772011dfa66d)  
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
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=cfa10178-9859-4e03-bedc-e3f5297a0251)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=a511d33a-9ae0-46ee-a225-9d97390de7d1)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=56f4f43e-c313-49dc-a278-e3e8a83a907e)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=486d1969-6814-4556-8dc0-5bfbaee528b0)  
(KB2478971)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=541f228f-79b3-402a-8ff9-366c1e595227)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=d431100d-a627-4ea0-b75b-2d4157e38df2)  
(重大)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=a795de21-13f4-4035-a4d5-4257ddc92fe7)  
(重大)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=69dfa24b-7c56-4521-850c-1485b062154a)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=bcb7217e-624a-4d61-86a1-f2440a1afd57)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=074396f0-a68c-4190-8dac-0b883d56e3f1)  
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
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9f0b7b77-5b90-4a4b-97a4-0c1ce6a70126)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e7273a85-ce96-464b-8c4f-2710701213e3)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e80db313-b470-4d71-bc34-70bfbfb6579f)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a210c796-7077-4617-a9a8-9ea99fe11a5e)  
(KB2478971)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=82189bf2-3f34-4949-92da-eea98036d18e)  
(重要)
</td>
</tr>
<tr>
<th colspan="12">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-003**](http://technet.microsoft.com/security/bulletin/ms11-003)
</td>
<td style="border:1px solid black;">
[**MS11-006**](http://technet.microsoft.com/security/bulletin/ms11-006)
</td>
<td style="border:1px solid black;">
[**MS11-007**](http://technet.microsoft.com/security/bulletin/ms11-007)
</td>
<td style="border:1px solid black;">
[**MS11-004**](http://technet.microsoft.com/security/bulletin/ms11-004)
</td>
<td style="border:1px solid black;">
[**MS11-005**](http://technet.microsoft.com/security/bulletin/ms11-005)
</td>
<td style="border:1px solid black;">
[**MS11-009**](http://technet.microsoft.com/security/bulletin/ms11-009)
</td>
<td style="border:1px solid black;">
[**MS11-010**](http://technet.microsoft.com/security/bulletin/ms11-010)
</td>
<td style="border:1px solid black;">
[**MS11-011**](http://technet.microsoft.com/security/bulletin/ms11-011)
</td>
<td style="border:1px solid black;">
[**MS11-012**](http://technet.microsoft.com/security/bulletin/ms11-012)
</td>
<td style="border:1px solid black;">
[**MS11-013**](http://technet.microsoft.com/security/bulletin/ms11-013)
</td>
<td style="border:1px solid black;">
[**MS11-014**](http://technet.microsoft.com/security/bulletin/ms11-014)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=5e0f4bf2-f727-483a-af3a-9a2abf0c36bb)  
(中度)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=45e504d4-c17d-4b73-b08e-d9c0cb3f4918)  
(中度)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=74238e08-fae2-4f17-ac72-681226a53a40)  
(中度)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2aa94528-5063-427b-97f7-2a0a55cbb6bf)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a99c2b13-db81-4f18-9cf7-c20614ba0132)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=651c1f4f-4e69-4d17-8aa2-72681dfc5463)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=aed08b96-24cc-4e23-8fd5-c7e52f8ef41a)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6bf2eeec-8225-477f-a606-263d3ee434d6)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=54fe2669-8a63-4d96-8b82-5b10f45b293e)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8a1e2675-0bf0-4d94-b48a-6e846dd6d9f5)  
(KB2478971)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4e31e6b1-577e-468e-9c94-67227d2273c2)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=0592b520-88d1-45bc-8b15-d3f0c8fa2181)  
(中度)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=29adcfb5-540f-4980-b2ca-9a22aa7bba13)  
(中度)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=ebef4869-9812-46ce-9c01-2fb8c866ec90)  
(中度)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6e740922-6ce4-46ec-a35e-e94201a9e398)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=aeed45fb-9395-4c2b-a674-e38b04fe0914)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=ec962b0e-e951-4e70-8d97-8c2afd360c28)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ca7879e1-e295-445d-a658-0a31be1928cc)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ec544894-ee98-4a2b-ac4d-33b0c3754213)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4632e1ce-6ae8-431c-9104-9a8840e5ac63)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e79bbbd4-8d5a-4c4c-8427-21c14400f041)  
(KB2478971)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=76e3c229-d812-433c-ad05-7cbd1f9c6a6d)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=b2298b32-238a-4970-bc1f-2ede51a6c361)  
(中度)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=c41a0094-204b-4d05-ab39-a32915201af1)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=a4f9ec46-35b2-44c9-abf6-647f7a474b99)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=bc09e42b-2eed-41b3-a03f-cb8cc94adfee)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=4ac66eae-e6d8-4e8b-b4ea-e7a77cc74db0)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=50855101-a15c-4c81-ad81-a7fe3f1d2026)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=fcd48499-1bb4-4304-b9cc-27d9d92e11cd)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=a09c3e6e-c55c-492a-b7ad-3e3d35711643)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=856fbcc2-ead9-4ec1-92dd-988e6d22dae9)  
(KB2478971)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=a0cde8d8-7c85-4fcb-bcf7-205064970b41)  
(重要)
</td>
</tr>
<tr>
<th colspan="12">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-003**](http://technet.microsoft.com/security/bulletin/ms11-003)
</td>
<td style="border:1px solid black;">
[**MS11-006**](http://technet.microsoft.com/security/bulletin/ms11-006)
</td>
<td style="border:1px solid black;">
[**MS11-007**](http://technet.microsoft.com/security/bulletin/ms11-007)
</td>
<td style="border:1px solid black;">
[**MS11-004**](http://technet.microsoft.com/security/bulletin/ms11-004)
</td>
<td style="border:1px solid black;">
[**MS11-005**](http://technet.microsoft.com/security/bulletin/ms11-005)
</td>
<td style="border:1px solid black;">
[**MS11-009**](http://technet.microsoft.com/security/bulletin/ms11-009)
</td>
<td style="border:1px solid black;">
[**MS11-010**](http://technet.microsoft.com/security/bulletin/ms11-010)
</td>
<td style="border:1px solid black;">
[**MS11-011**](http://technet.microsoft.com/security/bulletin/ms11-011)
</td>
<td style="border:1px solid black;">
[**MS11-012**](http://technet.microsoft.com/security/bulletin/ms11-012)
</td>
<td style="border:1px solid black;">
[**MS11-013**](http://technet.microsoft.com/security/bulletin/ms11-013)
</td>
<td style="border:1px solid black;">
[**MS11-014**](http://technet.microsoft.com/security/bulletin/ms11-014)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
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
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 1 和 Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=b176777e-4897-4cf1-9fc0-dd608930bb4c)  
(重大)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=77971c3c-55ec-4a9c-bcb8-8fb8c61431e3)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0c18ecca-afb9-4738-bc7b-76a0e815dfb8)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d60a2098-7351-4fce-83b2-2c1c3a24faa0)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.0 for IIS 7.0](https://www.microsoft.com/download/details.aspx?familyid=c09ccc72-8f94-416b-9a7f-ed16e90342a2)<sup>[1]</sup>
(重要)  
[Microsoft FTP Service 7.5 for IIS 7.0](https://www.microsoft.com/download/details.aspx?familyid=da9b7982-1c6b-45ac-8dd0-d7101bb83949)<sup>[1]</sup>
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
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=66978514-bb7f-42cc-9360-2fd1c686f4e6)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6fb7ebcc-2052-457b-b5bc-1bbcb17696b9)  
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
Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=20ad0136-c6df-4c7b-811f-d6b3dd9e2c56)  
(重大)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d3580784-aada-4118-b7f2-3a23aec2ed04)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=62dc454f-4b1e-4ac0-8ffe-6c73112f8d4d)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=065ad8fe-1caf-488e-a2e1-96db29f2fa57)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.0 for IIS 7.0](https://www.microsoft.com/download/details.aspx?familyid=e88d072f-0f5f-4c85-ad2f-91b9b8bf6b3a)<sup>[1]</sup>
(重要)  
[Microsoft FTP Service 7.5 for IIS 7.0](https://www.microsoft.com/download/details.aspx?familyid=6e4b9878-b5d2-4025-8839-b41515932cf2)<sup>[1]</sup>
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
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8fdb8c37-1b22-457b-bdc0-21f6a5061dd3)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=88d68757-1ab0-4585-9578-52a474b10882)  
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
<th colspan="12">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-003**](http://technet.microsoft.com/security/bulletin/ms11-003)
</td>
<td style="border:1px solid black;">
[**MS11-006**](http://technet.microsoft.com/security/bulletin/ms11-006)
</td>
<td style="border:1px solid black;">
[**MS11-007**](http://technet.microsoft.com/security/bulletin/ms11-007)
</td>
<td style="border:1px solid black;">
[**MS11-004**](http://technet.microsoft.com/security/bulletin/ms11-004)
</td>
<td style="border:1px solid black;">
[**MS11-005**](http://technet.microsoft.com/security/bulletin/ms11-005)
</td>
<td style="border:1px solid black;">
[**MS11-009**](http://technet.microsoft.com/security/bulletin/ms11-009)
</td>
<td style="border:1px solid black;">
[**MS11-010**](http://technet.microsoft.com/security/bulletin/ms11-010)
</td>
<td style="border:1px solid black;">
[**MS11-011**](http://technet.microsoft.com/security/bulletin/ms11-011)
</td>
<td style="border:1px solid black;">
[**MS11-012**](http://technet.microsoft.com/security/bulletin/ms11-012)
</td>
<td style="border:1px solid black;">
[**MS11-013**](http://technet.microsoft.com/security/bulletin/ms11-013)
</td>
<td style="border:1px solid black;">
[**MS11-014**](http://technet.microsoft.com/security/bulletin/ms11-014)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
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
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=ee61f0dd-9797-4e11-8281-a05b201d0c0b)\*\*  
(中度)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=ef1ae382-8835-4f60-83bd-e84a3400d55c)\*\*  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=253c47a0-69ac-437a-ad3e-778c37fa37cb)\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=88ba83b9-c14e-499a-8335-04bac1c49c0c)\*  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.0 for IIS 7.0](https://www.microsoft.com/download/details.aspx?familyid=3cc55af7-5cd9-4923-8ec5-462ff201d734)<sup>[1]</sup>\*  
(重要)  
[Microsoft FTP Service 7.5 for IIS 7.0](https://www.microsoft.com/download/details.aspx?familyid=4dfa0a25-b7e3-4fb6-a351-58ec3f8a8435)<sup>[1]</sup>\*  
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
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4b37418a-e044-415e-b566-4507f157934a)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=80494972-db45-475f-97cd-dac46b9486a1)\*  
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
適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=558bc86a-a49d-4d6c-b5e4-f12956f6b61b)\*\*  
(中度)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=5607df02-93fa-45fe-a928-e5f6329851f3)\*\*  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ec7101aa-96c2-4931-a3e4-0c55cbc74d9c)\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7c74d7f4-6372-4809-89b8-c79b05e54cdd)\*  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.0 for IIS 7.0](https://www.microsoft.com/download/details.aspx?familyid=f485b30d-dcaf-47c3-ac62-982b14670a1f)<sup>[1]</sup>\*  
(重要)  
[Microsoft FTP Service 7.5 for IIS 7.0](https://www.microsoft.com/download/details.aspx?familyid=a98a74c1-0c91-446d-b822-fe57ff06d90b)<sup>[1]</sup>\*  
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
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=163d3aca-3703-452e-b1cb-73932e2bcf8c)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5597d449-17e3-440f-8b0e-56a902a96569)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=8c2abba5-0597-4565-9b87-a37e574690e0)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e62493cb-8d25-4975-bbe6-a368e039872b)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=91d5d34b-9d7e-4e83-89a4-f1aa388dc4e4)  
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
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=55b07bc0-dff5-4cd7-87c9-c08e5a49197d)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d10eda21-b3c3-4d8e-8596-bc45e4165f93)  
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
<th colspan="12">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-003**](http://technet.microsoft.com/security/bulletin/ms11-003)
</td>
<td style="border:1px solid black;">
[**MS11-006**](http://technet.microsoft.com/security/bulletin/ms11-006)
</td>
<td style="border:1px solid black;">
[**MS11-007**](http://technet.microsoft.com/security/bulletin/ms11-007)
</td>
<td style="border:1px solid black;">
[**MS11-004**](http://technet.microsoft.com/security/bulletin/ms11-004)
</td>
<td style="border:1px solid black;">
[**MS11-005**](http://technet.microsoft.com/security/bulletin/ms11-005)
</td>
<td style="border:1px solid black;">
[**MS11-009**](http://technet.microsoft.com/security/bulletin/ms11-009)
</td>
<td style="border:1px solid black;">
[**MS11-010**](http://technet.microsoft.com/security/bulletin/ms11-010)
</td>
<td style="border:1px solid black;">
[**MS11-011**](http://technet.microsoft.com/security/bulletin/ms11-011)
</td>
<td style="border:1px solid black;">
[**MS11-012**](http://technet.microsoft.com/security/bulletin/ms11-012)
</td>
<td style="border:1px solid black;">
[**MS11-013**](http://technet.microsoft.com/security/bulletin/ms11-013)
</td>
<td style="border:1px solid black;">
[**MS11-014**](http://technet.microsoft.com/security/bulletin/ms11-014)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=07aa7ffc-47c7-4611-b32c-ecb3fbcad32f)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=1da57fbc-9ea4-4fc4-911d-d5c7825e012c)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.5 for IIS 7.5](https://www.microsoft.com/download/details.aspx?familyid=9dabd1d1-3f1e-46d1-b171-aafd3f08d291)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[JScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=54a64215-e407-4b7b-8536-28817ef23bac)  
(重要)  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=54a64215-e407-4b7b-8536-28817ef23bac)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=e1224c90-b0bc-4e4b-999a-efae327213b4)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=078fe6c0-1b2c-4896-a345-25cc1b1105e2)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=ffed7c76-0b75-4f57-9b63-3961a8b449f6)  
(KB2425227)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=2b8ffafe-78bb-4fa7-aea2-01208b6a3dfe)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=587adb89-2f6a-4893-9906-b6d6d9ada2bd)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.5 for IIS 7.5](https://www.microsoft.com/download/details.aspx?familyid=66fb4efe-bcd3-4e90-8e35-b013e014a952)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[JScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=b854d76e-6891-426d-8c09-0ed8243a3b8d)  
(重要)  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=b854d76e-6891-426d-8c09-0ed8243a3b8d)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=ddcf352e-742c-485e-9ed5-19cdba673562)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=b42642b3-fb78-4700-bfe8-bfa997b90c16)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=c26cebcf-683f-4a51-be75-76535fb979a7)  
(KB2425227)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="12">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-003**](http://technet.microsoft.com/security/bulletin/ms11-003)
</td>
<td style="border:1px solid black;">
[**MS11-006**](http://technet.microsoft.com/security/bulletin/ms11-006)
</td>
<td style="border:1px solid black;">
[**MS11-007**](http://technet.microsoft.com/security/bulletin/ms11-007)
</td>
<td style="border:1px solid black;">
[**MS11-004**](http://technet.microsoft.com/security/bulletin/ms11-004)
</td>
<td style="border:1px solid black;">
[**MS11-005**](http://technet.microsoft.com/security/bulletin/ms11-005)
</td>
<td style="border:1px solid black;">
[**MS11-009**](http://technet.microsoft.com/security/bulletin/ms11-009)
</td>
<td style="border:1px solid black;">
[**MS11-010**](http://technet.microsoft.com/security/bulletin/ms11-010)
</td>
<td style="border:1px solid black;">
[**MS11-011**](http://technet.microsoft.com/security/bulletin/ms11-011)
</td>
<td style="border:1px solid black;">
[**MS11-012**](http://technet.microsoft.com/security/bulletin/ms11-012)
</td>
<td style="border:1px solid black;">
[**MS11-013**](http://technet.microsoft.com/security/bulletin/ms11-013)
</td>
<td style="border:1px solid black;">
[**MS11-014**](http://technet.microsoft.com/security/bulletin/ms11-014)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=38b67efb-dd4b-4e8c-8460-0f40f0367441)\*\*  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?familyid=638318ed-4000-4b1a-bb4b-65b795f59784)\*  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.5 for IIS 7.5](https://www.microsoft.com/download/details.aspx?familyid=1e075f57-1723-4933-9b8e-7bce4a44a1c1)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[JScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=f482bd40-f0b9-4534-a768-45879f1e7285)\*\*  
(中度)  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=f482bd40-f0b9-4534-a768-45879f1e7285)\*\*  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?familyid=70f5056a-72ad-46ff-a43f-ee151639b9a7)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?familyid=d2c53f44-12eb-4293-9fa5-2a14075b636e)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?familyid=46bb3ef1-24c3-41cb-8141-0fdbd85093f7)\*  
(KB2425227)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=0e41cbe5-5e5e-4ece-a71a-71f4b6319f0d)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?familyid=4688ea0d-a467-4f24-ac52-104d05c8cae8)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.5 for IIS 7.5](https://www.microsoft.com/download/details.aspx?familyid=bfddd539-c64f-4467-88ee-6bdfe645b478)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[JScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=f05a3de0-381c-4d17-83ee-ca4f6da1bdb0)  
(中度)  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=f05a3de0-381c-4d17-83ee-ca4f6da1bdb0)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?familyid=1646b3a5-714f-4ea5-b109-566fa9b933b6)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?familyid=8c6bf720-f544-4f58-9b1c-2399957ec43d)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?familyid=01737933-e7de-451b-b02f-b7ca24693965)  
(KB2425227)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
</table>
 
**Windows Server 2008 和 Windows Server 2008 R2 注意事項**

**\*Server Core 安裝會受影響。** 無論上述受支援的 Windows Server 2008 或 Windows Server 2008 R2 版本是否使用 Server Core 安裝選項安裝，這個更新均以相同的嚴重性等級套用。 如需此安裝選項的詳細資訊，請參閱 TechNet 文章：[管理 Server Core 安裝](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[維護 Server Core 安裝](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 和 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**\*\*Server Core 安裝不受影響。** 如果 Windows Server 2008 或 Windows Server 2008 R2 是使用 Server Core 安裝選項所安裝，則這項更新解決的資訊安全風險並不會影響受支援的 Windows Server 2008 或 Windows Server 2008 R2。 如需此安裝選項的詳細資訊，請參閱 TechNet 文章：[管理 Server Core 安裝](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[維護 Server Core 安裝](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 和 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**MS11-004 注意事項**

<sup>[1]</sup>不是此作業系統的預設 FTP 服務

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
Microsoft Office 程式
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-008**](http://technet.microsoft.com/security/bulletin/ms11-008)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2002 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2002 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=273d8078-0dc7-43d8-bcae-54c811e49e0e)  
(KB2434711)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=f1067eaa-d18d-4bff-a02e-1d990c36ca7f)  
(KB2434733)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=097a642b-b786-4724-a907-79f37cded836)  
(KB2434737)  
(重要)
</td>
</tr>
</table>
 

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和 資訊安全更新。 如需更多資訊，請參閱 [TechNet 更新管理中心](http://technet.microsoft.com/zh-tw/updatemanagement/default.aspx) (英文)。 [TechNet Security Center](http://technet.microsoft.com/zh-tw/security/default.aspx) 提供 Microsoft 產品安全性的其他資訊。 消費者可以造訪[在家上網的安全性](http://www.microsoft.com/taiwan/protect/default.mspx)網站，只要按一下 \[最新 資訊安全更新\] 即可在此網站取得此資訊。

資訊安全更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 以及 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) 取得。 資訊安全更新也可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得。 您也可以利用「 資訊安全更新」("security update") 關鍵字搜尋輕易地找到 資訊安全更新。

對於 Microsoft Office for Mac 的客戶，Microsoft AutoUpdate for Mac 可協助您保持最新的 Microsoft 軟體。 如需使用 Microsoft AutoUpdate for Mac 的詳細資訊，請參閱[自動檢查軟體更新](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea) (英文)。

最後，您可以從 [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) 下載 資訊安全更新。 Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括 資訊安全更新、驅動程式和 Service Pack。 只要以 資訊安全公告編號 (例如：MS07-036) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。 如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](http://go.microsoft.com/fwlink/?linkid=97900)。

**偵測與部署指南**

Microsoft 針對 資訊安全更新提供偵測和部署指南。 本指南所含之建議和資訊，能幫助 IT 專業人員瞭解如何使用用於 資訊安全更新的偵測和部署的各種工具。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 961747](http://support.microsoft.com/kb/961747/zh-tw)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少 資訊安全更新以及一般 資訊安全設定錯誤的狀況。 如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) 網站 (英文)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速而可靠地將 Microsoft Windows 2000 作業系統及更新版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 適用的最新重大更新與 資訊安全更新部署到 Microsoft Windows 2000 及更新版本的作業系統中。

如需更多關於利用 Windows Server Update Services 部署 資訊安全更新的資訊，請造訪 [Windows Server Update Services](http://www.microsoft.com/taiwan/windowsserversystem/updateservices/evaluation/overview.mspx) 網站。

**System Center Configuration Manager 2007**

Configuration Manager 2007 軟體更新管理可簡化遞送和管理企業中 IT 系統更新的繁複作業。 IT 系統管理員可以使用 Configuration Manager 2007 遞送 Microsoft 產品更新給各種裝置，包括桌上型電腦、筆記型電腦、伺服器及行動裝置。

Configuration Manager 2007 中的自動資訊安全風險評估會找出更新需求並報告建議動作。 Configuration Manager 2007 中的軟體更新管理是建置在 Microsoft Windows Software Update Services (WSUS) 上，經過時間考驗，為全球 IT 系統管理員所熟悉的更新基礎架構。 如需更多有關系統管理員如何使用 Configuration Manager 2007 來部署更新的資訊，請參閱[軟體更新管理](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx) (英文)。 如需更多有關 Configuration Manager 的資訊，請造訪 [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx)。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要 資訊安全更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。

**注意：System Management Server 2003 自 2010 年 1 月 12 日起不受主流支援。**如需更多有關產品生命週期的資訊，請造訪 [Microsoft 產品技術支援週期](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle)。 現已推出新版的 SMS，System Center Configuration Manager 2007；請參閱前段的＜System Center Configuration Manager 2007＞一節。

如需更多有關系統管理員如何使用 SMS 2003 來部署 資訊安全更新的資訊，請參閱 [Microsoft Systems Management Server 2003 的案例與程序： 軟體發佈和補充程式管理](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en) (英文)。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx)。

**注意：**SMS 使用 Microsoft Baseline Security Analyzer 提供廣泛的 資訊安全公告更新偵測與部署支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些 資訊安全更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可使用 Elevated Rights Deployment Tool (隨 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en) (英文) 提供) 來安裝這些更新。

**Update Compatibility Evaluator 和 Application Compatibility Toolkit**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。 這可能會觸發不相容性，而拉長部署 資訊安全更新的時間。 您可以使用 [Application Compatibility Toolkit](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 隨附的 [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 元件，針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Microsoft Windows Vista、Windows Update、Microsoft 資訊安全更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非 資訊安全更新

如需在 Windows Update 和 Microsoft Update 上發行的非 資訊安全更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](http://support.microsoft.com/kb/894199/zh-tw)： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。 其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](http://technet.microsoft.com/en-us/wsus/bb456965.aspx)。 顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的安全性保護，Microsoft 將在每月發行 資訊安全更新之前，提前向重要 資訊安全軟體提供者提供資訊安全風險資訊。 資訊安全軟體提供者可利用此資訊安全風險資訊，透過其 資訊安全軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。 如果要判斷是否有 資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://www.microsoft.com/security/msrc/mapp/partners.mspx)上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 安全性策略與社群

**更新程式管理策略**

[更新程式管理安全性指南](http://technet.microsoft.com/zh-tw/library/bb466251(en-us).aspx)提供您有關套用 資訊安全更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他 資訊安全更新**

其他安全性問題的更新可由下列位置取得：

-   資訊安全更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「 資訊安全更新」("security update") 關鍵字搜尋輕易地找到 資訊安全更新。
-   客戶平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的 資訊安全更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](http://support.microsoft.com/kb/913086/zh-tw)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](http://technet.microsoft.com/zh-tw/security/cc136632.aspx)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](http://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 [Trend Micro](http://www.trendmicro.com) 的 Yuki Chen 回報 MS11-003 中描述的一項問題
-   感謝 [Google Inc.](http://www.google.com/) 的 SkyLined 回報 MS11-003 中描述的一項問題
-   感謝 [ACROS Security](http://www.acrossecurity.com/) 的 Mitja Kolsek 回報 MS11-003 中描述的一項問題
-   感謝 Kobi Pariente 和 Yaniv Miron，與 [VeriSign iDefense Labs](http://labs.idefense.com/) 攜手合作，回報 MS11-006 中描述的一項問題
-   感謝 Procyun 與 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 MS11-008 中描述的一項問題
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Xin Ouyang 回報 MS11-008 中描述的兩項問題
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Yamata Li 回報 MS11-009 中描述的問題
-   感謝[北京大學資訊安全系](http://www.ss.pku.edu.cn/en/)的 Sihan Qing (教授)、Weiping Wen (副教授)、Liang Yi 和 Husheng Zhou (研究生) 回報 MS11-010 中描述的一項問題
-   感謝 [360safe](http://www.360.cn) 的 Zhengwenbin 回報 MS11-011 中描述的一項問題
-   感謝 Guo Bojun 回報 MS11-011 中描述的一項問題
-   感謝 Wei Zhang 回報 MS11-011 中描述的一項問題
-   感謝 [Prevx](http://www.prevx.com/) 的 Marco Giuliani 協助我們解決 MS11-011 中描述的一項問題
-   感謝 std\_logic 與 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 MS11-011 中描述的一項問題
-   感謝 [Norman](http://www.norman.com) 的 Tarjei Mandt 回報 MS11-012 中描述的一項問題
-   感謝 [MIT Security Team](http://web.mit.edu/kerberos) 回報 MS11-013 中描述的一項問題
-   感謝 [iSEC Partners](http://www.isecpartners.com/) 的 Scott Stender 回報 MS11-013 中描述的一項問題
-   感謝 Primavera BSS 的安全測試員 Jorge Moura 回報 MS11-014 中描述的一項問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可洽詢[資訊安全支援](http://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 以取得技術支援。 與 資訊安全更新有關的支援電話不另外收費。 如需更多可用支援選項的資訊，請參閱 [Microsoft 技術支援服務](http://support.microsoft.com/?ln=zh-tw)。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與 資訊安全更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](http://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2011 年 2 月 9 日)： 公告摘要發行。

*Built at 2014-04-18T01:50:00Z-07:00*
