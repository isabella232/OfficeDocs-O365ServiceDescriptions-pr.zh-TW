---
title: 網路功能
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft Office 365 支援下列網路連線功能。
ms.openlocfilehash: 0a7956b5d59082f2f04f71ee2e349c2c3b238c83
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/22/2019
ms.locfileid: "34343622"
---
# <a name="networking"></a><span data-ttu-id="20908-103">網路功能</span><span class="sxs-lookup"><span data-stu-id="20908-103">Networking</span></span>

<span data-ttu-id="20908-104">Microsoft Office 365 支援下列網路連線功能。</span><span class="sxs-lookup"><span data-stu-id="20908-104">Microsoft Office 365 supports the following networking features.</span></span>
  
## <a name="ports-protocols-and-ip-addresses"></a><span data-ttu-id="20908-105">連接埠、通訊協定和 IP 位址</span><span class="sxs-lookup"><span data-stu-id="20908-105">Ports, protocols, and IP addresses</span></span>

<span data-ttu-id="20908-p101">Office 365 使用 IPv4 和 IPv6 位址。IPv6 位址指定的使用是選用的，且不是連線 Office 365 的必要條件。使用 IPv6 時，並非所有 Office 365 功能都可以完整啟用。如需有關 Office 365 之 Ipv6 支援的詳細資訊，請參閱〈[Office 365 服務中的 IPv6 支援](https://go.microsoft.com/fwlink/?LinkID=785121&amp;clcid=0x409)〉。</span><span class="sxs-lookup"><span data-stu-id="20908-p101">Office 365 uses IPv4 and IPv6 addresses. Use of IPv6 addressing is optional and not required for connectivity with Office 365. Not all Office 365 features are fully enabled using IPv6. For more information about Ipv6 support in Office 365, see [IPv6 support in Office 365 services](https://go.microsoft.com/fwlink/?LinkID=785121&amp;clcid=0x409).</span></span>
  
<span data-ttu-id="20908-p102">Office 365 會在 Office 365 說明中維護允許的 IP 位址清單。如需詳細資訊，請參閱〈[Office 365 URL 與 IP 位址範圍](https://go.microsoft.com/fwlink/p/?LinkID=243567)〉。對於 21Vianet 運作的 Office 365，請參閱〈[21Vianet 運作的 Office 365 的 URL 及 IP 位址](https://go.microsoft.com/fwlink/?LinkID=733351&amp;clcid=0x409)〉。如需了解 Office 365 Germany，請參閱〈[Office 365 Germany 端點](https://support.office.com/en-us/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8)〉。</span><span class="sxs-lookup"><span data-stu-id="20908-p102">Office 365 maintains a list of allowed IP addresses in the Office 365 help. For more information, see [Office 365 URLs and IP address ranges](https://go.microsoft.com/fwlink/p/?LinkID=243567). For Office 365 operated by 21Vianet, see [URLs and IP Addresses for Office 365 operated by 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733351&amp;clcid=0x409). For Office 365 Germany, see [Office 365 Germany endpoints](https://support.office.com/en-us/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="20908-p103">我們強烈建議您啟用上述文章中所列之根網域名稱的路由 (例如：\*.Outlook.com、\*.MicrosoftOnline.com 和 \*.SharePoint.com)，而非特定 IP 位址子網路的路由。仰賴 IP 位址子網路會讓您的使用者在進行變更時遇到中斷問題。</span><span class="sxs-lookup"><span data-stu-id="20908-p103">We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets. Relying on IP address subnets runs the risk of outages for your users as changes are made.</span></span> 
  
## <a name="bandwidth-requirements"></a><span data-ttu-id="20908-116">頻寬需求</span><span class="sxs-lookup"><span data-stu-id="20908-116">Bandwidth requirements</span></span>

<span data-ttu-id="20908-117">如需頻寬需求的相關資訊，請參閱〈[網際網路頻寬規劃](https://go.microsoft.com/fwlink/p/?LinkID=282467)〉。</span><span class="sxs-lookup"><span data-stu-id="20908-117">For information on bandwidth requirements, see [Internet bandwidth planning](https://go.microsoft.com/fwlink/p/?LinkID=282467).</span></span>
  
## <a name="connecting-to-office-365"></a><span data-ttu-id="20908-118">連線至 Office 365</span><span class="sxs-lookup"><span data-stu-id="20908-118">Connecting to Office 365</span></span>

<span data-ttu-id="20908-p104">Office 365 的所有連線都是透過公用網際網路或私人 Azure ExpressRoute 連線執行的，並且受到 SSL 的適當保護。Azure ExpressRoute 允許直接連線到全球 Microsoft 網路，而略過網際網路。Microsoft 網路合作夥伴提供全球 Microsoft 網路的連線。</span><span class="sxs-lookup"><span data-stu-id="20908-p104">All Connections to Office 365 are done over the public Internet or over a private Azure ExpressRoute connection, and are secured by SSL as appropriate. Azure ExpressRoute allows connecting directly to the global Microsoft network, bypassing the Internet. A Microsoft networking partner provides the connectivity to the global Microsoft network.</span></span>
  
<span data-ttu-id="20908-122">如需 Azure ExpressRoute 的詳細資訊，請參閱 [Azure ExpressRoute Office 365](https://aka.ms/expressrouteoffice365)。</span><span class="sxs-lookup"><span data-stu-id="20908-122">For more information about Azure ExpressRoute, see [Azure ExpressRoute for Office 365.](https://aka.ms/expressrouteoffice365)</span></span>
  
### <a name="wan-accelerators"></a><span data-ttu-id="20908-123">WAN 加速器</span><span class="sxs-lookup"><span data-stu-id="20908-123">WAN accelerators</span></span>

<span data-ttu-id="20908-p105">Microsoft 不支援客戶自有的 WAN 加速器和 Office 365 的快取裝置。如果您決定採用 WAN 的最佳化控制器，以改善高延遲與低頻寬情況下的效能，則您必須在向 Microsoft 提出疑難排解服務要求時，停用此裝置並洽詢裝置廠商以取得裝置支援。如需相關資訊，請參閱〈[WAN 加速器和 Office 365 的快取裝置](https://go.microsoft.com/fwlink/p/?LinkID=282468)〉。</span><span class="sxs-lookup"><span data-stu-id="20908-p105">Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365. If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support. For more information, see [WAN Acceleration and caching devices with Office 365](https://go.microsoft.com/fwlink/p/?LinkID=282468).</span></span>
  
## <a name="the-global-microsoft-network"></a><span data-ttu-id="20908-127">Microsoft 全球網路</span><span class="sxs-lookup"><span data-stu-id="20908-127">The global Microsoft network</span></span>

<span data-ttu-id="20908-p106">Office 365 網路基礎結構由資料中心、伺服器、內容發佈網路、邊際運算節點和光纖網路的大型全球組合組成，可提供全球散發服務。將精密的服務檢測和監控功能徹底整合至所有元件中，讓您輕鬆檢視資料中心、網路骨幹、網際網路交換等元件，以便找出、診斷和管理出現的中斷原因。此網路可在大規模網路中斷情況時，在不影響效能的情況下提供充足的儲存容量。如需相關資訊，請參閱〈[全球基礎服務](https://go.microsoft.com/fwlink/p/?LinkID=282622)〉。</span><span class="sxs-lookup"><span data-stu-id="20908-p106">The Office 365 networking infrastructure is comprised of a large global portfolio of data centers, servers, content distribution networks, edge computing nodes, and fiber optic networks to provide global distribution of services. Sophisticated service instrumentation and monitoring integrates at the deepest levels with each component, giving visibility into the data center, network backbone, internet exchanges and beyond, to help spot, diagnose and manage the cause of disruptions that arise. The network is built to maintain sufficient capacity even for large scale network interruptions without degradation of performance. For more information, see [Global Foundation Services](https://go.microsoft.com/fwlink/p/?LinkID=282622).</span></span> 
  
<span data-ttu-id="20908-p107">為維護客戶資料的機密安全和完整性，Microsoft 提供獨立於 Office 365 網路的消費者服務網路。Microsoft 技術用於控制資料流，包括但不限於：</span><span class="sxs-lookup"><span data-stu-id="20908-p107">To maintain the confidentiality and integrity of customer data, Microsoft keeps consumer services networks separate from Office 365 networks. Multiple techniques are used to control information flows, including but not limited to:</span></span>
  
- <span data-ttu-id="20908-p108">實體分隔。網路區段是由路由 (設定為防止特定的通訊模式) 進行實體分隔。</span><span class="sxs-lookup"><span data-stu-id="20908-p108">Physical separation. Network segments are physically separated by routers that are configured to prevent specific communication patterns.</span></span>
    
- <span data-ttu-id="20908-p109">邏輯分隔。虛擬 LAN (VLAN) 技術用於進一步分隔通訊。</span><span class="sxs-lookup"><span data-stu-id="20908-p109">Logical separation. Virtual LAN (VLAN) technology is used to further separate communications.</span></span>
    
- <span data-ttu-id="20908-p110">防火牆。防火牆和其他網路安全性強制端點用於限制與網際網路上的系統進行資料交換，以及隔離系統和 Microsoft 管理的後端系統。</span><span class="sxs-lookup"><span data-stu-id="20908-p110">Firewalls. Firewalls and other network security enforcement points are used to limit data exchanges with systems that are exposed to the Internet, and to isolate systems from back-end systems managed by Microsoft.</span></span> 
    
- <span data-ttu-id="20908-140">通訊協定限制。</span><span class="sxs-lookup"><span data-stu-id="20908-140">Protocol restrictions.</span></span>
    
<span data-ttu-id="20908-141">如需詳細資訊，請參閱〈[Office 365 信任中心](https://go.microsoft.com/fwlink/p/?LinkID=282621)〉。</span><span class="sxs-lookup"><span data-stu-id="20908-141">For more information, see the [Office 365 Trust Center](https://go.microsoft.com/fwlink/p/?LinkID=282621).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="20908-142">功能可用性</span><span class="sxs-lookup"><span data-stu-id="20908-142">Feature availability</span></span>

<span data-ttu-id="20908-143">若要檢視跨 Office 365 規劃的功能可用性，請參閱 [Office 365 平台服務說明](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx)。</span><span class="sxs-lookup"><span data-stu-id="20908-143">To view feature availability across Office 365 plans, see [Office 365 Platform Service Description](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).</span></span>
  

