---
title: Pitanja o načinu korišćenja alatke za primenu sistema Office (ODT)
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 3e88e0f3-c86d-4ab8-b076-59d0552318f9
ms.openlocfilehash: 4aef42df4dde17d15863fca67e41f0ff23e506dc
ms.sourcegitcommit: 7e06d9ec1dd462cbd882f088c997d012a032f04d
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/04/2020
ms.locfileid: "44010772"
---
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a><span data-ttu-id="caa81-102">Pitanja o načinu korišćenja alatke za primenu sistema Office (ODT)</span><span class="sxs-lookup"><span data-stu-id="caa81-102">Questions about how to use the Office Deployment Tool (ODT)</span></span>

<span data-ttu-id="caa81-103">Preuzmite alatku za primenu sistema Office sa [lokacije Microsoft Download Center](https://go.microsoft.com/fwlink/p/?LinkID=626065).</span><span class="sxs-lookup"><span data-stu-id="caa81-103">Download the Office Deployment Tool from the [Microsoft Download Center](https://go.microsoft.com/fwlink/p/?LinkID=626065).</span></span>
  
<span data-ttu-id="caa81-104">Kada preuzmete datoteku, pokrenite izvršnu datoteku koja se samostalno izdvaja, a koja sadrži izvršnu alatku "Office alatka za primenu" (Setup. exe) i probnu datoteku za konfiguraciju (konfiguracija. XML).</span><span class="sxs-lookup"><span data-stu-id="caa81-104">After downloading the file, run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span>
  
 <span data-ttu-id="caa81-105">**Da biste izuzeli ili uklonili Microsoft 365 aplikacije za Enterprise proizvode sa klijentskih računara:**</span><span class="sxs-lookup"><span data-stu-id="caa81-105">**To exclude or remove Microsoft 365 Apps for enterprise products from client computers:**</span></span>
  
<span data-ttu-id="caa81-106">Kada instalirate Microsoft 365 aplikacije za Enterprise, možete da izuzmete određene proizvode.</span><span class="sxs-lookup"><span data-stu-id="caa81-106">When installing Microsoft 365 Apps for enterprise, you can exclude specific products.</span></span> <span data-ttu-id="caa81-107">Da biste to uradili, sledite korake za instaliranje sistema Office sa ODT, ali uključite i ExcludeApp element u datoteku za konfiguraciju.</span><span class="sxs-lookup"><span data-stu-id="caa81-107">To do so, follow the steps for installing Office with the ODT, but include the ExcludeApp element in your configuration file.</span></span> <span data-ttu-id="caa81-108">Na primer, ova datoteka za konfiguraciju instalira sve Microsoft 365 aplikacije za Enterprise proizvode osim izdavača:</span><span class="sxs-lookup"><span data-stu-id="caa81-108">For example, this configuration file installs all the Microsoft 365 Apps for enterprise products except Publisher:</span></span>
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[<span data-ttu-id="caa81-109">Pregled alatke za primenu sistema Office</span><span class="sxs-lookup"><span data-stu-id="caa81-109">Overview of the Office Deployment Tool</span></span>](https://docs.microsoft.com/deployoffice/overview-office-deployment-tool)
  

