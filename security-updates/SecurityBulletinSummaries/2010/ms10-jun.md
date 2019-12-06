---
TOCTitle: 'MS10-JUN'
Title: 2010 年 6 月份 Microsoft 安全性公告摘要
ms:assetid: 'ms10-jun'
ms:contentKeyID: 61237707
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms10-jun(v=Security.10)'
---

2010 年 6 月份 Microsoft 安全性公告摘要
=======================================

發行: 2010年6月8日 | 更新: 2011年9月13日

**版本:** 2.0

本公告摘要列出 2010 年 6 月份發行之安全性公告。

發行 2010 年 6 月份公告之後，此公告摘要將取代原先於 2010 年 6 月 3 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](https://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2010 年 6 月 9 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。[立即註冊參力 6 月份安全性公告網路廣播](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032427727&eventcategory=4&culture=en-us&countrycode=us)。在這個日期後，此網路廣播將可隨選取得。如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](https://technet.microsoft.com/security/bulletin/summary)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性、高優先順序更新的優先順序，其中這些非安全性、高優先順序更新的發行日期與每月安全性更新的發行日期相同。請參閱＜其他資訊＞一節。

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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=191065">MS10-033</a></td>
<td style="border:1px solid black;"><strong>媒體解壓縮中的弱點可能會允許遠端執行程式碼 (979902)</strong><br />
<br />
此安全性更新可解決 Microsoft Windows 中兩項未公開報告的弱點。當使用者開啟蓄意製作的媒體檔案，或者從網站或任何提供 Web 內容的應用程式接收蓄意製作的串流內容時，這些弱點可能會允許遠端執行程式碼。成功利用這類弱點的攻擊者可以取得與本機使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=185159">MS10-034</a></td>
<td style="border:1px solid black;"><strong>ActiveX Kill Bit (刪除位元) 的積存安全性更新 (980195)</strong><br />
<br />
此安全性更新可解決兩項未公開報告的 Microsoft 軟體弱點。對於所有受支援版本的 Microsoft Windows 2000、Windows XP、Windows Vista 和 Windows 7，此安全性更新的等級為「重大」；對於所有受支援版本的 Windows Server 2003、Windows Server2008 和 Windows Server 2008 R2，此安全性更新的等級為「中度」。<br />
<br />
如果使用者使用 Internet Explorer 檢視蓄意製作而產生特定 ActiveX 控制項的網頁，這些弱點即可能允許遠端執行程式碼。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。此更新程式同時也包含四個協力廠商 ActiveX 控制項的 Kill Bit (刪除位元)。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=190898">MS10-035</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 積存安全性更新 (982381)</strong><br />
<br />
這個安全性更新可解決 Internet Explorer 中五項未公開報告的弱點，以及一項公開揭露的弱點。最嚴重的弱點可能會在使用者以 Internet Explorer 檢視蓄意製作的網頁時，允許遠端執行程式碼。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=184917">MS10-032</a></td>
<td style="border:1px solid black;"><strong>Windows 核心模式驅動程式的弱點可能會允許權限提高 (979559)</strong><br />
<br />
此安全性更新可解決 Windows 核心模式驅動程式中兩項公開揭露的弱點和一項未公開報告的弱點。如果使用者檢視以蓄意製作的 TrueType 字型所呈現的內容，則這些弱點可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=190554">MS10-036</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 中 COM 驗證的弱點可能會允許遠端執行程式碼 (983235)</strong><br />
<br />
此安全性更新可解決 Microsoft Office 的 COM 驗證中一項未公開報告的弱點。如果使用者使用受影響版本的 Microsoft Office 開啟蓄意製作的 Excel、Word、Visio、Publisher 或 PowerPoint 檔案，此弱點可能會允許遠端執行程式碼。無法透過電子郵件自動攻擊此弱點。使用者必須順利開啟電子郵件訊息中傳送的附件，攻擊才可進行。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=190508">MS10-037</a></td>
<td style="border:1px solid black;"><strong>OpenType 壓縮字型格式 (CFF) 驅動程式中的弱點可能會允許權限提高 (980218)</strong><br />
<br />
此安全性更新可解決 Windows OpenType 壓縮字型格式 (CFF) 驅動程式中一項未公開報告的弱點。如果使用者檢視以蓄意製作的 CFF 字型所呈現的內容，則該弱點可能會允許權限提高。攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項弱點。匿名或遠端使用者無法利用這個弱點。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Excel 中的弱點可能會允許遠端執行程式碼 (2027452)</strong><br />
<br />
此安全性更新可解決 Microsoft Office 中 14 項未公開報告的弱點。其中較嚴重的弱點，可能會在使用者開啟蓄意製作的 Excel 檔案時，允許遠端執行程式碼。成功利用這類任一弱點的攻擊者可以取得與本機使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=191905">MS10-039</a></td>
<td style="border:1px solid black;"><strong>Microsoft SharePoint 中的弱點可能會允許提高權限 (2028554)</strong><br />
<br />
此安全性更新可解決 Microsoft SharePoint 中一項公開揭露的弱點和兩項未公開報告的弱點。如果攻擊者引誘目標 SharePoint 網站的使用者點選蓄意製作的連結，則其中最嚴重的弱點可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office、Microsoft 伺服器軟體</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=191788">MS10-040</a></td>
<td style="border:1px solid black;"><strong>Internet Information Services 的弱點可能會允許遠端執行程式碼 (982666)</strong><br />
<br />
此安全性更新可解決 Internet Information Services (IIS) 中一項未公開報告的弱點。如果使用者收到蓄意製作的 HTTP 要求，此弱點可能會允許遠端執行程式碼。成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=185042">MS10-041</a></td>
<td style="border:1px solid black;"><strong>Microsoft .NET Framework 中的弱點可能會允許竄改 (981343)</strong><br />
<br />
此安全性更新可解決 Microsoft .NET Framework 中一項公開揭露的弱點。此弱點可能會允許竄改已簽署 XML 內容中的資料，而且不會被偵測到。這對自訂應用程式的安全性影響多寡，取決於已簽署的內容是如何用於特定的應用程式中。如果已簽署的 XML 訊息是透過安全通道 (例如 SSL) 傳輸，便不會受到此弱點影響。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
篡改</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、Microsoft .NET Framework</td>
</tr>
</tbody>
</table>
  
弱點索引  
--------
  
<span></span>
下表提供本月所述每個弱點的利用性評估。弱點根據遞減的弱點評估等級及 CVE 編號依序列出。僅包含安全性公告中，嚴重性等級為「重大」或「重要」的弱點。
  
**我該如何使用這個表格？**
  
請用這個表格來瞭解您可能需要安裝的每個安全性更新，與 30 天內已發行的可利用程式碼受影響之可能性。您應該檢閱下列的每個評估，按照特定的設定，將部署以優先次序排序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](https://technet.microsoft.com/en-us/security/cc998259.aspx)。
  
| 公告編號                                                  | 弱點標題                                | CVE ID                                                                           | 弱點索引評估                                                                                            | 主要重點                                                                                                       |  
|-----------------------------------------------------------|-----------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------|  
| [MS10-032](https://go.microsoft.com/fwlink/?linkid=184917) | Win32k 視窗建立弱點                     | [CVE-2010-0485](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0485) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                           |  
| [MS10-039](https://go.microsoft.com/fwlink/?linkid=191905) | Help.aspx XSS 弱點                      | [CVE-2010-0817](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0817) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | 此弱點最初是在 [Microsoft 安全性摘要報告 983438](https://technet.microsoft.com/security/advisory/983438) 中提出 |  
| [MS10-038](https://go.microsoft.com/fwlink/?linkid=191053) | Excel 物件堆疊溢位弱點                  | [CVE-2010-0822](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0822) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                           |  
| [MS10-038](https://go.microsoft.com/fwlink/?linkid=191053) | Excel 記錄記憶體損毀弱點                | [CVE-2010-0824](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0824) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                           |  
| [MS10-038](https://go.microsoft.com/fwlink/?linkid=191053) | Excel 記錄記憶體損毀弱點                | [CVE-2010-1245](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1245) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                           |  
| [MS10-038](https://go.microsoft.com/fwlink/?linkid=191053) | Excel RTD 記憶體損毀弱點                | [CVE-2010-1246](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1246) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                           |  
| [MS10-038](https://go.microsoft.com/fwlink/?linkid=191053) | Excel 記憶體損毀弱點                    | [CVE-2010-1247](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1247) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                           |  
| [MS10-038](https://go.microsoft.com/fwlink/?linkid=191053) | Excel HFPicture 記憶體損毀弱點          | [CVE-2010-1248](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1248) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                           |  
| [MS10-038](https://go.microsoft.com/fwlink/?linkid=191053) | Excel 記憶體損毀弱點                    | [CVE-2010-1249](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1249) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                           |  
| [MS10-038](https://go.microsoft.com/fwlink/?linkid=191053) | Excel EDG 記憶體損毀弱點                | [CVE-2010-1250](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1250) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                           |  
| [MS10-038](https://go.microsoft.com/fwlink/?linkid=191053) | Excel ADO 物件弱點                      | [CVE-2010-1253](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1253) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                           |  
| [MS10-038](https://go.microsoft.com/fwlink/?linkid=191053) | Mac Office Open XML 權限弱點            | [CVE-2010-1254](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1254) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                           |  
| [MS10-035](https://go.microsoft.com/fwlink/?linkid=190898) | 未初始化的記憶體損毀弱點                | [CVE-2010-1259](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1259) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                           |  
| [MS10-035](https://go.microsoft.com/fwlink/?linkid=190898) | 記憶體損毀弱點                          | [CVE-2010-1262](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1262) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                           |  
| [MS10-036](https://go.microsoft.com/fwlink/?linkid=190554) | COM 驗證弱點                            | [CVE-2010-1263](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1263) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                           |  
| [MS10-033](https://go.microsoft.com/fwlink/?linkid=191065) | 媒體解壓縮弱點                          | [CVE-2010-1879](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1879) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                           |  
| [MS10-035](https://go.microsoft.com/fwlink/?linkid=190898) | 跨網域資訊洩漏弱點                      | [CVE-2010-0255](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0255) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | 此弱點最初是在 [Microsoft 安全性摘要報告 980088](https://technet.microsoft.com/security/advisory/980088) 中提出 |  
| [MS10-032](https://go.microsoft.com/fwlink/?linkid=184917) | Win32k 資料驗證不當弱點                 | [CVE-2010-0484](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0484) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                           |  
| [MS10-037](https://go.microsoft.com/fwlink/?linkid=190508) | OpenType CFF 字型驅動程式記憶體損毀弱點 | [CVE-2010-0819](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0819) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                           |  
| [MS10-038](https://go.microsoft.com/fwlink/?linkid=191053) | Excel 記錄剖析記憶體損毀弱點            | [CVE-2010-0821](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0821) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                           |  
| [MS10-038](https://go.microsoft.com/fwlink/?linkid=191053) | Excel 記憶體損毀弱點                    | [CVE-2010-0823](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0823) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                           |  
| [MS10-038](https://go.microsoft.com/fwlink/?linkid=191053) | Excel 記錄堆疊損毀弱點                  | [CVE-2010-1251](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1251) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                           |  
| [MS10-038](https://go.microsoft.com/fwlink/?linkid=191053) | Excel 字串變數弱點                      | [CVE-2010-1252](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1252) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                           |  
| [MS10-032](https://go.microsoft.com/fwlink/?linkid=184917) | Win32k TrueType 字型剖析弱點            | [CVE-2010-1255](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1255) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                           |  
| [MS10-040](https://go.microsoft.com/fwlink/?linkid=191788) | IIS 驗證記憶體損毀弱點                  | [CVE-2010-1256](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1256) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                           |  
| [MS10-033](https://go.microsoft.com/fwlink/?linkid=191065) | MJPEG 媒體解壓縮弱點                    | [CVE-2010-1880](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1880) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                           |  
| [MS10-041](https://go.microsoft.com/fwlink/?linkid=185042) | XML 簽章 HMAC 截斷驗證略過弱點          | [CVE-2009-0217](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0217) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 這是一個偽造和竄改弱點                                                                                         |  
| [MS10-035](https://go.microsoft.com/fwlink/?linkid=190898) | toStaticHTML 資訊洩漏弱點               | [CVE-2010-1257](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1257) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 這個弱點也影響[MS10-039](https://go.microsoft.com/fwlink/?linkid=191905)                                        |  
| [MS10-039](https://go.microsoft.com/fwlink/?linkid=191905) | toStaticHTML 資訊洩漏弱點               | [CVE-2010-1257](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1257) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 這個弱點也影響 [MS10-035](https://go.microsoft.com/fwlink/?linkid=190898)                                       |  
| [MS10-039](https://go.microsoft.com/fwlink/?linkid=191905) | SharePoint 說明網頁拒絕服務弱點         | [CVE-2010-1264](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1264) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | (無)                                                                                                           |
  
受影響的軟體及下載位置  
----------------------
  
<span></span>
下表依據主要的軟體類別和嚴重性依序列出公告。
  
**我該如何使用這些表格？**
  
請用這些表格來瞭解可能需要安裝的安全性更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的安全性更新。若軟體程式或更新出現在清單中，則相關可用軟體更新也會以超連結方式提供，也會列出軟體更新的嚴重性等級。
  
**注意**：一項弱點，可能需要安裝數個安全性更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
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
</tr>
<tr>
<th colspan="8">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-032**](https://go.microsoft.com/fwlink/?linkid=184917)
</td>
<td style="border:1px solid black;">
[**MS10-033**](https://go.microsoft.com/fwlink/?linkid=191065)
</td>
<td style="border:1px solid black;">
[**MS10-034**](https://go.microsoft.com/fwlink/?linkid=185159)
</td>
<td style="border:1px solid black;">
[**MS10-035**](https://go.microsoft.com/fwlink/?linkid=190898)
</td>
<td style="border:1px solid black;">
[**MS10-037**](https://go.microsoft.com/fwlink/?linkid=190508)
</td>
<td style="border:1px solid black;">
[**MS10-040**](https://go.microsoft.com/fwlink/?linkid=191788)
</td>
<td style="border:1px solid black;">
[**MS10-041**](https://go.microsoft.com/fwlink/?linkid=185042)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
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
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=60c8579b-1540-40d8-80a0-956edadd63ce)  
(重要)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow) (DirectX 9)](https://www.microsoft.com/download/details.aspx?familyid=a51c53bd-f9c1-4d53-8ed2-034fd57bc75a)<sup>[1]</sup>
(KB975562)  
(重大)  
[Windows Media Format Runtime 9](https://www.microsoft.com/download/details.aspx?familyid=8417c0ac-bb6d-48f1-8237-77a4bdd8ccb2)<sup>[2]</sup>
(KB978695)  
(重大)  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=5b5398c1-5b30-4162-95b6-948d9be103bf)  
(KB979332)  
(重要)  
[Asycfilt.dll (COM 元件)](https://www.microsoft.com/download/details.aspx?familyid=1f929739-08a1-4faf-9ccf-5f1f43c5bb9e)  
(KB979482)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=d3955983-0079-476e-a488-99713097259c)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 5.01 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=0a6c09e5-c655-41a0-a133-78d55267a527)  
(無嚴重性等級)<sup>[1]</sup>
[Internet Explorer 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=e2f27eeb-54be-40be-a00e-72867090b8e7)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=5d645891-31e9-42c4-b12b-eb351473fd0c)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
(重要)
</td>
</tr>
<tr>
<th colspan="8">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-032**](https://go.microsoft.com/fwlink/?linkid=184917)
</td>
<td style="border:1px solid black;">
[**MS10-033**](https://go.microsoft.com/fwlink/?linkid=191065)
</td>
<td style="border:1px solid black;">
[**MS10-034**](https://go.microsoft.com/fwlink/?linkid=185159)
</td>
<td style="border:1px solid black;">
[**MS10-035**](https://go.microsoft.com/fwlink/?linkid=190898)
</td>
<td style="border:1px solid black;">
[**MS10-037**](https://go.microsoft.com/fwlink/?linkid=190508)
</td>
<td style="border:1px solid black;">
[**MS10-040**](https://go.microsoft.com/fwlink/?linkid=191788)
</td>
<td style="border:1px solid black;">
[**MS10-041**](https://go.microsoft.com/fwlink/?linkid=185042)
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
無
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 及 Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 及 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=023a777a-3d83-4a4e-8029-da8b095b074b)  
(重要)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=e77d5af8-e8e0-425c-a809-4cf274e17cc5)  
(KB975562)  
(重大)  
僅限 Windows XP Service Pack 2：  
[Windows Media Format Runtime 9、Windows Media Format Runtime 9.5 和 Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?familyid=bf8b9b46-ba28-4f48-9dac-6a90b7d592d3)  
(KB978695)  
(重大)  
僅限 Windows XP Service Pack 3：  
[Windows Media Format Runtime 9、Windows Media Format Runtime 9.5 和 Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?familyid=ebbccd82-c637-4c88-86ea-d39ae713c085)  
(KB978695)  
(重大)  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=5b5398c1-5b30-4162-95b6-948d9be103bf)  
(KB979332)  
(重要)  
[Asycfilt.dll (COM 元件)](https://www.microsoft.com/download/details.aspx?familyid=55c05cb8-aa6c-460b-9aa7-084842dab280)  
(KB979482)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 及 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=8c3f2e81-c0ea-494a-a47c-4f8982effb49)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=bfe87761-ed9e-4fec-a393-d7fddb919db4)  
(重大)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=fc02fc7e-ee85-4377-b54c-012fa60a8c9c)  
(重大)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=9cff9aba-7743-4c33-87c7-37d06ed60a21)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 及 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=b42a17c5-997e-4504-ba5b-bfa62166b460)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
僅限 Windows XP Media Center Edition 2005：  
[Microsoft .NET Framework 1.0 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=c658c108-abd3-4c24-898d-34d490151394)  
(KB979904)  
(重要)  
僅限 Windows XP Media Center Edition 2005 和 Windows XP Tablet PC Edition 2005：  
[Microsoft .NET Framework 1.0 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=c658c108-abd3-4c24-898d-34d490151394)  
(KB979904)  
(重要)  
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(重要)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8e3aac9d-7747-435f-9678-f621e314e070)  
(重要)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=7914fdae-9a7a-4a10-8ce7-c621eb903452)  
(KB975562)  
(重大)  
[Windows Media Format Runtime 9.5](https://www.microsoft.com/download/details.aspx?familyid=b56839e3-e7d3-48da-b90c-d403d8dbeed2)  
(KB978695)  
(重大)  
[Windows Media Format Runtime 9.5 x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=80006082-55f2-4857-9d2c-276c758b5555)<sup>[3]</sup>
(KB978695)  
(重大)  
[Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?familyid=d2887448-9d3c-472f-a0bd-ab083a65eafc)  
(KB978695)  
(重大)  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=94c654f0-f70f-4fbd-84de-797be20fc3b9)  
(KB979332)  
(重要)  
[Windows Media Encoder 9 x64](https://www.microsoft.com/download/details.aspx?familyid=2b7a3cb7-151c-4184-9865-f197ef6ee8e7)  
(KB979332)  
(重要)  
[Asycfilt.dll (COM 元件)](https://www.microsoft.com/download/details.aspx?familyid=c110d26e-9a1e-4e47-9ce2-4068f2733a2f)  
(KB979482)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f3e462fb-df95-4b79-a8bc-5359c2967503)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=7780af61-a206-49aa-a805-a49bdcbb5419)  
(重大)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=6c7cda29-161e-49b4-976a-c718c0aa11a0)  
(重大)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=37cd7533-ddad-4d0d-85c0-1491308e1ff8)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=dc835b94-3368-4c1c-8f29-40517c73540e)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(重要)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad) (KB979909)  
(重要)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-032**](https://go.microsoft.com/fwlink/?linkid=184917)
</td>
<td style="border:1px solid black;">
[**MS10-033**](https://go.microsoft.com/fwlink/?linkid=191065)
</td>
<td style="border:1px solid black;">
[**MS10-034**](https://go.microsoft.com/fwlink/?linkid=185159)
</td>
<td style="border:1px solid black;">
[**MS10-035**](https://go.microsoft.com/fwlink/?linkid=190898)
</td>
<td style="border:1px solid black;">
[**MS10-037**](https://go.microsoft.com/fwlink/?linkid=190508)
</td>
<td style="border:1px solid black;">
[**MS10-040**](https://go.microsoft.com/fwlink/?linkid=191788)
</td>
<td style="border:1px solid black;">
[**MS10-041**](https://go.microsoft.com/fwlink/?linkid=185042)
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
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中度**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中度**](https://go.microsoft.com/fwlink/?linkid=21140)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=79a11dcd-5d88-4d83-beae-6580ef6fc2c0)  
(重要)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=fc15c43b-d48f-4872-8f9d-ed973170db9a)  
(KB975562)  
(重大)  
[Windows Media Format Runtime 9.5](https://www.microsoft.com/download/details.aspx?familyid=bb580e94-8c02-46f1-b7f6-e7d4373cb1c5)  
(KB978695)  
(重大)  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=5b5398c1-5b30-4162-95b6-948d9be103bf)  
(KB979332)  
(重要)  
[Asycfilt.dll (COM 元件)](https://www.microsoft.com/download/details.aspx?familyid=0ddf95ac-dd49-4cb1-b6f6-bd4e987b0f06)  
(KB979482)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3c0bd349-aa77-47de-ba1d-1fcc72dcad28)  
(中度)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=bfb9acdb-2d9c-4c22-963c-8b9ce247350f)  
(中度)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=f0187b69-3ed9-494c-89f1-90a35e22078c)  
(中度)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=ebab6101-fcf1-4842-b22d-893a20c1c10f)  
(中度)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ca49b5b5-db8e-4ebc-9a3c-b1ace09ac3c0)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Information Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=0761c207-5465-4f42-b61f-bd02efcef27d)<sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=f82e1b73-7f8b-4f4c-8187-4050a11db44c)  
(KB979907)  
(重要)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f42cc5d4-1bea-4a4a-8a08-b3eb92503588)  
(重要)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=d28ecdf7-9fd4-437e-9db7-c6b579248abe)  
(KB975562)  
(重大)  
[Windows Media Format Runtime 9.5](https://www.microsoft.com/download/details.aspx?familyid=41faf16f-c7a8-4ce0-b388-a65478576163)  
(KB978695)  
(重大)  
[Windows Media Format Runtime 9.5 x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=80006082-55f2-4857-9d2c-276c758b5555)<sup>[3]</sup>
(KB978695)  
(重大)  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=94c654f0-f70f-4fbd-84de-797be20fc3b9)  
(KB979332)  
(重要)  
[Windows Media Encoder 9 x64](https://www.microsoft.com/download/details.aspx?familyid=2b7a3cb7-151c-4184-9865-f197ef6ee8e7)  
(KB979332)  
(重要)  
[Asycfilt.dll (COM 元件)](https://www.microsoft.com/download/details.aspx?familyid=77b1d55c-b015-4863-aab0-6463b90d4bf7)  
(KB979482)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4aa0ec4f-5502-4f2a-9732-975518c34444)  
(中度)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=81644c43-22c0-4c61-b395-3264516516a6)  
(中度)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=50b8ee2e-31f8-473d-83d1-822c89c28070)  
(中度)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=87e13912-f861-4985-ab9d-260a5898dfd4)  
(中度)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b0794e7e-c925-4672-b7a5-4bb3f847f045)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Information Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=023572ff-ce5d-4428-a96b-1245db6ff312)<sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(重要)[  
Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=50efb1cf-9d89-4522-929d-f87fd98d6fe8)  
(重要)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=7f101f4c-dcc8-474c-a844-fe0c45d6697c)  
(KB975562)  
(重大)  
[Asycfilt.dll (COM 元件)](https://www.microsoft.com/download/details.aspx?familyid=f34bc115-022b-46b0-9517-806bd0fc73c5)  
(KB979482)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=55d9d7f0-f9d9-4833-b5cc-eb87a62da6a8)  
(中度)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=abcdc3bb-4659-4b63-a9bd-e448f8bed90a)  
(中度)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=123bf547-9005-451f-9eba-97a68037304e)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=6e76ebea-bde1-4352-a283-dd71c2cc51a1)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Information Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=f1f3e524-8ac6-4210-a3a8-4ffc58a606ea)<sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(重要)[  
Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
(重要)
</td>
</tr>
<tr>
<th colspan="8">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-032**](https://go.microsoft.com/fwlink/?linkid=184917)
</td>
<td style="border:1px solid black;">
[**MS10-033**](https://go.microsoft.com/fwlink/?linkid=191065)
</td>
<td style="border:1px solid black;">
[**MS10-034**](https://go.microsoft.com/fwlink/?linkid=185159)
</td>
<td style="border:1px solid black;">
[**MS10-035**](https://go.microsoft.com/fwlink/?linkid=190898)
</td>
<td style="border:1px solid black;">
[**MS10-037**](https://go.microsoft.com/fwlink/?linkid=190508)
</td>
<td style="border:1px solid black;">
[**MS10-040**](https://go.microsoft.com/fwlink/?linkid=191788)
</td>
<td style="border:1px solid black;">
[**MS10-041**](https://go.microsoft.com/fwlink/?linkid=185042)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
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
Windows Vista Service Pack 1 和 Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7cb64633-d2a0-4e38-be35-ec32ea655a04)  
(重要)
</td>
<td style="border:1px solid black;">
僅限 Windows Vista Service Pack 1：  
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=b64107f2-990a-42df-a75a-5bf371709fd6)  
(KB975562)  
(重大)  
[Asycfilt.dll (COM 元件)](https://www.microsoft.com/download/details.aspx?familyid=75e4c9cb-a55a-4e2a-9c97-60a40353cae3)  
(KB979482)  
(重大)  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=9fab91da-1528-4df9-a2dd-90e57a3c24cf)  
(KB979332)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2ddaa4b3-1a98-4183-94af-ebdae4e7b76a)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=661c9528-917d-4df6-a330-c89f39dc5ce4)  
(重大)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=640f9216-3e99-46b6-aac8-cd051eedad3c)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=363b503a-2e1e-4284-a029-9695d2acfcb6)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Information Services 7.0](https://www.microsoft.com/download/details.aspx?familyid=01382926-2313-4769-a0a5-262c4f9f18a1)<sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(重要)  
僅限 Windows Vista Service Pack 1：  
[Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)  
(KB979913)  
(重要)  
僅限 Windows Vista Service Pack 1：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)  
(KB979911)  
(重要)  
僅限 Windows Vista Service Pack 2：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb) (KB979910)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=bbfc4d80-67eb-4deb-9595-cb67942a0df2)  
(重要)
</td>
<td style="border:1px solid black;">
僅限 Windows Vista x64 Edition Service Pack 1：  
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=0754addb-2f04-45c9-8594-174b8b8b297c)  
(KB975562)  
(重大)  
[Asycfilt.dll (COM 元件)](https://www.microsoft.com/download/details.aspx?familyid=c9f033f6-f587-494d-b968-1316f1deed06)  
(KB979482)  
(重大)  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=63bba49e-6d80-47b3-b109-fa9b2392af4f)  
(KB979332)  
(重要)  
[Windows Media Encoder 9 x64](https://www.microsoft.com/download/details.aspx?familyid=e19aeef8-6bef-45ee-bc9f-3e4b81a58e33)  
(KB979332)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ddf55e74-dbaa-45f7-ac5b-ae3da24e0e33)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=d9f5feb0-fa1a-40c1-9971-9b8af6f0b4a5)  
(重大)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=3076d1ea-7716-4b54-8ec4-660374f14dcb)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3f512b86-3a99-47f7-a90e-1ae9b291385c)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Information Services 7.0](https://www.microsoft.com/download/details.aspx?familyid=7fb6f2b8-c7a6-4239-99f3-cf3aacf89b0f)<sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(重要)  
僅限 Windows Vista x64 Edition Service Pack 1：  
[Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)  
(KB979913)  
(重要)  
僅限 Windows Vista x64 Edition Service Pack 1：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)  
(KB979911)  
(重要)  
僅限 Windows Vista x64 Edition Service Pack 2：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb)  
(KB979910)  
(重要)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-032**](https://go.microsoft.com/fwlink/?linkid=184917)
</td>
<td style="border:1px solid black;">
[**MS10-033**](https://go.microsoft.com/fwlink/?linkid=191065)
</td>
<td style="border:1px solid black;">
[**MS10-034**](https://go.microsoft.com/fwlink/?linkid=185159)
</td>
<td style="border:1px solid black;">
[**MS10-035**](https://go.microsoft.com/fwlink/?linkid=190898)
</td>
<td style="border:1px solid black;">
[**MS10-037**](https://go.microsoft.com/fwlink/?linkid=190508)
</td>
<td style="border:1px solid black;">
[**MS10-040**](https://go.microsoft.com/fwlink/?linkid=191788)
</td>
<td style="border:1px solid black;">
[**MS10-041**](https://go.microsoft.com/fwlink/?linkid=185042)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中度**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中度**](https://go.microsoft.com/fwlink/?linkid=21140)
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
適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=22d550fe-ba35-4750-a9d6-624858b67c94)\*  
(重要)
</td>
<td style="border:1px solid black;">
僅適用於 32 位元系統的 Windows Server 2008：  
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=18fd814b-51f3-470b-a5bd-97be752298d9)\*\*  
(KB975562)  
(重大)  
[Asycfilt.dll (COM 元件)](https://www.microsoft.com/download/details.aspx?familyid=5c5e2dfc-0078-4f2a-9c2e-75e45bb7638e)\*  
(KB979482)  
(重大)  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=1ce1e47f-b1c3-4480-bafd-74f8b12e2171)\*\*  
(KB979332)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a06b9f42-47ac-4ff2-ac32-e4958cdb611e)\*\*  
(中度)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=bed14484-7fc5-455d-b996-3192467543cc)\*\*  
(中度)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=24ed08c7-a474-4458-8269-3b9de5e22385)\*\*  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e78ad607-d209-48c4-b0f3-ed4c70993174)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Information Services 7.0](https://www.microsoft.com/download/details.aspx?familyid=84a54246-5d9e-49e2-8170-af48b43f984d)\*<sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)\*\*  
(KB979906)  
(重要)  
僅限適用於 32 位元系統的 Windows Server 2008：  
[Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)\*\*  
(KB979913)  
(重要)  
僅限適用於 32 位元系統的 Windows Server 2008：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)\*\*  
(KB979911)  
(重要)  
僅限適用於 32 位元系統的 Windows Server 2008 Service Pack 2：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb)\*\*  
(KB979910)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=09025626-4116-4a31-8700-215382898ee2)\*  
(重要)
</td>
<td style="border:1px solid black;">
僅適用於 x64 型系統的 Windows Server 2008：  
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=4e40da51-23ee-44f0-9ea0-99bda8cca731)\*\*  
(KB975562)  
(重大)  
[Asycfilt.dll (COM 元件)](https://www.microsoft.com/download/details.aspx?familyid=bfc0b62c-2d79-48dd-896f-d05057c02e8c)\*  
(KB979482)  
(重大)  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=93cc5ace-6382-4a2f-875b-9348b7e198a6)\*\*  
(KB979332)  
(重要)  
[Windows Media Encoder 9 x64](https://www.microsoft.com/download/details.aspx?familyid=d650a7d7-5620-4bb7-a7ad-0848dd28dae3)\*\*  
(KB979332)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6d0a3f7c-2617-4bc6-a4c7-cda26c6471e1)\*\*  
(中度)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=a24554e8-213b-4c24-b062-ec424d64128e)\*\*  
(中度)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=cf84469b-ce6d-45e8-8336-7b4501c6cf91)\*\*  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=85f6fc5d-efd1-4351-b4c0-b9b7080e6173)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Information Services 7.0](https://www.microsoft.com/download/details.aspx?familyid=38286e43-89a6-4895-8ff9-69452df38706)\*<sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)\*\*  
(KB979906)  
(重要)  
僅限適用於 x64 型系統的 Windows Server 2008：  
[Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)\*\*  
(KB979913)  
(重要)  
僅限適用於 x64 型系統的 Windows Server 2008：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)\*\*  
(KB979911)  
(重要)  
僅限適用於 x64 型系統的 Windows Server 2008 Service Pack 2：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb)\*\*  
(KB979910)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0035cfe2-d38d-41cd-b704-ec1feda307d8)  
(重要)
</td>
<td style="border:1px solid black;">
僅適用於 Itanium 型系統的 Windows Server 2008：  
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=120c68f5-4575-4e2a-912a-eed52736c403)  
(KB975562)  
(重大)  
[Asycfilt.dll (COM 元件)](https://www.microsoft.com/download/details.aspx?familyid=6e5753ab-848d-475f-917d-ba70f70b65f5)  
(KB979482)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=38347fa6-5946-4bb5-9fea-a5b2f4e7c1f2)  
(中度)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=dee5c0c0-b844-490d-8daf-6e6ec8a39e35)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c6f1aae5-e8fd-4121-89b2-b97c571e8223)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Information Services 7.0](https://www.microsoft.com/download/details.aspx?familyid=8ad19eba-9821-48b4-a942-4ee4f002f913)<sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(重要)  
僅限適用於 Itanium 型系統的 Windows Server 2008：  
[Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)  
(KB979913)  
(重要)  
僅限適用於 Itanium 型系統的 Windows Server 2008：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)  
(KB979911)  
(重要)  
僅限適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb)  
(KB979910)  
(重要)
</td>
</tr>
<tr>
<th colspan="8">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-032**](https://go.microsoft.com/fwlink/?linkid=184917)
</td>
<td style="border:1px solid black;">
[**MS10-033**](https://go.microsoft.com/fwlink/?linkid=191065)
</td>
<td style="border:1px solid black;">
[**MS10-034**](https://go.microsoft.com/fwlink/?linkid=185159)
</td>
<td style="border:1px solid black;">
[**MS10-035**](https://go.microsoft.com/fwlink/?linkid=190898)
</td>
<td style="border:1px solid black;">
[**MS10-037**](https://go.microsoft.com/fwlink/?linkid=190508)
</td>
<td style="border:1px solid black;">
[**MS10-040**](https://go.microsoft.com/fwlink/?linkid=191788)
</td>
<td style="border:1px solid black;">
[**MS10-041**](https://go.microsoft.com/fwlink/?linkid=185042)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=3e0ff389-4612-4c92-bbff-bb45b5bdfc6a)  
(重要)
</td>
<td style="border:1px solid black;">
[Asycfilt.dll (COM 元件)](https://www.microsoft.com/download/details.aspx?familyid=63567e99-087d-4804-953a-f23bdeba7772)  
(KB979482)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=5bce87fe-dcbb-4638-b248-3f0755537b00)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=5c835885-9375-4882-a92f-4d4cfcacc005)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=969af8d6-f6da-4dd1-a7d7-2de54a5a8978)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Information Services 7.5](https://www.microsoft.com/download/details.aspx?familyid=588167cb-f62a-4fb8-8a18-ac15dc322495)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764)  
(KB979916)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=2b1e4aff-605a-4e94-88f9-135ce35f0646)  
(重要)
</td>
<td style="border:1px solid black;">
[Asycfilt.dll (COM 元件)](https://www.microsoft.com/download/details.aspx?familyid=6c261dbf-14c6-4071-8523-e8ba8059fa54)  
(KB979482)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=ee68ecd0-5b8a-4c1e-bdee-bd8616558d43)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=5cfc5776-0c6b-4092-bc98-94df077c60d8)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=b069e5b2-aa2d-452e-b687-8734b5ba0051)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Information Services 7.5](https://www.microsoft.com/download/details.aspx?familyid=1c45d0c8-1629-470b-8167-c6bf66054595)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764)  
(KB979916)  
(重要)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-032**](https://go.microsoft.com/fwlink/?linkid=184917)
</td>
<td style="border:1px solid black;">
[**MS10-033**](https://go.microsoft.com/fwlink/?linkid=191065)
</td>
<td style="border:1px solid black;">
[**MS10-034**](https://go.microsoft.com/fwlink/?linkid=185159)
</td>
<td style="border:1px solid black;">
[**MS10-035**](https://go.microsoft.com/fwlink/?linkid=190898)
</td>
<td style="border:1px solid black;">
[**MS10-037**](https://go.microsoft.com/fwlink/?linkid=190508)
</td>
<td style="border:1px solid black;">
[**MS10-040**](https://go.microsoft.com/fwlink/?linkid=191788)
</td>
<td style="border:1px solid black;">
[**MS10-041**](https://go.microsoft.com/fwlink/?linkid=185042)
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
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中度**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中度**](https://go.microsoft.com/fwlink/?linkid=21140)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?familyid=4272277f-b2dd-4406-8bbd-bc461c9923b8)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Asycfilt.dll (COM 元件)](https://www.microsoft.com/download/details.aspx?familyid=1331f2bc-7479-4be7-a413-52afb488a330)\*  
(KB979482)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?familyid=901f7c89-02af-4f87-8592-dad318997d77)\*\*  
(中度)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=7c4ff5ae-eadd-431e-b982-d5f179efb8c0)\*\*  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?familyid=45242c7c-3752-44bf-a766-024ad7d28f53)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Information Services 7.5](https://www.microsoft.com/download/details.aspx?familyid=5d9b7705-6280-4d2e-94fa-3160b3ce5cfa)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764)\*  
(KB979916)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?familyid=7d636f82-e828-468c-ac36-808ff9d37c7f)  
(重要)
</td>
<td style="border:1px solid black;">
[Asycfilt.dll (COM 元件)](https://www.microsoft.com/download/details.aspx?familyid=7a1ee54f-3f73-4557-9071-5af236e70937)  
(KB979482)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?familyid=4958b221-2776-43d7-9e1c-1e1cb318a694)  
(中度)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=52c04d85-911f-47be-852e-c9bb4934744d)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?familyid=0a271fb5-da5b-4a17-9593-e56b9a843b8f)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Information Services 7.5](https://www.microsoft.com/download/details.aspx?familyid=869e900a-0063-4d8b-9b7c-7d12f6be12cd)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764)  
(KB979916)  
(重要)
</td>
</tr>
</table>
 
**Windows Server 2008 和 Windows Server 2008 R2 注意事項**

**\*會影響 Server Core 安裝。**無論上述受支援的 Windows Server 2008 或 Windows Server 2008 R2 版本是否使用 Server Core 安裝選項安裝，這個更新均以相同的嚴重性等級套用。如需此安裝選項的詳細資訊，請參閱 MSDN 文章：[伺服器核心](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英文) 以及[適用於 Windows Server 2008 R2 的伺服器核心](https://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 及 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**\*\*Server Core 安裝不受影響。**如果 Windows Server 2008 或 Windows Server 2008 R2 是使用 Server Core 安裝選項所安裝，則這項更新解決的弱點並不會影響受支援的 Windows Server 2008 或 Windows Server 2008 R2。如需此安裝選項的詳細資訊，請參閱 MSDN 文章：[伺服器核心](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英文) 以及[適用於 Windows Server 2008 R2 的伺服器核心](https://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 及 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**MS10-033 注意事項**

<sup>[1]</sup>Quartz.dll (Direct Show) (DirectX 9) 的更新也適用於 DirectX 9.0a、DirectX 9.0b 和 DirectX 9.0c。

<sup>[2]</sup>此更新程式封裝適用於 Microsoft Windows 2000 上的 Windows Media Format 9 SDK Runtime，含已啟用 DRM 之 Media Players 的更新 (KB891122)。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 974316](https://support.microsoft.com/kb/974316)。

<sup>[3]</sup>如果您是安裝 Windows Media Format Runtime 9.5 x64 Edition，您必須套用 Windows Media Format Runtime 9.5 和 Windows Media Format Runtime 9.5 x64 Edition 安全性更新，以便獲得充分保護，不受 MS10-033 中討論的弱點影響。

**MS10-035 注意事項**

<sup>[1]</sup>嚴重性等級不適用此更新，因為此公告討論的弱點不會影響此軟體。但是，提供此更新是為了修正源自 [MS09-054](https://go.microsoft.com/fwlink/?linkid=163979) 的一項迴歸問題。詳細資訊請參見 [MS10-035](https://go.microsoft.com/fwlink/?linkid=190898)。

**MS10-040 注意事項**

<sup>[1]</sup>只有在已安裝延伸驗證防護時才會影響此作業系統。請參閱 [Microsoft 知識庫文件編號 973917](https://support.microsoft.com/kb/973917)。

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
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="4">
Microsoft Office 套件、系統和元件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-036**](https://go.microsoft.com/fwlink/?linkid=190554)
</td>
<td style="border:1px solid black;">
[**MS10-038**](https://go.microsoft.com/fwlink/?linkid=191053)
</td>
<td style="border:1px solid black;">
[**MS10-039**](https://go.microsoft.com/fwlink/?linkid=191905)
</td>
</tr>
<tr class="alternateRow">
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
無
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3<sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=fec14a92-79a1-4281-8ee2-659b2dfd283f)  
(KB982299)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=80fdd134-2a86-4115-aea1-841f19af92e3)  
(KB982311)  
(重要)  
[Microsoft Office Excel 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=757b5d8f-ade5-4896-b152-43f76516bcf1)<sup>[2]</sup>
(KB982133)  
(重要)  
[Microsoft Office PowerPoint 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=6b6204c1-559f-45a5-8f6c-a1e216192efc)<sup>[2]</sup>
(KB982157)  
(重要)  
[Microsoft Office Publisher 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=87bac893-81ec-4ede-aca1-a9aa48b92cd4)<sup>[2]</sup>
(KB982122)  
(重要)  
[Microsoft Office Visio 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=1595ada3-bb4f-40f6-8137-23eba918bc8a)<sup>[2]</sup>
(KB982126)  
(重要)  
[Microsoft Office Word 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=d2c40eb5-1149-4466-840c-84f406f64245)<sup>[2]</sup>
(KB982134)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=757b5d8f-ade5-4896-b152-43f76516bcf1)  
(KB982133)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System Service Pack 1 和 2007 Microsoft Office System Service Pack 2
</td>
<td style="border:1px solid black;">
[2007 Microsoft Office System Service Pack 1 和 2007 Microsoft Office System Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6deb4fb0-cbfc-40df-8f62-35fa1db0e167)  
(KB982312)  
(重要)  
[Microsoft Office Excel 2007 Service Pack 1 和 Microsoft Office Excel 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1b2599f0-1e5d-463c-b100-6c6a1b17b2ec)<sup>[3]</sup>
(KB982308)  
(重要)  
[Microsoft Office PowerPoint 2007 Service Pack 1 和 Microsoft Office PowerPoint 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=decb834d-3958-45cc-a5ae-4283adb2462a)<sup>[3]</sup>
(KB982158)  
(重要)  
[Microsoft Office Publisher 2007 Service Pack 1 和 Microsoft Office Publisher 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6a74b986-1e99-4aa1-828f-757a36896f65)<sup>[3]</sup>
(KB982124)  
(重要)  
[Microsoft Office Visio 2007 Service Pack 1 和 Microsoft Office Visio 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d5df052e-1f38-4308-bcca-296cff22729b)<sup>[3]</sup>
(KB982127)  
(重要)  
[Microsoft Office Word 2007 Service Pack 1 和 Microsoft Office Word 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7e9708f0-8cd6-4f0b-8585-bccc54fa2755)<sup>[3]</sup>
(KB982135)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 Service Pack 1 和 Microsoft Office Excel 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1b2599f0-1e5d-463c-b100-6c6a1b17b2ec)<sup>[1]</sup>
(KB982308)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="4">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-036**](https://go.microsoft.com/fwlink/?linkid=190554)
</td>
<td style="border:1px solid black;">
[**MS10-038**](https://go.microsoft.com/fwlink/?linkid=191053)
</td>
<td style="border:1px solid black;">
[**MS10-039**](https://go.microsoft.com/fwlink/?linkid=191905)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=16c71ab8-9284-407a-856a-93c67995f125)  
(KB2028866)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=d46255bd-6470-4106-9fe2-ea67acd3f1bd)  
(KB2028864)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=b6ca7b05-cf97-43a2-95eb-7b5caf7c1528)  
(KB2078051)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="4">
其他 Office 軟體
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-036**](https://go.microsoft.com/fwlink/?linkid=190554)
</td>
<td style="border:1px solid black;">
[**MS10-038**](https://go.microsoft.com/fwlink/?linkid=191053)
</td>
<td style="border:1px solid black;">
[**MS10-039**](https://go.microsoft.com/fwlink/?linkid=191905)
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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer Service Pack 1 和 Microsoft Office Excel Viewer Service Pack 2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer Service Pack 1 和 Microsoft Office Excel Viewer Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=033b3bf3-7826-4064-b001-11e4dce2d91a)  
(KB982333)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Word、Excel 及 PowerPoint 2007 檔案格式相容性套件 Service Pack 1 和 Microsoft Office Word、Excel 及 PowerPoint 2007 檔案格式相容性套件 Service Pack 2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Word、Excel 與 PowerPoint 2007 檔案格式的 Microsoft Office 相容性套件 Service Pack 1 和 Word、Excel 與 PowerPoint 2007 檔案格式的 Microsoft Office 相容性套件 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7f89a734-cda4-4abb-9a10-f6dfe560e8d0)  
(KB982331)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office InfoPath 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office InfoPath 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=4f79d376-0ea2-4218-9200-3c34c83ba336)  
(KB980923)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office InfoPath 2007 Service Pack 1 和 Microsoft Office InfoPath 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office InfoPath 2007 Service Pack 1 和 Microsoft Office InfoPath 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=bfa8765a-7970-4feb-996c-7c27d71c97c6)  
(KB979441)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 1 和 Microsoft Office SharePoint Server 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 1 (32 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=52a55423-f33b-4cd1-919d-806972a553df)<sup>[1]</sup>
(KB979445)  
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (32 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=52a55423-f33b-4cd1-919d-806972a553df)<sup>[1]</sup>
(KB979445)  
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 1 (64 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=4d84a25b-532f-4319-9ab2-90e5b82ebd90)<sup>[1]</sup>
(KB979445)  
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (64 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=4d84a25b-532f-4319-9ab2-90e5b82ebd90)<sup>[1]</sup>
(KB979445)  
(重要)
</td>
</tr>
</table>
 
**MS10-036 注意事項**

<sup>[1]</sup>沒有可用的更新。請參閱公告內容以瞭解詳細資訊。

<sup>[2]</sup>除了此更新之外，客戶也必須安裝 Microsoft Office 2003 Service Pack 3 的更新 (KB982311)，才能避免受此公告中描述的弱點影響。

<sup>[3]</sup>除了此更新之外，客戶也必須安裝 2007 Microsoft Office System Service Pack 1 及 2007 Microsoft Office System Service Pack 2 的更新 (KB982312)，才能避免受此公告中描述的弱點影響。

**MS10-038 注意事項**

<sup>[1]</sup>除了此更新之外，客戶也必須安裝 Microsoft Office Word、Excel 及 PowerPoint 2007 檔案格式相容性套件 Service Pack 1 以及 Microsoft Office Word、Excel 及 PowerPoint 2007 檔案格式相容性套件 Service Pack 2 的安全性更新 (KB982308)，才能避免受此公告中描述的弱點影響。

**MS10-039 注意事項**

<sup>[1]</sup>針對支援的 Microsoft Office SharePoint Server 2007 版本，除了安裝安全性更新封裝 KB979445 外，客戶還需安裝適用於 Microsoft Windows SharePoint Services 3.0 的安全性更新 (KB983444)，以避免受本公告中所述的弱點影響。

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

#### Microsoft 伺服器軟體

 
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
Windows SharePoint Services
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-039**](https://go.microsoft.com/fwlink/?linkid=191905)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 1 和 Microsoft Windows SharePoint Services 3.0 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 Service Pack 1 和 Microsoft Windows SharePoint Services 3.0 Service Pack 2 (32 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=3841ceda-d0af-4e5e-8a1a-7dd954850783)  
(KB983444)  
(重要)  
[Microsoft Windows SharePoint Services 3.0 Service Pack 1 和 Microsoft Windows SharePoint Services 3.0 Service Pack 2 (64 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=94bc76d4-78e4-4bda-8922-36c3a9d3854f)  
(KB983444)  
(重要)
</td>
</tr>
</table>
 
**MS10-039 注意事項**

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和安全性更新。如需更多資訊，請參閱 [TechNet 更新管理中心](https://go.microsoft.com/fwlink/?linkid=69903) (英文)。[TechNet Security Center](https://go.microsoft.com/fwlink/?linkid=21171) 提供 Microsoft 產品安全性的其他資訊。消費者可以造訪[在家上網的安全性](https://go.microsoft.com/fwlink/?linkid=85102)網站，只要按一下 \[最新安全性更新\] 即可在此網站取得此資訊。

安全性更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 以及 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 取得。安全性更新也可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得。您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。

最後，您可以從 [Microsoft Update Catalog](https://go.microsoft.com/fwlink/?linkid=96155) 下載安全性更新。Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括安全性更新、驅動程式和 Service Pack。只要以安全性公告編號 (例如：MS07-036) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](https://go.microsoft.com/fwlink/?linkid=97900)。

**注意**：自 2009 年 8 月 1 日開始，Microsoft 已停止支援 Office Update 與 Office Update Inventory Tool。若要繼續取得 Microsoft Office 產品的最新更新，請使用 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)。如需更多資訊，請參閱[關於 Microsoft Office Update： 常見問題集](https://office.microsoft.com/en-us/downloads/fx010402221033.aspx) (英文)。

**偵測與部署指南**

Microsoft 針對安全性更新提供偵測和部署指南。本指南所含之建議和資訊，能幫助 IT 專業人員瞭解如何使用用於安全性更新的偵測和部署的各種工具。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 961747](https://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少安全性更新以及一般安全性設定錯誤的狀況。如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134) 網站 (英文)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速而可靠地將 Microsoft Windows 2000 作業系統及更新版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 適用的最新重大更新與安全性更新部署到 Microsoft Windows 2000 及更新版本的作業系統中。

如需更多關於利用 Windows Server Update Services 部署安全性更新的資訊，請造訪 [Windows Server Update Services](https://go.microsoft.com/fwlink/?linkid=50120) 網站。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。現已推出新版的 SMS，System Center Configuration Manager 2007；另請參閱 [System Center Configuration Manager 2007](https://technet.microsoft.com/en-us/library/bb735860.aspx)。如需更多有關系統管理員如何能使用 SMS 2003 部署安全性更新的資訊，請參閱 [SMS 2003 安全性修補程式管理](https://go.microsoft.com/fwlink/?linkid=22939) (英文)。SMS 2.0 使用者也可以使用安全性更新盤點工具 (Security Update Inventory Tool，SUIT) 來協助部署安全性更新。如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server](https://go.microsoft.com/fwlink/?linkid=21158)。

**注意** ：SMS 使用 Microsoft Baseline Security Analyzer 提供廣泛的安全性公告更新偵測與部署支援。不過這些工具可能無法偵測部分的軟體更新。在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](https://go.microsoft.com/fwlink/?linkid=33341)。某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。系統管理員可使用 Elevated Rights Deployment Tool (隨 [SMS 2.0 Administration Feature Pack (英文)](https://go.microsoft.com/fwlink/?linkid=21161) 提供) 來安裝這些更新。

**Update Compatibility Evaluator 和應用程式相容性工具組**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。這可能會觸發不相容性，而拉長部署安全性更新的時間。您可以使用 [Application Compatibility Toolkit](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 隨附的 [Update Compatibility Evaluator](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 元件，針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Microsoft Windows Vista、Windows Update、Microsoft 安全性更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非安全性、高優先順序更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](https://support.microsoft.com/kb/894199)： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](https://technet.microsoft.com/en-us/wsus/bb456965.aspx)。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的安全性保護，Microsoft 將在每月發行安全性更新之前，提前向重要安全性軟體提供者提供弱點資訊。安全性軟體提供者可利用此弱點資訊，透過其安全性軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有安全性軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](https://www.microsoft.com/security/msrc/mapp/partners.mspx)上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 安全性策略與社群

**更新程式管理策略**

[更新管理安全性指南](https://go.microsoft.com/fwlink/?linkid=21168) (英文) 提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](https://support.microsoft.com/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](https://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](https://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 [VUPEN Vulnerability Research Team](https://www.vupen.com/) 的 Sebastien Renaud 回報 MS10-032 中描述的一個問題
-   感謝 [Secunia Research](https://secunia.com/) 協助我們解決 MS10-032 中描述的問題
-   感謝 [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Yamata Li 回報 MS10-033 中描述的兩個問題
-   感謝 [NGS Software](https://www.ngssoftware.com/) 的 Shaun Colley 回報 MS10-034 中描述的一個問題
-   感謝卡內基美隆大學運算服務中心的 Chris Ries 回報 MS10-034 中描述的一個問題
-   感謝 [Casaba Security](https://www.casabasecurity.com/) 的 Chris Weber 回報 MS10-035 及 MS10-039 中描述的一個問題
-   感謝 [Mitsui Bussan Secure Directions, Inc.](https://www.mbsd.jp/) 的 Takeshi Terada 回報 MS10-035 中描述的一個問題
-   感謝 [Google Inc.](https://www.google.com/) 的 Michal Zalewski 回報 MS10-035 中描述的一個問題。
-   感謝 [Matasano Security](https://www.matasano.com/) 的 Chris Rohlf 回報 MS10-035 中描述的兩個問題
-   感謝 Peter Vreugdenhil 與 [TippingPoint](https://www.tippingpoint.com/) 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作，回報 MS10-035 中描述的一個問題
-   感謝 [IBM ISS X-Force](https://www.iss.net/) 的 David Dewey 和 [Accuvant](https://www.accuvant.com/) (舊稱 [VeriSign iDefense Labs](https://labs.idefense.com/)) 的 Ryan Smith 協助我們進行 MS10-036 中所述的深度防禦變更
-   感謝 Laserforce International 的 Chris Carton 與 [Secunia](https://secunia.com/) 合作回報 MS10-037 中描述的一個問題
-   感謝匿名的研究人員與 [TippingPoint](https://www.tippingpoint.com/) 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 MS10-038 中描述的一個問題
-   感謝 [VUPEN Vulnerability Research Team](https://www.vupen.com/) 的 Nicolas Joly 回報 MS10-038 中描述的八個問題
-   感謝 Fortinet 公司 [FortiGuard Labs](https://www.fortiguard.com/) 的 Bing Liu 回報 MS10-038 中描述的一個問題
-   感謝 [Secunia](https://secunia.com/) 的 Carsten Eiram 回報 MS10-038 中描述的兩個問題
-   感謝匿名的研究人員與 [TippingPoint](https://www.tippingpoint.com/) 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 MS10-038 中描述的一個問題
-   感謝位於美國亞利桑那州 Gilbert 的 Gilbert Public Schools 的 Rick Glaspie 回報 MS10-038 中描述的一個問題
-   感謝 Dallas County Community College District 的 Rik Jones 回報 MS10-039 中描述的一個問題
-   感謝 [WhiteHat Security](https://www.whitehatsec.com) 的 Arian Evans 回報在 ASP.NET 要求驗證中的略過問題 (該問題在 MS10-041 中是藉由深度防禦變更而解決)

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可洽詢[安全性支援](https://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 以取得技術支援。與安全性更新有關的支援電話不另外收費。如需更多可用支援選項的資訊，請參閱 [Microsoft 技術支援服務](https://support.microsoft.com/)。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。與安全性更新有關的支援電話不另外收費。如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](https://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2010 年 6 月 8 日)： 公告摘要發行。
-   V1.1 (2010 年 6 月 9 日)： 修訂＜受影響的軟體及下載位置＞一節中的 MS10-033 注意事項。
-   V2.0 (2011 年 9 月 13 日)： 重新發行 MS10-035 公告，以重新提供 Microsoft Windows 2000 和 Windows XP 上的 Internet Explorer 更新來解決一項偵測問題。安全性更新檔案沒有變更。已成功更新系統的客戶不必採取任何行動。

*Built at 2014-04-18T01:50:00Z-07:00*
