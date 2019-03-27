---
title: 1336 RecoverableItems fascikla je puna
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1336
ms.assetid: a3a923e8-fece-4a26-b8b6-00970d75275e
ms.openlocfilehash: a048949d5284d018303d03aad26cdf26eee2fb5c
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/22/2019
ms.locfileid: "30776410"
---
# <a name="the-recoverable-items-folder-is-full"></a><span data-ttu-id="a6789-102">Spasen stavke fascikla je puna</span><span class="sxs-lookup"><span data-stu-id="a6789-102">The Recoverable Items folder is full</span></span>

<span data-ttu-id="a6789-103">Za Exchange Online poštanskih sandučića u Office 365, ograničenje skladištenja podrazumevanu fasciklu spasen stavke je 30 GB.</span><span class="sxs-lookup"><span data-stu-id="a6789-103">For Exchange Online mailboxes in Office 365, the default storage limit for the Recoverable Items folder is 30 GB.</span></span> <span data-ttu-id="a6789-104">Ograničenje prostora za fasciklu spasen stavke automatski se povećao na 100 GB, ako poštansko sanduče stavljen na parnice drži, drži eDiscovery, ili je dodeljen smernice za zadržavanje Office 365.</span><span class="sxs-lookup"><span data-stu-id="a6789-104">The storage limit for the Recoverable Items folder is automatically increased to 100 GB if the mailbox is placed on Litigation Hold, eDiscovery hold, or is assigned to an Office 365 retention policy.</span></span>
  
<span data-ttu-id="a6789-105">Kada fasciklu spasen stavke dostigne ograničenje prostora, funkcionalnost poštansko sanduče utiče na sledeće načine:</span><span class="sxs-lookup"><span data-stu-id="a6789-105">When the Recoverable Items folder reaches the storage limit, mailbox functionality is affected in the following ways:</span></span>
  
- <span data-ttu-id="a6789-106">Korisnika nije moguće izbrisati stavke iz poštansko sanduče.</span><span class="sxs-lookup"><span data-stu-id="a6789-106">The user can't delete items from the mailbox.</span></span>
    
- <span data-ttu-id="a6789-107">Upravlja pomoćnika za fascikle nije moguće izbrisati stavke na osnovu oznake zadržavanja ili postavke kontrolisane fascikle.</span><span class="sxs-lookup"><span data-stu-id="a6789-107">The Managed Folder Assistant can't delete items based on retention tag or managed folder settings.</span></span>
    
- <span data-ttu-id="a6789-108">Za Poštanske sandučiće koja sadrži jednu stavku za oporavak omogućen ili se nalaze na čekanju, proces zaštitu kopiranja pri upisivanju stranice ne mogu da održe verzije stavki uređivati od strane korisnika.</span><span class="sxs-lookup"><span data-stu-id="a6789-108">For mailboxes that have Single Item Recovery enabled or are placed on hold, the copy-on-write page protection process can't maintain versions of items edited by the user.</span></span>
    
- <span data-ttu-id="a6789-109">Za Poštanske sandučiće koji imaju poštansko sanduče nadgledanja omogućeno evidentiranje, stavke evidencije nadgledanja nema poštansko sanduče se mogu sačuvati u u reviziju potfasciklu u fascikli spasen stavke.</span><span class="sxs-lookup"><span data-stu-id="a6789-109">For mailboxes that have mailbox audit logging enabled, no mailbox audit log entries can be saved in the Audits subfolder in the Recoverable Items folder.</span></span>
    
<span data-ttu-id="a6789-110">Za Poštanske sandučiće koje se ne nalaze na čekanju, možete koristiti admini na `Search-Mailbox -SearchDumpsterOnly -DeleteContent` komandu u Exchange Online PowerShell da biste izbrisali stavke u fascikli spasen stavke.</span><span class="sxs-lookup"><span data-stu-id="a6789-110">For mailboxes that aren't on hold, admins can use the  `Search-Mailbox -SearchDumpsterOnly -DeleteContent` command in Exchange Online PowerShell to delete items in the Recoverable Items folder.</span></span> <span data-ttu-id="a6789-111">Za više informacija, pogledajte sljedeće teme:</span><span class="sxs-lookup"><span data-stu-id="a6789-111">For more information, see the following topics:</span></span> 
  
- [<span data-ttu-id="a6789-112">Pretraživanje i brisanje poruka</span><span class="sxs-lookup"><span data-stu-id="a6789-112">Search for and delete messages</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-for-and-delete-messagesadmin-help)
    
- [<span data-ttu-id="a6789-113">Pretraživanje-poštansko sanduče</span><span class="sxs-lookup"><span data-stu-id="a6789-113">Search-Mailbox</span></span>](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)
    
<span data-ttu-id="a6789-114">Za Poštanske sandučiće koje su na čekanju, admini morate da uklonite zadršku, pre nego što oni mogu izbrisanih stavki iz fascikle spasen stavke.</span><span class="sxs-lookup"><span data-stu-id="a6789-114">For mailboxes that are on hold, admins have to remove the hold before they can deleted items from the Recoverable Items folder.</span></span> <span data-ttu-id="a6789-115">Više informacija potražite u odeljku [Brisanje stavki u spasen stavki držite fasciklu od zasnovano na Poštanske sandučiće na](https://docs.microsoft.com/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).</span><span class="sxs-lookup"><span data-stu-id="a6789-115">For more information, see [Delete items in the Recoverable Items folder of cloud-based mailboxes on hold](https://docs.microsoft.com/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).</span></span>
  
<span data-ttu-id="a6789-116">Sprečavanja fasciklu spasen stavke postane puna, admini možete povećati ograničenje skladišta spasen stavki fascikle za Poštanske sandučiće na držite i podesite smernice za zadržavanje poštansko sanduče koje premešta stavke iz fascikle spasen stavke korisnikove arhivu poštansko sanduče.</span><span class="sxs-lookup"><span data-stu-id="a6789-116">To help prevent the Recoverable Items folder from becoming full, admins can increase the storage limit of the Recoverable Items folder for mailboxes on hold and set up a mailbox retention policy that moves items from the Recoverable Items folder to the user's archive mailbox.</span></span> <span data-ttu-id="a6789-117">Vidim da [poveća spasen stavke kvote za Poštanske sandučiće na držite](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold).</span><span class="sxs-lookup"><span data-stu-id="a6789-117">See [Increase the Recoverable Items quota for mailboxes on hold](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold).</span></span>
  
