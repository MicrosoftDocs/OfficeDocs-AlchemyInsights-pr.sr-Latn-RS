---
title: Dynamics 365 - naopako kontrolne table prikazuje u jedinstvenoj interfejs Dynamics 365
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1484"
- "6200024"
ms.openlocfilehash: 6edf6fbae0174f3fa4d635c7a99e7daae1243b60
ms.sourcegitcommit: a413a0e27ef4ab8c484fa9fccff8bbef381c8b96
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 07/16/2019
ms.locfileid: "35748619"
---
# <a name="wrong-dashboard-shows-in-dynamics-365-unified-interface"></a>U redu kontrolne table prikazuje u jedinstvenoj interfejs Dynamics 365

Postoji nekoliko razloga zašto možda ćete videti različite instrument-tabli od one koju očekujete:

## <a name="the-user-has-set-a-user-default-dashboard"></a>Korisnik je odredio korisnik podrazumevanu kontrolnu tablu 

Obično možete da identifikujete korisnika podrazumevanu kontrolnu tablu postavljeno ako **Postavi kao podrazumevano** dugme ne prikazuje u kontrolnoj tabli komandna traka. Podrazumevane kontrolne table korisnika će poništiti sve druge podrazumevane kontrolne table, čak i ako korisnikove podrazumevane kontrolne table nije u trenutnoj molbi.

Koristite sledeće rešenje za uklanjanje svoju podrazumevanu kontrolnu tablu.

1. Kreirajte novu ličnu kontrolnu tablu.

2. Da postavite novi instrument tabli kao zadanog korisnika.

3. Izbriši instrument tabli.

## <a name="the-dashboard-is-set-in-the-sitemap"></a>Kontrolna tabla je postavljena u Mapa sajta

Možda ste postavili organizaciju podrazumevanu kontrolnu tablu od strane izabrati instrument-tabli i „Postavi kao podrazumevano” pod „Prilagođavanje sistema”. Ali, Kontrolna tabla definisan u dizajneru sitemap će prednost nad ovu kontrolnu tablu, ako korisnik ima pristup njemu.

Da bi korisnici vide kontrolne table ste postavili kao podrazumevani organizaciji, možete:

* Postavite instrument tabli u Mapa sajta

* Uklanjanje pristupa na kontrolnu tablu sitemap definisan za one korisnike