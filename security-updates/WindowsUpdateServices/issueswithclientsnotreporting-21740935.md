---
TOCTitle: Issues with Clients Not Reporting
Title: Issues with Clients Not Reporting
ms:assetid: '6bcc207a-4e3c-4063-afa4-fac6b4c620e7'
ms:contentKeyID: 21740935
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Dd939857(v=WS.10)'
---

Issues with Clients Not Reporting
=================================

If you have configured clients for a particular WSUS server, but they have not reported over a period of days, use the following procedures to isolate and repair the problem.

Troubleshooting client not reporting issues
-------------------------------------------

### Check the HTTP hotfix

Some clients have been affected by a known issue with Windows Server 2003 http.sys and IIS. In some cases this transient issue will prevent clients from checking in, because they receive incorrect responses from the server after a number of attempts. Further information about the issue can be found at [FIX: IIS 6.0 may send an "HTTP 100 Continue" response in the middle of the response stream when you send a POST request](http://go.microsoft.com/fwlink/?linkid=80715) (http://go.microsoft.com/fwlink/?LinkId=80715).

 
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" ><img src="images/Dd939857.note(WS.10).gif" />備註</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Failure of clients to contact the server is not related to compression. Administrators should not disable IIS compression, because allowing noncompressed data can increase network traffic and server load, while reducing the number of clients that can be served effectively.
</td>
</tr>
</tbody>
</table>
 

### Troubleshoot client connectivity

Ensure that the client connection to the WSUS server is working properly.

**To troubleshoot client connectivity**
1.  Open a command window.

2.  Contact the WSUS server: **ping***WSUSServerName*

3.  Contact the WSUS HTTP server. Open Internet Explorer and in the Address bar type: **http://***WSUSServerName***:***portNumber* where *WSUSServerName* is the name of the WSUS server, and *portNumber* is the port that has been configured for it (for example, 80 for HTTP, 443 for SSL, and 8530 for a custom port).

4.  Verify the existence of the self-update tree. In an Internet Explorer Address bar type **http://***WSUSServerName*/**selfupdate/wuident.cab**

5.  If the WSUS server is functioning properly, you should see a **File Download** window asking you whether to open or save the file. Close the window.

 
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" ><img src="images/Dd939857.note(WS.10).gif" />備註</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">If you do not see the <strong>File Download</strong> window, make sure that the client self-update tree has been configured properly. For more information, see <a href="https://technet.microsoft.com/0e9c0f6a-1039-4673-b5ac-ba5da88ea1d1">Issues with Client Self-Update</a>.
</td>
</tr>
</tbody>
</table>
 

### Troubleshoot the Automatic Update client

Ensure that the Automatic Update client has been configured correctly.

**To troubleshoot the Automatic Update client**
1.  Open a command window.

2.  Type:
    **reg query HKLM\\SOFTWARE\\Policies\\Microsoft\\Windows\\WindowsUpdate**

    You should see output like the following if the client has been configured to get its updates from a WSUS server:

    
        ```
    You should see output similar to the following if Automatic Update is functioning, but the client has not been configured to get its updates from a WSUS server:

    
        ```
    If the query returns the error, "The system was unable to find the specified registry key or value," Automatic Update has not been configured on this computer.

    If the output from step 2 above contains values for WUServer and WUStatusServer, try to contact the WSUS server listed in these values.

3.  Open Internet Explorer and in the Address bar type **http://***WUServer*
    where *WUServer* stands for the value in the output from step 2.

    You should see an "Under Construction" page if the *WUServer* value is valid. If it is not, you will get an HTTP error of some kind.

### Reset the Automatic Update client

It can be a good idea to reset the Automatic Update client if you are experiencing difficulty with contacting the WSUS server with the wuauclt utility. For more information about wuauclt, see [Appendix H: The wuauclt Utility](https://technet.microsoft.com/7cc1c5f9-5678-4bb4-a7a6-18939dcc120c).

**To reset the Automatic Update client**
1.  Open a command window.

2.  Type **wuauclt.exe /resetauthorization /detectnow**

3.  Wait 10 minutes for the detection cycle to finish.
