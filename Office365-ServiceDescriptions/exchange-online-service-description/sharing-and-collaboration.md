---
title: 共用和協同
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-sharing-and-collaboration
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 862dab54-701f-4014-a594-0b71e03772d2
ms.openlocfilehash: ca55a389f5ed117b09b6c10ca1b2caf42bf01be0
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/25/2019
ms.locfileid: "33246359"
---
# <a name="sharing-and-collaboration"></a>共用和協同

## <a name="federated-sharing"></a>同盟共用

同盟指的是支援同盟共用的基礎信任基礎結構，對 Microsoft Exchange Online 使用者而言，這是與其他外部同盟組織中的收件者或與可存取網際網路的使用者有空/忙碌共用行事曆資料和連絡人資訊的方法。這些包括使用 Exchange Online 託管的組織，或外部 Microsoft Exchange Server 2010 或 Exchange Server 2013 組織。Exchange Online 系統管理員可使用組織關係和共用原則，允許使用者從 Microsoft Outlook Web App 或 Microsoft Outlook 2010 或更新版本傳送行事曆共用邀請。
  
> [!IMPORTANT]
>  外部 Exchange 2010 和 Exchange 2013 組織必須在設定同盟共用的過程中，設定與 Microsoft Federation Gateway 之間的同盟信任。Exchange Online 組織不需要設定同盟信任，因為與 Microsoft Federation Gateway 之間的同盟信任會在建立 Office 365 租用戶時自動建立。 >  Exchange Online 組織必須設定組織關係或共用原則，才能啟用同盟共用。 >  同盟共用不支援共用全域存取清單 (GAL)，或在不同 Office 365 租用戶中於 Exchange Online 組織之間移動使用者信箱。 
  
如需有關同盟共用的詳細資訊，請參閱[在 Exchange Online 中共用](https://go.microsoft.com/fwlink/p/?LinkId=271774)。
  
## <a name="site-mailboxes"></a>網站信箱

電子郵件與文件將以傳統方式儲存於兩個獨特且分離的資料存放庫。大部分的團隊會同時使用電子郵件和文件來進行共同作業。挑戰在於電子郵件與文件皆使用不同客戶端存取。這通常是使用者生產力的下降以及使用者體驗的退化所產生的結果。
  
網站信箱是 Exchange 2013 中的全新概念，目的為嘗試解決此問題。網站信箱使用同一個用戶端介面同時允許存取 Microsoft SharePoint 2013 文件和 Exchange 電子郵件，來改善共同作業和使用者的生產力。網站信箱功能是由 SharePoint 2013 網站成員資格 (擁有者和成員) 組成，透過 Exchange 2013 信箱的電子郵件與 SharePoint 2013 網站的文件共用儲存，並使用同一個管理介面來解決佈建和週期需求。
  
> [!IMPORTANT]
> 您的 Office 365 計劃必須包括 SharePoint 在內。網站信箱要求使用者同時具有 SharePoint 和 Exchange 的授權。 
  
如需有關網站信箱的詳細資訊，請參閱[網站信箱](https://go.microsoft.com/fwlink/p/?LinkId=271789)。
  
## <a name="public-folders"></a>公用資料夾

Exchange Online 中的公用資料夾已經過強化，可善用信箱資料庫現有的高可用性和儲存技術。 公用資料夾架構使用特殊設計的信箱來儲存階層與公用資料夾內容。 這意味著再也沒有獨立的公用資料夾資料庫。 公用資料夾複寫目前使用連續複寫模型。 階層和內容信箱的高可用性是由資料中心的資料庫可用性群組 (DAG) 提供。 在 Exchange Online 中，您可以有 1000 個公用資料夾信箱。 每個公用資料夾信箱也有最大儲存大小。 如需詳細資訊，請參閱 [Exchange Online 限制](exchange-online-limits.md)中的＜信箱資料夾限制＞一節。 公用資料夾信箱與一般信箱具有相同的郵件、收件者及容量警示限制。 如需詳細資訊，請參閱[收件者](recipients.md)。 
  
如需有關公用資料夾的詳細資訊，請參閱[公用資料夾](https://go.microsoft.com/fwlink/p/?LinkId=271790)。
  
## <a name="group-and-shared-mailboxes"></a>群組及共用信箱

群組及共用信箱可方便一組特定的人員監視及傳送共用帳戶 (例如 info@contoso.com 或 contact@contoso.com 這類的公用電子郵件地址) 的電子郵件。當這組人員中有人回覆傳送到共用信箱的郵件時，電子郵件會顯示為由共用信箱寄出，而不是由個別使用者寄出。
  
通常，群組或共用信箱不需要個別的使用者授權。但是，若要啟用群組或共用信箱的就地封存，您必須為它指派 Exchange Online Plan 1 或 Exchange Online Plan 2 授權。指派授權後，信箱大小增加為授權計劃的大小。若要「就地保留」共用信箱，您必須為它指派 Exchange Online Plan 2 授權。請注意，目前無法指派群組信箱，但應該列入您的授權總計。
  
「就地封存」僅可用來封存已套用授權之單一使用者或實體 (例如共用信箱) 的郵件。禁止使用「就地封存」來儲存多個使用者或實體的郵件。例如，IT 系統管理員不能建立共用信箱，再由使用者純粹為了封存的目的來複製它 (透過 [副本] 或 [密件副本] 欄位，或透過傳輸規則)。請注意，多人使用的共用信箱不會實際儲存個別使用者的電子郵件。多個使用者可以存取，且傳送電子郵件做為共用信箱。因此，只有傳送至共用信箱或從共用信箱寄出的電子郵件會儲存在共用信箱中，做為共用信箱。
  
## <a name="feature-availability"></a>功能可用性

若要檢視 Office 365 計劃、獨立選項和內部部署解決方案中的功能可用性，請參閱 [Exchange Online 服務說明](exchange-online-service-description.md)。
  

