---
TOCTitle: 'MS10-AUG'
Title: 2010 年 8 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms10-aug'
ms:contentKeyID: 61237702
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms10-aug(v=Security.10)'
---

Security Bulletin Summary

2010 年 8 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2010年8月2日 | 更新: 2010年8月23日

**版本:** 2.0

此公告摘要列出 2010 年 8 月份發行之資訊安全公告。

發行 2010 年 8 月份公告之後，此公告摘要將取代原先於 2009 年 8 月 5 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 資訊安全公告預先通知](http://technet.microsoft.com/security/bulletin/advance) (英文)。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2010 年 8 月 23 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。 立即註冊參加 [8 月份資訊安全公告網路廣播](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032454431&eventcategory=4&culture=en-us&countrycode=us)。 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 資訊安全公告摘要和網路廣播](http://technet.microsoft.com/security/bulletin/summary)。

對於此不定期資訊安全公告 [MS10-046](http://technet.microsoft.com/security/bulletin/ms10-046) (原先在此公告摘要第 1.0 版中宣布)，Microsoft 在 2010 年 7 月 30 日發佈一個對應的公告預先通知，並在 2010 年 8 月 2 日舉辦公告網路廣播。您可申請參加此 [2010 年 8 月 2 日網路廣播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032456779&culture=zh-tw)。 如需更多資訊，請參閱 [Microsoft 資訊安全公告摘要和網路廣播](http://technet.microsoft.com/security/bulletin/summary)。

Microsoft 也會提供資訊協助客戶排定每月資訊安全更新以及任何非安全性、高優先順序更新的優先順序，其中這些非安全性、高優先順序更新的發行日期與每月資訊安全更新的發行日期相同。 請參閱＜其他資訊＞一節。

### 公告資訊

提要
----

<span></span>
下表依嚴重性摘要說明本月份資訊安全公告。

如需受影響的軟體之詳細資料，請參閱下節＜受影響的軟體及下載位置＞。

 
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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-046">MS10-046</a></td>
<td style="border:1px solid black;"><strong>Windows Shell 中的弱點可能會允許遠端執行程式碼 (2286198)</strong><br />
<br />
此資訊安全更新可解決 Windows Shell 中一項公開揭露的弱點。 當蓄意製作的捷徑圖示顯示時，此弱點可能會允許遠端執行程式碼。 成功利用此弱點的攻擊者可以取得與本機使用者相同的使用者權限。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-049">MS10-049</a></td>
<td style="border:1px solid black;"><strong>SChannel 中的弱點可能會允許遠端執行程式碼 (980436)</strong><br />
<br />
此資訊安全更新解決了 Windows 中安全通道 (SChannel) 安全性封裝中一項公開揭露的弱點和一項未公開報告的弱點。 如果使用者造訪蓄意製作的網站，且其設計用於透過網際網路網頁瀏覽器來利用這些弱點，則最嚴重的弱點可能會允許遠端執行程式碼。 但是，攻擊者無法強迫使用者造訪網站， 而是引誘使用者自行前往。一般的做法是設法讓使用者按一下電子郵件訊息或 Instant Messenger 中通往攻擊者網站的連結。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-051">MS10-051</a></td>
<td style="border:1px solid black;"><strong>Microsoft XML Core Services 中的弱點可能會允許遠端執行程式碼 (2079403)</strong><br />
<br />
這個資訊安全更新可解決 Microsoft XML Core Services 中一項未公開報告的弱點。 如果使用者使用 Internet Explorer 檢視蓄意製作的網頁，此弱點可能會允許遠端執行程式碼。 攻擊者並不能強迫使用者造訪這些網站。 而是引誘使用者自行前往。一般的做法是設法讓使用者按一下電子郵件或 Instant Messenger 訊息中通往攻擊者網站的連結。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-052">MS10-052</a></td>
<td style="border:1px solid black;"><strong>Microsoft MPEG Layer-3 轉碼器中的弱點可能會允許遠端執行程式碼 (2115168)</strong><br />
<br />
此資訊安全更新能解決 Microsoft MPEG Layer-3 音訊轉碼器中一項未公開報告的弱點。 當使用者開啟蓄意製作的媒體檔案，或者從網站或任何提供 Web 內容的應用程式收到蓄意製作的串流內容時，這些弱點可能會允許遠端執行程式碼。 成功利用此弱點的攻擊者可以取得與本機使用者相同的使用者權限。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-053">MS10-053</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 積存資訊安全更新 (2183461)</strong><br />
<br />
此資訊安全更新可解決 Internet Explorer 中六項未公開報告的弱點。 最嚴重的弱點可能會在使用者以 Internet Explorer 檢視蓄意製作的網頁時，允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-054">MS10-054</a></td>
<td style="border:1px solid black;"><strong>SMB 伺服器中的弱點可能會允許遠端執行程式碼 (982214)</strong><br />
<br />
這個資訊安全更新可解決 Microsoft Windows 中數個未公開報告的弱點。 如果攻擊者蓄意製作 SMB 封包並將其傳送至受影響的系統，最嚴重的弱點可能會允許遠端執行程式碼。 最佳做法的防火牆和標準預設防火牆設定有助於防止網路受到來自企業外試圖利用這些弱點的攻擊。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-055">MS10-055</a></td>
<td style="border:1px solid black;"><strong>Cinepak Codec 中的弱點可能會允許遠端執行程式碼 (982665)</strong><br />
<br />
此資訊安全更新可解決 Cinepak Codec 中一項未公開報告的弱點。 當使用者開啟蓄意製作的媒體檔案，或者從網站或任何提供 Web 內容的應用程式收到蓄意製作的串流內容時，這些弱點可能會允許遠端執行程式碼。 成功利用此弱點的攻擊者可以取得與本機使用者相同的使用者權限。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-056">MS10-056</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Word 中的弱點可能會允許遠端執行程式碼 (2269638)</strong><br />
<br />
這個資訊安全更新可解決 Microsoft Office 中四項未公開報告的弱點。 最嚴重的弱點可能會在使用者開啟或預覽蓄意製作的 RTF 電子郵件時，允許遠端執行程式碼。 成功利用這類任一弱點的攻擊者可以取得與本機使用者相同的使用者權限。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-060">MS10-060</a></td>
<td style="border:1px solid black;"><strong>Microsoft .NET Common Language Runtime 和 Microsoft Silverlight 中的弱點可能會允許遠端執行程式碼 (2265906)</strong><br />
<br />
這個資訊安全更新可解決 Microsoft .NET Framework 和 Microsoft Silverlight 中兩項未公開報告的弱點。 如果使用者使用可執行 XAML 瀏覽器應用程式 (XBAP) 或 Silverlight 應用程式的網頁瀏覽器來檢視蓄意製作的網頁，或攻擊者成功誘使使用者執行隨意製作的 Microsoft .NET 應用程式，則這些弱點可能會允許在用戶端系統上遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 如果伺服器允許處理 ASP.NET 網頁，且攻擊者將蓄意製作的 ASP.NET 網頁成功上載到執行 IIS 的伺服器系統並執行，則這些弱點也可能會允許在該伺服器系統上遠端執行程式碼 (虛擬主機案例可能會發生這種情況)。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows、Microsoft .NET Framework、Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-047">MS10-047</a></td>
<td style="border:1px solid black;"><strong>Windows 核心中的弱點可能會允許權限提高 (981852)</strong><br />
<br />
這個資訊安全更新可解決 Microsoft Windows 中數個未公開報告的弱點。 如果攻擊者從本機登入並執行蓄意製作的應用程式，則最嚴重的弱點可能會允許權限提高。 攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這些弱點。 遠端或匿名使用者無法利用這個弱點。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-048">MS10-048</a></td>
<td style="border:1px solid black;"><strong>Windows 核心模式驅動程式中的弱點可能會允許權限提高 (2160329)</strong><br />
<br />
此資訊安全更新可解決 Windows 核心模式驅動程式中一項公開揭露的弱點和四項未公開報告的弱點。 如果攻擊者登入受影響的系統並執行蓄意製作的應用程式，則最嚴重的弱點可能會允許權限提高。 攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項弱點。 匿名或遠端使用者無法利用這個弱點。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-050">MS10-050</a></td>
<td style="border:1px solid black;"><strong>Windows Movie Maker 中的弱點可能會允許遠端執行程式碼 (981997)</strong><br />
<br />
這個資訊安全更新可解決 Windows Movie Maker 中一項未公開報告的弱點。 如果攻擊者傳送蓄意製作的 Movie Maker 專案檔案，並且引誘使用者開啟蓄意製作的檔案，則此弱點可允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-057">MS10-057</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Excel 中的弱點可能會允許遠端執行程式碼 (2269707)</strong> <br />
<br />
這個資訊安全更新可解決 Microsoft Office 中一項未公開報告的弱點。 如果使用者開啟蓄意製作的 Excel 檔案，此弱點可能會允許遠端執行程式碼。 成功利用此弱點的攻擊者可以取得與登入使用者相同的使用者權限。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-058">MS10-058</a></td>
<td style="border:1px solid black;"><strong>TCP/IP 中的弱點可能會允許提高權限 (978886)</strong><br />
<br />
這個資訊安全更新可解決 Microsoft Windows 中兩項未公開報告的弱點。 由於特定輸入緩衝區的處理有錯誤，這些弱點中較嚴重者可能會允許權限提高。 能登入目標系統的攻擊者即可利用此弱點，並以系統層級權限執行任意程式碼。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-059">MS10-059</a></td>
<td style="border:1px solid black;"><strong>服務的追蹤功能中的弱點可能會允許權限提高 (982799)</strong><br />
<br />
此資訊安全更新可解決服務的追蹤功能中一項公開揭露的弱點和一項未公開報告的弱點。 如果攻擊者執行蓄意製作的應用程式，弱點就可能允許權限提高。 攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項弱點。 匿名或遠端使用者無法利用這個弱點。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
弱點索引  
--------
  
<span></span>
下表提供本月所述每個弱點的利用性評估。 弱點根據遞減的弱點評估等級及 CVE 編號依序列出。 僅包含資訊安全公告中，嚴重性等級為「重大」或「重要」的弱點。
  
**我該如何使用這個表格？**
  
請用這個表格來瞭解您可能需要安裝的每個資訊安全更新，與 30 天內已發行的可利用程式碼受影響之可能性。 您應該檢閱下列的每個評估，按照特定的設定，將部署以優先次序排序。 如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](http://technet.microsoft.com/en-us/security/cc998259.aspx)。
  
| 公告編號                                                            | 弱點標題                                                               | CVE ID                                                                           | 弱點索引評估                                                                                            | 主要重點                                                                                                                    |  
|---------------------------------------------------------------------|------------------------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|  
| [MS10-060](http://technet.microsoft.com/security/bulletin/ms10-060) | Microsoft Silverlight 記憶體損毀弱點                                   | [CVE-2010-0019](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0019) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                        |  
| [MS10-052](http://technet.microsoft.com/security/bulletin/ms10-052) | MPEG Layer-3 音訊解碼器緩衝區溢位弱點                                  | [CVE-2010-1882](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1882) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                        |  
| [MS10-047](http://technet.microsoft.com/security/bulletin/ms10-047) | Windows 核心資料初始化弱點                                             | [CVE-2010-1888](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1888) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                        |  
| [MS10-058](http://technet.microsoft.com/security/bulletin/ms10-058) | Windows 網路中的整數溢位弱點                                           | [CVE-2010-1893](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1893) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                        |  
| [MS10-048](http://technet.microsoft.com/security/bulletin/ms10-048) | Win32k 例外處理弱點                                                    | [CVE-2010-1894](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1894) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | **已經公開發佈這項弱點。**                                                                                                  |  
| [MS10-048](http://technet.microsoft.com/security/bulletin/ms10-048) | Win32k 集區溢位弱點                                                    | [CVE-2010-1895](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1895) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                        |  
| [MS10-048](http://technet.microsoft.com/security/bulletin/ms10-048) | Win32k 使用者輸入驗證弱點                                              | [CVE-2010-1896](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1896) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                        |  
| [MS10-048](http://technet.microsoft.com/security/bulletin/ms10-048) | Win32k 視窗建立弱點                                                    | [CVE-2010-1897](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1897) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                        |  
| [MS10-060](http://technet.microsoft.com/security/bulletin/ms10-060) | Microsoft Silverlight 和 Microsoft .NET Framework CLR 虛擬方法委派弱點 | [CVE-2010-1898](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1898) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                        |  
| [MS10-056](http://technet.microsoft.com/security/bulletin/ms10-056) | Word 記錄剖析弱點                                                      | [CVE-2010-1900](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1900) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                        |  
| [MS10-056](http://technet.microsoft.com/security/bulletin/ms10-056) | Word RTF 剖析引擎記憶體損毀弱點                                        | [CVE-2010-1901](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1901) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                        |  
| [MS10-055](http://technet.microsoft.com/security/bulletin/ms10-055) | Cinepak Codec 解壓縮弱點                                               | [CVE-2010-2553](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2553) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                        |  
| [MS10-059](http://technet.microsoft.com/security/bulletin/ms10-059) | 追蹤記憶體損毀弱點                                                     | [CVE-2010-2555](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2555) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                        |  
| [MS10-053](http://technet.microsoft.com/security/bulletin/ms10-053) | 未初始化的記憶體損毀弱點                                               | [CVE-2010-2557](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2557) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | 由於缺少資料執行防止 (DEP) 作為風險減輕措施，所以在 Internet Explorer 6 上較有可能利用此弱點進行攻擊。                      |  
| [MS10-053](http://technet.microsoft.com/security/bulletin/ms10-053) | HTML 配置記憶體損毀弱點                                                | [CVE-2010-2560](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2560) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                        |  
| [MS10-057](http://technet.microsoft.com/security/bulletin/ms10-057) | Excel 記憶體損毀弱點                                                   | [CVE-2010-2562](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2562) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                        |  
| [MS10-050](http://technet.microsoft.com/security/bulletin/ms10-050) | Movie Maker 記憶體損毀弱點                                             | [CVE-2010-2564](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2564) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                                                                                                        |  
| [MS10-046](http://technet.microsoft.com/security/bulletin/ms10-046) | 捷徑圖示載入弱點                                                       | [CVE-2010-2568](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2568) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | **此弱點目前在網際網路生態系統中遭到利用。**                                                                                |  
| [MS10-047](http://technet.microsoft.com/security/bulletin/ms10-047) | Windows 核心重覆釋放相同記憶體空間弱點                                 | [CVE-2010-1889](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1889) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                        |  
| [MS10-056](http://technet.microsoft.com/security/bulletin/ms10-056) | Word RTF 剖析緩衝區溢位弱點                                            | [CVE-2010-1902](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1902) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | 由於具備額外的堆積記憶體這項風險減輕機制，因此較難利用 Windows Vista 和 Windows 7。                                         |  
| [MS10-056](http://technet.microsoft.com/security/bulletin/ms10-056) | Word HTML 連結的物件記憶體損毀弱點                                     | [CVE-2010-1903](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1903) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                        |  
| [MS10-054](http://technet.microsoft.com/security/bulletin/ms10-054) | SMB 集區溢位弱點                                                       | [CVE-2010-2550](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2550) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | 遭到利用時比較有可能導致拒絕服務，不太可能執行程式碼。                                                                      |  
| [MS10-053](http://technet.microsoft.com/security/bulletin/ms10-053) | 未初始化的記憶體損毀弱點                                               | [CVE-2010-2556](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2556) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                        |  
| [MS10-053](http://technet.microsoft.com/security/bulletin/ms10-053) | 競爭條件記憶體損毀弱點                                                 | [CVE-2010-2558](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2558) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                        |  
| [MS10-053](http://technet.microsoft.com/security/bulletin/ms10-053) | 未初始化的記憶體損毀弱點                                               | [CVE-2010-2559](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2559) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                        |  
| [MS10-051](http://technet.microsoft.com/security/bulletin/ms10-051) | Msxml2.XMLHTTP.3.0 回應處理記憶體損毀弱點                              | [CVE-2010-2561](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2561) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                                                                                                        |  
| [MS10-049](http://technet.microsoft.com/security/bulletin/ms10-049) | SChannel 格式錯誤的憑證要求遠端執行程式碼弱點                          | [CVE-2010-2566](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2566) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | 遭到利用時很有可能導致拒絕服務， 不太可能遠端執行程式碼。                                                                   |  
| [MS10-049](http://technet.microsoft.com/security/bulletin/ms10-049) | TLS/SSL 重新交涉弱點                                                   | [CVE-2009-3555](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3555) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 這是一個偽造弱點。 在 [Microsoft 安全性摘要報告 977377](http://technet.microsoft.com/security/advisory/977377) 中已有說明。 |  
| [MS10-053](http://technet.microsoft.com/security/bulletin/ms10-053) | 事件處理常式跨網域弱點                                                 | [CVE-2010-1258](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1258) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 這是一個資訊洩漏的弱點。                                                                                                    |  
| [MS10-058](http://technet.microsoft.com/security/bulletin/ms10-058) | IPv6 記憶體損毀弱點                                                    | [CVE-2010-1892](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1892) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 這是一項拒絕服務的弱點。                                                                                                    |  
| [MS10-054](http://technet.microsoft.com/security/bulletin/ms10-054) | SMB 變數驗證弱點                                                       | [CVE-2010-2551](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2551) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 這是一項拒絕服務的弱點。                                                                                                    |  
| [MS10-054](http://technet.microsoft.com/security/bulletin/ms10-054) | SMB 堆疊耗盡弱點                                                       | [CVE-2010-2552](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2552) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 這是一項拒絕服務的弱點。                                                                                                    |
  
受影響的軟體及下載位置  
----------------------
  
<span></span>
下表依據主要的軟體類別和嚴重性依序列出公告。
  
**我該如何使用這些表格？**
  
請用這些表格來瞭解可能需要安裝的資訊安全更新有哪些。 您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的資訊安全更新。 若軟體程式或更新出現在清單中，則相關可用軟體更新也會以超連結方式提供，也會列出軟體更新的嚴重性等級。
  
**注意：**一項弱點可能需要安裝數個資訊安全更新才能妥善解決。 請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
#### Windows 作業系統與元件

 
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
[**MS10-046**](http://technet.microsoft.com/security/bulletin/ms10-046)
</td>
<td style="border:1px solid black;">
[**MS10-049**](http://technet.microsoft.com/security/bulletin/ms10-049)
</td>
<td style="border:1px solid black;">
[**MS10-051**](http://technet.microsoft.com/security/bulletin/ms10-051)
</td>
<td style="border:1px solid black;">
[**MS10-052**](http://technet.microsoft.com/security/bulletin/ms10-052)
</td>
<td style="border:1px solid black;">
[**MS10-053**](http://technet.microsoft.com/security/bulletin/ms10-053)
</td>
<td style="border:1px solid black;">
[**MS10-054**](http://technet.microsoft.com/security/bulletin/ms10-054)
</td>
<td style="border:1px solid black;">
[**MS10-055**](http://technet.microsoft.com/security/bulletin/ms10-055)
</td>
<td style="border:1px solid black;">
[**MS10-060**](http://technet.microsoft.com/security/bulletin/ms10-060)
</td>
<td style="border:1px solid black;">
[**MS10-047**](http://technet.microsoft.com/security/bulletin/ms10-047)
</td>
<td style="border:1px solid black;">
[**MS10-048**](http://technet.microsoft.com/security/bulletin/ms10-048)
</td>
<td style="border:1px solid black;">
[**MS10-050**](http://technet.microsoft.com/security/bulletin/ms10-050)
</td>
<td style="border:1px solid black;">
[**MS10-058**](http://technet.microsoft.com/security/bulletin/ms10-058)
</td>
<td style="border:1px solid black;">
[**MS10-059**](http://technet.microsoft.com/security/bulletin/ms10-059)
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
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
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
無
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=12361875-b453-45e8-852b-90f2727894fd)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=ff00381c-e74b-48e5-9dd9-34dbedd906a2)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=dbdbbe5e-2ef9-4704-80c4-27ef28fd95ef)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=08159149-17de-4640-8818-cb7bd4811531)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=bc949915-4e16-4897-a295-2f99102548ab)  
(重大)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4b489f8c-ada0-4051-8284-0a941c04d2ed)  
(重大)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=1662780f-370a-425b-9917-c601eb54a375)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6e5e16f8-c140-4a1d-b898-8417a6bfd4d8)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=5ddb5e34-f97a-47c6-96c8-ba2ed06ccb77)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=648cfca5-19eb-4658-a6ad-fe546c4c44b9)  
(KB983582)  
(重大)  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1e53f250-2d4b-4f61-86ee-9f9f3a9c0b48)  
(KB983583)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e3574047-5ce5-4461-94aa-4eb3258d5e71)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=deeac521-d3a2-4019-8176-c9228e733cf4)  
(重要)
</td>
<td style="border:1px solid black;">
[Movie Maker 2.1](http://www.microsoft.com/downloads/details.aspx?familyid=b211664b-434d-4626-816f-c77510cfd44d)<sup>[1]</sup>
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
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3b44bd67-48e2-497f-9165-42a702e2cc0d)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=eaffa70c-6f2b-4e66-b1bc-64bdbbbcd34f)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=4d4e8eeb-a0b2-41c6-9ee4-3f4beb44195e)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b7f28d7a-6b27-4059-865b-5fd55edb6299)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=96b7a562-af16-4f0d-840c-838fb12e7419)  
(重大)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5296fb82-c446-4681-a9a0-0f80a2e248be)  
(重大)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=f8ae3978-bad6-4201-8357-2d212ab703ef)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=fd6cc359-e72e-46ec-a08b-763934e3e115)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/my%20documents/release/5cff5d6e-11a5-40ed-92ac-e12d287919e6)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=648cfca5-19eb-4658-a6ad-fe546c4c44b9)  
(KB983582)  
(重大)  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1e53f250-2d4b-4f61-86ee-9f9f3a9c0b48)  
(KB983583)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d6c5455e-bc31-4842-aef4-ebff92324323)  
(重要)
</td>
<td style="border:1px solid black;">
[Movie Maker 2.1](http://www.microsoft.com/downloads/details.aspx?familyid=decb1fe6-adc8-44f7-89c5-f25767f0cefe)<sup>[1]</sup>
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
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-046**](http://technet.microsoft.com/security/bulletin/ms10-046)
</td>
<td style="border:1px solid black;">
[**MS10-049**](http://technet.microsoft.com/security/bulletin/ms10-049)
</td>
<td style="border:1px solid black;">
[**MS10-051**](http://technet.microsoft.com/security/bulletin/ms10-051)
</td>
<td style="border:1px solid black;">
[**MS10-052**](http://technet.microsoft.com/security/bulletin/ms10-052)
</td>
<td style="border:1px solid black;">
[**MS10-053**](http://technet.microsoft.com/security/bulletin/ms10-053)
</td>
<td style="border:1px solid black;">
[**MS10-054**](http://technet.microsoft.com/security/bulletin/ms10-054)
</td>
<td style="border:1px solid black;">
[**MS10-055**](http://technet.microsoft.com/security/bulletin/ms10-055)
</td>
<td style="border:1px solid black;">
[**MS10-060**](http://technet.microsoft.com/security/bulletin/ms10-060)
</td>
<td style="border:1px solid black;">
[**MS10-047**](http://technet.microsoft.com/security/bulletin/ms10-047)
</td>
<td style="border:1px solid black;">
[**MS10-048**](http://technet.microsoft.com/security/bulletin/ms10-048)
</td>
<td style="border:1px solid black;">
[**MS10-050**](http://technet.microsoft.com/security/bulletin/ms10-050)
</td>
<td style="border:1px solid black;">
[**MS10-058**](http://technet.microsoft.com/security/bulletin/ms10-058)
</td>
<td style="border:1px solid black;">
[**MS10-059**](http://technet.microsoft.com/security/bulletin/ms10-059)
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
[**中度**](http://technet.microsoft.com/security/bulletin/rating)
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
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
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
<td style="border:1px solid black;">
無
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=32fe91ef-5a8d-4095-90ee-2ca216696b09)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f76d68df-97e5-489c-a5f6-0c378c1f62ae)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=31ce233e-4d2d-404b-84a8-683319ba8ef7)  
(中度)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9c2110ec-7e6c-4e73-9785-0a8196095ea0)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=b0370e1e-dedf-4fe8-a06c-0e0f0a674205)  
(重大)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=8753ae27-60a4-475a-b8bc-6a7764480295)  
(重大)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=772e765d-0502-4b0b-bde8-d4f62b96db64)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=230e8559-e6df-49d5-acb5-b0cd4bde0bf4)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=648cfca5-19eb-4658-a6ad-fe546c4c44b9)  
(KB983582)  
(重大)  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1e53f250-2d4b-4f61-86ee-9f9f3a9c0b48)  
(KB983583)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=59395f00-90f4-4b68-8dd3-03ff611c1bc8)  
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
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=923de214-c4fa-41e6-8307-2c5a37f13e8e)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4543bcf0-3505-407b-a5a9-6250ece6fbac)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=4d784b57-8564-4e7e-8f61-f897398e7ea5)  
(中度)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=fdfad4ca-37c4-4ac5-bebc-a5ad61299503)  
(重大)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=d92f5e69-43cf-4615-aa3b-41f9f40bb57b)  
(重大)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=fd3e9d06-1f8b-4ef7-84f6-61e85a1767b8)  
(重大)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=863edf45-0d3b-4408-a47c-258dc4a4fd94)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=03804f59-748e-4832-98e4-2d88564bd10a)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=648cfca5-19eb-4658-a6ad-fe546c4c44b9)  
(KB983582)  
(重大)  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1e53f250-2d4b-4f61-86ee-9f9f3a9c0b48)  
(KB983583)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9ef1c600-bb93-4800-81b8-8c64b369c194)  
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
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=63aa5f8a-fe47-4892-b905-b54e4f3b6580)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=9ef992c3-96e9-4533-b844-07424a6054b3)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=d87ac8b3-41fb-4cdd-b305-181a0024d85c)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=782e2963-4a52-4a1d-b99a-34ba841038a7)  
(重大)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5e730064-8270-4d63-b497-c5ebeddea1fc)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=e4f4f8b3-7a39-4d77-a46b-02c86ad159c3)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=648cfca5-19eb-4658-a6ad-fe546c4c44b9)  
(KB983582)  
(重大)  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1e53f250-2d4b-4f61-86ee-9f9f3a9c0b48)  
(KB983583)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=f96b8154-9976-41b0-b9d7-d79887fe9364)  
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
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-046**](http://technet.microsoft.com/security/bulletin/ms10-046)
</td>
<td style="border:1px solid black;">
[**MS10-049**](http://technet.microsoft.com/security/bulletin/ms10-049)
</td>
<td style="border:1px solid black;">
[**MS10-051**](http://technet.microsoft.com/security/bulletin/ms10-051)
</td>
<td style="border:1px solid black;">
[**MS10-052**](http://technet.microsoft.com/security/bulletin/ms10-052)
</td>
<td style="border:1px solid black;">
[**MS10-053**](http://technet.microsoft.com/security/bulletin/ms10-053)
</td>
<td style="border:1px solid black;">
[**MS10-054**](http://technet.microsoft.com/security/bulletin/ms10-054)
</td>
<td style="border:1px solid black;">
[**MS10-055**](http://technet.microsoft.com/security/bulletin/ms10-055)
</td>
<td style="border:1px solid black;">
[**MS10-060**](http://technet.microsoft.com/security/bulletin/ms10-060)
</td>
<td style="border:1px solid black;">
[**MS10-047**](http://technet.microsoft.com/security/bulletin/ms10-047)
</td>
<td style="border:1px solid black;">
[**MS10-048**](http://technet.microsoft.com/security/bulletin/ms10-048)
</td>
<td style="border:1px solid black;">
[**MS10-050**](http://technet.microsoft.com/security/bulletin/ms10-050)
</td>
<td style="border:1px solid black;">
[**MS10-058**](http://technet.microsoft.com/security/bulletin/ms10-058)
</td>
<td style="border:1px solid black;">
[**MS10-059**](http://technet.microsoft.com/security/bulletin/ms10-059)
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
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
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
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 1 和 Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=52748886-6280-4247-8cbd-f64db229ee66)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=aca69406-f795-4398-968f-959fe3a74e89)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=bbfaadf8-ab38-456c-956a-ea18c64236c9)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=535c563e-cdac-4e3d-96b0-9947ea22deca)  
(重大)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=2062566b-8b81-43c2-875d-9c06d4e3fa82)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9087a3aa-aa55-41f6-8c4c-f322e4aa8681)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=60c81415-b61e-44a4-8dd9-cedec99eb70f)  
(重大)
</td>
<td style="border:1px solid black;">
僅限 Windows Vista Service Pack 1：  
[Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=616c39f7-137a-40b9-b691-bc33c0aef7e1)  
(KB983587)  
(重大)  
僅限 Windows Vista Service Pack 1：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=155bbb5c-247e-4bed-a287-527d978b7967)  
(KB983588)  
(重大)  
僅限 Windows Vista Service Pack 2：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7712e8ad-dea4-4a43-8a7b-dc154510c104)  
(KB983589)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4486f97c-4cf8-4236-bfc3-b50e72e2a5c1)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c9345207-7242-4b71-bf80-b52031e08f8c)  
(重要)
</td>
<td style="border:1px solid black;">
[Movie Maker 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=8aded9dd-08d6-4b19-955f-0d8414868cf9)<sup>[1]</sup>
(重要)  
[Movie Maker 2.6](http://www.microsoft.com/downloads/details.aspx?familyid=a1d8ed0d-a3b5-416a-ab8b-77501da62132)<sup>[2]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4684c4df-0a5c-4dba-82e5-059378737118)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=dfb31aa2-7457-4581-9e28-7984a360edf4)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=37648e95-05c2-4802-9a0f-660200baa229)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e2835ed1-5ca6-4347-8ff1-e694b1ac49ff)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=577131cd-1229-4746-89d7-84d75f29e1f0)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=cd1185e3-ca22-4197-a53b-e7a2806ac352)  
(重大)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=65b04e29-8e39-46de-94e8-b653969b1ffd)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=10c9d5f1-53ed-459b-a663-e69bdb845a6b)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=469b732d-ca62-4a48-bb55-99f2ae4ddcf5)  
(重大)
</td>
<td style="border:1px solid black;">
僅限 Windows Vista x64 Edition Service Pack 1：  
[Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=616c39f7-137a-40b9-b691-bc33c0aef7e1)  
(KB983587)  
(重大)  
僅限 Windows Vista x64 Edition Service Pack 1：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=155bbb5c-247e-4bed-a287-527d978b7967)  
(KB983588)  
(重大)  
僅限 Windows Vista x64 Edition Service Pack 2：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7712e8ad-dea4-4a43-8a7b-dc154510c104)  
(KB983589)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b547898e-f8a9-49dc-b49d-cffec5a001bc)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1620e7ac-3913-478d-8120-e9f46d98f453)  
(重要)
</td>
<td style="border:1px solid black;">
[Movie Maker 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=4baff9ae-dd25-4942-b45e-f281d0e1f4ac)<sup>[1]</sup>
(重要)  
[Movie Maker 2.6](http://www.microsoft.com/downloads/details.aspx?familyid=0a226592-8f98-4f67-ac60-1d00cbc56598)<sup>[2]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=18152cd4-815f-425f-8694-fbabcbe80609)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=110f932f-d13c-4486-a295-e6068d5d8d7a)  
(重要)
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
[**MS10-046**](http://technet.microsoft.com/security/bulletin/ms10-046)
</td>
<td style="border:1px solid black;">
[**MS10-049**](http://technet.microsoft.com/security/bulletin/ms10-049)
</td>
<td style="border:1px solid black;">
[**MS10-051**](http://technet.microsoft.com/security/bulletin/ms10-051)
</td>
<td style="border:1px solid black;">
[**MS10-052**](http://technet.microsoft.com/security/bulletin/ms10-052)
</td>
<td style="border:1px solid black;">
[**MS10-053**](http://technet.microsoft.com/security/bulletin/ms10-053)
</td>
<td style="border:1px solid black;">
[**MS10-054**](http://technet.microsoft.com/security/bulletin/ms10-054)
</td>
<td style="border:1px solid black;">
[**MS10-055**](http://technet.microsoft.com/security/bulletin/ms10-055)
</td>
<td style="border:1px solid black;">
[**MS10-060**](http://technet.microsoft.com/security/bulletin/ms10-060)
</td>
<td style="border:1px solid black;">
[**MS10-047**](http://technet.microsoft.com/security/bulletin/ms10-047)
</td>
<td style="border:1px solid black;">
[**MS10-048**](http://technet.microsoft.com/security/bulletin/ms10-048)
</td>
<td style="border:1px solid black;">
[**MS10-050**](http://technet.microsoft.com/security/bulletin/ms10-050)
</td>
<td style="border:1px solid black;">
[**MS10-058**](http://technet.microsoft.com/security/bulletin/ms10-058)
</td>
<td style="border:1px solid black;">
[**MS10-059**](http://technet.microsoft.com/security/bulletin/ms10-059)
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
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
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
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
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
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3aabd189-7d4c-4c9f-8854-f33127b1c309)\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6e0253d4-f0c0-4f28-ba08-6907c2fcb339)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=73b5f45c-c9d6-491f-8483-98838b2a7c04)\*  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=8239cb9e-bb5a-4157-8038-33d0b329eaee)\*\*  
(重大)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=409b9298-1e7d-48cf-9872-ffbdc56ebe53)\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a94e2e38-116a-4b63-9328-6c33e63bbbfe)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
僅適用於 32 位元系統的 Windows Server 2008：  
[Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=616c39f7-137a-40b9-b691-bc33c0aef7e1)\*\*  
(KB983587)  
(重大)  
僅適用於 32 位元系統的 Windows Server 2008：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=155bbb5c-247e-4bed-a287-527d978b7967)\*\*  
(KB983588)  
(重大)  
僅適用於 32 位元系統的 Windows Server 2008 Service Pack 2：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7712e8ad-dea4-4a43-8a7b-dc154510c104)\*\*  
(KB983589)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=611765ab-b3f3-45db-92b2-ee040b9cfd27)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a8b1a3f7-7147-494e-bfc0-b1979b9578e6)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=844404be-f2e8-47bc-9650-9e2bbe383814)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4c9b3e60-e166-40c9-8938-3cba0a399c47)\*  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=29c6fc2d-d318-4a63-9ab2-82e84272aaf2)\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a96891ff-8771-47b3-81bb-8640adb6c098)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=43ece408-4aa7-4819-b3f6-7f0719ed3213)\*  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5ef8abf0-c89e-4911-8d77-42400d9a398f)\*\*  
(重大)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=9b869bab-0797-4f83-8c64-23dda9983c8d)\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=602dd3f6-0d09-4546-b1db-d7b6b04edb66)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
僅適用於 x64 型系統的 Windows Server 2008：  
[Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=616c39f7-137a-40b9-b691-bc33c0aef7e1)\*\*  
(KB983587)  
(重大)  
僅適用於 x64 型系統的 Windows Server 2008：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=155bbb5c-247e-4bed-a287-527d978b7967)\*\*  
(KB983588)  
(重大)  
僅適用於 x64 型系統的 Windows Server 2008 Service Pack 2：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7712e8ad-dea4-4a43-8a7b-dc154510c104)\*\*  
(KB983589)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=131f3512-1585-462e-a4f1-3f359aac44bd)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c1c25cb7-7e82-4c14-9666-aff52dd308b4)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=08491c73-66b1-4c4c-8740-ea596a730fc1)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=fa84e547-2190-402f-9467-2450deeff565)\*  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=cfe227b5-6660-49f8-9d71-a997dd83de0b)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3b16a422-0ee9-4eab-9cfe-e7688ffa0d76)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=b6faee94-e821-432d-bfa2-9008664566af)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=2f1eee63-2cca-4ec5-b196-36de3c0054cf)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=24d8f0a3-51a9-46c1-b870-a2239bf600e4)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
僅適用於 Itanium 型系統的 Windows Server 2008：  
[Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=616c39f7-137a-40b9-b691-bc33c0aef7e1)  
(KB983587)  
(重大)  
僅適用於 Itanium 型系統的 Windows Server 2008：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=155bbb5c-247e-4bed-a287-527d978b7967)  
(KB983588)  
(重大)  
僅適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7712e8ad-dea4-4a43-8a7b-dc154510c104)  
(KB983589)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=972efd3a-ec1e-49b2-835e-76f4b21b5b79)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=45fe5135-aa89-4f60-8cdb-ec0edc9a7e77)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8aa12902-c234-4fd9-bba3-6767eafc38fc)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=84f89dca-108c-4956-9aa2-866e17a872fc)  
(重要)
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
[**MS10-046**](http://technet.microsoft.com/security/bulletin/ms10-046)
</td>
<td style="border:1px solid black;">
[**MS10-049**](http://technet.microsoft.com/security/bulletin/ms10-049)
</td>
<td style="border:1px solid black;">
[**MS10-051**](http://technet.microsoft.com/security/bulletin/ms10-051)
</td>
<td style="border:1px solid black;">
[**MS10-052**](http://technet.microsoft.com/security/bulletin/ms10-052)
</td>
<td style="border:1px solid black;">
[**MS10-053**](http://technet.microsoft.com/security/bulletin/ms10-053)
</td>
<td style="border:1px solid black;">
[**MS10-054**](http://technet.microsoft.com/security/bulletin/ms10-054)
</td>
<td style="border:1px solid black;">
[**MS10-055**](http://technet.microsoft.com/security/bulletin/ms10-055)
</td>
<td style="border:1px solid black;">
[**MS10-060**](http://technet.microsoft.com/security/bulletin/ms10-060)
</td>
<td style="border:1px solid black;">
[**MS10-047**](http://technet.microsoft.com/security/bulletin/ms10-047)
</td>
<td style="border:1px solid black;">
[**MS10-048**](http://technet.microsoft.com/security/bulletin/ms10-048)
</td>
<td style="border:1px solid black;">
[**MS10-050**](http://technet.microsoft.com/security/bulletin/ms10-050)
</td>
<td style="border:1px solid black;">
[**MS10-058**](http://technet.microsoft.com/security/bulletin/ms10-058)
</td>
<td style="border:1px solid black;">
[**MS10-059**](http://technet.microsoft.com/security/bulletin/ms10-059)
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
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/security/bulletin/rating)
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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=22e62b5c-e4c1-47d0-ae4a-8bd2d70d0a0a)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=71716507-7080-4102-991e-6afc7cc377d5)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=31d0f5ac-2cff-42a1-8f18-128bbfc4e57d)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ecaf42e0-a288-40c1-8602-21e967a87408)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=8d58ebc4-a5f9-4318-a6f1-168c1bcdae3c)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=2e782ac9-b5d5-490e-a01a-7d4481eab224)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=77d0c428-237c-4dab-9645-6400dd9e65f8)  
(KB983590)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=a7d60864-5942-47ed-a6f3-1c07b4833a14)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=68bddf4b-b597-477e-80e4-9293d7160496)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=3a5a088e-644a-4a0e-9a09-0370bcd97688)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=ce6233f3-2ee5-4329-908d-ba9b28ecc553)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=9499f771-c388-4de3-a5c7-8cc8b00b4395)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=c457d8ec-83b7-446f-b77c-e47d4187e616)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=a4f6d7c2-b475-4900-82f0-75f5be0b7b63)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ca57a47a-9111-4abe-9356-4962ca2c1d65)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=ad1ddf94-d714-4b36-8256-42bf79d03a90)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=24751193-592f-4c44-a8d6-f4112d4f011b)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=77d0c428-237c-4dab-9645-6400dd9e65f8)  
(KB983590)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=b00ec47c-402e-4207-a4c9-6c1900f254f8)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=5ff09e03-d662-4b23-ab26-d25ca2ba58df)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=163fe2bd-f999-47c1-9a35-c4fc868bda51)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](http://www.microsoft.com/downloads/details.aspx?familyid=146270fa-cd6f-440a-aa3e-e93af0bff447)  
(重要)
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
[**MS10-046**](http://technet.microsoft.com/security/bulletin/ms10-046)
</td>
<td style="border:1px solid black;">
[**MS10-049**](http://technet.microsoft.com/security/bulletin/ms10-049)
</td>
<td style="border:1px solid black;">
[**MS10-051**](http://technet.microsoft.com/security/bulletin/ms10-051)
</td>
<td style="border:1px solid black;">
[**MS10-052**](http://technet.microsoft.com/security/bulletin/ms10-052)
</td>
<td style="border:1px solid black;">
[**MS10-053**](http://technet.microsoft.com/security/bulletin/ms10-053)
</td>
<td style="border:1px solid black;">
[**MS10-054**](http://technet.microsoft.com/security/bulletin/ms10-054)
</td>
<td style="border:1px solid black;">
[**MS10-055**](http://technet.microsoft.com/security/bulletin/ms10-055)
</td>
<td style="border:1px solid black;">
[**MS10-060**](http://technet.microsoft.com/security/bulletin/ms10-060)
</td>
<td style="border:1px solid black;">
[**MS10-047**](http://technet.microsoft.com/security/bulletin/ms10-047)
</td>
<td style="border:1px solid black;">
[**MS10-048**](http://technet.microsoft.com/security/bulletin/ms10-048)
</td>
<td style="border:1px solid black;">
[**MS10-050**](http://technet.microsoft.com/security/bulletin/ms10-050)
</td>
<td style="border:1px solid black;">
[**MS10-058**](http://technet.microsoft.com/security/bulletin/ms10-058)
</td>
<td style="border:1px solid black;">
[**MS10-059**](http://technet.microsoft.com/security/bulletin/ms10-059)
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
[**中度**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
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
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**中度**](http://technet.microsoft.com/security/bulletin/rating)
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
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=0d9dd09b-db40-462b-88b0-4dbb8180e81f)\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=c9aeea25-ca14-4b42-9018-a27c9d8899c4)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=a48cdac5-4d78-49b5-a6d8-ecf6c58cace2)\*  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e7757bbc-3ef0-421d-ab57-0083a302c77b)\*\*  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=52642a8d-1081-4496-848e-9b03baf3fdac)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=77d0c428-237c-4dab-9645-6400dd9e65f8)\*  
(KB983590)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=c1ad1248-07f1-42d4-baa4-8a20837ec7b4)\*  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=6bbc9cb1-0b59-4473-adf9-2ce2f0f94c0a)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=a1f95600-34e5-44b3-b2cb-b2b2cbf645cb)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=333fb6e4-f867-4dcb-beb3-2d88e428ca2e)\*  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=ce2bb5d4-f661-44e3-ac28-0b81f7b72670)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=b7c2e91f-ca8a-4237-99c8-ca53c91cf73e)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=b4d3210e-f3ad-4dbb-9390-6e98eeb99eaa)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7b457d04-03a9-4eb0-ba6a-ab45267e4f74)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=783fb42c-3698-4b1d-a692-3ff319578931)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=77d0c428-237c-4dab-9645-6400dd9e65f8)  
(KB983590)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=f23dec0f-a33b-4d8c-a86d-0e9368ae7ff5)  
(中度)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=2543191a-09cb-4417-bbb2-aac4d9a2a756)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=c3cd7f2f-e198-4fbd-a65d-21a1bf51eb61)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows Server 2008 R2](http://www.microsoft.com/downloads/details.aspx?familyid=62034ecb-a6bd-46c5-a03d-9642880bc2d6)  
(重要)
</td>
</tr>
</table>
 
**Windows Server 2008 和 Windows Server 2008 R2 注意事項**

**\*Server Core 安裝會受影響。** 無論上述受支援的 Windows Server 2008 或 Windows Server 2008 R2 版本是否使用 Server Core 安裝選項安裝，這個更新均以相同的嚴重性等級套用。 如需此安裝選項的詳細資訊，請參閱 TechNet 文章：[管理 Server Core 安裝](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[維護 Server Core 安裝](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 和 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**\*\*Server Core 安裝不受影響。** 如果 Windows Server 2008 或 Windows Server 2008 R2 是使用 Server Core 安裝選項所安裝，則這項更新解決的弱點並不會影響受支援的 Windows Server 2008 或 Windows Server 2008 R2。 如需此安裝選項的詳細資訊，請參閱 TechNet 文章：[管理 Server Core 安裝](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[維護 Server Core 安裝](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 和 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**MS10-050 注意事項**

<sup>[1]</sup>這些 Windows Movie Maker 版本隨附於所述的作業系統。

<sup>[2]</sup> Windows Movie Maker 2.6 是選用的下載，可安裝於所述的作業系統。

**MS10-060 注意事項**

另請參閱＜受影響的軟體及下載位置＞中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。 本公告涉及多個軟體分類。

#### Microsoft Office 套件及軟體

 
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
[**MS10-056**](http://technet.microsoft.com/security/bulletin/ms10-056)
</td>
<td style="border:1px solid black;">
[**MS10-057**](http://technet.microsoft.com/security/bulletin/ms10-057)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=978eb887-25b6-4dde-a2ec-d2d1e7f1a434)  
(KB2251389)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=032e1530-8736-4e1c-a704-967679227619)  
(KB2264397)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=4360bcec-0731-4d4a-89eb-7d28a4607f06)  
(KB2251399)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=7cecbce3-bbb7-47d1-bda3-64d7e0f69f62)  
(KB2264403)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0d7210a3-662e-41e7-affc-ae94f9d89388)  
(KB2251419)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-056**](http://technet.microsoft.com/security/bulletin/ms10-056)
</td>
<td style="border:1px solid black;">
[**MS10-057**](http://technet.microsoft.com/security/bulletin/ms10-057)
</td>
</tr>
<tr>
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=d2f44d4a-7cd8-4514-b3ff-1770bc47d595)  
(KB2284171)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=d2f44d4a-7cd8-4514-b3ff-1770bc47d595)  
(KB2284171)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=6ece112f-0ca7-4b1f-ad20-603950edee66)  
(KB2284162)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=6ece112f-0ca7-4b1f-ad20-603950edee66)  
(KB2284162)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=a7b834a3-5a44-42d4-afe9-6ef207333834)  
(KB2284179)  
(重要)
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=a7b834a3-5a44-42d4-afe9-6ef207333834)  
(KB2284179)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
其他 Office 軟體
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-056**](http://technet.microsoft.com/security/bulletin/ms10-056)
</td>
<td style="border:1px solid black;">
[**MS10-057**](http://technet.microsoft.com/security/bulletin/ms10-057)
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
Microsoft Office Word Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Office Word Viewer](http://www.microsoft.com/downloads/details.aspx?familyid=39fe2229-9201-4270-bdc1-20bc8e30a766)  
(KB2251437)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Word、Excel 及 PowerPoint 2007 檔案格式相容性套件 Service Pack 2
</td>
<td style="border:1px solid black;">
[Word、Excel 與 PowerPoint 2007 檔案格式的 Microsoft Office 相容性套件 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ed5b9671-651d-41f3-aed3-93ee8a28657f)  
(KB2277947)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works 9
</td>
<td style="border:1px solid black;">
[Microsoft Works 9](http://www.microsoft.com/downloads/details.aspx?familyid=feb121ad-e5f6-40e2-bf12-045ae5c2a754)  
(KB2092914)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
</table>
 

#### Microsoft 開發者工具和軟體

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
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
[**MS10-060**](http://technet.microsoft.com/security/bulletin/ms10-060)
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
Microsoft Silverlight 2
</td>
<td style="border:1px solid black;">
安裝在 Mac 上的[Microsoft Silverlight 2](http://www.microsoft.com/getsilverlight/get-started/install/default.aspx)<sup>[1]</sup>
(KB982926)  
(重大)  
安裝在所有 Microsoft Windows 用戶端版本上的 [Microsoft Silverlight 2](http://www.microsoft.com/getsilverlight/get-started/install/default.aspx)<sup>[1]</sup>
(KB982926)  
(重大)  
安裝在所有 Microsoft Windows 伺服器版本上的 [Microsoft Silverlight 2](http://www.microsoft.com/getsilverlight/get-started/install/default.aspx)<sup>[1]</sup>\*\*  
(KB982926)  
(重大)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Silverlight 3
</td>
<td style="border:1px solid black;">
安裝在 Mac 上的 [Microsoft Silverlight 3](http://www.microsoft.com/downloads/details.aspx?familyid=7e3f6c16-1339-49bc-a60c-ddc6c3a54850)<sup>[2]</sup>
(KB978464)  
(重大)  
安裝在所有 Microsoft Windows 用戶端版本上的 [Microsoft Silverlight 3](http://www.microsoft.com/downloads/details.aspx?familyid=7e3f6c16-1339-49bc-a60c-ddc6c3a54850)<sup>[2]</sup>
(KB978464)  
(重大)  
安裝在所有 Microsoft Windows 伺服器版本上的 [Microsoft Silverlight 3](http://www.microsoft.com/downloads/details.aspx?familyid=7e3f6c16-1339-49bc-a60c-ddc6c3a54850)<sup>[2]</sup>\*\*  
(KB978464)  
(重大)
</td>
</tr>
</table>
 
**MS10-060 注意事項**

**\*\*Server Core 安裝不受影響。** 如果 Windows Server 2008 或 Windows Server 2008 R2 是使用 Server Core 安裝選項所安裝，則這項更新解決的弱點並不會影響受支援的 Windows Server 2008 或 Windows Server 2008 R2。 如需此安裝選項的詳細資訊，請參閱 TechNet 文章：[管理 Server Core 安裝](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[維護 Server Core 安裝](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 和 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

<sup>[1]</sup>此下載會將 Microsoft Silverlight 2 升級至不受本公告所描述弱點影響的新版。

<sup>[2]</sup>此下載會將 Microsoft Silverlight 升級至不受本公告所描述弱點影響的新版。

另請參閱＜受影響的軟體及下載位置＞中的其他軟體類別，以取得更多相同公告編號裡的更新檔案。 本公告涉及多個軟體分類。

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和資訊安全更新。 如需更多資訊，請參閱 [TechNet 更新管理中心](http://go.microsoft.com/fwlink/?linkid=69903) (英文)。 [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) 提供 Microsoft 產品安全性的其他資訊。 消費者可以造訪[在家上網的安全性](http://go.microsoft.com/fwlink/?linkid=85102)網站，只要按一下 \[最新資訊安全更新\] 即可在此網站取得此資訊。

資訊安全更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 以及 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) 取得。 資訊安全更新也可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得。 您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。

最後，您可以從 [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) 下載資訊安全更新。 Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括資訊安全更新、驅動程式和 Service Pack。 只要以資訊安全公告編號 (例如：MS07-036) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。 如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](http://go.microsoft.com/fwlink/?linkid=97900)。

**注意：**自 2009 年 8 月 1 日開始，Microsoft 已停止支援 Office Update 與 Office Update Inventory Tool。 若要繼續取得 Microsoft Office 產品的最新更新，請使用 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)。 如需更多資訊，請參閱[關於 Microsoft Office Update： 常見問題集](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx) (英文)。

**偵測與部署指南**

Microsoft 針對資訊安全更新提供偵測和部署指南。 本指南所含之建議和資訊，能幫助 IT 專業人員瞭解如何使用用於資訊安全更新的偵測和部署的各種工具。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 961747](http://support.microsoft.com/kb/961747/zh-tw)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少資訊安全更新以及一般安全性設定錯誤的狀況。 如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) 網站 (英文)。

**Windows Server Update Services**

Windows Server Update Services (WSUS) 可讓資訊技術管理員將最新的 Microsoft 產品更新部署到執行 Windows 作業系統的電腦。 如需更多關於利用 Windows Server Update Services 部署資訊安全更新的資訊，請參閱 TechNet 文章：[Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/default.aspx) (英文)。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要資訊安全更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。 現已推出新版的 SMS，System Center Configuration Manager 2007；另請參閱 [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)。如需更多有關系統管理員如何能使用 SMS 2003 部署資訊安全更新的資訊，請參閱 [SMS 2003 安全性修補程式管理](http://go.microsoft.com/fwlink/?linkid=22939) (英文)。 SMS 2.0 使用者也可以使用資訊安全更新盤點工具 (Security Update Inventory Tool，SUIT) 來協助部署資訊安全更新。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158)。

**注意：**SMS 使用 Microsoft Baseline Security Analyzer 提供廣泛的資訊安全公告更新偵測與部署支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些資訊安全更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可使用 Elevated Rights Deployment Tool (隨 [SMS 2.0 Administration Feature Pack (英文)](http://go.microsoft.com/fwlink/?linkid=21161) 提供) 來安裝這些更新。

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

為了增強客戶的安全性保護，Microsoft 將在每月發行資訊安全更新之前，提前向重要資訊安全軟體提供者提供弱點資訊。 資訊安全軟體提供者可利用此弱點資訊，透過其資訊安全軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。 如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://www.microsoft.com/security/msrc/mapp/partners.mspx)上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 安全性策略與社群

**更新程式管理策略**

[更新程式管理安全性指南](http://go.microsoft.com/fwlink/?linkid=21168)提供您有關套用資訊安全更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他資訊安全更新**

其他安全性問題的更新可由下列位置取得：

-   資訊安全更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。
-   客戶平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的資訊安全更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](http://support.microsoft.com/kb/913086/zh-tw)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](http://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](http://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 [VirusBlokAda](http://www.anti-virus.by/) 的 Sergey I. Ulasen 和 Oleg Kupreev 回報 MS10-046 中描述的一項問題
-   感謝 [AV-Test](http://www.av-test.org/) 的Andreas Marx 和 Maik Morgensternfor 回報 MS10-046 中描述的一項問題
-   感謝 [CERT/CC](http://www.cert.org) 的 Will Dormann 協助我們解決 MS10-046 中描述的一項問題
-   感謝 Niels Teusink 協助我們解決 MS10-046 中描述的一項問題
-   感謝 Stefan Kanthak 協助我們解決 MS10-046 中描述的一項問題
-   感謝 [Google Inc.](http://www.google.com/) 的 Tavis Ormandy 回報 MS10-047 中描述的三個問題
-   感謝 [Google Inc.](http://www.google.com/) 的 Tavis Ormandy 回報 MS10-048 中描述的問題
-   感謝 [MoonSols](http://moonsols.com/) 的 Matthieu Suiche 回報 MS10-048 中描述的兩個問題
-   感謝 [MoonSols](http://moonsols.com/) 的 Matthieu Suiche 與我們合作 MS10-048 中所述的深度防禦變更。
-   感謝 [Core Security Technologies](http://www.coresecurity.com/) 的 Nicolas Economou 回報 MS10-048 中描述的問題
-   感謝 [PhoneFactor](http://www.phonefactor.com/) 的Marsh Ray 和 Steve Dispensa 回報 MS10-049 中描述的問題
-   感謝 [Secunia](http://secunia.com/) 的 Dyon Balding 回報 MS10-050 中描述的問題
-   感謝 [Google Inc.](http://www.google.com/) 的 SkyLined 回報 MS10-051 中描述的問題
-   感謝 n.runs AG 的 Moritz Jodeit 與 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，回報 MS10-052 所描述的問題
-   感謝 [Google Inc.](http://www.google.com/) 的 David Bloom 回報 MS10-053 中描述的問題
-   感謝 [VUPEN Vulnerability Research Team](http://www.vupen.com) 的 Nicolas Joly 回報 MS10-053 中描述的四個問題
-   感謝 Gambino ZaDarkSide 回報 MS10-053 中描述的問題
-   感謝 [stratsec](http://www.stratsec.net/) 的 Laurent Gaffié 回報 MS10-054 中描述的問題
-   感謝 [Sourcefire VRT](http://www.sourcefire.com/services/sf_vrt.html) 的 Todd Wease 和 Richard Johnson 回報 MS10-054 中描述的問題
-   感謝 [Codenomicon](http://www.codenomicon.com/) 的 Riku Hietamaki 回報 MS10-054 中描述的問題
-   感謝匿名的研究人員與 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 MS10-055 中描述的問題
-   感謝 [team509](http://www.team509.com/) 的 L.W.Z 與 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 MS10-056 中描述的問題
-   感謝 [team509](http://www.team509.com/) 的 Wushi 與 [VeriSign iDefense Labs](http://labs.idefense.com/) 合作回報 MS10-056 中描述的問題
-   感謝 [team509](http://www.team509.com/) 與 [VeriSign iDefense Labs](http://labs.idefense.com/) 合作回報 MS10-056 中描述的問題
-   感謝 [Check Point](http://www.checkpoint.com/) IPS Research Team 的 Rodrigo Rubira Branco 回報 MS10-056 中描述的問題
-   感謝匿名的研究人員與 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作回報 MS10-056 中描述的一項問題
-   感謝 [Core Security Technologies](http://www.coresecurity.com/) 的 Damián Frizza 回報 MS10-057 中描述的問題
-   感謝 [Fourteenforty Research Institute, Inc.](http://www.fourteenforty.jp/) 的 Darren Willis 回報 MS10-058 中描述的問題
-   感謝 [MoonSols](http://moonsols.com/) 的 Matthieu Suiche 回報 MS10-058 中描述的問題
-   感謝 [Argeniss](http://www.argeniss.com/) 的 Cesar Cerrudo 協助我們解決 MS10-059 中描述的兩個問題
-   感謝 的 Carsten Book 回報 MS10-060 中描述的問題
-   感謝 [Eamon Nerbonne](http://eamon.nerbonne.org/) 回報 MS10-060 中描述的一個問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可洽詢[資訊安全支援](http://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 以取得技術支援。 與資訊安全更新有關的支援電話不另外收費。 如需更多可用支援選項的資訊，請參閱 [Microsoft 技術支援服務](http://support.microsoft.com/)。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與資訊安全更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](http://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2010 年 8 月 2 日)： 公告摘要發行。
-   V2.0 (2010 年 8 月 23 日)： 新增公告：MS10-047 到 MS10-060。

*Built at 2014-04-18T01:50:00Z-07:00*
