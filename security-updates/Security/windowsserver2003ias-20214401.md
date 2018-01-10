---
TOCTitle: '檢查清單：Windows Server 2003 IAS 伺服器'
Title: '檢查清單：Windows Server 2003 IAS 伺服器'
ms:assetid: '61df44ce-df67-4bdf-9401-079524471365'
ms:contentKeyID: 20214401
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Dd548218(v=TechNet.10)'
---

檢查清單：Windows Server 2003 IAS 伺服器
========================================

發佈日期: 2003 年 12 月 31 日 | 更新日期: 2004 年 7 月 1 日

##### 本頁內容

[](#ebaa)

請使用下列檢查清單，有助在強化 Microsoft® Windows Server™ 2003 作業系統下的網際網路驗證服務 (IAS)。

#### 建立 Microsoft Active Directory® IAS 伺服器組織單位結構：

 
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
<img src="images/Dd548218.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">建立 IAS 伺服器的組織單位 (OU)。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548218.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">建立增量的 IAS 伺服器原則。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548218.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">將 GPO 連結到 IAS 伺服器組織單位。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548218.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">將對應的用戶端環境安全性範本匯入到新建立的 GPO。</td>
<td style="border:1px solid black;">  </td>
</tr>
</tbody>
</table>
  
#### 強化 IAS 伺服器的步驟：

 
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
<img src="images/Dd548218.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">安裝和設定 Windows Server 2003。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548218.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">安裝並設定 IAS 伺服器。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548218.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">套用任何所需的 Service Pack 和/或更新。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548218.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">安裝和設定病毒防護解決方案。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548218.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">依要求來安裝和設定 Microsoft Operations Manager (MOM) 代理程式或類似的監視解決方案。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548218.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">將伺服器移動到相對應的 IAS 伺服器單位組織。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548218.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">保護已知的帳號。</td>
<td style="border:1px solid black;">重新命名內建的 Administrator 帳號，指派一個複雜的密碼。 請確定 Guest 帳戶已經停用。 變更預設帳號描述。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548218.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">保護服務帳號。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548218.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">確認網域控制站之間是否已覆寫增量的 IAS 原則。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548218.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">執行 GPUPDATE.EXE /FORCE。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548218.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">重新啟動電腦。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548218.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">查看事件日誌以檢查錯誤。</td>
<td style="border:1px solid black;">  </td>
</tr>
</tbody>
</table>
  
[](#mainsection)[回到頁首](#mainsection)
