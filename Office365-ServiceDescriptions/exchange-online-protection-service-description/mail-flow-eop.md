---
title: 郵件流程[EOP]
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: 對使用 Office 365 的大多數組織而言，我們可以代管信箱並處理郵件流程。 這是最簡單的配置，並代表 Office 365 管理所有的信箱和篩選。 不過，某些組織基於業務需求而需要將所有信箱保留在內部。 Exchange Online Protection (EOP) 可提供您這個功能，並在雲端提供防毒和反垃圾郵件處理。 如需詳細資訊並購買 EOP，請移至 Exchange Online Protection。
ms.openlocfilehash: c55d1d376d617b863a75ff609cbc3f064418746b
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/22/2019
ms.locfileid: "34341822"
---
# <a name="mail-floweop"></a>郵件流程[EOP]

對使用 Office 365 的大多數組織而言，我們可以代管信箱並處理郵件流程。 這是最簡單的配置，並代表 Office 365 管理所有的信箱和篩選。 不過，某些組織基於業務需求而需要將所有信箱保留在內部。 Exchange Online Protection (EOP) 可提供您這個功能，並在雲端提供防毒和反垃圾郵件處理。 如需詳細資訊並購買 EOP，請移至 [Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection)。
  
尋找網域管理還是目錄架構邊緣封鎖 (DBEB) 的詳細資訊？請參閱[收件者、網域和公司管理](recipient-domain-and-company-management.md)。若要深入了解所有 EOP 功能，請參閱 [Exchange Online Protection 服務說明](exchange-online-protection-service-description.md)。
  
## <a name="routing-email-between-office-365-and-your-own-email-servers"></a>在 Office 365 和您自己的電子郵件伺服器之間路由電子郵件
<a name="BKMK_outboundmailrouting"> </a>

您可以設定連接器以啟用 Office 365 (包括 Exchange Online 或 EOP) 和 SMTP 型電子郵件伺服器 (如 Exchange) 之間的郵件流程。如需相關的詳細資訊，請參閱[Do I need a connector](http://technet.microsoft.com/library/16731ae9-c909-49dd-bffc-a46e6151fc29.aspx)？和 [Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx)。
  
## <a name="secure-messaging-with-a-trusted-partner"></a>與信任的合作夥伴間的安全傳訊
<a name="BKMK_securemessagingwithatrustedpartner"> </a>

EOP 客戶可以使用 Office 365 連接器，設定與信任合作夥伴間的安全郵件流程。Office 365 支援透過傳輸層安全性 (TLS) 進行安全通訊，而您可以透過 TLS 建立連接器來強制執行加密。[TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) 這個密碼編譯通訊協定能提供網路通訊的安全性。您可以使用連接器，同時設定使用自我簽署或經過憑證授權單位 (CA) 驗證之憑證的強制內送和外寄 TLS。您也可以套用其他安全性限制 (像是指定合作夥伴組織傳送郵件所用的網域名稱或 IP 位址範圍)。 
  
如需詳細資訊，請參閱[對合作夥伴組織設定安全郵件流程連接器](https://technet.microsoft.com/en-us/library/dn751021%28v=exchg.150%29.aspx)。
  
## <a name="safe-listing-a-partners-ip-address"></a>安全列出夥伴的 IP 位址
<a name="BKMK_safelistingapartnersipaddress"> </a>

您可以將受信任夥伴的 IP 位址新增到安全清單中，以確保它們傳送給您的郵件不會受到垃圾郵件篩選功能的限制。若要這麼做，您可以使用連線篩選器的 IP 允許清單。如需詳細資訊，請參閱[設定連線篩選原則](https://go.microsoft.com/fwlink/p/?LinkID=287108)。
  
## <a name="conditional-mail-routing"></a>條件式郵件路由
<a name="BKMK_conditionalmailrouting"> </a>

您可以設定具有傳輸規則的連接器，以根據條件將郵件路由傳送至特定站台。如需詳細資訊，請參閱[Scenario: Conditional email routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx)。
  
## <a name="hybrid-mail-routing"></a>混合郵件路由
<a name="BKMK_hybridmailrouting"> </a>

混合的意思是部分信箱是內部部署，部分則是在雲端 (Exchange Online)。您可以從獨立 (內部) 部署移至混合部署。
  
如果具有混合部署，則可以利用 EOP 保護雲端及內部部署信箱。內部部署信箱在受到 EOP 保護時需要獨立授權。如需有關混合部署中郵件路由的詳細資訊，請參閱 [Exchange 混合部署的傳輸路由](https://go.microsoft.com/fwlink/p/?LinkId=271757)。
  
[Microsoft Exchange Server 部署助理](https://go.microsoft.com/fwlink/p/?LinkId=287036)也提供詳細的混合式部署佈建和混合式訊息傳輸指導。 
  
## <a name="feature-availability"></a>功能可用性
<a name="BKMK_hybridmailrouting"> </a>

若要檢視 Office 365 計劃、獨立選項和內部部署解決方案中的功能可用性，請參閱 [Exchange Online Protection 服務說明](exchange-online-protection-service-description.md)。
  

