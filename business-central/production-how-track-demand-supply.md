---
title: Rekja tengsl milli eftirspurnar og framboðs
description: Þetta efnisatriði útskýrir mismunandi leiðir til að rekja tengsl milli framboðs og eftirspurnar á borð við rakningu á tengdum vörum og meðhöndlun á óröktum einingum áætlanagerðar.
author: SorenGP
ms.topic: conceptual
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.form: '5830, 9101, 99000822, 99000855'
ms.date: 06/25/2021
ms.author: edupont
---
# <a name="track-relations-between-demand-and-supply" />Rekja tengsl milli eftirspurnar og framboðs

Frá hverju framboðs- eða eftirspurnarskjali í hinu svokallaða pöntunarneti, geturðu rakið pöntunareftirspurn (rakið magn), spá, standandi sölupöntun eða áætlunarfæribreytu (órakið magn) sem á við umrædda áætlunarlínu.

Áætlunarvinnublöðin bjóða einnig hjálplegar áætlunarupplýsingar um ópantaðar einingar, til að aðstoða skipuleggjandann við að búa til fullkomna framboðsáætlun. Frekari upplýsingar er að finna í [Óraktar áætlunareiningar](production-how-track-demand-supply.md#untracked-planning-elements).

## <a name="to-track-linked-items" />Rekja tengdar vörur
Pöntunarrakningin sýnir hvernig sölupantanir, framleiðslupantanir og innkaupapantanir tengjast aðalframleiðslupöntuninni í gegnum áætlanir og frátekningarkerfi.

Eftirfarandi lýsir hvernig rekja skal tengdar vörur í fastáætlunarpöntun. Skrefin eru svipuð fyrir allar aðrar tegundir af pöntunum, og frá áætlunarvinnublaðslínum.

1. Veldu ![Ljósapera sem opnar eiginleika Viðmótsleitar.](media/ui-search/search_small.png "Segðu mér hvað þú vilt gera") táknið, fara í **Fastáætluð framl.pöntun** og velja síðan viðkomandi tengil.
2. Viðeigandi fastáætluð framleiðslupöntun er opnuð úr listanum.
3. Á flýtiflipanum **Línur** skal velja aðgerðina **Aðgerðir**, og velja svo aðgerðina **Pöntunarrakning**.

Línurnar í glugganum **Pöntunarrakning** sýna fylgiskjölin sem tengjast gildandi framleiðslupöntunarlínunni.

## <a name="untracked-planning-elements" />Órakin áætlunaratriði
Síðan **Óraktar áætlunareiningar** opnast þegar þú velur **Órakið magn** reitinn í **Pantanaáætlun** glugginn. Það þjónar tvenns konar tilgangi:

1. Að geyma upplýsingar um órakið magn sem birtist þegar notandi flettir upp á síðunni Rakning pöntunar til að sjá órakið magn.
2. Að geyma viðvörunarboð sem birtast þegar notandi smellir á **Viðvörun** tákn á síðunni **Áætlunarvinnublað**.

Síðan inniheldur færslur sem standa fyrir órakið umframmagn í pöntunarrakningarkerfi. Þessar færslur eru stofnaðar við áætlunarkeyrslu og útskýra hvaðan órakta umframmagnið í rakningarlínunum kom. Þetta órakta umframmagn kom frá:

- Framleiðsluspá
- Standandi pantanir
- Magn í öryggisbirgðum
- Endurpöntunarmark
- Hámarksbirgðir
- Pöntunarmagn
- Hámarksmagn pöntunar
- Lágmarksmagn pöntunar
- Fjöldapanta
- Hömlur (% af lotustærð)

## <a name="see-also" />Sjá einnig
[Áætlun](production-planning.md)   
[Uppsetning framleiðslu](production-configure-production-processes.md)  
[Framleiðsla](production-manage-manufacturing.md)    
[Birgðir](inventory-manage-inventory.md)  
[Innkaup](purchasing-manage-purchasing.md)  
[Hönnunarupplýsingar: Frátekning, rakning og aðgerðarboð](design-details-reservation-order-tracking-and-action-messaging.md)  
[Hönnunarupplýsingar: framboðsáætlun](design-details-supply-planning.md)   
[Uppsetning bestu venja: Framboðsáætlun](setup-best-practices-supply-planning.md)  
[Vinna með [!INCLUDE[prod_short](includes/prod_short.md)]](ui-work-product.md)


[!INCLUDE[footer-include](includes/footer-banner.md)]
