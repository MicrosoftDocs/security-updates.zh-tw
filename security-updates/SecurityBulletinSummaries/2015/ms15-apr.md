---
TOCTitle: 'MS15-APR'
Title: 2015 年 4 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms15-apr'
ms:contentKeyID: 65308595
ms:date: '04/16/2015'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms15-apr(v=Security.10)'
---

2015 年 4 月份 Microsoft 資訊安全公告摘要
=========================================

發行日期：2015 年 4 月 14 日

**版本：** 1.0

此公告摘要列出 2015 年 4 月份所發行的安全性公告。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](https://technet.microsoft.com/zh-tw/security/dd252948.aspx)。

Microsoft 也會提供資訊協助客戶排定每月資訊安全更新以及任何非安全性更新的優先順序，其中這些非安全性更新的發行日期與每月安全性更新的發行日期相同。請參閱**＜其他資訊＞**一節。

提要
----

下表依嚴重性摘要說明本月份資訊安全公告。

如需受影響之軟體的詳細資料，請參閱下節**＜受影響的軟體＞**。

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
<td style="border:1px solid black;"><strong>公告 ID</strong></td>
<td style="border:1px solid black;"><strong>公告標題與提要</strong></td>
<td style="border:1px solid black;"><strong>最高的嚴重性等級<br />
和資訊安全風險影響</strong></td>
<td style="border:1px solid black;"><strong>重新啟動需求</strong></td>
<td style="border:1px solid black;"><strong>已知<br />
問題</strong></td>
<td style="border:1px solid black;"><strong>受影響的<br />
軟體</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532626">MS15-032</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 積存安全性更新 (3038314)</strong> <br />
此安全性更新可解決 Internet Explorer 中的資訊安全風險。其中最嚴重的資訊安全風險，可能在使用者以 Internet Explorer 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用這些資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532628">MS15-033</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 中的資訊安全風險可能會允許遠端執行程式碼 (3048019)</strong> <br />
此安全性更新可解決 Microsoft Office 中的資訊安全風險。如果使用者開啟蓄意製作的 Microsoft Office 檔案，最嚴重的資訊安全風險可能會允許遠端執行程式碼。成功利用這些資訊安全風險的攻擊者，能以目前使用者的權限層級執行任意程式碼。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532630">MS15-034</a></td>
<td style="border:1px solid black;"><strong>HTTP.sys 中的資訊安全風險可能會允許遠端執行程式碼 (3042553)</strong><br />
此安全性更新可解決 Microsoft Windows 中的資訊安全風險。如果攻擊者傳送蓄意製作的 HTTP 要求到受影響的 Windows 系統，則此資訊安全風險可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532631">MS15-035</a></td>
<td style="border:1px solid black;"><strong>Microsoft 圖形元件中的資訊安全風險可能會允許遠端執行程式碼 (3046306)</strong><br />
此安全性更新可解決 Microsoft Windows 中的資訊安全風險。如果攻擊者成功引誘使用者瀏覽蓄意製作的網站、開啟蓄意製作的檔案，或瀏覽到包含蓄意製作的增強型中繼檔案 (EMF) 影像檔的工作目錄，此資訊安全風險可能會允許遠端執行程式碼。但是，在所有情況下，攻擊者可能無法強制使用者採取此類動作；攻擊者必須引誘使用者這麼做，一般是藉助電子郵件附件或 Instant Messenger 訊息。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532634">MS15-036</a></td>
<td style="border:1px solid black;"><strong>在 Microsoft SharePoint Server 中的資訊安全風險可能會允許權限提高 (3052044)</strong><br />
此安全性更新可解決 Microsoft Office Server 及生產力軟體中的資訊安全風險。如果攻擊者將蓄意製作的要求傳送給受影響的 SharePoint 伺服器，則該資訊安全風險可能會允許權限提高。成功利用這些資訊安全風險的攻擊者，能讀取該攻擊者無權讀取的內容、冒充受害者的身分在 SharePoint 網站上進行變更權限及刪除內容等動作，以及將惡意內容插入受害者的瀏覽器。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft 伺服器軟體，<br />
生產力軟體</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532635">MS15-037</a></td>
<td style="border:1px solid black;"><strong>Windows 工作排程器中的資訊安全風險可能會允許權限提高 (3046269)</strong><br />
此安全性更新可解決 Microsoft Windows 中的資訊安全風險。成功利用這個資訊安全風險的攻擊者可利用已知的無效工作，導致工作排程器在系統帳戶內容中執行蓄意製作的應用程式。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">不需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532639">MS15-038</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows 中的資訊安全風險可能會允許權限提高 (3049576)</strong> <br />
此安全性更新可解決 Microsoft Windows 中的資訊安全風險。如果攻擊者登入系統並執行蓄意製作的應用程式，則這些資訊安全風險可能允許權限提高。如果要利用這些資訊安全風險，攻擊者首先必須登入系統。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532641">MS15-039</a></td>
<td style="border:1px solid black;"><strong>XML Core Services 中的資訊安全風險可能會允許資訊安全功能略過 (3046482)</strong> <br />
此安全性更新可解決 Microsoft Windows 中的資訊安全風險。如果使用者按下蓄意製作的連結，此資訊安全風險可能會允許資訊安全功能略過。但是，在所有情況下，攻擊者可能無法強制使用者按下蓄意製作的連結；攻擊者必須引誘使用者按下連結，一般是藉助電子郵件附件或 Instant Messenger 訊息。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
資訊安全功能略過</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532642">MS15-040</a></td>
<td style="border:1px solid black;"><strong>Active Directory Federation Services 中的資訊安全風險可能允許資訊洩漏 (3045711)</strong> <br />
這個安全性更新可解決 Active Directory Federation Services (AD FS) 中的資訊安全風險。如果使用者從應用程式登出後持續開啟瀏覽器，且攻擊者在使用者登出後立即在瀏覽器中重新開啟應用程式。則此資訊安全風險可能會允許資訊洩露。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
資訊洩漏</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532643">MS15-041</a></td>
<td style="border:1px solid black;"><strong>.NET Framework 中的資訊安全風險可能會導致資訊洩漏 (3048010)</strong><br />
這個安全性更新可解決 Microsoft .NET Framework 中一項資訊安全風險。如果攻擊者將蓄意製作的 Web 要求傳送至已自訂錯誤訊息的受影響伺服器，則此資訊安全風險可能會導致資訊洩漏。成功利用這個資訊安全風險的攻擊者可檢視組態檔的部分，從而得知敏感資訊。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
資訊洩漏</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532644">MS15-042</a></td>
<td style="border:1px solid black;"><strong>Windows Hyper-V 中的資訊安全風險可能會允許阻斷服務 (DoS) (3047234)</strong><br />
此安全性更新可解決 Microsoft Windows 中的資訊安全風險。如果通過驗證的攻擊者在虛擬機器 (VM) 工作階段中執行蓄意製作的應用程式，則此資訊安全風險可允許阻斷服務 (DoS)。請注意，阻斷服務 (DoS) 不允許攻擊者在 Hyper-V 主機上執行的其他 VM 上執行程式碼或提高使用者權限，但會導致 Virtual Machine Manager 的主機上的其他 VM 無法管理。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
阻斷服務 (DoS)</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
資訊安全風險入侵指數  
--------------------
  
下表提供本月所述每個資訊安全風險的利用性評估。會依序按公告編號及 CVE ID 的順序列出資訊安全風險。只會包含公告中嚴重性等級為「重大」或「重要」的資訊安全風險。
  
**我該如何使用這個表格？**
  
您可以運用此表格，針對您可能需要安裝的每一項安全性更新，瞭解資訊安全風險在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務 (DoS) 的可能性。請根據您特定的組態設定，檢閱下列各項評估，決定部署本月份更新的優先次序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](https://technet.microsoft.com/zh-tw/security/cc998259)。
  
在下方欄位中，「最新軟體版本」意指受影響軟體，「較舊軟體版本」意指受影響軟體所有較舊的支援版本，如公告中的「受影響的軟體」或「不受影響的軟體」表格裡所示。
  
<p></p>
<table style="width:100%;">
<colgroup>
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告 ID</strong></td>
<td style="border:1px solid black;"><strong>資訊安全風險標題</strong></td>
<td style="border:1px solid black;"><strong>CVE ID</strong></td>
<td style="border:1px solid black;"><strong>較早軟體版本的<br />
資訊安全風險評估</strong></td>
<td style="border:1px solid black;"><strong>較早軟體版本的<br />
資訊安全風險評估</strong></td>
<td style="border:1px solid black;"><strong>阻絕服務<br />
資訊安全風險評估</strong></td>
<td style="border:1px solid black;"><strong>主要重點</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532626">MS15-032</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1652">CVE-2015 -1652</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532626">MS15-032</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1657">CVE-2015 -1657</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532626">MS15-032</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1659">CVE-2015 -1659</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532626">MS15-032</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1660">CVE-2015 -1660</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532626">MS15-032</a></td>
<td style="border:1px solid black;">Internet Explorer ASLR 略過資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1661">CVE-2015 -1661</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532626">MS15-032</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1662">CVE-2015 -1662</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532626">MS15-032</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1665">CVE-2015 -1665</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532626">MS15-032</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1666">CVE-2015 -1666</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532626">MS15-032</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1667">CVE-2015 -1667</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532626">MS15-032</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1668">CVE-2015 -1668</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532628">MS15-033</a></td>
<td style="border:1px solid black;">Microsoft Outlook App for Mac XSS 資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1639">CVE-2015 -1639</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532628">MS15-033</a></td>
<td style="border:1px solid black;">Microsoft Office 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1641">CVE-2015 -1641</a></td>
<td style="border:1px solid black;">0 - 已偵測到利用</td>
<td style="border:1px solid black;">0 - 已偵測到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">此資訊安全風險已經公開揭發。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532628">MS15-033</a></td>
<td style="border:1px solid black;">Microsoft Office 元件釋放後使用資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1649">CVE-2015 -1649</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532628">MS15-033</a></td>
<td style="border:1px solid black;">Microsoft Office 元件釋放後使用資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1650">CVE-2015 -1650</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532628">MS15-033</a></td>
<td style="border:1px solid black;">Microsoft Office 元件釋放後使用資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1651">CVE-2015 -1651</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532630">MS15-034</a></td>
<td style="border:1px solid black;">HTTP.sys 遠端執行程式碼資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1635">CVE-2015 -1635</a></td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532631">MS15-035</a></td>
<td style="border:1px solid black;">EMF 處理遠端執行程式碼資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1645">CVE-2015 -1645</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532634">MS15-036</a></td>
<td style="border:1px solid black;">Microsoft SharePoint XSS 資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1640">CVE-2015 -1640</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是權限提高的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532634">MS15-036</a></td>
<td style="border:1px solid black;">Microsoft SharePoint XSS 資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1653">CVE-2015 -1653</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是權限提高的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532635">MS15-037</a></td>
<td style="border:1px solid black;">工作排程器權限提高資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0098">CVE-2015-0098</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">1 - 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是權限提高的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532639">MS15-038</a></td>
<td style="border:1px solid black;">NtCreateTransactionManager 類型混淆資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1643">CVE-2015 -1643</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">這是權限提高的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532639">MS15-038</a></td>
<td style="border:1px solid black;">Windows MS-DOS 裝置名稱資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1644">CVE-2015 -1644</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是權限提高的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532641">MS15-039</a></td>
<td style="border:1px solid black;">MSXML3 相同來源原則 SFB 資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1646">CVE-2015 -1646</a></td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊安全功能略過的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532642">MS15-040</a></td>
<td style="border:1px solid black;">Active Directory Federation Services 資訊洩露資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1638">CVE-2015 -1638</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊洩漏的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532643">MS15-041</a></td>
<td style="border:1px solid black;">ASP.NET 資訊洩漏資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1648">CVE-2015 -1648</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊洩漏的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=532644">MS15-042</a></td>
<td style="border:1px solid black;">Windows Hyper-V DoS 資訊安全風險</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1647">CVE-2015 -1647</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">4 - 不受影響</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">這是一項阻斷服務 (DoS) 的資訊安全風險。</td>
</tr>
</tbody>
</table>
  
受影響的軟體  
------------
  
下表依據主要的軟體類別和嚴重性依序列出公告。
  
請用這些表格來瞭解可能需要安裝的安全性更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的安全性更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。
  
**注意**：一項資訊安全風險，可能需要安裝數個資訊安全更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
### Windows 作業系統及元件 (表格 2 之 1)


<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-032**](https://go.microsoft.com/fwlink/?linkid=532626)

</td>
<td style="border:1px solid black;">
[**MS15-034**](https://go.microsoft.com/fwlink/?linkid=532630)

</td>
<td style="border:1px solid black;">
[**MS15-035**](https://go.microsoft.com/fwlink/?linkid=532631)

</td>
<td style="border:1px solid black;">
[**MS15-037**](https://go.microsoft.com/fwlink/?linkid=532635)

</td>
<td style="border:1px solid black;">
[**MS15-038**](https://go.microsoft.com/fwlink/?linkid=532639)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3038314)  
(中度)  
Internet Explorer 7  
(3038314)  
(中度)  
Internet Explorer 8  
(3038314)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3046306)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2003 R2 Service Pack 2  
(3045685)  
(重要)  
Windows Server 2003 Service Pack 2  
(3045999)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3038314)  
(中度)  
Internet Explorer 7  
(3038314)  
(中度)  
Internet Explorer 8  
(3038314)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3046306)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2003 R2 x64 Edition Service Pack 2  
(3045685)  
(重要)  
Windows Server 2003 x64 Edition Service Pack 2  
(3045999)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3038314)  
(中度)  
Internet Explorer 7  
(3038314)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(3046306)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(3045999)  
(重要)

</td>
</tr>
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
[**MS15-032**](https://go.microsoft.com/fwlink/?linkid=532626)

</td>
<td style="border:1px solid black;">
[**MS15-034**](https://go.microsoft.com/fwlink/?linkid=532630)

</td>
<td style="border:1px solid black;">
[**MS15-035**](https://go.microsoft.com/fwlink/?linkid=532631)

</td>
<td style="border:1px solid black;">
[**MS15-037**](https://go.microsoft.com/fwlink/?linkid=532635)

</td>
<td style="border:1px solid black;">
[**MS15-038**](https://go.microsoft.com/fwlink/?linkid=532639)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3038314)  
(重大)  
Internet Explorer 8  
(3038314)  
(重大)  
Internet Explorer 9  
(3038314)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3046306)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3045685)  
(重要)  
Windows Vista Service Pack 2  
(3045999)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3038314)  
(重大)  
Internet Explorer 8  
(3038314)  
(重大)  
Internet Explorer 9  
(3038314)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3046306)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3045685)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3045999)  
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
[**MS15-032**](https://go.microsoft.com/fwlink/?linkid=532626)

</td>
<td style="border:1px solid black;">
[**MS15-034**](https://go.microsoft.com/fwlink/?linkid=532630)

</td>
<td style="border:1px solid black;">
[**MS15-035**](https://go.microsoft.com/fwlink/?linkid=532631)

</td>
<td style="border:1px solid black;">
[**MS15-037**](https://go.microsoft.com/fwlink/?linkid=532635)

</td>
<td style="border:1px solid black;">
[**MS15-038**](https://go.microsoft.com/fwlink/?linkid=532639)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**普通**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3038314)  
(中度)  
Internet Explorer 8  
(3038314)  
(中度)  
Internet Explorer 9  
(3038314)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2  
(3046306)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2  
(3045685)  
(重要)  
32 位元系統的 Windows Server 2008 Service Pack 2  
(3045999)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3038314)  
(中度)  
Internet Explorer 8  
(3038314)  
(中度)  
Internet Explorer 9  
(3038314)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3046306)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3045685)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3045999)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3038314)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2  
(3046306)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2  
(3045685)  
(重要)  
Itanium 系統的 Windows Server 2008 Service Pack 2  
(3045999)  
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
[**MS15-032**](https://go.microsoft.com/fwlink/?linkid=532626)

</td>
<td style="border:1px solid black;">
[**MS15-034**](https://go.microsoft.com/fwlink/?linkid=532630)

</td>
<td style="border:1px solid black;">
[**MS15-035**](https://go.microsoft.com/fwlink/?linkid=532631)

</td>
<td style="border:1px solid black;">
[**MS15-037**](https://go.microsoft.com/fwlink/?linkid=532635)

</td>
<td style="border:1px solid black;">
[**MS15-038**](https://go.microsoft.com/fwlink/?linkid=532639)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3038314)  
(重大)  
Internet Explorer 9  
(3038314)  
(重大)  
Internet Explorer 10  
(3038314)  
(重大)  
Internet Explorer 11  
(3038314)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3042553)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3046306)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3046269)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3045685)  
(重要)  
Windows 7 32 位元系統 Service Pack 1  
(3045999)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3038314)  
(重大)  
Internet Explorer 9  
(3038314)  
(重大)  
Internet Explorer 10  
(3038314)  
(重大)  
Internet Explorer 11  
(3038314)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3042553)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3046306)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3046269)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3045685)  
(重要)  
Windows 7 x64 系統 Service Pack 1  
(3045999)  
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
[**MS15-032**](https://go.microsoft.com/fwlink/?linkid=532626)

</td>
<td style="border:1px solid black;">
[**MS15-034**](https://go.microsoft.com/fwlink/?linkid=532630)

</td>
<td style="border:1px solid black;">
[**MS15-035**](https://go.microsoft.com/fwlink/?linkid=532631)

</td>
<td style="border:1px solid black;">
[**MS15-037**](https://go.microsoft.com/fwlink/?linkid=532635)

</td>
<td style="border:1px solid black;">
[**MS15-038**](https://go.microsoft.com/fwlink/?linkid=532639)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**普通**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3038314)  
(中度)  
Internet Explorer 9  
(3038314)  
(中度)  
Internet Explorer 10  
(3038314)  
(中度)  
Internet Explorer 11  
(3038314)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3042553)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3046306)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3046269)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3045685)  
(重要)  
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3045999)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3038314)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3042553)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3046306)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3046269)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3045685)  
(重要)  
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3045999)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-032**](https://go.microsoft.com/fwlink/?linkid=532626)

</td>
<td style="border:1px solid black;">
[**MS15-034**](https://go.microsoft.com/fwlink/?linkid=532630)

</td>
<td style="border:1px solid black;">
[**MS15-035**](https://go.microsoft.com/fwlink/?linkid=532631)

</td>
<td style="border:1px solid black;">
[**MS15-037**](https://go.microsoft.com/fwlink/?linkid=532635)

</td>
<td style="border:1px solid black;">
[**MS15-038**](https://go.microsoft.com/fwlink/?linkid=532639)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 32 位元系統

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3038314)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3042553)  
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
(3045685)  
(重要)  
Windows 8 32 位元系統  
(3045999)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 x64 系統

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3038314)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3042553)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3045685)  
(重要)  
Windows 8 x64 系統  
(3045999)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3038314)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3042553)  
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
(3045685)  
(重要)  
Windows 8.1 32 位元系統  
(3045999)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 x64 系統

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3038314)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3042553)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3045685)  
(重要)  
Windows 8.1 x64 系統  
(3045999)  
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
[**MS15-032**](https://go.microsoft.com/fwlink/?linkid=532626)

</td>
<td style="border:1px solid black;">
[**MS15-034**](https://go.microsoft.com/fwlink/?linkid=532630)

</td>
<td style="border:1px solid black;">
[**MS15-035**](https://go.microsoft.com/fwlink/?linkid=532631)

</td>
<td style="border:1px solid black;">
[**MS15-037**](https://go.microsoft.com/fwlink/?linkid=532635)

</td>
<td style="border:1px solid black;">
[**MS15-038**](https://go.microsoft.com/fwlink/?linkid=532639)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**普通**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3038314)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3042553)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3045685)  
(重要)  
Windows Server 2012  
(3045999)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3038314)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3042553)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3045685)  
(重要)  
Windows Server 2012 R2  
(3045999)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-032**](https://go.microsoft.com/fwlink/?linkid=532626)

</td>
<td style="border:1px solid black;">
[**MS15-034**](https://go.microsoft.com/fwlink/?linkid=532630)

</td>
<td style="border:1px solid black;">
[**MS15-035**](https://go.microsoft.com/fwlink/?linkid=532631)

</td>
<td style="border:1px solid black;">
[**MS15-037**](https://go.microsoft.com/fwlink/?linkid=532635)

</td>
<td style="border:1px solid black;">
[**MS15-038**](https://go.microsoft.com/fwlink/?linkid=532639)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3038314)  
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
Windows RT  
(3045685)  
(重要)  
Windows RT  
(3045999)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3038314)  
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
(3045685)  
(重要)  
Windows RT 8.1  
(3045999)  
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
[**MS15-032**](https://go.microsoft.com/fwlink/?linkid=532626)

</td>
<td style="border:1px solid black;">
[**MS15-034**](https://go.microsoft.com/fwlink/?linkid=532630)

</td>
<td style="border:1px solid black;">
[**MS15-035**](https://go.microsoft.com/fwlink/?linkid=532631)

</td>
<td style="border:1px solid black;">
[**MS15-037**](https://go.microsoft.com/fwlink/?linkid=532635)

</td>
<td style="border:1px solid black;">
[**MS15-038**](https://go.microsoft.com/fwlink/?linkid=532639)

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
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
(3046306)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3045685)  
(重要)  
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3045999)  
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
(3046306)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3045685)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3045999)  
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
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3042553)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3046306)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3046269)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3045685)  
(重要)  
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3045999)  
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
Windows Server 2012 (Server Core 安裝)  
(3042553)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3045685)  
(重要)  
Windows Server 2012 (Server Core 安裝)  
(3045999)  
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
Windows Server 2012 R2 (Server Core 安裝)  
(3042553)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3045685)  
(重要)  
Windows Server 2012 R2 (Server Core 安裝)  
(3045999)  
(重要)

</td>
</tr>
</table>
 
**MS15-032 和 MS15-034 注意事項**

Windows Technical Preview 和 Windows Server Technical Preview 會受影響。建議執行這些作業系統的客戶透過 [Windows Update](https://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-tw) 套用此更新。

** **

### Windows 作業系統及元件 (表格 2 之 2)


<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-039**](https://go.microsoft.com/fwlink/?linkid=532641)

</td>
<td style="border:1px solid black;">
[**MS15-040**](https://go.microsoft.com/fwlink/?linkid=532642)

</td>
<td style="border:1px solid black;">
[**MS15-041**](https://go.microsoft.com/fwlink/?linkid=532643)

</td>
<td style="border:1px solid black;">
[**MS15-042**](https://go.microsoft.com/fwlink/?linkid=532644)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
Windows Server 2003 Service Pack 2  
(3046482)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1 (英文)  
(3037572)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2 (英文)  
(3037577)  
(重要)  
Microsoft .NET Framework 4  
(3037578)  
(重要)

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
Windows Server 2003 x64 Edition Service Pack 2  
(3046482)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2 (英文)  
(3037577)  
(重要)  
Microsoft .NET Framework 4  
(3037578)  
(重要)

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
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(3046482)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2 (英文)  
(3037577)  
(重要)  
Microsoft .NET Framework 4  
(3037578)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
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
[**MS15-039**](https://go.microsoft.com/fwlink/?linkid=532641)

</td>
<td style="border:1px solid black;">
[**MS15-040**](https://go.microsoft.com/fwlink/?linkid=532642)

</td>
<td style="border:1px solid black;">
[**MS15-041**](https://go.microsoft.com/fwlink/?linkid=532643)

</td>
<td style="border:1px solid black;">
[**MS15-042**](https://go.microsoft.com/fwlink/?linkid=532644)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
(3046482)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2 (英文)  
(3037573)  
(重要)  
Microsoft .NET Framework 4  
(3037578)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3037581)  
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
Windows Vista x64 Edition Service Pack 2  
(3046482)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2 (英文)  
(3037573)  
(重要)  
Microsoft .NET Framework 4  
(3037578)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3037581)  
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
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-039**](https://go.microsoft.com/fwlink/?linkid=532641)

</td>
<td style="border:1px solid black;">
[**MS15-040**](https://go.microsoft.com/fwlink/?linkid=532642)

</td>
<td style="border:1px solid black;">
[**MS15-041**](https://go.microsoft.com/fwlink/?linkid=532643)

</td>
<td style="border:1px solid black;">
[**MS15-042**](https://go.microsoft.com/fwlink/?linkid=532644)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
32 位元系統的 Windows Server 2008 Service Pack 2  
(3046482)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2 (英文)  
(3037573)  
(重要)  
Microsoft .NET Framework 4  
(3037578)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3037581)  
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
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3046482)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2 (英文)  
(3037573)  
(重要)  
Microsoft .NET Framework 4  
(3037578)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3037581)  
(重要)

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
Itanium 系統的 Windows Server 2008 Service Pack 2  
(3046482)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2 (英文)  
(3037573)  
(重要)  
Microsoft .NET Framework 4  
(3037578)  
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
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-039**](https://go.microsoft.com/fwlink/?linkid=532641)

</td>
<td style="border:1px solid black;">
[**MS15-040**](https://go.microsoft.com/fwlink/?linkid=532642)

</td>
<td style="border:1px solid black;">
[**MS15-041**](https://go.microsoft.com/fwlink/?linkid=532643)

</td>
<td style="border:1px solid black;">
[**MS15-042**](https://go.microsoft.com/fwlink/?linkid=532644)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3046482)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3037574)  
(重要)  
Microsoft .NET Framework 4  
(3037578)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3037581)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3046482)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3037574)  
(重要)  
Microsoft .NET Framework 4  
(3037578)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3037581)  
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
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-039**](https://go.microsoft.com/fwlink/?linkid=532641)

</td>
<td style="border:1px solid black;">
[**MS15-040**](https://go.microsoft.com/fwlink/?linkid=532642)

</td>
<td style="border:1px solid black;">
[**MS15-041**](https://go.microsoft.com/fwlink/?linkid=532643)

</td>
<td style="border:1px solid black;">
[**MS15-042**](https://go.microsoft.com/fwlink/?linkid=532644)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3046482)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3037574)  
(重要)  
Microsoft .NET Framework 4  
(3037578)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3037581)  
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
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3046482)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3037574)  
(重要)  
Microsoft .NET Framework 4  
(3037578)  
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
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-039**](https://go.microsoft.com/fwlink/?linkid=532641)

</td>
<td style="border:1px solid black;">
[**MS15-040**](https://go.microsoft.com/fwlink/?linkid=532642)

</td>
<td style="border:1px solid black;">
[**MS15-041**](https://go.microsoft.com/fwlink/?linkid=532643)

</td>
<td style="border:1px solid black;">
[**MS15-042**](https://go.microsoft.com/fwlink/?linkid=532644)

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
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 32 位元系統

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3037575)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3037580)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 x64 系統

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3037575)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3037580)  
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
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3037576)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3037579)  
(重要)

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
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3037576)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3037579)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3047234)  
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
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-039**](https://go.microsoft.com/fwlink/?linkid=532641)

</td>
<td style="border:1px solid black;">
[**MS15-040**](https://go.microsoft.com/fwlink/?linkid=532642)

</td>
<td style="border:1px solid black;">
[**MS15-041**](https://go.microsoft.com/fwlink/?linkid=532643)

</td>
<td style="border:1px solid black;">
[**MS15-042**](https://go.microsoft.com/fwlink/?linkid=532644)

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
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3037575)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3037580)  
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
Active Directory Federation Services 3.0  
(3045711)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3037576)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3037579)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3047234)  
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
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-039**](https://go.microsoft.com/fwlink/?linkid=532641)

</td>
<td style="border:1px solid black;">
[**MS15-040**](https://go.microsoft.com/fwlink/?linkid=532642)

</td>
<td style="border:1px solid black;">
[**MS15-041**](https://go.microsoft.com/fwlink/?linkid=532643)

</td>
<td style="border:1px solid black;">
[**MS15-042**](https://go.microsoft.com/fwlink/?linkid=532644)

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
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3037580)  
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
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1/4.5.2  
(3037579)  
(重要)

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
[**MS15-039**](https://go.microsoft.com/fwlink/?linkid=532641)

</td>
<td style="border:1px solid black;">
[**MS15-040**](https://go.microsoft.com/fwlink/?linkid=532642)

</td>
<td style="border:1px solid black;">
[**MS15-041**](https://go.microsoft.com/fwlink/?linkid=532643)

</td>
<td style="border:1px solid black;">
[**MS15-042**](https://go.microsoft.com/fwlink/?linkid=532644)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3046482)  
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
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3046482)  
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
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3046482)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3037574)  
(重要)  
Microsoft .NET Framework 4  
(3037578)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3037581)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

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
Microsoft .NET Framework 3.5  
(3037575)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3037580)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

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
Active Directory Federation Services 3.0  
(3045711)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3037576)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3037579)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3047234)  
(重要)

</td>
</tr>
</table>
 
**MS15-040 和 MS15-042 注意事項：**

Windows Technical Preview 和 Windows Server Technical Preview 會受影響。建議執行這些作業系統的客戶透過 [Windows Update](https://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-tw) 套用此更新。

 

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
[**MS15-036**](https://go.microsoft.com/fwlink/?linkid=532634)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1  
(2965219)  
(重要)  
Microsoft SharePoint Server 2013 Service Pack 1  
(2965219)  
(重要)

</td>
</tr>
</table>
 
**MS15-036 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

 

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
[**MS15-033**](https://go.microsoft.com/fwlink/?linkid=532628)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Word 2007 Service Pack 3  
(2965284)  
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
[**MS15-033**](https://go.microsoft.com/fwlink/?linkid=532628)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(2965236)  
(重大)  
Microsoft Word 2010 Service Pack 2 (32 位元版本)  
(2553428)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(2965236)  
(重大)  
Microsoft Word 2010 Service Pack 2 (64 位元版本)  
(2553428)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013 和 Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-033**](https://go.microsoft.com/fwlink/?linkid=532628)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 Service Pack 1 (32 位元版本)  
(2965224)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 位元版本)

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 Service Pack 1 (64 位元版本)  
(2965224)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1  
(2965224)  
(重要)

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
[**MS15-033**](https://go.microsoft.com/fwlink/?linkid=532628)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Outlook for Mac for Office 365

</td>
<td style="border:1px solid black;">
Microsoft Outlook for Mac for Office 365  
(3055707)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011  
(3051737)  
(重要)  
Microsoft Word for Mac 2011  
(3051737)  
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
[**MS15-033**](https://go.microsoft.com/fwlink/?linkid=532628)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2965289)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack Service Pack 3  
(2965210)  
(重大)

</td>
</tr>
</table>
 
**MS15-033 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

 

### Microsoft Office Services 和 Web Apps

<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-033**](https://go.microsoft.com/fwlink/?linkid=532628)

</td>
<td style="border:1px solid black;">
[**MS15-036**](https://go.microsoft.com/fwlink/?linkid=532634)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2553164)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft Project Server 2010 Service Pack 2  
(2965302)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-033**](https://go.microsoft.com/fwlink/?linkid=532628)

</td>
<td style="border:1px solid black;">
[**MS15-036**](https://go.microsoft.com/fwlink/?linkid=532634)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2965215)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Project Server 2013 Service Pack 1  
(2965278)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office Web Apps 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-033**](https://go.microsoft.com/fwlink/?linkid=532628)

</td>
<td style="border:1px solid black;">
[**MS15-036**](https://go.microsoft.com/fwlink/?linkid=532634)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2010 Service Pack 2  
(2965238)  
(重大)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office Web Apps 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS15-033**](https://go.microsoft.com/fwlink/?linkid=532628)

</td>
<td style="border:1px solid black;">
[**MS15-036**](https://go.microsoft.com/fwlink/?linkid=532634)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(2965306)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
</table>
 
**MS15-033 和 MS15-036 注意事項**

本公告涉及多個軟體分類。請參閱本節中的其他表格，瞭解其他受影響的軟體。

偵測與部署工具及指南
--------------------

有幾項資源可協助系統管理員部署資訊安全更新。

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機與遠端系統是否有遺漏的安全性更新或常見的安全性錯誤設定。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 可協助系統管理員發佈安全性更新。

應用程式相容性工具組隨附的 Update Compatibility Evaluator 元件可針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

如需上述工具以及其他可使用工具的詳細資訊，請參閱 [IT 專業人員的資訊安全工具](https://technet.microsoft.com/zh-tw/security/cc297183)。

致謝
----

Microsoft 了解資訊安全業界所做的努力，其盡責地透露資訊安全風險來協助我們保護客戶。請參閱[致謝](https://technet.microsoft.com/zh-tw/library/security/dn903755.aspx) (英文) 以取得詳細資訊。

其他資訊
--------

### Microsoft Windows 惡意軟體移除工具 (英文)

針對每個月第二個星期二發行的公告，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 及下載中心發行更新版本的 Microsoft Windows 惡意軟體移除工具。不定期資訊安全公告發行不提供更新版本的 Microsoft Windows 惡意軟體移除工具。

### MU、WU 及 WSUS 上的非安全性更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [Microsoft 知識庫文章 894199](https://support.microsoft.com/zh-tw/kb/894199)：Software Update Services 與 Windows Server Update Services 的說明內容有所變動。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](https://technet.microsoft.com/zh-tw/windowsserver/bb332157.aspx)。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的資訊安全保護，Microsoft 將在每月發行安全性更新之前，提前向重要資訊安全軟體提供者提供資訊安全風險資訊。資訊安全軟體提供者可利用此資訊安全風險資訊，透過其資訊安全軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](https://technet.microsoft.com/zh-tw/security/dn467918) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

### 安全性策略與社群

**更新程式管理策略**

[更新管理安全性指南](https://technet.microsoft.com/zh-tw/library/bb466251.aspx) (英文) 提供您有關套用資訊安全更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他資訊安全問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得，您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](https://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-tw) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的資訊安全更新。如需更多資訊，請參閱 [Microsoft 知識庫文章 913086](https://support.microsoft.com/zh-tw/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](https://technet.microsoft.com/zh-tw/security/cc136632.aspx)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

### 支援

所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](https://go.microsoft.com/fwlink/?linkid=21742)。

IT 專業人員的資訊安全解決方案：[TechNet 資訊安全疑難排解與支援](https://technet.microsoft.com/zh-tw/security/bb980617)

協助保護您執行 Windows 的電腦免於受到病毒和惡意程式碼攻擊：[病毒解決方案與資訊安全中心](https://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-tw)

您所在國家/地區的當地支援：[國際支援](https://support.microsoft.com/common/international.aspx?ln=zh-tw)

### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

### 修訂

-   V1.0 (2015 年 4 月 14 日)：公告摘要發行。

*頁面產生時間：2015-04-09 11:16Z-07:00。*
