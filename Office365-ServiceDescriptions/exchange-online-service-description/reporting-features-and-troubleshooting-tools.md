---
title: 報告功能和疑難排解工具
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online 提供各種報告 Exchange 系統管理中心 (EAC) 功能。
ms.openlocfilehash: 16bcea7f90115ca3238e502e5b57d756d24025ba
ms.sourcegitcommit: 4abe1be8a63406e8a8c1a4a69f95386906ea1499
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 02/22/2019
ms.locfileid: "30210216"
---
# <a name="reporting-features-and-troubleshooting-tools"></a>報告功能和疑難排解工具

Microsoft Exchange Online 提供各種報告 Exchange 系統管理中心 (EAC) 功能。
  
## <a name="reporting-features"></a>報告功能

下載 Excel 報告活頁簿，或使用 Web 服務 Exchange Online 客戶可以存取 Microsoft 365 系統管理中心內的報告。
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a>Microsoft 365 系統管理中心的報告

有 Microsoft 365 系統管理中心 [報告] 頁面上提供的信箱和群組的摘要資訊的報表。例如，一份報告列出群組建立與刪除一天、 一週、 一個月或年的數。也有新增和已刪除信箱摘要報告與使用中和非使用中的信箱。 
  
此外，Microsoft 365 系統管理中心 [報告] 頁面包含訊息提供郵件流量、 垃圾郵件和惡意程式碼偵測及訊息會受到 Exchange 傳輸規則或資料遺失防護 (DLP) 的相關資訊的資料報告原則。增強的保護、 規則和 DLP 報告提供 Exchange Online 管理員的互動式報表的體驗。這些報告提供摘要資料和向下切入需個別郵件的詳細資訊的能力。
  
如需受報表可用的每一個 Office 365 訂閱的詳細資訊，請參閱[報告](../office-365-platform-service-description/reports.md)。如需 Microsoft 365 系統管理中心中，[報告] 頁面的詳細的資訊請參閱[檢視並下載 Office 365 中服務使用情況報告](https://go.microsoft.com/fwlink/p/?LinkId=401187)和[使用的郵件保護報告 Office 365 中以檢視有關惡意程式碼、 垃圾郵件和規則偵測](https://go.microsoft.com/fwlink/p/?LinkID=401102).
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>使用 Excel 報告活頁簿執行報告

您也可以使用 Excel 2013 報告活頁簿檢視向下鑽研功能摘要報告。不過，建議改用增強的 Microsoft 365 系統管理中心報告。Excel 2013 報告活頁簿，計劃未來取代。如需詳細的概觀資訊以及下載和安裝此活頁簿的連結，請參閱[下載] 頁面上](https://go.microsoft.com/fwlink/p/?LinkId=271776)的下列。如需如何使用活頁簿的資訊，請參閱[使用 Excel 報告活頁簿的郵件保護報告](https://go.microsoft.com/fwlink/p/?LinkId=285211)。 
  
### <a name="reporting-using-web-services"></a>使用 Web 服務報告

透過使用 REST/OData Tenant Reporting Web 服務 (可讓您建立自訂報告的程式設計介面) 可同時存取信箱、群組和訊息資料的摘要報告和詳細資料報告。如需詳細資訊，請參閱 [Office 365 報告 Web 服務](https://go.microsoft.com/fwlink/p/?LinkId=287041)。
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a>EAC 中的報告功能和疑難排解工具

您可在 Exchange 系統管理中心中使用下列報告功能和疑難排解工具。
  
### <a name="trace-an-email-message"></a>追蹤電子郵件訊息

郵件追蹤功能可在電子郵件訊息通過 Exchange Online 服務時，讓您以系統管理員的身分跟隨。它可以協助您判斷服務是否已接收、拒絕、延遲或傳遞目標電子郵件訊息。此舉可讓您有效回答使用者的問題和疑難排解郵件流程問題，減少了需要連絡技術支援尋求協助的需求。
  
> [!IMPORTANT]
> 若要疑難排解一般問題和趨勢，請使用報告工具以取得此類資料。對於需要訊息詳細資料的單點細節，請使用郵件追蹤工具。 
  
如需有關郵件追蹤功能的詳細資訊，請參閱[追蹤電子郵件訊息](https://go.microsoft.com/fwlink/p/?LinkId=271777)。
  
### <a name="auditing-reports"></a>稽核報告

您可以使用稽核記錄來追蹤系統管理員所做的特定變更，藉以疑難排解組態問題，以及協助您符合法規、規範和訴訟需求。Exchange Online 提供了兩種稽核記錄：
  
- 系統管理員稽核記錄記錄記錄由系統管理員執行的任何動作。這種記錄可以協助您疑難排解組態問題，或識別安全性相關或規範符合性相關問題的原因。 
    
- 「信箱稽核記錄」會記錄信箱擁有者以外人員存取信箱的行為。這種記錄可以協助您判斷存取信箱的人員以及他們進行的動作。 
    
如需有關稽核記錄的詳細資訊，請參閱[稽核報告](https://go.microsoft.com/fwlink/p/?LinkId=271779)。
  
### <a name="unified-messaging-reports"></a>整合通訊報告

您可以在 Exchange Online 組織中使用這些報告來監控和疑難排解整合通訊 (UM)。如需詳細資訊，請參閱[執行語音信箱通話報告](https://go.microsoft.com/fwlink/p/?LinkId=287042)。
  
## <a name="feature-availability"></a>功能可用性

若要檢視 Office 365 計劃、獨立選項和內部部署解決方案中的功能可用性，請參閱 [Exchange Online 服務說明](exchange-online-service-description.md)。
  

