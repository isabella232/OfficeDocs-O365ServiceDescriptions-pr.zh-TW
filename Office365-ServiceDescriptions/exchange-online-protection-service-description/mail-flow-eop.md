---
title: 郵件流程 [EOP]
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: 對使用 Office 365 的大多數組織而言，我們可以代管信箱並處理郵件流程。 這是最簡單的設定，並表示 Microsoft 管理所有的信箱和篩選。 不過，某些組織基於業務需求而需要將所有信箱保留在內部。 Exchange Online Protection （EOP）可讓您執行這項作業，並在雲端中提供防病毒和反垃圾郵件的郵件處理。
ms.openlocfilehash: 751551ef6b3ae710646b2fb63960eee5983d6c47
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132817"
---
# <a name="mail-floweop"></a>郵件流程 [EOP]

針對使用 Microsoft 的大多陣列織，我們會主控您的信箱並處理郵件流程。 這是最簡單的設定，並表示 Microsoft 管理所有的信箱和篩選。 不過，某些組織基於業務需求而需要將所有信箱保留在內部。 Exchange Online Protection （EOP）可讓您執行這項作業，並在雲端中提供防病毒和反垃圾郵件的郵件處理。 如需詳細資訊並購買 EOP，請移至 [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection)。
  
尋找網域管理還是目錄架構邊緣封鎖 (DBEB) 的詳細資訊？ 請參閱[收件者、網域和公司管理](recipient-domain-and-company-management.md)。 若要深入瞭解所有 EOP 功能，請參閱[Exchange Online Protection 服務說明](exchange-online-protection-service-description.md)。
  
## <a name="routing-email-between-microsoft-and-your-own-email-servers"></a>在 Microsoft 和您自己的電子郵件伺服器之間路由傳送電子郵件

您可以設定連接器，以啟用 Microsoft （包括 Exchange Online 或 EOP）與 SMTP 型電子郵件伺服器（如 Exchange）之間的郵件流程。 如需相關的詳細資訊，請參閱[Do I need a connector](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)？ 和[設定連接器，以在 Microsoft 和您自己的電子郵件伺服器之間路由傳送郵件](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)。
  
## <a name="secure-messaging-with-a-trusted-partner"></a>與信任的合作夥伴間的安全傳訊

身為 EOP 客戶，您可以使用 Microsoft connector 設定安全的郵件流程與信任的合作夥伴。 Microsoft 會透過傳輸層安全性（TLS）來支援安全通訊，而且您可以建立連接器，透過 TLS 強制加密。 [TLS](https://docs.microsoft.com/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections)是一種加密通訊協定，可為透過網際網路的通訊提供安全性。 您可以使用連接器，同時設定使用自我簽署或經過憑證授權單位 (CA) 驗證之憑證的強制內送和外寄 TLS。 您也可以套用其他安全性限制 (像是指定合作夥伴組織傳送郵件所用的網域名稱或 IP 位址範圍)。 
  
如需詳細資訊，請參閱[對合作夥伴組織設定安全郵件流程連接器](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner)。
  
## <a name="safe-listing-a-partners-ip-address"></a>安全列出夥伴的 IP 位址

You can add a trusted partner's IP address to a safe list to ensure that messages they send to you are not subject to spam filtering. To do this, you can use the connection filter's IP Allow list. For more information, see [Configure the connection filter policy](https://go.microsoft.com/fwlink/p/?LinkID=287108).
  
## <a name="conditional-mail-routing"></a>條件式郵件路由

You can configure a connector with a Transport rule that routes mail to a specific site, based on conditions. For more information, see [Scenario: Conditional email routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="hybrid-mail-routing"></a>混合郵件路由

Hybrid means that you host a portion of your mailboxes on premises, and a portion in the cloud (Exchange Online). You can move from a standalone (on-premises) deployment to a hybrid deployment.
  
If you have a hybrid deployment, you can protect your cloud and on-premises mailboxes with EOP. Standalone licenses are required for on-premises mailboxes, when they are protected by EOP. For more information about mail routing in a hybrid deployment, see [Transport routing in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
[Microsoft Exchange Server 部署助理](https://go.microsoft.com/fwlink/p/?LinkId=287036)也提供詳細的混合式部署佈建和混合式訊息傳輸指導。 
  
## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online Protection 服務說明](exchange-online-protection-service-description.md)。
