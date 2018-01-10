---
TOCTitle: 'MS13-NOV'
Title: 2013 年 11 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms13-nov'
ms:contentKeyID: 61237748
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms13-nov(v=Security.10)'
---

Security Bulletin Summary

2013 年 11 月份 Microsoft 資訊安全公告摘要
==========================================

發行: 2013年11月12日

**版本:** 1.0

此公告摘要列出 2013 年 11 月份發行之資訊安全公告。

發行 2013 年 11 月份資訊安全公告之後，此公告摘要將取代原先於 2013 年 11 月 7 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 資訊安全公告預先通知](http://go.microsoft.com/fwlink/?linkid=217213)。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術資訊安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2013 年 11 月 13 日太平洋時間上午 11 點 (美國與加拿大) 解答客戶對於這些公告的問題。[立即註冊參加 11 月份資訊安全公告網路廣播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032557383&culture=zh-tw)。

Microsoft 也會提供資訊協助客戶排定每月資訊安全更新以及任何非資訊安全更新的優先順序，其中這些非資訊安全更新的發行日期與每月資訊安全更新的發行日期相同。請參閱**＜其他資訊＞**一節。

### 公告資訊

#### 提要

下表依嚴重性摘要說明本月份資訊安全公告。

如需受影響的軟體之詳細資料，請參閱下節＜受影響的軟體＞。

 
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >公告編號</th>
<th style="border:1px solid black;" >公告標題與提要</th>
<th style="border:1px solid black;" >最高的嚴重性等級與資訊安全風險影響</th>
<th style="border:1px solid black;" >重新開機需求</th>
<th style="border:1px solid black;" >受影響的軟體</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer</strong> <strong>積存資訊安全更新</strong> <strong>(2888505)</strong><br />
<br />
本資訊安全更新可解決 Internet Explorer 中 10 項未公開報告的資訊安全風險。最嚴重的資訊安全風險可能會在使用者以 Internet Explorer 檢視蓄意製作的網頁時，允許遠端執行程式碼。成功利用其中最嚴重的資訊安全風險的攻擊者，可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325390">MS13-089</a></td>
<td style="border:1px solid black;"><strong>Windows</strong> <strong>圖形裝置介面中的資訊安全風險可能會允許遠端執行程式碼</strong> <strong>(2876331)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果使用者透過 WordPad 檢視或開啟蓄意製作的 Windows Write 檔案，此資訊安全風險可能會允許遠端執行程式碼。成功利用此資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329834">MS13-090</a></td>
<td style="border:1px solid black;"><strong>ActiveX Kill Bit (刪除位元)</strong> <strong>的積存資訊安全更新</strong> <strong>(2900986)</strong><br />
<br />
這個資訊安全更新可解決目前遭到利用的一項未公開報告的資訊安全風險。InformationCardSigninHelper 類別 ActiveX 控制項中存在此資訊安全風險。如果使用者透過具現化 ActiveX 控制項的 Internet Explorer 檢視蓄意製作的網頁，這些資訊安全風險可能會允許遠端執行程式碼。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325392">MS13-091</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office</strong> <strong>中的資訊安全風險可能會允許遠端執行程式碼</strong> <strong>(2885093)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Office中三項未公開報告的資訊安全風險。其中的資訊安全風險，可能會在受影響版本的 Microsoft Office 軟體開啟蓄意製作的 WordPerfect 文件檔案時，允許遠端執行程式碼。成功利用最嚴重的資訊安全風險的攻擊者，可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324692">MS13-092</a></td>
<td style="border:1px solid black;"><strong>Hyper-V</strong> <strong>中的資訊安全風險可能會允許權限提高</strong> <strong>(2893986)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果攻擊者將 Hypercall 中蓄意製作的函數參數從現有正在執行的虛擬機器傳送到 Hypervisor，則該資訊安全風險可能會允許權限提高。如果攻擊者將 Hypercall 中蓄意製作的函數參數從現有正在執行的虛擬機器傳送到 Hypervisor，則該資訊安全風險也可能會允許 Hyper-V 主機阻斷服務 (DoS)。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325391">MS13-093</a></td>
<td style="border:1px solid black;"><strong>Windows</strong> <strong>附屬功能驅動程式中的資訊安全風險可能會允許資訊洩漏</strong> <strong>(2875783)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果攻擊者以本機使用者的身分登入受影響的系統，並在系統上執行能讓攻擊者從較高權限帳戶取得資訊之蓄意製作的應用程式，則此資訊安全風險便可能允許資訊洩漏。攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
資訊洩漏</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324873">MS13-094</a></td>
<td style="border:1px solid black;"><strong>Microsoft</strong> <strong>Outlook</strong> <strong>中的資訊安全風險可能會允許資訊洩漏</strong> <strong>(2894514)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Outlook 中一項公開揭露的資訊安全風險。如果使用者使用受影響版本的 Microsoft Outlook 開啟或預覽蓄意製作的電子郵件訊息，此資訊安全風險可能會允許資訊洩漏。成功利用此資訊安全風險的攻擊者可確認系統資訊 (例如 IP 位址)，並從目標系統和與目標系統共用網路的其他系統開啟 TCP 連接埠。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
資訊洩漏</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320632">MS13-095</a></td>
<td style="border:1px solid black;"><strong>數位簽章中的資訊安全風險可能會允許阻斷服務</strong> <strong>(DoS) (2868626)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。受影響的 Web 服務處理蓄意製作的 X.509 憑證時，此資訊安全風險可能會允許阻斷服務 (DoS)。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
阻斷服務 (DoS)</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
資訊安全風險入侵指數  
--------------------
  
<span></span>
下表提供本月所述每個資訊安全風險的利用性評估。資訊安全風險皆根據公告編號和 CVE 編號依序列出。僅包含資訊安全公告中，嚴重性等級為「重大」或「重要」的資訊安全風險。
  
**我該如何使用這個表格？**
  
您可以運用此表格，針對您可能需要安裝的每一項資訊安全更新，瞭解資訊安全風險在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務 (DoS) 的可能性。請根據您特定的組態設定，檢閱下列各項評估，決定部署本月份更新的優先次序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 資訊安全風險索引](http://technet.microsoft.com/security/cc998259)。
  
在下方欄位中，「最新軟體版本」意指受影響軟體，「較舊軟體版本」意指受影響軟體所有較舊的支援版本，如公告中的「受影響的軟體」或「不受影響的軟體」表格裡所示。

 
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >公告編號</th>
<th style="border:1px solid black;" >資訊安全風險標題</th>
<th style="border:1px solid black;" >CVE ID</th>
<th style="border:1px solid black;" >最新軟體版本的資訊安全風險評估</th>
<th style="border:1px solid black;" >較舊軟體版本的資訊安全風險評估</th>
<th style="border:1px solid black;" >阻斷服務 (DoS) 資訊安全風險評估</th>
<th style="border:1px solid black;" >主要重點</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3871">CVE-2013-3871</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 資訊洩漏資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3908">CVE-2013-3908</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊洩漏的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 資訊洩漏資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3909">CVE-2013-3909</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊洩漏的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3910">CVE-2013-3910</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3911">CVE-2013-3911</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3912">CVE-2013-3912</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3914">CVE-2013-3914</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3915">CVE-2013-3915</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3916">CVE-2013-3916</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3917">CVE-2013-3917</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325390">MS13-089</a></td>
<td style="border:1px solid black;">圖形裝置介面整數溢位資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3940">CVE-2013-3940</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329834">MS13-090</a></td>
<td style="border:1px solid black;">InformationCardSigninHelper 資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3918">CVE-2013-3918</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">Microsoft 已發現有嘗試利用此資訊安全風險、有限且目標明確的攻擊。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325392">MS13-091</a></td>
<td style="border:1px solid black;">WPD 檔案格式記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0082">CVE-2013-0082</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325392">MS13-091</a></td>
<td style="border:1px solid black;">Word 堆疊緩衝區溢位資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1324">CVE-2013-1324</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325392">MS13-091</a></td>
<td style="border:1px solid black;">Word 堆積覆寫資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1325">CVE-2013-1325</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324692">MS13-092</a></td>
<td style="border:1px solid black;">位址損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3898">CVE-2013-3898</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325391">MS13-093</a></td>
<td style="border:1px solid black;">附屬功能驅動程式資訊洩漏資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3887">CVE-2013-3887</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊洩漏的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324873">MS13-094</a></td>
<td style="border:1px solid black;">S/MIME AIA 資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3905">CVE-2013-3905</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊洩漏的資訊安全風險。<br />
<br />
此資訊安全風險已經遭到公開揭發。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320632">MS13-095</a></td>
<td style="border:1px solid black;">數位簽章資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3869">CVE-2013-3869</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">暫時</td>
<td style="border:1px solid black;">這是一項阻斷服務 (DoS) 的資訊安全風險。</td>
</tr>
</tbody>
</table>
  
受影響的軟體  
------------
  
<span></span>
下表依據主要的軟體類別和嚴重性依序列出公告。
  
**我該如何使用這些表格？**
  
請用這些表格來瞭解可能需要安裝的資訊安全更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的資訊安全更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。
  
**注意**：一項資訊安全風險，可能需要安裝數個資訊安全更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
#### Windows 作業系統與元件

 
<table style="border:1px solid black;">
<tr>
<th colspan="7">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-088**](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](http://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr class="alternateRow">
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
**無**[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2888505)  
(重大)  
Internet Explorer 7   
(2888505)  
(重大)  
Internet Explorer 8   
(2888505)  
(重大)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2876331)  
(重大)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2900986)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2868626)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2888505)  
(重大)  
Internet Explorer 7   
(2888505)  
(重大)  
Internet Explorer 8   
(2888505)  
(重大)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2876331)  
(重大)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2900986)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2875783)  
(重要)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2868626)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-088**](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](http://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**無**[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2888505)  
(重要)  
Internet Explorer 7  
(2888505)  
(重要)  
Internet Explorer 8  
(2888505)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2876331)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2900986)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2868626)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2888505)  
(重要)  
Internet Explorer 7  
(2888505)  
(重要)  
Internet Explorer 8  
(2888505)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2876331)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2900986)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2875783)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2868626)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2888505)  
(重要)  
Internet Explorer 7  
(2888505)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(2876331)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(2900986)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(2875783)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(2868626)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-088**](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](http://go.microsoft.com/fwlink/?linkid=320632)
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
**無**[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2888505)  
(重大)  
Internet Explorer 8  
(2888505)  
(重大)  
Internet Explorer 9   
(2888505)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2876331)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2900986)  
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
(2868626)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2888505)  
(重大)  
Internet Explorer 8  
(2888505)  
(重大)  
Internet Explorer 9   
(2888505)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2876331)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2900986)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2875783)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2868626)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-088**](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](http://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**無**[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2888505)  
(重要)  
Internet Explorer 8  
(2888505)  
(重要)  
Internet Explorer 9   
(2888505)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2876331)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2900986)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2868626)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2888505)  
(重要)  
Internet Explorer 8  
(2888505)  
(重要)  
Internet Explorer 9   
(2888505)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2876331)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2900986)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2875783)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2868626)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2888505)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2876331)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2900986)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2875783)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2868626)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-088**](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](http://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr class="alternateRow">
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
**無**[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2888505)  
(重大)  
Internet Explorer 9   
(2888505)  
(重大)  
Internet Explorer 10   
(2888505)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2876331)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2900986)  
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
(2868626)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2888505)  
(重大)  
Internet Explorer 9   
(2888505)  
(重大)  
Internet Explorer 10   
(2888505)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2876331)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2900986)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2875783)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2868626)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-088**](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](http://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**無**[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2888505)  
(重要)  
Internet Explorer 9   
(2888505)  
(重要)  
Internet Explorer 10   
(2888505)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2876331)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2900986)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2875783)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2868626)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2888505)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2876331)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2900986)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2875783)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2868626)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows 8 和 Windows 8.1
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-088**](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](http://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr class="alternateRow">
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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2888505)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8  
(2876331)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8  
(2900986)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8  
(2868626)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2888505)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(2876331)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(2900986)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(僅限 Professional 和 Enterprise 版本)  
(2893986)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(2875783)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(2868626)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1
</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2888505)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(2876331)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(2900986)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(2868626)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1
</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2888505)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(2876331)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(2900986)  
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
(2868626)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2012 和 Windows Server 2012 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-088**](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](http://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2888505)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2876331)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2900986)  
(中度)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(僅限 Standard 與 Datacenter 版本，以及 Hyper-V Server 2012)  
(2893986)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2875783)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2868626)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2012 R2
</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2888505)  
(中度)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2876331)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2900986)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2868626)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows RT 和 Windows RT 8.1
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-088**](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](http://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr class="alternateRow">
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
**無**[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**無**[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2888505)  
(重大)
</td>
<td style="border:1px solid black;">
Windows RT  
(2876331)  
(重大)
</td>
<td style="border:1px solid black;">
Windows RT  
(2900986)  
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
(2868626)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT 8.1
</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2888505)  
(重大)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2876331)  
(重大)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2900986)  
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
(2868626)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Server Core 安裝選項
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-088**](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](http://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**無**[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2876331)  
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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2868626)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2876331)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2875783)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2868626)  
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
(2876331)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(2875783)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(2868626)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(2876331)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(2893986)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(2875783)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(2868626)  
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
(2876331)  
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
Windows Server 2012 R2 (Server Core 安裝)  
(2868626)  
(重要)
</td>
</tr>
</table>
 

#### Microsoft Office 套件及軟體

 
<table style="border:1px solid black;">
<tr>
<th colspan="3">
Microsoft Office 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-091**](http://go.microsoft.com/fwlink/?linkid=325392)
</td>
<td style="border:1px solid black;">
[**MS13-094**](http://go.microsoft.com/fwlink/?linkid=324873)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**無**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3  
(檔案格式轉換程式)  
(2760494)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office 2007
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-091**](http://go.microsoft.com/fwlink/?linkid=325392)
</td>
<td style="border:1px solid black;">
[**MS13-094**](http://go.microsoft.com/fwlink/?linkid=324873)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(檔案格式轉換程式)  
(2760415)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2007 Service Pack 3  
(2825644)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-091**](http://go.microsoft.com/fwlink/?linkid=325392)
</td>
<td style="border:1px solid black;">
[**MS13-094**](http://go.microsoft.com/fwlink/?linkid=324873)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
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
Microsoft Office 2010 Service Pack 1 (32 位元版本)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32 位元版本)  
(檔案格式轉換程式)  
(2553284)  
(重要)  
Microsoft Office 2010 Service Pack 1 (32 位元版本)  
(校訂工具)  
(2760781)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2010 Service Pack 1 (32 位元版本)  
(2837597)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(檔案格式轉換程式)  
(2553284)  
(無嚴重性等級)  
Microsoft Office 2010 Service Pack 2 (32 位元版本)  
(校訂工具)  
(2760781)  
(無嚴重性等級)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2010 Service Pack 2 (32 位元版本)  
(2837597)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64 位元版本)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64 位元版本)  
(檔案格式轉換程式)  
(2553284)  
(重要)  
Microsoft Office 2010 Service Pack 1 (64 位元版本)  
(校訂工具)  
(2760781)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2010 Service Pack 1 (64 位元版本)  
(2837597)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(檔案格式轉換程式)  
(2553284)  
(無嚴重性等級)  
Microsoft Office 2010 Service Pack 2 (64 位元版本)  
(校訂工具)  
(2760781)  
(無嚴重性等級)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2010 Service Pack 2 (64 位元版本)  
(2837597)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-091**](http://go.microsoft.com/fwlink/?linkid=325392)
</td>
<td style="border:1px solid black;">
[**MS13-094**](http://go.microsoft.com/fwlink/?linkid=324873)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
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
Microsoft Office 2013 (32 位元版本)
</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (32 位元版本)  
(檔案格式轉換程式)  
(2768005)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2013 (32 位元版本)  
(2837618)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2013 (64 位元版本)
</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (64 位元版本)  
(檔案格式轉換程式)  
(2768005)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2013 (64 位元版本)  
(2837618)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT
</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT  
(檔案格式轉換程式)  
(2768005)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2013 RT   
(2837618)  
(重要)
</td>
</tr>
</table>
 

偵測與部署工具及指南
--------------------

<span></span>
有幾項資源可協助系統管理員部署資訊安全更新。

-   Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，查看是否遺漏資訊安全更新及一般資訊安全設定錯誤的狀況。
-   Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 可協助系統管理員散佈資訊安全更新。
-   應用程式相容性工具組隨附的 Update Compatibility Evaluator 元件可針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

如需上述工具以及其他可使用工具的詳細資訊，請參閱 [IT專業人員的資訊安全工具](http://technet.microsoft.com/security/cc297183)。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

針對每個月第二個星期二發行的公告，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 及下載中心發行更新版本的 Microsoft Windows 惡意軟體移除工具。不定期資訊安全公告發行不提供更新版本的 Microsoft Windows 惡意軟體移除工具。

#### MU、WU 及 WSUS 上的非資訊安全更新

如需在 Windows Update 和 Microsoft Update 上發行的非資訊安全更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](http://support.microsoft.com/kb/894199)
-   ： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](http://technet.microsoft.com/wsus/bb456965)
-   。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的資訊安全保護，Microsoft 將在每月發行資訊安全更新之前，提前向重要資訊安全軟體提供者提供資訊安全風險資訊。資訊安全軟體提供者可利用此資訊安全風險資訊，透過其資訊安全軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://go.microsoft.com/fwlink/?linkid=215201) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 資訊安全策略與社群

**更新程式管理策略**

[更新管理資訊安全指南](http://go.microsoft.com/fwlink/?linkid=21168) (英文) 提供您有關套用資訊安全更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他資訊安全更新**

其他資訊安全問題的更新可由下列位置取得：

-   資訊安全更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。
-   消費性平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以資訊安全和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的資訊安全更新。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](http://support.microsoft.com/kb/913086)。

**IT** **專業人員資訊安全社群**

在 [IT 專業人員資訊安全社群](http://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升資訊安全以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類資訊安全議題的討論。

#### 感謝

Microsoft [感謝](http://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

**MS13-088**

-   感謝 Simon Zuckerbraun 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3871)
-   感謝 Masato Kinugawa 回報 Internet Explorer 資訊洩漏資訊安全風險 (CVE-2013-3908)
-   感謝 Sergey Markov 回報 Internet Explorer 資訊洩漏資訊安全風險 (CVE-2013-3909)
-   感謝 [Corelan](http://www.corelangcv.com/) 的 Peter 'corelanc0d3r' Van Eeckhoutte 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3910)
-   感謝 [Harmony Security](http://www.harmonysecurity.com/) 的 Stephen Fewer 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3911)
-   感謝 lokihardt@ASRT 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3912)
-   感謝匿名的研究人員與 [VeriSign iDefense Labs](http://labs.idefense.com) 合作，回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3914)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3915)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3916)
-   感謝匿名的研究人員與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3917)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3917)

**MS13-089**

-   感謝 [Secunia Research](http://secunia.com/) 的 Hossein Lotfi 回報圖形裝置介面整數溢位資訊安全風險 (CVE-2013-3940)

**MS13-090**

-   感謝 [Cyber Defense Institute, Inc.](http://www.cyberdefense.jp/) 的 ucq 和 Daiki Fukumori 回報 InformationCardSigninHelper 資訊安全風險 (CVE-2013-3918)
-   感謝 [iSIGHT Partners](http://www.isightpartners.com/) 協助我們解決 InformationCardSigninHelper 資訊安全風險 (CVE-2013-3918)
-   感謝 [FireEye](http://www.fireeye.com/) 的 Dan Caselden 和 Xiaobo Chen 協助我們解決 InformationCardSigninHelper 資訊安全風險 (CVE-2013-3918)

**MS13-091**

-   感謝 Merliton 回報 WPD 檔案格式記憶體損毀資訊安全風險 (CVE-2013-0082)
-   感謝 [CERT/CC](http://www.cert.org/) 的 Will Dormann 回報 Word 堆疊緩衝區溢位資訊安全風險 (CVE-2013-1324)
-   感謝 [CERT/CC](http://www.cert.org/) 的 Will Dormann 回報 Word 堆積覆寫資訊安全風險 (CVE-2013-1325)

**MS13-092**

-   thinktecture ([www.thinktecture.com](http://www.thinktecture.com)) & ERNW ([www.ernw.de](http://www.ernw.de); Felix Wilhelm) 代表 Bundesamt für Sicherheit in der Informationstechnik (BSI，德國資訊安全聯邦辦公室) 回報位址損毀資訊安全風險 (CVE-2013-3898)

**MS13-094**

-   感謝 [n.runs professionals GmbH](https://www.nruns.com/) 的 Alexander Klink 回報 S/MIME AIA 資訊安全風險 (CVE-2013-3905)

**MS13-095**

-   感謝 [Context Information Security](http://www.contextis.com/) 的 James Forshaw 回報數位簽章資訊安全風險 (CVE-2013-3869)

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 支援週期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   IT 專業人員的資訊安全解決方案： [TechNet 資訊安全疑難排解與支援](http://technet.microsoft.com/security/bb980617)
-   協助保護您的 Widows 電腦免於病毒和惡意軟體攻擊： [病毒解決方案與資訊安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   您所在國家/地區的當地支援： [國際支援](http://support.microsoft.com/common/international.aspx)

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2013 年 11 月 12 日)： 公告摘要發行。

*Built at 2014-04-18T01:50:00Z-07:00*
