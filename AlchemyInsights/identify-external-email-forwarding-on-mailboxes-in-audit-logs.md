---
title: Identificarea redirecționării externe a e-mailurilor în cutiile poștale în jurnalele de audit
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1369"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 592eb92e4b0fe0f9da2fa20bb93ffa4fbbb76662
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 06/02/2020
ms.locfileid: "44508964"
---
# <a name="identify-when-external-email-forwarding-is-configured-on-mailboxes"></a>Identificarea când este configurată redirecționarea e-mailurilor externe în cutiile poștale

Atunci când un utilizator Microsoft 365 configurează redirecționarea de e-mail extern pe o cutie poștală, activitatea este auditat ca parte a cmdletului **Set-Mailbox** . Puteți vedea activitatea utilizând căutarea jurnalului de audit în Centrul de securitate & conformitate.

1. Conectați-vă la Centrul de [conformitate Microsoft 365 Security &](https://protection.office.com/).

2. Accesați pagina **Search**  >  **de căutare în jurnalul De audit căutare.**

3. Selectați intervalul de date din câmpurile **Data de început** și data de **sfârșit.** Nu este necesar să specificați un nume de utilizator. Verificați că câmpul **Activități** este setat la **Afișare rezultate pentru toate activitățile**.

4. Faceți clic pe **Căutare**.

În rezultate, faceți clic pe **Filtrare rezultate** și tastați **Set-Mailbox** în caseta filtru activitate. Selectați o înregistrare de audit în rezultate. În flyout **detalii,** faceți clic pe **Mai multe informații**. Trebuie să analizați detaliile fiecărei înregistrări de audit pentru a determina dacă activitatea este legată de redirecționarea e-mailurilor.

- **ObjectId**: Valoarea alias a cutiei poștale care a fost modificată.

- **Parametri:** _RedirecționareSmtpAddress_ indică adresa de e-mail țintă.

- **UserId**: Utilizatorul care a configurat redirecționarea e-mail ului pe cutia poștală în câmpul **ObjectId.**

Pentru mai multe informații, consultați [Determinarea cine a configurat redirecționarea e-mailului pentru o cutie poștală](https://docs.microsoft.com/microsoft-365/compliance/auditing-troubleshooting-scenarios#determine-who-set-up-email-forwarding-for-a-mailbox).
