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
# <a name="unable-to-set-primary-email-address-change-user-attributes-or-removedelete-a-synchronized-user"></a><span data-ttu-id="3754d-102">Nije moguće uspostaviti primarnu e-adresu, promeniti atribute korisnika ili ukloniti/izbrisati sinhronizovanog korisnika</span><span class="sxs-lookup"><span data-stu-id="3754d-102">Unable to set primary email address, change user attributes, or remove/delete a synchronized user</span></span>

<span data-ttu-id="3754d-103">Ako je sinhronizacija direktorijuma omogućena za okruženje, neki atributi korisnika ili objekta ne mogu se menjati pomoću Microsoft 365 centra administracije.</span><span class="sxs-lookup"><span data-stu-id="3754d-103">If directory synchronization is enabled for your environment, some user or object attributes cannot be changed using the Microsoft 365 admin center.</span></span>

<span data-ttu-id="3754d-104">Da biste u potpunosti upravljali sinhronizovanim korisnicima i svim njihovim atributima, koristite lokalnu konzolu za upravljanje korisnicima i upravljaču Active Directory (adsiedit. msc).</span><span class="sxs-lookup"><span data-stu-id="3754d-104">To fully manage synchronized users and all their attributes, use your local active directory users and groups management console (adsiedit.msc).</span></span>  

<span data-ttu-id="3754d-105">Alternativno, možete da promenite pojedinačne korisnike ili atribute za sinhronizovane korisnike pomoću PowerShell kao što je prikazano u sledećim primerima:</span><span class="sxs-lookup"><span data-stu-id="3754d-105">Alternatively, you can change individual users or attributes for synchronized users using powershell such as shown in these common examples:</span></span>

`Set-MsolUser -UserPrincipalName user@yourdomain.onmicrosoft.com -AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com`

`Set-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com" -DisplayName "Test User" -LastName "User" -Title "Manager" -Department "HR"`

`Remove-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com`
