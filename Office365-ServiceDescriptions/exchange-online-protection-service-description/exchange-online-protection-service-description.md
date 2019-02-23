---
title: Exchange Online Protection 服務說明
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: 取得 Exchange Online Protection 功能與需求的資訊。包含提供 Exchange Online Protection 的計劃清單，和不同計劃的功能比較。
ms.openlocfilehash: 749a4a8e1b9e8e93397f39a998e5bac6e1c0c745
ms.sourcegitcommit: 4abe1be8a63406e8a8c1a4a69f95386906ea1499
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 02/22/2019
ms.locfileid: "30210266"
---
# <a name="exchange-online-protection-service-description"></a>Exchange Online Protection 服務說明

取得 Exchange Online Protection 功能與需求的資訊。包含提供 Exchange Online Protection 的計劃清單，和不同計劃的功能比較。
  
Microsoft Exchange Online Protection (EOP) 是雲端式的電子郵件篩選服務，它能協助組織抵禦垃圾郵件和惡意軟體，同時也包括預防組織發生訊息原則違規的功能。EOP 能簡化訊息環境的管理，減輕維護內部部署硬體和軟體所衍生的繁重負擔。
  
下列是您可以使用 EOP 來保護郵件的主要方法：
  
- **在獨立案例**EOP 提供雲端式電子郵件保護您的內部部署 Exchange Server 2013 環境、 舊式 Exchange Server 版本，或任何其他內部部署 SMTP 電子郵件解決方案。 
    
- **作為 Microsoft Exchange Online** 的一部分根據預設，EOP 會保護 Exchange Online 雲端託管信箱。若要進一步了解 Exchange Online，請參閱 [Exchange Online 服務說明](../exchange-online-service-description/exchange-online-service-description.md)。
    
- **在混合部署中** EOP 可以設定為保護您的郵件環境，並在您混合使用內部部署及雲端信箱時控制郵件路由傳送。 
    
若要跨方案比較功能，請參閱 [比較 Office 365 for Business 方案](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)。
  
若要購買 Exchange Online Protection，請參閱 [Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=294201)。
  
您可以在「Office 365 服務說明」中匯出、儲存和列印頁面。了解如何[匯出多個頁面](https://go.microsoft.com/fwlink/?LinkId=403349)。
  
> [!IMPORTANT]
> EOP 取代了 Forefront Online Protection for Exchange (FOPE)。所有 FOPE 客戶將轉換到 EOP。EOP 不僅能提供 FOPE 固有的保護和控制力，同時還包括額外的功能。如需從 FOPE 轉換到 EOP 的詳細資訊，請前往 [Forefront Online Protection for Exchange (FOPE) 轉換中心](http://www.movetoeop.com)。 
  
## <a name="whats-new-in-exchange-online-protection-eop"></a>Exchange Online Protection (EOP) 的新功能

如需有關 EOP 新增功能的資訊，請參閱 [Exchange Online Protection 新增功能](https://go.microsoft.com/fwlink/p/?LinkId=320390)。如需 FOPE 與 EOP 的功能比較，請參閱 [FOPE 與 EOP 的功能比較](https://go.microsoft.com/fwlink/p/?LinkId=320391)。
  
## <a name="exchange-online-protection-eop-plans"></a>Exchange Online Protection (EOP) 計劃

EOP 可透過下列訂閱計劃取得：
  
|**計劃**|**描述**|
|:-----|:-----|
|[獨立式 EOP](https://go.microsoft.com/fwlink/p/?LinkId=294201) <br/> |EOP 會保護您的內部部署信箱。  <br/> |
|[Exchange Online 中的 EOP 功能](https://go.microsoft.com/fwlink/p/?LinkId=294197) <br/> |EOP 會保護您的 Exchange Online 雲端託管信箱。  <br/> |
|[Exchange Enterprise CAL with Services](https://go.microsoft.com/fwlink/p/?LinkId=293699) <br/> |EOP 會像獨立式 EOP 一樣保護您的內部部署信箱，並包含資料遺失防護 (DLP) 以及使用 Web 服務進行的報告。  <br/> |
   
### <a name="exchange-enterprise-cal-with-services-features"></a>Exchange Enterprise CAL with Services 功能

Microsoft Exchange Enterprise CAL with Services 提供適用於內部部署郵件環境的 EOP 電子郵件保護功能，以及下列功能：
  
- [資料外洩防護 (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)
    
- [使用 Web 服務報告](reporting-and-message-trace.md#reporting-using-web-services)
    
如需關於 Exchange Enterprise CAL with Services 授權的詳細資訊，請參閱 [Exchange Server 2013 授權](https://go.microsoft.com/fwlink/p/?LinkId=293699)。
  
如果您有 Exchange Enterprise CAL with Services 授權，而且想要佈建服務，請遵循[設定 EOP 服務](https://go.microsoft.com/fwlink/p/?LinkId=320397)中的指示。其設定步驟與獨立式 EOP 的設定步驟相同。
  
> [!NOTE]
> Exchange Enterprise CAL with Services 的新功能會與 Exchange Online (而非獨立式 EOP) 同時部署。請注意，獨立式 EOP 和 Exchange Online/Exchange Enterprise CAL with Service 的部署排程可能稍有不同。 
  
## <a name="requirements-for-exchange-online-protection-eop"></a>Exchange Online Protection (EOP) 的需求

EOP 可搭配任何 SMTP 郵件傳輸代理程式使用，例如 Microsoft Exchange Server 2013。如需 EOP 所支援的作業系統、網頁瀏覽器和語言的資訊，請參閱 [Exchange Online Protection 中的 Exchange 系統管理中心](https://go.microsoft.com/fwlink/p/?LinkId=282381)中的「支援的瀏覽器」和「支援的語言」小節。
  
## <a name="limits"></a>限制

如需了解 EOP 中的限制，請參閱 [Exchange Online Protection 限制](exchange-online-protection-limits.md)。
  
## <a name="feature-availability-across-exchange-online-protection-eop-plans"></a>各 Exchange Online Protection (EOP) 計劃中可用的功能

每項功能如下所列。如需 EOP 功能的詳細資訊，請按一下表格中的連結。提及 Exchange Online 時，通常是指 Office 365 企業版 服務系列。
  
|||||
|:-----|:-----|:-----|:-----|
|**功能** <br/> |**獨立式 EOP** <br/> |**Exchange Online 中的 EOP 功能** <br/> |**Exchange Enterprise CAL with Services** <br/> |
|[收件者](recipient-domain-and-company-management.md#mail-recipients) <br/> |是<sup>1</sup> <br/> |是<sup>1</sup> <br/> |是  <br/> |
|[系統管理角色群組權限](recipient-domain-and-company-management.md#admin-role-group-permissions) <br/> |是<sup>2</sup> <br/> |是  <br/> |可以  <br/> |
|[網域管理](recipient-domain-and-company-management.md#domain-management) <br/> |Yes<sup>3</sup> <br/> |Yes<sup>3</sup> <br/> |Yes<sup>3</sup> <br/> |
|[符合子網域](recipient-domain-and-company-management.md#match-subdomains) <br/> |是  <br/> |有  <br/> |否  <br/> |
|[目錄架構邊緣封鎖 (DBEB)](recipient-domain-and-company-management.md#directory-based-edge-blocking-dbeb) <br/> |是  <br/> |是   <br/> |是  <br/> |
|[傳輸規則](messaging-policy-and-compliance-servicedesc.md#transport-rules) <br/> |是<sup>3, 4, 14</sup> <br/> |是<sup>3, 4, 14</sup> <br/> |是  <br/> |
|[稽核記錄](messaging-policy-and-compliance-servicedesc.md#audit-logging) <br/> |Yes<sup>5</sup> <br/> |是  <br/> |可以  <br/> |
|[資料外洩防護 (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp) <br/> |否  <br/> |是  <br/> |Yes<sup>6</sup> <br/> |
|[Office 365 郵件加密](messaging-policy-and-compliance-servicedesc.md#office-365-message-encryption) <br/> |是<sup>12</sup> <br/> |是  <br/> |是<sup>12</sup> <br/> |
|[反垃圾郵件保護](anti-spam-and-anti-malware-protection-eop.md#anti-spam-protection) (內建)  <br/> |是  <br/> |是   <br/> |可以  <br/> |
|[自訂反垃圾郵件原則](anti-spam-and-anti-malware-protection-eop.md#customize-anti-spam-policies) <br/> |是<sup>7</sup> <br/> |是  <br/> |可以  <br/> |
|[反惡意程式碼保護](anti-spam-and-anti-malware-protection-eop.md#anti-malware-protection) (內建)  <br/> |Yes<sup>13</sup> <br/> |是  <br/> |可以  <br/> |
|[自訂反惡意程式碼原則](anti-spam-and-anti-malware-protection-eop.md#customize-anti-malware-policies) <br/> |是  <br/> |是   <br/> |可以  <br/> |
|[隔離](anti-spam-and-anti-malware-protection-eop.md#quarantine)：系統管理員管理  <br/> |是  <br/> |是   <br/> |是  <br/> |
|[隔離](anti-spam-and-anti-malware-protection-eop.md#quarantine)：使用者自我管理  <br/> |是  <br/> |是   <br/> |可以  <br/> |
|[適用於 Microsoft Office Outlook 的垃圾郵件回報增益集](anti-spam-and-anti-malware-protection-eop.md#junk-email-reporting-add-in-for-microsoft-office-outlook) <br/> |是  <br/> |有  <br/> |可以  <br/> |
|[Outlook Web App 中的垃圾郵件回報](anti-spam-and-anti-malware-protection-eop.md#junk-email-reporting-in-outlook-web-app) <br/> |Yes<sup>8</sup> <br/> |沒有<sup>8</sup> <br/> |沒有<sup>8</sup> <br/> |
|[在 Office 365 和您自己的電子郵件伺服器之間路由電子郵件](mail-flow-eop.md#routing-email-between-office-365-and-your-own-email-servers) <br/> |是  <br/> |有  <br/> |可以  <br/> |
|[與信任的合作夥伴間的安全傳訊](mail-flow-eop.md#secure-messaging-with-a-trusted-partner) <br/> |是  <br/> |有  <br/> |可以  <br/> |
|[安全列出夥伴的 IP 位址](mail-flow-eop.md#safe-listing-a-partners-ip-address) <br/> |是  <br/> |有  <br/> |可以  <br/> |
|[條件式郵件路由](mail-flow-eop.md#conditional-mail-routing) <br/> |是  <br/> |有  <br/> |是  <br/> |
|[混合郵件路由](mail-flow-eop.md#hybrid-mail-routing) <br/> |是  <br/> |有  <br/> |可以  <br/> |
|[Microsoft 365 系統管理中心報告](reporting-and-message-trace.md#office-365-admin-center-reports) <br/> |Yes<sup>9</sup> <br/> |是<sup>10</sup> <br/> |是 <sup>9, 10</sup> <br/> |
|[Excel 下載應用程式報告](reporting-and-message-trace.md#excel-download-application-reports) <br/> |是  <br/> |可以  <br/> |Yes<sup>11</sup> <br/> |
|[使用 Web 服務報告](reporting-and-message-trace.md#reporting-using-web-services) <br/> |否  <br/> |是  <br/> |是  <br/> |
|[郵件追蹤](reporting-and-message-trace.md#message-trace) <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是  <br/> |
|[Microsoft 365 系統管理中心存取](administration-and-management-eop.md#access-to-the-office-365-admin-center) <br/> |是  <br/> |有  <br/> |可以  <br/> |
|[存取 Exchange 系統管理中心](administration-and-management-eop.md#access-to-the-exchange-admin-center) (EAC)  <br/> |是  <br/> |有  <br/> |可以  <br/> |
|[遠端 Windows PowerShell 存取](administration-and-management-eop.md#remote-windows-powershell-access) <br/> |是<sup>2</sup> <br/> |是  <br/> |可以  <br/> |
   
> [!NOTE]
> <sup>1</sup>郵件使用者會定義為 「 信箱 」，和連同外部郵件連絡人可以新增、 移除，並直接在 Exchange 系統管理中心 (EAC) 或管理。 <br/><sup>2</sup>否 RBAC 自訂。只有系統管理員角色。 <br/> <sup>3</sup>可檢視受管理的網域，且可在 EAC 中編輯網域類型。所有其他網域管理必須完成 Microsoft 365 系統管理中心。 <br/><sup>4</sup>提供彈性的條件和動作不同 EOP 與 Exchange Online 之間。如需可用的條件和動作在 EOP 中的清單，請參閱[傳輸規則條件](https://go.microsoft.com/fwlink/p/?LinkId=320392)和[傳輸規則動作](https://go.microsoft.com/fwlink/p/?LinkId=320393)。如需可用的準則與 Exchange Online 中的動作的清單，請參閱[傳輸規則條件](https://go.microsoft.com/fwlink/p/?LinkId=320394)和[傳輸規則動作](https://go.microsoft.com/fwlink/p/?LinkId=320395)。 <br/><sup>5</sup> EOP 稽核報告是 Exchange Online 稽核報告，但不包括信箱的相關資訊的子集。 <br/> <sup>6</sup> DLP 原則祕訣不適用於 Exchange Enterprise CAL with Services 客戶。<br/><sup>7</sup>預設內容篩選動作是要將垃圾郵件移至 [收件者的垃圾郵件] 資料夾。這與內部部署信箱搭配使用，您也必須設定兩個 Exchange 傳輸規則來偵測垃圾郵件標頭新增 EOP 的內部部署伺服器上。如需詳細資訊，請參閱[確定垃圾郵件會路由傳送至每一個使用者的垃圾郵件] 資料夾](https://go.microsoft.com/fwlink/p/?LinkId=320396)。 <br/><sup>8</sup>是供其信箱透過 EOP、 篩選和推出可用以 Exchange Online 客戶的 Exchange Server 2013 Service Pack 1 (SP1) 客戶這項功能。 <br/><sup>9</sup> EOP 報告是 Exchange Online 報告，但不包括信箱的相關資訊的子集。 <br/><sup>10</sup>包含 DLP 報告。 <br/><sup>第 11</sup> Exchange Enterprise CAL with Services 客戶應該選取**Exchange Online**服務而不是**Exchange Online Protection**服務安裝此活頁簿。 <br/><sup>12</sup>支援的內部部署客戶購買 Azure 資訊保護及使用 Exchange Online Protection 路由傳送到 Exchange Online 電子郵件。 <br/> <sup>13</sup>掃描輸入及輸出郵件，但未掃描從組織中寄件者傳送至您組織中的收件者的內部郵件。 <br/><sup>14</sup>可用述詞和動作不同 EOP 與 Exchange Online 之間。 <br/> <sup>15</sup> 混合式安裝程式不能透過混合式精靈使用，但您可以手動設定 (如果您有 Exchange SP1)。 