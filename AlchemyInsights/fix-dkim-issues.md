---
title: Rešavanje problema sa programom DKIM
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1389
ms.assetid: ''
ms.openlocfilehash: 35e8023d26fe26211e27521ceb8751d2d7fc7a21
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/14/2020
ms.locfileid: "47744964"
---
# <a name="fix-dkim-setup-issues"></a><span data-ttu-id="28a27-102">Rešavanje problema sa programom DKIM</span><span class="sxs-lookup"><span data-stu-id="28a27-102">Fix DKIM setup issues</span></span>

<span data-ttu-id="28a27-103">Ako imate problema sa programom DKIM za prilagođeni domen, koristite sledeće korake:</span><span class="sxs-lookup"><span data-stu-id="28a27-103">If you experience issues enabling DKIM for your custom domain, use the following steps:</span></span>

- <span data-ttu-id="28a27-104">Većina DKIM instalacija je povezana sa neodgovarajućim DNS zapisima.</span><span class="sxs-lookup"><span data-stu-id="28a27-104">Most DKIM setup issues are related to incorrect DNS records.</span></span> <span data-ttu-id="28a27-105">Verifikujte ispravno oblikovan zapis DKIM CNAME (a**ne** txt zapis).</span><span class="sxs-lookup"><span data-stu-id="28a27-105">Verify the DKIM CNAME record (**not** a TXT record) is formatted correctly.</span></span> <span data-ttu-id="28a27-106">Više informacija potražite u članku ova [Tema](https://docs.microsoft.com/microsoft-365/security/office-365-security/use-dkim-to-validate-outbound-email#steps-you-need-to-do-to-manually-set-up-dkim).</span><span class="sxs-lookup"><span data-stu-id="28a27-106">For more information, see this [topic](https://docs.microsoft.com/microsoft-365/security/office-365-security/use-dkim-to-validate-outbound-email#steps-you-need-to-do-to-manually-set-up-dkim).</span></span>

- <span data-ttu-id="28a27-107">Kada kreirate ili ažurirate DKIM DNS zapise u usluzi DNS hostinga za domen (obično je to registar domena), sačekajte da se DNS zapisi prošire.</span><span class="sxs-lookup"><span data-stu-id="28a27-107">After you create or update your DKIM DNS records at the DNS hosting service for your domain (typically, your domain registrar), wait for the DNS records to propagate.</span></span>

- <span data-ttu-id="28a27-108">Ako ne možete da kreirate DKIM DNS zapise u centru administracije, možete da ga zamenite \<CustomDomain\> prilagođenim domenom (na primer, contoso.com) i da pokrećete ovu komandu u [Exchange online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell): `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true` .</span><span class="sxs-lookup"><span data-stu-id="28a27-108">If you can't create the DKIM DNS records in the admin center, you can replace \<CustomDomain\> with your custom domain (for example, contoso.com) and run this command in [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell): `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true`.</span></span>
