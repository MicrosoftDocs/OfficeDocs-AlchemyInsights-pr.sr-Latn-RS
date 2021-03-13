---
title: Automatsko šifrovanje usluge Office 365 e-pošte koje su poslate na određene domene
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/24/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000078"
- "7342"
ms.openlocfilehash: 7fb96a30cd1922bd39a4b99a7ecd869622f3a466
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/11/2021
ms.locfileid: "50749302"
---
# <a name="automatically-encrypt-office-365-email-messages-sent-to-certain-domains"></a><span data-ttu-id="4a4c2-102">Automatsko šifrovanje usluge Office 365 e-pošte koje su poslate na određene domene</span><span class="sxs-lookup"><span data-stu-id="4a4c2-102">Automatically encrypt Office 365 email messages sent to certain domains</span></span>

1. <span data-ttu-id="4a4c2-103">Iz [Exchange centra administracije](https://outlook.office365.com/ecp/)odaberite stavku **protok pošte > pravila**.</span><span class="sxs-lookup"><span data-stu-id="4a4c2-103">From the [Exchange admin center](https://outlook.office365.com/ecp/), choose **mail flow > rules**.</span></span> 
2. <span data-ttu-id="4a4c2-104">Kliknite na **novu (+)** ikonu, a zatim izaberite stavku **primene Office 365 Message šifrovanje i zaštita prava na poruke**.</span><span class="sxs-lookup"><span data-stu-id="4a4c2-104">Click the **New (+)** icon, and then click **Apply Office 365 Message Encryption and rights protection to messages**.</span></span>
3. <span data-ttu-id="4a4c2-105">U **ime** unesite ime pravila, kao što je *šifrovanje poruka koje se šalju u contoso.com*.</span><span class="sxs-lookup"><span data-stu-id="4a4c2-105">In **Name**, enter a name for the rule, such as *Encrypt messages sent to contoso.com*.</span></span>
4. <span data-ttu-id="4a4c2-106">U okviru **Primenjivanje ovog pravila ako**, odaberite **primalac > Domain**.</span><span class="sxs-lookup"><span data-stu-id="4a4c2-106">In **Apply this rule if**, choose **The recipient > domain is**.</span></span> 
5. <span data-ttu-id="4a4c2-107">Unesite ime domena, kao što je **contoso.com**.</span><span class="sxs-lookup"><span data-stu-id="4a4c2-107">Enter the name of the domain, such as **contoso.com**.</span></span>
6. <span data-ttu-id="4a4c2-108">Kliknite na ikonu **Dodaj (+)** , a zatim kliknite na dugme **u redu**.</span><span class="sxs-lookup"><span data-stu-id="4a4c2-108">Click the **Add (+)** icon, and then click **OK**.</span></span>
7. <span data-ttu-id="4a4c2-109">Pored polja **uradi sledeće** , izaberite stavku **Izaberi jednu**.</span><span class="sxs-lookup"><span data-stu-id="4a4c2-109">Next to the **Do the following** field, click **Select one**.</span></span> 
8. <span data-ttu-id="4a4c2-110">U padajućem meniju **RMS predloška** izaberite stavku **šifrovanje**, a zatim kliknite na dugme **u redu**.</span><span class="sxs-lookup"><span data-stu-id="4a4c2-110">In the **RMS template** drop-down menu, select **Encrypt**, and then click **OK**.</span></span> <span data-ttu-id="4a4c2-111">(Ako ne vidite ovu opciju, to znači da vaš plan ne podrazumeva automatsko šifrovanje.</span><span class="sxs-lookup"><span data-stu-id="4a4c2-111">(If you don't see this option, it means your plan doesn't include automatic encryption.</span></span> <span data-ttu-id="4a4c2-112">Ali možete da ga dodate!)</span><span class="sxs-lookup"><span data-stu-id="4a4c2-112">But you can add it!)</span></span>
9. <span data-ttu-id="4a4c2-113">Odaberite opcionalnu selekciju (sa liste opcionalnih izbora koje možete da napravite u ovom momentu, od kojih se mnogi mogu ostaviti podrazumevanom postavkom za jednostavnost).</span><span class="sxs-lookup"><span data-stu-id="4a4c2-113">Choose any optional selection (from a list of optional selections that you can make at this point, many of which can be left with the default setting for simplicity).</span></span>
10. <span data-ttu-id="4a4c2-114">Kliknite na dugme **Sačuvaj**.</span><span class="sxs-lookup"><span data-stu-id="4a4c2-114">Click **Save**.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="4a4c2-115">Uvek možete da se vratite i uredite ovo pravilo kasnije.</span><span class="sxs-lookup"><span data-stu-id="4a4c2-115">You can always come back and edit this rule later.</span></span>

<span data-ttu-id="4a4c2-116">Više informacija o kreiranju pravila za šifrovanje potražite u članku [Definisanje pravila toka pošte za šifrovanje e-poruka u sistemu Office 365](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email)</span><span class="sxs-lookup"><span data-stu-id="4a4c2-116">For more information about creating rules for encryption, see [Define mail flow rules to encrypt email messages in Office 365](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email)</span></span>