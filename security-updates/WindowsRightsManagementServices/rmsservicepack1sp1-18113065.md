---
TOCTitle: '使用 RMS Service Pack 1 (SP1) 更新部署'
Title: '使用 RMS Service Pack 1 (SP1) 更新部署'
ms:assetid: 'a562c4b0-15df-46db-9d61-24db74871cfa'
ms:contentKeyID: 18113065
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc747714(v=WS.10)'
---

使用 RMS Service Pack 1 (SP1) 更新部署
======================================

本區段提供的資訊可協助您在已部署 RMS 的組織中安裝 Microsoft® Windows® Rights Management Services (RMS) Service Pack 1 (SP1)。只有已部署 RMS 的組織必須使用 RMS SP1 更新部署。初次部署 RMS 的組織可按照本文件集內的＜規劃 RMS 部署＞(英文) 及＜部署 RMS 系統＞(英文) 中的方針，來部署 RMS SP1。

您可以安裝 RMS SP1，而不需移除現有的 RMS 安裝。RMS SP1 的安裝程式會偵測已安裝 RMS，並新增必要的其他功能與設定。

**本主題中的內容**

-   [準備 RMS SP1 更新](#bkmk_1)
-   [執行 RMS SP1 更新](#bkmk_2)
-   [更新叢集](#bkmk_3)
-   [更新 RMS 用戶端](#bkmk_4)
-   [與 RMS 1.0 版本的交互操作性](#bkmk_5)
-   [移除 RMS SP1](#bkmk_6)

<span id="BKMK_1"></span>
準備 RMS SP1 更新
-----------------

RMS SP1 更新可允許您繼續 RMS 作業，不需中斷。但是，在您升級 RMS 伺服器之前，建議您執行下列操作：

-   備份設定資料庫與 RMS 私密金鑰。如需相關資訊，請參閱本文件集內＜規劃 RMS 部署＞(英文) 區段內的＜RMS 系統備份＞(英文)。
-   請確認您擁有 RMS 私密金鑰密碼。
-   如果您要保留先前記錄的統計資料，請備份記錄資料庫。
-   請確認您擁有適用於用戶端與伺服器所安裝作業系統的最新重大更新與安全性更新。若要確認您擁有所有重大更新與安全性更新，請依序按一下 \[開始\]、\[Windows Update\]，然後按照螢幕上顯示的指示操作。

<span id="BKMK_2"></span>
執行 RMS SP1 更新
-----------------

RMS SP1 安裝精靈偵測到您的 RMS 安裝時，只會新增新檔案，或取代為 RMS SP1 必須變更的檔案。如果您已成功執行 RMS，在安裝 RMS SP1 之後，不需要重新提供或執行任何額外設定，即能繼續執行 RMS。

<span id="BKMK_3"></span>
更新叢集
--------

如果您已在叢集設定中安裝 RMS，則應規劃叢集的更新，以便使安裝上更新的影響降至最低。決定在組織中執行 RMS SP1 的最佳方式時，請考慮下列建議：

-   最好的作法是，將 RMS SP1 一次安裝於叢集的一部分中，使叢集的升級較可預測，並降低服務在升級期間降級的可能性。
-   如果您有多個 RMS 叢集，則應先升級根憑證叢集，然後再升級子註冊授權伺服器。
-   如果您使用跨樹系群組展開功能，則可以獨立升級樹系內的叢集，而不影響到 RMS 伺服器跨樹系展開群組成員資格的功能。
-   RMS SP1 與 RMS 1.0 版伺服器能共存並交互操作。
-   RMS SP1 安裝套件也能用於在伺服器上安裝新版本的 RMS SP1，且不會要求安裝 RMS 1.0 版本。

<span id="BKMK_4"></span>
更新 RMS 用戶端
---------------

新的 RMS 用戶端內含於 RMS SP1。RMS SP1 用戶端安裝套件也能用於在電腦上安裝新版本的 RMS SP1 用戶端，且不會要求安裝 RMS 1.0 版用戶端。RMS SP1 用戶端包含舊版相容功能，以便用於需要 RMS 1.0 版的 RMS 應用程式。

新的 RMS 用戶端提供下列功能：

-   用戶端不再需要透過網際網路連線至 Microsoft 並下載 Lockbox。
-   如果您使用 SMS 或群組原則安裝 RMS 用戶端，則安裝時不需要系統管理員權限。
-   RMS SP1 用戶端包含新的伺服器 Lockbox (也稱為伺服器安全性處理器)，此 Lockbox 可用於 RMS Web 服務或伺服器端應用程式，例如 Windows SharePoint® Services 及 Exchange Server 2003，以允許服務利用及轉散發受 RMS 保護的內容。此 Lockbox 的設計目標是，用於信任的伺服器應用程式時展現高效能且可擴充
-   RMS 用戶端使用獲得 FIPS 140-2 認證的密碼編譯演算法。這可讓您將用戶端部署於 FIPS 相容的組織中。

<span id="BKMK_5"></span>
與 RMS 1.0 版的交互操作性
-------------------------

因為 RMS SP1 有許多改進及效能強化，您完成測試之後，應予安裝。雖然執行 RMS SP1 的 RMS 伺服器與用戶端，和沒有執行 RMS SP1 的 RMS 伺服器與用戶端可完全交互操作，但是請注意，二者在混合環境中的運作有下列差異：

-   只有執行 RMS SP1 的伺服器提供離線註冊功能。
-   只有執行 RMS SP1 的用戶端能自我啟用。
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
<th style="border:1px solid black;" >SP1 用戶端支援的功能</th>
<th style="border:1px solid black;" >在混合 (第 1 版與 SP1) 用戶端環境中支援的功能</th>
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
如果是 SP1 用戶端，用戶端可自我啟用。
如果是第 1 版用戶端，用戶端必須透過網際網路啟用。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SP1</td>
<td style="border:1px solid black;">所有先前的功能。
伺服器離線註冊功能。
用戶端無法自我啟用。</td>
<td style="border:1px solid black;">所有 SP1 的功能。
伺服器離線註冊功能。  
用戶端可自我啟用。
伺服器 Lockbox。</td>
<td style="border:1px solid black;">所有先前的功能，加上 SP1 的功能。
伺服器離線註冊功能。  
如果是 SP1 用戶端，用戶端可自我啟用。
如果是第 1 版用戶端，用戶端必須透過網際網路啟用。</td>
</tr>
</tbody>
</table>
 

<span id="BKMK_6"></span>
移除 RMS SP1
------------

如果安裝 RMS SP1 之後，想要使 RMS 伺服器回復到先前的設定，則可以使用 \[控制台\] 的 \[新增或移除程式\] 移除 RMS SP1。

**注意**   如果您在安裝 RMS SP1 之前，即備份了設定資料庫，則您可以還原該備份，以完全消除 RMS SP1 所做的全部變更。如果您沒有備份設定資料庫，則可能可以用還原的 RMS 安裝來使用 RMS SP1 安裝的設定資料庫。還原的 RMS 安裝將會忽略 RMS SP1 安裝在設定資料庫中新增的額外欄位，因為不會使用到那些欄位。
