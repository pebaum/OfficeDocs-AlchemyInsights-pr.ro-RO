---
title: 2681 Attack Simulator în Microsoft 365
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "2681"
ms.assetid: ''
ms.openlocfilehash: 3dae4768ca62757ce7f92dfc527078c963d72742
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506750"
---
# <a name="attack-simulator-in-microsoft-365"></a>Attack Simulator în Microsoft 365

- Îți lipsește Simulatorul de atac? Attack Simulator necesită **Office 365 Advanced Threat Protection Plan 2 (ATP Plan 2)** sau **Office 365 Enterprise E5**. Attack Simulator **nu** este inclus în Office 365 Advanced Threat Protection Plan 1 (ATP Plan 1), Office 365 Enterprise E3 sau orice Microsoft 365 Apps for business abonamente.

- Contul pe care îl utilizați pentru a lansa atacuri simulate necesită permisiuni de administrator global sau de administrator de securitate și autentificare multi-factor (MAE). Pentru mai multe informații despre cerințele Attack Simulator, consultați [acest subiect](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).

- Lucruri importante de știut despre simulările de atac **brute force password:**

  - Dacă contul țintă are AMF activat și parola a fost ghicit corect, contul nu se va afișa ca compromis (al doilea factor de autentificare va fi incomplet).

  - Fișierul parolă nu poate fi mai mare de 10 MO. Utilizați o parolă pe linie și includeți o linie necompletată (retur de transport) după ultima parolă din listă.

- Lucruri importante de știut despre simulările de **atașare a sperei phishing:**

  - După proiectare, nu puteți furniza o valoare particularizată pentru **URL-ul serverului de conectare phishing**.

  - Dacă un destinatar utilizează [programul de completare Activare mesaj raport](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in) pentru a raporta mesajul ca phishing, este posibil să nu primiți alerte pentru mesaj (deoarece acesta este un atac simulat).

- Rapoarte: După terminarea atacului simulat, puteți face clic pe **Detalii atac** pentru a vedea raportul.

- Pentru instrucțiuni detaliate și caracteristici noi în Attack Simulator, consultați [Attack Simulator în Microsoft 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).
