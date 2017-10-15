---
TOCTitle: Office Update Approval
Title: Office Update Approval
ms:assetid: '31b5f2b1-dd8c-49ea-bc92-51b27b7ad3c9'
ms:contentKeyID: 21740887
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Dd939819(v=WS.10)'
---

Office Update Approval
======================

If you use WSUS to update Microsoft Office on your network computers, consider the following:

-   You must use an original baseline source for Microsoft Office Administrative Install Points (AIP) to use WSUS to update Office XP and Office 2003 on client computers. If you are applying updates to the AIP, you cannot use WSUS. The two methods of applying updates are mutually exclusive. If you have applied an update to an AIP and want to roll back the AIP to an original baseline source, use the instructions found at the [Microsoft Support Web site](http://go.microsoft.com/fwlink/?linkid=63962) (http://go.microsoft.com/fwlink/?LinkId=63962).

 
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" ><img src="images/Dd939819.Important(WS.10).gif" />重要</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Administrative Install Points are relevant only to Office XP and Office 2003. They are not used with Office 2007.
</td>
</tr>
</tbody>
</table>
 

-   If you have purchased a "per user" license agreement for Office or have installed Office per user, WSUS will not update Office.
-   Users can access the public Microsoft Office Online Web site to look for updates to their Office installation through the Microsoft Office Update wizard. Using Group Policy, you might want to create policies that prevent users from getting their own Office updates from Microsoft Office Online.

For more information and troubleshooting advice, see the following Knowledge Base articles.

-   [Office 2003 updates are offered to a user even if that user has installed those updates when you use WSUS to deploy software updates and hotfixes to computers that are in your organization](http://go.microsoft.com/fwlink/?linkid=78874) (http://go.microsoft.com/fwlink/?LinkId=78874)
-   [No appropriate Microsoft Office updates are displayed when you use Microsoft Update or Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=78871) (http://go.microsoft.com/fwlink/?LinkId=78871)
-   [How to change the source for a client computer from an updated administrative installation point to an Office 2003 original baseline source or Service Pack 2](http://go.microsoft.com/fwlink/?linkid=78872) (http://go.microsoft.com/fwlink/?LinkId=78872)
