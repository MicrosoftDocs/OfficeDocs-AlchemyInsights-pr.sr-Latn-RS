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
# <a name="troubleshoot-issues-with-enrolling-windows-devices-in-microsoft-intune"></a>Rešavanje problema sa upiљem Windows uređaja u Microsoft Intune

Pregledajte resurse dole navedene riješiti tvoj problem sada. 
  
Neke uobičajene poruke o grešci i rezolucija korake:
  
 **Ne može biti instaliran softver, 0x80cf4017:** Vaš račun certifikat je istekao. Ponovo preuzmite paket softvera za PC klijent u Intune Admin konzoli. Pregledajte ovu dokumentaciju za više informacija. 
  
 **Kôd greške 0x801c0003:** I greška se može pojaviti u sljedećim scenarijima: 
  
1. Korisnik ima više uređaja je upisano od ograničenja uređaja. Pregledajte ove dokumente da [uklonite uređaj](https://docs.microsoft.com/en-us/intune/devices-wipe) ili [promijenite ograničenja uređaja](https://docs.microsoft.com/en-us/intune/enrollment-restrictions-set#set-device-limit-restrictions).
    
2. „Korisnicima možete pridružiti uređaji azurno AD” je postavljen na „nijedan”. Postavite ga na sve, ili izaberite korisnika. Pregledajte [ovu dokumentaciju](https://docs.microsoft.com/en-us/azure/active-directory/device-management-azure-portal#configure-device-settings) za više informacija. 
    
3. Uređaj je već upisan drugi korisnik. Ako je to slučaj, uklonite uređaj iz konzole za Azure Intune ili ručno unenroll uređaj pre nego što pokušate ponovo.
    
4. Uređaj je Windows 10 Home. Samo Windows 10 Pro, obrazovanje i Enterprise MJ ne može da se pridruži Azure Active Directory.
    
Dodatni resursi da biste rešili problem:
  
1. Koristite [Intune rešavanje problema Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) da utvrdite i otklonite uobičajene upisa otkazivanja. Pregledajte [ovaj dokument](https://docs.microsoft.com/en-us/intune/help-desk-operators) za više detalja. 
    
2. Pregledajte ove dokumente za listu uobičajenih grešaka koje sprečavaju upisa i rezolucijama svakom: [Vodič za rešavanje problema](https://support.microsoft.com/en-us/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) i [otklanjanje poteškoća doc](https://docs.microsoft.com/en-us/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).
    
Da [biste saznali kako da se upišu Windows uređaja u Microsoft Intune](https://docs.microsoft.com/en-us/intune/windows-enroll).
  
