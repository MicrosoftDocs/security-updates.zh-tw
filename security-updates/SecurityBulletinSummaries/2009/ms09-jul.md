---
TOCTitle: 'MS09-JUL'
Title: 2009 年 7 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms09-jul'
ms:contentKeyID: 61237694
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms09-jul(v=Security.10)'
---

2009 年 7 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2009年7月15日 | 更新: 2010年3月10日

**版本:** 8.0

此公告摘要列出 2009 年 7 月份發行之安全性公告。

發行 2009 年 7 月份公告之後，此公告摘要將取代原先於 2009 年 7 月 10 日發行的公告預先通知，以及 7 月 24 日原始發行的不定期公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](https://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將於 2009 年 7 月 15 日的太平洋時間早上十一點 (美國與加拿大)，利用網路廣播解答客戶對於這些定期排程公告的問題。 此網路廣播現在可隨選取得。 如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](https://technet.microsoft.com/security/bulletin/summary)。

針對新增至此公告摘要 (MS09-034 及 MS09-035) 第 2.0 版的不定期安全性公告，Microsoft 將舉辦兩場網路廣播解決客戶對於這些公告的問題，時間分別在 2009 年 7 月 28 日的太平洋時間下午一點 (美國與加拿大) 與太平洋時間下午四點 (美國與加拿大)： 現在請註冊 [7 月 28 日，下午一點網路廣播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032422339&culture=en-us)和 [7 月 28 日，下午四點網路廣播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032422341&culture=en-us)。 在此之後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](https://technet.microsoft.com/security/bulletin/summary)。

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-029">MS09-029</a></td>
<td style="border:1px solid black;"><strong>內嵌 OpenType 字型引擎弱點可能允許遠端執行程式碼 (961371)</strong><br />
<br />
本安全性更新解決 Microsoft Windows 元件「內嵌 OpenType (EOT) 字型引擎」中，兩項未公開報告的弱點。 這些弱點可能允許遠端執行程式碼。 成功利用上述任一弱點的攻擊者可以從遠端取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-028">MS09-028</a></td>
<td style="border:1px solid black;"><strong>Microsoft DirectShow 中的弱點可能會允許遠端執行程式碼 (971633)</strong><br />
<br />
這個安全性更新可解決 Microsoft DirectShow 中一項公開揭露和兩項未公開報告的弱點。 如果使用者開啟蓄意製作的 QuickTime 媒體檔案，此弱點可能會允許遠端執行程式碼。 成功利用這類任一弱點的攻擊者可以取得與本機使用者相同的使用者權限。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-032">MS09-032</a></td>
<td style="border:1px solid black;"><strong>ActiveX Kill Bit (刪除位元) 的積存安全性更新 (973346)</strong><br />
<br />
這個安全性更新可解決目前遭到利用的一項未公開報告的弱點。 如果使用者透過具現化 ActiveX 控制項的 Internet Explorer 來檢視蓄意製作的網頁，Microsoft Video ActiveX 控制項的弱點可能會允許遠端執行程式碼。 此 ActiveX 控制項的設計原本不是在 Internet Explorer 中具現化。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-034">MS09-034</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 積存安全性更新 (972260)</strong><br />
<br />
此安全性更新與 Microsoft 安全性公告 MS09-035 共同不定期發行，說明使用易受到影響的 Microsoft Active Template Library (ATL) 版本所開發的元件和控制項中的弱點。 作為深度防禦措施，此 Internet Explorer 安全性更新有助於減輕 Internet Explorer 中，已使用易受攻擊的 ATL 版本所開發的元件和控制項的已知攻擊行為 (請參閱 Microsoft 安全性摘要報告 (973882) 和 Microsoft 安全性公告 MS09-035 的說明)。<br />
<br />
此安全性更新也可解決 Internet Explorer 中三項未公開報告的弱點。 如果使用者使用 Internet Explorer 檢視蓄意製作的網頁，這些弱點可能會允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-033">MS09-033</a></td>
<td style="border:1px solid black;"><strong>Virtual PC 與 Virtual Server 中的弱點可能會允許權限提高 (969856)</strong><br />
<br />
此安全性更新可解決 Microsoft Virtual PC 和 Microsoft Virtual Server 中一項未公開報告的弱點。 成功利用此弱點的攻擊者可執行任意程式碼，並取得受影響之客體作業系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Virtual PC、Virtual Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-031">MS09-031</a></td>
<td style="border:1px solid black;"><strong>在 Microsoft ISA Server 2006 中的弱點可能會造成權限提高 (970953)</strong><br />
<br />
這個安全性更新可解決 Microsoft Internet Security and Acceleration (ISA) Server 2006 中一項未公開報告的弱點。如果攻擊者成功假冒 ISA 伺服器的系統管理使用者帳戶，且已設定此 ISA 伺服器以 Kerberos 限制委派使用 Radius 一次有效密碼 (OTP) 驗證和驗證委派，弱點可能會允許權限提高。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft ISA Server</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-030">MS09-030</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Publisher 中的弱點可能會允許遠端執行程式碼 (969516)</strong><br />
<br />
此安全性更新可解決 Microsoft Office Publisher 中一項未公開報告的弱點，該弱點可在使用者開啟蓄意製作的 Publisher 檔案時，允許從遠端執行程式碼。 成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-035">MS09-035</a></td>
<td style="border:1px solid black;"><strong>Visual Studio Active Template Library 中的弱點可能會允許遠端執行程式碼 (969706)</strong><br />
<br />
此安全性更新解決了 Visual Studio 的 Microsoft Active Template Library(ATL) 公開版本中數個未公開報告的弱點。 此安全性更新特別適用於元件和控制項的開發人員。 使用 ATL 建立及重新分發元件和控制項的開發人員，應安裝此公告中所提供的更新，並遵循所提供的指南，建立不受此安全性公告所述弱點影響的元件和控制項，然後重新分發給客戶。<br />
<br />
此安全性公告所討論的內容是，使用者若載入了以易受影響的 ATL 版本所建立的元件或控制項，當中的弱點可能會允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">中度</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Visual Studio</td>
</tr>
</tbody>
</table>
  
弱點索引  
--------
  
<span></span>
下表提供本月所述每個弱點的利用性評估。 弱點皆根據公告編號和 CVE 編號依序列出。
  
**我該如何使用這個表格？**
  
請用這個表格來瞭解您可能需要安裝的每個安全性更新，與 30 天內已發行的可利用程式碼受影響之可能性。 您應該檢閱下列的每個評估，按照特定的設定，將部署以優先次序排序。 如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](https://technet.microsoft.com/en-us/security/cc998259.aspx)。
  
| 公告編號                                                            | 公告標題                                                                        | CVE ID                                                                           | 弱點索引評估                                                                                            | 主要重點                                               |  
|---------------------------------------------------------------------|---------------------------------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|--------------------------------------------------------|  
| [MS09-028](https://technet.microsoft.com/security/bulletin/ms09-028) | Microsoft DirectShow 中的弱點可能會允許遠端執行程式碼 (971633)                  | [CVE-2009-1537](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1537) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | **此弱點目前在網際網路生態系統中遭到利用。**           |  
| [MS09-028](https://technet.microsoft.com/security/bulletin/ms09-028) | Microsoft DirectShow 中的弱點可能會允許遠端執行程式碼 (971633)                  | [CVE-2009-1538](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1538) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                   |  
| [MS09-028](https://technet.microsoft.com/security/bulletin/ms09-028) | Microsoft DirectShow 中的弱點可能會允許遠端執行程式碼 (971633)                  | [CVE-2009-1539](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1539) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                   |  
| [MS09-029](https://technet.microsoft.com/security/bulletin/ms09-029) | 內嵌 OpenType 字型引擎弱點可能允許遠端執行程式碼 (961371)                       | [CVE-2009-0231](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0231) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                   |  
| [MS09-029](https://technet.microsoft.com/security/bulletin/ms09-029) | 內嵌 OpenType 字型引擎弱點可能允許遠端執行程式碼 (961371)                       | [CVE-2009-0232](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0232) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                   |  
| [MS09-030](https://technet.microsoft.com/security/bulletin/ms09-030) | Microsoft Office Publisher 中的弱點可能會允許遠端執行程式碼 (969516)            | [CVE-2009-0566](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0566) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                   |  
| [MS09-031](https://technet.microsoft.com/security/bulletin/ms09-031) | Microsoft ISA Server 2006 中的弱點可能會導致權限提高 (970953)                   | [CVE-2009-1135](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1135) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                   |  
| [MS09-032](https://technet.microsoft.com/security/bulletin/ms09-032) | ActiveX Kill Bit (刪除位元) 的積存安全性更新 (973346)                           | [CVE-2008-0015](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-0015) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | **此弱點目前在網際網路生態系統中遭到利用。**           |  
| [MS09-033](https://technet.microsoft.com/security/bulletin/ms09-033) | Virtual PC 與 Virtual Server 中的弱點可能會允許權限提高 (969856)                | [CVE-2009-1542](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1542) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | 偶爾可利用的弱點結果即有可能撰寫出利用此漏洞的程式碼。 |  
| [MS09-034](https://technet.microsoft.com/security/bulletin/ms09-034) | Internet Explorer 積存安全性更新 (972260)                                       | [CVE-2009-1917](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1917) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | 可輕易撰寫可利用此漏洞的可靠程式碼。                   |  
| [MS09-034](https://technet.microsoft.com/security/bulletin/ms09-034) | Internet Explorer 積存安全性更新 (972260)                                       | [CVE-2009-1918](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1918) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | 偶爾可利用的弱點結果即有可能撰寫出利用此漏洞的程式碼。 |  
| [MS09-034](https://technet.microsoft.com/security/bulletin/ms09-034) | Internet Explorer 積存安全性更新 (972260)                                       | [CVE-2009-1919](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1919) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | 偶爾可利用的弱點結果即有可能撰寫出利用此漏洞的程式碼。 |  
| [MS09-035](https://technet.microsoft.com/security/bulletin/ms09-035) | Visual Studio Active Template Library 中的弱點可能會允許遠端執行程式碼 (969706) | [CVE-2009-0901](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0901) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | 可輕易撰寫可利用此漏洞的可靠程式碼。                   |  
| [MS09-035](https://technet.microsoft.com/security/bulletin/ms09-035) | Visual Studio Active Template Library 中的弱點可能會允許遠端執行程式碼 (969706) | [CVE-2009-2493](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | 可輕易撰寫可利用此漏洞的可靠程式碼。                   |  
| [MS09-035](https://technet.microsoft.com/security/bulletin/ms09-035) | Visual Studio Active Template Library 中的弱點可能會允許遠端執行程式碼 (969706) | [CVE-2009-2495](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2495) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 不以執行程式碼進行攻擊的資訊洩漏錯誤。                 |
  
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
</tr>
<tr>
<th colspan="5">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-029**](https://technet.microsoft.com/security/bulletin/ms09-029)
</td>
<td style="border:1px solid black;">
[**MS09-028**](https://technet.microsoft.com/security/bulletin/ms09-028)
</td>
<td style="border:1px solid black;">
[**MS09-032**](https://technet.microsoft.com/security/bulletin/ms09-032)
</td>
<td style="border:1px solid black;">
[**MS09-034**](https://technet.microsoft.com/security/bulletin/ms09-034)
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
無
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
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=1efbbd95-cd72-43df-b1ce-7e2b0c0cb9e2)  
(重大)
</td>
<td style="border:1px solid black;">
[DirectX 7.0](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=e3e54348-6548-4162-b4c0-9910ec6e18b3)  
(重大)  
[DirectX 8.1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=ce297c3e-8122-4276-a9c2-d1a404f8028d)  
(重大)  
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=862db2ad-3c1f-4a26-af70-d8c4f5a69dda)\*\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=89d941f0-3f71-46e3-8096-716561396b72)  
(無嚴重性等級\*\*)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=50ffc8f4-7ab7-4e64-9965-5767db5f53cd)  
(重大)  
[Microsoft Internet Explorer 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=93bd1baa-e2fb-4e8c-9dd7-738efef32282)  
(重大)
</td>
</tr>
<tr>
<th colspan="5">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-029**](https://technet.microsoft.com/security/bulletin/ms09-029)
</td>
<td style="border:1px solid black;">
[**MS09-028**](https://technet.microsoft.com/security/bulletin/ms09-028)
</td>
<td style="border:1px solid black;">
[**MS09-032**](https://technet.microsoft.com/security/bulletin/ms09-032)
</td>
<td style="border:1px solid black;">
[**MS09-034**](https://technet.microsoft.com/security/bulletin/ms09-034)
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
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
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
[Windows XP Service Pack 2 與 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=6914167b-6961-480c-a4d4-808cd58a035b)  
(重大)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=09d585cb-481d-4767-875e-9c6ebe456b80)\*\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 與 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=24701af8-b87e-4e85-9463-f50755a1b6ad)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=22bed634-5227-4a22-8df5-801f3e2e232a)  
(重大)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=c874c8f8-0449-42b1-8d8b-901040069568)  
(重大)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=0acc8aaa-0ae1-412a-9f2b-dc7c707cae00)  
(重大)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3b8b019e-e6d8-4ce2-8f1f-3a6399b252d1)  
(重大)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=f8cd4803-82da-467c-8cb1-520f5a6021d4)\*\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2cbf3699-7f79-4006-99e9-0a4c0d394c48)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=35ab0c5e-df3d-4873-8139-d1d98b3ac350)  
(重大)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=113cc76a-c434-42ff-b594-4834989ad5ba)  
(重大)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=29c8d9e6-2cb8-42b6-b0a6-2510fdb49eab)  
(重大)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-029**](https://technet.microsoft.com/security/bulletin/ms09-029)
</td>
<td style="border:1px solid black;">
[**MS09-028**](https://technet.microsoft.com/security/bulletin/ms09-028)
</td>
<td style="border:1px solid black;">
[**MS09-032**](https://technet.microsoft.com/security/bulletin/ms09-032)
</td>
<td style="border:1px solid black;">
[**MS09-034**](https://technet.microsoft.com/security/bulletin/ms09-034)
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
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/security/bulletin/rating)
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
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=018ef53d-f78e-4084-940d-7c86bf59d83c)  
(重大)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=571d57c5-1ef8-4dc4-a1e5-2211a805f0cc)\*\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b0a458d6-c34c-41c7-964a-c130cfcb0d01)  
(中度)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=44852619-58ad-48f2-bc55-e8e1c72b1ba9)  
(中度)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=f4112c25-9e6f-473a-bdbc-3df6dd66e6af)  
(中度)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=f4ae65a7-142f-4953-a542-315dac2ac606)  
(中度)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7f5fc902-f5d8-4a87-a73f-68632f9a0935)  
(重大)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=1779cbc0-0c29-4fac-a3a6-8b335ffcb98e)\*\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8b7a7bb0-80ef-4f25-bc70-3d0ac06007c5)  
(中度)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=bd7f36c6-c5c5-4f19-ab59-39f1aaba7fe2)  
(中度)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=a594ee0d-ec8f-47df-9125-89d0bbf2115d)  
(中度)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=3bc0e17b-898b-4f29-aa29-607527e1c1cd)  
(中度)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=7df0fce2-543c-4e82-85e6-012bfc8bf130)  
(重大)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=48282a89-f849-405a-a31e-2676f45b5042)\*\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=7be36edf-02af-402f-983a-f9ca8128b6b5)  
(中度)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=cdb70acf-77c3-40a4-b6a3-0fbc0fc0d7fc)  
(中度)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=adb6bad2-9931-4ede-856e-bb43bb0f6071)  
(中度)
</td>
</tr>
<tr>
<th colspan="5">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-029**](https://technet.microsoft.com/security/bulletin/ms09-029)
</td>
<td style="border:1px solid black;">
[**MS09-028**](https://technet.microsoft.com/security/bulletin/ms09-028)
</td>
<td style="border:1px solid black;">
[**MS09-032**](https://technet.microsoft.com/security/bulletin/ms09-032)
</td>
<td style="border:1px solid black;">
[**MS09-034**](https://technet.microsoft.com/security/bulletin/ms09-034)
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
無
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
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c67d85c4-25c5-4821-8db9-91764888f893)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6c90240e-c201-4dad-9835-ea71e3527b45)  
(無嚴重性等級\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=d3be9a13-1a5b-4b74-9649-449df923f573)  
(重大)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=b05a19f7-7412-4c2b-ad11-34396e54ca43)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3f8ae651-59f7-48e1-9e8c-8e07c6806964)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d2084e8d-212b-4c39-9163-a71ec6d1b1c7)  
(無嚴重性等級\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=2b23cd74-6cf1-413b-82a7-b602347e3ce6)  
(重大)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=900e9a05-2f71-42de-b603-47e4ac061bcb)  
(重大)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-029**](https://technet.microsoft.com/security/bulletin/ms09-029)
</td>
<td style="border:1px solid black;">
[**MS09-028**](https://technet.microsoft.com/security/bulletin/ms09-028)
</td>
<td style="border:1px solid black;">
[**MS09-032**](https://technet.microsoft.com/security/bulletin/ms09-032)
</td>
<td style="border:1px solid black;">
[**MS09-034**](https://technet.microsoft.com/security/bulletin/ms09-034)
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
無
</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=91f6ee68-0e39-4ec3-b4cd-45f05404e2fb)\*  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0194f994-5821-4fb9-b9e1-ed6af248c995)\*  
(無嚴重性等級\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=92e3af41-71b0-4a28-afc7-123733180ead)\*  
(中度)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=30f99bda-9107-4969-90af-2a30e12acdae)\*  
(中度)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5cdc3014-97b3-47b5-a6b7-cd0e12ec60e4)\*  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4127b125-fdaa-489a-a80c-14b5647ac7e0)\*  
(無嚴重性等級\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=1958ec40-3b7b-43a9-9fdc-742735dcf516)\*  
(中度)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=acd3667b-6676-4010-b23b-e8372dd55f93)\*  
(中度)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=03330a14-9cfa-4146-a3d3-4b7a76975d2d)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4082c776-318c-4e0c-83fc-2f3f472c039a)  
(無嚴重性等級\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=470387ac-6d75-4b7e-8ca5-376b67a8bd4d)  
(中度)
</td>
</tr>
</table>
 
**Windows Server 2008 注意事項**

**\*\*Windows Server 2008 Server Core 安裝不受影響。** 如果 Windows Server 2008 是使用 Server Core 安裝選項所安裝，則這項更新解決的弱點並不會影響受支援的 Windows Server 2008 版本。 如需這個安裝選項的詳細資訊，請參閱 [Server Core](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 版本；請參閱[比較 Server Core 安裝選項](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**MS09-032 注意事項**

*\*嚴重性等級不適用此更新，因為此公告討論的弱點不會影響此軟體。 但是，做為在未來保護所識別之任何新模式的深度防禦措施，Microsoft 建議此軟體的客戶套用此安全性更新。

**MS09-028 注意事項**

\***DirectX 8.1 的更新也適用於 DirectX 8.1b。

\***DirectX 9.0 的更新也適用於 DirectX 9.0a、DirectX 9.0b 及 DirectX 9.0c。

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
[**MS09-030**](https://technet.microsoft.com/security/bulletin/ms09-030)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Publisher 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=d4b0665d-5744-49c7-a3c0-f231fd08d3b8)  
(KB969693)  
(重要)
</td>
</tr>
</table>
 

#### Microsoft 開發者工具和軟體

 
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
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-035**](https://technet.microsoft.com/security/bulletin/ms09-035)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=63ce454e-f69c-44e3-89fb-eb23c2e2154e)  
(KB971089)  
(中度)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2005
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=7c8729dc-06a2-4538-a90d-ff9464dc0197)  
(KB971090)  
(中度)  
[Microsoft Visual Studio 2005 Service Pack 1 64 位元裝載 Visual C++ 工具](https://www.microsoft.com/download/details.aspx?familyid=43f96f2a-69c6-4c5e-b72c-0edfa35f4fc2)  
(KB973830)  
(中度)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Embedded CE 6.0
</td>
<td style="border:1px solid black;">
[Windows Embedded CE 6.0](https://www.microsoft.com/download/details.aspx?familyid=99d114f8-4d95-4075-a0f1-45f498f0ade8)\*\*  
(KB974616)  
(中度)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2008
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008](https://www.microsoft.com/download/details.aspx?familyid=8f9da646-94dd-469d-baea-a4306270462c)  
(KB971091)  
(中度)  
[Microsoft Visual Studio 2008](https://www.microsoft.com/download/details.aspx?familyid=e3bb6602-b7f4-4614-9999-77f5c6f66ccd)\*  
(KB973674)  
(中度)  
[Microsoft Visual Studio 2008 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=294de390-3c94-49fb-a014-9a38580e64cb)  
(KB971092)  
(中度)  
[Microsoft Visual Studio 2008 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=75fbf397-5140-4961-92a9-78a88ba7228f)\*  
(KB973675)  
(中度)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual C++ 2005
</td>
<td style="border:1px solid black;">
[Microsoft Visual C++ 2005 Service Pack 1 Redistributable Package](https://www.microsoft.com/download/details.aspx?familyid=766a6af7-ec73-40ff-b072-9112bab119c2)  
(KB973544)  
(中度)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual C++ 2008
</td>
<td style="border:1px solid black;">
[Microsoft Visual C++ 2008 Redistributable Package](https://www.microsoft.com/download/details.aspx?familyid=8b29655e-9da4-4b6b-9ac5-687ca0770f93)  
(KB973551)  
(中度)  
[Microsoft Visual C++ 2008 Service Pack 1 可轉散發套件](https://www.microsoft.com/download/details.aspx?familyid=2051a0c1-c9b5-4b0a-a8f5-770a549fd78c)  
(KB973552)  
(中度)
</td>
</tr>
</table>
 
**MS09-035 注意事項**

\*針對使用 ATL for Smart Devices 的行動應用程式

\*\* 安裝 Windows Embedded CE 6.0 每月更新 (2009 年 12 月)。 這個更新程式封裝僅可以從 Microsoft 下載中心取得。

#### Microsoft 伺服器和安全性軟體

 
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
Microsoft Internet Security and Acceleration Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-031**](https://technet.microsoft.com/security/bulletin/ms09-031)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server 2006
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2006](https://www.microsoft.com/download/details.aspx?familyid=c4e9b1dd-526d-407b-bc23-ebc2738b1b19)  
(KB970811)  
(重要)  
[Microsoft Internet Security and Acceleration Server 2006 支援性更新](https://www.microsoft.com/download/details.aspx?familyid=e8ccd770-a925-411c-b994-78e4cf5c3476)  
(KB970811)  
(重要)  
[Microsoft Internet Security and Acceleration Server 2006 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=e536cfed-c1af-4868-b2ac-79178d6355a5)  
(KB971143)  
(重要)
</td>
</tr>
</table>
 

#### Microsoft 虛擬軟體

 
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
Microsoft Virtual PC
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-033**](https://technet.microsoft.com/security/bulletin/ms09-033)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Virtual PC 2004
</td>
<td style="border:1px solid black;">
[Microsoft Virtual PC 2004 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=56a160e1-59b5-45bc-aecf-dfe614a7efad)  
(KB969856)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual PC 2007
</td>
<td style="border:1px solid black;">
[Microsoft Virtual PC 2007](https://www.microsoft.com/download/details.aspx?familyid=5318c1fa-daf1-4028-832b-eaec9906a46a)  
(KB969856)  
(重要)  
[Microsoft Virtual PC 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=88de1513-8d35-410f-8896-fe668f885ca0)  
(KB969856)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Virtual PC 2007 x64 Edition
</td>
<td style="border:1px solid black;">
[Microsoft Virtual PC 2007 x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=5318c1fa-daf1-4028-832b-eaec9906a46a)  
(KB969856)  
(重要)  
[Microsoft Virtual PC 2007 x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=88de1513-8d35-410f-8896-fe668f885ca0)  
(KB969856)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Virtual Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS09-033**](https://technet.microsoft.com/security/bulletin/ms09-033)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual Server 2005 R2
</td>
<td style="border:1px solid black;">
[Microsoft Virtual Server 2005 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=1481024d-b430-4d0e-be16-2f141c6a7e57)  
(KB969856)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Virtual Server 2005 R2
</td>
<td style="border:1px solid black;">
[Microsoft Virtual Server 2005 R2 x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=1481024d-b430-4d0e-be16-2f141c6a7e57)  
(KB969856)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual Server 2005 R2 x64 Edition
</td>
<td style="border:1px solid black;">
[Microsoft Virtual Server 2005 R2 x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=1481024d-b430-4d0e-be16-2f141c6a7e57)  
(KB969856)  
(重要)
</td>
</tr>
</table>
 

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和安全性更新。 如需更多資訊，請參閱 [TechNet 更新管理中心](https://www.microsoft.com/taiwan/technet/updatemanagement/default.mspx) (英文)。 [TechNet Security Center](https://www.microsoft.com/taiwan/technet/security/default.mspx) 提供 Microsoft 產品安全性的其他資訊。 消費者可以造訪[在家上網的安全性](https://www.microsoft.com/taiwan/protect/default.mspx)網站，只要按一下 \[最新安全性更新\] 即可在此網站取得此資訊。

安全性更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 以及 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 取得。 安全性更新也可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得。 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。

最後，您可以從 [Microsoft Update Catalog](https://go.microsoft.com/fwlink/?linkid=96155) 下載安全性更新。 Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括安全性更新、驅動程式和 Service Pack。 只要以安全性公告編號 (例如：MS07-036) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。 如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](https://go.microsoft.com/fwlink/?linkid=97900)。

**注意：**從 2009 年 8 月 1 日開始，Microsoft 將停止支援 Office Update 與 Office Update Inventory Tool。 若要繼續取得 Microsoft Office 產品的最新更新，請使用 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)。 如需更多資訊，請參閱[關於 Microsoft Office Update： 常見問題集](https://office.microsoft.com/en-us/downloads/fx010402221033.aspx) (英文)。

**偵測與部署指南**

Microsoft 已提供本月安全性更新之偵測與部署指南。 此指南還能幫助 IT 專業人員瞭解如何使用各項工具來協助部署安全性更新，像是 Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office Detection Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool (加強版安全性更新清查工具，ESUIT)。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 910723](https://support.microsoft.com/kb/910723/zh-tw)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少安全性更新以及一般安全性設定錯誤的狀況。 如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134) 網站 (英文)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速可靠地將 Windows 2000 作業系統及更新系統版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 等最新的重大更新與安全性更新部署到 Windows 2000 及更新作業系統版本中。

如需更多關於利用 Windows Server Update Services 部署安全性更新的資訊，請造訪 [Windows Server Update Services](https://www.microsoft.com/taiwan/windowsserversystem/updateservices/evaluation/overview.mspx) 網站。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。 現已推出新版的 SMS，System Center Configuration Manager 2007；另請參閱 [System Center Configuration Manager 2007](https://www.microsoft.com/taiwan/systemcenter/configmgr/default.mspx)。如需更多有關系統管理員如何能使用 SMS 2003 部署安全性更新的資訊，請參閱 [SMS 2003 安全性修補程式管理](https://www.microsoft.com/taiwan/smserver/evaluation/capabilities/patch.htm) (英文)。 SMS 2.0 使用者也可以利用 [SMS 軟體更新服務功能套件](https://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/suspack/default.htm)來協助部署安全性更新。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server](https://www.microsoft.com/taiwan/smserver/)。

**注意：**SMS 使用 Microsoft Baseline Security Analyzer 及 Microsoft Office Detection Tool，為安全性公告更新的偵測及部署作業提供相當廣泛的支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](https://go.microsoft.com/fwlink/?linkid=33341)。 某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可以用 Elevated Rights Deployment Tool (隨 [SMS 2003 Administration Feature Pack](https://www.microsoft.com/taiwan/smserver/downloads/2003/adminpack.htm) (英文) 和 [SMS 管理功能套件](https://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/adminpack/default.htm) (英文) 提供) 來安裝這些更新。

**Update Compatibility Evaluator 和應用程式相容性工具組**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。 這可能會觸發不相容性，而拉長部署安全性更新的時間。 您可以使用 [Application Compatibility Toolkit 5.0](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 隨附的 [Update Compatibility Evaluator](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 元件，針對所安裝的應用程式，簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Microsoft Windows Vista、Windows Update、Microsoft 安全性更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非安全性、高優先順序更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](https://support.microsoft.com/kb/894199/zh-tw)： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。 其中也包括所有 Windows 的內容。
-   [適用於 Microsoft 產品 (除了 Microsoft Windows 以外) 的全新、修訂版以及已發行的更新](https://technet.microsoft.com/en-us/wsus/dd573344.aspx)。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的安全性保護，Microsoft 將在每月發行安全性更新之前，提前向重要安全性軟體提供者提供弱點資訊。 安全性軟體提供者可利用此弱點資訊，透過其安全性軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。 如果要判斷是否有安全性軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](https://www.microsoft.com/security/msrc/mapp/partners.mspx)上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 安全性策略與社群

**更新程式管理策略**

[更新管理安全性指南](https://technet.microsoft.com/zh-tw/library/bb466251(en-us).aspx) (英文) 提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](https://support.microsoft.com/kb/913086/zh-tw)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](https://technet.microsoft.com/zh-tw/security/cc136632.aspx)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](https://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 [SkyRecon](https://www.skyrecon.com/) 的 Thomas Garnier，和 [Qihoo 360 Security Center](https://www.360.cn/) 的 Zheng Wenbin、Liu Qi 與 Song Shenlei 合作，共同回報 MS09-028 的問題
-   感謝 [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Yamata Li 回報 MS09-028 中描述的問題
-   感謝 [TippingPoint DVLabs](https://dvlabs.tippingpoint.com/) 的 Aaron Portnoy 以及與 TippingPoint [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作的匿名研究者、[SkyRecon](https://www.skyrecon.com/) 的 Thomas Garnier、[Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Yamata Li 合作，共同回報 MS09-028 的問題
-   感謝 [VeriSign iDefense Labs](https://labs.idefense.com/) 回報 MS09-029 中描述的問題
-   感謝 Thomas Garnier 回報 MS09-029 中描述的問題
-   感謝 [Labo Skopia](https://www.laboskopia.com/) 的 Lionel d'Hauenens 與 [VersiSign iDefense Labs](https://www.idefense.com/) 合作，共同回報 MS09-028 的問題
-   感謝 [IBM IIS X-Force](https://www.iss.net/) 的 Ryan Smith 和 Alex Wheeler 最初回報 MS09-032 中描述的問題
-   感謝 [Google Inc.](https://www.google.com/) 的 Julien Tinnes 與 Tavis Ormandy 回報 MS09-033 中描述的問題。
-   感謝 [VeriSign iDefense Labs](https://labs.idefense.com/) 的 Peter Vreugdenhil 回報 MS09-034 中描述的問題
-   感謝 [team509](https://www.team509.com/) 的 Wushi 和 Ling 與 [TippingPoint](https://www.tippingpoint.com/) 及 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 MS09-034 中描述的問題
-   感謝 Peter Vreugdenhil 與 [TippingPoint](https://www.tippingpoint.com/) 及 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 MS09-034 中描述的問題。
-   感謝 [IBM ISS X-Force](https://www.iss.net/) 的 David Dewey 回報 MS09-035 中描述的問題
-   感謝 [VeriSign iDefense Labs](https://labs.idefense.com/) 的 Ryan Smith 回報 MS09-035 中描述的兩個問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可洽詢[安全性支援](https://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 以取得技術支援。 與安全性更新有關的支援電話不另外收費。 如需更多可用支援選項的資訊，請參閱 [Microsoft 技術支援服務](https://support.microsoft.com/?ln=zh-tw)。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與安全性更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](https://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2009 年 7 月 14 日)： 公告摘要發行。
-   V1.1 (2009 年 7 月 15 日)： 更新 MS09-032 的提要；修正 MS09-029 的重新開機需求；以及執行其他編輯。
-   V2.0 (2009 年 7 月 28 日)： 新增 Microsoft 安全性公告 MS09-034，適用於 Internet Explorer 的積存安全性更新 (972260)，以及 MS09-035，即 Visual Studio 作用中範本程式庫可能允許遠端執行程式碼的弱點 (969706)。 另外，還新增這些不定期安全性公告的公告網路廣播連結。
-   V3.0 (2009 年 8 月 4 日)： 修訂以宣佈重新發佈 Microsoft Windows 2000 Service Pack 4 中 Microsoft Internet Explorer 6 Service Pack 1 的更新。已安裝 Microsoft Windows 2000 Service Pack 4 中 Microsoft Internet Explorer 6 Service Pack 1 原始更新的所有客戶皆已受到保護。 但是，使用 Internet Explorer 6 Service Pack 1 韓文版本的客戶，可能需要在其 Windows 2000 系統中重新安裝 Internet Explorer 6 Service Pack 1 的更新，才能擁有相同保護並解決列印問題。 請參閱 Microsoft 安全性公告 MS09-034。
-   V4.0 (2009 年 8 月 11 日)： 修訂以宣佈重新發行 MS09-035。重新發行 MS09-035 旨在提供適用於 Microsoft Visual Studio 2005 Service Pack 1 (KB973673)、Microsoft Visual Studio 2008 (KB973674) 和 Microsoft Visual Studio 2008 Service Pack 1 (KB973675) 的更新，以及提供給從事以下工作的開發人員：使用 Visual Studio，針對使用 ATL for Smart Devices 的行動應用程式，建立其元件和控制項。
-   V4.1 (2009 年 8 月 13 日)： 更正 MS09-035 的重新開機需求。
-   V5.0 (2009 年 8 月 19 日)： 新增 MS09-028 公告的註腳，為 DirectX 8.1 說明受影響的軟體。
-   V6.0 (2009 年 8 月 25 日)： 修訂以宣佈重新發行 Windows XP Service Pack 2、Windows XP Service Pack 3，以及 Windows XP Professional x64 Edition Service Pack 2 的日文語言更新。已安裝原始更新的所有客戶皆已受到保護。 但是，擁有 Windows XP Service Pack 2、Windows XP Service Pack 3 或 Windows XP Professional x64 Edition Service Pack 2 日文語言版本的客戶應重新安裝更新以擁有相同的保護，而且還能解決列印問題。 請參閱 Microsoft 安全性公告 MS09-029。
-   V7.0 (2010 年 1 月 12 日)： 修訂公告，以新增 Windows Embedded CE 6.0 至 MS09-035 的受影響軟體。Windows Embedded CE 6.0 的更新 (KB974616) 是積存更新，僅可以從 Microsoft 下載中心取得。 使用 Windows Embedded CE 6.0 平台的客戶應該考慮套用此積存更新。
-   V8.0 (2010 年 3 月 9 日)： 修訂公告，將 Microsoft Virtual Server 2005 新增為 MS09-033 的受影響軟體。

*Built at 2014-04-18T01:50:00Z-07:00*
