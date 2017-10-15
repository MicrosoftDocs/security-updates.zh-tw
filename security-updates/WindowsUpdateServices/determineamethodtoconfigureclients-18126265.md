---
TOCTitle: Determine a Method to Configure Clients
Title: Determine a Method to Configure Clients
ms:assetid: 'a6c7fdf1-2256-4436-90f7-7111ba60d95d'
ms:contentKeyID: 18126265
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc708521(v=WS.10)'
---

Determine a Method to Configure Clients
=======================================

How best to configure Automatic Updates and WSUS environment options depends upon your network environment. In an Active Directory environment, you would use Group Policy. In a non-Active Directory environment, you might use the Local Group Policy object or edit the registry directly.

Administrator-defined configuration options driven by Group Policy—whether set with Group Policy in an Active Directory environment or via the registry or Local Group Policy object—always take precedence over user-defined options. When you use administrative policies to configure Automatic Updates, the Automatic Updates user interface is disabled on the target computer.

If you configure Automatic Updates to notify the user of updates that are ready to be downloaded, it sends the notification to the System log and to a logged-on administrator of the computer. You can use Group Policy to enable non-administrators to get this message. If no user with administrator credentials is logged on and you have not enabled non-administrators to get notifications, Automatic Updates waits for an administrator to log on before offering the notification.

By default every 22 hours, minus a random offset, Automatic Updates polls the WSUS server for approved updates; if any new updates need to be installed, they are downloaded. The amount of time between each detection cycle can be manipulated from 1 to 22 hours by using Group Policy.

You can manipulate the notification options as follows:

-   If Automatic Updates is configured to notify the user of updates that are ready to be installed, the notification is sent to the System log and to the notification area of the client computer.
-   When a user with appropriate credentials clicks the notification-area icon, Automatic Updates displays the available updates to install. In this case, a user with the appropriate credentials is either a logged-on administrator or a non-administrator granted appropriate credentials by means of Group Policy. The user must then click **Install**, so the installation can proceed. A message appears if the update requires the computer to be restarted to complete the update. If a restart is requested, Automatic Updates cannot detect additional updates until the computer is restarted.

If Automatic Updates is configured to install updates on a set schedule, applicable updates are downloaded and marked as ready to install. Automatic Updates notifies users having appropriate credentials via a notification-area icon, and an event is logged in the System log. This indicates that the user can install updates.

At the scheduled day and time, Automatic Updates installs the update and restarts the computer (if necessary), even if there is no local administrator logged on. If a local administrator is logged on and the computer requires a restart, Automatic Updates displays a warning and a countdown for when the computer will restart. Otherwise, the installation occurs in the background.

If it is required to restart the computer, and any user is logged on, a similar countdown dialog box is displayed, warning the logged-on user about the impending restart. You can manipulate computer restarts with Group Policy.

After the new updates are downloaded, Automatic Updates polls the WSUS server again for the list of approved packages to confirm that the packages it downloaded are still valid and approved. This means that, if a WSUS administrator removes updates from the list of approved updates while Automatic Updates is downloading updates, only the updates that are still approved are actually installed.

**In this guide**

[Configure Clients Using Group Policy](https://technet.microsoft.com/d7d4c391-f707-4257-8987-e40705e097e7)

[Configure Clients in a Non–Active Directory Environment](https://technet.microsoft.com/1776f85d-a326-4f1d-a2ed-2fdd21d590d7)
