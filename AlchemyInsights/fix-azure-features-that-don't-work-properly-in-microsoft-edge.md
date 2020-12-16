---
title: Šta da radite ako Azure funkcije ne funkcionišu ispravno u usluzi Microsoft Edge
ms.author: v-jmathew
author: v-jmathew
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004128"
- "7206"
ms.openlocfilehash: 463236bcd9ff480471604c992aa1ed1ed4ac2987
ms.sourcegitcommit: 2e4a5153e530bf15744a52e982eeb0d99757e9d2
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/04/2020
ms.locfileid: "49583784"
---
# <a name="what-to-do-if-azure-features-dont-work-properly-in-microsoft-edge"></a><span data-ttu-id="4595c-102">Šta da radite ako Azure funkcije ne funkcionišu ispravno u usluzi Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="4595c-102">What to do if Azure features don't work properly in Microsoft Edge</span></span>

<span data-ttu-id="4595c-103">Microsoft Edge ima [poznate probleme](https://go.microsoft.com/fwlink/?linkid=2140608) koji su povezani sa bezbednosnim zonama i koji možda utiču na to kako se Azure korisnici prijavljuju u Windows centar administracije.</span><span class="sxs-lookup"><span data-stu-id="4595c-103">Microsoft Edge has [known issues](https://go.microsoft.com/fwlink/?linkid=2140608) that are related to security zones and might affect how Azure users log in to Windows Admin Center.</span></span> <span data-ttu-id="4595c-104">Ako imate problema prilikom korišćenja Azure funkcija sa Microsoft Edge, Isprobajte sledeće korake:</span><span class="sxs-lookup"><span data-stu-id="4595c-104">If you're having trouble using Azure features with Microsoft Edge, try the following steps:</span></span>

1. <span data-ttu-id="4595c-105">U meniju **Start** potražite **Internet opcije** i izaberite je.</span><span class="sxs-lookup"><span data-stu-id="4595c-105">In the **Start** menu, search for **Internet Options** and select it.</span></span>
2. <span data-ttu-id="4595c-106">U dijalogu **Svojstva Internet** izaberite karticu **bezbednost** .</span><span class="sxs-lookup"><span data-stu-id="4595c-106">In the **Internet Properties** dialog box, go to the **Security** tab.</span></span>
3. <span data-ttu-id="4595c-107">Izaberite zonu **pouzdanih lokacija** , a zatim izaberite dugme **lokacije** .</span><span class="sxs-lookup"><span data-stu-id="4595c-107">Select the **Trusted sites** zone and then select the **Sites** button.</span></span>
4. <span data-ttu-id="4595c-108">U dijalogu **pouzdane lokacije** Dodajte URL adrese mrežnog prolaza [https://login.microsoftonline.com](https://login.microsoftonline.com) i [https://login.live.com](https://login.live.com) , a zatim kliknite na dugme **Zatvori**.</span><span class="sxs-lookup"><span data-stu-id="4595c-108">In the **Trusted sites** dialog box, add your gateway URL as well as [https://login.microsoftonline.com](https://login.microsoftonline.com) and [https://login.live.com](https://login.live.com), and then select **Close**.</span></span>
5. <span data-ttu-id="4595c-109">U dijalogu **Internet Svojstva** idite na karticu **Privatnost** .</span><span class="sxs-lookup"><span data-stu-id="4595c-109">In the **Internet Properties** dialog box, go to the **Privacy** tab.</span></span>
6. <span data-ttu-id="4595c-110">U odeljku **blokator iskačućih prozora** izaberite stavku **Postavke**.</span><span class="sxs-lookup"><span data-stu-id="4595c-110">In the **Pop-up Blocker** section, select **Settings**.</span></span> <span data-ttu-id="4595c-111">U dijalogu koji se otvara Dodajte URL adrese mrežnog prolaza [https://login.microsoftonline.com](https://login.microsoftonline.com) i [https://login.live.com](https://login.live.com) , a zatim kliknite na dugme **Zatvori**.</span><span class="sxs-lookup"><span data-stu-id="4595c-111">In the dialog box that opens, add your gateway URL as well as [https://login.microsoftonline.com](https://login.microsoftonline.com) and [https://login.live.com](https://login.live.com), and then select **Close**.</span></span>