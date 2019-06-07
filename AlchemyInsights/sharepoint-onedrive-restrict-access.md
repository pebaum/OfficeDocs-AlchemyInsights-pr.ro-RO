---
title: Restricţiona accesul în SharePoint sau OneDrive
ms.author: kirks
author: Techwriter40
ms.date: 8/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: 5101366ff65f477c19b9c7f2c0d7065cf88501b0
ms.sourcegitcommit: 241e21b6da226563bf70bdb1f5bad3d91c38cd2c
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 06/05/2019
ms.locfileid: "34735154"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a><span data-ttu-id="a414c-102">Restricţiona accesul în SharePoint sau OneDrive</span><span class="sxs-lookup"><span data-stu-id="a414c-102">Restrict access in SharePoint or OneDrive</span></span>

<span data-ttu-id="a414c-103">Există multe modalităţi de a restricţiona accesul la servicii de SharePoint Online/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="a414c-103">There are many ways to restrict access to SharePoint Online/OneDrive services.</span></span> <span data-ttu-id="a414c-104">Aceste diferite metode de restricţii de acces sunt prezentate mai jos.</span><span class="sxs-lookup"><span data-stu-id="a414c-104">These various access restriction methods are outlined below.</span></span> 

<span data-ttu-id="a414c-105">Permisiunea de restricţie</span><span class="sxs-lookup"><span data-stu-id="a414c-105">Permission Restriction</span></span>

<span data-ttu-id="a414c-106">În SharePoint Online şi OneDrive pentru afaceri, vom restricţiona accesul la elemente cum ar fi site-uri, fişiere şi foldere numai acorda acces la aceste grupuri/persoanele care ar trebui să aibă acces.</span><span class="sxs-lookup"><span data-stu-id="a414c-106">In SharePoint Online and OneDrive for Business, we restrict access to items like sites, files and folders by only granting access to those groups/individuals who should have access.</span></span>

[<span data-ttu-id="a414c-107">Personaliza permisiuni pentru o listă SharePoint sau biblioteca</span><span class="sxs-lookup"><span data-stu-id="a414c-107">Customize permissions for a SharePoint list or library</span></span>](https://support.office.com/en-us/article/Customize-permissions-for-a-SharePoint-list-or-library-02d770f3-59eb-4910-a608-5f84cc297782)

[<span data-ttu-id="a414c-108">Personaliza permisiunile de site-ul SharePoint</span><span class="sxs-lookup"><span data-stu-id="a414c-108">Customize SharePoint site permissions</span></span>](https://docs.microsoft.com/en-us/sharepoint/customize-sharepoint-site-permissions)

[<span data-ttu-id="a414c-109">Schimba permisiunile de pe un subfolder</span><span class="sxs-lookup"><span data-stu-id="a414c-109">Change the permissions on a subfolder</span></span>](https://support.office.com/en-us/article/Change-the-permissions-on-a-subfolder-5427BD7C-F20A-4F75-8CF2-5359DD45A1A6)

[<span data-ttu-id="a414c-110">Control acces la dispozitive negestionată</span><span class="sxs-lookup"><span data-stu-id="a414c-110">Control access from unmanaged devices</span></span>](https://docs.microsoft.com/en-us/sharepoint/control-access-from-unmanaged-devices)

<span data-ttu-id="a414c-111">Ca SharePoint sau administrator global în Office 365, puteţi bloca sau limita accesul la conținut SharePoint și OneDrive de la negestionată dispozitive (acele nu hibrid AD s-au alăturat sau compatibil în Intune).</span><span class="sxs-lookup"><span data-stu-id="a414c-111">As a SharePoint or global admin in Office 365, you can block or limit access to SharePoint and OneDrive content from unmanaged devices (those not hybrid AD joined or compliant in Intune).</span></span>

<span data-ttu-id="a414c-112">Restricţie de locaţie reţea</span><span class="sxs-lookup"><span data-stu-id="a414c-112">Network Location Restriction</span></span>

<span data-ttu-id="a414c-113">Ca un IT admin, puteţi controla accesul la resursele SharePoint și OneDrive bazat pe locațiile de rețea definită care aveţi încredere.</span><span class="sxs-lookup"><span data-stu-id="a414c-113">As an IT admin, you can control access to SharePoint and OneDrive resources based on defined network locations that you trust.</span></span> <span data-ttu-id="a414c-114">Acest lucru este, de asemenea, cunoscut sub numele politicii bazate pe locaţie.</span><span class="sxs-lookup"><span data-stu-id="a414c-114">This is also known as location-based policy.</span></span> <span data-ttu-id="a414c-115">Pentru mai multe informaţii, consultaţi [controlul accesului la SharePoint Online si OneDrive date bazate pe locaţie de reţea](https://docs.microsoft.com/en-us/sharepoint/control-access-based-on-network-location)</span><span class="sxs-lookup"><span data-stu-id="a414c-115">For more information, please see [Control access to SharePoint Online and OneDrive data based on network location](https://docs.microsoft.com/en-us/sharepoint/control-access-based-on-network-location)</span></span>

<span data-ttu-id="a414c-116">Restricţie de blocare site-ul</span><span class="sxs-lookup"><span data-stu-id="a414c-116">Site Lock Restriction</span></span> 

<span data-ttu-id="a414c-117">În SharePoint Online, aveţi posibilitatea de a bloca în jos o colecţie de site-ul, astfel incat nimeni nu are acces.</span><span class="sxs-lookup"><span data-stu-id="a414c-117">Within SharePoint Online you have the ability to lock down a site collection, so no one has access.</span></span> <span data-ttu-id="a414c-118">Acest câmp este setat prin intermediul PowerShell şi [SharePoint Online Management Shell](https://docs.microsoft.com/en-us/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps) utilizând proprietatea - LockState [Set-petre](https://docs.microsoft.com/en-us/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) .</span><span class="sxs-lookup"><span data-stu-id="a414c-118">This is set via PowerShell and the [SharePoint Online Management Shell](https://docs.microsoft.com/en-us/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps) using the [Set-SPOSite](https://docs.microsoft.com/en-us/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) -LockState property.</span></span>

<span data-ttu-id="a414c-119">Limita de utilizatori la crearea de site-uri sau subsite-uri</span><span class="sxs-lookup"><span data-stu-id="a414c-119">Restrict users from creating sites or subsites</span></span>

<span data-ttu-id="a414c-120">Ca SharePoint admin sau administrator global Office 365, puteti lasa utilizatorii crea şi administra propriile site-uri SharePoint, determina ce fel de site-uri pe care le poate crea, şi specificaţi locaţia de site-uri.</span><span class="sxs-lookup"><span data-stu-id="a414c-120">As a SharePoint admin or Office 365 global admin, you can let your users create and administer their own SharePoint sites, determine what kind of sites they can create, and specify the location of the sites.</span></span> <span data-ttu-id="a414c-121">Pentru mai multe informaţii, vă rugăm să consultaţi [Administreaza crearea de site-ul SharePoint Online](https://docs.microsoft.com/en-us/sharepoint/manage-site-creation)</span><span class="sxs-lookup"><span data-stu-id="a414c-121">For more information, please see [Manage site creation in SharePoint Online](https://docs.microsoft.com/en-us/sharepoint/manage-site-creation)</span></span>
