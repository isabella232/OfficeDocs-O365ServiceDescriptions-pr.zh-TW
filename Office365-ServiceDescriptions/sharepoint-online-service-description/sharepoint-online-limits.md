---
title: SharePoint 限制
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: 瞭解 Microsoft 365 和獨立方案的 SharePoint 限制。
ms.openlocfilehash: 7c449c12c4dc29784757454223d6b5479fa109b8
ms.sourcegitcommit: 325de2faa5a2f72cd464c957ed867d83b6c28469
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/22/2020
ms.locfileid: "45229639"
---
# <a name="sharepoint-limits"></a>SharePoint 限制

深入瞭解 Microsoft 365 SharePoint 中的服務限制。
  
## <a name="limits-by-plan"></a>依方案的限制 

|||||
|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Microsoft 365 商務基本、商務標準或商務版特優** <br/> |**Microsoft 365 E3 或 E5、Office 365 Enterprise E1、E3 或 E5，或 SharePoint 方案1或2** <br/> | **Microsoft 365 F1 或 F3，Office 365 Enterprise F3** <br/> |
|每個組織的總儲存量<sup>1，2，6</sup> <br/> |每個授權購買 1 TB 外加 10 GB<sup>3</sup>  <br/> |每個授權購買 1 TB 外加 10 GB<sup>3</sup> <br/> |1 TB<sup>3</sup> <br/> |
|每個網站最大儲存體（網站集合）<sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|每個組織的網站（網站集合）  <br/> |2000000<sup>6</sup> <br/> |2000000<sup>6</sup> <br/> |2000000<br/> |
|使用者數目  <br/> |最多 300 個  <br/> |1- 500,000<sup>7</sup> <br/> |1- 500,000<sup>7</sup> <br/> |
   
<sup>1</sup> [瞭解如何尋找組織的總數和可用儲存體](/sharepoint/manage-site-collection-storage-limits)。 您可以購買無限的額外 SharePoint 儲存空間。 請參閱＜ [變更您訂閱的儲存空間](/office365/admin/subscriptions-and-billing/add-storage-space)＞。 
<br/><sup>2</sup> 我們建議您監控並定期清空「資源回收筒」。 其使用的儲存空間為組織總儲存量限制的一部分。 
<br/> <sup>3</sup>如果您有 Microsoft 365 訂閱和 Office 365 額外檔案儲存空間，將會新增儲存量。 
<br/> <sup>4</sup>這是單一網站（先前稱為「網站集合」）的儲存量*限制*，而非每個網站所*提供*的儲存量。 此限制適用于所有類型的網站，包括 Office 365 群組連線的小組網站和 OneDrive。 SharePoint 管理員可以[手動設定較低的儲存量限制](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits)。 
<br/> <sup>5</sup> Firstline 工作者無法管理 SharePoint 網站。 
<br/> <sup>6</sup>不包括為每個授權使用者建立的 OneDrive。 
<br/> <sup>7</sup> 如果您有 500,000 位以上的使用者，請連絡 Microsoft 代表。 
  
## <a name="service-limits-for-all-plans"></a>所有方案的服務限制

### <a name="items-in-lists-and-libraries"></a>清單和文件庫中的專案

清單最多可包含30000000個專案，而文件庫最多可以有30000000個檔案和資料夾。 當清單、文件庫或資料夾包含超過100000個專案時，您就無法中斷清單、文件庫或資料夾的許可權繼承。 您也不能重新繼承其上的許可權。 不過，您仍然可以中斷該清單、文件庫或資料夾中個別專案的繼承，直到清單或文件庫中的唯一許可權數目上限（請參閱下一節）。 若要深入瞭解查看大型清單的其他限制，請參閱[管理 Office 365 中的大型清單和文件庫](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784)。 

> [!NOTE]
> 網站上可以擁有的文件庫數目沒有限制。

### <a name="unique-permissions-for-items-in-a-list-or-library"></a>清單或文件庫中專案的特定權限

支援的限制50000是專屬許可權唯一的專案，但是建議的一般限制為5000。 若要變更超過5000的專案，請專屬許可權一次以上的專案。 針對大型清單，設計若盡可能具有少數獨特的許可權。

另一個限制是每個唯一專屬許可權專案5000的角色指派。 

### <a name="file-size-and-file-path-length"></a>檔案大小及檔案路徑長度

100 GB。 附加至清單專案的檔案大小上限為 250 MB。 若要深入瞭解使用新的 OneDrive 同步處理應用程式（OneDrive.exe）時的限制和限制，請參閱[不正確檔案名和檔案類型](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)。

### <a name="moving-and-copying-across-sites"></a>跨網站移動及複製

在單一作業中複製/移動多個檔案具有三項需求： 

- 總檔案大小不得超過 100 GB 
- 不超過30000個檔案
- 每個檔案必須小於 2 GB

### <a name="sync"></a>Sync

**新 OneDrive 同步處理應用**程式-為了獲得最佳效能，建議您在所有已同步處理的文件庫中儲存不超過300000的檔案，即使您是以要求進行，或是只選擇文件庫中的某些資料夾，也能進行同步處理。

**OneDrive 舊版 Business sync app （Groove.exe）** -您最多可以同步處理所有已同步處理的文件庫中的20000個專案。 這包括 OneDrive 文件庫、小組網站程式庫或兩者。 與整體同步處理限制分開時，每個文件庫類型可同步處理的專案數有限制：

   - 您最多可以同步處理 OneDrive 程式庫中的20000個專案。 這包括資料夾及檔案。 
   - 您最多可以同步處理 SharePoint 程式庫中的5000個專案。 這包括資料夾及檔案。 這些是您可以在各種 SharePoint 網站上找到的文件庫，例如小組網站和群組網站、其他人員建立或您從您的網站頁面建立的文件庫。 您可以同步處理多個 SharePoint 文件庫。 您同步處理的任何小組網站也會在所有同步處理的文件庫中，計算全部20000專案限制。

> [!NOTE]
> 如果使用者需要同步處理包含成百上千個檔案的文件庫中的檔案，您可以將資料夾的許可權層級設定為「限制讀取」，以從同步處理應用程式中「隱藏」資料夾。 

### <a name="versions"></a>版本

50000主要版本和511次要版本。

### <a name="sharepoint-groups"></a>SharePoint 群組

使用者可以隸屬于每個網站（網站集合）的5000群組，而每個群組可以有最多5000個使用者。 您最多可以有10000個群組的網站（網站集合）。

> [!NOTE]
> 針對 Azure AD 群組限制，請參閱[AZURE ad 服務限制和限制](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions)，因為這類限制可能會影響公用和私人群組網站成員資格管理。 

### <a name="managed-metadata"></a>受管理的中繼資料

200000術語存放區中的術語，1000全域字片語，1000群組。

### <a name="overall-site-metadata"></a>整體網站中繼資料

每個網站 1000 GB （中繼資料極少會達到此大小）。

### <a name="subsites"></a>式 

每個網站2000個（網站集合）。 我們建議您建立網站，並將其組織成中樞，而不是建立子網站。 如果您使用子網站，建議您限制其編號（特別是在大量 trafficked 網站上）。

### <a name="sharepoint-hosted-applications"></a>主控應用程式 SharePoint

每個組織的20000個實例。

### <a name="people-editing-a-document-at-the-same-time"></a>使用者同時編輯檔

99人員可以同時開啟檔以供編輯。 若超過10位使用者同時編輯檔，其編輯很可能會衝突，而且使用者體驗會逐漸降低。

### <a name="users"></a>使用者

每個網站2000000個（網站集合）。
   
> [!NOTE]
> 您可以邀請 SharePoint 網站的客人數目沒有限制。 如需外部共用的詳細資訊，請參閱[外部共用一覽](/sharepoint/external-sharing-overview)。

## <a name="see-also"></a>請參閱

[SharePoint 的搜尋限制](/sharepoint/search-limits)
