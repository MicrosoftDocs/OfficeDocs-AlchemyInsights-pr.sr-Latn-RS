---
title: Povezivanje sa MSCommerce modulom
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001212"
- "3529"
ms.openlocfilehash: 15dc7038426a8d436c236a91aa0f3462f6a3e366
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/14/2020
ms.locfileid: "47702629"
---
# <a name="mscommerce-requires-a-company-or-billing-administrator-account"></a><span data-ttu-id="07da9-102">MSCommerce zahteva preduzeće ili administratorski nalog za naplatu</span><span class="sxs-lookup"><span data-stu-id="07da9-102">MSCommerce requires a Company or Billing Administrator account</span></span>

<span data-ttu-id="07da9-103">MSCommerce modul zahteva nalog sa privilegijama administratorskih privilegija ili administratora naplate.</span><span class="sxs-lookup"><span data-stu-id="07da9-103">The MSCommerce module requires an account with Company or Billing Administrator privileges.</span></span> <span data-ttu-id="07da9-104">Ako dobijate sledeću grešku, moraćete ponovo da se povežete sa drugim nalogom.</span><span class="sxs-lookup"><span data-stu-id="07da9-104">If you are receiving the following error, you will need to reconnect with a different account.</span></span>

<span data-ttu-id="07da9-105">*Errorporuka – Udaljeni server je vratio grešku: (403). Podaci o greškama-na C:\Program Files\windowspower, Modules\mskomerce\1.2\mskomerce.psm1:216 Char: 5*</span><span class="sxs-lookup"><span data-stu-id="07da9-105">*ErrorMessage - The remote server returned an error: (403) Forbidden. ErrorDetails - At C:\Program Files\WindowsPowerShell\Modules\MSCommerce\1.2\MSCommerce.psm1:216 char:5*</span></span><br>
<span data-ttu-id="07da9-106">*+&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Ruleerror-ErrorContext $ _-Customerrorporuka "nije uspelo za retri...*</span><span class="sxs-lookup"><span data-stu-id="07da9-106">*+&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;HandleError -ErrorContext $_ -CustomErrorMessage "Failed to retri ...*</span></span><br>
<span data-ttu-id="07da9-107">\+&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~</span><span class="sxs-lookup"><span data-stu-id="07da9-107">\+&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~</span></span><br>
<span data-ttu-id="07da9-108">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*+ Kategoriinformacije: nije navedeno: (:) [Greška pisanja], Writeerrorizuzetak*</span><span class="sxs-lookup"><span data-stu-id="07da9-108">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*+ CategoryInfo          : NotSpecified: (:) [Write-Error], WriteErrorException*</span></span><br>
<span data-ttu-id="07da9-109">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*+ Fullikvalifikacija ID-ovi: Microsoft. PowerShell. komande. Erriteerrorerr, HandleError*</span><span class="sxs-lookup"><span data-stu-id="07da9-109">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*+ FullyQualifiedErrorId : Microsoft.PowerShell.Commands.WriteErrorException,HandleError*</span></span>

<span data-ttu-id="07da9-110">Ako vaš nalog nema privilegije administratora za naplatu, obratite se IT administratoru.</span><span class="sxs-lookup"><span data-stu-id="07da9-110">If your account does not have Company or Billing Administrator privileges, contact your IT Admin.</span></span>
