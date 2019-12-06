---
TOCTitle: 'MS16-SEP'
Title: 2016 年 9 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms16-sep'
ms:contentKeyID: 73896062
ms:date: '07/11/2017'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms16-sep(v=Security.10)'
---



2016 年 9 月份 Microsoft 資訊安全公告摘要
=========================================

發行日期：2016 年 9 月 13 日 | 更新日期：2017 年 7 月 11 日

**版本：**1.1

此公告摘要列出 2016 年 9 月份所發行之資訊安全公告。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性更新的優先順序，其中這些非安全性更新的發行日期與每月安全性更新的發行日期相同。請參閱**其他資訊**一節。

提要
----

下表摘要本月資訊安全公告，以嚴重性高低排序。

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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=823624">MS16-104</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 累積安全性更新 (3183038)<br />
</strong>這個安全性更新可解決 Internet Explorer 中的弱點。如果使用者以 Internet Explorer 檢視蓄意製作的網頁，最嚴重的弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者可以取得與本機使用者相同的使用者權限。如果目前使用者以系統管理的使用者權限登入，則攻擊者即可取得受影響系統的控制權。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3185319">3185319</a></td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=823625">MS16-105</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 累積安全性更新 (3183043)<br />
</strong>這個安全性更新可解決 Microsoft Edge 中的弱點。如果使用者以 Microsoft Edge 檢視蓄意製作的網頁，最嚴重的弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者可以取得與本機使用者相同的使用者權限。在系統將帳戶設定為擁有較少使用者權限的客戶，相較於擁有管理使用者權限的使用者，受到影響較輕微。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=824814">MS16-106</a></td>
<td style="border:1px solid black;"><strong>Microsoft 圖形元件的安全性更新 (3185848)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。如果使用者造訪蓄意製作的網站或開啟蓄意製作的文件，最嚴重的弱點可能會允許遠端執行程式碼。系統中帳戶設定為具有較少使用者權限的使用者，其所受到的影響可能會比利用系統管理使用者權限進行操作的使用者所受到的影響小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=824817">MS16-107</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 的安全性更新 (3185852)<br />
</strong>這個安全性更新可解決 Microsoft Office 中的弱點。如果使用者開啟蓄意製作的 Microsoft Office 檔案，最嚴重的弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者，能以目前使用者的權限層級執行任意程式碼。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft Office Services 和 Web 應用程式</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=824829">MS16-108</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange Server 的安全性更新 (3185883)<br />
</strong>這個安全性更新可解決 Microsoft Exchange Server 中的弱點。如果攻擊者向易受攻擊的 Exchange 伺服器傳送含蓄意製作附件之電子郵件，最嚴重的弱點可能會允許在某些建置為 Exchange Server 的 Oracle Outside In 程式庫中遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Exchange</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=824768">MS16-109</a></td>
<td style="border:1px solid black;"><strong>Silverlight 的安全性更新 (3182373)<br />
</strong>這個安全性更新可解決 Microsoft Silverlight 中的弱點。如果使用者瀏覽包含蓄意製作之 Silverlight 應用程式的被駭網站，此弱點可能允許遠端執行程式碼。攻擊者並不能強迫使用者造訪被駭網站，而是引誘使用者自行前往。一般的做法是設法讓使用者按一下電子郵件或即時訊息中通往攻擊者網站的連結。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">不需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=821596">MS16-110</a></td>
<td style="border:1px solid black;"><strong>Windows 的安全性更新 (3178467)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者建立蓄意製作的要求並在目標系統中使用較高權限執行任意程式碼，最嚴重的弱點可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3187754">3187754</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=825142">MS16-111</a></td>
<td style="border:1px solid black;"><strong>Windows 核心的安全性更新 (3186973)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者在目標系統上執行蓄意製作的應用程式，這些弱點可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3175024">3175024</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=821605">MS16-112</a></td>
<td style="border:1px solid black;"><strong>Windows 鎖定畫面的安全性更新 (3178469)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中一項弱點。如果 Windows 不當允許從 Windows 鎖定畫面載入網路內容，此類弱點可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=824825">MS16-113</a></td>
<td style="border:1px solid black;"><strong>Windows 安全核心模式的安全性更新 (3185876)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中一項弱點。Windows 安全核心模式不當處理記憶體中物件時，存在資訊洩漏的弱點。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
資訊洩漏</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=824826">MS16-114</a></td>
<td style="border:1px solid black;"><strong>SMBv1 Server 的安全性更新 (3185879)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中一項弱點。在 Windows Vista、Windows Server 2008、Windows 7 和 Windows Server 2008 R2 作業系統中，如果已驗證的攻擊者向受影響的 Microsoft Server Message Block 1.0 (SMBv1) Server 傳送蓄意製作的封包，此弱點可能允許遠端執行程式碼。此弱點不影響其他 SMB Server 版本。儘管以後的作業系統也受到影響，但是潛在影響是阻斷服務。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=825727">MS16-115</a></td>
<td style="border:1px solid black;"><strong>Windows PDF 文件庫的安全性更新 (3188733)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中的弱點。如果使用者線上檢視蓄意製作之 PDF 內容，或開啟蓄意製作之 PDF 文件，此類弱點可能會允許資訊洩漏。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
資訊洩漏</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=825725">MS16-116</a></td>
<td style="border:1px solid black;"><strong>適用 VBScript 指令碼引擎的 OLE 自動化安全性更新 (3188724)<br />
</strong>這個安全性更新可解決 Microsoft Windows 中一項弱點。如果攻擊者成功引誘受影響系統之使用者造訪惡意網站或被駭網站，此弱點可能會允許遠端執行程式碼。請注意，您必須安裝兩個更新以防止受到本公告中所討論弱點的威脅：本公告 (MS16-116) 中的更新，以及 <a href="https://go.microsoft.com/fwlink/?linkid=823624">MS16-104</a> 中的更新。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows<br />
</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=825603">MS16-117</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player 的安全性更新 (3188128)<br />
</strong>當安裝於所有受支援版本的 Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1 和 Windows 10，此安全性更新可解決 Adobe Flash Player 中的弱點。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
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

下表提供本月所述每個弱點的利用性評估。這些弱點按照公告識別碼和 CVE ID 列出。只會列出公告上達到「重大」或「重要」嚴重性等級的弱點。

**如何使用此表格？**

您可以運用此表格，針對您可能需要安裝的每一項安全性更新，了解弱點在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務的可能性。檢閱下列各項評估，依據您的具體設定排定本月更新部署之優先順序。如需關於這些等級意義的更多資訊，以及決定等級方式的詳細資訊，請參閱 [Microsoft 弱點入侵指數](https://technet.microsoft.com/zh-tw/security/cc998259)。

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
[**MS16-104：Internet Explorer 的累積安全性更新 (3183038)**](https://go.microsoft.com/fwlink/?linkid=823624)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3247](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3247)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

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
[CVE-2016-3291](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3291)

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
[CVE-2016-3292](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3292)

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
[CVE-2016-3295](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3295)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

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
[CVE-2016-3297](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3297)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

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
[CVE-2016-3324](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3324)

</td>
<td style="border:1px solid black;">
Internet Explorer 記憶體損毀弱點

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
[CVE-2016-3325](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3325)

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
[CVE-2016-3351](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3351)

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
[CVE-2016-3353](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3353)

</td>
<td style="border:1px solid black;">
Internet Explorer 資訊安全功能略過

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
[CVE-2016-3375](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3375)

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
[**MS16-105：Microsoft Edge 的累積安全性更新 (3183043)**](https://go.microsoft.com/fwlink/?linkid=823625)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3247](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3247)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

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
[CVE-2016-3291](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3291)

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
[CVE-2016-3294](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3294)

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
[CVE-2016-3295](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3295)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

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
[CVE-2016-3297](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3297)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器記憶體損毀弱點

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
[CVE-2016-3325](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3325)

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
[CVE-2016-3330](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3330)

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
[CVE-2016-3350](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3350)

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
[CVE-2016-3351](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3351)

</td>
<td style="border:1px solid black;">
Microsoft 瀏覽器資訊洩漏弱點

</td>
<td style="border:1px solid black;">
0 - 已偵測到利用

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
[CVE-2016-3370](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3370)

</td>
<td style="border:1px solid black;">
PDF 文件庫資訊洩漏弱點

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
[CVE-2016-3374](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3374)

</td>
<td style="border:1px solid black;">
PDF 文件庫資訊洩漏弱點

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
[CVE-2016-3377](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3377)

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
[**MS16-106：Microsoft 圖形元件的安全性更新 (3185848)**](https://go.microsoft.com/fwlink/?linkid=824814)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3348](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3348)

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
[CVE-2016-3349](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3349)

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
[CVE–2016-3354](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3354)

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
[CVE–2016-3355](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3355)

</td>
<td style="border:1px solid black;">
GDI 權限提高弱點

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
[CVE–2016-3356](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3356)

</td>
<td style="border:1px solid black;">
GDI 遠端執行程式碼弱點

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
[**MS16-107：Microsoft Office 的安全性更新 (3185852)**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0137](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0137)

</td>
<td style="border:1px solid black;">
Microsoft APP-V ASLR 略過

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
[CVE-2016-0141](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0141)

</td>
<td style="border:1px solid black;">
Microsoft 資訊洩漏弱點

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
[CVE-2016-3357](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3357)

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
[CVE-2016-3358](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3358)

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
[CVE-2016-3359](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3359)

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
[CVE-2016-3360](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3360)

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
[CVE-2016-3361](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3361)

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
[CVE-2016-3362](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3362)

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
[CVE-2016-3363](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3363)

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
[CVE-2016-3364](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3364)

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
[CVE-2016-3365](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3365)

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
[CVE-2016-3366](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3366)

</td>
<td style="border:1px solid black;">
Microsoft Office 詐騙弱點

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
[CVE-2016-3381](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3381)

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
[**MS16-108：Microsoft Exchange Server 的安全性更新 (3185883)**](https://go.microsoft.com/fwlink/?linkid=824829)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0138](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0138)

</td>
<td style="border:1px solid black;">
Microsoft Exchange 資訊洩漏弱點

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
[CVE-2016-3378](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3378)

</td>
<td style="border:1px solid black;">
Microsoft Exchange 開啟重新導向弱點

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
[CVE-2016-3379](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3379)

</td>
<td style="border:1px solid black;">
Microsoft Exchange 權限提高弱點

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
[**MS16-109：Silverlight 的安全性更新 (3182373)**](https://go.microsoft.com/fwlink/?linkid=824768)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3367](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3367)

</td>
<td style="border:1px solid black;">
Microsoft Silverlight 記憶體損毀弱點

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
[**MS16-110：Windows 的安全性更新 (3178467)**](https://go.microsoft.com/fwlink/?linkid=821596)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3346](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3346)

</td>
<td style="border:1px solid black;">
Windows 權限執行強制權限提高弱點

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
[CVE-2016-3352](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3352)

</td>
<td style="border:1px solid black;">
Microsoft 資訊洩漏弱點

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
[CVE-2016-3368](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3368)

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
[CVE-2016-3369](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3369)

</td>
<td style="border:1px solid black;">
Windows 阻斷服務弱點

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS16-111：Windows 核心的安全性更新 (3186973)**](https://go.microsoft.com/fwlink/?linkid=825142)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3305](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3305)

</td>
<td style="border:1px solid black;">
Windows 工作階段物件權限提高弱點

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
[CVE-2016-3306](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3306)

</td>
<td style="border:1px solid black;">
Windows 工作階段物件權限提高弱點

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
[CVE-2016-3371](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3371)

</td>
<td style="border:1px solid black;">
Windows 核心權限提高弱點

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
[CVE-2016-3372](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3372)

</td>
<td style="border:1px solid black;">
Windows 核心權限提高弱點

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
[CVE-2016-3373](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3373)

</td>
<td style="border:1px solid black;">
Windows 核心權限提高弱點

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
[**MS16-112：鎖定畫面的安全性更新 (3178469)**](https://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3302](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3302)

</td>
<td style="border:1px solid black;">
Windows 鎖定畫面權限提高弱點

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
[**MS16-113：Windows 安全核心模式的安全性更新 (3185876)**](https://go.microsoft.com/fwlink/?linkid=824825)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3344](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3344)

</td>
<td style="border:1px solid black;">
Windows 安全核心模式資訊洩露弱點

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
<td style="border:1px solid black;" colspan="5">
[**MS16-114：SMBv1 Server 的安全性更新 (3185879)**](https://go.microsoft.com/fwlink/?linkid=824826)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3345](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3345)

</td>
<td style="border:1px solid black;">
Windows SMB 驗證遠端執行程式碼弱點

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS16-115：Microsoft Windows PDF 文件庫的安全性更新 (3188733)**](https://go.microsoft.com/fwlink/?linkid=825727)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3370](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3370)

</td>
<td style="border:1px solid black;">
PDF 文件庫資訊洩漏弱點

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
[CVE-2016-3374](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3374)

</td>
<td style="border:1px solid black;">
PDF 文件庫資訊洩漏弱點

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
[**MS16-116：OLE Automation for VBScript Scripting Engine 的安全性更新 (3188724)**](https://go.microsoft.com/fwlink/?linkid=825725)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3375](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3375)

</td>
<td style="border:1px solid black;">
指令碼引擎資訊洩漏弱點

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
[**MS16-117：Adobe Flash Player 的安全性更新 (3188128)**](https://go.microsoft.com/fwlink/?linkid=825603)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-29](https://helpx.adobe.com/tw/security/products/flash-player/apsb16-29.html)

</td>
<td style="border:1px solid black;">
請參閱 Adobe 資訊安全公告 [APSB16-29](https://helpx.adobe.com/tw/security/products/flash-player/apsb16-29.html) 了解弱點嚴重性以及更新優先順序等級。

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
 

受影響的軟體
------------

下表依據主要的軟體類別和嚴重性依序列出公告。

請用這些表格來了解可能需要安裝的安全性更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的安全性更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。

**注意**：一項弱點，可能需要安裝數個安全性更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。

 

### Windows 作業系統及元件 (表格 1 之 2)

 
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
[**MS16-104**](https://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](https://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](https://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](https://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](https://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](https://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(3185319)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3175024)  
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
Internet Explorer 9   
(3185319)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3175024)  
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
[**MS16-104**](https://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](https://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](https://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](https://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](https://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](https://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**中度**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(3185319)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3175024)  
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
Internet Explorer 9  
(3185319)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3175024)  
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
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3175024)  
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
[**MS16-104**](https://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](https://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](https://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](https://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](https://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](https://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(3185319)  
(重大)

</td>
<td style="border:1px solid black;">
不適用                   

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3175024)  
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
Internet Explorer 11  
(3185319)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3175024)  
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
[**MS16-104**](https://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](https://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](https://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](https://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](https://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](https://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**中度**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(3185319)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3175024)  
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
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3175024)  
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
[**MS16-104**](https://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](https://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](https://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](https://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](https://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](https://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185319)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3184471)  
(重要)  
適用於 32 位元系統的 Windows 8.1  
(3187754)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3175024)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3178539)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185319)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3184471)  
(重要)  
適用於 x64 型系統的 Windows 8.1  
(3187754)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3175024)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3178539)  
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
[**MS16-104**](https://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](https://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](https://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](https://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](https://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](https://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**中度**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(3185319)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3175024)  
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
Internet Explorer 11   
(3185319)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3175024)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3178539)  
(重要)

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
[**MS16-104**](https://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](https://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](https://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](https://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](https://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](https://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185319)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3184471)  
(重要)  
Windows RT 8.1  
(3187754)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3175024)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3178539)  
(重要)

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
[**MS16-104**](https://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](https://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](https://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](https://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](https://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](https://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(3185611)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3185611)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3185611)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3185611)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3185611)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3185611)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(3185611)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3185611)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3185611)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3185611)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3185611)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3185611)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185614)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3185614)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3185614)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185614)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3185614)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3185614)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3189866)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3189866)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版  
(3189866)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版  
(3189866)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版  
(3189866)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版  
(3189866)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3189866)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3189866)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版  
(3189866)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版  
(3189866)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版  
(3189866)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版  
(3189866)  
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
適用於 32 位元系統的 Windows 10 1703 版  
(4025342)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

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
適用於 x64 型系統的 Windows 10 1703 版  
(4025342)  
(重要)

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
[**MS16-104**](https://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](https://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](https://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](https://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](https://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](https://go.microsoft.com/fwlink/?linkid=821605)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3175024)  
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
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3175024)  
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

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3175024)  
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
Windows Server 2012 (Server Core 安裝)  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3175024)  
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
Windows Server 2012  R2 (Server Core 安裝)  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  R2 (Server Core 安裝)  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  R2 (Server Core 安裝)  
(3175024)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  R2 (Server Core 安裝)  
(3178539)  
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
[**MS16-113**](https://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](https://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](https://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](https://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](https://go.microsoft.com/fwlink/?linkid=825603)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3184122)  
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
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3184122)  
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
[**MS16-113**](https://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](https://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](https://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](https://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](https://go.microsoft.com/fwlink/?linkid=825603)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**中度**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3184122)  
(中度)

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
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3184122)  
(中度)

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
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3184122)  
(中度)

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
[**MS16-113**](https://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](https://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](https://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](https://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](https://go.microsoft.com/fwlink/?linkid=825603)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

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
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3184122)  
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
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3184122)  
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
[**MS16-113**](https://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](https://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](https://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](https://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](https://go.microsoft.com/fwlink/?linkid=825603)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**中度**](https://go.microsoft.com/fwlink/?linkid=21140)

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
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3184122)  
(中度)

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
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3184122)  
(中度)

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
[**MS16-113**](https://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](https://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](https://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](https://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](https://go.microsoft.com/fwlink/?linkid=825603)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

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
適用於 32 位元系統的 Windows 8.1  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3184943)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3184122)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(3188128)  
(重大)

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
適用於 x64 型系統的 Windows 8.1  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3184943)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3184122)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3188128)  
(重大)

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
[**MS16-113**](https://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](https://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](https://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](https://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](https://go.microsoft.com/fwlink/?linkid=825603)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**中度**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**中度**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2012  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3184943)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3184122)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3188128)  
(中度)

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
Windows Server 2012 R2  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3184943)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3184122)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3188128)  
(中度)

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
[**MS16-113**](https://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](https://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](https://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](https://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](https://go.microsoft.com/fwlink/?linkid=825603)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3184943)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3184122)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3188128)  
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
[**MS16-113**](https://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](https://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](https://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](https://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](https://go.microsoft.com/fwlink/?linkid=825603)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3185611)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3185611)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3185611)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3185611)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10  
(3188128)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3185611)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3185611)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3185611)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3185611)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3188128)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3185614)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版  
(3188128)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3185614)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版  
(3188128)  
(重大)

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
適用於 32 位元系統的 Windows 10 1607 版  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版  
(3189866)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版  
(3189866)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版  
(3188128)  
(重大)

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
適用於 x64 型系統的 Windows 10 1607 版  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版  
(3189866)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版  
(3189866)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版  
(3188128)  
(重大)

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
不適用

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
[**MS16-113**](https://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](https://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](https://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](https://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](https://go.microsoft.com/fwlink/?linkid=825603)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**中度**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3184122)  
(中度)

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
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3184122)  
(中度)

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
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3184122)  
(中度)

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
Windows Server 2012 (Server Core 安裝)  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3184122)  
(中度)

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
Windows Server 2012 R2 (Server Core 安裝)  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3184122)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
</table>
 
 

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
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3118300)  
(重大)  
Microsoft Excel 2007 Service Pack 3  
(3115459)  
(重要)  
Microsoft Outlook 2007  
(3118303)  
(重要)  
Microsoft PowerPoint 2007 Service Pack 3  
(3114744)  
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
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(3118309)  
(重大)  
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(2553432)  
(重大)  
Microsoft Excel 2010 Service Pack 2 (32 位元版本)  
(3118316)  
(重要)  
Microsoft Outlook 2010 Service Pack 2 (32 位元版本)  
(3118313)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (32 位元版本)  
(3115467)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3118309)  
(重大)  
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(2553432)  
(重大)  
Microsoft Excel 2010 Service Pack 2 (64 位元版本)  
(3118316)  
(重要)  
Microsoft Outlook 2010 Service Pack 2 (64 位元版本)  
(3118313)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (64 位元版本)  
(3115467)  
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
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 位元版本)  
(3118268)  
(重大)  
Microsoft Office 2013 Service Pack 1 (32 位元版本)<sup>[1]</sup>
(重要)  
Microsoft Excel 2013 Service Pack 1 (32 位元版本)  
(3118284)  
(重要)  
Microsoft Outlook 2013 Service Pack 1 (32 位元版本)  
(3118280)  
(重要)  
Microsoft PowerPoint 2013 Service Pack 1 (32 位元版本)  
(3115487)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 位元版本)  
(3118268)  
(重大)  
Microsoft Office 2013 Service Pack 1 (64 位元版本)<sup>[1]</sup>
(重要)  
Microsoft Excel 2013 Service Pack 1 (64 位元版本)  
(3118284)  
(重要)  
Microsoft Outlook 2013 Service Pack 1 (64 位元版本)  
(3118280)  
(重要)  
Microsoft PowerPoint 2013 Service Pack 1 (64 位元版本)  
(3115487)  
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
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1  
(3118268)  
(重大)  
Microsoft Excel 2013 RT Service Pack 1  
(3118284)  
(重要)  
Microsoft Outlook 2013 RT Service Pack 1  
(3118280)  
(重要)  
Microsoft PowerPoint 2013 RT Service Pack 1  
(3115487)  
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
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2016 (32 位元版本)<sup>[1]</sup>
Microsoft Office 2016 (32 位元版本)  
(3118292)  
(重大)  
Microsoft Excel 2016 (32 位元版本)  
(3118290)  
(重要)  
Microsoft Outlook 2016 (32 位元版本)  
(3118293)  
(重要)  
Microsoft Visio 2016 (32 位元版本)  
(重要)<sup>[1]</sup>

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 位元版本)<sup>[1]</sup>
Microsoft Office 2016 (64 位元版本)  
(3118292)  
(重大)  
Microsoft Excel 2016 (64 位元版本)  
(3118290)  
(重要)  
Microsoft Outlook 2016 (64 位元版本)  
(3118293)  
(重要)  
Microsoft Visio 2016 (64 位元版本)  
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
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Word for Mac 2011  
(3186805)  
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
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 for Mac  
(3186807)  
(重要)  
Microsoft PowerPoint 2016 for Mac  
(3186807)  
(重要)  
Microsoft Word 2016 for Mac  
(3186807)  
(重大)  
Microsoft Outlook 2016 for Mac  
(3186807)  
(重要)

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
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack Service Pack 3  
(2597974)  
(重要)  
Microsoft Office Compatibility Pack Service Pack 3  
(3115462)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3115463)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer

</td>
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer  
(3054969)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3118297)  
(重大)

</td>
</tr>
</table>
 
<sup>[1]</sup>此項目參考僅適用於隨選即用 (C2R) 版本。

 

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
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Excel Services  
(3115112)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 位元版本)

</td>
<td style="border:1px solid black;">
Excel Services  
(3115112)  
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
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Excel Services  
(3115119)  
(重要)  
Word Automation Services  
(3115466)  
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
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1  
(3054862)  
(重大)  
Excel Automation Services  
(3115169)  
(重大)  
Word Automation Services  
(3115443)  
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
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3115472)  
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
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3118270)  
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
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Office Online Server

</td>
<td style="border:1px solid black;">
Office Online Server  
(3118299)  
(重要)

</td>
</tr>
</table>
 
 

### Microsoft 伺服器軟體

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-108**](https://go.microsoft.com/fwlink/?linkid=824829)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3  
(3184711)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-108**](https://go.microsoft.com/fwlink/?linkid=824829)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3  
(3184728)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-108**](https://go.microsoft.com/fwlink/?linkid=824829)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1  
(3184736)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累積更新 12

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累積更新 12  
(3184736)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累積更新 13

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累積更新 13  
(3184736)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS16-108**](https://go.microsoft.com/fwlink/?linkid=824829)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016 累積更新 1

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016 累積更新 1  
(3184736)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016 累積更新 2

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016 累積更新 2  
(3184736)  
(重要)

</td>
</tr>
</table>
 
### Microsoft 開發者工具和軟體

<p></p>
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
[**MS16-109**](https://go.microsoft.com/fwlink/?linkid=824768)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**                                                     

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
安裝於 Mac 上的 Microsoft Silverlight 5  
(3182373)  
(重要)  
安裝於 Mac 上的 Microsoft Silverlight 5 Developer Runtime  
(3182373)  
(重要)  
安裝於所有 Microsoft Windows 用戶端支援版本的 Microsoft Silverlight 5  
(3182373)  
(重要)  
安裝於所有 Microsoft Windows 用戶端支援版本的 Microsoft Silverlight 5 Developer Runtime  
(3182373)  
(重要)  
安裝於所有 Microsoft Windows 伺服器支援版本的 Microsoft Silverlight 5  
(3182373)  
(重要)

</td>
</tr>
</table>
 
 

偵測與部署工具及指南
--------------------

有幾項資源可協助系統管理員部署安全性更新。

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，查看是否遺漏安全性更新以及是否存在一般安全設定錯誤。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 可協助系統管理員發佈安全性更新。

應用程式相容性工具組隨附的 Update Compatibility Evaluator 元件可針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

如需上述工具以及其他可使用工具的詳細資訊，請參閱 [IT 專業人員的資訊安全工具](https://technet.microsoft.com/zh-tw/security/cc297183)。 

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
-   [過去幾個月發行的 Windows Server Update Services 更新](https://technet.microsoft.com/zh-tw/wsus/bb456965)。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的安全性保護，Microsoft 將在每月發行安全性更新之前，提前向重要安全性軟體提供者提供弱點資訊。安全性軟體提供者可利用此弱點資訊，透過其安全性軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](https://go.microsoft.com/fwlink/?linkid=215201) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

### 安全性策略與社群

**更新程式管理策略**

[更新管理資訊安全指南](https://go.microsoft.com/fwlink/?linkid=21168) (英文) 提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他資訊安全問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得，您也可以利用「安全性更新」(security update) 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 映像檔的方式，取得本月份 Windows Update 提供的資訊安全更新。如需更多資訊，請參閱 [Microsoft 知識庫文章 913086](https://support.microsoft.com/zh-tw/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全社群](https://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

### 支援

所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要了解您軟體版本的支援週期，請造訪 [Microsoft 支援週期](https://go.microsoft.com/fwlink/?linkid=21742)網站。

適用於 IT 專業人員的安全性解決方案：[TechNet 安全性疑難排解與支援](https://technet.microsoft.com/zh-tw/security/bb980617)

協助保護您執行 Windows 的電腦免於受到病毒和惡意程式碼攻擊：[病毒解決方案與安全性中心](https://support.microsoft.com/zh-tw/contactus/cu_sc_virsec_master)

根據您所在國家/地區的當地支援：[國際化支援](https://support.microsoft.com/zh-tw/common/international.aspx)

### 免責聲明

Microsoft 知識庫中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

### 修訂

-   V1.0 ([2016 年 9 月 13 日](https://technet.microsoft.com/zh-TW/library/bulletin+summary_publisheddate(v=Security.10)))：公告摘要發行。
-   V1.1 (2017 年 7 月 11 日)：針對 MS16-111，在「受影響的軟體」表格中新增適用於 32 位元系統的 Windows 10 1703 版和適用於 x64 型系統的 Windows 10 1703 版，因為它們也受到 CVE-2016-3305 的影響。Microsoft 建議執行 Windows 10 1703 版的客戶安裝更新 4025342，以取得保護，免受到此弱點侵害。

*頁面產生時間：2017 年 7 月 3 日 16:05-07:00。*
