---
title: Introducere în SharePoint Online
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 7ae05f21-eb16-4d71-9e19-4f097eb100d2
ms.openlocfilehash: 285c580d69efb369fa6a60066165123e3c91b0a7
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 12/15/2019
ms.locfileid: "40051653"
---
# <a name="workflows-in-sharepoint"></a>Fluxuri de lucru în SharePoint

Dacă fluxurile de lucru SharePoint nu trimit e-mailuri, este posibil ca organizația să fi întâlnit limitele expeditorului Exchange Online.

Mesajul de eroare "flux de lucru este suspendat" poate apărea dacă aveți unul dintre următoarele elemente:

- Aveți un flux de lucru în SharePoint Online care utilizează tipul de platformă SharePoint 2010 sau SharePoint 2013 flux de lucru.

- Fluxul de lucru este configurat pentru a trimite un mesaj de e-mail personalizat la mai mult de 200 utilizatori la un moment dat, mai mult de 10.000 destinatari pe zi, sau mai mult de 30 de mesaje pe minut.

Când executați fluxul de lucru, mesajul de poștă electronică nu este trimis și observați mesajul de eroare, starea internă este setată la suspendat sau imposibil de trimis la un destinatar este afișat.

Pentru mai multe informații, vă rugăm să consultați următorul [articol](https://docs.microsoft.com/sharepoint/support/workflows/configured-workflow-fails-running).

