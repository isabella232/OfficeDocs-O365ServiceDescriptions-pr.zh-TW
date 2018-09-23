---
title: 規劃及部署
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-planning-and-deployment
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: e44e5e61-1f5d-4e68-981d-77a42f0ea0d4
ms.openlocfilehash: b8e805452bde7553640c4b02f39792c0dd1c6b78
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035344"
---
# <a name="planning-and-deployment"></a><span data-ttu-id="2fc56-102">規劃及部署</span><span class="sxs-lookup"><span data-stu-id="2fc56-102">Planning and Deployment</span></span>

## <a name="planning-for-service-changes-and-growth"></a><span data-ttu-id="2fc56-103">規劃服務的變化和增長</span><span class="sxs-lookup"><span data-stu-id="2fc56-103">Planning for service changes and growth</span></span>

<span data-ttu-id="2fc56-104">組織選擇遷移選項時，應基於來源電子郵件系統、希望的結束狀態（完全託管或部分託管）、遷移的使用者人數，以及結束狀態必須多快完成。</span><span class="sxs-lookup"><span data-stu-id="2fc56-104">Organizations should choose migration options based on their source email systems, the desired end state (fully hosted or partially hosted), the number of users to migrate, and how quickly the end state needs to be reached.</span></span>
  
## <a name="deployment-options"></a><span data-ttu-id="2fc56-105">部署選項</span><span class="sxs-lookup"><span data-stu-id="2fc56-105">Deployment options</span></span>

- <span data-ttu-id="2fc56-106">**僅限雲端部署**您的組織具有所有使用者信箱託管於 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="2fc56-106">**Cloud-only deployment** Your organization has all user mailboxes hosted in Exchange Online.</span></span> 
    
- <span data-ttu-id="2fc56-107">**Exchange 混合部署** 你的組織將部分使用者信箱託管於內部佈署 Exchange 組織，部分使用者信箱託管於 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="2fc56-107">**Exchange hybrid deployment** Your organization has some user mailboxes hosted in an on-premises Exchange organization and some user mailboxes hosted in Exchange Online.</span></span> 
    
### <a name="cloud-only"></a><span data-ttu-id="2fc56-108">僅雲端</span><span class="sxs-lookup"><span data-stu-id="2fc56-108">Cloud-only</span></span>

<span data-ttu-id="2fc56-p101">僅雲端部署是指 你的組織在 Exchange Online 服務中未與內部部署 Exchange 組織連線。所有使用者與信箱均由 Exchange Online 及 Office 365 託管及管理。</span><span class="sxs-lookup"><span data-stu-id="2fc56-p101">A cloud-only deployment is one where your organization in the Exchange Online service isn't connected with an on-premises Exchange organization. All users and mailboxes are hosted and managed in Exchange Online and Office 365.</span></span>
  
### <a name="hybrid"></a><span data-ttu-id="2fc56-111">混合</span><span class="sxs-lookup"><span data-stu-id="2fc56-111">Hybrid</span></span>

<span data-ttu-id="2fc56-p102">Microsoft Exchange 2003、Exchange 2007、Exchange 2010，以及 Exchange 2013 均適用的內部組織，混合部署提供了部分使用者信箱裝載於內部佈署 Exchange 組織，部分使用者信箱託管於 Exchange Online 的長期共存設置，或者將所有使用者信箱託管於 Exchange Online 的遷移路徑。混合部署可讓組織將功能豐富的體驗，以及現有內部部署 Microsoft Exchange 組織所具有的管理控制延伸至雲端。混合部署之特色包括安全郵件傳輸、共用行事曆空閑／忙碌資訊，以及內部佈署和 Exchange Online 組織之間的郵件追蹤。</span><span class="sxs-lookup"><span data-stu-id="2fc56-p102">Available for Microsoft Exchange 2003, Exchange 2007, Exchange 2010 and Exchange 2013 on-premises organizations, a hybrid deployment offers either a long-term coexistence configuration with some mailboxes hosted on-premises and some mailboxes hosted in Exchange Online or a migration path to hosting all user mailboxes in Exchange Online. A hybrid deployment offers organizations the ability to extend the feature-rich experience and administrative control they have with their existing on-premises Microsoft Exchange organization to the cloud. Hybrid deployment features include secure mail transport, shared calendar free/busy information, and message tracking between the on-premises and Exchange Online organizations.</span></span>
  
<span data-ttu-id="2fc56-p103">如需有關混合部署的詳細資訊，請參閱 [Exchange Server 2013 混合部署](https://go.microsoft.com/fwlink/p/?LinkId=287035)。如果您使用 21Vianet 操作的 Office 365，請參閱 [使用 21Vianet 操作的 Office 365 設定 Exchange 混合部署](http://go.microsoft.com/fwlink/?LinkID=733373&amp;clcid=0x409)。</span><span class="sxs-lookup"><span data-stu-id="2fc56-p103">For more information about hybrid deployments, see [Exchange Server 2013 Hybrid Deployments](https://go.microsoft.com/fwlink/p/?LinkId=287035). If you are using Office 365 operated by 21Vianet, see [Configuring Exchange hybrid deployment features with Office 365 operated by 21Vianet](http://go.microsoft.com/fwlink/?LinkID=733373&amp;clcid=0x409).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="2fc56-p104">內部部署 Exchange 2003 組織必須至少安裝一個 Exchange 2010 用戶端存取／郵件伺服器，以便設定和 Exchange Online 之混合部署。內部部署 Exchange 2007 組織必須至少安裝一個 Exchange 2010 或 Exchange 2013 用戶端存取及郵件伺服器，以便設定和 Exchange Online 之混合部署。內部部署 Exchange 2010 和及 Exchange 2013 組織原生支援和 Exchange Online 之混合部署。如需有關混合部署中 Exchange Server 相容性的詳細資訊，請參閱[混合部署必要條件](https://go.microsoft.com/fwlink/p/?LinkId=243541)。 > 內部佈署 Exchange 組織必須將其組織設定為混合部署。我們強烈建議管理者使用 Exchange Server 部署助理及混合設定精靈來設定混合部署。進一步了解 [Exchange Server 部署助理](https://go.microsoft.com/fwlink/p/?LinkId=287036)</span><span class="sxs-lookup"><span data-stu-id="2fc56-p104">On-premises Exchange 2003 organizations must install at least one Exchange 2010 Client Access/Mailbox server to configure a hybrid deployment with Exchange Online. On-premises Exchange 2007 organizations must install at least one Exchange 2010 or Exchange 2013 Client Access and Mailbox server to configure a hybrid deployment with Exchange Online. On-premises Exchange 2010 and Exchange 2013 organizations natively support hybrid deployments with Exchange Online. For more information about Exchange server compatibility in hybrid deployments, see [Hybrid Deployment Prerequisites](https://go.microsoft.com/fwlink/p/?LinkId=243541)> On-premises Exchange organizations must configure their organization for a hybrid deployment. We strongly recommend that administrators use the Exchange Server Deployment Assistant and the Hybrid Configuration Wizard to configure the hybrid deployment. Learn more at [Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036)</span></span>
  
## <a name="migration-options"></a><span data-ttu-id="2fc56-123">遷移選項</span><span class="sxs-lookup"><span data-stu-id="2fc56-123">Migration options</span></span>

<span data-ttu-id="2fc56-p105">組織選擇遷移選項時，應基於來源電子郵件系統、希望的結束狀態（完全託管或部分託管）、遷移的使用者人數，以及結束狀態必須多快完成。可能遷移選項：</span><span class="sxs-lookup"><span data-stu-id="2fc56-p105">Organizations should choose migration options based on their source email systems, the desired end state (fully hosted or partially hosted), the number of users to migrate, and how quickly the end state needs to be reached. Possible migration options are:</span></span>
  
- <span data-ttu-id="2fc56-126">**IMAP 遷移** 將信箱資料從 IMAP 架構之電子郵件系統遷移至 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="2fc56-126">**IMAP migration** Migrate mailbox data from IMAP-based email systems to Exchange Online.</span></span> 
    
- <span data-ttu-id="2fc56-127">**轉換 Exchange 移轉**以單一轉換方式遷移至 Exchange Online 將信箱從 Exchange Server 2003、 Exchange Server 2007、 Exchange Server 2010、 Exchange 2013 及 Hosted Exchange 系統遷移。</span><span class="sxs-lookup"><span data-stu-id="2fc56-127">**Cutover Exchange migration** Migrate mailboxes from Exchange Server 2003, Exchange Server 2007, Exchange Server 2010, Exchange 2013 and Hosted Exchange systems to Exchange Online in a single cutover migration.</span></span> 
    
- <span data-ttu-id="2fc56-128">**分段 Exchange 遷移**執行分段的移轉將信箱從 Exchange Server 2003 或 Exchange Server 2007 的資料具有網路架構遷移工具及最少改變移轉至內部部署基礎結構。</span><span class="sxs-lookup"><span data-stu-id="2fc56-128">**Staged Exchange migration** Perform a staged migration to migrate mailboxes from Exchange Server 2003 or Exchange Server 2007 with web-based migration tools and minimal changes to on-premises infrastructure.</span></span> 
    
- <span data-ttu-id="2fc56-p106">**遠端移動移轉** 將內部部署 Exchange 信箱移轉至 Exchange 混合部署的 Exchange Online。您必須具有 Exchange 混合部署，才能使用遠端移動移轉。</span><span class="sxs-lookup"><span data-stu-id="2fc56-p106">**Remote move migration** Migrate on-premises Exchange mailboxes to Exchange Online in an Exchange hybrid deployment. You must have an Exchange hybrid deployment to use a remote move migration.</span></span> 
    
<span data-ttu-id="2fc56-131">如需將電子郵件和信箱遷移至 Exchange Online 的詳細資訊，請參閱[將電子郵件移轉到 Exchange Online ](https://support.office.com/en-us/article/-a3e3bddb-582e-4133-8670-e61b9f58627e)。</span><span class="sxs-lookup"><span data-stu-id="2fc56-131">For more information about migrating email and mailboxes to Exchange Online, see [Mailbox Migration to Exchange Online ](https://support.office.com/en-us/article/-a3e3bddb-582e-4133-8670-e61b9f58627e).</span></span>
  
### <a name="imap-migration"></a><span data-ttu-id="2fc56-132">IMAP 移轉</span><span class="sxs-lookup"><span data-stu-id="2fc56-132">IMAP migration</span></span>

<span data-ttu-id="2fc56-p107">Exchange Online 提供網路架構工具，以便遷移支援 IMAP 的電子郵件系統中的信箱資料。它將透過以下遷移步驟來引導管理員：</span><span class="sxs-lookup"><span data-stu-id="2fc56-p107">Exchange Online offers a web-based tool for migrating mailbox data from email systems that support IMAP. It guides administrators through the following migration steps:</span></span> 
  
1. <span data-ttu-id="2fc56-135">在雲端為組織的使用者建立空信箱（通常是透過上傳 .csv 檔案，或使用遠端 Windows PowerShell 而完成）。</span><span class="sxs-lookup"><span data-stu-id="2fc56-135">Create empty mailboxes in the cloud for users in the organization (typically this is done by uploading a .csv file or using remote Windows PowerShell).</span></span>
    
2. <span data-ttu-id="2fc56-136">輸入遠端伺服器連接設置。</span><span class="sxs-lookup"><span data-stu-id="2fc56-136">Enter the remote server connection settings.</span></span>
    
3. <span data-ttu-id="2fc56-137">Use使用 CSV 檔案來指定信箱，信箱內的資料將由 Exchange Online 信箱遷移過來。</span><span class="sxs-lookup"><span data-stu-id="2fc56-137">Use a CSV file to specify the mailboxes whose data will be migrated to Exchange Online mailboxes.</span></span>
    
4. <span data-ttu-id="2fc56-138">輸入資料之後，Exchange Online 開始透過 IMAP 遷移信箱內容（行事曆項目、聯絡人、工作，以及其他非郵件項目將不會遷移）。</span><span class="sxs-lookup"><span data-stu-id="2fc56-138">After this information is entered, Exchange Online begins to migrate mailbox content via IMAP (calendar items, contacts, tasks, and other non-mail items are not migrated).</span></span>
    
<span data-ttu-id="2fc56-139">如需 IMAP 遷移的詳細資訊，請參閱[將 IMAP 信箱移轉到 Office 365](https://support.office.com/en-ie/article/Migrate-your-IMAP-mailboxes-to-Office-365-3fe19996-29bc-4879-aab9-5a622b2f1481) 和 [將其他類型的 IMAP 信箱移轉到 Office 365](https://support.office.com/en-ie/article/Migrate-other-types-of-IMAP-mailboxes-to-Office-365-58890ccd-ce5e-4d94-be75-560a3b70a706)。</span><span class="sxs-lookup"><span data-stu-id="2fc56-139">For more information about IMAP migration, see [Migrate Email from an IMAP Server to Exchange Online Mailboxes](https://support.office.com/en-ie/article/Migrate-your-IMAP-mailboxes-to-Office-365-3fe19996-29bc-4879-aab9-5a622b2f1481) and [Migrate other types of IMAP mailboxes](https://support.office.com/en-ie/article/Migrate-other-types-of-IMAP-mailboxes-to-Office-365-58890ccd-ce5e-4d94-be75-560a3b70a706).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="2fc56-140">為避免在遷移過程中過度使用遠端伺服器的來源和頻寬，Exchange Online 建立低於十個連線到 IMAP 伺服器。</span><span class="sxs-lookup"><span data-stu-id="2fc56-140">To avoid overusing the remote server's resources and bandwidth during the migration, Exchange Online creates fewer than 10 connections to the IMAP server.</span></span> 
  
### <a name="cutover-exchange-migration"></a><span data-ttu-id="2fc56-141">轉換 Exchange 遷移</span><span class="sxs-lookup"><span data-stu-id="2fc56-141">Cutover Exchange migration</span></span>

<span data-ttu-id="2fc56-p108">Exchange Online 提供網路架構工具，以便從內部部署 Exchange Server 2003、Exchange Server 2007，或 Exchange Server 2010 的環境遷移資料。它將透過以下遷移步驟來引導管理員：</span><span class="sxs-lookup"><span data-stu-id="2fc56-p108">Exchange Online offers a web-based tool for migrating data from on-premises Exchange Server 2003, Exchange Server 2007, or Exchange Server 2010 environments. It guides an administrator through the following migration steps:</span></span>
  
1. <span data-ttu-id="2fc56-144">對於內部部署管理員帳戶使用電子郵件地址及認證，Exchange Online 使用 自動探索 服務，連線到內部部署電子郵件組織。</span><span class="sxs-lookup"><span data-stu-id="2fc56-144">Using the email address and credentials for an on-premises administrator account, Exchange Online connects to the on-premises email organization by using the Autodiscover service.</span></span>
    
2. <span data-ttu-id="2fc56-145">Exchange Online 使用 RPC/HTTP 連線以讀取遠端伺服器的目錄資訊，並且在 Exchange Online 建立信箱。</span><span class="sxs-lookup"><span data-stu-id="2fc56-145">Exchange Online uses an RPC/HTTP connection to read directory information from the remote server and create mailboxes in Exchange Online.</span></span>
    
3. <span data-ttu-id="2fc56-p109">Exchange Online 將信箱內容同步化到雲端信箱。Users使用者將資料遷移到 Exchange Online，同時保持連線到原有的信箱。</span><span class="sxs-lookup"><span data-stu-id="2fc56-p109">Exchange Online synchronizes the mailbox content to the cloud mailboxes. Users remain connected to their original mailboxes while their data is being migrated to Exchange Online.</span></span>
    
4. <span data-ttu-id="2fc56-148">初始移轉完成後，系統每 24 小時會進行一次同步作業，將所有變更同步至雲端，直到管理員停止或刪除批次移轉。</span><span class="sxs-lookup"><span data-stu-id="2fc56-148">After the initial migration is complete, any changes are synchronized to the cloud every 24 hours until the administrator stops or deletes the migration batch.</span></span>
    
<span data-ttu-id="2fc56-p110">要切換使用者到雲端信箱，管理員會設定他們的 MX 紀錄指向 Office 365，並且在 Outlook 設定使用者檔案。使用者切換到雲端信箱時，他們的本機離線資料夾（.ost 檔案）會將重新同步化，結果會將遷移郵件下載到用戶端工作站。遷移之後，使用者可以回覆郵箱中的舊訊息。</span><span class="sxs-lookup"><span data-stu-id="2fc56-p110">To switch users to their cloud mailboxes, administrators configure their MX record to point to Office 365 and reconfigure the users' profiles in Outlook. When users switch to their cloud mailboxes, their local offline folders (.ost files) will resynchronize, resulting in the download of migrated mail to the client workstation. Users can reply to old messages in their mailboxes after migration.</span></span>
  
<span data-ttu-id="2fc56-152">如需轉換 Exchange 遷移的詳細資訊，請參閱[將電子郵件完全移轉到 Office 365 所需注意的事項](https://support.office.com/en-us/article/What-you-need-to-know-about-a-cutover-email-migration-to-Office-365-961978ef-f434-472d-a811-1801733869da)。</span><span class="sxs-lookup"><span data-stu-id="2fc56-152">For more information about a cutover Exchange migration, see [What you need to know about a cutover email migration to Office 365](https://support.office.com/en-us/article/What-you-need-to-know-about-a-cutover-email-migration-to-Office-365-961978ef-f434-472d-a811-1801733869da).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="2fc56-p111">組織可以使用 Exchange 完全移轉，將最多 2,000 個信箱從 Exchange 2003、Exchange 2007、Exchange 2010 或 Exchange 2013 信箱移轉至雲端。 > Exchange Online 必須連線到一個內部部署 Exchange 伺服器，所以內部部署伺服器必須具備由可信賴之憑證授權單位所發出的憑證，以及一個公開的 IP 位址。</span><span class="sxs-lookup"><span data-stu-id="2fc56-p111">An organization can migrate a maximum of 2,000 Exchange 2003, Exchange 2007, Exchange 2010, or Exchange 2013 mailboxes to the cloud using a cutover Exchange migration. > Exchange Online must connect to an on-premises Exchange Server, so the on-premises server must have a certificate issued by a trusted certificate authority and a public IP address.</span></span> 
  
### <a name="staged-exchange-migration"></a><span data-ttu-id="2fc56-155">Exchange 分段移轉</span><span class="sxs-lookup"><span data-stu-id="2fc56-155">Staged Exchange migration</span></span>

<span data-ttu-id="2fc56-p112">分段遷移的方法讓使用者能使用網路架構的 Exchange 工具，以及目錄同步處理工具來遷移至雲端。管理員不會一次遷移所有使用者，例如轉換 Exchange 遷移，而是分批遷移使用者。完成方式為上傳一個 .csv 檔案以指定遷移的使用者部份名單。在分段遷移中，組織內的所有使用者都能分享相同的電子郵件網域名稱。</span><span class="sxs-lookup"><span data-stu-id="2fc56-p112">With a staged migration, users can be migrated to the cloud using the web-based Exchange migration tool and the Directory Synchronization tool. Instead of migrating all users at once, like a cutover Exchange migration, administrators migrate users in batches. This is accomplished by uploading a .csv file to specify a partial list of users to migrate. In a staged migration, all of the users in an organization can share the same email domain name.</span></span>
  
<span data-ttu-id="2fc56-p113">分段 Exchange 遷移要求管理員使用線上服務目錄同步處理工具。這將提供使用者一個統一的全球通訊清單（GAL），線上環境會持續和內部部署環境進行同步化。</span><span class="sxs-lookup"><span data-stu-id="2fc56-p113">Staged Exchange migration requires administrators to use the Online Services Directory Synchronization tool. This provides users with a unified Global Address List (GAL) where the online environment is continuously synchronized with the on-premises environment.</span></span>
  
<span data-ttu-id="2fc56-162">如需分段 Exchange 遷移的詳細資訊，請參閱[將電子郵件分段移轉到 Office 365 所需注意的事項](https://support.office.com/en-ie/article/What-you-need-to-know-about-a-staged-email-migration-to-Office-365-7e2c82be-5f3d-4e36-bc6b-e5b4d411e207)。</span><span class="sxs-lookup"><span data-stu-id="2fc56-162">For more information about staged Exchange migrations, see [What you need to know about a staged email migration](https://support.office.com/en-ie/article/What-you-need-to-know-about-a-staged-email-migration-to-Office-365-7e2c82be-5f3d-4e36-bc6b-e5b4d411e207).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="2fc56-p114">組織不能使用 Exchange 分段移轉來移轉 Exchange 2010 和 Exchange 2013 信箱。如果組織中的 Exchange 2010 或 Exchange 2013 信箱少於 2,000 個，您可以使用 Exchange 完全移轉。如果您有超過 2,000 個 Exchange 2010 或 Exchange 2013 信箱，可以實作混合部署。 > 在遷移期間，管理員必須使用線上服務目錄同步處理工具，以提供使用者統一的全球通訊清單，線上環境將持續與內部部署環境進行同步化。</span><span class="sxs-lookup"><span data-stu-id="2fc56-p114">Organizations can't use a staged Exchange migration to migrate Exchange 2010 and Exchange 2013 mailboxes. If you have fewer than 2,000 Exchange 2010 or Exchange 2013 mailboxes in your organization, you can use a cutover Exchange migration. If you have more than 2,000 Exchange 2010 or Exchange 2013 mailboxes, you can implement a hybrid deployment. > During migration, administrators must use the Online Services Directory Synchronization tool to provide users with a unified Global Address List where the online environment is continuously synchronized with the on-premises environment.</span></span> 
  
## <a name="migration-tools"></a><span data-ttu-id="2fc56-167">遷移工具</span><span class="sxs-lookup"><span data-stu-id="2fc56-167">Migration tools</span></span>

<span data-ttu-id="2fc56-p115">Microsoft 提供數種工具以協助將現存電子郵件環境遷移至 Exchange Online。至於合適者為哪些，將視組織目前環境與內部部署目的而定：</span><span class="sxs-lookup"><span data-stu-id="2fc56-p115">Microsoft provides several tools to help migrate an existing email environment to Exchange Online. Which ones are appropriate depends on the organization's current environment and deployment goals:</span></span>
  
- <span data-ttu-id="2fc56-p116">**移轉儀表板** 管理員可使用 Exchange 系統管理中心的 [移轉] 儀表板，將信箱以 Exchange 完全或分段移轉的方式移轉至 Exchange Online。管理員也可以使用儀表板，將使用者信箱內容從內部部署 IMAP 伺服器移轉至現有的 Exchange Online 信箱。儀表板為管理員提供了以下功能：</span><span class="sxs-lookup"><span data-stu-id="2fc56-p116">**Migration dashboard** Administrators can use the Migration dashboard in the Exchange admin center to manage mailbox migration to Exchange Online in a cutover or staged Exchange migration. Administrators can also use the dashboard to migrate the contents of users' mailboxes from an on-premises IMAP server to existing Exchange Online mailboxes. The dashboard gives administrators the following capabilities:</span></span> 
    
  - <span data-ttu-id="2fc56-p117">**建立和啟動多個移轉批次** 管理員可以建立並在佇列中存放最多 100 個移轉批次。一次只執行一個遷移批次，不過管理員能將多重批次排入佇列，因此當一個遷移批次執行完畢，下一個佇列批次便能開始。</span><span class="sxs-lookup"><span data-stu-id="2fc56-p117">**Create and start multiple migration batches** Administrators can create and queue up to 100 migration batches. Only one migration batch runs at a time, but administrators can queue up multiple batches, so when a migration batch is finished running the next batch in the queue starts.</span></span> 
    
  - <span data-ttu-id="2fc56-p118">**重新啟動失敗的遷移批次**初始同步處理移轉批次，其中項目從內部部署信箱複製至雲端信箱遷移批次中每個使用者之後, 一些信箱可能會失敗同步處理。系統管理員可以重新啟動該遷移批次，以嘗試進行同步處理失敗的信箱。</span><span class="sxs-lookup"><span data-stu-id="2fc56-p118">**Restart a migration batch with failures** After the initial synchronization for a migration batch, where items are copied from on-premises mailboxes to the cloud mailboxes for each user in the migration batch, some mailboxes may fail synchronization. Administrators can restart that migration batch to try to synchronize the failed mailboxes.</span></span> 
    
  - <span data-ttu-id="2fc56-177">**取得略過項目之詳細資料** 針對 IMAP 移轉、完全移轉和分段移轉，[移轉] 儀表板會顯示略過之特定項目資訊，其中包括：原因以及該項目位於使用者信箱的哪個位置。</span><span class="sxs-lookup"><span data-stu-id="2fc56-177">**Get details about skipped items** For IMAP migrations, cutover migrations, and staged migrations, the Migration dashboard displays information about the specific items that were skipped, including the reason why and where the item is located in the user's mailbox.</span></span> 
    
  - <span data-ttu-id="2fc56-178">**開啟遷移報告**系統管理員可以開啟遷移統計或遷移錯誤報告的遷移批次右儀表板。</span><span class="sxs-lookup"><span data-stu-id="2fc56-178">**Open migration reports** Administrators can open migration statistics or the migration error report for a migration batch right from the dashboard.</span></span> 
    
  - <span data-ttu-id="2fc56-179">**編輯移轉批次**如果分段的 Exchange 遷移或 IMAP 遷移的遷移批次，但目前未執行移轉佇列中系統管理員可以編輯遷移批次。</span><span class="sxs-lookup"><span data-stu-id="2fc56-179">**Edit a migration batch** If a migration batch for a staged Exchange migration or an IMAP migration is in the migration queue but not currently running, administrators can edit the migration batch.</span></span> 
    
- <span data-ttu-id="2fc56-p119">**Azure Active Directory 同步處理工具**Azure Active Directory 同步處理工具在移轉中扮演重要的角色，混合使用 Exchange Online 與內部部署 Exchange Server 的電子郵件案例。工具的作用為進行從內部部署 Active Directory 到 Exchange Online 的單向同步化。遷移完成之後，管理員僅需使用 Exchange Online 來管理 Active Directory 使用者和群組。此工具也可讓使用者維持一致的全域通訊清單 (GAL)，線上環境會持續和內部部署環境進行同步作業。</span><span class="sxs-lookup"><span data-stu-id="2fc56-p119">**Azure Active Directory Sync tool** The Azure Active Directory Sync tool plays an important role in migration to hybrid email scenarios that utilize both Exchange Online and an on-premises Exchange Server. The tool performs a one-way synchronization from on-premises Active Directory to Exchange Online. After migration is complete, administrators only need to use Exchange Online to manage Active Directory users and groups. The tool also provides users with a unified Global Address List where the online environment is continuously synchronized with the on-premises environment.</span></span> 
    
    <span data-ttu-id="2fc56-184">如需 Azure Active Directory 同步處理工具的詳細資訊，請參閱[目錄同步處理：藍圖](https://go.microsoft.com/fwlink/p/?LinkId=287034)。</span><span class="sxs-lookup"><span data-stu-id="2fc56-184">For more information about the Azure Active Directory Sync tool, see [Directory synchronization: Roadmap](https://go.microsoft.com/fwlink/p/?LinkId=287034).</span></span>
    
- <span data-ttu-id="2fc56-p120">**混合組態精靈**混合組態精靈簡化混合式部署程序來簡化的內部部署和 Exchange Online 的功能與服務的設定。採用 Exchange Server 2010 Service Pack 2 的一部分，混合組態精靈只在內部部署組織中執行，並具有下列元件：</span><span class="sxs-lookup"><span data-stu-id="2fc56-p120">**Hybrid Configuration Wizard** The Hybrid Configuration Wizard streamlines the hybrid deployment process by simplifying the on-premises and Exchange Online configuration of features and services. Introduced as part of Exchange Server 2010 Service Pack 2, the Hybrid Configuration Wizard is run only in on-premises organizations and has the following components:</span></span> 
    
  - <span data-ttu-id="2fc56-187">[Exchange 系統管理中心 (EAC)] 精靈會引導管理員透過完整的程序，進行混合部署的設定。</span><span class="sxs-lookup"><span data-stu-id="2fc56-187">An Exchange admin center (EAC) wizard that guides administrators through the end-to-end process for configuring a hybrid deployment.</span></span>
    
  - <span data-ttu-id="2fc56-188">一組 Exchange Management Shell（EMS）指令，安排設定過程。</span><span class="sxs-lookup"><span data-stu-id="2fc56-188">A set of Exchange Management Shell (EMS) commands that orchestrate the configuration process.</span></span>
    
    <span data-ttu-id="2fc56-189">如需有關混合設定精靈的詳細資訊，請參閱[混合設定精靈](https://go.microsoft.com/fwlink/p/?LinkId=271734)。</span><span class="sxs-lookup"><span data-stu-id="2fc56-189">For more information about the Hybrid Configuration Wizard, see [Hybrid Configuration Wizard](https://go.microsoft.com/fwlink/p/?LinkId=271734).</span></span>
    
- <span data-ttu-id="2fc56-p121">**遠端 Windows PowerShell**Exchange Online 2011 年 12 月的一部分服務更新、 遠端 Windows PowerShell 可用來協助疑難排解移轉錯誤。例如，系統管理員可以顯示遷移批次為遷移統計資料的診斷資訊以及為其主要的 SMTP 地址為基礎的使用者的診斷資訊。</span><span class="sxs-lookup"><span data-stu-id="2fc56-p121">**Remote Windows PowerShell** As part of the Exchange Online December 2011 Service Update, remote Windows PowerShell can be used to help troubleshoot migration errors. For instance, administrators can display diagnostic information for migration batches, as well as migration statistics and diagnostic information for users based on their primary SMTP addresses.</span></span> 
    
## <a name="feature-availability"></a><span data-ttu-id="2fc56-192">功能可用性</span><span class="sxs-lookup"><span data-stu-id="2fc56-192">Feature Availability</span></span>

<span data-ttu-id="2fc56-193">若要檢視 Office 365 計劃、獨立選項和內部部署解決方案中的功能可用性，請參閱 [Exchange Online 服務說明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="2fc56-193">To view feature availability across Office 365 plans, standalone options, and on-premise solutions see, [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

