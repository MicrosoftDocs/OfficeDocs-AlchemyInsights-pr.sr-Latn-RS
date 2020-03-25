---
title: Više informacija o problemima sa DLP-a
ms.author: pebaum
author: pebaum
manager: laurawi
ms.audience: admin
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "2447"
- "3200001"
ms.openlocfilehash: 6525cee0555f1ae67b7d4e32445b9a1537d4a804
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932708"
---
# <a name="information-about-dlp-issues"></a><span data-ttu-id="e19cd-102">Informacije o problemima sa DLP-a</span><span class="sxs-lookup"><span data-stu-id="e19cd-102">Information about DLP issues</span></span>

<span data-ttu-id="e19cd-103">**Važno**: mnogi korisnici usluge SharePoint Online i OneDrive pokreću poslovne aplikacije u odnosu na uslugu koja se pokreće u pozadini.</span><span class="sxs-lookup"><span data-stu-id="e19cd-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="e19cd-104">Ovo uključuje migraciju sadržaja, sprečavanje gubitka podataka (DLP) i rešenja za rezervno kopiranje.</span><span class="sxs-lookup"><span data-stu-id="e19cd-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="e19cd-105">U ovim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive budu veoma dostupne i pouzdane za korisnike koji zavise od usluge u udaljenim radnim scenarijima.</span><span class="sxs-lookup"><span data-stu-id="e19cd-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="e19cd-106">U cilju podrške ovom cilju, Implementirao sam strožije limite na aplikacije u pozadini (migracioni, DLP i Backup rešenja) tokom dana u danima u sedmici.</span><span class="sxs-lookup"><span data-stu-id="e19cd-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="e19cd-107">Trebalo bi da očekujete da će ove aplikacije ostvariti veoma ograničenu propusnost tokom ovih vremena.</span><span class="sxs-lookup"><span data-stu-id="e19cd-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="e19cd-108">Međutim, tokom večeri i vikenda u regionu, usluga će biti spremna da obradi znatno veći obim zahteva iz aplikacija u pozadini.</span><span class="sxs-lookup"><span data-stu-id="e19cd-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="e19cd-109">**Informacije o smernicama za DLP**</span><span class="sxs-lookup"><span data-stu-id="e19cd-109">**Information on DLP policy**</span></span>

<span data-ttu-id="e19cd-110">Pomoću datoteke sa DLP-om možete da identifikujete, nadgledate i automatski zaštitite osetljive informacije širom Officea 365.</span><span class="sxs-lookup"><span data-stu-id="e19cd-110">With a DLP policy, you can identify, monitor, and automatically protect sensitive information across Office 365.</span></span>

<span data-ttu-id="e19cd-111">Molimo vas da posetite ove veze za više informacija:</span><span class="sxs-lookup"><span data-stu-id="e19cd-111">Please visit these links for more information:</span></span>

- [<span data-ttu-id="e19cd-112">Pregled sprečavanja gubitka podataka</span><span class="sxs-lookup"><span data-stu-id="e19cd-112">Overview of data loss prevention</span></span>](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)
- [<span data-ttu-id="e19cd-113">Kako izgledaju tipovi osetljivih informacija</span><span class="sxs-lookup"><span data-stu-id="e19cd-113">What the sensitive information types look for</span></span>](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)
- [<span data-ttu-id="e19cd-114">Kreiranje prilagođenog osetljivog tipa informacija</span><span class="sxs-lookup"><span data-stu-id="e19cd-114">Create a custom sensitive information type</span></span>](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type)
- [<span data-ttu-id="e19cd-115">Slanje obaveštenja e-poštom i prikazivanje saveta o smernicama</span><span class="sxs-lookup"><span data-stu-id="e19cd-115">Send email notifications and show policy tips</span></span>](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips)
- [<span data-ttu-id="e19cd-116">Zaštita SharePoint datoteka na mreži sa oznakama za zadržavanje i DLP</span><span class="sxs-lookup"><span data-stu-id="e19cd-116">Protect SharePoint Online files with retention labels and DLP</span></span>](https://docs.microsoft.com/office365/securitycompliance/protect-sharepoint-online-files-with-office-365-labels-and-dlp)
- [<span data-ttu-id="e19cd-117">DLP i Microsoft timovi</span><span class="sxs-lookup"><span data-stu-id="e19cd-117">DLP and Microsoft Teams</span></span>](https://docs.microsoft.com/office365/securitycompliance/dlp-microsoft-teams)

<span data-ttu-id="e19cd-118">Da biste testirali podatke pomoću ugrađenog ili prilagođenog tipa sa osetljivim informacijama, koristite opciju " **tip testa** " u okviru liste sa**osetljivim informacijama o** **klasifikaciji** > .</span><span class="sxs-lookup"><span data-stu-id="e19cd-118">To test your data with a built-in or custom sensitive information type, use the **Test type** option under **Classifications** > **Sensitive info types**.</span></span> <span data-ttu-id="e19cd-119">Za više informacija pogledajte odeljak [testiranje prilagođenih osetljivih tipova informacija](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).</span><span class="sxs-lookup"><span data-stu-id="e19cd-119">For more information, see [Test custom sensitive information types](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).</span></span>