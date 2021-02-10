---
title: Problem sa bezbednosnim grupama
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/09/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "8252"
- "9004397"
ms.openlocfilehash: 1198b79c3301bd2752a7385a6ba6746c8f0c2b5b
ms.sourcegitcommit: 22eaf0a151ab95414476f596db8d318b6540ff31
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/09/2021
ms.locfileid: "50177631"
---
# <a name="issue-with-security-groups"></a><span data-ttu-id="b87f1-102">Problem sa bezbednosnim grupama</span><span class="sxs-lookup"><span data-stu-id="b87f1-102">Issue with security groups</span></span>

<span data-ttu-id="b87f1-103">**Ako dobijate grešku na mreži AADDS104**</span><span class="sxs-lookup"><span data-stu-id="b87f1-103">**If you are getting Network Error AADDS104**</span></span>

<span data-ttu-id="b87f1-104">Nevažeća pravila mrežne bezbednosne grupe su Najčešći uzroci mrežnih grešaka za usluge Azure Active Directory (AD DS).</span><span class="sxs-lookup"><span data-stu-id="b87f1-104">Invalid network security group rules are the most common cause of network errors for Azure Active Directory Domain Services (AD DS).</span></span> <span data-ttu-id="b87f1-105">Bezbednosna grupa za mrežu za virtuelnu mrežu mora da omogući pristup određenim portima i protokolima.</span><span class="sxs-lookup"><span data-stu-id="b87f1-105">The network security group for the virtual network must allow access to specific ports and protocols.</span></span> <span data-ttu-id="b87f1-106">Ako su ovi portovi blokirani, Azure platforma ne može da nadgleda niti ažurira kontrolisano domen.</span><span class="sxs-lookup"><span data-stu-id="b87f1-106">If these ports are blocked, the Azure platform can't monitor or update the managed domain.</span></span> <span data-ttu-id="b87f1-107">Takođe je uključen sinhronizacija između Azure oglasa i Azure oglasa.</span><span class="sxs-lookup"><span data-stu-id="b87f1-107">The synchronization between the Azure AD and Azure AD DS is also impacted.</span></span> <span data-ttu-id="b87f1-108">Uverite se da su podrazumevani portovi otvoreni da biste izbegli prekid u usluzi usluge.</span><span class="sxs-lookup"><span data-stu-id="b87f1-108">Ensure you keep the default ports open to avoid interruption in service.</span></span>

<span data-ttu-id="b87f1-109">Da biste razumeli i rešili uobičajena obaveštenja za probleme sa konfiguracijom bezbednosti mreže, pogledajte članak [Dodavanje i verifikacija bezbednosnih grupa](https://docs.microsoft.com/azure/active-directory-domain-services/alert-nsg#verify-and-edit-existing-security-rules).</span><span class="sxs-lookup"><span data-stu-id="b87f1-109">To understand and to resolve common alerts for network security group configuration issues, see [Add and Verify Security Groups](https://docs.microsoft.com/azure/active-directory-domain-services/alert-nsg#verify-and-edit-existing-security-rules).</span></span>
