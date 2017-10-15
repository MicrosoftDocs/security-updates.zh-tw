---
TOCTitle: '檢查清單：Windows Server 2003 IIS 伺服器'
Title: '檢查清單：Windows Server 2003 IIS 伺服器'
ms:assetid: '80db96f8-54a0-4276-b7c6-79282b9a0280'
ms:contentKeyID: 20214400
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Dd548217(v=TechNet.10)'
---

檢查清單：Windows Server 2003 IIS 伺服器
========================================

發佈日期: 2003 年 12 月 31 日 | 更新日期: 2004 年 7 月 1 日

##### 本頁內容

[](#ebaa)

使用下列檢查清單，有助在強化 Microsoft® Windows Server™ 2003 作業系統網際網路資訊服務 (IIS) 時，正確執行所有的安全設定與程序。

#### 設定 Microsoft Active Directory® IIS 伺服器組織單位結構：

 
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
<img src="images/Dd548217.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">建立 IIS 伺服器組織單位 (OU)。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548217.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">建立增量 IIS 伺服器原則。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548217.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">連結 GPO 到 IIS 伺服器組織單位。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548217.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">將對應的用戶端環境安全性範本匯入到新建立的 GPO。</td>
<td style="border:1px solid black;">例如，企業用戶端環境的 Enterprise Client — IIS Server.inf。</td>
</tr>
</tbody>
</table>
  
#### 強化 IIS 伺服器的步驟：

 
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
<img src="images/Dd548217.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">安裝和設定 Windows Server 2003。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548217.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">安裝和設定 IIS 服務：<br />
<img src="images/Dd548217.mnp_checkbox(zh-tw,TechNet.10).gif" /> 只安裝必要的 IIS 元件。<br />
<img src="images/Dd548217.mnp_checkbox(zh-tw,TechNet.10).gif" /> 只啟用基本網頁服務延伸模組。<br />
<img src="images/Dd548217.mnp_checkbox(zh-tw,TechNet.10).gif" /> 放置內容在固定磁碟區。<br />
<img src="images/Dd548217.mnp_checkbox(zh-tw,TechNet.10).gif" /> 設定 NTFS 使用權限。<br />
<img src="images/Dd548217.mnp_checkbox(zh-tw,TechNet.10).gif" /> 設定 IIS 網站使用權限。<br />
<img src="images/Dd548217.mnp_checkbox(zh-tw,TechNet.10).gif" /> 設定 IIS 記錄。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548217.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">套用任何所需的 Service Pack 和/或更新。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548217.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">安裝和設定病毒防護解決方案。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548217.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">依要求來安裝和設定 MOM 代理程式或類似的監視解決方案。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548217.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">移動適當伺服器到對應的 IIS 伺服器組織單位。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548217.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">保護已知的帳號。</td>
<td style="border:1px solid black;">重新命名內建的 Administrator 帳號，指派一個複雜的密碼。 請確定 Guest 帳戶已經停用。 變更預設帳號描述。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548217.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">保護服務帳號。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548217.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">考慮是否執行 IPSec 篩選器。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548217.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">驗證網域控制站之間是否已覆寫增量 IIS 伺服器原則。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548217.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">執行 GPUPDATE.EXE /FORCE。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd548217.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">重新啟動電腦。</td>
<td style="border:1px solid black;">  </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd548217.mnp_checkbox(zh-tw,TechNet.10).gif" /></td>
<td style="border:1px solid black;">查看事件日誌以檢查錯誤。</td>
<td style="border:1px solid black;">  </td>
</tr>
</tbody>
</table>
  
[](#mainsection)[回到頁首](#mainsection)
