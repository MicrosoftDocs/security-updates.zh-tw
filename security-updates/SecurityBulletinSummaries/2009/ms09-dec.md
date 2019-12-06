---
TOCTitle: 'MS09-DEC'
Title: 2009 年 12 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms09-dec'
ms:contentKeyID: 61237691
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms09-dec(v=Security.10)'
---

2009 年 12 月份 Microsoft 資訊安全公告摘要
==========================================

發行: 2009年12月9日 | 更新: 2010年1月20日

**版本:** 2.0

此公告摘要列出 2009 年 12 月份發行之資訊安全公告。

發行 2009 年 12 月份公告之後，此公告摘要將取代原先於 2009 年 12 月 3 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 資訊安全公告預先通知](https://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2009 年 12 月 9 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。 [立即註冊參加 12 月份資訊安全公告網路廣播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032407802&culture=en-us)。 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 資訊安全公告摘要和網路廣播](https://technet.microsoft.com/security/bulletin/summary)。

Microsoft 也會提供資訊協助客戶排定每月資訊安全更新以及任何非安全性、高優先順序更新的優先順序，其中這些非安全性、高優先順序更新的發行日期與每月資訊安全更新的發行日期相同。 請參閱＜其他資訊＞一節。

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
<th style="border:1px solid black;" >最高的嚴重性等級與弱點影響</th>
<th style="border:1px solid black;" >重新開機需求</th>
<th style="border:1px solid black;" >受影響的軟體</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-071">MS09-071</a></td>
<td style="border:1px solid black;"><strong>網際網路驗證服務的弱點可能會允許遠端執行程式碼 (974318)</strong><br />
<br />
這個資訊安全更新可解決 Microsoft Windows 中兩項未公開報告的弱點。 若處理 PEAP 驗證嘗試時，將網際網路驗證服務伺服器接收到的訊息錯誤地複製到記憶體，這類弱點可能會允許遠端執行程式碼。 成功利用上述任一弱點的攻擊者可以取得受影響系統的完整控制權。 使用網際網路驗證服務的伺服器，只有在搭配 MS-CHAP v2 驗證使用 PEAP 時，才會受影響。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-074">MS09-074</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Project 中的弱點可能會允許遠端執行程式碼 (967183)</strong><br />
<br />
這個資訊安全更新可解決 Microsoft Office Project 中一項未公開報告的弱點。 如果使用者開啟蓄意製作的 Project 檔案，此弱點可能會允許遠端執行程式碼。 成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-072">MS09-072</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 積存資訊安全更新 (976325)</strong><br />
<br />
這個資訊安全更新可解決 Internet Explorer 中四項未公開報告的弱點，以及一項公開揭露的弱點。 如果使用者使用 Internet Explorer 檢視蓄意製作的網頁，這些弱點可能會允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 以 Microsoft Active Template Library (ATL) 標頭建立的一個 ActiveX 控制項可能也會允許遠端執行程式碼；此項弱點已在 Microsoft 安全性摘要報告 973882 與 Microsoft 資訊安全公告 MS09-035 中說明。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-069">MS09-069</a></td>
<td style="border:1px solid black;"><strong>本地安全性授權子系統服務中的弱點可能會允許拒絕服務 (974392)</strong><br />
<br />
這個資訊安全更新可解決 Microsoft Windows 中一項未公開報告的弱點。 如果通過驗證的遠端攻擊者透過網際網路通訊協定安全性 (IPSec) 的通訊方式，傳送蓄意製作的 ISAKMP 訊息給受影響系統上的本機安全性授權子系統服務，此弱點可能會允許拒絕服務。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
拒絕服務</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-070">MS09-070</a></td>
<td style="border:1px solid black;"><strong>Active Directory Federation Services 中的弱點可能會允許遠端執行程式碼 (971726)</strong><br />
<br />
這個資訊安全更新可解決 Microsoft Windows 中兩項未公開報告的弱點。 如果攻擊者將蓄意製作的 HTTP 要求傳送至啟用 ADFS 的 Web 伺服器，這些弱點中較嚴重者可能會允許遠端執行程式碼。 攻擊者必須是通過驗證的使用者，才能利用上述任一弱點。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-073">MS09-073</a></td>
<td style="border:1px solid black;"><strong>WordPad 及 Office 文字轉換程式中的弱點可能允許遠端執行程式碼 (975539)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Virtual PC 和 Microsoft Office 文字轉換程式中一項未公開報告的弱點。 若在 WordPad 或 Microsoft Office Word 中開啟蓄意製作的 Word 97 檔案，這些弱點可能會允許遠端執行程式碼。 成功利用這項弱點的攻擊者可以取得與使用者相同的權限。 系統上帳戶權限較少的使用者，其受影響的程度比擁有管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、Microsoft Office</td>
</tr>
</tbody>
</table>
  
弱點索引  
--------
  
<span></span>
下表提供本月所述每個弱點的利用性評估。 弱點皆根據公告編號和 CVE 編號依序列出。
  
**我該如何使用這個表格？**
  
請用這個表格來瞭解您可能需要安裝的每個資訊安全更新，與 30 天內已發行的可利用程式碼受影響之可能性。 您應該檢閱下列的每個評估，按照特定的設定，將部署以優先次序排序。 如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](https://technet.microsoft.com/en-us/security/cc998259.aspx)。
  
| 公告編號                                                            | 弱點標題                                     | CVE ID                                                                           | 弱點索引評估                                                                                            | 主要重點                                                                                                                                                                                                      |  
|---------------------------------------------------------------------|----------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-069](https://technet.microsoft.com/security/bulletin/ms09-069) | 本地安全性授權子系統服務資源耗盡弱點         | [CVE-2009-3675](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3675) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 此弱點不允許遠端執行程式碼，通過驗證的遠端使用者僅可嘗試利用拒絕服務。                                                                                                                                        |  
| [MS09-070](https://technet.microsoft.com/security/bulletin/ms09-070) | ADFS 的單一登入偽造弱點                      | [CVE-2009-2508](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2508) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 此弱點不允許遠端執行程式碼，僅可能導致偽造行為。                                                                                                                                                              |  
| [MS09-070](https://technet.microsoft.com/security/bulletin/ms09-070) | ADFS 的遠端執行程式碼弱點                    | [CVE-2009-2509](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2509) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | 只有通過驗證的攻擊者可利用此弱點。                                                                                                                                                                            |  
| [MS09-071](https://technet.microsoft.com/security/bulletin/ms09-071) | 網際網路驗證服務記憶體損毀弱點               | [CVE-2009-2505](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2505) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | 遠端執行程式碼的可能性有限。 最可能的結果是拒絕服務。                                                                                                                                                         |  
| [MS09-071](https://technet.microsoft.com/security/bulletin/ms09-071) | MS-CHAP 驗證略過弱點                         | [CVE-2009-3677](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3677) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 此弱點不允許遠端執行程式碼，僅可能因略過網路驗證而造成權限提高。                                                                                                                                              |  
| [MS09-072](https://technet.microsoft.com/security/bulletin/ms09-072) | ATL COM 初始化弱點                           | [CVE-2009-2493](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493) | 無                                                                                                      | (此弱點已經在[七月份公告摘要](https://technet.microsoft.com/security/bulletin/ms09-jul)中獲得弱點索引評估。 這是因為此弱點是由 [MS09-035](https://technet.microsoft.com/security/bulletin/ms09-035) 首先提出。) |  
| [MS09-072](https://technet.microsoft.com/security/bulletin/ms09-072) | 未初始化的記憶體損毀弱點                     | [CVE-2009-3671](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3671) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                                                                                          |  
| [MS09-072](https://technet.microsoft.com/security/bulletin/ms09-072) | HTML 物件記憶體損毀弱點                      | [CVE-2009-3672](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3672) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                                                                                          |  
| [MS09-072](https://technet.microsoft.com/security/bulletin/ms09-072) | 未初始化的記憶體損毀弱點                     | [CVE-2009-3673](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3673) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                                                                                          |  
| [MS09-072](https://technet.microsoft.com/security/bulletin/ms09-072) | 未初始化的記憶體損毀弱點                     | [CVE-2009-3674](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3674) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                                                                                          |  
| [MS09-073](https://technet.microsoft.com/security/bulletin/ms09-073) | WordPad 與 Office 文字轉換程式記憶體損毀弱點 | [CVE-2009-2506](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2506) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                                                                                                          |  
| [MS09-074](https://technet.microsoft.com/security/bulletin/ms09-074) | Project 記憶體驗證弱點                       | [CVE-2009-0102](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0102) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                                                                                                          |
  
受影響的軟體及下載位置  
----------------------
  
<span></span>
下表依據主要的軟體類別和嚴重性依序列出公告。
  
**我該如何使用這些表格？**
  
請用這些表格來瞭解可能需要安裝的資訊安全更新有哪些。 您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的資訊安全更新。 若軟體程式或更新出現在清單中，則相關可用軟體更新也會以超連結方式提供，也會列出軟體更新的嚴重性等級。
  
**注意**：一項弱點，可能需要安裝數個資訊安全更新才能妥善解決。 請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
#### Windows 作業系統與元件

 
<p> </p>
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
</tr>
<tr>
<th colspan="6">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-071**](https://technet.microsoft.com/security/bulletin/ms09-071)
</td>
<td style="border:1px solid black;">
[**MS09-072**](https://technet.microsoft.com/security/bulletin/ms09-072)
</td>
<td style="border:1px solid black;">
[**MS09-069**](https://technet.microsoft.com/security/bulletin/ms09-069)
</td>
<td style="border:1px solid black;">
[**MS09-070**](https://technet.microsoft.com/security/bulletin/ms09-070)
</td>
<td style="border:1px solid black;">
[**MS09-073**](https://technet.microsoft.com/security/bulletin/ms09-073)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=5b02d10d-1abd-4d68-826b-71dad543657a)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Explorer 5.01 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=0cf37247-505a-4dc2-aad7-c8cb1a63b57a)  
(重大)  
[Internet Explorer 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=7fb6261c-6895-4f79-be2c-bb110874a19c)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=560e01db-5f59-4ef1-9406-f5d7e0fd4128)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=50936f51-b0a9-4e94-85bf-93f9ad74fdd1)  
(KB973904)  
(重要)
</td>
</tr>
<tr>
<th colspan="6">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-071**](https://technet.microsoft.com/security/bulletin/ms09-071)
</td>
<td style="border:1px solid black;">
[**MS09-072**](https://technet.microsoft.com/security/bulletin/ms09-072)
</td>
<td style="border:1px solid black;">
[**MS09-069**](https://technet.microsoft.com/security/bulletin/ms09-069)
</td>
<td style="border:1px solid black;">
[**MS09-070**](https://technet.microsoft.com/security/bulletin/ms09-070)
</td>
<td style="border:1px solid black;">
[**MS09-073**](https://technet.microsoft.com/security/bulletin/ms09-073)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 及 Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 與 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=4d294be6-19d1-43b5-9c75-f9d30699a2e7)  
(中度)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=facab13f-ea31-4c71-be4c-24e44ded174f)  
(重大)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=def2c038-3b03-4162-a563-a6ebec756f37)  
(重大)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=6c003629-77bf-4735-bd4a-c37c4386f869)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 與 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=5448b168-6bf7-4bae-9627-b88d76c4d5c5)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 與 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=c090c4c2-c277-4d8c-91e1-28286bc5443e)  
(KB973904)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=17b5206d-61e9-4663-afc7-80e98bf4d618)  
(中度)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=a253c19a-c808-4115-8bd0-cf312d396abd)  
(重大)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=98a56425-4f88-4f0f-963b-dada8dc0d8f8)  
(重大)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=0c9af3b5-d015-4025-bbb4-1a5113e9113f)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c2bbf515-f81a-436b-947b-cbf2db85fdd9)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4b9bf156-cd34-460f-b4ad-571e37f54659)  
(KB973904)  
(重要)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-071**](https://technet.microsoft.com/security/bulletin/ms09-071)
</td>
<td style="border:1px solid black;">
[**MS09-072**](https://technet.microsoft.com/security/bulletin/ms09-072)
</td>
<td style="border:1px solid black;">
[**MS09-069**](https://technet.microsoft.com/security/bulletin/ms09-069)
</td>
<td style="border:1px solid black;">
[**MS09-070**](https://technet.microsoft.com/security/bulletin/ms09-070)
</td>
<td style="border:1px solid black;">
[**MS09-073**](https://technet.microsoft.com/security/bulletin/ms09-073)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3d49b386-133a-4d51-b6f0-cec0c70ef93e)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=6659fc40-71ee-44a9-9656-8d3ee02b5bc0)  
(重大)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=7bdba030-e2c6-44ac-bb5f-24ae8ec372a2)  
(中度)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=0dd50357-64f2-4286-86ba-c512e65eed2a)  
(中度)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a779aae1-7724-4458-94fb-a2343356ecae)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=31351b9e-b5bb-4618-990b-1089ea5a3bc2)<sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b9678229-2473-4aae-a814-eca9ea556d17)  
(KB973904)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5a273b47-8a18-4778-9b60-8b560a1ce089)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=287e7921-8aab-42a6-b647-551d0a9adc15)  
(重大)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=4de4bbcd-b1b8-4482-8ef7-0d9b4a730e0c)  
(中度)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=e62aba15-5eeb-46a2-a142-bfca94016c55)  
(中度)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a8a9bf12-4ad6-49fd-b2b7-f379dc3309d2)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b6eb9d9b-1a43-4b30-a033-19a1db786244)<sup>[2]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=257facf3-20a1-49e2-ab4c-c1ae67fe05a0)  
(KB973904)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=498f5eeb-d03e-42ee-ad6a-9d6f98c66acb)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=9ce1a721-0c6a-4775-9407-9633d817d716)  
(重大)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=72d44de7-dfc5-4667-a59f-2ee73d0e3708)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=f5b003ad-af25-488a-91fb-98835a0bfeac)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=1a7784ef-5d25-4de1-a293-f742b5a3473d)  
(KB973904)  
(重要)
</td>
</tr>
<tr>
<th colspan="6">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-071**](https://technet.microsoft.com/security/bulletin/ms09-071)
</td>
<td style="border:1px solid black;">
[**MS09-072**](https://technet.microsoft.com/security/bulletin/ms09-072)
</td>
<td style="border:1px solid black;">
[**MS09-069**](https://technet.microsoft.com/security/bulletin/ms09-069)
</td>
<td style="border:1px solid black;">
[**MS09-070**](https://technet.microsoft.com/security/bulletin/ms09-070)
</td>
<td style="border:1px solid black;">
[**MS09-073**](https://technet.microsoft.com/security/bulletin/ms09-073)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=3e4ae4d0-1060-4867-82c5-7e20ea93c2c6)  
(中度)  
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3e4ae4d0-1060-4867-82c5-7e20ea93c2c6)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=40d26d40-4203-4013-b3f9-912a5b209fbd)  
(重大)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=47d5ada1-1d60-4233-bdd3-64918b5e1245)  
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=2ca62ea8-67cb-40da-8a65-db6f3607bbab)  
(中度)  
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2ca62ea8-67cb-40da-8a65-db6f3607bbab)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=3140527a-aa33-462b-b3a6-bfcd78b5aa0c)  
(重大)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=1e466b48-422f-4c80-8fdf-ba61111942b1)  
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
</tr>
<tr>
<th colspan="6">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-071**](https://technet.microsoft.com/security/bulletin/ms09-071)
</td>
<td style="border:1px solid black;">
[**MS09-072**](https://technet.microsoft.com/security/bulletin/ms09-072)
</td>
<td style="border:1px solid black;">
[**MS09-069**](https://technet.microsoft.com/security/bulletin/ms09-069)
</td>
<td style="border:1px solid black;">
[**MS09-070**](https://technet.microsoft.com/security/bulletin/ms09-070)
</td>
<td style="border:1px solid black;">
[**MS09-073**](https://technet.microsoft.com/security/bulletin/ms09-073)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008](https://www.microsoft.com/download/details.aspx?familyid=582a1b15-214e-4f5e-bb5b-95677f4d5968)\*  
(重要)  
[適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=582a1b15-214e-4f5e-bb5b-95677f4d5968)\*  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=d0570536-756e-4fda-883d-f2a3c4ac5bbd)\*  
(中度)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=43660133-43e1-41f3-8a82-98c4a739914f)\*  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f6715abb-fd93-44ba-9854-2ecc672622da)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008](https://www.microsoft.com/download/details.aspx?familyid=77e774b4-ec0c-481c-9e93-eee9f44ec71b)\*  
(重要)  
[適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=77e774b4-ec0c-481c-9e93-eee9f44ec71b)\*  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=0e72d0f1-2ce7-4650-b72c-bb303351aafc)\*  
(中度)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=22972970-740f-4c50-93ec-f6d49dd1b360)\*  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7d1f5e9e-a7de-4f96-89c8-510fd51f16e7)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008](https://www.microsoft.com/download/details.aspx?familyid=89defe77-7e82-4bfa-9693-66c93b930da1)  
(中度)  
[適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=89defe77-7e82-4bfa-9693-66c93b930da1)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=2c7765a2-3117-4dd8-94b4-0060ca16871b)  
(中度)
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
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-071**](https://technet.microsoft.com/security/bulletin/ms09-071)
</td>
<td style="border:1px solid black;">
[**MS09-072**](https://technet.microsoft.com/security/bulletin/ms09-072)
</td>
<td style="border:1px solid black;">
[**MS09-069**](https://technet.microsoft.com/security/bulletin/ms09-069)
</td>
<td style="border:1px solid black;">
[**MS09-070**](https://technet.microsoft.com/security/bulletin/ms09-070)
</td>
<td style="border:1px solid black;">
[**MS09-073**](https://technet.microsoft.com/security/bulletin/ms09-073)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=5af3be0b-2dd2-4039-90e1-2278e9c5aee5)  
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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=9d9a04c8-a019-4943-8e93-c6bfd77c8960)  
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
</tr>
<tr>
<th colspan="6">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-071**](https://technet.microsoft.com/security/bulletin/ms09-071)
</td>
<td style="border:1px solid black;">
[**MS09-072**](https://technet.microsoft.com/security/bulletin/ms09-072)
</td>
<td style="border:1px solid black;">
[**MS09-069**](https://technet.microsoft.com/security/bulletin/ms09-069)
</td>
<td style="border:1px solid black;">
[**MS09-070**](https://technet.microsoft.com/security/bulletin/ms09-070)
</td>
<td style="border:1px solid black;">
[**MS09-073**](https://technet.microsoft.com/security/bulletin/ms09-073)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/security/bulletin/rating)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=bcb38127-787f-49b0-b3fb-62f6a8628d89)\*  
(中度)
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
適用於 Itanium 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=2c1b96f2-b3c3-4711-a9ad-b2133ea7bf81)  
(中度)
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
 
Windows Server 2008 和 Windows Server 2008 R2 注意事項

**\*Server Core 安裝不受影響。** 如果 Windows Server 2008 或 Windows Server 2008 R2 是使用 Server Core 安裝選項所安裝，則這項更新解決的弱點並不會影響受支援的 Windows Server 2008 或 Windows Server 2008 R2。 如需此安裝選項的詳細資訊，請參閱 MSDN 文章：[伺服器核心](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英文) 以及[適用於 Windows Server 2008 R2 的伺服器核心](https://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 及 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**MS09-070 注意事項**

<sup>[1]</sup> 只有在已更新 Windows Server 2003 R2、部署 Active Directory Federation Services 的狀態下才會受影響。

<sup>[2]</sup> 只有在已更新 Windows Server 2003 R2 x64 Edition、部署 Active Directory Federation Services 的狀態下才會受影響。

**MS09-073 注意事項**

另請參閱＜受影響的軟體及下載位置＞中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。 本公告涉及多個軟體分類。

#### Microsoft Office 套件及軟體

 
<p> </p>
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
Microsoft Office 套件、系統和元件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-074**](https://technet.microsoft.com/security/bulletin/ms09-074)
</td>
<td style="border:1px solid black;">
[**MS09-073**](https://technet.microsoft.com/security/bulletin/ms09-073)
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
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=bc3ec3ba-2cec-43ab-b184-c222794231f2)  
(KB975008)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=b4a4126c-b0b3-4db2-b6f5-0e67519c2a5f)  
(KB975051)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
其他 Microsoft Office 軟體
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-074**](https://technet.microsoft.com/security/bulletin/ms09-074)
</td>
<td style="border:1px solid black;">
[**MS09-073**](https://technet.microsoft.com/security/bulletin/ms09-073)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Project 2000
</td>
<td style="border:1px solid black;">
[Microsoft Project 2000 Service Release 1](https://www.microsoft.com/download/details.aspx?familyid=135c010a-55f4-4385-b67d-96ea06ef881a)  
(KB961083)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Project 2002
</td>
<td style="border:1px solid black;">
[Microsoft Project 2002 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=c55ef8fe-8f66-42fc-a298-de6f8886b3e4)  
(KB961079)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Project 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Project 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=2ea8ca39-f130-439a-92d5-77e9ef050105)  
(KB961082)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Works 8.5
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Works 8.5](https://www.microsoft.com/download/details.aspx?familyid=807426a1-8b78-4681-a606-dc39f4d7b64a)  
(KB977304)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Converter Pack
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office Converter Pack](https://www.microsoft.com/download/details.aspx?familyid=f3ff8bb6-d047-42f1-9331-b6df85fff9fd)  
(KB974882)  
(重要)
</td>
</tr>
</table>
 
**MS09-073 注意事項**

另請參閱＜受影響的軟體及下載位置＞中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。 本公告涉及多個軟體分類。

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和資訊安全更新。 如需更多資訊，請參閱 [TechNet 更新管理中心](https://www.microsoft.com/taiwan/technet/updatemanagement/default.mspx) 。 [TechNet 資訊安全中心](https://www.microsoft.com/taiwan/technet/security/default.mspx) 提供 Microsoft 產品安全性的其他資訊。 消費者可以造訪[在家上網的安全性](https://www.microsoft.com/taiwan/protect/default.mspx)網站，只要按一下 \[最新資訊安全更新\] 即可在此網站取得此資訊。

資訊安全更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 以及 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 取得。 資訊安全更新也可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得。 您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。

最後，您可以從 [Microsoft Update Catalog](https://go.microsoft.com/fwlink/?linkid=96155) 下載資訊安全更新。 Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括資訊安全更新、驅動程式和 Service Pack。 只要以資訊安全公告編號 (例如：MS07-036) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。 如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](https://go.microsoft.com/fwlink/?linkid=97900)。

**注意**：自 2009 年 8 月 1 日開始，Microsoft 已停止支援 Office Update 與 Office Update Inventory Tool。 若要繼續取得 Microsoft Office 產品的最新更新，請使用 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)。 如需更多資訊，請參閱[關於 Microsoft Office Update： 常見問題集](https://office.microsoft.com/en-us/downloads/fx010402221033.aspx) (英文)。

**偵測與部署指南**

Microsoft 針對資訊安全更新提供偵測和部署指南。 本指南所含之建議和資訊，能幫助 IT 專業人員瞭解如何使用用於資訊安全更新的偵測和部署的各種工具。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 961747](https://support.microsoft.com/kb/961747/zh-tw)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少資訊安全更新以及一般安全性設定錯誤的狀況。 如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134) 網站 (英文)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速可靠地將 Windows 2000 作業系統及更新系統版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 等最新的重大更新與資訊安全更新部署到 Windows 2000 及更新作業系統版本中。

如需更多關於利用 Windows Server Update Services 部署資訊安全更新的資訊，請造訪 [Windows Server Update Services](https://www.microsoft.com/taiwan/windowsserversystem/updateservices/evaluation/overview.mspx) 網站。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要資訊安全更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。 現已推出新版的 SMS，System Center Configuration Manager 2007；另請參閱 [System Center Configuration Manager 2007](https://www.microsoft.com/taiwan/systemcenter/configmgr/default.mspx)。如需更多有關系統管理員如何能使用 SMS 2003 部署資訊安全更新的資訊，請參閱 [SMS 2003 安全性修補程式管理](https://www.microsoft.com/taiwan/smserver/evaluation/capabilities/patch.htm) 。 SMS 2.0 使用者也可以使用資訊安全更新盤點工具 (Security Update Inventory Tool，SUIT) 來協助部署資訊安全更新。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server](https://www.microsoft.com/taiwan/smserver/)。

**注意**：SMS 使用 Microsoft Baseline Security Analyzer 提供廣泛的資訊安全公告更新偵測與部署支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](https://go.microsoft.com/fwlink/?linkid=33341)。 某些資訊安全更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可以用 Elevated Rights Deployment Tool (隨 [SMS 2003 Administration Feature Pack](https://www.microsoft.com/taiwan/smserver/downloads/2003/adminpack.htm) 和 [SMS 2.0 管理功能套件](https://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/adminpack/default.htm) 提供) 來安裝這些更新。

**Update Compatibility Evaluator 和應用程式相容性工具組**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。 這可能會觸發不相容性，而拉長部署資訊安全更新的時間。 您可以使用 [Application Compatibility Toolkit](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 隨附的 [Update Compatibility Evaluator](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 元件，針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Microsoft Windows Vista、Windows Update、Microsoft 資訊安全更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非安全性、高優先順序更新

如需在 Windows Update 和 Microsoft Update 上發行的非資訊安全更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](https://support.microsoft.com/kb/894199/zh-tw)： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。 其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](https://technet.microsoft.com/en-us/wsus/bb456965.aspx)。 顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的安全性保護，Microsoft 將在每月發行資訊安全更新之前，提前向重要安全性軟體提供者提供弱點資訊。 安全性軟體提供者可利用此弱點資訊，透過其安全性軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。 如果要判斷是否有安全性軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](https://www.microsoft.com/security/msrc/mapp/partners.mspx)上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 安全性策略與社群

**更新程式管理策略**

[更新管理安全性指南](https://technet.microsoft.com/zh-tw/library/bb466251(en-us).aspx) (英文) 提供您有關套用資訊安全更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他資訊安全更新**

其他安全性問題的更新可由下列位置取得：

-   資訊安全更新可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。
-   客戶平台的更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的資訊安全更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](https://support.microsoft.com/kb/913086/zh-tw)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](https://technet.microsoft.com/zh-tw/security/cc136632.aspx)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](https://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 [Verisign iDefense Labs](https://labs.idefense.com/) 的 Ryan Smith 回報 MS09-072 中描述的一項問題
-   感謝 eshu.co.uk 的 Sam Thomas 與 [TippingPoint](https://www.tippingpoint.com/) 和 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 MS09-072 中描述的一項問題
-   感謝 [team509](https://www.team509.com/) 與 [Verisign iDefense Labs](https://labs.idefense.com/) 合作回報 MS09-072 中描述的一項問題
-   感謝匿名的研究人員與 [Tipping Point](https://www.tippingpoint.com/) 及 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 MS09-072 中描述的一項問題
-   感謝匿名的研究人員與 [Tipping Point](https://www.tippingpoint.com/) 及 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 MS09-072 中描述的另一項問題
-   感謝 [VeriSign iDefense Labs](https://labs.idefense.com/) 的 Sean Larsson 和 Jun Mao 回報 MS09-073 中描述的一項問題
-   感謝 Fortinet 公司 [FortiGuard Labs](https://www.fortiguard.com/) 的 Bing Liu 回報 MS09-074 中描述的一項問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可洽詢[資訊安全支援](https://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 以取得技術支援。 與資訊安全更新有關的支援電話不另外收費。 如需更多可用支援選項的資訊，請參閱 [Microsoft 技術支援服務](https://support.microsoft.com/?ln=zh-tw)。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與資訊安全更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](https://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2009 年 12 月 9 日)： 公告摘要發行。
-   V1.1 (2009 年 12 月 30 日)： 更新「提要」表中的 MS09-071 說明。 更正 MS09-073 的重新開機需求。
-   V2.0 (2010 年 1 月 20 日)： 針對 MS09-073，將先前列為 **Microsoft Office Word 2002 Service Pack 3 (KB975008)** 及 **Microsoft Office Word 2003 Service Pack 3 (KB975051)** 的更新套件，分別重新命名為 **Microsoft Office XP Service Pack 3 (KB975008)** 及 **Microsoft Office 2003 Service Pack 3 (KB975051)**。

*Built at 2014-04-18T01:50:00Z-07:00*
