---
title: 安全性 & 合規性的 Microsoft 365 授權指南
ms.author: v-trscho
author: vtrscho
audience: ITPro
ms.topic: reference
ms.date: 7/13/2020
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 本文提供 Microsoft 365 合規性的授權指導方針，以協助避免因未經許可存取而造成的潛在服務中斷。
ms.openlocfilehash: f2da71ee9bdc8f8250d3f4a98e8f09b0a43edede
ms.sourcegitcommit: 1e0e3f5a43431e9a732ee2ca4459332c410b07e7
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/24/2020
ms.locfileid: "48245728"
---
# <a name="microsoft-365-licensing-guidance-for-security--compliance"></a>安全性 & 合規性的 Microsoft 365 授權指南

針對此文章的目的，租用戶層級服務為一項線上服務，&mdash;為租用戶中的任何使用者購買 (獨立購買或隨著 Office 365 或 Microsoft 365 方案購買)&mdash; 時，會為租用戶中的部分或所有使用者啟用。 雖然部分未取得授權的使用者在技術上可能可存取服務，但想要從服務獲益的任何使用者都必須具備授權。

> [!NOTE]
> 部分租用戶服務目前無法將權益限制在特定使用者。 應該努力將服務權益限制在取得授權的使用者。 這麼做有助於在鎖定功能可用時避免對組織造成潛在的服務中斷。

若要查看授權您的使用者從 Microsoft 365 規範功能受益于2020年4月1日的選項，請下載詳細的 Microsoft 365 相容性授權比較。 [ (PDF) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [ (Excel) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory Identity Protection 是 Azure Active Directory Premium P2 的功能，可讓您偵測影響組織之身分識別的潛在弱點、設定自動回應，以偵測到與您組織的身分識別相關的可疑動作，以及調查可疑的事件，並採取適當的措施加以解決。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

由於有了基於機器學習演算法、標幟的使用者和風險事件的彙總檢視，安全作業分析人員和安全性專業人員可從中獲益。 使用者則可獲益於透過風險式條件存取提供的自動防護，以及可對弱點採取行動而改善的安全性。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Enterprise 可移動性 + Security E5/A5，Microsoft 365 E5/A5，Microsoft 365 E5/A5 Security 和 Azure Active Directory Premium 方案2為使用者提供從 Azure Active Directory 身分識別保護中受益的權利。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，會在租使用者中的所有使用者在租使用者層級上啟用 Azure AD 身分識別保護功能。 如需 Azure AD 身分識別保護的詳細資訊，請參閱 [什麼是 Azure Active Directory 身分識別保護？](https://docs.microsoft.com/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員可以指派定義密碼重設層級的風險原則，並只允許授權使用者的存取，以限定 Azure AD 身分識別保護的範圍。 如需如何針對 Azure AD 身分識別保護部署進行範圍的指示，請參閱 [Configure the sign in 危險原則](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy)。

## <a name="azure-advanced-threat-protection"></a>Azure 進階威脅防護

Azure 進階威脅防護 (ATP) 是一項雲端服務，可協助保護企業混合式環境，免於多種類型的進階鎖定目標的網路攻擊和內部威脅。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

安全作業分析人員和安全性專業人員可從 Azure ATP 偵測和調查進階威脅、遭入侵的身分識別和惡意內部人員動作的能力獲益。 使用者透過讓 Azure ATP 監控其資料而獲益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Enterprise 可移動性 + Security E5/A5，Microsoft 365 E5/A5，Microsoft 365 E5/A5 安全性，以及 Azure 高級威脅防護為使用者提供從 Azure ATP 受益的權利。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，Azure ATP 功能會在租用戶層級針對租用戶內的所有使用者啟用。 如需設定 Azure ATP 的詳細資訊，請參閱[建立您的 Azure ATP 執行個體](https://docs.microsoft.com/azure-advanced-threat-protection/install-atp-step1)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

Azure ATP 服務目前不能限制特定使用者的功能。 您必須授權您想要受益的每一位使用者。

## <a name="office-365-advanced-threat-protection"></a>Office 365 進階威脅防護

進階威脅防護 (ATP) 可協助保護您的組織免受複雜的攻擊，例如網路釣魚和零時差惡意程式碼。 ATP 也可透過關聯大量資料的信號，協助識別、設定優先順序，並提供如何解決潛在威脅的建議，以提供行動的洞察力。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

ATP 可保護使用者免受複雜的攻擊，例如網路釣魚和零時差惡意程式碼。 如需方案 1 和方案 2 所提供服務的完整清單，請參閱 [Office 365 進階威脅防護](https://products.office.com/exchange/advance-threat-protection)。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？ 

Office 365 Advanced 威脅防護、Office 365 E5/G5、Microsoft 365 E5/A5/G5、microsoft 365 E5/A5/G5 安全性、Microsoft 365 商務版 Premium 和 Office 365 ATP 方案1和2為使用者提供的許可權，可從高級威脅防護中受益。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，ATP 功能會在租用戶層級針對租用戶內的所有使用者啟用。 如需為授權使用者設定 ATP 原則的詳細資訊，請參閱 [Office 365 進階威脅防護](https://docs.microsoft.com/office365/securitycompliance/office-365-atp)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

若要限定 ATP 的範圍，請遵循安全連結和安全附件部署原則：

- 如需為授權使用者設定安全連結的相關資訊，請參閱[設定 Office 365 ATP 安全連結原則](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-atp-safe-links-policies)。

- 如需為授權使用者設定安全附件的相關資訊，請參閱[設定 Office 365 ATP 安全附件原則](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-atp-safe-attachments-policies)。

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security (OCAS) 是 Microsoft Cloud App Security 的子集，具有的功能限級於 Office 365，且沒有針對協力廠商雲端應用程式和 IaaS 服務的額外安全性功能。

OCAS 可讓組織了解其雲端應用程式和服務，提供複雜的分析功能來識別和對抗網路威脅，並讓他們控制資料在 Office 365 之間移動的方式。

若要比較功能，請參閱 [Microsoft Cloud App Security 與 Office 365 Cloud App Security 之間的差異為何](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365)。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

OCAS 探索陰影它、提供各 Office 365 的威脅防護，以及可以控制哪些應用程式具有存取資料的許可權。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Office 365 E5/A5/G5 為使用者提供的權力可從 OCAS 中受益。
如需詳細資訊，請參閱 [Microsoft Cloud App Security 授權資料工作表](https://www.aka.ms/mcaslicensing)。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，OCAS 功能會在租用戶層級針對租用戶內的所有使用者啟用。

如需設定服務的詳細資訊，請參閱 [Cloud App Security 的基本設定](https://docs.microsoft.com/cloud-app-security/general-setup)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員可以限定 OCAS 部署的範圍，以強制存取特定應用程式的方式，並限制由 Office 365 Cloud App Security 所監控的使用者群組。 如需詳細資訊，請參閱[限定範圍的部署](https://docs.microsoft.com/cloud-app-security/scoped-deployment)。

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) 是 Cloud Access Security Broker (CASB) 解決方案，可讓組織了解其雲端應用程式和服務，提供複雜的分析功能來識別和對抗網路威脅，並讓他們控制資料在任何雲端應用程式之間移動的方式。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

MCAS 會探索並評定影子 IT，提供第一方與第三方雲端應用程式間的威脅防護，並保護第一方與第三方雲端應用程式間的資訊。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

MCAS，Enterprise 可移動性 + Security E5/A5/G5，Microsoft 365 E5/A5/G5，Microsoft 365 E5/A5/G5 安全性，Microsoft 365 E5/A5/G5 相容性，以及 Microsoft 365 資訊保護和控管為使用者提供的權力，可從 MCAS 中受益。

Azure AD P1 為使用者提供的權力，可從 MCAS 中的探索功能中受益。

若要從 MCAS 中的條件式存取應用程式控制功能獲益，使用者也必須取得 Azure Active Directory P1 的授權，其包括在 Enterprise Mobility + Security E3/A3/G3、Enterprise Mobility + Security E5/A5/G5、Microsoft 365 E3/A3/G3, Microsoft 365 E5/A5/G5 和 Microsoft 365 E5/A5/G5 Security 中。

若要從自動標籤獲得好處，使用者必須獲得 Azure 資訊保護 P2 的授權，其包含在 Enterprise 可移動性 + Security E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 相容性，以及 Microsoft 365 資訊保護和控管。

如需詳細資訊，請參閱 [Microsoft Cloud App Security 授權資料工作表](https://www.aka.ms/mcaslicensing)。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，MCAS 功能會在租用戶層級針對租用戶內的所有使用者啟用。

如需為授權使用者設定 Microsoft Cloud App Security 原則的詳細資訊，請參閱 [Microsoft Cloud App Security 概觀](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員可以利用服務中提供的限定範圍部署功能，將 MCAS 部署限定於授權使用者的範圍。 如需詳細資訊，請參閱[限定範圍的部署](https://docs.microsoft.com/cloud-app-security/scoped-deployment)。

## <a name="compliance-manager"></a>合規性管理員

使用合規性管理員簡化法規遵從性並降低風險。 合規性管理員可協助組織符合法規、標準、公司原則或其他必要控制項框架的需求。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

下列為使用者對合規性管理員服務的好處：

- 將複雜的法規、標準、公司原則或其他所需的控制項框架轉譯成簡易語言
- 可讓您存取廣泛的現成評估和自訂評估，以符合獨特的合規性需求
- 將規章控制對應至建議的改進動作
- 提供如何實施解決方案以符合法規需求的逐步指導方針
- 將分數與每個動作相關聯，以協助使用者設定對其組織合規性影響最高的動作優先順序。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

使用 Office 365 E1/A1/E3/A3 和 Microsoft 365 E3/A3 授權的客戶將可以存取資料保護基準評估。 使用 Office 365 E5/A5 和 Microsoft 365 E5/A5 授權的客戶，將可以存取資料保護基準、GDPR、NIST 800-53 及 ISO 22701 現成評估。 特優評估可用於購買至 Office 365 E5/A5 和 Microsoft 365 E5/A5 客戶。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

合規性管理員預設是針對您的承租人進行布建。 Admins 設定使用者權限並指派角色，使組織中的非系統管理員使用者可以開始使用合規性管理員。 如需詳細資訊，請參閱 [合規性管理員入門：設定使用者權限並指派角色](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

存取合規性管理員是透過設定使用者權限及指派角色加以控制。 如需詳細資訊，請參閱 [合規性管理員入門：設定使用者權限並指派角色](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)。

## <a name="microsoft-defender-atp"></a>Microsoft Defender ATP

Microsoft Defender ATP 是一個端點安全性解決方案，包含風險型弱點管理和評估;攻擊面降減功能;以行為為基礎和雲端電源的下一代保護;端點偵測和回應 (EDR) ;自動調查和修正;和受管理的搜尋服務。 請參閱 [Microsoft DEFENDER ATP](https://www.microsoft.com/microsoft-365/windows/microsoft-defender-atp?rtc=1) 頁面以深入瞭解。

### <a name="which-users-benefit-from-the-service"></a>哪些使用者可從此服務獲益？

Windows 10 企業版 E5 的授權使用者，Windows 10 教育版 A5，Microsoft 365 E5 (M365 E5) （包括 Windows 10 企業版 E5、Microsoft 365 E5 Security、Microsoft 365 A5 (M365 A5) 可從 Microsoft Defender ATP 取得效益）。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

SecOps 分析員和安全性專業人員會受益于 Microsoft Defender ATP 的端點安全性功能，以執行預防性保護、入侵後偵測、自動調查，以及對高級威脅的回應。 使用者利用 Microsoft Defender ATP 所監控的惡意事件，使使用者受益。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，會在承租人層級為租使用者內的所有使用者啟用 Microsoft Defender ATP 功能。 如需部署的詳細資訊，請參閱 [部署指南](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/deployment-phases)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

Microsoft Defender ATP 系統管理員可以利用以 [角色為基礎的存取控制 (RBAC) ](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/rbac) ，在安全性作業小組中建立角色和群組，以授與 Microsoft Defender security Center 的適當存取權。

## <a name="information-protection"></a>資訊保護

資訊保護可協助組織探索、分類、標籤及保護機密檔和電子郵件。 系統管理員可以定義規則和條件，以自動套用標籤，使用者可以手動套用標籤，或使用二者的組合，使用者會在其中獲得套用標籤的建議。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

使用者可透過將敏感度標籤手動套用至其內容，或透過自動分類其內容來獲得好處。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium，Enterprise 可移動性 + Security F3/E3/E5，Office 365 E5/A5/E3/A3/F3，AIP Plan 1，and AIP Plan 2 為使用者提供從手動敏感度標記中受益的權利。

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium、Enterprise 可移動性 + Security F3/E3/E5、AIP Plan 1 和 AIP Plan 2 為使用者提供的權力，可讓使用者在 Power BI 中套用和查看敏感度標籤，並在將資料從 Power BI 匯出至 Excel、PowerPoint 或 PDF 時，加以受益。 

> [!NOTE]
> Power BI 隨附于 Microsoft 365 E5/A5/G5;在所有其他計畫中，Power BI 必須另行授權。

Microsoft 365 E5/A5/G5，Microsoft 365 E5/a5/g5，Microsoft 365 資訊保護和控管，Office 365 E5，Office 365 Advanced 合規性，Enterprise 可移動性 + Security E5，及 AIP Plan 2 為使用者提供的權力，可供使用者從自動敏感度標記中受益。

如需授權的特定權利，請參閱詳細的 Microsoft 365 相容性授權比較。 [ (PDF) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [ (Excel) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)不包含根據機器學習 (trainable 的分類器) 自動分類的許可權。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，會在租使用者中的所有使用者的租使用者層級上啟用資訊保護功能。 如需設定授權使用者之原則的詳細資訊，請參閱啟用 Azure Rights Management。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

除了使用 AIP 掃描器功能時，您可以編輯原則，以防止未授權的使用者執行分類或標記功能。 如需如何限定 AIP 部署範圍的相關指示，請參閱[設定 Azure 資訊保護原則](https://docs.microsoft.com/azure/information-protection/configure-policy)。

針對 AIP 掃描器功能，Microsoft 並未承諾會為未授權的使用者提供檔案分類、標記或保護功能。

## <a name="information-governance"></a>資訊管理

資訊控管會透過發現、分類、標示和管理其資料來協助組織管理其風險。 資訊管理可讓組織滿足業務和法規需求，並透過在其 Microsoft 365 和協力廠商資料中提供保留和刪除功能來減少攻擊面。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

使用者可透過將資料分類以保留特定原則和規定，以加以受益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Microsoft 365 F3/Business Premium，Office 365 E1/A1/F3 和獨立 Exchange 計畫可為使用者提供權力，以手動將非記錄保留標籤套用至信箱資料。

Microsoft 365 F3/F1/Business Premium、Office 365 E1/A1/F3 和獨立的 SharePoint 計畫，可讓使用者在 SharePoint 或 OneDrive 中，將非記錄保留標籤手動套用至檔案，以獲得有益的權力。 

Microsoft 365 E5/A5/E3/A3/Business Premium、Office 365 E5/A5/E3/E3、Exchange Plan 2 和 Exchange Online 封存為使用者提供的許可權，可從基本整個組織或位置範圍的信箱保留原則和/或以手動方式將非記錄保留標籤套用至信箱資料。

Microsoft 365 E5/A5/E3/A3、Office 365 E5/A5/E3/A3 和 SharePoint 方案2為使用者提供的權力，可從基本 SharePoint 或 OneDrive 保留原則，以及/或手動將非記錄保留標籤套用至 SharePoint 或 OneDrive 中的檔案。

Microsoft 365 E5/A5/E3/A3 和 Office 365 E5/A5/E3/A3 可為使用者提供從小組保留原則中受益的權力。

Microsoft 365 E5/A5，Microsoft 365 E5/A5 相容性，Microsoft 365 資訊保護和控管，Office 365 E5/A5，和 Office 365 的「高級法規遵從性」為使用者提供的權力，可讓使用者從自動套用保留標籤或原則，獲得好處。套用預設保留標籤或原則，根據自訂事件開始保留標籤的保留期間，在標籤保留期間結束時觸發手動處置檢查、將協力廠商資料匯入到原生資料連線器、宣告檔案 a 記錄、探索標示的內容，以及監視標記活動。

Microsoft 365 E5/A5，Microsoft 365 E5/A5 符合性，Microsoft 365 資訊保護和控管為使用者提供的權力，是根據 trainable 的分類器自動套用保留標籤。

如需授權的特定權利，請參閱詳細的 Microsoft 365 相容性授權比較。 [ (PDF) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [ (Excel) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，會在租使用者中的所有使用者的租使用者層級上啟用資訊管理功能。 如需設定資訊管理以套用授權使用者的 autolabeling 和原則的資訊，請參閱 [管理資訊](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance)管理。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

資訊控管功能可套用至特定位置的授權使用者 (小組網站、群組網站等等 ) 。 如需設定資訊管理以套用授權使用者的 autolabeling 和原則的資訊，請參閱 [管理資訊](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance)管理。

## <a name="records-management"></a>記錄管理

記錄管理可協助組織在其 Microsoft 365 和協力廠商資料中探索、分類、標記、保留及 defensible 刪除功能，以滿足業務和法規記錄的要求。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Microsoft 365 E5/A5，Microsoft 365 E5/A5 相容性，Microsoft 365 資訊保護和控管，Office 365 E5/A5，Office 365 的「高級法規遵從性」為使用者提供的許可權可讓使用者受益于記錄管理，包括宣告專案為記錄、自動套用保留或記錄標籤，以及執行處置審閱程式 (排除以 trainable 的分類器) 自動套用保留

Microsoft 365 E5/A5，Microsoft 365 E5/A5 符合性，Microsoft 365 資訊保護和控管為使用者提供的權力，是根據 trainable 的分類器自動套用保留或記錄標籤。

如需授權的特定權利，請參閱詳細的 Microsoft 365 相容性授權比較。 [ (PDF) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [ (Excel) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

使用者可將內容宣告成記錄，並透過 defensible 處理從原則定義和宣告中管理其完整的記錄處理常式，以獲得好處。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，會在租使用者中的所有使用者的租使用者層級上啟用記錄管理功能。 如需設定記錄管理以套用授權使用者的詳細資訊，請參閱 [Microsoft 365 中的記錄管理](https://docs.microsoft.com/microsoft-365/compliance/records-management)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

記錄管理功能可套用至特定位置的授權使用者 (小組網站、群組網站等等 ) 。 如需設定記錄管理以套用授權使用者的詳細資訊，請參閱 [Microsoft 365 中的記錄管理](https://docs.microsoft.com/microsoft-365/compliance/records-management)。

## <a name="data-connectors"></a>資料連線器 

Microsoft 提供可在 Microsoft 365 規範中心內設定的協力廠商資料連線器。 如需 Microsoft 所提供的資料連線器清單，請參閱 [協力廠商資料連線器](https://docs.microsoft.com/microsoft-365/compliance/archiving-third-party-data) 表格。 此表格也會摘要說明在 Microsoft 365 中匯入及封存資料後，您可以套用至協力廠商資料的相容性解決方案，以及每個連接器的逐步指示連結。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

在 Microsoft 365 中，使用資料連線器匯入及封存協力廠商資料的主要優點是，您可以在匯入後，對其套用各種 Microsoft 365 規範解決方案。 這可協助確保您組織的非 Microsoft 資料符合影響組織的規章和標準。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

下列授權可為使用者提供的許可權，以受益于資料連線器：

- Microsoft 365 E5/A5
- Microsoft 365 E5/A5 Info Protection & 控管
- Microsoft 365 E5/A5 規範
- Microsoft 365 E5/A5 內幕人士風險管理 
- Microsoft 365 E5/A5 eDiscovery 和 Audit 
- Office 365 E5/A5
- Office 365 進階合規性

針對 M365 安全性 & 規範中心（由其中一個 Microsoft 合作夥伴提供）中的資料連線器，您的組織必須與合作夥伴進行業務關係，才能部署這些連接器。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

連接器是使用安全性 & 規範中心和連接器目錄設定。

### <a name="how-can-the-service-be-applied-only---to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用至已授權提供服務的承租人中的使用者？

資料連線器服務是租使用者層級的值。 每一位由此服務受益的使用者皆須獲得授權。

## <a name="microsoft-graph-apis-for-teams-dlp"></a>團隊 DLP 的 Microsoft Graph APIs

今年早些時候，我們 [宣佈小組中郵件的 Microsoft Graph 變更通知 API 公開預覽](https://developer.microsoft.com/en-us/graph/blogs/announcing-change-notifications-for-microsoft-teams-messages)。 此 API 可讓開發人員建立應用程式，該應用程式可以即時聆聽 Microsoft 小組郵件，並為客戶及 Isv 啟用 DLP 案例實施。 此外，Microsoft Graph 修補程式 API 允許將 DLP 動作套用至小組郵件。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

[資料遺失防護 (DLP) ](https://docs.microsoft.com/microsoft-365/compliance/dlp-microsoft-teams?view=o365-worldwide) 功能廣泛用於 Microsoft 小組，尤其是當組織已移動至遠端工作時。 如果您的組織有 DLP，您現在可以定義原則，以防止人員在 Microsoft 小組通道或聊天會話中共用機密資訊。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

您將需要下列其中一個 E5 授權，才能支援資料遺失防護 (DLP) protection 在小組聊天中：

- Microsoft 365 E5/A5
- Microsoft 365 E5/A5 規範
- Microsoft 365 E5/A5 資訊保護和控管
- Office 365 E5/A5 

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

可在租使用者層級設定 API 存取。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

Microsoft Graph API for 小組 DLP 是租使用者層級的值。 每一位由此服務受益的使用者皆須獲得授權。

## <a name="ediscovery"></a>電子文件探索

eDiscovery 在公司內為 IT 和法律部門提供調查和 eDiscovery 解決方案，以找出、收集、保留、減少及檢查與調查或訴訟相關的內容，然後再將其匯出至 Microsoft 365 系統。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

當使用者被選取為資料監管人 (具有文件或電子檔案系統管理控制權的人員) 時，使用者即可從進階電子文件探索獲益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Microsoft 365 E5/A5/G5/E3/A3/G3、Office 365 E5/A5/G5/E3/G3，以及 Office 365 Advanced 規章，為使用者提供從核心 eDiscovery 受益的權利。
Microsoft 365 E5/A5/G5，Microsoft 365 E5/a5/g5，Microsoft 365 E5/a5 電子檔探索與審核，Office 365 E5/A5/G5，以及 Office 365 的「高級法規遵從性」為使用者提供從「高級 eDiscovery」受益的權利。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，當系統管理員在安全性與合規性中心中指派電子文件探索權限時，系統會在租用戶內所有使用者的租用戶層級啟用進階電子文件探索功能。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

電子文件探索系統管理員可以使用進階電子文件探索中內建的監管人管理工具，將特定使用者選取為案例的資料監管人，如[將監管人新增至進階電子文件探索案例](https://docs.microsoft.com/microsoft-365/compliance/add-custodians-to-case)中所述。

## <a name="office-365-customer-key"></a>Office 365 客戶金鑰

有了客戶金鑰，您即可控制組織的加密金鑰，並將 Office 365 設定為使用這些金鑰來加密在 Microsoft 資料中心的待用資料。 換句話說，客戶金鑰可讓您新增屬於您、使用您自己的金鑰的一層加密。 存放的資料包括 Exchange Online 資料和儲存在信箱的商務用 Skype 資料，以及儲存在 SharePoint Online 和商務用 OneDrive 中的檔案。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

使用者可讓其待用資料在應用程式層使用其自己的組織所提供、控制及管理的加密金鑰加密，藉此從客戶金鑰獲益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Microsoft 365 E5/A5，Microsoft 365 E5/A5 相容性，Microsoft 365 資訊保護和控管，Office 365 E5/A5，以及 Office 365 的「高級法規遵從性」為使用者提供的權力，可從客戶金鑰獲得。 若要獲得客戶金鑰的完整優勢，您也必須具有 Azure 金鑰保存庫的訂閱。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

您可以對儲存在 Exchange Online 和商務用 Skype 信箱中的所有資料啟用 Office 365 客戶金鑰加密金鑰，並 SharePoint 線上、商務用 OneDrive，以及小組檔案。 如需有關 Office 365 客戶金鑰的詳細資訊，包括如何開始，請參閱 [Office 365 中的客戶金鑰服務加密](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

若要將加密金鑰指派給 Office 365 和/或 Microsoft 365 組織中的資料以供授權的使用者使用，請遵循客戶金鑰加密金鑰的部署指示。

- 如需 SharePoint 線上、商務 OneDrive 或小組檔案，可使用客戶金鑰加密一或多個網站上的檔案。

- 若為 Exchange Online 和商務用 Skype，可使用客戶金鑰加密信箱。

## <a name="office-365-customer-lockbox"></a>Office 365 客戶加密箱

透過讓客戶為服務作業提供明確的存取授權，客戶加密箱可提供額外的一層控制。 藉由示範該程序可用於明確資料存取授權，客戶加密箱也可協助組織符合特定合規性義務，例如 HIPAA 與 FEDRAMP。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

使用者受益于客戶密碼箱，以確保 Microsoft 沒有人能夠存取其內容來執行服務作業，而不需要客戶進行明確核准。 客戶加密箱會將客戶帶至要求存取其內容的核准工作流程。 有時候，Microsoft 工程師會於支援程序期間加入，以疑難排解並修正客戶報告的問題。 在大部分情況下，問題可透過 Microsoft 既有、用於其服務的廣泛遙測和偵錯工具修正。 不過，在某些情況下，可能會需要 Microsoft 工程師來存取客戶內容以判斷根本原因並修正問題。 客戶加密箱會要求工程師在核准工作流程的最後一個步驟向客戶要求存取。 這為組織提供核准或拒絕這些要求的選項，可讓使用者直接控制 Microsoft 工程師是否可以存取組織的使用者資料。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Office 365 E5/A5/G5、Microsoft 365 E5/a5/G5、Microsoft 365 E5/A5/g5 相容性、Microsoft 365 有問必答風險管理，以及 Office 365 的「高級法規遵從性」為使用者提供的權利可以從客戶密碼箱中受益。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

系統管理員可以在 Microsoft 365 系統管理中心開啟客戶加密箱控制。 如需詳細資訊，請參閱 [Office 365 中的客戶加密箱](https://docs.microsoft.com/microsoft-365/compliance/customer-lockbox-requests)。 當客戶加密箱開啟時，Microsoft 必須先取得組織的核准，再存取其任何內容。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

客戶加密箱服務目前不可限制為特定使用者。 您必須授權您想要受益的每一位使用者。

## <a name="privileged-access-management-in-office-365"></a>Office 365 的 Privileged Access Management

「[特權存取管理」 (PAM) ](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration)提供 Office 365 中的版權管理工作的細微存取控制。 啟用 PAM 之後，使用者將必須透過高度限定範圍和受限於時間的核准工作流程要求即時存取，以便完成提升權限和需要特殊權限的工作。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

啟用 PAM 可讓組織使用無常設權限作業。 使用者可從能抵禦為其資料提供不受束縛的常設系統管理存取所產生弱點新增的防禦層獲益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？ 

Office 365 E5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5 相容性，以及 Microsoft 365 E5/A5 資訊保護和控管為使用者提供的許可權，可供使用者從 PAM 中受益。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，PAM 功能會在租用戶層級針對租用戶內的所有使用者啟用。 如需設定 PAM 原則的詳細資訊，請參閱 [開始使用特殊許可權存取管理](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

客戶可以透過核准者群組和存取原則，以每位使用者為基礎管理 PAM (該原則可套用至授權的使用者)。 如需詳細資訊，請參閱 [Office 365 中的「特權存取管理](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)」。

## <a name="double-key-encryption-for-microsoft-365"></a>Microsoft 365 的雙金鑰加密 

Microsoft 365 的雙金鑰加密可讓您保護高度機密的資料，以符合特殊需求，並維護加密金鑰的完整控制權。 雙金鑰加密會使用兩個金鑰來保護您的資料，並在您的控制項和第二個金鑰儲存安全的 Microsoft Azure。 若要查看資料，您必須具有這兩個索引鍵的存取權。 因為 Microsoft 只可以存取單一機碼，所以您的金鑰和您的資料也無法供 Microsoft 使用，以確保您可以完全控制資料的隱私權和安全性。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

使用者可以將加密的資料移轉至雲端，並防止協力廠商存取，只要該機碼仍保持控制使用者，就能從雙金鑰加密中受益。 使用者可以保護和使用類似于任何其他敏感度標籤保護內容的雙金鑰加密內容。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Microsoft 365 E5/A5，Microsoft 365 E5/A5 相容性，Microsoft 365 資訊保護和控管，Office 365 E5/A5，以及 Office 365 的「高級法規遵從性」為使用者提供的許可權可讓使用者受益于雙金鑰加密。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

雙金鑰加密支援 Windows 版 Microsoft Office 的桌上出版本。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

若要將加密金鑰指派給 Office 365 和/或 Microsoft 365 組織中的資料以供授權的使用者使用，請遵循雙重金鑰加密部署指示。

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Office 365 資料遺失防護，適用于 Exchange Online、SharePoint 線上和商務 OneDrive

透過 Office 365 資料遺失防護 (的 DLP) 適用于 Exchange Online、SharePoint 線上及 OneDrive for Business，組織可以識別、監視和自動保護整個電子郵件和檔案中的機密資訊，包括儲存在 Microsoft 小組檔案存放庫 (中的檔案。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

當使用者的電子郵件和檔案檢查敏感資訊時（如組織的 DLP 原則中所設定），使用者可以從 DLP for Exchange Online、線上 SharePoint 和 OneDrive for Business 中受益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Microsoft 365 A1/E3/A3/Business、Office 365 E3/A3 和 Office 365 資料遺失防護可為使用者提供許可權，365以供 Exchange Online、線上 SharePoint 和商務 OneDrive 使用。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，Exchange Online 電子郵件、SharePoint 網站和 OneDrive 帳戶為針對租用戶內所有使用者的這些 DLP 功能的*啟用位置 (工作負載)*。 如需使用 DLP 原則的詳細資訊，請參閱[資料外洩防護概觀](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員可以自訂位置 (工作負載) 、包含的使用者，以及在 [安全性 & 規範中心] 中的 [**資料遺失防護**位置] 底下的使用者  >  ** **。

## <a name="communication-data-loss-prevention-for-teams"></a>小組的通訊資料遺失防護

透過通訊 DLP for a 小組，組織可以封鎖包含機密資訊（例如財務資訊、個人身分識別資訊、健康情況相關資訊或其他機密資訊）的研討及通道訊息。

### <a name="which-users-benefit-from-the-service"></a>哪些使用者可從此服務獲益？

Office 365 E5/A5 的授權使用者，Microsoft 365 E5/A5，Microsoft 365 資訊保護和控管，以及 Office 365 的高級規範可從適用于小組的通訊 DLP 受益。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

當寄件者在其外送聊天和通道訊息中檢查敏感資訊（如組織的 DLP 原則中所設定）時，寄件者的益處。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，Teams 聊天和頻道訊息為針對租用戶內所有使用者的這些 DLP 功能的*啟用位置 (工作負載)*。 如需使用 DLP 原則的詳細資訊，請參閱[資料外洩防護概觀](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員可以自訂位置 (工作負載) 、包含的使用者，以及在 [安全性 & 規範中心] 中的 [**資料遺失防護**位置] 底下的使用者  >  ** **。

## <a name="information-barriers"></a>資訊屏障

資訊屏障是系統管理員可以設定的原則，用來防止個人或群組彼此通訊。 比方說，如果某個部門處理的資訊不應與其他部門共用，或需要防止某個群組與外部連絡人通訊，此功能就相當實用。 資訊屏障原則也可以防止查閱和探索。 這表示如果您嘗試與不應與之通訊的人員通訊，您將不會在人員選擇器中找到該使用者。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

使用者可從使用者會受限而無法與其他人通訊之資訊屏障的進階符合性功能獲益。 例如：<br><br>

| 案例 | 誰需要授權？ |
|:------|:------|:------|
|  (Group &nbsp; 1 和 group) 2 群組的兩個群組 &nbsp; 無法彼此通訊 (也就是說，群組 &nbsp; 1 使用者受到限制，無法與群組 &nbsp; 2 使用者通訊，群組 &nbsp; 2 使用者限制于與群組 &nbsp; 1 使用者通訊。 | 群組 &nbsp; 1 和群組2中的 &nbsp; 使用者 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Microsoft 365 E5/A5，Microsoft 365 E5/A5 相容性，Microsoft 365 內部使用者風險管理，Office 365 E5/A5，和 Office 365 的「高級法規遵從性」為使用者提供的許可權，可讓使用者受益于資訊障礙。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

系統管理員會在安全性與合規性中心中使用 PowerShell Cmdlet 來建立及管理資訊屏障原則。 系統管理員必須獲指派 Microsoft 365 企業全域系統管理員、Office 365 全域系統管理員或合規性系統管理員角色，才能建立資訊屏障原則。 根據預設，這些原則會套用至租用戶中的所有使用者。 如需資訊屏障的詳細資訊，請參閱 [Microsoft Teams 中的資訊屏障](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員可以自訂 (工作負載) 、包含的使用者，以及在安全性 & 合規性中心內排除使用者的位置。 例如，如果所有使用者都已取得 Office 365 E3 的授權，且皆未取得 Office 365 進階合規性/E5 的授權，則不需要為組織建立任何資訊屏障原則。 如需詳細資訊，請參閱 [Microsoft Teams 中的資訊屏障](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)。

## <a name="office-365-message-encryption"></a>Office 365 郵件加密

Office 365 郵件加密 (OME) 是內建於 Azure 版權管理 (Azure RMS) 的服務，可讓您將加密的電子郵件傳送給組織內部或外部的人，無論目的地電子郵件地址為何 (Gmail、Yahoo! Mail、Outlook.com 等)。

若要檢視加密的郵件，收件者可以取得一次性密碼、使用 Microsoft 帳戶登入、或使用與 Office 365 相關聯的公司或學校帳戶登入。 收件者也可以傳送加密的回覆。 不需要訂閱即可查看加密的郵件或傳送加密的回復。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

郵件寄件者可從 Office 365 郵件加密所提供對敏感性電子郵件新增的控制而獲益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Microsoft 365 E3/A3、Office 365 E3/A3 和 Azure 資訊保護方案1為使用者提供從 Office 365 郵件加密中受益的權利。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

系統管理員會在 Exchange 系統管理中心的 [郵件流程]****  >  [規則]**** 下建立及管理 Office 365 郵件加密原則。 根據預設，這些規則會套用至租用戶中的所有使用者。 如需設定新的 Office 365 郵件加密功能的詳細資訊，請參閱[設定全新的 Office 365 郵件加密功能](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員應僅將 Office 365 郵件加密的郵件流程規則套用至授權使用者。 如需定義郵件流程規則的詳細資訊，請參閱[定義郵件流規則以加密 Office 365 中的電子郵件](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)。

## <a name="office-365-advanced-message-encryption"></a>Office 365 進階郵件加密

Office 365 Advanced Message Encryption 可協助客戶符合法規遵從性義務，需要更多彈性控制外部收件者，以及其對加密電子郵件的存取權。 有了進階郵件加密，系統管理員可以使用能偵測敏感性資訊類型的自動原則 (例如，個人識別資訊或是財務或健康身分編號) 控制在組織外部共用的敏感性電子郵件，或者他們可以透過安全網頁入口網站對加密的電子郵件套用自訂電子郵件範本和會到期的存取，以使用關鍵字來加強保護。 此外，系統管理員可隨時撤銷存取，進一步控制透過安全網頁入口網站存取的加密電子郵件。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

郵件寄件者可從進階郵件加密所提供對敏感性電子郵件新增的控制而獲益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Office 365 E5/A5，Microsoft 365 E5/A5，Microsoft 365 E5/A5 相容性，Microsoft 365 資訊保護和控管，以及 Office 365 的「高級法規遵從性」為使用者提供的許可權，可讓使用者從高級郵件加密中受益。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

系統管理員會在 Exchange 系統管理中心的郵件流程規則下建立及管理進階郵件加密原則。 根據預設，這些規則會套用至租用戶上的所有使用者。 如需設定新的郵件加密功能的詳細資訊，請參閱[設定全新的 Office 365 郵件加密功能](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員應僅將進階郵件加密的郵件流程規則套用至授權使用者。 如需定義郵件流程規則的詳細資訊，請參閱[定義郵件流規則以加密 Office 365 中的電子郵件](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)。

## <a name="communication-compliance"></a>通訊合規性

Microsoft 365 中的通訊法規遵從性，可協助您針對組織中的不適當郵件偵測、捕獲和採取補救措施，以盡可能降低通訊風險。 您可以定義可擷取內部和外部電子郵件、Microsoft Teams 或協力廠商通訊的特定原則。 檢閱者可以採取適當的修正動作，以確保它們符合您組織的郵件標準。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

合規性專家會透過通訊合規性原則監控組織通訊，以享受服務。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Office 365 E5/A5，Microsoft 365 E5/A5，Microsoft 365 E5/A5 相容性，而 Microsoft 365 內部使用者風險管理可為使用者提供權力，以受益于通訊相容性。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

管理員和合規性專業人員會在 Microsoft 365 規範中心建立通訊法規遵從性原則。 這些原則定義哪些通訊和使用者要在組織中進行審閱、定義通訊必須符合的自訂條件，以及指定應執行複查的人員。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

管理員選擇要包含在通訊合規性原則中的特定使用者或群組。 選擇群組時，使用者也可以從通訊合規性原則中，選取要排除在群組中的特定使用者。 如需有關通訊相容性原則的詳細資訊，請參閱 [Microsoft 365 中的通訊相容性](https://docs.microsoft.com/microsoft-365/compliance/communication-compliance-configure)。

## <a name="insider-risk-management"></a>測試人員風險管理

「內幕風險管理」是 Microsoft 365 中的解決方案，可讓您偵測、調查和採取行動，以應對組織中的危險活動，以協助降低內部風險。
自訂原則可讓您偵測組織中惡意和無意危險的活動，並採取動作，包括在必要時對 Microsoft Advanced eDiscovery 的升級案例。 組織中的風險分析人員可以快速採取適當的動作，以確保使用者符合您組織的規範標準。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

使用者可以利用其活動加以監控，以提升其的風險。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些授權可提供給使用者從服務中受益的許可權？

Microsoft 365 E5/A5、Microsoft 365 E5/A5 符合性，以及 Microsoft 365 「內幕人員風險管理」為使用者提供的權力，可從「內幕程式風險管理」中受益。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

內幕風險管理原則必須在 Microsoft 365 規範中心建立並指派給使用者。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

在 Microsoft 365 規範中心建立原則時，請在 [ **選擇使用者和群組** ] 頁面上，選取 **[選擇使用者或群組** ]，只選取授權的使用者，或者，如果您的所有使用者都獲得授權，您可以選取 [ **所有使用者及擁有郵件功能的群組** ] 核取方塊。 如需詳細資訊，請參閱 [立即開始使用「內幕風險管理](https://docs.microsoft.com/microsoft-365/compliance/insider-risk-management-configure)」。

## <a name="conditional-access-policies"></a>條件式存取原則

條件式存取是 Azure Active Directory 用來將信號一起使用的工具，以作出決策，並強制執行組織原則。 條件式存取是在 identity 導向控制平面的核心。 條件式存取原則最簡單的情況是 if-之後的語句。 如果使用者想要存取資源，則必須完成動作。 範例：工資管理員想要存取工資單應用程式，並且需要執行多重要素驗證以存取該應用程式。

### <a name="which-users-benefit-from-the-service"></a>哪些使用者可從此服務獲益？

已授權的 Enterprise 可移動性 + Security E3/A3 使用者、Microsoft 365 F3/E3/A3/Business Premium 和 Azure Active Directory Premium 方案1可以從條件式存取原則中受益。 Enterprise 可移動性 + Security E5/A5/G5、Microsoft 365 E5/A5、Microsoft E5 Security 和 Azure Active Directory Premium 方案2的授權使用者，可從身分識別保護 (風險的條件式存取原則) 中受益。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

安全性作業分析員和安全性專業人員可讓您在使用者上強制執行組織原則，並在授與公司內容的存取權之前符合特定準則，以受益。 使用者可以隨時隨地存取他們的工作，並在任何時候存取他們的工作，同時保護組織的資產。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，會在租使用者中的所有使用者的租使用者層級啟用條件式存取功能。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

針對身分識別保護和條件式存取，使用者必須包含在群組中或新增至條件式存取原則。 [使用者和群組] 條件是條件式存取原則中的強制性。 在您的原則中，您可以選取 [ **所有使用者** ] 或 [特定使用者和群組]。 您應該只選取適當授權的使用者和群組。 如需詳細資訊，請參閱 [Azure Active Directory 條件式存取中的條件為何？](https://docs.microsoft.com/azure/active-directory/conditional-access/conditions)。

## <a name="advanced-audit"></a>進階稽核

Microsoft 365 中的「高級核查」為使用者和系統管理員活動提供一年的審計記錄檔保留，並提供建立自訂審核記錄保留原則的能力，以管理其他 Microsoft 365 服務的審計記錄保留。 此外，它也可讓您存取重要事件，以進行調查和對 Office 365 管理活動 API 的高頻寬存取。 如需詳細資訊，請參閱 [Microsoft 365 中的「高級核查](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit)」。

您也可以使用附加元件 SKU 來啟用保留期間（10年）。 從2021開始，將需要附加元件 SKU。

### <a name="which-users-benefit-from-the-service"></a>哪些使用者可從此服務獲益？

授權使用者的 Office 365 E5、Microsoft 365 E5、Microsoft 365 E5 規範，以及 Microsoft 365 eDiscovery 和審核可從高級審計中受益。

使用高級審計的授權使用者，以及10年的審計記錄保留附加元件，可從10年的審計記錄保留中受益。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

因為 Microsoft 365 服務中使用者活動相關的審計記錄可保留最多一年，所以使用者可享受「高級審計」的好處。 此外，高值審核事件也會記錄下來，例如在存取或讀取使用者信箱中的專案時。 如需詳細資訊，請參閱 [Microsoft 365 中的「高級核查](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit)」。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，會在租使用者層級啟用 Office 365 或 Microsoft 365 E5 訂閱的「高級審核」，並自動為使用 Azure Active Directory、Exchange 及 SharePoint 中的適當授權) 使用者執行的 (活動提供一年的審計記錄檔保留。 此外，組織可使用審核記錄保留原則來管理其他 Microsoft 365 服務中的活動所產生的審計記錄保留期間。 您也可以使用相同的保留原則，啟用10年的審計記錄保留功能。 如需詳細資訊，請參閱[管理稽核記錄保留原則](https://docs.microsoft.com/microsoft-365/compliance/audit-log-retention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

只保留一年的審計記錄，而對重要的事件進行審核，只適用于具有適當授權的使用者。 此外，系統管理員可以使用審核記錄保留原則，為特定使用者的審計記錄檔指定較短的保留期間。

10年保留的審計記錄檔只適用于具有適當附加元件授權的使用者。 從2021開始，將需要附加元件 SKU。
