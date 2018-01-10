---
TOCTitle: '檢查清單：Windows Server 2003 網域基礎結構'
Title: '檢查清單：Windows Server 2003 網域基礎結構'
ms:assetid: '07024304-13eb-4b63-9ae9-d172729156ba'
ms:contentKeyID: 20214394
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Dd548211(v=TechNet.10)'
---

檢查清單：Windows Server 2003 網域基礎結構
==========================================

發佈日期: 2003 年 12 月 31 日 | 更新日期: 2004 年 7 月 1 日

##### 本頁內容

[](#ebaa)[](#ebaa)

使用下列檢查清單，有助在設定 Microsoft® Windows Server™ 2003 作業系統網域基礎結構時，正確執行所有的安全性設定與程序。

#### 設定網域原則

 
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
<img src="images/Dd548211.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">設定網域主控站 (PDC) 的外部時間來源與同步化時間。</td>
<td style="border:1px solid black;">使用 w32tm.exe 命令</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548211.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">建立增量網域原則。</td>
<td style="border:1px solid black;">例如，企業用戶端環境的 企業用戶端網域原則。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548211.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">將新建立的群組原則物件 (GPO) 連結到網域物件。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548211.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">確定 GPO 擁有最高的優先權。</td>
<td style="border:1px solid black;">GPO 應該在清單的最前面。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548211.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">將 GPO 設定為 [不可強制覆蓋]。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548211.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">將對應的用戶端環境安全性範本匯入到新建立的 GPO。</td>
<td style="border:1px solid black;">例如，企業用戶端環境的 Enterprise Client - Domain.inf。</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[回到頁首](#mainsection)
