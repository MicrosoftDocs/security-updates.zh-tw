---
TOCTitle: 'MS08-FEB'
Title: 2008 年 2 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms08-feb'
ms:contentKeyID: 61237680
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms08-feb(v=Security.10)'
---

2008 年 2 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2008年2月13日

**版本:** 1.0

此公告摘要列出 2008 年 2 月份發行之安全性公告。

發行 2008 年 2 月份公告之後，此公告摘要將取代原先於 2008 年 2 月 7 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 安全性公告預先通知](https://technet.microsoft.com/security/bulletin/advance)。

如需有關如何在 Microsoft 安全性公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2008 年 2 月 13 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。 立即註冊參加 [2 月份安全性公告網路廣播](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357215&eventcategory=4&culture=en-us&countrycode=us)。 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 安全性公告摘要和網路廣播](https://www.microsoft.com/taiwan/security/bulletins/default.mspx)。

Microsoft 也會提供資訊協助客戶排定每月安全性更新以及任何非安全性、高優先順序更新的優先順序，其中這些非安全性、高優先順序更新的發行日期與每月安全性更新的發行日期相同。 請參閱＜其他資訊＞一節。

### 公告資訊

#### 提要

本月份安全性公告依嚴重性列出如下：

重大 (6)
--------

<span></span>
| 公告編號             | Microsoft 安全性公告 MS08-007                                                                                                                                                                                      |
|----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**WebDAV 迷你重新導向程式中的弱點可能會允許遠端執行程式碼 (946026)**](https://technet.microsoft.com/security/bulletin/ms08-007)                                                                                    |
| **提要**             | 這個重大安全性更新可解決 WebDAV Mini-Redirector 中一項未公開報告的弱點。 成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 |
| **最高的嚴重性等級** | [重大](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                      |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                     |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新需要重新啟動電腦。                                                                                                                 |
| **受影響的軟體**     | **Windows。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                 |

| 公告編號             | Microsoft 安全性公告 MS08-008                                                                                                                                                                                                                           |
|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**OLE Automation 中的弱點可能會允許遠端執行程式碼 (947890)**](https://technet.microsoft.com/security/bulletin/ms08-008)                                                                                                                                 |
| **提要**             | 這個重大安全性更新可解決一項未公開報告的弱點。 如果使用者檢視蓄意製作的網頁，此弱點可能會允許遠端執行程式碼。 可透過攻擊物件連結與嵌入 (OLE) Automation 來利用此弱點。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重大](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                           |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                          |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新需要重新啟動電腦。                                                                                                                                                      |
| **受影響的軟體**     | **Windows、Office、Visual Basic。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                |

| 公告編號             | Microsoft 安全性公告 MS08-009                                                                                                                                                                                                                                                                                                                                   |
|----------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**VBScript 與 JScript 指令碼引擎中的弱點可能會允許遠端執行程式碼 (944338)**](https://technet.microsoft.com/security/bulletin/ms08-009)                                                                                                                                                                                                                          |
| **提要**             | 這個重大的安全性更新可解決 Microsoft Word 中一項未公開報告的弱點，該弱點可在使用者開啟蓄意製作的 Word 檔案時，允許從遠端執行程式碼。 成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重大](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                   |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                  |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新不需要重新啟動電腦。                                                                                                                                                                                                                                                            |
| **受影響的軟體**     | **Office。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                               |

| 公告編號             | Microsoft 安全性公告 MS08-010                                                                                                                                                                                                                                   |
|----------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Internet Explorer 積存安全性更新 (944533)**](https://technet.microsoft.com/security/bulletin/ms08-010)                                                                                                                                                        |
| **提要**             | 這個重大安全性更新可解決三項未公開報告的弱點，以及一項已公開報告的弱點。 如果使用者以 Internet Explorer 檢視蓄意製作的網頁，則對弱點造成的最嚴重影響可能會允許遠端執行程式碼。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重大](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                   |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                  |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新需要重新啟動電腦。                                                                                                                                                              |
| **受影響的軟體**     | **Windows、Internet Explorer。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                           |

| 公告編號             | Microsoft 安全性公告 MS08-012                                                                                                                                                                                                                                                                                                                                                      |
|----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Microsoft Office Publisher 中的弱點可能會允許遠端執行程式碼 (947085)**](https://technet.microsoft.com/security/bulletin/ms08-012)                                                                                                                                                                                                                                                |
| **提要**             | 這個重大的安全性更新可解決 Microsoft Office Publisher 中兩項未公開報告的弱點，該弱點可在使用者開啟蓄意製作的 Publisher 檔案時，允許從遠端執行程式碼。 成功利用這類弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重大](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                      |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                                     |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新不需要重新啟動電腦。                                                                                                                                                                                                                                                                               |
| **受影響的軟體**     | **Office。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                                                  |

| 公告編號             | Microsoft 安全性公告 MS08-013                                                                                                                                                                                                                                                                                                                                                                                      |
|----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Microsoft Office 中的弱點可能會允許遠端執行程式碼 (947108)**](https://technet.microsoft.com/security/bulletin/ms08-013)                                                                                                                                                                                                                                                                                          |
| **提要**             | 這個重大安全性更新可解決 Microsoft Office 中一項未公開報告的弱點。 如果使用者開啟蓄意製作、其中含有插入文件中之格式錯誤物件的 Microsoft Office 檔案，此弱點可能會允許從遠端執行程式碼。 成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重大](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                      |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                                                                     |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新不需要重新啟動電腦。                                                                                                                                                                                                                                                                                                               |
| **受影響的軟體**     | **Office。** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                                                                                  |

重要 (5)
--------

<span></span>
| 公告編號             | Microsoft 安全性公告 MS08-003                                                                                                                                                                                                                                                                                                                                                                                                      |
|----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Active Directory 中的弱點可能會允許拒絕服務 (946538)**](https://technet.microsoft.com/security/bulletin/ms08-003)                                                                                                                                                                                                                                                                                                                |
| **提要**             | 這個重要安全性更新可解決在 Microsoft Windows 2000 Server 及 Windows Server 2003 與 Active Directory 應用程式模式 (ADAM) (安裝於 Windows XP Professional 及 Windows Server 2003) 上實作 Active Directory 的一項未公開報告的弱點，此弱點可能會發生拒絕服務的情況。 在 Windows Server 2003 及 Windows XP Professional 上，攻擊者必須擁有有效的登入認證，才能利用這項弱點。 成功利用此弱點的攻擊者可使該系統停止回應，或自動重新啟動。 |
| **最高的嚴重性等級** | [重要](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                      |
| **弱點的影響**       | 拒絕服務                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新需要重新啟動電腦。                                                                                                                                                                                                                                                                                                                                 |
| **受影響的軟體**     | **Windows、Active Directory、ADAM。 **如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                                                                         |

| 公告編號             | Microsoft 安全性公告 MS08-004                                                                                                                         |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Windows TCP/IP 中的弱點可能會允許拒絕服務 (946456)**](https://technet.microsoft.com/security/bulletin/ms08-004)                                     |
| **提要**             | 此重要更新可解決傳輸控制通訊協定暨網際網路通訊協定 (TCP/IP) 處理中一項未公開報告的弱點。 成功利用此弱點的攻擊者將使受影響系統停止回應並自動重新啟動。 |
| **最高的嚴重性等級** | [重要](https://technet.microsoft.com/security/bulletin/rating)                                                                                         |
| **弱點的影響**       | 拒絕服務                                                                                                                                              |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新需要重新啟動電腦。                                                    |
| **受影響的軟體**     | **Windows。 **如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                    |

| 公告編號             | Microsoft 安全性公告 MS08-005                                                                                                                                                                                                                                                                  |
|----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Internet Information Services 中的弱點可能會允許權限提高 (942831)**](https://technet.microsoft.com/security/bulletin/ms08-005)                                                                                                                                                               |
| **提要**             | 此重要更新能解決 Internet Information Services (IIS) 中一項未公開報告的弱點。 成功利用此弱點的本機攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來能在系統上安裝程式；檢視、變更或刪除資料；或建立新帳戶。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。 |
| **最高的嚴重性等級** | [重要](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                  |
| **弱點的影響**       | 權限提高                                                                                                                                                                                                                                                                                       |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新需要重新啟動電腦。                                                                                                                                                                                             |
| **受影響的軟體**     | **Windows、IIS。 **如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                        |

| 公告編號             | Microsoft 安全性公告 MS08-006                                                                                                                                                                                                                                                                                                                                                                                                                           |
|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Internet Information Services 的弱點可能會允許遠端執行程式碼 (942830)**](https://technet.microsoft.com/security/bulletin/ms08-006)                                                                                                                                                                                                                                                                                                                    |
| **提要**             | 此重要更新能解決 Internet Information Services (IIS) 中一項未公開報告的弱點。 IIS 處理 ASP 網頁的輸入時，存在一個遠端執行程式碼弱點。 成功利用這項弱點的攻擊者，接著可能會以與工作者處理序識別 (WPI) 相同的權限，在 IIS 伺服器上執行動作。 WPI 依預設必須以網路服務帳戶權限來加以設定。 以 WPI (使用具備系統管理權限的帳戶) 設定應用程式集區的 IIS 伺服器 (包含 ASP 網頁)，相較於以預設 WPI 設定來設定應用程式集區的 IIS 伺服器，可能會產生較大的影響。 |
| **最高的嚴重性等級** | [重要](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                           |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新不需要重新啟動電腦。                                                                                                                                                                                                                                                                                                                                                    |
| **受影響的軟體**     | **Windows、IIS。 **如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                                                                                                                 |

| 公告編號             | Microsoft 安全性公告 MS08-011                                                                                                                                                                                                                                                                                                                                                         |
|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [**Microsoft Works File Converter 的弱點可能會允許遠端執行程式碼 (947081)**](https://technet.microsoft.com/security/bulletin/ms08-011)                                                                                                                                                                                                                                                 |
| **提要**             | 這個重要安全性更新可解決 Microsoft Works File Converter 中三項未公開報告的弱點。 如果使用者使用受影響版本的 Microsoft Office、Microsoft Works 或 Microsoft Works Suite 開啟蓄意製作的 Works (.wps) 檔案，上述弱點可能會允許遠端執行程式碼。 成功利用此弱點的攻擊者可以取得受影響系統的完整控制權。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 |
| **最高的嚴重性等級** | [中度](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                         |
| **弱點的影響**       | 遠端執行程式碼                                                                                                                                                                                                                                                                                                                                                                        |
| **偵測**             | Microsoft Baseline Security Analyzer 可以偵測您的電腦系統是否需要此更新。 此更新不需要重新啟動電腦。                                                                                                                                                                                                                                                                                  |
| **受影響的軟體**     | **Office、Works、Works Suite。 **如需更多資訊，請參閱＜受影響的軟體及下載位置＞部分。                                                                                                                                                                                                                                                                                                 |

受影響的軟體及下載位置
----------------------

<span></span>
**我該如何使用這個表格？**

請用這個表格來瞭解可能需要安裝的安全性更新有哪些。 您應該查看此處列出的每一種軟體程式或元件，看看是否有需要的安全性更新。 在列出的軟體程式或元件旁邊，會附註弱點的影響等級，同時也會列出可用軟體更新的超連結。

**注意**：一項弱點，可能需要安裝數個安全性更新才能妥善解決。 請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。

**受影響的軟體及下載位置**

#### 適用於公告 MS08-003 至 MS08-008 的受影響軟體與下載位置

 
<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
詳細資訊
</th>
<th style="border:1px solid black;" >
詳細資訊
</th>
<th style="border:1px solid black;" >
詳細資訊
</th>
<th style="border:1px solid black;" >
詳細資訊
</th>
<th style="border:1px solid black;" >
詳細資訊
</th>
<th style="border:1px solid black;" >
詳細資訊
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-003**](https://technet.microsoft.com/security/bulletin/ms08-003)
</td>
<td style="border:1px solid black;">
[**MS08-004**](https://technet.microsoft.com/security/bulletin/ms08-004)
</td>
<td style="border:1px solid black;">
[**MS08-005**](https://technet.microsoft.com/security/bulletin/ms08-005)
</td>
<td style="border:1px solid black;">
[**MS08-006**](https://technet.microsoft.com/security/bulletin/ms08-006)
</td>
<td style="border:1px solid black;">
[**MS08-007**](https://technet.microsoft.com/security/bulletin/ms08-007)
</td>
<td style="border:1px solid black;">
[**MS08-008**](https://go.microsoft.com/fwlink/?linkid=108277)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最高的嚴重性等級**
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
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<th colspan="7">
Windows 作業系統
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Server Service Pack 4
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=93b3d0a3-2091-405e-8dd4-10f20dc2be7f)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=afeef3ec-6160-4c1d-94bd-0bfce641d0a2)
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=5c331a3a-93e0-42e4-9cd1-4e32ebdda38d)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?familyid=15b7d1c4-4ef4-47b2-9e3b-22eafbdb90d8)
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?familyid=e0a15967-7184-4194-8edb-81760e440604)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 與 Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=b7e725bf-7248-4119-aca5-b7d502c09cfc)
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=cfa0d5c6-a9b0-4c5c-a651-898e9f900799)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=8af82f86-731c-46a0-a025-b62447e2af38)
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=a08e87dc-993b-493b-8af3-be6e98643aeb)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP1 for Itanium-based Systems 和 Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?familyid=bca224db-fe0e-411d-a948-1c776ce974f3)
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?familyid=5a88522b-ee30-4deb-878b-598e852fd60e)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=8ce9608b-7049-47cd-adc4-22a803877d33)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=ba7a2b42-1c89-45e5-b8a6-049fa500c03a)
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=c67ec357-0f86-4f7d-9af0-d63d8b765f44)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=d7b9c3d1-9c23-4e05-bac6-d0b327feaf53)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?familyid=45962232-af78-42cb-bfa0-9ce7de199585)
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=9137108f-e80b-46f1-b547-82da8fb058bf)
</td>
</tr>
<tr>
<th colspan="7">
受影響的 Windows 作業系統元件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 上的 Microsoft Internet Information Services 5.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=b24f34fb-40b9-4aa5-b5ac-e3f0a6062753)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional Service Pack 2 上的 Microsoft Internet Information Services 5.1
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=73d24fcf-bea9-4b13-9f1c-4e068c53a4ae)
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=2b498065-d682-4227-b23e-d234d7d6a3fe)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 與 Windows XP Professional x64 Edition Service Pack 2 上的 Microsoft Internet Information Services 5.1
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=103a6bc0-034a-443d-b1d4-81117820dcb2)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 與 Windows XP Professional x64 Edition Service Pack 2 上的 Microsoft Internet Information Services 6.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=df9875f7-04d6-486e-bdb5-35e9e305fa1d)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 與 Windows Server 2003 Service Pack 2 上的 Microsoft Internet Information Services 6.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=516ef8e8-3cb6-4660-b771-3c7f66917a11)
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=6583e798-d16d-419c-aee1-30c3e6c635b3)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 與 Windows Server 2003 x64 Edition Service Pack 2 上的 Microsoft Internet Information Services 6.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=e24fb33c-67b9-4ed4-9317-b5fd535d005a)
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=e8286174-8209-409f-8805-e534715a741c)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP1 for Itanium-based Systems 與 Windows Server 2003 SP2 for Itanium-based Systems 上的 Microsoft Internet Information Services 6.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=5a4a6083-8c67-4403-8e20-7f2b82178124)
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=29faa70d-f1ac-4da4-b72a-faf1973cd845)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 上的 Microsoft Internet Information Services 7.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=8c7018ec-ae80-4a30-93fc-0f7386732514)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 上的 Microsoft Internet Information Services 7.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=4de2fffc-5793-4acf-98ee-1b801e59ae39)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows 2000 Server Service Pack 4 上的 Active Directory
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=9df0875d-0466-4974-b4c0-1ecc777173b1)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
安裝在 Windows XP Professional Service Pack 2 上的 ADAM
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=bff7dcb9-5d00-442e-b03c-ce923d213faa)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
安裝於 Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2 上的 ADAM
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?familyid=36e36e1a-ed0d-45a6-b707-766fabc01fbd)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 上的 Active Directory
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=63d3d784-f057-4686-b85e-ab5fbab5a722)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
安裝在 Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 上的 ADAM
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=60781cf3-7c6d-4795-a9d0-bc18ee356e94)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 上的 Active Directory
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=835d647a-dce6-476e-b7c4-928a67b0acfb)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
安裝在 Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 上的 ADAM
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=5e97698d-8150-44f9-9d34-87a0db6ba5a7)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP1 和適用於 Itanium 型系統的 Windows Server 2003 SP2 上的 Active Directory
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?familyid=eda8af09-1a4c-4163-a8bb-97dacdebeae4)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="7">
Microsoft Office
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/mac/downloads.aspx)
</td>
</tr>
<tr>
<th colspan="7">
其他受影響的軟體
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Basic 6.0 Service Pack 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=c96420a9-7436-4625-9649-75f1514b0fe3)
</td>
</tr>
</table>
 
**注意：**

**<sup>[1]</sup>** 已針對此作業系統提供安全性更新。 請參閱表格中受影響的軟體或元件，以及相關的安全性公告以獲得詳細資訊。** **

#### 適用於公告 MS08-009 至 MS08-013 的受影響軟體與下載位置

 
<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
詳細資訊
</th>
<th style="border:1px solid black;" >
詳細資訊
</th>
<th style="border:1px solid black;" >
詳細資訊
</th>
<th style="border:1px solid black;" >
詳細資訊
</th>
<th style="border:1px solid black;" >
詳細資訊
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS08-009**](https://technet.microsoft.com/security/bulletin/ms08-009)
</td>
<td style="border:1px solid black;">
[**MS08-010**](https://technet.microsoft.com/security/bulletin/ms08-010)
</td>
<td style="border:1px solid black;">
[**MS08-011**](https://technet.microsoft.com/security/bulletin/ms08-011)
</td>
<td style="border:1px solid black;">
[**MS08-012**](https://technet.microsoft.com/security/bulletin/ms08-012)
</td>
<td style="border:1px solid black;">
[**MS08-013**](https://technet.microsoft.com/security/bulletin/ms08-013)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最高的嚴重性等級**
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
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重大**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<th colspan="6">
Windows 作業系統
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 與 Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP1 for Itanium-based Systems 和 Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="6">
受影響的 Windows 作業系統元件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 中的 Internet Explorer 5.01 Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=1032a039-468b-4c5f-8c1c-5e54c2832e41)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
安裝在 Microsoft Windows 2000 Service Pack 4 上的 Internet Explorer 6 Service Pack 1
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=87e66dce-5060-4814-8754-829b4e190359)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 2 中的 Internet Explorer 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=bb2aa3cb-021f-4890-ab20-2a51f8e17554)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2 的 Internet Explorer 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=8989f576-8b30-4866-90ec-929d24f3b409)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 的 Internet Explorer 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=429b7ed1-fe78-459a-b834-d0f3c69cb703)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 的 Internet Explorer 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=e989e23c-38bb-4fe7-a830-d7bdf7659392)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Windows Server 2003 SP1 for Itanium-based Systems 和 Windows Server 2003 SP2 for Itanium-based Systems 的 Internet Explorer 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?familyid=5a097f7a-b696-48d0-b13f-337c5fd14e24)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=d4aa293a-6332-4c6c-b128-876f516bd030)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Windows XP Professional x64 Edition 及 Windows XP Professional x64 Edition Service Pack 2 的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=b72af1b6-6e23-4005-aef6-82195b380153)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=b2aa6562-881e-4fd6-be1b-53426a0ff4a9)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=4bb99afc-be14-4f2e-9570-b7fe09e39131)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Windows Server 2003 SP1 for Itanium-based Systems 和 Windows Server 2003 SP2 for Itanium-based Systems 的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?familyid=6fa80e2c-5e91-4b33-acd9-33f156660ae7)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 中的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=0de25b98-f443-4874-a06f-4daae14c16b0)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition 中的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=c08ebbe7-639b-4ea2-8304-fab531930abf)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="6">
Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=5fb74e24-d9ee-4951-9c46-e1c84617f097)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=3e147b1a-f3be-465f-8587-7f3a33d6a6e5)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=f4ac0f34-4604-4bbe-9669-01db645041ca)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/mac/downloads.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=a513069b-8244-48e9-b136-01ddd3862802)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Word 2002 Service Pack 3
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=78c338aa-e410-4422-9e36-562f70d742e9)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=85cb1aa5-211f-4652-827b-2e79b8ffc2fc)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Word Viewer 2003
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=fd4ddecd-abd6-4783-b300-32b9d4bad22a)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Publisher 2000
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重大](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=d8b085fb-858f-4c7e-96de-edff8f49d62a)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Publisher 2002
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=1135c63a-6ce7-4051-81ba-bfbba8d857fb)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Publisher 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=7078b952-09f6-4c47-8c05-40667e1f1c3b)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="6">
受影響的 Office 軟體
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 2 上的 Microsoft Works 6 File Converter
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=30c9c3fe-fb85-43d9-bbc3-0b30d3a20286)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3 上的 Microsoft Works 6 File Converter
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中度](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=30c9c3fe-fb85-43d9-bbc3-0b30d3a20286)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Works 8.0 上的 Microsoft Works 6 File Converter
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=30c9c3fe-fb85-43d9-bbc3-0b30d3a20286)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works Suite 2005 上的 Microsoft Works 6 File Converter
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-tw&familyid=30c9c3fe-fb85-43d9-bbc3-0b30d3a20286)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
</table>
 
**注意：**

**<sup>[1]</sup>** 已針對此作業系統提供安全性更新。 請參閱表格中受影響的軟體或元件，以及相關的安全性公告以獲得詳細資訊。** **

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及行動電腦的軟體和安全性更新。 如需更多資訊，請參閱 [TechNet 更新管理中心](https://www.microsoft.com/taiwan/technet/updatemanagement/default.mspx) (英文)。 [TechNet Security Center](https://www.microsoft.com/taiwan/technet/security/default.mspx) 提供 Microsoft 產品安全性的其他資訊。 消費者可以造訪[在家上網的安全性](https://www.microsoft.com/taiwan/athome/security/default.mspx)網站，只要按一下 \[最新安全性更新\] 即可在此網站取得此資訊。

安全性更新可以從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)、[Windows Update](https://go.microsoft.com/fwlink/?linkid=21130)及 [Office Update](https://office.microsoft.com/zh-tw/downloads/default.aspx)取得。 安全性更新也可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得。 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。

最後，您可以從 [Microsoft Update Catalog](https://go.microsoft.com/fwlink/?linkid=96155) 下載安全性更新。 Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括安全性更新、驅動程式和 Service Pack。 只要以安全性公告編號 (例如，"MS07-036") 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。 如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](https://go.microsoft.com/fwlink/?linkid=97900)。

**偵測與部署指南**

Microsoft 已提供本月安全性更新之偵測與部署指南。 此指南還能幫助 IT 專業人員瞭解如何使用各項工具來協助部署安全性更新，像是 Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office Detection Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool (加強版安全性更新清查工具，ESUIT)。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 910723](https://support.microsoft.com/kb/910723)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少安全性更新以及一般安全性設定錯誤的狀況。 如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134) 網站 (英文)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速可靠地將 Windows 2000 作業系統及更新系統版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 等最新的重大更新與安全性更新部署到 Windows 2000 及更新作業系統版本中。

System Center Configuration Manager (SCCM) 2007 使用 WSUS 3.0 來偵測更新。 如需更多關於 SCCM 2007 軟體更新管理的資訊，請造訪 [System Center Configuration Manager 2007](https://technet.microsoft.com/en-us/library/bb735860.aspx) 網站。

如需更多關於利用 Windows Server Update Services 部署安全性更新的資訊，請造訪 [Windows Server Update Services](https://www.microsoft.com/taiwan/windowsserversystem/updateservices/evaluation/overview.mspx) 網站。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。 現已推出新版的 SMS，System Center Configuration Manager 2007；另請參閱 [System Center Configuration Manager 2007](https://technet.microsoft.com/en-us/library/bb735860.aspx)。如需更多有關系統管理員如何能使用 SMS 2003 部署安全性更新的資訊，請參閱 [SMS 2003 安全性修補程式管理](https://www.microsoft.com/taiwan/smserver/evaluation/capabilities/patch.htm) (英文)。 SMS 2.0 使用者也可以利用 [SMS 軟體更新服務功能套件](https://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/suspack/default.htm)來協助部署安全性更新。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server](https://www.microsoft.com/taiwan/smserver/)。

**注意：**SMS 使用 Microsoft Baseline Security Analyzer 及 Microsoft Office Detection Tool，為安全性公告更新的偵測及部署作業提供相當廣泛的支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](https://go.microsoft.com/fwlink/?linkid=33341)。 某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可以用 Elevated Rights Deployment Tool (隨 [SMS 2003 Administration Feature Pack](https://www.microsoft.com/taiwan/smserver/downloads/2003/adminpack.htm) (英文) 和 [SMS 管理功能套件](https://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/adminpack/default.htm) (英文) 提供) 來安裝這些更新。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非安全性、高優先順序更新

本月份：

-   Microsoft 已在 Microsoft Update (MU) 和 Windows Server Update Services (WSUS) 上發行五個「非安全性」高優先順序更新。
-   Microsoft 已在 Windows Update (WU) 及 WSUS 上針對 Windows 發行兩個「非安全性」高優先順序更新。

請注意，此資訊僅與 Microsoft Update、Windows Update 和 Windows Server Update Services 上，與本安全性公告摘要同日發行的「非安全性」高優先順序更新有關。 於其他日期發行的「非安全性」更新相關資訊並未包含在內。

#### 安全性策略與社群

**更新程式管理策略**

[更新管理安全性指南](https://www.microsoft.com/taiwan/technet/security/topics/patchmanagement.mspx) (英文) 提供您有關套用安全性更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他安全性更新**

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「安全性更新」("security update") 關鍵字搜尋輕易地找到安全性更新。
-   客戶平台的更新可從 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的安全性更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](https://support.microsoft.com/kb/913086)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](https://go.microsoft.com/fwlink/?linkid=21164)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](https://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 [SkyRecon](https://www.skyrecon.com/) 的 Thomas Garnier 回報 MS08-003 中描述的問題
-   感謝 [Whitestein](https://www.whitestein.com/) Technologies 的 Tomas Potok、Martin Dominik、Martin Luptak、Eva Juhasova 回報 MS08-004 中描述的問題
-   感謝 [COSEINC Vulnerability Research Lab](https://www.coseinc.com/) 的 Steven 回報 MS08-007 中描述的問題
-   感謝 [IBM ISS X-Force](https://www.iss.net/) 的 Ryan Smith 和 Alex Wheeler 回報 MS08-008 中描述的問題
-   感謝 [Reversemode.com](https://reversemode.com/) 的 Rubén Santamarta 回報 MS08-009 中描述的問題
-   感謝 [Security Objectives](https://www.security-objectives.com/) 的 Shane Macaulay 和 Riley Hassell 回報 MS08-010 中描述的問題
-   感謝匿名的研究人員和 [TippingPoint](https://www.tippingpoint.com/) 及 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作回報 MS08-010 中描述的問題
-   感謝 hyy 與 [VeriSign iDefense VCP](https://idefense.com/) 合作，協助 Microsoft 解決 MS08-010 中描述的問題
-   感謝 [ADLABS](https://www.venustech.com.cn/) 的 Venustech 回報 MS08-010 中描述的問題
-   感謝 [VeriSign iDefense VCP](https://labs.idefense.com/) 回報 MS08-011 中描述的問題
-   感謝 Damian Put 與 [VeriSign iDefense VCP](https://labs.idefense.com/) 合作，共同回報 MS08-011 中描述的問題
-   感謝 [IBM Internet Security Systems X-Force](https://xforce.iss.net/) 回報 MS08-011 中描述的問題
-   感謝 Piotr Bania 回報 MS08-012 中描述的問題
-   感謝 [Fortinet Security Research](https://www.fortinet.com/) 的 Bing Liu 回報 MS08-012 中描述的問題
-   感謝 [Fortinet Security Research](https://www.fortinet.com/) 的 Bing Liu 回報 MS08-012 中描述的問題
-   感謝 [NGSSoftware](https://www.ngssoftware.com/) 的 Shaun Colley 回報 MS08-013 中描述的問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可電洽 1-866-PCSAFETY [Microsoft 產品支援服務](https://go.microsoft.com/fwlink/?linkid=21131)以取得技術支援。 與安全性更新有關的支援電話不另外收費。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與安全性更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](https://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2008 年 2 月 13 日)： 公告摘要發行。

*Built at 2014-04-18T01:50:00Z-07:00*
