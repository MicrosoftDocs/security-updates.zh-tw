---
TOCTitle: 'MS10-FEB'
Title: 2010 年 2 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms10-feb'
ms:contentKeyID: 61237704
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms10-feb(v=Security.10)'
---

2010 年 2 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2010年2月10日

**版本:** 1.0

此公告摘要列出 2010 年 2 月份發行之安全性公告。

發行 2010 年 2 月份公告之後，此公告摘要將取代原先於 2010 年 2 月 4 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 資訊安全性公告預先通知](https://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 資訊安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2010 年 2 月 10 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。 立即註冊參加 [2 月份安全性公告網路廣播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032427679&culture=en-us)。 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 資訊安全性公告摘要和網路廣播](https://technet.microsoft.com/security/bulletin/summary)。

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-006">MS10-006</a></td>
<td style="border:1px solid black;"><strong>SMB 用戶端中的弱點可能會允許遠端執行程式碼 (978251)</strong><br />
<br />
這個安全性更新可解決 Microsoft Windows 中兩項未公開報告的弱點。 如果攻擊者將蓄意製作的 SMB 回應傳送至一用戶端啟動的 SMB 要求，這些弱點可能會允許遠端執行程式碼。 要利用這些弱點，攻擊者必須引誘使用者啟動連至一台惡意 SMB 伺服器的 SMB 連線。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-007">MS10-007</a></td>
<td style="border:1px solid black;"><strong>Windows Shell Handler 中的弱點可能會允許遠端執行程式碼 (975713)</strong><br />
<br />
此安全性更新解決了 Microsoft Windows 2000、Windows XP、Windows Server 2003 中一個未公開報告的弱點。其他 Windows 版本不受此安全性更新影響。 若應用程式 (例如網頁瀏覽器) 將蓄意製作的資料透過 Windows Shell 處理常式傳遞至 ShellExecute API 函式，則該弱點可能允許遠端執行程式碼。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-008">MS10-008</a></td>
<td style="border:1px solid black;"><strong>ActiveX Kill Bit (刪除位元) 的積存安全性更新 (978262)</strong><br />
<br />
此安全性更新可解決一項未公開報告的 Microsoft 軟體弱點。 對於所有受支援版本的 Microsoft Windows 2000 和 Windows XP，此安全性更新的等級為「重大」；對於所有受支援版本的 Windows Vista 和 Windows 7，此安全性更新的等級為「重要」；對於所有受支援版本的 Windows Server 2003，此安全性更新的等級為「中度」；對於所有受支援版本的 Windows Server 2008 和 Windows Server 2008 R2，此安全性更新的等級為「低」。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-009">MS10-009</a></td>
<td style="border:1px solid black;"><strong>Windows TCP/IP 中的弱點可能會允許遠端執行程式碼 (974145)</strong><br />
<br />
這個安全性更新可解決 Microsoft Windows 中四項未公開報告的弱點。 如果將蓄意製作的封包傳送到啟用 IPv6 的電腦，則其中最嚴重的弱點可能會允許遠端執行程式碼。 攻擊者可以建立蓄意製作的 ICMPv6 封包，並將封包傳送給啟用 IPv6 的系統，以嘗試利用此弱點。 唯有當攻擊者已連結，才可能利用此弱點。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-013">MS10-013</a></td>
<td style="border:1px solid black;"><strong>Microsoft DirectShow 中的弱點可能會允許遠端執行程式碼 (977935)</strong><br />
<br />
這個安全性更新可解決 Microsoft DirectShow 中一項未公開報告的弱點。 如果使用者開啟蓄意製作的 AVI 檔案，則此弱點可能會允許遠端執行程式碼。 成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-003">MS10-003</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office (MSO) 中的弱點可能會允許遠端執行程式碼 (978214)</strong><br />
<br />
此安全性更新可解決 Microsoft Office 中一項未公開報告的弱點，該弱點可在使用者開啟蓄意製作的 Office 檔案時，允許從遠端執行程式碼。 成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-004">MS10-004</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office PowerPoint 的弱點可能會允許遠端執行程式碼 (975416)</strong><br />
<br />
這個安全性更新可解決 Microsoft Office PowerPoint 中六個未公開報告的弱點。 如果使用者開啟蓄意製作的 PowerPoint 檔案，此弱點可能會允許遠端執行程式碼。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-010">MS10-010</a></td>
<td style="border:1px solid black;"><strong>Windows Server 2008 Hyper-V 中的弱點可能會允許拒絕服務 (977894)</strong><br />
<br />
這個安全性更新能解決 Windows Server 2008 Hyper-V 和 Windows Server 2008 R2 Hyper-V 中一項未公開報告的弱點。 如果經過驗證的使用者在 Hyper-V 伺服器主控的客體虛擬機器上執行一連串格式錯誤的機器指令，這個弱點可能會允許拒絕服務。 攻擊者必須擁有有效的登入認證，並能夠從本機登入客體虛擬機器，才能利用這項弱點。 匿名或遠端使用者無法利用這個弱點。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
拒絕服務</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-011">MS10-011</a></td>
<td style="border:1px solid black;"><strong>Windows Client/Server Run-time Subsystem 中的弱點可能會允許權限提高 (978037)</strong><br />
<br />
此安全性更新解決了 Microsoft Windows Client/Server Run-time Subsystem (CSRSS) 中一個未公開報告的弱點，會影響 Microsoft Windows 2000、Windows XP、Windows Server 2003。其他 Windows 版本不受影響。 如果攻擊者登入系統並執行蓄意製作、可在攻擊者登出後繼續執行的應用程式，這個弱點可能會允許權限提高。 攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這項弱點。 匿名使用者無法利用這個弱點。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-012">MS10-012</a></td>
<td style="border:1px solid black;"><strong>SMB 伺服器中的弱點可能會允許遠端執行程式碼 (971468)</strong><br />
<br />
這個安全性更新可解決 Microsoft Windows 中數個未公開報告的弱點。 如果攻擊者蓄意製作 SMB 封包並將其傳送至受影響的系統，最嚴重的弱點可能會允許遠端執行程式碼。 最佳做法的防火牆和標準預設防火牆設定有助於防止網路受到來自企業外試圖利用這些弱點的攻擊。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-014">MS10-014</a></td>
<td style="border:1px solid black;"><strong>Kerberos 中的弱點可能會允許拒絕服務 (977290)</strong><br />
<br />
這個安全性更新可解決 Microsoft Windows 中一項未公開報告的弱點。 如果受信任的非 Windows Kerberos 領域中經過驗證的使用者傳送蓄意製作的票證更新要求至 Windows Kerberos 網域，這個弱點可能會允許拒絕服務。 拒絕服務可能會持續到網域控制站重新啟動為止。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
拒絕服務</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-015">MS10-015</a></td>
<td style="border:1px solid black;"><strong>Windows 核心中的弱點可能會允許權限提高 (977165)</strong><br />
<br />
這個安全性更新可解決 Microsoft Windows 中一項公開揭露和一項未公開報告的弱點。 如果攻擊者登入系統，並執行蓄意製作的應用程式，則這些弱點可能會允許權限提高。 如果要利用前述任一弱點，攻擊者必須擁有有效的登入認證，並且能夠在本機登入。 遠端或匿名使用者無法利用這個弱點。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-005">MS10-005</a></td>
<td style="border:1px solid black;"><strong>Microsoft Silverlight 中的弱點可能會允許遠端執行程式碼 (978706)</strong><br />
<br />
這個安全性更新可解決 Microsoft 小畫家中一項未公開報告的弱點。 如果使用者使用 Microsoft 小畫家檢視蓄意製作的 JPEG 影像檔，這個弱點可能會允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">中度</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
弱點索引  
--------
  
<span></span>
下表提供本月所述每個弱點的利用性評估。 弱點根據遞減的弱點評估等級及 CVE 編號依序列出。
  
**我該如何使用這個表格？**
  
請用這個表格來瞭解您可能需要安裝的每個安全性更新，與 30 天內已發行的可利用程式碼受影響之可能性。 您應該檢閱下列的每個評估，按照特定的設定，將部署以優先次序排序。 如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 弱點索引](https://technet.microsoft.com/en-us/security/cc998259.aspx)。
  
| 公告編號                                                            | 弱點標題                                                      | CVE ID                                                                           | 弱點索引評估                                                                                            | 主要重點                                           |  
|---------------------------------------------------------------------|---------------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|----------------------------------------------------|  
| [MS10-006](https://technet.microsoft.com/security/bulletin/ms10-006) | SMB 用戶端競爭狀況弱點                                        | [CVE-2010-0017](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0017) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | 遠端攻擊模式可能造成 DoS；本機攻擊模式可能造成 EoP |  
| [MS10-011](https://technet.microsoft.com/security/bulletin/ms10-011) | CSRSS 本機權限提高弱點                                        | [CVE-2010-0023](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0023) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | 攻擊者和受害者必須登入相同的主控台                 |  
| [MS10-007](https://technet.microsoft.com/security/bulletin/ms10-007) | URL 驗證弱點                                                  | [CVE-2010-0027](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0027) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                               |  
| [MS10-004](https://technet.microsoft.com/security/bulletin/ms10-004) | PowerPoint LinkedSlideAtom 堆積溢位弱點                       | [CVE-2010-0030](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0030) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                               |  
| [MS10-004](https://technet.microsoft.com/security/bulletin/ms10-004) | PowerPoint OEPlaceholderAtom 'placementId' 無效的陣列索引弱點 | [CVE-2010-0031](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0031) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                               |  
| [MS10-004](https://technet.microsoft.com/security/bulletin/ms10-004) | PowerPoint OEPlaceholder Atom 釋放後使用弱點                  | [CVE-2010-0032](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0032) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                               |  
| [MS10-004](https://technet.microsoft.com/security/bulletin/ms10-004) | PowerPoint Viewer TextBytesAtom 記錄堆疊溢位弱點              | [CVE-2010-0033](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0033) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | 弱點只會影響 PowerPoint Viewer 2003                |  
| [MS10-004](https://technet.microsoft.com/security/bulletin/ms10-004) | Office PowerPoint Viewer TextCharsAtom 記錄堆疊溢位弱點       | [CVE-2010-0034](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0034) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | 弱點只會影響 PowerPoint Viewer 2003                |  
| [MS10-012](https://technet.microsoft.com/security/bulletin/ms10-012) | SMB NTLM 驗證缺乏 Entropy 弱點                                | [CVE-2010-0231](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0231) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                               |  
| [MS10-015](https://technet.microsoft.com/security/bulletin/ms10-015) | Windows 核心例外處理常式弱點                                  | [CVE-2010-0232](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0232) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                               |  
| [MS10-003](https://technet.microsoft.com/security/bulletin/ms10-003) | MSO.DLL 緩衝區溢位弱點                                        | [CVE-2010-0243](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0243) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                               |  
| [MS10-013](https://technet.microsoft.com/security/bulletin/ms10-013) | DirectShow 堆積溢位弱點                                       | [CVE-2010-0250](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0250) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | (無)                                               |  
| [MS10-006](https://technet.microsoft.com/security/bulletin/ms10-006) | SMB 用戶端集區損毀弱點                                        | [CVE-2010-0016](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0016) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                               |  
| [MS10-012](https://technet.microsoft.com/security/bulletin/ms10-012) | SMB 路徑名稱溢位弱點                                          | [CVE-2010-0020](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0020) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                               |  
| [MS10-012](https://technet.microsoft.com/security/bulletin/ms10-012) | SMB 憶體損毀弱點                                              | [CVE-2010-0021](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0021) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                               |  
| [MS10-005](https://technet.microsoft.com/security/bulletin/ms10-005) | MS 小畫家整數溢位弱點                                         | [CVE-2010-0028](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0028) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | 需相當程度的使用者互動才能成功利用弱點             |  
| [MS10-004](https://technet.microsoft.com/security/bulletin/ms10-004) | PowerPoint 檔案路徑處理緩衝區溢位弱點                         | [CVE-2010-0029](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0029) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                               |  
| [MS10-015](https://technet.microsoft.com/security/bulletin/ms10-015) | Windows 核心重覆釋放相同記憶體空間弱點                        | [CVE-2010-0233](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0233) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | (無)                                               |  
| [MS10-009](https://technet.microsoft.com/security/bulletin/ms10-009) | ICMPv6 路由器通告弱點                                         | [CVE-2010-0239](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0239) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | 需攻擊者連結至目標主機才能利用弱點攻擊             |  
| [MS10-009](https://technet.microsoft.com/security/bulletin/ms10-009) | 標頭 MDL 片段弱點                                             | [CVE-2010-0240](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0240) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | 弱點需要協力廠商網路驅動程式                       |  
| [MS10-009](https://technet.microsoft.com/security/bulletin/ms10-009) | ICMPv6 路由資訊弱點                                           | [CVE-2010-0241](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0241) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能撰寫出偶爾可利用此漏洞的程式碼 | 需攻擊者連結至目標主機才能利用弱點攻擊             |  
| [MS10-012](https://technet.microsoft.com/security/bulletin/ms10-012) | SMB Null 指標弱點                                             | [CVE-2010-0022](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0022) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | (無)                                               |  
| [MS10-010](https://technet.microsoft.com/security/bulletin/ms10-010) | Hyper-V 指示設定驗證弱點                                      | [CVE-2010-0026](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0026) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 弱點可能造成只有 DoS 的狀況                        |  
| [MS10-014](https://technet.microsoft.com/security/bulletin/ms10-014) | Kerberos Null 指標解除參照弱點                                | [CVE-2010-0035](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0035) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | 只有 DoS；只有非預設設定的網域控制站上才可能利用   |  
| [MS10-009](https://technet.microsoft.com/security/bulletin/ms10-009) | TCP/IP 選擇性認可弱點                                         | [CVE-2010-0242](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0242) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能撰寫出可利用此漏洞的程式碼 | (無)                                               |
  
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
<th colspan="12">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-006**](https://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](https://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](https://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**MS10-009**](https://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](https://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](https://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](https://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](https://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](https://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](https://technet.microsoft.com/security/bulletin/ms10-015)
</td>
<td style="border:1px solid black;">
[**MS10-005**](https://technet.microsoft.com/security/bulletin/ms10-005)
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
無
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
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
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=80b49bab-6c2f-48a8-a901-ca3f76e4fe6b)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=92234237-a8eb-4ce4-bc5e-cd86feb7dbd3)  
(重大)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=543dc6a7-fa76-4ba9-81e4-25fdf2013548)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[AVI 篩選器](https://www.microsoft.com/download/details.aspx?familyid=ba110440-10ce-40a0-884a-8b9afd45a3e3)  
(KB977914)  
(重大)  
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=16787c93-2c95-4c13-8492-be1db9d18146)  
(KB975560)  
(重大)  
[DirectX 9.0 的 Quartz](https://www.microsoft.com/download/details.aspx?familyid=59a8bc19-02bb-4800-bac1-464f59e1cb7b)<sup>[1]</sup>
(KB975560)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=456185b5-57d1-4fa5-a4a9-5b2006ede3ad)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=267ce982-54a0-418f-ad52-e4963610f714)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=56a9afba-a6ee-4fb9-ba85-e51d9f94de27)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=ed8ac6a5-c8bb-4ed4-8994-810e9a1863c3)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=e5861705-8f49-45cb-8a92-cf052ccf4134)  
(中度)
</td>
</tr>
<tr>
<th colspan="12">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-006**](https://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](https://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](https://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**MS10-009**](https://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](https://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](https://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](https://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](https://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](https://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](https://technet.microsoft.com/security/bulletin/ms10-015)
</td>
<td style="border:1px solid black;">
[**MS10-005**](https://technet.microsoft.com/security/bulletin/ms10-005)
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
無
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
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
<td style="border:1px solid black;">
[**中度**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 及 Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 與 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=f6c4472e-385c-4412-bda9-c2e615e50713)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 與 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=b8e7bf17-a037-4200-9ae2-2280b19766a4)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 與 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=7bcf3945-0552-478e-b7f3-bbca97dd1b5d)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[AVI 篩選器](https://www.microsoft.com/download/details.aspx?familyid=a9beb2bd-e5f6-43f9-bbcc-a2afee5e5ceb)  
(KB977914)  
(重大)  
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=7ab53be3-3f42-4e61-a2bc-3ed41d8736ff)  
(KB975560)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 與 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=b9234b40-1b1c-498b-90d4-0bff347b36ee)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 與 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=8f7adee3-e68e-41b3-b835-d84691774f31)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 與 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=e2b348f5-ec8d-4782-bb03-5de550adea77)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 與 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=b2e70df6-7728-4fc3-8df7-8ddb9ba5202f)  
(中度)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=63e15ff0-73b3-46c9-96f8-c18977d35a10)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b8d83f30-9cd7-4d6b-b2b9-65d0a483cb9c)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=25ef97e8-e76e-44c2-953c-f94cbac552cf)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[AVI 篩選器](https://www.microsoft.com/download/details.aspx?familyid=dedc3010-a989-45f7-b9d4-f7079db3e572)  
(KB977914)  
(重大)  
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=7543e819-cd36-4e89-9850-60f00c50999d)  
(KB975560)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1f83bf7a-e16c-404a-89bd-f65843938299)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=91ee57f2-81e5-49bd-bdfc-d3e385efc8a5)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e534d00c-6ddc-4eb3-9464-5db6e90afa3e)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f8c4acc8-c2f4-41f7-9b32-e7bd791e0155)  
(中度)
</td>
</tr>
<tr>
<th colspan="12">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-006**](https://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](https://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](https://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**MS10-009**](https://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](https://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](https://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](https://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](https://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](https://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](https://technet.microsoft.com/security/bulletin/ms10-015)
</td>
<td style="border:1px solid black;">
[**MS10-005**](https://technet.microsoft.com/security/bulletin/ms10-005)
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
無
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
無
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
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=feb8c145-7c30-45fa-a6f0-8b6453ddd521)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5cb2e203-18fb-4887-a1c9-289d86b8ba11)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=29ff72f7-1663-4f35-a794-2dfe3c17b39c)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[AVI 篩選器](https://www.microsoft.com/download/details.aspx?familyid=cc5150d7-070e-4a87-9c02-d050a8cb2204)  
(KB977914)  
(重大)  
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=983c5484-6321-4765-97ec-8d42d42d1f70)  
(KB975560)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2c8c4eec-255e-41d5-b1e6-f0204edcb46f)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3d18cbc4-ac48-458c-8aa3-90708fd854ff)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=738e2fda-96fc-413d-a5c7-74b1fac1d6b3)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=defd8603-ed9b-42f9-a539-2b6a690e9575)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c1efbe73-fc87-4e6a-8b36-81f125a27aec)  
(中度)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=36d88c1b-814c-4371-9ed2-d4576f419fc3)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=90360537-9311-45e2-8047-9a971f90c3c3)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d4a97bb7-4f74-4884-9a6e-7a4df9c540fb)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[AVI 篩選器](https://www.microsoft.com/download/details.aspx?familyid=db13e99b-2f2a-4474-8d6e-271b025bd07f)  
(KB977914)  
(重大)  
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=7dc20252-6091-407b-befc-c25e8f5d3fb0)  
(KB975560)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=de0186f6-27a2-4226-b8eb-f2912710f072)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7d63c95e-311a-446f-8852-dffd217a89f6)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f8ad539d-8191-4864-977b-ad4e31c04ba0)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9873c962-9d3d-46ef-b54b-2a50696fb6b2)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9143e435-f0d6-464b-9273-4d1f38f8ff3a)  
(中度)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=622442b0-cffe-4fc2-94a8-edff9d71ecd3)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=d695ca9f-a1db-4c0f-94b6-7112861c28da)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=b84f0be4-6d11-4b07-bb3c-2c76ae9ceea8)  
(中度)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[AVI 篩選器](https://www.microsoft.com/download/details.aspx?familyid=aec66173-e2c6-4c39-8d60-8fbef6d7b764)  
(KB977914)  
(重要)  
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=b1a7533a-913f-4054-b579-489a257bae5f)  
(KB975560)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=87732f7a-9339-43bc-a4e8-3da849f35b70)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=ee7f8cc4-f7fd-4dc7-808c-436204ee80cb)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=d549c927-add7-4d83-bfc7-15dc35663dfb)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=c3c21225-8534-4c7f-96b6-20a743dcea74)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](https://www.microsoft.com/download/details.aspx?familyid=ee603435-26af-4ab9-9f22-92734346dc0a)  
(中度)
</td>
</tr>
<tr>
<th colspan="12">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-006**](https://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](https://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](https://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**MS10-009**](https://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](https://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](https://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](https://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](https://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](https://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](https://technet.microsoft.com/security/bulletin/ms10-015)
</td>
<td style="border:1px solid black;">
[**MS10-005**](https://technet.microsoft.com/security/bulletin/ms10-005)
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
無
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
<td style="border:1px solid black;">
無
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
<td style="border:1px solid black;">
無
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1902fc93-0f4b-4261-9da3-17d1931daf2e)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2c897ddd-f441-41d4-b5b4-d794cfc96e6b)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=71f03946-622c-4403-b94f-f6a3de18a8c3)  
(重大)
</td>
<td style="border:1px solid black;">
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=7130ce0f-df38-4c96-ac54-cdbff35f03e7)  
(KB975560)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=16494dac-553a-4de9-b751-0d6b51cb43f0)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2761c7b4-d472-4f00-949b-af3ebafdc08d)  
(重要)
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
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7c2f89b5-a3b3-42cd-857d-923fe8b8f1da)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f349f7aa-d020-4e0d-a35f-518a63ec92df)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=519815fd-707d-476f-9e29-7b03b7a17af5)  
(重大)
</td>
<td style="border:1px solid black;">
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=de7b7c8f-bd0a-4e13-bd58-d95507a6274b)  
(KB975560)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=cec582b3-e37f-448e-a5c3-6abdcee9e57c)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=38b40dab-6b4d-434b-9997-12ef70d6bbcc)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="12">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-006**](https://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](https://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](https://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**MS10-009**](https://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](https://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](https://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](https://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](https://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](https://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](https://technet.microsoft.com/security/bulletin/ms10-015)
</td>
<td style="border:1px solid black;">
[**MS10-005**](https://technet.microsoft.com/security/bulletin/ms10-005)
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
無
</td>
<td style="border:1px solid black;">
[**輕微**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
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
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
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
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=09e19263-18ba-495e-bcf7-719e957204a7)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9a85b1bf-7427-47d0-9e1b-21dbe824a62c)\*\*  
(輕微)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=bc451228-3de4-427c-b42f-91f204c708b8)\*  
(重大)
</td>
<td style="border:1px solid black;">
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=5ac0a948-0bdc-4c10-9b88-16a5d7092e47)\*\*  
(KB975560)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=597b2310-2cd8-4d0f-8248-781eb8b7450a)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=75327470-0f14-4cdd-bcb7-64684c61c267)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=21e87558-9bd2-4aa9-aaa5-7fd26a5b60e6)\*  
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
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=180c2313-5e3e-4d84-87cd-64048f51e0f6)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=fde218c3-90ab-4664-852d-25ca55835054)\*\*  
(輕微)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3a889152-5d7c-4a3e-b4f1-c6507b739ca0)\*  
(重大)
</td>
<td style="border:1px solid black;">
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=362fea40-649b-4471-aad7-db29edd0ac10)\*\*  
(KB975560)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3463a63c-e88a-4036-ab60-f84d4bf4191a)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=67119fb6-e517-46f4-ab0b-2351cdc3d670)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7d0f8f81-fc10-450a-a653-06f89acba9fa)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0b93047d-f2c6-403b-9200-c251898bc1e0)\*  
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
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=614eaf7e-95aa-4f8f-910c-1980e1f14d11)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5b6e9451-df38-4626-bb1d-4fc160d7a40e)  
(輕微)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1cd1882b-8e55-47ea-a82a-68bb59a500a7)  
(重大)
</td>
<td style="border:1px solid black;">
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=effa638b-cfc1-4777-8219-7b433ed5e717)  
(KB975560)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f90fc0c8-babe-4224-be07-614ea7ddf102)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=cd6b234b-8e96-4128-a77a-645a0882996a)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
</tr>
<tr>
<th colspan="12">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-006**](https://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](https://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](https://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**MS10-009**](https://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](https://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](https://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](https://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](https://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](https://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](https://technet.microsoft.com/security/bulletin/ms10-015)
</td>
<td style="border:1px solid black;">
[**MS10-005**](https://technet.microsoft.com/security/bulletin/ms10-005)
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
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
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
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=a589431a-93dc-42cd-a74e-d9c1e3452fef)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=ec6d996f-dffa-45ad-9467-e96a4ac63e5f)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=4ec49aa2-81df-4e65-80da-6201394c4089)  
(KB975560)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=122fc003-0651-4ad2-a5c8-a21536defad8)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=66f14bb4-40fc-4ae3-9baf-429b7106cd91)  
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
[適用於 x64 型系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=3c1edcf8-d304-45c4-9818-1cd86383b3fe)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=b3265576-04c1-48b1-8ce9-128843c58cf5)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=a8a2519c-3b89-4987-9473-920adafc78cb)  
(KB975560)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7](https://www.microsoft.com/download/details.aspx?familyid=3e096468-db6c-45c6-bee5-eaeaa63500b5)  
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
<th colspan="12">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-006**](https://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](https://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](https://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**MS10-009**](https://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](https://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](https://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](https://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](https://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](https://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](https://technet.microsoft.com/security/bulletin/ms10-015)
</td>
<td style="border:1px solid black;">
[**MS10-005**](https://technet.microsoft.com/security/bulletin/ms10-005)
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
[**輕微**](https://technet.microsoft.com/security/bulletin/rating)
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
無
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
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
[適用於 x64 型系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=ecb06350-47a7-48eb-825f-3e8f89c5ca8e)\*  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?familyid=cda31c54-8b81-4185-a623-64480ad4b73c)\*\*  
(輕微)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=a9811baa-1500-4c73-940b-57f8c5456891)\*\*  
(KB975560)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=3214b347-d901-4aac-85ce-676e4602de87)\*  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=dc757b6d-f0f8-4e71-ab6f-1417233eedf9)\*  
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
適用於 Itanium 型系統的 Windows Server 2008 R2
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?familyid=badd6cab-7738-4401-a68c-c15414388601)  
(重大)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?familyid=43fa4e26-160f-4aa3-a03d-b98a79666a18)  
(輕微)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=2ed23bf5-6217-413c-a7ba-eccc82139d68)  
(KB975560)  
(重要)
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 系統的 Windows Server 2008 R2](https://www.microsoft.com/download/details.aspx?familyid=d5b0b1eb-24f3-47ec-aba1-c1b95400189e)  
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
</table>
 
**MS10-013 注意事項**

<sup>[1]</sup>DirectX 9.0 的更新也適用於 Microsoft Windows 2000 上的 DirectX 9.0a、DirectX 9.0b 及 DirectX 9.0c。

**Windows Server 2008 和 Windows Server 2008 R2 注意事項**

**\*會影響 Server Core 安裝。** 無論上述受支援的 Windows Server 2008 或 Windows Server 2008 R2 版本是否使用 Server Core 安裝選項安裝，這個更新均以相同的嚴重性等級套用。 如需此安裝選項的詳細資訊，請參閱 MSDN 文章：[伺服器核心](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英文) 以及[適用於 Windows Server 2008 R2 的伺服器核心](https://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 及 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](https://www.microsoft.com/taiwan/windowsserver2008/prodinfo/compare-core-installation.aspx) 。

**\*\*Server Core 安裝不受影響。** 如果 Windows Server 2008 或 Windows Server 2008 R2 是使用 Server Core 安裝選項所安裝，則這項更新解決的弱點並不會影響受支援的 Windows Server 2008 或 Windows Server 2008 R2。 如需此安裝選項的詳細資訊，請參閱 MSDN 文章：[伺服器核心](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英文) 以及[適用於 Windows Server 2008 R2 的伺服器核心](https://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx) (英文)。請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 及 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](https://www.microsoft.com/taiwan/windowsserver2008/prodinfo/compare-core-installation.aspx) 。

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
[**MS10-003**](https://technet.microsoft.com/security/bulletin/ms10-003)
</td>
<td style="border:1px solid black;">
[**MS10-004**](https://technet.microsoft.com/security/bulletin/ms10-004)
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
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=47553f45-fa10-40e5-8267-9d42ff560a62)  
(KB977896)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=cfc697b4-2ceb-4030-86c5-be9bc8bfd07c)  
(KB973143)  
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
[Microsoft Office PowerPoint 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=2291ae24-fa39-4ad8-a7d0-12726b68ad96)  
(KB976881)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office for Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS10-003**](https://technet.microsoft.com/security/bulletin/ms10-003)
</td>
<td style="border:1px solid black;">
[**MS10-004**](https://technet.microsoft.com/security/bulletin/ms10-004)
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
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=7c985595-00c5-44b8-81c3-59d9967220f8)<sup>[1]</sup>
(KB979674)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=7c985595-00c5-44b8-81c3-59d9967220f8)<sup>[1]</sup>
(KB979674)  
(重要)
</td>
</tr>
</table>
 
**Microsoft Office for Mac 注意事項**

<sup>[1]</sup>基於 Mac Microsoft Office 2004 的累計服務模型，這些更新是相同的。

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和安全性更新。 如需更多資訊，請參閱 [TechNet 更新管理中心](https://technet.microsoft.com/zh-tw/updatemanagement/default.aspx) 。 [TechNet Security Center](https://go.microsoft.com/fwlink/?linkid=21171) 提供 Microsoft 產品安全性的其他資訊。 消費者可以造訪[在家上網的安全性](https://go.microsoft.com/fwlink/?linkid=85102)網站，只要按一下 \[最新安全性更新\] 即可在此網站取得此資訊。

安全性更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 以及 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 取得。 安全性更新也可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得。 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。

最後，您可以從 [Microsoft Update Catalog](https://go.microsoft.com/fwlink/?linkid=96155) 下載安全性更新。 Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括安全性更新、驅動程式和 Service Pack。 只要以安全性公告編號 (例如：MS07-036) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。 如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](https://go.microsoft.com/fwlink/?linkid=97900)。

**注意**：自 2009 年 8 月 1 日開始，Microsoft 已停止支援 Office Update 與 Office Update Inventory Tool。 若要繼續取得 Microsoft Office 產品的最新更新，請使用 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)。 如需更多資訊，請參閱[關於 Microsoft Office Update： 常見問題集](https://office.microsoft.com/en-us/downloads/fx010402221033.aspx) (英文)。

**偵測與部署指南**

Microsoft 針對安全性更新提供偵測和部署指南。 本指南所含之建議和資訊，能幫助 IT 專業人員瞭解如何使用用於安全性更新的偵測和部署的各種工具。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 961747](https://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少安全性更新以及一般安全性設定錯誤的狀況。 如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134) 網站 (英文)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速而可靠地將 Microsoft Windows 2000 作業系統及更新版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 適用的最新重大更新與安全性更新部署到 Microsoft Windows 2000 及更新版本的作業系統中。

如需更多關於利用 Windows Server Update Services 部署安全性更新的資訊，請造訪 [Windows Server Update Services](https://www.microsoft.com/taiwan/windowsserversystem/updateservices/evaluation/overview.mspx) 網站。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。 現已推出新版的 SMS，System Center Configuration Manager 2007；另請參閱 [System Center Configuration Manager 2007](https://technet.microsoft.com/en-us/library/bb735860.aspx)。如需更多有關系統管理員如何能使用 SMS 2003 部署安全性更新的資訊，請參閱 [SMS 2003 安全性修補程式管理](https://go.microsoft.com/fwlink/?linkid=22939) (英文)。 SMS 2.0 使用者也可以使用安全性更新盤點工具 (Security Update Inventory Tool，SUIT) 來協助部署安全性更新。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server](https://www.microsoft.com/taiwan/smserver/)。

**注意**：SMS 使用 Microsoft Baseline Security Analyzer 提供廣泛的安全性公告更新偵測與部署支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](https://go.microsoft.com/fwlink/?linkid=33341)。 某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可使用 Elevated Rights Deployment Tool (隨 [SMS 2.0 Administration Feature Pack (英文)](https://go.microsoft.com/fwlink/?linkid=21161) 提供) 來安裝這些更新。

**Update Compatibility Evaluator 和應用程式相容性工具組**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。 這可能會觸發不相容性，而拉長部署安全性更新的時間。 您可以使用 [Application Compatibility Toolkit](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 隨附的 [Update Compatibility Evaluator](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 元件，針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Microsoft Windows Vista、Windows Update、Microsoft 安全性更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非安全性、高優先順序更新

如需在 Windows Update 和 Microsoft Update 上發行的非安全性更新之相關資訊，請參閱：

-   [Microsoft 知識庫文件編號 894199](https://support.microsoft.com/kb/894199)： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。 其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](https://technet.microsoft.com/en-us/wsus/bb456965.aspx)。 顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的安全性保護，Microsoft 將在每月發行安全性更新之前，提前向重要安全性軟體提供者提供弱點資訊。 安全性軟體提供者可利用此弱點資訊，透過其安全性軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。 如果要判斷是否有安全性軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](https://www.microsoft.com/security/msrc/mapp/partners.mspx)上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 安全性策略與社群

**更新程式管理策略**

[更新管理安全性指南](https://technet.microsoft.com/zh-tw/library/bb466251(en-us).aspx) (英文) 提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](https://support.microsoft.com/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](https://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](https://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 [Core Security Technologies](https://www.coresecurity.com/) 的 Damian Frizza 回報 MS10-003 中描述的問題
-   感謝 [Secunia](https://secunia.com/) 的 Carsten Eiram 回報 MS10-004 中描述的問題
-   感謝 [VeriSign iDefense Labs](https://labs.idefense.com/) 的 Sean Larsson 回報 MS10-004 中描述的三個問題
-   感謝 SkD 與 與 [TippingPoint](https://www.tippingpoint.com/) 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作，回報 MS10-004 中描述的問題
-   感謝 [TippingPoint DVLabs](https://dvlabs.tippingpoint.com/) 的 Cody Pierce 回報 MS10-004 中描述的問題
-   感謝 ICST-ERCIS (中國北京大學計算機科學技術研究所信息安全工程研究中心) 的 Tielei Wang 與 [Secunia](https://secunia.com/) 合作，共同回報 MS10-005 中描述的問題
-   感謝 [stratsec](https://www.stratsec.net/) 的 Laurent Gaffié 回報 MS10-006 中描述的兩個問題
-   感謝 Brett Moore 與 [TippingPoint](https://www.tippingpoint.com/) 及 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 MS10-007 中描述的問題
-   感謝 [Lostmon Lord](https://lostmon.blogspot.com/) 回報 MS10-007 中描述的問題
-   感謝 [NGS Software](https://www.ngssoftware.com/) 的 Shaun Colley 回報 MS10-008 中描述的問題
-   感謝 [Google Security Team](https://www.google.com/) 的 Sumit Gwalani、Drew Hintz 和 Neel Mehta 回報 MS10-009 中描述的三個問題
-   感謝 Jan Bottorff 回報 MS10-010 中描述的問題
-   感謝 [Hispasec](https://www.hispasec.com/) 的 Matthew 'j00ru' Jurczyk 和 Gynvael Coldwind 回報 MS10-011 中描述的問題
-   感謝 [Codenomicon](https://www.codenomicon.com/) 的 Joshua Morin 回報 MS10-012 中描述的問題
-   感謝 [BSI](https://www.bsi.bund.de/) 的 Florian Rienhardt 回報 MS10-012 中描述的問題
-   感謝 Hernan Ochoa 回報 MS10-012 中描述的問題
-   感謝 [TippingPoint](https://www.tippingpoint.com/) 和 [Zero Day Initiative](https://www.zerodayinitiative.com/) 回報 MS10-013 中描述的問題
-   感謝 [Google Inc.](https://www.google.com/) 的 Tavis Ormandy 回報 MS10-015 中描述的問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可洽詢[安全性支援](https://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 以取得技術支援。 與安全性更新有關的支援電話不另外收費。 如需更多可用支援選項的資訊，請參閱 [Microsoft 技術支援服務](https://support.microsoft.com/?ln=zh-tw/)。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與安全性更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](https://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2010 年 2 月 10 日)： 公告摘要發行。

*Built at 2014-04-18T01:50:00Z-07:00*
