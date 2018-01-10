---
TOCTitle: 'MS04-NOV'
Title: 2004 年 11 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms04-nov'
ms:contentKeyID: 61237640
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms04-nov(v=Security.10)'
---

Security Bulletin Summary

2004 年 11 月份 Microsoft 資訊安全公告摘要
==========================================

發行: 2004年11月10日

**版本:** 1.0

**發佈日期：**2004 年 11 月 10 日
**版本號碼：**1.0

請參考[此處](http://www.microsoft.com/taiwan/security/default.mspx)所提供的使用者版本資訊。

**保護您的電腦：**Microsoft 在下列網址提供有助於保護電腦的相關資訊：

-   一般使用者可以瀏覽[保護您的電腦網站](http://www.microsoft.com/taiwan/security/protect/)。
-   IT 專業人員可以瀏覽[資訊安全指導中心](http://www.microsoft.com/taiwan/security/guidance/default.mspx)網站。

**更新程式管理策略：**[Microsoft 安全性補充程式管理指南](http://www.microsoft.com/taiwan/security/spm_guide.asp)網站提供您有關套用安全性更新的 Microsoft 最佳實作建議資訊。

**IT Pro 資訊安全區社群：**在 [IT Pro 資訊安全區網站](http://go.microsoft.com/fwlink/?linkid=21164) (英文) 上，學習如何提升安全性及加強您的 IT 基礎結構，並與其他的 IT 專業人員共同參與各類安全性議題的討論。

**Microsoft 安全性通知服務：**如果要在 Microsoft 安全性公告發佈時收到電子郵件通知，請訂閱 [Microsoft 安全性通知服務](http://go.microsoft.com/fwlink/?linkid=21163) (英文)。

#### 摘要

本次摘要報告內含最近發現弱點的更新資訊。 依照嚴重性的等級，這些弱點分類如下：

重要 (1)
--------

<span></span>
| 公告編號             | Microsoft 安全性公告 MS04-039                                                                                                                      |
|----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告標題**         | [ISA Server 2000 及 Proxy Server 2.0 中的弱點可能會允許網際網路內容偽造 (888258)](http://www.microsoft.com/taiwan/security/bulletin/ms04-039.mspx) |
| **提要**             | 這項弱點可使攻擊者能夠偽造信任的網際網路內容。                                                                                                     |
| **最高的嚴重性等級** | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                      |
| **弱點的影響**       | 偽造                                                                                                                                               |
| **受影響的軟體**     | **Windows** 如需更多資訊，請參閱＜受影響的軟體及下載位置＞部份。                                                                                   |

受影響的軟體及下載位置
----------------------

<span></span>
**我該如何使用這個表格？**

您可以用這個表格來瞭解可能需要安裝的安全性更新有哪些。 您應該查看此處列出的每一種軟體程式或元件，看看是否有需要的安全性更新。 在列出的軟體程式或元件旁邊，會附註弱點的影響等級，同時也會列出可用軟體更新的超連結。

**受影響的軟體及下載位置**

|                                                                                                                                                    | 詳細資訊                                                                                              |
|----------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|
| **公告編號**                                                                                                                                       | [**MS04-039**](http://www.microsoft.com/taiwan/security/bulletin/ms04-039.mspx)                       |
| **最高的嚴重性等級**                                                                                                                               | [**重要**](http://technet.microsoft.com/security/bulletin/rating)                                     |
| **受影響的 Windows 軟體：**                                                                                                                        |                                                                                                       |
| Microsoft Internet Security and Acceleration Server 2000 Service Pack 1 及 Microsoft Internet Security and Acceleration Server 2000 Service Pack 2 | [重要](http://www.microsoft.com/downloads/details.aspx?familyid=7a4c318f-5ac9-4cf2-8792-a4a62076ebe7) |
| Microsoft Small Business Server 2000 (其中即包含 Microsoft Internet Security and Acceleration Server 2000)                                         | [重要](http://www.microsoft.com/downloads/details.aspx?familyid=7a4c318f-5ac9-4cf2-8792-a4a62076ebe7) |
| Microsoft Small Business Server 2003 Premium Edition (其中即包含 Microsoft Internet Security and Acceleration Server 2000)                         | [重要](http://www.microsoft.com/downloads/details.aspx?familyid=7a4c318f-5ac9-4cf2-8792-a4a62076ebe7) |
| Microsoft Proxy Server 2.0 Service Pack 1                                                                                                          | [重要](http://www.microsoft.com/downloads/details.aspx?familyid=55643141-91e3-4474-8134-72887bc6fc18) |

部署
----

<span></span>
**Systems Management Server：**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要安全性更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。 如需更多關於系統管理員如何使用 SMS 2003 部署安全性更新的資訊，請瀏覽 [SMS 2003 的安全性補充程式管理網站](http://www.microsoft.com/taiwan/smserver/evaluation/capabilities/patch.htm)。 SMS 2.0 使用者也可以利用 [SMS 軟體更新服務功能套件](http://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/suspack/)來協助部署安全性更新。 如需關於 SMS 的詳細資訊，請瀏覽 [SMS 網站](http://www.microsoft.com/taiwan/smserver/)。

**注意：**SMS 使用 Microsoft 基線安全性分析器及 Microsoft Office Detection Tool，為安全性公告更新的偵測及部署作業提供相當廣泛的支援。 不過這些工具可能無法偵測部份的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需更多關於這個程序的資訊，請瀏覽這個[網站](http://go.microsoft.com/fwlink/?linkid=33341)。 某些安全性更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可以用 Elevated Rights Deployment Tool (隨 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/taiwan/smserver/downloads/2003/adminpack.htm) 和 [SMS 管理功能套件](http://www.microsoft.com/taiwan/smserver/downloads/20/featurepacks/adminpack/default.htm)提供) 來安裝這些更新。

#### 其他資訊：

**感謝**

Microsoft [感謝](http://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   Info Support 的 [Martijn de Vries](mailto:martijnv@infosupport.com) 與 [Thomas de Klerk](mailto:thomask@infosupport.com) 分別發現和回報偽造弱點 (CAN-2004-0892)。

**取得其他安全性更新：**

其他安全性問題的更新可由下列位置取得：

-   安全性更新可以從 [Microsoft 下載中心](http://www.microsoft.com/downloads/search.aspx?displaylang=zh-tw)取得， 您也可以利用 "security\_patch" 關鍵字搜尋輕易地找到安全性更新。
-   使用者平台的更新程式可以從 [Windows Update 網站](http://go.microsoft.com/fwlink/?linkid=21130)取得。

**支援：**

-   美國及加拿大地區客戶可電洽 1-866-PCSAFETY [Microsoft 技術支援服務](http://go.microsoft.com/fwlink/?linkid=21131)以取得技術支援。 與安全性更新有關的支援電話不另外收費。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與安全性更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，可以從[世界各地技術支援網站](http://go.microsoft.com/fwlink/?linkid=21155)取得。

**安全性資源：**

-   [Microsoft TechNet 資訊安全](http://www.microsoft.com/taiwan/technet/security/default.mspx)網站提供了有關 Microsoft 產品安全性的其他資訊。
-   [Microsoft Software Update Services](http://www.microsoft.com/taiwan/windowsserversystem/sus/default.mspx)
-   [Microsoft 基線安全性分析器](http://www.microsoft.com/taiwan/security/tools/mbsahome.asp) (MBSA)
-   [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)
-   Windows Update 目錄：如需更多關於 Windows Update 目錄的資訊，請參閱 Microsoft 知識庫文件編號 [323166](http://support.microsoft.com/default.aspx?scid=kb;en-us;323166)。
-   [Office Update](http://go.microsoft.com/fwlink/?linkid=21135)

**免責聲明：**

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

**修訂：**

-   V1.0 (2004 年 11 月 10 日)：公告發行

*Built at 2014-04-18T01:50:00Z-07:00*
