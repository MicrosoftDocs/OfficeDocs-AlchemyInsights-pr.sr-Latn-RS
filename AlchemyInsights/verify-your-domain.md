---
title: Proverite svoj domen
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "47"
- "48"
- "8"
ms.assetid: 81fd176b-3d67-4e52-9ab8-d36602412734
ms.openlocfilehash: 2c4d8e075d2cf7214b5ef005b856daf7fb0ed53c
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43710457"
---
# <a name="verify-your-domain"></a><span data-ttu-id="c04cc-102">Proverite svoj domen</span><span class="sxs-lookup"><span data-stu-id="c04cc-102">Verify your domain</span></span>

 <span data-ttu-id="c04cc-103">**Zapis verovatno nije ažuriran preko interneta.**</span><span class="sxs-lookup"><span data-stu-id="c04cc-103">**The record probably hasn't updated across the Internet.**</span></span>
  
<span data-ttu-id="c04cc-104">Obično nam je potrebno samo nekoliko minuta da bismo mogli da vidimo novi zapis, ali ponekad može da traje već nekoliko sati.</span><span class="sxs-lookup"><span data-stu-id="c04cc-104">It typically only takes a few minutes for us to be able to see the new record, but occasionally it can take as long as a few hours.</span></span> 
  
- <span data-ttu-id="c04cc-105">Ako ste već dugo čekali, dvaput proverite da li ste kopirali i nalepili tačnu vrednost u zapis za verifikaciju u TXT na DNS domaćinu.</span><span class="sxs-lookup"><span data-stu-id="c04cc-105">If you've waited that long already, double-check that you've copied and pasted the exact value into the TXT verification record at your DNS host.</span></span> <span data-ttu-id="c04cc-106">Jedno od uobičajenih problema ne uključuje deo zapisa "MS =".</span><span class="sxs-lookup"><span data-stu-id="c04cc-106">One common issue is not including the "MS=" part of the record.</span></span> <span data-ttu-id="c04cc-107">Potrebna nam je i to!</span><span class="sxs-lookup"><span data-stu-id="c04cc-107">We need that too!</span></span>

- <span data-ttu-id="c04cc-108">Kod nekih DNS domaćina morate da preduzmete dodatni korak da biste sačuvali datoteku zone (gde se nalazi DNS zapis) tako da će se ažurirati preko interneta.</span><span class="sxs-lookup"><span data-stu-id="c04cc-108">At some DNS hosts, you have to take an extra step to save the zone file (where the DNS record is stored) so that it will update across the Internet.</span></span> <span data-ttu-id="c04cc-109">Uverite se da ste sačuvali promene tako da Microsoft može da vidi i potvrdi zapis.</span><span class="sxs-lookup"><span data-stu-id="c04cc-109">Make sure you've saved your changes so Microsoft can see and verify the record.</span></span>
