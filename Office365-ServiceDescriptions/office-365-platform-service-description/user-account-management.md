---
title: 使用者帳戶管理
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-user-account-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: e7616079-5b13-4f1c-99ed-b20174e0808d
description: Microsoft Office 365 支援下列方法來建立、 管理，並驗證使用者。
ms.openlocfilehash: 76a47ba99c9b163c98b7370407d3390c20235ed5
ms.sourcegitcommit: a6d9057a955ca220db9e4dbc29cd9ea0053616fc
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/10/2019
ms.locfileid: "31764851"
---
# <a name="user-account-management"></a>使用者帳戶管理

Microsoft Office 365 支援下列方法來建立、 管理，並驗證使用者。 
  
> [!NOTE]
> 本主題不包含允許或禁止存取個別 Office 365 資源的安全性功能資訊 (例如：Microsoft Exchange Online 的角色型存取控制或在 Microsoft SharePoint Online 中設定安全性)。如需這些功能的詳細資訊，請參閱 [Exchange Online 服務說明](../exchange-online-service-description/exchange-online-service-description.md)及 [SharePoint Online 服務說明](../sharepoint-online-service-description/sharepoint-online-service-description.md)。 
  
若您需要有助於執行系統管理工作的工具相關資訊，請參閱〈[管理 Office 365 帳戶的工具](https://go.microsoft.com/fwlink/?linkid=847777)〉。若要了解如何執行日常管理工作，請參閱〈[Office 365 的一般管理工作](https://go.microsoft.com/fwlink/?linkid=847778)〉。
  
## <a name="need-help-signing-in-installing-or-uninstalling-or-canceling-your-subscription"></a>需要登入、安裝或解除安裝，或是取消訂閱的協助嗎？

取得[登入 Office 365](http://go.microsoft.com/fwlink/?LinkID=529144&amp;clcid=0x409) | [安裝或解除安裝 Office](http://go.microsoft.com/fwlink/?LinkID=827202&amp;clcid=0x409) | [取消 Office 365](https://support.office.com/en-us/article/Cancel-Office-365-for-business-b1bc0bef-4608-4601-813a-cdd9f746709a) 的說明
  
如有其他關於 Office 365 的問題，請造訪 [Microsoft 支援中心](https://go.microsoft.com/fwlink/?LinkID=808783)。若要取得中國的 21Vianet 運作的 Office 365 的支援，請連絡 [21Vianet 支援小組](https://support.office.com/en-US/article/Get-technical-billing-and-subscription-support-for-Office-365-operated-by-21Vianet-671FB12E-F5D8-4CDF-B3E9-E8068A9AA496)。若要取得 Office 365 Germany 的支援，請連絡 [Office 365 Germany 支援小組](https://support.office.com/en-us/article/Get-technical-and-billing-support-for-Office-365-Germany-83ef2266-2543-48d7-a41a-1b56b403a8e9?ui=en-US&amp;rs=en-US&amp;ad=US&amp;fromAR=1)。 
  
## <a name="sign-in-options"></a>登入選項

Office 365 有兩個系統可用於使用者身分識別：
  
- **工作或學校帳戶 (雲端身分識別)** 使用者會收到 Azure Active Directory 雲端認證  不同於其他桌面或公司認證  以便登入 Office 365 和其他 Microsoft 雲端服務。這是預設也是建議身分識別，以便將部署複雜度降至最低。工作或學校帳戶的密碼請使用Azure Active Directory [密碼原則](http://go.microsoft.com/fwlink/?LinkID=730689&amp;clcid=0x409)。
    
- **同盟帳戶 (同盟身分識別)** 針對採用單一登入 (SSO) 之內部部署 Active Directory 的組織中的所有訂閱，使用者可以使用 Active Directory 認證來登入 Office 365 服務。公司Active Directory 儲存和控制密碼原則。如需有關 SSO 的資訊，請參閱 [單一登入藍圖](https://go.microsoft.com/fwlink/p/?LinkID=270015)。
    
身分類型影響使用者經驗及使用者帳戶管理選項，還有硬體和軟體需求及其他部署考量。
  
### <a name="custom-domains-and-identity-options"></a>自訂網域和身分選項

當您建立新的使用者時，使用者的登入名稱和電子郵件地址會指派給預設網域為 Microsoft 365 系統管理中心中的設定。 若要深入了解，請參閱[將您的使用者與網域新增至 Office 365](https://support.office.com/en-us/article/Add-your-users-and-domain-to-Office-365-6383f56d-3d09-4dcb-9b41-b5f5a5efd611)。 
  
根據預設，Office 365 訂閱者會使用以此帳戶建立的 \< _company name_\> **.onmicrosoft.com** 網域。\* 您可以新增一或多個自訂網域到 Office 365 而不必限定於 onmicrosoft.com 網域，並且能指派使用者登入任何有效的網域。每位使用者的指派網域就是電子郵件地址，將顯示在寄出或接收的電子郵件訊息。 
  
您能託管高達 900 個登錄的網路網域在 Office 365，每個網域各由不同的命名空間代表。 
  
針對採用單一登入的組織，網域上的所有使用者都必須使用相同的身份識別系統：雲端身份或同盟身份。 舉例來說，你可以擁有一組使用者，僅需一個雲端身分，因為他們不存取內部部署系統，另一組使用者使用 Office 365 以及內部部署系統。 您應將兩個網域新增至 Office 365，例如： contractors.contoso.com 和 staff.contoso.com，然後只設定 SSO 的其中一部。 您可以將整個網域從雲端身分識別轉換為同盟身分識別，或者從同盟身分識別轉換為雲端身分識別。
  
如需 Office 365 之網域相關資訊，請參閱 [網域](domains.md) 服務說明。 
  
\* 如果您在中國使用 21Vianet 運作的 Office 365，預設網域是 \<公司名稱\> **.onmsChina.cn**。如果您使用 Office 365 Germany，預設網域是 \<公司名稱\> **.onmicrosoft.de**
  
## <a name="authentication"></a>驗證

除了以 SharePoint Online 建立匿名存取的網站之外，在存取 Office 365 服務時，使用者必須獲得驗證。 
  
- **新式驗證** 新式驗證讓平台中的所有 Office 用戶端應用程式都使用 Active Directory 驗證程式庫 (ADAL) 式登入。如此可啟用類似 Multi-Factor Authentication (MFA)、具備 Office 用戶端應用程式的 SAML 型第三方識別提供者，以及智慧卡及憑證式驗證等的登入功能。同時也會移除 Microsoft Outlook 使用基本驗證通訊協定的需求。如需詳細資訊，包括跨 Office 應用程式的新式驗證可用性，請參閱 [新式驗證如何在 Office 2013 及 Office 2016 用戶端應用程式中運作](http://go.microsoft.com/fwlink/?LinkID=717892&amp;clcid=0x409)以及[在 Office 用戶端中使用 Office 365 新式驗證](http://go.microsoft.com/fwlink/?LinkID=717893&amp;clcid=0x409)。
    
    Exchange Online 並未預設開啟新式驗證。若要了解如何開啟，請參閱[啟用 Exchange Online 進行新式驗證](http://go.microsoft.com/fwlink/?LinkID=717894&amp;clcid=0x409)。
    
- **Cloud identity authentication** Users with cloud identities are authenticated using traditional challenge/response. The web browser is redirected to the Office 365 sign-in service, where you type the user name and password for your work or school account. The sign-in service authenticates your credentials and generates a service token, which the web browser posts to the requested service and logs you in. 
    
- **Federated identity authentication** Users with federated identities are authenticated using Active Directory Federation Services (AD FS) 2.0 or other Security Token Services. 在網頁瀏覽器重新導向至 Office 365 登入服務，其中您輸入您公司的識別碼在表單中的使用者主要名稱 (UPN; 例如， isabel@contoso.com)。 The sign-in service determines that you are part of a federated domain and offers to redirect you to the on-premises Federation Server for authentication. If you are logged on to the desktop (domain joined), you are authenticated (using Kerberos or NTLMv2) and the on-premises Security Token Service generates a logon token, which the web browser posts to the Office 365 sign-in service. Using the logon token, the sign-in service generates a service token that the web browser posts to the requested service and logs you in. For a list of available Security Token Services available, see [Single sign-on roadmap](https://go.microsoft.com/fwlink/p/?LinkID=270015).
    
Office 365 使用表單式驗證，網路的驗證傳輸流量總是會使用 443 埠，以 TLS/SSL 加密。驗證傳輸流量使用極小百分比的頻寬提供 Office 365 服務。 
  
### <a name="multi-factor-authentication-for-office-365"></a>Office 365 的 Multi-Factor Authentication

With Multi-Factor Authentication for Office 365, users are required to acknowledge a phone call, text message, or an app notification on their smartphone after correctly entering their password. Only after this second authentication can the user sign in. Office 365 系統管理員可以註冊 Microsoft 365 系統管理中心中的多重要素驗證的使用者。 Learn more about [Multi-Factor Authentication for Office 365](https://go.microsoft.com/fwlink/p/?LinkId=392429).
  
### <a name="rich-client-authentication"></a>豐富型用戶驗證

針對如 Microsoft Office 桌面應用程式的豐富型用戶端，驗證的方式有兩種：
  
- **Microsoft 線上服務登入助理** 這個 登入小幫手 透過 Office 365 桌面設定 安裝，包含用戶端服務，取得來自 Office 365 登入服務的服務權杖，並將其返回豐富型用戶端。 
    
  - 假如您有雲端身分，您會收到驗證的提示，用戶端服務會寄至 Office 365 登入服務以便驗證 (使用 WS-Trust)。
    
  - 如果您有同盟身分識別，則用戶端服務會先連絡 AD FS 2.0 伺服器，以進行認證驗證 (使用 Kerberos 或 NTLMv2)，並取得傳送至 Office 365 登入服務 (使用 WS-Federation 及 WS-Trust) 的登錄權杖。
    
- **透過 SSL 的基礎/Proxy 驗證** Outlook 用戶端會透過 SSL 將基礎驗證認證傳送至 Exchange Online。Exchange Online Proxy 會將驗證要求傳送至 Office 365 身份識別平台，然後再傳送至內部部署 Active Directory 同盟伺服器 (適用於 SSO)。 
    
為確保 Office 365 服務的適當發現與驗證，管理員必須應用一組元件並升級到每個使用豐富型客戶端 (例如 Microsoft Office 2010) 的工作站，並連線到 Office 365。Office 365 桌面設定是一個自動工具，設定工作站的升級要求。如需詳細資訊，請參閱[搭配 Office 365 使用我目前的 Office 桌面應用程式](https://go.microsoft.com/fwlink/p/?LinkID=270049)。
  
### <a name="sign-in-experience"></a>登入經驗

登入經驗會改變，端視使用的 Office 365 身分類別：
  
||**雲端身分識別**|**同盟身分識別**|
|:-----|:-----|:-----|
|Outlook 2016  <br/> |登入每個工作階段 <sup>1</sup> <br/> |登入每個工作階段 <sup>2</sup> <br/> |
|Outlook 2013  <br/> |登入每個工作階段 <sup>1</sup> <br/> |登入每個工作階段 <sup>2</sup> <br/> |
|Outlook 2010 或 Office 2007 在 Windows 7  <br/> |登入每個工作階段 <sup>1</sup> <br/> |登入每個工作階段 <sup>2</sup> <br/> |
|Outlook 2010 或 Office Outlook 2007 在 Windows Vista  <br/> |登入每個工作階段 <sup>1</sup> <br/> |登入每個工作階段 <sup>2</sup> <br/> |
|Microsoft Exchange ActiveSync  <br/> |登入每個工作階段 <sup>1</sup> <br/> |登入每個工作階段 <sup>2</sup> <br/> |
|POP、IMAP、Outlook for Mac  <br/> |登入每個工作階段 <sup>1</sup> <br/> |登入每個工作階段 <sup>2</sup> <br/> |
|Web 體驗：Office 365 入口網站/Outlook Web App/SharePoint Online/Office Online  <br/> |登入每個瀏覽器工作階段<sup>4</sup> <br/> |登入每個工作階段 <sup>3</sup> <br/> |
|Office 2010 或 Office 2007 使用 SharePoint Online  <br/> |登入每個 SharePoint Online 工作階段 <sup>4</sup> <br/> |登入每個 SharePoint Online 工作階段<sup>3</sup> <br/> |
|商務用 Skype Online  <br/> |登入每個工作階段 <sup>1</sup> <br/> |無提示  <br/> |
|Mac 版 Outlook  <br/> |登入每個工作階段 <sup>1</sup> <br/> |登入每個工作階段 <sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> When first prompted, you can save your password for future use. You will not receive another prompt until you change the password. > <sup>2</sup> You enter your corporate credentials. You can save your password and will not be prompted again until your password changes. > <sup>3</sup> All apps require you to enter your username or click to sign in. You are not prompted for your password if your computer is joined to the domain. If you click **Keep me signed in** you will not be prompted again until you sign out. > <sup>4</sup> If you click **Keep me signed in** you will not be prompted again until you sign out. 
  
## <a name="creating-user-accounts"></a>建立使用者帳戶

有多種方式能讓您將使用者加入 Office 365。 若要了解更多，請參閱[使用者個別或大量將新增至 Office 365-系統管理說明](https://go.microsoft.com/fwlink/p/?linkid=860006)以及[新增、 移除及管理 Microsoft 365 系統管理中心預覽中的使用者](http://go.microsoft.com/fwlink/?LinkID=624101&amp;clcid=0x409)。 如果您在中國使用由 21Vianet 提供的 Office 365，請參閱[在由 21Vianet 提供的 Office 365 中建立或編輯使用者帳戶 - 管理中心說明](http://go.microsoft.com/fwlink/?LinkID=730724&amp;clcid=0x409)。
  
## <a name="deleting-accounts"></a>刪除帳戶

如何刪除帳戶端視您是否使用目錄同步處理： 
  
- 若您未使用目錄同步處理，帳戶會因為使用 Office 365 管理頁面或使用 Windows PowerShell 而被刪除。
    
- 若您使用目錄同步處理，您必須從本機 Active Directory，而非從 Office 365 刪除使用者。
    
當帳戶被刪除，它將變為非作用狀態。帳戶刪除約 30 日之後，您可以復原帳戶。如需刪除及還原帳戶的詳細資訊，請參閱[在 Office 365 中刪除或還原使用者](https://go.microsoft.com/fwlink/p/?LinkID=270053)；或如如果您在中國使用 21Vianet 運作的 Office 365，請參閱[在 21Vianet 運作的 Office 365 中建立或編輯使用者帳戶 - 管理說明](http://go.microsoft.com/fwlink/?LinkID=730724&amp;clcid=0x409)。
  
## <a name="password-management"></a>密碼管理

密碼管理的原則和程序依身份識別系統而定。
  
 **雲端身分識別密碼管理：**
  
使用雲端身分時，在建立帳戶時會自動產生密碼。
  
- 如需雲端身分識別密碼強度需求，請參閱[密碼原則](http://go.microsoft.com/fwlink/?LinkID=730689&amp;clcid=0x409)。
    
- 為增強安全性，使用者必須在首次存取 Office 365 服務時變更密碼。最後結果為，在使用者能存取 Office 365 服務之前，他們必須登入 Office 365 網路入口，並得到變更密碼的提示。
    
- 管理員可以設定密碼到期原則。如需詳細資訊，請參閱[設定使用者的密碼到期原則](https://go.microsoft.com/fwlink/p/?LinkID=285381)。
    
下列為具備雲端身份之使用者可用的密碼重設工具：
  
- **管理員重設密碼** 如果使用者遺失或忘記密碼，管理員可以在 Office 365 入口網站或使用 Windows PowerShell 來重設使用者的密碼。使用者必須知道自己的現有密碼，才能變更密碼。 
    
    用於企業方案，如果系統管理員會遺失或忘記密碼，則不同的系統管理員，以全域系統管理員角色可以重設在 Microsoft 365 系統管理中心或使用 Windows PowerShell 的系統管理員的密碼。 有關詳細資訊，請參閱[重置管理員密碼](https://go.microsoft.com/fwlink/p/?LinkID=270062)。 如果您在中國使用 21Vianet 運作的 Office 365，請參閱[在 21Vianet 運作的 Office 365 中建立或重設密碼](http://go.microsoft.com/fwlink/?LinkID=730731&amp;clcid=0x409)。
    
- **使用者透過 Outlook Web App 變更密碼**Outlook Web App 選項頁面有 **[變更密碼]** 超連結，其可將使用者重新導向至 [變更密碼] 頁面。使用者必須知道他們先前的密碼。如需詳細資訊，請參閱 [ 變更密碼 ](https://go.microsoft.com/fwlink/p/?LinkID=270063)。如果您在中國使用 21Vianet 運作的 Office 365，請參閱[在 21Vianet 運作的 Office 365 中建立或重設密碼](http://go.microsoft.com/fwlink/?LinkID=730731&amp;clcid=0x409)。
    
- **Role-based reset password rights** For Enterprise plans, authorized users such as helpdesk staff can be assigned the **Reset Password** user right and the right to change passwords by using the Office 365 predefined or custom roles without becoming full services administrators. By default in Enterprise plans, admins with the Global Administrator, Password Administrator, or User Management Administrator role can change passwords. For more information, see [Assigning admin roles](https://go.microsoft.com/fwlink/p/?LinkID=270061).
    
- **Reset passwords using Windows PowerShell** Service administrators can use Windows PowerShell to reset passwords. 
    
 **同盟身分識別密碼管理：**
  
使用同盟身分時，密碼會在 Active Directory 中管理。內部部署安全性權杖服務和 Office 365 同盟閘道交涉驗證，不透過使用者的本機 Active Directory 密碼從網際網路到 Office 365。使用本機密碼原則，或如果是網頁用戶端則使用雙因素驗證。Outlook Web App 不包含 [變更密碼] 超連結。使用者變更密碼，使用標準的內部部署工具，或經由桌面 PC 登入選項。
  
如果您已在 Office 365 環境中啟用[搭配單一登入的目錄同步作業案例](https://go.microsoft.com/fwlink/p/?LinkId=509831)，而且發生的中斷影響同盟識別提供者，則同盟登入的密碼同步備份會提供將網域手動切換至密碼同步的選項。使用 密碼 同步處理，可讓您的使用者在修正中斷時存取 Office 365。了解[如何從單一登入切換至密碼同步](https://go.microsoft.com/fwlink/p/?LinkId=509832)。
  
## <a name="license-management"></a>授權條款管理

Office 365 授權給予使用者對於一組 Office 365 服務的存取權。針對使用者需要存取之服務，管理員會指派一個授權給每位使用者。例如，您可以指派使用者商務用 Skype Online 而非 SharePoint Online 的存取權。
  
Office 365 帳務管理員可以對訂閱詳細資料進行變更，例如使用者授權數和您的公司使用的額外服務數。請參閱[在 Office 365 中指派或移除授權](https://go.microsoft.com/fwlink/p/?LinkID=270069)。如果您使用 21Vianet 運作的 Office 365，請參閱[在 21Vianet 運作的 Office 365 中指派或移除授權](http://go.microsoft.com/fwlink/?LinkID=730747&amp;clcid=0x409)。
  
## <a name="group-management"></a>群組管理

安全性群組使用於 SharePoint Online 以控制制對網站之存取。 安全性群組可以建立 Microsoft 365 系統管理中心。 有關安全性群組的詳細資訊，請參閱[建立、編輯或刪除安全性群組](http://go.microsoft.com/fwlink/?LinkID=733611&amp;clcid=0x409)。
  
## <a name="administrator-roles"></a>系統管理員角色

Office 365 Enterprise 採用角色型存取控制 (RBAC) 模型：權限和功能依「管理角色」而有所不同。系統會自動將代替組織註冊使用 Office 365 的人員設為全域管理員或高階管理員。共有五種管理員角色：全域管理員、帳務管理員、密碼管理員、服務管理員和使用者管理管理員。如需有關 Office 365 Enterprise 管理員角色的詳細資訊 (包括他們如何應用 Exchange Online、SharePoint Online 和 商務用 Skype Online 管理)，請參閱[指派管理員角色](https://go.microsoft.com/fwlink/p/?LinkID=282732)。如果您在中國使用 21Vianet 運作的 Office 365，請參閱[在 Office 365 for business 中指派系統管理員角色](https://go.microsoft.com/fwlink/p/?linkid=270061)。
  
## <a name="delegated-administration-and-support-for-partners"></a>委派合作夥伴管理和支援

合作夥伴可以被授權管理客戶帳戶。 客戶不得要求合作夥伴使用之使用者帳戶，指派管理授權時亦不需使用 Office 365 授權條款。 合作夥伴可以將完全或有限存取權限分配給他們的組織內的使用者。 Limited 有限存取包括重設密碼、管理服務要求，以及監督服務健全之權力。 
  
> [!NOTE]
> 使用並將夥伴指定為委派系統管理員的能力依地區而有所不同。 
  
## <a name="azure-active-directory-services"></a>Azure Active Directory 服務

Azure Active Directory (AD) 將完整的身分識別與存取管理功能帶到 Office 365。它結合了目錄服務、進階身分識別管理、應用程式存取管理以及豐富的標準型開發人員平台。若要深入了解 Office 365 中的 AD 功能，請參閱[登入頁面商標及雲端使用者自助式密碼重設](https://blogs.office.com/2015/02/17/sign-page-branding-cloud-user-self-service-password-reset-office-365/)。深入了解 [Azure Active Directory 版本](https://msdn.microsoft.com/en-us/library/azure/dn532272.aspx)。 
  
## <a name="feature-availability"></a>功能可用性

若要檢視跨 Office 365 計劃、獨立選項和內部部署方案的功能可用性，請參閱 [Office 365 平台服務說明](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx)。
  
