---
title: 郵件原則及合規性
ms.author: office365servicedesc
author: pamelaar
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-message-policy-recovery-and-compliance
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5c43c8eb-f8f7-4b5a-a743-b1dab7dc2fc8
ms.openlocfilehash: 5565085472d43230f9059e1dcac115105a2e20d5
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132697"
---
# <a name="message-policy-and-compliance"></a>郵件原則及合規性

## <a name="archiving-exchange-online-based-mailboxes"></a>封存 Exchange Online 式信箱

Exchange Online mailboxes reside in the cloud, and archiving them requires unique hosting environments. In some cases, Exchange Online can also be used to archive on-premises mailboxes in the cloud. The options for archiving with Exchange Online are described in this section.
  
Exchange Online 提供內建的封存功能來封存雲端式信箱，包括提供使用者方便的地方來儲存舊電子郵件訊息的「就地封存」。 In-Place 封存是一種特殊類型的信箱，它會出現在 Outlook 和網頁型 Outlook 中使用者的主要信箱資料夾旁。 使用者存取和搜尋封存的方式與存取和搜尋主要信箱相同。 可用的功能取決於使用的用戶端：
  
- **Outlook 2016、outlook 2013、outlook 2010 和 outlook 網頁**版使用者可以存取封存的完整功能，以及相關的合規性功能，例如控制保留和封存原則。 
    
- **Outlook 2007** Users have basic support for the In-Place Archive, but not all archiving and compliance features are available. For example, users cannot apply retention or archive policies to mailbox items and must rely on administrator-provisioned policies instead. 
    
系統管理員可使用 Exchange 系統管理中心或遠端 Windows PowerShell，針對特定使用者啟用個人封存功能。
  
如需詳細資訊，請參閱：
  
- [Exchange Online 中的封存信箱](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-archiving-service-description/archive-features)
    
- [在 Exchange Online 中啟用或停用封存信箱](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)
    
### <a name="archive-sizes"></a>封存大小

每個個人封存只能儲存一位使用者的郵件資料。 儲存空間的配置取決於訂閱計劃。 如需有關封存信箱大小的詳細資訊，請參閱[Exchange Online 限制](exchange-online-limits.md)中的「信箱儲存限制」一節。
  
> [!IMPORTANT]
> - 不允許使用日誌記錄、傳輸規則或自動轉寄規則將郵件複製到 Exchange Online 信箱以進行封存。 Microsoft 保留在信箱封存未使用於個人案例中或其他不適當用途的情況下，拒絕無限封存的權利。
> - In-Place Archive has specific licensing requirements for Outlook users. Outlook 2007 users must have the Office 2007 Cumulative Update for February 2011 to access the personal archive. 
> - Exchange Online 不支援 Exchange Server 2010 Service Pack 1 或更新版本的 Windows PowerShell 指令程式的_New-MailboxImportRequest_ Windows Cmdlet，以供系統管理員驅動的將 .pst 檔案匯入個人封存。 如果使用者在 Exchange Online 中同時有主要信箱和封存，則系統管理員可以使用 PST Capture 這項免費的工具，將 .pst 檔案資料匯入使用者的主要信箱或封存。

## <a name="cloud-based-archiving-of-on-premises-mailboxes"></a>雲端式封存內部部署信箱

Using Exchange Online for cloud-based archiving of on-premises Exchange Server 2010 or later mailboxes is possible with Microsoft Exchange Online Archiving, a hosted archiving solution from Microsoft. This requires that the on-premises organization be in Hybrid mode or be set up for Exchange Online Archiving.
  
> [!IMPORTANT]
> 若使用者在 Exchange 2010 信箱伺服器上有內部部署信箱，而且套用了受管理的資料夾原則，就無法啟用內部部署或雲端式就地封存功能。 
  
## <a name="retention-tags-and-retention-policies"></a>保留標記和保留原則

Exchange Online 提供保留原則，可協助組織減少電子郵件和其他通訊相關的責任。 透過這些原則，系統管理員可以將保留設定套用到使用者收件匣中的特定資料夾。 管理員也可以將保留原則的功能表提供給使用者，讓他們將原則套用至特定專案、交談或使用 Outlook 2010 或更新版本的資料夾或網頁上的 Outlook。
  
在 Exchange Online 中，系統管理員可以使用 Exchange 系統管理中心 (EAC) 或遠端 Windows PowerShell 來管理保留原則。
  
Exchange Online offers two types of policies: archive policies and delete policies. Both types can be combined on the same item or folder. For example, a user can tag an email message to be automatically moved to the In-Place Archive in a specified number of days and deleted after another span of days.
  
使用 Outlook 2010 或更新版本以及 Outlook 網頁版，使用者可以將保留原則套用至資料夾、交談或個別郵件。 他們也可以檢視套用的保留原則以及郵件的預定刪除日期。 其他電子郵件用戶端的使用者則只能根據系統管理員設定的伺服器端保留原則刪除或封存電子郵件訊息。
  
The retention policy capabilities offered in Exchange Online are the same as those offered in Exchange Server 2010 Service Pack 2 RU4. Administrators can use remote Windows PowerShell to migrate retention policies from on-premises Exchange Server 2010 or later environments to Exchange Online.
  
> [!IMPORTANT]
> Exchange Online 不提供「受管理的資料夾」，這是 Exchange Server 2007 所引進的功能，為早期郵件記錄管理方法。 
  
如需詳細資訊，請參閱〈[保留標記和保留原則](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/retention-tags-and-policies)〉。
  
## <a name="encryption-of-data-at-rest"></a>靜態資料的加密

靜態客戶資料的加密是由多種服務端技術所提供，包括 BitLocker、DKM、Azure 儲存服務加密，以及 Exchange Online 中的服務加密、商務用 Skype、商務 OneDrive，以及 SharePoint 線上。 Office 365 服務加密包含一個選項，可使用儲存在 Azure Key Vault 中客戶管理的加密金鑰。 此客戶管理的金鑰選項（稱為「[客戶金鑰](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key?redirectSourcePath=%252fen-us%252farticle%252fControlling-your-data-in-Office-365-using-Customer-Key-f2cd475a-e592-46cf-80a3-1bfb0fa17697)」）適用于 Exchange Online、SharePoint Online 和商務 OneDrive。 
  
### <a name="bitlocker"></a>BitLocker

Microsoft 伺服器使用 BitLocker，將包含客戶資料的磁片磁碟機加密在磁片區層級。 BitLocker 加密是 Windows 內建的資料保護功能。 BitLocker 是用來保護威脅的技術之一，以防其他程式或控制措施（例如，對硬體的存取控制或回收）發生不足時，可能會導致某些人能夠實際存取包含客戶資料的磁片。 在此情況下，BitLocker 會因遺失、被竊或無法正確解除委任的電腦和磁片，避免資料竊取或洩密的可能性。 
  
### <a name="distributed-key-manager"></a>分散式金鑰管理員

除了 BitLocker 之外，我們還使用稱為「分散式金鑰管理員」（DKM）的技術。 DKM 是一種用戶端功能，使用一組機密金鑰來加密及解密資訊。 只有 Active Directory 網域服務中特定安全性群組的成員可以存取這些機碼，以解密由 DKM 所加密的資料。 在 Exchange Online 中，只有在執行 Exchange 程式的特定服務帳戶才屬於該安全性群組。 在資料中心的標準作業程式中，未被任何人提供此安全性群組的一部分認證，因此沒有人員可以存取可將這些機密解密的金鑰。
  
## <a name="customer-key"></a>客戶金鑰

使用客戶金鑰，您可以控制組織的加密金鑰，然後進行設定，以在 Microsoft 資料中心內加密靜態資料。 存放的資料包括 Exchange Online 資料和儲存在信箱的商務用 Skype 資料，以及儲存在 SharePoint Online 中和商務用 OneDrive 中的檔案。 如需詳細資訊，請參閱[使用客戶金鑰](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key)和[服務加密以客戶重要的常見問題解答](https://docs.microsoft.com/office365/securitycompliance/service-encryption-with-customer-key-faq)來控制您的資料。
  
## <a name="office-365-message-encryption"></a>Office 365 郵件加密

Office 365 郵件加密可讓電子郵件使用者將加密的電子郵件傳送給任何人。 我們宣佈 Office 郵件加密中的新功能，利用 Azure 資訊加密中的保護功能。 這些新功能提供增強的使用者體驗，可讓您輕鬆地與組織內外的任何人共用及共同處理受保護的郵件。 新的 Office 郵件加密功能具有一些設定需求。 請參閱設定以 Azure 資訊保護為基礎的新 Office 365 郵件加密功能。 舊版 Office 365 郵件加密的客戶不會取得上述新功能，而不需遵循以上所提供的指導方針。 如需詳細資訊，請參閱[常見問題解答](https://support.office.com/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e)以取得新的 vs 舊版本 Office 365 郵件加密功能。 

Office 365 Advanced Message Encryption 允許郵件到期和吊銷，提供額外的保護。  您也可以建立多個範本，以用於來自組織的加密電子郵件。  Advanced Message Encryption 包含在 Microsoft 365 E5、Office 365 E5、Microsoft 365 E5 （非盈利性人員定價）、Office 365 企業版 E5 （非盈利性員工定價）或 Office 365 教育版 A5 中。 如果您的組織有未加入 Office 365 Advanced Message Encryption 的訂閱，您可以購買 Microsoft 365 E5 規範或 Office 365 Advanced 合規性 SKU 做為附加元件。

## <a name="securemultipurpose-internet-mail-extensions-smime"></a>Secure/Multipurpose Internet Mail Extensions (S/MIME)

S/MIME allows you to help protect sensitive information by sending signed and encrypted email within your organization. Administrators can use remote Windows PowerShell to set up S/MIME after establishing and issuing PKI certificates to users. These certificates must be synchronized from an on-premises Active Directory Certificate Service.
  
Microsoft Edge 和 Internet Explorer 11 支援 S/MIME。 目前，Firefox、Opera 和 Chrome 不支援 S/MIME。 如需詳細資訊，請參閱〈[適用於訊息簽署和加密的 S/MIME](https://docs.microsoft.com/Exchange/policy-and-compliance/smime?view=exchserver-2019)〉。
  
## <a name="in-place-hold-and-litigation-hold"></a>就地保留與訴訟暫止

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
  
如需詳細資訊，請參閱[原有範圍暫止](https://docs.microsoft.com/exchange/security-and-compliance/in-place-and-litigation-holds)。
  
## <a name="in-place-ediscovery"></a>就地 eDiscovery

Exchange Online 可讓客戶使用網頁型介面搜尋整個組織中的信箱內容。 具有就地 eDiscovery 搜尋執行授權 (透過指派) 的系統管理員或法規遵循和安全性職員可搜尋電子郵件訊息、附件、行事曆約會、工作、連絡人及其他項目。 就地 eDiscovery 可以同時搜尋主要信箱和封存。 功能齊備的篩選功能包括寄件者、收件者、訊息類型、傳送/接收日期和副本/密件副本，另外還包括 KQL 語法。 搜尋結果將同時包含 [刪除的郵件] 資料夾中符合搜尋查詢的項目。
  
Results of In-Place eDiscovery searches can be previewed in the web-based interface, exported to a PST file or copied to a special type of mailbox called a Discovery mailbox. A Discovery mailbox has a 50 GB quota for storing search results. Administrators can also connect Outlook to the Discovery mailbox to access search results, and export the search results to a .pst file.
  
Administrators use either the Exchange admin center or remote Windows PowerShell to perform multi-mailbox searches. The Exchange admin center can provide a read-only preview of the search results, enabling administrators to quickly verify a search and rerun it, if needed, with different parameters. Once a search is optimized, the administrator can copy the results to the Discovery mailbox.
  
By default, one Discovery mailbox is created for each organization, but administrators can create additional Discovery mailboxes using remote Windows PowerShell. Discovery mailboxes cannot be used for any purpose other than storing In-Place eDiscovery search results.
  
Administrators use either the Exchange admin center or remote Windows PowerShell to perform In-Place eDiscovery searches. The Exchange admin center can provide a read-only preview of the search results, enabling administrators to quickly verify a search and rerun it, if needed, with different parameters. Once a search is optimized, the administrator can copy the results to the Discovery mailbox or export search results to a PST file.
  
系統管理員可以使用 Exchange 系統管理中心或遠端 Windows PowerShell，最多在就地 eDiscovery 搜尋中同時搜尋 10,000 個信箱。 
  
在 Exchange Online 中，已授權使用者能執行就地 eDiscovery 並選擇下列其中一個動作：
  
- **預估搜尋結果**預估搜尋將傳回的郵件數，包括關鍵字統計資料，可確定用於搜尋的關鍵字效率，並依需求調整搜尋參數。 
    
- **預覽搜尋結果**
    
- 複製搜尋結果所傳回的郵件到探索信箱。
    
如需詳細資訊，請參閱[就地 eDiscovery](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery)。
  
## <a name="mail-flow-rules"></a>郵件流程規則

您可以使用郵件流程規則，針對透過您的組織並採取行動的郵件尋找特定條件。 郵件流程規則可讓您將郵件原則套用至電子郵件訊息、安全訊息、保護郵件系統，並避免資訊洩露。
  
Many organizations today are required by law, regulatory requirements, or company policies to apply messaging policies that limit the interaction between recipients and senders, both inside and outside the organization. In addition to limiting interactions among individuals, departmental groups inside the organization, and entities outside the organization, some organizations are also subject to the following messaging policy requirements:
  
- 防止不適當的內容進入或流出組織
    
- 篩選機密的組織資訊
    
- 追蹤或複製已傳送至特定個人或從特定個人接收到的郵件
    
- 在傳遞之前重新導向輸入及輸出郵件以進行檢查
    
- 在郵件通過組織時套用免責聲明至其中
    
> [!IMPORTANT]
> 需要在電子郵件伺服器（例如 Adobe）上安裝協力廠商 Ifilter 的附件檔案類型，在安裝適當的 iFilter 之前，無法使用郵件流程規則加以檢查。 如需郵件流程規則支援之檔案類型的相關資訊，請參閱[使用郵件流程規則檢查 Office 365 中的郵件附件](https://docs.microsoft.com/exchange/security-and-compliance/mail-flow-rules/inspect-message-attachments)。
  
如需郵件流程規則的相關資訊，請參閱[mail flow rules In Exchange 2016](https://docs.microsoft.com/Exchange/policy-and-compliance/mail-flow-rules/mail-flow-rules?view=exchserver-2019)。
  
## <a name="data-loss-prevention"></a>資料遺失防護

資料遺失防護 (DLP) 功能可透過深入內容分析，協助您識別、監視和保護組織的敏感資訊。 DLP 是對於企業郵件系統越來越重要的一項高階功能，因為業務關鍵電子郵件包含需要受到保護的敏感資料。 Exchange Online 中的 DLP 功能可讓您保護機密資料，而不會影響工作者的生產力。
  
您可以在 Exchange 系統管理中心 (EAC) 管理介面中設定 DLP 原則，以便： 
  
- 開始使用預先設定的原則範本，協助您偵測特定的敏感資訊類型，例如 PCI-DSS 資料、Gramm-Leach-Bliley 金融服務業現代化法案資料，或甚至是特定地區設定的個人識別資訊 (PII)。
    
- 運用現有傳輸規則準則和動作的完整功能，並新增傳輸規則。
    
- 在完整執行 DLP 原則之前先測試其有效性。
    
- 加入您自己的自訂 DLP 原則範本和敏感資訊類型。
    
- 偵測郵件附件、本文或主旨行中的敏感資訊，並調整 Exchange Online 作用的信賴等級。
    
- Detect sensitive form data by using Document Fingerprinting. Document Fingerprinting helps you easily create custom sensitive information types based on text-based forms that you can use to define transport rules and DLP policies.
    
- 新增原則提示，可將通知顯示在 Outlook 2016、Outlook 2013、Outlook 網頁版和使用者的 OWA，以協助減少資料遺失，也可以允許誤報，以提升原則的效能。 
    
- 檢閱 DLP 報告中的事件資料，或使用產生事件報告動作來新增您自己的特定報告。
    
如需有關 DLP 的詳細資訊，請參閱〈[資料遺失防護](https://docs.microsoft.com/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention)〉。
  
## <a name="journaling"></a>日誌

You can configure Exchange Online to journal copies of emails to any external mailbox that can receive messages via SMTP. Journaling can help your organization respond to legal, regulatory, and organizational compliance requirements by recording inbound and outbound email communications. When planning for messaging retention and compliance, it's important to understand journaling and how it fits in with your organization's compliance policies.
  
You can manage journal rules by using the Exchange admin center or remote Windows PowerShell. You can configure journaling on a per-user and per-distribution list basis, and choose to journal only internal messages, only external messages, or both. Journaled messages include not only the original message but also information about the sender, recipients, copies, and blind copies.
  
為了確保成功且可靠的日誌記錄解決方案，您必須完成下列工作：
  
- 請確定日誌記錄目的地不是 Exchange Online 信箱。
    
- 在客戶目錄中針對 SMTP 目標電子郵件地址建立連絡人物件，以用於日誌記錄。
    
- 建立第二個連絡人物件作為備用日誌信箱，以便在無法使用主要日誌信箱時擷取任何日誌報告。
    
- 維護 SMTP 目標的適當管理、冗余、可用性、效能和功能等級，以確保永遠能夠成功接受郵件。
    
- 在 Exchange Server 和 Exchange 傳輸之間提供適當的互通性，包括郵件格式、寄件者/收件者資訊整合以及適當的內容轉換。
    
如需有關日誌記錄的詳細資訊，請參閱〈[日誌記錄](https://docs.microsoft.com/exchange/security-and-compliance/journaling/journaling)〉。
  
## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online 服務說明](exchange-online-service-description.md)。
  

