---
title: 權限
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-permissions
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7803d7c0-93e6-43a2-b2a4-3a39abe25500
description: Microsoft Exchange Online 使用角色型存取控制 (RBAC) 模式，讓組織管理員可以準確地控制哪些使用者與 IT 員工可在服務中作業。例如，如果法務人員負責信箱搜尋要求，系統管理員可以透過 RBAC 將管理功能委派給法務人員。Exchange Online 使用相同的 RBAC 框架作為 Microsoft Exchange Server 2013。
ms.openlocfilehash: 9f7cad7587d3700971a9cedaf38a20161f203c01
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/07/2019
ms.locfileid: "30468130"
---
# <a name="permissions"></a><span data-ttu-id="bb300-105">權限</span><span class="sxs-lookup"><span data-stu-id="bb300-105">Permissions</span></span>

<span data-ttu-id="bb300-p102">Microsoft Exchange Online 使用角色型存取控制 (RBAC) 模式，讓組織管理員可以準確地控制哪些使用者與 IT 員工可在服務中作業。例如，如果法務人員負責信箱搜尋要求，系統管理員可以透過 RBAC 將管理功能委派給法務人員。Exchange Online 使用相同的 RBAC 框架作為 Microsoft Exchange Server 2013。</span><span class="sxs-lookup"><span data-stu-id="bb300-p102">Microsoft Exchange Online uses a Role Based Access Control (RBAC) model to allow organization administrators to finely control what users and IT employees can do in the service. For example, if a compliance officer is responsible for mailbox search requests, the administrator can delegate this administrative feature to the officer through RBAC. Exchange Online uses the same RBAC framework as Microsoft Exchange Server 2013.</span></span> 
  
<span data-ttu-id="bb300-p103">在其最高階層中，RBAC 由管理角色、管理角色群組和管理角色指派原則構成。以下各節提供有關每個 RBAC 元件的詳細資訊。</span><span class="sxs-lookup"><span data-stu-id="bb300-p103">At its highest level, RBAC is made up of management roles, management role groups, and management role assignment policies. The following sections provide more information about each RBAC component.</span></span>
  
<span data-ttu-id="bb300-111">如需有關用於 Exchange Online 的 RBAC 權限模型的詳細資訊，請參閱[權限](https://go.microsoft.com/fwlink/p/?LinkId=271935)。</span><span class="sxs-lookup"><span data-stu-id="bb300-111">For more information about the RBAC permissions model that's used in Exchange Online, see [Permissions](https://go.microsoft.com/fwlink/p/?LinkId=271935).</span></span>
  
## <a name="role-based-permissions"></a><span data-ttu-id="bb300-112">以角色為基礎的權限</span><span class="sxs-lookup"><span data-stu-id="bb300-112">Role-Based permissions</span></span>

<span data-ttu-id="bb300-p104">在 Exchange Online 中，您授與系統管理員和使用者的權限都是以管理角色為基礎。角色定義了系統管理員或使用者所能執行的一組工作。例如，名為  `Mail Recipients` 的管理角色定義某個人可以對一組信箱、連絡人和通訊群組執行的工作。將角色指派給系統管理員或使用者後，該名人員便會獲得此角色所提供的權限。</span><span class="sxs-lookup"><span data-stu-id="bb300-p104">In Exchange Online, the permissions that you grant to administrators and users are based on management roles. A role defines the set of tasks that an administrator or user can perform. For example, a management role called  `Mail Recipients` defines the tasks that someone can perform on a set of mailboxes, contacts, and distribution groups. When a role is assigned to an administrator or user, that person is granted the permissions provided by the role.</span></span> 
  
<span data-ttu-id="bb300-117">角色可分成系統管理角色和使用者角色兩種類型：</span><span class="sxs-lookup"><span data-stu-id="bb300-117">There are two types of roles, administrative roles and end-user roles:</span></span>
  
- <span data-ttu-id="bb300-118">**系統管理角色** 您可以使用負責管理 Exchange Online 組織某個部分 (例如收件者、伺服器或資料庫) 的角色群組，將這些角色包含的權限指派給系統管理員或專家使用者。</span><span class="sxs-lookup"><span data-stu-id="bb300-118">**Administrative roles** These roles contain permissions that can be assigned to administrators or specialist users by using role groups that manage a part of the Exchange Online organization, such as recipients, servers, or databases.</span></span> 
    
- <span data-ttu-id="bb300-p105">**使用者角色** 這些角色是利用角色指派原則來指派，可以讓使用者管理其專屬信箱與擁有之通訊群組的各個層面。使用者角色是以前置詞  `My` 作為開頭。</span><span class="sxs-lookup"><span data-stu-id="bb300-p105">**End-user roles** These roles, assigned by using role assignment policies, enable users to manage aspects of their own mailboxes and distribution groups that they own. End-user roles begin with the prefix  `My`.</span></span>
    
<span data-ttu-id="bb300-p106">角色是透過讓角色指派對象能夠使用 Cmdlet 的方式，授與系統管理員和使用者執行工作的權限。由於 Exchange 系統管理中心 (EMC) 和 Exchange 管理命令介面會使用 Cmdlet 管理 Exchange Online，因此授與 Cmdlet 存取權即可授與管理員或使用者在每個 Exchange Online 管理介面中執行工作的權限。</span><span class="sxs-lookup"><span data-stu-id="bb300-p106">Roles give administrators and users permissions to perform tasks by making cmdlets available to those who are assigned the roles. Because the Exchange admin center (EAC) and Exchange Management Shell use cmdlets to manage Exchange Online, granting access to a cmdlet gives the administrator or user permission to perform the task in each of the Exchange Online management interfaces.</span></span>
  
<span data-ttu-id="bb300-p107">Microsoft Online Service 的角色型權限以兩種方式與 Exchange Online RBAC 重疊。第一種為 Microsoft Online 的全域管理員或服務管理員會自動指派給 Exchange Online 的組織管理角色群組。第二種為 Microsoft Online 的服務中心管理員會自動指派給 Exchange Online 的服務中心角色群組。此外，兩種安全性模式為分別管理。</span><span class="sxs-lookup"><span data-stu-id="bb300-p107">The role-based permissions for Microsoft Online Services overlap with those of Exchange Online RBAC in two ways. First, users who are Global Administrators or Service Administrators in Microsoft Online are automatically assigned to the Organization Management role group in Exchange Online. Second, users who are Help Desk Administrators in Microsoft Online are automatically assigned to the Help Desk role group in Exchange Online. Otherwise, the two security models are managed separately.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="bb300-127">部分可在 Microsoft Exchange Server 2013 內部部署版本上使用的角色可能無法在 Exchange Online 中使用。</span><span class="sxs-lookup"><span data-stu-id="bb300-127">Some roles available in the on-premises version of Microsoft Exchange Server 2013 may not be available in Exchange Online.</span></span> 
  
<span data-ttu-id="bb300-128">如需有關 Exchange Online 權限的詳細資訊，請參閱[以角色為基礎的權限](https://go.microsoft.com/fwlink/p/?LinkId=271936)。</span><span class="sxs-lookup"><span data-stu-id="bb300-128">For more information about permissions in Exchange Online, see [Role-Based Permissions](https://go.microsoft.com/fwlink/p/?LinkId=271936).</span></span>
  
## <a name="role-groups"></a><span data-ttu-id="bb300-129">角色群組</span><span class="sxs-lookup"><span data-stu-id="bb300-129">Role groups</span></span>

<span data-ttu-id="bb300-p108">「管理角色群組」將管理角色與系統管理員群組或專家使用者產生關聯。系統管理員管理更廣泛的 Exchange Online 組織或收件者組態。專家使用者管理 Exchange Online 的特定功能，例如規範或者具有受限的管理能力，如服務中心成員，但不具有廣泛的管理權限。角色群組通常與啟用系統管理員和專家使用者的系統管理角色產生關聯，以便管理其組織和收件者的組態。例如，系統管理員是否可管理收件者或使用信箱探索功能，是使用角色群組來控制。</span><span class="sxs-lookup"><span data-stu-id="bb300-p108">Management role groups associate management roles to a group of administrators or specialist users. Administrators manage a broad Exchange Online organization or recipient configuration. Specialist users manage the specific features of Exchange Online, such as compliance, or they may have limited management abilities, such as Help desk members, but aren't given broad administrative rights. Role groups typically associate administrative management roles that enable administrators and specialist users to manage the configuration of their organization and recipients. For example, whether administrators can manage recipients or use mailbox discovery features is controlled by using role groups.</span></span> 
  
> [!IMPORTANT]
> <span data-ttu-id="bb300-135">部分可在 Microsoft Exchange Server 2013 內部部署版本上使用的角色群組可能無法在 Exchange Online 中使用。</span><span class="sxs-lookup"><span data-stu-id="bb300-135">Some role groups available in the on-premises version of Microsoft Exchange Server 2013 may not be available in Exchange Online.</span></span> 
  
<span data-ttu-id="bb300-136">如需有關角色群組的詳細資訊，請參閱[角色群組和角色指派原則](https://go.microsoft.com/fwlink/p/?LinkId=271937)。</span><span class="sxs-lookup"><span data-stu-id="bb300-136">For more information about role groups, see [Role groups and role assignment policies](https://go.microsoft.com/fwlink/p/?LinkId=271937).</span></span>
  
## <a name="role-assignment-policies"></a><span data-ttu-id="bb300-137">角色指派原則</span><span class="sxs-lookup"><span data-stu-id="bb300-137">Role assignment policies</span></span>

<span data-ttu-id="bb300-p109">管理角色指派原則會建立一般使用者管理角色和使用者的關聯。角色指派原則由控制使用者可以使用其信箱或通訊群組，執行哪些工作的角色所組成。這些角色不能管理與使用者沒有直接關聯的功能。當您建立角色指派原則，您便定義使用者可以使用其信箱執行的每一件工作。例如，角色指派原則可讓使用者設定顯示名稱、設定語音信箱和設定收件匣規則。其他角色指派原則，可讓使用者變更地址、使用文字郵件和設定通訊群組。包含系統管理員在內的每一位使用者都有一個 Exchange Online 信箱，預設會指定角色指派原則。您可以決定預設應指派哪一個角色指派原則、選擇應包含哪一個預設角色指派原則、覆寫某些信箱的預設值，或不指派預設的任何角色指派原則。</span><span class="sxs-lookup"><span data-stu-id="bb300-p109">Management role assignment policies associate end-user management roles to users. Role assignment policies consist of roles that control what users can do with their mailboxes or distribution groups. These roles don't allow management of features that aren't directly associated with the user. When you create a role assignment policy, you define everything a user can do with his or her mailbox. For example, a role assignment policy might allow a user to set the display name, set up voice mail, and configure Inbox rules. Another role assignment policy might allow a user to change the address, use text messaging, and set up distribution groups. Every user with an Exchange Online mailbox, including administrators, is given a role assignment policy by default. You can decide which role assignment policy should be assigned by default, choose what the default role assignment policy should include, override the default for certain mailboxes, or not assign any role assignment policies by default.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="bb300-146">部分可在 Microsoft Exchange Server 2013 內部部署版本上使用的角色指派可能無法在 Exchange Online 中使用。</span><span class="sxs-lookup"><span data-stu-id="bb300-146">Some role assignments available in the on-premises version of Microsoft Exchange Server 2013 may not be available in Exchange Online.</span></span> 
  
<span data-ttu-id="bb300-147">如需有關角色指派原則的詳細資訊，請參閱[角色群組和角色指派原則](https://go.microsoft.com/fwlink/p/?LinkId=271937)。</span><span class="sxs-lookup"><span data-stu-id="bb300-147">For more information about role assignment policies, see [Role groups and role assignment policies](https://go.microsoft.com/fwlink/p/?LinkId=271937).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="bb300-148">功能可用性</span><span class="sxs-lookup"><span data-stu-id="bb300-148">Feature Availability</span></span>

<span data-ttu-id="bb300-149">若要檢視 Office 365 計劃、獨立選項和內部部署解決方案中的功能可用性，請參閱 [Exchange Online 服務說明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="bb300-149">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

