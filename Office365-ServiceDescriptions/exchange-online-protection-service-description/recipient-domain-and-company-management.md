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
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: 請閱讀本文以瞭解 Microsoft Exchange Online Protection (EOP) 中的收件者、網域和公司管理。
ms.openlocfilehash: f58ffe829be839d8321cfc98f331d1836986e293
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652995"
---
# <a name="recipient-domain-and-company-management-in-exchange-online-protection"></a><span data-ttu-id="24676-103">Exchange Online Protection 中的收件者、網域和公司管理</span><span class="sxs-lookup"><span data-stu-id="24676-103">Recipient, domain, and company management in Exchange Online Protection</span></span>

<span data-ttu-id="24676-104">Microsoft Exchange OnlineProtection (EOP) 提供數種方式來管理您的收件者、網域和公司資訊。</span><span class="sxs-lookup"><span data-stu-id="24676-104">Microsoft Exchange Online Protection (EOP) offers several means of managing your recipient, domain, and company information.</span></span> <span data-ttu-id="24676-105">您可以以系統管理員身分執行 Exchange 系統管理中心內的某些管理工作 (EAC) ，並確認 Microsoft 365 系統管理中心中所執行的其他管理工作。</span><span class="sxs-lookup"><span data-stu-id="24676-105">As an administrator, you can perform certain management tasks within the Exchange admin center (EAC), and verify other management tasks performed in the Microsoft 365 admin center.</span></span>
  
<span data-ttu-id="24676-106">尋找所有 EOP 功能的相關資訊嗎？</span><span class="sxs-lookup"><span data-stu-id="24676-106">Looking for information about all EOP features?</span></span> <span data-ttu-id="24676-107">請參閱[Exchange Online Protection 服務描述](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="24676-107">See the [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="mail-recipients"></a><span data-ttu-id="24676-108">Mail recipients</span><span class="sxs-lookup"><span data-stu-id="24676-108">Mail recipients</span></span>

<span data-ttu-id="24676-109">郵件收件者可分類為郵件使用者或群組，而且可以透過目錄同步作業進行管理 (在 EAC 中直接進行，或透過遠端 Windows PowerShell 進行)。</span><span class="sxs-lookup"><span data-stu-id="24676-109">Mail recipients are categorized as mail users or groups and can be managed through directory synchronization, directly in the EAC, or via remote Windows PowerShell.</span></span> <span data-ttu-id="24676-110">如果您管理內部部署的收件者，則必須執行目錄同步處理，才能在 EAC 中反映郵件收件者。</span><span class="sxs-lookup"><span data-stu-id="24676-110">If you're managing your recipients on-premises, you must run directory synchronization in order for your mail recipients to be reflected in the EAC.</span></span> <span data-ttu-id="24676-111">僅在 Microsoft 365 系統管理中心內管理的使用者無法在 eac 中查看，但可在 eac 中的系統管理員角色群組中新增或移除成員資格。</span><span class="sxs-lookup"><span data-stu-id="24676-111">Users managed solely in the Microsoft 365 admin center aren't viewable in the EAC, but they can be added to or removed from membership in an administrator role group in the EAC.</span></span> <span data-ttu-id="24676-112">如需 EOP 中收件者的詳細資訊，請參閱 [EOP 中的收件者](/microsoft-365/security/office-365-security/manage-recipients-in-eop)。</span><span class="sxs-lookup"><span data-stu-id="24676-112">For more information about recipients in EOP, see [Recipients in EOP](/microsoft-365/security/office-365-security/manage-recipients-in-eop).</span></span>
  
## <a name="admin-role-group-permissions"></a><span data-ttu-id="24676-113">Admin role group permissions</span><span class="sxs-lookup"><span data-stu-id="24676-113">Admin role group permissions</span></span>

<span data-ttu-id="24676-p104">在 EOP 中，您僅可設定系統管理角色。可在 EAC 中直接從預設系統管理角色群組新增及移除使用者。無法自訂 RBAC。如需詳細資訊，請參閱[在 EOP 中管理系統管理角色群組權限](/microsoft-365/security/office-365-security/manage-admin-role-group-permissions-in-eop)。</span><span class="sxs-lookup"><span data-stu-id="24676-p104">In EOP, you can configure administrative roles only. Users can be added and removed from default admin role groups directly in the EAC. No RBAC customization is available. For more information, see [Manage Admin Role Group Permissions in EOP](/microsoft-365/security/office-365-security/manage-admin-role-group-permissions-in-eop).</span></span>
  
## <a name="domain-management"></a><span data-ttu-id="24676-118">網域管理</span><span class="sxs-lookup"><span data-stu-id="24676-118">Domain management</span></span>

<span data-ttu-id="24676-119">受管理的網域就是受 EOP 保護的網域。</span><span class="sxs-lookup"><span data-stu-id="24676-119">Managed domains are domains that are protected by EOP.</span></span> <span data-ttu-id="24676-120">可在 EAC 中檢視受管理網域，並編輯網域類型。</span><span class="sxs-lookup"><span data-stu-id="24676-120">Managed domains can be viewed and domain types can be edited in the EAC.</span></span> <span data-ttu-id="24676-121">網域布建和管理會在 Microsoft 365 系統管理中心進行，而且變更會反映在 EAC 中。</span><span class="sxs-lookup"><span data-stu-id="24676-121">Domain provisioning and management occurs in the Microsoft 365 admin center and changes are reflected in the EAC.</span></span> <span data-ttu-id="24676-122">如需詳細資訊，請參閱[在 EOP 中檢視或編輯受管理的網域](/microsoft-365/security/office-365-security/exchange-online-protection-overview)。</span><span class="sxs-lookup"><span data-stu-id="24676-122">For more information, see [View or Edit Managed Domains in EOP](/microsoft-365/security/office-365-security/exchange-online-protection-overview).</span></span>
  
## <a name="match-subdomains"></a><span data-ttu-id="24676-123">符合子網域</span><span class="sxs-lookup"><span data-stu-id="24676-123">Match subdomains</span></span>

<span data-ttu-id="24676-p106">在 EOP 中，您可以啟用受管理網域之子網域的郵件流程。如需詳細資訊，請參閱[在 EOP 中啟用子網域的電子郵件流程](/microsoft-365/security/office-365-security/mail-flow-in-eop)。</span><span class="sxs-lookup"><span data-stu-id="24676-p106">In EOP, you can enable mail flow to subdomains of a managed domain. For more information, see [Enable Email Flow for Subdomains in EOP](/microsoft-365/security/office-365-security/mail-flow-in-eop).</span></span> 
  
## <a name="directory-based-edge-blocking-dbeb"></a><span data-ttu-id="24676-126">目錄架構邊緣封鎖 (DBEB)</span><span class="sxs-lookup"><span data-stu-id="24676-126">Directory Based Edge Blocking (DBEB)</span></span>

<span data-ttu-id="24676-127">目錄架構邊緣封鎖功能可讓您拒絕服務網路周邊的無效收件者的郵件。</span><span class="sxs-lookup"><span data-stu-id="24676-127">The Directory Based Edge Blocking feature lets you reject messages for invalid recipients at the service network perimeter.</span></span> <span data-ttu-id="24676-128">DBEB 可讓系統管理員將擁有郵件功能的收件者新增至 Microsoft，並封鎖所有傳送至 Microsoft 未出現之電子郵件地址的郵件。</span><span class="sxs-lookup"><span data-stu-id="24676-128">DBEB lets admins add mail-enabled recipients to Microsoft and block all messages sent to email addresses that aren't present in Microsoft.</span></span> <span data-ttu-id="24676-129">如果郵件傳送至 Microsoft 中的有效電子郵件地址，郵件會繼續進行其他服務篩選層， (反惡意程式碼、反垃圾郵件、傳輸規則) 。</span><span class="sxs-lookup"><span data-stu-id="24676-129">If a message is sent to a valid email address present in Microsoft, the message continues through the rest of the service filtering layers (anti-malware, anti-spam, transport rules).</span></span> <span data-ttu-id="24676-130">如果地址不存在，則服務會先封鎖郵件，再進行篩選，並將未傳遞回報 (NDR) 傳送給寄件者，通知他們未傳遞其郵件。</span><span class="sxs-lookup"><span data-stu-id="24676-130">If the address is not present, the service blocks the message before filtering even occurs, and a non-delivery report (NDR) is sent to the sender informing them that their message was not delivered.</span></span> 
  
<span data-ttu-id="24676-p108">需要進行使用者和網域設定才能啟用 DBEB。如需詳細資訊，請參閱[使用目錄架構邊緣封鎖拒絕傳送給無效收件者的郵件](/exchange/mail-flow-best-practices/use-directory-based-edge-blocking)。</span><span class="sxs-lookup"><span data-stu-id="24676-p108">Enabling DBEB requires some user and domain configuration. For more information, see [Use Directory Based Edge Blocking to Reject Messages Sent to Invalid Recipients](/exchange/mail-flow-best-practices/use-directory-based-edge-blocking).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="24676-133">功能可用性</span><span class="sxs-lookup"><span data-stu-id="24676-133">Feature availability</span></span>

<span data-ttu-id="24676-134">若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online Protection 服務描述](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="24676-134">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>