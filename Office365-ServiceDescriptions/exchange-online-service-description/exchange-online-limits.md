---
title: Exchange Online 限制
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 02/21/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 70b38a05-6cfa-4ced-a137-116019262fed
description: 尋找不同服務區域的 Exchange Online 限制，包括通訊錄限制、信箱儲存限制以及報告與郵件追蹤限制，以上所列僅是其中幾例。
ms.openlocfilehash: ce25d57281cd9a5260b34f2d33d7cf4a490ac866
ms.sourcegitcommit: 30c7b713cbe28bc2ce1f0bd850e48fbc9b1d63f7
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 02/22/2019
ms.locfileid: "30199918"
---
# <a name="exchange-online-limits"></a>Exchange Online 限制

尋找不同服務區域的 Exchange Online 限制，包括通訊錄限制、信箱儲存限制以及報告與郵件追蹤限制，以上所列僅是其中幾例。
  
> [!NOTE]
>  如果您需要某項工作的協助，或是要針對某個問題進行疑難排解，您可能會發現下列文章很實用：  <br/> • [[電子郵件](https://support.office.com/en-us/article/Email-94275804-7147-4332-9ccd-5d421760a9ed?ui=en-US&amp;rs=en-US&amp;ad=US)（如說明建立及傳送電子郵件）  <br/> • [ [Office 365 企業版-Admin 說明中的電子郵件](https://go.microsoft.com/fwlink/?linkid=529722) <br/>   •[修正 Outlook 和 Microsoft 支援服務和 Office 365 的助理修復 Office 365 的問題](https://diagnostics.office.com/) <br/>  • [ [Office 365 中的電子郵件未傳遞回報](https://go.microsoft.com/fwlink/?linkid=526653) <br/> • [Exchange 線上說明](https://go.microsoft.com/fwlink/?linkid=825607) <br/>
  
在 Microsoft Exchange Online 限制配合分成下列類別：
  
- [通訊錄限制](#address-book-limits)
    
- [信箱儲存限制](#mailbox-storage-limits)
    
- [容量提醒](#capacity-alerts)
    
- [信箱資料夾限制](#mailbox-folder-limits)
    
- [郵件限制](#message-limits)

- [接收及傳送限制](#receiving-and-sending-limits)
    
- [報告和郵件追蹤限制](#reporting-and-message-trace-limits)
    
- [保留限制](#retention-limits)
    
- [通訊群組限制](#distribution-group-limits)
    
- [日誌、 傳輸及收件匣規則限制](#journal-transport-and-inbox-rule-limits)
    
- [仲裁限制](#moderation-limits)
    
- [Exchange ActiveSync 限制](#exchange-activesync-limits)
    
> [!IMPORTANT]
>  • [套用至 Microsoft Office 365 組織的限制可能會根據多久組織有所不同具有已註冊服務。<br/> • [限制變更 Microsoft 資料中心，則可能需要一些時間來將變更套用至所有現有的客戶。<br/> • 您無法修改大部分的這些限制，不過您和使用者應該要知道有這些項目。<br/> • 這些限制適用於內部和外部收件者。<br/> • [依預設，Exchange Online Protection (EOP) 提供保護 Exchange Online 信箱。如需套用至 EOP 功能在 Exchange Online 的限制，請參閱[Exchange Online Protection Limits](../exchange-online-protection-service-description/exchange-online-protection-limits.md)。<br/> • For Office 365 群組限制的相關資訊請參閱"How do I 管理 「 我的 groups?"中[了解 Office 365 群組](https://go.microsoft.com/fwlink/?linkid=846714)。 
  
## <a name="address-book-limits"></a>通訊錄限制

- **通訊清單限制** 可以在 Exchange Online 或 Exchange Server 2013 組織中建立的通訊清單數目上限。這個數目包括 Exchange Online 中的預設通訊清單，例如 [所有連絡人] 和 [所有群組]。 
    
    > [!NOTE]
    > 最多可將 20 筆通訊清單指派給單一離線通訊錄 (OAB)。 
  
- **離線通訊錄限制** 可以在 Exchange Online 或 Exchange Server 2013 組織中建立的離線通訊錄 (OAB) 數目上限。 
    
- **通訊錄原則限制** 可以在 Exchange Online 或 Exchange Server 2013 組織中建立的通訊錄原則 (ABP) 數目上限。 
    
- **全域通訊清單** 可以在 Exchange Online 或 Exchange Server 2013 組織中建立的全域通訊清單 (GAL) 數目上限。 
    
### <a name="address-book-limits-across-office-365-options"></a>所有 Office 365 選項的通訊錄限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商務基本版** <br/> |**Office 365 商務進階版** <br/> |**Office 365 企業版 E1** <br/> |**Office 365 企業版 E3** <br/> |**Office 365 企業版 E5** <br/> |**Office 365 企業版 F1** <br/> |
|通訊清單限制  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|離線通訊錄 (OAB) 限制  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|通訊錄原則 (ABP) 限制  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|全域通訊清單限制  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
   
### <a name="address-book-limits-across-standalone-plans"></a>所有獨立方案的通訊錄限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 方案 1** <br/> |**Exchange Online 方案 2** <br/> |**Exchange Online Kiosk** <br/> |
|通訊清單限制  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|離線通訊錄 (OAB) 限制  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|通訊錄原則 (ABP) 限制  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|全域通訊清單限制  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
   
## <a name="mailbox-storage-limits"></a>信箱儲存限制

可用的信箱儲存容量取決於信箱類型和使用者的訂閱授權。管理員可降低單一使用者或全域的最高信箱大小。
  
> [!NOTE]
> 不允許使用日誌記錄、傳輸規則或自動轉寄規則將郵件複製到 Exchange Online 信箱以進行封存。使用者的封存信箱僅供該使用者使用。Microsoft 保留在使用者封存信箱中用來儲存其他使用者之封存資料的執行個體中拒絕不受限封存的權限。 
  
### <a name="storage-limits-across-office-365-options"></a>不同 Office 365 選項中的儲存限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商務基本版** <br/> |**Office 365 商務進階版** <br/> |**Office 365 企業版 E1** <br/> |**Office 365 企業版 E3** <br/> |**Office 365 企業版 E5** <br/> |**Office 365 企業版 F1** <br/> |
|使用者信箱  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |100 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
|封存信箱<sup>7, 8</sup> <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |無限制的<sup>1</sup> <br/> |無限制的<sup>1</sup> <br/> |無法使用<sup>4</sup> <br/> |
|共用信箱  <br/> |50 GB<sup>2</sup> <br/> |50 GB<sup>2</sup> <br/> |50 GB<sup>2</sup> <br/> |50 GB<sup>2,9</sup> <br/> |50 GB<sup>2,9</sup> <br/> |50 GB<sup>2</sup> <br/> |
|資源信箱  <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3,9</sup> <br/> |50 GB<sup>3,9</sup> <br/> |50 GB<sup>3</sup> <br/> |
|站台信箱<sup>5</sup> <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |無  <br/> |
|公用資料夾信箱  <br/> |50 GB<sup>6</sup> <br/> |50 GB<sup>6</sup> <br/> |50 GB<sup>6</sup> <br/> |100 GB<sup>6</sup> <br/> |100 GB<sup>6</sup> <br/> |無法使用  <br/> |
|群組信箱  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |
   
> [!NOTE]
> <sup>1</sup>每位使用者最初 100 GB 的存放區中收到封存信箱。自動展開封存開啟時，達到 100 GB 的儲存容量時自動新增額外儲存空間。如需詳細資訊，請參閱 ＜ [Overview of Office 365 中沒有限制之封存](https://go.microsoft.com/fwlink/?linkid=844060)。請參閱[Office 365 藍圖](http://go.microsoft.com/fwlink/?LinkId=509914)如需可用性的詳細資訊。<br/>  <sup>2</sup>來存取共用的信箱，使用者必須具有的 Exchange Online 授權。共用的信箱不需要個別授權。但沒有授權、 共用的信箱的限制為 50 GB。若要增加的信箱大小，必須被指派 E3 或 E5 授權。這會增加為 100 GB 的信箱。如果您想要啟用封存信箱或置於訴訟暫止狀態共用信箱，Exchange Online 計劃 2 授權或 Exchange Online 計劃 1 與 Exchange Online 封存授權則需要。如果您啟用封存信箱與共用信箱的自動展開封存，達到封存信箱 100 GB 儲存容量時自動新增額外儲存空間。<br/>  <sup>3</sup>資源信箱不需要授權。但沒有授權、 共用的信箱的限制為 50 GB。若要增加的信箱大小，必須被指派 E3 或 E5 授權。這會增加為 100 GB 的信箱。<br/>  <sup>4</sup> Exchange Online Kiosk 中不要包括封存信箱。不過，可以為透過 Exchange Online 封存的附加元件購買。如需詳細資訊，請參閱[Exchange Online 封存服務說明](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md)。<br/>  <sup>5</sup>站台信箱會建立及管理 SharePoint Online 中。如需詳細資訊，請參閱[使用 Office 365 中的網站信箱的準備](http://go.microsoft.com/fwlink/p/?LinkId=299131)。<br/>  <sup>6</sup>您有 1000 公用資料夾信箱，而且所有公用資料夾信箱的總大小上限為 50 TB。階層提供信箱皆有 100 個公用資料夾信箱。<br/>  <sup>7</sup>封存信箱僅可用來為其授權已套用封存的單一使用者或實體 （例如共用信箱） 的郵件。使用封存信箱作為儲存郵件從多個使用者或實體的方法被禁止。例如，IT 系統管理員無法建立共用的信箱且明確的目的封存 （透過 [副本] 或 [密件副本] 欄位中，或透過傳輸規則） 複製的使用者。請注意使用多人共用的信箱實際上不會儲存這些個別使用者的電子郵件。多個使用者都擁有存取，並為共用信箱傳送電子郵件。因此，只有儲存在共用信箱的電子郵件是指傳送至或來自它，*做為*共用信箱。<br/>  <sup>8</sup>如果您在 Exchange Online 中建立保留原則，郵件將會自動移到使用者的封存信箱只有當使用者的主要信箱大於 10 MB。保留原則不會執行自動小於 10 MB 的信箱。<br/>  <sup>9</sup>共用和資源信箱不需要授權。但沒有授權、 共用的信箱的限制為 50 GB。若要增加的信箱大小，必須被指派 E3 或 E5 授權。這會增加為 100 GB 的信箱。 
  
### <a name="storage-limits-across-standalone-plans"></a>不同獨立計劃中的儲存限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 方案 1** <br/> |**Exchange Online 方案 2** <br/> |**Exchange Online Kiosk** <br/> |
|使用者信箱  <br/> |2 GB<sup>1</sup> <br/> |50 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
|封存信箱<sup>8, 9</sup> <br/> |100 GB<sup>1</sup> <br/> |50 GB  <br/> |無限制的<sup>2</sup> <br/> |無法使用<sup>5</sup> <br/> |
|共用信箱  <br/> |2 GB<sup>1</sup> <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3,10</sup> <br/> |50 GB<sup>3</sup> <br/> |
|資源信箱  <br/> |2 GB<sup>1</sup> <br/> |50 GB<sup>4</sup> <br/> |50 GB<sup>4,10</sup> <br/> |50 GB<sup>4</sup> <br/> |
|公用資料夾信箱  <br/> |2 GB<sup>6</sup> <br/> |50 GB<sup>7</sup> <br/> |100 GB<sup>7</sup> <br/> |無法使用  <br/> |
|群組信箱  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |
   
> [!NOTE]
> <sup>1</sup>這是 Exchange Server 2013 組織的預設信箱大小。系統管理員可以變更這個值為其組織。沒有內部部署信箱的最大的儲存量限制。<br/>  <sup>2</sup>每位使用者最初 100 GB 的存放區中收到封存信箱。自動展開封存開啟時，達到 100 GB 的儲存容量時自動新增額外儲存空間。如需詳細資訊，請參閱 ＜ [Overview of Office 365 中沒有限制之封存](https://go.microsoft.com/fwlink/?linkid=844060)。請參閱 ＜ [Office 365 藍圖](http://go.microsoft.com/fwlink/?LinkId=509914)如需詳細資訊的自動展開可用性封存。<br/> <sup>3</sup>若要存取共用的信箱，使用者必須具有的 Exchange Online 授權。共用的信箱不需要個別授權。但沒有授權、 共用的信箱的限制為 50 GB。若要增加的信箱大小，必須被指派 Exchange Online 計劃 2 授權。這會增加為 100 GB 的信箱。如果您想要啟用封存信箱或置於訴訟暫止狀態共用信箱，Exchange Online 計劃 2 授權或 Exchange Online 計劃 1 與 Exchange Online 封存授權則需要。如果您啟用封存信箱與共用信箱的自動展開封存，達到封存信箱 100 GB 儲存容量時自動新增額外儲存空間。<br/> <sup>4</sup>資源信箱不需要授權。但沒有授權、 共用的信箱的限制為 50 GB。若要增加的信箱大小，必須被指派 Exchange Online 計劃 2 授權。這會增加為 100 GB 的信箱。<br/>  <sup>5</sup> Exchange Online Kiosk 中不要包括封存信箱。不過，可以為透過 Exchange Online 封存的附加元件購買。如需詳細資訊，請參閱[Exchange Online 封存服務說明](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md)。<br/>  <sup>6</sup>這是 Microsoft Exchange Server 2013 組織的預設信箱大小。系統管理員可以變更這個值為其組織。在 Exchange Server 2013，您有 100 個公用資料夾信箱，而且所有公用資料夾信箱的總大小上限為 50 TB。<br/>  <sup>7</sup> In Exchange Online 中，您有 1000 公用資料夾信箱，而且所有公用資料夾信箱的總大小上限為 50 TB。<br/>  <sup>8</sup>封存信箱僅可用來封存的單一使用者或實體已套用授權的郵件。禁止為方法使用的封存信箱來儲存來自多個使用者或實體的郵件。例如 IT 管理員無法建立共用的信箱並讓使用者將複製 （透過 [副本] 或 [密件副本] 欄位中，或透過傳輸規則） 共用的信箱的封存明確的目的。<br/>  <sup>9</sup>如果您在 Exchange Online 中建立保留原則，郵件將會自動移到使用者的封存信箱只有當使用者的主要信箱大於 10 MB。保留原則不會執行自動小於 10 MB 的信箱。<br/>  <sup>10</sup>共用和資源信箱不需要指派授權。但沒有授權，這些信箱是限制為 50 GB。若要增加的信箱大小，Exchange Online 計劃 2 授權必須被指派。這會增加為 100 GB 的信箱。 
  
> [!NOTE]
> 共用的信箱並不被設計直接登入。共用信箱本身的使用者帳戶應該留在**已停用**（或"中斷連線 」） 的狀態。 
  
## <a name="capacity-alerts"></a>容量提醒

Exchange Online 在使用者信箱接近容量上限或已達上限時提供三種通知類型：
  
- **警告** 使用者收到信箱接近大小限制上限的電子郵件警告。此警告的目的是讓使用者刪除不需要的郵件。 
    
- **禁止傳送** 當達到信箱大小限制時，使用者會收到禁止傳送通知電子郵件。在刪除足夠的電子郵件以將信箱容量降低至大小上限前，使用者無法傳送新的郵件。 
    
- **禁止傳送/接收** 當達到信箱大小上限時，Exchange Online 將拒絕任何來信，並將傳送未傳遞回報 (NDR) 給寄件者。寄件者可選擇稍後嘗試重新傳送該郵件。若再次收到訊息，使用者必須刪除電子郵件，直到信箱低於大小限制為止。 
    
### <a name="capacity-alerts-across-office-365-options"></a>不同 Office 365 選項中的容量警示

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商務基本版** <br/> |**Office 365 商務進階版** <br/> |**Office 365 企業版 E1** <br/> |**Office 365 企業版 E3** <br/> |**Office 365 企業版 E5** <br/> |**Office 365 企業版 F1** <br/> |
|警告  <br/> |49 GB  <br/> |49 GB  <br/> |49 GB  <br/> |98 GB  <br/> |98 GB  <br/> |1.96 GB  <br/> |
|禁止傳送  <br/> |49.5 GB  <br/> |49.5 GB  <br/> |49.5 GB  <br/> |99 GB  <br/> |99 GB  <br/> |1.98 GB  <br/> |
|禁止傳送/接收  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |100 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
   
### <a name="capacity-alerts-across-standalone-plans"></a>不同獨立計劃中的容量警示

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 方案 1** <br/> |**Exchange Online 方案 2** <br/> |**Exchange Online Kiosk** <br/> |
|警告  <br/> |1.9 GB<sup>1</sup> <br/> |49 GB  <br/> |98 GB  <br/> |1.96 GB  <br/> |
|禁止傳送  <br/> |2 GB<sup>1</sup> <br/> |49.5 GB  <br/> |99 GB  <br/> |1.98 GB  <br/> |
|禁止傳送/接收  <br/> |2.3 GB<sup>1</sup> <br/> |50 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
   
> [!NOTE]
> <sup>1</sup> 這是 Exchange Server 2013 組織的預設值。系統管理員可以為其組織變更此值。 
  
## <a name="mailbox-folder-limits"></a>信箱資料夾限制

這些限制是為了讓信箱容量不超過 Exchange Online 可支援的已知大小範圍。這些限制的目的在於防止每一資料夾有無限多個信箱項目、每一信箱有無限多個資料夾，或每一 Exchange Online 組織有無限多個公用資料夾。為了實用目的，信箱資料夾限制實際上不受限，且足以支援大多數的 Exchange Online 信箱和已移轉至 Exchange Online 的內部部署信箱。
  
- **每一信箱資料夾的郵件數目上限** 指定信箱資料夾的郵件數目上限。達到此限制時，新郵件便無法傳遞或儲存至資料夾。 
    
- **每一信箱資料夾的郵件數目警告** 指定在 Exchange Online 傳送警告訊息給信箱擁有者之前，信箱資料夾可以保留的郵件數目。達到此配額時，一天會傳送一次警告訊息。 
    
- **[可復原的項目] 資料夾中每一資料夾的郵件數目上限** 指定 [可復原的項目] 資料夾中每個資料夾可以包含的郵件數目上限。資料夾超過此限制時，就無法儲存新郵件。例如，如果 [可復原的項目] 資料夾中的 [刪除] 資料夾已超過郵件計數限制，而且信箱擁有者嘗試從其信箱中永久刪除項目，則刪除會失敗。 
    
- **[可復原的項目] 資料夾中每一資料夾的郵件數目警告** 指定在 Exchange Online 於應用程式事件記錄中記錄事件之前，[可復原的項目] 資料夾中每個資料夾可以保留的郵件數目。 
    
- **每一信箱資料夾的子資料夾數目上限** 指定可以在信箱資料夾中建立的子資料夾數目上限。達到此限制時，信箱擁有者就無法建立新的子資料夾。 
    
- **每一信箱資料夾的子資料夾數目警告** 指定在 Exchange Online 傳送警告訊息給信箱擁有者之前，可以在信箱資料夾中建立的子資料夾數目。達到此配額時，一天會傳送一次警告訊息。 
    
- **資料夾階層深度上限** 指定信箱的資料夾階層中的層級數目上限。達到此限制時，信箱擁有者就無法在信箱資料夾的資料夾階層中建立另一個層級。 
    
- **資料夾階層深度警告** 指定在 Exchange Online 傳送警告訊息給信箱擁有者之前，可以在信箱資料夾的資料夾階層中建立的層級數目。達到此配額時，一天會傳送一次警告訊息。 
    
- **最大公用資料夾數目** 指定完整公用資料夾階層中的最大公用資料夾數目。達到此限制時，必須先刪除現有公用資料夾，才能建立新的公用資料夾。 
    
- **每一公用資料夾的子資料夾數目上限** 指定可在公用資料夾中建立的子資料夾數目上限。達到此限制時，即無法在公用資料夾中建立新的子資料夾。 
    
- **每一公用資料夾的子資料夾數目警告** 指定在 Exchange Online 傳送警告訊息給資料夾擁有者之前，可以在公用資料夾中建立的子資料夾數目。如果沒有擁有者存在，則會傳送警告訊息給具有擁有者權限的使用者。達到此配額時，一天會傳送一次警告訊息。 
    
### <a name="mailbox-folder-limits-across-office-365-options"></a>不同 Office 365 選項中的信箱資料夾限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商務基本版** <br/> |**Office 365 商務進階版** <br/> |**Office 365 企業版 E1** <br/> |**Office 365 企業版 E3** <br/> |**Office 365 企業版 E5** <br/> |**Office 365 企業版 F1** <br/> |
|每一信箱資料夾的郵件數目上限  <br/> |1 百萬  <br/> |1 百萬  <br/> |1 百萬  <br/> |1 百萬  <br/> |1 百萬  <br/> |1 百萬  <br/> |
|每一信箱資料夾的郵件數目警告  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |
|[可復原的項目] 資料夾中每一資料夾的郵件數目上限  <br/> |3 百萬  <br/> |3 百萬  <br/> |3 百萬  <br/> |3 百萬  <br/> |3 百萬  <br/> |3 百萬  <br/> |
|主信箱中 [可復原的項目] 資料夾的儲存配額 (未保留)  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |
|主信箱中 [可復原的項目] 資料夾的儲存配額 (保留)  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |
|封存信箱中 [可復原的項目] 資料夾的儲存配額 (未保留)  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |無限制的<sup>2</sup> <br/> |無限制的<sup>2</sup> <br/> |30 GB  <br/> |
|封存信箱中 [可復原的項目] 資料夾的儲存配額 (保留)  <br/> |100 GB<sup>1</sup> <br/> |100 GB<sup>1</sup> <br/> |100 GB<sup>1</sup> <br/> |無限制的<sup>2</sup> <br/> |無限制的<sup>2</sup> <br/> |100 GB<sup>1</sup> <br/> |
|[可復原的項目] 資料夾中每一資料夾的郵件數目警告  <br/> |275 萬  <br/> |275 萬  <br/> |275 萬  <br/> |275 萬  <br/> |275 萬  <br/> |275 萬  <br/> |
|每一信箱資料夾的子資料夾數目上限  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |
|每一信箱資料夾的子資料夾數目警告  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |
|資料夾階層深度上限  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |
|資料夾階層深度警告  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|最大公用資料夾數目  <br/> | 500,000  <br/> | 500,000  <br/> | 500,000  <br/> | 500,000  <br/> | 500,000  <br/> |無法使用  <br/> |
|每一公用資料夾的子資料夾數目上限  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |無  <br/> |
|每一公用資料夾的子資料夾數目警告  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |無  <br/> |
   
> [!NOTE]
> <sup>1</sup>這是儲存配額可復原的項目] 資料夾的 [不整個封存信箱的配額。封存信箱儲存配額為無限制的使用者與 Exchange Online 計劃 2 授權或具有 Exchange Online 計劃 1 和 Exchange Online 封存的授權的使用者。如需增加可復原的項目配額資訊，請參閱[增加可復原的項目上的信箱配額保留](http://technet.microsoft.com/library/a8bdcbdd-9298-462f-b889-df26037a990c.aspx)。<br/> <sup>2</sup>中的封存信箱 [可復原的項目] 資料夾的初始儲存配額為 100 GB。自動展開封存開啟時，達到 [可復原的項目] 資料夾的儲存容量時自動新增額外儲存空間。如需詳細資訊，請參閱 ＜ [Overview of Office 365 中沒有限制之封存](https://go.microsoft.com/fwlink/?linkid=844060)。請參閱 ＜ [Office 365 藍圖](http://go.microsoft.com/fwlink/?LinkId=509914)如需詳細資訊的自動展開可用性封存。 
  
### <a name="mailbox-folder-limits-across-standalone-plans"></a>不同獨立計劃中的信箱資料夾限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 方案 1** <br/> |**Exchange Online 方案 2** <br/> |**Exchange Online Kiosk** <br/> |
|每一信箱資料夾的郵件數目上限  <br/> |沒有限制<sup>1</sup> <br/> |1 百萬  <br/> |1 百萬  <br/> |1 百萬  <br/> |
|每一信箱資料夾的郵件數目警告  <br/> |無限制  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |
|[可復原的項目] 資料夾中每一資料夾的郵件數目上限  <br/> |無限制  <br/> |3 百萬  <br/> |3 百萬  <br/> |3 百萬  <br/> |
|主信箱中 [可復原的項目] 資料夾的儲存配額 (未保留)  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |
|主信箱中 [可復原的項目] 資料夾的儲存配額 (保留)  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |
|封存信箱中 [可復原的項目] 資料夾的儲存配額 (未保留)  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |
|封存信箱中 [可復原的項目] 資料夾的儲存配額 (保留)  <br/> |100 GB<sup>2</sup> <br/> |100 GB<sup>2</sup> <br/> |無限制的<sup>3</sup> <br/> |無限制的<sup>3</sup> <br/> |
|[可復原的項目] 資料夾中每一資料夾的郵件數目警告  <br/> |無限制  <br/> |275 萬  <br/> |275 萬  <br/> |275 萬  <br/> |
|每一信箱資料夾的子資料夾數目上限  <br/> |無限制  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|每一信箱資料夾的子資料夾數目警告  <br/> |無限制  <br/> |900  <br/> |900  <br/> |900  <br/> |
|資料夾階層深度上限  <br/> |無限制  <br/> |300  <br/> |300  <br/> |300  <br/> |
|資料夾階層深度警告  <br/> |無限制  <br/> |250  <br/> |250  <br/> |250  <br/> |
|最大公用資料夾數目  <br/> |1,000,000  <br/> |100,000  <br/> |100,000  <br/> |無法使用  <br/> |
|每一公用資料夾的子資料夾數目上限  <br/> |不適用  <br/> |1,000  <br/> |1,000  <br/> |無  <br/> |
|每一公用資料夾的子資料夾數目警告  <br/> |不適用  <br/> |900  <br/> |900  <br/> |無  <br/> |
   
> [!NOTE]
> <sup>1</sup> Microsoft 建議不得超過 1000000 個每一信箱資料夾的郵件。><br/> <sup>2</sup>這是儲存配額可復原的項目] 資料夾的 [不整個封存信箱的配額。封存信箱儲存配額為無限制的使用者與 Exchange Online 計劃 2 授權或具有 Exchange Online 計劃 1 和 Exchange Online 封存的授權的使用者。如需增加可復原的項目配額資訊，請參閱[增加可復原的項目上的信箱配額保留](http://technet.microsoft.com/library/a8bdcbdd-9298-462f-b889-df26037a990c.aspx)。<br/> <sup>3</sup>封存信箱中的 [可復原的項目] 資料夾的初始儲存配額為 100 GB。自動展開封存開啟時，達到 [可復原的項目] 資料夾的儲存容量時自動新增額外儲存空間。如需詳細資訊，請參閱 ＜ [Overview of Office 365 中沒有限制之封存](https://go.microsoft.com/fwlink/?linkid=844060)。請參閱 ＜ [Office 365 藍圖](http://go.microsoft.com/fwlink/?LinkId=509914)如需詳細資訊的自動展開可用性封存。 
  
## <a name="message-limits"></a>郵件限制

下列限制會套用至每封電子郵件。
  
- **郵件大小限制** 為避免大型郵件封鎖其他郵件的遞送，以及影響所有使用者的服務效能，需要設定郵件大小限制。這些限制包含附件，且適用於整個組織內的所有郵件 (內送、外寄和內部)。大於此上限的郵件將不會傳遞，而寄件者將收到未傳遞回報 (NDR)。雖然郵件大小上限無法上調、下調或依各使用者為基準設定，管理員仍可建立傳輸規則來限制任何個別附件的最高大小上限。若要深入了解，請參閱 [Office 365 現在可支援較大的電子郵件訊息](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/)。
    
    > [!NOTE]
    > 特定電子郵件用戶端可擁有較低的郵件大小或可限制個別檔案附件的大小為小於 Exchange Online 郵件大小上限的值。 
  
- **郵件標頭大小限制**指定在郵件中的所有郵件標頭欄位的大小上限。目前的限制為 256 KB。如果所有的郵件標頭的總大小超過 256 KB，Exchange Online 會拒絕此郵件錯誤"552 5.3.4 標頭大小超過固定大小上限。 」不被視為郵件內文或附件的大小。因為標頭欄位純文字、 標頭大小決定以每個標頭] 欄位中的字元數與標頭欄位的總數。每個文字字元會耗用 1 個位元組。

- **主旨長度限制** 電子郵件主旨行中允許的文字字元數目上限。 
    
- **檔案附件限制** 電子郵件中允許的檔案附件數目上限。即使所有檔案附件的大小總計沒有違反郵件大小限制，郵件中允許的附件數目仍然具有限制。此限制會由 Multipart 郵件限制控制。 
    
- **檔案附件大小限制** 單一附件的檔案大小上限。 
    
    > [!NOTE]
    > 這是單一附件的檔案大小上限。個別用戶端方案 (包括 Outlook Web App) 可能會規定附件大小需低於此上限。Exchange ActiveSync 未針對個別附件實作附件大小限制。Exchange ActiveSync 郵件的所有附件大小總和必須小於郵件大小限制。 
  
- **Multipart 郵件限制** MIME Multipart 郵件中允許的郵件內文部分數目上限。此限制也會控制郵件允許的檔案附件數目上限。 
    
- **內嵌郵件深度限制** 電子郵件中允許的轉寄電子郵件數目上限。 
    
### <a name="message-limits-across-office-365-options"></a>不同 Office 365 選項中的郵件限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商務基本版** <br/> |**Office 365 商務進階版** <br/> |**Office 365 企業版 E1** <br/> |**Office 365 企業版 E3** <br/> |**Office 365 企業版 E5** <br/> |**Office 365 企業版 F1** <br/> |
|郵件大小限制 - Outlook  <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |
|郵件大小限制 - OWA  <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |
|郵件大小限制 - Outlook for Mac  <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |
|郵件大小限制 - 移轉  <br/> |150 MB <sup>4</sup> <br/> |150 MB <sup>4</sup> <br/> |150 MB <sup>4</sup> <br/> |150 MB <sup>4</sup> <br/> |150 MB <sup>4</sup> <br/> |150 MB <sup>4</sup> <br/> |
|加密郵件的大小限制 (適用於使用 Office 365 郵件加密與新功能的訂閱者)<sup>5</sup> <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|加密郵件的大小限制 (適用於使用舊版 Office 365 郵件加密的訂閱者)<sup>5</sup> <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
|主旨長度限制  <br/> |255 個字元  <br/> |255 個字元  <br/> |255 個字元  <br/> |255 個字元  <br/> |255 個字元  <br/> |255 個字元  <br/> |
|檔案附件限制  <br/> |250 個附件  <br/> |250 個附件  <br/> |250 個附件  <br/> |250 個附件  <br/> |250 個附件  <br/> |250 個附件  <br/> |
|檔案附件大小限制 - Outlook  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|檔案附件大小限制 - OWA <sup>6</sup> <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |
|檔案附件大小限制 - Outlook for Mac  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Multipart 郵件限制  <br/> |250 個部分  <br/> |250 個部分  <br/> |250 個部分  <br/> |250 個部分  <br/> |250 個部分  <br/> |250 個部分  <br/> |
|內嵌郵件深度限制  <br/> |30 封內嵌郵件  <br/> |30 封內嵌郵件  <br/> |30 封內嵌郵件  <br/> |30 封內嵌郵件  <br/> |30 封內嵌郵件  <br/> |30 封內嵌郵件  <br/> |
   
> [!NOTE]
> <sup>1</sup>預設郵件大小上限為 Office 365 信箱為 25 MB。Office 365 系統管理員可以指定自訂限制 1 MB 和 150 MB 之間。不過，您可以傳送或接收之郵件的大小也取決於您的電子郵件用戶端或方案支援的項目。如需自訂允許的郵件大小上限為組織的詳細資訊，請參閱[Office 365 現在支援較大的電子郵件訊息](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/)。<br/> <sup>2</sup>您可以傳送和接收向上 150 MB （其中郵件永遠不會保留 Office 365 資料中心） 的 Office 365 使用者之間的郵件。外部 Office 365 資料中心會路由傳送的郵件會受到編碼的增加，在此案例的郵件大小上限為 112 MB 其他 33%轉譯。<br/> <sup>3</sup> OWA 帳戶的郵件可能會受限於編碼增加 33%和限制的郵件大小在其中您可以傳送給 25%小於設定的設定值。例如，如果您在自訂您的設定為 100 MB 的郵件大小上限，您可以傳送郵件不得大於 75 MB。<br/> <sup>4</sup> Exchange Online 會計算要移動至 Exchange Online 的郵件大小。Exchange Server 2013 之前的 Exchange 版本可能會報告較小的項目大小。此限制適用於使用任何支援的 Exchange 信箱複寫服務來移動基本移轉。其他移轉方法 (轉換、分段、IMAP、PST) 和其他協力廠商工具都受限於一般訊息大小限制。<br/> <sup>5</sup> 如需 OME 與新功能的相關資訊，請參閱 [設定以 Azure 資訊保護為基礎所建置的全新 Office 365 郵件加密功能](https://support.office.com/en-us/article/Set-up-new-Office-365-Message-Encryption-capabilities-built-on-top-of-Azure-Information-Protection-7ff0c040-b25c-4378-9904-b1b50210d00e?ui=en-US&amp;rs=en-US&amp;ad=US)。<br/> <sup>6</sup> 您無法附加超過 35 MB 的單一檔案。此外，您也無法附加全部加起來超過 35 MB 的檔案。例如，如果附加一個 34 MB 的檔案，您只能再額外附加 1 MB 的檔案。 
  
### <a name="message-limits-across-standalone-options"></a>不同獨立選項中的郵件限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 方案 1** <br/> |**Exchange Online 方案 2** <br/> |**Exchange Online Kiosk** <br/> |
|郵件大小限制 - Outlook  <br/> |10 MB<sup>4</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>2</sup> <br/> |
|郵件大小限制 - OWA  <br/> |10 MB<sup>4</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |
|郵件大小限制 - Outlook for Mac  <br/> |10 MB<sup>4</sup> <br/> |150 MB  <br/> |150 MB  <br/> ||
|郵件大小限制 - 移轉  <br/> |不適用  <br/> |150 MB <sup>5</sup> <br/> |150 MB <sup>5</sup> <br/> |150 MB <sup>5</sup> <br/> |
|加密郵件的大小限制 (適用於使用 Office 365 郵件加密與新功能的訂閱者)<sup>6</sup> <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|加密郵件的大小限制 (適用於使用舊版 Office 365 郵件加密的訂閱者)<sup>6</sup> <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
|主旨長度限制  <br/> |255 個字元  <br/> |255 個字元  <br/> |255 個字元  <br/> |255 個字元  <br/> |
|檔案附件限制  <br/> |1024 附件<sup>4</sup> <br/> |250 個附件  <br/> |250 個附件  <br/> |250 個附件  <br/> |
|檔案附件大小限制 - Outlook  <br/> |35 MB<sup>4</sup> <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|檔案附件大小限制 - OWA  <br/> |35 MB<sup>4</sup> <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |
|檔案附件大小限制 - Outlook for Mac  <br/> |35 MB<sup>4</sup> <br/> |150 MB  <br/> |150 MB  <br/> |35 MB  <br/> |
|Multipart 郵件限制  <br/> |250 個部分  <br/> |250 個部分  <br/> |250 個部分  <br/> |250 個部分  <br/> |
|內嵌郵件深度限制  <br/> |30 封內嵌郵件  <br/> |30 封內嵌郵件  <br/> |30 封內嵌郵件  <br/> |30 封內嵌郵件  <br/> |
   
> [!NOTE]
> <sup>1</sup> office 365 系統管理員可以指定自訂限制 1 MB 和 150 MB 之間。不過，您可以傳送或接收之郵件的大小也取決於您的電子郵件用戶端或方案支援的項目。如需自訂允許的郵件大小上限為組織的詳細資訊，請參閱[Office 365 現在支援較大的電子郵件訊息](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/)。<br/> <sup>2</sup>您可以傳送和接收向上 150 MB （其中郵件永遠不會保留 Office 365 資料中心） 的 Office 365 使用者之間的郵件。外部 Office 365 資料中心會路由傳送的郵件會受到編碼的增加，在此案例的郵件大小上限為 112 MB 其他 33%轉譯。<br/> <sup>3</sup> OWA 帳戶的郵件可能會受限於編碼增加 33%和限制的郵件大小在其中您可以傳送給 25%小於設定的設定值。例如，如果您在自訂您的設定為 100 MB 的郵件大小上限，您可以傳送郵件不得大於 75 MB。<br/> <sup>4</sup>這是 Exchange Server 2013 組織的預設限制。系統管理員可以變更這個值為其組織。<br/> <sup>5</sup> Exchange Online 會利用計算移至 Exchange Online 郵件的大小。Exchange Server 2013 以前的 Exchange 版本可能會回報較小的項目大小。<br/> <sup>6</sup> 如需 OME 與新功能的相關資訊，請參閱 [設定以 Azure 資訊保護為基礎所建置的全新 Office 365 郵件加密功能](https://support.office.com/en-us/article/Set-up-new-Office-365-Message-Encryption-capabilities-built-on-top-of-Azure-Information-Protection-7ff0c040-b25c-4378-9904-b1b50210d00e?ui=en-US&amp;rs=en-US&amp;ad=US)。 
  
## <a name="receiving-and-sending-limits"></a>接收及傳送限制

接收及傳送限制會套用至郵件、寄件者或收件者，以便抵禦垃圾郵件和大量郵寄蠕蟲或病毒。這些限制有助於保護系統的健康情況，並確保使用者安全。
  
### <a name="receiving-limits"></a>接受限制

接受限制會套用至使用者、群組或公用資料夾每小時能接收的訊息數量。這會同時套用至從網際網路和內部部署伺服器接收的訊息。當超過接收限制時，任何傳送到該信箱的電子郵件將會收到未傳遞報告，指出信箱已超過最大傳遞臨界值。一個小時之後，將會重新整理限制，而信箱就能夠再度接收郵件。
  
||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商務基本版** <br/> |**Office 365 商務進階版 Office** <br/> |**Office 365 企業版 E1** <br/> |**Office 365 企業版 E3** <br/> |**Office 365 企業版 E5** <br/> |**Office 365 企業版 F1** <br/> |
|已接收的訊息  <br/> |每小時 3600 訊息  <br/> |每小時 3600 訊息  <br/> |每小時 3600 訊息  <br/> |每小時 3600 訊息  <br/> |每小時 3600 封訊息  <br/> |每小時 3600 封訊息  <br/> |
   
### <a name="sending-limits"></a>傳送限制

傳送限制會套用至使用者可以從 Exchange Online 帳戶傳送的收件者數量、訊息數量和每封訊息的收件者數量。
  
> [!NOTE]
> 就儲存於組織通訊錄中的通訊群組而言，系統會將群組視為一位收件者。就儲存於信箱之 [連絡人] 資料夾中的通訊群組而言，則系統將群組中的成員視為個別收件者。 
  
- **收件者流量限制** 為了減少來路不明的大量郵件遞送，Exchange Online 擁有防止使用者與應用程式傳送大量電子郵件的收件者限制。這些限制會套用至每位使用者的所有外寄和內部郵件。 
    
    > [!NOTE]
    > Exchange Online 客戶若需要傳送合法的大量商業電子郵件 (例如客戶電子報)，應使用專門提供這些服務的第三方供應商。 
  
- **收件者限制** 此為單封電子郵件中 [收件者:]、[副本:] 和 [密件副本:]欄位允許的收件者數量上限。 
    
    > [!NOTE]
    > 基於收件者流量限制和收件者限制的用意，組織共用通訊錄中所儲存的通訊群組會算為一位收件者。在個人通訊群組清單中，每位收件者皆分開計算。 
  
- **郵件流量限制**郵件流量限制會決定使用者在指定時間內從 Exchange Online帳戶傳送的郵件數量。此限制可協助防止單一寄件者的系統資源使用量過高。如果使用者提交郵件的速率超過透過 SMTP 用戶端提交的限制，則會拒絕郵件，用戶端必須重試。 
    
#### <a name="sending-limits-across-office-365-options"></a>不同 Office 365 選項的傳送限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商務基本版** <br/> |**Office 365 商務進階版** <br/> |**Office 365 企業版 E1** <br/> |**Office 365 企業版 E3** <br/> |**Office 365 企業版 E5** <br/> |**Office 365 企業版 F1** <br/> |
|收件者流量限制  <br/> |每天 10,000 位收件者  <br/> |每天 10,000 位收件者  <br/> |每天 10,000 位收件者  <br/> |每天 10,000 位收件者  <br/> |每天 10,000 位收件者  <br/> |每天 10,000 位收件者  <br/> |
|收件者限制  <br/> |500 位收件者  <br/> |500 位收件者  <br/> |500 位收件者  <br/> |500 位收件者  <br/> |500 位收件者  <br/> |500 位收件者  <br/> |
|收件者 proxy 位址限制  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |
|郵件流量限制  <br/> |每分鐘 30 封郵件  <br/> |每分鐘 30 封郵件  <br/> |每分鐘 30 封郵件  <br/> |每分鐘 30 封郵件  <br/> |每分鐘 30 封郵件  <br/> |每分鐘 30 封郵件  <br/> |
   
#### <a name="sending-limits-across-standalone-options"></a>不同獨立選項的傳送限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 方案 1** <br/> |**Exchange Online 方案 2** <br/> |**Exchange Online Kiosk** <br/> |
|收件者流量限制  <br/> |沒有限制<sup>1</sup> <br/> |每天 10,000 位收件者  <br/> |每天 10,000 位收件者  <br/> |每天 10,000 位收件者  <br/> |
|收件者限制  <br/> |500 收件者<sup>1</sup> <br/> |500 位收件者  <br/> |500 位收件者  <br/> |500 位收件者  <br/> |
|收件者 proxy 位址限制  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |
   
> [!NOTE]
> <sup>1</sup> 這是 Exchange Server 2013 組織的預設限制。系統管理員可以為其組織變更此值。 
  
## <a name="reporting-and-message-trace-limits"></a>報告和郵件追蹤限制
<a name="bkmk_Reporting_Message_Trace_Limits"> </a>

如需報告和郵件追蹤限制，請參閱 [Exchange Online Protection 的報告和郵件追蹤](http://go.microsoft.com/fwlink/p/?LinkId=394248)中的「報告和郵件追蹤資料可用性和延遲」一節。
  
## <a name="retention-limits"></a>保留限制
<a name="RetentionLimits"> </a>

這些限制會控制可存取 [收件匣] 內特定資料夾中項目的時間長度。
  
- **[刪除的郵件] 資料夾保留期間** 自動移除項目之前可保留在 [刪除的郵件] 資料夾中的天數上限。 
    
- **從 [刪除的郵件] 資料夾移除之項目的保留期間** 從 [刪除的郵件] 資料夾移除的項目在被永久刪除之前可保留的天數上限。 
    
- **[垃圾郵件] 資料夾保留期間** 自動移除項目之前可保留在 [垃圾郵件] 資料夾中的天數上限。 
    
### <a name="retention-limits-across-office-365-options"></a>不同 Office 365 選項中的保留限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商務基本版** <br/> |**Office 365 商務進階版** <br/> |**Office 365 企業版 E1** <br/> |**Office 365 企業版 E3** <br/> |**Office 365 企業版 E5** <br/> |**Office 365 企業版 F1** <br/> |
|[刪除的郵件] 資料夾保留期間  <br/> |沒有限制<sup>1</sup> <br/> |沒有限制<sup>1</sup> <br/> |沒有限制<sup>1</sup> <br/> |沒有限制<sup>1</sup> <br/> |沒有限制<sup>1</sup> <br/> |沒有限制<sup>1</sup> <br/> |
|從 [刪除的郵件] 資料夾移除之項目的保留期間  <br/> |14 天<sup>1</sup> <br/> |14 天<sup>1</sup> <br/> |14 天<sup>1</sup> <br/> |14 天<sup>1</sup> <br/> |14 天<sup>1</sup> <br/> |14 天<sup>1</sup> <br/> |
|[垃圾郵件] 資料夾保留期間  <br/> |30 天  <br/> |30 天  <br/> |30 天  <br/> |30 天  <br/> |30 天  <br/> |30 天  <br/> |
   
> [!NOTE]
> <sup>1</sup> 這是預設限制。系統管理員可以為其組織變更此值。 
  
### <a name="retention-limits-across-standalone-options"></a>不同獨立選項中的保留限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 方案 1** <br/> |**Exchange Online 方案 2** <br/> |**Exchange Online Kiosk** <br/> |
|[刪除的郵件] 資料夾保留期間  <br/> |沒有限制<sup>1</sup> <br/> |沒有限制<sup>1</sup> <br/> |沒有限制<sup>1</sup> <br/> |沒有限制<sup>1</sup> <br/> |
|從 [刪除的郵件] 資料夾移除之項目的保留期間  <br/> |14 天<sup>1</sup> <br/> |14 天<sup>2</sup> <br/> |14 天<sup>2</sup> <br/> |14 天<sup>2</sup> <br/> |
|[垃圾郵件] 資料夾保留期間  <br/> |2 年<sup>1</sup> <br/> |30 天  <br/> |30 天  <br/> |30 天  <br/> |
   
> [!NOTE]
> <sup>1</sup> 這是預設限制。系統管理員可以為其組織變更此值。<br/> <sup>2</sup>這是 Exchange Online 組織的預設值。系統管理員可以變更這個值為其組織中信箱的 30 天的最大值。 
  
## <a name="distribution-group-limits"></a>通訊群組限制

這些限制會套用至組織共用通訊錄中的通訊群組。
  
- **通訊群組成員人數上限** 收件者總數是在通訊群組擴充之後決定的。 
    
- **傳送郵件給大型通訊群組的限制** 通訊群組如果包含這項限制所指定的成員人數，就必須設有傳遞管理或郵件核准選項。傳遞管理會指定一份寄件者清單，只有這些寄件者才能傳送郵件至此通訊群組。郵件核准會指定一位或多位仲裁者，郵件必須通過他們的核准才能傳送至此通訊群組。 
    
- **大型通訊群組的郵件大小上限** 如果郵件是要傳送給 5,000 位以上的收件者，則該郵件大小不可超過此限制。如果郵件大小超過限制，郵件不會傳遞出去，而且寄件者會收到未傳遞回報 (NDR)。收件者總數是在通訊群組擴充之後決定的。 
    
### <a name="distribution-group-limits-across-office-365-options"></a>不同 Office 365 選項中的通訊群組限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商務基本版** <br/> |**Office 365 商務進階版** <br/> |**Office 365 企業版 E1** <br/> |**Office 365 企業版 E3** <br/> |**Office 365 企業版 E5** <br/> |**Office 365 企業版 F1** <br/> |
|通訊群組成員數目上限<sup>1</sup> <br/> |100,000 位成員  <br/> |100,000 位成員  <br/> |100,000 位成員  <br/> |100,000 位成員  <br/> |100,000 位成員  <br/> |100,000 位成員  <br/> |
|傳送郵件給大型通訊群組的限制  <br/> |5,000 位以上成員  <br/> |5,000 位以上成員  <br/> |5,000 位以上成員  <br/> |5,000 位以上成員  <br/> |5,000 位以上成員  <br/> |5,000 位以上成員  <br/> |
|通訊群組與至 100000 之間 5000 個成員的郵件大小上限  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
|100000 或多個成員的通訊群組的郵件大小上限  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |
|通訊群組擁有者數目上限  <br/> |10   <br/> |10   <br/> |10   <br/> |10   <br/> |10   <br/> |10   <br/> |
|使用者可以建立的群組數目上限  <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup>如果您使用 Azure Active Directory DirSync，您可以對 Azure Active Directory 同步處理從內部部署 Active Directory 的通訊群組成員數目上限為 15000。如果您使用 Azure AD 連線，該號碼為 50000。<br/> <sup>2</sup> 這項限制也適用於系統管理員。 
  
### <a name="distribution-group-limits-across-standalone-options"></a>不同獨立選項中的通訊群組限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 方案 1** <br/> |**Exchange Online 方案 2** <br/> |**Exchange Online Kiosk** <br/> |
|通訊群組成員數目上限  <br/> |100,000 位成員<sup>1</sup> <br/> |100,000 位成員  <br/> |100,000 位成員  <br/> |100,000 位成員  <br/> |
|傳送郵件給大型通訊群組的限制  <br/> |5,000 位以上成員<sup>1</sup> <br/> |5,000 位以上成員  <br/> |5,000 位以上成員  <br/> |5,000 位以上成員  <br/> |
|通訊群組擁有者數目上限  <br/> |10   <br/> |10   <br/> |10   <br/> |10   <br/> |
|使用者可以建立的群組數目上限  <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> 這是 Exchange Server 2013 組織的預設限制。系統管理員可以為其組織變更此值。<br/> <sup>2</sup> 這項限制也適用於系統管理員。 
  
## <a name="journal-transport-and-inbox-rule-limits"></a>日誌、傳輸和收件匣規則限制

下列清單包括套用至日誌規則、傳輸規則 (也稱為組織規則) 的限制，以及套用至「收件匣」規則的限制。「收件匣」規則是由個別使用者所設定，並且套用至由個別使用者的信箱所傳送和接收的郵件。
  
- **規則數目上限** 組織中可以存在的日誌規則數目上限。 
    
- **傳輸規則數目上限** 組織中可以存在的規則數目上限。 
    
- **個別傳輸規則的大小上限** 單一傳輸規則中可以使用的字元數目上限。這些字元是用在條件、例外狀況和動作中。 
    
- **所有傳輸規則中使用之所有規則運算式的字元限制** 在組織中的所有傳輸規則條件及例外狀況中，所有規則運算式所使用的字元總數。您可以有幾條規則使用又長又複雜的規則運算式，也可以有許多規則使用簡單的規則運算式。 
    
- **附件內容的掃描限制** 傳輸規則條件可讓您檢查郵件附件的內容，但只會檢查從附件擷取的第 1 MB 文字。此 1 MB 限制是指從附件擷取的文字，而不是附件的檔案大小。例如，2 MB 檔案可能包含小於 1 MB 的文字，所以會檢查所有的文字 
    
- **所有傳輸規則新增到郵件的收件者人數上限** 當郵件由不同的傳輸規則進行處理時，可新增到郵件中的收件者人數是有限制的。達到此上限之後，就不再將任何其餘的收件者新增到郵件中。此外，傳輸規則也不能將通訊群組新增到郵件中。 
    
- **轉寄者限制** 可為收件匣或傳輸規則設定之具有重新導向動作的收件者人數上限。如果為某個規則設定的郵件重新導向收件者數目超過此數目，系統將不會套用該規則，而任何符合該規則條件的郵件將不會被重新導向到規則中所列的任何收件者。 
    
- **重新導向郵件的次數** 根據收件匣規則自動重新導向、轉寄或回覆郵件的次數。例如，使用者 A 的收件匣規則會根據寄件者，將郵件重新導向到使用者 B。使用者 B 的收件匣規則會根據主旨行中的關鍵字，將郵件轉寄給使用者 C。如果某封郵件同時符合這兩項條件，該郵件將只會傳送給使用者 B 而不會轉寄給使用者 C，因為只允許重新導向一次。在此情況下，會捨棄郵件，而未將未傳遞回報 (NDR) 傳送給使用者 B，指出未將郵件傳遞給使用者 C。 
    
### <a name="journal-transport-and-inbox-rule-limits-across-office-365-options"></a>不同 Office 365 選項中的日誌、傳輸和收件匣規則限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商務基本版** <br/> |**Office 365 商務進階版** <br/> |**Office 365 企業版 E1** <br/> |**Office 365 企業版 E3** <br/> |**Office 365 企業版 E5** <br/> |**Office 365 企業版 F1** <br/> |
|日誌規則數目上限  <br/> |10 條規則  <br/> |10 條規則  <br/> |10 條規則  <br/> |10 條規則  <br/> |10 條規則  <br/> |10 條規則  <br/> |
|傳輸規則數目上限  <br/> |300 條規則  <br/> |300 條規則  <br/> |300 條規則  <br/> |300 條規則  <br/> |300 條規則  <br/> |300 條規則  <br/> |
|個別傳輸規則的大小上限  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |
|所有傳輸規則中使用之所有規則運算式的字元限制  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |
|附件內容的掃描限制  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |
|所有傳輸規則新增到郵件中的收件者人數上限  <br/> |100 位收件者  <br/> |100 位收件者  <br/> |100 位收件者  <br/> |100 位收件者  <br/> |100 位收件者  <br/> |100 位收件者  <br/> |
|轉寄者限制  <br/> |10 位收件者  <br/> |10 位收件者  <br/> |10 位收件者  <br/> |10 位收件者  <br/> |10 位收件者  <br/> |10 位收件者  <br/> |
|重新導向郵件的次數  <br/> |1 次重新導向  <br/> |1 次重新導向  <br/> |1 次重新導向  <br/> |1 次重新導向  <br/> |1 次重新導向  <br/> |1 次重新導向  <br/> |
   
### <a name="journal-transport-and-inbox-rule-limits-across-standalone-options"></a>不同獨立選項中的日誌、傳輸和收件匣規則限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 方案 1** <br/> |**Exchange Online 方案 2** <br/> |**Exchange Online Kiosk** <br/> |
|日誌規則數目上限  <br/> |無限制  <br/> |10 條規則  <br/> |10 條規則  <br/> |10 條規則  <br/> |
|傳輸規則數目上限  <br/> |無限制  <br/> |300 條規則  <br/> |300 條規則  <br/> |300 條規則  <br/> |
|個別傳輸規則的大小上限  <br/> |40 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |
|所有傳輸規則中使用之所有規則運算式的字元限制  <br/> |無限制  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |
|所有傳輸規則新增到郵件中的收件者人數上限  <br/> |無限制  <br/> |100 位收件者  <br/> |100 位收件者  <br/> |100 位收件者  <br/> |
|轉寄者限制  <br/> |無限制  <br/> |10 位收件者  <br/> |10 位收件者  <br/> |10 位收件者  <br/> |
|重新導向郵件的次數  <br/> |3 次重新導向  <br/> |1 次重新導向  <br/> |1 次重新導向  <br/> |1 次重新導向  <br/> |
  
## <a name="moderation-limits"></a>仲裁限制
<a name="ModerationLimits"> </a>

這些限制會控制在通訊群組和傳輸規則套用之郵件核准所採用的仲裁設定。
  
- **仲裁信箱的大小上限** 如果仲裁信箱超過此限制，需要仲裁的郵件會就包含在傳回給寄件者的未傳遞回報 (NDR) 中。 
    
- **仲裁者人數上限** 可指派給單一仲裁通訊群組的仲裁者人數上限，或是可使用單一傳輸規則新增到郵件中的仲裁者人數上限。請注意，您無法將通訊群組指定為仲裁者。 
    
- **等候仲裁之郵件的到期日** 根據預設，等候仲裁的郵件會在兩天後過期。不過，過期的仲裁郵件處理會每七天執行一次，也就是說，仲裁郵件會在兩天到九天之間的任何時候過期。 
    
- **過期仲裁通知郵件的最大速率** 這項限制會設定過期仲裁郵件一小時內的通知郵件數目上限。這項限制是設置在資料中心內的每個信箱資料庫上。 
    
    在大量使用期間，某些寄件者可能不會收到有關仲裁郵件已過期的通知郵件。不過，這些通知還是可以使用傳遞回報找到。
    
### <a name="moderation-limits-across-office-365-options"></a>不同 Office 365 選項中的仲裁限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商務基本版** <br/> |**Office 365 商務進階版** <br/> |**Office 365 企業版 E1** <br/> |**Office 365 企業版 E3** <br/> |**Office 365 企業版 E5** <br/> |**Office 365 企業版 F1** <br/> |
|仲裁信箱的大小上限  <br/> |10GB  <br/> |10GB  <br/> |10GB  <br/> |10GB  <br/> |10GB  <br/> |10 GB  <br/> |
|仲裁者人數上限  <br/> |10 位仲裁者  <br/> |10 位仲裁者  <br/> |10 位仲裁者  <br/> |10 位仲裁者  <br/> |10 位仲裁者  <br/> |10 位仲裁者  <br/> |
|等候仲裁的郵件到期日  <br/> |2 天  <br/> |2 天  <br/> |2 天  <br/> |2 天  <br/> |2 天  <br/> |2 天  <br/> |
|過期仲裁通知郵件的最大速率  <br/> |每小時 300 個過期通知  <br/> |每小時 300 個過期通知  <br/> |每小時 300 個過期通知  <br/> |每小時 300 個過期通知  <br/> |每小時 300 個過期通知  <br/> |每小時 300 個過期通知  <br/> |
   
### <a name="moderation-limits-across-standalone-options"></a>不同獨立選項中的仲裁限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 方案 1** <br/> |**Exchange Online 方案 2** <br/> |**Exchange Online Kiosk** <br/> |
|仲裁信箱的大小上限  <br/> |沒有限制<sup>1</sup> <br/> |10 GB  <br/> |10GB  <br/> |10 GB  <br/> |
|仲裁者人數上限  <br/> |無限制  <br/> |10 位仲裁者  <br/> |10 位仲裁者  <br/> |10 位仲裁者  <br/> |
|等候仲裁的郵件到期日  <br/> |5 天<sup>1</sup> <br/> |2 天  <br/> |2 天  <br/> |2 天  <br/> |
|過期仲裁通知郵件的最大速率  <br/> |每小時 300 個過期通知  <br/> |每小時 300 個過期通知  <br/> |每小時 300 個過期通知  <br/> |每小時 300 個過期通知  <br/> |
   
> [!NOTE]
> <sup>1</sup> 這是 Exchange Server 2013 組織的預設限制。系統管理員可以為其組織變更此值。 
  
## <a name="exchange-activesync-limits"></a>Exchange ActiveSync 限制
<a name="BKMK_ExchangeActiveSync_Limits"> </a>

下列限制適用於 Microsoft Exchange ActiveSync，這是一種用戶端通訊協定，可以同步處理行動裝置與 Exchange 之間的信箱資料。 
  
- **Exchange ActiveSync 裝置限制**：每個信箱的 Exchange ActiveSync 裝置數目上限。 
    
- **Exchange ActiveSync 裝置刪除限制**：Exchange 系統管理員可以在一個月內刪除的 Exchange ActiveSync 裝置數目上限。 
    
- **Exchange ActiveSync 檔案附件限制**：Exchange ActiveSync 裝置可以傳送或接收的郵件檔案附件大小上限。 
    
### <a name="exchange-activesync-limits-across-office-365-options"></a>跨 Office 365 選項的 Exchange ActiveSync 限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商務基本版** <br/> |**Office 365 商務進階版** <br/> |**Office 365 企業版 E1** <br/> |**Office 365 企業版 E3** <br/> |**Office 365 企業版 E5** <br/> |**Office 365 企業版 F1** <br/> |
|Exchange ActiveSync 裝置限制  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |
|Exchange ActiveSync 裝置刪除限制  <br/> |20 個  <br/> |20 個  <br/> |20 個  <br/> |20 個  <br/> |20 個  <br/> |20 個  <br/> |
|Exchange ActiveSync 檔案附件限制  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
   
### <a name="exchange-activesync-limits-across-standalone-options"></a>跨獨立選項的 Exchange ActiveSync 限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 方案 1** <br/> |**Exchange Online 方案 2** <br/> |**Exchange Online Kiosk** <br/> |
|Exchange ActiveSync 裝置限制  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |
|Exchange ActiveSync 裝置刪除限制  <br/> |20 個  <br/> |20 個  <br/> |20 個  <br/> |20 個  <br/> |
|Exchange ActiveSync 檔案附件限制  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
