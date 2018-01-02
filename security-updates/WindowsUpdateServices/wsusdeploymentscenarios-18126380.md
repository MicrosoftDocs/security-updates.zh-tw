---
TOCTitle: WSUS Deployment Scenarios
Title: WSUS Deployment Scenarios
ms:assetid: 'fd378729-0893-42cf-a2a9-c8dc6ee2dad9'
ms:contentKeyID: 18126380
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc708628(v=WS.10)'
---

WSUS Deployment Scenarios
=========================

WSUS is flexible enough to meet the update management needs of a wide range of organizations — from small businesses with dial-up connectivity to the largest businesses with thousands of users distributed across multiple sites. Depending on the size of the organization, its location, and its connectivity infrastructure, administrators can determine the most efficient way to scale out their WSUS servers — this might be one or many WSUS servers.

In this section, you can learn more about the common scenarios for deploying WSUS components in small, medium, and restricted networks.

Single WSUS Server (Small-Sized or Simple Network)
--------------------------------------------------

In a single WSUS server scenario, administrators can set up a server running WSUS inside their corporate firewall, which synchronizes content directly with Microsoft Update, and distributes updates to client computers, as shown in the following figure.

![](images/Cc708628.f243221a-3e52-47f3-b615-6fda4ffbbf4c(WS.10).gif)

Multiple WSUS Servers (Medium-Sized or More Complex Network)
------------------------------------------------------------

The following are common scenarios for deploying WSUS components in a medium-sized or more complex network.

#### Multiple Independent WSUS Servers

Administrators can deploy multiple servers that are configured so that each server is managed independently and so that each server synchronizes its content from Microsoft Update, as shown in the following figure.

![](images/Cc708628.30559d49-ce7a-483c-b0b3-7b66f479391e(WS.10).gif)

The deployment method in this scenario would be appropriate for situations in which different local area network (LAN) or wide area network (WAN) segments are managed as separate entities (for example, a branch office). It would also be appropriate in cases where one server running WSUS is configured to deploy updates only to client computers running a certain operating system (such as Windows 2000), while another server is configured to deploy updates only to client computers running another operating system (such as Windows XP). In these situations, the two servers would not need to synchronize content.

#### Multiple Internally Synchronized WSUS Servers

Administrators can deploy multiple servers running WSUS that synchronize all content within their organization’s intranet. In the following figure, only one server is exposed to the Internet. In this configuration, this is the only server that downloads updates from Microsoft Update. This server is set up as the upstream server — the source to which the downstream server synchronizes. When applicable, servers can be located throughout a geographically dispersed network to provide the best connectivity to all client computers.

![](images/Cc708628.3bdd2c72-270a-4109-9703-06adc6467061(WS.10).gif)

Disconnected WSUS Servers (Limited or Restricted Internet Connectivity)
-----------------------------------------------------------------------

If corporate policy or other conditions limit computer access to the Internet, administrators can set up an internal server running WSUS, as illustrated in the following figure. In this example, a server is created that is connected to the Internet but is isolated from the intranet. After downloading, testing, and approving the updates on this server, an administrator would then export the update metadata and content to a CD, and then, from the CD, import the update metadata and content to servers running WSUS within the intranet. Although the following figure illustrates this model in its simplest form, it could be scaled to any-size deployment.

![](images/Cc708628.970fd502-ce48-4a7b-a0f4-7a7c6eb5b36a(WS.10).gif)
