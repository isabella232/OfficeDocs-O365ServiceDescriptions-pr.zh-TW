---
title: Exchange Online 封存服務說明
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-archiving-service-description
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 21ebd4bb-7d88-489f-a8aa-376e2536900c
description: 請閱讀本文以瞭解 Microsoft Exchange Online 封存。
ms.openlocfilehash: b757e208c1a3422fad001ba7dbf0e27597ea58ee
ms.sourcegitcommit: 2464903b4632fd8ad2554f37c2646f124b3dd8c4
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/06/2021
ms.locfileid: "60149395"
---
# <a name="exchange-online-archiving-service-description"></a>Exchange Online 封存服務說明

Microsoft Exchange Online封存是部署 Microsoft Exchange Server 2019、Microsoft Exchange Server 2016、Microsoft Exchange Server 2013 或訂閱特定的組織 Microsoft 365 雲端架構的企業級封存解決方案。 Exchange Online 或 Microsoft 365 計畫。 Exchange Online 封存協助組織封存、法規遵從性、法規和 eDiscovery 挑戰。

做為一套 Microsoft 線上服務，Exchange Online 封存旨在協助達成對健全安全性、可靠性和使用者生產力的需求。 如需 Microsoft 365 的詳細資訊（包括所有 Microsoft online 服務通用的功能），請參閱[Microsoft 365 及 Office 365 platform service description](../office-365-platform-service-description/office-365-platform-service-description.md)。

## <a name="exchange-online-archiving-plans"></a>Exchange Online 封存計劃

如需可讓使用者 Exchange Online 封存之訂閱的詳細計畫資訊，請參閱[Exchange Online 封存](https://www.microsoft.com/microsoft-365/exchange/microsoft-exchange-online-archiving-email)。

您可透過下列計劃使用 Exchange Online Archiving。<br><br>
  
| 規劃 | 描述 |
|:-----|:-----|
|**Exchange Server 適用的 Exchange Online 封存** |雲端式封存，適用于在 Exchange Server 2019 中使用主要信箱的使用者，Exchange Server 2016，Exchange Server 2013，或 Exchange 2010 (SP2 或更新版本) 。 <br/> 如果您想要將雲端型封存新增至位於內部部署 Exchange 伺服器的主要信箱，您需要設定混合部署。 如需混合式部署的詳細資訊，請參閱[Exchange Server 混合式部署](/exchange/exchange-hybrid)。 |
|**Exchange Server 適用的 Exchange Online 封存 (透過企業 CAL 套件)** |雲端式封存，適用于在 Exchange Server 2019 中使用主要信箱的使用者，Exchange Server 2016，Exchange Server 2013，或 Exchange 2010 (SP2 或更新版本) 。 如需詳細資訊，請參閱 [Client Access 授權和管理授權](https://www.microsoft.com/licensing/product-licensing/client-access-license)。 |
|**Exchange Online 適用的 Exchange Online 封存** | 雲端式封存和就地保留做為下列方案<sup>1、2、3</sup>的附加元件：<br/> • Exchange Online 方案1 <br/> • Exchange Online Kiosk <br/> • Microsoft 365 商務基本版 <br/> • Microsoft 365 商務標準版 <br/> • Microsoft 365 商務進階版 <br/> • Office 365 E1 <br/> • Office 365 A1 <br/> • Office 365 G1 <br/> • Office 365 F3 <br/> • Microsoft 365 F3<br/> <b>附注：</b>下列計畫已包含封存，而且不需要 Exchange Online 封存做為附加元件：<br/> • Office 365 A3 <br/> • Office 365 A5 <br/> • Office 365 E3 <br/> • Office 365 E5 <br/> • Exchange Online 方案2 <br/> • Microsoft 365 E3 <br/> • Microsoft 365 E5 <br/> • Microsoft 365 F5 規範 <br/> 如需 Exchange Online 信箱之封存功能的詳細資料，請參閱[Exchange Online 封存中](./archive-features.md)的封存功能。|

<sup>1</sup> 組織只採用雲端 (即組織中沒有信箱位於內部部署 Exchange 伺服器) 時不一定要採用混合部署。 不過，如果內部部署信箱已存在，則需要混合部署。
<br/>
<sup>2</sup> Exchange Online 方案1、Office 365 E1/A1/G1 及 Microsoft 365 商務基本版/Standard/進階版的信箱和封存的大小限制。 如需詳細資訊，請參閱 [Exchange Online 限制](../exchange-online-service-description/exchange-online-limits.md)。 適用於 Exchange Online 的 Exchange Online 封存附加元件會新增自動展開的封存，以及[In-Place 保留和訴訟暫](compliance-and-security-features.md#in-place-hold-and-litigation-hold)止。
<br/>
<sup>3</sup>包括我們政府的 GCC、GCC 高及 DoD 方案。

尋找所有 Microsoft 365 計畫的相關資訊嗎？ Microsoft 365 提供各種可滿足您組織需求的最佳方案。 如需不同計畫的詳細資訊，包括獨立計畫選項及從一個計畫移至另一個計畫的資訊，請參閱[Office 365 plan options](../office-365-platform-service-description/office-365-plan-options.md)。

如需不同方案的詳細資訊，請參閱 [完整訂閱比較表](https://go.microsoft.com/fwlink/?linkid=2139145)。

> [!TIP]
> 您可以匯出、儲存及列印服務描述中的頁面。 瞭解如何 [**匯出內容搜尋結果**](/microsoft-365/compliance/export-search-results)。

## <a name="feature-availability-across-exchange-online-archiving-plans"></a>各 Exchange Online 封存計劃中可用的功能

下表列出各項方案中可用的主要 Exchange Online 封存功能 (某些告誡適用于) 。 此表格可能會變更而不另行通知。 如需進一步資訊，請參閱註腳。 如需最新、完整的功能清單，請參閱 [強大的工具來支援您的企業](https://products.office.com/business/compare-more-office-365-for-business-plans)。

| 功能 | Exchange Server 適用的 Exchange Online Archiving<sup>1</sup> | Exchange Online 適用的 Exchange Online Archiving<sup>2</sup> |
|---------|------------------------------------------------|------------------------------------------------|
| [**Exchange Online 封存中的封存功能**](/office365/servicedescriptions/exchange-online-archiving-service-description/archive-features) | | |
| 封存信箱 | 是 | 是 |
| 使用封存原則移動郵件 | 是 | 是 |
| 將資料匯入封存 | 是 | 是 |
| 復原已刪除的項目 | 是 | 是 |
| 復原已刪除的信箱 | 是 | 是 |
| 信箱備份 | 是 | 是 |
| [**Exchange Online 封存中的用戶端功能**](/office365/servicedescriptions/exchange-online-archiving-service-description/client-features) | | |
| Outlook<sup>3</sup> | 是 | 是 |
| Outlook 網頁版 | 是 | 是 |
| [**Exchange Online 封存中的規範與安全性功能**](/office365/servicedescriptions/exchange-online-archiving-service-description/compliance-and-security-features) | | |
| 保留原則 | 是 | 是 |
| 就地保留與訴訟資料暫留<sup>6</sup> | 是 | 是 |
| 就地 eDiscovery | 是 | 是 |
| 內部部署伺服器與 Exchange Online 封存之間的加密 | 是 | 是 |
| 用戶端與 Exchange Online 封存之間的加密 | 是 | 是 |
| 加密：S/MIME 和 PGP | 是 | 是 |
| 使用 Azure 資訊保護 的 IRM | 否 | 否<sup>4</sup> |
| 使用 Windows Server AD RMS 的 IRM | 是<sup>5</sup> | 是<sup>5</sup> |
| 稽核 | 是 | 是 |

<sup>1</sup>使用者信箱必須位於 Exchange 2013 或更新版本。 <br/>
<sup>2</sup> 封存信箱只能用於封存已套用授權之單一使用者或實體的郵件。 禁止使用封存信箱來儲存多個使用者或實體的郵件。 例如，IT 系統管理員不能建立共用信箱，再由使用者純粹為了封存的目的來複製 (透過 [副本] 或 [密件副本] 欄位，或透過傳輸規則) 共用信箱。 <br/>
<sup>3</sup>如需支援的 Microsoft Outlook 版本清單，請參閱[Exchange Online 封存中的用戶端功能](/office365/servicedescriptions/exchange-online-archiving-service-description/client-features)。 <br/>
<sup>4</sup> 不包含 Azure 資訊保護，但可以個別的附加元件形式購買，並且會啟用支援的資訊版權管理 (IRM) 功能。 有些 Azure 資訊保護功能需要訂閱 Microsoft 365 Apps 企業版，但不包括 Microsoft 365 商務基本版、Microsoft 365 商務標準版、Office 365 企業版 E1、Office 365 教育版或 Office 365 企業版 F3。 <br/>
<sup>5</sup> Windows Server AD RMS 是內部部署伺服器，必須個別採購並管理，以便啟用支援的 IRM 功能。 <br/>
<sup>6</sup> 當您對信箱進行就地保留或訴訟資料暫留時，會同時保留主要和封存信箱。

## <a name="licensing-terms"></a>授權條款

如需透過 Microsoft 商用大量授權方案購買的產品和服務的授權條款及條件，請參閱[產品條款網站](https://www.microsoft.com/licensing/terms/)。

## <a name="messaging"></a>訊息

若要追蹤即將發生的變更, 包括新功能和變更的功能、計劃中的維護或其他重要的公告, 請造訪訊息中心。若需其他資訊, 請參閱 [訊息中心](/microsoft-365/admin/manage/message-center)。

## <a name="accessibility"></a>協助工具

Microsoft 持續致力於您的資料安全性，以及我們服務的[協助工具](https://www.microsoft.com/trust-center/compliance/accessibility)。 如需詳細資訊，請參閱 [Microsoft 信任中心](https://www.microsoft.com/trust-center)和 [Office 協助工具中心](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)。

## <a name="learn-more"></a>深入了解

如需 Exchange Online 封存的技術相關資訊，請參閱下列資源：

- 瞭解如何使用規範中心來啟用封存信箱，以支援您組織的郵件保留、eDiscovery 和保留需求：[在安全規範中心啟用封存信箱 &amp; -Microsoft 365 法規遵從性](/microsoft-365/compliance/enable-archive-mailboxes)。
- 深入瞭解 Microsoft Exchange Online 封存中可用的封存功能： [Exchange Online 封存服務描述中](/office365/servicedescriptions/exchange-online-archiving-service-description/archive-features)的封存功能。
- 瞭解如何在 Microsoft 365 中建立封存和刪除原則，以自動將專案移至使用者的封存信箱：[設定組織中的信箱的封存與刪除原則-Microsoft 365 合規性](/microsoft-365/compliance/set-up-an-archive-and-deletion-policy-for-mailboxes)。
- 若要找出各種服務區域的 Exchange Online 限制，包括通訊錄、信箱儲存區，以及報告和郵件追蹤限制，請參閱[Exchange Online 限制-服務描述](/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits)。
- 管理員可以深入瞭解已刪除郵件的復原選項，以及 Exchange Online 用來保護信箱資料的高階方法：[在 Exchange Online 中備份電子郵件](/exchange/back-up-email)。
- 系統管理員可以在使用者的信箱中搜尋及復原已刪除的電子郵件：在 Exchange Online 中，[復原使用者信箱中已刪除的郵件](/exchange/recipients-in-exchange-online/manage-user-mailboxes/recover-deleted-messages)。

### <a name="requirements"></a>需求

若要使用適用於 Exchange Server 的 Exchange Online 封存，使用者信箱必須位於 Exchange Server 2019、Exchange Server 2016 或 Exchange Server 2013。

### <a name="user-subscriptions"></a>使用者訂閱

每位存取 Exchange Online Archiving 服務的使用者皆必須具有 Exchange Online Archiving 訂閱。每項電子郵件封存訂閱皆僅能用來儲存一位使用者的郵件資料。

### <a name="federated-identity-and-single-sign-on"></a>同盟身分識別和單一登入

系統管理員可以使用單一登入方法，以內部部署 Active Directory 進行驗證。 為了達到此目的，管理員可以設定內部部署的 Active Directory Federation Services （Microsoft Windows Server &reg; 2008 service）以與 Microsoft 同盟閘道同盟。 設定 Active Directory Federation Services 後，其身分識別的所有使用者都可以使用其現有的公司登入，以自動驗證 Office 365。

### <a name="archive-storage-quota"></a>封存儲存配額

系統管理員無法調整儲存空間配額。 「封存」功能 (稱為「 *自動展開* 封存」) 會在封存信箱中提供額外的儲存空間，最多可達 1.5 TB。 每位 Exchange Online 封存訂閱者初始會獲得 100 GB 的封存信箱儲存空間。 當自動展開的封存開啟時，當達到 100 GB 的儲存容量時，會自動新增額外的儲存空間。 在 Exchange 混合式部署中，當內部部署使用者的信箱位於 Exchange Server 2019、Exchange Server 2016 或 Exchange Server 2013 SP1 和更新版本時，僅支援雲端式封存信箱的自動展開封存。

[！注意] 只有針對個別使用者或共用信箱所用的信箱，才支援自動展開封存，其增長率為 *每日未超過 1 GB*。 禁止透過日誌記錄、傳輸規則或自動轉寄規則，將郵件複製到 Exchange Online Archiving信箱中進行封存。 使用者的封存信箱僅供該使用者使用。 Microsoft 保留拒絕封存的權利，在此情況下，使用者的封存信箱是用來儲存其他使用者的封存資料，或其他不適當使用的情況。

## <a name="auto-expanding-archiving"></a>自動展開封存

稱為 *自動展開* 封存的封存功能可在封存信箱中提供額外的儲存空間。 每位 Exchange Online 封存訂閱者初始會獲得 100 GB 的封存信箱儲存空間。 當自動展開的封存開啟時，當達到 100 GB 的儲存容量時，會自動新增額外的儲存空間。 這會持續增加儲存空間，直到封存儲存達到 1.5 TB 為止。 在 Exchange 混合式部署中，僅支援雲端式封存信箱的自動展開封存，當內部部署使用者的信箱位於 Exchange Server 2019、Exchange Server 2016 或 Exchange Server 2013 (SP1 或更新版本。 如需詳細資訊，請參閱 [自動展開封存功能概觀](/microsoft-365/compliance/autoexpanding-archiving)。
  
> [!IMPORTANT]
> 系統管理員無法調整儲存空間配額。
>
> 位於 Exchange Server 2010 上的信箱不支援自動展開封存。
  
> [!IMPORTANT]
> [！注意] 只有針對個別使用者或共用信箱所用的信箱，才支援自動展開封存，其增長率為 *&nbsp; 每日未超過 1 GB*。 禁止透過日誌記錄、傳輸規則或自動轉寄規則，將郵件複製到 Exchange Online Archiving信箱中進行封存。 使用者的封存信箱僅供該使用者使用。 Microsoft 保留在使用者的封存信箱用來儲存其他使用者的封存資料或其他不適當用途的情況下，拒絕其他封存儲存的權利。
