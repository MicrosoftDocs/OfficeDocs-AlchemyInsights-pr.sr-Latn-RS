---
title: Omogućavanje nadgledanja poštanskog sandučeta
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: 2bcfb7cc174cd58b21e1bb0c82f0d7cdb25e2fdd
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506968"
---
# <a name="enable-mailbox-auditing"></a>Omogućavanje nadgledanja poštanskog sandučeta

Da biste omogućili nadzor poštanskog sandučeta za jednog korisnika ili čitavu organizaciju, sledeće cmdlet se moraju pokretati iz udaljene ljuske napajanja:
  
 **Jedan korisnik**
  
Set-poštansko sanduče-identitet "Jane Dau"-AuditEnabled $true
  
 **Organizacija**
  
Preuzimanje-poštansko sanduče-veličina rezultata neograničenog-filter {RecipientTypeDetails-sa "Userpoštansko sanduče"} | Set-poštansko sanduče-AuditEnabled $true
  
[uči više](https://docs.microsoft.com/microsoft-365/compliance/enable-mailbox-auditing)
  

