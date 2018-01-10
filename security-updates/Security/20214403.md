---
TOCTitle: '檢查清單：Windows Server 2003 堡壘主機'
Title: '檢查清單：Windows Server 2003 堡壘主機'
ms:assetid: '59a9eb40-d7c4-4855-9213-f7a843f0fa77'
ms:contentKeyID: 20214403
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Dd548220(v=TechNet.10)'
---

檢查清單：Windows Server 2003 堡壘主機
======================================

發佈日期: 2003 年 12 月 31 日 | 更新日期: 2004 年 7 月 1 日

##### 本頁內容

[](#ebaa)

使用下列檢查清單，有助正確地強化 Microsoft® Windows Server™ 2003 作業系統的堡壘主機伺服器，例如，網域名稱系統 (DNS) 伺服器、檔案傳輸通訊協定 (FTP) 伺服器、Simple Mail Transport Protocol (SMTP) 伺服器，以及網路 News 傳輸通訊協定 (NNTP) 伺服器。

#### 強化堡壘主機的步驟：

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >  </th>
<th style="border:1px solid black;" >步驟</th>
<th style="border:1px solid black;" >注意：</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548220.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">安裝和設定 Windows Server 2003。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548220.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">安裝並設定適當的堡壘主機伺服器。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548220.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">套用任何所需的 Service Pack 和/或更新。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548220.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">安裝和設定病毒防護解決方案。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548220.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">安裝並設定適當的堡壘主機伺服器。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548220.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">修改堡壘主機安全性範本，以啟動所須的服務，進而提供恰當的堡壘主機功能。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548220.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">將安全性範本匯入堡壘主機的本機原則 (BHLP)。</td>
<td style="border:1px solid black;">使用增益級 Security and Configuration Analysis 來匯入 High Security – Bastion Host.inf。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548220.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">移除非必要的通訊協定及連結。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548220.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">保護已知的帳號。</td>
<td style="border:1px solid black;">重新命名內建的 Administrator 帳號，指派一個複雜的密碼。 請確定 Guest 帳戶已經停用。 變更預設帳號描述。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548220.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">保護服務帳號。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548220.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">停用 BHLP 內的錯誤報告。</td>
<td style="border:1px solid black;">DCBP內的路徑： Computer Configuration\Administrative Templates\System\Error Reporting。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548220.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">執行 IPSec 篩選。</td>
<td style="border:1px solid black;">修改 PacketFilters-SMTPBastionHost.cmd 檔案，以啟用適當的堡壘主機功能。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548220.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">重新啟動電腦。</td>
<td style="border:1px solid black;">  </td>
</tr>
</tbody>
</table>
  
[](#mainsection)[回到頁首](#mainsection)
