---
title: Microsoft 365 租用戶層級服務授權指導方針
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 本文提供 Microsoft 365 租用戶層級服務的授權指導方針，以協助避免由於未授權的存取造成潛在的服務中斷。
ms.openlocfilehash: b0ff01a92ed1d3c3a5284fd3eba45241a65c0a6a
ms.sourcegitcommit: f69656f34dcb4f4e9a5857d8c4236084c94a05b1
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/31/2019
ms.locfileid: "37890477"
---
# <a name="microsoft-365-tenant-level-services-licensing-guidance"></a>Microsoft 365 租用戶層級服務授權指導方針

針對此文章的目的，租用戶層級服務為一項線上服務，&mdash;為租用戶中的任何使用者購買 (獨立購買或隨著 Office 365 或 Microsoft 365 方案購買)&mdash; 時，會為租用戶中的部分或所有使用者啟用。 雖然部分未取得授權的使用者在技術上可能可存取服務，但想要從服務獲益的任何使用者都必須具備授權。

> [!NOTE]
> 部分租用戶服務目前無法將權益限制在特定使用者。 應該努力將服務權益限制在取得授權的使用者。 這麼做有助於在鎖定功能可用時避免對組織造成潛在的服務中斷。

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory Identity Protection (AADIP) 是 Azure Active Directory Premium P2 方案的一項功能，可讓您偵測會影響組織身分識別的潛在弱點，設定對偵測到與組織身分識別相關的可疑動作進行自動回應，以及調查可疑的事件並採取適當動作來加以解決。

### <a name="which-users-benefit-from-the-service"></a>哪些使用者可從此服務獲益？

Enterprise Mobility + Security E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 Security 和 Azure Active Directory Premium 方案 2 的授權使用者可從 AADIP 獲益。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

由於有了基於機器學習演算法、標幟的使用者和風險事件的彙總檢視，安全作業分析人員和安全性專業人員可從中獲益。 使用者則可獲益於透過風險式條件存取提供的自動防護，以及可對弱點採取行動而改善的安全性。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，AADIP 功能會在租用戶層級針對租用戶內的所有使用者啟用。 如需設定 AADIP 的相關資訊，請參閱[啟用 Azure Active Directory Identity Protection](https://docs.microsoft.com/azure/active-directory/identity-protection/enable)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員可以透過指派可定義密碼重設層級的風險原則，並僅允許取得授權的使用者存取，以限定 AADIP 的範圍。 如需如何限定 AADIP 部署範圍的相關指示，請參閱[設定登入風險原則](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy)。

## <a name="azure-advanced-threat-protection"></a>Azure 進階威脅防護

Azure 進階威脅防護 (ATP) 是一項雲端服務，可協助保護企業混合式環境，免於多種類型的進階鎖定目標的網路攻擊和內部威脅。

### <a name="which-users-benefit-from-the-service"></a>哪些使用者可從此服務獲益？

Enterprise Mobility + Security E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 Security 和 Azure 進階威脅防護的授權使用者可從 Azure ATP 獲益。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

安全作業分析人員和安全性專業人員可從 Azure ATP 偵測和調查進階威脅、遭入侵的身分識別和惡意內部人員動作的能力獲益。 使用者透過讓 Azure ATP 監控其資料而獲益。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，Azure ATP 功能會在租用戶層級針對租用戶內的所有使用者啟用。 如需設定 Azure ATP 的詳細資訊，請參閱[建立您的 Azure ATP 執行個體](https://docs.microsoft.com/azure-advanced-threat-protection/install-atp-step1)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

Microsoft 會為授權的使用者提供威脅偵測功能。

## <a name="azure-information-protection"></a>Azure 資訊保護

Azure 資訊保護 (AIP) 可協助組織探索、分類、標記及保護機密文件和電子郵件。 系統管理員可以定義規則和條件以自動套用標籤，使用者可以手動套用標籤，或使用這兩者的組合 (當使用者收到套用標籤的建議時)。

### <a name="which-users-benefit-from-the-service"></a>哪些使用者可從此服務獲益？

Microsoft 365 F1、Microsoft 365 商務版、Microsoft 365 E3/A3/G3 和 AIP 方案 1 的授權使用者可從 AIP 方案 1 獲益。 Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 Compliance 和 AIP 方案 2 的授權使用者可從 AIP 方案 2 獲益。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

AIP 掃描器功能會自動分類、標籤及保護位於內部部署檔案儲存庫中的檔案。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，AIP 功能會在租用戶層級針對租用戶內的所有使用者啟用。 如需針對授權使用者設定 AIP 原則的相關資訊，請參閱[啟用 Azure 版權管理](https://docs.microsoft.com/azure/information-protection/activate-service)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

AIP 功能原則 (掃描器功能除外) 可限定在特定群組或使用者的範圍；可以編輯登錄以防止未授權的使用者執行 AIP 分類或標記功能。 如需如何限定 AIP 部署範圍的相關指示，請參閱[設定 Azure 資訊保護原則](https://docs.microsoft.com/azure/information-protection/configure-policy)。

針對 AIP 掃描器功能，Microsoft 並未承諾會為未授權的使用者提供檔案分類、標記或保護功能。 一段時間後，系統會將授權檢查或目標式工具新增至 AIP，以確保可會將掃描器功能指派給授權使用者。

## <a name="office-365-advanced-threat-protection"></a>Office 365 進階威脅防護

進階威脅防護 (ATP) 可協助保護您的組織免受複雜的攻擊，例如網路釣魚和零時差惡意程式碼。 透過將來自廣泛資料的信號建立關聯，以協助識別、設定優先順序，並提供如何處理潛在威脅的建議，它也能夠提供可行的見解。

### <a name="which-users-benefit-from-the-service"></a>哪些使用者可從此服務獲益？

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 Security、Microsoft 365 商務版和 Office 365 ATP 方案 1 和 2 的授權使用者可從 ATP 獲益。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

ATP 可保護使用者免受複雜的攻擊，例如網路釣魚和零時差惡意程式碼。 如需方案 1 和方案 2 所提供服務的完整清單，請參閱 [Office 365 進階威脅防護](https://products.office.com/exchange/advance-threat-protection)。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，ATP 功能會在租用戶層級針對租用戶內的所有使用者啟用。 如需為授權使用者設定 ATP 原則的詳細資訊，請參閱 [Office 365 進階威脅防護](https://docs.microsoft.com/office365/securitycompliance/office-365-atp)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

若要限定 ATP 的範圍，請遵循安全連結和安全附件部署原則：

  - 如需為授權使用者設定安全連結的相關資訊，請參閱[設定 Office 365 ATP 安全連結原則](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-links-policies)。

  - 如需為授權使用者設定安全附件的相關資訊，請參閱[設定 Office 365 ATP 安全附件原則](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-attachments-policies)。

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security (OCAS) 是 Microsoft Cloud App Security 的子集，具有的功能限級於 Office 365，且沒有針對協力廠商雲端應用程式和 IaaS 服務的額外安全性功能。

OCAS 可讓組織了解其雲端應用程式和服務，提供複雜的分析功能來識別和對抗網路威脅，並讓他們控制資料在 Office 365 之間移動的方式。

若要比較功能，請參閱 [Microsoft Cloud App Security 與 Office 365 Cloud App Security 之間的差異為何](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365)。

### <a name="which-users-benefit-from-the-service"></a>哪些使用者可從此服務獲益？

Office 365 E5/A5/G5 的授權使用者可從 OCAS 獲益。

如需詳細資訊，請參閱 [Microsoft Cloud App Security 授權資料工作表](https://www.aka.ms/mcaslicensing)。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

OCAS 會探索影子 IT，提供 Office 365 的威脅防護，並可控制有權限可存取 Office 365 資料的應用程式。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，OCAS 功能會在租用戶層級針對租用戶內的所有使用者啟用。

如需設定服務的詳細資訊，請參閱 [Cloud App Security 的基本設定](https://docs.microsoft.com/cloud-app-security/general-setup)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員可以限定 OCAS 部署的範圍，以強制存取特定應用程式的方式，並限制由 Office 365 Cloud App Security 所監控的使用者群組。 如需詳細資訊，請參閱[限定範圍的部署](https://docs.microsoft.com/cloud-app-security/scoped-deployment)。

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) 是 Cloud Access Security Broker (CASB) 解決方案，可讓組織了解其雲端應用程式和服務，提供複雜的分析功能來識別和對抗網路威脅，並讓他們控制資料在任何雲端應用程式之間移動的方式。

### <a name="which-users-benefit-from-the-service"></a>哪些使用者可從此服務獲益？

MCAS、Enterprise Mobility + Security E5/A5/G5、Microsoft 365 E5/A5/G5 和 Microsoft 365 E5/A5/G5 Security 的授權使用者可從 MCAS 獲益。

Azure AD P1 的授權使用者可從 MCAS 中的探索功能獲益。

若要從 MCAS 中的[條件式存取應用程式控制](https://docs.microsoft.com/cloud-app-security/proxy-intro-aad)功能獲益，使用者也必須取得 Azure Active Directory P1 的授權，其包括在 Enterprise Mobility + Security E3/A3/G3、Enterprise Mobility + Security E5/A5/G5、Microsoft 365 E3/A3/G3, Microsoft 365 E5/A5/G5 和 Microsoft 365 E5/A5/G5 Security 中。

若要從[自動加標記](https://docs.microsoft.com/cloud-app-security/data-protection-policies)功能獲益，使用者必須取得 Azure 資訊保護 P2 的授權，其包含在 Enterprise Mobility + Security E5/A5/G5、Microsoft 365 E5/A5/G5 和 Microsoft 365 E5/A5/G5 Compliance 中。

如需詳細資訊，請參閱 [Microsoft Cloud App Security 授權資料工作表](https://www.aka.ms/mcaslicensing)。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

MCAS 會探索並評定影子 IT，提供第一方與第三方雲端應用程式間的威脅防護，並保護第一方與第三方雲端應用程式間的資訊。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，MCAS 功能會在租用戶層級針對租用戶內的所有使用者啟用。

如需為授權使用者設定 Microsoft Cloud App Security 原則的詳細資訊，請參閱 [Microsoft Cloud App Security 概觀](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員可以利用服務中提供的限定範圍部署功能，將 MCAS 部署限定於授權使用者的範圍。 如需詳細資訊，請參閱[限定範圍的部署](https://docs.microsoft.com/cloud-app-security/scoped-deployment)。

## <a name="office-365-advanced-data-governance"></a>Office 365 進階資料控管

進階資料控管 (ADG) 可協助組織使用可啟用保留及刪除的原則來滿足資訊控管需求。 ADG 可讓組織根據敏感性資訊類型自動為內容加上標籤，並將控管原則套用至該內容。

### <a name="which-users-benefit-from-the-service"></a>哪些使用者可從此服務獲益？

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 Compliance 和 Office 365 進階合規性的授權使用者可從 ADG 獲益。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

ADG 可讓使用者將標籤套用至特定資料，以支持特定原則，自動將內容標記為記錄，以及管理從宣告到處置的完整記錄程序。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，ADG 功能會在租用戶層級針對租用戶內的所有使用者啟用。 如需設定 ADG 以為授權使用者套用自動標籤和原則的詳細資訊，請參閱[保留標籤的概觀](https://docs.microsoft.com/office365/securitycompliance/labels)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

透過自動分類，您可將 ADG 保留原則套用至特定位置的授權使用者 (小組網站、群組網站等)。 如需套用 ADG 保留原則的指示，請參閱[將保留原則套用到整個組織或特定位置](https://docs.microsoft.com/office365/securitycompliance/retention-policies#applying-a-retention-policy-to-an-entire-organization-or-specific-locations)。

## <a name="office-365-advanced-ediscovery"></a>Office 365 進階電子文件探索

Office 365 進階電子文件探索可為公司內的 IT 和法律部門提供調查電子文件探索解決方案，以在從 Office 365 系統匯出之前，先行識別、收集、保留、縮減和檢閱與調查或訴訟相關的內容。

### <a name="which-users-benefit-from-the-service"></a>哪些使用者可從此服務獲益？

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 Compliance 和 Office 365 進階合規性的授權使用者可從進階電子文件探索獲益。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

當使用者被選取為資料監管人 (具有文件或電子檔案系統管理控制權的人員) 時，使用者即可從進階電子文件探索獲益。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，當系統管理員在安全性與合規性中心中指派電子文件探索權限時，系統會在租用戶內所有使用者的租用戶層級啟用進階電子文件探索功能。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

電子文件探索系統管理員可以使用進階電子文件探索中內建的監管人管理工具，將特定使用者選取為案例的資料監管人，如[將監管人新增至進階電子文件探索案例](https://docs.microsoft.com/office365/securitycompliance/compliance20/add-custodians-to-case)中所述。

## <a name="office-365-customer-key"></a>Office 365 客戶金鑰

有了客戶金鑰，您即可控制組織的加密金鑰，並將 Office 365 設定為使用這些金鑰來加密在 Microsoft 資料中心的待用資料。 換句話說，客戶金鑰可讓您新增屬於您、使用您自己的金鑰的一層加密。 存放的資料包括 Exchange Online 資料和儲存在信箱的商務用 Skype 資料，以及儲存在 SharePoint Online 和商務用 OneDrive 中的檔案。

### <a name="which-users-benefit-from-the-service"></a>哪些使用者可從此服務獲益？

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 Compliance 和 Office 365 進階合規性的授權使用者可從客戶金鑰獲益。 若要獲得客戶金鑰的完整優勢，您也必須具有 Azure 金鑰保存庫的訂閱。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

使用者可讓其待用資料在應用程式層使用其自己的組織所提供、控制及管理的加密金鑰加密，藉此從客戶金鑰獲益。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

您可以為儲存在 Exchange Online 和商務用 Skype 信箱，以及 SharePoint Online 和商務用 OneDrive 檔案中的所有資料啟用 Office 365 客戶金鑰加密金鑰。 如需設定 Office 365 客戶金鑰以加密您的待用資料的詳細資訊，請參閱[使用客戶金鑰控制 Office 365 中的資料](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

若要將加密金鑰指派給 Office 365 和/或 Microsoft 365 租用戶內的資料，請遵循客戶金鑰加密金鑰部署指示：

  - 針對 SharePoint Online 和商務用 OneDrive，一或多個網站上的檔案可以使用此處所述的客戶金鑰加密：[設定 SharePoint Online 和商務用 OneDrive 的客戶金鑰](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-sharepoint-online-and-onedrive-for-business)。

  - 如果您使用 Exchange Online 和商務用 Skype Online，信箱可使用此處所述的客戶金鑰加密：[設定 Exchange Online 和商務用 Skype 的客戶金鑰](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-exchange-online-and-skype-for-business)

## <a name="office-365-customer-lockbox"></a>Office 365 客戶加密箱

透過讓客戶為服務作業提供明確的存取授權，客戶加密箱可提供額外的一層控制。 藉由示範該程序可用於明確資料存取授權，客戶加密箱也可協助組織符合特定合規性義務，例如 HIPAA 與 FEDRAMP。

### <a name="which-users-benefit-from-the-service"></a>哪些使用者可從此服務獲益？

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 Compliance 和 Office 365 進階合規性的授權使用者可從客戶加密箱獲益。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

自客戶加密箱獲益的使用者，可確保在未經客戶明確同意的情況下，Microsoft 中沒有人能存取客戶內容來執行服務作業。 客戶加密箱會將客戶帶至要求存取其內容的核准工作流程。 有時候，Microsoft 工程師會於支援程序期間加入，以疑難排解並修正客戶報告的問題。 在大部分情況下，問題可透過 Microsoft 既有、用於其服務的廣泛遙測和偵錯工具修正。 不過，在某些情況下，可能會需要 Microsoft 工程師來存取客戶內容以判斷根本原因並修正問題。 客戶加密箱會要求工程師在核准工作流程的最後一個步驟向客戶要求存取。 這可讓組織可選擇核准或拒絕這些要求，讓他們直接控制 Microsoft 工程師是否能夠存取組織的使用者資料。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

系統管理員可以在 Microsoft 365 系統管理中心開啟客戶加密箱控制。 如需詳細資訊，請參閱 [Office 365 中的客戶加密箱](https://docs.microsoft.com/Office365/Admin/manage/customer-lockbox-requests)。 當客戶加密箱開啟時，Microsoft 必須在存取組織的任何內容之前，先取得組織的核准。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

Microsoft 可為您的 Office 365 組織中的使用者提供客戶加密箱存取控制核准要求。

## <a name="privileged-access-management-in-office-365"></a>Office 365 中的特殊權限存取管理

特殊權限存取管理 (PAM) 可對 Office 365 中的特殊權限系統管理工作提供細微的存取控制。 啟用 PAM 之後，使用者將必須透過高度限定範圍和受限於時間的核准工作流程要求即時存取，以便完成提升權限和需要特殊權限的工作。

### <a name="which-users-benefit-from-the-service"></a>哪些使用者可從此服務獲益？

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 Compliance 和 Office 365 進階合規性的授權使用者可從 PAM 獲益。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

啟用 PAM 可讓組織使用無常設權限作業。 使用者可從能抵禦為其資料提供不受束縛的常設系統管理存取所產生弱點新增的防禦層獲益。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，PAM 功能會在租用戶層級針對租用戶內的所有使用者啟用。 如需設定 PAM 原則的詳細資訊，請參閱[設定 Office 365 中的特殊權限存取管理](https://docs.microsoft.com/office365/securitycompliance/privileged-access-management-configuration)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

客戶可以透過核准者群組和存取原則，以每位使用者為基礎管理 PAM (該原則可套用至授權的使用者)。 如需詳細資訊，請參閱 [Office 365 中的特殊權限存取管理](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)。

## <a name="data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Exchange Online、SharePoint Online 及商務用 OneDrive 適用的資料外洩防護

有了 Exchange Online、SharePoint Online 和商務用 OneDrive 適用的資料外洩防護 (DLP)，組織可以識別、監控及自動保護電子郵件和檔案中的敏感性資訊 (包括儲存在 Microsoft Teams 檔案儲存庫中的檔案)。

### <a name="which-users-benefit-from-the-service"></a>哪些使用者可從此服務獲益？

Office 365 E3/A3/G3、Microsoft 365 商務版、Microsoft 365 A1/E3/A3/G3 和 Office 365 資料外洩防護的授權使用者可從 Exchange Online、SharePoint Online 和商務用 OneDrive 適用的 DLP 獲益。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

如同組織的 DLP 原則中所設定，當使用者的電子郵件檔案經過敏感性資訊檢查時，使用者可以從適用於 Exchange Online、SharePoint Online 和商務用 OneDrive 的 DLP 中獲益。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，Exchange Online 電子郵件、SharePoint 網站和 OneDrive 帳戶為針對租用戶內所有使用者的這些 DLP 功能的*啟用位置 (工作負載)*。 如需使用 DLP 原則的詳細資訊，請參閱[資料外洩防護概觀](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員可以在 Office 365 安全性與合規性中心的 [資料外洩防護]****  >  [位置]**** 下自訂位置 (工作負載)、包含的使用者以及排除的使用者。

## <a name="data-loss-prevention-for-teams-chat-and-channel-messages"></a>Teams 聊天和頻道訊息適用的資料外洩防護

有了 Teams 聊天和頻道訊息適用的資料外洩防護 (DLP)，組織可以封鎖內含敏感性資訊的聊天和頻道訊息，例如財務資訊、個人識別資訊、健康相關資訊或其他機密資訊。

### <a name="which-users-benefit-from-the-service"></a>哪些使用者可從此服務獲益？

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 Compliance 和 Office 365 進階合規性的授權使用者可從 Teams 聊天和頻道訊息適用的 DLP 獲益。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

如同組織的 DLP 原則中所設定，寄件者可藉由讓其外寄聊天和頻道訊息中的敏感性資訊經過敏感性資訊檢查而獲益。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

根據預設，Teams 聊天和頻道訊息為針對租用戶內所有使用者的這些 DLP 功能的*啟用位置 (工作負載)*。 如需使用 DLP 原則的詳細資訊，請參閱[資料外洩防護概觀](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員可以在 Office 365 安全性與合規性中心的 [資料外洩防護]****  >  [位置]**** 下自訂位置 (工作負載)、包含的使用者以及排除的使用者。

## <a name="information-barriers"></a>資訊屏障

資訊屏障是系統管理員可以設定的原則，用來防止個人或群組彼此通訊。 比方說，如果某個部門處理的資訊不應與其他部門共用，或需要防止某個群組與外部連絡人通訊，此功能就相當實用。 資訊屏障原則也可以防止查閱和探索。 這表示如果您嘗試與不應與之通訊的人員通訊，您將不會在人員選擇器中找到該使用者。

### <a name="which-users-benefit-from-the-service"></a>哪些使用者可從此服務獲益？

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 Compliance 和 Office 365 進階合規性的授權使用者可從資訊屏障獲益。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

使用者可從使用者會受限而無法與其他人通訊之資訊屏障的進階符合性功能獲益。 例如：

| 案例                                                                                                                                                                                                              | 誰需要授權？ |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| 兩個群組 (群組 1 和群組 2) 無法彼此通訊 (也就是說，群組 1 的使用者受到限制，無法與群組 2 的使用者通訊，而群組 2 使用者則受到限制，無法與群組 1 的使用者通訊。 | 群組 1 和群組 2 中的使用者                    |
| 群組 1 中的使用者受到限制，無法與公司其餘人員通訊。                                                                                                                                       | 僅限群組 1 中的使用者                                |
| 公司的其餘人員受到限制，無法與群組 1 通訊。                                                                                                                                                 | 群組 1 中以外的所有使用者                    |
| 群組 1 使用者受到限制，無法與群組 2 使用者通訊，但群組 2 使用者可以與群組 1 使用者通訊。                                                                                              | 僅限群組 1 中的使用者                                |

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

系統管理員會在安全性與合規性中心中使用 PowerShell Cmdlet 來建立及管理資訊屏障原則。 系統管理員必須獲指派 Microsoft 365 企業全域系統管理員、Office 365 全域系統管理員或合規性系統管理員角色，才能建立資訊屏障原則。 根據預設，這些原則會套用至租用戶中的所有使用者。 如需資訊屏障的詳細資訊，請參閱 [Microsoft Teams 中的資訊屏障](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員可以在 Office 365 安全性與合規性中心中自訂位置 (工作負載)、包含的使用者以及排除的使用者。 例如，如果所有使用者都已取得 Office 365 E3 的授權，且皆未取得 Office 365 進階合規性/E5 的授權，則不需要為組織建立任何資訊屏障原則。 如需詳細資訊，請參閱 [Microsoft Teams 中的資訊屏障](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)。

## <a name="office-365-message-encryption"></a>Office 365 郵件加密

Office 365 郵件加密 (OME) 是內建於 Azure 版權管理 (Azure RMS) 的服務，可讓您將加密的電子郵件傳送給組織內部或外部的人，無論目的地電子郵件地址為何 (Gmail、Yahoo! Mail、Outlook.com 等)。

若要檢視加密的郵件，收件者可以取得一次性密碼、使用 Microsoft 帳戶登入、或使用與 Office 365 相關聯的公司或學校帳戶登入。 收件者也可以傳送加密的回覆。 他們不需要 Office 365 訂閱，即可檢視加密的郵件或傳送加密的回覆。

### <a name="which-users-benefit-from-the-service"></a>哪些使用者可從此服務獲益？

Office 365 E3/A3/G3、Microsoft 365 E3/A3/G3 和 Azure 資訊保護方案 1 的授權使用者可從 Office 365 郵件加密獲益。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

郵件寄件者可從 Office 365 郵件加密所提供對敏感性電子郵件新增的控制而獲益。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

系統管理員會在 Exchange 系統管理中心的 [郵件流程]****  >  [規則]**** 下建立及管理 Office 365 郵件加密原則。 根據預設，這些規則會套用至租用戶中的所有使用者。 如需設定新的 Office 365 郵件加密功能的詳細資訊，請參閱[設定全新的 Office 365 郵件加密功能](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員應僅將 Office 365 郵件加密的郵件流程規則套用至授權使用者。 如需定義郵件流程規則的詳細資訊，請參閱[定義郵件流規則以加密 Office 365 中的電子郵件](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)。


## <a name="office-365-advanced-message-encryption"></a>Office 365 進階郵件加密

進階郵件加密可協助客戶滿足需要對外部收件者更靈活控制，以及其對加密電子郵件存取的合規性義務。 有了進階郵件加密，系統管理員可以使用能偵測敏感性資訊類型的自動原則 (例如，個人識別資訊或是財務或健康身分編號) 控制在組織外部共用的敏感性電子郵件，或者他們可以透過安全網頁入口網站對加密的電子郵件套用自訂電子郵件範本和會到期的存取，以使用關鍵字來加強保護。 此外，系統管理員可隨時撤銷存取，進一步控制透過安全網頁入口網站存取的加密電子郵件。

### <a name="which-users-benefit-from-the-service"></a>哪些使用者可從此服務獲益？

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 Compliance 和 Office 365 進階合規性的授權使用者可從進階郵件加密獲益。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

郵件寄件者可從進階郵件加密所提供對敏感性電子郵件新增的控制而獲益。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

系統管理員會在 Exchange 系統管理中心的郵件流程規則下建立及管理進階郵件加密原則。 根據預設，這些規則會套用至租用戶上的所有使用者。 如需設定新的郵件加密功能的詳細資訊，請參閱[設定全新的 Office 365 郵件加密功能](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員應僅將進階郵件加密的郵件流程規則套用至授權使用者。 如需定義郵件流程規則的詳細資訊，請參閱[定義郵件流規則以加密 Office 365 中的電子郵件](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)。

## <a name="supervision-policies"></a>監督原則

Office 365 中的監督原則可讓您透過指定的檢閱者擷取要進行檢查的員工通訊。 您可以定義可擷取內部和外部電子郵件、Microsoft Teams 或協力廠商通訊的特定原則。 然後，檢閱者可以檢閱郵件，以確定郵件符合您組織的郵件標準，並使用分類類型解析郵件。

### <a name="which-users-benefit-from-the-service"></a>哪些使用者可從此服務獲益？

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 Compliance 和 Office 365 進階合規性的授權使用者可從監督原則獲益。

### <a name="how-do-users-benefit-from-the-service"></a>使用者如何從此服務獲益？

使用者可讓其通訊由監督原則監視，藉此從服務獲益。

### <a name="how-is-the-service-provisioneddeployed"></a>服務如何佈建/部署？

系統管理員在安全性與合規性中心建立監督原則。 這些原則可定義組織中要受限於檢查的通訊和使用者、定義通訊必須符合的自訂條件，以及指定應執行檢查的人員。
 
### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何只將服務套用到租用戶中已取得服務授權的使用者？

系統管理員會選擇要包含在監管原則的特定使用者或群組。 選擇群組時，他們也可以選取群組中的特定使用者，以從監管原則中排除。 如需監管原則的詳細資訊，請參閱 [Office 365 中的監督原則](https://docs.microsoft.com/office365/SecurityCompliance/supervision-policies)。
