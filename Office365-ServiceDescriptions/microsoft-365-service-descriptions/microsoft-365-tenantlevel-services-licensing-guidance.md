---
title: Microsoft 365 租使用者層級服務授權指南
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
description: 本文提供 Microsoft 365 租使用者層級服務的授權指引, 以協助避免因未經許可存取而造成的潛在服務中斷。
ms.openlocfilehash: fdd16e2b9fe7f5bd9dc3c59fbc77ddd8e308afee
ms.sourcegitcommit: dab03604af87399ad70323ede34dc8abe28c63d8
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/28/2019
ms.locfileid: "35394907"
---
# <a name="microsoft-365-tenant-level-services-licensing-guidance"></a>Microsoft 365 租使用者層級服務授權指南

針對本文的目的, 承租人層級服務是一種線上服務,&mdash;當您為租使用者 (獨立版或 Office 365 或 Microsoft 365 方案)&mdash;購買任何使用者時, 就會為租使用者中的所有使用者啟用部分或完整啟動。 雖然某些未經授權的使用者可以從技術上存取服務, 但您想要從服務獲益的任何使用者都需要授權。

> [!NOTE]
> 某些租使用者服務目前無法限制特定使用者的權益。 應採取努力, 以將服務權益限制為已授權的使用者。 這有助於避免您的組織在目標功能可以使用時中斷潛在的服務中斷。

# <a name="azure-active-directory-identity-protection"></a>Azure Active Directory 身分識別保護

Azure Active Directory Identity Protection (AADIP) 是 Azure Active Directory Premium P2 計畫的一項功能, 可讓您偵測影響組織身分識別的潛在弱點, 以及設定偵測到可疑的自動化回應與您組織的身分識別相關的動作, 並調查可疑事件, 並採取適當的動作來解決問題。

## <a name="which-users-benefit-from-the-service"></a>哪些使用者從服務獲益？

Enterprise 可移動性 + Security E5 的授權使用者、Microsoft 365 E5、Microsoft 365 E5 安全性和 Azure Active Directory Premium Plan 2 可從 AADIP 獲益。

## <a name="how-do-users-benefit-from-the-service"></a>使用者如何從服務獲益？

SecOps 分析師和安全性專業人員會受益于根據機器學習演算法, 擁有已標記使用者的合併視圖和風險事件。 使用者會受益于透過風險型條件式存取所提供的自動防護, 以及由操作漏洞所提供的改善安全性。

## <a name="how-is-the-service-provisioneddeployed"></a>如何布建/部署服務？

根據預設, AADIP 功能會在租使用者層級上為租使用者中的所有使用者啟用。 如需設定 AADIP 的詳細資訊, 請參閱[啟用 Azure Active Directory 身分識別保護](https://docs.microsoft.com/azure/active-directory/identity-protection/enable)。

## <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何僅將服務套用至已授權服務的租使用者中的使用者？

系統管理員可以指派定義密碼重設層級的風險原則, 並只允許授權使用者的存取, 以範圍 AADIP。 如需如何 AADIP 部署範圍的相關指示, 請參閱[設定登入風險原則](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy)。

# <a name="azure-advanced-threat-protection"></a>Azure 高級威脅防護

Azure Advanced 威脅防護 (ATP) 是一種雲端服務, 可協助您保護企業混合式環境, 從多種類型的高級目標網路攻擊和內部網路威脅。

## <a name="which-users-benefit-from-the-service"></a>哪些使用者從服務獲益？

授權使用者的企業行動 + 安全性 E5、Microsoft 365 E5、Microsoft 365 E5 安全性, 以及 Azure 的使用者可從 Azure ATP 獲益。

## <a name="how-do-users-benefit-from-the-service"></a>使用者如何從服務獲益？

SecOp 分析師和安全性專業人員會受益于 Azure ATP 偵測和調查高級威脅、洩漏身分識別和惡意的擁有者動作的能力。 使用者可以透過 Azure ATP 來監視其資料, 以獲得好處。

## <a name="how-is-the-service-provisioneddeployed"></a>如何布建/部署服務？

根據預設, 會在承租人層級為租使用者中的所有使用者啟用 Azure ATP 功能。 如需設定 Azure ATP 的詳細資訊, 請參閱[建立您的 AZURE atp 實例](https://docs.microsoft.com/azure-advanced-threat-protection/install-atp-step1)。

## <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何僅將服務套用至已授權服務的租使用者中的使用者？

Microsoft 不會認可將威脅偵測功能提供給未獲授權的使用者。 一段時間之後, 系統會將授權檢查或目標工具新增至 Azure ATP, 以確保 Azure ATP 功能只適用于授權使用者。

# <a name="azure-information-protection"></a>Azure 資訊保護

Azure 資訊保護 (AIP) 可協助組織探索、分類、標記和保護機密檔和電子郵件。 系統管理員可以定義規則和條件, 以自動套用標籤, 使用者可以手動套用標籤, 或是在使用者有權&mdash;套用標籤時, 可以使用二者的組合。

## <a name="which-users-benefit-from-the-service"></a>哪些使用者從服務獲益？

Microsoft 365 F1、Microsoft 365 E3 和 AIP Plan 1 的授權使用者可以從 AIP 方案1獲益。 Microsoft 365 E5、Microsoft 365 E5 規範和 AIP 方案2的授權使用者可以從 AIP 方案2獲益。

## <a name="how-do-users-benefit-from-the-service"></a>使用者如何從服務獲益？

AIP 掃描器功能會自動分類、標籤, 並保護位於內部部署檔案存放庫中的檔案。

## <a name="how-is-the-service-provisioneddeployed"></a>如何布建/部署服務？

根據預設, AIP 功能會在租使用者層級上為租使用者中的所有使用者啟用。 如需設定授權使用者之 AIP 原則的詳細資訊, 請參閱[啟用 Azure Rights Management](https://docs.microsoft.com/azure/information-protection/activate-service)。

## <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何僅將服務套用至已授權服務的租使用者中的使用者？

AIP 功能原則 (掃描器功能除外) 可以限定為特定群組或使用者。您可以編輯註冊表, 以防止未授權的使用者執行 AIP 分類或標籤功能。 如需如何 AIP 部署範圍的相關指示, 請參閱設定[Azure 資訊保護原則](https://docs.microsoft.com/azure/information-protection/configure-policy)。

對於 AIP 掃描器功能, Microsoft 不會認可對未獲授權的使用者提供檔分類、標籤或保護功能。 經過一段時間後, 就會將授權檢查或目標工具新增至 AIP, 以確保掃描器功能可獲獲授權的使用者。

# <a name="office-365-advanced-threat-protection"></a>Office 365 進階威脅防護

高級威脅防護 (ATP) 可協助保護組織, 防範複雜的攻擊, 例如網路釣魚和零天的惡意程式碼。 它也提供可操作的見解, 方法是將各種資料與信號關聯, 以協助識別、設定優先順序, 並提供如何解決潛在威脅的建議。

## <a name="which-users-benefit-from-the-service"></a>哪些使用者從服務獲益？

授權使用者的 Office 365 E5、Microsoft 365 E5、Microsoft 365 E5 Security、Microsoft 365 商務和 Office 365 ATP 方案1和2可從 ATP 獲益。

## <a name="how-do-users-benefit-from-the-service"></a>使用者如何從服務獲益？

ATP 會保護使用者不受複雜的攻擊, 例如網路釣魚和零天的惡意程式碼。 如需方案1和方案2中提供的完整服務清單, 請參閱[Office 365 Advanced 威脅防護](https://products.office.com/exchange/advance-threat-protection)。

## <a name="how-is-the-service-provisioneddeployed"></a>如何布建/部署服務？

根據預設, 所有使用者在租使用者層級上都會啟用 ATP 功能。 如需設定授權使用者的 ATP 原則的詳細資訊, 請參閱[Office 365 Advanced 威脅防護](https://docs.microsoft.com/office365/securitycompliance/office-365-atp)。

## <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何僅將服務套用至已授權服務的租使用者中的使用者？

若要範圍 ATP, 請遵循 [安全連結] 和 [安全附件] 部署原則:

  - 如需設定授權使用者安全連結的詳細資訊, 請參閱[Set Up Office 365 ATP Safe Links 原則](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-links-policies)。

  - 如需設定授權使用者安全附件的詳細資訊, 請參閱[設定 Office 365 ATP 安全附件原則](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-attachments-policies)。

# <a name="office-365-cloud-app-security"></a>Office 365 雲端 App 安全性

Office 365 Cloud App Security (OCAS) 是 Microsoft Cloud App Security 的子集, 其中的功能限於 Office 365, 且不需要額外的安全性即可進行協力廠商雲端應用程式和 IaaS 服務。

OCAS 可讓組織看到其生產力的雲端應用程式和服務, 提供複雜的分析來識別和打擊網路威脅, 並讓他們控制&mdash;資料如何跨 Office 365 傳播。

若要比較功能, 請參閱[Microsoft Cloud App security 與 Office 365 Cloud App security 之間的差異](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365)。

## <a name="which-users-benefit-from-the-service"></a>哪些使用者從服務獲益？

Office 365 E5 的授權使用者可以從 OCAS 獲益。

如需詳細資訊, 請參閱[Microsoft Cloud App Security 授權](http://www.aka.ms/mcaslicensing)資料工作表。

## <a name="how-do-users-benefit-from-the-service"></a>使用者如何從服務獲益？

OCAS 探索陰影 IT, 提供不同 Office 365 的威脅防護, 並可控制哪些應用程式具有存取 Office 365 資料的許可權。

## <a name="how-is-the-service-provisioneddeployed"></a>如何布建/部署服務？

根據預設, OCAS 功能會在租使用者層級上為租使用者中的所有使用者啟用。

如需設定服務的詳細資訊, 請參閱[Cloud App Security 的基本設定](https://docs.microsoft.com/cloud-app-security/general-setup)。

## <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何僅將服務套用至已授權服務的租使用者中的使用者？

系統管理員可以將 OCAS 部署的範圍, 強制執行特定應用程式的存取方式, 並限制 Office 365 Cloud App 安全性所監控的使用者群組。 如需詳細資訊, 請參閱[範圍部署](https://docs.microsoft.com/cloud-app-security/scoped-deployment)。

# <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) 是雲端存取安全性代理程式 (CASB) 解決方案, 可讓組織瞭解他們的雲端應用程式和服務, 提供完善的分析來識別和打擊網路威脅, 並讓他們控制資料如何在&mdash;任何雲端應用程式間移動。

## <a name="which-users-benefit-from-the-service"></a>哪些使用者從服務獲益？

MCAS 的授權使用者, 企業行動 + 安全性 E5, Microsoft 365 E5 和 Microsoft 365 E5 安全性可從 MCAS 獲益。

Azure AD P1 的授權使用者可以受益于 MCAS 的探索功能。

若要從 MCAS 的[條件式存取應用程式控制](https://docs.microsoft.com/cloud-app-security/proxy-intro-aad)功能中獲益, 使用者也必須獲得 Azure Active Directory P1 的授權, 其包含于企業行動性 + 安全性 E3、企業行動 + 安全性 E5、Microsoft 365 E3、microsoft 365E5 和 Microsoft 365 E5 安全性。

若要從[自動標籤](https://docs.microsoft.com/cloud-app-security/data-protection-policies)獲益, 使用者必須獲得 Azure 資訊保護 P2 的授權, 其包含在企業行動性 + 安全性 E5、Microsoft 365 E5 和 Microsoft 365 e5 規範中。

如需詳細資訊, 請參閱[Microsoft Cloud App Security 授權](http://www.aka.ms/mcaslicensing)資料工作表。

## <a name="how-do-users-benefit-from-the-service"></a>使用者如何從服務獲益？

MCAS 探索並評估陰影它、提供第一和協力廠商雲端應用程式的威脅防護, 以及保護第一方和協力廠商雲端應用程式的資訊。

## <a name="how-is-the-service-provisioneddeployed"></a>如何布建/部署服務？

根據預設, MCAS 功能會在租使用者層級上為租使用者中的所有使用者啟用。

如需針對授權使用者設定 Microsoft Cloud App Security 原則的詳細資訊, 請參閱[Microsoft Cloud App security 總覽](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)。

## <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何僅將服務套用至已授權服務的租使用者中的使用者？

系統管理員可以使用服務中提供的範圍部署功能, 將 MCAS 部署的範圍設定為已授權的使用者。 如需詳細資訊, 請參閱[範圍部署](https://docs.microsoft.com/cloud-app-security/scoped-deployment)。

# <a name="office-365-advanced-data-governance"></a>Office 365 進階資料控管

Advanced Data 控管 (ADG) 可協助組織符合資訊控管需求, 以及可啟用保留和刪除的原則。 ADG 可讓組織根據敏感資訊類型自動為內容加上標籤, 並將控管原則套用至該內容。

## <a name="which-users-benefit-from-the-service"></a>哪些使用者從服務獲益？

Office 365 E5 的授權使用者, Microsoft 365 E5, Microsoft 365 E5 合規性, 以及 Office 365 Advanced 合規性可從 ADG 獲益。

## <a name="how-do-users-benefit-from-the-service"></a>使用者如何從服務獲益？

ADG 可讓使用者將標籤套用至特定的資料, 以保持特定原則、自動將內容標記為記錄, 以及管理從宣告到處置的完整記錄處理常式。

## <a name="how-is-the-service-provisioneddeployed"></a>如何布建/部署服務？

根據預設, ADG 功能會在租使用者層級上為租使用者中的所有使用者啟用。 如需設定 ADG 以對授權使用者套用自動標籤和原則的詳細資訊, 請參閱[保留標籤](https://docs.microsoft.com/office365/securitycompliance/labels)。

## <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何僅將服務套用至已授權服務的租使用者中的使用者？

ADG 保留原則可套用至特定位置 (小組網站、群組網站等) 的授權使用者, 以及自動分類。 如需套用 ADG 保留原則的相關指示, 請參閱[將保留原則套用至整個組織或特定位置](https://docs.microsoft.com/office365/securitycompliance/retention-policies#applying-a-retention-policy-to-an-entire-organization-or-specific-locations)。

# <a name="office-365-advanced-ediscovery"></a>Office 365 進階電子文件探索

Advanced eDiscovery 為 IT 和法律部門提供調查和 eDiscovery 解決方案, 以在出口 Office 365 之前先識別、收集、保留、減少及查看與調查或訴訟相關的內容。坐標系.

## <a name="which-users-benefit-from-the-service"></a>哪些使用者從服務獲益？

Office 365 E5 的授權使用者, Microsoft 365 E5, Microsoft 365 E5 合規性, 以及 Office 365 Advanced 合規性可從高級 eDiscovery 獲益。

## <a name="how-do-users-benefit-from-the-service"></a>使用者如何從服務獲益？

當使用者的內容保留為訴訟或調查的一部分時, 他們就會受益于高級 eDiscovery。

## <a name="how-is-the-service-provisioneddeployed"></a>如何布建/部署服務？

根據預設, 當系統管理員指派安全性 & 規範中心內的 eDiscovery 許可權時, 就會在租使用者層級上啟用高級 eDiscovery 功能。

## <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何僅將服務套用至已授權服務的租使用者中的使用者？

組織可以依每個使用者來管理 Advanced eDiscovery, 並將使用者新增至高級 eDiscovery 案例, 以及透過 eDiscovery 許可權讓使用者能夠編輯共用位置。 如需如何將高級 eDiscovery 許可權套用至授權使用者的相關指示, 請參閱[在安全性 & 規範中心指派 eDiscovery 許可權](https://docs.microsoft.com/office365/securitycompliance/assign-ediscovery-permissions)。

# <a name="office-365-customer-key"></a>Office 365 客戶金鑰

使用客戶金鑰, 您可以控制組織的加密金鑰, 並設定 Office 365, 以使用這些金鑰在 Microsoft 資料中心內的靜態資料進行加密。 換句話說, 客戶金鑰可讓您使用自己的金鑰, 新增屬於您的加密層。 靜態資料包含來自 Exchange Online 的資料, 以及儲存在 SharePoint Online 和商務用 OneDrive 中之信箱和檔案的商務用 Skype。

## <a name="which-users-benefit-from-the-service"></a>哪些使用者從服務獲益？

Office 365 E5 的授權使用者, Microsoft 365 E5, Microsoft 365 E5 合規性, 以及 Office 365 Advanced 合規性可從客戶金鑰獲益。 若要取得客戶金鑰的完整優點, 您也必須具備 Azure Key Vault 的訂閱。

## <a name="how-do-users-benefit-from-the-service"></a>使用者如何從服務獲益？

使用者可以利用客戶的金鑰, 讓其資料在應用程式層使用加密金鑰 (由自己的組織提供、控制及管理) 來加密。

## <a name="how-is-the-service-provisioneddeployed"></a>如何布建/部署服務？

Office 365 客戶金鑰加密金鑰可用於 Exchange Online 和商務用 Skype 信箱中儲存的所有資料, 以及 SharePoint Online 和商務用 OneDrive 檔案。 如需設定 Office 365 客戶金鑰以加密靜態資料的詳細資訊, 請參閱[使用客戶金鑰控制 office 365 中的資料](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key)。

## <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何僅將服務套用至已授權服務的租使用者中的使用者？

若要將加密金鑰指派給已授權使用者的 Office 365 和/或 Microsoft 365 租使用者中的資料, 請遵循客戶金鑰加密金鑰的部署原則:

  - 對於 SharePoint Online, 一或多個網站上的檔案可以使用客戶金鑰進行加密, 如下所述:[設定 SharePoint Online 和商務用 OneDrive 的客戶金鑰](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-sharepoint-online-and-onedrive-for-business)。

  - 針對 Exchange Online 和商務用 Skype Online, 您可以使用以下所述的客戶金鑰加密信箱:[設定 Exchange Online 和商務用 skype 的客戶金鑰](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-exchange-online-and-skype-for-business)

# <a name="office-365-customer-lockbox"></a>Office 365 客戶加密箱

客戶加密箱提供額外的控制層, 讓客戶能夠授與服務作業的明確存取授權。 透過示範明確資料存取授權的程式, 客戶加密箱也可能會協助組織符合特定合規性義務, 例如 HIPAA 和 FEDRAMP。

## <a name="which-users-benefit-from-the-service"></a>哪些使用者從服務獲益？

授權使用者的 Office 365 E5, Microsoft 365 E5, Microsoft 365 E5 合規性, 以及 Office 365 的高級規範可從客戶加密箱獲益。

## <a name="how-do-users-benefit-from-the-service"></a>使用者如何從服務獲益？

使用者可從客戶加密箱獲益, 確保 Microsoft 無法存取其內容以執行服務作業, 而不需要客戶明確核准。 客戶加密箱讓客戶加入核准工作流程, 以取得存取其內容的要求。 在支援程式中, 有時候會涉及 Microsoft 工程師, 以進行疑難排解並修正客戶報告的問題。 在大多數情況下, 您可以透過 Microsoft 已在其服務中進行的大量遙測和調試工具來解決問題。 不過, 在某些情況下, 您可能需要 Microsoft 工程師存取客戶內容, 以判斷根源並修正問題。 客戶加密箱要求工程師在核准工作流程中的最後一個步驟要求客戶進行存取。 這可讓組織選擇核准或拒絕這些要求, 讓他們可以直接控制 Microsoft 工程師是否可以存取組織的使用者資料。

## <a name="how-is-the-service-provisioneddeployed"></a>如何布建/部署服務？

系統管理員可以在 Microsoft 365 系統管理中心中開啟客戶加密箱控制項。 如需詳細資訊, 請參閱[Office 365 中的客戶加密箱](https://docs.microsoft.com/Office365/Admin/manage/customer-lockbox-requests)。 當客戶加密箱開啟時, 在存取其任何內容之前, 必須先取得該組織的核准。

## <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何僅將服務套用至已授權服務的租使用者中的使用者？

Microsoft 不會認可為未獲授權的使用者提供客戶加密箱存取控制核准要求。 經過一段時間後, 就會將授權檢查或目標工具新增至客戶加密箱, 以確保客戶加密箱可獲獲授權的使用者。

# <a name="privileged-access-management-in-office-365"></a>Office 365 中的許可權存取管理

特殊許可權存取管理 (PAM) 提供對 Office 365 中的特權系統管理工作的精細存取控制。 啟用特殊許可權存取管理之後, 使用者將需要透過高度範圍和時間限制的核准工作流程要求即時存取, 以完成提升和特權的工作。

## <a name="which-users-benefit-from-the-service"></a>哪些使用者從服務獲益？

Office 365 E5 的授權使用者, Microsoft 365 E5, Microsoft 365 E5 合規性, 以及 Office 365 Advanced 合規性可從 PAM 獲益。

## <a name="how-do-users-benefit-from-the-service"></a>使用者如何從服務獲益？

啟用 PAM 可讓組織以零為使用中的許可權來運作。 使用者會受益于因提供對其資料進行 unfettered 存取的系統管理存取所產生的弱點。

## <a name="how-is-the-service-provisioneddeployed"></a>如何布建/部署服務？

根據預設, 所有使用者在租使用者層級上都會啟用 PAM 功能。 如需設定 PAM 原則的詳細資訊, 請參閱[在 Office 365 中設定特殊許可權存取管理](https://docs.microsoft.com/office365/securitycompliance/privileged-access-management-configuration)。

## <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何僅將服務套用至已授權服務的租使用者中的使用者？

客戶可以透過核准者群組和存取原則 (可套用至授權的使用者), 以每一使用者為基礎來管理 PAM。 如需詳細資訊, 請參閱[Office 365 中的許可權存取管理](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)。

# <a name="data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Exchange Online、SharePoint Online 和商務用 OneDrive 的資料遺失防護

針對 Exchange Online、SharePoint Online 和商務用 OneDrive 的資料遺失防護 (DLP), 組織可以識別、監視及自動保護電子郵件和檔案 (包括儲存在 Microsoft 小組檔案中的檔案) 中的機密資訊。存放庫)。

## <a name="which-users-benefit-from-the-service"></a>哪些使用者從服務獲益？

Office 365 E3、Microsoft 365 E3 及 Office 365 資料遺失防護的授權使用者, 可從 DLP for Exchange Online、SharePoint Online 和商務用 OneDrive 中獲益。

## <a name="how-do-users-benefit-from-the-service"></a>使用者如何從服務獲益？

當檢查其電子郵件和檔案是否有機密資訊 (如組織的 DLP 原則所設定) 時, 使用者會受益于 DLP for Exchange Online、SharePoint Online 和商務用 OneDrive。

## <a name="how-is-the-service-provisioneddeployed"></a>如何布建/部署服務？

根據預設, Exchange Online 電子郵件、SharePoint 網站和 OneDrive 帳戶是為租使用者中的所有使用者啟用這些 DLP 功能的*位置 (工作負載)* 。 如需使用 DLP 原則的詳細資訊, 請參閱[資料遺失防護概述](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)。

## <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何僅將服務套用至已授權服務的租使用者中的使用者？

系統管理員可以在 [Office 365 安全性 & 規範中心] 的 [**資料遺失防護** > **位置**] 下, 自訂位置 (工作負載)、包含的使用者, 以及排除的使用者。

# <a name="data-loss-prevention-for-teams-chat-and-channel-conversations"></a>小組聊天和管道交談的資料遺失防護

透過資料遺失防護 (DLP) 來進行小組聊天和管道交談, 組織可以封鎖包含機密資訊 (例如財務資訊、個人識別資訊) 的交談和管道交談中的郵件。健康情況相關資訊或其他機密資訊。

## <a name="which-users-benefit-from-the-service"></a>哪些使用者從服務獲益？

Office 365 E5 的授權使用者, Microsoft 365 E5, Microsoft 365 E5 合規性, 以及 Office 365 Advanced 合規性可從 DLP 進行小組聊天和管道交談。

## <a name="how-do-users-benefit-from-the-service"></a>使用者如何從服務獲益？

寄件者在其外送聊天和管道交談訊息中有機密資訊已檢查過的敏感資訊, 如組織的 DLP 原則所設定。

## <a name="how-is-the-service-provisioneddeployed"></a>如何布建/部署服務？

依預設, 小組聊天和管道交談為租使用者中所有使用者的 DLP 功能的*已啟用位置 (工作負載)* 。 如需使用 DLP 原則的詳細資訊, 請參閱[資料遺失防護概述](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)。

## <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何僅將服務套用至已授權服務的租使用者中的使用者？

系統管理員可以在 [Office 365 安全性 & 規範中心] 的 [**資料遺失防護** > **位置**] 下, 自訂位置 (工作負載)、包含的使用者, 以及排除的使用者。

# <a name="information-barriers"></a>資訊障礙

資訊屏障是系統管理員可以設定的原則, 以防止個人或群組相互通訊。 例如, 如果一個部門處理的資訊不應該與其他部門共用, 或群組需要防止與外部連絡人進行通訊, 則此方法很有用。 資訊屏障原則也會防止查閱和探索。 這表示, 如果您嘗試與不應與之通訊的人員進行通訊, 則不會在 [人員選擇] 中找到該使用者。

## <a name="which-users-benefit-from-the-service"></a>哪些使用者從服務獲益？

Office 365 E5 的授權使用者, Microsoft 365 E5, Microsoft 365 E5 合規性, 以及 Office 365 Advanced 合規性可從資訊障礙中獲益。

## <a name="how-do-users-benefit-from-the-service"></a>使用者如何從服務獲益？

使用者無法與其他人通訊時, 會從資訊障礙的高級規範功能獲益。 例如：

| 案例                                                                                                                                                                                                              | 誰需要授權？ |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| 兩個群組 (群組1和群組 2) 無法彼此通訊 (亦即, 群組1使用者限制于與群組2使用者通訊, 而群組2使用者則會受到限制, 無法與群組1使用者通訊。 | 群組1和群組2中的使用者                    |
| 群組1中的使用者會受到限制, 無法與公司的其餘部分進行通訊。                                                                                                                                       | 僅限群組1中的使用者                                |
| 公司的其餘部分會受到限制, 無法與群組1通訊。                                                                                                                                                 | 除了群組1中的使用者以外的所有使用者                    |
| 群組1使用者受到限制, 無法與群組2使用者通訊, 但是群組2使用者可以與群組1使用者通訊。                                                                                              | 僅限群組1中的使用者                                |

## <a name="how-is-the-service-provisioneddeployed"></a>如何布建/部署服務？

系統管理員可以使用安全性 & 規範中心中的 PowerShell Cmdlet 來建立及管理資訊障礙原則。 系統管理員必須被指派 Microsoft 365 企業通用系統管理員、Office 365 全域管理員或合規性系統管理員角色, 才能建立資訊屏障原則。 依預設, 這些原則會套用至租使用者中的所有使用者。 如需資訊障礙的詳細資訊, 請參閱[Microsoft 小組中的資訊障礙](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)。

## <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何僅將服務套用至已授權服務的租使用者中的使用者？

系統管理員可以在 Office 365 安全性 & 合規性中心內自訂位置 (工作負載)、包含的使用者, 以及排除的使用者。 例如, 如果所有使用者都有 Office 365 E3 的授權, 而且沒有授權 Office 365 Advanced 合規性/E5, 他們就不需要為組織建立任何資訊屏障原則。 如需詳細資訊, 請參閱[Microsoft 小組中的資訊障礙](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)。

# <a name="office-365-advanced-message-encryption"></a>Office 365 進階郵件加密

高級郵件加密可協助客戶符合合規性義務, 這些義務需要更靈活的控制, 超過外部收件者, 以及存取加密的電子郵件。 使用高級郵件加密時, 系統管理員可以透過可偵測敏感資訊類型的自動原則 (例如, 個人識別資訊或財務或健康情況識別碼) 來控制組織外共用的機密電子郵件, 或您可以使用關鍵字來加強保護, 方法是套用自訂電子郵件範本, 並透過安全的 web 入口網站來終止對加密電子郵件的存取。 此外, 系統管理員可以隨時撤銷存取權, 以進一步控制透過安全的網頁入口網站存取的加密電子郵件。

## <a name="which-users-benefit-from-the-service"></a>哪些使用者從服務獲益？

Office 365 E5 的授權使用者, Microsoft 365 E5, Microsoft 365 E5 合規性, 以及 Office 365 Advanced 合規性可從高級郵件加密獲益。

## <a name="how-do-users-benefit-from-the-service"></a>使用者如何從服務獲益？

郵件寄件者會受益于由高級郵件加密所提供的機密電子郵件所新增的控制權。

## <a name="how-is-the-service-provisioneddeployed"></a>如何布建/部署服務？

系統管理員在 [郵件流程規則] 底下的 Exchange 系統管理中心中建立及管理高級郵件加密原則。 依預設, 這些規則會套用至承租人上的所有使用者。 如需設定新郵件加密功能的詳細資訊, 請參閱[設定新的 Office 365 郵件加密功能](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)。

## <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何僅將服務套用至已授權服務的租使用者中的使用者？

系統管理員應該僅將高級郵件加密的郵件流程規則套用至授權的使用者。 如需定義郵件流程規則的詳細資訊, 請參閱[定義郵件流程規則以加密 Office 365 中的電子](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)郵件。
