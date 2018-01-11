---
TOCTitle: 'MS15-JAN'
Title: 2015 年 1 月份 Microsoft 資訊安全佈告欄摘要
ms:assetid: 'ms15-jan'
ms:contentKeyID: 63898352
ms:date: '01/13/2015'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms15-jan(v=Security.10)'
---

2015 年 1 月份 Microsoft 資訊安全佈告欄摘要
===========================================

發行日期：2015 年 1 月 13 日

**版本：** 1.0

此佈告摘要列出 2015 年 1 月份發行之資訊安全佈告欄。

如需有關如何在 Microsoft 資訊安全佈告欄發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://technet.microsoft.com/zh-tw/security/dd252948.aspx)。

Microsoft 也會提供資訊協助客戶排定每月資訊安全更新以及任何非資訊安全更新的優先順序，其中這些非資訊安全更新的發行日期與每月資訊安全更新的發行日期相同。請參閱**＜其他資訊＞**一節。

提要
----

下表依嚴重性摘要說明本月份資訊安全佈告欄。

如需受影響之軟體的詳細資料，請參閱下節**＜受影響的軟體＞**。

 
<p></p>
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>資訊安全佈告欄 ID</strong></td>
<td style="border:1px solid black;"><strong>佈告標題與提要</strong></td>
<td style="border:1px solid black;"><strong>最高的嚴重性等級與資訊安全風險影響</strong></td>
<td style="border:1px solid black;"><strong>重新開機需求</strong></td>
<td style="border:1px solid black;"><strong>受影響的軟體</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522536">MS15-001</a></td>
<td style="border:1px solid black;"><strong>Windows 應用程式相容性快取中的資訊安全風險可能會允許權限提高 (3023266)<br />
<br />
</strong>此資訊安全更新可解決 Microsoft Windows 中一項公開揭露的資訊安全風險。如果攻擊者登入系統並執行蓄意製作的應用程式，則這個資訊安全風險可能允許權限提高。成功利用此資訊安全風險的驗證攻擊者，可以略過現有於 Microsoft Windows 應用程式相容性元件的快取修改中操作的權限檢查，並使用提高的權限執行任意程式碼。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522537">MS15-002</a></td>
<td style="border:1px solid black;"><strong>Windows Telnet 服務中的資訊安全風險可能會允許遠端執行程式碼 (3020393)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果攻擊者傳送蓄意製作的封包到受影響的 Windows 伺服器，這項資訊安全風險可允許遠端執行程式碼。依照預設，Telnet 並未安裝於任何受影響的作業系統版本上。唯有手動安裝此項服務的客戶，才有可能受影響。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522528">MS15-003</a></td>
<td style="border:1px solid black;"><strong>Windows 使用者設定檔服務中的資訊安全風險可能會允許權限提高 (3021674)</strong><br />
<br />
此安全性更新可解決 Microsoft Windows 中一項公開揭露的資訊安全風險。如果攻擊者登入系統並執行蓄意製作的應用程式，則此資訊安全風險可能允許權限提高。一旦攻擊得逞，本機攻擊者將能在目標系統上以提高的權限執行任意程式碼。攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522521">MS15-004</a></td>
<td style="border:1px solid black;"><strong>Windows 元件中的資訊安全風險可能會允許權限提高 (3025421)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果攻擊者成功誘使使用者執行蓄意製作的應用程式，則此資訊安全風險可能允許權限提高。成功利用此資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。如果目前的使用者以系統管理的使用者權限登入，攻擊者接下來就能安裝程式，並檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。系統上帳戶使用者權限較低的客戶，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522531">MS15-005</a></td>
<td style="border:1px solid black;"><strong>網路位置感知服務中的資訊安全風險可能會允許資訊安全功能略過 (3022777)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。此資訊安全風險發生於與受害者位於相同網路的攻擊者偽造受害者啟動的 DNS 和 LDAP 流量回應時，無意間放鬆防火牆原則及/或某些服務的設定造成資訊安全功能略過。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
資訊安全功能略過</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522535">MS15-006</a></td>
<td style="border:1px solid black;"><strong>Windows 錯誤報告中的資訊安全風險可能允許安全性功能略過 (3004365)</strong><br />
<br />
此資訊安全更新可解決 Windows 錯誤報告 (WER) 中一項未公開報告的資訊安全風險。如果攻擊者成功利用此資訊安全風險，可能會允許資訊安全功能略過。成功利用這項資訊安全風險的攻擊者可存取執行程序的記憶體。設定為具有較少使用者權限的使用者帳戶所受到的影響，可能會比利用系統管理使用者權限進行操作的使用者帳戶小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
資訊安全功能略過</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519134">MS15-007</a></td>
<td style="border:1px solid black;"><strong>網路原則伺服器 RADIUS 實施中的資訊安全風險可能會導致阻斷服務 (3014029)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。此資訊安全風險在攻擊者傳送蓄意製作的 Username 字串值至網際網路驗證服務 (IAS) 或網路原則伺服器 (NPS) 時，將導致 IAS 或 NPS 阻斷服務。請注意，拒絕服務資訊安全風險不會允許攻擊者執行程式碼或提高其使用者權限，但會導致 RADIUS 認證在 IAS 或 NPS 上無法使用。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
阻斷服務 (DoS)</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522533">MS15-008</a></td>
<td style="border:1px solid black;"><strong>Windows 核心模式驅動程式的資訊安全風險可能會允許權限提高 (3019215)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果攻擊者在受影響的系統上執行蓄意製作的應用程式，這項資訊安全風險可能會允許權限提高。攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/gg309177.aspx">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
 
  
資訊安全風險入侵指數  
--------------------
  
下表提供本月所述每個資訊安全風險的利用性評估。會依序按佈告編號及 CVE ID 的順序列出資訊安全風險。只會包含佈告中嚴重性等級為「重大」或「重要」的資訊安全風險。
  
**我該如何使用這個表格？**
  
您可以運用此表格，針對您可能需要安裝的每一項資訊安全更新，瞭解資訊安全風險在資訊安全佈告欄發行 30 日內遭成功利用而導致程式碼執行與阻斷服務 (DoS) 的可能性。請根據您特定的組態設定，檢閱下列各項評估，決定部署本月份更新的優先次序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](http://technet.microsoft.com/zh-tw/security/cc998259)。
  
在下方欄位中，「最新軟體版本」意指受影響軟體，「較舊軟體版本」意指受影響軟體所有較舊的支援版本，如佈告中的「受影響的軟體」或「不受影響的軟體」表格裡所示。
  
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
<td style="border:1px solid black;"><strong>資訊安全佈告欄 ID</strong></td>
<td style="border:1px solid black;"><strong>資訊安全風險標題</strong></td>
<td style="border:1px solid black;"><strong>CVE ID</strong></td>
<td style="border:1px solid black;"><strong>最新軟體版本的資訊安全風險評估</strong></td>
<td style="border:1px solid black;"><strong>較舊軟體版本的資訊安全風險評估</strong></td>
<td style="border:1px solid black;"><strong>阻斷服務 (DoS) 資訊安全風險評估</strong></td>
<td style="border:1px solid black;"><strong>主要重點</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522536">MS15-001</a></td>
<td style="border:1px solid black;">Microsoft 應用程式相容性基礎結構權限提高的資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0002">CVE-2015-0002</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">此資訊安全風險已經遭到公開揭發。<br />
<br />
這是權限提高的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522537">MS15-002</a></td>
<td style="border:1px solid black;">Windows Telnet 服務緩衝區溢位資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0014">CVE-2015-0014</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">這是遠端執行程式碼的資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522528">MS15-003</a></td>
<td style="border:1px solid black;">Microsoft 使用者設定檔服務權限提高的資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0004">CVE-2015-0004</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">此資訊安全風險已經公開揭發。<br />
<br />
這是權限提高的資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522521">MS15-004</a></td>
<td style="border:1px solid black;">目錄周遊權限提高資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0016">CVE-2015-0016</a></td>
<td style="border:1px solid black;">0 - 已偵測到利用</td>
<td style="border:1px solid black;">0 - 已偵測到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是權限提高的資訊安全風險。<br />
<br />
此資訊安全風險正被用於略過沙箱的受限、目標式攻擊。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522531">MS15-005</a></td>
<td style="border:1px solid black;">NLA 資訊安全功能略過資訊安全風險 - CVE-2015-0006</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0006">CVE-2015-0006</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊安全功能略過之資訊安全風險。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522535">MS15-006</a></td>
<td style="border:1px solid black;">Windows 錯誤報告資訊安全功能略過資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0001">CVE-2015-0001</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊安全功能略過之資訊安全風險。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519134">MS15-007</a></td>
<td style="border:1px solid black;">網路原則伺服器 RADIUS 實作拒絕服務資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0015">CVE-2015-0015</a></td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">3 - 不太可能遭到利用</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">此資訊安全風險會造成拒絕服務。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522533">MS15-008</a></td>
<td style="border:1px solid black;">WebDAV 權限提高資訊安全風險</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0011">CVE-2015-0011</a></td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">2 - 遭到利用的可能性較小</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是權限提高的資訊安全風險。</td>
</tr>
</tbody>
</table>
  
 
  
受影響的軟體  
------------
  
下表依據主要的軟體類別和嚴重性依序列出佈告。
  
請用這些表格來瞭解可能需要安裝的資訊安全更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的資訊安全更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。
  
**注意**：一項資訊安全風險，可能需要安裝數個資訊安全更新才能妥善解決。請參閱各佈告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
### Windows 作業系統與元件

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**佈告編號**

</td>
<td style="border:1px solid black;">
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3020393)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2<sup>[1]</sup>
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3014029)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3020393)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2<sup>[1]</sup>
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3014029)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Itanium 系統 (含 SP2)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2003 Itanium 系統 (含 SP2)  
(3020393)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Itanium 系統 (含 SP2)  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 Itanium 系統的 Windows Server 2003 包含 SP2<sup>[1]</sup>
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2003 Itanium 系統 (含 SP2)  
(3014029)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Itanium 系統 (含 SP2)  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**佈告編號**

</td>
<td style="border:1px solid black;">
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3020393)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2 (已安裝遠端桌面用戶端 7.0)  
(3023299)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3019215)  
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
Windows Vista x64 Edition Service Pack 2  
(3020393)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2 (已安裝遠端桌面用戶端 7.0)  
(3023299)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**佈告編號**

</td>
<td style="border:1px solid black;">
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

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
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2  
(3020393)  
(重大)

</td>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2  
(3014029)  
(重要)

</td>
<td style="border:1px solid black;">
32 位元系統的 Windows Server 2008 Service Pack 2  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3020393)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3014029)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2  
(3020393)  
(重大)

</td>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Itanium 系統的 Windows Server 2008 Service Pack 2  
(3022777)  
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
<td style="border:1px solid black;" colspan="9">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**佈告編號**

</td>
<td style="border:1px solid black;">
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3020393)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3019978)  
(重要)  
32 位元系統的 Windows 7 Service Pack 1 (已安裝遠端桌面用戶端 8.0)  
(3020387)  
(重要)  
32 位元系統的 Windows 7 Service Pack 1 (已安裝遠端桌面用戶端 8.1)  
(3020388)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 7 32 位元系統 Service Pack 1  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3020393)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3019978)  
(重要)  
Windows 7 x64 系統 Service Pack 1 (已安裝遠端桌面用戶端 8.0)  
(3020387)  
(重要)  
Windows 7 x64 系統 Service Pack 1 (已安裝遠端桌面用戶端 8.1)  
(3020388)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 7 x64 系統 Service Pack 1  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**佈告編號**

</td>
<td style="border:1px solid black;">
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3020393)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3019978)  
(重要)  
Windows Server 2008 R2 x64 系統 Service Pack 1 (已安裝遠端桌面用戶端 8.0)  
(3020387)  
(重要)  
Windows Server 2008 R2 x64 系統 Service Pack 1 (已安裝遠端桌面用戶端 8.1)  
(3020388)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3014029)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 系統 Service Pack 1  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3020393)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3019978)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1  
(3022777)  
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
<td style="border:1px solid black;" colspan="9">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**佈告編號**

</td>
<td style="border:1px solid black;">
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 32 位元系統

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3020393)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3019978)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3004365)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8 32 位元系統  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 x64 系統

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3020393)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3019978)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3022777) )  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3004365)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8 x64 系統  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3020393)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3019978)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3022777) )  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3004365)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8.1 32 位元系統  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 x64 系統

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3020393)  
(重大)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3019978)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3022777) )  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3004365)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 系統  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**佈告編號**

</td>
<td style="border:1px solid black;">
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3020393)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3019978)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3004365)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3014029)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3020393)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3019978)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3004365)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3014029)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**佈告編號**

</td>
<td style="border:1px solid black;">
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**無**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Windows RT  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3019978)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT  
(3004365)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3019978)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3004365)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Server Core 安裝選項**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**佈告編號**

</td>
<td style="border:1px solid black;">
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-tw/security/gg309177.aspx)

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
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3020393)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3022777)  
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
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3020393)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
不適用

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2 (Server Core 安裝)  
(3022777)  
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
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3020393)  
(重大)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3019978)  
(重要)

</td>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)  
(3022777)  
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
Windows Server 2012 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3020393)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3019978)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 安裝)  
(3004365)  
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
Windows Server 2012 R2 (Server Core 安裝)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3020393)  
(重大)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3019978)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 安裝)  
(3004365)  
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
 
**MS15-005 注意事項**
<sup>[1]</sup>Windows Server 2003 受到影響，但是目前未發行可用的更新。請參閱佈告，了解詳細資訊。

 

偵測與部署工具及指南
--------------------

有幾項資源可協助系統管理員部署資訊安全更新。

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機與遠端系統是否有遺漏的資訊安全更新或常見的安全性錯誤設定。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 可協助系統管理員發佈資訊安全更新。

應用程式相容性工具組隨附的 Update Compatibility Evaluator 元件可針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

如需上述工具以及其他可使用工具的詳細資訊，請參閱 [IT 專業人員的資訊安全工具](http://technet.microsoft.com/zh-tw/security/cc297183)。

致謝
----

Microsoft 了解資訊安全業界所做的努力，其盡責地透露資訊安全風險來協助我們保護客戶。請參閱[致謝](https://technet.microsoft.com/zh-tw/library/security/dn820091.aspx) (英文) 以取得詳細資訊。

其他資訊
--------

### Microsoft Windows 惡意軟體移除工具 (英文)

針對每個月第二個星期二發行的佈告，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 及下載中心發行更新版本的 Microsoft Windows 惡意軟體移除工具。不定期資訊安全佈告欄發行不提供更新版本的 Microsoft Windows 惡意軟體移除工具。

### MU、WU 及 WSUS 上的非資訊安全更新

如需在 Windows Update 和 Microsoft Update 上發行的非資訊安全更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](https://support.microsoft.com/kb/894199/zh-tw)：Software Update Services 與 Windows Server Update Services 的說明內容有所變動。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](http://technet.microsoft.com/zh-tw/windowsserver/bb332157.aspx)。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的資訊安全保護，Microsoft 將在每月發行資訊安全更新之前，提前向重要資訊安全軟體提供者提供資訊安全風險資訊。資訊安全軟體提供者可利用此資訊安全風險資訊，透過其資訊安全軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://technet.microsoft.com/zh-tw/security/dn467918) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

### 安全性策略與社群

**更新程式管理策略**

[更新管理安全性指南](http://technet.microsoft.com/zh-tw/library/bb466251.aspx) (英文) 提供您有關套用資訊安全更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他資訊安全更新**

其他資訊安全問題的更新可由下列位置取得：

-   資訊安全更新可以從 [Microsoft 下載中心](http://www.microsoft.com/downloads/results.aspx?displaylang=zh-tw&freetext=security%20update)取得，您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。
-   客戶平台的更新可從 [Microsoft Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-tw) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的資訊安全更新。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](https://support.microsoft.com/kb/913086/zh-tw)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](http://technet.microsoft.com/zh-tw/security/cc136632.aspx)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

### 支援

所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](http://go.microsoft.com/fwlink/?linkid=21742)。

IT 專業人員的資訊安全解決方案：[安全性疑難排解與支援](http://technet.microsoft.com/zh-tw/security/bb980617)

協助保護您的 Widows 電腦免於病毒和惡意軟體攻擊：[病毒解决方案和安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-tw)

您所在國家/地區的當地支援：[國際支援](http://support.microsoft.com/common/international.aspx?ln=zh-tw)

### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

### 修訂

-   V1.0 (2015 年 1 月 13 日)：佈告摘要發行。

*頁面產生時間：2015-01-08 14:01Z-08:00。*
