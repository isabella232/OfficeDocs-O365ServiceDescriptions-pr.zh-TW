---
title: Exchange Online 封存中的封存功能
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- archive-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 38abfbd2-5aaa-444a-a431-5e71c566f3e4
description: 下列各節說明 Microsoft Exchange Online 封存的封存功能。
ms.openlocfilehash: 7f6b5863d94862644fb90d1d0d85c3765ad05e9b
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131527"
---
# <a name="archive-features-in-exchange-online-archiving"></a>Exchange Online 封存中的封存功能

下列各節說明 Microsoft Exchange Online 封存的封存功能。
  
## <a name="archive-mailbox"></a>封存信箱

Exchange Online Archiving 以封存信箱功能的形式，為使用者提供進階封存功能。 封存信箱是一種特殊的信箱，會出現在 Outlook 或網頁型 Outlook 中使用者的主要信箱資料夾旁。 使用者可以像存取主要信箱一樣來存取封存。 此外，使用者可以同時在封存和主要信箱中進行搜尋。
  
Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users. For more information, see [Enable or disable archive mailboxes in Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes).
  
> [!IMPORTANT]
>  禁止透過日誌記錄、傳輸規則或自動轉寄規則，將郵件複製到 Exchange Online Archiving信箱中進行封存。 <br/>
>  使用者的封存信箱僅供該使用者使用。 Microsoft 保留在使用者的封存信箱用來儲存其他使用者的封存資料或其他不適當用途的情況下，拒絕無限封存的權利。
  
### <a name="move-messages-to-exchange-online-archiving"></a>將郵件移至 Exchange Online 封存

使用者可以將郵件從 .pst 檔案拖放至封存中，以方便進行線上存取。 使用者也可以使用「封存原則」，自動將電子郵件項目從主要信箱中移至封存信箱中，以減少主要信箱的大小並改善其效能。 
  
### <a name="import-data-to-the-archive"></a>將資料匯入封存

使用者可以使用下列方式將資料匯入封存：
  
- 使用 Outlook 的「匯入及匯出」精靈，從 .pst 檔案匯入資料。
    
- 將電子郵件訊息從 .pst 檔案拖曳至封存中。
    
- 將電子郵件訊息從主要信箱拖曳至封存中。
    
- Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages. For more information, see [Retention Tags and Retention Policies](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).
    
> [!NOTE]
> Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes. For more information, see [Use network upload to import PST files to Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files). 
  
## <a name="deleted-item-recovery"></a>復原已刪除的項目

Users can restore items they have deleted from any email folder in their archive. When an item is deleted, it is kept in the archive's Deleted Items folder. It remains there until it is manually removed by the user, or automatically removed by retention policies.
  
After an item has been removed from the archive's Deleted Items folder, the item is kept in the archive's Recoverable Items folder for an additional 14 days before being permanently removed. 使用者可以使用 Microsoft Outlook 或 web 上的 Outlook 中的 [**復原刪除的郵件**] 功能來復原這些專案。 
  
If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery. This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes. For more information, see [Enable or disable single item recovery for a mailbox](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).
  
> [!NOTE]
>  單一項目復原期間預設為 14 天，但在某些情況下，您可加以自訂。 <br/>
>  如果系統管理員將使用者的信箱設為 In-Place 保留或訴訟資料暫留狀態，就會無限期保留清除的專案，且不會套用14天的視窗。 
  
## <a name="deleted-mailbox-recovery"></a>復原已刪除的信箱

當系統管理員從內部部署 Exchange Server 中刪除使用者時，使用者的封存也會遭到刪除。 如果需要復原已刪除的封存信箱，則 Microsoft 支援小組可以執行此修復。 復原的封存信箱將包含遭刪除時所有儲存在該信箱內的郵件。
  
> [!IMPORTANT]
> Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery. After 30 days, the archive mailbox is not recoverable. 
  
## <a name="mailbox-service-redundancy"></a>信箱服務備援

Exchange Online Archiving 中的封存信箱會複寫至多個資料庫副本 (位於不同地區的 Microsoft 資料中心內)，以防萬一訊息基礎結構故障，還有辦法可以還原資料。 對於大規模的故障，則有永續營運管理程序。 
  
## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online 封存服務說明](exchange-online-archiving-service-description.md)。
  
