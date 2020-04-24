---
title: Configuration Manager uređaji nedostaju na portalu
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9001495"
- "4384"
ms.openlocfilehash: 7a11ad3c6970be2c52a7cf0696bd3810b9bd665a
ms.sourcegitcommit: 89ae9e8b36d1980f89f07b016fff0ec48f96b620
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/23/2020
ms.locfileid: "43790231"
---
# <a name="configuration-manager-devices-missing-in-the-portal"></a>Configuration Manager uređaji nedostaju na portalu

Da bi sinhronizacija uređaja funkcionisala, [obavezne internet krajnje tačke](https://docs.microsoft.com/configmgr/tenant-attach/device-sync-actions#internet-endpoints) moraju da budu dostupne a internog servera koji hostuje ulogu tačke za povezivanje sa ulogom. Da biste rešili problem sa sinhronizacijom uređaja pregledajte **CMGatewaySyncUploadWorker.log** koji se nalazi u tački za povezivanje sa ulogom.

Saznajte više u članku [Prilaganje zakupca u aplikaciju Microsoft Endpoint Manager](https://docs.microsoft.com/configmgr/tenant-attach/).
