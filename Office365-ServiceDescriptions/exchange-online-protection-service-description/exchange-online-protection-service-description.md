---
title: Exchange Online Protection 服務說明
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: 取得 Exchange Online Protection 的功能和需求的相關資訊。 包含提供 Exchange Online Protection 的方案清單，以及這些方案中的功能比較。
ms.openlocfilehash: a82468c95f8d674bb2e4b27abc668074f222b419
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/24/2021
ms.locfileid: "59670709"
---
# <a name="exchange-online-protection-service-description"></a>Exchange Online Protection 服務說明

取得 Exchange Online Protection 的功能和需求的相關資訊。 包含提供 Exchange Online Protection 的方案清單，以及這些方案中的功能比較。

Microsoft Exchange OnlineProtection (EOP) 是雲端式的電子郵件篩選服務，可協助組織抵禦垃圾郵件和惡意程式碼，並包含保護您的組織不受郵件原則侵犯的功能。 EOP 能簡化訊息環境的管理，減輕維護內部部署硬體和軟體所衍生的繁重負擔。

下列清單說明您可以使用 EOP 進行郵件保護的主要方式：

- **在獨立案例中**： EOP 為您的內部部署電子郵件環境提供雲端式電子郵件保護。 (Exchange Server 或其他內部部署 SMTP 電子郵件解決方案) 。

- **Microsoft Exchange Online 的一部分**：根據預設，EOP 會保護 Exchange Online 雲端主控信箱。 若要深入瞭解 Exchange Online，請參閱[Exchange Online 服務描述](../exchange-online-service-description/exchange-online-service-description.md)。

- **在混合式部署中**：EOP 可以設定為保護您的郵件環境，並在您混合使用內部部署及雲端信箱時控制郵件路由傳送。

## <a name="available-plans"></a>可用規劃

下表顯示包含 Exchange Online Protection 的計畫，以便您可以選擇最符合組織需求的解決方案。 如需詳細的計畫資訊，請參閱[Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection)。

如需可讓使用者 Exchange Online Protection 之訂閱的詳細計畫資訊，請參閱[完整訂閱比較表](https://www.microsoft.com/microsoft-365/compare-microsoft-365-enterprise-plans)。

### <a name="exchange-enterprise-cal-with-services-features"></a>Exchange Enterprise CAL with Services 功能

Microsoft Exchange Enterprise CAL with Services 提供 EOP 的電子郵件保護功能，以及下列其他雲端式功能：

- [資料外洩防護](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)

- [使用 Web 服務報告](reporting-and-message-trace.md#reporting-using-web-services)

如需 Exchange Enterprise CAL with Services 授權的詳細資訊，請參閱[Exchange 授權 FAQs](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)。

如果您有 Exchange Enterprise CAL with Services 授權，且您想要布建 EOP，請依照[設定 EOP 服務](/microsoft-365/security/office-365-security/set-up-your-eop-service)中的指示進行。 其設定步驟與獨立式 EOP 的設定步驟相同。

> [!NOTE]
> Exchange Enterprise CAL with Services 的新功能會與 Exchange Online (而非獨立式 EOP) 同時部署。請注意，獨立式 EOP 和 Exchange Online/Exchange Enterprise CAL with Service 的部署排程可能稍有不同。

## <a name="requirements-for-exchange-online-protection-eop"></a>Exchange Online Protection (EOP) 的需求

EOP 可搭配任何 SMTP 郵件傳輸代理程式使用，例如 Microsoft Exchange Server。 如需 EOP 所支援的作業系統、網頁瀏覽器及語言的相關資訊，請參閱[Exchange Online Protection 中 Exchange 系統管理中心](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)的「支援的瀏覽器」和「支援的語言」一節。

## <a name="limits"></a>限制

如需 EOP 中的限制，請參閱[Exchange Online Protection 限制](exchange-online-protection-limits.md)。

## <a name="feature-availability"></a>功能可用性

下表列出各種方案中可用的主要 Exchange Online Protection 功能。 適用某些注意事項。 如需進一步資訊，請參閱註腳。 此表格可能會變更而不另行通知。 如需最新、完整的功能清單，請參閱 [強大的工具來支援您的企業](https://products.office.com/business/compare-more-office-365-for-business-plans)。

| 功能 | 獨立 EOP | EOP in EE CAL （含服務） | Exchange Online 中的 EOP 功能 |
|:-----|:-----|:-----|:-----|
|**Protection**||||
|) 內建及自訂的反惡意程式碼原則 (|是|是|是|
|內建和自訂) 的輸入反垃圾郵件原則 (|是|是|是|
|輸出反垃圾郵件原則 (內建和自訂) |是|是|是|
|連線篩選 (IP 允許清單和 IP 封鎖清單) |是|是|是|
|防網路釣魚原則 (內建和自訂) |是|是|是|
|反欺騙保護 (內建和自訂) |是|是|是|
|以零小時自動清除 (ZAP) ，以供傳遞的惡意程式碼、垃圾郵件和網路釣魚郵件<sup>10</sup>|否|否|是|
|預設安全性原則|是|是|是|
|適用於保護原則的設定分析器|是|是|是|
|租用戶允許/封鎖清單|是|是|是|
|郵件寄件者的封鎖清單|是|是|是|
|允許郵件寄件者的清單|是|是|是|
|Edge 封鎖|是|是|是|
|不存在之收件者的目錄基礎 Edge 封鎖 (DBEB) |是|是|是|
|**隔離和提交**||||
|系統管理員提交<sup>10</sup>|否|否|是|
|使用者提交 (自訂信箱) <sup>10</sup>|否|否|是|
|系統管理員隔離|是|是|是|
|使用者隔離|是|是|是|
|報告郵件增益集及報告 Outlook 的網路釣魚增益集|是|是|是|
|**郵件流程**||||
|郵件流程規則 (傳輸規則) <sup>4</sup>|是|是<sup>6</sup>|是|
|公認的網域<sup>3</sup> |是|是|是|
|連接器|是|是|是|
|針對連接器的增強篩選 (略過清單) |是|是|是|
|**監視**||||
|郵件追蹤|是|是|是|
|Microsoft 365 系統管理中心中的電子郵件和安全性報告|是<sup>7</sup>|是<sup>7,8</sup>|是<sup>8</sup>|
|Microsoft 365 安全性中心的安全性報告|是<sup>7</sup>|是<sup>7,8</sup>|是<sup>8</sup>|
|EAC 中的電子郵件報告|是<sup>7</sup>|是<sup>7,8</sup>|是<sup>8</sup>|
|管理員審核記錄<sup>5</sup>|是|是|是|
|**Users**||||
|郵件使用者和郵件連絡人<sup>1</sup>|是|是|是|
|信箱|否|否|是<sup>1a</sup>|
|以角色為基礎的存取控制 (RBAC) <sup>2</sup>|是|是|是|
|**合規性**||||
|電子郵件的資料遺失防護|否|是|是|
|Office 365 郵件加密|無<sup>9</sup>|無<sup>9</sup>|是|
|**系統管理**||||
|Microsoft 365 系統管理中心|是|是|是|
|Exchange 系統管理中心|是|是|是|
|Microsoft 365 安全性中心|是|是|是|
|獨立 Exchange Online Protection PowerShell|是|否|否|
|Exchange Online PowerShell|否|是|是|

<sup>1</sup> 您可以在 EAC 中建立、移除及編輯郵件使用者和郵件連絡人。 <br/>
<sup>1a</sup>您可以在 Microsoft 365 系統管理中心中建立及移除信箱。 您可以在 EAC 中編輯現有的信箱。 <br/>
<sup>2</sup>在獨立 EOP 和 EE CAL 搭配服務，沒有任何使用者角色或角色指派原則。<br/>
<sup>3</sup>您新增及移除 Microsoft 365 系統管理中心中的網域。  在 EAC 中，您可以將網域設定為「授權」或「非授權」。<br/>
<sup>4</sup>獨立 EOP 或使用服務 EE CAL 中的 EOP 無法使用一些規則條件、例外狀況和動作。 這些差異在 Exchange Online 郵件流程規則內容中已明確標明。 <br/>
<sup>5</sup> In 獨立 EOP，並 EE CAL 與服務：

- 信箱審核報告無法使用。
- 系統管理員角色群組報告和系統管理員審核記錄報告為 EAC 中唯一的系統管理員審核報告。
- 只能透過 PowerShell 使用審核記錄匯出。 <br/>

<sup>6</sup> DLP 原則秘訣不適用於具有服務的 EE CAL。 <br/>
<sup>7</sup>獨立 EOP 中的報告和 EE CAL 搭配服務是 Exchange Online 報告的子集， (與) 信箱相關的報告。<br/>
<sup>8</sup> 包含 DLP 報告。 <br/>
<sup>9</sup> 您可以購買 Azure 資訊保護做為附加元件訂閱，並在您設定內部部署電子郵件環境，以透過 EOP 將電子郵件路由傳送到網際網路，並使用 OME。 <br/>
<sup>10</sup>此功能需要 Exchange Online 信箱。 <br/>

## <a name="learn-more"></a>深入了解

如需 Exchange Online Protection 的技術相關資訊，請參閱下列資源：

[Microsoft 365 藍圖](https://office.microsoft.com/products/office-365-roadmap-FX104343353.aspx)是找出即將推出之新功能之相關資訊的好資源。

### <a name="licensing-terms"></a>授權條款

如需透過 Microsoft 商用大量授權方案購買的產品和服務的授權條款及條件，請參閱[產品條款網站](https://www.microsoft.com/licensing/terms/)。

### <a name="messaging"></a>訊息

若要追蹤即將發生的變更，包括新功能和變更的功能、計劃中的維護或其他重要的公告，請造訪訊息中心。 如需詳細資訊，請參閱[訊息中心](/microsoft-365/admin/manage/message-center)。

### <a name="accessibility"></a>協助工具

Microsoft 持續致力於您的資料安全性，以及我們服務的[協助工具](https://www.microsoft.com/trust-center/compliance/accessibility)。 如需詳細資訊，請參閱 [Microsoft 信任中心](https://www.microsoft.com/trust-center)和 [Office 協助工具中心](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)。
