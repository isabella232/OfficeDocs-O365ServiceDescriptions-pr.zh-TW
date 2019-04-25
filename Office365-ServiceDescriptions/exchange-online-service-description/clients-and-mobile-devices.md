---
title: 用戶端和行動裝置
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 04/10/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
ms.openlocfilehash: 380f542c6db323d5dac647dc694c0b320bf13be6
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/25/2019
ms.locfileid: "33246229"
---
# <a name="clients-and-mobile-devices"></a>用戶端和行動裝置

## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook 是電子郵件程式，包含支援行事曆、 連絡人、 工作及下列重要功能：
  
- **MAPI over HTTP**Messaging Application Program Interface (MAPI) over HTTP 可讓 Outlook 使用者透過網際網路，從組織防火牆外部連線至 Exchange Online 信箱。 MAPI over HTTP，Outlook 無所不在的長詞彙取代項目。 此連線方法提供改良的連線恢復能力、 更安全的登入、 擴充性，以及增強功能 IT 和支援。 若要深入了解，請參閱<b0>RPC over HTTP 達到的 Office 365 中支援的結束</b0>> 及 < <b1>MAPI over HTTP</b1>。
    
- **Autodiscover** Autodiscover 服務功能自動設定 Outlook 搭配 Exchange Online 使用。Outlook 使用者首次以電子郵件地址與密碼登入時，能直接由 Exchange Online 接收他們要求的檔案設定。這些設定會以建立並維護使用者設定檔所需的資訊自動更新 Outlook 用戶端。使用 Autodiscover 服務需要 SSL 憑證。此 SSL 憑證僅限於單一的主要 SSL 網域。 
    
- **快取 Exchange 模式** 快取 Exchange 模式功允許M Outlook 使用者在未連線至網際網路時，能存取 Exchange Online 信箱的本機副本。快取 Exchange 模式保存使用者在 Outlook 的 Exchange 信箱之用戶端副本，並自動將此副本與郵件伺服器進行同步處理。我們建議使用快取 Exchange 模式中的 Outlook，因為它提供離線存取，並協助提供回應使用者經驗，即使用戶端與伺服器之間的網路狀況不理想。 
    
依照預設，Outlook 存取對所有使用者開放啟用狀態。管理員可以透過 Windows PowerShell，禁止特定的使用者或群組存取。我們建議使用最新版本的 Outlook--安裝最新版的 service pack--來存取 Exchange Online。 
  
如需哪些 Outlook 用戶端受到 Exchange 2016 和 Exchange Online 支援的詳細資訊，請參閱 [Exchange 2016 系統需求](https://go.microsoft.com/fwlink/?LinkID=828972)中的＜支援的用戶端＞。
  
> [!IMPORTANT]
>  Outlook 不包含在 Exchange Online 的訂閱價格之內。 Microsoft Office Pro Plus（包括 Microsoft Outlook）包含在某些 Office 365 計畫內，並且能以單獨訂閱的方式購買。 如果您使用 POP 連線至 Exchange Online 的電子郵件帳戶，您會看到下列限制： > 沒有行事曆資訊 > 沒有空閒/忙碌資訊 > 否全域通訊清單 > 沒有發送電子郵件 > 透過 POP 連接時，所有的郵件將是 downlo用戶端和有將 aded 是沒有多部電腦或裝置 （例如筆電膝上型電腦和手機） 之間的同步處理。 
  
## <a name="outlook-on-the-web"></a>Outlook 網頁版

Outlook 網頁版是網路架構版本的 Outlook 電子郵件程式，搭配 Exchange Online 使用。它能讓使用者透過網路瀏覽器接存取電子郵件、行事曆，以及聯絡人，不無論他們在哪裡連接網際網路。如需有關支援瀏覽器的詳細資訊，請參閱[商務用 Outlook 網頁版支援的瀏覽器](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006)。
  
Outlook 網頁版有兩種用戶端版本，皆可搭配 Exchange Online 使用：
  
- **Outlook 網頁版** Outlook 網頁版標準版本提供 Exchange Online 使用者和 Outlook 使用者如出一轍的郵件傳送體驗。它支援最新的網路瀏覽器，無論使用平板電腦、智慧型手機、桌上型電腦和筆電，都提供高效能運用。使用者可以讀取和傳送郵件、組織連絡人，以及排定約會與會議。預設的以活動為基礎的逾時是設定為 6 小時，但是可以 [由系統管理員在 Windows PowerShell 中設定](https://go.microsoft.com/fwlink/p/?LinkId=399155)，從 5 分鐘到 8 小時不等。這個逾時取決於 Web 應用程式內的使用者互動，例如按一下按鈕或選取某個郵件。另外也有由安全性驅動的個別逾時，這個逾時無法設定且不論使用者活動如何都會發生。如果使用者已經登入長達 8 小時，OWA 將會自動把使用者登出並要求重新驗證。 
    
- **Outlook 網頁精簡版** Outlook 網頁精簡版可讓使用者透過任一種網路瀏覽器存取信箱。使用者可以讀取和傳送郵件、組織連絡人，以及排定約會與會議。預設的以活動為基礎的逾時是設定為 6 小時，但是可以 [由系統管理員在 Windows PowerShell 中設定](https://go.microsoft.com/fwlink/p/?LinkId=399155)，從 5 分鐘到 8 小時不等。這個逾時取決於 Web 應用程式內的使用者互動，例如按一下按鈕或選取某個郵件。另外也有由安全性驅動的個別逾時，這個逾時無法設定且不論使用者活動如何都會發生。如果使用者已經登入長達 8 小時，精簡版的 OWA 將會自動把使用者登出並要求重新驗證。 
    
Outlook 網頁版也有行動版本。如需詳細資訊，請參閱[此頁面](http://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409)。
  
## <a name="outlook-for-mac"></a>Mac 版 Outlook

Exchange Online 支援 Microsoft Outlook for Mac，提供電子郵件、 行事曆、 地址簿、 工作清單，以及備註清單。
  
## <a name="outlook-for-ios-android-and-windows-phone"></a>Outlook for iOS、 Android 和 Windows Phone

Outlook 相關應用程式適用於 iOS、 Android 和 Windows Phone 與 Exchange Online 運作。 在任何這些裝置，使用應用程式市集，尋找 Outlook 應用程式。 以下是行動裝置 OS 明細。
  
|||||
|:-----|:-----|:-----|:-----|
|裝置  <br/> |Android  <br/> |iOS  <br/> |Windows Phone  <br/> |
|Outlook 行動應用程式可用性  <br/> |是  <br/> [取得 Android 版 Outlook](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |是  <br/> [取得適用於 iOS 的 Outlook](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |內建  <br/> |
|與 Exchange Online 相容的內建的電子郵件應用程式  <br/> |Gmail 應用程式/Samsung 電子郵件應用程式  <br/> |ios 電子郵件應用程式  <br/> |Outlook 郵件、 行事曆、 連絡人  <br/> |
|詳細資訊  <br/> |[Android 的行動裝置設定](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[iPhone 或 iPad 的安裝程式](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[Windows Phone 安裝程式](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |
   
也有使用裝置，包括 Blackberry 使用 Exchange Online 的選項。
  
### <a name="feature-availability"></a>功能可用性

Outlook 會讓使用者快速且容易了解電子郵件和行事曆體驗，預期現代行動應用程式，從時所提供的 Office 365 的最佳功能支援僅應用程式。 它是特別設計用來支援完整的 Office 365 體驗，請授與使用者的一致的體驗從桌面行動唯一的電子郵件應用程式。 Outlook 整合 Intune、 企業行動力與安全性和 Exchange 控制以保護資料和使用者的安全。
  
Outlook 可讓使用者：
  
- 從行動裝置管理其整個天。
    
- 連線到應用程式，也須能生產力，同時保持其工作和個人資訊分開及安全的服務。
    
Outlook for iOS、 Android 版 Outlook 或 Outlook for Windows Phone 中，使用者可以進行下列作業： 
  
- 享有焦點收件匣的優先順序重要的電子郵件
    
- 自訂以符合其唯一的電子郵件習慣往撥動手勢
    
- 建立可直接加入在行事曆，以提供一眼的重要資訊的旅遊行程
    
- 從收件匣 RSVP 加入會議。
    
- 電子郵件中使用直覺式的圖示，並協助他們的行事曆約會快速處理資訊
    
- 所有裝置上使用一致且熟悉的 Outlook 經驗
    
- 輕鬆地啟動並加入從行事曆的 Skype 會議
    
- 讀取和回應 IRM 加密和保護電子郵件
    
- 儲存在商務用 OneDrive 中共用檔案
    
- 點選 [設定自動回覆
    
- 檢視及管理共用與委派的行事曆
    
- 搜尋與一些點選其公司的全域通訊清單
    
- 檢視同事的可用性和排程適用於所有人的會議時間
    
- 請參閱受邀者接受、 暫訂，並拒絕狀態
    
- 共用權限從其電話的行事曆
    
- 啟動並加入 Skype 會議右，從行事曆
    
- 存取公司與個人的行事曆在一個位置，而不切換應用程式
    
## <a name="exchange-activesync"></a>Exchange ActiveSync

Exchange Online 支援 Microsoft Exchange ActiveSync 協定，將行動裝置與 Exchange Online 之間的信箱資料同步處理，使用者便能隨時隨地存取電子郵件、行事曆、聯絡人和工作。
  
Exchange ActiveSync 可與各種行動裝置相容，包括 Microsoft Windows Phone、Apple iPhone 和 iPad，以及 Android 手機和平板電腦。 除了手機和裝置，Windows Phone 的郵件應用程式連線到 Exchange Online 使用 Exchange ActiveSync。 目前 Exchange ActiveSync 授權條款的完整清單可在 Exchange ActiveSync Licensing 網站查閱。
  
如需 Exchange ActiveSync 的詳細資訊，請參閱[Exchange ActiveSync](https://go.microsoft.com/fwlink/p/?LinkId=271792)。
  
> [!IMPORTANT]
> 每個信箱的 Exchange ActiveSync 裝置數目上限是 100。 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a>以 Exchange Web Services（EWS）研發的應用程式

 以 Exchange Web Services (EWS) 或 EWS Managed API 開發的應用程式，可讓管理員從執行於內部部署、Azure 或其他託管服務中的應用程式，存取儲存在 Exchange Online 那邊的資料。 
  
如需以 Exchange Web 服務開發之應用程式的詳細資訊，請參閱 [Exchange 中的 Web 服務](https://go.microsoft.com/fwlink/?LinkId=325346)。
  
## <a name="pop-and-imap"></a>POP 與 IMAP

Exchange Online 支援透過 POP3 和 IMAP4 協定的信箱存取。POP 和 IMAP 存取要求使用 SSL 加密。預設情況下，為所有使用者啟用 POP。使用者能在 Outlook 網頁版中檢視他們的 POP 和 IMAP 連線設定。管理員可以對個別使用者分別禁用 POP 和 IMAP 存取。
  
如需 POP3 和 IMAP4 連線的相關資訊，請參閱 [POP3 和 IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070)。
  
## <a name="smtp"></a>SMTP

簡易郵件傳輸通訊協定（SMTP）是用來發送外寄郵件給透過 IMAP 或 POP 連線至 Exchange Online 的客戶端。它是路由和通過 Exchange 伺服器傳遞的主協定。Exchange Online 為需要 SMTP 郵件提交的授權內部客戶應用程式提供兩種型態的 SMTP 轉送服務：
  
- SMTP 郵件提交給託管環境內的使用者。
    
- 已通過驗證的 SMTP 郵件將轉送到託管環境的外部地址。
    
> [!IMPORTANT]
> 需要授權的來源伺服器 IP 位址以允許 SMTP 轉送。使用 SMTP 寄送郵件時，需要傳輸層安全性（TLS）加密與驗證。 
  
## <a name="blackberry-devices"></a>BlackBerry® 裝置

透過 Exchange ActiveSync BlackBerry® 裝置上使用 office 365 電子郵件。 若要找出您的選項為何，請參閱下列主題：
  
- [BlackBerry 裝置上設定電子郵件](https://go.microsoft.com/fwlink/?linkid=863394)
    
- [BlackBerry 裝置 7.1 上設定電子郵件 OS 和更早版本](https://go.microsoft.com/fwlink/?linkid=863403)
    
如需詳細資訊，請參閱 [BlackBerry](../office-365-platform-service-description/blackberry.md)。
  
> [!NOTE]
> 如果您在中國使用 21Vianet 運作的 Office 365，將無法使用 BlackBerry Business 雲端服務。不過您可以使用 Exchange ActiveSync 裝置或 Research in Motion 的產品 (RIM、BlackBerry 無線電子郵件解決方案) 來執行 BlackBerry 企業伺服器 (BES)。 
  
## <a name="feature-availability"></a>功能可用性

若要檢視 Office 365 計劃、獨立選項和內部部署解決方案中的功能可用性，請參閱 [Exchange Online 服務說明](exchange-online-service-description.md)。
  

