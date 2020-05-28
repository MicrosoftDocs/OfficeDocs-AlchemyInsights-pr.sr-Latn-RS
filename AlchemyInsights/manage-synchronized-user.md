---
title: Upravljaj sinhronizovanim korisničkim
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000609"
- "2444"
ms.openlocfilehash: 84e337a7224fdd3c3ab7ad0f61240692fe007d5a
ms.sourcegitcommit: 82af227ac6d075e748e27c4ce6bdcf56628559cb
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/28/2020
ms.locfileid: "44407364"
---
# <a name="unable-to-set-primary-email-address-change-user-attributes-or-removedelete-a-synchronized-user"></a>Nije moguće podesiti primarnu e-adresu, promeniti korisničke atribute ili ukloniti/izbrisati sinhronizovani korisnik

Ako je sinhronizacija direktorijuma omogućena za vaš ambijent, neki korisnici ili atributi objekta ne mogu biti promenjeni pomoću Microsoft 365 admin Center.

Da biste u potpunosti upravljali sinhronizovanim korisnicima i svim njihovim atributima, koristite lokalnu grupu "korisnici aktivnog direktorijuma" i "Upravljanje grupama" (adsiedit. msc).  

Osim toga, možete da promenite pojedinačne korisnike ili atribute za sinhronizovane korisnike koristeći PowerShell kao što je prikazano u sledećim primerima: 
- `Set-MsolUser -UserPrincipalName user@yourdomain.onmicrosoft.com -AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com`

- `Set-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com" -DisplayName "Test User" -LastName "User" -Title "Manager" -Department "HR"`

- `Remove-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com`
