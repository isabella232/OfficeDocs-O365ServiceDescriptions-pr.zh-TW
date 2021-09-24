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
ms.openlocfilehash: 5030c265b309641a0d69e79c1aa8942c45360550
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/24/2021
ms.locfileid: "59670689"
---
# <a name="exchange-online-archiving-service-description"></a>Exchange Online 封存服務說明

Microsoft Exchange Online封存是部署 Microsoft Exchange Server 2019、Microsoft Exchange Server 2016、Microsoft Exchange Server 2013 之組織的 Microsoft 365 雲端架構企業級封存解決方案。Microsoft Exchange Server 2010 (SP2 和更新版本) ，或訂閱特定 Exchange Online 或 Microsoft365 方案。 Exchange Online Archiving可為這些組織在封存、符合性、法規及 eDiscovery 挑戰等方面提供協助，同時可簡化內部部署基礎結構，進而降低成本和減輕 IT 重擔。
  
做為一套 Microsoft 線上服務，Exchange Online 封存旨在協助達成對健全安全性、可靠性和使用者生產力的需求。 如需 Microsoft 365 的詳細資訊（包括所有 Microsoft online 服務通用的功能），請參閱[Microsoft 365 及 Office 365 platform service description](../office-365-platform-service-description/office-365-platform-service-description.md)。
  
若要購買 Exchange Online 封存，請參閱[Exchange Online 封存 for server](https://products.office.com/exchange/microsoft-exchange-online-archiving-email)。
  
## <a name="available-plans"></a>可用規劃

如需可讓使用者 Exchange Online 封存之訂閱的詳細計畫資訊，請參閱[完整訂閱比較表](https://go.microsoft.com/fwlink/?linkid=2139145)。
  
> [!TIP]
> 您可以匯出、儲存及列印服務描述中的頁面。 瞭解如何 [匯出內容搜尋結果](/office365/securitycompliance/export-search-results)。 
  
## <a name="exchange-online-archiving-plans"></a>Exchange Online 封存計劃

您可透過下列計劃使用 Exchange Online Archiving。<br><br>
  
| 規劃 | 描述 |
|:-----|:-----|
|**Exchange Server 適用的 Exchange Online 封存** <br/> |雲端式封存，適用于在 Exchange Server 2019 中使用主要信箱的使用者，Exchange Server 2016，Exchange Server 2013，或 Exchange 2010 (SP2 或更新版本) 。 <br/> 如果您想要將雲端型封存新增至位於內部部署 Exchange 伺服器的主要信箱，您需要設定混合部署。 如需有關混合部署的詳細資訊，請參閱[Exchange Server 混合式部署](/exchange/exchange-hybrid)。 <br/> |
|**Exchange Server 適用的 Exchange Online 封存 (透過企業 CAL 套件)** <br/> |雲端式封存，適用于在 Exchange Server 2019 中使用主要信箱的使用者，Exchange Server 2016，Exchange Server 2013，或 Exchange 2010 (SP2 或更新版本) 。 如需詳細資訊，請參閱 [Client Access 授權和管理授權](https://www.microsoft.com/licensing/product-licensing/client-access-license)。 <br/> |
|**Exchange Online 適用的 Exchange Online 封存** <br/> | 雲端式封存和就地保留做為下列方案<sup>1、2、3</sup>的附加元件：<br/> Exchange Online Plan 1 <br/> Exchange Online Kiosk <br/> Microsoft 365 商務基本版 <br/> Microsoft 365 商務標準版 <br/> Microsoft 365 商務進階版 <br/> Office 365 E1 <br/> Office 365 A1 <br/> Office 365G1 <br/> Office 365鍵 <br/> Microsoft 365 F3<br/> <b>附注：</b>下列計畫已包含封存，而且不需要 Exchange Online 封存做為附加元件：<br/>Office 365 A3 <br/> Office 365 A5 <br/> Office 365 E3 <br/> Office 365 E5 <br/> Exchange Online Plan 2 <br/>Microsoft 365 E3 <br/> Microsoft 365 E5 <br/> Microsoft 365F5 規範 <br/> 如需 Exchange Online 信箱之封存功能的詳細資料，請參閱[Exchange Online 封存中](./archive-features.md)的封存功能。|

<sup>1</sup> 組織只採用雲端 (即組織中沒有信箱位於內部部署 Exchange 伺服器) 時不一定要採用混合部署。 不過，如果內部部署信箱已存在，則需要混合部署。
<br/>
<sup>2</sup> Exchange Online 方案1、Office 365 E1/A1/G1 及 Microsoft 365 商務基本版/Standard/進階版的信箱和封存的大小限制。 如需詳細資訊，請參閱 [Exchange Online 限制](../exchange-online-service-description/exchange-online-limits.md)。 Exchange Online 適用的Exchange Online Archiving附加元件增加了無限量雲端型封存和 [就地保留與訴訟暫止](compliance-and-security-features.md#in-place-hold-and-litigation-hold)。
<br/>
<sup>3</sup>包括我們政府的 GCC、GCC 高及 DoD 方案。

尋找所有 Microsoft 365 計畫的相關資訊嗎？ Microsoft 365 提供各種可滿足您組織需求的最佳方案。 如需不同計畫的詳細資訊，包括獨立計畫選項及從一個計畫移至另一個計畫的資訊，請參閱[Office 365 plan options](../office-365-platform-service-description/office-365-plan-options.md)。
  
## <a name="requirements"></a>需求

若要使用適用於 Exchange Server 的 Exchange Online 封存，使用者信箱必須位於 Exchange Server 2019，Exchange Server 2016，Exchange Server 2013，或 Exchange Server 2010 (SP2 或更新版本) 。
  
### <a name="federated-identity-and-single-sign-on"></a>同盟身分識別和單一登入

系統管理員可以使用單一登入方法，以內部部署 Active Directory 進行驗證。 為了達到此目的，管理員可以設定內部部署的 Active Directory Federation Services （Microsoft Windows Server &reg; 2008 service）以與 Microsoft 同盟閘道同盟。 設定 Active Directory Federation Services 後，其身分識別的所有使用者都可以使用其現有的公司登入，以自動驗證 Office 365。
  
### <a name="user-subscriptions"></a>使用者訂閱

每位存取 Exchange Online Archiving 服務的使用者皆必須具有 Exchange Online Archiving 訂閱。每項電子郵件封存訂閱皆僅能用來儲存一位使用者的郵件資料。
  
## <a name="unlimited-archive-storage-quota"></a>無限制封存儲存配額

 無限制封存功能 (稱為 *自動展開封存*) 提供封存信箱中額外的儲存空間。 每位 Exchange Online 封存訂閱者初始會獲得 100 GB 的封存信箱儲存空間。 當自動展開的封存開啟時，當達到 100 GB 的儲存容量時，會自動新增額外的儲存空間。 在 Exchange 混合式部署中，僅支援雲端式封存信箱的自動展開封存，當內部部署使用者的信箱位於 Exchange Server 2019、Exchange Server 2016 或 Exchange Server 2013 (SP1 或更新版本。 如需詳細資訊，請參閱 [無限制封存的概觀](/office365/securitycompliance/unlimited-archiving)。
  
> [!IMPORTANT]
> 系統管理員無法調整儲存空間配額。<br/>
> 位於 Exchange Server 2010 上的信箱不支援自動展開封存。
  
> [!IMPORTANT]
> [！注意] 只有針對個別使用者或共用信箱所用的信箱，才支援自動展開封存，其增長率為 *&nbsp; 每日未超過 1 GB*。 禁止透過日誌記錄、傳輸規則或自動轉寄規則，將郵件複製到 Exchange Online Archiving信箱中進行封存。 使用者的封存信箱僅供該使用者使用。 Microsoft 保留在使用者封存信箱中用來儲存其他使用者之封存資料的執行個體中或是其他不當使用案例中拒絕不受限封存的權限。
  
## <a name="feature-availability-across-exchange-online-archiving-plans"></a>各 Exchange Online 封存計劃中可用的功能

| 功能 | Exchange Server 適用的 Exchange Online Archiving<sup>1</sup> | Exchange Online 適用的 Exchange Online Archiving<sup>2</sup> |
|:-----|:-----|:-----|
|**[Exchange Online 封存中的封存功能](archive-features.md)** <br/> |||
|封存信箱  <br/> |是  <br/> |是  <br/> |
|使用封存原則移動郵件  <br/> |是  <br/> |是  <br/> |
|將資料匯入封存  <br/> |是  <br/> |是  <br/> |
|復原已刪除的項目  <br/> |是  <br/> |是  <br/> |
|復原已刪除的信箱  <br/> |是  <br/> |是  <br/> |
|信箱備份  <br/> |是  <br/> |是  <br/> |
|**[Exchange Online 封存中的用戶端功能](client-features.md)** <br/> |||
|Outlook<sup>3</sup> <br/> |是  <br/> |是  <br/> |
|Outlook 網頁版  <br/> |是  <br/> |是  <br/> |
|**[Exchange Online 封存中的規範與安全性功能](compliance-and-security-features.md)** <br/> |||
|保留原則  <br/> |是  <br/> |是  <br/> |
|就地保留與訴訟資料暫留<sup>6</sup> <br/> |是  <br/> |是  <br/> |
|就地 eDiscovery  <br/> |是  <br/> |是  <br/> |
|內部部署伺服器與 Exchange Online 封存之間的加密  <br/> |是  <br/> |是  <br/> |
|用戶端與 Exchange Online 封存之間的加密  <br/> |是  <br/> |是  <br/> |
|加密：S/MIME 和 PGP  <br/> |是  <br/> |是  <br/> |
|使用 Azure 資訊保護 的 IRM  <br/> |否  <br/> |否<sup>4</sup> <br/> |
|使用 Windows Server AD RMS 的 IRM  <br/> |是<sup>5</sup> <br/> |是<sup>5</sup> <br/> |
|稽核  <br/> |是  <br/> |是  <br/> |
   

<sup>1</sup> 使用者信箱必須位於 Exchange 2010 SP2 或更新版本上。
<br/>
<sup>2</sup> In-Place 封存僅可用於封存已套用授權之單一使用者或實體的郵件。 禁止使用「就地封存」來儲存多個使用者或實體的郵件。 例如，IT 系統管理員不能建立共用信箱，再由使用者純粹為了封存的目的來複製 (透過 [副本] 或 [密件副本] 欄位，或透過傳輸規則) 共用信箱。 <br/> 
<sup>3</sup>如需支援的 Microsoft Outlook 版本清單，請參閱[Exchange Online 封存中的用戶端功能](client-features.md)。 <br/>
<sup>4</sup> 不包含 Azure 資訊保護，但可以個別的附加元件形式購買，並且會啟用支援的資訊版權管理 (IRM) 功能。 有些 Azure 資訊保護功能需要訂閱 Microsoft 365 Apps 企業版，但不包括 Microsoft 365 商務基本版、Microsoft 365 商務標準版、Office 365 企業版 E1、Office 365 教育版或 Office 365 企業版 F3。 <br/>
<sup>5</sup> Windows Server AD RMS 是內部部署伺服器，必須個別採購並管理，以便啟用支援的 IRM 功能。 <br/>
<sup>6</sup> 當您對信箱進行就地保留或訴訟資料暫留時，會同時保留主要和封存信箱。