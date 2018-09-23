---
title: 用戶端和行動裝置
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
ms.openlocfilehash: ad19845f7a06cfb01a74507fdb794813091c1c2b
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035385"
---
# <a name="clients-and-mobile-devices"></a>用戶端和行動裝置

## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook 是包含行事曆、 連絡人、 工作及下列重要功能，包括支援的電子郵件程式：
  
- **MAPI over HTTP**Over HTTP 通訊應用程式介面 (MAPI) 可讓 Outlook 使用者透過網際網路其組織防火牆外部連線到 Exchange Online 信箱。MAPI over HTTP，Outlook 無所不在 」 的長期取代。此連線方法提供改善的連線恢復能力、 更安全登入、 擴充性，以及增強功能的 IT 和支援。若要深入了解，請參閱[RPC over HTTP 達到的 Office 365 中支援的結束](https://go.microsoft.com/fwlink/?linkid=863890)及[MAPI over HTTP](https://go.microsoft.com/fwlink/?linkid=393041)。
    
- **Autodiscover** Autodiscover 服務功能自動設定 Outlook 搭配 Exchange Online 使用。Outlook 使用者首次以電子郵件地址與密碼登入時，能直接由 Exchange Online 接收他們要求的檔案設定。這些設定會以建立並維護使用者設定檔所需的資訊自動更新 Outlook 用戶端。使用 Autodiscover 服務需要 SSL 憑證。此 SSL 憑證僅限於單一的主要 SSL 網域。 
    
- **快取 Exchange 模式** 快取 Exchange 模式功允許M Outlook 使用者在未連線至網際網路時，能存取 Exchange Online 信箱的本機副本。快取 Exchange 模式保存使用者在 Outlook 的 Exchange 信箱之用戶端副本，並自動將此副本與郵件伺服器進行同步處理。我們建議使用快取 Exchange 模式中的 Outlook，因為它提供離線存取，並協助提供回應使用者經驗，即使用戶端與伺服器之間的網路狀況不理想。 
    
依照預設，Outlook 存取對所有使用者開放啟用狀態。管理員可以透過 Windows PowerShell，禁止特定的使用者或群組存取。我們建議使用最新版本的 Outlook--安裝最新版的 service pack--來存取 Exchange Online。 
  
如需哪些 Outlook 用戶端受到 Exchange 2016 和 Exchange Online 支援的詳細資訊，請參閱 [Exchange 2016 系統需求](https://go.microsoft.com/fwlink/?LinkID=828972)中的＜支援的用戶端＞。
  
> [!IMPORTANT]
>  Outlook 不包含在 Exchange Online 的訂閱價格之內。Microsoft Office Pro Plus（包括 Microsoft Outlook）包含在某些 Office 365 計畫內，並且能以單獨訂閱的方式購買。 >  如果您使用 POP 與 Exchange Online 電子郵件帳戶連線，您會看到下列限制︰ >  沒有行事曆資訊 >  沒有空閒/忙碌資訊 >  沒有全球通訊清單 >  沒有行動郵件 >  透過 POP 連接時，所有郵件都會被下載到用戶端，不會在多部電腦或裝置之間（例如筆電和手機）進行同步處理。 
  
## <a name="outlook-on-the-web"></a>網頁型 Outlook

Outlook 網頁版是網路架構版本的 Outlook 電子郵件程式，搭配 Exchange Online 使用。它能讓使用者透過網路瀏覽器接存取電子郵件、行事曆，以及聯絡人，不無論他們在哪裡連接網際網路。如需有關支援瀏覽器的詳細資訊，請參閱[商務用 Outlook 網頁版支援的瀏覽器](https://go.microsoft.com/fwlink/p/?LinkId=287032)。
  
Outlook 網頁版有兩種用戶端版本，皆可搭配 Exchange Online 使用：
  
- **Outlook 網頁版** Outlook 網頁版標準版本提供 Exchange Online 使用者和 Outlook 使用者如出一轍的郵件傳送體驗。它支援最新的網路瀏覽器，無論使用平板電腦、智慧型手機、桌上型電腦和筆電，都提供高效能運用。使用者可以讀取和傳送郵件、組織連絡人，以及排定約會與會議。預設的以活動為基礎的逾時是設定為 6 小時，但是可以 [由系統管理員在 Windows PowerShell 中設定](https://go.microsoft.com/fwlink/p/?LinkId=399155)，從 5 分鐘到 8 小時不等。這個逾時取決於 Web 應用程式內的使用者互動，例如按一下按鈕或選取某個郵件。另外也有由安全性驅動的個別逾時，這個逾時無法設定且不論使用者活動如何都會發生。如果使用者已經登入長達 8 小時，OWA 將會自動把使用者登出並要求重新驗證。 
    
- **Outlook 網頁精簡版** Outlook 網頁精簡版可讓使用者透過任一種網路瀏覽器存取信箱。使用者可以讀取和傳送郵件、組織連絡人，以及排定約會與會議。預設的以活動為基礎的逾時是設定為 6 小時，但是可以 [由系統管理員在 Windows PowerShell 中設定](https://go.microsoft.com/fwlink/p/?LinkId=399155)，從 5 分鐘到 8 小時不等。這個逾時取決於 Web 應用程式內的使用者互動，例如按一下按鈕或選取某個郵件。另外也有由安全性驅動的個別逾時，這個逾時無法設定且不論使用者活動如何都會發生。如果使用者已經登入長達 8 小時，精簡版的 OWA 將會自動把使用者登出並要求重新驗證。 
    
Outlook 網頁版也有行動版本。如需詳細資訊，請參閱[此頁面](http://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409)。
  
## <a name="outlook-for-mac"></a>Mac 版 Outlook

Exchange Online 支援 Microsoft Outlook for Mac，提供電子郵件、 行事曆、 地址簿、 工作清單和備註清單。
  
## <a name="outlook-for-ios-android-and-windows-phone"></a>IOS、 Android、 及 Windows Phone 的 outlook

Outlook 相關應用程式適用於 iOS、 Android、 及 Windows Phone 與 Exchange Online 運作。在任何這些裝置上使用的應用程式存放區來尋找 Outlook 應用程式。以下是分解行動 os。
  
|||||
|:-----|:-----|:-----|:-----|
|裝置  <br/> |Android  <br/> |iOS  <br/> |Windows Phone  <br/> |
|Outlook 行動裝置應用程式可用性  <br/> |是  <br/> [取得 Outlook for android （英文)](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |是  <br/> [取得 iOS 的 Outlook](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |內建  <br/> |
|與 Exchange Online 相容的內建的電子郵件應用程式  <br/> |Gmail 應用程式/Samsung 電子郵件應用程式  <br/> |iOS 郵件應用程式  <br/> |Outlook 郵件、 行事曆、 連絡人  <br/> |
|詳細資訊  <br/> |[Android 行動裝置的安裝程式](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[iPhone 或 iPad 的安裝程式](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[Windows Phone 安裝程式](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |
   
也有包括 Blackberry 裝置搭配使用 Exchange Online 的選項。
  
### <a name="feature-availability"></a>功能可用性

Outlook 會讓使用者快速且直覺式電子郵件和行事曆的體驗他們預期從現代的行動裝置應用程式時所提供支援的 Office 365 的最佳功能僅應用程式。它是特別設計來支援完整的 Office 365 體驗，讓使用者有一致的體驗從桌面至行動裝置的唯一電子郵件應用程式。Outlook 整合 Intune、 企業行動性及安全性和保護資料和使用者的安全 Exchange 控制項。
  
Outlook 可讓使用者：
  
- 從行動裝置管理其整個一天。
    
- 連線到應用程式及服務所需要提高工作效率，同時個別及安全保持其工時和個人資訊。
    
IOS for Android、 Outlook 或 Outlook for Windows Phone 的 Outlook 使用者可以進行下列作業： 
  
- 獲益具有焦點的收件匣的優先順序重要電子郵件
    
- 自訂以符合其唯一的電子郵件習慣往撥動手勢
    
- 建立可新增到行事曆的重要資訊可用一覽直接的旅遊行程
    
- 從收件匣 RSVP 加入會議。
    
- 用於協助他們快速處理資訊的電子郵件和行事曆約會直覺式圖示
    
- 所有裝置都使用始終如一且熟悉的 Outlook 經驗
    
- 輕鬆地啟動並加入 Skype 會議遠行事曆
    
- 讀取和回應 IRM 加密及受保護的電子郵件
    
- 儲存在 OneDrive for Business 的共用檔案
    
- 使用點選 [設定自動回覆
    
- 檢視及管理共用和委派的行事曆
    
- 使用幾個的點選搜尋其公司的全域通訊清單
    
- 檢視同事的可用性及排程適用於所有人的會議時間
    
- 請參閱受邀者接受、 訂、 和拒絕狀態
    
- 共用行事曆右從其電話
    
- 啟動並加入 Skype 會議右從行事曆
    
- 存取工時和一個位置，而不切換應用程式的個人行事曆
    
## <a name="exchange-activesync"></a>Exchange ActiveSync

Exchange Online 支援 Microsoft Exchange ActiveSync 協定，將行動裝置與 Exchange Online 之間的信箱資料同步處理，使用者便能隨時隨地存取電子郵件、行事曆、聯絡人和工作。
  
各種行動裝置使用 Exchange ActiveSync，包括 Microsoft Windows Phone、 Apple iPhone 與 iPad 及 Android 電話與平板電腦。除了行動電話與裝置、 Windows Phone 的郵件應用程式會使用 Exchange ActiveSync 連線到 Exchange Online。目前的 Exchange ActiveSync 使用人均的完整清單位在 Exchange ActiveSync 授權站台。
  
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

透過 Exchange ActiveSync BlackBerry® 裝置上使用 office 365 電子郵件。若要了解您的選項，請參閱下列主題：
  
- [BlackBerry 裝置上設定電子郵件](https://go.microsoft.com/fwlink/?linkid=863394)
    
- [BlackBerry 裝置 7.1 上設定電子郵件 OS 或更早版本](https://go.microsoft.com/fwlink/?linkid=863403)
    
如需詳細資訊，請參閱 [BlackBerry](../office-365-platform-service-description/blackberry.md)。
  
> [!NOTE]
> 如果您在中國使用 21Vianet 運作的 Office 365，將無法使用 BlackBerry Business 雲端服務。不過您可以使用 Exchange ActiveSync 裝置或 Research in Motion 的產品 (RIM、BlackBerry 無線電子郵件解決方案) 來執行 BlackBerry 企業伺服器 (BES)。 
  
## <a name="feature-availability"></a>功能可用性

若要檢視 Office 365 計劃、獨立選項和內部部署解決方案中的功能可用性，請參閱 [Exchange Online 服務說明](exchange-online-service-description.md)。
  

