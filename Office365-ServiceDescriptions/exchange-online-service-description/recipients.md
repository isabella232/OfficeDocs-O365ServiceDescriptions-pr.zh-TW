---
title: 收件者
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-recipients
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: da22b03a-c981-49c6-9928-4312c2c5e2ee
description: 本主題說明 Microsoft Exchange Online 中包含的收件者相關功能。 其中包括電子郵件、連絡人、通訊群組，以及行事曆與排程功能。
ms.openlocfilehash: 5ede65581fc1962a55e565c54509998b9e05b9d0
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173558"
---
# <a name="recipients"></a>收件者

本主題說明 Microsoft Exchange Online 中包含的收件者相關功能。 其中包括電子郵件、連絡人、通訊群組，以及行事曆與排程功能。
  
## <a name="email"></a>電子郵件

每位 Microsoft Exchange Online 訂閱者皆接收信箱，而專用信箱可用於排程設備資源（如會議室）以及多重使用者存取共享電子郵件地址。最高儲存限制適用於大多數的信箱，而管理員可控制允許的信箱大小。自動通知與限制可在使用者信箱接近容量上限或已達容量上限時提醒使用者。Exchange Online 同時擁有數種郵件上限類型－郵件大小、郵件率以及收件者清單上限。所有這些功能與限制的詳細資訊如下所示。
  
> [!NOTE]
> Exchange Online 中不再支援 全部擷取位址。 由於可防止潛在垃圾郵件的收件者篩選，因此會拒絕組織中不存在的電子郵件地址。 
  
### <a name="mailbox-types-storage-limits-and-capacity-alerts"></a>信箱類型、儲存限制及容量警示

每位使用者可使用的信箱儲存量和預設信箱大小由信箱類型和使用者的訂閱授權而定。管理員可降低單一使用者或全域的最高信箱大小。當使用者的信箱接近容量限制或達到容量限制時，Exchange Online 也會提供通知。
  
如需詳細資訊，請參閱本主題中的「信箱儲存限制」和「容量警示」一節中的 [Exchange Online 限制](exchange-online-limits.md)。
  
### <a name="mailtips"></a>MailTips

寄件提醒為自動化、具資訊內容的郵件，在使用者編寫或傳送郵件時，將出現在收件人：列的上方。專為協助預防意外傳遞、違反政策或不必要的未傳遞回報 (NDR) 而設計。舉例來說，寄件提醒可在寄件人嘗試傳送郵件給過大的群組、包含外部收件人的群組、或者遭仲裁或限制的通訊群組時產生警告。如需詳細資訊，請參閱[郵件提示](/exchange/clients-and-mobile-in-exchange-online/mailtips/mailtips)。
  
### <a name="delegate-access"></a>委派存取

Exchange Online 支援委任存取－允許他人管理使用者電子郵件與行事曆的能力。 委任存取常用於經理與助理之間，因助理需處理經理的電子郵件並安排經理的行事曆。 您可以透過 Outlook 或 Outlook 網頁版中的 Exchange Online 使用者，或 Exchange 系統管理中心中的管理員來啟用委派存取。 
  
委任存取有兩種類型：
  
- **代理傳送權限** 代理人可編寫電子郵件並在寄件者欄位輸入其他人的姓名，將顯示為「委任姓名」代表「姓名」。 
    
- **代表傳送權限** 代理人可以信箱擁有者身分自他人的信箱傳送郵件。此情況常見於有共用信箱以及不自 Exchange Online 而自該共用信箱傳送電子郵件的員工。 
    
如需委派存取權的詳細資訊，請參閱[管理收件者的權限](/Exchange/recipients/mailbox-permissions)。
  
### <a name="inbox-rules"></a>收件匣規則

Exchange Online 允許使用者建立收到電子郵件時的收件匣規則，自動執行特定、以標準為基礎的動作。 舉例來說，若郵件發送給特定通訊群組，即可建立規則以自動移動所有郵件至特定資料夾。 使用者在 Outlook 或網頁上的 Outlook 中管理收件匣規則。 管理員可藉停用伺服器端轉寄及/或伺服器端自動回覆來封鎖特定收件匣規則類型。 例如，停用伺服器端轉寄可防止使用者自動轉寄電子郵件至個人帳戶。 相同地，停用伺服器端的自動回覆可防止外部人士使用這些回覆來辨識有效的電子郵件地址。 這些變更將透過 Windows PowerShell 完成。
  
### <a name="clutter"></a>雜亂資料

雜亂資料設計來協助您專注於收件匣中的最重要郵件。它會使用電腦學習，透過移出低優先順序的郵件並將它放入新的 [雜亂資料] 資料夾，來去除收件匣的雜亂資料。雜亂資料會使用現有電子郵件規則，因此，如果您已經建立規則來組織電子郵件，則會繼續套用那些規則，而且雜亂資料不會處理那些郵件。預設會停用收件匣的雜亂資料。若要深入了解，請參閱[在 Office 365 中去除收件匣的雜亂資料](https://go.microsoft.com/fwlink/?linkid=2144145)。
  
### <a name="connected-accounts"></a>連結帳戶

「已連線的帳戶」功能可讓 Exchange Online 使用者將外部電子郵件帳戶 (（例如個人帳戶）) 至 Exchange Online 中的內部電子郵件帳戶，然後使用網頁上的 Outlook 以單一位置與其所有郵件互動。 連線的帳戶會在登入至網頁型 Outlook 時自動同步處理。使用者也可以手動從網頁上的 Outlook 同步處理帳戶。 管理員可透過 [Exchange 系統管理中心](/exchange/exchange-admin-center)為特定使用者或所有使用者啟用或停用此功能。
  
### <a name="inactive-mailboxes"></a>非使用中的信箱

Exchange Online 可供使用者無限期保留已刪除信箱的內容。此功能稱為非使用中的信箱。在刪除信箱前，針對該信箱設定「就地保留」或「訴訟暫止」屬性便能使其成為非使用中的信箱。此設定可使您無限期保留該信箱中的內容。管理員、法務人員或記錄管理員均可使用 Exchange Online 中的就地 eDiscovery 功能存取非使用中的信箱的內容。
  
啟用非使用中的信箱要求信箱必須具備 Exchange Online (計劃 2) 的指派授權或 Exchange Online 封存訂閱，才能在其遭刪除前設定「就地保留」或「訴訟暫止」屬性。
  
> [!IMPORTANT]
> 若在信箱遭刪除前未設定 Hold 屬性，則該信箱中的內容將不予保留且無法提供搜尋。信箱在遭刪除後的 30 天內可復原，若未復原，則 30 天後系統將不保留該信箱的內容，且將永久刪除該信箱。 
  
如需詳細資訊，請參閱：
  
- [在 Exchange Online 中管理非使用中的信箱](/microsoft-365/security/office-365-security/exchange-online-protection-overview)
    
- [就地保留和訴訟資料暫留](/exchange/security-and-compliance/in-place-and-litigation-holds)
    
- [就地 eDiscovery](/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery)
    
## <a name="contacts-and-distribution-groups"></a>連絡人與通訊群組

### <a name="offline-address-book"></a>離線通訊錄

「離線通訊錄」功能可提供 Outlook 全域通訊清單 (GAL) 中可用之 Active Directory 資訊的快照。 將在 Outlook 中快取，讓使用者離線工作時可使用。
  
### <a name="address-book-policies"></a>通訊錄原則

Exchange Online 支援通訊錄原則。 通訊錄原則 (ABP) 允許您將使用者分入特定群組以提供您組織的全域通訊清單 (GAL) 之自訂檢視。 建立 ABP 時，您要指定 GAL、離線通訊錄 (OAB)、會議室清單和一個以上的通訊清單給該原則。 然後，您可以將 ABP 指派給信箱使用者，讓他們可以存取 Outlook 和網頁型 Outlook 中的自訂 GAL。 管理員可以使用遠端 Windows PowerShell 來設定通訊錄原則。 若要深入了解通訊錄原則，請參閱 [Exchange Online 中的通訊錄](/exchange/address-books/address-books)。
  
### <a name="address-lists"></a>通訊清單

Exchange Online 支援通訊清單和 Gal 的自訂。 GAL 是所有擁有郵件功能的使用者、通訊群組和外部連絡人的全組織目錄。 系統管理員可以使用目錄同步作業工具或遠端 Windows PowerShell，隱藏 GAL 中的使用者、通訊群組和連絡人。
  
### <a name="hierarchical-address-books"></a>階層式通訊錄

 階層式通訊錄可讓使用者使用組織階層，在 Exchange 組織中瀏覽收件者。管理員可依年資和排名 (不用按字母順序) 來自訂通訊錄。 
  
### <a name="distribution-groups-global"></a>通訊群組（全域）

通訊群組（或通訊清單）為使用者、連絡人與其他通訊群組的組合，可為公司中的所有使用者使用。 使用者寄送電子郵件給通訊群組別名以傳送郵件給所有群組中的人。 通訊群組與個人於 Outlook 中建立的個人通訊群組相似，除通訊群組的成員清單可提供給公司中所有人使用。 管理員可在 Exchange 系統管理中心中建立通訊群組。 群組可自內部部署的 Active Directory 與 Exchange Online 同步。 它們會出現在 Outlook 的 GAL 中。 Exchange Online 支援進階通訊群組能力，包括以下所述：
  
- **受限的通訊群組** 根據預設，任何人都可以傳送電子郵件給任何通訊群組。管理員可變更僅允許特定個人傳送電子郵件給特定群組的權限－例如，減少大量通訊清單的不當使用。管理員同時可阻止外部來源傳送電子郵件給通訊群組，以阻擋垃圾郵件。對於使用 Directory Synchronization 工具自內部部署 Active Directory 同步的通訊群組來說，限制的屬性將自動同步至雲端。如需詳細資訊，請參閱 [管理通訊群組](/Exchange/recipients/distribution-groups)。
    
- **動態通訊群組** 動態通訊群組的成員清單 (也稱為動態通訊群組清單或以查詢為基礎的通訊群組清單) 將在每次傳送郵件給群組時執行計算。此計算係根據管理員定義的篩選器與條件而定。這些設定可透過遠端 Windows PowerShell 於 Exchange Online 中管理。如需動態通訊群組的詳細資訊，請參閱 [管理動態通訊群組](/Exchange/recipients/dynamic-distribution-groups/dynamic-distribution-groups)。
    
    > [!IMPORTANT]
    > Office 365 目錄同步處理工具會忽略內部部署 Active Directory 中的動態通訊群組，且不會將這些群組與 Exchange Online 同步處理。使用 Directory Synchronization 工具的組織應使用命名慣例以避免受內部部署管理的一般通訊群組與在 Exchange Online 中管理的動態通訊群組間發生衝突。 
  
- **仲裁通訊群組** 管理員可選取仲裁者來控管傳送給通訊群組的郵件流量。透過仲裁通訊群組，任何人皆可傳送電子郵件給通訊群組別名，但在郵件傳送給群組成員前，仲裁者須檢視並核准該郵件。如需仲裁的詳細資訊，請參閱 [管理通訊群組](/Exchange/recipients/distribution-groups)中的「訊息核准」一節。
    
- **自助通訊群組** 管理員可授予權限讓使用者從網路架構介面管理自己的通訊群組成員。使用者將獲得建立、刪除、加入或離開通訊群組的權限。這些功能根據預設將為所有 Exchange Online 使用者啟用。若需要，管理者可停用這些功能以限制僅讓 IT 部門可管理通訊群組。也可建立命名原則來標準化並管理使用者建立的通訊群組名稱。例如，建立名稱時可新增特定前置詞或尾碼至通訊群組名稱，或阻止特定字詞用於群組名稱。 
    
    > [!IMPORTANT]
    > 自助服務功能不可用於自內部部署 Active Directory 同步至 Exchange Online 的通訊群組。使用 Directory Synchronization 的組織應使用命名慣例以避免受內部部署管理的通訊群組與在雲端中管理的動態通訊群組間發生衝突。 
  
### <a name="external-contacts-global"></a>外部連絡人 (全域)

外部連絡人為其中包含在特定組織外作業的個人資訊的紀錄。 外部連絡人與個人於 Outlook 中建立的個人連絡人相似，除外部連絡人可提供給公司中所有人使用。 管理員可使用 Exchange 系統管理中心或遠端 Windows PowerShell 建立外部連絡人。 這些連絡人可自內部部署的 Active Directory 與 Exchange Online 同步。 它們會出現在 Outlook 的 GAL 中。
  
如需外部連絡人的詳細資訊，請參閱[在 Exchange Online 中建立組織關係](/exchange/sharing/organization-relationships/create-an-organization-relationship)。
  
## <a name="calendar-and-scheduling"></a>日曆與排程

### <a name="resource-mailboxes"></a>資源信箱

資源信箱（例如會議室與實體設備）代表公司的會議室或其他設施或資源。 使用者可以在 Outlook 或網頁型 Outlook 中新增資源的電子郵件別名到會議邀請中，以預約會議室或資源。 會議室和資源會出現在 Outlook 和 Outlook 網頁版的 GAL 中。
  
管理員可使用 Exchange 系統管理中心或遠端 Windows PowerShell 來建立資源信箱。信箱可自內部部署的 Active Directory 與 Exchange Online 同步。
  
如需資源信箱的相關資訊，請參閱：
  
- [建立及管理會議室信箱](/Exchange/recipients/room-mailboxes)
    
- [管理設備信箱](/Exchange/recipients/equipment-mailboxes)
    
### <a name="conference-room-management"></a>會議室管理

Exchange Online 包含自動化會議室與其他資源排程的 Resource Booking Attendant (RBA)。受 RBA 設定的資源信箱將根據資源的行事曆時間來接受、拒絕或認可來自會議組織人的會議請求。 
  
管理員可以自訂自動會議室回應，並在網頁上的 Outlook 中設定預約原則。 這些原則包含可排定資源的人、可排程的時間、在資源行事曆上顯示的會議資訊、以及允許的排程衝突百分比。 管理員可停用 Resource Booking Attendant 並指定特定使用者以手動管理關於會議室的會議請求。
  
Ad管理員需透過遠端 Windows PowerShell 來定義並管理 RBA 設定。
  
### <a name="out-of-office-replies"></a>外出回覆

外出回覆郵件將自動代表使用者回覆 Exchange Online 寄來的郵件。使用者可事先排定外出郵件，指定詳細的開始與結束時間，並可未內部收件者與外部收件者建立不同的外出回覆郵件。也可自支援此 Exchange ActiveSync 功能的行動裝置建立外出郵件。在 Exchange Online 內的垃圾郵件與郵寄清單感知將防止使用者傳送外部外出郵件給擴充的郵寄清單與可能的垃圾郵件寄件者。管理員也可防止使用者使用 Windows PowerShell 傳送外出郵件給外部使用者。
  
### <a name="calendar-sharing"></a>行事曆共用

使用者可以下列方式之一分享其個人行事曆：
  
- **共用同盟行事曆** 同盟指的是支援同盟共用的基礎信任基礎結構，對 Exchange 使用者而言，這是與其他外部同盟組織中的收件者共用空閒/忙碌行事曆資料和連絡人資訊的簡易方法。 其中包括 Exchange Online 組織或在內部部署執行 Exchange Server 2010 或 Exchange Server 2013 組織。 Exchange Online 系統管理員不需要設定 Microsoft Federation Gateway 的信任，因為建立 Microsoft 服務時，會為所有 Exchange Online 客戶預先設定此信任。 預設共用原則可讓使用者從網頁上的 Outlook 或 Outlook 2010 傳送行事曆共用邀請。 管理員使用遠端 Windows PowerShell 來停用此原則或設定使用者可共享的空閒／忙碌行事曆資料層級。 管理員也可與其他同盟組織建立組織對組織的關係，允許每個使用者的空閒／忙碌資訊層級顯示於跨組織平台上，而無需讓個別使用者建立共享邀請。 在管理員定義的共享原則及／或組織對組織關係的範圍內，使用者可進一步個別限制其共享詳情。 
    
- **共用網際網路行事曆** Exchange Online 允許使用者使用 iCal 格式由組織內或組織外的使用者進行匿名存取以發佈行事曆。 收件者可使用 Exchange、其他平台或單純使用網路瀏覽器。 Exchange Online 使用者也可以訂閱其他人透過 iCal 發佈到網際網路位置的行事曆。 此個人行事曆共享與由管理員設定同盟行事曆共享不同，並提供組織對組織的空閒／忙碌共享。 在管理員設定並套用允許的共用原則之後，使用者才可以以 iCal 格式發佈行事歷數據。 管理員可使用 Windows PowerShell 為組織中的使用者停用 iCal 發布與 iCal 訂閱。
    
如需有關同盟共用的詳細資訊，請參閱[在 Exchange Online 中共用](/exchange/sharing/sharing)。
  
### <a name="outlook-2010-room-finder"></a>Outlook 2010 會議室尋找工具

Exchange Online 支援 Outlook 2010 的會議室尋找工具功能，將會議室排定為清單（例如稱為「Building 5 rooms」的清單），讓排定會議時間時更容易找到附近的會議室。若要顯示於會議室清單，通訊群組須以以下方式之一特別標示： 
  
- 可透過遠端 Windows PowerShell 建立新的會議室清單。 
    
- 任何只包含會議室的通訊群組可透過遠端 Windows PowerShell 轉換為會議室清單。
    
## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱 [Exchange Online 服務說明](exchange-online-service-description.md)。
