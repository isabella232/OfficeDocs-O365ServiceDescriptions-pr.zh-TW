---
title: Exchange Online 封存中的用戶端功能
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- clients-and-devices-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c8d5f97a-607f-4949-a4f7-0b9e3b246851
description: Microsoft Exchange Online 封存可讓使用者從各種裝置和平臺連接至其封存信箱。 所有對使用者封存進行的網路連線都是透過網際網路進行，不需要虛擬私人網路 (VPN) 連線。 組織可以發佈內部部署用戶端存取伺服器，讓使用者能夠使用 Outlook 無所不在 存取其主要信箱，而不需要 VPN 連線。 如果要求要有 VPN 連線才能存取內部部署伺服器上使用者的主要信箱，則此要求並不會變。
ms.openlocfilehash: b4f35a2bdc4e0c9f4ae54ec7be4997c9d946e0d4
ms.sourcegitcommit: af6f6ee0a74831a5af784612c7a4316658a53e28
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/18/2019
ms.locfileid: "35018295"
---
# <a name="client-features-in-exchange-online-archiving"></a><span data-ttu-id="6cc5b-106">Exchange Online 封存中的用戶端功能</span><span class="sxs-lookup"><span data-stu-id="6cc5b-106">Client Features in Exchange Online Archiving</span></span>

<span data-ttu-id="6cc5b-107">Microsoft Exchange Online 封存可讓使用者從各種裝置和平臺連接至其封存信箱。</span><span class="sxs-lookup"><span data-stu-id="6cc5b-107">Microsoft Exchange Online Archiving enables users to connect to their archive mailboxes from a variety of devices and platforms.</span></span> <span data-ttu-id="6cc5b-108">所有對使用者封存進行的網路連線都是透過網際網路進行，不需要虛擬私人網路 (VPN) 連線。</span><span class="sxs-lookup"><span data-stu-id="6cc5b-108">All network connectivity to the user's archive occurs over the Internet, and virtual private network (VPN) connections are not required.</span></span> <span data-ttu-id="6cc5b-109">組織可以發佈內部部署用戶端存取伺服器，讓使用者能夠使用 Outlook 無所不在 存取其主要信箱，而不需要 VPN 連線。</span><span class="sxs-lookup"><span data-stu-id="6cc5b-109">Organizations can publish an on-premises Client Access server to allow users to access their primary mailbox using Outlook Anywhere, without requiring a VPN connection.</span></span> <span data-ttu-id="6cc5b-110">如果要求要有 VPN 連線才能存取內部部署伺服器上使用者的主要信箱，則此要求並不會變。</span><span class="sxs-lookup"><span data-stu-id="6cc5b-110">If VPN access is required to access the user's primary mailbox located on an on-premises server, this requirement does not change.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="6cc5b-111">不論什麼用戶端軟體，只要是發出會對 Exchange Online Archiving服務的健康狀況造成負面影響的連線，Microsoft 保留封鎖或調節這類連線的權利。</span><span class="sxs-lookup"><span data-stu-id="6cc5b-111">Microsoft reserves the right to block or throttle connections from any client software that negatively impacts the health of the Exchange Online Archiving service.</span></span> 
  
## <a name="microsoft-outlook"></a><span data-ttu-id="6cc5b-112">Microsoft Outlook</span><span class="sxs-lookup"><span data-stu-id="6cc5b-112">Microsoft Outlook</span></span>

<span data-ttu-id="6cc5b-p103">Microsoft Outlook 是一款功能豐富的電子郵件程式，可支援行事曆、聯絡人與工作。Exchange Online Archiving可支援 Outlook 2013、Outlook 2010 及 Outlook 2007。其主要功能包括：</span><span class="sxs-lookup"><span data-stu-id="6cc5b-p103">Microsoft Outlook is a rich email program that includes support for calendaring, contacts, and tasks. Exchange Online Archiving supports Outlook 2013, Outlook 2010, and Outlook 2007. Key features include:</span></span>
  
- <span data-ttu-id="6cc5b-p104">**Outlook 無所不在** Outlook 無所不在 可以讓 Outlook 使用者透過網際網路連線至 Exchange Server 和 Exchange Online Archiving，而不需要 VPN 連線。Outlook 與 Exchange Online Archiving之間是透過 SSL 安全保護通道，使用 RPC-over-HTTP Windows 網路元件進行通訊。</span><span class="sxs-lookup"><span data-stu-id="6cc5b-p104">**Outlook Anywhere** Outlook Anywhere lets Outlook users connect to Exchange Server and Exchange Online Archiving over the Internet with no need for a VPN connection. Communication between Outlook and Exchange Online Archiving occurs via an SSL-secured tunnel, using the RPC-over-HTTP Windows networking component.</span></span>    
- <span data-ttu-id="6cc5b-p105">**Autodiscover** Exchange Autodiscover 服務會自動設定 Outlook 使用Exchange Online Archiving。Autodiscover 可以讓 Outlook 使用者在第一次以電子郵件地址和密碼登入時 (以及此後的固定間隔)，直接從 Exchange 接收必要的設定檔設定。</span><span class="sxs-lookup"><span data-stu-id="6cc5b-p105">**Autodiscover** The Exchange Autodiscover service automatically configures Outlook to work with Exchange Online Archiving. Autodiscover enables Outlook users to receive their required profile settings directly from Exchange the first time (and at fixed intervals thereafter) that they sign in with their email address and password.</span></span> 
    
<span data-ttu-id="6cc5b-120">Outlook 2010 與更新版本及 Outlook Web App 可提供使用者對封存的完整功能，以及諸如保留和封存原則等相關功能。</span><span class="sxs-lookup"><span data-stu-id="6cc5b-120">Outlook 2010 and later and Outlook Web App provide users with the full features of the archive, as well as related features like retention and archive policies.</span></span>
  
<span data-ttu-id="6cc5b-p106">Outlook 2007 可提供對封存的基本支援，但是並非所有封存和法規遵循功能都可以在 Outlook 2007 中使用。例如在 Outlook 2007，使用者無法對其信箱中的項目套用保留或封存原則，而必須仰賴管理員佈建的原則。Outlook 2007 使用者必須要有 2011 年 2 月的 Office 2007 累計更新，才能存取封存。</span><span class="sxs-lookup"><span data-stu-id="6cc5b-p106">Outlook 2007 provides basic support for the archive, but not all archiving and compliance features are available in Outlook 2007. For example, with Outlook 2007, users cannot apply retention or archive policies to items in their mailboxes. They must rely on administrator-provisioned policies instead. Outlook 2007 users require the Office 2007 Cumulative Update for February 2011 to access the archive.</span></span>
  
> [!NOTE]
> <span data-ttu-id="6cc5b-p107">Exchange Online Archiving並未隨附 Outlook。Microsoft Office 365 專業增強版 (包括 Microsoft Outlook) 隨附於某些 Office 365 計劃內，但也能以單獨訂閱的方式購買。如需詳細資訊，請參閱[Office 365 方案選項](../office-365-platform-service-description/office-365-plan-options.md)。如需 Office 365 專業增強版 的詳細資訊，請參閱＜[Office 應用程式服務說明](../office-applications-service-description/office-applications-service-description.md)＞。</span><span class="sxs-lookup"><span data-stu-id="6cc5b-p107">Outlook is not provided with Exchange Online Archiving. Microsoft Office 365 ProPlus (which includes Microsoft Outlook) is included in some Office 365 plans and can be purchased as a separate subscription. For more information, see [Office 365 Plan Options](../office-365-platform-service-description/office-365-plan-options.md). For more information about Office 365 ProPlus, see the [Office Applications Service Description](../office-applications-service-description/office-applications-service-description.md).</span></span> 
  
### <a name="clients-supported-by-exchange-online-archiving"></a><span data-ttu-id="6cc5b-129">Exchange Online 封存所支援的用戶端</span><span class="sxs-lookup"><span data-stu-id="6cc5b-129">Clients supported by Exchange Online Archiving</span></span>

<span data-ttu-id="6cc5b-130">下表列出 Exchange Online Archiving所支援的用戶端：</span><span class="sxs-lookup"><span data-stu-id="6cc5b-130">The table below lists the clients supported by Exchange Online Archiving:</span></span>
  
|<span data-ttu-id="6cc5b-131">**用戶端**</span><span class="sxs-lookup"><span data-stu-id="6cc5b-131">**Client**</span></span>|<span data-ttu-id="6cc5b-132">**EOA 支援**</span><span class="sxs-lookup"><span data-stu-id="6cc5b-132">**EOA Support**</span></span>|
|:-----|:-----|
|<span data-ttu-id="6cc5b-133">Outlook 2010 及更新版本</span><span class="sxs-lookup"><span data-stu-id="6cc5b-133">Outlook 2010 and later</span></span>  <br/> |<span data-ttu-id="6cc5b-134">支援 Exchange Online Archiving 的最新功能。<sup>1</sup></span><span class="sxs-lookup"><span data-stu-id="6cc5b-134">Supports the latest features in Exchange Online Archiving.<sup>1</sup></span></span> <br/> |
|<span data-ttu-id="6cc5b-135">Outlook 2007</span><span class="sxs-lookup"><span data-stu-id="6cc5b-135">Outlook 2007</span></span>  <br/> |<span data-ttu-id="6cc5b-136">支援搭配 Exchange Online Archiving使用。<sup>1,2</sup></span><span class="sxs-lookup"><span data-stu-id="6cc5b-136">Supported for use with Exchange Online Archiving.<sup>1,2</sup></span></span> <br/> |
|<span data-ttu-id="6cc5b-137">Outlook 2003</span><span class="sxs-lookup"><span data-stu-id="6cc5b-137">Outlook 2003</span></span>  <br/> |<span data-ttu-id="6cc5b-138">不支援</span><span class="sxs-lookup"><span data-stu-id="6cc5b-138">Not supported</span></span>  <br/> |
|<span data-ttu-id="6cc5b-139">Outlook for Mac 2011</span><span class="sxs-lookup"><span data-stu-id="6cc5b-139">Outlook for Mac 2011</span></span>  <br/> |<span data-ttu-id="6cc5b-140">不支援</span><span class="sxs-lookup"><span data-stu-id="6cc5b-140">Not supported</span></span>  <br/> |
|<span data-ttu-id="6cc5b-141">Mac 版 Outlook</span><span class="sxs-lookup"><span data-stu-id="6cc5b-141">Outlook for Mac</span></span>  <br/> |<span data-ttu-id="6cc5b-142">支援與 Exchange Online 封存搭配使用。<sup>3</sup></span><span class="sxs-lookup"><span data-stu-id="6cc5b-142">Supported for use with Exchange Online Archiving.<sup>3</sup></span></span> <br/> |
|<span data-ttu-id="6cc5b-143">Microsoft Office Entourage 2008 Web Services Edition</span><span class="sxs-lookup"><span data-stu-id="6cc5b-143">Microsoft Office Entourage 2008 Web Services Edition</span></span>  <br/> |<span data-ttu-id="6cc5b-144">不支援</span><span class="sxs-lookup"><span data-stu-id="6cc5b-144">Not supported</span></span>  <br/> |
|<span data-ttu-id="6cc5b-145">IMAP 與 POP</span><span class="sxs-lookup"><span data-stu-id="6cc5b-145">IMAP and POP</span></span>  <br/> |<span data-ttu-id="6cc5b-146">不支援</span><span class="sxs-lookup"><span data-stu-id="6cc5b-146">Not supported</span></span>  <br/> |
|<span data-ttu-id="6cc5b-147">Exchange ActiveSync (行動裝置)</span><span class="sxs-lookup"><span data-stu-id="6cc5b-147">Exchange ActiveSync (Mobile devices)</span></span>  <br/> |<span data-ttu-id="6cc5b-148">不支援</span><span class="sxs-lookup"><span data-stu-id="6cc5b-148">Not supported</span></span>  <br/> |
   
> [!NOTE]
> <span data-ttu-id="6cc5b-149"><sup>1</sup> Outlook included with Microsoft Office Standard is not supported.</span><span class="sxs-lookup"><span data-stu-id="6cc5b-149"><sup>1</sup> Outlook included with Microsoft Office Standard is not supported.</span></span> <span data-ttu-id="6cc5b-150">To learn more, see [License requirements for Personal Archive and retention policies](https://support.office.com/article/Outlook-license-requirements-for-Exchange-features-46B6B7C5-C3CA-43E5-8424-1E2807917C99).</span><span class="sxs-lookup"><span data-stu-id="6cc5b-150">To learn more, see [License requirements for Personal Archive and retention policies](https://support.office.com/article/Outlook-license-requirements-for-Exchange-features-46B6B7C5-C3CA-43E5-8424-1E2807917C99).</span></span> <br/><span data-ttu-id="6cc5b-151"> 
<sup>2</sup> Requires update to enable archiving support.</span><span class="sxs-lookup"><span data-stu-id="6cc5b-151"> 
<sup>2</sup> Requires update to enable archiving support.</span></span> <span data-ttu-id="6cc5b-152">Outlook 2007 users cannot view or apply retention or archive policies to items in their archive mailboxes; they must rely on administrator-provisioned policies.</span><span class="sxs-lookup"><span data-stu-id="6cc5b-152">Outlook 2007 users cannot view or apply retention or archive policies to items in their archive mailboxes; they must rely on administrator-provisioned policies.</span></span> <span data-ttu-id="6cc5b-153">Additionally, Outlook 2007 users cannot search the on-premises mailbox and the archive at the same time.</span><span class="sxs-lookup"><span data-stu-id="6cc5b-153">Additionally, Outlook 2007 users cannot search the on-premises mailbox and the archive at the same time.</span></span> <br/><span data-ttu-id="6cc5b-154"> 
<sup>3</sup>您無法使用 outlook 2016 for Mac 或 Outlook for mac 來移動或複製資料夾、行事曆專案、連絡人、工作或記事至您的封存, 或在封存信箱中查看這些專案 (如果先前已使用任何其他版本的 Outlook 移動過的話) (例如Outlook 2016 for Windows)。</span><span class="sxs-lookup"><span data-stu-id="6cc5b-154"> 
<sup>3</sup> You can't use Outlook 2016 for Mac or Outlook for Mac to move or copy folders, calendar items, contacts, tasks, or notes to your archive, or view them in the archive mailbox, if the items were previously moved there by using any other version of Outlook (such as Outlook 2016 for Windows).</span></span> <span data-ttu-id="6cc5b-155">如需詳細資訊, 請參閱[使用您的線上封存搭配 Outlook 2016 For Mac](https://support.office.com/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238)。</span><span class="sxs-lookup"><span data-stu-id="6cc5b-155">For more information, see [Use your online archive with Outlook 2016 for Mac](https://support.office.com/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238).</span></span> 

## <a name="outlook-web-app"></a><span data-ttu-id="6cc5b-156">Outlook Web App</span><span class="sxs-lookup"><span data-stu-id="6cc5b-156">Outlook Web App</span></span>

<span data-ttu-id="6cc5b-p111">Outlook Web App 是網路架構版本的 Outlook 電子郵件程式，搭配 Exchange Online 使用。透過 Outlook Web App，使用者無論身在何處 (例如在家、在辦公室或出門在外)，只要連上網際網路，就能存取其電子郵件。</span><span class="sxs-lookup"><span data-stu-id="6cc5b-p111">Outlook Web App is a web-based version of the Outlook email program that is used with Exchange Online. Wherever users are connected to the Internet—at home, at the office, or on the road—they can access their email through Outlook Web App.</span></span>
  
<span data-ttu-id="6cc5b-p112">使用者可以藉由登入內部部署 Outlook Web App (使用相同 URL) 存取其封存。封存會隨主要信箱一起出現在 Outlook Web App 中。沒有直接從 Outlook Web App 存取封存的明確方式。</span><span class="sxs-lookup"><span data-stu-id="6cc5b-p112">Users can access their archive by signing in to Outlook Web App on-premises (using the same URL). The archive appears alongside their primary mailbox in Outlook Web App. There is no explicit way to access the archive directly from Outlook Web App.</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="6cc5b-162">功能可用性</span><span class="sxs-lookup"><span data-stu-id="6cc5b-162">Feature Availability</span></span>

<span data-ttu-id="6cc5b-163">若要檢視 Office 365 計劃、獨立選項和內部部署解決方案中的功能可用性，請參閱 [Exchange Online 封存服務說明](exchange-online-archiving-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="6cc5b-163">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Archiving Service Description](exchange-online-archiving-service-description.md).</span></span>