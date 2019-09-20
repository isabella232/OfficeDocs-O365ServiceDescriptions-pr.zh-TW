---
title: SharePoint Online 限制
ms.author: sharik
author: skjerland
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: 尋找適用於 Office 365 企業版方案及獨立方案的 SharePoint Online 限制。
ms.openlocfilehash: 4ec162de7b5e005a177d0eb2f2122ba46422519c
ms.sourcegitcommit: 0d63d969bf286c3ab2b297867713d41f485ccc07
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/18/2019
ms.locfileid: "37035099"
---
# <a name="sharepoint-online-limits"></a>SharePoint Online 限制 

尋找適用於 Office 365 方案及 SharePoint Online 獨立方案的 SharePoint 限制。
  
## <a name="limits-by-plan"></a>各方案的限制 

|||||
|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商務基本版或商務進階版** <br/> |**Office 365 企業版 E1、E3 或 E5，或 SharePoint Online 方案 1 或 2** <br/> | **Office 365 企業版 F1** <br/> |
|每個組織的儲存體總計<sup>1、2</sup> <br/> |每個購買授權 1 TB 加上 10 GB  <br/> |每個購買授權 1 TB 加上10 GB<sup>3</sup> <br/> |1 TB<sup>3</sup> <br/> |
|每個網站集合的最大儲存體<sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|每個組織的網站集合  <br/> |1 百萬<sup>6</sup> <br/> |1 百萬<sup>6</sup> <br/> |1 百萬<br/> |
|使用者數目  <br/> |最多 300 個  <br/> |1- 500,000<sup>7</sup> <br/> |1- 500,000<sup>7</sup> <br/> |
   
<sup>1</sup> 您可以無限制地購買額外的 SharePoint 儲存體。 請參閱[變更您訂閱的儲存空間](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/add-storage-space)。 
<br/><sup>2</sup> 我們建議您監控並定期清空「資源回收筒」。 其使用的儲存空間也會計入組織的儲存空間上限總額。 
<br/> <sup>3</sup> 如果您有訂閱 Office 365 和 Office 365 額外檔案儲存空間附加元件，儲存空間容量會累加。 
<br/> <sup>4</sup> 這是單一網站集合的儲存空間限制，而非每個網站集合所提供的儲存限制。 這項限制適用於所有類型的網站集合，包括 Office 365 群組連結的小組網站和 OneDrive。 SharePoint 系統管理員可以[手動設定降低儲存體限制](https://docs.microsoft.com/sharepoint/manage-site-collection-storage-limits)。 
<br/> <sup>5</sup> Kiosk 人員無法管理 SharePoint 網站集合。 
<br/> <sup>6</sup> 不包括為每個授權使用者建立的 OneDrive 網站集合。 
<br/> <sup>7</sup> 如果您有 500,000 位以上的使用者，請連絡 Microsoft 代表。 
  
## <a name="service-limits-for-all-plans"></a>所有方案的服務限制

- **清單和文件庫中的項目** - 一份清單最多可有 3 千萬個項目，而一個文件庫最多可有 3 千萬個檔案和資料夾。 100,000 個的項目新增至清單、文件庫或資料夾後，清單、文件庫或資料夾的權限繼承就無法變更。 若要深入了解檢視大型清單的其他限制，請參閱 [管理 Office 365 中的大型清單和文件庫](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784)。 

- **檔案大小及檔案路徑長度** - 15 GB。 附加至清單項目的檔案大小上限為 250 MB。 若要深入了解使用新版 OneDrive 同步處理用戶端 (OneDrive.exe) 的限制之詳細資訊，請參閱 [無效的檔案名稱和檔案類型](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)。

- **移動和複製整個網站集合** - 每個作業 100 GB。 網頁瀏覽器必須保持開啟狀態。

- **同步處理** - 為了獲得最佳效能，我們建議您在所有同步處理文件庫中儲存的檔案不要超過 300,000 個，即使您使用的是檔案隨選只選擇同步處理文件庫中的部分資料夾。

    如果您使用之前的商務用 OneDrive同步處理用戶端 (Groove.exe)，則可以在所有同步文件庫中同步處理最多 20,000 個項目。 其中包括商務用 OneDrive 文件庫、小組網站文件庫，或兩者。 除了整體同步處理限制之外，每個文件庫類型可同步處理的項目數量也會有所限制：
    - 您可以在商務用 OneDrive 文件庫中同步處理最多 20,000 個項目。 包括資料夾和檔案。 
    - 您可以在 SharePoint 文件庫中同步處理最多 5,000 個項目。 包括資料夾和檔案。 這些是您在不同 SharePoint 網站上找到的文件庫，例如小組網站和社群網站、其他人建立的文件庫或您從 [網站] 頁面建立的文件庫。 您可以同步處理多個 SharePoint 文件庫。 任何您同步處理的小組網站也會計算在所有同步處理文件庫的整體20,000 個項目數限制內。

    > [!NOTE]
    > 如果使用者需要同步處理的文件庫內擁有成千上百的檔案，可以將資料夾的權限層級設定為「限制讀取」，讓同步處理用戶端無法處理資料夾。 

- **版本** - 50,000 個主要版本和 511 個次要版本。

- **SharePoint 群組** - 使用者可屬於 5,000 個群組，每個群組最多可有 5,000 個使用者。 每個網站集合最多可以有 10,000 個群組。
    > [!NOTE]
    > 針對 Azure AD 群組限制，請參閱 [Azure AD 服務限制](https://docs.microsoft.com/azure/active-directory/users-groups-roles/directory-service-limits-restrictions)，因為這類限制可能會影響公用和私人群組網站成員資格管理。 
- **受管理的中繼資料** - 字詞庫中 200,000 個字詞、1000 個全域字詞組，以及 1000 個群組。

- **子網站** - 每個網站集合 2,000 個。

- **SharePoint 託管的應用程式** - 每個組織 20,000 個執行個體。

- **每個清單或文件庫唯一的安全性範圍** - 5,000。 針對大型清單，請設計儘可能最少的唯一權限數。

- **使用者** - 每個網站集合最多 200 萬個使用者。
    > [!NOTE]
    > 邀請參加 SharePoint 網站集合的的訪客數量沒有限制。 如需外部共用的詳細資訊，請參閱[外部共用概觀](https://docs.microsoft.com/sharepoint/external-sharing-overview)。
## <a name="see-also"></a>另請參閱

[SharePoint Online 的搜尋限制](https://docs.microsoft.com/sharepoint/search-limits)
