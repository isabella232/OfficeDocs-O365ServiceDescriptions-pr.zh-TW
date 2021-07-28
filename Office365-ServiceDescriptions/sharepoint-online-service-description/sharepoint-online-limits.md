---
title: SharePoint 限制
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: 了解 Microsoft 365 和獨立計畫的 SharePoint 限制。
ms.openlocfilehash: 44571cedf74b2a094231173b87731916d9e26975
ms.sourcegitcommit: 10699cc17ddfed6af78ce1466f478b2bd67ba26a
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/08/2021
ms.locfileid: "53338336"
---
# <a name="sharepoint-limits"></a>SharePoint 限制

了解適用於 Microsoft 365 的 SharePoint 中的服務限制。
  
## <a name="limits-by-plan"></a>各方案的限制 

| 功能 | Microsoft 365 商務基本版、商務標準版或商務進階版 | Microsoft 365 E3 或 E5、Office 365 E1、E3 或 E5，或 SharePoint 方案 1 或 2 | Microsoft 365 F1 或 F3、Office 365 F3 |
|:-----|:-----|:-----|:-----|
|每個組織的儲存體總計<sup>1、2、6</sup> <br/> |每個購買授權 1 TB 加上 10 GB<sup>3</sup>  <br/> |每個購買授權 1 TB 加上 10 GB<sup>3</sup> <br/> |1 TB<sup>3</sup> <br/> |
|每個網站 (網站集合) 的最大儲存空間<sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|每個組織的網站 (網站集合)  <br/> |2 百萬<sup>6</sup> <br/> |2 百萬<sup>6</sup> <br/> |2 百萬<br/> |
|使用者數目  <br/> |最多 300 個  <br/> |1- 500,000<sup>7</sup> <br/> |1- 500,000<sup>7</sup> <br/> |
   
<sup>1</sup> [了解如何尋找貴組織的總計和可用儲存空間](/sharepoint/manage-site-collection-storage-limits)。 您可以無限制地購買額外的 SharePoint Online 儲存空間。 請參閱[新增訂閱的儲存空間](/office365/admin/subscriptions-and-billing/add-storage-space)。 
<br/><sup>2</sup> 我們建議您監控並定期清空「資源回收筒」。 其使用的儲存空間也是組織中總儲存空間上限的一部份。 
<br/> <sup>3</sup> 如果您有訂閱 Microsoft 365 和 Office 365 額外檔案儲存空間附加元件，儲存空間容量會累加。 
<br/> <sup>4</sup> 這是單一網站的儲存空間 *限制*，而非每個網站所 *提供* 的儲存空間總量。 這項限制適用於所有類型的網站，包括 Office 365 群組連結的小組網站和 OneDrive。 SharePoint 系統管理員可以[手動設定降低儲存體限制](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits)。 
<br/> <sup>5</sup> 第一線員工無法管理 SharePoint 網站集合。 
<br/> <sup>6</sup> 不包括為每個授權使用者建立的 OneDrive。 
<br/> <sup>7</sup> 如果您有 500,000 位以上的使用者，請連絡 Microsoft 代表。 
  
## <a name="service-limits-for-all-plans"></a>所有方案的服務限制

### <a name="items-in-lists-and-libraries"></a>清單和文件庫中的項目

一份清單最多可有 3 千萬個項目，而一個文件庫最多可有 3 千萬個檔案和資料夾。 當清單、文件庫或資料夾包含超過 100，000 個項目時，無法中斷清單、文件庫或資料夾的權限繼承。 您也無法重新繼承權限。 不過，您仍然可以中斷清單、文件庫或資料夾內個別項目的繼承，最多可達清單或文件庫中的唯一權限數目上限 (請參閱下一節)。 若要深入了解檢視大型清單的其他限制，請參閱 [管理 Office 365 中的大型清單和文件庫](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784)。

### <a name="unique-security-scopes-per-list-or-library"></a>每個清單或文件庫的唯一安全性範圍

針對大型清單，請設計儘可能最少的唯一權限數，並維持在總計 5,000 個以下。

### <a name="file-size-and-file-path-length"></a>檔案大小及檔案路徑長度

- **250 GB - 檔案上傳限制。** 適用於每個上傳至 Microsoft Teams 檔案的個別檔案、SharePoint 文件庫、OneDrive 資料夾和 Yammer 交談。

- **250 MB - 附加至清單項目的檔案。** 適用於 Microsoft 清單和 SharePoint 清單 - 兩者均以相同的清單平台為基礎。

若要深入了解使用新版 Microsoft OneDrive 同步處理應用程式 (OneDrive.exe) 的規定和限制詳細資訊，請參閱 [無效的檔案名稱和檔案類型](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)。

### <a name="moving-and-copying-across-sites"></a>在各網站間移動和複製

在單一操作中複製/移動多個檔案有三個要求：

- 檔案大小總計不超過 100 GB
- 不超過 30,000 個檔案。
- 每個檔案須小於 15 GB。

### <a name="sync"></a>同步處理

為獲得最佳效能，建議您不要在單一個 OneDrive 或小組網站文件庫中儲存超過 300,000 個檔案。 雖然 SharePoint Online 每個文件庫可儲存 3 千萬份文件，為獲得最佳效能，我們建議所有文件庫中同步處理的檔案不要超過 300,000 個檔案。 此外，如果所有文件庫中有 300,000 個以上的項目要同步處理，即使您沒有同步處理這些文件庫中的所有項目，也會發生相同的效能問題。 如果您使用的是舊版 Microsoft 商務用 OneDrive 同步處理用戶端 (Groove.exe)，則每個文件庫的同步處理上限為 20,000 個項目 (每個小組網站包含 5,000 個項目)。

### <a name="versions"></a>版本

50,000 個主要版本和 511 個次要版本。

### <a name="sharepoint-groups"></a>SharePoint 群組

使用者可在每個網站中隸屬於 5,000 個群組，且每個群組最多可有 5,000 個使用者。 每個網站 (小組集合) 最多包含 10,000 個群組。

> [!NOTE]
> 針對 Azure AD 群組限制，請參閱 [Azure AD 服務規定和限制](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions)，因為這類限制可能會影響公用和私人群組網站成員資格管理。

### <a name="managed-metadata"></a>受管理的中繼資料

總計 1 百萬個字詞，共有 2 百萬個字詞標籤和 1 百萬個字詞屬性 (這些限制是用於全域和網站層級的字詞組合)。 1,000 個全域字詞組和 1,000 個全域群組。

### <a name="overall-site-metadata"></a>整體網站中繼資料

每個網站 1000 GB (中繼資料很難達到此容量)。

### <a name="subsites"></a>子網站

每個網站 (網站集合) 2,000 個。 我們建議您建立網站並將這些網站組織成中樞，而不是建立子網站。 如果您確實會用到子網站，我們建議您限制其數量 (特別是在高流量網站上)。

> [!NOTE]
> 貴組織限定使用 2,000 個中樞網站。 您可能不需要每個功能都有一個中樞網站，在您建立中樞網站之前務必先執行規劃。 如需詳細資料，請瀏覽 [規劃您的 SharePoint 中樞網站](/sharepoint/planning-hub-sites)。

### <a name="sharepoint-hosted-applications"></a>SharePoint 託管的應用程式

每個組織 20,000 個執行個體。

### <a name="users"></a>使用者

每個網站集合 2 百萬。

> [!NOTE]
> 邀請參加 SharePoint 網站的的訪客數量沒有不同的限制。 如需外部共用的詳細資訊，請參閱 [外部共用概觀](/sharepoint/external-sharing-overview)。

## <a name="see-also"></a>另請參閱

[SharePoint 的搜尋限制](/sharepoint/search-limits)