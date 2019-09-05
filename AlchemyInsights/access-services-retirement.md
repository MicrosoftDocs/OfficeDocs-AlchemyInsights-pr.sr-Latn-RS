---
title: Penzione usluge pristupa
ms.author: pebaum
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "9000356"
- "2009"
ms.assetid: ''
ms.openlocfilehash: 197366882468ebc87fc26f2fe2733371790d1871
ms.sourcegitcommit: a65d196d00adb70045af5caca9828fe44b951f61
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/04/2019
ms.locfileid: "36747798"
---
# <a name="access-services-retirement"></a><span data-ttu-id="5cd4b-102">Penzione usluge pristupa</span><span class="sxs-lookup"><span data-stu-id="5cd4b-102">Access services retirement</span></span>

<span data-ttu-id="5cd4b-103">Kao što smo prvobitno objavili u MC97576, u martu 2017, i nastavila da komuniciramo u proteklih godinu dana Access servisi se penzioniraju iz Officea 365.</span><span class="sxs-lookup"><span data-stu-id="5cd4b-103">As we originally announced in MC97576, in March 2017, and continued to communicate over the past year Access Services are being retired from Office 365.</span></span> <span data-ttu-id="5cd4b-104">Sledeća faza u ovom procesu će biti uklanjanje Access Web baza podataka koje koriste SharePoint liste kao svoje osnovno skladište podataka.</span><span class="sxs-lookup"><span data-stu-id="5cd4b-104">The next phase in this process will be the removal of Access Web Databases that use SharePoint lists as their underlying data storage.</span></span>

<span data-ttu-id="5cd4b-105">**Kako to utiče na mene?**</span><span class="sxs-lookup"><span data-stu-id="5cd4b-105">**How does this affect me?**</span></span>

<span data-ttu-id="5cd4b-106">Počevši od juna 2019, Zaustavićemo kreiranje novih Access baza podataka u sistemu SharePoint Online i isključiti uslugu i sve preostale aplikacije do aprila 2020.</span><span class="sxs-lookup"><span data-stu-id="5cd4b-106">Starting June 2019, we will stop creation of new Access databases in SharePoint Online and shut down the service and any remaining apps by April 2020.</span></span>

<span data-ttu-id="5cd4b-107">**Šta mi je potrebno da bih se pripremio za ovu promenu?**</span><span class="sxs-lookup"><span data-stu-id="5cd4b-107">**What do I need to do to prepare for this change?**</span></span>

<span data-ttu-id="5cd4b-108">Savetujemo vam da kreirate plan tranzicije za Web baze podataka u vašoj organizaciji.</span><span class="sxs-lookup"><span data-stu-id="5cd4b-108">We encourage you to create a transition plan for your organization’s Access web databases.</span></span> <span data-ttu-id="5cd4b-109">Administratori mogu da koriste [skener aplikacija za SharePoint Access](https://github.com/SharePoint/PnP-Tools/tree/master/Solutions/SharePoint.AccessApp.Scanner) da bi nabavili popis Access aplikacija koje lokacije koriste.</span><span class="sxs-lookup"><span data-stu-id="5cd4b-109">Admins can use the [SharePoint Access app scanner](https://github.com/SharePoint/PnP-Tools/tree/master/Solutions/SharePoint.AccessApp.Scanner) to obtain an inventory of the Access apps that sites are using.</span></span>

<span data-ttu-id="5cd4b-110">Postoji nekoliko načina za migraciju podataka iz Access Web baza podataka:</span><span class="sxs-lookup"><span data-stu-id="5cd4b-110">There are several ways to migrate Access web databases data:</span></span>

- <span data-ttu-id="5cd4b-111">Uvozi u lokalnu Access bazu podataka (. ACCDB) ili u Excel datoteku.</span><span class="sxs-lookup"><span data-stu-id="5cd4b-111">Importing to a local Access database (.ACCDB) or to an Excel file.</span></span>
- <span data-ttu-id="5cd4b-112">Takođe preporučujemo da istražujete Microsoft PowerApps kao alternativnu platformu da biste kreirali poslovnu rešenja za Web i mobilne uređaje.</span><span class="sxs-lookup"><span data-stu-id="5cd4b-112">We also recommend exploring Microsoft PowerApps as an alternative platform to create no-code business solutions for web and mobile devices.</span></span>