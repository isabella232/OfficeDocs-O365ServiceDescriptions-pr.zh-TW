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
description: Microsoft Exchange Online Protection (EOP) 提供數種方法來管理您的收件者、 網域和公司資訊。身為管理員，您可以執行 Exchange 系統管理中心 (EAC) 內特定管理工作，並確認在 Microsoft Office 365 系統管理中心中執行其他管理工作。
ms.openlocfilehash: 17a87a85611dc286e3d19eaeefe04466a1ac62d0
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035398"
---
# <a name="recipient-domain-and-company-management"></a><span data-ttu-id="f3708-104">收件者、網域和公司管理</span><span class="sxs-lookup"><span data-stu-id="f3708-104">Recipient, Domain, and Company Management</span></span>

<span data-ttu-id="f3708-p102">Microsoft Exchange Online Protection (EOP) 提供數種方法來管理您的收件者、 網域和公司資訊。身為管理員，您可以執行 Exchange 系統管理中心 (EAC) 內特定管理工作，並確認在 Microsoft Office 365 系統管理中心中執行其他管理工作。</span><span class="sxs-lookup"><span data-stu-id="f3708-p102">Microsoft Exchange Online Protection (EOP) offers several means of managing your recipient, domain, and company information. As an administrator, you can perform certain management tasks within the Exchange admin center (EAC), and verify other management tasks performed in the Microsoft Office 365 admin center.</span></span>
  
<span data-ttu-id="f3708-p103">尋找所有 EOP 功能的相關資訊嗎？請參閱 [Exchange Online Protection 服務說明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="f3708-p103">Looking for information about all EOP features? See the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="mail-recipients"></a><span data-ttu-id="f3708-109">收件者</span><span class="sxs-lookup"><span data-stu-id="f3708-109">Mail recipients</span></span>
<span data-ttu-id="f3708-110"><a name="BKMK_mailrecipients"> </a></span><span class="sxs-lookup"><span data-stu-id="f3708-110"></span></span>

<span data-ttu-id="f3708-p104">郵件收件者可分類為郵件使用者或群組，而且可以透過目錄同步作業進行管理 (在 EAC 中直接進行，或透過遠端 Windows PowerShell 進行)。如果您管理內部部署的收件者，則必須執行目錄同步處理，才能在 EAC 中反映郵件收件者。僅在 Office 365 管理中心內管理的使用者不會顯示於 EAC 中，但可在 EAC 系統管理員角色群組的成員資格中新增或移除。如需 EOP 中收件者的詳細資訊，請參閱 [EOP 中的收件者](https://go.microsoft.com/fwlink/p/?LinkId=280011)。</span><span class="sxs-lookup"><span data-stu-id="f3708-p104">Mail recipients are categorized as mail users or groups and can be managed through directory synchronization, directly in the EAC, or via remote Windows PowerShell. If you're managing your recipients on-premises, you must run directory synchronization in order for your mail recipients to be reflected in the EAC. Users managed solely in the Office 365 admin center aren't viewable in the EAC, but they can be added to or removed from membership in an administrator role group in the EAC. For more information about recipients in EOP, see [Recipients in EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).</span></span>
  
## <a name="admin-role-group-permissions"></a><span data-ttu-id="f3708-115">系統管理角色群組權限</span><span class="sxs-lookup"><span data-stu-id="f3708-115">Admin role group permissions</span></span>
<span data-ttu-id="f3708-116"><a name="BKMK_adminrolegrouppermissions"> </a></span><span class="sxs-lookup"><span data-stu-id="f3708-116"></span></span>

<span data-ttu-id="f3708-p105">在 EOP 中，您僅可設定系統管理角色。可在 EAC 中直接從預設系統管理角色群組新增及移除使用者。無法自訂 RBAC。如需詳細資訊，請參閱[在 EOP 中管理系統管理角色群組權限](https://go.microsoft.com/fwlink/p/?LinkId=282238)。</span><span class="sxs-lookup"><span data-stu-id="f3708-p105">In EOP, you can configure administrative roles only. Users can be added and removed from default admin role groups directly in the EAC. No RBAC customization is available. For more information, see [Manage Admin Role Group Permissions in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).</span></span>
  
## <a name="domain-management"></a><span data-ttu-id="f3708-121">網域管理</span><span class="sxs-lookup"><span data-stu-id="f3708-121">Domain management</span></span>
<span data-ttu-id="f3708-122"><a name="BKMK_domainmanagement"> </a></span><span class="sxs-lookup"><span data-stu-id="f3708-122"></span></span>

<span data-ttu-id="f3708-p106">受管理的網域就是受 EOP 保護的網域。可在 EAC 中檢視受管理網域，並編輯網域類型。網域佈建及管理是在 Office 365 系統管理中心進行，而變更會反映在 EAC 中。如需詳細資訊，請參閱[在 EOP 中檢視或編輯受管理的網域](https://go.microsoft.com/fwlink/p/?LinkId=282239)。</span><span class="sxs-lookup"><span data-stu-id="f3708-p106">Managed domains are domains that are protected by EOP. Managed domains can be viewed and domain types can be edited in the EAC. Domain provisioning and management occurs in the Office 365 admin center and changes are reflected in the EAC. For more information, see [View or Edit Managed Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span></span>
  
## <a name="match-subdomains"></a><span data-ttu-id="f3708-127">符合子網域</span><span class="sxs-lookup"><span data-stu-id="f3708-127">Match subdomains</span></span>
<span data-ttu-id="f3708-128"><a name="BKMK_EOP_Match_Subdomains"> </a></span><span class="sxs-lookup"><span data-stu-id="f3708-128"></span></span>

<span data-ttu-id="f3708-p107">在 EOP 中，您可以啟用受管理網域之子網域的郵件流程。如需詳細資訊，請參閱[在 EOP 中啟用子網域的電子郵件流程](https://go.microsoft.com/fwlink/p/?LinkId=397213)。</span><span class="sxs-lookup"><span data-stu-id="f3708-p107">In EOP, you can enable mail flow to subdomains of a managed domain. For more information, see [Enable Email Flow for Subdomains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213).</span></span> 
  
## <a name="directory-based-edge-blocking-dbeb"></a><span data-ttu-id="f3708-131">目錄架構邊緣封鎖 (DBEB)</span><span class="sxs-lookup"><span data-stu-id="f3708-131">Directory Based Edge Blocking (DBEB)</span></span>
<span data-ttu-id="f3708-132"><a name="BKMK_DBEB"> </a></span><span class="sxs-lookup"><span data-stu-id="f3708-132"></span></span>

<span data-ttu-id="f3708-p108">目錄架構邊緣封鎖功能可讓您拒絕服務網路周邊的無效收件者的郵件。DBEB 可讓系統管理員將啟用郵件功能的使用者新增至 Office 365，並將傳送至未顯示於 Office 365 中電子郵件地址的所有郵件加以封鎖。如果郵件傳送至顯示於 Office 365 中的有效電子郵件地址，則郵件會繼續通過其餘的服務篩選層 (反惡意軟體、反垃圾郵件、傳輸規則)。如果地址不存在，則服務會先封鎖郵件，再進行篩選，並將未傳遞回報 (NDR) 傳送給寄件者，通知他們未傳遞其郵件。</span><span class="sxs-lookup"><span data-stu-id="f3708-p108">The Directory Based Edge Blocking feature lets you reject messages for invalid recipients at the service network perimeter. DBEB lets admins add mail-enabled recipients to Office 365 and block all messages sent to email addresses that aren't present in Office 365. If a message is sent to a valid email address present in Office 365, the message continues through the rest of the service filtering layers (anti-malware, anti-spam, transport rules). If the address is not present, the service blocks the message before filtering even occurs, and a non-delivery report (NDR) is sent to the sender informing them that their message was not delivered.</span></span> 
  
<span data-ttu-id="f3708-p109">需要進行使用者和網域設定才能啟用 DBEB。如需詳細資訊，請參閱[使用目錄架構邊緣封鎖拒絕傳送給無效收件者的郵件](https://go.microsoft.com/fwlink/p/?LinkId=390676)。</span><span class="sxs-lookup"><span data-stu-id="f3708-p109">Enabling DBEB requires some user and domain configuration. For more information, see [Use Directory Based Edge Blocking to Reject Messages Sent to Invalid Recipients](https://go.microsoft.com/fwlink/p/?LinkId=390676).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="f3708-139">功能可用性</span><span class="sxs-lookup"><span data-stu-id="f3708-139">Feature Availability</span></span>
<span data-ttu-id="f3708-140"><a name="BKMK_DBEB"> </a></span><span class="sxs-lookup"><span data-stu-id="f3708-140"></span></span>

<span data-ttu-id="f3708-141">若要檢視 Office 365 計劃、獨立選項和內部部署解決方案中的功能可用性，請參閱 [Exchange Online Protection 服務說明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="f3708-141">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  

