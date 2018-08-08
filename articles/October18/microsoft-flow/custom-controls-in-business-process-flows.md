---
title: "業務プロセス フロー内のカスタム コントロール"
description: "業務プロセス フローは、カスタム コントロールや業務ルールを含むあらゆるフォーム機能をサポートします。"
author: KaranSr
manager: AnnBe
ms.date: 7/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: karansr
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: fda7f78e07a45b66e870904f44776fcdeb799d05
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---
# <a name="custom-controls-in-business-process-flows"></a><span data-ttu-id="8b44e-103">業務プロセス フロー内のカスタム コントロール</span><span class="sxs-lookup"><span data-stu-id="8b44e-103">Custom controls in business process flows</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="8b44e-104">業務プロセス フローは、顧客が業務プロセスを辿り、最も重要なデータに注目するための、ガイド付きの方法を提供します。</span><span class="sxs-lookup"><span data-stu-id="8b44e-104">Business process flows provide a guided way for customers to walk through their business processes and focus on the data that is most important to them.</span></span> <span data-ttu-id="8b44e-105">業務プロセスに関するフィールドのみを関連するステージにカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="8b44e-105">It encapsulates only the fields pertinent to a business process into relevant stages.</span></span> <span data-ttu-id="8b44e-106">これらのフィールドはステップと呼ばれ、アプリ用 Common Data Service (CDS) エンティティ属性にバインドされます。</span><span class="sxs-lookup"><span data-stu-id="8b44e-106">These fields are referred to as steps and are bound to Common Data Service for Apps (CDS) entity attributes.</span></span> <span data-ttu-id="8b44e-107">以前の業務プロセス フローでは、使用可能な XRM 属性の種類 (テキスト、オプション セット、参照、数など) だけが、業務プロセス フローのステージ内のコントロール手順として表示されることを許可されました。</span><span class="sxs-lookup"><span data-stu-id="8b44e-107">Previously, business process flows only permitted the available XRM attribute types (such as text, optionset, lookup, number, and so on) to be surfaced as control steps inside business process flow stages.</span></span> <span data-ttu-id="8b44e-108">現在は、統一インターフェイスと Web クライアントの両方で豊富な対話機能を提供するカスタム コントロールがサポートされています。</span><span class="sxs-lookup"><span data-stu-id="8b44e-108">Now, custom controls, which offer rich interaction mechanisms both in Unified Interface and the Web Client, are supported.</span></span> <span data-ttu-id="8b44e-109">スライダー、放射状ノブ、タイムライン、LinkedIn コントロールなどのコントロールが強化されます。</span><span class="sxs-lookup"><span data-stu-id="8b44e-109">They power controls such as sliders, radial knobs, timelines, and even the LinkedIn controls.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="8b44e-110">![カスタム コントロールの例](media/custom-controls_01.png "カスタム コントロールの例")</span><span class="sxs-lookup"><span data-stu-id="8b44e-110">![Example of custom controls](media/custom-controls_01.png "Example of custom controls")</span></span>

<span data-ttu-id="8b44e-111">この機能は、わかりやすくてイマーシブなプロセス ランタイム エクスペリエンスの可能性を高めます。</span><span class="sxs-lookup"><span data-stu-id="8b44e-111">This feature increases the potential for intuitive and immersive process runtime experiences.</span></span>


