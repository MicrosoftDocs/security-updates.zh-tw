---
TOCTitle: 'Windows 2000 Server 的 TCP/IP 漏洞與對策'
Title: 'Windows 2000 Server 的 TCP/IP 漏洞與對策'
ms:assetid: 'd291acd3-9776-4de1-864c-d7e0a45f5a42'
ms:contentKeyID: 20214390
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Dd548207(v=TechNet.10)'
---

Windows 2000 Server 的 TCP/IP 漏洞與對策
========================================

Overview

發佈日期: 2004 年 11 月 17 日 | 更新日期: 2006 年 5 月 31 日

##### 本頁內容

[](#efaa)[目標](#efaa)
[](#eeaa)[適用於](#eeaa)
[](#edaa)[如何使用本單元](#edaa)
[](#ecaa)[摘要](#ecaa)
[](#ebaa)[Windows 2000 TCP/IP 堆疊可能的威脅及對策的影響](#ebaa)

### 目標

透過本單元即可：

-   識別 Microsoft® Windows® 2000 作業系統 TCP/IP 堆疊可能的漏洞。

-   將登錄設定成是因應 Windows 2000 TCP/IP 堆疊漏洞的對策。

-   識別 Windows 2000 TCP/IP 堆疊其漏洞和對策的可能影響。

[](#mainsection)[回到頁首](#mainsection)

### 適用於

本單元適用於下列產品及技術：

-   Windows 2000

-   Windows 2000 TCP/IP 堆疊

-   Windows 2000 登錄

[](#mainsection)[回到頁首](#mainsection)

### 如何使用本單元

本單元應用於保障 Windows 2000 TCP/IP 堆疊的安全。本單元也可用於識別 TCP/IP 堆疊的漏洞和對策的影響。

[](#mainsection)[回到頁首](#mainsection)

### 摘要

本單元在於強調 Windows 2000 TCP/IP 堆疊可能的漏洞。本單元還探討了可透過 **HKLM\\System\\CurrentControlSet\\Services\\Tcpip\\Parameters\\** 登錄機碼的設定而套用的對策。另外也涵蓋了此設定的可能影響。

[](#mainsection)[回到頁首](#mainsection)

### Windows 2000 TCP/IP 堆疊可能的威脅及對策的影響

\[表 1\] 指出 TCP/IP 堆疊可能的漏洞。該表還指出可能的對策，以及漏洞和對策可能的影響。

**\[表 1\]：TCP/IP 堆疊可能的漏洞**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >登錄值項目</th>
<th style="border:1px solid black;" >對策可能的影響</th>
<th style="border:1px solid black;" >可能的漏洞</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">EnableICMPRedirect</td>
<td style="border:1px solid black;">當「路由及遠端存取服務 (RRAS)」設定為自發的系統邊界路由器 (Autonomous System Boundary Router，ASBR) 時，並無法正確地匯入連線的介面子網路路由。此路由器反而會將主機路由插入 Open Shortest Path First (OSPF) 路由。由於 OSPF 路由器無法用作為 ASBR 路由器，將連線的介面子網路路由匯入到 OSPF 會造成路由表與陌生的路由路徑相混淆。</td>
<td style="border:1px solid black;">「網際網路控制訊息通訊協定 (Internet Control Message Protocol，ICMP)」重新導向會導致堆疊包含主機路由。這些路由會覆蓋 OSPF 產生的路由。<br />
這本身是預期的行為。問題在於 ICMP 包含重新導向之路由的 10 分鐘逾時期間會引起網路相關的黑洞。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SynAttackProtect</td>
<td style="border:1px solid black;">這是促使 TCP 調整 SYN-ACK 重新傳輸的登錄值。當您設定此值時，在 SYN 攻擊的事件中，連線會更快速回應逾時。此值會在連線指示增加額外的延遲，而 TCP 連線要求在 SYN 攻擊進行時很快就會逾時。當您設定此設定時，在每一介面卡通訊端選項上的可調整視窗和 TCP 參數 (包括「初始往返時間 (RTT)」和視窗大小) 將不再有作用。</td>
<td style="border:1px solid black;">在 SYN 大量攻擊中，攻擊者會傳送連續不斷的 SYN 封包資料流給伺服器，而伺服器會保持半開放的連線，直到無法負荷而且不能再回應合法的要求為止。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">EnableDeadGWDetect</td>
<td style="border:1px solid black;">當啟用死閘道偵測時，如果大量連線遭遇到問題，TCP 可能會要求 IP 變更備份閘道。當此設定設定為 0 時，Windows 將不再偵測死閘道而會自動切換到其他閘道。</td>
<td style="border:1px solid black;">攻擊者可強制伺服器將閘道切換到一個可能是非預期的閘道。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">EnablePMTUDiscovery</td>
<td style="border:1px solid black;">當您將 EnablePMTUDiscovery 設定為 1 時，TCP 會嘗試在遠端主機的路徑上探索傳輸單元最大值 (MTU) 或最大封包大小。TCP 可藉由探索路徑 MTU 並限制 TCP 片段為此大小，來消除以不同 MTU 連接網路的路徑之路由器的分散程度。<br />
分散程度對 TCP 輸出量有不利的影響。當此值設為 0 時，所有不是本機子網路主機的連線都會使用 576 位元組的 MTU。</td>
<td style="border:1px solid black;">若您不將此值設為 0，攻擊者就可藉由強制伺服器分散成許多封包，來迫使 MTU 變成非常小的值而過度使用堆疊。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">KeepAliveTime</td>
<td style="border:1px solid black;">這個值會透過傳送持續作用的 (Keep-Alive) 封包，來控制 TCP 多久嘗試確認一個閒置連線是否仍然處於完整無缺。若遠端電腦仍是可以連線的，它會告知收到持續作用的封包。<br />
持續作用的封包依預設並不會傳送。您可以使用程式在連線上設定此值。將此值從預設的 2 小時減少為 5 分鐘，表示會更快速地中斷非作用中工作階段的連線。</td>
<td style="border:1px solid black;">能夠連線到網路應用程式的攻擊者，可藉由建立無數的連線而造成 Dos 的狀況。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">DisableIPSourceRouting</td>
<td style="border:1px solid black;">IP 來源路由是一種允許傳送者決定資料包通過網路時應該採用 IP 路由的機制。將此值設為 2 將致使所有連入的來源路由封包遭到捨棄。</td>
<td style="border:1px solid black;">攻擊者會利用來源路由封包來隱匿它們的身分和位置。來源路由允許傳送封包的電腦指定它要採用的路由。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">TCPMaxConnectResponseRetransmissions</td>
<td style="border:1px solid black;">此參數控制著若 SYN 未被認可，則為了回應連線要求而重新傳輸 SYN-ACK 的次數。<br />
若此值大於或等於 2，則堆疊會從內部採取 SYN-ATTACK 保護。若此值小於 2，則堆疊完全不會讀取 SYN-ATTACK 保護的登錄值。此參數會縮短清除半開啟 TCP 連線所花的預設時間。處於重度攻擊的站台可將此值設為 1。0 的值也有效。不過，若此參數設為 0，將完全無法重新傳輸 SYN-ACK，而且將於 3 秒內逾時。將此值設得如此低，可能會導致遠處用戶端的合法連線嘗試失敗。</td>
<td style="border:1px solid black;">在 SYN 大量攻擊中，攻擊者會傳送連續不斷的 SYN 封包資料流給伺服器，而伺服器會保持半開放的連線，直到無法負荷而且不能再回應合法的要求為止。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">TCPMaxDataRetransmissions</td>
<td style="border:1px solid black;">TCP 會在每個輸出片段交至 IP 時，啟動重新傳輸計時器。若在計時器過期前未收到對特定片段中的資料認可，最多將重新傳輸該片段 3 次。</td>
<td style="border:1px solid black;">在 SYN 大量攻擊中，攻擊者會傳送連續不斷的 SYN 封包資料流給伺服器，而伺服器會保持半開放的連線，直到無法負荷而且不能再回應合法的要求為止。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">PerformRouterDiscovery</td>
<td style="border:1px solid black;">這個設定是為了防止 Windows 2000 (支援「網際網路路由器探索通訊協定 (Internet Router Discovery Protocol，IRDP)」) 自動在電腦上偵測和設定預設閘道位址。</td>
<td style="border:1px solid black;">取得相同網路片段上其中一個系統控制權的攻擊者，可設定網路上的一部電腦來模擬路由器。<br />
其他有啟用 IRDP 的電腦接著就會嘗試將它們的流量路由到已遭入侵的系統。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">TCPMaxPortsExhausted</td>
<td style="border:1px solid black;">此參數控制著 SYN-ATTACK 保護開始操作的點。SYN-ATTACK 保護會在 TCPMaxPortsExhausted 連接要求因連線可用的積存設為 0 而遭到系統拒絕時開始操作。這對嘗試合法使用它的伺服器或系統有些微的影響。</td>
<td style="border:1px solid black;">在 SYN 大量攻擊中，攻擊者會傳送連續不斷的 SYN 封包資料流給伺服器，而伺服器會保持半開放的連線，直到無法負荷而且不能再回應合法的要求為止。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">AFD 設定：
DynamicBacklogGrowthDelta  
EnableDynamicBacklog<br />
MinimumDynamicBacklog
MaximumDynamicBacklog</td>
<td style="border:1px solid black;">Windows 通訊端應用程式，如 FTP 伺服器及 Web 伺服器，其連線嘗試是由 Afd.sys 所處理。Afd.sys 已經過修改成在不拒絕合法用戶端存取的情況下，支援大量半開放狀態下的連線。<br />
這是藉由允許系統管理員設定動態積存而達成。<br />
DynamicBacklogGrowthDelta 控制著在需要額外連線時，可建立的免費連線數目。請小心使用此值，因為較大的值可能會導致配置過多的免費連線。</td>
<td style="border:1px solid black;">在 SYN 大量攻擊中，攻擊者會傳送連續不斷的 SYN 封包資料流給伺服器，而伺服器會保持半開放的連線，直到無法負荷而且不能再回應合法的要求為止。</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[回到頁首](#mainsection)
