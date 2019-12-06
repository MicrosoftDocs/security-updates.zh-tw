---
TOCTitle: 'MS09-SEP'
Title: 2009 年 9 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms09-sep'
ms:contentKeyID: 61237700
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms09-sep(v=Security.10)'
---

2009 年 9 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2009年9月8日 | 更新: 2009年11月11日

**版本:** 3.0

此公告摘要列出 2009 年 9 月份發行之安全性公告。

發行 2009 年 9 月份公告之後，此公告摘要將取代原先於 2009 年 9 月 3 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](https://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2008 年 9 月 9 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。 [立即註冊參加 9 月份安全性公告網路廣播](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032407486&eventcategory=4&culture=en-us&countrycode=us)。 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](https://www.microsoft.com/taiwan/security/bulletins/default.mspx)。

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-045">MS09-045</a></td>
<td style="border:1px solid black;"><strong>JScript 指令碼引擎中的弱點可能允許遠端執行程式碼 (971961)</strong><br />
<br />
這個安全性更新能解決 DHTML 編輯元件 ActiveX 控制項中一項未公開報告的弱點。 攻擊者可蓄意製作網頁以利用此弱點。 當使用者檢視網頁時，此弱點可能會允許遠端執行程式碼。 成功利用此弱點的攻擊者可以取得與登入使用者相同的使用者權限。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-049">MS09-049</a></td>
<td style="border:1px solid black;"><strong>無線區域網路自動設定服務中的弱點可能允許遠端執行程式碼 (970710)</strong><br />
<br />
這個安全性更新可解決無線區域網路自動設定服務中一項未公開報告的弱點。 若用戶端或伺服器已啟用無線網路介面，並收到蓄意製作的無線框架，此弱點可能允許遠端執行程式碼。 未啟用無線網卡的系統，不受這項弱點影響。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-047">MS09-047</a></td>
<td style="border:1px solid black;"><strong>Windows Media 格式中的弱點可能會允許遠端執行程式碼 (973812)</strong><br />
<br />
這個安全性更新可解決 Windows Media 格式中兩項未公開報告的弱點。 如果使用者開啟蓄意製作的媒體檔案，則前述任一弱點可能會允許遠端執行程式碼。 如果使用者以系統管理的使用者權限登入，成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-048">MS09-048</a></td>
<td style="border:1px solid black;"><strong>Windows TCP/IP 中的弱點可能會允許遠端執行程式碼 (967723)</strong><br />
<br />
這個安全性更新可解決傳輸控制通訊協定暨網際網路通訊協定 (TCP/IP) 處理中多項未公開報告的弱點。 如果攻擊者將蓄意製作的 TCP/IP 封包透過網路傳送至正在接聽服務的電腦，則此弱點可能允許遠端執行程式碼。 最佳實作的防火牆和標準預設防火牆設定有助於防止網路受到來自企業外的攻擊。 最佳方式建議連線至網際網路的系統盡可能曝露最少數量的連接埠。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-046">MS09-046</a></td>
<td style="border:1px solid black;"><strong>DHTML 編輯元件 ActiveX 控制項中的弱點可能會允許遠端執行程式碼 (956844)</strong><br />
<br />
這個安全性更新能解決 DHTML 編輯元件 ActiveX 控制項中一項未公開報告的弱點。 攻擊者可蓄意製作網頁以利用此弱點。 當使用者檢視網頁時，此弱點可能會允許遠端執行程式碼。 成功利用此弱點的攻擊者可以取得與登入使用者相同的使用者權限。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
弱點索引  
--------
  
<span></span>
下表提供本月所述每個弱點的利用性評估。 弱點皆根據公告編號和 CVE 編號依序列出。
  
**我該如何使用這個表格？**
  
請用這個表格來瞭解您可能需要安裝的每個安全性更新，與 30 天內已發行的可利用程式碼受影響之可能性。 您應該檢閱下列的每個評估，按照特定的設定，將部署以優先次序排序。 如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](https://technet.microsoft.com/en-us/security/cc998259.aspx)。
  
| 公告編號                                                            | 公告標題                                                               | CVE ID                                                                           | 弱點索引評估                                                                                            | 主要重點                                                                                                  |  
|---------------------------------------------------------------------|------------------------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|  
| [MS09-045](https://technet.microsoft.com/security/bulletin/ms09-045) | JScript 指令碼引擎中的弱點可能允許遠端執行程式碼 (971961)              | [CVE-2009-1920](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1920) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                      |  
| [MS09-046](https://technet.microsoft.com/security/bulletin/ms09-046) | DHTML 編輯元件 ActiveX 控制項中的弱點可能會允許遠端執行程式碼 (956844) | [CVE-2009-2519](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2519) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                      |  
| [MS09-047](https://technet.microsoft.com/security/bulletin/ms09-047) | Windows Media 格式中的弱點可能會允許遠端執行程式碼 (973812)            | [CVE-2009-2498](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2498) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                      |  
| [MS09-047](https://technet.microsoft.com/security/bulletin/ms09-047) | Windows Media 格式中的弱點可能會允許遠端執行程式碼 (973812)            | [CVE-2009-2499](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2499) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                      |  
| [MS09-048](https://technet.microsoft.com/security/bulletin/ms09-048) | Windows TCP/IP 中的弱點可能會允許遠端執行程式碼 (967723)               | [CVE-2008-4609](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4609) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 此屬消耗記憶體的拒絕服務攻擊類型。                                                                        |  
| [MS09-048](https://technet.microsoft.com/security/bulletin/ms09-048) | Windows TCP/IP 中的弱點可能會允許遠端執行程式碼 (967723)               | [CVE-2009-1925](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1925) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | 可能撰寫出可利用此漏洞的程式碼，但在不同環境或系統上可能產生的效果不一定。 拒絕服務是最有可能發生的影響。 |  
| [MS09-048](https://technet.microsoft.com/security/bulletin/ms09-048) | Windows TCP/IP 中的弱點可能會允許遠端執行程式碼 (967723)               | [CVE-2009-1926](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1926) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 此屬消耗記憶體的拒絕服務攻擊類型。                                                                        |  
| [MS09-049](https://technet.microsoft.com/security/bulletin/ms09-049) | 無線區域網路自動設定服務中的弱點可能允許遠端執行程式碼 (970710)        | [CVE-2009-1132](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1132) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | 堆積保護可讓此弱點難以產生效果一致的利用行為。                                                            |
  
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
[**MS09-045**](https://technet.microsoft.com/security/bulletin/ms09-045)
</td>
<td style="border:1px solid black;">
[**MS09-049**](https://technet.microsoft.com/security/bulletin/ms09-049)
</td>
<td style="border:1px solid black;">
[**MS09-047**](https://technet.microsoft.com/security/bulletin/ms09-047)
</td>
<td style="border:1px solid black;">
[**MS09-048**](https://technet.microsoft.com/security/bulletin/ms09-048)
</td>
<td style="border:1px solid black;">
[**MS09-046**](https://technet.microsoft.com/security/bulletin/ms09-046)
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
無
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
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
[JScript 5.1 和 JScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=2bb3af8d-f36c-4497-9f48-fc59bcff2583)  
(KB971961)  
(重大)  
[JScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=b2773db5-b17d-4b98-b4e2-219b23854abd)  
(KB975542)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 9.0](https://www.microsoft.com/download/details.aspx?familyid=02b9dc42-38c2-44b1-a77c-34854f4a86c4)  
(KB968816)  
(重大)
</td>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4<sup>[3]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=6dd4b0f8-6b54-49a6-a6df-9420f9fd3333)  
(重大)
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
[**MS09-045**](https://technet.microsoft.com/security/bulletin/ms09-045)
</td>
<td style="border:1px solid black;">
[**MS09-049**](https://technet.microsoft.com/security/bulletin/ms09-049)
</td>
<td style="border:1px solid black;">
[**MS09-047**](https://technet.microsoft.com/security/bulletin/ms09-047)
</td>
<td style="border:1px solid black;">
[**MS09-048**](https://technet.microsoft.com/security/bulletin/ms09-048)
</td>
<td style="border:1px solid black;">
[**MS09-046**](https://technet.microsoft.com/security/bulletin/ms09-046)
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
[**輕微**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重大**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 及 Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 上的 JScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=0af373b2-2240-4079-a748-a38d1bc06f39)  
(KB971961)  
(重大)  
[Windows XP Service Pack 2 上的 JScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=c933377d-e0bc-4334-bc75-029045d7a62a)<sup>[1]</sup>
(KB971961)  
(重大)  
[Windows XP Service Pack 3 上的 JScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=c933377d-e0bc-4334-bc75-029045d7a62a)  
(KB971961)  
(重大)  
[JScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=992602d8-d857-41cf-b7b1-527afdc1dc0f)<sup>[2]</sup>
(KB971961)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 9.0、Windows Media Format Runtime 9.5 及 Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=6ffc081e-f892-4818-acb9-6d79e15d473c)  
(KB968816)  
(重大)  
(僅限 Windows XP Service Pack 2)  
[Windows Media Format Runtime 9.0、Windows Media Format Runtime 9.5、及 Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=31585f5a-9aaa-40da-b15a-11284b4b800c)  
(KB968816)  
(重大)  
(僅限 Windows XP Service Pack 3)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 2 及 Windows XP Service Pack 3<sup>[3]</sup>
(輕微)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 及 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=8523d5be-88a2-4124-9b02-660f612e2a12)  
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=0d671004-da4e-4dbd-a066-861b53b0c59c)  
(KB971961)  
(重大)  
[JScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=9aae426d-ee9a-4736-b0a2-e0f8890a6895)<sup>[1]</sup>
(KB971961)  
(重大)  
[JScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=00bae02a-64eb-4b91-965f-da2dc987a2ff)<sup>[2]</sup>
(KB971961)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 9.5](https://www.microsoft.com/download/details.aspx?familyid=3780d565-d027-4f54-8fc0-05f5c3c6ba1a)  
(KB968816)  
(重大)  
[Windows Media Format Runtime 9.5 x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=ce515188-db3c-4694-85da-177c8f76b68c)  
(KB968816)  
(重大)  
[Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?familyid=9a465f92-3067-4a5a-9882-1fc2cf796c99)  
(KB968816)  
(重大)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2<sup>[3]</sup>
(輕微)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=dbc33f6b-61bf-409a-89b5-60002192e0e0)  
(重大)
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
[**MS09-045**](https://technet.microsoft.com/security/bulletin/ms09-045)
</td>
<td style="border:1px solid black;">
[**MS09-049**](https://technet.microsoft.com/security/bulletin/ms09-049)
</td>
<td style="border:1px solid black;">
[**MS09-047**](https://technet.microsoft.com/security/bulletin/ms09-047)
</td>
<td style="border:1px solid black;">
[**MS09-048**](https://technet.microsoft.com/security/bulletin/ms09-048)
</td>
<td style="border:1px solid black;">
[**MS09-046**](https://technet.microsoft.com/security/bulletin/ms09-046)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=6acc9d2d-b71f-4b5c-9aea-b217b6ae240b)  
(KB971961)  
(重大)  
[JScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=6af5d034-fd89-42e2-bc18-d44b7a6b0a85)<sup>[1]</sup>
(KB971961)  
(重大)  
[JScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=ecf9f7e2-3104-4de2-8b3d-99dcdcae6e62)<sup>[2]</sup>
(KB971961)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 9.5](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=8654ee33-6083-447f-ae5b-43ef8d8b613d)  
(KB968816)  
(重大)  
[Windows Media Services 9.1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=61cd0581-c36e-4da6-ae95-41609adbe922)  
(KB972554)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=48d82036-2fde-4bb0-a60e-92eed83ddc3f)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=7478f73f-dd20-4cfa-a650-4c84f37ada2f)  
(中度)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.6](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=d0de3ab1-73e9-4a09-841f-81ade41a8c81)  
(KB971961)  
(重大)  
[JScript 5.7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=8f48bc05-ffac-4a21-8d21-dd20355cda8a)<sup>[1]</sup>
(重大)  
[JScript 5.8](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=643f9e2f-2e5b-48dd-b1a0-22ccb633ed18)<sup>[2]</sup>
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 9.5](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=8654ee33-6083-447f-ae5b-43ef8d8b613d)  
(KB968816)  
(重大)  
[Windows Media Format Runtime 9.5 x64 Edition](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=ce515188-db3c-4694-85da-177c8f76b68c)  
(KB968816)  
(重大)  
[Windows Media Services 9.1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=67c46f26-e6df-4ba2-9c03-1590b31e454c)  
(KB972554)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=e0298ddf-026e-4137-8197-ed9d9b889825)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=88bf502d-1a7c-447a-ac4c-401e1698669b)  
(中度)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[JScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=e78cf021-54f5-4526-b5f0-f781aebf9d72&displaylang=en)  
(KB971961)  
(重大)  
[JScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=fb1ca290-cea4-49c0-a37e-613a654bff3c&displaylang=en)<sup>[1]</sup>
(重大)  
[JScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=?...?)<sup>[2]</sup>
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=c948c4d8-5788-4c1a-9fb6-a969b06a888d)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=8d881ff8-f51f-4476-8cb6-2bebd5b2047f)  
(中度)
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
[**MS09-045**](https://technet.microsoft.com/security/bulletin/ms09-045)
</td>
<td style="border:1px solid black;">
[**MS09-049**](https://technet.microsoft.com/security/bulletin/ms09-049)
</td>
<td style="border:1px solid black;">
[**MS09-047**](https://technet.microsoft.com/security/bulletin/ms09-047)
</td>
<td style="border:1px solid black;">
[**MS09-048**](https://technet.microsoft.com/security/bulletin/ms09-048)
</td>
<td style="border:1px solid black;">
[**MS09-046**](https://technet.microsoft.com/security/bulletin/ms09-046)
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
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
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
[JScript 5.7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=bcb12e57-f5d6-4b4e-88ab-13c28137f11a)  
(重大)  
[JScript 5.8](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=80e7390f-df39-4d99-b2e1-01c7f6a951bb)<sup>[2]</sup>
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=e9fe967f-d78d-43c2-bbcc-5098bd20267e)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=d2bdefcc-f6b9-47c3-a55d-a4f33f967828)  
(KB968816)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=7d72f845-9feb-4685-a669-f9d6ab54f9ed)  
(重大)
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
[JScript 5.7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=8b1b76d5-a6b0-4c2f-8768-e55e82c2c118)  
(KB971961)  
(重大)  
[JScript 5.8](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=24457cdd-1973-40c9-9c2d-c1a75fdfa7fa)<sup>[2]</sup>
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=f93470bd-2e6d-4340-88c6-bb212baf750a)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=97f00b25-fb8f-4300-80c0-c63179f32182)  
(KB968816)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=b2930ff1-5f0a-4a5d-bf2a-9fb76dd8da63)  
(重大)
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
[**MS09-045**](https://technet.microsoft.com/security/bulletin/ms09-045)
</td>
<td style="border:1px solid black;">
[**MS09-049**](https://technet.microsoft.com/security/bulletin/ms09-049)
</td>
<td style="border:1px solid black;">
[**MS09-047**](https://technet.microsoft.com/security/bulletin/ms09-047)
</td>
<td style="border:1px solid black;">
[**MS09-048**](https://technet.microsoft.com/security/bulletin/ms09-048)
</td>
<td style="border:1px solid black;">
[**MS09-046**](https://technet.microsoft.com/security/bulletin/ms09-046)
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
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
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
[JScript 5.7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=df88e6e5-78d3-4fa6-858d-b935d812cada)\*  
(重大)  
[JScript 5.8](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=e7b07be6-a4f8-4847-9c55-9b3d2965fa77)\*,<sup>[2]</sup>
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=ac3f6800-bc3e-4b35-a482-54e1a2da1ab5)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=9c111bff-aff6-4ff7-81f6-e736cfcbe3ed)\*\*  
(KB968816)  
(重大)  
[Windows Media Services 2008](https://www.microsoft.com/download/details.aspx?familyid=2801f69b-37d0-4d0f-9632-31382b824d36)\*  
(KB972554)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=35c1d5a9-a953-4fc6-90c0-d2358c7b89e6)\*  
(重大)
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
[JScript 5.7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=f584f8ca-f6b1-4285-a44c-3df5e51e75de)\*  
(重大)  
[JScript 5.8](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=9eddbb89-4178-49c2-836a-2d292fe50936)\*,<sup>[2]</sup>
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=7d1b9b4f-bf35-44aa-a660-afb2ef2c9e30)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=59615c8b-a07f-4326-836d-f17b2fcc4695)\*\*  
(KB968816)  
(重大)  
[Windows Media Services 2008](https://www.microsoft.com/technet/security/bulletin/)\*  
(KB972554)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=6e46822e-f79d-492d-ad01-ee680ad324f5)\*  
(重大)
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
[JScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=b84fca1d-914d-45af-a48c-d9bc5d20c6b7&displaylang=en)  
(KB971961)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2ac76ee2-b1b6-4300-9cba-af33d9dd54eb)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
</table>
 
**Windows Server 2008 注意事項**

**\*Windows Server 2008 Server Core 安裝會受影響。** 對於受支援的 Windows Server 2008 版本，無論 Windows Server 2008 是否使用 Server Core 安裝選項，這個更新均以相同的嚴重性等級套用。 如需這個安裝選項的詳細資訊，請參閱 [Server Core](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 版本；請參閱[比較 Server Core 安裝選項](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**\*\*Windows Server 2008 Server Core 安裝不受影響。** 如果 Windows Server 2008 是使用 Server Core 安裝選項所安裝，則這項更新解決的弱點並不會影響受支援的 Windows Server 2008 版本。 如需這個安裝選項的詳細資訊，請參閱 [Server Core](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 版本；請參閱[比較 Server Core 安裝選項](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**MS09-045 注意事項**

<sup>[1]</sup>在已安裝 Internet Explorer 7 的系統上

<sup>[2]</sup>在已安裝 Internet Explorer 8 的系統上

**MS09-048 注意事項**

<sup>[3]</sup> 沒有可用的更新 如需更多資訊，請參閱 [MS09-048](https://technet.microsoft.com/security/bulletin/ms09-048) 中的＜與本安全性更新相關的常見問題集 (FAQ)＞項目。

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和安全性更新。 如需更多資訊，請參閱 [TechNet 更新管理中心](https://www.microsoft.com/taiwan/technet/updatemanagement/default.mspx) 。 [TechNet 資訊安全中心](https://www.microsoft.com/taiwan/technet/security/default.mspx) 提供 Microsoft 產品安全性的其他資訊。 消費者可以造訪[在家上網的安全性](https://www.microsoft.com/taiwan/athome/security/default.mspx)網站，只要按一下 \[最新安全性更新\] 即可在此網站取得此資訊。

安全性更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 以及 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 取得。 安全性更新也可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得。 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。

最後，您可以從 [Microsoft Update Catalog](https://go.microsoft.com/fwlink/?linkid=96155) 下載安全性更新。 Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括安全性更新、驅動程式和 Service Pack。 只要以安全性公告編號 (例如：MS07-036) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。 如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](https://go.microsoft.com/fwlink/?linkid=97900)。

**注意**自 2009 年 8 月 1 日開始，Microsoft 已停止支援 Office Update 與 Office Update Inventory Tool。 若要繼續取得 Microsoft Office 產品的最新更新，請使用 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)。 如需更多資訊，請參閱[關於 Microsoft Office Update： 常見問題集](https://office.microsoft.com/en-us/downloads/fx010402221033.aspx) (英文)。

**偵測與部署指南**

Microsoft 針對安全性更新提供偵測和部署指南。 本指南所含之建議和資訊，能幫助 IT 專業人員瞭解如何使用用於安全性更新的偵測和部署的各種工具。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 961747](https://support.microsoft.com/kb/961747/zh-tw)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少安全性更新以及一般安全性設定錯誤的狀況。 如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134) 網站 (英文)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速可靠地將 Windows 2000 作業系統及更新系統版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 等最新的重大更新與安全性更新部署到 Windows 2000 及更新作業系統版本中。

如需更多關於利用 Windows Server Update Services 部署安全性更新的資訊，請造訪 [Windows Server Update Services](https://www.microsoft.com/taiwan/windowsserversystem/updateservices/evaluation/overview.mspx) 網站。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。 現已推出新版的 SMS，System Center Configuration Manager 2007；另請參閱 [System Center Configuration Manager 2007](https://technet.microsoft.com/en-us/library/bb735860.aspx)。如需更多有關系統管理員如何能使用 SMS 2003 部署安全性更新的資訊，請參閱 [SMS 2003 安全性修補程式管理](https://www.microsoft.com/taiwan/smserver/evaluation/capabilities/patch.htm) (英文)。 SMS 2.0 使用者也可以使用安全性更新盤點工具 (Security Update Inventory Tool，SUIT) 來協助部署安全性更新。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server](https://www.microsoft.com/taiwan/smserver/)。

**注意**：SMS 使用 Microsoft Baseline Security Analyzer 提供廣泛的安全性公告更新偵測與部署支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](https://go.microsoft.com/fwlink/?linkid=33341)。 某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可以用 Elevated Rights Deployment Tool (隨 [SMS 2003 Administration Feature Pack](https://go.microsoft.com/fwlink/?linkid=33387) (英文) 和 [SMS 管理功能套件](https://go.microsoft.com/fwlink/?linkid=21161) (英文) 提供) 來安裝這些更新。

**Update Compatibility Evaluator 和應用程式相容性工具組**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。 這可能會觸發不相容性，而拉長部署安全性更新的時間。 您可以使用 [Application Compatibility Toolkit](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 隨附的 [Update Compatibility Evaluator](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 元件，針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Microsoft Windows Vista、Windows Update、Microsoft 安全性更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非安全性、高優先順序更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](https://support.microsoft.com/kb/894199/zh-tw)： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。 其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](https://technet.microsoft.com/en-us/wsus/bb456965.aspx)。 顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的安全性保護，Microsoft 將在每月發行安全性更新之前，提前向重要安全性軟體提供者提供弱點資訊。 安全性軟體提供者可利用此弱點資訊，透過其安全性軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。 如果要判斷是否有安全性軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](https://www.microsoft.com/security/msrc/mapp/partners.mspx)上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 安全性策略與社群

**更新程式管理策略**

[更新程式管理安全性指南](https://www.microsoft.com/taiwan/technet/security/topics/patchmanagement.mspx)提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](https://support.microsoft.com/kb/913086/zh-tw)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](https://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](https://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 [team509](https://www.team509.com/) 的 Wushi 與 Zero Day Initiative 合作，回報 MS09-045 中描述的問題
-   感謝 [Google Inc.](https://www.google.com/) 的 Tavis Ormandy 回報 MS09-046 中描述的問題
-   感謝 [NGS Software](https://www.ngssoftware.com/) 的 Peter Winter-Smith 回報 MS09-047 中描述的問題
-   感謝 Alice Carroll Fan Club 的 Hiroshi Noguchi 回報 MS09-047 中描述的問題
-   感謝 [Outpost24](https://www.outpost24.com/) 的 Jack C. Louis 回報 MS09-048 中描述的問題
-   感謝 [Recurity Labs GmbH](https://www.recurity-labs.com/) 的 Felix Lindner 回報 MS09-048 中描述的問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可洽詢[安全性支援](https://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 以取得技術支援。 與安全性更新有關的支援電話不另外收費。 如需更多可用支援選項的資訊，請參閱 [Microsoft 技術支援服務](https://support.microsoft.com/)。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與安全性更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](https://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2009 年 9 月 9 日)： 公告摘要發行。
-   V2.0 (2009 年 9 月 10 日)： 新增 Windows XP Service Pack 2、Windows XP Service Pack 3，以及 Windows XP Professional x64 Edition Service Pack 2 至 MS09-048 的「受影響的軟體」表。但是，這些平台目前沒有可用的更新。 請參閱 MS09-048 的＜與本安全性更新相關的常見問題集 (FAQ)＞中的項目。本公告中提供的安全性更新沒有變更。
-   V3.0 (2009 年 11 月 11 日)： 將 Microsoft Windows 2000 Service Pack 4 上的 JScript 5.7 新增到 MS09-045 的＜受影響的軟體＞表中。

*Built at 2014-04-18T01:50:00Z-07:00*
