---
title: 服務健康狀況和持續性
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-service-health
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0483499d-8972-4a8f-97bd-b82f5b138991
description: Microsoft Office 365 系統管理員可以檢視之服務的狀態並找出維護已排程的時間。服務健康狀況之資訊隨時登入 Office 365。
ms.openlocfilehash: cc19a26f7bef070837b1dfa53df927373fd35d3e
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035417"
---
# <a name="service-health-and-continuity"></a>服務健康狀況和持續性

Microsoft Office 365 系統管理員可以檢視之服務的狀態並找出維護已排程的時間。服務健康狀況之資訊隨時登入 Office 365。
  
> [!NOTE]
> 如果您使用 21Vianet 所操作的 Office 365，以下的部分資訊可能不適用。相反地，請參閱 [21Vianet 服務層次協議](http://www.21vbluecloud.com/office365/O365-SLA/)。 
  
## <a name="view-status-of-services"></a>檢視服務狀態

服務健康狀況] 區段中的 Office 365 顯示服務及服務干擾及中斷的詳細資料的目前狀態。計劃的維護資訊會訊息中心上提供。如需詳細資訊，請參閱 ＜[檢視服務的狀態](https://go.microsoft.com/fwlink/p/?LinkID=270178)。 
  
## <a name="service-incidents"></a>服務事件

建立服務事件是會影響的服務傳遞事件。服務事件可能會造成於 Microsoft 資料中心，客戶與 Microsoft、 或主要資料中心挑戰例如火災、 洪水或區域災難之間的無效的網路連線的硬體或軟體失敗。大部分的服務事件可以使用 Microsoft 技術及程序解決方案解決，以及解決在短時間內。不過，某些服務事件更嚴重，且可能會導致較長的字詞庫中斷。
  
有兩種類型的相關當服務可能無法使用的時間通知：
  
- **計劃維護事件：** 計劃的維護是一般的 Microsoft 起始服務基礎結構及軟體應用程式更新。計劃的維護通知通知客戶需可能會影響功能的 Office 365 服務的服務運作。客戶不晚於五天前透過 Office 365 系統管理入口網站上的訊息中心的所有計劃維護會收到通知。Microsoft 通常將維護計劃的時間時服務使用方式在過去在其最低根據區域的時區。 
    
- **意外停機** 其中一個 Office 365 套件中的服務無法使用或無回應時，就會發生意外的服務事件。 
    
## <a name="notification-policy"></a>通知原則

建立服務事件發生時，Microsoft 可辨識及時、 目標，且正確的通訊很重要的客戶。Microsoft 通知由更新承租人特定服務健康狀況儀表板 (SHD) Office 365 系統管理入口網站上的 Office 365 系統管理員。在每小時的頻率所提供的服務事件更新或如果需要不同的頻率，它會上文 SHD 通訊張貼。 
  
## <a name="service-health-communication-channels"></a>服務健康狀況的通訊通道

### <a name="office-365-admin-app"></a>Office 365 系統管理應用程式

Office 365 租用戶系統管理員管理應用程式可讓您能夠連線以在行進貴組織的 Office 365 服務狀態。Office 365 租用戶系統管理員必須能夠檢視服務健康狀況資訊及維護的狀態更新他們的行動裝置。如需詳細資訊，請瀏覽[管理應用程式常見問題集](https://community.office365.com/en-us/w/manage/office-365-admin-app-faq.aspx)。
  
### <a name="office-365-management-pack-for-microsoft-system-center-2012-r2"></a>Microsoft System Center 2012 R2 的 Office 365 管理組件

Microsoft System Center 是可幫助您管理資料中心、 用戶端裝置和混合式雲端的 IT 環境整合的管理平台。Office 365 系統管理員使用 System Center 現在已匯入 Office 365 管理套件，讓它們可以檢視 System Center Operations Manager 內的所有服務通訊選項。使用此工具可讓您存取您的訂閱的服務、 作用中且解析服務事件及訊息中心通訊的狀態。如需詳細資訊，請瀏覽[新的 Office 365 系統管理工具](https://blogs.office.com/2014/07/29/new-office-365-admin-tools/)部落格文章。 
  
### <a name="office-365-service-communications-api"></a>Office 365 服務通訊 API

Office 365 服務通訊 API 可讓您以您想要的方式存取 Office 365 服務通訊。有了這個新的系統管理工具，您現在可以建立您的工具或將其連線至 Office 365 服務通訊，也可能簡化監視環境的方式。服務通訊 API 可讓您監視環境中的下列項目：
  
- 即時服務健康狀況
    
- 訊息中心通訊
    
- 規劃的維護通知
    
若需詳細資訊，請瀏覽[新的 Office 365 系統管理工具](https://blogs.office.com/2014/07/29/new-office-365-admin-tools/) 部落格文章。 
  
## <a name="post-incident-reviews"></a>事件後續檢閱

Microsoft 對於持續改善服務的承諾包括針對對客戶產生影響的意外服務事件之分析，以至將未來重複發生的機會降至最低。 
  
因的服務事件被定義為多承租人服務中斷的影響服務使用情況定義我們服務 sla，而且有已因此宣告服務健康狀況儀表板上。
  
 針對因客戶會影響服務事件中有廣泛和明顯影響整個組織的數目、 初步後事件檢閱 (PIR) 會傳遞透過服務健康狀況儀表板事件的 48 小時內解決方法，後面接著最後一個 PIR 五個工作天內。詳細的 PIR 報告包含： 
  
- 使用者經驗和客戶影響
    
- 事件開始和結束日期/時間
    
- 詳細的時間表的影響和解決方法的量值
    
- 根本原因分析和為持續改進所採取的動作
    
針對其他所有服務事件、 服務健康狀況儀表板會提供事件關閉摘要包含最後一個事件、 初步根本原因、 開始與結束時間和資訊細部下一個步驟的摘要。此類別的服務事件不會產生 PIR。 
  
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
  

