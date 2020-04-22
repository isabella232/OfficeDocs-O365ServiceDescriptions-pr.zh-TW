---
title: Exchange Online 封存中的封存功能
ms.author: sharik
author: skjerland
manager: mnirkhe
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
ms.openlocfilehash: cc4b6cb6f0aa817f3b0369f2bf3517fd480a11e8
ms.sourcegitcommit: 7a68dc894dde0d06fab014c56914a78aa8cda847
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/21/2020
ms.locfileid: "43639831"
---
# <a name="archive-features-in-exchange-online-archiving"></a><span data-ttu-id="0026a-103">Exchange Online 封存中的封存功能</span><span class="sxs-lookup"><span data-stu-id="0026a-103">Archive features in Exchange Online Archiving</span></span>

<span data-ttu-id="0026a-104">下列各節說明 Microsoft Exchange Online 封存的封存功能。</span><span class="sxs-lookup"><span data-stu-id="0026a-104">The following sections describe the archive features of Microsoft Exchange Online Archiving.</span></span>
  
## <a name="archive-mailbox"></a><span data-ttu-id="0026a-105">封存信箱</span><span class="sxs-lookup"><span data-stu-id="0026a-105">Archive mailbox</span></span>

<span data-ttu-id="0026a-106">Exchange Online Archiving 以封存信箱功能的形式，為使用者提供進階封存功能。</span><span class="sxs-lookup"><span data-stu-id="0026a-106">Exchange Online Archiving offers users advanced archiving capabilities with the archive mailbox feature.</span></span> <span data-ttu-id="0026a-107">封存信箱是一種特殊的信箱，會出現在 Outlook 或網頁型 Outlook 中使用者的主要信箱資料夾旁。</span><span class="sxs-lookup"><span data-stu-id="0026a-107">An archive mailbox is a specialized mailbox that appears alongside the users' primary mailbox folders in Outlook or Outlook on the web.</span></span> <span data-ttu-id="0026a-108">使用者可以像存取主要信箱一樣來存取封存。</span><span class="sxs-lookup"><span data-stu-id="0026a-108">Users can access the archive in the same way that they access their primary mailboxes.</span></span> <span data-ttu-id="0026a-109">此外，使用者可以同時在封存和主要信箱中進行搜尋。</span><span class="sxs-lookup"><span data-stu-id="0026a-109">In addition, they can search both their archives and primary mailboxes.</span></span>
  
<span data-ttu-id="0026a-p102">系統管理員可以使用 Exchange 系統管理中心 (EAC) 或遠端 Windows PowerShell，為特定使用者啟用封存功能。如需詳細資訊，請參閱[啟用或停用 Exchange Online 中的封存信箱](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)。</span><span class="sxs-lookup"><span data-stu-id="0026a-p102">Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users. For more information, see [Enable or disable archive mailboxes in Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes).</span></span>
  
> [!IMPORTANT]
>  <span data-ttu-id="0026a-112">禁止透過日誌記錄、傳輸規則或自動轉寄規則，將郵件複製到 Exchange Online Archiving信箱中進行封存。</span><span class="sxs-lookup"><span data-stu-id="0026a-112">Using journaling, transport rules, or auto-forwarding rules to copy messages to Exchange Online Archiving for the purposes of archiving is not permitted.</span></span> <br/>
>  <span data-ttu-id="0026a-113">使用者的封存信箱僅供該使用者使用。</span><span class="sxs-lookup"><span data-stu-id="0026a-113">A user's archive mailbox is intended for just that user.</span></span> <span data-ttu-id="0026a-114">Microsoft 保留在使用者的封存信箱用來儲存其他使用者的封存資料或其他不適當用途的情況下，拒絕無限封存的權利。</span><span class="sxs-lookup"><span data-stu-id="0026a-114">Microsoft reserves the right to deny unlimited archiving in instances where a user's archive mailbox is used to store archive data for other users or in other cases of inappropriate use.</span></span>
  
### <a name="move-messages-to-exchange-online-archiving"></a><span data-ttu-id="0026a-115">將郵件移至 Exchange Online 封存</span><span class="sxs-lookup"><span data-stu-id="0026a-115">Move messages to Exchange Online Archiving</span></span>

<span data-ttu-id="0026a-116">使用者可以將郵件從 .pst 檔案拖放至封存中，以方便進行線上存取。</span><span class="sxs-lookup"><span data-stu-id="0026a-116">Users can drag and drop messages from .pst files into the archive, for easy online access.</span></span> <span data-ttu-id="0026a-117">使用者也可以使用「封存原則」，自動將電子郵件項目從主要信箱中移至封存信箱中，以減少主要信箱的大小並改善其效能。</span><span class="sxs-lookup"><span data-stu-id="0026a-117">Users can also move email items from the primary mailbox to the archive mailbox automatically, using Archive Polices, to reduce the size and improve the performance of the primary mailbox.</span></span> 
  
### <a name="import-data-to-the-archive"></a><span data-ttu-id="0026a-118">將資料匯入封存</span><span class="sxs-lookup"><span data-stu-id="0026a-118">Import data to the archive</span></span>

<span data-ttu-id="0026a-119">使用者可以使用下列方式將資料匯入封存：</span><span class="sxs-lookup"><span data-stu-id="0026a-119">Users can import data to the archive in the following ways:</span></span>
  
- <span data-ttu-id="0026a-120">使用 Outlook 的「匯入及匯出」精靈，從 .pst 檔案匯入資料。</span><span class="sxs-lookup"><span data-stu-id="0026a-120">Import data from a .pst file using Outlook's Import and Export wizard.</span></span>
    
- <span data-ttu-id="0026a-121">將電子郵件訊息從 .pst 檔案拖曳至封存中。</span><span class="sxs-lookup"><span data-stu-id="0026a-121">Drag email messages from .pst files into the archive.</span></span>
    
- <span data-ttu-id="0026a-122">將電子郵件訊息從主要信箱拖曳至封存中。</span><span class="sxs-lookup"><span data-stu-id="0026a-122">Drag email messages from the primary mailbox into the archive.</span></span>
    
- <span data-ttu-id="0026a-p106">讓封存原則根據電子郵件訊息的已存留時間，自動將郵件移出主要信箱。如需詳細資訊，請參閱[保留標記和保留原則](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies)。</span><span class="sxs-lookup"><span data-stu-id="0026a-p106">Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages. For more information, see [Retention Tags and Retention Policies](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).</span></span>
    
> [!NOTE]
> <span data-ttu-id="0026a-p107">系統管理員也可以使用 Office 365 匯入服務，將 .pst 檔案匯入到使用者的雲端型封存信箱。如需詳細資訊，請參閱[使用網路上傳將 PST 檔案匯入 Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files)。</span><span class="sxs-lookup"><span data-stu-id="0026a-p107">Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes. For more information, see [Use network upload to import PST files to Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span></span> 
  
## <a name="deleted-item-recovery"></a><span data-ttu-id="0026a-127">復原已刪除的項目</span><span class="sxs-lookup"><span data-stu-id="0026a-127">Deleted item recovery</span></span>

<span data-ttu-id="0026a-p108">使用者可以在封存中還原已從任何電子郵件資料夾中刪除的郵件。郵件遭刪除時，會保留在封存的 [刪除的郵件] 資料夾中。該郵件會一直留在該處，直到遭使用者手動移除或遭保留原則自動移除為止。</span><span class="sxs-lookup"><span data-stu-id="0026a-p108">Users can restore items they have deleted from any email folder in their archive. When an item is deleted, it is kept in the archive's Deleted Items folder. It remains there until it is manually removed by the user, or automatically removed by retention policies.</span></span>
  
<span data-ttu-id="0026a-131">After an item has been removed from the archive's Deleted Items folder, the item is kept in the archive's Recoverable Items folder for an additional 14 days before being permanently removed.</span><span class="sxs-lookup"><span data-stu-id="0026a-131">After an item has been removed from the archive's Deleted Items folder, the item is kept in the archive's Recoverable Items folder for an additional 14 days before being permanently removed.</span></span> <span data-ttu-id="0026a-132">使用者可以使用 Microsoft Outlook 或 web 上的 Outlook 中的 [**復原刪除的郵件**] 功能來復原這些專案。</span><span class="sxs-lookup"><span data-stu-id="0026a-132">Users can recover these items using the **Recover Deleted Items** feature in Microsoft Outlook or Outlook on the web.</span></span> 
  
<span data-ttu-id="0026a-p110">如果使用者已從 [可復原的項目] 資料夾中手動清除某個郵件，則系統管理員可以透過名為「單一項目復原」的功能，同樣在這 14 天內復原郵件。此功能可讓系統管理員搜尋多個信箱來尋找已清除的郵件，然後使用  `Search-Mailbox` Windows PowerShell Cmdlet 將郵件從探索信箱移至使用者的信箱。如需詳細資訊，請參閱 [為信箱啟用或停用單一項目復原](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files)。</span><span class="sxs-lookup"><span data-stu-id="0026a-p110">If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery. This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes. For more information, see [Enable or disable single item recovery for a mailbox](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="0026a-136">單一項目復原期間預設為 14 天，但在某些情況下，您可加以自訂。</span><span class="sxs-lookup"><span data-stu-id="0026a-136">The Single Item Recovery period is 14 days by default, but it can be customized in some circumstances.</span></span> <br/>
>  <span data-ttu-id="0026a-137">如果系統管理員將使用者的信箱設為 In-Place 保留或訴訟資料暫留狀態，就會無限期保留清除的專案，且不會套用14天的視窗。</span><span class="sxs-lookup"><span data-stu-id="0026a-137">If an administrator has placed a user's mailbox on In-Place Hold or Litigation Hold, purged items are retained indefinitely and the 14-day window does not apply.</span></span> 
  
## <a name="deleted-mailbox-recovery"></a><span data-ttu-id="0026a-138">復原已刪除的信箱</span><span class="sxs-lookup"><span data-stu-id="0026a-138">Deleted mailbox recovery</span></span>

<span data-ttu-id="0026a-139">當系統管理員從內部部署 Exchange Server 中刪除使用者時，使用者的封存也會遭到刪除。</span><span class="sxs-lookup"><span data-stu-id="0026a-139">When administrators delete users from the on-premises Exchange Server, the users' archives are also deleted.</span></span> <span data-ttu-id="0026a-140">如果需要復原已刪除的封存信箱，則 Microsoft 支援小組可以執行此修復。</span><span class="sxs-lookup"><span data-stu-id="0026a-140">If the deleted archive mailboxes need to be recovered, the Microsoft support team can perform this recovery.</span></span> <span data-ttu-id="0026a-141">復原的封存信箱將包含遭刪除時所有儲存在該信箱內的郵件。</span><span class="sxs-lookup"><span data-stu-id="0026a-141">A recovered archive will contain all of the mail stored in it at the time it was deleted.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="0026a-p113">自刪除使用者的信箱起，系統管理員有 30 天的時間可以要求復原封存信箱。超過 30 天後，就無法復原封存信箱。</span><span class="sxs-lookup"><span data-stu-id="0026a-p113">Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery. After 30 days, the archive mailbox is not recoverable.</span></span> 
  
## <a name="mailbox-service-redundancy"></a><span data-ttu-id="0026a-144">信箱服務備援</span><span class="sxs-lookup"><span data-stu-id="0026a-144">Mailbox service redundancy</span></span>

<span data-ttu-id="0026a-145">Exchange Online Archiving 中的封存信箱會複寫至多個資料庫副本 (位於不同地區的 Microsoft 資料中心內)，以防萬一訊息基礎結構故障，還有辦法可以還原資料。</span><span class="sxs-lookup"><span data-stu-id="0026a-145">Archive mailboxes in Exchange Online Archiving are replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a messaging infrastructure failure.</span></span> <span data-ttu-id="0026a-146">對於大規模的故障，則有永續營運管理程序。</span><span class="sxs-lookup"><span data-stu-id="0026a-146">For large-scale failures, business continuity management is initiated.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="0026a-147">功能可用性</span><span class="sxs-lookup"><span data-stu-id="0026a-147">Feature availability</span></span>

<span data-ttu-id="0026a-148">若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online 封存服務說明](exchange-online-archiving-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="0026a-148">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online Archiving service description](exchange-online-archiving-service-description.md).</span></span>
  
