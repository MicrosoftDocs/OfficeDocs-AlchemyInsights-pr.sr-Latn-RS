---
title: Pristup odbijen prilikom prikazivanja toka posla
ms.author: pebaum
author: pebaum
ms.date: 11/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 47ceb983-f9a4-4c55-a40c-03d5c3d75dc9
ms.openlocfilehash: 1cfda8e08ada05858a28f2bede8c31261f9de351
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/15/2019
ms.locfileid: "40050539"
---
# <a name="access-denied-when-viewing-a-workflow"></a><span data-ttu-id="a36f6-102">Pristup odbijen prilikom prikazivanja toka posla</span><span class="sxs-lookup"><span data-stu-id="a36f6-102">Access denied when viewing a Workflow</span></span>

<span data-ttu-id="a36f6-103">SharePoint 2013 tokovi posla koji pokušaju da pošalju e-poruku SharePoint grupi mogu da uspeju sa porukom o grešci "pristup nije dozvoljen" Ako članstvo SharePoint grupe nije postavljeno na svakoga.</span><span class="sxs-lookup"><span data-stu-id="a36f6-103">SharePoint 2013 Workflows that attempt to send an email to a SharePoint group can fail with an "Access Denied" error message if the membership of the SharePoint group is not set to Everyone.</span></span>
  
 <span data-ttu-id="a36f6-104">**Da biste rešili ovaj problem, izvršite ove korake:**</span><span class="sxs-lookup"><span data-stu-id="a36f6-104">**To resolve this issue, do these steps:**</span></span>
  
 1. <span data-ttu-id="a36f6-105">Dozvolite svima da vide članove SharePoint grupe.</span><span class="sxs-lookup"><span data-stu-id="a36f6-105">Allow everybody to see the members of the SharePoint group.</span></span>
  
 2. <span data-ttu-id="a36f6-106">Uklonite SharePoint grupu iz reda "za" ili "CC" e-poruke.</span><span class="sxs-lookup"><span data-stu-id="a36f6-106">Remove the SharePoint group from the To or CC line of the email.</span></span>
  
 3. <span data-ttu-id="a36f6-107">Izričito dodajte korisnike u red "za" ili "CC" Ako se ne može promeniti vidljivost članstva za SharePoint grupu.</span><span class="sxs-lookup"><span data-stu-id="a36f6-107">Explicitly add the users to the To or CC line if the membership visibility cannot be changed for SharePoint group.</span></span>
  
<span data-ttu-id="a36f6-108">Da biste prikazali više detalja, pogledajte [http neovlašćen do/_vti_bin/Client.svc/SP.Utilities.Utility.sendemail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="a36f6-108">To view more details please refer to [HTTP Unauthorized to /_vti_bin/client.svc/sp.utilities.utility.SendEmail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).</span></span>
  