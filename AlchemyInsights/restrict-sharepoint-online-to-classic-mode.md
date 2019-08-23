---
title: Ograničite SharePoint Online na klasičan način
ms.author: kirks
author: Techwriter40
ms.date: 3/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6e99da1c-e61d-40ba-855e-1a8f346e42fd
ms.custom:
- "1835"
- "1889"
- "9000225"
ms.openlocfilehash: e7ecfd8c2f1a532355bfb8c2c0a846fc0d6e88b1
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36551573"
---
# <a name="restrict-sharepoint-online-to-classic-mode"></a><span data-ttu-id="919b3-102">Ograničite SharePoint Online na klasičan način</span><span class="sxs-lookup"><span data-stu-id="919b3-102">Restrict SharePoint Online to classic mode</span></span>

<span data-ttu-id="919b3-103">Neke organizacije su potrebni klasični režim iskustvo.</span><span class="sxs-lookup"><span data-stu-id="919b3-103">Some organizations still require the Classic mode experience.</span></span> <span data-ttu-id="919b3-104">Dok ga ne planira da se ukloni klasični režim na osnovnom nivou, ona više neće biti moguće da biste ograničili celu organizaciju (stanar) klasični režim za liste i biblioteke.</span><span class="sxs-lookup"><span data-stu-id="919b3-104">While there are no plans to remove classic mode at a granular level, it is no longer possible to restrict an entire organization (tenant) to classic mode for lists and libraries.</span></span>

<span data-ttu-id="919b3-105">U admin će imati sledeće opcije za upravljanje pojedinačnim listama i bibliotekama u klasični režimu pomoću zrnasti saglasnosti prekidači koje pružamo na sledeće nivoe:</span><span class="sxs-lookup"><span data-stu-id="919b3-105">The admin will have the following options to manage individual lists and libraries in classic mode using granular opt-out switches that we provide at the following levels:</span></span>

- <span data-ttu-id="919b3-106">kolekcija lokacija</span><span class="sxs-lookup"><span data-stu-id="919b3-106">site collection</span></span>
- <span data-ttu-id="919b3-107">lokacija</span><span class="sxs-lookup"><span data-stu-id="919b3-107">site</span></span>
- <span data-ttu-id="919b3-108">lista</span><span class="sxs-lookup"><span data-stu-id="919b3-108">list</span></span>
- <span data-ttu-id="919b3-109">biblioteka</span><span class="sxs-lookup"><span data-stu-id="919b3-109">library</span></span>

<span data-ttu-id="919b3-110">Pored toga, liste koje koriste određene funkcije i prilagođavanja koja ne podržava moderne će i dalje biti automatski prebacio na klasičan način.</span><span class="sxs-lookup"><span data-stu-id="919b3-110">Additionally, lists that use certain features and customizations that are not supported by modern will still be automatically switched to classic mode.</span></span>

<span data-ttu-id="919b3-111">April 1, 2019 godine, proces da biste onemogućili nivo stanar saglasnost moderne listi i biblioteka će početi, a traje do 31 maja, 2019.</span><span class="sxs-lookup"><span data-stu-id="919b3-111">Beginning April 1, 2019, the process to disable the tenant level opt out of modern list and libraries will start and continue through May 31, 2019.</span></span>  <span data-ttu-id="919b3-112">Liste i biblioteke koje se nalaze u klasični režim kao rezultat stanar saglasnosti biće automatski pomereni u moderni.</span><span class="sxs-lookup"><span data-stu-id="919b3-112">The lists and libraries that are in classic mode as a result of tenant opt-out will automatically be shifted to modern.</span></span>

<span data-ttu-id="919b3-113">Ako je potrebno da klasični režimu pogledajte više informacija [ovde](https://techcommunity.microsoft.com/t5/Microsoft-SharePoint-Blog/Delivering-SharePoint-modern-experiences/ba-p/315023) i uputstvo za PnP Powershell [ovde](https://docs.microsoft.com/sharepoint/dev/transform/modernize-userinterface-lists-and-libraries-optout) koji opisuje opcije i alatke koje možete koristiti danas klasični režim iskustvo.</span><span class="sxs-lookup"><span data-stu-id="919b3-113">If you require classic mode please see more information [here](https://techcommunity.microsoft.com/t5/Microsoft-SharePoint-Blog/Delivering-SharePoint-modern-experiences/ba-p/315023) and PnP Powershell instruction [here](https://docs.microsoft.com/sharepoint/dev/transform/modernize-userinterface-lists-and-libraries-optout) that describes options and tools you can use today to use the classic mode experience.</span></span>
