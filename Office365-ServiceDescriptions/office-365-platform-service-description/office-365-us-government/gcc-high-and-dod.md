---
title: Office 365 GCC 高和 DoD
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0821204d-5515-43de-8ed6-ab84bd1693c1
description: 深入瞭解 Office 365 GCC 高和 DoD 環境與 Office 365 商業環境的獨特承諾和差異。
ms.openlocfilehash: c4dfdabde7090a7a0b89975eb329eb92016e22f2
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173958"
---
# <a name="office-365-gcc-high-and-dod"></a>Office 365 GCC 高和 DoD

為了符合美國國防部的獨特和不斷演變的需求，以及承包商保留或處理 DoD 控制的未分類資訊 (CUI) 或受制于 (ITAR 的國際流量，Microsoft 提供了 GCC 的高和) 的環境。 可透過大量授權提供，有需要的組織請在建立環境之前通過驗證程序，以確保資格。 這次恕不提供試用版。 
  
請與您的帳戶小組或首選合作夥伴接洽，以深入瞭解或啟動驗證程式。 如需如何購買的詳細資訊，請參閱 [Microsoft 365 政府–如何購買](./microsoft-365-government-how-to-buy.md)。
  
## <a name="how-to-use-this-service-description"></a>如何使用此服務說明

「Office 365 美國政府服務說明」是設計為一般 Office 365 服務說明的疊加。 它會定義獨特的承諾和差異與 Office 365 for enterprise 產品的差異。
  
## <a name="compliance"></a>合規性

GCC 高和 DoD 符合下列認證和資格鑒定的規範需求： 
  
- 聯邦風險和授權管理計畫的 FedRAMP 高，包含這些安全性控制和控制的增強功能（如《國家標準和技術研究院 (NIST) 特殊出版物800-53 所述）。
    
- 針對影響級別最高達等級 5 (L5) 的美國國防部雲端運算安全需求準則 (SRG) 安全性控制和控制增強功能。
    
Office 365 的國防版訂閱者會從符合 DOD SRG L5 的 DOD 獨佔式環境接收服務。 非國防部的訂閱者會從在 L5 評估的美國政府國防環境接收服務，但使用 L4 分割。
  
## <a name="background-screening"></a>背景遮罩

Office 365 人員並未存取 GCC 高和 DoD 的實際執行。 任何要求會授與客戶內容存取權的暫時許可權提升的人員，都必須先傳遞下列背景檢查。<br><br>
  
| Microsoft 人員篩選和背景檢查<sup>1</sup> | 描述 |
|:-----|:-----|
|美國公民權  <br/> |美國公民權驗證  <br/> |
|工作經驗檢查  <br/> |七 (7) 年工作經驗的驗證  <br/> |
|教育驗證  <br/> |取得之最高學位驗證  <br/> |
|美國社會安全編號 (SSN) 搜尋  <br/> |所提供之 SSN 為有效的驗證  <br/> |
|刑事案件記錄檢查  <br/> |州、郡及地方層級和聯邦層級之重刑和民事案件的七 (7) 年刑事案件記錄  <br/> |
|海外資產控制辦公室 (OFAC)  <br/> |美國人民不允許參與貿易或財務交易之財政部團體清單驗證  <br/> |
|工業和安全局清單 (BIS)  <br/> |商務部禁止從事出口活動之個人與實體清單驗證  <br/> |
|防衛辦公室貿易控制排除人員清單 (DDTC)  <br/> |國務院禁止從事國防工業相關之出口活動的個人與實體清單驗證  <br/> |
|指紋檢查  <br/> |FBI 資料庫指紋背景檢查  <br/> |
|美國國防部 IT-2  <br/> |員工若想要求權限提高以存取客戶資料，或 DOD SRG L5 服務能力具權限的系統管理存取權，必須先根據美國人事管理局第 3 層調查 (OPM Tier 3 investigation) 通過美國國防部 IT-2 裁定  <br/> |

<sup>1</sup> 只適用于具有暫存或存取 OFFICE 365 US GCC-High 或 DOD 雲彩中之客戶內容的人員。
## <a name="feature-nuances-based-on-compliant-cloud-architecture"></a>根據相容的雲端架構的功能細微差別

在 GCC 高和 DoD 環境中的訂閱包含核心 Exchange Online、SharePoint 和商務用 Skype 功能。 針對基礎結構增加的憑證和資格鑒定，一般商業版 Office 365 產品與 GCC High 和 DoD 中提供的功能有所不同。
  
### <a name="exchange-online"></a>Exchange Online

 **Exchange online 整合通訊支援 On-Premises IP-PBX** 支援整合內部部署 IP-PBX 系統與 Exchange Online 整合通訊，但在 GCC 高階及 DoD 訂閱中並不支援。 
  
### <a name="file-sharing"></a>檔案共用

使用者可以使用多個選項，在 SharePoint 和 OneDrive 中共用檔案和資料夾。 所有選項均可在 GCC 高和 DoD 環境中使用。 如需管理這些選項的詳細資訊，請參閱 [管理共用設定](/sharepoint/turn-external-sharing-on-or-off)。 GCC-High 中的使用者只可以與 GCC 中的其他組織共用。 此外，不支援附加至使用者設定檔的非 GCC 高電子郵件地址，也不會允許傳送警示電子郵件。 例如，在內部部署使用者 A 會被指派 Gmail 電子郵件地址，然後同步處理至 Azure GCC 高組織。 使用者 A 導覽至文件庫，並建立任何變更的警示。 警示將不會傳送至 Gmail 位址。

> [!NOTE]
> GCC-High 中的使用者目前無法與非 GCC 的高組織中的使用者共用。

無法使用 Office 365 政府的檔案[要求](https://support.office.com/article/f54aa7f8-2589-4421-b351-d415fc3b83af)。

### <a name="skype-for-business-online"></a>商務用 Skype Online

 **PSTN 通話 &amp; PSTN 會議** -由於需要使用公用交換電話網路 (pstn) 進行電話語音服務， &amp; 因此在 GCC 高階及 DoD 中目前無法使用 pstn 通話 pstn 會議服務。

### <a name="microsoft-teams"></a>Microsoft Teams

**電話系統和音訊會議 (透過直接** 路由傳送) 電話系統和音訊 DoD 會議，可透過直接路由傳送。 如需詳細資訊，請參閱以下的服務層級檔：

- [經由直接路由傳送的電話系統](/microsoftteams/here-s-what-you-get-with-phone-system)
- [適用於 GCC High 和 DoD 的音訊會議搭配直接路由](/microsoftteams/audio-conferencing-with-direct-routing-for-gcch-and-dod)

### <a name="identity"></a>身分識別

由於使用了多重要素驗證的同盟識別身分模型，因此可支援 PIV 和 CAC 卡的使用。
  
### <a name="yammer"></a>Yammer

在 GCC 高端和 DoD 環境中，無法使用「企業版的 Yammer」。
  
## <a name="customer-support"></a>客戶支援

當您在使用 Office 365 GCC 高/DOD 時，Microsoft 會提醒您不要以客戶支援人員身分共用任何受管理的敏感資訊或機密資訊，除非您確認支援代理程式的授權才能查看或存取這類資料。

Microsoft 致力於保護您的 [隱私權](https://privacy.microsoft.com/privacystatement)) 。 不過，Office 365 GCC 高階/DoD 支援並未包含在服務資格鑒定界限內，而且不提供 FedRAMP、DOD SRG、ITAR、IRS 1075 或 CJIS 資料處理規範保證。