---
title: 用戶端和行動裝置
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 04/10/2019
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
ms.openlocfilehash: 50272acc0333760f1a85b43539cc0ad244a11f15
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/22/2019
ms.locfileid: "34342722"
---
# <a name="clients-and-mobile-devices"></a><span data-ttu-id="f69c2-102">用戶端和行動裝置</span><span class="sxs-lookup"><span data-stu-id="f69c2-102">Clients and Mobile Devices</span></span>

## <a name="microsoft-outlook"></a><span data-ttu-id="f69c2-103">Microsoft Outlook</span><span class="sxs-lookup"><span data-stu-id="f69c2-103">Microsoft Outlook</span></span>

<span data-ttu-id="f69c2-104">Microsoft Outlook 是電子郵件程式，包含支援行事曆、 連絡人、 工作及下列重要功能：</span><span class="sxs-lookup"><span data-stu-id="f69c2-104">Microsoft Outlook is an email program that includes support for calendar, contacts, tasks, and the following key features:</span></span>
  
- <span data-ttu-id="f69c2-105">**MAPI over HTTP**Messaging Application Program Interface (MAPI) over HTTP 可讓 Outlook 使用者透過網際網路，從組織防火牆外部連線至 Exchange Online 信箱。</span><span class="sxs-lookup"><span data-stu-id="f69c2-105">**MAPI over HTTP** Messaging Application Program Interface (MAPI) over HTTP allows Outlook users to connect to Exchange Online mailboxes over the Internet from outside their organization's firewall.</span></span> <span data-ttu-id="f69c2-106">MAPI over HTTP，Outlook 無所不在的長詞彙取代項目。</span><span class="sxs-lookup"><span data-stu-id="f69c2-106">MAPI over HTTP, the long term replacement for Outlook Anywhere.</span></span> <span data-ttu-id="f69c2-107">此連線方法提供改良的連線恢復能力、 更安全的登入、 擴充性，以及增強功能 IT 和支援。</span><span class="sxs-lookup"><span data-stu-id="f69c2-107">This connectivity method offers improved connection resiliency, more secure sign-in, extensibility, as well as enhancements for IT and support.</span></span> <span data-ttu-id="f69c2-108">若要深入了解，請參閱<b0>RPC over HTTP 達到的 Office 365 中支援的結束</b0>> 及 < <b1>MAPI over HTTP</b1>。</span><span class="sxs-lookup"><span data-stu-id="f69c2-108">To learn more, see [RPC over HTTP reaches end of support in Office 365](https://go.microsoft.com/fwlink/?linkid=863890) and [MAPI over HTTP](https://go.microsoft.com/fwlink/?linkid=393041).</span></span>
    
- <span data-ttu-id="f69c2-p102">**Autodiscover** Autodiscover 服務功能自動設定 Outlook 搭配 Exchange Online 使用。Outlook 使用者首次以電子郵件地址與密碼登入時，能直接由 Exchange Online 接收他們要求的檔案設定。這些設定會以建立並維護使用者設定檔所需的資訊自動更新 Outlook 用戶端。使用 Autodiscover 服務需要 SSL 憑證。此 SSL 憑證僅限於單一的主要 SSL 網域。</span><span class="sxs-lookup"><span data-stu-id="f69c2-p102">**Autodiscover** The Autodiscover service feature automatically configures Outlook to work with Exchange Online. Outlook users can receive their required profile settings directly from Exchange Online the first time they sign in with their email address and password. These settings automatically update the Outlook client with the information necessary to create and maintain the user's profile. An SSL certificate is required to use the Autodiscover service. This SSL certificate is limited to a single primary SSL domain.</span></span> 
    
- <span data-ttu-id="f69c2-p103">**快取 Exchange 模式** 快取 Exchange 模式功允許M Outlook 使用者在未連線至網際網路時，能存取 Exchange Online 信箱的本機副本。快取 Exchange 模式保存使用者在 Outlook 的 Exchange 信箱之用戶端副本，並自動將此副本與郵件伺服器進行同步處理。我們建議使用快取 Exchange 模式中的 Outlook，因為它提供離線存取，並協助提供回應使用者經驗，即使用戶端與伺服器之間的網路狀況不理想。</span><span class="sxs-lookup"><span data-stu-id="f69c2-p103">**Cached Exchange Mode** The Cached Exchange Mode feature allows Outlook users to access local copies of their Exchange Online mailboxes when they are not connected to the Internet. Cached Exchange Mode retains a client-side copy of users' Exchange mailboxes in Outlook and automatically synchronizes this copy with the email server. We recommend using Outlook in Cached Exchange Mode because it provides offline access and helps to provide a responsive user experience even when network conditions between the client and the server are not ideal.</span></span> 
    
<span data-ttu-id="f69c2-p104">依照預設，Outlook 存取對所有使用者開放啟用狀態。管理員可以透過 Windows PowerShell，禁止特定的使用者或群組存取。我們建議使用最新版本的 Outlook--安裝最新版的 service pack--來存取 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="f69c2-p104">By default, Outlook access is enabled for all users. Administrators can disable access for specific users or groups through Windows PowerShell. We recommend using the latest version of Outlook—with the latest service pack installed—to access Exchange Online.</span></span> 
  
<span data-ttu-id="f69c2-120">如需哪些 Outlook 用戶端受到 Exchange 2016 和 Exchange Online 支援的詳細資訊，請參閱 [Exchange 2016 系統需求](https://go.microsoft.com/fwlink/?LinkID=828972)中的＜支援的用戶端＞。</span><span class="sxs-lookup"><span data-stu-id="f69c2-120">For information about which Outlook clients are supported by Exchange 2016 and Exchange Online, see "Supported clients" in [Exchange 2016 system requirements](https://go.microsoft.com/fwlink/?LinkID=828972).</span></span>
  
> [!IMPORTANT]
>  <span data-ttu-id="f69c2-121">Outlook 不包含在 Exchange Online 的訂閱價格之內。</span><span class="sxs-lookup"><span data-stu-id="f69c2-121">Outlook is not provided as part of the Exchange Online subscription price.</span></span> <span data-ttu-id="f69c2-122">Microsoft Office Pro Plus（包括 Microsoft Outlook）包含在某些 Office 365 計畫內，並且能以單獨訂閱的方式購買。</span><span class="sxs-lookup"><span data-stu-id="f69c2-122">Microsoft Office Pro Plus (which includes Microsoft Outlook) is included in some Office 365 plans and can be purchased as a separate subscription.</span></span> <span data-ttu-id="f69c2-123">如果您使用 POP 連線至 Exchange Online 的電子郵件帳戶，您會看到下列限制： > 沒有行事曆資訊 > 沒有空閒/忙碌資訊 > 否全域通訊清單 > 沒有發送電子郵件 > 透過 POP 連接時，所有的郵件將是 downlo用戶端和有將 aded 是沒有多部電腦或裝置 （例如筆電膝上型電腦和手機） 之間的同步處理。</span><span class="sxs-lookup"><span data-stu-id="f69c2-123">You will see the following limitations if you use POP to connect to an Exchange Online email account: >  No calendar information >  No free/busy information >  No Global Address List >  No push email >  When connecting through POP, all messages will be downloaded to the client and there will be no synchronization between multiple computers or devices (such as between a laptop and a phone).</span></span> 
  
## <a name="outlook-on-the-web"></a><span data-ttu-id="f69c2-124">Outlook 網頁版</span><span class="sxs-lookup"><span data-stu-id="f69c2-124">Outlook on the web</span></span>

<span data-ttu-id="f69c2-p106">Outlook 網頁版是網路架構版本的 Outlook 電子郵件程式，搭配 Exchange Online 使用。它能讓使用者透過網路瀏覽器接存取電子郵件、行事曆，以及聯絡人，不無論他們在哪裡連接網際網路。如需有關支援瀏覽器的詳細資訊，請參閱[商務用 Outlook 網頁版支援的瀏覽器](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006)。</span><span class="sxs-lookup"><span data-stu-id="f69c2-p106">Outlook on the web is a web-based version of the Outlook email program that is used with Exchange Online. It enables users to access their email, calendar, and contacts through a web browser from wherever they connect to the Internet. For information about supported browsers, see [Supported browsers for Outlook on the web for business](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006).</span></span>
  
<span data-ttu-id="f69c2-128">Outlook 網頁版有兩種用戶端版本，皆可搭配 Exchange Online 使用：</span><span class="sxs-lookup"><span data-stu-id="f69c2-128">Outlook on the web comes in two client versions, both of which can be used with Exchange Online:</span></span>
  
- <span data-ttu-id="f69c2-p107">**Outlook 網頁版** Outlook 網頁版標準版本提供 Exchange Online 使用者和 Outlook 使用者如出一轍的郵件傳送體驗。它支援最新的網路瀏覽器，無論使用平板電腦、智慧型手機、桌上型電腦和筆電，都提供高效能運用。使用者可以讀取和傳送郵件、組織連絡人，以及排定約會與會議。預設的以活動為基礎的逾時是設定為 6 小時，但是可以 [由系統管理員在 Windows PowerShell 中設定](https://go.microsoft.com/fwlink/p/?LinkId=399155)，從 5 分鐘到 8 小時不等。這個逾時取決於 Web 應用程式內的使用者互動，例如按一下按鈕或選取某個郵件。另外也有由安全性驅動的個別逾時，這個逾時無法設定且不論使用者活動如何都會發生。如果使用者已經登入長達 8 小時，OWA 將會自動把使用者登出並要求重新驗證。</span><span class="sxs-lookup"><span data-stu-id="f69c2-p107">**Outlook on the web** The standard version of Outlook on the web provides Exchange Online users with a messaging experience most similar to that of Outlook users. It supports most newer web browsers and is optimized for use on tablets and smartphones as well as desktops and laptops. Users can read and send messages, organize contacts, and schedule appointments and meetings. The default activity-based time-out is set at six hours, but it can be [configured by an administrator in Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) from 5 minutes to 8 hours. This time-out depends on user interactions within the web app, such as clicking a button or selecting a message. There is also a separate security-driven time-out, which is not configurable and will occur regardless of user activity. If a user is logged in for 8 hours, OWA will automatically log the user out and ask for re-authentication.</span></span> 
    
- <span data-ttu-id="f69c2-p108">**Outlook 網頁精簡版** Outlook 網頁精簡版可讓使用者透過任一種網路瀏覽器存取信箱。使用者可以讀取和傳送郵件、組織連絡人，以及排定約會與會議。預設的以活動為基礎的逾時是設定為 6 小時，但是可以 [由系統管理員在 Windows PowerShell 中設定](https://go.microsoft.com/fwlink/p/?LinkId=399155)，從 5 分鐘到 8 小時不等。這個逾時取決於 Web 應用程式內的使用者互動，例如按一下按鈕或選取某個郵件。另外也有由安全性驅動的個別逾時，這個逾時無法設定且不論使用者活動如何都會發生。如果使用者已經登入長達 8 小時，精簡版的 OWA 將會自動把使用者登出並要求重新驗證。</span><span class="sxs-lookup"><span data-stu-id="f69c2-p108">**The light version of Outlook on the web** The light version of Outlook on the web provides Exchange Online users access to the mailbox using almost any web browser. Users can read and send messages, organize contacts, and schedule appointments and meetings. The default activity-based time-out is set at six hours, but it can be [configured by an administrator in Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) from 5 minutes to 8 hours. This time-out depends on user interactions within the web app, such as clicking a button or selecting a message. There is also a separate security-driven time-out, which is not configurable and will occur regardless of user activity. If a user is logged in for 8 hours, the light version of OWA will automatically log the user out and ask for re-authentication.</span></span> 
    
<span data-ttu-id="f69c2-p109">Outlook 網頁版也有行動版本。如需詳細資訊，請參閱[此頁面](http://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409)。</span><span class="sxs-lookup"><span data-stu-id="f69c2-p109">Outlook on the web also is available in mobile versions. For more information, see [this page](http://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409).</span></span>
  
## <a name="outlook-for-mac"></a><span data-ttu-id="f69c2-144">Mac 版 Outlook</span><span class="sxs-lookup"><span data-stu-id="f69c2-144">Outlook for Mac</span></span>

<span data-ttu-id="f69c2-145">Exchange Online 支援 Microsoft Outlook for Mac，提供電子郵件、 行事曆、 地址簿、 工作清單，以及備註清單。</span><span class="sxs-lookup"><span data-stu-id="f69c2-145">Exchange Online supports Microsoft Outlook for Mac, which provides email, calendar, an address book, a task list, and a note list.</span></span>
  
## <a name="outlook-for-ios-android-and-windows-phone"></a><span data-ttu-id="f69c2-146">Outlook for iOS、 Android 和 Windows Phone</span><span class="sxs-lookup"><span data-stu-id="f69c2-146">Outlook for iOS, Android, and Windows Phone</span></span>

<span data-ttu-id="f69c2-147">Outlook 相關應用程式適用於 iOS、 Android 和 Windows Phone 與 Exchange Online 運作。</span><span class="sxs-lookup"><span data-stu-id="f69c2-147">Exchange Online works with Outlook apps available for iOS, Android, and Windows Phone.</span></span> <span data-ttu-id="f69c2-148">在任何這些裝置，使用應用程式市集，尋找 Outlook 應用程式。</span><span class="sxs-lookup"><span data-stu-id="f69c2-148">On any of these devices, use the app store to find the Outlook app.</span></span> <span data-ttu-id="f69c2-149">以下是行動裝置 OS 明細。</span><span class="sxs-lookup"><span data-stu-id="f69c2-149">Here's a breakdown by mobile OS.</span></span>
  
|||||
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="f69c2-150">裝置</span><span class="sxs-lookup"><span data-stu-id="f69c2-150">Device</span></span>  <br/> |<span data-ttu-id="f69c2-151">Android</span><span class="sxs-lookup"><span data-stu-id="f69c2-151">Android</span></span>  <br/> |<span data-ttu-id="f69c2-152">iOS</span><span class="sxs-lookup"><span data-stu-id="f69c2-152">iOS</span></span>  <br/> |<span data-ttu-id="f69c2-153">Windows Phone</span><span class="sxs-lookup"><span data-stu-id="f69c2-153">Windows Phone</span></span>  <br/> |
|<span data-ttu-id="f69c2-154">Outlook 行動應用程式可用性</span><span class="sxs-lookup"><span data-stu-id="f69c2-154">Outlook mobile app availability</span></span>  <br/> |<span data-ttu-id="f69c2-155">是</span><span class="sxs-lookup"><span data-stu-id="f69c2-155">Yes</span></span>  <br/> [<span data-ttu-id="f69c2-156">取得 Android 版 Outlook</span><span class="sxs-lookup"><span data-stu-id="f69c2-156">Get Outlook for Android</span></span>](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |<span data-ttu-id="f69c2-157">是</span><span class="sxs-lookup"><span data-stu-id="f69c2-157">Yes</span></span>  <br/> [<span data-ttu-id="f69c2-158">取得適用於 iOS 的 Outlook</span><span class="sxs-lookup"><span data-stu-id="f69c2-158">Get Outlook for iOS</span></span>](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |<span data-ttu-id="f69c2-159">內建</span><span class="sxs-lookup"><span data-stu-id="f69c2-159">Built-in</span></span>  <br/> |
|<span data-ttu-id="f69c2-160">與 Exchange Online 相容的內建的電子郵件應用程式</span><span class="sxs-lookup"><span data-stu-id="f69c2-160">Built-in email apps compatible with Exchange Online</span></span>  <br/> |<span data-ttu-id="f69c2-161">Gmail 應用程式/Samsung 電子郵件應用程式</span><span class="sxs-lookup"><span data-stu-id="f69c2-161">Gmail app/Samsung Email app</span></span>  <br/> |<span data-ttu-id="f69c2-162">ios 電子郵件應用程式</span><span class="sxs-lookup"><span data-stu-id="f69c2-162">iOS Mail app</span></span>  <br/> |<span data-ttu-id="f69c2-163">Outlook 郵件、 行事曆、 連絡人</span><span class="sxs-lookup"><span data-stu-id="f69c2-163">Outlook Mail, calendar, contacts</span></span>  <br/> |
|<span data-ttu-id="f69c2-164">詳細資訊</span><span class="sxs-lookup"><span data-stu-id="f69c2-164">More information</span></span>  <br/> |[<span data-ttu-id="f69c2-165">Android 的行動裝置設定</span><span class="sxs-lookup"><span data-stu-id="f69c2-165">Android mobile setup</span></span>](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[<span data-ttu-id="f69c2-166">iPhone 或 iPad 的安裝程式</span><span class="sxs-lookup"><span data-stu-id="f69c2-166">iPhone or iPad setup</span></span>](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[<span data-ttu-id="f69c2-167">Windows Phone 安裝程式</span><span class="sxs-lookup"><span data-stu-id="f69c2-167">Windows Phone setup</span></span>](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |
   
<span data-ttu-id="f69c2-168">也有使用裝置，包括 Blackberry 使用 Exchange Online 的選項。</span><span class="sxs-lookup"><span data-stu-id="f69c2-168">There are also options for using Exchange Online with devices, including Blackberry.</span></span>
  
### <a name="feature-availability"></a><span data-ttu-id="f69c2-169">功能可用性</span><span class="sxs-lookup"><span data-stu-id="f69c2-169">Feature availability</span></span>

<span data-ttu-id="f69c2-170">Outlook 會讓使用者快速且容易了解電子郵件和行事曆體驗，預期現代行動應用程式，從時所提供的 Office 365 的最佳功能支援僅應用程式。</span><span class="sxs-lookup"><span data-stu-id="f69c2-170">Outlook gives users the fast, intuitive email and calendar experience that they expect from a modern mobile app, while being the only app to provide support for the best features of Office 365.</span></span> <span data-ttu-id="f69c2-171">它是特別設計用來支援完整的 Office 365 體驗，請授與使用者的一致的體驗從桌面行動唯一的電子郵件應用程式。</span><span class="sxs-lookup"><span data-stu-id="f69c2-171">It is the only email app specifically designed to support the full Office 365 experience, giving users a coherent experience from desktop to mobile.</span></span> <span data-ttu-id="f69c2-172">Outlook 整合 Intune、 企業行動力與安全性和 Exchange 控制以保護資料和使用者的安全。</span><span class="sxs-lookup"><span data-stu-id="f69c2-172">Outlook is integrated with Intune, enterprise mobility and security, and Exchange controls to keep data and users safe.</span></span>
  
<span data-ttu-id="f69c2-173">Outlook 可讓使用者：</span><span class="sxs-lookup"><span data-stu-id="f69c2-173">Outlook enables users to:</span></span>
  
- <span data-ttu-id="f69c2-174">從行動裝置管理其整個天。</span><span class="sxs-lookup"><span data-stu-id="f69c2-174">Manage their entire day from a mobile device.</span></span>
    
- <span data-ttu-id="f69c2-175">連線到應用程式，也須能生產力，同時保持其工作和個人資訊分開及安全的服務。</span><span class="sxs-lookup"><span data-stu-id="f69c2-175">Connect to the apps and services they need to be productive, while keeping their work and personal information separate and secure.</span></span>
    
<span data-ttu-id="f69c2-176">Outlook for iOS、 Android 版 Outlook 或 Outlook for Windows Phone 中，使用者可以進行下列作業：</span><span class="sxs-lookup"><span data-stu-id="f69c2-176">With Outlook for iOS, Outlook for Android, or Outlook for Windows Phone, users can:</span></span> 
  
- <span data-ttu-id="f69c2-177">享有焦點收件匣的優先順序重要的電子郵件</span><span class="sxs-lookup"><span data-stu-id="f69c2-177">Benefit from a focused inbox that priorities important email</span></span>
    
- <span data-ttu-id="f69c2-178">自訂以符合其唯一的電子郵件習慣往撥動手勢</span><span class="sxs-lookup"><span data-stu-id="f69c2-178">Customize swipe gestures to match their unique email habits</span></span>
    
- <span data-ttu-id="f69c2-179">建立可直接加入在行事曆，以提供一眼的重要資訊的旅遊行程</span><span class="sxs-lookup"><span data-stu-id="f69c2-179">Create travel itineraries that can be added directly to the calendar, with key information available at a glance</span></span>
    
- <span data-ttu-id="f69c2-180">從收件匣 RSVP 加入會議。</span><span class="sxs-lookup"><span data-stu-id="f69c2-180">RSVP to meetings from the inbox.</span></span>
    
- <span data-ttu-id="f69c2-181">電子郵件中使用直覺式的圖示，並協助他們的行事曆約會快速處理資訊</span><span class="sxs-lookup"><span data-stu-id="f69c2-181">Use intuitive icons in email and calendar appointments that help them process information quickly</span></span>
    
- <span data-ttu-id="f69c2-182">所有裝置上使用一致且熟悉的 Outlook 經驗</span><span class="sxs-lookup"><span data-stu-id="f69c2-182">Use a consistent and familiar Outlook experience across all devices</span></span>
    
- <span data-ttu-id="f69c2-183">輕鬆地啟動並加入從行事曆的 Skype 會議</span><span class="sxs-lookup"><span data-stu-id="f69c2-183">Easily launch and join Skype meetings from the calendar</span></span>
    
- <span data-ttu-id="f69c2-184">讀取和回應 IRM 加密和保護電子郵件</span><span class="sxs-lookup"><span data-stu-id="f69c2-184">Read and respond to IRM encrypted and protected emails</span></span>
    
- <span data-ttu-id="f69c2-185">儲存在商務用 OneDrive 中共用檔案</span><span class="sxs-lookup"><span data-stu-id="f69c2-185">Share files stored in OneDrive for Business</span></span>
    
- <span data-ttu-id="f69c2-186">點選 [設定自動回覆</span><span class="sxs-lookup"><span data-stu-id="f69c2-186">Set Automatic Replies with a tap</span></span>
    
- <span data-ttu-id="f69c2-187">檢視及管理共用與委派的行事曆</span><span class="sxs-lookup"><span data-stu-id="f69c2-187">View and manage shared and delegated calendars</span></span>
    
- <span data-ttu-id="f69c2-188">搜尋與一些點選其公司的全域通訊清單</span><span class="sxs-lookup"><span data-stu-id="f69c2-188">Search their company's global address list with a few taps</span></span>
    
- <span data-ttu-id="f69c2-189">檢視同事的可用性和排程適用於所有人的會議時間</span><span class="sxs-lookup"><span data-stu-id="f69c2-189">View coworker's availability and schedule a meeting time that works for everyone</span></span>
    
- <span data-ttu-id="f69c2-190">請參閱受邀者接受、 暫訂，並拒絕狀態</span><span class="sxs-lookup"><span data-stu-id="f69c2-190">See invitees accept, tentative, and decline status</span></span>
    
- <span data-ttu-id="f69c2-191">共用權限從其電話的行事曆</span><span class="sxs-lookup"><span data-stu-id="f69c2-191">Share calendars right from their phones</span></span>
    
- <span data-ttu-id="f69c2-192">啟動並加入 Skype 會議右，從行事曆</span><span class="sxs-lookup"><span data-stu-id="f69c2-192">Start and join Skype meetings right from a calendar</span></span>
    
- <span data-ttu-id="f69c2-193">存取公司與個人的行事曆在一個位置，而不切換應用程式</span><span class="sxs-lookup"><span data-stu-id="f69c2-193">Access work and personal calendars in one place, without switching apps</span></span>
    
## <a name="exchange-activesync"></a><span data-ttu-id="f69c2-194">Exchange ActiveSync</span><span class="sxs-lookup"><span data-stu-id="f69c2-194">Exchange ActiveSync</span></span>

<span data-ttu-id="f69c2-195">Exchange Online 支援 Microsoft Exchange ActiveSync 協定，將行動裝置與 Exchange Online 之間的信箱資料同步處理，使用者便能隨時隨地存取電子郵件、行事曆、聯絡人和工作。</span><span class="sxs-lookup"><span data-stu-id="f69c2-195">Exchange Online supports the Microsoft Exchange ActiveSync protocol, which synchronizes mailbox data between mobile devices and Exchange Online, so users can access their email, calendar, contacts, and tasks on the go.</span></span>
  
<span data-ttu-id="f69c2-196">Exchange ActiveSync 可與各種行動裝置相容，包括 Microsoft Windows Phone、Apple iPhone 和 iPad，以及 Android 手機和平板電腦。</span><span class="sxs-lookup"><span data-stu-id="f69c2-196">A wide range of mobile devices work with Exchange ActiveSync, including Microsoft Windows Phone, Apple iPhone and iPad, and Android phones and tablets.</span></span> <span data-ttu-id="f69c2-197">除了手機和裝置，Windows Phone 的郵件應用程式連線到 Exchange Online 使用 Exchange ActiveSync。</span><span class="sxs-lookup"><span data-stu-id="f69c2-197">In addition to mobile phones and devices, the Mail application in Windows Phone uses Exchange ActiveSync to connect to Exchange Online.</span></span> <span data-ttu-id="f69c2-198">目前 Exchange ActiveSync 授權條款的完整清單可在 Exchange ActiveSync Licensing 網站查閱。</span><span class="sxs-lookup"><span data-stu-id="f69c2-198">A complete list of current Exchange ActiveSync licensees is available at the Exchange ActiveSync Licensing site.</span></span>
  
<span data-ttu-id="f69c2-199">如需 Exchange ActiveSync 的詳細資訊，請參閱[Exchange ActiveSync](https://go.microsoft.com/fwlink/p/?LinkId=271792)。</span><span class="sxs-lookup"><span data-stu-id="f69c2-199">For more information about Exchange ActiveSync, see [Exchange ActiveSync](https://go.microsoft.com/fwlink/p/?LinkId=271792).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="f69c2-200">每個信箱的 Exchange ActiveSync 裝置數目上限是 100。</span><span class="sxs-lookup"><span data-stu-id="f69c2-200">The maximum number of Exchange ActiveSync devices per mailbox is 100.</span></span> 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a><span data-ttu-id="f69c2-201">以 Exchange Web Services（EWS）研發的應用程式</span><span class="sxs-lookup"><span data-stu-id="f69c2-201">Applications developed with Exchange Web Services (EWS)</span></span>

 <span data-ttu-id="f69c2-202">以 Exchange Web Services (EWS) 或 EWS Managed API 開發的應用程式，可讓管理員從執行於內部部署、Azure 或其他託管服務中的應用程式，存取儲存在 Exchange Online 那邊的資料。</span><span class="sxs-lookup"><span data-stu-id="f69c2-202">Applications developed using Exchange Web Services (EWS) or the EWS Managed API let administrators access data stored with Exchange Online from applications that are running on-premises, in Azure, or in other hosted services.</span></span> 
  
<span data-ttu-id="f69c2-203">如需以 Exchange Web 服務開發之應用程式的詳細資訊，請參閱 [Exchange 中的 Web 服務](https://go.microsoft.com/fwlink/?LinkId=325346)。</span><span class="sxs-lookup"><span data-stu-id="f69c2-203">For more information on applications developed with Exchange Web Services, see [Web Services in Exchange](https://go.microsoft.com/fwlink/?LinkId=325346).</span></span>
  
## <a name="pop-and-imap"></a><span data-ttu-id="f69c2-204">POP 與 IMAP</span><span class="sxs-lookup"><span data-stu-id="f69c2-204">POP and IMAP</span></span>

<span data-ttu-id="f69c2-p113">Exchange Online 支援透過 POP3 和 IMAP4 協定的信箱存取。POP 和 IMAP 存取要求使用 SSL 加密。預設情況下，為所有使用者啟用 POP。使用者能在 Outlook 網頁版中檢視他們的 POP 和 IMAP 連線設定。管理員可以對個別使用者分別禁用 POP 和 IMAP 存取。</span><span class="sxs-lookup"><span data-stu-id="f69c2-p113">Exchange Online supports mailbox access through both POP3 and IMAP4 protocols. POP and IMAP access requires encryption using SSL. POP is enabled by default for all users. Users can view their POP and IMAP connection settings in Outlook on the web. Administrators can disable POP and IMAP access on a per-user basis.</span></span>
  
<span data-ttu-id="f69c2-210">如需 POP3 和 IMAP4 連線的相關資訊，請參閱 [POP3 和 IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070)。</span><span class="sxs-lookup"><span data-stu-id="f69c2-210">For more information about POP3 and IMAP4 connectivity, see [POP3 and IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070).</span></span>
  
## <a name="smtp"></a><span data-ttu-id="f69c2-211">SMTP</span><span class="sxs-lookup"><span data-stu-id="f69c2-211">SMTP</span></span>

<span data-ttu-id="f69c2-p114">簡易郵件傳輸通訊協定（SMTP）是用來發送外寄郵件給透過 IMAP 或 POP 連線至 Exchange Online 的客戶端。它是路由和通過 Exchange 伺服器傳遞的主協定。Exchange Online 為需要 SMTP 郵件提交的授權內部客戶應用程式提供兩種型態的 SMTP 轉送服務：</span><span class="sxs-lookup"><span data-stu-id="f69c2-p114">Simple Mail Transfer Protocol (SMTP) is used to send outbound mail for clients that connect to Exchange Online through IMAP or POP. It is the primary protocol for routing and delivery through Exchange Server. Exchange Online supports two types of SMTP relay services for authorized internal customer applications that require SMTP mail submission:</span></span>
  
- <span data-ttu-id="f69c2-215">SMTP 郵件提交給託管環境內的使用者。</span><span class="sxs-lookup"><span data-stu-id="f69c2-215">SMTP message submission to users inside the managed environment.</span></span>
    
- <span data-ttu-id="f69c2-216">已通過驗證的 SMTP 郵件將轉送到託管環境的外部地址。</span><span class="sxs-lookup"><span data-stu-id="f69c2-216">Authenticated SMTP message relay to addresses outside the managed environment.</span></span>
    
> [!IMPORTANT]
> <span data-ttu-id="f69c2-p115">需要授權的來源伺服器 IP 位址以允許 SMTP 轉送。使用 SMTP 寄送郵件時，需要傳輸層安全性（TLS）加密與驗證。</span><span class="sxs-lookup"><span data-stu-id="f69c2-p115">IP addresses for authorized source servers are required to allow SMTP relay. Transport Layer Security (TLS) encryption and authentication is required when using SMTP to send email.</span></span> 
  
## <a name="blackberry-devices"></a><span data-ttu-id="f69c2-219">BlackBerry® 裝置</span><span class="sxs-lookup"><span data-stu-id="f69c2-219">BlackBerry® devices</span></span>

<span data-ttu-id="f69c2-220">透過 Exchange ActiveSync BlackBerry® 裝置上使用 office 365 電子郵件。</span><span class="sxs-lookup"><span data-stu-id="f69c2-220">Office 365 email is available on BlackBerry® devices via Exchange ActiveSync.</span></span> <span data-ttu-id="f69c2-221">若要找出您的選項為何，請參閱下列主題：</span><span class="sxs-lookup"><span data-stu-id="f69c2-221">To find out what your options are, see these topics:</span></span>
  
- [<span data-ttu-id="f69c2-222">BlackBerry 裝置上設定電子郵件</span><span class="sxs-lookup"><span data-stu-id="f69c2-222">Set up email on a BlackBerry device</span></span>](https://go.microsoft.com/fwlink/?linkid=863394)
    
- [<span data-ttu-id="f69c2-223">BlackBerry 裝置 7.1 上設定電子郵件 OS 和更早版本</span><span class="sxs-lookup"><span data-stu-id="f69c2-223">Set up email on a BlackBerry device 7.1 OS and earlier</span></span>](https://go.microsoft.com/fwlink/?linkid=863403)
    
<span data-ttu-id="f69c2-224">如需詳細資訊，請參閱 [BlackBerry](../office-365-platform-service-description/blackberry.md)。</span><span class="sxs-lookup"><span data-stu-id="f69c2-224">For more information, see [BlackBerry](../office-365-platform-service-description/blackberry.md).</span></span>
  
> [!NOTE]
> <span data-ttu-id="f69c2-p117">如果您在中國使用 21Vianet 運作的 Office 365，將無法使用 BlackBerry Business 雲端服務。不過您可以使用 Exchange ActiveSync 裝置或 Research in Motion 的產品 (RIM、BlackBerry 無線電子郵件解決方案) 來執行 BlackBerry 企業伺服器 (BES)。</span><span class="sxs-lookup"><span data-stu-id="f69c2-p117">If you are using Office 365 operated by 21Vianet in China, BlackBerry Business Cloud Services is not available. However, you can use Exchange ActiveSync devices or an offering from Research in Motion (RIM, the BlackBerry wireless email solution) to run Blackberry Enterprise Server (BES).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="f69c2-227">功能可用性</span><span class="sxs-lookup"><span data-stu-id="f69c2-227">Feature Availability</span></span>

<span data-ttu-id="f69c2-228">若要檢視 Office 365 計劃、獨立選項和內部部署解決方案中的功能可用性，請參閱 [Exchange Online 服務說明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="f69c2-228">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

