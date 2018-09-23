---
title: 郵件流程
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-mail-flow
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 8e5267e6-d224-485b-a081-c71a1fd0c4c3
description: '對使用 Office 365 的大多數組織而言，我們可以代管信箱並處理郵件流程。這是最簡單的配置，並代表 Office 365 管理所有的信箱和篩選。不過，某些組織需要更複雜的郵件流程設定，以確保它們遵守特定法規或業務需求。您可以在此找到這些選項。 '
ms.openlocfilehash: 3decc04fb4c426e161541c1d24480cc0344b0a00
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035337"
---
# <a name="mail-flow"></a><span data-ttu-id="6b021-106">郵件流程</span><span class="sxs-lookup"><span data-stu-id="6b021-106">Mail Flow</span></span>

<span data-ttu-id="6b021-p102">對使用 Office 365 的大多數組織而言，我們可以代管信箱並處理郵件流程。這是最簡單的配置，並代表 Office 365 管理所有的信箱和篩選。不過，某些組織需要更複雜的郵件流程設定，以確保它們遵守特定法規或業務需求。您可以在此找到這些選項。 </span><span class="sxs-lookup"><span data-stu-id="6b021-p102">For most organizations using Office 365, we host your mailboxes and take care of mail flow. It's the simplest configuration and means that Office 365 manages all mailboxes and filtering. However, some organizations need more complex mail flow setups to make sure that they comply with specific regulatory or business needs. You can find out about those options here.</span></span> 
  
## <a name="custom-routing-of-outbound-email"></a><span data-ttu-id="6b021-111">自訂輸出電子郵件的路由傳送</span><span class="sxs-lookup"><span data-stu-id="6b021-111">Custom routing of outbound email</span></span>

<span data-ttu-id="6b021-p103">Microsoft Exchange Online 可以透過內部部署伺服器或託管服務 (有時稱為「智慧型託管」) 路由來自組織的郵件流程。這可以讓組織使用資料遺失防護 (DLP) 應用裝置、執行自訂的外寄電子郵件後續處理，以及透過私人網路將電子郵件傳送給業務合作夥伴。Exchange Online 也支援地址修正功能，透過會修改位址的功能，外寄電子郵件將會透過內部部署閘道進行路由。此功能可讓您隱藏子網域，使來自多網域組織的電子郵件顯示為單一網域，或是使合作夥伴轉送的電子郵件顯示為寄自組織內部。管理員可以在 Exchange 系統管理中心 (EAC) 內設定自訂電子郵件路由。</span><span class="sxs-lookup"><span data-stu-id="6b021-p103">Microsoft Exchange Online can route mail flowing from your organization through an on-premises server or a hosted service (sometimes called "smart hosting"). This enables your organization to use data loss prevention (DLP) appliances, perform custom post-processing of outgoing email, and deliver email to business partners through private networks. Exchange Online also supports Address Rewrite, which routes outgoing email through an on-premises gateway that modifies the addresses. This feature enables you to hide sub-domains, make email from a multi-domain organization appear as a single domain, or make partner-relayed email appear as if it were sent from inside your organization. Administrators configure custom email routing within the Exchange admin center (EAC).</span></span>
  
<span data-ttu-id="6b021-117">如需詳細資訊，請參閱＜[Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx)＞。</span><span class="sxs-lookup"><span data-stu-id="6b021-117">For more information, see [Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="6b021-118">Exchange Online 可以傳送在您的組織中進出的郵件。</span><span class="sxs-lookup"><span data-stu-id="6b021-118">Exchange Online can deliver mail flowing into and out of your organization.</span></span> 
  
## <a name="secure-messaging-with-a-trusted-partner"></a><span data-ttu-id="6b021-119">與信任的合作夥伴間的安全傳訊</span><span class="sxs-lookup"><span data-stu-id="6b021-119">Secure messaging with a trusted partner</span></span>

<span data-ttu-id="6b021-p104">Exchange Online 客戶可以使用 Office 365 連接器，設定與信任合作夥伴間的安全郵件流程。Office 365 支援透過傳輸層安全性 (TLS) 進行安全通訊，而您可以透過 TLS 建立連接器來強制執行加密。[TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) 這個密碼編譯通訊協定能提供網路通訊的安全性。您可以使用連接器，同時設定使用自我簽署或經過憑證授權單位 (CA) 驗證之憑證的強制內送和外寄 TLS。您也可以套用其他安全性限制 (像是指定合作夥伴組織傳送郵件所用的網域名稱或 IP 位址範圍)。</span><span class="sxs-lookup"><span data-stu-id="6b021-p104">As an Exchange Online customer, you can set up secure mail flow with a trusted partner by using Office 365 connectors. Office 365 supports secure communication through Transport Layer Security (TLS), and you can create a connector to enforce encryption via TLS. [TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) is a cryptographic protocol that provides security for communications over the Internet. By using connectors, you can configure both forced incoming and outgoing TLS using self-signed or certification authority (CA)-validated certificates. You can also apply other security restrictions, such as specifying domain names or IP address ranges from which your partner organization sends mail.</span></span> 
  
<span data-ttu-id="6b021-125">如需詳細資訊，請參閱＜[Set up connectors for secure mail flow with a partner organization](http://technet.microsoft.com/library/1ce4d6a4-41ba-4d1e-9ca9-e826252c1041.aspx)＞。</span><span class="sxs-lookup"><span data-stu-id="6b021-125">For more information, see [Set up connectors for secure mail flow with a partner organization](http://technet.microsoft.com/library/1ce4d6a4-41ba-4d1e-9ca9-e826252c1041.aspx).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="6b021-126">可能需要經過 CA 驗證的憑證。</span><span class="sxs-lookup"><span data-stu-id="6b021-126">A CA-validated certificate may be required.</span></span> 
  
## <a name="conditional-mail-routing"></a><span data-ttu-id="6b021-127">條件式郵件路由</span><span class="sxs-lookup"><span data-stu-id="6b021-127">Conditional mail routing</span></span>

<span data-ttu-id="6b021-p105">您可以使用連接器和傳輸規則直接傳送郵件到特定網站。透過條件式路由，您可以根據特定條件選擇要使用的連接器。</span><span class="sxs-lookup"><span data-stu-id="6b021-p105">You can direct mail to specific sites by using connectors and transport rules. With criteria-based routing, you can choose a connector based on specific conditions.</span></span>
  
<span data-ttu-id="6b021-130">如需詳細資訊，請參閱＜[Scenario: Conditional mail routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx)＞。</span><span class="sxs-lookup"><span data-stu-id="6b021-130">For more information, see [Scenario: Conditional mail routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx).</span></span>
  
## <a name="incoming-mail-safe-list"></a><span data-ttu-id="6b021-131">內送郵件安全清單</span><span class="sxs-lookup"><span data-stu-id="6b021-131">Incoming mail safe list</span></span>

<span data-ttu-id="6b021-p106">您可以將受信任夥伴的 IP 位址新增到安全清單中，以確保傳送給您的郵件不會被防垃圾郵件篩選功能限制。若要這麼做，您可以使用連線篩選器的 IP 允許清單。</span><span class="sxs-lookup"><span data-stu-id="6b021-p106">You can add a trusted partner's IP address to a safe list to ensure that messages the partner sends to you are not subject to anti-spam filtering. To do this, you can use the connection filter's IP Allow list.</span></span>
  
<span data-ttu-id="6b021-134">如需詳細資訊，請參閱＜[Configure the connection filter policy](http://technet.microsoft.com/library/6ae78c12-7bbe-44fa-ab13-c3768387d0e3.aspx)＞。</span><span class="sxs-lookup"><span data-stu-id="6b021-134">For more information, see [Configure the connection filter policy](http://technet.microsoft.com/library/6ae78c12-7bbe-44fa-ab13-c3768387d0e3.aspx).</span></span>
  
## <a name="hybrid-email-routing"></a><span data-ttu-id="6b021-135">混合電子郵件路由</span><span class="sxs-lookup"><span data-stu-id="6b021-135">Hybrid email routing</span></span>

<span data-ttu-id="6b021-p107">混合部署可讓組織將功能豐富的體驗，以及現有內部部署 Microsoft Exchange 組織所具有的管理控制延伸至雲端。在採用混合傳輸的情況下，任一組織中的收件者之間傳送的郵件都會使用傳輸層安全性 (TLS) 進行驗證、加密及傳輸，並對傳輸規則、日誌及反垃圾郵件原則等 Exchange 元件顯示為「內部」。您可以在 Exchange Server 中使用混合組態精靈來設定混和傳輸。</span><span class="sxs-lookup"><span data-stu-id="6b021-p107">A hybrid deployment gives organizations the ability to extend the feature-rich experience and administrative control they have with their existing on-premises Microsoft Exchange organization to the cloud. With hybrid transport, messages sent between recipients in either organization are authenticated, encrypted, and transferred using Transport Layer Security (TLS), and appear as "internal" to Exchange components such as transport rules, journaling, and anti-spam policies. You configure hybrid transport by using the Hybrid Configuration Wizard in Exchange Server.</span></span>
  
<span data-ttu-id="6b021-139">如需有關混合部署中郵件路由的詳細資訊，請參閱 [Exchange 混合部署的傳輸路由](https://go.microsoft.com/fwlink/p/?LinkId=271757)。</span><span class="sxs-lookup"><span data-stu-id="6b021-139">For more information about mail routing in a hybrid deployment, see [Transport routing in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkId=271757).</span></span>
  
<span data-ttu-id="6b021-140">[Microsoft Exchange Server 部署助理](https://go.microsoft.com/fwlink/p/?LinkId=287036)也提供詳細的混合式部署佈建和混合式訊息傳輸指導。</span><span class="sxs-lookup"><span data-stu-id="6b021-140">The [Microsoft Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036) also provides detailed hybrid deployment provisioning and hybrid message transport guidance.</span></span> 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a><span data-ttu-id="6b021-141">具有內部部署路由控制的共用位址空間 (MX 點至內部部署)</span><span class="sxs-lookup"><span data-stu-id="6b021-141">Shared Address Space with On-Premises Routing Control (MX Points to On-Premises)</span></span>

<span data-ttu-id="6b021-p108">具有內部部署路由控制的共用位址空間 (MX 點至內部部署) 是一種混合環境的郵件路由案例，其中您的信箱會部分託管於 Exchange Online，部分位於內部部署，而內送和外寄網際網路郵件流程會透過內部部署 Exchange 組織進行路由。這種案例也稱為集中式郵件傳輸。在此案例中，Exchange Online 會隨 EOP 一起佈建，內送網際網路郵件則會路由至內部部署郵件伺服器，然後再路由至 EOP，最後再送至託管於 Exchange Online 的信箱內。此外，來自 Exchange Online 信箱的外寄郵件會透過內部部署 Exchange 組織進行路由，以使郵件傳送至外部收件者。您可以透過這個設定，將單一 SMTP 網域命名空間使用於內部部署 Exchange 組織和 Exchange Online 組織中的所有信箱。</span><span class="sxs-lookup"><span data-stu-id="6b021-p108">Shared Address Space with On-Premises Routing Control (MX Points to On-Premises) is a hybrid deployment mail-routing scenario in which your mailboxes are hosted partially in Exchange Online and partially on-premises, and incoming and outgoing Internet mail flow is routed through the on-premises Exchange organization. This scenario is also called centralized mail transport. In this scenario, Exchange Online is provisioned with EOP and incoming Internet mail is routed to your on-premises mail server before being routed to EOP and finally to mailboxes hosted in Exchange Online. Additionally, outgoing mail from Exchange Online mailboxes is routed through the on-premises Exchange organization for messages sent to external recipients. With this configuration, you can use a single SMTP domain namespace for all mailboxes in both your on-premises Exchange organization and your Exchange Online organization.</span></span> 
  
<span data-ttu-id="6b021-147">如需有關混合部署中傳輸選項的詳細資訊，請參閱 [Exchange 混合部署的傳輸選項](https://go.microsoft.com/fwlink/p/?LinkID=271758)。</span><span class="sxs-lookup"><span data-stu-id="6b021-147">For more information about transport options in a hybrid deployment, see [Transport options in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkID=271758).</span></span>
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a><span data-ttu-id="6b021-148">無內部部署路由控制的共用位址空間 (MX 點至 EOP)</span><span class="sxs-lookup"><span data-stu-id="6b021-148">Shared Address Space without On-Premises Routing Control (MX Points to EOP)</span></span>

<span data-ttu-id="6b021-p109">無內部部署路由控制的共用位址空間 (MX 指向 EOP) 是一種混合郵件路由案例，其中信箱部分託管於雲端 (使用 Exchange Online)，部分位於內部部署，而 MX 記錄會指向 EOP。當您使用 Office 365 服務託管組織的部分信箱，並且希望使用 EOP 同時保護內部部署和雲端信箱時，此案例即適用。在此案例中，傳送至您組織中收件者的郵件一開始會透過 EOP 進行路由 (會在此處進行垃圾郵件和原則篩選作業)，然後再送達您內部部署信箱和雲端信箱。</span><span class="sxs-lookup"><span data-stu-id="6b021-p109">Shared Address Space without On-Premises Routing Control (MX Points to EOP) is a hybrid mail-routing scenario in which your mailboxes are hosted partially in the cloud using Exchange Online and partially on-premises, and your MX record points to EOP. This scenario is appropriate when you use the Office 365 service to host some of your organization's mailboxes and you want EOP to protect both your on-premises and cloud mailboxes. In this scenario, mail sent to recipients within your organization is initially routed through EOP, where spam and policy filtering occurs, before it reaches your on-premises mailboxes and cloud mailboxes.</span></span> 
  
<span data-ttu-id="6b021-152">如需有關混合部署中傳輸選項的詳細資訊，請參閱 [Exchange 混合部署的傳輸選項](https://go.microsoft.com/fwlink/p/?LinkID=271758)。</span><span class="sxs-lookup"><span data-stu-id="6b021-152">For more information about transport options in a hybrid deployment, see [Transport options in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkID=271758).</span></span>
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a><span data-ttu-id="6b021-153">使用混合組態精靈進行部署的疑難排解</span><span class="sxs-lookup"><span data-stu-id="6b021-153">Troubleshooting a deployment with the Hybrid Configuration Wizard</span></span>

<span data-ttu-id="6b021-p110">使用混合組態精靈在 Microsoft Exchange Server 中設定混合部署，可大幅降低混合部署發生問題的可能性。不過，有一些在混合組態精靈的範圍以外的一般區域可能在設定錯誤的情況下，於混合部署中發生問題。這些包括適當的 Client Access Server 設定以及適當的憑證安裝和設定。</span><span class="sxs-lookup"><span data-stu-id="6b021-p110">Using the Hybrid Configuration Wizard to configure a hybrid deployment in Microsoft Exchange Server greatly minimizes the potential that the hybrid deployment will experience problems. However, there are some typical areas outside the scope of the Hybrid Configuration Wizard that, if misconfigured, may present problems in a hybrid deployment. These include proper Client Access server configuration and proper certificate installation and configuration.</span></span>
  
<span data-ttu-id="6b021-157">如需有關使用混合組態精靈對部署進行疑難排解的詳細資訊，請參閱[疑難排解混合部署](https://go.microsoft.com/fwlink/p/?LinkId=271040)。</span><span class="sxs-lookup"><span data-stu-id="6b021-157">For more information about troubleshooting a deployment with the Hybrid Configuration Wizard, see [Troubleshoot a hybrid deployment](https://go.microsoft.com/fwlink/p/?LinkId=271040).</span></span>
  
### <a name="managing-a-hybrid-configuration"></a><span data-ttu-id="6b021-158">管理混合組態</span><span class="sxs-lookup"><span data-stu-id="6b021-158">Managing a hybrid configuration</span></span>

<span data-ttu-id="6b021-p111">您可以在混合組態精靈中變更設定，以修改現有混合組態。案例包括停用集中式運輸或停用安全郵件傳輸。</span><span class="sxs-lookup"><span data-stu-id="6b021-p111">You can modify an existing hybrid configuration by changing settings in the Hybrid Configuration Wizard. Scenarios include disabling centralized transport or disabling secure mail transport.</span></span>
  
<span data-ttu-id="6b021-161">如需有關管理混合部署設定的詳細資訊，請參閱[管理混合部署](https://go.microsoft.com/fwlink/p/?LinkId=271044)。</span><span class="sxs-lookup"><span data-stu-id="6b021-161">For more information about managing a hybrid deployment configuration, see [Manage a hybrid deployment](https://go.microsoft.com/fwlink/p/?LinkId=271044).</span></span>
  
### <a name="hybrid-deployment-requirements"></a><span data-ttu-id="6b021-162">混合部署需求</span><span class="sxs-lookup"><span data-stu-id="6b021-162">Hybrid deployment requirements</span></span>

<span data-ttu-id="6b021-163">如需有關混合部署需求的詳細資訊，請參閱[混合部署必要條件](https://go.microsoft.com/fwlink/p/?LinkId=271759)。</span><span class="sxs-lookup"><span data-stu-id="6b021-163">For more information about hybrid deployment requirements, see [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/p/?LinkId=271759).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="6b021-164">在某些混合組態中，您可能需要為內部部署信箱購買 Exchange Online Protection 授權。</span><span class="sxs-lookup"><span data-stu-id="6b021-164">In some hybrid configurations, you may need to purchase Exchange Online Protection licenses for your on-premises mailboxes.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="6b021-165">功能可用性</span><span class="sxs-lookup"><span data-stu-id="6b021-165">Feature Availability</span></span>

<span data-ttu-id="6b021-166">若要檢視 Office 365 方案、獨立選項和內部部署解決方案中的功能可用性，請參閱 [Exchange Online 服務說明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="6b021-166">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see the [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

