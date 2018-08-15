---
title: "Dynamics 365 for Customer Service での顧客サービス管理設定の理解"
description: "Dynamics 365 for Customer Service の管理設定の新機能を説明します"
author: vippand
manager: mahesh
ms.date: 7/22/2018
ms.assetid: 516afbde-61a3-4718-8ce1-a4007ada5960
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 6854d6a0ca5d97ae26bf8a522e2249a11a82716c
ms.contentlocale: ja-jp
ms.lasthandoff: 08/15/2018

---
#  <a name="customer-service-admin-settings"></a><span data-ttu-id="199ee-103">Customer Service 管理設定</span><span class="sxs-lookup"><span data-stu-id="199ee-103">Customer Service admin settings</span></span> 

[!include[customer-service-core-release-notes banner](../../includes/customer-service-core-release-notes.md)]




<span data-ttu-id="199ee-104">Dynamics 365 の顧客の主要な目標の 1 つは、業務プロセスをすばやく展開することです。</span><span class="sxs-lookup"><span data-stu-id="199ee-104">One of the key goals for Dynamics 365 customers is quick deployment of their business processes.</span></span> <span data-ttu-id="199ee-105">Service Management モジュールは、顧客サービス マネージャーが、さまざまな顧客サービス プロセスを自動化し、エージェントのターンアラウンド時間を短縮し、顧客満足を最善にするのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="199ee-105">The Service Management module helps customer service managers automate various customer service processes, improve agent turn-around time, and lead toward optimum customer satisfaction.</span></span> <span data-ttu-id="199ee-106">Service Management は、パブリック キューまたはプライベート キューの構成、親子サポート案件設定のセットアップ、ルーティング規則の構成、自動レコード作成と更新ルールの構成、サービス レベル アグリーメント (SLA) のセットアップなど、顧客サービス タスクを構成して管理する機能を管理者に提供します。</span><span class="sxs-lookup"><span data-stu-id="199ee-106">Service Management provides an admin the ability to configure and manage customer service tasks such as configuring public or private queues, setting up parent-child case settings, configuring routing rules, configuring automatic record creation and update rules, and setting up service level agreements (SLAs), among other capabilities.</span></span>

<span data-ttu-id="199ee-107">最新リリースの Service Management は Customer Service ハブの下に移動しており、顧客サービス マネージャーはアプリケーション内から構成にアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="199ee-107">With the latest release, Service Management moves under the Customer Service Hub, enabling customer service managers to access the configurations from inside the application.</span></span> <span data-ttu-id="199ee-108">統一インターフェイスに基づく新しい Service Management では、サービス タスクを簡単に構成でき、生産性を高めることができます。</span><span class="sxs-lookup"><span data-stu-id="199ee-108">Built on the Unified Interface, the new Service Management helps to easily configure service tasks, enabling increased productivity.</span></span> 

<span data-ttu-id="199ee-109">Service Management には、Customer Service ハブのサイトマップからアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="199ee-109">You can access Service Management through the sitemap in the Customer Service Hub:</span></span> 

<span data-ttu-id="199ee-110">![](media/csh-sitemap-service-management.png "サイトマップから Service Management へのアクセス")</span><span class="sxs-lookup"><span data-stu-id="199ee-110">![](media/csh-sitemap-service-management.png "Accessing Service Management through the sitemap")</span></span>

<span data-ttu-id="199ee-111">Service Management 内では、さまざまな機能をカスタマイズできます。</span><span class="sxs-lookup"><span data-stu-id="199ee-111">Within Service Management, you can customize various features.</span></span> <span data-ttu-id="199ee-112">次のような機能です。</span><span class="sxs-lookup"><span data-stu-id="199ee-112">These include:</span></span>  

- <span data-ttu-id="199ee-113">**キュー**: Service Management のキューには再設計されたエクスペリエンスが付属し、割り当てられた作業の進捗の適切な優先順位付けと監視に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="199ee-113">**Queues**: Queues in Service Management come with a redesigned experience that helps to appropriately prioritize and monitor the progress of the assigned work.</span></span>

  <span data-ttu-id="199ee-114">![](media/service-management-queues.png "Service Management でのキューの使用")</span><span class="sxs-lookup"><span data-stu-id="199ee-114">![](media/service-management-queues.png "Using queues in Service Management")</span></span>

- <span data-ttu-id="199ee-115">**情報カテゴリ**: 情報カテゴリは、サポート案件、サポート情報の記事、製品、営業資料を分類する強力な機能であり、それによってエージェントの能力を高め、顧客への迅速な応答を促進します。</span><span class="sxs-lookup"><span data-stu-id="199ee-115">**Subjects**: Subjects are a powerful mechanism to classify cases, knowledge base articles, products, and sales literature, thereby empowering agents and facilitating quick responses to customers.</span></span>  

  <span data-ttu-id="199ee-116">![](media/service-management-subjects.png "Service Management での情報カテゴリの使用")</span><span class="sxs-lookup"><span data-stu-id="199ee-116">![](media/service-management-subjects.png "Using subjects in Service Management")</span></span>

- <span data-ttu-id="199ee-117">**サポート案件の設定**: 親子サポート案件の設定を使用すると、サポート案件をリンクでき、一般的な問題に対する応答と追跡が向上します。</span><span class="sxs-lookup"><span data-stu-id="199ee-117">**Case settings**: With the Parent-Child case settings, cases can be linked together, enabling better response and tracking for common issues.</span></span>  

- <span data-ttu-id="199ee-118">**ルーティング規則**: ルーティング規則は、手動介入なしで、適切なキュー、ユーザー、またはをチームへのサポート案件のルーティングを自動化します。</span><span class="sxs-lookup"><span data-stu-id="199ee-118">**Routing rules**: Routing rules help automatic routing of cases to the right queue, user, or team without any manual intervention.</span></span> 

- <span data-ttu-id="199ee-119">**自動レコード作成と更新ルール**: このルールでは、電子メール、ソーシャル アクティビティ、または他のカテゴリのアクティビティなどの入力アクティビティに基づいて、サポート案件や関連するレコードの作成または更新を自動化できます。</span><span class="sxs-lookup"><span data-stu-id="199ee-119">**Automatic record creation and update rules**: These rules allow automatic creation or update of a case or related record based on incoming activities like email, social activity, or other categories of activities.</span></span> 

- <span data-ttu-id="199ee-120">**権利**: 権利は、顧客に資格があるサポートの定義と定量化に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="199ee-120">**Entitlement**: Entitlements help define and quantify the support for which a customer is eligible.</span></span> <span data-ttu-id="199ee-121">時間数またはサポート案件数に基づいて、サポート条件を指定できます。</span><span class="sxs-lookup"><span data-stu-id="199ee-121">The support terms can be specified based on number of hours or number of cases.</span></span> 

  <span data-ttu-id="199ee-122">![](media/service-management-entitlements.png "権利の使用")</span><span class="sxs-lookup"><span data-stu-id="199ee-122">![](media/service-management-entitlements.png "Using entitlements")</span></span>

- <span data-ttu-id="199ee-123">**権利テンプレート**: 権利セットアップ用の再利用可能なテンプレートを使用して、エクスペリエンスをすばやく構成できます。</span><span class="sxs-lookup"><span data-stu-id="199ee-123">**Entitlement templates**: Entitlement templates enable a quick configuration experience by allowing reusable templates for setting up entitlements.</span></span>  

- <span data-ttu-id="199ee-124">**祝日スケジュール**: SLA が影響を受けないように、祝日の休業に対応できます。</span><span class="sxs-lookup"><span data-stu-id="199ee-124">**Holiday schedule**: Holiday schedule lets you accommodate holiday closures so that the SLA is not impacted.</span></span> 

  <span data-ttu-id="199ee-125">![](media/service-management-holiday-schedule.png "祝日のスケジューリング")</span><span class="sxs-lookup"><span data-stu-id="199ee-125">![](media/service-management-holiday-schedule.png "Scheduling holidays")</span></span>

- <span data-ttu-id="199ee-126">**顧客サービス スケジュール**: チームの営業時間を定義するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="199ee-126">**Customer service schedule**: Customer service schedule can be used to define the business hours for your team.</span></span>  

  <span data-ttu-id="199ee-127">![](media/service-management-customer-service-schedule.png "顧客サービス スケジュールの設定")</span><span class="sxs-lookup"><span data-stu-id="199ee-127">![](media/service-management-customer-service-schedule.png "Setting customer service schedule")</span></span>

- <span data-ttu-id="199ee-128">**サービス レベル アグリーメント**: サービス タスクのマイルストーンの合意に使用されます。</span><span class="sxs-lookup"><span data-stu-id="199ee-128">**Service level agreements**: Service level agreements are used for agreement on milestones of the service tasks.</span></span> <span data-ttu-id="199ee-129">サービス レベル アグリーメントは、祝日スケジュールと顧客サービス スケジュールで定義されている構成に従います。</span><span class="sxs-lookup"><span data-stu-id="199ee-129">Service level agreements adhere to the configurations defined in the holiday schedule and customer service schedule.</span></span>  

- <span data-ttu-id="199ee-130">**ナレッジ マネージメントの設定**: ナレッジ マネージメントとテキスト分析に対してエンティティを有効にするために使用されます。</span><span class="sxs-lookup"><span data-stu-id="199ee-130">**Knowledge management settings**: Knowledge management settings are used to enable entities for knowledge management and text analytics.</span></span> 






