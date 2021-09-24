---
title: Exchange Online Protection 中的收件者、網域和公司管理
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: 請閱讀本文以瞭解 Microsoft Exchange Online Protection (EOP) 中的收件者、網域和公司管理。
ms.openlocfilehash: 928f94153f91c5067bc5e7ea80525a36cc8e7de3
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/24/2021
ms.locfileid: "59672226"
---
# <a name="recipient-domain-and-company-management-in-exchange-online-protection"></a>Exchange Online Protection 中的收件者、網域和公司管理

Microsoft Exchange OnlineProtection (EOP) 提供數種方式來管理您的收件者、網域和公司資訊。 您可以以系統管理員身分執行 Exchange 系統管理中心內的某些管理工作 (EAC) ，並確認 Microsoft 365 系統管理中心中執行的其他管理工作。
  
尋找所有 EOP 功能的相關資訊嗎？ 請參閱[Exchange Online Protection 服務描述](exchange-online-protection-service-description.md)。
  
## <a name="mail-recipients"></a>Mail recipients

郵件收件者可分類為郵件使用者或群組，而且可以透過目錄同步作業進行管理 (在 EAC 中直接進行，或透過遠端 Windows PowerShell 進行)。 如果您管理內部部署的收件者，則必須執行目錄同步處理，才能在 EAC 中反映郵件收件者。 僅在 Microsoft 365 系統管理中心中管理的使用者不會在 eac 中查看，但可在 eac 中的系統管理員角色群組中新增或移除成員資格。 如需 EOP 中收件者的詳細資訊，請參閱 [EOP 中的收件者](/microsoft-365/security/office-365-security/manage-recipients-in-eop)。
  
## <a name="admin-role-group-permissions"></a>Admin role group permissions

在 EOP 中，您僅可設定系統管理角色。可在 EAC 中直接從預設系統管理角色群組新增及移除使用者。無法自訂 RBAC。如需詳細資訊，請參閱[在 EOP 中管理系統管理角色群組權限](/microsoft-365/security/office-365-security/manage-admin-role-group-permissions-in-eop)。
  
## <a name="domain-management"></a>網域管理

受管理的網域就是受 EOP 保護的網域。 可在 EAC 中檢視受管理網域，並編輯網域類型。 網域布建和管理發生在 Microsoft 365 系統管理中心中，而且變更會反映在 EAC 中。 如需詳細資訊，請參閱[在 EOP 中檢視或編輯受管理的網域](/microsoft-365/security/office-365-security/exchange-online-protection-overview)。
  
## <a name="match-subdomains"></a>符合子網域

在 EOP 中，您可以啟用受管理網域之子網域的郵件流程。如需詳細資訊，請參閱[在 EOP 中啟用子網域的電子郵件流程](/microsoft-365/security/office-365-security/mail-flow-in-eop)。 
  
## <a name="directory-based-edge-blocking-dbeb"></a>目錄架構邊緣封鎖 (DBEB)

目錄架構邊緣封鎖功能可讓您拒絕服務網路周邊的無效收件者的郵件。 DBEB 可讓系統管理員將擁有郵件功能的收件者新增至 Microsoft，並封鎖所有傳送至 Microsoft 未出現之電子郵件地址的郵件。 如果郵件傳送至 Microsoft 中的有效電子郵件地址，郵件會繼續進行其他服務篩選層， (反惡意程式碼、反垃圾郵件、傳輸規則) 。 如果地址不存在，則服務會先封鎖郵件，再進行篩選，並將未傳遞回報 (NDR) 傳送給寄件者，通知他們未傳遞其郵件。 
  
需要進行使用者和網域設定才能啟用 DBEB。如需詳細資訊，請參閱[使用目錄架構邊緣封鎖拒絕傳送給無效收件者的郵件](/exchange/mail-flow-best-practices/use-directory-based-edge-blocking)。
  
## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online Protection 服務描述](exchange-online-protection-service-description.md)。