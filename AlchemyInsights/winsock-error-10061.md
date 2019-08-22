---
title: 1554 Winsock greška 10061
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 12/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1554"
- "9000079"
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: f54c7fc81c274871fbc22908ce0fb21500975d9e
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36530819"
---
# <a name="winsock-error-10061"></a><span data-ttu-id="bfcce-102">Winsock greška 10061</span><span class="sxs-lookup"><span data-stu-id="bfcce-102">Winsock error 10061</span></span>

<span data-ttu-id="bfcce-103">Ovaj kôd greške znači da Office 365 nije mogao da uspostavi TCP priključak (veza) sa meta domaćin.</span><span class="sxs-lookup"><span data-stu-id="bfcce-103">This error code means that Office 365 couldn't establish a TCP socket (connection) with the target host.</span></span> <span data-ttu-id="bfcce-104">Najverovatniji uzrok ove greške je problem u konfiguraciji vatrozida.</span><span class="sxs-lookup"><span data-stu-id="bfcce-104">The most likely cause of this error is a problem with your firewall configuration.</span></span> <span data-ttu-id="bfcce-105">Da biste rešili problem, pogledajte ove postavke:</span><span class="sxs-lookup"><span data-stu-id="bfcce-105">To fix the problem, check these settings:</span></span>

- <span data-ttu-id="bfcce-106">Proverite konfiguraciju zaštitnog zida sa informacijama u [Office 365 URL adrese i opsega IP adresa](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)</span><span class="sxs-lookup"><span data-stu-id="bfcce-106">Verify your firewall configuration with the information in [Office 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)</span></span>

- <span data-ttu-id="bfcce-107">Ako greška je specifična za Exchange Online zaštitu (EOP), trebalo bi da ste prethodno obavešteni do promene na [Exchange Online zaštitu IP adrese](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span><span class="sxs-lookup"><span data-stu-id="bfcce-107">If the error is specific to Exchange Online Protection (EOP), you should have been previously notified to a change to the [Exchange Online Protection IP addresses](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>

- <span data-ttu-id="bfcce-108">Uverite se da je tvoj dobavljač Internet usluga (ISP) ne blokira port.</span><span class="sxs-lookup"><span data-stu-id="bfcce-108">Verify that your Internet Service Provider (ISP) isn't blocking the port.</span></span>

- <span data-ttu-id="bfcce-109">Provjerite pametan hosta i ciljnih postavke servera u tvoj konektori.</span><span class="sxs-lookup"><span data-stu-id="bfcce-109">Verify the smart host and target server settings in your connectors.</span></span>

<span data-ttu-id="bfcce-110">Imajte na umu da Office 365 ne blokira *dolazne* veze na ovaj način.</span><span class="sxs-lookup"><span data-stu-id="bfcce-110">Note that Office 365 doesn't block *incoming* connections in this manner.</span></span>
