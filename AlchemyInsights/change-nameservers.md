---
title: Promena servera imena
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "5"
- "14"
ms.openlocfilehash: 51532f42e7cbd39ebad3f0160465218c6e1454a2
ms.sourcegitcommit: a256e8680379c006287ae30996763051c4d9ff85
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/04/2019
ms.locfileid: "36736663"
---
# <a name="update-your-domain-nameservers-to-office-365"></a><span data-ttu-id="d048b-102">Ažuriranje servera imena domena u usluzi Office 365</span><span class="sxs-lookup"><span data-stu-id="d048b-102">Update your domain nameservers to Office 365</span></span>

<span data-ttu-id="d048b-103">Napomena: Promena servera imena ponekad može da potraje do 48 časova.</span><span class="sxs-lookup"><span data-stu-id="d048b-103">Note: Nameserver changes can sometimes take up to 48 hours to propagate.</span></span>
  
<span data-ttu-id="d048b-104">Da biste podesili domen u usluzi Office 365, serveri imena u registru treba da se ažuriraju.</span><span class="sxs-lookup"><span data-stu-id="d048b-104">To set up your domain in Office 365, the nameservers at your registrar need to be updated.</span></span> <span data-ttu-id="d048b-105">Kreirajte ili uredite zapise servera imena u registru domena.</span><span class="sxs-lookup"><span data-stu-id="d048b-105">Create or edit your nameserver records at your domain registrar.</span></span>
  
1. <span data-ttu-id="d048b-106">Idite na veb sajt registra domena i pronađite oblast gde možete da uredite servere imena.</span><span class="sxs-lookup"><span data-stu-id="d048b-106">Go to your domain registrar's website and find the area where you can edit the nameservers.</span></span>
  
2. <span data-ttu-id="d048b-107">Kreirajte ili uredite dva zapisa servera imena tako da se podudaraju sa ovim vrednostima:</span><span class="sxs-lookup"><span data-stu-id="d048b-107">Create or edit two nameserver records to match these values:</span></span>

  - <span data-ttu-id="d048b-108">ns1.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="d048b-108">ns1.bdm.microsoftonline.com</span></span>

  - <span data-ttu-id="d048b-109">ns2.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="d048b-109">ns2.bdm.microsoftonline.com</span></span>

3. <span data-ttu-id="d048b-110">Sačuvajte promene.</span><span class="sxs-lookup"><span data-stu-id="d048b-110">Save changes.</span></span>

<span data-ttu-id="d048b-111">Takođe možete da pronađete detaljna uputstva u ovom članku: [Promena servera imena radi podešavanja usluge Office 365 pomoću bilo kog registra domena](https://docs.microsoft.com//office365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)</span><span class="sxs-lookup"><span data-stu-id="d048b-111">You can also find detailed instructions in this article: [Change nameservers to set up Office 365 with any domain registrar](https://docs.microsoft.com//office365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)</span></span>
  