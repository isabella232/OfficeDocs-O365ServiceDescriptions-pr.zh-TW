---
title: 在 Exchange Online 封存的遵循與安全性功能
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
ms.openlocfilehash: 815800d14ab4eacf43ef966218117db5ad3c90f4
ms.sourcegitcommit: 19591e97b35c1b2a99e04a496d83af27dc6530d6
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/18/2019
ms.locfileid: "37581879"
---
# <a name="compliance-and-security-features-in-exchange-online-archiving"></a>在 Exchange Online 封存的遵循與安全性功能

## <a name="compliance-features-in-exchange-online-archiving"></a>Exchange Online 封存中的符合性功能

下列幾節說明 Microsoft Exchange Online Archiving 的符合性功能。
  
### <a name="retention-policies"></a>保留原則

Exchange Online Archiving 提供保留原則，可協助組織減少電子郵件與其他通訊的相關責任。 透過這些原則，系統管理員可以將保留設定套用到使用者收件匣中的特定資料夾。 系統管理員也可以授與使用者的保留原則] 功能表，並讓他們將原則套用到特定項目、 對話或資料夾使用 Outlook 2010 或更新版本或網頁型 Outlook。 在 Exchange Online Archiving 中，系統管理員會從內部部署基礎結構來管理保留原則。
  
Exchange Online Archiving 提供兩種類型的原則：封存原則和刪除原則。您可以在同一個項目或資料夾上同時套用這兩種類型。例如，使用者可以標記電子郵件，使其在指定天數後自動移至個人封存，並在又過了指定天數後刪除。
  
Outlook 2010 和更新版本及 outlook 網頁版，使用者可以將保留原則套用至資料夾、 對話或個別郵件，並可以對郵件也檢視套用的保留原則和預定的刪除日期。 其他電子郵件用戶端的使用者可根據系統管理員所佈建的伺服器端保留原則來刪除或封存電子郵件，但是沒有相同程度的檢視和控制能力。
  
Exchange Online Archiving 提供的保留原則功能與 Exchange Server 2010 Service Pack 2 (SP2) 及更新版本所提供的相同。系統管理員可以從內部部署 Exchange Server 2010 及更新版本的環境管理保留原則。受管理的資料夾是 Exchange 2007 中引進的舊式郵件記錄管理方法，無法在 Exchange Online 封存中使用且不相容。如需詳細資訊，請參閱[保留標記和保留原則](https://go.microsoft.com/fwlink/p/?LinkID=314153)。
  
### <a name="in-place-hold-and-litigation-hold"></a>就地保留與訴訟暫止

如果合理預期到訴訟的可能性，組織就需要保留與案件相關的電子儲存資訊 (ESI)，包括電子郵件。此預期心理會在了解案件的特定資料之前出現，而且需要保留的資料範圍通常很廣。組織可以保留所有與特定主題相關的電子郵件，或是有關特定個人的所有電子郵件。
  
> [!NOTE]
> 就地保留與訴訟暫止目前不會套用到使用 POP 或 IMAP 用戶端所傳送的電子郵件，或是藉由使用 SMTP 通訊協定的自訂應用程式所傳送的電子郵件。 
  
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

Exchange Online Archiving 支援就地 eDiscovery，可供搜尋組織中的信箱內容。系統管理員或經過授權的 Discovery 管理員可以從內部部署 Exchange 2013 伺服器，使用 Exchange 系統管理中心或遠端 Windows PowerShell 來搜尋各種信箱項目，包括電子郵件、附件、行事曆約會、工作及連絡人。就地 eDiscovery 可以同時搜尋主要信箱和封存。功能齊備的篩選功能包括寄件者、收件者、郵件類型、傳送日期、接收日期、副本及密件副本，另外還包括關鍵字查詢語法 (KQL) 語法。如需詳細資訊，請參閱[就地 eDiscovery](https://go.microsoft.com/fwlink/p/?LinkId=314169)。
  
Exchange 系統管理中心或遠端 Windows PowerShell 一次最多可以在就地 eDiscovery 搜尋中搜尋 5,000 個信箱。如需使用遠端 Windows PowerShell 執行就地 eDiscovery 搜尋的詳細資料，請參閱 [New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170)。 
  
> [!NOTE]
> 在遠端 Windows PowerShell 中， `Search-Mailbox` Cmdlet 可以用來搜尋 5,000 個以上的信箱。如需使用遠端 Windows PowerShell 搜尋大量信箱的詳細資訊，請參閱 [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171)。 
  
就地 eDiscovery 搜尋的結果可在 Exchange 系統管理中心預覽、匯出為 .pst 檔案，或複製到名為探索信箱的特殊信箱中。系統管理員或符合性專員可以連到探索信箱來檢閱郵件。如需詳細資訊，請參閱[建立就地 eDiscovery 搜尋](https://go.microsoft.com/fwlink/p/?LinkId=314172)。
  
> [!NOTE]
> 複製跨內部部署與雲端信箱或封存來執行之就地 eDiscovery 搜尋的搜尋結果時，您必須選取內部部署的探索信箱。內部部署主要信箱和雲端封存中的郵件會複製到內部部署的探索信箱。 
  
系統管理員也可以搜尋並刪除寄送到整個組織中之多個信箱的不當電子郵件。例如，如果不小心將機密薪資資訊寄給所有員工，系統管理員就可以從使用者的信箱刪除電子郵件。此類型的搜尋不適用於 Exchange 系統管理中心。它必須使用遠端 PowerShell 執行。如需如何從使用者的信箱刪除郵件的詳細資訊，請參閱[搜尋並刪除郵件](https://go.microsoft.com/fwlink/p/?LinkId=314173)。
  
## <a name="security-features-in-exchange-online-archiving"></a>Exchange Online 封存中的安全性功能

下列幾節說明 Microsoft Exchange Online Archiving 的安全性功能。
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a>內部部署伺服器與 Exchange Online 封存之間的加密

TLS 用來加密電子郵件伺服器之間的連線，以防止詐騙並為傳輸中的郵件添加機密性。TLS 也用來保護送至 Exchange Online Archiving之 Office 365 資料中心的內部部署郵件伺服器流量。
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a>用戶端與 Exchange Online 封存之間的加密

與 Exchange Online Archiving的用戶端連線使用下列加密方法來加強安全性：
  
- 使用 SSL 來保護 Outlook、 Outlook web] 中，與 Exchange Web 服務流量使用 TCP 連接埠 443。
    
- 與內部部署伺服器的用戶端連線不會因為 Exchange Online Archiving的出現而改變。
    
### <a name="encryption-smime-and-pgp"></a>加密：S/MIME 和 PGP

Exchange Online Archiving 會儲存安全多用途網際網路郵件延伸 (S/MIME) 郵件。不過，Exchange Online Archiving不會裝載 S/MIME 功能或公開金鑰，也不會提供金鑰存放庫、金鑰管理或金鑰目錄服務，因為這些服務全都會附加至內部部署 Exchange 基礎結構。
  
同樣地，Exchange Online Archiving會儲存使用用戶端、協力廠商加密解決方案 (如 Pretty Good Privacy (PGP)) 加密的郵件。
  
### <a name="information-rights-management"></a>資訊版權管理

Exchange Online Archiving不提供託管的資訊版權管理 (IRM) 服務，但管理員可以使用內部部署的 Active Directory 版權管理服務 (AD RMS)。若部署了 AD RMS 伺服器，則 Outlook 可以直接與該伺服器通訊，讓使用者能夠撰寫和讀取受到 IRM 保護的郵件。若設定了 AD RMS 伺服器與內部部署 Exchange 環境之間的交互操作性，則使用者可以撰寫和讀取受到 IRM 保護的郵件。
  
#### <a name="support-for-irm-in-outlook-on-the-web"></a>Outlook 網頁版中的 IRM 支援

使用者可以讀取和建立受 IRM 保護的郵件原生網頁型 Outlook 中一樣，它們可以在 Outlook 中。 網頁型 Outlook 中的 IRM 保護的郵件可透過 Internet Explorer、 Firefox、 Safari 和 Chrome (不需要外掛程式)。 這些郵件包含全文檢索搜尋、交談檢視和預覽窗格。 必須設定 Active Directory Rights Management Services 伺服器與內部部署 Exchange 環境之間的交互操作性，才能啟用此功能。
  
#### <a name="irm-search"></a>IRM 搜尋

受 IRM 保護的郵件因為已有編製索引，所以可以加以搜尋，包括標題、主旨、內文及附件。 使用者可以在 Outlook 和網頁型 Outlook 中搜尋受 IRM 保護的項目和系統管理員可以使用就地 eDiscovery 或**Search-mailbox** cmdlet 來搜尋受 IRM 保護的項目。
  
### <a name="auditing"></a>稽核

Exchange Online Archiving提供兩種類型的內建稽核功能：
  
- **系統管理員稽核記錄功能** 系統管理員稽核記錄功能可讓客戶追蹤其系統管理員在 Exchange Online Archiving 環境中所做的變更，包括對 RBAC 角色或 Exchange 原則與設定的變更。 
    
- **信箱稽核記錄功能** 信箱稽核記錄功能可讓客戶追蹤信箱擁有者以外的使用者對信箱的存取情形。 
    
Exchange 系統管理中心提供多份預先定義的稽核報告，包括系統管理員角色變更、訴訟資料暫留，以及非擁有者信箱存取。系統管理員可依日期與角色篩選報告，也可基於長期保留或自訂報告等目的，使用 XML 格式匯出指定信箱的所有稽核事件。
  
系統管理員稽核記錄功能預設會開啟，但信箱稽核記錄功能預設會關閉。系統管理員可以使用遠端 Windows PowerShell 來啟用組織中部分或全部信箱的信箱稽核記錄功能。如需詳細資訊，請參閱[稽核報告](https://go.microsoft.com/fwlink/p/?LinkId=314175)。
  
## <a name="feature-availability"></a>功能可用性

若要檢視 Office 365 計劃、獨立選項和內部部署解決方案中的功能可用性，請參閱 [Exchange Online 封存服務說明](exchange-online-archiving-service-description.md)。
  

