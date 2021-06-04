---
title: Microsoft Teams 服務描述
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: 深入瞭解 Microsoft 365 和 Office 365 方案中的 Microsoft Teams 服務和功能可用性。
ms.openlocfilehash: 721c4bd99fd8f81e471ea79e6725c2d6c53d1791
ms.sourcegitcommit: c455501e86037b0f86e0afc9d6d6d04afdfd3442
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/28/2021
ms.locfileid: "52074484"
---
# <a name="microsoft-teams-service-description"></a>Microsoft Teams 服務描述

Microsoft Teams 是 Microsoft 365 團隊合作的中心。 Teams 服務可讓您立即訊息、音訊和影片通話、豐富的線上會議、行動經驗和大量的 web 會議功能。 此外，Teams 提供檔案與資料共同作業及擴充功能，並與 Microsoft 365 和其他 Microsoft 和合作夥伴應用程式整合。

商務用 Skype線上停用於2021年7月31日（從 2019[宣佈](https://techcommunity.microsoft.com/t5/Microsoft-Teams-Blog/Skype-for-Business-Online-to-Be-Retired-in-2021/ba-p/777833)）。 Microsoft Teams 是一種全新的服務，其從頭開始使用 Azure 及其他 Microsoft 的服務創新，從頭開始為雲端構建全新服務。 Microsoft Teams 是以 Microsoft 365 的群組、Microsoft Graph，以及與其他 Office 365 相同的企業層級安全性、合規性和可管理性來建立。 Teams 利用 Azure Active Directory (Azure AD) 中儲存的身分識別。 這些服務是由 Microsoft 資料中心提供，可供使用者從公司網路內部或透過網際網路內部的各種裝置存取。 如需詳細資訊，請參閱[Microsoft Teams IT 架構和電話語音解決方案海報](/microsoftteams/teams-architecture-solutions-posters)。

此服務說明會詳細說明各雲端安裝所提供服務之間的主要差異。 每個訂閱中的核心功能都不會有不同的 Microsoft Teams。 相容性功能的可用性取決於您的訂閱等級。 若要深入瞭解 Teams 安全性與合規性，請參閱[Microsoft Teams 中的安全性和符合性](/microsoftteams/security-compliance-overview)。

如果使用者已完全線上，他們必須同時擁有兩個小組和商務用 Skype 線上授權，以取得完整 Teams 功能，即使不會使用商務用 Skype 線上也是一樣。

## <a name="available-plans"></a>可用規劃

如需可讓使用者 Teams 之訂閱的詳細計畫資訊，請參閱[尋找您的公司的正確 Microsoft Teams](https://www.microsoft.com/microsoft-teams/compare-microsoft-teams-options)。 您可以在 [Microsoft 解決方案比較表](https://go.microsoft.com/fwlink/?linkid=2139145)中找到其他詳細資料。

支援 Teams 的政府方案包括 Office 365 G1 到 G5。 如需詳細資訊，請參閱[Office 365 政府版方案](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans)。

所有支援的訂閱者案都符合存取 Microsoft Teams 網頁用戶端、桌面用戶端和行動應用程式的資格。

不能以獨立服務的方式使用 Microsoft Teams。

## <a name="feature-availability"></a>功能可用性

下表列出各種方案中可用的主要 Teams 功能。 適用某些注意事項。 如需詳細資訊，請參閱註腳。 此表格可能會變更，恕不另行通知。

若要深入瞭解作業系統平臺的 Teams 功能，請參閱[依平臺 Teams 功能](https://aka.ms/teamsfeaturesbyplatform)。

如需跨 Microsoft 365 和 Office 365 方案的 Teams 功能的最新清單，請參閱[尋找適用于您的商務 Microsoft Teams](https://www.microsoft.com/microsoft-teams/compare-microsoft-teams-options)。<br><br>

| 功能 | 小型企業方案 | Enterprise 方案 | GCC | GCC-高 | DOD | 教育計畫 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|聊天  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Teams  <br/> |是 <br/> |是 <br/> |是 <br/> |是<sup>1</sup>  <br/> |是<sup>1</sup>  <br/> |是  <br/> |
|通道-標準  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|通道-私人  <br/> |是  <br/> |是<sup>2</sup>  <br/> |是 <br/> |否  <br/> |否 <br/> |是  <br/> |
|會議  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Audio/Video 桌面 PowerPoint 螢幕共用 <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|語音  <br/> |是  <br/> |是  <br/> |是  <br/> |是<sup>3</sup>  <br/> |是<sup>3</sup>  <br/> |是  <br/> |
|音訊會議  <br/> |是  <br/> |是  <br/> |是  <br/> |是<sup>3</sup>  <br/> |是<sup>3</sup>  <br/> |是  <br/> |
|應用程式、Bot、& 連接器  <br/> |是  <br/> |是  <br/> |是<sup>4</sup>  <br/> |是<sup>4</sup>  <br/> |是<sup>4</sup>  <br/> |是  <br/> |
|即時事件  <br/> |否  <br/> |是  <br/> |是  <br/> |否<sup>5</sup>  <br/> |否<sup>5</sup>  <br/> |是  <br/> |

<sup>1</sup> Microsoft Teams 在個別小組中 GCC-High 和 DOD 支援2500成員。<br/>
<sup>2</sup> Microsoft Planner 目前無法存取私人通道。<br/>
<sup>3</sup>必須設定直接路由，Microsoft Teams 語音和音訊會議才能在 GCCH 和 DoD 中運作。<br/>
<sup>4</sup> 此時不提供這些雲中的協力廠商應用程式和應用程式發佈。 GCCH 和 DOD 不支援連接器。<br/>
目前 GCC-High 或 DOD 未提供<sup>5</sup>項 Live 事件。<br/>

### <a name="cloud-voice-features"></a>雲端語音功能

若為音訊會議，您的組織必須為設定電話撥入式會議的每位使用者購買並指派音訊會議授權。 針對需要通話方案的 Teams 功能，每一位使用者都需要一個電話系統和國內或國內和國際通話方案。 若要深入瞭解，請參閱[Microsoft Teams 附加元件授權](/microsoftteams/teams-add-on-licensing/microsoft-teams-add-on-licensing)。

### <a name="live-events"></a>即時活動

在 Office 365 中這項服務會取代退休的 Skype 會議廣播。 即時事件功能適用于 Stream service 中詳細的授權方案。 如需詳細資訊，請參閱 [Microsoft Stream 授權概述](/stream/license-overview)。 即時事件服務可透過 Stream、Yammer 或 Microsoft Teams 進行存取。 若要深入瞭解即時事件功能，請參閱在[Yammer、Microsoft Teams 和 Microsoft Stream 的 Microsoft 365 中的即時事件](/stream/live-event-m365)。 若要深入瞭解規劃即時事件（包括授權需求），請參閱[Plan for live events in Microsoft Teams](/microsoftteams/teams-live-events/plan-for-teams-live-events)。

## <a name="learn-more"></a>深入了解

如需 Teams 的詳細資訊，請參閱下列資源：
 
- [Microsoft Teams 系統管理文件](/MicrosoftTeams)
- [Microsoft Teams 技術社區](https://techcommunity.microsoft.com/t5/microsoft-teams/ct-p/MicrosoftTeams)
- [Microsoft Teams 博客](https://aka.ms/TeamsBlog)

### <a name="licensing-terms"></a>授權條款

如需透過 Microsoft 商業大量授權方案購買之產品和服務的授權條款及條件，請參閱 [產品條款網站](https://www.microsoft.com/licensing/terms/)。 

### <a name="messaging"></a>訊息

若要瞭解即將進行的變更，包括新增及變更的功能、規劃的維護或其他重要宣告，請造訪郵件中心。 如需詳細資訊，請參閱 [Message center](/microsoft-365/admin/manage/message-center)。

### <a name="accessibility"></a>協助工具

Microsoft 仍會致力於保護您的資料和我們的服務的可存取性。 如需詳細資訊，請參閱[Microsoft 信任中心](https://www.microsoft.com/trust-center)和[Office 協助工具中心](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)。
