---
TOCTitle: 'MS08-NOV'
Title: 2008 年 11 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms08-nov'
ms:contentKeyID: 61237686
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms08-nov(v=Security.10)'
---

2008 年 11 月份 Microsoft 資訊安全公告摘要
==========================================

發行: 2008年11月11日 | 更新: 2009年10月14日

**版本:** 3.0

此公告摘要列出 2008 年 11 月份發行之安全性公告。

發行 2008 年 11 月份公告之後，此公告摘要將取代原先於 2008 年 11 月 6 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](http://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2008 年 11 月 12 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。 [立即註冊參加 11 月份安全性公告網路廣播](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374642)。 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](http://technet.microsoft.com/security/bulletin/summary)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性、高優先順序更新的優先順序，其中這些非安全性、高優先順序更新的發行日期與每月安全性更新的發行日期相同。 請參閱＜其他資訊＞一節。

### 公告資訊

#### 提要

本月份安全性公告依嚴重性列出如下：

重大 (1)
--------

<span></span>

| 公告編號             | Microsoft 安全性公告 MS08-069                                                                                                                                                                                                                |
|----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Microsoft XML Core Services 的弱點可能會允許遠端執行程式碼 (955218)**](http://go.microsoft.com/fwlink/?linkid=128803)                                                                                                                     |
| **提要**             | 這個安全性更新可解決 Microsoft XML Core Services 中的多個弱點。 如果使用者使用 Internet Explorer 檢視蓄意製作的網頁，最嚴重的弱點可能會允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重大](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                         |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                               |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新可能需要重新啟動電腦。                                                                                                                                       |
| **受影響的軟體**     | **Microsoft Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                 |

重要 (1)
--------

<span></span>

| 公告編號             | Microsoft 安全性公告 MS08-068                                                                                                                                                                                                                                                                                     |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**SMB 中的弱點可能允許遠端執行程式碼 (957097)**](http://go.microsoft.com/fwlink/?linkid=133434)                                                                                                                                                                                                                  |
| **提要**             | 這個安全性更新可解決 Microsoft 伺服器訊息區 (SMB) 通訊協定中一項公開報告的弱點。 弱點可能會在受影響的系統上允許遠端執行程式碼。 成功地利用這些弱點的攻擊者可以安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重要](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                              |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                                    |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 本更新程式需要重新開機。                                                                                                                                                                                                                |
| **受影響的軟體**     | **Microsoft Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                      |

弱點索引
--------

<span></span>
**我該如何使用這個表格？**

請用這個表格來瞭解您可能需要安裝的每個安全性更新，與 30 天內已發行的可利用程式碼受影響之可能性。 您應該檢閱下列的每個評估，按照特定的設定，將部署以優先次序排序。 如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](http://technet.microsoft.com/en-us/security/cc998259.aspx)。

| 公告編號                                                  | 公告標題                                                                                                             | CVE ID                                                                           | 弱點索引評估                                                                                        | 主要重點                                                                             |
|-----------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|
| [MS08-068](http://go.microsoft.com/fwlink/?linkid=133434) | [SMB 中的弱點可能允許遠端執行程式碼 (957097)](http://go.microsoft.com/fwlink/?linkid=133434)                         | [CVE-2008-4037](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4037) | [1 - 可能撰寫出可持續利用此漏洞的程式碼](http://technet.microsoft.com/en-us/security/cc998259.aspx) | 此弱點的可利用程式碼目前在 Windows XP 上為公開。                                     |
| [MS08-069](http://go.microsoft.com/fwlink/?linkid=128803) | [Microsoft XML Core Services 的弱點可能會允許遠端執行程式碼 (955218)](http://go.microsoft.com/fwlink/?linkid=128803) | [CVE-2008-4029](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4029) | [1 - 可能撰寫出可持續利用此漏洞的程式碼](http://technet.microsoft.com/en-us/security/cc998259.aspx) | 針對資訊洩漏的可利用程式碼可能會用於交叉網域攻擊。                                   |
| [MS08-069](http://go.microsoft.com/fwlink/?linkid=128803) | [Microsoft XML Core Services 的弱點可能會允許遠端執行程式碼 (955218)](http://go.microsoft.com/fwlink/?linkid=128803) | [CVE-2007-0099](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2007-0099) | [2 - 可能撰寫出偶而可利用此漏洞的程式碼](http://technet.microsoft.com/en-us/security/cc998259.aspx) | 這個弱點會造成在載入 XML 檔案時發生競爭狀況。 因此，要利用此類漏洞的程式碼非常困難。 |
| [MS08-069](http://go.microsoft.com/fwlink/?linkid=128803) | [Microsoft XML Core Services 的弱點可能會允許遠端執行程式碼 (955218)](http://go.microsoft.com/fwlink/?linkid=128803) | [CVE-2008-4033](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4033) | [2 - 可能撰寫出偶而可利用此漏洞的程式碼](http://technet.microsoft.com/en-us/security/cc998259.aspx) |                                                                                      |

受影響的軟體及下載位置
----------------------

<span></span>
**我該如何使用這個表格？**

請用這個表格來瞭解可能需要安裝的安全性更新有哪些。 您應該查看此處列出的每一種軟體程式或元件，看看是否有需要的安全性更新。 若軟體程式或更新出現在清單中，則相關可用軟體更新也會以超連結方式提供，也會列出軟體更新的嚴重性等級。

**注意**：一項弱點，可能需要安裝數個安全性更新才能妥善解決。 請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。

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
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://go.microsoft.com/fwlink/?linkid=133434)
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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=559cd4b6-24b7-4e60-8749-37d9b833d3eb)  
(KB955069)  
(重大)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(重要)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=44c971e6-96fc-4bba-8f4a-f9d46bda2b6c)  
(重要)
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
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://go.microsoft.com/fwlink/?linkid=133434)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ed1a087-97e2-4283-9b53-b7b046654d08)  
(KB955069)  
(重大)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(重要)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6f8ae0aa-fd68-4156-9016-bba00149793c)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.http//www.microsoft.com/downloads/details.aspx?familyid=6ed1a087-97e2-4283-9b53-b7b046654d08)  
(KB955069)  
(重大)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(重要)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=7493fa37-2cbf-4d66-8690-d50d63da4096)  
(KB954459)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6f8ae0aa-fd68-4156-9016-bba00149793c)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=1b79f220-ebfc-49c1-963b-58bbda21b6e7)  
(KB955069)  
(重大)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(重要)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9501b33b-d639-43e7-ad5a-9e76ed66effd)  
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
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://go.microsoft.com/fwlink/?linkid=133434)
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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 與 Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=0a0f8385-e908-4b5f-b9bf-80b7dabfcafd)  
(KB955069)  
(重大)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(輕微)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(輕微)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=57a0606d-ea7a-4e5b-8b8b-7b77a444ef75)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=347c8c83-4269-4a0e-af6f-4be2e824d22b)  
(KB955069)  
(重大)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(輕微)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(輕微)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=915e001f-9aa0-4fb0-9c2a-0f0c72b4f056)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP1 for Itanium-based Systems 和 Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=3a65e1cd-eb4e-44b6-8868-a5a84be2cb32)  
(KB955069)  
(重大)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(輕微)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(輕微)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP1 和適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=6abf7ba9-825f-4ee2-a2fe-6b1cd9fab622)  
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
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://go.microsoft.com/fwlink/?linkid=133434)
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
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 和 Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=affbc957-1867-4bbe-924d-6f0696ae0895)  
(KB955069)  
(重大)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(重要)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=cb6c4315-8c6d-43af-978b-b190b1a1577a)  
(KB954459)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5612815f-8685-45d2-af4a-164c298a0869)  
(中度)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=b01a5f31-8c57-4c5c-909e-b37caf0439b0)  
(KB955069)  
(重大)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(重要)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=39443046-2093-4c87-ac7b-679deab96414)  
(KB954459)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=727ce9b6-827f-4350-b4ff-c08e8ac541a6)  
(中度)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
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
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://go.microsoft.com/fwlink/?linkid=133434)
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
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=90a04164-4d02-4ce9-b3d8-bddb1ec27618)\*\*  
(KB955069)  
(重大)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)\*\*  
(KB954430)  
(輕微)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=dea9f227-967f-47c7-bb2a-ed68f13645d9)\*\*  
(KB954459)  
(輕微)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008](http://www.microsoft.com/downloads/details.aspx?familyid=b305e894-61ec-46b4-91ee-4c9ac59bc47e)\*  
(中度)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)\*\*  
(KB954430)  
(輕微)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=b7bfe3f4-835f-402c-95b5-6d49b6935308)\*\*  
(KB955069)  
(重大)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)\*\*  
(KB954430)  
(輕微)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=f16e2a5f-37fd-4ee1-aef0-597214323dc4)\*\*  
(KB954459)  
(輕微)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008](http://www.microsoft.com/downloads/details.aspx?familyid=e8d26dfd-b347-4f10-b5b6-27dfff5e4f47)\*  
(中度)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)\*\*  
(KB954430)  
(輕微)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=4e0d1efe-70ac-459b-b330-c0149b74f520)  
(KB955069)  
(重大)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(輕微)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=d4ae74e2-1b09-4a99-8cf5-8a8ca8ac6f7f)  
(KB954459)  
(輕微)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008](http://www.microsoft.com/downloads/details.aspx?familyid=d565467d-e10f-4ddc-a278-3f81a3798686)  
(中度)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(輕微)
</td>
<td style="border:1px solid black;">
不適用
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
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://go.microsoft.com/fwlink/?linkid=133434)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(重要)
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
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
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
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://go.microsoft.com/fwlink/?linkid=133434)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**輕微**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)\*\*  
(KB954430)  
(輕微)
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
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(輕微)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
</table>
 
**\*會影響 Server Core 安裝。** 無論上述受支援的 Windows Server 2008 或 Windows Server 2008 R2 版本是否使用 Server Core 安裝選項安裝，這個更新均以相同的嚴重性等級套用。 如需此安裝選項的詳細資訊，請參閱 MSDN 文章：[伺服器核心](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英文) 以及[適用於 Windows Server 2008 R2 的伺服器核心](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 及 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**\*\*Server Core 安裝不受影響。** 如果 Windows Server 2008 或 Windows Server 2008 R2 是使用 Server Core 安裝選項所安裝，則這項更新解決的弱點並不會影響受支援的 Windows Server 2008 或 Windows Server 2008 R2。 如需此安裝選項的詳細資訊，請參閱 MSDN 文章：[伺服器核心](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英文) 以及[適用於 Windows Server 2008 R2 的伺服器核心](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 及 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

#### Microsoft Office 套件及軟體

 
<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Office 套件、系統和元件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=7ad891a8-c3bb-4479-8282-13d629c410e3)  
(KB951535)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
2007 Microsoft Office System 和 2007 Microsoft Office System Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=27b06ee8-570a-4dc2-a230-c70d4a706245)  
(KB951550)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
其他 Office 軟體
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=7ad891a8-c3bb-4479-8282-13d629c410e3)  
(KB951535)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats 和 Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=27b06ee8-570a-4dc2-a230-c70d4a706245)  
(KB951550)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Expression Web 和 Microsoft Expression Web 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=27b06ee8-570a-4dc2-a230-c70d4a706245)  
(KB951550)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 和 Microsoft Office SharePoint Server 2007 Service Pack 1 (32 位元版本)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=a208f2b5-2b0d-43bb-8f8a-58d4a3fc64f5)  
(KB951597)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 和 Microsoft Office SharePoint Server 2007 Service Pack 1 (64 位元版本)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=0735f4af-e32b-4970-bed7-b2b9323cf54c)  
(KB951597)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Groove Server 2007
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=0735f4af-e32b-4970-bed7-b2b9323cf54c)  
(KB951597)  
(重要)
</td>
</tr>
</table>
 

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和安全性更新。 如需更多資訊，請參閱 [TechNet 更新管理中心](http://go.microsoft.com/fwlink/?linkid=69903) (英文)。 [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) 提供 Microsoft 產品安全性的其他資訊。 消費者可以造訪[在家上網的安全性](http://go.microsoft.com/fwlink/?linkid=85102)網站，只要按一下 \[最新安全性更新\] 即可在此網站取得此資訊。

安全性更新可以從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)、[Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)及 [Office Update](http://go.microsoft.com/fwlink/?linkid=21135)取得。 安全性更新也可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得。 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。

最後，您可以從 [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) 下載安全性更新。 Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括安全性更新、驅動程式和 Service Pack。 只要以安全性公告編號 (例如，"MS07-036") 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。 如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](http://go.microsoft.com/fwlink/?linkid=97900)。

**偵測與部署指南**

Microsoft 已提供本月安全性更新之偵測與部署指南。 此指南還能幫助 IT 專業人員瞭解如何使用各項工具來協助部署安全性更新，像是 Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office Detection Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool (加強版安全性更新清查工具，ESUIT)。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 910723](http://support.microsoft.com/kb/910723)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少安全性更新以及一般安全性設定錯誤的狀況。 如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) 網站 (英文)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速可靠地將 Windows 2000 作業系統及更新系統版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 等最新的重大更新與安全性更新部署到 Windows 2000 及更新作業系統版本中。

如需更多關於利用 Windows Server Update Services 部署安全性更新的資訊，請造訪 [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) 網站。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。 現已推出新版的 SMS，System Center Configuration Manager 2007；另請參閱 [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)。如需更多有關系統管理員如何能使用 SMS 2003 部署安全性更新的資訊，請參閱 [SMS 2003 安全性修補程式管理](http://go.microsoft.com/fwlink/?linkid=22939) (英文)。 SMS 2.0 使用者也可以利用 [SMS 軟體更新服務功能套件](http://go.microsoft.com/fwlink/?linkid=33340)來協助部署安全性更新。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158)。

**注意：**SMS 使用 Microsoft Baseline Security Analyzer 及 Microsoft Office Detection Tool，為安全性公告更新的偵測及部署作業提供相當廣泛的支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可以用 Elevated Rights Deployment Tool (隨 [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) (英文) 和 [SMS 管理功能套件](http://go.microsoft.com/fwlink/?linkid=21161) (英文) 提供) 來安裝這些更新。

**Update Compatibility Evaluator 和應用程式相容性工具組**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。 這可能會觸發不相容性，而拉長部署安全性更新的時間。 您可以使用 [Application Compatibility Toolkit 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 隨附的 [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 元件，針對所安裝的應用程式，簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Microsoft Windows Vista、Windows Update、Microsoft 安全性更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非安全性、高優先順序更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](http://support.microsoft.com/kb/894199)： Software Update Services 與 Windows Server Update Services 的說明內容在 2008 年有所變動。其中也包括所有 Windows 的內容。
-   [適用於 Microsoft 產品 (除了 Microsoft Windows 以外) 的全新、修訂版以及已發行的更新](http://technet.microsoft.com/en-us/wsus/bb466214.aspx)。

#### 安全性策略與社群

**更新程式管理策略**

[更新管理安全性指南](http://go.microsoft.com/fwlink/?linkid=21168) (英文) 提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](http://support.microsoft.com/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](http://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](http://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 Gregory Fleischer 回報 MS08-069 中描述的問題
-   感謝 [Minded Security](http://www.mindedsecurity.com/) 的 Stefano Di Paola 回報 MS08-069 中描述的問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可電洽 1-866-PCSAFETY [Microsoft 產品支援服務](http://go.microsoft.com/fwlink/?linkid=21131)以取得技術支援。 與安全性更新有關的支援電話不另外收費。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與安全性更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](http://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2008 年 11 月 11 日)： 公告摘要發行。
-   V2.0 (2009 年 4 月 29 日)： 將 32 位元和 x64 版本之 Windows Vista Service Pack 2，以及 32 位元、x64 和 Itanium 版本之 Windows Server 2008 Service Pack 2 上的 Microsoft XML Core Services 4.0 (KB954430) 新增為 MS08-069 的受影響軟體。此變更僅屬偵測變更；二進位檔案則保持不變。 已成功安裝 KB954430 的客戶無需重新安裝。
-   V3.0 (2009 年 10 月 14 日)： 將 32 位元和 x64 版本之 Windows 7，以及 x64 和 Itanium 版本之 Windows Server 2008 R2 上安裝的 Microsoft XML Core Services 4.0 (KB954430) 新增為 MS08-069 的受影響軟體。此變更僅屬偵測變更；二進位檔案則保持不變。 已成功安裝 KB954430 的客戶無需重新安裝。

*Built at 2014-04-18T01:50:00Z-07:00*
