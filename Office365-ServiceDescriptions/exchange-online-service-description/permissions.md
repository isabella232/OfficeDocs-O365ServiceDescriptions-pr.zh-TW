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
description: Microsoft Exchange Online 使用角色型存取控制 (RBAC) 模式，讓組織管理員可以準確地控制哪些使用者與 IT 員工可在服務中作業。例如，如果法務人員負責信箱搜尋要求，系統管理員可以透過 RBAC 將管理功能委派給法務人員。Exchange Online 使用相同的 RBAC 框架作為 Microsoft Exchange Server 2013。
ms.openlocfilehash: 0593c98857a7ce0c487c628018097395d7a5fe50
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132687"
---
# <a name="permissions"></a>權限

Microsoft Exchange Online 使用角色型存取控制 (RBAC) 模式，讓組織管理員可以準確地控制哪些使用者與 IT 員工可在服務中作業。例如，如果法務人員負責信箱搜尋要求，系統管理員可以透過 RBAC 將管理功能委派給法務人員。Exchange Online 使用相同的 RBAC 框架作為 Microsoft Exchange Server 2013。 
  
在其最高階層中，RBAC 由管理角色、管理角色群組和管理角色指派原則構成。以下各節提供有關每個 RBAC 元件的詳細資訊。
  
如需有關用於 Exchange Online 的 RBAC 權限模型的詳細資訊，請參閱[權限](https://go.microsoft.com/fwlink/p/?LinkId=271935)。
  
## <a name="role-based-permissions"></a>角色型權限

在 Exchange Online 中，您授與系統管理員和使用者的權限都是以管理角色為基礎。角色定義了系統管理員或使用者所能執行的一組工作。例如，名為  `Mail Recipients` 的管理角色定義某個人可以對一組信箱、連絡人和通訊群組執行的工作。將角色指派給系統管理員或使用者後，該名人員便會獲得此角色所提供的權限。 
  
角色可分成系統管理角色和使用者角色兩種類型：
  
- **系統管理角色** 您可以使用負責管理 Exchange Online 組織某個部分 (例如收件者、伺服器或資料庫) 的角色群組，將這些角色包含的權限指派給系統管理員或專家使用者。 
    
- **使用者角色**這些角色是使用角色指派原則所指派，讓使用者可以管理自己的信箱和擁有的通訊群組的各個層面。 使用者角色是以前置詞  `My` 作為開頭。
    
角色是透過讓角色指派對象能夠使用 Cmdlet 的方式，授與系統管理員和使用者執行工作的權限。由於 Exchange 系統管理中心 (EMC) 和 Exchange 管理命令介面會使用 Cmdlet 管理 Exchange Online，因此授與 Cmdlet 存取權即可授與管理員或使用者在每個 Exchange Online 管理介面中執行工作的權限。
  
Microsoft Online Service 的角色型權限以兩種方式與 Exchange Online RBAC 重疊。第一種為 Microsoft Online 的全域管理員或服務管理員會自動指派給 Exchange Online 的組織管理角色群組。第二種為 Microsoft Online 的服務中心管理員會自動指派給 Exchange Online 的服務中心角色群組。此外，兩種安全性模式為分別管理。
  
> [!IMPORTANT]
> 部分可在 Microsoft Exchange Server 2013 內部部署版本上使用的角色可能無法在 Exchange Online 中使用。 
  
如需有關 Exchange Online 權限的詳細資訊，請參閱[以角色為基礎的權限](https://go.microsoft.com/fwlink/p/?LinkId=271936)。
  
## <a name="role-groups"></a>角色群組

「管理角色群組」將管理角色與系統管理員群組或專家使用者產生關聯。 系統管理員管理更廣泛的 Exchange Online 組織或收件者組態。 專家使用者管理 Exchange Online 的特定功能，例如規範或者具有受限的管理能力，如服務中心成員，但不具有廣泛的管理權限。 角色群組通常會關聯系統管理角色，讓系統管理員和專家使用者管理其組織和收件者的設定。 例如，系統管理員是否可管理收件者或使用信箱探索功能，是使用角色群組來控制。 
  
> [!IMPORTANT]
> 部分可在 Microsoft Exchange Server 2013 內部部署版本上使用的角色群組可能無法在 Exchange Online 中使用。 
  
如需有關角色群組的詳細資訊，請參閱[角色群組和角色指派原則](https://go.microsoft.com/fwlink/p/?LinkId=271937)。
  
## <a name="role-assignment-policies"></a>角色指派原則

管理角色指派原則會建立一般使用者管理角色和使用者的關聯。角色指派原則由控制使用者可以使用其信箱或通訊群組，執行哪些工作的角色所組成。這些角色不能管理與使用者沒有直接關聯的功能。當您建立角色指派原則，您便定義使用者可以使用其信箱執行的每一件工作。例如，角色指派原則可讓使用者設定顯示名稱、設定語音信箱和設定收件匣規則。其他角色指派原則，可讓使用者變更地址、使用文字郵件和設定通訊群組。包含系統管理員在內的每一位使用者都有一個 Exchange Online 信箱，預設會指定角色指派原則。您可以決定預設應指派哪一個角色指派原則、選擇應包含哪一個預設角色指派原則、覆寫某些信箱的預設值，或不指派預設的任何角色指派原則。
  
> [!IMPORTANT]
> 部分可在 Microsoft Exchange Server 2013 內部部署版本上使用的角色指派可能無法在 Exchange Online 中使用。 
  
如需有關角色指派原則的詳細資訊，請參閱[角色群組和角色指派原則](https://go.microsoft.com/fwlink/p/?LinkId=271937)。
  
## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online 服務說明](exchange-online-service-description.md)。
  

