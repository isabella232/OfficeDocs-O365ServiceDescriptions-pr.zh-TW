---
title: 用戶端和行動裝置
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
ms.openlocfilehash: a09609e81d9d179dcd156db886913d3124b2e16f
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132967"
---
# <a name="clients-and-mobile-devices"></a>用戶端和行動裝置

## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook 是一項電子郵件程式，其中包含對行事曆、連絡人、工作及下列主要功能的支援：
  
- **MAPI OVER HTTP**郵件應用程式介面（MAPI） over HTTP 允許 Outlook 使用者從其組織防火牆以外的網際網路連線至 Exchange Online 信箱。 MAPI over HTTP，長期取代 Outlook Anywhere。 這種連線方式可提供更好的連線恢復功能、更安全的登入、擴充性，以及 IT 和支援的增強功能。 若要深入瞭解，請參閱[RPC OVER HTTP 的支援終止于 Office 365](https://go.microsoft.com/fwlink/?linkid=863890)和[MAPI over HTTP](https://go.microsoft.com/fwlink/?linkid=393041)。

- **Autodiscover** The Autodiscover service feature automatically configures Outlook to work with Exchange Online. Outlook users can receive their required profile settings directly from Exchange Online the first time they sign in with their email address and password. These settings automatically update the Outlook client with the information necessary to create and maintain the user's profile. An SSL certificate is required to use the Autodiscover service. This SSL certificate is limited to a single primary SSL domain. 

- 快取**Exchange 模式**「快取 Exchange 模式」功能可讓 Outlook 使用者在未連線至網際網路時，存取其 Exchange Online 信箱的本機複本。 快取 Exchange 模式保存使用者在 Outlook 的 Exchange 信箱之用戶端副本，並自動將此副本與郵件伺服器進行同步處理。 我們建議使用快取 Exchange 模式中的 Outlook，因為它提供離線存取，並協助提供回應使用者經驗，即使用戶端與伺服器之間的網路狀況不理想。 

By default, Outlook access is enabled for all users. Administrators can disable access for specific users or groups through Windows PowerShell. We recommend using the latest version of Outlook—with the latest service pack installed—to access Exchange Online. 
  
如需 Exchange 2016 和 Exchange Online 所支援之 Outlook 用戶端的相關資訊，請參閱[Office 的系統需求](https://products.office.com/office-system-requirements)。 

Microsoft 365 專為與最新的 Office 和 Office 版本搭配使用而設計。 如果您使用舊版的瀏覽器和不在主流支援的 Office 版本，請執行下列步驟：

- Microsoft 不會故意阻止您連線至服務，但您的經驗品質會隨著時間而降低。
- Microsoft 不會提供軟體更新，以解決與不安全相關的問題。

> [!IMPORTANT]
>  Outlook 不包含在 Exchange Online 的訂閱價格之內。 適用于企業的 Microsoft 365 應用程式（包括 Microsoft Outlook）包含在某些方案中，而且可以以個別訂閱形式購買。 如果您使用 POP 連線至 Exchange Online 電子郵件帳戶，將會看到下列限制： > 沒有任何行事曆資訊 > 沒有空閒/忙碌 > 資訊 > 沒有任何的電子郵件 > 當透過 POP 連線時，所有郵件都會下載至用戶端，而且在多部電腦或裝置之間（例如，膝上型電腦和電話），將不會進行同步處理。 
  
## <a name="outlook-on-the-web"></a>Outlook 網頁版

Outlook 網頁版是網路架構版本的 Outlook 電子郵件程式，搭配 Exchange Online 使用。 它可讓使用者透過網頁瀏覽器存取其電子郵件、行事曆和連絡人，而不論他們連線至網際網路的任何地方。 如需有關支援瀏覽器的詳細資訊，請參閱[商務用 Outlook 網頁版支援的瀏覽器](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006)。
  
Outlook 網頁版有兩種用戶端版本，皆可搭配 Exchange Online 使用：
  
- **Outlook 網頁版** Outlook 網頁版標準版本提供 Exchange Online 使用者和 Outlook 使用者如出一轍的郵件傳送體驗。 它支援最新的網路瀏覽器，無論使用平板電腦、智慧型手機、桌上型電腦和筆電，都提供高效能運用。 使用者可以讀取和傳送郵件、組織連絡人，以及排定約會與會議。 預設的以活動為基礎的逾時是設定為 6 小時，但是可以 [由系統管理員在 Windows PowerShell 中設定](https://go.microsoft.com/fwlink/p/?LinkId=399155)，從 5 分鐘到 8 小時不等。 此超時取決於 web 應用程式中的使用者互動，例如選取按鈕或選取郵件。 另外也有由安全性驅動的個別逾時，這個逾時無法設定且不論使用者活動如何都會發生。 如果使用者已經登入長達 8 小時，OWA 將會自動把使用者登出並要求重新驗證。 

- **Outlook 網頁精簡版** Outlook 網頁精簡版可讓使用者透過任一種網路瀏覽器存取信箱。 使用者可以讀取和傳送郵件、組織連絡人，以及排定約會與會議。 預設的以活動為基礎的逾時是設定為 6 小時，但是可以 [由系統管理員在 Windows PowerShell 中設定](https://go.microsoft.com/fwlink/p/?LinkId=399155)，從 5 分鐘到 8 小時不等。 此超時取決於 web 應用程式中的使用者互動，例如選取按鈕或選取郵件。 另外也有由安全性驅動的個別逾時，這個逾時無法設定且不論使用者活動如何都會發生。 如果使用者已經登入長達 8 小時，精簡版的 OWA 將會自動把使用者登出並要求重新驗證。 

Outlook 網頁版也有行動版本。 如需詳細資訊，請參閱[此頁面](https://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409)。
  
## <a name="outlook-for-mac"></a>Mac 版 Outlook

Exchange Online 支援 Microsoft Outlook for Mac，可提供電子郵件、行事曆、通訊錄、工作清單及附注清單。
  
## <a name="outlook-for-ios-android-and-windows-phone"></a>適用于 iOS、Android 和 Windows Phone 的 Outlook

Exchange Online 適用于適用于 iOS、Android 和 Windows Phone 的 Outlook app。 在上述任一裝置上，使用 app store 尋找 Outlook 應用程式。 以下是移動作業系統的分解。
  
|||||
|:-----|:-----|:-----|:-----|
|裝置  <br/> |Android  <br/> |iOS  <br/> |Windows Phone  <br/> |
|Outlook 行動應用程式可用性  <br/> |是  <br/> [取得適用于 Android 的 Outlook](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |是  <br/> [取得 iOS 的 Outlook](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |內建  <br/> |
|與 Exchange Online 相容的內建電子郵件應用程式  <br/> |Gmail app/Samsung 電子郵件應用程式  <br/> |iOS 郵件應用程式  <br/> |Outlook 郵件、行事曆、連絡人  <br/> |
|詳細資訊  <br/> |[Android mobile 設定](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[iPhone 或 iPad 安裝程式](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[Windows Phone 設定](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |

此外，還有一些搭配使用 Exchange Online 和裝置（包括 Blackberry）的選項。
  
### <a name="feature-availability"></a>功能可用性

Outlook 為使用者提供來自現代行動應用程式的快速、直觀的電子郵件和行事歷經驗，同時也是唯一提供最佳功能支援的應用程式。 這是唯一專為支援完整的 Microsoft 體驗而設計的電子郵件應用程式，可讓使用者在桌面與行動裝置上具有連貫的體驗。 Outlook 與 Intune、enterprise 可移動性和 security 和 Exchange 控制項整合，可讓資料和使用者安全。
  
透過 Outlook，使用者可以：
  
- 從行動裝置管理其全天。

- 連線至所需的應用程式和服務，以提高其生產力，同時保持其工作和個人資訊的安全。

使用者可以使用 Outlook for iOS、適用于 Android 的 outlook 或 Outlook for Windows Phone，使用者可以： 
  
- 受益于優先順序重要電子郵件的焦點收件匣

- 自訂滑動筆勢以符合其獨特的電子郵件習慣

- 建立可直接新增至行事曆的旅行行程，並提供快速的重要資訊

- 從收件匣到會議的 RSVP。

- 在電子郵件和行事曆約會中使用直觀的圖示，可協助使用者快速處理資訊

- 在所有裝置中使用一致且熟悉的 Outlook 體驗

- 從行事曆輕鬆啟動及加入 Skype 會議

- 讀取和回應 IRM 加密和受保護的電子郵件

- 在商務用 OneDrive 中共用儲存的檔案

- 使用攻絲設定自動回復

- 查看及管理共用及委派的行事曆

- 使用一些分路器搜尋公司的全域通訊清單

- 查看同事的可用性及排程適用于每個人的會議時間

- 請參閱被邀請者 accept、暫定和拒絕狀態

- 從手機共用行事曆

- 從行事曆開始及加入 Skype 會議

- 在單一位置存取工作和個人行事曆，不需要切換應用程式
    
## <a name="exchange-activesync"></a>Exchange ActiveSync

Exchange Online 支援 Microsoft Exchange ActiveSync 協定，將行動裝置與 Exchange Online 之間的信箱資料同步處理，使用者便能隨時隨地存取電子郵件、行事曆、聯絡人和工作。
  
Exchange ActiveSync 可與各種行動裝置相容，包括 Microsoft Windows Phone、Apple iPhone 和 iPad，以及 Android 手機和平板電腦。 除了行動電話和裝置之外，Windows Phone 中的郵件應用程式也會使用 Exchange ActiveSync 連接至 Exchange Online。 目前 Exchange ActiveSync 授權條款的完整清單可在 Exchange ActiveSync Licensing 網站查閱。
  
如需 Exchange ActiveSync 的詳細資訊，請參閱[exchange ActiveSync](https://go.microsoft.com/fwlink/p/?LinkId=271792)。
  
> [!IMPORTANT]
> 每個信箱的 Exchange ActiveSync 裝置數目上限是 100。 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a>以 Exchange Web Services（EWS）研發的應用程式

 以 Exchange Web Services (EWS) 或 EWS Managed API 開發的應用程式，可讓管理員從執行於內部部署、Azure 或其他託管服務中的應用程式，存取儲存在 Exchange Online 那邊的資料。 
  
如需以 Exchange Web 服務開發之應用程式的詳細資訊，請參閱 [Exchange 中的 Web 服務](https://go.microsoft.com/fwlink/?LinkId=325346)。
  
## <a name="pop-and-imap"></a>POP 與 IMAP

Exchange Online supports mailbox access through both POP3 and IMAP4 protocols. POP and IMAP access requires encryption using SSL. POP is enabled by default for all users. Users can view their POP and IMAP connection settings in Outlook on the web. Administrators can disable POP and IMAP access on a per-user basis.
  
如需 POP3 和 IMAP4 連線的相關資訊，請參閱 [POP3 和 IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070)。
  
## <a name="smtp"></a>SMTP

Simple Mail Transfer Protocol (SMTP) is used to send outbound mail for clients that connect to Exchange Online through IMAP or POP. It is the primary protocol for routing and delivery through Exchange Server. Exchange Online supports two types of SMTP relay services for authorized internal customer applications that require SMTP mail submission:
  
- SMTP 郵件提交給託管環境內的使用者。

- 已通過驗證的 SMTP 郵件將轉送到託管環境的外部地址。

> [!IMPORTANT]
> IP addresses for authorized source servers are required to allow SMTP relay. Transport Layer Security (TLS) encryption and authentication is required when using SMTP to send email. 
  
## <a name="blackberryreg-devices"></a>BlackBerry &reg; 裝置

電子郵件可透過 &reg; Exchange ActiveSync 在 BlackBerry 裝置上。 若要瞭解您的選項是什麼，請參閱下列主題：
  
- [在 BlackBerry 裝置上設定電子郵件](https://go.microsoft.com/fwlink/?linkid=863394)

- [在 BlackBerry 裝置上設定電子郵件7.1 作業系統及更早版本](https://go.microsoft.com/fwlink/?linkid=863403)

如需詳細資訊，請參閱 [BlackBerry](../office-365-platform-service-description/blackberry.md)。
  
> [!NOTE]
> If you are using Office 365 operated by 21Vianet in China, BlackBerry Business Cloud Services is not available. However, you can use Exchange ActiveSync devices or an offering from Research in Motion (RIM, the BlackBerry wireless email solution) to run Blackberry Enterprise Server (BES). 
  
## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online 服務說明](exchange-online-service-description.md)。
  