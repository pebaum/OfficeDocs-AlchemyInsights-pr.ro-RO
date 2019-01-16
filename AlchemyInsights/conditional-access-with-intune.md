---
title: Acces condiţionat cu Intune
ms.author: pebaum
author: pebaum
ms.date: 10/11/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: aecba7c5-e86d-4ec8-9d44-679f5a3d659d
ms.openlocfilehash: 59f1aefaeec3d655b2388b00e7d58a8c2338504b
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 01/15/2019
ms.locfileid: "28306655"
---
# <a name="conditional-access-with-intune"></a><span data-ttu-id="0a3fe-102">Acces condiţionat cu Intune</span><span class="sxs-lookup"><span data-stu-id="0a3fe-102">Conditional Access with Intune</span></span>

<span data-ttu-id="0a3fe-103">Folosind **Accesul condiționat** cu Intune necesită 3 pasi:</span><span class="sxs-lookup"><span data-stu-id="0a3fe-103">Using **Conditional Access** with Intune requires 3 steps:</span></span> 
  
- <span data-ttu-id="0a3fe-p101">Creaţi o **Politica de acces condiționat** , care defineşte ce resurse sunt protejata, şi ce condiţii trebuie să fie îndeplinite pentru a accesa aceste resurse. De exemplu, un aparat trebuie să fie compatibile cu înainte de a accesa e-mail corporative.</span><span class="sxs-lookup"><span data-stu-id="0a3fe-p101">Create a **Conditional Access Policy** that defines what resources are being protected, and what conditions need to be met to access those resources. For example, a device must be compliant before accessing corporate email.</span></span> 
    
- <span data-ttu-id="0a3fe-p102">Creaţi o **Politică de conformitate** pentru a defini setările care trebuie îndeplinite înainte ca dispozitivul este considerat compatibil cu. De exemplu, un aparat trebuie să aibă un ac de cel puţin 6 cifre înainte se consideră conforme.</span><span class="sxs-lookup"><span data-stu-id="0a3fe-p102">Create a **Compliance Policy** to define settings that must be met before the device is considered compliant. For example, a device must have a pin of at least 6 digits before it is considered compliant.</span></span> 
    
- <span data-ttu-id="0a3fe-p103">Asigura **Respectarea politicilor** şi de **Politici de acces condiționat** sunt direcţionate către grupuri dorit de utilizatori. Acest lucru poate necesita crearea grupuri specifice de utilizatori în Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="0a3fe-p103">Ensuring both **Compliance Policies** and **Conditional Access Policies** are targeted to the desired groups of users. This may require creating specific groups of users in Azure Active Directory.</span></span> 
    
<span data-ttu-id="0a3fe-110">Citeşte mai mult:</span><span class="sxs-lookup"><span data-stu-id="0a3fe-110">Read more:</span></span>
  
- [<span data-ttu-id="0a3fe-111">Condiţionată de acces cele mai bune practici</span><span class="sxs-lookup"><span data-stu-id="0a3fe-111">Conditional Access best practices</span></span>](https://docs.microsoft.com/en-us/azure/active-directory/conditional-access/best-practices)
    
- [<span data-ttu-id="0a3fe-112">Noţiuni de bază cu acces condiționat</span><span class="sxs-lookup"><span data-stu-id="0a3fe-112">Getting started with Conditional Access </span></span>](https://docs.microsoft.com/en-us/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    
