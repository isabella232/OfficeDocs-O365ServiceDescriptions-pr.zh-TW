---
title: 郵件原則及符合性[ServiceDesc]
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: Microsoft Exchange Online Protection (EOP) 提供郵件原則及符合性功能，可協助您管理電子郵件資料。
ms.openlocfilehash: 7ac2ad58bd4eeebc7ee0af3f5befcaab8959beec
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/07/2019
ms.locfileid: "30466970"
---
# <a name="messaging-policy-and-complianceservicedesc"></a>郵件原則及符合性[ServiceDesc]

Microsoft Exchange Online Protection (EOP) 提供郵件原則及符合性功能，可協助您管理電子郵件資料。
  
尋找所有 EOP 功能的相關資訊嗎？ 請參閱 [Exchange Online Protection 服務說明](exchange-online-protection-service-description.md)。
  
## <a name="transport-rules"></a>傳輸規則
<a name="BKMK_transportrules"> </a>

傳輸規則可讓您彈性地將自己公司特有的原則套用至電子郵件。傳輸規則由彈性準則構成，可讓您定義條件和例外狀況，以及根據準則採取的動作。如需有關傳輸規則的詳細資訊，請參閱[傳輸規則](https://go.microsoft.com/fwlink/p/?LinkId=320399)。
  
## <a name="audit-logging"></a>稽核記錄
<a name="BKMK_auditlogging"> </a>

稽核記錄可讓您追蹤系統管理員對您組織所做的特定變更。這些報告可協助您符合法規、規範和訴訟需求。如需詳細資訊，請參閱 [EOP 中的稽核報告](https://go.microsoft.com/fwlink/p/?LinkId=314258)。
  
## <a name="data-loss-prevention-dlp"></a>資料外洩防護 (DLP)
<a name="BKMK_datalossprevention"> </a>

獨立式 EOP 客戶無法使用此功能。透過深度內容分析，資料外洩防護 (DLP) 可協助您識別、監視和保護組織中的機密資訊。DLP 對於企業郵件系統越來越重要，因為業務關鍵電子郵件包含需要受到保護的機密資料。DLP 功能可讓您保護機密資料，同時又不影響工作者的生產力。
  
您可以在 EAC 中設定 DLP 原則，以便可以：
  
- 開始使用預先設定的原則範本，協助您偵測特定的敏感資訊類型，例如 PCI-DSS 資料、Gramm-Leach-Bliley 金融服務業現代化法案資料，或甚至是特定地區設定的個人識別資訊 (PII)。
    
- 運用現有傳輸規則準則和動作的完整功能，並新增傳輸規則。
    
- 在完整執行 DLP 原則之前先測試其有效性。
    
- 加入您自己的自訂 DLP 原則範本和敏感資訊類型。
    
- 偵測郵件附件、本文或主旨行中的機密資訊，並調整服務採取動作的信賴等級。
    
- 使用「文件指紋」偵測敏感表單資料。「文件指紋」會協助您根據可用於定義傳輸規則和 DLP 原則的文字型表單，輕易地建立自訂敏感資訊類型。
    
- 新增原則提示，藉由對 Outlook 2013、Outlook Web App 及 OWA for Devices 使用者顯示通知來協助減少資料遺失，而且也能夠藉由允許誤判回報來改善原則的有效性。
    
- 檢閱 DLP 報告中的事件資料，或使用產生事件報告動作來新增您自己的特定報告。
    
> [!NOTE]
> DLP 原則只會套用至進出組織的郵件。組織內部 (內部) 郵件不會套用 DLP 原則，除非您在內部部署 DLP 的情況下執行 Exchange Server 2013。這項條件也適用於 DLP 原則提示，這些提示會在機密資料誤送至未授權收件者之前，通知使用者可能會發生的原則違規情形。 
  
若要深入了解 DLP，請參閱[資料外洩防護](https://go.microsoft.com/fwlink/p/?LinkId=320398)。
  
## <a name="office-365-message-encryption"></a>Office 365 郵件加密
<a name="BKMK_OME_in_EOP"> </a>

Office 365 郵件加密的 Azure 資訊保護，組件是一種線上服務，可讓電子郵件使用者將加密的電子郵件傳送給任何人。 內部部署客戶可以購買 Azure 資訊保護，並且使用 Exchange Online Protection 設定郵件流程通過 Exchange Online 存取 Office 365 郵件加密。 若要進一步了解 Exchange Online 中的 Office 365 郵件加密，請參閱 Exchange Online 服務說明的＜[Office 365 Message Encryption](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption)＞。 
  
## <a name="messaging-policy-and-compliance-features-across-eop-options"></a>EOP 選項的郵件原則和符合性功能
<a name="BKMK_OME_in_EOP"> </a>

|**功能**|**獨立式 EOP**|**Exchange Online 中的 EOP 功能**|**Exchange Enterprise CAL with Services**|
|:-----|:-----|:-----|:-----|
|傳輸規則  <br/> |Yes<sup>1</sup> <br/> |Yes<sup>1</sup> <br/> |是  <br/> |
|稽核記錄  <br/> |是<sup>2</sup> <br/> |是  <br/> |是  <br/> |
|資料外洩防護 (DLP)  <br/> |否  <br/> |是  <br/> |是<sup>3</sup> <br/> |
|Office 365 郵件加密  <br/> |是<sup>4</sup> <br/> |是  <br/> |是<sup>4</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> EOP 與 Exchange Online 可用的準則和動作各不相同。 如需 EOP 中可用的準則和動作清單，請參閱 [傳輸規則準則](https://go.microsoft.com/fwlink/p/?LinkId=320392) 和 [傳輸規則動作](https://go.microsoft.com/fwlink/p/?LinkId=320393)。 如需 Exchange Online 中可用的準則和動作清單，請參閱[傳輸規則準則](https://go.microsoft.com/fwlink/p/?LinkId=320394) 和 [傳輸規則動作](https://go.microsoft.com/fwlink/p/?LinkId=320395)。 > <sup>2</sup> EOP 稽核報告是 Exchange Online 稽核報告的子集，但不包括信箱的相關資訊。 > <sup>3</sup> DLP 原則祕訣不適用於 Exchange Enterprise CAL with Services 客戶。 > <sup>4</sup>對於購買 Azure 資訊保護附加元件，並使用 Exchange Online Protection 透過 Exchange Online 路由電子郵件的內部部署客戶支援。 為桌面體驗，除了 Azure 資訊保護的附加元件，Office 365 專業增強版需要購買。 
  

