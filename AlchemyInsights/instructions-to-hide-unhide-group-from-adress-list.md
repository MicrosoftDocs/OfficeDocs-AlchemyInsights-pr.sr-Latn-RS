---
title: Uputstva za skrivanje/otkrivanje grupe iz liste adresa
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1200024"
- "3161"
ms.openlocfilehash: d0e0285701f1a5f308bdc682abaddf5cc2d34120
ms.sourcegitcommit: defe2c412567b596fa8c3ab52111bde712ebb314
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/29/2019
ms.locfileid: "37768948"
---
# <a name="hide-office-365-group-from-address-list-gal"></a><span data-ttu-id="08f84-102">Sakrij Office 365 grupu sa spiska adresa (GAL)</span><span class="sxs-lookup"><span data-stu-id="08f84-102">Hide Office 365 group from address list (GAL)</span></span>

<span data-ttu-id="08f84-103">Da biste sakrili Office 365 grupu sa lista adresa (GAL) Exchange klijenata (kao što su Outlook ili OWOVA), koristite sledeću komandu u EXO Shell:</span><span class="sxs-lookup"><span data-stu-id="08f84-103">To hide an Office 365 group from address lists (GAL) of Exchange clients (such as Outlook or OWA), use the following command in EXO shell:</span></span>

`Set-UnifiedGroup -Identity GroupName -HiddenFromAddressListsEnabled:$true`

<span data-ttu-id="08f84-104">Da biste sakrili Office 365 grupu koja je vidljiva za Exchange klijente, koristite sledeću komandu u EXO Shell:</span><span class="sxs-lookup"><span data-stu-id="08f84-104">To hide the Office 365 group from being visible to Exchange clients, use the following command in EXO shell:</span></span>

`Set-unifiedGroup -Identity GroupName -HiddenFromExchangeClientsEnabled:$true
Check this article for detailed instructions`
