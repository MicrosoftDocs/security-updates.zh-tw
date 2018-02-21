---
TOCTitle: 'MS12-JAN'
Title: 2012 年 1 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms12-jan'
ms:contentKeyID: 61237730
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms12-jan(v=Security.10)'
---

2012 年 1 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2012年1月11日 | 更新: 2012年1月28日

**版本:** 2.1

此公告摘要列出 2012 年 1 月份發行之資訊安全公告。

發行 2012 年 1 月份資訊安全公告之後，此公告摘要將取代原先於 2012 年 1 月 5 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 資訊安全公告預先通知](http://technet.microsoft.com/zh-tw/security/bulletin/advance)。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術資訊安全通知](http://technet.microsoft.com/zh-tw/security/dd252948.aspx)。

Microsoft 將利用網路廣播於 2012 年 1 月 11 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。[立即註冊參加 1 月份資訊安全公告網路廣播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032499498)。在這個日期後，此網路廣播將可隨選取得。如需更多資訊，請參閱 [Microsoft 資訊安全公告摘要和網路廣播](http://technet.microsoft.com/zh-tw/security/bulletinarchive?y=2012&m=1) (英文)。

Microsoft 也會提供資訊協助客戶排定每月資訊安全更新以及任何非資訊安全更新的優先順序，其中這些非資訊安全更新的發行日期與每月資訊安全更新的發行日期相同。請參閱＜其他資訊＞一節。

### 公告資訊

提要
----

<span></span>
下表依嚴重性摘要說明本月份資訊安全公告。

如需受影響的軟體之詳細資料，請參閱下節＜受影響的軟體及下載位置＞。

 
<p> </p>
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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-004">MS12-004</a></td>
<td style="border:1px solid black;">Windows Media 中的資訊安全風險可能會允許遠端執行程式碼 (2636391) <br />
<br />
這個資訊安全更新可解決 Microsoft Windows 中兩項未公開報告的資訊安全風險。如果使用者開啟蓄意製作的媒體檔案，此資訊安全風險可能會允許遠端執行程式碼。成功利用資訊安全風險的攻擊者可以取得與本機使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-001">MS12-001</a></td>
<td style="border:1px solid black;">Windows 核心中的資訊安全風險可能允許部分安全功能被略過 (2644615) <br />
<br />
這個資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。此資訊安全風險可能讓攻擊者略過軟體應用程式中的 SafeSEH 安全性功能。然後攻擊者便可利用其他資訊安全風險，以利用結構化例外處理常式來執行任意程式碼。只有使用 Microsoft Visual C++ .NET 2003 編譯的軟體應用程式可用來利用這個資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
安全性功能略過</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-002">MS12-002</a></td>
<td style="border:1px solid black;">Windows 物件封裝程式中的資訊安全風險可能會允許遠端執行程式碼 (2603381) <br />
<br />
這個資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果使用者開啟與蓄意製作之可執行檔位於相同網路目錄的正常檔案，且該檔案內嵌封裝物件，則此資訊安全風險可能會允許遠端執行程式碼。成功利用此資訊安全風險的攻擊者可以取得與登入使用者相同的使用者權限。攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-003">MS12-003</a></td>
<td style="border:1px solid black;">Windows Client/Server Run-time Subsystem 中的資訊安全風險可能會允許權限提高 (2646524) <br />
<br />
此資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。對於所有受支援版本的 Windows XP、Windows Server 2003、Windows Vista 及 Windows Server 2008，此資訊安全更新的等級為「重要」。所有受支援版本的 Windows 7 和 Windows Server 2008 R2，皆不受此資訊安全風險影響。<br />
<br />
如果攻擊者登入受影響的系統，並執行蓄意製作的應用程式，則此資訊安全風險可能會允許權限提高。然後，攻擊者便可以取得受影響系統的完整控制權，使用完整的使用者權限安裝程式；檢視、變更或刪除資料；或建立新帳戶。只有在設定成中文、日文或韓文系統地區設定的系統上，此資訊安全風險才會遭到利用。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-005">MS12-005</a></td>
<td style="border:1px solid black;">Microsoft Windows 中的資訊安全風險可能會允許遠端執行程式碼 (2584146) <br />
<br />
這個資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。如果使用者開啟包含惡意內嵌 ClickOnce 應用程式之蓄意製作的 Microsoft Office 檔案，此資訊安全風險可能允許遠端執行程式碼。成功利用此資訊安全風險的攻擊者可以取得與本機使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-006">MS12-006</a></td>
<td style="border:1px solid black;">SSL/TLS 中的資訊安全風險可能會導致資訊洩漏 (2643584) <br />
<br />
此資訊安全更新可解決 SSL 3.0 和 TLS 1.0 中公開揭露的資訊安全風險。此資訊安全風險影響的是通訊協定本身，並非 Windows 作業系統所特有。如果攻擊者攔截受影響系統所服務的加密網站流量，則此資訊安全風險可能會導致資訊洩漏。TLS 1.1、TLS 1.2、和不使用 CBC 模式的所有加密套件不受影響。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
資訊洩漏</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/ms12-007">MS12-007</a></td>
<td style="border:1px solid black;">AntiXSS Library 中的資訊安全風險可能會導致資訊洩漏 (2607664) <br />
<br />
此資訊安全更新可解決 Microsoft Anti-Cross Site Scripting (AntiXSS) Library 中一項未公開報告的資訊安全風險。如果攻擊者將惡意指令碼傳給使用 AntiXSS Library 清理功能的網站，此資訊安全風險便可能允許資訊洩漏。該資訊遭到洩漏所產生的後果，將視資訊本身的性質而定。請注意，這個資訊安全風險不會直接允許攻擊者執行程式碼或提高攻擊者的使用者權限，但能用來產生可以進一步破壞受影響系統的資訊。只有使用 AntiXSS Library 清理模組的網站會受到此資訊安全風險影響。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
資訊洩漏</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft 開發者工具和軟體</td>
</tr>
</tbody>
</table>
  
資訊安全風險索引  
----------------
  
<span></span>
下表提供本月所述每個資訊安全風險的利用性評估。資訊安全風險皆根據公告編號和 CVE 編號依序列出。僅包含資訊安全公告中，嚴重性等級為「重大」或「重要」的資訊安全風險。
  
我該如何使用這個表格？
  
您可以運用此表格，針對您可能需要安裝的每一項資訊安全更新，瞭解資訊安全風險在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務的可能性。請根據您特定的組態設定，檢閱下列各項評估，決定部署本月份更新的優先次序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 資訊安全風險索引](http://technet.microsoft.com/security/cc998259.aspx)。
  
在下方欄位中，「最新軟體版本」意指受影響軟體，「較舊軟體版本」意指受影響軟體所有較舊的支援版本，如公告中的「受影響的軟體」或「不受影響的軟體」表格裡所示。
  
| 公告編號                                                                  | 資訊安全風險標題                           | CVE ID                                                                           | 最新軟體版本的資訊安全風險評估                                                                      | 較舊軟體版本的資訊安全風險評估                                                                      | 阻斷服務資訊安全風險評估 | 主要重點                                                       |  
|---------------------------------------------------------------------------|--------------------------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|--------------------------|----------------------------------------------------------------|  
| [MS12-001](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-001) | Windows 核心 SafeSEH 略過資訊安全風險      | [CVE-2012-0001](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0001) | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | 不適用                   | 這是一個安全性略過資訊安全風險。                               |  
| [MS12-002](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-002) | 物件封裝程式不安全可執行檔啟動資訊安全風險 | [CVE-2012-0009](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0009) | 不受影響                                                                                            | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | 不適用                   | (無)                                                           |  
| [MS12-003](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-003) | CSRSS 權限提高資訊安全風險                 | [CVE-2012-0005](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0005) | 不受影響                                                                                            | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | 永久                     | (無)                                                           |  
| [MS12-004](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-004) | MIDI 遠端執行程式碼資訊安全風險            | [CVE-2012-0003](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0003) | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | 不適用                   | (無)                                                           |  
| [MS12-004](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-004) | Direct Show 遠端執行程式碼資訊安全風險     | [CVE-2012-0004](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0004) | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | 不適用                   | (無)                                                           |  
| [MS12-005](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-005) | 組件執行資訊安全風險                       | [CVE-2012-0013](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0013) | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼     | 不適用                   | (無)                                                           |  
| [MS12-006](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-006) | SSL 和 TLS 通訊協定資訊安全風險            | [CVE-2011-3389](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3389) | [3](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | [3](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 不適用                   | 這是一個資訊洩漏資訊安全風險，且已連同有限的詳細資訊公開揭露。 |  
| [MS12-007](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-007) | AntiXSS Library 略過資訊安全風險           | [CVE-2012-0007](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0007) | [3](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | [3](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 不適用                   | 這是一個資訊洩漏的資訊安全風險。                               |
  
受影響的軟體及下載位置  
----------------------
  
<span></span>
下表依據主要的軟體類別和嚴重性依序列出公告。
  
我該如何使用這些表格？
  
請用這些表格來瞭解可能需要安裝的資訊安全更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的資訊安全更新。若軟體程式或更新出現在清單中，則相關可用軟體更新也會以超連結方式提供，也會列出軟體更新的嚴重性等級。
  
注意：一項資訊安全風險，可能需要安裝數個資訊安全更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
#### Windows 作業系統與元件

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="7">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-004](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-004)
</td>
<td style="border:1px solid black;">
[MS12-001](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-001)
</td>
<td style="border:1px solid black;">
[MS12-002](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-002)
</td>
<td style="border:1px solid black;">
[MS12-003](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-003)
</td>
<td style="border:1px solid black;">
[MS12-005](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-005)
</td>
<td style="border:1px solid black;">
[MS12-006](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-006)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[重大](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows Multimedia Library](http://www.microsoft.com/downloads/details.aspx?familyid=a142f7ba-4268-4453-a8eb-470213c028ac)  
(KB2598479)  
(重大)  
[Windows Multimedia Library](http://www.microsoft.com/downloads/details.aspx?familyid=89b23d72-410f-4133-9c14-24eb01e5a732)  
(KB2628259)  
(僅適用於 Windows XP Media Center Edition 2005 Service Pack 3)  
(重大)  
[DirectShow](http://www.microsoft.com/downloads/details.aspx?familyid=4b168ee8-eb15-4c2c-afb0-e63d62b4a6dc)  
(KB2631813)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=feaeda8c-84ee-47be-8c68-736f0e5b1fc7)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=cfc38dc2-c4c7-4a44-8e5a-b98bb9bc0396)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=1bcb1d1e-9261-4a36-9256-90d3df9bd4fb)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=fb0360b1-254c-4ecb-a36a-807cabfec1ab)  
(KB2585542)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Multimedia Library](http://www.microsoft.com/downloads/details.aspx?familyid=0928d720-ae88-40d6-b76f-636d67da8526)  
(KB2598479)  
(重大)  
[DirectShow](http://www.microsoft.com/downloads/details.aspx?familyid=13d74cc6-8d8e-45ea-8cdc-c15782f6626b)  
(KB2631813)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=46386269-6e37-4710-bfef-cedfe60d881c)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=211827f2-fe6a-4e16-a90c-0cc3b60a722d)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3956db98-88d9-49fc-be51-247b40bfc272)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2c687796-4c41-4d17-b738-511d2fbfc126)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=afe6b34d-21b1-4dfa-afa6-2c5c2a678e9e)  
(KB2585542)  
(重要)  
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=986f1156-0190-48c2-9f39-29cacb91f0f9)  
(KB2638806)  
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
公告 編號
</td>
<td style="border:1px solid black;">
[MS12-004](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-004)
</td>
<td style="border:1px solid black;">
[MS12-001](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-001)
</td>
<td style="border:1px solid black;">
[MS12-002](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-002)
</td>
<td style="border:1px solid black;">
[MS12-003](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-003)
</td>
<td style="border:1px solid black;">
[MS12-005](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-005)
</td>
<td style="border:1px solid black;">
[MS12-006](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-006)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
彙總 嚴重性等級
</td>
<td style="border:1px solid black;">
[重大](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Multimedia Library](http://www.microsoft.com/downloads/details.aspx?familyid=3c266dfb-630d-4f32-b2ca-63955279b6a9)  
(KB2598479)  
(重大)  
[DirectShow](http://www.microsoft.com/downloads/details.aspx?familyid=89ae6ed0-537f-421c-b755-ef28691abd88)  
(KB2631813)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9cdfc0fe-8f43-4e13-8a1f-2b48ff9ff472)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b8e46267-7988-4fbe-ae94-68b6fdb2e7d9)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=39f5f8fb-ee4d-4b7a-9cd7-3d1e9c8abd8c)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2c39be84-1eab-4794-b3ed-e529643aca21)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e2c503a5-3f15-4a77-9a05-9ea0fbaf4503)  
(KB2585542)  
(重要)  
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c23e7604-d489-4836-8b54-3b2b3d6a365c)  
(KB2638806)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Multimedia Library](http://www.microsoft.com/downloads/details.aspx?familyid=8dd1c882-4ed1-4e47-a017-7d162bd94194)  
(KB2598479)  
(重大)  
[DirectShow](http://www.microsoft.com/downloads/details.aspx?familyid=08be569c-e9d1-4fc5-8670-ebe9da0a2072)  
(KB2631813)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4e5783aa-6847-404c-9b75-621fa14ebbb8)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5975b01e-139b-4b9d-a0d5-a87a279bfea1)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e27d85f8-a285-4e95-85a0-0868286cc2b9)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3cf29dfd-239e-4707-92e6-952133c1c1c2)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2ad34496-40af-40cb-9f85-5d3c31543211)  
(KB2585542)  
(重要)  
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2f36e991-4e1a-4b8c-8cfb-e7f20d97cf0b)  
(KB2638806)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2
</td>
<td style="border:1px solid black;">
[Windows Multimedia Library](http://www.microsoft.com/downloads/details.aspx?familyid=3a9b09d6-7060-47ab-9f76-c3c5acb024e6)  
(KB2598479)  
(重大)  
[DirectShow](http://www.microsoft.com/downloads/details.aspx?familyid=3401ac20-3701-471f-9757-097a9402d761)  
(KB2631813)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=cdf8208c-d55b-428f-bdd3-26e291dfb08d)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=26079c35-4b96-42fc-ad47-138be25a6bf0)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=b69bd01d-9925-4ff1-bfeb-b4473631578c)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=623c1c7d-6902-4876-9614-1b6e1ef80831)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=56deb935-9226-49f8-b705-edb3d662d8aa)  
(KB2585542)  
(重要)  
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=2d72cf5a-cca7-4341-b862-017e3f34a3c9)  
(KB2638806)  
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
公告編號
</td>
<td style="border:1px solid black;">
[MS12-004](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-004)
</td>
<td style="border:1px solid black;">
[MS12-001](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-001)
</td>
<td style="border:1px solid black;">
[MS12-002](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-002)
</td>
<td style="border:1px solid black;">
[MS12-003](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-003)
</td>
<td style="border:1px solid black;">
[MS12-005](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-005)
</td>
<td style="border:1px solid black;">
[MS12-006](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-006)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[重大](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Multimedia Library](http://www.microsoft.com/downloads/details.aspx?familyid=99d9b9fc-ed37-4a32-a20d-6604a1b9c4ca)  
(KB2598479)  
(重大)  
[適用於 Windows Vista (32 位元版本) 的 Windows Media Center TV Pack](http://www.microsoft.com/downloads/details.aspx?familyid=f345e093-336d-4464-b7f8-a14398b62ebf)<sup>[1]</sup>
(KB2628642)  
(重要)  
[DirectShow](http://www.microsoft.com/downloads/details.aspx?familyid=4818059a-52ad-4c2e-9605-4e0f5d9da5ba)  
(KB2631813)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=44eeb0a2-ae17-4971-8a7e-e25b260c582c)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=73682d4b-3179-4488-8ba9-94ed68c4896b)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=038970b6-aeec-4e18-8dfe-887b260a7c87)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f9269bd6-8c4f-476e-8481-fc0de52a22e6)  
(KB2585542)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Multimedia Library](http://www.microsoft.com/downloads/details.aspx?familyid=44aa8d91-2b30-4191-8965-8aee2b860d50)  
(KB2598479)  
(重大)  
[適用於 Windows Vista (64 位元版本) 的 Windows Media Center TV Pack](http://www.microsoft.com/downloads/details.aspx?familyid=559d028f-9810-4c50-b65d-f567cbb15427)<sup>[1]</sup>
(KB2628642)  
(重要)  
[DirectShow](http://www.microsoft.com/downloads/details.aspx?familyid=13cc2519-860d-4c64-b7f8-8f9c0bdaefcf)  
(KB2631813)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=79ceba86-59a1-4138-a5de-8df20ad81b02)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b5c33025-13d9-43d2-a415-a8a4d683a821)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=23abeb12-f2fe-43fd-9c4a-4d3d244832f8)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0403c753-d4fa-4e3d-a61b-7f816f5c352b)  
(KB2585542)  
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
公告編號
</td>
<td style="border:1px solid black;">
[MS12-004](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-004)
</td>
<td style="border:1px solid black;">
[MS12-001](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-001)
</td>
<td style="border:1px solid black;">
[MS12-002](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-002)
</td>
<td style="border:1px solid black;">
[MS12-003](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-003)
</td>
<td style="border:1px solid black;">
[MS12-005](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-005)
</td>
<td style="border:1px solid black;">
[MS12-006](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-006)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[重大](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Multimedia Library](http://www.microsoft.com/downloads/details.aspx?familyid=787e6285-3ba5-4aae-9d8d-e3c1eca3b35d)\*  
(KB2598479)  
(重大)  
[DirectShow](http://www.microsoft.com/downloads/details.aspx?familyid=92df13c1-fdf6-4602-acb2-e634a1bcd9da)\*\*  
(KB2631813)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5ab87c6c-5802-4454-bce4-12501e5b816d)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=fbf119cf-a8ed-4266-a673-442149992f7c)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d089d9cb-382c-4e64-94c5-69b9864010b1)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2fe2f398-433f-4338-a273-813185b43ea8)\*  
(KB2585542)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Multimedia Library](http://www.microsoft.com/downloads/details.aspx?familyid=9eff12b2-70a4-452b-b6bc-0d83f2edcf6c)\*  
(KB2598479)  
(重大)  
[DirectShow](http://www.microsoft.com/downloads/details.aspx?familyid=7ff10d7f-26a6-403a-a4b7-7aff55e2fa16)\*\*  
(KB2631813)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=726ff17e-ac90-4832-91e7-46f71ad2f868)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e8e68f89-27f4-4142-94ca-58f086a98157)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1ac8a368-4298-4c1d-9cfd-924d6df563af)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f54ac30d-8e41-4df9-bd43-db6742a24d4c)\*  
(KB2585542)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Multimedia Library](http://www.microsoft.com/downloads/details.aspx?familyid=4e2edb23-7f4e-4fe4-848c-1d744e0dce9f)  
(KB2598479)  
(重大)  
[DirectShow](http://www.microsoft.com/downloads/details.aspx?familyid=5e0394c9-3de4-46f6-ae7f-18d5a555532e)  
(KB2631813)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ba2c3d57-1bdd-44f2-9233-86c7ea6f0ddb)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=fc6491e8-6c3e-43a1-bc56-16c9a2fd2749)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3e08b242-2516-4cf6-b38e-35ec2b8b788d)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3979db3b-4961-4df8-84a4-1f26672b127c)  
(KB2585542)  
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
公告編號
</td>
<td style="border:1px solid black;">
[MS12-004](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-004)
</td>
<td style="border:1px solid black;">
[MS12-001](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-001)
</td>
<td style="border:1px solid black;">
[MS12-002](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-002)
</td>
<td style="border:1px solid black;">
[MS12-003](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-003)
</td>
<td style="border:1px solid black;">
[MS12-005](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-005)
</td>
<td style="border:1px solid black;">
[MS12-006](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-006)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
[DirectShow](http://www.microsoft.com/downloads/details.aspx?familyid=d736daf8-db6d-485f-b0cb-7f2d8c86f9a2)  
(KB2631813)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=0ee22036-b7f4-40f5-8f40-a77e8faf48b2)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7422605b-7a02-4161-b7f8-92b3ccffef64)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=0f433f2c-c61d-461d-af9c-0145af4b72ab)  
(KB2585542)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
[DirectShow](http://www.microsoft.com/downloads/details.aspx?familyid=21b37775-3e7b-462d-8234-7c47d52daef9)  
(KB2631813)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7444e20c-9821-4c91-9779-2728c537dd6a)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=4ba46bc7-af7a-445a-84f2-b0c13674409b)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=0839fec0-b6a7-4e47-9da3-2caef44a7df4)  
(KB2585542)  
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
公告編號
</td>
<td style="border:1px solid black;">
[MS12-004](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-004)
</td>
<td style="border:1px solid black;">
[MS12-001](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-001)
</td>
<td style="border:1px solid black;">
[MS12-002](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-002)
</td>
<td style="border:1px solid black;">
[MS12-003](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-003)
</td>
<td style="border:1px solid black;">
[MS12-005](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-005)
</td>
<td style="border:1px solid black;">
[MS12-006](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-006)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
[DirectShow](http://www.microsoft.com/downloads/details.aspx?familyid=355c980d-ec2e-4b2d-a7d4-2e3dbd3a0dde)\*\*  
(KB2631813)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=4c73a16d-e9fa-48de-9dca-a6360ce3d029)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=db3a4814-a409-4def-944d-4eaa540b83b0)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=34542a5a-88df-4a07-b1ed-d4c845502cd8)\*  
(KB2585542)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 和適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
[DirectShow](http://www.microsoft.com/downloads/details.aspx?familyid=d4b2389e-fd9f-47c7-9afd-4077f5632c21)  
(KB2631813)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2 和適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1cc14ee8-f035-4bfc-bf38-33c6b9a2e776)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2 和適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=2101663a-ed3d-4850-b79a-16960ab56b45)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2 和適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=fe661936-06e1-45d3-89f6-1093504496a7)  
(KB2585542)  
(重要)
</td>
</tr>
</table>
 
Windows Server 2008 和 Windows Server 2008 R2 注意事項

\*Server Core 安裝會受影響。無論上述受支援的 Windows Server 2008 或 Windows Server 2008 R2 版本是否使用 Server Core 安裝選項安裝，這個更新均以相同的嚴重性等級套用。如需此安裝選項的詳細資訊，請參閱 TechNet 文章：[管理 Server Core 安裝](http://technet.microsoft.com/zh-tw/library/ee441255(ws.10).aspx) (英文) 和[維護 Server Core 安裝](http://technet.microsoft.com/zh-tw/library/ff698994(ws.10).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 和 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

\*\*Server Core 安裝不受影響。如果 Windows Server 2008 或 Windows Server 2008 R2 是使用 Server Core 安裝選項所安裝，則這項更新解決的資訊安全風險並不會影響受支援的 Windows Server 2008 或 Windows Server 2008 R2。如需此安裝選項的詳細資訊，請參閱 TechNet 文章：[管理 Server Core 安裝](http://technet.microsoft.com/zh-tw/library/ee441255(ws.10).aspx) (英文) 和[維護 Server Core 安裝](http://technet.microsoft.com/zh-tw/library/ff698994(ws.10).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 和 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

MS12-004 注意事項

<sup>[1]</sup>唯有在原始設備廠商 (OEM) 安裝的 Home Premium 和 Ultimate 版的 Windows Vista 上，適用於 Windows Vista 的 Windows Media Center TV Pack 才以選用元件的方式提供使用。已安裝這個選用元件的客戶應安裝所有適用於其 Windows Vista 版本的更新。為符合最佳作法，Microsoft 建議先安裝適用的作業系統更新 (KB2598479 和 KB2631813)，再安裝 Windows Media Center TV Pack 更新 (KB2628642)。

#### Microsoft 開發者工具和軟體

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Anti-Cross Site Scripting Library
</th>
</tr>
<tr>
<td style="border:1px solid black;">
公告編號
</td>
<td style="border:1px solid black;">
[MS12-007](http://technet.microsoft.com/zh-tw/security/bulletin/ms12-007)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
彙總嚴重性等級
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Anti-Cross Site Scripting Library V3.x 和 Microsoft Anti-Cross Site Scripting Library V4.0
</td>
<td style="border:1px solid black;">
[Microsoft Anti-Cross Site Scripting Library V3.x 和 Microsoft Anti-Cross Site Scripting Library V4.0](http://www.microsoft.com/downloads/details.aspx?familyid=b3ef05ce-70fe-4f25-9aee-cb7a42a53d11)<sup>[1]</sup><sup>[2]</sup>
</td>
</tr>
</table>
 
MS12-007 注意事項

<sup>[1]</sup> 此下載會將 Microsoft Anti-Cross Site Scripting (AntiXSS) Library 升級為不受資訊安全風險影響的新版 Microsoft Anti-Cross Site Scripting Library。

<sup>[2]</sup>此升級程式僅可以從 Microsoft 下載中心取得。

偵測與部署工具及指南
--------------------

<span></span>
資訊安全中心

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和資訊安全更新。如需更多資訊，請參閱 [TechNet 更新管理中心](http://technet.microsoft.com/zh-tw/updatemanagement/default.aspx) (英文)。[TechNet 資訊安全技術中心](http://technet.microsoft.com/zh-tw/security/default.aspx)提供 Microsoft 產品安全性的其他資訊。消費者可以造訪[在家上網的安全性](http://technet.microsoft.com/zh-tw/security/default.aspx)網站，只要按一下 \[最新資訊安全更新\] 即可在此網站取得此資訊。

資訊安全更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 以及 [Windows Update](http://update.microsoft.com/windowsupdate/v6/default.aspx) 取得。資訊安全更新也可以從 [Microsoft 下載中心](http://www.microsoft.com/download/en/default.aspx)取得。您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。

對於 Microsoft Office for Mac 的客戶，Microsoft AutoUpdate for Mac 可協助您保持最新的 Microsoft 軟體。如需使用 Microsoft AutoUpdate for Mac 的詳細資訊，請參閱[自動檢查軟體更新](http://mac2.microsoft.com/help/office/14/zh-tw/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea) (英文)。

最後，您可以從 [Microsoft Update Catalog](http://catalog.update.microsoft.com/v7/site/) 下載資訊安全更新。Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括資訊安全更新、驅動程式和 Service Pack。只要以資訊安全公告編號 (例如：MS07-036) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](http://catalog.update.microsoft.com/v7/site/faq.aspx)。

偵測與部署指南

Microsoft 針對資訊安全更新提供偵測和部署指南。本指南所含之建議和資訊，能幫助 IT 專業人員瞭解如何使用用於資訊安全更新的偵測和部署的各種工具。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 961747](http://support.microsoft.com/kb/961747?ln=zh-tw)。

Microsoft Baseline Security Analyzer

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少資訊安全更新以及一般資訊安全設定錯誤的狀況。如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](http://technet.microsoft.com/zh-tw/security/cc184924.aspx)。

Windows Server Update Services

透過 Windows Server Update Services (WSUS)，系統管理員可迅速而可靠地將 Microsoft Windows 2000 作業系統及更新版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 適用的最新重大更新與資訊安全更新部署到 Microsoft Windows 2000 及更新版本的作業系統中。

如需更多關於利用 Windows Server Update Services 部署資訊安全更新的資訊，請造訪 [Windows Server Update Services](http://technet.microsoft.com/zh-tw/wsus/default.aspx) (英文)。

System Center Configuration Manager 2007

Configuration Manager 2007 軟體更新管理可簡化遞送和管理企業中 IT 系統更新的繁複作業。IT 系統管理員可以使用 Configuration Manager 2007 遞送 Microsoft 產品更新給各種裝置，包括桌上型電腦、筆記型電腦、伺服器及行動裝置。

Configuration Manager 2007 中的自動資訊安全風險評估會找出更新需求並報告建議動作。Configuration Manager 2007 中的軟體更新管理是建置在 Microsoft Windows Software Update Services (WSUS) 上，經過時間考驗，為全球 IT 系統管理員所熟悉的更新基礎架構。如需更多有關系統管理員如何使用 Configuration Manager 2007 來部署更新的資訊，請參閱[軟體更新管理](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx) (英文)。如需更多有關 Configuration Manager 的資訊，請造訪 [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx)。

Systems Management Server 2003

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。透過 SMS，系統管理員能判斷有哪些 Windows 系統需要資訊安全更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。

注意：System Management Server 2003 自 2010 年 1 月 12 日起不受主流支援。如需更多有關產品生命週期的資訊，請造訪 [Microsoft 支援週期](http://support.microsoft.com/common/international.aspx?rdpath=dm;zh-tw;lifecycle?ln=zh-tw)。現已推出新版的 SMS：System Center Configuration Manager 2007；請參閱前段的＜System Center Configuration Manager 2007＞一節。

如需更多有關系統管理員如何使用 SMS 2003 來部署資訊安全更新的資訊，請參閱 [Microsoft Systems Management Server 2003 的案例與程序： 軟體發佈和補充程式管理](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en) (英文)。如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server 技術中心 (TechCenter)](http://technet.microsoft.com/zh-tw/systemcenter/bb545936.aspx)。

注意 ：SMS 使用 Microsoft Baseline Security Analyzer 提供廣泛的資訊安全公告更新偵測與部署支援。不過這些工具可能無法偵測部分的軟體更新。在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](http://technet.microsoft.com/zh-tw/library/cc917507.aspx) (英文)。某些資訊安全更新程式在電腦重新啟動之後，會需要系統管理員的權限。系統管理員可使用 Elevated Rights Deployment Tool (隨附於 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)) 來安裝這些更新。

Update Compatibility Evaluator 和 Application Compatibility Toolkit

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。這可能會觸發不相容性，而拉長部署資訊安全更新的時間。您可以使用 [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 隨附的 [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 元件，針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Microsoft Windows Vista、Windows Update、Microsoft 資訊安全更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非資訊安全更新

如需在 Windows Update 和 Microsoft Update 上發行的非資訊安全更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](http://support.microsoft.com/kb/894199?ln=zh-tw)
-   ： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](http://technet.microsoft.com/zh-tw/wsus/bb456965.aspx)
-   。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的資訊安全保護，Microsoft 將在每月發行資訊安全更新之前，提前向重要資訊安全軟體提供者提供資訊安全風險資訊。資訊安全軟體提供者可利用此資訊安全風險資訊，透過其資訊安全軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://www.microsoft.com/security/msrc/collaboration/mapp.aspx) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 安全性策略與社群

更新程式管理策略

[更新管理資訊安全指南](http://technet.microsoft.com/zh-tw/library/bb466251(zh-tw).aspx) (英文) 提供您有關套用資訊安全更新的 Microsoft 最佳實作建議的其他資訊。

取得其他資訊安全更新

其他資訊安全問題的更新可由下列位置取得：

-   資訊安全更新可以從 [Microsoft 下載中心](http://www.microsoft.com/download/en/default.aspx)取得， 您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。
-   消費性平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的資訊安全更新。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](http://support.microsoft.com/kb/913086?ln=zh-tw)。

IT 專業人員資訊安全社群

在 [IT 專業人員安全性社群](http://technet.microsoft.com/zh-tw/security/cc136632.aspx)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](http://technet.microsoft.com/zh-tw/security/bulletin/policy)下列人士協助我們一同保護我們的客戶：

-   感謝 [Accuvant LABS](http://www.accuvant.com/)的 Joshua J. Drake 回報 MS12-001 中描述的一項問題
-   感謝 Parvez Anwar 與 [Secunia Research](http://secunia.com/) 合作，回報 MS12-002 中描述的一項問題
-   感謝 [Shenzhen Jowto Research Dep](http://www.jowto.com/) 的 Kang Wu 回報 MS12-003 中描述的一項問題
-   感謝 [IBM Security System's X-Force Research](http://xforce.iss.net/) 的 Shane Garrett 回報 MS12-004 中描述的一項問題
-   感謝 [Google Inc.](http://www.google.com/) 的 Neel Mehta 回報 MS12-004 中描述的一項問題
-   感謝 Yorick Koster 與 [Beyond Security 的 SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html) 計畫合作，回報 MS12-005 中描述的一項問題
-   感謝 [IBM Rational Application Security](http://blog.watchfire.com/) 的 Adi Cohen，回報 MS12-007 中描述的一項問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 支援週期](http://support.microsoft.com/default.aspx?scid=fh;%5bln%5d;lifecycle)。
-   美國及加拿大地區客戶可洽詢[資訊安全支援](https://consumersecuritysupport.microsoft.com/default.aspx?mkt=zh-tw&st=1&wfxredirect=1)或 1-866-PCSAFETY (1-866-727-2338) 以取得技術支援。與資訊安全更新有關的支援電話不另外收費。如需更多可用支援選項的資訊，請參閱 [Microsoft 技術支援](http://support.microsoft.com/?ln=zh-tw)。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。與資訊安全更新有關的支援電話不另外收費。如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[國際化支援](http://support.microsoft.com/common/international.aspx)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2012 年 1 月 11 日)： 公告摘要發行。
-   V2.0 (2012 年 1 月 12 日)： 針對 MS12-003，在 CVE-2012-0005 的＜資訊安全風險入侵指數＞中更正最新軟體版本的資訊安全風險評估。針對 MS12-007，修訂以宣布重新發行公告。如需更多資訊，請參閱 MS12-007 公告。
-   V2.1 (2012 年 1 月 28 日)： 對於 MS12-004，更正針對所有支援 Windows XP、Windows Server 2003、Windows Vista 和 Windows Server 2008 版本所列之 KB2631813 更新程式封裝的彙總嚴重性等級。請參閱 MS12-004 公告以獲得詳細資訊。

*Built at 2014-04-18T01:50:00Z-07:00*
