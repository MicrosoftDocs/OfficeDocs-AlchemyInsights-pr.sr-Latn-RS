---
title: Popravka pravila transporta
ms.author: v-jmathew
author: v-jmathew
manager: dansimp
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000760"
- "7391"
ms.openlocfilehash: 635009ed4b78d2b05b0eef1f3298765b10f86ede
ms.sourcegitcommit: bd6a9cb5d357baee5134c0dea430afc2a035c810
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/09/2021
ms.locfileid: "50695860"
---
# <a name="fix-transport-rules"></a><span data-ttu-id="75576-102">Popravka pravila transporta</span><span class="sxs-lookup"><span data-stu-id="75576-102">Fix transport rules</span></span>

<span data-ttu-id="75576-103">Pravilo za Prilagođeno slanje pošte utiče na ovu poruku.</span><span class="sxs-lookup"><span data-stu-id="75576-103">A custom mail flow rule affected this message.</span></span> <span data-ttu-id="75576-104">Da biste redigovali tačno pravilo, uradite sledeće:</span><span class="sxs-lookup"><span data-stu-id="75576-104">To review the exact rule, do the following:</span></span>

1. <span data-ttu-id="75576-105">U rezultatima prosleđivanja, u okviru **dodatne informacije** zabeležite **GUID** ili **ime smernica**.</span><span class="sxs-lookup"><span data-stu-id="75576-105">In the submission results, under **Additional information**, note the **GUID** or the **Policy Name**.</span></span>
2. <span data-ttu-id="75576-106">Pokrenite Exchange Management Shell.</span><span class="sxs-lookup"><span data-stu-id="75576-106">Launch Exchange Management Shell.</span></span> <span data-ttu-id="75576-107">Više informacija potražite u članku [Otvaranje programskog dodatka Exchange Management Shell](https://go.microsoft.com/fwlink/?linkid=2101432).</span><span class="sxs-lookup"><span data-stu-id="75576-107">For more information, see [Open the Exchange Management Shell](https://go.microsoft.com/fwlink/?linkid=2101432).</span></span>
3. <span data-ttu-id="75576-108">Pokrene ovu komandu (pomoću GUID-a sa vaše prosleđivanja):  **"Uzmi-TransportRule-identitet" GUID "| FL \* opis**\*</span><span class="sxs-lookup"><span data-stu-id="75576-108">Run this command (using the GUID from your submission):  **Get-TransportRule -identity "GUID" | fl \* Description**\*</span></span>
4. <span data-ttu-id="75576-109">Pregledajte opis da biste videli podešene uslove koji utiču na poruku.</span><span class="sxs-lookup"><span data-stu-id="75576-109">Review the description to see the configured conditions that affected the message.</span></span>

<span data-ttu-id="75576-110">Da biste saznali više, pogledajte članak [transport](https://go.microsoft.com/fwlink/?linkid=2101523).</span><span class="sxs-lookup"><span data-stu-id="75576-110">To learn more, see [Get-TransportRule](https://go.microsoft.com/fwlink/?linkid=2101523).</span></span>
