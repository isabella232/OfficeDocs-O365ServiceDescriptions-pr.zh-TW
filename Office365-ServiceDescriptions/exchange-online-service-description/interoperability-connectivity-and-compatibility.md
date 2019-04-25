---
title: 互通性、連線性和相容性
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: 55cb63c948d6e5f98cea64f98d0ca9d3d8fcdc21
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/25/2019
ms.locfileid: "33244879"
---
# <a name="interoperability-connectivity-and-compatibility"></a><span data-ttu-id="4bd9c-102">互通性、連線性和相容性</span><span class="sxs-lookup"><span data-stu-id="4bd9c-102">Interoperability, Connectivity, and Compatibility</span></span>

## <a name="interoperability-with-other-microsoft-products"></a><span data-ttu-id="4bd9c-103">與其他 Microsoft 產品互通性</span><span class="sxs-lookup"><span data-stu-id="4bd9c-103">Interoperability with other Microsoft products</span></span>

### <a name="skype-for-business-online"></a><span data-ttu-id="4bd9c-104">商務用 Skype Online</span><span class="sxs-lookup"><span data-stu-id="4bd9c-104">Skype for Business Online</span></span>

<span data-ttu-id="4bd9c-105">針對在內部部署 Microsoft Lync Server 2010、Lync Server 2013 或 Microsoft Office Communications Server 2007 R2 的客戶，Microsoft Office Communicator 可以藉由 Exchange Web 服務連線至 Microsoft Exchange Online，以存取郵件答錄機訊息和行事曆資料。</span><span class="sxs-lookup"><span data-stu-id="4bd9c-105">For customers who have deployed Microsoft Lync Server 2010, Lync Server 2013 or Microsoft Office Communications Server 2007 R2 on-premises, Microsoft Office Communicator can connect to Microsoft Exchange Online by using Exchange Web Services to access out-of-office messages and calendar data.</span></span>
  
<span data-ttu-id="4bd9c-106">內部部署的 Lync Server 2010 和 Lync Server 2013 可以使用另外兩種方式與 Exchange Online 交互操作：</span><span class="sxs-lookup"><span data-stu-id="4bd9c-106">On-premises Lync Server 2010 and Lync Server 2013 can interoperate with Exchange Online in two additional ways:</span></span>
  
- <span data-ttu-id="4bd9c-107">Outlook Web App 的 IM 和顯示狀態的互通性</span><span class="sxs-lookup"><span data-stu-id="4bd9c-107">IM and presence interoperability in Outlook Web App</span></span>
    
- <span data-ttu-id="4bd9c-108">語音信箱互通性</span><span class="sxs-lookup"><span data-stu-id="4bd9c-108">Voice mail interoperability</span></span>
    
<span data-ttu-id="4bd9c-p101">如需要更多關於如何利用 Exchange Online 設定 商務用 Skype Server 2015 的資訊，請參閱[設定內部部署商務用 Skype Server 2015 與 Exchange Online 的整合](https://go.microsoft.com/fwlink/p/?LinkId=271804)。如需混合式組態的詳細資訊，請參閱[支援的商務用 Skype Server 2015 混合式組態](https://go.microsoft.com/fwlink/?LinkID=513084)。</span><span class="sxs-lookup"><span data-stu-id="4bd9c-p101">For more information about how to configure Skype for Business Server 2015 with Exchange Online, see [Configuring On-premises Skype for Business Server 2015 Integration with Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). For hybrid configurations, see [Supported Skype for Business Server 2015 hybrid configurations](https://go.microsoft.com/fwlink/?LinkID=513084).</span></span>
  
### <a name="microsoft-sharepoint"></a><span data-ttu-id="4bd9c-111">Microsoft SharePoint</span><span class="sxs-lookup"><span data-stu-id="4bd9c-111">Microsoft SharePoint</span></span>

<span data-ttu-id="4bd9c-112">針對已部署 Microsoft SharePoint Server 或 SharePoint Online 以作為 Office 365 訂閱計劃一部分的客戶，SharePoint 可以連線至 Exchange Online 以獲得整合服務。</span><span class="sxs-lookup"><span data-stu-id="4bd9c-112">For customers who have deployed Microsoft SharePoint Server or SharePoint Online as part of an Office 365 subscription plan, SharePoint can connect to Exchange Online for integrated services.</span></span>
  
<span data-ttu-id="4bd9c-113">如需有關如何將 SharePoint 與 Exchange Online 連線的更多資訊，請參閱[在自訂網域中使用 SharePoint Online 與其他服務](https://go.microsoft.com/fwlink/?LinkId=271805)。</span><span class="sxs-lookup"><span data-stu-id="4bd9c-113">For more information about connecting SharePoint to Exchange Online, see [Use SharePoint Online on a custom domain together with other services](https://go.microsoft.com/fwlink/?LinkId=271805).</span></span>
  
## <a name="features-for-external-connectivity"></a><span data-ttu-id="4bd9c-114">外部連線功能</span><span class="sxs-lookup"><span data-stu-id="4bd9c-114">Features for external connectivity</span></span>

<span data-ttu-id="4bd9c-115">為了與外部應用程式和設備連線，Exchange Online 提供下列功能：</span><span class="sxs-lookup"><span data-stu-id="4bd9c-115">Exchange Online offers the following features for connecting with external applications and devices:</span></span>
  
- <span data-ttu-id="4bd9c-p102">**透過 MAPI over HTTP、SMTP、POP3、IMAP4 這類訊息通訊協定或 Exchange Web 服務** 在內部部署、Azure 或其他託管服務中執行的外部應用程式，可以透過 MAPI over HTTP、SMTP、POP3 和 IMAPv4 這類訊息通訊協定存取以 Exchange Online 儲存的資料。應用程式部署時，建議使用 Exchange Web 服務或 Exchange Web 服務管理的 API。</span><span class="sxs-lookup"><span data-stu-id="4bd9c-p102">**Through messaging protocols such as MAPI over HTTP, SMTP, POP3, IMAP4, or Exchange Web Services** External applications that are running on-premises, in Azure, or in other hosted services can access data stored with Exchange Online by using messaging protocols such as MAPI over HTTP, SMTP, POP3, and IMAPv4. Exchange Web Services or the Exchange Web Services Managed API is recommended for application development.</span></span> 
    
- <span data-ttu-id="4bd9c-118">**如同 SMTP 轉送** Exchange Online 可以被設定成 SMTP 傳遞服務，用以轉送從傳真閘道、網路設備和自訂應用程式寄來的電子郵件訊息。</span><span class="sxs-lookup"><span data-stu-id="4bd9c-118">**As an SMTP relay** Exchange Online can be set up as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications.</span></span> 
    
### <a name="exchange-web-services"></a><span data-ttu-id="4bd9c-119">Exchange Web 服務</span><span class="sxs-lookup"><span data-stu-id="4bd9c-119">Exchange Web Services</span></span>

<span data-ttu-id="4bd9c-p103">Exchange Web Services (EWS) 是適合用於 Exchange Server 和 Exchange Online 開發的 API。系統管理員可以使用 EWS 或 EWS 管理的 API，從內部部署、Azure 或其他託管服務中執行的應用程式，存取以 Exchange Online 儲存的資料。EWS 可支援管理員執行特殊的動作，例如查詢信箱內容、張貼行事曆活動、建立工作，或是依據電子郵件訊息內容觸發特定動作。Exchange Online 可藉由將應用程式權限授予客戶帳號以啟用 EWS 功能。這些權限允許客戶的應用程式存取應用程式信箱並新增內容。Exchange 模擬 是一種用來授予應用程式權限的方式。關於如何以 Exchange Online 使用 Exchange Web Services 的細節，請參閱 Exchange Online 開發人員中心的技術文章。</span><span class="sxs-lookup"><span data-stu-id="4bd9c-p103">Exchange Web Services (EWS) is the preferred development API for Exchange Server and Exchange Online. Using EWS or the EWS Managed API, administrators can access data stored with Exchange Online from applications that are running on-premises, in Azure, or in other hosted services. EWS enables administrators to perform specialized actions, such as querying the contents of a mailbox, posting a calendar event, creating a task, or triggering a specific action based on the content of an email message. Exchange Online enables EWS functionality by granting application permissions to customer accounts. These permissions allow the customer application to access the application mailbox and add content. Exchange Impersonation is one method used to grant application permissions. For details about how to use Exchange Web Services with Exchange Online, refer to the technical articles at the Exchange Online Developer Center.</span></span>
  
### <a name="smtp-relay"></a><span data-ttu-id="4bd9c-127">SMTP 轉送</span><span class="sxs-lookup"><span data-stu-id="4bd9c-127">SMTP relay</span></span>

<span data-ttu-id="4bd9c-p104">Exchange Online 可以當作 SMTP 傳遞服務使用，用以轉送從傳真閘道、網路設備和自訂應用程式寄來的電子郵件訊息。舉例來說，如果企業營運應用程式寄送電子郵件警示給使用者，可以將其設定成使用 Exchange Online 作為郵件傳送系統。應用程式或服務必需透過有效且已獲授權之 Exchange Online 信箱的使用者名稱和密碼來進行驗證，並使用傳輸層安全性 (TLS) 連線。</span><span class="sxs-lookup"><span data-stu-id="4bd9c-p104">Exchange Online can be used as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications. For example, if a line-of-business application sends email alerts to users, it can be configured to use Exchange Online as the mail delivery system. The application or service must authenticate with the username and password of a valid, licensed Exchange Online mailbox, and connect by using Transport Layer Security (TLS).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="4bd9c-131">功能可用性</span><span class="sxs-lookup"><span data-stu-id="4bd9c-131">Feature Availability</span></span>

<span data-ttu-id="4bd9c-132">若要檢視 Office 365 計劃、獨立選項和內部部署解決方案中的功能可用性，請參閱 [Exchange Online 服務說明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="4bd9c-132">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

