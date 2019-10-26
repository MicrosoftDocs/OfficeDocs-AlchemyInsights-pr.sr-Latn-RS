---
title: Pristup odbijen prilikom mapiranja disk jedinice na SharePoint
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 12/17/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: b7da3918-969f-40bb-acb3-fbc762605504
ms.openlocfilehash: c41bfd9d25c8aa946a4ec5156be6d2424f4e2133
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/25/2019
ms.locfileid: "36737491"
---
# <a name="fix-problems-with-sharepoint-libraries-mapped-to-network-drives"></a><span data-ttu-id="1b3e2-102">Rešavanje problema sa SharePoint bibliotekama mapiranim na mrežnim driveovima</span><span class="sxs-lookup"><span data-stu-id="1b3e2-102">Fix problems with SharePoint libraries mapped to network drives</span></span>

<span data-ttu-id="1b3e2-103">Kada pretražujete mapiranu mrežnu disk jedinicu, možda ćete videti neku od sledećih poruka:</span><span class="sxs-lookup"><span data-stu-id="1b3e2-103">When you browse to a mapped network drive, you may see one of the following messages:</span></span>
  
- <span data-ttu-id="1b3e2-104">**\\Putanja nije dostupna. Možda nemate dozvolu da koristite ovaj mrežni resurs. Obratite se administratoru ovog servera da biste saznali da li imate dozvole za pristup.**</span><span class="sxs-lookup"><span data-stu-id="1b3e2-104">**\\Path is not accessible. You might not have permission to use this network resource. Contact the administrator of this server to find out if you have access permissions.**</span></span>

- <span data-ttu-id="1b3e2-105">**Pristup je odbijen. Pre nego što otvorite datoteke na ovoj lokaciji, morate prvo da dodate Web lokaciju na listu pouzdanih lokacija, potražite Web lokaciju i izaberete opciju za automatsko prijavljivanje.**</span><span class="sxs-lookup"><span data-stu-id="1b3e2-105">**Access Denied. Before opening files in this location, you must first add the web site to your trusted site list, browse to the web site, and select the option to login automatically.**</span></span>

<span data-ttu-id="1b3e2-106">[Pronađite pomoć za rešavanje problema sa mapiranim mrežnim driveovima](https://docs.microsoft.com/sharepoint/support/administration/troubleshoot-mapped-network-drives).</span><span class="sxs-lookup"><span data-stu-id="1b3e2-106">[Get help troubleshooting mapped network drives](https://docs.microsoft.com/sharepoint/support/administration/troubleshoot-mapped-network-drives).</span></span>
  
<span data-ttu-id="1b3e2-107">Mapiranje biblioteke kao mrežne disk jedinice je privremeno i podržano samo u programu Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="1b3e2-107">Mapping a library as a network drive is temporary and supported only in Internet Explorer.</span></span> <span data-ttu-id="1b3e2-108">Umesto toga, [sinhronizujte SharePoint datoteke pomoću novog OneDrive klijenta za sinhronizaciju](https://support.office.com/article/6de9ede8-5b6e-4503-80b2-6190f3354a88.aspx) koji uključuje [datoteke na zahtev](https://support.office.com/article/0e6860d3-d9f3-4971-b321-7092438fb38e.aspx).</span><span class="sxs-lookup"><span data-stu-id="1b3e2-108">Instead, [sync SharePoint files with the new OneDrive sync client](https://support.office.com/article/6de9ede8-5b6e-4503-80b2-6190f3354a88.aspx) which includes [Files On-Demand](https://support.office.com/article/0e6860d3-d9f3-4971-b321-7092438fb38e.aspx).</span></span> <span data-ttu-id="1b3e2-109">Pristupite svim datotekama u usluzi OneDrive bez korišćenja lokalnog prostora za skladištenje.</span><span class="sxs-lookup"><span data-stu-id="1b3e2-109">Access all your files in OneDrive without using local storage space.</span></span>
  