---
TOCTitle: 'MS13-MAR'
Title: 2013 年 3 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms13-mar'
ms:contentKeyID: 61237746
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms13-mar(v=Security.10)'
---

2013 年 3 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2013年3月13日 | 更新: 2013年4月10日

**版本:** 1.1

此公告摘要列出 2013 年 3 月份發行之資訊安全公告。

發行 2013 年 3 月份資訊安全公告之後，此公告摘要將取代原先於 2013 年 3 月 7 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 資訊安全公告預先通知](https://technet.microsoft.com/zh-tw/security/gg309152.aspx)。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術資訊安全通知](https://technet.microsoft.com/zh-tw/security/dd252948.aspx)。

Microsoft 將利用網路廣播於 2013 年 3 月 13 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。[立即註冊參加 3 月份資訊安全公告網路廣播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538636&culture=en-us)。在這個日期後，此網路廣播將可[隨選取得](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538636&culture=en-us)。

Microsoft 也會提供資訊協助客戶排定每月資訊安全更新以及任何非資訊安全更新的優先順序，其中這些非資訊安全更新的發行日期與每月資訊安全更新的發行日期相同。請參閱＜其他資訊＞一節。

### 公告資訊

#### 提要

下表依嚴重性摘要說明本月份資訊安全公告。

如需受影響的軟體之詳細資料，請參閱下節＜受影響的軟體及下載位置＞。

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-021">MS13-021</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer</strong> <strong>積存資訊安全更新</strong> <strong>(2809289)  <br />
<br />
</strong>這個資訊安全更新可解決 Internet Explorer 中八項未公開報告的資訊安全風險，以及一項公開揭露的資訊安全風險。最嚴重的資訊安全風險可能會在使用者以 Internet Explorer 檢視蓄意製作的網頁時，允許遠端執行程式碼。成功利用這些資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/rating">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-022">MS13-022</a></td>
<td style="border:1px solid black;"><strong>Silverlight</strong> <strong>中的資訊安全風險可能會允許遠端執行程式碼</strong> <strong>(2814124)</strong> <br />
<br />
這個資訊安全更新可解決 Microsoft Silverlight 中一項未公開報告的資訊安全風險。如果攻擊者架設一個網站，並在其中包含蓄意製作的 Silverlight 應用程式來利用此資訊安全風險，然後引誘使用者檢視此網站，此資訊安全風險可能會允許遠端執行程式碼。攻擊者也可能利用受侵害的網站，以及接受或裝載使用者提供內容或廣告的網站。這類網站可能含有蓄意製作並可利用此資訊安全風險的內容。但是，在所有情況下，攻擊者都無法強迫使用者造訪網站， 而一般的做法是讓使用者點選電子郵件訊息或 Instant Messenger 訊息中連往攻擊者網站的連結，以引誘使用者造訪網站。攻擊者也可能使用橫幅廣告或其他方式來顯示蓄意製作的網頁內容，以便將內容傳遞到受影響的系統。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/rating">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">不需要重新開機</td>
<td style="border:1px solid black;">Microsoft Silverlight</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-023">MS13-023</a></td>
<td style="border:1px solid black;"><strong>Microsoft Visio Viewer 2010</strong> <strong>中的資訊安全風險可能會允許遠端執行程式碼</strong> <strong>(2801261)  <br />
<br />
</strong>此資訊安全更新可解決 Microsoft Office 中一項未公開報告的資訊安全風險。如果使用者開啟蓄意製作的 Visio 檔案，此資訊安全風險可能會允許遠端執行程式碼。成功利用此資訊安全風險的攻擊者可以取得與目前使用者相同的使用者權限。系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/rating">重大</a> <br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-024">MS13-024</a></td>
<td style="border:1px solid black;"><strong>SharePoint</strong> <strong>中的資訊安全風險可能會允許提高權限</strong> <strong>(2780176)  <br />
<br />
</strong>本資訊安全更新可解決 Microsoft SharePoint 及 Microsoft SharePoint Foundation 中四項未公開報告的資訊安全風險。如果使用者點選會將使用者帶到目標 SharePoint 網站之蓄意製作的 URL，則最嚴重的資訊安全風險可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/rating">重大</a> <br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office、Microsoft 伺服器軟體</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-025">MS13-025</a></td>
<td style="border:1px solid black;"><strong>Microsoft OneNote</strong> <strong>中的資訊安全風險可能會允許資訊洩漏</strong> <strong>(2816264)  <br />
<br />
</strong>此資訊安全更新可解決 Microsoft OneNote 中一項未公開報告的資訊安全風險。如果攻擊者引誘使用者開啟蓄意製作的 OneNote 檔案，則此資訊安全風險可能會允許資訊洩漏。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
資訊洩漏</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-026">MS13-026</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office</strong> for Mac 中的<strong>資訊安全風險可能允許資訊洩漏</strong> <strong>(2813682)  <br />
<br />
</strong>這個資訊安全更新可解決 Microsoft Office for Mac 中一項未公開報告的資訊安全風險。如果使用者開啟蓄意製作的電子郵件訊息，則此資訊安全風險便可能允許資訊洩漏。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
資訊洩漏</td>
<td style="border:1px solid black;">不需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/ms13-027">MS13-027</a></td>
<td style="border:1px solid black;"><strong>核心模式驅動程式中的資訊安全風險可能會允許權限提高</strong> <strong>(2807986)  <br />
<br />
</strong>這個資訊安全更新可解決 Microsoft Windows 中三項未公開報告的資訊安全風險。如果攻擊者能存取系統，則這些資訊安全風險可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/zh-tw/security/bulletin/rating">重要</a> <br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
資訊安全風險入侵指數  
--------------------
  

下表提供本月所述每個資訊安全風險的利用性評估。資訊安全風險皆根據公告編號和 CVE 編號依序列出。僅包含資訊安全公告中，嚴重性等級為「重大」或「重要」的資訊安全風險。
  
**我該如何使用這個表格？**
  
您可以運用此表格，針對您可能需要安裝的每一項資訊安全更新，瞭解資訊安全風險在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務 (DoS) 的可能性。請根據您特定的組態設定，檢閱下列各項評估，決定部署本月份更新的優先次序。如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 資訊安全風險索引](https://technet.microsoft.com/security/cc998259)。
  
在下方欄位中，「最新軟體版本」意指受影響軟體，「較舊軟體版本」意指受影響軟體所有較舊的支援版本，如公告中的「受影響的軟體」或「不受影響的軟體」表格裡所示。
  
| 公告編號                                                                  | 資訊安全風險標題                                                | CVE ID                                                                           | 最新軟體版本的資訊安全風險評估                                                                  | 較舊軟體版本的資訊安全風險評估                                                                  | 阻斷服務 (DoS) 資訊安全風險評估 | 主要重點                                |  
|---------------------------------------------------------------------------|-----------------------------------------------------------------|----------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|---------------------------------|-----------------------------------------|  
| [MS13-021](https://technet.microsoft.com/zh-tw/error.htm)                  | Internet Explorer OnResize 釋放後使用資訊安全風險               | [CVE-2013-0087](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0087) | [1](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼 | [1](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼 | 不適用                          | (無)                                    |  
| [MS13-021](https://technet.microsoft.com/zh-tw/error.htm)                  | Internet Explorer saveHistory 釋放後使用資訊安全風險            | [CVE-2013-0088](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0088) | [1](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼 | [1](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼 | 不適用                          | (無)                                    |  
| [MS13-021](https://technet.microsoft.com/zh-tw/error.htm)                  | Internet Explorer CMarkupBehaviorContext 釋放後使用資訊安全風險 | [CVE-2013-0089](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0089) | [1](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼 | [1](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼 | 不適用                          | (無)                                    |  
| [MS13-021](https://technet.microsoft.com/zh-tw/error.htm)                  | Internet Explorer CCaret 釋放後使用資訊安全風險                 | [CVE-2013-0090](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0090) | [2](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 很難建立可利用此漏洞的程式碼   | [1](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼 | 不適用                          | (無)                                    |  
| [MS13-021](https://technet.microsoft.com/zh-tw/error.htm)                  | Internet Explorer CElement 釋放後使用資訊安全風險               | [CVE-2013-0091](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0091) | 不受影響                                                                                        | [1](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼 | 不適用                          | (無)                                    |  
| [MS13-021](https://technet.microsoft.com/zh-tw/error.htm)                  | Internet Explorer GetMarkupPtr 釋放後使用資訊安全風險           | [CVE-2013-0092](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0092) | [1](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼 | [1](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼 | 不適用                          | (無)                                    |  
| [MS13-021](https://technet.microsoft.com/zh-tw/error.htm)                  | Internet Explorer onBeforeCopy 釋放後使用資訊安全風險           | [CVE-2013-0093](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0093) | [1](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼 | [1](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼 | 不適用                          | (無)                                    |  
| [MS13-021](https://technet.microsoft.com/zh-tw/error.htm)                  | Internet Explorer removeChild 釋放後使用資訊安全風險            | [CVE-2013-0094](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0094) | [1](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼 | [1](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼 | 不適用                          | (無)                                    |  
| [MS13-021](https://technet.microsoft.com/zh-tw/error.htm)                  | Internet Explorer CTreeNode 釋放後使用資訊安全風險              | [CVE-2013-1288](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1288) | 不受影響                                                                                        | [1](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼 | 不適用                          | 此資訊安全風險已經遭到公開揭發。        |  
| [MS13-022](https://technet.microsoft.com/zh-tw/error.htm)                  | Silverlight 雙重解除參照資訊安全風險                            | [CVE-2013-0074](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0074) | [1](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼 | 不適用                                                                                          | 不適用                          | (無)                                    |  
| [MS13-023](https://technet.microsoft.com/zh-tw/error.htm)                  | Visio Viewer 樹狀結構物件類型混淆資訊安全風險                   | [CVE-2013-0079](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0079) | 不受影響                                                                                        | [2](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 很難建立可利用此漏洞的程式碼   | 不適用                          | (無)                                    |  
| [MS13-024](https://technet.microsoft.com/zh-tw/error.htm)                  | 回呼函數資訊安全風險                                            | [CVE-2013-0080](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0080) | 不受影響                                                                                        | [1](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼 | 不適用                          | (無)                                    |  
| [MS13-024](https://technet.microsoft.com/zh-tw/error.htm)                  | SharePoint XSS 資訊安全風險                                     | [CVE-2013-0083](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0083) | 不受影響                                                                                        | [1](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼 | 不適用                          | (無)                                    |  
| [MS13-024](https://technet.microsoft.com/zh-tw/error.htm)                  | SharePoint 目錄周遊資訊安全風險                                 | [CVE-2013-0084](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0084) | 不受影響                                                                                        | [1](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼 | 不適用                          | (無)                                    |  
| [MS13-024](https://technet.microsoft.com/zh-tw/error.htm)                  | 緩衝區溢位資訊安全風險                                          | [CVE-2013-0085](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0085) | 不受影響                                                                                        | [3](https://technet.microsoft.com/security/cc998259) - 不太可能撰寫出可利用此漏洞的程式碼        | 暫時                            | 這是一項阻斷服務 (DoS) 的資訊安全風險。 |  
| [MS13-025](https://technet.microsoft.com/zh-tw/error.htm)                  | 緩衝區大小驗證資訊安全風險                                      | [CVE-2013-0086](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0086) | 不受影響                                                                                        | [3](https://technet.microsoft.com/security/cc998259) - 不太可能撰寫出可利用此漏洞的程式碼        | 不適用                          | 這是一個資訊洩漏的資訊安全風險。        |  
| [MS13-026](https://technet.microsoft.com/zh-tw/error.htm)                  | 非預期內容載入資訊安全風險                                      | [CVE-2013-0095](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0095) | [3](https://technet.microsoft.com/security/cc998259) - 不太可能撰寫出可利用此漏洞的程式碼        | [3](https://technet.microsoft.com/security/cc998259) - 不太可能撰寫出可利用此漏洞的程式碼        | 不適用                          | 這是一個資訊洩漏的資訊安全風險。        |  
| [MS13-027](https://technet.microsoft.com/zh-tw/error.htm)                  | Windows USB 描述元資訊安全風險                                  | [CVE-2013-1285](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1285) | [1](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼 | [1](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼 | 永久                            | (無)                                    |  
| [MS13-027](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-027) | Windows USB 描述元資訊安全風險                                  | [CVE-2013-1286](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1286) | [1](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼 | [1](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼 | 永久                            | (無)                                    |  
| [MS13-027](https://technet.microsoft.com/zh-tw/error.htm)                  | Windows USB 描述元資訊安全風險                                  | [CVE-2013-1287](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1287) | [1](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼 | [1](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可利用此漏洞的程式碼 | 永久                            | (無)                                    |
  
受影響的軟體及下載位置  
----------------------
  

下表依據主要的軟體類別和嚴重性依序列出公告。
  
**我該如何使用這些表格？**
  
請用這些表格來瞭解可能需要安裝的資訊安全更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的資訊安全更新。若軟體程式或更新出現在清單中，則相關可用軟體更新也會以超連結方式提供，也會列出軟體更新的嚴重性等級。
  
**注意**：一項資訊安全風險，可能需要安裝數個資訊安全更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
#### Windows 作業系統與元件

<p></p>
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
[**MS13-021**](https://technet.microsoft.com/zh-tw/error.htm)
</td>
<td style="border:1px solid black;">
[**MS13-027**](https://technet.microsoft.com/zh-tw/error.htm)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=ace6994d-7482-40de-84ad-a87853a35860)   
(2809289)  
(重大)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=50c59794-4ec7-404a-b316-dae314521ebb)  
(2809289)  
(重大)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=7e5d96a7-d9f5-4832-b4f9-b6e0148c655b)  
(2809289)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=ba528d03-b0a6-40a5-a6bd-13c062a8a877)   
(2807986)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=795cef4e-9c01-447f-916c-e52e69eca4a3)   
(2809289)  
(重大)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=16993a2c-1fe1-4c1e-bcd9-db1a7dd4a058)  
(2809289)  
(重大)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=66a08524-883d-4d67-82cc-2c0f55c56b31)  
(2809289)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4f8a48d4-b1bb-465c-a232-d29fe94d1429)   
(2807986)  
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
[**MS13-021**](https://technet.microsoft.com/zh-tw/error.htm)
</td>
<td style="border:1px solid black;">
[**MS13-027**](https://technet.microsoft.com/zh-tw/error.htm)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=e3c911b3-7fdd-4105-a20a-eef65b0908e3)   
(2809289)  
(中度)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=0f58d63e-0d2c-41d2-9792-edbb2f4a539d)  
(2809289)  
(中度)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=e6b63da9-a414-40ee-b877-4fb0d62bacba)  
(2809289)  
(中度)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=835651b7-79fb-4d50-b48e-f02173062253)   
(2807986)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=eaf2c568-089a-4c2f-bca6-da83f7332de9)   
(2809289)  
(中度)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=5a18b139-2773-44c8-85f9-8dce24249e71)  
(2809289)  
(中度)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d6feba92-f014-4521-b6c4-7f5f358a3ce3)  
(2809289)  
(中度)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9d5f1ed1-f33b-4c90-9b29-ee8ac587d31b)   
(2807986)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=088fd3ec-62e1-4737-8132-6b51219ed37f)   
(2809289)  
(中度)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=799748d8-056d-4139-86e1-9bd0cb0151b4)  
(2809289)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=28d441e7-abcf-4cc9-84e0-572e5b79aab7)   
(2807986)  
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
[**MS13-021**](https://technet.microsoft.com/zh-tw/error.htm)
</td>
<td style="border:1px solid black;">
[**MS13-027**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-027)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=0bf77905-1199-4219-a67d-1e9ad3f63757)  
(2809289)  
(重大)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=76e328f8-4f86-4e50-b7e0-22db0385ab01)  
(2809289)  
(重大)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=c26f74fc-e224-4533-a4e3-b52125dca5cd)   
(2809289)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b8472bc7-9e20-4238-adcf-a1e1a91687a1)   
(2807986)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=7b652bb4-7a0a-437b-bcc5-ebbbb820c559)  
(2809289)  
(重大)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=67b09398-ceb6-403c-bba4-261d9d9dea98)  
(2809289)  
(重大)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=3f1795a5-4376-4929-8748-743840ec2154)   
(2809289)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e412c54a-a93d-4c5b-9b13-40b59d1dff35)   
(2807986)  
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
[**MS13-021**](https://technet.microsoft.com/zh-tw/error.htm)
</td>
<td style="border:1px solid black;">
[**MS13-027**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-027)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=0303fcb1-34d5-47da-b6ee-18222fe3235a)  
(2809289)  
(中度)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=337068a5-9281-4db6-9ff1-5282cdfa0763)  
(2809289)  
(中度)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=c672c196-5072-468c-8d88-34534fa219fd)   
(2809289)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f1ca4fe0-3ee3-4162-a9fa-48c54fc8b08e)   
(2807986)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=f22b9327-1430-44cb-a609-ea1bb9b7b8f8)  
(2809289)  
(中度)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=0496cbfe-77d2-4de6-b78d-937225dc8974)  
(2809289)  
(中度)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=5c40f237-b4c8-41eb-a649-baad46dfa13c)   
(2809289)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8b61f3e5-0cf9-4eab-8a59-829957135dd6)   
(2807986)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=09e4832c-b95e-4581-a73b-49cb6a60c1df)  
(2809289)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=af2e8e83-fb8f-4ba5-83ec-8bd4347a5fe6)   
(2807986)  
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
[**MS13-021**](https://technet.microsoft.com/zh-tw/error.htm)
</td>
<td style="border:1px solid black;">
[**MS13-027**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-027)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=b07b63d5-925d-4c4f-ae19-18a9b141eaa0)  
(2809289)  
(重大)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=54c619b7-e156-4f07-a90e-56ed9a618085)   
(2809289)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=c72f78be-e6a8-43b4-9303-7c93dd11d502)   
(2807986)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=b07b63d5-925d-4c4f-ae19-18a9b141eaa0)  
(2809289)  
(重大)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=54c619b7-e156-4f07-a90e-56ed9a618085)   
(2809289)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=c72f78be-e6a8-43b4-9303-7c93dd11d502)   
(2807986)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=610da6c6-e8a9-4726-ae54-11f01fb5ab2d)  
(2809289)  
(重大)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=86f2a369-d71d-4a36-95ed-d5be89cbbbae)   
(2809289)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=6a8a22d6-0e6e-4d3b-afd0-d4841274ade0)   
(2807986)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=610da6c6-e8a9-4726-ae54-11f01fb5ab2d)  
(2809289)  
(重大)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=86f2a369-d71d-4a36-95ed-d5be89cbbbae)   
(2809289)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6a8a22d6-0e6e-4d3b-afd0-d4841274ade0)   
(2807986)  
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
[**MS13-021**](https://technet.microsoft.com/zh-tw/error.htm)
</td>
<td style="border:1px solid black;">
[**MS13-027**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-027)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=cf5f65e1-93ae-4ec3-84d2-eb017efdc9d6)  
(2809289)  
(中度)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=c5018865-7162-4d8d-86fc-aacd6d5f0a37)   
(2809289)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?familyid=84ba3686-14ed-4aac-8db1-4438aa9e0a2e)   
(2807986)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=cf5f65e1-93ae-4ec3-84d2-eb017efdc9d6)  
(2809289)  
(中度)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=c5018865-7162-4d8d-86fc-aacd6d5f0a37)   
(2809289)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=84ba3686-14ed-4aac-8db1-4438aa9e0a2e)   
(2807986)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=3436d1d1-bf20-40cc-8c51-f093da67c8a9)  
(2809289)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?familyid=01498cd0-e27e-4256-8f21-7a6eeedfb77c)   
(2807986)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=3436d1d1-bf20-40cc-8c51-f093da67c8a9)  
(2809289)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=01498cd0-e27e-4256-8f21-7a6eeedfb77c)   
(2807986)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-021**](https://technet.microsoft.com/zh-tw/error.htm)
</td>
<td style="border:1px solid black;">
[**MS13-027**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-027)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=7c348fe3-f4f0-4f22-8a7f-8563705c1f64)   
(2809289)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 8](https://www.microsoft.com/download/details.aspx?familyid=de4ec125-c337-4615-b39b-8456658dae22)   
(2807986)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 64 位元系統的 Windows 8
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=0c503b83-5b13-41da-a5ff-7519bc244521)   
(2809289)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 64 位元系統的 Windows 8](https://www.microsoft.com/download/details.aspx?familyid=c1539e94-0635-4f51-8172-a96a737d81d3)   
(2807986)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-021**](https://technet.microsoft.com/zh-tw/error.htm)
</td>
<td style="border:1px solid black;">
[**MS13-027**](https://technet.microsoft.com/security/bulletin/ms13-027)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=f9b299f1-8a73-40b2-9942-e6419496bb39)   
(2809289)  
(中度)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=959c78e1-29d9-40a3-9eb3-1206c09e3752)   
(2807986)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-021**](https://technet.microsoft.com/zh-tw/error.htm)
</td>
<td style="border:1px solid black;">
[**MS13-027**](https://technet.microsoft.com/zh-tw/error.htm)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10<sup>[1]</sup>   
(2809289)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="3">
Server Core 安裝選項
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-021**](https://technet.microsoft.com/zh-tw/error.htm)
</td>
<td style="border:1px solid black;">
[**MS13-027**](https://technet.microsoft.com/security/bulletin/ms13-027)
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
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
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
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f1ca4fe0-3ee3-4162-a9fa-48c54fc8b08e) (Server Core 安裝)   
(2807986)  
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
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8b61f3e5-0cf9-4eab-8a59-829957135dd6) (Server Core 安裝)   
(2807986)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 (Server Core 安裝)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?familyid=84ba3686-14ed-4aac-8db1-4438aa9e0a2e) (Server Core 安裝)   
(2807986)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1 (Server Core 安裝)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=84ba3686-14ed-4aac-8db1-4438aa9e0a2e) (Server Core 安裝)   
(2807986)  
(重要)
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
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=959c78e1-29d9-40a3-9eb3-1206c09e3752) (Server Core 安裝)   
(2807986)  
(重要)
</td>
</tr>
</table>
 
**MS13-021** **注意事項**

<sup>[1]</sup>Windows RT 資訊安全更新是透過 [Windows Update](https://update.microsoft.com/windowsupdate/v6/default.aspx) 提供。

#### Microsoft Office 套件及軟體

<p></p> 
<table style="border:1px solid black;">
<tr>
<th colspan="4">
Microsoft Office 軟體
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-023**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-023)
</td>
<td style="border:1px solid black;">
[**MS13-025**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-025)
</td>
<td style="border:1px solid black;">
[**MS13-026**](https://technet.microsoft.com/zh-tw/error.htm)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 Service Pack 1 (32 位元版本)
</td>
<td style="border:1px solid black;">
[Microsoft Visio Viewer 2010 Service Pack 1 (32 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=b01b4410-1107-472f-bf96-234304e91e77)   
(2687505)  
(重大)
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
Microsoft Visio Viewer 2010 Service Pack 1 (64 位元版本)
</td>
<td style="border:1px solid black;">
[Microsoft Visio Viewer 2010 Service Pack 1 (64 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=24065dd5-251b-4a3c-bb44-8d552a1f265e)   
(2687505)  
(重大)
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
Microsoft Visio 2010 Service Pack 1 (32 位元版本)
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2010 Service Pack 1 (32 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=7a1a21e7-3137-4201-a005-cc66379fc1c5)   
(2760762)  
(無嚴重性等級)<sup>[1]</sup>
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
Microsoft Visio 2010 Service Pack 1 (64 位元版本)
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2010 Service Pack 1 (64 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=7b7d39f0-a341-4d48-8177-329cccb5a7f1)   
(2760762)  
(無嚴重性等級)<sup>[1]</sup>
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
Microsoft Office 2010 Filter Pack Service Pack 1 (32位元版本)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 Filter Pack Service Pack 1 (32位元版本)](https://www.microsoft.com/download/details.aspx?familyid=f10db48f-a980-47bf-83a5-c0da4e615114)   
(2553501)  
(無嚴重性等級)<sup>[1]</sup>
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
Microsoft Office 2010 Filter Pack Service Pack 1 (64位元版本)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 Filter Pack Service Pack 1 (64位元版本)](https://www.microsoft.com/download/details.aspx?familyid=70d3372b-74a8-4b68-b6c4-18863835915d)   
(2553501)  
(無嚴重性等級)<sup>[1]</sup>
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
Microsoft OneNote 2010 Service Pack 1 (32 位元版本)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft OneNote 2010 Service Pack 1 (32 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=da4bfd31-65b9-496b-aa98-4fa8b729dcf3)   
(2760600)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft OneNote 2010 Service Pack 1 (64 位元版本)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft OneNote 2010 Service Pack 1 (64 位元版本)](https://www.microsoft.com/download/details.aspx?familyid=10fc7350-e1d4-40b6-a5d1-8670263faf05)   
(2760600)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
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
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=d7aef20a-922b-4495-b473-1afa4a7ac514)   
(2817449)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](https://www.microsoft.com/download/details.aspx?familyid=4960674b-1cb4-499a-999e-7aa4d4c49e5e)   
(2817452)  
(重要)
</td>
</tr>
</table>
 
**MS13-023** **注意事項**

<sup>[1]</sup>針對指定的軟體，嚴重性等級並不適用於本更新，因為此資訊安全風險的已知攻擊媒介是受到封鎖的。

#### Microsoft 開發者工具和軟體

<p></p>
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Silverlight
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-022**](https://technet.microsoft.com/security/bulletin/ms13-022)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
安裝在 Mac 上的 Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
安裝在 Mac 上的 [Microsoft Silverlight 5](https://www.microsoft.com/download/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9)   
(2814124)   
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
安裝在 Mac 上的 Microsoft Silverlight 5 Developer Runtime
</td>
<td style="border:1px solid black;">
安裝在 Mac 上的 [Microsoft Silverlight 5 Developer Runtime](https://www.microsoft.com/download/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9)   
(2814124)   
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
安裝在 Microsoft Windows 用戶端所有受支援版本上的 Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
安裝在 Microsoft Windows 用戶端所有受支援版本上的 [Microsoft Silverlight 5](https://www.microsoft.com/download/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9)   
(2814124)   
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
安裝在所有受支援版本之 Microsoft Windows 用戶端上的 Microsoft Silverlight 5 Developer Runtime
</td>
<td style="border:1px solid black;">
安裝在所有受支援版本之 Microsoft Windows 用戶端上的 [Microsoft Silverlight 5 Developer Runtime](https://www.microsoft.com/download/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9)   
(2814124)   
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
安裝在 Microsoft Windows 伺服器所有受支援版本上的 Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
安裝在 Microsoft Windows 伺服器所有受支援版本上的 [Microsoft Silverlight 5](https://www.microsoft.com/download/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9)  
(2814124)   
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
安裝在所有受支援版本之 Microsoft Windows 伺服器上的 Microsoft Silverlight 5 Developer Runtime
</td>
<td style="border:1px solid black;">
安裝在所有受支援版本之 Microsoft Windows 伺服器上的 [Microsoft Silverlight 5 Developer Runtime](https://www.microsoft.com/download/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9)  
(2814124)   
(重大)
</td>
</tr>
</table>
 

#### Microsoft 伺服器軟體

<p></p> 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-024**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-024)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2010 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=a9e8acbd-90e5-4acd-aa8f-b743a352787b)<sup>[1]</sup>   
(wasrv)  
(2553407)  
(重大)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft SharePoint Foundation
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS13-024**](https://technet.microsoft.com/zh-tw/security/bulletin/ms13-024)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-tw/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=293666ec-3290-4c6f-a7f6-b44c9b7fa0a6)   
(2687418)  
(重要)
</td>
</tr>
</table>
 
**MS13-024** **注意事項**

<sup>[1]</sup>對於受支援版本的 Microsoft SharePoint Server 2010，除了安裝適用於 Microsoft SharePoint 2010 的資訊安全更新套件 (2553407) 外，客戶還需安裝適用於 Microsoft SharePoint Foundation 2010 的資訊安全更新 (2687418)，以避免受本公告中所述的資訊安全風險影響。

偵測與部署工具及指南
--------------------


**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和資訊安全更新。如需更多資訊，請參閱 [TechNet 更新管理中心](https://technet.microsoft.com/zh-tw/updatemanagement/default.aspx) (英文)。[TechNet 資訊安全技術中心](https://technet.microsoft.com/zh-tw/security/default.aspx)提供 Microsoft 產品資訊安全的其他資訊。一般消費者可造訪 [Microsoft Safety & Security Center](https://technet.microsoft.com/zh-tw/security/default.aspx) (英文)，並點選 \[Security Updates\] (資訊安全更新) 來取得上述資訊。

資訊安全更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 以及 [Windows Update](https://update.microsoft.com/windowsupdate/v6/default.aspx) 取得。資訊安全更新也可以從 [Microsoft 下載中心](https://www.microsoft.com/zh-tw/download/search.aspx?q=security%20update)取得。您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。

對於 Microsoft Office for Mac 的客戶，Microsoft AutoUpdate for Mac 可協助您保持最新的 Microsoft 軟體。如需使用 Microsoft AutoUpdate for Mac 的詳細資訊，請參閱[自動檢查軟體更新](https://mac2.microsoft.com/help/office/14/zh-tw/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea) (英文)。

最後，您可以從 [Microsoft Update Catalog](https://catalog.update.microsoft.com/v7/site/) 下載資訊安全更新。Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括資訊安全更新、驅動程式和 Service Pack。只要以資訊安全公告編號 (例如：MS13-001) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](https://catalog.update.microsoft.com/v7/site/faq.aspx)。

**偵測與部署指南**

Microsoft 針對資訊安全更新提供偵測和部署指南。本指南所含之建議和資訊，能幫助 IT 專業人員瞭解如何使用用於資訊安全更新的偵測和部署的各種工具。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 961747](https://support.microsoft.com/kb/961747?ln=zh-tw)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少資訊安全更新以及一般資訊安全設定錯誤的狀況。如需更多有關 MBSA 的資訊，請參閱 [Microsoft Baseline Security Analyzer](https://technet.microsoft.com/zh-tw/security/cc184924.aspx) (英文)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速而可靠地將 Microsoft Windows 2000 作業系統及更新版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 適用的最新重大更新與資訊安全更新部署到 Microsoft Windows 2000 及更新版本的作業系統中。

如需更多關於利用 Windows Server Update Services 部署資訊安全更新的資訊，請造訪 [Windows Server Update Services](https://technet.microsoft.com/wsus/default) (英文)。

**System Center Configuration Manager**

System Center Configuration Manager 軟體更新管理可簡化遞送和管理企業中 IT 系統更新的繁複作業。IT 系統管理員可以使用 System Center Configuration Manager 遞送 Microsoft 產品更新給各種裝置，包括桌上型電腦、筆記型電腦、伺服器及行動裝置。

System Center Configuration Manager 中的自動資訊安全風險評估會找出更新需求並報告建議動作。System Center Configuration Manager 中的軟體更新管理是建置在 Microsoft Windows Software Update Services (WSUS) 上，經過時間考驗，為全球 IT 系統管理員所熟悉的更新基礎架構。如需更多有關 System Center Configuration Manager 的資訊，請造訪 [System Center 技術資源](https://technet.microsoft.com/systemcenter/bb980621)。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。透過 SMS，系統管理員能判斷有哪些 Windows 系統需要資訊安全更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。

**注意：**System Management Server 2003 自 2010 年 1 月 12 日起不受主流支援。如需更多有關產品生命週期的資訊，請造訪 [Microsoft 支援週期](https://support.microsoft.com/default.aspx?scid=fh;%5bln%5d;lifecycle)。現已推出新版的 SMS，System Center Configuration Manager；請參閱前段的＜System Center Configuration Manager＞一節。

如需更多有關系統管理員如何使用 SMS 2003 來部署資訊安全更新的資訊，請參閱 [Microsoft Systems Management Server 2003 的案例與程序： 軟體發佈和補充程式管理](https://www.microsoft.com/download/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f) (英文)。如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server 技術中心 (TechCenter)](https://technet.microsoft.com/systemcenter/bb545936)。

**注意**：SMS 使用 Microsoft Baseline Security Analyzer 提供廣泛的資訊安全公告更新偵測與部署支援。不過這些工具可能無法偵測部分的軟體更新。在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](https://technet.microsoft.com/zh-tw/library/cc917507.aspx) (英文)。某些資訊安全更新程式在電腦重新啟動之後，會需要系統管理員的權限。系統管理員可使用 Elevated Rights Deployment Tool (隨附於 [SMS 2003 Administration Feature Pack](https://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d)) 來安裝這些更新。

**Update Compatibility Evaluator** **和** **Application Compatibility Toolkit**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。這可能會觸發不相容性，而拉長部署資訊安全更新的時間。您可以使用 [Application Compatibility Toolkit](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971) 隨附的 [Update Compatibility Evaluator](https://technet.microsoft.com/library/cc749197) 元件，針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Windows Vista、Windows Update、Microsoft 資訊安全更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

針對每個月第二個星期二發行的公告，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 及下載中心發行更新版本的 Microsoft Windows 惡意軟體移除工具。不定期資訊安全公告發行不提供更新版本的 Microsoft Windows 惡意軟體移除工具。

#### MU、WU 及 WSUS 上的非資訊安全更新

如需在 Windows Update 和 Microsoft Update 上發行的非資訊安全更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](https://support.microsoft.com/kb/894199?ln=zh-tw)
-   ： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](https://technet.microsoft.com/wsus/bb456965)
-   。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的資訊安全保護，Microsoft 將在每月發行資訊安全更新之前，提前向重要資訊安全軟體提供者提供資訊安全風險資訊。資訊安全軟體提供者可利用此資訊安全風險資訊，透過其資訊安全軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](https://www.microsoft.com/security/msrc/collaboration/mapp.aspx) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 資訊安全策略與社群

**更新程式管理策略**

[更新管理資訊安全指南](https://technet.microsoft.com/zh-tw/library/bb466251(zh-tw).aspx) (英文) 提供您有關套用資訊安全更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他資訊安全更新**

其他資訊安全問題的更新可由下列位置取得：

-   資訊安全更新可以從 [Microsoft 下載中心](https://www.microsoft.com/zh-tw/download/search.aspx?q=security%20update)取得， 您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。
-   消費性平台的更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以資訊安全和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的資訊安全更新。如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](https://support.microsoft.com/kb/913086?ln=zh-tw)。

**IT** **專業人員資訊安全社群**

在 [IT 專業人員資訊安全社群](https://technet.microsoft.com/zh-tw/security/cc136632.aspx)上，學習如何提升資訊安全以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類資訊安全議題的討論。

#### 感謝

Microsoft [感謝](https://technet.microsoft.com/zh-tw/security/gg309157.aspx)下列人士協助我們一同保護我們的客戶：

**MS13-021**

-   感謝 [TELUS Security Labs](https://telussecuritylabs.com/) 的 Arseniy Akuney 回報 Internet Explorer OnResize 釋放後使用資訊安全風險 (CVE-2013-0087)
-   感謝匿名的研究人員與 [HP 的](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 Internet Explorer saveHistory 釋放後使用資訊安全風險 (CVE-2013-0088)
-   感謝匿名的研究人員與 [HP 的](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 Internet Explorer CMarkupBehaviorContext 釋放後使用資訊安全風險 (CVE-2013-0089)
-   感謝 [Harmony Security](https://www.harmonysecurity.com/) 的 Stephen Fewer 和 [HP](https://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 Internet Explorer CCaret 釋放後使用資訊安全風險 (CVE-2013-0090)
-   感謝 Skylined 與 [HP 的](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 Internet Explorer CCaret 釋放後使用資訊安全風險 (CVE-2013-0090)
-   感謝 Yenteasy - Security Research 的 Jose A Vazquez 與 [Exodus Intelligence](https://www.exodusintel.com/) 合作回報 Internet Explorer CElement 釋放後使用資訊安全風險 (CVE-2013-0091)
-   感謝 [Aniway.Aniway@gmail.com](mailto:aniway.aniway@gmail.com) 和 [HP](https://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 Internet Explorer GetMarkupPtr 釋放後使用資訊安全風險 (CVE-2013-0092)
-   感謝 [Aniway.Aniway@gmail.com](mailto:aniway.aniway@gmail.com) 和 [HP](https://www.hpenterprisesecurity.com/products) 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 Internet Explorer onBeforeCopy 釋放後使用資訊安全風險 (CVE-2013-0093)
-   感謝 Simon Zuckerbraun 與 [HP 的](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 Internet Explorer removeChild 釋放後使用資訊安全風險 (CVE-2013-0094)
-   感謝 [Venustech](https://www.venustech.com.cn/) ADLab 的 Gen Chen 與我們合作解決 Internet Explorer CTreeNode 釋放後使用資訊安全風險 (CVE-2013-1288)
-   感謝 [Qihoo 360 Security Center](https://www.360.cn/) 與我們合作解決 Internet Explorer CTreeNode 釋放後使用資訊安全風險 (CVE-2013-1288)

**MS13-022**

-   感謝 [Context Information Security](https://www.contextis.com/) 的 James Forshaw 回報 Silverlight 雙重解除參照資訊安全風險 (CVE-2013-0074)

**MS13-023**

-   感謝 [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com) 與 [VeriSign iDefense Labs](https://labs.idefense.com/) 合作回報 Visio Viewer 樹狀結構物件類型混淆資訊安全風險 (CVE-2013-0079)

**MS13-024**

-   感謝 [BugSec](https://www.bugsec.com/) 的Emanuel Bronshtein 回報回呼函數資訊安全風險 (CVE-2013-0080)
-   感謝 INR Labs ([Network Intelligence India](https://niiconsulting.com/)) 的 Sunil Yadav 回報 SharePoint XSS 資訊安全風險 (CVE-2013-0083)
-   感謝 [n.runs AG](https://www.nruns.com/) 的 Moritz Jodeit 回報 SharePoint 目錄周遊資訊安全風險 (CVE-2013-0084)

**MS13-025**

-   感謝 的 Christopher Gabriel 回報緩衝區大小驗證資訊安全風險 (CVE-2013-0086)

**MS13-026**

-   感謝 [Nick Semenkovich](https://technet.microsoft.com/zh-TW/mailto:semenko@alum.mit.edu) 回報非預期內容載入資訊安全風險 (CVE- 2013-0095)

**MS13-027**

-   感謝 NCC 小組的 Andy Davis 回報 Windows USB 描述元資訊安全風險 (CVE-2013-1285)
-   感謝 NCC 小組的 Andy Davis 回報 Windows USB 描述元資訊安全風險 (CVE-2013-1286)
-   感謝 NCC 小組的 Andy Davis 回報 Windows USB 描述元資訊安全風險 (CVE-2013-1287)

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 支援週期](https://support.microsoft.com/default.aspx?scid=fh;%5bln%5d;lifecycle)。
-   IT 專業人員的資訊安全解決方案： [TechNet 資訊安全疑難排解與支援](https://technet.microsoft.com/security/bb980617.aspx)
-   協助保護您的 Windows 電腦免於病毒和惡意軟體攻擊： [病毒解決方案與資訊安全中心](https://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-tw)
-   您所在國家/地區的當地支援： [國際支援](https://support.microsoft.com/common/international.aspx?ln=zh-tw)

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2013 年 3 月 13 日)： 公告摘要發行。
-   V1.1 (2013 年 4 月 10 日)在＜提要＞一節中修正 MS13-026 公告標題。

*Built at 2014-04-18T01:50:00Z-07:00*
