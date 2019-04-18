---
title: Identifica adresa IP şi client în jurnalele de auditare
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1367
ms.assetid: ''
ms.openlocfilehash: 7e30a638de5926aa11b8ae637613a48076d7bdc9
ms.sourcegitcommit: ffe2f489b1ac3aae62aa784c959da6a41c3261eb
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 04/17/2019
ms.locfileid: "31909483"
---
# <a name="identify-ip-address-and-client-in-audit-logs"></a>Identifica adresa IP şi client în jurnalele de auditare

IP-ul care corespunde unei activități de către un utilizator sau administrator este indicat în jurnalele de Audit. Informaţii client este, de asemenea, conectat. Aici sunt paşii pentru astfel de informaţii de identificare

1. Conectaţi-vă la [Centrul de conformitatea Office 365 securitate &](https://protection.office.com/)

2. Faceţi clic pe **Căutare şi ancheta** şi selectaţi **Căutare de jurnalul de Audit**.

   Dacă sunteţi interesat într-o activitate specifică, selectaţi-l din lista de **activităţi** . Dacă nu, toate activităţile vor fi returnate pentru utilizator selectat (setarea implicită).

   **Notă**: anumite activităţi să nu fie disponibilă în meniul de **activităţi** ; cu toate acestea, cei de audit elemente vor fi returnate dacă **Arată rezultate pentru toate acțiunile** este selectat (. lipsă aranjare).

3. Specificaţi numele de utilizator în câmpul **utilizatorilor** , selectaţi intervalul de date corespunzător pentru activitatea şi apoi faceţi clic pe **Căutare**.

În rezultate, puteţi vedea adresa IP pentru activitatea respectivă în panoul de rezultate. Selectaţi înregistrarea de audit pentru a vedea informaţii detaliate în fișă de **Detalii** (de exemplu, Client, utilizatorul care a efectuat acţiunea, etc.).

Pentru informaţii suplimentare, consultaţi [Găsirea adresei IP a computerului utilizat pentru a accesa un cont compromise](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).