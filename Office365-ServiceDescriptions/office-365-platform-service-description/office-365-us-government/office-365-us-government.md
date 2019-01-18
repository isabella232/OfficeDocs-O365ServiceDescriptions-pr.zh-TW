---
title: Office 365 US Government
ms.author: danarl
author: danarl
manager: dianap
ms.date: 1/9/2019
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 3f482abc-993f-41bf-8754-0f489a7e4861
description: 以回應美國公開的磁區的唯一與發展需求、 Microsoft 已建立 Office 365 美國政府計劃 (orOffice 365 美國政府)。本節提供 Office 365 美國政府特有的功能的概觀。建議您先閱讀本節補充與 Office 365 服務說明。
ms.openlocfilehash: 05da74a6efad6834f2108c83126aa1522ae62776
ms.sourcegitcommit: 389748748f04e29e096c0971707b5993f56dd6c6
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 01/17/2019
ms.locfileid: "28694677"
---
# <a name="office-365-us-government"></a>Office 365 US Government

以回應美國公開的磁區的唯一與發展需求、 Microsoft 已建立 Office 365 美國政府計劃 （或"Office 365 美國政府"）。本節提供 Office 365 美國政府特有的功能的概觀。建議您先閱讀本節補充與[Office 365 服務說明](../../office-365-service-descriptions-technet-library.md)。
  
## <a name="how-to-use-this-service-description-section"></a>如何使用此「服務說明」一節
<a name="TopOfPage"> </a>

Office 365 US Government 服務說明的設計目的在於與一般 Office 365 服務說明之間互相對照，定義了與 Office 365 企業版產品之間特色和差異的比較。
  
## <a name="about-office-365-us-government-environments"></a>關於 Office 365 美國政府環境
<a name="BM1_About"> </a>

Office 365 US Government 方案為每月訂閱，並且可授權給不限數量的使用者。 
  
- **Office 365 GCC**環境提供遵守美國聯邦雲端服務，包括 FedRAMP 設定一般需求和罪犯正義和聯邦稅資訊系統 （CJI 和 FTI 資料類型） 的需求。 
    
- **Office 365 GCC 高和 DoD**環境傳遞規範部門的防禦安全性需求指導方針、 防禦聯邦擷取規定 supplement （英文) (DFARS)，與國際流量中召集令規定 (ITAR)。 
    
除了具有 Office 365 的功能外，使用 Office 365 US Government 的組織還可從以下專屬於 Office 365 US Government 的功能獲得好處：
  
- 組織的客戶內容和 Microsoft 的商業 Office 365 服務中的客戶內容會以邏輯方式區隔。
    
- 組織的客戶內容儲存於美國境內。
    
- 只有經過篩選的 Microsoft 人員可以存取組織的客戶內容。
    
- Office 365 US Government 符合美國公共部門客戶所要求的認證和資格鑑定。
    
[如何使用此「服務說明」一節](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="customer-eligibility"></a>客戶資格
<a name="BM2-customer"> </a>

Office 365 美國政府供 （1） 美國聯邦、 state、 本機、 部落，且就政府實體和處理受限於政府法規與需求的資料，並讓使用的 Office 365 美國政府 （2） 其他實體是適用於符合這些需求，受限於驗證的資格。Microsoft 的資格驗證將會包含確認處理受限於國際流量中召集令規定 (ITAR)、 受限於 fbi 機關罪犯正義資訊服務 (CJIS) 原則或其他法律強制執行資料的資料政府規範或控制資料。驗證可能需要美國部門的狀態與註冊證明 ITAR 資料或贊助所處理之資料的特定需求政府實體。Office 365 DoD 環境是防禦的美國部門獨佔使用。
  
不同 Office 365 美國政府版方案資格準則是一致的而 Microsoft 只將同意 DFARS ITAR 合約語言 GCC 高的環境。
  
若有關於 Office 365 US Government 資格問題的機構應諮詢其客戶團隊。
  
在更新客戶的 Office 365 US Government 合約時，必須重新驗證資格。
  
[如何使用此「服務說明」一節](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="customer-content-located-within-the-united-states"></a>美國境內的客戶內容
<a name="BM3-withinUSA"> </a>

Office 365 US Government 服務是由美國境內的實體資料中心所提供。下列客戶內容會靜止存放在僅位於美國境內的實體資料中心裡： 
  
- Exchange Online 信箱內容 (電子郵件內文、行事曆項目和電子郵件附件的內容)。
    
- SharePoint Online 站台內容和儲存在該站台內的檔案。
    
- 商務用 Skype 保存的對話、上傳的文件和白板工作階段。
    
> [!NOTE]
> 一般來說，商務用 Skype 不會儲存客戶內容，但是如果有儲存的話，將會儲存在美國境內的資料中心。 
  
如果使用者在美國境內使用 Office Online (以前稱為 Office Web Apps)，或是您採用 Active Directory Federation Services (AD FS) 2.0，並且設定原則來確保使用者透過單一登入來與服務連線，那麼任何在 Office Online 中暫時快取的客戶內容將會存在於美國境內。
  
[如何使用此「服務說明」一節](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="office-365-us-government-and-third-party-services"></a>Office 365 US Government 與協力廠商服務
<a name="BM4-3rdParty"> </a>

Office 365 可將協力廠商的應用程式整合至 SharePoint Online 站台、商務用 Skype、Office 365 ProPlus 中的 Office 應用程式 (如 Word、Excel、PowerPoint 和 Outlook) 以及 Outlook Web App。此外，Office 365 還支援與服務提供者協力廠商整合。這些協力廠商應用程式和服務可能會在 Office 365 基礎結構外的協力廠商系統上儲存、傳輸和處理組織的客戶資料，因此不在 Office 365 規範和資料保護承諾的保證範圍內。建議您檢閱協力廠商提供的隱私權和規範聲明，來評估適合組織的服務使用方式。
  
[如何使用此「服務說明」一節](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="restricted-data-access-by-administrators"></a>受限制的系統管理員資料存取
<a name="BM5-Restricted"> </a>

只有具有美國公民身分的 Microsoft 系統管理員能夠存取 Office 365 US Government 客戶內容。這些人員會依據相關的政府標準來進行背景調查。
  
||||
|:-----|:-----|:-----|
|**背景檢測** <br/> |**GCC** <br/> |**GCC 高和 Dod** <br/> |
|美國公民權驗證  <br/> |是  <br/> |是  <br/> |
|工作經驗檢查  <br/> |是  <br/> |是  <br/> |
|教育驗證  <br/> |是  <br/> |是  <br/> |
|美國社會安全編號 (SSN) 搜尋  <br/> |是  <br/> |是  <br/> |
|刑事案件記錄檢查 (7 年)  <br/> |是  <br/> |是  <br/> |
|海外資產控制辦公室 (OFAC)  <br/> |是  <br/> |是  <br/> |
|工業和安全局清單 (BIS)  <br/> |是  <br/> |是  <br/> |
|FBI 刑事案件資料庫指紋式檢查  <br/> |是  <br/> |是  <br/> |
|CJIS 刑事案件背景檢查  <br/> |是  <br/> |否  <br/> |
|根據 OPM 層級 3 調查的 DOD IT 2  <br/> |否  <br/> |僅限 DOD SRG L5 Tenant  <br/> |
   
[如何使用此「服務說明」一節](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="fasttrack-center-onboarding-assistance"></a>FastTrack 中心 Onboarding 協助
<a name="BM5-Restricted"> </a>

與 Office 365<sup>1</sup>FastTrack 中心福利，您使用遠端 FastTrack 專家取得 Office 365 環境備妥可供使用與計劃導入和組織內的使用方式。FastTrack 程序提供 onboarding 和使用者採用服務。 
  
上架包含︰
  
- 核心 onboarding-這些是視租用戶組態和整合 Azure Active Directory (Azure AD) 所需的工作。核心 onboarding 也提供基線 onboarding 其他合格的服務。
    
- 服務 onboarding 與移轉-服務 onboarding 工作可讓您的租用戶中的案例。[資料移轉](https://aka.ms/whatcanmigrate)討論資料移轉 （包括電子郵件和檔案）。<sup>2</sup>
    
使用者採用服務由數項工作所組成，提供您指引以確保您的使用者知道適合的服務，並用來促進商業價值。
  
您可以找到 FastTrack 中心處理序上的特定資訊[此處](https://aka.ms/whatistheprocess)。如參與角色和責任的分解，請檢閱[FastTrack 責任](https://aka.ms/whatdoesftcdo)為[您的責任](https://aka.ms/whatdowedo)。
  
<sup>1</sup>您必須購買[合格的計劃](https://aka.ms/whocanbenefit)接收 FastTrack 服務清單中，至少有 50 授權 
  
<sup>2</sup>資料移轉服務可用來與 500 或多個授權 Office 365 租用戶。 
  
## <a name="data-migrations-performed-by-fasttrack"></a>FastTrack 所執行的資料移轉
<a name="BM5-Restricted"> </a>

選擇[FastTrack](https://fasttrack.microsoft.com/)移轉福利的客戶必須授與存取管理其資料移轉小組。這些人員是美國市民和、 經歷的客戶的 Office 365 美國政府服務執行移轉前的下列背景檢查。 
  
||||
|:-----|:-----|:-----|
|**背景檢測** <br/> |**GCC** <br/> |**GCC High 和 DoD** <br/> |
|美國公民權驗證  <br/> |是  <br/> |是  <br/> |
|工作經驗檢查  <br/> |是  <br/> |是  <br/> |
|教育驗證  <br/> |是  <br/> |是  <br/> |
|社會安全號碼 (SSN) 搜尋  <br/> |是  <br/> |是  <br/> |
|刑事案件記錄檢查 (7 年)  <br/> |是  <br/> |是  <br/> |
   
[如何使用此「服務說明」一節](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="office-365-us-government-and-azure-government-expressroute"></a>Office 365 US Government 和 Azure 政府版 Express Route
<a name="BM6-Express"> </a>

Office 365 US Government 客戶可以使用 Azure 政府版 ExpressRoute 服務私下連線到支援的 Office 365 服務，而不透過公用的網際網路連線。
  
如需了解支援提供者、價格模型及相關資訊的詳細資料，請檢閱 [Azure ExpressRoute 資訊](http://go.microsoft.com/fwlink/?LinkID=798220&amp;clcid=0x409)。
  
如需 Office 365 Azure ExpressRoute 支援的詳細資訊，請參閱 [Azure ExpressRoute for Office 365](http://go.microsoft.com/fwlink/?LinkID=798216&amp;clcid=0x409)。
  
[如何使用此「服務說明」一節](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="system-requirements"></a>系統需求
<a name="BM9-Requirements"> </a>

如需適用於 Office 365 US Government 方案的系統需求，請參閱 [office.com](http://go.microsoft.com/fwlink/?LinkID=626095&amp;clcid=0x409) 產品網站上的 [Office 的系統需求](http://go.microsoft.com/fwlink/?LinkID=509817&amp;clcid=0x409)。 
  
[如何使用此「服務說明」一節](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="security-amp-compliance-center"></a>安全性&amp;規範中心
<a name="BM9-Requirements"> </a>

如需安全性的資訊&amp;規範中心和連結的其他資訊和可用性，請參閱[Office 365 安全性&amp;規範中心](../../office-365-platform-service-description/office-365-securitycompliance-center.md)。
  
## <a name="service-availability-for-each-plan"></a>每個方案可用的服務
<a name="BM9-Requirements"> </a>

每個 Office 365 方案皆包含一些個別服務，例如 Exchange Online 和 SharePoint Online。下表顯示每項 Office 365 US Government 方案中可用的服務。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**Office 365 服務** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府 G3** <br/> |**Office 365 美國政府 G5** <br/> |**Office 365 美國政府 f1 鍵** <br/> |
|Office Online  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Office 365 專業增強版  <br/> |否 <br/> |是 <br/> |是 <br/> |否  <br/> |
|Exchange Online  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Exchange Online Protection  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|SharePoint Online  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|商務用 OneDrive  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Skype for Business (立即訊息&amp;平台服務)  <br/> |是<sup>1</sup> <br/> |是  <br/> |是  <br/> |是<sup>1</sup> <br/> |
| 語音-電話系統音訊會議  <br/> |否<sup>2, 3</sup> <br/> |否<sup>2, 3</sup> <br/> |Yes <sup>3、 5 個</sup> <br/> |否  <br/> |
|Power BI Pro  <br/> |沒有<sup>2</sup> <br/> |沒有<sup>2</sup> <br/> |是  <br/> |沒有<sup>2</sup> <br/> |
|Project Online  <br/> |沒有<sup>2</sup> <br/> |沒有<sup>2</sup> <br/> |沒有<sup>2</sup> <br/> |沒有<sup>2</sup> <br/> |
|Yammer Enterprise  <br/> |沒有<sup>4</sup> <br/> |沒有<sup>4</sup> <br/> |沒有<sup>4</sup> <br/> |沒有<sup>4</sup> <br/> |
   
> <sup>1</sup>是可用的所有客戶的商業基本 Skype。商務桌面用戶端 Skype 是在本機上已安裝的應用程式提供顯示狀態、 立即訊息與會議功能內含 Skype 商務 Online 的 Office 365 計劃。Office 365 ProPlus、 G3，以及 G5 包括完整 Skype 應用程式，其中包含其他功能，例如進階電話語音支援、 封存、 和符合性功能。商務 Online 授權 Skype 必須被指派每位使用者。<br/><sup>2</sup>未包含，但是可以購買作為個別的附加元件。Project Online 包含 Project Online 桌面用戶端訂閱的一部分。<br/> <sup>3</sup> GCC 高或 DoD 計劃，但即將推出尚無法使用。 
<br/><sup>4</sup> yammer Enterprise 不是 Office 365 美國政府、 元件，但可能會在沒有成本取得為每位使用者的獨立優惠 for Office 365 中以 GCC 授權。此產品項目是目前僅限於購買 Office 365 GCC 企業協議與企業訂閱協議下的客戶。Yammer 不 GCC 高或 DoD 中提供。<br/><sup>5</sup>呼叫規劃是附加元件。 
  
## <a name="platform-features"></a>平台功能
<a name="BM7-Platform"> </a>

下表列出可用於 Office 365 US Government 方案的平台功能和服務。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府 G3** <br/> |**Office 365 美國政府 G5** <br/> |**Office 365 美國政府 f1 鍵** <br/> |
|**Office 365 管理** <br/> |||||
|使用 Office 365 系統管理中心來管理 Office 365  <br/> |Yes<sup>16</sup> <br/> |Yes<sup>16</sup> <br/> |是  <br/> |Yes<sup>16</sup> <br/> |
|從 Office 365 管理核心服務設定  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|使用 Windows PowerShell 管理 Office 365  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|使用 Azure 資訊保護 來保護內容  <br/> |無<sup>1</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup>  <br/> |無<sup>1</sup> <br/> |
|**[Office 365 套件功能](../../office-365-platform-service-description/office-365-suite-features.md)** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府 G3** <br/> |**Office 365 美國政府 G5** <br/> |**Office 365 美國政府 f1 鍵** <br/> |
|Microsoft Bookings  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |
|Microsoft Flow  <br/> |Yes<sup>11</sup> <br/> |Yes<sup>11</sup> <br/> |Yes<sup>11</sup> <br/> |Yes<sup>11</sup> <br/> |
|Microsoft Forms  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|Microsoft Graph API  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Microsoft MyAnalytics  <br/> |沒有<sup>9，12，15</sup> <br/> |沒有<sup>9，12，15</sup> <br/> |Yes<sup>9、 15</sup> <br/> |沒有<sup>9，12，15</sup> <br/> |
|Microsoft Planner  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|Microsoft PowerApps  <br/> |Yes<sup>11</sup> <br/> |Yes<sup>11</sup> <br/> |Yes<sup>11</sup> <br/> |Yes<sup>11</sup> <br/> |
|Microsoft StaffHub  <br/> |Yes<sup>13</sup> <br/> |Yes<sup>13</sup> <br/> |Yes<sup>13</sup> <br/> |Yes<sup>13</sup> <br/> |
|Microsoft Stream  <br/> |Yes<sup>11</sup> <br/> |Yes<sup>11</sup> <br/> |Yes<sup>11</sup> <br/> |否  <br/> |
|Microsoft Sway  <br/> |Yes<sup>13</sup> <br/> |Yes<sup>13</sup> <br/> |Yes<sup>13</sup> <br/> |Yes<sup>13</sup> <br/> |
|Microsoft Teams  <br/> |Yes<sup>9、 15</sup> <br/> |Yes<sup>9、 15</sup> <br/> |Yes<sup>9、 15</sup> <br/> |Yes<sup>9、 15</sup> <br/> |
|Office Delve  <br/> |Yes<sup>17</sup> <br/> |Yes<sup>17</sup> <br/> |是  <br/> |Yes<sup>17</sup> <br/> |
|Office 365 群組  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Microsoft Stream  <br/> |Yes<sup>9、 15</sup> <br/> |Yes<sup>9、 15</sup> <br/> |Yes<sup>9、 15</sup> <br/> |否  <br/> |
|**[使用者帳戶管理](../../office-365-platform-service-description/user-account-management.md)** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府 G3** <br/> |**Office 365 美國政府 G5** <br/> |**Office 365 美國政府 f1 鍵** <br/> |
|雲端身分識別  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|同盟身分識別 (單一登入)  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|多重要素驗證  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|電話因素驗證  <br/> |Yes<sup>9</sup> <br/> |Yes<sup>9</sup> <br/> |是  <br/> |Yes<sup>9</sup> <br/> |
|Office 365 桌面設定  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|以 Office 365 管理使用者  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|使用.csv 檔案大量上傳  <br/> |Yes<sup>9</sup> <br/> |Yes<sup>9</sup> <br/> |是  <br/> |Yes<sup>9</sup> <br/> |
|目錄同步處理工具  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Exchange 簡易 (完全) 移轉  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|透過使用 Office 365 來刪除帳戶  <br/> |是 <sup>3</sup> <br/> |是 <sup>3</sup> <br/> |是 <sup>3</sup> <br/> |是 <sup>3</sup> <br/> |
|管理員可以從 Office 365 或使用 Windows PowerShell 重設使用者密碼  <br/> |是 <sup>4</sup> <br/> |是 <sup>4</sup> <br/> |是 <sup>4</sup> <br/> |是 <sup>4</sup> <br/> |
|使用者可以變更自己的密碼  <br/> |是 <sup>5</sup> <br/> |是 <sup>5</sup> <br/> |是 <sup>5</sup> <br/> |是 <sup>5</sup> <br/> |
|管理授權  <br/> |是<sup>7, 8</sup> <br/> |是<sup>7, 8</sup> <br/> |是<sup>7, 8</sup> <br/> |是<sup>7,8</sup> <br/> |
|從 Office 365 管理安全性群組  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|多個可用的管理員角色  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|允許合作夥伴代替您管理 Office 365  <br/> |Yes<sup>11</sup> <br/> |Yes<sup>11</sup> <br/> |Yes<sup>11</sup> <br/> |Yes<sup>11</sup> <br/> |
|Azure Active Directory 服務  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[網域](../../office-365-platform-service-description/domains.md)** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府 G3** <br/> |**Office 365 美國政府 G5** <br/> |**Office 365 美國政府 f1 鍵** <br/> |
|新增自訂的第 2 層網域，如 fourthcoffee.com  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|新增自訂的第 3 層網域，如 marketing.fourthcoffee.com  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|最多可新增 900 個自訂網域  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|自訂網域需要網域所有權驗證  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[服務健康狀況和持續性](../../office-365-platform-service-description/service-health-and-continuity.md)** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府 G3** <br/> |**Office 365 美國政府 G5** <br/> |**Office 365 美國政府 f1 鍵** <br/> |
|可在 **[服務健康狀況]** 或 **[服務狀態]** 頁面上獲取狀態資訊  <br/> |Yes<sup>9、 15</sup> <br/> |Yes<sup>9、 15</sup> <br/> |Yes<sup>9、 15</sup> <br/> |Yes<sup>9、 15</sup> <br/> |
|可在 Office 365 系統管理中心儀表板上獲取個別警示狀態  <br/> |Yes<sup>9、 15</sup> <br/> |Yes<sup>9、 15</sup> <br/> |Yes<sup>9、 15</sup> <br/> |Yes<sup>9、 15</sup> <br/> |
|**服務健康狀況** RSS 摘要  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[報告](../../office-365-platform-service-description/reports.md)** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府 G3** <br/> |**Office 365 美國政府 G5** <br/> |**Office 365 美國政府 f1 鍵** <br/> |
|使用中和非使用中的信箱  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|新增和已刪除的信箱  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|新的和已刪除的群組  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|信箱使用量  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|信箱連線類型  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|傳送和接收的郵件  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|排名最前面的寄件者及收件者  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|垃圾郵件偵測  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|惡意程式碼偵測  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|郵件中排名最前面的惡意程式碼  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|郵件符合規則的數目  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|郵件排名最前面的相符規則  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|郵件排名最前面的相符 DLP 原則  <br/> |否  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|依重要性分組顯示郵件符合 DLP 原則的數目  <br/> |否  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|郵件的 DLP 原則比對、覆寫及誤判  <br/> |否  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|郵件排名最前面的相符 DLP 規則  <br/> |否  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|IM 和音訊工作階段  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|應用程式共用、Web 及電話撥入式會議  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|視訊、應用程式共用及檔案傳輸工作階段  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|IM 和音訊/視訊會議  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|可下載的郵件保護報告  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|使用的瀏覽器  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|使用的作業系統  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|使用 Office 365 報表 Web 服務，建立自己的報表  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|**[服務更新](../../office-365-platform-service-description/service-updates.md)** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府 G3** <br/> |**Office 365 美國政府 G5** <br/> |**Office 365 美國政府 f1 鍵** <br/> |
|提供給所有客戶的定期更新  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|需要採取 行動時， 將通知傳送給 「訊息中心」  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|Roadmap.office.com 的一些服務 更新  <br/> |沒有<sup>10、 13</sup> <br/> |沒有<sup>10、 13</sup> <br/> |沒有<sup>10、 13</sup> <br/> |沒有<sup>10、 13</sup> <br/> |
|若要開啟選取的目標版本] 選項  <br/> |是<sup>10</sup> <br/> |是<sup>10</sup> <br/> |是<sup>10</sup> <br/> |是<sup>10</sup> <br/> |
|**[說明和訓練](../../office-365-platform-service-description/help-and-training.md)** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府 G3** <br/> |**Office 365 美國政府 G5** <br/> |**Office 365 美國政府 f1 鍵** <br/> |
|線上說明  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|社群  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|其他自助資源  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|自訂進度訓練  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[網路功能](../../office-365-platform-service-description/networking.md)** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府 G3** <br/> |**Office 365 美國政府 G5** <br/> |**Office 365 美國政府 f1 鍵** <br/> |
|IPv4 和 IPv6 通訊協定  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**信任** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府 G3** <br/> |**Office 365 美國政府 G5** <br/> |**Office 365 美國政府 f1 鍵** <br/> |
|**[隱私權、安全性和透明化](../../office-365-platform-service-description/privacy-security-and-transparency.md)** <br/> |||||
|進階資料管理  <br/> |沒有<sup>12</sup> <br/> |沒有<sup>12</sup> <br/> |是 <br/> |沒有<sup>12</sup> <br/> |
|雲端 App 安全性  <br/> |沒有<sup>11、 12</sup> <br/> |沒有<sup>11、 12</sup> <br/> |Yes<sup>11</sup> <br/> |沒有<sup>11、 12</sup> <br/> |
|進階威脅防護  <br/> |沒有<sup>12</sup> <br/> |沒有<sup>12</sup> <br/> |是  <br/> |沒有<sup>12</sup> <br/> |
|客戶加密箱  <br/> |沒有<sup>9，12，15</sup> <br/> |沒有<sup>9，12，15</sup> <br/> |Yes<sup>9、 15</sup> <br/> |沒有<sup>9，12，15</sup> <br/> |
|Office 365 進階 eDiscovery  <br/> |沒有<sup>12</sup> <br/> |沒有<sup>12</sup> <br/> |是  <br/> |沒有<sup>12</sup> <br/> |
|安全分數<sup>14</sup> <br/> |Yes<sup>9、 15</sup> <br/> |Yes<sup>9</sup> <br/> |Yes<sup>9、 15</sup> <br/> |Yes<sup>9、 15</sup> <br/> |
|Office 郵件加密  <br/> |否  <br/> |是 <br/> |是 <br/> |否  <br/> |
|威脅情報  <br/> |沒有<sup>12</sup> <br/> |沒有<sup>12</sup> <br/> |是 <br/> |沒有<sup>12</sup> <br/> |
|**[合規性[ServiceDesc]](../../office-365-platform-service-description/compliance-servicedesc.md)** <br/> |||||
|SAS 70 / SSAE16 評估  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|ISO 27001 認證  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|歐盟示範條款  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|歐盟安全港  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|HIPAA 業務關聯協議  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|FISMA 操作授權  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Microsoft 資料處理協議  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|PCI DSS 最高等級  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|PCI 規範 PAN 資料  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |
|**[服務連續性](../../office-365-platform-service-description/service-health-and-continuity.md)** <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[BlackBerry](../../office-365-platform-service-description/blackberry.md)** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府 G3** <br/> |**Office 365 美國政府 G5** <br/> |**Office 365 美國政府 f1 鍵** <br/> |
|使用 BlackBerry Internet Service (BIS)  <br/> |沒有<sup>2</sup> <br/> |沒有<sup>2</sup> <br/> |沒有<sup>2</sup> <br/> |沒有<sup>2</sup> <br/> |
|**[協力程式](../../office-365-platform-service-description/partners.md)** <br/> |||||
|針對正在使用指定計劃的客戶建立試用邀請和購買訂單  <br/> |沒有<sup>11</sup> <br/> |沒有<sup>11</sup> <br/> |沒有<sup>11</sup> <br/> |沒有<sup>11</sup> <br/> |
|提供委派管理  <br/> |沒有<sup>11</sup> <br/> |沒有<sup>11</sup> <br/> |沒有<sup>11</sup> <br/> |沒有<sup>11</sup> <br/> |
|**[服務等級協定](../../office-365-platform-service-description/service-level-agreement.md)** <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[產品使用權限](../../office-365-platform-service-description/product-use-rights.md)** <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
   
> <sup>1</sup> azure 資訊保護未包含在內，但是可以購買作為個別的附加元件與將會啟用支援的資訊版權管理 (IRM) 功能。一些 Azure 資訊保護功能需要訂閱即可 Office 365 ProPlus，此做法便不包含在 Office 365 美國政府版 G1 或 Office 365 美國政府 f1 鍵。><br/><sup>2</sup>現有 BBCS 和 BIS 客戶可以繼續使用服務。不接受新的客戶。<br/><sup>3</sup> 如果您是使用目錄同步處理，則必須使用 Active Directory (非使用 Office 365 入口網站) 或使用 Windows PowerShell 的 Azure Active Directory 模組來刪除帳戶或變更密碼。 
<br/><sup>4</sup> 如果使用密碼同步化，使用者必須在本機 Active Directory 中變更其密碼。 
<br/><sup>5</sup> 若要了解如何為使用者設定自助式密碼管理原則，請參閱 [在 Azure AD 中管理密碼](https://azure.microsoft.com/en-us/documentation/articles/active-directory-manage-passwords/)。 <br/><sup>6</sup>您可以使用 Office 365 只有一個公用網站除非您已從舊版的 Office 365 升級。在此情況下，您有兩個公用網站，但是只有其中可以裝載以自訂的網域名稱。如需使用適用於 Business 訂閱的兩個網站的詳細資訊，請參閱[如何使用兩種 Office 365 公用網站](https://go.microsoft.com/fwlink/p/?LinkID=271589)。如果您有不同的訂閱，深入了解在[深入瞭解協力廠商網站架設和 Office 365 中的公用網站](https://go.microsoft.com/fwlink/p/?LinkID=325009)的公用網站。<br/><sup>7</sup>減少字詞折扣所購買的基座可能會受限於早期的終止費用。這不適用於付費每月為基礎的訂閱。<br/><sup>8</sup>於下列計劃不支援從 Office 365 系統管理中心的授權基座變更： > Office 365 美國政府版 G1 > Office 365 美國政府 G3 > Office 365 美國政府 K1 <br/><sup>9</sup>尚無法使用 GCC 高，但即將推出。
<br/><sup>10</sup>的 Office 365 美國政府版 G1、 G3、 和 F1 Targeted 版本與商務流程的 Office 365 適用於;但是可能會有一些複寫差異處或[規範需求](https://products.office.com/en-us/business/office-365-trust-center-cloud-computing-security?legRedir=true&amp;CorrelationId=eeaccba9-85ea-4fa8-9c84-3fb4c9e1547b&amp;tab=7a3a6365-14c0-81ac-34ff-f4a416599263)因特定的服務更新的延遲。
<br/><sup>第 11</sup>尚無法使用在 Office 365 美國政府版方案，但即將推出。 ><br/><sup>12</sup>不包含，但是可以購買作為個別的附加元件 GCC 中。 
<br/><sup>13</sup>不支援的 Office 365 美國政府版方案。 
<br/><sup>14</sup>位於[https://securescore.office.com](https://securescore.office.com)。需要系統管理員權限。如需詳細資訊，請參閱[簡介 Office 365 安全分數](https://go.microsoft.com/fwlink/?linkid=836894)。<br/><sup>15</sup> DoD 環境中，但即將推出尚無法使用。 
<br><sup>16</sup>系統管理中心不包括流量分析，DoD 或 GCC 高的環境中
<br><sup>第 17</sup>不支援 GCC 高或 DoD 環境
  
[如何使用此「服務說明」一節](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="office-application-features"></a>Office 應用程式功能
<a name="BM11-Applications"> </a>

下表顯示可用於 Office 365 US Government 方案的 Office 應用程式功能。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府 G3** <br/> |**Office 365 美國政府 G5** <br/> |**Office 365 美國政府 f1 鍵** <br/> |
|**Office 應用程式** <br/> |||||
|[Microsoft Word](../../office-applications-service-description/office-applications.md#microsoft-word) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Microsoft Excel](../../office-applications-service-description/office-applications.md#microsoft-excel) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Microsoft PowerPoint](../../office-applications-service-description/office-applications.md#microsoft-powerpoint) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Microsoft OneNote](../../office-applications-service-description/office-applications.md#microsoft-onenote) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Microsoft Outlook](../../office-applications-service-description/office-applications.md#microsoft-outlook) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Microsoft Publisher](../../office-applications-service-description/office-applications.md#microsoft-publisher) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Microsoft Access](../../office-applications-service-description/office-applications.md#microsoft-access) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[商務用 Skype](../../office-applications-service-description/office-applications.md#skype-for-business) <br/> |Yes<sup>3</sup> <br/> |是  <br/> |是  <br/> |Yes<sup>3</sup> <br/> |
|[Office 365 的 Mac 版 Office](https://support.office.com/en-us/article/General-requirements-for-Outlook-2016-for-Mac-A07A593D-B383-4906-A6C1-962D5543ED57?ui=en-US&amp;rs=en-US&amp;ad=US) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Office Mobile for iPad/iPhone](../../office-applications-service-description/office-applications.md#office-mobile-for-ipadiphone) <br/> |否  <br/> |是<sup></sup> <br/> |是<sup></sup> <br/> |否  <br/> |
|[Office Mobile for Android](../../office-applications-service-description/office-applications.md#office-mobile-for-android) <br/> |否  <br/> |是<sup></sup> <br/> |是<sup></sup> <br/> |否  <br/> |
|[適用於 Windows Phone 手機的 Office Mobile](../../office-applications-service-description/office-applications.md#office-mobile-for-windows-phone) <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|Office Mobile for Windows 10 平板電腦 <br/> |否  <br/> |是<sup></sup> <br/> |是<sup></sup> <br/> |否  <br/> |
|Outlook iOS 及 Android<sup>5、 4</sup>  <br/> |是 <br/> |是 <br/> |是 <br/> |是 <br/> |
|**企業價值** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府 G3** <br/> |**Office 365 美國政府 G5** <br/> |**Office 365 美國政府 f1 鍵** <br/> |
|每個使用者可同時在 5 部 PC 或 Mac 上安裝  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|自動化使用者帳戶的佈建  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|多種語系使用者介面  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|用戶端推送部署  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|內部部署 Exchange 的用戶端支援  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|內部部署 SharePoint 的用戶端支援  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|軟體更新的控制  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|資料庫比較  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|桌上型電腦虛擬化  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|Excel 試算表比較  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|Excel 試算表查詢  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|Exchange Online 和 SharePoint Online 封存與規範  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|群組原則支援  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|使用 Azure 資訊保護的資訊版權管理  <br/> |無<sup>1</sup> <br/> |Yes<sup>6</sup> <br/> |Yes<sup>6</sup> <br/> |無<sup>1</sup> <br/> |
|使用 Windows Server AD RMS 的 Information Rights Management  <br/> |是<sup>2</sup> <br/> |是<sup>2</sup> <br/> |是<sup>2</sup> <br/> |是<sup>2</sup> <br/> |
|Office 增益集、ActiveX 與 BHO 支援  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|SharePoint Server、SharePoint Online、商務用 OneDrive 和 Office 365 上筆記本的 OneNote 用戶端存取  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|Office Lens  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |
|Office 遙測  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|用戶端應用程式的離線支援  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|最佳化的並存用戶端安裝  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|Excel 的 Power Map  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|Power Pivot for Excel  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|Excel 的 Power Query  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|Power View for Excel  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|漫遊設定  <br/> |否  <br/> |是<sup></sup> <br/> |是<sup></sup> <br/> |否  <br/> |
|共用電腦啟用  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|支援對雲端架構檔案儲存進行封鎖  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|版本升級  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|大量啟用 (KMS/MAK)  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |
   
> <sup>1</sup> azure 資訊保護未包含在內，但是可以購買作為個別的附加元件與將會啟用支援的資訊版權管理 (IRM) 功能。一些 Azure 資訊保護功能需要訂閱即可 Office 365 ProPlus，此做法便不包含在 Office 365 美國政府版 G1 或 Office 365 美國政府 f1 鍵。<br/><sup>2</sup> Windows Server AD RMS 是內部部署伺服器必須是個別採購並管理啟用支援的 IRM 功能。 
<br/><sup>3</sup>的商業基本 Skype 是可用的所有客戶。商務桌面用戶端 Skype 是在本機上已安裝的應用程式提供顯示狀態、 立即訊息與會議功能內含 Skype 商務 Online 的 Office 365 計劃。Office 365 ProPlus 和 Office 365 企業版 E3 包含完整 Skype 應用程式，其中包含其他功能，例如進階電話語音支援、 封存、 和符合性功能。商務 Online 授權 Skype 必須被指派每位使用者。如需有關 Lync Basic 功能的詳細資訊，請參閱[Skype for Business Online 用戶端比較表](https://technet.microsoft.com/en-us/library/gg425836%28v=ocs.15%29.aspx)。<br/><sup>4</sup>尚無法使用 GCC 高或 DoD 環境中，但即將推出。
<br/><sup>5</sup>請參閱[使用 Outlook iOS 及 Android 政府社群雲端中的](https://docs.microsoft.com/en-us/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud)如需詳細資訊。
  <br/><sup>6</sup>尚無法使用在 Office 365 DoD 環境中，但即將推出。
<br/><br/>[如何使用此「服務說明」一節](office-365-us-government.md#how-to-use-this-service-description-section)
