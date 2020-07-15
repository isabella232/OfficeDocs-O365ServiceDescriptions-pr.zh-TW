---
title: 報告功能和疑難排解工具
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online 提供 Exchange 系統管理中心（EAC）內和以外的各種報告功能。
ms.openlocfilehash: f2cc51c9923be8d399fa2837e5b5fabe3117d5ba
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132597"
---
# <a name="reporting-features-and-troubleshooting-tools"></a>報告功能和疑難排解工具

Microsoft Exchange Online 提供 Exchange 系統管理中心（EAC）內和以外的各種報告功能。
  
## <a name="reporting-features"></a>報告功能

Exchange Online 客戶可以透過下載 Excel 報告活頁簿或使用 web 服務，存取 Microsoft 365 系統管理中心中的報告。
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a>Microsoft 365 系統管理中心的報告

Microsoft 365 系統管理中心的 [報告] 頁面上有報告，提供信箱和群組的摘要資訊。 例如，一份報告列出了依日、週或年所建立和刪除的群組數目。 也有新增和刪除信箱的摘要報告，以及使用中和非使用中信箱的摘要報告。 
  
此外，Microsoft 365 系統管理中心的 [報告] 頁面包含郵件資料包告，其可提供郵件流量、垃圾郵件和惡意程式碼偵測的相關資訊，以及受 Exchange Transport Rules 或資料遺失防護（DLP）原則影響的郵件。 保護、規則和 DLP 的增強型報告可讓 Exchange Online 系統管理員享有互動報告體驗。 這些報告提供摘要資料，而且可供人向下切入至個別郵件的詳細資料。
  
如需每個訂閱可用報告的詳細資訊，請參閱[報告](../office-365-platform-service-description/reports.md)。 如需 Microsoft 365 系統管理中心內 [報告] 頁面的詳細資訊，請參閱[view and 下載中心 For Office 365 中的服務使用狀況](https://go.microsoft.com/fwlink/p/?LinkId=401187)和[使用郵件保護報告來查看有關惡意程式碼、垃圾郵件和規則](https://go.microsoft.com/fwlink/p/?LinkID=401102)偵測的資料。
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>使用 Excel 報告活頁簿執行報告

您也可以使用 Excel 2013 報告活頁簿，來檢視具有深入探查功能的摘要報告。 不過，我們建議您改為使用增強型 Microsoft 365 系統管理中心報告。 Excel 2013 報告活頁簿預計將在未來被取代。 如需更多概觀資訊，以及下載和安裝活頁簿的連結，請參閱下列[下載頁面](https://go.microsoft.com/fwlink/p/?LinkId=271776)。 如需有關如何使用活頁簿的資訊，請參閱[使用 Excel 報告活頁簿的郵件保護報告](https://go.microsoft.com/fwlink/p/?LinkId=285211)。 
  
### <a name="reporting-using-web-services"></a>Reporting using web services

您可以使用 REST/OData 租使用者報告 web 服務（這是一種程式設計介面，可讓您建立自訂報告），存取信箱、群組和郵件資料的摘要和詳細報告。 如需詳細資訊，請參閱[Office 365 報告 web 服務](https://go.microsoft.com/fwlink/p/?LinkId=287041)。
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a>EAC 中的報告功能和疑難排解工具

您可在 Exchange 系統管理中心中使用下列報告功能和疑難排解工具。
  
### <a name="trace-an-email-message"></a>追蹤電子郵件訊息

郵件追蹤功能可讓您以系統管理員的身分，在電子郵件訊息通過 Exchange Online 服務時，追蹤電子郵件。 它可以協助您判斷服務是否已接收、拒絕、延遲或傳遞目標電子郵件訊息。 此舉可讓您有效回答使用者的問題和疑難排解郵件流程問題，減少了需要連絡技術支援尋求協助的需求。
  
> [!IMPORTANT]
> For troubleshooting general issues and trends, use the reporting tools to obtain such data. For single point specifics where details are needed about a message, use the message trace tool. 
  
如需有關郵件追蹤功能的詳細資訊，請參閱[追蹤電子郵件訊息](https://go.microsoft.com/fwlink/p/?LinkId=271777)。
  
### <a name="auditing-reports"></a>稽核報告

You can use audit logging to troubleshoot configuration issues by tracking specific changes made by administrators and to help you meet regulatory, compliance, and litigation requirements. Exchange Online provides two types of audit logging:
  
- Administrator audit logging records any action performed by an administrator. This can help you troubleshoot configuration issues or identify the cause of security-related or compliance-related problems. 
    
- Mailbox audit logging records whenever a mailbox is accessed by someone other than the person who owns the mailbox. This can help you determine who has accessed a mailbox and what they've done. 
    
如需有關稽核記錄的詳細資訊，請參閱[稽核報告](https://go.microsoft.com/fwlink/p/?LinkId=271779)。
  
### <a name="unified-messaging-reports"></a>整合通訊報告

You can use these reports to monitor and troubleshoot Unified Messaging (UM) in your Exchange Online organization. For more information, see [Run Reports for Voice Mail Calls](https://go.microsoft.com/fwlink/p/?LinkId=287042).
  
## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online 服務說明](exchange-online-service-description.md)。
  

