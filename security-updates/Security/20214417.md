---
TOCTitle: '檢查清單：Windows XP 用戶端的安全性設定'
Title: '檢查清單：Windows XP 用戶端的安全性設定'
ms:assetid: 'c50b6323-864c-45c9-8efb-d63be3c5cc0c'
ms:contentKeyID: 20214417
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Dd548235(v=TechNet.10)'
---

檢查清單：Windows XP 用戶端的安全性設定
=======================================

### Overview

發佈日期: 2003 年 5 月 22 日|更新日期: 2006 年 4 月 13 日

##### 本頁內容

[](#ebaa)[](#ebaa)

請使用下列檢查清單，確保您有根據相關單元所述，正確地執行所有安全性設定和程序。

**設定 Windows® XP® 的安全性設定：**

 
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
<img src="images/Dd548235.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">將桌上型電腦用戶端的電腦帳戶移動到桌上型電腦 OU。</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548235.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">將膝上型電腦用戶端的電腦帳戶移動到膝上型電腦 OU。</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548235.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">建立桌上型電腦 GPO。</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548235.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">建立膝上型電腦 GPO。</td>
<td style="border:1px solid black;">GPO 應該在清單的最前面。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548235.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">將相對的桌上型電腦用戶端環境安全性範本，匯入到桌上型電腦 GPO。</td>
<td style="border:1px solid black;">例如，企業用戶端 - 企業用戶端環境的 Desktop.inf。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548235.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">將相對的膝上型電腦用戶端環境安全性範本，匯入到膝上型電腦 GPO。</td>
<td style="border:1px solid black;">例如，企業用戶端 - 企業用戶端環境的 Laptop.inf。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548235.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">修改 [帳戶：重新命名系統管理員帳戶] 設定，以指定您在這兩個 GPO 中要使用的管理員帳戶名稱。</td>
<td style="border:1px solid black;">請參考相關的單元，以取得此設定的指引。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548235.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">修改 [帳戶：重新命名來賓帳戶名稱] 設定，以指定您在這兩個 GPO 中要使用的來賓帳戶名稱。</td>
<td style="border:1px solid black;">請參考相關的單元，以取得此設定的指引。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548235.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">連同您的法務部門一起檢閱將透過 [互動式登入：給登入使用者的訊息本文] 以及 [互動式登入：給登入使用者的訊息標題] 設定的訊息和標題。</td>
<td style="border:1px solid black;">請參考相關的單元，以取得此設定的指引。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548235.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">請檢閱其餘推薦的設定，以確保這些設定符合 貴組織的安全性目標。</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548235.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">將桌上型電腦 GPO 連結到桌上型電腦 OU。</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548235.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">將膝上型電腦 GPO 連結到膝上型電腦 OU。</td>
<td style="border:1px solid black;"> </td>
</tr>
</tbody>
</table>
  
[](#mainsection)[回到頁首](#mainsection)
