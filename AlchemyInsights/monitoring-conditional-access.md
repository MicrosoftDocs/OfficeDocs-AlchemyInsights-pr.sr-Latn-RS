---
title: Monitoring uslovnog pristupa
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "9003769"
- "6702"
ms.openlocfilehash: c3bf5dd9066685af2df7ba50f0eb3ba6e891c2a9
ms.sourcegitcommit: 0eb4f9bde53395b5fd4b5cd4ffc56ca96db91298
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/10/2021
ms.locfileid: "50708688"
---
# <a name="monitoring-conditional-access-for-exchange"></a>Monitoring uslovnog pristupa za Exchange

Korisnici koji su usmereni na uslovno pristup dobiće obaveštenje ako ne ispune zahteve za pristup vaše organizacije. Da biste rešili, preporučujemo neka od sledećih rešenja:

- Ako se na uređaj pretpostavlja da je upisan, savetujte korisnika da ode na aplikaciju portala preduzeća i potvrdi da se pojavljuje na portalu preduzeća. Ako nije, korisnik treba da prijavi uređaj.
- U Azure portalu idite u Intune > usaglašenost uređaja. U okviru prati izaberite stavku usaglašenost uređaja. Prikažite izveštaj usaglašenosti uređaja da biste potvrdili da je uređaj korisnika označen kao usaglašeni.
- U Azure portalu idite u Intune > usaglašenost uređaja. U okviru upravljanje izaberite stavku smernice. Na listi smernica usaglašenosti proverite da li je profil dodeljen vašem uređaju. Ako nijedan profil nije dodeljen, Intune neće moći da potvrdi status usaglašenosti uređaja.
- Uredite zadatak korisnika uslovnog pristupa.

1. U Azure portalu idite na **Podešavanje**  >  **uslovnih**  >  **smernica** za pristup.
2. Izaberite smernice sa liste.
3. Izaberite stavku korisnici i grupe.
4. Da biste nekome ciljali određenu politiku, dodajte ih na listu "ukljuci". Da biste se uverili da je osoba izostavljena iz smernica, dodajte ih na listu "Isključi".

Korisne veze:

[Pregled usaglašenosti uređaja](https://docs.microsoft.com/intune/device-compliance-get-started)

[Rešavanje problema sa kom](https://docs.microsoft.com/intune/troubleshoot-conditional-access)

[Smernice za rešavanje problema](https://docs.microsoft.com/troubleshoot/mem/intune/troubleshoot-policies-in-microsoft-intune)

[Nadgledanje usaglašenosti uređaja](https://docs.microsoft.com/intune/compliance-policy-monitor)

Napomena: Ovi koraci su korisni samo u rešavanju problema sa funkcijom Azure Active Directory. Uređaj može da blokira i blokiranje pristupa e-poštom pomoću Exchange smernica. Više informacija o upravljanju Exchange uređajima može se pronaći [ovde] ( https://docs.microsoft.com/previous-versions/office/exchange-server-2010/ff959225(v=exchg.141) .
