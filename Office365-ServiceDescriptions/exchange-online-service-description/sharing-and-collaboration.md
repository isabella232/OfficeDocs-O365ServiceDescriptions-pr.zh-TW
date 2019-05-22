---
title: 共用和協同
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-sharing-and-collaboration
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 862dab54-701f-4014-a594-0b71e03772d2
ms.openlocfilehash: f007f4b1c0b11e183e62b6c9ba482daa98cdcdf4
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/22/2019
ms.locfileid: "34342602"
---
# <a name="sharing-and-collaboration"></a><span data-ttu-id="14666-102">共用和協同</span><span class="sxs-lookup"><span data-stu-id="14666-102">Sharing and Collaboration</span></span>

## <a name="federated-sharing"></a><span data-ttu-id="14666-103">同盟共用</span><span class="sxs-lookup"><span data-stu-id="14666-103">Federated sharing</span></span>

<span data-ttu-id="14666-p101">同盟指的是支援同盟共用的基礎信任基礎結構，對 Microsoft Exchange Online 使用者而言，這是與其他外部同盟組織中的收件者或與可存取網際網路的使用者有空/忙碌共用行事曆資料和連絡人資訊的方法。這些包括使用 Exchange Online 託管的組織，或外部 Microsoft Exchange Server 2010 或 Exchange Server 2013 組織。Exchange Online 系統管理員可使用組織關係和共用原則，允許使用者從 Microsoft Outlook Web App 或 Microsoft Outlook 2010 或更新版本傳送行事曆共用邀請。</span><span class="sxs-lookup"><span data-stu-id="14666-p101">Federation refers to the underlying trust infrastructure that supports federated sharing, a method for Microsoft Exchange Online users to share free/busy calendar data and contact information with recipients in other external federated organizations or with users that have Internet access. These include organizations that are also hosted by Exchange Online, or external Microsoft Exchange Server 2010 or Exchange Server 2013 organizations. Using organization relationships and sharing policies, Exchange Online administrators can enable users to send calendar-sharing invitations from Microsoft Outlook Web App or Microsoft Outlook 2010 or later.</span></span>
  
> [!IMPORTANT]
>  <span data-ttu-id="14666-p102">外部 Exchange 2010 和 Exchange 2013 組織必須在設定同盟共用的過程中，設定與 Microsoft Federation Gateway 之間的同盟信任。Exchange Online 組織不需要設定同盟信任，因為與 Microsoft Federation Gateway 之間的同盟信任會在建立 Office 365 租用戶時自動建立。 >  Exchange Online 組織必須設定組織關係或共用原則，才能啟用同盟共用。 >  同盟共用不支援共用全域存取清單 (GAL)，或在不同 Office 365 租用戶中於 Exchange Online 組織之間移動使用者信箱。</span><span class="sxs-lookup"><span data-stu-id="14666-p102">External Exchange 2010 and Exchange 2013 organizations must configure a federation trust with the Microsoft Federation Gateway as part of configuring federated sharing. Exchange Online organizations don't have to configure a federation trust—the federation trust with the Microsoft Federation Gateway is automatically created when the Office 365 tenant is created. >  Exchange Online organizations must configure either an organization relationship or a sharing policy to enable federated sharing. >  Sharing of the global access list (GAL) or moving user mailboxes between Exchange Online organizations in different Office 365 tenants is not supported in federated sharing.</span></span> 
  
<span data-ttu-id="14666-111">如需有關同盟共用的詳細資訊，請參閱[在 Exchange Online 中共用](https://go.microsoft.com/fwlink/p/?LinkId=271774)。</span><span class="sxs-lookup"><span data-stu-id="14666-111">For more information about federated sharing, see [Sharing in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271774).</span></span>
  
## <a name="site-mailboxes"></a><span data-ttu-id="14666-112">網站信箱</span><span class="sxs-lookup"><span data-stu-id="14666-112">Site mailboxes</span></span>

<span data-ttu-id="14666-p103">電子郵件與文件將以傳統方式儲存於兩個獨特且分離的資料存放庫。大部分的團隊會同時使用電子郵件和文件來進行共同作業。挑戰在於電子郵件與文件皆使用不同客戶端存取。這通常是使用者生產力的下降以及使用者體驗的退化所產生的結果。</span><span class="sxs-lookup"><span data-stu-id="14666-p103">Email and documents are traditionally kept in two unique and separate data repositories. Most teams collaborate by using both email and documents. The challenge is that email and documents are accessed by using different clients. This usually results in a reduction in user productivity and a degraded user experience.</span></span>
  
<span data-ttu-id="14666-p104">網站信箱是 Exchange 2013 中的全新概念，目的為嘗試解決此問題。網站信箱使用同一個用戶端介面同時允許存取 Microsoft SharePoint 2013 文件和 Exchange 電子郵件，來改善共同作業和使用者的生產力。網站信箱功能是由 SharePoint 2013 網站成員資格 (擁有者和成員) 組成，透過 Exchange 2013 信箱的電子郵件與 SharePoint 2013 網站的文件共用儲存，並使用同一個管理介面來解決佈建和週期需求。</span><span class="sxs-lookup"><span data-stu-id="14666-p104">The site mailbox is a new concept in Exchange 2013 that attempts to solve this problem. Site mailboxes improve collaboration and user productivity by using the same client interface to allow access to both Microsoft SharePoint 2013 documents and Exchange email. A site mailbox functionally consists of SharePoint 2013 site membership (owners and members), shared storage through an Exchange 2013 mailbox for email messages and a SharePoint 2013 site for documents, and a management interface that addresses provisioning and life cycle needs.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="14666-p105">您的 Office 365 計劃必須包括 SharePoint 在內。網站信箱要求使用者同時具有 SharePoint 和 Exchange 的授權。</span><span class="sxs-lookup"><span data-stu-id="14666-p105">Your Office 365 plan must include SharePoint. Site mailboxes require that users have both SharePoint and Exchange licenses.</span></span> 
  
<span data-ttu-id="14666-122">如需有關網站信箱的詳細資訊，請參閱[網站信箱](https://go.microsoft.com/fwlink/p/?LinkId=271789)。</span><span class="sxs-lookup"><span data-stu-id="14666-122">For more information about site mailboxes, see [Site Mailboxes](https://go.microsoft.com/fwlink/p/?LinkId=271789).</span></span>
  
## <a name="public-folders"></a><span data-ttu-id="14666-123">公用資料夾</span><span class="sxs-lookup"><span data-stu-id="14666-123">Public folders</span></span>

<span data-ttu-id="14666-124">Exchange Online 中的公用資料夾已經過強化，可善用信箱資料庫現有的高可用性和儲存技術。</span><span class="sxs-lookup"><span data-stu-id="14666-124">Public folders in Exchange Online have been modernized to take advantage of the existing high availability and storage technologies of the mailbox database.</span></span> <span data-ttu-id="14666-125">公用資料夾架構使用特殊設計的信箱來儲存階層與公用資料夾內容。</span><span class="sxs-lookup"><span data-stu-id="14666-125">The public folder architecture uses specially designed mailboxes to store both the hierarchy and the public folder content.</span></span> <span data-ttu-id="14666-126">這意味著再也沒有獨立的公用資料夾資料庫。</span><span class="sxs-lookup"><span data-stu-id="14666-126">This means that there's no longer a separate public folder database.</span></span> <span data-ttu-id="14666-127">公用資料夾複寫目前使用連續複寫模型。</span><span class="sxs-lookup"><span data-stu-id="14666-127">Public folder replication now uses the continuous replication model.</span></span> <span data-ttu-id="14666-128">階層和內容信箱的高可用性是由資料中心的資料庫可用性群組 (DAG) 提供。</span><span class="sxs-lookup"><span data-stu-id="14666-128">High availability for the hierarchy and content mailboxes is provided by a database availability group (DAG) in the data center.</span></span> <span data-ttu-id="14666-129">在 Exchange Online 中，您可以有 1000 個公用資料夾信箱。</span><span class="sxs-lookup"><span data-stu-id="14666-129">In Exchange Online, you are limited to 1000 public folder mailboxes.</span></span> <span data-ttu-id="14666-130">每個公用資料夾信箱也有最大儲存大小。</span><span class="sxs-lookup"><span data-stu-id="14666-130">Each public folder mailbox also has a maximum storage size.</span></span> <span data-ttu-id="14666-131">如需詳細資訊，請參閱 [Exchange Online 限制](exchange-online-limits.md)中的＜信箱資料夾限制＞一節。</span><span class="sxs-lookup"><span data-stu-id="14666-131">For more information, see the "Mailbox folder limits" section in [Exchange Online Limits](exchange-online-limits.md).</span></span> <span data-ttu-id="14666-132">公用資料夾信箱與一般信箱具有相同的郵件、收件者及容量警示限制。</span><span class="sxs-lookup"><span data-stu-id="14666-132">Public folder mailboxes have the same message, recipient, and capacity alert limits as regular mailboxes.</span></span> <span data-ttu-id="14666-133">如需詳細資訊，請參閱[收件者](recipients.md)。</span><span class="sxs-lookup"><span data-stu-id="14666-133">For more information, see [Recipients](recipients.md).</span></span> 
  
<span data-ttu-id="14666-134">如需有關公用資料夾的詳細資訊，請參閱[公用資料夾](https://go.microsoft.com/fwlink/p/?LinkId=271790)。</span><span class="sxs-lookup"><span data-stu-id="14666-134">For more information about public folders, see [Public Folders](https://go.microsoft.com/fwlink/p/?LinkId=271790).</span></span>
  
## <a name="group-and-shared-mailboxes"></a><span data-ttu-id="14666-135">群組及共用信箱</span><span class="sxs-lookup"><span data-stu-id="14666-135">Group and Shared mailboxes</span></span>

<span data-ttu-id="14666-p107">群組及共用信箱可方便一組特定的人員監視及傳送共用帳戶 (例如 info@contoso.com 或 contact@contoso.com 這類的公用電子郵件地址) 的電子郵件。當這組人員中有人回覆傳送到共用信箱的郵件時，電子郵件會顯示為由共用信箱寄出，而不是由個別使用者寄出。</span><span class="sxs-lookup"><span data-stu-id="14666-p107">Group and Shared mailboxes make it easy for a specific group of people to monitor and send email from a common account, like public email addresses (for example, info@contoso.com or contact@contoso.com). When a person in the group replies to a message sent to the Shared mailbox, the email appears to be from the Shared mailbox, not from the individual user.</span></span>
  
<span data-ttu-id="14666-p108">通常，群組或共用信箱不需要個別的使用者授權。但是，若要啟用群組或共用信箱的就地封存，您必須為它指派 Exchange Online Plan 1 或 Exchange Online Plan 2 授權。指派授權後，信箱大小增加為授權計劃的大小。若要「就地保留」共用信箱，您必須為它指派 Exchange Online Plan 2 授權。請注意，目前無法指派群組信箱，但應該列入您的授權總計。</span><span class="sxs-lookup"><span data-stu-id="14666-p108">Typically, Group or Shared mailboxes don't require a separate user license. However, To enable In-Place Archive for a Group or Shared mailbox, you must assign an Exchange Online Plan 1 or Exchange Online Plan 2 license to it. After the license is assigned, the mailbox size increases to that of the licensed plan. To put a Shared mailbox on In-Place Hold, you must assign an Exchange Online Plan 2 license to it. Please note that Group mailboxes cannot be assigned at this time but should be accounted for in your total licenses.</span></span>
  
<span data-ttu-id="14666-p109">「就地封存」僅可用來封存已套用授權之單一使用者或實體 (例如共用信箱) 的郵件。禁止使用「就地封存」來儲存多個使用者或實體的郵件。例如，IT 系統管理員不能建立共用信箱，再由使用者純粹為了封存的目的來複製它 (透過 [副本] 或 [密件副本] 欄位，或透過傳輸規則)。請注意，多人使用的共用信箱不會實際儲存個別使用者的電子郵件。多個使用者可以存取，且傳送電子郵件做為共用信箱。因此，只有傳送至共用信箱或從共用信箱寄出的電子郵件會儲存在共用信箱中，做為共用信箱。</span><span class="sxs-lookup"><span data-stu-id="14666-p109">In-Place Archive can only be used to archive mail for a single user or entity (such as a Shared mailbox) for which a license has been applied. Using an In-Place Archive as a means of storing mail from multiple users or entities is prohibited. For example, an IT administrator can't create a Shared mailbox and have users copy it (through the Cc or Bcc field, or through a transport rule) for the explicit purpose of archiving. Note that a Shared mailbox that multiple people use does not actually store email for those individual users. Multiple users have access, and they send email as the Shared mailbox. Therefore, the only emails stored in the Shared mailbox are those sent to or from it, as the Shared mailbox.</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="14666-149">功能可用性</span><span class="sxs-lookup"><span data-stu-id="14666-149">Feature Availability</span></span>

<span data-ttu-id="14666-150">若要檢視 Office 365 計劃、獨立選項和內部部署解決方案中的功能可用性，請參閱 [Exchange Online 服務說明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="14666-150">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

