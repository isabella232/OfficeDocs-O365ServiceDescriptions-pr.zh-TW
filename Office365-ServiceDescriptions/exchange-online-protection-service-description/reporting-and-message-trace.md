---
title: 報告和郵件追蹤
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
description: Microsoft Exchange Online Protection (EOP) 提供許多不同的報告，可協助您判斷貴組織的整體狀態與健全狀況。 有些報告可在 Microsoft 365 系統管理中心中取得，而其他則是在 Exchange 系統管理中心（EAC）中提供。
ms.openlocfilehash: 0fab453ae50454e9f613c0996b8baacc7081cb97
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132757"
---
# <a name="reporting-and-message-trace"></a>報告和郵件追蹤

Microsoft Exchange Online Protection (EOP) 提供許多不同的報告，可協助您判斷貴組織的整體狀態與健全狀況。 有些報告可在 Microsoft 365 系統管理中心中取得，而其他則是在 Exchange 系統管理中心（EAC）中提供。

尋找所有 EOP 功能的相關資訊嗎？ 請參閱[Exchange Online Protection 服務說明](exchange-online-protection-service-description.md)。

## <a name="microsoft-365-admin-center-reports"></a>Microsoft 365 系統管理中心報告

Microsoft 365 系統管理中心的 [報告] 頁面提供郵件流量、垃圾郵件和惡意程式碼偵測的相關資訊，以及受郵件流程規則（也稱為傳輸規則）或資料遺失防護（DLP）原則影響的郵件。 保護、規則和 DLP 的增強型報告可讓 EOP 系統管理員享有互動報告體驗。 這些報告提供摘要資料，而且可供人向下切入至個別郵件的詳細資料。

如需這些報告的詳細資訊，請參閱[Use mail protection reports 可查看有關惡意程式碼、垃圾郵件和規則](https://docs.microsoft.com/exchange/monitoring/use-mail-protection-reports)偵測的資料。

## <a name="reporting-using-web-services"></a>Reporting using web services

> [!NOTE]
> 許多 REST 型報表功能和相關 Cmdlet 在2018年1月已被取代。 如需 Office 365 中可用的取代 Microsoft Graph 報告的詳細資訊，請參閱使用[Microsoft graph 的使用狀況報告](https://go.microsoft.com/fwlink/p/?LinkID=865135)一主題。

獨立式 EOP 客戶無法使用此功能。 您可以使用 REST/OData 租使用者報告 web 服務，以程式設計方式收集有關郵件資料的摘要和詳細報告，而且您可以在自訂 web 管理入口網站的網頁上顯示資料。

## <a name="message-trace"></a>郵件追蹤

EAC 中的郵件追蹤功能可讓您以系統管理員身分遵循 EOP 中的電子郵件訊息。 它可以協助您判斷服務是否已接收、拒絕、延遲或傳遞目標電子郵件訊息。 它也會顯示郵件在達到其最終狀態前所發生過的動作。 取得特定郵件的詳細資訊可讓您有效回答使用者的問題、疑難排解郵件流程問題、驗證原則變更，以及減少了需要連絡技術支援尋求協助的需求。 如需詳細資訊，請參閱[執行郵件追蹤並在 Exchange 系統管理中心中查看結果](https://docs.microsoft.com/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results)。

## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online Protection 服務說明](exchange-online-protection-service-description.md)。
