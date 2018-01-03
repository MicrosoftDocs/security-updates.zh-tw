---
TOCTitle: 'MS16-NOV'
Title: 2016 年 11 月份 Microsoft 安全性公告摘要
ms:assetid: 'ms16-nov'
ms:contentKeyID: 74240705
ms:date: '11/09/2016'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms16-nov(v=Security.10)'
---

2016 年 11 月份 Microsoft 安全性公告摘要
========================================

發行日期：2016年11月8日

**版本：**1.0

此公告摘要列出 2016 年 11 月份發行之安全性公告。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性更新的優先順序，其中這些非安全性更新的發行日期與每月安全性更新的發行日期相同。請參閱**其他資訊**一節。

提要
----

<span id="sectionToggle0"></span>
下表摘要本月安全性公告，以嚴重性高低排序。

如需受影響軟體的詳細資訊，請參閱下一節**＜受影響的軟體＞**。

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
<td style="border:1px solid black;"><strong>最高嚴重性分級<br />
與弱點影響</strong></td>
<td style="border:1px solid black;"><strong>重新啟動需求</strong></td>
<td style="border:1px solid black;"><strong>已知<br />
問題</strong></td>
<td style="border:1px solid black;"><strong>受影響的軟體</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=830431">MS16-129</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 累積安全性更新 (3199057)</strong><br />
這個安全性更新可解決 Microsoft Edge 中的弱點。如果使用者以 Microsoft Edge 檢視蓄意製作的網頁，最嚴重的弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者可以取得與本機使用者相同的使用者權限。在系統將帳戶設定為擁有較少使用者權限的客戶，相較於擁有管理使用者權限的使用者，受到影響較輕微。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=833191">MS16-130</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows 的安全性更新 (3199172)</strong><br />
這個安全性更新可解決 Microsoft Windows 中的弱點。如果在本機驗證的攻擊者執行蓄意製作的應用程式，則這些弱點中最嚴重者可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a>  <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=833189">MS16-131</a></td>
<td style="border:1px solid black;"><strong>Microsoft 視訊控制項的安全性更新 (3199151)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。當 Windows 視訊控制項無法適當處理記憶體中物件時，此弱點可能允許遠端執行程式碼。成功利用此資訊安全風險的攻擊者，能以目前使用者的權限層級執行任意程式碼。然而，攻擊者必須先引誘使用者從網頁或電子郵件訊息中開啟蓄意製作的檔案或程式。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=830425">MS16-132</a></td>
<td style="border:1px solid black;"><strong>Microsoft 圖形元件的安全性更新 (3199120)</strong><br />
這個安全性更新可解決 Microsoft Windows 中的弱點。如果用戶訪問惡意網頁，當 Windows 動畫管理器不正確地處理記憶體中的物件時，最嚴重的弱點可能允許存在遠端執行程式碼弱點。成功利用這項弱點的攻擊者可以安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=833188">MS16-133</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 的安全性更新 (3199168)<br />
</strong>這個安全性更新可解決 Microsoft Office 中的弱點。如果使用者開啟蓄意製作的 Microsoft Office 檔案，最嚴重的弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者，能以目前使用者的權限層級執行任意程式碼。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft Office Services 和 Web 應用程式</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=828018">MS16-134</a></td>
<td style="border:1px solid black;"><strong>一般記錄檔系統驅動程式的安全性更新 (3193706)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。當 Windows 一般記錄檔系統 (CLFS) 驅動程式不當處理記憶體中物件時，此弱點可能會允許權限提高。在本機攻擊的案例中，攻擊者可以利用這些弱點執行蓄意製作的應用程式，以取得受影響系統的完整控制權。成功利用此弱點的攻擊者能以提高權限的層級執行程序。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=830428">MS16-135</a></td>
<td style="border:1px solid black;"><strong>Windows 核心模式驅動程式的安全性更新 (3199135)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者登入受影響的系統，然後執行蓄意製作的應用程式來利用這些弱點，並取得受影響系統的控制權，則最嚴重的弱點可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=830963">MS16-136</a></td>
<td style="border:1px solid black;"><strong>SQL Server 的安全性更新 (3199641)<br />
</strong>這個安全性更新可解決 SQL Server 中的弱點。最嚴重的弱點可能允許攻擊者可提高權限，從而用來檢視、變更或刪除資料；或建立新帳戶。安全性更新修正 SQL Server 處理指標轉型的方式，從而消除了這些最嚴重的弱點。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft SQL Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=833192">MS16-137</a></td>
<td style="border:1px solid black;"><strong>Windows 驗證方法的安全性更新 (3199173)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。最嚴重的弱點可能允許權限提高。要利用此弱點，攻擊者首先需要使用有效的用戶憑據向目標，已加入網域的系統進行身份驗證。成功利用此弱點的攻擊者可以將其許可權從非特權用戶帳戶升級到管理員。攻擊者接下來能在系統上安裝程式；檢視、變更或刪除資料；或建立新帳戶。攻擊者隨後可能嘗試透過本機執行旨在操縱 NTLM 密碼更改請求的蓄意製作的應用程式來提升。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=830965">MS16-138</a></td>
<td style="border:1px solid black;"><strong>Microsoft 虛擬硬碟驅動器的安全性更新 (3199647)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。Windows 虛擬硬碟驅動器不正確地處理用戶對某些檔案的訪問。攻擊者可以透過利用此漏洞在無法為用戶使用的位置處理檔案。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=830965">MS16-139</a></td>
<td style="border:1px solid black;"><strong>Windows 核心的安全性更新 (3199720)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者執行蓄意製作的應用程式訪問敏感資訊，這項弱點可能會允許權限提高。在本機驗證的攻擊者可能會透過執行蓄意製作的應用程式嘗試利用此弱點。攻擊者可透過使用該方法訪問無法為用戶使用的資訊。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=827857">MS16-140</a></td>
<td style="border:1px solid black;"><strong>開機管理程式的安全性更新 (3193479)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。如果物理攻擊者安裝了受影響的開機原則，弱點可能允許安全性功能略過。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
安全性功能略過</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=834404">MS16-141</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player 的安全性更新 (3202790)<br />
</strong>當安裝於所有受支援版本的 Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1、Windows 10 和 Windows Server 2016，此安全性更新可解決 Adobe Flash Player 中的弱點。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Adobe Flash Player</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=830372">MS16-142</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 累積安全性更新 (3198467)<br />
</strong>這個安全性更新可解決 Internet Explorer 中的弱點。如果使用者以 Internet Explorer 檢視蓄意製作的網頁，最嚴重的弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者可以取得與本機使用者相同的使用者權限。如果目前使用者以系統管理的使用者權限登入，則攻擊者即可取得受影響系統的控制權。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
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

<span id="sectionToggle1"></span>
下表提供本月所述每個弱點的利用性評估。這些弱點按照公告識別碼和 CVE ID 列出。只會列出公告上達到「重大」或「重要」嚴重性等級的弱點。

**如何使用此表格？**

您可以運用此表格，針對您可能需要安裝的每一項安全性更新，瞭解資訊安全風險在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務 (DoS) 的可能性。檢閱下列各項評估，依據您的具體設定排定本月更新部署之優先順序。如需關於這些等級意義的更多資訊，以及決定等級方式的詳細資訊，請參閱 [Microsoft 弱點入侵指數](http://technet.microsoft.com/zh-tw/security/cc998259)。

下方欄位「最新軟體版本」意指受影響軟體，「較舊軟體版本」意指受影響軟體所有較舊的支援版本，如公告中的「受影響的軟體」或「不受影響的軟體」表格裡所示。

 
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
[**MS16-129：Microsoft Edge 的累積安全性更新 (3199057)**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7195](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7195)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀資訊安全風險

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
[CVE-2016-7196](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7196)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀資訊安全風險

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
[CVE-2016-7198](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7198)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀資訊安全風險

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
[CVE-2016-7199](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7199)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器資訊洩漏弱點

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
[CVE-2016-7200](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7200)

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
[CVE-2016-7201](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7201)

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
[CVE-2016-7202](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7202)

</td>
<td style="border:1px solid black;">
指令碼引擎記憶體損毀弱點

</td>
<td style="border:1px solid black;">
4 - 不受影響

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
[CVE-2016-7203](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7203)

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
[CVE-2016-7204](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7204)

</td>
<td style="border:1px solid black;">
Microsoft Edge 資訊洩漏弱點

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
[CVE-2016-7208](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7208)

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
[CVE-2016-7209](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7209)

</td>
<td style="border:1px solid black;">
Microsoft Edge 詐騙弱點

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
[CVE-2016-7227](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7227)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器資訊洩漏弱點

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
[CVE-2016-7239](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7239)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器資訊洩漏

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
[CVE-2016-7240](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7240)

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
[CVE-2016-7241](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7241)

</td>
<td style="border:1px solid black;">
Microsoft Browser 遠端執行程式碼弱點

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
[CVE-2016-7242](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7242)

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
[CVE-2016-7243](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7243)

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
<td style="border:1px solid black;" colspan="5">
[**MS16-130：Microsoft Windows 的安全性更新 (3199172)**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7212](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7212)

</td>
<td style="border:1px solid black;">
Windows 遠端執行程式碼弱點

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
[CVE-2016-7221](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7221)

</td>
<td style="border:1px solid black;">
Windows IME 權限提高弱點

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
[CVE-2016-7222](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7222)

</td>
<td style="border:1px solid black;">
工作排程器權限提高資訊安全風險

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
[**MS16-131：Microsoft 視訊控制項的安全性更新 (3199151)**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7248](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-cve-2016-7248)

</td>
<td style="border:1px solid black;">
Microsoft Video Control 的安全性更新

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
[**MS16-132：Microsoft 圖形元件的安全性更新 (3199120)**](https://go.microsoft.com/fwlink/?linkid=830425)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7205](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7205)

</td>
<td style="border:1px solid black;">
Windows 動畫管理器記憶體損壞弱點

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
[CVE-2016-7210](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7210)

</td>
<td style="border:1px solid black;">
打開 Type 字型資訊洩漏弱點

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
[CVE-2016-7217](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7217)

</td>
<td style="border:1px solid black;">
媒體基礎記憶體損壞弱點

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
[CVE-2016-7256](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7256)

</td>
<td style="border:1px solid black;">
打開 Type 字型遠端執行程式碼弱點

</td>
<td style="border:1px solid black;">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
0 - 已偵測到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-133：Microsoft Office 的安全性更新 (3199168)**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7213](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7213)

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
[CVE-2016-7228](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7228)

</td>
<td style="border:1px solid black;">
Microsoft Office 記憶體損毀弱點

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
[CVE-2016-7229](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7229)

</td>
<td style="border:1px solid black;">
Microsoft Office 記憶體損毀弱點

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
[CVE-2016-7230](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7230)

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
[CVE-2016-7231](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7231)

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
[CVE-2016-7232](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7232)

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
[CVE-2016-7233](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7233)

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
[CVE-2016-7234](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7234)

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
[CVE-2016-7235](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7235)

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
[CVE-2016-7236](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7236)

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
[CVE-2016-7244](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7244)

</td>
<td style="border:1px solid black;">
Microsoft Office 阻斷服務弱點

</td>
<td style="border:1px solid black;">
4 - 不受影響

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
[CVE-2016-7245](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7245)

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
<td style="border:1px solid black;" colspan="5">
[**MS16-134：一般記錄檔系統驅動程式的安全性更新 (3193706)**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0026](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0026)

</td>
<td style="border:1px solid black;">
Windows CLFS 權限提高

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
[CVE-2016-3332](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3332)

</td>
<td style="border:1px solid black;">
Windows 一般記錄檔系統驅動程式權限提高弱點

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
[CVE-2016-3333](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3333)

</td>
<td style="border:1px solid black;">
Windows 一般記錄檔系統驅動程式權限提高弱點

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
[CVE-2016-3334](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3334)

</td>
<td style="border:1px solid black;">
Windows 一般記錄檔系統驅動程式權限提高弱點

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
[CVE-2016-3335](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3335)

</td>
<td style="border:1px solid black;">
Windows 一般記錄檔系統驅動程式權限提高弱點

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
[CVE-2016-3338](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3338)

</td>
<td style="border:1px solid black;">
Windows 一般記錄檔系統驅動程式權限提高弱點

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
[CVE-2016-3340](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3340)

</td>
<td style="border:1px solid black;">
Windows 一般記錄檔系統驅動程式權限提高弱點

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
[CVE-2016-3342](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3342)

</td>
<td style="border:1px solid black;">
Windows 一般記錄檔系統驅動程式權限提高弱點

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
[CVE-2016-3343](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3343)

</td>
<td style="border:1px solid black;">
Windows 一般記錄檔系統驅動程式權限提高弱點

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
[CVE-2016-7184](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7184)

</td>
<td style="border:1px solid black;">
Windows CLFS 權限提高

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
[**MS16-135：Windows 核心模式驅動程式的安全性更新 (3199135)**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7214](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7214)

</td>
<td style="border:1px solid black;">
Win32k 資訊洩漏弱點

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
[CVE-2016-7215](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7215)

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
[CVE-2016-7218](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7218)

</td>
<td style="border:1px solid black;">
Bowser.sys 資訊洩漏弱點

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
[CVE-2016-7246](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7246)

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
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7255](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7255)

</td>
<td style="border:1px solid black;">
Win32k 權限提高弱點

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
0 - 已偵測到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-136：SQL Server 的安全性更新 (3199641)**](https://go.microsoft.com/fwlink/?linkid=830963)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7249](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7249)

</td>
<td style="border:1px solid black;">
SQL RDBMS Engine 權限提高弱點

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
[CVE-2016-7250](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7250)

</td>
<td style="border:1px solid black;">
SQL RDBMS Engine 權限提高弱點

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
[CVE-2016-7251](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7251)

</td>
<td style="border:1px solid black;">
MDS API XSS 弱點

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
[CVE-2016-7252](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7252)

</td>
<td style="border:1px solid black;">
SQL 分析服務資訊洩露弱點

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
[CVE-2016-7253](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7253)

</td>
<td style="border:1px solid black;">
SQL Server Agent 權限提高弱點

</td>
<td style="border:1px solid black;">
4 - 不受影響

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
[CVE-2016-7254](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7254)

</td>
<td style="border:1px solid black;">
SQL RDBMS Engine EoP 弱點

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
[**MS16-137：Windows 驗證方法的安全性更新 (3199173)**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7220](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7220)

</td>
<td style="border:1px solid black;">
虛擬安全模式資訊洩露弱點

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
[CVE-2016-7237](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7237)

</td>
<td style="border:1px solid black;">
本地安全認證子系統服務阻斷服務弱點

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
[CVE-2016-7238](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7238)

</td>
<td style="border:1px solid black;">
Windows NTLM 權限提高弱點

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
[**MS16-138：Microsoft 虛擬硬碟驅動器的安全性更新 (3199647)**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7223](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7223)

</td>
<td style="border:1px solid black;">
VHDFS 驅動程式的權限提高弱點

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
[CVE-2016-7224](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7224)

</td>
<td style="border:1px solid black;">
VHDFS 驅動程式的權限提高弱點

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
[CVE-2016-7225](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7225)

</td>
<td style="border:1px solid black;">
VHDFS 驅動程式的權限提高弱點

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
<td style="border:1px solid black;">
[CVE-2016-7226](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7226)

</td>
<td style="border:1px solid black;">
VHDFS 驅動程式的權限提高弱點

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
[**MS16-139：Windows 核心的安全性更新 (3199720)**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7216](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7216)

</td>
<td style="border:1px solid black;">
Windows 核心權限提高弱點

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
[**MS16-140：開機管理程式的安全性更新 (3193479)**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7247](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7247)

</td>
<td style="border:1px solid black;">
安全開機安全性功能略過弱點

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
[**MS16-141：Adobe Flash Player 的安全性更新 (3202790)**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-37](http://helpx.adobe.com/tw/security/products/flash-player/apsb16-37.html)

</td>
<td style="border:1px solid black;">
請參閱 Adobe 資訊安全公告 [APSB16-37](http://helpx.adobe.com/tw/security/products/flash-player/apsb16-37.html) 了解弱點嚴重性以及更新優先順序等級。

</td>
<td style="border:1px solid black;">
---------

</td>
<td style="border:1px solid black;">
---------

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-142：Internet Explorer 的累積安全性更新 (3198467)**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7239](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7239)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器資訊洩漏

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
[CVE-2016-7227](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7227)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器資訊洩漏弱點

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
[CVE-2016-7198](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7198)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀資訊安全風險

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
[CVE-2016-7199](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7199)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器資訊洩漏弱點

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
[CVE-2016-7195](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7195)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀資訊安全風險

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
[CVE-2016-7196](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7196)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀資訊安全風險

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
[CVE-2016-7241](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7241)

</td>
<td style="border:1px solid black;">
Microsoft Browser 遠端執行程式碼弱點

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
</table>
 

受影響的軟體
------------

<span id="sectionToggle2"></span>
下表依據主要的軟體類別和嚴重性依序列出公告。

請用這些表格來了解可能需要安裝的安全性更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的安全性更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。

**注意**：一項弱點，可能需要安裝數個安全性更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。

### Windows 作業系統及元件 (表格 3 之 1)

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(3193418)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3198218)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3198195)  
(重要)

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
(3193418)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3198218)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3198195)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3193418)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3198195)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3193418)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3198195)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3193418)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3198195)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
僅限安全性

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3197867)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3197867)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3197867)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
每月彙總套件

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3197868)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3197868)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3197868)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
僅限安全性

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3197867)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3197867)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3197867)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
每月彙總套件

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3197868)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3197868)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3197868)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
僅限安全性

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197867)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197867)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
每月彙總套件

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197868)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197868)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
僅限安全性

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197867)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197867)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
每月彙總套件

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197868)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197868)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
僅限安全性

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3197873)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3197873)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
每月彙總套件

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3197874)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3197874)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
僅限安全性

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3197873)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3197873)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
每月彙總套件

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3197874)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3197874)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2012  
僅限安全性

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3197876)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3197876)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
每月彙總套件

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3197877)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3197877)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
僅限安全性

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3197873)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3197873)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
每月彙總套件

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3197874)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3197874)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
每月彙總套件

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT 8.1<span></span>
(3197874)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT 8.1<span></span>
(3197874)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT 8.1<span></span>
(3197874)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3198585)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3198585)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3198585)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3198585)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3198585)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3198585)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3198585)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3198585)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3198585)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3198585)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3198586)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3198586)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3198586)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3198586)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 版本 1511  
(3198586)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3198586)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3198586)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3198586)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3198586)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 版本 1511  
(3198586)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版  
(3200970)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版  
(3200970)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版  
(3200970)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版  
(3200970)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 版本 1607  
(3200970)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版  
(3200970)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版 <span></span>
(3200970)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版  
(3200970)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版<span></span>
(3200970)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

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
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

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
適用於 x64 型系統的 Windows Server 2016

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016  
(3200970)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016  
(3200970)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Server Core 安裝選項**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3193418)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3193418)  
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
適用於 x86 位系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3193418)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x86 位系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3193418)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)  
僅限安全性

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3197867)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3197867)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
每月彙總套件

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3197868)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3197868)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012   
(Server Core 安裝)  
僅限安全性

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3197876)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3197876)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)  
每月彙總套件

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3197877)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3197877)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2   
(Server Core 安裝)  
僅限安全性

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3197873)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3197873)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)  
每月彙總套件

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3197874)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3197874)  
(重大)

</td>
</tr>
</table>
 
### Windows 作業系統及元件 (表格 2 之 3)

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16**-138](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;" colspan="2">
Windows Vista Service Pack 2  
(3181707)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Vista Service Pack 2  
(3193418)  
(重要)  
Windows Vista Service Pack 2  
(3194371)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Vista Service Pack 2  
(3198510)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3198483)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;" colspan="2">
Windows Vista x64 Edition Service Pack 2  
(3181707)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Vista x64 Edition Service Pack 2  
(3193418)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3194371)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Vista x64 Edition Service Pack 2  
(3198510)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3198483)  
(重要)

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
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16**-138](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;" colspan="2">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3181707)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3193418)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3194371)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3198510)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3198483)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;" colspan="2">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3181707)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3193418)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3194371)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3198510)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3198483)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;" colspan="2">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3181707)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3193418)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3194371)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3198510)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3198483)  
(重要)

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
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16**-138](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
僅限安全性

</td>
<td style="border:1px solid black;" colspan="2">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3197867)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
每月彙總套件

</td>
<td style="border:1px solid black;" colspan="2">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3197868)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
僅限安全性

</td>
<td style="border:1px solid black;" colspan="2">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3197867)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
每月彙總套件

</td>
<td style="border:1px solid black;" colspan="2">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3197868)  
(重要)

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
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16**-138](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
僅限安全性

</td>
<td style="border:1px solid black;" colspan="2">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197867)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
每月彙總套件

</td>
<td style="border:1px solid black;" colspan="2">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197868)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
僅限安全性

</td>
<td style="border:1px solid black;" colspan="2">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197867)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
每月彙總套件

</td>
<td style="border:1px solid black;" colspan="2">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197868)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16**-138](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
僅限安全性

</td>
<td style="border:1px solid black;" colspan="2">
適用於 32 位元系統的 Windows 8.1  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 32 位元系統的 Windows 8.1  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
適用於 32 位元系統的 Windows 8.1  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 32 位元系統的 Windows 8.1  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
每月彙總套件

</td>
<td style="border:1px solid black;" colspan="2">
適用於 32 位元系統的 Windows 8.1  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 32 位元系統的 Windows 8.1  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
適用於 32 位元系統的 Windows 8.1  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 32 位元系統的 Windows 8.1  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
僅限安全性

</td>
<td style="border:1px solid black;" colspan="2">
適用於 x64 型系統的 Windows 8.1  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 x64 型系統的 Windows 8.1  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
適用於 x64 型系統的 Windows 8.1  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 x64 型系統的 Windows 8.1  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
每月彙總套件

</td>
<td style="border:1px solid black;" colspan="2">
適用於 x64 型系統的 Windows 8.1  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 x64 型系統的 Windows 8.1  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
適用於 x64 型系統的 Windows 8.1  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 x64 型系統的 Windows 8.1  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

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
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16**-138](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
僅限安全性

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2012  
(3197876)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012  
(3197876)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2012  
(3197876)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012  
(3197876)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
每月彙總套件

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2012  
(3197877)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012  
(3197877)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2012  
(3197877)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012  
(3197877)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
僅限安全性

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2012 R2  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012 R2  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2012 R2  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012 R2  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
每月彙總套件

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2012 R2  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012 R2  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2012 R2  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012 R2  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16**-138](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
**無**

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
每月彙總套件

</td>
<td style="border:1px solid black;" colspan="2">
Windows RT 8.1  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows RT 8.1  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows RT 8.1  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16**-138](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10

</td>
<td style="border:1px solid black;" colspan="2">
適用於 32 位元系統的 Windows 10  
(3198585)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 32 位元系統的 Windows 10  
(3198585)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
適用於 32 位元系統的 Windows 10  
(3198585)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 32 位元系統的 Windows 10  
(3198585)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10

</td>
<td style="border:1px solid black;" colspan="2">
適用於 x64 型系統的 Windows 10  
(3198585)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 x64 型系統的 Windows 10  
(3198585)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
適用於 x64 型系統的 Windows 10  
(3198585)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 x64 型系統的 Windows 10  
(3198585)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;" colspan="2">
適用於 32 位元系統的 Windows 10 1511 版  
(3198586)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 32 位元系統的 Windows 10 1511 版  
(3198586)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
適用於 32 位元系統的 Windows 10 1511 版  
(3198586)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 32 位元系統的 Windows 10 1511 版  
(3198586)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;" colspan="2">
適用於 x64 型系統的 Windows 10 1511 版  
(3198586)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 x64 型系統的 Windows 10 1511 版  
(3198586)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
適用於 x64 型系統的 Windows 10 1511 版  
(3198586)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 x64 型系統的 Windows 10 1511 版  
(3198586)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版

</td>
<td style="border:1px solid black;" colspan="2">
適用於 32 位元系統的 Windows 10 1607 版  
(3200970)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 32 位元系統的 Windows 10 1607 版  
(3200970)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
適用於 32 位元系統的 Windows 10 1607 版  
(3200970)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 32 位元系統的 Windows 10 1607 版  
(3200970)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版

</td>
<td style="border:1px solid black;" colspan="2">
適用於 x64 型系統的 Windows 10 1607 版<span></span>
(3200970)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 x64 型系統的 Windows 10 1607 版<span></span>
(3200970)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
適用於 x64 型系統的 Windows 10 1607 版<span></span>
(3200970)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 x64 型系統的 Windows 10 1607 版<span></span>
(3200970)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**公告編號**

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16**-138](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
適用於 x64 型系統的 Windows Server 2016

</td>
<td style="border:1px solid black;" colspan="2">
適用於 x64 型系統的 Windows Server 2016  
(3200970)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 x64 型系統的 Windows Server 2016  
(3200970)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016  
(3200970)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 x64 型系統的 Windows Server 2016  
(3200970)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
不適用

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
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16**-138](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)

</td>
<td style="border:1px solid black;" colspan="2">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2<span></span>(Server Core 安裝)  
(3181707)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2<span></span>(Server Core 安裝)  
(3198234)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2<span></span>(Server Core 安裝)  
(3190847)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3196718)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)

</td>
<td style="border:1px solid black;" colspan="2">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2<span></span>(Server Core 安裝)  
(3181707)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2<span></span>(Server Core 安裝)  
(3198234)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2<span></span>(Server Core 安裝)  
(3190847)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3196718)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)  
僅限安全性

</td>
<td style="border:1px solid black;" colspan="2">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1<span></span>(Server Core 安裝)  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
不適用

</td>
<td style="border:1px solid black;" colspan="4">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1<span></span>(Server Core 安裝)  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1<span></span>(Server Core 安裝)  
(3197867)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
每月彙總套件

</td>
<td style="border:1px solid black;" colspan="2">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1<span></span>(Server Core 安裝)  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
不適用

</td>
<td style="border:1px solid black;" colspan="4">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1<span></span>(Server Core 安裝)  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1<span></span>(Server Core 安裝)  
(3197868)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012   
(Server Core 安裝)  
僅限安全性

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2012<span></span>(Server Core 安裝)  
(3197876)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
不適用

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2012<span></span>(Server Core 安裝)  
(3197876)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012<span></span>(Server Core 安裝)  
(3197876)  
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
每月彙總套件

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2012<span></span>(Server Core 安裝)  
(3197877)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
不適用

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2012<span></span>(Server Core 安裝)  
(3197877)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012<span></span>(Server Core 安裝)  
(3197877)  
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
僅限安全性

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2012 R2<span></span>(Server Core 安裝)  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
不適用

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2012 R2<span></span>(Server Core 安裝)  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012 R2<span></span>(Server Core 安裝)  
(3197873)  
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
每月彙總套件

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2012 R2<span></span>(Server Core 安裝)  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
不適用

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2012 R2<span></span>(Server Core 安裝)  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012 R2<span></span>(Server Core 安裝)  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
</table>
 
** **

### Windows 作業系統及元件 (表格 3 之 3)

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;" colspan="2">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;" colspan="2">
不適用

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3197655)  
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
<td style="border:1px solid black;" colspan="2">
不適用

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3197655)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;" colspan="2">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://catalog.update.microsoft.com/v7/site/search.aspx?q=kb3193418)  
(3193418)

</td>
<td style="border:1px solid black;" colspan="2">
不適用

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3197655)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://catalog.update.microsoft.com/v7/site/search.aspx?q=kb3193418)  
(3193418)

</td>
<td style="border:1px solid black;" colspan="2">
不適用

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3197655)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://catalog.update.microsoft.com/v7/site/search.aspx?q=kb3193418)  
(3193418)

</td>
<td style="border:1px solid black;" colspan="2">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;" colspan="2">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
僅限安全性

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;" colspan="2">
不適用

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197867)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
每月彙總套件

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;" colspan="2">
不適用

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197868)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
僅限安全性

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;" colspan="2">
不適用

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197867)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
每月彙總套件

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;" colspan="2">
不適用

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197868)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;" colspan="2">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
僅限安全性

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
不適用

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197867)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
每月彙總套件

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
不適用

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197868)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
僅限安全性

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;" colspan="2">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
每月彙總套件

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;" colspan="2">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="2">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
僅限安全性

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(重大)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197873)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
每月彙總套件

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(重大)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197874)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
僅限安全性

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(重大)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197873)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
每月彙總套件

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(重大)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197874)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="2">
**中度**

</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
僅限安全性

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3197876)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(中度)

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(3197876)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
每月彙總套件

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3197877)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(中度)

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(3197877)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
僅限安全性

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(中度)

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(3197873)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
每月彙總套件

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(中度)

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(3197874)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
每月彙總套件

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=832634)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="2">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3198585)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(重大)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3198585)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3198585)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(重大)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3198585)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3198586)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(重大)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3198586)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3198586)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(重大)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3198586)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版  
(3200970)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(重大)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3200970)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 10 1607 版

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版<span></span>
(3200970)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(重大)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3200970)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

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
**無**

</td>
<td style="border:1px solid black;" colspan="2">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016  
(3200970)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;" colspan="2">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Server Core 安裝選項**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="2">
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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2<span></span>(Server Core 安裝)  
(3190847)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
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
適用於 x64 型系統的 Windows Server 2008 Service Pack 2<span></span>(Server Core 安裝)  
(3190847)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
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
僅限安全性

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1<span></span>(Server Core 安裝)  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
每月彙總套件

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1<span></span>(Server Core 安裝)  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
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
僅限安全性

</td>
<td style="border:1px solid black;">
Windows Server 2012<span></span>(Server Core 安裝)  
(3197876)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
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
每月彙總套件

</td>
<td style="border:1px solid black;">
Windows Server 2012<span></span>(Server Core 安裝)  
(3197877)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
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
僅限安全性

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2<span></span>(Server Core 安裝)  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
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
每月彙總套件

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2<span></span>(Server Core 安裝)  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
</table>
 
### Microsoft Office 套裝及軟體

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**Microsoft Office 2007**

</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

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
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 Service Pack 3  
(3118395)  
(重要)  
Microsoft Word 2007  
(3127949)  
(重要)  
Microsoft Office 2007 Service Pack 3  
(3118396)  
(重要)  
Microsoft Office 2007 Service Pack 3  
(2986253)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Microsoft Office 2010**

</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

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
Microsoft Office 2010 Service Pack 2 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(3127951)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (32 位元版本)  
(3118390)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 位元版本)  
(3127953)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (32 位元版本)  
(3118378)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(3115120)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3127951)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3127951)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 位元版本)  
(3127953)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (64 位元版本)  
(3118378)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3115120)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Microsoft Office 2013**

</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

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
Microsoft Office 2013 Service Pack 1 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (32 位元版本)  
(3127921)  
(重要)  
Microsoft Office 2013 Service Pack 1 (32 位元版本)  
(3115153)  
(重要)  
Microsoft Word 2013 Service Pack 1 (32 位元版本)  
(3127932)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (64 位元版本)  
(3127921)  
(重要  
Microsoft Office 2013 Service Pack 1 (64 位元版本)  
(3115153)  
(重要)  
Microsoft Word 2013 Service Pack 1 (64 位元版本)  
(3127932)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Microsoft Office 2013 RT**

</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

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
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT Service Pack 1  
(3127921)  
(重要)  
Microsoft Office 2013 RT Service Pack 1  
(3115153)  
(重要)  
Microsoft Word 2013 RT Service Pack 1  
(3127932)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Microsoft Office 2016**

</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

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
Microsoft Office 2016 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (32 位元版本)  
(3127904)  
(重要)  
Microsoft Office 2016 (32 位元版本)  
(3115135)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (64 位元版本)  
(3127904)  
(重要)  
Microsoft Office 2016 (64 位元版本)  
(3115135)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Microsoft Office for Mac 2011**

</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

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
</td>
<td style="border:1px solid black;">
Microsoft Excel for Mac 2011  
(3198807)  
(重要)  
Microsoft Word for Mac 2011  
(3198807)  
(重要)

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
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

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
</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 for Mac  
(3198798)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
其他 Office 軟體

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

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
Microsoft Office 相容性套件 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack Service Pack 3  
(3127889)  
(重要)  
Microsoft Office Compatibility Pack Service Pack 3  
(3127948  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3127893)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer

</td>
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer  
(3118382)  
(重要)

</td>
</tr>
</table>
 
 

### Microsoft Office Services 和 Web Apps

 
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
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

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
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Excel Services  
(3118381)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3127950)  
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
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

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
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3127927)  
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
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

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
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3127954)  
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
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

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
Microsoft Office Web Apps Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3127929)  
(重要)

</td>
</tr>
</table>
 
 

### Microsoft SQL Server

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2012 Service Pack 2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-136**](https://go.microsoft.com/fwlink/?linkid=830963)

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
適用於 x64 型系統的 Microsoft SQL Server 2012 Service Pack 2

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Microsoft SQL Server 2012 Service Pack 2  
(GDR)  
(3194719)  
(重要)  
適用於 x64 型系統的 Microsoft SQL Server 2012 Service Pack 2  
(3194725)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2012 Service Pack 3**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-136**](https://go.microsoft.com/fwlink/?linkid=830963)

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
適用於 x64 型系統的 Microsoft SQL Server 2012 Service Pack 3

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Microsoft SQL Server 2012 Service Pack 3  
(GDR)  
(3194721)  
(重要)  
適用於 x64 型系統的 Microsoft SQL Server 2012 Service Pack 3  
(3194724)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2014 Service Pack 1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-136**](https://go.microsoft.com/fwlink/?linkid=830963)

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
適用於 x64 型系統的 Microsoft SQL Server 2014 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Microsoft SQL Server 2014 Service Pack 1  
(GDR)  
(3194720)  
(重要)  
適用於 x64 型系統的 Microsoft SQL Server 2014 Service Pack 1  
(3194722)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2014 Service Pack 2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-136**](https://go.microsoft.com/fwlink/?linkid=830963)

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
適用於 x64 型系統的 Microsoft SQL Server 2014 Service Pack 2

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Microsoft SQL Server 2014 Service Pack 2  
(3194714)  
(重要)  
適用於 x64 型系統的 Microsoft SQL Server 2014 Service Pack 2  
(3194718)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-136**](https://go.microsoft.com/fwlink/?linkid=830963)

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
適用於 x64 型系統的 Microsoft SQL Server 2016

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Microsoft SQL Server 2016  
(GDR)  
(3194716)  
(重要)  
適用於 x64 型系統的 Microsoft SQL Server 2016  
(3194717)  
(重要)

</td>
</tr>
</table>
 

偵測與部署工具及指南
--------------------

<span id="sectionToggle3"></span>
有幾項資源可協助系統管理員部署安全性更新。

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，查看是否遺漏安全性更新以及是否存在一般安全設定錯誤。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 可協助系統管理員發佈安全性更新。

應用程式相容性工具組隨附的 Update Compatibility Evaluator 元件可針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

如需上述工具以及其他可使用工具的詳細資訊，請參閱 [IT 專業人員的資訊安全工具](http://technet.microsoft.com/zh-tw/security/cc297183)。 

致謝
----

<span id="sectionToggle4"></span>
Microsoft 了解資訊安全業界所做的努力，其盡責地揭露弱點來協助我們保護客戶。請參閱[致謝](https://technet.microsoft.com/zh-tw/library/security/mt674627.aspx)以取得詳細資訊。

其他資訊
--------

<span id="sectionToggle5"></span>
### Microsoft Windows 惡意軟體移除工具

針對每個月第二個星期二發行的公告，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 及下載中心發行更新版本的 Microsoft Windows 惡意軟體移除工具。不定期資訊安全公告發行不提供更新版本的 Microsoft Windows 惡意軟體移除工具。

### MU、WU 及 WSUS 上的非安全性更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件 894199](https://support.microsoft.com/zh-tw/kb/894199)：說明 Software Update Services 和 Windows Server Update Services 的內容變更。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](http://technet.microsoft.com/zh-tw/wsus/bb456965)。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的安全性保護，Microsoft 將在每月發行安全性更新之前，提前向重要安全性軟體提供者提供弱點資訊。安全性軟體提供者可利用此弱點資訊，透過其安全性軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://go.microsoft.com/fwlink/?linkid=215201) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

### 安全性策略與社群

**更新程式管理策略**

[更新管理資訊安全指南](http://go.microsoft.com/fwlink/?linkid=21168) (英文) 提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他資訊安全問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得，您也可以利用「安全性更新」(security update) 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 映像檔的方式，取得本月份 Windows Update 提供的資訊安全更新。如需更多資訊，請參閱 [Microsoft 知識庫文章 913086](https://support.microsoft.com/zh-tw/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全社群](http://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

### 支援

所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要了解您軟體版本的支援週期，請造訪 [Microsoft 支援週期](http://go.microsoft.com/fwlink/?linkid=21742)網站。

適用於 IT 專業人員的安全性解決方案：[TechNet 安全性疑難排解與支援](http://technet.microsoft.com/zh-tw/security/bb980617)

協助保護您執行 Windows 的電腦免於受到病毒和惡意程式碼攻擊：[病毒解決方案與安全性中心](http://support.microsoft.com/zh-tw/contactus/cu_sc_virsec_master)

根據您所在國家/地區的當地支援：[國際化支援](http://support.microsoft.com/zh-tw/common/international.aspx)

### 免責聲明

Microsoft 知識庫中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

### 修訂

-   V1.0 (2016 年 11 月 8 日)：公告摘要發行。

*頁面產生時間：2016/11/7 下午 12:03-08:00。*
