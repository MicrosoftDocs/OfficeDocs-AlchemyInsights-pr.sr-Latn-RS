---
title: Omogućavanje sistema Office 365 ATP za SharePoint, OneDrive i Microsoft timove
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Admin_O365
ms.custom: 3100021
ms.openlocfilehash: c84458622ae86bcf0f9f541a3a209b4f0ff2fc3f
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/14/2020
ms.locfileid: "47709921"
---
# <a name="enable-office-365-advanced-threat-protection-for-sharepoint-online-onedrive-and-microsoft-teams"></a><span data-ttu-id="ca6e7-102">Omogućavanje usluge Office 365 napredne zaštite pretnji za SharePoint online, OneDrive i Microsoft timove</span><span class="sxs-lookup"><span data-stu-id="ca6e7-102">Enable Office 365 Advanced Threat Protection for SharePoint Online, OneDrive, and Microsoft Teams</span></span>

1. <span data-ttu-id="ca6e7-103">Idite na https://protection.office.com i prijavite se.</span><span class="sxs-lookup"><span data-stu-id="ca6e7-103">Go to https://protection.office.com and sign in.</span></span>
2. <span data-ttu-id="ca6e7-104">Odaberite stavku smernice **za upravljanje pretnjama**i  >  **Policy**  >  **bezbednost**.</span><span class="sxs-lookup"><span data-stu-id="ca6e7-104">Choose **Threat management** > **Policy** > **Safe Attachments**.</span></span>
3. <span data-ttu-id="ca6e7-105">Izaberite stavku **UKLJUČI ATP za SharePoint, OneDrive i Microsoft timove**, a zatim kliknite na dugme **Sačuvaj**.</span><span class="sxs-lookup"><span data-stu-id="ca6e7-105">Select **Turn on ATP for SharePoint, OneDrive, and Microsoft Teams**, and then click **Save**.</span></span>
4. <span data-ttu-id="ca6e7-106">Preporučuje Kao globalni administrator ili SharePoint online administrator, uradite " [setu-Spojstanar](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) " cmdlet pomoću parametra za **Disallowinittedpreuzeto** na *TRUE*.</span><span class="sxs-lookup"><span data-stu-id="ca6e7-106">(Recommended) As a global administrator or a SharePoint Online administrator, run the [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) cmdlet with the **DisallowInfectedFileDownload** parameter set to *true*.</span></span>
5. <span data-ttu-id="ca6e7-107">Preporučuje [Podesite upozorenja](https://docs.microsoft.com/microsoft-365/security/office-365-security/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) za otkrivene datoteke.</span><span class="sxs-lookup"><span data-stu-id="ca6e7-107">(Recommended) [Set up alerts](https://docs.microsoft.com/microsoft-365/security/office-365-security/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) for detected files.</span></span>

> [!NOTE]
> <span data-ttu-id="ca6e7-108">ATP će nZa skeniranje svake datoteke u usluzi SharePoint online, OneDrive ili Microsoft tima.</span><span class="sxs-lookup"><span data-stu-id="ca6e7-108">ATP will nto scan every single file in SharePoint Online, OneDrive, or Microsoft Teams.</span></span> <span data-ttu-id="ca6e7-109">Datoteke su isiskirale asihrono, kroz proces koji koristi deljenje i događaje sa gostima, zajedno sa pametnim houristikom i signalima pretnje za identifikovanje zlonamernih datoteka.</span><span class="sxs-lookup"><span data-stu-id="ca6e7-109">Files are scanned asynchronously, through a process that uses sharing and guest activity events, along with smart heuristics and threat signals to identify malicious files.</span></span> <span data-ttu-id="ca6e7-110">Pogledajte [ATP za SharePoint, OneDrive i Microsoft timove](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams).</span><span class="sxs-lookup"><span data-stu-id="ca6e7-110">See [ATP for SharePoint, OneDrive, and Microsoft Teams](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams).</span></span>