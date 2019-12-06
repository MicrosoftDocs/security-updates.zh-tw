---
TOCTitle: 'MS09-AUG'
Title: 2009 年 8 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms09-aug'
ms:contentKeyID: 61237690
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms09-aug(v=Security.10)'
---

2009 年 8 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2009年8月12日 | 更新: 2009年9月9日

**版本:** 3.0

此公告摘要列出 2009 年 8 月份發行之安全性公告。

發行 2009 年 8 月份公告之後，此公告摘要將取代原先於 2009 年 8 月 6 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](https://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2009 年 8 月 12 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。 [立即註冊參加 8 月份安全性公告網路廣播](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032407484&eventcategory=4&culture=en-us&countrycode=us)。 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](https://technet.microsoft.com/security/bulletin/summary)。

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-043">MS09-043</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Web 元件的弱點可能會允許遠端執行程式碼 (957638)</strong><br />
<br />
這個安全性更新可解決 Microsoft Office Web 元件中數項未公開報告的弱點，這些弱點可在使用者檢視蓄意製作的網頁時，允許遠端執行程式碼。 成功利用這類弱點的攻擊者可以取得與本機使用者相同的使用者權限。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office、Microsoft Visual Studio、Microsoft ISA Server、Microsoft BizTalk Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-044">MS09-044</a></td>
<td style="border:1px solid black;"><strong>Remote Desktop Connection 中的弱點可能會允許遠端執行程式碼 (970927)</strong><br />
<br />
這個安全性更新可解決 Microsoft Remote Desktop Connection 中兩項未公開報告的弱點。 如果攻擊者成功地說服終端機服務的使用者連線到惡意的 RDP 伺服器，或如果使用者造訪可利用此弱點的蓄意製作網站，則此弱點可能會允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、適用於 Mac 的 Remote Desktop Connection 用戶端</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-039">MS09-039</a></td>
<td style="border:1px solid black;"><strong>WINS 中的弱點可能會允許遠端執行程式碼 (969883)</strong><br />
<br />
這個安全性更新可解決 Windows 網際網路名稱服務 (WINS) 中兩項未公開報告的弱點。 如果使用者在執行 WINS 服務的受影響系統上接收到蓄意製作的 WINS 複寫封包，則前述任一弱點都可能會允許遠端執行程式碼。 依照預設，WINS 並未安裝於任何受影響的作業系統版本上。 唯有手動安裝此元件的客戶，才可能受此問題影響。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-038">MS09-038</a></td>
<td style="border:1px solid black;"><strong>Windows Media 檔案處理中的弱點可能會允許遠端執行程式碼 (971557)</strong><br />
<br />
這個安全性更新可解決 Windows Media 檔案處理中兩項未公開報告的弱點。 如果使用者開啟蓄意製作的 AVI 檔案，則前述任一弱點可能會允許遠端執行程式碼。 如果使用者以系統管理的使用者權限登入，成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-037">MS09-037</a></td>
<td style="border:1px solid black;"><strong>Microsoft 作用中範本程式庫 (ATL) 的弱點可能會允許遠端執行程式碼 (973908)</strong><br />
<br />
這個安全性更新可解決 Microsoft 作用中範本程式庫 (ATL) 數個未公開報告的弱點。 如果使用者載入了惡意網站上蓄意製作的元件或控制項，這些弱點可能會允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-041">MS09-041</a></td>
<td style="border:1px solid black;"><strong>Workstation 服務中的弱點可能會允許提高權限 (971657)</strong><br />
<br />
這個安全性更新可解決 Windows Workstation 服務中一項未公開報告的弱點。 如果攻擊者建立蓄意製作的 RPC 訊息，並將該訊息送往受影響的系統，則此弱點可能允許提高權限。 成功利用此弱點的攻擊者可執行任意程式碼，並取得受影響之系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 攻擊者必須擁有易受影響之系統的有效登入認證，才能利用這項弱點。 匿名使用者無法利用這個弱點。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-040">MS09-040</a></td>
<td style="border:1px solid black;"><strong>訊息佇列中的弱點可能會允許權限提高 (971032)</strong><br />
<br />
這個安全性更新可解決 Windows 訊息佇列服務 (MSMQ) 的一項未公開報告的弱點。 如果使用者在受影響的 MSMQ 服務收到蓄意製作的要求，則該弱點可能會允許權限提高。 依據預設，不會將訊息佇列元件安裝於任何受影響的作業系統版本上，且唯有具備系統管理權限的使用者才能啟用。 只有手動安裝 Message Queuing 元件的客戶可能會受此問題影響。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-036">MS09-036</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows 中的 ASP.NET 的弱點可能會造成拒絕服務 (970957)</strong><br />
<br />
這個安全性更新可解決 Microsoft Windows 上的 Microsoft .NET Framework 元件中，一項未公開報告的拒絕服務弱點。 僅在受影響版本的 Microsoft Windows 裝有 Internet Information Services (IIS) 7.0，且 ASP.NET 設定使用整合模式時，才可以利用此弱點。 攻擊者可蓄意製作匿名 HTTP 要求，導致受影響的網頁伺服器無法回應，直到重新啟動相關的應用程式集區為止。 以傳統模式執行 IIS 7.0 的客戶不會受到此弱點影響。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
拒絕服務</td>
<td style="border:1px solid black;">不需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-042">MS09-042</a></td>
<td style="border:1px solid black;"><strong>Telnet 中的弱點可能允許遠端執行程式碼 (960859)</strong><br />
<br />
這個安全性更新可解決 Microsoft Telnet 服務中一項公開報告的弱點。 此弱點可讓攻擊者取得認證，然後使用認證再度登入受影響的系統。 攻擊者隨後可以在系統上取得與登入使用者相同的使用者權限。 這種情況最終可能會允許在受影響的系統上遠端執行程式碼。 成功地利用這些弱點的攻擊者可以安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
遠端執行程式碼</td>
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
  
請用這個表格來瞭解您可能需要安裝的每個安全性更新，與 30 天內已發行的可利用程式碼受影響之可能性。 您應該檢閱下列的每個評估，按照特定的設定，將部署以優先次序排序。 如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](https://technet.microsoft.com/zh-tw/security/cc998259.aspx)。
  
| 公告編號                                                            | 公告標題                                                                 | CVE ID                                                                           | 弱點索引評估                                                                                            | 主要重點                                                                                                                                                                                                      |  
|---------------------------------------------------------------------|--------------------------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-036](https://technet.microsoft.com/security/bulletin/ms09-036) | Microsoft Windows 中的 ASP.NET 的弱點可能會造成拒絕服務 (970957)         | [CVE-2009-1536](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1536) | [**3**](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 可能撰寫出拒絕服務工具。 但是，不太可能撰寫出可利用此漏洞的程式碼來進行遠端執行程式碼。                                                                                                                       |  
| [MS09-037](https://technet.microsoft.com/security/bulletin/ms09-037) | Microsoft 作用中範本程式庫 (ATL) 的弱點可能會允許遠端執行程式碼 (973908) | [CVE-2008-0015](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-0015) | [**1**](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | **此弱點目前在網際網路生態系統中遭到利用。**                                                                                                                                                                  |  
| [MS09-037](https://technet.microsoft.com/security/bulletin/ms09-037) | Microsoft 作用中範本程式庫 (ATL) 的弱點可能會允許遠端執行程式碼 (973908) | [CVE-2008-0020](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-0020) | [**1**](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                                                                                          |  
| [MS09-037](https://technet.microsoft.com/security/bulletin/ms09-037) | Microsoft 作用中範本程式庫 (ATL) 的弱點可能會允許遠端執行程式碼 (973908) | [CVE-2009-0901](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0901) | 無                                                                                                      | (此弱點已經在[七月份公告摘要](https://technet.microsoft.com/security/bulletin/ms09-jul)中獲得弱點索引評估。 這是因為此弱點是由 [MS09-035](https://technet.microsoft.com/security/bulletin/ms09-035) 首先提出。) |  
| [MS09-037](https://technet.microsoft.com/security/bulletin/ms09-037) | Microsoft 作用中範本程式庫 (ATL) 的弱點可能會允許遠端執行程式碼 (973908) | [CVE-2009-2493](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493) | 無                                                                                                      | (此弱點已經在[七月份公告摘要](https://technet.microsoft.com/security/bulletin/ms09-jul)中獲得弱點索引評估。 這是因為此弱點是由 [MS09-035](https://technet.microsoft.com/security/bulletin/ms09-035) 首先提出。) |  
| [MS09-037](https://technet.microsoft.com/security/bulletin/ms09-037) | Microsoft 作用中範本程式庫 (ATL) 的弱點可能會允許遠端執行程式碼 (973908) | [CVE-2009-2494](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2494) | [**1**](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                                                                                          |  
| [MS09-038](https://technet.microsoft.com/security/bulletin/ms09-038) | Windows Media 檔案處理中的弱點可能會允許遠端執行程式碼 (971557)          | [CVE-2009-1545](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1545) | [**2**](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                                                                                                          |  
| [MS09-038](https://technet.microsoft.com/security/bulletin/ms09-038) | Windows Media 檔案處理中的弱點可能會允許遠端執行程式碼 (971557)          | [CVE-2009-1546](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1546) | [**2**](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                                                                                                          |  
| [MS09-039](https://technet.microsoft.com/security/bulletin/ms09-039) | WINS 中的弱點可能會允許遠端執行程式碼 (969883)                           | [CVE-2009-1923](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1923) | [**1**](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                                                                                          |  
| [MS09-039](https://technet.microsoft.com/security/bulletin/ms09-039) | WINS 中的弱點可能會允許遠端執行程式碼 (969883)                           | [CVE-2009-1924](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1924) | [**2**](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | 以 Windows 2000 作為目標更可能成功利用。                                                                                                                                                                      |  
| [MS09-040](https://technet.microsoft.com/security/bulletin/ms09-040) | 訊息佇列中的弱點可能會允許權限提高 (971032)                              | [CVE-2009-1922](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1922) | [**1**](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | 不可能遠端攻擊此弱點。                                                                                                                                                                                        |  
| [MS09-041](https://technet.microsoft.com/security/bulletin/ms09-041) | Workstation 服務中的弱點可能會允許提高權限 (971657)                      | [CVE-2009-1544](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1544) | [**1**](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | 攻擊者必須擁有驗證，才能利用這項弱點。                                                                                                                                                                        |  
| [MS09-042](https://technet.microsoft.com/security/bulletin/ms09-042) | Telnet 中的弱點可能允許遠端執行程式碼 (960859)                           | [CVE-2009-1930](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1930) | [**1**](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | 此弱點與之前的 NTLM 認證反映弱點相似，存在可利用此漏洞的程式碼。                                                                                                                                              |  
| [MS09-043](https://technet.microsoft.com/security/bulletin/ms09-043) | Microsoft Office Web 元件的弱點可能會允許遠端執行程式碼 (957638)         | [CVE-2009-0562](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0562) | [**1**](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                                                                                          |  
| [MS09-043](https://technet.microsoft.com/security/bulletin/ms09-043) | Microsoft Office Web 元件的弱點可能會允許遠端執行程式碼 (957638)         | [CVE-2009-1136](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1136) | [**1**](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | 已公開發佈可利用此弱點的程式碼。                                                                                                                                                                              |  
| [MS09-043](https://technet.microsoft.com/security/bulletin/ms09-043) | Microsoft Office Web 元件的弱點可能會允許遠端執行程式碼 (957638)         | [CVE-2009-1534](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1534) | [**1**](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                                                                                          |  
| [MS09-043](https://technet.microsoft.com/security/bulletin/ms09-043) | Microsoft Office Web 元件的弱點可能會允許遠端執行程式碼 (957638)         | [CVE-2009-2496](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2496) | [**1**](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                                                                                          |  
| [MS09-044](https://technet.microsoft.com/security/bulletin/ms09-044) | Remote Desktop Connection 中的弱點可能會允許遠端執行程式碼 (970927)      | [CVE-2009-1133](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1133) | [**2**](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                                                                                                          |  
| [MS09-044](https://technet.microsoft.com/security/bulletin/ms09-044) | Remote Desktop Connection 中的弱點可能會允許遠端執行程式碼 (970927)      | [CVE-2009-1929](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1929) | [**1**](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                                                                                          |
  
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
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="9">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-044**](https://technet.microsoft.com/security/bulletin/ms09-044)
</td>
<td style="border:1px solid black;">
[**MS09-039**](https://technet.microsoft.com/security/bulletin/ms09-039)
</td>
<td style="border:1px solid black;">
[**MS09-038**](https://technet.microsoft.com/security/bulletin/ms09-038)
</td>
<td style="border:1px solid black;">
[**MS09-037**](https://technet.microsoft.com/security/bulletin/ms09-037)
</td>
<td style="border:1px solid black;">
[**MS09-041**](https://technet.microsoft.com/security/bulletin/ms09-041)
</td>
<td style="border:1px solid black;">
[**MS09-040**](https://technet.microsoft.com/security/bulletin/ms09-040)
</td>
<td style="border:1px solid black;">
[**MS09-036**](https://technet.microsoft.com/security/bulletin/ms09-036)
</td>
<td style="border:1px solid black;">
[**MS09-042**](https://technet.microsoft.com/security/bulletin/ms09-042)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[RDP 5.2 版](https://www.microsoft.com/download/details.aspx?familyid=027e757d-08d5-4932-b8c4-52ee1be1c864)\*\*\*  
(KB958471) 和 [RDP 5.0 版](https://www.microsoft.com/download/details.aspx?familyid=027e757d-08d5-4932-b8c4-52ee1be1c864) (KB958470)  
(重大)  
[RDP 5.1 版](https://www.microsoft.com/download/details.aspx?familyid=ae72782e-920f-4176-a27b-c3b91d50c7d2)\*\*\*\*  
(KB958470)  
(重大)  
[RDP 5.2 版](https://www.microsoft.com/download/details.aspx?familyid=ae72782e-920f-4176-a27b-c3b91d50c7d2)\*\*\*\*  
(KB958470)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=b5b9228a-66c0-49e6-afde-cc2825a6851f)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=5f80bf0b-898c-46ca-b20c-21e0e729c332)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 5.5 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6f9fcbe9-8496-4d23-8a16-b334157688c2)  
(KB973354)  
(重大)  
[Microsoft Outlook Express 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=f340af34-b9a0-44fb-b595-dbb346c727bf)  
(KB973354)  
(重大)  
[Windows Media Player 9](https://www.microsoft.com/download/details.aspx?familyid=bd7c9fc4-61cb-4c23-9961-6d63f234731c)  
(KB973354)  
(重大)  
[Windows ATL Component](https://www.microsoft.com/download/details.aspx?familyid=c773149a-f4fc-486a-b718-6b8ff7a36ae2)  
(KB973507)  
(重大)  
[DHTML 編輯元件 ActiveX 控制項](https://www.microsoft.com/download/details.aspx?familyid=223e25d2-83d7-4cb7-85c4-46a42b8110e0)  
(KB973869)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=8ed8bad7-2885-452c-9c34-3982cd498be8)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=240977d6-3581-4058-b9f1-7847e4edcf8a)  
(重要)
</td>
</tr>
<tr>
<th colspan="9">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-044**](https://technet.microsoft.com/security/bulletin/ms09-044)
</td>
<td style="border:1px solid black;">
[**MS09-039**](https://technet.microsoft.com/security/bulletin/ms09-039)
</td>
<td style="border:1px solid black;">
[**MS09-038**](https://technet.microsoft.com/security/bulletin/ms09-038)
</td>
<td style="border:1px solid black;">
[**MS09-037**](https://technet.microsoft.com/security/bulletin/ms09-037)
</td>
<td style="border:1px solid black;">
[**MS09-041**](https://technet.microsoft.com/security/bulletin/ms09-041)
</td>
<td style="border:1px solid black;">
[**MS09-040**](https://technet.microsoft.com/security/bulletin/ms09-040)
</td>
<td style="border:1px solid black;">
[**MS09-036**](https://technet.microsoft.com/security/bulletin/ms09-036)
</td>
<td style="border:1px solid black;">
[**MS09-042**](https://technet.microsoft.com/security/bulletin/ms09-042)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 及 Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 上的 RDP 5.1 版：](https://www.microsoft.com/download/details.aspx?familyid=2a8830dd-8fb3-4556-a6e7-2c237235357f)  
(KB958470)  
(重大)  
[適用於 Windows XP Service Pack 2 的 RDP 5.2 版](https://www.microsoft.com/download/details.aspx?familyid=2a8830dd-8fb3-4556-a6e7-2c237235357f)\*\*\*\*  
(KB958469)  
(重大)  
[Windows XP Service Pack 3 上的 RDP 5.2 版](https://www.microsoft.com/download/details.aspx?familyid=cf9f9898-10c8-45ab-9df3-85e0b37e6046)  
(KB958469)  
(重大)  
[適用於 Windows XP Service Pack 2 的 RDP 6.0 版](https://www.microsoft.com/download/details.aspx?familyid=d1f82d76-eeb2-4ff4-9d2c-46882f214719)\*\*\*\*  
(KB956744)  
(重要)  
[RDP 6.1 版](https://www.microsoft.com/download/details.aspx?familyid=d1f82d76-eeb2-4ff4-9d2c-46882f214719)\*\*\*\*  
(KB956744)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 與 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=2e8a68ee-eb24-424c-b084-450636ccaeec)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](https://www.microsoft.com/download/details.aspx?familyid=c67b5506-00ea-47cc-a0e8-897057b7380c)  
(KB973354)  
(重大)  
[Windows Media Player 9、Windows Media Player 10 及 Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=34b2b14d-5811-4635-ba83-f837dcb03d04)  
(KB973540)  
(重大)  
(僅限 Windows XP Service Pack 2)  
[Windows Media Player 9、Windows Media Player 10 及 Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=ec84c98b-6bc7-442f-9280-d6e204280b2f)  
(KB973540)  
(重大)  
(僅限 Windows XP Service Pack 3)  
[Windows ATL Component](https://www.microsoft.com/download/details.aspx?familyid=4b4c6fc5-e8e6-4d89-a181-e231240468f9)  
(KB973507)  
(重大)  
[DHTML 編輯元件 ActiveX 控制項](https://www.microsoft.com/download/details.aspx?familyid=bdfcd0c3-7c18-4e63-91dd-d8f82cd89592)  
(KB973869  
(重大)  
[Microsoft MSWebDVD ActiveX 控制項](https://www.microsoft.com/download/details.aspx?familyid=8b71bcc9-5146-4afc-8847-0af21d7fad36)  
(KB973769)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 與 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=9c0e5bff-c248-4e87-a83b-82ba52f5299d)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=93490aa7-9985-4658-b0d7-88fb3f27ada0)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 與 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=b3331388-1e52-4924-b512-23275a8fde84)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2 上的 RDP 5.2 版](https://www.microsoft.com/download/details.aspx?familyid=948da99a-44ed-4390-b1b4-7ed3f15a9cda)  
(KB958469)  
(重大)  
[適用於 Windows XP Professional x64 Edition Service Pack 2 的 RDP 6.1 版](https://www.microsoft.com/download/details.aspx?familyid=5061615f-fa8f-465f-ac8f-393998b7e91b)\*\*\*\*  
(KB956744)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a1ff2ace-b9dc-4cf3-a151-ac6959bcb3a6)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](https://www.microsoft.com/download/details.aspx?familyid=ede1a73a-e303-435e-a2c7-0281ce2370da)  
(KB973354)  
(重大)  
[Windows Media Player 10](https://www.microsoft.com/download/details.aspx?familyid=bb98187a-8db9-47e4-88ac-15544c5268f6)  
(KB973540)  
(重大)  
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=9e8b9027-4407-4c31-a2ba-9e094557d467)  
(KB973540)  
(重大)  
[Windows ATL Component](https://www.microsoft.com/download/details.aspx?familyid=2f2b93fc-f977-4f23-af90-c27f744fad0a)  
(KB973507)  
(重大)  
[DHTML 編輯元件 ActiveX 控制項](https://www.microsoft.com/download/details.aspx?familyid=d04a6959-41a4-4a87-b3ad-7455d8fe8b99)  
(KB973869  
(重大)  
[Microsoft MSWebDVD ActiveX 控制項](https://www.microsoft.com/download/details.aspx?familyid=85b2dcdb-cea9-4c4a-8ebd-50264e781ade)  
(KB973769)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7b64a454-d383-47e3-b469-b87e2b3c1a9f)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=12e6be68-dc87-450e-927b-3c9b6873eb13)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a6ee7af3-3e39-4866-a893-92bf1c786cd4)  
(重要)
</td>
</tr>
<tr>
<th colspan="9">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-044**](https://technet.microsoft.com/security/bulletin/ms09-044)
</td>
<td style="border:1px solid black;">
[**MS09-039**](https://technet.microsoft.com/security/bulletin/ms09-039)
</td>
<td style="border:1px solid black;">
[**MS09-038**](https://technet.microsoft.com/security/bulletin/ms09-038)
</td>
<td style="border:1px solid black;">
[**MS09-037**](https://technet.microsoft.com/security/bulletin/ms09-037)
</td>
<td style="border:1px solid black;">
[**MS09-041**](https://technet.microsoft.com/security/bulletin/ms09-041)
</td>
<td style="border:1px solid black;">
[**MS09-040**](https://technet.microsoft.com/security/bulletin/ms09-040)
</td>
<td style="border:1px solid black;">
[**MS09-036**](https://technet.microsoft.com/security/bulletin/ms09-036)
</td>
<td style="border:1px solid black;">
[**MS09-042**](https://technet.microsoft.com/security/bulletin/ms09-042)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[RDP 5.2 版](https://www.microsoft.com/download/details.aspx?familyid=60c79729-ef01-4630-bd67-ec63e7f8b56b)  
(KB958469)  
(重大)  
[RDP 6.0 版](https://www.microsoft.com/download/details.aspx?familyid=a37a2d8a-a5ce-4f06-bf07-8cafa16e7a59)\*\*\*\*  
(KB956744)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3a8d8ef9-ad41-4237-9cbb-daecfd8f216c)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=cba78658-899c-428f-8b04-cfe14ce3c255)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](https://www.microsoft.com/download/details.aspx?familyid=3119ab1e-6729-40a1-b28f-0dab50502be6)  
(KB973354)  
(重大)  
[Windows Media Player 10](https://www.microsoft.com/download/details.aspx?familyid=ab054890-983b-4414-ad0a-da1b2d2a4895)  
(KB973540)  
(重大)  
[Windows ATL Component](https://www.microsoft.com/download/details.aspx?familyid=7d9369b5-0c54-4c17-bc62-fba0a7b4728c)  
(KB973507)  
(重大)  
[DHTML 編輯元件 ActiveX 控制項](https://www.microsoft.com/download/details.aspx?familyid=bfc474c2-e3c5-40df-85d4-4ac666ff0561)  
(KB973869  
(重大)  
[Microsoft MSWebDVD ActiveX 控制項](https://www.microsoft.com/download/details.aspx?familyid=301ad191-8d3f-41d3-b41c-e2e863893f73)  
(KB973815)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9cb0477f-0656-47f5-bd35-5716e0572fbd)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=52f59c56-2aba-4626-a90e-311e0e73c813)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3fe9c745-d87c-43b0-9b2a-356fb34282b4)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[RDP 5.2 版](https://www.microsoft.com/download/details.aspx?familyid=60c79729-ef01-4630-bd67-ec63e7f8b56b)  
(KB958469)  
(重大)  
[RDP 6.0 版](https://www.microsoft.com/download/details.aspx?familyid=a37a2d8a-a5ce-4f06-bf07-8cafa16e7a59)\*\*\*\*  
(KB956744)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e132d051-4444-4ef1-9b6f-2d7da9d2e88e)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=58a7c8d9-ec36-46a6-a89b-d8dfd989fda4)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](https://www.microsoft.com/download/details.aspx?familyid=17bd00e3-810c-4a72-bd13-1b55ffb52a5e)  
(KB973354)  
(重大)  
[Windows Media Player 10](https://www.microsoft.com/download/details.aspx?familyid=5890233a-d8f7-490c-8bf5-3ed4bd1c6991)  
(KB973540)  
(重大)  
[Windows ATL Component](https://www.microsoft.com/download/details.aspx?familyid=90e0e014-ed7e-498a-9f61-18bb09a384b3)  
(KB973507)  
(重大)  
[DHTML 編輯元件 ActiveX 控制項](https://www.microsoft.com/download/details.aspx?familyid=9f502d79-99a8-45dc-9876-2df27e14ffaa)  
(KB973869  
(重大)  
[Microsoft MSWebDVD ActiveX 控制項](https://www.microsoft.com/download/details.aspx?familyid=2ae71a65-5eee-4dd2-bc79-b7c5a73022bc)  
(KB973769)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=96fbf65f-1db2-432d-92a0-6669d8abaeb0)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2f77ef7b-54f8-4260-b6a6-d62a0f85ef45)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e2a788e7-a9d1-4574-b106-f8ab44c6c4a2)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[RDP 5.2 版](https://www.microsoft.com/download/details.aspx?familyid=8f88a714-b917-4193-9002-19fa65722028)  
(KB958469)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=96c3f496-7b2f-4dbc-b484-216c9943c2b1)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=187b02bd-73d6-4f72-81d1-d9477d495499)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](https://www.microsoft.com/download/details.aspx?familyid=7978b921-c5b5-461f-a284-b9848f568aa9)  
(KB973354)  
(重大)  
[Windows ATL Component](https://www.microsoft.com/download/details.aspx?familyid=ad1791b3-8553-4433-a9f7-8b4f857665be)  
(KB973507)  
(重大)  
[DHTML 編輯元件 ActiveX 控制項](https://www.microsoft.com/download/details.aspx?familyid=82c0bb02-70ad-4605-a1f4-4698adf9f4ac)  
(KB973869  
(重大)  
[Microsoft MSWebDVD ActiveX 控制項](https://www.microsoft.com/download/details.aspx?familyid=5b8a8958-c3cd-4b24-85a2-1baacf92d218)  
(KB973815)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=11321f48-8997-4b99-982a-3ba4ad3f5992)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=ad55c653-ee6b-4c92-b7f4-3923bb916546)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=4f625d39-29d4-44f9-b4bd-cd99f1ea422d)  
(重要)
</td>
</tr>
<tr>
<th colspan="9">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-044**](https://technet.microsoft.com/security/bulletin/ms09-044)
</td>
<td style="border:1px solid black;">
[**MS09-039**](https://technet.microsoft.com/security/bulletin/ms09-039)
</td>
<td style="border:1px solid black;">
[**MS09-038**](https://technet.microsoft.com/security/bulletin/ms09-038)
</td>
<td style="border:1px solid black;">
[**MS09-037**](https://technet.microsoft.com/security/bulletin/ms09-037)
</td>
<td style="border:1px solid black;">
[**MS09-041**](https://technet.microsoft.com/security/bulletin/ms09-041)
</td>
<td style="border:1px solid black;">
[**MS09-040**](https://technet.microsoft.com/security/bulletin/ms09-040)
</td>
<td style="border:1px solid black;">
[**MS09-036**](https://technet.microsoft.com/security/bulletin/ms09-036)
</td>
<td style="border:1px solid black;">
[**MS09-042**](https://technet.microsoft.com/security/bulletin/ms09-042)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista 上的 RDP 6.0 版](https://www.microsoft.com/download/details.aspx?familyid=cf95a552-f6fd-4e35-815a-d16c015cd3ea)  
(KB956744)  
(重要)  
適用於 Windows Vista Service Pack 1 和 Windows Vista Service Pack 2  
的 RDP 6.1 版(KB956744)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=81fce7bd-f33c-4586-949d-ac40d415f755)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=3766aed9-93f5-478e-a5bf-b7ee0b577088)  
(KB973540)  
(重大)  
[Windows ATL Component](https://www.microsoft.com/download/details.aspx?familyid=80de158d-157e-4c21-9154-c1dbd6e57cb3)  
(KB973507)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=979ac9da-940f-49e7-91a2-b12db3708076)  
(中度)
</td>
<td style="border:1px solid black;">
[Windows Vista](https://www.microsoft.com/download/details.aspx?familyid=00afd94c-b483-4155-884f-b617acca6e7d)  
(重要)
</td>
<td style="border:1px solid black;">
僅限 Windows Vista： [Microsoft .NET Framework 2.0 Service Pack 1 與 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=d42444bb-5030-4b47-87fa-9df3a8c640ff) (KB972591)，[Microsoft .NET Framework 2.0 Service Pack 2 與 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=310f3aa6-c264-45a2-b24a-3f178b41830e)\*\*\*\*\* (KB972592)  
(重要)  
僅限 Windows Vista Service Pack 1：  
[Microsoft .NET Framework 2.0 Service Pack 1 與 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd) (KB972593)，[Microsoft .NET Framework 2.0 Service Pack 2 與 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f)\*\*\*\*\* (KB972594)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d77f406d-11cb-4d19-94ec-938b356c3427)  
(中度)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 上的 RDP 6.0 版](https://www.microsoft.com/download/details.aspx?familyid=5e19cef7-2413-4575-9597-c6273a097aad)  
(KB956744)  
(重要)  
[適用於 Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2 的 RDP 6.1 版](https://www.microsoft.com/download/details.aspx?familyid=5e19cef7-2413-4575-9597-c6273a097aad)  
(KB956744)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a6cea61a-4ad9-4e18-bf18-348ae4ae51c4)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=64edbd64-9faa-4f54-b0d5-836c683ca7cd)  
(KB973540)  
(重大)  
[Windows ATL Component](https://www.microsoft.com/download/details.aspx?familyid=82940d30-6a30-47ca-b184-2ac96e35c294)  
(KB973507)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b9aa04cc-a5c5-47ae-bf0f-250cff275d26)  
(中度)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=a0c698aa-a913-4981-8798-6bbb8cacfb86)  
(重要)
</td>
<td style="border:1px solid black;">
僅限 Windows Vista x64 Edition： [Microsoft .NET Framework 2.0 Service Pack 1 與 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=d42444bb-5030-4b47-87fa-9df3a8c640ff) (KB972591)，[Microsoft .NET Framework 2.0 Service Pack 2 與 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=310f3aa6-c264-45a2-b24a-3f178b41830e)\*\*\*\*\* (KB972592)  
(重要)  
僅限 Windows Vista x64 Edition Service Pack 1：  
[Microsoft .NET Framework 2.0 Service Pack 1 與 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd) (KB972593)，[Microsoft .NET Framework 2.0 Service Pack 2 與 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f) (KB972594)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7a41b8c1-f955-474e-a08e-5e73964327d1)  
(中度)
</td>
</tr>
<tr>
<th colspan="9">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-044**](https://technet.microsoft.com/security/bulletin/ms09-044)
</td>
<td style="border:1px solid black;">
[**MS09-039**](https://technet.microsoft.com/security/bulletin/ms09-039)
</td>
<td style="border:1px solid black;">
[**MS09-038**](https://technet.microsoft.com/security/bulletin/ms09-038)
</td>
<td style="border:1px solid black;">
[**MS09-037**](https://technet.microsoft.com/security/bulletin/ms09-037)
</td>
<td style="border:1px solid black;">
[**MS09-041**](https://technet.microsoft.com/security/bulletin/ms09-041)
</td>
<td style="border:1px solid black;">
[**MS09-040**](https://technet.microsoft.com/security/bulletin/ms09-040)
</td>
<td style="border:1px solid black;">
[**MS09-036**](https://technet.microsoft.com/security/bulletin/ms09-036)
</td>
<td style="border:1px solid black;">
[**MS09-042**](https://technet.microsoft.com/security/bulletin/ms09-042)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[RDP 6.1 版](https://www.microsoft.com/download/details.aspx?familyid=71c17a87-710b-434d-9b2a-2f471674915a)\*\*  
(KB956744)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=fdc96a07-ed79-4798-8077-b2e9ca64cd0f)\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=85d9e69f-99a2-467f-bf37-4b47466a12d4)\*\*  
(KB973540)  
(重大)  
[Windows ATL Component](https://www.microsoft.com/download/details.aspx?familyid=ba423491-6c29-49f2-811b-ac3f9bbc58fc)\*  
(KB973507)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=24c77c27-0b7d-4a35-a871-b453f90e5913)\*  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
僅適用於 32 位元系統的 Windows Server 2008： [Microsoft .NET Framework 2.0 Service Pack 1 與 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd) (KB972593)，[Microsoft .NET Framework 2.0 Service Pack 2 與 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f) (KB972594)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=62f2e0a6-5e68-41c7-a851-d99bcff6ff3e)\*  
(中度)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[RDP 6.1 版](https://www.microsoft.com/download/details.aspx?familyid=f095d2d5-4513-4ae1-96c7-cbcf83304261)\*\*  
(KB956744)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8e3afba4-6761-4b3d-98bb-4b4145e27b7f)\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=9501c8c2-a526-4661-8cba-7847bace1aa0)\*\*  
(KB973540)  
(重大)  
[Windows ATL Component](https://www.microsoft.com/download/details.aspx?familyid=b9311953-889a-415f-a396-250a005e95cd)\*  
(KB973507)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=48d0432e-704a-4bbb-b0a1-cd14069a8e93)\*  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
僅適用於 x64 型系統的 Windows Server 2008： [Microsoft .NET Framework 2.0 Service Pack 1 與 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd) (KB972593)，[Microsoft .NET Framework 2.0 Service Pack 2 與 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f) (KB972594)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6e5d1db9-efef-4112-8138-62f14670cf0d)\*  
(中度)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[RDP 6.1 版](https://www.microsoft.com/download/details.aspx?familyid=65d0af4e-22a2-4524-a003-2f4858012fa8)  
(KB956744)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=aa1bb13a-5905-48c4-8e74-a41104593046)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows ATL Component](https://www.microsoft.com/download/details.aspx?familyid=e5612bb4-5f37-4b38-bd2e-f198c413371c)  
(KB973507)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c119223c-f4e0-449b-8e7b-a6bf11c98f94)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
僅適用於 Itanium 型系統的 Windows Server 2008： [Microsoft .NET Framework 2.0 Service Pack 1 與 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd) (KB972593)，[Microsoft .NET Framework 2.0 Service Pack 2 與 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f) (KB972594)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4b813c74-b2ae-4962-9ebb-1311193d9e2d)  
(中度)
</td>
</tr>
</table>
 
**Windows Server 2008 注意事項**

**\*Windows Server 2008 Server Core 安裝會受影響。** 對於受支援的 Windows Server 2008 版本，無論 Windows Server 2008 是否使用 Server Core 安裝選項，這個更新均以相同的嚴重性等級套用。 如需這個安裝選項的詳細資訊，請參閱 [Server Core](https://msdn.microsoft.com/zh-tw/library/ms723891(vs.85).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 版本；請參閱[比較 Server Core 安裝選項](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**\*\*Windows Server 2008 Server Core 安裝不受影響。** 如果 Windows Server 2008 是使用 Server Core 安裝選項所安裝，則這項更新解決的弱點並不會影響受支援的 Windows Server 2008 版本。 如需這個安裝選項的詳細資訊，請參閱 [Server Core](https://msdn.microsoft.com/zh-tw/library/ms723891(vs.85).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 版本；請參閱[比較 Server Core 安裝選項](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**MS09-044 注意事項**

**\*\*\***Microsoft Windows 2000 Service Pack 4 上 RDP 5.0 版的使用者，必須同時安裝 KB958471 和 KB958470。

**\*\*\*\***系統管理員可能已手動安裝此不定期下載。

另請參閱＜受影響的軟體及下載位置＞中的＜適用於 Mac 的用戶端軟體＞，以取得更多相同公告編號裡的更新檔案。 本公告涉及多個軟體分類。

**MS09-036 的注意事項**

**\*\*\*\*\***因為 Windows Vista Starter 及 Windows Vista Home Basic 並不執行 IIS 7.0，所以下列版本不受影響： Windows Vista Starter (32 位元)、Windows Vista Home Basic (32 位元) 以及 Windows Vista Home Basic (64 位元)。

#### 適用於 Mac 的用戶端軟體

 
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
遠端桌面
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-044**](https://technet.microsoft.com/security/bulletin/ms09-044)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Mac 的 Remote Desktop Connection 用戶端
</td>
<td style="border:1px solid black;">
[適用於 Mac 2.0.1 的 Remote Desktop Connection 用戶端](https://www.microsoft.com/download/details.aspx?familyid=cd9ec77e-5b07-4332-849f-046611458871)**\***  
(重要)
</td>
</tr>
</table>
 
**MS09-044 注意事項**

**\***此下載會將 Remote Desktop Connection Client for Mac 2.0 升級為 Remote Desktop Connection Client for Mac 2.0.1，此版本可解決此項弱點。

另請參閱本節＜受影響的軟體及下載位置＞中的＜Windows 作業系統與元件＞，以取得更多相同公告編號的更新檔案。 本公告涉及多個軟體分類。

#### Microsoft Office 套件及軟體

 
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
Microsoft Office 套件、系統和元件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-043**](https://technet.microsoft.com/security/bulletin/ms09-043)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=60e2e4e7-aa75-441d-b6fc-7e850bf8e580)  
(KB947320)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=95c94c9a-6aca-42fb-9679-3234f06c72f7)  
(KB947319)  
(重大)
</td>
</tr>
<tr>
<th colspan="2">
Office Web 元件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-043**](https://technet.microsoft.com/security/bulletin/ms09-043)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 Web 元件
</td>
<td style="border:1px solid black;">
[Microsoft Office 2000 Web Components Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=60e2e4e7-aa75-441d-b6fc-7e850bf8e580)  
(KB947320)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP Web 元件
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Web Components Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=60e2e4e7-aa75-441d-b6fc-7e850bf8e580)  
(KB947320)  
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Web 元件
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Web Components Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=95c94c9a-6aca-42fb-9679-3234f06c72f7)  
(KB947319)  
(重大)  
[Microsoft Office 2003 Web Components Service Pack 1 for the 2007 Microsoft Office System](https://www.microsoft.com/download/details.aspx?familyid=644008e0-77c9-4a02-ac9b-e30d0930c4be)\*  
(KB947318)  
(重大)
</td>
</tr>
<tr>
<th colspan="2">
其他 Office 軟體
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-043**](https://technet.microsoft.com/security/bulletin/ms09-043)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Small Business Accounting 2006
</td>
<td style="border:1px solid black;">
[Microsoft Office Small Business Accounting 2006](https://www.microsoft.com/download/details.aspx?familyid=0d77ddb3-4d34-4cfe-913b-d05981f59a82)  
(KB968377)  
(重大)
</td>
</tr>
</table>
 
**MS09-043 注意事項**

**\***SQL Server 2008 與 Microsoft Forefront Threat Management Gateway Medium Business Edition 轉散發 Office 2003 Web Components for the 2007 Microsoft Office System 這個受影響的元件。 Office 2003 Web Components for the 2007 Microsoft Office System 元件的更新程式偵測到 SQL Server 2008 和 Microsoft Forefront Threat Management Gateway Medium Business Edition 後，會將這些更新提供給客戶。

另請參閱＜受影響的軟體及下載位置＞中的其他小節，以取得更多相同公告編號裡的更新檔案。 本公告涉及多個軟體分類。

#### Microsoft 開發者工具和軟體

 
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
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-043**](https://technet.microsoft.com/security/bulletin/ms09-043)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=ba2915a0-f5f4-4e18-b0c0-534d2a948585)  
(KB969172)  
(重大)
</td>
</tr>
</table>
 
**MS09-043 注意事項**

另請參閱＜受影響的軟體及下載位置＞中的其他小節，以取得更多相同公告編號裡的更新檔案。 本公告涉及多個軟體分類。

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
Microsoft Internet Security and Acceleration Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-043**](https://technet.microsoft.com/security/bulletin/ms09-043)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server 2004
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2004 Standard Edition Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=8f79a073-27e8-46ef-87d8-f09b93521326)\*  
(KB947826)  
(重大)  
[Microsoft Internet Security and Acceleration Server 2004 Enterprise Edition Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=8f79a073-27e8-46ef-87d8-f09b93521326)  
(KB947826)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server 2006
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2006 Standard Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=8f79a073-27e8-46ef-87d8-f09b93521326)  
(KB947826)  
(重大)  
[Microsoft Internet Security and Acceleration Server 2006 Enterprise Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=8f79a073-27e8-46ef-87d8-f09b93521326)  
(KB947826)  
(重大)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft BizTalk Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-043**](https://technet.microsoft.com/security/bulletin/ms09-043)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft BizTalk Server 2002
</td>
<td style="border:1px solid black;">
[Microsoft BizTalk Server 2002](https://www.microsoft.com/download/details.aspx?familyid=495839b6-0322-4755-997d-4a7762c53333)  
(KB971388)  
(重大)
</td>
</tr>
</table>
 
**MS09-043 注意事項**

\*Microsoft ISA Server 2004 Standard Edition 是以獨立產品提供。 Microsoft ISA Server 2004 Standard Edition 也能以 Windows Small Business Server 2003 Premium Edition Service Pack 1，或 Windows Small Business Server 2003 R2 Premium Edition 元件提供。

另請參閱＜受影響的軟體及下載位置＞中的其他小節，以取得更多相同公告編號裡的更新檔案。 本公告涉及多個軟體分類。

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和安全性更新。 如需更多資訊，請參閱 [TechNet 更新管理中心](https://www.microsoft.com/taiwan/technet/updatemanagement/default.mspx) (英文)。 [TechNet Security Center](https://www.microsoft.com/taiwan/technet/security/default.mspx) 提供 Microsoft 產品安全性的其他資訊。 消費者可以造訪[在家上網的安全性](https://www.microsoft.com/taiwan/athome/security/default.mspx)網站，只要按一下 \[最新安全性更新\] 即可在此網站取得此資訊。

安全性更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 以及 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 取得。 安全性更新也可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得。 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。

最後，您可以從 [Microsoft Update Catalog](https://go.microsoft.com/fwlink/?linkid=96155) 下載安全性更新。 Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括安全性更新、驅動程式和 Service Pack。 只要以安全性公告編號 (例如：MS07-036) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。 如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](https://go.microsoft.com/fwlink/?linkid=97900)。

**注意**：自 2009 年 8 月 1 日開始，Microsoft 已停止支援 Office Update 與 Office Update Inventory Tool。 若要繼續取得 Microsoft Office 產品的最新更新，請使用 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)。 如需更多資訊，請參閱[關於 Microsoft Office Update： 常見問題集](https://office.microsoft.com/en-us/downloads/fx010402221033.aspx) (英文)。

**偵測與部署指南**

Microsoft 針對安全性更新提供偵測和部署指南。 本指南所含之建議和資訊，能幫助 IT 專業人員瞭解如何使用用於安全性更新的偵測和部署的各種工具。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 961747](https://support.microsoft.com/kb/961747/zh-tw)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少安全性更新以及一般安全性設定錯誤的狀況。 如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134) 網站 (英文)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速可靠地將 Windows 2000 作業系統及更新系統版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 等最新的重大更新與安全性更新部署到 Windows 2000 及更新作業系統版本中。

如需更多關於利用 Windows Server Update Services 部署安全性更新的資訊，請造訪 [Windows Server Update Services](https://www.microsoft.com/taiwan/windowsserversystem/updateservices/evaluation/overview.mspx) 網站。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。 現已推出新版的 SMS，System Center Configuration Manager 2007；另請參閱 [System Center Configuration Manager 2007](https://technet.microsoft.com/en-us/library/bb735860.aspx)。如需更多有關系統管理員如何能使用 SMS 2003 部署安全性更新的資訊，請參閱 [SMS 2003 安全性修補程式管理](https://www.microsoft.com/taiwan/smserver/evaluation/capabilities/patch.htm) (英文)。 SMS 2.0 使用者也可以使用安全性更新盤點工具 (Security Update Inventory Tool，SUIT) 來協助部署安全性更新。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server](https://www.microsoft.com/taiwan/smserver/)。

**注意**：SMS 使用 Microsoft Baseline Security Analyzer 提供廣泛的安全性公告更新偵測與部署支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](https://go.microsoft.com/fwlink/?linkid=33341)。 某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可以用 Elevated Rights Deployment Tool (隨 [SMS 2003 Administration Feature Pack](https://www.microsoft.com/taiwan/smserver/downloads/2003/adminpack.htm) (英文) 和 [SMS 管理功能套件](https://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/adminpack/default.htm) (英文) 提供) 來安裝這些更新。

**Update Compatibility Evaluator 和應用程式相容性工具組**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。 這可能會觸發不相容性，而拉長部署安全性更新的時間。 您可以使用 [Application Compatibility Toolkit](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 隨附的 [Update Compatibility Evaluator](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 元件，針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Microsoft Windows Vista、Windows Update、Microsoft 安全性更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非安全性、高優先順序更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](https://support.microsoft.com/kb/894199/zh-tw)： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。 其中也包括所有 Windows 的內容。
-   [適用於 Microsoft 產品 (除了 Microsoft Windows 以外) 的全新、修訂版以及已發行的更新](https://technet.microsoft.com/en-us/wsus/dd573344.aspx)。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的安全性保護，Microsoft 將在每月發行安全性更新之前，提前向重要安全性軟體提供者提供弱點資訊。 安全性軟體提供者可利用此弱點資訊，透過其安全性軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。 如果要判斷是否有安全性軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](https://www.microsoft.com/security/msrc/mapp/partners.mspx)上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 安全性策略與社群

**更新程式管理策略**

[更新管理安全性指南](https://www.microsoft.com/taiwan/technet/security/topics/patchmanagement.mspx) (英文) 提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](https://support.microsoft.com/kb/913086/zh-tw)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](https://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](https://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 [Digitiria](https://www.digitaria.com/) 的 Alexander Pfandt 回報 MS09-036 中描述的問題
-   感謝 [IBM ISS X-Force](https://www.iss.net/) 的 Ryan Smith 和 Alex Wheeler 最初回報 MS09-037 中描述的問題
-   感謝 [IBM ISS X-Force](https://www.iss.net/) 的 Robert Freeman 回報 MS09-037 中描述的問題
-   感謝 [IBM ISS X-Force](https://www.iss.net/) 的 David Dewey 回報 MS09-037 中描述的問題
-   感謝 [VeriSign iDefense Labs](https://labs.idefense.com/) 的 Ryan Smith 回報 MS09-037 中描述的兩個問題
-   感謝 [Adobe Systems, Inc.](https://www.adobe.com/) 的 Vinay Anantharaman 回報 MS09-038 中描述的兩個問題
-   感謝 [TippingPoint](https://www.tippingpoint.com/) 和 [Zero Day Initiative](https://www.zerodayinitiative.com/) 回報 MS09-039 中描述的問題
-   感謝 [National University of Defense Technology](https://english.nudt.edu.cn/) 的 LiGen 回報 MS09-039 中描述的問題
-   感謝 [Positive Technologies Research Team](https://en.securitylab.ru/lab/) 的 Nikita Tarakanov 回報 MS09-040 中描述的問題
-   感謝 [TippingPoint DVLabs](https://dvlabs.tippingpoint.com/) 的 Cody Pierce 回報 MS09-041 中描述的問題
-   感謝 [Zero Day Initiative](https://www.zerodayinitiative.com/) 的 Peter Vreugdenhil 回報 MS09-043 中描述的兩個問題
-   感謝 [Zero Day Initiative](https://www.zerodayinitiative.com/) 的 Peter Vreugdenhil 及 Fortinet 的 [FortiGuard Global Security Research Team](https://www.fortiguardcenter.com/) 的 Haifei Li 回報 MS09-043 中描述的問題
-   感謝 [VeriSign iDefense Labs](https://labs.idefense.com/) 的 Sean Larsson 回報 MS09-043 中描述的問題
-   感謝 [Team509](https://www.team509.com/) 的 Wushi 與 Zero Day Initiative 合作，回報 MS09-044 中描述的問題。
-   感謝 [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Yamata Li 回報 MS09-044 中描述的問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可洽詢[安全性支援](https://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 以取得技術支援。 與安全性更新有關的支援電話不另外收費。 如需更多可用支援選項的資訊，請參閱 [Microsoft 技術支援服務](https://support.microsoft.com/)。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與安全性更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](https://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2009 年 8 月 12 日)： 公告摘要發行。
-   V1.1 (2009 年 8 月 18 日)： 已更正 Windows XP Service Pack 2 與 Windows XP Service Pack 3 針對 MS09-044 的 RDP 更新清單以符合公告。 變更 MS09-037、MS09-042 和 MS09-044 的重新開機需求。
-   V2.0 (2009 年 8 月 25 日)： 針對 MS09-044，更正 Windows XP Service Pack 2 RDP 5.2 版的下載連結 (KB958469)。 另外，也已經為 KB958471 和 KB958470 更正指定錯誤安裝順序的註腳。已成功安裝這些更新的客戶無需重新安裝。
-   V3.0 (2009 年 9 月 8 日)： Microsoft 重新發行 MS09-037 是為了提供 Windows XP Media Center Edition 2005 和所有支援的 Windows Vista 版本上 HtmlInput 物件 ActiveX 控制項的新更新。

*Built at 2014-04-18T01:50:00Z-07:00*
