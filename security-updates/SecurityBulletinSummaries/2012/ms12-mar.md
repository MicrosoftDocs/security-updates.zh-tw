---
TOCTitle: 'MS12-MAR'
Title: 2012 年 3 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms12-mar'
ms:contentKeyID: 61237733
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms12-mar(v=Security.10)'
---

2012 年 3 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2012年3月13日

**版本:** 1.0

此公告摘要列出 2012 年 3 月份所發行之安全性公告。

發行 2012 年 3 月份安全性公告之後，此公告摘要將取代原先於 2012 年 3 月 8 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](http://go.microsoft.com/fwlink/?linkid=217213)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2012 年 3 月 14 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。立即註冊參加 3 月份安全性公告網路廣播。在這個日期後，此網路廣播將可隨選取得。如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](http://go.microsoft.com/fwlink/?linkid=217214) (英文)。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232664">MS12-020</a></td>
<td style="border:1px solid black;">遠端桌面中的弱點可能會允許遠端執行程式碼 (2671387) <br />
<br />
此安全性更新可解決遠端桌面通訊協定中兩項未公開報告的弱點。如果攻擊者將蓄意製作的 RDP 封包序列傳送至受影響的系統，這些弱點中較嚴重者可能會允許遠端執行程式碼。依據預設，所有 Windows 作業系統上均未啟用遠端桌面通訊協定 (RDP)。未啟用的 RDP 的系統則無風險。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235401">MS12-017</a></td>
<td style="border:1px solid black;">DNS 伺服器中的弱點可能會允許拒絕服務 (2647170) <br />
<br />
這個安全性更新可解決 Microsoft Windows 中一項未公開報告的弱點。如果遠端未經驗證的攻擊者將蓄意製作的 DNS 查詢傳送至目標 DNS 伺服器，此弱點可能會允許拒絕服務。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
阻斷服務 (DoS)</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235364">MS12-018</a></td>
<td style="border:1px solid black;">Windows 核心模式驅動程式的弱點可能會允許權限提高 (2641653) <br />
<br />
這個安全性更新可解決 Microsoft Windows 中一項未公開報告的弱點。如果攻擊者登入系統並執行蓄意製作的應用程式，則這個弱點可能允許權限提高。攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項弱點。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235362">MS12-021</a></td>
<td style="border:1px solid black;">Visual Studio 中的弱點可能會允許權限提高 (2651019) <br />
<br />
此安全性更新可解決 Visual Studio 中一項未公開報告的弱點。如果攻擊者將蓄意製作的增益集放在 Visual Studio 所使用的路徑中，並引誘權限較高的使用者啟動 Visual Studio，此弱點便可能允許權限提高。攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項弱點。匿名或遠端使用者無法利用這個弱點。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Visual Studio</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235361">MS12-022</a></td>
<td style="border:1px solid black;">Expression Design 中的弱點可能會允許遠端執行程式碼 (2651018) <br />
<br />
此安全性更新可解決 Microsoft Expression Design 中一項未公開報告的弱點。如果使用者開啟與蓄意製作之動態連結程式庫 (DLL) 檔案位於相同網路目錄的合法檔案 (例如 .xpr 或 .DESIGN 檔)，此弱點可能會允許遠端執行程式碼。之後在開啟合法檔案時，Microsoft Expression Design 可能會嘗試載入 DLL 檔案，並執行其內含的任何程式碼。使用者必須造訪不受信任的遠端檔案系統位置或 WebDAV 共用，並從該位置開啟合法檔案 (例如 .xpr 或 .DESIGN 檔案)，讓檔案被有弱點的應用程式所載入，攻擊才有可能成功。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Expression Design</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=239573">MS12-019</a></td>
<td style="border:1px solid black;">DirectWrite 中的弱點 可能會允許拒絕服務 (2665364) <br />
<br />
此安全性更新可解決 Windows DirectWrite 中一項公開揭露的弱點。在 Instant Messenger 型攻擊的情況中，如果攻擊者將蓄意製作的 Unicode 字元序列直接傳送至 Instant Messenger 用戶端，此弱點可能會允許拒絕服務。當 DirectWrite 轉譯蓄意製作的 Unicode 字元序列時，目標應用程式可能會變成沒有回應而無法繼續。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">中度</a> <br />
阻斷服務 (DoS)</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
弱點索引  
--------
  
<span></span>
下表提供本月所述每個弱點的利用性評估。弱點皆根據公告編號和 CVE 編號依序列出。僅包含安全性公告中，嚴重性等級為「重大」或「重要」的弱點。
  
我該如何使用這個表格？
  
您可以運用此表格，針對您可能需要安裝的每一項安全性更新，瞭解弱點在安全性公告發行 30 日內遭成功利用而導致程式碼執行與拒絕服務的可能性。請根據您特定的組態設定，檢閱下列各項評估，決定部署本月份更新的優先次序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](http://technet.microsoft.com/security/cc998259.aspx)。
  
在下方欄位中，「最新軟體版本」意指受影響軟體，「較舊軟體版本」意指受影響軟體所有較舊的支援版本，如公告中的「受影響的軟體」或「不受影響的軟體」表格裡所示。

 
<p> </p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >公告編號</th>
<th style="border:1px solid black;" >弱點標題</th>
<th style="border:1px solid black;" >CVE ID</th>
<th style="border:1px solid black;" >最新軟體版本的弱點評估</th>
<th style="border:1px solid black;" >較舊軟體版本的弱點評估</th>
<th style="border:1px solid black;" >拒絕服務弱點評估</th>
<th style="border:1px solid black;" >主要重點</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235401">MS12-017</a></td>
<td style="border:1px solid black;">DNS 拒絕服務弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0006">CVE-2012-0006</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">這是一項拒絕服務的弱點。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235364">MS12-018</a></td>
<td style="border:1px solid black;">PostMessage 函式弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0157">CVE-2012-0157</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232664">MS12-020</a></td>
<td style="border:1px solid black;">遠端桌面通訊協定弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0002">CVE-2012-0002</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">這是一項未經驗證遠端執行程式碼弱點。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232664">MS12-020</a></td>
<td style="border:1px solid black;">終端伺服器拒絕服務弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0152">CVE-2012-0152</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">暫時</td>
<td style="border:1px solid black;">這是一項拒絕服務的弱點。<br />
<br />
只有最新版本會受拒絕服務攻擊 (DoS) 影響。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235362">MS12-021</a></td>
<td style="border:1px solid black;">Visual Studio 增益集弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0008">CVE-2012-0008</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235361">MS12-022</a></td>
<td style="border:1px solid black;">Expression Design 不安全程式庫載入弱點</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0016">CVE-2012-0016</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
</tbody>
</table>
  
受影響的軟體及下載位置  
----------------------
  
<span></span>
下表依據主要的軟體類別和嚴重性依序列出公告。
  
我該如何使用這些表格？
  
請用這些表格來瞭解可能需要安裝的安全性更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的安全性更新。若軟體程式或更新出現在清單中，則相關可用軟體更新也會以超連結方式提供，也會列出軟體更新的嚴重性等級。
  
注意：一項弱點，可能需要安裝數個安全性更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
#### Windows 作業系統與元件

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="5">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-020](http://go.microsoft.com/fwlink/?linkid=232664)
</td>
<td style="border:1px solid black;">
[MS12-017](http://go.microsoft.com/fwlink/?linkid=235401)
</td>
<td style="border:1px solid black;">
[MS12-018](http://go.microsoft.com/fwlink/?linkid=235364)
</td>
<td style="border:1px solid black;">
[MS12-019](http://go.microsoft.com/fwlink/?linkid=239573)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[重大](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=18a1fe48-1318-4b93-afad-206950bb1ae5)  
(KB2621440)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=2922411c-9755-461b-9904-f6940322af19)  
(重要)
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
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=eccf865d-399a-4862-b26f-f35580419875)  
(KB2621440)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e72b6b1f-68f5-4e1a-878e-290a5f03ca30)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-020](http://go.microsoft.com/fwlink/?linkid=232664)
</td>
<td style="border:1px solid black;">
[MS12-017](http://go.microsoft.com/fwlink/?linkid=235401)
</td>
<td style="border:1px solid black;">
[MS12-018](http://go.microsoft.com/fwlink/?linkid=235364)
</td>
<td style="border:1px solid black;">
[MS12-019](http://go.microsoft.com/fwlink/?linkid=239573)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
彙總 嚴重性等級
</td>
<td style="border:1px solid black;">
[重大](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b69b4b9b-c0a1-4c1e-b081-8529eaf1536a)  
(KB2621440)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b04da098-666f-4760-90da-d2a17e78bf47)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=599e5db1-3bf1-4d44-bc7c-81bc545c58ec)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8081e67f-288c-4714-bff8-e0ff9777692f)  
(KB2621440)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=647eaf09-3959-439e-8418-fd25221eb6b9)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=482c2890-8d4c-4e13-820f-d5ff256b6a3a)  
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
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=521baa02-5d7a-4cba-8a1a-2af1b6e4cbe4)  
(KB2621440)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=92f3af60-9a9b-4419-9e95-55f5cb54cf00)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=ccd0f116-73c2-4471-a6d9-e07d1dbdd406)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="5">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-020](http://go.microsoft.com/fwlink/?linkid=232664)
</td>
<td style="border:1px solid black;">
[MS12-017](http://go.microsoft.com/fwlink/?linkid=235401)
</td>
<td style="border:1px solid black;">
[MS12-018](http://go.microsoft.com/fwlink/?linkid=235364)
</td>
<td style="border:1px solid black;">
[MS12-019](http://go.microsoft.com/fwlink/?linkid=239573)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[重大](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[中度](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=39abdf7b-ea9d-4b95-a28d-4140374d531d)  
(KB2621440)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f4e73a92-583b-4352-b19d-7a8e3ef162b7)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7da5b341-6a6f-46de-8d01-448da38e9908)  
(中度)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e5970daf-4440-42fa-8efc-e6190c6a22aa)  
(KB2621440)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ead9d29b-becf-448e-bff4-d5bb12d02c64)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1ba25d9c-0fef-471f-8e30-045fe9586a9c)  
(中度)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-020](http://go.microsoft.com/fwlink/?linkid=232664)
</td>
<td style="border:1px solid black;">
[MS12-017](http://go.microsoft.com/fwlink/?linkid=235401)
</td>
<td style="border:1px solid black;">
[MS12-018](http://go.microsoft.com/fwlink/?linkid=235364)
</td>
<td style="border:1px solid black;">
[MS12-019](http://go.microsoft.com/fwlink/?linkid=239573)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[重大](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[中度](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=fef2c1d7-2004-43d7-aa49-673c6f374670)\*  
(KB2621440)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=233c62b7-f2b1-49ce-9a7f-e51435be0d26)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=dd547364-f6bb-453c-9e4d-6b80dfc47fbb)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=45a4784e-5051-4628-9a19-d53f30c1fdf3)\*\*  
(中度)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4ffae13f-3432-4849-a2da-a76f96d7ceb3)\*  
(KB2621440)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=56eae770-5990-4e1b-8b48-3d0602fcc72b)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5ff65fc2-5969-4d7e-9c72-9a2096dafdcf)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=503cb9c0-d6db-4deb-a555-67af0b25739b)\*\*  
(中度)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=67581250-50fd-4f4c-a3cc-45ce2662b0c3)  
(KB2621440)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=eeb5385c-fb81-4d33-af2a-986e6cf14ee2)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="5">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-020](http://go.microsoft.com/fwlink/?linkid=232664)
</td>
<td style="border:1px solid black;">
[MS12-017](http://go.microsoft.com/fwlink/?linkid=235401)
</td>
<td style="border:1px solid black;">
[MS12-018](http://go.microsoft.com/fwlink/?linkid=235364)
</td>
<td style="border:1px solid black;">
[MS12-019](http://go.microsoft.com/fwlink/?linkid=239573)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[重大](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[中度](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=16b0195c-84d3-4c08-8b98-ff2c80d144e1)  
(KB2621440)  
(重大)  
[適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=3a6c7fdf-105a-4886-ad52-c892f37e32d1)  
(KB2667402)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=75fd93ff-5be5-42b5-ab00-3378e545c271)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=f3a14012-38ae-490e-a48e-7c851f82a7e6)  
(中度)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=40b62d08-d2a2-4900-b01c-46fc761973d0)  
(KB2621440)  
(重大)  
[適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=1bbe7cda-4bee-4d65-8127-3c13624a1168)  
(KB2667402)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=71ffba4c-d816-45a9-abef-131915885bc8)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=760b5aa4-4e65-4ff1-9ae2-771234803bf0)  
(中度)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-020](http://go.microsoft.com/fwlink/?linkid=232664)
</td>
<td style="border:1px solid black;">
[MS12-017](http://go.microsoft.com/fwlink/?linkid=235401)
</td>
<td style="border:1px solid black;">
[MS12-018](http://go.microsoft.com/fwlink/?linkid=235364)
</td>
<td style="border:1px solid black;">
[MS12-019](http://go.microsoft.com/fwlink/?linkid=239573)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[重大](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[中度](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=7c1774cc-e00c-47f3-97a2-bc90de857793)\*  
(KB2621440)  
(重大)  
[適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=7ec21f41-1673-4592-b45c-6438ad57e08c)\*  
(KB2667402)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=19a4f3d1-24d2-41af-a41a-e5cc2c6232e8)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=22d6a234-6447-4854-8119-4fddd3c6e1bb)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=86095b20-5869-4b55-8777-ee0af82aaf37)\*\*  
(中度)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 和適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2 和適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6a07f99c-8ab4-4e44-8d48-6ac787dd2b51)  
(KB2621440)  
(重大)  
[適用於 Itanium 型系統的 Windows Server 2008 R2 和適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=469aa1f6-ed89-4649-8736-eaa5e2ad44ee)  
(KB2667402)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2 和適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=cb5ac981-e8e5-4df7-84bb-7a2a916d0ce9)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2 和適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=dc5c336f-329c-4a56-8b24-555e3c8afd50)  
(中度)
</td>
</tr>
</table>
 
Windows Server 2008 和 Windows Server 2008 R2 注意事項

\*Server Core 安裝會受影響。無論上述受支援的 Windows Server 2008 或 Windows Server 2008 R2 版本是否使用 Server Core 安裝選項安裝，這個更新均以相同的嚴重性等級套用。如需此安裝選項的詳細資訊，請參閱 TechNet 文章：[管理 Server Core 安裝](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (英文) 和[維護 Server Core 安裝](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 和 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

\*\*Server Core 安裝不受影響。如果 Windows Server 2008 或 Windows Server 2008 R2 是使用 Server Core 安裝選項所安裝，則這項更新解決的弱點並不會影響受支援的 Windows Server 2008 或 Windows Server 2008 R2。如需此安裝選項的詳細資訊，請參閱 TechNet 文章：[管理 Server Core 安裝](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (英文) 和[維護 Server Core 安裝](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 和 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

#### Microsoft 開發者工具和軟體

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="3">
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-021](http://go.microsoft.com/fwlink/?linkid=235362)
</td>
<td style="border:1px solid black;">
[MS12-022](http://go.microsoft.com/fwlink/?linkid=235361)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2008 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=99d7c39a-14f1-4e7e-8a4f-2466b16821eb)  
(KB2669970)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2010
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2010](https://www.microsoft.com/download/details.aspx?familyid=f80235ae-da15-4527-93b3-c2f31ec2f387)  
(KB2644980)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2010 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=e2aaec35-b2c0-48f0-8a51-34e44f6d12fb)  
(KB2645410)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Expression Design
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-021](http://go.microsoft.com/fwlink/?linkid=235362)
</td>
<td style="border:1px solid black;">
[MS12-022](http://go.microsoft.com/fwlink/?linkid=235361)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Expression Design
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Expression Design](https://www.microsoft.com/download/details.aspx?familyid=49e12f3a-718d-4d54-82be-b78efb372d07)  
(KB2675064)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Expression Design Service Pack 1
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Expression Design Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=899c6860-6081-429b-971a-4d689444920f)  
(KB2667724)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Expression Design 2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Expression Design 2](https://www.microsoft.com/download/details.aspx?familyid=2ca4fb5a-3ab4-410b-b42b-075eb1d70410)  
(KB2667725)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Expression Design 3
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Expression Design 3](https://www.microsoft.com/download/details.aspx?familyid=73b44e97-6dda-4e24-9758-e86a1de4c0c8)  
(KB2667727)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Expression Design 4
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Expression Design 4](https://www.microsoft.com/download/details.aspx?familyid=be56221e-4271-42dc-a6e4-ebf0290e4ad8)  
(KB2667730)  
(重要)
</td>
</tr>
</table>
 

偵測與部署工具及指南
--------------------

<span></span>
資訊安全中心

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和安全性更新。如需更多資訊，請參閱 [TechNet 更新管理中心](http://go.microsoft.com/fwlink/?linkid=69903) (英文)。[TechNet 資訊安全技術中心](http://go.microsoft.com/fwlink/?linkid=21171)提供 Microsoft 產品安全性的其他資訊。消費者可以造訪[在家上網的安全性](http://go.microsoft.com/fwlink/?linkid=85102)網站，只要按一下 \[最新安全性更新\] 即可在此網站取得此資訊。

安全性更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 以及 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) 取得。安全性更新也可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得。您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。

對於 Microsoft Office for Mac 的客戶，Microsoft AutoUpdate for Mac 可協助您保持最新的 Microsoft 軟體。如需使用 Microsoft AutoUpdate for Mac 的詳細資訊，請參閱[自動檢查軟體更新](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea) (英文)。

最後，您可以從 [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) 下載安全性更新。Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括安全性更新、驅動程式和 Service Pack。只要以安全性公告編號 (例如：MS07-036) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](http://go.microsoft.com/fwlink/?linkid=97900)。

偵測與部署指南

Microsoft 針對安全性更新提供偵測和部署指南。本指南所含之建議和資訊，能幫助 IT 專業人員瞭解如何使用用於安全性更新的偵測和部署的各種工具。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 961747](http://support.microsoft.com/kb/961747)。

Microsoft Baseline Security Analyzer

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少安全性更新以及一般安全性設定錯誤的狀況。如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)。

Windows Server Update Services

透過 Windows Server Update Services (WSUS)，系統管理員可迅速而可靠地將 Microsoft Windows 2000 作業系統及更新版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 適用的最新重大更新與安全性更新部署到 Microsoft Windows 2000 及更新版本的作業系統中。

如需更多關於利用 Windows Server Update Services 部署安全性更新的資訊，請造訪 [Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/default.aspx) (英文)。

System Center Configuration Manager 2007

Configuration Manager 2007 軟體更新管理可簡化遞送和管理企業中 IT 系統更新的繁複作業。IT 系統管理員可以使用 Configuration Manager 2007 遞送 Microsoft 產品更新給各種裝置，包括桌上型電腦、筆記型電腦、伺服器及行動裝置。

Configuration Manager 2007 中的自動弱點評估會找出更新需求並報告建議動作。Configuration Manager 2007 中的軟體更新管理是建置在 Microsoft Windows Software Update Services (WSUS) 上，經過時間考驗，為全球 IT 系統管理員所熟悉的更新基礎架構。如需更多有關系統管理員如何使用 Configuration Manager 2007 來部署更新的資訊，請參閱[軟體更新管理](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx) (英文)。如需更多有關 Configuration Manager 的資訊，請造訪 [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx)。

Systems Management Server 2003

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。

注意：System Management Server 2003 自 2010 年 1 月 12 日起不受主流支援。如需更多有關產品生命週期的資訊，請造訪 [Microsoft 支援週期](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle)。現已推出新版的 SMS：System Center Configuration Manager 2007；請參閱前段的＜System Center Configuration Manager 2007＞一節。

如需更多有關系統管理員如何使用 SMS 2003 來部署安全性更新的資訊，請參閱 [Microsoft Systems Management Server 2003 的案例與程序： 軟體發佈和補充程式管理](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en) (英文)。如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server 技術中心 (TechCenter)](http://technet.microsoft.com/zh-tw/systemcenter/bb545936.aspx)。

注意 ：SMS 使用 Microsoft Baseline Security Analyzer 提供廣泛的安全性公告更新偵測與部署支援。不過這些工具可能無法偵測部分的軟體更新。在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](http://go.microsoft.com/fwlink/?linkid=33341) (英文)。某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。系統管理員可使用 Elevated Rights Deployment Tool (隨附於 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)) 來安裝這些更新。

Update Compatibility Evaluator 和 Application Compatibility Toolkit

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。這可能會觸發不相容性，而拉長部署安全性更新的時間。您可以使用 [Application Compatibility Toolkit](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 隨附的 [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 元件，針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Windows Vista、Windows Update、Microsoft 安全性更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非安全性更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](http://support.microsoft.com/kb/894199)
-   ： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](http://technet.microsoft.com/en-us/wsus/bb456965.aspx)
-   。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的安全性保護，Microsoft 將在每月發行安全性更新之前，提前向重要安全性軟體提供者提供弱點資訊。安全性軟體提供者可利用此弱點資訊，透過其安全性軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有安全性軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://go.microsoft.com/fwlink/?linkid=215201) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 安全性策略與社群

更新程式管理策略

[更新管理安全性指南](http://go.microsoft.com/fwlink/?linkid=21168) (英文) 提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

取得其他安全性更新

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   消費性平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](http://support.microsoft.com/kb/913086)。

IT 專業人員資訊安全社群

在 [IT 專業人員安全性社群](http://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](http://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 [Nikolaos Bougalis](https://technet.microsoft.com/zh-TW/mailto:nikb@bougalis.net) 回報 MS12-018 中描述的一項問題
-   感謝 Khaled M. Salameh 回報 MS12-019 中描述的一項問題
-   感謝 Luigi Auriemma 與 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 MS12-020 中描述的一項問題
-   感謝 [Laplinker](http://www.laplinker.com) 回報 MS12-021 中描述的一項問題
-   感謝 [Laplinker](http://www.laplinker.com) 回報 MS12-022 中描述的一項問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 支援週期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可洽詢[安全性支援](http://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY (1-866-727-2338) 以取得技術支援。如需更多可用支援選項的資訊，請參閱 [Microsoft 技術支援](http://support.microsoft.com/)。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[國際化支援](http://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2012 年 3 月 13 日)： 公告摘要發行。

*Built at 2014-04-18T01:50:00Z-07:00*
