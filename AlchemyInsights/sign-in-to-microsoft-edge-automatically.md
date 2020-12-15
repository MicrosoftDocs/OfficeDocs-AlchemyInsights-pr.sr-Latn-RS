---
title: Automatsko prijavljivanje na Microsoft Edge
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 12/03/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9003848"
- "6898"
ms.openlocfilehash: 68a1119abd0a3f687b6448bb6e58c6485c239c0f
ms.sourcegitcommit: 94036315916fbc79dca2a692c2e9bc1139dd28f6
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/08/2020
ms.locfileid: "49678814"
---
# <a name="sign-in-to-microsoft-edge-automatically"></a><span data-ttu-id="d9e81-102">Automatsko prijavljivanje na Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="d9e81-102">Sign in to Microsoft Edge automatically</span></span>

<span data-ttu-id="d9e81-103">Microsoft Edge koristi podrazumevani nalog OS za automatsko prijavljivanje korisnika u skladu sa načinom konfigurisanja uređaja.</span><span class="sxs-lookup"><span data-stu-id="d9e81-103">Microsoft Edge uses the OS's default account to automatically sign in a user according to how the user's device is configured.</span></span> 

<span data-ttu-id="d9e81-104">Scenariji svakog tipa konfiguracije uređaja i njegovog procesa prijavljivanja zavisnog korisnika opisani su u nastavku:</span><span class="sxs-lookup"><span data-stu-id="d9e81-104">The scenarios of each type of device configuration and its dependent user sign-in process are described below:</span></span>

1. <span data-ttu-id="d9e81-105">**Uređaj je hibrid/AAD-J**: Ova opcija je dostupna u operativnom sistemu Windows 10, sistemu sa više nivoa i odgovarajućim verzijama servera.</span><span class="sxs-lookup"><span data-stu-id="d9e81-105">**The device is hybrid/AAD-J**: This option is available on Windows 10, down-level Windows, and corresponding server versions.</span></span> <span data-ttu-id="d9e81-106">Korisnici se automatski prijave pomoću Azure Active Directory (AD) naloga.</span><span class="sxs-lookup"><span data-stu-id="d9e81-106">Users are automatically signed in with their Azure Active Directory (AD)accounts.</span></span>
2. <span data-ttu-id="d9e81-107">**Uređaj je pridružen domenu**: Ova opcija je dostupna u operativnom sistemu Windows 10, u operativnom sistemu Windows 10 i odgovarajućim verzijama servera.</span><span class="sxs-lookup"><span data-stu-id="d9e81-107">**The device is domain-joined**: This option is available on Windows 10, down-level Windows, and corresponding server versions.</span></span> <span data-ttu-id="d9e81-108">Korisnici sa nalozima domena se podrazumevano ne potpiše automatski; da biste omogućili automatsko prijavljivanje za njih, koristite smernice **konfiguracione** polise.</span><span class="sxs-lookup"><span data-stu-id="d9e81-108">By default, users with domain accounts are not signed in automatically; to enable automatic sign-in for them, use the **ConfigureOnPremisesAccountAutoSignIn** policy.</span></span> <span data-ttu-id="d9e81-109">Da biste omogućili automatsko prijavljivanje za korisnike sa Azure AD nalozima, razmotrite hibridno pridruživanje njihovim uređajima.</span><span class="sxs-lookup"><span data-stu-id="d9e81-109">To enable automatic sign-in for users with Azure AD accounts, consider hybrid-joining their devices.</span></span>
3. <span data-ttu-id="d9e81-110">**Podrazumevani nalog OS je Microsoft nalog**: Ova opcija je dostupna u operativnom sistemu Windows 10 RS3 (verzija 1709, verzija 10.0.16299) i novije verzije.</span><span class="sxs-lookup"><span data-stu-id="d9e81-110">**The OS's default account is a Microsoft account**: This option is available on Windows 10 RS3 (version 1709, build 10.0.16299) and later versions.</span></span> <span data-ttu-id="d9e81-111">Nije moguće doći do scenarija na preduzećima uređajima.</span><span class="sxs-lookup"><span data-stu-id="d9e81-111">The scenario is unlikely to occur on enterprise devices.</span></span> <span data-ttu-id="d9e81-112">Međutim, ako je podrazumevani nalog OS Microsoft nalog, Microsoft Edge će automatski prijaviti korisnika pomoću Microsoft naloga.</span><span class="sxs-lookup"><span data-stu-id="d9e81-112">However, if the OS's default account is a Microsoft account, then Microsoft Edge will automatically sign in the user with the Microsoft account.</span></span>
 
 
