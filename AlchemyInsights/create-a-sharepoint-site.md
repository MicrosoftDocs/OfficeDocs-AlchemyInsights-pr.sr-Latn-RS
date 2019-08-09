---
title: Kreiranje SharePoint lokacije
ms.author: efrene
author: efrene
ms.date: 1/16/2019
ms.audience: ITPro
ms.topic: article
ms.collection: Adm_O365
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "5200004"
- "1386"
- "2303"
ms.assetid: e62b9f80-b017-42dc-9464-f4e32c19d6c9
ms.openlocfilehash: ad1a77b69d2d453dbd3daa304759238b329f96ba
ms.sourcegitcommit: 631e527967f4d641bc9227642ffe38967ae87a00
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/09/2019
ms.locfileid: "36269930"
---
# <a name="create-a-sharepoint-site"></a><span data-ttu-id="9144e-102">Kreiranje SharePoint lokacije</span><span class="sxs-lookup"><span data-stu-id="9144e-102">Create a SharePoint site</span></span>

<span data-ttu-id="9144e-103">Možete da vidite u nastavku su navedene informacije o kreiranje SharePoint lokacije:</span><span class="sxs-lookup"><span data-stu-id="9144e-103">You can see the following for information about SharePoint site creation:</span></span>
- <span data-ttu-id="9144e-104">[Upravljanje lokacijama u centru za admin novu SharePoint](https://docs.microsoft.com/sharepoint/manage-site-creation): Saznajte više o opcijama kreiranja lokacije, uključujući kreiranje klasični lokacije ili lokacije timova koji ne sadrži grupu Office 365.</span><span class="sxs-lookup"><span data-stu-id="9144e-104">[Manage sites in the new SharePoint admin center](https://docs.microsoft.com/sharepoint/manage-site-creation): Learn about site creation options, including how to create a classic site or a teams site that doesn't include an Office 365 group.</span></span>
- <span data-ttu-id="9144e-105">[Kreiraj lokaciju tima u sistemu SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d?ui=en-US&amp;rs=en-US&amp;ad=US): Saznajte kako da kreirate lokaciju tima.</span><span class="sxs-lookup"><span data-stu-id="9144e-105">[Create a team site in SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d?ui=en-US&amp;rs=en-US&amp;ad=US): Learn how to create a team site.</span></span>
- <span data-ttu-id="9144e-106">[Kreiranje lokacije u SharePoint Online komunikacija](https://support.office.com/article/7fb44b20-a72f-4d2c-9173-fc8f59ba50eb): Saznajte kako da kreirate lokaciju za komunikacije.</span><span class="sxs-lookup"><span data-stu-id="9144e-106">[Create a communication site in SharePoint Online](https://support.office.com/article/7fb44b20-a72f-4d2c-9173-fc8f59ba50eb): Learn how to create a communications site.</span></span>
- <span data-ttu-id="9144e-107">[Upravljanje lokacijama u centru za admin novu SharePoint](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#create-a-site): Saznajte kako da kreirate lokaciju za klasični ili lokaciji tima koji ne sadrži grupu Office 365.</span><span class="sxs-lookup"><span data-stu-id="9144e-107">[Manage sites in the new SharePoint admin center](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#create-a-site):  Learn how to create a classic site or a team site that doesn't include an Office 365 group.</span></span>


  
> [! Savjeti]
> - <span data-ttu-id="9144e-109">Ne mogu da kreirate lokaciju sa istom URL postojeće lokacije.</span><span class="sxs-lookup"><span data-stu-id="9144e-109">You cannot create a site with the same URL of an existing site.</span></span> <span data-ttu-id="9144e-110">Ako ste izbrisali lokaciju i su u želji da ponovo koristite URL, jeste izbrisane lokacija i dalje postoji ispod **lokacija izbrisane**.</span><span class="sxs-lookup"><span data-stu-id="9144e-110">If you deleted a site and are wishing to re-use the URL, it's possible the deleted site still exists under **Deleted sites**.</span></span> <span data-ttu-id="9144e-111">Da biste upravljali izbrisane lokacijama potražite [Brisanje lokacije](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site).</span><span class="sxs-lookup"><span data-stu-id="9144e-111">To manage deleted sites see, [Delete a Site](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site).</span></span> <span data-ttu-id="9144e-112">Da biste potpuno uklonili lokacija sa Powershell, pogledajte primer cmdlet [Remove-SPSite](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) .</span><span class="sxs-lookup"><span data-stu-id="9144e-112">To completely remove a site with Powershell, see the [Remove-SPSite](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) cmdlet example.</span></span>
> - <span data-ttu-id="9144e-113">Neki korisnici možda nećete moći da kreirate lokaciju.</span><span class="sxs-lookup"><span data-stu-id="9144e-113">Some users may not be able to create a site.</span></span> <span data-ttu-id="9144e-114">Vidi [Upravljanje Kreiranje lokacije u SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation).</span><span class="sxs-lookup"><span data-stu-id="9144e-114">See [Manage site creation in SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation).</span></span>
> - <span data-ttu-id="9144e-115">To je moguće da se lokacija pojavljuje zaglavljen u **Kreiranje** duže nego što je očekivano.</span><span class="sxs-lookup"><span data-stu-id="9144e-115">It's possible the site appears stuck at **Creating** longer than expected.</span></span> <span data-ttu-id="9144e-116">Ako više od 24 sata je prošlo od kad ste prvi put videli ovaj problem, odjavite kartu za podršku.</span><span class="sxs-lookup"><span data-stu-id="9144e-116">If more than 24 hours have passed since you first saw this issue, please log a support ticket.</span></span> <span data-ttu-id="9144e-117">U mnogim slučajevima, već radimo na rešenje.</span><span class="sxs-lookup"><span data-stu-id="9144e-117">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="9144e-118">Molim vas, dajte nam barem 24 sata da biste dovršili rešenje.</span><span class="sxs-lookup"><span data-stu-id="9144e-118">Please give us at least 24 hours to complete a solution.</span></span>
> - <span data-ttu-id="9144e-119">Ako je potrebno da kreirate novu lokaciju tima koji ne sadrži grupu Office 365</span><span class="sxs-lookup"><span data-stu-id="9144e-119">If you need to create a new team site that doesn't include an Office 365 group,</span></span> 


