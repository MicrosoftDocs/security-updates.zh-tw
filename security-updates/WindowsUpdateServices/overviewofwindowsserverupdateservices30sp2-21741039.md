---
TOCTitle: 'Overview of Windows Server Update Services 3.0 SP2'
Title: 'Overview of Windows Server Update Services 3.0 SP2'
ms:assetid: 'ecefc27c-3ebd-49a2-81b5-4c911f5f5fbc'
ms:contentKeyID: 21741039
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Dd939931(v=WS.10)'
---

Overview of Windows Server Update Services 3.0 SP2
==================================================

You can use Windows Server Update Services (WSUS) 3.0 SP2 to manage downloading software updates from Microsoft Update and distributing them to computers in your network.

How WSUS Works
--------------

WSUS provides a management infrastructure consisting of the following:

-   Microsoft Update: the Microsoft Web site that distributes updates to Microsoft products.
-   Windows Server Update Services server: the server component that is installed on a computer running a supported operating system inside the corporate firewall. WSUS server software enables administrators to manage and distribute updates through an administrative console, which can be used to manage any WSUS server in any domain with which it has a trust relationship. A WSUS server can obtain updates either from Microsoft Update or from another WSUS server, but at least one WSUS server in the network must connect to Microsoft Update to get available updates. The administrator can decide how many WSUS servers should connect directly to Microsoft Update, based on network configuration, bandwidth, and security considerations. These servers can then distribute updates to other downstream WSUS servers.
-   Automatic Updates: the client computer component built into Windows operating systems. Automatic Updates enables both server and client computers to receive updates either from Microsoft Update or from a WSUS server.

### Software Updates

Software updates consist of two parts:

-   Update files: the actual files that are installed on client computers.
-   Update metadata: the information needed to perform the installation, which includes:
    -   Update properties: title, description, Knowledge Base article, Microsoft Security Response Center number.
    -   Applicability rules: used by Automatic Updates to determine whether or not the update is needed on a particular computer.
    -   Installation information: command-line options to apply when installing the updates.

The two parts of the update can be downloaded independently of each other. For example, if you choose not to store updates locally, only update metadata (and any applicable Microsoft Software License Terms) will be downloaded to the WSUS server; clients will get their update files directly from Microsoft Update. On the other hand, if you are storing updates locally on the WSUS server, you can either download everything at the time of synchronization, or download only the metadata during the synchronization, leaving the actual update files to be downloaded after you have approved the update.
