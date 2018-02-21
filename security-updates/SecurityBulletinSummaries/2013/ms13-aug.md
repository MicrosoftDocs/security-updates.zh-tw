---
TOCTitle: 'MS13-AUG'
Title: 2013 年 8 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms13-aug'
ms:contentKeyID: 61237740
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms13-aug(v=Security.10)'
---

2013 年 8 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2013年8月13日 | 更新: 2013年8月28日

**版本:** 3.0

此公告摘要列出 2013 年 8 月份發行之資訊安全公告。

發行 2013 年 8 月份資訊安全公告之後，此公告摘要將取代原先於 2013 年 8 月 8 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 資訊安全公告預先通知](http://technet.microsoft.com/zh-tw/security/gg309152.aspx)。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術資訊安全通知](http://technet.microsoft.com/zh-tw/security/dd252948.aspx)。

Microsoft 將利用網路廣播於 2013 年 8 月 14 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。[立即註冊參加 8 月份資訊安全公告網路廣播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032557295&culture=en-us)。在這個日期後，此網路廣播將可[隨選取得](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032557295&culture=en-us)。

Microsoft 也會提供資訊協助客戶排定每月資訊安全更新以及任何非資訊安全更新的優先順序，其中這些非資訊安全更新的發行日期與每月資訊安全更新的發行日期相同。請參閱**＜其他資訊＞**一節。

### 公告資訊

#### 提要

下表依嚴重性摘要說明本月份資訊安全公告。

如需受影響的軟體之詳細資料，請參閱下節＜受影響的軟體＞。


<p></p> 
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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-059">MS13-059</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer</strong> <strong>積存資訊安全更新</strong> <strong>(2862772)  <br />
<br />
</strong>這個資訊安全更新可解決 Internet Explorer 中十一項未公開報告的資訊安全風險。最嚴重的資訊安全風險可能會在使用者以 Internet Explorer 檢視蓄意製作的網頁時，允許遠端執行程式碼。成功利用其中最嚴重的資訊安全風險的攻擊者，可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-060">MS13-060</a></td>
<td style="border:1px solid black;"><strong>Unicode</strong> <strong>指令碼處理器中的資訊安全風險可能允許遠端執行程式碼</strong> <strong>(2850869)<br />
<br />
</strong>這個資訊安全更新可解決 Microsoft Windows 隨附的 Unicode 指令碼處理器中一項未公開報告的資訊安全風險 如果使用者利用支援內嵌 OpenType 字型的應用程式來檢視蓄意製作的文件或網頁，此資訊安全風險可能會允許遠端執行程式碼。成功利用此資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-061">MS13-061</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange Server</strong> <strong>中的資訊安全風險可能會允許遠端執行程式碼</strong> <strong>(2876063)<br />
<br />
</strong>此資訊安全更新可解決 Microsoft Exchange Server 中三項公開揭露的資訊安全風險。上述資訊安全風險存在於 Microsoft Exchange Server 的 WebReady 文件檢視和資料遺失防止功能中。如果使用者使用 Outlook Web App (OWA) 預覽蓄意製作的檔案，則此資訊安全風險可能會允許在 Exchange Server 上轉碼服務的資訊安全內容中遠端執行程式碼。Exchange 中用於 WebReady 文件檢視的轉碼服務是使用 LocalService 帳戶的認證執行。資料遺失防止功能裝載有程式碼，如果 Exchange Server 收到蓄意製作的訊息，可能會允許在 Filtering Management 服務的安全性內容中遠端執行程式碼。Exchange 中的 Filtering Management 服務會使用 LocalService 帳戶的認證。LocalService 帳戶在本機系統擁有最低權限，在網路上提供匿名認證。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft 伺服器軟體</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-062">MS13-062</a></td>
<td style="border:1px solid black;"><strong>遠端程序呼叫中的資訊安全風險可能允許權限提高</strong> <strong>(2849470)<br />
<br />
</strong>此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果攻擊者傳送蓄意製作的 RPC 要求，此資訊安全風險可能允許權限提高。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-063">MS13-063</a></td>
<td style="border:1px solid black;"><strong>Windows</strong> <strong>核心中的資訊安全風險可能會允許權限提高</strong> <strong>(2859537)<br />
<br />
</strong>此資訊安全更新可解決 Microsoft Windows 中一項公開揭露的資訊安全風險和三項未公開報告的資訊安全風險。如果攻擊者從本機登入並執行蓄意製作的應用程式，則最嚴重的資訊安全風險可能會允許權限提高。攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這些資訊安全風險。遠端或匿名使用者無法利用這個資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-064">MS13-064</a></td>
<td style="border:1px solid black;"><strong>Windows NAT</strong> <strong>驅動程式中的資訊安全風險可能會允許阻斷服務</strong> <strong>(2849568)<br />
<br />
</strong>此資訊安全更新可解決 Microsoft Windows 之 Windows NAT 驅動程式中一項未公開報告的資訊安全風險。如果攻擊者將蓄意製作的 ICMP 封包傳送給正在執行 Windows NAT 驅動程式服務的目標伺服器，這個資訊安全風險可能會允許阻斷服務。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
阻斷服務 (DoS)</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-065">MS13-065</a></td>
<td style="border:1px solid black;"><strong>ICMPv6</strong> <strong>中的資訊安全風險可能會允許阻斷服務</strong> <strong>(2868623)<br />
<br />
</strong>此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果攻擊者將蓄意製作的 ICMP 封包傳送給目標系統，這個資訊安全風險可能會允許阻斷服務 (DoS)。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
阻斷服務 (DoS)</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-066">MS13-066</a></td>
<td style="border:1px solid black;"><strong>Active Directory Federation Services</strong> <strong>中的資訊安全風險可能允許資訊洩漏</strong> <strong>(2873872)</strong> <br />
<br />
這個資訊安全更新可解決 Active Directory Federation Services (AD FS) 中一項未公開報告的資訊安全風險。此資訊安全風險可能會洩漏 AD FS 所使用之服務帳戶的相關資訊。攻擊者可能會嘗試從企業網路外部登入，而如果已設定帳戶鎖定原則，便會導致 AD FS 使用的服務帳戶遭鎖定。這會導致所有仰賴 AD FS 執行個體的應用程式阻斷服務 (DoS)。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
資訊洩漏</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-059">MS13-059</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3184">CVE-2013-3184</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-059">MS13-059</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3187">CVE-2013-3187</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-059">MS13-059</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3188">CVE-2013-3188</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-059">MS13-059</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3189">CVE-2013-3189</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-059">MS13-059</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3190">CVE-2013-3190</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-059">MS13-059</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3191">CVE-2013-3191</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-059">MS13-059</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3193">CVE-2013-3193</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-059">MS13-059</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3194">CVE-2013-3194</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-059">MS13-059</a></td>
<td style="border:1px solid black;">Internet Explorer 記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3199">CVE-2013-3199</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-060">MS13-060</a></td>
<td style="border:1px solid black;">Uniscribe 字型剖析引擎記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3181">CVE-2013-3181</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-061">MS13-061</a></td>
<td style="border:1px solid black;">Oracle Outside In 包含多項可能遭利用的資訊安全風險</td>
<td style="border:1px solid black;">多項&#42;</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">&#42;多項資訊安全風險，請參閱 MS13-061 公告內容以瞭解詳細資訊。<br />
<br />
這類資訊安全風險已被公開揭發。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-062">MS13-062</a></td>
<td style="border:1px solid black;">遠端程序呼叫資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3175">CVE-2013-3175</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-063">MS13-063</a></td>
<td style="border:1px solid black;">ASLR 資訊安全功能略過資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-2556">CVE-2013-2556</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊安全功能略過之資訊安全風險。<br />
<br />
此資訊安全風險已經遭到公開揭發。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-063">MS13-063</a></td>
<td style="border:1px solid black;">Windows 核心記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3196">CVE-2013-3196</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-063">MS13-063</a></td>
<td style="border:1px solid black;">Windows 核心記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3197">CVE-2013-3197</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-063">MS13-063</a></td>
<td style="border:1px solid black;">Windows 核心記憶體損毀資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3198">CVE-2013-3198</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-064">MS13-064</a></td>
<td style="border:1px solid black;">Windows NAT 阻斷服務資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3182">CVE-2013-3182</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">這是一項阻斷服務 (DoS) 的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-065">MS13-065</a></td>
<td style="border:1px solid black;">ICMPv6 資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3183">CVE-2013-3183</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">這是一項阻斷服務 (DoS) 的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-066">MS13-066</a></td>
<td style="border:1px solid black;">AD FS 資訊洩漏資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3185">CVE-2013-3185</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">暫時</td>
<td style="border:1px solid black;">這是一個資訊洩漏的資訊安全風險。</td>
</tr>
</tbody>
</table>
  
受影響的軟體  
------------
  

下表依據主要的軟體類別和嚴重性依序列出公告。
  
**我該如何使用這些表格？**
  
請用這些表格來瞭解可能需要安裝的資訊安全更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的資訊安全更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。
  
**注意**：一項資訊安全風險，可能需要安裝數個資訊安全更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
#### Windows 作業系統與元件


<p></p> 
<table style="border:1px solid black;">
<tr>
<th colspan="8">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-059**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-059)
</td>
<td style="border:1px solid black;">
[**MS13-060**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-060)
</td>
<td style="border:1px solid black;">
[**MS13-062**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-062)
</td>
<td style="border:1px solid black;">
[**MS13-063**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-063)
</td>
<td style="border:1px solid black;">
[**MS13-064**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-064)
</td>
<td style="border:1px solid black;">
[**MS13-065**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-065)
</td>
<td style="border:1px solid black;">
[**MS13-066**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-066)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2862772)  
(重大)  
Internet Explorer 7   
(2862772)  
(重大)  
Internet Explorer 8   
(2862772)  
(重大)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2850869)  
(重大)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2859537)  
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2862772)  
(重大)  
Internet Explorer 7   
(2862772)  
(重大)  
Internet Explorer 8   
(2862772)  
(重大)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2850869)  
(重大)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2849470)  
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
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-059**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-059)
</td>
<td style="border:1px solid black;">
[**MS13-060**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-060)
</td>
<td style="border:1px solid black;">
[**MS13-062**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-062)
</td>
<td style="border:1px solid black;">
[**MS13-063**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-063)
</td>
<td style="border:1px solid black;">
[**MS13-064**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-064)
</td>
<td style="border:1px solid black;">
[**MS13-065**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-065)
</td>
<td style="border:1px solid black;">
[**MS13-066**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-066)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2862772)  
(中度)  
Internet Explorer 7  
(2862772)  
(中度)  
Internet Explorer 8  
(2862772)  
(中度)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2850869)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
Active Directory Federation Services 1.x  
(僅 Windows Server 2003 R2 Service Pack 2)  
(2868846)  
(無嚴重性等級)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2862772)  
(中度)  
Internet Explorer 7  
(2862772)  
(中度)  
Internet Explorer 8  
(2862772)  
(中度)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2850869)  
(重大)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2849470)  
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
<td style="border:1px solid black;">
Active Directory Federation Services 1.x  
(僅 Windows Server 2003 R2 x64 Edition Service Pack 2)  
(2868846)  
(無嚴重性等級)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2862772)  
(中度)  
Internet Explorer 7  
(2862772)  
(中度)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(2850869)  
(重大)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2  
(2849470)  
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
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="8">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-059**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-059)
</td>
<td style="border:1px solid black;">
[**MS13-060**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-060)
</td>
<td style="border:1px solid black;">
[**MS13-062**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-062)
</td>
<td style="border:1px solid black;">
[**MS13-063**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-063)
</td>
<td style="border:1px solid black;">
[**MS13-064**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-064)
</td>
<td style="border:1px solid black;">
[**MS13-065**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-065)
</td>
<td style="border:1px solid black;">
[**MS13-066**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-066)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2862772)  
(重大)  
Internet Explorer 8  
(2862772)  
(重大)  
Internet Explorer 9   
(2862772)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2868623)  
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
(2862772)  
(重大)  
Internet Explorer 8  
(2862772)  
(重大)  
Internet Explorer 9   
(2862772)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-059**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-059)
</td>
<td style="border:1px solid black;">
[**MS13-060**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-060)
</td>
<td style="border:1px solid black;">
[**MS13-062**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-062)
</td>
<td style="border:1px solid black;">
[**MS13-063**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-063)
</td>
<td style="border:1px solid black;">
[**MS13-064**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-064)
</td>
<td style="border:1px solid black;">
[**MS13-065**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-065)
</td>
<td style="border:1px solid black;">
[**MS13-066**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-066)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2862772)  
(中度)  
Internet Explorer 8  
(2862772)  
(中度)  
Internet Explorer 9   
(2862772)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
Active Directory Federation Services 2.0  
(2843638)  
(重要)  
Active Directory Federation Services 1.x  
(2868846)  
(無嚴重性等級)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2862772)  
(中度)  
Internet Explorer 8  
(2862772)  
(中度)  
Internet Explorer 9   
(2862772)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
Active Directory Federation Services 2.0  
(2843638)  
(重要)  
Active Directory Federation Services 1.x  
(2868846)  
(無嚴重性等級)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2862772)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="8">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-059**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-059)
</td>
<td style="border:1px solid black;">
[**MS13-060**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-060)
</td>
<td style="border:1px solid black;">
[**MS13-062**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-062)
</td>
<td style="border:1px solid black;">
[**MS13-063**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-063)
</td>
<td style="border:1px solid black;">
[**MS13-064**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-064)
</td>
<td style="border:1px solid black;">
[**MS13-065**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-065)
</td>
<td style="border:1px solid black;">
[**MS13-066**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-066)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
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
(2862772)  
(重大)  
Internet Explorer 9   
(2862772)  
(重大)  
Internet Explorer 10   
(2862772)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2862772)  
(重大)  
Internet Explorer 9   
(2862772)  
(重大)  
Internet Explorer 10   
(2862772)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-059**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-059)
</td>
<td style="border:1px solid black;">
[**MS13-060**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-060)
</td>
<td style="border:1px solid black;">
[**MS13-062**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-062)
</td>
<td style="border:1px solid black;">
[**MS13-063**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-063)
</td>
<td style="border:1px solid black;">
[**MS13-064**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-064)
</td>
<td style="border:1px solid black;">
[**MS13-065**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-065)
</td>
<td style="border:1px solid black;">
[**MS13-066**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-066)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2862772)  
(中度)  
Internet Explorer 9   
(2862772)  
(中度)  
Internet Explorer 10   
(2862772)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
Active Directory Federation Services 2.0  
(2843638)  
(重要)  
Active Directory Federation Services 1.x  
(2868846)  
(無嚴重性等級)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2862772)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="8">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-059**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-059)
</td>
<td style="border:1px solid black;">
[**MS13-060**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-060)
</td>
<td style="border:1px solid black;">
[**MS13-062**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-062)
</td>
<td style="border:1px solid black;">
[**MS13-063**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-063)
</td>
<td style="border:1px solid black;">
[**MS13-064**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-064)
</td>
<td style="border:1px solid black;">
[**MS13-065**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-065)
</td>
<td style="border:1px solid black;">
[**MS13-066**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-066)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2862772)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 8
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2862772)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 8  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 8  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-059**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-059)
</td>
<td style="border:1px solid black;">
[**MS13-060**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-060)
</td>
<td style="border:1px solid black;">
[**MS13-062**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-062)
</td>
<td style="border:1px solid black;">
[**MS13-063**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-063)
</td>
<td style="border:1px solid black;">
[**MS13-064**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-064)
</td>
<td style="border:1px solid black;">
[**MS13-065**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-065)
</td>
<td style="border:1px solid black;">
[**MS13-066**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-066)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2862772)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2849568)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
Active Directory Federation Services 2.1  
(2843638)  
(重要)  
Active Directory Federation Services 2.1  
(2843639)  
(無嚴重性等級)
</td>
</tr>
<tr>
<th colspan="8">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-059**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-059)
</td>
<td style="border:1px solid black;">
[**MS13-060**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-060)
</td>
<td style="border:1px solid black;">
[**MS13-062**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-062)
</td>
<td style="border:1px solid black;">
[**MS13-063**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-063)
</td>
<td style="border:1px solid black;">
[**MS13-064**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-064)
</td>
<td style="border:1px solid black;">
[**MS13-065**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-065)
</td>
<td style="border:1px solid black;">
[**MS13-066**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-066)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2862772)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
Windows RT  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
Windows RT  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="8">
Server Core 安裝選項
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-059**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-059)
</td>
<td style="border:1px solid black;">
[**MS13-060**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-060)
</td>
<td style="border:1px solid black;">
[**MS13-062**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-062)
</td>
<td style="border:1px solid black;">
[**MS13-063**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-063)
</td>
<td style="border:1px solid black;">
[**MS13-064**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-064)
</td>
<td style="border:1px solid black;">
[**MS13-065**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-065)
</td>
<td style="border:1px solid black;">
[**MS13-066**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-066)
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
**無**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
**無**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
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
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
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
不適用
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(2868623)  
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
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
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
不適用
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
</table>
 

#### Microsoft 伺服器軟體


<p></p> 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Exchange Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-061**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-061)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3  
(2873746)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 2  
(2874216)  
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3  
(2866475)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 積存更新 1
</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 積存更新 1  
(2874216)  
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 積存更新 2
</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 積存更新 2  
(2874216)  
(重大)
</td>
</tr>
</table>
 

偵測與部署工具及指南
--------------------


**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和資訊安全更新。如需更多資訊，請參閱 [TechNet 更新管理中心](http://technet.microsoft.com/zh-tw/updatemanagement/default.aspx) (英文)。[TechNet 資訊安全技術中心](http://technet.microsoft.com/zh-tw/security/default.aspx)提供 Microsoft 產品資訊安全的其他資訊。一般消費者可造訪 [Microsoft Safety & Security Center](http://technet.microsoft.com/zh-tw/security/default.aspx) (英文)，並點選 \[Security Updates\] (資訊安全更新) 來取得上述資訊。

資訊安全更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 以及 [Windows Update](http://update.microsoft.com/windowsupdate/v6/default.aspx) 取得。資訊安全更新也可以從 [Microsoft 下載中心](http://www.microsoft.com/zh-tw/download/search.aspx?q=security%20update)取得。您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。

對於 Microsoft Office for Mac 的客戶，Microsoft AutoUpdate for Mac 可協助您保持最新的 Microsoft 軟體。如需使用 Microsoft AutoUpdate for Mac 的詳細資訊，請參閱[自動檢查軟體更新](http://mac2.microsoft.com/help/office/14/zh-tw/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea) (英文)。

最後，您可以從 [Microsoft Update Catalog](http://catalog.update.microsoft.com/v7/site/) 下載資訊安全更新。Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括資訊安全更新、驅動程式和 Service Pack。只要以資訊安全公告編號 (例如：MS13-001) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](http://catalog.update.microsoft.com/v7/site/faq.aspx)。

**偵測與部署指南**

Microsoft 針對資訊安全更新提供偵測和部署指南。本指南所含之建議和資訊，能幫助 IT 專業人員瞭解如何使用用於資訊安全更新的偵測和部署的各種工具。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 961747](http://support.microsoft.com/kb/961747?ln=zh-tw)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少資訊安全更新以及一般資訊安全設定錯誤的狀況。如需更多有關 MBSA 的資訊，請參閱 [Microsoft Baseline Security Analyzer](http://technet.microsoft.com/zh-tw/security/cc184924.aspx) (英文)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速而可靠地將 Microsoft Windows 2000 作業系統及更新版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 適用的最新重大更新與資訊安全更新部署到 Microsoft Windows 2000 及更新版本的作業系統中。

如需更多關於利用 Windows Server Update Services 部署資訊安全更新的資訊，請造訪 [Windows Server Update Services](http://technet.microsoft.com/wsus/default) (英文)。

**System Center Configuration Manager**

System Center Configuration Manager 軟體更新管理可簡化遞送和管理企業中 IT 系統更新的繁複作業。IT 系統管理員可以使用 System Center Configuration Manager 遞送 Microsoft 產品更新給各種裝置，包括桌上型電腦、筆記型電腦、伺服器及行動裝置。

System Center Configuration Manager 中的自動資訊安全風險評估會找出更新需求並報告建議動作。System Center Configuration Manager 中的軟體更新管理是建置在 Microsoft Windows Software Update Services (WSUS) 上，經過時間考驗，為全球 IT 系統管理員所熟悉的更新基礎架構。如需更多有關 System Center Configuration Manager 的資訊，請造訪 [System Center 技術資源](http://technet.microsoft.com/systemcenter/bb980621)。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。透過 SMS，系統管理員能判斷有哪些 Windows 系統需要資訊安全更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。

**注意：**System Management Server 2003 自 2010 年 1 月 12 日起不受主流支援。如需更多有關產品生命週期的資訊，請造訪 [Microsoft 支援週期](http://support.microsoft.com/default.aspx?scid=fh;%5bln%5d;lifecycle)。現已推出新版的 SMS，System Center Configuration Manager；請參閱前段的＜System Center Configuration Manager＞一節。

如需更多有關系統管理員如何使用 SMS 2003 來部署資訊安全更新的資訊，請參閱 [Microsoft Systems Management Server 2003 的案例與程序： 軟體發佈和補充程式管理](http://www.microsoft.com/downloads/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f) (英文)。如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server 技術中心 (TechCenter)](http://technet.microsoft.com/systemcenter/bb545936)。

**注意**：SMS 使用 Microsoft Baseline Security Analyzer 提供廣泛的資訊安全公告更新偵測與部署支援。不過這些工具可能無法偵測部分的軟體更新。在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](http://technet.microsoft.com/zh-tw/library/cc917507.aspx) (英文)。某些資訊安全更新程式在電腦重新啟動之後，會需要系統管理員的權限。系統管理員可使用 Elevated Rights Deployment Tool (隨附於 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d)) 來安裝這些更新。

**Update Compatibility Evaluator** **和** **Application Compatibility Toolkit**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。這可能會觸發不相容性，而拉長部署資訊安全更新的時間。您可以使用 [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971) 隨附的 [Update Compatibility Evaluator](http://technet.microsoft.com/library/cc749197) 元件，針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Windows Vista、Windows Update、Microsoft 資訊安全更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

針對每個月第二個星期二發行的公告，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 及下載中心發行更新版本的 Microsoft Windows 惡意軟體移除工具。不定期資訊安全公告發行不提供更新版本的 Microsoft Windows 惡意軟體移除工具。

#### MU、WU 及 WSUS 上的非資訊安全更新

如需在 Windows Update 和 Microsoft Update 上發行的非資訊安全更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](http://support.microsoft.com/kb/894199?ln=zh-tw)
-   ： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](http://technet.microsoft.com/wsus/bb456965)
-   。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的資訊安全保護，Microsoft 將在每月發行資訊安全更新之前，提前向重要資訊安全軟體提供者提供資訊安全風險資訊。資訊安全軟體提供者可利用此資訊安全風險資訊，透過其資訊安全軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://www.microsoft.com/security/msrc/collaboration/mapp.aspx) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 資訊安全策略與社群

**更新程式管理策略**

[更新管理資訊安全指南](http://technet.microsoft.com/zh-tw/library/bb466251(zh-tw).aspx) (英文) 提供您有關套用資訊安全更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他資訊安全更新**

其他資訊安全問題的更新可由下列位置取得：

-   資訊安全更新可以從 [Microsoft 下載中心](http://www.microsoft.com/zh-tw/download/search.aspx?q=security%20update)取得， 您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。
-   消費性平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以資訊安全和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的資訊安全更新。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](http://support.microsoft.com/kb/913086?ln=zh-tw)。

**IT** **專業人員資訊安全社群**

在 [IT 專業人員資訊安全社群](http://technet.microsoft.com/zh-tw/security/cc136632.aspx)上，學習如何提升資訊安全以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類資訊安全議題的討論。

#### 感謝

Microsoft [感謝](http://technet.microsoft.com/zh-tw/security/gg309157.aspx)下列人士協助我們一同保護我們的客戶：

**MS13-059**

-   感謝 [Corelan](http://www.corelangcv.com/) Peter 'corelanc0d3r' Van Eeckhoutte 的與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3184)
-   感謝 [Google Security Team](http://www.google.com/) 的 Fermin J. Serna 回報程序完整性層級指派資訊安全風險 (CVE-2013-3186)
-   感謝 Arthur Gerkis 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3187)
-   感謝 [Security-Assessment.com](http://www.security-assessment.com/) 的 Scott Bell 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3188)
-   感謝 [Security-Assessment.com](http://www.security-assessment.com/) 的 Scott Bell 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3189)
-   感謝 [Google Security Team](http://www.google.com/) 的 Ivan Fratric 和 Ben Hawkes 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3190)
-   感謝 [Google Security Team](http://www.google.com/) 的 Ivan Fratric 和 Ben Hawkes 回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3191)
-   感謝 Alex Inführ 回報 EUC-JP 字元編碼資訊安全風險 (CVE-2013-3192)
-   感謝 Jose Antonio Vazquez Gonzalez 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3193)
-   感謝 Arthur Gerkis 與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3194)
-   感謝匿名的研究人員與 [HP](http://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 Internet Explorer 記憶體損毀資訊安全風險 (CVE-2013-3199)
-   感謝 [VUPEN Security](http://www.vupen.com/) 與 [HP 的](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 協助我們解決本公告中所含之深度防禦變更的問題

**MS13-060**

-   感謝 [Mozilla](http://www.mozilla.org/) 的 Bob Clary 回報 Uniscribe 字型剖析引擎記憶體損毀資訊安全風險 (CVE-2013-3181)

**MS13-063**

-   感謝 [VUPEN Security](http://www.vupen.com/) 與 [HP 的](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作協助我們解決 ASLR 資訊安全功能略過資訊安全風險 (CVE-2013-2556)
-   感謝 [NSFOCUS Security Team](http://www.nsfocus.com/) 的 Yang Yu 協助我們解決 ASLR 資訊安全功能略過資訊安全風險 (CVE-2013-2556)
-   感謝 [Google Inc](http://www.google.com/) 的 [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org/) 回報 Windows 核心損毀資訊安全風險 (CVE-2013-3196)
-   感謝 [Google Inc](http://www.google.com/) 的 [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org/) 回報 Windows 核心損毀資訊安全風險 (CVE-2013-3197)
-   感謝 [Google Inc](http://www.google.com/) 的 [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org/) 回報 Windows 核心損毀資訊安全風險 (CVE-2013-3198)

**MS13-065**

-   感謝 Symantec 的 Basil Gabriel 回報 ICMPv6 資訊安全風險 (CVE-2013-3183)

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 支援週期](http://support.microsoft.com/default.aspx?scid=fh;%5bln%5d;lifecycle)。
-   IT 專業人員的資訊安全解決方案： [TechNet 資訊安全疑難排解與支援](http://technet.microsoft.com/security/bb980617)
-   協助保護您的 Widows 電腦免於病毒和惡意軟體攻擊： [病毒解決方案與資訊安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-tw)
-   您所在國家/地區的當地支援： [國際支援](http://support.microsoft.com/common/international.aspx?ln=zh-tw)

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2013 年 8 月 13 日)： 公告摘要發行。
-   V2.0 (2013 年 8 月 19 日)： 針對 MS13-066，修訂公告以宣佈重新提供 Windows Server 2008 和 Windows Server 2008 R2 上 Active Directory Federation Services 2.0 的 2843638 更新。詳細資訊請參閱公告。
-   V3.0 (2013 年 8 月 28 日)： 針對 MS13-061，修訂公告以宣佈重新提供 Microsoft Exchange Server 2013 積存更新 1 和 Microsoft Exchange Server 2013 積存更新 2 的 2874216 更新。詳細資訊請參閱公告。

*Built at 2014-04-18T01:50:00Z-07:00*
