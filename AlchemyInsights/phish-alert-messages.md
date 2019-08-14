---
title: 2491 upozorenja e-poruka od „Kasetama isporučena usled stanara ili korisnika da zameni” politike
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 2491
ms.assetid: ''
ms.openlocfilehash: 456b186ecea59422c791c79d4df056ad8446bc70
ms.sourcegitcommit: 7c90dcc570d32ebd968e3e4e816a7b482890b3a4
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/13/2019
ms.locfileid: "36391500"
---
# <a name="alert-email-messages-from-the-phish-delivered-due-to-tenant-or-user-override-policy"></a><span data-ttu-id="0cee4-102">Upozorenje o e-poruka od „Kasetama isporučena usled stanara ili korisnika da zameni” politike</span><span class="sxs-lookup"><span data-stu-id="0cee4-102">Alert email messages from the 'Phish Delivered due to tenant or user override' policy</span></span>

<span data-ttu-id="0cee4-103">Podrazumevani upozorenja politike koja se zove „Kasetama Delivered zbog stanara ili korisnika override” je bilo umotano stanarima sa Office 365 ATP P1 i P2 licence.</span><span class="sxs-lookup"><span data-stu-id="0cee4-103">A default alert policy named "Phish Delivered due to tenant or user override" has been rolled out to tenants with Office 365 ATP P1 and P2 licenses.</span></span> <span data-ttu-id="0cee4-104">Ako ste primili ovo obaveštenje, evo korake kako bi istražili:</span><span class="sxs-lookup"><span data-stu-id="0cee4-104">If you received this alert, here are the steps to investigate:</span></span>

1. <span data-ttu-id="0cee4-105">Iz poruka sa obaveštenjem, kliknite **Prikaz upozorenje** da idite na stranicu **upozorenja** u bezbednosti & usklađenosti centar.</span><span class="sxs-lookup"><span data-stu-id="0cee4-105">From the alert message, click **View Alert** to go to the **Alerts** page in the Security & Compliance Center.</span></span>

2. <span data-ttu-id="0cee4-106">Izaberite obaveštenje da vidite opciju za **prikaz liste poruka** ili **Prikaz poruka u Explorer**.</span><span class="sxs-lookup"><span data-stu-id="0cee4-106">Select the alert to see the option to **View message list** or **View messages in Explorer**.</span></span> <span data-ttu-id="0cee4-107">Obe ove opcije te odvesti na detalje poruke, koja uključuje ID poruke.</span><span class="sxs-lookup"><span data-stu-id="0cee4-107">Both of these options take you to the details of the message, which includes the Message ID.</span></span> <span data-ttu-id="0cee4-108">Imajte na umu da će na pretnju Explorer vezu automatski filtrirati poruke koje odgovara kriterijumima upozorenja.</span><span class="sxs-lookup"><span data-stu-id="0cee4-108">Note that the Threat Explorer link will automatically filter the messages that match the alert criteria.</span></span> <span data-ttu-id="0cee4-109">Možda ti treba da podesite filter datuma u opasnost Explorer.</span><span class="sxs-lookup"><span data-stu-id="0cee4-109">You might need to adjust the date filter in Threat Explorer.</span></span>

<span data-ttu-id="0cee4-110">Phishing poruka je isporučena zbog premostite ručno konfiguriran:</span><span class="sxs-lookup"><span data-stu-id="0cee4-110">The phishing message was delivered because of a manually configured override:</span></span>

- <span data-ttu-id="0cee4-111">Za dozvoljenih pošiljaoca ili domena postavljen od strane korisnika.</span><span class="sxs-lookup"><span data-stu-id="0cee4-111">An allowed sender or domain set by the user.</span></span>

- <span data-ttu-id="0cee4-112">Za dozvoljenih pošiljaoca ili domena postavio admin u smernice za borbu protiv neželjene pošte.</span><span class="sxs-lookup"><span data-stu-id="0cee4-112">An allowed sender or domain set by the admin in an anti-spam policy.</span></span>

- <span data-ttu-id="0cee4-113">Dozvoljenih IP adresu u smernicama za povezivanje filtera.</span><span class="sxs-lookup"><span data-stu-id="0cee4-113">An allowed IP address in a connection filter policy.</span></span>

- <span data-ttu-id="0cee4-114">Pošta protok pravilo (poznat i kao transportni pravilo) koji je konfigurisan da dozvoli poruke u.</span><span class="sxs-lookup"><span data-stu-id="0cee4-114">A mail flow rule (also known as a transport rule) that's configured to allow messages in.</span></span>

<span data-ttu-id="0cee4-115">Ako smatrate da je poruka bila pogrešno označene kao Cecu, koristite Outlook [poruku o izveštaju programski dodatak](https://support.office.com/article/b5caa9f1-cdf3-4443-af8c-ff724ea719d2) da prosledite poruku uzorke korporaciji Microsoft.</span><span class="sxs-lookup"><span data-stu-id="0cee4-115">If you believe the message was incorrectly marked as phish, use the Outlook [Report Message add-in](https://support.office.com/article/b5caa9f1-cdf3-4443-af8c-ff724ea719d2) to submit message samples to Microsoft.</span></span>
