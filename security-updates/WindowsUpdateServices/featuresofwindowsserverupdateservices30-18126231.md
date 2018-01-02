---
TOCTitle: 'Features of Windows Server Update Services 3.0'
Title: 'Features of Windows Server Update Services 3.0'
ms:assetid: '87a8575f-9a8d-4fdd-98ac-a6d15f2831d5'
ms:contentKeyID: 18126231
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc708464(v=WS.10)'
---

Features of Windows Server Update Services 3.0
==============================================

Server-side features
--------------------

The server-side component of the WSUS solution includes the following features.

#### More updates

Microsoft Update publishes updates for the following products:

-   Windows 2000
-   Windows XP (32-bit, IA-64 and x64 Editions)
-   Windows Vista
-   Windows Server 2003
-   Windows Small Business Server 2003
-   Exchange Server 2000
-   Exchange Server 2003
-   Exchange Server 2007
-   SQL Server
-   SQL Server 2005
-   Office XP
-   Office 2003
-   Microsoft ISA Server 2004
-   Microsoft Data Protection Manager
-   Microsoft ForeFront
-   Windows Live
-   Windows Defender

At least one upstream WSUS server connects to Microsoft Update to get available updates and update information, while other downstream servers get their updates from the upstream server.

#### Specific updates can be set to download automatically

When a WSUS server downloads available updates, either from Microsoft Update or an upstream WSUS server, synchronization occurs.

Administrators can choose which updates are downloaded to a WSUS server during synchronization, based on the following criteria:

-   Product or product family (for example, Microsoft Windows Server 2003 or Microsoft Office)
-   Update classification (for example, critical updates, and drivers)
-   Language (for example, English and Japanese only)

In addition, administrators can specify a schedule for synchronization to initiate automatically.

#### Automated actions for updates determined by administrator approval

An administrator must approve every automated action to be carried out for the update.

Approval actions include the following:

-   Approve
-   Remove (this action is possible only if the update supports uninstall)
-   Decline

In addition, the administrator can enforce a deadline, a specific date and time to install or remove (uninstall) updates. The administrator can force an immediate download by setting a deadline for a time in the past.

#### E-mail notification of new updates and status reports

WSUS 3.0 can be configured to send e-mail notification of new updates and status reports. Specified recipients can receive update notifications as they arrive on the WSUS server. Status reports can be sent at specified times and intervals.

#### Ability to determine the applicability of updates before installing them

WSUS 3.0 now automatically scans updates to determine the computers on which they should be installed. Before actually planning and deploying the update for installation, the administrator can analyze the update’s impact by means of a status report that can be generated directly from the update view for a single update, a subset of updates, or all updates.

#### Targeting

Targeting enables administrators to deploy updates to specific computers and groups of computers. Targeting can be configured either on the WSUS server directly, on the WSUS server by using Group Policy in an Active Directory network environment, or on the client computer by editing registry settings.

The following are examples of targeting tasks that administrators can perform:

-   Deploying new updates to a test computer group and then evaluating the updates before distributing them to the production environment.
-   Protecting computers that run specific applications. For example, if a critical update is incompatible with an application used by only certain computers, an administrator can make sure that the update is not distributed to those computers.
-   Specifying a deadline by which an update must be installed, and then setting different deadlines for different computers or computer groups.
-   Making the same computer a member of more than one group. For example, a computer could be a member of the "Test" group and also a member of the "Special Applications" group.

#### Database options

The WSUS database stores update information, event information about update actions on client computers, and WSUS server settings.

Administrators have the following options for the WSUS 3.0 database:

-   The Windows® Internal Database database that WSUS can install during setup on Windows Server 2003.
-   An existing Microsoft SQL Server™ 2005 Service Pack 1 database.

#### Replica synchronization and reporting

WSUS enables administrators to create an update management infrastructure consisting of a hierarchy of WSUS servers. WSUS servers can be scaled out to handle any number of clients.

With replica synchronization, the administrator of the central WSUS server can create updates, target groups, and approvals that are automatically propagated to WSUS servers designated as replica servers. This means that branch office clients can get centrally approved updates from a local server without the need for a local WSUS administrator. Also, offices with a low-bandwidth link to the central server pose less of a problem, because the branch WSUS server connects only to the central WSUS server. Update status reports can be generated for all the clients of a replica server.

#### Management of multiple WSUS servers from a single console

WSUS 3.0 now allows administrators to manage a WSUS server hierarchy from a single WSUS console. The WSUS administration snap-in to the Microsoft Management Console can be installed on any computer in the network.

#### Reporting

Using WSUS reports, administrators can monitor the following activity (all reports are in a printable format and can be exported to Excel spreadsheets or Adobe .pdf files):

-   **Update status**: Administrators can monitor the level of update compliance for their client computers on an ongoing basis using Update Status reports, which can provide status for update approval and deployment per update, per computer, and per computer group, based on all events that are sent from the client computer.
-   **Computer status**: Administrators can assess the status of updates on client computers. For example, they can request a summary of updates that have been installed or are needed for a particular computer.
-   **Computer compliance status**: Administrators can view or print a summary of compliance information for a specific computer, including basic software and hardware information, WSUS activity, and update status.
-   **Update compliance status**: Administrators can view or print a summary of compliance information for a specific update, including the update properties and cumulative status for each computer group.
-   **Synchronization (or download) status**: Administrators can monitor synchronization activity and status for a given time period, and view the latest updates that have been downloaded.
-   **WSUS configuration settings**: Administrators can see a summary of options they have specified for their WSUS implementation.

#### Troubleshooting

The WSUS Management Pack allows administrators to troubleshoot WSUS infrastructure, including network connectivity, permissions, SQL connectivity, and WSUS-related services. The WSUS Management Pack exposes this information in the State view of the Microsoft Operations Manager. Administrators can get detailed information about the cause of the problem and related solutions.

#### Extensibility

A software development kit (SDK) is available to enable administrators and developers to work with the .NET-based API.

Administrators can create custom code to manage both Automatic Updates and WSUS servers. New APIs allow administrators to collect hardware and software inventories from managed devices, create approvals for installation via the **Add or Remove Programs** dialog box, and integrate WSUS management with that of other management tools, such as System Center Essentials.

Developers can create management applications to integrate with WSUS or to publish third-party updates using WSUS infrastructure.

#### Configurable communication options

Administrators have the flexibility of configuring computers to get updates directly from Microsoft Update, from an intranet WSUS server that distributes updates internally, or from a combination of both, depending on the network configuration.

Administrators can configure a WSUS server to use a custom port for connecting to the intranet or Internet, if appropriate. (The default port used by a WSUS server is port 80.) It is also possible to connect via SSL, in which case the default port is 443.

Administrators can configure proxy server settings if the WSUS server connects to the Internet through a proxy server.

#### Import and export and data migration from the command line

Administrators can import and export update metadata and content between WSUS servers. This is a necessary task in a network with limited or restricted Internet connectivity.

Administrators can seamlessly migrate their previous administrative settings, content approvals, and content from a WSUS 2.0 server to a WSUS 3.0 server. Migration can also be useful for consolidation of WSUS servers. For example, administrators can migrate approvals for specific target groups from one WSUS server to another.

#### Backup and restore

WSUS supports ntbackup for update content files and SQL Server metadata.

Client-side features
--------------------

The following features comprise the client-side component of the WSUS solution.

#### Powerful and extensible management of the Automatic Updates service

In an Active Directory service environment, administrators can configure the behavior of Automatic Updates by using Group Policy. In other cases, administrators can remotely configure Automatic Updates using registry keys through the use of a logon script or similar mechanism.

Administrator capabilities for configuring client computers include the following:

-   Configuring notification and scheduling options for users through Group Policy.
-   Configuring how often the client computer checks the update source (either Microsoft Update or another WSUS server) for new updates.
-   Configuring Automatic Updates to install updates that do not require reboots or service interruptions as soon as it finds them and not to wait until the scheduled automatic installation time.
-   Managing client computers through the Component Object Model (COM)–based API. An SDK is available.

#### Self-updating for client computers

WSUS client computers can detect from the WSUS server if a newer version of Automatic Updates is available, and then upgrade their Automatic Updates service automatically.

#### Automatic detection of applicable updates

Automatic Updates can download and install specific updates that are truly applicable to the computer. Automatic Updates works with the WSUS server to evaluate which updates should be applied to a specific client computer.

#### Under-the-hood efficiency

The Automatic Updates service works in the background so that the perceptible impact on employee productivity and network functionality is minimal.

Automatic Updates consolidates updates that require computer restarts into a single restart.

Automatic Updates eliminates the need for users in a managed environment to interact with Microsoft Software License Terms. License terms are accepted on the WSUS server by administrators on behalf of client computers.

BITS 2.0 employs delta compression to facilitate downloads that are invisible to the user. For example, after Automatic Updates downloads an update to a client computer, it will continue to monitor either the upstream WSUS server or Microsoft Update, and then download only changes in an update file to the client computer. This technology also enables efficient distribution of service packs through Automatic Updates.
