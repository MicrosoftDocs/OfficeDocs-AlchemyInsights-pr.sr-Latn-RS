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
ms.openlocfilehash: 9a8d72a01ed35794fcab370b48bbb189663d3396
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/04/2019
ms.locfileid: "34718760"
---
# <a name="workflows-in-sharepoint"></a><span data-ttu-id="4d7f7-102">Tokovi posla u sistemu SharePoint</span><span class="sxs-lookup"><span data-stu-id="4d7f7-102">Workflows in SharePoint</span></span>

<p><span data-ttu-id="4d7f7-103">Ako SharePoint tokovi posla ne šaljete e-mailove, vaša organizacija naišao na Exchange Online pošiljaoca granice.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="4d7f7-103">If SharePoint workflows are not sending emails, your organization may have encountered the Exchange Online sender limits.&nbsp;</span></span></p> <p><span data-ttu-id="4d7f7-104">„Tok posla je obustavljen” poruka o pogrešci može pojaviti ako imate jednu od sledećih stavki:</span><span class="sxs-lookup"><span data-stu-id="4d7f7-104">'Workflow is Suspended' error message may occur if you have one of the following items:</span></span></p> <ul> <li><span data-ttu-id="4d7f7-105">Imate toka posla u SharePoint na mreži koja koristi SharePoint 2010 ili SharePoint 2013 toka posla platforma tip.</span><span class="sxs-lookup"><span data-stu-id="4d7f7-105">You have a workflow in SharePoint Online that's using the SharePoint 2010 or SharePoint 2013 workflow platform type.</span></span></li> <li><span data-ttu-id="4d7f7-106">Tok je konfigurisan da pošaljete poruku prilagođene e-pošte za više od 200 korisnika po jedan, više od 10 000 primalaca dnevno ili više od 30 poruka u minuti.</span><span class="sxs-lookup"><span data-stu-id="4d7f7-106">The workflow is configured to send a custom email message to more than 200 users at a time, more than 10,000 recipients per day, or more than 30 messages per minute.</span></span></li> <li><span data-ttu-id="4d7f7-107">Kada pokrenete tok posla, zar ne poslati poruku e-pošte i primetite poruku o grešci, <strong>Unutrašnja statusa postavljena na privremenoj</strong> ili <strong>nije moguće poslati primaocu</strong> prikazuje.</span><span class="sxs-lookup"><span data-stu-id="4d7f7-107">When you run the workflow, the email message isn't sent, and you notice the error message, <strong>Internal Status is set to Suspended</strong> or <strong>Unable to send to a recipient</strong> is displayed.</span></span></li> </ul> <p><span data-ttu-id="4d7f7-108">Za više informacija, pogledajte sledeći <a href="https://support.office.com/en-us/article/-daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or-unable-to-send-to-a-recipient-error-in-a-sharepoint-online-workflow-89d02169-5fa6-4259-affc-73edb6ca9fb6?ui=en-US&amp;rs=en-US&amp;ad=US">članak</a>.</span><span class="sxs-lookup"><span data-stu-id="4d7f7-108">For more information, please refer to the following <a href="https://support.office.com/en-us/article/-daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or-unable-to-send-to-a-recipient-error-in-a-sharepoint-online-workflow-89d02169-5fa6-4259-affc-73edb6ca9fb6?ui=en-US&amp;rs=en-US&amp;ad=US">article</a>.</span></span></p>

