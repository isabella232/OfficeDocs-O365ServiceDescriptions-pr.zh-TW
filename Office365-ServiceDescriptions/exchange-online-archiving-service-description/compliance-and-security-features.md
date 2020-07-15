---
title: Exchange Online 封存中的合規性和安全性功能
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- compliance-and-security-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7482322a-39fe-4a99-b29c-63cb1bc3cf1f
ms.openlocfilehash: b03c74e0c760cf22c12e6973a544553d119471fe
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132737"
---
# <a name="compliance-and-security-features-in-exchange-online-archiving"></a>Exchange Online 封存中的合規性和安全性功能

## <a name="compliance-features-in-exchange-online-archiving"></a>Exchange Online 封存中的符合性功能

下列幾節說明 Microsoft Exchange Online Archiving 的符合性功能。
  
### <a name="retention-policies"></a>保留原則

Exchange Online Archiving 提供保留原則，可協助組織減少電子郵件與其他通訊的相關責任。 透過這些原則，系統管理員可以將保留設定套用到使用者收件匣中的特定資料夾。 管理員也可以將保留原則的功能表提供給使用者，讓他們將原則套用至特定專案、交談或使用 Outlook 2010 或更新版本的資料夾或網頁上的 Outlook。 在 Exchange Online Archiving 中，系統管理員會從內部部署基礎結構來管理保留原則。
  
Exchange Online Archiving offers two types of policies: archive and delete. Both types can be applied to the same item or folder. For example, a user can tag an email message so that it is automatically moved to the personal archive in a specified number of days and deleted after another span of days.
  
使用 Outlook 2010 和更新版本和 Outlook 網頁版，使用者可以將保留原則套用至資料夾、交談或個別郵件，也可以在郵件上查看套用的保留原則和預期刪除日期。 其他電子郵件用戶端的使用者可根據系統管理員所佈建的伺服器端保留原則來刪除或封存電子郵件，但是沒有相同程度的檢視和控制能力。
  
The retention policy capabilities offered in Exchange Online Archiving are the same as those offered in Exchange Server 2010 Service Pack 2 (SP2) and later. Administrators can manage retention policies from on-premises Exchange Server 2010 and later environments. Managed Folders, an older approach to messaging records management that was introduced in Exchange 2007, are not available in and not compatible with Exchange Online Archiving. For more details, see [Retention Tags and Retention Policies](https://go.microsoft.com/fwlink/p/?LinkID=314153).
  
### <a name="in-place-hold-and-litigation-hold"></a>就地保留與訴訟暫止

When a reasonable expectation of litigation exists, organizations are required to preserve electronically stored information (ESI), including email that's relevant to the case. This expectation can occur before the specifics of the case are known, and preservation is often broad. Organizations may preserve all email related to a specific topic, or all email for certain individuals.
  
在 Exchange Online 中，您可以使用就地保留或訴訟資料暫留功能來達成下列目標：
  
- 暫停使用者使用信箱，並永久保留信箱項目
    
- 保留由使用者或自動刪除程序 (例如 MRM) 刪除的信箱項目
    
- 儲存原始郵件的複本，以防信箱郵件遭到竄改、被使用者變更或自動處理
    
- 無限期或於指定期間內保留項目
    
- 無需暫停 MRM，讓使用者不會察覺到被保留
    
- 使用就地保留 eDiscovery 來搜尋信箱郵件，包括被保留的郵件
    
此外，您還可以使用就地保留來：
  
- 搜尋並保留符合指定條件的郵件
    
- 針對不同案件或調查，將使用者進行多項就地保留
    
> [!NOTE]
> 當您對信箱進行就地保留或訴訟資料暫留時，會同時保留主要和封存信箱。 
  
如需詳細資訊，請參閱[原有範圍暫止](https://go.microsoft.com/fwlink/p/?LinkId=271746)。
  
> [!NOTE]
> 對於 Exchange Online Archiving使用者而言，[可復原的項目] 資料夾的預設配額為 100 GB。 
  
### <a name="in-place-ediscovery"></a>就地 eDiscovery

Exchange Online Archiving supports In-Place eDiscovery for searching the contents of mailboxes in an organization. Using the Exchange admin center or remote Windows PowerShell from an on-premises Exchange 2013 server, administrators or authorized Discovery managers can search a variety of mailbox items - including email messages, attachments, calendar appointments, tasks, and contacts. In-Place eDiscovery can search simultaneously across primary mailboxes and archives. Rich filtering capabilities include sender, receiver, message types, sent date, received date, carbon copy, and blind carbon copy, along with Keyword Query Language (KQL) syntax. For more details, see [In-Place eDiscovery](https://go.microsoft.com/fwlink/p/?LinkId=314169).
  
The Exchange admin center and remote Windows PowerShell can be used to search up to 5,000 mailboxes at a time in an In-Place eDiscovery search. For details about using remote Windows PowerShell to run In-Place eDiscovery searches, see [New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170). 
  
> [!NOTE]
> In remote Windows PowerShell, the  `Search-Mailbox` cmdlet can be used to search more than 5,000 mailboxes. For details about searching large numbers of mailboxes using remote Windows PowerShell, see [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171). 
  
Results of an In-Place eDiscovery search can be previewed in the Exchange admin center, exported to a .pst file, or copied to a special type of mailbox, called a discovery mailbox. Administrators or compliance officers can connect to the discovery mailbox to review messages. For details, see [Create an In-Place eDiscovery Search](https://go.microsoft.com/fwlink/p/?LinkId=314172).
  
> [!NOTE]
> When copying search results for an In-Place eDiscovery search performed across on-premises and cloud-based mailboxes or archives, you must select an on-premises discovery mailbox. Messages from the on-premises primary mailbox and the cloud-based archive are copied to the on-premises discovery mailbox. 
  
Administrators can also search for and delete inappropriate email messages sent to multiple mailboxes across their organizations. For example, if confidential salary information was accidentally sent to all employees, an administrator can delete the email from the users' mailboxes. This type of search is not available in the Exchange admin center. It must be performed using Remote PowerShell. For details on how to delete messages from users' mailboxes, see [Search and Delete Messages](https://go.microsoft.com/fwlink/p/?LinkId=314173).
  
## <a name="security-features-in-exchange-online-archiving"></a>Exchange Online 封存中的安全性功能

下列幾節說明 Microsoft Exchange Online Archiving 的安全性功能。
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a>內部部署伺服器與 Exchange Online 封存之間的加密

TLS 用來加密電子郵件伺服器之間的連線，以防止詐騙並為傳輸中的郵件添加機密性。 TLS 也可用來保護內部部署郵件伺服器流量，以進行 Exchange Online 封存的 Microsoft 資料中心。
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a>用戶端與 Exchange Online 封存之間的加密

與 Exchange Online Archiving的用戶端連線使用下列加密方法來加強安全性：
  
- SSL 是用來保護 Outlook、Outlook 網頁版和 Exchange Web 服務流量，使用 TCP 埠443。
    
- 與內部部署伺服器的用戶端連線不會因為 Exchange Online Archiving的出現而改變。
    
### <a name="encryption-smime-and-pgp"></a>加密：S/MIME 和 PGP

Exchange Online Archiving will store Secure/Multipurpose Internet Mail Extensions (S/MIME) messages. However, Exchange Online Archiving does not host S/MIME functions or host the public keys, nor does it provide key repository, key management, or key directory services because all of these services attach to the on-premises Exchange infrastructure.
  
同樣地，Exchange Online Archiving會儲存使用用戶端、協力廠商加密解決方案 (如 Pretty Good Privacy (PGP)) 加密的郵件。
  
### <a name="information-rights-management"></a>資訊版權管理

Exchange Online Archiving does not provide hosted Information Rights Management (IRM) services, but administrators can use on-premises Active Directory Rights Management Services (AD RMS). If an AD RMS server is deployed, Outlook can communicate directly with that server, enabling users to compose and read IRM-protected messages. If interoperability between the AD RMS server and the on-premises Exchange environment is configured, users will be able to compose and read IRM-protected messages.
  
#### <a name="support-for-irm-in-outlook-on-the-web"></a>在 web 上的 Outlook 中支援 IRM

使用者可以在網頁型 Outlook 中以本機方式閱讀和建立受 IRM 保護的郵件，就像在 Outlook 中一樣。 您可以透過 Internet Explorer、Firefox、Safari 和 Chrome （不需要外掛程式）來存取網頁上的受 IRM 保護的郵件。 這些郵件包含全文檢索搜尋、交談檢視和預覽窗格。 必須設定 Active Directory Rights Management Services 伺服器與內部部署 Exchange 環境之間的交互操作性，才能啟用此功能。
  
#### <a name="irm-search"></a>IRM 搜尋

受 IRM 保護的郵件因為已有編製索引，所以可以加以搜尋，包括標題、主旨、內文及附件。 使用者可以在 Outlook 和網頁型 outlook 中搜尋受 IRM 保護的專案，系統管理員可以使用 In-Place eDiscovery 或**Search-Mailbox** Cmdlet 搜尋受 irm 保護的專案。
  
### <a name="auditing"></a>稽核

Exchange Online Archiving提供兩種類型的內建稽核功能：
  
- **系統管理員稽核記錄功能** 系統管理員稽核記錄功能可讓客戶追蹤其系統管理員在 Exchange Online Archiving 環境中所做的變更，包括對 RBAC 角色或 Exchange 原則與設定的變更。 
    
- **信箱稽核記錄功能** 信箱稽核記錄功能可讓客戶追蹤信箱擁有者以外的使用者對信箱的存取情形。 
    
Several predefined audit reports are available in the Exchange admin center, including Administrator Role Changes, Litigation Hold, and Non-Owner Mailbox Access. Administrators can filter reports by date and role, and they can export all audit events for specified mailboxes in XML format for long-term retention or custom reporting.
  
Administrator audit logging is on by default, and mailbox audit logging is off by default. Administrators can use remote Windows PowerShell to enable mailbox audit logging for some or all mailboxes in their organization. For more information, see [Auditing Reports](https://go.microsoft.com/fwlink/p/?LinkId=314175).
  
## <a name="feature-availability"></a>功能可用性

若要查看不同計畫、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online 封存服務說明](exchange-online-archiving-service-description.md)。
  

