---
title: 高可用性和業務連續性
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-high-availability-and-business-continuity
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7b03465e-3b9c-4500-8956-a83377f4c2c3
description: Microsoft Exchange Online 提供組織的電子郵件基礎結構的廣泛保留和復原支援。 其中包括在資料中心複寫信箱，以及還原已刪除信箱和已刪除郵件的能力。
ms.openlocfilehash: e205f26bfa611e388cc22557db98eeb84505ef9c
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173678"
---
# <a name="high-availability-and-business-continuity"></a>高可用性和業務連續性

Microsoft Exchange Online 提供組織的電子郵件基礎結構的廣泛保留和復原支援。 其中包括在資料中心複寫信箱，以及還原已刪除信箱和已刪除郵件的能力。
  
## <a name="mailbox-replication-at-data-centers"></a>在資料中心複寫信箱

Exchange Online 信箱在各 Microsoft 資料中心內持續複寫至多重資料庫複本，藉此在本機訊息基礎結構故障時提供資料還原功能。若是大規模的失敗，則會啟動服務連續性管理程序。
  
如需有關 Microsoft 如何保護資料的詳細資訊，請參閱 [Office 365 信任中心r](https://go.microsoft.com/fwlink/p/?LinkId=299135)。如果您使用 21Vianet 運作的 Office 365，請參閱 [21Vianet 信任中心](https://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl)。
  
## <a name="deleted-mailbox-recovery"></a>復原已刪除的信箱

管理員可以使用 Microsoft 365 系統管理中心刪除 Exchange Online 信箱，以刪除對應的使用者帳戶或移除 Exchange Online 授權，或是使用遠端 Windows PowerShell 中的 **Remove-Mailbox** Cmdlet 來刪除。 信箱刪除之後，Exchange Online 預設會保留該信箱及其內容 30 天。 30 天後，信箱將無法復原。 復原的信箱包含所有儲存在信箱內遭到刪除的資料。 系統管理員可以使用 Microsoft 365 系統管理中心，在保留期間內復原已刪除的信箱。 若要復原已刪除的信箱，系統管理員必須還原對應的使用者帳戶，或將 Exchange Online 授權重新指派給使用者帳戶。 如需詳細資訊，請參閱 [刪除或還原 Exchange Online 中的使用者信箱](/exchange/recipients-in-exchange-online/delete-or-restore-mailboxes).
  
## <a name="deleted-item-recovery"></a>復原已刪除的項目

Exchange Online 可讓使用者還原已從任何電子郵件資料夾中刪除的專案，包括「刪除的郵件」資料夾。 郵件被刪除後，會保留在使用者的 [刪除的郵件] 資料夾中。 在使用者將它手動移除或保留原則將它自動移除之前，它會一直保留在該處。 系統管理員可以在 EAC 中或使用遠端 Windows PowerShell 自訂保留原則。
  
郵件從 [刪除的郵件] 資料夾中被移除後，會在 [可復原的項目] 資料夾中額外保留 14 天，然後才會永久移除，但是系統管理員可使用遠端 Windows PowerShell 將此天數增加，最多可達 30 天。 在此期間內，使用者可以使用 Outlook 網頁版或 Outlook 中的 [復原刪除的郵件] 功能來復原專案。 了解如何[變更已刪除郵件的保留期間](/exchange/recipients-in-exchange-online/manage-user-mailboxes/change-deleted-item-retention)。
  
如果使用者已從 [可復原的項目] 資料夾中手動清除郵件，則系統管理員可以透過遠端 Windows PowerShell 使用「單一項目復原」功能，在一樣的保留期間內復原郵件。建立信箱時，預設會啟用「單一項目復原」。若要深入了解，請參閱[啟用或停用信箱的單一項目復原](/exchange/recipients-in-exchange-online/manage-user-mailboxes/enable-or-disable-single-item-recovery)。
  
若要將郵件保留在 [可復原的項目] 資料夾 30 天以上，組織可以實作更長期的電子郵件保留或以時間為基礎的就地保留功能。深入了解如何[將信箱設為就地保留](/exchange/security-and-compliance/in-place-and-litigation-holds)。
  
## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱 [Exchange Online 服務說明](exchange-online-service-description.md)。
