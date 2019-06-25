---
title: Office 365 安全規範中心
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5a693243-2f13-4c7e-af1a-779c0752ae35
description: Office 365 安全性&amp;與規範中心的設計目的是協助您跨組織的 Office 365 管理合規性功能。 Links to existing SharePoint and Exchange compliance features bring together compliance capabilities across Office 365.
ms.openlocfilehash: 96b9e2c9528f0ea5052ec73fa4f514f2eb767b21
ms.sourcegitcommit: 7a67ef94d2f9101a7f9d8989bfd5013bc89dce00
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/07/2019
ms.locfileid: "34780642"
---
# <a name="office-365-security-amp-compliance-center"></a>Office 365 Security &amp; Compliance Center

[Office 365 安全性&amp;與規範中心](https://docs.microsoft.com/office365/securitycompliance/)的設計目的是協助您跨組織的 Office 365 管理合規性功能。 Links to existing SharePoint and Exchange compliance features bring together compliance capabilities across Office 365. 
  
> [!NOTE]
> Currently, many of the compliance features are still accessible through service-specific management interfaces, such as the Exchange admin center (EAC). However, this will change in the future as more service-independent compliance features are added to the Security &amp; Compliance Center. 
  
## <a name="security-amp-compliance-center-availability-for-business-and-enterprise-plans"></a>商務&amp;和企業方案的安全性合規性中心可用性

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商務基本版** <br/> |**Office 365 商務進階版** <br/> |**Office 365 企業版 E1** <br/> **Office 365 美國政府版 G1** <br/> |**Office 365 企業版 E3** <br/> **Office 365 美國政府版 G3** <br/> |**Office 365 企業版 E5** <br/> |**Office 365 企業版 F1** <br/> **Office 365 美國政府版 F1** <br/> |
|[存取安全&amp;規範中心](https://docs.microsoft.com/office365/securitycompliance/go-to-the-securitycompliance-center) <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|[Office 365 雲端 App 安全性](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security) <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |是  <br/> |否  <br/> |
|[威脅管理](https://docs.microsoft.com/office365/securitycompliance/protect-against-threats), 例如郵件篩選和反惡意程式碼  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|針對網路釣魚活動<sup>6</sup>的[高級威脅管理](https://docs.microsoft.com/office365/securitycompliance/office-365-ti), 例如客戶加密箱和威脅瀏覽器 <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |是  <br/> |否  <br/> |
|[行動裝置管理](https://support.office.com/article/set-up-mobile-device-management-mdm-in-office-365-dd892318-bc44-4eb1-af00-9db5430be3cd) <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|[Exchange Online、SharePoint Online 和商務用 OneDrive 的資料遺失防護](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)<sup>7</sup><br/> |否  <br/> |否  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Microsoft 小組聊天和管道交談的資料遺失防護](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies) <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |是  <br/> |否  <br/>|
|[資料](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)控管<sup>1</sup> <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|[高級資料](https://docs.microsoft.com/office365/securitycompliance/labels)控管<sup>2</sup> <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |是  <br/> |否  <br/> |
|[搜尋和調查](https://docs.microsoft.com/office365/securitycompliance/datainvestigations/search-for-data) <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|[eDiscovery 搜尋](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases) <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|[eDiscovery 匯出](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases?) <br/> |否  <br/> |否  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[eDiscovery 保留 (包括查詢式 eDiscovery 保留)](https://support.office.com/article/eDiscovery-cases-in-the-Office-365-Security-Compliance-Center-8dd335ab-29d0-41c3-8dd8-9f7c7481e60c#step3_1) <br/> |否  <br/> |否  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[高級 eDiscovery](https://docs.microsoft.com/office365/securitycompliance/office-365-advanced-ediscovery)<sup>5</sup> <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |是  <br/> |否  <br/> |
|[存檔](https://technet.microsoft.com/library/exchange-online-limits.aspx) <br/> |是<sup>3</sup> <br/> |是<sup>3</sup> <br/> |是<sup>3</sup> <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|手動保留原則  <br/> |否  <br/> |否  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
   
<sup>1</sup>資料控管可讓使用者建立、發佈和手動將標籤套用至檔;使用磁片磁碟機運送或透過網路匯入資料。<br/>
<sup>2</sup>高級資料控管可讓您根據保留或刪除原則或兩者來分類資訊, 以保留重要資訊並刪除不重要的資訊。 它包含智慧/自動化動作, 例如建議原則、自動將標籤套用至資料、套用標籤至資料、套用標籤 (根據敏感資料類型或查詢、處置檢查, 以及使用智慧匯入篩選)。 它也包含監督功能, 以出於安全性和合規性目的而檢查員工的通訊。<br/>
<sup>3</sup> 50 GB 的限制。 <br/>
<sup>4</sup>無限制。 <br/>
<sup>5</sup>美國和西歐 (荷蘭) 地區支援高級 eDiscovery。 (來自加拿大和亞太地區的客戶資料會匯出至美國。 從歐洲、中東和非洲的客戶資料匯出至西歐 [荷蘭]。<br>
<sup>6</sup> Office 365 企業版 E5 和 Office 365 企業版 E3 的獨立365服務提供了高級威脅防護。<br> 
<sup>7</sup>包含儲存在 Microsoft 小組存放庫中的檔案。<br/>
   
## <a name="security-amp-compliance-center-availability-for-standalone-plans"></a>獨立&amp;方案的安全性合規性中心可用性

|||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Online 方案 1** <br/> |**Exchange Online 方案 2** <br/> |**Exchange Online Kiosk** <br/> |**SharePoint Online 計劃 1** <br/> |**SharePoint Online 計劃 2** <br/> |**商務用 Skype Online 方案 1** <br/> |**商務用 Skype Online 方案 2** <br/> |
|[存取安全&amp;規範中心](https://docs.microsoft.com/office365/securitycompliance/go-to-the-securitycompliance-center) <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|[Office 365 雲端 App 安全性](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security) <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |是  <br/> |
|[威脅管理](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security), 例如郵件篩選和反惡意程式碼  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|針對網路釣魚活動的[高級威脅管理](https://docs.microsoft.com/office365/securitycompliance/office-365-ti), 例如客戶加密箱和威脅瀏覽器  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |
|[行動裝置管理](https://support.office.com/article/set-up-mobile-device-management-mdm-in-office-365-dd892318-bc44-4eb1-af00-9db5430be3cd) <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|[資料遺失防護](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies) <br/> |否  <br/> |是  <br/> |否  <br/> |否  <br/> |是 <sup>7<sup> <br/> |否  <br/> |是  <br/> |
|[資料](https://docs.microsoft.com/office365/securitycompliance/retention-policies)控管<sup>1</sup> <br/> |是<sup>2</sup> <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|[高級資料](https://docs.microsoft.com/office365/securitycompliance/labels)控管<sup>3</sup> <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |
|[搜尋和調查](https://docs.microsoft.com/office365/securitycompliance/datainvestigations/search-for-data) <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|[eDiscovery 搜尋](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases) <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |否  <br/> |否  <br/> |
|[eDiscovery 匯出](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases) <br/> |否  <br/> |是  <br/> |否  <br/> |否  <br/> |是  <br/> |無<sup>4</sup> <br/> |無<sup>4</sup> <br/> |
|[eDiscovery 保留 (包括查詢式 eDiscovery 保留)](https://support.office.com/article/eDiscovery-cases-in-the-Office-365-Security-Compliance-Center-8dd335ab-29d0-41c3-8dd8-9f7c7481e60c#step3_1) <br/> |否  <br/> |是  <br/> |否  <br/> |否  <br/> |是  <br/> |否  <br/> |否  <br/> |
|[高級 eDiscovery](https://docs.microsoft.com/office365/securitycompliance/office-365-advanced-ediscovery)<sup>5</sup> <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |
|[](https://technet.microsoft.com/library/exchange-online-limits.aspx)封存<sup>6</sup> <br/> |是  <br/> |是  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |否  <br/> |
|手動保留原則  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
   
<sup>1</sup>資料控管可讓使用者建立、發佈和手動將標籤套用至檔;使用磁片磁碟機運送或透過網路匯入資料。 <br/>
<sup>2</sup>需要購買 Exchange Online 封存附加元件。 <br/>
<sup>3</sup>高級資料控管可讓您根據保留或刪除原則或兩者來分類資訊, 以保留重要資訊並刪除不重要的資訊。 它包含智慧/自動化動作, 例如建議原則、自動將標籤套用至資料、套用標籤至資料、套用標籤 (根據敏感資料類型或查詢、處置檢查, 以及使用智慧匯入篩選)。 它也包含監督功能, 以出於安全性和合規性目的而檢查員工的通訊。<br/>
<sup>4</sup>會將 Skype 交談儲存為信箱的一部分。 <br/>
<sup>5</sup>高級 EDiscovery 需要 Office 365 企業版 E5 或附加元件授權。 <br/>
<sup>6</sup> Skype 封存位於使用者的信箱內。<br/> 
<sup>7</sup>包含儲存在 Microsoft 小組存放庫中的檔案。 
  
## <a name="security-amp-compliance-center-availability-in-office-365-operated-by-21vianet"></a>Security &amp; Compliance Center availability in Office 365 operated by 21Vianet

在任何由世紀運作的 Office 365 方案中, 無法使用安全性 & 合規性中心。
  
## <a name="security-amp-compliance-center-availability-in-office-365-germany"></a>Security &amp; Compliance Center availability in Office 365 Germany

您可以在 Office 365 德國取得安全性 & 規範中心。 如需有關 Office 365 德國的詳細資訊, 請參閱[Office 365 德國](office-365-germany.md)。
  

