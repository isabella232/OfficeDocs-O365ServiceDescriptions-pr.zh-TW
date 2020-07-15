---
title: 網路功能
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft 支援下列網路功能。
ms.openlocfilehash: 0f0554bdd907a6f0a37299dc3e38e5f778e7187e
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132327"
---
# <a name="networking"></a><span data-ttu-id="080db-103">網路功能</span><span class="sxs-lookup"><span data-stu-id="080db-103">Networking</span></span>

<span data-ttu-id="080db-104">Microsoft 支援下列網路功能。</span><span class="sxs-lookup"><span data-stu-id="080db-104">Microsoft supports the following networking features.</span></span>
  
## <a name="ports-protocols-and-ip-addresses"></a><span data-ttu-id="080db-105">連接埠、通訊協定和 IP 位址</span><span class="sxs-lookup"><span data-stu-id="080db-105">Ports, protocols, and IP addresses</span></span>

<span data-ttu-id="080db-106">Microsoft 使用 IPv4 和 IPv6 位址。</span><span class="sxs-lookup"><span data-stu-id="080db-106">Microsoft uses IPv4 and IPv6 addresses.</span></span> <span data-ttu-id="080db-107">IPv6 位址指定的使用是選用的，且不是連線 Office 365 的必要條件。</span><span class="sxs-lookup"><span data-stu-id="080db-107">Use of IPv6 addressing is optional and not required for connectivity with Office 365.</span></span> <span data-ttu-id="080db-108">使用 IPv6，並非所有的 Microsoft 365 功能都已完全啟用。</span><span class="sxs-lookup"><span data-stu-id="080db-108">Not all Microsoft 365 features are fully enabled using IPv6.</span></span> <span data-ttu-id="080db-109">如需 Ipv6 支援的詳細資訊，請參閱[Microsoft 服務中的 IPv6 支援](https://docs.microsoft.com/office365/enterprise/ipv6-support)。</span><span class="sxs-lookup"><span data-stu-id="080db-109">For more information about Ipv6 support, see [IPv6 support in Microsoft services](https://docs.microsoft.com/office365/enterprise/ipv6-support).</span></span>
  
<span data-ttu-id="080db-110">Microsoft 會在 Microsoft 協助中維護允許的 IP 位址清單。</span><span class="sxs-lookup"><span data-stu-id="080db-110">Microsoft maintains a list of allowed IP addresses in the Microsoft help.</span></span> <span data-ttu-id="080db-111">如需詳細資訊，請參閱[URLs 和 IP 位址範圍](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)。</span><span class="sxs-lookup"><span data-stu-id="080db-111">For more information, see [URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span></span> <span data-ttu-id="080db-112">對於 21Vianet 運作的 Office 365，請參閱〈[21Vianet 運作的 Office 365 的 URL 及 IP 位址](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints)〉。</span><span class="sxs-lookup"><span data-stu-id="080db-112">For Office 365 operated by 21Vianet, see [URLs and IP Addresses for Office 365 operated by 21Vianet](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints).</span></span> <span data-ttu-id="080db-113">如需了解 Office 365 Germany，請參閱〈[Office 365 Germany 端點](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8)〉。</span><span class="sxs-lookup"><span data-stu-id="080db-113">For Office 365 Germany, see [Office 365 Germany endpoints](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="080db-114">We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets.</span><span class="sxs-lookup"><span data-stu-id="080db-114">We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets.</span></span> <span data-ttu-id="080db-115">Relying on IP address subnets runs the risk of outages for your users as changes are made.</span><span class="sxs-lookup"><span data-stu-id="080db-115">Relying on IP address subnets runs the risk of outages for your users as changes are made.</span></span> 
  
## <a name="bandwidth-requirements"></a><span data-ttu-id="080db-116">頻寬需求</span><span class="sxs-lookup"><span data-stu-id="080db-116">Bandwidth requirements</span></span>

<span data-ttu-id="080db-117">如需頻寬需求的相關資訊，請參閱〈[網際網路頻寬規劃](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance)〉。</span><span class="sxs-lookup"><span data-stu-id="080db-117">For information on bandwidth requirements, see [Internet bandwidth planning](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance).</span></span>
  
## <a name="connecting-to-microsoft"></a><span data-ttu-id="080db-118">連接至 Microsoft</span><span class="sxs-lookup"><span data-stu-id="080db-118">Connecting to Microsoft</span></span>

<span data-ttu-id="080db-119">所有對 Microsoft 的連線都是透過公用網際網路或私人 Azure ExpressRoute 連線進行，並視需要受到 SSL 保護。</span><span class="sxs-lookup"><span data-stu-id="080db-119">All Connections to Microsoft are done over the public internet or over a private Azure ExpressRoute connection, and are secured by SSL as appropriate.</span></span> <span data-ttu-id="080db-120">Azure ExpressRoute 允許直接連線至全域 Microsoft 網路，而不會略過網際網路。</span><span class="sxs-lookup"><span data-stu-id="080db-120">Azure ExpressRoute allows connecting directly to the global Microsoft network, bypassing the internet.</span></span> <span data-ttu-id="080db-121">Microsoft 網路合作夥伴提供全球 Microsoft 網路的連線。</span><span class="sxs-lookup"><span data-stu-id="080db-121">A Microsoft networking partner provides the connectivity to the global Microsoft network.</span></span>
  
<span data-ttu-id="080db-122">如需 Azure ExpressRoute 的詳細資訊，請參閱 [Azure ExpressRoute Office 365](https://aka.ms/expressrouteoffice365)。</span><span class="sxs-lookup"><span data-stu-id="080db-122">For more information about Azure ExpressRoute, see [Azure ExpressRoute for Office 365.](https://aka.ms/expressrouteoffice365)</span></span>
  
### <a name="wan-accelerators"></a><span data-ttu-id="080db-123">WAN 加速器</span><span class="sxs-lookup"><span data-stu-id="080db-123">WAN accelerators</span></span>

<span data-ttu-id="080db-124">Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365.</span><span class="sxs-lookup"><span data-stu-id="080db-124">Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365.</span></span> <span data-ttu-id="080db-125">If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support.</span><span class="sxs-lookup"><span data-stu-id="080db-125">If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support.</span></span> <span data-ttu-id="080db-126">For more information, see [WAN Acceleration and caching devices with Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).</span><span class="sxs-lookup"><span data-stu-id="080db-126">For more information, see [WAN Acceleration and caching devices with Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).</span></span>
  
## <a name="the-global-microsoft-network"></a><span data-ttu-id="080db-127">Microsoft 全球網路</span><span class="sxs-lookup"><span data-stu-id="080db-127">The global Microsoft network</span></span>

<span data-ttu-id="080db-128">Microsoft 網路基礎結構由大量的資料中心、伺服器、內容發佈網路、edge 計算節點及光纖網路組成，以提供服務的全球發佈。</span><span class="sxs-lookup"><span data-stu-id="080db-128">The Microsoft networking infrastructure is comprised of a large global portfolio of data centers, servers, content distribution networks, edge computing nodes, and fiber optic networks to provide global distribution of services.</span></span> <span data-ttu-id="080db-129">將精密的服務檢測和監控功能徹底整合至所有元件中，讓您輕鬆檢視資料中心、網路骨幹、網際網路交換等元件，以便找出、診斷和管理出現的中斷原因。</span><span class="sxs-lookup"><span data-stu-id="080db-129">Sophisticated service instrumentation and monitoring integrates at the deepest levels with each component, giving visibility into the data center, network backbone, internet exchanges and beyond, to help spot, diagnose and manage the cause of disruptions that arise.</span></span> <span data-ttu-id="080db-130">此網路可在大規模網路中斷情況時，在不影響效能的情況下提供充足的儲存容量。</span><span class="sxs-lookup"><span data-stu-id="080db-130">The network is built to maintain sufficient capacity even for large scale network interruptions without degradation of performance.</span></span> <span data-ttu-id="080db-131">如需詳細資訊，請參閱[Microsoft 全球網路](https://docs.microsoft.com/azure/networking/microsoft-global-network)。</span><span class="sxs-lookup"><span data-stu-id="080db-131">For more information, see [Microsoft Global Network](https://docs.microsoft.com/azure/networking/microsoft-global-network).</span></span> 
  
<span data-ttu-id="080db-132">為了維護客戶資料的機密性和完整性，Microsoft 保留獨立于 Microsoft 網路的消費者服務網路。</span><span class="sxs-lookup"><span data-stu-id="080db-132">To maintain the confidentiality and integrity of customer data, Microsoft keeps consumer services networks separate from Microsoft networks.</span></span> <span data-ttu-id="080db-133">Microsoft 技術用於控制資料流，包括但不限於：</span><span class="sxs-lookup"><span data-stu-id="080db-133">Multiple techniques are used to control information flows, including but not limited to:</span></span>
  
- <span data-ttu-id="080db-134">Physical separation.</span><span class="sxs-lookup"><span data-stu-id="080db-134">Physical separation.</span></span> <span data-ttu-id="080db-135">Network segments are physically separated by routers that are configured to prevent specific communication patterns.</span><span class="sxs-lookup"><span data-stu-id="080db-135">Network segments are physically separated by routers that are configured to prevent specific communication patterns.</span></span>
    
- <span data-ttu-id="080db-136">Logical separation.</span><span class="sxs-lookup"><span data-stu-id="080db-136">Logical separation.</span></span> <span data-ttu-id="080db-137">Virtual LAN (VLAN) technology is used to further separate communications.</span><span class="sxs-lookup"><span data-stu-id="080db-137">Virtual LAN (VLAN) technology is used to further separate communications.</span></span>
    
- <span data-ttu-id="080db-138">防火牆。</span><span class="sxs-lookup"><span data-stu-id="080db-138">Firewalls.</span></span> <span data-ttu-id="080db-139">防火牆和其他網路安全性強制端點可用於限制對網際網路公開之系統的資料交換，以及與 Microsoft 所管理的後端系統隔離系統。</span><span class="sxs-lookup"><span data-stu-id="080db-139">Firewalls and other network security enforcement points are used to limit data exchanges with systems that are exposed to the internet, and to isolate systems from back-end systems managed by Microsoft.</span></span> 
    
- <span data-ttu-id="080db-140">通訊協定限制。</span><span class="sxs-lookup"><span data-stu-id="080db-140">Protocol restrictions.</span></span>
    
<span data-ttu-id="080db-141">如需詳細資訊，請參閱〈[Office 365 信任中心](https://www.microsoft.com/trust-center)〉。</span><span class="sxs-lookup"><span data-stu-id="080db-141">For more information, see the [Office 365 Trust Center](https://www.microsoft.com/trust-center).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="080db-142">功能可用性</span><span class="sxs-lookup"><span data-stu-id="080db-142">Feature availability</span></span>

<span data-ttu-id="080db-143">若要查看不同方案中的功能可用性，請參閱[Microsoft 365 和 Office 365 平臺服務說明](office-365-platform-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="080db-143">To view feature availability across plans, see [Microsoft 365 and Office 365 platform service description](office-365-platform-service-description.md).</span></span>
  

