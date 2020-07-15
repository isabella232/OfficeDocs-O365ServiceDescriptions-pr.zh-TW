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
# <a name="mail-flow"></a>郵件流程

對大多數的組織而言，我們會主控您的信箱並處理郵件流程。 這是最簡單的設定，並表示 Microsoft 管理所有的信箱和篩選。 不過，某些組織需要更複雜的郵件流程設定，以確保它們遵守特定法規或業務需求。 您可以在此找到這些選項。 
  
## <a name="custom-routing-of-outbound-email"></a>自訂輸出電子郵件的路由傳送

Microsoft Exchange Online 可以透過內部部署伺服器或託管服務 (有時稱為「智慧型託管」) 路由來自組織的郵件流程。 這可讓您的組織使用資料遺失防護（DLP）裝置，執行外寄電子郵件的自訂後續處理，並透過私人網路絡將電子郵件傳送給商務合作夥伴。 Exchange Online 也支援地址修正功能，透過會修改位址的功能，外寄電子郵件將會透過內部部署閘道進行路由。 這項功能可讓您隱藏子域、將多網域組織的電子郵件顯示為單一網域，或讓夥伴轉送的電子郵件顯示為從組織內傳送。 管理員可以在 Exchange 系統管理中心 (EAC) 內設定自訂電子郵件路由。
  
如需詳細資訊，請參閱[設定連接器以在 Microsoft 和您自己的電子郵件伺服器之間路由傳送郵件](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)。
  
> [!IMPORTANT]
> Exchange Online 可以傳送在您的組織中進出的郵件。 如果您的收件者網域主控于 Exchange Online 中，且 DNS MX 記錄指向 Exchange Online Protection，則來自您租使用者的郵件流程將不會透過網際網路傳送。
  
## <a name="secure-messaging-with-a-trusted-partner"></a>與信任的合作夥伴間的安全傳訊

做為 Exchange Online 客戶時，您可以使用 Microsoft 連接器設定安全的郵件流程與信任的合作夥伴。 Microsoft 會透過傳輸層安全性（TLS）來支援安全通訊，而且您可以建立連接器，透過 TLS 強制加密。 [TLS](https://docs.microsoft.com/office365/securitycompliance/exchange-online-uses-tls-to-secure-email-connections)是一種加密通訊協定，可為透過網際網路的通訊提供安全性。 您可以使用連接器，同時設定使用自我簽署或經過憑證授權單位 (CA) 驗證之憑證的強制內送和外寄 TLS。 您也可以套用其他安全性限制 (像是指定合作夥伴組織傳送郵件所用的網域名稱或 IP 位址範圍)。 
  
如需詳細資訊，請參閱＜[Set up connectors for secure mail flow with a partner organization](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner)＞。
  
> [!IMPORTANT]
> 可能需要經過 CA 驗證的憑證。 
  
## <a name="conditional-mail-routing"></a>條件式郵件路由

You can direct mail to specific sites by using connectors and transport rules. With criteria-based routing, you can choose a connector based on specific conditions.
  
如需詳細資訊，請參閱＜[Scenario: Conditional mail routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing)＞。
  
## <a name="incoming-mail-safe-list"></a>內送郵件安全清單

You can add a trusted partner's IP address to a safe list to ensure that messages the partner sends to you are not subject to anti-spam filtering. To do this, you can use the connection filter's IP Allow list.
  
如需詳細資訊，請參閱＜[Configure the connection filter policy](https://docs.microsoft.com/office365/SecurityCompliance/configure-the-connection-filter-policy)＞。
  
## <a name="hybrid-email-routing"></a>混合電子郵件路由

A hybrid deployment gives organizations the ability to extend the feature-rich experience and administrative control they have with their existing on-premises Microsoft Exchange organization to the cloud. With hybrid transport, messages sent between recipients in either organization are authenticated, encrypted, and transferred using Transport Layer Security (TLS), and appear as "internal" to Exchange components such as transport rules, journaling, and anti-spam policies. You configure hybrid transport by using the Hybrid Configuration Wizard in Exchange Server.
  
如需有關混合部署中郵件路由的詳細資訊，請參閱 [Exchange 混合部署的傳輸路由](https://go.microsoft.com/fwlink/p/?LinkId=271757)。
  
[Microsoft Exchange Server 部署助理](https://go.microsoft.com/fwlink/p/?LinkId=287036)也提供詳細的混合式部署佈建和混合式訊息傳輸指導。 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a>具有內部部署路由控制的共用位址空間 (MX 點至內部部署)

具有 On-Premises 路由控制的共用位址空間（MX 指向 On-Premises）是一種混合式部署郵件路由案例，在此案例中，您的信箱已部分主控于 Exchange Online 和部分內部部署中，而且傳入和傳出網際網路郵件流程會透過內部部署 Exchange 組織進行路由傳送。 這種案例也稱為集中式郵件傳輸。 在此案例中，會使用 EOP 來布建 Exchange Online，而且傳入的網際網路郵件會路由傳送至您的內部部署郵件伺服器，然後才會路由傳送至 EOP，最後傳送至 Exchange Online 中主控的信箱。 此外，來自 Exchange Online 信箱的外寄郵件會透過內部部署 Exchange 組織進行路由，以使郵件傳送至外部收件者。 您可以透過這個設定，將單一 SMTP 網域命名空間使用於內部部署 Exchange 組織和 Exchange Online 組織中的所有信箱。 
  
如需有關混合部署中傳輸選項的詳細資訊，請參閱 [Exchange 混合部署的傳輸選項](https://go.microsoft.com/fwlink/p/?LinkID=271758)。
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a>無內部部署路由控制的共用位址空間 (MX 點至 EOP)

無內部部署路由控制的共用位址空間 (MX 指向 EOP) 是一種混合郵件路由案例，其中信箱部分託管於雲端 (使用 Exchange Online)，部分位於內部部署，而 MX 記錄會指向 EOP。 當您使用 Microsoft 來裝載某些組織的信箱，且您想要 EOP 保護您的內部部署和雲端信箱時，此案例適用。 在此案例中，傳送至您組織中收件者的郵件一開始會透過 EOP 進行路由 (會在此處進行垃圾郵件和原則篩選作業)，然後再送達您內部部署信箱和雲端信箱。 
  
如需有關混合部署中傳輸選項的詳細資訊，請參閱 [Exchange 混合部署的傳輸選項](https://go.microsoft.com/fwlink/p/?LinkID=271758)。
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a>使用混合組態精靈進行部署的疑難排解

Using the Hybrid Configuration Wizard to configure a hybrid deployment in Microsoft Exchange Server greatly minimizes the potential that the hybrid deployment will experience problems. However, there are some typical areas outside the scope of the Hybrid Configuration Wizard that, if misconfigured, may present problems in a hybrid deployment. These include proper Client Access server configuration and proper certificate installation and configuration.
  
如需有關使用混合組態精靈對部署進行疑難排解的詳細資訊，請參閱[疑難排解混合部署](https://go.microsoft.com/fwlink/p/?LinkId=271040)。
  
### <a name="managing-a-hybrid-configuration"></a>管理混合組態

You can modify an existing hybrid configuration by changing settings in the Hybrid Configuration Wizard. Scenarios include disabling centralized transport or disabling secure mail transport.
  
如需有關管理混合部署設定的詳細資訊，請參閱[管理混合部署](https://go.microsoft.com/fwlink/p/?LinkId=271044)。
  
### <a name="hybrid-deployment-requirements"></a>混合部署需求

如需有關混合部署需求的詳細資訊，請參閱[混合部署必要條件](https://go.microsoft.com/fwlink/p/?LinkId=271759)。
  
> [!IMPORTANT]
> 在某些混合組態中，您可能需要為內部部署信箱購買 Exchange Online Protection 授權。 
  
## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online 服務說明](exchange-online-service-description.md)。
  