---
title: 服務健康狀況和持續性
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-service-health
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0483499d-8972-4a8f-97bd-b82f5b138991
description: Microsoft 系統管理員可以查看服務的狀態，並找出維護排程的時間。 服務健康資訊可隨時登入。
ms.openlocfilehash: ea9beb020d2f868eb51638c4729924a7ac873b7b
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/24/2021
ms.locfileid: "51174138"
---
# <a name="service-health-and-continuity"></a>服務健康狀況和持續性

Microsoft 系統管理員可以查看服務的狀態，並找出維護排程的時間。 服務健康資訊可隨時登入。
  
> [!NOTE]
> 如果您使用 21Vianet 所操作的 Office 365，以下的部分資訊可能不適用。 相反地，請參閱 [21Vianet 服務層次協議](https://www.21vbluecloud.com/office365/O365-SLA/)。 
  
## <a name="view-status-of-services"></a>查看服務的狀態

服務健康情況區段會顯示服務的目前狀態，以及服務中斷及中斷的詳細資料。 計畫的維護資訊可在訊息中心上取得。 如需詳細資訊，請參閱[檢視您服務的狀態](/office365/enterprise/view-service-health)。 
  
## <a name="service-incidents"></a>服務事件

服務事件為可影響服務傳遞的事件。 服務事件可能是由 Microsoft 資料中心中的硬體或軟體故障、客戶與 Microsoft 之間的錯誤網路連線，或是主要的資料中心挑戰（如火災、洪水或地區災難）所造成。 大多數的服務意外事件皆可使用 Microsoft 技術與程序解決方案，在短時間內解決。 但是，部分服務意外事件可能更為嚴重，且會導致較長期的服務中斷。
  
服務可能無法使用時，有兩種通知類型：
  
- **計畫的維護事件：** 規劃維護是針對基礎結構和軟體應用程式的定期 Microsoft 發起服務更新。 規劃的維護通知會告知客戶可能會影響 Microsoft 服務功能的服務運作。 透過 Microsoft 365 系統管理中心的郵件中心，所有的計畫維護都有超過五天后，客戶便會收到通知。 根據區域時區的情形，Microsoft 一般會規劃維護，以瞭解服務的使用頻率為最低。 
    
- **意外停機時間：** 當其中一個服務無法使用或無回應時，就會發生意外的服務事件。 

### <a name="recent-worldwide-uptimes"></a>最近世界上線時間

移至雲端服務不一定意味著會失去知道即將發生的功能。 使用 Office 365 時，它不會。 我們的作業中的目標是透明的，因此您可以監視服務的狀態、追蹤問題，並提供可用性的歷史視圖。 下表顯示最近的全球運作時間資料。

**2020**

| 季度 | 推出 | Q3 | Q4 |
|:-----|:-----|:-----|:-----|
| 99.98% <br/> | 99.99%<br/> | 99.97%<br/> | 99.97%<br/> |

<br>

**2019**

| 季度 | 推出 | Q3 | Q4 |
|:-----|:-----|:-----|:-----|
| 99.97% <br/> | 99.97% <br/> | 99.98% <br/> | 99.98% <br/> |

<br>

**2018**

| 季度 | 推出 | Q3 | Q4 |
|:-----|:-----|:-----|:-----|
| 99.99% <br/> | 99.98% <br/> | 99.97% <br/> | 99.98% <br/> |

<br>

**2017 年**

| 季度 | 推出 | Q3 | Q4 |
|:-----|:-----|:-----|:-----|
| 99.99% <br/> | 99.97% <br/> | 99.98% <br/> | 99.99% <br/> |

## <a name="notification-policy"></a>通知原則

服務事件發生時，Microsoft 會辨識及時、鎖定目標且正確的通訊對客戶很重要。 Microsoft 會透過更新 Microsoft 365 系統管理中心的承租人特定服務健康情況儀表板 (SHD) 來通知系統管理員。 服務事件更新是以每小時的節奏提供，或者，如果需要不同的節奏，就會在 SHD 通訊發佈中加以說明。 
  
## <a name="service-health-communication-channels"></a>服務健康情況通道

### <a name="admin-app"></a>系統管理應用程式

組織管理員的系統管理員應用程式可讓您在旅途上連線到組織的 Microsoft 服務狀態。 Microsoft 系統管理員可以從其行動裝置查看服務健康情況資訊與維護狀態更新。 如需詳細資訊，請造訪[系統管理 App 常見問題集](/office365/admin/admin-overview/admin-mobile-app)。
  
### <a name="office-365-management-pack-for-microsoft-system-center-2012-r2"></a>Microsoft System Center 2012 R2 的 Office 365 管理組件

Microsoft System Center 是可協助您管理資料中心、用戶端裝置和混合雲端 IT 環境的整合式管理平台。 使用 System Center 的 Microsoft 系統管理員現在可以選擇匯入 Office 365 管理元件，讓他們可以在 System Center 的 Operations Manager 中查看所有服務通訊。 使用此工具可讓您存取您已訂閱服務的狀態、作用中及已解決服務事件及訊息中心通訊。 如需詳細資訊，請在 Microsoft 下載中心取得 [Microsoft System Center Management Pack For Office 365](https://www.microsoft.com/download/details.aspx?id=43708) 。 
  
### <a name="office-365-service-communications-api"></a>Office 365 服務通訊 API

Office 365 服務通訊 API 可讓您以您想要的方式存取服務通訊。 使用此 API，您可以建立或連接工具以服務通訊，並可能簡化您監視環境的方式。 服務通訊 API 可讓您監視環境的下列專案：
  
- 即時服務健康狀況
    
- 訊息中心通訊
    
如需詳細資訊，請參閱 [Office 365 服務通訊 API 參考](/office/office-365-management-api/office-365-service-communications-api-reference)。 
  
## <a name="post-incident-reviews"></a>事件後續檢閱

Microsoft 對於持續改善服務的承諾包括針對對客戶產生影響的意外服務事件之分析，以至將未來重複發生的機會降至最低。 
  
「計畫外服務事件」是指多承租人服務中斷，它會影響服務等級協定 (Sla) 所定義的服務，並在服務健康情況儀表板上宣告為這類狀況。
  
 針對未計畫的客戶影響服務事件，在這種情況下 (，在大量組織中有廣泛且明顯的影響，PIR) 將會透過您的服務健康情況儀表板在事件解決的48小時內傳遞，並在五個工作日內進行最後的 PIR。 詳細 PIR 報告包含下列專案： 
  
- 使用者經驗和客戶影響
    
- 事件開始和結束日期/時間
    
- 影響與解決方法的詳細時程表
    
- 根本原因分析和為持續改進所採取的動作
    
在所有其他服務事件中，服務健康情況儀表板會提供事件結束摘要，包括事件的最後摘要、初步的根本原因、開始和結束時間，以及詳述後續步驟的資訊。 對於這個類別的服務事件，將不會產生 PIR。 
  
## <a name="service-continuity"></a>服務連續性

Microsoft 提供的服務可透過高彈性系統進行傳遞，以協助維護峰值服務效能。 服務持續性規定是系統設計的一部分。 這些規定可讓 Microsoft 快速從意外事件（例如硬體或應用程式失敗、資料損毀或其他影響使用者的事件）進行復原。 這些服務持續性解決方法同時應用於災難性的中斷期間 (例如天災或者 Microsoft 資料中心中發生的意外事件，造成整個資料中心無法運作)。
  
請注意，從災難性中斷復原後，可能需要一段時間，才能還原服務的完整資料中心冗余。 例如，如果資料中心1失敗，則會透過資料中心2中的資源還原服務。 不過，您可能需要一段時間，直到資料中心2中的服務因還原資料中心1中的資源或資料中心3中的新資源而支援服務持續性。 Microsoft [服務等級協定](service-level-agreement.md) (SLA) 會在此期間套用。 由世紀運作的 Office 365 具有不同的 SLA。 如需詳細資訊，請參閱 [ [世紀] 網站](https://www.21vbluecloud.com/office365/O365-SLA/)。 
  
## <a name="ensuring-data-availability"></a>確保資料可用性

Microsoft 可確保客戶資料在需要時可透過下列功能取用：
  
- **資料儲存與備援：** 透過健全的資料備份保護功能，客戶資料可儲存於備援環境中，以提供可用性、企業持續性和快速的回復能力。將實作多階層的資料備援，範圍從防止本機磁碟故障的備援磁碟到持續性、完整的資料複寫，到依地理位置不同的資料中心。 
    
- **資料監視：** Microsoft 服務會透過監控，維持高效能效能： 
    
  - 資料庫
    
  - 封鎖的程序
    
  - 封包遺失
    
  - 已排入佇列的程序
    
  - 查詢延遲
    
- **完成預防性維護：** 完成預防性維護包括資料庫一致性檢查、定期資料壓縮、以及錯誤記錄檢閱。 
    
## <a name="support"></a>支援

Microsoft 開發和作業團隊是以專屬支援組織為依據，這在提供客戶業務連續性方面起著重要的作用。 支援工作人員對於服務與其相關的應用程式具備專業知識，同時在架構、研發與測試方面也可直接獲得 Microsoft 專家的協助。
  
支援組織與營運及產品研發有緊密關聯，不僅提供快速的解決時間，也為客戶的意見提供發表的管道。客戶的意見回饋也可嘉惠規劃、研發以及營運等程序。
  
- **線上問題追蹤：** 客戶需得知自己的問題已在解決中，也須能即時追蹤解決進度。 Microsoft 365 系統管理中心提供單一的 web 介面以提供支援。 客戶可使用入口網站來新增並監控服務請求，以及接收來自 Microsoft 支援團隊的回覆。 
    
- **由持續性人員支援作為後盾的自我協助：** Microsoft 提供一系列自助資源和工具，可協助客戶解決與服務相關的問題而不需要 Microsoft 支援。 
    
在客戶輸入服務請求前，可先進入知識庫文章以及問答集來查看常見問題的即刻協助。這些資源將持續更新最新資訊，為已知問題提供解決方案以避免問題造成的延誤。但是，當提出的問題需要支援專家的幫助時，工作人員可透過電話或行政入口網站提供全年無休的立即協助。
  
如需支援的相關資訊，請參閱 [支援](support.md) 文章。 
  
## <a name="feature-availability"></a>功能可用性

若要查看不同方案中的功能可用性，請參閱 [Microsoft 365 和 Office 365 平臺服務說明](office-365-platform-service-description.md)。
