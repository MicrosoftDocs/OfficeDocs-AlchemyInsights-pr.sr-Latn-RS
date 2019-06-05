---
title: Rešavanje problema sa zabranom pristupa porukama
ms.author: kirks
author: Techwriter40
ms.date: 6/29/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: ee154a60d80472639371d44faef464eea8734dc9
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/04/2019
ms.locfileid: "34716660"
---
# <a name="troubleshoot-access-denied-messages-in-sharepointonedrive-admin-center"></a>Rešavanje problema sa zabranom pristupa porukama u Sharepoint/OneDrive Admin Center

<p><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;">Ako dobijate pristup nije dozvoljen poruka pri pokušaju da pregledaju Sharepoint/OneDrive Admin centru, uverite se da <a href="https://docs.microsoft.com/en-us/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One">dodelite dozvole za korisnika </a>. Ako korisnik ima dozvolu, obavezno takođe se uverite da su <a href="https://docs.microsoft.com/en-us/office365/admin/add-users/about-admin-roles?view=o365-worldwide">dodeljene su ulogu administratora</a> koji možete da pristupite sa admin centrima.</span></p>  <p style="orphans: 2; -webkit-text-stroke-width: 0px; word-spacing: 0px;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;">Ovog problema takođe može doći kada korisnik je izbrisan i ponovo kreiran sa istom glavno ime korisnika (UPN). Novi nalog kreiran pomoću različitih PUID (jedinstveni Passport ID) vrednost. Kada korisnik pokuša da pristupi kolekciju lokacija ili njihove OneDrive, je jedan pogrešan PUID korisnika. Drugi scenario uključuje sinhronizacija direktorijuma sa organizacionih jedinica za Active Directory (OU). Ako su korisnici već prijavljeni na SharePoint, i onda su se preselili u različitim OU i najhrabriji sa SharePoint, oni su iskusiti ovaj problem.</span></span></p>  <ul style="orphans: 2; -webkit-text-stroke-width: 0px; word-spacing: 0px;" type="disc">  <li style="line-height: normal; ; font-size: 11pt; font-style: normal; font-weight: 400;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;">Da biste rešili ovaj problem, trebalo da vratite u prethodno stanje originalnu UPN sa koracima u članku, <a href="https://docs.microsoft.com/en-us/office365/admin/add-users/restore-user?view=o365-worldwide">Vraćanje korisnik u Office 365</a>.</span></span></li>  </ul>  <p style="orphans: 2; -webkit-text-stroke-width: 0px; word-spacing: 0px;"><strong><span style="font-size: 10.5pt; font-family: '&amp;quot',serif;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif; mso-bidi-font-family: Calibri;">Napomena:</span></span></strong><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif; mso-fareast-font-family: 'Times New Roman'; mso-bidi-font-family: 'Times New Roman';"><span style="font-size: 10.5pt; font-family: '&amp;quot',serif;"><em style="mso-bidi-font-style: normal;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;">&nbsp;</span></em><em><span style="font-family: '&amp;quot',serif;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif; mso-bidi-font-family: Calibri;font-style: normal; mso-bidi-font-style: italic;">Ako centar za OneDrive ili SharePoint Admin nije dostupna za više korisnika koji su prethodno imali pristup, moguće je da je servis privremeno problem.&nbsp; </span></span></em> <em><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif; mso-bidi-font-family: Calibri;"> <a href="https://portal.office.com/adminportal/home#/servicehealth" target="_blank" rel="noopener"><span style="font-style: normal; mso-bidi-font-style: italic;">Proveri kontrolne table zdravstvenih usluga</span></a>.</span></em></span></span></p>

