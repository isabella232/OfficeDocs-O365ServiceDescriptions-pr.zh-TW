---
title: Office 365 US Government
ms.author: danarl
author: danarl
manager: dianap
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 3f482abc-993f-41bf-8754-0f489a7e4861
description: 回應美國公共部門特殊且不斷變化需求，Microsoft 已建立 Office 365 US Government 計劃 （或 Office 365 政府版）。 本文提供 Office 365 政府美國環境特有的功能的概觀。
ms.openlocfilehash: 7fdf83fc7cd4ededf28826861ef0202aca6185bf
ms.sourcegitcommit: 66e0fa8f265fe5cdb0d94c340fef5cb5431fc600
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 01/18/2020
ms.locfileid: "41233356"
---
# <a name="office-365-us-government"></a>Office 365 US Government

回應美國公共部門特殊且不斷變化需求，Microsoft 已建立 Office 365 US Government 計劃 （或 Office 365 政府版）。 本節提供 Office 365 政府美國環境特有的功能的概觀。 我們建議您先閱讀本補充章節配合[Office 365 服務說明](../../office-365-service-descriptions-technet-library.md)。
  
## <a name="how-to-use-this-service-description"></a>如何使用此服務描述

Office 365 US Government 服務描述被設計來做為一般的 Office 365 服務描述重疊。 它會定義唯一的承諾和差異相較於 Office 365 企業版供應項目。
  
## <a name="about-office-365-us-government-environments"></a>關於 Office 365 US Government 環境

Office 365 US Government 方案為每月訂閱，並且可授權給不限數量的使用者。 
  
- **Office 365 GCC**環境可提供遵循美國聯邦雲端服務需求的包括 FedRAMP 中度和司法正義與聯邦稅務資訊系統 （CJI 和 FTI 資料類型） 的需求。 
    
- **Office 365 GCC High 和 DoD**環境傳送合規性部門的防禦安全性需求指南、 防禦聯邦擷取法規補充 (DFARS)，與國際流量中武器法規 (ITAR)。 
    
除了具有 Office 365 的功能外，使用 Office 365 US Government 的組織還可從以下專屬於 Office 365 US Government 的功能獲得好處：
  
- 組織的客戶內容和 Microsoft 的商業 Office 365 服務中的客戶內容會以邏輯方式區隔。
    
- 組織的客戶內容儲存於美國境內。
    
- 只有經過篩選的 Microsoft 人員可以存取組織的客戶內容。
    
- Office 365 US Government 符合美國公共部門客戶所要求的認證和資格鑑定。
  
## <a name="customer-eligibility"></a>客戶資格

Office 365 US Government 的可 （1） 美國聯邦，狀態，本機、 部落，且就政府實體和處理受限於政府法規及需求的資料，其中用於的 Office 365 US Government （2） 其他實體適用於符合這些需求，受限於驗證資格。 驗證資格 microsoft 將會包含確認處理受到國際流量中武器法規 (ITAR)，受限於 FBI 司法正義資訊服務 (CJIS) 原則，或其他法律強制執行資料的資料政府管制或受控制的資料。 驗證可能需要註冊美國部門的狀態證明 ITAR 資料或支持所處理的資料的特定需求的政府實體。 Office 365 DoD 環境適用於美國國防部獨佔使用。
  
資格準則都是一致跨 Office 365 政府版方案，Microsoft 將僅同意 GCC High 環境 DFARS 和 ITAR 合約語言]。
  
若有關於 Office 365 US Government 資格問題的機構應諮詢其客戶團隊。
  
在更新客戶的 Office 365 US Government 合約時，必須重新驗證資格。
  
## <a name="customer-content-located-within-the-united-states"></a>美國境內的客戶內容

Office 365 US Government 服務是由美國境內的實體資料中心所提供。下列客戶內容會靜止存放在僅位於美國境內的實體資料中心裡： 
  
- Exchange Online 信箱內容 （電子郵件內文、 行事曆項目和電子郵件附件的內容）
    
- SharePoint Online 站台內容和儲存在該站台內的檔案
    
- 商務用 Skype 保存的對話、 上傳的文件和白板工作階段

- Microsoft Teams 常設聊天室執行緒
    
> [!NOTE]
> 一般來說，商務用 Skype 不會儲存客戶內容，但是如果有儲存的話，將會儲存在美國境內的資料中心。 
  
2.0 和設定原則，以協助確保您的使用者如果您的使用者是位在美國境內的網頁 （先前稱為 Office Web Apps） 使用 Office 時，或採用的 Active Directory Federation Services (AD FS) 使用連線至透過單一 si 服務1&sd 入暫時快取 Office 中網頁的任何客戶內容會位於美國境內的
  
## <a name="office-365-us-government-and-third-party-services"></a>Office 365 US Government 與協力廠商服務

Office 365 可將協力廠商的應用程式整合至 SharePoint Online 站台、商務用 Skype、Office 365 ProPlus 中的 Office 應用程式 (如 Word、Excel、PowerPoint 和 Outlook) 以及 Outlook Web App。此外，Office 365 還支援與服務提供者協力廠商整合。這些協力廠商應用程式和服務可能會在 Office 365 基礎結構外的協力廠商系統上儲存、傳輸和處理組織的客戶資料，因此不在 Office 365 規範和資料保護承諾的保證範圍內。建議您檢閱協力廠商提供的隱私權和規範聲明，來評估適合組織的服務使用方式。
  
## <a name="restricted-data-access-by-administrators"></a>受限制的系統管理員資料存取

存取 Office 365 US Government 客戶內容 Microsoft 系統管理員會受限於雲端過濾的人員。 檢測層級的詳細資訊，請參閱每個個別的環境 （GCC 或 GCC 高和 DoD） 的服務描述頁面。 

  
## <a name="fasttrack-center-onboarding-assistance"></a>FastTrack Center 上架協助

Office 365<sup>1</sup>FastTrack Center 權益，您可以使用遠端與 FastTrack 專家以取得 Office 365 環境準備好使用並計劃導入和組織內的使用狀況。 FastTrack 程序提供上架和使用者採用服務。 
  
上架包含︰
  
- 核心上架-這些是視租用戶組態和與 Azure Active Directory (Azure AD) 整合所需的工作。 核心上架也能成為將其他合格之服務上架的基準。
    
- 服務上架和移轉-服務上架工作會啟用租用戶中的案例。 [資料移轉](https://aka.ms/whatcanmigrate)中涵蓋資料移轉 （包括電子郵件和檔案）。<sup>2</sup>

使用者採用服務是由提供的指引，以確保您的使用者知道合格的服務，可以利用這些磁碟機商業價值的工作所組成。 上架活動的同時，就會發生此尋求協助。
  
FastTrack Center 程序上的特定資訊，請參閱[以下](https://aka.ms/whatistheprocess)。 如參與角色和責任的明細，請參閱[FastTrack 責任](https://aka.ms/whatdoesftcdo)，以及[您的責任](https://aka.ms/whatdowedo)。
  
> <sup>1</sup>您必須購買至少 50 個授權從收到 FastTrack 服務[合格方案](https://aka.ms/whocanbenefit)清單。
<br/><sup>2</sup>資料移轉服務可用於 Office 365 租用戶 500 個以上的授權。
  
## <a name="data-migrations-performed-by-fasttrack"></a>FastTrack 所執行的資料移轉

選擇 [ [FastTrack](https://fasttrack.microsoft.com/)移轉優惠的客戶必須授與存取管理其資料移轉小組。 這些人員美國公民且經過下列背景檢查前的客戶的 Office 365 US Government 服務執行移轉。
  
||||
|:-----|:-----|:-----|
|**背景檢測** <br/> |**GCC** <br/> |**GCC High 和 DoD** <br/> |
|美國公民權  <br/> |是  <br/> |是  <br/> |
|工作經驗檢查  <br/> |是  <br/> |是  <br/> |
|教育驗證  <br/> |是  <br/> |是  <br/> |
|社會安全號碼 (SSN) 搜尋  <br/> |是  <br/> |是  <br/> |
|刑事案件記錄檢查 （7 年）  <br/> |是  <br/> |是  <br/> |
     
## <a name="office-365-us-government-and-azure-government-expressroute"></a>Office 365 US Government 和 Azure 政府版 Express Route

Office 365 US Government 客戶可以使用 Azure 政府版 ExpressRoute 服務私下連線到支援的 Office 365 服務，而不透過公用的網際網路連線。
  
如需詳細資訊，例如支援提供者、 價格模型及詳細資訊，請檢閱[Azure ExpressRoute 資訊](https://go.microsoft.com/fwlink/?LinkID=798220&amp;clcid=0x409)。
  
如需 Office 365 Azure ExpressRoute 支援的詳細資訊，請參閱[Azure ExpressRoute for Office 365](https://go.microsoft.com/fwlink/?LinkID=798216&amp;clcid=0x409)
  
## <a name="system-requirements"></a>系統需求

如需適用於 Office 365 US Government 方案的系統需求，請參閱 [office.com](https://go.microsoft.com/fwlink/?LinkID=626095&amp;clcid=0x409) 產品網站上的 [Office 的系統需求](https://go.microsoft.com/fwlink/?LinkID=509817&amp;clcid=0x409)。 
  
## <a name="security-amp-compliance-center"></a>安全性&amp;合規性中心

如需安全性資訊&amp;規範中心和連結的其他資訊和可用性，請參閱[Office 365 安全性&amp;合規性中心](../../office-365-platform-service-description/office-365-securitycompliance-center.md)。
  
## <a name="service-availability-for-each-plan"></a>每個方案可用的服務

每個 Office 365 方案皆包含一些個別服務，例如 Exchange Online 和 SharePoint Online。下表顯示每項 Office 365 US Government 方案中可用的服務。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**Office 365 服務** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府版 F1** <br/> |
|網頁版 Office  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Office 365 專業增強版  <br/> |否 <br/> |是 <br/> |是 <br/> |否  <br/> |
|Exchange Online  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Exchange Online Protection  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|SharePoint Online  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|商務用 OneDrive  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Skype for Business (Instant Messaging &amp; Presence)  <br/> |是<sup>1</sup> <br/> |是  <br/> |是  <br/> |是<sup>1</sup> <br/> |
| 語音-電話系統、 音訊會議  <br/> |否<sup>2</sup> <br/> |否<sup>2</sup> <br/> |是 <sup>5</sup> <br/> |否  <br/> |
|Power BI Pro  <br/> |否<sup>2</sup> <br/> |否<sup>2</sup> <br/> |是  <br/> |否<sup>2</sup> <br/> |
|Project Online  <br/> |否<sup>2</sup> <br/> |否<sup>2</sup> <br/> |否<sup>2</sup> <br/> |否<sup>2</sup> <br/> |
|Visio 網頁版  <br/> |否<sup>6</sup> <br/> |否<sup>6</sup> <br/> |否<sup>6</sup> <br/> |否<sup>6</sup> <br/> |
|Yammer Enterprise  <br/> |否<sup>4</sup> <br/> |否<sup>4</sup> <br/> |否<sup>4</sup> <br/> |否<sup>4</sup> <br/> |
   
> <sup>1</sup>商務用 Skype 商務基本是供所有客戶使用。 商務用 Skype 桌面用戶端是在本機安裝的應用程式，可針對包含 商務用 Skype Online 的 Office 365 方案，提供目前狀態、立即訊息和會議功能。 Office 365 專業增強版、 G3 和 G5 包含完整的 Skype 應用程式，其包含額外的功能，例如進階電話語音支援、 封存和規範功能。 必須為每個使用者指派商務用 Skype Online 授權。
<br/><sup>2</sup>不包含在內，但是能以個別的附加元件形式購買。 Project Online 包含 Project Online 桌面用戶端訂閱的一部分。
<br/> <sup>3</sup>尚未不適用於 GCC High 或 DoD 計劃，但即將推出。 
<br/><sup>4</sup> yammer Enterprise 不是 Office 365 美國政府的元件，但可能在為每位使用者的獨立優惠授權 office 365 中 GCC 免費取得。 此提供的功能是目前僅限於購買 Office 365 GCC Enterprise 合約及 Enterprise 訂閱合約的客戶。 GCC 高或 DoD 中，不提供 yammer。
<br/><sup>5</sup>通話方案是附加元件。 
<br/><sup>6</sup>不包含在內，但是能以個別的附加元件形式購買。 Visio 網頁包含 Visio 桌面應用程式做為訂閱的一部分。

## <a name="platform-features"></a>平台功能

下表列出可用於 Office 365 US Government 方案的平台功能和服務。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府版 F1** <br/> |
|**Office 365 管理** <br/> |||||
|使用 Microsoft 365 系統管理中心來管理 Office 365  <br/> |是<sup>16</sup> <br/> |是<sup>16</sup> <br/> |是  <br/> |是<sup>16</sup> <br/> |
|從 Office 365 管理核心服務設定  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|使用 Windows PowerShell 管理 Office 365  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|使用 Azure 資訊保護 來保護內容  <br/> |否<sup>1</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup>  <br/> |否<sup>1</sup> <br/> |
|**[Office 365 套件功能](../../office-365-platform-service-description/office-365-suite-features.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府版 F1** <br/> |
|Microsoft Bookings  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |
|Microsoft 簡報電子郵件  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |
|Microsoft Power 自動化  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|Microsoft Forms  <br/> |是 <br/> |是 <br/> |是<br/> |是</sup> <br/> |
|Microsoft Graph API  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Microsoft MyAnalytics  <br/> |否 <br/> |否 <br/> |Yes<sup>17</sup> <br/> |否 <br/> |
|Microsoft Planner  <br/> |是 <br/> |是 <br/> |是 <br/> |是 <br/> |
|Microsoft PowerApps  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|Microsoft StaffHub  <br/> |否 <br/> |否 <br/> |否 <br/> |否<br/> |
|Microsoft Stream  <br/> |是<sup>9、 15</sup> <br/> |是<sup>9、 15</sup> <br/> |是<sup>9、 15</sup> <br/> |否  <br/> |
|Microsoft Sway  <br/> |否 <br/> |否 <br/> |否 <br/> |否 <br/> |
|Microsoft Teams  <br/> |是 <br/> |是 <br/> |是 <br/> |是 <br/> |
|Office Delve  <br/> |Yes<sup>17</sup> <br/> |Yes<sup>17</sup> <br/> |是  <br/> |Yes<sup>17</sup> <br/> |
|Office 365 群組  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[使用者帳戶管理](../../office-365-platform-service-description/user-account-management.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府版 F1** <br/> |
|雲端身分識別  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|同盟身分識別 (單一登入)  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|多重要素驗證  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|電話要素驗證  <br/> |是<sup>9</sup> <br/> |是<sup>9</sup> <br/> |是  <br/> |是<sup>9</sup> <br/> |
|Office 365 桌面設定  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|以 Office 365 管理使用者  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|使用.csv 檔案大量上傳  <br/> |是<sup>9</sup> <br/> |是<sup>9</sup> <br/> |是  <br/> |是<sup>9</sup> <br/> |
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
|**[網域](../../office-365-platform-service-description/domains.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府版 F1** <br/> |
|新增自訂的第 2 層網域，如 fourthcoffee.com  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|新增自訂的第 3 層網域，如 marketing.fourthcoffee.com  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|最多可新增 900 個自訂網域  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|自訂網域需要網域所有權驗證  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[服務健康狀況和持續性](../../office-365-platform-service-description/service-health-and-continuity.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府版 F1** <br/> |
|可在 **[服務健康狀況]** 或 **[服務狀態]** 頁面上獲取狀態資訊  <br/> |是<sup>9、 15</sup> <br/> |是<sup>9、 15</sup> <br/> |是<sup>9、 15</sup> <br/> |是<sup>9、 15</sup> <br/> |
|可在 Microsoft 365 系統管理中心儀表板上獲取個別警示狀態  <br/> |是<sup>9、 15</sup> <br/> |是<sup>9、 15</sup> <br/> |是<sup>9、 15</sup> <br/> |是<sup>9、 15</sup> <br/> |
|**服務健康狀況** RSS 摘要  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[報告](../../office-365-platform-service-description/reports.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府版 F1** <br/> |
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
|使用 Office 365 回報網路服務來建立自己的報表  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|**[服務更新](../../office-365-platform-service-description/service-updates.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府版 F1** <br/> |
|提供給所有客戶的定期更新  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|需要採取行動時，將通知傳送給「訊息中心」  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|Roadmap.office.com 的一些服務 更新  <br/> |沒有<sup>10、 13</sup> <br/> |沒有<sup>10、 13</sup> <br/> |沒有<sup>10、 13</sup> <br/> |沒有<sup>10、 13</sup> <br/> |
|若要開啟已設定目標發行選項  <br/> |是<sup>10</sup> <br/> |是<sup>10</sup> <br/> |是<sup>10</sup> <br/> |是<sup>10</sup> <br/> |
|**[說明與訓練](../../office-365-platform-service-description/help-and-training.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府版 F1** <br/> |
|線上說明  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|社群  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|其他自助資源  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|自訂進度訓練  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[網路功能](../../office-365-platform-service-description/networking.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府版 F1** <br/> |
|IPv4 和 IPv6 通訊協定  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**信任** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府版 F1** <br/> |
|**[隱私權、安全性及透明性](../../office-365-platform-service-description/privacy-security-and-transparency.md)** <br/> |||||
|進階資料管理  <br/> |沒有<sup>12</sup> <br/> |沒有<sup>12</sup> <br/> |是 <br/> |沒有<sup>12</sup> <br/> |
|Cloud App Security  <br/> |沒有<sup>12、 15、 19</sup> <br/> |沒有<sup>12、 15、 19</sup> <br/> |是<sup>15、 19</sup> <br/> |沒有<sup>12、 15、 19</sup> <br/> |
|進階威脅防護  <br/> |沒有<sup>12、 18</sup> <br/> |沒有<sup>12、 18</sup> <br/> |是<sup>18</sup>  <br/> |沒有<sup>12、 18</sup> <br/> |
|客戶加密箱  <br/> |沒有<sup>12</sup> <br/> |沒有<sup>12</sup> <br/> |是 <br/> |沒有<sup>12</sup> <br/> |
|Office 365 進階電子文件探索  <br/> |沒有<sup>12</sup> <br/> |沒有<sup>12</sup> <br/> |是  <br/> |沒有<sup>12</sup> <br/> |
|安全分數<sup>14</sup> <br/> |是<sup>9、 15</sup> <br/> |是<sup>9</sup> <br/> |是<sup>9、 15</sup> <br/> |是<sup>9、 15</sup> <br/> |
|Office 郵件加密  <br/> |否  <br/> |是 <br/> |是 <br/> |否  <br/> |
|威脅情報  <br/> |沒有<sup>12</sup> <br/> |沒有<sup>12</sup> <br/> |是 <br/> |沒有<sup>12</sup> <br/> |
|**[合規性](../../office-365-platform-service-description/compliance-servicedesc.md)** <br/> |||||
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
|**[BlackBerry](../../office-365-platform-service-description/blackberry.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府版 F1** <br/> |
|使用 BlackBerry Internet Service (BIS)  <br/> |否<sup>2</sup> <br/> |否<sup>2</sup> <br/> |否<sup>2</sup> <br/> |否<sup>2</sup> <br/> |
|**[協力程式](../../office-365-platform-service-description/partners.md)** <br/> |||||
|針對正在使用指定計劃的客戶建立試用邀請和購買訂單  <br/> |沒有<sup>11</sup> <br/> |沒有<sup>11</sup> <br/> |沒有<sup>11</sup> <br/> |沒有<sup>11</sup> <br/> |
|提供委派管理  <br/> |沒有<sup>11</sup> <br/> |沒有<sup>11</sup> <br/> |沒有<sup>11</sup> <br/> |沒有<sup>11</sup> <br/> |
|**[服務等級協定](../../office-365-platform-service-description/service-level-agreement.md)** <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[產品使用權限](../../office-365-platform-service-description/product-use-rights.md)** <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
   
> <sup>1</sup> azure 資訊保護未包含在內，但能以個別的附加元件形式購買，並將會啟用支援的資訊版權管理 (IRM) 功能。 部分 Azure 資訊保護功能需要訂閱 Office 365 專業增強版，而不含 Office 365 政府版 G1 或 Office 365 政府版 F1。 > 
<br/><sup>2</sup> 現有的 BBCS 和 BIS 客戶可以繼續使用服務。 不接受新的客戶。 
<br/><sup>3</sup> 如果您是使用目錄同步處理，則必須使用 Active Directory (非使用 Office 365 入口網站) 或使用 Windows PowerShell 的 Azure Active Directory 模組來刪除帳戶或變更密碼。 
<br/><sup>4</sup> 如果使用密碼同步化，使用者必須在本機 Active Directory 中變更其密碼。 
<br/><sup>5</sup> 若要了解如何為使用者設定自助式密碼管理原則，請參閱 [在 Azure AD 中管理密碼](https://azure.microsoft.com/documentation/articles/active-directory-manage-passwords/)。 
<br/><sup>6</sup> 您在 Office 365 只能有一個公用網站，除非您已從舊版 Office 365 升級。 在後者情況下，您有兩個公用網站，但只有一個能以自訂的網域名稱裝載。 如需就商務版訂閱來使用這兩個網站的詳細資訊，請參閱 [使用您的兩個 Office 365 公用網站](https://go.microsoft.com/fwlink/p/?LinkID=271589)。 如果您有不同的訂閱，請到 [Office 365 的公用網站說明](https://go.microsoft.com/fwlink/p/?LinkID=325009)深入了解公用網站。 
<br/><sup>7</sup> 若減少以折扣條件購買的基座，有可能需支付提前終止訂閱的費用。 這不適用於每月付款的訂閱。 
<br/><sup>8</sup>下列方案不支援從 Microsoft 365 系統管理中心的授權基座變更： Office 365 政府版 G1、 Office 365 政府版 G3、 Office 365 政府版 F1。 
<br/><sup>9</sup>尚無法使用 GCC 高，但即將推出。
<br/><sup>10</sup>的 Office 365 政府版 G1、 G3 和 F1、 已設定目標發行和適用於商務藍圖的 Office 365 套用;不過，可能有一些差異或延遲的特定服務更新，因為[符合性需求](https://www.microsoft.com/trust-center)。
<br/><sup>11</sup>尚無法使用 Office 365 政府版方案，但即將推出。 
<br/><sup>12</sup>不包含在內，但是能以 GCC 中的個別附加元件形式購買。 
<br/><sup>13</sup>不支援 Office 365 政府版方案。 
<br/><sup>14</sup>可在[https://securescore.office.com](https://securescore.office.com)。 需要系統管理員權限。 如需詳細資訊，請參閱 [Office 365 安全分數簡介](https://go.microsoft.com/fwlink/?linkid=836894)。 
<br/><sup>15</sup>尚無法使用 DoD 環境中，但即將推出。 
<br/><sup>16</sup>系統管理中心不包含使用情況分析中的 DoD 或 GCC High 環境。
<br/>GCC 高] 或 [DoD 環境不支援<sup>17</sup> 。
<br/><sup>18</sup>反網路釣魚的使用者和網域模擬和詐騙智慧尚無法使用 GCC 高和 DoD 中。
<br/><sup>19</sup>尚無法使用 GCC 環境中，但即將推出。
  
## <a name="office-application-availability-and-enterprise-value"></a>Office 應用程式的可用性和企業值

下表顯示可用於 Office 365 US Government 方案的 Office 應用程式功能。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府版 F1** <br/> |
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
|Outlook for iOS 和 Android<sup>5、 4</sup>  <br/> |是 <br/> |是 <br/> |是 <br/> |是 <br/> |
|**企業價值** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府版 F1** <br/> |
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
   
> <sup>1</sup> azure 資訊保護未包含在內，但能以個別的附加元件形式購買，並將會啟用支援的資訊版權管理 (IRM) 功能。 部分 Azure 資訊保護功能需要訂閱 Office 365 專業增強版，而不含 Office 365 政府版 G1 或 Office 365 政府版 F1。 
<br/><sup>2</sup> Windows Server AD RMS 是內部部署伺服器，必須是採購並管理，才能啟用支援的 IRM 功能。 
<br/><sup>3</sup>商務基本 Skype 是供所有客戶使用。 商務用 Skype 桌面用戶端是在本機安裝的應用程式，可針對包含 商務用 Skype Online 的 Office 365 方案，提供目前狀態、立即訊息和會議功能。 Office 365 專業增強版和 Office 365 Enterprise E3 包含完整的 Skype 應用程式，其包含額外的功能，例如進階電話語音支援、 封存和規範功能。 A Skype for Business Online license must be assigned for each user. For more information on Lync Basic features, see [Skype for Business Online client comparison tables](https://docs.microsoft.com/lyncserver/lync-server-2013-desktop-client-comparison-tables). 
<br/><sup>4</sup>尚未提供，不在 GCC High 或 DoD 環境中，但即將推出。
<br/><sup>5</sup>如需詳細資訊，請參閱[使用 Outlook for iOS 和 Android 中 「 政府社群雲端](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud)。
<br/><sup>6</sup>尚未不適用於 Office 365 DoD 環境中，但即將推出。
<br/><sup>7</sup>應用程式可完整使用政府雲中，但無法在此階段的特定功能。 如需詳細資訊，請參閱[Office 應用程式的功能可用性](#office-application-and-feature-availability-in-government-plans)。

## <a name="office-application-and-feature-availability-in-government-plans"></a>政府版計劃中的 office 應用程式和功能可用性

下列 Office 應用程式中可用的政府定域機組中;不過，某些雲端架構的功能可能無法目前，表格所示。

|||||
|-----|-----|-----|-----|
|政府雲中以外的下列功能，此時無法使用， [**Microsoft Excel**](../../office-applications-service-description/office-applications.md#microsoft-excel)會完全提供： | **GCC** <br/> | **GCC 高** <br/> | **DOD** <br/> |
|3D 內嵌動畫和 3D 模型 | 否 <br/> | 否 <br/> | 否 <br/> |
|資料類型 | 否 <br/> | 否 <br/> | 否 <br/> |
|快速填入 | 否 <br/> | 否 <br/> | 否 <br/> |
|想法 （深入了解服務） | 否 <br/> | 否 <br/> | 否 <br/> |
|更完美地的整合使用 PowerBI （自訂視覺效果，建立 PBI 圖表直接從 Excel） | 否 <br/> | 否 <br/> | 否 <br/> |
|智慧型數位筆跡 | 否 <br/> | 否 <br/> | 否 <br/> |
|Office 365 群組 | 否 <br/> | 否 <br/> | 否 <br/> |
|連線至樞紐分析表的樞紐分析圖資料 | 否 <br/> | 否 <br/> | 否 <br/> |
|PowerPivot | 否 <br/> | 否 <br/> | 否 <br/> |
|發佈至 PowerBI | 否 <br/> | 否 <br/> | 否 <br/> |
|即時共同作業平台服務、 一般共同撰寫 （中的文件聊天室） | 否 <br/> | 否 <br/> | 否 <br/> |
|Shared with Me | 否 <br/> | 否 <br/> | 否 <br/> |
|智慧查閱 | 否 <br/> | 否 <br/> | 否 <br/> |
|圖表： 烈日樹狀圖、 瀑布圖、 長條圖、 對應、 時間表、 漏斗 | 否 <br/> | 否 <br/> | 否 <br/> |
|版本歷程記錄 | 否 <br/> | 否 <br/> | 否 <br/> |
|[**Microsoft Forms**](https://support.office.com/article/5cbd407a-eef7-431e-8e3a-eb666eab4b4c)是完全可用以外的下列功能，此時無法使用的政府定域機組中： | **GCC** <br/> | **GCC 高** <br/> | **DOD**<sup>3</sup> <br/> |
|電子郵件通知 | 否<sup>1</sup> <br/> | 否<sup>1</sup> <br/> | 否 <br/> | 
|插入圖片 | 否<sup>1</sup> <br/> | 否<sup>1</sup> <br/> | 否 <br/> |
|插入影片 | 否<sup>1</sup> <br/> | 否<sup>1</sup> <br/> | 否 <br/> |
|數學 | 否<sup>1</sup> <br/> | 否<sup>1</sup> <br/> | 否 <br/> |
|Office 整合 | 否<sup>1</sup> <br/> | 否<sup>1</sup> <br/> | 否 <br/> |
|最新的群組表單 | 是 <br/> | 是 <br/> | 否 <br/> |
|外部共用<sup>4</sup> | 是 <br/> | 否 <br/> | 否 <br/> |
|形成 Pro | 否 | 否 | 否 |
|[**Microsoft OneNote**](../../office-applications-service-description/office-applications.md#microsoft-onenote)是完全可用以外的下列功能，此時無法使用的政府定域機組中： | **GCC** <br/> | **GCC 高** <br/> | **DOD** <br/> |
|研究工具 | 否 <br/> | 否 <br/> | 否 <br/> |
|智慧型數位筆跡 | 否 <br/> | 否 <br/> | 否 <br/> |
|政府雲中以外的下列功能，此時無法使用[**Microsoft Outlook**](../../office-applications-service-description/office-applications.md#microsoft-outlook)是完全可用： | **GCC** <br/> | **GCC 高** <br/> | **DOD** <br/> |
|Office 聲音 （部分） | 否 <br/> | 否 <br/> | 否 <br/> |
|動態資料交換 (DDE) 預設停用 | 否 <br/> | 否 <br/> | 否 <br/> |
|聽寫 | 否<sup>1</sup> <br/> | 否<sup>1</sup> <br/> | 否<sup>1</sup> <br/> |
|[**Microsoft PowerPoint**](../../office-applications-service-description/office-applications.md#microsoft-powerpoint)以外的下列功能，此時無法使用的政府定域機組中是完全可用： | **GCC** <br/> | **GCC 高** <br/> | **DOD** <br/> |
|智慧查閱 | 否 <br/> | 否 <br/> | 否 <br/> |
|Office 聲音 （部分） | 否 <br/> | 否 <br/> | 否 <br/> |
|3D 模型和 3D 內嵌動畫 | 否 <br/> | 否 <br/> | 否 <br/> |
|圖表： 對應 | 否 <br/> | 否 <br/> | 否 <br/> |
|智慧型數位筆跡 | 否 <br/> | 否 <br/> | 否 <br/> |
|在 PowerPoint 中即時標題和子標題 | 否 <br/> | 否 <br/> | 否 <br/> |
|簡報者指導 | 否 <br/> | 否 <br/> | 否 <br/> |
|Shared with Me | 否 <br/> | 否 <br/> | 否 <br/> |
|商務用 Skype 與共用 Business 整合 | 否 <br/> | 否 <br/> | 否 <br/> |
|版本歷程記錄 | 否 <br/> | 否 <br/> | 否 <br/> |
|Office 365 群組 | 否 <br/> | 否 <br/> | 否 <br/> |
|即時共同作業平台服務、 一般共同撰寫 （中的文件聊天室） | 否 <br/> | 否 <br/> | 否 <br/> |
|聽寫 | 否<sup>1</sup> <br/> | 否<sup>1</sup> <br/> | 否<sup>1</sup> <br/> |
|重複使用的投影片 | 否 <br/> | 否 <br/> | 否 <br/> |
|政府定域機組中的**Microsoft 白板**只有目前在中樞用戶端，而不是在桌面。 | **GCC**<sup>2</sup> <br/> | **GCC 高**<sup>2</sup> <br/> | **DOD**<sup>2</sup> <br/> |
|插入自黏便箋、 文字和影像 | 是<sup>2</sup> <br/>| 是<sup>2</sup> <br/>| 是<sup>2</sup> <br/>|
|筆跡圖形和筆跡成表格 | 是<sup>2</sup> <br/>| 是<sup>2</sup> <br/>| 是<sup>2</sup> <br/>|
|筆跡 beautification | 是<sup>2</sup> <br/>| 是<sup>2</sup> <br/>| 是<sup>2</sup> <br/>|
|轉換筆跡的影像 | 是<sup>2</sup> <br/>| 是<sup>2</sup> <br/>| 是<sup>2</sup> <br/>|
|協助工具檢查程式 | 是<sup>2</sup> <br/>| 是<sup>2</sup> <br/>| 是<sup>2</sup> <br/>|
|動態範本 （KANBAN、 SWOT，依此類推） | 否 <br/> | 否 <br/> | 否 <br/> |
|即時共同作業 | 否 <br/> | 否 <br/> | 否 <br/> |
|即時顯示狀態 | 否 <br/> | 否 <br/> | 否 <br/> |
|在內容上反應 | 否 <br/> | 否 <br/> | 否 <br/> |
|白板棋盤圖庫，包括與您共用 | 否 <br/> | 否 <br/> | 否 <br/> |
|政府雲中以外的下列功能，此時無法使用， [**Microsoft Word**](../../office-applications-service-description/office-applications.md#microsoft-word)會完全提供： | **GCC** <br/> | **GCC 高** <br/> | **DOD** <br/> |
|智慧查閱 | 否 <br/> | 否 <br/> | 否 <br/> |
|研究工具 | 否 <br/> | 否 <br/> | 否 <br/> |
|Office 音效  | 否 <br/> | 否 <br/> | 否 <br/> |
|3D 模型 | 否 <br/> | 否 <br/> | 否 <br/> |
|3D 內嵌的動畫  | 否 <br/> | 否 <br/> | 否 <br/> |
|點選  | 否 <br/> | 否 <br/> | 否 <br/> |
|簡歷小幫手 | 否 <br/> | 否 <br/> | 否 <br/> |
|地圖圖表 | 否 <br/> | 否 <br/> | 否 <br/> |
|智慧型數位筆跡 | 否 <br/> | 否 <br/> | 否 <br/> |
|Shared with Me | 否 <br/> | 否 <br/> | 否 <br/> |
|Translation | 否 <br/> | 否 <br/> | 否 <br/> |
|商務用 Skype 與共用 Business 整合 | 否 <br/> | 否 <br/> | 否 <br/> |
|版本歷程記錄 | 否 <br/> | 否 <br/> | 否 <br/> |
|Office 365 群組 | 否 <br/> | 否 <br/> | 否 <br/> |
|使用共同撰寫作者的內容相關式交談： 與文件內的共同撰寫作者的聊天室 | 否 <br/> | 否 <br/> | 否 <br/> |
|聽寫 | 否<sup>1</sup> <br/> | 否<sup>1</sup> <br/> | 否<sup>1</sup> <br/> |

> <sup>1</sup>可用性即將推出。<br/>
<sup>2</sup> （未登入） 的本機 Surface Hub 上的可用性。<br/>
<sup>3</sup>應用程式不適目前 DOD 定域機組中。<br/>
<sup>4</sup>外部共用是用於 GCC 環境。 深入了解如何[關閉或開啟 Microsoft 表單上](https://support.office.com/article/cc52287a-4550-464d-9a1b-457bf9df2240#PickTab=Configure)為您的組織。 GCC 高和 DOD 環境; 的已停用外部共用您的組織內的使用者可能會執行下列動作： 完成表單，並提交回應，[複製及共用做為範本的表單](https://support.office.com/article/82ea9d8a-260a-47a0-afdb-497f3d746e3f)，[共同撰寫作者或在表單上共同作業](https://support.office.com/article/d5bb5cf0-8401-4c15-bb8c-8e108cd7e69b)，以及[存取表單的結果](https://support.office.com/article/02859424-341d-406f-b32a-9a0fbaf357af)。
