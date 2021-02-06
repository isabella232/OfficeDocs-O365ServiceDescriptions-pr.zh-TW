---
title: 安全性與合規性中心
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5a693243-2f13-4c7e-af1a-779c0752ae35
description: 安全性與 &amp; 合規性中心的設計目的是協助您管理組織的 Office 365 的相容性功能。 現有 SharePoint 和 Exchange 合規性功能的連結可將整個 Office 365 的合規性功能結合在一起。
ms.openlocfilehash: 0116ecf3f46c2d870d88a5d1ef53e18452a53e7b
ms.sourcegitcommit: f98239a5631ba312d63753ffce83a7413a143ee5
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 02/05/2021
ms.locfileid: "50122193"
---
# <a name="security-amp-compliance-center"></a>安全性與 &amp; 合規性中心

[安全性與 &amp; 合規性中心](https://protection.office.com/)的設計目的是協助您管理組織的 Office 365 的相容性功能。 現有 SharePoint 和 Exchange 合規性功能的連結可將整個 Office 365 的合規性功能結合在一起。
  
> [!NOTE]
> Currently, many of the compliance features are still accessible through service-specific management interfaces, such as the Exchange admin center (EAC). However, this will change in the future as more service-independent compliance features are added to the Security &amp; Compliance Center.

若要查看授權您的使用者從 Microsoft 365 規範功能受益于2020年4月1日的選項，請下載詳細的 Microsoft 365 相容性授權比較。 [ (PDF) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [ (Excel) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)
  
## <a name="security-amp-compliance-center-availability-for-business-and-enterprise-plans"></a>&amp;商務和企業方案的安全性與合規性中心可用性

| 功能 | Microsoft 365 商務基本版 | Microsoft 365 商務標準版 | Microsoft 365 商務進階版 | Office 365 E1，Office 365 美國政府版 G1 | Office 365 E3，Office 365 美國政府版 G3 | Office 365 E5 | Office 365 F3，Office 365 美國政府（F3）|
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|[存取安全性與合規性中心](https://docs.microsoft.com/office365/securitycompliance/go-to-the-securitycompliance-center)  |是   |是   |是   |是   |是   |是   |是   |
|[資料遺失防護，適用于 Exchange online、SharePoint 線上及 OneDrive （適用于 Business](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies)<sup>2</sup> ） | 否 | 否  |否   | 是 | 是 | 是 | 否  |
|[手動敏感度標籤](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)<sup>3</sup> | 否 | 否  |否   | 是 | 是 | 是 | 否  |
|[電子文件探索案例](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases)  |是   |是   |是   |是   |是   |是   |是   |
|[電子文件探索保留 (包括查詢式 電子文件探索保留)](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-4-place-content-locations-on-hold)  |否   |否   |否  |否   |是   |是   |否   |
|[電子文件探索匯出](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-6-export-the-results-of-a-content-search-associated-with-a-case)  |否   |否   |否   |否   |是   |是   |否   |
|[基本審核](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)<sup>1</sup> |是   |是   |是|是   |是   |是   |是   |
|[Office 365 郵件加密 (OME) 基本](https://docs.microsoft.com/microsoft-365/compliance/ome)  |否   |否   |否   |否   |是  |是   |否   |

<sup>1</sup> 除了 E5) 之外，所有包含基本 (審核的計畫的審計記錄會保留90天。 因為 E5 包含高級審計，所以審計記錄會保留最多一年。 此外，您也可以使用 [Office 365 管理活動 API](https://docs.microsoft.com/office/office-365-management-api/office-365-management-activity-api-reference) ，從統一的審計記錄檔中取得事件。

<sup>2</sup> 需要 Office 365 資料遺失防護附加元件。

<sup>3</sup> 在 Azure 資訊保護 P1 和 P2 中也會包含靈敏度標籤。

## <a name="security-amp-compliance-center-availability-for-standalone-plans"></a>&amp;獨立方案的安全性與合規性中心可用性

| 功能 | Exchange Online Plan 1 | Exchange Online Plan 2 | Exchange Online Kiosk | SharePoint Online 方案 1 | SharePoint Online 方案 2 | 商務用 OneDrive 方案 1 | 商務用 OneDrive 方案 2 | 商務用 Skype Online 方案 1 | 商務用 Skype Online 方案 2|
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|[存取安全性與合規性中心](https://docs.microsoft.com/office365/securitycompliance/go-to-the-securitycompliance-center)  |是   |是   |是   |是   |是   |是   |是   |是   |是   |
|[Office 365 雲端 App 安全性](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)  |否   |否   |否   |否   |否   |否   |否   |否   |是   |
|[威脅管理](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security) (英文)，例如郵件篩選和反惡意程式碼   |是   |是   |是   |是   |是   |是   |是   |是   |是   |
|[高級威脅管理](https://docs.microsoft.com/office365/securitycompliance/office-365-ti)，例如網路釣魚活動的威脅瀏覽器   |否   |否   |否   |否   |否   |否   |否   |否   |否  |
|[客戶加密箱](https://docs.microsoft.com/office365/securitycompliance/customer-lockbox-requests)  |否   |否   |否   |否   |否   |否   |否   |否   |否   |
|[行動裝置管理](https://support.office.com/article/set-up-mobile-device-management-mdm-in-office-365-dd892318-bc44-4eb1-af00-9db5430be3cd)  |是   |是   |是   |是   |是   |是   |是   |是   |是   |
|[資料遺失防護，適用于 Exchange online、SharePoint 線上及 OneDrive 商務](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)用<sup>9</sup>  |否   |是   |否   |否   |是 <sup>7<sup>  |否  |是<sup>10</sup> |否   |是   |
|[Microsoft 小組的通訊資料遺失防護](https://docs.microsoft.com/microsoft-365/compliance/dlp-microsoft-teams)  |否   |否   |否   |否   |否   |否   |否   |否   |否   |
|[資訊屏障](https://docs.microsoft.com/office365/securitycompliance/information-barriers)  |否   |否   |否   |否   |否   |否   |否   |否   |否   |
|[資訊管理](https://docs.microsoft.com/office365/securitycompliance/retention-policies)<sup>1</sup>  |是<sup>2</sup>  |是   |是   |是   |是   |是<sup>10</sup>  |是<sup>10</sup>  |是   |是   |
|[高級資訊管理](https://docs.microsoft.com/office365/securitycompliance/labels)<sup>3</sup>  |否   |否   |否   |否   |否   |否   |否   |否   |否   |
|[內容搜尋](https://docs.microsoft.com/office365/securitycompliance/search-for-content)  |是   |是   |是   |是   |是  | 是<sup>10</sup>  |是<sup>10</sup>  |是   |是   |
|[電子文件探索案例](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases)  |是   |是   |是   |是   |是   |是<sup>10</sup>  |是<sup>10</sup>  |否   |否   |
|[電子文件探索匯出](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-6-export-the-results-of-a-content-search-associated-with-a-case)  |否   |是   |否   |否   |是   |否  |是<sup>10</sup> |否<sup>4</sup>  |否<sup>4</sup>  |
|[電子文件探索保留 (包括查詢式 電子文件探索保留)](https://support.office.com/article/eDiscovery-cases-in-the-Office-365-Security-Compliance-Center-8dd335ab-29d0-41c3-8dd8-9f7c7481e60c#step3_1)  |否   |是   |否   |否   |是   |否  |是<sup>10</sup> |否<sup>4</sup>  |否<sup>4</sup>  |
|[Advanced eDiscovery](https://docs.microsoft.com/office365/securitycompliance/compliance20/overview-ediscovery-20)<sup>5</sup>  |否   |否   |否   |否   |否   |否   |否   |否   |否   |
|[](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)封存<sup>6</sup>  |否   |是   |否   |是   |是   |是<sup>10</sup> |是<sup>10</sup>  |否   |否   |
|[基本審核](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)<sup>8</sup>|是|是|是|是|是|是<sup>10</sup>|是<sup>10</sup>|否|否|
|進階稽核|否|否|否|否|否|否|否|否|否|
|[通訊合規性 (監察原則) ](https://docs.microsoft.com/office365/securitycompliance/supervision-policies)  |否   |否   |否   |否   |否   |否   |否   |否   |否   |
|[Office 365 郵件加密 (OME)](https://docs.microsoft.com/microsoft-365/compliance/ome)  |否   |是   |否   |否   |是   |否   |否|否|否|
|[Office 365 進階郵件加密](https://docs.microsoft.com/microsoft-365/compliance/ome-advanced-message-encryption)  |否   |否   |否   |否   |是   |否   |否|否|否|
|[特殊許可權存取管理](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-overview)  |否   |否   |否   |否   |是   |否   |否|否|否|

<sup>1</sup> 資訊管理可讓使用者建立、發佈和手動將標籤套用至檔;使用磁片磁碟機運送或透過網路匯入資料。 您可以在 E3 和 E5 使用這些功能，只在 E1 中使用有限的可用性。 如需 E1、E3 及 E5 中可用之功能的完整清單，請參閱詳細的 Microsoft 365 相容性授權比較。 [ (PDF) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [ (Excel) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

<sup>2</sup> 需要購買 Exchange Online 封存附加元件。

<sup>3</sup> 高級資訊管理可讓您根據保留或刪除原則或兩者來分類資訊，保留重要資訊並刪除不重要的資訊。 它包含智慧/自動化的動作，例如推薦原則、自動將標籤套用至資料、套用標籤的敏感資料類型或查詢、處置檢查，以及使用智慧匯入篩選。 其中也包含監督功能，可讓您針對安全性與合規性目的檢閱員工通訊。

<sup>4</sup> 會將 Skype 交談儲存為信箱的一部分。

<sup>5</sup> 「高級 eDiscovery」需要 Office 365 E5 或附加元件授權。

<sup>6</sup> Skype 封存位於使用者的信箱內。

<sup>7</sup> 包括儲存在 Microsoft 團隊存放庫中的檔案。

<sup>8</sup> 所有包含基本審核之方案的審計記錄會保留90天。 此外，您也可以使用 [Office 365 管理活動 API](https://docs.microsoft.com/office/office-365-management-api/office-365-management-activity-api-reference) ，從統一的審計記錄檔中取得事件。

<sup>9</sup> 需要 Office 365 資料遺失防護附加元件。

<sup>10</sup> 僅限儲存在商務 OneDrive 中的檔案。

<sup>11</sup> 使用保留原則將使用者信箱保留，需要 Exchange online 方案2或 exchange online 封存授權。
  
## <a name="security-amp-compliance-center-availability-in-office-365-operated-by-21vianet"></a>Security &amp; Compliance Center availability in Office 365 operated by 21Vianet

「合規性中心」是由世紀運作之 Office 365 的 E3 計畫中提供的。
  
## <a name="security-amp-compliance-center-availability-in-office-365-germany"></a>Security &amp; Compliance Center availability in Office 365 Germany

安全性 & 規範中心可用於 Office 365 德國。 如需有關 Office 365 德國的資訊，請參閱 [office 365 德國](office-365-germany.md)。
