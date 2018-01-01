---
TOCTitle: 變更 Active Directory 快取設定
Title: 變更 Active Directory 快取設定
ms:assetid: '8789a7a5-2065-4fae-9104-e0a70f1f2fb6'
ms:contentKeyID: 18113013
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc747586(v=WS.10)'
---

變更 Active Directory 快取設定
==============================

登錄中的設定值會指定儲存於 Active Directory 快取的項目數。若要改善回應用戶端要求的時間，您可以修改這些設定值。如需詳細資訊，請參閱本主題前面的＜最佳化目錄服務效能＞。也可以指定儲存於快取中資訊的有效期間。

在執行 Windows Server 2003 32 位元版的電腦中，下列登錄機碼是快取項目的完整子機碼路徑：

**HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\DRMS\\1.0\\DirectoryServices**

在執行 Windows Server 2003 64 位元版的電腦中，下列登錄機碼是快取項目的完整子機碼路徑：

**HKEY\_LOCAL\_MACHINE\\SoftwareWOW6432Node\\Microsoft\\DRMS\\1.0\\DirectoryServices**

下列表格列出控制內部快取行為的項目。

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >名稱</th>
<th style="border:1px solid black;" >類型</th>
<th style="border:1px solid black;" >預設值</th>
<th style="border:1px solid black;" >描述</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">PrincipalCacheMax</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">1,000</td>
<td style="border:1px solid black;">可儲存於快取中的主體以及其電子郵件地址和其 SID 的上限數。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">PrincipalCacheExpireMinutes</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">12</td>
<td style="border:1px solid black;">主體快取資訊的有效期。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">GroupIDCacheMax</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">1,000</td>
<td style="border:1px solid black;">可儲存於快取中的群組以及其電子郵件地址和其 SID 的上限數。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">GroupIDCacheExpireMinutes</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">12</td>
<td style="border:1px solid black;">群組成員的快取資訊有效期。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">GroupMembershipCacheMax</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">1,000</td>
<td style="border:1px solid black;">可儲存於快取中的連絡人 (屬於群組的成員) 的上限數。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">GroupMembershipCacheExpireMinutes</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">12</td>
<td style="border:1px solid black;">連絡人 (屬於群組的成員) 的快取資訊有效期。</td>
</tr>
</tbody>
</table>
  
| ![](images/Cc747586.Caution(WS.10).gif)注意                         |  
|--------------------------------------------------------------------------------------------------|  
| 非正確編寫的登錄項目可能會嚴重損害您的系統。在變更登錄項目前，您應該先備份電腦中的任何重要資料。 |
  
| ![](images/Cc747586.note(WS.10).gif)附註                                                                                                                                                                               |  
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| **PrincipalCacheExpireMinutes**、**GroupIDCacheExpireMinutes**、**GroupMembershipCacheExpireMinutes** 及 **ContactMembersofGroupCacheExpireMinutes** 登錄項目還可控制資料庫伺服器的目錄服務資料庫中儲存的本機 Active Directory 快取中的快取到期日。 |
