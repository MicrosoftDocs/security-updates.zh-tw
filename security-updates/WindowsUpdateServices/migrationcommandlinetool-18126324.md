---
TOCTitle: 'Migration Command-line Tool'
Title: 'Migration Command-line Tool'
ms:assetid: 'c06eceaf-a4f6-4b74-a694-75960fdf706b'
ms:contentKeyID: 18126324
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc708569(v=WS.10)'
---

Migration Command-line Tool
===========================

WSUSutil.exe is a command-line tool that enables you to migrate from SUS to WSUS, among other things. You can find WSUSutil.exe in the Tools subfolder where you installed WSUS. By default, it appears in the following location:

*WSUS install drive*:\\Program Files\\Microsoft Windows Server Update Services\\Tools

You must be a member of the local Administrators group on the WSUS server to import approvals or content from SUS. These operations can only be run from the WSUS server itself. You can only run WSUSutil.exe on a 32-bit platform.

SUS does not have to be running to move updates or approvals. Although WSUSutil.exe allows you to move both approvals and updates, you are not required to migrate one, the other, or both. WSUSutil.exe uses HTTP to get approvals and SMB to copy updates from a remote SUS installation. To copy updates from a remote computer, this tool requires Read share permissions on the Content folder and all its subfolders.
