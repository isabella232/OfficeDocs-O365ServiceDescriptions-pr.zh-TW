---
title: 郵件原則及合規性
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-message-policy-recovery-and-compliance
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5c43c8eb-f8f7-4b5a-a743-b1dab7dc2fc8
description: 深入瞭解 Exchange Online 中的郵件原則和符合性。
ms.openlocfilehash: 22de08fb350785b63db97da7271182eb62980cae
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652707"
---
# <a name="message-policy-and-compliance"></a>郵件原則及合規性

## <a name="archiving-exchange-online-based-mailboxes"></a>封存 Exchange Online 式信箱

Exchange Online 信箱位於雲端，封存這些信箱需要獨特的主控環境。在某些情況下，Exchange Online 也可用來封存雲端中的內部部署信箱。本節將說明使用 Exchange Online 封存的選項。
  
Exchange Online 提供內建的封存功能來封存雲端式信箱，包括提供使用者方便的地方來儲存舊電子郵件訊息的「就地封存」。 In-Place 封存是一種特殊類型的信箱，它會出現在 Outlook 和網頁型 Outlook 中使用者的主要信箱資料夾旁。 使用者存取和搜尋封存的方式與存取和搜尋主要信箱相同。 可用的功能取決於使用的用戶端：
  
- **Outlook 2016、outlook 2013、outlook 2010 和 outlook 網頁** 版使用者可以存取封存的完整功能，以及相關的合規性功能，例如控制保留和封存原則。 
    
- **Outlook 2007** 使用者可使用就地封存的基本支援，但並非所有封存和符合性功能都可使用。例如，使用者無法將保留或封存原則套用到信箱項目，而必須改為依賴系統管理員所佈建的原則。 
    
系統管理員可使用 Exchange 系統管理中心或遠端 Windows PowerShell，針對特定使用者啟用個人封存功能。
  
如需詳細資訊，請參閱：
  
- [Exchange Online 中的封存信箱](../exchange-online-archiving-service-description/archive-features.md)
    
- [在 Exchange Online 中啟用或停用封存信箱](/office365/securitycompliance/enable-archive-mailboxes)
    
### <a name="archive-sizes"></a>封存大小

每個個人封存只能儲存一位使用者的郵件資料。 儲存空間的配置取決於訂閱計劃。 如需有關封存信箱大小的詳細資訊，請參閱 [Exchange Online 限制](exchange-online-limits.md)中的「信箱儲存限制」一節。
  
> [!IMPORTANT]
> - 不允許使用日誌記錄、傳輸規則或自動轉寄規則將郵件複製到 Exchange Online 信箱以進行封存。 Microsoft 保留在信箱封存未使用於個人案例中或其他不適當用途的情況下，拒絕無限封存的權利。
> - 就地封存針對 Outlook 使用者有特定的授權需求。Outlook 2007 使用者必須要有 2011 年 2 月累計更新的 Office 2007，才能存取個人封存。 
> - Exchange Online 不支援 Exchange Server 2010 Service Pack 1 或更新版本的 Windows PowerShell 指令程式的  _New-MailboxImportRequest_ Windows Cmdlet，以供系統管理員驅動的將 .pst 檔案匯入個人封存。 如果使用者在 Exchange Online 中同時有主要信箱和封存，則系統管理員可以使用 PST Capture 這項免費的工具，將 .pst 檔案資料匯入使用者的主要信箱或封存。

## <a name="cloud-based-archiving-of-on-premises-mailboxes"></a>雲端式封存內部部署信箱

您可以使用 Microsoft Exchange Online 封存這項由 Microsoft 提供的託管封存解決方案，使用 Exchange Online 對內部部署 Exchange Server 2010 或更新版本的信箱進行雲端式封存。若要執行這項作業，內部部署組織必須處於混合模式或設定使用 Exchange Online 封存。
  
> [!IMPORTANT]
> 若使用者在 Exchange 2010 信箱伺服器上有內部部署信箱，而且套用了受管理的資料夾原則，就無法啟用內部部署或雲端式就地封存功能。 
  
## <a name="retention-tags-and-retention-policies"></a>保留標記和保留原則

Exchange Online 提供保留原則，可協助組織減少電子郵件和其他通訊相關的責任。 透過這些原則，系統管理員可以將保留設定套用到使用者收件匣中的特定資料夾。 管理員也可以將保留原則的功能表提供給使用者，讓他們將原則套用至特定專案、交談或使用 Outlook 2010 或更新版本的資料夾或網頁上的 Outlook。
  
在 Exchange Online 中，系統管理員可以使用 Exchange 系統管理中心 (EAC) 或遠端 Windows PowerShell 來管理保留原則。
  
Exchange Online 提供兩種原則類型：封存原則和刪除原則。您可以在同一個項目或資料夾上結合使用這兩種類型。例如，使用者可以將電子郵件訊息標記在指定天數後自動移到就地封存，並在過了另一段天數之後刪除。
  
使用 Outlook 2010 或更新版本以及 Outlook 網頁版，使用者可以將保留原則套用至資料夾、交談或個別郵件。 他們也可以檢視套用的保留原則以及郵件的預定刪除日期。 其他電子郵件用戶端的使用者則只能根據系統管理員設定的伺服器端保留原則刪除或封存電子郵件訊息。
  
Exchange Online 提供的保留原則功能與 Exchange Server 2010 Service Pack 2 RU4 所提供的相同。系統管理員可以使用遠端 Windows PowerShell，將保留原則從內部部署 Exchange Server 2010 或更新版本的環境移轉到 Exchange Online。
  
> [!IMPORTANT]
> Exchange Online 不提供「受管理的資料夾」，這是 Exchange Server 2007 所引進的功能，為早期郵件記錄管理方法。 
  
如需詳細資訊，請參閱〈[保留標記和保留原則](/exchange/security-and-compliance/messaging-records-management/retention-tags-and-policies)〉。
  
## <a name="encryption-of-data-at-rest"></a>靜態資料的加密

靜態客戶資料的加密是由多種服務端技術所提供，包括 BitLocker、DKM、Azure 儲存服務加密，以及 Exchange Online 中的服務加密、商務用 Skype、商務 OneDrive，以及 SharePoint 線上。 Office 365 服務加密包含一個選項，可使用儲存在 Azure Key Vault 中客戶管理的加密金鑰。 此客戶管理的金鑰選項（稱為「 [客戶金鑰](/microsoft-365/compliance/customer-key-overview)」）適用于 Exchange Online、SharePoint Online 和商務 OneDrive。 
  
### <a name="bitlocker"></a>BitLocker

Microsoft 伺服器使用 BitLocker，將包含客戶資料的磁片磁碟機加密在磁片區層級。 BitLocker 加密是 Windows 內建的資料保護功能。 BitLocker 是用來保護威脅的技術之一，以防其他進程或控制項的存取控制或回收 (（例如，對包含客戶資料的磁片進行實體存取的硬體) 進行存取控制或回收）。 在此情況下，BitLocker 會因遺失、被竊或無法正確解除委任的電腦和磁片，避免資料竊取或洩密的可能性。 
  
### <a name="distributed-key-manager"></a>分散式金鑰管理員

除了 BitLocker 之外，我們還使用稱為「分散式金鑰管理員」 (DKM) 的技術。 DKM 是一種用戶端功能，使用一組機密金鑰來加密及解密資訊。 只有 Active Directory 網域服務中特定安全性群組的成員可以存取這些機碼，以解密由 DKM 所加密的資料。 在 Exchange Online 中，只有在執行 Exchange 程式的特定服務帳戶才屬於該安全性群組。 在資料中心的標準作業程式中，未被任何人提供此安全性群組的一部分認證，因此沒有人員可以存取可將這些機密解密的金鑰。
  
## <a name="customer-key"></a>客戶金鑰

使用客戶金鑰，您可以控制組織的加密金鑰，然後進行設定，以在 Microsoft 資料中心內加密靜態資料。 存放的資料包括 Exchange Online 資料和儲存在信箱的商務用 Skype 資料，以及儲存在 SharePoint Online 中和商務用 OneDrive 中的檔案。 如需詳細資訊，請參閱 [使用客戶金鑰](/office365/securitycompliance/controlling-your-data-using-customer-key) 和 [服務加密以客戶重要的常見問題解答](/office365/securitycompliance/service-encryption-with-customer-key-faq)來控制您的資料。
  
## <a name="office-365-message-encryption"></a>Office 365 郵件加密

Office 365 郵件加密可讓電子郵件使用者將加密的電子郵件傳送給任何人。 我們宣佈 Office 郵件加密中的新功能，利用 Azure 資訊加密中的保護功能。 這些新功能提供增強的使用者體驗，可讓您輕鬆地與組織內外的任何人共用及共同處理受保護的郵件。 新的 Office 郵件加密功能具有一些設定需求。 請參閱設定以 Azure 資訊保護為基礎的新 Office 365 郵件加密功能。 舊版 Office 365 郵件加密的客戶不會取得上述新功能，而不需遵循以上所提供的指導方針。 如需詳細資訊，請參閱 [常見問題解答](https://support.office.com/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e) 以取得新的 vs 舊版本 Office 365 郵件加密功能。 

Office 365 Advanced Message Encryption 允許郵件到期和吊銷，提供額外的保護。  您也可以建立多個範本，以用於來自組織的加密電子郵件。  「高級郵件加密」包含在 Microsoft 365 E5、Office 365 E5、Microsoft 365 E5 (非盈利性員工定價) 、Office 365 企業版 E5 (非盈利性員工定價) 或 Office 365 教育版 A5。 如果您的組織有未加入 Office 365 Advanced Message Encryption 的訂閱，您可以購買 Microsoft 365 E5 規範或 Office 365 Advanced 合規性 SKU 做為附加元件。

## <a name="securemultipurpose-internet-mail-extensions-smime"></a>Secure/Multipurpose Internet Mail Extensions (S/MIME)

S/MIME 可讓您在組織內傳送已簽署和已加密電子郵件，以協助保護敏感資訊。在建立並發出 PKI 憑證給使用者之後，系統管理員可以使用遠端 Windows PowerShell 來設定 S/MIME。這些憑證必須透過內部部署 Active Directory 憑證服務進行同步處理。
  
Microsoft Edge 和 Internet Explorer 11 支援 S/MIME。 目前，Firefox、Opera 和 Chrome 不支援 S/MIME。 如需詳細資訊，請參閱〈[適用於訊息簽署和加密的 S/MIME](/Exchange/policy-and-compliance/smime?preserve-view=true&view=exchserver-2019)〉。
  
## <a name="in-place-hold-and-litigation-hold"></a>就地保留與訴訟暫止

如果合理預期到訴訟的可能性，組織就需要保留與案件相關的電子儲存資訊 (ESI)，包括電子郵件。此預期心理會在了解案件的特定資料之前出現，而且需要保留的資料範圍通常很廣。組織可以保留所有與特定主題相關的電子郵件，或是有關特定個人的所有電子郵件。
  
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
  
如需詳細資訊，請參閱[原有範圍暫止](/exchange/security-and-compliance/in-place-and-litigation-holds)。
  
## <a name="in-place-ediscovery"></a>就地 eDiscovery

Exchange Online 可讓客戶使用網頁型介面搜尋整個組織中的信箱內容。 具有就地 eDiscovery 搜尋執行授權 (透過指派) 的系統管理員或法規遵循和安全性職員可搜尋電子郵件訊息、附件、行事曆約會、工作、連絡人及其他項目。 就地 eDiscovery 可以同時搜尋主要信箱和封存。 功能齊備的篩選功能包括寄件者、收件者、訊息類型、傳送/接收日期和副本/密件副本，另外還包括 KQL 語法。 搜尋結果將同時包含 [刪除的郵件] 資料夾中符合搜尋查詢的項目。
  
就地 eDiscovery 的搜尋結果可透過 Web 介面來預覽、匯出為 PST 檔案或複製到名稱為探索信箱的特殊信箱中。探索信箱有 50 GB 的配額可儲存搜尋結果。系統管理員也可以將 Outlook 連線至探索信箱，以存取搜尋結果並將其匯出為 .pst 檔案。
  
系統管理員可以使用 Exchange 系統管理中心或遠端 Windows PowerShell 來執行多信箱搜尋。Exchange 系統管理中心可提供搜尋結果的唯讀預覽，讓系統管理員可以快速驗證搜尋，並視需要使用不同參數重新執行該搜尋。在最佳化搜尋之後，系統管理員便可以將結果複製到探索信箱。
  
根據預設，系統會為每個組織建立一個探索信箱，不過系統管理員可以使用遠端 Windows PowerShell 建立更多的探索信箱。探索信箱無法用於儲存就地 eDiscovery 搜尋結果以外的用途。
  
系統管理員可以使用 Exchange 系統管理中心或遠端 Windows PowerShell 來執行就地 eDiscovery 搜尋。Exchange 系統管理中心可提供搜尋結果的唯讀預覽，讓系統管理員可以快速驗證搜尋，並視需要使用不同參數重新執行該搜尋。在最佳化搜尋之後，系統管理員便可以將結果複製到探索信箱，或將搜尋結果匯出為 PST 檔案。
  
系統管理員可以使用 Exchange 系統管理中心或遠端 Windows PowerShell，最多在就地 eDiscovery 搜尋中同時搜尋 10,000 個信箱。 
  
在 Exchange Online 中，已授權使用者能執行就地 eDiscovery 並選擇下列其中一個動作：
  
- **預估搜尋結果** 預估搜尋將傳回的郵件數，包括關鍵字統計資料，可確定用於搜尋的關鍵字效率，並依需求調整搜尋參數。 
    
- **預覽搜尋結果**
    
- 複製搜尋結果所傳回的郵件到探索信箱。
    
如需詳細資訊，請參閱[就地 eDiscovery](/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery)。
  
## <a name="mail-flow-rules"></a>郵件流程規則

您可以使用郵件流程規則，針對透過您的組織並採取行動的郵件尋找特定條件。 郵件流程規則可讓您將郵件原則套用至電子郵件訊息、安全訊息、保護郵件系統，並避免資訊洩露。
  
現今的法律、管控需求或公司原則要求許多組織套用郵件傳遞原則，以限制組織內部和外部之收件者與寄件者間的互動。除了限制個人、組織內的部門群組，以及組織外的實體間的互動外，有些組織也會受到下列郵件原則需求的控制：
  
- 防止不適當的內容進入或流出組織
    
- 篩選機密的組織資訊
    
- 追蹤或複製已傳送至特定個人或從特定個人接收到的郵件
    
- 在傳遞之前重新導向輸入及輸出郵件以進行檢查
    
- 在郵件通過組織時套用免責聲明至其中
    
> [!IMPORTANT]
> 需要在電子郵件伺服器上安裝協力廠商 Ifilter 的附件檔案類型 (例如 Adobe) 無法使用郵件流程規則來檢查，直到安裝適當的 iFilter 為止。 如需郵件流程規則支援之檔案類型的相關資訊，請參閱 [使用郵件流程規則檢查 Office 365 中的郵件附件](/exchange/security-and-compliance/mail-flow-rules/inspect-message-attachments)。
  
如需郵件流程規則的相關資訊，請參閱 [mail flow rules In Exchange 2016](/Exchange/policy-and-compliance/mail-flow-rules/mail-flow-rules?preserve-view=true&view=exchserver-2019)。
  
## <a name="data-loss-prevention"></a>資料遺失防護

資料遺失防護 (DLP) 功能可透過深入內容分析，協助您識別、監視和保護組織的敏感資訊。 DLP 是對於企業郵件系統越來越重要的一項高階功能，因為業務關鍵電子郵件包含需要受到保護的敏感資料。 Exchange Online 中的 DLP 功能可讓您保護機密資料，而不會影響工作者的生產力。
  
您可以在 Exchange 系統管理中心 (EAC) 管理介面中設定 DLP 原則，以便： 
  
- 開始使用預先設定的原則範本，協助您偵測特定的敏感資訊類型，例如 PCI-DSS 資料、Gramm-Leach-Bliley 金融服務業現代化法案資料，或甚至是特定地區設定的個人識別資訊 (PII)。
    
- 運用現有傳輸規則準則和動作的完整功能，並新增傳輸規則。
    
- 在完整執行 DLP 原則之前先測試其有效性。
    
- 加入您自己的自訂 DLP 原則範本和敏感資訊類型。
    
- 偵測郵件附件、本文或主旨行中的敏感資訊，並調整 Exchange Online 作用的信賴等級。
    
- 使用「文件指紋」偵測敏感表單資料。「文件指紋」會協助您根據可用於定義傳輸規則和 DLP 原則的文字型表單，輕易地建立自訂敏感資訊類型。
    
- 新增原則提示，可將通知顯示在 Outlook 2016、Outlook 2013、Outlook 網頁版和使用者的 OWA，以協助減少資料遺失，也可以允許誤報，以提升原則的效能。 
    
- 檢閱 DLP 報告中的事件資料，或使用產生事件報告動作來新增您自己的特定報告。
    
如需有關 DLP 的詳細資訊，請參閱〈[資料遺失防護](/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention)〉。
  
## <a name="journaling"></a>日誌

您可以設定 Exchange Online 將電子郵件的複本記錄到可以透過 SMTP 接收郵件的任何外部信箱。日誌記錄可藉由錄製輸入和輸出電子郵件通訊，協助您的組織回應法律、法規和組織符合性需求。規劃郵件保留和符合性時，務必了解日誌記錄的內容以及其如何適用於組織的符合性原則。
  
您可以使用 Exchange 系統管理中心或遠端 Windows PowerShell 來管理日誌規則。您可以依個別使用者或通訊群組清單設定日誌記錄，並選擇只記錄內部郵件、只記錄外部郵件，或兩者都記錄。日誌記錄郵件不僅包含原始郵件，同時還包含寄件者、收件者、副本和密件副本的相關資訊。
  
為了確保成功且可靠的日誌記錄解決方案，您必須完成下列工作：
  
- 請確定日誌記錄目的地不是 Exchange Online 信箱。
    
- 在客戶目錄中針對 SMTP 目標電子郵件地址建立連絡人物件，以用於日誌記錄。
    
- 建立第二個連絡人物件作為備用日誌信箱，以便在無法使用主要日誌信箱時擷取任何日誌報告。
    
- 維護 SMTP 目標的適當管理、冗余、可用性、效能和功能等級，以確保永遠能夠成功接受郵件。
    
- 在 Exchange Server 和 Exchange 傳輸之間提供適當的互通性，包括郵件格式、寄件者/收件者資訊整合以及適當的內容轉換。
    
如需有關日誌記錄的詳細資訊，請參閱〈[日誌記錄](/exchange/security-and-compliance/journaling/journaling)〉。
  
## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱 [Exchange Online 服務說明](exchange-online-service-description.md)。
