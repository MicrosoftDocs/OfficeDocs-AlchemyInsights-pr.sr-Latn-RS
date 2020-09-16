---
title: Dodavanje grupe na SharePoint sajt
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f7d730bf-0d6e-424c-970c-6137c71cb50b
ms.openlocfilehash: 9bec2f71465e43e1c3cba038e0e68949672ceb8a
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/15/2020
ms.locfileid: "47771222"
---
# <a name="issues-when-creating-a-group-connected-site-in-sharepoint"></a><span data-ttu-id="2dadc-102">Problemi prilikom kreiranja povezane lokacije grupe u sistemu SharePoint</span><span class="sxs-lookup"><span data-stu-id="2dadc-102">Issues when creating a group connected site in SharePoint</span></span>

1. <span data-ttu-id="2dadc-103">Neki uobičajeni problemi se susreжu prilikom kreiranja ili ponovnog kreiranja povezane lokacijske grupe.</span><span class="sxs-lookup"><span data-stu-id="2dadc-103">Some common issues encountered when creating or re-creating a group connected site.</span></span>
<span data-ttu-id="2dadc-104">Ako ste izbrisali grupu i njenu povezanu sajt i želite da kreirate drugu sajt sa istim URL adresom, moraćete trajno da uklonite prethodnu stranicu.</span><span class="sxs-lookup"><span data-stu-id="2dadc-104">If you have deleted a group and its connected site and wish to create another site with the same URL, you'll need to permanently remove the previous site.</span></span>

   - <span data-ttu-id="2dadc-105">Preuzmite [SPO Management Shell](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)</span><span class="sxs-lookup"><span data-stu-id="2dadc-105">Download [SPO Management Shell](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)</span></span>
   - <span data-ttu-id="2dadc-106">Više informacija o prvi koraci uz PowerShell potražite u članku [Prvi koraci uz SharePoint online Management Shell](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite).</span><span class="sxs-lookup"><span data-stu-id="2dadc-106">For more info on getting started with Powershell, see [Getting started with SharePoint Online Management Shell](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite).</span></span>
   - <span data-ttu-id="2dadc-107">Uklonite lokaciju sa izbrisanih lokacija pomoću modula za [Uklanjanje-Spodeletedsites](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) PowerShell cmdlet.</span><span class="sxs-lookup"><span data-stu-id="2dadc-107">Remove the Site from Deleted Sites using the [Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) Powershell cmdlet.</span></span> <span data-ttu-id="2dadc-108">PowerShell je potreban za trajno brisanje lokacija grupe.</span><span class="sxs-lookup"><span data-stu-id="2dadc-108">Powershell is required to permanently delete group sites.</span></span>

1. <span data-ttu-id="2dadc-109">Ako kreirate Veb lokaciju povezanu sa grupom i primite upozorenje: **već postoji druga grupa sa istim pseudonima**, pregledajte postojeće grupe iz [Microsoft 365 centra administracije](https://admin.microsoft.com/AdminPortal/Home#/groups).</span><span class="sxs-lookup"><span data-stu-id="2dadc-109">If you're creating a group connected site and receive a warning: **Another group with the same alias already exists**, check the existing groups from the [Microsoft 365 admin center](https://admin.microsoft.com/AdminPortal/Home#/groups).</span></span> <span data-ttu-id="2dadc-110">Da biste rešili problem, izbrišite postojeću grupu ako ona više nije potrebna ili kreirajte sajt sa drugim dodeljenim pseudonima.</span><span class="sxs-lookup"><span data-stu-id="2dadc-110">To resolve the issue, delete the existing group if it's no longer needed or create the site with a different alias assigned.</span></span>

1. <span data-ttu-id="2dadc-111">Postoje različiti načini za kreiranje i korišćenje modernih grupa sa sistemom SharePoint.</span><span class="sxs-lookup"><span data-stu-id="2dadc-111">There are different ways to create and use modern groups with SharePoint.</span></span>

   - <span data-ttu-id="2dadc-112">Postojeće lokacije možete povezati sa Microsoft 365 grupom.</span><span class="sxs-lookup"><span data-stu-id="2dadc-112">You can connect existing sites to a Microsoft 365 group.</span></span> <span data-ttu-id="2dadc-113">Više informacija potražite u članku [povezivanje Microsoft 365 grupe pomoću SharePoint korisničkog interfejsa](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).</span><span class="sxs-lookup"><span data-stu-id="2dadc-113">For more info, see [Connect a Microsoft 365 group using the SharePoint user interface](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).</span></span>
   - <span data-ttu-id="2dadc-114">Da biste kreirali Microsoft 365 povezanu lokaciju, moraćete da kreirate [lokaciju tima](https://admin.microsoft.com/sharepoint).</span><span class="sxs-lookup"><span data-stu-id="2dadc-114">To create a Microsoft 365 group connected site, you'll need to create a [Team Site](https://admin.microsoft.com/sharepoint).</span></span>
