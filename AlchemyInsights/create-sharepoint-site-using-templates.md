---
title: Creaţi un site SharePoint Online
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 84f2b70e-2b23-4039-8305-85783798feed
ms.openlocfilehash: 2097933dd20f326a7bda2151596d514c37d566ff
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 06/04/2019
ms.locfileid: "34717778"
---
# <a name="create-sharepoint-sites-using-templates"></a><span data-ttu-id="8d305-102">Creare site-uri SharePoint folosind template-uri</span><span class="sxs-lookup"><span data-stu-id="8d305-102">Create SharePoint sites using templates</span></span>

<span data-ttu-id="8d305-103">Șabloanele de site SharePoint sunt precompilate definiţii concepute în jurul o afacere special nevoie.</span><span class="sxs-lookup"><span data-stu-id="8d305-103">SharePoint site templates are prebuilt definitions designed around a particular business need.</span></span> <span data-ttu-id="8d305-104">Pentru informaţii suplimentare, consultaţi <a href="https://support.office.com/en-us/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4">folosind template-uri pentru a crea diferite tipuri de site-uri SharePoint.</a></span></span><span class="sxs-lookup"><span data-stu-id="8d305-104">For more information, see <a href="https://support.office.com/en-us/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4">Using templates to create different kinds of SharePoint sites.</a></span></span></span></p> <p><span data-ttu-id="8d305-105"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Aici sunt unele probleme/solutii comune cu privire la salvarea un site-ul sau lista ca şablon în Sharepoint Online.</span></span><span class="sxs-lookup"><span data-stu-id="8d305-105"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Here are some common issues/solutions regarding Saving a Site or List as a template in Sharepoint Online. </span></span></span></p> <p><span data-ttu-id="8d305-106"><strong style="mso-bidi-font-weight: normal;"><u><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Salva/lista de site-ul şablon buton nu este disponibil sau lipsă.</span></u></strong></span><span class="sxs-lookup"><span data-stu-id="8d305-106"><strong style="mso-bidi-font-weight: normal;"><u><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Save site/list template button is not available or missing. </span></u></strong></span></span></p> <ul> <li><span data-ttu-id="8d305-107"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Administratorii va trebui să permite script-ul personalizat pentru a activa caracteristicile şablon. Pentru măsurile detaliate, exemple şi consideraţii </span> </span> <a style="orphans: 2; -webkit-text-stroke-width: 0px; word-spacing: 0px;" href="https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script">permite sau împiedică script-ul personalizat</a>.</span><span class="sxs-lookup"><span data-stu-id="8d305-107"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Administrators will need to Allow Custom Script to enable the template features. For detailed steps, examples and considerations see </span></span><a style="orphans: 2; -webkit-text-stroke-width: 0px; word-spacing: 0px;" href="https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script">Allow or prevent custom script</a>.</span></span></li> <li><span data-ttu-id="8d305-108"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Site-ul salvaţi ca şablon de comandă nu este acceptată şi pot provoca probleme de pe site-urile care folosesc infrastructura de publicare SharePoint Server.</span></span><span class="sxs-lookup"><span data-stu-id="8d305-108"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">The Save site as template command is not supported and can cause problems on sites that use the SharePoint Server Publishing Infrastructure. </span></span></span></li> </ul> <p><span data-ttu-id="8d305-109"><strong style="mso-bidi-font-weight: normal;"><u><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Șablonul de site-ul nu poate fi creat sau nu funcţionează corect</span></u></strong></span><span class="sxs-lookup"><span data-stu-id="8d305-109"><strong style="mso-bidi-font-weight: normal;"><u><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">The site template cannot be created or does not work correctly</span></u></strong></span></span></p> <ul> <li><span data-ttu-id="8d305-110"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Şablonul poate fi lipsesc o <a href="https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx">caracteristică</a> şi a câştigat&rsquo;t activate. Dacă funcţia nu este disponibilă pentru a activa în colecția de site-ul curent, se poate utiliza site-ul şablon pentru a crea un site.</span></span><span class="sxs-lookup"><span data-stu-id="8d305-110"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">The template may be missing a <a href="https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx">feature</a> and won&rsquo;t activate. If the feature is not available to activate in the current site collection, you cannot use the site template to create a site.</span></span></span></li> <li><span data-ttu-id="8d305-111"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Verificaţi pentru a vedea dacă orice liste sau biblioteci depăşi elementele <a href="https://support.office.com/en-us/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59">Prag limită de vizualizare listă de</a> 5000, acest lucru poate bloca crearea unui şablon de site-ul.</span></span><span class="sxs-lookup"><span data-stu-id="8d305-111"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Check to see if any lists or libraries exceed the <a href="https://support.office.com/en-us/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59">List View Limit Threshold of</a> 5000 items as this can block creation of a site template.</span></span></span></li> <li><span data-ttu-id="8d305-112"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Site-ul poate folosi prea multe resurse si, prin urmare, site-ul şablon depășește limita de 50 MB.</span></span><span class="sxs-lookup"><span data-stu-id="8d305-112"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">The site may be using too many resources and therefore the site template exceeds the 50 MB limit.</span></span></span></li> <li>
<span data-ttu-id="8d305-113">Există probleme afişarea datelor dintr-o listă care utilizează o coloană de căutare.</span><span class="sxs-lookup"><span data-stu-id="8d305-113">There are problems displaying data from a list that uses a lookup column.</span></span> <span data-ttu-id="8d305-114">Pentru informaţii suplimentare, consultaţi </span> <span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;"> <a style="box-sizing: border-box; -webkit-text-stroke-width: 0px; word-spacing: 0px;" href="https://support.office.com/en-us/article/template-generated-list-doesn-t-display-correct-data-for-a-column-in-sharepoint-online-20430b62-e40c-4f6f-8889-aa24e80d605a"> <span style="color: #0067b8; text-decoration: none; text-underline: none;">generate de şablon lista&rsquo;t afişarea datelor din lista de căutare corectă în SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="8d305-114">For more information, see </span><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;"><a style="box-sizing: border-box; -webkit-text-stroke-width: 0px; word-spacing: 0px;" href="https://support.office.com/en-us/article/template-generated-list-doesn-t-display-correct-data-for-a-column-in-sharepoint-online-20430b62-e40c-4f6f-8889-aa24e80d605a"><span style="color: #0067b8; text-decoration: none; text-underline: none;">Template-generated list doesn&rsquo;t display data from the correct lookup list in SharePoint Online.</span></span>

<span data-ttu-id="8d305-115">Pentru mai multe informaţii pe probleme comune şi soluţii detaliate, vă rugăm să verificaţi <a href="https://support.office.com/en-us/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989">crearea şi utilizarea site-ul template-uri.</span><span class="sxs-lookup"><span data-stu-id="8d305-115">For more detailed information on common problems and solutions, please check <a href="https://support.office.com/en-us/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989">Create and use site templates.</span></span>


