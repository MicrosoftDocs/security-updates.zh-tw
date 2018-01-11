---
TOCTitle: 'MS15-SEP'
Title: 2015 年 9 月份 Microsoft 安全性公告摘要
ms:assetid: 'ms15-sep'
ms:contentKeyID: 69933051
ms:date: '11/07/2015'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms15-sep(v=Security.10)'
---

2015 年 9 月份 Microsoft 安全性公告摘要
=======================================

發行日期：2015 年 9 月 8 日 | 更新日期：2015 年 11 月 10 日

**版本：** 4.0

此公告摘要列出 2015 年 9 月份所發行之資訊安全公告。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://technet.microsoft.com/zh-tw/security/dd252948.aspx)。

Microsoft 也會提供資訊協助客戶排定每月資訊安全更新以及任何非資訊安全更新的優先順序，其中這些非資訊安全更新的發行日期與每月資訊安全更新的發行日期相同。請參閱**＜其他資訊＞**一節。

提要
----

<span id="sectionToggle0"></span>
下表依嚴重性摘要說明本月份資訊安全公告。

如需受影響的軟體之詳細資料，請參閱下節＜**受影響的軟體**＞。

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
<td style="border:1px solid black;"><strong>公告編號</strong></td>
<td style="border:1px solid black;"><strong>公告標題與提要</strong></td>
<td style="border:1px solid black;"><strong>最高的嚴重性等級<br />
和弱點影響</strong></td>
<td style="border:1px solid black;"><strong>重新開機需求</strong></td>
<td style="border:1px solid black;"><strong>已知<br />
問題</strong></td>
<td style="border:1px solid black;"><strong>受影響的軟體</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-094">MS15-094</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 積存安全性更新 (3089548)</strong> <br />
此安全性更新可解決 Internet Explorer 中的弱點。其中最嚴重的弱點，可能在使用者以 Internet Explorer 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用這些弱點的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-095">MS15-095</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 的累積安全性更新 (3089665)<br />
</strong>此安全性更新可解決 Microsoft Edge 中的弱點。其中最嚴重的弱點，可能在使用者以 Internet Edge 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用這些弱點的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-096">MS15-096</a></td>
<td style="border:1px solid black;"><strong>Active Directory 服務中的弱點可能會允許阻斷服務 (DoS) (3072595)<br />
</strong>此安全性更新可解決 Active Directory 中的弱點。這項弱點可能會在通過驗證的攻擊者建立多個電腦帳戶時，允許阻斷服務。若要利用這項弱點，攻擊者必須擁有一個有權將電腦加入網域的帳戶。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要 </a><br />
阻斷服務 (DoS)</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-097">MS15-097</a></td>
<td style="border:1px solid black;"><strong>Microsoft 圖形元件中的弱點可能會允許遠端執行程式碼 (3089656)<br />
</strong>此安全性更新可解決 Microsoft Windows、Microsoft Office 和 Microsoft Lync 中的弱點。如果使用者開啟蓄意製作的文件，或是造訪內嵌 OpenType 字型的不受信任網頁，這些弱點中最嚴重者可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3086255">3086255</a><br />
<a href="https://support.microsoft.com/zh-tw/kb/3099414">3099414</a></td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Office、<br />
Microsoft Lync</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-098">MS15-098</a></td>
<td style="border:1px solid black;"><strong>Windows 筆記本中的弱點可能會允許遠端執行程式碼 (3089669)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。其中較嚴重的弱點，可能會在使用者開啟蓄意製作的筆記本檔案時，允許遠端執行程式碼。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-099">MS15-099</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 的弱點可能會允許遠端執行程式碼 (3089664)<br />
</strong>此安全性更新可解決 Microsoft Office 中的弱點。如果使用者開啟蓄意製作的 Microsoft Office 檔案，最嚴重的弱點可能會允許遠端執行程式碼。成功利用這些弱點的攻擊者，能以目前使用者的權限層級執行任意程式碼。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft SharePoint Foundation</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-100">MS15-100</a></td>
<td style="border:1px solid black;"><strong>Windows Media Center 中的弱點可能會允許遠端執行程式碼 (3087918)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果 Windows Media Center 開啟參考惡意程式碼的蓄意製作 Media Center 連結 (.mcl) 檔案，則此弱點可能會允許遠端執行程式碼。成功利用此弱點的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要 </a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-101">MS15-101</a></td>
<td style="border:1px solid black;"><strong>.NET Framework 中的弱點可能會允許權限提高 (3089662)<br />
</strong>這個安全性更新可解決 Microsoft .NET Framework 中的弱點。如果使用者執行蓄意製作的 .NET 應用程式，則這些弱點中最嚴重者可能會允許提高權限。不過，在所有情況下，攻擊者都無法強迫使用者執行應用程式，他們必須說服使用者。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要 </a><br />
權限提高</td>
<td style="border:1px solid black;">不需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-102">MS15-102</a></td>
<td style="border:1px solid black;"><strong>Windows 工作管理中的弱點可能會允許權限提高 (3089657)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者登入系統並執行蓄意製作的應用程式，則這些弱點可能允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要 </a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-103">MS15-103</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange Server 中的弱點可能會允許資訊洩漏 (3089250)<br />
</strong>此安全性更新可解決 Microsoft Exchange Server 中的弱點。這些弱點中最嚴重者會在 Outlook Web Access (OWA) 無法正確處理 Web 要求並清理使用者輸入和電子郵件內容時允許資訊洩漏。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要 </a><br />
資訊洩漏</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Exchange Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-104">MS15-104</a></td>
<td style="border:1px solid black;"><strong>商務用 Skype Server 和 Lync Server 中的弱點可能會允許權限提高 (3089952)<br />
</strong>此安全性更新可解決商務用 Skype Server 和 Microsoft Lync Server 中的弱點。如果使用者點選蓄意製作的 URL，則這些弱點中最嚴重者可能會允許權限提高。攻擊者必須說服使用者點選即時訊息或電子郵件中的連結，以透過蓄意製作的 URL 將使用者引導至受影響的網站。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要 </a><br />
權限提高</td>
<td style="border:1px solid black;">不需要重新開機</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-tw/kb/3080353">3080353</a></td>
<td style="border:1px solid black;">商務用 Skype Server、<br />
Microsoft Lync Server</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-105">MS15-105</a></td>
<td style="border:1px solid black;"><strong>Windows Hyper-V 中的弱點可能會允許資訊安全功能略過 (3091287)<br />
</strong>此安全性更新可解決 Microsoft Windows 中的弱點。如果攻擊者執行蓄意製作的應用程式，而讓 Windows Hyper-V 未能正確套用存取控制清單 (ACL) 組態設定，則此弱點可能會允許資訊安全功能略過。尚未啟用 Hyper-V 角色的客戶不會受到影響。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要 </a><br />
資訊安全功能略過</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
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
<td style="border:1px solid black;"><strong>公告編號</strong></td>
<td style="border:1px solid black;"><strong>弱點標題</strong></td>
<td style="border:1px solid black;"><strong>CVE ID</strong></td>
<td style="border:1px solid black;"><strong>較早軟體版本的<br />
弱點評估</strong></td>
<td style="border:1px solid black;"><strong>較早軟體版本的<br />
弱點評估</strong></td>
<td style="border:1px solid black;"><strong>阻斷服務<br />
弱點評估</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-094">MS15-094</a></td>
<td style="border:1px solid black;">資訊洩漏弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2483">CVE-2015-2483</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-094">MS15-094</a></td>
<td style="border:1px solid black;">竄改弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2484">CVE-2015-2484</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-094">MS15-094</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2485">CVE-2015-2485</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-094">MS15-094</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2486">CVE-2015-2486</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-094">MS15-094</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2487">CVE-2015-2487</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-094">MS15-094</a></td>
<td style="border:1px solid black;">權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2489">CVE-2015-2489</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-094">MS15-094</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2490">CVE-2015-2490</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-094">MS15-094</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2491">CVE-2015-2491</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-094">MS15-094</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2492">CVE-2015-2492</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-094">MS15-094</a></td>
<td style="border:1px solid black;">指令碼引擎記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2493">CVE-2015-2493</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-094">MS15-094</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2494">CVE-2015-2494</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-094">MS15-094</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2498">CVE-2015-2498</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-094">MS15-094</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2499">CVE-2015-2499</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-094">MS15-094</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2500">CVE-2015-2500</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-094">MS15-094</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2501">CVE-2015-2501</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-094">MS15-094</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2541">CVE-2015-2541</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-094">MS15-094</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2542">CVE-2015-2542</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-095">MS15-095</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2485">CVE-2015-2485</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-095">MS15-095</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2486">CVE-2015-2486</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-095">MS15-095</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2494">CVE-2015-2494</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-095">MS15-095</a></td>
<td style="border:1px solid black;">記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2542">CVE-2015-2542</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-096">MS15-096</a></td>
<td style="border:1px solid black;">Active Directory 阻斷服務弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2535">CVE-2015-2535</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-097">MS15-097</a></td>
<td style="border:1px solid black;">OpenType 字型剖析弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2506">CVE-2015-2506</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-097">MS15-097</a></td>
<td style="border:1px solid black;">字型驅動程式的權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2507">CVE-2015-2507</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-097">MS15-097</a></td>
<td style="border:1px solid black;">字型驅動程式的權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2508">CVE-2015-2508</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">暫時</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-097">MS15-097</a></td>
<td style="border:1px solid black;">圖形元件緩衝區溢位弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2510">CVE-2015-2510</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-097">MS15-097</a></td>
<td style="border:1px solid black;">Win32k 記憶體損毀權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2511">CVE-2015-2511</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-097">MS15-097</a></td>
<td style="border:1px solid black;">字型驅動程式的權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2512">CVE-2015-2512</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-097">MS15-097</a></td>
<td style="border:1px solid black;">Win32k 記憶體損毀權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2517">CVE-2015-2517</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-097">MS15-097</a></td>
<td style="border:1px solid black;">Win32k 記憶體損毀權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2518">CVE-2015-2518</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-097">MS15-097</a></td>
<td style="border:1px solid black;">Win32k 權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2527">CVE-2015-2527</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-097">MS15-097</a></td>
<td style="border:1px solid black;">核心 ASLR 略過弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2529">CVE-2015-2529</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-097">MS15-097</a></td>
<td style="border:1px solid black;">Win32k 記憶體損毀權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2546">CVE-2015-2546</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">0 - 已偵測到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-098">MS15-098</a></td>
<td style="border:1px solid black;">Windows 筆記本 RCE 弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2513">CVE-2015-2513</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-098">MS15-098</a></td>
<td style="border:1px solid black;">Windows 筆記本 DoS 弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2514">CVE-2015-2514</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-098">MS15-098</a></td>
<td style="border:1px solid black;">Windows 筆記本 DoS 弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2516">CVE-2015-2516</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-098">MS15-098</a></td>
<td style="border:1px solid black;">Windows 筆記本整數溢位 RCE 弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2519">CVE-2015-2519</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-098">MS15-098</a></td>
<td style="border:1px solid black;">Windows 筆記本 RCE 弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2530">CVE-2015-2530</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-099">MS15-099</a></td>
<td style="border:1px solid black;">Microsoft Office 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2520">CVE-2015-2520</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-099">MS15-099</a></td>
<td style="border:1px solid black;">Microsoft Office 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2521">CVE-2015-2521</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-099">MS15-099</a></td>
<td style="border:1px solid black;">Microsoft SharePoint XSS 偽造弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2522">CVE-2015-2522</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-099">MS15-099</a></td>
<td style="border:1px solid black;">Microsoft Office 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2523">CVE-2015-2523</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-099">MS15-099</a></td>
<td style="border:1px solid black;">Microsoft Office 中，EPS 檔案因格式錯誤所造成的弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2545">CVE-2015-2545</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">0 - 已偵測到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-100">MS15-100</a></td>
<td style="border:1px solid black;">Windows Media Center RCE 弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2509">CVE-2015-2509</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-101">MS15-101</a></td>
<td style="border:1px solid black;">.NET 權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2504">CVE-2015-2504</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-101">MS15-101</a></td>
<td style="border:1px solid black;">MVC 阻斷服務弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2526">CVE-2015-2526</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">暫時</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-102">MS15-102</a></td>
<td style="border:1px solid black;">Windows 工作管理權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2524">CVE-2015-2524</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-102">MS15-102</a></td>
<td style="border:1px solid black;">Windows 工作檔案刪除的權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2525">CVE-2015-2525</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-102">MS15-102</a></td>
<td style="border:1px solid black;">Windows 工作管理權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2528">CVE-2015-2528</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-103">MS15-103</a></td>
<td style="border:1px solid black;">Exchange 資訊洩漏弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2505">CVE-2015-2505</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-103">MS15-103</a></td>
<td style="border:1px solid black;">Exchange 偽造弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2543">CVE-2015-2543</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-103">MS15-103</a></td>
<td style="border:1px solid black;">Exchange 偽造弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2544">CVE-2015-2544</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-104">MS15-104</a></td>
<td style="border:1px solid black;">商務用 Skype Server 和 Lync Server 的 XSS 資訊洩漏弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2531">CVE-2015-2531</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-104">MS15-104</a></td>
<td style="border:1px solid black;">Lync Server XSS 資訊洩漏弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2532">CVE-2015-2532</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-104">MS15-104</a></td>
<td style="border:1px solid black;">商務用 Skype Server 和 Lync Server 的 XSS 權限提高弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2536">CVE-2015-2536</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/library/security/ms15-105">MS15-105</a></td>
<td style="border:1px solid black;">Hyper-V 資訊安全功能略過弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2534">CVE-2015-2534</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
</tr>
</tbody>
</table>
  
受影響的軟體  
------------
  
<span id="sectionToggle2"></span>
下表依據主要的軟體類別和嚴重性依序列出公告。
  
請用這些表格來瞭解可能需要安裝的資訊安全更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的資訊安全更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。
  
**注意**：一項弱點，可能需要安裝數個資訊安全更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
### Windows 作業系統及元件 (表格 2 之 1)

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-094**](https://technet.microsoft.com/zh-tw/library/security/ms15-094)

</td>
<td style="border:1px solid black;">
[**MS15-095**](https://technet.microsoft.com/zh-tw/library/security/ms15-095)

</td>
<td style="border:1px solid black;">
[**MS15-096**](https://technet.microsoft.com/zh-tw/library/security/ms15-096)

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-tw/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-098**](https://technet.microsoft.com/zh-tw/library/security/ms15-098)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087038)  
(重大)  
Internet Explorer 8  
(3087038)  
(重大)  
Internet Explorer 9  
(3087038)  
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
(3087039)  
(重要)  
Windows Vista Service Pack 2  
(3087135)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3069114)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087038)  
(重大)  
Internet Explorer 8  
(3087038)  
(重大)  
Internet Explorer 9  
(3087038)  
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
(3087039)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3087135)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3069114)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-094**](https://technet.microsoft.com/zh-tw/library/security/ms15-094)

</td>
<td style="border:1px solid black;">
[**MS15-095**](https://technet.microsoft.com/zh-tw/library/security/ms15-095)

</td>
<td style="border:1px solid black;">
[**MS15-096**](https://technet.microsoft.com/zh-tw/library/security/ms15-096)

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-tw/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-098**](https://technet.microsoft.com/zh-tw/library/security/ms15-098)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**普通**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087038)  
(中度)  
Internet Explorer 8  
(3087038)  
(中度)  
Internet Explorer 9  
(3087038)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3072595)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3087039)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3087135)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3069114)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087038)  
(中度)  
Internet Explorer 8  
(3087038)  
(中度)  
Internet Explorer 9  
(3087038)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3072595)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3087039)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3087135)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3069114)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087038)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3072595)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3087039)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3087135)  
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
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-094**](https://technet.microsoft.com/zh-tw/library/security/ms15-094)

</td>
<td style="border:1px solid black;">
[**MS15-095**](https://technet.microsoft.com/zh-tw/library/security/ms15-095)

</td>
<td style="border:1px solid black;">
[**MS15-096**](https://technet.microsoft.com/zh-tw/library/security/ms15-096)

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-tw/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-098**](https://technet.microsoft.com/zh-tw/library/security/ms15-098)

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
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3087038)  
(重大)  
Internet Explorer 9  
(3087038)  
(重大)  
Internet Explorer 10  
(3087038)  
(重大)  
Internet Explorer 11  
(3087038)  
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
(3087039)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3069114)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3087038)  
(重大)  
Internet Explorer 9  
(3087038)  
(重大)  
Internet Explorer 10  
(3087038)  
(重大)  
Internet Explorer 11  
(3087038)  
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
(3087039)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3069114)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-094**](https://technet.microsoft.com/zh-tw/library/security/ms15-094)

</td>
<td style="border:1px solid black;">
[**MS15-095**](https://technet.microsoft.com/zh-tw/library/security/ms15-095)

</td>
<td style="border:1px solid black;">
[**MS15-096**](https://technet.microsoft.com/zh-tw/library/security/ms15-096)

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-tw/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-098**](https://technet.microsoft.com/zh-tw/library/security/ms15-098)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**普通**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3087038)  
(中度)  
Internet Explorer 9  
(3087038)  
(中度)  
Internet Explorer 10  
(3087038)  
(中度)  
Internet Explorer 11  
(3087038)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3072595)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3087039)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3069114)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3087038)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3072595)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3087039)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-094**](https://technet.microsoft.com/zh-tw/library/security/ms15-094)

</td>
<td style="border:1px solid black;">
[**MS15-095**](https://technet.microsoft.com/zh-tw/library/security/ms15-095)

</td>
<td style="border:1px solid black;">
[**MS15-096**](https://technet.microsoft.com/zh-tw/library/security/ms15-096)

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-tw/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-098**](https://technet.microsoft.com/zh-tw/library/security/ms15-098)

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
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 32 位元系統

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3087038)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3087039)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3069114)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3087038)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(3087039)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(3069114)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3087038)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3087039)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3069114)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3087038)  
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
(3087039)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3069114)  
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
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-094**](https://technet.microsoft.com/zh-tw/library/security/ms15-094)

</td>
<td style="border:1px solid black;">
[**MS15-095**](https://technet.microsoft.com/zh-tw/library/security/ms15-095)

</td>
<td style="border:1px solid black;">
[**MS15-096**](https://technet.microsoft.com/zh-tw/library/security/ms15-096)

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-tw/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-098**](https://technet.microsoft.com/zh-tw/library/security/ms15-098)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**普通**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3087038)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3072595)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3087039)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3069114)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3087038)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3072595)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3087039)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3069114)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-094**](https://technet.microsoft.com/zh-tw/library/security/ms15-094)

</td>
<td style="border:1px solid black;">
[**MS15-095**](https://technet.microsoft.com/zh-tw/library/security/ms15-095)

</td>
<td style="border:1px solid black;">
[**MS15-096**](https://technet.microsoft.com/zh-tw/library/security/ms15-096)

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-tw/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-098**](https://technet.microsoft.com/zh-tw/library/security/ms15-098)

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
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3087038)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT  
(3087039)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3069114)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3087038)  
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
(3087039)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3069114)  
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
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-094**](https://technet.microsoft.com/zh-tw/library/security/ms15-094)

</td>
<td style="border:1px solid black;">
[**MS15-095**](https://technet.microsoft.com/zh-tw/library/security/ms15-095)

</td>
<td style="border:1px solid black;">
[**MS15-096**](https://technet.microsoft.com/zh-tw/library/security/ms15-096)

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-tw/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-098**](https://technet.microsoft.com/zh-tw/library/security/ms15-098)

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
**無**

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
Windows 10 32 位元系統

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3081455)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3081455)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 10 32 位元系統  
(3081455)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 32 位元系統  
(3081455)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3081455)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3081455)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3081455)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3081455)  
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
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-094**](https://technet.microsoft.com/zh-tw/library/security/ms15-094)

</td>
<td style="border:1px solid black;">
[**MS15-095**](https://technet.microsoft.com/zh-tw/library/security/ms15-095)

</td>
<td style="border:1px solid black;">
[**MS15-096**](https://technet.microsoft.com/zh-tw/library/security/ms15-096)

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-tw/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-098**](https://technet.microsoft.com/zh-tw/library/security/ms15-098)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3072595)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3087039)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3087135)  
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
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3072595)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3087039)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3087135)  
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
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)  
(3072595)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)  
(3087039)  
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
Windows Server 2012  
(Server Core 安裝)  
(3072595)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)  
(3087039)  
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
(3072595)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)  
(3087039)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
</table>
 
**MS15-097 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

### Windows 作業系統及元件 (表格 2 之 2)

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-100**](https://technet.microsoft.com/zh-tw/library/security/ms15-100)

</td>
<td style="border:1px solid black;">
[**MS15-101**](https://technet.microsoft.com/zh-tw/library/security/ms15-101)

</td>
<td style="border:1px solid black;">
[**MS15-102**](https://technet.microsoft.com/zh-tw/library/security/ms15-102)

</td>
<td style="border:1px solid black;">
[**MS15-105**](https://technet.microsoft.com/zh-tw/library/security/ms15-105)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3087918)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3074541)  
(重要)  
Microsoft .NET Framework 4  
(3074547)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074550)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074230)  
(重要)  
Microsoft .NET Framework 4.6  
(3074554)  
(重要)  
Microsoft .NET Framework 4.6  
(3074233)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3084135)  
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
Windows Media Center  
(3087918)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3074541)  
(重要)  
Microsoft .NET Framework 4  
(3074547)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074550)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074230)  
(重要)  
Microsoft .NET Framework 4.6  
(3074554)  
(重要)  
Microsoft .NET Framework 4.6  
(3074233)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3084135)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-100**](https://technet.microsoft.com/zh-tw/library/security/ms15-100)

</td>
<td style="border:1px solid black;">
[**MS15-101**](https://technet.microsoft.com/zh-tw/library/security/ms15-101)

</td>
<td style="border:1px solid black;">
[**MS15-102**](https://technet.microsoft.com/zh-tw/library/security/ms15-102)

</td>
<td style="border:1px solid black;">
[**MS15-105**](https://technet.microsoft.com/zh-tw/library/security/ms15-105)

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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3074541)  
(重要)  
Microsoft .NET Framework 4  
(3074547)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074550)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074230)  
(重要)  
Microsoft .NET Framework 4.6  
(3074554)  
(重要)  
Microsoft .NET Framework 4.6  
(3074233)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(3084135)  
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
Microsoft .NET Framework 2.0 Service Pack 2  
(3074541)  
(重要)  
Microsoft .NET Framework 4  
(3074547)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074550)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074230)  
(重要)  
Microsoft .NET Framework 4.6  
(3074554)  
(重要)  
Microsoft .NET Framework 4.6  
(3074233)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3084135)  
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
Microsoft .NET Framework 2.0 Service Pack 2  
(3074541)  
(重要)  
Microsoft .NET Framework 4  
(3074547)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(3084135)  
(重要)

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
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-100**](https://technet.microsoft.com/zh-tw/library/security/ms15-100)

</td>
<td style="border:1px solid black;">
[**MS15-101**](https://technet.microsoft.com/zh-tw/library/security/ms15-101)

</td>
<td style="border:1px solid black;">
[**MS15-102**](https://technet.microsoft.com/zh-tw/library/security/ms15-102)

</td>
<td style="border:1px solid black;">
[**MS15-105**](https://technet.microsoft.com/zh-tw/library/security/ms15-105)

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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3087918)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3074543)  
(重要)  
Microsoft .NET Framework 4  
(3074547)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074550)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074230)  
(重要)  
Microsoft .NET Framework 4.6  
(3074554)  
(重要)  
Microsoft .NET Framework 4.6  
(3074233)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(3084135)  
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
Windows Media Center  
(3087918)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3074543)  
(重要)  
Microsoft .NET Framework 4  
(3074547)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074550)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074230)  
(重要)  
Microsoft .NET Framework 4.6  
(3074554)  
(重要)  
Microsoft .NET Framework 4.6  
(3074233)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(3084135)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-100**](https://technet.microsoft.com/zh-tw/library/security/ms15-100)

</td>
<td style="border:1px solid black;">
[**MS15-101**](https://technet.microsoft.com/zh-tw/library/security/ms15-101)

</td>
<td style="border:1px solid black;">
[**MS15-102**](https://technet.microsoft.com/zh-tw/library/security/ms15-102)

</td>
<td style="border:1px solid black;">
[**MS15-105**](https://technet.microsoft.com/zh-tw/library/security/ms15-105)

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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3074543)  
(重要)  
Microsoft .NET Framework 4  
(3074547)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074550)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074230)  
(重要)  
Microsoft .NET Framework 4.6  
(3074554)  
(重要)  
Microsoft .NET Framework 4.6  
(3074233)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(3084135)  
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
Microsoft .NET Framework 3.5.1  
(3074543)  
(重要)  
Microsoft .NET Framework 4  
(3074547)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3084135)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-100**](https://technet.microsoft.com/zh-tw/library/security/ms15-100)

</td>
<td style="border:1px solid black;">
[**MS15-101**](https://technet.microsoft.com/zh-tw/library/security/ms15-101)

</td>
<td style="border:1px solid black;">
[**MS15-102**](https://technet.microsoft.com/zh-tw/library/security/ms15-102)

</td>
<td style="border:1px solid black;">
[**MS15-105**](https://technet.microsoft.com/zh-tw/library/security/ms15-105)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 32 位元系統

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3087918)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3074544)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074229)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074549)  
(重要)  
Microsoft .NET Framework 4.6  
(3074552)  
(重要)  
Microsoft .NET Framework 4.6  
(3074231)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3082089)  
(重要)  
Windows 8 32 位元系統  
(3084135)  
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
Windows Media Center  
(3087918)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3074544)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074229)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074549)  
(重要)  
Microsoft .NET Framework 4.6  
(3074552)  
(重要)  
Microsoft .NET Framework 4.6  
(3074231)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(3082089)  
(重要)  
適用於 x64 型系統的 Windows 8  
(3084135)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3087918)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3074545)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3074548)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3074228)  
(重要)  
Microsoft .NET Framework 4.6  
(3074553)  
(重要)  
Microsoft .NET Framework 4.6  
(3074232)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3082089)  
(重要)  
Windows 8.1 32 位元系統  
(3084135)  
(重要)

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
Windows Media Center  
(3087918)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3074545)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3074548)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3074228)  
(重要)  
Microsoft .NET Framework 4.6  
(3074553)  
(重要)  
Microsoft .NET Framework 4.6  
(3074232)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3082089)  
(重要)  
適用於 x64 型系統的 Windows 8.1  
(3084135)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(3087088)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-100**](https://technet.microsoft.com/zh-tw/library/security/ms15-100)

</td>
<td style="border:1px solid black;">
[**MS15-101**](https://technet.microsoft.com/zh-tw/library/security/ms15-101)

</td>
<td style="border:1px solid black;">
[**MS15-102**](https://technet.microsoft.com/zh-tw/library/security/ms15-102)

</td>
<td style="border:1px solid black;">
[**MS15-105**](https://technet.microsoft.com/zh-tw/library/security/ms15-105)

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
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
Microsoft .NET Framework 3.5  
(3074544)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074229)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074549)  
(重要)  
Microsoft .NET Framework 4.6  
(3074552)  
(重要)  
Microsoft .NET Framework 4.6  
(3074231)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3082089)  
(重要)  
Windows Server 2012  
(3084135)  
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
Microsoft .NET Framework 3.5  
(3074545)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3074548)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3074228)  
(重要)  
Microsoft .NET Framework 4.6  
(3074553)  
(重要)  
Microsoft .NET Framework 4.6  
(3074232)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3082089)  
(重要)  
Windows Server 2012 R2  
(3084135)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3087088)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-100**](https://technet.microsoft.com/zh-tw/library/security/ms15-100)

</td>
<td style="border:1px solid black;">
[**MS15-101**](https://technet.microsoft.com/zh-tw/library/security/ms15-101)

</td>
<td style="border:1px solid black;">
[**MS15-102**](https://technet.microsoft.com/zh-tw/library/security/ms15-102)

</td>
<td style="border:1px solid black;">
[**MS15-105**](https://technet.microsoft.com/zh-tw/library/security/ms15-105)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074229)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074549)  
(重要)  
Microsoft .NET Framework 4.6  
(3074231)  
(重要)  
Microsoft .NET Framework 4.6  
(3074552)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3082089)  
(重要)  
Windows RT  
(3084135)  
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
Microsoft .NET Framework 4.5.1/4.5.2  
(3074548)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3074228)  
(重要)  
Microsoft .NET Framework 4.6  
(3074232)  
(重要)  
Microsoft .NET Framework 4.6  
(3074553)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3082089)  
(重要)  
Windows RT 8.1  
(3084135)  
(重要)

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
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-100**](https://technet.microsoft.com/zh-tw/library/security/ms15-100)

</td>
<td style="border:1px solid black;">
[**MS15-101**](https://technet.microsoft.com/zh-tw/library/security/ms15-101)

</td>
<td style="border:1px solid black;">
[**MS15-102**](https://technet.microsoft.com/zh-tw/library/security/ms15-102)

</td>
<td style="border:1px solid black;">
[**MS15-105**](https://technet.microsoft.com/zh-tw/library/security/ms15-105)

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
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 32 位元系統

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3081455)  
(重要)  
Microsoft .NET Framework 4.6  
(3081455)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 32 位元系統  
(3081455)  
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
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3081455)  
(重要)  
Microsoft .NET Framework 4.6  
(3081455)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3081455)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10  
(3081455)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Server Core 安裝選項**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-100**](https://technet.microsoft.com/zh-tw/library/security/ms15-100)

</td>
<td style="border:1px solid black;">
[**MS15-101**](https://technet.microsoft.com/zh-tw/library/security/ms15-101)

</td>
<td style="border:1px solid black;">
[**MS15-102**](https://technet.microsoft.com/zh-tw/library/security/ms15-102)

</td>
<td style="border:1px solid black;">
[**MS15-105**](https://technet.microsoft.com/zh-tw/library/security/ms15-105)

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
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3084135)  
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
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(Server Core 安裝)  
(3084135)  
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
Microsoft .NET Framework 3.5.1  
(3074543)  
(重要)  
Microsoft .NET Framework 4  
(3074547)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074550)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074230)  
(重要)  
Microsoft .NET Framework 4.6  
(3074554)  
(重要)  
Microsoft .NET Framework 4.6  
(3074233)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(Server Core 安裝)  
(3084135)  
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
Microsoft .NET Framework 3.5  
(3074544)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074229)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074549)  
(重要)  
Microsoft .NET Framework 4.6  
(3074552)  
(重要)  
Microsoft .NET Framework 4.6  
(3074231)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 安裝)  
(3082089)  
(重要)  
Windows Server 2012  
(Server Core 安裝)  
(3084135)  
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
Microsoft .NET Framework 3.5  
(3074545)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3074548)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3074228)  
(重要)  
Microsoft .NET Framework 4.6  
(3074553)  
(重要)  
Microsoft .NET Framework 4.6  
(3074232)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)  
(3082089)  
(重要)  
Windows Server 2012 R2  
(Server Core 安裝)  
(3084135)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 安裝)  
(3087088)  
(重要)

</td>
</tr>
</table>
 
### Microsoft 伺服器軟體

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Foundation 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-099**](https://technet.microsoft.com/zh-tw/library/security/ms15-099)

</td>
<td style="border:1px solid black;">
[**MS15-103**](https://technet.microsoft.com/zh-tw/library/security/ms15-103)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1  
(3085501)  
(重要)

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
Microsoft Exchange Server 2013

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 積存更新 8  
(3089250)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 積存更新 9  
(3089250)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1  
(3089250)  
(重要)

</td>
</tr>
</table>
 
**MS15-099 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

### Microsoft Office 套件及軟體

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-tw/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-099**](https://technet.microsoft.com/zh-tw/library/security/ms15-099)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3085546)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3085620)  
(重大)  
Microsoft Excel 2007 Service Pack 3  
(3085543)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-tw/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-099**](https://technet.microsoft.com/zh-tw/library/security/ms15-099)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(3085529)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(3085560)  
(重大)  
Microsoft Excel 2010 Service Pack 2 (32 位元版本)  
(3085526)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3085529)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(3085560)  
(重大)  
Microsoft Excel 2010 Service Pack 2 (64 位元版本)  
(3085526)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-tw/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-099**](https://technet.microsoft.com/zh-tw/library/security/ms15-099)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
Microsoft Office 2013 Service Pack 1 (32 位元版本)  
(3085572)  
(重大)  
Microsoft Excel 2013 Service Pack 1 (32 位元版本)  
(3085502)  
(重要)

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
Microsoft Office Service Pack 1 (64 位元版本)  
(3085572)  
(重大)  
Microsoft Excel 2013 Service Pack 1 (64 位元版本)  
(3085502)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-tw/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-099**](https://technet.microsoft.com/zh-tw/library/security/ms15-099)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
Microsoft Office 2013 RT Service Pack 1 (32 位元版本)  
(3085572)  
(重大)  
Microsoft Excel 2013 RT Service Pack 1  
(3085502)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-tw/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-099**](https://technet.microsoft.com/zh-tw/library/security/ms15-099)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
Microsoft Office 2016 (32 位元版本)  
(3085635)  
(重大)  
Microsoft Excel 2016 (32 位元版本)  
(2920693)  
(重要)

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
Microsoft Office 2016 (64 位元版本)  
(3085635)  
(重大)  
Microsoft Excel 2016 (64 位元版本)  
(2920693)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-tw/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-099**](https://technet.microsoft.com/zh-tw/library/security/ms15-099)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Excel for Mac 2011  
(3088501)  
(重要)

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
Microsoft Excel 2016 for Mac  
(3088502)  
重要

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**其他 Office 軟體**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-tw/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-099**](https://technet.microsoft.com/zh-tw/library/security/ms15-099)

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
(3054993)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3054995)  
(重要)

</td>
</tr>
</table>
 
**MS15-097 和 MS15-099 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

### Microsoft 通訊平台和軟體

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Live Meeting 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-tw/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-104**](https://technet.microsoft.com/zh-tw/library/security/ms15-104)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console

</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console  
(3081090)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Lync 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-tw/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-104**](https://technet.microsoft.com/zh-tw/library/security/ms15-104)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 位元)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 位元)  
(3081087)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 位元)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 位元)  
(3081087)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

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
(3081088)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

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
(3081089)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Lync 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-tw/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-104**](https://technet.microsoft.com/zh-tw/library/security/ms15-104)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (32 位元)  
(商務用 Skype)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (32 位元)  
(商務用 Skype)  
(3085500)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (32 位元)  
(商務用 Skype 基本版)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (32 位元)  
(商務用 Skype 基本版)  
(3085500)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

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
(3085500)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (64 位元)  
(商務用 Skype 基本版)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (64 位元)  
(商務用 Skype 基本版)  
(3085500)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**商務用 Skype 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-tw/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-104**](https://technet.microsoft.com/zh-tw/library/security/ms15-104)

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
</tr>
<tr>
<td style="border:1px solid black;">
商務用 Skype 2016 (32 位元)

</td>
<td style="border:1px solid black;">
商務用 Skype 2016 (32 位元)  
(2910994)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
商務用 Skype 2016 (64 位元)

</td>
<td style="border:1px solid black;">
商務用 Skype 2016 (64 位元)  
(2910994)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Lync Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-tw/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-104**](https://technet.microsoft.com/zh-tw/library/security/ms15-104)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Server 2013  
(Web 元件伺服器)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft Lync Server 2013  
(Web 元件伺服器)  
(3080353)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**商務用 Skype Server 2015**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號                                                 **

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-tw/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-104**](https://technet.microsoft.com/zh-tw/library/security/ms15-104)

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
</tr>
<tr>
<td style="border:1px solid black;">
商務用 Skype Server 2015

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
商務用 Skype Server 2015  
(3061064)  
(重要)

</td>
</tr>
</table>
 
**MS15-097 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

偵測與部署工具及指南
--------------------

<span id="sectionToggle3"></span>
有幾項資源可協助系統管理員部署資訊安全更新。

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，查看是否遺漏資訊安全更新及一般資訊安全設定錯誤的狀況。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 可協助系統管理員散佈資訊安全更新。

應用程式相容性工具組隨附的 Update Compatibility Evaluator 元件可針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

如需上述工具以及其他可使用工具的詳細資訊，請參閱 [IT 專業人員的資訊安全工具](http://technet.microsoft.com/zh-tw/security/cc297183)。

感謝
----

<span id="sectionToggle4"></span>
Microsoft 了解資訊安全業界所做的努力，其盡責地透露弱點來協助我們保護客戶。請參閱[致謝](https://technet.microsoft.com/zh-tw/library/security/dn903755.aspx) (英文) 以取得詳細資訊。

其他資訊
--------

<span id="sectionToggle5"></span>
### Microsoft Windows 惡意軟體移除工具 (英文)

針對每個月第二個星期二發行的公告，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 及下載中心發行更新版本的 Microsoft Windows 惡意軟體移除工具。不定期資訊安全公告發行不提供更新版本的 Microsoft Windows 惡意軟體移除工具。

### MU、WU 及 WSUS 上的非資訊安全更新

如需在 Windows Update 和 Microsoft Update 上發行的非資訊安全更新之相關資訊，請參閱：

-   [Microsoft 知識庫文章 894199](https://support.microsoft.com/zh-tw/kb/894199)：Software Update Services 與 Windows Server Update Services 的說明內容有所變動。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](http://technet.microsoft.com/zh-tw/windowsserver/bb332157.aspx)。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的資訊安全保護，Microsoft 將在每月發行安全性更新之前，提前向重要資訊安全軟體提供者提供弱點資訊。資訊安全軟體提供者可利用此弱點，透過其資訊安全軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://technet.microsoft.com/zh-tw/security/dn467918) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

### 安全性策略與社群

**更新程式管理策略**

[更新管理資訊安全指南](http://technet.microsoft.com/zh-tw/library/bb466251.aspx) (英文) 提供您有關套用資訊安全更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他資訊安全更新**

其他資訊安全問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得，您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-tw) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](https://support.microsoft.com/zh-tw/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](http://technet.microsoft.com/zh-tw/security/cc136632.aspx)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

### 支援

所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](https://support.microsoft.com/zh-tw/lifecycle)。

IT 專業人員的資訊安全解決方案：[TechNet 資訊安全疑難排解與支援](http://technet.microsoft.com/zh-tw/security/bb980617)

協助保護您的 Widows 電腦免於病毒和惡意軟體攻擊：[病毒解決方案與資訊安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-tw)

您所在國家/地區的當地支援：[國際支援](http://support.microsoft.com/common/international.aspx?ln=zh-tw)

### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

### 版本

-   V1.0 (2015 年 9 月 8 日)：公告摘要發行。
-   V1.1 (2015 年 9 月 8 日)：MS15-097 已為 CVE-2015-2506 修改了「弱點入侵指數」的安全風險評估。這項變更僅屬資訊上的變更。
-   V1.2 (2015 年 9 月 9 日)：MS15-097 已為 CVE-2015-2506 修改了「弱點入侵指數」的安全風險評估，而 MS15-099 則是為 CVE-2015-2545 的相同評估進行了修改。這些變更均只屬於資訊上變更。
-   V1.3 (2015 年 9 月 23 日)：修訂公告摘要，以更正「弱點入侵指數」中 CVE-2015-2514 的標題。這只是資訊的變更。如果客戶已成功安裝可解決此問題的更新，則不必採取任何行動。
-   V1.4 (2015 年 9 月 25 日)：MS15-099 已為 Microsoft Office 2016 for Mac 新增了更新 3088502，自 2015 年 9 月 15 日起已可開始取得。如需詳細資訊，請參閱 [Microsoft 知識庫文章 3088502](https://support.microsoft.com/zh-tw/kb/3088502)。
-   V2.0 (2015 年 9 月 30 日)：修訂公告摘要，宣佈 MS15-097 中的 Microsoft Office 2016 和 MS15-099 中的商務用 Skype 2016 的更新套件已可使用。執行 Microsoft Office 2016 或商務用 Skype 2016 的客戶應套用更新以防止受到本公告討論的弱點影響。大部分客戶都已啟用自動更新，不必採取任何行動，因為系統會自動下載和安裝適用的更新。
-   V3.0 (2015 年 10 月 13 日)：對於 MS15-099，修訂公告摘要，宣佈 Microsoft Excel 2016 的更新套件已可使用。執行 Microsoft Excel 2016 的客戶應套用更新 2920693 以防止受到 MS15-099 討論的弱點影響。大部分客戶都已啟用自動更新，因此不必採取任何行動，因為系統會自動下載和安裝更新。
-   V4.0 (2015 年 11 月 10 日)：對於 MS15-099，為了完全解決 CVE-2015-2545，Microsoft 重新發行所有受影響的 Microsoft Office 軟體適用的安全性更新。Microsoft 建議執行受影響 Microsoft Office 軟體版本的客戶應安裝與此公告修訂一起發行的安全性更新，才能徹底不受此弱點影響。執行其他 Microsoft Office 軟體的客戶不需要採取任何動作。請參閱 [MS15-099](https://technet.microsoft.com/zh-tw/library/security/ms15-099) 的下載連結，如需詳細資訊，請參閱 [Microsoft 知識庫文章 3089664](https://support.microsoft.com/zh-tw/kb/3089664)。

*頁面產生時間：2015/11/2 16:26:00-08:00。*
