---
title: Problemi sa prijavljivanjem u Microsoft 365 aplikacije
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000571"
- "2559"
ms.openlocfilehash: 4e7612562d036f1c717817d3c883d6df80f86e2f
ms.sourcegitcommit: f28dafa0f727870038f72bc904da926daf4ec07b
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/05/2020
ms.locfileid: "44579879"
---
# <a name="fixing-the-microsoft-365-apps-your-computers-trusted-platform-module-is-not-functioning-properly-message"></a><span data-ttu-id="71670-102">Popravka Microsoft 365 aplikacija "modul pouzdane platforme računara ne funkcioniše ispravno" poruka</span><span class="sxs-lookup"><span data-stu-id="71670-102">Fixing the Microsoft 365 apps "Your computer's Trusted Platform module is not functioning properly" message</span></span>

<span data-ttu-id="71670-103">Da biste ispravili ovu grešku, pokušajte sledeće:</span><span class="sxs-lookup"><span data-stu-id="71670-103">To fix this error, try the following:</span></span>

- <span data-ttu-id="71670-104">Instalirajte najnovije ispravke za [Windows](https://support.microsoft.com/help/4027667/windows-10-update) i [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).</span><span class="sxs-lookup"><span data-stu-id="71670-104">Install the latest updates for [Windows](https://support.microsoft.com/help/4027667/windows-10-update) and [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).</span></span>
- <span data-ttu-id="71670-105">[Obrišite Office akreditive](https://docs.microsoft.com/eoffice/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) koristeći Windows upravljač akreditivima.</span><span class="sxs-lookup"><span data-stu-id="71670-105">[Clear Office credentials](https://docs.microsoft.com/eoffice/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br/>
    <span data-ttu-id="71670-106">**Napomena:** Putanje registratora za Office 2016 su promenjene u 16,0.</span><span class="sxs-lookup"><span data-stu-id="71670-106">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="71670-107">(Ex: \Software\microsoft\office\16.0\zajed\identitet\)</span><span class="sxs-lookup"><span data-stu-id="71670-107">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span></span>
- <span data-ttu-id="71670-108">Pokušajte sa [procesom oporavka korisnika](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-2) da biste otklonili greške modula pouzdane platforme (TPM).</span><span class="sxs-lookup"><span data-stu-id="71670-108">Try the [user recovery process](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-2) to fix Trusted Platform Module (TPM) failures.</span></span>
- <span data-ttu-id="71670-109">Postavite Vodolovni potencijalnog klijenta = 0 koristeći sledeće korake:</span><span class="sxs-lookup"><span data-stu-id="71670-109">Set the EnableADAL = 0 using the following steps:</span></span>  
    1. <span data-ttu-id="71670-110">Kliknite desnim tasterom miša na dugme "Start" operativnog sistema Windows, izaberite stavku **Pokreni**, otkucajte **Regedit**, a zatim odaberite **"u redu"**.</span><span class="sxs-lookup"><span data-stu-id="71670-110">Right-click the Windows Start button, choose **Run**, type **regedit**, and then choose **OK**.</span></span>
    2. <span data-ttu-id="71670-111">Izaberite **da** da dozvolite Registry Editoru da napravi izmjene na vašem uređaju.</span><span class="sxs-lookup"><span data-stu-id="71670-111">Select **Yes** to allow Registry Editor to make changes to your device.</span></span>
    3. <span data-ttu-id="71670-112">U programu Registry Editor dodajte DWORD vrednost **Enabpotencijalnog klijenta** sa postavkom **0** ispod HKEY_CURRENT_USER \Software\microsoft\office\16.0\pod\identity.</span><span class="sxs-lookup"><span data-stu-id="71670-112">In Registry Editor, add a DWORD value of **EnableADAL** with a setting of **0** under HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Common\Identity.</span></span>

<span data-ttu-id="71670-113">Više informacija potražite u članku [problemi prilikom prijavljivanja nakon ažuriranja na Office 2016 Build 16.0.7967 na Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).</span><span class="sxs-lookup"><span data-stu-id="71670-113">For more information, see [Connection issues in sign-in after update to Office 2016 build 16.0.7967 on Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).</span></span>