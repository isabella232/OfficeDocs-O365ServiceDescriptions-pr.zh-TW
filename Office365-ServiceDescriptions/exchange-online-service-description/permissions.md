---
title: 權限
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-permissions
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7803d7c0-93e6-43a2-b2a4-3a39abe25500
description: Microsoft Exchange Online uses a Role Based Access Control (RBAC) model to allow organization administrators to finely control what users and IT employees can do in the service. For example, if a compliance officer is responsible for mailbox search requests, the administrator can delegate this administrative feature to the officer through RBAC. Exchange Online uses the same RBAC framework as Microsoft Exchange Server 2013.
ms.openlocfilehash: 0593c98857a7ce0c487c628018097395d7a5fe50
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132687"
---
# <a name="permissions"></a>權限

Microsoft Exchange Online uses a Role Based Access Control (RBAC) model to allow organization administrators to finely control what users and IT employees can do in the service. For example, if a compliance officer is responsible for mailbox search requests, the administrator can delegate this administrative feature to the officer through RBAC. Exchange Online uses the same RBAC framework as Microsoft Exchange Server 2013. 
  
At its highest level, RBAC is made up of management roles, management role groups, and management role assignment policies. The following sections provide more information about each RBAC component.
  
如需有關用於 Exchange Online 的 RBAC 權限模型的詳細資訊，請參閱[權限](https://go.microsoft.com/fwlink/p/?LinkId=271935)。
  
## <a name="role-based-permissions"></a>角色型權限

In Exchange Online, the permissions that you grant to administrators and users are based on management roles. A role defines the set of tasks that an administrator or user can perform. For example, a management role called  `Mail Recipients` defines the tasks that someone can perform on a set of mailboxes, contacts, and distribution groups. When a role is assigned to an administrator or user, that person is granted the permissions provided by the role. 
  
角色可分成系統管理角色和使用者角色兩種類型：
  
- **系統管理角色** 您可以使用負責管理 Exchange Online 組織某個部分 (例如收件者、伺服器或資料庫) 的角色群組，將這些角色包含的權限指派給系統管理員或專家使用者。 
    
- **使用者角色**這些角色是使用角色指派原則所指派，讓使用者可以管理自己的信箱和擁有的通訊群組的各個層面。 使用者角色是以前置詞  `My` 作為開頭。
    
Roles give administrators and users permissions to perform tasks by making cmdlets available to those who are assigned the roles. Because the Exchange admin center (EAC) and Exchange Management Shell use cmdlets to manage Exchange Online, granting access to a cmdlet gives the administrator or user permission to perform the task in each of the Exchange Online management interfaces.
  
The role-based permissions for Microsoft Online Services overlap with those of Exchange Online RBAC in two ways. First, users who are Global Administrators or Service Administrators in Microsoft Online are automatically assigned to the Organization Management role group in Exchange Online. Second, users who are Help Desk Administrators in Microsoft Online are automatically assigned to the Help Desk role group in Exchange Online. Otherwise, the two security models are managed separately.
  
> [!IMPORTANT]
> 部分可在 Microsoft Exchange Server 2013 內部部署版本上使用的角色可能無法在 Exchange Online 中使用。 
  
如需有關 Exchange Online 權限的詳細資訊，請參閱[以角色為基礎的權限](https://go.microsoft.com/fwlink/p/?LinkId=271936)。
  
## <a name="role-groups"></a>角色群組

「管理角色群組」將管理角色與系統管理員群組或專家使用者產生關聯。 系統管理員管理更廣泛的 Exchange Online 組織或收件者組態。 專家使用者管理 Exchange Online 的特定功能，例如規範或者具有受限的管理能力，如服務中心成員，但不具有廣泛的管理權限。 角色群組通常會關聯系統管理角色，讓系統管理員和專家使用者管理其組織和收件者的設定。 例如，系統管理員是否可管理收件者或使用信箱探索功能，是使用角色群組來控制。 
  
> [!IMPORTANT]
> 部分可在 Microsoft Exchange Server 2013 內部部署版本上使用的角色群組可能無法在 Exchange Online 中使用。 
  
如需有關角色群組的詳細資訊，請參閱[角色群組和角色指派原則](https://go.microsoft.com/fwlink/p/?LinkId=271937)。
  
## <a name="role-assignment-policies"></a>角色指派原則

Management role assignment policies associate end-user management roles to users. Role assignment policies consist of roles that control what users can do with their mailboxes or distribution groups. These roles don't allow management of features that aren't directly associated with the user. When you create a role assignment policy, you define everything a user can do with his or her mailbox. For example, a role assignment policy might allow a user to set the display name, set up voice mail, and configure Inbox rules. Another role assignment policy might allow a user to change the address, use text messaging, and set up distribution groups. Every user with an Exchange Online mailbox, including administrators, is given a role assignment policy by default. You can decide which role assignment policy should be assigned by default, choose what the default role assignment policy should include, override the default for certain mailboxes, or not assign any role assignment policies by default.
  
> [!IMPORTANT]
> 部分可在 Microsoft Exchange Server 2013 內部部署版本上使用的角色指派可能無法在 Exchange Online 中使用。 
  
如需有關角色指派原則的詳細資訊，請參閱[角色群組和角色指派原則](https://go.microsoft.com/fwlink/p/?LinkId=271937)。
  
## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online 服務說明](exchange-online-service-description.md)。
  

