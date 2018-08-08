---
title: "封緘された入札"
description: "封緘された入札"
author: ShylaThompson
manager: AnnBe
ms.date: 07/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: shylaw
audience: end-user
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 2405e676929ee3a49bce634b83c744f138fe401a
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---

# <a name="sealed-bidding"></a><span data-ttu-id="d40ba-103">封緘された入札</span><span class="sxs-lookup"><span data-stu-id="d40ba-103">Sealed bidding</span></span> 

[!include[banner](../../includes/banner.md)]

<span data-ttu-id="d40ba-104">見積依頼機能は、封緘された入札をサポートするように強化されました。</span><span class="sxs-lookup"><span data-stu-id="d40ba-104">The request for quotation capabilities will be enhanced to support sealed bidding.</span></span> <span data-ttu-id="d40ba-105">仕入先は、仕入先コラボレーション インターフェイスの専用フォームを通じて、.pdf の添付ファイルを含んだ入札を入力し、送信することができます。</span><span class="sxs-lookup"><span data-stu-id="d40ba-105">A vendor can enter and submit a bid including .pdf attachments via a dedicated form in vendor collaborating interface.</span></span> <span data-ttu-id="d40ba-106">入札は、調達担当者がアクセスできる RFQ のコンテキストでは表示されません。</span><span class="sxs-lookup"><span data-stu-id="d40ba-106">The bid will not be visible in the context of the RFQ that the procurement personnel have access to.</span></span> <span data-ttu-id="d40ba-107">入札は暗号化されて保存されます。</span><span class="sxs-lookup"><span data-stu-id="d40ba-107">The bid is stored encrypted.</span></span> <span data-ttu-id="d40ba-108">仕入先連絡先として登録されていて、かつ必要なロールのアクセス許可を持っている連絡担当者だけが、開封前の入札にアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="d40ba-108">Only the contact person registered as a vendor contact and having the required role permissions can access the bid before it is unsealed.</span></span> <span data-ttu-id="d40ba-109">有効期限が切れると、調達担当者が入札を開封できるようになり、その時点で、RFQ のコンテキスト内から仕入先の入札を表示できるようになります。</span><span class="sxs-lookup"><span data-stu-id="d40ba-109">The procurement personnel can unseal the bids after the expiration date, and from that point can see the vendor's bid in context of the RFQ.</span></span> <span data-ttu-id="d40ba-110">入札に対して有効期限内に行われたユーザー操作 (読み取りや書き込みを伴う操作) は、監査目的でログに記録され、その情報は入札の開封時に仕入先と調達担当者に開示されます。</span><span class="sxs-lookup"><span data-stu-id="d40ba-110">Any user action that reads or writes in the bid before the expiration date will be logged for audit purposes and that information will be available to the vendor and also to the procurement personnel when the bid is unsealed.</span></span>  

