---
TOCTitle: '檢查清單：Windows XP 用戶端的軟體限制原則'
Title: '檢查清單：Windows XP 用戶端的軟體限制原則'
ms:assetid: '580f81c0-38e5-43a3-8e78-801cd7030814'
ms:contentKeyID: 20214416
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Dd548234(v=TechNet.10)'
---

檢查清單：Windows XP 用戶端的軟體限制原則
=========================================

### Overview

發佈日期: 2003 年 5 月 22 日 | 更新日期: 2006 年 4 月 13 日

##### 本頁內容

[](#ebaa)[](#ebaa)

請使用下列檢查清單，確保您有根據相關單元所述，正確地執行所有安全性設定和程序。

**設定本機群組原則物件：**

 
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
<img src="images/Dd548234.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">清查應用程式並記錄所有可執行檔。</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548234.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">記錄程式檔案位置以及相關的連結。</td>
<td style="border:1px solid black;">例如：c:\Program Files、桌面程式連結、[開始] 功能表連結。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548234.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">從資料夾執行指令檔。</td>
<td style="border:1px solid black;">例如：SA 企業 XP 用戶端 - Desktop.cmd</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548234.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">判斷指定的檔案類型。</td>
<td style="border:1px solid black;">例如：exe、vbs、ocx。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548234.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">設定原則。</td>
<td style="border:1px solid black;">先預設使用「沒有限制」，直到原則完全設定完成，然後再設定為「不允許」。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548234.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">將新建立的 GPO 連結到網域 OU 物件。</td>
<td style="border:1px solid black;"> </td>
</tr>
</tbody>
</table>
  
[](#mainsection)[回到頁首](#mainsection)
