---
title: 互通性、連線性和相容性
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: 5308770ff7fc6ab6c44f27293ff89ebbffa6e72f
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132747"
---
# <a name="interoperability-connectivity-and-compatibility"></a>互通性、連線性和相容性

## <a name="interoperability-with-other-microsoft-products"></a>與其他 Microsoft 產品互通性

### <a name="skype-for-business-online"></a>商務用 Skype Online

針對在內部部署 Microsoft Lync Server 2010、Lync Server 2013 或 Microsoft Office Communications Server 2007 R2 的客戶，Microsoft Office Communicator 可以藉由 Exchange Web 服務連線至 Microsoft Exchange Online，以存取郵件答錄機訊息和行事曆資料。
  
內部部署的 Lync Server 2010 和 Lync Server 2013 可以使用另外兩種方式與 Exchange Online 交互操作：
  
- Outlook 網頁版中的 IM 和目前狀態互通性
    
- 語音信箱互通性
    
For more information about how to configure Skype for Business Server 2015 with Exchange Online, see [Configuring On-premises Skype for Business Server 2015 Integration with Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). For hybrid configurations, see [Supported Skype for Business Server 2015 hybrid configurations](https://go.microsoft.com/fwlink/?LinkID=513084).
  
### <a name="microsoft-sharepoint"></a>Microsoft SharePoint

若客戶已部署 Microsoft SharePoint Server 或 SharePoint 線上做為訂閱計畫的一部分，SharePoint 可連線至 Exchange Online 的整合式服務。
  
如需有關如何將 SharePoint 與 Exchange Online 連線的更多資訊，請參閱[在自訂網域中使用 SharePoint Online 與其他服務](https://go.microsoft.com/fwlink/?LinkId=271805)。
  
## <a name="features-for-external-connectivity"></a>外部連線功能

為了與外部應用程式和設備連線，Exchange Online 提供下列功能：
  
- **Through messaging protocols such as MAPI over HTTP, SMTP, POP3, IMAP4, or Exchange Web Services** External applications that are running on-premises, in Azure, or in other hosted services can access data stored with Exchange Online by using messaging protocols such as MAPI over HTTP, SMTP, POP3, and IMAPv4. Exchange Web Services or the Exchange Web Services Managed API is recommended for application development. 
    
- **如同 SMTP 轉送** Exchange Online 可以被設定成 SMTP 傳遞服務，用以轉送從傳真閘道、網路設備和自訂應用程式寄來的電子郵件訊息。 
    
### <a name="exchange-web-services"></a>Exchange Web 服務

Exchange Web Services (EWS) 是適合用於 Exchange Server 和 Exchange Online 開發的 API。 系統管理員可以使用 EWS 或 EWS 管理的 API，從內部部署、Azure 或其他託管服務中執行的應用程式，存取以 Exchange Online 儲存的資料。 EWS 可讓系統管理員執行特殊的動作，例如查詢信箱內容、發佈行事曆事件、建立任務，或根據電子郵件的內容觸發特定動作。 Exchange Online 可藉由將應用程式權限授予客戶帳號以啟用 EWS 功能。 這些權限允許客戶的應用程式存取應用程式信箱並新增內容。 Exchange 模擬 是一種用來授予應用程式權限的方式。 關於如何以 Exchange Online 使用 Exchange Web Services 的細節，請參閱 Exchange Online 開發人員中心的技術文章。
  
### <a name="smtp-relay"></a>SMTP 轉送

Exchange Online can be used as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications. For example, if a line-of-business application sends email alerts to users, it can be configured to use Exchange Online as the mail delivery system. The application or service must authenticate with the username and password of a valid, licensed Exchange Online mailbox, and connect by using Transport Layer Security (TLS).
  
## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online 服務說明](exchange-online-service-description.md)。
  

