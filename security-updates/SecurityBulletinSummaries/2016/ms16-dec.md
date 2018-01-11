---
TOCTitle: 'MS16-DEC'
Title: 2016 年 12 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms16-dec'
ms:contentKeyID: 74262523
ms:date: '12/14/2016'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms16-dec(v=Security.10)'
---

2016 年 12 月份 Microsoft 資訊安全公告摘要
==========================================

發行日期：2016 年 12 月 13 日

**版本：**1.0

此公告摘要列出 2016 年 12 月份發行之資訊安全公告。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性更新的優先順序，其中這些非安全性更新的發行日期與每月安全性更新的發行日期相同。請參閱**其他資訊**一節。

**注意** 提醒您，[安全性更新導覽](https://portal.msrc.microsoft.com/zh-tw/security-guidance)將會在 2017 年 2 月前取代資訊安全公告。請參閱我們的部落格文章[將我們的承諾延續至安全性更新（英文）](https://blogs.technet.microsoft.com/msrc/2016/11/08/furthering-our-commitment-to-security-updates/)，取得詳細資訊。

提要
----

下表摘要本月安全性公告，以嚴重性高低排序。

如需受影響軟體的詳細資訊，請參閱下一節**＜受影響的軟體＞**。

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
<td style="border:1px solid black;"><strong>最高嚴重性分級<br />
與弱點影響</strong></td>
<td style="border:1px solid black;"><strong>重新啟動需求</strong></td>
<td style="border:1px solid black;"><strong>已知<br />
問題</strong></td>
<td style="border:1px solid black;"><strong>受影響的軟體</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=834441">MS16-144</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 累積安全性更新 (3204059)</strong><br />
這個安全性更新可解決 Internet Explorer 中的弱點。其中最嚴重的弱點，可能在使用者以 Internet Explorer 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用這些弱點的攻擊者可以取得與本機使用者相同的使用者權限。如果目前使用者以系統管理的使用者權限登入，則攻擊者即可取得受影響系統的控制權。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=834442">MS16-145</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 累積安全性更新 (3204062)</strong><br />
這個安全性更新可解決 Microsoft Edge 中的弱點。如果使用者以 Microsoft Edge 檢視蓄意製作的網頁，最嚴重的弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者可以取得與本機使用者相同的使用者權限。在系統將帳戶設定為擁有較少使用者權限的客戶，相較於擁有管理使用者權限的使用者，受到影響較輕微。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=834444">MS16-146</a></td>
<td style="border:1px solid black;"><strong>Microsoft 圖形元件的安全性更新 (3204066)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。如果使用者造訪蓄意製作的網站或開啟蓄意製作的文件，最嚴重的弱點可能會允許遠端執行程式碼。系統中帳戶設定為具有較少使用者權限的使用者，其所受到的影響可能會比利用系統管理使用者權限進行操作的使用者所受到的影響小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=834947">MS16-147</a></td>
<td style="border:1px solid black;"><strong>Microsoft Uniscribe 的安全性更新 (3204063)</strong><br />
這個安全性更新可解決 Windows Uniscribe 中的弱點。如果使用者造訪蓄意製作的網站或開啟蓄意製作的文件，弱點可能會允許遠端執行程式碼。系統中帳戶設定為具有較少使用者權限的使用者，其所受到的影響可能會比利用系統管理使用者權限進行操作的使用者所受到的影響小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=834445">MS16-148</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 的安全性更新 (3204068)<br />
</strong>這個安全性更新可解決 Microsoft Office 中的弱點。如果使用者開啟蓄意製作的 Microsoft Office 檔案，最嚴重的弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者，能以目前使用者的權限層級執行任意程式碼。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft Office Services 和 Web 應用程式</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=834964">MS16-149</a></td>
<td style="border:1px solid black;"><strong>Windows 的安全性更新 (3205655)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。如果本機驗證的攻擊者執行蓄意製作的應用程式，則較嚴重的弱點可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=834939">MS16-150</a></td>
<td style="border:1px solid black;"><strong>Windows 安全核心模式的安全性更新 (3205642)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中一項弱點。如果經過本機驗證的攻擊者在目標系統上執行蓄意製作的應用程式，弱點可能會允許權限提高。成功利用弱點的攻擊者可能會違反虛擬信任層級 (VTL)。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=834956">MS16-151</a></td>
<td style="border:1px solid black;"><strong>核心模式驅動程式的安全性更新 (3205651)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者登入受影響的系統，然後執行蓄意製作的應用程式來利用這些弱點，並取得受影響系統的控制權，則這些弱點可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=834960">MS16-152</a></td>
<td style="border:1px solid black;"><strong>Windows 核心的安全性更新 (3199709)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。Windows 核心不當處理記憶體中的物件時，弱點可能會允許資訊洩漏。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
資訊洩漏</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=835768">MS16-153</a></td>
<td style="border:1px solid black;"><strong>通用記錄檔系統驅動程式的安全性更新 (3207328)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。當 Windows 一般記錄檔系統 (CLFS) 驅動程式不當處理記憶體中物件時，此弱點可能會允許權限提高。在本機攻擊的案例中，攻擊者可能會針對弱點執行蓄意製作的應用程式，來取得受影響系統的控制權。成功利用此弱點的攻擊者可能會以提高的層級執行處理程序。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
資訊洩漏</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=834443">MS16-154</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player 的安全性更新 (3209498)<br />
</strong>當安裝於所有受支援版本的 Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1、Windows 10 和 Windows Server 2016，此安全性更新可解決 Adobe Flash Player 中的弱點。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Adobe Flash Player</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=834937">MS16-155</a></td>
<td style="border:1px solid black;"><strong>.NET Framework 的安全性更新 (3205640)<br />
</strong>這個安全性更新可解決 Microsoft .Net Framework 中的弱點。.NET Framework 4.6.2 中存在安全性弱點，該弱點可能會允許攻擊者在系統閒置時存取應由密碼編譯機制保護的資訊。此更新會更正架構處理開發人員所提供之金鑰的方式，藉此解決弱點，進而在系統閒置時妥善保護資料。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
資訊洩漏</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、Microsoft .NET Framework</td>
</tr>
</tbody>
</table>
  
弱點入侵指數  
------------
  
下表提供本月所述每個弱點的利用性評估。這些弱點按照公告識別碼和 CVE ID 列出。只會列出公告上達到「重大」或「重要」嚴重性等級的弱點。
  
**如何使用此表格？**
  
您可以運用此表格，針對您可能需要安裝的每一項安全性更新，瞭解資訊安全風險在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務 (DoS) 的可能性。檢閱下列各項評估，依據您的具體設定排定本月更新部署之優先順序。如需關於這些等級意義的更多資訊，以及決定等級方式的詳細資訊，請參閱 [Microsoft 弱點入侵指數](http://technet.microsoft.com/zh-tw/security/cc998259)。
  
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
[**MS16-144：Internet Explorer 累積安全性更新 (3204059)**](https://go.microsoft.com/fwlink/?linkid=834441)

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
[CVE-2016-7278](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7278)

</td>
<td style="border:1px solid black;">
Windows 超連結物件程式庫資訊洩漏弱點

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
[CVE-2016-7279](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7279)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

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
[CVE-2016-7281](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7281)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器安全性功能略過

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
[CVE-2016-7282](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7282)

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
[CVE-2016-7283](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-cve-2016-7283)

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
[CVE-2016-7284](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7284)

</td>
<td style="border:1px solid black;">
Internet Explorer 資訊洩漏弱點

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
[CVE-2016-7287](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7287)

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
[**MS16-145：Microsoft Edge 的累積安全性更新 (3204062)**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7181](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7181)

</td>
<td style="border:1px solid black;">
Microsoft Edge 記憶體損毀弱點

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
[CVE-2016-7206](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7206)

</td>
<td style="border:1px solid black;">
Microsoft Edge 資訊洩漏弱點

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
[CVE-2016-7279](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7279)

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
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7280](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7280)

</td>
<td style="border:1px solid black;">
Microsoft Edge 資訊洩漏弱點

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
[CVE-2016-7281](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7281)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器安全性功能略過

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
[CVE-2016-7282](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7282)

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
[CVE-2016-7286](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7286)

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
[CVE-2016-7287](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7287)

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
[CVE-2016-7288](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7288)

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
[CVE-2016-7296](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7296)

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
[CVE-2016-7297](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7297)

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
[**MS16-146：Microsoft 圖形元件的安全性更新 (3204066)**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7257](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7257)

</td>
<td style="border:1px solid black;">
GDI 資訊洩漏弱點

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
[CVE-2016-7272](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7272)

</td>
<td style="border:1px solid black;">
Windows 圖形遠端執行程式碼弱點

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
[CVE-2016-7273](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7273)

</td>
<td style="border:1px solid black;">
Windows 圖形遠端執行程式碼弱點

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
[**MS16-147：Microsoft Uniscribe 的安全性更新 (3204063)**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7274](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7274)

</td>
<td style="border:1px solid black;">
Windows Uniscribe 遠端執行程式碼弱點

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
[**MS16-148：Microsoft Office 的安全性更新 (3204068)**](https://go.microsoft.com/fwlink/?linkid=834445)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7257](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7257)

</td>
<td style="border:1px solid black;">
GDI 資訊洩漏弱點

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
[CVE-2016-7262](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7262)

</td>
<td style="border:1px solid black;">
Microsoft Office 資訊安全功能略過弱點

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
[CVE-2016-7263](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7263)

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
[CVE-2016-7264](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7264)

</td>
<td style="border:1px solid black;">
Microsoft Office 資訊洩漏弱點

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
[CVE-2016-7265](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7265)

</td>
<td style="border:1px solid black;">
Microsoft Office 資訊洩漏弱點

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
[CVE-2016-7266](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7266)

</td>
<td style="border:1px solid black;">
Microsoft Office 資訊安全功能略過弱點

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
[CVE-2016-7267](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7267)

</td>
<td style="border:1px solid black;">
Microsoft Office 資訊安全功能略過弱點

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
[CVE-2016-7268](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7268)

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
[CVE-2016-7275](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7275)

</td>
<td style="border:1px solid black;">
Microsoft Office OLE DLL 端載入資訊弱點

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
[CVE-2016-7276](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7276)

</td>
<td style="border:1px solid black;">
Microsoft Office 資訊洩漏弱點

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
[CVE-2016-7277](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7277)

</td>
<td style="border:1px solid black;">
Microsoft Office 記憶體損毀弱點

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
[CVE-2016-7289](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7289)

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
[CVE-2016-7290](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7290)

</td>
<td style="border:1px solid black;">
Microsoft Office 資訊洩漏弱點

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
[CVE-2016-7291](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7291)

</td>
<td style="border:1px solid black;">
Microsoft Office 資訊洩漏弱點

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
[CVE-2016-7298](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7298)

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
[**MS16-149：Windows 的安全性更新 (3205655)**](https://go.microsoft.com/fwlink/?linkid=834964)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7219](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7219)

</td>
<td style="border:1px solid black;">
Windows 密碼編譯驅動程式的資訊洩漏弱點

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
[CVE-2016-7292](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7292)

</td>
<td style="border:1px solid black;">
Windows Installer 權限提高弱點

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
[**MS16-150：Windows 安全核心模式的安全性更新 (3205642)**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7271](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7271)

</td>
<td style="border:1px solid black;">
Windows 安全核心模式權限提高弱點

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
[**MS16-151：核心模式驅動程式的安全性更新 (3205651)**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7259](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7259)

</td>
<td style="border:1px solid black;">
Win32k 權限提高弱點

</td>
<td style="border:1px solid black;">
3 - 不太可能遭到利用

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
[CVE-2016-7260](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7260)

</td>
<td style="border:1px solid black;">
Win32k 權限提高弱點

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
[**MS16-152：Windows 核心的安全性更新 (3199709)**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7258](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7258)

</td>
<td style="border:1px solid black;">
Windows 核心記憶體位址資訊洩漏弱點

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
[**MS16-153：一般記錄檔系統驅動程式的安全性更新 (3207328)**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7295](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7295)

</td>
<td style="border:1px solid black;">
Windows 通用記錄檔系統驅動程式資訊洩漏弱點

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
[**MS16-154：Adobe Flash Player 的安全性更新 (3202790)**](https://go.microsoft.com/fwlink/?linkid=834443)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-39](http://helpx.adobe.com/tw/security/products/flash-player/apsb16-39.html)

</td>
<td style="border:1px solid black;">
請參閱 Adobe 資訊安全公告 [APSB16-39](http://helpx.adobe.com/tw/security/products/flash-player/apsb16-39.html) 了解弱點嚴重性以及更新優先順序等級。

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
[**MS16-155：.NET Framework 的安全性更新 (3205640)**](https://go.microsoft.com/fwlink/?linkid=834937)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7270](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7270)

</td>
<td style="border:1px solid black;">
.NET Framework 資訊洩漏弱點

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
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3203621)  
(重大)  
Microsoft Windows 超連結物件程式庫  
(3208481)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3204724)  
(重要)  
Windows Vista Service Pack 2  
(3205638)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3196348)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3204808)  
(重要)  
Windows Vista Service Pack 2  
(3196726)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3203621)  
(重大)  
Microsoft Windows 超連結物件程式庫  
(3208481)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3204724)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3205638)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3196348)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3204808)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3196726)  
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
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3203621)  
(中度)  
Microsoft Windows 超連結物件程式庫  
(3208481)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3204724)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3205638)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3196348)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3204808)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3196726)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3203621)  
(中度)  
Microsoft Windows 超連結物件程式庫  
(3208481)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3204724)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3205638)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3196348)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3204808)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3196726)  
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
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3204724)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3205638)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3196348)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3204808)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3196726)  
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
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
僅限安全性

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205394)  
(重大)

</td>
<td style="border:1px solid black;">
不適用                   

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3205394)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3205394)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3205394)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
每月彙總套件

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3207752)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3207752)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3207752)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3207752)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
僅限安全性

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205394)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3205394)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3205394)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3205394)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
每月彙總套件

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3207752)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3207752)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3207752)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3207752)  
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
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
僅限安全性

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(3205394)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3205394)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3205394)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3205394)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
每月彙總套件

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(3207752)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3207752)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3207752)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3207752)  
(重要)

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
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3205394)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3205394)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3205394)  
(重要)

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
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3207752)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3207752)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3207752)  
(重要)

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
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
僅限安全性

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205400)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3205400)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3205400)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3205400)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
每月彙總套件

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205401)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3205401)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3205401)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3205401)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
僅限安全性

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205400)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3205400)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3205400)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3205400)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
每月彙總套件

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205401)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3205401)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3205401)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3205401)  
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
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
僅限安全性

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(3205408)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205408)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205408)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205408)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
每月彙總套件

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(3205409)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205409)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205409)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205409)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
僅限安全性

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(3205400)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205400)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205400)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205400)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
每月彙總套件

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(3205401)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205401)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205401)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205401)  
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
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
每月彙總套件

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205401)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3205401)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3205401)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3205401)  
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
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205383)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3205383)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3205383)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3205383)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3205383)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205383)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3205383)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3205383)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3205383)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3205383)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205386)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3205386)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3205386)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3205386)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3205386)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205386)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3205386)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3205386)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3205386)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3205386)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3206632)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3206632)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版  
(3206632)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版  
(3206632)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版  
(3206632)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3206632)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3206632)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版  
(3206632)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版  
(3206632)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版  
(3206632)  
(重要)

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
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)

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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(3206632)  
(中度)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3206632)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016  
(3206632)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016  
(3206632)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016  
(3206632)  
(重要)

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
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3204724)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3205638)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3196348)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3204808)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3196726)  
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
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3204724)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3205638)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3196348)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3204808)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3196726)  
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
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3205394)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3205394)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3205394)  
(重要)

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
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3207752)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3207752)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3207752)  
(重要)

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
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3205408)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3205408)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3205408)  
(重要)

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
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3205409)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3205409)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3205409)  
(重要)

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
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3205400)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3205400)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3205400)  
(重要)

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
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3205401)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3205401)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3205401)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016  
(Server Core 安裝)  
(3206632)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016  
(Server Core 安裝)  
(3206632)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016  
(Server Core 安裝)  
(3206632)  
(重要)

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
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834937)

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
(3204723)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3203838)  
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
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3204723)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3203838)  
(重要)

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
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834937)

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
(3204723)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3203838)  
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
(3204723)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3203838)  
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
(3204723)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3203838)  
(重要)

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
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834937)

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
<td style="border:1px solid black;">
**無**

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
(3205394)  
(重要)

</td>
<td style="border:1px solid black;">
不適用                   

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3205394)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

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
(3207752)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3207752)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

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
(3205394)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3205394)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

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
(3207752)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3207752)  
(重要)

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
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834937)

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
<td style="border:1px solid black;">
**無**

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
(3205394)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3205394)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

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
(3207752)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3207752)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

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
(3205394)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3205394)  
(重要)

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
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3207752)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3207752)  
(重要)

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
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834937)

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
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3205400)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3205400)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
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
(3205401)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3205401)  
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
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3205400)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3205400)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
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
(3205401)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3205401)  
(重要)

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
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834937)

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
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205408)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205408)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
(中度)

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
(3205409)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205409)  
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
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205400)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205400)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
(中度)

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
(3205401)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205401)  
(重要)

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
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834937)

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
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows RT 8.1  
(3205401)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3205401)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
(重大)

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
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834937)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(3205383)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3205383)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3205383)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3205383)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3205383)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3205383)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3205383)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3205383)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3205386)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3205386)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3205386)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3205386)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3205386)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3205386)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3205386)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3205386)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
(重大)

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
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834937)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Server Core 安裝**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834937)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3204723)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3203838)  
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
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3204723)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3203838)  
(重要)

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
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3205394)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3205394)  
(重要)

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
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3207752)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3207752)  
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
僅限安全性

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3205408)  
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
每月彙總套件

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3205409)  
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
Windows Server 2012 R2   
(Server Core 安裝)  
僅限安全性

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3205400)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3205400)  
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
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3205401)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3205401)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016  
(Server Core 安裝)  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016  
(Server Core 安裝)  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016  
(Server Core 安裝)  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016  
(Server Core 安裝)  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
</table>
 
 

### Microsoft .NET Framework – 僅限安全性版本

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft .NET Framework**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 7 和 Windows Server 2008 R2  
Microsoft .NET Framework 4.6.2 更新 (KB3205406)**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
適用於 32 位元系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204805)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204805)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204805)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204805)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-155**](http://go.microsoft.com/fwlink/?linkid=834937)

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
適用於 32 位元系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204802)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204802)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows Server 2012

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204801)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204802)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
適用於 32 位元系統的 Windows 10 版本 1607  
(3206632)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 版本 1607  
(3206632)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
適用於 x64 型系統的 Windows Server 2016  
(3206632)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Server Core 安裝選項**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204805)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204801)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204802)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016 (Server Core 安裝)  
(3206632)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(重要)

</td>
</tr>
</table>
 
**MS16-155 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

### Microsoft .NET Framework – 每月彙總發行

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft .NET Framework**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 7 和 Windows Server 2008 R2  
Microsoft .NET Framework 4.6.2 更新 (KB3205406)**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
適用於 32 位元系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3205379)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3205379)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3205379)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3205379)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
適用於 32 位元系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3205378)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3205378)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows Server 2012

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3205377)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3205378)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
適用於 32 位元系統的 Windows 10 版本 1607  
(3206632)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 版本 1607  
(3206632)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
適用於 x64 型系統的 Windows Server 2016  
(3206632)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Server Core 安裝選項**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3205379)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3205377)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3205378)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016 (Server Core 安裝)  
(3206632)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(重要)

</td>
</tr>
</table>
 
**MS16-155 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

 

### Microsoft Office 套裝及軟體

 
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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
(3128019)  
(重要)  
Microsoft Word 2007 Service Pack 3  
(3128025)  
(重要)  
Microsoft Office 2007 Service Pack 3  
(2883033)  
(重大)  
Microsoft Office 2007 Service Pack 3  
(3128020)  
(重要)

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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
(3128032)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(3118380)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(2889841)  
(重大)  
Microsoft Excel 2010 Service Pack 2 (32 位元版本)  
(3128037)  
(重要)  
Microsoft Publisher 2010 Service Pack 2 (32 位元版本)  
(3114395)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 位元版本)  
(3128034)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3128032)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3118380)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(2889841)  
(重大)  
Microsoft Excel 2010 Service Pack 2 (64 位元版本)  
(3128037)  
(重要)  
Microsoft Publisher 2010 Service Pack 2 (64 位元版本)  
(3114395)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 位元版本)  
(3128034)  
(重要)

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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
(3128008)  
(重要)  
Microsoft Office 2013 Service Pack 1 (32 位元版本)  
(3127968)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (64 位元版本)  
(3128008)  
(重要)  
Microsoft Office 2013 Service Pack 1 (64 位元版本)  
(3127968)  
(重要)

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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
(3128008)  
(重要)  
Microsoft Office 2013 RT Service Pack 1  
(3127968)  
(重要)

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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
(3128016)  
(重要)  
Microsoft Office 2016 (32 位元版本)  
(3127986)  
(重要)  
Microsoft Office 2016 (32 位元版本)  
(重要)<sup>[1]</sup>

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (64 位元版本)  
(3128016)  
(重要)  
Microsoft Office 2016 (64 位元版本)  
(3127986)  
(重要)  
Microsoft Office 2016 (64 位元版本)  
(重要)<sup>[1]</sup>

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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
Microsoft Office for Mac 2011  
(3198808)  
(重要)  
Microsoft Excel for Mac 2011  
(3198808)  
(重要)  
Microsoft Word for Mac 2011  
(3198808)  
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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
Microsoft Office 2016 for Mac  
(3198800)  
(重要)  
Microsoft Excel 2016 for Mac  
(3198800)  
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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
Microsoft Office Compatibility Pack Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack Service Pack 3  
(3128022)  
(重要)  
Microsoft Office Compatibility Pack Service Pack 3  
(3128024)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3128023)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3128044)  
(重要)  
Microsoft Word Viewer  
(3127995)  
(重大)

</td>
</tr>
</table>
 
<sup>[1]</sup>此項目參考僅適用於隨選即用 (C2R) 版本。

**MS16-148 注意事項**

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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
Microsoft SharePoint Server 2007 Service Pack 3 (32 位元版本)

</td>
<td style="border:1px solid black;">
Excel Services  
(3127892)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 位元版本)

</td>
<td style="border:1px solid black;">
Excel Services  
(3127892)  
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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
(3128029)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3128026)  
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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
(3128035)  
(重要)

</td>
</tr>
</table>
 
**MS16-148 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

 

偵測與部署工具及指南
--------------------

有幾項資源可協助系統管理員部署安全性更新。

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，查看是否遺漏安全性更新以及是否存在一般安全設定錯誤。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 可協助系統管理員發佈安全性更新。

應用程式相容性工具組隨附的 Update Compatibility Evaluator 元件可針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

如需上述工具以及其他可使用工具的詳細資訊，請參閱 [IT 專業人員的資訊安全工具](http://technet.microsoft.com/zh-tw/security/cc297183)。 

致謝
----

Microsoft 了解資訊安全業界所做的努力，其盡責地揭露弱點來協助我們保護客戶。請參閱[致謝](https://technet.microsoft.com/zh-tw/library/security/mt674627.aspx)以取得詳細資訊。

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

-   V1.0 (2016 年 12 月 13 日)：公告摘要發行。

*頁面產生時間：2016-12-07 12:39-08:00。*
