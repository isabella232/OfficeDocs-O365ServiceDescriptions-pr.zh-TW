---
title: 適用于美國政府環境的 Exchange Online
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 本文概要說明美國政府雲端與商業性雲端之間的功能差異，如 Exchange Online 服務說明所示。
ms.openlocfilehash: 1c0b3c415b388f1c84c49e09aae0ed243e436b6f
ms.sourcegitcommit: 4ef127c684c8a6ad630a2b9bce2fe3fb25aa3e25
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 08/16/2021
ms.locfileid: "58363609"
---
# <a name="exchange-online-for-us-government-environments"></a>適用于美國政府環境的 Exchange Online

本文概要說明美國政府雲端與商業性雲端之間的功能差異，如[Exchange Online 服務說明](../../exchange-online-service-description/exchange-online-service-description.md)所示。 Exchange Online 適用于政府社群雲端 (GCC) 、GCC 高和國防部門 (DoD) 環境。

如需政府雲端（包括資格和購買）的詳細資訊，請參閱[Microsoft 365 政府–如何購買](./microsoft-365-government-how-to-buy.md)。 若要比較 Office 365 政府版計畫，請參閱[Office 365 政府版計畫](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)。

若要在管理網路連線時瞭解必要的端點，請參閱[Office 365 美國政府 GCC 高階端點](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business)或[Office 365 美國政府 DoD 端點](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)。

除了享受 Office 365 的功能和功能之外，組織還會受益于美國政府雲端環境的下列功能：

- 您的組織的客戶內容會與商業 Office 365 服務中的客戶內容有邏輯隔離。

- 貴組織的客戶內容儲存于美國的內省。

- 只有經過篩選的 Microsoft 人員可以存取組織的客戶內容。

- 政府雲端環境符合美國公共部門客戶通常需要的認證和資格鑒定。

我們的一般目的是將所有 Exchange 商業功能和功能提供給政府雲端環境。 也就是說，由於政府雲端客戶的需求，有些功能無法使用。 其他功能會進入政府環境，但是尚未提供。 請參閱下列各節以瞭解政府雲端環境中的功能可用性。

## <a name="exchange-online-features"></a>Exchange Online 功能

下表說明 GCC、GCC 高及 DoD 環境中是否可使用指定的 Exchange Online 功能。 當支援陳述 (或缺乏) 時，會提供其他內容的細微差別。<br><br>

| 功能 | GCC | GCC High | DoD | 主要考慮 |
|:-----|:-----|:-----|:-----|:-----|
|**[規劃及部署](../../exchange-online-service-description/planning-and-deployment.md)**|||||
|支援混合部署|是|是|是|若要與內部部署 Exchange Server 共存，Microsoft 必須至少安裝一個 Exchange Server 2013 Client Access Server (或 Exchange Server 2016。 ) 。 不支援 Exchange Server 2010 及更舊版本。|
|支援 IMAP 移轉|是|是|是||
|支援完全移轉|是|是|是||
|支援階段性移轉|是|是|是|GCC 高和 DoD 不支援 GSuite 遷移。 如需詳細資訊，請參閱 <a href="/exchange/mailbox-migration/perform-g-suite-migration">執行 GSuite 遷移</a>。|
|**[權限](../../exchange-online-service-description/permissions.md)**|**GCC**|**GCC High**|**DoD**|**主要考慮**|
|角色型權限|是|是|是||
|角色群組|是|是|是||
|角色指派原則|是|是|是||
|**[郵件原則及合規性](../../exchange-online-service-description/message-policy-and-compliance.md)**|**GCC**|**GCC High**|**DoD**|**主要考慮**|
|封存 Exchange Online 式信箱|是|是|是||
|雲端式封存內部部署信箱|是|是|是||
|通訊記錄管理 (MRM)  |是|是|是||
|手動保留原則、標籤和標記 |是|是|是||
|靜態資料的加密 (BitLocker)|是|是|是||
|使用 Azure 資訊保護 的 IRM|是|是|是|如需 GCC 高及 DoD 中 AIP 限制的詳細資訊，請參閱<a href="/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description">Azure 資訊保護進階版政府服務描述</a>。<br><br>Azure 資訊保護並未包含在 G1/F3 中，但可以以個別的附加元件形式購買，並且會啟用支援的資訊版權管理 (IRM) 功能。 有些 Azure 資訊保護功能需要訂閱 Office 365 專業增強版，但不包含 Office 365 政府版 G1 或 Office 365 政府版 F3。|
|使用 Windows Server AD RMS 的 IRM|是|是|是|Windows Server ADRMS 是內部部署伺服器，必須個別採購並管理，以便啟用支援的 IRM 功能。|
|Office 365 郵件加密|是|是|是|請參閱本文中[GCC 高/DoD 界限內的 Office 365 郵件加密行為](#office-365-message-encryptionbehavior-across-gcc-highdod-boundary)，以及<a href="/microsoft-365/compliance/ome-version-comparison#unique-characteristics-of-office-365-message-encryption-in-a-gcc-high-deployment">Office 365 郵件加密的獨特特性，在</a>GCC 高/Office 365 郵件加密和非 GCC 的高/DoD 使用者之間傳送郵件時，其檔行為的細微差別。|
|客戶金鑰|是|是|是|需要 G5 服務方案。|
|S/MIME|是|是|是||
|就地保留與訴訟暫止|是|是|是|需要 G3 或 G5 服務方案。|
|就地 eDiscovery|是|是|是||
|郵件流程規則|是|是|是||
|資料外洩防護|是|是|是|需要 G3 或 G5 服務方案。|
|日誌|是|是|是||
|**[反垃圾郵件和反惡意程式碼防護](../../exchange-online-service-description/anti-spam-and-anti-malware-protection.md)**|**GCC**|**GCC High**|**DoD**|**主要考慮**|
|內建反垃圾郵件保護|是|是|是||
|自訂反垃圾郵件原則|是|是|是||
|內建反惡意程式碼保護|是|是|是||
|自訂反惡意程式碼原則|是|是|是||
|隔離 - 系統管理員管理|是|是|是||
|隔離 - 使用者自我管理|是|是|是||
|適用於 Office 365 的 Microsoft Defender|是|是|是|需要 G5 Service plan (或購買附加元件) 。<br><br>在 GCC 高及 DoD 中，使用者和網域模擬和欺騙智慧的反網路釣魚仍無法使用。|
|**[郵件流程](../../exchange-online-service-description/mail-flow.md)**|**GCC**|**GCC High**|**DoD**|**主要考慮**|
|自訂輸出郵件的路由|是|是|是||
|與信任的合作夥伴間的安全傳訊|是|是|是||
|條件式郵件路由|是|是|是||
|新增合作夥伴到輸入安全清單|是|是|是||
|混合電子郵件路由|是|是|是||
|**[收件者](../../exchange-online-service-description/recipients.md)**|**GCC**|**GCC High**|**DoD**|**主要考慮**|
|容量警示|是|是|是||
|雜亂資料|是|是|是||
|MailTips|是|是|是||
|委派存取|是|是|是||
|收件匣規則|是|是|是||
|連結帳戶|是|否|否|因為對協力廠商服務的輸出連線限制，所以 GCC 高或 DoD 中不支援此功能。 如需受影響功能的相關資訊，請參閱本文中 [協力廠商服務的](#connectivity-with-third-party-services) 連線。|
|非使用中的信箱|是|是|是|需要 G3 或 G5 服務方案。|
|離線通訊錄|是|是|是||
|通訊錄原則|是|是|是||
|階層式通訊錄|是|是|是||
|通訊清單和全域通訊清單|是|是|是||
|Office 365 群組|是|是|是|GCC 高環境和 DoD 環境不支援來賓存取 Office 365 群組。 如需詳細資訊，請參閱 <a href="/azure/azure-government/documentation-government-services-securityandidentity">Azure 政府安全性 + 身分識別</a>。|
|通訊群組|是|是|是||
|外部連絡人 (全域)|是|是|是|受限於 GCC 高和 DoD 環境中的組織關聯性共同作業限制。 |
|社交網路的連絡人連結|是|否|否|GCC 高或 DoD 不支援此功能。|
|資源信箱|是|是|是||
|會議室管理|是|是|是||
|外出回覆|是|是|是||
|網際網路行事曆共用|是|否|否|在 GCC 高，網際網路行事曆發佈/共用可用於 GCC 高使用者共用的行事曆的輸入連線，但不會 GCC 高使用者連線到 GCC 高的共用行事曆。<br><br>在 DoD 中–由於輸入/輸出連線允許在該環境中列出的需求，因此不支援網際網路行事曆共用。|
|**[報告功能和疑難排解工具](../../exchange-online-service-description/reporting-features-and-troubleshooting-tools.md)**|**GCC**|**GCC High**|**DoD**|**主要考慮**|
|Microsoft 365 系統管理中心報告|是|是|否|報表不可用於 DoD。 請參閱《 Office 365 美國政府服務說明」中的 [<a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">平臺功能</a>] 一節，以取得更新/目前的可用性。|
|Web 服務報告|是|是|否|報表不可用於 DoD。 請參閱《 Office 365 美國政府服務說明」中的 [<a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">平臺功能</a>] 一節，以取得更新/目前的可用性。|
|郵件追蹤|是|是|是||
|稽核報告|是|是|否|報表不可用於 DoD。 請參閱《 Office 365 美國政府服務說明」中的 [<a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">平臺功能</a>] 一節，以取得更新/目前的可用性。|
|整合通訊報告|是|否|否||
|**[共用和協同合作](../../exchange-online-service-description/sharing-and-collaboration.md)**|**GCC**|**GCC High**|**DoD**|**主要考慮**|
|同盟共用 (包括行事曆發佈) |是|是|是|GCC 高和 DoD 皆存在限制。 請參閱本文中 [Free/Busy 同盟](#freebusy-federation) 。|
|網站信箱|是|是|是||
|公用資料夾|是|是|是||
|**[用戶端和行動裝置](../../exchange-online-service-description/clients-and-mobile-devices.md)**|**GCC**|**GCC High**|**DoD**|**主要考慮**|
|網頁上的 To Do|是|否|否||
|Windows 版 Outlook|是|是|是|為了符合 GCC 高和 DoD 規範的需求，您必須執行最低版本1803的 Office 365 專業增強版。 Office 365 專業增強版不包含 G1 或 F3。|
|Outlook 網頁版<sup>1</sup>|是|是|是||
|Mac 版 Outlook|是|是|是|為了符合 GCC 高和 DoD 規範的需求，您必須執行最低版本1803的 Office 365 專業增強版。 Office 365 專業增強版不包含 G1 或 F3。|
|iOS 和 Android 版 Outlook|是|是|是||
|Exchange ActiveSync|是|是|是||
|Microsoft 365 的基本行動性和安全性|是|否|否||
|POP 與 IMAP|是|是|是||
|SMTP|是|是|是||
|EWS 應用程式支援|是|是|是||
|**[語音訊息服務](../../exchange-online-service-description/voice-message-services.md)**|**GCC**|**GCC High**|**DoD**|**主要考慮**|
|語音信箱|否|否|否|不支援整合內部部署 IP-PBX 具有 Exchange Online 整合通訊的系統。|
|語音信箱與第三方傳真之間的整合|否|否|否|不支援整合內部部署 IP-PBX 具有 Exchange Online 整合通訊的系統。|
|第三方語音信箱互通性|否|否|否|不支援整合內部部署 IP-PBX 具有 Exchange Online 整合通訊的系統。|
|商務用 Skype 整合|是|是|是||
|**[高可用性和業務連續性](../../exchange-online-service-description/high-availability-and-business-continuity.md)**|**GCC**|**GCC High**|**DoD**|**主要考慮**|
|資料中心的信箱複寫|是|是|是||
|復原已刪除的信箱|是|是|是||
|復原已刪除的項目|是|是|是||
|單一項目復原|是|是|是||
|**[互通性、連線能力和相容性](../../exchange-online-service-description/interoperability-connectivity-and-compatibility.md)**|**GCC**|**GCC High**|**DoD**|**主要考慮**|
|OWA 和 Outlook 中的目前狀態|是|是|是||
|SharePoint 互通性|是|是|是||
|EWS 連線支援|是|是|是||
|SMTP 轉送支援|是|是|是||
|**[Exchange Online 設定與管理](../../exchange-online-service-description/exchange-online-setup-and-administration.md)**|**GCC**|**GCC High**|**DoD**|**主要考慮**|
|Microsoft Office 365 入口網站存取|是|是|否|報表不可用於 DoD。 請參閱《 Office 365 美國政府服務說明」中的 [<a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">平臺功能</a>] 一節，以取得更新/目前的可用性。|
|Microsoft 365 系統管理中心存取|是|是|否|報表不可用於 DoD。 請參閱《 Office 365 美國政府服務說明」中的 [<a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">平臺功能</a>] 一節，以取得更新/目前的可用性。|
|Exchange 系統管理中心存取|是|是|是||
|遠端 Windows PowerShell 存取|是|是|是||
|用於行動裝置的 ActiveSync 原則|是|是|是||
|使用報告|是|是|否|報表不可用於 DoD。 請參閱《 Office 365 美國政府服務說明」中的 [<a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">平臺功能</a>] 一節，以取得更新/目前的可用性。|
|**[擴展服務 - 自訂、增益集和資源](../../exchange-online-service-description/exchange-online-service-description.md)**|**GCC**|**GCC High**|**DoD**|**主要考慮**|
|Outlook 增益集和 Outlook MAPI|是|是|是|只有部分 OWA 和 Outlook 增益集可用 GCC 高及 DoD。 請參閱本文中[Outlook 和 Outlook Web App 中的增益集](#add-insin-outlook-and-outlook-web-app)。|

<sup>1</sup> Outlook 在案例中 Outlook Windows 因跨界限限制而無法顯示受 IRM 保護的郵件時， (GCC 高/非 GCC 高案例) 。

## <a name="feature-nuances-within-gcc-high-and-dod-environments"></a>GCC 高和 DoD 環境中的功能細微差別

### <a name="connectivity-with-third-party-services"></a>與協力廠商服務的連線能力  

GCC 高和 DoD 環境都是限制的環境，需要明確核准和設定輸出連線。 此外，Microsoft 無法容納允許從這些環境輸出存取商業雲端服務 (商業 Office 365、Google GSuite、Amazon Web 服務等) 的要求。

由於這些限制，通常不支援依賴此輸出連線的來自 GCC 高/DoD 環境的功能，包括：

- 連線的帳戶-使用者無法新增/同步處理帳戶 (Google、POP/IMAP 等等) 。

- 支援協力廠商檔案儲存提供者-您可以在各種 Outlook 用戶端中存取使用者的商務用 OneDrive *DoD GCC* 帳戶，以進行附加/共用檔的目的。 無法新增 (Dropbox、Box、Google 雲端硬碟) 的協力廠商儲存體帳戶。

- 與社交網路的連線，如 Facebook 或 LinkedIn。

### <a name="azure-active-directory-b2b-collaboration"></a>Azure Active DirectoryB2B 共同作業

Azure Active Directory目前只有位於 Azure US 政府雲端且支援 B2B 共同作業的組織，才支援共同作業 B2B 協同作業

此外，GCC 高 DoD 及環境不支援 B2B 使用者當作 Office 365 群組中的來賓。 

如需詳細資訊及最新的更新，請參閱 [Azure 政府安全性 + 身分識別](/azure/azure-government/documentation-government-services-securityandidentity)。

### <a name="office-365-message-encryption-behavior-across-gcc-highdod-boundary"></a>GCC 高/DoD 邊界的 Office 365 郵件加密行為

如果您打算在 GCC 高環境中使用 Office 365 郵件加密，請注意這些收件者經驗的獨特特性：  

- 將加密的電子郵件從 GCC 高或 DoD 傳送至相同環境中的收件者時：
    
    - 寄件者可以在 Outlook 針對電腦及 Mac 和 Outlook 網頁版手動加密電子郵件，或組織可以設定使用 Exchange 郵件流程規則來加密電子郵件的原則。
    
    - GCC 高/DoD 內的收件者會收到與其他所有 Office 365 使用者相同的電腦及 Mac 和 Outlook 網頁版 Outlook 的內文讀取體驗。

<!-- end list -->

- 將加密的電子郵件從 GCC 高或 DoD 傳送至該環境以外的收件者 (（包括 GCC 和商業) ）：
    
    - GCC 高/DoD 內的寄件者可以在 GCC 的高/DoD 界限外傳送加密的電子郵件。
    
    - 所有在 GCC 高/DoD 之外的收件者（包括商業性 Office 365 使用者、Outlook .com 使用者及其他電子郵件提供者的其他使用者）都會收到包裝郵件。 此包裝郵件會將收件者重新導向至 OME 入口網站，以便收件者可以閱讀和回復郵件。

如需詳細資訊及最新的更新，請參閱 [比較版本的 OME](/microsoft-365/compliance/ome-version-comparison)。

### <a name="freebusy-federation"></a>Free/Busy 同盟

同盟共用（包括空閒/忙碌資訊）目前受限於 DoD 環境中的數個重要限制。

在 GCC 高環境：

- 同盟信任 (包括雙向空閒/忙碌共用) GCC 高、GCC 和商業雲彩中的承租人，以及透過混合共存 (Exchange 2013 或更新版本) 。

在 DoD 環境中：

  - 同盟信任 (包括空閒/忙碌共用) 目前只支援 DoD 環境中的承租人。 DoD 承租人和 GCC、GCC 高或商業承租人之間不支援此功能。

### <a name="client-configuration"></a>用戶端設定

部署及設定 Office ProPlus (包括 Outlook) ，請執行其他步驟。 如需這些步驟的詳細說明，請參閱[在 GCC 高或 DoD 環境中部署 Microsoft 365 Apps 企業版的指導](/deployoffice/deploy-microsoft-365-apps-gcc-high-dod)方針。

GCC 高端及 DoD 環境也可使用 iOS 和 Android 的 Outlook。 若要深入瞭解這些環境中的功能限制和管理，請參閱[政府社群雲端中的 iOS 和 Android 的使用 Outlook](/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud)。

### <a name="add-ins-in-outlook-and-outlook-web-app"></a>Outlook 和 Outlook Web App 中的增益集  

只有部分 OWA 和 Outlook 增益集可用 GCC 高及 DoD。 「我的範本」和「建議會議」是可用的，且預期可正常運作。 只支援五個預設 OWA 增益集。 您可以整合協力廠商應用程式，但這些整合並未涵蓋 GCC 高或 DoD 的 Microsoft 規範承諾。 客戶應熟悉協力廠商的資料處理做法和合規性承諾，才能設定其組織的附加元件。

## <a name="feature-nuances-within-gcc-environments-for-microsoft-to-do"></a>Microsoft To Do GCC 環境中的功能細微差別

| 功能 | 描述 | WW | GCC 中的可用性 |
|:-----|:-----|:-----|:-----|
|支援的平臺|Web、Android、iOS、Mac Windows|全部|僅限網頁|
|M365 hub 支援|與 Outlook、Teams、規劃器的整合|全部|Outlook、Planner (Teams 可搭配 Teams 工作應用程式使用) |
|Wunderlist遷移|允許 wunderlist 使用者將資料移轉至網頁上的 To Do|是|否|
|推播通知|將推播通知傳送給使用者的提醒等等。|是|否|
|Helpshift 支援|使用 helpshift 介面建立支援要求|是|否|
|My Day|規劃您的日常|是|是|
|計畫清單|查看具有到期日的所有任務|是|是|
|指派給您的清單|在您的共用清單、Planner 或 WXP 中指派給您的所有工作 (未來) |是|是|
|已標記的電子郵件|查看以 outlook 標記為任務的電子郵件|是|是|
|多帳戶支援|在一個窗格中使用家用和 office 帳戶|是|是|
|共用清單|與相同組織中的同事共用清單|是|是|
|跨租使用者共用|共用組織外部的工作清單|是|否|
|提醒及週期|設定任務的提醒 |是|是|

* 這兩種環境都可使用任何其他未提及的功能。