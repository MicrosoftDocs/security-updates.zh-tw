---
TOCTitle: 'MS11-DEC'
Title: 2011 年 12 月份 Microsoft 安全性公告摘要
ms:assetid: 'ms11-dec'
ms:contentKeyID: 61237715
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms11-dec(v=Security.10)'
---

2011 年 12 月份 Microsoft 安全性公告摘要
========================================

發行: 2011年12月13日 | 更新: 2012年2月22日

**版本:** 2.1

此公告摘要列出 2011 年 12 月份所發行之安全性公告。

發行 2011 年 12 月份安全性公告之後，此公告摘要將取代原先於 2011 年 12 月 28 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](https://go.microsoft.com/fwlink/?linkid=217213)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2011 年 12 月 14 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。[立即註冊參加 12 月份安全性公告網路廣播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032487961)。在這個日期後，此網路廣播將可隨選取得。如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](https://go.microsoft.com/fwlink/?linkid=217214) (英文)。

Microsoft 預定於太平洋時間 (美國與加拿大) 2011 年 12 月 29 日下午 1 點，舉辦一場網路廣播，解答客戶對於此不定期安全性公告的問題。[立即註冊參加 12 月 29 日下午 1 點的安全性公告網路廣播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032502798&culture=en-us)。在這個日期後，此網路廣播將可隨選取得。如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](https://go.microsoft.com/fwlink/?linkid=217214) (英文)。

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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=233008">MS11-087</a></td>
<td style="border:1px solid black;"><strong>Windows 核心模式驅動程式中的弱點可能會允許遠端執行程式碼 (2639417)</strong><br />
<br />
此安全性更新可解決 Microsoft Windows 中一項公開揭露的弱點。如果使用者開啟蓄意製作的文件或是造訪內嵌 TrueType 字型檔案的惡意網頁，則此弱點可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232507">MS11-090</a></td>
<td style="border:1px solid black;"><strong>ActiveX Kill Bit (刪除位元) 的積存安全性更新 (2618451)</strong><br />
<br />
此安全性更新可解決 Microsoft 軟體中一項未公開報告的弱點。如果使用者在 Internet Explorer 中檢視蓄意製作而使用特定二進位行為的網頁，這項弱點即可能允許遠端執行程式碼。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。此更新程式同時也包含四個協力廠商 ActiveX 控制項的 Kill Bit (刪除位元)。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232517">MS11-092</a></td>
<td style="border:1px solid black;"><strong>Windows Media 中的弱點</strong> <strong>可能會允許遠端執行程式碼 (2648048)</strong><br />
<br />
這個安全性更新可解決 Windows Media Player 和 Windows Media Center 中一項未公開報告的弱點。若使用者開啟蓄意製作的 Microsoft Digital Video Recording (.dvr-ms) 檔案，此弱點可能會允許遠端執行程式碼。在所有情況下，使用者都不會被迫開啟此檔案。使用者必須受欺騙而開啟此檔案，攻擊才可能成功。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=227070">MS11-088</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office IME</strong> <strong>(中文版) 中的弱點可能會允許權限提高 (2652016)</strong><br />
<br />
這個安全性更新可解決 Microsoft Office IME (中文版) 中一項未公開報告的弱點。如果登入的使用者在系統上執行特定動作，而該系統已安裝受影響的 Microsoft Pinyin (MSPY) 輸入法 (IME) 簡體中文版，則弱點可能會允許權限提高。成功利用此弱點的攻擊者可以在核心模式下執行任意程式碼。接下來，攻擊者就能安裝程式，檢視、變更或刪除資料，或是建立具有完整系統管理權限的新帳戶。只有 Microsoft Pinyin IME 2010 實作會受到這項弱點的影響。其他版本的簡體中文 IME 和其他 IME 實作則不受影響。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=225739">MS11-089</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 中的弱點</strong> <strong>可能會允許遠端執行程式碼 (2590602)</strong><br />
<br />
這個安全性更新可解決 Microsoft Office 中一項未公開報告的弱點。如果使用者開啟蓄意製作的 Word 檔案，此弱點可能會允許遠端執行程式碼。成功利用此弱點的攻擊者可以取得與登入使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=235287">MS11-091</a></td>
<td style="border:1px solid black;"><strong>Microsoft Publisher 中的弱點可能會允許遠端</strong> <strong>執行程式碼 (2607702)</strong><br />
<br />
此安全性更新可解決 Microsoft Office 中一項公開揭露的弱點和三項未公開報告的弱點。其中最嚴重的弱點，可能會在使用者開啟蓄意製作的 Publisher 檔案時，允許遠端執行程式碼。成功利用這些弱點的攻擊者可以取得受影響系統的完整控制權。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232516">MS11-093</a></td>
<td style="border:1px solid black;"><strong>OLE 中的弱點可能會允許遠端執行程式碼 (2624667)</strong><br />
<br />
這個安全性更新可解決所有 Windows XP 和 Windows Server 2003 受支援版本中一項未公開報告的弱點。對於所有受支援版本的 Windows XP 和 Windows Server 2003，此安全性更新的等級為「重要」。Windows Vista、Windows Server 2008、Windows 7 和 Windows Server 2008 R2 不受此弱點影響。<br />
<br />
如果使用者開啟包含蓄意製作的 OLE 物件的檔案，此弱點可能會允許遠端執行程式碼。成功利用此弱點的攻擊者可以取得與本機使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232493">MS11-094</a></td>
<td style="border:1px solid black;"><strong>Microsoft PowerPoint 中的弱點可能會允許遠端執行程式碼 (2639142)</strong><br />
<br />
此安全性更新可解決<strong></strong>Microsoft Office 中兩項未公開報告的弱點。如果使用者開啟蓄意製作的 PowerPoint 檔案，此弱點可能會允許遠端執行程式碼。成功利用上述任一弱點的攻擊者可以取得受影響系統的完整控制權。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232666">MS11-095</a></td>
<td style="border:1px solid black;"><strong>Active Directory 中的弱點可能會允許遠端執行程式碼 (2640045)</strong><br />
<br />
這個安全性更新可解決 Active Directory、Active Directory 應用程式模式 (ADAM) 及 Active Directory 輕量型目錄服務 (AD LDS) 中一個未公開報告的弱點。如果攻擊者登入 Active Directory 網域並執行蓄意製作的應用程式，則此弱點可能會允許遠端執行程式碼。若要利用此弱點，攻擊者必須先取得認證才能登入 Active Directory 網域。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232696">MS11-096</a></td>
<td style="border:1px solid black;"><strong>Microsoft Excel 中的弱點可能會允許遠端執行程式碼 (2640241)</strong><br />
<br />
這個安全性更新可解決 Microsoft Office 中一項未公開報告的弱點。如果使用者開啟蓄意製作的 Excel 檔案，此弱點可能會允許遠端執行程式碼。成功利用此弱點的攻擊者可以取得與登入使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。安裝和設定 Office 檔案驗證 (OFV) 來防止開啟可疑的檔案，可阻止攻擊模式利用 CVE-2011-3403 中說明的弱點。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232663">MS11-097</a></td>
<td style="border:1px solid black;"><strong>Windows Client/Server</strong> <strong>Run-time Subsystem 中的弱點可能會允許權限提高 (2620712)</strong><br />
<br />
這個安全性更新可解決 Microsoft Windows 中一項未公開報告的弱點。如果攻擊者登入受影響的系統並執行蓄意製作的應用程式，以傳送裝置事件訊息至完整性較高的處理序，則此弱點可能會允許權限提高。攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項弱點。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232424">MS11-098</a></td>
<td style="border:1px solid black;"><strong>Windows 核心中的弱點可能會允許權限提高 (2633171)</strong><br />
<br />
這個安全性更新可解決 Microsoft Windows 中一項未公開報告的弱點。如果攻擊者登入受影響的系統，並執行蓄意製作的應用程式來利用弱點，則此弱點可能會允許權限提高。攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項弱點。匿名或遠端使用者無法利用這個弱點。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232505">MS11-099</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer <strong>積存安全性更新</strong> (2618444)</strong><br />
<br />
此安全性更新可解決 Internet Explorer 中三項未公開報告的弱點。如果使用者開啟蓄意製作之動態連結程式庫 (DLL) 檔案所在之相同目錄中的合法超文字標記語言 (HTML) 檔案，則最嚴重的弱點可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232432">MS11-100</a></td>
<td style="border:1px solid black;"><strong>.NET Framework</strong> <strong>中的</strong> <strong>弱點可能會允許</strong> <strong>權限提高</strong> <strong>(2638420)</strong><br />
<br />
此安全性更新可解決 Microsoft .NET Framework 中一項公開揭露的弱點和三項未公開報告的弱點。如果未經驗證的攻擊者將蓄意製作的 Web 要求傳送至目標網站，則最嚴重的弱點可能會允許權限提高。成功利用此弱點的攻擊者，可在現有帳戶於 ASP.NET 網站的內容中執行任意動作，包括執行任意命令。為了利用此弱點，攻擊者必須能在 ASP.NET 網站上登錄帳戶，且必須知道現有的使用者名稱。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、Microsoft .NET Framework</td>
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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=233008">MS11-087</a></td>
<td style="border:1px solid black;">TrueType 字型剖析弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3402">CVE-2011-3402</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">這項弱點已經公開揭露。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=227070">MS11-088</a></td>
<td style="border:1px solid black;">Pinyin IME 權限提高弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2010">CVE-2011-2010</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=225739">MS11-089</a></td>
<td style="border:1px solid black;">Word 釋放後使用弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1983">CVE-2011-1983</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232507">MS11-090</a></td>
<td style="border:1px solid black;">Microsoft Time 遠端執行程式碼弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3397">CVE-2011-3397</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=235287">MS11-091</a></td>
<td style="border:1px solid black;">Publisher 陣列超出範圍索引弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3410">CVE-2011-3410</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=235287">MS11-091</a></td>
<td style="border:1px solid black;">Publisher 無效指標弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3411">CVE-2011-3411</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=235287">MS11-091</a></td>
<td style="border:1px solid black;">Publisher 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3412">CVE-2011-3412</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232517">MS11-092</a></td>
<td style="border:1px solid black;">Windows Media Player DVR-MS 記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3401">CVE-2011-3401</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232516">MS11-093</a></td>
<td style="border:1px solid black;">OLE 內容弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3400">CVE-2011-3400</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232493">MS11-094</a></td>
<td style="border:1px solid black;">PowerPoint 不安全程式庫載入弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3396">CVE-2011-3396</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">只有在未安裝最新版 Service Pack 時，Microsoft PowerPoint 2010 才會受影響。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232493">MS11-094</a></td>
<td style="border:1px solid black;">OfficeArt Shape RCE 弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3413">CVE-2011-3413</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232666">MS11-095</a></td>
<td style="border:1px solid black;">Active Directory 緩衝區溢位弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3406">CVE-2011-3406</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">只有執行 Active Directory、AD LDS 或 ADAM 的系統會受影響。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232696">MS11-096</a></td>
<td style="border:1px solid black;">記錄記憶體損毀弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3403">CVE-2011-3403</a></td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232663">MS11-097</a></td>
<td style="border:1px solid black;">CSRSS 本機權限提高弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3408">CVE-2011-3408</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232424">MS11-098</a></td>
<td style="border:1px solid black;">Windows 核心例外處理常式弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2018">CVE-2011-2018</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232505">MS11-099</a></td>
<td style="border:1px solid black;">XSS 篩選器資訊洩漏弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1992">CVE-2011-1992</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">這是一個資訊洩漏的弱點。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232505">MS11-099</a></td>
<td style="border:1px solid black;">Internet Explorer 不安全程式庫載入弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2019">CVE-2011-2019</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不受影響</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">(無)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232432">MS11-100</a></td>
<td style="border:1px solid black;">HashTable 中的碰撞可能會導致 DoS 弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3414">CVE-2011-3414</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">3</a> - 不太可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">暫時</td>
<td style="border:1px solid black;">此弱點只是一項拒絕服務，並已經公開揭露。
<div>
  
</div>
<div>
<a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">拒絕服務弱點將收到等級 &quot;3&quot; 的弱點入侵指數。</a>
</div></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232432">MS11-100</a></td>
<td style="border:1px solid black;">ASP.Net 表單驗證略過弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3416">CVE-2011-3416</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">1</a> - 可能撰寫出可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">權限提高 - 帳戶接管</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232432">MS11-100</a></td>
<td style="border:1px solid black;">ASP.NET 表單驗證票證快取弱點</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3417">CVE-2011-3417</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/cc998259.aspx">2</a> - 很難建立可利用此漏洞的程式碼</td>
<td style="border:1px solid black;">不適用</td>
<td style="border:1px solid black;">權限提高 - 帳戶接管</td>
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
  
**表 1**

 
<p> </p>
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
[**MS11-087**](https://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[**MS11-090**](https://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[**MS11-092**](https://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[**MS11-093**](https://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[**MS11-095**](https://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[**MS11-097**](https://go.microsoft.com/fwlink/?linkid=232663)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
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
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=b01bb041-005c-48c4-a606-66aa264ba0fa)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=21b4b999-2dbf-4921-80bd-cc7ab2cd1190)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=d85091b5-69bb-4d0f-839a-a65cd94e2887)  
(KB2619339)  
(重大)  
[Windows XP Media Center Edition 2005 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=03bc6446-7cf3-47c4-8ed1-a53a4d53a429)  
(KB2619340)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=73531165-f299-4b62-b738-52fca410eaae)  
(重要)
</td>
<td style="border:1px solid black;">
[Active Directory 應用程式模式 (ADAM)](https://www.microsoft.com/download/details.aspx?familyid=3b816964-d3c3-4f05-94c3-f54a6f54ca73)  
(KB2626416)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=edb594a4-14d2-4ffe-8d1c-2c283689fe8c)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0a872cd2-5f4d-400c-a1c4-a2d194746fb6)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=126e8092-980d-471a-867d-d5939671b7df)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7d1d1e9a-603c-4895-a69f-b61186a75ad5)  
(KB2619339)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a98bb7cf-9939-4927-8d21-ccb3845e7cb7)  
(重要)
</td>
<td style="border:1px solid black;">
[Active Directory 應用程式模式 (ADAM)](https://www.microsoft.com/download/details.aspx?familyid=986f0087-c674-4060-8710-af3496adbfdd)  
(KB2626416)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9e1273e2-7775-40b4-b939-ab530677cd4a)  
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
[**MS11-087**](https://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[**MS11-090**](https://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[**MS11-092**](https://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[**MS11-093**](https://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[**MS11-095**](https://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[**MS11-097**](https://go.microsoft.com/fwlink/?linkid=232663)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總** **嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e84e6964-1580-41ef-9d3e-4d0c3ad4cb69)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=dfb948c5-8aee-4bcd-babf-3564b78712dd)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6b555040-1117-4b06-a48c-02f0e1b686d8)  
(重要)
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=01caf06f-777d-4ea8-95ca-e11d60a973ad)  
(KB2621146)  
(重要)  
[Active Directory 應用程式模式 (ADAM)](https://www.microsoft.com/download/details.aspx?familyid=6f7c7ccd-22a3-4fbc-bf21-bd0e42ab1da5)  
(KB2626416)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a14057e5-e2c2-4dde-8d26-542a9f162e98)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9d9f3667-3fd6-4948-83db-282783599f41)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2d37a8cb-2316-4db4-980c-11b6dcbdc696)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=eb17782c-f754-42ab-905b-6f141df008c3)  
(重要)
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=e1ba50cf-fc6b-4668-b71c-e9f75a8ac638)  
(KB2621146)  
(重要)  
[Active Directory 應用程式模式 (ADAM)](https://www.microsoft.com/download/details.aspx?familyid=1b610eb3-456c-4125-94b7-1ead4face8e3)  
(KB2626416)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7f595fd6-bdfd-4075-97e5-70efb7d49dff)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=1ecf72cd-6732-4cf3-aa22-8caf15ea633e)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=7726ddbe-0578-44fb-a40f-49b804a45989)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=4cdde8a9-6d44-41fa-82c0-a25404cdfbb5)  
(重要)
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=74099261-60ad-4c68-906c-60e131818955)  
(KB2621146)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=147ec6d3-3401-4aa3-a409-55346bcc7bd7)  
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
[**MS11-087**](https://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[**MS11-090**](https://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[**MS11-092**](https://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[**MS11-093**](https://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[**MS11-095**](https://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[**MS11-097**](https://go.microsoft.com/fwlink/?linkid=232663)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7f69ec9d-43ad-4106-90ef-c191e7ec43af)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1dd069a2-fb1a-4f31-88cc-bc031c3e2c80)  
(無嚴重性等級<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e9130fad-de8c-4be0-aea1-62cbaa310b76)  
(KB2619339)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Active Directory 輕量型目錄服務 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=470da512-2c8b-4ba9-b7bb-b9e6c45cd33f)  
(KB2621146)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=fa6e6d91-4aca-49a6-a6e8-c33ec413097e)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ae1f1f86-6f13-4e1e-9f93-4f70b6c9927e)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=60fd5bf6-e820-44f6-8081-b98c0103acc1)  
(無嚴重性等級<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b7c4bf05-eb2d-48ac-a6df-8afd88e811d8)  
(KB2619339)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Active Directory 輕量型目錄服務 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=8daf9a49-60cb-4813-ac7a-e9a4bf296889)  
(KB2621146)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c9794756-803d-48ba-86db-350fb577f01b)  
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
[**MS11-087**](https://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[**MS11-090**](https://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[**MS11-092**](https://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[**MS11-093**](https://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[**MS11-095**](https://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[**MS11-097**](https://go.microsoft.com/fwlink/?linkid=232663)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
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
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c4ba344d-dd0d-4cfb-81d9-d364d7f37e25)\*\*\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f485d4c3-a4af-4ae6-9404-e79afcbb4f6e)\*\*  
(無嚴重性等級<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Active Directory 和 Active Directory 輕量型目錄服務 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=6f9ddcdb-a471-4e00-a697-92a24e4ea8d4)\*  
(KB2621146)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6f934885-b134-400c-a452-50fd4eeedd5e)\*  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=058963f6-9654-41d0-86d2-f25a0c2ad416)\*\*\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=28598ef6-13fb-44fd-8c76-599af7b0a01d)\*\*  
(無嚴重性等級<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Active Directory 和 Active Directory 輕量型目錄服務 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=5253477b-422f-404a-941e-8b69da5a2670)\*  
(KB2621146)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7ade3832-bc20-4fce-8eac-8a3d072d2f1c)\*  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=42cd1c33-11a7-4a29-ae85-f7272a626f91)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5915e19c-b576-453b-b621-5737774f5955)  
(無嚴重性等級<sup>[1]</sup>)
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
[適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4bd7a02b-c6d8-4eb5-a46d-e494a1233dc8)  
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
[**MS11-087**](https://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[**MS11-090**](https://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[**MS11-092**](https://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[**MS11-093**](https://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[**MS11-095**](https://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[**MS11-097**](https://go.microsoft.com/fwlink/?linkid=232663)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)
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
適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=0526727a-f2fb-4846-9b04-f1899f52f1f6)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=d112623c-86ce-434a-8fe1-ec3e3e632763)  
(無嚴重性等級<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b6e44069-dec5-48f6-8fc4-8ab375a10b4e)  
(KB2619339)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Active Directory 輕量型目錄服務 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=d2e87199-6469-4bc0-a721-f43e817e4344)  
(KB2621146)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=0666bdf5-9eed-44c9-84ee-b45f9b3e14b3)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=cfd42c42-1595-419a-bf04-b23b64663629)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=81114ecd-0c73-4ca6-8a66-09c6c636a5db)  
(無嚴重性等級<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=f7997ab8-27e0-4714-845a-d237f4326587)  
(KB2619339)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Active Directory 輕量型目錄服務 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=ba8d7aa9-8299-49a3-b0c0-b8b5eab48434)  
(KB2621146)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=620f94f9-1f61-45a0-a22e-e7510b56b9b8)  
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
[**MS11-087**](https://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[**MS11-090**](https://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[**MS11-092**](https://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[**MS11-093**](https://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[**MS11-095**](https://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[**MS11-097**](https://go.microsoft.com/fwlink/?linkid=232663)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
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
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=d64a31ca-cccd-488a-98fd-c059b9e9e1ea)\*\*\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=bc018647-08cb-431a-8e7c-5dc04980eaa9)\*\*  
(無嚴重性等級<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Active Directory 和 Active Directory 輕量型目錄服務 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=a3e0d27c-8b29-4981-bdef-bcd037fd3408)\*  
(KB2621146)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=04878e9a-539a-4549-a5af-11d45add91da)\*  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 和適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2 和適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b46f6da7-6d24-4262-8e55-3b657db39813)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2 和適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=9323b9b9-e9b0-4941-afe0-196d22df9ab4)  
(無嚴重性等級<sup>[1]</sup>)
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
[適用於 Itanium 型系統的 Windows Server 2008 R2 和適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5b2ebec4-cebb-47b6-864a-12d59a9a3e18)  
(重要)
</td>
</tr>
</table>
 
**Windows Server 2008 和 Windows Server 2008 R2 注意事項**

**\*Server Core 安裝會受影響。**無論上述受支援的 Windows Server 2008 或 Windows Server 2008 R2 版本是否使用 Server Core 安裝選項安裝，這個更新均以相同的嚴重性等級套用。如需此安裝選項的詳細資訊，請參閱 TechNet 文章：[管理 Server Core 安裝](https://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (英文) 和[維護 Server Core 安裝](https://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 和 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**\*\*Server Core 安裝不受影響。**如果 Windows Server 2008 或 Windows Server 2008 R2 是使用 Server Core 安裝選項所安裝，則這項更新解決的弱點並不會影響受支援的 Windows Server 2008 或 Windows Server 2008 R2。如需此安裝選項的詳細資訊，請參閱 TechNet 文章：[管理 Server Core 安裝](https://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (英文) 和[維護 Server Core 安裝](https://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 和 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**\*\*\*\*Server Core 安裝會受影響。**這項更新適用於上述受支援的 Windows Server 2008 或 Windows Server 2008 R2 版本 (當使用 Server Core 安裝選項安裝時)，且嚴重性等級較低。如需此安裝選項的詳細資訊，請參閱 TechNet 文章：[管理 Server Core 安裝](https://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (英文) 和[維護 Server Core 安裝](https://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 和 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**MS11-090** 注意事項

<sup>[1]</sup> 這個特定的作業系統不受本公告所描述的弱點影響。可用的更新程式會設定協力廠商控制項的 Kill Bit (刪除位元)。

**表 2**

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="4">
Windows XP
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-098**](https://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[**MS11-099**](https://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[**MS11-100**](https://go.microsoft.com/fwlink/?linkid=232432)
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
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=7a6fcf8d-8c7b-4882-90d3-02db79a75238)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=caa9360b-2fd8-4f46-99e6-2decf1b60ca7)  
(中度)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=dc6dcd8c-c39f-4c4b-b5b2-b4c18c36973b)  
(中度)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=f3906245-b6f6-464a-84b6-e1b6b195df95)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2)  
(KB2656352)  
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
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
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=2fa77733-70f5-46ff-9cfe-2262d292b870)  
(中度)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=a0c55d9b-8529-4d3d-910d-1a822a825be2)  
(中度)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=3e60e996-8850-4d25-b994-39646e2cc25e)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2)  
(KB2656352)  
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-098**](https://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[**MS11-099**](https://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[**MS11-100**](https://go.microsoft.com/fwlink/?linkid=232432)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性** **等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**低**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=281e5bd4-4582-4aa9-af88-518ad3152132)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=759041cf-fd8b-4e04-b289-d74112bf978b)  
(無嚴重性等級<sup>[1]</sup>)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=b1b4af92-3ff1-4727-9ba3-52764a7b81bb)  
(無嚴重性等級<sup>[1]</sup>)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=1cbe9469-05f4-4305-bbfd-76b4a04cd598)  
(輕微)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=7538762a-50e9-4f13-a60e-ff99aa8fbbf8)  
(KB2656358)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2)  
(KB2656352)  
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=5587eca8-86e9-4a63-81cb-81f68178a6c0)  
(無嚴重性等級<sup>[1]</sup>)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=7a87f890-f106-41ab-bc53-4ca44dc99cb1)  
(無嚴重性等級<sup>[1]</sup>)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=a42fa727-482c-4578-9a30-61fdf14ed4da)  
(輕微)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2)  
(KB2656352)  
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=02d5c057-d551-411b-917b-43d7795111bc)  
(無嚴重性等級<sup>[1]</sup>)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=2fccb214-6c79-4ef6-9d6e-df4f16ef792e)  
(無嚴重性等級<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2)  
(KB2656352)  
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr>
<th colspan="4">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-098**](https://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[**MS11-099**](https://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[**MS11-100**](https://go.microsoft.com/fwlink/?linkid=232432)
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
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a6c7c960-768d-40d4-8fe5-7d59f48ead1d)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=0adc422f-73f2-46ee-973f-9b7603a76d1e)  
(中度)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=4327147b-0481-4172-a835-8786abc50596)  
(重要)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=a0b19b35-1d48-4419-ba3d-66063cc472a7)  
(中度)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=49050cf2-949a-40e5-b2ee-6257a3837294)  
(KB2656362)  
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
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
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=8a3f2351-380b-4566-b186-906dca426d39)  
(中度)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=987f0966-01de-4edf-a0d6-4032d1d72966)  
(重要)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=c951044b-4596-462f-bc8f-bdd9d6734297)  
(中度)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=49050cf2-949a-40e5-b2ee-6257a3837294)  
(KB2656362)  
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-098**](https://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[**MS11-099**](https://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[**MS11-100**](https://go.microsoft.com/fwlink/?linkid=232432)
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
[**低**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5a4443f8-fec8-42be-ad67-8475920f1460)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=eaf587f0-9951-4480-a08b-377e61aaf72b)\*\*  
(無嚴重性等級<sup>[1]</sup>)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=8f5af52f-dece-4f0c-9fc0-d4973e4f7b1a)\*\*  
(輕微)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=c03e65d6-4f92-4bc1-94b5-2f0183d0133e)\*\*  
(無嚴重性等級<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)\*\*  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=49050cf2-949a-40e5-b2ee-6257a3837294)\*\*  
(KB2656362)  
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)\*\*  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)\*\*<sup>[1]</sup>
(KB2656351)
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
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=2f18fc98-984a-4c02-951f-b8438a9e4f6b)\*\*  
(無嚴重性等級<sup>[1]</sup>)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=808d26f7-c8fa-446d-9d2f-e8c0babb0c4a)\*\*  
(輕微)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=b7a582f3-0a18-4fbf-9b99-21c664bfd979)\*\*  
(無嚴重性等級<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)\*\*  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=49050cf2-949a-40e5-b2ee-6257a3837294)\*\*  
(KB2656362)  
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)\*\*  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)\*\*<sup>[1]</sup>
(KB2656351)
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
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=fc62df39-7185-448b-b356-25a5a07886ec)  
(無嚴重性等級<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=49050cf2-949a-40e5-b2ee-6257a3837294)  
(KB2656362)  
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr>
<th colspan="4">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-098**](https://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[**MS11-099**](https://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[**MS11-100**](https://go.microsoft.com/fwlink/?linkid=232432)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總** **嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=eb2bd108-5ef1-45be-9157-e7cbfc8afd2a)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=018610bb-e80a-432a-8f32-f50451f71ad9)  
(重要)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=ec2046a6-f069-4f02-9600-7640e57be0a3)  
(重要)
</td>
<td style="border:1px solid black;">
僅適用於 32 位元系統的 Windows 7：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=2de28d32-1efd-4177-82e6-19a08266096c)  
(KB2656355)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)  
僅適用於 32 位元系統的 Windows 7 Service Pack 1：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=26e0b56d-9228-49cf-9276-0741257567a9)  
(KB2656356)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)

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
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=dbe85b05-e252-4029-8e25-f2452db1c017)  
(重要)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=4c773b3d-0ca3-4b9b-af9a-9d6edcd261f7)  
(重要)
</td>
<td style="border:1px solid black;">
僅適用於 x64 型系統的 Windows 7：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=2de28d32-1efd-4177-82e6-19a08266096c)  
(KB2656355)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)  
僅適用於 x64 型系統的 Windows 7 Service Pack 1：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=26e0b56d-9228-49cf-9276-0741257567a9)  
(KB2656356)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-098**](https://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[**MS11-099**](https://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[**MS11-100**](https://go.microsoft.com/fwlink/?linkid=232432)
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
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=2108b4ef-942f-4727-a1fc-ee7d0abb427c)\*\*  
(輕微)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=72c1654e-526f-4ece-b7ad-767a0710e076)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
僅適用於 x64 型系統的 Windows Server 2008 R2：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=2de28d32-1efd-4177-82e6-19a08266096c)\*  
(KB2656355)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)  
僅適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=26e0b56d-9228-49cf-9276-0741257567a9)\*  
(KB2656356)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)\*<sup>[1]</sup>
(KB2656351)
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
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=74614510-e13c-43e8-90e7-d81e63895cf2)  
(輕微)
</td>
<td style="border:1px solid black;">
僅適用於 Itanium 型系統的 Windows Server 2008 R2：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=2de28d32-1efd-4177-82e6-19a08266096c)  
(KB2656355)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)  
僅適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=26e0b56d-9228-49cf-9276-0741257567a9)  
(KB2656356)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
</table>
 
**Windows Server 2008 和 Windows Server 2008 R2 注意事項**

**\*Server Core 安裝會受影響。**無論上述受支援的 Windows Server 2008 或 Windows Server 2008 R2 版本是否使用 Server Core 安裝選項安裝，這個更新均以相同的嚴重性等級套用。如需此安裝選項的詳細資訊，請參閱 TechNet 文章：[管理 Server Core 安裝](https://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (英文) 和[維護 Server Core 安裝](https://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 和 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**\*\*Server Core 安裝不受影響。**如果 Windows Server 2008 或 Windows Server 2008 R2 是使用 Server Core 安裝選項所安裝，則這項更新解決的弱點並不會影響受支援的 Windows Server 2008 或 Windows Server 2008 R2。如需此安裝選項的詳細資訊，請參閱 TechNet 文章：[管理 Server Core 安裝](https://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (英文) 和[維護 Server Core 安裝](https://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 和 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**MS11-099 注意事項**

<sup>[1]</sup>嚴重性等級不適用此指定軟體的更新，因為在預設設定中會封鎖此公告討論之弱點的已知攻擊行為。不過，Microsoft 仍建議此軟體的客戶套用此安全性更新，以做為深度防禦措施。

**MS11-100** **注意事項**

<sup>[1]</sup>**.NET Framework 4 和 .NET Framework 4 Client Profile 會受到影響。**可在兩個設定檔中使用 .NET Framework 第 4 版可轉散發套件： .NET Framework 4 和 .NET Framework 4 Client Profile。.NET Framework 4 Client Profile 是 .NET Framework 4 的子集。此更新所解決的弱點會同時影響到 .NET Framework 4 和 .NET Framework 4 Client Profile。如需詳細資訊，請參閱 MSDN 文章：[安裝 .NET Framework](https://msdn.microsoft.com/zh-tw/library/5a4x27ek.aspx)。

#### Microsoft Office 套件及軟體

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="6">
Microsoft Office 套件和元件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-088**](https://go.microsoft.com/fwlink/?linkid=227070)
</td>
<td style="border:1px solid black;">
[**MS11-089**](https://go.microsoft.com/fwlink/?linkid=225739)
</td>
<td style="border:1px solid black;">
[**MS11-091**](https://go.microsoft.com/fwlink/?linkid=235287)
</td>
<td style="border:1px solid black;">
[**MS11-094**](https://go.microsoft.com/fwlink/?linkid=232493)
</td>
<td style="border:1px solid black;">
[**MS11-096**](https://go.microsoft.com/fwlink/?linkid=232696)
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
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=13f3e884-37bf-4ed2-b3ed-a0e7fb48e44f)  
(KB2553084)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=5859014f-afc5-4958-82ea-6ba45a5ad4b3)  
(KB2596954)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2 和 Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 2 和 Microsoft Office 2007 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=e924cd85-5764-4056-bd32-b0e57dc25146)  
(KB2596785)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2007 Service Pack 2 和 Microsoft Publisher 2007 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=2856821e-f1fd-424b-b03c-e443685eea6d)  
(KB2596705)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d0c3156c-c87c-4d3e-aca2-3fab9ff78711)  
(KB2596764)  
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
[Microsoft Pinyin IME 2010 (32 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=d812621e-c35a-4cb0-ba26-928363f3422d)  
(KB2596511)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 和 Microsoft Office 2010 Service Pack 1 (32 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=e47c0694-a9a5-4dd7-bfba-e470d9855c28)  
(KB2589320)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2010 (32 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=fd32d083-46e7-4835-ba83-c33332b920bd)  
(KB2553185)  
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
[Microsoft Pinyin IME 2010 (64 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=c8d3ac17-5aca-4da3-961f-b753be4a3634)  
(KB2596511)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 和 Microsoft Office 2010 Service Pack 1 (64 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=6c2d5273-eef9-4ff6-be6f-8d86f417f004)  
(KB2589320)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2010 (64 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=f28b8cf6-8946-448a-ae4e-d11f8a76a679)  
(KB2553185)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="6">
Microsoft Office for Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-088**](https://go.microsoft.com/fwlink/?linkid=227070)
</td>
<td style="border:1px solid black;">
[**MS11-089**](https://go.microsoft.com/fwlink/?linkid=225739)
</td>
<td style="border:1px solid black;">
[**MS11-091**](https://go.microsoft.com/fwlink/?linkid=235287)
</td>
<td style="border:1px solid black;">
[**MS11-094**](https://go.microsoft.com/fwlink/?linkid=232493)
</td>
<td style="border:1px solid black;">
[**MS11-096**](https://go.microsoft.com/fwlink/?linkid=232696)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總** **嚴重性等級**
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
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
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
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=ef3b559c-0bd2-45dd-8049-6946f6431a2a)  
(KB2644358)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
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
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=2c4d0381-f7ab-49ed-a0c0-b381387d1e68)  
(KB2644354)  
(重要)
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
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](https://www.microsoft.com/download/details.aspx?familyid=3c8017d6-232c-42a6-a133-96efe3ad3385)  
(KB2644347)  
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
<th colspan="6">
其他 Microsoft Office 軟體
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-088**](https://go.microsoft.com/fwlink/?linkid=227070)
</td>
<td style="border:1px solid black;">
[**MS11-089**](https://go.microsoft.com/fwlink/?linkid=225739)
</td>
<td style="border:1px solid black;">
[**MS11-091**](https://go.microsoft.com/fwlink/?linkid=235287)
</td>
<td style="border:1px solid black;">
[**MS11-094**](https://go.microsoft.com/fwlink/?linkid=232493)
</td>
<td style="border:1px solid black;">
[**MS11-096**](https://go.microsoft.com/fwlink/?linkid=232696)
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
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer 2007 Service Pack 2
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
[Microsoft PowerPoint Viewer 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4417592a-8db0-4e35-9895-d589bc341077)  
(KB2596912)  
(重要)
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
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office Word、Excel 及 PowerPoint 2007 檔案格式相容性套件 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e799f654-7e2d-40c7-a3b8-32e44d1aa6ee)  
(KB2596843)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Pinyin SimpleFast Style 2010 和 Microsoft Office Pinyin New Experience Style 2010 (32 位元版本)
</td>
<td style="border:1px solid black;">
Microsoft Office Pinyin SimpleFast Style 2010 和 Microsoft Office Pinyin New Experience Style 2010 (32 位元版本)<sup>[1]</sup>
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
<td style="border:1px solid black;">
Microsoft Office Pinyin SimpleFast Style 2010 和 Microsoft Office Pinyin New Experience Style 2010 (64 位元版本)
</td>
<td style="border:1px solid black;">
Microsoft Office Pinyin SimpleFast Style 2010 和 Microsoft Office Pinyin New Experience Style 2010 (64 位元版本)<sup>[1]</sup>
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
</table>
 
**MS11-088 注意事項**

<sup>[1]</sup>對此版本 Microsoft Office Pinyin 的支援已停止。

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和安全性更新。如需更多資訊，請參閱 [TechNet 更新管理中心](https://go.microsoft.com/fwlink/?linkid=69903) (英文)。[TechNet 資訊安全技術中心](https://go.microsoft.com/fwlink/?linkid=21171)提供 Microsoft 產品安全性的其他資訊。消費者可以造訪[在家上網的安全性](https://go.microsoft.com/fwlink/?linkid=85102)網站，只要按一下 \[最新安全性更新\] 即可在此網站取得此資訊。

安全性更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 以及 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 取得。安全性更新也可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得。您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。

對於 Microsoft Office for Mac 的客戶，Microsoft AutoUpdate for Mac 可協助您保持最新的 Microsoft 軟體。如需使用 Microsoft AutoUpdate for Mac 的詳細資訊，請參閱[自動檢查軟體更新](https://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea) (英文)。

最後，您可以從 [Microsoft Update Catalog](https://go.microsoft.com/fwlink/?linkid=96155) 下載安全性更新。Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括安全性更新、驅動程式和 Service Pack。只要以安全性公告編號 (例如：MS07-036) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](https://go.microsoft.com/fwlink/?linkid=97900)。

**偵測與部署指南**

Microsoft 針對安全性更新提供偵測和部署指南。本指南所含之建議和資訊，能幫助 IT 專業人員瞭解如何使用用於安全性更新的偵測和部署的各種工具。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 961747](https://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少安全性更新以及一般安全性設定錯誤的狀況。如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速而可靠地將 Microsoft Windows 2000 作業系統及更新版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 適用的最新重大更新與安全性更新部署到 Microsoft Windows 2000 及更新版本的作業系統中。

如需更多關於利用 Windows Server Update Services 部署安全性更新的資訊，請造訪 [Windows Server Update Services](https://technet.microsoft.com/en-us/wsus/default.aspx) (英文)。

**System Center Configuration Manager 2007**

Configuration Manager 2007 軟體更新管理可簡化遞送和管理企業中 IT 系統更新的繁複作業。IT 系統管理員可以使用 Configuration Manager 2007 遞送 Microsoft 產品更新給各種裝置，包括桌上型電腦、筆記型電腦、伺服器及行動裝置。

Configuration Manager 2007 中的自動弱點評估會找出更新需求並報告建議動作。Configuration Manager 2007 中的軟體更新管理是建置在 Microsoft Windows Software Update Services (WSUS) 上，經過時間考驗，為全球 IT 系統管理員所熟悉的更新基礎架構。如需更多有關系統管理員如何使用 Configuration Manager 2007 來部署更新的資訊，請參閱[軟體更新管理](https://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx) (英文)。如需更多有關 Configuration Manager 的資訊，請造訪 [System Center Configuration Manager](https://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx)。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。

**注意：**System Management Server 2003 自 2010 年 1 月 12 日起不受主流支援。如需更多有關產品生命週期的資訊，請造訪 [Microsoft 支援週期](https://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle)。現已推出新版的 SMS：System Center Configuration Manager 2007；請參閱前段的＜System Center Configuration Manager 2007＞一節。

如需更多有關系統管理員如何使用 SMS 2003 來部署安全性更新的資訊，請參閱 [Microsoft Systems Management Server 2003 的案例與程序： 軟體發佈和補充程式管理](https://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en) (英文)。如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server 技術中心 (TechCenter)](https://technet.microsoft.com/zh-tw/systemcenter/bb545936.aspx)。

**注意** ：SMS 使用 Microsoft Baseline Security Analyzer 提供廣泛的安全性公告更新偵測與部署支援。不過這些工具可能無法偵測部分的軟體更新。在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](https://go.microsoft.com/fwlink/?linkid=33341) (英文)。某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。系統管理員可使用 Elevated Rights Deployment Tool (隨附於 [SMS 2003 Administration Feature Pack](https://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)) 來安裝這些更新。

**Update Compatibility Evaluator 和 Application Compatibility Toolkit**

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

為了增強客戶的安全性保護，Microsoft 將在每月發行安全性更新之前，提前向重要安全性軟體提供者提供弱點資訊。安全性軟體提供者可利用此弱點資訊，透過其安全性軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有安全性軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](https://go.microsoft.com/fwlink/?linkid=215201) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 安全性策略與社群

**更新程式管理策略**

[更新管理安全性指南](https://go.microsoft.com/fwlink/?linkid=21168) (英文) 提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   消費性平台的更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](https://support.microsoft.com/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員安全性社群](https://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](https://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 Symantec 和 Laboratory of Cryptography and System Security (CrySyS) 與我們合作解決 MS11-087 中描述的一個問題
-   感謝 Yang Yanbei 回報 MS11-088 中描述的一個問題
-   感謝 Nikita Tarakanov (CISS Research Team) 和 Alexey Sintsov (Digital Security Research Group) 與 [TippingPoint](https://www.tippingpoint.com/) 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作，回報 MS11-089 中描述的一個問題
-   感謝匿名的研究人員與 [VeriSign iDefense Labs](https://labs.idefense.com) 合作回報 MS11-090 中描述的一個問題
-   感謝 [CERT/CC](https://www.cert.org/) 的 Will Dormann 回報 MS11-091 中描述的三個問題
-   感謝匿名的研究人員與 [VeriSign iDefense Labs](https://labs.idefense.com) 合作回報 MS11-092 中描述的一個問題
-   感謝匿名的研究人員與 [VeriSign iDefense Labs](https://labs.idefense.com) 合作回報 MS11-093 中描述的一個問題
-   感謝 [iSIGHT Partners Labs](https://www.isightpartners.com/) 的 Greg MacManus 回報 MS11-094 中描述的一個問題
-   感謝匿名的研究人員與 [TippingPoint](https://www.tippingpoint.com/) 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 MS11-094 中描述的一個問題
-   感謝匿名的研究人員與 [VeriSign iDefense Labs](https://labs.idefense.com) 合作回報 MS11-096 中描述的一個問題
-   感謝 Winsider Seminars & Solutions Inc. 的 Alex Ionescu 回報 MS11-097 中描述的一個問題
-   感謝 Matthew Jurczyk 與 [VeriSign iDefense Labs](https://labs.idefense.com/) 合作，回報 MS11-098 中描述的一個問題
-   感謝 Thomas Stehle 回報 MS11-099 中描述的一個問題
-   感謝 [Citrix Security Team](https://www.citrix.com) 的 Andy Cooper 回報 MS11-099 中描述的一個問題
-   感謝 [Google Inc.](https://www.google.com/) 的 [Robert Swiecki](https://www.swiecki.net/) 回報 MS11-099 中描述的一個問題
-   感謝 [Yosuke Hasegawa](https://utf-8.jp/) 協助我們解決 MS11-099 中描述的一個問題
-   感謝 [Jan Schejbal](https://janschejbal.wordpress.com/) 協助我們解決 MS11-099 中所含之深度防禦變更的問題
-   感謝 [Seeker](https://www.seekersec.com) 的 Irene Abezgauz 回報 MS11-100 中描述的一個問題
-   感謝 [SEC Consult](https://www.sec-consult.com/) 的 Kestutis Gudinavicius 回報 MS11-100 中描述的一個問題
-   感謝 [LBi](https://www.lbi.com/) 的 Oliver Dewdney 回報 MS11-100 中描述的一個問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 支援週期](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可洽詢[安全性支援](https://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY (1-866-727-2338) 以取得技術支援。與安全性更新有關的支援電話不另外收費。如需更多可用支援選項的資訊，請參閱 [Microsoft 技術支援](https://support.microsoft.com/)。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。與安全性更新有關的支援電話不另外收費。如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[國際化支援](https://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2011 年 12 月 13 日)： 公告摘要發行。
-   V1.1 (2011 年 12 月 13 日)： 針對 MS11-099，更正「受影響的軟體」表格中的嚴重性等級。針對 MS11-088，更正弱點索引中的「主要重點」。這些只是資訊的變更。安全性更新檔案或偵測邏輯沒有變更。
-   V2.0 (2011 年 12 月 29 日)： 新增 Microsoft 安全性公告 MS11-100：.NET Framework 中的弱點可能會允許權限提高 (2638420)。另外還新增此不定期安全性公告的公告網路廣播連結。
-   V2.1 (2011 年 2 月 22 日)： 針對 MS11-088，說明 Microsoft Office Pinyin SimpleFast Style 2010 和 Microsoft Office Pinyin New Experience Style 2010 的產品支援狀態。這兩個版本的 Microsoft Office Pinyin 已不再獲得支援。請參閱公告內容以瞭解詳細資訊。

*Built at 2014-04-18T01:50:00Z-07:00*
