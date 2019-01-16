---
title: Eroare trimitere e-mail blocat de SpamHaus
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 2/23/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: fa98ab4a-92eb-45e9-8d57-ad10fb123042
ms.openlocfilehash: a16c998d2f289ea2da52454819f6677c405381a1
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 01/15/2019
ms.locfileid: "28307393"
---
# <a name="error-sending-email-client-host-blocked-using-spamhaus"></a><span data-ttu-id="28b48-102">Eroare trimitere e-mail: clientul gazdă blocat folosind Spamhaus</span><span class="sxs-lookup"><span data-stu-id="28b48-102">Error sending email: Client host blocked using Spamhaus</span></span>

<span data-ttu-id="28b48-p101">IP-ul care a trimis mesajul este pe o listă de bloc, deţinut de [Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245). Motivele fiind blocate de Spamhaus includ conturi compromise, compromisă masini schimb o adresă IP publică și politici de furnizorul de servicii Internet (ISP). Remedierile posibile sunt:</span><span class="sxs-lookup"><span data-stu-id="28b48-p101">The IP address that sent the message is on a block list owned by [Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245). Reasons for being blocked by Spamhaus include compromised accounts, compromised machines sharing a public IP address, and Internet Service Provider (ISP) policies. Possible fixes are:</span></span>
  
- <span data-ttu-id="28b48-106">Pentru mesajele de intrare blocat la Office 365 în cazul în care aveţi de a controla sursa de server de e-mail, aveţi nevoie pentru a determina cauza şi de a elimina bloc din site-ul Spamhaus.</span><span class="sxs-lookup"><span data-stu-id="28b48-106">For blocked inbound messages to Office 365 where you control the source email server, you need to determine the cause and remove the block from the Spamhaus website.</span></span>
    
- <span data-ttu-id="28b48-p102">Blocat mesaje de intrare la Office 365 în cazul în care adresa de IP a sursei aparţine altcuiva, adresa proprietarului trebuie să scoateţi blocul Spamhaus pe site-ul. Dacă adresa IP este pe lista de bloc Politica (PBL), proprietarul poate atribui o altă adresă IP statică sau elimina adresa de PBL.</span><span class="sxs-lookup"><span data-stu-id="28b48-p102">For blocked inbound messages to Office 365 where the source IP address belongs to someone else, the address owner needs to remove the block from the Spamhaus website. If the IP address is on the Policy Block List (PBL), the owner can assign a different static IP address or remove the address from the PBL.</span></span>
    
- <span data-ttu-id="28b48-p103">Pentru mesajele de ieşire blocate din domeniul Office 365, puteţi primi această eroare în cazul în care mesajele sunt dirijate printr-un serviciu de 3rd party. Utilizaţi un instrument de căutare WHOIS pentru a găsi proprietarul de adrese IP blocate.</span><span class="sxs-lookup"><span data-stu-id="28b48-p103">For blocked outbound messages from your Office 365 domain, you can receive this error if the messages are routed through a 3rd party service. You can use a WHOIS lookup tool to find the blocked IP address owner.</span></span>
    
