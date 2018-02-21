---
TOCTitle: 'MS10-DEC'
Title: 2010 年 12 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms10-dec'
ms:contentKeyID: 61237703
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms10-dec(v=Security.10)'
---

2010 年 12 月份 Microsoft 資訊安全公告摘要
==========================================

發行: 2010年12月15日

**版本:** 1.0

此公告摘要列出 2010 年 12 月份發行之資訊安全公告。

發行 2010 年 12 月份資訊安全公告之後，此公告摘要將取代原先於 2010 年 12 月 9 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 資訊安全公告預先通知](http://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2010 年 12 月 15 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。 [立即註冊參加 12 月份資訊安全公告網路廣播](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032454444&eventcategory=4&culture=en-us&countrycode=us)。 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 資訊安全公告摘要和網路廣播](http://www.microsoft.com/taiwan/security/bulletins/default.mspx)。

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
<th style="border:1px solid black;" >最高的嚴重性等級與資訊安全風險影響</th>
<th style="border:1px solid black;" >重新開機需求</th>
<th style="border:1px solid black;" >受影響的軟體</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-090">MS10-090</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 積存資訊安全更新 (2416400)</strong><br />
<br />
此資訊安全更新可解決 Internet Explorer 中四項未公開報告的資訊安全風險，以及三項公開揭露的資訊安全風險。 最嚴重的資訊安全風險可能會在使用者以 Internet Explorer 檢視蓄意製作的網頁時，允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-091">MS10-091</a></td>
<td style="border:1px solid black;"><strong>OpenType 字型 (OTF) 驅動程式中的資訊安全風險可能會允許遠端執行程式碼 (2296199)</strong><br />
<br />
這個資訊安全更新可解決 Windows OpenType 字型 (OTF) 驅動程式中數個未公開報告的資訊安全風險，這些資訊安全風險可能會允許遠端執行程式碼。 攻擊者可能在網路共用上主控蓄意製作的 OpenType 字型。 當使用者瀏覽至 Windows 檔案總管中的共用時，便會觸發受影響的控制項路徑，允許蓄意製作的字型取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-092">MS10-092</a></td>
<td style="border:1px solid black;"><strong>工作排程器中的資訊安全風險可能會允許權限提高 (2305420)</strong><br />
<br />
此資訊安全更新可解決 Windows 工作排程器中一項公開揭露的資訊安全風險。 如果攻擊者登入受影響的系統，並執行蓄意製作的應用程式，則這些資訊安全風險可能會允許權限提高。 攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項資訊安全風險。 匿名或遠端使用者無法利用這個資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-093">MS10-093</a></td>
<td style="border:1px solid black;"><strong>Windows Movie Maker 中的資訊安全風險可能會允許遠端執行程式碼 (2424434)</strong><br />
<br />
此資訊安全更新可解決 Windows Movie Maker 中一項公開揭露的資訊安全風險。 如果攻擊者引誘使用者開啟與蓄意製作之程式庫檔案位於相同網路目錄的合法 Windows Movie Maker 檔案，則此資訊安全風險可能會允許遠端執行程式碼。 使用者必須造訪不受信任的遠端檔案系統位置或 WebDAV 共用，並從該位置開啟文件，然後使用有資訊安全風險的應用程式載入文件，這類攻擊才會成功。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-094">MS10-094</a></td>
<td style="border:1px solid black;"><strong>Windows Media Encoder 中的資訊安全風險可能會允許遠端執行程式碼 (2447961)</strong><br />
<br />
此資訊安全更新可解決 Windows Media Encoder 中一項公開揭露的資訊安全風險。 如果攻擊者引誘使用者開啟與蓄意製作之程式庫檔案位於相同網路目錄的合法 Windows Media 設定檔 (.prx) 檔案，則此資訊安全風險可能會允許遠端執行程式碼。 使用者必須造訪不受信任的遠端檔案系統位置或 WebDAV 共用，並從該位置開啟文件，然後使用有資訊安全風險的應用程式載入文件，這類攻擊才會成功。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-095">MS10-095</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows 中的資訊安全風險可能會允許遠端執行程式碼 (2385678)</strong><br />
<br />
這個資訊安全更新可解決 Microsoft Windows 中一項未公開報告的資訊安全風險。 如果使用者開啟的檔案類型 (例如 .eml 及 .rss (Windows Live Mail) 或 .wpost (Microsoft Live Writer)) 與蓄意製作之程式庫檔案位於相同的網路資料夾中，則此資訊安全風險可能會允許遠端執行程式碼。 使用者必須造訪不受信任的遠端檔案系統位置或 WebDAV 共用，並從該位置開啟文件，然後使用有資訊安全風險的應用程式載入文件，這類攻擊才會成功。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-096">MS10-096</a></td>
<td style="border:1px solid black;"><strong>Windows 通訊錄中的資訊安全風險可能會允許遠端執行程式碼 (2423089)</strong><br />
<br />
此資訊安全更新可解決 Windows 通訊錄中一項公開揭露的資訊安全風險。 如果使用者開啟與蓄意製作之程式庫檔案位於相同網路資料夾的 Windows 通訊錄檔案，則此資訊安全風險可能會允許遠端執行程式碼。 使用者必須造訪不受信任的遠端檔案系統位置或 WebDAV 共用，並從該位置開啟文件，然後使用有資訊安全風險的應用程式載入文件，這類攻擊才會成功。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-097">MS10-097</a></td>
<td style="border:1px solid black;"><strong>網際網路連線登入精靈中的不安全程式庫載入可能會允許遠端執行程式碼 (2443105)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Windows 網際網路連線登入精靈中一項公開揭露的資訊安全風險。 對於所有受支援版本的 Windows XP 和 Windows Server 2003，此資訊安全更新的等級為「重要」。所有受支援版本的 Windows Vista、Windows Server 2008、Windows 7、Windows Server 2008 R2，皆不受此資訊安全風險影響。<br />
<br />
如果使用者開啟與蓄意製作之程式庫檔案位於相同網路資料夾的 .ins 或 .isp 檔案，則此資訊安全風險可能會允許遠端執行程式碼。 使用者必須造訪不受信任的遠端檔案系統位置或 WebDAV 共用，並從該位置開啟文件，然後使用有資訊安全風險的應用程式載入文件，這類攻擊才會成功。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-098">MS10-098</a></td>
<td style="border:1px solid black;"><strong>Windows 核心模式驅動程式中的資訊安全風險可能會允許權限提高 (2436673)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Windows 中一項公開揭露的資訊安全風險和多項未公開報告的資訊安全風險。 如果攻擊者從本機登入並執行蓄意製作的應用程式，則可能會允許權限提高。 攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這些資訊安全風險。 遠端或匿名使用者無法利用這個資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-099">MS10-099</a></td>
<td style="border:1px solid black;"><strong>路由及遠端存取中的資訊安全風險可能會允許權限提高</strong> (2440591)<br />
<br />
此資訊安全更新可解決 Microsoft Windows 的路由及遠端存取 NDProxy 元件中一項未公開報告的資訊安全風險。 對於所有受支援版本的 Windows XP 和 Windows Server 2003，此資訊安全更新的等級為「重要」。所有受支援版本的 Windows Vista、Windows Server 2008、Windows 7、Windows Server 2008 R2，皆不受此資訊安全風險影響。<br />
<br />
如果攻擊者登入受影響的系統，並執行蓄意製作的應用程式，則此資訊安全風險可能會允許權限提高。 攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項資訊安全風險。 匿名或遠端使用者無法利用這個資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-100">MS10-100</a></td>
<td style="border:1px solid black;"><strong>同意使用者介面中的資訊安全風險可能會允許權限提高 (2442962)</strong><br />
<br />
此資訊安全更新可解決同意使用者介面 (UI) 中一項未公開報告的資訊安全風險。 如果攻擊者在受影響的系統上執行蓄意製作的應用程式，這項資訊安全風險可能會允許權限提高。 攻擊者必須擁有有效的登入認證和 SeImpersonatePrivilege，並能夠從本機登入，才能利用這項資訊安全風險。 匿名或遠端使用者無法利用這個資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-101">MS10-101</a></td>
<td style="border:1px solid black;"><strong>Windows Netlogon 服務中的資訊安全風險可能會允許拒絕服務 (2207559)</strong><br />
<br />
此資訊安全更新可解決 Netlogon RPC 服務中，針對已設定作為網域控制站之受影響版本 Windows Server 的一項未公開報告資訊安全風險。 如果攻擊者將蓄意製作的 RPC 封包傳送至受影響系統上的 Netlogon RPC 服務介面，此資訊安全風險可能會允許拒絕服務。 攻擊者需要在機器上有系統管理員權限，且該機器加入與網域控制站相同的網域，功擊者才能利用此資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
拒絕服務</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-102">MS10-102</a></td>
<td style="border:1px solid black;"><strong>Hyper-V 中的資訊安全風險可能會允許拒絕服務 (2345316)</strong><br />
<br />
這個資訊安全更新能解決 Windows Server 2008 Hyper-V 和 Windows Server 2008 R2 Hyper-V 中一項未公開報告的資訊安全風險。 如果通過驗證的使用者在 Hyper-V 伺服器主控的任何來賓虛擬機器上將蓄意製作的封包傳送到 VMBus，則此資訊安全風險可能會允許拒絕服務。 如果要利用這項資訊安全風險，攻擊者必須具有有效的登入認證，且能夠從來賓虛擬機器傳送蓄意製作的內容。 匿名或遠端使用者無法利用這個資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
拒絕服務</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-103">MS10-103</a></td>
<td style="border:1px solid black;"><strong>Microsoft Publisher 中的資訊安全風險可能會允許遠端執行程式碼 (2292970)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Publisher 中五項未公開報告的資訊安全風險，該類資訊安全風險可在使用者開啟蓄意製作的 Publisher 檔案時，允許從遠端執行程式碼。 成功利用這些資訊安全風險的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-104">MS10-104</a></td>
<td style="border:1px solid black;"><strong>Microsoft SharePoint 中的資訊安全風險可能會允許遠端執行程式碼 (2455005)</strong><br />
<br />
此資訊安全更新可解決 Microsoft SharePoint 中一項未公開報告的資訊安全風險。 如果攻擊者將蓄意製作的 SOAP 要求，傳送到使用文件轉換負載平衡器服務之 SharePoint 伺服器環境中的文件轉換啟動器服務，則此資訊安全風險可能會允許在來賓使用者的安全性內容中遠端執行程式碼。 依照預設，文件轉換負載平衡器服務和文件轉換啟動器服務在 Microsoft Office SharePoint Server 2007 中並不會啟用。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft SharePoint</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-105">MS10-105</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 圖形篩選器中的資訊安全風險可能會允許遠端執行程式碼 (968095)</strong><br />
<br />
這個資訊安全更新可解決 Microsoft Office 中七個未公開報告的資訊安全風險。 如果使用者使用 Microsoft Office 檢視蓄意製作的影像檔，這些資訊安全風險可能會允許遠端執行程式碼。 成功利用這類任一資訊安全風險的攻擊者可以取得與本機使用者相同的使用者權限。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-106">MS10-106</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange Server 中的資訊安全風險可能會允許拒絕服務 (2407132)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Exchange Server 中一項未公開報告的資訊安全風險。 如果通過驗證的攻擊者將蓄意製作的網路訊息傳送至執行 Exchange 服務的電腦，則此資訊安全風險可允許拒絕服務。 最佳實作的防火牆和標準預設防火牆設定有助於防止網路受到來自企業外的攻擊。 最佳方式建議連線至網際網路的系統盡可能曝露最少數量的連接埠。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">中度</a><br />
拒絕服務</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Exchange</td>
</tr>
</tbody>
</table>
  
資訊安全風險索引  
----------------
  
<span></span>
下表提供本月所述每個資訊安全風險的利用性評估。 資訊安全風險根據遞減的資訊安全風險評估等級及 CVE 編號依序列出。 僅包含資訊安全公告中，嚴重性等級為「重大」或「重要」的資訊安全風險。
  
**我該如何使用這個表格？**
  
請用這個表格來瞭解您可能需要安裝的每個資訊安全更新，與 30 天內已發行的可利用程式碼受影響之可能性。 您應該檢閱下列的每個評估，按照特定的設定，將部署以優先次序排序。 如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 資訊安全風險索引](http://technet.microsoft.com/en-us/security/cc998259.aspx)。
  
| 公告編號                                                            | 資訊安全風險標題                                             | CVE ID                                                                           | 資訊安全風險索引評估                                                                                    | 主要重點                                           |  
|---------------------------------------------------------------------|--------------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|----------------------------------------------------|  
| [MS10-103](http://technet.microsoft.com/security/bulletin/ms10-103) | pubconv.dll 中的大小值堆積損毀資訊安全風險                   | [CVE-2010-2569](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2569) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                               |  
| [MS10-103](http://technet.microsoft.com/security/bulletin/ms10-103) | pubconv.dll 中的堆積溢位資訊安全風險                         | [CVE-2010-2570](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2570) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                               |  
| [MS10-097](http://technet.microsoft.com/security/bulletin/ms10-097) | 網際網路連線註冊精靈的不安全程式庫載入資訊安全風險           | [CVE-2010-3144](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3144) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | **這項資訊安全風險已經公開揭露**                   |  
| [MS10-096](http://technet.microsoft.com/security/bulletin/ms10-096) | 不安全程式庫載入資訊安全風險                                 | [CVE-2010-3147](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3147) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | **這項資訊安全風險已經公開揭露**                   |  
| [MS10-092](http://technet.microsoft.com/security/bulletin/ms10-092) | 工作排程器資訊安全風險                                       | [CVE-2010-3338](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3338) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | **此資訊安全風險在網際網路生態系統中遭到利用**     |  
| [MS10-090](http://technet.microsoft.com/security/bulletin/ms10-090) | HTML 物件記憶體損毀資訊安全風險                              | [CVE-2010-3340](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3340) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                               |  
| [MS10-090](http://technet.microsoft.com/security/bulletin/ms10-090) | HTML 物件記憶體損毀資訊安全風險                              | [CVE-2010-3343](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3343) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                               |  
| [MS10-090](http://technet.microsoft.com/security/bulletin/ms10-090) | HTML 元素記憶體損毀資訊安全風險                              | [CVE-2010-3345](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3345) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                               |  
| [MS10-090](http://technet.microsoft.com/security/bulletin/ms10-090) | HTML 元素記憶體損毀資訊安全風險                              | [CVE-2010-3346](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3346) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                               |  
| [MS10-098](http://technet.microsoft.com/security/bulletin/ms10-098) | Win32k 緩衝區溢位資訊安全風險                                | [CVE-2010-3939](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3939) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | **這項資訊安全風險已經公開揭露**                   |  
| [MS10-098](http://technet.microsoft.com/security/bulletin/ms10-098) | Win32k PFE 指標重覆釋放相同記憶體空間資訊安全風險            | [CVE-2010-3940](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3940) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                               |  
| [MS10-098](http://technet.microsoft.com/security/bulletin/ms10-098) | Win32k 滑鼠連結資訊安全風險                                  | [CVE-2010-3943](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3943) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                               |  
| [MS10-098](http://technet.microsoft.com/security/bulletin/ms10-098) | Win32k 記憶體損毀資訊安全風險                                | [CVE-2010-3944](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3944) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                               |  
| [MS10-105](http://technet.microsoft.com/security/bulletin/ms10-105) | FlashPix 影像轉換程式緩衝區溢位資訊安全風險                  | [CVE-2010-3951](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3951) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                               |  
| [MS10-091](http://technet.microsoft.com/security/bulletin/ms10-091) | OpenType 字型重覆釋放相同記憶體空間資訊安全風險              | [CVE-2010-3957](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3957) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                               |  
| [MS10-091](http://technet.microsoft.com/security/bulletin/ms10-091) | OpenType CMAP 表格資訊安全風險                               | [CVE-2010-3959](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3959) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                               |  
| [MS10-100](http://technet.microsoft.com/security/bulletin/ms10-100) | 同意 UI 模擬資訊安全風險                                     | [CVE-2010-3961](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3961) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                               |  
| [MS10-090](http://technet.microsoft.com/security/bulletin/ms10-090) | 未初始化的記憶體損毀資訊安全風險                             | [CVE-2010-3962](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3962) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | **此資訊安全風險目前在網際網路生態系統中遭到利用** |  
| [MS10-099](http://technet.microsoft.com/security/bulletin/ms10-099) | Kernel NDProxy 緩衝區溢位資訊安全風險                        | [CVE-2010-3963](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3963) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                               |  
| [MS10-104](http://technet.microsoft.com/security/bulletin/ms10-104) | 格式錯誤的要求執行程式碼資訊安全風險                         | [CVE-2010-3964](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3964) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                               |  
| [MS10-094](http://technet.microsoft.com/security/bulletin/ms10-094) | 不安全程式庫載入資訊安全風險                                 | [CVE-2010-3965](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3965) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | **這項資訊安全風險已經公開揭露**                   |  
| [MS10-095](http://technet.microsoft.com/security/bulletin/ms10-095) | BranchCache 不安全程式庫載入資訊安全風險                     | [CVE-2010-3966](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3966) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                               |  
| [MS10-093](http://technet.microsoft.com/security/bulletin/ms10-093) | 不安全程式庫載入資訊安全風險                                 | [CVE-2010-3967](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3967) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | **這項資訊安全風險已經公開揭露**                   |  
| [MS10-103](http://technet.microsoft.com/security/bulletin/ms10-103) | Pubconv.dll 中因索引至陣列無效所導致的記憶體損毀資訊安全風險 | [CVE-2010-2571](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2571) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                               |  
| [MS10-098](http://technet.microsoft.com/security/bulletin/ms10-098) | Win32k 重覆釋放相同記憶體空間資訊安全風險                    | [CVE-2010-3941](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3941) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                               |  
| [MS10-098](http://technet.microsoft.com/security/bulletin/ms10-098) | Win32k WriteAV 資訊安全風險                                  | [CVE-2010-3942](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3942) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                               |  
| [MS10-105](http://technet.microsoft.com/security/bulletin/ms10-105) | CGM 影像轉換程式緩衝區溢位資訊安全風險                       | [CVE-2010-3945](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3945) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                               |  
| [MS10-105](http://technet.microsoft.com/security/bulletin/ms10-105) | PICT 影像轉換程式整數溢位資訊安全風險                        | [CVE-2010-3946](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3946) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                               |  
| [MS10-105](http://technet.microsoft.com/security/bulletin/ms10-105) | TIFF 影像轉換程式堆積溢位資訊安全風險                        | [CVE-2010-3947](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3947) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                               |  
| [MS10-105](http://technet.microsoft.com/security/bulletin/ms10-105) | TIFF 影像轉換程式緩衝區溢位資訊安全風險                      | [CVE-2010-3949](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3949) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                               |  
| [MS10-105](http://technet.microsoft.com/security/bulletin/ms10-105) | TIFF 影像轉換程式記憶體損毀資訊安全風險                      | [CVE-2010-3950](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3950) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                               |  
| [MS10-105](http://technet.microsoft.com/security/bulletin/ms10-105) | FlashPix 影像轉換程式堆積損毀資訊安全風險                    | [CVE-2010-3952](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3952) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                               |  
| [MS10-103](http://technet.microsoft.com/security/bulletin/ms10-103) | 陣列索引記憶體損毀資訊安全風險                               | [CVE-2010-3955](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3955) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                               |  
| [MS10-091](http://technet.microsoft.com/security/bulletin/ms10-091) | OpenType 字型索引資訊安全風險                                | [CVE-2010-3956](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3956) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                               |  
| [MS10-101](http://technet.microsoft.com/security/bulletin/ms10-101) | Netlogon RPC Null 解除參照 DOS 資訊安全風險                  | [CVE-2010-2742](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2742) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – 不太可能撰寫出可利用此漏洞的程式碼 | 這只是拒絕服務資訊安全風險                         |  
| [MS10-106](http://technet.microsoft.com/security/bulletin/ms10-106) | Exchange Server 無窮迴圈資訊安全風險                         | [CVE-2010-3937](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3937) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – 不太可能撰寫出可利用此漏洞的程式碼 | 這只是拒絕服務資訊安全風險                         |  
| [MS10-103](http://technet.microsoft.com/security/bulletin/ms10-103) | Microsoft Publisher 記憶體損毀資訊安全風險                   | [CVE-2010-3954](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3954) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – 不太可能撰寫出可利用此漏洞的程式碼 | (無)                                               |  
| [MS10-102](http://technet.microsoft.com/security/bulletin/ms10-102) | Hyper-V VMBus 資訊安全風險                                   | [CVE-2010-3960](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3960) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – 不太可能撰寫出可利用此漏洞的程式碼 | 這只是拒絕服務資訊安全風險                         |
  
受影響的軟體及下載位置  
----------------------
  
<span></span>
下表依據主要的軟體類別和嚴重性依序列出公告。
  
**我該如何使用這些表格？**
  
請用這些表格來瞭解可能需要安裝的資訊安全更新有哪些。 您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的資訊安全更新。 若軟體程式或更新出現在清單中，則相關可用軟體更新也會以超連結方式提供，也會列出軟體更新的嚴重性等級。
  
**注意：**一項資訊安全風險可能需要安裝數個資訊安全更新才能妥善解決。 請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
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
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-090**](http://technet.microsoft.com/security/bulletin/ms10-090)
</td>
<td style="border:1px solid black;">
[**MS10-091**](http://technet.microsoft.com/security/bulletin/ms10-091)
</td>
<td style="border:1px solid black;">
[**MS10-092**](http://technet.microsoft.com/security/bulletin/ms10-092)
</td>
<td style="border:1px solid black;">
[**MS10-093**](http://technet.microsoft.com/security/bulletin/ms10-093)
</td>
<td style="border:1px solid black;">
[**MS10-094**](http://technet.microsoft.com/security/bulletin/ms10-094)
</td>
<td style="border:1px solid black;">
[**MS10-095**](http://technet.microsoft.com/security/bulletin/ms10-095)
</td>
<td style="border:1px solid black;">
[**MS10-096**](http://technet.microsoft.com/security/bulletin/ms10-096)
</td>
<td style="border:1px solid black;">
[**MS10-097**](http://technet.microsoft.com/security/bulletin/ms10-097)
</td>
<td style="border:1px solid black;">
[**MS10-098**](http://technet.microsoft.com/security/bulletin/ms10-098)
</td>
<td style="border:1px solid black;">
[**MS10-099**](http://technet.microsoft.com/security/bulletin/ms10-099)
</td>
<td style="border:1px solid black;">
[**MS10-100**](http://technet.microsoft.com/security/bulletin/ms10-100)
</td>
<td style="border:1px solid black;">
[**MS10-101**](http://technet.microsoft.com/security/bulletin/ms10-101)
</td>
<td style="border:1px solid black;">
[**MS10-102**](http://technet.microsoft.com/security/bulletin/ms10-102)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
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
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=6031d98a-cd0f-4dd8-80b6-70a7167e9e55)  
(重大)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=922a0835-7f69-4e37-a9f7-c64e976e3513)  
(重大)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=a55b8029-9499-4219-99b7-65c30b0b864a)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=cdef3358-ad3e-40a6-9ba5-3be220a56a65)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=ef0ada2c-965f-438f-a1d3-bd45db8460c1)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=46baa431-126c-4fa5-9a7b-525008e2817d)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=fa9a1aac-b9c5-4d4e-9083-a080ad4ccc6f)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=bb9d1657-5beb-4372-b74c-a612a6fff5a8)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=4d0ae558-a4f2-4048-b5fd-ba072ca35e48)  
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=5d3a5678-77f8-4ebc-8775-aedd25ef0eb8)  
(重大)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a7c826b0-4aac-41ce-b297-6b6e11105c14)  
(重大)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d5207bf5-7e58-4001-aa8f-f9a4b2c037d8)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=070fef8e-ba09-40f4-abaa-9cebf08983c3)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=dc777e61-e1e3-43bf-a84d-22c4a69c135d)  
(重要)  
[Windows Media Encoder 9 x64](http://www.microsoft.com/downloads/details.aspx?familyid=550957c2-ce66-439f-95ea-681237513f75)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b9ce9d62-2eaa-48d8-bb6d-ea137e63d077)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6dabc306-c858-46b1-815c-cd8d011ff62e)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1f277ae4-4f85-4c8a-bfc5-dcdc8afed133)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=238bb885-eae6-464a-bb3d-679025f1cb50)  
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
[**MS10-090**](http://technet.microsoft.com/security/bulletin/ms10-090)
</td>
<td style="border:1px solid black;">
[**MS10-091**](http://technet.microsoft.com/security/bulletin/ms10-091)
</td>
<td style="border:1px solid black;">
[**MS10-092**](http://technet.microsoft.com/security/bulletin/ms10-092)
</td>
<td style="border:1px solid black;">
[**MS10-093**](http://technet.microsoft.com/security/bulletin/ms10-093)
</td>
<td style="border:1px solid black;">
[**MS10-094**](http://technet.microsoft.com/security/bulletin/ms10-094)
</td>
<td style="border:1px solid black;">
[**MS10-095**](http://technet.microsoft.com/security/bulletin/ms10-095)
</td>
<td style="border:1px solid black;">
[**MS10-096**](http://technet.microsoft.com/security/bulletin/ms10-096)
</td>
<td style="border:1px solid black;">
[**MS10-097**](http://technet.microsoft.com/security/bulletin/ms10-097)
</td>
<td style="border:1px solid black;">
[**MS10-098**](http://technet.microsoft.com/security/bulletin/ms10-098)
</td>
<td style="border:1px solid black;">
[**MS10-099**](http://technet.microsoft.com/security/bulletin/ms10-099)
</td>
<td style="border:1px solid black;">
[**MS10-100**](http://technet.microsoft.com/security/bulletin/ms10-100)
</td>
<td style="border:1px solid black;">
[**MS10-101**](http://technet.microsoft.com/security/bulletin/ms10-101)
</td>
<td style="border:1px solid black;">
[**MS10-102**](http://technet.microsoft.com/security/bulletin/ms10-102)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=4f1f41fb-368a-42e6-8d17-fca83b64f57b)  
(重大)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a3b57d26-5551-4785-86cf-41b532d78979)  
(重大)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=4f5a3677-0990-4702-bf08-af64cf12cb6c)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9b70334c-490d-446c-988a-a88a75595fd4)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=ef0ada2c-965f-438f-a1d3-bd45db8460c1)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e0b2837c-019b-419b-954d-5bdc71a3a332)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8fa2cfa4-a01d-4910-b69f-736aeb585bab)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4aa39f59-2177-459f-9b8a-9543330d48ec)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c87af292-a068-4089-aab8-115c18b4b024)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ad843b97-2f6e-4406-a17a-627b7db8a926)  
(重要)
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=6a9f56a0-230a-4dde-94da-f051ebf51f47)  
(重大)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=8b0d2a3a-7fed-4d48-9ec5-8558000e51bb)  
(重大)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=1e134e5d-84fb-432b-99b1-593b1be5d5a4)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=08328e82-b012-4ea5-bf89-becb4881084f)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=dc777e61-e1e3-43bf-a84d-22c4a69c135d)  
(重要)  
[Windows Media Encoder 9 x64](http://www.microsoft.com/downloads/details.aspx?familyid=550957c2-ce66-439f-95ea-681237513f75)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4c5cb600-9a39-40a0-be42-1593b1e0b97d)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=17b0b340-73b2-42a7-9d86-1297c63dcc2b)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bca61d61-d5cf-49a4-ab99-b61e50e8f619)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e17b8878-d065-49cc-bdba-0f24cdf35ea3)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0b0a06e7-0ae5-41f4-9ff5-d524fc0afbfa)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=7c1cf126-604c-4f70-bbe8-aa4d145eb68f)  
(重大)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=96884bfa-00c8-4263-9936-d7c054919dd3)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=15588d6a-f576-4e3d-95e8-d422af8a94de)  
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
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=9abc8270-f3ac-474d-9ebc-410aaa6262cc)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=04a178cc-1afd-4e47-8cab-05e402e5a568)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=4fce129d-2b4e-4a66-af27-bbbde1e65ba1)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=ad896d80-167f-4e8f-a448-cac93516f4d0)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=7c0c2850-e81d-4347-aeb3-47036caa7c1b)  
(重要)
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
[**MS10-090**](http://technet.microsoft.com/security/bulletin/ms10-090)
</td>
<td style="border:1px solid black;">
[**MS10-091**](http://technet.microsoft.com/security/bulletin/ms10-091)
</td>
<td style="border:1px solid black;">
[**MS10-092**](http://technet.microsoft.com/security/bulletin/ms10-092)
</td>
<td style="border:1px solid black;">
[**MS10-093**](http://technet.microsoft.com/security/bulletin/ms10-093)
</td>
<td style="border:1px solid black;">
[**MS10-094**](http://technet.microsoft.com/security/bulletin/ms10-094)
</td>
<td style="border:1px solid black;">
[**MS10-095**](http://technet.microsoft.com/security/bulletin/ms10-095)
</td>
<td style="border:1px solid black;">
[**MS10-096**](http://technet.microsoft.com/security/bulletin/ms10-096)
</td>
<td style="border:1px solid black;">
[**MS10-097**](http://technet.microsoft.com/security/bulletin/ms10-097)
</td>
<td style="border:1px solid black;">
[**MS10-098**](http://technet.microsoft.com/security/bulletin/ms10-098)
</td>
<td style="border:1px solid black;">
[**MS10-099**](http://technet.microsoft.com/security/bulletin/ms10-099)
</td>
<td style="border:1px solid black;">
[**MS10-100**](http://technet.microsoft.com/security/bulletin/ms10-100)
</td>
<td style="border:1px solid black;">
[**MS10-101**](http://technet.microsoft.com/security/bulletin/ms10-101)
</td>
<td style="border:1px solid black;">
[**MS10-102**](http://technet.microsoft.com/security/bulletin/ms10-102)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
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
Windows Vista Service Pack 1 和 Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=897351de-9697-4954-aa7e-169e980b932c)  
(重大)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=bebf0df0-5ebe-44b4-9ace-b3085a993e58)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2ddb8a06-c9cc-4d33-b6d1-22dbda2d871f)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=48f10251-34d8-4149-b4b2-bf3ec28f5846)  
(重要)
</td>
<td style="border:1px solid black;">
[Movie Maker 2.6](http://www.microsoft.com/downloads/details.aspx?familyid=55141a02-3ad3-4691-98b9-80dd8ecb14c5)<sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=e8a57950-43cd-486f-bd97-70b0ad360a0b)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a1c7f1b5-e054-4cd6-857d-2ab0a2fe9f62)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b824d3b9-2ce1-4abc-ae06-68aef1250be9)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=85265a23-5094-4007-8d33-f402cabd1664)  
(重要)
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
Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=171c02f9-f7d2-42f2-ba31-4c819a43784a)  
(重大)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=837b6056-af04-4aed-8afe-cc392770a590)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9a245f3c-ffb6-4ccd-956c-e7d1231fca30)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=099ccc5f-b92f-4d06-bcb5-92e35c49f613)  
(重要)
</td>
<td style="border:1px solid black;">
[Movie Maker 2.6](http://www.microsoft.com/downloads/details.aspx?familyid=5b078136-a492-4a2e-939d-82799f774d82)<sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=f98c3b96-acb5-49f1-be42-3dd44d316408)  
(重要)  
[Windows Media Encoder 9 x64](http://www.microsoft.com/downloads/details.aspx?familyid=e1054088-f484-4f44-ba0e-5cbd21773c0c)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=73624b68-a69d-4517-b971-f0b7d2ccc9d6)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f4c42cfe-b7f2-4436-919e-4bd305a3439a)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=63c7257a-16bf-4108-80b9-9dfe53528348)  
(重要)
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
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-090**](http://technet.microsoft.com/security/bulletin/ms10-090)
</td>
<td style="border:1px solid black;">
[**MS10-091**](http://technet.microsoft.com/security/bulletin/ms10-091)
</td>
<td style="border:1px solid black;">
[**MS10-092**](http://technet.microsoft.com/security/bulletin/ms10-092)
</td>
<td style="border:1px solid black;">
[**MS10-093**](http://technet.microsoft.com/security/bulletin/ms10-093)
</td>
<td style="border:1px solid black;">
[**MS10-094**](http://technet.microsoft.com/security/bulletin/ms10-094)
</td>
<td style="border:1px solid black;">
[**MS10-095**](http://technet.microsoft.com/security/bulletin/ms10-095)
</td>
<td style="border:1px solid black;">
[**MS10-096**](http://technet.microsoft.com/security/bulletin/ms10-096)
</td>
<td style="border:1px solid black;">
[**MS10-097**](http://technet.microsoft.com/security/bulletin/ms10-097)
</td>
<td style="border:1px solid black;">
[**MS10-098**](http://technet.microsoft.com/security/bulletin/ms10-098)
</td>
<td style="border:1px solid black;">
[**MS10-099**](http://technet.microsoft.com/security/bulletin/ms10-099)
</td>
<td style="border:1px solid black;">
[**MS10-100**](http://technet.microsoft.com/security/bulletin/ms10-100)
</td>
<td style="border:1px solid black;">
[**MS10-101**](http://technet.microsoft.com/security/bulletin/ms10-101)
</td>
<td style="border:1px solid black;">
[**MS10-102**](http://technet.microsoft.com/security/bulletin/ms10-102)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
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
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=f3785f3b-64c6-46a4-8e3a-9b9448124a8f)\*\*  
(重大)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=98183a76-5642-4e19-b488-029eb7ed3942)\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=87149ec2-74a8-4dea-b7e3-873558e0103e)\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bdc9564a-4091-4cde-963a-239513db6c17)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=a4ea028f-edfc-4237-8325-7ece11fcf437)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=118f528f-bd05-49c2-a4a4-78314cd00992)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6e2f572a-4169-47f2-a872-5466997122ed)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=14e079a8-01a4-47c9-bd47-f5c9a6ca070a)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6793f75b-cdf4-42ef-a53e-a1acb5b662d1)\*  
(重要)
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
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4b81aae5-6034-4c83-b5d2-e7e472435284)\*\*  
(重大)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d47b457d-e995-4a7e-9bfa-eebab9b3a729)\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=523a47d3-771d-471a-889b-16311c276a00)\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=dff39bfe-0799-4912-ae22-392562178ae6)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=f468d2b5-f02c-4691-9fb5-a7f69752f126)\*\*  
(重要)  
[Windows Media Encoder 9 x64](http://www.microsoft.com/downloads/details.aspx?familyid=533d91d8-0291-421e-9701-3bd86d18bc45)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=77e288fb-b51f-4f57-baac-1443d8fbd37b)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=09a4b646-989d-43ef-a3e8-64af8b380a14)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6baf92b7-a336-45f2-a1ba-c00c34dfb76f)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=85add876-ca5a-4a92-984e-188a72e349fc)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b8c06bbc-6e84-4cf1-89f0-c0d34cfffaed)\*  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=8ddafaaf-84a0-4325-b06f-4aac7cd61274)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=959146ee-0e70-4e56-9012-72ed59aeb24b)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=cf341a35-32ea-4ff7-aca9-1a4683c100ee)  
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
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=82f71194-6f1f-4f43-8752-4bf5e5f94a93)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=46522323-837e-4a74-9cf0-45f69343e776)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7a4b23d4-f68e-4d5b-8814-d9247145f164)  
(重要)
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
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-090**](http://technet.microsoft.com/security/bulletin/ms10-090)
</td>
<td style="border:1px solid black;">
[**MS10-091**](http://technet.microsoft.com/security/bulletin/ms10-091)
</td>
<td style="border:1px solid black;">
[**MS10-092**](http://technet.microsoft.com/security/bulletin/ms10-092)
</td>
<td style="border:1px solid black;">
[**MS10-093**](http://technet.microsoft.com/security/bulletin/ms10-093)
</td>
<td style="border:1px solid black;">
[**MS10-094**](http://technet.microsoft.com/security/bulletin/ms10-094)
</td>
<td style="border:1px solid black;">
[**MS10-095**](http://technet.microsoft.com/security/bulletin/ms10-095)
</td>
<td style="border:1px solid black;">
[**MS10-096**](http://technet.microsoft.com/security/bulletin/ms10-096)
</td>
<td style="border:1px solid black;">
[**MS10-097**](http://technet.microsoft.com/security/bulletin/ms10-097)
</td>
<td style="border:1px solid black;">
[**MS10-098**](http://technet.microsoft.com/security/bulletin/ms10-098)
</td>
<td style="border:1px solid black;">
[**MS10-099**](http://technet.microsoft.com/security/bulletin/ms10-099)
</td>
<td style="border:1px solid black;">
[**MS10-100**](http://technet.microsoft.com/security/bulletin/ms10-100)
</td>
<td style="border:1px solid black;">
[**MS10-101**](http://technet.microsoft.com/security/bulletin/ms10-101)
</td>
<td style="border:1px solid black;">
[**MS10-102**](http://technet.microsoft.com/security/bulletin/ms10-102)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
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
適用於 32 位元系統的 Windows 7
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c288fe87-b113-4615-9b02-5e388bcb5241)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=ff590db8-4264-42ba-9e07-88d100e1c4f5)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=cf85cdb6-58c7-4144-82f6-f01a6a4f9c3a)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=75591d37-2cb8-4cdf-acbb-89cd0d1a9290)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=4e8ad5cd-af27-4f00-9378-ad778b8ee7b3)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=aa7de2e4-ba48-4d58-b034-05349f0eb920)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=f7c7d57a-d031-46a3-9613-eae2b9cb6401)  
(重要)
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
適用於 x64 型系統的 Windows 7
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=2cf4ac70-88b4-4840-9895-2bcf119312a7)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=4ea4e339-9db2-4b99-b567-80ee55ecdf92)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=0597018d-39f5-4ca9-b437-63d9e68f264d)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=3a0c4dd0-98b4-4e7a-99ed-22b9d9f76cd1)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=35a3e821-b463-411c-858b-d01eb5aed42b)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=b21db627-91c2-4ebf-b7c0-38ac58ae5b6c)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=e52c36f5-637b-4928-83d0-27514c6cc384)  
(重要)
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
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-090**](http://technet.microsoft.com/security/bulletin/ms10-090)
</td>
<td style="border:1px solid black;">
[**MS10-091**](http://technet.microsoft.com/security/bulletin/ms10-091)
</td>
<td style="border:1px solid black;">
[**MS10-092**](http://technet.microsoft.com/security/bulletin/ms10-092)
</td>
<td style="border:1px solid black;">
[**MS10-093**](http://technet.microsoft.com/security/bulletin/ms10-093)
</td>
<td style="border:1px solid black;">
[**MS10-094**](http://technet.microsoft.com/security/bulletin/ms10-094)
</td>
<td style="border:1px solid black;">
[**MS10-095**](http://technet.microsoft.com/security/bulletin/ms10-095)
</td>
<td style="border:1px solid black;">
[**MS10-096**](http://technet.microsoft.com/security/bulletin/ms10-096)
</td>
<td style="border:1px solid black;">
[**MS10-097**](http://technet.microsoft.com/security/bulletin/ms10-097)
</td>
<td style="border:1px solid black;">
[**MS10-098**](http://technet.microsoft.com/security/bulletin/ms10-098)
</td>
<td style="border:1px solid black;">
[**MS10-099**](http://technet.microsoft.com/security/bulletin/ms10-099)
</td>
<td style="border:1px solid black;">
[**MS10-100**](http://technet.microsoft.com/security/bulletin/ms10-100)
</td>
<td style="border:1px solid black;">
[**MS10-101**](http://technet.microsoft.com/security/bulletin/ms10-101)
</td>
<td style="border:1px solid black;">
[**MS10-102**](http://technet.microsoft.com/security/bulletin/ms10-102)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=99a91ba7-035b-4717-ada5-c1ad6645db64)\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=e52f7869-474a-44c8-a102-e766c576fc01)\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=28c832fb-4937-4652-8799-eab6c76d05fb)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=f58a765f-cea9-456d-b0ab-bfc70b109cbf)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=9e2c95f6-9381-4484-b11b-814ab9138118)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=d417ebce-7841-4bbb-8abc-b15ef5f4b733)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=b823a7aa-0eb9-42dd-bf56-8907d94b314a)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=d7307afd-84a0-434e-9658-bf9f8ae4b938)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=39b7abc7-65a4-4dfd-92ba-c638e3de1118)\*  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c26de145-94b8-404a-b946-744988fab83b)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=a21d061a-794a-4012-b3cd-c67445c074f5)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=3ad64d5c-2d81-4ac8-934e-8917b2fcf961)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=13a9f838-ac07-43dc-9aee-a77207998e1e)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=cb4211f3-1082-4245-8f03-7cbac90e9a31)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=7eeac1bb-9f86-4ea5-b30f-980d52be5044)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=66b2506d-80e0-4e32-86e6-0908ef56ae90)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
</table>
 
**Windows Server 2008 和 Windows Server 2008 R2 注意事項**

**\*Server Core 安裝會受影響。** 無論上述受支援的 Windows Server 2008 或 Windows Server 2008 R2 版本是否使用 Server Core 安裝選項安裝，這個更新均以相同的嚴重性等級套用。 如需此安裝選項的詳細資訊，請參閱 TechNet 文章：[管理 Server Core 安裝](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[維護 Server Core 安裝](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 和 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**\*\*Server Core 安裝不受影響。** 如果 Windows Server 2008 或 Windows Server 2008 R2 是使用 Server Core 安裝選項所安裝，則這項更新解決的資訊安全風險並不會影響受支援的 Windows Server 2008 或 Windows Server 2008 R2。 如需此安裝選項的詳細資訊，請參閱 TechNet 文章：[管理 Server Core 安裝](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[維護 Server Core 安裝](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 和 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**MS10-093 注意事項**

<sup>[1]</sup> Windows Movie Maker 2.6 是選用的下載，可安裝於所述的作業系統。

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
Microsoft Office 套件和元件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-103**](http://technet.microsoft.com/security/bulletin/ms10-103)
</td>
<td style="border:1px solid black;">
[**MS10-105**](http://technet.microsoft.com/security/bulletin/ms10-105)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=f540692c-e404-4383-8937-4d6a36475da5)  
(KB2284692)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=724d0ad6-ba5f-4dbf-b280-3fb36335d33b)  
(KB2289162)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e600de65-3e9d-4e37-8906-8b7091ff523e)  
(KB2284695)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=976857e9-77fc-4667-88ca-7637e57536cd)  
(KB2289163)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=79275011-bdc1-446a-8ea6-56fc31bd9c35)  
(KB2284697)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=676eeed6-f2b7-4265-afc7-a82ffdbeb290)  
(KB2288931)  
(無嚴重性等級<sup>[1]</sup>)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 (32 位元版本)
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2010 (32 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=99e18990-75e9-497e-9b4f-5d7ef8656ab2)  
(KB2409055)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 (32 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=6d644494-b530-4b37-bc37-8a8a7edefe53)  
(KB2289078)  
(無嚴重性等級<sup>[1]</sup>)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 (64 位元版本)
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2010 (64 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=9b27ee11-e563-4152-9691-25eec1ee9966)  
(KB2409055)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 (64 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=58e54779-aa8f-41b3-9993-8cec12c49082)  
(KB2289078)  
(無嚴重性等級<sup>[1]</sup>)
</td>
</tr>
<tr>
<th colspan="3">
其他 Office 軟體
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-103**](http://technet.microsoft.com/security/bulletin/ms10-103)
</td>
<td style="border:1px solid black;">
[**MS10-105**](http://technet.microsoft.com/security/bulletin/ms10-105)
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
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Converter Pack
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Office Converter Pack](http://www.microsoft.com/downloads/details.aspx?familyid=dcded2ee-0673-4afe-abe6-04941a2ad306)  
(KB2456849)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works 9
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Works 9](http://www.microsoft.com/downloads/details.aspx?familyid=10f6f330-05d8-4b60-9ebb-822a7321ac0f)  
(KB2431831)  
(重要)
</td>
</tr>
</table>
 
**MS10-105 注意事項**

<sup>[1]</sup>嚴重性等級不適用此更新，因為此公告討論的資訊安全風險不會影響此軟體。 但是，做為在未來保護所識別之任何新模式的深度防禦措施，Microsoft 建議此軟體的客戶套用此資訊安全更新。

#### Microsoft 伺服器軟體

 
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
Microsoft SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-104**](http://technet.microsoft.com/security/bulletin/ms10-104)
</td>
<td style="border:1px solid black;">
[**MS10-106**](http://technet.microsoft.com/security/bulletin/ms10-106)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 2 (32 位元版本)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 2 (32 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=3c8fb9f9-7920-43ea-b618-e26dc3360c60)  
(KB2433089)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 2 (64 位元版本)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 2 (64 位元版本)](http://www.microsoft.com/downloads/details.aspx?familyid=3db09280-24bd-42e0-9ae3-02c9bf3e8ee3)  
(KB2433089)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Exchange Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-104**](http://technet.microsoft.com/security/bulletin/ms10-104)
</td>
<td style="border:1px solid black;">
[**MS10-106**](http://technet.microsoft.com/security/bulletin/ms10-106)
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
[**中度**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Microsoft Exchange Server 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Microsoft Exchange Server 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7b983156-9e9f-4d29-9e9b-2369747e3b62)  
(KB2407132)  
(中度)
</td>
</tr>
</table>
 

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和資訊安全更新。 如需更多資訊，請參閱 [TechNet 更新管理中心](http://technet.microsoft.com/zh-tw/updatemanagement/default.aspx) (英文)。 [TechNet Security Center](http://technet.microsoft.com/zh-tw/security/default.aspx) 提供 Microsoft 產品安全性的其他資訊。 消費者可以造訪[在家上網的安全性](http://www.microsoft.com/taiwan/protect/default.mspx)網站，只要按一下 \[最新資訊安全更新\] 即可在此網站取得此資訊。

資訊安全更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 以及 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) 取得。 資訊安全更新也可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得。 您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。

對於 Microsoft Office for Mac 的客戶，Microsoft AutoUpdate for Mac 可協助您保持最新的 Microsoft 軟體。 如需使用 Microsoft AutoUpdate for Mac 的詳細資訊，請參閱[自動檢查軟體更新](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea) (英文)。

最後，您可以從 [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) 下載資訊安全更新。 Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括資訊安全更新、驅動程式和 Service Pack。 只要以資訊安全公告編號 (例如：MS07-036) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。 如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](http://go.microsoft.com/fwlink/?linkid=97900)。

**偵測與部署指南**

Microsoft 針對資訊安全更新提供偵測和部署指南。 本指南所含之建議和資訊，能幫助 IT 專業人員瞭解如何使用用於資訊安全更新的偵測和部署的各種工具。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 961747](http://support.microsoft.com/kb/961747/zh-tw)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少資訊安全更新以及一般安全性設定錯誤的狀況。 如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) 網站 (英文)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速而可靠地將 Microsoft Windows 2000 作業系統及更新版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 適用的最新重大更新與資訊安全更新部署到 Microsoft Windows 2000 及更新版本的作業系統中。

如需更多關於利用 Windows Server Update Services 部署資訊安全更新的資訊，請造訪 [Windows Server Update Services](http://www.microsoft.com/taiwan/windowsserversystem/updateservices/evaluation/overview.mspx) 網站。

**SystemCenter Configuration Manager 2007**

Configuration Manager 2007 軟體更新管理可簡化遞送和管理企業中 IT 系統更新的繁複作業。 IT 系統管理員可以使用 Configuration Manager 2007 遞送 Microsoft 產品更新給各種裝置，包括桌上型電腦、筆記型電腦、伺服器及行動裝置。

Configuration Manager 2007 中的自動資訊安全風險評估會找出更新需求並報告建議動作。 Configuration Manager 2007 中的軟體更新管理是建置在 Microsoft Windows Software Update Services (WSUS) 上，經過時間考驗，為全球 IT 系統管理員所熟悉的更新基礎架構。 如需更多有關系統管理員如何使用 Configuration Manager 2007 來部署更新的資訊，請參閱[軟體更新管理](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx) (英文)。 如需更多有關 Configuration Manager 的資訊，請造訪 [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx)。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要資訊安全更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。

**注意：**System Management Server 2003 自 2010 年 1 月 12 日起不受主流支援。如需更多有關產品生命週期的資訊，請造訪 。現已推出新版的 SMS：System Center Configuration Manager 2007；請參閱前段的＜SystemCenter Configuration Manager 2007＞一節。

如需更多有關系統管理員如何使用 SMS 2003 來部署資訊安全更新的資訊，請參閱 [Microsoft Systems Management Server 2003 的案例與程序： 軟體發佈和補充程式管理](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en) (英文)。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx)。

**注意：**SMS 使用 Microsoft Baseline Security Analyzer 提供廣泛的資訊安全公告更新偵測與部署支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](http://technet.microsoft.com/zh-tw/library/cc917507(en-us).aspx)。 某些資訊安全更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可使用 Elevated Rights Deployment Tool (隨 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en) (英文) 提供) 來安裝這些更新。

**Update Compatibility Evaluator 和 Application Compatibility Toolkit**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。 這可能會觸發不相容性，而拉長部署資訊安全更新的時間。 您可以使用 [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 隨附的 [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 元件，針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Microsoft Windows Vista、Windows Update、Microsoft 資訊安全更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非安全性、高優先順序更新

如需在 Windows Update 和 Microsoft Update 上發行的非資訊安全更新之相關資訊，請參閱：

-   [icrosoft 知識庫文件編號 894199](http://support.microsoft.com/kb/894199/zh-tw)： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。 其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](http://technet.microsoft.com/en-us/wsus/bb456965.aspx)。 顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的安全性保護，Microsoft 將在每月發行資訊安全更新之前，提前向重要資訊安全軟體提供者提供資訊安全風險資訊。 資訊安全軟體提供者可利用此資訊安全風險資訊，透過其資訊安全軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。 如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://www.microsoft.com/security/msrc/mapp/partners.mspx)上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 安全性策略與社群

**更新程式管理策略**

[更新程式管理安全性指南](http://technet.microsoft.com/zh-tw/library/bb466251(en-us).aspx)提供您有關套用資訊安全更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他資訊安全更新**

其他安全性問題的更新可由下列位置取得：

-   資訊安全更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。
-   客戶平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的資訊安全更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](http://support.microsoft.com/kb/913086/zh-tw)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](http://technet.microsoft.com/zh-tw/security/cc136632.aspx)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](http://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 [VeriSign iDefense Labs](http://labs.idefense.com/) 的 Aniway 回報 MS10-090 中描述的一項問題
-   感謝 [VUPEN Vulnerability Research Team](http://www.vupen.com/) 的 Nicolas Joly 回報 MS10-090 中描述的一項問題
-   感謝 Stephen Fewer 與 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 MS10-090 中描述的一項問題
-   感謝 [Peter Vreugdenhil](http://vreugdenhilresearch.nl/) 與 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 MS10-090 中描述的一項問題
-   感謝 [Yosuke Hasegawa](http://utf-8.jp/) 協助我們解決 MS10-090 中描述的一項問題
-   感謝 [VeriSign iDefense Labs](http://labs.idefense.com/) 的 Jose Antonio Vazquez Gonzalez 回報 MS10-090 中描述的一項問題
-   感謝 [Red Hat Security Response Team](https://www.redhat.com/security/team/) 的 Marc Schoenefeld，與 [Opera Security Team](http://www.opera.com/security/) 攜手合作，回報 MS10-091 中描述的一項問題
-   感謝 [Red Hat Security Response Team](https://www.redhat.com/security/team/) 的 Marc Schoenefeld 回報 MS10-091 中描述的一項問題
-   感謝Paul-Kenji Cahier Furuya 回報 MS10-091 中描述的一項問題
-   感謝 [Kaspersky Lab](http://usa.kaspersky.com/) 的 Sergey Golovanov、Alexander Gostev、Maxim Golovkin 和 Alexey Monastyrsky，以及 [Design and Test Lab](http://www.dnt-lab.com/) 的 Vitaly Kiktenko 和 Alexander Saprykin 回報 MS10-092 中描述的一項問題
-   感謝 [Symantec](http://www.symantec.com/index.jsp) 的 Liam O Murchu 回報 MS10-092 中描述的一項問題
-   感謝 [ESET](http://www.eset.com/) 的 Alexandr Matrosov、Eugene Rodionov、Juraj Malcho 和 David Harley MS10-092 中描述的一項問題
-   感謝 [Fortinet FortiGuard Labs](http://www.fortiguard.com/) 的 Haifei Li 回報 MS10-095 中描述的一項問題
-   感謝 [ACROS Security](http://www.acrossecurity.com/) 的 Simon Raner 回報 MS10-096 中描述的一項問題
-   感謝 [Rapid7](http://www.rapid7.com/) 的 HD Moore 回報 MS10-096 中描述的一項問題
-   感謝 [NGS Software](http://www.ngssoftware.com/) 的 Muhaimin Dzulfakar 回報 MS10-096 中描述的一項問題
-   感謝 [NGS Software](http://www.ngssoftware.com/) 的 Muhaimin Dzulfakar 回報 MS10-097 中描述的一項問題
-   感謝 [Norman](http://www.norman.com/) 的 Tarjei Mandt 回報 MS10-098 中描述的四項問題
-   感謝 [Sysdream](http://www.sysdream.com/) 的 Stefan Le Berre 回報 MS10-098 中描述的一項問題
-   感謝 [Fortinet FortiGuard Labs](http://www.fortiguard.com/) 的 Honggang Ren 回報 MS10-099 中描述的一項問題
-   感謝 [Argeniss](http://www.argeniss.com/) 的 Cesar Cerrudo 回報 MS10-100 中描述的一項問題
-   感謝The Samba Team 的 Matthias Dieter Wallnofer 和 Andrew Bartlett 回報 MS10-101 中描述的一項問題
-   感謝 [HP](http://www.hp.com/) 和 [techit](http://www.techit.de/) 回報 MS10-102 中描述的一項問題
-   感謝 [VUPEN Vulnerability Research Team](http://www.vupen.com/) 的 Chaouki Bekrar 回報 MS10-103 中描述的五項問題
-   感謝 Oleksandr Mirosh 與 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 MS10-104 中描述的一項問題
-   感謝 [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Yamata Li 回報 MS10-105 中描述的兩項問題
-   感謝 [Secunia Research](http://secunia.com/) 的 Alin Rad Pop 回報 MS10-105 中描述的一項問題
-   感謝 [Secunia Research](http://secunia.com/) 的 Carsten Eiram 回報 MS10-105 中描述的三項問題
-   感謝 [Secunia Research](http://secunia.com/) 的 Dyon Balding 回報 MS10-105 中描述的兩項問題
-   感謝 Oleksandr Mirosh 與 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 MS10-106 中描述的一項問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可洽詢[資訊安全支援](http://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 以取得技術支援。 與資訊安全更新有關的支援電話不另外收費。 如需更多可用支援選項的資訊，請參閱 [Microsoft 技術支援服務](http://support.microsoft.com/?ln=zh-tw)。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與資訊安全更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](http://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2010 年 12 月 14 日)： 公告摘要發行。

*Built at 2014-04-18T01:50:00Z-07:00*
