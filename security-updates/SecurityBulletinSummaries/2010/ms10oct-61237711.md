---
TOCTitle: 'MS10-OCT'
Title: 2010 年 10 月份 Microsoft 安全性公告摘要
ms:assetid: 'ms10-oct'
ms:contentKeyID: 61237711
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms10-oct(v=Security.10)'
---

Security Bulletin Summary

2010 年 10 月份 Microsoft 安全性公告摘要
========================================

發行: 2010年10月12日 | 更新: 2011年10月26日

**版本:** 4.1

本公告摘要列出 2010 年 10 月份所發行之安全性公告。

發行 2010 年 10 月份公告之後，此公告摘要將取代原先於 2010 年 10 月 7 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](http://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2010 年 10 月 13 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。[立即註冊參加 10 月份安全性公告網路廣播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032454437&culture=zh-tw)。在這個日期後，此網路廣播將可隨選取得。如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](http://technet.microsoft.com/security/bulletin/summary) (英文)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性、高優先順序更新的優先順序，其中這些非安全性、高優先順序更新的發行日期與每月安全性更新的發行日期相同。請參閱＜其他資訊＞一節。

### 公告資訊

提要
----

<span></span>
下表依嚴重性摘要說明本月份安全性公告。

如需受影響的軟體之詳細資料，請參閱下節＜受影響的軟體及下載位置＞。

 
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
<th style="border:1px solid black;" >最高的嚴重性等級與弱點影響</th>
<th style="border:1px solid black;" >重新開機需求</th>
<th style="border:1px solid black;" >受影響的軟體</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=202013">MS10-071</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 積存安全性更新 (2360131)</strong><br />
<br />
這個安全性更新可解決 Internet Explorer 中七項未公開報告的弱點，以及三項公開揭露的弱點。最嚴重的弱點可能會在使用者以 Internet Explorer 檢視蓄意製作的網頁時，允許遠端執行程式碼。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=201722">MS10-075</a></td>
<td style="border:1px solid black;"><strong>Media Player 網路共用服務中的弱點可能會允許遠端執行程式碼 (2281679)</strong><br />
<br />
此安全性更新可解決 Microsoft Windows Media Player 網路共用服務中一項未公開報告的弱點。如果攻擊者傳送蓄意製作的 RTSP 封包到受影響的系統，則此弱點可能會允許遠端執行程式碼。不過，根據預設，家用媒體的網際網路存取為停用。在這樣的預設設定中，只有相同子網路中的攻擊者能夠利用此弱點。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=194560">MS10-076</a></td>
<td style="border:1px solid black;"><strong>內嵌 OpenType 字型引擎弱點可能允許遠端執行程式碼 (982132)</strong><br />
<br />
本安全性更新解決 Microsoft Windows 元件「內嵌 OpenType (EOT) 字型引擎」中，一項未公開報告的弱點。此弱點可能會允許遠端執行程式碼。成功利用此弱點的攻擊者可以從遠端取得受影響系統的完整控制權。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=201704">MS10-077</a></td>
<td style="border:1px solid black;"><strong>.NET Framework 中的弱點</strong> <strong>可能會允許遠端執行程式碼 (2160841)</strong><br />
<br />
這個安全性更新可解決 Microsoft .NET Framework 中一項未公開報告的弱點。如果使用者使用可執行 XAML 瀏覽器應用程式 (XBAP) 的網頁瀏覽器檢視蓄意製作的網頁，此弱點就可能允許在用戶端系統上遠端執行程式碼。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。如果伺服器允許處理 ASP.NET 網頁，且攻擊者將蓄意製作的 ASP.NET 網頁成功上傳到執行 IIS 的伺服器系統並加以執行，則這些弱點也可能會允許在該伺服器系統上遠端執行程式碼 (網站代管可能會發生這種情況)。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=202016">MS10-072</a></td>
<td style="border:1px solid black;"><strong>SafeHTML 的弱點可能會導致資訊洩漏 (2412048)</strong><br />
<br />
此安全性更新可解決 Microsoft SharePoint 和 Windows SharePoint Services 中一項公開揭露的弱點和一項未公開報告的弱點。如果攻擊者使用 SafeHTML 將蓄意製作的指令碼提交至目標網站，這些弱點會允許資訊洩漏。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
資訊洩漏</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft 伺服器軟體</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=201093">MS10-073</a></td>
<td style="border:1px solid black;"><strong>Windows 核心模式</strong> <strong>驅動程式的弱點可能會允許權限提高 (981957)</strong><br />
<br />
此安全性更新可解決 Windows 核心模式驅動程式中數項公開揭露的弱點。如果攻擊者登入受影響的系統並執行蓄意製作的應用程式，則最嚴重的弱點可能會允許權限提高。
攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項弱點。匿名或遠端使用者無法利用這個弱點。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=201084">MS10-078</a></td>
<td style="border:1px solid black;"><strong>OpenType 字型 (CTF) 格式驅動程式中的弱點可能會允許權限提高 (2279986)</strong><br />
<br />
此安全性更新可解決 Windows OpenType 字型 (OTF) 格式驅動程式中兩項未公開報告的弱點。對於所有受支援版本的 Windows XP 和 Windows Server 2003，此安全性更新的等級為「重要」。所有受支援版本的 Windows Vista、Windows Server 2008、Windows 7、Windows Server 2008 R2，皆不受此弱點影響。<br />
<br />
如果使用者檢視以蓄意製作的 OpenType 字型所呈現的內容，則這些弱點可能會允許權限提高。攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項弱點。匿名或遠端使用者無法利用這個弱點。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=201696">MS10-079</a></td>
<td style="border:1px solid black;"><strong>Microsoft Word 中的弱點可能會允許遠端執行程式碼 (2293194)</strong><br />
<br />
這個安全性更新可解決 Microsoft Office 中 11 項未公開報告的弱點。如果使用者開啟蓄意製作的 Word 檔案，此弱點可能會允許遠端執行程式碼。成功利用這類任一弱點的攻擊者可以取得與本機使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=200529">MS10-080</a></td>
<td style="border:1px solid black;"><strong>Microsoft Excel 中的弱點可能會允許遠端執行程式碼 (2293211)</strong><br />
<br />
這個安全性更新可解決 Microsoft Office 中 13 項未公開報告的弱點。如果使用者開啟蓄意製作的 Excel 檔案或蓄意製作的 Lotus 1-2-3 檔案，這些弱點可能會允許遠端執行程式碼。成功利用這類任一弱點的攻擊者可以取得與本機使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=201086">MS10-081</a></td>
<td style="border:1px solid black;"><strong>Windows 通用控制項程式庫中的弱點可能會允許遠端執行程式碼 (2296011)</strong><br />
<br />
此安全性更新可解決 Windows 通用控制項程式庫中一項未公開報告的弱點。如果使用者造訪蓄意製作的網頁，此弱點可能會允許遠端執行程式碼。如果使用者以系統管理的使用者權限登入，成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=201098">MS10-082</a></td>
<td style="border:1px solid black;"><strong>Windows Media</strong> <strong>Player 中的弱點可能會允許遠端執行程式碼 (2378111)</strong><br />
<br />
這個安全性更新可解決 Windows Media Player 中一項未公開報告的弱點。如果 Windows Media Player 開啟位在惡意網站上的蓄意製作之媒體內容，此項弱點可能允許遠端執行程式碼。成功利用此弱點的攻擊者可以取得與本機使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190553">MS10-083</a></td>
<td style="border:1px solid black;"><strong>Windows Shell 和 WordPad 中 COM 驗證的弱點可能會允許遠端執行程式碼 (2405882)</strong><br />
<br />
這個安全性更新可解決 Microsoft Windows 中一項未公開報告的弱點。當使用者使用 WordPad 開啟蓄意製作的檔案，或者選取或開啟網路或 WebDAV 共用位置上的捷徑檔案時，此弱點可能會允許遠端執行程式碼。成功利用此弱點的攻擊者可以取得與本機使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=201720">MS10-084</a></td>
<td style="border:1px solid black;"><strong>Windows 本機程序呼叫中的弱點可能會造成權限提高 (2360937)</strong><br />
<br />
此安全性更新可解決 Microsoft Windows 中一項公開揭露的弱點。對於所有受支援版本的 Windows XP 和 Windows Server 2003，此安全性更新的等級為「重要」。所有受支援版本的 Windows Vista、Windows Server 2008、Windows 7、Windows Server 2008 R2，皆不受此弱點影響。<br />
<br />
如果攻擊者登入受影響的系統並執行蓄意製作的程式碼，將 LPC 訊息傳送至本機 LRPC Server，則此弱點可能會允許權限提高。該訊息可讓通過驗證的使用者以 NetworkService 帳戶的權限來存取資源。攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項弱點。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=201705">MS10-085</a></td>
<td style="border:1px solid black;"><strong>SChannel 中的弱點可能會允許拒絕服務 (2207566)</strong><br />
<br />
這個安全性更新可解決 Windows 安全通道 (Schannel) 安全性套件中一項未公開報告的弱點。如果受影響的系統透過安全通訊端層 (SSL) 收到蓄意製作的封包訊息，此弱點可能會允許拒絕服務。依照預設，所有受支援版本的 Windows Vista、Windows Server 2008、Windows 7 及 Windows Server 2008 R2 不會設為接收 SSL 網路資料流。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
阻絕服務</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=201703">MS10-074</a></td>
<td style="border:1px solid black;"><strong>Microsoft Foundation Classes 中的弱點可能會允許遠端執行程式碼 (2387149)</strong><br />
<br />
此安全性更新可解決 Microsoft Foundation Class (MFC) 程式庫中一項公開報告的弱點。如果使用者以系統管理員的使用者權限登入，並開啟以 MFC 程式庫建立的應用程式，則此弱點可能會允許遠端執行程式碼。成功利用此弱點的攻擊者，可取得與目前登入的使用者相同的權限。如果使用者以系統管理的使用者權限登入，則攻擊者即可取得受影響系統的完整控制權。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">中度</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=201721">MS10-086</a></td>
<td style="border:1px solid black;"><strong>Windows 共用叢集磁碟中的弱點可能會允許竄改 (2294255)</strong><br />
<br />
這個安全性更新可解決 Windows Server 2008 R2 作為共用容錯移轉叢集時一項未公開報告的弱點。此弱點可能會允許竄改容錯移轉叢集磁碟的系統管理共用中的資料。依照預設，Windows Server 2008 R2 伺服器不會受到此弱點影響。此弱點僅會影響容錯移轉叢集中使用的叢集磁碟。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">中度</a><br />
竄改</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
弱點索引  
--------
  
<span></span>
下表提供本月所述每個弱點的利用性評估。弱點根據遞減的弱點評估等級及 CVE 編號依序列出。僅包含安全性公告中，嚴重性等級為「重大」或「重要」的弱點。
  
**我該如何使用這個表格？**
  
請用這個表格來瞭解您可能需要安裝的每個安全性更新，與 30 天內已發行的可利用程式碼受影響之可能性。您應該檢閱下列的每個評估，按照特定的設定，將部署以優先次序排序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](http://technet.microsoft.com/zh-tw/security/cc998259.aspx)。
  
| 公告編號                                                  | 弱點標題                            | CVE ID                                                                           | 弱點索引評估                                                                                            | 主要重點                                                                                                                                   |  
|-----------------------------------------------------------|-------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS10-083](http://go.microsoft.com/fwlink/?linkid=190553) | COM 驗證弱點                        | [CVE-2010-1263](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1263) | [**1**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-076](http://go.microsoft.com/fwlink/?linkid=194560) | 內嵌 OpenType 字型整數溢位弱點      | [CVE-2010-1883](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1883) | [**1**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | 較新版作業系統上的 ASLR 能讓此弱點較難以被利用                                                                                             |  
| [MS10-078](http://go.microsoft.com/fwlink/?linkid=201084) | OpenType 字型剖析弱點               | [CVE-2010-2740](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2740) | [**1**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-078](http://go.microsoft.com/fwlink/?linkid=201084) | OpenType 字型驗證弱點               | [CVE-2010-2741](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2741) | [**1**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-073](http://go.microsoft.com/fwlink/?linkid=201093) | Win32k 鍵盤配置弱點                 | [CVE-2010-2743](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2743) | [**1**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | **這項弱點目前已公開揭露，並在網際網路生態系統中遭到利用**                                                                                 |  
| [MS10-073](http://go.microsoft.com/fwlink/?linkid=201093) | Win32k 視窗類別弱點                 | [CVE-2010-2744](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2744) | [**1**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | **這項弱點已經公開揭露**                                                                                                                   |  
| [MS10-082](http://go.microsoft.com/fwlink/?linkid=201098) | Windows Media Player 記憶體損毀弱點 | [CVE-2010-2745](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2745) | [**1**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-081](http://go.microsoft.com/fwlink/?linkid=201086) | Comctl32 堆積溢位弱點               | [CVE-2010-2746](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2746) | [**1**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-079](http://go.microsoft.com/fwlink/?linkid=201696) | Word 堆疊溢位弱點                   | [CVE-2010-3214](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3214) | [**1**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-079](http://go.microsoft.com/fwlink/?linkid=201696) | Word 書籤弱點                       | [CVE-2010-3216](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3216) | [**1**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-084](http://go.microsoft.com/fwlink/?linkid=201720) | LPC 訊息緩衝區溢位弱點              | [CVE-2010-3222](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3222) | [**1**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | **這項弱點已經公開揭露**                                                                                                                   |  
| [MS10-075](http://go.microsoft.com/fwlink/?linkid=201722) | RTSP 釋放後使用弱點                 | [CVE-2010-3225](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3225) | [**1**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-077](http://go.microsoft.com/fwlink/?linkid=201704) | .NET Framework x64 JIT 編譯器弱點   | [CVE-2010-3228](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3228) | [**1**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-080](http://go.microsoft.com/fwlink/?linkid=200529) | Excel 檔案格式剖析弱點              | [CVE-2010-3232](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3232) | [**1**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-080](http://go.microsoft.com/fwlink/?linkid=200529) | 公式子串流記憶體損毀弱點            | [CVE-2010-3234](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3234) | [**1**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-080](http://go.microsoft.com/fwlink/?linkid=200529) | 公式 Biff 記錄弱點                  | [CVE-2010-3235](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3235) | [**1**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-080](http://go.microsoft.com/fwlink/?linkid=200529) | 陣列超出範圍弱點                    | [CVE-2010-3236](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3236) | [**1**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-080](http://go.microsoft.com/fwlink/?linkid=200529) | 負向未來函式弱點                    | [CVE-2010-3238](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3238) | [**1**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-080](http://go.microsoft.com/fwlink/?linkid=200529) | 額外記錄剖析超出界線弱點            | [CVE-2010-3239](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3239) | [**1**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-071](http://go.microsoft.com/fwlink/?linkid=202013) | 未初始化的記憶體損毀弱點            | [CVE-2010-3326](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3326) | [**1**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-071](http://go.microsoft.com/fwlink/?linkid=202013) | 未初始化的記憶體損毀弱點            | [CVE-2010-3328](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3328) | [**1**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-071](http://go.microsoft.com/fwlink/?linkid=202013) | 未初始化的記憶體損毀弱點            | [CVE-2010-3329](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3329) | [**1**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-071](http://go.microsoft.com/fwlink/?linkid=202013) | 未初始化的記憶體損毀弱點            | [CVE-2010-3331](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3331) | [**1**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-079](http://go.microsoft.com/fwlink/?linkid=201696) | Word 未初始化指標弱點               | [CVE-2010-2747](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2747) | [**2**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-079](http://go.microsoft.com/fwlink/?linkid=201696) | Word 界限檢查弱點                   | [CVE-2010-2748](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2748) | [**2**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-079](http://go.microsoft.com/fwlink/?linkid=201696) | Word 索引弱點                       | [CVE-2010-2750](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2750) | [**2**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-079](http://go.microsoft.com/fwlink/?linkid=201696) | Word 傳回值弱點                     | [CVE-2010-3215](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3215) | [**2**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-079](http://go.microsoft.com/fwlink/?linkid=201696) | Word 指標弱點                       | [CVE-2010-3217](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3217) | [**2**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-079](http://go.microsoft.com/fwlink/?linkid=201696) | Word 堆積溢位弱點                   | [CVE-2010-3218](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3218) | [**2**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-079](http://go.microsoft.com/fwlink/?linkid=201696) | Word 索引剖析弱點                   | [CVE-2010-3219](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3219) | [**2**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-079](http://go.microsoft.com/fwlink/?linkid=201696) | Word 剖析弱點                       | [CVE-2010-3220](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3220) | [**2**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-079](http://go.microsoft.com/fwlink/?linkid=201696) | Word 剖析弱點                       | [CVE-2010-3221](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3221) | [**2**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-080](http://go.microsoft.com/fwlink/?linkid=200529) | Excel 記錄剖析整數溢位弱點          | [CVE-2010-3230](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3230) | [**2**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-080](http://go.microsoft.com/fwlink/?linkid=200529) | Excel 記錄剖析記憶體損毀弱點        | [CVE-2010-3231](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3231) | [**2**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-080](http://go.microsoft.com/fwlink/?linkid=200529) | Lotus 1-2-3 活頁簿剖析弱點          | [CVE-2010-3233](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3233) | [**2**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-080](http://go.microsoft.com/fwlink/?linkid=200529) | 合併儲存格記錄指標弱點              | [CVE-2010-3237](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3237) | [**2**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-080](http://go.microsoft.com/fwlink/?linkid=200529) | 即時資料陣列記錄弱點                | [CVE-2010-3240](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3240) | [**2**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-080](http://go.microsoft.com/fwlink/?linkid=200529) | 在剖析中記憶體寫入超出範圍弱點      | [CVE-2010-3241](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3241) | [**2**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-080](http://go.microsoft.com/fwlink/?linkid=200529) | 準刪除記錄類型剖析弱點              | [CVE-2010-3242](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3242) | [**2**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                                       |  
| [MS10-073](http://go.microsoft.com/fwlink/?linkid=201093) | Win32k 參照計數弱點                 | [CVE-2010-2549](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2549) | [**3**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | **這項弱點已經公開揭露**                                                                                                                   |  
| [MS10-085](http://go.microsoft.com/fwlink/?linkid=201705) | TLSv1 拒絕服務弱點                  | [CVE-2010-3229](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3229) | [**3**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 對安全性構成的最大影響僅為拒絕服務                                                                                                         |  
| [MS10-071](http://go.microsoft.com/fwlink/?linkid=202013) | HTML 清理弱點                       | [CVE-2010-3243](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3243) | [**3**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | [MS10-072](http://go.microsoft.com/fwlink/?linkid=202016) 也能解決這項弱點。對安全性構成的最大影響僅為資訊洩漏。                           |  
| [MS10-072](http://go.microsoft.com/fwlink/?linkid=202016) | HTML 清理弱點                       | [CVE-2010-3243](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3243) | [**3**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | [MS10-071](http://go.microsoft.com/fwlink/?linkid=202013) 也能解決這項弱點。對安全性構成的最大影響僅為資訊洩漏。                           |  
| [MS10-071](http://go.microsoft.com/fwlink/?linkid=202013) | HTML 清理弱點                       | [CVE-2010-3324](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3324) | [**3**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | [MS10-072](http://go.microsoft.com/fwlink/?linkid=202016) 也能解決這項弱點。**這項弱點已經公開揭露。**對安全性構成的最大影響僅為資訊洩漏。 |  
| [MS10-072](http://go.microsoft.com/fwlink/?linkid=202016) | HTML 清理弱點                       | [CVE-2010-3324](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3324) | [**3**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | [MS10-071](http://go.microsoft.com/fwlink/?linkid=202013) 也能解決這項弱點。**這項弱點已經公開揭露。**對安全性構成的最大影響僅為資訊洩漏。 |  
| [MS10-071](http://go.microsoft.com/fwlink/?linkid=202013) | CSS 特殊字元資訊洩漏弱點            | [CVE-2010-3325](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3325) | [**3**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | **這項弱點已經公開揭露。**對安全性構成的最大影響僅為資訊洩漏。                                                                             |  
| [MS10-071](http://go.microsoft.com/fwlink/?linkid=202013) | 跨網域資訊洩漏弱點                  | [CVE-2010-3330](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3330) | [**3**](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 對安全性構成的最大影響僅為資訊洩漏                                                                                                         |
  
受影響的軟體及下載位置  
----------------------
  
<span></span>
下表依據主要的軟體類別和嚴重性依序列出公告。
  
**我該如何使用這些表格？**
  
請用這些表格來瞭解可能需要安裝的安全性更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的安全性更新。若軟體程式或更新出現在清單中，則相關可用軟體更新也會以超連結方式提供，也會列出軟體更新的嚴重性等級。
  
**注意**：一項弱點，可能需要安裝數個安全性更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
#### Windows 作業系統與元件

 
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
<th colspan="14">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告** **編號**
</td>
<td style="border:1px solid black;">
[**MS10-071**](http://go.microsoft.com/fwlink/?linkid=202013)
</td>
<td style="border:1px solid black;">
[**MS10-075**](http://go.microsoft.com/fwlink/?linkid=201722)
</td>
<td style="border:1px solid black;">
[**MS10-076**](http://go.microsoft.com/fwlink/?linkid=194560)
</td>
<td style="border:1px solid black;">
[**MS10-077**](http://go.microsoft.com/fwlink/?linkid=201704)
</td>
<td style="border:1px solid black;">
[**MS10-073**](http://go.microsoft.com/fwlink/?linkid=201093)
</td>
<td style="border:1px solid black;">
[**MS10-078**](http://go.microsoft.com/fwlink/?linkid=201084)
</td>
<td style="border:1px solid black;">
[**MS10-081**](http://go.microsoft.com/fwlink/?linkid=201086)
</td>
<td style="border:1px solid black;">
[**MS10-082**](http://go.microsoft.com/fwlink/?linkid=201098)
</td>
<td style="border:1px solid black;">
[**MS10-083**](http://go.microsoft.com/fwlink/?linkid=190553)
</td>
<td style="border:1px solid black;">
[**MS10-084**](http://go.microsoft.com/fwlink/?linkid=201720)
</td>
<td style="border:1px solid black;">
[**MS10-085**](http://go.microsoft.com/fwlink/?linkid=201705)
</td>
<td style="border:1px solid black;">
[**MS10-074**](http://go.microsoft.com/fwlink/?linkid=201703)
</td>
<td style="border:1px solid black;">
[**MS10-086**](http://go.microsoft.com/fwlink/?linkid=201721)
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
無
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
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=3b029696-cf98-4935-b3d6-846110aaa4bb)  
(重大)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=c77ee103-7e97-44b2-bbf3-ee9f0de37fed)  
(重大)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=93580299-d764-417f-a7fa-ee441fea2bb3)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=c3799399-ca72-4dec-a2a2-3571ad0b2f63)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=3966d754-d298-4e4a-9ce6-8205accd2215)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=0553fc7c-deed-4594-a133-d621551310dc)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=912a7c20-8177-4f65-b986-43fca6375ec1)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Media Player 9 Series](http://www.microsoft.com/downloads/details.aspx?familyid=bbf153e7-e764-46a0-a33b-81b7288d346c)  
(重要)  
[Windows Media Player 10](http://www.microsoft.com/downloads/details.aspx?familyid=bbf153e7-e764-46a0-a33b-81b7288d346c)  
(重要)  
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?familyid=bbf153e7-e764-46a0-a33b-81b7288d346c)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=211d95be-5630-4af5-85a7-c50268c475a9)  
(KB979687)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6049c879-b81a-4d10-b96b-b2837cb24834)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=22f46b3b-9be6-45ea-a639-9974324ce4bd)  
(中度)
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=d494535a-b68e-4242-af85-5fa62f631ffc)  
(重大)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=ff9c65fe-437c-426d-9096-dd89ff7927fd)  
(重大)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=05413f6c-b4be-4892-b4b3-c54dd01fd95d)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=860ff738-205d-430e-b223-b333813fc590)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f)<sup>[1]</sup>
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7fd7c675-0675-4a87-a709-edc47a30f1e2)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1ad30596-bac6-4d48-8b15-0245960c443b)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6c651bca-adb1-4172-9714-cd5a6e5d2c2a)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Media Player 10](http://www.microsoft.com/downloads/details.aspx?familyid=0663e0e8-c5d1-4cd2-b6d3-ff78fb56bba1)  
(重要)  
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?familyid=474b5618-dfe6-40de-b59b-1fd61a05749e)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4b6f0898-8f77-4ce1-9c96-2b17c496230b)  
(KB979687)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d690846c-5e0b-4216-84cd-d17e366dd16d)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=285627b9-242d-4247-a4c8-55dc89386b62)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="14">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-071**](http://go.microsoft.com/fwlink/?linkid=202013)
</td>
<td style="border:1px solid black;">
[**MS10-075**](http://go.microsoft.com/fwlink/?linkid=201722)
</td>
<td style="border:1px solid black;">
[**MS10-076**](http://go.microsoft.com/fwlink/?linkid=194560)
</td>
<td style="border:1px solid black;">
[**MS10-077**](http://go.microsoft.com/fwlink/?linkid=201704)
</td>
<td style="border:1px solid black;">
[**MS10-073**](http://go.microsoft.com/fwlink/?linkid=201093)
</td>
<td style="border:1px solid black;">
[**MS10-078**](http://go.microsoft.com/fwlink/?linkid=201084)
</td>
<td style="border:1px solid black;">
[**MS10-081**](http://go.microsoft.com/fwlink/?linkid=201086)
</td>
<td style="border:1px solid black;">
[**MS10-082**](http://go.microsoft.com/fwlink/?linkid=201098)
</td>
<td style="border:1px solid black;">
[**MS10-083**](http://go.microsoft.com/fwlink/?linkid=190553)
</td>
<td style="border:1px solid black;">
[**MS10-084**](http://go.microsoft.com/fwlink/?linkid=201720)
</td>
<td style="border:1px solid black;">
[**MS10-085**](http://go.microsoft.com/fwlink/?linkid=201705)
</td>
<td style="border:1px solid black;">
[**MS10-074**](http://go.microsoft.com/fwlink/?linkid=201703)
</td>
<td style="border:1px solid black;">
[**MS10-086**](http://go.microsoft.com/fwlink/?linkid=201721)
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
無
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
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=f64af3cd-591d-4212-94a0-3bc9a4d9782a)  
(重要)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=fbcf0e65-c9f4-47f8-b4fc-ae46a66ab339)  
(重要)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=9af37f62-5585-4ff5-9dd3-3fa0b148ae08)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7b240b65-f3ca-465c-a606-b561999c1977)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8ef4378e-21ff-4290-96ba-e00a60f372d1)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f94763e7-b1db-4043-aa79-d5be1a42307d)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3b2eb449-ad55-4dfb-a3c5-aac767de6f45)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Media Player 10](http://www.microsoft.com/downloads/details.aspx?familyid=5479fd20-50d1-447a-8555-a98ce0723f71)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=13c08ec0-53ae-4b85-b669-8c88f6089259)  
(KB979687)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b31e18b0-da9f-4b3b-82c6-603e08b3b241)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d220f04e-9dbb-4b6d-924a-23065b48b8b6)  
(中度)
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=12c3b950-b955-4820-9b4c-5206deb0cd3e)  
(重要)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=59a715a5-10ff-40e6-88e0-096c9b640799)  
(重要)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c8052f0c-e62c-46c4-bb59-d515fa388ea8)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=70c9e826-b80b-4a20-82d2-8e52e5cca839)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f)<sup>[1]</sup>
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4a95c74b-cfd8-45b5-8887-777429d21745)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6fca5cab-7e11-4911-a6a8-f73f113b2963)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=54fc4bc6-f46c-447c-8307-afd8338e7ffb)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Media Player 10](http://www.microsoft.com/downloads/details.aspx?familyid=a9515e69-c147-4810-8c5a-6cb94c398a95)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=02519f9e-e1c5-48a1-8420-01898c45ec01)  
(KB979687)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1d73f0f1-6ec8-4304-a20e-345d8b6c225a)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=de908137-33e0-4f23-b32b-cc1bdbcb349c)  
(中度)
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=97b3f6dc-8df5-4c93-aaee-f191498c7ce4)  
(重要)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=ba194be9-24f9-4c62-9aa9-9e98c81ddba1)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=bd5878bb-f565-4303-afed-4e17b44a02f2)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f)<sup>[1]</sup>
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=21637cd8-c75c-43b4-9948-be7be54af6bf)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=e8f297e2-0dfd-421a-b598-a78199ad6baa)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=64f5c311-d74a-4665-9775-ac91c6885ed3)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=1064bccb-3ce6-4a72-8788-56d8021bca91)  
(KB979687)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=8fad4f77-7c89-4684-b957-9c00ced248d3)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=873dea9d-44cc-4e16-8a6d-dca678ce3a80)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="14">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-071**](http://go.microsoft.com/fwlink/?linkid=202013)
</td>
<td style="border:1px solid black;">
[**MS10-075**](http://go.microsoft.com/fwlink/?linkid=201722)
</td>
<td style="border:1px solid black;">
[**MS10-076**](http://go.microsoft.com/fwlink/?linkid=194560)
</td>
<td style="border:1px solid black;">
[**MS10-077**](http://go.microsoft.com/fwlink/?linkid=201704)
</td>
<td style="border:1px solid black;">
[**MS10-073**](http://go.microsoft.com/fwlink/?linkid=201093)
</td>
<td style="border:1px solid black;">
[**MS10-078**](http://go.microsoft.com/fwlink/?linkid=201084)
</td>
<td style="border:1px solid black;">
[**MS10-081**](http://go.microsoft.com/fwlink/?linkid=201086)
</td>
<td style="border:1px solid black;">
[**MS10-082**](http://go.microsoft.com/fwlink/?linkid=201098)
</td>
<td style="border:1px solid black;">
[**MS10-083**](http://go.microsoft.com/fwlink/?linkid=190553)
</td>
<td style="border:1px solid black;">
[**MS10-084**](http://go.microsoft.com/fwlink/?linkid=201720)
</td>
<td style="border:1px solid black;">
[**MS10-085**](http://go.microsoft.com/fwlink/?linkid=201705)
</td>
<td style="border:1px solid black;">
[**MS10-074**](http://go.microsoft.com/fwlink/?linkid=201703)
</td>
<td style="border:1px solid black;">
[**MS10-086**](http://go.microsoft.com/fwlink/?linkid=201721)
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
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
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
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 1 和 Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4f656d16-2a7e-4d18-8a5a-ebf8a1a10e2b)  
(重大)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=191c8388-f1ef-45b6-9f07-d5654a973abe)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4a481825-d9ad-4a7c-aa89-f40fb9651961)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=29c4afb1-227d-4572-b136-a78ef7e1df77)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e9f735ab-d995-4209-b2dc-197f53fdee0f)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=95ceafc6-e37a-4c77-b16e-c9c94a7d89bd)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?familyid=95e24a63-d21a-4756-a16e-17a977595396)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=80c99d69-4b97-4af2-8f8e-f3b300a89a5a)<sup>[1]</sup>
(KB979687)  
(重要)  
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=dff92449-22ad-49a8-8b28-5295a8af5b8b)<sup>[1]</sup>
(KB979688)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4af2f6e6-6905-498c-bfba-a565976b3365)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=75ca4e2c-b0ae-46f4-a0fc-616510c41a55)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=02c6260c-8e21-401a-992d-884c6ff7141d)  
(重大)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=adeb3036-62fa-4a29-b82f-ff4a50c05996)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=15d8f81b-97b0-43d9-b218-1cdd759cb2ec)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=880ad9a0-6ddd-41f4-a608-171d59a31b6a)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f)<sup>[1]</sup>
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=738c8f70-b46a-4a59-bea6-078074a9c4db)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=dfe7cd18-53a3-433e-9a33-bd96b04b4deb)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?familyid=277151a2-b74f-4da6-8203-e774af75e44c)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b73951f2-a7eb-4c7c-bf60-fdcfee83574f)<sup>[1]</sup>
(KB979687)  
(重要)  
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c9d2261f-bd9a-4495-a2f1-3c3b2208b01e)<sup>[1]</sup>
(KB979688)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8c56ba29-b2a8-47a8-a605-4c54c0a7fa7c)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0a12ff95-ea5c-4c48-96c5-9494eb8f9f0d)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="14">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-071**](http://go.microsoft.com/fwlink/?linkid=202013)
</td>
<td style="border:1px solid black;">
[**MS10-075**](http://go.microsoft.com/fwlink/?linkid=201722)
</td>
<td style="border:1px solid black;">
[**MS10-076**](http://go.microsoft.com/fwlink/?linkid=194560)
</td>
<td style="border:1px solid black;">
[**MS10-077**](http://go.microsoft.com/fwlink/?linkid=201704)
</td>
<td style="border:1px solid black;">
[**MS10-073**](http://go.microsoft.com/fwlink/?linkid=201093)
</td>
<td style="border:1px solid black;">
[**MS10-078**](http://go.microsoft.com/fwlink/?linkid=201084)
</td>
<td style="border:1px solid black;">
[**MS10-081**](http://go.microsoft.com/fwlink/?linkid=201086)
</td>
<td style="border:1px solid black;">
[**MS10-082**](http://go.microsoft.com/fwlink/?linkid=201098)
</td>
<td style="border:1px solid black;">
[**MS10-083**](http://go.microsoft.com/fwlink/?linkid=190553)
</td>
<td style="border:1px solid black;">
[**MS10-084**](http://go.microsoft.com/fwlink/?linkid=201720)
</td>
<td style="border:1px solid black;">
[**MS10-085**](http://go.microsoft.com/fwlink/?linkid=201705)
</td>
<td style="border:1px solid black;">
[**MS10-074**](http://go.microsoft.com/fwlink/?linkid=201703)
</td>
<td style="border:1px solid black;">
[**MS10-086**](http://go.microsoft.com/fwlink/?linkid=201721)
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
無
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
無
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0107dd61-7b3e-4fcf-9743-d9ae594b2278)\*\*  
(重要)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ea5b7c86-3878-43a9-a4bc-12e04bfbd06e)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=50386655-982e-4126-8261-2c972d695bbd)\*\*  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4dff0ebe-ccba-4675-98ca-9903f1cb6763)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d5f079b0-d8e1-47fe-b9dd-41eeb463a93c)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?familyid=67eb3a70-9ca7-4184-b9fe-cc3e66b1bf36)\*\*  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=fd507e7a-4516-474b-8f33-7fa8fd2afa6d)\*\*<sup>[1]</sup>
(KB979687)  
(重要)  
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4a8c2358-36ea-4757-abfc-5bffcad0a872)\*\*<sup>[1]</sup>
(KB979688)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0566915f-2a1b-474b-b5f1-e1a9cedd836a)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=952b3594-d980-45b1-8fa3-49403784afbf)\*\*  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=139f3bb2-eefc-4cf4-9c15-de78f5a736c1)\*\*  
(重要)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=71ecdb27-46aa-4db1-b86a-3268cda88632)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a6b2ae1d-9225-4495-8560-97860f87d7b4)\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f)\*\*<sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=da7905a9-9587-4184-8fca-ecc636a3b67e)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8e88d9c5-eb57-4d39-a880-a478c5f286da)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?familyid=33a06f0e-81ab-445a-bc89-14350ebfe688)\*\*  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b5f53faf-61e2-4b4e-8b85-c5e8f38e5c30)\*\*<sup>[1]</sup>
(KB979687)  
(重要)  
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=612ab78c-1ff1-45d2-96cc-ae831fb0a563)\*\*<sup>[1]</sup>
(KB979688)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=74ac2233-02ec-454c-8aa0-64b18071e16a)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=21128031-d935-4e2d-b001-c502a2d6022c)\*\*  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=1a971fb2-7dc4-43bf-ae25-3a420bb1acf9)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a4e38a77-3835-47b3-bd86-6c039169abf5)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f)<sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b9096046-8c7a-450c-b8c5-6e9fb001e6cd)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=76e46d08-22d9-4a0c-82cd-d2753d07efe6)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5efe55b0-d34d-4f00-98b2-cc0e9807a8b9)<sup>[1]</sup>
(KB979687)  
(重要)  
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d30368cb-c6e8-403e-aaf6-425f96b6211e)<sup>[1]</sup>
(KB979688)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2fff281a-2221-42a3-a2b7-07b5c5e66ae7)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2eca0c38-73f5-4f83-ab62-97f979716a1d)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="14">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-071**](http://go.microsoft.com/fwlink/?linkid=202013)
</td>
<td style="border:1px solid black;">
[**MS10-075**](http://go.microsoft.com/fwlink/?linkid=201722)
</td>
<td style="border:1px solid black;">
[**MS10-076**](http://go.microsoft.com/fwlink/?linkid=194560)
</td>
<td style="border:1px solid black;">
[**MS10-077**](http://go.microsoft.com/fwlink/?linkid=201704)
</td>
<td style="border:1px solid black;">
[**MS10-073**](http://go.microsoft.com/fwlink/?linkid=201093)
</td>
<td style="border:1px solid black;">
[**MS10-078**](http://go.microsoft.com/fwlink/?linkid=201084)
</td>
<td style="border:1px solid black;">
[**MS10-081**](http://go.microsoft.com/fwlink/?linkid=201086)
</td>
<td style="border:1px solid black;">
[**MS10-082**](http://go.microsoft.com/fwlink/?linkid=201098)
</td>
<td style="border:1px solid black;">
[**MS10-083**](http://go.microsoft.com/fwlink/?linkid=190553)
</td>
<td style="border:1px solid black;">
[**MS10-084**](http://go.microsoft.com/fwlink/?linkid=201720)
</td>
<td style="border:1px solid black;">
[**MS10-085**](http://go.microsoft.com/fwlink/?linkid=201705)
</td>
<td style="border:1px solid black;">
[**MS10-074**](http://go.microsoft.com/fwlink/?linkid=201703)
</td>
<td style="border:1px solid black;">
[**MS10-086**](http://go.microsoft.com/fwlink/?linkid=201721)
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
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[無](http://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=6595770f-e580-4613-a83a-3b8ee4cc30f1)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=1a3953fe-ba48-4980-a65d-74e3b756d53c)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=f6cae091-e9f1-48e9-a035-4346b9c6fec6)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=b5b31499-d242-42bf-ac78-b787ffb4d602)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=bdff9057-381a-44e8-b093-84f07d8d7e3c)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Media Player 12](http://www.microsoft.com/downloads/details.aspx?familyid=59a2ef36-9c32-488b-b5b1-30b5bcd83358)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=b0d46bc3-24db-4207-b6fc-46b8cc64f075)<sup>[1]</sup>
(KB979687)  
(重要)  
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=4a422192-d7fa-47e5-9661-2c65eaefaf62)<sup>[1]</sup>
(KB979688)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=d7a08a66-08b4-421c-afad-f2f367d4a9f0)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=f09fbc23-cb6b-4525-8e41-8c14e8d03de9)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ffe364ee-e2ae-466c-b727-14b1a976a860)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=5759d2a3-7f35-4fa1-8ab4-17145839fa26)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=35882477-4e0a-4783-a4b4-0f1ea3398360)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f)<sup>[1]</sup>
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=c47e8b74-8cfe-42d9-9362-8786687c88ad)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=35a2b1a9-6dd6-4a7e-bc0a-b4fcffa06b28)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Media Player 12](http://www.microsoft.com/downloads/details.aspx?familyid=00176d56-8a93-4780-96fc-a7ab715e7291)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=2de197c0-6d9e-460e-9509-f337fac8ee85)<sup>[1]</sup>
(KB979687)  
(重要)  
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=03665687-8fd4-4afd-ac33-5f6824f51df8)<sup>[1]</sup>
(KB979688)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=50d27c23-5f69-40fa-b517-32c245009467)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=abc24826-b83a-4e01-be68-8e3a73c10494)  
(中度)
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
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f)<sup>[1]</sup>
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
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="14">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-071**](http://go.microsoft.com/fwlink/?linkid=202013)
</td>
<td style="border:1px solid black;">
[**MS10-075**](http://go.microsoft.com/fwlink/?linkid=201722)
</td>
<td style="border:1px solid black;">
[**MS10-076**](http://go.microsoft.com/fwlink/?linkid=194560)
</td>
<td style="border:1px solid black;">
[**MS10-077**](http://go.microsoft.com/fwlink/?linkid=201704)
</td>
<td style="border:1px solid black;">
[**MS10-073**](http://go.microsoft.com/fwlink/?linkid=201093)
</td>
<td style="border:1px solid black;">
[**MS10-078**](http://go.microsoft.com/fwlink/?linkid=201084)
</td>
<td style="border:1px solid black;">
[**MS10-081**](http://go.microsoft.com/fwlink/?linkid=201086)
</td>
<td style="border:1px solid black;">
[**MS10-082**](http://go.microsoft.com/fwlink/?linkid=201098)
</td>
<td style="border:1px solid black;">
[**MS10-083**](http://go.microsoft.com/fwlink/?linkid=190553)
</td>
<td style="border:1px solid black;">
[**MS10-084**](http://go.microsoft.com/fwlink/?linkid=201720)
</td>
<td style="border:1px solid black;">
[**MS10-085**](http://go.microsoft.com/fwlink/?linkid=201705)
</td>
<td style="border:1px solid black;">
[**MS10-074**](http://go.microsoft.com/fwlink/?linkid=201703)
</td>
<td style="border:1px solid black;">
[**MS10-086**](http://go.microsoft.com/fwlink/?linkid=201721)
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
無
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
無
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d8b563ce-5db1-4490-8a63-44833d55152b)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=b060c516-233a-4e1e-9237-698420e97b2f)\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f)<sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=98e0c6ac-c30b-4d39-8ed9-1fe69e7644e5)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=25fff010-3abc-45e6-979e-21d2bae49418)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Media Player 12](http://www.microsoft.com/downloads/details.aspx?familyid=4cf0e3b1-4b72-4f99-b716-2489ea42ed72)\*\*  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=70622d35-4877-4cbb-bdbf-7648dc1ea8ed)\*\*<sup>[1]</sup>
(KB979687)  
(重要)  
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=1c2ff242-65e3-4d47-bfca-4db30f809ed8)\*\*<sup>[1]</sup>
(KB979688)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=d356af2f-eadf-4bf2-82d1-efa0d01ac92d)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=e4d27aa6-9739-4e41-9536-5f0b8d26503c)\*\*  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=1de12fdf-b439-4020-9313-a193d47dcfb2)\*  
(中度)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1
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
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f)\*\*<sup>[1]</sup>
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
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=bbaa9f46-8fc7-4c44-b38c-dc3d5210f63d)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=0ead2ed9-8b2f-496e-b7d1-3ad2b04be5cc)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f)<sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=44080c75-036e-4bd0-914a-74ab72189ee3)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=d0742526-b5ec-4658-82f1-c3680f33a790)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=3cec2b70-f694-4c0d-bf82-96a4fd50675d)<sup>[1]</sup>
(KB979687)  
(重要)  
[適用於 Itanium 系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=f478020b-0305-47d5-bcb2-0758f292db29)<sup>[1]</sup>
(KB979688)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=334d39e6-8e4c-4e83-94c1-1db3d636e865)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=c1634278-5598-45e0-81c6-f18fb5ba54cf)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=1c607c7d-6144-4a39-beea-a31b62085047)  
(中度)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1
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
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f)<sup>[1]</sup>
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
不適用
</td>
</tr>
</table>
 
**MS10-077 注意事項**

<sup>[1]</sup>**.NET Framework 4.0 和 .NET Framework 4.0 Client Profile 會受到影響。**可在兩個設定檔中使用 .NET Framework 第 4 版可轉散發套件： .NET Framework 4.0 和 .NET Framework 4.0 Client Profile。.NET Framework 4.0 Client Profile 是 .NET Framework 4.0 的子集。此更新所解決的弱點會影響到 .NET Framework 4.0 和 .NET Framework 4.0 Client Profile。如需詳細資訊，請參閱 MSDN 文章：安裝 .NET Framework (英文)。

**MS10-083 注意事項**

<sup>[1]</sup>如果同一種作業系統同時有 KB979687 和 KB979688 兩個安全性更新套件，客戶必須兩者都安裝，才能有效防範 MS10-083 中所說明的弱點。

**Windows Server 2008 和 Windows Server 2008 R2 注意事項**

**\*Server** **Core 安裝會受影響。**無論上述受支援的 Windows Server 2008 或 Windows Server 2008 R2 版本是否使用 Server Core 安裝選項安裝，這個更新均以相同的嚴重性等級套用。如需此安裝選項的詳細資訊，請參閱 TechNet 文章：[管理 Server Core 安裝](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (英文) 和[維護 Server Core 安裝](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 和 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**\*\*Server Core 安裝不受影響。**如果 Windows Server 2008 是使用 Server Core 安裝選項所安裝，則這項更新解決的弱點並不會影響受支援的 Windows Server 2008。如需此安裝選項的詳細資訊，請參閱 TechNet 文章：[管理 Server Core 安裝](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (英文) 和[維護 Server Core 安裝](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 和 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

#### Microsoft Office 套件及軟體

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="3">
Microsoft Office 套件和元件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-079**](http://go.microsoft.com/fwlink/?linkid=201696)
</td>
<td style="border:1px solid black;">
[**MS10-080**](http://go.microsoft.com/fwlink/?linkid=200529)
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
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Word 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=f22d10fd-cb12-43e8-88d5-2116cf4317c4)  
(KB2328360)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=ea859881-2cc5-407b-a394-5d00c5d9fd97)  
(KB2345017)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Word 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=172f3743-cdfa-42d7-aeb4-27ba0e4139f7)  
(KB2344911)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=3d9a00b8-0f80-4d36-b92a-89b61350fb36)  
(KB2344893)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Word 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ccad4871-32f2-4982-a23e-9b5824397615)<sup>[1]</sup>
(KB2344993)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=dc9b9af5-50b0-4a07-8923-a30fd5548760)<sup>[1]</sup>
(KB2345035)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 (32 位元版本)
</td>
<td style="border:1px solid black;">
[Microsoft Word 2010 (32 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=6c3b8690-e568-42ed-a858-0cbdd5ea3669)  
(KB2345000)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 (64 位元版本)
</td>
<td style="border:1px solid black;">
[Microsoft Word 2010 (64 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=f31a1f9b-02df-4a85-a7d1-7d1e31baa30f)  
(KB2345000)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-079**](http://go.microsoft.com/fwlink/?linkid=201696)
</td>
<td style="border:1px solid black;">
[**MS10-080**](http://go.microsoft.com/fwlink/?linkid=200529)
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
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=464965fa-971a-49dd-bcee-c4d91fac86a9)  
(KB2422343)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=464965fa-971a-49dd-bcee-c4d91fac86a9)  
(KB2422343)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=abd05074-8ffc-41a4-a2f3-1d8047574552)  
(KB2422352)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=abd05074-8ffc-41a4-a2f3-1d8047574552)  
(KB2422352)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=5c759c46-ead3-44ea-b7c8-a308b3140d2e)  
(KB2422398)  
(重要)
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=5c759c46-ead3-44ea-b7c8-a308b3140d2e)  
(KB2422398)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
其他 Office 軟體
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-079**](http://go.microsoft.com/fwlink/?linkid=201696)
</td>
<td style="border:1px solid black;">
[**MS10-080**](http://go.microsoft.com/fwlink/?linkid=200529)
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
Microsoft Word Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Word Viewer](http://www.microsoft.com/downloads/details.aspx?familyid=1cb5ab02-074d-4877-b378-7058959705ae)  
(KB2345009)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Excel Viewer
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Excel Viewer Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a833a94a-2dc0-4864-9c14-e196dc54c5a7)  
(KB2345088)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Word、Excel 及 PowerPoint 2007 檔案格式相容性套件 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Office Word、Excel 及 PowerPoint 2007 檔案格式相容性套件 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=553d28ae-c352-4985-97c3-e5038414be45)  
(KB2345043)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Word、Excel 及 PowerPoint 2007 檔案格式相容性套件 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7391ec2f-12c9-483c-91d8-e3ec5754da1c)  
(KB2344875)  
(重要)
</td>
</tr>
</table>
 
**MS10-079 注意事項**

<sup>[1]</sup>針對 Microsoft Office Word 2007 Service Pack 2，除了安全性更新套件 KB2344993 外，客戶也必須安裝 Word、Excel 與 PowerPoint 2007 檔案格式的 Microsoft Office 相容性套件 Service Pack 2 的安全性更新 (KB2345043)，才能有效防範 MS10-079 所說明的弱點。

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

**MS10-080 注意事項**

<sup>[1]</sup>針對 Microsoft Office Excel 2007 Service Pack 2，除了安全性更新套件 KB2345035 外，客戶也需安裝 Word、Excel 與 PowerPoint 2007 檔案格式的 Microsoft Office 相容性套件 Service Pack 2 之安全性更新 (KB2344875)，才能有效防範 MS10-080 所說明的弱點。

#### Microsoft 伺服器軟體

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="3">
Microsoft SharePoint Services 與 Microsoft SharePoint Foundation
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-072**](http://go.microsoft.com/fwlink/?linkid=202016)
</td>
<td style="border:1px solid black;">
[**MS10-079**](http://go.microsoft.com/fwlink/?linkid=201696)
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
無
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 Service Pack 2 (32 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=12fd97a9-6fb8-4b65-a497-a56587f114e1)  
(KB2345304)  
(重要)  
[Microsoft Windows SharePoint Services 3.0 Service Pack 2 (64 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=58d1e91d-a037-485d-a6d9-80fbf403b108)  
(KB2345304)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010](http://www.microsoft.com/downloads/details.aspx?familyid=fc146fcb-c2cb-4860-a0cd-4b09fa3f44eb)  
(KB2345322)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="3">
Microsoft SharePoint 和 Microsoft Groove Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-072**](http://go.microsoft.com/fwlink/?linkid=202016)
</td>
<td style="border:1px solid black;">
[**MS10-079**](http://go.microsoft.com/fwlink/?linkid=201696)
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
無
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 2 (32 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=aee3f2de-ccf3-4d32-b468-eede4e8afcd4)<sup>[1]</sup>
(KB2345212)  
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (64 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=e5e60751-242a-4fdb-9852-6d94050d3d0e)<sup>[1]</sup>
(KB2345212)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Groove Server 2010
</td>
<td style="border:1px solid black;">
[Microsoft Groove Server 2010](http://www.microsoft.com/downloads/details.aspx?familyid=e032aef8-dd30-41c6-99bb-8cf0491451cc)  
(KB2346298)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
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
[**MS10-072**](http://go.microsoft.com/fwlink/?linkid=202016)
</td>
<td style="border:1px solid black;">
[**MS10-079**](http://go.microsoft.com/fwlink/?linkid=201696)
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
Microsoft Office Web Apps
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps](http://www.microsoft.com/downloads/details.aspx?familyid=8fb56eb9-9601-4c1e-905a-9fe4802b2c8d)  
(KB2346411)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps](http://www.microsoft.com/downloads/details.aspx?familyid=8fb56eb9-9601-4c1e-905a-9fe4802b2c8d)<sup>[2]</sup>
(KB2346411)  
(重要)  
[Microsoft Word Web App](http://www.microsoft.com/downloads/details.aspx?familyid=13b24264-ec3d-44e8-81e3-82ac767defd3)<sup>[2]</sup>
(KB2345015)  
(重要)
</td>
</tr>
</table>
 
**MS10-072 注意事項**

<sup>[1]</sup>針對支援的 Microsoft SharePoint Server 2007 版本，除了安全性更新套件 KB2345212 外，客戶還必須安裝 Microsoft Windows SharePoint Services 3.0 的安全性更新 (KB2345304)，才能有效防範 MS10-072 中所說明的弱點。

**MS10-079 注意事項**

<sup>[2]</sup>針對 Microsoft Office Web Apps，客戶必須安裝安全性更新 KB2346411 和安全性更新 KB2345015 兩者，才能有效防範 MS10-079 中所說明的弱點。

另請參閱＜受影響的軟體及下載位置＞一節中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。本公告涉及多個軟體分類。

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和安全性更新。如需更多資訊，請參閱 [TechNet 更新管理中心](http://go.microsoft.com/fwlink/?linkid=69903) (英文)。[TechNet 資訊安全技術中心](http://go.microsoft.com/fwlink/?linkid=21171)提供 Microsoft 產品安全性的其他資訊。消費者可以造訪[在家上網的安全性](http://go.microsoft.com/fwlink/?linkid=85102)網站，只要按一下 \[最新安全性更新\] 即可在此網站取得此資訊。

安全性更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 以及 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) 取得。安全性更新也可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得。您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。

最後，您可以從 [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) 下載安全性更新。Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括安全性更新、驅動程式和 Service Pack。只要以安全性公告編號 (例如：MS07-036) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](http://go.microsoft.com/fwlink/?linkid=97900)。

**偵測與部署指南**

Microsoft 針對安全性更新提供偵測和部署指南。本指南所含之建議和資訊，能幫助 IT 專業人員瞭解如何使用用於安全性更新的偵測和部署的各種工具。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 961747](http://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少安全性更新以及一般安全性設定錯誤的狀況。如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速而可靠地將 Microsoft Windows 2000 作業系統及更新版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 適用的最新重大更新與安全性更新部署到 Microsoft Windows 2000 及更新版本的作業系統中。

如需更多關於利用 Windows Server Update Services 部署安全性更新的資訊，請造訪 [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) (英文)。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。現已推出新版的 SMS，System Center Configuration Manager 2007；另請參閱 [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)。如需更多有關系統管理員如何能使用 SMS 2003 部署安全性更新的資訊，請參閱 [SMS 2003 安全性修補程式管理 (英文)](http://go.microsoft.com/fwlink/?linkid=22939)。SMS 2.0 使用者也可以使用安全性更新盤點工具 (Security Update Inventory Tool，SUIT) 來協助部署安全性更新。如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158)。

**注意** ：SMS 使用 Microsoft Baseline Security Analyzer 提供廣泛的安全性公告更新偵測與部署支援。不過這些工具可能無法偵測部分的軟體更新。在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](http://go.microsoft.com/fwlink/?linkid=33341) (英文)。某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。系統管理員可使用 Elevated Rights Deployment Tool (隨 [SMS 2.0 Administration Feature Pack (英文)](http://go.microsoft.com/fwlink/?linkid=21161) 提供) 來安裝這些更新。

**Update Compatibility Evaluator 和應用程式相容性工具組**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。這可能會觸發不相容性，而拉長部署安全性更新的時間。您可以使用 [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 隨附的 [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 元件，針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Microsoft Windows Vista、Windows Update、Microsoft 安全性更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非安全性、高優先順序更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](http://support.microsoft.com/kb/894199)： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](http://technet.microsoft.com/en-us/wsus/bb456965.aspx)。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的安全性保護，Microsoft 將在每月發行安全性更新之前，提前向重要安全性軟體提供者提供弱點資訊。安全性軟體提供者可利用此弱點資訊，透過其安全性軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有安全性軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://www.microsoft.com/security/msrc/mapp/partners.mspx) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 安全性策略與社群

**更新程式管理策略**

[更新管理安全性指南](http://go.microsoft.com/fwlink/?linkid=21168) (英文) 提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   消費性平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](http://support.microsoft.com/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員安全性社群](http://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](http://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 [Google Inc.](http://www.google.com/) 的 [Sirdarckcat](http://www.sirdarckcat.net/) 回報 MS10-071 中描述的一項問題。
-   感謝 Mario Heiderich 回報 MS10-071 中描述的一項問題
-   感謝 [IBM ISS X-Force](http://www.iss.net/) 的 Takehiro Takahashi 回報 MS10-071 中描述的一項問題
-   感謝 [Peter Vreugdenhil](http://vreugdenhilresearch.nl) 與 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 MS10-071 中描述的一項問題
-   感謝 [Core Security Technologies](http://www.coresecurity.com/) 的 Damián Frizza 回報 MS10-071 中描述的一項問題
-   感謝 [Cigital](http://www.cigital.com/) 的 Aldwin Saugere 和 Radoslav Vasilev 回報 MS10-071 中描述的一項問題
-   感謝 [Check Point](http://www.checkpoint.com/) IPS Research Center 的 Rodrigo Rubira Branco 回報 MS10-071 中描述的一項問題
-   感謝 [Google Inc.](http://www.google.com/) 的 [Sirdarckcat](http://www.sirdarckcat.net/) 回報 MS10-072 中描述的一項問題
-   感謝 Mario Heiderich 回報 MS10-072 中描述的一項問題
-   感謝 [Kaspersky Lab](http://www.kaspersky.com) 的 Sergey Golovanov、Alexander Gostev、Maxim Golovkin 和 Alexey Monastyrsky，以及 [Design and Test Lab](http://www.dnt-lab.com) 的 Vitaly Kiktenko 和 Alexander Saprykin 回報 MS10-073 中描述的一項問題
-   感謝 [Symantec](http://www.symantec.com/index.jsp) 的 Eric Chien 回報 MS10-073 中描述的一項問題
-   感謝 [Norman](http://www.norman.com) 的 Tarjei Mandt 協助我們解決 MS10-073 中描述的一項問題
-   感謝 [Secunia](http://secunia.com/) 的 Carsten H. Eiram 協助我們解決 MS10-074 中描述的問題
-   感謝 Oleksandr Mirosh 與 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 MS10-075 中描述的一項問題
-   感謝 Sebastian Apelt 與 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 MS10-076 中描述的一項問題
-   感謝 [iSIGHT Partners Global Vulnerability Partnership](https://gvp.isightpartners.com/) 的 Ivan Fratric 回報 MS10-076 中描述的一項問題
-   感謝 [Sumatra](http://www.sumatra.nl/) 的 Jeroen Frijters 回報 MS10-077 中描述的一項問題
-   感謝 [Siberas](http://www.siberas.de/) 的 Sebastian Apelt 回報 MS10-078 中描述的一項問題
-   感謝 [Core Security Technologies](http://www.coresecurity.com/) 的 Diego Juarez 回報 MS10-078 中描述的一項問題
-   感謝 [VUPEN Vulnerability Research Team](http://www.vupen.com/) 的 Chaouki Bekrar 回報 MS10-079 中描述的一項問題
-   感謝 [VUPEN Vulnerability Research Team](http://www.vupen.com/) 的 Nicolas Joly 回報 MS10-079 中描述的一項問題
-   感謝 [Secunia Research](http://secunia.com/) 的 Alin Rad Pop 回報 MS10-079 中描述的一項問題
-   感謝 [Secunia](http://secunia.com/) 的 Alin Rad Pop 回報 MS10-080 中描述的兩項問題
-   感謝 [VUPEN Vulnerability Research Team](http://www.vupen.com/) 的 Chaouki Bekrar 回報 MS10-080 中描述的十項問題
-   感謝 Omair 回報 MS10-080 中描述的一項問題
-   感謝 [Secunia](http://secunia.com/) 的 Carsten H. Eiram 回報 MS10-080 中描述的兩項問題
-   感謝 Krystian Kloskowski (h07) 與 [Secunia](http://secunia.com/) 合作，共同回報 MS10-081 中描述的一項問題
-   感謝 [Google Inc.](http://www.google.com/) 的 SkyLined 回報 MS10-082 中描述的一項問題
-   感謝 [Rapid7](http://www.rapid7.com/) 的 HD Moore 回報 MS10-083 中描述的一項問題
-   感謝 [IBM ISS X-Force](http://www.iss.net/) 的 David Dewey 和 [Accuvant](http://www.accuvant.com/) (舊稱 [VeriSign iDefense Labs](http://labs.idefense.com/)) 的 Ryan Smith 協助我們開發 MS10-083 中所述的深度防禦變更
-   感謝 [Mu Dynamics](http://www.mudynamics.com/) 的 [Mu Test Suite Team](http://www.mudynamics.com/products/mu-test-suite.html) 回報 MS10-085 中描述的一項問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 支援週期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可洽詢[安全性支援](http://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 以取得技術支援。與安全性更新有關的支援電話不另外收費。如需更多可用支援選項的資訊，請參閱 [Microsoft 技術支援](http://support.microsoft.com/)。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。與安全性更新有關的支援電話不另外收費。如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[國際化支援](http://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2010 年 10 月 12 日)： 公告摘要發行。
-   V1.1 (2010 年 10 月 13 日)： 針對 MS10-077，Windows Server 2008 和 Windows Server 2008 R2 的弱點嚴重性等級變更為「重要」。此外，針對 MS10-082，更正 Windows XP Professional x64 Edition Service Pack 2 上的 Windows Media Player 11 的下載連結。
-   V2.0 (2010 年 10 月 18 日)： 針對 MS10-085，更改了＜提要＞中的描述，說明在設定為接收 SSL 網路資料流的受影響系統上，此弱點可能會遭到利用。這只是資訊的變更。已成功更新系統的客戶，包括已啟用自動更新的客戶，不必採取任何行動。尚未安裝此更新的客戶可能需要重新評估其系統是否需要此更新。
-   V3.0 (2010 年 12 月 14 日)： 修訂此公告摘要，以宣布下列內容： 對於 MS10-077，.NET Framework 4.0 已有可用的新版更新套件，可對安裝程式的一個問題進行修正，以免無法成功安裝其他更新和/或產品。已成功更新系統的客戶不必採取任何行動。MS10-083 提供額外更新：Windows Vista Service Pack 2 (KB979688) 和 Windows Server 2008 Service Pack 2 (KB979688)，對象是在 Windows Vista Service Pack 1 或 Windows Server 2008 安裝了 Windows Search 4.0，然後安裝 KB2405882 提供之安全性更新，接著移轉至 Windows Vista Service Pack 2 或 Windows Server 2008 Service Pack 2 的使用者。新版更新可從 [Microsoft 知識庫文件編號 2405882](http://support.microsoft.com/kb/2405882) 取得。
-   V4.0 (2011 年 2 月 22 日)： MS10-077 變更偵測方式，針對在安裝適用於 x64 型系統的 Windows 7 Service Pack 1、適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 或適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1 後繼續安裝 Microsoft .NET Framework 4.0 的客戶，提供 Microsoft .NET Framework 4.0 更新套件。已成功更新系統的客戶不必採取任何行動。
-   V4.1 (2011 年 10 月 26 日)： 針對 MS10-077，更正 x64 型系統 Windows Server 2008 R2 上 .NET Framework 4 的 Server Core 安裝適用性。

*Built at 2014-04-18T01:50:00Z-07:00*
