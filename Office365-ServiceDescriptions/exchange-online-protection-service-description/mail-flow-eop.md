---
title: 郵件流程[EOP]
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: 對使用 Office 365 的大多數組織而言，我們可以代管信箱並處理郵件流程。 這是最簡單的配置，並代表 Office 365 管理所有的信箱和篩選。 不過，某些組織基於業務需求而需要將所有信箱保留在內部。 Exchange Online Protection (EOP) 可提供您這個功能，並在雲端提供防毒和反垃圾郵件處理。 如需詳細資訊並購買 EOP，請移至 Exchange Online Protection。
ms.openlocfilehash: 0e9e5fffaa88b2ec654cb90dc5d432875336328e
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/07/2019
ms.locfileid: "30467570"
---
# <a name="mail-floweop"></a><span data-ttu-id="522b2-107">郵件流程[EOP]</span><span class="sxs-lookup"><span data-stu-id="522b2-107">Mail Flow[EOP]</span></span>

<span data-ttu-id="522b2-108">對使用 Office 365 的大多數組織而言，我們可以代管信箱並處理郵件流程。</span><span class="sxs-lookup"><span data-stu-id="522b2-108">For most organizations that use Office 365, we host your mailboxes and take care of mail flow.</span></span> <span data-ttu-id="522b2-109">這是最簡單的配置，並代表 Office 365 管理所有的信箱和篩選。</span><span class="sxs-lookup"><span data-stu-id="522b2-109">It's the simplest configuration and means that Office 365 manages all mailboxes and filtering.</span></span> <span data-ttu-id="522b2-110">不過，某些組織基於業務需求而需要將所有信箱保留在內部。</span><span class="sxs-lookup"><span data-stu-id="522b2-110">However, some organizations have a business need to keep all their mailboxes on premises.</span></span> <span data-ttu-id="522b2-111">Exchange Online Protection (EOP) 可提供您這個功能，並在雲端提供防毒和反垃圾郵件處理。</span><span class="sxs-lookup"><span data-stu-id="522b2-111">Exchange Online Protection (EOP) enables you to do that and provides antivirus and anti-spam mail processing in the cloud.</span></span> <span data-ttu-id="522b2-112">如需詳細資訊並購買 EOP，請移至 [Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection)。</span><span class="sxs-lookup"><span data-stu-id="522b2-112">For more information and to purchase EOP, go to [Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection).</span></span>
  
<span data-ttu-id="522b2-p103">尋找網域管理還是目錄架構邊緣封鎖 (DBEB) 的詳細資訊？請參閱[收件者、網域和公司管理](recipient-domain-and-company-management.md)。若要深入了解所有 EOP 功能，請參閱 [Exchange Online Protection 服務說明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="522b2-p103">Looking for information about domain management or Directory Based Edge Blocking (DBEB)? See [Recipient, Domain, and Company Management](recipient-domain-and-company-management.md). To learn more about all EOP features, see the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="routing-email-between-office-365-and-your-own-email-servers"></a><span data-ttu-id="522b2-116">在 Office 365 和您自己的電子郵件伺服器之間路由電子郵件</span><span class="sxs-lookup"><span data-stu-id="522b2-116">Routing email between Office 365 and your own email servers</span></span>
<span data-ttu-id="522b2-117"><a name="BKMK_outboundmailrouting"> </a></span><span class="sxs-lookup"><span data-stu-id="522b2-117"></span></span>

<span data-ttu-id="522b2-p104">您可以設定連接器以啟用 Office 365 (包括 Exchange Online 或 EOP) 和 SMTP 型電子郵件伺服器 (如 Exchange) 之間的郵件流程。如需相關的詳細資訊，請參閱[Do I need a connector](http://technet.microsoft.com/library/16731ae9-c909-49dd-bffc-a46e6151fc29.aspx)？和 [Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx)。</span><span class="sxs-lookup"><span data-stu-id="522b2-p104">You can configure a connector to enable mail flow between Office 365 (including Exchange Online or EOP) and an SMTP-based email server such as Exchange. For details about this, see [Do I need a connector](http://technet.microsoft.com/library/16731ae9-c909-49dd-bffc-a46e6151fc29.aspx)? And [Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx).</span></span>
  
## <a name="secure-messaging-with-a-trusted-partner"></a><span data-ttu-id="522b2-121">與信任的合作夥伴間的安全傳訊</span><span class="sxs-lookup"><span data-stu-id="522b2-121">Secure messaging with a trusted partner</span></span>
<span data-ttu-id="522b2-122"><a name="BKMK_securemessagingwithatrustedpartner"> </a></span><span class="sxs-lookup"><span data-stu-id="522b2-122"></span></span>

<span data-ttu-id="522b2-p105">EOP 客戶可以使用 Office 365 連接器，設定與信任合作夥伴間的安全郵件流程。Office 365 支援透過傳輸層安全性 (TLS) 進行安全通訊，而您可以透過 TLS 建立連接器來強制執行加密。[TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) 這個密碼編譯通訊協定能提供網路通訊的安全性。您可以使用連接器，同時設定使用自我簽署或經過憑證授權單位 (CA) 驗證之憑證的強制內送和外寄 TLS。您也可以套用其他安全性限制 (像是指定合作夥伴組織傳送郵件所用的網域名稱或 IP 位址範圍)。</span><span class="sxs-lookup"><span data-stu-id="522b2-p105">As an EOP customer, you can set up secure mail flow with a trusted partner by using Office 365 connectors. Office 365 supports secure communication through Transport Layer Security (TLS), and you can create a connector to enforce encryption via TLS. [TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) is a cryptographic protocol that provides security for communications over the Internet. By using connectors, you can configure both forced incoming and outgoing TLS using self-signed or certification authority (CA)-validated certificates. You can also apply other security restrictions, such as specifying domain names or IP address ranges from which your partner organization sends mail.</span></span> 
  
<span data-ttu-id="522b2-128">如需詳細資訊，請參閱[對合作夥伴組織設定安全郵件流程連接器](https://technet.microsoft.com/en-us/library/dn751021%28v=exchg.150%29.aspx)。</span><span class="sxs-lookup"><span data-stu-id="522b2-128">For more information, see [Set up connectors for secure mail flow with a partner organization](https://technet.microsoft.com/en-us/library/dn751021%28v=exchg.150%29.aspx).</span></span>
  
## <a name="safe-listing-a-partners-ip-address"></a><span data-ttu-id="522b2-129">安全列出夥伴的 IP 位址</span><span class="sxs-lookup"><span data-stu-id="522b2-129">Safe listing a partner's IP address</span></span>
<span data-ttu-id="522b2-130"><a name="BKMK_safelistingapartnersipaddress"> </a></span><span class="sxs-lookup"><span data-stu-id="522b2-130"></span></span>

<span data-ttu-id="522b2-p106">您可以將受信任夥伴的 IP 位址新增到安全清單中，以確保它們傳送給您的郵件不會受到垃圾郵件篩選功能的限制。若要這麼做，您可以使用連線篩選器的 IP 允許清單。如需詳細資訊，請參閱[設定連線篩選原則](https://go.microsoft.com/fwlink/p/?LinkID=287108)。</span><span class="sxs-lookup"><span data-stu-id="522b2-p106">You can add a trusted partner's IP address to a safe list to ensure that messages they send to you are not subject to spam filtering. To do this, you can use the connection filter's IP Allow list. For more information, see [Configure the connection filter policy](https://go.microsoft.com/fwlink/p/?LinkID=287108).</span></span>
  
## <a name="conditional-mail-routing"></a><span data-ttu-id="522b2-134">條件式郵件路由</span><span class="sxs-lookup"><span data-stu-id="522b2-134">Conditional mail routing</span></span>
<span data-ttu-id="522b2-135"><a name="BKMK_conditionalmailrouting"> </a></span><span class="sxs-lookup"><span data-stu-id="522b2-135"></span></span>

<span data-ttu-id="522b2-p107">您可以設定具有傳輸規則的連接器，以根據條件將郵件路由傳送至特定站台。如需詳細資訊，請參閱[Scenario: Conditional email routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx)。</span><span class="sxs-lookup"><span data-stu-id="522b2-p107">You can configure a connector with a Transport rule that routes mail to a specific site, based on conditions. For more information, see [Scenario: Conditional email routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx).</span></span>
  
## <a name="hybrid-mail-routing"></a><span data-ttu-id="522b2-138">混合郵件路由</span><span class="sxs-lookup"><span data-stu-id="522b2-138">Hybrid mail routing</span></span>
<span data-ttu-id="522b2-139"><a name="BKMK_hybridmailrouting"> </a></span><span class="sxs-lookup"><span data-stu-id="522b2-139"></span></span>

<span data-ttu-id="522b2-p108">混合的意思是部分信箱是內部部署，部分則是在雲端 (Exchange Online)。您可以從獨立 (內部) 部署移至混合部署。</span><span class="sxs-lookup"><span data-stu-id="522b2-p108">Hybrid means that you host a portion of your mailboxes on premises, and a portion in the cloud (Exchange Online). You can move from a standalone (on-premises) deployment to a hybrid deployment.</span></span>
  
<span data-ttu-id="522b2-p109">如果具有混合部署，則可以利用 EOP 保護雲端及內部部署信箱。內部部署信箱在受到 EOP 保護時需要獨立授權。如需有關混合部署中郵件路由的詳細資訊，請參閱 [Exchange 混合部署的傳輸路由](https://go.microsoft.com/fwlink/p/?LinkId=271757)。</span><span class="sxs-lookup"><span data-stu-id="522b2-p109">If you have a hybrid deployment, you can protect your cloud and on-premises mailboxes with EOP. Standalone licenses are required for on-premises mailboxes, when they are protected by EOP. For more information about mail routing in a hybrid deployment, see [Transport routing in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkId=271757).</span></span>
  
<span data-ttu-id="522b2-145">[Microsoft Exchange Server 部署助理](https://go.microsoft.com/fwlink/p/?LinkId=287036)也提供詳細的混合式部署佈建和混合式訊息傳輸指導。</span><span class="sxs-lookup"><span data-stu-id="522b2-145">The [Microsoft Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036) also provides detailed hybrid deployment provisioning and hybrid message transport guidance.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="522b2-146">功能可用性</span><span class="sxs-lookup"><span data-stu-id="522b2-146">Feature Availability</span></span>
<span data-ttu-id="522b2-147"><a name="BKMK_hybridmailrouting"> </a></span><span class="sxs-lookup"><span data-stu-id="522b2-147"></span></span>

<span data-ttu-id="522b2-148">若要檢視 Office 365 計劃、獨立選項和內部部署解決方案中的功能可用性，請參閱 [Exchange Online Protection 服務說明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="522b2-148">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  

