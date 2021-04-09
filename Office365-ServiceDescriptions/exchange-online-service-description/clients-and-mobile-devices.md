---
title: 用戶端和行動裝置
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
description: Exchange Online 可搭配桌面和 mobile 版本的 Outlook 以及網頁上的 Outlook 使用。
ms.openlocfilehash: 3aa0c2bbdf9b55b6a3544919143fd9d5e5cfed24
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653115"
---
# <a name="clients-and-mobile-devices"></a>用戶端和行動裝置

## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook 是一項電子郵件程式，其中包含對行事曆、連絡人、工作及下列主要功能的支援：
  
- **Mapi OVER HTTP** -郵件應用程式介面 (mapi) over Http 允許 Outlook 使用者從其組織防火牆外，透過網際網路連線至 Exchange Online 信箱。 MAPI over HTTP，長期取代 Outlook Anywhere。 這種連線方式可提供更好的連線恢復功能、更安全的登入、擴充性，以及 IT 和支援的增強功能。 若要深入瞭解，請參閱 [RPC OVER HTTP 的支援終止于 Office 365](/exchange/troubleshoot/administration/rpc-over-http-end-of-support) 和 [MAPI over HTTP](/exchange/mapi-over-http-exchange-2013-help)。

- **自動** 探索-自動探索服務功能會自動設定 Outlook 搭配 Exchange Online 使用。 Outlook 使用者首次以電子郵件地址與密碼登入時，能直接由 Exchange Online 接收他們要求的檔案設定。 這些設定會以建立並維護使用者設定檔所需的資訊自動更新 Outlook 用戶端。 使用 Autodiscover 服務需要 SSL 憑證。 此 SSL 憑證僅限於單一的主要 SSL 網域。 

- 快取 **Exchange 模式**-快取 exchange 模式功能可讓 Outlook 使用者在未連線至網際網路的情況下，存取其 Exchange Online 信箱的本機複本。 快取 Exchange 模式保存使用者在 Outlook 的 Exchange 信箱之用戶端副本，並自動將此副本與郵件伺服器進行同步處理。 我們建議使用快取 Exchange 模式中的 Outlook，因為它提供離線存取，並協助提供回應使用者經驗，即使用戶端與伺服器之間的網路狀況不理想。 

依照預設，Outlook 存取對所有使用者開放啟用狀態。管理員可以透過 Windows PowerShell，禁止特定的使用者或群組存取。我們建議使用最新版本的 Outlook--安裝最新版的 service pack--來存取 Exchange Online。 
  
如需 Exchange 2016 和 Exchange Online 所支援之 Outlook 用戶端的相關資訊，請參閱 [Office 的系統需求](https://products.office.com/office-system-requirements)。 

Microsoft 365 專為與最新的 Office 和 Office 版本搭配使用而設計。 如果您使用舊版的瀏覽器和不在主流支援的 Office 版本，請執行下列步驟：

- Microsoft 不會故意阻止您連線至服務，但您的經驗品質會隨著時間而降低。
- Microsoft 不會提供軟體更新，以解決與不安全相關的問題。

> [!IMPORTANT]
> Outlook 不包含在 Exchange Online 的訂閱價格之內。 Microsoft 365 for enterprise (包含 Microsoft Outlook) 包含在某些方案中，而且可以以個別訂閱形式購買。 如果您使用 POP 連線至 Exchange Online 電子郵件帳戶，您將會看到下列限制：
> - 沒有行事曆資訊
>- 沒有空閒/忙碌資訊
>- 無全域通訊清單
>- 無推入電子郵件
>- 透過 POP 連線時，會將所有郵件下載到用戶端，而且在多部電腦或裝置之間不會進行同步處理 (例如，在膝上型電腦與電話) 之間。 
  
## <a name="outlook-on-the-web"></a>Outlook 網頁版

Outlook 網頁版是網路架構版本的 Outlook 電子郵件程式，搭配 Exchange Online 使用。 它可讓使用者透過網頁瀏覽器存取其電子郵件、行事曆和連絡人，而不論他們連線至網際網路的任何地方。 如需有關支援瀏覽器的詳細資訊，請參閱[商務用 Outlook 網頁版支援的瀏覽器](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006)。
  
Outlook 網頁版有兩種用戶端版本，皆可搭配 Exchange Online 使用：
  
- **網頁** 型 outlook-web 上的 outlook standard 版本為 Exchange Online 使用者提供與 Outlook 使用者類似的通訊經驗。 它支援最新的網路瀏覽器，無論使用平板電腦、智慧型手機、桌上型電腦和筆電，都提供高效能運用。 使用者可以讀取和傳送郵件、組織連絡人，以及排定約會與會議。 預設的以活動為基礎的逾時是設定為 6 小時，但是可以 [由系統管理員在 Windows PowerShell 中設定](/powershell/module/exchange/set-organizationconfig)，從 5 分鐘到 8 小時不等。 此超時取決於 web 應用程式中的使用者互動，例如選取按鈕或選取郵件。 另外也有由安全性驅動的個別逾時，這個逾時無法設定且不論使用者活動如何都會發生。 如果使用者已經登入長達 8 小時，OWA 將會自動把使用者登出並要求重新驗證。 

- **Web 上的 outlook** 的精簡版-web 上的低版本 outlook 可讓 Exchange Online 使用者使用幾乎任何網頁瀏覽器存取信箱。 使用者可以讀取和傳送郵件、組織連絡人，以及排定約會與會議。 預設的以活動為基礎的逾時是設定為 6 小時，但是可以 [由系統管理員在 Windows PowerShell 中設定](/powershell/module/exchange/set-organizationconfig)，從 5 分鐘到 8 小時不等。 此超時取決於 web 應用程式中的使用者互動，例如選取按鈕或選取郵件。 另外也有由安全性驅動的個別逾時，這個逾時無法設定且不論使用者活動如何都會發生。 如果使用者已經登入長達 8 小時，精簡版的 OWA 將會自動把使用者登出並要求重新驗證。 

Outlook 網頁版也有行動版本。 如需詳細資訊，請參閱[此頁面](https://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409)。
  
## <a name="outlook-for-mac"></a>Mac 版 Outlook

Exchange Online 支援 Microsoft Outlook for Mac，可提供電子郵件、行事曆、通訊錄、工作清單及附注清單。
  
## <a name="outlook-for-ios-android-and-windows-phone"></a>適用于 iOS、Android 和 Windows Phone 的 Outlook

Exchange Online 適用于適用于 iOS、Android 和 Windows Phone 的 Outlook app。 在上述任一裝置上，使用 app store 尋找 Outlook 應用程式。 以下是移動作業系統的分解。<br><br>
  
| 裝置 | Android | iOS | Windows Phone |
|:-----|:-----|:-----|:-----|
|Outlook 行動應用程式可用性  <br/> |是  <br/> [取得適用于 Android 的 Outlook](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |是  <br/> [取得 iOS 的 Outlook](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |內建  <br/> |
|與 Exchange Online 相容的內建電子郵件應用程式  <br/> |Gmail app/Samsung 電子郵件應用程式  <br/> |iOS 郵件應用程式  <br/> |Outlook 郵件、行事曆、連絡人  <br/> |
|其他資訊  <br/> |[Android mobile 設定](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[iPhone 或 iPad 安裝程式](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[Windows Phone 設定](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |

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
  
如需 Exchange ActiveSync 的詳細資訊，請參閱 [exchange ActiveSync](/exchange/clients-and-mobile-in-exchange-online/clients-and-mobile-in-exchange-online)。
  
> [!IMPORTANT]
> 每個信箱的 Exchange ActiveSync 裝置數目上限是 100。 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a>以 Exchange Web Services（EWS）研發的應用程式

 以 Exchange Web Services (EWS) 或 EWS Managed API 開發的應用程式，可讓管理員從執行於內部部署、Azure 或其他託管服務中的應用程式，存取儲存在 Exchange Online 那邊的資料。 
  
如需以 Exchange Web 服務開發之應用程式的詳細資訊，請參閱 [Exchange 中的 Web 服務](/exchange/client-developer/exchange-web-services/explore-the-ews-managed-api-ews-and-web-services-in-exchange)。
  
## <a name="pop-and-imap"></a>POP 與 IMAP

Exchange Online 支援透過 POP3 和 IMAP4 協定的信箱存取。POP 和 IMAP 存取要求使用 SSL 加密。預設情況下，為所有使用者啟用 POP。使用者能在 Outlook 網頁版中檢視他們的 POP 和 IMAP 連線設定。管理員可以對個別使用者分別禁用 POP 和 IMAP 存取。
  
如需 POP3 和 IMAP4 連線的相關資訊，請參閱 [POP3 和 IMAP4](/exchange/pop3-and-imap4-in-exchange-server-2013-exchange-2013-help)。
  
## <a name="smtp"></a>SMTP

簡易郵件傳輸通訊協定（SMTP）是用來發送外寄郵件給透過 IMAP 或 POP 連線至 Exchange Online 的客戶端。它是路由和通過 Exchange 伺服器傳遞的主協定。Exchange Online 為需要 SMTP 郵件提交的授權內部客戶應用程式提供兩種型態的 SMTP 轉送服務：
  
- SMTP 郵件提交給託管環境內的使用者。

- 已通過驗證的 SMTP 郵件將轉送到託管環境的外部地址。

> [!IMPORTANT]
> 需要授權的來源伺服器 IP 位址以允許 SMTP 轉送。使用 SMTP 寄送郵件時，需要傳輸層安全性（TLS）加密與驗證。 
  
## <a name="blackberry-devices"></a>BlackBerry 裝置

電子郵件可透過 &reg; Exchange ActiveSync 在 BlackBerry 裝置上。 若要瞭解您的選項是什麼，請參閱下列主題：
  
- [在 BlackBerry 裝置上設定電子郵件](https://go.microsoft.com/fwlink/?linkid=863394)

- [在 BlackBerry 裝置上設定電子郵件7.1 作業系統及更早版本](https://go.microsoft.com/fwlink/?linkid=863403)

如需詳細資訊，請參閱 [BlackBerry](../office-365-platform-service-description/blackberry.md)。
  
> [!NOTE]
> 如果您在中國使用 21Vianet 運作的 Office 365，將無法使用 BlackBerry Business 雲端服務。不過您可以使用 Exchange ActiveSync 裝置或 Research in Motion 的產品 (RIM、BlackBerry 無線電子郵件解決方案) 來執行 BlackBerry 企業伺服器 (BES)。 
  
## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱 [Exchange Online 服務說明](exchange-online-service-description.md)。
