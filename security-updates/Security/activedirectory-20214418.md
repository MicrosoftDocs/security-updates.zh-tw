---
TOCTitle: '檢查清單：設定 Active Directory 網域基礎結構'
Title: '檢查清單：設定 Active Directory 網域基礎結構'
ms:assetid: '81a670ed-daa8-4c1b-a528-200eec2d2c5d'
ms:contentKeyID: 20214418
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Dd548236(v=TechNet.10)'
---

檢查清單：設定 Active Directory 網域基礎結構
============================================

### Overview

發佈日期: 2003 年 5 月 22 日|更新日期: 2006 年 4 月 13 日

##### 本頁內容

[](#eaaa)[](#eaaa)

請使用下列檢查清單，確保您有根據相關單元所述，正確地執行所有安全性設定和程序。

**設定網域原則：**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" ></th>
<th style="border:1px solid black;" >步驟</th>
<th style="border:1px solid black;" >參考：</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548236.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">請確認網域控制站的系統時間已經同步化。</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548236.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">建立增量網域原則</td>
<td style="border:1px solid black;">例如，企業用戶端 - 企業用戶端環境的網域原則。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548236.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">將新建立的 GPO 連結到網域物件。</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548236.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">確定 GPO 擁有最高的優先權</td>
<td style="border:1px solid black;">GPO 應該在清單的最前面。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548236.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">將 GPO 設定為 [不可強制覆蓋]。</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548236.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">將相對的用戶端環境安全性範本匯入到新建立的 GPO。</td>
<td style="border:1px solid black;">例如，企業用戶端 - 企業用戶端環境的 Domain.inf。</td>
</tr>
</tbody>
</table>
  
**建立 Windows XP OU 結構：**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" ></th>
<th style="border:1px solid black;" >步驟</th>
<th style="border:1px solid black;" >參考：</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548236.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">建立 Windows XP OU。</td>
<td style="border:1px solid black;">這可以是在部門或公司 OU 之下。這是所有 Windows® XP® 電腦的父 OU。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548236.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">建立 Windows XP 安全的使用者 OU。</td>
<td style="border:1px solid black;">這可以是在部門或公司 OU 之下。這應該與 Windows XP OU 在同一階層。這是儲存所有 Windows XP 使用者帳戶的 OU。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548236.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">將桌上型電腦 OU 建立為 Windows XP OU 的子項。</td>
<td style="border:1px solid black;">這是包含 Windows XP 桌上型電腦帳戶的 OU。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548236.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">將膝上型電腦 OU 建立為 Windows XP OU 的子項。</td>
<td style="border:1px solid black;">這是包含 Windows XP 膝上型電腦帳戶的 OU。</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[回到頁首](#mainsection)
