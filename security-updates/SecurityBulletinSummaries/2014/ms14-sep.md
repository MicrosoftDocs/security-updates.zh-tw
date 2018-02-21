---
TOCTitle: 'MS14-SEP'
Title: 2014 年 9 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms14-sep'
ms:contentKeyID: 62841261
ms:date: '09/22/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms14-sep(v=Security.10)'
---

2014 年 9 月份 Microsoft 資訊安全公告摘要
=========================================

發行日期： 2014 年 9 月 9 日

**版本：** 1.0

此公告摘要列出 2014 年 9 月份所發行之資訊安全公告。

發行 2014 年 9 月份資訊安全公告之後，此公告摘要將取代原先於 2014 年 9 月 4 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 資訊安全公告預先通知](http://go.microsoft.com/fwlink/?linkid=217213)。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術資訊安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播，於 2014 年 9 月 10 日太平洋時間早上 11 點 (美國與加拿大) 解答客戶對於這些公告的問題。若要檢視每月網路廣播和其他資訊安全公告網路廣播的連結，請參閱 [Microsoft 資訊安全公告網路廣播](http://technet.microsoft.com/security/dn756352)。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 積存資訊安全更新 (2977629)<br />
<br />
</strong>此資訊安全更新可解決 Internet Explorer 中一項公開揭露的資訊安全風險，以及三十六項未公開報告的資訊安全風險。其中最嚴重的資訊安全風險，可能在使用者以 Internet Explorer 檢視蓄意製作的網頁時允許遠端執行程式碼。成功利用這些資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的客戶要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507670">MS14-053</a></td>
<td style="border:1px solid black;"><strong>.NET Framework 中的資訊安全風險可能會允許阻斷服務 (DoS) (2990931)</strong><br />
<br />
這個資訊安全更新可解決 Microsoft .NET Framework 中一項未公開報告的資訊安全風險。如果攻擊者將小量蓄意製作的要求傳送至受影響的 .NET 網站，此資訊安全風險可能會允許阻斷服務 (DoS)。依照預設，當 Microsoft .NET Framework 安裝於任何受支援版本的 Microsoft Windows 時，並未安裝 ASP.NET。客戶必須手動安裝並透過向 IIS 註冊以啟用 ASP.NET，才會受此資訊安全風險影響。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
阻斷服務 (DoS)</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507672">MS14-054</a></td>
<td style="border:1px solid black;"><strong>Windows 工作排程器中的資訊安全風險可能會允許權限提高 (2988948)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果攻擊者登入受影響的系統，並執行蓄意製作的應用程式，則此資訊安全風險可能會允許權限提高。攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項資訊安全風險。匿名或遠端使用者無法利用這個資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507669">MS14-055</a></td>
<td style="border:1px solid black;"><strong>Microsoft Lync Server 中的資訊安全風險可能會允許阻斷服務 (DoS) (2990928)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Lync Server 中三項未公開報告的資訊安全風險。如果攻擊者將蓄意製作的要求傳送至 Lync 伺服器，則其中最嚴重的資訊安全風險可能會允許阻斷服務 (DoS)。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
阻斷服務 (DoS)</td>
<td style="border:1px solid black;">不需要重新開機</td>
<td style="border:1px solid black;">Microsoft Lync Server</td>
</tr>
</tbody>
</table>
  
 
  
資訊安全風險入侵指數  
--------------------
  
下表提供本月所述每個資訊安全風險的利用性評估。資訊安全風險皆根據公告編號和 CVE 編號依序列出。僅包含資訊安全公告中，嚴重性等級為「重大」或「重要」的資訊安全風險。
  
我該如何使用這個表格？
  
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 資源資訊洩漏資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-7331">CVE-2013-7331</a></td>
<td style="border:1px solid black;">0 - 已偵測到利用</td>
<td style="border:1px solid black;">0 - 已偵測到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">此資訊安全風險已經遭到公開揭發。Microsoft 已發現有嘗試利用此資訊安全風險、有限且主動的攻擊。<br />
這是一個資訊洩漏的資訊安全風險： 攻擊者可以推斷出本機磁碟機上的檔案。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2799">CVE-2014-2799</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4059">CVE-2014-4059</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4065">CVE-2014-4065</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4079">CVE-2014-4079</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4080">CVE-2014-4080</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4081">CVE-2014-4081</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4082">CVE-2014-4082</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4083">CVE-2014-4083</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4084">CVE-2014-4084</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4085">CVE-2014-4085</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4086">CVE-2014-4086</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4087">CVE-2014-4087</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4088">CVE-2014-4088</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4089">CVE-2014-4089</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4090">CVE-2014-4090</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4091">CVE-2014-4091</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4092">CVE-2014-4092</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4093">CVE-2014-4093</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4094">CVE-2014-4094</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4095">CVE-2014-4095</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4096">CVE-2014-4096</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4097">CVE-2014-4097</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4098">CVE-2014-4098</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4099">CVE-2014-4099</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">暫時</td>
<td style="border:1px solid black;">此記憶體損毀資訊安全風險可能會導致阻斷服務 (DoS)。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4100">CVE-2014-4100</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4101">CVE-2014-4101</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4102">CVE-2014-4102</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4103">CVE-2014-4103</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4104">CVE-2014-4104</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4105">CVE-2014-4105</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4106">CVE-2014-4106</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4107">CVE-2014-4107</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4108">CVE-2014-4108</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4109">CVE-2014-4109</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4110">CVE-2014-4110</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4111">CVE-2014-4111</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507670">MS14-053</a></td>
<td style="border:1px solid black;">.NET Framework 阻斷服務 (DoS) 資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4072">CVE-2014-4072</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">這是一項阻斷服務 (DoS) 的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507672">MS14-054</a></td>
<td style="border:1px solid black;">工作排程器資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4074">CVE-2014-4074</a></td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">1- 較可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507669">MS14-055</a></td>
<td style="border:1px solid black;">Lync 阻斷服務 (DoS) 資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4068">CVE-2014-4068</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">暫時</td>
<td style="border:1px solid black;">這是一項阻斷服務 (DoS) 的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507669">MS14-055</a></td>
<td style="border:1px solid black;">Lync XSS 資訊洩漏資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4070">CVE-2014-4070</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊洩漏的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507669">MS14-055</a></td>
<td style="border:1px solid black;">Lync 阻斷服務 (DoS) 資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4071">CVE-2014-4071</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">暫時</td>
<td style="border:1px solid black;">這是一項阻斷服務 (DoS) 的資訊安全風險。</td>
</tr>
</tbody>
</table>
  
 
  
受影響的軟體  
------------
  
下表依據主要的軟體類別和嚴重性依序列出公告。
  
**我該如何使用這些表格？**
  
請用這些表格來瞭解可能需要安裝的資訊安全更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的資訊安全更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。
  
**注意**：一項資訊安全風險，可能需要安裝數個資訊安全更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
**Windows 作業系統與元件**

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
(2977629)  
(中度)  
Internet Explorer 7  
(2977629)  
(中度)  
Internet Explorer 8  
(2977629)  
(中度)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2972207)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2972214)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2973115)  
(重要)  
Microsoft .NET Framework 4  
(2972215)  
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
(2977629)  
(中度)  
Internet Explorer 7  
(2977629)  
(中度)  
Internet Explorer 8  
(2977629)  
(中度)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2972214)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2973115)  
(重要)  
Microsoft .NET Framework 4  
(2972215)  
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
(2977629)  
(中度)  
Internet Explorer 7  
(2977629)  
(中度)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2972214)  
(重要)  
Microsoft .NET Framework 4  
(2972215)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 7  
(2977629)  
(重大)  
Internet Explorer 8  
(2977629)  
(重大)  
Internet Explorer 9  
(2977629)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2974268)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2974269)  
(重要)  
Microsoft .NET Framework 4  
(2972215)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
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
Internet Explorer 7  
(2977629)  
(重大)  
Internet Explorer 8  
(2977629)  
(重大)  
Internet Explorer 9  
(2977629)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2974268)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2974269)  
(重要)  
Microsoft .NET Framework 4  
(2972215)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 7  
(2977629)  
(中度)  
Internet Explorer 8  
(2977629)  
(中度)  
Internet Explorer 9  
(2977629)  
(中度)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2974268)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2974269)  
(重要)  
Microsoft .NET Framework 4  
(2972215)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
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
Internet Explorer 7  
(2977629)  
(中度)  
Internet Explorer 8  
(2977629)  
(中度)  
Internet Explorer 9  
(2977629)  
(中度)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2974268)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2974269)  
(重要)  
Microsoft .NET Framework 4  
(2972215)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
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
Internet Explorer 7  
(2977629)  
(中度)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2974268)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2974269)  
(重要)  
Microsoft .NET Framework 4  
(2972215)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 8  
(2977629)  
(重大)  
Internet Explorer 9  
(2977629)  
(重大)  
Internet Explorer 10  
(2977629)  
(重大)  
Internet Explorer 11  
(2977629)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2972211)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2973112)  
(重要)  
Microsoft .NET Framework 4  
(2972215)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
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
Internet Explorer 8  
(2977629)  
(重大)  
Internet Explorer 9  
(2977629)  
(重大)  
Internet Explorer 10  
(2977629)  
(重大)  
Internet Explorer 11  
(2977629)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2972211)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2973112)  
(重要)  
Microsoft .NET Framework 4  
(2972215)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 8  
(2977629)  
(中度)  
Internet Explorer 9  
(2977629)  
(中度)  
Internet Explorer 10  
(2977629)  
(中度)  
Internet Explorer 11  
(2977629)  
(中度)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2972211)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2973112)  
(重要)  
Microsoft .NET Framework 4  
(2972215)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
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
Internet Explorer 8  
(2977629)  
(中度)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2972211)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2973112)  
(重要)  
Microsoft .NET Framework 4  
(2972215)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
(2977629)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972212)  
(重要)  
Microsoft .NET Framework 3.5  
(2973113)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2977766)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8  
(2988948)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2977629)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972212)  
(重要)  
Microsoft .NET Framework 3.5  
(2973113)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2977766)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8  
(2988948)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2977629)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972213)  
(重要)  
Microsoft .NET Framework 3.5  
(2973114)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2977765)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
(2988948)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2977629)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972213)  
(重要)  
Microsoft .NET Framework 3.5  
(2973114)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2977765)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
(2988948)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
(2977629)  
(中度)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972212)  
(重要)  
Microsoft .NET Framework 3.5  
(2973113)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2977766)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2988948)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2977629)  
(中度)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972213)  
(重要)  
Microsoft .NET Framework 3.5  
(2973114)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2977765)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2988948)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2977629)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2977766)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(2988948)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2977629)  
(重大)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1/4.5.2  
(2977765)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2988948)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Server Core 安裝選項**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Microsoft .NET Framework 3.5.1  
(2972211)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2973112)  
(重要)  
Microsoft .NET Framework 4  
(2972215)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
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
Microsoft .NET Framework 3.5  
(2972212)  
(重要)  
Microsoft .NET Framework 3.5  
(2973113)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2977766)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(2988948)  
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
Microsoft .NET Framework 3.5  
(2972213)  
(重要)  
Microsoft .NET Framework 3.5  
(2973114)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2977765)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(2988948)  
(重要)

</td>
</tr>
</table>
 
 

**Microsoft 通訊平台和軟體**

<p></p> 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
**Microsoft Lync Server**

</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS14-055**](http://go.microsoft.com/fwlink/?linkid=507669)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Server 2010

</td>
<td style="border:1px solid black;">
Microsoft Lync Server 2010  
(伺服器)  
(2982385)  
(無嚴重性等級) <sup>[1]</sup>
Microsoft Lync Server 2010  
(回應群組服務)  
(2982388)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Server 2013

</td>
<td style="border:1px solid black;">
Microsoft Lync Server 2013  
(伺服器)  
(2986072)  
(重要)  
Microsoft Lync Server 2013  
(回應群組服務)  
(2982389)  
(重要)  
Microsoft Lync Server 2013  
(核心元件)  
(2992965)  
(重要)  
Microsoft Lync Server 2013  
(Web 元件伺服器)  
(2982390)  
(重要)

</td>
</tr>
</table>
 
**MS14-055 注意事項**

<sup>[1]</sup>針對指定的軟體，嚴重性等級並不適用於本更新；不過，Microsoft 仍建議此軟體的客戶套用此資訊安全更新，以做為深度防禦措施，協助防範未來任何可能的新攻擊模式。

 

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

**MS14-052**

-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2799)
-   感謝 [Adlab of Venustech](http://www.venustech.com.cn/) 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-2799)
-   感謝 [Venustech 的 Adlab](http://www.venustech.com.cn/) 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4059)
-   感謝 [HP](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 的 AbdulAziz Hariri 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4065)
-   感謝 56e7aec02099b976120abfda31254b05 與 [HP 的](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4079)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4080)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4081)
-   感謝 [Venustech 的 Adlab](http://www.venustech.com.cn/) 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4081)
-   感謝 [Qihoo 360](http://www.360.cn/) 的 Yuki Chen 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4082)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4082)
-   感謝 [Venustech 的 Adlab](http://www.venustech.com.cn/) 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4083)
-   感謝 [Venustech 的 Adlab](http://www.venustech.com.cn/) 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4084)
-   感謝 [KnownSec Team](http://www.knownsec.com/) 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4084)
-   感謝 Sky 與 [HP 的](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4085)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4086)
-   感謝 [Qihoo 360](http://www.360.cn/) 的 Liu Long 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4086)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4087)
-   感謝 [Qihoo 360](http://www.360.cn/) 的 Zhibin Hu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4087)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Hui Gao 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4088)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4089)
-   感謝 Garage4Hackers 與 [HP 的](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4090)
-   感謝 [Qihoo 360](http://www.360.cn/) 的 Yuki Chen 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4091)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4092)
-   感謝 A3F2160DCA1BDE70DA1D99ED267D5DC1EC336192 與 [HP 的](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4092)
-   感謝 Jason Kratzer 與 [HP 的](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4092)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4093)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4094)
-   感謝 [Trend Micro](http://www.trendmicro.com/) 的 Yuki Chen 與 [HP 的](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4095)
-   感謝 cloudfuzzer 與 [HP 的](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4096)
-   感謝 [HP 的](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 的 AbdulAziz Hariri 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4096)
-   感謝 [Trend Micro](http://www.trendmicro.com/) 的 Yuki Chen 與 [HP 的](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4096)
-   感謝 [Trend Micro](http://www.trendmicro.com/) 的 Yuki Chen 與 [HP 的](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4097)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4097)
-   感謝匿名的研究人員與 [HP 的](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4098)
-   感謝 SkyLined 與 [HP 的](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4099)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4100)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Xin Ouyang 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4101)
-   感謝 Yenteasy 的 José A. Vázquez 和 [HP 的](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4101)
-   感謝 [Qihoo 360](http://www.360.cn/) 的 Liu Long 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4102)
-   感謝 [HP 的](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 的 AbdulAziz Hariri 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4103)
-   感謝 [Qihoo 360](http://www.360.cn/) 的 Liu Long 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4104)
-   感謝 [Trend Micro](http://www.trendmicro.com/) 的 Yuki Chen 與 [HP 的](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4105)
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Bo Qu 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4106)
-   感謝 [HP 的](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 的 AbdulAziz Hariri 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4107)
-   感謝匿名的研究人員與 [HP 的](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4108)
-   感謝 John Villamil (@day6reak) 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4109)
-   感謝 [Keen Team](http://www.knownsec.com/)回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4110)
-   感謝 [Qihoo 360](http://www.360.cn/) 的 Yujie Wen 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2014-4111)
-   感謝 Masato Kinugawa 和 [Google Security Team](http://www.google.com/) 協助我們解決本公告中所含之深度防禦變更的問題

**MS14-053**

-   感謝 [Cynops GmbH](http://www.cynops.de/) 的 Alexander Klink 回報 .NET Framework 阻斷服務 (DoS) 資訊安全風險 (CVE-2014-4072)

**MS14-054**

-   感謝 [Context Information Security](http://www.contextis.com/) 的 James Forshaw 回報工作排程器資訊安全風險 (CVE-2014-4074)

**MS14-055**

-   感謝 [Telecommunication Software GmbH](http://www.telecomsoftware.com/) 的 Peter Schraffl 回報 Lync 阻斷服務 (DoS) 資訊安全風險 (CVE-2014-4068)
-   感謝 Noam Rathaus 與 Beyond Security 的 [SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html) 團隊合作回報 Lync XSS 資訊洩漏資訊安全風險 (CVE-2014-4070)

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

-   V1.0 (2014 年 9 月 9 日)： 公告摘要發行。

*頁面產生時間：2014-09-18 16:20Z-07:00。*
