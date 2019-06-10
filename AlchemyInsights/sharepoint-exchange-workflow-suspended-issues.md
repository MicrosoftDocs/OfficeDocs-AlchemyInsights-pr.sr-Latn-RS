---
title: Prvi koraci sa SharePoint Online
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 7ae05f21-eb16-4d71-9e19-4f097eb100d2
ms.openlocfilehash: afb1ef115d364ee3e2cf09ea850adb57ad1d44e6
ms.sourcegitcommit: 136b8209c52c2a05d0f2fdaab93b2cd92253fa2c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/07/2019
ms.locfileid: "34770576"
---
# <a name="workflows-in-sharepoint"></a><span data-ttu-id="720c7-102">Tokovi posla u sistemu SharePoint</span><span class="sxs-lookup"><span data-stu-id="720c7-102">Workflows in SharePoint</span></span>

<span data-ttu-id="720c7-103">Ako SharePoint tokovi posla ne šaljete e-mailove, vaša organizacija naišao na Exchange Online pošiljaoca granice.</span><span class="sxs-lookup"><span data-stu-id="720c7-103">If SharePoint workflows are not sending emails, your organization may have encountered the Exchange Online sender limits.</span></span>

<span data-ttu-id="720c7-104">„Tok posla je obustavljen” poruka o pogrešci može pojaviti ako imate jednu od sledećih stavki:</span><span class="sxs-lookup"><span data-stu-id="720c7-104">'Workflow is Suspended' error message may occur if you have one of the following items:</span></span>

- <span data-ttu-id="720c7-105">Imate toka posla u SharePoint na mreži koja koristi SharePoint 2010 ili SharePoint 2013 toka posla platforma tip.</span><span class="sxs-lookup"><span data-stu-id="720c7-105">You have a workflow in SharePoint Online that's using the SharePoint 2010 or SharePoint 2013 workflow platform type.</span></span>

- <span data-ttu-id="720c7-106">Tok je konfigurisan da pošaljete poruku prilagođene e-pošte za više od 200 korisnika po jedan, više od 10 000 primalaca dnevno ili više od 30 poruka u minuti.</span><span class="sxs-lookup"><span data-stu-id="720c7-106">The workflow is configured to send a custom email message to more than 200 users at a time, more than 10,000 recipients per day, or more than 30 messages per minute.</span></span>

<span data-ttu-id="720c7-107">Kada pokrenete tok posla, zar ne poslati poruku e-pošte i primetite poruku o grešci, unutrašnja Status je podešen da prikazuje prividne ili nije moguće poslati primaocu.</span><span class="sxs-lookup"><span data-stu-id="720c7-107">When you run the workflow, the email message isn't sent, and you notice the error message, Internal Status is set to Suspended or Unable to send to a recipient is displayed.</span></span>

<span data-ttu-id="720c7-108">Za više informacija, pogledajte sledeći [članak](https://support.office.com/article/-daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or-unable-to-send-to-a-recipient-error-in-a-sharepoint-online-workflow-89d02169-5fa6-4259-affc-73edb6ca9fb6?ui=en-US&amp;rs=en-US&amp;ad=US).</span><span class="sxs-lookup"><span data-stu-id="720c7-108">For more information, please refer to the following [article](https://support.office.com/article/-daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or-unable-to-send-to-a-recipient-error-in-a-sharepoint-online-workflow-89d02169-5fa6-4259-affc-73edb6ca9fb6?ui=en-US&amp;rs=en-US&amp;ad=US).</span></span>
