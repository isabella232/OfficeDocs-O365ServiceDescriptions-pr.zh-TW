---
title: 服務健康狀況和持續性
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-service-health
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0483499d-8972-4a8f-97bd-b82f5b138991
description: Microsoft Office 365 系統管理員可以檢視服務的狀態，並找出維護排定的時間。 服務健康狀況資訊，請在任何時間登入 Office 365。
ms.openlocfilehash: ffa55d304f5fbf7a9f97aef83207a923ea4dcce2
ms.sourcegitcommit: 96dc758c790ddaf05f5c2b836451b417729cf119
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/18/2019
ms.locfileid: "35776444"
---
# <a name="service-health-and-continuity"></a>服務健康狀況和持續性

Microsoft Office 365 系統管理員可以檢視服務的狀態，並找出維護排定的時間。 服務健康狀況資訊，請在任何時間登入 Office 365。
  
> [!NOTE]
> 如果您使用 21Vianet 所操作的 Office 365，以下的部分資訊可能不適用。 相反地，請參閱 [21Vianet 服務層次協議](http://www.21vbluecloud.com/office365/O365-SLA/)。 
  
## <a name="view-status-of-services"></a>檢視服務狀態

Office 365 的服務健康區段顯示服務和相關服務干擾及中斷的詳細資料的目前狀態。 在 [訊息中心都提供計劃的維護資訊。 如需詳細資訊，請參閱[檢視您服務的狀態](https://docs.microsoft.com/office365/enterprise/view-service-health)。 
  
## <a name="service-incidents"></a>服務事件

服務事件為可影響服務傳遞的事件。 服務意外事件可能是在 Microsoft 資料中心，客戶與 Microsoft 或主要資料中心項挑戰，例如火災、 洪水或區域災難之間的無效的網路連線的硬體或軟體失敗所造成。 大多數的服務意外事件皆可使用 Microsoft 技術與程序解決方案，在短時間內解決。 但是，部分服務意外事件可能更為嚴重，且會導致較長期的服務中斷。
  
有兩種類型的通知時服務可能無法使用的時間：
  
- **計劃維護事件：** 計畫性的維護是基礎架構與軟體應用程式的 Microsoft 起始的定期服務更新。 規劃的維護通知知會客戶關於可能影響的 Office 365 服務功能的服務工程。 不晚遲透過訊息中心 Office 365 管理入口網站上的所有計畫維護五天前通知客戶。 Microsoft 通常會以時間時服務使用情況紀錄位於最低點根據區域時間方案維護。 
    
- **意外停機** 其中一個 Office 365 套件中的服務無法使用或無回應時，就會發生意外的服務事件。 

### <a name="recent-worldwide-uptimes"></a>最近的全球透明化

移至雲端服務，不應該會失去能夠知道什麼事。 使用 Office 365，不支援。 我們的目標是透明我們操作，因此您可以監視的服務狀態、 追蹤問題，並有可用性的歷史檢視。 下表顯示的最近使用的全球上線時間資料。

<br/>

|**2019** <br/> ||||
|:-----|:-----|:-----|:-----|
| **Q1** <br/> | **Q2** <br/> |**Q3** <br/> |**Q4** <br/> |
| 99.97% <br/> |  <br/> |  <br/> |  <br/> |

<br/>

|**2018** <br/>||||
|:-----|:-----|:-----|:-----|
| **Q1** <br/> | **Q2** <br/> |**Q3** <br/> |**Q4** <br/> |
| 99.99% <br/> | 99.98% <br/> | 99.97% <br/> | 99.98% <br/> |

<br/>

|**2017** <br/> ||||
|:-----|:-----|:-----|:-----|
| **Q1** <br/> | **Q2** <br/> |**Q3** <br/> |**Q4** <br/> |
| 99.99% <br/> | 99.97% <br/> | 99.98% <br/> | 99.99% <br/> |

<br/>

## <a name="notification-policy"></a>通知原則

服務事件發生時，Microsoft 會辨識及時、鎖定目標且正確的通訊對客戶很重要。 Microsoft 會藉由更新租用戶特定服務健康狀況儀表板 (SHD) 上 Office 365 系統管理入口網站通知 Office 365 系統管理員。 服務事件更新會提供每小時的頻率，或者，如果需要不同的頻率，將會說明在 SHD 通訊張貼內容中。 
  
## <a name="service-health-communication-channels"></a>服務健康狀況的通訊通道

### <a name="office-365-admin-app"></a>Office 365 系統管理應用程式

Office 365 租用戶系統管理員系統管理應用程式可讓您能夠隨時隨地貴組織的 Office 365 服務狀態連線。 Office 365 租用戶系統管理員必須能夠檢視服務健康情況資訊及維護狀態更新，從行動裝置。 如需詳細資訊，請瀏覽[系統管理應用程式常見問題集](https://docs.microsoft.com/en-us/office365/admin/admin-overview/admin-mobile-app?view=o365-worldwide)。
  
### <a name="office-365-management-pack-for-microsoft-system-center-2012-r2"></a>Microsoft System Center 2012 R2 的 Office 365 管理組件

Microsoft System Center 是可協助您管理資料中心、用戶端裝置和混合雲端 IT 環境的整合式管理平台。 Office 365 系統管理員現在使用 System Center 已匯入 Office 365 管理組件，可讓他們能夠檢視在 System Center Operations Manager 內的所有服務通訊選項。 使用此工具可讓您存取您已訂閱服務的狀態、作用中及已解決服務事件及訊息中心通訊。 若需詳細資訊，請瀏覽[新的 Office 365 系統管理工具](https://blogs.office.com/2014/07/29/new-office-365-admin-tools/) 部落格文章。 
  
### <a name="office-365-service-communications-api"></a>Office 365 服務通訊 API

Office 365 服務通訊 API 可讓您以您想要的方式存取 Office 365 服務通訊。有了這個新的系統管理工具，您現在可以建立您的工具或將其連線至 Office 365 服務通訊，也可能簡化監視環境的方式。服務通訊 API 可讓您監視環境中的下列項目：
  
- 即時服務健康狀況
    
- 訊息中心通訊
    
- 規劃的維護通知
    
若需詳細資訊，請瀏覽[新的 Office 365 系統管理工具](https://blogs.office.com/2014/07/29/new-office-365-admin-tools/) 部落格文章。 
  
## <a name="post-incident-reviews"></a>事件後續檢閱

Microsoft 對於持續改善服務的承諾包括針對對客戶產生影響的意外服務事件之分析，以至將未來重複發生的機會降至最低。 
  
意外的服務事件定義為多用戶服務中斷，影響服務使用，我們的服務 Sla 所定義，並已在 [服務健康狀況儀表板上做如此宣告。
  
 意外客戶產生影響的服務事件順序時發生廣泛和明顯影響整個組織的大型數字，如初步事件後續檢閱 (PIR) 將會透過傳遞服務健全狀況儀表板的事件 48 小時內解決方法，接著五個工作天內的最後一個 PIR。 詳細的 PIR 報告中包含： 
  
- 使用者經驗和客戶影響
    
- 事件開始和結束日期/時間
    
- 詳細的時間表的影響和解決措施
    
- 根本原因分析和為持續改進所採取的動作
    
對於所有其他的服務事件，服務健全狀況儀表板會提供包括事件、 初步的根本原因，開始和結束時間及細部後續步驟的資訊的最終摘要意外關閉摘要。 對於這個類別的服務事件，將不會產生 PIR。 
  
## <a name="service-continuity"></a>服務連續性

Microsoft Office 365 方案會以高度彈性的系統傳遞，以維持最佳服務效能。服務持續性佈建為 Office 365 系統設計中的一部份。這些佈建可讓 Office 365 快速自未預期的事件中復原，例如硬體或應用程式故障、資料中斷或者其他影響使用者的事件。這些服務持續性解決方法同時應用於災難性的中斷期間 (例如天災或者 Microsoft 資料中心中發生的意外事件，造成整個資料中心無法運作)。
  
請注意，從重大中斷事件回復後，可能需要經過一段時間，服務的完整資料中心備援才會恢復運作。例如：如果資料中心 1 故障，則可由資料中心 2 的資源回復服務；不過，可能需要等待一段時間，資料中心 2 才可獲得資料中心 1 中已回復之資源或資料中心 3 中新資源的服務持續性支援。在此期間，可適用 Office 365 [服務等級協定](https://technet.microsoft.com/en-us/library/office-365-service-level-agreement.aspx) (SLA)。21Vianet 運作的 Office 365 有不同的 SLA。如需詳細資訊，請參閱 [21Vianet 網站](http://www.21vbluecloud.com/office365/O365-SLA/)。 
  
## <a name="ensuring-data-availability"></a>確保資料可用性

Microsoft 可確保客戶資料在需要時可透過下列功能取用：
  
- **資料儲存與備援：** 透過健全的資料備份保護功能，客戶資料可儲存於備援環境中，以提供可用性、企業持續性和快速的回復能力。將實作多階層的資料備援，範圍從防止本機磁碟故障的備援磁碟到持續性、完整的資料複寫，到依地理位置不同的資料中心。 
    
- **資料監視：** Office 365 服務保持高層級的效能： 
    
  - **監視資料庫：**
    
  - 封鎖的程序
    
  - 封包遺失
    
  - 已排入佇列的程序
    
  - 查詢延遲
    
- **完成預防性維護：** 完成預防性維護包括資料庫一致性檢查、定期資料壓縮、以及錯誤記錄檢閱。 
    
## <a name="support"></a>支援

Office 365 研發與營運團隊將由專用的 Office 365 支援組織來完整架構，在提供客戶企業持續性中扮演了舉足輕重的角色。支援工作人員對於服務與其相關的應用程式具備專業知識，同時在架構、研發與測試方面也可直接獲得 Microsoft 專家的協助。
  
支援組織與營運及產品研發有緊密關聯，不僅提供快速的解決時間，也為客戶的意見提供發表的管道。客戶的意見回饋也可嘉惠規劃、研發以及營運等程序。
  
- **線上問題追蹤：** 客戶需得知自己的問題已在解決中，也須能即時追蹤解決進度。Office 365 入口網站提供了單一的網路架構介面支援服務。客戶可使用入口網站來新增並監控服務請求，以及接收來自 Microsoft 支援團隊的回覆。 
    
- **自助服務，由持續性人員支援維持：** Office 365 提供許多自助資源和工具，可協助客戶解決與服務相關的問題而不需要 Microsoft 支援。 
    
在客戶輸入服務請求前，可先進入知識庫文章以及問答集來查看常見問題的即刻協助。這些資源將持續更新最新資訊，為已知問題提供解決方案以避免問題造成的延誤。但是，當提出的問題需要支援專家的幫助時，工作人員可透過電話或行政入口網站提供全年無休的立即協助。
  
如需詳細資訊，請參閱[支援](https://technet.microsoft.com/en-us/library/office-365-support.aspx) 主題。 
  
## <a name="feature-availability"></a>功能可用性

若要檢視跨 Office 365 規劃的功能可用性，請參閱 [Office 365 平台服務說明](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx)。
  