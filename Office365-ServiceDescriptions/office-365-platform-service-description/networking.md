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
# <a name="networking"></a>網路功能

Microsoft Office 365 支援下列網路連線功能。
  
## <a name="ports-protocols-and-ip-addresses"></a>連接埠、通訊協定和 IP 位址

Office 365 使用 IPv4 和 IPv6 位址。IPv6 位址指定的使用是選用的，且不是連線 Office 365 的必要條件。使用 IPv6 時，並非所有 Office 365 功能都可以完整啟用。如需有關 Office 365 之 Ipv6 支援的詳細資訊，請參閱〈[Office 365 服務中的 IPv6 支援](https://go.microsoft.com/fwlink/?LinkID=785121&amp;clcid=0x409)〉。
  
Office 365 會在 Office 365 說明中維護允許的 IP 位址清單。如需詳細資訊，請參閱〈[Office 365 URL 與 IP 位址範圍](https://go.microsoft.com/fwlink/p/?LinkID=243567)〉。對於 21Vianet 運作的 Office 365，請參閱〈[21Vianet 運作的 Office 365 的 URL 及 IP 位址](https://go.microsoft.com/fwlink/?LinkID=733351&amp;clcid=0x409)〉。如需了解 Office 365 Germany，請參閱〈[Office 365 Germany 端點](https://support.office.com/en-us/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8)〉。
  
> [!IMPORTANT]
> 我們強烈建議您啟用上述文章中所列之根網域名稱的路由 (例如：\*.Outlook.com、\*.MicrosoftOnline.com 和 \*.SharePoint.com)，而非特定 IP 位址子網路的路由。仰賴 IP 位址子網路會讓您的使用者在進行變更時遇到中斷問題。 
  
## <a name="bandwidth-requirements"></a>頻寬需求

如需頻寬需求的相關資訊，請參閱〈[網際網路頻寬規劃](https://go.microsoft.com/fwlink/p/?LinkID=282467)〉。
  
## <a name="connecting-to-office-365"></a>連線至 Office 365

Office 365 的所有連線都是透過公用網際網路或私人 Azure ExpressRoute 連線執行的，並且受到 SSL 的適當保護。Azure ExpressRoute 允許直接連線到全球 Microsoft 網路，而略過網際網路。Microsoft 網路合作夥伴提供全球 Microsoft 網路的連線。
  
如需 Azure ExpressRoute 的詳細資訊，請參閱 [Azure ExpressRoute Office 365](https://aka.ms/expressrouteoffice365)。
  
### <a name="wan-accelerators"></a>WAN 加速器

Microsoft 不支援客戶自有的 WAN 加速器和 Office 365 的快取裝置。如果您決定採用 WAN 的最佳化控制器，以改善高延遲與低頻寬情況下的效能，則您必須在向 Microsoft 提出疑難排解服務要求時，停用此裝置並洽詢裝置廠商以取得裝置支援。如需相關資訊，請參閱〈[WAN 加速器和 Office 365 的快取裝置](https://go.microsoft.com/fwlink/p/?LinkID=282468)〉。
  
## <a name="the-global-microsoft-network"></a>Microsoft 全球網路

Office 365 網路基礎結構由資料中心、伺服器、內容發佈網路、邊際運算節點和光纖網路的大型全球組合組成，可提供全球散發服務。將精密的服務檢測和監控功能徹底整合至所有元件中，讓您輕鬆檢視資料中心、網路骨幹、網際網路交換等元件，以便找出、診斷和管理出現的中斷原因。此網路可在大規模網路中斷情況時，在不影響效能的情況下提供充足的儲存容量。如需相關資訊，請參閱〈[全球基礎服務](https://go.microsoft.com/fwlink/p/?LinkID=282622)〉。 
  
為維護客戶資料的機密安全和完整性，Microsoft 提供獨立於 Office 365 網路的消費者服務網路。Microsoft 技術用於控制資料流，包括但不限於：
  
- 實體分隔。網路區段是由路由 (設定為防止特定的通訊模式) 進行實體分隔。
    
- 邏輯分隔。虛擬 LAN (VLAN) 技術用於進一步分隔通訊。
    
- 防火牆。防火牆和其他網路安全性強制端點用於限制與網際網路上的系統進行資料交換，以及隔離系統和 Microsoft 管理的後端系統。 
    
- 通訊協定限制。
    
如需詳細資訊，請參閱〈[Office 365 信任中心](https://go.microsoft.com/fwlink/p/?LinkID=282621)〉。 
  
## <a name="feature-availability"></a>功能可用性

若要檢視跨 Office 365 規劃的功能可用性，請參閱 [Office 365 平台服務說明](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx)。
  

