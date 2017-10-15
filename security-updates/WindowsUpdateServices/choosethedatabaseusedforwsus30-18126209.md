---
TOCTitle: 'Choose the Database Used for WSUS 3.0'
Title: 'Choose the Database Used for WSUS 3.0'
ms:assetid: '6f51cae4-4b1e-4a4b-81ef-cc92dd3644fd'
ms:contentKeyID: 18126209
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc708452(v=WS.10)'
---

Choose the Database Used for WSUS 3.0
=====================================

You do not need to be a database administrator or purchase database software to use WSUS. WSUS 3.0 will install Windows Internal Database if you choose to install a minimal version of SQL Server. This version of SQL Server is designed to require very little management by the WSUS administrator. (If you already have Windows Internal Database installed, WSUS will use that.) Of course, if you want more control over the database, you can also use the full version of SQL Server with WSUS.

The WSUS database stores the following types of information:

-   WSUS server configuration information
-   Metadata that describes each update
-   Information about client computers, updates, and client interaction with updates

You should not attempt to manage WSUS by accessing data directly in the database. Manage WSUS manually by using the WSUS console, or programmatically by calling WSUS APIs.

Each WSUS server requires its own database. If there are multiple WSUS servers in your environment, you must have multiple WSUS databases. WSUS does not support storing multiple WSUS databases on a SQL Server instance. The only exception is the case of a network load balanced cluster using a SQL Server failover cluster, as described in [Appendix C: Configure WSUS for Network Load Balancing](https://technet.microsoft.com/b17d7555-81fd-4e32-8e8b-92b4c7922116).

Selecting a database
--------------------

Use the following information to determine what database software is right for your organization. Once you have made a selection, see if there are any additional tasks you need to complete to set up the database software to work with WSUS. You can use database software that is 100-percent compatible with Microsoft SQL. There are two options that have been tested extensively for use with WSUS:

-   Windows Internal Database ships with WSUS 3.0. This version of SQL Server does not have a user interface or tools. Administrators are meant to interact with these products through WSUS.
-   Microsoft SQL Server 2005 is the full-featured database software from Microsoft. WSUS 3.0 requires SQL Server 2005 with Service Pack 1. If you use the full version of SQL Server, the SQL Server administrator should enable the *nested triggers* option in SQL Server. Do this before the WSUS administrator installs WSUS and specifies the database during the setup process. WSUS Setup enables the *recursive triggers* option, which is a database-specific option; however, it does not enable the *nested triggers* option, which is a server global option.

WSUS does support running database software on a computer separate from WSUS, but there are some restrictions. See [Appendix B: Configure Remote SQL](https://technet.microsoft.com/d7183651-b9fb-4288-a15f-33032c40ce2d) for more information.

Database authentication, instance, and database name
----------------------------------------------------

You cannot use SQL authentication with WSUS, which supports only Windows authentication. If you choose Windows Internal Database for the WSUS database, WSUS Setup creates an instance of SQL Server named *server*\\MICROSOFT\#\#SSEE, where *server* is the name of the computer. With either database option, WSUS Setup creates a database named SUSDB. The name of this database is not configurable.

In most cases each WSUS server will use a different SQL Server instance. One exception is the network load balancing configuration, in which multiple WSUS servers use a clustered SQL Server instance. For more information about this configuration and how to set it up, see [Appendix C: Configure WSUS for Network Load Balancing](https://technet.microsoft.com/b17d7555-81fd-4e32-8e8b-92b4c7922116).
