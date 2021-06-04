---
title: Exchange Online Protection 中的郵件原則及符合性
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: 請閱讀本文以瞭解 Microsoft Exchange Online Protection (EOP) 中的郵件原則和符合性功能。
ms.openlocfilehash: 81228b13036e831df630cca6f27b4ad285705f29
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653345"
---
# <a name="messaging-policy-and-compliance-in-exchange-online-protection"></a>Exchange Online Protection 中的郵件原則及符合性

Microsoft Exchange OnlineProtection (EOP) 提供可協助您管理電子郵件資料的郵件原則及符合性功能。

尋找所有 EOP 功能的相關資訊嗎？ 請參閱[Exchange Online Protection 服務描述](exchange-online-protection-service-description.md)。

## <a name="mail-flow-rules"></a>郵件流程規則

郵件流程規則 (也稱為傳輸) 規則，可讓您靈活地將自己公司特有的原則套用至電子郵件。 郵件流程規則是由彈性準則所組成，可讓您根據準則定義要採取的條件、例外狀況和動作。 如需詳細資訊，請參閱 [Exchange Online Protection 中的郵件流程規則 (傳輸規則)](/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0)。

## <a name="audit-logging"></a>稽核記錄

稽核記錄可讓您追蹤系統管理員對您組織所做的特定變更。 這些報告可協助您符合法規、規範和訴訟需求。 如需詳細資訊，請參閱 [EOP 中的稽核報告](/microsoft-365/security/office-365-security/auditing-reports-in-eop)。

## <a name="data-loss-prevention-dlp"></a>資料外洩防護 (DLP)

獨立式 EOP 客戶無法使用此功能。 透過深度內容分析，資料外洩防護 (DLP) 可協助您識別、監視和保護組織中的機密資訊。 DLP 對於企業郵件系統越來越重要，因為業務關鍵電子郵件包含需要受到保護的機密資料。 DLP 功能可讓您保護機密資料，而不會影響工作者的生產力。

您可以在 EAC 中設定 DLP 原則，以便可以：

- 開始使用預先設定的原則範本，協助您偵測特定的敏感資訊類型，例如 PCI-DSS 資料、Gramm-Leach-Bliley 金融服務業現代化法案資料，或甚至是特定地區設定的個人識別資訊 (PII)。

- 使用現有郵件流程規則準則和動作的完整功能，並新增郵件流程規則。

- 在完整執行 DLP 原則之前先測試其有效性。

- 加入您自己的自訂 DLP 原則範本和敏感資訊類型。

- 偵測郵件附件、本文或主旨行中的機密資訊，並調整服務採取動作的信賴等級。

- 使用「文件指紋」偵測敏感表單資料。 檔指紋可協助您根據您可以用來定義郵件流程規則和 DLP 原則的文字型表單，輕鬆建立自訂機密資訊類型。

- 新增原則提示，它會向您的 Outlook 2013、Outlook 網頁上和 OWA for 裝置使用者顯示通知，以協助減少資料遺失，也可以透過允許誤報，提高原則的效能。

- 檢閱 DLP 報告中的事件資料，或使用產生事件報告動作來新增您自己的特定報告。

> [!NOTE]
> DLP 原則只會套用至進出組織的郵件。組織內部 (內部) 郵件不會套用 DLP 原則，除非您在內部部署 DLP 的情況下執行 Exchange Server 2013。這項條件也適用於 DLP 原則提示，這些提示會在機密資料誤送至未授權收件者之前，通知使用者可能會發生的原則違規情形。

若要深入瞭解 DLP，請參閱[資料遺失防護 in Exchange Online](/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention)。

## <a name="office-365-message-encryption"></a>Office 365 郵件加密

Office 365 郵件加密（Azure 資訊保護的一部分）是一項線上服務，可讓電子郵件使用者將加密的電子郵件傳送給任何人。 內部部署客戶可以購買 Azure 資訊保護，並使用 Exchange Online Protection 設定透過 Exchange Online 的郵件流程，來存取 Office 365 郵件加密。 若要深入瞭解 Exchange Online 中的 Office 365 郵件加密，請參閱 Exchange Online 服務說明中的[Office 365 郵件加密](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption)。

## <a name="messaging-policy-and-compliance-features-across-eop-options"></a>EOP 選項的郵件原則和符合性功能

| 功能 | 獨立式 EOP | EOP 中的功能 <br/> Exchange Online | Exchange Enterprise <br/> CAL 與服務 |
|:-----|:-----|:-----|:-----|
|郵件流程規則|是<sup>1</sup>|是<sup>1</sup>|是<sup>1、3</sup>|
|稽核記錄|是<sup>2</sup>|是|是|
|資料外洩防護 (DLP)|否|是|是<sup>3</sup>|
|Office 365 郵件加密|是<sup>4</sup>|是|是<sup>4</sup>|

> [!NOTE]
> <sup>1</sup> EOP 和 Exchange Online 之間可用的郵件流程規則條件、例外狀況和動作略有不同。 這些差異會記入[郵件流程規則條件和例外狀況 () 中 Exchange Online](/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions)和[郵件流程規則動作中 Exchange Online](/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions)。 <br/>
> <sup>2</sup> EOP 稽核報告是 Exchange Online 稽核報告的子集，但不包括信箱的相關資訊。<br/>
> <sup>3</sup> DLP 原則祕訣不適用於 Exchange Enterprise CAL with Services 客戶。<br/>
> <sup>4</sup>對於購買 Azure 資訊保護附加元件和使用 Exchange Online Protection 以透過 Exchange Online 路由傳送電子郵件的內部部署客戶提供支援。 針對桌面體驗，除了 Azure 資訊保護附加元件之外，還需購買 Microsoft 365 Apps 企業版。 <br/>