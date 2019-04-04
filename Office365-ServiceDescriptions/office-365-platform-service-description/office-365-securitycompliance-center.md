---
title: Office 365 安全規範中心
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5a693243-2f13-4c7e-af1a-779c0752ae35
description: Office 365 安全性&amp;合規性中心設計來協助您管理 Office 365 組織符合性功能。 Links to existing SharePoint and Exchange compliance features bring together compliance capabilities across Office 365.
ms.openlocfilehash: a3534103053d4299177880ef1992ad0b7b36b5f7
ms.sourcegitcommit: d8369cb3d7886e33f9738ad3e95b02de0b54184e
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/03/2019
ms.locfileid: "31411862"
---
# <a name="office-365-security-amp-compliance-center"></a>Office 365 Security &amp; Compliance Center

[Office 365 安全性&amp;合規性中心](https://go.microsoft.com/fwlink/?LinkID=824876)設計來協助您管理 Office 365 組織符合性功能。 Links to existing SharePoint and Exchange compliance features bring together compliance capabilities across Office 365. 
  
> [!NOTE]
> Currently, many of the compliance features are still accessible through service-specific management interfaces, such as the Exchange admin center (EAC). However, this will change in the future as more service-independent compliance features are added to the Security &amp; Compliance Center. 
  
## <a name="security-amp-compliance-center-availability-for-business-and-enterprise-plans"></a>安全性&amp;商務和企業版計劃的規範中心可用性

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商務基本版** <br/> |**Office 365 商務進階版** <br/> |**Office 365 企業版 E1** <br/> **Office 365 美國政府版 G1** <br/> |**Office 365 Enterprise E3** <br/> **Office 365 美國政府版 G3** <br/> |**Office 365 企業版 E5** <br/> |**Office 365 企業版 F1** <br/> **Office 365 美國政府版 F1** <br/> |
|[Access to the Security &amp; Compliance Center](https://go.microsoft.com/fwlink/?linkid=841313) <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|[Office 365 雲端 App 安全性](https://go.microsoft.com/fwlink/?linkid=845423) <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |是  <br/> |否  <br/> |
|[威脅管理](https://go.microsoft.com/fwlink/?linkid=845550)，例如郵件篩選和反惡意程式碼  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|[進階威脅管理，](https://go.microsoft.com/fwlink/?linkid=846673)例如網路釣魚活動<sup>6</sup>的客戶加密箱和威脅總管 <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |是  <br/> |否  <br/> |
|[行動裝置管理](https://go.microsoft.com/fwlink/?linkid=524859) <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|[資料遺失防護](https://go.microsoft.com/fwlink/?linkid=846843) <br/> |否  <br/> |否  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[資料控管](https://go.microsoft.com/fwlink/?linkid=863925)<sup>1</sup> <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|[進階資料控管](https://go.microsoft.com/fwlink/?linkid=842991)<sup>2</sup> <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |是  <br/> |否  <br/> |
|[搜尋和調查](https://go.microsoft.com/fwlink/?linkid=824872) <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|[eDiscovery 搜尋](https://go.microsoft.com/fwlink/?linkid=837776) <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|[eDiscovery 匯出](https://go.microsoft.com/fwlink/?linkid=837776) <br/> |否  <br/> |否  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[eDiscovery 保留 （包括查詢為基礎的 eDiscovery 保留）](https://support.office.com/article/eDiscovery-cases-in-the-Office-365-Security-Compliance-Center-8dd335ab-29d0-41c3-8dd8-9f7c7481e60c#step3_1) <br/> |否  <br/> |否  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[進階 eDiscovery](https://go.microsoft.com/fwlink/?linkid=715714)<sup>5</sup> <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |是  <br/> |否  <br/> |
|[封存](https://technet.microsoft.com/en-us/library/exchange-online-limits.aspx) <br/> |是<sup>3</sup> <br/> |是<sup>3</sup> <br/> |是<sup>3</sup> <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|手動保留/刪除原則  <br/> |否  <br/> |否  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
   
> <sup>1</sup>資料控管可讓使用者建立、 發佈及以手動方式將標籤套用至文件;使用磁碟機運送或透過網路; 匯入資料建立並套用保留/刪除原則工作負載、 使用者和群組。 套用至信箱的保留原則需要 Office 365 企業版 E3 或 E5。
<br/><sup>2</sup>進階的資料控管可讓您保留重要的資訊，並刪除不重要的資訊來分類保留或刪除原則或兩者為基礎的資訊。 它包含智慧型/自動化動作，例如建議原則，自動將標籤套用至資料，套用敏感資料類型或查詢、 處置檢閱，以及使用智慧匯入篩選器為基礎的標籤。 此外，它還會包含用於檢閱員工通訊安全性與合規性的用途，「 監督 」 功能。
<br/><sup>3</sup> 50 GB 限制。 
<br/><sup>4</sup>無限制。 
<br/><sup>5</sup>進階電子文件是在美國及支援西歐 （荷蘭） 區域中。 （從加拿大和亞太地區的客戶資料匯出至美國境內。 歐洲、 中東和非洲地區的客戶資料匯出至西歐 [荷蘭]。） <br/><sup>6</sup>進階威脅防護是可在 Office 365 企業版 E5 和 Office 365 企業版 E1 和 Office 365 企業版 E3 屬於獨立服務。 
  
## <a name="security-amp-compliance-center-availability-for-standalone-plans"></a>安全性&amp;獨立計劃的規範中心可用性

|||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Online Plan 1** <br/> |**Exchange Online Plan 2** <br/> |**Exchange Online Kiosk** <br/> |**SharePoint Online 方案 1** <br/> |**SharePoint Online 方案 2** <br/> |**商務用 Skype Online 方案 1** <br/> |**商務用 Skype Online 方案 2** <br/> |
|[Access to the Security &amp; Compliance Center](https://go.microsoft.com/fwlink/?linkid=841313) <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|[Office 365 雲端 App 安全性](https://go.microsoft.com/fwlink/?linkid=845423) <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |是  <br/> |
|[威脅管理](https://go.microsoft.com/fwlink/?linkid=845550)，例如郵件篩選和反惡意程式碼  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|[進階威脅管理，](https://go.microsoft.com/fwlink/?linkid=846673)例如網路釣魚活動的客戶加密箱和威脅總管  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |
|[行動裝置管理](https://go.microsoft.com/fwlink/?linkid=524859) <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|[資料遺失防護](https://go.microsoft.com/fwlink/?linkid=846843) <br/> |否  <br/> |是  <br/> |否  <br/> |否  <br/> |是  <br/> |否  <br/> |是  <br/> |
|[資料控管](https://go.microsoft.com/fwlink/?linkid=863925)<sup>1</sup> <br/> |是<sup>2</sup> <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|[進階資料控管](https://go.microsoft.com/fwlink/?linkid=842991)<sup>3</sup> <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |
|[搜尋和調查](https://go.microsoft.com/fwlink/?linkid=824872) <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|[eDiscovery 搜尋](https://go.microsoft.com/fwlink/?linkid=837776) <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |否  <br/> |否  <br/> |
|[eDiscovery 匯出](https://go.microsoft.com/fwlink/?linkid=837776) <br/> |否  <br/> |是  <br/> |否  <br/> |否  <br/> |是  <br/> |沒有<sup>4</sup> <br/> |沒有<sup>4</sup> <br/> |
|[eDiscovery 保留 （包括查詢為基礎的 eDiscovery 保留）](https://support.office.com/article/eDiscovery-cases-in-the-Office-365-Security-Compliance-Center-8dd335ab-29d0-41c3-8dd8-9f7c7481e60c#step3_1) <br/> |否  <br/> |是  <br/> |否  <br/> |否  <br/> |是  <br/> |否  <br/> |否  <br/> |
|[進階 eDiscovery](https://go.microsoft.com/fwlink/?linkid=715714)<sup>5</sup> <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |
|[封存](https://technet.microsoft.com/en-us/library/exchange-online-limits.aspx)<sup>6</sup> <br/> |是  <br/> |是  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |否  <br/> |
|手動保留/刪除原則  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |是  <br/> |否  <br/> |是  <br/> |
   
> <sup>1</sup>資料控管可讓使用者建立、 發佈及以手動方式將標籤套用至文件;使用磁碟機運送或透過網路; 匯入資料建立並套用保留/刪除原則工作負載、 使用者和群組。 套用至信箱的保留原則需要 Office 365 企業版 E3 或 E5。 
<br/><sup>2</sup>需要 Exchange Online Archiving 附加元件形式購買。 
<br/><sup>3</sup>進階的資料控管可讓您保留重要的資訊，並刪除不重要的資訊來分類保留或刪除原則或兩者為基礎的資訊。 它包含智慧型/自動化動作，例如建議原則，自動將標籤套用至資料，套用敏感資料類型或查詢、 處置檢閱，以及使用智慧匯入篩選器為基礎的標籤。 此外，它還會包含用於檢閱員工通訊安全性與合規性的用途，「 監督 」 功能。
<br/><sup>4</sup> Skype 對話會儲存為信箱的部分。 
<br/><sup>5</sup>進階電子文件需要 Office 365 企業版 E5 或附加元件授權。 <br/><sup>6</sup> Skype 封存是在使用者的信箱內。 
  
## <a name="security-amp-compliance-center-availability-in-office-365-operated-by-21vianet"></a>Security &amp; Compliance Center availability in Office 365 operated by 21Vianet

安全性 & 合規性中心不適用於由 21Vianet 運作的 Office 365 任何計劃中。
  
## <a name="security-amp-compliance-center-availability-in-office-365-germany"></a>Security &amp; Compliance Center availability in Office 365 Germany

使用 Office 365 germany 安全性 & 合規性中心。 如需 Office 365 Germany 的資訊，請參閱 < <b0>Office 365 Germany</b0>。
  

