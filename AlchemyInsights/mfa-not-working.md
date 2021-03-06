---
title: Probleme cu MFA
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.custom:
- "2417"
- "9000557"
ms.openlocfilehash: a415116b9ba437cb13426896119cd1b40d9ab491
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 11/15/2019
ms.locfileid: "37768849"
---
# <a name="issues-with-azure-mfa"></a>Probleme cu Azure MFA
Există câteva lucruri pentru a verifica dacă utilizatorii nu pot conecta utilizând autentificarea multi-factor (MFA)

1. Utilizatorul afectat poate fi blocat în Azure Active Directory portal. În acest caz, încercările de autentificare pentru acel utilizator specific vor fi refuzate automat. [Vă rugăm să urmați pașii din acest articol pentru a le debloca.](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#block-and-unblock-users)

2. Dacă deblocarea utilizatorului nu a ajutat sau utilizatorul nu este blocat, puteți încerca să reinițializați MFA pentru utilizator și vor trece prin procesul de înscriere din nou. [Vă rugăm să urmați pașii din acest articol.](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-userdevicesettings#require-users-to-provide-contact-methods-again)

Dacă aceasta este prima dată când ați activat MFA și utilizatorii nu pot să se autentifice la clienții non-browsere, ar fi Outlook, Skype, etc, poate ADAL (Active Directory Authentication Library) nu este activată pe abonamentul O365. În acest caz, va trebui să vă conectați la Exchange Online PowerShell și executați acest cmdlet:  *Set-OrganizationConfig-OAuth2ClientProfileEnabled: $True*