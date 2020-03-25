---
title: Ograničavanje SharePoint migracije sa 503 grešaka
ms.author: pebaum
author: pebaum
ms.date: 8/8/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: ''
ms.custom:
- "9000136"
- "2541"
ms.openlocfilehash: 7e12c74d33e3cee7c626ad899a4e7f2f0a409bca
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931672"
---
# <a name="sharepoint-migration-throttling-with-503-errors"></a><span data-ttu-id="e7de0-102">Ograničavanje SharePoint migracije sa 503 grešaka</span><span class="sxs-lookup"><span data-stu-id="e7de0-102">SharePoint migration throttling with 503 errors</span></span>

<span data-ttu-id="e7de0-103">**Važno**: mnogi korisnici usluge SharePoint Online i OneDrive pokreću poslovne aplikacije u odnosu na uslugu koja se pokreće u pozadini.</span><span class="sxs-lookup"><span data-stu-id="e7de0-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="e7de0-104">Ovo uključuje migraciju sadržaja, sprečavanje gubitka podataka (DLP) i rešenja za rezervno kopiranje.</span><span class="sxs-lookup"><span data-stu-id="e7de0-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="e7de0-105">U ovim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive budu veoma dostupne i pouzdane za korisnike koji zavise od usluge u udaljenim radnim scenarijima.</span><span class="sxs-lookup"><span data-stu-id="e7de0-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="e7de0-106">U cilju podrške ovom cilju, Implementirao sam strožije limite na aplikacije u pozadini (migracioni, DLP i Backup rešenja) tokom dana u danima u sedmici.</span><span class="sxs-lookup"><span data-stu-id="e7de0-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="e7de0-107">Trebalo bi da očekujete da će ove aplikacije ostvariti veoma ograničenu propusnost tokom ovih vremena.</span><span class="sxs-lookup"><span data-stu-id="e7de0-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="e7de0-108">Međutim, tokom večeri i vikenda u regionu, usluga će biti spremna da obradi znatno veći obim zahteva iz aplikacija u pozadini.</span><span class="sxs-lookup"><span data-stu-id="e7de0-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="e7de0-109">**503 grešaka pri preseljenja na SharePoint online**</span><span class="sxs-lookup"><span data-stu-id="e7de0-109">**503 errors when migrating to SharePoint Online**</span></span>

<span data-ttu-id="e7de0-110">Izgleda da se migrirate na SharePoint Online i dobijate 503 grešaka.</span><span class="sxs-lookup"><span data-stu-id="e7de0-110">It appears you are migrating to SharePoint Online and receiving 503 errors.</span></span> <span data-ttu-id="e7de0-111">Pratite dolenavedene korake da bismo vam mogli pomoći u najkraćem mogućem roku.</span><span class="sxs-lookup"><span data-stu-id="e7de0-111">Please follow the steps below so we may assist you as soon as possible.</span></span> 

1. <span data-ttu-id="e7de0-112">Izaberite stavku **Podrška za kontakt**, a zatim **novi zahtev za servis**.</span><span class="sxs-lookup"><span data-stu-id="e7de0-112">Click **Contact Support**, and then **New Service Request**.</span></span>
2. <span data-ttu-id="e7de0-113">Za naslov i opis, otkucajte " **ograničavanje SharePoint migracije" sa 503**.</span><span class="sxs-lookup"><span data-stu-id="e7de0-113">For the title and description, type **SharePoint Migration Throttling with 503**.</span></span>
3. <span data-ttu-id="e7de0-114">Kada se karta prosledi, ažurirajte je sledećim informacijama:</span><span class="sxs-lookup"><span data-stu-id="e7de0-114">Once the ticket has been submitted, please update it with the following information:</span></span>
    - <span data-ttu-id="e7de0-115">Koliko je preostalo za migraciju (na primer, koliko TBs?).</span><span class="sxs-lookup"><span data-stu-id="e7de0-115">How much left of migration (for example, how many TBs?).</span></span>
    - <span data-ttu-id="e7de0-116">Početni i krajnji datum migracije.</span><span class="sxs-lookup"><span data-stu-id="e7de0-116">Migration start and end date.</span></span>
    - <span data-ttu-id="e7de0-117">Opišite mesto na koje želite da migrirate sadržaj, kao što je SharePoint Server, box, Gdisk, deljeni resursi datoteka itd...</span><span class="sxs-lookup"><span data-stu-id="e7de0-117">Describe where you are migrating your content from, such as SharePoint Server, Box, GDrive, File shares, etc..</span></span>
    - <span data-ttu-id="e7de0-118">Procenite broj grešaka u regulisanja (na primer, x reguliranje po satu?) i kada se dogodi ograničavanje.</span><span class="sxs-lookup"><span data-stu-id="e7de0-118">Estimate the number of throttling errors (for example, x throttle per hour?) and when did the throttling happen.</span></span>
    - <span data-ttu-id="e7de0-119">Koju alatku za migraciju koristite (na primer, SPMT ili ShareGate).</span><span class="sxs-lookup"><span data-stu-id="e7de0-119">Which migration tool you are using (for example, SPMT or ShareGate).</span></span>


