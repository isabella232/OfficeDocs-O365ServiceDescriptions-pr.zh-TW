---
title: 收件者、網域和公司管理
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: Microsoft Exchange Online Protection (EOP) 提供數種方法來管理您的收件者、 網域和公司資訊。身為管理員，您可以執行 Exchange 系統管理中心 (EAC) 內特定管理工作，並確認在 Microsoft 365 系統管理中心中執行其他管理工作。
ms.openlocfilehash: fcae2c3ad93b977fb197089e2c8809b74ada7bd7
ms.sourcegitcommit: 4abe1be8a63406e8a8c1a4a69f95386906ea1499
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 02/22/2019
ms.locfileid: "30210326"
---
# <a name="recipient-domain-and-company-management"></a>收件者、網域和公司管理

Microsoft Exchange Online Protection (EOP) 提供數種方法來管理您的收件者、 網域和公司資訊。身為管理員，您可以執行 Exchange 系統管理中心 (EAC) 內特定管理工作，並確認在 Microsoft 365 系統管理中心中執行其他管理工作。
  
尋找所有 EOP 功能的相關資訊嗎？請參閱 [Exchange Online Protection 服務說明](exchange-online-protection-service-description.md)。
  
## <a name="mail-recipients"></a>收件者
<a name="BKMK_mailrecipients"> </a>

郵件收件者可分類為 「 郵件使用者或群組並可透過目錄同步處理，直接在 EAC 中，或透過遠端 Windows PowerShell 進行管理。如果您正在管理收件者在內部，您必須反映在 EAC 中您郵件收件者的順序執行目錄同步處理。管理關係 Microsoft 365 系統管理中心中的使用者都可檢視在 EAC 中，但可以加入或移除在 EAC 中系統管理員角色群組的成員資格。如需在 EOP 中的收件者的詳細資訊，請參閱[Recipients in EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011)。
  
## <a name="admin-role-group-permissions"></a>系統管理角色群組權限
<a name="BKMK_adminrolegrouppermissions"> </a>

在 EOP 中，您僅可設定系統管理角色。可在 EAC 中直接從預設系統管理角色群組新增及移除使用者。無法自訂 RBAC。如需詳細資訊，請參閱[在 EOP 中管理系統管理角色群組權限](https://go.microsoft.com/fwlink/p/?LinkId=282238)。
  
## <a name="domain-management"></a>網域管理
<a name="BKMK_domainmanagement"> </a>

受管理的網域是 EOP 來保護的網域。可檢視受管理的網域，且可在 EAC 中編輯網域類型。網域佈建和管理發生在 Microsoft 365 系統管理中心並變更便會反映在 EAC 中。如需詳細資訊，請參閱[檢視] 或 [Edit Managed Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239)。
  
## <a name="match-subdomains"></a>符合子網域
<a name="BKMK_EOP_Match_Subdomains"> </a>

在 EOP 中，您可以啟用受管理網域之子網域的郵件流程。如需詳細資訊，請參閱[在 EOP 中啟用子網域的電子郵件流程](https://go.microsoft.com/fwlink/p/?LinkId=397213)。 
  
## <a name="directory-based-edge-blocking-dbeb"></a>目錄架構邊緣封鎖 (DBEB)
<a name="BKMK_DBEB"> </a>

目錄架構邊緣封鎖功能可讓您拒絕服務網路周邊的無效收件者的郵件。DBEB 可讓系統管理員將啟用郵件功能的使用者新增至 Office 365，並將傳送至未顯示於 Office 365 中電子郵件地址的所有郵件加以封鎖。如果郵件傳送至顯示於 Office 365 中的有效電子郵件地址，則郵件會繼續通過其餘的服務篩選層 (反惡意軟體、反垃圾郵件、傳輸規則)。如果地址不存在，則服務會先封鎖郵件，再進行篩選，並將未傳遞回報 (NDR) 傳送給寄件者，通知他們未傳遞其郵件。 
  
需要進行使用者和網域設定才能啟用 DBEB。如需詳細資訊，請參閱[使用目錄架構邊緣封鎖拒絕傳送給無效收件者的郵件](https://go.microsoft.com/fwlink/p/?LinkId=390676)。
  
## <a name="feature-availability"></a>功能可用性
<a name="BKMK_DBEB"> </a>

若要檢視 Office 365 計劃、獨立選項和內部部署解決方案中的功能可用性，請參閱 [Exchange Online Protection 服務說明](exchange-online-protection-service-description.md)。
  

