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
ms.openlocfilehash: a2d1f37bf4f86399522573d18177f6c397fd761c
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132637"
---
# <a name="recipients"></a>收件者

本主題說明 Microsoft Exchange Online 中包含的收件者相關功能。 其中包括電子郵件、連絡人、通訊群組，以及行事曆與排程功能。
  
## <a name="email"></a>電子郵件

Every Microsoft Exchange Online subscriber receives a mailbox, and specialty mailboxes are available for scheduling facilities resources (such as conference rooms) and for multiuser access to shared email addresses. Maximum storage limits apply to most mailboxes, and administrators can control allowable mailbox sizes. Automated notifications and restrictions can alert users when their mailboxes are nearing, or at, capacity. Exchange Online also has several types of message limitations—message size, message rate, and recipient list limits. Details of all these features and limits are provided below.
  
> [!NOTE]
> Exchange Online 中不再支援 全部擷取位址。 由於可防止潛在垃圾郵件的收件者篩選，因此會拒絕組織中不存在的電子郵件地址。 
  
### <a name="mailbox-types-storage-limits-and-capacity-alerts"></a>信箱類型、儲存限制及容量警示

The amount of mailbox storage available to a user and the default mailbox size are determined by the mailbox type and the user's subscription license. Administrators can reduce maximum mailbox sizes per user or globally. Exchange Online also provides notifications when a user's mailbox is nearing, or at, capacity.
  
如需詳細資訊，請參閱本主題中的「信箱儲存限制」和「容量警示」一節中的[Exchange Online 限制](exchange-online-limits.md)。
  
### <a name="mailtips"></a>MailTips

MailTips are automated, informative messages that appear above the To: line while users are composing or addressing a message. They are designed to help prevent accidental delivery, policy violations, or unnecessary non-delivery reports (NDRs). For example, MailTips can generate an alert if senders try to send messages to overly large groups, to groups that contain external recipients, or to a distribution group that is moderated or restricted. For more information, see [MailTips](https://go.microsoft.com/fwlink/p/?LinkId=401472).
  
### <a name="delegate-access"></a>委派存取

Exchange Online 支援委任存取－允許他人管理使用者電子郵件與行事曆的能力。 委任存取常用於經理與助理之間，因助理需處理經理的電子郵件並安排經理的行事曆。 您可以透過 Outlook 或 Outlook 網頁版中的 Exchange Online 使用者，或 Exchange 系統管理中心中的管理員來啟用委派存取。 
  
委任存取有兩種類型：
  
- **代理傳送權限** 代理人可編寫電子郵件並在寄件者欄位輸入其他人的姓名，將顯示為「委任姓名」代表「姓名」。 
    
- **Send As permissions** The delegate can send messages from the other person's mailbox as if the delegate were the mailbox owner. This scenario is common where there is a shared mailbox and several employees send email messages from that shared mailbox instead of from their Exchange Online accounts. 
    
如需委派存取權的詳細資訊，請參閱[管理收件者的權限](https://technet.microsoft.com/library/jj919240%28v=exchg.160%29.aspx)。
  
### <a name="inbox-rules"></a>收件匣規則

Exchange Online 允許使用者建立收到電子郵件時的收件匣規則，自動執行特定、以標準為基礎的動作。 舉例來說，若郵件發送給特定通訊群組，即可建立規則以自動移動所有郵件至特定資料夾。 使用者在 Outlook 或網頁上的 Outlook 中管理收件匣規則。 管理員可藉停用伺服器端轉寄及/或伺服器端自動回覆來封鎖特定收件匣規則類型。 例如，停用伺服器端轉寄可防止使用者自動轉寄電子郵件至個人帳戶。 相同地，停用伺服器端的自動回覆可防止外部人士使用這些回覆來辨識有效的電子郵件地址。 這些變更將透過 Windows PowerShell 完成。
  
### <a name="clutter"></a>雜亂資料

Clutter is designed to help you focus on the most important messages in your inbox. It uses machine learning to de-clutter your inbox by moving lower priority messages out of your way and into a new Clutter folder. Clutter respects your existing email rules, so if you have created rules to organize your email those rules continue to be applied and Clutter won't act on those messages. Clutter is disabled by default for your inbox. To learn more, see [De-clutter your inbox in Office 365](https://www.microsoft.com/en-us/microsoft-365/blog/2014/11/11/de-clutter-inbox-office-365/).
  
### <a name="connected-accounts"></a>連結帳戶

「已連線的帳戶」功能可讓 Exchange Online 使用者將外部電子郵件帳戶（例如個人帳戶）連線至 Exchange Online 中的內部電子郵件帳戶，然後使用網頁上的 Outlook，在單一位置與其所有郵件互動。 連線的帳戶會在登入至網頁型 Outlook 時自動同步處理。使用者也可以手動從網頁上的 Outlook 同步處理帳戶。 管理員可透過 [Exchange 系統管理中心](https://go.microsoft.com/fwlink/?LinkID=785297&amp;clcid=0x409)為特定使用者或所有使用者啟用或停用此功能。
  
### <a name="inactive-mailboxes"></a>非使用中的信箱

Exchange Online provides the capability to preserve the contents of deleted mailboxes indefinitely. This feature is called inactive mailboxes. A mailbox becomes inactive when an In-Place Hold or a Litigation Hold is placed on the mailbox before it's deleted. This results in the contents of the mailbox being preserved indefinitely. Administrators, compliance officers, or record managers can use the In-Place eDiscovery feature in Exchange Online to access the contents of an inactive mailbox.
  
啟用非使用中的信箱要求信箱必須具備 Exchange Online (計劃 2) 的指派授權或 Exchange Online 封存訂閱，才能在其遭刪除前設定「就地保留」或「訴訟暫止」屬性。
  
> [!IMPORTANT]
> If a hold isn't placed on a mailbox before it's deleted, the contents of the mailbox will not be preserved or discoverable. The mailbox can be recovered within 30 days of deletion, but the mailbox and its contents will be permanently deleted after 30 days if it isn't recovered. 
  
如需詳細資訊，請參閱：
  
- [在 Exchange Online 中管理非使用中的信箱](https://go.microsoft.com/fwlink/p/?LinkId=286991)
    
- [就地保留和訴訟資料暫留](https://go.microsoft.com/fwlink/p/?LinkId=271746)
    
- [就地 eDiscovery](https://go.microsoft.com/fwlink/p/?LinkId=271747)
    
## <a name="contacts-and-distribution-groups"></a>連絡人與通訊群組

### <a name="offline-address-book"></a>離線通訊錄

離線通訊錄功能提供 Outlook 全域通訊清單（GAL）中可用之 Active Directory 資訊的快照。 將在 Outlook 中快取，讓使用者離線工作時可使用。
  
### <a name="address-book-policies"></a>通訊錄原則

Exchange Online 支援通訊錄原則。 通訊錄原則 (ABP) 允許您將使用者分入特定群組以提供您組織的全域通訊清單 (GAL) 之自訂檢視。 建立 ABP 時，您要指定 GAL、離線通訊錄 (OAB)、會議室清單和一個以上的通訊清單給該原則。 然後，您可以將 ABP 指派給信箱使用者，讓他們可以存取 Outlook 和網頁型 Outlook 中的自訂 GAL。 管理員可以使用遠端 Windows PowerShell 來設定通訊錄原則。 若要深入了解通訊錄原則，請參閱 [Exchange Online 中的通訊錄](https://go.microsoft.com/fwlink/p/?LinkId=394203)。
  
### <a name="address-lists"></a>通訊清單

Exchange Online 支援通訊清單和 Gal 的自訂。 GAL 是所有擁有郵件功能的使用者、通訊群組和外部連絡人的全組織目錄。 系統管理員可以使用目錄同步作業工具或遠端 Windows PowerShell，隱藏 GAL 中的使用者、通訊群組和連絡人。
  
### <a name="hierarchical-address-books"></a>階層式通訊錄

 Hierarchical address books allow end users to browse for recipients in their Exchange organization using an organizational hierarchy. Administrators can customize the address book by seniority and rank rather than alphabetical listings. 
  
### <a name="distribution-groups-global"></a>通訊群組（全域）

通訊群組（或通訊清單）為使用者、連絡人與其他通訊群組的組合，可為公司中的所有使用者使用。 使用者寄送電子郵件給通訊群組別名以傳送郵件給所有群組中的人。 通訊群組與個人於 Outlook 中建立的個人通訊群組相似，除通訊群組的成員清單可提供給公司中所有人使用。 管理員可在 Exchange 系統管理中心中建立通訊群組。 群組可自內部部署的 Active Directory 與 Exchange Online 同步。 它們會出現在 Outlook 的 GAL 中。 Exchange Online 支援進階通訊群組能力，包括以下所述：
  
- **Restricted distribution groups** By default, anyone can send emails to any distribution group. Administrators can change permissions to allow only specific individuals to send emails to a particular group—for example, to discourage inappropriate use of large distribution lists. Administrators can also block external sources from sending email to distribution groups to help prevent spam. For distribution groups that are synchronized from on-premises Active Directory using the Directory Synchronization tool, the attributes for restriction are synchronized to the cloud automatically. For more information, see [Manage Distribution Groups](https://technet.microsoft.com/library/mt577270%28v=exchg.160%29.aspx).
    
- **Dynamic distribution groups** The membership list for a dynamic distribution group (also known as a dynamic distribution list, or query-based distribution list) is calculated every time a message is sent to the group. This calculation is based on filters and conditions that the administrator defines. They are managed in Exchange Online through remote Windows PowerShell. For more information about dynamic distribution groups, see [Manage Dynamic Distribution Groups](https://technet.microsoft.com/library/bb123722%28v=exchg.160%29.aspx).
    
    > [!IMPORTANT]
    > The Office 365 Directory Synchronization tool ignores dynamic distribution groups in on-premises Active Directory, and does not synchronize these to Exchange Online. Organizations that use the Directory Synchronization tool should use a naming convention that avoids conflicts between the regular distribution groups that are managed on-premises and the dynamic distribution groups that are managed in Exchange Online. 
  
- **Moderated distribution groups** Administrators can select a moderator to regulate the flow of messages to a distribution group. With moderated distribution groups, anyone can email the distribution group alias, but before the message is delivered to the members of the group, a moderator must review and approve it. For more information about moderation, see the Message Approval section in [Manage Distribution Groups](https://technet.microsoft.com/library/mt577270%28v=exchg.160%29.aspx).
    
- **Self-Service distribution groups** Administrators can give users the ability to manage their own distribution group membership from a web-based interface. Users can be given permissions to create, delete, join, or leave distribution groups. These capabilities are enabled by default for all Exchange Online users. Administrators can disable them so that only the IT department can manage distribution groups, if desired. They can also create naming policies to standardize and manage the names of distribution groups that their users create. For example, they can add a specific prefix or suffix to the distribution group name when it is created, or block specific words from being used in the group's name. 
    
    > [!IMPORTANT]
    > Self-service capabilities are not available for distribution groups that are synchronized from on-premises Active Directory to Exchange Online. Organizations that use Directory Synchronization should use a naming convention that avoids conflicts between distribution groups that are managed on-premises and distribution groups that are managed in the cloud. 
  
### <a name="external-contacts-global"></a>外部連絡人 (全域)

外部連絡人為其中包含在特定組織外作業的個人資訊的紀錄。 外部連絡人與個人於 Outlook 中建立的個人連絡人相似，除外部連絡人可提供給公司中所有人使用。 管理員可使用 Exchange 系統管理中心或遠端 Windows PowerShell 建立外部連絡人。 這些連絡人可自內部部署的 Active Directory 與 Exchange Online 同步。 它們會出現在 Outlook 的 GAL 中。
  
如需外部連絡人的詳細資訊，請參閱[在 Exchange Online 中建立組織關係](https://technet.microsoft.com/library/jj916671%28v=exchg.150%29.aspx)。
  
## <a name="calendar-and-scheduling"></a>日曆與排程

### <a name="resource-mailboxes"></a>資源信箱

資源信箱（例如會議室與實體設備）代表公司的會議室或其他設施或資源。 使用者可以在 Outlook 或網頁型 Outlook 中新增資源的電子郵件別名到會議邀請中，以預約會議室或資源。 會議室和資源會出現在 Outlook 和 Outlook 網頁版的 GAL 中。
  
Administrators create resource mailboxes using the Exchange admin center or remote Windows PowerShell. The mailboxes can also be synchronized with Exchange Online from on-premises Active Directory.
  
如需資源信箱的相關資訊，請參閱：
  
- [建立及管理會議室信箱](https://go.microsoft.com/fwlink/?LinkId=717533&amp;clcid=0x409)
    
- [管理設備信箱](https://go.microsoft.com/fwlink/?LinkId=717534)
    
### <a name="conference-room-management"></a>會議室管理

Exchange Online includes the Resource Booking Attendant (RBA), which automates scheduling of conference rooms and other resources. A resource mailbox that is RBA-configured accepts, declines, or acknowledges meeting requests from a meeting organizer based on the resource's calendar availability. 
  
管理員可以自訂自動會議室回應，並在網頁上的 Outlook 中設定預約原則。 這些原則包含可排定資源的人、可排程的時間、在資源行事曆上顯示的會議資訊、以及允許的排程衝突百分比。 管理員可停用 Resource Booking Attendant 並指定特定使用者以手動管理關於會議室的會議請求。
  
Ad管理員需透過遠端 Windows PowerShell 來定義並管理 RBA 設定。
  
### <a name="out-of-office-replies"></a>外出回覆

Out-of-office messages are automatic replies to incoming messages that Exchange Online sends on behalf of a user. Users can schedule out-of-office messages in advance, with specific start and end times, and can configure separate out-of-office messages for internal and external recipients. They can also set out-of-office messages from mobile devices that support this Exchange ActiveSync feature. Junk-email and mailing-list awareness within Exchange Online prevents users from sending external out-of-office messages to extended mailing lists and potential spammers. Administrators can also prevent users from sending out-of-office messages to external users using remote Windows PowerShell.
  
### <a name="calendar-sharing"></a>行事曆共用

使用者可以下列方式之一分享其個人行事曆：
  
- **共用同盟行事曆** 同盟指的是支援同盟共用的基礎信任基礎結構，對 Exchange 使用者而言，這是與其他外部同盟組織中的收件者共用空閒/忙碌行事曆資料和連絡人資訊的簡易方法。 其中包括 Exchange Online 組織或在內部部署執行 Exchange Server 2010 或 Exchange Server 2013 組織。 Exchange Online 系統管理員不需要設定 Microsoft Federation Gateway 的信任，因為建立 Microsoft 服務時，會為所有 Exchange Online 客戶預先設定此信任。 預設共用原則可讓使用者從網頁上的 Outlook 或 Outlook 2010 傳送行事曆共用邀請。 管理員使用遠端 Windows PowerShell 來停用此原則或設定使用者可共享的空閒／忙碌行事曆資料層級。 管理員也可與其他同盟組織建立組織對組織的關係，允許每個使用者的空閒／忙碌資訊層級顯示於跨組織平台上，而無需讓個別使用者建立共享邀請。 在管理員定義的共享原則及／或組織對組織關係的範圍內，使用者可進一步個別限制其共享詳情。 
    
- **共用網際網路行事曆** Exchange Online 允許使用者使用 iCal 格式由組織內或組織外的使用者進行匿名存取以發佈行事曆。 收件者可使用 Exchange、其他平台或單純使用網路瀏覽器。 Exchange Online 使用者也可以訂閱其他人透過 iCal 發佈到網際網路位置的行事曆。 此個人行事曆共享與由管理員設定同盟行事曆共享不同，並提供組織對組織的空閒／忙碌共享。 在管理員設定並套用允許的共用原則之後，使用者才可以以 iCal 格式發佈行事歷數據。 管理員可使用 Windows PowerShell 為組織中的使用者停用 iCal 發布與 iCal 訂閱。
    
如需有關同盟共用的詳細資訊，請參閱[在 Exchange Online 中共用](https://go.microsoft.com/fwlink/p/?LinkId=271774)。
  
### <a name="outlook-2010-room-finder"></a>Outlook 2010 會議室尋找工具

Exchange Online supports the Room Finder feature of Outlook 2010, which arranges rooms into lists (for example, a list called "Building 5 rooms") to make it easier to find a nearby room when scheduling a meeting. To appear in the room list, a distribution group must be specially marked using one of two methods: 
  
- 可透過遠端 Windows PowerShell 建立新的會議室清單。 
    
- 任何只包含會議室的通訊群組可透過遠端 Windows PowerShell 轉換為會議室清單。
    
## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online 服務說明](exchange-online-service-description.md)。
  