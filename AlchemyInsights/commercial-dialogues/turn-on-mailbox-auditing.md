---
title: Uključivanje nadgledanja poštanskog sandučeta
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 02/26/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3100005"
- "7327"
ms.openlocfilehash: aa0ff925ae891d28e31394ec66eb17c2d9710008
ms.sourcegitcommit: 251e2e82571fb3bb1fbe3dbf7bfca30e004b3373
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/05/2021
ms.locfileid: "50483542"
---
# <a name="turn-on-mailbox-auditing"></a><span data-ttu-id="339ec-102">Uključivanje nadgledanja poštanskog sandučeta</span><span class="sxs-lookup"><span data-stu-id="339ec-102">Turn on mailbox auditing</span></span>

<span data-ttu-id="339ec-103">Da biste uključili nadzor poštanskog sandučeta za jednog korisnika ili celu organizaciju, uradite sledeće cmdlet lokacije iz udaljenog PowerShell:</span><span class="sxs-lookup"><span data-stu-id="339ec-103">To turn on mailbox auditing for a single user or an entire organization, run the following cmdlets from Remote PowerShell:</span></span>

- <span data-ttu-id="339ec-104">**Pojedinačni korisnik**: Set-Mailbox-identitet "Džejn Dow" – $TRUE</span><span class="sxs-lookup"><span data-stu-id="339ec-104">**Single user**: Set-Mailbox -Identity "Jane Dow" -AuditEnabled $true</span></span>
- <span data-ttu-id="339ec-105">**Organizacija**: Get-Mailbox-Rezultsize neograničen-filter {RecipientTypeDetails-EQ "Korisnikopoštansko sanduče"} | Set-Mailbox-Revizoit $true</span><span class="sxs-lookup"><span data-stu-id="339ec-105">**Organization**: Get-Mailbox -ResultSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true</span></span>

<span data-ttu-id="339ec-106">Da biste saznali više, pogledajte članak [Upravljanje nadgledanjem poštanskog sandučeta](https://go.microsoft.com/fwlink/?linkid=2103668).</span><span class="sxs-lookup"><span data-stu-id="339ec-106">To learn more, see [Manage mailbox auditing](https://go.microsoft.com/fwlink/?linkid=2103668).</span></span>