---
TOCTitle: 'Step 7: Approve Updates'
Title: 'Step 7: Approve Updates'
ms:assetid: '91da2689-5b28-4111-8f82-8e4ab1e1d650'
ms:contentKeyID: 18126248
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc708485(v=WS.10)'
---

Step 7: Approve Updates
=======================

In this step you approve updates for any computers in the Server or the

Client computer groups. Computers in these groups will check in with the WSUS server over the next 24 hours. After this period, you can use the WSUS reporting feature to determine whether those updates have been installed.

Step 7 contains the following procedures:

-   Approve and deploy an update.
-   Check the Status of Updates report.

**To approve and deploy an update**
1.  On the WSUS console toolbar, click **Updates**. By default, the list of updates is filtered to show only Critical and Security Updates that have been approved for detection by client computers. Use the default filter for this procedure.

2.  On the list of updates, select the updates you want to approve for installation. Information about a selected update is available on the **Details** tab. To select multiple contiguous updates, press and hold down the SHIFT key while selecting; to select multiple non-contiguous updates, press and hold down the CTRL key while selecting.

3.  Under **Update Tasks**, click **Change approval**. The **Approve Updates** dialog box appears.

4.  In the **Group approval settings for the selected updates** list, click the default value in the **Approval** column for the group you intend to work with, and then click **Install.**

5.  Click **OK**.

| ![](images/Cc708485.note(WS.10).gif)附註                                                                                                                                                                                                                                                                          |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| There are many options associated with approving updates, such as setting deadlines and uninstalling updates. These are discussed in “Microsoft Windows Server Update Services Operations Guide,” which is available at the [Microsoft Web site](http://go.microsoft.com/fwlink/?linkid=41171) (http://go.microsoft.com/fwlink/?linkid=41171). |

After 24 hours, you can use the WSUS reporting feature to determine whether those updates have been installed.

**To check the Status of Updates report**
1.  On the WSUS console toolbar, click **Reports**.

2.  On the **Reports** page, click **Status of Updates**.

3.  If you want to filter the list of updates, under **View**, select the criteria you want to use, and then click **Apply**.

4.  If you want to see the status of an update by computer group and then by computer, expand the view of the update as necessary.

5.  If you want to print the Status of Updates report, under **Tasks**, click **Print report**.
