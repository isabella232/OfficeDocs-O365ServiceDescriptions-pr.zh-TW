---
title: Office 365 GCC 高和 DoD
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: 0821204d-5515-43de-8ed6-ab84bd1693c1
description: 深入瞭解 Office 365 GCC 高和 DoD 環境的獨特承諾和差異，與 Office 365 的商業環境相較。
ms.openlocfilehash: e23093e2fdebad45175746aa57bedc0c87728d4b
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/24/2021
ms.locfileid: "59670328"
---
# <a name="office-365-gcc-high-and-dod"></a>Office 365 GCC 高和 DoD

為了符合美國國防部的獨特和不斷演變的需求，以及承包商保留或處理 DoD 控制的未分類資訊， (CUI) 或受制于 (ITAR 的國際流量) ，Microsoft 提供 GCC 高和 DoD 的環境。 可透過大量授權提供，有需要的組織請在建立環境之前通過驗證程序，以確保資格。 這次恕不提供試用版。 
  
請與您的帳戶小組或首選合作夥伴接洽，以深入瞭解或啟動驗證程式。 如需如何購買的詳細資訊，請參閱[Microsoft 365 政府–如何購買](./microsoft-365-government-how-to-buy.md)。
  
## <a name="how-to-use-this-service-description"></a>如何使用此服務說明

Office 365 美國政府服務說明是設計為覆蓋一般 Office 365 服務描述。 它會定義與企業產品的 Office 365 相對的獨特承諾和差異。
  
## <a name="compliance"></a>合規性

GCC高和 DoD 符合下列認證和資格鑒定的規範需求： 
  
- 聯邦風險和授權管理計畫的 FedRAMP 高，包含這些安全性控制和控制的增強功能（如《國家標準和技術研究院 (NIST) 特殊出版物800-53 所述）。
    
- 針對影響級別最高達等級 5 (L5) 的美國國防部雲端運算安全需求準則 (SRG) 安全性控制和控制增強功能。
    
Office 365 的國防訂閱者會從符合 dod SRG L5 的 DOD 獨佔式環境接收服務。 非國防部的訂閱者會從在 L5 評估的美國政府國防環境接收服務，但使用 L4 分割。
  
## <a name="background-screening"></a>背景遮罩

Office 365 人員無法存取 GCC 高和 DoD 的實際執行。 任何要求會授與客戶內容存取權的暫時許可權提升的人員，都必須先傳遞下列背景檢查。<br><br>
  
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

<sup>1</sup>只適用于具有暫存或存取 Office 365 US GCC-High 或 DOD 雲彩中之客戶內容的人員。
## <a name="feature-nuances-based-on-compliant-cloud-architecture"></a>根據相容的雲端架構的功能細微差別

GCC 高和 DoD 環境中的訂閱包含核心 Exchange Online、SharePoint 及商務用 Skype 功能。 針對基礎結構增加的憑證和資格鑒定，一般商業 Office 365 產品與 GCC 高和 DoD 中的功能各有不同。
  
### <a name="exchange-online"></a>Exchange Online

 Exchange Online 高和 GCC 的訂閱中不支援整合內部部署 IP-PBX 系統與 DoD 整合通訊的 **Exchange Online 整合通訊 On-Premises 支援 IP-PBX** 。 
  
### <a name="file-sharing"></a>檔案共用

使用者可以使用多個選項，在 SharePoint 和 OneDrive 中共用檔案和資料夾。 所有選項均可在 GCC 高及 DoD 環境中使用。 如需管理這些選項的詳細資訊，請參閱 [管理共用設定](/sharepoint/turn-external-sharing-on-or-off)。 GCC-High 中的使用者將只能在 GCC 高的其他組織中共用。 此外，不支援附加至使用者設定檔的非 GCC 高電子郵件地址，也不會允許傳送警示電子郵件。 例如，在內部部署使用者 A 會被指派 Gmail 電子郵件地址，然後同步處理至 Azure GCC 高組織。 使用者 A 導覽至文件庫，並建立任何變更的警示。 警示將不會傳送至 Gmail 位址。

> [!NOTE]
> GCC-High 中的使用者目前無法與非 GCC 高組織的使用者共用。

無法使用 Office 365 政府版的檔案[要求](https://support.office.com/article/f54aa7f8-2589-4421-b351-d415fc3b83af)。

### <a name="skype-for-business-online"></a>商務用 Skype Online

 **PSTN 通話 &amp;PSTN 會議**-由於需要使用公用交換電話網路 (pstn) 進行電話語音服務， &amp; 因此目前無法使用 pstn 通話 pstn 會議服務，GCC 高及 DoD。

### <a name="microsoft-teams"></a>Microsoft Teams

透過直接路由傳送 GCC 高及 DoD 環境的透過直接路由) 電話系統和音訊會議 **(電話系統和音訊會議**。 如需詳細資訊，請參閱以下的服務層級檔：

- [透過直接路由電話系統](/microsoftteams/here-s-what-you-get-with-phone-system)
- [適用於 GCC High 和 DoD 的音訊會議搭配直接路由](/microsoftteams/audio-conferencing-with-direct-routing-for-gcch-and-dod)

### <a name="identity"></a>身分識別

由於使用了多重要素驗證的同盟識別身分模型，因此可支援 PIV 和 CAC 卡的使用。
  
### <a name="yammer"></a>Yammer

GCC 高和 DoD 環境中無法使用 enterprise 的 Yammer。
  
## <a name="customer-support"></a>客戶支援

當您使用 Office 365 GCC 高/DOD 時，Microsoft 會提醒您不要與客戶支援人員共用任何受控制、敏感或機密的資訊，除非您確認支援代理程式的授權才能查看或存取這類資料。

Microsoft 致力於保護您的 [隱私權](https://privacy.microsoft.com/privacystatement)) 。 不過，Office 365 GCC 高/DoD 支援不會包含在服務資格鑒定界限內，也不會提供 FedRAMP、DoD SRG、ITAR、IRS 1075 或 CJIS 資料處理規範保證。