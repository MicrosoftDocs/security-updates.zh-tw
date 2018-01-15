---
TOCTitle: 'MS16-FEB'
Title: 2016 年 2 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms16-feb'
ms:contentKeyID: 72239080
ms:date: '03/14/2016'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms16-feb(v=Security.10)'
---

2016 年 2 月份 Microsoft 資訊安全公告摘要
=========================================

發行日期：2016 年 2 月 9 日 | 更新日期：2016 年 2 月 24 日

**版本：** 3.1

此公告摘要列出 2016 年 2 月份發行之資訊安全公告。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://technet.microsoft.com/zh-tw/security/dd252948.aspx)。

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-009">MS16-009</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 累積安全性更新 (3134220)</strong> <br />
此安全性更新可解決 Internet Explorer 中的弱點。其中最嚴重的弱點，可能在使用者以 Internet Explorer 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用此弱點的攻擊者可以取得與目前使用者相同的使用者權限。如果目前的使用者以系統管理使用者權限登入，則成功利用此弱點的攻擊者可以取得受影響系統的控制權。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3134814">3134814</a></td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-011">MS16-011</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 的累積安全性更新 (3134225)<br />
</strong>此安全性更新可解決 Microsoft Edge 中的弱點。其中最嚴重的弱點，可能在使用者以 Microsoft Edge 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用這些弱點的攻擊者可以取得與本機使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-012">MS16-012</a></td>
<td style="border:1px solid black;"><strong>用來解決遠端執行程式碼的 Microsoft Windows PDF 程式庫安全性更新 (3138938)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果 Microsoft Windows PDF 程式庫不當處理應用程式開發介面 (API) 呼叫，其中較嚴重的弱點可能會允許遠端執行程式碼，並可允許攻擊者在使用者的系統上執行任意程式碼。成功利用這些弱點的攻擊者可以取得與本機使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。但是，攻擊者無法強迫使用者下載或開啟惡意的 PDF 文件。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-013">MS16-013</a></td>
<td style="border:1px solid black;"><strong>用來解決遠端執行程式碼的 Windows 筆記本安全性更新 (3134811)</strong><br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果使用者開啟蓄意製作的筆記本檔案，此弱點可能會允許遠端執行程式碼。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-014">MS16-014</a></td>
<td style="border:1px solid black;"><strong>用來解決遠端執行程式碼的 Microsoft Windows 安全性更新 (3134228)</strong><br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者可以登入目標系統並執行蓄意製作的應用程式，則最嚴重的弱點可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3126041">3126041</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3126587">3126587</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3126593">3126593</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-015">MS16-015</a></td>
<td style="border:1px solid black;"><strong>用來解決遠端執行程式碼的 Microsoft Office 安全性更新 (3134226)</strong><br />
此安全性更新可解決 Microsoft Office 中的弱點。如果使用者開啟蓄意製作的 Microsoft Office 檔案，最嚴重的弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者，能以目前使用者的權限層級執行任意程式碼。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft Office Services 和 Web Apps、<br />
Microsoft 伺服器軟體</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-016">MS16-016</a></td>
<td style="border:1px solid black;"><strong>用來解決權限提高的 WebDAV 安全性更新 (3136041)</strong><br />
此安全性更新可解決 Microsoft Windows 中的弱點。該弱點會在攻擊者使用 Microsoft 網頁分工編寫及版本管理 (WebDAV) 用戶端傳送蓄意製作的輸入至伺服器時，允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-017">MS16-017</a></td>
<td style="border:1px solid black;"><strong>用來解決權限提高的遠端桌面顯示驅動程式安全性更新 (3134700)</strong><br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果通過驗證的攻擊者使用 RDP 登入目標系統並透過連線傳送蓄意製作的資料，此弱點就可能會允許權限提高。依照預設，RDP 並未在任何 Windows 作業系統上啟用。未啟用 RDP 的系統都沒有受到弱點影響的風險。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3134700">3134700</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3126446">3126446</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-018">MS16-018</a></td>
<td style="border:1px solid black;"><strong>用來解決權限提高的 Windows 核心模式驅動程式安全性更新 (3136082)</strong><br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者登入受影響的系統，並執行蓄意製作的應用程式，則此弱點可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-019">MS16-019</a></td>
<td style="border:1px solid black;"><strong>解決阻斷服務的 .NET Framework 安全性更新 (3137893)<br />
</strong>這個安全性更新可解決 Microsoft .NET Framework 中的弱點。如果攻擊者將蓄意製作的 XSLT 插入用戶端的 XML 網頁組件，造成伺服器以遞迴方式編譯 XSLT 轉換時，其中較嚴重的弱點會造成阻斷服務。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
阻斷服務 (DoS)</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-020">MS16-020</a></td>
<td style="border:1px solid black;"><strong>解決阻斷服務的 Active Directory 同盟服務安全性更新 (3134222)<br />
</strong>這個安全性更新可解決 Active Directory 同盟服務 (ADFS) 中的弱點。如果攻擊者在表單型驗證期間傳送特定的輸入資料至 ADFS 伺服器，造成伺服器沒有回應，則此弱點會允許阻斷服務。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
阻斷服務 (DoS)</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-021">MS16-021</a></td>
<td style="border:1px solid black;"><strong>解決阻斷服務的 NPS RADIUS 伺服器安全性更新 (3133043)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。此弱點會在攻擊者傳送蓄意製作的使用者名稱字串值至網路原則伺服器 (NPS)，進而阻止 NPS 上的 RADIUS 驗證時，造成 NPS 上的阻斷服務。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a> <br />
阻斷服務 (DoS)</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms16-022">MS16-022</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player 的安全性更新 (3135782)<br />
</strong>此安全性更新可解決安裝於 Windows Server 2012、Windows 8.1、Windows Server 2012 R2、Windows RT 8.1 和 Windows 10 上之 Adobe Flash Player 中的弱點。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows<br />
Adobe Flash Player</td>
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
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-009：Internet Explorer 累積安全性更新 (3134220)**](https://technet.microsoft.com/zh-tw/library/security/ms16-009)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0041](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0041)

</td>
<td style="border:1px solid black;">
DLL 載入遠端執行程式碼弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0059](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0059)

</td>
<td style="border:1px solid black;">
Internet Explorer 資訊洩漏弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0060](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0060)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0061](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0061)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0062](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0062)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0063](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0063)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0064](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0064)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0067](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0067)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0068](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0068)

</td>
<td style="border:1px solid black;">
Internet Explorer 權限提高弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0069](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0069)

</td>
<td style="border:1px solid black;">
Internet Explorer 權限提高弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0071](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0071)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0072](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0072)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0077](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0077)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器詐騙弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-011：Microsoft Edge 的累積安全性更新 (3134225)**](https://technet.microsoft.com/zh-tw/library/security/ms16-011)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0060](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0060)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0061](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0061)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0062](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0062)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0077](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0077)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器詐騙弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0080](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0080)

</td>
<td style="border:1px solid black;">
Microsoft Edge ASLR 略過

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0084](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0084)

</td>
<td style="border:1px solid black;">
Microsoft Edge 記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-012：用來解決遠端執行程式碼的 Microsoft Windows PDF 程式庫安全性更新 (3138938)**](https://technet.microsoft.com/zh-tw/library/security/ms16-012)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0046](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0046)

</td>
<td style="border:1px solid black;">
Microsoft Windows 閱讀程式弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0058](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0058)

</td>
<td style="border:1px solid black;">
Microsoft PDF 程式庫緩衝區溢位弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-013：用來解決遠端執行程式碼的 Windows 筆記本安全性更新 (3134811)**](https://technet.microsoft.com/zh-tw/library/security/ms16-013)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0038](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0038)

</td>
<td style="border:1px solid black;">
Windows 筆記本記憶體損毀弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-014：用來解決遠端執行程式碼的 Microsoft Windows 安全性更新 (3134228)**](https://technet.microsoft.com/zh-tw/library/security/ms16-014)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0040](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0040)

</td>
<td style="border:1px solid black;">
Windows 權限提高弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0041](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0041)

</td>
<td style="border:1px solid black;">
DLL 載入遠端執行程式碼弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0042](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0042)

</td>
<td style="border:1px solid black;">
Windows DLL 載入遠端執行程式碼弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0044](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0044)

</td>
<td style="border:1px solid black;">
Windows DLL 載入阻斷服務弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0049](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0049)

</td>
<td style="border:1px solid black;">
Windows Kerberos 資訊安全功能略過

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-015：用來解決遠端執行程式碼的 Microsoft Office 安全性更新 (3134226)**](https://technet.microsoft.com/zh-tw/library/security/ms16-015)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0022](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0022)

</td>
<td style="border:1px solid black;">
Microsoft Office 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0039](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0039)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint XSS 弱點

</td>
<td style="border:1px solid black;">
3 - 不太可能遭到利用

</td>
<td style="border:1px solid black;" colspan="2">
4 - 不受影響

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0052](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0052)

</td>
<td style="border:1px solid black;">
Microsoft Office 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0053](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0053)

</td>
<td style="border:1px solid black;">
Microsoft Office 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0054](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0054)

</td>
<td style="border:1px solid black;">
Microsoft Office 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0055](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0055)

</td>
<td style="border:1px solid black;">
Microsoft Office 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
4 - 不受影響

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0056](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0056)

</td>
<td style="border:1px solid black;">
Microsoft Office 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;" colspan="2">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-016：用來解決權限提高的 WebDAV 安全性更新 (3136041)**](https://technet.microsoft.com/zh-tw/library/security/ms16-016)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0051](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0051)

</td>
<td style="border:1px solid black;">
WebDAV 權限提高弱點

</td>
<td style="border:1px solid black;" colspan="2">
3 - 不太可能遭到利用

</td>
<td style="border:1px solid black;">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-017：用來解決權限提高的遠端桌面顯示驅動程式安全性更新 (3134700)**](https://technet.microsoft.com/zh-tw/library/security/ms16-017)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0036](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0036)

</td>
<td style="border:1px solid black;">
遠端桌面通訊協定 (RDP) 權限提高弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-018：用來解決權限提高的 Windows 核心模式驅動程式安全性更新 (3136082)**](https://technet.microsoft.com/zh-tw/library/security/ms16-018)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0048](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0048)

</td>
<td style="border:1px solid black;">
Win32k 權限提高弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-019：解決阻斷服務的 .NET Framework 安全性更新 (3137893)**](https://technet.microsoft.com/zh-tw/library/security/ms16-019)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0033](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0033)

</td>
<td style="border:1px solid black;">
.NET Framework 堆疊溢位阻斷服務弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;">
[CVE-2016-0047](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0047)

</td>
<td style="border:1px solid black;">
Windows Forms 資訊洩露弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-020：解決阻斷服務的 Active Directory 同盟服務安全性更新 (3134222)**](https://technet.microsoft.com/zh-tw/library/security/ms16-020)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0037](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0037)

</td>
<td style="border:1px solid black;">
Microsoft Active Directory 同盟服務阻斷服務弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-021：解決阻斷服務的 NPS RADIUS 伺服器安全性更新 (3133043)**](https://technet.microsoft.com/zh-tw/library/security/ms16-021)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0050](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0050)

</td>
<td style="border:1px solid black;">
網路原則伺服器 RADIUS 實作阻斷服務弱點

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-022：Adobe Flash Player 的安全性更新 (3135782)**](https://technet.microsoft.com/zh-tw/library/security/ms16-022)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-04](https://helpx.adobe.com/tw/security/products/flash-player/apsb16-04.html)

</td>
<td style="border:1px solid black;">
請參閱 [Adobe 資訊安全公告 APSB16-04](https://helpx.adobe.com/tw/security/products/flash-player/apsb16-04.html) 以了解弱點嚴重性和更新的優先順序級別。

</td>
<td style="border:1px solid black;" colspan="2">
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

**注意**：一項弱點，可能需要安裝數個安全性更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。

 

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
[**MS16-009**](https://technet.microsoft.com/zh-tw/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/zh-tw/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/zh-tw/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/zh-tw/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/zh-tw/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/zh-tw/library/security/ms16-016)

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
(3134814)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3115858)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3126587)  
(重要)  
Windows Vista Service Pack 2  
(3126593)  
(重要)  
Windows Vista Service Pack 2  
(3126041)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3124280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3134814)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3115858)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3126587)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3126593)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3126041)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3124280)  
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
[**MS16-009**](https://technet.microsoft.com/zh-tw/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/zh-tw/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/zh-tw/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/zh-tw/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/zh-tw/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/zh-tw/library/security/ms16-016)

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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3134814)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3115858)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3126587)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3126593)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3126041)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3124280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3134814)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3115858)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3126587)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3126593)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3126041)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3124280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3134814)  
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
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3126587)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3126593)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3126041)  
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
[**MS16-009**](https://technet.microsoft.com/zh-tw/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/zh-tw/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/zh-tw/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/zh-tw/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/zh-tw/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/zh-tw/library/security/ms16-016)

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
(3134814)  
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
(3115858)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3126587)  
(重要)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3126593)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3124280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows 7 Service Pack 1  
(3115858)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows 7 Service Pack 1  
(3126587)  
(重要)  
適用於 x64 系統的 Windows 7 Service Pack 1  
(3126593)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows 7 Service Pack 1  
(3124280)  
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
[**MS16-009**](https://technet.microsoft.com/zh-tw/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/zh-tw/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/zh-tw/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/zh-tw/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/zh-tw/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/zh-tw/library/security/ms16-016)

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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(3115858)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(3126587)  
(重要)  
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(3126593)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(3124280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
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
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3126587)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3126593)  
(重要)

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
[**MS16-009**](https://technet.microsoft.com/zh-tw/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/zh-tw/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/zh-tw/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/zh-tw/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/zh-tw/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/zh-tw/library/security/ms16-016)

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
[**中度**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3123294)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3115858)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3126587)  
(重要)  
適用於 32 位元系統的 Windows 8.1  
(3126593)  
(重要)  
適用於 32 位元系統的 Windows 8.1  
(3126041)  
(重要)  
適用於 32 位元系統的 Windows 8.1  
(3126434)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3124280)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3123294)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3115858)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3126587)  
(重要)  
適用於 x64 型系統的 Windows 8.1  
(3126593)  
(重要)  
適用於 x64 型系統的 Windows 8.1  
(3126041)  
(重要)  
適用於 x64 型系統的 Windows 8.1  
(3126434)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3124280)  
(中度)

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
[**MS16-009**](https://technet.microsoft.com/zh-tw/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/zh-tw/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/zh-tw/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/zh-tw/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/zh-tw/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/zh-tw/library/security/ms16-016)

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
[**中度**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3134814)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3123294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3115858)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3126587)  
(重要)  
Windows Server 2012  
(3126593)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3124280)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3123294)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3115858)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3126587)  
(重要)  
Windows Server 2012 R2  
(3126593)  
(重要)  
Windows Server 2012 R2  
(3126041)  
(重要)  
Windows Server 2012 R2  
(3126434)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3124280)  
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
[**MS16-009**](https://technet.microsoft.com/zh-tw/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/zh-tw/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/zh-tw/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/zh-tw/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/zh-tw/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/zh-tw/library/security/ms16-016)

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
[**中度**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
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
(3126587)  
(重要)  
Windows RT 8.1  
(3126593)  
(重要)  
Windows RT 8.1  
(3126434)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3124280)  
(中度)

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
[**MS16-009**](https://technet.microsoft.com/zh-tw/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/zh-tw/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/zh-tw/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/zh-tw/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/zh-tw/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/zh-tw/library/security/ms16-016)

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
[**中度**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3135174)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3135174)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3135174)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3135174)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3135174)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3135174)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3135174)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3135174)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3135174)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3135174)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3135174)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3135174)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3135173)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3135173)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3135173)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3135173)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3135173)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3135173)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3135173)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3135173)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3135173)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3135173)  
(中度)

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
[**MS16-009**](https://technet.microsoft.com/zh-tw/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/zh-tw/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/zh-tw/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/zh-tw/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/zh-tw/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/zh-tw/library/security/ms16-016)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3126587)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3126593)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3126041)  
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
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3126587)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3126593)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3126041)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
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
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3126587)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3126593)  
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
Windows Server 2012 (Server Core 安裝)  
(3126587)  
(重要)  
Windows Server 2012 (Server Core 安裝)  
(3126593)  
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
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)  
(3123294)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3126587)  
(重要)  
Windows Server 2012 R2 (Server Core 安裝)  
(3126593)  
(重要)  
Windows Server 2012 R2 (Server Core 安裝)  
(3126041)  
(重要)

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
<td style="border:1px solid black;" colspan="7">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-017**](https://technet.microsoft.com/zh-tw/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/zh-tw/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/zh-tw/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/zh-tw/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/zh-tw/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/zh-tw/library/security/ms16-022)

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
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3122646)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(3127219)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(重要)  
Microsoft .NET Framework 4.6  
(3122661)  
(重要)  
Microsoft .NET Framework 4.6  
(3127233)  
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
Windows Vista x64 Edition Service Pack 2  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3122646)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(3127219)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(重要)  
Microsoft .NET Framework 4.6  
(3122661)  
(重要)  
Microsoft .NET Framework 4.6  
(3127233)  
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
[**MS16-017**](https://technet.microsoft.com/zh-tw/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/zh-tw/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/zh-tw/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/zh-tw/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/zh-tw/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/zh-tw/library/security/ms16-022)

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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3122646)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(3127219)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(重要)  
Microsoft .NET Framework 4.6  
(3122661)  
(重要)  
Microsoft .NET Framework 4.6  
(3127233)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3133043)  
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
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3122646)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(3127219)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(重要)  
Microsoft .NET Framework 4.6  
(3122661)  
(重要)  
Microsoft .NET Framework 4.6  
(3127233)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3133043)  
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
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3122646)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(3127219)  
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
[**MS16-017**](https://technet.microsoft.com/zh-tw/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/zh-tw/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/zh-tw/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/zh-tw/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/zh-tw/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/zh-tw/library/security/ms16-022)

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
(3126446)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3122648)  
(重要)  
Microsoft .NET Framework 3.5.1  
(3127220)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3122661)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3127233)  
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
適用於 x64 系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows 7 Service Pack 1  
(3126446)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows 7 Service Pack 1  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3122648)  
(重要)  
Microsoft .NET Framework 3.5.1  
(3127220)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3122661)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3127233)  
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
[**MS16-017**](https://technet.microsoft.com/zh-tw/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/zh-tw/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/zh-tw/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/zh-tw/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/zh-tw/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/zh-tw/library/security/ms16-022)

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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3122648)  
(重要)  
Microsoft .NET Framework 3.5.1  
(3127220)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3122661)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3127233)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(3133043)  
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
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3122648)  
(重要)  
Microsoft .NET Framework 3.5.1  
(3127220)  
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
[**MS16-017**](https://technet.microsoft.com/zh-tw/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/zh-tw/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/zh-tw/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/zh-tw/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/zh-tw/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/zh-tw/library/security/ms16-022)

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
**無**

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
適用於 32 位元系統的 Windows 8.1  
(3126446)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3122651)  
(重要)  
Microsoft .NET Framework 3.5  
(3127222)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122654)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127226)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3122660)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3127231)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3126446)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3122651)  
(重要)  
Microsoft .NET Framework 3.5  
(3127222)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122654)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127226)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3122660)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3127231)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
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
[**MS16-017**](https://technet.microsoft.com/zh-tw/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/zh-tw/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/zh-tw/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/zh-tw/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/zh-tw/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/zh-tw/library/security/ms16-022)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3126446)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3122649)  
(重要)  
Microsoft .NET Framework 3.5  
(3127221)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122655)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127227)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3122658)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3127230)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3133043)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3126446)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3122651)  
(重要)  
Microsoft .NET Framework 3.5  
(3127222)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122654)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127226)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3122660)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3127231)  
(重要)

</td>
<td style="border:1px solid black;">
Active Directory Federation Services 3.0  
(3134222)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3133043)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
(重大)

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
[**MS16-017**](https://technet.microsoft.com/zh-tw/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/zh-tw/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/zh-tw/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/zh-tw/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/zh-tw/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/zh-tw/library/security/ms16-022)

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
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3122654)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127226)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3122660)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3127231)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
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
[**MS16-017**](https://technet.microsoft.com/zh-tw/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/zh-tw/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/zh-tw/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/zh-tw/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/zh-tw/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/zh-tw/library/security/ms16-022)

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
**無**

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
適用於 32 位元系統的 Windows 10  
(3135174)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3135174)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135174)  
(重要)  
Microsoft .NET Framework 4.6  
(3135174)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3135174)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3135174)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135174)  
(重要)  
Microsoft .NET Framework 4.6  
(3135174)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
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
(3135173)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135173)  
(重要)  
Microsoft .NET Framework 4.6.1  
(3135173)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
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
(3135173)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135173)  
(重要)  
Microsoft .NET Framework 4.6.1  
(3135173)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
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
[**MS16-017**](https://technet.microsoft.com/zh-tw/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/zh-tw/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/zh-tw/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/zh-tw/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/zh-tw/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/zh-tw/library/security/ms16-022)

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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3134214)  
(重要)

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
(3133043)  
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
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3134214)  
(重要)

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
(3133043)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3122648)  
(重要)  
Microsoft .NET Framework 3.5.1  
(3127220)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)  
(3133043)  
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
Windows Server 2012 (Server Core 安裝)  
(3126446)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3122649)  
(重要)  
Microsoft .NET Framework 3.5  
(3127221)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122655)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127227)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3122658)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3127230)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)  
(3133043)  
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
Windows Server 2012 R2 (Server Core 安裝)  
(3126446)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3122651)  
(重要)  
Microsoft .NET Framework 3.5  
(3127222)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122654)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127226)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3122660)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3127231)  
(重要)

</td>
<td style="border:1px solid black;">
Active Directory Federation Services 3.0  
(3134222)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)  
(3133043)  
(重要)

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
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-015**](https://technet.microsoft.com/zh-tw/library/security/ms16-015)

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
(3114742)  
(重要)  
Microsoft Excel 2007 Service Pack 3  
(3114741)  
(重要)  
Microsoft Word 2007 Service Pack 3  
(3114748)  
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
[**MS16-015**](https://technet.microsoft.com/zh-tw/library/security/ms16-015)

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
(3114752)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (32 位元版本)  
(3114759)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 位元版本)  
(3114755)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3114752)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (64 位元版本)  
(3114759)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 位元版本)  
(3114755)  
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
[**MS16-015**](https://technet.microsoft.com/zh-tw/library/security/ms16-015)

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
Microsoft Excel 2013 Service Pack 1 (32 位元版本)  
(3114734)  
(重要)  
Microsoft Word 2013 Service Pack 1 (32 位元版本)  
(3114724)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (64 位元版本)  
(3114734)  
(重要)  
Microsoft Word 2013 Service Pack 1 (64 位元版本)  
(3114724)  
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
[**MS16-015**](https://technet.microsoft.com/zh-tw/library/security/ms16-015)

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
Microsoft Excel 2013 RT Service Pack 1  
(3114734)  
(重要)  
Microsoft Word 2013 RT Service Pack 1  
(3114724)  
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
[**MS16-015**](https://technet.microsoft.com/zh-tw/library/security/ms16-015)

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
Microsoft Excel 2016 (32 位元版本)  
(3114698)  
(重要)  
Microsoft Word 2016 (32 位元版本)  
(3114702)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (64 位元版本)  
(3114698)  
(重要)  
Microsoft Word 2016 (64 位元版本)  
(3114702)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-015**](https://technet.microsoft.com/zh-tw/library/security/ms16-015)

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
Microsoft Excel for Mac 2011  
(3137721)  
(重要)  
Microsoft Word for Mac 2011  
(3137721)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 for Mac  
(3134241)  
(重要)  
Microsoft Word 2016 for Mac  
(3134241)  
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
[**MS16-015**](https://technet.microsoft.com/zh-tw/library/security/ms16-015)

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
(3114548)  
(重要)  
Microsoft Office 相容性套件 Service Pack 3  
(3114745)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3114747)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3114773)  
(重要)

</td>
</tr>
</table>
 
**MS16-015 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

 

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
[**MS16-015**](https://technet.microsoft.com/zh-tw/library/security/ms16-015)

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
Microsoft SharePoint Server 2007 Service Pack 3 (32 位元版本)

</td>
<td style="border:1px solid black;">
Excel Services  
(3114432)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 位元版本)

</td>
<td style="border:1px solid black;">
Excel Services  
(3114432)  
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
[**MS16-015**](https://technet.microsoft.com/zh-tw/library/security/ms16-015)

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
Excel Services  
(3114401)  
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
[**MS16-015**](https://technet.microsoft.com/zh-tw/library/security/ms16-015)

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
Excel Services  
(3114335)  
(重要)  
Word Automation Services  
(3114481)  
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
[**MS16-015**](https://technet.microsoft.com/zh-tw/library/security/ms16-015)

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
(3114407)  
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
[**MS16-015**](https://technet.microsoft.com/zh-tw/library/security/ms16-015)

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
(3114338)  
(重要)

</td>
</tr>
</table>
 
**MS16-015 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

 

### Microsoft 伺服器軟體

 
<p></p>
<table style="border:1px solid black;">
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
[**MS16-015**](https://technet.microsoft.com/zh-tw/library/security/ms16-015)

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
Microsoft SharePoint Server 2013 Service Pack 1  
(3039768)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Foundation 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-015**](https://technet.microsoft.com/zh-tw/library/security/ms16-015)

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
Microsoft SharePoint Foundation 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1  
(3114733)  
(重要)

</td>
</tr>
</table>
 
**MS16-015 注意事項**

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

-   V1.0 (2016 年 2 月 9 日)：公告摘要發行。
-   V2.0 (2016 年 2 月 10 日)：針對 MS16-014 修訂公告摘要，以宣佈適用於 Microsoft Windows Vista、Windows Server 2008、Windows Server 2008 for Itanium-based Systems、Windows 8.1 和 Windows Server 2012 R2 的更新 3126041 已可供使用。客戶應套用適用的更新以防止受到本公告中討論的弱點威脅。大部分客戶都已啟用自動更新，不必採取任何行動，因為系統會自動下載和安裝更新。針對 MS16-021 修正 CVE-2016-0050 的弱點利用性評估。
-   V3.0 (2016 年 2 月 16 日)：針對 MS16-015，新增適用於 Microsoft Office 2016 for Mac 的 3134241 更新及適用於 Microsoft Office for Mac 2011 的 3137721 更新 (自 2016 年 2 月 16 日起已可供使用)。如需詳細資訊，請參閱 [Microsoft 知識庫文章 3134241](https://support.microsoft.com/zh-tw/kb/3134241) 和 [Microsoft 知識庫文章 3137721](https://support.microsoft.com/zh-tw/kb/3137721)。
-   V3.1 (2016 年 2 月 24 日)：新增已知問題參考至 MS16-014 的「提要」表格。如需詳細資訊，請參閱 [Microsoft 知識庫文章 3126041](https://support.microsoft.com/zh-tw/kb/3126041)。並也請注意包含因應措施的次要已知問題已新增至 [Microsoft 知識庫文章 3126587](https://support.microsoft.com/zh-tw/kb/3126587)。

*頁面產生時間：24.02.2016 г. 下午 01:45:00-08:00。*
