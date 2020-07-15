---
title: Office 365 US Government
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 3f482abc-993f-41bf-8754-0f489a7e4861
description: 為了回應美國公開部門的獨特和不斷演變的需求，Microsoft 已建立 Office 365 美國政府方案（或 Office 365 政府版）。 本文概要說明 Office 365 政府美國環境所特有的功能。
ms.openlocfilehash: 7ca2dc6afa9d22f17b7c95d338e5b700df070d42
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131727"
---
# <a name="office-365-us-government"></a>Office 365 US Government

> [!IMPORTANT]
> 因為 coronavirus （COVID-19） pandemic，所以 Microsoft 團隊在線上通話和音訊/視訊會議方面的經歷極大。<br/>
> 
>為了回應空前增加的通話，並確保持續性和可用性，Microsoft 可讓 Microsoft 小組擁有的音訊/視訊伺服器，利用我們的商業資料中心及政府資料中心的處理能力。<br/>
> 
>這些音訊/視訊伺服器位於美國的 Microsoft Azure FedRAMP 高資格鑒定界限伺服器內，而且不會儲存任何客戶內容。 不過，這些伺服器正在處理通話和會議的音訊和影片，且在這段期間內由商業員工運作。<br/>
> 
>合格的遮罩式人員會透過複查這些伺服器的任何互動式登入，監視這些伺服器以取得客戶資料的潛在存取權。 合格的人員可在存取客戶內容時，符合 GCC 的要求。 如需篩選要求的詳細資訊，請參閱[GCC service description](gcc.md)。<br/>
> 
>在我們採取步驟時，感謝您的支援，以確保我們的服務在這些特別的時間內仍保持可用及可靠的狀態。<br/> 

為了回應美國公開部門的獨特和不斷演變的需求，Microsoft 已建立 Office 365 美國政府方案（或 Office 365 政府版）。 本節提供 Office 365 政府美國環境特有功能的概覽。 我們建議您閱讀此補充章節（ [Microsoft 365 和 Office 365 服務說明](../../office-365-service-descriptions-technet-library.md)）。
  
## <a name="how-to-use-this-service-description"></a>如何使用此服務說明

「Office 365 美國政府服務說明」是設計為一般 Office 365 服務說明的疊加。 與 Office 365 企業版產品相比，它會定義獨特的承諾和差異。
  
## <a name="about-office-365-us-government-environments"></a>關於 Office 365 美國政府環境

Office 365 US Government 方案為每月訂閱，並且可授權給不限數量的使用者。 
  
- **Office 365 GCC**環境可滿足雲端服務的聯邦需求，包括 FedRAMP 適中，以及刑事審判和聯邦稅收資訊系統的需求（CJI 及 FTI 資料類型）。 
    
- **Office 365 GCC 高和 DoD**環境會為管制原則（ITAR）中的國防安全性需求指導方針、國防聯邦購買法規補充（DFARS）及國際流量提供法規遵從性。 
    
除了具有 Office 365 的功能外，使用 Office 365 US Government 的組織還可從以下專屬於 Office 365 US Government 的功能獲得好處：
  
- 組織的客戶內容和 Microsoft 的商業 Office 365 服務中的客戶內容會以邏輯方式區隔。
    
- 組織的客戶內容儲存於美國境內。
    
- 只有經過篩選的 Microsoft 人員可以存取組織的客戶內容。
    
- Office 365 US Government 符合美國公共部門客戶所要求的認證和資格鑑定。
  
## <a name="customer-eligibility"></a>客戶資格

Office 365 US 政府可用於（1）美國聯邦、state、local、部落及 territorial 政府機構，以及（2）個其他實體，可處理政府法規和需求的相關資料，以及使用 Office 365 US 政府來符合這些需求（遵循資格驗證）。 Microsoft 的資格驗證會包含對透過 Arm 法規（ITAR）中的國際流量所加以的處理資料的確認、法律強制執行資料（遵循 FBI 的刑事審判資訊服務（CJIS）原則，或其他政府管制或受管理的資料）。 驗證可能需要使用美國州的「州」部門進行註冊，以供政府機構使用特定的資料處理要求的 ITAR 資料或資助。 Office 365 DoD 環境是以專屬方式使用美國國防部。
  
雖然各 Office 365 政府產品皆符合資格準則，但 Microsoft 只會同意 DFARS 及 ITAR 合約語言的 GCC 高環境。
  
若有關於 Office 365 US Government 資格問題的機構應諮詢其客戶團隊。
  
在更新客戶的 Office 365 US Government 合約時，必須重新驗證資格。
  
## <a name="customer-content-located-within-the-united-states"></a>美國境內的客戶內容

Office 365 US Government services are provided from datacenters physically located in the United States. The following customer content is stored at rest in datacenters physically located only in the U.S.A.: 
  
- Exchange Online 信箱內容（電子郵件內文、行事曆專案和電子郵件附件的內容）
    
- SharePoint 線上網站內容和儲存在該網站中的檔案
    
- 商務用 Skype 封存對話、上傳的檔和白板會話

- Microsoft 團隊持久聊天線程
    
> [!NOTE]
> 一般來說，商務用 Skype 不會儲存客戶內容，但是如果有儲存的話，將會儲存在美國境內的資料中心。 
  
如果您的使用者在美國境內中使用 Office （以前稱為 Office Web Apps），或是採用 Active Directory Federation Services （AD FS）2.0 和設定原則，以協助確保您的使用者透過單一登入連線到服務，則暫時快取在 Office 中的任何客戶內容都會位於美國境內中。
  
## <a name="office-365-us-government-and-third-party-services"></a>Office 365 US Government 與協力廠商服務

Office 365 提供將協力廠商應用程式整合至 SharePoint Online 網站、商務用 Skype、商務365用 Office 應用程式（如 Word、Excel、PowerPoint 和 Outlook）和 Outlook Web App 的功能。 此外，Office 365 還支援與服務提供者協力廠商整合。 這些協力廠商應用程式和服務可能會在 Office 365 基礎結構外的協力廠商系統上儲存、傳輸和處理組織的客戶資料，因此不在 Office 365 規範和資料保護承諾的保證範圍內。 建議您檢閱協力廠商提供的隱私權和規範聲明，來評估適合組織的服務使用方式。
  
## <a name="restricted-data-access-by-administrators"></a>受限制的系統管理員資料存取

Microsoft 系統管理員對 Office 365 美國政府客戶內容的存取權僅限於對人員進行遮罩式。 如需詳細的詳細資訊，請參閱每個個別環境（GCC 或 GCC 高端和 DoD）的服務描述頁面。 

  
## <a name="fasttrack-center-onboarding-assistance"></a>FastTrack 中心上架協助

透過 Office 365<sup>1</sup>的 FastTrack 中心權益，您可以與 FastTrack 專家遠端合作，讓您的 Office 365 環境做好使用，並規劃組織內的首展和使用方式。 FastTrack 程序提供上架和使用者採用服務。 
  
上架包含︰
  
- 核心上架-這些是租使用者設定及與 Azure Active Directory （Azure AD）整合時所需的工作（如有需要）。 核心上架也能成為將其他合格之服務上架的基準。
    
- 服務上架和遷移-服務上架工作會啟用您租使用者中的案例。 資料移轉中涵蓋資料移轉（包括電子郵件和檔案[）。](https://aka.ms/whatcanmigrate)<sup>2</sup>

使用者採用服務是由為您提供指導方針，以確保您的使用者瞭解合格服務，並可使用這些服務來推動商業價值的任務。 這項協助會與上架活動同時進行。
  
您可以在[這裡](https://aka.ms/whatistheprocess)找到 FastTrack 中心流程的特定資訊。 如需預訂角色和責任的細分，請複查[FastTrack 責任](https://aka.ms/whatdoesftcdo)以及您的[責任](https://aka.ms/whatdowedo)。
  
> <sup>1</sup>您必須從可接收 FastTrack 服務的[合格方案](https://aka.ms/whocanbenefit)清單中至少購買50個授權。
<br/><sup>2</sup>資料移轉服務可用於具有500或更多授權的 Office 365 承租人。
  
## <a name="data-migrations-performed-by-fasttrack"></a>FastTrack 所執行的資料移轉

選擇[FastTrack](https://fasttrack.microsoft.com/)遷移權益的客戶將需要授與管理其資料移轉的小組存取權。 在針對 Office 365 美國政府服務的客戶執行遷移之前，這些人員都是美國公民並進行下列背景檢查。
  
||||
|:-----|:-----|:-----|
|**背景遮罩** <br/> |**GCC** <br/> |**GCC High 和 DoD** <br/> |
|驗證 US 公民  <br/> |是  <br/> |是  <br/> |
|工作經歷檢查  <br/> |是  <br/> |是  <br/> |
|教育驗證  <br/> |是  <br/> |是  <br/> |
|社會安全號碼（SSN）搜尋  <br/> |是  <br/> |是  <br/> |
|刑事病史檢查（7年）  <br/> |是  <br/> |是  <br/> |
     
## <a name="office-365-us-government-and-azure-government-expressroute"></a>Office 365 US Government 和 Azure 政府版 Express Route

Office 365 美國政府客戶可以使用 Azure 政府 ExpressRoute 服務，以私下連線到支援的 Office 365 服務，而不是透過公用網際網路進行連接。
  
如需詳細資訊，例如支援的提供者、價格模型等等，請參閱[Azure ExpressRoute 資訊](https://go.microsoft.com/fwlink/?LinkID=798220&amp;clcid=0x409)。
  
如需 Office 365 Azure ExpressRoute 支援的詳細資訊，請參閱[azure ExpressRoute For Office 365](https://go.microsoft.com/fwlink/?LinkID=798216&amp;clcid=0x409)
  
## <a name="system-requirements"></a>系統需求

如需適用於 Office 365 US Government 方案的系統需求，請參閱 [office.com](https://go.microsoft.com/fwlink/?LinkID=626095&amp;clcid=0x409) 產品網站上的 [Office 的系統需求](https://go.microsoft.com/fwlink/?LinkID=509817&amp;clcid=0x409)。 
  
## <a name="security-amp-compliance-center"></a>安全性與 &amp; 合規性中心

如需安全性 &amp; 與合規性中心的詳細資訊，以及其他資訊與可用性的連結，請參閱[安全性 &amp; 合規性中心](../../office-365-platform-service-description/office-365-securitycompliance-center.md)。
  
## <a name="service-availability-for-each-plan"></a>每個方案可用的服務

Each Office 365 plan includes a number of individual services, such as Exchange Online and SharePoint Online. The following table shows the services that are available in each Office 365 US Government plan.
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**Office 365 服務** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F3** <br/> |
|網頁版 Office  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|企業用 Microsoft 365 應用程式  <br/> |否 <br/> |是 <br/> |是 <br/> |否  <br/> |
|Exchange Online  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Exchange Online Protection  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|SharePoint Online  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|商務用 OneDrive  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Skype for Business (Instant Messaging &amp; Presence)  <br/> |是<sup>1</sup> <br/> |是  <br/> |是  <br/> |是<sup>1</sup> <br/> |
| 語音電話系統、音訊會議  <br/> |否<sup>2</sup> <br/> |否<sup>2</sup> <br/> |是 <sup>5</sup> <br/> |否  <br/> |
|Power BI Pro  <br/> |否<sup>2</sup> <br/> |否<sup>2</sup> <br/> |是  <br/> |否<sup>2</sup> <br/> |
|Project Online  <br/> |否<sup>2</sup> <br/> |否<sup>2</sup> <br/> |否<sup>2</sup> <br/> |否<sup>2</sup> <br/> |
|Visio 網頁版  <br/> |否<sup>6</sup> <br/> |否<sup>6</sup> <br/> |否<sup>6</sup> <br/> |否<sup>6</sup> <br/> |
|Yammer Enterprise  <br/> |否<sup>4</sup> <br/> |否<sup>4</sup> <br/> |否<sup>4</sup> <br/> |否<sup>4</sup> <br/> |
   
> <sup>1</sup>商務用 Skype Basic 適用于所有客戶。 商務用 Skype 桌面用戶端是在本機安裝的應用程式，可針對包含 商務用 Skype Online 的 Office 365 方案，提供目前狀態、立即訊息和會議功能。 Microsoft 365 應用程式適用于企業、G3 及 G5 包含完整的 Skype 應用程式，其包含額外的功能，例如高級電話語音支援、封存及合規性功能。 必須為每個使用者指派商務用 Skype Online 授權。
<br/><sup>2</sup>不包含在內，但能以個別的附加元件形式購買。 Project Online 包含 Project Online 桌面用戶端做為訂閱的一部分。
<br/> 在 GCC 高或 DoD 方案<sup>中尚未提供</sup>，但即將推出。 
<br/><sup>4</sup> Yammer Enterprise 不是 OFFICE 365 美國政府的元件，但可免費提供給在 GCC 中為 Office 365 授權的每位使用者提供的獨立功能。 這項優惠目前僅限於以企業合約和企業訂閱協定購買 Office 365 GCC 的客戶。 在 GCC High 或 DoD 中無法使用 Yammer。
<br/><sup>5</sup>通話方案為附加元件。 
<br/><sup>6</sup>不含在內，但能以個別的附加元件形式購買。 Web 的 visio 包含 Visio 桌面應用程式作為訂閱的一部分。

## <a name="platform-features"></a>平台功能

下表列出可用於 Office 365 US Government 方案的平台功能和服務。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F3** <br/> |
|**Office 365 管理** <br/> |||||
|使用 Microsoft 365 admin center 管理 Office 365  <br/> |是<sup>16</sup> <br/> |是<sup>16</sup> <br/> |是  <br/> |是<sup>16</sup> <br/> |
|從 Office 365 管理核心服務設定  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|使用 Windows PowerShell 管理 Office 365  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|使用 Azure 資訊保護 來保護內容  <br/> |否<sup>1</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup>  <br/> |否<sup>1</sup> <br/> |
|**[Office 365 套件功能](../../office-365-platform-service-description/office-365-suite-features.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F3** <br/> |
|Microsoft Bookings  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |
|Microsoft 簡報電子郵件  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |
|Microsoft Power Automate  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|Microsoft Forms  <br/> |是 <br/> |是 <br/> |是<br/> |是</sup> <br/> |
|Microsoft Graph API  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Microsoft MyAnalytics  <br/> |否 <br/> |否 <br/> |是<sup>17</sup> <br/> |否 <br/> |
|Microsoft Planner  <br/> |是 <br/> |是 <br/> |是 <br/> |是 <br/> |
|Microsoft PowerApps  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|Microsoft StaffHub  <br/> |否 <br/> |否 <br/> |否 <br/> |否<br/> |
|Microsoft Stream  <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15，20</sup>  <br/> |
|Microsoft Sway  <br/> |否 <br/> |否 <br/> |否 <br/> |否 <br/> |
|Microsoft Teams  <br/> |是 <br/> |是 <br/> |是 <br/> |是 <br/> |
|Office Delve  <br/> |是<sup>17</sup> <br/> |是<sup>17</sup> <br/> |是  <br/> |是<sup>17</sup> <br/> |
|Office 365 群組  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[使用者帳戶管理](../../office-365-platform-service-description/user-account-management.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F3** <br/> |
|雲端身分識別  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|同盟身分識別 (單一登入)  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|多重要素驗證  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|電話係數驗證  <br/> |是<sup>9</sup> <br/> |是<sup>9</sup> <br/> |是  <br/> |是<sup>9</sup> <br/> |
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
|**[網域](../../office-365-platform-service-description/domains.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F3** <br/> |
|新增自訂的第 2 層網域，如 fourthcoffee.com  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|新增自訂的第 3 層網域，如 marketing.fourthcoffee.com  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|最多可新增 900 個自訂網域  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|自訂網域需要網域所有權驗證  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[服務健康狀況和持續性](../../office-365-platform-service-description/service-health-and-continuity.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F3** <br/> |
|可在 **[服務健康狀況]** 或 **[服務狀態]** 頁面上獲取狀態資訊  <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |
|可在 Microsoft 365 系統管理中心儀表板上獲取個別警示狀態  <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |
|**服務健康狀況** RSS 摘要  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[報告](../../office-365-platform-service-description/reports.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F3** <br/> |
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
|郵件排名最前面的相符 DLP 原則  <br/> |否  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |否 <br/> |
|依重要性分組顯示郵件符合 DLP 原則的數目  <br/> |否  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |否 <br/> |
|郵件的 DLP 原則比對、覆寫及誤判  <br/> |否  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |否 <br/> |
|郵件排名最前面的相符 DLP 規則  <br/> |否  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |否 <br/> |
|IM 和音訊工作階段  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|應用程式共用、Web 及電話撥入式會議  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|視訊、應用程式共用及檔案傳輸工作階段  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|IM 和音訊/視訊會議  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|可下載的郵件保護報告  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|使用的瀏覽器  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|使用的作業系統  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|使用 Microsoft 365 報表 web 服務建立您自己的報表  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|**[服務更新](../../office-365-platform-service-description/service-updates.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F3** <br/> |
|提供給所有客戶的定期更新  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|需要採取行動時，將通知傳送給「訊息中心」  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|Roadmap.office.com 的一些服務 更新  <br/> |無<sup>10、13</sup> <br/> |無<sup>10、13</sup> <br/> |無<sup>10、13</sup> <br/> |無<sup>10、13</sup> <br/> |
|開啟目標版本的選項  <br/> |是<sup>10</sup> <br/> |是<sup>10</sup> <br/> |是<sup>10</sup> <br/> |是<sup>10</sup> <br/> |
|**[說明與訓練](../../office-365-platform-service-description/help-and-training.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F3** <br/> |
|線上說明  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|社群  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|其他自助資源  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|自訂進度訓練  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[網路功能](../../office-365-platform-service-description/networking.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F3** <br/> |
|IPv4 和 IPv6 通訊協定  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**信任** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F3** <br/> |
|**[隱私權、安全性及透明性](../../office-365-platform-service-description/privacy-security-and-transparency.md)** <br/> |||||
|進階資料管理  <br/> |無<sup>12</sup> <br/> |無<sup>12</sup> <br/> |是 <br/> |無<sup>12</sup> <br/> |
|Cloud App Security  <br/> |無<sup>12、15、19</sup> <br/> |無<sup>12、15、19</sup> <br/> |是<sup>15、19</sup> <br/> |無<sup>12、15、19</sup> <br/> |
|進階威脅防護  <br/> |無<sup>12，18</sup> <br/> |無<sup>12，18</sup> <br/> |是<sup>18</sup>  <br/> |無<sup>12，18</sup> <br/> |
|客戶加密箱  <br/> |無<sup>12</sup> <br/> |無<sup>12</sup> <br/> |是 <br/> |無<sup>12</sup> <br/> |
|進階電子文件探索  <br/> |無<sup>12</sup> <br/> |無<sup>12</sup> <br/> |是  <br/> |無<sup>12</sup> <br/> |
|安全分數<sup>14</sup> <br/> |是<sup>9，15</sup> <br/> |是<sup>9</sup> <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |
|Office 郵件加密  <br/> |否  <br/> |是 <br/> |是 <br/> |否  <br/> |
|威脅情報  <br/> |無<sup>12</sup> <br/> |無<sup>12</sup> <br/> |是 <br/> |無<sup>12</sup> <br/> |
|**[合規性](https://docs.microsoft.com/microsoft-365/compliance/offering-home)** <br/> |||||
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
|**[BlackBerry](../../office-365-platform-service-description/blackberry.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F3** <br/> |
|使用 BlackBerry Internet Service (BIS)  <br/> |否<sup>2</sup> <br/> |否<sup>2</sup> <br/> |否<sup>2</sup> <br/> |否<sup>2</sup> <br/> |
|**[協力程式](../../office-365-platform-service-description/partners.md)** <br/> |||||
|針對正在使用指定計劃的客戶建立試用邀請和購買訂單  <br/> |無<sup>11</sup> <br/> |無<sup>11</sup> <br/> |無<sup>11</sup> <br/> |無<sup>11</sup> <br/> |
|提供委派管理  <br/> |無<sup>11</sup> <br/> |無<sup>11</sup> <br/> |無<sup>11</sup> <br/> |無<sup>11</sup> <br/> |
|**[服務等級協定](../../office-365-platform-service-description/service-level-agreement.md)** <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[產品使用權限](../../office-365-platform-service-description/product-use-rights.md)** <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
   
> <sup>1</sup> Azure 資訊保護未包含在內，但能以個別的附加元件形式購買，並且會啟用支援的資訊版權管理（IRM）功能。 部分 Azure 資訊保護功能需要訂閱 Microsoft 365 Apps for enterprise，不包含在 Office 365 政府版 G1 或 Office 365 政府 F3 中。 > 
<br/><sup>2</sup> 現有的 BBCS 和 BIS 客戶可以繼續使用服務。 不接受新的客戶。 
<br/><sup>3</sup> 如果您是使用目錄同步處理，則必須使用 Active Directory (非使用 Office 365 入口網站) 或使用 Windows PowerShell 的 Azure Active Directory 模組來刪除帳戶或變更密碼。 
<br/><sup>4</sup> 如果使用密碼同步化，使用者必須在本機 Active Directory 中變更其密碼。 
<br/><sup>5</sup> 若要了解如何為使用者設定自助式密碼管理原則，請參閱 [在 Azure AD 中管理密碼](https://azure.microsoft.com/documentation/articles/active-directory-manage-passwords/)。 
<br/><sup>6</sup> 您在 Office 365 只能有一個公用網站，除非您已從舊版 Office 365 升級。 在後者情況下，您有兩個公用網站，但只有一個能以自訂的網域名稱裝載。 如需就商務版訂閱來使用這兩個網站的詳細資訊，請參閱 [使用您的兩個 Office 365 公用網站](https://go.microsoft.com/fwlink/p/?LinkID=271589)。 如果您有不同的訂閱，請到 [Office 365 的公用網站說明](https://go.microsoft.com/fwlink/p/?LinkID=325009)深入了解公用網站。 
<br/><sup>7</sup> 若減少以折扣條件購買的基座，有可能需支付提前終止訂閱的費用。 這不適用於每月付款的訂閱。 
<br/><sup>8</sup>下列方案不支援來自 Microsoft 365 系統管理中心的授權基座變更： Office 365 政府版 G1，Office 365 政府版 G3，Office 365 政府 F3。 
<br/><sup>9</sup>在 GCC 高版本中尚未提供，但即將推出。
<br/><sup>10</sup> For Office 365 政府 G1、G3 及 F3、目標版本和 Office 365 For business 藍圖適用;不過，由於[相容性需求](https://www.microsoft.com/trust-center)，特定服務更新可能會有一些差異或延遲。
<br/><sup>11</sup>尚未提供于 Office 365 政府方案中，但即將推出。 
<br/><sup>12</sup>不包含在內，但可以在 GCC 中以個別的附加元件形式購買。 
<br/><sup>13</sup>不支援 Office 365 政府版服務。 
<br/><sup>14</sup>可供使用 [https://securescore.office.com](https://securescore.office.com) 。 需要系統管理員許可權。 如需詳細資訊，請參閱 [Office 365 安全分數簡介](https://docs.microsoft.com/microsoft-365/security/mtp/microsoft-secure-score)。
). 
<br/><sup>15</sup>在 DoD 環境中尚未提供，但即將推出。 
<br/><sup>16</sup>系統管理中心不包括 DOD 或 GCC 高環境中的流量分析。
<br/><sup>17</sup>不支援 GCC 高或 DoD 環境。
<br/><sup>18</sup>不 DoD 提供使用者和網域模擬的反網路釣魚和欺騙智慧。
<br/><sup>19</sup>環境中尚未提供，但即將推出。
<br/>僅適用于 Microsoft Stream 的<sup>20</sup>個消耗：無發佈或共用。 
  
## <a name="office-application-availability-and-enterprise-value"></a>Office 應用程式可用性和企業價值

下表顯示可用於 Office 365 US Government 方案的 Office 應用程式功能。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F3** <br/> |
|**Office 應用程式** <br/> |||||
|[Microsoft Word](../../office-applications-service-description/office-applications.md#microsoft-word)<sup>7</sup> <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Microsoft Excel](../../office-applications-service-description/office-applications.md#microsoft-excel)<sup>7</sup> <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Microsoft PowerPoint](../../office-applications-service-description/office-applications.md#microsoft-powerpoint)<sup>7</sup> <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Microsoft OneNote](../../office-applications-service-description/office-applications.md#microsoft-onenote)<sup>7</sup> <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Microsoft Outlook](../../office-applications-service-description/office-applications.md#microsoft-outlook)<sup>7</sup> <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|Microsoft Forms<sup>7</sup>| 是 <br/> | 是 <br/>| 是 <br/> | 否 <br/> |
|Microsoft 白板<sup>7</sup>| 否 <br/> | 是 <br/> | 是 <br/> | 否 <br/> |
|[Microsoft Publisher](../../office-applications-service-description/office-applications.md#microsoft-publisher) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Microsoft Access](../../office-applications-service-description/office-applications.md#microsoft-access) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[商務用 Skype](../../office-applications-service-description/office-applications.md#skype-for-business) <br/> |是<sup>3</sup> <br/> |是  <br/> |是  <br/> |是<sup>3</sup> <br/> |
|[Office 365 的 Mac 版 Office](https://support.office.com/article/General-requirements-for-Outlook-2016-for-Mac-A07A593D-B383-4906-A6C1-962D5543ED57) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Office Mobile for iPad/iPhone](../../office-applications-service-description/office-applications.md#office-mobile-for-ipadiphone) <br/> |是  <br/> |是<sup></sup> <br/> |是<sup></sup> <br/> |是  <br/> |
|[Office Mobile for Android](../../office-applications-service-description/office-applications.md#office-mobile-for-android) <br/> |是  <br/> |是<sup></sup> <br/> |是<sup></sup> <br/> |是  <br/> |
|[Office Mobile for Windows Phone](../../office-applications-service-description/office-applications.md#office-mobile-for-windows-phone) <br/> |是  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |是  <br/> |
|Office Mobile for Windows 10 tablets <br/> |是  <br/> |是<sup></sup> <br/> |是<sup></sup> <br/> |是  <br/> |
|適用于 iOS 和 Android<sup>5，4</sup>的 Outlook  <br/> |是 <br/> |是 <br/> |是 <br/> |是 <br/> |
|**企業價值** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F3** <br/> |
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
|使用 Azure 資訊保護的資訊版權管理  <br/> |否<sup>1</sup> <br/> |是<sup>6</sup> <br/> |是<sup>6</sup> <br/> |否<sup>1</sup> <br/> |
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
|共用電腦啟用  <br/> |否  <br/> |是 <br/> |是 <br/> |否  <br/> |
|支援對雲端架構檔案儲存進行封鎖  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|版本升級  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|大量啟用 (KMS/MAK)  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |
   
> <sup>1</sup> Azure 資訊保護未包含在內，但能以個別的附加元件形式購買，並且會啟用支援的資訊版權管理（IRM）功能。 部分 Azure 資訊保護功能需要訂閱 Microsoft 365 Apps for enterprise，不包含在 Office 365 政府版 G1 或 Office 365 政府 F3 中。 
<br/><sup>2</sup> WINDOWS SERVER AD RMS 是內部部署伺服器，必須個別採購並管理，以便啟用支援的 IRM 功能。 
<br/><sup>3</sup>商務用 Skype Basic 適用于所有客戶。 商務用 Skype 桌面用戶端是在本機安裝的應用程式，可針對包含 商務用 Skype Online 的 Office 365 方案，提供目前狀態、立即訊息和會議功能。 Microsoft 365 應用程式（適用于企業）和 Office 365 企業版 E3 包含完整的 Skype 應用程式，其包含額外的功能，例如高級電話語音支援、封存及合規性功能。 A Skype for Business Online license must be assigned for each user. For more information on Lync Basic features, see [Skype for Business Online client comparison tables](https://docs.microsoft.com/lyncserver/lync-server-2013-desktop-client-comparison-tables). 
<br/><sup>4</sup>在 GCC 高或 DoD 環境中尚未提供，但即將推出。
<br/><sup>5</sup>如需詳細資訊，請參閱[使用 Outlook For iOS 和 Android In 政府社區雲端](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud)。
<br/><sup>6</sup> Office 365 DoD 環境中尚未提供，但即將推出。
<br/><sup>7</sup>應用程式在政府群中完全可用，但目前無法使用的特定功能例外。 如需詳細資訊，請參閱[Office 應用程式功能可用性](#office-application-and-feature-availability-in-government-plans)。

## <a name="office-application-and-feature-availability-in-government-plans"></a>政府方案中的 Office 應用程式和功能可用性

政府雲彩中提供下列 Office 應用程式;不過，有些雲端式功能可能無法使用，如表格中所示。

|||||
|-----|-----|-----|-----|
|[**Microsoft Excel**](../../office-applications-service-description/office-applications.md#microsoft-excel)在政府雲彩中完全可用，但下列功能仍無法使用，但目前無法使用： | **GCC** <br/> | **GCC 高** <br/> | **國防部** <br/> |
|3D 內嵌動畫和3D 模型 | 否 <br/> | 否 <br/> | 否 <br/> |
|資料類型 | 否 <br/> | 否 <br/> | 否 <br/> |
|Flash 填滿 | 否 <br/> | 否 <br/> | 否 <br/> |
|創意（真知灼見服務） | 否 <br/> | 否 <br/> | 否 <br/> |
|改善與 PowerBI 的整合（自訂視覺效果、直接從 Excel 建立 PBI 圖表） | 否 <br/> | 否 <br/> | 否 <br/> |
|智慧數位墨水 | 否 <br/> | 否 <br/> | 否 <br/> |
|Office 365 群組 | 否 <br/> | 否 <br/> | 否 <br/> |
|PivotCharts 資料連線至 PivotTables | 否 <br/> | 否 <br/> | 否 <br/> |
|PowerPivot | 否 <br/> | 否 <br/> | 否 <br/> |
|發佈至 PowerBI | 否 <br/> | 否 <br/> | 否 <br/> |
|即時共同作業（目前狀態、一般共同作業、檔內聊天） | 否 <br/> | 否 <br/> | 否 <br/> |
|Shared with Me | 否 <br/> | 否 <br/> | 否 <br/> |
|智慧查閱 | 否 <br/> | 否 <br/> | 否 <br/> |
|圖表：旭日樹狀圖、瀑布、長條圖、地圖、時程表、漏斗 | 否 <br/> | 否 <br/> | 否 <br/> |
|版本歷程記錄 | 否 <br/> | 否 <br/> | 否 <br/> |
|[**Microsoft 表單**](https://support.office.com/article/5cbd407a-eef7-431e-8e3a-eb666eab4b4c)完全可用於政府雲彩，但無法使用下列功能： | **GCC** <br/> | **GCC 高** <br/> | **國防部** <br/> |
|電子郵件通知 | 否<sup>1</sup> <br/> | 否<sup>1</sup> <br/> | 否 <br/> | 
|插入圖片 | 否<sup>1</sup> <br/> | 否<sup>1</sup> <br/> | 否 <br/> |
|插入影片 | 否<sup>1</sup> <br/> | 否<sup>1</sup> <br/> | 否 <br/> |
|數學 | 否<sup>1</sup> <br/> | 否<sup>1</sup> <br/> | 否 <br/> |
|Office 整合 | 否<sup>1</sup> <br/> | 否<sup>1</sup> <br/> | 否 <br/> |
|最近的群組表單 | 否<sup>4</sup> <br/> | 是 <br/> | 是 <br/> |
|外部共用<sup>3</sup> | 是 <br/> | 否 <br/> | 否 <br/> |
|Forms Pro | 否 | 否 | 否 |
|[**Microsoft OneNote**](../../office-applications-service-description/office-applications.md#microsoft-onenote)完全可用於政府雲彩，但下列功能除外，但目前無法使用： | **GCC** <br/> | **GCC 高** <br/> | **國防部** <br/> |
|研究工具 | 否 <br/> | 否 <br/> | 否 <br/> |
|智慧數位墨水 | 否 <br/> | 否 <br/> | 否 <br/> |
|[**Microsoft Outlook**](../../office-applications-service-description/office-applications.md#microsoft-outlook)完全可用於政府雲彩，但下列功能仍無法使用，但現在無法使用： | **GCC** <br/> | **GCC 高** <br/> | **國防部** <br/> |
|Office 聲音（部分） | 否 <br/> | 否 <br/> | 否 <br/> |
|預設會停用動態資料交換（DDE） | 否 <br/> | 否 <br/> | 否 <br/> |
|聽寫 | 否<sup>1</sup> <br/> | 否<sup>1</sup> <br/> | 否<sup>1</sup> <br/> |
|[**Microsoft PowerPoint**](../../office-applications-service-description/office-applications.md#microsoft-powerpoint)完全可用於政府雲彩，但下列功能除外，但目前無法使用： | **GCC** <br/> | **GCC 高** <br/> | **國防部** <br/> |
|智慧查閱 | 否 <br/> | 否 <br/> | 否 <br/> |
|Office 聲音（部分） | 否 <br/> | 否 <br/> | 否 <br/> |
|3D 模型和3D 內嵌動畫 | 否 <br/> | 否 <br/> | 否 <br/> |
|圖表：地圖 | 否 <br/> | 否 <br/> | 否 <br/> |
|智慧數位墨水 | 否 <br/> | 否 <br/> | 否 <br/> |
|PowerPoint 中的 Live 字幕和副標題 | 否 <br/> | 否 <br/> | 否 <br/> |
|簡報者指導 | 否 <br/> | 否 <br/> | 否 <br/> |
|Shared with Me | 否 <br/> | 否 <br/> | 否 <br/> |
|與共享的商務用 Skype 整合 | 否 <br/> | 否 <br/> | 否 <br/> |
|版本歷程記錄 | 否 <br/> | 否 <br/> | 否 <br/> |
|Office 365 群組 | 否 <br/> | 否 <br/> | 否 <br/> |
|即時共同作業（目前狀態、一般共同作業、檔內聊天） | 否 <br/> | 否 <br/> | 否 <br/> |
|聽寫 | 否<sup>1</sup> <br/> | 否<sup>1</sup> <br/> | 否<sup>1</sup> <br/> |
|重複使用滑動片 | 否 <br/> | 否 <br/> | 否 <br/> |
|目前只有 Hub 用戶端（而不是在桌面上）提供政府群中的**Microsoft 白板**。 | **GCC**<sup>2</sup> <br/> | **GCC 高**<sup>2</sup> <br/> | **DOD**<sup>2</sup> <br/> |
|插入粘滯便箋、文字和圖像 | 是<sup>2</sup> <br/>| 是<sup>2</sup> <br/>| 是<sup>2</sup> <br/>|
|手寫的圖案和墨蹟至表格 | 是<sup>2</sup> <br/>| 是<sup>2</sup> <br/>| 是<sup>2</sup> <br/>|
|筆跡 beautification | 是<sup>2</sup> <br/>| 是<sup>2</sup> <br/>| 是<sup>2</sup> <br/>|
|將圖像轉換成筆跡 | 是<sup>2</sup> <br/>| 是<sup>2</sup> <br/>| 是<sup>2</sup> <br/>|
|協助工具檢查程式 | 是<sup>2</sup> <br/>| 是<sup>2</sup> <br/>| 是<sup>2</sup> <br/>|
|動態範本（看板、SWOT 等等） | 否 <br/> | 否 <br/> | 否 <br/> |
|即時合作 | 否 <br/> | 否 <br/> | 否 <br/> |
|即時目前狀態 | 否 <br/> | 否 <br/> | 否 <br/> |
|內容的反應 | 否 <br/> | 否 <br/> | 否 <br/> |
|白板的板圖庫（包括與您共用） | 否 <br/> | 否 <br/> | 否 <br/> |
|[**Microsoft Word**](../../office-applications-service-description/office-applications.md#microsoft-word)完全可用於政府雲彩，但下列功能仍無法使用，但目前無法使用： | **GCC** <br/> | **GCC 高** <br/> | **國防部** <br/> |
|智慧查閱 | 否 <br/> | 否 <br/> | 否 <br/> |
|研究工具 | 否 <br/> | 否 <br/> | 否 <br/> |
|Office 聲音  | 否 <br/> | 否 <br/> | 否 <br/> |
|3D 模型 | 否 <br/> | 否 <br/> | 否 <br/> |
|3D 嵌入動畫  | 否 <br/> | 否 <br/> | 否 <br/> |
|點選  | 否 <br/> | 否 <br/> | 否 <br/> |
|簡歷小幫手 | 否 <br/> | 否 <br/> | 否 <br/> |
|地圖圖表 | 否 <br/> | 否 <br/> | 否 <br/> |
|智慧數位墨水 | 否 <br/> | 否 <br/> | 否 <br/> |
|Shared with Me | 否 <br/> | 否 <br/> | 否 <br/> |
|Translation | 否 <br/> | 否 <br/> | 否 <br/> |
|與共享的商務用 Skype 整合 | 否 <br/> | 否 <br/> | 否 <br/> |
|版本歷程記錄 | 否 <br/> | 否 <br/> | 否 <br/> |
|Office 365 群組 | 否 <br/> | 否 <br/> | 否 <br/> |
|與共同作者的內容聊天：與檔內的共同撰寫人員聊天 | 否 <br/> | 否 <br/> | 否 <br/> |
|聽寫 | 否<sup>1</sup> <br/> | 否<sup>1</sup> <br/> | 否<sup>1</sup> <br/> |

><sup>1</sup>可用性即將推出。
<br/><sup>2</sup>在本機 Surface Hub 上的可用性（未登入）。
<br/><sup>3</sup>可供 GCC 環境使用外部共用。 深入瞭解如何[關閉或開啟組織的 Microsoft 表單](https://support.office.com/article/cc52287a-4550-464d-9a1b-457bf9df2240#PickTab=Configure)。 已停用 GCC 高和 DOD 環境的外部共用;您組織內的使用者可能會執行下列動作：完成表單並提交回應、[複製表單並將表單共用做為範本](https://support.office.com/article/82ea9d8a-260a-47a0-afdb-497f3d746e3f)、[共同撰寫表單或在表單上共同](https://support.office.com/article/d5bb5cf0-8401-4c15-bb8c-8e108cd7e69b)作業，以及[存取表單結果](https://support.office.com/article/02859424-341d-406f-b32a-9a0fbaf357af)。
<br/><sup>4</sup>已停用 GCC 環境的最近組表單功能。 不過，使用者仍然可以透過選取 [群組表單] 索引標籤上的特定群組，存取群組表單。