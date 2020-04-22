---
title: 收件者、網域和公司管理
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: Microsoft Exchange Online Protection （EOP）提供數種方式來管理您的收件者、網域和公司資訊。 以系統管理員身分，您可以在 Exchange 系統管理中心（EAC）內執行某些管理工作，並驗證在 Microsoft 365 系統管理中心中執行的其他管理工作。
ms.openlocfilehash: dcd039eab77c1b9df638df5ac3a3e5f6373e852d
ms.sourcegitcommit: 7a68dc894dde0d06fab014c56914a78aa8cda847
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/21/2020
ms.locfileid: "43640261"
---
# <a name="recipient-domain-and-company-management"></a>收件者、網域和公司管理

Microsoft Exchange Online Protection （EOP）提供數種方式來管理您的收件者、網域和公司資訊。 以系統管理員身分，您可以在 Exchange 系統管理中心（EAC）內執行某些管理工作，並驗證在 Microsoft 365 系統管理中心中執行的其他管理工作。
  
尋找所有 EOP 功能的相關資訊嗎？ 請參閱[Exchange Online Protection 服務說明](exchange-online-protection-service-description.md)。
  
## <a name="mail-recipients"></a>Mail recipients

郵件收件者可分類為郵件使用者或群組，而且可以透過目錄同步作業進行管理 (在 EAC 中直接進行，或透過遠端 Windows PowerShell 進行)。 如果您管理內部部署的收件者，則必須執行目錄同步處理，才能在 EAC 中反映郵件收件者。 只在 Microsoft 365 系統管理中心內管理的使用者無法在 EAC 中查看，但可在 EAC 中的系統管理員角色群組中新增或移除成員資格。 如需 EOP 中收件者的詳細資訊，請參閱 [EOP 中的收件者](https://go.microsoft.com/fwlink/p/?LinkId=280011)。
  
## <a name="admin-role-group-permissions"></a>Admin role group permissions

在 EOP 中，您僅可設定系統管理角色。可在 EAC 中直接從預設系統管理角色群組新增及移除使用者。無法自訂 RBAC。如需詳細資訊，請參閱[在 EOP 中管理系統管理角色群組權限](https://go.microsoft.com/fwlink/p/?LinkId=282238)。
  
## <a name="domain-management"></a>網域管理

受管理的網域就是受 EOP 保護的網域。 可在 EAC 中檢視受管理網域，並編輯網域類型。 網域布建和管理發生在 Microsoft 365 系統管理中心，而且變更會反映在 EAC 中。 如需詳細資訊，請參閱[在 EOP 中檢視或編輯受管理的網域](https://go.microsoft.com/fwlink/p/?LinkId=282239)。
  
## <a name="match-subdomains"></a>符合子網域

在 EOP 中，您可以啟用受管理網域之子網域的郵件流程。如需詳細資訊，請參閱[在 EOP 中啟用子網域的電子郵件流程](https://go.microsoft.com/fwlink/p/?LinkId=397213)。 
  
## <a name="directory-based-edge-blocking-dbeb"></a>目錄架構邊緣封鎖 (DBEB)

目錄架構邊緣封鎖功能可讓您拒絕服務網路周邊的無效收件者的郵件。 DBEB 可讓系統管理員將擁有郵件功能的收件者新增至 Microsoft，並封鎖所有傳送至 Microsoft 未出現之電子郵件地址的郵件。 如果郵件傳送至 Microsoft 中有效的電子郵件地址，郵件會繼續進行其他服務篩選層（反惡意程式碼、反垃圾郵件、傳輸規則）。 如果地址不存在，則服務會先封鎖郵件，再進行篩選，並將未傳遞回報 (NDR) 傳送給寄件者，通知他們未傳遞其郵件。 
  
需要進行使用者和網域設定才能啟用 DBEB。如需詳細資訊，請參閱[使用目錄架構邊緣封鎖拒絕傳送給無效收件者的郵件](https://go.microsoft.com/fwlink/p/?LinkId=390676)。
  
## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online Protection 服務說明](exchange-online-protection-service-description.md)。
