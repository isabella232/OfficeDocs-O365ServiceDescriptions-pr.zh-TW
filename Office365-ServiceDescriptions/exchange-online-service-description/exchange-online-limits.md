---
title: Exchange Online 限制
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
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
ms.openlocfilehash: 243e43803c7b9932491da75e64173433fb831309
ms.sourcegitcommit: 83c602d9c498df5a2fe0095c6fb0a267c8a708b7
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/17/2020
ms.locfileid: "42687929"
---
# <a name="exchange-online-limits"></a>Exchange Online 限制

尋找不同服務區域的 Exchange Online 限制，包括通訊錄限制、信箱儲存限制以及報告與郵件追蹤限制，以上所列僅是其中幾例。

> [!NOTE]
> 如果您需要某項工作的協助，或是要針對某個問題進行疑難排解，您可能會發現下列文章很實用：  <br/> *  [電子郵件](https://support.office.com/article/94275804-7147-4332-9ccd-5d421760a9ed)（協助建立及傳送電子郵件）  <br/> *  [商務用 Office 365 中的電子郵件-系統管理說明](https://go.microsoft.com/fwlink/?linkid=529722) <br/>   *  [使用適用于 Office 365 的 Microsoft 支援和修復小幫手來修正 Outlook 和 Office 365 問題](https://diagnostics.office.com/) <br/>  *  [Office 365 中的電子郵件未傳遞回報](https://go.microsoft.com/fwlink/?linkid=526653) <br/> *  [Exchange Online 說明](https://go.microsoft.com/fwlink/?linkid=825607)

Microsoft Exchange Online 中的限制屬於下列其中一個類別：

- [Address book limits](#address-book-limits)

- [Mailbox storage limits](#mailbox-storage-limits)

- [Capacity alerts](#capacity-alerts)

- [Mailbox folder limits](#mailbox-folder-limits)

- [Message limits](#message-limits)

- [接收及傳送限制](#receiving-and-sending-limits)

- [報告和郵件追蹤限制](#reporting-and-message-trace-limits)

- [Retention limits](#retention-limits)

- [Distribution group limits](#distribution-group-limits)

- [日誌、傳輸和收件匣規則限制](#journal-transport-and-inbox-rule-limits)

- [Moderation limits](#moderation-limits)

- [Exchange ActiveSync 限制](#exchange-activesync-limits)

> [!IMPORTANT]
> *  適用於 Microsoft Office 365 組織的限制可能會因為組織在服務中註冊的時間長短而有所不同。 <br/> * 在 Microsoft 資料中心內變更限制時，可能需要一些時間才能將變更套用至所有現有的客戶。 <br/> * 您無法修改大部分的這些限制，不過您和您的使用者都應該知道這些限制。 <br/> * 這些限制同時適用于內部和外部收件者。 <br/> * 依預設，Exchange Online Protection （EOP）會保護 Exchange Online 信箱。 如需適用于 Exchange Online 中的 EOP 功能的限制，請參閱[Exchange Online Protection 限制](../exchange-online-protection-service-description/exchange-online-protection-limits.md)。 <br/> * 如需 Office 365 群組限制的相關資訊，請參閱「如何管理我的群組？」。 [深入瞭解 Office 365 群組](https://go.microsoft.com/fwlink/?linkid=846714)中的「如何管理我的群組？」。

## <a name="address-book-limits"></a>通訊錄限制

- **通訊清單限制**：可以在 exchange Online 或 exchange Server 2013 組織中建立的通訊清單數目上限。 這個數目包括 Exchange Online 中的預設通訊清單，例如 [所有連絡人] 和 [所有群組]。

    > [!NOTE]
    > 最多可將 20 筆通訊清單指派給單一離線通訊錄 (OAB)。

- **離線通訊錄限制**：可以在 exchange Online 或 exchange Server 2013 組織中建立的離線通訊錄（OAB）數目上限。

- **通訊錄原則限制**：在 Exchange Online 或 exchange Server 2013 組織中建立的通訊錄原則（ABP）數目上限。

- **全域通訊清單**：在 Exchange Online 或 exchange Server 2013 組織中建立的全域通訊清單（GAL）數目上限。

### <a name="address-book-limits-across-office-365-options"></a>不同 Office 365 選項的通訊錄限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能**|**Office 365 商務基本版**|**Office 365 商務進階版**|**Office 365 企業版 E1**|**Office 365 企業版 E3**|**Office 365 企業版 E5**|**Office 365 企業版 F3**|
|通訊清單限制|1000|1000|1000|1000|1000|1000|
|離線通訊錄 (OAB) 限制|250|250|250|250|250|250|
|通訊錄原則 (ABP) 限制|250|250|250|250|250|250|
|全域通訊清單限制|250|250|250|250|250|250|

### <a name="address-book-limits-across-standalone-plans"></a>不同獨立方案的通訊錄限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能**|**Exchange Server 2013**|**Exchange Online 方案 1**|**Exchange Online 方案 2**|**Exchange Online Kiosk**|
|通訊清單限制|1000|1000|1000|1000|
|離線通訊錄 (OAB) 限制|250|250|250|250|
|通訊錄原則 (ABP) 限制|250|250|250|250|
|全域通訊清單限制|250|250|250|250|

## <a name="mailbox-storage-limits"></a>信箱儲存限制

可用的信箱儲存容量取決於信箱類型和使用者的訂閱授權。管理員可降低單一使用者或全域的最高信箱大小。

> [!NOTE]
> 不允許使用日誌記錄、傳輸規則或自動轉寄規則將郵件複製到 Exchange Online 信箱以進行封存。 使用者的封存信箱僅供該使用者使用。 Microsoft 保留在使用者的封存信箱用來儲存其他使用者的封存資料或其他不適當用途的情況下，拒絕無限封存的權利。

### <a name="storage-limits-across-office-365-options"></a>不同 Office 365 選項的儲存限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能**|**Office 365 商務基本版**|**Office 365 商務進階版**|**Office 365 企業版 E1**|**Office 365 企業版 E3**|**Office 365 企業版 E5**|**Office 365 企業版 F3**|
|使用者信箱|50 GB|50 GB|50 GB|100 GB|100 GB|2 GB|
|封存信箱<sup>7、8</sup>|50 GB|50 GB|50 GB|無限制<sup>1</sup>|Unlimited<sup>1</sup>|無法使用<sup>4</sup>|
|共用信箱<sup>10</sup>|50 GB<sup>2</sup>|50 GB<sup>2</sup>|50 GB<sup>2</sup>|50 GB<sup>2、9</sup>|50 GB<sup>2、9</sup>|50 GB<sup>2</sup>|
|資源信箱|50 GB<sup>3</sup>|50 GB<sup>3</sup>|50 GB<sup>3</sup>|50 GB<sup>3、9</sup>|50 GB<sup>3、9</sup>|50 GB<sup>3</sup>|
|站台信箱<sup>5</sup>|50 GB|50 GB|50 GB|50 GB|50 GB|無法使用|
|公用資料夾信箱|50 GB<sup>6</sup>|50 GB<sup>6</sup>|50 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|無|
|群組信箱|50 GB|50 GB|50 GB|50 GB|50 GB|50 GB|

> [!NOTE]
> <sup>1</sup> 每位使用者初始會獲得 100 GB 的封存信箱儲存空間。 開啟自動展開封存時，當儲存容量達到 100 GB 時，會自動加入額外的儲存空間。 如需詳細資訊，請參閱 [在 Office 365 中的無限制封存的概觀](https://go.microsoft.com/fwlink/?linkid=844060)。 <br/> <sup>2</sup>若要存取共用信箱，使用者必須擁有 Exchange Online 授權，但共用信箱不需要個別的授權。 沒有授權，共用信箱限制為 50 GB。 若要將大小限制增加為 100 GB，必須為共用信箱指派 exchange Online Plan 2 授權或 Exchange online Plan 1 授權與 Exchange Online 封存附加元件授權。 這也可讓您針對無限量的封存儲存容量啟用自動擴充封存。 同樣地，如果您想要將共用信箱設為訴訟暫止狀態，共用信箱必須有 exchange Online Plan 2 授權或 Exchange Online Plan 1 授權與 Exchange Online 封存附加元件授權。 如果您想要套用高級功能（例如 Office 365 高級威脅防護、高級電子檔探索）或自動保留原則，共用信箱必須獲得這些功能的授權。 <br/> <sup>3</sup> 資源信箱不需要授權。 不過，如果沒有授權，資源信箱會限制為 50 GB。 若要增加信箱大小，必須指派 E3 或 E5 授權。 這樣會將信箱增加至 100 GB。 <br/> <sup>4</sup> Exchange Online Kiosk 中未包含封存信箱。 但可以透過 Exchange Online 封存以附加元件形式購買。 如需詳細資訊，請參閱[Exchange Online 封存服務說明](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md)。 <br/> <sup>5</sup>網站信箱已從 Exchange Online 移除，在2017中 SharePoint 線上。 <br/> <sup>6</sup> 您最多可以有 1,000 個公用資料夾信箱，而且所有公用資料夾信箱的大小總和上限為 50 TB。 階層服務信箱的限制為 100 個公用資料夾信箱。 <br/> <sup>7</sup> 封存信箱僅可用來封存已套用授權之單一使用者或實體 (例如共用信箱) 的郵件。 禁止使用封存信箱來儲存多個使用者或實體的郵件。 例如，IT 系統管理員不能建立共用信箱，再由使用者純粹為了封存的目的來複製它 (透過 [副本] 或 [密件副本] 欄位，或透過傳輸規則)。 請注意，多人使用的共用信箱不會實際儲存個別使用者的電子郵件。 多個使用者可以存取，且傳送電子郵件做為共用信箱。 因此，只有傳送至共用信箱或從共用信箱寄出的電子郵件會儲存在共用信箱中，*做為*共用信箱。 <br/> <sup>8</sup>如果您已在 Exchange Online 中建立保留原則，則只有當使用者的主要信箱大於 10 MB 時，系統才會自動將郵件移到使用者的封存信箱。 若信箱小於 10 MB，則保留原則不會不該信箱自動執行。 <br/> <sup>9</sup> 共用信箱和資源信箱不需要授權。 不過，若沒有授權，這些信箱的限制為 50 GB。 若要增加信箱大小，必須指派 E3 或 E5 授權。 這樣會將信箱增加至 100 GB。 <br/> <sup>10</sup>依預設，共用信箱具有系統產生（未知）密碼的相關聯作用中使用者帳戶。 若要封鎖關聯共用信箱帳戶的登入，請參閱[共用信箱帳戶的封鎖登入](https://docs.microsoft.com/office365/admin/email/create-a-shared-mailbox#block-sign-in-for-the-shared-mailbox-account)。

### <a name="storage-limits-across-standalone-plans"></a>不同獨立方案的儲存限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能**|**Exchange Server 2013**|**Exchange Online 方案 1**|**Exchange Online 方案 2**|**Exchange Online Kiosk**|
|使用者信箱|2 GB<sup>1</sup>|50 GB|100 GB|2 GB|
|封存信箱<sup>8, 9</sup>|100 GB<sup>1</sup>|50 GB|無限制<sup>2</sup>|無法使用<sup>5</sup>|
|共用信箱<sup>11</sup>|2 GB<sup>1</sup>|50 GB<sup>3</sup>|50 GB<sup>3、10</sup>|50 GB<sup>3</sup>|
|資源信箱|2 GB<sup>1</sup>|50 GB<sup>4</sup>|50 GB<sup>4、10</sup>|50 GB<sup>4</sup>|
|公用資料夾信箱|2 GB<sup>6</sup>|50 GB<sup>7</sup>|100 GB<sup>7</sup>|無|
|群組信箱|50 GB|50 GB|50 GB|50 GB|

> [!NOTE]
> <sup>1</sup> 這是 Exchange Server 2013 組織的預設信箱大小。 系統管理員可以為其組織變更此值。 內部部署信箱並無儲存空間上限。 <br/> <sup>2</sup> 每位使用者初始會獲得 100 GB 的封存信箱儲存空間。 開啟自動展開封存時，當儲存容量達到 100 GB 時，會自動加入額外的儲存空間。 如需詳細資訊，請參閱 [在 Office 365 中的無限制封存的概觀](https://go.microsoft.com/fwlink/?linkid=844060)。 如需自動展開封存的可用性詳細資訊，請參閱 [Office 365 藍圖](https://go.microsoft.com/fwlink/?LinkId=509914)。 <br/> <sup>3</sup>若要存取共用信箱，使用者必須擁有 Exchange Online 授權，但共用信箱不需要個別的授權。 沒有授權，共用信箱限制為 50 GB。 若要將大小限制增加為 100 GB，必須為共用信箱指派 exchange Online Plan 2 授權或 Exchange online Plan 1 授權與 Exchange Online 封存附加元件授權。 這也可讓您針對無限量的封存儲存容量啟用自動擴充封存。 同樣地，如果您想要將共用信箱設為訴訟暫止狀態，共用信箱必須有 exchange Online Plan 2 授權或 Exchange Online Plan 1 授權與 Exchange Online 封存附加元件授權。 如果您想要套用高級功能（例如 Office 365 高級威脅防護、高級電子檔探索）或自動保留原則，共用信箱必須獲得這些功能的授權。 <br/> <sup>4</sup> 資源信箱不需要授權。 不過，如果沒有授權，資源信箱會限制為 50 GB。 若要增加信箱大小，必須指派 Exchange Online 方案 2 授權。 這樣會將信箱增加至 100 GB。 <br/> <sup>5</sup> Exchange Online Kiosk 中未包含封存信箱。 但可以透過 Exchange Online 封存以附加元件形式購買。 如需詳細資訊，請參閱[Exchange Online 封存服務說明](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md)。 <br/> <sup>6</sup> 這是 Microsoft Exchange Server 2013 組織的預設信箱大小。 系統管理員可以為其組織變更此值。 在 Exchange Server 2013您最多可以有 100 個公用資料夾信箱，而且所有公用資料夾信箱的大小總和上限為 50 TB。 <br/> <sup>7</sup> 在 Exchange Online 中，您最多可以有 1,000 個公用資料夾信箱，而且所有公用資料夾信箱的大小總和上限為 50 TB。  <br/> <sup>8</sup> 封存信箱僅可用來封存已套用授權之單一使用者或實體的郵件。 禁止使用封存信箱來儲存多個使用者或實體的郵件。 例如，IT 系統管理員不能建立共用信箱，再由使用者純粹為了封存的目的來複製 (透過 [副本] 或 [密件副本] 欄位，或透過傳輸規則) 共用信箱。 <br/> <sup>9</sup> 如果您已在 Exchange Online 中建立保留原則，則只有當使用者的主要信箱大於 10 MB 時，系統才會自動將郵件移到使用者的封存信箱。 若信箱小於 10 MB，則保留原則不會不該信箱自動執行。 <br/> <sup>10</sup>共用和資源信箱不需要授權。 不過，若沒有授權，這些信箱的限制為 50 GB。 若要增加信箱大小，必須指派 Exchange Online 方案 2 授權。 這樣會將信箱增加至 100 GB。 <br/> <sup>11</sup>依預設，共用信箱具有系統產生（未知）密碼的相關聯作用中使用者帳戶。 若要封鎖關聯共用信箱帳戶的登入，請參閱[共用信箱帳戶的封鎖登入](https://docs.microsoft.com/office365/admin/email/create-a-shared-mailbox#block-sign-in-for-the-shared-mailbox-account)。

## <a name="capacity-alerts"></a>容量警示

Exchange Online 在使用者信箱接近容量上限或已達上限時提供三種通知類型：

- **警告**：使用者收到信箱接近大小上限的電子郵件警告。 此警告的目的是讓使用者刪除不需要的郵件。

- **禁止傳送**：當達到信箱大小限制時，使用者會收到禁止傳送通知電子郵件。 在刪除足夠的電子郵件後，使用者才無法傳送新郵件，使信箱達到大小限制。

- **禁止傳送/接收**：當達到信箱大小限制時，Exchange Online 會拒絕任何傳入郵件，並將未傳遞回報（NDR）傳送給寄件者。 寄件者可選擇稍後嘗試重新傳送該郵件。 若再次收到訊息，使用者必須刪除電子郵件，直到信箱低於大小限制為止。

### <a name="capacity-alerts-across-office-365-options"></a>不同 Office 365 選項的容量警示

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能**|**Office 365 商務基本版**|**Office 365 商務進階版**|**Office 365 企業版 E1**|**Office 365 企業版 E3**|**Office 365 企業版 E5**|**Office 365 企業版 F3**|
|警告|49 GB|49 GB|49 GB|98 GB|98 GB|1.96 GB|
|禁止傳送|49.5 GB|49.5 GB|49.5 GB|99 GB|99 GB|1.98 GB|
|禁止傳送/接收|50 GB|50 GB|50 GB|100 GB|100 GB|2 GB|

### <a name="capacity-alerts-across-standalone-plans"></a>不同獨立方案的容量警示

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能**|**Exchange Server 2013**|**Exchange Online 方案 1**|**Exchange Online 方案 2**|**Exchange Online Kiosk**|
|警告|1.9 GB<sup>1</sup>|49 GB|98 GB|1.96 GB|
|禁止傳送|2 GB<sup>1</sup>|49.5 GB|99 GB|1.98 GB|
|禁止傳送/接收|2.3 GB<sup>1</sup>|50 GB|100 GB|2 GB|

> [!NOTE]
> <sup>1</sup> 這是 Exchange Server 2013 組織的預設值。系統管理員可以為其組織變更此值。

## <a name="mailbox-folder-limits"></a>信箱資料夾限制

這些限制是為了讓信箱容量不超過 Exchange Online 可支援的已知大小範圍。這些限制的目的在於防止每一資料夾有無限多個信箱項目、每一信箱有無限多個資料夾，或每一 Exchange Online 組織有無限多個公用資料夾。為了實用目的，信箱資料夾限制實際上不受限，且足以支援大多數的 Exchange Online 信箱和已移轉至 Exchange Online 的內部部署信箱。

- **每個信箱資料夾的郵件數目上限**：指定信箱資料夾的郵件數目上限。 達到此限制時，新郵件便無法傳遞或儲存至資料夾。

- **每個信箱資料夾的郵件數目警告**：指定在 Exchange Online 傳送警告訊息給信箱擁有者前，信箱資料夾可以保留的郵件數目。 達到此配額時，一天會傳送一次警告訊息。

- **[可復原的專案] 資料夾中每個資料夾的郵件數目上限**：指定 [可復原的專案] 資料夾中每個資料夾可包含的郵件數目上限。 資料夾超過此限制時，就無法儲存新郵件。 例如，如果 [可復原的項目] 資料夾中的 [刪除] 資料夾已超過郵件計數限制，而且信箱擁有者嘗試從其信箱中永久刪除項目，則刪除會失敗。

- **[可復原的專案] 資料夾中每個資料夾的郵件數目警告**：指定 [可復原的專案] 資料夾中每個資料夾可以保留的郵件數目，Exchange Online 會在應用程式事件記錄檔中記錄事件。

- **每個信箱資料夾的子資料夾數目上限**：指定可在信箱資料夾中建立的子資料夾數目上限。 達到此限制時，信箱擁有者就無法建立新的子資料夾。

- **每個信箱資料夾的子資料夾數目警告**：指定在 Exchange Online 將警告郵件傳送給信箱擁有者前，可在信箱資料夾中建立的子資料夾數目。 達到此配額時，一天會傳送一次警告訊息。

- **資料夾階層深度上限**：指定信箱之資料夾階層中的層級數目上限。 達到此限制時，信箱擁有者就無法在信箱資料夾的資料夾階層中建立另一個層級。

- **針對資料夾階層深度的警告**：指定在 Exchange Online 傳送警告訊息給信箱擁有者前，可建立之信箱資料夾的資料夾階層中的層級數目。 達到此配額時，一天會傳送一次警告訊息。

- **公用資料夾的數目上限**：指定完整公用資料夾階層中的公用資料夾數目上限。 達到此限制時，必須先刪除現有公用資料夾，才能建立新的公用資料夾。

- **每個公用資料夾的子資料夾數目上限**：指定可在公用資料夾中建立的子資料夾數目上限。 達到此限制時，即無法在公用資料夾中建立新的子資料夾。

- **每個公用資料夾的子資料夾數目的警告**：指定在 Exchange Online 向資料夾擁有者傳送警告郵件之前，可在公用資料夾中建立的子資料夾數目。 如果沒有擁有者存在，則會傳送警告訊息給具有擁有者權限的使用者。 達到此配額時，一天會傳送一次警告訊息。

### <a name="mailbox-folder-limits-across-office-365-options"></a>不同 Office 365 選項的信箱資料夾限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能**|**Office 365 商務基本版**|**Office 365 商務進階版**|**Office 365 企業版 E1**|**Office 365 企業版 E3**|**Office 365 企業版 E5**|**Office 365 企業版 F3**|
|每一信箱資料夾的郵件數目上限|1 百萬|1 百萬|1 百萬|1 百萬|1 百萬|1 百萬|
|每一信箱資料夾的郵件數目警告|900,000|900,000|900,000|900,000|900,000|900,000|
|[可復原的項目] 資料夾中每一資料夾的郵件數目上限|3 百萬|3 百萬|3 百萬|3 百萬|3 百萬|3 百萬|
|主信箱中 [可復原的項目] 資料夾的儲存配額 (未保留)|30 GB|30 GB|30 GB|30 GB|30 GB|30 GB|
|主信箱中 [可復原的項目] 資料夾的儲存配額 (保留)|100 GB|100 GB|100 GB|100 GB|100 GB|100 GB|
|封存信箱中 [可復原的項目] 資料夾的儲存配額 (未保留)|30 GB|30 GB|30 GB|Unlimited<sup>2</sup>|Unlimited<sup>2</sup>|30 GB|
|封存信箱中 [可復原的項目] 資料夾的儲存配額 (保留)|100 GB<sup>1</sup>|100 GB<sup>1</sup>|100 GB<sup>1</sup>|Unlimited<sup>2</sup>|Unlimited<sup>2</sup>|100 GB<sup>1</sup>|
|[可復原的項目] 資料夾中每一資料夾的郵件數目警告|275 萬|275 萬|275 萬|275 萬|275 萬|275 萬|
|每一信箱資料夾的子資料夾數目上限|10,000|10,000|10,000|10,000|10,000|10,000|
|每一信箱資料夾的子資料夾數目警告|9000|9000|9000|9000|9000|9000|
|資料夾階層深度上限|300|300|300|300|300|300|
|資料夾階層深度警告|250|250|250|250|250|250|
|最大公用資料夾數目|500,000|500,000|500,000|500,000|500,000|無|
|每一公用資料夾的子資料夾數目上限|10,000|10,000|10,000|10,000|10,000|無|
|每一公用資料夾的子資料夾數目警告|9000|9000|9000|9000|9000|無法使用|

> [!NOTE]
> <sup>1</sup> 這是 [可復原的項目] 資料夾的儲存配額，而非整個封存信箱的配額。 對於使用 Exchange Online 方案 2 授權的使用者或同時擁有 Exchange Online 方案 1 和 Exchange Online 封存授權的使用者，封存信箱的儲存配額是無限制的。 如需增加可復原的項目配額的詳細資訊，請參閱[為保留中信箱增加可復原的項目配額](https://docs.microsoft.com/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold)。 <br/> <sup>2</sup> 封存信箱中 [可復原的項目] 資料夾的初始儲存配額是 100 GB。 開啟自動展開封存時，當 [可復原項目] 資料夾達到儲存容量時，會自動加入額外的儲存空間。 如需詳細資訊，請參閱 [在 Office 365 中的無限制封存的概觀](https://go.microsoft.com/fwlink/?linkid=844060)。 如需自動展開封存的可用性詳細資訊，請參閱 [Office 365 藍圖](https://go.microsoft.com/fwlink/?LinkId=509914)。

### <a name="mailbox-folder-limits-across-standalone-plans"></a>不同獨立方案的信箱資料夾限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能**|**Exchange Server 2013**|**Exchange Online 方案 1**|**Exchange Online 方案 2**|**Exchange Online Kiosk**|
|每一信箱資料夾的郵件數目上限|沒有限制<sup>1</sup>|1 百萬|1 百萬|1 百萬|
|每一信箱資料夾的郵件數目警告|無限制|900,000|900,000|900,000|
|[可復原的項目] 資料夾中每一資料夾的郵件數目上限|無限制|3 百萬|3 百萬|3 百萬|
|主信箱中 [可復原的項目] 資料夾的儲存配額 (未保留)|30 GB|30 GB|30 GB|30 GB|
|主信箱中 [可復原的項目] 資料夾的儲存配額 (保留)|100 GB|100 GB|100 GB|100 GB|
|封存信箱中 [可復原的項目] 資料夾的儲存配額 (未保留)|30 GB|30 GB|30 GB|30 GB|
|封存信箱中 [可復原的項目] 資料夾的儲存配額 (保留)|100 GB<sup>2</sup>|100 GB<sup>2</sup>|Unlimited<sup>3</sup>|Unlimited<sup>3</sup>|
|[可復原的項目] 資料夾中每一資料夾的郵件數目警告|無限制|275 萬|275 萬|275 萬|
|每一信箱資料夾的子資料夾數目上限|無限制|1000|1000|1000|
|每一信箱資料夾的子資料夾數目警告|無限制|900|900|900|
|資料夾階層深度上限|無限制|300|300|300|
|資料夾階層深度警告|無限制|250|250|250|
|最大公用資料夾數目|1,000,000|100,000|100,000|無法使用|
|每一公用資料夾的子資料夾數目上限|不適用|1,000|1,000|無|
|每一公用資料夾的子資料夾數目警告|不適用|900|900|無|

> [!NOTE]
> <sup>1</sup> Microsoft 建議每個信箱資料夾的郵件數不要超過 1,000,000 封。 > <br/> <sup>2</sup> 這是 [可復原的項目] 資料夾的儲存配額，而非整個封存信箱的配額。 對於使用 Exchange Online 方案 2 授權的使用者或同時擁有 Exchange Online 方案 1 和 Exchange Online 封存授權的使用者，封存信箱的儲存配額是無限制的。 如需增加可復原的項目配額的詳細資訊，請參閱[為保留中信箱增加可復原的項目配額](https://docs.microsoft.com/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold)。 <br/> <sup>3</sup> 封存信箱中 [可復原的項目] 資料夾的初始儲存配額是 100 GB。 開啟自動展開封存時，當 [可復原項目] 資料夾達到儲存容量時，會自動加入額外的儲存空間。 如需詳細資訊，請參閱 [在 Office 365 中的無限制封存的概觀](https://go.microsoft.com/fwlink/?linkid=844060)。 如需自動展開封存的可用性詳細資訊，請參閱 [Office 365 藍圖](https://go.microsoft.com/fwlink/?LinkId=509914)。

## <a name="message-limits"></a>郵件限制

下列限制會套用至每封電子郵件。

- **郵件大小限制**：您必須要有郵件大小限制，以防止大郵件封鎖其他郵件的傳遞，並影響所有使用者的服務效能。 這些限制包含附件，且適用於整個組織內的所有郵件 (內送、外寄和內部)。 大於此上限的郵件將不會傳遞，而寄件者將收到未傳遞回報 (NDR)。 雖然郵件大小上限無法上調、下調或依各使用者為基準設定，管理員仍可建立傳輸規則來限制任何個別附件的最高大小上限。 若要深入了解，請參閱 [Office 365 現在可支援較大的電子郵件訊息](https://www.microsoft.com/en-us/microsoft-365/blog/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/)。

    > [!NOTE]
    > 部分電子郵件用戶端可擁有較低的郵件大小或可限制個別檔案附件的大小為小於 Exchange Online 郵件大小上限的值。

- **郵件頭大小限制**：指定郵件中所有郵件頭欄位的大小上限。 目前的限制為 256 KB。 如果所有郵件標頭的大小總計超過 256 KB，Exchange Online 就會拒絕該郵件，出現錯誤「552 5.3.4 標頭大小超過固定大小上限」。 郵件內文或附件的大小不考慮在內。 因為標頭欄位是純文字，所以標頭大小是由每個標頭欄位中的字元數以及標頭欄位的總數來決定。 每個文字字元都佔用 1 個位元組。

- **主體長度限制**：電子郵件主旨行中允許的文字字元數目上限。

- 檔案**附件限制**：電子郵件中允許的檔案附件數目上限。 即使所有檔案附件的大小總計沒有違反郵件大小限制，郵件中允許的附件數目仍然具有限制。 此限制會由 Multipart 郵件限制控制。

- 檔案**附件大小限制**：單一附件的檔案大小上限。

    > [!NOTE]
    > 這是單一附件的檔案大小上限。 個別用戶端方案 (包括網頁版 Outlook) 可能會規定附件大小需低於此上限。 Exchange ActiveSync 未針對個別附件實作附件大小限制。 Exchange ActiveSync 郵件的所有附件大小總和必須小於郵件大小限制。

- **多部分郵件限制**： MIME 多部分郵件中允許的郵件內文部分數目上限。 此限制也會控制郵件允許的檔案附件數目上限。

- **內嵌郵件深度限制**：電子郵件中允許的轉寄電子郵件數目上限。

### <a name="message-limits-across-office-365-options"></a>不同 Office 365 選項的郵件限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能**|**Office 365 商務基本版**|**Office 365 商務進階版**|**Office 365 企業版 E1**|**Office 365 企業版 E3**|**Office 365 企業版 E5**|**Office 365 企業版 F3**|
|郵件大小限制 - Outlook|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1、2</sup>|
|郵件大小限制 - OWA|112 MB<sup>1、3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|
|郵件大小限制 - Outlook for Mac|150 MB<sup>1、2</sup>|150 MB<sup>1、2</sup>|150 MB<sup>1、2</sup>|150 MB<sup>1、2</sup>|150 MB<sup>1、2</sup>|150 MB<sup>1, 2</sup>|
|郵件大小限制 - 移轉|150 MB <sup>1、4</sup>|150 MB <sup>1、4</sup>|150 MB <sup>1、4</sup>|150 MB <sup>1、4</sup>|150 MB <sup>1、4</sup>|150 MB <sup>1、4</sup>|
|郵件大小限制-Outlook for iOS 和 Android | 33 MB| 33 MB| 33 MB| 33 MB| 33 MB| 33 MB|
|加密郵件的大小限制 (適用於使用 Office 365 郵件加密與新功能的訂閱者)<sup>5</sup>|150 MB |150 MB |150 MB |150 MB |150 MB |150 MB|
|加密郵件的大小限制 (適用於使用舊版 Office 365 郵件加密的訂閱者)<sup>5</sup>|25 MB|25 MB|25 MB|25 MB|25 MB|25 MB|
|主旨長度限制|255 個字元|255 個字元|255 個字元|255 個字元|255 個字元|255 個字元|
|檔案附件限制|250 個附件|250 個附件|250 個附件|250 個附件|250 個附件|250 個附件|
|檔案附件大小限制 - Outlook|150 MB|150 MB |150 MB |150 MB |150 MB |150 MB|
|檔案附件大小限制 - OWA |112 MB<sup>3，6</sup>|112 MB<sup>3，6</sup>|112 MB<sup>3，6</sup>|112 MB<sup>3，6</sup>|112 MB<sup>3，6</sup>|112 MB<sup>3，6</sup>|
|檔案附件大小限制 - Outlook for Mac|150 MB|150 MB |150 MB |150 MB |150 MB |150 MB|
|檔附件大小限制-Outlook for iOS 和 Android|33 MB |33 MB |33 MB |33 MB |33 MB |33 MB |
|Multipart 郵件限制|250 個部分|250 個部分|250 個部分|250 個部分|250 個部分|250 個部分|
|內嵌郵件深度限制|30 封內嵌郵件|30 封內嵌郵件|30 封內嵌郵件|30 封內嵌郵件|30 封內嵌郵件|30 封內嵌郵件|

> [!NOTE]
> <sup>1</sup> Office 365 信箱的預設郵件大小上限為 25 MB。 Office 365 管理員可以指定介於 1 MB 和 150 MB 之間的自訂限制。 不過，您可以傳送或接收的郵件大小也取決於您的電子郵件用戶端或解決方案支援的項目。 如需自訂您的組織允許的最大郵件大小的詳細資訊，請參閱 [Office 365 現在支援較大的電子郵件訊息](https://www.microsoft.com/en-us/microsoft-365/blog/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/)。 
<br/> <sup>2</sup> 您可以在 Office 365 使用者之間 (郵件永遠不會離開 Office 365 資料中心) 傳送和接收最多 150 MB 的郵件。 Office 365 資料中心外路由傳送的郵件都會受限於額外 33% 轉譯編碼增加，如此一來，郵件大小上限是 112 MB。 <br/> 
<sup>3</sup> OWA 會計算您的訊息可能受限於編碼增加 33% 的可能性，並且會將您可以傳送的郵件大小限制為小於已配置的設定 25%。 例如，如果您自訂的設定是 100 MB 的郵件大小上限，您可以傳送的郵件不超過 75 MB。 
<br/> <sup>4</sup> Exchange Online 會計算要移動至 Exchange Online 的郵件大小。 Exchange Server 2013 之前的 Exchange 版本可能會報告較小的項目大小。 此限制適用于使用任何支援的 Exchange 信箱複寫服務的移動型遷移。 其他遷移方法 (轉換、分段、IMAP、PST) 和其他第三方工具都受限於一般訊息大小限制。 <br/> 
<sup>5</sup> 如需 OME 與新功能的相關資訊，請參閱 [設定以 Azure 資訊保護為基礎所建置的全新 Office 365 郵件加密功能](https://support.office.com/article/7ff0c040-b25c-4378-9904-b1b50210d00e)。<br/> 
<sup>6</sup>傳統檔案附件的限制為 112 MB，但 OneDrive 檔案附件最多可達 2 GB。


### <a name="message-limits-across-standalone-options"></a>不同獨立選項的郵件限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能**|**Exchange Server 2013**|**Exchange Online 方案 1**|**Exchange Online 方案 2**|**Exchange Online Kiosk**|
|郵件大小限制 - Outlook|10 MB<sup>4</sup>|150 MB<sup>1、2</sup>|150 MB<sup>1、2</sup>|150 MB<sup>2</sup>|
|郵件大小限制 - OWA|10 MB<sup>4</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|150 MB<sup>1, 2</sup>|
|郵件大小限制 - Outlook for Mac|10 MB<sup>4</sup>|150 MB |150 MB||
|郵件大小限制 - 移轉|不適用|150 MB <sup>5</sup>|150 MB <sup>5</sup>|150 MB <sup>5</sup>|
|郵件大小限制-Outlook for iOS 和 Android |25 MB |33 MB |33 MB |33 MB |
|加密郵件的大小限制 (適用於使用 Office 365 郵件加密與新功能的訂閱者)<sup>6</sup>|150 MB|150 MB |150 MB |150 MB|
|加密郵件的大小限制 (適用於使用舊版 Office 365 郵件加密的訂閱者)<sup>6</sup>|25 MB|25 MB|25 MB|25 MB|
|主旨長度限制|255 個字元|255 個字元|255 個字元|255 個字元|
|檔案附件限制|1024 attachments<sup>4</sup>|250 個附件|250 個附件|250 個附件|
|檔案附件大小限制 - Outlook|35 MB<sup>4</sup>|150 MB|150 MB |150 MB|
|檔案附件大小限制 - OWA|35 MB<sup>4</sup>|112 MB<sup>3</sup>|112 MB<sup>3</sup>|112 MB<sup>3</sup>|
|檔案附件大小限制 - Outlook for Mac|35 MB<sup>4</sup>|150 MB|150 MB|35 MB|
|檔附件大小限制-Outlook for iOS 和 Android|25 MB |33 MB|33 MB|33 MB|
|Multipart 郵件限制|250 個部分|250 個部分|250 個部分|250 個部分|
|內嵌郵件深度限制|30 封內嵌郵件|30 封內嵌郵件|30 封內嵌郵件|30 封內嵌郵件|

> [!NOTE]
> <sup>1</sup> Office 365 系統管理員可以指定 1 MB 到 150 MB 之間的自訂限制。 不過，您可以傳送或接收的郵件大小也取決於您的電子郵件用戶端或解決方案支援的項目。 如需自訂您的組織允許的最大郵件大小的詳細資訊，請參閱 [Office 365 現在支援較大的電子郵件訊息](https://www.microsoft.com/en-us/microsoft-365/blog/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/)。 <br/> <sup>2</sup> 您可以在 Office 365 使用者之間 (郵件永遠不會離開 Office 365 資料中心) 傳送和接收最多 150 MB 的郵件。 Office 365 資料中心外路由傳送的郵件都會受限於額外 33% 轉譯編碼增加，如此一來，郵件大小上限是 112 MB。 <br/> 
<sup>3</sup> OWA 會計算您的訊息可能受限於編碼增加 33% 的可能性，並且會將您可以傳送的郵件大小限制為小於已配置的設定 25%。 例如，如果您自訂的設定是 100 MB 的郵件大小上限，您可以傳送的郵件不超過 75 MB。 <br/> 
<sup>4</sup> 這是 Exchange Server 2013 組織的預設限制。 系統管理員可以為其組織變更此值。 <br/> 
<sup>5</sup> Exchange Online 會計算要移動至 Exchange Online 的郵件大小。 Exchange Server 2013 之前的 Exchange 版本可能會報告較小的項目大小。 <br/> 
<sup>6</sup> 如需 OME 與新功能的相關資訊，請參閱 [設定以 Azure 資訊保護為基礎所建置的全新 Office 365 郵件加密功能](https://support.office.com/article/7ff0c040-b25c-4378-9904-b1b50210d00e)。

## <a name="receiving-and-sending-limits"></a>接收及傳送限制

接收及傳送限制會套用至郵件、寄件者或收件者，以便抵禦垃圾郵件和大量郵寄蠕蟲或病毒。這些限制有助於保護系統的健康情況，並確保使用者安全。

### <a name="receiving-limits"></a>接收限制

接受限制會套用至使用者、群組或公用資料夾每小時能接收的訊息數量。 這適用于從網際網路和內部部署伺服器接收的郵件。 當超過接收限制時，任何傳送到該信箱的電子郵件將會收到未傳遞報告，指出信箱已超過最大傳遞臨界值。 一個小時之後，將會重新整理限制，而信箱就能夠再度接收郵件。

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能**|**Office 365 商務基本版**|**Office 365 商務進階版 Office**|**Office 365 企業版 E1**|**Office 365 企業版 E3**|**Office 365 企業版 E5**|**Office 365 企業版 F3**|
|已接收的訊息|每小時 3,600 封訊息|每小時 3,600 封訊息|每小時 3,600 封訊息|每小時 3,600 封訊息|每小時 3,600 封訊息|每小時 3600 封訊息|

### <a name="sending-limits"></a>傳送限制

傳送限制會套用至使用者可以從 Exchange Online 帳戶傳送的收件者數量、訊息數量和每封訊息的收件者數量。

> [!NOTE]
> 就儲存於組織通訊錄中的通訊群組而言，系統會將群組視為一位收件者。就儲存於信箱之 [連絡人] 資料夾中的通訊群組而言，則系統將群組中的成員視為個別收件者。

- **收件者速率限制**：若要避免傳遞未經許可的大宗郵件，Exchange Online 具有限制使用者和應用程式傳送大量電子郵件的收件者限制。 這些限制會套用至每位使用者的所有外寄和內部郵件。

    > [!NOTE]
    > Exchange Online 客戶若需要傳送合法的大量商業電子郵件（例如客戶電子報），應使用專門提供這些服務的第三方供應商。

- **收件者限制**：這是單一電子郵件訊息的 [收件者：]、[副本：] 和 [密件副本] 欄位中所允許的收件者數目上限。

    > [!NOTE]
    > 基於收件者流量限制和收件者限制的用意，組織共用通訊錄中所儲存的通訊群組會算為一位收件者。在個人通訊群組清單中，每位收件者皆分開計算。

- **收件者 proxy 位址限制**：收件者 proxy 位址限制是收件者信箱可以擁有的別名數目上限（電子郵件地址）。 

- **郵件速率限制**：郵件速率限制決定使用者可以在指定的一段時間內從 Exchange Online 帳戶傳送多少封郵件。 此限制可協助單一寄件者避免過度消耗系統資源。 如果使用者提交郵件的速率超過透過 SMTP 用戶端提交的限制，則會拒絕郵件，用戶端必須重試。

#### <a name="sending-limits-across-office-365-options"></a>不同 Office 365 選項的傳送限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能**|**Office 365 商務基本版**|**Office 365 商務進階版**|**Office 365 企業版 E1**|**Office 365 企業版 E3**|**Office 365 企業版 E5**|**Office 365 企業版 F3**|
|收件者速率限制<sup>1</sup>|每天 10,000 位收件者|每天 10,000 位收件者|每天 10,000 位收件者|每天 10,000 位收件者|每天 10,000 位收件者|每天 10,000 位收件者|
|收件者限制|500 位收件者|1000收件者|1000收件者|1000收件者|1000收件者|1000收件者|
|收件者 proxy 位址限制|400|400|400|400|400|400|
|郵件速率限制|每分鐘 30 封郵件|每分鐘 30 封郵件|每分鐘 30 封郵件|每分鐘 30 封郵件|每分鐘 30 封郵件|每分鐘 30 封郵件|

> [!NOTE]
> <sup>1</sup>達到收件者速率限制後，郵件便無法從信箱傳送，直到過去24小時內傳送郵件的收件者數目降至限制以下。 例如，使用者會將電子郵件訊息傳送給位於 09:00 AM 的5000收件者，然後將另一封郵件傳送給2、1000位收件者的 10:00 AM，然後再將另一封郵件傳送給2500收件者，以達到 11:00 AM 的限制，達到最大的 使用者將無法再傳送郵件，直到下一天的 09:00 AM。

#### <a name="sending-limits-across-standalone-options"></a>不同獨立選項的傳送限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能**|**Exchange Server 2013**|**Exchange Online 方案 1**|**Exchange Online 方案 2**|**Exchange Online Kiosk**|
|收件者流量限制|沒有限制<sup>1</sup>|每日10000個收件者<sup>2</sup>|每日10000個收件者<sup>2</sup>|每日10000個收件者<sup>2</sup>|
|收件者限制|1000收件者<sup>1</sup>|1000收件者|1000收件者|1000收件者|
|收件者 proxy 位址限制|400|400|400|400|
|郵件速率限制|每分鐘 30 封郵件|每分鐘 30 封郵件|每分鐘 30 封郵件|每分鐘 30 封郵件|

> [!NOTE]
> <sup>1</sup> 這是 Exchange Server 2013 組織的預設限制。 系統管理員可以為其組織變更此值。<br/>
<sup>2</sup>達到收件者速率限制後，郵件便無法從信箱傳送，直到在過去24小時內傳送郵件的收件者數目降至限制以下。 例如，使用者會將電子郵件訊息傳送給位於 09:00 AM 的5000收件者，然後將另一封郵件傳送給在 10:00 AM 的2500收件者，然後再將另一封郵件傳送給位於 2500 AM 的11:00 收件者，並達到10000郵件的限制。 使用者將無法再傳送郵件，直到下一天的 09:00 AM。

## <a name="reporting-and-message-trace-limits"></a>報告和郵件追蹤限制

如需報告和郵件追蹤限制，請參閱[Exchange Online Protection 中報告和郵件追蹤](https://go.microsoft.com/fwlink/p/?LinkId=394248)中的「報告和郵件追蹤資料可用性和延遲」一節。

## <a name="retention-limits"></a>保留限制

這些限制會控制可存取 [收件匣] 內特定資料夾中項目的時間長度。

- [**刪除的郵件] 資料夾保留期間**：專案在自動移除之前可保留在 [刪除的郵件] 資料夾中的天數上限。

- **從 [刪除的郵件] 資料夾移除之專案的保留期間**：從 [刪除的郵件] 資料夾移除的專案在被永久刪除之前，可保留的天數上限。

- [**垃圾郵件] 資料夾保留期間**：專案在自動移除之前可保留在 [垃圾郵件] 資料夾中的天數上限。

### <a name="retention-limits-across-office-365-options"></a>不同 Office 365 選項的保留限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能**|**Office 365 商務基本版**|**Office 365 商務進階版**|**Office 365 企業版 E1**|**Office 365 企業版 E3**|**Office 365 企業版 E5**|**Office 365 企業版 F3**|
|[刪除的郵件] 資料夾保留期間|沒有限制<sup>1</sup>|沒有限制<sup>1</sup>|沒有限制<sup>1</sup>|沒有限制<sup>1</sup>|沒有限制<sup>1</sup>|沒有限制<sup>1</sup>|
|從 [刪除的郵件] 資料夾移除之項目的保留期間|14 天<sup>1</sup>|14 天<sup>1</sup>|14 天<sup>1</sup>|14 天<sup>1</sup>|14 天<sup>1</sup>|14 天<sup>1</sup>|
|[垃圾郵件] 資料夾保留期間|30 天|30 天|30 天|30 天|30 天|30 天|

> [!NOTE]
> <sup>1</sup> 這是 Office 365 組織的預設值。 系統管理員可以將組織中信箱的這個值變更為最多 30 天。

### <a name="retention-limits-across-standalone-options"></a>不同獨立選項的保留限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能**|**Exchange Server 2013**|**Exchange Online 方案 1**|**Exchange Online 方案 2**|**Exchange Online Kiosk**|
|[刪除的郵件] 資料夾保留期間|沒有限制<sup>1</sup>|沒有限制<sup>1</sup>|沒有限制<sup>1</sup>|沒有限制<sup>1</sup>|
|從 [刪除的郵件] 資料夾移除之項目的保留期間|14 天<sup>1</sup>|14 天<sup>2</sup>|14 天<sup>2</sup>|14 天<sup>2</sup>|
|[垃圾郵件] 資料夾保留期間|2 年<sup>1</sup>|30 天|30 天|30 天|

> [!NOTE]
> <sup>1</sup> 這是預設限制。系統管理員可以為其組織變更此值。<br/> <sup>2</sup> 這是 Exchange Online 組織的預設值。 系統管理員可以將組織中信箱的這個值變更為最多 30 天。

## <a name="distribution-group-limits"></a>通訊群組限制

這些限制會套用至組織共用通訊錄中的通訊群組。

- **通訊群組成員的數目上限**：收件者總數是在通訊群組擴充之後決定的。

- **將郵件傳送至大型通訊群組的限制**：包含此限制所指定之成員數目的通訊群組必須已設定傳遞管理或郵件核准選項。 傳遞管理會指定一份寄件者清單，只有這些寄件者才能傳送郵件至此通訊群組。 郵件核准會指定一位或多位仲裁者，郵件必須通過他們的核准才能傳送至此通訊群組。

- **大型通訊群組的郵件大小上限**：如果郵件傳送給5000或多個收件者，則郵件大小不能超過此限制。 如果郵件大小超過限制，郵件不會傳遞出去，而且寄件者會收到未傳遞回報 (NDR)。

### <a name="distribution-group-limits-across-office-365-options"></a>不同 Office 365 選項的通訊群組限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能**|**Office 365 商務基本版**|**Office 365 商務進階版**|**Office 365 企業版 E1**|**Office 365 企業版 E3**|**Office 365 企業版 E5**|**Office 365 企業版 F3**|
|通訊群組成員數目上限<sup>1</sup>|100,000 位成員|100,000 位成員|100,000 位成員|100,000 位成員|100,000 位成員|100,000 位成員|
|傳送郵件給大型通訊群組的限制|5,000 位以上成員|5,000 位以上成員|5,000 位以上成員|5,000 位以上成員|5,000 位以上成員|5,000 位以上成員|
|具有 5,000 到 99,999 位成員的通訊群組郵件大小上限|25 MB|25 MB|25 MB|25 MB|25 MB|25 MB|
|具有 100,000 位成員的通訊群組郵件大小上限|5 MB|5 MB|5 MB|5 MB|5 MB|5 MB|
|通訊群組擁有者數目上限|10 |10 |10 |10 |10 |10 |
|使用者可以建立的群組數目上限|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|

> [!NOTE]
> <sup>1</sup> 如果您是使用 Azure Active Directory DirSync，則您可以從內部部署 Active Directory 同步到 Azure Active Directory 的通訊群組成員最大數量為 15,000。 如果您使用的是 Azure AD Connect，則該數量為 50,000。 <br/> <sup>2</sup> 這項限制也適用於系統管理員。

### <a name="distribution-group-limits-across-standalone-options"></a>不同獨立選項的通訊群組限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能**|**Exchange Server 2013**|**Exchange Online 方案 1**|**Exchange Online 方案 2**|**Exchange Online Kiosk**|
|通訊群組成員數目上限|100,000 位成員<sup>1</sup>|100,000 位成員|100,000 位成員|100,000 位成員|
|傳送郵件給大型通訊群組的限制|5,000 位以上成員<sup>1</sup>|5,000 位以上成員|5,000 位以上成員|5,000 位以上成員|
|通訊群組擁有者數目上限|10 |10 |10 |10 |
|使用者可以建立的群組數目上限|250<sup>2</sup>|250<sup>2</sup>|250<sup>2</sup>|250<sup>2</sup>|

> [!NOTE]
> <sup>1</sup> 這是 Exchange Server 2013 組織的預設限制。 系統管理員可以為其組織變更此值。 <br/> <sup>2</sup> 這項限制也適用於系統管理員。

## <a name="journal-transport-and-inbox-rule-limits"></a>日誌、傳輸和收件匣規則限制

下列清單包含套用至日誌規則、傳輸規則（也稱為整個組織規則）的限制，以及適用于收件匣規則的限制。 「收件匣」規則是由個別使用者所設定，並且套用至由個別使用者的信箱所傳送和接收的郵件。

- **規則數目上限** 組織中可以存在的日誌規則數目上限。

- **傳輸規則數目上限** 組織中可以存在的規則數目上限。

- **個別傳輸規則的大小上限** 單一傳輸規則中可以使用的字元數目上限。這些字元是用在條件、例外狀況和動作中。

- **所有傳輸規則中使用之所有規則運算式的字元限制** 在組織中的所有傳輸規則條件及例外狀況中，所有規則運算式所使用的字元總數。您可以有幾條規則使用又長又複雜的規則運算式，也可以有許多規則使用簡單的規則運算式。

- **附件內容的掃描限制** 傳輸規則條件可讓您檢查郵件附件的內容，但只會檢查從附件擷取的第 1 MB 文字。 此 1 MB 限制是指從附件擷取的文字，而不是附件的檔案大小。 例如，2 MB 檔案可能包含小於 1 MB 的文字，所以會檢查所有的文字。

- **所有傳輸規則新增到郵件的收件者人數上限** 當郵件由不同的傳輸規則進行處理時，可新增到郵件中的收件者人數是有限制的。達到此上限之後，就不再將任何其餘的收件者新增到郵件中。此外，傳輸規則也不能將通訊群組新增到郵件中。

- **轉寄者限制** 可為收件匣或傳輸規則設定之具有重新導向動作的收件者人數上限。如果為某個規則設定的郵件重新導向收件者數目超過此數目，系統將不會套用該規則，而任何符合該規則條件的郵件將不會被重新導向到規則中所列的任何收件者。
    
- **重新導向郵件的次數** 根據收件匣規則自動重新導向、轉寄或回覆郵件的次數。 例如，使用者 A 的收件匣規則會根據寄件者，將郵件重新導向到使用者 B。 使用者 B 的收件匣規則會根據主旨行中的關鍵字，將郵件轉寄給使用者 C。 如果某封郵件同時符合這兩項條件，該郵件將只會傳送給使用者 B 而不會轉寄給使用者 C，因為只允許重新導向一次。 在此情況下，會丟棄郵件，而不傳送未傳遞回報（NDR）給使用者 B，表示郵件未傳遞給使用者 C。我們會使用 X 毫秒-Exchange-收件匣規則來判斷重新導向郵件的次數。 此標頭也會保留在 Exchange 組織界限內。

- **傳輸規則重新導向郵件的次數**會根據傳輸規則重新導向郵件的次數。 例如，Exchange 組織 Tailspin 玩具有一個傳輸規則，可將傳送給使用者 A 的每封郵件重新導向至位於 Exchange 組織 Contoso 中的使用者 B。 在 Exchange 組織 Contoso 內，已有一個傳輸規則，可將傳送給使用者 B 的每封郵件重新導向至位於 Exchange 組織 A Datum Corporation 的使用者 C。 在此情況下，郵件會被刪除，而未傳遞回報（NDR）具有狀態碼，並拒絕郵件*550 5.7.128 TRANSPORT。規則。RejectMessage;已超過傳輸規則的迴圈計數，郵件被拒絕*會傳送給使用者 A。我們會使用 X-MS-Transport 標頭來判斷郵件已由傳輸規則重新導向的次數。 此標頭也會保留在 Exchange 組織界限內。

### <a name="journal-transport-and-inbox-rule-limits-across-office-365-options"></a>跨 Office 365 選項的日誌、傳輸和收件匣規則限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能**|**Office 365 商務基本版**|**Office 365 商務進階版**|**Office 365 企業版 E1**|**Office 365 企業版 E3**|**Office 365 企業版 E5**|**Office 365 企業版 F3**|
|日誌規則數目上限|50 條規則|50 條規則|50 條規則|50 條規則|50 條規則|50 條規則|
|傳輸規則數目上限|300 條規則|300 條規則|300 條規則|300 條規則|300 條規則|300 條規則|
|個別傳輸規則的大小上限|8 KB|8 KB|8 KB|8 KB|8 KB|8 KB|
|所有傳輸規則中使用之所有規則運算式的字元限制|20 KB|20 KB|20 KB|20 KB|20 KB|20 KB|
|附件內容的掃描限制|1 MB|1 MB|1 MB|1 MB|1 MB|1 MB|
|所有傳輸規則新增到郵件中的收件者人數上限|100 位收件者|100 位收件者|100 位收件者|100 位收件者|100 位收件者|100 位收件者|
|轉寄者限制|10 位收件者|10 位收件者|10 位收件者|10 位收件者|10 位收件者|10 位收件者|
|重新導向郵件的次數|1 次重新導向|1 次重新導向|1 次重新導向|1 次重新導向|1 次重新導向|1 次重新導向|
|傳輸規則重新導向郵件的次數|1 次重新導向|1 次重新導向|1 次重新導向|1 次重新導向|1 次重新導向|1 次重新導向|

### <a name="journal-transport-and-inbox-rule-limits-across-standalone-options"></a>不同獨立選項中的日誌、傳輸和收件匣規則限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能**|**Exchange Server 2013**|**Exchange Online 方案 1**|**Exchange Online 方案 2**|**Exchange Online Kiosk**|
|日誌規則數目上限|無限制|50 條規則|50 條規則|50 條規則|
|傳輸規則數目上限|無限制|300 條規則|300 條規則|300 條規則|
|個別傳輸規則的大小上限|40 KB|8 KB|8 KB|8 KB|
|所有傳輸規則中使用之所有規則運算式的字元限制|無限制|20 KB|20 KB|20 KB|
|所有傳輸規則新增到郵件中的收件者人數上限|無限制|100 位收件者|100 位收件者|100 位收件者|
|轉寄者限制|無限制|10 位收件者|10 位收件者|10 位收件者|
|重新導向郵件的次數|3 次重新導向|1 次重新導向|1 次重新導向|1 次重新導向|
|傳輸規則重新導向郵件的次數|無限制|1 次重新導向|1 次重新導向|1 次重新導向|

## <a name="moderation-limits"></a>仲裁限制

這些限制會控制在通訊群組和傳輸規則套用之郵件核准所採用的仲裁設定。

- **仲裁信箱的大小上限**：如果仲裁信箱超過此限制，需要仲裁的郵件會在未傳遞回報（NDR）中傳回給寄件者。

- **仲裁者數目上限**：您可以指派給單一仲裁通訊群組的仲裁者數目上限，也可以使用單一傳輸規則新增至郵件。 請注意，您無法將通訊群組指定為仲裁者。

- **等候仲裁的郵件到期**：依預設，等候仲裁的郵件會在兩天后到期。 不過，處理到期的仲裁郵件會在每7天執行一次。 這表示，仲裁郵件可能會在兩到九天的任何時間到期。

- **到期仲裁通知訊息的最大速率**：此限制會設定一小時內到期之仲裁郵件的通知訊息數目上限。 這項限制是設置在資料中心內的每個信箱資料庫上。

在大量使用期間，某些寄件者可能不會收到有關仲裁郵件已過期的通知郵件。不過，這些通知還是可以使用傳遞回報找到。

### <a name="moderation-limits-across-office-365-options"></a>不同 Office 365 選項的仲裁限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能**|**Office 365 商務基本版**|**Office 365 商務進階版**|**Office 365 企業版 E1**|**Office 365 企業版 E3**|**Office 365 企業版 E5**|**Office 365 企業版 F3**|
|仲裁信箱的大小上限|10GB|10 GB|10 GB|10 GB|10 GB|10 GB|
|仲裁者人數上限|10 位仲裁者|10 位仲裁者|10 位仲裁者|10 位仲裁者|10 位仲裁者|10 位仲裁者|
|等候仲裁的郵件到期日|2 天|2 天|2 天|2 天|2 天|2 天|
|過期仲裁通知郵件的最大速率|每小時 300 個過期通知|每小時 300 個過期通知|每小時 300 個過期通知|每小時 300 個過期通知|每小時 300 個過期通知|每小時 300 個過期通知|

### <a name="moderation-limits-across-standalone-options"></a>不同獨立選項的仲裁限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能**|**Exchange Server 2013**|**Exchange Online 方案 1**|**Exchange Online 方案 2**|**Exchange Online Kiosk**|
|仲裁信箱的大小上限|沒有限制<sup>1</sup>|10GB|10 GB|10 GB|
|仲裁者人數上限|無限制|10 位仲裁者|10 位仲裁者|10 位仲裁者|
|等候仲裁的郵件到期日|5 天<sup>1</sup>|2 天|2 天|2 天|
|過期仲裁通知郵件的最大速率|每小時 300 個過期通知|每小時 300 個過期通知|每小時 300 個過期通知|每小時 300 個過期通知|

> [!NOTE]
> <sup>1</sup> 這是 Exchange Server 2013 組織的預設限制。系統管理員可以為其組織變更此值。

## <a name="exchange-activesync-limits"></a>Exchange ActiveSync 限制

下列限制適用於 Microsoft Exchange ActiveSync，這是一種用戶端通訊協定，可以同步處理行動裝置與 Exchange 之間的信箱資料。

- **Exchange ActiveSync 裝置限制**：每個信箱的 exchange ActiveSync 裝置數目上限。

- **Exchange ActiveSync 裝置刪除限制**： exchange 系統管理員可在單一月內刪除的 exchange ActiveSync 裝置數目上限。

### <a name="exchange-activesync-limits-across-office-365-options"></a>不同 Office 365 選項的 Exchange ActiveSync 限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能**|**Office 365 商務基本版**|**Office 365 商務進階版**|**Office 365 企業版 E1**|**Office 365 企業版 E3**|**Office 365 企業版 E5**|**Office 365 企業版 F3**|
|Exchange ActiveSync 裝置限制|100|100|100|100|100|100|
|Exchange ActiveSync 裝置刪除限制|共|共|共|共|共|共|

### <a name="exchange-activesync-limits-across-standalone-options"></a>不同獨立選項的 Exchange ActiveSync 限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能**|**Exchange Server 2013**|**Exchange Online 方案 1**|**Exchange Online 方案 2**|**Exchange Online Kiosk**|
|Exchange ActiveSync 裝置限制|100|100|100|100|
|Exchange ActiveSync 裝置刪除限制|共|共|共|共|
