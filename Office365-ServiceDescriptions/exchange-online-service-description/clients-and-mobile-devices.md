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
# <a name="clients-and-mobile-devices"></a><span data-ttu-id="a9fbe-102">用戶端和行動裝置</span><span class="sxs-lookup"><span data-stu-id="a9fbe-102">Clients and Mobile Devices</span></span>

## <a name="microsoft-outlook"></a><span data-ttu-id="a9fbe-103">Microsoft Outlook</span><span class="sxs-lookup"><span data-stu-id="a9fbe-103">Microsoft Outlook</span></span>

<span data-ttu-id="a9fbe-104">Microsoft Outlook 是包含行事曆、 連絡人、 工作及下列重要功能，包括支援的電子郵件程式：</span><span class="sxs-lookup"><span data-stu-id="a9fbe-104">Microsoft Outlook is an email program that includes support for calendar, contacts, tasks, and the following key features:</span></span>
  
- <span data-ttu-id="a9fbe-p101">**MAPI over HTTP**Over HTTP 通訊應用程式介面 (MAPI) 可讓 Outlook 使用者透過網際網路其組織防火牆外部連線到 Exchange Online 信箱。MAPI over HTTP，Outlook 無所不在 」 的長期取代。此連線方法提供改善的連線恢復能力、 更安全登入、 擴充性，以及增強功能的 IT 和支援。若要深入了解，請參閱[RPC over HTTP 達到的 Office 365 中支援的結束](https://go.microsoft.com/fwlink/?linkid=863890)及[MAPI over HTTP](https://go.microsoft.com/fwlink/?linkid=393041)。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-p101">**MAPI over HTTP** Messaging Application Program Interface (MAPI) over HTTP allows Outlook users to connect to Exchange Online mailboxes over the Internet from outside their organization's firewall. MAPI over HTTP, the long term replacement for Outlook Anywhere. This connectivity method offers improved connection resiliency, more secure sign-in, extensibility, as well as enhancements for IT and support. To learn more, see [RPC over HTTP reaches end of support in Office 365](https://go.microsoft.com/fwlink/?linkid=863890) and [MAPI over HTTP](https://go.microsoft.com/fwlink/?linkid=393041).</span></span>
    
- <span data-ttu-id="a9fbe-p102">**Autodiscover** Autodiscover 服務功能自動設定 Outlook 搭配 Exchange Online 使用。Outlook 使用者首次以電子郵件地址與密碼登入時，能直接由 Exchange Online 接收他們要求的檔案設定。這些設定會以建立並維護使用者設定檔所需的資訊自動更新 Outlook 用戶端。使用 Autodiscover 服務需要 SSL 憑證。此 SSL 憑證僅限於單一的主要 SSL 網域。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-p102">**Autodiscover** The Autodiscover service feature automatically configures Outlook to work with Exchange Online. Outlook users can receive their required profile settings directly from Exchange Online the first time they sign in with their email address and password. These settings automatically update the Outlook client with the information necessary to create and maintain the user's profile. An SSL certificate is required to use the Autodiscover service. This SSL certificate is limited to a single primary SSL domain.</span></span> 
    
- <span data-ttu-id="a9fbe-p103">**快取 Exchange 模式** 快取 Exchange 模式功允許M Outlook 使用者在未連線至網際網路時，能存取 Exchange Online 信箱的本機副本。快取 Exchange 模式保存使用者在 Outlook 的 Exchange 信箱之用戶端副本，並自動將此副本與郵件伺服器進行同步處理。我們建議使用快取 Exchange 模式中的 Outlook，因為它提供離線存取，並協助提供回應使用者經驗，即使用戶端與伺服器之間的網路狀況不理想。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-p103">**Cached Exchange Mode** The Cached Exchange Mode feature allows Outlook users to access local copies of their Exchange Online mailboxes when they are not connected to the Internet. Cached Exchange Mode retains a client-side copy of users' Exchange mailboxes in Outlook and automatically synchronizes this copy with the email server. We recommend using Outlook in Cached Exchange Mode because it provides offline access and helps to provide a responsive user experience even when network conditions between the client and the server are not ideal.</span></span> 
    
<span data-ttu-id="a9fbe-p104">依照預設，Outlook 存取對所有使用者開放啟用狀態。管理員可以透過 Windows PowerShell，禁止特定的使用者或群組存取。我們建議使用最新版本的 Outlook--安裝最新版的 service pack--來存取 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-p104">By default, Outlook access is enabled for all users. Administrators can disable access for specific users or groups through Windows PowerShell. We recommend using the latest version of Outlook—with the latest service pack installed—to access Exchange Online.</span></span> 
  
<span data-ttu-id="a9fbe-120">如需哪些 Outlook 用戶端受到 Exchange 2016 和 Exchange Online 支援的詳細資訊，請參閱 [Exchange 2016 系統需求](https://go.microsoft.com/fwlink/?LinkID=828972)中的＜支援的用戶端＞。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-120">For information about which Outlook clients are supported by Exchange 2016 and Exchange Online, see "Supported clients" in [Exchange 2016 system requirements](https://go.microsoft.com/fwlink/?LinkID=828972).</span></span>
  
> [!IMPORTANT]
>  <span data-ttu-id="a9fbe-p105">Outlook 不包含在 Exchange Online 的訂閱價格之內。Microsoft Office Pro Plus（包括 Microsoft Outlook）包含在某些 Office 365 計畫內，並且能以單獨訂閱的方式購買。 >  如果您使用 POP 與 Exchange Online 電子郵件帳戶連線，您會看到下列限制︰ >  沒有行事曆資訊 >  沒有空閒/忙碌資訊 >  沒有全球通訊清單 >  沒有行動郵件 >  透過 POP 連接時，所有郵件都會被下載到用戶端，不會在多部電腦或裝置之間（例如筆電和手機）進行同步處理。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-p105">Outlook is not provided as part of the Exchange Online subscription price. Microsoft Office Pro Plus (which includes Microsoft Outlook) is included in some Office 365 plans and can be purchased as a separate subscription. >  You will see the following limitations if you use POP to connect to an Exchange Online email account: >  No calendar information >  No free/busy information >  No Global Address List >  No push email >  When connecting through POP, all messages will be downloaded to the client and there will be no synchronization between multiple computers or devices (such as between a laptop and a phone).</span></span> 
  
## <a name="outlook-on-the-web"></a><span data-ttu-id="a9fbe-124">網頁型 Outlook</span><span class="sxs-lookup"><span data-stu-id="a9fbe-124">Outlook on the web</span></span>

<span data-ttu-id="a9fbe-p106">Outlook 網頁版是網路架構版本的 Outlook 電子郵件程式，搭配 Exchange Online 使用。它能讓使用者透過網路瀏覽器接存取電子郵件、行事曆，以及聯絡人，不無論他們在哪裡連接網際網路。如需有關支援瀏覽器的詳細資訊，請參閱[商務用 Outlook 網頁版支援的瀏覽器](https://go.microsoft.com/fwlink/p/?LinkId=287032)。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-p106">Outlook on the web is a web-based version of the Outlook email program that is used with Exchange Online. It enables users to access their email, calendar, and contacts through a web browser from wherever they connect to the Internet. For information about supported browsers, see [Supported browsers for Outlook on the web for business](https://go.microsoft.com/fwlink/p/?LinkId=287032).</span></span>
  
<span data-ttu-id="a9fbe-128">Outlook 網頁版有兩種用戶端版本，皆可搭配 Exchange Online 使用：</span><span class="sxs-lookup"><span data-stu-id="a9fbe-128">Outlook on the web comes in two client versions, both of which can be used with Exchange Online:</span></span>
  
- <span data-ttu-id="a9fbe-p107">**Outlook 網頁版** Outlook 網頁版標準版本提供 Exchange Online 使用者和 Outlook 使用者如出一轍的郵件傳送體驗。它支援最新的網路瀏覽器，無論使用平板電腦、智慧型手機、桌上型電腦和筆電，都提供高效能運用。使用者可以讀取和傳送郵件、組織連絡人，以及排定約會與會議。預設的以活動為基礎的逾時是設定為 6 小時，但是可以 [由系統管理員在 Windows PowerShell 中設定](https://go.microsoft.com/fwlink/p/?LinkId=399155)，從 5 分鐘到 8 小時不等。這個逾時取決於 Web 應用程式內的使用者互動，例如按一下按鈕或選取某個郵件。另外也有由安全性驅動的個別逾時，這個逾時無法設定且不論使用者活動如何都會發生。如果使用者已經登入長達 8 小時，OWA 將會自動把使用者登出並要求重新驗證。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-p107">**Outlook on the web** The standard version of Outlook on the web provides Exchange Online users with a messaging experience most similar to that of Outlook users. It supports most newer web browsers and is optimized for use on tablets and smartphones as well as desktops and laptops. Users can read and send messages, organize contacts, and schedule appointments and meetings. The default activity-based time-out is set at six hours, but it can be [configured by an administrator in Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) from 5 minutes to 8 hours. This time-out depends on user interactions within the web app, such as clicking a button or selecting a message. There is also a separate security-driven time-out, which is not configurable and will occur regardless of user activity. If a user is logged in for 8 hours, OWA will automatically log the user out and ask for re-authentication.</span></span> 
    
- <span data-ttu-id="a9fbe-p108">**Outlook 網頁精簡版** Outlook 網頁精簡版可讓使用者透過任一種網路瀏覽器存取信箱。使用者可以讀取和傳送郵件、組織連絡人，以及排定約會與會議。預設的以活動為基礎的逾時是設定為 6 小時，但是可以 [由系統管理員在 Windows PowerShell 中設定](https://go.microsoft.com/fwlink/p/?LinkId=399155)，從 5 分鐘到 8 小時不等。這個逾時取決於 Web 應用程式內的使用者互動，例如按一下按鈕或選取某個郵件。另外也有由安全性驅動的個別逾時，這個逾時無法設定且不論使用者活動如何都會發生。如果使用者已經登入長達 8 小時，精簡版的 OWA 將會自動把使用者登出並要求重新驗證。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-p108">**The light version of Outlook on the web** The light version of Outlook on the web provides Exchange Online users access to the mailbox using almost any web browser. Users can read and send messages, organize contacts, and schedule appointments and meetings. The default activity-based time-out is set at six hours, but it can be [configured by an administrator in Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) from 5 minutes to 8 hours. This time-out depends on user interactions within the web app, such as clicking a button or selecting a message. There is also a separate security-driven time-out, which is not configurable and will occur regardless of user activity. If a user is logged in for 8 hours, the light version of OWA will automatically log the user out and ask for re-authentication.</span></span> 
    
<span data-ttu-id="a9fbe-p109">Outlook 網頁版也有行動版本。如需詳細資訊，請參閱[此頁面](http://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409)。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-p109">Outlook on the web also is available in mobile versions. For more information, see [this page](http://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409).</span></span>
  
## <a name="outlook-for-mac"></a><span data-ttu-id="a9fbe-144">Mac 版 Outlook</span><span class="sxs-lookup"><span data-stu-id="a9fbe-144">Outlook for Mac</span></span>

<span data-ttu-id="a9fbe-145">Exchange Online 支援 Microsoft Outlook for Mac，提供電子郵件、 行事曆、 地址簿、 工作清單和備註清單。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-145">Exchange Online supports Microsoft Outlook for Mac, which provides email, calendar, an address book, a task list, and a note list.</span></span>
  
## <a name="outlook-for-ios-android-and-windows-phone"></a><span data-ttu-id="a9fbe-146">IOS、 Android、 及 Windows Phone 的 outlook</span><span class="sxs-lookup"><span data-stu-id="a9fbe-146">Outlook for iOS, Android, and Windows Phone</span></span>

<span data-ttu-id="a9fbe-p110">Outlook 相關應用程式適用於 iOS、 Android、 及 Windows Phone 與 Exchange Online 運作。在任何這些裝置上使用的應用程式存放區來尋找 Outlook 應用程式。以下是分解行動 os。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-p110">Exchange Online works with Outlook apps available for iOS, Android, and Windows Phone. On any of these devices, use the app store to find the Outlook app. Here's a breakdown by mobile OS.</span></span>
  
|||||
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="a9fbe-150">裝置</span><span class="sxs-lookup"><span data-stu-id="a9fbe-150">Device</span></span>  <br/> |<span data-ttu-id="a9fbe-151">Android</span><span class="sxs-lookup"><span data-stu-id="a9fbe-151">Android</span></span>  <br/> |<span data-ttu-id="a9fbe-152">iOS</span><span class="sxs-lookup"><span data-stu-id="a9fbe-152">iOS</span></span>  <br/> |<span data-ttu-id="a9fbe-153">Windows Phone</span><span class="sxs-lookup"><span data-stu-id="a9fbe-153">Windows Phone</span></span>  <br/> |
|<span data-ttu-id="a9fbe-154">Outlook 行動裝置應用程式可用性</span><span class="sxs-lookup"><span data-stu-id="a9fbe-154">Outlook mobile app availability</span></span>  <br/> |<span data-ttu-id="a9fbe-155">是</span><span class="sxs-lookup"><span data-stu-id="a9fbe-155">Yes</span></span>  <br/> [<span data-ttu-id="a9fbe-156">取得 Outlook for android （英文)</span><span class="sxs-lookup"><span data-stu-id="a9fbe-156">Get Outlook for Android</span></span>](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |<span data-ttu-id="a9fbe-157">是</span><span class="sxs-lookup"><span data-stu-id="a9fbe-157">Yes</span></span>  <br/> [<span data-ttu-id="a9fbe-158">取得 iOS 的 Outlook</span><span class="sxs-lookup"><span data-stu-id="a9fbe-158">Get Outlook for iOS</span></span>](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |<span data-ttu-id="a9fbe-159">內建</span><span class="sxs-lookup"><span data-stu-id="a9fbe-159">Built-in</span></span>  <br/> |
|<span data-ttu-id="a9fbe-160">與 Exchange Online 相容的內建的電子郵件應用程式</span><span class="sxs-lookup"><span data-stu-id="a9fbe-160">Built-in email apps compatible with Exchange Online</span></span>  <br/> |<span data-ttu-id="a9fbe-161">Gmail 應用程式/Samsung 電子郵件應用程式</span><span class="sxs-lookup"><span data-stu-id="a9fbe-161">Gmail app/Samsung Email app</span></span>  <br/> |<span data-ttu-id="a9fbe-162">iOS 郵件應用程式</span><span class="sxs-lookup"><span data-stu-id="a9fbe-162">iOS Mail app</span></span>  <br/> |<span data-ttu-id="a9fbe-163">Outlook 郵件、 行事曆、 連絡人</span><span class="sxs-lookup"><span data-stu-id="a9fbe-163">Outlook Mail, calendar, contacts</span></span>  <br/> |
|<span data-ttu-id="a9fbe-164">詳細資訊</span><span class="sxs-lookup"><span data-stu-id="a9fbe-164">More information</span></span>  <br/> |[<span data-ttu-id="a9fbe-165">Android 行動裝置的安裝程式</span><span class="sxs-lookup"><span data-stu-id="a9fbe-165">Android mobile setup</span></span>](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[<span data-ttu-id="a9fbe-166">iPhone 或 iPad 的安裝程式</span><span class="sxs-lookup"><span data-stu-id="a9fbe-166">iPhone or iPad setup</span></span>](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[<span data-ttu-id="a9fbe-167">Windows Phone 安裝程式</span><span class="sxs-lookup"><span data-stu-id="a9fbe-167">Windows Phone setup</span></span>](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |
   
<span data-ttu-id="a9fbe-168">也有包括 Blackberry 裝置搭配使用 Exchange Online 的選項。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-168">There are also options for using Exchange Online with devices, including Blackberry.</span></span>
  
### <a name="feature-availability"></a><span data-ttu-id="a9fbe-169">功能可用性</span><span class="sxs-lookup"><span data-stu-id="a9fbe-169">Feature availability</span></span>

<span data-ttu-id="a9fbe-p111">Outlook 會讓使用者快速且直覺式電子郵件和行事曆的體驗他們預期從現代的行動裝置應用程式時所提供支援的 Office 365 的最佳功能僅應用程式。它是特別設計來支援完整的 Office 365 體驗，讓使用者有一致的體驗從桌面至行動裝置的唯一電子郵件應用程式。Outlook 整合 Intune、 企業行動性及安全性和保護資料和使用者的安全 Exchange 控制項。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-p111">Outlook gives users the fast, intuitive email and calendar experience that they expect from a modern mobile app, while being the only app to provide support for the best features of Office 365. It is the only email app specifically designed to support the full Office 365 experience, giving users a coherent experience from desktop to mobile. Outlook is integrated with Intune, enterprise mobility and security, and Exchange controls to keep data and users safe.</span></span>
  
<span data-ttu-id="a9fbe-173">Outlook 可讓使用者：</span><span class="sxs-lookup"><span data-stu-id="a9fbe-173">Outlook enables users to:</span></span>
  
- <span data-ttu-id="a9fbe-174">從行動裝置管理其整個一天。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-174">Manage their entire day from a mobile device.</span></span>
    
- <span data-ttu-id="a9fbe-175">連線到應用程式及服務所需要提高工作效率，同時個別及安全保持其工時和個人資訊。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-175">Connect to the apps and services they need to be productive, while keeping their work and personal information separate and secure.</span></span>
    
<span data-ttu-id="a9fbe-176">IOS for Android、 Outlook 或 Outlook for Windows Phone 的 Outlook 使用者可以進行下列作業：</span><span class="sxs-lookup"><span data-stu-id="a9fbe-176">With Outlook for iOS, Outlook for Android, or Outlook for Windows Phone, users can:</span></span> 
  
- <span data-ttu-id="a9fbe-177">獲益具有焦點的收件匣的優先順序重要電子郵件</span><span class="sxs-lookup"><span data-stu-id="a9fbe-177">Benefit from a focused inbox that priorities important email</span></span>
    
- <span data-ttu-id="a9fbe-178">自訂以符合其唯一的電子郵件習慣往撥動手勢</span><span class="sxs-lookup"><span data-stu-id="a9fbe-178">Customize swipe gestures to match their unique email habits</span></span>
    
- <span data-ttu-id="a9fbe-179">建立可新增到行事曆的重要資訊可用一覽直接的旅遊行程</span><span class="sxs-lookup"><span data-stu-id="a9fbe-179">Create travel itineraries that can be added directly to the calendar, with key information available at a glance</span></span>
    
- <span data-ttu-id="a9fbe-180">從收件匣 RSVP 加入會議。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-180">RSVP to meetings from the inbox.</span></span>
    
- <span data-ttu-id="a9fbe-181">用於協助他們快速處理資訊的電子郵件和行事曆約會直覺式圖示</span><span class="sxs-lookup"><span data-stu-id="a9fbe-181">Use intuitive icons in email and calendar appointments that help them process information quickly</span></span>
    
- <span data-ttu-id="a9fbe-182">所有裝置都使用始終如一且熟悉的 Outlook 經驗</span><span class="sxs-lookup"><span data-stu-id="a9fbe-182">Use a consistent and familiar Outlook experience across all devices</span></span>
    
- <span data-ttu-id="a9fbe-183">輕鬆地啟動並加入 Skype 會議遠行事曆</span><span class="sxs-lookup"><span data-stu-id="a9fbe-183">Easily launch and join Skype meetings from the calendar</span></span>
    
- <span data-ttu-id="a9fbe-184">讀取和回應 IRM 加密及受保護的電子郵件</span><span class="sxs-lookup"><span data-stu-id="a9fbe-184">Read and respond to IRM encrypted and protected emails</span></span>
    
- <span data-ttu-id="a9fbe-185">儲存在 OneDrive for Business 的共用檔案</span><span class="sxs-lookup"><span data-stu-id="a9fbe-185">Share files stored in OneDrive for Business</span></span>
    
- <span data-ttu-id="a9fbe-186">使用點選 [設定自動回覆</span><span class="sxs-lookup"><span data-stu-id="a9fbe-186">Set Automatic Replies with a tap</span></span>
    
- <span data-ttu-id="a9fbe-187">檢視及管理共用和委派的行事曆</span><span class="sxs-lookup"><span data-stu-id="a9fbe-187">View and manage shared and delegated calendars</span></span>
    
- <span data-ttu-id="a9fbe-188">使用幾個的點選搜尋其公司的全域通訊清單</span><span class="sxs-lookup"><span data-stu-id="a9fbe-188">Search their company's global address list with a few taps</span></span>
    
- <span data-ttu-id="a9fbe-189">檢視同事的可用性及排程適用於所有人的會議時間</span><span class="sxs-lookup"><span data-stu-id="a9fbe-189">View coworker's availability and schedule a meeting time that works for everyone</span></span>
    
- <span data-ttu-id="a9fbe-190">請參閱受邀者接受、 訂、 和拒絕狀態</span><span class="sxs-lookup"><span data-stu-id="a9fbe-190">See invitees accept, tentative, and decline status</span></span>
    
- <span data-ttu-id="a9fbe-191">共用行事曆右從其電話</span><span class="sxs-lookup"><span data-stu-id="a9fbe-191">Share calendars right from their phones</span></span>
    
- <span data-ttu-id="a9fbe-192">啟動並加入 Skype 會議右從行事曆</span><span class="sxs-lookup"><span data-stu-id="a9fbe-192">Start and join Skype meetings right from a calendar</span></span>
    
- <span data-ttu-id="a9fbe-193">存取工時和一個位置，而不切換應用程式的個人行事曆</span><span class="sxs-lookup"><span data-stu-id="a9fbe-193">Access work and personal calendars in one place, without switching apps</span></span>
    
## <a name="exchange-activesync"></a><span data-ttu-id="a9fbe-194">Exchange ActiveSync</span><span class="sxs-lookup"><span data-stu-id="a9fbe-194">Exchange ActiveSync</span></span>

<span data-ttu-id="a9fbe-195">Exchange Online 支援 Microsoft Exchange ActiveSync 協定，將行動裝置與 Exchange Online 之間的信箱資料同步處理，使用者便能隨時隨地存取電子郵件、行事曆、聯絡人和工作。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-195">Exchange Online supports the Microsoft Exchange ActiveSync protocol, which synchronizes mailbox data between mobile devices and Exchange Online, so users can access their email, calendar, contacts, and tasks on the go.</span></span>
  
<span data-ttu-id="a9fbe-p112">各種行動裝置使用 Exchange ActiveSync，包括 Microsoft Windows Phone、 Apple iPhone 與 iPad 及 Android 電話與平板電腦。除了行動電話與裝置、 Windows Phone 的郵件應用程式會使用 Exchange ActiveSync 連線到 Exchange Online。目前的 Exchange ActiveSync 使用人均的完整清單位在 Exchange ActiveSync 授權站台。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-p112">A wide range of mobile devices work with Exchange ActiveSync, including Microsoft Windows Phone, Apple iPhone and iPad, and Android phones and tablets. In addition to mobile phones and devices, the Mail application in Windows Phone uses Exchange ActiveSync to connect to Exchange Online. A complete list of current Exchange ActiveSync licensees is available at the Exchange ActiveSync Licensing site.</span></span>
  
<span data-ttu-id="a9fbe-199">如需 Exchange ActiveSync 的詳細資訊，請參閱[Exchange ActiveSync](https://go.microsoft.com/fwlink/p/?LinkId=271792)。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-199">For more information about Exchange ActiveSync, see [Exchange ActiveSync](https://go.microsoft.com/fwlink/p/?LinkId=271792).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="a9fbe-200">每個信箱的 Exchange ActiveSync 裝置數目上限是 100。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-200">The maximum number of Exchange ActiveSync devices per mailbox is 100.</span></span> 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a><span data-ttu-id="a9fbe-201">以 Exchange Web Services（EWS）研發的應用程式</span><span class="sxs-lookup"><span data-stu-id="a9fbe-201">Applications developed with Exchange Web Services (EWS)</span></span>

 <span data-ttu-id="a9fbe-202">以 Exchange Web Services (EWS) 或 EWS Managed API 開發的應用程式，可讓管理員從執行於內部部署、Azure 或其他託管服務中的應用程式，存取儲存在 Exchange Online 那邊的資料。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-202">Applications developed using Exchange Web Services (EWS) or the EWS Managed API let administrators access data stored with Exchange Online from applications that are running on-premises, in Azure, or in other hosted services.</span></span> 
  
<span data-ttu-id="a9fbe-203">如需以 Exchange Web 服務開發之應用程式的詳細資訊，請參閱 [Exchange 中的 Web 服務](https://go.microsoft.com/fwlink/?LinkId=325346)。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-203">For more information on applications developed with Exchange Web Services, see [Web Services in Exchange](https://go.microsoft.com/fwlink/?LinkId=325346).</span></span>
  
## <a name="pop-and-imap"></a><span data-ttu-id="a9fbe-204">POP 與 IMAP</span><span class="sxs-lookup"><span data-stu-id="a9fbe-204">POP and IMAP</span></span>

<span data-ttu-id="a9fbe-p113">Exchange Online 支援透過 POP3 和 IMAP4 協定的信箱存取。POP 和 IMAP 存取要求使用 SSL 加密。預設情況下，為所有使用者啟用 POP。使用者能在 Outlook 網頁版中檢視他們的 POP 和 IMAP 連線設定。管理員可以對個別使用者分別禁用 POP 和 IMAP 存取。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-p113">Exchange Online supports mailbox access through both POP3 and IMAP4 protocols. POP and IMAP access requires encryption using SSL. POP is enabled by default for all users. Users can view their POP and IMAP connection settings in Outlook on the web. Administrators can disable POP and IMAP access on a per-user basis.</span></span>
  
<span data-ttu-id="a9fbe-210">如需 POP3 和 IMAP4 連線的相關資訊，請參閱 [POP3 和 IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070)。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-210">For more information about POP3 and IMAP4 connectivity, see [POP3 and IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070).</span></span>
  
## <a name="smtp"></a><span data-ttu-id="a9fbe-211">SMTP</span><span class="sxs-lookup"><span data-stu-id="a9fbe-211">SMTP</span></span>

<span data-ttu-id="a9fbe-p114">簡易郵件傳輸通訊協定（SMTP）是用來發送外寄郵件給透過 IMAP 或 POP 連線至 Exchange Online 的客戶端。它是路由和通過 Exchange 伺服器傳遞的主協定。Exchange Online 為需要 SMTP 郵件提交的授權內部客戶應用程式提供兩種型態的 SMTP 轉送服務：</span><span class="sxs-lookup"><span data-stu-id="a9fbe-p114">Simple Mail Transfer Protocol (SMTP) is used to send outbound mail for clients that connect to Exchange Online through IMAP or POP. It is the primary protocol for routing and delivery through Exchange Server. Exchange Online supports two types of SMTP relay services for authorized internal customer applications that require SMTP mail submission:</span></span>
  
- <span data-ttu-id="a9fbe-215">SMTP 郵件提交給託管環境內的使用者。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-215">SMTP message submission to users inside the managed environment.</span></span>
    
- <span data-ttu-id="a9fbe-216">已通過驗證的 SMTP 郵件將轉送到託管環境的外部地址。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-216">Authenticated SMTP message relay to addresses outside the managed environment.</span></span>
    
> [!IMPORTANT]
> <span data-ttu-id="a9fbe-p115">需要授權的來源伺服器 IP 位址以允許 SMTP 轉送。使用 SMTP 寄送郵件時，需要傳輸層安全性（TLS）加密與驗證。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-p115">IP addresses for authorized source servers are required to allow SMTP relay. Transport Layer Security (TLS) encryption and authentication is required when using SMTP to send email.</span></span> 
  
## <a name="blackberry-devices"></a><span data-ttu-id="a9fbe-219">BlackBerry® 裝置</span><span class="sxs-lookup"><span data-stu-id="a9fbe-219">BlackBerry® devices</span></span>

<span data-ttu-id="a9fbe-p116">透過 Exchange ActiveSync BlackBerry® 裝置上使用 office 365 電子郵件。若要了解您的選項，請參閱下列主題：</span><span class="sxs-lookup"><span data-stu-id="a9fbe-p116">Office 365 email is available on BlackBerry® devices via Exchange ActiveSync. To find out what your options are, see these topics:</span></span>
  
- [<span data-ttu-id="a9fbe-222">BlackBerry 裝置上設定電子郵件</span><span class="sxs-lookup"><span data-stu-id="a9fbe-222">Set up email on a BlackBerry device</span></span>](https://go.microsoft.com/fwlink/?linkid=863394)
    
- [<span data-ttu-id="a9fbe-223">BlackBerry 裝置 7.1 上設定電子郵件 OS 或更早版本</span><span class="sxs-lookup"><span data-stu-id="a9fbe-223">Set up email on a BlackBerry device 7.1 OS and earlier</span></span>](https://go.microsoft.com/fwlink/?linkid=863403)
    
<span data-ttu-id="a9fbe-224">如需詳細資訊，請參閱 [BlackBerry](../office-365-platform-service-description/blackberry.md)。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-224">For more information, see [BlackBerry](../office-365-platform-service-description/blackberry.md).</span></span>
  
> [!NOTE]
> <span data-ttu-id="a9fbe-p117">如果您在中國使用 21Vianet 運作的 Office 365，將無法使用 BlackBerry Business 雲端服務。不過您可以使用 Exchange ActiveSync 裝置或 Research in Motion 的產品 (RIM、BlackBerry 無線電子郵件解決方案) 來執行 BlackBerry 企業伺服器 (BES)。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-p117">If you are using Office 365 operated by 21Vianet in China, BlackBerry Business Cloud Services is not available. However, you can use Exchange ActiveSync devices or an offering from Research in Motion (RIM, the BlackBerry wireless email solution) to run Blackberry Enterprise Server (BES).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="a9fbe-227">功能可用性</span><span class="sxs-lookup"><span data-stu-id="a9fbe-227">Feature Availability</span></span>

<span data-ttu-id="a9fbe-228">若要檢視 Office 365 計劃、獨立選項和內部部署解決方案中的功能可用性，請參閱 [Exchange Online 服務說明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="a9fbe-228">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

