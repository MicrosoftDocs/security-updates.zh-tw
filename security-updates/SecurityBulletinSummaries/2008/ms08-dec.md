---
TOCTitle: 'MS08-DEC'
Title: 2008 年 12 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms08-dec'
ms:contentKeyID: 61237679
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms08-dec(v=Security.10)'
---

2008 年 12 月份 Microsoft 資訊安全公告摘要
==========================================

發行: 2008年12月10日 | 更新: 2009年2月3日

**版本:** 5.0

此公告摘要列出 2008 年 12 月份發行之安全性公告。

發行 2008 年 12 月份公告之後，此公告摘要將取代原先於 2008 年 12 月 4 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](http://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播，於 2008 年 12 月 10 日太平洋時間早上十一點 (美國與加拿大)，解答客戶對於這些公告的問題。 [立即註冊參加 12 月份安全性公告網路廣播](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374647)。 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](http://www.microsoft.com/taiwan/security/bulletins/default.mspx)。

針對新增至此公告摘要 (MS08-078) 第 3.0 版的不定期安全性公告，Microsoft 將舉辦兩場網路廣播解決客戶對於這些公告的問題： 一場在在 2008 年 12 月 17 日太平洋時間下午 1 點 (美國與加拿大地區)，一場則是 2008 年 12 月 18 日太平洋時間上午 11 點。 立即註冊參加 [12 月 17 日的網路廣播](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032399448&culture=en-us)和 [12 月 18 日的網路廣播](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032399449&culture=en-us)。 在此之後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](http://www.microsoft.com/taiwan/security/bulletins/default.mspx)。

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-071">MS08-071</a></td>
<td style="border:1px solid black;"><strong>GDI 中的弱點可能會允許遠端執行程式碼 (956802)</strong><br />
<br />
這個安全性更新可解決 GDI 中兩項未公開報告的弱點。 如果使用者開啟蓄意製作的 WMF 影像檔案，攻擊者可利用上述任一弱點，允許遠端執行程式碼。 成功利用這類弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-075">MS08-075</a></td>
<td style="border:1px solid black;"><strong>Windows 搜尋的弱點可能會允許遠端執行程式碼 (959349)</strong><br />
<br />
這個安全性更新可解決 Windows 搜尋中兩項未公開報告的弱點。 如果使用者在 Windows 檔案總管中開啟和儲存蓄意製作的儲存搜尋檔案，或按一下蓄意製作的搜尋 URL，這些弱點可能會允許遠端執行程式碼。 成功利用這類弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-073">MS08-073</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 積存安全性更新 (958215)</strong><br />
<br />
這個安全性更新可解決四項未公開報告的弱點。 如果使用者使用 Internet Explorer 檢視蓄意製作的網頁，這些弱點可能會允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-078">MS08-078</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 安全性更新 (960714)</strong><br />
<br />
這個安全性更新能解決一項公開揭發的弱點。 如果使用者使用 Internet Explorer 檢視蓄意製作的網頁，這些弱點可能會允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-070">MS08-070</a></td>
<td style="border:1px solid black;"><strong>Visual Basic 6.0 執行階段延伸檔案 (ActiveX 控制項) 中的弱點可能允許遠端執行程式碼 (932349)</strong><br />
<br />
這個安全性更新可解決 Microsoft Visual Basic 6.0 執行階段延伸檔案 ActiveX 控制項中的五個未公開報告的弱點，以及一個已公開揭露的弱點。 如果使用者瀏覽到內含特製內容的網站，這些弱點可能會允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft 開發者工具和軟體、Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-072">MS08-072</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Word 的弱點可能會允許遠端執行程式碼 (957173)</strong><br />
<br />
這個安全性更新可解決 Microsoft Office Word 和 Microsoft Office Outlook 中八項未公開報告的弱點，這些弱點可在使用者開啟蓄意製作的 Word 或 RTF 格式 (RTF) 檔案時，允許從遠端執行程式碼。 成功利用這類弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-074">MS08-074</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Excel 的弱點可能會允許遠端執行程式碼 (959070)</strong><br />
<br />
此安全性更新可解決 Microsoft Office Excel 中三項未公開報告的弱點，該弱點可在使用者開啟蓄意製作的 Excel 檔案時，允許遠端執行程式碼。 成功利用這類弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-077">MS08-077</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office SharePoint Server 中的弱點可能會導致權限提高 (957175)</strong><br />
<br />
這個安全性更新能解決一項未公開報告的弱點。 如果攻擊者瀏覽至 SharePoint 網站上的系統管理 URL 來避開驗證，此弱點可能就會允許權限的提高。 攻擊成功會造成權限提高，進而導致拒絕服務或資訊洩漏。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office、Microsoft 伺服器軟體</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-076">MS08-076</a></td>
<td style="border:1px solid black;"><strong>Windows Media Components 中的弱點可能會允許遠端執行程式碼 (959807)</strong><br />
<br />
這個安全性更新可解決下列 Windows Media 元件中兩項未公開報告的弱點。 Windows Media Player、Windows Media Format Runtime、及 Windows Media Services。 最嚴重的弱點可能會允許遠端執行程式碼。 如果使用者以系統管理的使用者權限登入，成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
弱點索引  
--------
  
<span></span>
**我該如何使用這個表格？**
  
請用這個表格來瞭解您可能需要安裝的每個安全性更新，與 30 天內已發行的可利用程式碼受影響之可能性。 您應該檢閱下列的每個評估，按照特定的設定，將部署以優先次序排序。 如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](http://technet.microsoft.com/en-us/security/cc998259.aspx)。

 
<p> </p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >公告編號</th>
<th style="border:1px solid black;" >公告標題</th>
<th style="border:1px solid black;" >CVE ID</th>
<th style="border:1px solid black;" >弱點索引評估</th>
<th style="border:1px solid black;" >主要重點</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-070">MS08-070</a></td>
<td style="border:1px solid black;">Visual Basic 6.0 執行階段延伸檔案 (ActiveX 控制項) 中的弱點可能允許遠端執行程式碼 (932349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3704">CVE-2008-3704</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">可持續利用此漏洞的程式碼已公開</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-070">MS08-070</a></td>
<td style="border:1px solid black;">Visual Basic 6.0 執行階段延伸檔案 (ActiveX 控制項) 中的弱點可能允許遠端執行程式碼 (932349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4252">CVE-2008-4252</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-070">MS08-070</a></td>
<td style="border:1px solid black;">Visual Basic 6.0 執行階段延伸檔案 (ActiveX 控制項) 中的弱點可能允許遠端執行程式碼 (932349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4256">CVE-2008-4256</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-070">MS08-070</a></td>
<td style="border:1px solid black;">Visual Basic 6.0 執行階段延伸檔案 (ActiveX 控制項) 中的弱點可能允許遠端執行程式碼 (932349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4253">CVE-2008-4253</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能撰寫出偶爾可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-070">MS08-070</a></td>
<td style="border:1px solid black;">Visual Basic 6.0 執行階段延伸檔案 (ActiveX 控制項) 中的弱點可能允許遠端執行程式碼 (932349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4254">CVE-2008-4254</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能撰寫出偶爾可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-070">MS08-070</a></td>
<td style="border:1px solid black;">Visual Basic 6.0 執行階段延伸檔案 (ActiveX 控制項) 中的弱點可能允許遠端執行程式碼 (932349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4255">CVE-2008-4255</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能撰寫出偶爾可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">Windows 2000 系統的風險最大。 可利用此漏洞的程式碼不可能影響到 Windows XP SP2、Windows Server 2003 SP1、及更新的作業系統，因為這些作業系統的堆積保護功能更強大。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-071">MS08-071</a></td>
<td style="border:1px solid black;">GDI 中的弱點可能會允許遠端執行程式碼 (956802)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3465">CVE-2008-3465</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能撰寫出偶爾可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-071">MS08-071</a></td>
<td style="border:1px solid black;">GDI 中的弱點可能會允許遠端執行程式碼 (956802)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-2249">CVE-2008-2249</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-072">MS08-072</a></td>
<td style="border:1px solid black;">Microsoft Office Word 的弱點可能會允許遠端執行程式碼 (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4024">CVE-2008-4024</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-072">MS08-072</a></td>
<td style="border:1px solid black;">Microsoft Office Word 的弱點可能會允許遠端執行程式碼 (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4025">CVE-2008-4025</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能撰寫出偶爾可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-072">MS08-072</a></td>
<td style="border:1px solid black;">Microsoft Office Word 的弱點可能會允許遠端執行程式碼 (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4026">CVE-2008-4026</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能撰寫出偶爾可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-072">MS08-072</a></td>
<td style="border:1px solid black;">Microsoft Office Word 的弱點可能會允許遠端執行程式碼 (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4027">CVE-2008-4027</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能撰寫出偶爾可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-072">MS08-072</a></td>
<td style="border:1px solid black;">Microsoft Office Word 的弱點可能會允許遠端執行程式碼 (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4028">CVE-2008-4028</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能撰寫出偶爾可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-072">MS08-072</a></td>
<td style="border:1px solid black;">Microsoft Office Word 的弱點可能會允許遠端執行程式碼 (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4030">CVE-2008-4030</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能撰寫出偶爾可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-072">MS08-072</a></td>
<td style="border:1px solid black;">Microsoft Office Word 的弱點可能會允許遠端執行程式碼 (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4837">CVE-2008-4837</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能撰寫出偶爾可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-072">MS08-072</a></td>
<td style="border:1px solid black;">Microsoft Office Word 的弱點可能會允許遠端執行程式碼 (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4031">CVE-2008-4031</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-073">MS08-073</a></td>
<td style="border:1px solid black;">Internet Explorer 積存安全性更新 (958215)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4258">CVE-2008-4258</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-073">MS08-073</a></td>
<td style="border:1px solid black;">Internet Explorer 積存安全性更新 (958215)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4259">CVE-2008-4259</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-073">MS08-073</a></td>
<td style="border:1px solid black;">Internet Explorer 積存安全性更新 (958215)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4261">CVE-2008-4261</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-073">MS08-073</a></td>
<td style="border:1px solid black;">Internet Explorer 積存安全性更新 (958215)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4260">CVE-2008-4260</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能撰寫出偶爾可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-074">MS08-074</a></td>
<td style="border:1px solid black;">Microsoft Office Excel 的弱點可能會允許遠端執行程式碼 (959070)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4265">CVE-2008-4265</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-074">MS08-074</a></td>
<td style="border:1px solid black;">Microsoft Office Excel 的弱點可能會允許遠端執行程式碼 (959070)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4266">CVE-2008-4266</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-074">MS08-074</a></td>
<td style="border:1px solid black;">Microsoft Office Excel 的弱點可能會允許遠端執行程式碼 (959070)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4264">CVE-2008-4264</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能撰寫出偶爾可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-075">MS08-075</a></td>
<td style="border:1px solid black;">Windows 搜尋的弱點可能會允許遠端執行程式碼 (959349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4269">CVE-2008-4269</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-075">MS08-075</a></td>
<td style="border:1px solid black;">Windows 搜尋的弱點可能會允許遠端執行程式碼 (959349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4268">CVE-2008-4268</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能撰寫出偶爾可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-076">MS08-076</a></td>
<td style="border:1px solid black;">Windows Media 元件中的弱點可能會允許遠端執行程式碼 (959807)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3009">CVE-2008-3009</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">在這個問題中，可持續利用此漏洞的程式碼是有可能建立的， 不過，攻擊方式的性質有所侷限，所以不大可能發生實際攻擊。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-076">MS08-076</a></td>
<td style="border:1px solid black;">Windows Media 元件中的弱點可能會允許遠端執行程式碼 (959807)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3010">CVE-2008-3010</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">在這個問題中，可持續利用此漏洞的程式碼是有可能建立的， 不過，攻擊方式的性質有所侷限，所以不大可能發生實際攻擊。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-077">MS08-077</a></td>
<td style="border:1px solid black;">Microsoft Office SharePoint Server 中的弱點可能會導致權限提高 (957175)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4032">CVE-2008-4032</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">在這個問題中，可持續利用此漏洞的程式碼是有可能建立的， 然而，利用此項弱點的攻擊行為有可能只會造成資訊洩漏，不會造成遠端執行程式碼。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-078">MS08-078</a></td>
<td style="border:1px solid black;">Internet Explorer 安全性更新 (960714)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4844">CVE-2008-4844</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能撰寫出可持續利用此漏洞的程式碼<br />
(公開於公告發行)</td>
<td style="border:1px solid black;">在主動式攻擊中發現持續利用此漏洞的程式碼。 但是，以 Windows Vista 和 Windows Server 2008 預設安裝於受保護模式執行的 Internet Explorer，會使得攻擊較為困難。</td>
</tr>
</tbody>
</table>
  
受影響的軟體及下載位置  
----------------------
  
<span></span>
**我該如何使用這個表格？**
  
請用這個表格來瞭解可能需要安裝的安全性更新有哪些。 您應該查看此處列出的每一種軟體程式或元件，看看是否有需要的安全性更新。 若軟體程式或更新出現在清單中，則相關可用軟體更新也會以超連結方式提供，也會列出軟體更新的嚴重性等級。
  
**注意：**一項弱點可能需要安裝數個安全性更新才能妥善解決。 請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
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
</tr>
<tr>
<th colspan="6">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-071**](http://technet.microsoft.com/security/bulletin/ms08-071)
</td>
<td style="border:1px solid black;">
[**MS08-075**](http://technet.microsoft.com/security/bulletin/ms08-075)
</td>
<td style="border:1px solid black;">
[**MS08-073**](http://technet.microsoft.com/security/bulletin/ms08-073)
</td>
<td style="border:1px solid black;">
[**MS08-078**](http://technet.microsoft.com/security/bulletin/ms08-078)
</td>
<td style="border:1px solid black;">
[**MS08-076**](http://technet.microsoft.com/security/bulletin/ms08-076)
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
無
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=3b775fb1-1077-455d-af4a-4ccb5237974f)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=c242ba42-556b-4c87-bf33-9d99166ff096)  
(重大)  
[Microsoft Internet Explorer 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=c0583745-7e57-4265-9429-c3415cb8465f)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=d3e18732-47f1-40ce-999c-d1fd283bf138)  
(重大)  
[Microsoft Internet Explorer 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=124c14b6-9323-4f6f-902b-727aa56444bc)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Media Player 6.4](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=c33d558e-45f9-4e85-b48c-03bd0e8cb4bc)  
(KB954600)  
(重要)  
[Windows Media Format Runtime 7.1 及 Windows Media Format Runtime 9.0](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=6a459497-0ab8-41cb-87d0-b551631d8d8a)  
(KB952069)  
(重要)  
[Windows Media Services 4.1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=58b7d241-cef6-48fa-aa52-017695f71db1)  
(KB952068)  
(重要)
</td>
</tr>
<tr>
<th colspan="6">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-071**](http://technet.microsoft.com/security/bulletin/ms08-071)
</td>
<td style="border:1px solid black;">
[**MS08-075**](http://technet.microsoft.com/security/bulletin/ms08-075)
</td>
<td style="border:1px solid black;">
[**MS08-073**](http://technet.microsoft.com/security/bulletin/ms08-073)
</td>
<td style="border:1px solid black;">
[**MS08-078**](http://technet.microsoft.com/security/bulletin/ms08-078)
</td>
<td style="border:1px solid black;">
[**MS08-076**](http://technet.microsoft.com/security/bulletin/ms08-076)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
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
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 及 Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 及 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=2151fbba-c464-4d1e-82d4-5b096e82bed0)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=af9a6cb0-725d-490c-9858-16ec40e98560)  
(重大)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=1b582695-b3cc-4c65-bc4b-d673c9a6d82a)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=1d83e0af-46fa-4bfc-ba57-635435a7ef2d)  
(重大)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=0190a289-164e-41a7-8c01-fa1aaed3f531)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Media Player 6.4](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=99241309-e644-4088-a8f3-38837fab4037)  
(KB954600)  
(重要)  
[Windows Media Format Runtime 9.0、Windows Media Format Runtime 9.5、及 Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=504f816c-f554-4b93-ac28-b085574d9bac)  
(僅限 Windows XP Service Pack 2)  
(KB952069)  
(重要)  
[Windows Media Format Runtime 9.0、Windows Media Format Runtime 9.5、及 Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=ad76fcf3-a2f9-4e36-bd1b-c1536749173c)  
(僅限 Windows XP Service Pack 3)  
(KB952069)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2247f6a5-aa33-4c68-9ea8-a63488d126d3)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=60bf9851-24fe-4658-8333-d353e82063c7)  
(重大)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=107cf54b-29d4-4c54-b091-2b5b3ffbf49d)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=a585cb73-2c1a-4fa8-862a-ad6aeaeaf2f8)  
(重大)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=9ba71e23-8cef-4399-b215-983b0dcf5cb5)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Media Player 6.4](https://www.microsoft.com/download/details.aspx?familyid=946d47c9-b208-4fab-8ef6-774413d61bc8)  
(KB954600)  
(重要)  
[Windows Media Format Runtime 9.5](https://www.microsoft.com/download/details.aspx?familyid=644ef023-ee40-45b0-9c9d-c76d9fab0005)  
(KB952069)  
(重要)  
[Windows Media Format Runtime 9.5 x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=ae9e8b07-5354-42f3-a226-ba2193244524)  
(KB952069)  
(重要)  
[Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?familyid=2dadc017-2be5-4240-ab8f-0291756dca6b)  
(KB952069)  
(重要)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-071**](http://technet.microsoft.com/security/bulletin/ms08-071)
</td>
<td style="border:1px solid black;">
[**MS08-075**](http://technet.microsoft.com/security/bulletin/ms08-075)
</td>
<td style="border:1px solid black;">
[**MS08-073**](http://technet.microsoft.com/security/bulletin/ms08-073)
</td>
<td style="border:1px solid black;">
[**MS08-078**](http://technet.microsoft.com/security/bulletin/ms08-078)
</td>
<td style="border:1px solid black;">
[**MS08-076**](http://technet.microsoft.com/security/bulletin/ms08-076)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
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
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 與 Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=0c396796-0929-4cd2-99e8-3c0f7075a89e)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=d53adf6f-9501-4862-a1ca-57eb4d40cd75)  
(中度)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=9cdd4f9e-c578-405c-af9e-628f2d77fdf4)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=d81e9cf9-ce0c-463a-a359-49a348cb89ae)  
(重大)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=388847ec-817e-45cf-8fa7-32c7e1f57f80)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Media Player 6.4](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=2315ce20-2f46-42c2-bb40-045f003409d7)  
(KB954600)  
(重要)  
[Windows Media Format Runtime 9.5](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=d8958248-c889-499e-a6a9-3b394cdb27ea)  
(KB952069)  
(重要)  
[Windows Media Services 9 Series](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=e71abc2d-d60e-444a-9b7b-062c5805fe9e)  
(KB952068)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=6d5c7d2f-1a82-4cdf-b3f2-b2c2390c6a64)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=5e37cb34-32be-4bbe-87f3-c4e1974e4d00)  
(中度)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=7c36f92c-d8a0-4b70-b85f-83588a0299a0)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=015df302-d79f-43a1-b5c5-32ac04de0510)  
(重大)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=2ae17caf-6204-470e-8480-380d3d505657)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Media Player 6.4](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=4c29bed9-1b88-4d2f-80a5-305c2bedd89f)  
(KB954600)  
(重要)  
[Windows Media Format Runtime 9.5](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=2278022e-a716-46c0-bedf-d626933bd815)  
(KB952069)  
(重要)  
[Windows Media Format Runtime 9.5 x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=ae9e8b07-5354-42f3-a226-ba2193244524)  
(KB952069)  
(重要)  
[Windows Media Services 9 Series](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=e0030155-1a9a-46cc-bbc8-6d0d1ed65c1f)  
(KB952068)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP1 for Itanium-based Systems 和 Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP1 和適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=1edb62b4-3d0f-4891-b4b3-8f8bc4e7bdfe)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=0da4e424-4682-4401-a226-7d8f1be19d44)  
(中度)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=3811030d-5958-4b91-b5b8-20587dc7c4d6)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=18016305-7f72-47f6-ab4c-94282289bf5f)  
(重大)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=97d6c093-f68d-4ddf-8e3c-f29662a1940f)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="6">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-071**](http://technet.microsoft.com/security/bulletin/ms08-071)
</td>
<td style="border:1px solid black;">
[**MS08-075**](http://technet.microsoft.com/security/bulletin/ms08-075)
</td>
<td style="border:1px solid black;">
[**MS08-073**](http://technet.microsoft.com/security/bulletin/ms08-073)
</td>
<td style="border:1px solid black;">
[**MS08-078**](http://technet.microsoft.com/security/bulletin/ms08-078)
</td>
<td style="border:1px solid black;">
[**MS08-076**](http://technet.microsoft.com/security/bulletin/ms08-076)
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
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 和 Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=cddf9cf6-bdeb-4429-823a-879387a428d7)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=0dcc5373-0435-42d5-864d-298e5bb122d9)  
(KB958623)  
(重要)  
[Windows Vista 和 Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=5b1b65f0-6848-47c6-bdd5-be3c0621b323)  
(KB958624)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=3f62030a-9ce2-4c92-b948-143a6881921e)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=7887111d-4fac-4823-bdd2-a18d9468fdf0)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=1fcdc8dd-26d9-4d1a-8b3f-7b6a21a95999)  
(KB952069)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=73dc3775-b6f0-40f1-bd36-6b5fb80eb2fa)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=2112c5c8-7c9f-4491-b127-b1093085e105)  
(KB958623)  
(重要)  
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=eb1d0ffe-1644-457b-9e82-768bd4c7f7ab)  
(KB958624)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=d8800493-fba4-41f8-bde5-a53eeaf89d54)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=69979d92-8d45-47fe-ac4c-c2f1f23cf1fb)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=8839f6cd-dfbf-448c-bf1e-1da9bb5f3f25)  
(KB952069)  
(重要)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-071**](http://technet.microsoft.com/security/bulletin/ms08-071)
</td>
<td style="border:1px solid black;">
[**MS08-075**](http://technet.microsoft.com/security/bulletin/ms08-075)
</td>
<td style="border:1px solid black;">
[**MS08-073**](http://technet.microsoft.com/security/bulletin/ms08-073)
</td>
<td style="border:1px solid black;">
[**MS08-078**](http://technet.microsoft.com/security/bulletin/ms08-078)
</td>
<td style="border:1px solid black;">
[**MS08-076**](http://technet.microsoft.com/security/bulletin/ms08-076)
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
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=bbed9e8b-e75e-44ef-ba1d-fd6f852c1f67)\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=90ab7e6f-5ae7-4f55-8838-868fc98d8a16)\*\*\*  
(KB958623)  
(重要)  
[適用於 32 位元系統的 Windows Server 2008](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=470d506f-77ae-4a44-8598-df645f484295)\*\*\*  
(KB958624)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=45a0de3c-c7d1-4314-a456-1f7428b7c90a)\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=5552e564-dd1c-4e2a-9a42-6317522c884d)\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=91ec4195-bc1c-444e-a7b0-ebde46c088fa)  
(KB952069)  
(重要)  
[Windows Media Services 2008](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=ffb5d945-7f98-4849-b020-ed4873fa42df)\*  
(KB952068)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=48aecf4c-1296-490d-ba37-a28e3ec19bd6)\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=e1deab57-ada2-4b12-9157-5615e7b0071d)\*\*\*  
(KB958623)  
(重要)  
[適用於 x64 型系統的 Windows Server 2008](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=e41f23e4-6a2f-4ebb-b425-d241a08da316)\*\*\*  
(KB958624)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=405b28db-47d7-4d6b-90e6-834c0a409323)\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=889c6eb1-7d1f-4e60-b637-535cb6e4e443)\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=8cab6fe8-161d-4d8c-9772-eb3174a2c3c3)  
(KB952069)  
(重要)  
[Windows Media Services 2008](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=0204a366-5641-4036-9cb0-a46d04af9d72)\*  
(KB952068)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008](https://www.microsoft.com/download/details.aspx?familyid=9bfe15cd-02ff-45cf-85c8-5ff1e6c1a871)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008](https://www.microsoft.com/download/details.aspx?familyid=48bed90d-c243-4969-8e54-326d9a7af343)  
(KB958623)  
(重要)  
[適用於 Itanium 型系統的 Windows Server 2008](https://www.microsoft.com/download/details.aspx?familyid=83de2263-de2a-4c13-96ba-ecfebdaf0bb9)  
(KB958624)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=f0d4f321-941e-4da7-958f-582c75542ee8)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=06cb502a-6818-4599-aa24-6eddb83e4b84)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
</table>
 
**MS08-078 的注意事項**

這項由 MS08-078 解決的弱點是在 Windows Internet Explorer 8 Beta 2 發行之後回報。建議執行 Windows Internet Explorer 8 Beta 2 的客戶為其系統下載並套用更新程式。

安全性更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 以及 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) 取得。 安全性更新也可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得。 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。

**Windows Server 2008 注意事項**

**\*Windows Server 2008 Server Core 安裝會受影響。** 對於受支援的 Windows Server 2008 版本，無論 Windows Server 2008 是否使用 Server Core 安裝選項，這個更新均以相同的嚴重性等級套用。 如需這個安裝選項的詳細資訊，請參閱 [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**\*\*Windows Server 2008 Server Core 安裝不受影響。** 如果 Windows Server 2008 是使用 Server Core 安裝選項所安裝，則這項更新解決的弱點並不會影響受支援的 Windows Server 2008 版本。 如需這個安裝選項的詳細資訊，請參閱 [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**\*\*\*Windows Server 2008 server Core 安裝不受影響。** 如果 Windows Server 2008 是使用 Server Core 安裝選項所安裝，即使受到這些弱點影響的檔案可能會出現在系統上，這項更新解決的弱點並不會影響受支援的 Windows Server 2008 版本。 但是我們仍會將此更新提供給具有受影響之檔案的使用者，因為相較於您系統上目前的檔案，此更新檔案較新 (其版本號碼較高)。 如需這個安裝選項的詳細資訊，請參閱 [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

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
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="5">
Microsoft Office 套件、系統和元件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-070**](http://technet.microsoft.com/security/bulletin/ms08-070)
</td>
<td style="border:1px solid black;">
[**MS08-072**](http://technet.microsoft.com/security/bulletin/ms08-072)
</td>
<td style="border:1px solid black;">
[**MS08-074**](http://technet.microsoft.com/security/bulletin/ms08-074)
</td>
<td style="border:1px solid black;">
[**MS08-077**](http://technet.microsoft.com/security/bulletin/ms08-077)
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
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2000 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=43e8c4d8-307b-48f6-ac99-a9617421d40a)  
(KB956328)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2000 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=f39d2a49-f861-4f2d-bf91-94a8a85af40c)  
(KB958435)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=3ef41412-50b3-4077-b0e3-9a3704d2f876)  
(KB956329)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=72076e21-2aa3-48e8-883a-c3cb756fc72a)  
(KB958372)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
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
[Microsoft Office Word 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=45c81c60-4b1b-4246-839b-198ebc4eeae2)  
(KB956357)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=6c0771e5-fcd4-4365-b903-1a3bd95d9e66)  
(KB958436)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
2007 Microsoft Office System
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2007](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37)  
(KB956358)  
(重要)  
[Microsoft Office Outlook 2007](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37)  
(KB956358)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=68bb8d99-f28b-4efd-9314-3eee0bb00ccf)  
(KB958437)\*\*\*\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System Service Pack 1
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37)  
(KB956358)  
(重要)  
[Microsoft Office Outlook 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37)  
(KB956358)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=68bb8d99-f28b-4efd-9314-3eee0bb00ccf)  
(KB958437)\*\*\*\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office FrontPage
</td>
<td style="border:1px solid black;">
[Microsoft Office FrontPage 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=0a6130ae-c5b4-43cb-afe3-ab6a55b9d9ea)\*  
(KB957797)  
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Project
</td>
<td style="border:1px solid black;">
[Microsoft Office Project 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=89a44042-a629-40f3-800a-0bb45fc36591)  
(KB949045)  
(重大)  
[Microsoft Office Project 2007](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=2fbf6a5b-ff35-4a2d-9fa0-4e62b6486fe6)  
(KB949046)  
(重大)  
[Microsoft Office Project 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=2fbf6a5b-ff35-4a2d-9fa0-4e62b6486fe6)  
(KB949046)  
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
</tr>
<tr>
<th colspan="5">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-070**](http://technet.microsoft.com/security/bulletin/ms08-070)
</td>
<td style="border:1px solid black;">
[**MS08-072**](http://technet.microsoft.com/security/bulletin/ms08-072)
</td>
<td style="border:1px solid black;">
[**MS08-074**](http://technet.microsoft.com/security/bulletin/ms08-074)
</td>
<td style="border:1px solid black;">
[**MS08-077**](http://technet.microsoft.com/security/bulletin/ms08-077)
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
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
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
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=eca13ad8-62ae-41a8-b308-41e2d1773820)\*\*  
(KB960402)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=eca13ad8-62ae-41a8-b308-41e2d1773820)\*\*  
(KB960402)  
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
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=ab31a564-43d2-45bd-98bf-19e9ca477b62)\*\*  
(KB960401)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=ab31a564-43d2-45bd-98bf-19e9ca477b62)\*\*  
(KB960401)  
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
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=edb6cd8f-832c-4123-8982-ac0c601ea0a7)\*\*  
(KB960403)  
(重要)
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=edb6cd8f-832c-4123-8982-ac0c601ea0a7)\*\*  
(KB960403)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="5">
其他 Office 軟體
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-070**](http://technet.microsoft.com/security/bulletin/ms08-070)
</td>
<td style="border:1px solid black;">
[**MS08-072**](http://technet.microsoft.com/security/bulletin/ms08-072)
</td>
<td style="border:1px solid black;">
[**MS08-074**](http://technet.microsoft.com/security/bulletin/ms08-074)
</td>
<td style="border:1px solid black;">
[**MS08-077**](http://technet.microsoft.com/security/bulletin/ms08-077)
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
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Works 8](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=1537d181-90d9-4bb5-b5ae-8d9990a349af)\*\*\*  
(KB959487)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel Viewer
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 2003](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=4b3989ef-02b8-4bd2-b2ab-c3716079936e)  
(KB958434)  
(重要)  
[Microsoft Office Excel Viewer 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=4b3989ef-02b8-4bd2-b2ab-c3716079936e)  
(KB958434)  
(重要)  
[Microsoft Office Excel Viewer](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=9dbb35c1-aa7a-481b-a330-8ba916ddd443)  
(KB958442)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Word Viewer
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office Word Viewer 2003 Service Pack 3 與 Microsoft Office Word Viewer](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=70de7c3c-519f-4f4a-a03f-027f80b5415c)  
(KB956366)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
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
[Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=55430121-4476-48b8-9f6f-4a60fa0b2970)  
(KB956828)  
(重要)  
[Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=55430121-4476-48b8-9f6f-4a60fa0b2970)  
(KB956828)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=99cca4ed-f1f9-4cfd-a986-edbec82ced4f)  
(KB958439)  
(重要)  
[Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=99cca4ed-f1f9-4cfd-a986-edbec82ced4f)  
(KB958439)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007
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
[Microsoft Office SharePoint Server 2007 (32 位元版本)](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=f8f73997-6f4c-4b43-aa50-5c8276e83d3e)  
(KB956716)  
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 1 (32 位元版本)](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=f8f73997-6f4c-4b43-aa50-5c8276e83d3e)  
(KB956716)  
(重要)  
[Microsoft Office SharePoint Server 2007 (64 位元版本)](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=a7fda284-273c-42ab-8188-433beaacca86)  
(KB956716)  
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 1 (64 位元版本)](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=a7fda284-273c-42ab-8188-433beaacca86)  
(KB956716)  
(重要)
</td>
</tr>
</table>
 
**MS08-070 注意事項**  
另請參閱下節＜Microsoft 開發者工具和軟體＞，瞭解更多更新檔案。 本公告涉及 Microsoft Office 與 Microsoft 開發者工具和軟體。

**MS08-077 注意事項**  
另請參閱＜Microsoft 伺服器軟體＞小節，瞭解更多更新檔案。 本公告涉及 Microsoft Office 套件和軟體，以及 Microsoft 伺服器軟體。

**MS08-070 中的 Microsoft Office FrontPage 注意事項**  
\* 此更新程式僅適用於簡體中文 (中國)、泛亞中文 (香港)、繁體中文 (臺灣) 和韓文版本的 FrontPage 2002 Service Pack 3。

**MS08-072 和 MS08-074 中的 Microsoft Office for Mac 注意事項**  
\*\*MS08-072 和 MS08-074 中的對應更新是相同的。因為這些弱點存在於相同檔案中，所以這兩個公告所提及的更新均相同。

**MS08-072 中的 Works 8 注意事項**  
\*\*\*為能接收此安全性更新，執行 Microsoft Works 8.0 的客戶必須先更新到 Works 8.5，如 [Microsoft Works Update](http://www.microsoft.com/products/works/international/update_1001.mspx) 中所述。 所有使用 Microsoft Works 8.0、Works Suite 2004、及 Works Suite 2005 的客戶也包括在內。至於執行 Works Suite 2006 的客戶，Works 8.5 已包含其中。

**MS08-074 中 Microsoft Office Excel 2007 和 Microsoft Office Excel 2007 Service Pack 1 的注意事項**  
\*\*\*\*針對 Microsoft Office Excel 2007 和 Microsoft Office Excel 2007 Service Pack 1，除了安全性更新套件 KB958437 外，客戶也需安裝[適用於 Word、Excel 及 PowerPoint 2007 檔案格式的 Microsoft Office 相容性套件的安全性更新](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=99cca4ed-f1f9-4cfd-a986-edbec82ced4f) (KB958439)，以免受 MS08-074 中描述的弱點影響。已成功安裝 KB958437 和 KB958439 更新套件的客戶不必重新安裝。

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
Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-070**](http://technet.microsoft.com/security/bulletin/ms08-070)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Basic
</td>
<td style="border:1px solid black;">
[Microsoft Visual Basic 6.0 執行階段延伸檔案](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=e27eebcb-095d-43ec-a19e-4a46e591715c)  
(KB926857)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio .NET
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2002 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=afad980d-7f27-49d9-aa23-b762c7b94cd6)  
(KB958392)  
(重大)  
[Microsoft Visual Studio .NET 2003 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=6ac7cf8f-d046-43a8-b4ef-253153d65aed)  
(KB958393)  
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual FoxPro
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 8.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=a6977f81-f7f6-486b-96ad-8d296d79f205)  
(KB958369)  
(重大)  
[Microsoft Visual FoxPro 9.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=386d27a6-b2c7-4acc-bf3e-edcbc7358172)  
(KB958370)  
(重大)  
[Microsoft Visual FoxPro 9.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5b1f28a9-da8d-463a-8ae4-dfc8fcc6c41a)  
(KB958371)  
(重大)
</td>
</tr>
</table>
 
**MS08-070 注意事項**
另請參閱上節＜Microsoft Office 套件及軟體＞，瞭解更多更新檔案。 本公告涉及 Microsoft Office 套件和軟體，以及 Microsoft 開發者工具和軟體。

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
Search Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-077**](http://technet.microsoft.com/security/bulletin/ms08-077)
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
Microsoft Search Server
</td>
<td style="border:1px solid black;">
[Microsoft Search Server 2008 (32 位元版本)](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=f8f73997-6f4c-4b43-aa50-5c8276e83d3e)\*  
(KB956716)  
(重要)  
[Microsoft Search Server 2008 (64 位元版本)](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=a7fda284-273c-42ab-8188-433beaacca86)\*\*  
(KB956716)  
(重要)
</td>
</tr>
</table>
 
**MS08-077 注意事項**

\*包括 Microsoft Search Server 2008 Express (32 位元)

\*\*包括 Microsoft Search Server 2008 Express (64 位元)

另請參閱＜Microsoft Office 套件及軟體＞小節，瞭解更多更新檔案。 本公告涉及 Microsoft Office 套件和軟體，以及 Microsoft 伺服器軟體。

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和安全性更新。 如需更多資訊，請參閱 [TechNet 更新管理中心](http://www.microsoft.com/taiwan/technet/updatemanagement/default.mspx)。 [TechNet Security Center](http://www.microsoft.com/taiwan/technet/security/default.mspx) 提供 Microsoft 產品安全性的其他資訊。 消費者可以造訪[在家上網的安全性](http://www.microsoft.com/taiwan/athome/security/default.mspx)網站，只要按一下 \[最新安全性更新\] 即可在此網站取得此資訊。

安全性更新可以從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)、[Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)及 [Office Update](http://office.microsoft.com/zh-tw/downloads/default.aspx)取得。 安全性更新也可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得。 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。

最後，您可以從 [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) 下載安全性更新。 Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括安全性更新、驅動程式和 Service Pack。 只要以安全性公告編號 (例如，"MS07-036") 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。 如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](http://go.microsoft.com/fwlink/?linkid=97900)。

**偵測與部署指南**

Microsoft 已提供本月安全性更新之偵測與部署指南。 此指南還能幫助 IT 專業人員瞭解如何使用各項工具來協助部署安全性更新，像是 Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office Detection Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool (加強版安全性更新清查工具，ESUIT)。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 910723](http://support.microsoft.com/kb/910723)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少安全性更新以及一般安全性設定錯誤的狀況。 如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) 網站 (英文)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速可靠地將 Windows 2000 作業系統及更新系統版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 等最新的重大更新與安全性更新部署到 Windows 2000 及更新作業系統版本中。

如需更多關於利用 Windows Server Update Services 部署安全性更新的資訊，請造訪 [Windows Server Update Services](http://www.microsoft.com/taiwan/windowsserversystem/updateservices/evaluation/overview.mspx) 網站。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。 現已推出新版的 SMS，System Center Configuration Manager 2007；另請參閱 [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)。如需更多有關系統管理員如何能使用 SMS 2003 部署安全性更新的資訊，請參閱 [SMS 2003 安全性修補程式管理](http://www.microsoft.com/taiwan/smserver/evaluation/capabilities/patch.htm)。 SMS 2.0 使用者也可以利用 [SMS 軟體更新服務功能套件](http://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/suspack/default.htm)來協助部署安全性更新。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server](http://www.microsoft.com/taiwan/smserver/)。

**注意：**SMS 使用 Microsoft Baseline Security Analyzer 及 Microsoft Office Detection Tool，為安全性公告更新的偵測及部署作業提供相當廣泛的支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可以用 Elevated Rights Deployment Tool (隨 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/taiwan/smserver/downloads/2003/adminpack.htm) 和 [SMS 管理功能套件](http://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/adminpack/default.htm) 提供) 來安裝這些更新。

**Update Compatibility Evaluator 和 Application Compatibility Toolkit**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。 這可能會觸發不相容性，而拉長部署安全性更新的時間。 您可以使用 [Application Compatibility Toolkit 5.0](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 隨附的 [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 元件，針對所安裝的應用程式，簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Microsoft Windows Vista、Windows Update、Microsoft 安全性更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非安全性、高優先順序更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [icrosoft 知識庫文件編號 894199](http://support.microsoft.com/kb/894199)： Software Update Services 與 Windows Server Update Services 的說明內容在 2008 年有所變動。其中也包括所有 Windows 的內容。
-   [適用於 Microsoft 產品 (除了 Microsoft Windows 以外) 的全新、修訂版以及已發行的更新](http://technet.microsoft.com/en-us/wsus/bb466214.aspx)。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的安全性保護，Microsoft 將在每月發行安全性更新之前，提前向重要安全性軟體提供者提供弱點資訊。 安全性軟體提供者可利用此弱點資訊，透過其安全性軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。 如果要判斷是否有安全性軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://www.microsoft.com/security/msrc/mapp/partners.mspx)上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 安全性策略與社群

**更新程式管理策略**

[更新程式管理安全性指南](http://www.microsoft.com/taiwan/technet/security/topics/patchmanagement.mspx)提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](http://support.microsoft.com/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](http://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](http://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 [VenusTech](http://www.venustech.com.cn/) 的 ADLab 回報 MS08-070 中描述的問題
-   感謝 [Affiliated Computer Services](http://www.acs-inc.com/) 的 Jason Medeiros 回報 MS08-070 中描述的問題
-   感謝 [Secunia Research](http://secunia.com/) 的 Carsten Eiram 回報 MS08-070 中描述的問題
-   感謝 Mark Dowd 與 [McAfee Avert Labs](http://www.avertlabs.com/) 合作回報 MS08-070 中描述的問題
-   感謝 [Insomnia Security](http://www.insomniasec.com/) 的 Brett Moore 回報 MS08-070 中描述的問題
-   感謝 CHkr\_D591 與 [TippingPoint](http://www.tippingpoint.com/) 和 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 MS08-070 中描述的問題
-   感謝 Michal Bucko 與 [CERT/CC](http://www.cert.org/) 合作回報 MS08-070 中描述的問題
-   感謝賽門鐵克的 [Security Intelligence Analysis Team](http://www.symantec.com/) 與我們合作解決 MS08-070 中描述的問題
-   感謝 [Verisign iDefense Labs](http://labs.idefense.com/) 的 Jun Mao 回報 MS08-071 中描述的問題
-   感謝 Juan Caballero 與[卡內基美隆大學 Bitblaze 小組及加州大學柏克萊分校](http://bitblaze.cs.berkeley.edu/)合作回報 MS08-071 中描述的問題
-   感謝 [Core Security Technologies](http://www.coresecurity.com/) 的 Ricardo Narvaja 回報 MS08-072 中描述的問題
-   感謝 [Secunia Research](http://secunia.com/) 的 Dyon Balding 回報 MS08-072 中描述的問題
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Yamata Li 回報 MS08-072 中描述的問題
-   感謝 Wushi 與 [TippingPoint](http://www.tippingpoint.com/) 及 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 MS08-072 中描述的問題
-   感謝 [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/) 的 Aaron Portnoy 回報 MS08-072 中描述的問題。
-   感謝 [team509](http://www.team509.com/) 的 Wushi 與 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 MS08-072 中描述的問題。
-   感謝 Wushi 和 Ling 與 [TippingPoint](http://www.tippingpoint.com/) 及 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 MS08-072 中描述的問題
-   感謝 Carlo Di Dato (亦稱 shinnai) 回報 MS08-073 中描述的問題
-   感謝 Brett Moore 與 [TippingPoint](http://www.tippingpoint.com/) 及 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 MS08-073 中描述的問題
-   感謝 [Casaba Security](http://www.casabasecurity.com/) 的 Chris Weber 回報 MS08-073 中描述的問題
-   感謝 [Verisign iDefense Labs](http://labs.idefense.com/) 的 Jun Mao 回報 MS08-073 中描述的問題
-   感謝 [Verisign iDefense Labs](http://labs.idefense.com/) 的 Joshua J. Drake 回報 MS08-074 中描述的問題
-   感謝 [signedness.org](http://www.signedness.org/) 的 Claes M Nyberg 回報 MS08-074 中描述的問題
-   感謝 [Secunia](http://secunia.com/) 的 Dyon Balding 回報 MS08-074 中描述的問題
-   感謝 [eEye Digital Security](http://www.eeye.com/) 的 Andre Protas 回報 MS08-075 中描述的問題
-   感謝 Nate McFeters 回報 MS08-075 中描述的問題
-   感謝一位匿名的發現者回報 MS08-077 中描述的問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可電洽 1-866-PCSAFETY [Microsoft 產品支援服務](http://go.microsoft.com/fwlink/?linkid=21131)以取得技術支援。 與安全性更新有關的支援電話不另外收費。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與安全性更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](http://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2008 年 12 月 10 日)： 公告摘要發行。
-   V2.0 (2008 年 12 月 12 日)： 針對 MS08-076 修正受影響的軟體，已將 Windows Media Format Runtime 9.5 和 Windows Media Format Runtime 11 列為對 Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2 各自獨立的更新。同時移除 MS08-076 的錯誤參照 Windows XP Professional x64 Edition、Windows XP Professional x64 Edition Service Pack 2、Windows Server 2003 x64 Edition，以及 Windows Server 2003 x64 Edition Service Pack 2 上的 Windows Media Format Runtime 11 x64 Edition。
-   V3.0 (2008 年 12 月 17 日)： 新增 Microsoft 安全性公告 MS08-078，Internet Explorer 安全性更新 (960714)。 另外還新增此不定期安全性公告的公告網路廣播連結。
-   V3.1 (2008 年 12 月 18 日)： 針對適用於 32 位元系統之 Windows Server 2008 中的 Internet Explorer 7，以及適用於 x64 型系統之 Windows Server 2008 中的 Internet Explorer 7，在 MS08-078 中新增不受影響的伺服器核心標註。
-   V3.2 (2009 年 1 月 7 日)： 從適用於 MS08-072 之受影響的軟體移除 Microsoft Office Word Viewer 2003。
-   V4.0 (2009 年 1 月 13 日)： Microsoft 已重新發行 MS08-076，目的在於針對 Windows XP Service Pack 2 (KB952069) 以及 Windows XP Service Pack 3 (KB952069) 上的 Windows Media Format Runtime 9.5，提供新的更新套件。 執行其他所有受支援或受影響版本的 Windows Media 元件的客戶，若已套用原來的 MS08-076 安全性更新套件，則不必再進行任何進一步的動作。 除此之外還針對 MS08-076，將 Windows Media Player 6.4 與 Windows Media Services 4.1 列為 Microsoft Windows 2000 Service Pack 4 所有版本上的受影響軟體；有收到此更新 (Windows Media Player 6.4 為 KB954600，而 Windows Media Services 4.1 則為 KB952068)，但尚未套用更新的客戶，必須加以套用。 最後，針對 MS08-072，將 Microsoft Office Word Viewer 列為受影響的軟體；已順利安裝安全性更新 KB956366 的客戶不必再重新安裝。
-   V5.0 (2009 年 2 月 03 日)： ＜受影響的軟體＞表中的 MS08-074 新增註腳，內容與 Microsoft Office Excel 2007 支援版本的安全性更新套件 KB958437 和 KB958439 相關。安全性更新二進位檔案或偵測沒有變更。 具有 Microsoft Office Excel 2007 或 Microsoft Office Excel 2007 Service Pack 1，且已成功安裝 KB958437 和 KB958439 的客戶不必重新安裝。

*Built at 2014-04-18T01:50:00Z-07:00*
