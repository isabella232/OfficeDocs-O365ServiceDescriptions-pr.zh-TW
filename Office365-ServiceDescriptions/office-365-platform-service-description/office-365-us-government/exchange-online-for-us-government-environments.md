---
title: 適用于美國政府環境的 Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 本文概要說明美國政府雲端與商業性雲端之間的功能差異（如 Exchange Online 服務說明所列）。
ms.openlocfilehash: e8e552076f7e318db9a4de17ad605d3c260b2295
ms.sourcegitcommit: 09b52ff24e7153457c7b4f775ea809079103f6e9
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 11/10/2020
ms.locfileid: "48988080"
---
# <a name="exchange-online-for-us-government-environments"></a>適用于美國政府環境的 Exchange Online

本文概要說明美國政府雲端與商業性雲端之間的功能差異（如 [Exchange Online 服務說明](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-service-description)所列）。 Exchange Online 可供政府社區雲端 (GCC) 、GCC High 和國防部門 (DoD) 環境。

如需政府雲端（包括資格和購買）的詳細資訊，請參閱 [Microsoft 365 政府-如何購買](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy)。 若要比較 Office 365 政府方案，請參閱 [office 365 政府方案](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)。

若要深入瞭解管理網路連線時所需的端點，請參閱 [office 365 美國政府版高端點](https://docs.microsoft.com/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) 或 [Office 365 美國政府 DoD 端點](https://docs.microsoft.com/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)。

除了享受 Office 365 的功能之外，組織還會受益于美國政府雲端環境獨有的下列功能：

- 貴組織的客戶內容會在邏輯上與商業 Office 365 服務中的客戶內容隔離。

- 貴組織的客戶內容儲存于美國的內省。

- 只有經過篩選的 Microsoft 人員可以存取組織的客戶內容。

- 政府雲端環境符合美國公共部門客戶通常需要的認證和資格鑒定。

我們的一般目的是將所有 Exchange 商業功能和功能提供給政府雲端環境。 也就是說，由於政府雲端客戶的需求，有些功能無法使用。 其他功能會進入政府環境，但是尚未提供。 請參閱下列各節以瞭解政府雲端環境中的功能可用性。

## <a name="exchange-online-features"></a>Exchange Online 功能

下表說明 GCC、GCC High 和 DoD 環境中是否有指定的 Exchange Online 功能。 當支援陳述 (或缺乏) 時，會提供其他內容的細微差別。<br><br>

| 功能 | GCC | GCC High | DoD | 主要考慮 |
|:-----|:-----|:-----|:-----|:-----|
|**[規劃及部署](../../exchange-online-service-description/planning-and-deployment.md)**|||||
|支援混合部署|是|是|是|若要與 Exchange Server 內部部署共存，Microsoft 需要安裝至少一個 Exchange Server 2013 Client Access Server (或 Exchange Server 2016 ) 。 不支援 Exchange Server 2010 和更舊版本。|
|支援 IMAP 移轉|是|是|是||
|支援完全移轉|是|是|是||
|支援階段性移轉|是|是|是|GSuite 遷移不支援 GCC High 和 DoD。 如需詳細資訊，請參閱 <a href="https://docs.microsoft.com/exchange/mailbox-migration/perform-g-suite-migration">執行 GSuite 遷移</a>。|
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
|使用 Azure 資訊保護 的 IRM|是|是|是|如需有關 AIP 在 GCC High 和 DoD 中限制的詳細資訊，請參閱 <a href="https://docs.microsoft.com/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description">Azure 資訊保護 [特優政府服務說明</a>]。<br><br>Azure 資訊保護並未包含在 G1/F3 中，但可以以個別的附加元件形式購買，並且會啟用支援的資訊版權管理 (IRM) 功能。 部分 Azure 資訊保護功能需要訂閱 Office 365 ProPlus，但不包含在 Office 365 政府版 G1 或 Office 365 政府 F3 中。|
|使用 Windows Server AD RMS 的 IRM|是|是|是|Windows Server AD RMS 是內部部署伺服器，必須個別採購並管理，以便啟用支援的 IRM 功能。|
|Office 365 郵件加密|是|是|是|請參閱本文章中的《 [office 365 郵件加密行為](#office-365-message-encryptionbehavior-across-gcc-highdod-boundary) 」和 gcc 高/DoD 界限內的 Office <a href="https://docs.microsoft.com/microsoft-365/compliance/ome-version-comparison#unique-characteristics-of-office-365-message-encryption-in-a-gcc-high-deployment">365 郵件</a>加密，以及在 gcc 高/DoD 和非 GCC DoD 使用者之間傳送郵件時，其檔行為會細微變化的 office 365 郵件加密。|
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
|進階威脅防護|是|是|是|需要 G5 Service plan (或購買附加元件) 。<br><br>在 GCC High 和 DoD 中，尚未提供使用者和網域模擬和欺騙情報的反網路釣魚。|
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
|連結帳戶|是|否|否|由於對協力廠商服務的輸出連線限制，所以在 GCC 高或 DoD 中不支援此功能。 如需受影響功能的相關資訊，請參閱本文中 [協力廠商服務的](#connectivity-with-third-party-services) 連線。|
|非使用中的信箱|是|是|是|需要 G3 或 G5 服務方案。|
|離線通訊錄|是|是|是||
|通訊錄原則|是|是|是||
|階層式通訊錄|是|是|是||
|通訊清單和全域通訊清單|是|是|是||
|Office 365 群組|是|是|是|在 GCC 高端和 DoD 環境中，不支援來賓存取 Office 365 群組。 如需詳細資訊，請參閱 <a href="https://docs.microsoft.com/azure/azure-government/documentation-government-services-securityandidentity">Azure 政府安全性 + 身分識別</a>。|
|通訊群組|是|是|是||
|外部連絡人 (全域)|是|是|是|受限於 GCC 高和 DoD 環境中的組織關聯性共同作業限制。 |
|社交網路的連絡人連結|是|否|否|在 GCC High 或 DoD 中，不支援此功能。|
|資源信箱|是|是|是||
|會議室管理|是|是|是||
|外出回覆|是|是|是||
|網際網路行事曆共用|是|否|否|在 GCC 高版中，網際網路行事曆發佈/共用可用於與 GCC 高使用者共用之行事曆的輸入連線，但不適用於連線到超過 GCC 之共用行事曆的 GCC 高使用者。<br><br>在 DoD 中–由於輸入/輸出連線允許在該環境中列出的需求，因此不支援網際網路行事曆共用。|
|**[報告功能和疑難排解工具](../../exchange-online-service-description/reporting-features-and-troubleshooting-tools.md)**|**GCC**|**GCC High**|**DoD**|**主要考慮**|
|Microsoft 365 系統管理中心報告|是|是|否|報表不可用於 DoD。 請參閱 Office 365 美國政府服務說明的 <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">平臺功能</a> 一節，以取得更新/目前的可用性。|
|Web 服務報告|是|是|否|報表不可用於 DoD。 請參閱 Office 365 美國政府服務說明的 <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">平臺功能</a> 一節，以取得更新/目前的可用性。|
|郵件追蹤|是|是|是||
|稽核報告|是|是|否|報表不可用於 DoD。 請參閱 Office 365 美國政府服務說明的 <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">平臺功能</a> 一節，以取得更新/目前的可用性。|
|整合通訊報告|是|否|否||
|**[共用和協同合作](../../exchange-online-service-description/sharing-and-collaboration.md)**|**GCC**|**GCC High**|**DoD**|**主要考慮**|
|同盟共用 (包括行事曆發佈) |是|是|是|在同一個 GCC 高和 DoD 都存在限制。 請參閱本文中 [Free/Busy 同盟](#freebusy-federation) 。|
|網站信箱|是|是|是||
|公用資料夾|是|是|是||
|**[用戶端和行動裝置](../../exchange-online-service-description/clients-and-mobile-devices.md)**|**GCC**|**GCC High**|**DoD**|**主要考慮**|
|若要執行 Web|是|否|否||
| Outlook for Windows|是|是|是|為了符合 GCC 高和 DoD 規範的需求，您必須執行最低版本1803的 Office 365 ProPlus。 Office 365 ProPlus 不含 G1 或 F3。|
|Outlook 網頁版|是|是|是||
|Mac 版 Outlook|是|是|是|為了符合 GCC 高和 DoD 規範的需求，您必須執行最低版本1803的 Office 365 ProPlus。 Office 365 ProPlus 不含 G1 或 F3。|
|iOS 和 Android 版 Outlook|是|是|是||
|Exchange ActiveSync|是|是|是||
|Microsoft 365 的基本行動性和安全性|是|否|否||
|POP 與 IMAP|是|是|是||
|SMTP|是|是|是||
|EWS 應用程式支援|是|是|是||
|**[語音訊息服務](../../exchange-online-service-description/voice-message-services.md)**|**GCC**|**GCC High**|**DoD**|**主要考慮**|
|語音信箱|否|否|否|不支援整合內部部署 IP-PBX 系統與 Exchange Online 整合通訊。|
|語音信箱與第三方傳真之間的整合|否|否|否|不支援整合內部部署 IP-PBX 系統與 Exchange Online 整合通訊。|
|第三方語音信箱互通性|否|否|否|不支援整合內部部署 IP-PBX 系統與 Exchange Online 整合通訊。|
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
|Microsoft Office 365 入口網站存取|是|是|否|報表不可用於 DoD。 請參閱 Office 365 美國政府服務說明的 <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">平臺功能</a> 一節，以取得更新/目前的可用性。|
|Microsoft 365 系統管理中心存取|是|是|否|報表不可用於 DoD。 請參閱 Office 365 美國政府服務說明的 <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">平臺功能</a> 一節，以取得更新/目前的可用性。|
|Exchange 系統管理中心存取|是|是|是||
|遠端 Windows PowerShell 存取|是|是|是||
|用於行動裝置的 ActiveSync 原則|是|是|是||
|使用報告|是|是|否|報表不可用於 DoD。 請參閱 Office 365 美國政府服務說明的 <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">平臺功能</a> 一節，以取得更新/目前的可用性。|
|**[擴展服務 - 自訂、增益集和資源](../../exchange-online-service-description/exchange-online-service-description.md)**|**GCC**|**GCC High**|**DoD**|**主要考慮**|
|Outlook 增益集和 Outlook MAPI|是|是|是|在 GCC High 和 DoD 中，只有一部分 OWA 和 Outlook 增益集可用。 請參閱本文中 [outlook 和 Outlook Web App 中的增益集](#add-insin-outlook-and-outlook-web-app) 。|

## <a name="feature-nuances-within-gcc-high-and-dod-environments"></a>GCC 高和 DoD 環境中的功能細微差別

### <a name="connectivity-with-third-party-services"></a>與協力廠商服務的連線能力  

GCC 高和 DoD 環境都是限制的環境，需要明確核准和設定輸出連線。 此外，Microsoft 無法容納允許從這些環境輸出存取 (商務用 Office 365、Google GSuite、Amazon Web 服務等等) 的要求。

由於這些限制，通常不支援依賴此輸出連線的來自 GCC 高端/DoD 環境的功能，包括：

- 連線的帳戶-使用者無法新增/同步處理帳戶 (Google、POP/IMAP 等等) 。

- 支援協力廠商檔案儲存提供者-在不同的 Outlook 用戶端中，只有使用者的 OneDrive 商務 *DoD* 帳戶可以存取，以進行附加/共用檔案的目的。 無法新增 (收存箱、Box、Google Drive) 的協力廠商儲存體帳戶。

- 與社交網路的連線，如 Facebook 或 LinkedIn。

### <a name="azure-active-directory-b2b-collaboration"></a>Azure Active Directory B2B 協同作業

目前只有位於 Azure US 政府雲端且支援 B2B 共同作業的組織之間，才支援 azure Active Directory B2B 協同作業。

此外，在 GCC 的高和 DoD 環境中，不支援將使用者當做 Office 365 群組中的來賓 B2B。 

如需詳細資訊及最新的更新，請參閱 [Azure 政府安全性 + 身分識別](https://docs.microsoft.com/azure/azure-government/documentation-government-services-securityandidentity)。

### <a name="office-365-message-encryption-behavior-across-gcc-highdod-boundary"></a>跨 GCC 高/DoD 界限的 Office 365 郵件加密行為

如果您在 GCC 高環境中使用 Office 365 郵件加密，請注意這些收件者經驗的獨特特性：  

- 從 GCC 高或 DoD 將加密電子郵件傳送至相同環境中的收件者時：
    
    - 寄件者可以手動加密 Outlook 中的電子郵件和 outlook 的 outlook 和 Mac 和 Outlook 網頁版，或組織可以設定使用 Exchange 郵件流程規則來加密電子郵件的原則。
    
    - 在 GCC 內高/DoD 內的收件者會在 Outlook 中，以電腦及 Mac 和 Outlook 網頁的方式接收相同的內嵌讀取體驗，就像所有其他 Office 365 使用者。

<!-- end list -->

- 將加密的電子郵件從 GCC 高或 DoD 傳送至該環境以外的收件者時 (包括 GCC 和商業銀行) ：
    
    - GCC 內高/DoD 內的寄件者可以在 GCC 的高/DoD 界限外傳送加密的電子郵件。
    
    - 所有在 GCC 高/DoD 之外的收件者（包括商業 Office 365 使用者、Outlook.com 使用者和其他電子郵件提供者的其他使用者）都會收到包裝郵件。 此包裝郵件會將收件者重新導向至 OME 入口網站，以便收件者可以閱讀和回復郵件。

如需詳細資訊及最新的更新，請參閱 [比較版本的 OME](https://docs.microsoft.com/microsoft-365/compliance/ome-version-comparison)。

### <a name="freebusy-federation"></a>Free/Busy 同盟

同盟共用（包括空閒/忙碌資訊）目前受制于 GCC 高和 DoD 環境中的數個重要限制。

在 GCC 的高環境中：

- 在 GCC 中的承租人和混合共存 (Exchange 2013 或更新) 版本之間，都支援 (的同盟信任（包括雙向空閒/忙碌共用) ）。

- 在 GCC High 和 GCC 或 Office 365 商業銀行中的承租人之間不支援同盟共用。 目前不允許使用來自 GCC 高環境的輸出連線到商用雲端 (包括 GCC 和 Office 365 商用) 。 因此，GCC 的高使用者無法對 GCC/商業銀行進行必要的輸出要求，以存取共用的行事曆資訊。

在 DoD 環境中：

  - 同盟信任 (包括空閒/忙碌共用) 目前只支援 DoD 環境中的承租人。 DoD 承租人和 GCC 或商業承租人之間不支援此功能。

### <a name="client-configuration"></a>用戶端設定

部署和設定 Office ProPlus (包括 Outlook) 的其他步驟。 如需這些步驟的詳細說明，請參閱 [在 GCC 高或 DoD 環境中部署適用于企業的 Microsoft 365 應用程式的指導](https://docs.microsoft.com/deployoffice/deploy-microsoft-365-apps-gcc-high-dod)方針。

IOS 和 Android 的 Outlook 也可用於 GCC 高和 DoD 環境。 若要深入瞭解這些環境中的功能限制和管理，請參閱 [使用 Outlook for iOS 和 Android In 政府社區雲端](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud)。

### <a name="add-ins-in-outlook-and-outlook-web-app"></a>Outlook 和 Outlook Web App 中的增益集  

在 GCC High 和 DoD 中，只有一部分 OWA 和 Outlook 增益集可用。 「我的範本」和「建議會議」是可用的，且預期可正常運作。 只支援五個預設 OWA 增益集。 不過，您可以整合協力廠商應用程式，但這些整合不會受到針對 GCC 高或 DoD 的 Microsoft 規範承諾。 客戶應熟悉協力廠商的資料處理做法和合規性承諾，才能設定其組織的附加元件。

## <a name="feature-nuances-within-gcc-environments"></a>在 GCC 環境中的功能細微差別

| 功能 | 描述 | Ww | GCC 中的可用性 |
|:-----|:-----|:-----|:-----|
|支援的平臺|Web、Android、iOS、Mac、Windows|全部|僅限網頁|
|M365 hub 支援|與 Outlook、小組、Planner 的整合|全部|Outlook、Planner (小組可用小組的工作應用程式) |
|Wunderlist 遷移|允許 wunderlist 使用者將資料移轉至執行|是|否|
|推播通知|將推播通知傳送給使用者的提醒等等。|是|否|
|Helpshift 支援|使用 helpshift 介面建立支援要求|是|否|
|My Day|規劃您的日常|是|是|
|計畫清單|查看具有到期日的所有任務|是|是|
|指派給您的清單|所有指派給您的共用清單、Planner 或 WXP (未來的任務) |是|是|
|已標記的電子郵件|查看以 outlook 標記為任務的電子郵件|是|是|
|多帳戶支援|在一個窗格中使用家用和 office 帳戶|是|是|
|共用清單|與相同組織中的同事共用清單|是|是|
|跨租使用者共用|共用組織外部的工作清單|是|否|
|提醒及週期|設定任務的提醒 |是|是|

* 這兩種環境都可使用任何其他未提及的功能。
