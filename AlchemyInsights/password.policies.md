---
title: Smernice za lozinke
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 03/11/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004595"
- "9277"
ms.openlocfilehash: 826e266d08aa68c0d4213d8058a0244f404fe965
ms.sourcegitcommit: 186281d0b87d67f041c127d4334faa937da9a48a
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/11/2021
ms.locfileid: "50747051"
---
# <a name="password-policies"></a><span data-ttu-id="8a81d-102">Smernice za lozinke</span><span class="sxs-lookup"><span data-stu-id="8a81d-102">Password policies</span></span>

<span data-ttu-id="8a81d-103">**Imam problema sa smernicama za lozinku za korisnika**</span><span class="sxs-lookup"><span data-stu-id="8a81d-103">**I'm having problems with the password policy for a user**</span></span>

- <span data-ttu-id="8a81d-104">Smernice za lozinku za korisnika zavise od toga da li je korisnik samo Cloud ili lokalno.</span><span class="sxs-lookup"><span data-stu-id="8a81d-104">The password policy for a user depends on whether the user is cloud only or on-premises.</span></span>
- <span data-ttu-id="8a81d-105">Cloud samo korisnici moraju odabrati lozinku koja ispunjava zahteve iz ovog članka: smernice za [lozinke koje se primenjuju samo na korisničke naloge u oblaku](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy?WT.mc_id=Portal-Microsoft_Azure_Support#password-policies-that-only-apply-to-cloud-user-accounts)</span><span class="sxs-lookup"><span data-stu-id="8a81d-105">Cloud only users must choose a password that meets the requirements in this article: [Password policies that only apply to cloud user accounts](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy?WT.mc_id=Portal-Microsoft_Azure_Support#password-policies-that-only-apply-to-cloud-user-accounts)</span></span>
- <span data-ttu-id="8a81d-106">Lokalni korisnici moraju da odaberu lozinku koja ispunjava lokalne zahteve.</span><span class="sxs-lookup"><span data-stu-id="8a81d-106">On-premises users must choose a password that meets the on-premises requirements.</span></span> <span data-ttu-id="8a81d-107">Ako lokalni korisnik ne može da podesi lozinku, potvrdite lokalno.</span><span class="sxs-lookup"><span data-stu-id="8a81d-107">If an on-premises user is unable to set their password, check your on-premises requirements.</span></span>

<span data-ttu-id="8a81d-108">**Ne znam kako da podesim ili provjerim smernice za rok važenja lozinke**</span><span class="sxs-lookup"><span data-stu-id="8a81d-108">**I don't know how to set or check password expiration policies**</span></span>

- <span data-ttu-id="8a81d-109">Možete da postavljate i proveravate smernice za rok važenja za korisnike oblaka u zakupcu pomoću programa PowerShell.</span><span class="sxs-lookup"><span data-stu-id="8a81d-109">You can set and check the expiration policy for cloud users in your tenant by using PowerShell.</span></span> <span data-ttu-id="8a81d-110">Izvršite uputstva iz ovog članka: [postavite ili potvrdite smernice lozinki pomoću programa PowerShell](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy?WT.mc_id=Portal-Microsoft_Azure_Support#set-or-check-the-password-policies-by-using-powershell)</span><span class="sxs-lookup"><span data-stu-id="8a81d-110">Follow the instructions in this article: [Set or check the password policies by using PowerShell](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy?WT.mc_id=Portal-Microsoft_Azure_Support#set-or-check-the-password-policies-by-using-powershell)</span></span>
- <span data-ttu-id="8a81d-111">Smernice za rok važenja lozinki za lokalne korisnike se postavljaju u lokalnu reklamu.</span><span class="sxs-lookup"><span data-stu-id="8a81d-111">The password expiration policy for on-premises users is set in your on-premises AD.</span></span>

<span data-ttu-id="8a81d-112">**Druge korisne veze:**</span><span class="sxs-lookup"><span data-stu-id="8a81d-112">**Other Helpful links:**</span></span>
- [<span data-ttu-id="8a81d-113">Prvi koraci uz poništavanje lozinke</span><span class="sxs-lookup"><span data-stu-id="8a81d-113">Getting Started with Password Reset</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy?WT.mc_id=Portal-Microsoft_Azure_Support#set-or-check-the-password-policies-by-using-powershell)
- [<span data-ttu-id="8a81d-114">Rešavanje problema sa Poništavanjem lozinke koja je pokrenula administrator</span><span class="sxs-lookup"><span data-stu-id="8a81d-114">Troubleshoot Administrator-initiated Password Reset</span></span>](https://docs.microsoft.com/azure/active-directory/active-directory-passwords-troubleshoot?WT.mc_id=Portal-Microsoft_Azure_Support#troubleshoot-the-password-reset-portal)
