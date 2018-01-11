---
TOCTitle: '使用 RMS Service Pack 2 (SP2) 更新部署'
Title: '使用 RMS Service Pack 2 (SP2) 更新部署'
ms:assetid: '27ee06a1-f467-4a6c-b662-45ddb5f8c13e'
ms:contentKeyID: 18112877
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc720225(v=WS.10)'
---

使用 RMS Service Pack 2 (SP2) 更新部署
======================================

本區段提供的資訊可協助您在已部署 RMS 的組織中安裝 Microsoft® Windows® Rights Management Services (RMS) Service Pack 2 (SP2)。只有已部署 RMS 的組織必須使用 RMS SP2 更新部署。初次部署 RMS 的組織可按照本文件集內的＜規劃 RMS 部署＞(英文) ([http://go.microsoft.com/fwlink/?LinkId=74999](http://go.microsoft.com/fwlink/?linkid=74999)) 及＜部署 RMS 系統＞(英文) ([http://go.microsoft.com/fwlink/?LinkID=75000](http://go.microsoft.com/fwlink/?linkid=75000)) 中的方針，來部署 RMS SP2。

您可以安裝 RMS SP2，而不需移除現有的 RMS SP1 安裝。RMS SP2 的安裝程式會偵測到已安裝 RMS SP1，並新增必要的其他功能與設定。

> [!Note]  
> 不支援從不含 Service Pack 的 RMS 伺服器升級到 RMS SP2。如果您使用不含 Service Pack 的 RMS 伺服器，在升級為 RMS SP2 之前，必須先升級為 RMS SP1。RMS 用戶端可從任何舊版的 RMS 用戶端升級。 

**本主題中的內容**

-   [準備 RMS SP2 更新](#bkmk_preparingforsp2update)
-   [執行 RMS SP2 更新](#bkmk_performingsp2update)
-   [更新叢集](#bkmk_updateclusters)
-   [更新 RMS 用戶端](#bkmk_updateclients)
-   [與 RMS 1.0 版的交互操作性](#bkmk_interop)
-   [移除 RMS SP2](#bkmk_removingrms)

<span id="bkmk_PreparingForSP2Update"></span>
準備 RMS SP2 更新
-----------------

RMS SP2 更新可允許您繼續執行 RMS 而不中斷。但是，在您升級 RMS 叢集之前，建議您執行下列操作：

-   備份設定資料庫與 RMS 私密金鑰。如需相關資訊，請參閱本文件集內的＜RMS 系統備份＞(英文) ([http://go.microsoft.com/fwlink/?LinkId=75001](http://go.microsoft.com/fwlink/?linkid=75001))。
-   如果您使用軟體式私密金鑰，請確認您擁有 RMS 私密金鑰密碼。
-   如果您要保留先前記錄的統計資料，請備份記錄資料庫。
-   請確認您擁有適用於用戶端與伺服器所安裝作業系統的最新重大更新與安全性更新。若要確認您擁有所有重大更新與安全性更新，請依序按一下 \[開始\]、\[Windows Update\]，然後按照螢幕上顯示的指示操作。

<span id="bkmk_PerformingSP2Update"></span>
執行 RMS SP2 更新
-----------------

Windows Rights Management Services Service Pack 2 安裝精靈偵測到您的 RMS 安裝時，會查看目前的 RMS SP1 安裝，然後只會新增新檔案，或取代為 RMS SP2 必須變更的檔案。如果您已成功執行 RMS，在安裝 RMS SP2 之後，不需要重新提供或執行任何額外設定，即能繼續執行 RMS。

<span id="bkmk_UpdateClusters"></span>
更新叢集
--------

如果您已在叢集設定中安裝 RMS，則應規劃叢集的更新，以便使安裝上的更新影響降至最低。決定在組織中執行 RMS SP2 的最佳方式時，請考慮下列建議：

-   最好的作法是，將 RMS SP2 一次安裝於叢集的一部分中，使叢集的升級較可預測，並降低服務在升級期間降級的可能性。
-   如果您有多個 RMS 叢集，則應先升級根憑證叢集，然後再升級子註冊授權伺服器。
-   如果您使用跨樹系群組展開功能，則可以獨立升級樹系內的叢集，而不影響到 RMS 伺服器跨樹系展開群組成員資格的功能。
-   唯有 RMS SP2、RMS SP1 與 RMS 1.0 版伺服器位於不同的 Active Directory 樹系時，才能共存並交互操作。我們不建議在同一叢集中安裝不同版本的 RMS 伺服器。
-   RMS SP2 安裝套件也能用於在伺服器上安裝新的 RMS SP2 部署，且不會要求安裝 RMS SP1。

<span id="bkmk_UpdateClients"></span>
更新 RMS 用戶端
---------------

新的 RMS SP2 用戶端可從 Windows Update 或 Microsoft 下載中心取得。RMS SP2 用戶端安裝套件也能用於在電腦上安裝新版本的 RMS SP2 用戶端，且不會要求安裝 RMS 1.0 版用戶端。RMS SP2 用戶端包含舊版相容功能，以便用於需要 RMS 1.0 版的 RMS 應用程式。

如需更新與安裝 RMS 用戶端的相關資訊，請參閱＜發佈 RMS 用戶端＞(英文) ([http://go.microsoft.com/fwlink/?LinkId=75070](http://go.microsoft.com/fwlink/?linkid=75070))。

<span id="bkmk_InterOp"></span>
與 RMS 1.0 版的交互操作性
-------------------------

因為 RMS SP2 有許多改進及效能強化，您應在下一次的升級週期中安裝。雖然執行 RMS SP2 的 RMS 伺服器與用戶端，和沒有執行 RMS SP2 的 RMS 伺服器與用戶端可完全交互操作，但是請注意，二者在混合環境中的運作有下列差異：

-   只有執行 RMS SP1 及更新版的伺服器提供離線註冊功能。
-   只有執行 RMS SP1 及更新版的用戶端能自我啟用。
-   下表描述混合環境中所支援的功能：

<p></p> 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >RMS 伺服器版本</th>
<th style="border:1px solid black;" >第 1 版用戶端支援的功能</th>
<th style="border:1px solid black;" >SP2 用戶端支援的功能</th>
<th style="border:1px solid black;" >在混合用戶端環境中支援的功能</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">1.0</td>
<td style="border:1px solid black;">所有先前的功能。
沒有伺服器離線註冊功能。伺服器必須透過網際網路註冊。
用戶端無法自我啟用。</td>
<td style="border:1px solid black;">所有先前的功能。
沒有伺服器離線註冊功能。
用戶端可自我啟用。</td>
<td style="border:1px solid black;">所有先前的功能。
如果是 SP2 用戶端，用戶端可自我啟用。
如果是第 1 版用戶端，用戶端必須透過網際網路啟用。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SP2</td>
<td style="border:1px solid black;">所有先前的功能。
伺服器離線註冊功能。
用戶端無法自我啟用。</td>
<td style="border:1px solid black;">所有 SP1 的功能。
伺服器離線註冊功能。  
用戶端可自我啟用。  
伺服器 Lockbox。
可立即支援 Microsoft SQL Server™ 2005。</td>
<td style="border:1px solid black;">所有先前的功能，加上 SP2 的功能。
伺服器離線註冊功能。  
如果是 SP2 用戶端，用戶端可自我啟用。
如果是第 1 版用戶端，用戶端必須透過網際網路啟用。</td>
</tr>
</tbody>
</table>
 

<span id="bkmk_RemovingRMS"></span>
移除 RMS SP2
------------

如果安裝 RMS SP2 之後，想要使 RMS 伺服器回復到先前的設定，則可以使用 \[控制台\] 的 \[新增或移除程式\] 移除 RMS SP2。
