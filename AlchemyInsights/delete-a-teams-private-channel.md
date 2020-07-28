---
title: Brisanje timova privatni kanal
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/24/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3781"
- "9001223"
ms.openlocfilehash: 2ee998f0c70973645c273a2a6609af2420a4f74b
ms.sourcegitcommit: b10cea11b4975354b91193327b58aa4740d34833
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 07/28/2020
ms.locfileid: "45439916"
---
# <a name="delete-a-teams-private-channel"></a><span data-ttu-id="e6386-102">Brisanje timova privatni kanal</span><span class="sxs-lookup"><span data-stu-id="e6386-102">Delete a Teams private channel</span></span>

<span data-ttu-id="e6386-103">Microsoft je svestan problema koji će izbrisati privatni kanal timova ako imate omogućenu SharePoint smernice za zadržavanje za osnovnu SharePoint lokaciju.</span><span class="sxs-lookup"><span data-stu-id="e6386-103">Microsoft is aware of an issue deleting a Teams private channel if you have SharePoint Retention Policies enabled for the underlying SharePoint site.</span></span> <span data-ttu-id="e6386-104">Microsoft radi na ispravu.</span><span class="sxs-lookup"><span data-stu-id="e6386-104">Microsoft is working on a fix.</span></span> <span data-ttu-id="e6386-105">U međuvremenu, možete da koristite sledeća rešenja za brisanje privatnog kanala.</span><span class="sxs-lookup"><span data-stu-id="e6386-105">In the meantime, you can use the following workarounds to delete the private channel.</span></span>

<span data-ttu-id="e6386-106">**Izuzmite tim/kolekciju lokacija iz SharePoint smernica za zadržavanje.**</span><span class="sxs-lookup"><span data-stu-id="e6386-106">**Exclude the Team/site collection from the Sharepoint retention policy.**</span></span>

1. <span data-ttu-id="e6386-107">Posetite Office 365 admin portal i u levom oknu za navigaciju izaberite stavku " **Prikaži sve** ".</span><span class="sxs-lookup"><span data-stu-id="e6386-107">Go to the Office 365 admin portal, and select **Show all** in the left navigation pane.</span></span>
2. <span data-ttu-id="e6386-108">U okviru opcije " **admin centri**" Idite na **bezbednosnu &**  >  smernice za**sprečavanje gubitka podataka**  >  **Policy**.</span><span class="sxs-lookup"><span data-stu-id="e6386-108">Under **Admin centers**, go to **Security & Compliance** > **Data Loss Prevention** > **Policy**.</span></span>
3. <span data-ttu-id="e6386-109">Identifikujte sve smernice koje se odnose na SharePoint lokacije i izmenite smernice tako da SharePoint lokacija tima koji sadrži privatni kanal nije uključena u smernice za zadržavanje.</span><span class="sxs-lookup"><span data-stu-id="e6386-109">Identify any policy that applies to Sharepoint sites, and modify the policy so the Sharepoint site for the Team containing the private channel is NOT included under the retention policy.</span></span>
4. <span data-ttu-id="e6386-110">Sačuvajte smernice.</span><span class="sxs-lookup"><span data-stu-id="e6386-110">Save the policy.</span></span>
    <span data-ttu-id="e6386-111">Može da potraje i do 24 sata da bi postavke smernica stupile na snagu.</span><span class="sxs-lookup"><span data-stu-id="e6386-111">It can take up to 24 hours for policy settings to take effect.</span></span>
    <span data-ttu-id="e6386-112">Nakon što je lokacija isključena, možete da izbrišete privatni kanal.</span><span class="sxs-lookup"><span data-stu-id="e6386-112">After the site has been excluded, you can delete the private channel.</span></span>  
    
<span data-ttu-id="e6386-113">***Možda*** ćete moći da izbrišete privatni kanal pomoću Microsoft timova na vašem Android uređaju.</span><span class="sxs-lookup"><span data-stu-id="e6386-113">You  ***might*** be able to delete the private channel by using Microsoft Teams on your Android device.</span></span> 

<span data-ttu-id="e6386-114">Za srodne SharePoint informacije pogledajte odeljak [nije moguće izbrisati stavke u sistemu SharePoint Online ili OneDrive za posao](https://docs.microsoft.com/alchemyinsights/retention-policy-ediscovery-hold).</span><span class="sxs-lookup"><span data-stu-id="e6386-114">For related SharePoint information, see [Unable to delete items in SharePoint Online or OneDrive for Business](https://docs.microsoft.com/alchemyinsights/retention-policy-ediscovery-hold).</span></span>