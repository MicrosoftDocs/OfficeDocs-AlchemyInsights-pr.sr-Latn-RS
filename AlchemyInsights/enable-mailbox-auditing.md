---
title: Omogućite nadgledanje poštansko sanduče
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/5/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: 3a7ffccadf6b415f7dd0d0871d368402332a0cd7
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/12/2019
ms.locfileid: "29916754"
---
# <a name="enable-mailbox-auditing"></a><span data-ttu-id="08c71-102">Omogućite nadgledanje poštansko sanduče</span><span class="sxs-lookup"><span data-stu-id="08c71-102">Enable mailbox auditing</span></span>

<span data-ttu-id="08c71-103">Da biste omogućili nadzor poštanskog sandučeta za jednog korisnika ili za celu organizaciju sledeće cmdlets mora pokretati sa Remote Shell napajanja:</span><span class="sxs-lookup"><span data-stu-id="08c71-103">To enable Mailbox Auditing for either a single user or an entire organization the following cmdlets must be run from Remote Power Shell:</span></span>
  
 <span data-ttu-id="08c71-104">**Jedan korisnik**</span><span class="sxs-lookup"><span data-stu-id="08c71-104">**Single User**</span></span>
  
<span data-ttu-id="08c71-105">Setu-poštansko sanduče - identitet „Jane Dow” - AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="08c71-105">Set-Mailbox -Identity "Jane Dow" -AuditEnabled $true</span></span>
  
 <span data-ttu-id="08c71-106">**Organizacija**</span><span class="sxs-lookup"><span data-stu-id="08c71-106">**Organization**</span></span>
  
<span data-ttu-id="08c71-107">Uzmi-poštansko sanduče - ResultSize neograničen - filtriranje {„UserMailbox” RecipientTypeDetails - eq} | Setu-poštansko sanduče - AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="08c71-107">Get-Mailbox -ResultSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true</span></span>
  
[<span data-ttu-id="08c71-108">Saznajte više</span><span class="sxs-lookup"><span data-stu-id="08c71-108">Learn more</span></span>](https://support.office.com/article/aaca8987-5b62-458b-9882-c28476a66918)
  

