---
title: Ispravka greške 0x8004de40 u usluzi OneDrive
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: b9bd6dff48f78063e3d47f5fe2f834f59eb9868a
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/14/2020
ms.locfileid: "47745144"
---
# <a name="fix-0x8004de40-error-in-onedrive"></a><span data-ttu-id="d3f8e-102">Ispravka greške 0x8004de40 u usluzi OneDrive</span><span class="sxs-lookup"><span data-stu-id="d3f8e-102">Fix 0x8004de40 error in OneDrive</span></span>

<span data-ttu-id="d3f8e-103">Ako primite grešku 0x8004de40 0 uz OneDrive:</span><span class="sxs-lookup"><span data-stu-id="d3f8e-103">If you receive an 0x8004de40 error with OneDrive:</span></span>

- <span data-ttu-id="d3f8e-104">Ponovo pokrenite računar koji utiče na njega dok ste povezani sa Acitve Domain Domain Directory.</span><span class="sxs-lookup"><span data-stu-id="d3f8e-104">Reboot the affected computer while connected to your Acitve Directory domain.</span></span>
- <span data-ttu-id="d3f8e-105">Ako ponovno pokretanje ne reši problem, odpridružite se i pridružite se uređaju iz usluge Azure AD.</span><span class="sxs-lookup"><span data-stu-id="d3f8e-105">If a reboot doesn't fix the issue, unjoin and rejoin your device from Azure AD.</span></span> 

<span data-ttu-id="d3f8e-106">**Napomena**: trebalo bi da budete na mreži preduzeća prilikom izvršavanja ovih koraka.</span><span class="sxs-lookup"><span data-stu-id="d3f8e-106">**Note**: You should be on your corporate network while performing these steps.</span></span> <span data-ttu-id="d3f8e-107">Nemojte vršiti ove korake kada ne možete da se povežete sa korporativnom infrastrukturom (na primer, dok putujete).</span><span class="sxs-lookup"><span data-stu-id="d3f8e-107">Don't perform these steps when you aren't able to connect to your corporate infrastructure (for example, while traveling).</span></span> 

- <span data-ttu-id="d3f8e-108">Otvorite otvorenu komandnu liniju.</span><span class="sxs-lookup"><span data-stu-id="d3f8e-108">Open an elevated command prompt.</span></span> 
- <span data-ttu-id="d3f8e-109">Da biste otvorili povećanu komandnu liniju, kliknite- **Start**, kliknite desnim tasterom miša na **komandnu liniju**, a zatim izaberite stavku **Pokreni kao administrator**.</span><span class="sxs-lookup"><span data-stu-id="d3f8e-109">To open an elevated command prompt, click - **Start**, right-click **Command Prompt**, and then click **Run as administrator**.</span></span>
- <span data-ttu-id="d3f8e-110">Otkucajte *dsregcmd/ostavi* i pritisnite taster **ENTER**.</span><span class="sxs-lookup"><span data-stu-id="d3f8e-110">Type *dsregcmd /leave* and press **Enter**.</span></span>
- <span data-ttu-id="d3f8e-111">Kada završite, otkucajte *dsregcmd/JOIN* i pritisnite taster **ENTER**.</span><span class="sxs-lookup"><span data-stu-id="d3f8e-111">When complete, type *dsregcmd /join* and press **Enter**.</span></span>
- <span data-ttu-id="d3f8e-112">Kada završite, zatvorite komandnu liniju.</span><span class="sxs-lookup"><span data-stu-id="d3f8e-112">When complete, close the command prompt.</span></span>
- <span data-ttu-id="d3f8e-113">Ponovo pokrenite računar i prijavite se u OneDrive.</span><span class="sxs-lookup"><span data-stu-id="d3f8e-113">Reboot the computer, and log into OneDrive.</span></span>