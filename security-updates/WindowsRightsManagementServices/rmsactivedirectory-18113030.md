---
TOCTitle: 支援 RMS 的 Active Directory
Title: 支援 RMS 的 Active Directory
ms:assetid: '9589127d-19b3-44f1-b7a1-01992e78218a'
ms:contentKeyID: 18113030
ms:mtpsurl: 'https://technet.microsoft.com/zh-tw/library/Cc747604(v=WS.10)'
---

支援 RMS 的 Active Directory
============================

RMS 可將 Active Directory 用於下列用途：

-   **提供使用者驗證。** Active Directory 可提供用於驗證 RMS 使用者的目錄服務。如需關於驗證與 RMS 的詳細資訊，請參閱本主題後面的＜[RMS 安全性模式](https://technet.microsoft.com/665db831-366d-4dca-9bb3-cc2912481fe1)＞。
-   **解析群組成員與個別使用者的帳號憑證。** Active Directory 可提供發行授權向群組 (而不是個別使用者帳號) 授予權限時，RMS 將授予受 RMS 保護內容的使用授權之群組成員的資訊。為減少在 Active Directory 中執行 LDAP 查詢的數量，RMS 會快取在本機快取中取得的資訊，還會快取集中目錄服務資料庫裡取得的資訊。如需詳細資訊，請參閱本主題前面的＜[RMS Active Directory 快取](https://technet.microsoft.com/c721a2eb-2fe9-4346-b426-3cc169b97265)＞與＜[RMS 目錄服務資料庫](https://technet.microsoft.com/6f6b8586-5d17-4a40-94a3-4dc738195301)＞。
-   **儲存 RMS 服務探索位置。** 服務要求 (例如，使用授權、發行授權或授權伺服器的子註冊的要求) 必須傳送至授予要求之 Web 服務可執行模組的 URL。所有服務要求都從 Active Directory 查詢伺服器 Web 服務 (Server.asmx) 的 URL 開始，接著會為服務要求提供正確的 URL。如需詳細資訊，請參閱本主題後面的＜[RMS 服務發行與探索](https://technet.microsoft.com/336c0d55-fd7f-4aa9-b3e6-bfd6565b1086)＞。
