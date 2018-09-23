---
title: Exchange Online 封存服務說明
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-archiving-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 21ebd4bb-7d88-489f-a8aa-376e2536900c
description: Microsoft Exchange Online 封存是 Microsoft Office 365 雲端式企業等級封存解決方案的組織已部署 Microsoft Exchange Server 2013]、 [Microsoft Exchange Server 2010 (SP2 或更新版本)，或某些訂閱Exchange Online 或 Office 365 計劃。Exchange Online 封存協助其封存、 規範、 法規這些組織和 eDiscovery 挑戰簡化內部部署基礎結構，進而降低成本及簡化 IT 負擔時。
ms.openlocfilehash: d88d336f0e5b30a245b6c90c7cc488ca6d5dfc54
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035281"
---
# <a name="exchange-online-archiving-service-description"></a>Exchange Online 封存服務說明

Microsoft Exchange Online 封存是 Microsoft Office 365 雲端式企業等級封存解決方案的組織已部署 Microsoft Exchange Server 2013]、 [Microsoft Exchange Server 2010 (SP2 或更新版本)，或某些訂閱Exchange Online 或 Office 365 計劃。Exchange Online 封存協助其封存、 規範、 法規這些組織和 eDiscovery 挑戰簡化內部部署基礎結構，進而降低成本及簡化 IT 負擔時。
  
做為一套 Microsoft Office 365 線上服務，Exchange Online Archiving旨在協助達成對健全安全性、可靠性和使用者生產力的需求。如需 Office 365 (包括所有 Office 365 線上服務的常見功能) 的詳細資訊，請參閱 [Office 365 平台服務說明](../office-365-platform-service-description/office-365-platform-service-description.md)。
  
若要購買 Exchange Online 封存，請參閱 [Exchange Online 封存](https://go.microsoft.com/fwlink/p/?LinkId=314176)。
  
若要跨方案比較功能，請參閱 [比較 Office 365 for Business 方案](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)。
  
> [!TIP]
> 您可以在「Office 365 服務說明」中匯出、儲存和列印頁面。了解如何[匯出多個頁面](https://go.microsoft.com/fwlink/?LinkId=403349)。 
  
## <a name="exchange-online-archiving-plans"></a>Exchange Online 封存計劃
<a name="bkmk_EOA_Plans"> </a>

您可透過下列計劃使用 Exchange Online Archiving。
  
|**計劃**|**描述**|
|:-----|:-----|
|**Exchange Server 適用的 Exchange Online 封存** <br/> |雲端型封存，適用於在 Exchange Server 2013 或 Exchange 2010 (SP2 或更新版本) 中有主要信箱的使用者。  <br/> 如果您想要將雲端型封存新增至位於內部部署 Exchange 伺服器的主要信箱，您需要設定混合部署。如需有關混合部署的詳細資訊，請參閱 [Exchange Server 混合部署](https://technet.microsoft.com/library/jj200581%28v=exchg.150%29.aspx)。  <br/> |
|**Exchange Server 適用的 Exchange Online 封存 (透過企業 CAL 套件)** <br/> |雲端型封存，適用於在 Exchange Server 2013 或 Exchange 2010 (SP2 或更新版本) 中有主要信箱的使用者。如需詳細資訊，請參閱[授權簡介 - 獲得核心 CAL 套件和企業 CAL 套件的授權](https://go.microsoft.com/fwlink/p/?LinkId=314160)。  <br/> |
|**Exchange Online 適用的 Exchange Online 封存** <br/> | 雲端式封存與就地保留，做為下列計劃的附加元件: <sup>1、 2</sup>、  <br/>  Exchange Online Plan 1  <br/>  Exchange Online Kiosk  <br/>  Office 365 商務基本版  <br/>  Office 365 商務進階版  <br/>  Office 365 Enterprise E1  <br/>  Office 365 企業版 F1  <br/> > [!NOTE]> 於下列計劃已包含封存並不需要 Exchange Online 封存做為附加元件： > Office 365 教育版 A1 > Office 365 教育版 A3 > Office 365 教育版 A5 > Office 365 企業版 E3 > Office 365 企業版 E5 > Exchange Online 計劃 2 > Exchange Online 信箱的封存功能的詳細資訊，請參閱[封存信箱在 Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404421)。           |
   
> [!NOTE]
> <sup>1</sup> 組織只採用雲端 (即組織中沒有信箱位於內部部署 Exchange 伺服器) 時不一定要採用混合部署。不過，如果內部部署信箱已存在，則需要混合部署。 > <sup>2</sup> Exchange Online Plan 1 和 Office 365 商務版計劃有 [信箱和封存的大小限制](https://go.microsoft.com/fwlink/?LinkId=330039)。Exchange Online 適用的Exchange Online Archiving附加元件增加了無限量雲端型封存和 [就地保留與訴訟暫止](compliance-and-security-features.md#in-place-hold-and-litigation-hold)。 
  
尋找關於所有 Office 365 計劃的詳細資訊嗎？我們在多種計劃中提供 Office 365 以盡可能滿足組織的需求。如需各種計劃的相關資訊 (包括獨立計劃選項和從某個計劃移動到其他計劃的資訊)，請參閱 Office 365 計劃選項[Office 365 方案選項](../office-365-platform-service-description/office-365-plan-options.md)。
  
## <a name="requirements"></a>需求
<a name="bkmk_EOA_Plans"> </a>

為了使用 Exchange Online Archiving for Exchange Server，使用者信箱必須位於 Exchange Server 2013 或 Exchange Server 2010 (SP2 或更新版本) 上。
  
### <a name="federated-identity-and-single-sign-on"></a>同盟身分識別和單一登入

系統管理員可以使用內部部署 Active Directory 以單一登入法進行 Office 365 驗證。若要達成這個目的，系統管理員可以設定內部部署 Active Directory Federation Services (一套 Microsoft Windows Server® 2008 服務)，透過 Microsoft 同盟閘道 來建立同盟。設定 Active Directory Federation Services 之後，所有其身分識別是以同盟網域為基礎的 Office 365 使用者，皆可以使用其現有的公司登入帳戶，自動在 Office 365 通過驗證。
  
### <a name="user-subscriptions"></a>使用者訂閱

每位存取 Exchange Online Archiving 服務的使用者皆必須具有 Exchange Online Archiving 訂閱。每項電子郵件封存訂閱皆僅能用來儲存一位使用者的郵件資料。
  
## <a name="unlimited-archive-storage-quota"></a>無限制封存儲存配額
<a name="bkmk_EOA_Plans"> </a>

 Office 365 中的無限制封存功能 (稱為 自動展開封存) 提供封存信箱中無限制的儲存空間量。每位 Exchange Online Archiving 訂閱者初始會獲得 100 GB 的封存信箱儲存空間。開啟自動展開封存時，當儲存容量達到 100 GB 時，會自動加入額外的儲存空間。如需詳細資訊，請參閱[在 Office 365 中的無限制封存的概觀](https://go.microsoft.com/fwlink/?linkid=844060)。如需可用性的詳細資訊，請參閱 [Office 365 藍圖](http://go.microsoft.com/fwlink/?LinkId=509914)。 
  
> [!IMPORTANT]
> 系統管理員無法調整儲存空間配額。 
  
> [!IMPORTANT]
> 禁止透過日誌記錄、傳輸規則或自動轉寄規則，將郵件複製到 Exchange Online Archiving信箱中進行封存。使用者的封存信箱僅供該使用者使用。Microsoft 保留在使用者封存信箱中用來儲存其他使用者之封存資料的執行個體中拒絕不受限封存的權限。 
  
## <a name="feature-availability-across-exchange-online-archiving-plans"></a>各 Exchange Online 封存計劃中可用的功能
<a name="bkmk_EOA_Plans"> </a>

||||
|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Server 適用的 Exchange Online Archiving<sup>1</sup>**          <br/> |**Exchange Online 適用的 Exchange Online Archiving<sup>2</sup>** <br/> |
|**[Exchange Online 封存中的封存功能](archive-features.md)** <br/> |||
|封存信箱  <br/> |是  <br/> |是  <br/> |
|使用封存原則移動郵件  <br/> |是  <br/> |是  <br/> |
|將資料匯入封存  <br/> |是  <br/> |是  <br/> |
|復原已刪除的項目  <br/> |是  <br/> |是  <br/> |
|復原已刪除的信箱  <br/> |是  <br/> |是  <br/> |
|信箱備份  <br/> |是  <br/> |是  <br/> |
|**[Exchange Online 封存中的用戶端功能](client-features.md)** <br/> |||
|Outlook<sup>3</sup> <br/> |是  <br/> |是  <br/> |
|Outlook Web App  <br/> |是  <br/> |是  <br/> |
|**[在 Exchange Online 封存的遵循與安全性功能](compliance-and-security-features.md)** <br/> |||
|保留原則  <br/> |是  <br/> |是  <br/> |
|就地保留與訴訟資料暫留<sup>6</sup> <br/> |是  <br/> |是  <br/> |
|就地 eDiscovery  <br/> |是  <br/> |是  <br/> |
|內部部署伺服器與 Exchange Online 封存之間的加密  <br/> |是  <br/> |是  <br/> |
|用戶端與 Exchange Online 封存之間的加密  <br/> |是  <br/> |是  <br/> |
|加密：S/MIME 和 PGP  <br/> |是  <br/> |是  <br/> |
|使用 Azure 資訊保護 的 IRM  <br/> |否  <br/> |沒有<sup>4</sup> <br/> |
|使用 Windows Server AD RMS 的 IRM  <br/> |Yes<sup>5</sup> <br/> |Yes<sup>5</sup> <br/> |
|稽核  <br/> |是  <br/> |是  <br/> |
   

> <sup>1</sup> 使用者信箱必須位於 Exchange 2010 SP2 或更新版本上。
 <br/><sup>2</sup>就地封存只封存郵件單一使用者或實體已套用授權的使用。禁止為方法使用就地封存儲存來自多個使用者或實體的郵件。例如 IT 管理員無法建立共用的信箱並讓使用者將複製 （透過 [副本] 或 [密件副本] 欄位中，或透過傳輸規則） 共用的信箱的封存明確的目的。 <br/> <sup>3</sup>支援的 Microsoft Outlook 版本清單，請參閱[Exchange Online 封存中的用戶端功能](client-features.md)。 
 <br/><sup>4</sup> azure 資訊保護未包含在內，但是可以購買作為個別的附加元件和會啟用支援的資訊版權管理 (IRM) 功能。有些 Azure 資訊保護功能需要 Office 365 ProPlus，這是不包含在 Office 365 商務 Essentials、 Office 365 企業進階版、 Office 365 企業版 E1、 Office 365 教育版或 Office 365 企業版 F1 訂閱。 <br/><sup>5</sup> Windows Server AD RMS 是內部部署伺服器，必須個別採購並管理，以便啟用支援的 IRM 功能。 
 <br/><sup>6</sup> 當您對信箱進行就地保留或訴訟資料暫留時，會同時保留主要和封存信箱。 