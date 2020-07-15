---
title: Exchange Online Protection 服務說明
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: 取得 Exchange Online Protection 功能和需求的相關資訊。 包含提供 Exchange Online Protection 的方案清單，以及各項方案中功能的比較。
ms.openlocfilehash: 74a2d3a1af3e369e51e1f9b3b4e1cf5cc981c0d8
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132837"
---
# <a name="exchange-online-protection-service-description"></a>Exchange Online Protection 服務說明

取得 Exchange Online Protection 功能和需求的相關資訊。 包含提供 Exchange Online Protection 的方案清單，以及各項方案中功能的比較。

Microsoft Exchange Online Protection (EOP) is a cloud-based email filtering service that helps protect your organization against spam and malware, and includes features to safeguard your organization from messaging-policy violations. EOP can simplify the management of your messaging environment and alleviate many of the burdens that come with maintaining on-premises hardware and software.

下列清單說明您可以使用 EOP 進行郵件保護的主要方式：

- **在獨立案例中**： EOP 為您的內部部署電子郵件環境（Exchange Server 或其他內部部署 SMTP 電子郵件解決方案）提供雲端式電子郵件保護。

- **在 Microsoft Exchange online 中**：依預設，EOP 會保護 Exchange Online 雲端託管信箱。 若要深入瞭解 Exchange Online，請參閱[Exchange online 服務說明](../exchange-online-service-description/exchange-online-service-description.md)。

- **在混合式部署中**：EOP 可以設定為保護您的郵件環境，並在您混合使用內部部署及雲端信箱時控制郵件路由傳送。

若要跨方案比較功能，請參閱[強大的工具來支援您的企業](https://products.office.com/business/compare-more-office-365-for-business-plans)。

若要購買 Exchange Online Protection，請參閱 [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection)。

> [!NOTE]
> EOP 已取代 Forefront Online Protection for Exchange （FOPE）。 所有 FOPE 客戶都已轉換成 EOP。

## <a name="whats-new-in-exchange-online-protection-eop"></a>Exchange Online Protection (EOP) 的新功能

[Microsoft 365 藍圖](https://office.microsoft.com/products/office-365-roadmap-FX104343353.aspx)是用來找出即將推出之新功能之相關資訊的有用資源。

## <a name="exchange-online-protection-eop-plans"></a>Exchange Online Protection (EOP) 計劃

EOP 可透過下列訂閱計劃取得：

|**計劃**|**描述**|
|:-----|:-----|
|[獨立式 EOP](https://products.office.com/exchange/exchange-email-security-spam-protection)|保護您的內部部署電子郵件組織的個別雲端式服務。|
|[Exchange Online 中的 EOP 功能](https://products.office.com/exchange/compare-microsoft-exchange-online-plans)|Exchange Online 雲端託管信箱內建的保護。|
|[Exchange Enterprise CAL with Services](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)|您為內部部署 Exchange 組織購買的附加元件授權，包含 EOP 及其他雲端式功能（如需詳細資訊，請參閱下一節）。|

### <a name="exchange-enterprise-cal-with-services-features"></a>Exchange Enterprise CAL with Services 功能

Microsoft Exchange Enterprise CAL with Services 提供 EOP 的電子郵件保護功能，以及下列其他雲端式功能：

- [資料外洩防護 (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)

- [使用 Web 服務報告](reporting-and-message-trace.md#reporting-using-web-services)

如需 Exchange Enterprise CAL with Services 授權的詳細資訊，請參閱[Exchange 授權 FAQs](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)。

如果您有 Exchange Enterprise CAL with Services 授權，且您想要布建 EOP，請依照[設定 EOP 服務](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-your-eop-service)中的指示進行。 其設定步驟與獨立式 EOP 的設定步驟相同。

> [!NOTE]
> New features for Exchange Enterprise CAL with Services are deployed at the same time as Exchange Online, not EOP standalone. Be advised that the deployment schedules for EOP standalone and Exchange Online/Exchange Enterprise CAL with Services may be slightly different.

## <a name="requirements-for-exchange-online-protection-eop"></a>Exchange Online Protection (EOP) 的需求

EOP 可搭配任何 SMTP 郵件傳輸代理程式使用，例如 Microsoft Exchange Server。 如需 EOP 所支援的作業系統、網頁瀏覽器及語言的相關資訊，請參閱[Exchange Online Protection 中 exchange 系統管理中心](https://docs.microsoft.com/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)的「支援的瀏覽器」和「支援的語言」一節。

## <a name="limits"></a>限制

如需 EOP 中的限制，請參閱[Exchange Online Protection 限制](exchange-online-protection-limits.md)。

## <a name="feature-availability-across-exchange-online-protection-eop-plans"></a>各 Exchange Online Protection (EOP) 計劃中可用的功能

Each feature is listed below. For more detailed information about EOP features, click the links in the table. When Exchange Online is mentioned, it typically refers to the Office 365 Enterprise service family.

|||||
|:-----|:-----|:-----|:-----|
|**功能**|**獨立式 EOP**|**Exchange Online 中的 EOP 功能 <br/>**|**Exchange Enterprise <br/> CAL With Services**|
|[收件者](recipient-domain-and-company-management.md#mail-recipients)|是<sup>1</sup>|是<sup>1</sup>|是|
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
|[反惡意程式碼保護](anti-spam-and-anti-malware-protection-eop.md#anti-malware-protection) (內建)|是<sup>13</sup>|是|是|
|[自訂反惡意程式碼原則](anti-spam-and-anti-malware-protection-eop.md#customize-anti-malware-policies)|是|是|是|
|[隔離](anti-spam-and-anti-malware-protection-eop.md#quarantine)：系統管理員管理|是|是|是|
|[隔離](anti-spam-and-anti-malware-protection-eop.md#quarantine)：使用者自我管理|是|是|是|
|[提交](anti-spam-and-anti-malware-protection-eop.md#report-messages-to-microsoft-for-analysis)|否|是|否|
|[Outlook 的報告訊息增益集](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in)|是|是|是|
|[Outlook 網頁版中的垃圾郵件報告](https://docs.microsoft.com/microsoft-365/security/office-365-security/report-junk-email-and-phishing-scams-in-outlook-on-the-web-eop)|是|是|是|
|[在 Microsoft 和您自己的電子郵件伺服器之間路由傳送電子郵件](mail-flow-eop.md#routing-email-between-microsoft-and-your-own-email-servers)|是|是|是|
|[與信任的合作夥伴間的安全傳訊](mail-flow-eop.md#secure-messaging-with-a-trusted-partner)|是|是|是|
|[安全列出夥伴的 IP 位址](mail-flow-eop.md#safe-listing-a-partners-ip-address)|是|是|是|
|[條件式郵件路由](mail-flow-eop.md#conditional-mail-routing)|是|是|是|
|[混合郵件路由](mail-flow-eop.md#hybrid-mail-routing)|是|是|是|
|[Microsoft 365 系統管理中心報告](reporting-and-message-trace.md#microsoft-365-admin-center-reports)<br/> |是<sup>9</sup>|是<sup>10</sup>|是 <sup>9, 10</sup>|
|[使用 Web 服務報告](reporting-and-message-trace.md#reporting-using-web-services)|否|是|是|
|[郵件追蹤](reporting-and-message-trace.md#message-trace)|是<sup>15</sup>|是<sup>15</sup>|是|
|[存取 Microsoft 365 系統管理中心](administration-and-management-eop.md#access-to-the-microsoft-365-admin-center)|是|是|是|
|[存取 Exchange 系統管理中心](administration-and-management-eop.md#access-to-the-exchange-admin-center (EAC))|是|是|是|
|[Remote Windows PowerShell access](administration-and-management-eop.md#remote-windows-powershell-access)|是|是|是|

<sup>1</sup> 郵件使用者會定義為「信箱」，而且可以連同外部郵件連絡人直接在 Exchange 系統管理中心 (EAC) 中新增、移除或管理。 <br/>
<sup>2</sup> 沒有 RBAC 自訂。 僅限系統管理員角色。 <br/>
<sup>3</sup> 在 EAC 中，可檢視受管理網域和編輯網域類型。 所有其他網域管理都必須在 Microsoft 365 系統管理中心完成。<br/>
EOP 中的<sup>4 個</sup>郵件流程規則（也稱為傳輸規則）是在[Exchange Online Protection 中的郵件流程規則（傳輸規則）](https://docs.microsoft.com/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0)中說明。 EOP 與 Exchange Online 之間的可用郵件流程規則條件、例外狀況和動作略有不同。 在 Exchange Online 中的[郵件流程規則條件和例外狀況（](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions)述詞）和[exchange Online 中的郵件流程規則動作](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions)都有這些差異。<br/>
<sup>5</sup> EOP 稽核報告是 Exchange Online 稽核報告的子集，但不包括信箱的相關資訊。 <br/>
<sup>6</sup> DLP 原則祕訣不適用於 Exchange Enterprise CAL with Services 客戶。  <br/>
<sup>7</sup> 預設的內容篩選動作，就是將垃圾郵件移至收件者的 [垃圾郵件] 資料夾。 若要使用內部部署 Exchange 信箱，您也需要在內部部署 Exchange 組織中設定兩個傳輸規則，以偵測 EOP 新增的垃圾郵件頭。 如需詳細資訊，請參閱[Configure 獨立 EOP 以將垃圾郵件傳遞至混合式環境中的 [垃圾郵件] 資料夾](https://docs.microsoft.com/microsoft-365/security/office-365-security/ensure-that-spam-is-routed-to-each-user-s-junk-email-folder)。 <br/>
<sup>9</sup> EOP 報告是 Exchange Online 報告的子集，但不包括信箱的相關資訊。<br/>
<sup>10</sup> 包括 DLP 報告。 <br/>
<sup>12</sup>對於購買 Azure 資訊保護並使用 Exchange online Protection 透過 exchange online 路由電子郵件的內部部署客戶提供支援。 <br/>
<sup>13</sup> 掃描輸入及輸出郵件，但未掃描從組織中寄件者傳送給組織中收件者的內部郵件。 <br/>
<sup>15</sup> 混合式安裝程式不能透過混合式精靈使用，但您可以手動設定 (如果您有 Exchange SP1)。
