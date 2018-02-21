---
TOCTitle: 'MS14-JUL'
Title: 2014 年 7 月 Microsoft 資訊安全公告摘要
ms:assetid: 'ms14-jul'
ms:contentKeyID: 62554724
ms:date: '08/08/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms14-jul(v=Security.10)'
---

2014 年 7 月 Microsoft 資訊安全公告摘要
=======================================

發行日期： 2014 年 7 月 8 日 | 更新日期： 2014 年 7 月 29 日

**版本：** 1.1

此公告摘要列出 2014 年 7 月發行之資訊安全公告。

發行 2014 年 7 月份資訊安全公告之後，此公告摘要將取代原先於 2014 年 7 月 3 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 資訊安全公告預先通知](http://go.microsoft.com/fwlink/?linkid=217213)。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術資訊安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播，於 2014 年 7 月 9 日太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。若要檢視每月網路廣播和其他資訊安全公告網路廣播的連結，請參閱 [Microsoft 資訊安全公告網路廣播](http://technet.microsoft.com/security/dn756352)。

Microsoft 也會提供資訊協助客戶排定每月資訊安全更新以及任何非資訊安全更新的優先順序，其中這些非資訊安全更新的發行日期與每月資訊安全更新的發行日期相同。請參閱**＜其他資訊＞**一節。

提要
----

下表依嚴重性摘要說明本月份資訊安全公告。

如需受影響的軟體之詳細資料，請參閱下節＜**受影響的軟體**＞。

<p></p> 
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 積存資訊安全更新 (2975687)<br />
<br />
</strong>此資訊安全更新可解決 Internet Explorer 中一項公開揭露的資訊安全風險，以及二十四項未公開報告的資訊安全風險。其中最嚴重的資訊安全風險，可能在使用者以 Internet Explorer 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用這些資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402326">MS14-038</a></td>
<td style="border:1px solid black;"><strong>Windows 筆記本中的資訊安全風險可能會允許遠端執行程式碼 (2975689)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果使用者開啟蓄意製作的筆記本檔案，此資訊安全風險可能會允許遠端執行程式碼。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402327">MS14-039</a></td>
<td style="border:1px solid black;"><strong>螢幕小鍵盤中的資訊安全風險可能會允許提高權限 (2975685)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果攻擊者利用低完整性程序中的資訊安全風險來執行螢幕小鍵盤 (OSK)，並上傳蓄意製作的程式到目標系統，這項資訊安全風險可能就會允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402328">MS14-040</a></td>
<td style="border:1px solid black;"><strong>附屬功能驅動程式 (AFD) 中的資訊安全風險可能會允許權限提高 (2975684)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果攻擊者登入系統並執行蓄意製作的應用程式，則這個資訊安全風險可能允許權限提高。攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402330">MS14-041</a></td>
<td style="border:1px solid black;"><strong>DirectShow 中的資訊安全風險可能會允許權限提高 (2975681)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。若攻擊者先利用另一個低完整性程序中的資訊安全風險，再使用此資訊風險在已登入使用者的權限層級中執行蓄意製作的程式碼，此資訊安全風險可能會允許權限提高。根據預設，目前在 Windows 8 與 Windows 8.1 上所提供的沈浸式瀏覽體驗是搭配加強的受保護模式 (EPM) 執行。舉例來說，如果使用者在新型的 Windows 平板上使用具備觸控功能的 Internet Explorer 11 瀏覽器，依預設也會使用「加強的受保護模式」。「加強的受保護模式」採用進階的資訊安全保護功能，有助於緩和 64 位元系統遭到此資訊安全風險利用的問題。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402462">MS14-042</a></td>
<td style="border:1px solid black;"><strong>Microsoft Service Bus 中的資訊安全風險可能允許阻斷服務 (DoS) (2972621)<br />
</strong><br />
此資訊安全更新可解決 Microsoft Service Bus for Windows Server 中一項已公開揭露的資訊安全風險。若通過驗證的遠端攻擊者建立並執行可傳送一連串蓄意製作的進階訊息佇列通訊協定 (AMQP) 訊息至目標系統的程式，資訊安全風險可能允許阻斷服務 (DoS)。Microsoft Service Bus for Windows Server 未隨附於任何 Microsoft 作業系統。由於受影響的系統容易受到資訊安全風險影響，Microsoft Service Bus 務必先下載、安裝及設定完成，接著與其他使用者共用其設定詳細資料 (陣列憑證)。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">中度</a> <br />
阻斷服務 (DoS)</td>
<td style="border:1px solid black;">不需要重新開機</td>
<td style="border:1px solid black;">Microsoft 伺服器軟體</td>
</tr>
</tbody>
</table>
  
 
  
資訊安全風險入侵指數  
--------------------
  
下表提供本月所述每個資訊安全風險的利用性評估。資訊安全風險皆根據公告編號和 CVE 編號依序列出。僅包含資訊安全公告中，嚴重性等級為「重大」或「重要」的資訊安全風險。
  
**我該如何使用這個表格？**
  
您可以運用此表格，針對您可能需要安裝的每一項資訊安全更新，瞭解資訊安全風險在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務 (DoS) 的可能性。請根據您特定的組態設定，檢閱下列各項評估，決定部署本月份更新的優先次序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 資訊安全風險索引](http://technet.microsoft.com/security/cc998259)。
  
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
<td style="border:1px solid black;"><strong>公告編號</strong></td>
<td style="border:1px solid black;"><strong>資訊安全風險標題</strong></td>
<td style="border:1px solid black;"><strong>CVE ID</strong></td>
<td style="border:1px solid black;"><strong>最新軟體版本的資訊安全風險評估</strong></td>
<td style="border:1px solid black;"><strong>較舊軟體版本的資訊安全風險評估</strong></td>
<td style="border:1px solid black;"><strong>阻斷服務 (DoS) 資訊安全風險評估</strong></td>
<td style="border:1px solid black;"><strong>主要重點</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1763">CVE-2014-1763</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1765">CVE-2014-1765</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2785">CVE-2014-2785</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2786">CVE-2014-2786</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2787">CVE-2014-2787</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2788">CVE-2014-2788</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2789">CVE-2014-2789</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2790">CVE-2014-2790</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2791">CVE-2014-2791</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2792">CVE-2014-2792</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2794">CVE-2014-2794</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2795">CVE-2014-2795</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2797">CVE-2014-2797</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2798">CVE-2014-2798</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2800">CVE-2014-2800</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2801">CVE-2014-2801</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2802">CVE-2014-2802</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2803">CVE-2014-2803</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2804">CVE-2014-2804</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2806">CVE-2014-2806</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2807">CVE-2014-2807</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2809">CVE-2014-2809</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2813">CVE-2014-2813</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4066">CVE-2014-4066</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402326">MS14-038</a></td>
<td style="border:1px solid black;">Windows 筆記本遠端執行程式碼資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1824">CVE-2014-1824</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402327">MS14-039</a></td>
<td style="border:1px solid black;">螢幕小鍵盤權限提高資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2781">CVE-2014-2781</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402328">MS14-040</a></td>
<td style="border:1px solid black;">附屬功能驅動程式權限提高資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1767">CVE-2014-1767</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402330">MS14-041</a></td>
<td style="border:1px solid black;">DirectShow 權限提高資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2780">CVE-2014-2780</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
</tbody>
</table>
  
受影響的軟體  
------------
  
下表依據主要的軟體類別和嚴重性依序列出公告。
  
**我該如何使用這些表格？**
  
請用這些表格來瞭解可能需要安裝的資訊安全更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的資訊安全更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。
  
**注意**：一項資訊安全風險，可能需要安裝數個資訊安全更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
### Windows 作業系統與元件

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
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
**無**

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
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2962872)  
(中度)  
Internet Explorer 7  
(2962872)  
(中度)  
Internet Explorer 8  
(2962872)  
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
(2961072)  
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
Internet Explorer 6  
(2962872)  
(中度)  
Internet Explorer 7  
(2962872)  
(中度)  
Internet Explorer 8  
(2962872)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2961072)  
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
Internet Explorer 6  
(2962872)  
(中度)  
Internet Explorer 7  
(2962872)  
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
(2961072)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

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
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2962872)  
(重大)  
Internet Explorer 8  
(2962872)  
(重大)  
Internet Explorer 9  
(2962872)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2971850)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2961072)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2972280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2962872)  
(重大)  
Internet Explorer 8  
(2962872)  
(重大)  
Internet Explorer 9  
(2962872)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2971850)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2961072)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2972280)  
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
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2962872)  
(中度)  
Internet Explorer 8  
(2962872)  
(中度)  
Internet Explorer 9  
(2962872)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2971850)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2961072)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2972280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2962872)  
(中度)  
Internet Explorer 8  
(2962872)  
(中度)  
Internet Explorer 9  
(2962872)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2971850)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2961072)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2972280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2962872)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2961072)  
(重要)

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
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
適用於 32 位元系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2962872)  
(重大)  
Internet Explorer 9  
(2962872)  
(重大)  
Internet Explorer 10  
(2962872)  
(重大)  
Internet Explorer 11  
(2962872)  
(重大)  
Internet Explorer 11  
(2963952)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2971850)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2961072)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2972280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2962872)  
(重大)  
Internet Explorer 9  
(2962872)  
(重大)  
Internet Explorer 10  
(2962872)  
(重大)  
Internet Explorer 11  
(2962872)  
(重大)  
Internet Explorer 11  
(2963952)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2971850)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2961072)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2972280)  
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
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2962872)  
(中度)  
Internet Explorer 9  
(2962872)  
(中度)  
Internet Explorer 10  
(2962872)  
(中度)  
Internet Explorer 11  
(2962872)  
(中度)  
Internet Explorer 11  
(2963952)  
(中度)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2971850)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2961072)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2972280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2962872)  
(中度)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2961072)  
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
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
適用於 32 位元系統的 Windows 8

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2962872)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8  
(2971850)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8  
(2961072)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8  
(2972280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2962872)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(2971850)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(2961072)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(2972280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2962872)  
(重大)  
Internet Explorer 11  
(2963952)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(2971850)  
(重大)  
適用於 32 位元系統的 Windows 8.1  
(2974286)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(2973201)  
(重要)  
適用於 32 位元系統的 Windows 8.1  
(2973906)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(2961072)  
(重要)  
適用於 32 位元系統的 Windows 8.1  
(2973408)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(2972280)  
(重要)  
適用於 32 位元系統的 Windows 8.1  
(2973932)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2962872)  
(重大)  
Internet Explorer 11  
(2963952)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(2971850)  
(重大)  
適用於 x64 型系統的 Windows 8.1  
(2974286)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(2973201)  
(重要)  
適用於 x64 型系統的 Windows 8.1  
(2973906)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(2961072)  
(重要)  
適用於 x64 型系統的 Windows 8.1  
(2973408)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(2972280)  
(重要)  
適用於 x64 型系統的 Windows 8.1  
(2973932)  
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
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2962872)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2971850)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2961072)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2972280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2962872)  
(中度)  
Internet Explorer 11  
(2963952)  
(中度)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2971850)  
(重大)  
Windows Server 2012 R2  
(2974286)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2973201)  
(重要)  
Windows Server 2012 R2  
(2973906)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2961072)  
(重要)  
Windows Server 2012 R2  
(2973408)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2972280)  
(重要)  
Windows Server 2012 R2  
(2973932)  
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
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2962872)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT  
(2971850)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(2961072)  
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
Internet Explorer 11  
(2962872)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2971850)  
(重大)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2961072)  
(重要)

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
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2961072)  
(重要)

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
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2961072)  
(重要)

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
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(2961072)  
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
Windows Server 2012 (Server Core 安裝)  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(2961072)  
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
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(2973201)  
(重要)  
Windows Server 2012 R2 (Server Core 安裝)  
(2973906)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(2961072)  
(重要)  
Windows Server 2012 R2 (Server Core 安裝)  
(2973408)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
</table>
 
 

### Windows Server 軟體

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Server Bus for Windows Server**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-042**](http://go.microsoft.com/fwlink/?linkid=402462)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;" colspan="2">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Service Bus for Windows Server

</td>
<td style="border:1px solid black;" colspan="2">
安裝於適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 上的 Microsoft Service Bus 1.1  
(2972621)  
(中度)  
安裝於 Windows Server 2012 上的 Microsoft Service Bus 1.1  
(2972621)  
(中度)  
安裝於 Windows Server 2012 R2 上的 Microsoft Service Bus 1.1  
(2972621)  
(中度)

</td>
</tr>
</table>
 

偵測與部署工具及指南
--------------------

有幾項資源可協助系統管理員部署資訊安全更新。

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，查看是否遺漏資訊安全更新及一般資訊安全設定錯誤的狀況。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 可協助系統管理員散佈資訊安全更新。

應用程式相容性工具組隨附的 Update Compatibility Evaluator 元件可針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

如需上述工具以及其他可使用工具的詳細資訊，請參閱 [IT專業人員的資訊安全工具](http://technet.microsoft.com/security/cc297183)。 

感謝
----

Microsoft [感謝](http://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

**MS14-037**

-   感謝 [VUPEN](http://www.vupen.com/) 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-1763)
-   感謝 [Andreas Schmidt](https://technet.microsoft.com/zh-TW/mailto:andreas.schmidt@siberas.de) 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-1765)
-   0016EECD9D7159A949DAD3BC17E0A939 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-1765)
-   感謝 91fba4fa08fe776e7369ab4d96db6578 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-1765)
-   感謝 [Eric Lawrence](https://twitter.com/ericlaw) 回報延伸驗證 (EV) 憑證資訊安全功能略過的資訊安全風險 (CVE-2014-2783)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2785)
-   感謝 [Qihoo 360](http://www.360.cn/) 的 Liu Long 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2785)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2786)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2787)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2788)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2789)
-   感謝 [Qihoo 360](http://www.360.cn/) 的 Yujie Wen 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2790)
-   感謝 [Qihoo 360](http://www.360.cn/) 的 Liu Long 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2790)
-   感謝 Arthur Gerkis 與 [HP 的](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2791)
-   感謝 [HP](http://www.hpenterprisesecurity.com/products) [Zero Day Initiative](http://www.zerodayinitiative.com/) 的 Abdul Aziz Hariri、Matt Molinyawe 和 Jasiel Spelman 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2792)
-   感謝 [KnownSec](http://www.knownsec.com/) 的 ZhaoWei 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2794)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Hui Gao 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2795)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Royce Lu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2797)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2798)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2800)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2801)
-   感謝 [Qihoo 360](http://www.360.cn/) 的 Yuki Chen 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2802)
-   感謝 Sky 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2802)
-   感謝 [NSFOCUS Security Team](http://www.nsfocus.com/) 的 [Chen Zhang (demi6od)](https://github.com/demi6od) 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2802)
-   感謝 AMol NAik 與 [VeriSign iDefense Labs](http://labs.idefense.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2803)
-   感謝 Garage4Hackers 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2803)
-   感謝 [Qihoo 360](http://www.360.cn/) 的 Yuki Chen 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2803)
-   感謝 [NSFOCUS Security Team](http://www.nsfocus.com/) 的 exp-sky 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2804)
-   感謝 [NSFOCUS Security Team](http://www.nsfocus.com/) 的 [Chen Zhang (demi6od)](https://github.com/demi6od) 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2806)
-   感謝 Yenteasy - Security Research 的 José A. Vázquez 和 [VeriSign iDefense Labs](http://labs.idefense.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2807)
-   感謝 [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com) 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2809)
-   感謝 [HP](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 的 Abdul Aziz Hariri 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2813)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4066)

     

**MS14-038**

-   [Hamburgers.maccoy@gmail.com](mailto:hamburgers.maccoy@gmail.com) 回報 Windows 筆記本遠端執行程式碼資訊安全風險 (CVE-2014-1824)

     

**MS14-039**

-   感謝 [lokihardt@asrt](https://technet.microsoft.com/zh-TW/mailto:lokihardt@asrt) 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報螢幕小鍵盤權限提高資訊安全風險 (CVE-2014-2781)

     

**MS14-040**

-   感謝 [Sebastian Apelt](https://technet.microsoft.com/zh-TW/mailto:sebastian.apelt@siberas.de) 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報附屬功能驅動程式權限提高的資訊安全風險 (CVE-2014-1767)

     

**MS14-041**

-   感謝 [VUPEN](http://www.vupen.com/) 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 DirectShow 權限提高資訊安全風險 (CVE-2014-2780)

     

其他資訊
--------

### Microsoft Windows 惡意軟體移除工具 (英文)

針對每個月第二個星期二發行的公告，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 及下載中心發行更新版本的 Microsoft Windows 惡意軟體移除工具。不定期資訊安全公告發行不提供更新版本的 Microsoft Windows 惡意軟體移除工具。

### MU、WU 及 WSUS 上的非資訊安全更新

如需在 Windows Update 和 Microsoft Update 上發行的非資訊安全更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](https://support.microsoft.com/kb/894199)： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](http://technet.microsoft.com/wsus/bb456965)。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的資訊安全保護，Microsoft 將在每月發行資訊安全更新之前，提前向重要資訊安全軟體提供者提供資訊安全風險資訊。資訊安全軟體提供者可利用此資訊安全風險資訊，透過其資訊安全軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://go.microsoft.com/fwlink/?linkid=215201) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

### 資訊安全策略與社群

**更新程式管理策略**

[更新管理資訊安全指南](http://go.microsoft.com/fwlink/?linkid=21168) (英文) 提供您有關套用資訊安全更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他資訊安全更新**

其他資訊安全問題的更新可由下列位置取得：

-   資訊安全更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。
-   消費性平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以資訊安全和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的資訊安全更新。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](https://support.microsoft.com/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全社群](http://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升資訊安全以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類資訊安全議題的討論。

### 支援

所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 支援週期](http://go.microsoft.com/fwlink/?linkid=21742)。

IT 專業人員的資訊安全解決方案： [TechNet 資訊安全疑難排解與支援](http://technet.microsoft.com/security/bb980617)

協助保護您的 Widows 電腦免於病毒和惡意軟體攻擊： [病毒解決方案與資訊安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master)

您所在國家/地區的當地支援： [國際支援](http://support.microsoft.com/common/international.aspx)

### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

### 修訂

-   V1.0 (2014 年 7 月 8日)： 公告摘要發行。
-   V1.1 (2014 年 7 月 29 日)： 針對 MS14-037，為 CVE-2014-4066 新增「資訊安全風險入侵指數」的資訊安全風險評估。這項變更僅屬於資訊上的變更。

*頁面產生時間：2014-08-06 16:51Z-07:00。*
