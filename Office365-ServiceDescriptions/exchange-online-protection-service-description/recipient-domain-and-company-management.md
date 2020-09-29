---
title: Exchange Online Protection 中的收件者、網域和公司管理
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: 若要瞭解 Microsoft Exchange Online Protection (EOP) 中的收件者、網域和公司管理，請閱讀本文。
ms.openlocfilehash: 7be36ecbf065eb7bc1ce2c890ac84a6fea565c68
ms.sourcegitcommit: e342174df76128430dfc8c971716da5c4b2942ac
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/28/2020
ms.locfileid: "48294119"
---
# <a name="recipient-domain-and-company-management-in-exchange-online-protection"></a><span data-ttu-id="7fc96-103">Exchange Online Protection 中的收件者、網域和公司管理</span><span class="sxs-lookup"><span data-stu-id="7fc96-103">Recipient, domain, and company management in Exchange Online Protection</span></span>

<span data-ttu-id="7fc96-104">Microsoft Exchange Online Protection (EOP) 提供數種方式來管理您的收件者、網域和公司資訊。</span><span class="sxs-lookup"><span data-stu-id="7fc96-104">Microsoft Exchange Online Protection (EOP) offers several means of managing your recipient, domain, and company information.</span></span> <span data-ttu-id="7fc96-105">以管理員身分，您可以在 Exchange 系統管理中心內執行某些管理工作 (EAC) ，並確認在 Microsoft 365 系統管理中心中執行的其他管理工作。</span><span class="sxs-lookup"><span data-stu-id="7fc96-105">As an administrator, you can perform certain management tasks within the Exchange admin center (EAC), and verify other management tasks performed in the Microsoft 365 admin center.</span></span>
  
<span data-ttu-id="7fc96-106">尋找所有 EOP 功能的相關資訊嗎？</span><span class="sxs-lookup"><span data-stu-id="7fc96-106">Looking for information about all EOP features?</span></span> <span data-ttu-id="7fc96-107">請參閱 [Exchange Online Protection 服務說明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="7fc96-107">See the [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="mail-recipients"></a><span data-ttu-id="7fc96-108">Mail recipients</span><span class="sxs-lookup"><span data-stu-id="7fc96-108">Mail recipients</span></span>

<span data-ttu-id="7fc96-109">郵件收件者可分類為郵件使用者或群組，而且可以透過目錄同步作業進行管理 (在 EAC 中直接進行，或透過遠端 Windows PowerShell 進行)。</span><span class="sxs-lookup"><span data-stu-id="7fc96-109">Mail recipients are categorized as mail users or groups and can be managed through directory synchronization, directly in the EAC, or via remote Windows PowerShell.</span></span> <span data-ttu-id="7fc96-110">如果您管理內部部署的收件者，則必須執行目錄同步處理，才能在 EAC 中反映郵件收件者。</span><span class="sxs-lookup"><span data-stu-id="7fc96-110">If you're managing your recipients on-premises, you must run directory synchronization in order for your mail recipients to be reflected in the EAC.</span></span> <span data-ttu-id="7fc96-111">只在 Microsoft 365 系統管理中心內管理的使用者無法在 EAC 中查看，但可在 EAC 中的系統管理員角色群組中新增或移除成員資格。</span><span class="sxs-lookup"><span data-stu-id="7fc96-111">Users managed solely in the Microsoft 365 admin center aren't viewable in the EAC, but they can be added to or removed from membership in an administrator role group in the EAC.</span></span> <span data-ttu-id="7fc96-112">如需 EOP 中收件者的詳細資訊，請參閱 [EOP 中的收件者](https://go.microsoft.com/fwlink/p/?LinkId=280011)。</span><span class="sxs-lookup"><span data-stu-id="7fc96-112">For more information about recipients in EOP, see [Recipients in EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).</span></span>
  
## <a name="admin-role-group-permissions"></a><span data-ttu-id="7fc96-113">Admin role group permissions</span><span class="sxs-lookup"><span data-stu-id="7fc96-113">Admin role group permissions</span></span>

<span data-ttu-id="7fc96-p104">在 EOP 中，您僅可設定系統管理角色。可在 EAC 中直接從預設系統管理角色群組新增及移除使用者。無法自訂 RBAC。如需詳細資訊，請參閱[在 EOP 中管理系統管理角色群組權限](https://go.microsoft.com/fwlink/p/?LinkId=282238)。</span><span class="sxs-lookup"><span data-stu-id="7fc96-p104">In EOP, you can configure administrative roles only. Users can be added and removed from default admin role groups directly in the EAC. No RBAC customization is available. For more information, see [Manage Admin Role Group Permissions in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).</span></span>
  
## <a name="domain-management"></a><span data-ttu-id="7fc96-118">網域管理</span><span class="sxs-lookup"><span data-stu-id="7fc96-118">Domain management</span></span>

<span data-ttu-id="7fc96-119">受管理的網域就是受 EOP 保護的網域。</span><span class="sxs-lookup"><span data-stu-id="7fc96-119">Managed domains are domains that are protected by EOP.</span></span> <span data-ttu-id="7fc96-120">可在 EAC 中檢視受管理網域，並編輯網域類型。</span><span class="sxs-lookup"><span data-stu-id="7fc96-120">Managed domains can be viewed and domain types can be edited in the EAC.</span></span> <span data-ttu-id="7fc96-121">網域布建和管理發生在 Microsoft 365 系統管理中心，而且變更會反映在 EAC 中。</span><span class="sxs-lookup"><span data-stu-id="7fc96-121">Domain provisioning and management occurs in the Microsoft 365 admin center and changes are reflected in the EAC.</span></span> <span data-ttu-id="7fc96-122">如需詳細資訊，請參閱[在 EOP 中檢視或編輯受管理的網域](https://go.microsoft.com/fwlink/p/?LinkId=282239)。</span><span class="sxs-lookup"><span data-stu-id="7fc96-122">For more information, see [View or Edit Managed Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span></span>
  
## <a name="match-subdomains"></a><span data-ttu-id="7fc96-123">符合子網域</span><span class="sxs-lookup"><span data-stu-id="7fc96-123">Match subdomains</span></span>

<span data-ttu-id="7fc96-p106">在 EOP 中，您可以啟用受管理網域之子網域的郵件流程。如需詳細資訊，請參閱[在 EOP 中啟用子網域的電子郵件流程](https://go.microsoft.com/fwlink/p/?LinkId=397213)。</span><span class="sxs-lookup"><span data-stu-id="7fc96-p106">In EOP, you can enable mail flow to subdomains of a managed domain. For more information, see [Enable Email Flow for Subdomains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213).</span></span> 
  
## <a name="directory-based-edge-blocking-dbeb"></a><span data-ttu-id="7fc96-126">目錄架構邊緣封鎖 (DBEB)</span><span class="sxs-lookup"><span data-stu-id="7fc96-126">Directory Based Edge Blocking (DBEB)</span></span>

<span data-ttu-id="7fc96-127">目錄架構邊緣封鎖功能可讓您拒絕服務網路周邊的無效收件者的郵件。</span><span class="sxs-lookup"><span data-stu-id="7fc96-127">The Directory Based Edge Blocking feature lets you reject messages for invalid recipients at the service network perimeter.</span></span> <span data-ttu-id="7fc96-128">DBEB 可讓系統管理員將擁有郵件功能的收件者新增至 Microsoft，並封鎖所有傳送至 Microsoft 未出現之電子郵件地址的郵件。</span><span class="sxs-lookup"><span data-stu-id="7fc96-128">DBEB lets admins add mail-enabled recipients to Microsoft and block all messages sent to email addresses that aren't present in Microsoft.</span></span> <span data-ttu-id="7fc96-129">如果郵件傳送至 Microsoft 中的有效電子郵件地址，郵件會繼續進行其他服務篩選層， (反惡意程式碼、反垃圾郵件、傳輸規則) 。</span><span class="sxs-lookup"><span data-stu-id="7fc96-129">If a message is sent to a valid email address present in Microsoft, the message continues through the rest of the service filtering layers (anti-malware, anti-spam, transport rules).</span></span> <span data-ttu-id="7fc96-130">如果地址不存在，則服務會先封鎖郵件，再進行篩選，並將未傳遞回報 (NDR) 傳送給寄件者，通知他們未傳遞其郵件。</span><span class="sxs-lookup"><span data-stu-id="7fc96-130">If the address is not present, the service blocks the message before filtering even occurs, and a non-delivery report (NDR) is sent to the sender informing them that their message was not delivered.</span></span> 
  
<span data-ttu-id="7fc96-p108">需要進行使用者和網域設定才能啟用 DBEB。如需詳細資訊，請參閱[使用目錄架構邊緣封鎖拒絕傳送給無效收件者的郵件](https://go.microsoft.com/fwlink/p/?LinkId=390676)。</span><span class="sxs-lookup"><span data-stu-id="7fc96-p108">Enabling DBEB requires some user and domain configuration. For more information, see [Use Directory Based Edge Blocking to Reject Messages Sent to Invalid Recipients](https://go.microsoft.com/fwlink/p/?LinkId=390676).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="7fc96-133">功能可用性</span><span class="sxs-lookup"><span data-stu-id="7fc96-133">Feature availability</span></span>

<span data-ttu-id="7fc96-134">若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱 [Exchange Online Protection 服務說明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="7fc96-134">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>
