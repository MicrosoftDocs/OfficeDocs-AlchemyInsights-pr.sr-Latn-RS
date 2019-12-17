---
title: Problemi sa performansama-SharePoint ili OneDrive
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1133"
- "2397"
- "2418"
- "5200018"
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.openlocfilehash: aecbf4043c6456ece73f7deed6b068040f0691a2
ms.sourcegitcommit: 0fb89d8106fe409ab1b78e50f5357ffc2252f7c7
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/17/2019
ms.locfileid: "40068430"
---
# <a name="sharepoint-or-onedrive-slow-inaccessible-or-unavailable-for-multiple-users"></a><span data-ttu-id="7c62c-102">SharePoint ili OneDrive spore, nepristupačne ili nedostupne za više korisnika</span><span class="sxs-lookup"><span data-stu-id="7c62c-102">SharePoint or OneDrive slow, inaccessible, or unavailable for multiple users</span></span>

<span data-ttu-id="7c62c-103">SharePoint ili OneDrive mogu da budu spore, nepristupačne ili nedostupne ili mogu da prikažu usluge nedostupne ili 503 grešaka, iz nekoliko razloga:</span><span class="sxs-lookup"><span data-stu-id="7c62c-103">SharePoint or OneDrive may be slow, inaccessible, or unavailable, or may display service unavailable or 503 errors, for several reasons:</span></span>
  
- <span data-ttu-id="7c62c-104">Ako je SharePoint ili OneDrive lokacija spora ili odložena za više korisnika, možda postoji problem sa privremenim servisom gde korisnici dovode do povremenih kašnjenja ili grešaka pri navigaciji prilikom pristupanja SharePoint lokacijama ili OneDrive sadržaju.</span><span class="sxs-lookup"><span data-stu-id="7c62c-104">If your SharePoint or OneDrive site is slow or delayed for multiple users, there may be a temporary service issue where users experience intermittent delays or navigation errors when accessing SharePoint sites or OneDrive content.</span></span> <span data-ttu-id="7c62c-105">Proverite da li je vaša organizacija uticala na [instrument za zdravstvo](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) .</span><span class="sxs-lookup"><span data-stu-id="7c62c-105">Check the [Service health dashboard](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) to see if your organization is impacted.</span></span>
  
- <span data-ttu-id="7c62c-106">Korisnici mogu da prime *503 server je zauzet* greškom prilikom pokušaja da se kreću na SharePoint ili OneDrive lokacije.</span><span class="sxs-lookup"><span data-stu-id="7c62c-106">Users may receive a *503 server is busy* error when attempting to navigate to SharePoint or OneDrive sites.</span></span> <span data-ttu-id="7c62c-107">Ova greška može biti izazvana regulisanja u okviru SharePoint usluge.</span><span class="sxs-lookup"><span data-stu-id="7c62c-107">This error can be caused by throttling within the SharePoint service.</span></span> <span data-ttu-id="7c62c-108">SharePoint online koristi ograničavanje za održavanje optimalnih performansi i pouzdanosti SharePoint usluge na mreži.</span><span class="sxs-lookup"><span data-stu-id="7c62c-108">SharePoint Online uses throttling to maintain optimal performance and reliability of the SharePoint Online service.</span></span> <span data-ttu-id="7c62c-109">Ograničavanje ograničava broj radnji korisnika ili uporedne pozive (po skripti ili kodu) da bi sprečio prekomerno korišćenje resursa.</span><span class="sxs-lookup"><span data-stu-id="7c62c-109">Throttling limits the number of user actions or concurrent calls (by script or code) to prevent overuse of resources.</span></span> <span data-ttu-id="7c62c-110">Za više informacija o regulisanja pogledajte, [izbegavajte ograničavanje ili blokiranje na lokaciji SharePoint online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span><span class="sxs-lookup"><span data-stu-id="7c62c-110">For more information on throttling see, [Avoid getting throttled or blocked in SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span></span>

- <span data-ttu-id="7c62c-111">Ako dođe do sporih performansi sa **klasičnom** ili **modernom** SharePoint lokacijom ili stranicom, koristite [dijagnostičku alatku stranice](https://aka.ms/perftool) da biste analizirali stranice.</span><span class="sxs-lookup"><span data-stu-id="7c62c-111">If you experience slow performance with a **classic** or **modern** SharePoint site or page, utilize the [Page Diagnostic tool](https://aka.ms/perftool) to analyze the pages.</span></span>
  
- <span data-ttu-id="7c62c-112">Ako i dalje nailazite na opšte sporije performanse, pregledajte resurse na dnu ovog članka: [Uvod u podešavanje performansi za SharePoint online](https://go.microsoft.com/fwlink/?linkid=2024334)</span><span class="sxs-lookup"><span data-stu-id="7c62c-112">If you still experience general slow performance, please review the resources at the bottom of this article: [Introduction to performance tuning for SharePoint Online](https://go.microsoft.com/fwlink/?linkid=2024334)</span></span>
  