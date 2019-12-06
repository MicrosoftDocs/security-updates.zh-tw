---
TOCTitle: 'MS10-JAN'
Title: 2010 年 1 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms10-jan'
ms:contentKeyID: 61237705
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms10-jan(v=Security.10)'
---

2010 年 1 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2010年1月13日 | 更新: 2010年1月22日

**版本:** 2.0

此公告摘要列出 2010 年 1 月份發行之資訊安全公告。

發行 2010 年 1 月份公告之後，此公告摘要將取代原先於 2010 年 1 月 20 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 資訊安全公告預先通知](https://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2010 年 1 月 13 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。 [立即註冊參加 1 月份資訊安全公告網路廣播](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032427677&eventcategory=4&culture=en-us&countrycode=us)。 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 資訊安全公告摘要和網路廣播](https://technet.microsoft.com/security/bulletin/summary)。

針對新增至本公告摘要 2.0 版的不定期資訊安全公告 (MS-10-002)，Microsoft 將利用網路廣播於 2010 年 1 月 22 日，太平洋時間下午 1 點（美國與加拿大）解答客戶對於這些公告的問題。 [立即註冊參加 1 月 21 日下午 1 點的網路廣播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032440627&culture=en-us)。 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 資訊安全公告摘要和網路廣播](https://technet.microsoft.com/security/bulletin/summary)。

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-001">MS10-001</a></td>
<td style="border:1px solid black;"><strong>內嵌 OpenType 字型引擎弱點可能允許遠端執行程式碼 (972270)</strong><br />
<br />
這個資訊安全更新可解決 Microsoft Windows 中一項未公開報告的弱點。 如果使用者在能夠呈現內嵌 OpenType (EOT) 字型的用戶端應用程式中 (例如 Microsoft Internet Explorer、Microsoft Office PowerPoint 或 Microsoft Office Word)，檢視了蓄意製作之 EOT 字型所顯示的內容，此弱點可能會允許遠端執行程式碼。 成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-002">MS10-002</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 積存資訊安全更新 (978207)</strong><br />
<br />
這個資訊安全更新可解決 Internet Explorer 中七項未公開報告的弱點，以及一項公開揭露的弱點。 其中較嚴重的弱點，可能在使用者以 Internet Explorer 檢視蓄意製作的網頁時允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
弱點索引  
--------
  
<span></span>
下表提供本月所述每個弱點的利用性評估。 弱點皆根據公告編號和 CVE 編號依序列出。
  
**我該如何使用這個表格？**
  
請用這個表格來瞭解您可能需要安裝的每個資訊安全更新，與 30 天內已發行的可利用程式碼受影響之可能性。 您應該檢閱下列的每個評估，按照特定的設定，將部署以優先次序排序。 如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](https://technet.microsoft.com/zh-tw/security/cc998259.aspx)。
  
| 公告編號                                                            | 弱點標題                                                        | CVE ID                                                                           | 弱點索引評估                                                                                            | 主要重點                                                                                                                                        |  
|---------------------------------------------------------------------|-----------------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS10-001](https://technet.microsoft.com/security/bulletin/ms10-001) | LZCOMP Decompressor 弱點中的 Microtype Express 壓縮字型整數缺點 | [CVE-2010-0018](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0018) | [**2**](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | 此弱點索引評估適用於執行 Microsoft Windows 2000 的系統。如果系統執行的是 Windows XP 與更新版本的作業，是不大可能被利用的。                      |  
| [MS10-002](https://technet.microsoft.com/security/bulletin/ms10-002) | XSS 篩選器指令碼處理弱點                                        | [CVE-2009-4047](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-4047) | 無                                                                                                      | 不可能利用此弱點執行程式碼。                                                                                                                    |  
| [MS10-002](https://technet.microsoft.com/security/bulletin/ms10-002) | URL 驗證弱點                                                    | [CVE-2010-0027](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0027) | [**1**](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                            |  
| [MS10-002](https://technet.microsoft.com/security/bulletin/ms10-002) | 未初始化的記憶體損毀弱點                                        | [CVE-2010-0244](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0244) | [**1**](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                            |  
| [MS10-002](https://technet.microsoft.com/security/bulletin/ms10-002) | 未初始化的記憶體損毀弱點                                        | [CVE-2010-0245](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0245) | 無                                                                                                      | 已經套用 [MS09-072](https://technet.microsoft.com/security/bulletin/ms09-072) 的客戶可受到保護，因為 MS09-072 更新程式所做的變更包括封鎖此弱點。 |  
| [MS10-002](https://technet.microsoft.com/security/bulletin/ms10-002) | 未初始化的記憶體損毀弱點                                        | [CVE-2010-0246](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0246) | 無                                                                                                      | 已經套用 [MS09-072](https://technet.microsoft.com/security/bulletin/ms09-072) 的客戶可受到保護，因為 MS09-072 更新程式所做的變更包括封鎖此弱點。 |  
| [MS10-002](https://technet.microsoft.com/security/bulletin/ms10-002) | 未初始化的記憶體損毀弱點                                        | [CVE-2010-0247](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0247) | [**1**](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                                            |  
| [MS10-002](https://technet.microsoft.com/security/bulletin/ms10-002) | 未初始化的記憶體損毀弱點                                        | [CVE-2010-0248](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0248) | [**2**](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                                            |  
| [MS10-002](https://technet.microsoft.com/security/bulletin/ms10-002) | 未初始化的記憶體損毀弱點                                        | [CVE-2010-0249](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0249) | [**1**](https://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | **此弱點目前在網際網路生態系統中遭到利用。**                                                                                                    |
  
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
</tr>
<tr>
<th colspan="3">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-001**](https://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](https://technet.microsoft.com/security/bulletin/ms10-002)
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
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=47f85cbd-282e-4c92-9809-68bba49e0a12)  
(重大)
</td>
<td style="border:1px solid black;">
[安裝在 Microsoft Windows 2000 Service Pack 4 上的 Internet Explorer 5.01 Service Pack 4](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=51e99e4f-1670-4b12-a9fe-e0ccf50cdabc)  
(重大)  
[安裝在 Microsoft Windows 2000 Service Pack 4 上的 Internet Explorer 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=a38aa9d0-c3fe-4d41-8805-7d5370263c1b)  
(重大)
</td>
</tr>
<tr>
<th colspan="3">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-001**](https://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](https://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**輕微**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 及 Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 與 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=793a6b3f-7660-40be-b7d5-7b0eec55e1cd)  
(輕微)
</td>
<td style="border:1px solid black;">
[適用於 Windows XP Service Pack 2 及 Windows XP Service Pack 3 的 Internet Explorer 6](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=207eecad-6e84-48e6-ae18-6794a3618ee0)  
(重大)  
[適用於 Windows XP Service Pack 2 及 Windows XP Service Pack 3 的 Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=3510c7d8-7e8f-479e-b6f9-5745a845664d)  
(重大)  
[適用於 Windows XP Service Pack 2 及 Windows XP Service Pack 3 的 Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=7c2948fb-f486-4801-bc21-bbf40d5a78c2)  
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=31609ce9-656a-4f7d-a501-709a31ca34c3)  
(輕微)
</td>
<td style="border:1px solid black;">
[適用於 Windows XP Professional x64 Edition Service Pack 2 的 Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=eb2d8055-4d50-4f83-82b8-055c7b8f5422)  
(重大)  
[適用於 Windows XP Professional x64 Edition Service Pack 2 的 Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=cc5aea0b-e553-4f7f-a2cc-cba41bb87ae7)  
(重大)  
[Windows XP Professional x64 Edition Service Pack 2 的 Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=41b83fad-948b-4a9c-80ed-9c5a60bd35b4)  
(重大)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-001**](https://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](https://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**輕微**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e1d6e338-dea9-458e-b35d-796e069d74d7)  
(輕微)
</td>
<td style="border:1px solid black;">
[適用於 Windows Server 2003 Service Pack 2 的 Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=fea91227-44ad-4549-8732-497a8ceff870)  
(中度)  
[Windows 2003 Service Pack 2 中的 Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=14726445-3ff4-463c-9fc1-c9b758079aca)  
(重大)  
[Windows 2003 Service Pack 2 中的 Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=7d480c87-2ca9-4505-a59d-a6d73d001fa5)  
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ddbcf231-9fde-4dc2-ad04-a01b69d1a980)  
(輕微)
</td>
<td style="border:1px solid black;">
[適用於 Windows Server 2003 x64 Edition Service Pack 2 的 Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=633e63f4-605b-43c4-8a4b-2730312a1c72)  
(中度)  
[Windows Server 2003 x64 Edition Service Pack 2 的 Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=c8742230-16d8-4b2f-bd3e-8834c759856b)  
(重大)  
[Windows Server 2003 x64 Edition Service Pack 2 的 Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=3e2e740b-8417-4758-8468-15221249ec71)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=c71a13cf-7e2f-4b02-8684-1a4e4b46ddda)  
(輕微)
</td>
<td style="border:1px solid black;">
[適用於 Windows Server 2003 SP2 for Itanium-based Systems 的 Windows Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=b9308d50-ca66-43ff-9dc5-d05c90baa764)  
(中度)  
[適用於 Itanium 型系統的 Windows Server 2003 SP2 中的 Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=5622f223-df9c-4a6a-bdf0-feebaf9920fd)  
(重大)
</td>
</tr>
<tr>
<th colspan="3">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-001**](https://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](https://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**輕微**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6387228c-eedc-4511-b3c6-8922606f4c84)  
(輕微)
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2 中的 Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=92495551-dedd-43d4-bb3a-51028bc5c6d6)  
(重大)  
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2 中的 Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=5e2cbd7d-f64f-49e5-a159-1965ebfe2a92)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7b4f5089-13b1-421b-a00b-22632bba4229)  
(輕微)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2 中的 Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=3cb139b3-59f4-44ef-9911-4dd4e3b83e7d)  
(重大)  
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2 中的 Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=b7a7e8e7-f4c5-459d-ab6c-05a192e1e3f9)  
(重大)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-001**](https://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](https://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**輕微**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e175c436-37e0-497f-8b7f-6cacaa25ad7c)\*\*  
(輕微)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2 中的 Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=8c4c91ec-1b2b-4176-bd77-45245b590329)\*\*  
(重大)  
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2 中的 Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=f5ce8582-af63-4870-bee3-0abeeefa1458)\*\*  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1b10a177-fd45-406f-8edc-b8d4b84881b7)\*\*  
(輕微)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2 中的 Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=4f9975b8-3f91-4116-9200-ef55ece75854)\*\*  
(重大)  
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2 中的 Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=be11981c-d286-4e3c-94bf-d4e67a975d5a)\*\*  
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e8bc9a24-a794-4827-a6bb-785c6b2189f4)  
(輕微)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2 中的 Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=9395547f-b620-4cbd-9ff5-11b76cd73859)  
(重大)
</td>
</tr>
<tr>
<th colspan="3">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-001**](https://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](https://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**輕微**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=75491ad0-40a6-4efb-9574-d82210f6d0da)  
(輕微)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統之 Windows 7 中的 Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=278443c1-15dc-436b-893b-ffea6d29d16d)  
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=8a53f0e9-0616-440e-90f2-a12524e1bee4)  
(輕微)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統之 Windows 7 中的 Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=a584cd0f-2e05-4e36-8858-0ffead637162)  
(重大)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-001**](https://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](https://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**輕微**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?familyid=308166e4-571b-4d6c-bd9f-3ed4afa4eafe)\*\*  
(輕微)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統之 Windows Server 2008 R2 中的 Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d3386793-a594-4bc5-8308-28b561d43087)\*\*  
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?familyid=1d0da42b-9755-4fd2-afd1-0d023d187133)  
(輕微)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統之 Windows Server 2008 R2 中的 Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=9d137bab-8312-4240-af74-c65ba652fde0)  
(重大)
</td>
</tr>
</table>
 
Windows Server 2008 和 Windows Server 2008 R2 注意事項

**\*\*Server Core 安裝不受影響。** 如果 Windows Server 2008 或 Windows Server 2008 R2 是使用 Server Core 安裝選項所安裝，則這項更新解決的弱點並不會影響受支援的 Windows Server 2008 或 Windows Server 2008 R2。 如需此安裝選項的詳細資訊，請參閱 MSDN 文章：[伺服器核心](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英文) 以及[適用於 Windows Server 2008 R2 的伺服器核心](https://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 及 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和資訊安全更新。 如需更多資訊，請參閱 [TechNet 更新管理中心](https://technet.microsoft.com/zh-tw/updatemanagement/default.aspx)。 [TechNet Security Center](https://technet.microsoft.com/zh-tw/security/default.aspx) 提供 Microsoft 產品安全性的其他資訊。 消費者可以造訪[在家上網的安全性](https://www.microsoft.com/taiwan/protect/default.mspx)網站，只要按一下 \[最新資訊安全更新\] 即可在此網站取得此資訊。

資訊安全更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 以及 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 取得。 資訊安全更新也可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得。 您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。

最後，您可以從 [Microsoft Update Catalog](https://go.microsoft.com/fwlink/?linkid=96155) 下載資訊安全更新。 Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括資訊安全更新、驅動程式和 Service Pack。 只要以資訊安全公告編號 (例如：MS07-036) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。 如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](https://go.microsoft.com/fwlink/?linkid=97900)。

**注意**：自 2009 年 8 月 1 日開始，Microsoft 已停止支援 Office Update 與 Office Update Inventory Tool。 若要繼續取得 Microsoft Office 產品的最新更新，請使用 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)。 如需更多資訊，請參閱[關於 Microsoft Office Update： 常見問題集](https://office.microsoft.com/en-us/downloads/fx010402221033.aspx) (英文)。

**偵測與部署指南**

Microsoft 針對資訊安全更新提供偵測和部署指南。 本指南所含之建議和資訊，能幫助 IT 專業人員瞭解如何使用用於資訊安全更新的偵測和部署的各種工具。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 961747](https://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少資訊安全更新以及一般安全性設定錯誤的狀況。 如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134) 網站 (英文)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速而可靠地將 Microsoft Windows 2000 作業系統及更新版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 適用的最新重大更新與資訊安全更新部署到 Microsoft Windows 2000 及更新版本的作業系統中。

如需更多關於利用 Windows Server Update Services 部署資訊安全更新的資訊，請造訪 [Windows Server Update Services](https://www.microsoft.com/taiwan/windowsserversystem/updateservices/evaluation/overview.mspx) 網站。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要資訊安全更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。 現已推出新版的 SMS，System Center Configuration Manager 2007；另請參閱 [System Center Configuration Manager 2007](https://technet.microsoft.com/en-us/library/bb735860.aspx)。如需更多有關系統管理員如何能使用 SMS 2003 部署資訊安全更新的資訊，請參閱 [SMS 2003 安全性修補程式管理](https://go.microsoft.com/fwlink/?linkid=22939) (英文)。 SMS 2.0 使用者也可以使用資訊安全更新盤點工具 (Security Update Inventory Tool，SUIT) 來協助部署資訊安全更新。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server](https://www.microsoft.com/taiwan/smserver/)。

**注意**：SMS 使用 Microsoft Baseline Security Analyzer 提供廣泛的資訊安全公告更新偵測與部署支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](https://go.microsoft.com/fwlink/?linkid=33341)。 某些資訊安全更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可使用 Elevated Rights Deployment Tool (隨 [SMS 2.0 Administration Feature Pack (英文)](https://go.microsoft.com/fwlink/?linkid=21161) 提供) 來安裝這些更新。

**Update Compatibility Evaluator 和應用程式相容性工具組**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。 這可能會觸發不相容性，而拉長部署資訊安全更新的時間。 您可以使用 [Application Compatibility Toolkit](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 隨附的 [Update Compatibility Evaluator](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 元件，針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Microsoft Windows Vista、Windows Update、Microsoft 資訊安全更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非安全性、高優先順序更新

如需在 Windows Update 和 Microsoft Update 上發行的非資訊安全更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](https://support.microsoft.com/kb/894199)： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。 其中也包括所有 Windows 的內容。
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
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的資訊安全更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](https://support.microsoft.com/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](https://technet.microsoft.com/zh-tw/security/cc136632.aspx)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](https://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 [Google Inc.](https://www.google.com/) 的 Tavis Ormandy 回報 MS10-001 中描述的問題
-   [感謝 David Lindsay「thornmaker」](https://p42.us/)及 [Eduardo A. Vela Nava「sirdarckcat」](https://www.sirdarckcat.net/)回報 MS10-002 中描述的問題
-   感謝 Lostmon Lord 回報 MS10-002 中描述的問題
-   感謝 Brett Moore 與 [TippingPoint](https://www.tippingpoint.com/) 及 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 MS10-002 中描述的問題
-   感謝 [team509](https://www.team509.com/) 的 Wushi 與 [TippingPoint](https://www.tippingpoint.com/) 及 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 MS10-002 中描述的問題
-   感謝 eshu.co.uk 的 Sam Thomas 與 [TippingPoint](https://www.tippingpoint.com/) 和 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 MS10-002 中描述的問題
-   感謝 eshu.co.uk 的 Sam Thomas 與 [TippingPoint](https://www.tippingpoint.com/) 和 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 MS10-002 中描述的問題
-   感謝 Fortinet [FortiGuard Global Security Research Team](https://www.fortiguardcenter.com/) 的 Haifei Li 回報 MS10-002 中描述的問題
-   感謝 [Verisign iDefense Labs](https://labs.idefense.com/) 的 Peter Vreugdenhil 與 [TippingPoint](https://www.tippingpoint.com/) 及 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 MS10-002 中描述的問題。
-   感謝 [BugSec](https://www.bugsec.com/) 的 Meron Sellem 回報 MS10-002 中描述的問題

Microsoft [感謝](https://go.microsoft.com/fwlink/?linkid=21127)下列公司與我們合作並提供關於 MS10-002 所述問題的詳細資訊：

-   [Google Inc.](https://www.google.com/) 與 [MANDIANT](https://www.mandiant.com/)
-   [Adobe](https://www.adobe.com/)
-   [McAfee](https://www.mcafee.com/)

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可洽詢[安全性支援](https://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 以取得技術支援。 與資訊安全更新有關的支援電話不另外收費。 如需更多可用支援選項的資訊，請參閱 [Microsoft 技術支援服務](https://support.microsoft.com/?ln=zh-tw)。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與資訊安全更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](https://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2010 年 1 月 13 日)： 公告摘要發行。
-   V2.0 (2010 年 1 月 22 日)： 新增 Microsoft 資訊安全公告 [MS10-002：Internet Explorer 積存更新 (978207)](https://technet.microsoft.com/security/bulletin/ms10-002)。 另外還新增此不定期資訊安全公告的公告網路廣播連結。

*Built at 2014-04-18T01:50:00Z-07:00*
