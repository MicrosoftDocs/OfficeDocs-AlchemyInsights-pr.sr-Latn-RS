---
title: Adr.
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/8/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "645"
- "1300012"
ms.assetid: 26a7eebb-1424-4ddc-a123-af1cc94bc40f
ms.openlocfilehash: eafd31e91340b41b7948fb1fe62889731b816d9a
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/25/2019
ms.locfileid: "36737203"
---
# <a name="adfs-federation-certificate-expiring"></a><span data-ttu-id="ef1dd-102">Adr.</span><span class="sxs-lookup"><span data-stu-id="ef1dd-102">ADFS Federation Certificate Expiring</span></span>

<span data-ttu-id="ef1dd-103">Da biste riješili taj problem, slijedite ove korake:</span><span class="sxs-lookup"><span data-stu-id="ef1dd-103">To resolve this issue, follow these steps:</span></span>
  
1. <span data-ttu-id="ef1dd-104">Instalirajte Microsoft Azure Active Directory modul za Windows PowerShell na računaru (ako modul nije već instaliran).</span><span class="sxs-lookup"><span data-stu-id="ef1dd-104">Install the Microsoft Azure Active Directory Module for Windows PowerShell on the computer (if the module isn't already installed).</span></span> <span data-ttu-id="ef1dd-105">Da biste to uradili, idite da biste [upravljali AZURE oglasima pomoću Windows PowerShell](https://aka.ms/aadposh).</span><span class="sxs-lookup"><span data-stu-id="ef1dd-105">To do this, go to [Manage Azure AD using Windows PowerShell](https://aka.ms/aadposh).</span></span>

2. <span data-ttu-id="ef1dd-106">Sledite korake u odjeljku "scenario 1: istekao je certifikat potpisa" AD FS "-za potpisivanje" [postoji problem "Došlo je do problema sa pristupom lokaciji" iz AD FS-a kada se federirani korisnik prijavi na Office 365, Azure ili Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span><span class="sxs-lookup"><span data-stu-id="ef1dd-106">Follow the steps in the "Scenario 1: The AD FS token-signing certificate expired" section of ["There was a problem accessing the site" error from AD FS when a federated user signs in to Office 365, Azure, or Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span></span>

3. <span data-ttu-id="ef1dd-107">Sledite korake u programu [Update ili popravite postavke federovanog domena u sistemu Office 365, Azure ili Intune](https://docs.microsoft.com/office365/troubleshoot/security/update-federated-domain-office-365).</span><span class="sxs-lookup"><span data-stu-id="ef1dd-107">Follow the steps in [Update or repair the settings of a federated domain in Office 365, Azure, or Intune](https://docs.microsoft.com/office365/troubleshoot/security/update-federated-domain-office-365).</span></span>

    <span data-ttu-id="ef1dd-108">Da biste saznali više o obnavljanju certifikata Federacije, pogledajte odeljak [obnavljanje certifikata Federacije za Office 365 i Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span><span class="sxs-lookup"><span data-stu-id="ef1dd-108">To learn more about renewing Federation certificates, see [Renew federation certificates for Office 365 and Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span></span>
