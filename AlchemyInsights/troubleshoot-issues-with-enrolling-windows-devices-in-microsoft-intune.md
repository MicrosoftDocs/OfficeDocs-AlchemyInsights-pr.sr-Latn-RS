---
title: Rešavanje problema sa upiљem Windows uređaja u Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 20e9bd42-2db0-4dd7-b480-966571494dd9
ms.openlocfilehash: 8d19bbd5a5782c7793c87499baf62b2eb7de82ae
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/15/2019
ms.locfileid: "28310231"
---
# <a name="troubleshoot-issues-with-enrolling-windows-devices-in-microsoft-intune"></a><span data-ttu-id="ede86-102">Rešavanje problema sa upiљem Windows uređaja u Microsoft Intune</span><span class="sxs-lookup"><span data-stu-id="ede86-102">Troubleshoot issues with enrolling Windows devices in Microsoft Intune</span></span>

<span data-ttu-id="ede86-103">Pregledajte resurse dole navedene riješiti tvoj problem sada.</span><span class="sxs-lookup"><span data-stu-id="ede86-103">Review the resources listed below to resolve your issue now.</span></span> 
  
<span data-ttu-id="ede86-104">Neke uobičajene poruke o grešci i rezolucija korake:</span><span class="sxs-lookup"><span data-stu-id="ede86-104">Some common error messages and resolution steps:</span></span>
  
 <span data-ttu-id="ede86-p101">**Ne može biti instaliran softver, 0x80cf4017:** Vaš račun certifikat je istekao. Ponovo preuzmite paket softvera za PC klijent u Intune Admin konzoli. Pregledajte ovu dokumentaciju za više informacija.</span><span class="sxs-lookup"><span data-stu-id="ede86-p101">**The software cannot be installed, 0x80cf4017:** Your account certificate has expired. Re-download the PC Client software package in the Intune Admin Console. Review this documentation for more information.</span></span> 
  
 <span data-ttu-id="ede86-108">**Kôd greške 0x801c0003:** I greška se može pojaviti u sljedećim scenarijima:</span><span class="sxs-lookup"><span data-stu-id="ede86-108">**Error code 0x801c0003:** The error can occur in the following scenarios:</span></span> 
  
1. <span data-ttu-id="ede86-p102">Korisnik ima više uređaja je upisano od ograničenja uređaja. Pregledajte ove dokumente da [uklonite uređaj](https://docs.microsoft.com/en-us/intune/devices-wipe) ili [promijenite ograničenja uređaja](https://docs.microsoft.com/en-us/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span><span class="sxs-lookup"><span data-stu-id="ede86-p102">The user has more devices enrolled than the device limit. Review these documents to [remove a device](https://docs.microsoft.com/en-us/intune/devices-wipe) or [change the device limit](https://docs.microsoft.com/en-us/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span></span>
    
2. <span data-ttu-id="ede86-p103">„Korisnicima možete pridružiti uređaji azurno AD” je postavljen na „nijedan”. Postavite ga na sve, ili izaberite korisnika. Pregledajte [ovu dokumentaciju](https://docs.microsoft.com/en-us/azure/active-directory/device-management-azure-portal#configure-device-settings) za više informacija.</span><span class="sxs-lookup"><span data-stu-id="ede86-p103">"Users may join devices to Azure AD" is set to "none". Set it to all or select users. Review [this documentation](https://docs.microsoft.com/en-us/azure/active-directory/device-management-azure-portal#configure-device-settings) for more information.</span></span> 
    
3. <span data-ttu-id="ede86-p104">Uređaj je već upisan drugi korisnik. Ako je to slučaj, uklonite uređaj iz konzole za Azure Intune ili ručno unenroll uređaj pre nego što pokušate ponovo.</span><span class="sxs-lookup"><span data-stu-id="ede86-p104">The device is already enrolled by another user. If that's the case, remove the device from the Azure Intune console or manually unenroll the device before trying again.</span></span>
    
4. <span data-ttu-id="ede86-p105">Uređaj je Windows 10 Home. Samo Windows 10 Pro, obrazovanje i Enterprise MJ ne može da se pridruži Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="ede86-p105">The device is Windows 10 Home. Only Windows 10 Pro, Education and Enterprise SKUs can join Azure Active Directory.</span></span>
    
<span data-ttu-id="ede86-118">Dodatni resursi da biste rešili problem:</span><span class="sxs-lookup"><span data-stu-id="ede86-118">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="ede86-p106">Koristite [Intune rešavanje problema Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) da utvrdite i otklonite uobičajene upisa otkazivanja. Pregledajte [ovaj dokument](https://docs.microsoft.com/en-us/intune/help-desk-operators) za više detalja.</span><span class="sxs-lookup"><span data-stu-id="ede86-p106">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures. Review [this document](https://docs.microsoft.com/en-us/intune/help-desk-operators) for more details.</span></span> 
    
2. <span data-ttu-id="ede86-121">Pregledajte ove dokumente za listu uobičajenih grešaka koje sprečavaju upisa i rezolucijama svakom: [Vodič za rešavanje problema](https://support.microsoft.com/en-us/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) i [otklanjanje poteškoća doc](https://docs.microsoft.com/en-us/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span><span class="sxs-lookup"><span data-stu-id="ede86-121">Review these documents for a list of common errors that prevent enrollment and resolutions to each: [Troubleshooting guide](https://support.microsoft.com/en-us/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) and [Troubleshooting doc](https://docs.microsoft.com/en-us/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span></span>
    
<span data-ttu-id="ede86-122">Da [biste saznali kako da se upišu Windows uređaja u Microsoft Intune](https://docs.microsoft.com/en-us/intune/windows-enroll).</span><span class="sxs-lookup"><span data-stu-id="ede86-122">[Learn how to enroll Windows devices in Microsoft Intune](https://docs.microsoft.com/en-us/intune/windows-enroll).</span></span>
  

