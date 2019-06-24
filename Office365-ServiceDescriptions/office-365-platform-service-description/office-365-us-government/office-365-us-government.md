---
title: Office 365 US Government
ms.author: danarl
author: danarl
manager: dianap
ms.date: 3/4/2019
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 3f482abc-993f-41bf-8754-0f489a7e4861
description: 為了回應美國公開部門的獨特和演變需求, Microsoft 已建立 Office 365 美國政府版方案 (orOffice 365 美國政府版)。 本節提供 Office 365 US Government 特有功能的概觀。 建議您閱讀此補充章節, 以及 Office 365 服務說明。
ms.openlocfilehash: 1d7878c232f8c08c4b039562d0424fba9fd48d07
ms.sourcegitcommit: 0f5ad374ff3559c10a1665d894d68665dbd1214b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/21/2019
ms.locfileid: "35131277"
---
# <a name="office-365-us-government"></a>Office 365 US Government

為了回應美國公開部門的獨特和演變需求, Microsoft 已建立 Office 365 美國政府方案 (或「Office 365 美國政府版」)。 本節提供 Office 365 US Government 特有功能的概觀。 建議您閱讀此補充章節, 以及[Office 365 服務說明](../../office-365-service-descriptions-technet-library.md)。
  
## <a name="how-to-use-this-service-description-section"></a>如何使用此「服務說明」一節
<a name="TopOfPage"> </a>

Office 365 US Government 服務說明的設計目的在於與一般 Office 365 服務說明之間互相對照，定義了與 Office 365 企業版產品之間特色和差異的比較。
  
## <a name="about-office-365-us-government-environments"></a>關於 Office 365 美國政府環境
<a name="BM1_About"> </a>

Office 365 US Government 方案為每月訂閱，並且可授權給不限數量的使用者。 
  
- **Office 365 GCC**環境可提供雲端服務的聯邦需求 (包括 FedRAMP 適中), 以及犯罪審判和聯邦稅務資訊系統 (CJI 和 FTI 資料類型) 的需求。 
    
- **Office 365 GCC 的高和 DoD**環境提供遵守國防部的安全性需求指導方針、國防聯邦收購規定 (DFARS), 以及 arm 規章 (ITAR) 中的國際流量。 
    
除了具有 Office 365 的功能外，使用 Office 365 US Government 的組織還可從以下專屬於 Office 365 US Government 的功能獲得好處：
  
- 組織的客戶內容和 Microsoft 的商業 Office 365 服務中的客戶內容會以邏輯方式區隔。
    
- 組織的客戶內容儲存於美國境內。
    
- 只有經過篩選的 Microsoft 人員可以存取組織的客戶內容。
    
- Office 365 US Government 符合美國公共部門客戶所要求的認證和資格鑑定。
    
[如何使用此服務描述區段](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="customer-eligibility"></a>客戶資格
<a name="BM2-customer"> </a>

Office 365 美國政府版可供 (1) 美國聯邦、州、local、部落和 territorial 政府機構, 以及 (2) 其他實體, 負責處理政府法規和需求的資料, 以及 Office 365 美國政府的使用方式。適用于符合這些需求, 請遵守資格驗證。 Microsoft 的資格驗證將會包含以 Arm 規定 (ITAR) 中的國際流量為目標的處理資料的確認, 法律強制執行資料受 FBI 的刑事審判資訊服務 (CJIS) 原則或其他政府管制或控制的資料。 驗證可能需要使用美國的美國部門的註冊證明, 以 ITAR 資料, 或政府機構的資助, 以處理資料的特定需求。 Office 365 DoD 環境是專為美國國防部專屬使用。
  
雖然在 Office 365 美國政府版方案中的資格準則是一致的, 但 Microsoft 只會同意 DFARS 和 ITAR 合約語言的 GCC 高環境。
  
若有關於 Office 365 US Government 資格問題的機構應諮詢其客戶團隊。
  
在更新客戶的 Office 365 US Government 合約時，必須重新驗證資格。
  
[如何使用此服務描述區段](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="customer-content-located-within-the-united-states"></a>美國境內的客戶內容
<a name="BM3-withinUSA"> </a>

Office 365 US Government 服務是由美國境內的實體資料中心所提供。下列客戶內容會靜止存放在僅位於美國境內的實體資料中心裡： 
  
- Exchange Online 信箱內容 (電子郵件內文、行事曆項目和電子郵件附件的內容)。
    
- SharePoint Online 站台內容和儲存在該站台內的檔案。
    
- 商務用 Skype 保存的對話、上傳的文件和白板工作階段。
    
> [!NOTE]
> 一般來說，商務用 Skype 不會儲存客戶內容，但是如果有儲存的話，將會儲存在美國境內的資料中心。 
  
如果您的使用者在美國境內中使用 Office (先前稱為 Office Web Apps), 或是採用 Active Directory Federation Services (AD FS) 2.0 並設定原則, 以協助確保使用者透過單一 si 連接至服務gn-開啟時, 在網頁版中暫時快取的任何客戶內容都將位於美國境內中。
  
[如何使用此服務描述區段](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="office-365-us-government-and-third-party-services"></a>Office 365 US Government 與協力廠商服務
<a name="BM4-3rdParty"> </a>

Office 365 可將協力廠商的應用程式整合至 SharePoint Online 站台、商務用 Skype、Office 365 ProPlus 中的 Office 應用程式 (如 Word、Excel、PowerPoint 和 Outlook) 以及 Outlook Web App。此外，Office 365 還支援與服務提供者協力廠商整合。這些協力廠商應用程式和服務可能會在 Office 365 基礎結構外的協力廠商系統上儲存、傳輸和處理組織的客戶資料，因此不在 Office 365 規範和資料保護承諾的保證範圍內。建議您檢閱協力廠商提供的隱私權和規範聲明，來評估適合組織的服務使用方式。
  
[如何使用此服務描述區段](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="restricted-data-access-by-administrators"></a>受限制的系統管理員資料存取
<a name="BM5-Restricted"> </a>

Microsoft 系統管理員可以存取 Office 365 美國政府客戶內容, 僅限於對人員進行篩選。 如需詳細的篩選層級詳細資料, 請參閱每個個別環境 (GCC 或 GCC 高和 DoD) 的服務描述頁面。 

  
## <a name="fasttrack-center-onboarding-assistance"></a>FastTrack Center 上架協助
<a name="BM5-Restricted"> </a>

透過 Office 365<sup>1</sup>的 FastTrack Center 權益, 您可以與 FastTrack 專家遠端合作, 讓您的 Office 365 環境準備好使用, 並規劃組織內的推廣和使用方式。 FastTrack 程序提供上架和使用者採用服務。 
  
上架包含︰
  
- 核心上架--這些是租使用者設定及與 Azure Active Directory (Azure AD) 整合所需的工作 (如有需要)。 核心上架也能成為將其他合格之服務上架的基準。
    
- 服務上架和遷移-服務上架工作會啟用您租使用者中的案例。 資料移轉中涵蓋資料移轉 (包括電子郵件和[](https://aka.ms/whatcanmigrate)檔案)。<sup>2</sup>
    
使用者採用服務由數項工作所組成，提供您指引以確保您的使用者知道適合的服務，並用來促進商業價值。
  
您可以在[這裡](https://aka.ms/whatistheprocess)找到 FastTrack Center 程式的特定資訊。 如需參與角色和責任的細目, 請查看[FastTrack 責任](https://aka.ms/whatdoesftcdo)以及[您的責任](https://aka.ms/whatdowedo)。
  
<sup>1</sup>您必須從[合格方案](https://aka.ms/whocanbenefit)清單中購買至少50授權, 才能收到 FastTrack 服務。 
  
<sup>2</sup>資料移轉服務可供含500或更多授權的 Office 365 租使用者使用。 
  
## <a name="data-migrations-performed-by-fasttrack"></a>FastTrack 執行的資料移轉
<a name="BM5-Restricted"> </a>

選擇[FastTrack](https://fasttrack.microsoft.com/)遷移權益的客戶必須將存取權授與管理其資料移轉的小組。 這些人員都是美國公民, 並在為 Office 365 美國政府服務的客戶執行遷移之前先進行下列背景檢查。 
  
||||
|:-----|:-----|:-----|
|**背景檢測** <br/> |**GCC** <br/> |**GCC High 和 DoD** <br/> |
|美國公民權驗證  <br/> |是  <br/> |是  <br/> |
|工作經驗檢查  <br/> |是  <br/> |是  <br/> |
|教育驗證  <br/> |是  <br/> |是  <br/> |
|社會保險號碼 (SSN) 搜尋  <br/> |是  <br/> |是  <br/> |
|刑事案件記錄檢查 (7 年)  <br/> |是  <br/> |是  <br/> |
   
[如何使用此服務描述區段](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="office-365-us-government-and-azure-government-expressroute"></a>Office 365 US Government 和 Azure 政府版 Express Route
<a name="BM6-Express"> </a>

Office 365 US Government 客戶可以使用 Azure 政府版 ExpressRoute 服務私下連線到支援的 Office 365 服務，而不透過公用的網際網路連線。
  
如需了解支援提供者、價格模型及相關資訊的詳細資料，請檢閱 [Azure ExpressRoute 資訊](http://go.microsoft.com/fwlink/?LinkID=798220&amp;clcid=0x409)。
  
如需 Office 365 Azure ExpressRoute 支援的詳細資訊，請參閱 [Azure ExpressRoute for Office 365](http://go.microsoft.com/fwlink/?LinkID=798216&amp;clcid=0x409)。
  
[如何使用此服務描述區段](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="system-requirements"></a>系統需求
<a name="BM9-Requirements"> </a>

如需適用於 Office 365 US Government 方案的系統需求，請參閱 [office.com](http://go.microsoft.com/fwlink/?LinkID=626095&amp;clcid=0x409) 產品網站上的 [Office 的系統需求](http://go.microsoft.com/fwlink/?LinkID=509817&amp;clcid=0x409)。 
  
[如何使用此服務描述區段](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="security-amp-compliance-center"></a>安全性&amp;與規範中心
<a name="BM9-Requirements"> </a>

如需安全性&amp;與合規性中心的相關資訊, 以及其他資訊與可用性的連結, 請參閱[Office 365 安全性&amp;與合規性中心](../../office-365-platform-service-description/office-365-securitycompliance-center.md)。
  
## <a name="service-availability-for-each-plan"></a>每個方案可用的服務
<a name="BM9-Requirements"> </a>

每個 Office 365 方案皆包含一些個別服務，例如 Exchange Online 和 SharePoint Online。下表顯示每項 Office 365 US Government 方案中可用的服務。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**Office 365 服務** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府版 G3** <br/> |**Office 365 美國政府版 G5** <br/> |**Office 365 美國政府版 F1** <br/> |
|Web 版 Office  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Office 365 專業增強版  <br/> |否 <br/> |是 <br/> |是 <br/> |否  <br/> |
|Exchange Online  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Exchange Online Protection  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|SharePoint Online  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|商務用 OneDrive  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Skype for Business (Instant Messaging &amp; Presence)  <br/> |是<sup>1</sup> <br/> |是  <br/> |是  <br/> |是<sup>1</sup> <br/> |
| 語音電話系統、音訊會議  <br/> |否<sup>2, 3</sup> <br/> |否<sup>2, 3</sup> <br/> |是<sup>3、5</sup> <br/> |否  <br/> |
|Power BI Pro  <br/> |無<sup>2</sup> <br/> |無<sup>2</sup> <br/> |是  <br/> |無<sup>2</sup> <br/> |
|Project Online  <br/> |無<sup>2</sup> <br/> |無<sup>2</sup> <br/> |無<sup>2</sup> <br/> |無<sup>2</sup> <br/> |
|Visio Online  <br/> |無<sup>6</sup> <br/> |無<sup>6</sup> <br/> |無<sup>6</sup> <br/> |無<sup>6</sup> <br/> |
|Yammer Enterprise  <br/> |無<sup>4</sup> <br/> |無<sup>4</sup> <br/> |無<sup>4</sup> <br/> |無<sup>4</sup> <br/> |
   
> <sup>1</sup>商務用 Skype 基本版適用于所有客戶。 商務用 Skype 桌面用戶端是在本機安裝的應用程式，可針對包含 商務用 Skype Online 的 Office 365 方案，提供目前狀態、立即訊息和會議功能。 Office 365 專業增強版、G3 和 G5 包含完整的 Skype 應用程式, 其包含額外的功能, 例如: 高級電話語音支援、封存及合規性功能。 A Skype for Business Online license must be assigned for each user.
<br/><sup>2</sup>不包含在內, 但能以個別的附加元件形式購買。 Project Online 包含 Project Online 桌面用戶端作為訂閱的一部分。
<br/> <sup>3</sup>在 GCC 高或 DoD 方案中尚未提供, 但即將推出。 
<br/><sup>4</sup> Yammer 企業不是 OFFICE 365 美國政府版的元件, 但可為 GCC 中 office 365 授權的每位使用者提供免費服務。 這項優惠目前僅限於以企業協定和企業訂閱協定購買 Office 365 GCC 的客戶。 在 GCC High 或 DoD 中無法使用 Yammer。
<br/><sup>5</sup>通話方案是附加元件。 
<br/><sup>6</sup>不包含在內, 但能以個別的附加元件形式購買。 Visio Online 包含 Visio Online 桌面用戶端作為訂閱的一部分。  
## <a name="platform-features"></a>平台功能
<a name="BM7-Platform"> </a>

下表列出可用於 Office 365 US Government 方案的平台功能和服務。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府版 G3** <br/> |**Office 365 美國政府版 G5** <br/> |**Office 365 美國政府版 F1** <br/> |
|**Office 365 管理** <br/> |||||
|使用 Microsoft 365 系統管理中心管理 Office 365  <br/> |是<sup>16</sup> <br/> |是<sup>16</sup> <br/> |是  <br/> |是<sup>16</sup> <br/> |
|從 Office 365 管理核心服務設定  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|使用 Windows PowerShell 管理 Office 365  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|使用 Azure 資訊保護 來保護內容  <br/> |沒有<sup>1</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup>  <br/> |沒有<sup>1</sup> <br/> |
|**[Office 365 套件功能](../../office-365-platform-service-description/office-365-suite-features.md)** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府版 G3** <br/> |**Office 365 美國政府版 G5** <br/> |**Office 365 美國政府版 F1** <br/> |
|Microsoft Bookings  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |
|Microsoft Flow  <br/> |是<sup>11</sup> <br/> |是<sup>11</sup> <br/> |是<sup>11</sup> <br/> |是<sup>11</sup> <br/> |
|Microsoft Forms  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|Microsoft Graph API  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Microsoft MyAnalytics  <br/> |無<sup>9、12、15</sup> <br/> |無<sup>9、12、15</sup> <br/> |是<sup>9, 15</sup> <br/> |無<sup>9、12、15</sup> <br/> |
|Microsoft Planner  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|Microsoft PowerApps  <br/> |是<sup>11</sup> <br/> |是<sup>11</sup> <br/> |是<sup>11</sup> <br/> |是<sup>11</sup> <br/> |
|Microsoft StaffHub  <br/> |否 <br/> |否 <br/> |否 <br/> |否<br/> |
|Microsoft Stream  <br/> |是<sup>11</sup> <br/> |是<sup>11</sup> <br/> |是<sup>11</sup> <br/> |否  <br/> |
|Microsoft Sway  <br/> |否 <br/> |否 <br/> |否 <br/> |否 <br/> |
|Microsoft Teams  <br/> |是 <br/> |是 <br/> |是 <br/> |是 <br/> |
|Office Delve  <br/> |是<sup>17</sup> <br/> |是<sup>17</sup> <br/> |是  <br/> |是<sup>17</sup> <br/> |
|Office 365 群組  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Microsoft Stream  <br/> |是<sup>9, 15</sup> <br/> |是<sup>9, 15</sup> <br/> |是<sup>9, 15</sup> <br/> |否  <br/> |
|**[使用者帳戶管理](../../office-365-platform-service-description/user-account-management.md)** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府版 G3** <br/> |**Office 365 美國政府版 G5** <br/> |**Office 365 美國政府版 F1** <br/> |
|雲端身分識別  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|同盟身分識別 (單一登入)  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|多重要素驗證  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|電話因素驗證  <br/> |是<sup>9</sup> <br/> |是<sup>9</sup> <br/> |是  <br/> |是<sup>9</sup> <br/> |
|Office 365 桌面設定  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|以 Office 365 管理使用者  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|使用 .csv 檔案大量上傳  <br/> |是<sup>9</sup> <br/> |是<sup>9</sup> <br/> |是  <br/> |是<sup>9</sup> <br/> |
|目錄同步處理工具  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Exchange 簡易 (完全) 移轉  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|透過使用 Office 365 來刪除帳戶  <br/> |是 <sup>3</sup> <br/> |是 <sup>3</sup> <br/> |是 <sup>3</sup> <br/> |是 <sup>3</sup> <br/> |
|管理員可以從 Office 365 或使用 Windows PowerShell 重設使用者密碼  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |
|使用者可以變更自己的密碼  <br/> |是 <sup>5</sup> <br/> |是 <sup>5</sup> <br/> |是 <sup>5</sup> <br/> |是 <sup>5</sup> <br/> |
|管理授權  <br/> |是<sup>7, 8</sup> <br/> |是<sup>7, 8</sup> <br/> |是<sup>7, 8</sup> <br/> |是<sup>7,8</sup> <br/> |
|從 Office 365 管理安全性群組  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|多個可用的管理員角色  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|允許合作夥伴代替您管理 Office 365  <br/> |是<sup>11</sup> <br/> |是<sup>11</sup> <br/> |是<sup>11</sup> <br/> |是<sup>11</sup> <br/> |
|Azure Active Directory 服務  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[網域](../../office-365-platform-service-description/domains.md)** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府版 G3** <br/> |**Office 365 美國政府版 G5** <br/> |**Office 365 美國政府版 F1** <br/> |
|新增自訂的第 2 層網域，如 fourthcoffee.com  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|新增自訂的第 3 層網域，如 marketing.fourthcoffee.com  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|最多可新增 900 個自訂網域  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|自訂網域需要網域所有權驗證  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[服務健康狀況和持續性](../../office-365-platform-service-description/service-health-and-continuity.md)** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府版 G3** <br/> |**Office 365 美國政府版 G5** <br/> |**Office 365 美國政府版 F1** <br/> |
|可在 **[服務健康狀況]** 或 **[服務狀態]** 頁面上獲取狀態資訊  <br/> |是<sup>9, 15</sup> <br/> |是<sup>9, 15</sup> <br/> |是<sup>9, 15</sup> <br/> |是<sup>9, 15</sup> <br/> |
|Microsoft 365 系統管理中心儀表板上可用的個別警示狀態  <br/> |是<sup>9, 15</sup> <br/> |是<sup>9, 15</sup> <br/> |是<sup>9, 15</sup> <br/> |是<sup>9, 15</sup> <br/> |
|**服務健康狀況** RSS 摘要  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[報告](../../office-365-platform-service-description/reports.md)** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府版 G3** <br/> |**Office 365 美國政府版 G5** <br/> |**Office 365 美國政府版 F1** <br/> |
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
|**[服務更新](../../office-365-platform-service-description/service-updates.md)** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府版 G3** <br/> |**Office 365 美國政府版 G5** <br/> |**Office 365 美國政府版 F1** <br/> |
|提供給所有客戶的定期更新  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|需要採取 行動時， 將通知傳送給 「訊息中心」  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|Roadmap.office.com 的一些服務 更新  <br/> |無<sup>10、13</sup> <br/> |無<sup>10、13</sup> <br/> |無<sup>10、13</sup> <br/> |無<sup>10、13</sup> <br/> |
|開啟目標版本的選項  <br/> |是<sup>10</sup> <br/> |是<sup>10</sup> <br/> |是<sup>10</sup> <br/> |是<sup>10</sup> <br/> |
|**[說明和訓練](../../office-365-platform-service-description/help-and-training.md)** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府版 G3** <br/> |**Office 365 美國政府版 G5** <br/> |**Office 365 美國政府版 F1** <br/> |
|線上說明  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|社群  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|其他自助資源  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|自訂進度訓練  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[網路功能](../../office-365-platform-service-description/networking.md)** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府版 G3** <br/> |**Office 365 美國政府版 G5** <br/> |**Office 365 美國政府版 F1** <br/> |
|IPv4 和 IPv6 通訊協定  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**信任** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府版 G3** <br/> |**Office 365 美國政府版 G5** <br/> |**Office 365 美國政府版 F1** <br/> |
|**[隱私權、安全性和透明化](../../office-365-platform-service-description/privacy-security-and-transparency.md)** <br/> |||||
|進階資料管理  <br/> |無<sup>12</sup> <br/> |無<sup>12</sup> <br/> |是 <br/> |無<sup>12</sup> <br/> |
|雲端 App 安全性  <br/> |無<sup>11、12</sup> <br/> |無<sup>11、12</sup> <br/> |是<sup>11</sup> <br/> |無<sup>11、12</sup> <br/> |
|進階威脅防護  <br/> |無<sup>12</sup> <br/> |無<sup>12</sup> <br/> |是  <br/> |無<sup>12</sup> <br/> |
|客戶加密箱  <br/> |無<sup>9、12、15</sup> <br/> |無<sup>9、12、15</sup> <br/> |是<sup>9, 15</sup> <br/> |無<sup>9、12、15</sup> <br/> |
|Office 365 進階電子文件探索  <br/> |無<sup>12</sup> <br/> |無<sup>12</sup> <br/> |是  <br/> |無<sup>12</sup> <br/> |
|安全分數<sup>14</sup> <br/> |是<sup>9, 15</sup> <br/> |是<sup>9</sup> <br/> |是<sup>9, 15</sup> <br/> |是<sup>9, 15</sup> <br/> |
|Office 郵件加密  <br/> |否  <br/> |是 <br/> |是 <br/> |否  <br/> |
|威脅情報  <br/> |無<sup>12</sup> <br/> |無<sup>12</sup> <br/> |是 <br/> |無<sup>12</sup> <br/> |
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
|**[BlackBerry](../../office-365-platform-service-description/blackberry.md)** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府版 G3** <br/> |**Office 365 美國政府版 G5** <br/> |**Office 365 美國政府版 F1** <br/> |
|使用 BlackBerry Internet Service (BIS)  <br/> |無<sup>2</sup> <br/> |無<sup>2</sup> <br/> |無<sup>2</sup> <br/> |無<sup>2</sup> <br/> |
|**[協力程式](../../office-365-platform-service-description/partners.md)** <br/> |||||
|針對正在使用指定計劃的客戶建立試用邀請和購買訂單  <br/> |無<sup>11</sup> <br/> |無<sup>11</sup> <br/> |無<sup>11</sup> <br/> |無<sup>11</sup> <br/> |
|提供委派管理  <br/> |無<sup>11</sup> <br/> |無<sup>11</sup> <br/> |無<sup>11</sup> <br/> |無<sup>11</sup> <br/> |
|**[服務等級協定](../../office-365-platform-service-description/service-level-agreement.md)** <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[產品使用權限](../../office-365-platform-service-description/product-use-rights.md)** <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
   
> <sup>1</sup> Azure 資訊保護不包含在內, 但能以個別的附加元件形式購買, 並且會啟用支援的資訊版權管理 (IRM) 功能。 某些 Azure 資訊保護功能需要訂閱 Office 365 專業增強版, 但不包含在 Office 365 美國政府版 G1 或 Office 365 美國政府 F1。 > 
<br/><sup>2</sup> 現有的 BBCS 和 BIS 客戶可以繼續使用服務。 不接受新的客戶。 
<br/><sup>3</sup> 如果您是使用目錄同步處理，則必須使用 Active Directory (非使用 Office 365 入口網站) 或使用 Windows PowerShell 的 Azure Active Directory 模組來刪除帳戶或變更密碼。 
<br/><sup>4</sup> 如果使用密碼同步化，使用者必須在本機 Active Directory 中變更其密碼。 
<br/><sup>5</sup> 若要了解如何為使用者設定自助式密碼管理原則，請參閱 [在 Azure AD 中管理密碼](https://azure.microsoft.com/en-us/documentation/articles/active-directory-manage-passwords/)。 <br/><sup>6</sup> 您在 Office 365 只能有一個公用網站，除非您已從舊版 Office 365 升級。 在後者情況下，您有兩個公用網站，但只有一個能以自訂的網域名稱裝載。 如需就商務版訂閱來使用這兩個網站的詳細資訊，請參閱 [使用您的兩個 Office 365 公用網站](https://go.microsoft.com/fwlink/p/?LinkID=271589)。 如果您有不同的訂閱，請到 [Office 365 的公用網站說明](https://go.microsoft.com/fwlink/p/?LinkID=325009)深入了解公用網站。 
<br/><sup>7</sup> 若減少以折扣條件購買的基座，有可能需支付提前終止訂閱的費用。 這不適用於每月付款的訂閱。 
<br/><sup>8</sup>下列方案不支援 Microsoft 365 系統管理中心的授權基座變更: > OFFICE 365 美國政府版 G1 > OFFICE 365 美國政府版 G3 > OFFICE 365 美國政府 K1 <br/><sup>9</sup>尚未提供, 但即將推出。
<br/><sup>10</sup> For OFFICE 365 US 政府版 G1、G3 和 F1、目標版本和 office 365 For business 藍圖適用于。不過, 由於[合規性需求](https://products.office.com/en-us/business/office-365-trust-center-cloud-computing-security?legRedir=true&amp;CorrelationId=eeaccba9-85ea-4fa8-9c84-3fb4c9e1547b&amp;tab=7a3a6365-14c0-81ac-34ff-f4a416599263), 特定服務更新可能會有一些差異或延遲。
<br/><sup>11</sup> OFFICE 365 美國政府版方案中尚未提供, 但即將推出。 ><br/><sup>12</sup>不包含在內, 但能以個別的附加元件形式購買。 
<br/><sup>13</sup>不支援 OFFICE 365 美國政府版產品。 
<br/><sup>14</sup>可供[https://securescore.office.com](https://securescore.office.com)使用。 需要系統管理員許可權。 如需詳細資訊, 請參閱[簡介 Office 365 安全分數](https://go.microsoft.com/fwlink/?linkid=836894)。 
<br/><sup>15</sup>尚未在 DoD 環境中使用, 但即將推出。 
<br><sup>16</sup>系統管理中心不包括 DOD 或 GCC 高環境中的流量分析
<br><sup>17</sup>不支援 GCC (高或 DoD) 環境
  
[如何使用此服務描述區段](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="office-application-features"></a>Office 應用程式功能  
<a name="BM11-Applications"> </a>

下表顯示可用於 Office 365 US Government 方案的 Office 應用程式功能。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府版 G3** <br/> |**Office 365 美國政府版 G5** <br/> |**Office 365 美國政府版 F1** <br/> |
|**Office 應用程式** <br/> |||||
|[Microsoft Word](../../office-applications-service-description/office-applications.md#microsoft-word) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Microsoft Excel](../../office-applications-service-description/office-applications.md#microsoft-excel) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Microsoft PowerPoint](../../office-applications-service-description/office-applications.md#microsoft-powerpoint) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Microsoft OneNote](../../office-applications-service-description/office-applications.md#microsoft-onenote) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Microsoft Outlook](../../office-applications-service-description/office-applications.md#microsoft-outlook) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Microsoft Publisher](../../office-applications-service-description/office-applications.md#microsoft-publisher) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Microsoft Access](../../office-applications-service-description/office-applications.md#microsoft-access) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[商務用 Skype](../../office-applications-service-description/office-applications.md#skype-for-business) <br/> |是<sup>3</sup> <br/> |是  <br/> |是  <br/> |是<sup>3</sup> <br/> |
|[Office 365 的 Mac 版 Office](https://support.office.com/en-us/article/General-requirements-for-Outlook-2016-for-Mac-A07A593D-B383-4906-A6C1-962D5543ED57?ui=en-US&amp;rs=en-US&amp;ad=US) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Office Mobile for iPad/iPhone](../../office-applications-service-description/office-applications.md#office-mobile-for-ipadiphone) <br/> |否  <br/> |是的<sup></sup> <br/> |是<sup></sup> <br/> |否  <br/> |
|[Office Mobile for Android](../../office-applications-service-description/office-applications.md#office-mobile-for-android) <br/> |否  <br/> |是的<sup></sup> <br/> |是<sup></sup> <br/> |否  <br/> |
|[適用於 Windows Phone 手機的 Office Mobile](../../office-applications-service-description/office-applications.md#office-mobile-for-windows-phone) <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|Office Mobile for Windows 10 tablets <br/> |否  <br/> |是的<sup></sup> <br/> |是<sup></sup> <br/> |否  <br/> |
|Outlook for iOS 和 Android<sup>5, 4</sup>  <br/> |是 <br/> |是 <br/> |是 <br/> |是 <br/> |
|**企業價值** <br/> |**Office 365 美國政府版 G1** <br/> |**Office 365 美國政府版 G3** <br/> |**Office 365 美國政府版 G5** <br/> |**Office 365 美國政府版 F1** <br/> |
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
|使用 Azure 資訊保護的資訊版權管理  <br/> |沒有<sup>1</sup> <br/> |是<sup>6</sup> <br/> |是<sup>6</sup> <br/> |沒有<sup>1</sup> <br/> |
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
|漫遊設定  <br/> |否  <br/> |是的<sup></sup> <br/> |是<sup></sup> <br/> |否  <br/> |
|共用電腦啟用  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|支援對雲端架構檔案儲存進行封鎖  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|版本升級  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|大量啟用 (KMS/MAK)  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |
   
> <sup>1</sup> Azure 資訊保護不包含在內, 但能以個別的附加元件形式購買, 並且會啟用支援的資訊版權管理 (IRM) 功能。 某些 Azure 資訊保護功能需要訂閱 Office 365 專業增強版, 但不包含在 Office 365 美國政府版 G1 或 Office 365 美國政府 F1。 
<br/><sup>2</sup> WINDOWS SERVER AD RMS 是內部部署伺服器, 必須個別採購並管理, 以啟用支援的 IRM 功能。 
<br/><sup>3</sup>商務用 Skype 基本版適用于所有客戶。 商務用 Skype 桌面用戶端是在本機安裝的應用程式，可針對包含 商務用 Skype Online 的 Office 365 方案，提供目前狀態、立即訊息和會議功能。 Office 365 專業增強版和 Office 365 企業版 E3 包含完整的 Skype 應用程式, 其包含額外的功能, 例如: 高級電話語音支援、封存及合規性功能。 A Skype for Business Online license must be assigned for each user. For more information on Lync Basic features, see [Skype for Business Online client comparison tables](https://technet.microsoft.com/en-us/library/gg425836%28v=ocs.15%29.aspx). 
<br/><sup>4</sup>在 GCC 高或 DoD 環境中尚未提供, 但即將推出。
<br/><sup>5</sup>如需詳細資訊, 請參閱[在政府版雲端中使用適用于 iOS 和 Android 的 Outlook](https://docs.microsoft.com/en-us/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud) 。
  <br/><sup>6</sup> Office 365 DoD 環境中尚未提供, 但即將推出。
<br/><br/>[如何使用此服務描述區段](office-365-us-government.md#how-to-use-this-service-description-section)
