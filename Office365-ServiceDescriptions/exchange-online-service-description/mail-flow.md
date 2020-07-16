---
title: 郵件流程
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-mail-flow
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 8e5267e6-d224-485b-a081-c71a1fd0c4c3
description: 對大多數的組織而言，我們會主控您的信箱並處理郵件流程。 這是最簡單的設定，並表示 Microsoft 管理所有的信箱和篩選。 不過，某些組織需要更複雜的郵件流程設定，以確保它們遵守特定法規或業務需求。 您可以在此找到這些選項。
ms.openlocfilehash: 1ada5a3199e6ae65c6aaa99873f13a4025366a8d
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132717"
---
# <a name="mail-flow"></a><span data-ttu-id="22684-106">郵件流程</span><span class="sxs-lookup"><span data-stu-id="22684-106">Mail flow</span></span>

<span data-ttu-id="22684-107">對大多數的組織而言，我們會主控您的信箱並處理郵件流程。</span><span class="sxs-lookup"><span data-stu-id="22684-107">For most organizations, we host your mailboxes and take care of mail flow.</span></span> <span data-ttu-id="22684-108">這是最簡單的設定，並表示 Microsoft 管理所有的信箱和篩選。</span><span class="sxs-lookup"><span data-stu-id="22684-108">It's the simplest configuration and means that Microsoft manages all mailboxes and filtering.</span></span> <span data-ttu-id="22684-109">不過，某些組織需要更複雜的郵件流程設定，以確保它們遵守特定法規或業務需求。</span><span class="sxs-lookup"><span data-stu-id="22684-109">However, some organizations need more complex mail flow setups to make sure that they comply with specific regulatory or business needs.</span></span> <span data-ttu-id="22684-110">您可以在此找到這些選項。</span><span class="sxs-lookup"><span data-stu-id="22684-110">You can find out about those options here.</span></span> 
  
## <a name="custom-routing-of-outbound-email"></a><span data-ttu-id="22684-111">自訂輸出電子郵件的路由傳送</span><span class="sxs-lookup"><span data-stu-id="22684-111">Custom routing of outbound email</span></span>

<span data-ttu-id="22684-112">Microsoft Exchange Online 可以透過內部部署伺服器或託管服務 (有時稱為「智慧型託管」) 路由來自組織的郵件流程。</span><span class="sxs-lookup"><span data-stu-id="22684-112">Microsoft Exchange Online can route mail flowing from your organization through an on-premises server or a hosted service (sometimes called "smart hosting").</span></span> <span data-ttu-id="22684-113">這可讓您的組織使用資料遺失防護（DLP）裝置，執行外寄電子郵件的自訂後續處理，並透過私人網路絡將電子郵件傳送給商務合作夥伴。</span><span class="sxs-lookup"><span data-stu-id="22684-113">This lets your organization to use data loss prevention (DLP) appliances, perform custom post-processing of outgoing email, and deliver email to business partners through private networks.</span></span> <span data-ttu-id="22684-114">Exchange Online 也支援地址修正功能，透過會修改位址的功能，外寄電子郵件將會透過內部部署閘道進行路由。</span><span class="sxs-lookup"><span data-stu-id="22684-114">Exchange Online also supports Address Rewrite, which routes outgoing email through an on-premises gateway that modifies the addresses.</span></span> <span data-ttu-id="22684-115">這項功能可讓您隱藏子域、將多網域組織的電子郵件顯示為單一網域，或讓夥伴轉送的電子郵件顯示為從組織內傳送。</span><span class="sxs-lookup"><span data-stu-id="22684-115">This feature lets you hide sub-domains, make email from a multi-domain organization appear as a single domain, or make partner-relayed email appear as if it were sent from inside your organization.</span></span> <span data-ttu-id="22684-116">管理員可以在 Exchange 系統管理中心 (EAC) 內設定自訂電子郵件路由。</span><span class="sxs-lookup"><span data-stu-id="22684-116">Administrators configure custom email routing within the Exchange admin center (EAC).</span></span>
  
<span data-ttu-id="22684-117">如需詳細資訊，請參閱[設定連接器以在 Microsoft 和您自己的電子郵件伺服器之間路由傳送郵件](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)。</span><span class="sxs-lookup"><span data-stu-id="22684-117">For more information, see [Set up connectors to route mail between Microsoft and your own email servers](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="22684-118">Exchange Online 可以傳送在您的組織中進出的郵件。</span><span class="sxs-lookup"><span data-stu-id="22684-118">Exchange Online can deliver mail flowing into and out of your organization.</span></span> <span data-ttu-id="22684-119">如果您的收件者網域主控于 Exchange Online 中，且 DNS MX 記錄指向 Exchange Online Protection，則來自您租使用者的郵件流程將不會透過網際網路傳送。</span><span class="sxs-lookup"><span data-stu-id="22684-119">If your recipient domain is hosted in Exchange Online with DNS MX records pointing to Exchange Online Protection, mail flow from your tenant to the recipient will not travel over the internet.</span></span>
  
## <a name="secure-messaging-with-a-trusted-partner"></a><span data-ttu-id="22684-120">與信任的合作夥伴間的安全傳訊</span><span class="sxs-lookup"><span data-stu-id="22684-120">Secure messaging with a trusted partner</span></span>

<span data-ttu-id="22684-121">做為 Exchange Online 客戶時，您可以使用 Microsoft 連接器設定安全的郵件流程與信任的合作夥伴。</span><span class="sxs-lookup"><span data-stu-id="22684-121">As an Exchange Online customer, you can set up secure mail flow with a trusted partner by using Microsoft connectors.</span></span> <span data-ttu-id="22684-122">Microsoft 會透過傳輸層安全性（TLS）來支援安全通訊，而且您可以建立連接器，透過 TLS 強制加密。</span><span class="sxs-lookup"><span data-stu-id="22684-122">Microsoft supports secure communication through Transport Layer Security (TLS), and you can create a connector to enforce encryption via TLS.</span></span> <span data-ttu-id="22684-123">[TLS](https://docs.microsoft.com/office365/securitycompliance/exchange-online-uses-tls-to-secure-email-connections)是一種加密通訊協定，可為透過網際網路的通訊提供安全性。</span><span class="sxs-lookup"><span data-stu-id="22684-123">[TLS](https://docs.microsoft.com/office365/securitycompliance/exchange-online-uses-tls-to-secure-email-connections) is a cryptographic protocol that provides security for communications over the internet.</span></span> <span data-ttu-id="22684-124">您可以使用連接器，同時設定使用自我簽署或經過憑證授權單位 (CA) 驗證之憑證的強制內送和外寄 TLS。</span><span class="sxs-lookup"><span data-stu-id="22684-124">By using connectors, you can configure both forced incoming and outgoing TLS using self-signed or certification authority (CA)-validated certificates.</span></span> <span data-ttu-id="22684-125">您也可以套用其他安全性限制 (像是指定合作夥伴組織傳送郵件所用的網域名稱或 IP 位址範圍)。</span><span class="sxs-lookup"><span data-stu-id="22684-125">You can also apply other security restrictions, such as specifying domain names or IP address ranges from which your partner organization sends mail.</span></span> 
  
<span data-ttu-id="22684-126">如需詳細資訊，請參閱＜[Set up connectors for secure mail flow with a partner organization](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner)＞。</span><span class="sxs-lookup"><span data-stu-id="22684-126">For more information, see [Set up connectors for secure mail flow with a partner organization](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="22684-127">可能需要經過 CA 驗證的憑證。</span><span class="sxs-lookup"><span data-stu-id="22684-127">A CA-validated certificate may be required.</span></span> 
  
## <a name="conditional-mail-routing"></a><span data-ttu-id="22684-128">條件式郵件路由</span><span class="sxs-lookup"><span data-stu-id="22684-128">Conditional mail routing</span></span>

<span data-ttu-id="22684-p106">您可以使用連接器和傳輸規則直接傳送郵件到特定網站。透過條件式路由，您可以根據特定條件選擇要使用的連接器。</span><span class="sxs-lookup"><span data-stu-id="22684-p106">You can direct mail to specific sites by using connectors and transport rules. With criteria-based routing, you can choose a connector based on specific conditions.</span></span>
  
<span data-ttu-id="22684-131">如需詳細資訊，請參閱＜[Scenario: Conditional mail routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing)＞。</span><span class="sxs-lookup"><span data-stu-id="22684-131">For more information, see [Scenario: Conditional mail routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).</span></span>
  
## <a name="incoming-mail-safe-list"></a><span data-ttu-id="22684-132">內送郵件安全清單</span><span class="sxs-lookup"><span data-stu-id="22684-132">Incoming mail safe list</span></span>

<span data-ttu-id="22684-p107">您可以將受信任夥伴的 IP 位址新增到安全清單中，以確保傳送給您的郵件不會被防垃圾郵件篩選功能限制。若要這麼做，您可以使用連線篩選器的 IP 允許清單。</span><span class="sxs-lookup"><span data-stu-id="22684-p107">You can add a trusted partner's IP address to a safe list to ensure that messages the partner sends to you are not subject to anti-spam filtering. To do this, you can use the connection filter's IP Allow list.</span></span>
  
<span data-ttu-id="22684-135">如需詳細資訊，請參閱＜[Configure the connection filter policy](https://docs.microsoft.com/office365/SecurityCompliance/configure-the-connection-filter-policy)＞。</span><span class="sxs-lookup"><span data-stu-id="22684-135">For more information, see [Configure the connection filter policy](https://docs.microsoft.com/office365/SecurityCompliance/configure-the-connection-filter-policy).</span></span>
  
## <a name="hybrid-email-routing"></a><span data-ttu-id="22684-136">混合電子郵件路由</span><span class="sxs-lookup"><span data-stu-id="22684-136">Hybrid email routing</span></span>

<span data-ttu-id="22684-p108">混合部署可讓組織將功能豐富的體驗，以及現有內部部署 Microsoft Exchange 組織所具有的管理控制延伸至雲端。在採用混合傳輸的情況下，任一組織中的收件者之間傳送的郵件都會使用傳輸層安全性 (TLS) 進行驗證、加密及傳輸，並對傳輸規則、日誌及反垃圾郵件原則等 Exchange 元件顯示為「內部」。您可以在 Exchange Server 中使用混合組態精靈來設定混和傳輸。</span><span class="sxs-lookup"><span data-stu-id="22684-p108">A hybrid deployment gives organizations the ability to extend the feature-rich experience and administrative control they have with their existing on-premises Microsoft Exchange organization to the cloud. With hybrid transport, messages sent between recipients in either organization are authenticated, encrypted, and transferred using Transport Layer Security (TLS), and appear as "internal" to Exchange components such as transport rules, journaling, and anti-spam policies. You configure hybrid transport by using the Hybrid Configuration Wizard in Exchange Server.</span></span>
  
<span data-ttu-id="22684-140">如需有關混合部署中郵件路由的詳細資訊，請參閱 [Exchange 混合部署的傳輸路由](https://go.microsoft.com/fwlink/p/?LinkId=271757)。</span><span class="sxs-lookup"><span data-stu-id="22684-140">For more information about mail routing in a hybrid deployment, see [Transport routing in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkId=271757).</span></span>
  
<span data-ttu-id="22684-141">[Microsoft Exchange Server 部署助理](https://go.microsoft.com/fwlink/p/?LinkId=287036)也提供詳細的混合式部署佈建和混合式訊息傳輸指導。</span><span class="sxs-lookup"><span data-stu-id="22684-141">The [Microsoft Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036) also provides detailed hybrid deployment provisioning and hybrid message transport guidance.</span></span> 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a><span data-ttu-id="22684-142">具有內部部署路由控制的共用位址空間 (MX 點至內部部署)</span><span class="sxs-lookup"><span data-stu-id="22684-142">Shared Address Space with On-Premises Routing Control (MX Points to On-Premises)</span></span>

<span data-ttu-id="22684-143">具有 On-Premises 路由控制的共用位址空間（MX 指向 On-Premises）是一種混合式部署郵件路由案例，在此案例中，您的信箱已部分主控于 Exchange Online 和部分內部部署中，而且傳入和傳出網際網路郵件流程會透過內部部署 Exchange 組織進行路由傳送。</span><span class="sxs-lookup"><span data-stu-id="22684-143">Shared Address Space with On-Premises Routing Control (MX Points to On-Premises) is a hybrid deployment mail-routing scenario in which your mailboxes are hosted partially in Exchange Online and partially on-premises, and incoming and outgoing internet mail flow is routed through the on-premises Exchange organization.</span></span> <span data-ttu-id="22684-144">這種案例也稱為集中式郵件傳輸。</span><span class="sxs-lookup"><span data-stu-id="22684-144">This scenario is also called centralized mail transport.</span></span> <span data-ttu-id="22684-145">在此案例中，會使用 EOP 來布建 Exchange Online，而且傳入的網際網路郵件會路由傳送至您的內部部署郵件伺服器，然後才會路由傳送至 EOP，最後傳送至 Exchange Online 中主控的信箱。</span><span class="sxs-lookup"><span data-stu-id="22684-145">In this scenario, Exchange Online is provisioned with EOP and incoming internet mail is routed to your on-premises mail server before being routed to EOP and finally to mailboxes hosted in Exchange Online.</span></span> <span data-ttu-id="22684-146">此外，來自 Exchange Online 信箱的外寄郵件會透過內部部署 Exchange 組織進行路由，以使郵件傳送至外部收件者。</span><span class="sxs-lookup"><span data-stu-id="22684-146">Additionally, outgoing mail from Exchange Online mailboxes is routed through the on-premises Exchange organization for messages sent to external recipients.</span></span> <span data-ttu-id="22684-147">您可以透過這個設定，將單一 SMTP 網域命名空間使用於內部部署 Exchange 組織和 Exchange Online 組織中的所有信箱。</span><span class="sxs-lookup"><span data-stu-id="22684-147">With this configuration, you can use a single SMTP domain namespace for all mailboxes in both your on-premises Exchange organization and your Exchange Online organization.</span></span> 
  
<span data-ttu-id="22684-148">如需有關混合部署中傳輸選項的詳細資訊，請參閱 [Exchange 混合部署的傳輸選項](https://go.microsoft.com/fwlink/p/?LinkID=271758)。</span><span class="sxs-lookup"><span data-stu-id="22684-148">For more information about transport options in a hybrid deployment, see [Transport options in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkID=271758).</span></span>
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a><span data-ttu-id="22684-149">無內部部署路由控制的共用位址空間 (MX 點至 EOP)</span><span class="sxs-lookup"><span data-stu-id="22684-149">Shared Address Space without On-Premises Routing Control (MX Points to EOP)</span></span>

<span data-ttu-id="22684-150">無內部部署路由控制的共用位址空間 (MX 指向 EOP) 是一種混合郵件路由案例，其中信箱部分託管於雲端 (使用 Exchange Online)，部分位於內部部署，而 MX 記錄會指向 EOP。</span><span class="sxs-lookup"><span data-stu-id="22684-150">Shared Address Space without On-Premises Routing Control (MX Points to EOP) is a hybrid mail-routing scenario in which your mailboxes are hosted partially in the cloud using Exchange Online and partially on-premises, and your MX record points to EOP.</span></span> <span data-ttu-id="22684-151">當您使用 Microsoft 來裝載某些組織的信箱，且您想要 EOP 保護您的內部部署和雲端信箱時，此案例適用。</span><span class="sxs-lookup"><span data-stu-id="22684-151">This scenario is appropriate when you use Microsoft to host some of your organization's mailboxes and you want EOP to protect both your on-premises and cloud mailboxes.</span></span> <span data-ttu-id="22684-152">在此案例中，傳送至您組織中收件者的郵件一開始會透過 EOP 進行路由 (會在此處進行垃圾郵件和原則篩選作業)，然後再送達您內部部署信箱和雲端信箱。</span><span class="sxs-lookup"><span data-stu-id="22684-152">In this scenario, mail sent to recipients within your organization is initially routed through EOP, where spam and policy filtering occurs, before it reaches your on-premises mailboxes and cloud mailboxes.</span></span> 
  
<span data-ttu-id="22684-153">如需有關混合部署中傳輸選項的詳細資訊，請參閱 [Exchange 混合部署的傳輸選項](https://go.microsoft.com/fwlink/p/?LinkID=271758)。</span><span class="sxs-lookup"><span data-stu-id="22684-153">For more information about transport options in a hybrid deployment, see [Transport options in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkID=271758).</span></span>
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a><span data-ttu-id="22684-154">使用混合組態精靈進行部署的疑難排解</span><span class="sxs-lookup"><span data-stu-id="22684-154">Troubleshooting a deployment with the Hybrid Configuration Wizard</span></span>

<span data-ttu-id="22684-p111">使用混合組態精靈在 Microsoft Exchange Server 中設定混合部署，可大幅降低混合部署發生問題的可能性。不過，有一些在混合組態精靈的範圍以外的一般區域可能在設定錯誤的情況下，於混合部署中發生問題。這些包括適當的 Client Access Server 設定以及適當的憑證安裝和設定。</span><span class="sxs-lookup"><span data-stu-id="22684-p111">Using the Hybrid Configuration Wizard to configure a hybrid deployment in Microsoft Exchange Server greatly minimizes the potential that the hybrid deployment will experience problems. However, there are some typical areas outside the scope of the Hybrid Configuration Wizard that, if misconfigured, may present problems in a hybrid deployment. These include proper Client Access server configuration and proper certificate installation and configuration.</span></span>
  
<span data-ttu-id="22684-158">如需有關使用混合組態精靈對部署進行疑難排解的詳細資訊，請參閱[疑難排解混合部署](https://go.microsoft.com/fwlink/p/?LinkId=271040)。</span><span class="sxs-lookup"><span data-stu-id="22684-158">For more information about troubleshooting a deployment with the Hybrid Configuration Wizard, see [Troubleshoot a hybrid deployment](https://go.microsoft.com/fwlink/p/?LinkId=271040).</span></span>
  
### <a name="managing-a-hybrid-configuration"></a><span data-ttu-id="22684-159">管理混合組態</span><span class="sxs-lookup"><span data-stu-id="22684-159">Managing a hybrid configuration</span></span>

<span data-ttu-id="22684-p112">您可以在混合組態精靈中變更設定，以修改現有混合組態。案例包括停用集中式運輸或停用安全郵件傳輸。</span><span class="sxs-lookup"><span data-stu-id="22684-p112">You can modify an existing hybrid configuration by changing settings in the Hybrid Configuration Wizard. Scenarios include disabling centralized transport or disabling secure mail transport.</span></span>
  
<span data-ttu-id="22684-162">如需有關管理混合部署設定的詳細資訊，請參閱[管理混合部署](https://go.microsoft.com/fwlink/p/?LinkId=271044)。</span><span class="sxs-lookup"><span data-stu-id="22684-162">For more information about managing a hybrid deployment configuration, see [Manage a hybrid deployment](https://go.microsoft.com/fwlink/p/?LinkId=271044).</span></span>
  
### <a name="hybrid-deployment-requirements"></a><span data-ttu-id="22684-163">混合部署需求</span><span class="sxs-lookup"><span data-stu-id="22684-163">Hybrid deployment requirements</span></span>

<span data-ttu-id="22684-164">如需有關混合部署需求的詳細資訊，請參閱[混合部署必要條件](https://go.microsoft.com/fwlink/p/?LinkId=271759)。</span><span class="sxs-lookup"><span data-stu-id="22684-164">For more information about hybrid deployment requirements, see [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/p/?LinkId=271759).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="22684-165">在某些混合組態中，您可能需要為內部部署信箱購買 Exchange Online Protection 授權。</span><span class="sxs-lookup"><span data-stu-id="22684-165">In some hybrid configurations, you may need to purchase Exchange Online Protection licenses for your on-premises mailboxes.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="22684-166">功能可用性</span><span class="sxs-lookup"><span data-stu-id="22684-166">Feature availability</span></span>

<span data-ttu-id="22684-167">若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online 服務說明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="22684-167">To view feature availability across plans, standalone options, and on-premises solutions, see the [Exchange Online service description](exchange-online-service-description.md).</span></span>
  