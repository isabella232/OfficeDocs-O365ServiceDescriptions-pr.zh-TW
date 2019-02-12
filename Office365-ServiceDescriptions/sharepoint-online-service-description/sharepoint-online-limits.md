---
title: SharePoint Online 限制
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: 尋找適用於 Office 365 企業版方案及獨立方案的 SharePoint Online 限制。
ms.openlocfilehash: 9d960aa50bef0b200fef2afe63ac1732cf201582
ms.sourcegitcommit: 30a452b9b9a0d8fc288e5911235454cc8f1907be
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 02/12/2019
ms.locfileid: "25848688"
---
# <a name="sharepoint-online-limits"></a>SharePoint Online 限制

尋找 SharePoint 限制 Office 365 計劃和 SharePoint Online 獨立計劃。
  
## <a name="limits-by-plan"></a>依計劃的限制

|||||
|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商務 Essentials 或企業進階版** <br/> |**Office 365 企業版 E1、 E3 或 E5 或 SharePoint Online 計劃 1 或 2** <br/> | **Office 365 企業版 F1** <br/> |
|儲存體<sup>1、2</sup> <br/> |組織每 1 TB 加上 10 GB 每個附加元件購買的授權  <br/> |組織每 1 TB 加上 10 GB 每個授權購買<sup>3</sup> <br/> |每個組織 1 TB <sup>3</sup> <br/> |
|網站集合儲存體  <br/> |每個網站集合或群組最多 25 TB<sup>4</sup> <br/> |每個網站集合或群組最多 25 TB<sup>4</sup> <br/> |每個網站集合或群組最多 25 TB<sup>5</sup> <br/> |
|每個組織的網站集合  <br/> |500000<sup>6</sup> <br/> |500000<sup>6</sup> <br/> | 500,000<br/> |
|使用者數目  <br/> |最多 300 個  <br/> |1- 500,000<sup>7</sup> <br/> |1- 500,000<sup>7</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup>您可以購買額外的 SharePoint Online 儲存空間不受限制的數量。請參閱[您的訂閱的變更儲存空間](https://support.office.com/article/96EA3533-DE64-4B01-839A-C560875A662C)。<br/>建議監視資源回收筒和定期清空的<sup>2</sup> 。它會使用的儲存空間是組織的總檔案存放區限制的一部分。<br/> <sup>3</sup> 當您有 Office 365 訂閱和 SharePoint Online 獨立方案時，儲存體數量會增加。<br/><sup>4</sup> SharePoint Online 系統管理員可以設定網站集合與網站的儲存限制。<br/> <sup>5</sup> kiosk 工作者不能管理 SharePoint Online 網站集合。您必須至少一個 Enterprise 使用者授權管理 kiosk 網站集合。<br/> <sup>6</sup> 不包括為每個授權使用者建立的商務用 OneDrive 網站集合。<br/><sup>7</sup> 如果您有 500,000 位以上的使用者，請連絡 Microsoft 代表。 
  

  
## <a name="service-limits-for-all-plans"></a>各計劃的服務限制

- **清單和文件庫中的項目**-清單可以包含多達 30 萬個項目和文件庫可有最多 30 萬個檔案及資料夾。檢視可有最多 12 個查閱欄。若要深入了解檢視大型清單的其他限制，請參閱[管理大型清單與 Office 365 中的文件庫](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784)。檔案名稱中不能使用的字元的相關資訊，請參閱[檔案和資料夾名稱中有無效的字元](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)。

- **檔案大小及檔案路徑長度**-15 GB。若要深入了解限制和限制使用新的 OneDrive sync 用戶端 (OneDrive.exe) 時，請參閱[無效的檔案名稱及 OneDrive for Business 和 SharePoint 的 onedrive 的檔案類型](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)。

- **同步處理**-以獲得最佳效能，建議 OneDrive 或小組網站的單一文件庫中儲存不超過 300000 檔案。雖然 SharePoint Online 可儲存文件庫每 30 萬份文件，以獲得最佳效能建議跨所有文件庫次不超過 300000 檔案。此外，如果您有 300000 項或多個跨所有文件庫您正在同步處理，即使您不會同步處理這些文件庫中的所有項目可以發生相同的效能問題。如果您使用先前的 OneDrive for Business sync 用戶端 (Groove.exe)，每個文件庫的同步處理限制為 20000 （包括每個小組網站 5000 個項目） 的項目。

- **版本**-50000 的主要版本和 511 次要版本。

- **SharePoint 群組**-使用者可以隸屬於 5000 群組和每個群組可以有多達 5000 個使用者。您可以讓每個網站集合最多 10000 個群組。

- **受管理的中繼資料**-200000 字詞儲存區、 1000 個的全域字詞集 1000 個群組中的條款。

- **子網站**-最多 2000 每個網站集合。

- **SharePoint 主控應用程式**-20000 個組織的執行個體。

- **每個清單或文件庫的唯一安全性範圍**-5000。大型清單設計儘可能有較少的唯一權限。

- **使用者**-每個網站集合 2 百萬。

> [!NOTE]
> [!附註] 您所能邀請進入 SharePoint Online 網站集合的外部使用者人數並無任何限制。如需詳細資訊，請參閱[為您的 SharePoint Online 環境管理外部共用](/sharepoint/external-sharing-overview)。

## <a name="see-also"></a>另請參閱

[SharePoint Online 的搜尋限制](/sharepoint/search-limits)