---
TOCTitle: 'MS16-OCT'
Title: 2016 年 10 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms16-oct'
ms:contentKeyID: 74109939
ms:date: '09/09/2017'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms16-oct(v=Security.10)'
---

2016 年 10 月份 Microsoft 資訊安全公告摘要
==========================================

發行日期：2016 年 10 月 11 日 | 更新日期：2017 年 9 月 12 日

**版本：**3.0

此公告摘要列出 2016 年 10 月份所發行之資訊安全公告。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=827591">MS16-118</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 累積安全性更新 (3192887)<br />
</strong>這個安全性更新可解決 Internet Explorer 中的弱點。如果使用者以 Internet Explorer 檢視蓄意製作的網頁，最嚴重的弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者可以取得與本機使用者相同的使用者權限。如果目前使用者以系統管理的使用者權限登入，則攻擊者即可取得受影響系統的控制權。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3185614">3185614</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3185611">3185611</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3188966">3188966</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3192392">3192392</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3192393">3192393</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3192391">3192391</a></td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=827592">MS16-119</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 累積安全性更新 (3192890)<br />
</strong>這個安全性更新可解決 Microsoft Edge 中的弱點。如果使用者以 Microsoft Edge 檢視蓄意製作的網頁，最嚴重的弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者可以取得與本機使用者相同的使用者權限。在系統將帳戶設定為擁有較少使用者權限的客戶，相較於擁有管理使用者權限的使用者，受到影響較輕微。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3185614">3185614</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3185611">3185611</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3188966">3188966</a></td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=827590">MS16-120</a></td>
<td style="border:1px solid black;"><strong>Microsoft 圖形元件的安全性更新 (3192884)<br />
</strong>此安全性更新可以解決 Microsoft Windows、Microsoft .NET Framework、Microsoft Office、商務用 Skype 和 Microsoft Lync 中的弱點。如果使用者造訪蓄意製作的網站或開啟蓄意製作的文件，這些弱點中最嚴重的可能會允許遠端執行程式碼。系統中帳戶設定為具有較少使用者權限的使用者，其所受到的影響可能會比利用系統管理使用者權限進行操作的使用者所受到的影響小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3185614">3185614</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3185611">3185611</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3188966">3188966</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3192392">3192392</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3192393">3192393</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3192391">3192391</a></td>
<td style="border:1px solid black;">Microsoft Windows、Microsoft .NET Framework、<br />
Microsoft Office、商務用 Skype<br />
，以及 Microsoft Lync。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=828158">MS16-121</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 的安全性更新 (3194063)<br />
</strong>這個安全性更新可解決 Microsoft Office 中的弱點。當 Microsoft Office 軟體無法正確處理 RTF 檔案時，Office 軟體即存在 Office RTF 遠端執行程式碼弱點。成功利用此弱點的攻擊者，可能會以目前使用者的權限層級執行任意程式碼。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft Office Services 和 Web 應用程式</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=829051">MS16-122</a></td>
<td style="border:1px solid black;"><strong>Microsoft 視訊控制項的安全性更新 (3195360)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。如果 Windows 視訊控制項無法適當處理記憶體中物件，此弱點可能允許遠端程式碼執行。成功利用此資訊安全風險的攻擊者，能以目前使用者的權限層級執行任意程式碼。然而，攻擊者必須先引誘使用者從網頁或電子郵件訊息中開啟蓄意製作的檔案或程式。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3185614">3185614</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3185611">3185611</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3188966">3188966</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3192392">3192392</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3192393">3192393</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3192391">3192391</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=827595">MS16-123</a></td>
<td style="border:1px solid black;"><strong>Windows 核心模式驅動程式的安全性更新 (3192892)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者登入受影響的系統，然後執行蓄意製作的應用程式來利用這些弱點，並取得受影響系統的控制權，則較嚴重的弱點可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3185614">3185614</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3185611">3185611</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3188966">3188966</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3192392">3192392</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3192393">3192393</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3192391">3192391</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=827821">MS16-124</a></td>
<td style="border:1px solid black;"><strong>Windows 登錄的安全性更新 (3193227)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者可存取機密的登錄資訊，這些弱點可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3185614">3185614</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3185611">3185611</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3188966">3188966</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3192392">3192392</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3192393">3192393</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3192391">3192391</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=827822">MS16-125</a></td>
<td style="border:1px solid black;"><strong>診斷中樞的安全性更新 (3193229)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者登入受影響的系統，並執行蓄意製作的應用程式，則這項弱點可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3185614">3185614</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3185611">3185611</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3188966">3188966</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=829052">MS16-126</a></td>
<td style="border:1px solid black;"><strong>Microsoft 網際網路郵件 API 的安全性更新 (3196067)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。當 Microsoft 網際網路郵件 API 不正確地處理記憶體中的物件時，就會存在資訊洩漏弱點。成功利用此弱點的攻擊者，可以測試磁碟上是否有檔案。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">中度</a><br />
資訊洩漏</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3185614">3185614</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3185611">3185611</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3188966">3188966</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3192392">3192392</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3192393">3192393</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3192391">3192391</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=829053">MS16-127</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player 的安全性更新 (3194343)<br />
</strong>當安裝於所有受支援版本的 Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1 和 Windows 10，此安全性更新可解決 Adobe Flash Player 中的弱點。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Adobe Flash Player</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=832634">MS16-128</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player 的安全性更新 (3201860</strong>)<br />
此安全性更新可解決安裝於所有受支援版本的 Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1 和 Windows 10 上之 Adobe Flash Player 中的弱點。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Adobe Flash Player</td>
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
[**MS16-118：Internet Explorer 的累積安全性更新 (3192887)**](http://go.microsoft.com/fwlink/?linkid=827591)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3267](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3267)

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
[CVE-2016-3298](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3298)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器資訊洩漏弱點

</td>
<td style="border:1px solid black;">
0 - 已偵測到利用

</td>
<td style="border:1px solid black;">
0 - 已偵測到利用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3331](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3331)

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
[CVE-2016-3382](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3382)

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
[CVE-2016-3383](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3383)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

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
[CVE-2016-3384](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3384)

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
[CVE-2016-3385](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3385)

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
[CVE-2016-3387](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3387)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器權限提高弱點

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
[CVE-2016-3388](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3388)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器權限提高弱點

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
[CVE-2016-3390](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3390)

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
[CVE-2016-3391](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3391)

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
<td style="border:1px solid black;" colspan="5">
[**MS16-119：Microsoft Edge 的累積安全性更新 (3192890)**](http://go.microsoft.com/fwlink/?linkid=827592)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3267](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3267)

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
<td style="border:1px solid black;">
[CVE-2016-3331](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3331)

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
[CVE-2016-3382](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3382)

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
[CVE-2016-3386](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3386)

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
[CVE-2016-3387](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3387)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器權限提高弱點

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
[CVE-2016-3388](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3388)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器權限提高弱點

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
[CVE-2016-3389](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3389)

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
[CVE-2016-3390](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3390)

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
[CVE-2016-3391](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3391)

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
[CVE-2016-3392](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3392)

</td>
<td style="border:1px solid black;">
Microsoft Edge 資訊安全功能略過

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
[CVE-2016-7189](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7189)

</td>
<td style="border:1px solid black;">
指令碼引擎遠端執行程式碼弱點

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
[CVE-2016-7190](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7190)

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
[CVE-2016-7194](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7194)

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
[**MS16-120：Microsoft 圖形元件的安全性更新 (3192884)**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3209](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3209)

</td>
<td style="border:1px solid black;">
True Type 字型剖析資訊洩漏弱點

</td>
<td style="border:1px solid black;">
2 - 遭到利用的可能性較小

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
[CVE-2016-3262](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3262)

</td>
<td style="border:1px solid black;">
GDI+ 資訊洩漏弱點

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
[CVE-2016-3263](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3263)

</td>
<td style="border:1px solid black;">
GDI+ 資訊洩漏弱點

</td>
<td style="border:1px solid black;">
4 - 不受影響

</td>
<td style="border:1px solid black;">
2 - 遭到利用的可能性較小

</td>
<td style="border:1px solid black;">
暫時

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3270](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3270)

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
[CVE-2016-3393](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3393)

</td>
<td style="border:1px solid black;">
Windows 圖形元件 RCE 弱點

</td>
<td style="border:1px solid black;">
1 - 較可能遭到利用

</td>
<td style="border:1px solid black;">
0 - 已偵測到利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3396](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3396)

</td>
<td style="border:1px solid black;">
GDI+ 遠端執行程式碼弱點

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
[CVE-2016-7182](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7182)

</td>
<td style="border:1px solid black;">
True Type 字型剖析權限提高弱點

</td>
<td style="border:1px solid black;">
2 - 遭到利用的可能性較小

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
[**MS16-121：Microsoft Office 的安全性更新 (3194063)**](http://go.microsoft.com/fwlink/?linkid=828158)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7193](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7193)

</td>
<td style="border:1px solid black;">
Microsoft Office 記憶體損毀弱點

</td>
<td style="border:1px solid black;">
0 - 已偵測到利用

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
[**MS16-122：Microsoft 視訊控制項的安全性更新 (3195360)**](http://go.microsoft.com/fwlink/?linkid=829051)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0142](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0142)

</td>
<td style="border:1px solid black;">
Microsoft 視訊控制項遠端執行程式碼弱點

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
[**MS16-123：Windows 核心模式驅動程式的安全性更新 (3192892)**](http://go.microsoft.com/fwlink/?linkid=827595)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3266](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3266)

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
[CVE-2016-3341](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3341)

</td>
<td style="border:1px solid black;">
Windows 交易管理員權限提高弱點

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
[CVE-2016-3376](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3376)

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
<td style="border:1px solid black;">
[CVE-2016-7185](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7185)

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
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7211](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7211)

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
[**MS16-124：Windows 登錄的安全性更新 (3193227)**](http://go.microsoft.com/fwlink/?linkid=827821)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0070](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0070)

</td>
<td style="border:1px solid black;">
Windows 核心本機權限提高

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
[CVE-2016-0073](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0073)

</td>
<td style="border:1px solid black;">
Windows 核心本機權限提高

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
[CVE-2016-0075](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0075)

</td>
<td style="border:1px solid black;">
Windows 核心本機權限提高

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
[CVE-2016-0079](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0079)

</td>
<td style="border:1px solid black;">
Windows 核心本機權限提高

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
[**MS16-125：診斷中樞的安全性更新 (3193229)**](http://go.microsoft.com/fwlink/?linkid=827822)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7188](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7188)

</td>
<td style="border:1px solid black;">
Windows 診斷中樞權限提高

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
[**MS16-126：Microsoft 網際網路郵件 API 的安全性更新 (3196067)**](http://go.microsoft.com/fwlink/?linkid=829052)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3298](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3298)

</td>
<td style="border:1px solid black;">
Internet Explorer 資訊洩漏弱點

</td>
<td style="border:1px solid black;">
4 - 不受影響

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
[**MS16-127：Adobe Flash Player 的安全性更新 (3194343)**](http://go.microsoft.com/fwlink/?linkid=829053)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-32](http://helpx.adobe.com/tw/security/products/flash-player/apsb16-32.html)

</td>
<td style="border:1px solid black;">
請參閱 Adobe 資訊安全公告 [APSB16-32](http://helpx.adobe.com/tw/security/products/flash-player/apsb16-32.html) 了解弱點嚴重性以及更新優先順序等級。

</td>
<td style="border:1px solid black;">
-------------

</td>
<td style="border:1px solid black;">
-------------

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-128：Adobe Flash Player 的安全性更新 (3201860)**](http://go.microsoft.com/fwlink/?linkid=832634)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-36](https://helpx.adobe.com/tw/security/products/flash-player/apsb16-36)

</td>
<td style="border:1px solid black;">
請參閱 Adobe 資訊安全公告 [APSB16-36](http://helpx.adobe.com/tw/security/products/flash-player/apsb16-36.html) 了解弱點嚴重性以及更新優先順序等級。

</td>
<td style="border:1px solid black;">
-------------

</td>
<td style="border:1px solid black;">
-------------

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

### Windows 作業系統及元件 (表格 1 之 2)

 
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
[**MS16-118**](http://go.microsoft.com/fwlink/?linkid=827591)

</td>
<td style="border:1px solid black;">
[**MS16-119**](http://go.microsoft.com/fwlink/?linkid=827592)

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-122**](http://go.microsoft.com/fwlink/?linkid=829051)

</td>
<td style="border:1px solid black;">
[**MS16-123**](http://go.microsoft.com/fwlink/?linkid=827595)

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
(3191492)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3191203)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3190847)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3191203)  
(重要)  
Windows Vista Service Pack 2  
(3183431) (重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3191492)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3191203)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3190847)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3191203)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3183431) (重要)

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
[**MS16-118**](http://go.microsoft.com/fwlink/?linkid=827591)

</td>
<td style="border:1px solid black;">
[**MS16-119**](http://go.microsoft.com/fwlink/?linkid=827592)

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-122**](http://go.microsoft.com/fwlink/?linkid=829051)

</td>
<td style="border:1px solid black;">
[**MS16-123**](http://go.microsoft.com/fwlink/?linkid=827595)

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
Internet Explorer 9   
(3191492)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3191203)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3191203)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3183431) (重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3191492)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3191203)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3191203)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3183431) (重要)

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
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3191203)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3191203)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3183431) (重要)

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
[**MS16-118**](http://go.microsoft.com/fwlink/?linkid=827591)

</td>
<td style="border:1px solid black;">
[**MS16-119**](http://go.microsoft.com/fwlink/?linkid=827592)

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-122**](http://go.microsoft.com/fwlink/?linkid=829051)

</td>
<td style="border:1px solid black;">
[**MS16-123**](http://go.microsoft.com/fwlink/?linkid=827595)

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
(3192391)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3192391)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3192391)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3192391)  
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
(3185330)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3185330)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3185330)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3185330)  
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
(3192391)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3192391)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3192391)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3192391)  
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
(3185330)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3185330)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3185330)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3185330)  
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
[**MS16-118**](http://go.microsoft.com/fwlink/?linkid=827591)

</td>
<td style="border:1px solid black;">
[**MS16-119**](http://go.microsoft.com/fwlink/?linkid=827592)

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-122**](http://go.microsoft.com/fwlink/?linkid=829051)

</td>
<td style="border:1px solid black;">
[**MS16-123**](http://go.microsoft.com/fwlink/?linkid=827595)

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
Internet Explorer 11   
(3192391)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3192391)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3192391)  
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
(3185330)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3185330)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3185330)  
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
(3192391)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3192391)  
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
(3185330)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3185330)  
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
[**MS16-118**](http://go.microsoft.com/fwlink/?linkid=827591)

</td>
<td style="border:1px solid black;">
[**MS16-119**](http://go.microsoft.com/fwlink/?linkid=827592)

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-122**](http://go.microsoft.com/fwlink/?linkid=829051)

</td>
<td style="border:1px solid black;">
[**MS16-123**](http://go.microsoft.com/fwlink/?linkid=827595)

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
(3192392)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3192392)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3192392)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3192392)  
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
(3185331)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3185331)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3185331)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3185331)  
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
(3192392)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3192392)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3192392)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3192392)  
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
(3185331)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3185331)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3185331)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3185331)  
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
[**MS16-118**](http://go.microsoft.com/fwlink/?linkid=827591)

</td>
<td style="border:1px solid black;">
[**MS16-119**](http://go.microsoft.com/fwlink/?linkid=827592)

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-122**](http://go.microsoft.com/fwlink/?linkid=829051)

</td>
<td style="border:1px solid black;">
[**MS16-123**](http://go.microsoft.com/fwlink/?linkid=827595)

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
Internet Explorer 10   
(3192393)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3192393)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3192393)  
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
(3185332)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3185332)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3185332)  
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
(3192392)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3192392)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3192392)  
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
(3185331)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3185331)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3185331)  
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
[**MS16-118**](http://go.microsoft.com/fwlink/?linkid=827591)

</td>
<td style="border:1px solid black;">
[**MS16-119**](http://go.microsoft.com/fwlink/?linkid=827592)

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-122**](http://go.microsoft.com/fwlink/?linkid=829051)

</td>
<td style="border:1px solid black;">
[**MS16-123**](http://go.microsoft.com/fwlink/?linkid=827595)

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
(3185331)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3185331)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3185331)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3185331)  
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
[**MS16-118**](http://go.microsoft.com/fwlink/?linkid=827591)

</td>
<td style="border:1px solid black;">
[**MS16-119**](http://go.microsoft.com/fwlink/?linkid=827592)

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-122**](http://go.microsoft.com/fwlink/?linkid=829051)

</td>
<td style="border:1px solid black;">
[**MS16-123**](http://go.microsoft.com/fwlink/?linkid=827595)

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
(3192440)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3192440)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3192440)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3192440)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3192440)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3192440)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3192440)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3192440)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3192440)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3192440)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3192441)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3192441)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3192441)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3192441)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3192441)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3192441)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3192441)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3192441)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3192441)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3192441)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3194798)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3194798)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版  
(3194798)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版  
(3194798)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版  
(3194798)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3194798)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3194798)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版  
(3194798)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版  
(3194798)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版  
(3194798)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1703 版

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
適用於 x64 型系統的 Windows 10 1607 版  
(4038788)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1703 版

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
適用於 x64 型系統的 Windows 10 1607 版  
(4038788)  
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
[**MS16-118**](http://go.microsoft.com/fwlink/?linkid=827591)

</td>
<td style="border:1px solid black;">
[**MS16-119**](http://go.microsoft.com/fwlink/?linkid=827592)

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-122**](http://go.microsoft.com/fwlink/?linkid=829051)

</td>
<td style="border:1px solid black;">
[**MS16-123**](http://go.microsoft.com/fwlink/?linkid=827595)

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
**None**

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
(3191203)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3191203)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3183431) (重要)

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
(3191203)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3191203)  
(重要)  
適用於 64 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3183431) (重要)

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
(3192391)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3192391)  
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
(3185330)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3185330)  
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
(3192393)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3192393)  
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
(3185332)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3185332)  
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
(3192392)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3192392)  
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
(3185331)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3185331)  
(重要)

</td>
</tr>
</table>
 
### Windows 作業系統及元件 (表格 2 之 2)

 
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
[**MS16-124**](http://go.microsoft.com/fwlink/?linkid=827821)

</td>
<td style="border:1px solid black;">
[**MS16-125**](http://go.microsoft.com/fwlink/?linkid=827822)

</td>
<td style="border:1px solid black;">
[**MS16-126**](http://go.microsoft.com/fwlink/?linkid=829052)

</td>
<td style="border:1px solid black;">
[**MS16-127**](http://go.microsoft.com/fwlink/?linkid=829053)

</td>
<td style="border:1px solid black;">
[**MS16-128**](http://go.microsoft.com/fwlink/?linkid=832634)

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
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(3191256)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3193515)  
(中度)

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
(3191256)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3193515)  
(中度)

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
[**MS16-124**](http://go.microsoft.com/fwlink/?linkid=827821)

</td>
<td style="border:1px solid black;">
[**MS16-125**](http://go.microsoft.com/fwlink/?linkid=827822)

</td>
<td style="border:1px solid black;">
[**MS16-126**](http://go.microsoft.com/fwlink/?linkid=829052)

</td>
<td style="border:1px solid black;">
[**MS16-127**](http://go.microsoft.com/fwlink/?linkid=829053)

</td>
<td style="border:1px solid black;">
[**MS16-128**](http://go.microsoft.com/fwlink/?linkid=832634)

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
<td style="border:1px solid black;">
[**低**](http://go.microsoft.com/fwlink/?linkid=21140)

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
32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3191256)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3193515)  
(低)

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
適用於 64 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3191256)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3193515)  
(低)

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
Itanium 系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3191256)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3193515)  
(低)

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
[**MS16-124**](http://go.microsoft.com/fwlink/?linkid=827821)

</td>
<td style="border:1px solid black;">
[**MS16-125**](http://go.microsoft.com/fwlink/?linkid=827822)

</td>
<td style="border:1px solid black;">
[**MS16-126**](http://go.microsoft.com/fwlink/?linkid=829052)

</td>
<td style="border:1px solid black;">
[**MS16-127**](http://go.microsoft.com/fwlink/?linkid=829053)

</td>
<td style="border:1px solid black;">
[**MS16-128**](http://go.microsoft.com/fwlink/?linkid=832634)

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
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)

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
僅限安全性

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3192391)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3192391)  
(中度)

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
適用於 32 位元系統的 Windows 7 Service Pack 1  
每月彙總套件

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3185330)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3185330)  
(中度)

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
僅限安全性

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3192391)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3192391)  
(中度)

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
每月彙總套件

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3185330)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3185330)  
(中度)

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
[**MS16-124**](http://go.microsoft.com/fwlink/?linkid=827821)

</td>
<td style="border:1px solid black;">
[**MS16-125**](http://go.microsoft.com/fwlink/?linkid=827822)

</td>
<td style="border:1px solid black;">
[**MS16-126**](http://go.microsoft.com/fwlink/?linkid=829052)

</td>
<td style="border:1px solid black;">
[**MS16-127**](http://go.microsoft.com/fwlink/?linkid=829053)

</td>
<td style="border:1px solid black;">
[**MS16-128**](http://go.microsoft.com/fwlink/?linkid=832634)

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
<td style="border:1px solid black;">
[**低**](http://go.microsoft.com/fwlink/?linkid=21140)

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
僅限安全性

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3192391)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3192391)  
(低)

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
每月彙總套件

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3185330)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3185330)  
(低)

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
僅限安全性

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3192391)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3192391)  
(低)

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
每月彙總套件

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3185330)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3185330)  
(低)

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
[**MS16-124**](http://go.microsoft.com/fwlink/?linkid=827821)

</td>
<td style="border:1px solid black;">
[**MS16-125**](http://go.microsoft.com/fwlink/?linkid=827822)

</td>
<td style="border:1px solid black;">
[**MS16-126**](http://go.microsoft.com/fwlink/?linkid=829052)

</td>
<td style="border:1px solid black;">
[**MS16-127**](http://go.microsoft.com/fwlink/?linkid=829053)

</td>
<td style="border:1px solid black;">
[**MS16-128**](http://go.microsoft.com/fwlink/?linkid=832634)

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
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
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
(3192392)  
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
(3194343)  
(重大)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3201860)  
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
(3185331)  
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
適用於 x64 型系統的 Windows 8.1  
僅限安全性

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3192392)  
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
(3194343)  
(重大)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3201860)  
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
(3185331)  
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
<td style="border:1px solid black;" colspan="6">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-124**](http://go.microsoft.com/fwlink/?linkid=827821)

</td>
<td style="border:1px solid black;">
[**MS16-125**](http://go.microsoft.com/fwlink/?linkid=827822)

</td>
<td style="border:1px solid black;">
[**MS16-126**](http://go.microsoft.com/fwlink/?linkid=829052)

</td>
<td style="border:1px solid black;">
[**MS16-127**](http://go.microsoft.com/fwlink/?linkid=829053)

</td>
<td style="border:1px solid black;">
[**MS16-128**](http://go.microsoft.com/fwlink/?linkid=832634)

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
<td style="border:1px solid black;">
**None**

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
Windows Server 2012  
僅限安全性

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3192393)  
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
(3194343)  
(中度)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3201860)  
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
(3185332)  
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
Windows Server 2012 R2  
僅限安全性

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3192392)  
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
(3194343)  
(中度)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3201860)  
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
(3185331)  
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
<td style="border:1px solid black;" colspan="6">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-124**](http://go.microsoft.com/fwlink/?linkid=827821)

</td>
<td style="border:1px solid black;">
[**MS16-125**](http://go.microsoft.com/fwlink/?linkid=827822)

</td>
<td style="border:1px solid black;">
[**MS16-126**](http://go.microsoft.com/fwlink/?linkid=829052)

</td>
<td style="border:1px solid black;">
[**MS16-127**](http://go.microsoft.com/fwlink/?linkid=829053)

</td>
<td style="border:1px solid black;">
[**MS16-128**](http://go.microsoft.com/fwlink/?linkid=832634)

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
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows RT 8.1  
(3185331)  
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
(3194343)  
(重大)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3201860)  
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
[**MS16-124**](http://go.microsoft.com/fwlink/?linkid=827821)

</td>
<td style="border:1px solid black;">
[**MS16-125**](http://go.microsoft.com/fwlink/?linkid=827822)

</td>
<td style="border:1px solid black;">
[**MS16-126**](http://go.microsoft.com/fwlink/?linkid=829052)

</td>
<td style="border:1px solid black;">
[**MS16-127**](http://go.microsoft.com/fwlink/?linkid=829053)

</td>
<td style="border:1px solid black;">
[**MS16-128**](http://go.microsoft.com/fwlink/?linkid=832634)

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
(3192440)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3192440)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3194343)  
(重大)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3201860)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3192440)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3192440)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3194343)  
(重大)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3201860)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3192441)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3192441)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3194343)  
(重大)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3201860)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3192441)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3192441)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3194343)  
(重大)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3201860)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版  
(3194798)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版  
(3194798)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3194343)  
(重大)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3201860)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 10 1607 版

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版  
(3194798)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版  
(3194798)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3194343)  
(重大)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3201860)  
(重大)

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
[**MS16-124**](http://go.microsoft.com/fwlink/?linkid=827821)

</td>
<td style="border:1px solid black;">
[**MS16-125**](http://go.microsoft.com/fwlink/?linkid=827822)

</td>
<td style="border:1px solid black;">
[**MS16-126**](http://go.microsoft.com/fwlink/?linkid=829052)

</td>
<td style="border:1px solid black;">
[**MS16-127**](http://go.microsoft.com/fwlink/?linkid=829053)

</td>
<td style="border:1px solid black;">
[**MS16-128**](http://go.microsoft.com/fwlink/?linkid=832634)

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
<td style="border:1px solid black;">
**None**

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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3191256)  
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
(3191256)  
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
僅限安全性

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3192391)  
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
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
每月彙總套件

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3185330)  
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
Windows Server 2012   
(Server Core 安裝)  
僅限安全性

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3192393)  
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
Windows Server 2012  
(Server Core 安裝)  
每月彙總套件

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3185332)  
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
Windows Server 2012 R2   
(Server Core 安裝)  
僅限安全性

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3192392)  
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
Windows Server 2012 R2  
(Server Core 安裝)  
每月彙總套件

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3185331)  
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
</table>
 
 

### Microsoft .NET Framework – 僅限安全性版本

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft .NET Framework**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Vista  
適用於 Vista 和 Server 2008 的 Microsoft .NET Framework 3.0、4.5.2 和 4.6 更新 (KB3188736)**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

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
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.0 Service Pack 2  
(3188726)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3189039)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3189040)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.0 Service Pack 2  
(3188726)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3189039)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3189040)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2008  
適用於 Vista 和 Server 2008 的 Microsoft .NET Framework 3.0、4.5.2 和 4.6 更新 (KB3188736)**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

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
32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.0 Service Pack 2  
(3188726)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3189039)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3189040)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.0 Service Pack 2  
(3188726)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3189039)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3189040)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

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
Windows 7 32 位元系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3188730)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3188730)  
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
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

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
適用於 64 位元系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3188730)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3188730)  
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
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

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
Microsoft .NET Framework 3.5  
(3188732)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3188732)  
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
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

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
Microsoft .NET Framework 3.5  
(3188731)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3188732)  
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
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

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
適用於 32 位元系統的 Windows 10  
(3192440)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3192440)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 版本 1511  
(3192441)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 版本 1511  
(3192441)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 版本 1607  
(3194798)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 版本 1607  
(3194798)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
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
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

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
Microsoft .NET Framework 3.5.1  
(3188730)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3188731)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3188732)  
(重要)

</td>
</tr>
</table>
 
 

### Microsoft .NET Framework – 每月彙總套件版本

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft .NET Framework**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Vista  
適用於 Vista 和 Server 2008 的 Microsoft .NET Framework 3.0、4.5.2 和 4.6 更新 (KB3188744)**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

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
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.0 Service Pack 2  
(3188735)  
重要

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3189051)  
重要

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3189052)  
重要

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.0 Service Pack 2  
(3188735)  
重要

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3189051)  
重要

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3189052)  
重要

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2008  
適用於 Vista 和 Server 2008 的 Microsoft .NET Framework 3.0、4.5.2 和 4.6 更新 (KB3188744)**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

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
32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.0 Service Pack 2  
(3188735)  
重要

</td>
</tr>
<tr>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3189051)  
重要

</td>
</tr>
<tr>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3189052)  
重要

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.0 Service Pack 2  
(3188735)  
重要

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3189051)  
重要

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3189052)  
重要

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

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
Windows 7 32 位元系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3188740)  
重要

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3188740)  
重要

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
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

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
適用於 64 位元系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3188740)  
重要

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3188740)  
重要

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
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

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
Microsoft .NET Framework 3.5  
(3188743)  
重要

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3188743)  
重要

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
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

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
Microsoft .NET Framework 3.5  
(3188741)  
重要

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3188743)  
重要

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
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

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
適用於 32 位元系統的 Windows 10  
(3192440)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
重要

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3192440)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
重要

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 版本 1511  
(3192441)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
重要

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 版本 1511  
(3192441)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
重要

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 版本 1607  
(3194798)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
重要

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 版本 1607  
(3194798)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
重要

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
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

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
Microsoft .NET Framework 3.5.1  
(3188740)  
重要

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3188741)  
重要

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3188743)  
重要

</td>
</tr>
</table>
 
 

### Microsoft 通訊平台和軟體

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**商務用 Skype 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

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
商務用 Skype 2016 (32 位元版本)

</td>
<td style="border:1px solid black;">
商務用 Skype 2016 (32 位元版本)  
(3118327)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
商務用 Skype 基本版 2016 (32 位元版本)

</td>
<td style="border:1px solid black;">
商務用 Skype 基本版 2016 (32 位元版本)  
(3118327)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
商務用 Skype 2016 (64 位元版本)

</td>
<td style="border:1px solid black;">
商務用 Skype 2016 (64 位元版本)  
(3118327)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
商務用 Skype 基本版 2016 (64 位元版本)

</td>
<td style="border:1px solid black;">
商務用 Skype 基本版 2016 (64 位元版本)  
(3118327)  
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
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

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
Microsoft Lync 2013 Service Pack 1 (32 位元)  
(商務用 Skype)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (32 位元)  
(商務用 Skype)  
(3118348)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (32 位元)  
(商務用 Skype 基本版)

</td>
<td style="border:1px solid black;">
Microsoft Lync 基本版 2013 Service Pack 1 (32 位元)  
(商務用 Skype 基本版)  
(3118348)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (64 位元)  
(商務用 Skype)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (64 位元)  
(商務用 Skype)  
(3118348)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (64 位元)  
(商務用 Skype 基本版)

</td>
<td style="border:1px solid black;">
Microsoft Lync 基本版 2013 Service Pack 1 (64 位元)  
(商務用 Skype 基本版)  
(3118348)  
(重要)

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
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

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
(3188397)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 位元)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 位元)  
(3188397)  
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
(3188399)  
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
(3188400)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Live Meeting 2007 Console**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

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
Microsoft Live Meeting 2007 Console

</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 用戶端  
(3189647)  
(重要)

</td>
</tr>
</table>
 
 

### Microsoft 開發者工具和軟體

 
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
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

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
安裝在 Mac 上的 Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
安裝在 Mac 上的 Microsoft Silverlight 5  
(3193713)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
安裝在 Mac 上的 Microsoft Silverlight 5 Developer 執行階段

</td>
<td style="border:1px solid black;">
安裝在 Mac 上的 Microsoft Silverlight 5 Developer 執行階段  
(3193713)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
安裝在所有受支援版本的 Microsoft Windows 用戶端上的 Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
安裝在所有受支援版本的 Microsoft Windows 用戶端上的 Microsoft Silverlight 5  
(3193713)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
安裝在所有受支援的 Microsoft Windows 用戶端版本上的 Microsoft Silverlight 5 Developer 執行階段

</td>
<td style="border:1px solid black;">
安裝在所有受支援版本的 Microsoft Windows 用戶端上的 Microsoft Silverlight 5 Developer 執行階段  
(3193713)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
安裝在所有受支援的 Microsoft Windows 伺服器版本上的 Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
安裝在所有受支援版本的 Microsoft Windows 伺服器上的 Microsoft Silverlight 5  
(3193713)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
安裝在所有受支援的 Microsoft Windows 伺服器版本上的 Microsoft Silverlight 5 Developer 執行階段

</td>
<td style="border:1px solid black;">
安裝在所有受支援版本的 Microsoft Windows 伺服器上的 Microsoft Silverlight 5 Developer 執行階段  
(3193713)  
(重要)

</td>
</tr>
</table>
 
 

### Microsoft Office 套裝及軟體

 
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
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-121**](http://go.microsoft.com/fwlink/?linkid=828158)

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
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3118301)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Word 2007 Service Pack 3  
(3118308)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-121**](http://go.microsoft.com/fwlink/?linkid=828158)

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
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(3118317)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(3118311)  
(重大)  
Microsoft Word 2010 Service Pack 2 (32 位元版本)  
(3118312)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3118317)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3118311)  
(重大)  
Microsoft Word 2010 Service Pack 2 (64 位元版本)  
(3118312)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-121**](http://go.microsoft.com/fwlink/?linkid=828158)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 位元版本)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 Service Pack 1 (32 位元版本)  
(3118345)  
(重大)

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
Microsoft Word 2013 Service Pack 1 (64 位元版本)  
(3118345)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-121**](http://go.microsoft.com/fwlink/?linkid=828158)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 RT Service Pack 1  
(3118345)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-121**](http://go.microsoft.com/fwlink/?linkid=828158)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (32 位元版本)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Word 2016 (32 位元版本)  
(3118331)  
(重大)

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
Microsoft Word 2016 (64 位元版本)  
(3118331)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office for Mac 2011**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-121**](http://go.microsoft.com/fwlink/?linkid=828158)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Word for Mac 2011  
(3193442)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2016 for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-121**](http://go.microsoft.com/fwlink/?linkid=828158)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Word 2016 for Mac  
(3193438)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**其他 Office 軟體**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-121**](http://go.microsoft.com/fwlink/?linkid=828158)

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
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(3118307)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3118394)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3127898)  
(重大)

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
[**MS16-121**](http://go.microsoft.com/fwlink/?linkid=828158)

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
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3118377)  
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
[**MS16-121**](http://go.microsoft.com/fwlink/?linkid=828158)

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
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3118352)  
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
[**MS16-121**](http://go.microsoft.com/fwlink/?linkid=828158)

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
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3118384)  
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
[**MS16-121**](http://go.microsoft.com/fwlink/?linkid=828158)

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
Microsoft Office Web Apps Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3118360)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Office Online Server

</td>
<td style="border:1px solid black;">
Office Online Server  
(3127897)  
(重大)

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

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全社群](http://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

### 支援

所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要了解您軟體版本的支援週期，請造訪 [Microsoft 支援週期](http://go.microsoft.com/fwlink/?linkid=21742)網站。

適用於 IT 專業人員的安全性解決方案：[TechNet 安全性疑難排解與支援](http://technet.microsoft.com/zh-tw/security/bb980617)

協助保護您執行 Windows 的電腦免於受到病毒和惡意程式碼攻擊：[病毒解決方案與安全性中心](http://support.microsoft.com/zh-tw/contactus/cu_sc_virsec_master)

根據您所在國家/地區的當地支援：[國際化支援](http://support.microsoft.com/zh-tw/common/international.aspx)

### 免責聲明

Microsoft 知識庫中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

### 日期

-   V1.0 (2016 年 10 月 11 日)：公告摘要發行。
-   V1.1 (2016 年 10 月 12 日)：公告摘要修訂，將 MS16-121 的嚴重性變更為「重大」。這只是資訊的變更。
-   V2.0 (2016 年 10 月 27 日)：公告摘要修訂，新增 Flash MS16-128 公告。
-   V3.0 (2017 年 9 月 12 日)：針對 MS16-123，已修訂「Windows 作業系統和元件受影響的軟體」表格，以包含 32 位元系統 Windows 10 1703 版和 x64 型系統 Windows 10 1703 版，因為它們也受到 CVE-2016-3376 的影響。Microsoft 建議執行 Windows 10 1703 版的客戶安裝更新 4038788，以取得保護，避免因為此弱點而受害。

*頁面產生時間：2017 年 9 月 5 日 09:21-07:00。*
