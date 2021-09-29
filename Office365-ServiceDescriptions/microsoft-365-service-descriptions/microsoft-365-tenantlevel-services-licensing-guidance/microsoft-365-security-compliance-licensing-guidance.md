---
title: 安全性 & 相容性的 Microsoft 365 指導方針
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.reviewer: v-trscho
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: 本文提供 Microsoft 365 合規性的指導方針，以協助避免因未授權存取的潛在服務中斷。
ms.openlocfilehash: 59e7714ec09b56a0e9bfb22d87d9419d991f8ee6
ms.sourcegitcommit: 0ef110d0f0a11c1943560373e0f022364053640c
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/28/2021
ms.locfileid: "59986159"
---
# <a name="microsoft-365-guidance-for-security-amp-compliance"></a>安全性規範的 Microsoft 365 指導方針 &amp;

針對此文章的目的，租用戶層級服務為一項線上服務，&mdash;為租用戶中的任何使用者購買 (獨立購買或隨著 Office 365 或 Microsoft 365 方案購買)&mdash; 時，會為租用戶中的部分或所有使用者啟用。 雖然部分未取得授權的使用者在技術上可能可存取服務，但想要從服務獲益的任何使用者都必須具備授權。

> [!NOTE]
> 部分租用戶服務目前無法將權益限制在特定使用者。 應該努力將服務權益限制在取得授權的使用者。 這麼做有助於在鎖定功能可用時避免對組織造成潛在的服務中斷。

若要查看授權您的使用者受益 Microsoft 365 規範功能的選項，請下載[Microsoft 365 比較表](https://go.microsoft.com/fwlink/?linkid=2139145)。

## <a name="advanced-audit"></a>進階稽核

Microsoft 365 中的「高級審計」為使用者和系統管理員活動提供一年的審計記錄檔保留，並提供建立自訂審核記錄保留原則，以管理其他 Microsoft 365 服務的審計記錄保留。 此外，它也可讓您存取重要事件，以進行調查和對 Office 365 管理活動 API 的高頻寬存取。 如需詳細資訊，請參閱[Microsoft 365 中的「高級審核](/microsoft-365/compliance/advanced-audit)」。

您也可以使用附加元件 SKU 來啟用保留期間（10年）。

### <a name="which-users-benefit-from-the-service"></a>哪些使用者可從此服務獲益？

Office 365 E5/A5/G5 的授權使用者，Microsoft 365 E5/A5/G5，Microsoft 365 E5/A5/G5/F5 相容性，Microsoft 365 F5 安全性 & 相容性，以及 Microsoft 365 E5/A5/G5 eDiscovery 和審核可從高級審核中受益。

使用高級審計的授權使用者，以及10年的審計記錄保留附加元件，可從10年的審計記錄保留中受益。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

使用者受益于「高級審計」，是因為與 Microsoft 365 服務中的使用者活動相關的審計記錄可以保留最多一年。 此外，會記錄高值審核事件，例如，當存取或讀取使用者信箱中的專案時。 如需詳細資訊，請參閱[Microsoft 365 中的「高級審核](/microsoft-365/compliance/advanced-audit)」。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，會針對所有從服務受益的使用者，在租使用者層級啟用高級審核，並自動提供一年的審計記錄檔保留，以 (供使用者使用適當授權) Azure Active Directory、Exchange 及 SharePoint 執行。 此外，組織可使用審核記錄保留原則來管理其他 Microsoft 365 服務中的活動所產生的審計記錄的保留期間。 您也可以使用相同的保留原則，啟用10年的審計記錄保留功能。 如需詳細資訊，請參閱[管理稽核記錄保留原則](/microsoft-365/compliance/audit-log-retention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

只保留一年的審計記錄，而對重要的事件進行審核，只適用于具有適當授權的使用者。 此外，系統管理員可以使用審核記錄保留原則，為特定使用者的審計記錄檔指定較短的保留期間。

10年保留的審計記錄檔只適用于具有適當附加元件授權的使用者。 從2021開始，將需要附加元件 SKU。

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory身分識別保護是 Azure Active Directory Premium P2 計畫的一項功能，可讓您偵測影響組織之身分識別的潛在弱點、設定自動回應，以偵測到與您組織的身分識別相關的可疑動作，以及調查可疑事件，並採取適當的措施加以解決。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

由於有了基於機器學習演算法、標幟的使用者和風險事件的彙總檢視，安全作業分析人員和安全性專業人員可從中獲益。 使用者則可獲益於透過風險式條件存取提供的自動防護，以及可對弱點採取行動而改善的安全性。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

- Azure Active Directory方案1： Microsoft 365 E3/A3/G3/F1/F3、Enterprise 行動性 & 安全性 E3 及 Microsoft 365 商務進階版
- Azure Active Directory方案2： Microsoft 365 E5/A5/G5、Enterprise 行動性 & 安全性 E5、Microsoft 365 E5/F5 安全性及 Microsoft 365 F5 安全性 & 相容性

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，會在租使用者中的所有使用者在租使用者層級上啟用 Azure AD 身分識別保護功能。 如需 Azure AD 身分識別保護的詳細資訊，請參閱 [何謂身分識別保護？](/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員可以指派定義密碼重設層級的風險原則，並只允許授權使用者的存取，以限定 Azure AD 身分識別保護的範圍。 如需如何針對 Azure AD 身分識別保護部署進行範圍的指示，請參閱 how [to configure and enable 危險原則](/azure/active-directory/identity-protection/howto-sign-in-risk-policy)。

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory身分識別管理

Azure Active Directory身分識別管理可讓您以適當的處理常式和可視性，平衡組織的安全性和員工生產力需求。 它使用權利管理、存取權、特權身分識別管理，以及使用條款原則，以確保適當的人員能夠正確地存取正確的資源。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

Azure Active Directory身分識別控管會讓使用者在一個存取封裝中存取應用程式、群組和 Microsoft Teams 變得更容易。 使用者也可以設定為核准者，但不包括管理員。 若要進行存取權檢查，使用者可以透過智慧建議檢查群組的成員資格，以定期採取動作。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Enterprise Mobility + SecurityE5/A5，Microsoft 365 E5/A5，Microsoft 365 E5/A5/F5 安全性和 F5 security & 合規性，而 Azure Active Directory Premium 計畫2為使用者提供權力，以 Azure Active Directory 身分識別管理。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

Azure AD 身分識別控管功能會在租使用者層級啟用，但是會以每位使用者的身分執行。 如需 Azure AD 身分識別管理的相關資訊，請參閱 [什麼是 AZURE ad 身分識別管理？](/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員可以只為已授權的使用者指派訪問套件、存取權或特權身分識別管理，以限定 Azure AD 身分識別管理的範圍。 如需如何針對 Azure AD 身分識別管理部署進行範圍的指示，請參閱：

- [Azure AD 權利管理授權需求](/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Azure AD access 複查授權需求](/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [使用 Privileged Identity Management 的授權需求](/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="communication-compliance"></a>通訊合規性

Microsoft 365 中的通訊法規遵從性，可協助您偵測、捕獲和採取補救措施，對組織中不適當的郵件進行偵測，以盡可能降低通訊風險。 您可以定義可擷取內部和外部電子郵件、Microsoft Teams 或協力廠商通訊的特定原則。 檢閱者可以採取適當的修正動作，以確保它們符合您組織的郵件標準。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

合規性專家會透過通訊合規性原則監控組織通訊，以享受服務。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Office 365 E5/A5/G5，Microsoft 365 E5/A5/G5，Microsoft 365 E5/A5/G5/F5 相容性，Microsoft 365 F5 安全性 & 法規遵從性和 Microsoft 365 E5/A5/G5 有問必答「內幕人員風險管理」為使用者提供的許可權，以獲得通訊相容性。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

管理員和合規性專業人員會在 Microsoft 365 合規性中心中建立通訊法規遵從性原則。 這些原則定義哪些通訊和使用者要在組織中進行審閱、定義通訊必須符合的自訂條件，以及指定應執行複查的人員。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

管理員選擇要包含在通訊合規性原則中的特定使用者或群組。 選擇群組時，使用者也可以從通訊合規性原則中，選取要排除在群組中的特定使用者。 如需通訊相容性原則的詳細資訊，請參閱[Microsoft 365 中的通訊符合性入門](/microsoft-365/compliance/communication-compliance-configure)。

## <a name="compliance-manager"></a>合規性管理員

[Microsoft 合規性管理員](https://compliance.microsoft.com/compliancemanager)是[Microsoft 365 合規性中心](/microsoft-365/compliance/microsoft-365-compliance-center)中的功能，可協助您管理組織的合規性需求，以獲得更輕鬆和便利。 合規性管理員可在整個合規性過程中協助您，從盤點資料保護風險到管理實施控制措施的複雜性、保持最新的法規和認證，以及向稽核員報告。

合規性管理員提供下列功能，協助簡化法規遵從性並降低風險：

- 針對常見的產業和地區的標準與法規預先建立的評估或自訂評估，可符合您獨特的合規性需求。
- 工作流程功能可透過單一工具協助您有效率地完成風險評定。
- 詳細的逐步指導方針，可協助您遵循組織最相關的標準及規定。 針對 Microsoft 所管理的動作，您將會看到「執行詳細資料」和「審計結果」。
- 以風險為基礎的符合性分數，可協助您瞭解符合性狀況，方法是測量您完成改進動作的進度。

### <a name="who-can-access-compliance-manager"></a>神秘可以存取合規性管理員？

合規性管理員可供具有 Office 365 和 Microsoft 365 授權的組織使用，並可政府社群雲端 (GCC) 、GCC 高及國防部門 (DoD) 客戶。 評估可用性和管理功能取決於您的授權合約。

### <a name="what-are-premium-assessments"></a>何謂高級評估？

進階版評估是合規性管理員及協助的附加元件值：

- 將複雜的法規需求翻譯為特定控制項
- 建議的改進動作
- 針對法規提供可計量的規範衡量

合規性管理員有300個以上的評估，可供客戶用來評估其與全球通用、地區和工業法規及標準範圍的符合性。

任何含 Microsoft Exchange Online 授權之訂閱的客戶都可能購買合規性管理員特優評估。

### <a name="which-premium-assessments-are-available"></a>可以使用哪種高級評估？

以下是 [特優評估清單](/microsoft-365/compliance/compliance-manager-templates-list#premium-templates)。

### <a name="which-assessments-are-included-by-default-free-of-cost"></a>預設 (包含哪些評估) 可用成本？

某些評估包含在合規性管理員和客戶授權類型中。 如需詳細資訊，請參閱下表：

| 授權類型 | 預設會包含評估範本 ()  |
|:-----|:-----|
|<ul><li>Microsoft 365 或 Office 365 A1/E1/F1/G1</li><li>Microsoft 365 或 Office 365 A3/E3/F3/G3</li></ul>|<ul><li>資料保護基準</li></ul>|
|<ul><li>Microsoft 365 或 Office 365 A5/E5/G5</li><li>Microsoft 365 A5/E5/F5/G5 合規性</li><li>Microsoft 365 A5/E5/F5/G5 eDiscovery 和核查</li><li>Microsoft 365 A5/E5/F5/G5 有問必答風險管理</li><li>Microsoft 365 A5/E5/F5/G5 資訊保護和管理</li></ul>|<ul><li>資料保護基準</li><li>歐盟 GDPR</li><li>NIST 800-53</li><li>ISO 27001</li><li>CMMC 等級 1-5 (僅可用於 G5) </li><li>自訂評估</li></ul>|

### <a name="what-are-custom-assessments"></a>何謂自訂評估？

自訂評估是一種合規性管理員功能，可讓您建立新的範本或自訂現有的評估範本，包括新增或更新控制項和改進動作。

### <a name="who-can-access-custom-assessments"></a>神秘可以存取自訂評估？

自訂評估功能可供具有 E5 訂閱的客戶使用，如下所示：

- Microsoft 365 或 Office 365 A5/E5/G5
- Microsoft 365 A5/E5/F5/G5 合規性
- Microsoft 365 A5/E5/F5/G5 eDiscovery 和核查
- Microsoft 365 A5/E5/F5/G5 有問必答風險管理
- Microsoft 365 A5/E5/F5/G5 資訊保護和管理

## <a name="customer-key-for-microsoft-365"></a>Microsoft 365 的客戶金鑰

使用客戶金鑰，您可以控制組織的加密金鑰，並設定 Microsoft 365，以使用這些金鑰在 Microsoft 資料中心內加密您的資料。 換句話說，客戶金鑰可讓您新增屬於您、使用您自己的金鑰的一層加密。 客戶金鑰透過 Microsoft 365 資料靜態加密服務，提供多個[Microsoft 365 工作負載](/microsoft-365/compliance/customer-key-overview#about-data-encryption-policies)的資料靜止加密支援。 此外，客戶金鑰會為 SharePoint 線上和商務用 OneDrive 資料提供加密，以及 Exchange Online 信箱層級加密。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

使用者可讓其待用資料在應用程式層使用其自己的組織所提供、控制及管理的加密金鑰加密，藉此從客戶金鑰獲益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 規範、Microsoft 365 F5 安全性 & 法規遵從性、Microsoft 365 E5/A5/G5 資訊保護和控管，以及 Office 365 E5/A5/G5 為使用者提供的權力，都是由客戶金鑰帶來的益處。 若要獲得客戶金鑰的完整優勢，您也必須具有 Azure 金鑰保存庫的訂閱。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

[設定客戶重要](/microsoft-365/compliance/customer-key-set-up)文章說明建立及設定必要 Azure 資源所需遵循的步驟，並提供設定客戶機碼的步驟。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

Microsoft 365 提供多工作負載加密支援的資料靜止服務是租使用者層級服務。 雖然部分未取得授權的使用者在技術上可能可存取服務，但想要從服務獲益的任何使用者都必須具備授權。 針對 Exchange Online 信箱層級加密，必須授權使用者信箱指派資料加密原則。

## <a name="data-connectors"></a>資料連線器

Microsoft 提供可在 Microsoft 365 合規性中心中設定的協力廠商資料連線器。 如需 Microsoft 所提供的資料連線器清單，請參閱 [協力廠商資料連線器](/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) 表格。 在 Microsoft 365 中匯入及封存資料後，此表格也會摘要您可以套用至協力廠商資料的相容性解決方案，並連結至每個連接器的逐步指示。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

使用資料連線器匯入及封存 Microsoft 365 中協力廠商資料的主要好處是，您可以在匯入資料後，將各種 Microsoft 365 規範解決方案套用至資料。 這可協助確保您組織的非 Microsoft 資料符合影響組織的規章和標準。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

下列授權可為使用者提供的許可權，以受益于資料連線器：

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 &amp; 資訊保護控管
- Microsoft 365 E5/A5/G5/F5 合規性
- Microsoft 365F5 安全性 & 合規性
- Microsoft 365 E5/A5/G5 有問必答風險管理
- Microsoft 365 E5/A5/G5 eDiscovery 和核查
- Office 365 E5/A5/G5

針對 Microsoft 合作夥伴提供的 Microsoft 365 安全性規範中心內的資料連線器，您的 &amp; 組織必須與合作夥伴進行業務關係，才能部署這些連接器。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

連接器是使用安全性與 &amp; 合規性中心和連接器目錄來設定。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

資料連線器服務是租使用者層級的值。 每一位由此服務受益的使用者皆須獲得授權。

## <a name="data-classification-analytics-overview-content-amp-activity-explorer"></a>資料分類分析：內容 &amp; 活動瀏覽器

資料分類分析功能可在 Microsoft 365 合規性中心體驗內使用。 [一覽表] 顯示數位內容的位置，以及最常見的敏感資訊類型及標籤的位置。 內容瀏覽器提供敏感性資料數量和類型的可見度，並可讓使用者依標籤或敏感度類型進行篩選，以取得儲存敏感性資料位置的詳細資訊。 活動瀏覽器顯示與敏感性資料和標籤相關的活動，例如標籤降級或外部共用，可將內容公開至風險。

活動瀏覽器提供單一的玻璃窗格，讓系統管理員可以深入瞭解與使用者所使用之敏感資訊相關的活動。 這些資料包括標籤活動、資料遺失防護 (DLP) 記錄、自動標籤、端點 DLP 等等。

內容 Explorer 會讓系統管理員能夠為儲存在支援 Microsoft 365 工作負載內的敏感檔編制索引，並識別所儲存的機密資訊。 此外，內容瀏覽器也可協助識別使用敏感度和保留標籤分類的檔。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

資訊保護和合規性系統管理員可以存取這些記錄檔及索引資料，以瞭解儲存敏感性資料的位置以及與此資料相關的活動，以及使用者所執行的活動。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Microsoft 365 E5/A5/G5 的授權使用者，Microsoft 365 E5/A5/G5/F5 相容性，Microsoft 365 F5 安全性 & 法規遵從性，Microsoft 365 E5/A5/G5 資訊保護控管 &amp; 和 Office 365 E5 可以從 Microsoft 365 資料分類分析中受益。

Microsoft 365 E3/A3/G3 和 Office 365 E3/A3/G3 可讓使用者只從內容瀏覽器資料匯總中受益。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，會在租使用者中的所有使用者在租使用者層級上啟用總覽內容和活動瀏覽器功能。 如需設定授權使用者資料分類 analytics 的詳細資訊，請參閱：

- **內容瀏覽器**：[從內容 explorer 開始-Microsoft 365 符合性 |Microsoft](/microsoft-365/compliance/data-classification-content-explorer)檔。
- **活動瀏覽器**：[開始使用活動 explorer-Microsoft 365 符合性 |Microsoft](/microsoft-365/compliance/data-classification-activity-explorer)檔。
- **資料分類版本** 資訊：[資料分類版本記事-Microsoft 365 符合性 |Microsoft](/microsoft-365/compliance/data-classification-pub-preview-relnotes)檔。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

您必須將此功能的範圍設為主動使用 Microsoft 365 規範入口網站內之解決方案的使用者。

## <a name="data-loss-prevention-for-teams"></a>Teams 的資料遺失防護

透過 Teams 的通訊 DLP，組織可以封鎖包含機密資訊（例如財務資訊、個人身分識別資訊、健康情況相關資訊或其他機密資訊）的研討及通道訊息。

### <a name="which-users-benefit-from-the-service"></a>哪些使用者可從此服務獲益？

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5/F5 合規性和 F5 安全性 & 相容性
- Microsoft 365 E5/A5/G5 資訊保護和管理
- Office 365 E5/A5/G5

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

當寄件者在其外送聊天和通道訊息中檢查敏感資訊（如組織的 DLP 原則中所設定）時，寄件者的益處。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，Teams 聊天和頻道訊息為針對租用戶內所有使用者的這些 DLP 功能的 *啟用位置 (工作負載)*。 如需使用 DLP 原則的詳細資訊，請參閱[資料外洩防護概觀](/office365/securitycompliance/data-loss-prevention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員可以在安全 &amp; 規範中心的 [**資料遺失防護**] 位置下，自訂地點 (工作負載) 、包含的使用者，以及排除的使用者  >  ****。

## <a name="data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Exchange Online、SharePoint Online 及商務用 OneDrive 適用的資料外洩防護

使用 Office 365 資料遺失防護 (DLP) 進行 Exchange Online、SharePoint 線上及商務用 OneDrive，組織可以識別、監視和自動保護整個電子郵件和檔案中的機密資訊，包括儲存在 (檔案中的檔案。資料庫) 。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

在檢查電子郵件和檔案的敏感資訊時（如組織的 DLP 原則中所設定），使用者會從 DLP 取得 Exchange Online、SharePoint 線上及商務用 OneDrive 的益處。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Microsoft 365 E3/A3/Business 進階版，Office 365 E3/A3，及 Office 365 資料遺失防護和 f5 相容性和 f5 安全性 & 規範可為使用者提供權力，以供 Office 365、Exchange Online 線上及 SharePoint 的商務用 OneDrive DLP 中受益。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，Exchange Online 電子郵件、SharePoint 網站和 OneDrive 帳戶為針對租用戶內所有使用者的這些 DLP 功能的 *啟用位置 (工作負載)*。 如需使用 DLP 原則的詳細資訊，請參閱[資料外洩防護概觀](/microsoft-365/compliance/data-loss-prevention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員可以在安全 &amp; 規範中心的 [**資料遺失防護**] 位置下，自訂地點 (工作負載) 、包含的使用者，以及排除的使用者  >  ****。

## <a name="double-key-encryption-for-microsoft-365"></a>Microsoft 365 的雙金鑰加密

Microsoft 365 的雙金鑰加密可讓您保護高度機密的資料，以符合特殊需求，並維護加密金鑰的完整控制權。 雙金鑰加密會使用兩個金鑰來保護您的資料，並在您的控制項中有一個按鍵，並 Microsoft Azure 安全地儲存第二個金鑰。 若要查看資料，您必須具有這兩個索引鍵的存取權。 因為 Microsoft 只可以存取單一機碼，所以您的金鑰和您的資料也無法供 Microsoft 使用，以確保您可以完全控制資料的隱私權和安全性。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

使用者可以將加密的資料移轉至雲端，以將其加密的資料移轉至雲端，以避免協力廠商存取，只要該機碼仍保持控制使用者的控制權，使用者就能受益。 使用者可以保護和使用類似于任何其他敏感度標籤的加密內容，類似于任何其他敏感度標籤保護的內容。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Microsoft 365 E5/A5/G5，Microsoft 365 E5/A5/G5/F5 相容性和 F5 安全性 & 法規遵從性，Microsoft 365 E5/A5/G5 資訊保護和控管，Office 365 E5/A5/G5 和 EMS E5 可為使用者提供的權力，以從雙金鑰加密中受益。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

雙金鑰加密可支援 Windows 的 Microsoft Office 的桌上出版本。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

若要將加密金鑰指派到 Office 365 和/或 Microsoft 365 組織中的資料，以供授權的使用者使用，請遵循雙重金鑰加密部署指示。

## <a name="ediscovery"></a>電子文件探索

eDiscovery 在公司內為 IT 和法律部門提供調查和 eDiscovery 解決方案，以在 Microsoft 365 系統中出口、收集、保留、減少及檢查與調查或訴訟相關的內容。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

當使用者被選取為資料監管人 (具有文件或電子檔案系統管理控制權的人員) 時，使用者即可從進階電子文件探索獲益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Microsoft 365 E5/A5/G5/E3/A3/G3，Office 365 E5/A5/G5/E3/A3/G3 and f5 合規性和 f5 Security & 合規性會為使用者提供從核心 eDiscovery 受益的權利。

Microsoft 365 E5/A5/G5，Microsoft 365 E5/A5/G5/F5 相容性和 F5 安全性 & 法規遵從性、Microsoft 365 E5/A5/G5 eDiscovery 及 Audit，以及 Office 365 E5/A5/G5 為使用者提供的權力，可從 Advanced eDiscovery 中受益。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，當系統管理員在安全規範中心中指派 eDiscovery 許可權時，會在租使用者層級上啟用 Advanced eDiscovery 功能 &amp; 。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

電子文件探索系統管理員可以使用進階電子文件探索中內建的監管人管理工具，將特定使用者選取為案例的資料監管人，如[將監管人新增至進階電子文件探索案例](/microsoft-365/compliance/add-custodians-to-case)中所述。

## <a name="information-barriers"></a>資訊障礙

資訊障礙是指管理員可以設定以避免個人或群組彼此進行通訊的原則。 比方說，如果某個部門處理的資訊不應與其他部門共用，或需要防止某個群組與外部連絡人通訊，此功能就相當實用。 資訊屏障原則也可以防止查閱和探索。 這表示如果您嘗試與不應與之通訊的人員通訊，您將不會在人員選擇器中找到該使用者。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

使用者可從使用者會受限而無法與其他人通訊之資訊屏障的進階符合性功能獲益。 您可以定義資訊障礙原則，以防止某些使用者從彼此進行通訊，或允許特定的區段只與特定的網段進行通訊。 如需定義資訊障礙原則的詳細資訊，請參閱 [定義資訊關卡原則](/microsoft-365/compliance/information-barriers-policies)。 針對兩個群組無法彼此通訊的情況，這兩個群組中的使用者都需要授權才能從服務中受益 (請參閱下列範例) 。<br><br>

| 案例 | 誰需要授權？ |
|:------|:------|
|  (Group &nbsp; 1 和 group) 2 群組的兩個群組 &nbsp; 無法彼此通訊 (也就是說，群組 &nbsp; 1 使用者受到限制，無法與群組 &nbsp; 2 使用者通訊，群組 &nbsp; 2 使用者限制于與群組 &nbsp; 1 使用者通訊。 | 群組 &nbsp; 1 和群組2中的 &nbsp; 使用者 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 相容性和 F5 安全性 & 法規遵從性、Microsoft 365 E5/A5/G5 內幕風險管理，以及 Office 365 E5/A5/G5，為使用者提供權力，以受益于資訊障礙。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

系統管理員可以使用安全性與合規性中心的 PowerShell Cmdlet 來建立及管理資訊障礙原則 &amp; 。 系統管理員必須獲指派 Microsoft 365 企業全域系統管理員、Office 365 全域系統管理員或合規性系統管理員角色，才能建立資訊屏障原則。 根據預設，這些原則會套用至租用戶中的所有使用者。 如需資訊屏障的詳細資訊，請參閱 [Microsoft Teams 中的資訊屏障](/MicrosoftTeams/information-barriers-in-teams)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員可以自訂 (工作負載) 、包含的使用者，以及在安全性與合規性中心內排除使用者的位置 &amp; 。 例如，如果所有使用者都已取得 Office 365 E3 的授權，且皆未取得 Office 365 進階合規性/E5 的授權，則不需要為組織建立任何資訊屏障原則。 如需詳細資訊，請參閱 [Microsoft Teams 中的資訊屏障](/MicrosoftTeams/information-barriers-in-teams)。

## <a name="information-protection"></a>資訊保護

資訊保護可協助組織探索、分類、標籤及保護機密檔和電子郵件。 系統管理員可以定義規則和條件，以自動套用標籤，使用者可以手動套用標籤，或使用二者的組合，使用者會在其中獲得套用標籤的建議。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

使用者可透過將敏感度標籤手動套用至其內容，或透過自動分類其內容來獲得好處。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business 進階版，f5 相容性和 F5 Security & 合規性，企業行動力 + 安全性 E3/E5，M365 E5/A5/G5，Office 365 E5/A5/E3/A3/F3，AIP Plan 1，and AIP Plan 2 為使用者提供的權力，可供使用者從手動敏感度標記中受益。

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business 進階版 and 企業行動力 + 安全性 E3/E5，AIP Plan 1，and AIP Plan 2 and f5 合規性和 f5 安全性 & 規範可讓使用者受益于在 Power BI 中套用和查看敏感度標籤，並在從 Power BI 匯出至 Excel、PowerPoint 或 PDF 時，保護資料。

Microsoft 365 商務進階版和 Enterprise 行動性提供使用[AIPService](/powershell/azure/aip/overview#aipservice) PowerShell 模組管理 azure 資訊保護 azure rights Management protection service 的許可權。

> [!NOTE]
> Power BI 包含 Microsoft 365 E5/A5/G5;在所有其他計畫中，必須個別授權 Power BI。

Microsoft 365 E5/A5/G5，Microsoft 365 E5/A5/G5/F5 相容性和 F5 安全性 & 合規性，Microsoft 365 E5/A5/G5 資訊保護和控管，Office 365 E5，Enterprise Mobility + Security E5/A5/G5和 AIP Plan 2 為使用者提供的權力，可從自動敏感度標記中受益。

資訊保護不包含根據機器學習 (trainable 分類器) 自動分類的許可權。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，會在租使用者中的所有使用者的租使用者層級上啟用資訊保護功能。 如需設定授權使用者之原則的詳細資訊，請參閱啟用 Azure Rights Management。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

除了使用 AIP 掃描器功能時，您可以編輯原則，以防止未授權的使用者執行分類或標記功能。

針對 AIP 掃描器功能，Microsoft 並未承諾會為未授權的使用者提供檔案分類、標記或保護功能。

如需詳細資訊，請參閱 [建立及發行敏感度標籤](/microsoft-365/compliance/create-sensitivity-labels#publish-sensitivity-labels-by-creating-a-label-policy) 及 [瞭解 Azure 資訊保護統一標記掃描器](/azure/information-protection/deploy-aip-scanner)。

## <a name="information-governance"></a>資訊管理

資訊控管會透過發現、分類、標示和管理其資料來協助組織管理其風險。 資訊管理可讓組織滿足業務和法規需求，並透過跨其 Microsoft 365 和協力廠商資料提供保留和刪除功能來減少其攻擊面。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

使用者可透過將資料分類以保留特定原則和規定，以加以受益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Microsoft 365 F3/Business 進階版、Office 365 E5/A5/G5/E3/A3/G3/E1/A1/G1/F3 和獨立的 Exchange 計畫，可為使用者提供權力，以手動將非記錄保留標籤套用至信箱資料。

Microsoft 365 F3/F1/Business 進階版、Office 365 E5/A5/G5/E3/A3/G3/F3/E1/A1/G1 和獨立的 SharePoint 計畫，可提供使用者的權力，以手動將非記錄保留標籤套用至 SharePoint 或 OneDrive 中的檔案。

Microsoft 365 E5/A5/G5/E3/A3/Business 進階版、Office 365 E5/A5/G5/E3/A3、Exchange Plan 2 和 Exchange Online 封存為使用者提供許可權，以供使用者從基本整個組織或全位置信箱保留原則中受益。

Microsoft 365 E5/A5/G5/E3/A3、Office 365 E5/A5/G5/E3/A3 和 SharePoint 方案2為使用者提供的許可權，可讓使用者受益于基本 SharePoint 或 OneDrive 保留原則，以及/或手動將非記錄保留標籤套用至 SharePoint 中的檔案或OneDrive。

組織可以根據其原則，使用保留原則來保留或刪除 Teams 郵件。 這包括在 Teams 聊天和交談中管理郵件。

下列授權可讓使用者從 Teams 保留原則中受益的權利如下：

- Microsoft 365 E5/G5/A5/E3/G3/A3/F3/F1、商務基本、商務標準和商務進階版
- Office 365 E5/G5/A5/E3/G3/A3/F3/E1/G1

針對具有下列授權的使用者，支援的最低保留或刪除期限為30天：

- Microsoft 365 F1/F3、商務基本、商務標準和商務進階版
- Office 365 E1/G1 及 F3

Microsoft 365 E5/A5/G5，Microsoft 365 E5/A5/G5/F5 相容性和 F5 安全性 & 法規遵從性、Microsoft 365 資訊保護和控管 E5/A5/G5，以及 Office 365 E5/A5 為使用者提供權力，以自動套用保留標籤或原則，並套用預設保留。標籤或原則，根據自訂事件開始保留標籤的保留期間，在標籤保留期間結束時觸發手動處理檢查，並透過原生資料連線器匯入協力廠商資料、宣告檔案 a 記錄、探索標示的內容，以及監控標記活動。

Microsoft 365 E5/A5/G5，Microsoft 365 E5/A5/G5/F5 相容性和 F5 安全性 & 合規性，Microsoft 365 E5/A5/G5 資訊保護和控管為使用者提供的權力，是根據 trainable 分類器自動套用保留標籤。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，會在租使用者中的所有使用者的租使用者層級上啟用資訊管理功能。 如需設定資訊管理以套用授權使用者的 autolabeling 和原則的資訊，請參閱[Microsoft information 控管 in Microsoft 365](/microsoft-365/compliance/manage-information-governance)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

資訊控管功能可套用至特定位置的授權使用者 (小組網站、群組網站等等 ) 。 如需設定資訊管理以套用授權使用者的 autolabeling 和原則的資訊，請參閱[Microsoft information 控管 in Microsoft 365](/microsoft-365/compliance/manage-information-governance)。

## <a name="insider-risk-management"></a>測試人員風險管理

「內部使用者風險管理」是 Microsoft 365 中的解決方案，可讓您偵測、調查和採取行動，以組織中的危險活動來降低內部風險。

自訂原則可讓您偵測組織中惡意和無意危險的活動，並採取行動（如有需要），包括對 Microsoft Advanced eDiscovery 的升級案例。 組織中的風險分析人員可以快速採取適當的動作，以確保使用者符合您組織的規範標準。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

使用者可以利用其活動加以監控，以提升其的風險。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 相容性和 F5 安全性 & 合規性，以及 Microsoft 365 E5/A5/G5 有問必答風險管理，可為使用者提供權利，以供「內部使用者風險管理」受益。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

必須在 Microsoft 365 合規性中心中建立內部使用者風險管理原則，並將其指派給使用者。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

在 Microsoft 365 合規性中心中建立原則時，請在 [**選擇使用者和群組**] 頁面上，選取 **[選擇使用者或群組**] 只選取授權的使用者，或者，如果您的所有使用者都獲得授權，您可以選取 [**所有使用者及擁有郵件功能的群組**] 核取方塊。 如需詳細資訊，請參閱 [立即開始使用「內幕風險管理](/microsoft-365/compliance/insider-risk-management-configure)」。

## <a name="microsoft-defender-for-identity"></a>適用於身分識別的 Microsoft Defender

Microsoft Defender for Identity (先前的 Azure 高級威脅防護) 是一項雲端服務，可協助您從多種類型的高級目標網路攻擊和有問必答威脅中保護企業混合式環境。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

SecOp 分析員和安全性專業人員會受益于 Microsoft Defender 身分識別偵測和調查高級威脅、受損身分識別和惡意內幕程式動作的能力。 使用者可以透過 Microsoft Defender 身分識別來監控其資料，以獲得好處。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Enterprise Mobility + SecurityE5/A5，Microsoft 365 E5/A5/G5，Microsoft 365 E5/A5/G5/F5 安全性，microsoft F5 security & 合規性，以及 microsoft defender for 使用者身分識別，可提供 microsoft defender 身分識別權益的權利。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，在租使用者中的所有使用者的租使用者層級上啟用 Microsoft Defender 身分識別功能。 如需設定 Azure ATP 的詳細資訊，請參閱 [Create a Microsoft Defender For Identity instance](/defender-for-identity/install-step1)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

Microsoft Defender 身分識別服務目前無法限制特定使用者的功能。 您必須授權您想要受益的每一位使用者。

## <a name="microsoft-defender-for-office-365"></a>適用於 Office 365 的 Microsoft Defender

Microsoft Defender for Office 365 (過去 Office 365 的「高級威脅防護」) 可協助保護組織，以防禦複雜的攻擊，例如網路釣魚和零日惡意程式碼。 Microsoft Defender for Office 365 也會透過關聯大量資料的信號，以協助識別、優先順序，並提供如何解決潛在威脅的建議，以提供切實可行的洞察力。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

Microsoft Defender for Office 365 會保護使用者免受複雜的攻擊，例如網路釣魚和零日惡意程式碼。 如需方案1和方案2中提供的完整服務清單，請參閱[Microsoft Defender for Office 365](/microsoft-365/security/office-365-security/office-365-atp)。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？ 

microsoft defender for Office 365 方案1和2、Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 安全性、Microsoft 365 F5 Security & 合規性，以及 Microsoft 365 商務進階版為使用者提供的許可權，以供 Office 365 的 Microsoft defender 使用。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，會在租使用者中的所有使用者在租使用者層級上啟用 Microsoft Defender for Office 365 功能。 如需針對授權使用者設定 microsoft defender Office 365 原則的詳細資訊，請參閱[Microsoft defender for Office 365](/microsoft-365/security/office-365-security/office-365-atp)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

若要限定 Office 365 的 Microsoft Defender，請遵循保管庫連結和保管庫附件部署原則：

- 如需設定授權使用者保管庫連結的詳細資訊，請參閱[保管庫 Microsoft Defender for Office 365 中的連結](/microsoft-365/security/office-365-security/atp-safe-links)。

- 如需設定授權使用者保管庫附件的詳細資訊，請參閱[保管庫 Office 365 中的 Microsoft Defender 附件](/microsoft-365/security/office-365-security/atp-safe-attachments)。

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) 是 Cloud Access Security Broker (CASB) 解決方案，可讓組織了解其雲端應用程式和服務，提供複雜的分析功能來識別和對抗網路威脅，並讓他們控制資料在任何雲端應用程式之間移動的方式。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

MCAS 會探索並評定影子 IT，提供第一方與第三方雲端應用程式間的威脅防護，並保護第一方與第三方雲端應用程式間的資訊。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Enterprise Mobility + SecurityE5，Microsoft 365 E5/A5/G5，Microsoft 365 E5/A5/G5/F5 安全性，Microsoft 365 E5/A5/G5/F5 法規遵從性，Microsoft 365 F5 安全性 & 合規性，以及 Microsoft 365 資訊保護和控管，可為使用者提供的權力，以供使用者從 MCAS 中受益。

Azure AD P1 為使用者提供的權力，可從 MCAS 中的探索功能中受益。

若要從 MCAS 的條件式存取應用程式控制功能中受益，使用者必須也會獲得 Azure Active Directory P1 的授權，此 Microsoft 365 E3 包括 Enterprise Mobility + Security F1/F3/E3/A3/G3、Enterprise Mobility + Security E5、/A3/G3、Microsoft 365 E5/A5/G5，以及 Microsoft 365 E5/A5/G5/F5 安全性，以及 Microsoft 365 F5 安全性 & 規範。

若要從自動用戶端標籤獲得好處，使用者必須獲得 Azure 資訊保護 P2 的授權，該/A5/G5 包含在 Enterprise Mobility + Security E5/A5/G5 中，Microsoft 365 E5，Microsoft 365 E5/A5/G5/F5 相容性，Microsoft 365 F5 安全性 &規範，並 Microsoft 365 資訊保護和控管。

> [!NOTE]
> 自動伺服器端標籤需要 Office 365 進階版授權 (或) 的資訊 `MIP_S_CLP2` 保護 `efb0351d-3b08-4503-993d-383af8de41e3` 。 如需參考，請參閱 [產品名稱和服務方案識別碼取得授權](/azure/active-directory/enterprise-users/licensing-service-plan-reference)。

如需詳細資訊，請參閱 [Microsoft Cloud App Security 授權資料工作表](https://www.aka.ms/mcaslicensing)。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，MCAS 功能會在租用戶層級針對租用戶內的所有使用者啟用。

如需為授權使用者設定 Microsoft Cloud App Security 原則的詳細資訊，請參閱 [Microsoft Cloud App Security 概觀](/cloud-app-security/what-is-cloud-app-security)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員可以利用服務中提供的限定範圍部署功能，將 MCAS 部署限定於授權使用者的範圍。 如需詳細資訊，請參閱[限定範圍的部署](/cloud-app-security/scoped-deployment)。

## <a name="microsoft-defender-for-endpoint"></a>適用於端點的 Microsoft Defender

microsoft defender for endpoint (以前的 microsoft defender ATP) 是一個包含風險弱點管理和評估的端點安全性解決方案。攻擊面降減功能;以行為為基礎和雲端電源的下一代保護;端點偵測和回應 (EDR) ;自動調查和修正;和受管理的搜尋服務。 若要深入瞭解，請參閱 [Microsoft Defender For Endpoint](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) 頁面。

### <a name="which-users-benefit-from-the-service"></a>哪些使用者可從此服務獲益？

Windows 10 企業版 E5 的授權使用者 Windows 10 教育版 A5 Microsoft 365 E5/G5，包含 Windows 10 企業版 E5、Microsoft 365 E5/A5/G5/F5 安全性，以及 Microsoft 365 F5 安全性 &合規性可以從 Microsoft Defender for Endpoint 受益。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

SecOps 分析員和安全性專業人員受益于 Microsoft Defender for Endpoint 的端點安全性功能，以執行預防性保護、入侵後偵測、自動調查，以及回應高級威脅。 使用者利用 Microsoft Defender for Endpoint 所監控的惡意事件，使使用者受益。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，會在租使用者中的所有使用者在租使用者層級上啟用 Microsoft Defender for Endpoint 功能。 如需部署的詳細資訊，請參閱 [部署階段](/windows/security/threat-protection/microsoft-defender-atp/deployment-phases)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

Microsoft Defender for Endpoint 系統管理員可以使用以角色為基礎的存取控制 (RBAC) ，以在安全作業小組中建立角色和群組，以授與 Microsoft Defender 資訊安全中心的適當存取權。 如需詳細資訊，請參閱 [使用以角色為基礎的存取控制管理入口網站存取](/windows/security/threat-protection/microsoft-defender-atp/rbac)。

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp"></a>Microsoft Graph APIs Teams 資料遺失防護 (DLP) 

此 API 可讓開發人員建立可在近乎即時聽取 Microsoft Teams 訊息的應用程式，並為客戶及 isv 啟用 DLP 案例實施。 此外，Microsoft Graph Patch API 也可將 DLP 動作套用至 Teams 郵件。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

[資料遺失防護 (DLP) ](/microsoft-365/compliance/dlp-microsoft-teams)功能廣泛用於 Microsoft Teams，尤其是當組織已轉向遠端工作時。 如果您的組織有 DLP，您現在可以定義原則，以防止人員在 Microsoft Teams 通道或聊天會話中共用機密資訊。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5/F5 合規性
- Microsoft 365F5 安全性 & 合規性
- Microsoft 365 E5/A5/G5 資訊保護和管理
- Office 365 E5/A5/G5

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

可在租使用者層級設定 API 存取。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

Teams DLP 的 Microsoft Graph API 是租使用者層級的值。 每一位由此服務受益的使用者皆須獲得授權。

## <a name="office-365-advanced-message-encryption"></a>Office 365 進階郵件加密

Office 365 進階郵件加密可協助客戶符合法規遵從性義務，需要更多彈性控制外部收件者，以及其對加密電子郵件的存取權。 有了進階郵件加密，系統管理員可以使用能偵測敏感性資訊類型的自動原則 (例如，個人識別資訊或是財務或健康身分編號) 控制在組織外部共用的敏感性電子郵件，或者他們可以透過安全網頁入口網站對加密的電子郵件套用自訂電子郵件範本和會到期的存取，以使用關鍵字來加強保護。 此外，系統管理員可隨時撤銷存取，進一步控制透過安全網頁入口網站存取的加密電子郵件。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

郵件寄件者可從進階郵件加密所提供對敏感性電子郵件新增的控制而獲益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合規性和 F5 安全性 & 法規遵從性，以及 Microsoft 365 E5/A5/G5 資訊保護和控管，可提供使用者的許可權，以從高級郵件加密中受益。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

系統管理員會在 [**郵件流程** 規則] 底下的 Exchange 系統管理中心建立及管理高級郵件加密原則  >  ****。 根據預設，這些規則會套用至租用戶中的所有使用者。 如需設定新的郵件加密功能的詳細資訊，請參閱[設定全新的 Office 365 郵件加密功能](/office365/securitycompliance/set-up-new-message-encryption-capabilities)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員應僅將進階郵件加密的郵件流程規則套用至授權使用者。 如需定義郵件流程規則的詳細資訊，請參閱[定義郵件流規則以加密 Office 365 中的電子郵件](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)。

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security (OCAS) 是 Microsoft Cloud App Security 的子集，具有的功能限級於 Office 365，且沒有針對協力廠商雲端應用程式和 IaaS 服務的額外安全性功能。

OCAS 可讓組織了解其雲端應用程式和服務，提供複雜的分析功能來識別和對抗網路威脅，並讓他們控制資料在 Office 365 之間移動的方式。

若要比較功能，請參閱 [Microsoft Cloud App Security 與 Office 365 Cloud App Security 之間的差異為何](/cloud-app-security/editions-cloud-app-security-o365)。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

OCAS 探索陰影它、提供 Office 365 的威脅防護，以及可以控制哪些應用程式具有存取資料的許可權。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Office 365 E5/A3/A5/G5 為使用者提供的權力，可從 OCAS 中受益。
如需詳細資訊，請參閱 [Microsoft Cloud App Security 授權資料工作表](https://www.aka.ms/mcaslicensing)。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，OCAS 功能會在租用戶層級針對租用戶內的所有使用者啟用。

如需設定服務的詳細資訊，請參閱 [Cloud App Security 的基本設定](/cloud-app-security/general-setup)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員可以限定 OCAS 部署的範圍，以強制存取特定應用程式的方式，並限制由 Office 365 Cloud App Security 所監控的使用者群組。 如需詳細資訊，請參閱[限定範圍的部署](/cloud-app-security/scoped-deployment)。

## <a name="office-365-customer-lockbox"></a>Office 365 客戶加密箱

透過讓客戶為服務作業提供明確的存取授權，客戶加密箱可提供額外的一層控制。 透過示範明確的資料存取授權，客戶加密箱也可能會協助組織符合特定合規性義務，例如 HIPAA 和 FedRAMP。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

客戶加密箱可確保 Microsoft 沒有人能夠存取客戶內容以執行服務作業，而不需要客戶進行明確核准。 客戶加密箱會將客戶帶至要求存取其內容的核准工作流程。 有時候，Microsoft 工程師會於支援程序期間加入，以疑難排解並修正客戶報告的問題。 在大部分情況下，問題可透過 Microsoft 既有、用於其服務的廣泛遙測和偵錯工具修正。 不過，在某些情況下，可能會需要 Microsoft 工程師來存取客戶內容以判斷根本原因並修正問題。 客戶加密箱會要求工程師在核准工作流程的最後一個步驟向客戶要求存取。 這為組織提供核准或拒絕這些要求的選項，可讓使用者直接控制 Microsoft 工程師是否可以存取組織的使用者資料。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合規性和 F5 安全性 & 法規遵從性，以及 Microsoft 365 E5/A5/G5 內幕人員風險管理，可為使用者提供從客戶密碼箱受益的權利。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

系統管理員可以在 Microsoft 365 系統管理中心中開啟客戶加密箱。 如需詳細資訊，請參閱 [Office 365 中的客戶加密箱](/microsoft-365/compliance/customer-lockbox-requests)。 當客戶加密箱開啟時，Microsoft 必須先取得組織的核准，再存取其任何內容。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

目前，客戶加密箱服務不能限制在特定使用者。 雖然租使用者服務目前無法將權益限制于特定的使用者，但應該採取工作以將服務權益限制為已授權的使用者。 這有助於避免在有目標功能可供使用時，可能會造成服務中斷的情況。

## <a name="office-365-message-encryption"></a>Office 365 郵件加密

Office 365 郵件加密 (OME) 是內建於 Azure 版權管理 (Azure RMS) 的服務，可讓您將加密的電子郵件傳送給組織內部或外部的人，無論目的地電子郵件地址為何 (Gmail、Yahoo! Mail、Outlook.com 等)。

若要檢視加密的郵件，收件者可以取得一次性密碼、使用 Microsoft 帳戶登入、或使用與 Office 365 相關聯的公司或學校帳戶登入。 收件者也可以傳送加密的回覆。 不需要訂閱即可查看加密的郵件或傳送加密的回復。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

郵件寄件者可從 Office 365 郵件加密所提供對敏感性電子郵件新增的控制而獲益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Microsoft 365 E3/A3/G3、Office 365 E3/A3/G3 和 Azure 資訊保護方案1為使用者提供從 Office 365 郵件加密中受益的權利。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

系統管理員會在 Exchange 系統管理中心的 [郵件流程]  >  [規則] 下建立及管理 Office 365 郵件加密原則。 根據預設，這些規則會套用至租用戶中的所有使用者。 如需設定新 Office 365 郵件加密功能的相關資訊，請參閱[Set up new Message Encryption 功能](/office365/securitycompliance/set-up-new-message-encryption-capabilities)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員應僅將 Office 365 郵件加密的郵件流程規則套用至授權使用者。 如需定義郵件流程規則的詳細資訊，請參閱 [定義郵件流程規則以加密電子郵件訊息](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)。

## <a name="privileged-access-management-in-office-365"></a>Office 365 的 Privileged Access Management

「[特權存取管理」 (PAM) ](/microsoft-365/compliance/privileged-access-management-configuration)提供 Office 365 中的版權管理工作的細微存取控制。 啟用 PAM 後，若要完成提升和特權的工作，使用者將需要透過高範圍和時間限制的核准工作流程要求即時存取。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

啟用 PAM 可讓組織使用無常設權限作業。 使用者可從能抵禦為其資料提供不受束縛的常設系統管理存取所產生弱點新增的防禦層獲益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？ 

Office 365 E5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5/F5 合規性和 F5 安全性 & 法規遵從性，以及 Microsoft 365 E5/A5 資訊保護和控管為使用者提供的權利可從 PAM 中受益。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，PAM 功能會在租用戶層級針對租用戶內的所有使用者啟用。 如需設定 PAM 原則的詳細資訊，請參閱 [開始使用特殊許可權存取管理](/microsoft-365/compliance/privileged-access-management-configuration)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

客戶可以透過核准者群組和存取原則，以每位使用者為基礎管理 PAM (該原則可套用至授權的使用者)。 如需詳細資訊，請參閱[Office 365 中的「特權存取管理](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)」。

## <a name="records-management"></a>記錄管理

記錄管理可協助組織跨其 Microsoft 365 和協力廠商資料的發現、分類、標記、保留和 defensible 刪除功能，以滿足其業務及規定的記錄保留義務。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Microsoft 365 E5/A5/G5，Microsoft 365 E5/A5/G5/F5 相容性和 F5 安全性 & 法規遵從性、Microsoft 365 資訊保護和控管 E5/A5/G5，以及 Office 365 E5/A5/G5 為使用者提供權力，讓使用者能夠受益于記錄管理，包括宣告專案為記錄或法規記錄。自動套用保留或記錄標籤，並執行處置評審程式 (排除根據 trainable 的分類器) 自動套用保留標籤。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 規範和 F5 Security & 合規性，以及 Microsoft 365 資訊保護和控管，可為使用者提供權力，以根據 trainable 的分類程式自動套用保留或記錄標籤。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

使用者可將內容宣告成記錄，並透過 defensible 處理從原則定義和宣告中管理其完整的記錄處理常式，以獲得好處。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，會在租使用者中的所有使用者的租使用者層級上啟用記錄管理功能。 如需設定記錄管理以套用授權使用者的相關資訊，請參閱[瞭解 Microsoft 365 中的記錄管理](/microsoft-365/compliance/records-management)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

記錄管理功能可套用至特定位置的授權使用者 (小組網站、群組網站等等 ) 。 如需設定記錄管理以套用授權使用者的相關資訊，請參閱[瞭解 Microsoft 365 中的記錄管理](/microsoft-365/compliance/records-management)。
