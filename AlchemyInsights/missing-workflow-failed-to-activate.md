---
title: Tok posla koji nedostaje nije uspeo da se aktivira
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: e46ae8c5-3d81-457e-8c77-f7c1cbe267c4
ms.openlocfilehash: 604dc770c5c14ded6a8de1cec9e311b03b69f094
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/14/2020
ms.locfileid: "47667100"
---
# <a name="missing-workflow-failed-to-activate"></a>Tok posla koji nedostaje nije uspeo da se aktivira

U Microsoft SharePoint kolekciji lokacija ne možete da dodate globalni tok posla koji se može ponovo koristiti (kao što je "odobravanje-SharePoint 2010") na listu ili u biblioteku.
  
Da biste rešili ovaj problem, slijedite ove korake: 
  
1. Otvorite osnovnu Veb lokaciju kolekcije lokacija u sistemu SharePoint Designer 2013.
  
2. U okviru **objekti portala**izaberite stavku **Tokovi posla**. 
  
3. U **novom** odeljku trake **tokova posla** izaberite stavku **tok posla**koji je moguće ponovo koristiti. 
  
4. Na obrascu **toka posla** koji je moguće ponovo koristiti unesite ime * * *Repair2010* * *. Za **tip platforme**izaberite stavke **SharePoint 2010 tokovi posla**, a zatim kliknite na dugme **u redu**. 
  
1. U odeljku **Čuvanje** trake **toka posla** izaberite stavku **Objavi**. 
  
2. U odeljku **Upravljanje** traci **toka posla** izaberite stavku objavi na **globalnom nivou**. U dijalogu za potvrdu koji se pojavi izaberite stavku **u redu**. 
  
3. U Veb pregledaču pronađite osnovnu Veb lokaciju kolekcije lokacija, a zatim Access **Site Settings** \> **funkcije kolekcije lokacija**za postavke lokacije. Zatim, preklopnik funkcije **tokova posla** : 
  
· Ako je funkcija  *aktivirana*  , kliknite na dugme **Deaktiviraj,** a zatim kliknite na dugme **Aktiviraj**. 
  
· Ako je funkcija  *deaktivirana*  , kliknite na dugme **Aktiviraj**. 
  
Više informacija potražite u sledećem [članku](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).
  

