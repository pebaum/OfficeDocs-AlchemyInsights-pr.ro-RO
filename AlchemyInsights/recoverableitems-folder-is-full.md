---
title: 1336 RecoverableItems folder este plin
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1336"
- "3700003"
ms.assetid: a3a923e8-fece-4a26-b8b6-00970d75275e
ms.openlocfilehash: 4f0cba480fcc05114abd8f370b84e9a37e5f2804
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 06/02/2020
ms.locfileid: "44510764"
---
# <a name="the-recoverable-items-folder-is-full"></a>Folderul Elemente recuperabile este plin

Pentru cutiile poștale Exchange Online, limita de stocare implicită pentru folderul Elemente recuperabile este de 30 GO. Limita de stocare pentru folderul Elemente recuperabile este mărită automat la 100 GO dacă cutia poștală este plasată în Contencios Hold, eDiscovery hold sau este atribuită unei politici de conservare.

Când folderul Elemente recuperabile atinge limita de stocare, funcționalitatea cutiei poștale este afectată în următoarele moduri:

- Utilizatorul nu poate șterge elemente din cutia poștală.

- Asistentul folder gestionat nu poate șterge elemente bazate pe eticheta de conservare sau pe setările folderului gestionat.

- Pentru cutiile poștale care au single element de recuperare activat sau sunt plasate în așteptare, procesul de copiere-pe-scrie pagina de protecție nu poate menține versiuni de elemente editate de utilizator.

- Pentru cutiile poștale care au cutie poștală audit înregistrarea în jurnal activat, nu intrările jurnal de audit cutie poștală pot fi salvate în subfolderul audituri în folderul Elemente recuperabile.

Pentru cutiile poștale care nu sunt în așteptare, administratorii pot utiliza `Search-Mailbox -SearchDumpsterOnly -DeleteContent` comanda în Exchange Online PowerShell pentru a șterge elemente în folderul Elemente recuperabile. Pentru informații suplimentare, consultați următoarele articole:

- [Căutarea și ștergerea mesajelor](https://docs.microsoft.com/microsoft-365/compliance/search-for-and-delete-messagesadmin-help)

- [Caută-Cutie poștală](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)

Pentru cutiile poștale care sunt în așteptare, administratorii trebuie să eliminați reținerea înainte de a putea șterge elemente din folderul Elemente recuperabile. Pentru mai multe informații, consultați [Ștergerea elementelor din folderul Elemente recuperabile din cutiile poștale din cadrul norului în așteptare](https://docs.microsoft.com/microsoft-365/compliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).

Pentru a preveni folderul Elemente recuperabile de a deveni plin, administratorii pot mări limita de stocare a folderului Elemente recuperabile pentru cutiile poștale în așteptare și configurați o politică de retenție cutie poștală care mută elemente din folderul Elemente recuperabile la cutia poștală de arhivă a utilizatorului. Consultați [Mărirea cotei elemente recuperabile pentru cutiile poștale în așteptare](https://docs.microsoft.com/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold).
