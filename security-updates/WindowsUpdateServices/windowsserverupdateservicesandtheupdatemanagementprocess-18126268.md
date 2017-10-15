---
TOCTitle: Windows Server Update Services and the Update Management Process
Title: Windows Server Update Services and the Update Management Process
ms:assetid: '974d08bc-7930-42c3-b6bf-c8e2005e1bdc'
ms:contentKeyID: 18126268
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc708499(v=WS.10)'
---

Windows Server Update Services and the Update Management Process
================================================================

This Microsoft-recommended approach to the update management process consists of an ongoing set of four phases, as illustrated in the following figure. It is essential to repeat the update management process on an ongoing basis, as new updates become available that can enhance and protect the production environment.

Following are the goals of each phase, and examples of how administrators can use WSUS features to ensure success during each of the four phases of the process. It is important to note that many of the features can be employed in more than one phase.

![](images/Cc708499.dfdf34ec-7b30-4462-b807-e10a7347b771(WS.10).gif)
1. Assess
---------

The administrator’s goals for the Assess phase are:

-   To understand potential threats to the production environment.
-   To set up a production environment that will support update management for both routine and emergency scenarios.

Although it is the first step, the Assess phase is essentially an ongoing process. For example, administrators have to assess how many servers and client computers they need to update, what their storage and network bandwidth requirements are, and what timeframe is acceptable to deploy an average update. They also have to determine what platforms, products, and languages they want to update. Based on these factors, they can determine the most efficient topology for scaling out their WSUS components. WSUS provides numerous options for setting up WSUS components, including the ability to store update content locally on WSUS servers or download content on demand from Microsoft Update. Administrators can also configure Automatic Updates to download and install missing updates on a computer automatically. WSUS provides options for managing client computers in both Active Directory and non–Active Directory environments.

WSUS provides standardized aggregate reports that administrators can run on an ongoing basis. These reports provide comprehensive information about all activity in the WSUS implementation including information about updates that have been synchronized to a WSUS server, and which updates are installed or are missing from each computer.

2. Identify
-----------

The administrator’s goals for the Identify phase are:

-   To discover new updates in a convenient manner.
-   To determine whether updates are relevant to the production environment.
-   To determine update priority.

WSUS enables administrators to determine which types of updates to synchronize from Microsoft Update. Administrators can also set the synchronization schedule.

To determine whether an update is relevant to the production environment, administrators can look at the properties of an update. They can then approve an update for a “detect-only” action that enables them to determine how many computers need the update and how the deployment of the update would impact the network before installation of the update in the production environment.

3. Evaluate and Plan
--------------------

The administrator’s goals for the Evaluate and Plan phase are:

-   To test updates in an environment that is separate from but resembles the production environment.
-   To determine whether business-critical systems and applications could be compromised.
-   To determine the tasks necessary to deploy updates into production, plan the update releases, build the releases, and then conduct acceptance testing of the releases.

When evaluating updates in a test environment, administrators can run many of the WSUS features they would be using in the actual deployment. This includes setting the criteria and schedule for automatically synchronizing their WSUS servers, creating computer groups, and then targeting updates for those groups by approving updates for detect-only and approving for install. During and after testing, administrators can use the standardized reports that WSUS provides to monitor the success of their test update installations.

When evaluating updates in a test environment, WSUS features enable the administrators to prepare their test systems and evaluate their results with minimal oversight. By creating a computer group of test computers, and auto-approving updates for download and install by product, language, and other classifications, administrators can implement automated testing for various types of updates. During and after testing, administrators can use WSUS standardized or custom reports to validate installed updates correlated with test results to make download and install approval and timing decisions for the production environment.

4. Deploy
---------

The administrator’s goals for the Deploy phase are:

-   To test, approve, and schedule update installations.
-   To review the process after the deployment is complete.

To survey the production environment to ensure that it can handle updates before they are deployed, WSUS enables administrators to review the properties for an update and use the scan or detect-only feature to determine its impact before it is installed. Administrators can then specify target groups of computers and then approve deployment actions for updates to those groups. To establish the order in which updates are rolled out into production, administrators can use WSUS to create the upstream and downstream WSUS server configuration that is the most efficient, based on their network and staffing resources. In addition, administrators can configure how client computers communicate with WSUS servers or Microsoft Update by using Group Policy or by managing servers or client computers extensibly through the API. The administrator can then use reporting to determine the success of the update deployment by computer or target group.
