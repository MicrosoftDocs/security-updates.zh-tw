---
TOCTitle: Update Client
Title: Update Client
ms:assetid: '9e3f8272-a9c5-479a-8f75-b54d9f3548e6'
ms:contentKeyID: 21740987
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Dd939887(v=WS.10)'
---

Update Client
=============

WSUS requires the WSUS client, a version of Automatic Updates compatible with WSUS. Computers running Windows XP with Service Pack 2 and Windows Vista already have the WSUS client installed.

Automatic Updates client self-update feature
--------------------------------------------

Each time Automatic Updates checks the public Web site or internal server for updates, it also checks for updates to itself. This means that most versions of Automatic Updates can be pointed to the public Windows Update site and they will automatically self-update. You can also use the WSUS server to self-update the client software. For specifics, see the "Client self-update" section in [Configure IIS](https://technet.microsoft.com/a9fe03de-3bbe-4782-a570-8c35e104fabe) earlier in this guide.

The self-updating client software is available on the following operating systems:

-   Windows Vista
-   Windows Server 2008
-   Windows Server 2003
-   Windows XP with Service Pack 2
