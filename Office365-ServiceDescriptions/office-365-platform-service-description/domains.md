---
title: 網域
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-domains
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 5c374309-8016-4f18-8f2a-bceeb863ca67
description: 當您新增網域時，逐步嚮導會協助您新增使用者，並將您的電子郵件地址和其他服務轉換為您的公司名稱。 當您完成該嚮導後，您的企業電子郵件會從 Microsoft 開始，而不是移至目前的電子郵件提供者。 若要深入瞭解，請參閱將您的使用者與網域新增至 Microsoft。 如果使用 21Vianet 運作的 Office 365，請參閱驗證您的網域。
ms.openlocfilehash: 730165d82298a43af1cd9903e6bb5726e98f8ec5
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/24/2021
ms.locfileid: "59670318"
---
# <a name="domains"></a>網域

當您新增網域時，逐步嚮導會協助您新增使用者，並將您的電子郵件地址和其他服務轉換為您的公司名稱。 當您完成該嚮導後，您的企業電子郵件會從 Microsoft 開始，而不是移至目前的電子郵件提供者。 若要深入瞭解，請參閱 [將您的使用者與網域新增至 Microsoft](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611)。 如果使用 21Vianet 運作的 Office 365，請參閱[驗證您的網域](/office365/admin/setup/add-domain)。
  
## <a name="custom-domains"></a>自訂網域

您可以將最多900網域新增至您的訂閱 (包括子域) 。 您無法將網域新增至您已在其他 Microsoft 雲端服務中使用的 Microsoft 365。 這表示您無法將相同的網域新增至多個訂閱。 如需詳細資訊，請參閱 [網域常見問題](https://support.office.com/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a)。
  
### <a name="second-and-third-level-domains"></a>第二層和第三層網域

使用 Office 365 企業版和 Microsoft 365 Apps 商務版，您可以新增任何層級的網域，包括 marketing.contoso.com 等第三層級的網域。 請參閱 [將自訂子域或多個網域新增至 Microsoft](/office365/admin/setup/domains-faq)。 如果您使用 21Vianet 運作的 Office 365，請參閱[將自訂的子網域或多個網域新增到 21Vianet 運作的 Office 365](/office365/admin/setup/domains-faq)。
  
## <a name="domain-verification-and-managing-dns-records"></a>網域驗證和管理 DNS 記錄

透過 Microsoft 365，您可以在您的 dns 主機服務提供者管理所有的 dns 記錄，或選擇讓 Microsoft 為您設定和管理您網域的 dns 記錄。 如果您繼續記錄管理，您視需要變更特定記錄，使其指向 Microsoft 服務。 如需提供新增記錄的逐步指示（包括每筆記錄使用的特定值）的網域註冊機構清單，請參閱[create dns](/office365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider) record; 如果您使用的是由世紀運作的 Office 365，請參閱在任何提供者處建立 dns 記錄（如果您使用的是由世紀運作的 Office 365）。 
  
如果 Microsoft 為您管理網域的 DNS 記錄，您必須先切換網域的名稱伺服器記錄，以指向 Microsoft，然後 Microsoft 會設定您的服務，然後在 Microsoft 管理您網域的 DNS 記錄。
  
如果您的網域是在 GoDaddy 註冊，Microsoft 可以在 GoDaddy 為您建立所需的記錄。 
  
不論您的 DNS 記錄的主控位置為何，您都可以設定 DNS 記錄，以將您的網域用於 Microsoft 或其他主機服務提供者所主控之公用網站的 URL。 
  
Microsoft 主動檢查您的 DNS 記錄，以尋找及協助修正 DNS 問題。 如果您的 DNS 記錄不符合我們預期的記錄，您會收到 Microsoft 365 系統管理中心中的通知，以及告訴您如何修正已識別的可能問題的資訊。
  
如需詳細資訊，請參閱[Microsoft 如何管理 dns 記錄](/office365/admin/setup/domains-faq)，或在由世紀運作的 Office 365 中，查看[當您管理 dns 記錄時 Office 365 建立 dns 記錄](/office365/admin/services-in-china/create-dns-records-when-you-manage-your-dns-records)。
  
## <a name="sharing-a-domain"></a>共用網域

您可以在 Microsoft 上試驗某個網域的某些電子郵件地址，以及您先前的電子郵件提供者。 建議僅在試驗期間使用此選項，因為它需要額外的設定步驟，且對 Microsoft 服務有一些限制。 如需詳細資訊，請參閱：
  
- [適用于小型企業的試驗 Microsoft 365](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [使用 FastTrack) 大型商務 (試驗 Microsoft 365](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>功能可用性

若要針對商務方案、獨立選項和內部部署解決方案，查看不同 Microsoft 365 的功能可用性，請參閱[Microsoft 365 及 Office 365 platform service description](office-365-platform-service-description.md)。
