---
TOCTitle: '檢查清單：Windows Server 2003 成員伺服器基準線。'
Title: '檢查清單：Windows Server 2003 成員伺服器基準線。'
ms:assetid: '22b080be-e739-42c4-ab38-ccbe046fea23'
ms:contentKeyID: 20214395
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Dd548212(v=TechNet.10)'
---

檢查清單：Windows Server 2003 成員伺服器基準線。
================================================

發佈日期: 2003 年 12 月 31 日 | 更新日期: 2004 年 7 月 1 日

##### 本頁內容

[](#ebaa)[](#ebaa)

使用下列檢查清單，有助在建立 Microsoft® Windows Server™ 2003作業系統成員伺服器基準線時，正確執行所有的安全性設定與程序。

#### 設定成員伺服器基準線原則：

 
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
<img src="images/Dd548212.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">建立成員伺服器組織單位 (OU)。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548212.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">建立成員伺服器基準線原則 (MSBP)。</td>
<td style="border:1px solid black;">例如，企業用戶端環境的企業用戶端成員伺服器基準線原則。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548212.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">將 MSBP 連結到成員伺服器組織單位。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548212.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">將適當的安全性範本匯入到新建立的 MSBP。</td>
<td style="border:1px solid black;">例如，企業用戶端環境的 Enterprise Client Domain.inf。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548212.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">設定網域控制站基準線原則 (DCBP) 內的其他終端機服務設定。</td>
<td style="border:1px solid black;">MSBP 內的路徑： Computer Configuration\Administrative Templates\Windows Components\Terminal Services\Encryption and Security。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548212.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">新增指定網域的群組到「使用者指派權限」。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548212.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">停用 MSBP 內的錯誤報告。</td>
<td style="border:1px solid black;">MSBP 內的路徑： Computer Configuration\Administrative Templates\System\Error Reporting</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[回到頁首](#mainsection)
