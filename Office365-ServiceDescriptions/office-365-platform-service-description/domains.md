---
title: 網域
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-domains
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 5c374309-8016-4f18-8f2a-bceeb863ca67
description: 新增網域時，逐步精靈可協助您新增使用者，並將您的 Office 365 電子郵件地址和其他服務轉換為公司名稱。 完成精靈後，您的商業電子郵件會開始進入 Office 365，而不是移至目前的電子郵件提供者。 若要深入了解，請參閱將您的使用者與網域新增至 Office 365。 如果使用 21Vianet 運作的 Office 365，請參閱驗證您的網域。
ms.openlocfilehash: d4d2e0316960f6c3d91cbdb088bd154d6739c2f2
ms.sourcegitcommit: 4d1cc432b4ce292abeb926f88108937695ce619b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/15/2019
ms.locfileid: "37523398"
---
# <a name="domains"></a>網域

新增網域時，逐步精靈可協助您新增使用者，並將您的 Office 365 電子郵件地址和其他服務轉換為公司名稱。 完成精靈後，您的商業電子郵件會開始進入 Office 365，而不是移至目前的電子郵件提供者。 若要深入了解，請參閱[將您的使用者與網域新增至 Office 365](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611)。 如果使用 21Vianet 運作的 Office 365，請參閱[驗證您的網域](https://docs.microsoft.com/office365/admin/setup/add-domain)。
  
## <a name="custom-domains"></a>自訂網域
<a name="BKMK_CustomDomains"> </a>

您最多可以新增 900 個網域到 Office 365 訂閱。 不過，您不能將已經在其他 Microsoft 雲端服務中使用的網域新增到 Office 365。 這表示您無法將相同的網域新增到多個 Office 365 訂閱。 如需詳細資訊，請參閱[網域的常見問題集](https://support.office.com/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a)。
  
### <a name="second-and-third-level-domains"></a>第二層和第三層網域
<a name="BKMK_SecondAndThirdLevelDomains"> </a>

在 Office 365 Enterprise 和 Office 365 商務版，您可以新增任何層級的網域，包括第三層網域，例如 marketing.contoso.com。請參閱[將自訂的子網域或多個網域新增到 Office 365](https://docs.microsoft.com/office365/admin/setup/domains-faq)。如果您使用 21Vianet 運作的 Office 365，請參閱[將自訂的子網域或多個網域新增到 21Vianet 運作的 Office 365](https://docs.microsoft.com/office365/admin/setup/domains-faq)。
  
## <a name="domain-verification-and-managing-dns-records"></a>網域驗證和管理 DNS 記錄
<a name="BKMK_ManagingDNSRecords"> </a>

使用 Office 365，您可以在 DNS 主機服務提供者管理所有的 DNS 記錄，或選擇讓 Office 365 為您設定及管理網域的 DNS 記錄。如果您繼續管理記錄，請視需要將特定記錄變更為指向 Office 365 服務。如需提供新增記錄 (包括用於每筆記錄的特定值) 逐步指示的網域註冊機構清單，請參閱[建立 Office 365 的 DNS 記錄](https://docs.microsoft.com/office365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider)，或如果使用 21Vianet 運作的 Office 365，請在 21Vianet 運作的 Office 365 的任何提供者上參閱「建立 DNS 記錄」。 
  
如果 Office 365 為您管理網域的 DNS 記錄，您必須先將網域的名稱伺服器記錄切換為指向 Office 365，然後 Office 365 會設定您的 Office 365 服務，而後網域的 DNS 記錄就會在 Office 365 上進行管理。
  
如果在 GoDaddy 註冊您的網域，Office 365 即可為您在 GoDaddy 上建立所需的記錄。 
  
不論 DNS 記錄裝載在哪裡，您都可以設定 DNS 記錄，以使用您的網站做為裝載於 Office 365 上或位於其他主機服務提供者那邊之公用網站的 URL。 
  
Office 365 主動檢查您的 DNS 記錄以尋找和協助修正 DNS 問題。 如果您的 DNS 記錄不符合我們預期它們是，您會收到通知，在 Microsoft 365 系統管理中心，以及告訴您如何修正可能已識別的問題的資訊。
  
如需詳細資訊，請參閱 [Office 365 如何管理 DNS 記錄](https://docs.microsoft.com/office365/admin/setup/domains-faq)；或對於 21Vianet 運作的 Office 365，請參閱[管理您的 DNS 記錄時建立 Office 365 的 DNS 記錄](https://docs.microsoft.com/office365/admin/services-in-china/create-dns-records-when-you-manage-your-dns-records)。
  
## <a name="sharing-a-domain"></a>共用網域
<a name="BKMK_ManagingDNSRecords"> </a>

您可以讓某個網域有些電子郵件地址裝載於 Office 365，有些則裝載於先前的電子郵件提供者，來試驗 Office 365。 這是建議您只使用 Office 365 的試驗期間因為它需要額外的設定步驟，並具有 Office 365 服務會受到一些限制。 如需詳細資訊，請參閱：
  
- [試驗 Office 365 小型企業版](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [試驗 Office 365 大型企業版 (使用 FastTrack)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>功能可用性
<a name="BKMK_ManagingDNSRecords"> </a>

若要檢視跨 Office 365 計劃、 獨立選項和內部部署解決方案的功能可用性，請參閱[Office 365 平台服務說明](office-365-platform-service-description.md)。
  

