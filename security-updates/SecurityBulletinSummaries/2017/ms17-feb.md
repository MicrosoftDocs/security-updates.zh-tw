---
TOCTitle: 'MS17-FEB'
Title: 2017 年 2 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms17-feb'
ms:contentKeyID: 74419995
ms:date: '02/23/2017'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms17-feb(v=Security.10)'
---

2017 年 2 月份 Microsoft 資訊安全公告摘要
=========================================

發行日期：2017 年 2 月 21 日

**版本：** 1.0

此公告摘要列出 2017 年 2 月份發行的資訊安全公告。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知的詳細資訊，請造訪 [Microsoft 技術安全性通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性更新的優先順序，其中這些非安全性更新的發行日期與每月安全性更新的發行日期相同。請參閱**其他資訊**一節。

提醒您，[安全性更新導覽](https://portal.msrc.microsoft.com/zh-tw/security-guidance)將會取代資訊安全公告。請參閱我們的部落格文章[將我們的承諾延續至安全性更新 (英文)](https://blogs.technet.microsoft.com/msrc/2016/11/08/furthering-our-commitment-to-security-updates/)，取得詳細資訊。

提要
----

下表摘要本月安全性公告，以嚴重性高低排序。

如需受影響軟體的詳細資訊，請參閱下一節**＜受影響的軟體＞**。


<p></p>
<table style="width:100%;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告識別碼</strong></td>
<td style="border:1px solid black;"><strong>公告標題與提要</strong></td>
<td style="border:1px solid black;"><strong>最高嚴重性分級<br />
與弱點影響</strong></td>
<td style="border:1px solid black;"><strong>重新啟動需求</strong></td>
<td style="border:1px solid black;"><strong>已知<br />
問題</strong></td>
<td style="border:1px solid black;"><strong>受影響的軟體</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=839437">MS17-005</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player 的安全性更新 (4010250)<br />
</strong>當安裝於所有受支援版本的 Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1、Windows 10 和 Windows Server 2016，此安全性更新可解決 Adobe Flash Player 中的弱點。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Adobe Flash Player</td>
</tr>
</tbody>
</table>
 

弱點入侵指數
------------

下表提供本月所述每個弱點的利用性評估。這些弱點按照公告識別碼和 CVE ID 列出。只會列出公告上達到「重大」或「重要」嚴重性等級的弱點。

**如何使用此表格？**

您可以運用此表格，針對您可能需要安裝的每一項安全性更新，瞭解資訊安全風險在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與阻斷服務 (DoS) 的可能性。檢閱下列各項評估，依據您的具體設定排定本月更新部署之優先順序。如需關於這些等級意義的更多資訊，以及決定等級方式的詳細資訊，請參閱 [Microsoft 弱點入侵指數](http://technet.microsoft.com/zh-tw/security/cc998259)。

下方欄位「最新軟體版本」意指受影響軟體，「較舊軟體版本」意指受影響軟體所有較舊的支援版本，如公告中的「受影響的軟體」或「不受影響的軟體」表格裡所示。

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**CVE ID**                    

</td>
<td style="border:1px solid black;">
**弱點標題**

</td>
<td style="border:1px solid black;">
**最新軟體版本的  
弱點評估**

</td>
<td style="border:1px solid black;">
**較舊軟體版本的  
弱點評估**

</td>
<td style="border:1px solid black;">
**阻斷服務  
弱點評估**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-005: Adobe Flash Player 的安全性更新 (4010250)**](https://go.microsoft.com/fwlink/?linkid=839437)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB17-04](http://helpx.adobe.com/tw/security/products/flash-player/apsb17-04.html)

</td>
<td style="border:1px solid black;">
請參閱 Adobe 資訊安全公告 APSB17-04，了解弱點嚴重性以及更新優先順序等級。

</td>
<td style="border:1px solid black;">
---------

</td>
<td style="border:1px solid black;">
---------

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
</table>
 

受影響的軟體
------------

下表依據主要的軟體類別和嚴重性依序列出公告。

請用這些表格來了解可能需要安裝的安全性更新有哪些。您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的安全性更新。清單中若列出軟體程式或元件，軟體更新的嚴重性等級也會列出來。

**注意**：一項弱點，可能需要安裝數個安全性更新才能妥善解決。請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。

### Windows 作業系統與元件

 
<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS17-005**](https://go.microsoft.com/fwlink/?linkid=839437)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
僅限安全性

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4010250)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 8.1  
每月彙總套件

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
僅限安全性

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4010250)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 8.1  
每月彙總套件

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS17-005**](https://go.microsoft.com/fwlink/?linkid=839437)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**中度**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
僅限安全性

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4010250)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
每月彙總套件

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
僅限安全性

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4010250)  
(中度)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
每月彙總套件

</td>
<td style="border:1px solid black;">
不適用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS17-005**](https://go.microsoft.com/fwlink/?linkid=839437)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
每月彙總套件

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4010250)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS17-005**](https://go.microsoft.com/fwlink/?linkid=839437)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
32 位元系統的 Windows 10

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4010250)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4010250)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4010250)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1511 版

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4010250)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 10 1607 版

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4010250)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 10 1607 版

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4010250)  
(重大)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**

</td>
<td style="border:1px solid black;">
[**MS17-005**](https://go.microsoft.com/fwlink/?linkid=839437)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**

</td>
<td style="border:1px solid black;">
[**重大**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2016

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4010250)  
(重大)

</td>
</tr>
</table>
 

偵測與部署工具及指南
--------------------

有幾項資源可協助系統管理員部署安全性更新。

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，查看是否遺漏安全性更新以及是否存在一般安全設定錯誤。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 可協助系統管理員發佈安全性更新。

應用程式相容性工具組隨附的 Update Compatibility Evaluator 元件可針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

如需上述工具以及其他可使用工具的詳細資訊，請參閱 [IT 專業人員的資訊安全工具](http://technet.microsoft.com/zh-tw/security/cc297183)。 

致謝
----

Microsoft 了解資訊安全業界所做的努力，其盡責地揭露弱點來協助我們保護客戶。請參閱[致謝](https://technet.microsoft.com/zh-tw/library/security/mt745121.aspx)以取得詳細資訊。

其他資訊
--------

### Microsoft Windows 惡意軟體移除工具

針對每個月第二個星期二發行的公告，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 及下載中心發行更新版本的 Microsoft Windows 惡意軟體移除工具。不定期資訊安全公告發行不提供更新版本的 Microsoft Windows 惡意軟體移除工具。

### MU、WU 及 WSUS 上的非安全性更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件 894199](https://support.microsoft.com/zh-tw/kb/894199)：說明 Software Update Services 和 Windows Server Update Services 的內容變更。其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](http://technet.microsoft.com/zh-tw/wsus/bb456965)。顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的安全性保護，Microsoft 將在每月發行安全性更新之前，提前向重要安全性軟體提供者提供弱點資訊。安全性軟體提供者可利用此弱點資訊，透過其安全性軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://go.microsoft.com/fwlink/?linkid=215201) (英文) 上列出的計畫合作夥伴所提供的主動保護計畫網站。

### 安全性策略與社群

**更新程式管理策略**

[更新管理資訊安全指南](http://go.microsoft.com/fwlink/?linkid=21168) (英文) 提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他資訊安全問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得，您也可以利用「安全性更新」(security update) 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 映像檔的方式，取得本月份 Windows Update 提供的資訊安全更新。如需詳細資訊，請參閱 [Microsoft 知識庫文章 913086](https://support.microsoft.com/zh-tw/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全社群](http://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

### 支援

所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。其他版本超出它們的支援週期。若要了解您軟體版本的支援週期，請造訪 [Microsoft 支援週期](http://go.microsoft.com/fwlink/?linkid=21742)網站。

適用於 IT 專業人員的安全性解決方案：[TechNet 安全性疑難排解與支援](http://technet.microsoft.com/zh-tw/security/bb980617)

協助保護您執行 Windows 的電腦免於受到病毒和惡意程式碼攻擊：[病毒解決方案與安全性中心](http://support.microsoft.com/zh-tw/contactus/cu_sc_virsec_master)

根據您所在國家/地區的當地支援：[國際化支援](http://support.microsoft.com/zh-tw/common/international.aspx)

### 免責聲明

Microsoft 知識庫中的資訊係以其「現狀」提供，並不提供任何形式之擔保。Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

### 修訂

-   V1.0 (2017 年 2 月 21 日)：公告摘要發行。

*頁面產生時間：2017-02-21 07:05-08:00。*