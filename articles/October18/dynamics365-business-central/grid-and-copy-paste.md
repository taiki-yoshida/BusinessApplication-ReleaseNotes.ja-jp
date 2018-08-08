---
title: "コピーと貼り付けによるグリッドの機能向上"
description: "リストの読み込みの向上と、行をコピーして貼り付ける機能。"
author: mikebcMSFT
manager: edupont04
ms.date: 07/22/2018
ms.assetid: 011c924e-f156-4cd7-a034-99a13b5a7869
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: mikebc
audience: end user
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 31954e79880f4b4f2d2737a74321b6334af88889
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---
#  <a name="improved-grid-with-copy-and-paste"></a><span data-ttu-id="14081-103">コピーと貼り付けによるグリッドの機能向上</span><span class="sxs-lookup"><span data-stu-id="14081-103">Improved grid with copy and paste</span></span>

[!include[banner](../../includes/banner.md)]
[!include[banner](Includes/disclaimer.md)]

<span data-ttu-id="14081-104">向上したグリッドのスケーラビリティと行をコピーして貼り付ける機能を使用すると、Dynamics 365 Business Central でのリストの作業が効率化されます。</span><span class="sxs-lookup"><span data-stu-id="14081-104">Work efficiently in lists in Dynamics 365 Business Central with improved grid scalability and the ability to copy and paste rows.</span></span>

<span data-ttu-id="14081-105">バックオフィスのインフォメーション ワーカーは、傾向と異常の分析やデータの入力と変更などで、リストに関する作業に多くの時間を費やします。</span><span class="sxs-lookup"><span data-stu-id="14081-105">Back-office information workers spend significant time working with lists: analyzing trends and anomalies or entering and modifying data.</span></span> <span data-ttu-id="14081-106">業務データベースが大きくなっても、エクスペリエンスはパフォーマンスを維持し、ユーザーが効率的に作業を続けられるようにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="14081-106">As the business database grows, the experience must remain performant and enable users to continue working efficiently.</span></span> <span data-ttu-id="14081-107">データの反復入力タスクは前に入力されているデータをコピーすると大幅に時間を短縮でき、ユーザーは、そのレベルの生産性向上のために Ctrl + C などの業界標準のキーボード ショートカットを期待します。</span><span class="sxs-lookup"><span data-stu-id="14081-107">Repetitive data entry tasks can be greatly accelerated by copying data entered earlier, and users expect industry-standard keyboard shortcuts such as Ctrl+C to help achieve that level of productivity.</span></span> <span data-ttu-id="14081-108">また、クリップボードにデータをコピーできると、ソフトウェアの境界をまたぐデータの移動が容易になります (たとえば、割引品目のリストを顧客へのメールに貼り付ける、など)。</span><span class="sxs-lookup"><span data-stu-id="14081-108">Being able to copy data to the clipboard also facilitates moving data across software boundaries, such as pasting a list of discounted items into an email to a customer.</span></span>

## <a name="improved-grid"></a><span data-ttu-id="14081-109">グリッドの機能向上</span><span class="sxs-lookup"><span data-stu-id="14081-109">Improved grid</span></span>
<span data-ttu-id="14081-110">リストの表示方法とデータのフェッチ方法が修正されて、グリッドに表示できる行数と列数が増えます。</span><span class="sxs-lookup"><span data-stu-id="14081-110">We've rewritten how lists are displayed and how they fetch data, allowing grids to scale to more rows and more columns.</span></span> <span data-ttu-id="14081-111">これにより、グリッドのセル間の移動の全体的な機敏性が向上します。</span><span class="sxs-lookup"><span data-stu-id="14081-111">This improves the overall snappiness of navigating across grid cells.</span></span> <span data-ttu-id="14081-112">行のプリロードの頻度が上がると、シームレスなスクロール エクスペリエンスに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="14081-112">Preloading rows more frequently makes for a seamless scrolling experience.</span></span> <span data-ttu-id="14081-113">ユーザーはキーボードまたはスクロール バーを使用してリスト内のどこにでもスクロールでき、ビュー内のデータはすぐに表示されます。</span><span class="sxs-lookup"><span data-stu-id="14081-113">Users can now scroll to any position in the list using the keyboard or scroll bar, and the data in view will display immediately.</span></span>

## <a name="copy-and-paste"></a><span data-ttu-id="14081-114">コピーと貼り付け</span><span class="sxs-lookup"><span data-stu-id="14081-114">Copy and paste</span></span>
<span data-ttu-id="14081-115">次のことができます。</span><span class="sxs-lookup"><span data-stu-id="14081-115">This enables you to:</span></span>

* <span data-ttu-id="14081-116">リスト内の 1 つまたは複数の行をコピーし、同じ (または似た) リストに貼り付けます。</span><span class="sxs-lookup"><span data-stu-id="14081-116">Copy one or more rows in a list and paste them to the same (or similar) list.</span></span>
* <span data-ttu-id="14081-117">1 つまたは複数の行をコピーし、列のキャプションも含めて、Microsoft Excel に貼り付けます。</span><span class="sxs-lookup"><span data-stu-id="14081-117">Copy one or more rows and paste them into Microsoft Excel, including the column captions.</span></span>
  <span data-ttu-id="14081-118">Excel を使用していない場合</span><span class="sxs-lookup"><span data-stu-id="14081-118">Not using Excel?</span></span> <span data-ttu-id="14081-119">Microsoft Outlook などのほとんどのアプリケーションでは表形式のコンテンツを貼り付けることができ、列のキャプションが表示されます。</span><span class="sxs-lookup"><span data-stu-id="14081-119">Most applications such as Microsoft Outlook allow pasting tabular content where the column captions will be displayed.</span></span>
* <span data-ttu-id="14081-120">Excel から 1 つまたは複数の行をコピーし、Business Central に貼り付けます。</span><span class="sxs-lookup"><span data-stu-id="14081-120">Copy one or more rows from Excel and paste them into DBusiness Central.</span></span>

## <a name="keyboard-shortcuts"></a><span data-ttu-id="14081-121">キーボード ショートカット</span><span class="sxs-lookup"><span data-stu-id="14081-121">Keyboard shortcuts</span></span>
<span data-ttu-id="14081-122">業界標準のショートカットである Ctrl + V および Ctrl + C に加えて、要望の多かった、上にあるセルをコピーする F8 ショートカットが追加されました。</span><span class="sxs-lookup"><span data-stu-id="14081-122">Apart from the industry-standard shortcuts Ctrl+C and Ctrl+V, we've added the highly requested F8 shortcut that copies the cell above.</span></span> <span data-ttu-id="14081-123">Tab キーでセル間を移動し、上にある行の値をコピーしたいセルで F8 キーを押すことにより、新しい行にすばやく入力できます。</span><span class="sxs-lookup"><span data-stu-id="14081-123">You can rapidly fill in a new row by tabbing across cells and selecting F8 on the cells where you want to copy the value from the row above.</span></span>

<!--
### Who uses these features
These features are available to all desktop users without additional setup in the browser or Windows 10 companion app.
## Status
### Availability
Cloud, on-premises, hybrid
### Regional availability
No regional restrictions. Available to all Dynamics 365 Business Central supported markets.
-->

## <a name="tell-us-what-you-think"></a><span data-ttu-id="14081-124">フィードバック</span><span class="sxs-lookup"><span data-stu-id="14081-124">Tell us what you think</span></span>
<span data-ttu-id="14081-125">Dynamics 365 Business Central の機能向上のため、アイデアを検討したり、提案したり、フィードバックを提供してください。</span><span class="sxs-lookup"><span data-stu-id="14081-125">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="14081-126">Business Central フォーラム (https://aka.ms/businesscentralfeedback) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="14081-126">Use the Business Central forum at https://aka.ms/businesscentralfeedback.</span></span>

