---
title: Întârzieri în primirea alertelor SharePoint și OneDrive
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000118"
- "2642"
ms.openlocfilehash: fb7ab6e8139c46d89b1cae1ee0ab9b9a601c8b64
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 04/22/2020
ms.locfileid: "43742013"
---
# <a name="delays-in-receiving-sharepoint-and-onedrive-alerts"></a>Întârzieri în primirea alertelor SharePoint și OneDrive

- Mai întâi verificați folderul Nedorit sau spam din e-mail.
- Dacă **toate alertele din mai multe fișiere sau biblioteci sunt întârziate**, vizitați [tabloul de bord Sănătate serviciu](https://portal.office.com/adminportal/home?ref=/servicehealth) pentru a verifica orice recomandări/incidente care pot apărea cu SharePoint sau Exchange. Problema poate fi cu capacitatea de alertă SharePoint sau întârzieri în e-mailuri prin Exchange. De asemenea, rețineți dacă se livrează alt e-mail - dacă nu, problema este probabil cu întârzieri Exchange.
- Dacă **nu este livrată o avertizare individuală dintr-un anumit fișier sau bibliotecă,** încercați să o ștergeți și să o creați din nou. Consultați [Gestionarea, vizualizarea sau ștergerea alertelor SharePoint](https://support.microsoft.com/office/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2) pentru a recrea alerta.

> [!NOTE]
> - Alertele nu pot fi trimise către un grup de distribuire. Sunt acceptate numai grupurile Security și O365.
> - Nu aveți posibilitatea să particularizați șabloanele de e-mail de avertizare. Trebuie să utilizați Microsoft Flow sau SharePoint Designer Flux de lucru pentru a obține cele.
