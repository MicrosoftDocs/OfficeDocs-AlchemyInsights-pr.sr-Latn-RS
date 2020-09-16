---
title: Rešavanje problema sa programom DKIM
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1389
ms.assetid: ''
ms.openlocfilehash: 35e8023d26fe26211e27521ceb8751d2d7fc7a21
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/14/2020
ms.locfileid: "47744964"
---
# <a name="fix-dkim-setup-issues"></a>Rešavanje problema sa programom DKIM

Ako imate problema sa programom DKIM za prilagođeni domen, koristite sledeće korake:

- Većina DKIM instalacija je povezana sa neodgovarajućim DNS zapisima. Verifikujte ispravno oblikovan zapis DKIM CNAME (a**ne** txt zapis). Više informacija potražite u članku ova [Tema](https://docs.microsoft.com/microsoft-365/security/office-365-security/use-dkim-to-validate-outbound-email#steps-you-need-to-do-to-manually-set-up-dkim).

- Kada kreirate ili ažurirate DKIM DNS zapise u usluzi DNS hostinga za domen (obično je to registar domena), sačekajte da se DNS zapisi prošire.

- Ako ne možete da kreirate DKIM DNS zapise u centru administracije, možete da ga zamenite \<CustomDomain\> prilagođenim domenom (na primer, contoso.com) i da pokrećete ovu komandu u [Exchange online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell): `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true` .
