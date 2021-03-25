---
title: Exchange Online Protection 的報告與訊息追蹤
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: 若要瞭解 Microsoft Exchange Online Protection (EOP) 中的報告與訊息追蹤，請閱讀本文。
ms.openlocfilehash: e07b7b9f6f7bee2715314021d9a7e96a29af8b21
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173328"
---
# <a name="reporting-and-message-trace-in-exchange-online-protection"></a><span data-ttu-id="c80a8-103">Exchange Online Protection 的報告與訊息追蹤</span><span class="sxs-lookup"><span data-stu-id="c80a8-103">Reporting and message trace in Exchange Online Protection</span></span>

<span data-ttu-id="c80a8-104">Microsoft Exchange Online Protection (EOP) 提供許多不同的報告，可協助您判斷貴組織的整體狀態與健全狀況。</span><span class="sxs-lookup"><span data-stu-id="c80a8-104">Microsoft Exchange Online Protection (EOP) offers many different reports that can help you determine the overall status and health of your organization.</span></span> <span data-ttu-id="c80a8-105">有些報告可在 Microsoft 365 系統管理中心中取得，而其他可在 Exchange 系統管理中心 (EAC) 中取得。</span><span class="sxs-lookup"><span data-stu-id="c80a8-105">Some reports are available in the Microsoft 365 admin center, while others are available in the Exchange admin center (EAC).</span></span>

<span data-ttu-id="c80a8-106">尋找所有 EOP 功能的相關資訊嗎？</span><span class="sxs-lookup"><span data-stu-id="c80a8-106">Looking for information about all EOP features?</span></span> <span data-ttu-id="c80a8-107">請參閱 [Exchange Online Protection 服務說明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="c80a8-107">See the [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>

## <a name="microsoft-365-admin-center-reports"></a><span data-ttu-id="c80a8-108">Microsoft 365 系統管理中心報告</span><span class="sxs-lookup"><span data-stu-id="c80a8-108">Microsoft 365 admin center reports</span></span>

<span data-ttu-id="c80a8-109">Microsoft 365 系統管理中心的 [報告] 頁面提供郵件流量、垃圾郵件和惡意程式碼偵測的相關資訊，以及受郵件流程規則影響的郵件 (也稱為傳輸規則) 或資料遺失防護 (DLP) 原則。</span><span class="sxs-lookup"><span data-stu-id="c80a8-109">The Reports page in the Microsoft 365 admin center provides information about message traffic, spam and malware detections, and messages affected by mail flow rules (also known as transport rules) or data loss prevention (DLP) policies.</span></span> <span data-ttu-id="c80a8-110">保護、規則和 DLP 的增強型報告可讓 EOP 系統管理員享有互動報告體驗。</span><span class="sxs-lookup"><span data-stu-id="c80a8-110">The enhanced reports for protection, rules, and DLP offer an interactive reporting experience for EOP admins.</span></span> <span data-ttu-id="c80a8-111">這些報告提供摘要資料，而且可供人向下切入至個別郵件的詳細資料。</span><span class="sxs-lookup"><span data-stu-id="c80a8-111">These reports provide summary data and the ability to drill down into details about individual messages.</span></span>

<span data-ttu-id="c80a8-112">如需這些報告的詳細資訊，請參閱 [Use mail protection reports 可查看有關惡意程式碼、垃圾郵件和規則](/exchange/monitoring/use-mail-protection-reports)偵測的資料。</span><span class="sxs-lookup"><span data-stu-id="c80a8-112">For more detailed information about these reports, see [Use mail protection reports to view data about malware, spam, and rule detections](/exchange/monitoring/use-mail-protection-reports).</span></span>

## <a name="reporting-using-web-services"></a><span data-ttu-id="c80a8-113">Reporting using web services</span><span class="sxs-lookup"><span data-stu-id="c80a8-113">Reporting using web services</span></span>

> [!NOTE]
> <span data-ttu-id="c80a8-114">許多 REST 型報表功能和相關 Cmdlet 在2018年1月已被取代。</span><span class="sxs-lookup"><span data-stu-id="c80a8-114">Many of the REST-based reporting features and related cmdlets were deprecated in January, 2018.</span></span> <span data-ttu-id="c80a8-115">如需 Office 365 中可用的取代 Microsoft Graph 報告的詳細資訊，請參閱使用 [Microsoft graph 的使用狀況報告](/graph/api/resources/report)一主題。</span><span class="sxs-lookup"><span data-stu-id="c80a8-115">For information about the available replacement Microsoft Graph reports in Office 365, see the subtopics of [Working with usage reports in Microsoft Graph](/graph/api/resources/report).</span></span>

<span data-ttu-id="c80a8-116">獨立式 EOP 客戶無法使用此功能。</span><span class="sxs-lookup"><span data-stu-id="c80a8-116">Not available to EOP standalone customers.</span></span> <span data-ttu-id="c80a8-117">您可以使用 REST/OData 租使用者報告 web 服務，以程式設計方式收集有關郵件資料的摘要和詳細報告，而且您可以在自訂 web 管理入口網站的網頁上顯示資料。</span><span class="sxs-lookup"><span data-stu-id="c80a8-117">You can use the REST/OData Tenant Reporting web service to programmatically collect summary and detailed reports about messaging data, and you can display the data on a web page in a custom web management portal.</span></span>

## <a name="message-trace"></a><span data-ttu-id="c80a8-118">郵件追蹤</span><span class="sxs-lookup"><span data-stu-id="c80a8-118">Message trace</span></span>

<span data-ttu-id="c80a8-119">EAC 中的郵件追蹤功能可讓您以系統管理員身分遵循 EOP 中的電子郵件訊息。</span><span class="sxs-lookup"><span data-stu-id="c80a8-119">The message trace feature in the EAC lets you, as an administrator, follow email messages as they pass through the EOP.</span></span> <span data-ttu-id="c80a8-120">它可以協助您判斷服務是否已接收、拒絕、延遲或傳遞目標電子郵件訊息。</span><span class="sxs-lookup"><span data-stu-id="c80a8-120">It helps you determine whether a targeted email message was received, rejected, deferred, or delivered by the service.</span></span> <span data-ttu-id="c80a8-121">它也會顯示郵件在達到其最終狀態前所發生過的動作。</span><span class="sxs-lookup"><span data-stu-id="c80a8-121">It also shows what actions have occurred to the message before reaching its final status.</span></span> <span data-ttu-id="c80a8-122">取得特定郵件的詳細資訊可讓您有效回答使用者的問題、疑難排解郵件流程問題、驗證原則變更，以及減少了需要連絡技術支援尋求協助的需求。</span><span class="sxs-lookup"><span data-stu-id="c80a8-122">Obtaining detailed information about a specific message lets you efficiently answer your user's questions, troubleshoot mail flow issues, validate policy changes, and alleviates the need to contact technical support for assistance.</span></span> <span data-ttu-id="c80a8-123">如需詳細資訊，請參閱 [執行郵件追蹤並在 Exchange 系統管理中心中查看結果](/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results)。</span><span class="sxs-lookup"><span data-stu-id="c80a8-123">For more information, see [Run a message trace and view the results in the Exchange admin center](/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results).</span></span>

## <a name="feature-availability"></a><span data-ttu-id="c80a8-124">功能可用性</span><span class="sxs-lookup"><span data-stu-id="c80a8-124">Feature availability</span></span>

<span data-ttu-id="c80a8-125">若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱 [Exchange Online Protection 服務說明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="c80a8-125">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>