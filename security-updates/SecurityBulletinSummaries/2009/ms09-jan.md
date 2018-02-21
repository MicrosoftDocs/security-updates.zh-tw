---
TOCTitle: 'MS09-JAN'
Title: 2009 年 1 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms09-jan'
ms:contentKeyID: 61237693
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms09-jan(v=Security.10)'
---

2009 年 1 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2009年1月14日

**版本:** 1.0

此公告摘要列出 2009 年 1 月份發行之安全性公告。

發行 2009 年 1 月份公告之後，此公告摘要將取代原先於 2009 年 1 月 8 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](http://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2009 年 1 月 14 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。 [立即註冊參加 1 月份安全性公告網路廣播](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032395120)。 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](http://www.microsoft.com/taiwan/security/bulletins/default.mspx)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性、高優先順序更新的優先順序，其中這些非安全性、高優先順序更新的發行日期與每月安全性更新的發行日期相同。 請參閱＜其他資訊＞一節。

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-001">MS09-001</a></td>
<td style="border:1px solid black;"><strong>SMB 中的弱點可能會允許遠端執行程式碼 (958687)</strong><br />
<br />
這個安全性更新在解決Microsoft 伺服器訊息區 (SMB) 通訊協定中兩個未公開以及一個已經被公開的弱點。 弱點可能會在受影響的系統上允許遠端執行程式碼。 成功地利用這些弱點的攻擊者可以安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 最佳實作的防火牆和標準預設防火牆設定有助於防止網路受到來自企業外的攻擊。 最佳方式建議連線至網際網路的系統盡可能曝露最少數量的連接埠。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
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
  
請用這個表格來瞭解您可能需要安裝的每個安全性更新，與 30 天內已發行的可利用程式碼受影響之可能性。 您應該檢閱下列的每個評估，按照特定的設定，將部署以優先次序排序。 如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](http://technet.microsoft.com/en-us/security/cc998259.aspx)。
  
| 公告編號                                                            | 公告標題                                      | CVE ID                                                                           | 弱點索引評估                                                                                            | 主要重點                                                                                                                                                                                                                                                                            |  
|---------------------------------------------------------------------|-----------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-001](http://technet.microsoft.com/security/bulletin/ms09-001) | SMB 中的弱點可能會允許遠端執行程式碼 (958687) | [CVE-2008-4114](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4114) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 這只是一個拒絕服務弱點。                                                                                                                                                                                                                                                            |  
| [MS09-001](http://technet.microsoft.com/security/bulletin/ms09-001) | SMB 中的弱點可能會允許遠端執行程式碼 (958687) | [CVE-2008-4834](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4834) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | 若此為一遠端執行程式碼弱點，則不太可能撰寫出可利用此漏洞的程式碼。 如需更多資訊，請參閱 Microsoft 安全性弱點研究與防禦部落格：[排定 SMB 公告部署的優先順序](http://blogs.technet.com/swi/archive/2009/01/09/ms09-001-prioritizing-the-deployment-of-the-smb-bulletin.aspx) (英文)。 |  
| [MS09-001](http://technet.microsoft.com/security/bulletin/ms09-001) | SMB 中的弱點可能會允許遠端執行程式碼 (958687) | [CVE-2008-4835](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4835) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 若此為一遠端執行程式碼弱點，則不太可能撰寫出可利用此漏洞的程式碼。 如需更多資訊，請參閱 Microsoft 安全性弱點研究與防禦部落格：[排定 SMB 公告部署的優先順序](http://blogs.technet.com/swi/archive/2009/01/09/ms09-001-prioritizing-the-deployment-of-the-smb-bulletin.aspx) (英文)。 |
  
受影響的軟體及下載位置  
----------------------
  
<span></span>
下表依據主要的軟體類別和嚴重性依序列出公告。
  
**我該如何使用這些表格？**
  
請用這些表格來瞭解可能需要安裝的安全性更新有哪些。 您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的安全性更新。 若軟體程式或更新出現在清單中，則相關可用軟體更新也會以超連結方式提供，也會列出軟體更新的嚴重性等級。
  
**注意**：一項弱點，可能需要安裝數個安全性更新才能妥善解決。 請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
#### Windows 作業系統與元件

 
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
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-001**](http://technet.microsoft.com/security/bulletin/ms09-001)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=e0678d14-c1b5-457a-8222-8e7682760ed4)  
(重大)  
[Microsoft Windows 2000 Service Pack 4(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=e0678d14-c1b5-457a-8222-8e7682760ed4)  
(重大)

</td>
</tr>
<tr>
<th colspan="2">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-001**](http://technet.microsoft.com/security/bulletin/ms09-001)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 及 Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 與 Windows XP Service Pack 3(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=eeafcdc5-df39-4b29-b6f1-7d32b64761e1)  
(重大)  
[Windows XP Service Pack 2 與 Windows XP Service Pack 3(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=eeafcdc5-df39-4b29-b6f1-7d32b64761e1)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=26898401-f669-4542-ad93-199ed1fe9a2a)  
(重大)
</td>
</tr>
<tr>
<th colspan="2">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-001**](http://technet.microsoft.com/security/bulletin/ms09-001)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 與 Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=588ca8e8-38a9-47ed-9c41-09aaf1022e49)  
(重大)  
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=588ca8e8-38a9-47ed-9c41-09aaf1022e49)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=ee59441c-1e8f-4425-ae8d-dec14e7f13fb)  
(重大)  
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=ee59441c-1e8f-4425-ae8d-dec14e7f13fb)  
(重大)

</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP1 for Itanium-based Systems 和 Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP1 和適用於 Itanium 型系統的 Windows Server 2003 SP2(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=caec9321-fa5b-42f0-9f26-61f673fe6eef)  
(重大)
</td>
</tr>
<tr>
<th colspan="2">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-001**](http://technet.microsoft.com/security/bulletin/ms09-001)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 和 Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=9179c463-c10a-452a-990f-b7e37cdd889b)  
(中度)  
[Windows Vista 和 Windows Vista Service Pack 1(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=9179c463-c10a-452a-990f-b7e37cdd889b)  
(中度)

</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=6b26952e-b59d-4b0f-a52d-025e45ecd233)  
(中度)  
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=6b26952e-b59d-4b0f-a52d-025e45ecd233)  
(中度)

</td>
</tr>
<tr>
<th colspan="2">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-001**](http://technet.microsoft.com/security/bulletin/ms09-001)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=7245b411-7c9e-41e5-9841-4c586336086c)\*  
(中度)  
[適用於 32 位元系統的 Windows Server 2008(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=7245b411-7c9e-41e5-9841-4c586336086c)\*  
(中度)

</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 系統的 Windows Server 2008
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=a241eaad-95a0-442b-978f-f21a6f0c7db4)\*  
(中度)  
[適用於 x64 型系統的 Windows Server 2008(中文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?displaylang=zh-tw&familyid=a241eaad-95a0-442b-978f-f21a6f0c7db4)\*  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008(英文下載更新程式)](http://www.microsoft.com/downloads/details.aspx?familyid=ab7c7015-20bb-4a0c-977a-969f4e2a5189)  
(中度)
</td>
</tr>
</table>
 
**Windows Server 2008 注意事項**

**\*Windows Server 2008 Server Core 安裝會受影響。** 對於受支援的 Windows Server 2008 版本，無論 Windows Server 2008 是否使用 Server Core 安裝選項，這個更新均以相同的嚴重性等級套用。 如需這個安裝選項的詳細資訊，請參閱 [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和安全性更新。 如需更多資訊，請參閱 [TechNet 更新管理中心](http://www.microsoft.com/taiwan/technet/updatemanagement/default.mspx) 。 [TechNet Security Center](http://www.microsoft.com/taiwan/technet/security/default.mspx) 提供 Microsoft 產品安全性的其他資訊。 消費者可以造訪[在家上網的安全性](http://www.microsoft.com/taiwan/athome/security/default.mspx)網站，只要按一下 \[最新安全性更新\] 即可在此網站取得此資訊。

安全性更新可以從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)、[Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)及 [Office Update](http://office.microsoft.com/zh-tw/downloads/default.aspx)取得。 安全性更新也可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得。 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。

最後，您可以從 [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) 下載安全性更新。 Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括安全性更新、驅動程式和 Service Pack。 只要以安全性公告編號 (例如，"MS07-036") 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。 如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](http://go.microsoft.com/fwlink/?linkid=97900)。

**偵測與部署指南**

Microsoft 已提供本月安全性更新之偵測與部署指南。 此指南還能幫助 IT 專業人員瞭解如何使用各項工具來協助部署安全性更新，像是 Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office Detection Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool (加強版安全性更新清查工具，ESUIT)。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 910723](http://support.microsoft.com/kb/910723)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少安全性更新以及一般安全性設定錯誤的狀況。 如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) 網站 (英文)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速可靠地將 Windows 2000 作業系統及更新系統版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 等最新的重大更新與安全性更新部署到 Windows 2000 及更新作業系統版本中。

如需更多關於利用 Windows Server Update Services 部署安全性更新的資訊，請造訪 [Windows Server Update Services](http://www.microsoft.com/taiwan/windowsserversystem/updateservices/evaluation/overview.mspx) 網站。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。 現已推出新版的 SMS，System Center Configuration Manager 2007；另請參閱 [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)。如需更多有關系統管理員如何能使用 SMS 2003 部署安全性更新的資訊，請參閱 [SMS 2003 安全性修補程式管理](http://www.microsoft.com/taiwan/smserver/evaluation/capabilities/patch.htm) 。 SMS 2.0 使用者也可以利用 [SMS 軟體更新服務功能套件](http://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/suspack/default.htm)來協助部署安全性更新。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server](http://www.microsoft.com/taiwan/smserver/)。

**注意：**SMS 使用 Microsoft Baseline Security Analyzer 及 Microsoft Office Detection Tool，為安全性公告更新的偵測及部署作業提供相當廣泛的支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可以用 Elevated Rights Deployment Tool (隨 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/taiwan/smserver/downloads/2003/adminpack.htm) 和 [SMS 管理功能套件](http://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/adminpack/default.htm) 提供) 來安裝這些更新。

**Update Compatibility Evaluator 和應用程式相容性工具組**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。 這可能會觸發不相容性，而拉長部署安全性更新的時間。 您可以使用 [Application Compatibility Toolkit 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 隨附的 [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 元件，針對所安裝的應用程式，簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Microsoft Windows Vista、Windows Update、Microsoft 安全性更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非安全性、高優先順序更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](http://support.microsoft.com/kb/894199)： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。 其中也包括所有 Windows 的內容。
-   [適用於 Microsoft 產品 (除了 Microsoft Windows 以外) 的全新、修訂版以及已發行的更新](http://technet.microsoft.com/en-us/wsus/bb466214.aspx)。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的安全性保護，Microsoft 將在每月發行安全性更新之前，提前向重要安全性軟體提供者提供弱點資訊。 安全性軟體提供者可利用此弱點資訊，透過其安全性軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。 如果要判斷是否有安全性軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://www.microsoft.com/taiwan/security/default.mspx/msrc/mapp/partners.mspx)上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 安全性策略與社群

**更新程式管理策略**

[更新管理安全性指南](http://www.microsoft.com/taiwan/technet/security/topics/patchmanagement.mspx) (英文) 提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](http://support.microsoft.com/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](http://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](http://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝匿名的研究人員與 [TippingPoint](http://www.tippingpoint.com/) 及 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 MS09-001 中描述的問題。
-   感謝匿名的研究人員與 [TippingPoint](http://www.tippingpoint.com/) 及 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 MS09-001 中描述的另一個問題。

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可電洽 1-866-PCSAFETY [Microsoft 產品支援服務](http://go.microsoft.com/fwlink/?linkid=21131)以取得技術支援。 與安全性更新有關的支援電話不另外收費。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與安全性更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](http://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2009 年 1 月 14 日)： 公告摘要發行。

*Built at 2014-04-18T01:50:00Z-07:00*
