---
title: 適用于美國政府環境的 SharePoint
ms.author: office365servicedesc
author: pamelaar
ms.reviewer: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 瞭解美國政府雲端客戶的 SharePoint 功能可用性。
ms.openlocfilehash: b0f36ea92b856a3fa9c1bf4ddd4cb4265655d1ae
ms.sourcegitcommit: 9961f5111b2b8b871183afcd03fcfb7fc05da4fc
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 01/21/2021
ms.locfileid: "49919746"
---
# <a name="sharepoint-for-us-government-environments"></a>適用于美國政府環境的 SharePoint

本文概述美國政府雲端與商業雲端之間的功能差異，如 [SharePoint 服務描述所列](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-service-description)。 SharePoint 適用于政府社群雲端 (GCC) 、GCC High 和 DoD 環境。 

有關政府雲端功能詳細資訊，包括資格與購買，請參閱 [Microsoft 365 政府版 - 如何購買](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy)。 若要比較 Office 365 政府版方案，請參閱 [Office 365 政府版方案](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)。

若要瞭解管理網路連接時所需的端點，請參閱 Office [365](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) 美國政府 GCC High 端點或 [Office 365](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)美國政府 DoD 端點。

除了享受 Office 365 的功能之外，組織也受益于美國政府雲端環境所獨有的下列功能：

-   貴組織的客戶內容在邏輯上與 Microsoft 商業 Office 365 服務中的客戶內容分隔。
-   組織的客戶內容儲存於美國境內。
-   只有經過篩選的 Microsoft 人員可以存取組織的客戶內容。
-   政府雲端環境符合美國公用組織客戶所需的認證與規定。

我們的目標是提供所有 SharePoint 商業功能至政府雲端環境。 部分功能因為政府雲端客戶的需求而無法使用。 其他功能即將在政府環境中提供，但尚未提供。 請參閱下列各節，以瞭解政府雲端環境中的功能可用性。

## <a name="developer-features"></a>開發人員功能

商業客戶開發人員功能與政府雲端客戶開發人員功能之間沒有任何已知差異。

- 與外部應用程式的連結 ，例如，適用于附加元件之資料來源，僅限於位於您政府環境支援之系統安全性界限內的來源。
- Business Connectivity Services (BCS) 功能支援在雲端服務的安全性邊界內保持可連接的資料來源。

如果您在網站上使用協力廠商應用程式，請審查協力廠商在評估這些服務對貴組織適當使用時所提供的隱私權與合規性聲明。 協力廠商應用程式和服務可能包括在政府雲端以外，因此未涵蓋其合規性和資料保護承諾的協力廠商系統上儲存、傳送及處理貴組織的客戶資料。 

## <a name="it-admin-features"></a>IT 系統管理功能

以下是商業客戶及政府雲端客戶之 IT 系統管理功能之間的差異。

- GCC High 客戶無法變更網站位址
- 混合式 SharePoint Server 不適用於所有政府雲端客戶
- SharePoint 移移工具和移移管理員需要變更設定。 詳情請參閱 [SPMT 政府雲端支援](/sharepointmigration/spmt-install-issues#government-cloud-support)。
- Mover.io尚未支援
- 並非所有政府雲端客戶都提供多地理位置服務

有關 FastTrack 移移的資訊，請參閱 [Office 365 美國政府服務說明](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#data-migrations-performed-by-fasttrack)。

## <a name="security-and-compliance-features"></a>安全性與合規性功能

商業客戶以及政府雲端客戶的安全性與合規性功能之間沒有任何已知的差異。

有關安全性與合規性功能的資訊，請參閱 [安全性&規範中心](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-securitycompliance-center)。

有關 Azure Active Directory 政府版功能的資訊，請參閱 [Azure 政府安全性 + 身分識別檔](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory)。 

有關適用于政府之 Azure 資訊保護功能的資訊，請參閱 [Azure 資訊保護進位政府服務說明](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description)。 

## <a name="sites-and-content"></a>網站和內容

以下是商業客戶的網站與內容功能，以及政府雲端客戶網站與內容功能之間的差異：

- 仰賴網際網路服務之連結的網頁元件 ，例如 Amazon Kindle、Bing 地圖服務、Twitter 和 YouTube 網頁元件無法如預期方式使用
- 組織資產庫未提供
- GCC High 和 DoD 客戶無法新增清單和頁面至 Teams
- SharePoint Online for GCC High 內的圖形功能目前已停用。 目前可能無法使用任何仰賴 Microsoft Graph 的服務

## <a name="search-features"></a>搜尋功能

以下是商業客戶搜尋功能與政府雲端客戶搜尋功能之間的差異：

- Microsoft Search 整合並未提供。

## <a name="sharing-and-sync"></a>共用與同步

有關商業雲端與政府雲端環境之間的功能差異，請參閱 [檔案共用](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/gcc-high-and-dod#file-sharing)。

## <a name="plan-for-governance"></a>監管計畫

您移到雲端後，內建系統管理控制項提供轉換體驗。 決定您的監管需求，以及您可以如何符合這些需求。 請前往 [規劃監管，以轉換使用 Microsoft 365](https://resources.techcommunity.microsoft.com/teamwork-governance/) 的團隊合作，以瞭解更多資訊。 您可以找到 Office 365 群組、SharePoint、Teams 等的指引。

## <a name="deploy-sharepoint-for-collaboration"></a>部署 SharePoint 進行共同合作

在 Microsoft 美國政府雲端設定您的組織之後，請遵循 SharePoint 採用資源中心內所述的 [建議部署路徑](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/)。 請務必參與您的採用和變更管理世界。
您也可以使用 [FastTrack](https://www.microsoft.com/fasttrack) 或您選擇的合作夥伴，將服務推出給使用者。
請流覽 [Microsoft 信任中心](https://www.microsoft.com/trust-center) ，深入瞭解 Microsoft 如何執行安全性、隱私權和合規性，以及我們授權組織服務客戶的核心核心。
