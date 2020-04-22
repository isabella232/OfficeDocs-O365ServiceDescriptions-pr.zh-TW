---
title: Exchange Online 封存中的合規性和安全性功能
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- compliance-and-security-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7482322a-39fe-4a99-b29c-63cb1bc3cf1f
ms.openlocfilehash: b977fea67c28a660a7468945c76d19677769cd8f
ms.sourcegitcommit: 7a68dc894dde0d06fab014c56914a78aa8cda847
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/21/2020
ms.locfileid: "43638691"
---
# <a name="compliance-and-security-features-in-exchange-online-archiving"></a><span data-ttu-id="0d9b7-102">Exchange Online 封存中的合規性和安全性功能</span><span class="sxs-lookup"><span data-stu-id="0d9b7-102">Compliance and security features in Exchange Online Archiving</span></span>

## <a name="compliance-features-in-exchange-online-archiving"></a><span data-ttu-id="0d9b7-103">Exchange Online 封存中的符合性功能</span><span class="sxs-lookup"><span data-stu-id="0d9b7-103">Compliance features in Exchange Online Archiving</span></span>

<span data-ttu-id="0d9b7-104">下列幾節說明 Microsoft Exchange Online Archiving 的符合性功能。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-104">The following sections describe the compliance features of Microsoft Exchange Online Archiving.</span></span>
  
### <a name="retention-policies"></a><span data-ttu-id="0d9b7-105">保留原則</span><span class="sxs-lookup"><span data-stu-id="0d9b7-105">Retention policies</span></span>

<span data-ttu-id="0d9b7-106">Exchange Online Archiving 提供保留原則，可協助組織減少電子郵件與其他通訊的相關責任。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-106">Exchange Online Archiving offers retention policies to help organizations reduce the liabilities associated with email and other communications.</span></span> <span data-ttu-id="0d9b7-107">透過這些原則，系統管理員可以將保留設定套用到使用者收件匣中的特定資料夾。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-107">With these policies, administrators can apply retention settings to specific folders in users' inboxes.</span></span> <span data-ttu-id="0d9b7-108">管理員也可以將保留原則的功能表提供給使用者，讓他們將原則套用至特定專案、交談或使用 Outlook 2010 或更新版本的資料夾或網頁上的 Outlook。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-108">Administrators can also give users a menu of retention policies and let them apply the policies to specific items, conversations, or folders using Outlook 2010 or later or Outlook on the web.</span></span> <span data-ttu-id="0d9b7-109">在 Exchange Online Archiving 中，系統管理員會從內部部署基礎結構來管理保留原則。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-109">In Exchange Online Archiving, administrators manage retention policies from the on-premises infrastructure.</span></span>
  
<span data-ttu-id="0d9b7-p102">Exchange Online Archiving 提供兩種類型的原則：封存原則和刪除原則。您可以在同一個項目或資料夾上同時套用這兩種類型。例如，使用者可以標記電子郵件，使其在指定天數後自動移至個人封存，並在又過了指定天數後刪除。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-p102">Exchange Online Archiving offers two types of policies: archive and delete. Both types can be applied to the same item or folder. For example, a user can tag an email message so that it is automatically moved to the personal archive in a specified number of days and deleted after another span of days.</span></span>
  
<span data-ttu-id="0d9b7-113">使用 Outlook 2010 和更新版本和 Outlook 網頁版，使用者可以將保留原則套用至資料夾、交談或個別郵件，也可以在郵件上查看套用的保留原則和預期刪除日期。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-113">With Outlook 2010 and later and Outlook on the web, users can apply retention policies to folders, conversations, or individual messages and can also view the applied retention policies and expected deletion dates on messages.</span></span> <span data-ttu-id="0d9b7-114">其他電子郵件用戶端的使用者可根據系統管理員所佈建的伺服器端保留原則來刪除或封存電子郵件，但是沒有相同程度的檢視和控制能力。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-114">Users of other email clients can have email deleted or archived based on server-side retention policies provisioned by the administrator, but they do not have the same level of visibility and control.</span></span>
  
<span data-ttu-id="0d9b7-p104">Exchange Online Archiving 提供的保留原則功能與 Exchange Server 2010 Service Pack 2 (SP2) 及更新版本所提供的相同。系統管理員可以從內部部署 Exchange Server 2010 及更新版本的環境管理保留原則。受管理的資料夾是 Exchange 2007 中引進的舊式郵件記錄管理方法，無法在 Exchange Online 封存中使用且不相容。如需詳細資訊，請參閱[保留標記和保留原則](https://go.microsoft.com/fwlink/p/?LinkID=314153)。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-p104">The retention policy capabilities offered in Exchange Online Archiving are the same as those offered in Exchange Server 2010 Service Pack 2 (SP2) and later. Administrators can manage retention policies from on-premises Exchange Server 2010 and later environments. Managed Folders, an older approach to messaging records management that was introduced in Exchange 2007, are not available in and not compatible with Exchange Online Archiving. For more details, see [Retention Tags and Retention Policies](https://go.microsoft.com/fwlink/p/?LinkID=314153).</span></span>
  
### <a name="in-place-hold-and-litigation-hold"></a><span data-ttu-id="0d9b7-119">就地保留與訴訟暫止</span><span class="sxs-lookup"><span data-stu-id="0d9b7-119">In-Place Hold and Litigation Hold</span></span>

<span data-ttu-id="0d9b7-p105">如果合理預期到訴訟的可能性，組織就需要保留與案件相關的電子儲存資訊 (ESI)，包括電子郵件。此預期心理會在了解案件的特定資料之前出現，而且需要保留的資料範圍通常很廣。組織可以保留所有與特定主題相關的電子郵件，或是有關特定個人的所有電子郵件。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-p105">When a reasonable expectation of litigation exists, organizations are required to preserve electronically stored information (ESI), including email that's relevant to the case. This expectation can occur before the specifics of the case are known, and preservation is often broad. Organizations may preserve all email related to a specific topic, or all email for certain individuals.</span></span>
  
<span data-ttu-id="0d9b7-123">在 Exchange Online 中，您可以使用就地保留或訴訟資料暫留功能來達成下列目標：</span><span class="sxs-lookup"><span data-stu-id="0d9b7-123">In Exchange Online, you can use In-Place Hold or Litigation Hold to accomplish the following goals:</span></span>
  
- <span data-ttu-id="0d9b7-124">暫停使用者使用信箱，並永久保留信箱項目</span><span class="sxs-lookup"><span data-stu-id="0d9b7-124">Enable users to be placed on hold and preserve mailbox items immutably</span></span>
    
- <span data-ttu-id="0d9b7-125">保留由使用者或自動刪除程序 (例如 MRM) 刪除的信箱項目</span><span class="sxs-lookup"><span data-stu-id="0d9b7-125">Preserve mailbox items deleted by users or automatic deletion processes such as MRM</span></span>
    
- <span data-ttu-id="0d9b7-126">儲存原始郵件的複本，以防信箱郵件遭到竄改、被使用者變更或自動處理</span><span class="sxs-lookup"><span data-stu-id="0d9b7-126">Protect mailbox items from tampering, changes by a user, or automatic processes by saving a copy of the original item</span></span>
    
- <span data-ttu-id="0d9b7-127">無限期或於指定期間內保留項目</span><span class="sxs-lookup"><span data-stu-id="0d9b7-127">Preserve items indefinitely or for a specific duration</span></span>
    
- <span data-ttu-id="0d9b7-128">無需暫停 MRM，讓使用者不會察覺到被保留</span><span class="sxs-lookup"><span data-stu-id="0d9b7-128">Keep holds transparent from the user by not having to suspend MRM</span></span>
    
- <span data-ttu-id="0d9b7-129">使用就地保留 eDiscovery 來搜尋信箱郵件，包括被保留的郵件</span><span class="sxs-lookup"><span data-stu-id="0d9b7-129">Use In-Place eDiscovery to search mailbox items, including items placed on hold</span></span>
    
<span data-ttu-id="0d9b7-130">此外，您還可以使用就地保留來：</span><span class="sxs-lookup"><span data-stu-id="0d9b7-130">Additionally, you can use In-Place Hold to:</span></span>
  
- <span data-ttu-id="0d9b7-131">搜尋並保留符合指定條件的郵件</span><span class="sxs-lookup"><span data-stu-id="0d9b7-131">Search and hold items matching specified criteria</span></span>
    
- <span data-ttu-id="0d9b7-132">針對不同案件或調查，將使用者進行多項就地保留</span><span class="sxs-lookup"><span data-stu-id="0d9b7-132">Place a user on multiple In-Place Holds for different cases or investigations</span></span>
    
> [!NOTE]
> <span data-ttu-id="0d9b7-133">當您對信箱進行就地保留或訴訟資料暫留時，會同時保留主要和封存信箱。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-133">When you put a mailbox on In-Place Hold or Litigation Hold, the hold is placed on both the primary and the archive mailbox.</span></span> 
  
<span data-ttu-id="0d9b7-134">如需詳細資訊，請參閱[原有範圍暫止](https://go.microsoft.com/fwlink/p/?LinkId=271746)。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-134">For more information, see [In-Place Hold and Litigation Hold](https://go.microsoft.com/fwlink/p/?LinkId=271746).</span></span>
  
> [!NOTE]
> <span data-ttu-id="0d9b7-135">對於 Exchange Online Archiving使用者而言，[可復原的項目] 資料夾的預設配額為 100 GB。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-135">The default quota for the Recoverable Items Folder is 100 GB for Exchange Online Archiving users.</span></span> 
  
### <a name="in-place-ediscovery"></a><span data-ttu-id="0d9b7-136">就地 eDiscovery</span><span class="sxs-lookup"><span data-stu-id="0d9b7-136">In-Place eDiscovery</span></span>

<span data-ttu-id="0d9b7-p106">Exchange Online Archiving 支援就地 eDiscovery，可供搜尋組織中的信箱內容。系統管理員或經過授權的 Discovery 管理員可以從內部部署 Exchange 2013 伺服器，使用 Exchange 系統管理中心或遠端 Windows PowerShell 來搜尋各種信箱項目，包括電子郵件、附件、行事曆約會、工作及連絡人。就地 eDiscovery 可以同時搜尋主要信箱和封存。功能齊備的篩選功能包括寄件者、收件者、郵件類型、傳送日期、接收日期、副本及密件副本，另外還包括關鍵字查詢語法 (KQL) 語法。如需詳細資訊，請參閱[就地 eDiscovery](https://go.microsoft.com/fwlink/p/?LinkId=314169)。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-p106">Exchange Online Archiving supports In-Place eDiscovery for searching the contents of mailboxes in an organization. Using the Exchange admin center or remote Windows PowerShell from an on-premises Exchange 2013 server, administrators or authorized Discovery managers can search a variety of mailbox items - including email messages, attachments, calendar appointments, tasks, and contacts. In-Place eDiscovery can search simultaneously across primary mailboxes and archives. Rich filtering capabilities include sender, receiver, message types, sent date, received date, carbon copy, and blind carbon copy, along with Keyword Query Language (KQL) syntax. For more details, see [In-Place eDiscovery](https://go.microsoft.com/fwlink/p/?LinkId=314169).</span></span>
  
<span data-ttu-id="0d9b7-p107">Exchange 系統管理中心或遠端 Windows PowerShell 一次最多可以在就地 eDiscovery 搜尋中搜尋 5,000 個信箱。如需使用遠端 Windows PowerShell 執行就地 eDiscovery 搜尋的詳細資料，請參閱 [New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170)。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-p107">The Exchange admin center and remote Windows PowerShell can be used to search up to 5,000 mailboxes at a time in an In-Place eDiscovery search. For details about using remote Windows PowerShell to run In-Place eDiscovery searches, see [New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170).</span></span> 
  
> [!NOTE]
> <span data-ttu-id="0d9b7-p108">在遠端 Windows PowerShell 中， `Search-Mailbox` Cmdlet 可以用來搜尋 5,000 個以上的信箱。如需使用遠端 Windows PowerShell 搜尋大量信箱的詳細資訊，請參閱 [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171)。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-p108">In remote Windows PowerShell, the  `Search-Mailbox` cmdlet can be used to search more than 5,000 mailboxes. For details about searching large numbers of mailboxes using remote Windows PowerShell, see [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171).</span></span> 
  
<span data-ttu-id="0d9b7-p109">就地 eDiscovery 搜尋的結果可在 Exchange 系統管理中心預覽、匯出為 .pst 檔案，或複製到名為探索信箱的特殊信箱中。系統管理員或符合性專員可以連到探索信箱來檢閱郵件。如需詳細資訊，請參閱[建立就地 eDiscovery 搜尋](https://go.microsoft.com/fwlink/p/?LinkId=314172)。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-p109">Results of an In-Place eDiscovery search can be previewed in the Exchange admin center, exported to a .pst file, or copied to a special type of mailbox, called a discovery mailbox. Administrators or compliance officers can connect to the discovery mailbox to review messages. For details, see [Create an In-Place eDiscovery Search](https://go.microsoft.com/fwlink/p/?LinkId=314172).</span></span>
  
> [!NOTE]
> <span data-ttu-id="0d9b7-p110">複製跨內部部署與雲端信箱或封存來執行之就地 eDiscovery 搜尋的搜尋結果時，您必須選取內部部署的探索信箱。內部部署主要信箱和雲端封存中的郵件會複製到內部部署的探索信箱。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-p110">When copying search results for an In-Place eDiscovery search performed across on-premises and cloud-based mailboxes or archives, you must select an on-premises discovery mailbox. Messages from the on-premises primary mailbox and the cloud-based archive are copied to the on-premises discovery mailbox.</span></span> 
  
<span data-ttu-id="0d9b7-p111">系統管理員也可以搜尋並刪除寄送到整個組織中之多個信箱的不當電子郵件。例如，如果不小心將機密薪資資訊寄給所有員工，系統管理員就可以從使用者的信箱刪除電子郵件。此類型的搜尋不適用於 Exchange 系統管理中心。它必須使用遠端 PowerShell 執行。如需如何從使用者的信箱刪除郵件的詳細資訊，請參閱[搜尋並刪除郵件](https://go.microsoft.com/fwlink/p/?LinkId=314173)。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-p111">Administrators can also search for and delete inappropriate email messages sent to multiple mailboxes across their organizations. For example, if confidential salary information was accidentally sent to all employees, an administrator can delete the email from the users' mailboxes. This type of search is not available in the Exchange admin center. It must be performed using Remote PowerShell. For details on how to delete messages from users' mailboxes, see [Search and Delete Messages](https://go.microsoft.com/fwlink/p/?LinkId=314173).</span></span>
  
## <a name="security-features-in-exchange-online-archiving"></a><span data-ttu-id="0d9b7-156">Exchange Online 封存中的安全性功能</span><span class="sxs-lookup"><span data-stu-id="0d9b7-156">Security features in Exchange Online Archiving</span></span>

<span data-ttu-id="0d9b7-157">下列幾節說明 Microsoft Exchange Online Archiving 的安全性功能。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-157">The following sections describe the security features of Microsoft Exchange Online Archiving.</span></span>
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a><span data-ttu-id="0d9b7-158">內部部署伺服器與 Exchange Online 封存之間的加密</span><span class="sxs-lookup"><span data-stu-id="0d9b7-158">Encryption between on-premises servers and Exchange Online Archiving</span></span>

<span data-ttu-id="0d9b7-159">TLS 用來加密電子郵件伺服器之間的連線，以防止詐騙並為傳輸中的郵件添加機密性。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-159">TLS is used to encrypt the connection between email servers to help prevent spoofing and provide confidentiality for messages in transit.</span></span> <span data-ttu-id="0d9b7-160">TLS 也可用來保護內部部署郵件伺服器流量，以進行 Exchange Online 封存的 Microsoft 資料中心。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-160">TLS is also used for securing on-premises mail server traffic to Microsoft datacenters for Exchange Online Archiving.</span></span>
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a><span data-ttu-id="0d9b7-161">用戶端與 Exchange Online 封存之間的加密</span><span class="sxs-lookup"><span data-stu-id="0d9b7-161">Encrypting between clients and Exchange Online Archiving</span></span>

<span data-ttu-id="0d9b7-162">與 Exchange Online Archiving的用戶端連線使用下列加密方法來加強安全性：</span><span class="sxs-lookup"><span data-stu-id="0d9b7-162">Client connections to Exchange Online Archiving use the following encryption methods to enhance security:</span></span>
  
- <span data-ttu-id="0d9b7-163">SSL 是用來保護 Outlook、Outlook 網頁版和 Exchange Web 服務流量，使用 TCP 埠443。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-163">SSL is used for securing Outlook, Outlook on the web, and Exchange Web Services traffic, using TCP port 443.</span></span>
    
- <span data-ttu-id="0d9b7-164">與內部部署伺服器的用戶端連線不會因為 Exchange Online Archiving的出現而改變。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-164">Client connections to on-premises servers do not change with the introduction of Exchange Online Archiving.</span></span>
    
### <a name="encryption-smime-and-pgp"></a><span data-ttu-id="0d9b7-165">加密：S/MIME 和 PGP</span><span class="sxs-lookup"><span data-stu-id="0d9b7-165">Encryption: S/MIME and PGP</span></span>

<span data-ttu-id="0d9b7-p113">Exchange Online Archiving 會儲存安全多用途網際網路郵件延伸 (S/MIME) 郵件。不過，Exchange Online Archiving不會裝載 S/MIME 功能或公開金鑰，也不會提供金鑰存放庫、金鑰管理或金鑰目錄服務，因為這些服務全都會附加至內部部署 Exchange 基礎結構。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-p113">Exchange Online Archiving will store Secure/Multipurpose Internet Mail Extensions (S/MIME) messages. However, Exchange Online Archiving does not host S/MIME functions or host the public keys, nor does it provide key repository, key management, or key directory services because all of these services attach to the on-premises Exchange infrastructure.</span></span>
  
<span data-ttu-id="0d9b7-168">同樣地，Exchange Online Archiving會儲存使用用戶端、協力廠商加密解決方案 (如 Pretty Good Privacy (PGP)) 加密的郵件。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-168">Similarly, Exchange Online Archiving will store messages that are encrypted using client-side, third-party encryption solutions such as Pretty Good Privacy (PGP).</span></span>
  
### <a name="information-rights-management"></a><span data-ttu-id="0d9b7-169">資訊版權管理</span><span class="sxs-lookup"><span data-stu-id="0d9b7-169">Information Rights Management</span></span>

<span data-ttu-id="0d9b7-p114">Exchange Online Archiving不提供託管的資訊版權管理 (IRM) 服務，但管理員可以使用內部部署的 Active Directory 版權管理服務 (AD RMS)。若部署了 AD RMS 伺服器，則 Outlook 可以直接與該伺服器通訊，讓使用者能夠撰寫和讀取受到 IRM 保護的郵件。若設定了 AD RMS 伺服器與內部部署 Exchange 環境之間的交互操作性，則使用者可以撰寫和讀取受到 IRM 保護的郵件。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-p114">Exchange Online Archiving does not provide hosted Information Rights Management (IRM) services, but administrators can use on-premises Active Directory Rights Management Services (AD RMS). If an AD RMS server is deployed, Outlook can communicate directly with that server, enabling users to compose and read IRM-protected messages. If interoperability between the AD RMS server and the on-premises Exchange environment is configured, users will be able to compose and read IRM-protected messages.</span></span>
  
#### <a name="support-for-irm-in-outlook-on-the-web"></a><span data-ttu-id="0d9b7-173">在 web 上的 Outlook 中支援 IRM</span><span class="sxs-lookup"><span data-stu-id="0d9b7-173">Support for IRM in Outlook on the web</span></span>

<span data-ttu-id="0d9b7-174">使用者可以在網頁型 Outlook 中以本機方式閱讀和建立受 IRM 保護的郵件，就像在 Outlook 中一樣。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-174">Users can read and create IRM-protected messages natively in Outlook on the web, just as they can in Outlook.</span></span> <span data-ttu-id="0d9b7-175">您可以透過 Internet Explorer、Firefox、Safari 和 Chrome （不需要外掛程式）來存取網頁上的受 IRM 保護的郵件。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-175">IRM-protected messages in Outlook on the web can be accessed through Internet Explorer, Firefox, Safari, and Chrome (with no plug-in required).</span></span> <span data-ttu-id="0d9b7-176">這些郵件包含全文檢索搜尋、交談檢視和預覽窗格。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-176">The messages include full-text search, conversation view, and the preview pane.</span></span> <span data-ttu-id="0d9b7-177">必須設定 Active Directory Rights Management Services 伺服器與內部部署 Exchange 環境之間的交互操作性，才能啟用此功能。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-177">Interoperability between the Active Directory Rights Management Services server and the on-premises Exchange environment must be configured to enable this.</span></span>
  
#### <a name="irm-search"></a><span data-ttu-id="0d9b7-178">IRM 搜尋</span><span class="sxs-lookup"><span data-stu-id="0d9b7-178">IRM search</span></span>

<span data-ttu-id="0d9b7-179">受 IRM 保護的郵件因為已有編製索引，所以可以加以搜尋，包括標題、主旨、內文及附件。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-179">IRM-protected messages are indexed and searchable, including headers, subject, body, and attachments.</span></span> <span data-ttu-id="0d9b7-180">使用者可以在 Outlook 和網頁型 outlook 中搜尋受 IRM 保護的專案，系統管理員可以使用 In-Place eDiscovery 或**Search-Mailbox** Cmdlet 搜尋受 irm 保護的專案。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-180">Users can search IRM-protected items in Outlook and Outlook on the web, and administrators can search IRM-protected items by using In-Place eDiscovery or the **Search-Mailbox** cmdlet.</span></span>
  
### <a name="auditing"></a><span data-ttu-id="0d9b7-181">稽核</span><span class="sxs-lookup"><span data-stu-id="0d9b7-181">Auditing</span></span>

<span data-ttu-id="0d9b7-182">Exchange Online Archiving提供兩種類型的內建稽核功能：</span><span class="sxs-lookup"><span data-stu-id="0d9b7-182">Exchange Online Archiving provides two types of built-in auditing capabilities:</span></span>
  
- <span data-ttu-id="0d9b7-183">**系統管理員稽核記錄功能** 系統管理員稽核記錄功能可讓客戶追蹤其系統管理員在 Exchange Online Archiving 環境中所做的變更，包括對 RBAC 角色或 Exchange 原則與設定的變更。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-183">**Administrator audit logging** Administrator audit logging allows customers to track changes made by their administrators in the Exchange Online Archiving environment, including changes to RBAC roles or Exchange policies and settings.</span></span> 
    
- <span data-ttu-id="0d9b7-184">**信箱稽核記錄功能** 信箱稽核記錄功能可讓客戶追蹤信箱擁有者以外的使用者對信箱的存取情形。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-184">**Mailbox audit logging** Mailbox audit logging allows customers to track access to mailboxes by users other than the mailbox owner.</span></span> 
    
<span data-ttu-id="0d9b7-p117">Exchange 系統管理中心提供多份預先定義的稽核報告，包括系統管理員角色變更、訴訟資料暫留，以及非擁有者信箱存取。系統管理員可依日期與角色篩選報告，也可基於長期保留或自訂報告等目的，使用 XML 格式匯出指定信箱的所有稽核事件。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-p117">Several predefined audit reports are available in the Exchange admin center, including Administrator Role Changes, Litigation Hold, and Non-Owner Mailbox Access. Administrators can filter reports by date and role, and they can export all audit events for specified mailboxes in XML format for long-term retention or custom reporting.</span></span>
  
<span data-ttu-id="0d9b7-p118">系統管理員稽核記錄功能預設會開啟，但信箱稽核記錄功能預設會關閉。系統管理員可以使用遠端 Windows PowerShell 來啟用組織中部分或全部信箱的信箱稽核記錄功能。如需詳細資訊，請參閱[稽核報告](https://go.microsoft.com/fwlink/p/?LinkId=314175)。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-p118">Administrator audit logging is on by default, and mailbox audit logging is off by default. Administrators can use remote Windows PowerShell to enable mailbox audit logging for some or all mailboxes in their organization. For more information, see [Auditing Reports](https://go.microsoft.com/fwlink/p/?LinkId=314175).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="0d9b7-190">功能可用性</span><span class="sxs-lookup"><span data-stu-id="0d9b7-190">Feature availability</span></span>

<span data-ttu-id="0d9b7-191">若要查看不同計畫、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online 封存服務說明](exchange-online-archiving-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="0d9b7-191">To view feature availability across plans, standalone options, and on-premise solutions, see [Exchange Online Archiving service description](exchange-online-archiving-service-description.md).</span></span>
  

