---
title: 網路功能
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft 支援下列網路功能。
ms.openlocfilehash: df2fb9343529a7722fc434a79bf74621b78b787e
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652537"
---
# <a name="networking"></a>網路功能

Microsoft 支援下列網路功能。
  
## <a name="ports-protocols-and-ip-addresses"></a>連接埠、通訊協定和 IP 位址

Microsoft 使用 IPv4 和 IPv6 位址。 IPv6 位址指定的使用是選用的，且不是連線 Office 365 的必要條件。 使用 IPv6，並非所有的 Microsoft 365 功能都已完全啟用。 如需 Ipv6 支援的詳細資訊，請參閱 [Microsoft 服務中的 IPv6 支援](/office365/enterprise/ipv6-support)。
  
Microsoft 會在 Microsoft 協助中維護允許的 IP 位址清單。 如需詳細資訊，請參閱 [URLs 和 IP 位址範圍](/office365/enterprise/urls-and-ip-address-ranges)。 對於 21Vianet 運作的 Office 365，請參閱〈[21Vianet 運作的 Office 365 的 URL 及 IP 位址](/office365/enterprise/managing-office-365-endpoints)〉。 如需了解 Office 365 Germany，請參閱〈[Office 365 Germany 端點](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8)〉。
  
> [!IMPORTANT]
> 我們強烈建議您啟用上述文章中所列之根網域名稱的路由 (例如：\*.Outlook.com、\*.MicrosoftOnline.com 和 \*.SharePoint.com)，而非特定 IP 位址子網路的路由。仰賴 IP 位址子網路會讓您的使用者在進行變更時遇到中斷問題。 
  
## <a name="bandwidth-requirements"></a>頻寬需求

如需頻寬需求的相關資訊，請參閱〈[網際網路頻寬規劃](/office365/enterprise/network-planning-and-performance)〉。
  
## <a name="connecting-to-microsoft"></a>連接至 Microsoft

所有對 Microsoft 的連線都是透過公用網際網路或私人 Azure ExpressRoute 連線進行，並視需要受到 SSL 保護。 Azure ExpressRoute 允許直接連線至全域 Microsoft 網路，而不會略過網際網路。 Microsoft 網路合作夥伴提供全球 Microsoft 網路的連線。
  
如需 Azure ExpressRoute 的詳細資訊，請參閱 [Azure ExpressRoute Office 365](/microsoft-365/enterprise/azure-expressroute)。
  
### <a name="wan-accelerators"></a>WAN 加速器

Microsoft 不支援客戶自有的 WAN 加速器和 Office 365 的快取裝置。如果您決定採用 WAN 的最佳化控制器，以改善高延遲與低頻寬情況下的效能，則您必須在向 Microsoft 提出疑難排解服務要求時，停用此裝置並洽詢裝置廠商以取得裝置支援。如需相關資訊，請參閱〈[WAN 加速器和 Office 365 的快取裝置](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365)〉。
  
## <a name="the-global-microsoft-network"></a>Microsoft 全球網路

Microsoft 網路基礎結構由大量的資料中心、伺服器、內容發佈網路、edge 計算節點及光纖網路組成，以提供服務的全球發佈。 將精密的服務檢測和監控功能徹底整合至所有元件中，讓您輕鬆檢視資料中心、網路骨幹、網際網路交換等元件，以便找出、診斷和管理出現的中斷原因。 此網路可在大規模網路中斷情況時，在不影響效能的情況下提供充足的儲存容量。 如需詳細資訊，請參閱 [Microsoft 全球網路](/azure/networking/microsoft-global-network)。 
  
為了維護客戶資料的機密性和完整性，Microsoft 保留獨立于 Microsoft 網路的消費者服務網路。 Microsoft 技術用於控制資料流，包括但不限於：
  
- 實體分隔。網路區段是由路由 (設定為防止特定的通訊模式) 進行實體分隔。
    
- 邏輯分隔。虛擬 LAN (VLAN) 技術用於進一步分隔通訊。
    
- 防火牆。 防火牆和其他網路安全性強制端點可用於限制對網際網路公開之系統的資料交換，以及與 Microsoft 所管理的後端系統隔離系統。 
    
- 通訊協定限制。
    
如需詳細資訊，請參閱〈[Office 365 信任中心](https://www.microsoft.com/trust-center)〉。 
  
## <a name="feature-availability"></a>功能可用性

若要查看不同方案中的功能可用性，請參閱 [Microsoft 365 和 Office 365 平臺服務說明](office-365-platform-service-description.md)。
