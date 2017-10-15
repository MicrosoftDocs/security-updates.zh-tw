---
TOCTitle: 'Appendix A: Uninstalling Windows Internal Database'
Title: 'Appendix A: Uninstalling Windows Internal Database'
ms:assetid: 'f8abcf6e-b6ef-4872-bf51-1b89994700d5'
ms:contentKeyID: 18126356
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc708610(v=WS.10)'
---

Appendix A: Uninstalling Windows Internal Database
==================================================

It is not usually necessary to uninstall Windows Internal Database, which WSUS installs as the default SQL Server version. It is not possible to remove this application with **Add or Remove Programs**, and it will not be uninstalled automatically when WSUS is uninstalled. If you wish to do so, you will need to call the **msiexec** executable with the correct key for the operating system platform.

| ![](images/Cc708610.Important(WS.10).gif)重要事項                                                                                                          |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Uninstalling Windows Internal Database is not recommended, because it may affect other applications that may be using the same database instance (such as Windows SharePoint Services). |

**To uninstall Windows Internal Database**
1.  Open a command shell.

2.  Call **msiexec** with the correct key for the operating system platform.

    -   On 32-bit platforms**: msiexec /x {CEB5780F-1A70-44A9-850F-DE6C4F6AA8FB} callerid=ocsetup.exe**
    -   On 64-bit platforms: **msiexec /x {BDD79957-5801-4A2D-B09E-852E7FA64D01} callerid=ocsetup.exe**

| ![](images/Cc708610.Important(WS.10).gif)重要事項                                                                                                                                    |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| The removal of the application may not remove the default .mdb and .ldb files, which will cause a subsequent WSUS 3.0 installation to fail. These files can be deleted from the %windir%\\SYSMSI\\SSEE directory. |
