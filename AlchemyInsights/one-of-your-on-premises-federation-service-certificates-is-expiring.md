---
title: Jedan od tvojih potvrda o službi Federacije
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 172084b7-68a1-42a5-944d-2e871eaa2972
ms.openlocfilehash: 24c369c61ad7cf7a9fe101ac29271c32e5159c1f
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43761397"
---
# <a name="one-of-your-on-premises-federation-service-certificates-is-expiring"></a><span data-ttu-id="fd7dc-102">Jedan od tvojih potvrda o službi Federacije</span><span class="sxs-lookup"><span data-stu-id="fd7dc-102">One of your on-premises Federation Service Certificates is expiring</span></span>

<span data-ttu-id="fd7dc-103">Da biste riješili taj problem, slijedite ove korake:</span><span class="sxs-lookup"><span data-stu-id="fd7dc-103">To resolve this issue, follow these steps:</span></span>
  
- <span data-ttu-id="fd7dc-104">Instalirajte Microsoft Azure Active Directory modul za Windows PowerShell na računaru (ako modul nije već instaliran).</span><span class="sxs-lookup"><span data-stu-id="fd7dc-104">Install the Microsoft Azure Active Directory Module for Windows PowerShell on the computer (if the module isn't already installed).</span></span> <span data-ttu-id="fd7dc-105">Da biste to uradili, idite na [Azure PowerShell aktivnog direktorijuma za grafik](https://docs.microsoft.com/powershell/azure/active-directory/install-adv2?view=azureadps-2.0)</span><span class="sxs-lookup"><span data-stu-id="fd7dc-105">To do this, go to [Azure Active Directory PowerShell for Graph ](https://docs.microsoft.com/powershell/azure/active-directory/install-adv2?view=azureadps-2.0)</span></span>
    
- <span data-ttu-id="fd7dc-106">Sledite korake u odjeljku "scenario 1: istekao je certifikat potpisa" AD FS "-za potpisivanje" [postoji problem "Došlo je do problema sa pristupom lokaciji" iz AD FS-a kada se federirani korisnik prijavi na Office 365, Azure ili Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span><span class="sxs-lookup"><span data-stu-id="fd7dc-106">Follow the steps in the "Scenario 1: The AD FS token-signing certificate expired" section of ["There was a problem accessing the site" error from AD FS when a federated user signs in to Office 365, Azure, or Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span></span>
    
- <span data-ttu-id="fd7dc-107">Sledite korake u t[Kako da ažurirate ili popravite postavke federovanog domena u sistemu Office 365, Azure ili Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).</span><span class="sxs-lookup"><span data-stu-id="fd7dc-107">Follow the steps in t[How to update or repair the settings of a federated domain in Office 365, Azure, or Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).</span></span>
    
<span data-ttu-id="fd7dc-108">Za više informacija o obnavljanju certifikata u Federaciji pogledajte odeljak [obnova certifikata za O365 i AZURE oglas](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span><span class="sxs-lookup"><span data-stu-id="fd7dc-108">For more information about renewing Federation certificates, see [Certificate renewal for O365 and Azure AD](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span></span>
  

