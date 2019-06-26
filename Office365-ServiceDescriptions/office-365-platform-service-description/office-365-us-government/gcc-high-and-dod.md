---
title: Office 365 GCC 高和 DoD
ms.author: danarl
author: danarl
manager: dianap
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0821204d-5515-43de-8ed6-ab84bd1693c1
description: 為了符合美國國防部的獨特和不斷演變的需求, 以及持有或處理 DoD 控制的未分類資訊 (CUI) 或受限於使用 Arm 規章 (ITAR) 的國際流量的承包商, Microsoft 提供了GCC 高和 DoD 的環境。 可透過大量授權提供，有需要的組織請在建立環境之前通過驗證程序，以確保資格。 這次恕不提供試用版。
ms.openlocfilehash: 196e1e37a00be9e23897e0f2caa78d978d9702b4
ms.sourcegitcommit: e77906b172913bb7b3359d649da59c5d2ee1123f
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/26/2019
ms.locfileid: "35233520"
---
# <a name="office-365-gcc-high-and-dod"></a>Office 365 GCC 高和 DoD

為了符合美國國防部的獨特和不斷演變的需求, 以及持有或處理 DoD 控制的未分類資訊 (CUI) 或受限於使用 Arm 規章 (ITAR) 的國際流量的承包商, Microsoft 提供了GCC 高和 DoD 的環境。 可透過大量授權提供，有需要的組織請在建立環境之前通過驗證程序，以確保資格。 這次恕不提供試用版。 
  
請洽詢您的客戶團隊或偏好的夥伴以瞭解詳細資訊，或啟動驗證程序。 如需如何購買的詳細資訊, 請參閱[Microsoft 365 政府版-如何購買](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy)。
  
## <a name="how-to-use-this-service-description-section"></a>如何使用此「服務說明」一節

Office 365 US Government 服務說明的設計目的在於與一般 Office 365 服務說明之間互相對照，定義了與 Office 365 企業版產品之間特色和差異的比較。
  
## <a name="compliance"></a>合規性

GCC 高和 DoD 符合下列認證和資格鑒定的規範需求: 
  
- 聯邦政府風險與授權管理計畫中度基準 (FedRAMP 中等影響級別) 包括美國國家標準技術研究所 (NIST) 特別出版品 800 53 中所述的這些安全性控制和控制增強功能。
    
- 針對影響級別最高達等級 5 (L5) 的美國國防部雲端運算安全需求準則 (SRG) 安全性控制和控制增強功能。
    
Office 365 的國防部訂閱者會從符合 DOD SRG L5 的 DOD 獨佔式環境中, 收到提供的服務。 非防護部門訂閱者會收到在 L5 評估的美國政府國防環境中的服務, 但使用 L4 分割。
  
## <a name="background-screening"></a>背景遮罩

Office 365 人員不具備對 GCC 高和 DoD 生產的存取權。 任何人員若想要求臨時權限提高以獲授客戶內容存取權，必須先經過下列背景檢查︰
  
|||
|:-----|:-----|
|**Microsoft 人員篩選和背景檢查**<sup>1</sup> <br/> |**描述** <br/> |
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

<sup>1</sup>僅適用于擁有 OFFICE 365 US GCC-高或 DOD 雲端中的客戶內容存取權的人員。
## <a name="feature-nuances-based-on-compliant-cloud-architecture"></a>根據相容的雲端架構進行功能細微差別

在 GCC 高和 DoD 的環境中, Office 365 訂閱包含核心 Exchange Online、SharePoint Online 和商務用 Skype 功能。 鑒於基礎結構的更高認證和資格認證, 一般商業 Office 365 產品和 GCC 高和 DoD 中提供的功能各有不同。
  
### <a name="exchange-online"></a>Exchange Online

 **對於內部部署 ip-pbx 的 Exchange Online 整合通訊支援**, 在 GCC 高和 DoD 訂閱中, 不支援整合內部部署 ip-pbx 系統與 Exchange Online 整合通訊的支援。 
  
### <a name="sharepoint-online"></a>SharePoint Online

 **檔共用**-SharePoint Online 和商務用 OneDrive 可讓使用者與小組之間共用及共同作業。 檔擁有者可以透過網頁介面或 Outlook 中的新式附件, 讓其他使用者能夠存取其檔。 共用檔時, 有多個選項可供管理許可權: 
  
1. 僅自己
    
2. 公司內的任何人
    
3. 具有此連結的任何人
    
4. 特定人員
    
在 GCC 高或 DoD 環境中使用 SharePoint Online 和商務用 OneDrive 的客戶可以將檔設為私人 (第一個選項)、與組織中的任何人共用 (第二個選項)、與任何有連結至檔的人共用 (第三個選項), 以及僅與 GCC 高和 DoD 環境中的特定人員共用 (第四個選項);當然, 您也可以根據租使用者層級的存取控制來限制這些選項。
  
GCC 高租使用者只能與其他 GCC 高租使用者共用。 例如：
  
- GCC 高租使用者 A 可以與 GCC 高租使用者 B 共用。
    
- 非 GCC 租使用者 C 可以與 GCC 高租使用者 A 或 B 共用。
    
- GCC 高租使用者 A 或 B 無法與非 GCC 高租使用者 C 共用。
    
此外, 不支援附加至使用者設定檔的非 GCC 高電子郵件地址, 也不會允許傳送提醒電子郵件。 例如, 在內部部署使用者 A 會被指派 Gmail 電子郵件地址, 然後同步處理至 Azure GCC 高租使用者。 使用者 A 會流覽至文件庫, 並建立任何變更的警示。 警示將不會傳送至 Gmail 位址。
  
 **外部應用程式存取**-與外部應用程式 (例如增益集的資料來源) 的連線, 限於位於 GCC 高和 DoD 所支援之系統安全性界限內的來源。 
  
 **Business Connectivity Services** -支援可在雲端服務的安全性界限記憶體取資料來源的連線案例的 BCS 功能。 
  
 **沙箱解決方案**-此功能已被取代, 無法使用。 所有沙箱化的解決方案都應移轉到 [ SharePoint 增益集擴充性模型中 ]( https://msdn.microsoft.com/library/office/fp179930.aspx)。
  
### <a name="skype-for-business-online"></a>商務用 Skype Online

 **PSTN 呼叫&amp; pstn 會議**-由於需要使用電話導向服務的公用交換電話網路 (PSTN), 因此在 GCC 高和 DoD 中目前無法&amp;使用 pstn 呼叫 pstn 會議服務。 
  
### <a name="identity"></a>身分識別

由於使用了多重要素驗證的同盟識別身分模型，因此可支援 PIV 和 CAC 卡的使用。
  
### <a name="yammer"></a>Yammer

Yammer Enterprise 無法在 GCC 高和 DoD 環境中使用。
  

