---
title: 適用于美國政府環境的 SharePoint
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.reviewer: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: 深入瞭解美國政府雲端客戶的 SharePoint 功能可用性。
ms.openlocfilehash: 1c584c3bfd62b7573f4c9bcc0c0fb5402b2d9bef
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/24/2021
ms.locfileid: "59673000"
---
# <a name="sharepoint-for-us-government-environments"></a>適用于美國政府環境的 SharePoint

本文概要說明美國政府雲端與商業性雲端之間的功能差異，如[SharePoint 服務說明](../../sharepoint-online-service-description/sharepoint-online-service-description.md)所示。 SharePoint 可用於政府社群雲端 (GCC) 、GCC 高及 DoD 的環境。 

如需政府雲端（包括資格和購買）的詳細資訊，請參閱[Microsoft 365 政府–如何購買](./microsoft-365-government-how-to-buy.md)。 若要比較 Office 365 政府版計畫，請參閱[Office 365 政府版計畫](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)。

若要在管理網路連線時瞭解必要的端點，請參閱[Office 365 美國政府 GCC 高階端點](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business)或[Office 365 美國政府 DoD 端點](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)。

除了享受 Office 365 的功能和功能之外，組織還會受益于美國政府雲端環境所獨有的下列功能：

-   您組織的客戶內容與 Microsoft 的商業 Office 365 服務中的客戶內容有邏輯隔離。
-   組織的客戶內容儲存於美國境內。
-   只有經過篩選的 Microsoft 人員可以存取組織的客戶內容。
-   政府雲端環境符合美國公共部門客戶所需的認證和資格鑒定。

我們的目標是將所有 SharePoint 商業功能和功能提供給政府雲端環境。 由於政府雲端客戶的需求，有些功能無法使用。 其他功能會進入政府環境，但尚未提供。 請參閱下列各節以瞭解政府雲端環境中的功能可用性。

## <a name="developer-features"></a>開發人員功能

商務客戶的開發人員功能和政府雲端客戶的開發人員功能都沒有已知的差異。

- 外部應用程式的連線（如增益集的資料來源）會受限於位於政府環境所支援之系統安全性界限內的來源。
- Business Connectivity在您的雲端服務安全性界限內可存取資料來源的連線情況下，可支援服務 (BCS) 功能。

如果您在網站上使用協力廠商應用程式，請在評估組織的適當使用服務時，複查協力廠商所提供的隱私權和符合性聲明。 協力廠商的應用程式和服務可能涉及在政府雲端以外的協力廠商系統上儲存、傳送和處理組織的客戶資料，因此不在其合規性和資料保護承諾範圍內。 

## <a name="it-admin-features"></a>IT 系統管理功能

以下是適用于商務客戶的 IT 系統管理功能與政府雲端客戶之 IT 系統管理員功能之間的差異。

- GCC 高客戶無法使用變更網站位址
- SharePoint 遷移工具和遷移管理員需要變更設定。 如需詳細資訊，請參閱 [SPMT 政府 cloud support](/sharepointmigration/spmt-install-issues#government-cloud-support)。
- 尚未支援 Mover.io
- 多地理位置無法供所有政府雲端客戶使用

如需 FastTrack 遷移的相關資訊，請參閱[Office 365 US 政府服務說明](./office-365-us-government.md#data-migrations-performed-by-fasttrack)。

## <a name="security-and-compliance-features"></a>安全性和符合性功能

商業客戶的安全性和符合性功能和政府雲端客戶的安全性和符合性功能之間沒有任何已知的差異。

如需安全性與合規性功能的相關資訊，請參閱 [安全性 & 規範中心](../office-365-securitycompliance-center.md)。

如需政府 Azure Active Directory 功能的相關資訊，請參閱[Azure 政府安全性 + 身分識別檔](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory)。 

如需有關適用于政府之 Azure 資訊保護功能的詳細資訊，請參閱[Azure 資訊保護進階版政府服務說明](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description)。 

如需 SharePoint Syntex 功能的相關資訊，請參閱[SharePoint Syntex 功能服務說明](/office365/servicedescriptions/sharepoint-syntex-service-description/sharepoint-syntex-features)。

## <a name="sites-and-content"></a>網站和內容

以下是商務客戶的網站和內容功能與政府雲端客戶之網站和內容功能之間的差異：

- 依靠網際網路服務連線（例如 Amazon Kindle、Bing 地圖服務、Twitter 及 YouTube 網頁元件）的網頁元件，不會如預期般運作
- 組織資產庫無法使用
- GCC 高和 DoD 客戶無法將清單及頁面新增至 Teams
- SharePoint Online 中 GCC 高的 Graph 功能目前已停用。 任何依賴 Microsoft Graph 的服務目前可能無法使用
- 依靠網際網路服務連線的功能（例如 [股票影像] 索引標籤）不會如預期般運作。
- 無法使用檔案和網站活動的通知
- 「新聞網頁元件」只會從目前的網站納入資訊。 GCC 高和 DoD 客戶無法使用來自所選網站或 hub 新聞匯總的資訊（來自關聯的網站）

## <a name="search-features"></a>搜尋功能

以下是商務客戶之搜尋功能與政府雲端客戶之搜尋功能之間的差異：

- GCC 中無法使用 Microsoft 搜尋。

## <a name="sharing-and-sync"></a>共用及同步處理

如需商業雲端和政府雲端環境之間的功能差異，請參閱檔案 [共用](./gcc-high-and-dod.md#file-sharing)。

## <a name="plan-for-governance"></a>規劃管理

您可以使用內建的系統管理控制，將您移至雲端提供 transformative 經驗。 決定您的控管需求，以及如何符合您的需求。 請參閱[Plan for Plan with Microsoft 365](https://resources.techcommunity.microsoft.com/teamwork-governance/)中的轉換，以取得詳細資訊。 您會發現 Office 365 群組、SharePoint、Teams 等相關指引。

## <a name="deploy-sharepoint-for-collaboration"></a>部署協同 SharePoint 以進行共同作業

在 Microsoft US 政府雲端中設定組織之後，請遵循[SharePoint 採用資源中心](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/)中所述的建議部署途徑。 請務必與您的採用和變更管理擁護者接洽。
您也可以使用[FastTrack](https://www.microsoft.com/fasttrack)或您所選的合作夥伴，向您的使用者推出服務。
若要深入瞭解 Microsoft 的安全性、隱私權及合規性，請造訪 [Microsoft 信任中心](https://www.microsoft.com/trust-center) ，以瞭解如何讓組織為客戶服務的核心原則。

## <a name="configuring-sharepoint-hybrid-configuration-wizard-support-for-all-government-cloud-customers"></a>為所有政府雲端客戶設定 SharePoint 混合式設定向導支援

SharePoint 混合式設定向導支援搭配特殊 SPO 環境 SharePoint 混合式功能。

您必須在 **.config** 檔案中編輯與環境相關的參數值，才能讓該環境使用 SharePoint 的混合式功能。 請參閱 [編輯設定檔](#editing-configuration-file)。

> [!NOTE]
> 如需 SharePoint 混合式功能提供支援之特殊 SPO 環境的詳細資訊，請參閱[支援的環境](#supported-environments)。

## <a name="editing-configuration-file"></a>編輯設定檔

1. 安裝或更新 SharePoint 混合式設定向導。
2. 移至安裝 SharePoint 混合式設定向導的資料夾。 例如，`%LOCALAPPDATA%\Apps\HybridSP\HybridSP`
3. 在文字編輯器（例如記事本）中啟動 **microsoft.online.cse.hybridsp.common.dll.config** 檔案。
此檔案中的內容將在下列螢幕擷取畫面中所示：

:::image type="content" source="../../media/content.png" alt-text="設定檔中的內容":::

4. 修改參數的值 `SPOEnvironmentType` 。
5. 將變更儲存在 **microsoft.online.cse.hybridsp.common.dll.config** 檔中。
6. 重新開機 SharePoint 混合式設定向導。
   會套用設定，且已設定的 SPO 環境可使用 SharePoint 混合式功能。

## <a name="supported-environments"></a>支援的環境

SharePoint 混合式功能支援下列 SPO 環境：

- 公開
- PPE
- GCC
- GccHigh
- DoD
- 自訂

如果客戶將值設 `SPOEnvironmentType` 為 **custom**，，， `AuthorityEndPoint` ， `AADGraphEndPoint` 和 `MSGraphEndPoint` 鍵會用來設定該自訂 SPO 環境的端點。

如果 `SPOEnvironmentType` 值設為 **Custom** 以外的任何值，則 `AuthorityEndPoint` `AADGraphEndPoint` 會忽略、和鍵， `MSGraphEndPoint` 而且 SharePoint 混合式設定向導會使用適合這些 SPO 環境類型的硬編碼值。
