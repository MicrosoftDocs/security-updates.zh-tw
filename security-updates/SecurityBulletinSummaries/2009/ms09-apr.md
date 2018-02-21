---
TOCTitle: 'MS09-APR'
Title: 2009 年 4 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms09-apr'
ms:contentKeyID: 61237689
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms09-apr(v=Security.10)'
---

2009 年 4 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2009年4月15日

**版本:** 1.0

此公告摘要列出 2009 年 4 月份所發行的安全性公告。

發行 2009 年 4 月份公告之後，此公告摘要將取代原先於 2009 年 4 月 9 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](http://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2009 年 4 月 15 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。 [立即註冊參加 4 月份安全性公告網路廣播。](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032395126) 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](http://www.microsoft.com/taiwan/security/bulletins/default.mspx)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性、高優先順序更新的優先順序，其中這些非安全性、高優先順序更新的發行日期與每月安全性更新的發行日期相同。 請參閱＜其他資訊＞一節。

### 公告資訊

提要
----

<span></span>
下表依嚴重性摘要說明本月份安全性公告。

如需受影響的軟體之詳細資料，請參閱下節＜受影響的軟體及下載位置＞。

 
<p> </p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >公告編號</th>
<th style="border:1px solid black;" >公告標題與提要</th>
<th style="border:1px solid black;" >最高的嚴重性等級與弱點影響</th>
<th style="border:1px solid black;" >重新開機需求</th>
<th style="border:1px solid black;" >受影響的軟體</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-010">MS09-010</a></td>
<td style="border:1px solid black;"><strong>WordPad 及 Office 文字轉換程式中的弱點可能允許遠端執行程式碼 (960477)</strong><br />
<br />
此安全性更新可解決 Microsoft WordPad 及 Microsoft Office 文字轉換程式中，兩項公開揭發和兩項未公開報告的弱點。 若在 WordPad 或 Microsoft Office Word 中開啟蓄意製作的檔案，這些弱點可能會允許遠端執行程式碼。 使用受影響版本的 WordPad 或 Microsoft Office Word 時，請勿開啟來自不信任來源的 Microsoft Office、RTF、Write 或 WordPerfect 檔案。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-013">MS09-013</a></td>
<td style="border:1px solid black;"><strong>Windows HTTP 服務中的弱點可能會允許遠端執行程式碼 (960803)</strong><br />
<br />
這個安全性更新可解決 Microsoft Windows HTTP 服務 (WinHTTP) 中一項公開揭露和兩項未公開報告的弱點。 最嚴重的弱點可能會允許遠端執行程式碼。 成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-011">MS09-011</a></td>
<td style="border:1px solid black;"><strong>Microsoft DirectShow 中的弱點可能會允許遠端執行程式碼 (961373)</strong><br />
<br />
這個安全性更新可解決 Microsoft DirectX 中一項未公開報告的弱點。 如果使用者開啟蓄意製作的 MJPEG 檔案，此弱點可能會允許遠端執行程式碼。 成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-014">MS09-014</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 積存安全性更新 (963027)</strong><br />
<br />
這個安全性更新可解決 Internet Explorer 中四項未公開報告的弱點，以及兩項公開揭露的弱點。 若使用者用 Internet Explorer 檢視蓄意製作的網頁，或使用者透過 HTTP 通訊協定連線至攻擊者的伺服器時，這些弱點可能允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-009">MS09-009</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Excel 的弱點可能會導致遠端執行程式碼 (968557)</strong><br />
<br />
此安全性更新可解決一項未公開報告的弱點，以及一項已公開揭露的弱點。 如果使用者開啟蓄意製作的 Excel 檔案，此弱點可能會允許遠端執行程式碼。 成功利用這類弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-012">MS09-012</a></td>
<td style="border:1px solid black;"><strong>Windows 中的弱點可能會允許權限提高 (959454)</strong><br />
<br />
這個安全性更新可解決 Microsoft Windows 中四項公開報告的弱點。 如果允許攻擊者登入系統，並執行蓄意製作的應用程式，則弱點可能會允許權限提高。 攻擊者必須能夠在本機電腦執行程式碼，才能利用這項弱點。 成功利用這些弱點的攻擊者可以取得受影響系統的完整控制權。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-016">MS09-016</a></td>
<td style="border:1px solid black;"><strong>Microsoft ISA Server 與 Forefront Threat Management Gateway (Medium Business Edition) 中的弱點可能導致拒絕服務 (961759)</strong><br />
<br />
這個安全性更新可解決 Microsoft Internet Security and Acceleration (ISA) Server 與 Microsoft Forefront Threat Management Gateway (TMG) Medium Business Edition (MBE) 中的一個未公開報告的弱點，以及一個已公開揭露的弱點。 若攻擊者將蓄意製作的網路封包傳送至受影響的系統，則這些弱點可能導致拒絕服務；若使用者按下惡意的 URL，或造訪的網站含有由攻擊者所控制的內容，則這些弱點可能導致資訊洩漏。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
拒絕服務</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Forefront Edge Security</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-015">MS09-015</a></td>
<td style="border:1px solid black;"><strong>SearchPath 中的混合威脅弱點可能會允許權限提高 (959426)</strong><br />
<br />
這個安全性更新可解決 Windows SearchPath 函式中一項公開報告的弱點：如果使用者下載蓄意製作的檔案至特定位置，之後開啟了可能在特定情況下載入該檔案的應用程式，則可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">中度</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
弱點索引  
--------
  
<span></span>
下表提供本月所述每個弱點的利用性評估。 弱點皆根據公告編號和 CVE 編號依序列出。
  
**我該如何使用這個表格？**
  
請用這個表格來瞭解您可能需要安裝的每個安全性更新，與 30 天內已發行的可利用程式碼受影響之可能性。 您應該檢閱下列的每個評估，按照特定的設定，將部署以優先次序排序。 如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](http://technet.microsoft.com/en-us/security/cc998259.aspx)。
  
| 公告編號                                                            | 公告標題                                                                                                                | CVE ID                                                                             | 弱點索引評估                                                                                            | 主要重點           |  
|---------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|--------------------|  
| [MS09-010](http://technet.microsoft.com/security/bulletin/ms09-010) | WordPad 及 Office 文字轉換程式中的弱點可能允許遠端執行程式碼 (960477)                                                   | [CVE-2008-4841](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4841)   | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | 左側的等級只是範例 |  
| [MS09-010](http://technet.microsoft.com/security/bulletin/ms09-010) | WordPad 及 Office 文字轉換程式中的弱點可能允許遠端執行程式碼 (960477)                                                   | [CVE-2009-0087](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0087)   | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 左側的等級只是範例 |  
| [MS09-010](http://technet.microsoft.com/security/bulletin/ms09-010) | WordPad 及 Office 文字轉換程式中的弱點可能允許遠端執行程式碼 (960477)                                                   | [CVE-2009-0088](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0088)   | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | 左側的等級只是範例 |  
| [MS09-010](http://technet.microsoft.com/security/bulletin/ms09-010) | WordPad 及 Office 文字轉換程式中的弱點可能允許遠端執行程式碼 (960477)                                                   | [CVE-2009-0235](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0235)   |                                                                                                         |                    |  
| [MS09-013](http://technet.microsoft.com/security/bulletin/ms09-013) | Windows HTTP 服務中的弱點可能會允許遠端執行程式碼 (960803)                                                              | [CVE-2009-0086](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0086)   |                                                                                                         |                    |  
| [MS09-013](http://technet.microsoft.com/security/bulletin/ms09-013) | Windows HTTP 服務中的弱點可能會允許遠端執行程式碼 (960803)                                                              | [CVE-2009-0089](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0089)   |                                                                                                         |                    |  
| [MS09-013](http://technet.microsoft.com/security/bulletin/ms09-013) | Windows HTTP 服務中的弱點可能會允許遠端執行程式碼 (960803)                                                              | [CVE-2009-0550](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0550)   |                                                                                                         |                    |  
| [MS09-011](http://technet.microsoft.com/security/bulletin/ms09-011) | Microsoft DirectShow 中的弱點可能會允許遠端執行程式碼 (961373)                                                          | [CVE-2009-0084](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0084)   |                                                                                                         |                    |  
| [MS09-014](http://technet.microsoft.com/security/bulletin/ms09-014) | Internet Explorer 積存安全性更新 (963027)                                                                               | [CVE-2008-2540](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-2540)\* |                                                                                                         |                    |  
| [MS09-014](http://technet.microsoft.com/security/bulletin/ms09-014) | Internet Explorer 積存安全性更新 (963027)                                                                               | [CVE-2009-0550](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0550)   |                                                                                                         |                    |  
| [MS09-014](http://technet.microsoft.com/security/bulletin/ms09-014) | Internet Explorer 積存安全性更新 (963027)                                                                               | [CVE-2009-0551](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0551)   |                                                                                                         |                    |  
| [MS09-014](http://technet.microsoft.com/security/bulletin/ms09-014) | Internet Explorer 積存安全性更新 (963027)                                                                               | [CVE-2009-0552](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0552)   |                                                                                                         |                    |  
| [MS09-014](http://technet.microsoft.com/security/bulletin/ms09-014) | Internet Explorer 積存安全性更新 (963027)                                                                               | [CVE-2009-0553](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0553)   |                                                                                                         |                    |  
| [MS09-014](http://technet.microsoft.com/security/bulletin/ms09-014) | Internet Explorer 積存安全性更新 (963027)                                                                               | [CVE-2009-0554](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0554)   |                                                                                                         |                    |  
| [MS09-009](http://technet.microsoft.com/security/bulletin/ms09-009) | Microsoft Office Excel 的弱點可能會導致遠端執行程式碼 (968557)                                                          | [CVE-2009-0100](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0100)   |                                                                                                         |                    |  
| [MS09-009](http://technet.microsoft.com/security/bulletin/ms09-009) | Microsoft Office Excel 的弱點可能會導致遠端執行程式碼 (968557)                                                          | [CVE-2009-0238](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0238)   |                                                                                                         |                    |  
| [MS09-012](http://technet.microsoft.com/security/bulletin/ms09-012) | Windows 中的弱點可能會允許權限提高 (959454)                                                                             | [CVE-2008-1436](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-1436)   |                                                                                                         |                    |  
| [MS09-012](http://technet.microsoft.com/security/bulletin/ms09-012) | Windows 中的弱點可能會允許權限提高 (959454)                                                                             | [CVE-2009-0078](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0078)   |                                                                                                         |                    |  
| [MS09-012](http://technet.microsoft.com/security/bulletin/ms09-012) | Windows 中的弱點可能會允許權限提高 (959454)                                                                             | [CVE-2009-0079](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0079)   |                                                                                                         |                    |  
| [MS09-012](http://technet.microsoft.com/security/bulletin/ms09-012) | Windows 中的弱點可能會允許權限提高 (959454)                                                                             | [CVE-2009-0080](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0080)   |                                                                                                         |                    |  
| [MS09-016](http://technet.microsoft.com/security/bulletin/ms09-016) | Microsoft ISA Server 與 Forefront Threat Management Gateway (Medium Business Edition) 中的弱點可能導致拒絕服務 (961759) | [CVE-2009-0077](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0077)   |                                                                                                         |                    |  
| [MS09-016](http://technet.microsoft.com/security/bulletin/ms09-016) | Microsoft ISA Server 與 Forefront Threat Management Gateway (Medium Business Edition) 中的弱點可能導致拒絕服務 (961759) | [CVE-2009-0237](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-0237)        |                                                                                                         |                    |  
| [MS09-015](http://technet.microsoft.com/security/bulletin/ms09-015) | SearchPath 中的混合威脅弱點可能會允許權限提高 (959426)                                                                  | [CVE-2008-2540](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-2540)\* |                                                                                                         |                    |
  
\* 相同的弱點已在兩個安全性更新中獲得解決。 請參閱各自的公告以獲得詳細資訊。
  
受影響的軟體及下載位置  
----------------------
  
<span></span>
下表依據主要的軟體類別和嚴重性依序列出公告。
  
**我該如何使用這些表格？**
  
請用這些表格來瞭解可能需要安裝的安全性更新有哪些。 您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的安全性更新。 若軟體程式或更新出現在清單中，則相關可用軟體更新也會以超連結方式提供，也會列出軟體更新的嚴重性等級。
  
**注意**：一項弱點，可能需要安裝數個安全性更新才能妥善解決。 請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
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
</tr>
<tr>
<th colspan="7">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-013**](http://technet.microsoft.com/security/bulletin/ms09-013)
</td>
<td style="border:1px solid black;">
[**MS09-011**](http://technet.microsoft.com/security/bulletin/ms09-011)
</td>
<td style="border:1px solid black;">
[**MS09-014**](http://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-012**](http://technet.microsoft.com/security/bulletin/ms09-012)
</td>
<td style="border:1px solid black;">
[**MS09-015**](http://technet.microsoft.com/security/bulletin/ms09-015)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
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
(無嚴重性等級)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=552d322a-5282-42c7-9c1e-1d8c494a7318)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=39d5468e-5733-4c3e-9e75-3adac8ac8cb9)  
(重大)
</td>
<td style="border:1px solid black;">
[DirectX 8.1](http://www.microsoft.com/downloads/details.aspx?familyid=0ec5b7c7-13d3-467a-b24e-3cc6fb47adf6)  
(重大)  
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=8b98ed5c-a3ab-45a7-a61e-349eae304bc6)\*\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=7799fd05-5b26-449f-8a14-50227c9164d1)  
(重大)  
[Microsoft Internet Explorer 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=87f0c380-5c31-4099-a6a9-c12f9d69b03b)  
(重大)
</td>
<td style="border:1px solid black;">
MSDTC 交易設施更新：  
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=52b756e7-636f-4d9e-8a17-dbf467bfbe4d)  
(KB952004)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=c4e408d7-6716-4a12-ad3a-8029667f5c84)  
(無嚴重性等級)
</td>
</tr>
<tr>
<th colspan="7">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-013**](http://technet.microsoft.com/security/bulletin/ms09-013)
</td>
<td style="border:1px solid black;">
[**MS09-011**](http://technet.microsoft.com/security/bulletin/ms09-011)
</td>
<td style="border:1px solid black;">
[**MS09-014**](http://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-012**](http://technet.microsoft.com/security/bulletin/ms09-012)
</td>
<td style="border:1px solid black;">
[**MS09-015**](http://technet.microsoft.com/security/bulletin/ms09-015)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
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
[**中度**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 及 Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 與 Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=50a8519a-503e-43dd-a78a-c1bc764fd213)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 與 Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=35af4151-1858-4c9a-85e4-9ff45feca1a4)  
(重大)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=feb5d821-f210-40e8-b1aa-2ca3170df8df)\*\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=052c29fc-e8df-402c-9ab1-1079bc738e1b)  
(重大)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=55d6729a-9f96-4da4-b564-676c0a0c9390)  
(重大)
</td>
<td style="border:1px solid black;">
MSDTC 交易設施更新：  
[Windows XP Service Pack 2 及 Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=90fe715e-8190-43e9-9c43-df5be564d923)  
(KB952004)  
(重要)  
Windows 服務隔離更新：  
[Windows XP Service Pack 2 及 Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=73d2324f-be59-4b0c-b1ac-9876a13c2c03)  
(KB956572)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 與 Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=3de0684d-605c-489b-bdc7-08bce9b2d4f6)  
(中度)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=323f4211-5add-4e02-bce1-e5a1b489982c)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=49b16f0f-f6c3-4ca8-8041-392f4f7b5bbb)  
(重大)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=f1be8b7c-4874-4342-99b3-76ff725fbb9a)\*\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=84c62211-2e82-4ccc-9f9b-26462b026d86)  
(重大)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=191c2f20-89ae-4e1c-bdd4-24b4abfe6b6c)  
(重大)
</td>
<td style="border:1px solid black;">
MSDTC 交易設施更新：  
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a794c32a-9a0c-47d9-9c57-ff5d4a8e4944)  
(KB952004)  
(重要)  
Windows 服務隔離更新：  
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b2f12ae5-0e46-47e1-ac5b-93550d030189)  
(KB956572)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b743a7fe-7bf4-420d-a72e-39471e5659fa)  
(中度)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-013**](http://technet.microsoft.com/security/bulletin/ms09-013)
</td>
<td style="border:1px solid black;">
[**MS09-011**](http://technet.microsoft.com/security/bulletin/ms09-011)
</td>
<td style="border:1px solid black;">
[**MS09-014**](http://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-012**](http://technet.microsoft.com/security/bulletin/ms09-012)
</td>
<td style="border:1px solid black;">
[**MS09-015**](http://technet.microsoft.com/security/bulletin/ms09-015)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
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
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 與 Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2233a4d2-7c8a-4c89-b020-100d9afb43c8)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=42509f5a-d0f9-444a-9445-5eabdb555011)  
(重大)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=c1b4cd76-1dd6-43fa-bb9a-20c428985bfd)\*\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=f73a3669-c17f-4b18-8456-96cb7d52ed86)  
(重要)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=6a45dbd0-0520-4d9b-b76e-3f5109dd310d)  
(重要)
</td>
<td style="border:1px solid black;">
MSDTC 交易設施更新：  
[Windows Server 2003 Service Pack 1 與 Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=25adec10-db8c-4cac-bf74-2c784678150a)  
(KB952004)  
(重要)  
Windows 服務隔離更新：  
[Windows Server 2003 Service Pack 1 與 Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=42aba890-8b76-4c5a-8fb6-609797d19831)  
(KB956572)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=992bb0cd-fbc7-4a7c-9088-f7f9d9a3ead0)  
(中度)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=323f4211-5add-4e02-bce1-e5a1b489982c)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7373ea32-bc2e-49f1-8b9f-4eeda5acc74c)  
(重大)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=f0e1e1db-94a5-451c-ab11-6b431fa065f1)\*\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=03a9d581-2bd5-4151-9826-17b96e16f606)  
(重要)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=60ccc1d6-ea31-420c-b630-d7878a8dc527)  
(重要)
</td>
<td style="border:1px solid black;">
MSDTC 交易設施更新：  
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b014c399-f404-4cb2-8f9d-864df382efeb)  
(KB952004)  
(重要)  
Windows 服務隔離更新：  
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a0609f65-82d9-4d82-9f48-f3266e8de123)  
(KB956572)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f0a58e8c-7d63-4d7d-ba95-b3787cf408f0)  
(中度)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP1 for Itanium-based Systems 和 Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP1 和適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=e840b9cb-f1f4-482a-aa07-eb6b42b477c4)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP1 和適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=05e33cc5-cff6-4c71-be71-285f66a95e01)  
(重大)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=8f36c215-fa8a-40c2-b680-6b1fece03b8d)\*\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=53d13c07-80b0-4f05-b372-a2dac17e6157)  
(重要)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0abaa2fb-7c4f-4149-993d-1575888bfc84)  
(重要)
</td>
<td style="border:1px solid black;">
MSDTC 交易設施更新：  
[Windows Server 2003 SP1 for Itanium-based Systems 和 Windows Server 2003 SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=6ada372b-ba17-433e-b022-d2c57b35af8a)  
(KB952004)  
(重要)  
Windows 服務隔離更新：  
[Windows Server 2003 SP1 for Itanium-based Systems 和 Windows Server 2003 SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=fda8837c-e5d2-4489-9b44-4c24a1102e77)  
(KB956572)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP1 和適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=00c6479d-f81f-445d-b8e4-7b71d77d540a)  
(中度)
</td>
</tr>
<tr>
<th colspan="7">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-013**](http://technet.microsoft.com/security/bulletin/ms09-013)
</td>
<td style="border:1px solid black;">
[**MS09-011**](http://technet.microsoft.com/security/bulletin/ms09-011)
</td>
<td style="border:1px solid black;">
[**MS09-014**](http://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-012**](http://technet.microsoft.com/security/bulletin/ms09-012)
</td>
<td style="border:1px solid black;">
[**MS09-015**](http://technet.microsoft.com/security/bulletin/ms09-015)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
無
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
[**中度**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 和 Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=f071d770-3b6b-4040-9911-d4de8cde4c68)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d743849d-f3b5-4114-adef-ade2716d55ac)  
(重大)
</td>
<td style="border:1px solid black;">
MSDTC 交易設施更新：  
[Windows Vista 和 Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=f111b99a-e555-4f29-8d1f-e9ec03d5cf1f)  
(KB952004)  
(重要)  
Windows 服務隔離更新：  
[Windows Vista 和 Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d0ea1598-45cb-4c79-8945-caae98969675)  
(KB956572)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=2b672d45-f33b-4edc-9f22-2f2c8c726a8b)  
(中度)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7ceef2d0-f316-48d1-aecc-d74f91cc5e1f)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d191c8dc-a965-4a6a-b6d8-1470505eb55f)  
(重大)
</td>
<td style="border:1px solid black;">
MSDTC 交易設施更新：  
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=fa153bdc-6b48-4df2-9e5e-abacd6da782c)  
(KB952004)  
(重要)  
Windows 服務隔離更新：  
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=6dd82f4b-bb33-41ec-90a7-9ef91329b240)  
(KB956572)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7576e7d5-5bb1-4a53-b568-1ee0500ce721)  
(中度)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-013**](http://technet.microsoft.com/security/bulletin/ms09-013)
</td>
<td style="border:1px solid black;">
[**MS09-011**](http://technet.microsoft.com/security/bulletin/ms09-011)
</td>
<td style="border:1px solid black;">
[**MS09-014**](http://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-012**](http://technet.microsoft.com/security/bulletin/ms09-012)
</td>
<td style="border:1px solid black;">
[**MS09-015**](http://technet.microsoft.com/security/bulletin/ms09-015)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
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
[**中度**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008](http://www.microsoft.com/downloads/details.aspx?familyid=4c36548f-c8c9-4318-91e2-9e0501339548)\*  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e2c6313c-3ba9-4f7c-b259-b4582a390146)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
MSDTC 交易設施更新：  
[適用於 32 位元系統的 Windows Server 2008](http://www.microsoft.com/downloads/details.aspx?familyid=9e3c7b52-65a7-42fb-beb5-1b374934737f)\*  
(KB952004)  
(重要)  
Windows 服務隔離更新：  
[適用於 32 位元系統的 Windows Server 2008](http://www.microsoft.com/downloads/details.aspx?familyid=d58702af-bbf8-4f1b-ae72-ced9ef23d581)\*  
(KB956572)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008](http://www.microsoft.com/downloads/details.aspx?familyid=6b73cf5e-66fe-4b7d-95fc-91a1c262c1e5)\*  
(中度)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008](http://www.microsoft.com/downloads/details.aspx?familyid=1c3f0997-a8a9-4340-ae0c-2c4d6792c65c)\*  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=ebbade9d-704c-440b-8796-6d64225ac01a)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
MSDTC 交易設施更新：  
[適用於 x64 型系統的 Windows Server 2008](http://www.microsoft.com/downloads/details.aspx?familyid=eebb4d4d-29d2-4247-8cbb-63a3b17585ec)\*  
(KB952004)  
(重要)  
Windows 服務隔離更新：  
[適用於 x64 型系統的 Windows Server 2008](http://www.microsoft.com/downloads/details.aspx?familyid=20bf4e9b-909b-4bc3-ae43-322d74a4f1c3)\*  
(KB956572)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008](http://www.microsoft.com/downloads/details.aspx?familyid=7e60847c-b341-4c38-bc25-2e3cf2d4ae14)\*  
(中度)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008](http://www.microsoft.com/downloads/details.aspx?familyid=0885b3b0-b78e-4980-902d-dff3886bcaac)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=1b04aa6f-b787-4122-bf82-0d150618fe7a)  
(重要)
</td>
<td style="border:1px solid black;">
MSDTC 交易設施更新：  
[適用於 Itanium 型系統的 Windows Server 2008](http://www.microsoft.com/downloads/details.aspx?familyid=cc383c24-b0f6-47c1-9e89-6a378b09e82f)  
(KB952004)  
(重要)  
Windows 服務隔離更新：  
[適用於 Itanium 型系統的 Windows Server 2008](http://www.microsoft.com/downloads/details.aspx?familyid=bcc2b18f-67db-4109-a9f4-764f985423ee)  
(KB956572)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008](http://www.microsoft.com/downloads/details.aspx?familyid=de1c2b4b-af47-4b9a-8363-720e5527573c)  
(中度)
</td>
</tr>
</table>
 
**Windows Server 2008 注意事項**

**\*Windows Server 2008 Server Core 安裝會受影響。** 對於受支援的 Windows Server 2008 版本，無論 Windows Server 2008 是否使用 Server Core 安裝選項，這個更新均以相同的嚴重性等級套用。 如需這個安裝選項的詳細資訊，請參閱 [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**\*\*Windows Server 2008 Server Core 安裝不受影響。** 如果 Windows Server 2008 是使用 Server Core 安裝選項所安裝，則這項更新解決的弱點並不會影響受支援的 Windows Server 2008 版本。 如需這個安裝選項的詳細資訊，請參閱 [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**MS09-010 的注意事項**

另請參閱＜Microsoft Office 套件及軟體＞小節，瞭解更多更新檔案。 本公告涉及 Windows 作業系統和元件與 Microsoft Office 套件及軟體。

**MS09-011 的注意事項**

\*\*\*DirectX 9.0 的更新也適用於 DirectX 9.0a、DirectX 9.0b 及 DirectX 9.0c。

#### Microsoft Office 套件及軟體

 
<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="3">
Microsoft Office 套件、系統和元件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-009**](http://technet.microsoft.com/security/bulletin/ms09-009)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2000 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=95876927-e612-414c-bdec-3632a3100415)  
(KB921606)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2000 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=3dc8b670-25a5-4f46-b7de-12bc693b628a)  
(KB959964)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e1db55c6-78fb-498d-89a5-9ad54d971546)  
(KB933399)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=9a52bf4b-05f6-4b73-94b9-28ed7e20f86c)  
(KB959988)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=d9dbfa63-c0cb-4c84-9b8a-6e52568045b0)  
(KB959995)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
2007 Microsoft Office System Service Pack 1
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=50d8630b-1365-4007-81a0-18c0d6d4b86e)\*  
(KB959997)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office for Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-009**](http://technet.microsoft.com/security/bulletin/ms09-009)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=52271140-89be-4b9c-baa2-cea09097d703)  
(KB968695)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=f6e407eb-11a5-433f-8006-4b822953ca98)  
(KB968694)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
其他 Office 軟體
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-009**](http://technet.microsoft.com/security/bulletin/ms09-009)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Excel Viewer
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=c72e6087-b48f-4d2d-8366-01d9f5ff6b6c)  
(KB959993)  
(重要)  
[Microsoft Office Excel Viewer](http://www.microsoft.com/downloads/details.aspx?familyid=58b3929c-5373-47a4-aa97-66d179758792)  
(KB960000)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Word、Excel 及 PowerPoint 2007 檔案格式的 Microsoft Office 相容性套件
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=05f7c517-e551-4dcd-b24a-5d548f2d09cf)  
(KB960003)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Converter Pack
</td>
<td style="border:1px solid black;">
[Microsoft Office Converter Pack](http://www.microsoft.com/downloads/details.aspx?familyid=d763fae3-b2af-47f9-a554-ec786766b3c3)  
(KB960476)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
</table>
 
**MS09-010 的注意事項**

另請參閱＜Microsoft 作業系統與元件＞一節，瞭解更多更新檔案。 本公告涉及 Windows 作業系統和元件與 Microsoft 伺服器軟體。

**MS09-009 的注意事項**

\*針對 Microsoft Office Excel 2007 Service Pack 1，客戶也需安裝適用於 Word、Excel 及 PowerPoint 2007 檔案格式的 Microsoft Office 相容性套件 Service Pack 1 的安全性更新，以免受此公告中描述的弱點影響。

#### Microsoft 伺服器和安全性軟體

 
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
Microsoft Forefront
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-016**](http://technet.microsoft.com/security/bulletin/ms09-016)
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
Microsoft Forefront Threat Management Gateway
</td>
<td style="border:1px solid black;">
[Microsoft Forefront Threat Management Gateway, Medium Business Edition](http://www.microsoft.com/downloads/details.aspx?familyid=6abf9fb4-42d0-4c67-935f-8dc67850148b)\*  
(KB968075)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Internet Security and Acceleration Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-016**](http://technet.microsoft.com/security/bulletin/ms09-016)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server 2004
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2004 Standard Edition Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=adf623fa-2d74-4f2a-9835-4b8debdb0e1b)\*\*  
(KB960995)  
(重要)  
[Microsoft Internet Security and Acceleration Server 2004 Enterprise Edition Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=d1d55ab6-3de5-4811-9693-8d43f49f5fe8)  
(KB960995)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server 2006
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2006](http://www.microsoft.com/downloads/details.aspx?familyid=eda30bcc-0582-4f60-a4c5-ea5000b7c770)  
(KB968078)  
(重要)  
[Microsoft Internet Security and Acceleration Server 2006 支援性更新](http://www.microsoft.com/downloads/details.aspx?familyid=eda30bcc-0582-4f60-a4c5-ea5000b7c770)  
(KB968078)  
(重要)  
[Microsoft Internet Security and Acceleration Server 2006 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=eda30bcc-0582-4f60-a4c5-ea5000b7c770)  
(KB968078)  
(重要)
</td>
</tr>
</table>
 
**MS09-016 的注意事項**

\*Microsoft Forefront Threat Management Gateway, Medium Business Edition 能以獨立產品提供，也能以 Windows Essential Business Server 2008 元件提供。

\*\*Microsoft ISA Server 2004 Standard Edition 是以獨立產品提供。 Microsoft ISA Server 2004 Standard Edition 能以 Windows Small Business Server 2003 Enterprise Edition Service Pack 1 元件提供，也能以 Windows Small Business Server 2003 R2 Enterprise Edition 元件提供。

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和安全性更新。 如需更多資訊，請參閱 [TechNet 更新管理中心](http://www.microsoft.com/taiwan/technet/updatemanagement/default.mspx)。 [TechNet Security Center](http://www.microsoft.com/taiwan/technet/security/default.mspx) 提供 Microsoft 產品安全性的其他資訊。 消費者可以造訪[在家上網的安全性](http://www.microsoft.com/taiwan/athome/security/default.mspx)網站，只要按一下 \[最新安全性更新\] 即可在此網站取得此資訊。

安全性更新可以從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)、[Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)及 [Office Update](http://office.microsoft.com/zh-tw/downloads/default.aspx)取得。 安全性更新也可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得。 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。

最後，您可以從 [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) 下載安全性更新。 Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括安全性更新、驅動程式和 Service Pack。 只要以安全性公告編號 (例如：MS07-036) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。 如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](http://go.microsoft.com/fwlink/?linkid=97900)。

**偵測與部署指南**

Microsoft 已提供本月安全性更新之偵測與部署指南。 此指南還能幫助 IT 專業人員瞭解如何使用各項工具來協助部署安全性更新，像是 Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office Detection Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool (加強版安全性更新清查工具，ESUIT)。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 910723](http://support.microsoft.com/kb/910723/zh-tw)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少安全性更新以及一般安全性設定錯誤的狀況。 如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) 網站 (英文)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速可靠地將 Windows 2000 作業系統及更新系統版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 等最新的重大更新與安全性更新部署到 Windows 2000 及更新作業系統版本中。

如需更多關於利用 Windows Server Update Services 部署安全性更新的資訊，請造訪 [Windows Server Update Services](http://www.microsoft.com/taiwan/windowsserversystem/updateservices/evaluation/overview.mspx) 網站。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。 現已推出新版的 SMS，System Center Configuration Manager 2007；另請參閱 [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)。如需更多有關系統管理員如何能使用 SMS 2003 部署安全性更新的資訊，請參閱 [SMS 2003 安全性修補程式管理](http://www.microsoft.com/taiwan/smserver/evaluation/capabilities/patch.htm) (英文)。 SMS 2.0 使用者也可以利用 [SMS 軟體更新服務功能套件](http://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/suspack/default.htm)來協助部署安全性更新。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server](http://www.microsoft.com/taiwan/smserver/)。

**注意：**SMS 使用 Microsoft Baseline Security Analyzer 及 Microsoft Office Detection Tool，為安全性公告更新的偵測及部署作業提供相當廣泛的支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可以用 Elevated Rights Deployment Tool (隨 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/taiwan/smserver/downloads/2003/adminpack.htm) (英文) 和 [SMS 管理功能套件](http://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/adminpack/default.htm) (英文) 提供) 來安裝這些更新。

**Update Compatibility Evaluator 和應用程式相容性工具組**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。 這可能會觸發不相容性，而拉長部署安全性更新的時間。 您可以使用 [Application Compatibility Toolkit 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 隨附的 [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 元件，針對所安裝的應用程式，簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Microsoft Windows Vista、Windows Update、Microsoft 安全性更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非安全性、高優先順序更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](http://support.microsoft.com/kb/894199/zh-tw)： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。 其中也包括所有 Windows 的內容。
-   [適用於 Microsoft 產品 (除了 Microsoft Windows 以外) 的全新、修訂版以及已發行的更新](http://technet.microsoft.com/en-us/wsus/dd573344.aspx)。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的安全性保護，Microsoft 將在每月發行安全性更新之前，提前向重要安全性軟體提供者提供弱點資訊。 安全性軟體提供者可利用此弱點資訊，透過其安全性軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。 如果要判斷是否有安全性軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://www.microsoft.com/security/msrc/mapp/partners.mspx)上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 安全性策略與社群

**更新程式管理策略**

[更新管理安全性指南](http://www.microsoft.com/taiwan/technet/security/topics/patchmanagement.mspx) (英文) 提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](http://support.microsoft.com/kb/913086/zh-tw)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](http://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](http://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 Fortinet 公司 [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com/) 的 Haifei Li 回報 ms09-009 中描述的問題
-   感謝 [VeriSign iDefense Labs](http://labs.idefense.com/) 的 Sean Larsson 和 Jun Mao 回報 MS09-010 中描述的問題
-   感謝 Fortinet 公司 [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com/) 的研究人員回報 MS09-010 中描述的問題
-   感謝 [VeriSign iDefense Labs](http://labs.idefense.com/) 的研究人員回報 MS09-010 中描述的問題
-   感謝 [Kryptos Logic](http://www.kryptoslogic.com/) 的 Piotr Bania 回報 MS09-011 中描述的問題
-   感謝 [Argeniss](http://www.argeniss.com/) 的 Cesar Cerrudo 回報 MS09-012 中描述的多個問題
-   感謝 [iSIGHT Partners](http://www.isightpartners.com/) 的 Greg MacManus 回報 MS09-013 中描述的問題。
-   感謝 [Google Inc.](http://www.google.com/) 的 Wan-Teh Chang 和 Cem Paya 回報 MS09-013 中描述的問題
-   感謝 [Aviv Raff](http://aviv.raffon.net/) 回報 MS09-014 中描述的問題。
-   感謝 [Google Inc.](http://www.google.com/) 的 Michal Zalewski 回報 MS09-014 中描述的問題。
-   感謝 [iSIGHT Partners Labs](http://www.isightpartners.com/) 的 Ivan Fratric 回報 MS09-014 中描述的問題
-   感謝 [Google Inc.](http://www.google.com/) 的 Skylined 回報 MS09-014 中描述的問題。
-   感謝 [VenusTech](http://www.venustech.com.cn/) 的 ADLab 回報 MS09-014 中描述的問題。
-   感謝 [Aviv Raff](http://aviv.raffon.net/) 回報 MS09-015 中描述的問題。
-   感謝紐約州資訊長/技術處回報 MS09-016 中描述的問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可洽詢[安全性支援](http://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 以取得技術支援。 與安全性更新有關的支援電話不另外收費。 如需更多可用支援選項的資訊，請參閱 [Microsoft 技術支援服務](http://support.microsoft.com/?ln=zh-tw)。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與安全性更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](http://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2009 年 4 月 15 日)： 公告摘要發行。

*Built at 2014-04-18T01:50:00Z-07:00*
