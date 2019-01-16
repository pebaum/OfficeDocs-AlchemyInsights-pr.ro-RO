---
title: Eroare AttributeValueMustBeUnique
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: bf8ac830-6f0c-4616-827d-987616700e59
ms.openlocfilehash: 7a97d1a5ff352b55833bd457e3220a56130d7e7e
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 01/15/2019
ms.locfileid: "28307232"
---
# <a name="error-attributevaluemustbeunique"></a><span data-ttu-id="adfea-102">Eroare: AttributeValueMustBeUnique</span><span class="sxs-lookup"><span data-stu-id="adfea-102">Error: AttributeValueMustBeUnique</span></span>

<span data-ttu-id="adfea-p101">Cel mai frecvent motiv pentru erori de AttributeValueMustBeUnique este două obiecte cu diferite SourceAnchor (immutableId) au aceeaşi valoare pentru atributele ProxyAddresses şi/sau UserPrincipalName. Pentru a remedia eroarea AttributeValueMustBeUnique:</span><span class="sxs-lookup"><span data-stu-id="adfea-p101">The most common reason for the AttributeValueMustBeUnique error is two objects with different SourceAnchor (immutableId) have the same value for the ProxyAddresses and/or UserPrincipalName attributes. To fix the AttributeValueMustBeUnique error:</span></span>
  
1. <span data-ttu-id="adfea-p102">Identifica proxyAddresses duplicat, userPrincipalName sau altă valoare de atribut care provoacă eroarea. De asemenea, identifica care două (sau mai multe) obiecte sunt implicate în conflict. Raportul generat de sănătate Azure AD Connect pentru sincronizare vă pot ajuta să identifice două obiecte.</span><span class="sxs-lookup"><span data-stu-id="adfea-p102">Identify the duplicated proxyAddresses, userPrincipalName or other attribute value that's causing the error. Also identify which two (or more) objects are involved in the conflict. The report generated by Azure AD Connect Health for sync can help you identify the two objects.</span></span>
    
2. <span data-ttu-id="adfea-108">Identificarea obiectului care ar trebui să continue să aibă valoarea duplicat şi obiect care ar trebui să nu.</span><span class="sxs-lookup"><span data-stu-id="adfea-108">Identify which object should continue to have the duplicated value and which object should not.</span></span>
    
3. <span data-ttu-id="adfea-p103">Elimina valoarea duplicat la obiect pe care ar trebui să aibă această valoare. Reţineţi că ar trebui să facă schimbare în directorul în care obiectul este provin din. În unele cazuri, trebuie să ştergeţi unul dintre obiectele în conflict.</span><span class="sxs-lookup"><span data-stu-id="adfea-p103">Remove the duplicated value from the object that should NOT have that value. Note that you should make the change in the directory where the object is sourced from. In some cases, you may need to delete one of the objects in conflict.</span></span>
    
4. <span data-ttu-id="adfea-112">În cazul în care aţi făcut schimbarea în incinta pe AD, să Azure AD conecta sincronizare schimbarea de eroare pentru a obţine stabilite.</span><span class="sxs-lookup"><span data-stu-id="adfea-112">If you made the change in the on premises AD, let Azure AD Connect sync the change for the error to get fixed.</span></span>
    
