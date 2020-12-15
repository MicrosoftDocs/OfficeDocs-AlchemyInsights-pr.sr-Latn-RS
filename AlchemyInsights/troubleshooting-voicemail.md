---
title: 'Rešavanje problema sa govorne pošte '
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 12/09/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9002347"
- "7564"
ms.openlocfilehash: a2d26da512838ae112c352fe21366074b69fa224
ms.sourcegitcommit: 3802f2f4db4f53a408a360187db67f2296448c21
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/09/2020
ms.locfileid: "49679102"
---
# <a name="troubleshooting-voicemail"></a><span data-ttu-id="d1bd2-102">Rešavanje problema sa govorne pošte</span><span class="sxs-lookup"><span data-stu-id="d1bd2-102">Troubleshooting Voicemail</span></span>

<span data-ttu-id="d1bd2-103">Uverite se da je funkcija prometne na posao namerna.</span><span class="sxs-lookup"><span data-stu-id="d1bd2-103">Ensure that the Busy on Busy feature is intentional.</span></span>

<span data-ttu-id="d1bd2-104">Ako ova funkcija nije potrebna na ovom korisniku:</span><span class="sxs-lookup"><span data-stu-id="d1bd2-104">If this feature is not needed on this user:</span></span>

1. <span data-ttu-id="d1bd2-105">Idite u [Centar administracije](https://admin.teams.microsoft.com/policies/calling).</span><span class="sxs-lookup"><span data-stu-id="d1bd2-105">Go to [Teams Admin center](https://admin.teams.microsoft.com/policies/calling).</span></span>
1. <span data-ttu-id="d1bd2-106">U levoj železničkoj pruzi Pronađite **glas**  >    >  za smernice za **Upravljanje** smernicama za **pozivanje**.</span><span class="sxs-lookup"><span data-stu-id="d1bd2-106">On the left rail navigate **Voice** > **Calling policies** > **Manage Policies** on the **Calling Policy**.</span></span>
1. <span data-ttu-id="d1bd2-107">Izaberite stavku **Upravljanje korisnicima**.</span><span class="sxs-lookup"><span data-stu-id="d1bd2-107">Select **Manage Users**.</span></span>
1. <span data-ttu-id="d1bd2-108">Potražite korisnika i promenite smernice za pozivanje na onu koja je zauzeta **na poslu, kada je u pozivu** za **Isključivanje**.</span><span class="sxs-lookup"><span data-stu-id="d1bd2-108">Search for user and change the Calling Policy to one that has **Busy on Busy is available when in a call** to **Off**.</span></span>
1. <span data-ttu-id="d1bd2-109">Kliknite na dugme **Primeni**.</span><span class="sxs-lookup"><span data-stu-id="d1bd2-109">Click **Apply**.</span></span>
> [!NOTE]
> <span data-ttu-id="d1bd2-110">Promene smernica mogu da imaju do 24 časa za replikaciju.</span><span class="sxs-lookup"><span data-stu-id="d1bd2-110">Changes to policies can take up to 24 hours to replicate.</span></span>

<span data-ttu-id="d1bd2-111">Više informacija o ovoj funkciji upućuje na: [zauzeto na posao je dostupno dok ste u pozivu](https://docs.microsoft.com/microsoftteams/teams-calling-policy#busy-on-busy-is-available-while-in-a-call).</span><span class="sxs-lookup"><span data-stu-id="d1bd2-111">For more information on this feature refer to: [Busy on Busy is available while in a call](https://docs.microsoft.com/microsoftteams/teams-calling-policy#busy-on-busy-is-available-while-in-a-call).</span></span>
