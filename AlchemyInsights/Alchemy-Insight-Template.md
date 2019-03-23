---
title: fel de nume de fişier este cel mai bun
ms.author: pebaum
author: pebaum
manager: jackiesm
ms.date: 4/27/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 5555
ms.assetid: (guid of old soc version if any)
ms.openlocfilehash: 68f743ee9c448565470815f8410cc6ce4b384bed
ms.sourcegitcommit: 0b6e9470c6b73616ba8bacef7010f739b7fac332
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 03/21/2019
ms.locfileid: "30742446"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a>Necesare alchimie antet H1, H2 pe nu funcţionează.
Cele mai bune practici și liniile directoare pentru authoring de Alchemy:

1. **Cuib alchimie intuiţii în dosare**- acest lucru va rupe structura de URL-ul. Suntem în căutarea în stabilirea acest lucru.
1. Fişierele din folderul **AlchemyInsights** trebuie să aibă minuscule de fişiere cu cratime pentru spaţiile ex. ***Cum-la spre-enable--litigiu***.
    1. Includ ID regula ID sau găleată din [alchimie partener portal](https://alchemyportal.azurewebsites.net) în domeniul ms.custom. ex. ***MS.Custom: 100021***
1. Utilizaţi restul de metadate în partea de sus a acestui fișier ca șablon.
1. În [alchimie partener portal](https://alchemyportal.azurewebsites.net), navigaţi în jos la secţiunea **titlu de carte de vizita clientului:** și care, ca începând cu un punct pentru H1 titlu pentru înţelegere. 
    > [!NOTE]
    > Alchimia intuiţii trebuie să aibă doar un singur H1 la partea de sus sau se va intrerupe în producţie. H2s nu face atât utilizarea **îndrăzneţ** sau alte convenții înseamnă secţiuni separate.
1. Apoi, completaţi în corpul textului folosind materiale de proiect în secţiunea clientului intuiţii a paginii de regulă de alchimie
    1. Liste cu marcatori sunt bine
    1. Liste numerotate prea
    1. **Bold** şi *cursive* sunt un-OK
    1. Link-uri ar trebui să fie întotdeauna **"link-uri la web" / extern** OR **adânc-link-uri la elemente de UI**, link-uri nu interne.
    1. Imaginile nu sunt suportate oficial în acest moment, dar este pe foaia de parcurs.

Şi acest lucru este într-adevăr deja un pic prea lung. Cele mai bune practici este de aproximativ 400 de caractere---

Odată ce conţinutul este gata, trageţi-l la sucursala live. Apoi, du-te la [portalului Partner de alchimie](https://alchemyportal.azurewebsites.net) şi introduceţi numele fişierului în câmpul URL-ul. M