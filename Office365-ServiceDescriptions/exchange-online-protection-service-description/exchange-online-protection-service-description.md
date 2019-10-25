---
title: Exchange Online Protection 服務說明
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: 取得功能和需求，Exchange Online Protection 的相關資訊。 包含會提供 Exchange Online Protection 的計劃的清單，以及的功能比較不同計劃。
ms.openlocfilehash: 92363cebf6478f87f553792d449f0b9b0784fa5b
ms.sourcegitcommit: 05458701350d269dce45c9a0812d67d653c52621
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/25/2019
ms.locfileid: "37700225"
---
# <a name="exchange-online-protection-service-description"></a>Exchange Online Protection 服務說明

取得功能和需求，Exchange Online Protection 的相關資訊。 包含會提供 Exchange Online Protection 的計劃的清單，以及的功能比較不同計劃。

Microsoft Exchange Online Protection (EOP) 是雲端式的電子郵件篩選服務，它能協助組織抵禦垃圾郵件和惡意軟體，同時也包括預防組織發生訊息原則違規的功能。EOP 能簡化訊息環境的管理，減輕維護內部部署硬體和軟體所衍生的繁重負擔。

下列清單說明您可以使用 EOP 來保護郵件的主要方法：

- **在獨立案例中**： EOP 提供雲端式電子郵件保護，如內部電子郵件環境 （Exchange Server 或其他內部部署 SMTP 電子郵件解決方案）。

- **作為 Microsoft Exchange Online 的一部分**： 根據預設，EOP 會保護 Exchange Online 雲端託管信箱。 若要深入了解 Exchange Online，請參閱 [Exchange Online 服務說明](../exchange-online-service-description/exchange-online-service-description.md)。

- **在混合式部署**： EOP 可以設定為保護您的郵件環境，並控制郵件路由傳送您混合使用內部部署及雲端信箱時。

若要跨方案比較功能，請參閱 [比較 Office 365 for Business 方案](https://products.office.com/business/compare-more-office-365-for-business-plans)。

若要購買 Exchange Online Protection，請參閱 [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection)。

> [!NOTE]
> EOP 會取代 Forefront Online Protection for Exchange (FOPE)。 所有 FOPE 客戶已都轉換到 EOP。

## <a name="whats-new-in-exchange-online-protection-eop"></a>Exchange Online Protection (EOP) 的新功能

[適用於商務藍圖的 Office 365](https://office.microsoft.com/products/office-365-roadmap-FX104343353.aspx) 是很好的資源，可找出即將推出之新功能的相關資訊。

## <a name="exchange-online-protection-eop-plans"></a>Exchange Online Protection (EOP) 計劃

EOP 可透過下列訂閱計劃取得：

|**計劃**|**描述**|
|:-----|:-----|
|[獨立式 EOP](https://products.office.com/exchange/exchange-email-security-spam-protection)|個別雲端式服務會保護您的內部部署電子郵件組織。|
|[Exchange Online 中的 EOP 功能](https://products.office.com/exchange/compare-microsoft-exchange-online-plans)|適用於 Exchange Online 雲端託管信箱內建的保護。|
|[Exchange Enterprise CAL with Services](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)|在內部部署 Exchange 組織，包括 EOP 和其他雲端式的功能 （請參閱下一節以取得詳細資料） 購買附加元件授權。|

### <a name="exchange-enterprise-cal-with-services-features"></a>Exchange Enterprise CAL with Services 功能

Microsoft Exchange Enterprise CAL with Services 提供 EOP 的電子郵件保護功能與下列額外項雲端架構的功能：

- [資料外洩防護 (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)

- [使用 Web 服務報告](reporting-and-message-trace.md#reporting-using-web-services)

如需 Exchange Enterprise CAL with Services 授權的詳細資訊，請參閱[Exchange Server 授權](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)。

如果您有 Exchange Enterprise CAL with Services 授權，而且您想要佈建 EOP，請遵循[設定 EOP 服務](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-your-eop-service)中的指示。 其設定步驟與獨立式 EOP 的設定步驟相同。

> [!NOTE]
> Exchange Enterprise CAL with Services 的新功能會與 Exchange Online (而非獨立式 EOP) 同時部署。請注意，獨立式 EOP 和 Exchange Online/Exchange Enterprise CAL with Service 的部署排程可能稍有不同。

## <a name="requirements-for-exchange-online-protection-eop"></a>Exchange Online Protection (EOP) 的需求

EOP 可搭配任何 SMTP 郵件傳輸代理程式，例如 Microsoft Exchange Server。 作業系統、 網頁瀏覽器及 EOP 所支援的語言的相關資訊，請參閱 「 支援瀏覽器 」 和 「 支援的語言 > 章節中[Exchange 系統管理中心在 Exchange Online Protection](https://docs.microsoft.com/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)。

## <a name="limits"></a>限制

如需了解 EOP 中的限制，請參閱 [Exchange Online Protection 限制](exchange-online-protection-limits.md)。

## <a name="feature-availability-across-exchange-online-protection-eop-plans"></a>各 Exchange Online Protection (EOP) 計劃中可用的功能

每項功能如下所列。如需 EOP 功能的詳細資訊，請按一下表格中的連結。提及 Exchange Online 時，通常是指 Office 365 企業版 服務系列。

|||||
|:-----|:-----|:-----|:-----|
|**功能**|**獨立式 EOP**|**中的 EOP 功能<br/>Exchange Online**|**Exchange Enterprise <br/> CAL with Services**|
|[收件者](recipient-domain-and-company-management.md#mail-recipients)|Yes<sup>1</sup>|Yes<sup>1</sup>|是|
|[系統管理角色群組權限](recipient-domain-and-company-management.md#admin-role-group-permissions)|是<sup>2</sup>|是|是|
|[網域管理](recipient-domain-and-company-management.md#domain-management)|是<sup>3</sup>|是<sup>3</sup>|是<sup>3</sup>|
|[符合子網域](recipient-domain-and-company-management.md#match-subdomains)|是|是|否|
|[目錄架構邊緣封鎖 (DBEB)](recipient-domain-and-company-management.md#directory-based-edge-blocking-dbeb)|是|是|是|
|[郵件流程規則](../exchange-online-service-description/message-policy-and-compliance.md#mail-flow-rules)|是<sup>4</sup>|是<sup>4，6</sup>|是|
|[稽核記錄](messaging-policy-and-compliance-servicedesc.md#audit-logging)|是<sup>5</sup>|是|是|
|[資料外洩防護 (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)|否|是|是<sup>6</sup>|
|[Office 365 郵件加密](messaging-policy-and-compliance-servicedesc.md#office-365-message-encryption)|是<sup>12</sup>|是|是<sup>12</sup>|
|[反垃圾郵件保護](anti-spam-and-anti-malware-protection-eop.md#anti-spam-protection) (內建)|是|是|是|
|[自訂反垃圾郵件原則](anti-spam-and-anti-malware-protection-eop.md#customize-anti-spam-policies)|是<sup>7</sup>|是|是|
|[反惡意程式碼保護](anti-spam-and-anti-malware-protection-eop.md#anti-malware-protection) (內建)|Yes<sup>13</sup>|是|是|
|[自訂反惡意程式碼原則](anti-spam-and-anti-malware-protection-eop.md#customize-anti-malware-policies)|是|是|是|
|[隔離](anti-spam-and-anti-malware-protection-eop.md#quarantine)：系統管理員管理|是|是|是|
|[隔離](anti-spam-and-anti-malware-protection-eop.md#quarantine)：使用者自我管理|是|是|是|
|[報告訊息增益集以進行 Outlook](anti-spam-and-anti-malware-protection-eop.md#report-message-add-in-for-outlook)|是|是|是|
|[垃圾郵件回報網頁型 Outlook 中](anti-spam-and-anti-malware-protection-eop.md#junk-email-reporting-in-outlook-on-the-web)|是|是|是|
|[在 Office 365 和您自己的電子郵件伺服器之間路由電子郵件](mail-flow-eop.md#routing-email-between-office-365-and-your-own-email-servers)|是|是|是|
|[與信任的合作夥伴間的安全傳訊](mail-flow-eop.md#secure-messaging-with-a-trusted-partner)|是|是|是|
|[安全列出夥伴的 IP 位址](mail-flow-eop.md#safe-listing-a-partners-ip-address)|是|是|是|
|[條件式郵件路由](mail-flow-eop.md#conditional-mail-routing)|是|是|是|
|[混合郵件路由](mail-flow-eop.md#hybrid-mail-routing)|是|是|是|
|[Microsoft 365 系統管理中心報告](reporting-and-message-trace.md#microsoft-365-admin-center-reports)<br/> |是<sup>9</sup>|是<sup>10</sup>|是 <sup>9, 10</sup>|
|[使用 Web 服務報告](reporting-and-message-trace.md#reporting-using-web-services)|否|是|是|
|[郵件追蹤](reporting-and-message-trace.md#message-trace)|是<sup>15</sup>|是<sup>15</sup>|是|
|[Microsoft 365 系統管理中心存取](administration-and-management-eop.md#access-to-the-microsoft-365-admin-center)|是|是|是|
|[在 Exchange 系統管理中心存取](administration-and-management-eop.md#access-to-the-exchange-admin-center (EAC))|是|是|是|
|[Remote Windows PowerShell access](administration-and-management-eop.md#remote-windows-powershell-access)|是|是|是|

<sup>1</sup> 郵件使用者會定義為「信箱」，而且可以連同外部郵件連絡人直接在 Exchange 系統管理中心 (EAC) 中新增、移除或管理。 <br/>
<sup>2</sup> 沒有 RBAC 自訂。 僅限系統管理員角色。 <br/>
<sup>3</sup> 在 EAC 中，可檢視受管理網域和編輯網域類型。 其他所有網域管理作業都必須在 Microsoft 365 系統管理中心。<br/>
<sup>4</sup> EOP 中的郵件流程規則 （也稱為傳輸規則） 說明[郵件流程規則 （傳輸規則） 在 [Exchange Online Protection](https://docs.microsoft.com/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0)。 可用的郵件流程規則條件、 例外狀況和動作各不相同稍微 EOP 與 Exchange Online。 這些差異是[郵件流程規則條件和例外狀況 （述詞） 中 Exchange Online](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions)和[郵件流程規則動作在 Exchange Online](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions)中所述。<br/>
<sup>5</sup> EOP 稽核報告是 Exchange Online 稽核報告的子集，但不包括信箱的相關資訊。 <br/>
<sup>6</sup> DLP 原則祕訣不適用於 Exchange Enterprise CAL with Services 客戶。  <br/>
<sup>7</sup> 預設的內容篩選動作，就是將垃圾郵件移至收件者的 [垃圾郵件] 資料夾。 針對此選項，即可使用內部部署 Exchange 信箱，您也需要在內部部署 Exchange 組織，以偵測 EOP 所新增的垃圾郵件標頭中設定兩個傳輸規則。 如需詳細資訊，請參閱[確定垃圾郵件會路由傳送至每位使用者的垃圾郵件] 資料夾](https://docs.microsoft.com/microsoft-365/security/office-365-security/ensure-that-spam-is-routed-to-each-user-s-junk-email-folder)。 <br/>
<sup>9</sup> EOP 報告是 Exchange Online 報告的子集，但不包括信箱的相關資訊。<br/>
<sup>10</sup> 包括 DLP 報告。 <br/>
<sup>12</sup>對於購買 Azure 資訊保護，並使用 Exchange Online Protection 透過 Exchange Online 路由電子郵件的內部部署客戶支援。 <br/>
<sup>13</sup> 掃描輸入及輸出郵件，但未掃描從組織中寄件者傳送給組織中收件者的內部郵件。 <br/>
<sup>15</sup> 混合式安裝程式不能透過混合式精靈使用，但您可以手動設定 (如果您有 Exchange SP1)。
