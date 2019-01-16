---
title: Ograniči pristup u SharePoint ili OneDrive
ms.author: mikeplum
author: MikePlumleyMSFT
ms.date: 8/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: b6be074ed5f7e83f8196ca3fe90252673896569f
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/15/2019
ms.locfileid: "28310043"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a><span data-ttu-id="41414-102">Ograniči pristup u SharePoint ili OneDrive</span><span class="sxs-lookup"><span data-stu-id="41414-102">Restrict access in SharePoint or OneDrive</span></span>

<span data-ttu-id="41414-p101">U SharePoint i OneDrive, te ograničite pristup stavki kao što su datoteke, fascikle i liste od strane omogućavanjem pristupa samo na grupama ili pojedincima koji želite dati pristup. Podrazumevano, dozvole u SharePoint se prenose sa visine u hijerarhiji. Datoteka je nasleđuje svoje dozvole iz fascikle, koji se nasleđuje svoje dozvole od biblioteke, koji se nasleđuje svoje dozvole od lokacije.</span><span class="sxs-lookup"><span data-stu-id="41414-p101">In SharePoint and OneDrive, you restrict access to items like files, folders, and lists by granting access only to groups or individuals you want to have access. By default, permissions in SharePoint are inherited from higher up in the hierarchy. So a file inherits its permissions from the folder, which inherits its permissions from the library, which inherits its permissions from the site.</span></span>
  
<span data-ttu-id="41414-p102">Možete dijeliti na višem nivou (kao što deljenju čitavu lokaciju) i zatim prekid nasleđivanja ako ne želite da delite sve artikle na lokaciji. Međutim, ne preporučujemo vam ovo jer se onda održavanje dozvole složenije i konfuzno u budućnosti. Ovde je da li bi umesto toga:</span><span class="sxs-lookup"><span data-stu-id="41414-p102">You can share at a higher level (such as by sharing an entire site) and then break inheritance if you don't want to share all the items on the site. However, we don't recommend this because it makes maintaining the permissions more complex and confusing in the future. Here's what you could do instead:</span></span>
  
- <span data-ttu-id="41414-109">Ako, na primer, želite da delite sadržaj fascikle osim jedne datoteke u njoj, tu datoteku premestite na novu lokaciju koja nije deljena.</span><span class="sxs-lookup"><span data-stu-id="41414-109">If, for example, you want to share all the contents of a folder except for one file in it, move that file to a new location that isn't shared.</span></span>
    
- <span data-ttu-id="41414-110">Ako imate dva potfascikle u fascikli, a želite da delite jednu potfasciklu sa grupe A i B i dozvolite samo grupa A pristup u drugi potfasciklu, deljenje nadređene fascikle sa grupom A i dodavanje grupe B prve potfascikle.</span><span class="sxs-lookup"><span data-stu-id="41414-110">If you have two subfolders in a folder, and you want to share one subfolder with groups A and B and allow only group A access to the second subfolder, share the parent folder with group A and add group B to the first subfolder.</span></span>
    
[<span data-ttu-id="41414-111">Prestanete da delite datoteku ili fasciklu</span><span class="sxs-lookup"><span data-stu-id="41414-111">Stop sharing a file or folder </span></span>](https://go.microsoft.com/fwlink/?linkid=2008861)
  

