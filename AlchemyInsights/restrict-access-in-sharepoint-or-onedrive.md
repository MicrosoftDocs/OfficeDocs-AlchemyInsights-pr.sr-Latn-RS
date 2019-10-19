---
title: Ograničavanje pristupa u sistemu SharePoint ili OneDrive
ms.author: mikeplum
author: MikePlumleyMSFT
ms.date: 8/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: e5458226fe33bd5cb3da1f608fb113b888fbfd16
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/18/2019
ms.locfileid: "36551465"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a><span data-ttu-id="0c5ab-102">Ograničavanje pristupa u sistemu SharePoint ili OneDrive</span><span class="sxs-lookup"><span data-stu-id="0c5ab-102">Restrict access in SharePoint or OneDrive</span></span>

<span data-ttu-id="0c5ab-103">U sistemu SharePoint i OneDrive ograničajte pristup stavkama kao što su datoteke, fascikle i liste dodeljivanjem pristupa samo grupama ili pojedincima kojima želite da pristupite.</span><span class="sxs-lookup"><span data-stu-id="0c5ab-103">In SharePoint and OneDrive, you restrict access to items like files, folders, and lists by granting access only to groups or individuals you want to have access.</span></span> <span data-ttu-id="0c5ab-104">Podrazumevano, dozvole u sistemu SharePoint su nasleđene od višeg u hijerarhiji.</span><span class="sxs-lookup"><span data-stu-id="0c5ab-104">By default, permissions in SharePoint are inherited from higher up in the hierarchy.</span></span> <span data-ttu-id="0c5ab-105">Zato datoteka nasleđuje dozvole iz fascikle koja nasleđuje dozvole iz biblioteke, što nasleđuje dozvole od lokacije.</span><span class="sxs-lookup"><span data-stu-id="0c5ab-105">So a file inherits its permissions from the folder, which inherits its permissions from the library, which inherits its permissions from the site.</span></span>
  
<span data-ttu-id="0c5ab-106">Možete da delite na višem nivou (kao što je deljenje čitave lokacije), a zatim da prekinete nasleđivanje ako ne želite da delite sve stavke na lokaciji.</span><span class="sxs-lookup"><span data-stu-id="0c5ab-106">You can share at a higher level (such as by sharing an entire site) and then break inheritance if you don't want to share all the items on the site.</span></span> <span data-ttu-id="0c5ab-107">Međutim, to ne preporučujemo zato što je održanje dozvola u budućnosti složenija i zbunjujuća.</span><span class="sxs-lookup"><span data-stu-id="0c5ab-107">However, we don't recommend this because it makes maintaining the permissions more complex and confusing in the future.</span></span> <span data-ttu-id="0c5ab-108">Evo šta možete uraditi:</span><span class="sxs-lookup"><span data-stu-id="0c5ab-108">Here's what you could do instead:</span></span>
  
- <span data-ttu-id="0c5ab-109">Ako, na primer, želite da delite celokupan sadržaj fascikle osim jedne datoteke u njoj, premestite tu datoteku na novu lokaciju koja se ne deli.</span><span class="sxs-lookup"><span data-stu-id="0c5ab-109">If, for example, you want to share all the contents of a folder except for one file in it, move that file to a new location that isn't shared.</span></span>
    
- <span data-ttu-id="0c5ab-110">Ako imate dve potfascikle u fascikli i želite da delite jednu potfasciklu sa grupama a i B i da dozvolite samo grupisanje pristupa drugoj potfascikli, podelite nadređenu fasciklu sa grupom a i dodajte grupu B u prvu potfasciklu.</span><span class="sxs-lookup"><span data-stu-id="0c5ab-110">If you have two subfolders in a folder, and you want to share one subfolder with groups A and B and allow only group A access to the second subfolder, share the parent folder with group A and add group B to the first subfolder.</span></span>
    
[<span data-ttu-id="0c5ab-111">Prestanak deljenja datoteke ili fascikle</span><span class="sxs-lookup"><span data-stu-id="0c5ab-111">Stop sharing a file or folder </span></span>](https://go.microsoft.com/fwlink/?linkid=2008861)
  

