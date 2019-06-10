---
title: Korisnicima dali pristup SharePoint i OneDrive
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.date: 11/14/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: a689769dab24e12832ddc0937bc5ddc3d71dbee3
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/07/2019
ms.locfileid: "34759269"
---
# <a name="give-users-access-to-sharepoint-and-onedrive"></a><span data-ttu-id="9177b-102">Korisnicima dali pristup SharePoint i OneDrive</span><span class="sxs-lookup"><span data-stu-id="9177b-102">Give users access to SharePoint and OneDrive</span></span>

<span data-ttu-id="9177b-103">Do ovog problema najčešće dolazi kada korisnik je izbrisan i ponovo kreiran sa istom glavno ime korisnika (UPN).</span><span class="sxs-lookup"><span data-stu-id="9177b-103">This issue most frequently occurs when a user is deleted and re-created with the same user principal name (UPN).</span></span> <span data-ttu-id="9177b-104">Novi nalog kreiran pomoću različitih PUID (jedinstveni Passport ID) vrednost.</span><span class="sxs-lookup"><span data-stu-id="9177b-104">The new account is created by using a different PUID (Passport Unique ID) value.</span></span> <span data-ttu-id="9177b-105">Kada korisnik pokuša da pristupi kolekciju lokacija ili njihove OneDrive, je jedan pogrešan PUID korisnika.</span><span class="sxs-lookup"><span data-stu-id="9177b-105">When the user tries to access a site collection or their OneDrive, the user has an incorrect PUID.</span></span> <span data-ttu-id="9177b-106">Drugi scenario uključuje sinhronizacija direktorijuma sa organizacionih jedinica za Active Directory (OU).</span><span class="sxs-lookup"><span data-stu-id="9177b-106">A second scenario involves directory synchronization with an Active Directory organizational unit (OU).</span></span> <span data-ttu-id="9177b-107">Ako su korisnici već prijavljeni na SharePoint, i onda su se preselili u različitim OU i najhrabriji sa SharePoint, oni su iskusiti ovaj problem.</span><span class="sxs-lookup"><span data-stu-id="9177b-107">If users have already signed in to SharePoint, and then are moved to a different OU and resynced with SharePoint, they may experience this problem.</span></span>

<span data-ttu-id="9177b-108">Da biste rešili ovaj problem bi trebalo obnoviti originalne UPN sa koracima u članku,[Vraćanje korisnik u Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).</span><span class="sxs-lookup"><span data-stu-id="9177b-108">To resolve this issue you should restore the original UPN with the steps in the article,[Restore a user in Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).</span></span>

<span data-ttu-id="9177b-109">Nakon ovoga, možete da potvrdite da korisnik ima admin prava na OneDrive lokaciju tako što ćete pratiti korake za [Dodavanje admin je za korisnika OneDrive](https://docs.microsoft.com/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive)</span><span class="sxs-lookup"><span data-stu-id="9177b-109">After this is done, you can verify the user has admin rights to the OneDrive site by following the steps to [Add admin's for a user's OneDrive](https://docs.microsoft.com/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive)</span></span>

<span data-ttu-id="9177b-110">Za više informacija o nivoima dozvola, potražite u članku, [Razumevanje nivoa dozvola u sistemu SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span><span class="sxs-lookup"><span data-stu-id="9177b-110">For more information on permission levels, see the article, [Understanding permission levels in SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span></span>