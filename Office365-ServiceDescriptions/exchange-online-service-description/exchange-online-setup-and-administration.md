---
title: Exchange Online 設定與管理
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-administration-and-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 80c07748-ac57-4b90-97dd-a2d1115009a6
description: 本文說明可自訂 Exchange Online 設定並保持組織的 Exchange Online 環境為已啟動、執行及目前狀態的管理控制和支援。 其中包括以下相關資訊：可供組織使用的自助管理工具和功能；Microsoft 管理責任和效能承諾；以及服務和產品升級。
ms.openlocfilehash: 19ec50b3f502ee111de05e1a115d17f16fec3569
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132998"
---
# <a name="exchange-online-setup-and-administration"></a><span data-ttu-id="2d0f5-104">Exchange Online 設定與管理</span><span class="sxs-lookup"><span data-stu-id="2d0f5-104">Exchange Online setup and administration</span></span>

<span data-ttu-id="2d0f5-105">本文說明可自訂 Exchange Online 設定並保持組織的 Exchange Online 環境為已啟動、執行及目前狀態的管理控制和支援。</span><span class="sxs-lookup"><span data-stu-id="2d0f5-105">This article describes the administration controls and support that are available to customize Exchange Online settings and keep an organization's Exchange Online environment up, running, and current.</span></span> <span data-ttu-id="2d0f5-106">其中包括以下相關資訊：可供組織使用的自助管理工具和功能；Microsoft 管理責任和效能承諾；以及服務和產品升級。</span><span class="sxs-lookup"><span data-stu-id="2d0f5-106">It includes information about self-service administration tools and capabilities available to organizations; Microsoft administration responsibilities and performance commitments; and service and product upgrades.</span></span>
  
## <a name="self-service-administration-tools"></a><span data-ttu-id="2d0f5-107">自助系統管理工具</span><span class="sxs-lookup"><span data-stu-id="2d0f5-107">Self-service administration tools</span></span>

<span data-ttu-id="2d0f5-108">雖然 Microsoft 直接控制所有 Exchange Online 資料中心，並負責整體系統效能，但它只會控制結合的部分元素，以提供使用者的整體經驗。</span><span class="sxs-lookup"><span data-stu-id="2d0f5-108">Although Microsoft directly controls all Exchange Online data centers and is responsible for overall system performance, it can control only a portion of the elements that combine to provide the total experience for users.</span></span> <span data-ttu-id="2d0f5-109">組織須自行負責與資料中心的網路連線、客戶的廣域網路 (WAN) 以及客戶的區域網路 (LAN)。</span><span class="sxs-lookup"><span data-stu-id="2d0f5-109">Organizations themselves are responsible for the network connections to the data centers, the customer's wide area network (WAN), and the customer's local area networks (LANs).</span></span> <span data-ttu-id="2d0f5-110">此外，他們也負責使用者裝置和其設定。</span><span class="sxs-lookup"><span data-stu-id="2d0f5-110">Additionally, they are in charge of user devices and their configuration.</span></span><span data-ttu-id="2d0f5-111">他們也須負責維護每個使用者針對任何功能所需的授權，包括 (但不限於) 管理這些功能的能力，直到使用者不需存取該功能為止。</span><span class="sxs-lookup"><span data-stu-id="2d0f5-111">  They are also responsible for maintaining the required licensing per user for any desired feature, including, but not limited to, the ability to manage these features, for as long as the user needs access to the feature.</span></span>
  
<span data-ttu-id="2d0f5-112">因此，Exchange Online 提供客戶系統管理員下列工具 (如下所述)，以管理各種訊息相關工作：</span><span class="sxs-lookup"><span data-stu-id="2d0f5-112">Exchange Online therefore provides customer administrators with the following tools, described below, to manage a variety of messaging-related tasks:</span></span>
  
- [<span data-ttu-id="2d0f5-113">Microsoft Office 365 入口網站</span><span class="sxs-lookup"><span data-stu-id="2d0f5-113">Microsoft Office 365 portal</span></span>](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [<span data-ttu-id="2d0f5-114">Microsoft 365 系統管理中心</span><span class="sxs-lookup"><span data-stu-id="2d0f5-114">Microsoft 365 admin center</span></span>](#microsoft-365-admin-center)
    
- [<span data-ttu-id="2d0f5-115">Exchange 系統管理中心</span><span class="sxs-lookup"><span data-stu-id="2d0f5-115">Exchange admin center</span></span>](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [<span data-ttu-id="2d0f5-116">Exchange Online 的遠端 Windows PowerShell</span><span class="sxs-lookup"><span data-stu-id="2d0f5-116">Remote Windows PowerShell for Exchange Online</span></span>](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a><span data-ttu-id="2d0f5-117">Microsoft Office 365 入口網站</span><span class="sxs-lookup"><span data-stu-id="2d0f5-117">Microsoft Office 365 portal</span></span>

<span data-ttu-id="2d0f5-118">位於 [https://portal.office.com](https://portal.office.com) 的 Microsoft Office 365 入口網站，可供系統管理員與合作夥伴購買和管理 Office 365 服務，並讓使用者存取及使用 Office 365 共同作業工具。</span><span class="sxs-lookup"><span data-stu-id="2d0f5-118">The Microsoft Office 365 portal, at [https://portal.office.com](https://portal.office.com), is the website through which administrators and partners purchase and manage Office 365 services and where users access and use Office 365 collaborative tools.</span></span>
  
### <a name="microsoft-365-admin-center"></a><span data-ttu-id="2d0f5-119">Microsoft 365 系統管理中心</span><span class="sxs-lookup"><span data-stu-id="2d0f5-119">Microsoft 365 admin center</span></span>

<span data-ttu-id="2d0f5-120">Microsoft 365 系統管理中心是一個網頁入口網站，每個公司的服務管理員可以從該入口網站管理每個訂閱的 Microsoft 服務的使用者帳戶和設定。</span><span class="sxs-lookup"><span data-stu-id="2d0f5-120">The Microsoft 365 admin center is the web portal from which each company's service administrator can manage user accounts and settings for each of the Microsoft services to which they subscribe.</span></span> <span data-ttu-id="2d0f5-121">在 Microsoft 365 系統管理中心內，管理員可以追蹤 Exchange 系統管理中心（EAC）的連結，以便在其中管理 Exchange Online 特有的設定。</span><span class="sxs-lookup"><span data-stu-id="2d0f5-121">From within the Microsoft 365 admin center, administrators can follow links to the Exchange admin center (EAC), where they can manage settings specific to Exchange Online.</span></span> <span data-ttu-id="2d0f5-122">如需使用 Microsoft 365 系統管理中心開始及執行的詳細資訊，請參閱下列影片： [Office 365 Enterprise 簡介](https://go.microsoft.com/fwlink/p/?LinkId=271806)。</span><span class="sxs-lookup"><span data-stu-id="2d0f5-122">For more information about getting up and running using the Microsoft 365 admin center, see the following video: [Introducing Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806).</span></span>
  
### <a name="exchange-admin-center"></a><span data-ttu-id="2d0f5-123">Exchange 系統管理中心</span><span class="sxs-lookup"><span data-stu-id="2d0f5-123">Exchange admin center</span></span>

<span data-ttu-id="2d0f5-124">Exchange Online provides a single unified management console that allows for ease of use and is optimized for management of on-premises, online, or hybrid deployments.</span><span class="sxs-lookup"><span data-stu-id="2d0f5-124">Exchange Online provides a single unified management console that allows for ease of use and is optimized for management of on-premises, online, or hybrid deployments.</span></span> <span data-ttu-id="2d0f5-125">The Exchange admin center (EAC) is where administrators can manage Exchange-specific settings.</span><span class="sxs-lookup"><span data-stu-id="2d0f5-125">The Exchange admin center (EAC) is where administrators can manage Exchange-specific settings.</span></span>
  
<span data-ttu-id="2d0f5-126">如需有關如何使用 EAC 管理 Exchange Online 的詳細資訊，請參閱 [Exchange 系統管理中心](https://go.microsoft.com/fwlink/p/?LinkId=271807)。</span><span class="sxs-lookup"><span data-stu-id="2d0f5-126">For more information about how to use the EAC to manage Exchange Online, see [Exchange admin center](https://go.microsoft.com/fwlink/p/?LinkId=271807).</span></span>
  
### <a name="remote-windows-powershell-for-exchange-online"></a><span data-ttu-id="2d0f5-127">Exchange Online 的遠端 Windows PowerShell</span><span class="sxs-lookup"><span data-stu-id="2d0f5-127">Remote Windows PowerShell for Exchange Online</span></span>

<span data-ttu-id="2d0f5-128">Using remote Windows PowerShell, administrators can connect to Exchange Online to perform management tasks that are not available or practical using the EAC.</span><span class="sxs-lookup"><span data-stu-id="2d0f5-128">Using remote Windows PowerShell, administrators can connect to Exchange Online to perform management tasks that are not available or practical using the EAC.</span></span> <span data-ttu-id="2d0f5-129">These include the ability to automate repetitive tasks, extract data for custom reports, customize policies, and connect Exchange Online to existing infrastructure and processes.</span><span class="sxs-lookup"><span data-stu-id="2d0f5-129">These include the ability to automate repetitive tasks, extract data for custom reports, customize policies, and connect Exchange Online to existing infrastructure and processes.</span></span> <span data-ttu-id="2d0f5-130">For more information, see [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).</span><span class="sxs-lookup"><span data-stu-id="2d0f5-130">For more information, see [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).</span></span>
  
<span data-ttu-id="2d0f5-131">Exchange Online uses the same Windows PowerShell cmdlets as Exchange Server 2013, with certain commands and parameters unavailable because these features do not apply in Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="2d0f5-131">Exchange Online uses the same Windows PowerShell cmdlets as Exchange Server 2013, with certain commands and parameters unavailable because these features do not apply in Exchange Online.</span></span> <span data-ttu-id="2d0f5-132">For a list of cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span><span class="sxs-lookup"><span data-stu-id="2d0f5-132">For a list of cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span></span>
  
<span data-ttu-id="2d0f5-133">Administrators do not need to install any Exchange Server management or migration tools to use remote Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="2d0f5-133">Administrators do not need to install any Exchange Server management or migration tools to use remote Windows PowerShell.</span></span> <span data-ttu-id="2d0f5-134">However, administrators' computers must be running the Windows Management Framework 3.0, which contains Windows PowerShell v3 and WinRM 3.0; and Windows .NET Framework 4.5.</span><span class="sxs-lookup"><span data-stu-id="2d0f5-134">However, administrators' computers must be running the Windows Management Framework 3.0, which contains Windows PowerShell v3 and WinRM 3.0; and Windows .NET Framework 4.5.</span></span> <span data-ttu-id="2d0f5-135">These components are already installed on computers running Windows 8 or Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="2d0f5-135">These components are already installed on computers running Windows 8 or Windows Server 2012.</span></span> <span data-ttu-id="2d0f5-136">Administrators can manually download these components for computers that are running Windows 7 or Windows Server 2008 R2.</span><span class="sxs-lookup"><span data-stu-id="2d0f5-136">Administrators can manually download these components for computers that are running Windows 7 or Windows Server 2008 R2.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="2d0f5-137">為防止拒絕服務 (DoS) 攻擊，您最多只能對您的 Exchange Online 組織建立三個 Windows PowerShell 連線。</span><span class="sxs-lookup"><span data-stu-id="2d0f5-137">To help prevent denial of service (DoS) attacks, you're limited to three open Windows PowerShell connections to your Exchange Online organization.</span></span> 
  
## <a name="self-service-capabilities-for-exchange-online"></a><span data-ttu-id="2d0f5-138">Exchange Online 自助功能</span><span class="sxs-lookup"><span data-stu-id="2d0f5-138">Self-service capabilities for Exchange Online</span></span>

<span data-ttu-id="2d0f5-139">Below are important capabilities that are available for managing Exchange Online by using the EAC, remote Windows PowerShell, and other tools.</span><span class="sxs-lookup"><span data-stu-id="2d0f5-139">Below are important capabilities that are available for managing Exchange Online by using the EAC, remote Windows PowerShell, and other tools.</span></span> <span data-ttu-id="2d0f5-140">Many other settings can also be controlled with these tools, as described throughout this document.</span><span class="sxs-lookup"><span data-stu-id="2d0f5-140">Many other settings can also be controlled with these tools, as described throughout this document.</span></span>
  
### <a name="mobile-device-security-policies-for-exchange-online"></a><span data-ttu-id="2d0f5-141">Exchange Online 的行動裝置安全性原則</span><span class="sxs-lookup"><span data-stu-id="2d0f5-141">Mobile device security policies for Exchange Online</span></span>

<span data-ttu-id="2d0f5-142">Exchange Online supports the same ActiveSync policies for mobile devices as Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="2d0f5-142">Exchange Online supports the same ActiveSync policies for mobile devices as Exchange Server 2013.</span></span> <span data-ttu-id="2d0f5-143">Administrators can enforce and customize these security policies for specific users and groups by using the EAC or remote Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="2d0f5-143">Administrators can enforce and customize these security policies for specific users and groups by using the EAC or remote Windows PowerShell.</span></span>
  
### <a name="message-tracking-for-exchange-online"></a><span data-ttu-id="2d0f5-144">Exchange Online 的郵件追蹤</span><span class="sxs-lookup"><span data-stu-id="2d0f5-144">Message tracking for Exchange Online</span></span>

<span data-ttu-id="2d0f5-145">透過「傳遞回報」功能進行的郵件追蹤會在下列主題中說明：[報告功能和疑難排解工具](reporting-features-and-troubleshooting-tools.md)。</span><span class="sxs-lookup"><span data-stu-id="2d0f5-145">Message tracking via the Delivery Reports feature is described in the following topic: [Reporting features and troubleshooting tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
### <a name="usage-reporting-for-exchange-online"></a><span data-ttu-id="2d0f5-146">Exchange Online 的使用報告</span><span class="sxs-lookup"><span data-stu-id="2d0f5-146">Usage reporting for Exchange Online</span></span>

<span data-ttu-id="2d0f5-147">Administrators can use remote Windows PowerShell to retrieve information about how people in their organizations use the Exchange Online service.</span><span class="sxs-lookup"><span data-stu-id="2d0f5-147">Administrators can use remote Windows PowerShell to retrieve information about how people in their organizations use the Exchange Online service.</span></span> <span data-ttu-id="2d0f5-148">Available information includes:</span><span class="sxs-lookup"><span data-stu-id="2d0f5-148">Available information includes:</span></span>
  
- <span data-ttu-id="2d0f5-149">顯示組織中每個使用者的信箱大小。</span><span class="sxs-lookup"><span data-stu-id="2d0f5-149">Showing the mailbox size for each user in the organization.</span></span>
    
- <span data-ttu-id="2d0f5-150">顯示信箱上已設定的自訂權限，例如委派存取。</span><span class="sxs-lookup"><span data-stu-id="2d0f5-150">Displaying custom permissions that are set on mailboxes, such as delegate access.</span></span>
    
- <span data-ttu-id="2d0f5-151">擷取有關行動裝置存取的資料，例如，哪些使用者透過 Exchange ActiveSync 進行連線、使用哪些裝置，以及最後一次的連線時間。</span><span class="sxs-lookup"><span data-stu-id="2d0f5-151">Extracting data about mobile device access, such as which users are connecting through Exchange ActiveSync, what devices they are using, and when they last connected.</span></span>
    
<span data-ttu-id="2d0f5-152">Remote Windows PowerShell cmdlets that start with "get-" can fetch data from the Exchange Online system.</span><span class="sxs-lookup"><span data-stu-id="2d0f5-152">Remote Windows PowerShell cmdlets that start with "get-" can fetch data from the Exchange Online system.</span></span> <span data-ttu-id="2d0f5-153">Administrators can export this information from Windows PowerShell in .csv format for advanced analysis or reporting.</span><span class="sxs-lookup"><span data-stu-id="2d0f5-153">Administrators can export this information from Windows PowerShell in .csv format for advanced analysis or reporting.</span></span>
  
<span data-ttu-id="2d0f5-154">如需有關可與 Exchange Online 搭配使用的 Windows PowerShell Cmdlet 的詳細資訊，請參閱 [Exchange Online Cmdlet](https://go.microsoft.com/fwlink/p/?LinkId=271808)。</span><span class="sxs-lookup"><span data-stu-id="2d0f5-154">For more information about Windows PowerShell cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span></span>
  
### <a name="auditing-for-exchange-online"></a><span data-ttu-id="2d0f5-155">Exchange Online 的稽核</span><span class="sxs-lookup"><span data-stu-id="2d0f5-155">Auditing for Exchange Online</span></span>

<span data-ttu-id="2d0f5-156">下列主題說明「審核記錄」功能：[報告功能和疑難排解工具](reporting-features-and-troubleshooting-tools.md)。</span><span class="sxs-lookup"><span data-stu-id="2d0f5-156">The audit logging feature is described in the following topic: [Reporting features and troubleshooting tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
## <a name="service-and-product-upgrades-for-exchange-online"></a><span data-ttu-id="2d0f5-157">Exchange Online 的服務和產品升級</span><span class="sxs-lookup"><span data-stu-id="2d0f5-157">Service and product upgrades for Exchange Online</span></span>

<span data-ttu-id="2d0f5-158">Exchange Online customers benefit from periodic upgrades to the latest Exchange technology, including new releases of Exchange Server.</span><span class="sxs-lookup"><span data-stu-id="2d0f5-158">Exchange Online customers benefit from periodic upgrades to the latest Exchange technology, including new releases of Exchange Server.</span></span> <span data-ttu-id="2d0f5-159">These upgrades are made available at no additional charge, and ensure that customers are always using the latest Exchange software.</span><span class="sxs-lookup"><span data-stu-id="2d0f5-159">These upgrades are made available at no additional charge, and ensure that customers are always using the latest Exchange software.</span></span>
  
<span data-ttu-id="2d0f5-160">在 Microsoft 發行 Exchange 的主要版本後，客戶必須在 12 個月內，將服務升級為新版本。</span><span class="sxs-lookup"><span data-stu-id="2d0f5-160">After a major version of Exchange is released by Microsoft, customers have up to 12 months to upgrade their service to the new release.</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="2d0f5-161">功能可用性</span><span class="sxs-lookup"><span data-stu-id="2d0f5-161">Feature availability</span></span>

<span data-ttu-id="2d0f5-162">若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online 服務說明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="2d0f5-162">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
  