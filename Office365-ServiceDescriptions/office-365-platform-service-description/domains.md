---
title: 網域
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/10/2017
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-domains
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 5c374309-8016-4f18-8f2a-bceeb863ca67
description: 當您新增網域時，逐步精靈會協助您新增使用者並將您的 Office 365 電子郵件地址和其他服務轉換成企業名稱。當您完成精靈時，商業電子郵件會啟動傳入到 Office 365 而非移至目前的電子郵件供應商。若要深入了解，請參閱新增使用者和網域至 Office 365。如果您使用 Office 365 21Vianet 所運作，請參閱確認您的網域。
ms.openlocfilehash: 47c378482b8a8d09e2f2516968af99af9472c641
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035280"
---
# <a name="domains"></a>網域

當您新增網域時，逐步精靈會協助您新增使用者並將您的 Office 365 電子郵件地址和其他服務轉換成企業名稱。當您完成精靈時，商業電子郵件會啟動傳入到 Office 365 而非移至目前的電子郵件供應商。若要深入了解，請參閱[新增使用者和 Office 365 的網域](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611)。如果您使用 Office 365 21Vianet 所運作，請參閱[確認您的網域](http://go.microsoft.com/fwlink/?LinkID=733344&amp;clcid=0x409)。
  
## <a name="custom-domains"></a>自訂網域
<a name="BKMK_CustomDomains"> </a>

您可以將最多可達 900 個網域新增至您的 Office 365 訂閱。不過，您無法將網域新增至您已使用另一個 Microsoft 雲端服務中的 Office 365。這表示您不能將相同的網域新增至多個 Office 365 訂閱。如需詳細資訊，請參閱[網域常見問題集](https://support.office.com/en-us/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a)。
  
### <a name="second-and-third-level-domains"></a>第二層和第三層網域
<a name="BKMK_SecondAndThirdLevelDomains"> </a>

在 Office 365 Enterprise 和 Office 365 商務版，您可以新增任何層級的網域，包括第三層網域，例如 marketing.contoso.com。請參閱[將自訂的子網域或多個網域新增到 Office 365](http://go.microsoft.com/fwlink/?LinkID=733345&amp;clcid=0x409)。如果您使用 21Vianet 運作的 Office 365，請參閱[將自訂的子網域或多個網域新增到 21Vianet 運作的 Office 365](http://go.microsoft.com/fwlink/?LinkID=733346&amp;clcid=0x409)。
  
## <a name="domain-verification-and-managing-dns-records"></a>網域驗證和管理 DNS 記錄
<a name="BKMK_ManagingDNSRecords"> </a>

使用 Office 365，您可以在 DNS 主機服務提供者管理所有的 DNS 記錄，或選擇讓 Office 365 為您設定及管理網域的 DNS 記錄。如果您繼續管理記錄，請視需要將特定記錄變更為指向 Office 365 服務。如需提供新增記錄 (包括用於每筆記錄的特定值) 逐步指示的網域註冊機構清單，請參閱[建立 Office 365 的 DNS 記錄](https://go.microsoft.com/fwlink/p/?LinkID=270173)，或如果使用 21Vianet 運作的 Office 365，請在 21Vianet 運作的 Office 365 的任何提供者上參閱「建立 DNS 記錄」。 
  
如果 Office 365 為您管理網域的 DNS 記錄，您必須先將網域的名稱伺服器記錄切換為指向 Office 365，然後 Office 365 會設定您的 Office 365 服務，而後網域的 DNS 記錄就會在 Office 365 上進行管理。
  
如果在 GoDaddy 註冊您的網域，Office 365 即可為您在 GoDaddy 上建立所需的記錄。 
  
不論 DNS 記錄裝載在哪裡，您都可以設定 DNS 記錄，以使用您的網站做為裝載於 Office 365 上或位於其他主機服務提供者那邊之公用網站的 URL。 
  
Office 365 主動檢查您的 DNS 記錄以尋找和協助修正 DNS 問題。如果您的 DNS 記錄不符合我們預期的 DNS 記錄，則您會在 Office 365 系統管理中心中接收到通知，以及告訴您如何修正找到的可能問題的資訊。
  
如需詳細資訊，請參閱 [Office 365 如何管理 DNS 記錄](https://go.microsoft.com/fwlink/p/?LinkID=270144)；或對於 21Vianet 運作的 Office 365，請參閱[管理您的 DNS 記錄時建立 Office 365 的 DNS 記錄](http://go.microsoft.com/fwlink/?LinkID=817326&amp;clcid=0x409)。
  
## <a name="sharing-a-domain"></a>共用網域
<a name="BKMK_ManagingDNSRecords"> </a>

您可以使用在 Office 365 的網域部分電子郵件地址有些舊的電子郵件供應商試驗 Office 365。這是僅建議使用在 Office 365 試驗期間因為它需要其他設定步驟及有 for Office 365 服務限制。如需詳細資訊，請參閱：
  
- [試驗 Office 365 小型企業版](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [試驗 Office 365 大型企業版 (使用 FastTrack)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>功能可用性
<a name="BKMK_ManagingDNSRecords"> </a>

若要檢視跨 Office 365 計劃、獨立選項和內部部署方案的功能可用性，請參閱 [Office 365 平台服務說明](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx)。
  

