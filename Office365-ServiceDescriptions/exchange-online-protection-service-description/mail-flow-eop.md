---
title: 郵件流程[EOP]
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: 對使用 Office 365 的大多數組織而言，我們可以代管信箱並處理郵件流程。 這是最簡單的配置，並代表 Office 365 管理所有的信箱和篩選。 不過，某些組織基於業務需求而需要將所有信箱保留在內部。 Exchange Online Protection (EOP) 可提供您這個功能，並在雲端提供防毒和反垃圾郵件處理。 如需詳細資訊並購買 EOP，請移至 Exchange Online Protection。
ms.openlocfilehash: 5a581c8004bcdc001160a2499cd623c6eee772f2
ms.sourcegitcommit: 3d180fb603896239b30d9db6ba865843c29801b0
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/10/2019
ms.locfileid: "37442728"
---
# <a name="mail-floweop"></a><span data-ttu-id="6d6a6-107">郵件流程[EOP]</span><span class="sxs-lookup"><span data-stu-id="6d6a6-107">Mail Flow[EOP]</span></span>

<span data-ttu-id="6d6a6-108">對使用 Office 365 的大多數組織而言，我們可以代管信箱並處理郵件流程。</span><span class="sxs-lookup"><span data-stu-id="6d6a6-108">For most organizations that use Office 365, we host your mailboxes and take care of mail flow.</span></span> <span data-ttu-id="6d6a6-109">這是最簡單的配置，並代表 Office 365 管理所有的信箱和篩選。</span><span class="sxs-lookup"><span data-stu-id="6d6a6-109">It's the simplest configuration and means that Office 365 manages all mailboxes and filtering.</span></span> <span data-ttu-id="6d6a6-110">不過，某些組織基於業務需求而需要將所有信箱保留在內部。</span><span class="sxs-lookup"><span data-stu-id="6d6a6-110">However, some organizations have a business need to keep all their mailboxes on premises.</span></span> <span data-ttu-id="6d6a6-111">Exchange Online Protection (EOP) 可提供您這個功能，並在雲端提供防毒和反垃圾郵件處理。</span><span class="sxs-lookup"><span data-stu-id="6d6a6-111">Exchange Online Protection (EOP) enables you to do that and provides antivirus and anti-spam mail processing in the cloud.</span></span> <span data-ttu-id="6d6a6-112">如需詳細資訊並購買 EOP，請移至 [Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection)。</span><span class="sxs-lookup"><span data-stu-id="6d6a6-112">For more information and to purchase EOP, go to [Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection).</span></span>
  
<span data-ttu-id="6d6a6-p103">尋找網域管理還是目錄架構邊緣封鎖 (DBEB) 的詳細資訊？請參閱[收件者、網域和公司管理](recipient-domain-and-company-management.md)。若要深入了解所有 EOP 功能，請參閱 [Exchange Online Protection 服務說明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="6d6a6-p103">Looking for information about domain management or Directory Based Edge Blocking (DBEB)? See [Recipient, Domain, and Company Management](recipient-domain-and-company-management.md). To learn more about all EOP features, see the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="routing-email-between-office-365-and-your-own-email-servers"></a><span data-ttu-id="6d6a6-116">在 Office 365 和您自己的電子郵件伺服器之間路由電子郵件</span><span class="sxs-lookup"><span data-stu-id="6d6a6-116">Routing email between Office 365 and your own email servers</span></span>

<span data-ttu-id="6d6a6-p104">您可以設定連接器以啟用 Office 365 (包括 Exchange Online 或 EOP) 和 SMTP 型電子郵件伺服器 (如 Exchange) 之間的郵件流程。如需相關的詳細資訊，請參閱[Do I need a connector](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)？和 [Set up connectors to route mail between Office 365 and your own email servers](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)。</span><span class="sxs-lookup"><span data-stu-id="6d6a6-p104">You can configure a connector to enable mail flow between Office 365 (including Exchange Online or EOP) and an SMTP-based email server such as Exchange. For details about this, see [Do I need a connector](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)? And [Set up connectors to route mail between Office 365 and your own email servers](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).</span></span>
  
## <a name="secure-messaging-with-a-trusted-partner"></a><span data-ttu-id="6d6a6-120">與信任的合作夥伴間的安全傳訊</span><span class="sxs-lookup"><span data-stu-id="6d6a6-120">Secure messaging with a trusted partner</span></span>

<span data-ttu-id="6d6a6-121">EOP 客戶可以使用 Office 365 連接器，設定與信任合作夥伴間的安全郵件流程。</span><span class="sxs-lookup"><span data-stu-id="6d6a6-121">As an EOP customer, you can set up secure mail flow with a trusted partner by using Office 365 connectors.</span></span> <span data-ttu-id="6d6a6-122">Office 365 支援透過傳輸層安全性 (TLS) 進行安全通訊，而您可以透過 TLS 建立連接器來強制執行加密。</span><span class="sxs-lookup"><span data-stu-id="6d6a6-122">Office 365 supports secure communication through Transport Layer Security (TLS), and you can create a connector to enforce encryption via TLS.</span></span> <span data-ttu-id="6d6a6-123">[TLS](https://docs.microsoft.com/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections)是透過網際網路進行通訊提供安全性密碼編譯通訊協定。</span><span class="sxs-lookup"><span data-stu-id="6d6a6-123">[TLS](https://docs.microsoft.com/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) is a cryptographic protocol that provides security for communications over the internet.</span></span> <span data-ttu-id="6d6a6-124">您可以使用連接器，同時設定使用自我簽署或經過憑證授權單位 (CA) 驗證之憑證的強制內送和外寄 TLS。</span><span class="sxs-lookup"><span data-stu-id="6d6a6-124">By using connectors, you can configure both forced incoming and outgoing TLS using self-signed or certification authority (CA)-validated certificates.</span></span> <span data-ttu-id="6d6a6-125">您也可以套用其他安全性限制 (像是指定合作夥伴組織傳送郵件所用的網域名稱或 IP 位址範圍)。</span><span class="sxs-lookup"><span data-stu-id="6d6a6-125">You can also apply other security restrictions, such as specifying domain names or IP address ranges from which your partner organization sends mail.</span></span> 
  
<span data-ttu-id="6d6a6-126">如需詳細資訊，請參閱[對合作夥伴組織設定安全郵件流程連接器](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner)。</span><span class="sxs-lookup"><span data-stu-id="6d6a6-126">For more information, see [Set up connectors for secure mail flow with a partner organization](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).</span></span>
  
## <a name="safe-listing-a-partners-ip-address"></a><span data-ttu-id="6d6a6-127">安全列出夥伴的 IP 位址</span><span class="sxs-lookup"><span data-stu-id="6d6a6-127">Safe listing a partner's IP address</span></span>

<span data-ttu-id="6d6a6-p106">您可以將受信任夥伴的 IP 位址新增到安全清單中，以確保它們傳送給您的郵件不會受到垃圾郵件篩選功能的限制。若要這麼做，您可以使用連線篩選器的 IP 允許清單。如需詳細資訊，請參閱[設定連線篩選原則](https://go.microsoft.com/fwlink/p/?LinkID=287108)。</span><span class="sxs-lookup"><span data-stu-id="6d6a6-p106">You can add a trusted partner's IP address to a safe list to ensure that messages they send to you are not subject to spam filtering. To do this, you can use the connection filter's IP Allow list. For more information, see [Configure the connection filter policy](https://go.microsoft.com/fwlink/p/?LinkID=287108).</span></span>
  
## <a name="conditional-mail-routing"></a><span data-ttu-id="6d6a6-131">條件式郵件路由</span><span class="sxs-lookup"><span data-stu-id="6d6a6-131">Conditional mail routing</span></span>

<span data-ttu-id="6d6a6-p107">您可以設定具有傳輸規則的連接器，以根據條件將郵件路由傳送至特定站台。如需詳細資訊，請參閱[Scenario: Conditional email routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing)。</span><span class="sxs-lookup"><span data-stu-id="6d6a6-p107">You can configure a connector with a Transport rule that routes mail to a specific site, based on conditions. For more information, see [Scenario: Conditional email routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).</span></span>
  
## <a name="hybrid-mail-routing"></a><span data-ttu-id="6d6a6-134">混合郵件路由</span><span class="sxs-lookup"><span data-stu-id="6d6a6-134">Hybrid mail routing</span></span>

<span data-ttu-id="6d6a6-p108">混合的意思是部分信箱是內部部署，部分則是在雲端 (Exchange Online)。您可以從獨立 (內部) 部署移至混合部署。</span><span class="sxs-lookup"><span data-stu-id="6d6a6-p108">Hybrid means that you host a portion of your mailboxes on premises, and a portion in the cloud (Exchange Online). You can move from a standalone (on-premises) deployment to a hybrid deployment.</span></span>
  
<span data-ttu-id="6d6a6-p109">如果具有混合部署，則可以利用 EOP 保護雲端及內部部署信箱。內部部署信箱在受到 EOP 保護時需要獨立授權。如需有關混合部署中郵件路由的詳細資訊，請參閱 [Exchange 混合部署的傳輸路由](https://go.microsoft.com/fwlink/p/?LinkId=271757)。</span><span class="sxs-lookup"><span data-stu-id="6d6a6-p109">If you have a hybrid deployment, you can protect your cloud and on-premises mailboxes with EOP. Standalone licenses are required for on-premises mailboxes, when they are protected by EOP. For more information about mail routing in a hybrid deployment, see [Transport routing in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkId=271757).</span></span>
  
<span data-ttu-id="6d6a6-140">[Microsoft Exchange Server 部署助理](https://go.microsoft.com/fwlink/p/?LinkId=287036)也提供詳細的混合式部署佈建和混合式訊息傳輸指導。</span><span class="sxs-lookup"><span data-stu-id="6d6a6-140">The [Microsoft Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036) also provides detailed hybrid deployment provisioning and hybrid message transport guidance.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="6d6a6-141">功能可用性</span><span class="sxs-lookup"><span data-stu-id="6d6a6-141">Feature Availability</span></span>

<span data-ttu-id="6d6a6-142">若要檢視 Office 365 計劃、獨立選項和內部部署解決方案中的功能可用性，請參閱 [Exchange Online Protection 服務說明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="6d6a6-142">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
