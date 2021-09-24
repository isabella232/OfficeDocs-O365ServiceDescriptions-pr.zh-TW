---
title: Exchange Online Protection 中的郵件流程
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: 請閱讀本文以瞭解 Microsoft Exchange Online Protection (EOP) 中的郵件流程。
ms.openlocfilehash: 4cc64692eb9cfb338e4fa9ab1ad7d7b4f889e280
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/24/2021
ms.locfileid: "59672334"
---
# <a name="mail-flow-in-exchange-online-protection"></a>Exchange Online Protection 中的郵件流程

針對使用 Microsoft 的大多陣列織，我們會主控您的信箱並處理郵件流程。 這是最簡單的設定，並表示 Microsoft 管理所有的信箱和篩選。 不過，某些組織基於業務需求而需要將所有信箱保留在內部。 Exchange Online Protection (EOP) 可讓您執行此作業，並在雲端中提供防病毒和反垃圾郵件的郵件處理。 如需詳細資訊並購買 EOP，請移至 [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection)。
  
尋找網域管理還是目錄架構邊緣封鎖 (DBEB) 的詳細資訊？ 請參閱 [收件者、網域和公司管理](recipient-domain-and-company-management.md)。 若要深入瞭解所有 EOP 功能，請參閱[Exchange Online Protection 服務描述](exchange-online-protection-service-description.md)。
  
## <a name="routing-email-between-microsoft-and-your-own-email-servers"></a>在 Microsoft 和您自己的電子郵件伺服器之間路由傳送電子郵件

您可以設定連接器，以啟用包含 Exchange Online 或 EOP) 和 SMTP 型電子郵件伺服器（如 Exchange）的 Microsoft (之間的郵件流程。 如需相關的詳細資訊，請參閱[Do I need a connector](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)？ 和 [設定連接器，以在 Microsoft 和您自己的電子郵件伺服器之間路由傳送郵件](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)。
  
## <a name="secure-messaging-with-a-trusted-partner"></a>與信任的合作夥伴間的安全傳訊

身為 EOP 客戶，您可以使用 Microsoft connector 設定安全的郵件流程與信任的合作夥伴。 Microsoft 會透過傳輸層安全性 (TLS) 來支援安全通訊，而且您可以建立連接器，透過 TLS 強制加密。 [TLS](/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) 是一種加密通訊協定，可為透過網際網路的通訊提供安全性。 您可以使用連接器，同時設定使用自我簽署或經過憑證授權單位 (CA) 驗證之憑證的強制內送和外寄 TLS。 您也可以套用其他安全性限制 (像是指定合作夥伴組織傳送郵件所用的網域名稱或 IP 位址範圍)。 
  
如需詳細資訊，請參閱[對合作夥伴組織設定安全郵件流程連接器](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner)。
  
## <a name="safe-listing-a-partners-ip-address"></a>安全列出夥伴的 IP 位址

您可以將受信任夥伴的 IP 位址新增到安全清單中，以確保它們傳送給您的郵件不會受到垃圾郵件篩選功能的限制。若要這麼做，您可以使用連線篩選器的 IP 允許清單。如需詳細資訊，請參閱[設定連線篩選原則](/microsoft-365/security/office-365-security/configure-the-connection-filter-policy)。
  
## <a name="conditional-mail-routing"></a>條件式郵件路由

您可以設定具有傳輸規則的連接器，以根據條件將郵件路由傳送至特定站台。如需詳細資訊，請參閱[Scenario: Conditional email routing](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing)。
  
## <a name="hybrid-mail-routing"></a>混合郵件路由

混合的意思是部分信箱是內部部署，部分則是在雲端 (Exchange Online)。您可以從獨立 (內部) 部署移至混合部署。
  
如果具有混合部署，則可以利用 EOP 保護雲端及內部部署信箱。內部部署信箱在受到 EOP 保護時需要獨立授權。如需有關混合部署中郵件路由的詳細資訊，請參閱 [Exchange 混合部署的傳輸路由](/exchange/transport-routing)。
  
[Microsoft Exchange Server 部署助理](/exchange/exchange-deployment-assistant)也提供詳細的混合式部署佈建和混合式訊息傳輸指導。 
  
## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online Protection 服務描述](exchange-online-protection-service-description.md)。