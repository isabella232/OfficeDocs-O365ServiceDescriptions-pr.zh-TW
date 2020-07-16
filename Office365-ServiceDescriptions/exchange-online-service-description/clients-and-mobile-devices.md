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
# <a name="clients-and-mobile-devices"></a><span data-ttu-id="b2c35-102">用戶端和行動裝置</span><span class="sxs-lookup"><span data-stu-id="b2c35-102">Clients and mobile devices</span></span>

## <a name="microsoft-outlook"></a><span data-ttu-id="b2c35-103">Microsoft Outlook</span><span class="sxs-lookup"><span data-stu-id="b2c35-103">Microsoft Outlook</span></span>

<span data-ttu-id="b2c35-104">Microsoft Outlook 是一項電子郵件程式，其中包含對行事曆、連絡人、工作及下列主要功能的支援：</span><span class="sxs-lookup"><span data-stu-id="b2c35-104">Microsoft Outlook is an email program that includes support for calendar, contacts, tasks, and the following key features:</span></span>
  
- <span data-ttu-id="b2c35-105">**MAPI OVER HTTP**郵件應用程式介面（MAPI） over HTTP 允許 Outlook 使用者從其組織防火牆以外的網際網路連線至 Exchange Online 信箱。</span><span class="sxs-lookup"><span data-stu-id="b2c35-105">**MAPI over HTTP** Messaging Application Program Interface (MAPI) over HTTP allows Outlook users to connect to Exchange Online mailboxes over the internet from outside their organization's firewall.</span></span> <span data-ttu-id="b2c35-106">MAPI over HTTP，長期取代 Outlook Anywhere。</span><span class="sxs-lookup"><span data-stu-id="b2c35-106">MAPI over HTTP, the long term replacement for Outlook Anywhere.</span></span> <span data-ttu-id="b2c35-107">這種連線方式可提供更好的連線恢復功能、更安全的登入、擴充性，以及 IT 和支援的增強功能。</span><span class="sxs-lookup"><span data-stu-id="b2c35-107">This connectivity method offers improved connection resiliency, more secure sign-in, extensibility, as well as enhancements for IT and support.</span></span> <span data-ttu-id="b2c35-108">若要深入瞭解，請參閱[RPC OVER HTTP 的支援終止于 Office 365](https://go.microsoft.com/fwlink/?linkid=863890)和[MAPI over HTTP](https://go.microsoft.com/fwlink/?linkid=393041)。</span><span class="sxs-lookup"><span data-stu-id="b2c35-108">To learn more, see [RPC over HTTP reaches end of support in Office 365](https://go.microsoft.com/fwlink/?linkid=863890) and [MAPI over HTTP](https://go.microsoft.com/fwlink/?linkid=393041).</span></span>

- <span data-ttu-id="b2c35-p102">**Autodiscover** Autodiscover 服務功能自動設定 Outlook 搭配 Exchange Online 使用。Outlook 使用者首次以電子郵件地址與密碼登入時，能直接由 Exchange Online 接收他們要求的檔案設定。這些設定會以建立並維護使用者設定檔所需的資訊自動更新 Outlook 用戶端。使用 Autodiscover 服務需要 SSL 憑證。此 SSL 憑證僅限於單一的主要 SSL 網域。</span><span class="sxs-lookup"><span data-stu-id="b2c35-p102">**Autodiscover** The Autodiscover service feature automatically configures Outlook to work with Exchange Online. Outlook users can receive their required profile settings directly from Exchange Online the first time they sign in with their email address and password. These settings automatically update the Outlook client with the information necessary to create and maintain the user's profile. An SSL certificate is required to use the Autodiscover service. This SSL certificate is limited to a single primary SSL domain.</span></span> 

- <span data-ttu-id="b2c35-114">快取**Exchange 模式**「快取 Exchange 模式」功能可讓 Outlook 使用者在未連線至網際網路時，存取其 Exchange Online 信箱的本機複本。</span><span class="sxs-lookup"><span data-stu-id="b2c35-114">**Cached Exchange Mode** The Cached Exchange Mode feature allows Outlook users to access local copies of their Exchange Online mailboxes when they are not connected to the internet.</span></span> <span data-ttu-id="b2c35-115">快取 Exchange 模式保存使用者在 Outlook 的 Exchange 信箱之用戶端副本，並自動將此副本與郵件伺服器進行同步處理。</span><span class="sxs-lookup"><span data-stu-id="b2c35-115">Cached Exchange Mode retains a client-side copy of users' Exchange mailboxes in Outlook and automatically synchronizes this copy with the email server.</span></span> <span data-ttu-id="b2c35-116">我們建議使用快取 Exchange 模式中的 Outlook，因為它提供離線存取，並協助提供回應使用者經驗，即使用戶端與伺服器之間的網路狀況不理想。</span><span class="sxs-lookup"><span data-stu-id="b2c35-116">We recommend using Outlook in Cached Exchange Mode because it provides offline access and helps to provide a responsive user experience even when network conditions between the client and the server are not ideal.</span></span> 

<span data-ttu-id="b2c35-p104">依照預設，Outlook 存取對所有使用者開放啟用狀態。管理員可以透過 Windows PowerShell，禁止特定的使用者或群組存取。我們建議使用最新版本的 Outlook--安裝最新版的 service pack--來存取 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="b2c35-p104">By default, Outlook access is enabled for all users. Administrators can disable access for specific users or groups through Windows PowerShell. We recommend using the latest version of Outlook—with the latest service pack installed—to access Exchange Online.</span></span> 
  
<span data-ttu-id="b2c35-120">如需 Exchange 2016 和 Exchange Online 所支援之 Outlook 用戶端的相關資訊，請參閱[Office 的系統需求](https://products.office.com/office-system-requirements)。</span><span class="sxs-lookup"><span data-stu-id="b2c35-120">For information about which Outlook clients are supported by Exchange 2016 and Exchange Online, see [System Requirements for Office](https://products.office.com/office-system-requirements).</span></span> 

<span data-ttu-id="b2c35-121">Microsoft 365 專為與最新的 Office 和 Office 版本搭配使用而設計。</span><span class="sxs-lookup"><span data-stu-id="b2c35-121">Microsoft 365 is designed to work with the latest browsers and versions of Office.</span></span> <span data-ttu-id="b2c35-122">如果您使用舊版的瀏覽器和不在主流支援的 Office 版本，請執行下列步驟：</span><span class="sxs-lookup"><span data-stu-id="b2c35-122">If you use older browsers and versions of Office that aren't in mainstream support:</span></span>

- <span data-ttu-id="b2c35-123">Microsoft 不會故意阻止您連線至服務，但您的經驗品質會隨著時間而降低。</span><span class="sxs-lookup"><span data-stu-id="b2c35-123">Microsoft won't deliberately prevent you from connecting to the service, but the quality of your experience may diminish over time.</span></span>
- <span data-ttu-id="b2c35-124">Microsoft 不會提供軟體更新，以解決與不安全相關的問題。</span><span class="sxs-lookup"><span data-stu-id="b2c35-124">Microsoft won't provide software updates to resolve non-security related problems.</span></span>

> [!IMPORTANT]
>  <span data-ttu-id="b2c35-125">Outlook 不包含在 Exchange Online 的訂閱價格之內。</span><span class="sxs-lookup"><span data-stu-id="b2c35-125">Outlook is not provided as part of the Exchange Online subscription price.</span></span> <span data-ttu-id="b2c35-126">適用于企業的 Microsoft 365 應用程式（包括 Microsoft Outlook）包含在某些方案中，而且可以以個別訂閱形式購買。</span><span class="sxs-lookup"><span data-stu-id="b2c35-126">Microsoft 365 Apps for enterprise (which includes Microsoft Outlook) is included in some plans and can be purchased as a separate subscription.</span></span> <span data-ttu-id="b2c35-127">如果您使用 POP 連線至 Exchange Online 電子郵件帳戶，將會看到下列限制： > 沒有任何行事曆資訊 > 沒有空閒/忙碌 > 資訊 > 沒有任何的電子郵件 > 當透過 POP 連線時，所有郵件都會下載至用戶端，而且在多部電腦或裝置之間（例如，膝上型電腦和電話），將不會進行同步處理。</span><span class="sxs-lookup"><span data-stu-id="b2c35-127">You will see the following limitations if you use POP to connect to an Exchange Online email account: >  No calendar information >  No free/busy information >  No Global Address List >  No push email >  When connecting through POP, all messages will be downloaded to the client and there will be no synchronization between multiple computers or devices (such as between a laptop and a phone).</span></span> 
  
## <a name="outlook-on-the-web"></a><span data-ttu-id="b2c35-128">Outlook 網頁版</span><span class="sxs-lookup"><span data-stu-id="b2c35-128">Outlook on the web</span></span>

<span data-ttu-id="b2c35-129">Outlook 網頁版是網路架構版本的 Outlook 電子郵件程式，搭配 Exchange Online 使用。</span><span class="sxs-lookup"><span data-stu-id="b2c35-129">Outlook on the web is a web-based version of the Outlook email program that is used with Exchange Online.</span></span> <span data-ttu-id="b2c35-130">它可讓使用者透過網頁瀏覽器存取其電子郵件、行事曆和連絡人，而不論他們連線至網際網路的任何地方。</span><span class="sxs-lookup"><span data-stu-id="b2c35-130">It lets users access their email, calendar, and contacts through a web browser from wherever they connect to the internet.</span></span> <span data-ttu-id="b2c35-131">如需有關支援瀏覽器的詳細資訊，請參閱[商務用 Outlook 網頁版支援的瀏覽器](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006)。</span><span class="sxs-lookup"><span data-stu-id="b2c35-131">For information about supported browsers, see [Supported browsers for Outlook on the web for business](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006).</span></span>
  
<span data-ttu-id="b2c35-132">Outlook 網頁版有兩種用戶端版本，皆可搭配 Exchange Online 使用：</span><span class="sxs-lookup"><span data-stu-id="b2c35-132">Outlook on the web comes in two client versions, both of which can be used with Exchange Online:</span></span>
  
- <span data-ttu-id="b2c35-133">**Outlook 網頁版** Outlook 網頁版標準版本提供 Exchange Online 使用者和 Outlook 使用者如出一轍的郵件傳送體驗。</span><span class="sxs-lookup"><span data-stu-id="b2c35-133">**Outlook on the web** The standard version of Outlook on the web provides Exchange Online users with a messaging experience most similar to that of Outlook users.</span></span> <span data-ttu-id="b2c35-134">它支援最新的網路瀏覽器，無論使用平板電腦、智慧型手機、桌上型電腦和筆電，都提供高效能運用。</span><span class="sxs-lookup"><span data-stu-id="b2c35-134">It supports most newer web browsers and is optimized for use on tablets and smartphones as well as desktops and laptops.</span></span> <span data-ttu-id="b2c35-135">使用者可以讀取和傳送郵件、組織連絡人，以及排定約會與會議。</span><span class="sxs-lookup"><span data-stu-id="b2c35-135">Users can read and send messages, organize contacts, and schedule appointments and meetings.</span></span> <span data-ttu-id="b2c35-136">預設的以活動為基礎的逾時是設定為 6 小時，但是可以 [由系統管理員在 Windows PowerShell 中設定](https://go.microsoft.com/fwlink/p/?LinkId=399155)，從 5 分鐘到 8 小時不等。</span><span class="sxs-lookup"><span data-stu-id="b2c35-136">The default activity-based time-out is set at six hours, but it can be [configured by an administrator in Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) from 5 minutes to 8 hours.</span></span> <span data-ttu-id="b2c35-137">此超時取決於 web 應用程式中的使用者互動，例如選取按鈕或選取郵件。</span><span class="sxs-lookup"><span data-stu-id="b2c35-137">This time-out depends on user interactions within the web app, such as selecting a button or selecting a message.</span></span> <span data-ttu-id="b2c35-138">另外也有由安全性驅動的個別逾時，這個逾時無法設定且不論使用者活動如何都會發生。</span><span class="sxs-lookup"><span data-stu-id="b2c35-138">There is also a separate security-driven time-out, which is not configurable and will occur regardless of user activity.</span></span> <span data-ttu-id="b2c35-139">如果使用者已經登入長達 8 小時，OWA 將會自動把使用者登出並要求重新驗證。</span><span class="sxs-lookup"><span data-stu-id="b2c35-139">If a user is logged in for 8 hours, OWA will automatically log the user out and ask for re-authentication.</span></span> 

- <span data-ttu-id="b2c35-140">**Outlook 網頁精簡版** Outlook 網頁精簡版可讓使用者透過任一種網路瀏覽器存取信箱。</span><span class="sxs-lookup"><span data-stu-id="b2c35-140">**The light version of Outlook on the web** The light version of Outlook on the web provides Exchange Online users access to the mailbox using almost any web browser.</span></span> <span data-ttu-id="b2c35-141">使用者可以讀取和傳送郵件、組織連絡人，以及排定約會與會議。</span><span class="sxs-lookup"><span data-stu-id="b2c35-141">Users can read and send messages, organize contacts, and schedule appointments and meetings.</span></span> <span data-ttu-id="b2c35-142">預設的以活動為基礎的逾時是設定為 6 小時，但是可以 [由系統管理員在 Windows PowerShell 中設定](https://go.microsoft.com/fwlink/p/?LinkId=399155)，從 5 分鐘到 8 小時不等。</span><span class="sxs-lookup"><span data-stu-id="b2c35-142">The default activity-based time-out is set at six hours, but it can be [configured by an administrator in Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) from 5 minutes to 8 hours.</span></span> <span data-ttu-id="b2c35-143">此超時取決於 web 應用程式中的使用者互動，例如選取按鈕或選取郵件。</span><span class="sxs-lookup"><span data-stu-id="b2c35-143">This time-out depends on user interactions within the web app, such as selecting a button or selecting a message.</span></span> <span data-ttu-id="b2c35-144">另外也有由安全性驅動的個別逾時，這個逾時無法設定且不論使用者活動如何都會發生。</span><span class="sxs-lookup"><span data-stu-id="b2c35-144">There is also a separate security-driven time-out, which is not configurable and will occur regardless of user activity.</span></span> <span data-ttu-id="b2c35-145">如果使用者已經登入長達 8 小時，精簡版的 OWA 將會自動把使用者登出並要求重新驗證。</span><span class="sxs-lookup"><span data-stu-id="b2c35-145">If a user is logged in for 8 hours, the light version of OWA will automatically log the user out and ask for re-authentication.</span></span> 

<span data-ttu-id="b2c35-146">Outlook 網頁版也有行動版本。</span><span class="sxs-lookup"><span data-stu-id="b2c35-146">Outlook on the web also is available in mobile versions.</span></span> <span data-ttu-id="b2c35-147">如需詳細資訊，請參閱[此頁面](https://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409)。</span><span class="sxs-lookup"><span data-stu-id="b2c35-147">For more information, see [this page](https://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409).</span></span>
  
## <a name="outlook-for-mac"></a><span data-ttu-id="b2c35-148">Mac 版 Outlook</span><span class="sxs-lookup"><span data-stu-id="b2c35-148">Outlook for Mac</span></span>

<span data-ttu-id="b2c35-149">Exchange Online 支援 Microsoft Outlook for Mac，可提供電子郵件、行事曆、通訊錄、工作清單及附注清單。</span><span class="sxs-lookup"><span data-stu-id="b2c35-149">Exchange Online supports Microsoft Outlook for Mac, which provides email, calendar, an address book, a task list, and a note list.</span></span>
  
## <a name="outlook-for-ios-android-and-windows-phone"></a><span data-ttu-id="b2c35-150">適用于 iOS、Android 和 Windows Phone 的 Outlook</span><span class="sxs-lookup"><span data-stu-id="b2c35-150">Outlook for iOS, Android, and Windows Phone</span></span>

<span data-ttu-id="b2c35-151">Exchange Online 適用于適用于 iOS、Android 和 Windows Phone 的 Outlook app。</span><span class="sxs-lookup"><span data-stu-id="b2c35-151">Exchange Online works with Outlook apps available for iOS, Android, and Windows Phone.</span></span> <span data-ttu-id="b2c35-152">在上述任一裝置上，使用 app store 尋找 Outlook 應用程式。</span><span class="sxs-lookup"><span data-stu-id="b2c35-152">On any of these devices, use the app store to find the Outlook app.</span></span> <span data-ttu-id="b2c35-153">以下是移動作業系統的分解。</span><span class="sxs-lookup"><span data-stu-id="b2c35-153">Here's a breakdown by mobile OS.</span></span>
  
|||||
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="b2c35-154">裝置</span><span class="sxs-lookup"><span data-stu-id="b2c35-154">Device</span></span>  <br/> |<span data-ttu-id="b2c35-155">Android</span><span class="sxs-lookup"><span data-stu-id="b2c35-155">Android</span></span>  <br/> |<span data-ttu-id="b2c35-156">iOS</span><span class="sxs-lookup"><span data-stu-id="b2c35-156">iOS</span></span>  <br/> |<span data-ttu-id="b2c35-157">Windows Phone</span><span class="sxs-lookup"><span data-stu-id="b2c35-157">Windows Phone</span></span>  <br/> |
|<span data-ttu-id="b2c35-158">Outlook 行動應用程式可用性</span><span class="sxs-lookup"><span data-stu-id="b2c35-158">Outlook mobile app availability</span></span>  <br/> |<span data-ttu-id="b2c35-159">是</span><span class="sxs-lookup"><span data-stu-id="b2c35-159">Yes</span></span>  <br/> [<span data-ttu-id="b2c35-160">取得適用于 Android 的 Outlook</span><span class="sxs-lookup"><span data-stu-id="b2c35-160">Get Outlook for Android</span></span>](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |<span data-ttu-id="b2c35-161">是</span><span class="sxs-lookup"><span data-stu-id="b2c35-161">Yes</span></span>  <br/> [<span data-ttu-id="b2c35-162">取得 iOS 的 Outlook</span><span class="sxs-lookup"><span data-stu-id="b2c35-162">Get Outlook for iOS</span></span>](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |<span data-ttu-id="b2c35-163">內建</span><span class="sxs-lookup"><span data-stu-id="b2c35-163">Built-in</span></span>  <br/> |
|<span data-ttu-id="b2c35-164">與 Exchange Online 相容的內建電子郵件應用程式</span><span class="sxs-lookup"><span data-stu-id="b2c35-164">Built-in email apps compatible with Exchange Online</span></span>  <br/> |<span data-ttu-id="b2c35-165">Gmail app/Samsung 電子郵件應用程式</span><span class="sxs-lookup"><span data-stu-id="b2c35-165">Gmail app/Samsung Email app</span></span>  <br/> |<span data-ttu-id="b2c35-166">iOS 郵件應用程式</span><span class="sxs-lookup"><span data-stu-id="b2c35-166">iOS Mail app</span></span>  <br/> |<span data-ttu-id="b2c35-167">Outlook 郵件、行事曆、連絡人</span><span class="sxs-lookup"><span data-stu-id="b2c35-167">Outlook Mail, calendar, contacts</span></span>  <br/> |
|<span data-ttu-id="b2c35-168">詳細資訊</span><span class="sxs-lookup"><span data-stu-id="b2c35-168">More information</span></span>  <br/> |[<span data-ttu-id="b2c35-169">Android mobile 設定</span><span class="sxs-lookup"><span data-stu-id="b2c35-169">Android mobile setup</span></span>](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[<span data-ttu-id="b2c35-170">iPhone 或 iPad 安裝程式</span><span class="sxs-lookup"><span data-stu-id="b2c35-170">iPhone or iPad setup</span></span>](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[<span data-ttu-id="b2c35-171">Windows Phone 設定</span><span class="sxs-lookup"><span data-stu-id="b2c35-171">Windows Phone setup</span></span>](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |

<span data-ttu-id="b2c35-172">此外，還有一些搭配使用 Exchange Online 和裝置（包括 Blackberry）的選項。</span><span class="sxs-lookup"><span data-stu-id="b2c35-172">There are also options for using Exchange Online with devices, including Blackberry.</span></span>
  
### <a name="feature-availability"></a><span data-ttu-id="b2c35-173">功能可用性</span><span class="sxs-lookup"><span data-stu-id="b2c35-173">Feature availability</span></span>

<span data-ttu-id="b2c35-174">Outlook 為使用者提供來自現代行動應用程式的快速、直觀的電子郵件和行事歷經驗，同時也是唯一提供最佳功能支援的應用程式。</span><span class="sxs-lookup"><span data-stu-id="b2c35-174">Outlook gives users the fast, intuitive email and calendar experience that they expect from a modern mobile app, while being the only app to provide support for the best features.</span></span> <span data-ttu-id="b2c35-175">這是唯一專為支援完整的 Microsoft 體驗而設計的電子郵件應用程式，可讓使用者在桌面與行動裝置上具有連貫的體驗。</span><span class="sxs-lookup"><span data-stu-id="b2c35-175">It is the only email app specifically designed to support the full Microsoft experience, giving users a coherent experience from desktop to mobile.</span></span> <span data-ttu-id="b2c35-176">Outlook 與 Intune、enterprise 可移動性和 security 和 Exchange 控制項整合，可讓資料和使用者安全。</span><span class="sxs-lookup"><span data-stu-id="b2c35-176">Outlook is integrated with Intune, enterprise mobility and security, and Exchange controls to keep data and users safe.</span></span>
  
<span data-ttu-id="b2c35-177">透過 Outlook，使用者可以：</span><span class="sxs-lookup"><span data-stu-id="b2c35-177">With Outlook, users can:</span></span>
  
- <span data-ttu-id="b2c35-178">從行動裝置管理其全天。</span><span class="sxs-lookup"><span data-stu-id="b2c35-178">Manage their entire day from a mobile device.</span></span>

- <span data-ttu-id="b2c35-179">連線至所需的應用程式和服務，以提高其生產力，同時保持其工作和個人資訊的安全。</span><span class="sxs-lookup"><span data-stu-id="b2c35-179">Connect to the apps and services they need to be productive, while keeping their work and personal information separate and secure.</span></span>

<span data-ttu-id="b2c35-180">使用者可以使用 Outlook for iOS、適用于 Android 的 outlook 或 Outlook for Windows Phone，使用者可以：</span><span class="sxs-lookup"><span data-stu-id="b2c35-180">With Outlook for iOS, Outlook for Android, or Outlook for Windows Phone, users can:</span></span> 
  
- <span data-ttu-id="b2c35-181">受益于優先順序重要電子郵件的焦點收件匣</span><span class="sxs-lookup"><span data-stu-id="b2c35-181">Benefit from a focused inbox that priorities important email</span></span>

- <span data-ttu-id="b2c35-182">自訂滑動筆勢以符合其獨特的電子郵件習慣</span><span class="sxs-lookup"><span data-stu-id="b2c35-182">Customize swipe gestures to match their unique email habits</span></span>

- <span data-ttu-id="b2c35-183">建立可直接新增至行事曆的旅行行程，並提供快速的重要資訊</span><span class="sxs-lookup"><span data-stu-id="b2c35-183">Create travel itineraries that can be added directly to the calendar, with key information available at a glance</span></span>

- <span data-ttu-id="b2c35-184">從收件匣到會議的 RSVP。</span><span class="sxs-lookup"><span data-stu-id="b2c35-184">RSVP to meetings from the inbox.</span></span>

- <span data-ttu-id="b2c35-185">在電子郵件和行事曆約會中使用直觀的圖示，可協助使用者快速處理資訊</span><span class="sxs-lookup"><span data-stu-id="b2c35-185">Use intuitive icons in email and calendar appointments that help them process information quickly</span></span>

- <span data-ttu-id="b2c35-186">在所有裝置中使用一致且熟悉的 Outlook 體驗</span><span class="sxs-lookup"><span data-stu-id="b2c35-186">Use a consistent and familiar Outlook experience across all devices</span></span>

- <span data-ttu-id="b2c35-187">從行事曆輕鬆啟動及加入 Skype 會議</span><span class="sxs-lookup"><span data-stu-id="b2c35-187">Easily launch and join Skype meetings from the calendar</span></span>

- <span data-ttu-id="b2c35-188">讀取和回應 IRM 加密和受保護的電子郵件</span><span class="sxs-lookup"><span data-stu-id="b2c35-188">Read and respond to IRM encrypted and protected emails</span></span>

- <span data-ttu-id="b2c35-189">在商務用 OneDrive 中共用儲存的檔案</span><span class="sxs-lookup"><span data-stu-id="b2c35-189">Share files stored in OneDrive for Business</span></span>

- <span data-ttu-id="b2c35-190">使用攻絲設定自動回復</span><span class="sxs-lookup"><span data-stu-id="b2c35-190">Set Automatic Replies with a tap</span></span>

- <span data-ttu-id="b2c35-191">查看及管理共用及委派的行事曆</span><span class="sxs-lookup"><span data-stu-id="b2c35-191">View and manage shared and delegated calendars</span></span>

- <span data-ttu-id="b2c35-192">使用一些分路器搜尋公司的全域通訊清單</span><span class="sxs-lookup"><span data-stu-id="b2c35-192">Search their company's global address list with a few taps</span></span>

- <span data-ttu-id="b2c35-193">查看同事的可用性及排程適用于每個人的會議時間</span><span class="sxs-lookup"><span data-stu-id="b2c35-193">View coworker's availability and schedule a meeting time that works for everyone</span></span>

- <span data-ttu-id="b2c35-194">請參閱被邀請者 accept、暫定和拒絕狀態</span><span class="sxs-lookup"><span data-stu-id="b2c35-194">See invitees accept, tentative, and decline status</span></span>

- <span data-ttu-id="b2c35-195">從手機共用行事曆</span><span class="sxs-lookup"><span data-stu-id="b2c35-195">Share calendars right from their phones</span></span>

- <span data-ttu-id="b2c35-196">從行事曆開始及加入 Skype 會議</span><span class="sxs-lookup"><span data-stu-id="b2c35-196">Start and join Skype meetings right from a calendar</span></span>

- <span data-ttu-id="b2c35-197">在單一位置存取工作和個人行事曆，不需要切換應用程式</span><span class="sxs-lookup"><span data-stu-id="b2c35-197">Access work and personal calendars in one place, without switching apps</span></span>
    
## <a name="exchange-activesync"></a><span data-ttu-id="b2c35-198">Exchange ActiveSync</span><span class="sxs-lookup"><span data-stu-id="b2c35-198">Exchange ActiveSync</span></span>

<span data-ttu-id="b2c35-199">Exchange Online 支援 Microsoft Exchange ActiveSync 協定，將行動裝置與 Exchange Online 之間的信箱資料同步處理，使用者便能隨時隨地存取電子郵件、行事曆、聯絡人和工作。</span><span class="sxs-lookup"><span data-stu-id="b2c35-199">Exchange Online supports the Microsoft Exchange ActiveSync protocol, which synchronizes mailbox data between mobile devices and Exchange Online, so users can access their email, calendar, contacts, and tasks on the go.</span></span>
  
<span data-ttu-id="b2c35-200">Exchange ActiveSync 可與各種行動裝置相容，包括 Microsoft Windows Phone、Apple iPhone 和 iPad，以及 Android 手機和平板電腦。</span><span class="sxs-lookup"><span data-stu-id="b2c35-200">A wide range of mobile devices work with Exchange ActiveSync, including Microsoft Windows Phone, Apple iPhone and iPad, and Android phones and tablets.</span></span> <span data-ttu-id="b2c35-201">除了行動電話和裝置之外，Windows Phone 中的郵件應用程式也會使用 Exchange ActiveSync 連接至 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="b2c35-201">In addition to mobile phones and devices, the Mail application in Windows Phone uses Exchange ActiveSync to connect to Exchange Online.</span></span> <span data-ttu-id="b2c35-202">目前 Exchange ActiveSync 授權條款的完整清單可在 Exchange ActiveSync Licensing 網站查閱。</span><span class="sxs-lookup"><span data-stu-id="b2c35-202">A complete list of current Exchange ActiveSync licensees is available at the Exchange ActiveSync Licensing site.</span></span>
  
<span data-ttu-id="b2c35-203">如需 Exchange ActiveSync 的詳細資訊，請參閱[exchange ActiveSync](https://go.microsoft.com/fwlink/p/?LinkId=271792)。</span><span class="sxs-lookup"><span data-stu-id="b2c35-203">For more information about Exchange ActiveSync, see [Exchange ActiveSync](https://go.microsoft.com/fwlink/p/?LinkId=271792).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="b2c35-204">每個信箱的 Exchange ActiveSync 裝置數目上限是 100。</span><span class="sxs-lookup"><span data-stu-id="b2c35-204">The maximum number of Exchange ActiveSync devices per mailbox is 100.</span></span> 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a><span data-ttu-id="b2c35-205">以 Exchange Web Services（EWS）研發的應用程式</span><span class="sxs-lookup"><span data-stu-id="b2c35-205">Applications developed with Exchange Web Services (EWS)</span></span>

 <span data-ttu-id="b2c35-206">以 Exchange Web Services (EWS) 或 EWS Managed API 開發的應用程式，可讓管理員從執行於內部部署、Azure 或其他託管服務中的應用程式，存取儲存在 Exchange Online 那邊的資料。</span><span class="sxs-lookup"><span data-stu-id="b2c35-206">Applications developed using Exchange Web Services (EWS) or the EWS Managed API let administrators access data stored with Exchange Online from applications that are running on-premises, in Azure, or in other hosted services.</span></span> 
  
<span data-ttu-id="b2c35-207">如需以 Exchange Web 服務開發之應用程式的詳細資訊，請參閱 [Exchange 中的 Web 服務](https://go.microsoft.com/fwlink/?LinkId=325346)。</span><span class="sxs-lookup"><span data-stu-id="b2c35-207">For more information on applications developed with Exchange Web Services, see [Web Services in Exchange](https://go.microsoft.com/fwlink/?LinkId=325346).</span></span>
  
## <a name="pop-and-imap"></a><span data-ttu-id="b2c35-208">POP 與 IMAP</span><span class="sxs-lookup"><span data-stu-id="b2c35-208">POP and IMAP</span></span>

<span data-ttu-id="b2c35-p114">Exchange Online 支援透過 POP3 和 IMAP4 協定的信箱存取。POP 和 IMAP 存取要求使用 SSL 加密。預設情況下，為所有使用者啟用 POP。使用者能在 Outlook 網頁版中檢視他們的 POP 和 IMAP 連線設定。管理員可以對個別使用者分別禁用 POP 和 IMAP 存取。</span><span class="sxs-lookup"><span data-stu-id="b2c35-p114">Exchange Online supports mailbox access through both POP3 and IMAP4 protocols. POP and IMAP access requires encryption using SSL. POP is enabled by default for all users. Users can view their POP and IMAP connection settings in Outlook on the web. Administrators can disable POP and IMAP access on a per-user basis.</span></span>
  
<span data-ttu-id="b2c35-214">如需 POP3 和 IMAP4 連線的相關資訊，請參閱 [POP3 和 IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070)。</span><span class="sxs-lookup"><span data-stu-id="b2c35-214">For more information about POP3 and IMAP4 connectivity, see [POP3 and IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070).</span></span>
  
## <a name="smtp"></a><span data-ttu-id="b2c35-215">SMTP</span><span class="sxs-lookup"><span data-stu-id="b2c35-215">SMTP</span></span>

<span data-ttu-id="b2c35-p115">簡易郵件傳輸通訊協定（SMTP）是用來發送外寄郵件給透過 IMAP 或 POP 連線至 Exchange Online 的客戶端。它是路由和通過 Exchange 伺服器傳遞的主協定。Exchange Online 為需要 SMTP 郵件提交的授權內部客戶應用程式提供兩種型態的 SMTP 轉送服務：</span><span class="sxs-lookup"><span data-stu-id="b2c35-p115">Simple Mail Transfer Protocol (SMTP) is used to send outbound mail for clients that connect to Exchange Online through IMAP or POP. It is the primary protocol for routing and delivery through Exchange Server. Exchange Online supports two types of SMTP relay services for authorized internal customer applications that require SMTP mail submission:</span></span>
  
- <span data-ttu-id="b2c35-219">SMTP 郵件提交給託管環境內的使用者。</span><span class="sxs-lookup"><span data-stu-id="b2c35-219">SMTP message submission to users inside the managed environment.</span></span>

- <span data-ttu-id="b2c35-220">已通過驗證的 SMTP 郵件將轉送到託管環境的外部地址。</span><span class="sxs-lookup"><span data-stu-id="b2c35-220">Authenticated SMTP message relay to addresses outside the managed environment.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="b2c35-p116">需要授權的來源伺服器 IP 位址以允許 SMTP 轉送。使用 SMTP 寄送郵件時，需要傳輸層安全性（TLS）加密與驗證。</span><span class="sxs-lookup"><span data-stu-id="b2c35-p116">IP addresses for authorized source servers are required to allow SMTP relay. Transport Layer Security (TLS) encryption and authentication is required when using SMTP to send email.</span></span> 
  
## <a name="blackberryreg-devices"></a><span data-ttu-id="b2c35-223">BlackBerry &reg; 裝置</span><span class="sxs-lookup"><span data-stu-id="b2c35-223">BlackBerry&reg; devices</span></span>

<span data-ttu-id="b2c35-224">電子郵件可透過 &reg; Exchange ActiveSync 在 BlackBerry 裝置上。</span><span class="sxs-lookup"><span data-stu-id="b2c35-224">Email is available on BlackBerry&reg; devices via Exchange ActiveSync.</span></span> <span data-ttu-id="b2c35-225">若要瞭解您的選項是什麼，請參閱下列主題：</span><span class="sxs-lookup"><span data-stu-id="b2c35-225">To find out what your options are, see these topics:</span></span>
  
- [<span data-ttu-id="b2c35-226">在 BlackBerry 裝置上設定電子郵件</span><span class="sxs-lookup"><span data-stu-id="b2c35-226">Set up email on a BlackBerry device</span></span>](https://go.microsoft.com/fwlink/?linkid=863394)

- [<span data-ttu-id="b2c35-227">在 BlackBerry 裝置上設定電子郵件7.1 作業系統及更早版本</span><span class="sxs-lookup"><span data-stu-id="b2c35-227">Set up email on a BlackBerry device 7.1 OS and earlier</span></span>](https://go.microsoft.com/fwlink/?linkid=863403)

<span data-ttu-id="b2c35-228">如需詳細資訊，請參閱 [BlackBerry](../office-365-platform-service-description/blackberry.md)。</span><span class="sxs-lookup"><span data-stu-id="b2c35-228">For more information, see [BlackBerry](../office-365-platform-service-description/blackberry.md).</span></span>
  
> [!NOTE]
> <span data-ttu-id="b2c35-p118">如果您在中國使用 21Vianet 運作的 Office 365，將無法使用 BlackBerry Business 雲端服務。不過您可以使用 Exchange ActiveSync 裝置或 Research in Motion 的產品 (RIM、BlackBerry 無線電子郵件解決方案) 來執行 BlackBerry 企業伺服器 (BES)。</span><span class="sxs-lookup"><span data-stu-id="b2c35-p118">If you are using Office 365 operated by 21Vianet in China, BlackBerry Business Cloud Services is not available. However, you can use Exchange ActiveSync devices or an offering from Research in Motion (RIM, the BlackBerry wireless email solution) to run Blackberry Enterprise Server (BES).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="b2c35-231">功能可用性</span><span class="sxs-lookup"><span data-stu-id="b2c35-231">Feature availability</span></span>

<span data-ttu-id="b2c35-232">若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online 服務說明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="b2c35-232">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
  