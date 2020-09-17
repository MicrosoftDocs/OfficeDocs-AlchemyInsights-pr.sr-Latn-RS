---
title: Identifikovanje aktivnosti pravila prijemnog poštanskog sandučeta u evidenciji nadzora
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1368"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 3de6fcde6dc649cb77077d469cc66d4003e0c890
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/15/2020
ms.locfileid: "47779065"
---
# <a name="identify-inbox-rule-activity-in-audit-logs"></a><span data-ttu-id="b8491-102">Identifikovanje aktivnosti pravila prijemnog poštanskog sandučeta u evidenciji nadzora</span><span class="sxs-lookup"><span data-stu-id="b8491-102">Identify inbox rule activity in audit logs</span></span>

<span data-ttu-id="b8491-103">Možete da koristite pretragu evidencije nadzora u Microsoft 365 Security & centar za usaglašenost da biste prikazali događaje pravila prijemnog poštanskog sandučeta (kreiranje, izmena i brisanje pravila prijemnog poštanskog sandučeta).</span><span class="sxs-lookup"><span data-stu-id="b8491-103">You can use audit log search in the Microsoft 365 Security & Compliance Center to view inbox rule events (creating, modifying, and deleting inbox rules).</span></span>

1. <span data-ttu-id="b8491-104">Prijavite se u [Microsoft 365 Security & centar za usaglašenost](https://protection.office.com/).</span><span class="sxs-lookup"><span data-stu-id="b8491-104">Log in to the [Microsoft 365 Security & Compliance Center](https://protection.office.com/).</span></span>

2. <span data-ttu-id="b8491-105">Idite na stranicu **Search**  >  **Pretraga evidencije nadgledanja** za pretraživanje.</span><span class="sxs-lookup"><span data-stu-id="b8491-105">Go to the **Search** > **Audit log search** page.</span></span>

3. <span data-ttu-id="b8491-106">Izaberite opseg datuma u poljima **početni** i **Krajnji datum** .</span><span class="sxs-lookup"><span data-stu-id="b8491-106">Select the date range in the **Start date** and **End date** fields.</span></span>

4. <span data-ttu-id="b8491-107">U okviru stavke **aktivnosti Exchange poštanskog sandučeta**potvrdite da je polje **aktivnosti** postavljeno na **novo-inboxpravilo kreiranje/izmena/omogućavanje/onemogućavanje pravila prijemnog poštanskog sandučeta**.</span><span class="sxs-lookup"><span data-stu-id="b8491-107">Under **Exchange Mailbox Activities**, verify the **Activities** field is set to **New-InboxRule Create/modify/enable/disable inbox rule**.</span></span>

5. <span data-ttu-id="b8491-108">Kliknite na dugme **Pretraži**.</span><span class="sxs-lookup"><span data-stu-id="b8491-108">Click **Search**.</span></span>

<span data-ttu-id="b8491-109">U rezultatima izaberite zapis nadzora.</span><span class="sxs-lookup"><span data-stu-id="b8491-109">In the results, select an audit record.</span></span> <span data-ttu-id="b8491-110">U okviru detalji, kliknite na dugme **više informacija**.</span><span class="sxs-lookup"><span data-stu-id="b8491-110">In the details flyout, click **More Information**.</span></span> <span data-ttu-id="b8491-111">Informacije o postavkama pravila prijemnog poštanskog sandučeta prikazuju se u polju **Parametri** .</span><span class="sxs-lookup"><span data-stu-id="b8491-111">Information about the inbox rule settings is displayed in the **Parameters** field.</span></span>

<span data-ttu-id="b8491-112">Više informacija potražite u članku [Utvrđivanje toga da li je korisnik kreirao pravilo prijemnog poštanskog sandučeta](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule)</span><span class="sxs-lookup"><span data-stu-id="b8491-112">For more information, see [Determining if a user created an inbox rule](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule)</span></span>
