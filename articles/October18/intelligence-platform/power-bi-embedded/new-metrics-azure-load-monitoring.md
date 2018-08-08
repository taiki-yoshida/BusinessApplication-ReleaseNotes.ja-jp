---
title: "Azure 負荷監視用の新しいメトリック"
description: "Power BI Embedded のリソース消費を監視し、構成可能なしきい値を超えたときにアクションをトリガーするために、4 つの新しいメトリックが追加されました。"
author: MargoC
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 082d21ac-805e-4007-8810-f1838369569c
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 51b13a358399105084d85e62222aec8339d4b42f
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---
#  <a name="new-metrics-for-azure-load-monitoring"></a><span data-ttu-id="6ef37-103">Azure 負荷監視用の新しいメトリック</span><span class="sxs-lookup"><span data-stu-id="6ef37-103">New metrics for Azure load monitoring</span></span>

[!include[banner](../../../includes/banner.md)]

<span data-ttu-id="6ef37-104">Power BI Embedded のリソース消費を監視し、構成可能なしきい値を超えたときにアクションをトリガーするために、4 つの新しいメトリックが追加されました。</span><span class="sxs-lookup"><span data-stu-id="6ef37-104">Four new metrics were added to monitor Power BI Embedded resource consumption and trigger actions when configurable thresholds are exceeded:</span></span>

- <span data-ttu-id="6ef37-105">メモリ消費</span><span class="sxs-lookup"><span data-stu-id="6ef37-105">Memory consumption</span></span>
- <span data-ttu-id="6ef37-106">メモリ スラッシング</span><span class="sxs-lookup"><span data-stu-id="6ef37-106">Memory thrashing</span></span>
- <span data-ttu-id="6ef37-107">80% を超える CPU スパイク</span><span class="sxs-lookup"><span data-stu-id="6ef37-107">CPU spikes over 80 percent</span></span>
- <span data-ttu-id="6ef37-108">DirectQuery の使用状況</span><span class="sxs-lookup"><span data-stu-id="6ef37-108">DirectQuery usage</span></span>

<span data-ttu-id="6ef37-109">開発者は、Azure を使用してしきい値を定義し、特定のモニターが定義済みしきい値を超えるたびにリソースを自動スケールアップするなど、アラートを使用して特定のアクションをトリガーできます。</span><span class="sxs-lookup"><span data-stu-id="6ef37-109">Developers can use Azure to define thresholds to trigger specific actions using alerts, such as automatic scale-up of the resource whenever a specific monitor crosses a defined threshold.</span></span>

