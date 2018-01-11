---
TOCTitle: 'MS15-JUN'
Title: 2015 年 6 月 Microsoft 資訊安全公告摘要
ms:assetid: 'ms15-jun'
ms:contentKeyID: 65883235
ms:date: '06/09/2015'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms15-jun(v=Security.10)'
---

2015 年 6 月 Microsoft 資訊安全公告摘要
=======================================

發行日期：2015 年 6 月 9 日

**版本：** 1.0

此公告摘要列出 2015 年 6 月發行之資訊安全公告。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://technet.microsoft.com/zh-tw/security/dd252948.aspx)。

Microsoft 也會提供資訊協助客戶排定每月資訊安全更新以及任何非安全性更新的優先順序，其中這些非安全性更新的發行日期與每月安全性更新的發行日期相同。請參閱**＜其他資訊＞**一節。

提要
----

<span id="sectionToggle0"></span>
下表依嚴重性摘要說明本月份資訊安全公告。

如需受影響之軟體的詳細資料，請參閱下節**＜受影響的軟體＞**。

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
和弱點影響</strong></td>
<td style="border:1px solid black;"><strong>重新啟動需求</strong></td>
<td style="border:1px solid black;"><strong>已知<br />
問題</strong></td>
<td style="border:1px solid black;"><strong>受影響的軟體</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 積存安全性更新 (3058515)</strong> <br />
此安全性更新可解決 Internet Explorer 中的弱點。其中最嚴重的弱點，可能在使用者以 Internet Explorer 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用這些弱點的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614954">MS15-057</a></td>
<td style="border:1px solid black;"><strong>Windows Media Player 中的弱點可能會允許遠端執行程式碼 (3033890)</strong> <br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果 Windows Media Player 開啟位在惡意網站上的蓄意製作之媒體內容，此弱點可能允許遠端執行程式碼。成功利用此弱點的攻擊者可以從遠端取得受影響系統的完整控制權。設定為具有較少使用者權限的使用者帳戶所受到的影響，可能會比利用系統管理使用者權限進行操作的使用者帳戶小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614957">MS15-059</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 的弱點可能會允許遠端執行程式碼 (3064949)</strong> <br />
此安全性更新可解決 Microsoft Office 中的弱點。如果使用者開啟蓄意製作的 Microsoft Office 檔案，最嚴重的弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者，能以目前使用者的權限層級執行任意程式碼。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614958">MS15-060</a></td>
<td style="border:1px solid black;"><strong>Microsoft 通用控制項中的弱點可能會允許遠端執行程式碼 (3059317)</strong> <br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果使用者按一下蓄意製作的連結，或連結至蓄意製作的內容，然後在 Internet Explorer 中叫用 F12 開發工具，則此弱點可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614959">MS15-061</a></td>
<td style="border:1px solid black;"><strong>Windows 核心模式驅動程式的弱點可能會允許權限提高 (3057839)</strong> <br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者登入系統並執行蓄意製作的應用程式，則最嚴重的弱點可能會允許權限提高。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614960">MS15-062</a></td>
<td style="border:1px solid black;"><strong>Active Directory Federation Services 中的弱點可能會允許權限提高 (3062577)</strong> <br />
這個安全性更新可解決 Microsoft Active Directory Federation Services (AD FS) 中的弱點。如果攻擊者將蓄意製作的 URL 提交給目標網站，此弱點可能會允許權限提高。由於存在此弱點，因此在特定情況下，蓄意製作的指令碼並不會被正確清理，進而導致攻擊者提供的指令碼在檢視惡意內容的使用者資訊安全內容中執行。若為跨網站指令碼攻擊，使用者必須造訪受影響的網站，攻擊者才能利用此弱點執行任何惡意動作。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">不需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614961">MS15-063</a></td>
<td style="border:1px solid black;"><strong>Windows 核心中的弱點可能會允許權限提高 (3063858)</strong> <br />
此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者在電腦或網路共用的本機目錄中放置惡意的 .dll 檔案，此弱點可能會允許權限提高。攻擊者接著必須等待使用者執行程式來載入惡意的 .dll 檔案，從而導致權限提高。但在所有情況下，攻擊者並不能強迫使用者造訪這類網路共用或網站。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614962">MS15-064</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange Server 中的弱點可能會允許提高權限 (3062157)</strong> <br />
此安全性更新可解決 Microsoft Exchange Server 中的弱點。如果經驗證的使用者按一下連結以前往蓄意製作的網頁，則最嚴重者的弱點可能會允許權限提高。攻擊者並不能強迫使用者造訪網站，而是，攻擊者必須引誘使用者按一下連結，一般是藉助電子郵件的附件或 Instant Messenger 訊息。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">不需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Exchange Server</td>
</tr>
</tbody>
</table>
  
弱點入侵指數  
------------
  
<span id="sectionToggle1"></span>
下表提供本月所述每個弱點的利用性評估。會依序按公告編號及 CVE ID 的順序列出弱點。只會包含公告中嚴重性等級為「重大」或「重要」的弱點。
  
**我該如何使用這個表格？**
  
您可以運用此表格，針對您可能需要安裝的每一項安全性更新，瞭解弱點在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務 (DoS) 的可能性。請根據您特定的組態設定，檢閱下列各項評估，決定部署本月份更新的優先次序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](http://technet.microsoft.com/zh-tw/security/cc998259)。
  
在下方欄位中，「最新軟體版本」意指受影響軟體，「較舊軟體版本」意指受影響軟體所有較舊的支援版本，如公告中的「受影響的軟體」或「不受影響的軟體」表格裡所示。
  
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
<td style="border:1px solid black;"><strong>弱點標題</strong></td>
<td style="border:1px solid black;"><strong>CVE ID</strong></td>
<td style="border:1px solid black;"><strong>較早軟體版本的<br />
弱點評估</strong></td>
<td style="border:1px solid black;"><strong>較早軟體版本的<br />
弱點評估</strong></td>
<td style="border:1px solid black;"><strong>阻絕服務<br />
弱點評估</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1687">CVE-2015-1687</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1730">CVE-2015-1730</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1731">CVE-2015-1731</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1732">CVE-2015-1732</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1735">CVE-2015-1735</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1736">CVE-2015-1736</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1737">CVE-2015-1737</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1739">CVE-2015-1739</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1740">CVE-2015-1740</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1741">CVE-2015-1741</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1742">CVE-2015-1742</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1743">CVE-2015-1743</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1744">CVE-2015-1744</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1745">CVE-2015-1745</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1747">CVE-2015-1747</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1748">CVE-2015-1748</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1750">CVE-2015-1750</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1751">CVE-2015-1751</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1752">CVE-2015-1752</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1753">CVE-2015-1753</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1754">CVE-2015-1754</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1755">CVE-2015-1755</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 資訊洩漏弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1765">CVE-2015-1765</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1766">CVE-2015-1766</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614954">MS15-057</a></td>
<td style="border:1px solid black;">透過 DataObject 的 Windows Media Player RCE 弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1728">CVE-2015-1728</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614957">MS15-059</a></td>
<td style="border:1px solid black;">Microsoft Office 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1759">CVE-2015-1759</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614957">MS15-059</a></td>
<td style="border:1px solid black;">Microsoft Office 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1760">CVE-2015-1760</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614957">MS15-059</a></td>
<td style="border:1px solid black;">Microsoft Office 未初始化的記憶體使用弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1770">CVE-2015-1770</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614958">MS15-060</a></td>
<td style="border:1px solid black;">Microsoft 通用控制項釋放後使用弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1756">CVE-2015-1756</a></td>
<td style="border:1px solid black;">2 - 較可能遭到利用</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614959">MS15-061</a></td>
<td style="border:1px solid black;">Microsoft Windows 核心資訊洩露弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1719">CVE-2015-1719</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">永久</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614959">MS15-061</a></td>
<td style="border:1px solid black;">Microsoft Windows 核心釋放後使用弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1720">CVE-2015-1720</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614959">MS15-061</a></td>
<td style="border:1px solid black;">Win32k Null 指標解除參照弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1721">CVE-2015-1721</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614959">MS15-061</a></td>
<td style="border:1px solid black;">Microsoft Windows 核心點陣圖處理釋放後使用弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1722">CVE-2015-1722</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614959">MS15-061</a></td>
<td style="border:1px solid black;">Microsoft Windows 站釋放後使用弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1723">CVE-2015-1723</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614959">MS15-061</a></td>
<td style="border:1px solid black;">Microsoft Windows 核心物件釋放後使用弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1724">CVE-2015-1724</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614959">MS15-061</a></td>
<td style="border:1px solid black;">Win32k 緩衝區溢位弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1725">CVE-2015-1725</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614959">MS15-061</a></td>
<td style="border:1px solid black;">Microsoft Windows 核心 Brush 物件釋放後使用弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1726">CVE-2015-1726</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614959">MS15-061</a></td>
<td style="border:1px solid black;">Win32k 集區緩衝區溢位弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1727">CVE-2015-1727</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614959">MS15-061</a></td>
<td style="border:1px solid black;">Win32k 記憶體損毀權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1768">CVE-2015-1768</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614959">MS15-061</a></td>
<td style="border:1px solid black;">Win32k 權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2360">CVE-2015-2360</a></td>
<td style="border:1px solid black;">0 - 已偵測到利用</td>
<td style="border:1px solid black;">0 - 已偵測到利用</td>
<td style="border:1px solid black;">永久</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614960">MS15-062</a></td>
<td style="border:1px solid black;">ADFS XSS 權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1757">CVE-2015-1757</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614961">MS15-063</a></td>
<td style="border:1px solid black;">Windows LoadLibrary EoP 弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1758">CVE-2015-1758</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614962">MS15-064</a></td>
<td style="border:1px solid black;">Exchange Server 端要求偽造弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1764">CVE-2015-1764</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614962">MS15-064</a></td>
<td style="border:1px solid black;">Exchange 跨網站要求偽造弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1771">CVE-2015-1771</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=614962">MS15-064</a></td>
<td style="border:1px solid black;">Exchange HTML 導入弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2359">CVE-2015-2359</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
</tr>
</tbody>
</table>
  
受影響的軟體  
------------
  
<span id="sectionToggle2"></span>
下表依據主要的軟體類別和嚴重性依序列出公告。
  
請用這些表格來瞭解可能需要安裝的安全性更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的安全性更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。
  
**注意**：一項弱點，可能需要安裝數個資訊安全更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
### Windows 作業系統與元件

 
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
[**MS15-056**](http://go.microsoft.com/fwlink/?linkid=614953)

</td>
<td style="border:1px solid black;">
[**MS15-057**](http://go.microsoft.com/fwlink/?linkid=614954)

</td>
<td style="border:1px solid black;">
[**MS15-060**](http://go.microsoft.com/fwlink/?linkid=614958)

</td>
<td style="border:1px solid black;">
[**MS15-061**](http://go.microsoft.com/fwlink/?linkid=614959)

</td>
<td style="border:1px solid black;">
[**MS15-062**](http://go.microsoft.com/fwlink/?linkid=614960)

</td>
<td style="border:1px solid black;">
[**MS15-063**](http://go.microsoft.com/fwlink/?linkid=614961)

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
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3058515)  
(中度)  
Internet Explorer 7  
(3058515)  
(中度)  
Internet Explorer 8  
(3058515)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Media Player 10  
(3033890)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3057839)  
(重要)  
Windows Server 2003 R2 Service Pack 2  
(3057839)  
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
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3058515)  
(中度)  
Internet Explorer 7  
(3058515)  
(中度)  
Internet Explorer 8  
(3058515)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Media Player 10  
(3033890)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3057839)  
(重要)  
Windows Server 2003 R2 x64 Edition Service Pack 2  
(3057839)  
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
適用於 Itanium 型系統的 Windows Server 2003 SP2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3058515)  
(中度)  
Internet Explorer 7  
(3058515)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(3057839)  
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
<td style="border:1px solid black;" colspan="7">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-056**](http://go.microsoft.com/fwlink/?linkid=614953)

</td>
<td style="border:1px solid black;">
[**MS15-057**](http://go.microsoft.com/fwlink/?linkid=614954)

</td>
<td style="border:1px solid black;">
[**MS15-060**](http://go.microsoft.com/fwlink/?linkid=614958)

</td>
<td style="border:1px solid black;">
[**MS15-061**](http://go.microsoft.com/fwlink/?linkid=614959)

</td>
<td style="border:1px solid black;">
[**MS15-062**](http://go.microsoft.com/fwlink/?linkid=614960)

</td>
<td style="border:1px solid black;">
[**MS15-063**](http://go.microsoft.com/fwlink/?linkid=614961)

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
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3058515)  
(重大)  
Internet Explorer 8  
(3058515)  
(重大)  
Internet Explorer 9  
(3058515)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Media Player 11  
(3033890)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3059317)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3057839)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3063858)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3058515)  
(重大)  
Internet Explorer 8  
(3058515)  
(重大)  
Internet Explorer 9  
(3058515)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Media Player 11  
(3033890)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3059317)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3057839)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3063858)  
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
[**MS15-056**](http://go.microsoft.com/fwlink/?linkid=614953)

</td>
<td style="border:1px solid black;">
[**MS15-057**](http://go.microsoft.com/fwlink/?linkid=614954)

</td>
<td style="border:1px solid black;">
[**MS15-060**](http://go.microsoft.com/fwlink/?linkid=614958)

</td>
<td style="border:1px solid black;">
[**MS15-061**](http://go.microsoft.com/fwlink/?linkid=614959)

</td>
<td style="border:1px solid black;">
[**MS15-062**](http://go.microsoft.com/fwlink/?linkid=614960)

</td>
<td style="border:1px solid black;">
[**MS15-063**](http://go.microsoft.com/fwlink/?linkid=614961)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3058515)  
(中度)  
Internet Explorer 8  
(3058515)  
(中度)  
Internet Explorer 9  
(3058515)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Media Player 11  
(3033890)  
(重大)

</td>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2  
(3059317)  
(重要)

</td>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2  
(3057839)  
(重要)

</td>
<td style="border:1px solid black;">
Active Directory Federation Services 2.0  
(3062577)  
(重要)

</td>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2  
(3063858)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3058515)  
(中度)  
Internet Explorer 8  
(3058515)  
(中度)  
Internet Explorer 9  
(3058515)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Media Player 11  
(3033890)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3059317)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3057839)  
(重要)

</td>
<td style="border:1px solid black;">
Active Directory Federation Services 2.0  
(3062577)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3063858)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3058515)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2  
(3059317)  
(重要)

</td>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2  
(3057839)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2  
(3063858)  
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
[**MS15-056**](http://go.microsoft.com/fwlink/?linkid=614953)

</td>
<td style="border:1px solid black;">
[**MS15-057**](http://go.microsoft.com/fwlink/?linkid=614954)

</td>
<td style="border:1px solid black;">
[**MS15-060**](http://go.microsoft.com/fwlink/?linkid=614958)

</td>
<td style="border:1px solid black;">
[**MS15-061**](http://go.microsoft.com/fwlink/?linkid=614959)

</td>
<td style="border:1px solid black;">
[**MS15-062**](http://go.microsoft.com/fwlink/?linkid=614960)

</td>
<td style="border:1px solid black;">
[**MS15-063**](http://go.microsoft.com/fwlink/?linkid=614961)

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
Windows 7 32 位元系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3058515)  
(重大)  
Internet Explorer 9  
(3058515)  
(重大)  
Internet Explorer 10  
(3058515)  
(重大)  
Internet Explorer 11  
(3058515)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Media Player 12  
(3033890)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3059317)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3057839)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3063858)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3058515)  
(重大)  
Internet Explorer 9  
(3058515)  
(重大)  
Internet Explorer 10  
(3058515)  
(重大)  
Internet Explorer 11  
(3058515)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Media Player 12  
(3033890)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3059317)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3057839)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3063858)  
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
[**MS15-056**](http://go.microsoft.com/fwlink/?linkid=614953)

</td>
<td style="border:1px solid black;">
[**MS15-057**](http://go.microsoft.com/fwlink/?linkid=614954)

</td>
<td style="border:1px solid black;">
[**MS15-060**](http://go.microsoft.com/fwlink/?linkid=614958)

</td>
<td style="border:1px solid black;">
[**MS15-061**](http://go.microsoft.com/fwlink/?linkid=614959)

</td>
<td style="border:1px solid black;">
[**MS15-062**](http://go.microsoft.com/fwlink/?linkid=614960)

</td>
<td style="border:1px solid black;">
[**MS15-063**](http://go.microsoft.com/fwlink/?linkid=614961)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
Windows Server 2008 R2 x64 系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3058515)  
(中度)  
Internet Explorer 9  
(3058515)  
(中度)  
Internet Explorer 10  
(3058515)  
(中度)  
Internet Explorer 11  
(3058515)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Media Player 12  
(3033890)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3059317)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3057839)  
(重要)

</td>
<td style="border:1px solid black;">
Active Directory Federation Services 2.0  
(3062577)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3063858)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3058515)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3059317)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3057839)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3063858)  
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
[**MS15-056**](http://go.microsoft.com/fwlink/?linkid=614953)

</td>
<td style="border:1px solid black;">
[**MS15-057**](http://go.microsoft.com/fwlink/?linkid=614954)

</td>
<td style="border:1px solid black;">
[**MS15-060**](http://go.microsoft.com/fwlink/?linkid=614958)

</td>
<td style="border:1px solid black;">
[**MS15-061**](http://go.microsoft.com/fwlink/?linkid=614959)

</td>
<td style="border:1px solid black;">
[**MS15-062**](http://go.microsoft.com/fwlink/?linkid=614960)

</td>
<td style="border:1px solid black;">
[**MS15-063**](http://go.microsoft.com/fwlink/?linkid=614961)

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
Windows 8 32 位元系統

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3058515)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3059317)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3057839)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3063858)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 x64 系統

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3058515)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3059317)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3057839)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3063858)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3058515)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3059317)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3057839)  
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
Windows 8.1 x64 系統

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3058515)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3059317)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3057839)  
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
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-056**](http://go.microsoft.com/fwlink/?linkid=614953)

</td>
<td style="border:1px solid black;">
[**MS15-057**](http://go.microsoft.com/fwlink/?linkid=614954)

</td>
<td style="border:1px solid black;">
[**MS15-060**](http://go.microsoft.com/fwlink/?linkid=614958)

</td>
<td style="border:1px solid black;">
[**MS15-061**](http://go.microsoft.com/fwlink/?linkid=614959)

</td>
<td style="border:1px solid black;">
[**MS15-062**](http://go.microsoft.com/fwlink/?linkid=614960)

</td>
<td style="border:1px solid black;">
[**MS15-063**](http://go.microsoft.com/fwlink/?linkid=614961)

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
Internet Explorer 10  
(3058515)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3059317)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3057839)  
(重要)

</td>
<td style="border:1px solid black;">
Active Directory Federation Services 2.1  
(3062577)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3063858)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3058515)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3059317)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3057839)  
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
<td style="border:1px solid black;" colspan="7">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-056**](http://go.microsoft.com/fwlink/?linkid=614953)

</td>
<td style="border:1px solid black;">
[**MS15-057**](http://go.microsoft.com/fwlink/?linkid=614954)

</td>
<td style="border:1px solid black;">
[**MS15-060**](http://go.microsoft.com/fwlink/?linkid=614958)

</td>
<td style="border:1px solid black;">
[**MS15-061**](http://go.microsoft.com/fwlink/?linkid=614959)

</td>
<td style="border:1px solid black;">
[**MS15-062**](http://go.microsoft.com/fwlink/?linkid=614960)

</td>
<td style="border:1px solid black;">
[**MS15-063**](http://go.microsoft.com/fwlink/?linkid=614961)

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
Internet Explorer 10  
(3058515)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT  
(3059317)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3057839)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT  
(3063858)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3058515)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3059317)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3057839)  
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
<td style="border:1px solid black;" colspan="7">
**Server Core 安裝選項**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-056**](http://go.microsoft.com/fwlink/?linkid=614953)

</td>
<td style="border:1px solid black;">
[**MS15-057**](http://go.microsoft.com/fwlink/?linkid=614954)

</td>
<td style="border:1px solid black;">
[**MS15-060**](http://go.microsoft.com/fwlink/?linkid=614958)

</td>
<td style="border:1px solid black;">
[**MS15-061**](http://go.microsoft.com/fwlink/?linkid=614959)

</td>
<td style="border:1px solid black;">
[**MS15-062**](http://go.microsoft.com/fwlink/?linkid=614960)

</td>
<td style="border:1px solid black;">
[**MS15-063**](http://go.microsoft.com/fwlink/?linkid=614961)

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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3059317)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3057839)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3063858)  
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
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3059317)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3057839)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3063858)  
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
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3059317)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3057839)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3063858)  
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
(3059317)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3057839)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3063858)  
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
(3059317)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3057839)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
</table>
 
### Microsoft 伺服器軟體

 
<table style="border:1px solid black;">
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
[**MS15-064**](http://go.microsoft.com/fwlink/?linkid=614962)

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
Microsoft Exchange Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1  
(3062157)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 積存更新 8

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 積存更新 8  
(3062157)  
(重要)

</td>
</tr>
</table>
 
### Microsoft Office 套件及軟體

 
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
[**MS15-059**](http://go.microsoft.com/fwlink/?linkid=614957)

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
(2863812)  
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
[**MS15-059**](http://go.microsoft.com/fwlink/?linkid=614957)

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
Microsoft Office 2010 Service Pack 2 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(2863817)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(2863817)  
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
[**MS15-059**](http://go.microsoft.com/fwlink/?linkid=614957)

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
Microsoft Office 2013 Service Pack 1 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 位元版本)  
(3039749)  
(重要)  
Microsoft Office 2013 Service Pack 1 (32 位元版本)  
(3039782)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 位元版本)  
(3039749)  
(重要)  
Microsoft Office 2013 Service Pack 1 (64 位元版本)  
(3039782)  
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
[**MS15-059**](http://go.microsoft.com/fwlink/?linkid=614957)

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
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1  
(3039749)  
(重要)  
Microsoft Office 2013 RT Service Pack 1  
(3039782)  
(重要)

</td>
</tr>
</table>
 

偵測與部署工具及指南
--------------------

<span id="sectionToggle3"></span>
有幾項資源可協助系統管理員部署資訊安全更新。

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機與遠端系統是否有遺漏的安全性更新或常見的安全性錯誤設定。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 可協助系統管理員發佈安全性更新。

應用程式相容性工具組隨附的 Update Compatibility Evaluator 元件可針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

如需上述工具以及其他可使用工具的詳細資訊，請參閱 [IT 專業人員的資訊安全工具](http://technet.microsoft.com/zh-tw/security/cc297183)。

致謝
----

<span id="sectionToggle4"></span>
Microsoft 了解資訊安全業界所做的努力，其盡責地透露弱點來協助我們保護客戶。請參閱[致謝](https://technet.microsoft.com/zh-tw/library/security/dn903755.aspx) (英文) 以取得詳細資訊。

其他資訊
--------

<span id="sectionToggle5"></span>
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

[更新管理安全性指南](http://technet.microsoft.com/zh-tw/library/bb466251.aspx) (英文) 提供您有關套用資訊安全更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他資訊安全問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得，您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-tw) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的資訊安全更新。如需更多資訊，請參閱 [Microsoft 知識庫文章 913086](https://support.microsoft.com/zh-tw/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](http://technet.microsoft.com/zh-tw/security/cc136632.aspx)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

### 支援

所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](https://support.microsoft.com/zh-tw/lifecycle)。

適用於 IT 專業人員的安全性解決方案：[安全性疑難排解與支援](http://technet.microsoft.com/zh-tw/security/bb980617)

協助保護您執行 Windows 的電腦免於受到病毒和惡意程式碼攻擊：[病毒與安全性解決方案中心](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-tw)

根據您所在國家/地區的當地支援：[Micorsoft 技術支援](http://support.microsoft.com/common/international.aspx?ln=zh-tw)

### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

### 修訂

-   V1.0 (2015 年 6 月 9 日)：公告摘要發行。

*頁面產生時間：2015-06-08 11:03Z-07:00。*
