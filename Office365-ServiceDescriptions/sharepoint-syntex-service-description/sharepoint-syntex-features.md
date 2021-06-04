---
title: SharePoint Syntext 功能 (部分機器翻譯)
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: 深入瞭解合格的 Microsoft 365、Office 365 和 SharePoint 的線上方案中提供的主要 SharePoint Syntex 功能。
ms.openlocfilehash: 2ffc3ccb52d074434c89424a151e63c7698b62c2
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/09/2021
ms.locfileid: "51651028"
---
# <a name="sharepoint-syntex-features"></a>SharePoint Syntext 功能 (部分機器翻譯) 

下列各節說明適用于符合條件 Microsoft 365、Office 365 和 SharePoint 線上方案的主要[SharePoint Syntex](sharepoint-syntex-service-description.md)功能。 可用的功能可能會變更，恕不另行通知。 如需最新的完整功能清單，請參閱[SharePoint Syntex 方案及定價] 頁面](https://www.microsoft.com/microsoft-365/enterprise/sharepoint-syntex)。

## <a name="syntex-content-center"></a>Syntex 內容中心

Syntex 提供一個 &mdash; 稱為 *內容中心* &mdash; 的網站範本，用以管理規模的內容、整合中繼資料和工作流程，以及提供法規遵從性自動化。 內容中心提供的功能可教雲端如何以您手動的方式閱讀和處理檔。 Syntex 會使用這些洞察力自動辨識內容、解壓縮重要資訊，並套用元資料標記。 此外，您可以使用整合式視覺分析追蹤模型的效能。

若要深入瞭解內容中心及其建立方式，請參閱[在 SharePoint Syntex 中建立內容中心](/microsoft-365/contentunderstanding/create-a-content-center)。

## <a name="object-recognition"></a>物件識別

Syntex 可以使用具有數千個普遍辨識物件的新視覺字典，自動標記影像。 此外，Syntex 可以辨識手寫的文字，並將其轉換成標記以供搜尋使用，並進行進一步處理。

若要深入瞭解 Syntex 中的物件識別及如何設定影像標記，請參閱[image 標記 in SharePoint Syntex](/microsoft-365/contentunderstanding/image-tagging)。

## <a name="document-understanding"></a>文件瞭解

您可以教 Syntex 以教學方式來閱讀您的內容，以利用機器教學來建立人工智慧 (AI) 模型，但沒有任何程式碼。 Syntex 可自動建議或建立中繼資料、呼叫自訂 Power Automate 工作流程，以及附加合規性標籤，以強制執行保留或記錄管理原則。

檔理解模型是以 Azure 認知服務中的語言瞭解模型為基礎。 這些模型是在 Syntex 內容中心內建立及管理，您可以將模型發佈並更新至任何內容中心內的任何文件庫中 Syntex。

若要深入瞭解檔瞭解，請參閱 [檔理解一覽](/microsoft-365/contentunderstanding/document-understanding-overview)。

## <a name="form-processing"></a>表單處理

Syntex 包含功能強大的表單處理引擎，以 AI 產生器為基礎，可讓您自動辨識及提取半結構化或結構化檔中的一般值，例如日期、圖表、名稱或位址。 這些模型是以不含程式碼為基礎的，只需要一些檔才能獲得可靠的結果。

若要深入瞭解表單處理，請參閱 [表單處理一覽](/microsoft-365/contentunderstanding/form-processing-overview)。

## <a name="microsoft-graph-content-connectors"></a>Microsoft Graph 內容連接器

Syntex 使用 microsoft Graph 連接器整合遠端來源 &mdash; ，例如檔案共用、Azure SQL 或協力廠商來源（如 Box 和 IBM FileNet &mdash; ）到 Microsoft Graph 中，使其可供搜尋並供整個 Microsoft 365 使用。

透過 microsoft Graph 連接器，客戶可以在外部存放庫中索引項目目，以包含在 microsoft 搜尋結果中。 Microsoft 365 E5 和 Office 365 E5 包含的功能是使用 microsoft Search (（不含于 A5) ）為 microsoft Search 的 microsoft Graph 連接器編制索引最多500個專案。 任何具有套件或獨立授權（包括 SharePoint 或 OneDrive 計畫）的使用者，都可以查看 microsoft 搜尋的 microsoft Graph 連接器中的搜尋結果。

現在，Microsoft 或我們的其中一個合作夥伴提供超過130個來源的連接器。 若要深入瞭解，請參閱[Microsoft Graph connector 的概述](/MicrosoftSearch/connectors-overview)。

## <a name="advanced-taxonomy-services"></a>高級分類法服務

Syntex 包含的功能可讓您觀賞及分析整個 Microsoft 365 中的字詞建立及使用方式。 這些報告會在 SharePoint 系統管理中心內傳遞。

共用內容類型可透過[SharePoint hub 網站](/sharepoint/dev/features/hub-site/hub-site-overview)發佈至 SharePoint 和 Microsoft Teams。 將內容類型從中央圖庫發佈到 hub sites，可提供更靈活的方式，以確保一般使用的內容類型（透過內容瞭解增強）可在必要時，快速地部署及升級到架構的各個廣泛區段。 連接到中樞的網站將會自動接收已發佈和更新的內容類型。