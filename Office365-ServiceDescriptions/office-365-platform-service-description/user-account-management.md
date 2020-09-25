---
title: User account management
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-user-account-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: e7616079-5b13-4f1c-99ed-b20174e0808d
description: Microsoft 支援下列方式來建立、管理及驗證使用者。
ms.openlocfilehash: 967d60becc99d55cd188b4623e936b37cb04f7c7
ms.sourcegitcommit: 0f17ea421190f52bf55e530e9374543fd59b8665
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/24/2020
ms.locfileid: "48261545"
---
# <a name="user-account-management"></a>User account management

Microsoft 支援下列方式來建立、管理及驗證使用者。 
  
> [!NOTE]
> 本主題不包含可允許或禁止存取個別 Microsoft 資源的安全性功能資訊 (例如，Microsoft Exchange Online 中的角色型存取控制或設定 Microsoft SharePoint Online) 中的安全性。 如需這些功能的詳細資訊，請參閱 [Exchange online 服務說明](../exchange-online-service-description/exchange-online-service-description.md) 和 [SharePoint 線上服務描述](../sharepoint-online-service-description/sharepoint-online-service-description.md)。 
  
如果您需要可協助您執行系統管理工作的工具相關資訊，請參閱 [tools to Manage Microsoft accounts](https://docs.microsoft.com/office365/enterprise/manage-office-365-accounts)。 若要瞭解如何執行日常管理工作，請參閱 [常見管理](https://docs.microsoft.com/office365/admin/manage/manage)工作。
  
## <a name="need-help-with-signing-in-installing-or-uninstalling-or-canceling-your-subscription"></a>需要有關登入、安裝或卸載或取消訂閱的協助嗎？

取得協助：[簽署](https://support.office.com/article/where-to-sign-in-to-office-365-for-business-e9eb7d51-5430-4929-91ab-6157c5a050b4)  |  [安裝或卸載 office](https://support.office.com/article/download-and-install-or-reinstall-office-365-or-office-2019-on-a-pc-or-mac-4414eaaf-0478-48be-9c42-23adc4716658)  |  [取消 office 365](https://support.office.com/article/Cancel-Office-365-for-business-b1bc0bef-4608-4601-813a-cdd9f746709a)
  
如需其他問題，請造訪 [Microsoft 支援中心](https://support.microsoft.com/contactus/)。 若要取得中國的 21Vianet 運作的 Office 365 的支援，請連絡 [21Vianet 支援小組](https://support.office.com/article/Get-technical-billing-and-subscription-support-for-Office-365-operated-by-21Vianet-671FB12E-F5D8-4CDF-B3E9-E8068A9AA496)。 若要取得 Office 365 Germany 的支援，請連絡 [Office 365 Germany 支援小組](https://support.office.com/article/Get-technical-and-billing-support-for-Office-365-Germany-83ef2266-2543-48d7-a41a-1b56b403a8e9?ui=en-US&amp;rs=en-US&amp;ad=US&amp;fromAR=1)。 
  
## <a name="sign-in-options"></a>登入選項

Microsoft 有兩個系統可用於使用者身分識別：
  
- **工作或學校帳戶 (雲端身分識別) ** -使用者接收 Azure Active Directory 雲端認證（與其他桌面或公司認證不同），以登入 Microsoft 雲端服務。 這是預設也是建議身分識別，以便將部署複雜度降至最低。 工作或學校帳戶的密碼請使用Azure Active Directory [密碼原則](https://docs.microsoft.com/previous-versions/azure/jj943764(v=azure.100))。
    
- 同盟**帳戶 (同盟身分識別) ** -針對具有使用單一登入 (SSO) 之內部部署 Active Directory 的組織中的所有訂閱，使用者可以使用 Active directory 認證來登入 Microsoft 服務。 公司Active Directory 儲存和控制密碼原則。 如需有關 SSO 的資訊，請參閱 [單一登入藍圖](https://docs.microsoft.com/previous-versions/azure/azure-services/hh967643(v=azure.100))。
    
身分類型影響使用者經驗及使用者帳戶管理選項，還有硬體和軟體需求及其他部署考量。
  
### <a name="custom-domains-and-identity-options"></a>自訂網域和身分選項

當您建立新的使用者時，使用者的登入名稱和電子郵件地址會指派給 Microsoft 365 系統管理中心中所設定的預設網域。 若要深入瞭解，請參閱 [新增您的使用者和網域](https://support.office.com/article/Add-your-users-and-domain-to-Office-365-6383f56d-3d09-4dcb-9b41-b5f5a5efd611)。 
  
根據預設，訂閱使用以該帳戶建立的 <*公司名稱* > **onmicrosoft.com**網域。 如果您使用的是以中國公司運作的 Office 365，預設網域是 <*companyname* > **onmsChina.cn**。 如果您使用的是 Office 365 德國，預設網域*是 <* > **onmicrosoft.de**。 您可以將一或多個自訂網域新增至 Microsoft，而不是保留 **onmicrosoft.com** 網域，而且可以指派使用者使用任何驗證的網域登入。 每個使用者的指派網域是將會出現在傳送和接收的電子郵件訊息上的電子郵件地址。 
  
您最多可以主控900個已註冊的網際網路網域，每個網域都以不同的命名空間代表。 
  
針對採用單一登入的組織，網域上的所有使用者都必須使用相同的身份識別系統：雲端身份或同盟身份。 例如，您可以讓一組使用者只需要雲端身分識別，因為他們不會存取內部部署系統，另一組使用者則使用 Microsoft 和內部部署系統。 您可以將兩個網域新增至 Office 365，例如 **contractors.contoso.com** 和 **staff.contoso.com**，並只為其中一個網域設定 SSO。 您可以將整個網域從雲端身分識別轉換為同盟身分識別，或者從同盟身分識別轉換為雲端身分識別。
  
如需 Office 365 之網域相關資訊，請參閱 [網域](domains.md) 服務說明。 
  
## <a name="authentication"></a>驗證

除了使用 SharePoint 線上建立匿名存取的網際網路網站之外，在存取 Microsoft 服務時，使用者必須經過驗證。 
  
- **新式驗證** -新式驗證會透過平臺將 Microsoft 驗證程式庫登入帶入 Office 用戶端應用程式。 如此可啟用類似 Multi-Factor Authentication (MFA)、具備 Office 用戶端應用程式的 SAML 型第三方識別提供者，以及智慧卡及憑證式驗證等的登入功能。 同時也會移除 Microsoft Outlook 使用基本驗證通訊協定的需求。 如需詳細資訊（包括所有 Office 應用程式的新式驗證可用性），請參閱 [office 2013 和 office 2016 用戶端應用程式的新式驗證運作方式](https://docs.microsoft.com/office365/enterprise/modern-auth-for-office-2013-and-2016)。
    
    Exchange Online 預設會開啟新式驗證。 若要瞭解如何將其開啟或關閉，請參閱 [在 Exchange Online 中啟用新式驗證](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/enable-or-disable-modern-authentication-in-exchange-online)。
    
- **雲端身分識別驗證** -使用傳統挑戰/回應驗證具有雲端身分識別的使用者。 網頁瀏覽器會重新導向至 Microsoft 登入服務，您可以在其中輸入您工作或學校帳戶的使用者名稱和密碼。 The sign-in service authenticates your credentials and generates a service token, which the web browser posts to the requested service and logs you in. 
    
- 同盟**識別驗證**-使用 Active Directory Federation SERVICES (AD FS) 2.0 或其他安全性 Token 服務，驗證具有同盟身分識別的使用者。 網頁瀏覽器會重新導向至 Microsoft 登入服務，您可以在其中以使用者主要名稱 (UPN) 來輸入您的公司識別碼，例如： *isabel@contoso.com*。 The sign-in service determines that you are part of a federated domain and offers to redirect you to the on-premises Federation Server for authentication. 如果您已登入桌面 (已加入網域的) ，您會使用 Kerberos 或) NTLMv2 的驗證 (，而且內部部署 Security Token Service 會產生登入權杖，網頁瀏覽器會將其發佈至 Microsoft 登入服務。 Using the logon token, the sign-in service generates a service token that the web browser posts to the requested service and logs you in. For a list of available Security Token Services available, see [Single sign-on roadmap](https://docs.microsoft.com/previous-versions/azure/azure-services/hh967643(v=azure.100)).
    
Microsoft 使用以表單為基礎的驗證，而且透過網路驗證流量永遠使用埠 443 TLS/SSL 加密。 驗證流量使用的是不計的 Microsoft 服務頻寬百分比。 
  
### <a name="multi-factor-authentication"></a>Multi-Factor 驗證

使用 Multi-Factor 驗證，使用者在正確輸入密碼後，必須先在其 smartphone 上認可電話、文字訊息或代理程式更新。 Only after this second authentication can the user sign in. Microsoft 系統管理員可在 Microsoft 365 系統管理中心中，註冊多重要素驗證的使用者。 深入瞭解 [Multi-Factor 驗證](https://docs.microsoft.com/office365/admin/security-and-compliance/set-up-multi-factor-authentication)。
  
### <a name="rich-client-authentication"></a>豐富型用戶驗證

針對如 Microsoft Office 桌面應用程式的豐富型用戶端，驗證的方式有兩種：
  
- **Microsoft Online Services Sign-In 助理** -由桌面安裝程式安裝的登入小幫手，包含用戶端服務，可取得登入服務的服務權杖，並將其傳回豐富型用戶端。 
    
  - 如果您有雲端身分識別，您會收到驗證的提示，用戶端服務會使用 WS-Trust) 傳送給登入服務以進行驗證 (。
    
  - 如果您有同盟身分識別，用戶端服務會先聯繫 AD FS 2.0 伺服器以驗證使用 Kerberos 或) NTLMv2 的認證 (，並使用 WS-Federation 和 WS-Trust) ，取得傳送至登入服務的登入 (服務權杖。
    
- 透過**ssl 的基本/proxy 驗證**-Outlook 用戶端透過 ssl 將基本驗證認證傳遞到 Exchange Online。 Exchange Online 會將驗證要求傳送至身分識別平臺，然後再將其傳送至內部部署 Active Directory 同盟伺服器 (，以進行 SSO) 。 
    
為了確保正確探索和驗證 Microsoft 服務，管理員必須將一組元件和更新套用至每個使用胖用戶端的工作站 (例如 Microsoft Office 2010) 並連接到 Office 365。 桌面安裝程式是一種自動化的工具，可設定具有必要更新的工作站。 如需詳細資訊，請參閱 [使用我目前的 Office 桌面應用程式](https://support.office.com/article/set-up-office-2010-desktop-programs-to-work-with-office-365-for-business-3324b8b8-dceb-45e2-ac24-c642720108f7?ocmsassetID=HA102817827&CorrelationId=8eb1b198-827a-4999-a584-05a05a92d224&ui=en-US&rs=en-US&ad=US)。
  
### <a name="sign-in-experience"></a>登入經驗

登入經驗會變更，取決於使用的身分識別類型：<br><br>
  
| 服務 | 雲端身分識別 | 同盟身分識別 |
|:-----|:-----|:-----|
|Outlook 2016  <br/> |登入每個工作階段 <sup>1</sup> <br/> |登入每個工作階段 <sup>2</sup> <br/> |
|Outlook 2013  <br/> |登入每個工作階段 <sup>1</sup> <br/> |登入每個工作階段 <sup>2</sup> <br/> |
|Outlook 2010 或 Office 2007 在 Windows 7  <br/> |登入每個工作階段 <sup>1</sup> <br/> |登入每個工作階段 <sup>2</sup> <br/> |
|Outlook 2010 或 Office Outlook 2007 在 Windows Vista  <br/> |登入每個工作階段 <sup>1</sup> <br/> |登入每個工作階段 <sup>2</sup> <br/> |
|Microsoft Exchange ActiveSync  <br/> |登入每個工作階段 <sup>1</sup> <br/> |登入每個工作階段 <sup>2</sup> <br/> |
|POP、IMAP、Outlook for Mac  <br/> |登入每個工作階段 <sup>1</sup> <br/> |登入每個工作階段 <sup>2</sup> <br/> |
|網頁體驗： Microsoft 365 admin center/Outlook on web/SharePoint Online/Office 網頁版  <br/> |登入每個瀏覽器工作階段<sup>4</sup> <br/> |登入每個工作階段 <sup>3</sup> <br/> |
|Office 2010 或 Office 2007 使用 SharePoint Online  <br/> |登入每個 SharePoint Online 工作階段 <sup>4</sup> <br/> |登入每個 SharePoint Online 工作階段<sup>3</sup> <br/> |
|商務用 Skype Online  <br/> |登入每個工作階段 <sup>1</sup> <br/> |無提示  <br/> |
|Mac 版 Outlook  <br/> |登入每個工作階段 <sup>1</sup> <br/> |登入每個工作階段 <sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> 當第一次出現提示時，您可以儲存密碼供日後使用。 除非您變更密碼，否則您不會收到其他提示。 <br/> 
<sup>2</sup> 您輸入您的公司認證。 您可以儲存您的密碼，並且在密碼變更之前不會出現提示。 <br/> 
<sup>3</sup> 所有應用程式都需要您輸入或選取您的使用者名稱，才能登入。 如果您的電腦已加入網域，系統不會提示您輸入密碼。 如果您選取 [ **讓我保持登入** ]，您將不會再收到提示，直到您登出為止。 <br/> 
<sup>4</sup> 如果您選取 [ **讓我保持登入** ]，您將不會再收到提示，直到您登出為止。 
  
## <a name="create-user-accounts"></a>Create user accounts

有多種方式可以讓您新增使用者。 若要深入瞭解，請參閱 [個別或大量系統管理協助新增使用者](https://docs.microsoft.com/office365/admin/add-users/add-users) [，以及新增、移除及管理 Microsoft 365 系統管理中心預覽中的使用者](https://support.office.com/article/add-remove-and-manage-users-in-the-new-office-365-admin-center-6e80db58-c36b-4add-b1c8-cc5135f111f3?amp%3Bclcid=0x409&ui=en-US&rs=en-US&ad=US)。 如果您在中國使用由 21Vianet 提供的 Office 365，請參閱[在由 21Vianet 提供的 Office 365 中建立或編輯使用者帳戶 - 管理中心說明](https://docs.microsoft.com/office365/admin/add-users/add-users)。
  
## <a name="delete-user-accounts"></a>刪除使用者帳戶

如何刪除帳戶端視您是否使用目錄同步處理： 
  
- 如果您不是使用目錄同步處理，則可以使用 [管理] 頁面或使用 Windows PowerShell 刪除帳戶。
    
- 若您使用目錄同步處理，您必須從本機 Active Directory，而非從 Office 365 刪除使用者。
    
當帳戶被刪除，它將變為非作用狀態。 帳戶刪除約 30 日之後，您可以復原帳戶。 如需有關刪除及還原帳戶的詳細資訊，請參閱 [刪除使用者](https://docs.microsoft.com/office365/admin/add-users/delete-a-user) 及 [還原使用者](https://docs.microsoft.com/office365/admin/add-users/restore-user) ; 如果使用中國的世紀運作的 office 365，請參閱 [Create Or edit user accounts in Office 365 運作-系統管理](https://docs.microsoft.com/office365/admin/add-users/add-users)說明。
  
## <a name="password-management"></a>密碼管理

密碼管理的原則和程序依身份識別系統而定。
  
### <a name="cloud-identity-password-management"></a>雲端身分識別密碼管理
  
使用雲端身分時，在建立帳戶時會自動產生密碼。
  
- 如需雲端身分識別密碼強度需求，請參閱[密碼原則](https://docs.microsoft.com/previous-versions/azure/jj943764(v=azure.100))。
    
- 若要提高安全性，使用者必須在第一次存取 Microsoft 服務時變更其密碼。 因此，在使用者可以存取 Microsoft 服務之前，他們必須登入 Microsoft 365 系統管理中心，以提示他們變更其密碼。
    
- 管理員可以設定密碼到期原則。如需詳細資訊，請參閱[設定使用者的密碼到期原則](https://docs.microsoft.com/office365/admin/manage/set-password-expiration-policy)。
    
下列為具備雲端身份之使用者可用的密碼重設工具：
  
- 系統**管理員重設密碼**-如果使用者遺失或遺忘密碼，系統管理員可以在系統管理中心或使用 Windows PowerShell 重設使用者密碼。 使用者必須知道自己的現有密碼，才能變更密碼。 
    
    針對企業方案，如果系統管理員丟失或忘記其密碼，則具有全域系統管理員角色的不同系統管理員可以在 Microsoft 365 系統管理中心或使用 Windows PowerShell 重設系統管理員的密碼。 有關詳細資訊，請參閱[重置管理員密碼](https://docs.microsoft.com/office365/admin/add-users/reset-passwords)。 如果您在中國使用 21Vianet 運作的 Office 365，請參閱[在 21Vianet 運作的 Office 365 中建立或重設密碼](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b)。
    
- **使用者在網頁上使用 outlook 變更密碼** -[web 上的 outlook 選項] 頁面包含 [變更密碼] 超連結，可將使用者重新導向至 [ **變更密碼** ] 頁面。 使用者必須知道他們先前的密碼。 如需詳細資訊，請參閱 [ 變更密碼 ](https://support.office.com/article/change-password-in-outlook-web-app-50bb1309-6f53-4c24-8bfd-ed24ca9e872c)。 如果您在中國使用 21Vianet 運作的 Office 365，請參閱[在 21Vianet 運作的 Office 365 中建立或重設密碼](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b)。
    
- 以**角色為基礎的重設密碼權力**-針對企業方案，可將「**重設密碼**」使用者權利和使用預先定義或自訂角色變更密碼的許可權指派給使用者，而不會成為完全服務管理員。 依預設，在企業方案中，具有全域管理員、密碼管理員或使用者管理系統管理員角色的系統管理員可以變更密碼。 For more information, see [Assigning admin roles](https://docs.microsoft.com/office365/admin/add-users/assign-admin-roles).
    
- **使用 windows PowerShell 重設密碼** -服務管理員可使用 windows PowerShell 重設密碼。 
    
### <a name="federated-identity-password-management"></a>同盟身分識別密碼管理
  
使用同盟身分時，密碼會在 Active Directory 中管理。 內部部署 Security Token Service 會以同盟閘道來協商驗證，而不需透過網際網路將使用者的本機 Active Directory 密碼傳遞到 Office 365。 使用本機密碼原則，或如果是網頁用戶端則使用雙因素驗證。 網頁上的 Outlook 不包含 [變更密碼] 超連結。 使用者變更密碼，使用標準的內部部署工具，或經由桌面 PC 登入選項。
  
若您的組織環境中已啟用 [單一登入的目錄同步處理 (SSO) ](https://docs.microsoft.com/previous-versions/azure/azure-services/dn441213(v=azure.100)) ，且發生中斷，會影響同盟身分識別提供者，同盟登入的密碼同步備份可讓您選擇手動將網域切換至密碼同步處理。使用密碼同步處理會在修復中斷時，存取您的使用者。 瞭解 [如何從單一 Sign-On 切換到密碼同步](https://go.microsoft.com/fwlink/p/?LinkId=509832)處理。
  
## <a name="license-management"></a>授權管理

授權可讓使用者存取一組 Microsoft 服務。 針對使用者需要存取之服務，管理員會指派一個授權給每位使用者。 例如，您可以指派使用者商務用 Skype Online 而非 SharePoint Online 的存取權。
  
Microsoft 計費管理員可對訂閱詳細資料進行變更，例如使用者授權數目，以及貴公司所用的其他服務數目。 請參閱 [指派或移除授權](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users)。 如果您使用 21Vianet 運作的 Office 365，請參閱[在 21Vianet 運作的 Office 365 中指派或移除授權](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users)。
  
## <a name="group-management"></a>群組管理

安全性群組使用於 SharePoint Online 以控制制對網站之存取。 安全性群組可以在 Microsoft 365 系統管理中心中建立。 有關安全性群組的詳細資訊，請參閱[建立、編輯或刪除安全性群組](https://docs.microsoft.com/office365/admin/email/create-edit-or-delete-a-security-group)。
  
## <a name="administrator-roles"></a>系統管理員角色

Office 365 for enterprise 遵循以角色為基礎的存取控制 (RBAC) 模型：許可權和功能是由管理角色所定義。 系統會自動將代替組織註冊使用 Office 365 的人員設為全域管理員或高階管理員。 共有五種管理員角色：全域管理員、帳務管理員、密碼管理員、服務管理員和使用者管理管理員。 如需適用于企業的 Office 365 中系統管理員角色的詳細資訊，包括如何套用至 Exchange Online、SharePoint Online 和商務用 Skype Online 管理，請參閱 [指派系統管理員角色](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/jj878348(v=ws.11))。 如果您在中國使用 21Vianet 運作的 Office 365，請參閱[在 Office 365 for business 中指派系統管理員角色](https://docs.microsoft.com/office365/admin/add-users/assign-admin-roles)。
  
## <a name="delegated-administration-and-support-for-partners"></a>委派合作夥伴管理和支援

合作夥伴可以被授權管理客戶帳戶。 客戶不需要合作夥伴所使用的使用者帳戶，也不會在授與委派的管理授權時使用授權。 合作夥伴可以將完全或有限存取權限分配給他們的組織內的使用者。 Limited 有限存取包括重設密碼、管理服務要求，以及監督服務健全之權力。 
  
> [!NOTE]
> 使用並將夥伴指定為委派系統管理員的能力依地區而有所不同。 
  
## <a name="azure-active-directory-services"></a>Azure Active Directory 服務

Azure Active Directory (AD) 將完整的身分識別與存取管理功能帶到 Office 365。它結合了目錄服務、進階身分識別管理、應用程式存取管理以及豐富的標準型開發人員平台。若要深入了解 Office 365 中的 AD 功能，請參閱[登入頁面商標及雲端使用者自助式密碼重設](https://www.microsoft.com/en-us/microsoft-365/blog/2015/02/17/sign-page-branding-cloud-user-self-service-password-reset-office-365/)。深入了解 [Azure Active Directory 版本](https://msdn.microsoft.com/library/azure/dn532272.aspx)。 
  
## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱 [Microsoft 365 和 Office 365 平臺服務說明](office-365-platform-service-description.md)。
  
