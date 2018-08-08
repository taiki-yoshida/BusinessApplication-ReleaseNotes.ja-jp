---
title: "プロジェクトでの複数通貨の原価価格表の解決"
description: "プロジェクトでの複数通貨の原価価格表の解決"
author: rumant
manager: shellyhaverkamp
ms.date: 7/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: rumant
audience: developer, admin, end user, citizen developer, customizer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: dc40b9862dcb8c4e8eeb12168ab8497bc131c000
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---
#  <a name="resolution-of-multi-currency-cost-price-list-on-projects"></a><span data-ttu-id="6cd71-103">プロジェクトでの複数通貨の原価価格表の解決</span><span class="sxs-lookup"><span data-stu-id="6cd71-103">Resolution of multi-currency cost price list on projects</span></span> 


[!include[banner](../../../../includes/banner.md)]

<span data-ttu-id="6cd71-104">Project Service は、プロジェクトを所有する組織単位の通貨を価格表の通貨と一致させることで、プロジェクトの原価率の価格表を解決します。</span><span class="sxs-lookup"><span data-stu-id="6cd71-104">Project Service resolves the price list for cost rates on projects by matching the currency of the organizational unit that owns the project to the price list currency.</span></span> <span data-ttu-id="6cd71-105">価格表に複数通貨の価格がある場合、1 つのマスター価格表に複数通貨の原価率行があり、この価格表がすべてのプロジェクトでグローバルに使用されることが予想されます。</span><span class="sxs-lookup"><span data-stu-id="6cd71-105">In the case where a price list may have prices in multiple currencies, it's expected that there would be one master price list with cost rate lines in multiple currencies, and that this price list would be used by all projects globally.</span></span> 

<span data-ttu-id="6cd71-106">その状況では、価格表のヘッダーの通貨を使用したプロジェクトの原価価格表の解決が機能しなくなります。</span><span class="sxs-lookup"><span data-stu-id="6cd71-106">In that situation, resolving a cost price list for a project using the currency on the header of the price list would not work.</span></span> <span data-ttu-id="6cd71-107">この機能では、プロジェクトの原価価格表の既定の解決を設定するように構成できます。</span><span class="sxs-lookup"><span data-stu-id="6cd71-107">With this feature, it will be configurable to set up the default resolution of the project cost price list.</span></span> <span data-ttu-id="6cd71-108">使用可能なオプションは、プロジェクトのコスト通貨を現在機能している価格表のヘッダーと一致させるか、ヘッダー通貨に関係なく、グローバルに管理されている価格表を使用することです。</span><span class="sxs-lookup"><span data-stu-id="6cd71-108">The options available would be to match the project’s cost currency with the header of the price list as it works today or to use the globally managed price list regardless of its header currency.</span></span>  



