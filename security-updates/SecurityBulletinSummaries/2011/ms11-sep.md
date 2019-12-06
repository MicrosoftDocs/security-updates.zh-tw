---
TOCTitle: 'MS11-SEP'
Title: 2011 年 9 月份 Microsoft 安全性公告摘要
ms:assetid: 'ms11-sep'
ms:contentKeyID: 61237725
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms11-sep(v=Security.10)'
---

2011 年 9 月份 Microsoft 安全性公告摘要
=======================================

發行: 2011年9月13日 | 更新: 2011年9月13日

**版本:** 1.1

此公告摘要列出 2011 年 9 月份所發行之安全性公告。

發行 2011 年 9 月份安全性公告之後，此公告摘要將取代原先於 2011 年 9 月 8 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](https://go.microsoft.com/fwlink/?linkid=217213)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2011 年 9 月 14 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。[立即註冊參加 9 月份安全性公告網路廣播](https://msevents.microsoft.com/cui/eventdetail.aspx?culture=en-us&eventid=1032487951)。在這個日期後，此網路廣播將可隨選取得。如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](https://go.microsoft.com/fwlink/?linkid=217214)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性更新的優先順序，其中這些非安全性更新的發行日期與每月安全性更新的發行日期相同。請參閱＜其他資訊＞一節。

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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=225825">MS11-070</a></td>
<td style="border:1px solid black;"><strong>WINS 中的弱點可能會允許權限提高 (2571621)</strong><br />
<br />
此安全性更新可解決 Windows 網際網路名稱服務 (WINS) 中一項未公開報告的弱點。如果使用者在執行 WINS 服務的受影響系統上接收到蓄意製作的 WINS 複寫封包，則這個弱點可能會允許權限提高。攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項弱點。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=223632">MS11-071</a></td>
<td style="border:1px solid black;"><strong>Windows 元件中的弱點可能會允許遠端執行程式碼 (2570947)</strong><br />
<br />
此安全性更新可解決 Microsoft Windows 中一項公開揭露的弱點。如果使用者開啟和蓄意製作之動態連結程式庫 (DLL) 檔案位在同一個網路目錄中的合法 Rich Text 格式檔案 (.rtf)、文字檔案 (.txt) 或 Word 文件 (.doc)，該弱點可能會允許遠端執行程式碼。成功利用此弱點的攻擊者可以取得與本機使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;"><strong>Microsoft Excel 中的弱點可能會允許遠端執行程式碼 (2587505)</strong><br />
<br />
此安全性更新可解決 Microsoft Office 中五項未公開報告的弱點。如果使用者開啟蓄意製作的 Excel 檔案，上述弱點可能會允許遠端執行程式碼。成功利用這類任一弱點的攻擊者可以取得與登入使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。安裝和設定 Office 檔案驗證 (OFV) 來防止開啟可疑的檔案，可阻止攻擊模式利用 CVE-2011-1986 和 CVE-2011-1987 中說明的弱點。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft 伺服器軟體</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=225103">MS11-073</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 中的弱點可能會允許遠端執行程式碼 (2587634)</strong><br />
<br />
此安全性更新可解決 Microsoft Office 中兩項未公開報告的弱點。如果使用者開啟蓄意製作的 Office 檔案，或開啟位於與蓄意製作的程式庫檔案相同網路目錄的合法 Office 檔案，此弱點可能會允許遠端執行程式碼。成功利用其中一項弱點的攻擊者可以取得與登入使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;"><strong>Microsoft SharePoint 中的弱點可能會允許提高權限 (2451858)</strong><br />
<br />
此安全性更新可解決 Microsoft SharePoint 及 Windows SharePoint Services 中五項未公開報告的弱點，以及一項公開揭露的弱點。如果使用者點選蓄意製作的 URL 或造訪蓄意製作的網站，則最嚴重的弱點可能會允許權限提高。就最嚴重的弱點而言，由於依預設 Internet Explorer 8 及 Internet Explorer 9 中的 XSS 篩選器可協助封鎖網際網路區域的攻擊，所以能降低 Internet Explorer 8 及 Internet Explorer 9 使用者瀏覽至網際網路區域中 SharePoint 網站時所承受的風險。然而，內部網路區域依預設並不會啟用 Internet Explorer 8 和 Internet Explorer 9 中的 XSS 篩選器。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft 伺服器軟體</td>
</tr>
</tbody>
</table>
 

弱點索引
--------

<span></span>
下表提供本月所述每個弱點的利用性評估。弱點皆根據公告編號和 CVE 編號依序列出。僅包含安全性公告中，嚴重性等級為「重大」或「重要」的弱點。

**我該如何使用這個表格？**

您可以運用此表格，針對您可能需要安裝的每一項安全性更新，瞭解弱點在安全性公告發行 30 日內遭成功利用而導致程式碼執行與拒絕服務的可能性。請根據您特定的組態設定，檢閱下列各項評估，決定部署本月份更新的優先次序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](https://technet.microsoft.com/security/cc998259.aspx)。

在下方欄位中，「最新軟體版本」意指受影響軟體，「較舊軟體版本」意指受影響軟體所有較舊的支援版本，如公告中的「受影響的軟體」或「不受影響的軟體」表格裡所示。

 
<p> </p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >公告編號</th>
<th style="border:1px solid black;" >弱點標題</th>
<th style="border:1px solid black;" >CVE ID</th>
<th style="border:1px solid black;" >最新軟體版本的程式碼執行弱點評估</th>
<th style="border:1px solid black;" >較舊軟體版本的程式碼執行弱點評估</th>
<th style="border:1px solid black;" >拒絕服務弱點評估</th>
<th style="border:1px solid black;" >主要重點</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=225825">MS11-070</a></td>
<td style="border:1px solid black;">WINS 本機權限提高弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1984">CVE-2011-1984</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=223632">MS11-071</a></td>
<td style="border:1px solid black;">Windows 元件不安全程式庫載入弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1991">CVE-2011-1991</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這項弱點已經公開揭露</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">Excel 釋放後使用 WriteAV 弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1986">CVE-2011-1986</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">Excel 陣列超出範圍索引弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1987">CVE-2011-1987</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">Excel 堆積損毀弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1988">CVE-2011-1988</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 可能撰寫出偶爾可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">Excel 條件運算式剖析弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1989">CVE-2011-1989</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">Excel 陣列超出範圍索引弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1990">CVE-2011-1990</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=225103">MS11-073</a></td>
<td style="border:1px solid black;">Office 元件不安全程式庫載入弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1980">CVE-2011-1980</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=225103">MS11-073</a></td>
<td style="border:1px solid black;">Office 未初始化物件指標弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1982">CVE-2011-1982</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">暫時</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">SharePoint 行事曆中 XSS 弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0653">CVE-2011-0653</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">HTML 清理弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1252">CVE-2011-1252</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊洩漏的弱點<br />
<br />
這項弱點已經公開揭露</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">Editform 指令碼插入弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1890">CVE-2011-1890</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">連絡人詳細資料反映式 XSS 弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1891">CVE-2011-1891</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">SharePoint 遠端檔案洩漏弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1892">CVE-2011-1892</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊洩漏的弱點</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">SharePoint XSS 弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1893">CVE-2011-1893</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能撰寫出可持續利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
</tbody>
</table>
  
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
<tr>
<th colspan="3">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-070**](https://go.microsoft.com/fwlink/?linkid=225825)
</td>
<td style="border:1px solid black;">
[**MS11-071**](https://go.microsoft.com/fwlink/?linkid=223632)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=70f944b0-9bf0-4168-b150-67d2ff68df2d)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4b9debed-edbb-43e1-b755-0faf01980289)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-070**](https://go.microsoft.com/fwlink/?linkid=225825)
</td>
<td style="border:1px solid black;">
[**MS11-071**](https://go.microsoft.com/fwlink/?linkid=223632)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1e6ac3b2-752e-49a0-84e5-5a8dfe955299)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d44274d2-0401-4fd8-bc4f-c59f6d81c34f)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f9378339-c58e-4e84-9427-85aeb35b0d99)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=935720ee-cee0-42c2-965e-ce1b07e95e1a)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=c35c71a8-13b4-47a6-9763-06f6f65327b1)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=78c2ac72-da89-42a4-bff9-79551b5d3c4e)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-070**](https://go.microsoft.com/fwlink/?linkid=225825)
</td>
<td style="border:1px solid black;">
[**MS11-071**](https://go.microsoft.com/fwlink/?linkid=223632)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=15840336-4886-4a1b-8c1e-2c535c3938f7)  
(重要)
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
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e80739b4-89bb-4317-8381-991244a71cb8)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-070**](https://go.microsoft.com/fwlink/?linkid=225825)
</td>
<td style="border:1px solid black;">
[**MS11-071**](https://go.microsoft.com/fwlink/?linkid=223632)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a9039660-3cc2-470d-a0a5-a70f78074495)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=05c39ab3-7b57-4147-8913-df5df6005799)\*  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2\*](https://www.microsoft.com/download/details.aspx?familyid=5ea78a9b-b1f7-4e94-b69e-c984e1622ae9)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2\*](https://www.microsoft.com/download/details.aspx?familyid=1499d988-fd55-4317-b859-ec170907d547)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6e2d2ea9-0af6-4d23-875d-3211722cd62f)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-070**](https://go.microsoft.com/fwlink/?linkid=225825)
</td>
<td style="border:1px solid black;">
[**MS11-071**](https://go.microsoft.com/fwlink/?linkid=223632)
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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=76b99ab2-7e99-4aad-a419-7996bae05c48)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=0f6d32de-d3ff-4af9-9b26-a4f12581f5fe)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-070**](https://go.microsoft.com/fwlink/?linkid=225825)
</td>
<td style="border:1px solid black;">
[**MS11-071**](https://go.microsoft.com/fwlink/?linkid=223632)
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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=f58cf343-946c-4e74-bd9c-40ac934a4986)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=a8a451bd-3e5c-4845-9941-daabd9418776)\*  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 和適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2 和適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=0fdfb1f9-20b3-4d61-8019-33d1003290c8)  
(重要)
</td>
</tr>
</table>
 
**Windows Server 2008 和 Windows Server 2008 R2 注意事項**

**\*會影響 Server Core 安裝。**無論上述受支援的 Windows Server 2008 或 Windows Server 2008 R2 版本是否使用 Server Core 安裝選項安裝，這個更新均以相同的嚴重性等級套用。如需此安裝選項的詳細資訊，請參閱 TechNet 文章：[管理 Server Core 安裝](https://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[維護 Server Core 安裝](https://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 和 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

#### Microsoft Office 套件及軟體

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="4">
Microsoft Office 套件和元件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-072**](https://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[**MS11-073**](https://go.microsoft.com/fwlink/?linkid=225103)
</td>
<td style="border:1px solid black;">
[**MS11-074**](https://go.microsoft.com/fwlink/?linkid=204797)
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
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=dee4f3d7-bc4b-47fd-8e3f-9d2b0e82d0f6)  
(KB2553072)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=7faa2f90-2e64-4dbf-ac93-bb8cffc9b5fe)  
(KB2584052)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=498ac241-d728-4944-abac-ec8444ca6418)  
(KB2553073)<sup>[1]</sup>
(重要)  
[Microsoft Office 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=df04b9ce-2daa-4b4d-a944-a873075656f9)  
(KB2553089)<sup>[1]</sup>
(重要)  
[Microsoft Office 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=90eef02b-db1f-4fdd-bb1d-408063671e4d)  
(KB2553090)<sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=34bbee95-0e83-4705-8bfe-02e4fb22f8e7)  
(KB2584063)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 和 Microsoft Office 2010 Service Pack 1 (32 位元版本)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 和 Microsoft Excel 2010 Service Pack 1 (32 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=4612c6e4-ac29-4cc4-9da5-88779ea3643e)  
(KB2553070)  
(重要)  
[Microsoft Office 2010 和 Microsoft Office 2010 Service Pack 1 (32 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=1fd15144-5547-4927-8583-8d9b06819226)  
(KB2553091)  
(重要)  
[Microsoft Office 2010 和 Microsoft Office 2010 Service Pack 1 (32 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=18840d78-944f-400a-addc-dce7e570a569)  
(KB2553096)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 和 Microsoft Office 2010 Service Pack 1 (32 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=3c8fd04a-9df6-4726-a9bc-811f49665981)  
(KB2584066)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 和 Microsoft Office 2010 Service Pack 1 (64 位元版本)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 和 Microsoft Excel 2010 Service Pack 1 (64 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=d40db27b-1318-4ca7-b44f-c90bb6342109)  
(KB2553070)  
(重要)  
[Microsoft Office 2010 和 Microsoft Office 2010 Service Pack 1 (64 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=f83800aa-6403-4341-afea-d363e54d5831)  
(KB2553091)  
(重要)  
[Microsoft Office 2010 和 Microsoft Office 2010 Service Pack 1 (64 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=92787e00-6f30-4020-9c1a-70270be5a623)  
(KB2553096)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 和 Microsoft Office 2010 Service Pack 1 (64 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=85360dc1-99e7-4e3e-be6f-3795e8a8122f)  
(KB2584066)  
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
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-072**](https://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[**MS11-073**](https://go.microsoft.com/fwlink/?linkid=225103)
</td>
<td style="border:1px solid black;">
[**MS11-074**](https://go.microsoft.com/fwlink/?linkid=204797)
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
無
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=868f4d9f-3498-4d59-a017-59204553889c)  
(KB2598782)  
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
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=afa79cfc-6e8a-4d0b-88aa-0d7e05031e44)  
(KB2598781)  
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
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](https://www.microsoft.com/download/details.aspx?familyid=535fcf4a-eeb2-44eb-b2a6-9c512509c49d)  
(KB2598783)  
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
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=9796588d-238f-4694-9598-1aa8d2becb55)  
(KB2598785)  
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
<th colspan="4">
Microsoft Office Groove 和 Microsoft SharePoint Workspace
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-072**](https://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[**MS11-073**](https://go.microsoft.com/fwlink/?linkid=225103)
</td>
<td style="border:1px solid black;">
[**MS11-074**](https://go.microsoft.com/fwlink/?linkid=204797)
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
無
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Groove 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office Groove 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5ea6192b-55e5-4ca4-8d91-cc768ede8277)  
(KB2552997)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Workspace 2010 和 Microsoft SharePoint Workspace 2010 Service Pack 1 (32 位元版本)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Workspace 2010 和 Microsoft SharePoint Workspace 2010 Service Pack 1 (32 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=f6ee7e43-9da9-4b96-abd0-390cfcacb885)  
(KB2566445)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Workspace 2010 和 Microsoft SharePoint Workspace 2010 Service Pack 1 (64 位元版本)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Workspace 2010 和 Microsoft SharePoint Workspace 2010 Service Pack 1 (64 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=234efac1-4f09-41f5-90a9-4a3c2e81c05e)  
(KB2566445)  
(重要)
</td>
</tr>
<tr>
<th colspan="4">
其他 Microsoft Office 軟體
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-072**](https://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[**MS11-073**](https://go.microsoft.com/fwlink/?linkid=225103)
</td>
<td style="border:1px solid black;">
[**MS11-074**](https://go.microsoft.com/fwlink/?linkid=204797)
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
無
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Excel Viewer Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Excel Viewer Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f82ca5da-a55a-487c-8170-46a40000c8e3)  
(KB2553075)  
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
Microsoft Office Word、Excel 及 PowerPoint 2007 檔案格式相容性套件 Service Pack 2
</td>
<td style="border:1px solid black;">
[Word、Excel 與 PowerPoint 2007 檔案格式的 Microsoft Office 相容性套件 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=01093f22-06b7-4c9b-bff9-f54ac5d73bf8)  
(KB2553074)  
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
 
**MS11-072 注意事項**

<sup>[1]</sup>針對 Microsoft Excel 2007 Service Pack 2，除了安全性更新套件 KB2553073、KB2553089、KB2553090 外，客戶也必須安裝 Word、Excel 與 PowerPoint 2007 檔案格式的 Microsoft Office 相容性套件 Service Pack 2 的安全性更新 (KB2553074)，才能有效防範此公告所說明的弱點。

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

**MS11-074 注意事項**

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

#### Microsoft 伺服器軟體

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="3">
Microsoft SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-072**](https://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[**MS11-074**](https://go.microsoft.com/fwlink/?linkid=204797)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 2 (32 位元版本)
</td>
<td style="border:1px solid black;">
[Microsoft Excel Services](https://www.microsoft.com/download/details.aspx?familyid=dd532201-485c-4270-88d3-63bd3f24327e)  
(KB2553093)<sup>[2]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 2 (coreserver) (32 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=ad52c341-13ce-4b53-87b4-269cb3f41275)  
(KB2508964)<sup>[1]</sup>
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (oserver) (32 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=fd6189c9-ab3b-441f-a901-6ac7f3b202aa)  
(KB2553001)<sup>[1]</sup>
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (sserverx) (32 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=d9601fae-4a80-45cd-a49b-ef441856d7e4)  
(KB2553002)<sup>[1]</sup>
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (dlc) (32 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=55b60e2f-ec68-4ccb-803a-5d03add8a1f1)  
(KB2553003)<sup>[1]</sup>
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 2 (64 位元版本)
</td>
<td style="border:1px solid black;">
[Microsoft Excel Services](https://www.microsoft.com/download/details.aspx?familyid=1086a5b0-e441-4e26-a8d1-924a20121dde)  
(KB2553093)<sup>[2]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 2 (coreserver) (64 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=e5e60751-242a-4fdb-9852-6d94050d3d0e)  
(KB2508964)<sup>[1]</sup>
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (oserver) (64 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=b1466366-e2ae-498e-b964-135e034e7348)  
(KB2553001)<sup>[1]</sup>
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (sserverx) (64 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=bb788c8d-8383-4e53-ac05-2a7dd9b83e70)  
(KB2553002)<sup>[1]</sup>
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (dlc) (64 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=e8e1a5bb-a552-45fe-8e81-e05fbfbb57ee)<sup>[1]</sup>
(重要)  
(KB2553003)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2010 和 Microsoft Office SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Excel Services](https://www.microsoft.com/download/details.aspx?familyid=0c150328-6a15-4852-a09c-4063142bd946)  
(KB2553094)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2010 與 Microsoft Office SharePoint Server 2010 Service Pack 1 (osrchwfe)](https://www.microsoft.com/download/details.aspx?familyid=c17eb04d-cbbc-457e-a424-4ee26b7a9654)  
(KB2494022)  
(重要)  
[Microsoft Office SharePoint Server 2010 與 Microsoft Office SharePoint Server 2010 Service Pack 1 (osrv)](https://www.microsoft.com/download/details.aspx?familyid=2a80a849-b712-47d4-9def-9395ee54a265)  
(KB2560885)  
(重要)  
[Microsoft Office SharePoint Server 2010 與 Microsoft Office SharePoint Server 2010 Service Pack 1 (pplwfe)](https://www.microsoft.com/download/details.aspx?familyid=b84c2bcb-0327-4916-871e-7a5c19b8c41b)  
(KB2560890)  
(重要)  
[Microsoft Office SharePoint Server 2010 與 Microsoft Office SharePoint Server 2010 Service Pack 1 (ppsmawfe)](https://www.microsoft.com/download/details.aspx?familyid=1597f295-02a9-4479-9d52-f18f0e83eaba)  
(KB2566456)  
(重要)  
[Microsoft Office SharePoint Server 2010 與 Microsoft Office SharePoint Server 2010 Service Pack 1 (dlc)](https://www.microsoft.com/download/details.aspx?familyid=e6b666a4-a795-441c-9bda-23e2de2e7b05)  
(KB2566954)  
(重要)  
[Microsoft Office SharePoint Server 2010 與 Microsoft Office SharePoint Server 2010 Service Pack 1 (ppsmamui)](https://www.microsoft.com/download/details.aspx?familyid=57592ce4-5d99-45c2-830f-380d67af8899)  
(KB2566958)  
(重要)  
[Microsoft Office SharePoint Server 2010 與 Microsoft Office SharePoint Server 2010 Service Pack 1 (wosrv)](https://www.microsoft.com/download/details.aspx?familyid=dd64a635-1e55-4b4d-9718-9b94c31c5625)  
(KB2566960)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office Forms Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-072**](https://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[**MS11-074**](https://go.microsoft.com/fwlink/?linkid=204797)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性** **等級**
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
Microsoft Office Forms Server 2007 Service Pack 2 (32 位元版本)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office Forms Server 2007 Service Pack 2 (32 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=c4c8ad7e-50bd-460e-9678-d8c72c6ee7ab)  
(KB2553005)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Forms Server 2007 Service Pack 2 (64 位元版本)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office Forms Server 2007 Service Pack 2 (64 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=7390b526-f411-45a4-8587-8077b473ac17)  
(KB2553005)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Groove Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-072**](https://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[**MS11-074**](https://go.microsoft.com/fwlink/?linkid=204797)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Groove Data Bridge Server 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office Groove Data Bridge Server 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5958247e-204e-409c-bdc1-7aff06e854b8)  
(KB2552999)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Groove Management Server 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office Groove Management Server 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6b5b4caf-6a95-487d-ac17-c4435225af3a)  
(KB2552998)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Groove Server 2010 和 Microsoft Groove Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Groove Server 2010 和 Microsoft Groove Server 2010 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=71c0f217-5112-4dca-b9aa-46c69f6099e4)  
(KB2508965)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office Web Apps
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-072**](https://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[**MS11-074**](https://go.microsoft.com/fwlink/?linkid=204797)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 和 Microsoft Office Web Apps 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Excel Web App 2010 和 Microsoft Excel Web App 2010 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=73d49094-a9cf-407e-8921-1b22fbc30427)  
(KB2553095)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps 2010 和 Microsoft Office Web Apps 2010 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=288a7394-b8d5-4445-bd4c-65bbf4b10eaf)  
(KB2566449)  
(重要)  
[Microsoft Word Web App 2010 和 Microsoft Word Web App 2010 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=152ff9f4-d720-41af-8f89-793133ece037)  
(KB2566450)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows SharePoint Services 和 Microsoft SharePoint Foundation
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-072**](https://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[**MS11-074**](https://go.microsoft.com/fwlink/?linkid=204797)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 2.0
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 2.0](https://www.microsoft.com/download/details.aspx?familyid=71e32745-cb05-4b87-a447-741ccdac7450)  
(KB2494007)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 2 (32 位元版本)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 Service Pack 2 (32 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=0f306cbd-a652-4e77-b394-1a6dc38ba83c)  
(KB2493987)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 2 (64 位元版本)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 Service Pack 2 (64 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=3137e4c6-783d-4461-88bd-90da064e3105)  
(KB2493987)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 和 Microsoft SharePoint Foundation 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010 和 Microsoft SharePoint Foundation 2010 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=0db799e2-896f-464b-8cd5-ecf2014f0588)  
(KB2494001)  
(重要)
</td>
</tr>
</table>
 
**MS11-072 注意事項**

<sup>[2]</sup>此更新適用於已安裝 Excel Services 的伺服器，例如 Microsoft Office SharePoint Server 2007 Enterprise 和 Microsoft Office SharePoint Server 2007 for Internet sites 的預設設定。Microsoft Office SharePoint Server 2007 Standard 不包含 Excel Services。

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

**MS11-074 注意事項**

<sup>[1]</sup>對於支援的 Microsoft Office SharePoint Server 2007 版本，除了安裝適用於 Microsoft Office SharePoint 2007 的安全性更新套件 (KB2508964、KB2553001、KB2553002 和 KB2553003) 外，客戶還需安裝適用於 Microsoft Windows SharePoint Services 3.0 的安全性更新 (KB2493987)，以避免受本公告中所述的弱點影響。

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和安全性更新。如需更多資訊，請參閱 [TechNet 更新管理中心](https://go.microsoft.com/fwlink/?linkid=69903) (英文)。[TechNet Security Center](https://go.microsoft.com/fwlink/?linkid=21171) 提供 Microsoft 產品安全性的其他資訊。消費者可以造訪[在家上網的安全性](https://go.microsoft.com/fwlink/?linkid=85102)網站，只要按一下 \[最新安全性更新\] 即可在此網站取得此資訊。

安全性更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 以及 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 取得。安全性更新也可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得。您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。

對於 Microsoft Office for Mac 的客戶，Microsoft AutoUpdate for Mac 可協助您保持最新的 Microsoft 軟體。如需使用 Microsoft AutoUpdate for Mac 的詳細資訊，請參閱[自動檢查軟體更新](https://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea) (英文)。

最後，您可以從 [Microsoft Update Catalog](https://go.microsoft.com/fwlink/?linkid=96155) 下載安全性更新。Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括安全性更新、驅動程式和 Service Pack。只要以安全性公告編號 (例如：MS07-036) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](https://go.microsoft.com/fwlink/?linkid=97900)。

**偵測與部署指南**

Microsoft 針對安全性更新提供偵測和部署指南。本指南所含之建議和資訊，能幫助 IT 專業人員瞭解如何使用用於安全性更新的偵測和部署的各種工具。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 961747](https://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少安全性更新以及一般安全性設定錯誤的狀況。如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134) 網站 (英文)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速而可靠地將 Microsoft Windows 2000 作業系統及更新版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 適用的最新重大更新與安全性更新部署到 Microsoft Windows 2000 及更新版本的作業系統中。

如需更多關於利用 Windows Server Update Services 部署安全性更新的資訊，請造訪 [Windows Server Update Services](https://technet.microsoft.com/en-us/wsus/default.aspx) 網站。

**System Center Configuration Manager 2007**

Configuration Manager 2007 軟體更新管理可簡化遞送和管理企業中 IT 系統更新的繁複作業。IT 系統管理員可以使用 Configuration Manager 2007 遞送 Microsoft 產品更新給各種裝置，包括桌上型電腦、筆記型電腦、伺服器及行動裝置。

Configuration Manager 2007 中的自動弱點評估會找出更新需求並報告建議動作。Configuration Manager 2007 中的軟體更新管理是建置在 Microsoft Windows Software Update Services (WSUS) 上，經過時間考驗，為全球 IT 系統管理員所熟悉的更新基礎架構。如需更多有關系統管理員如何使用 Configuration Manager 2007 來部署更新的資訊，請參閱[軟體更新管理](https://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx) (英文)。如需更多有關 Configuration Manager 的資訊，請造訪 [System Center Configuration Manager](https://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx)。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。

**注意：**System Management Server 2003 自 2010 年 1 月 12 日起不受主流支援。如需更多有關產品生命週期的資訊，請造訪 [Microsoft 產品技術支援週期](https://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle)。現已推出新版的 SMS：System Center Configuration Manager 2007；請參閱前段的＜System Center Configuration Manager 2007＞一節。

如需更多有關系統管理員如何使用 SMS 2003 來部署安全性更新的資訊，請參閱 [Microsoft Systems Management Server 2003 的案例與程序： 軟體發佈和補充程式管理](https://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en) (英文)。如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server TechCenter](https://technet.microsoft.com/en-us/systemcenter/bb545936.aspx)。

**注意** ：SMS 使用 Microsoft Baseline Security Analyzer 提供廣泛的安全性公告更新偵測與部署支援。不過這些工具可能無法偵測部分的軟體更新。在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](https://go.microsoft.com/fwlink/?linkid=33341)。某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。系統管理員可使用 Elevated Rights Deployment Tool (隨 [SMS 2003 Administration Feature Pack](https://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en) (英文) 提供) 來安裝這些更新。

**Update Compatibility Evaluator 和應用程式相容性工具組**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。這可能會觸發不相容性，而拉長部署安全性更新的時間。您可以使用 [Application Compatibility Toolkit](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 隨附的 [Update Compatibility Evaluator](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 元件，針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Microsoft Windows Vista、Windows Update、Microsoft 安全性更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非安全性更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](https://support.microsoft.com/kb/894199)： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](https://technet.microsoft.com/en-us/wsus/bb456965.aspx)。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的安全性保護，Microsoft 將在每月發行安全性更新之前，提前向重要安全性軟體提供者提供弱點資訊。安全性軟體提供者可利用此弱點資訊，透過其安全性軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有安全性軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](https://go.microsoft.com/fwlink/?linkid=215201)上列出的計畫合作夥伴所提供的主動保護計畫網站。

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

-   感謝 [Core Security Technologies](https://www.coresecurity.com/) 的 Nicolas Economou 回報 MS11-070 中描述的一項問題
-   感謝匿名的研究人員與 [VeriSign iDefense Labs](https://labs.idefense.com/) 合作回報 MS11-072 中描述的一項問題
-   感謝 [VeriSign iDefense Labs](https://labs.idefense.com/) 的 Sean Larsson 回報 MS11-072 中描述的一項問題
-   感謝匿名的研究人員與 [VeriSign iDefense Labs](https://labs.idefense.com/) 合作回報 MS11-072 中描述的一項問題
-   感謝匿名的研究人員與 [TippingPoint](https://www.tippingpoint.com/) 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作，回報 MS11-072 中描述的一項問題
-   感謝 Omair 與 [TippingPoint](https://www.tippingpoint.com/) 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作，回報 MS11-072 中描述的一項問題
-   感謝 Parvez Anwar 與 [Secunia Research](https://secunia.com/) 合作，回報 MS11-073 中描述的一項問題
-   感謝 [CERT/CC](https://www.cert.org/) 的 David Warrenfor 回報 MS11-073 中描述的一項問題
-   感謝 [Critical Path Training, LLC](https://www.criticalpathtraining.com/) 的 Andrew Connell 回報 MS11-074 中描述的一項問題
-   感謝 [Raytheon](https://www.raytheon.com/) 的 David Feldman 回報 MS11-074 中描述的一項問題
-   感謝 [IBM Rational Application Security](https://blog.watchfire.com/) 的 Adi Cohen，回報 MS11-074 中描述的一項問題
-   感謝 [Trend Micro](https://www.trendmicro.com/) 協助我們解決 MS11-074 中描述的一項問題
-   感謝 [ITT](https://www.itt.com/) 的 Pedro Jimenez 回報 MS11-074 中描述的一項問題
-   感謝 [Seeker 自動應用程式安全性測試解決方案](https://www.seekersec.com/)團隊回報 MS11-074 中描述的一項問題
-   感謝 [Agarri](https://www.agarri.fr/) 的 Nicolas Grégoire 回報 MS11-074 中描述的一項問題
-   感謝 [LaValley Consulting, LLC](https://www.lavalley.net) 的 Jim LaValley 回報 MS11-074 中描述的一項問題
-   感謝 [Seeker](https://www.seekersec.com) 的 Irene Abezgauz 協助我們進行 MS11-074 中所述之深度防禦變更

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可洽詢[安全性支援](https://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 以取得技術支援。與安全性更新有關的支援電話不另外收費。如需更多可用支援選項的資訊，請參閱 [Microsoft 技術支援服務](https://support.microsoft.com/)。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。與安全性更新有關的支援電話不另外收費。如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](https://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2011 年 9 月 13 日)： 公告摘要發行。
-   V1.1 (2011 年 9 月 13 日)： 針對 MS11-074，新增 Microsoft Office SharePoint Server 2010 和 Microsoft Office SharePoint Server 2010 Service Pack 1 (pplwfe) (KB2560890) 的更新連結。

*Built at 2014-04-18T01:50:00Z-07:00*
