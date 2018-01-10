---
TOCTitle: '檢查清單：Windows Server 2003 列印伺服器'
Title: '檢查清單：Windows Server 2003 列印伺服器'
ms:assetid: 'bd12b230-079a-44e8-80b2-e349f422e38a'
ms:contentKeyID: 20214399
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Dd548216(v=TechNet.10)'
---

檢查清單：Windows Server 2003 列印伺服器
========================================

發佈日期: 2003 年 12 月 31 日 | 更新日期: 2004 年 7 月 1 日

##### 本頁內容

[](#ebaa)

使用下列檢查清單，有助在強化 Microsoft® Windows Server™ 2003 作業系統列印伺服器時，正確執行所有的安全設定和程序。

#### 建立 Microsoft Active Directory® 列印伺服器組織單位結構：

 
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
<img src="images/Dd548216.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">建立列印伺服器組織單位 (OU)。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548216.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">建立增量列印伺服器原則。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548216.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">將 GPO 連結到列印伺服器組織單位。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548216.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">將對應的用戶端環境安全性範本匯入到新建立的 GPO。</td>
<td style="border:1px solid black;">例如，企業用戶端環境的 Enterprise Client — Print Server.inf。</td>
</tr>
</tbody>
</table>
  
#### 安裝與強化列印伺服器的步驟：

 
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
<img src="images/Dd548216.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">安裝和設定 Windows Server 2003。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548216.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">套用任何所需的 Service Pack 和/或更新。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548216.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">安裝和設定病毒防護解決方案。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548216.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">依要求來安裝和設定 Microsoft Operations Manager (MOM) 代理程式或類似的監視解決方案。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548216.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">移動適當伺服器到對應的檔案伺服器組織單位。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548216.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">保護已知的帳號。</td>
<td style="border:1px solid black;">重新命名內建的 Administrator 帳號，指派一個複雜的密碼。 請確定 Guest 帳戶已經停用。 變更預設帳號描述。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548216.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">保護服務帳號。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548216.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">考慮執行 IPSec 篩選器。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548216.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">驗證網域控制站之間是否已覆寫增量列印伺服器原則。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548216.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">執行 GPUPDATE.EXE /FORCE。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548216.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">重新啟動電腦。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548216.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">查看事件日誌以檢查錯誤。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548216.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">必要時安裝和設定印表機共用。</td>
<td style="border:1px solid black;">  </td>
</tr>
</tbody>
</table>
  
[](#mainsection)[回到頁首](#mainsection)
