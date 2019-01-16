---
title: Depanarea problemelor cu inscrierea dispozitive Android în Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: d0269461-20a8-4c9e-83b2-8fcf608dc0a5
ms.openlocfilehash: 2f4fc434128ebe7323f0b8c08aec3be82112bbda
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 01/15/2019
ms.locfileid: "28307804"
---
# <a name="troubleshoot-issues-with-enrolling-android-devices-in-microsoft-intune"></a>Depanarea problemelor cu inscrierea dispozitive Android în Microsoft Intune

Consultaţi resurse enumerate mai jos pentru a rezolva problema acum.
  
Unele probleme comune şi rezoluţie paşi:
  
 **Aparat nu criptate eroare în compania Portal:** Versiunile mai noi de Android, în special începând cu v7.0, cere o parola de startup pentru a vă asigura că dispozitivul este complet criptat. Soluţiile comune sunt pentru a activa un cod pin startup sau cripta complet dispozitivul. Revizuirea [acestui document](https://docs.microsoft.com/en-us/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) , pentru mai multe informaţii. 
  
 **Dispozitive nu verifica cu serviciul Intune sau afişa ca "Nesanatoase" în consola de administrare Intune:** Unele 4.4 Samsung şi 5,5 dispozitive pot verifica în service. Există 3 posibile soluţii la această problemă: 
  
1. Manual deschide aplicaţia Portal de compania Intune, care va iniţia automat o sincronizare dispozitiv.
    
2. Actualizați dispozitivul Android 6.0 sau mai mare.
    
3. Dezactivaţi Samsung Smart Manager la gestionarea Intune compania Portal. Revizuirea [acestui document](https://docs.microsoft.com/en-us/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) , pentru mai multe detalii despre aceste probleme şi rezoluţii. 
    
 **User a da un permis tip nevalid** sau **User nume nu a fost recunoscut eroarea:** utilizatorul trebuie să li se atribuie o licenţă Intune sau EMS. Examina aceste documente pentru a atribui o licenţă prin: centrul de administrare Office sau Azure portal. 
  
Resurse suplimentare pentru a rezolva problema:
  
1. Utilizaţi [Intune depanare Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) pentru a diagnostica şi rezolva comune eşecuri de înscriere. Revizuirea [acestui document](https://docs.microsoft.com/en-us/intune/help-desk-operators) , pentru mai multe detalii. 
    
2. Consultaţi [acest document](https://docs.microsoft.com/en-us/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) pentru o listă de erori comune care împiedică înscrierea şi rezoluţii pentru fiecare. 
    
3. [Aflaţi cum să înscrie dispozitive Android în Microsoft Intune](https://docs.microsoft.com/en-us/intune/android-enroll).
    
