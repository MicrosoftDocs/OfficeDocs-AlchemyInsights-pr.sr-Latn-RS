---
title: Upravljanje sinhronizovanim korisnicima
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
- "9000609"
- "2444"
ms.openlocfilehash: 7bf7d3f00308ff6bc973cd52e09ca51c5fd0f45b
ms.sourcegitcommit: 1fb324fd156008e77b7e2008af4b3dc1c0d0ea3e
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/13/2020
ms.locfileid: "48451414"
---
# <a name="unable-to-set-primary-email-address-change-user-attributes-or-removedelete-a-synchronized-user"></a>Nije moguće uspostaviti primarnu e-adresu, promeniti atribute korisnika ili ukloniti/izbrisati sinhronizovanog korisnika

Ako je sinhronizacija direktorijuma omogućena za okruženje, neki atributi korisnika ili objekta ne mogu se menjati pomoću Microsoft 365 centra administracije.

Da biste u potpunosti upravljali sinhronizovanim korisnicima i svim njihovim atributima, koristite lokalnu konzolu za upravljanje korisnicima i upravljaču Active Directory (adsiedit. msc).  

Alternativno, možete da promenite pojedinačne korisnike ili atribute za sinhronizovane korisnike pomoću PowerShell kao što je prikazano u sledećim primerima:

`Set-MsolUser -UserPrincipalName user@yourdomain.onmicrosoft.com -AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com`

`Set-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com" -DisplayName "Test User" -LastName "User" -Title "Manager" -Department "HR"`

`Remove-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com`
