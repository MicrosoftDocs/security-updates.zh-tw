---
TOCTitle: 確保 Windows Small Business Server 2003 網路的安全
Title: 確保 Windows Small Business Server 2003 網路的安全
ms:assetid: '003658e1-2776-4d48-b810-199e55d4a648'
ms:contentKeyID: 20214542
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc700836(v=TechNet.10)'
---

確保 Windows Small Business Server 2003 網路的安全
==================================================

### Overview

發佈日期: 2003 年 5 月 22 日 | 更新日期: 2006 年 4 月 13 日

##### 本頁內容

[](#eoaa)[簡介](#eoaa)
[](#enaa)[開始之前](#enaa)
[](#emaa)[驗證您的拓撲及防火牆設定](#emaa)
[](#elaa)[設定存取安全的本機路由器](#elaa)
[](#ekaa)[在執行 Windows Small Business Server 2003 的電腦上，設定網路、防火牆、網頁及電子郵件服務](#ekaa)
[](#ejaa)[保持您的軟體在最新狀態](#ejaa)
[](#eiaa)[執行強性密碼](#eiaa)
[](#ehaa)[設定本機網路的遠端存取](#ehaa)
[](#egaa)[驗證使用者只有必要的權限](#egaa)
[](#efaa)[變更內建 Administrator 帳戶的帳戶名稱](#efaa)
[](#eeaa)[設定執行 Windows Small Business Server 2003 電腦的安全性](#eeaa)
[](#edaa)[執行防毒解決方案](#edaa)
[](#ecaa)[升級用戶端電腦](#ecaa)
[](#ebaa)[監視執行 Windows Small Business Server 2003 電腦上的安全性問題](#ebaa)
[](#eaaa)[相關資訊](#eaaa)

### 簡介

本文件將協助您為 Microsoft® Windows® Small Business Server 2003 網路設定更高的安全性。完成本文件的工作將協助保護您本機網路的可用性、完整性與私密性。本文件所包含可協助您確保您網路安全性的任務如下：

-   驗證您的拓撲與防火牆設定

-   設定安全存取的本機路由器

-   在執行 Windows Small Business Server 2003 的電腦上，設定網路、防火牆、網頁及電子郵件服務

-   保持您的軟體在最新狀態

-   執行強性密碼

-   設定本機網路的遠端存取

-   驗證使用者只有必要的權限

-   變更內建 Administrator 帳戶的帳戶名稱

-   確保執行 Windows Small Business Server 2003 電腦的安全性

-   實作防毒解決方案

-   將用戶端電腦升級

-   監視執行 Windows Small Business Server 2003 電腦上的安全性問題

除了本文所描述的確保您 Windows Small Business Server 網路的方式之外，在「安裝時」，便會預設很多安全性功能。如需關於「Windows Small Business Server 2003 安裝」預設設定值的更多資訊，請造訪 Microsoft 網站 [http://go.microsoft.com/fwlink/?LinkId=20122](http://go.microsoft.com/fwlink/?linkid=20122) 中《[Windows Small Business Server 2003 Getting Started Guide (英文)](http://go.microsoft.com/fwlink/?linkid=20122)》的＜Appendix D＞。

**重要：**本文件所包含的所有逐步指引是使用在您安裝作業系統時，就預設會出現的「開始」功能表，而發展出來的。如果您已經修改了「開始」功能表，這些步驟可能會有點不一樣。

[](#mainsection)[回到頁首](#mainsection)

### 開始之前

本文件假設您已經完成了包含「待辦清單」的「Windows Small Business Server 2003 安裝」。「待辦清單」會出現在「安裝」的最後，並且是用來完成設定 Windows Small Business Server 2003。如果您沒有完成所有「待辦清單」上的工作，本文件將協助您完成這些設定您執行 Windows Small Business Server 2003 電腦安全性的工作。如果您已經完成所有「待辦清單」上的工作，本文件將協助您驗證您使用的是維護您網路安全的選項。

**注意：**若要返回「待辦清單」，請按一下 \[開始\]，再按一下 \[伺服器管理\]。在主控台樹狀目錄中，按一下 \[待辦清單\]。

[](#mainsection)[回到頁首](#mainsection)

### 驗證您的拓撲及防火牆設定

如果您在 Windows Small Business Server 2003 使用的是寬頻 (高速) 網際網路連線，如果您有協助您保護本機網路的防火牆，實體拓撲 (您網路上裝置的實體配置) 一般來說會受到較好的保護。防火牆是設計來避免您本機網路的未授權存取。

使用下面的範例圖，識別 Windows Small Business Server 2003 網路的拓撲，然後驗證您拓撲的防火牆是否在正確的位置。

**注意：**如果您是撥接連線到網際網路，請參閱＜在執行 Windows Small Business Server 2003 的電腦上，設定網路、防火牆、網頁及電子郵件服務＞一節。它將說明如何啟用執行 Windows Small Business Server 2003 電腦上的防火牆。

基本上，有兩種寬頻拓撲：

-   一個使用 Windows Small Business Server 2003 提供的內部防火牆。這個拓撲在伺服器裡有兩張網路介面卡。

-   另一個使用外部防火牆。這個拓撲在伺服器上有一個路由器與一張網路介面卡。

#### 使用 Windows Small Business Server 2003 提供的外部防火牆

若要在寬頻連線使用 Windows Small Business Server 2003 提供的防火牆，執行 Windows Small Business Server 2003 的電腦必須使用兩張網路介面卡。這樣的情形下，您的拓撲會以下列方式呈現：

![](images/Cc700836.sec_sbs2003_network_01(zh-tw,TechNet.10).jpg)
如果您正在使用 Windows Small Business Server 2003 提供的內部防火牆來防止本機網路有未經授權的存取，但是您的拓撲反映的與範例圖不一樣，那麼您就必須修正相關設定。不然的話，Windows Small Business Server 2003 提供的內部防火牆將不會保護您的本機網路。

##### 需求

-   執行 Windows Small Business Server 2003 的電腦必須使用兩張網路介面卡。一張網路介面卡連線到本機網路，另一張使用網際網路連線裝置連線到網際網路。如果您沒有兩張網路介面卡，您必須使用下一節所描述的外部防火牆，或是安裝第二張網路介面卡。

    **注意：**即使您在執行 Windows Small Business Server 2003 用寬頻連線，而且有兩張網路介面卡，您還是可以使用外部防火牆。這樣的情形下，您可以使用 Windows Small Business Server 2003 提供的防火牆，或是路由器的防火牆，或者兩者都使用。如果您正在使用兩種防火牆，請確保您已將路由器設定為如＜設定存取安全的本機路由器＞一節中所討論的設定。

-   您必須以 Domain Admins 安全性群組成員的身份登入到執行 Windows Small Business Server 2003 的電腦。

-   這個程序假設您已經使用「設定電子郵件及網際網路連線精靈」連線到網際網路。如果您還沒有執行精靈，請依下列精靈指示說明完成它。當您找到 \[寬頻連線類型\] 頁面，請參閱下列程序的步驟 5 以取得關於如何完成網頁的更多資訊。如果您需要協助完成精靈，請按一下精靈頁面上的 \[其他資訊\]。

<!-- -->

-   **若要執行設定電子郵件及網際網路連線精靈**

    1.  按一下 \[開始\]，再按一下 \[伺服器管理\]。

    2.  在主控台樹狀目錄裡，按一下 \[網際網路及電子郵件\]。

    3.  在詳細資料窗格中，按一下 \[連線到網際網路\]。會出現「設定電子郵件及網際網路連線精靈」(CEICW)。

    4.  在 \[連線類型\] 的網頁上，確定 \[寬頻\] 已選取。

    5.  請在 \[寬頻連線類型\] 網頁上，確定 \[直接寬頻連線\] 已選取。如果您正在使用執行 Windows Small Business Server 2003 電腦上的防火牆與路由器上的防火牆，請確定 \[有 IP 位址的本機路由器裝置\] 已選取。

    6.  依照指示說明完成精靈。

    7.  在精靈的最後，如果您還沒有啟用密碼原則，在網路上使用強性密碼，請加以啟用。強烈建議您按一下 \[是\]，啟用密碼原則。如需關於如何啟用密碼原則的詳細資訊，請參閱＜執行強性密碼＞一節。

#### 使用外部防火牆

如果您在執行 Windows Small Business Server 2003 的電腦上只有一張網路介面卡，您的拓撲會以下列方式呈現：

![](images/Cc700836.sec_sbs2003_network_02(zh-tw,TechNet.10).jpg)
如果您正在使用外部防火牆 (有可能與您的本機路由器是同一個裝置) 來防止本機網路發生來自網際網路的未授權存取情況，而且執行 Windows Small Business Server 2003 的電腦只使用一張網路介面卡，您的拓撲就應該會與範例圖相同，否則，您就必須修正設定值。網路拓撲設定不正確，會導致外部防火牆無法保護本機網路。

##### 需求

-   執行 Windows Small Business Sever 2003 的電腦使用一張網路介面卡連線到網際網路及本機網路。如果它使用的是兩張網路介面卡，而您使用的是外部防火牆，那麼您的拓撲就會與前一節中的描述相似。

-   若要防止您的本機網路有未授權存取，請您新增一個外部防火牆，或是由網際網路連線裝置提供防火牆服務。在這個拓撲裡，您不能夠使在執行 Windows Small Business Server 2003 的電腦上使用防火牆，因為這個電腦並不是網際網路與用戶端電腦的閘道。如果您想使用防火牆，請您在執行 Windows Small Business Server 2003 的電腦上安裝第二張網路介面卡，並且使用前一節所描述的拓撲。

-   您必須用 Windows Small Business Server 網路需要的設定值，設定本機網路的外部防火牆。如需更多資訊，請參閱＜在執行 Windows Small Business Server 2003 的電腦上，設定網路、防火牆、網頁及電子郵件服務＞一節。若您變更了網路的拓撲，請依照＜若要執行設定電子郵件及網際網路連線精靈＞的程序，更新您的設定值。

[](#mainsection)[回到頁首](#mainsection)

### 設定存取安全的本機路由器

如果您正在使用本機路由器連線到網際網路，而且這個裝置提供無線網路或防火牆功能 (或兩者都有)，請確保這個裝置設定正確，以協助設定您本機網路的安全性。請考慮採取下列步驟：

-   在路由器上設定無線存取點的安全性

-   在路由器上驗證防火牆設定

#### 在路由器上設定無線存取點的安全性

如果路由器提供無線網路存取點 (也稱為基座)，而您的網路上並沒有無線裝置，停用存取點可以協助您消除本機網路的未授權存取。如果您在網路上有無線裝置，您必須考慮設定存取點，如此它才會安全。這將協助您避免未授權的使用者藉由連線到您的無線存取點而存取您的本機網路。

-   **若要停用路由器上的無線存取點**

    1.  檢查路由器的製造商說明文件。如果路由器沒有無線存取點，請跳到＜在路由器上驗證防火牆設定＞一節。

    2.  如果路由器有無線存取點，但是網路上沒有裝置 (如筆記型電腦) 使用它，請停用路由器上的無線存取點。如需詳細資訊，請檢查您的製造商說明文件。在停用無線存取點後，請跳到＜在路由器上驗證防火牆設定＞一節。

<!-- -->

-   **若要協助設定路由器上的無線存取點的安全性。**

    1.  藉由要求存取管理功能密碼 (通常是管理路由器的網頁)，協助設定路由器的安全性。這個密碼必須是強性密碼。而且，它不能是由製造商所提供的預設密碼。除此之外，在安全的位置存取您的密碼記錄。如需關於強性密碼的詳細資訊，請參閱＜執行強性密碼＞一節。

    2.  啟用您無線路由器支援的安全性通訊協定。例如，啟用 802.1x 授權，或是「有線等位私密 (Wired Equivalent Privacy，WEP)」。

        -   如果您的路由器支援 802.1x 驗證，請加以啟用。802.1x 是無線本機區域的安全性通訊協定，可以將透過無線電波從無線裝置傳輸到另一個無線裝置的資料加密，它是比「有線等位私密 (WEP)」更新更強的安全性通訊協定。如需關於設定 802.1x 驗證的詳細資訊，請看路由器的製造商說明文件。

        -   啟用 WEP，WEP 是無線本機區域網域的安全性通訊協定。WEP 協助進行資料加密，而這些資料將透過無線電波從無線裝置傳輸到另一個無線裝置。設定 WEP 時，您應該手動設定祕密鑰匙 (在無線裝置與存取點中加密資料的鑰匙)，而不是使用在無線裝置上自動設定的祕密鑰匙。除此之外，您應該要使用最長、可能的鑰匙長度。如需關於設定 WEP 的詳細資訊，請參閱路由器的製造商說明文件。

    3.  啟用「媒體存取控制」(Media Access Control，MAC) 篩選。MAC 位址用來識別網路上每個網路上的單一位址。藉由識別每個您本機網路上的無線網路上的 MAC 位址，您可以用 MAC 位址的清單，設定無線存取點是否被允許存取其他網路。

        1.  識別 MAC 每個本機網路上網路卡的 MAC 位址。在執行 Windows XP 或 Windows 2000 Professional 的電腦上，按一下 \[開始\]，再按一下 \[執行\]，再鍵入 **Cmd**。在命令提示字元裡，鍵入 **IPconfig /all**。

        2.  在顯示無線網路連線的區段，記錄 \[實體位址\]。您將會使用這個位址設定路由器上的 MAC 篩選。

        3.  依照路由器製造商的說明文件設定 MAC 篩選。

        **注意：**在您啟用 MAC 之後，每次從本機網路新增或移除一個無線裝置時，您都需要更新 MAC 位址的清單。

#### 在路由器上驗證防火牆設定

在執行 Windows Small Business Server 的電腦上，允許網路傳輸通過防火牆上的連接埠號，並只限存取已知服務，以協助保護您的網路。這些連接埠是在執行 Windows Small Business Server 2003 的電腦上，當您完成「待辦清單」上的「連線到網際網路」工作 (這個工作會開啟「設定電子郵件及網際網路連線精靈」) 時，自動設定的。

**注意：**開啟連接埠號也就是在一些路由器製造商的說明文件中的連接埠轉送功能。

##### 需求

-   存取您的路由器的管理功能 (通常是您管理路由器的網頁)。如需關於如何存取管理功能的資訊，請參閱您路由器的製造商說明文件。

-   如果您並沒有完成「待辦清單」上「連線到網際網路」的工作 (這個工作將會開啟「電子郵件及網際網路連線精靈」)，您在完成下列程序前，應該先完成。如需關於如何完成精靈的詳細資訊，請參閱＜在執行 Windows Small Business Server 2003 的電腦上，設定網路、防火牆、網頁及電子郵件服務＞一節。

<!-- -->

-   **若要在路由器上驗證防火牆設定**

    1.  在下列表格中，使用「設定電子郵件及網際網路連線精靈」清單，檢視可在執行 Windows Small Business Server 2003 的電腦上設定的服務及相關連接埠號。

    2.  判定使用者是否正在使用這項服務。如果使用者並沒有在使用這項服務，請考慮封鎖 (而不是允許) 路由器上防火牆的輸入連接埠。

        **服務及 TCP 埠號**

 
        <table style="border:1px solid black;">
        <colgroup>
        <col width="33%" />
        <col width="33%" />
        <col width="33%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th style="border:1px solid black;" >服務</th>
        <th style="border:1px solid black;" >TCP 埠號</th>
        <th style="border:1px solid black;" >輸入存取的建議</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td style="border:1px solid black;">電子郵件</td>
        <td style="border:1px solid black;">25</td>
        <td style="border:1px solid black;">如果您是使用 Exchange 接收網際網路電子郵件，建議允許這項功能。</td>
        </tr>
        <tr class="even">
        <td style="border:1px solid black;">網頁伺服器</td>
        <td style="border:1px solid black;">80 (對您網站的 HTTP 要求是必要的) 及 443 (在使用 Secure Sockets Layer (SSL)(可設定您伺服器及網頁瀏覽器通訊的安全性) 對 HTTPS 要求是必要的)。</td>
        <td style="border:1px solid black;">允許網際網路使用者存取在您伺服器上的特定網頁服務。
        使用連接埠 80 和/或連接埠 443 的網頁服務包括下列：  
        <ul>
        <li>Microsoft® Office Outlook® Web Access，允許使用者使用網頁瀏覽器，從網際網路存取他們的電子郵件。</li>
        <li>Windows Small Business Server 2003 伺服器效能及使用報告，包含了關於您伺服器的整體狀況與使用情形的詳細資訊。</li>
        <li>Outlook Mobile Access，允許使用者從行動裝置存取電子郵件。</li>
        <li>商業網站 (wwwroot)，允許使用者從網際網路存取公司的網際網路網站。</li>
        <li>經由網際網路的 Outlook，透過 HTTP 功能，使用「遠端程序呼叫 (Remote Procedure Call，RPC)」。</li>
        </ul></td>
        </tr>
        <tr class="odd">
        <td style="border:1px solid black;">Windows SharePoint Services 內部網路網站</td>
        <td style="border:1px solid black;">444</td>
        <td style="border:1px solid black;">允許使用者是否能安全地從網際網路存取由 Microsoft® Windows® SharePoint™ Services 建立的內部網路網站。</td>
        </tr>
        <tr class="even">
        <td style="border:1px solid black;">遠端網路工作環境</td>
        <td style="border:1px solid black;">4125 及 443</td>
        <td style="border:1px solid black;">允許使用者安全地存取遠端網頁工作環境以：
        <ul>
        <li>從 Outlook Web Access 連線到本機網路。</li>
        <li>在本機網路建立直接「遠端桌面網頁連線」到用戶端電腦。</li>
        <li>使用 Windows SharePoint Services 內部網路網站 (這也需要連接埠 444，如上面所提到)。</li>
        <li>下載「連線管理員」設定遠端用戶端電腦的遠端存取 (使用遠端存取也需要開啟連接埠 1723，如上面所提到)。</li>
        </ul></td>
        </tr>
        <tr class="odd">
        <td style="border:1px solid black;">虛擬私人網路 (Virtual Private Network，VPN)</td>
        <td style="border:1px solid black;">1723</td>
        <td style="border:1px solid black;">允許遠端用戶端如使用 VPN 連線安全地連線到網路，讓用戶端如同在本機登入般的使用資源。</td>
        </tr>
        <tr class="even">
        <td style="border:1px solid black;">終端機服務</td>
        <td style="border:1px solid black;">3389</td>
        <td style="border:1px solid black;">允許遠端使用者使用終端機服務連線到執行 Windows Small Business Server 2003 的電腦上。</td>
        </tr>
        <tr class="odd">
        <td style="border:1px solid black;">檔案傳輸通訊協定 (File Transfer Protocol，FTP)</td>
        <td style="border:1px solid black;">21</td>
        <td style="border:1px solid black;">允許遠端使用者使用檔案傳輸通訊協定 (FTP) 連線到執行 Windows Small Business Server 2003 的電腦上。</td>
        </tr>
        </tbody>
        </table>
  
    3.  檢查允許透過您路由器上防火牆的連接埠，以判定是否有其他允許的服務沒有列在表格中。如果您有其他允許透過防火牆的連接埠，您可以藉由查看 IANA 網站上的[常用連接埠清單](http://go.microsoft.com/fwlink/?linkid=22654) (位於 [http://go.microsoft.com/fwlink/?LinkId=22654](http://go.microsoft.com/fwlink/?linkid=22654)) 來驗證開啟連接埠的目的。如需關於連接埠的進階資訊，請參閱《Security Guidance Kit (英文)》中的＜Reference: Network Ports Used by Key Microsoft Server Products＞。
  
    4.  檢查路由器製造商的說明文件，以判定這個路由器是否支援記錄。如果支援，建議您設定記錄監視記錄檔。
  
**注意：**如需關於這個表格所討論每項服務的詳細資訊，請參閱在 Microsoft 網站 [http://go.microsoft.com/fwlink/?LinkId=20122](http://go.microsoft.com/fwlink/?linkid=20122) 上《[Windows Small Business Server 2003 Getting Started Guide (英文)](http://go.microsoft.com/fwlink/?linkid=20122)》的附錄。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 在執行 Windows Small Business Server 2003 的電腦上，設定網路、防火牆、網頁及電子郵件服務
  
使用「設定電子郵件及網際網路連線精靈」可以在您將執行 Windows Small Business Server 2003 的電腦連線到網際網路時，協助您正確地設定網路、防火牆、網站安全性及電子郵件等的設定值 (在「待辦清單」上，這個工作稱為「連線到網際網路」)。這個精靈會自動設定這些服務，然而，您應該要檢查下列事項：
  
-   驗證防火牆設定，以確保只有必要的服務才能允許透過防火牆。
  
-   驗證移除電子郵件附件的選項已經啟用。
  
#### 驗證防火牆設定
  
您可以使用這個精靈協助在執行 Windows Small Business Server 2003 的電腦上，正確地設定防火牆。在 Windows Small Business Server 2003 標準版中，這個精靈在「路由器和遠端存取」服務中，設定「基本防火牆」服務。在 Windows Small Business Server 2003 Premium Edition 中，它設定 Microsoft Internet Security and Acceleration (ISA) 伺服器。
  
當您啟用防火牆，您應該考慮只允許您伺服器存取網際網路或是使用者完成工作時，所需要用到的服務。例如，如果使用者使用「遠端網頁工作環境」，從網際網路連線到本機網路，您應該評估是否您也需要啟用「虛擬私人網路」(VPN)} 服務。
  
除此之外，如果您允許存取到商業網站 (wwwroot)，或是所有網站，您的網站可能需要列在網頁搜尋網站 (如 Google) 上。例如，一個網頁搜尋網站可能會列出「遠端網頁工作環境」。若要避免這種情形發生，請造訪 Microsoft 網站 [http://go.microsoft.com/fwlink/?LinkId=18144](http://go.microsoft.com/fwlink/?linkid=18144) 中的《[Windows Small Business Server 2003 Troubleshooting (英文)](http://go.microsoft.com/fwlink/?linkid=18144)》。
  
##### 需求
  
-   您必須以 Domain Admins 安全性群組成員的身份登入。
  
<!-- -->
  
-   **若要透過伺服器上的防火牆，檢視與移除允許的服務**
  
    1.  按一下 \[開始\]，再按一下 \[伺服器管理\]。
  
    2.  在詳細資料窗格中，按一下 \[網際網路及電子郵件\]，再按一下 \[連線到網際網路\]。會出現「設定電子郵件及網際網路連線精靈」。
  
    3.  在 \[連線類型\] 的頁面上，按一下 \[不要變更連線類型\]。
  
    4.  在 \[防火牆\] 頁面上，按一下 \[啟用防火牆\]。
  
    5.  在 \[服務設定\] 頁面上，清除所有您的使用者沒有使用，或是您的伺服器存取網際網路，所不需要用到的服務的核取方塊。
  
    6.  在 \[網路服務設定\] 的頁面上，清除所有使用者不需要用到的網頁服務的核取方塊。
  
    7.  依照指示說明完成精靈。
  
    8.  在精靈的最後，如果您還沒有在網路上啟用密碼原則強制強性密碼，請您啟用它。按一下 \[是\] 啟用強性密碼原則。這些原則提供額外的階層，防範未授權使用者存取您的網路。如需關於如何啟用密碼原則的詳細資訊，請參閱＜執行強性密碼＞一節。
  
#### 驗證移除電子郵件附件的選項已經啟用。
  
如果 Exchange Server 已經安裝在執行 Windows Small Business Server 2003 的電腦上，您應該考慮使用這個精靈，正確地設定您的伺服器去透過網際網路傳送與接收電子郵件。當您啟用網際網路電子郵件，從傳入電子郵件移除特定類型附件的選項，預設會選取。從傳入電子郵件移除特定類型附件將協助您防止病毒或是惡意程式擴散到您的本機網路。
  
當您完成了「待辦清單」上「連線到網際網路」的任務，如果您選擇不要移除電子郵件附件，建議您再執行一次精靈，變更您的選擇。
  
##### 需求
  
-   您必須以 Domain Admins 安全性群組成員的身份登入。
  
<!-- -->
  
-   **若要啟用移除電子郵件附件**
  
    1.  按一下 \[開始\]，再按一下 \[伺服器管理\]。
  
    2.  在詳細資料窗格上，按一下 \[網際網路及電子郵件\]，再按一下 \[連線到網際網路\]。會出現「設定電子郵件及網際網路連線精靈」。
  
    3.  在 \[連線類型\] 頁面上，按一下 \[不要變更連線類型\]。
  
    4.  在 \[防火牆\] 頁面上，接受 \[不要變更防火牆設定\] 的預設值。
  
    5.  如果您允許存取網頁服務，會出現 \[網頁伺服器憑證\] 頁面。接受 \[不要變更目前網頁伺服器憑證\] 的預設值。
  
    6.  在 \[網際網路電子郵件\] 的頁面，接受 \[啟用網際網路電子郵件\] 的預設值。在每個下列頁面上，按一下 \[下一步\]，直到您找到 \[移除電子郵件附件\] 的頁面。
  
    7.  在 \[移除電子郵件附件\] 頁面上，按一下 \[啟用 Exchange Server 來移除有下列副檔名的網際網路電子郵件附件\]。
  
    8.  依照指示說明完成精靈。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 保持您的軟體在最新狀態
  
一個協助維護您運算環境安全性的方法，就是及時安裝軟體更新，也就是修正檔案、安全性補充程式、Service Pack 與安全性積存套件。軟體更新的不是修正軟體的程式弱點，就是引入額外的安全性功能。建議您在更新可用後，愈快安裝他們愈好。下列方式將協助維護您的軟體在最新狀態：
  
-   安裝 Software Update Services。
  
-   檢查伺服器應用程式的更新。
  
-   檢查 Microsoft Office 的更新。
  
-   檢查其他應用程式的更新。
  
#### 安裝 Software Update Services
  
Microsoft Software Update Services (SUS) 可以用來更新執行 Windows XP Professional、Windows 2000 Professional、Windows 2000 Server 或是 Windows Server™ 2003。SUS 協助您收集、核准與散佈重大作業系統更新，以解決已知的安全性弱點與穩定性議題。
  
若要在 Windows Small Business Server 網路上安裝 SUS，請參閱在《Security Guidance Kit (英文)》的＜Updating a Windows Small Business Server 2003 Network Using Software Update Services Server 1.0＞。
  
如果您網路的作業系統不是用 Windows XP Professional、Windows 2000 Professional、Windows 2000 Server 或 Windows Server 2003，他們就不會被 SUS 自動更新。執行 Windows XP Home Edition 的使用者應該要設定電腦利用下列程序，自動更新。執行 Windows 95、Windows 98、Windows Millennium Edition 或是 Windows NT® Workstation 4.0 應該要使用 [Windows Update](http://go.microsoft.com/fwlink/?linkid=22655) 網站定期檢查需要安裝的更新。如需關於 [Windows Update](http://go.microsoft.com/fwlink/?linkid=22655) 的詳細資訊，請造訪 Microsoft 網站 [http://go.microsoft.com/fwlink/?LinkId=22655](http://go.microsoft.com/fwlink/?linkid=22655)。
  
##### 需求
  
-   您必須以 Domain Admins 安全性群組成員的身份登入。
  
<!-- -->
  
-   **若要設定 Windows XP Home Edition 的自動更新**
  
    1.  按一下 \[開始\]，再按一下 \[執行\]，然後再鍵入 **Control**。 按一下 \[確定\]。
  
    2.  按兩下 \[系統\]。會出現 \[系統內容\] 對話方塊。
  
    3.  按一下 \[自動更新\] 索引標籤。
  
    4.  按一下 \[保持我的電腦在更新狀態\] 核取方塊。
  
    5.  在 \[設定值\]，選取 \[自動下載更新，並在我指定的排程安裝它們\]，然後再指定電腦下載與安裝更新的時間。按一下 \[確定\]。
  
#### 檢查伺服器應用程式的更新。
  
檢查所有您在執行 Windows Small Business Server 2003 的電腦上，所使用的應用程式更新，以協助確保您有最新的修正檔案、安全性補充程式、Service Pack 與安全性積存套件。例如，您應該要檢查 Exchange Server 2003 的更新。除此之外，如果您有 Premium Edition，您應該要檢查 ISA Server 與 SQL Server™ 2000 的更新。
  
-   若要檢查 [Exchange Server 2003 的更新](http://go.microsoft.com/fwlink/?linkid=22656)，請造訪 Microsoft 網站 [http://go.microsoft.com/fwlink/?LinkId=22656](http://go.microsoft.com/fwlink/?linkid=22656)。
  
-   若要檢查 [ISA Server 的更新](http://go.microsoft.com/fwlink/?linkid=22657)，請造訪 Microsoft 網站 [http://go.microsoft.com/fwlink/?LinkId=22657](http://go.microsoft.com/fwlink/?linkid=22657)。
  
    **注意：**包含在 Windows Small Business Server 2003 Premium Edition 內的 ISA Server 2000，包含了 ISA Server 2000 Service Pack 1 及 Hotfix 177、255、256、257、265 及 277。
  
-   若要檢查 [SQL Server 2000 的更新](http://go.microsoft.com/fwlink/?linkid=22658)，請造訪 Microsoft 網站的 [http://go.microsoft.com/fwlink/?LinkId=22658](http://go.microsoft.com/fwlink/?linkid=22658)。
  
-   若要檢查所有 Microsoft 產品的更新，請造訪在 Microsoft 網站上 [http://go.microsoft.com/fwlink/?LinkId=22659](http://go.microsoft.com/fwlink/?linkid=22659) 的 [Microsoft Download Center (英文)](http://go.microsoft.com/fwlink/?linkid=22659)。
  
#### 檢查 Microsoft Office 的更新。
  
由一些 Microsoft Office 應用程式建立的檔案，可能是用來傳輸病毒與其他惡意程式。若要避免這樣的情形，請依下列方式，保持在用戶端電腦的 Office 應用程式在最新狀態：
  
-   如需關於 [Office Update (英文)](http://go.microsoft.com/fwlink/?linkid=8241) 自動檢查系統的詳細資訊，請造訪 Microsoft 網站 [http://go.microsoft.com/fwlink/?LinkId=8241](http://go.microsoft.com/fwlink/?linkid=8241)。下載 Outlook E-mail Security Update 可以協助保護您的電腦，不被流通在可執行檔或高風險附件中的病毒，與不被透過 Outlook 複製的蠕蟲攻擊侵入。
  
    **注意：**若要從 [Office Download Center (英文)](http://office.microsoft.com/officeupdate/default.aspx) 下載個別更新，請造訪 Microsoft 網站 [http://go.microsoft.com/fwlink/?LinkId=17163](http://go.microsoft.com/fwlink/?linkid=17163)。
  
-   若要在發行新更新時，收到通知，您可以訂閱在 Microsoft 網站 [http://go.microsoft.com/fwlink/?LinkId=22660](http://go.microsoft.com/fwlink/?linkid=22660) 上的 [Inside Office—Product Updates Alert Office Newsletter (英文)](http://go.microsoft.com/fwlink/?linkid=22660)。
  
#### 檢查其他應用軟體的更新
  
如果您執行其他軟體，請檢查製造商的網站，查看他是否支援應用程式的自動化更新，以協助保持您在本機網路上的電腦是安全且可靠的。如果這個軟體沒有支援自動化更新，定期檢查製造商網站的更新，以協助確保您有最新的修正檔案、安全性補充程式、Service Pack 與安全性積存套件。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 執行強性密碼
  
使用強性密碼提供額外的防護層，防範未授權使用者存取您的網路。若要執行強性密碼，您可以依照下列步驟：
  
-   啟用密碼原則。
  
-   教育使用者。
  
#### 啟用密碼原則
  
啟用密碼原則以強制強性密碼的使用，是協助您設定網路安全性的重要步驟。如果您執行「設定電子郵件及網際網路連線精靈」設定您的網際網路連線，在精靈的最後，要啟用密碼原則時，您會收到系統提示。如果在您啟用精靈後，您不確定您是否啟用了密碼原則，請完成下列步驟，啟用可以強制強性密碼的密碼原則，以協助限制您本機網路的未授權存取。
  
##### 需求
  
-   您必須以 Domain Admins 安全性群組成員的身份登入。
  
<!-- -->
  
-   **若要啟用密碼原則**
  
    1.  按一下 \[開始\]，再按一下 \[伺服器管理\]。
  
    2.  在詳細資料窗格中，按一下 \[使用者\]。
  
    3.  在主控台樹狀目錄中，按一下 \[設定密碼原則\]。
  
    4.  選取 \[最小長度\]、\[複雜性\] 及 \[最長使用期限\]，然後再變更 \[設定密碼原則\] 為 \[立即\]。按一下 \[確定\]。
  
        -   最小長度判定一個密碼可以包含的最小字元數目。設定最小長度可以避免使用者有短或空白密碼，以協助保護您的網路。預設值是 7 個字元。
  
        -   複雜性判定密碼是否須包含不同類型的字元。如果這個原則啟用了，密碼就不能夠包含所有或部份使用者帳戶名稱，而且必須包含下列四種類別的字元至少三種：大寫字母 (A 到 Z)、小寫字母 (a 到 z)、數字 (0 到 9) 及非英數字元 (如 !、$、\# 或 %)。
  
        -   「最大使用期限」判定在系統要求使用變更密碼前，所使用的期間 (以天來算)。預設值為 42 天。
  
    5.  在您啟用或變更密碼原則後，所有使用者都必須在下次登入時，變更他們的密碼。告知使用者他們在變更密碼時，所必須用到的需求，以協助確保他們了解如何選擇一個強性密碼。
  
#### 教育使用者
  
在執行強性密碼原則後，教育使用者關於強性與弱性密碼。要求使用者將他們的密碼視為私人資訊，比如是信用卡的 PIN 碼。下面是在執行時的傳統指導方針，以協助確保您的網路的強性密碼，而且受到更多的保護。
  
一個密碼不應該包含下列之一：
  
-   使用者名字或是電子郵件別名
  
-   使用者的孩子、父母、配偶或是朋友的名字。
  
-   任何可以在字典裡找到的字
  
-   附加編號的舊密碼
  
-   生日
  
-   電話號碼
  
-   身份證字號或其他識別碼
  
-   任何容易取得的個人資訊
  
一個強性密碼是由下列組成：
  
-   它並沒有包含全部或部份的使用者帳戶名稱。
  
-   它包含至少六個字元。
  
-   它包含以下四種類型的字元至少三種類型：
  
    -   大寫字母 (A 到 Z)。
  
    -   小寫字母 (a 到 z)。
  
    -   數字 (0 到 9)。
  
    -   非英數字元 (例如 !、$、\#、%)。
  
如需關於密碼原則的詳細資訊，請參閱《Security Guidance Kit (英文)》中的＜Selecting Secure Passwords＞。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 設定本機網路的遠端存取
  
您可以有效地利用「遠端網頁工作環境」，遠端存取 Windows Small Business Server 本機網路。您也可以使用「虛擬私人網路」(VPN)。然而，對於已授權的使用者存取本機網路而言，使用「遠端網頁工作環境」是比 VPN 連線更容易的方法。
  
使用其中一種方法，告訴使用者在完成避免未授權使用者存取網路的工作階段後，他們應該要登出。
  
您可以使用下列選項的其中一個或兩者都使用，以協助安全地設定 Windows Small Business Server 2003 遠端存取：
  
-   使用遠端網路工作環境。
  
-   使用遠端存取精靈。
  
#### 使用遠端網路工作環境
  
「遠端網頁工作環境」可以讓不在辦公室的使用者，存取 Windows Small Business Server 2003 的重要功能。使用「遠端網頁工作環境」的話，他們可以檢查電子郵件與行事曆，在工作時使用「遠端桌面」連線到他們的電腦，藉由下載「連線管理員」使用共用應用程式、存取公司的內部網站、檢閱效能報告或是加入一個電腦到 Windows Small Business Server 網路上。
  
如果使用者不需要遠端存取本機網路，停用「遠端網頁工作環境」，以協助限制可能的未授權使用者存取您的網路。若要停用「遠端網路工作環境」的存取，請完成＜若要透過伺服器上的防火牆，檢視與移除允許的服務＞中的程序。
  
**注意：**若要使用「遠端網路工作環境」連線到遠端的桌面，遠端的電腦就必須是執行 Windows 2000 Server 或 Windows XP Professional。執行任何其他作業系統的遠端電腦必須使用 VPN 或是撥接連線，如同在＜使用遠端存取精靈＞一節中所討論到的。
  
#### 使用遠端存取精靈
  
使用「遠端存取精靈」，您可以使用「虛擬私人網路 (VPN)」存取，或撥接存取，或兩者都可。VPN 存取可以使遠端用戶端電腦透過網際網路安全地連線到您的本機網路。使用者先連線到他們的網際網路提供服務者 (Internet Service Provider，ISP)，然後使用以 TCP/IP 為基礎的特殊通訊協定，叫做通訊協，安全地連線到本機網路。撥接連線允許遠端電腦透過電話線連線到執行 Windows Small Business Server 2003 的電腦上的數據機。
  
如果使用者沒有要求 VPN 或撥接存取，您應該要停用它們。
  
##### 需求
  
-   您必須以 Domain Admins 安全性群組成員的身份登入。
  
<!-- -->
  
-   **若要停用 VPN 存取、撥接存取，或兩者**
  
    1.  按一下 \[開始\]，再按一下 \[伺服器管理\]。
  
    2.  在詳細資料窗格上，按一下 \[網際網路及電子郵件\]，再按一下 \[設定遠端存取\]。會出現「遠端存取精靈」。
  
    3.  在 \[遠端存取方式\] 的網頁上，按一下 \[停用遠端存取\]。
  
        **注意：** 如果「停用遠端存取」的選項是灰色的，那麼遠端存取並沒有在執行 Windows Small Business Server 2003 的電腦上啟用。
  
    4.  依照指示說明完成精靈。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 驗證使用者只有必要的權限
  
您可以藉確保使用者只有他們做工作時、所需要的權限，與限制帳戶使用管理權利與權限，以協助設定網路安全性。若要驗證使用者只有他們所需要的權限，請依下列步驟：
  
-   使用正確的 Windows Small Business Server 範本。
  
-   對例行性工作不要使用 Administrator 或 Power User 帳戶。
  
-   指派權限到共用的匿名。
  
#### 使用正確的 Windows Small Business Server 範本
  
Windows Small Business Server 2003 有為了給予使用者他們需要的存取層級所設計，而預先定義的範本。例如，以「使用者範本」為基礎的使用者帳戶，並沒有使用 VPN 連線遠端存取本機網路，但是以「行動使用者」範本為基礎的使用者帳戶有這個存取。以下有四個範本：
  
**範本名稱與說明**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >範本名稱</th>
<th style="border:1px solid black;" >說明</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">使用者</td>
<td style="border:1px solid black;">以這個範本為基礎的帳戶可以存取共用資料夾、印表機與傳真機、電子郵件與網際網路。被指派這個範本的帳戶可以使用「遠端網頁工作環境」，從遠端位置存取本機網路。除此之外，被指派到這個範本的使用者帳戶可以開啟「遠端桌面連線」到執行Windows XP Professional 的電腦，而不是到執行 Windows Small Business Server 2003 的電腦上。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Mobile User</td>
<td style="border:1px solid black;">以這個範本為基礎的帳戶擁有所以「使用者範本」的權限，而且可以利用「遠端網頁工作環境」或是遠端存取連線，從遠端位置存取本機網路。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Power User</td>
<td style="border:1px solid black;">以這個範本為基礎的帳戶擁有所有 Mobile User 範本的權限，而且也可以執行委派的管理工作。Power User 可以遠端登入到執行 Windows Small Business Server 2003 的電腦上，但是他不能在本機登入。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">系統管理員</td>
<td style="border:1px solid black;">以這個範本為基礎的帳戶有無限制的系統存取 Windows Small Business Server 網路的權限。</td>
</tr>
</tbody>
</table>
  
檢視每個使用者目前指派到的範本，而且確保使用者只有他們做例行性工作時，所需要的最小層級的權限，以協助消除他們不當地刪除重要檔案，或是無意存取到 Administrator 帳戶的機會。除此之外，如果您允許從網際網路存取「遠端網頁工作環境」，而您不想要使用者從網際網路存取本機網路，您應該停用這個使用者帳戶的存取「遠端網頁工作環境」的權限。
  
##### 需求
  
-   您必須以 Domain Admins 安全性群組成員的身份登入。
  
<!-- -->
  
-   **若要檢視每個使用者指派到的範本**
  
    1.  按一下 \[開始\]，再按一下 \[伺服器管理\]。
  
    2.  在主控台樹狀目錄中，按一下 \[使用者\]。
  
    3.  在詳細資料窗格中，檢視每個使用者的 \[描述\] 欄位。
  
<!-- -->
  
-   **若要停用使用者存取「存取遠端網頁工作環境」**
  
    1.  按一下 \[開始\]，再按一下 \[伺服器管理\]。
  
    2.  在主控台樹狀目錄中，按一下 \[使用者\]。
  
    3.  在主控台樹狀目錄中，按一下您想要停用的使用者名稱。
  
    4.  按一下 \[修改使用者內容\]。
  
    5.  在 \[使用者內容\] 對話方塊中，按一下 \[隸屬\] 索引標籤。
  
    6.  按一下 \[遠端網頁工作環境\]，再按一下 \[移除\]。
  
<!-- -->
  
-   **若要變更使用者帳戶的權限**
  
    1.  按一下 \[開始\]，再按一下 \[伺服器管理\]。
  
    2.  在主控台樹狀目錄中，按一下 \[使用者\]。
  
    3.  在主控台樹狀目錄中，按一下您想要變更權限的使用者名稱。
  
    4.  按一下 \[變更使用者權限\]。會出現「變更使用者權限精靈」。
  
    5.  在 \[範本選擇\] 頁面上，選擇您想要變更到的範本。例如，如果您有一個 Administrator 權限的帳戶，而您想要變更，您可以指派 \[使用者範本\] 或是 \[Mobile User 範本\]。預設上來說，之前指派給使用者的權限已被取代了。
  
    6.  依照指示說明完成精靈。
  
#### 對例行性工作不要使用 Administrator 或 Power User 的帳戶
  
因為以 Administrator 與 Power User 為基礎的使用者帳戶是非常強大的，請考慮使用不強大的「使用者」範本為基礎的使用者帳戶。使用 Administrator 或 Power User 範本，即使使用者不需要更強大的存取權限，也提升了使用者藉由系統管理或進階權限，不當地刪除重要檔案，或取得無意圖存取帳戶的機會。
  
例如，如果您網路的使用者想要管理或進階權限，但例行性工作並不需要它們，您可以指派給使用者兩個帳戶。第一個帳戶是例行性工作的一般使用者帳戶，以「使用者」範本為基礎。第二個帳戶是以「Administrator 範本」為基礎，提供使用者無限制存取網域，或是以「Power User 範本」為基礎，提供使用者遠端連線到伺服器，並且執行委派任務。您必須指示使用者只有在完成特定工作時，才使用系統管理員或進階使用者權限。
  
因為 Administrator 帳戶是熟知的強大帳戶，而 Power User 允許使用者存取伺服器的管理工作，讓使用者依照下列程序，可以協助消除您網路上的未授權存取，與更多強大存取權限的誤用。
  
-   持續使用強性密碼。
  
-   用您的使用者帳戶登入，執行例行性工作，而不是用 Administrator 或 Power User 的帳戶登入。
  
-   永遠不要在您用 Administrator 或 Power User 的帳戶登入時，讓電腦自動安裝。
  
-   不要給其他人 Administrator 或 Power User 帳戶的密碼。
  
-   永遠不要在靠近電腦的地方，留下 Administrator 或 Power User 帳戶的密碼記錄。
  
##### 需求
  
-   您必須以 Domain Admins 安全性群組成員的身份登入。
  
<!-- -->
  
-   **若要建立例行性工作的使用者帳戶**
  
    1.  按一下 \[開始\]，再按一下 \[伺服器管理\]。
  
    2.  在主控台樹狀目錄中，按一下 \[使用者\]。
  
    3.  在詳細資料窗格中，按一下 \[新增使用者\]。會出現「新增使用者精靈」。
  
    4.  依照指示說明完成精靈，以建立沒有管理權限的使用者帳戶。
  
    5.  指示使用者在例行性活動使用「使用者」帳戶，只有在必須完成特定工作時才使用 Administrator 或 Power User 的帳戶。
  
**注意：**如果使用者已經長時間使用系統管理帳戶，如果您限制現存的系統管理帳戶，對這個使用者而這會比較容易 (請參閱＜若要變更使用者帳戶的權限＞中的程序)，然後再使用之前的程序新增新的管理帳戶。
  
#### 指派權限給共用資源帳戶
  
藉由指派哪些使用者或群組使用者可以在執行 Windows Small Business Server 2003 的電腦上存取共用資訊，您可以協助避免未授權使用者存取您公司的資料。預設上來說，任何在安裝 Windows Small Business Server 2003 過程中，所建立的共用資源帳戶，是被指派設定共用安全性的權限。如果您已經在伺服器上，建立額外的共用資源帳戶，請確保這些帳戶只有必要的權限，這樣可以協助您限制存取權限，只給那些需要的人。
  
##### 需求
  
-   您必須以 Domain Admins 安全性群組成員的身份登入。
  
<!-- -->
  
-   **若要判定伺服器上的共用資源清單**
  
    1.  在伺服器上，按一下 \[開始\]，再按一下 \[執行\]，然後鍵入 \\\\*YourServerName*。會出現共用資源清單。下列共用資源清單是在「安裝」時建立，而且會自動指派給適當權限：Address、*YourServerName.*log、ClientApps、Clients、Faxclient、Netlogon、Sysvol、Tsclient、Tsweb、Users 與 Printers and Faxes。
  
    2.  如果這份清單包含任何多於預設的共用資源，請將非預設的共用資源名稱記錄下來：
  
<!-- -->
  
-   **若要檢視及指派權限給非預設的共用資源**
  
    1.  當上列程序的共用資源清單依舊為開啟時，一個共用資源的名稱按一下滑鼠右鍵，再按一下 \[內容\]。
  
    2.  按一下 \[安全性\] 索引標籤。
  
    3.  檢視允許存取共用資源的群組清單，以及每個群組的相關權限。
  
    4.  如果共用資源沒有指派到安全性權限，請以您商務需要為基礎，指派權限給群組使用者。如需關於從執行 Windows Small Business Server 2003 的電腦上，指派權限給共用資源的詳細資訊，請按一下 \[開始\]，再按一下 \[說明及支援\]，然後搜尋「共用資料夾權限」。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 變更內建 Administrator 帳戶的帳戶名稱
  
在所有執行 Windows Small Business Server 網路的電腦，或至少在執行 Windows Small Business Server 2003 的電腦上，重新命名內建的 Administrator 帳戶，是可以協助消除未授權網路存取的標準實作。內建 Administrator 帳戶，是熟知的強大帳戶。惡意使用者通常嘗試猜測 Administrator 帳戶的密碼，登入到電腦。因為很多功能都需要用到這個帳戶，所以它不能被鎖定。然而，如果您變更這個帳戶的名稱，您會使未授權使用者更難發現密碼，而取得網路的存取。除此之外，您應該要考慮對 Administrator 帳戶使用強性密碼，才能在攻擊者可以判定新帳戶名稱時，採用新措施。如需關於強性密碼的詳細資訊，請參閱＜執行強性密碼＞一節。
  
**注意：**在執行 Windows Small Business Server 2003 的電腦上重新命名內建 Administrator 帳戶後，您必須要先登出伺服器，再使用重新命名過的帳戶登入。不然的話，您可能會被拒絕存取資源，或是不能夠成功使用一些 Windows Small Business Server 工具。
  
#### 需求
  
-   您必須以 Domain Admins 安全性群組成員的身份登入。
  
<!-- -->
  
-   **若要在執行 Windows Small Business Server 2003 的電腦上，重新命名 Administrator 帳戶**
  
    1.  按一下 \[開始\]，再按一下 \[伺服器管理\]。
  
    2.  在主控台樹狀目錄中，按一下 \[使用者\]。
  
    3.  在主控台樹狀目錄中，對 \[Administrator\] 按一下滑鼠右鍵，再按一下 \[內容\]。
  
    4.  在 \[一般\] 索引標籤，以及在 \[顯示名稱\] 文字方塊中，用新的名稱取代之前的名稱 (Administrator)。
  
    5.  在 \[帳戶\] 索引標籤，以及 \[使用者登入名稱\] 方塊中，鍵入新名稱。
  
    6.  在 \[使用者登入名稱 (Windows 2000 之前)\] 方塊中，用新名稱取代之前的名稱 (Administrator)，再按一下 \[確定\]。
  
    7.  在變更 Administrator 帳戶名稱後，您必須先登出，再使用新名稱以伺服器上的系統管理員的身份登入。
  
<!-- -->
  
-   **若要在用戶端電腦重新命名本機 Administrator 帳戶**
  
    1.  在用戶端電腦，按一下 \[開始\]。
  
    2.  如果用戶端電腦正在執行 Windows XP，請按一下 \[控制台\]，再按一下 \[效能及維護\]。如果它正在執行 Windows 2000，按一下 \[設定\]，再按一下 \[控制台\]。
  
    3.  按兩下 \[系統管理工具\]，再按兩下 \[電腦管理\]。
  
    4.  在主控台樹狀目錄中，按一下 \[本機使用者和群組\]，再按一下 \[使用者\]。
  
    5.  在詳細資料窗格中，在 \[Administrator\]，再按一下 \[重新命名使用者\]。輸入帳戶的新名稱。
  
    6.  在變更 Administrator 帳戶名稱後，您必須先登出，再使用新名稱以伺服器上的系統管理員的身份登入用戶端電腦。
  
**注意：** 如果您有很多用戶端電腦，使用「群組原則管理主控台 (GPMC)」自動重新命名在網路 (包含伺服器) 中，所有的 Administrator 帳戶會來得有效多了。如需這個方法的逐步說明，從執行 Windows Small Business Server 2003 的電腦上，按一下 \[開始\]，再按一下 \[說明及支援\]，然後再搜尋「使用群組原則管理主控台重新命名系統管理員帳戶」。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 設定執行 Windows Small Business Server 2003 電腦的安全性
  
使用下列方法可以協助設定執行 Windows Small Business Server 2003 電腦的安全性：
  
-   實體設定執行 Windows Small Business Server 2003 的電腦，避免線上攻擊。
  
-   不要將執行 Windows Small Business Server 2003 的電腦視為工作站使用。
  
-   不要在執行 Windows Small Business Server 2003 的電腦上安裝任何不必要的軟體。
  
-   設定備份程式。
  
#### 實體設定執行 Windows Small Business Server 2003 的電腦，避免線上攻擊
  
所有網路對於線上攻擊都是脆弱的，但是不受限於：對執行 Windows Small Business Server 2003 的電腦用磁片開機，並將硬碟重新格式化；開啟電腦的盒子，並用基本輸出/輸入系統 (BIOS) 晶片取代系統；從執行 Windows Small Business Server 2003 的電腦上移除硬碟，並且從硬碟讀取資訊；或是用可以協助監視任何您鍵入東西的事物 (包含密碼)，取代鍵盤。實體設定執行 Windows Small Business Server 2003 的電腦，可以協助限制這些線上攻擊。
  
-   **若要協助實體設定 Windows Small Business Server 2003 的電腦**
  
    1.  將磁帶備份保持在安全的離線位置。將線上備份儲存在安全的地方。
  
    2.  鎖定 CPU 的盒子，並確保鑰匙受到保護。製作備份鑰匙，並將它保持在離線的保險箱中。
  
    3.  限制執行 Windows Small Business Server 2003 電腦的實體存取，寧願在鎖定的房間存取，並且只發行給需要實體存取的使用者鑰匙。伺服器必須關閉或是放在安全的框架中。或者，使用纜線鎖。
  
    4.  請確保密碼不是寫在靠近電腦的地方 (例如在鍵盤下)。
  
    5.  用不斷電供應系統 (UPS) 保護執行 Windows Small Business Server 2003 的電腦。UPS 協助保護伺服器，使沒有造成伺服器失敗或檔案毀損的短暫電源喪失。
  
    6.  請確保所有磁碟區使用 NTFS 檔案系統。
  
    7.  設定系統 BIOS 的密碼。如需關於設定 BIOS 密碼的詳細資訊，請參閱伺服器製造商說明文件。
  
#### 不要將執行 Windows Small Business Server 2003 的電腦視為工作站使用
  
請考慮不要將執行 Windows Small Business Server 2003 視為工作站使用，因為這樣會增加遭受攻擊的表面區域，而影響了網路的效能。遭受攻擊的表面區域因為您需要在伺服器安裝用戶端應用程式而增加了。如果有任何用戶端應用程式的安全性相關問題，在安裝安全性補充程式前，伺服器對於攻擊是脆弱的。除此之外，如果不是系統管理員的使用者登入到伺服器，使用者意外地刪除重要資訊或是應用程式的機會會提升。
  
#### 不要在執行 Windows Small Business Server 2003 的電腦上安裝任何不必要的軟體
  
請考慮在執行 Windows Small Business Server 2003 的電腦上，只安裝您商務作業所需要的軟體，才能消除遭受攻擊的表面區域，並且協助將伺服器的效能最佳化。
  
#### 設定備份程式
  
將執行 Windows Small Business Server 2003 電腦上的資料備份，可以協助避免因使用者錯誤、資料竄改或病毒攻擊而導致的資料遺失。備份資料對小型企業是十分重要的，因為全部的系統失敗不但會造成重要資料的遺失，也會造成重要服務如電子郵件和網際網路連線等的遺失。如果沒有目前的備份資料，即使是使用鏡像硬碟設定的公司，也只能恢復部份損失。您應該將備份媒體保持在安全的位置，因為惡意使用者可以使用這些資料，在別的位置重新建構伺服器。除此之外，請考慮用從備份選取隨機檔的方式，測試備份資料的完整性，將它們還原到另一個位置，然後再確認這個檔案是否沒有變更。
  
Windows Small Business Server 2003 提供完整的備份解決方案。當您使用完整備份解決方案設定備份時，整個伺服器是依預設值備份，包括您的內部網路、信箱及使用者檔案。
  
若要設定備份，請參閱在《Security Guidance Kit (英文)》中的＜Backing Up and Restoring Windows Small Business Server 2003＞一節。
  
**注意：**若要開啟備份管理工作台，按一下 \[開始\]，再按一下 \[伺服器管理\]，再按一下 \[備份\]。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 執行防毒解決方案
  
電腦病毒可以很快地散佈且導致網路資源的過度負荷。除了透過電子郵件，病毒也可以透過執行 Windows Small Business Server 2003 電腦上的服務、網路上的共用資料夾、從網際網路或是從可移除的媒體 (如磁帶與光碟) 受影響的檔案來散佈。如需關於防毒軟體的詳細資訊，請造訪 Microsoft Security (英文) 網站 [http://go.microsoft.com/fwlink/?LinkId=22661](http://go.microsoft.com/fwlink/?linkid=22661) 上的《[Frequently Asked Questions About Antivirus Software (英文)](http://go.microsoft.com/fwlink/?linkid=22661)》。
  
使用保護整個網路，包含伺服器與用戶端電腦的防毒解決方案，可以協助您避免電腦病毒存取您的本機網路。除此之外，請考慮確保您有良好的備份與回復計劃，因為您可能需要在病毒感染發生前，還原系統到正常狀態。若要協助執行有效的防毒解決方案，請執行下列：
  
-   選擇一個防毒解決方案。
  
-   執行病毒反應計劃。
  
#### 選擇一個防毒解決方案
  
如果您沒有在執行防毒解決方案，請考慮購買符合下列標準的方案：
  
-   它支援 Windows Small Business Server 2003。
  
-   它支援 Exchange Server 2003 與支援 Microsoft Virus Scanning API 2.5。如需關於防毒軟體與 Exchange 伺服器的詳細資訊，請參閱在[微軟知識庫](http://go.microsoft.com/fwlink/?linkid=22662)中 [http://go.microsoft.com/fwlink/?LinkId=22662](http://go.microsoft.com/fwlink/?linkid=22662) 中的文件 82366，《Overview of Exchange Server 2003 and Antivirus Software (英文)》。
  
-   它必須保護執行 Windows Small Business Server 2003 電腦與用戶端電腦。
  
-   防毒軟體製造商應該迅速發行更新。
  
除此之外，只要您安裝防毒解決方案，將它設定為自動檢查防毒更新 (也稱作數位簽章)，而且自動安裝更新到特定排程，可以協助消除您的網路受到病毒或其他惡意程式感染的可能性。
  
如需關於[防毒廠商清單](http://go.microsoft.com/fwlink/?linkid=22663)，請造訪 Microsoft Security (英文) 網頁 [http://go.microsoft.com/fwlink/?LinkId=22663](http://go.microsoft.com/fwlink/?linkid=22663)。
  
#### 執行病毒反應計劃
  
在某些情況下，您可能會在有可用的防毒軟體更新之前，接收到新病毒的警告。如果這個情形發生了，擁有一個正確的如何處理病毒的回應計劃，可以協助消除您的網路被病毒感染的可能性。除此之外，您可以暫時停用您的網際網路連線。
  
-   **若要執行病毒反應計劃**
  
    1.  藉由與您的防毒軟體製造商確認，驗證這個病毒，是否為真的。有些病毒通知可能是不正確的。
  
    2.  如果這個病毒是真的，而且也有可用的更新，請立即下載更新。如果還沒有可用的更新，建議您做下列事項來避免病毒感染您的本機網路：
  
        1.  檢查防毒軟體製造商的網站，以取得這個病毒感染是如何發生的相關資訊。
  
        2.  確定是什麼動作導致病毒散佈之後，就可以避免病毒再散佈。
  
<!-- -->
  
-   **若要暫時停用您的網際網路連線**
  
    -   將您的網際網路連線裝置實體從網際網路中斷連線。例如，如果您是用寬頻連線，請將您「網際網路提供服務者 (ISP)」與您的寬頻裝置的連線中斷。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 升級用戶端電腦
  
如果您有執行 Windows 98 或更早版本，或 Windows NT 4.0 或更早版本的電腦，請考慮將這些電腦升級成 Windows XP Professional 或 Windows 2000 Professional。Windows XP Professional 及 Windows 2000 Professional 是設計來與 Windows Server 2003 網路環境一起運作。這樣將會增加本機網路的安全性、可靠性、效能與功能。除此之外，一些 Windows Small Business Server 2003 應用程式，如 Outlook 2003，是特別設計來與 Windows 2000 Professional Service Pack 3 或之後的版本一起運作的。
  
如需關於升級用戶端電腦的資訊，請造訪 Microsoft 網站 [http://go.microsoft.com/fwlink/?LinkId=22664](http://go.microsoft.com/fwlink/?linkid=22664) 上的《[Windows XP Professional Upgrade Center (英文)](http://go.microsoft.com/fwlink/?linkid=22664)》頁面。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 監視執行 Windows Small Business Server 2003 電腦上的安全性問題
  
您可以依下列方式，監視執行 Windows Small Business Server 2003 電腦上的安全性問題：
  
-   設定監視。
  
-   附加記錄檔來監視報告。
  
-   稽核失敗的登入事件與帳戶鎖定。
  
-   保持安全性資訊在最新狀態。
  
#### 設定監視
  
Windows Small Business Server 2003 效能與使用報告包含執行 Windows Small Business Server 2003 電腦的整體狀況與使用情形的詳細資訊。您可以藉執行「監視設定精靈」設定報告。
  
如果您沒有收到監視報告，您需要設定監視，或是新增您的電子郵件位址到報告收件者清單中。
  
##### 需求
  
-   您必須以 Domain Admins 安全性群組成員的身份登入。
  
<!-- -->
  
-   **若要設定效能與使用報告**
  
    1.  按一下 \[開始\]，再按一下 \[伺服器管理\]。
  
    2.  在詳細資料窗格中，按一下 \[監視及報告\]。
  
    3.  在主控台樹狀目錄中，按一下 \[設定監視報告及警示\]。會出現「監視設定精靈」。
  
    4.  依照指示說明完成精靈。
  
#### 附加記錄檔到監視報告
  
記錄檔包含關於應用程式事件、Internet Information Service (IIS)、安全性事件與系統事件的重要資訊，包含硬體與軟體問題。在記錄檔中會依時間先後記錄資訊。一些記錄檔，如防火牆記錄檔與安全性事件記錄檔，可以用來協助監視您網路的安全性。
  
您也可以藉檢視防火牆與安全性事件的記錄檔，監視網路的攻擊。您可以使用在 Windows Small Business Server 中可用的監視工具，監視這些記錄檔。這些工具包含警示通知及效能與使用報告。
  
##### 需求
  
-   您必須以 Domain Admins 安全性群組成員的身份登入。
  
<!-- -->
  
-   **若要將記錄檔附加到監視報告**
  
    1.  按一下 \[開始\]，再按一下 \[伺服器管理\]。
  
    2.  在主控台樹狀目錄中，按一下 \[監視及報告\]。
  
    3.  在詳細資料窗格中，按一下 \[變更伺服器狀態報告設定值\]。
  
    4.  在報告清單中，按一下您想要附加記錄檔的報告，然後再按一下 \[編輯\]。
  
    5.  在 \[內容\] 索引標籤，以及 \[要與報告一起傳送的記錄檔\] 下，按一下您想要附加到這個報告的記錄檔。
  
    6.  如果要附加 \[要與報告一起傳送的記錄檔\] 下沒有顯示的記錄檔，請按一下 \[新增\] 瀏覽記錄檔。  
        建議您將記錄檔附加為適合您特定商務用途的檔 (如 UP 記錄檔、重要商務應用程式記錄檔及防毒軟體記錄檔)。
  
        **注意：**記錄檔可能會非常的大。請在決定是否附加記錄檔到伺服器效能或使用報告時，考慮這點。如果壓縮後，效能與使用報告的附件超過 5 MB 時，它就不會附加在郵件上。除此之下，一些郵件服務可能對允許附件的大小，有較低的限制。
  
#### 稽核失敗的登入事件與帳戶鎖定
  
稽核使用者登入失敗的數目，將協助您發現在執行 Windows Small Business Server 2003 電腦上的暴力攻擊、字典與其他密碼攻擊。預設上來說，Windows Small Business Server 2003 啟用了失敗的登入事件與帳戶鎖定的稽核。如果使用者在十分鐘內有 50 次的嘗試登入失敗，這個帳戶就會鎖定十分鐘。十分鐘後，這個帳戶會重新設定，而使用者可以再嘗試登入。失敗稽核會在嘗試登入失敗時，產生一個稽核項目。因此，每次在執行 Windows Small Business Server 2003 的電腦上，發生無效的嘗試登入，或是帳戶鎖定發生時，在事件日誌上會產生一個訊息。另外，Windows Small Business Server 2003 效能報告會列出是否有發帳戶鎖定，指出有嘗試取得帳戶的未授權存取。如果您在執行「監視設定精靈」時，您選擇接收警示通知，就會傳送電子郵件訊息給特定使用者，指出發生一個帳戶鎖定。
  
#### 保持安全性資訊在最新狀態
  
公告、新聞稿與新聞群組包含最近關於安全性相關議題、受影響的產品 (如果有的話)、如果協助保護您的電腦及需要做什麼去修正安全性問題等的最新資訊。這些資源也包含其他資訊來源的連結。與安全性資訊保持在目前狀態，以協助您保護您的資料避免被未授權存取、病毒感染與偷竊。
  
##### 檢視安全性公告
  
安全性公告提供最新的安全性資訊。Microsoft Security Response Center 會定期發佈 Hotfix 及安全性公告。如需詳細資訊，請造訪在 Microsoft 網站 [http://go.microsoft.com/fwlink/?LinkId=16290](http://go.microsoft.com/fwlink/?linkid=16290) 上的 [HotFix and Security Bulletin Service (英文)](http://go.microsoft.com/fwlink/?linkid=16290)。
  
#### 訂閱安全性新聞稿
  
若要接收關於您所有 Microsoft 產品的通知與更新，請造訪在 Microsoft 網站上 [http://go.microsoft.com/fwlink/?LinkId=22339](http://go.microsoft.com/fwlink/?linkid=22339) 中 [subscribe to the Microsoft Security Update Newsletter (英文)](http://go.microsoft.com/fwlink/?linkid=22339)。而且，藉由造訪製造商網站，可將其他您可能會使用的軟體，保持在最新更新的狀態。
  
#### 檢視新聞群組
  
檢視新聞群組以接收最新的安全性相關資訊。
  
-   若要檢視 [Newsgroup for Windows Small Business Server 2003 (英文)](http://go.microsoft.com/fwlink/?linkid=22665)，請造訪 Microsoft 網站 [http://go.microsoft.com/fwlink/?LinkId=22665](http://go.microsoft.com/fwlink/?linkid=22665)。
  
-   若要檢視 [Microsoft Security Newsgroups (英文)](http://go.microsoft.com/fwlink/?linkid=17118)，請造訪 Microsoft 網站 [http://go.microsoft.com/fwlink/?LinkId=17118](http://go.microsoft.com/fwlink/?linkid=17118)。
  
[](#mainsection)[回到頁首](#mainsection)
  
### 相關資訊
  
如需關於安全性的詳細資訊，請參閱下列連結：
  
-   Microsoft 網站上的 [http://go.microsoft.com/fwlink/?LinkId=102](http://go.microsoft.com/fwlink/?linkid=102) 中的 [Microsoft Security](http://go.microsoft.com/fwlink/?linkid=102)。
  
如需關於 Windows Small Business Server 2003 的詳細資訊，請參閱下列：
  
-   Microsoft 網站 [http://go.microsoft.com/fwlink/?LinkId=22341](http://go.microsoft.com/fwlink/?linkid=22341) 上的 [Microsoft Windows Small Business Server 2003 (英文)](http://go.microsoft.com/fwlink/?linkid=22341)。
  
-   Microsoft 網站 [http://go.microsoft.com/fwlink/?LinkId=20122](http://go.microsoft.com/fwlink/?linkid=20122) 上的 [Windows Small Business Server 2003 Getting Started Guide (英文)](http://go.microsoft.com/fwlink/?linkid=20122)。
  
[](#mainsection)[回到頁首](#mainsection)
