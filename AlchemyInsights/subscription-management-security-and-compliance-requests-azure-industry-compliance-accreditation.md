---
title: Upravljanje pretplatom – zahtevi za bezbednost i usaglašenost – usaglašenost usluge Azure
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 12/07/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004112"
- "7191"
ms.openlocfilehash: 84c9d89161111a5a1cf9aea92f49c754ad6b7f73
ms.sourcegitcommit: c68aeb650c74cc790c6027a91965dcaf577f7428
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/08/2020
ms.locfileid: "49598782"
---
# <a name="subscription-management---security-and-compliance-requests---azure-industry-compliance-accreditation"></a><span data-ttu-id="46150-102">Upravljanje pretplatom – zahtevi za bezbednost i usaglašenost – usaglašenost usluge Azure</span><span class="sxs-lookup"><span data-stu-id="46150-102">Subscription management - security and compliance requests - azure industry compliance accreditation</span></span>

- <span data-ttu-id="46150-103">**Smernice**: za bilo koje pitanje o Microsoft članku usaglašenosti, pogledajte odeljak [Azure Trust Center pouzdanost](https://docs.microsoft.com/compliance/regulatory/offering-SOC).</span><span class="sxs-lookup"><span data-stu-id="46150-103">**Policy**: For any questions on Microsoft Compliance document, see [Azure Trust Center Compliance](https://docs.microsoft.com/compliance/regulatory/offering-SOC).</span></span>

- <span data-ttu-id="46150-104">**Hika i ACT HITECH**: pogledajte Windows AZURE Hika vodič ako ste zainteresovani za Hipa i ACT HITECH, da biste razumeli relevantne mogućnosti sistema Windows Azure.</span><span class="sxs-lookup"><span data-stu-id="46150-104">**HIPAA and the HITECH Act**: See Windows Azure HIPAA Guide if you are interested in HIPAA and the HITECH Act, to understand the relevant capabilities of Windows Azure.</span></span>

- <span data-ttu-id="46150-105">**Sertifikacija FedRAMP**: za sve informacije o usluzi FedRAMP, pogledajte odeljak Marketplace.</span><span class="sxs-lookup"><span data-stu-id="46150-105">**FedRamp Certification**: For any information on FedRamp certification, see FedRamp Marketplace.</span></span>

- <span data-ttu-id="46150-106">**Usaglašenost** sa AZURE PCI DSS-om: neophodni dokumenti vezani za Azure za ostvarivanje industrijske kartice su "Attestation usaglašenosti" i "Matrica odgovornosti" koje su dostupne u Azure Trust Trust.</span><span class="sxs-lookup"><span data-stu-id="46150-106">**Azure PCI DSS Compliance**: The required Azure-related documents for achieving Payment Card Industry compliances are the "Attestation of Compliance" and "Responsibility Matrix", both of which are available on the Azure Trust Center.</span></span> <span data-ttu-id="46150-107">Proverite da li imate ove dokumente.</span><span class="sxs-lookup"><span data-stu-id="46150-107">Please verify if you have these documents.</span></span> <span data-ttu-id="46150-108">Ako imate ove dokumente, ali vam je potreban dodatni dokaz usaglašenosti sa uslugom Microsoft Azure PCI podataka, pogledajte [Microsoft i PCI DSS](https://docs.microsoft.com/compliance/regulatory/offering-PCI-DSS).</span><span class="sxs-lookup"><span data-stu-id="46150-108">If you have these documents but need additional proof of Microsoft Azure PCI Data Security Standard Compliance, see [Microsoft and PCI DSS](https://docs.microsoft.com/compliance/regulatory/offering-PCI-DSS).</span></span>

- <span data-ttu-id="46150-109">**Azure operacije/bezbednost/usaglašenost**: Ako imate opšta pitanja vezana za bezbednost na lokaciji Azure, pogledajte standardni odgovor da biste zatražili informacije o usluzi Microsoft Azure Security, privatnosti i usaglašenosti ako imate pitanja u vezi sa Usaglašenošću, pogledajte članak: Microsoft stp-usaglašenost i Trust Trust</span><span class="sxs-lookup"><span data-stu-id="46150-109">**Azure Operations/Security/Compliance**: If you have general security-related questions on Azure, see Standard Response to Request for Information Microsoft Azure Security, Privacy, and Compliance If you have compliance related questions, please refer: Microsoft STP - Compliance and Service Trust Portal FAQ.</span></span>

<span data-ttu-id="46150-110">Ako imate pitanja vezana za usaglašenost, pogledajte članak [Microsoft STP-usaglašenost](https://www.microsoft.com/trust-center/compliance/compliance-overview) i Trust Trust</span><span class="sxs-lookup"><span data-stu-id="46150-110">If you have compliance-related questions, see [Microsoft STP - Compliance](https://www.microsoft.com/trust-center/compliance/compliance-overview) and Service Trust Portal FAQ.</span></span>

- <span data-ttu-id="46150-111">**Gdpr usaglašenost**: Ako imate pitanja o sporazumu o obradi podataka, pogledajte članak "Uslovi zaštite podataka" počevši od stranice 7 u "termini za usluge na mreži".</span><span class="sxs-lookup"><span data-stu-id="46150-111">**GDPR Compliance**: If you have questions about Data Processing Agreement, see "Data Protection Terms" starting on Page 7 in the "Online Services Terms".</span></span> <span data-ttu-id="46150-112">OST uključuje primarne uslove obrade podataka, ali je ugrađena u standardni komercijalni ugovor.</span><span class="sxs-lookup"><span data-stu-id="46150-112">The OST includes the primary data-processing terms but is incorporated into the standard commercial contract.</span></span> <span data-ttu-id="46150-113">Pored ostalog, pruža se ugovorna posvećenost koja se odnosi na naše goo obaveze.</span><span class="sxs-lookup"><span data-stu-id="46150-113">Among other things, it provides with a contractual commitment regarding our GDPR obligations.</span></span> <span data-ttu-id="46150-114">Pored toga, pogledajte članak određeni uslovi za goo na kraju ugovora u "prilog 4", počevši od stranice 42.</span><span class="sxs-lookup"><span data-stu-id="46150-114">Additionally, see the GDPR-specific terms at the end of the contract in "Attachment 4", starting on Page 42.</span></span> <span data-ttu-id="46150-115">Ovi odeljci pokrivaju lokacije Microsoft GDPR kao procesor podataka i kao subprocesor drugom procesoru podataka.</span><span class="sxs-lookup"><span data-stu-id="46150-115">These sections cover Microsoft’s GDPR obligations as a data processor and as a sub-processor to another data processor.</span></span>

> [!NOTE]
> <span data-ttu-id="46150-116">Preporučuje se da koristite Adobe Acrobat Reader za otvaranje PDF dokumenata, dok su problemi sa drugim PDF gledaocima zabeleženi. Preporučuje se i da lokalno preuzme datoteku umesto da je otvori u prozoru pregledača, pošto to može da izazove greške.</span><span class="sxs-lookup"><span data-stu-id="46150-116">It is strongly recommended to use Adobe Acrobat Reader to open PDF documents, as issues with other PDF viewers have been noted.It is also recommended to download the file locally instead of opening it in a browser window, as that may cause errors.</span></span>

- <span data-ttu-id="46150-117">**HDS usaglašenost**: Azure je sada "hosting podataka", certifikovan u skladu sa francuskim zahtevima.</span><span class="sxs-lookup"><span data-stu-id="46150-117">**HDS Compliance**: Azure is now "Health Data Hosting", certified in accordance with French requirements.</span></span> <span data-ttu-id="46150-118">Više informacija potražite u članku "Microsoft Azure je trenutno certifikovan za osetljive zdravstvene podatke u Francuskoj".</span><span class="sxs-lookup"><span data-stu-id="46150-118">For more information, see "Microsoft Azure is now certified to host sensitive health data in France".</span></span>

- <span data-ttu-id="46150-119">**Testiranje prodiranja**: ceo proces "prosleđivanje zahteva za testiranje" je klijent koji se samostalno služi u "pentestu".</span><span class="sxs-lookup"><span data-stu-id="46150-119">**Penetration Testing**: The entire "Penetration Test request submission" process is customer a self-serving process at "pentest".</span></span>

<span data-ttu-id="46150-120">Za više detalja o testu penetracije pogledajte članak [prodor na testiranje](https://docs.microsoft.com/azure/security/fundamentals/pen-testing).</span><span class="sxs-lookup"><span data-stu-id="46150-120">For more details about penetration testing, see [Penetration Testing](https://docs.microsoft.com/azure/security/fundamentals/pen-testing).</span></span>

- <span data-ttu-id="46150-121">**Obaveštenja klijenata za promene potprocesora**: možete da odlučite da se prijavite da biste dobili obaveštenja o promenama na listi Microsoft ličnih podataka.</span><span class="sxs-lookup"><span data-stu-id="46150-121">**Customer Notifications for Subprocessor Changes**: You may opt-in to receive notifications of changes to the Microsoft Personal Data Subprocessors List.</span></span>

> [!NOTE]
> <span data-ttu-id="46150-122">Informacije o klijentu klijenta i klijentske liste podataka su potpuno automatizovane.</span><span class="sxs-lookup"><span data-stu-id="46150-122">Online Services Customer Data and Personal Data List notification is fully automated.</span></span> <span data-ttu-id="46150-123">Više informacija potražite u članku resursi za zaštitu podataka Microsofta.</span><span class="sxs-lookup"><span data-stu-id="46150-123">For more information, see Microsofts Data Protection Resources.</span></span>

<span data-ttu-id="46150-124">**Preporučeni dokumenti**</span><span class="sxs-lookup"><span data-stu-id="46150-124">**Recommended Documents**</span></span>

- [<span data-ttu-id="46150-125">Izvoz ili brisanje postavki na Azure portalu</span><span class="sxs-lookup"><span data-stu-id="46150-125">Export or delete settings in the Azure portal</span></span>](https://docs.microsoft.com/azure/azure-portal/set-preferences)
- [<span data-ttu-id="46150-126">Pronalaženje izveštaja o aktivnostima na Azure portalu</span><span class="sxs-lookup"><span data-stu-id="46150-126">Find activity reports in the Azure portal</span></span>](https://docs.microsoft.com/azure/active-directory/reports-monitoring/howto-find-activity-reports)
- [<span data-ttu-id="46150-127">Događaji rizika za Azure Active Directory</span><span class="sxs-lookup"><span data-stu-id="46150-127">Azure Active Directory risk events</span></span>](https://docs.microsoft.com/azure/active-directory/identity-protection/overview-identity-protection)
- [<span data-ttu-id="46150-128">Korisnici rizikuju</span><span class="sxs-lookup"><span data-stu-id="46150-128">Users at risk</span></span>](https://docs.microsoft.com/azure/active-directory/identity-protection/overview-identity-protection)
- [<span data-ttu-id="46150-129">Riskantno prijavljivanje</span><span class="sxs-lookup"><span data-stu-id="46150-129">Risky sign-ins</span></span>](https://docs.microsoft.com/azure/active-directory/identity-protection/overview-identity-protection)
- [<span data-ttu-id="46150-130">Šta su to izveštaji Azure Active Directory?</span><span class="sxs-lookup"><span data-stu-id="46150-130">What are Azure Active Directory reports?</span></span>](https://docs.microsoft.com/azure/active-directory/reports-monitoring/overview-reports)
- [<span data-ttu-id="46150-131">Microsoft i HIKA i ACT HITECH-a</span><span class="sxs-lookup"><span data-stu-id="46150-131">Microsoft and HIPAA and the HITECH Act</span></span>](https://docs.microsoft.com/compliance/regulatory/offering-hipaa-hitech)
- [<span data-ttu-id="46150-132">Privremena dokumentacija autorizacije AMERIČKOG sekretarijata odbrane na IL4</span><span class="sxs-lookup"><span data-stu-id="46150-132">US Department of Defense (DoD) Provisional Authorization documentation on IL4</span></span>](https://docs.microsoft.com/compliance/regulatory/offering-DoD-DISA-L2-L4-L5)












