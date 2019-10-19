---
title: Kako onemogućiti spoljne grupe?
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "966"
- "6000006"
ms.assetid: 4e429507-039b-410e-a994-54b443d4e91e
ms.openlocfilehash: b2328ea85d3ff6ec722cc56d8a46395d8438f79c
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/18/2019
ms.locfileid: "36739507"
---
# <a name="how-to-disable-external-groups"></a><span data-ttu-id="09b16-102">Kako onemogućiti spoljne grupe?</span><span class="sxs-lookup"><span data-stu-id="09b16-102">How to disable External Groups</span></span>

<span data-ttu-id="09b16-103">Na mreži Yammer spoljne poruke primenjuje Exchange transportne pravila (ETRs), skup proaktivne kontrole kako bi se sprečilo deljenje informacija o preduzeću.</span><span class="sxs-lookup"><span data-stu-id="09b16-103">Yammer external messaging applies Exchange Transport Rules (ETRs), a set of proactive controls to prevent company information from being shared.</span></span> <span data-ttu-id="09b16-104">Da biste ograničili korisnike da kreiraju spoljne grupe, potrebno je da konfigurišete pravilo za prenos Exchange servera (ETR), a zatim da podesite Yammer da koristi Exchange prenos da biste blokirali spoljne poruke.</span><span class="sxs-lookup"><span data-stu-id="09b16-104">In order to restrict users from creating external groups, you need to configure an Exchange transport rule (ETR), and then configure Yammer to use the Exchange Transport rule to block external messaging.</span></span>
  
<span data-ttu-id="09b16-105">Nakon što ste kreirali pravilo u programu Exchange online admin Center, sledite ove korake da biste podesili ETR da se primeni na Yammer:</span><span class="sxs-lookup"><span data-stu-id="09b16-105">Once you have created a rule in Exchange Online admin center, follow these steps to set ETR to apply in Yammer:</span></span>
  
- <span data-ttu-id="09b16-106">Prijavite se na Yammer kao verifikovani administrator i u okviru **administratorskog centra za Yammer**, idite na C **sadržaj i bezbednosne \> postavke bezbednosti.**</span><span class="sxs-lookup"><span data-stu-id="09b16-106">Log on to Yammer as a verified admin, and in the **Yammer admin center**, go to C **Content and Security \> Security Settings.**</span></span>

- <span data-ttu-id="09b16-107">U okviru stavke **"spoljna razmena poruka**" izaberite stavku **Primeni pravila transporta Exchange servera (etrs) na mreži Yammer.**</span><span class="sxs-lookup"><span data-stu-id="09b16-107">Under **External Messaging**, select **Enforce your Exchange Online Exchange Transport Rules (ETRs) in Yammer.**</span></span>

- <span data-ttu-id="09b16-108">Kliknite na dugme **Sačuvaj**.</span><span class="sxs-lookup"><span data-stu-id="09b16-108">Choose **Save**.</span></span>

<span data-ttu-id="09b16-109">Više informacija potražite u članku [Onemogućavanje spoljnih poruka na mreži Yammer](https://docs.microsoft.com/yammer/work-with-external-users/disable-external-messaging).</span><span class="sxs-lookup"><span data-stu-id="09b16-109">For more information, see [Disable external messaging in a Yammer network](https://docs.microsoft.com/yammer/work-with-external-users/disable-external-messaging).</span></span>
  