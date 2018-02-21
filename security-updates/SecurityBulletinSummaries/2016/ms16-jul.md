---
TOCTitle: 'MS16-JUL'
Title: 2016 年 7 月 Microsoft 資訊安全公告摘要
ms:assetid: 'ms16-jul'
ms:contentKeyID: 73201239
ms:date: '09/12/2017'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms16-jul(v=Security.10)'
---



2016 年 7 月 Microsoft 資訊安全公告摘要
=======================================

出版日期：2016 年 7 月 12 日 | 更新日期：2017 年 9 月 12 日

**版本：**2.0

此公告摘要列出 2016 年 7 月份所發行的資訊安全公告。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性更新的優先順序，其中這些非安全性更新的發行日期與每月安全性更新的發行日期相同。請參閱**其他資訊**一節。

提要
----

下表摘要本月安全性公告，以嚴重性高低排序。

如需受影響軟體的詳細資訊，請參閱**受影響的軟體**一節。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808143">MS16-084</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 累積安全性更新 (3169991)<br />
</strong>這個安全性更新可解決 Internet Explorer 中的弱點。其中最嚴重的弱點，可能在使用者以 Internet Explorer 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用這些弱點的攻擊者可能會取得與目前使用者相同的使用者權限。如果目前使用者以系統管理的使用者權限登入，則攻擊者即可取得受影響系統的控制權。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808148">MS16-085</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 累積安全性更新 (3169999)<br />
</strong>這個安全性更新可解決 Microsoft Edge 中的弱點。其中最嚴重的弱點，可能在使用者以 Microsoft Edge 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用這些弱點的攻擊者可能會取得與目前使用者相同的使用者權限。在系統將帳戶設定為擁有較少使用者權限的客戶，相較於擁有管理使用者權限的使用者，受到影響較輕微。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808144">MS16-086</a></td>
<td style="border:1px solid black;"><strong>JScript 及 VBScript 的累積安全性更新 (3169996)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中 JScript 及 VBScript 指令碼引擎的弱點。如果使用者造訪蓄意製作的網站，此弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者可能會取得與目前使用者相同的使用者權限。如果目前的使用者以系統管理使用者權限登入，則成功利用這些弱點的攻擊者可以取得受影響系統的控制權。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808150">MS16-087</a></td>
<td style="border:1px solid black;"><strong>Windows 列印多工緩衝處理器元件的安全性更新 (3170005)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。較嚴重的弱點可能會在攻擊者能對工作站或列印伺服器執行攔截式 (MiTM) 攻擊，或對目標網路設定 Rogue 列印伺服器時，允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;"><a href="http://support.microsoft.com/zh-tw/kb/3170005">3170005</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808151">MS16-088</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 的安全性更新 (3170008)<br />
</strong>這個安全性更新可解決 Microsoft Office 中的弱點。如果使用者開啟蓄意製作的 Microsoft Office 檔案，最嚴重的弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者，能以目前使用者的權限層級執行任意程式碼。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft Office Services 和 Web 應用程式</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808157">MS16-089</a></td>
<td style="border:1px solid black;"><strong>Windows 安全核心模式的安全性更新 (3170050)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中一項弱點。Windows 安全核心模式不當處理記憶體中物件時，存在資訊洩漏的弱點。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
資訊洩漏</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808590">MS16-090</a></td>
<td style="border:1px solid black;"><strong>Windows 核心模式驅動程式的安全性更新 (3171481)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者登入受影響的系統，然後執行蓄意製作的應用程式來利用這些弱點，並取得受影響系統的控制權，則較嚴重的弱點可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808156">MS16-091</a></td>
<td style="border:1px solid black;"><strong>.NET Framework 的安全性更新 (3170048)<br />
</strong>這個安全性更新可解決 Microsoft .NET Framework 中的弱點。如果攻擊者上傳蓄意製作的 XML 檔案至 Web 式應用程式，該弱點可能會造成資訊洩漏。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
資訊洩漏</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808706">MS16-092</a></td>
<td style="border:1px solid black;"><strong>Windows 核心的安全性更新 (3171910)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。如果 Windows 核心無法判斷低完整性應用程式如何使用特定物件管理員功能，最嚴重的弱點可能允許略過資訊安全功能。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
安全性功能略過</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=809010">MS16-093</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player 的安全性更新 (3174060)<br />
</strong>當安裝在所有支援的 Windows 8.1、Windows Server 2012、Windows RT 8.1、Windows Server 2012 R2 和 Windows 10 版本時，此安全性更新可解決 Adobe Flash Player 中的弱點。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Adobe Flash Player</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=817339">MS16-094</a></td>
<td style="border:1px solid black;"><strong>安全開機的安全性更新 (3177404)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者在目標裝置上安裝受影響的原則，此弱點可能會允許攻擊者略過安全開機的安全性功能。攻擊者必須具有系統管理員特殊權限或實際存取權，才能安裝原則並略過安全開機。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
安全性功能略過</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
弱點入侵指數  
------------
  
下表提供本月修正所各個弱點的評估。這些弱點按照公告識別碼和 CVE ID 列出。只會列出公告上達到「重大」或「重要」嚴重性等級的弱點。
  
**如何使用此表格？**
  
您可以運用此表格，針對您可能需要安裝的每一項安全性更新，了解資訊安全風險在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務 (DoS) 的可能性。檢視下列各項評估，依據您的設定排定本月的更新佈署優先順序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 資訊安全風險索引](http://technet.microsoft.com/zh-tw/security/cc998259)。
  
下方欄位「最新軟體版本」意指受影響軟體，「較舊軟體版本」意指受影響軟體所有較舊的支援版本，如公告中的「受影響的軟體」或「不受影響的軟體」表格裡所示。

 
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
[**MS16-084：Internet Explorer 的累積安全性更新 (3169991)**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3204](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3204)

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
[CVE-2016-3240](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3240)

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
[CVE-2016-3241](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3241)

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
[CVE-2016-3242](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3242)

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
[CVE-2016-3243](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3243)

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
[CVE-2016-3245](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3245)

</td>
<td style="border:1px solid black;">
Internet Explorer 資訊安全功能略過弱點

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
[CVE-2016-3248](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3248)

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
[CVE-2016-3259](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3259)

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
[CVE-2016-3260](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3260)

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
[CVE-2016-3261](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3261)

</td>
<td style="border:1px solid black;">
Internet Explorer 資訊洩漏弱點

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
[CVE-2016-3264](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3264)

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
[CVE-2016-3273](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3273)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器資訊洩漏弱點

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
[CVE-2016-3274](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3274)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器詐騙弱點

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
[CVE-2016-3277](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3277)

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
<td style="border:1px solid black;" colspan="5">
[**MS16-085：Microsoft Edge 的累積安全性更新 (3169999)**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3244](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3244)

</td>
<td style="border:1px solid black;">
Microsoft Edge 資訊安全功能略過

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
[CVE-2016-3246](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3246)

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
[CVE-2016-3248](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3248)

</td>
<td style="border:1px solid black;">
指令碼引擎記憶體損毀弱點

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
[CVE-2016-3259](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3259)

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
[CVE-2016-3260](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3260)

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
[CVE-2016-3264](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3264)

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
[CVE-2016-3265](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3265)

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
[CVE-2016-3269](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3269)

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
[CVE-2016-3271](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3271)

</td>
<td style="border:1px solid black;">
指令碼引擎資訊洩漏弱點

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
[CVE-2016-3273](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3273)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器資訊洩漏弱點

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
[CVE-2016-3274](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3274)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器詐騙弱點

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
[CVE-2016-3276](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3276)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器詐騙弱點

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
[CVE-2016-3277](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3277)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器資訊洩漏弱點

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
[**MS16-086：JScript 和 VBScript 的累積安全性更新 (3169996)**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3204](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3204)

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
[**MS16-087：Microsoft 列印多工緩衝處理器的安全性更新 (3170005)**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3238](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3238)

</td>
<td style="border:1px solid black;">
Windows 列印多工緩衝處理器的遠端執行程式碼資訊安全風險

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
[CVE-2016-3239](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3239)

</td>
<td style="border:1px solid black;">
Windows 列印多工緩衝處理器權限提高弱點

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
[**MS16-088：Microsoft Office 的安全性更新 (3170008)**](http://go.microsoft.com/fwlink/?linkid=808151)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3278](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3278)

</td>
<td style="border:1px solid black;">
Microsoft Office 記憶體損毀弱點

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
[CVE-2016-3279](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3279)

</td>
<td style="border:1px solid black;">
Microsoft Office 資訊安全功能略過弱點

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
[CVE-2016-3280](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3280)

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
[CVE-2016-3281](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3281)

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
[CVE-2016-3282](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3282)

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
[CVE-2016-3283](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3283)

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
[CVE-2016-3284](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3284)

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
<td style="border:1px solid black;" colspan="5">
[**MS16-089：Windows 安全核心模式的安全性更新 (3170050)**](http://go.microsoft.com/fwlink/?linkid=808157)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3256](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3256)

</td>
<td style="border:1px solid black;">
Windows 安全核心的資訊洩漏弱點

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
<td style="border:1px solid black;" colspan="5">
[**MS16-090：Windows 核心模式驅動程式的安全性更新 (3171481)**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3249](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3249)

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
[CVE-2016-3250](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3250)

</td>
<td style="border:1px solid black;">
Win32k 權限提高弱點

</td>
<td style="border:1px solid black;">
3 - 不太可能遭到利用

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
[CVE-2016-3251](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3251)

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
[CVE-2016-3252](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3252)

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
[CVE-2016-3254](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3254)

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
[CVE-2016-3286](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3286)

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
<td style="border:1px solid black;" colspan="5">
[**MS16-091：.NET Framework 的安全性更新 (3170048)**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3255](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3255)

</td>
<td style="border:1px solid black;">
.NET 資訊洩漏弱點

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS16-092：Windows 核心的安全性更新 (3171910)**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3258](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3258)

</td>
<td style="border:1px solid black;">
Windows 檔案系統的資訊安全功能略過

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
[CVE-2016-3272](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3272)

</td>
<td style="border:1px solid black;">
Windows 核心的資訊洩漏弱點

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
[**MS16-093：Adobe Flash Player 的安全性更新 (3174060)**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-25](http://helpx.adobe.com/tw/security/products/flash-player/apsb16-25.html)

</td>
<td style="border:1px solid black;">
請參閱 [Adobe 資訊安全公告 APSB16-25](http://helpx.adobe.com/tw/security/products/flash-player/apsb16-25.html) 了解弱點嚴重性以及更新優先順序等級。

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
<td style="border:1px solid black;" colspan="5">
[**MS16-094：安全開機的安全性更新 (3177404)**](http://go.microsoft.com/fwlink/?linkid=817339)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3287](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3287)

</td>
<td style="border:1px solid black;">
安全開機的資訊安全功能略過

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

下表依據主要的軟體類別和嚴重性依序列出公告。

請用這些表格來了解可能需要安裝的安全性更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的安全性更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。

**注意**：一項弱點，可能需要安裝數個安全性更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。

 

### Windows 作業系統及元件 (表格 1 之 2)

 
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
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)                   

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)                   

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)                   

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

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
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3170106)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3169659)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3170455)  
(重大)

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
Internet Explorer 9  
(3170106)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3169659)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3170455)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

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
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**普通**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**普通**](http://go.microsoft.com/fwlink/?linkid=21140)

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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3170106)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3169659)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3170455)  
(重大)

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
Internet Explorer 9   
(3170106)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3169659)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3170455)  
(重大)

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
VBScript 5.7  
(3169659)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3170455)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

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
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

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
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 11  
(3170106)  
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
(4038779)  
僅限安全性  
(重大)  
適用於 32 位元系統的 Windows 7 Service Pack 1  
(4038777)  
每月彙總套件  
(重大)

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
Internet Explorer 11  
(3170106)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(4038779)  
僅限安全性  
(重大)  
適用於 x64 型系統的 Windows 7 Service Pack 1  
(4038777)  
每月彙總套件  
(重大)

</td>
<td style="border:1px solid black;">
不適用

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
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**普通**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
**無**

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
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(3170106)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(4038779)  
僅限安全性  
(重大)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(4038777)  
每月彙總套件  
(重大)

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
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(4038779)  
僅限安全性  
(重大)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(4038777)  
每月彙總套件  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

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
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3170106)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(4038793)  
僅限安全性  
(重大)  
適用於 32 位元系統的 Windows 8.1  
(4038792)  
每月彙總套件  
(重大)

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
Internet Explorer 11  
(3170106)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(4038793)  
僅限安全性  
(重大)  
適用於 x64 型系統的 Windows 8.1  
(4038792)  
每月彙總套件  
(重大)

</td>
<td style="border:1px solid black;">
不適用

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
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**普通**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
**無**

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
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(3170106)  
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
(4038786)  
僅限安全性  
(重大)  
Windows Server 2012  
(4038799)  
每月彙總套件  
(重大)

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
Internet Explorer 11   
(3170106)  
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
(4038793)  
僅限安全性  
(重大)  
Windows Server 2012 R2  
(4038792)  
每月彙總套件  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

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
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3170106)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4038792)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

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
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

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
**無**

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
Internet Explorer 11  
(3163912)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3163912)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(4038781)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3163912)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3163912)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3163912)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(4038781)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3163912)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3172985)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3172985)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(4038783)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3172985)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3172985)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3172985)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(4038783)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3172985)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版

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
適用於 32 位元系統的 Windows 10 1607 版  
(4038782)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版

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
適用於 x64 型系統的 Windows 10 1607 版  
(4038782)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

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
**無**

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
Windows Server 2016

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
Windows Server 2016  
(4038782)  
(重大)

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
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

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
[**普通**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(3169659)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3170455)  
(重大)

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
VBScript 5.7  
(3169659)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3170455)  
(重大)

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
JScript 5.8 和 VBScript 5.8  
(3169658)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(4038779)  
僅限安全性  
(重大)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(4038777)  
每月彙總套件  
(重大)

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
Windows Server 2012 (Server Core 安裝)  
(4038786)  
僅限安全性  
(重大)  
Windows Server 2012 (Server Core 安裝)  
(4038799)  
每月彙總套件  
(重大)

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
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(4038793)  
僅限安全性  
(重大)  
Windows Server 2012 R2 (Server Core 安裝)  
(4038792)  
每月彙總套件  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016  
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
Windows Server 2016  
(Server Core 安裝)  
(4038782)  
(重大)

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
<td style="border:1px solid black;" colspan="6">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Vista Service Pack 2  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3163244)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163251)  
(重要)  
Microsoft .NET Framework 4.6  
(3164025)  
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
Windows Vista x64 Edition Service Pack 2  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3163244)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163251)  
(重要)  
Microsoft .NET Framework 4.6  
(3164025)  
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
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3163244)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163251)  
(重要)  
Microsoft .NET Framework 4.6  
(3164025)  
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
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3163244)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163251)  
(重要)  
Microsoft .NET Framework 4.6  
(3164025)  
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
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3163244)  
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
<td style="border:1px solid black;" colspan="6">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3163245)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163251)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3164025)  
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
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3163245)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163251)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3164025)  
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
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3163245)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163251)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3164025)  
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
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3163245)  
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
<td style="border:1px solid black;" colspan="6">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163247)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163291)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3164024)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3170377)  
(重要)  
適用於 32 位元系統的 Windows 8.1  
(3169704)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3172727)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163247)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163291)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3164024)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3170377)  
(重要)  
適用於 x64 型系統的 Windows 8.1  
(3169704)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3172727)  
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
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**普通**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163246)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163250)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3164023)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3170377)  
(重要)  
Windows Server 2012  
(3169704)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3172727)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163247)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163291)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3164024)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3170377)  
(重要)  
Windows Server 2012 R2  
(3169704)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3172727)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3163291)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3164024)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3170377)  
(重要)  
Windows RT 8.1  
(3169704)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3172727)  
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
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(3163912)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163912)  
(重要)  
Microsoft .NET Framework 4.6  
(3163912)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3163912)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3163912)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3163912)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163912)  
(重要)  
Microsoft .NET Framework 4.6  
(3163912)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3163912)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3163912)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3172985)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3172985)  
(重要)  
Microsoft .NET Framework 4.6.1  
(3172985)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3172985)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3172985)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3172985)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3172985)  
(重要)  
Microsoft .NET Framework 4.6.1  
(3172985)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3172985)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3172985)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版

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
適用於 x64 型系統的 Windows 10 1607 版

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
<td style="border:1px solid black;" colspan="6">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
Windows Server 2016

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
<td style="border:1px solid black;" colspan="6">
**Server Core 安裝選項**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3168965)  
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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3168965)  
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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3163245)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163251)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3164025)  
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
Windows Server 2012 (Server Core 安裝)  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163246)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163250)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3164023)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3170377)  
(重要)  
Windows Server 2012 (Server Core 安裝)  
(3169704)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3172727)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163247)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163291)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3164024)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3170377)  
(重要)  
Windows Server 2012 R2 (Server Core 安裝)  
(3169704)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3172727)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016  
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 Service Pack 3  
(3115306)  
(重要)  
Microsoft Word 2007 Service Pack 3  
(3115311)  
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(3115315)  
(重大)  
Microsoft Excel 2010 Service Pack 2 (32 位元版本)  
(3115322)  
(重要)  
Microsoft Outlook 2010 Service Pack 2 (32 位元版本)  
(3115246)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (32 位元版本)  
(3115118)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 位元版本)  
(3115317)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3115315)  
(重大)  
Microsoft Excel 2010 Service Pack 2 (64 位元版本)  
(3115322)  
(重要)  
Microsoft Outlook 2010 Service Pack 2 (64 位元版本)  
(3115246)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (64 位元版本)  
(3115118)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 位元版本)  
(3115317)  
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (32 位元版本)  
(3115262)  
(重要)  
Microsoft Outlook 2013 Service Pack 1 (32 位元版本)  
(3115259)  
(重要)  
Microsoft PowerPoint 2013 Service Pack 1 (32 位元版本)  
(3115254)  
(重要)  
Microsoft Word 2013 Service Pack 1 (32 位元版本)  
(3115292)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (64 位元版本)  
(3115262)  
(重要)  
Microsoft Outlook 2013 Service Pack 1 (64 位元版本)  
(3115259)  
(重要)  
Microsoft PowerPoint 2013 Service Pack 1 (64 位元版本)  
(3115254)  
(重要)  
Microsoft Word 2013 Service Pack 1 (64 位元版本)  
(3115292)  
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT Service Pack 1  
(3115262)  
(重要)  
Microsoft Outlook 2013 RT Service Pack 1  
(3115259)  
(重要)  
Microsoft PowerPoint 2013 RT Service Pack 1  
(3115254)  
(重要)  
Microsoft Word 2013 RT Service Pack 1  
(3115292)  
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (32 位元版本)  
(3115272)  
(重要)  
Microsoft Outlook 2016 (32 位元版本)  
(3115279)  
(重要)  
Microsoft Word 2016 (32 位元版本)  
(3115301)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (64 位元版本)  
(3115272)  
(重要)  
Microsoft Outlook 2016 (64 位元版本)  
(3115279)  
(重要)  
Microsoft Word 2016 (64 位元版本)  
(3115301)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office for Mac 2011**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Excel for Mac 2011  
(3170463)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Word for Mac 2011  
(3170463)  
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 for Mac  
(3170460)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Word 2016 for Mac  
(3170460)  
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
Microsoft Office Compatibility Pack Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack Service Pack 3  
(3115308)  
(重要)  
Microsoft Office Compatibility Pack Service Pack 3  
(3115309)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3115114)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3115393)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3115395)  
(重大)

</td>
</tr>
</table>
 
**MS16-088 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，了解其他受影響的軟體。

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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
Word Automation Services  
(3115312)  
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
(3115285)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
Microsoft SharePoint Server 2016

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2016  
(3115299)  
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
(3115318)  
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
(3115289)  
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
Office Online Server

</td>
<td style="border:1px solid black;">
Office Online Server  
(3115386)  
(重要)

</td>
</tr>
</table>
 
**MS16-088 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，了解其他受影響的軟體。

偵測與部署工具及指南
--------------------

有幾項資源可協助系統管理員部署安全性更新。

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，查看是否遺漏安全性更新及一般資訊安全設定錯誤的狀況。

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

-   [Microsoft 知識庫文件 894199](https://support.microsoft.com/zh-tw/kb/894199)：說明 Software Update Services 和 Windows Server Update Services 的內容變更。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](http://technet.microsoft.com/zh-tw/wsus/bb456965)。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的安全性保護，Microsoft 將在每月發行安全性更新之前，提前向重要安全性軟體提供者提供弱點資訊。安全性軟體提供者可利用此弱點資訊，透過其安全性軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://go.microsoft.com/fwlink/?linkid=215201) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

### 安全性策略與社群

**更新程式管理策略**

[更新管理資訊安全指南](http://go.microsoft.com/fwlink/?linkid=21168) (英文) 提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他資訊安全問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得，您也可以利用「安全性更新」(”security update”) 關鍵字搜尋輕易地找到安全性更新。
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

Microsoft 知識庫提供的資訊係依「現況」提供，不做任何保證。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

### 修訂

-   V1.0 (2016 年 7 月 12 日)：公告摘要發行。
-   V1.1 (2016 年 7 月 29 日)：對於 MS16-087，在「提要」表格新增已知問題參考。如果您在環境中使用網路列印，在您套用 3170005 安全性更新之後，可能會收到有關安裝印表機驅動程式的警告，或者驅動程式可能無法安裝且未出現通知。如需有關更新和已知問題的詳細資訊，請參閱 [Microsoft 知識庫文章 3170005](https://support.microsoft.com/zh-tw/kb/3170005)。
-   V1.2 (2017 年 3 月 17 日)：對於 MS16-084，從＜弱點入侵指數＞移除 CVE-2016-3276，因為 Internet Explorer 9、Internet Explorer 10 和 Internet Explorer 11 不受影響。這只是資訊的變更。
-   V2.0(2017 年 9 月 12 日)：對於 MS16-087，為了解決適用於 CVE-2016-3238 之 3170455 更新的已知問題，Microsoft 已經為目前支援的 Microsoft Windows 版本提供下列更新：

    -   重新發行適用於 Windows Server 2008 的更新 3170455
    -   適用於 Windows 7 及 Windows Server 2008 R2 的每月彙總套件 4038777 和安全性更新 4038779
    -   適用於 Windows Server 2012 的每月彙總套件 4038799 和安全性更新 4038786
    -   適用於 Windows 8.1 及 Windows Server 2012 R2 的每月彙總套件 4038792 和安全性更新 4038793
    -   適用於 Windows 10 的累積更新 4038781
    -   適用於 Windows 10 1511 版的累積更新 4038781
    -   適用於 Windows 10 1607 版及 Windows Server 2016 的累積更新 4038782

    Microsoft 建議執行 Windows Server 2008 的客戶重新安裝更新 3170455。Microsoft 建議執行其他 Windows 支援版本的客戶安裝適用的更新。如需詳細資訊，請參閱 [Microsoft 知識庫文章 3170005](https://support.microsoft.com/zh-tw/help/3170005)

*頁面產生時間：2017 年 9 月 8 日 13:03-07:00。*
