---
title: Exchange Online 封存中的封存功能
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
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
ms.openlocfilehash: f14d8e5c6acefef6fd08cf8e8edf5f33acb9f9df
ms.sourcegitcommit: 433b170b26fbd9c2e9b0e520adfef6f0804df25a
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 11/08/2018
ms.locfileid: "26215348"
---
# <a name="archive-features-in-exchange-online-archiving"></a>Exchange Online 封存中的封存功能

下列各節說明 Microsoft Exchange Online 封存的封存功能。
  
## <a name="archive-mailbox"></a>封存信箱

Exchange Online Archiving 以封存信箱功能的形式，為使用者提供進階封存功能。封存信箱是一種特殊的信箱，會隨使用者的主要信箱資料夾一起顯示在 Outlook 或 Outlook Web App 中。使用者可以像存取主要信箱一樣來存取封存。此外，使用者可以同時在封存和主要信箱中進行搜尋。
  
系統管理員可以使用 Exchange 系統管理中心 (EAC) 或遠端 Windows PowerShell，為特定使用者啟用封存功能。如需詳細資訊，請參閱[啟用或停用 Exchange Online 中的封存信箱](https://go.microsoft.com/fwlink/p/?LinkId=404425)。
  
> [!IMPORTANT]
>  禁止透過日誌記錄、傳輸規則或自動轉寄規則，將郵件複製到 Exchange Online Archiving信箱中進行封存。 >  使用者的封存信箱僅供該使用者使用。Microsoft 保留在使用者封存信箱中用來儲存其他使用者之封存資料的執行個體中拒絕不受限封存的權限。 
  
### <a name="move-messages-to-exchange-online-archiving"></a>將郵件移至 Exchange Online 封存

使用者可以拖訊息從.pst 檔案至封存，輕鬆線上存取。使用者也可以移動電子郵件項目從主要信箱的封存信箱自動使用封存原則，減少大小及增進效能的主要信箱。此行為會不同於 Exchange Hosted Archive 可只會建立在封存中的每個郵件的次要複本，而其中一個案例中，可達到保留需求。 
  
### <a name="import-data-to-the-archive"></a>將資料匯入封存

使用者可以使用下列方式將資料匯入封存：
  
- 使用 Outlook 的「匯入及匯出」精靈，從 .pst 檔案匯入資料。
    
- 將電子郵件訊息從 .pst 檔案拖曳至封存中。
    
- 將電子郵件訊息從主要信箱拖曳至封存中。
    
- 讓封存原則根據電子郵件訊息的已存留時間，自動將郵件移出主要信箱。如需詳細資訊，請參閱[保留標記和保留原則](https://go.microsoft.com/fwlink/p/?LinkId=314153)。
    
> [!NOTE]
> 系統管理員也可以使用 Office 365 匯入服務，將 .pst 檔案匯入到使用者的雲端型封存信箱。如需詳細資訊，請參閱[使用網路上傳將 PST 檔案匯入 Office 365](https://go.microsoft.com/fwlink/p/?linkid=823074)。 
  
## <a name="deleted-item-recovery"></a>復原已刪除的項目

使用者可以在封存中還原已從任何電子郵件資料夾中刪除的郵件。郵件遭刪除時，會保留在封存的 [刪除的郵件] 資料夾中。該郵件會一直留在該處，直到遭使用者手動移除或遭保留原則自動移除為止。
  
已從封存的 [刪除項目] 資料夾中移除項目之後，此項目保留在封存的可復原的項目] 資料夾中其他的 14 天內之前要永久移除。使用者可以復原使用 Microsoft Outlook 或 Outlook Web App 中**復原刪除的郵件**功能這些項目。 
  
如果使用者已從 [可復原的項目] 資料夾中手動清除某個郵件，則系統管理員可以透過名為「單一項目復原」的功能，同樣在這 14 天內復原郵件。此功能可讓系統管理員搜尋多個信箱來尋找已清除的郵件，然後使用  `Search-Mailbox` Windows PowerShell Cmdlet 將郵件從探索信箱移至使用者的信箱。如需詳細資訊，請參閱 [為信箱啟用或停用單一項目復原](https://go.microsoft.com/fwlink/p/?LinkId=314155)。
  
> [!NOTE]
>  單一項目復原期間預設為 14 天，但在某些情況下，您可加以自訂。 >  如果系統管理員已讓使用者的信箱處於就地保留和訴訟資料暫留狀態，就會無限期保留已清除的郵件，不適用 14 天的期間。 
  
## <a name="deleted-mailbox-recovery"></a>復原已刪除的信箱

當系統管理員從內部部署 Exchange Server 中刪除使用者時，使用者的封存也會遭到刪除。如果需要復原已刪除的封存信箱，Office 365 支援小組可以執行此復原動作。復原的封存信箱將包含遭刪除時所有儲存在該信箱內的郵件。
  
> [!IMPORTANT]
> 自刪除使用者的信箱起，系統管理員有 30 天的時間可以要求復原封存信箱。超過 30 天後，就無法復原封存信箱。 
  
## <a name="mailbox-service-redundancy"></a>信箱服務備援

在 Exchange Online 封存的封存信箱會複寫到多個資料庫副本，分散在各地的 Microsoft 資料中心，以提供資料還原功能訊息的基礎結構失敗的情況下。大規模失敗起始營運持續力管理。 
  
## <a name="feature-availability"></a>功能可用性

若要檢視 Office 365 計劃、獨立選項和內部部署解決方案中的功能可用性，請參閱 [Exchange Online 封存服務說明](exchange-online-archiving-service-description.md)。
  
