---
title: Regulă DLP pentru numărul de cont bancar din SUA care nu funcționează
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1287"
- "3200001"
ms.assetid: 80b40145-8376-4c3a-8d22-6efb9f9cb271
ms.openlocfilehash: b032a7c80e8b387114aeda95c4f6af7e57225517
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 06/02/2020
ms.locfileid: "44507346"
---
# <a name="dlp-issues-with-us-bank-account-numbers"></a>Dlp probleme cu sua numere de cont bancar

**Important**: în timpul acestor vremuri fără precedent, vom lua măsuri pentru a ne asigura că serviciile SharePoint Online și OneDrive rămân extrem de disponibile. Vizitați [Ajustări temporare de caracteristici SharePoint Online](https://aka.ms/ODSPAdjustments) pentru mai multe informații.

**Dlp probleme cu sua numere de cont bancar**

Aveți probleme cu **Data Loss Prevention (DLP)** nu funcționează pentru conținut care conține un număr de cont bancar din **SUA** atunci când utilizați un tip de informații sensibile DLP în O365? Dacă da, asigurați-vă că conținutul conține informațiile necesare pentru ceea ce politica DLP caută atunci când este evaluat.
  
De exemplu, pentru o politică **de număr de cont bancar din SUA** configuratcu un nivel de încredere de 85%, sunt evaluate următoarele și trebuie să fie detectate pentru regula pentru a declanșa:
  
- **[Format:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#format-77)** 8-17 cifre

- **[Model:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#pattern-77)** 8-17 cifre consecutive.

- **[Suma de control:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#checksum-76)** Nu, nu există nici un Checksum

- **[Definiție:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)** O politică DLP este 75% încrezător că este detectat acest tip de informații sensibile în cazul în care, într-o apropiere de 300 de caractere:

  - Expresia regulată Regex_usa_bank_account_number găsește conținut care se potrivește cu modelul

  - Se găsește un cuvânt cheie din Keyword_usa_Bank_Account.

    De exemplu, următorul eșantion ar declanșa pentru politica **de număr de cont bancar din SUA:** Verificarea contului 78344011

Pentru mai multe informații despre ceea ce este necesar pentru un **număr de cont bancar din SUA** pentru a fi detectat pentru conținutul dvs., consultați următoarea secțiune din acest articol: Ce caută tipurile de informații [sensibile numărul de cont bancar din SUA](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#us-bank-account-number)
  
Utilizând un alt tip de informații sensibile încorporat, consultați următorul articol pentru informații despre ce este necesar pentru alte tipuri: [Ce caută tipurile de informații sensibile](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)
  