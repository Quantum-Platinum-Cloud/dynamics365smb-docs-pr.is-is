---
title: Hönnunarupplýsingar - áætlunartafla
description: Þetta efnisatriði veitir innsýn í hvað gerist þegar breyting á mynstri eftirspurnar eða framboðs krefst þess að þú reiknir út hvernig þú skipuleggur vöru.
author: SorenGP
ms.topic: conceptual
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: null
ms.date: 06/15/2021
ms.author: edupont
---
# <a name="design-details-planning-assignment-table" />Hönnunarupplýsingar: áætlunartafla
Allar vörur ættu að vera áætlaðar en aftur á móti er engin ástæða til að reikna áætlun fyrir vöru nema eftirspurnar- eða framboðsmynstur hafi breyst síðan áætlun var síðast reiknuð.  

Ef notandi hefur slegið inn nýja sölupöntun eða breytt pöntun sem fyrir er er ástæða til að endurreikna áætlunina. Aðrar ástæður eru m.a. breytingar á spá eða viðeigandi magn í öryggisbirgðum. Breyting á uppskrift með því að bæta við eða fjarlægja íhlut myndi líklega gefa til kynna breytingu, en aðeins fyrir hlut vöru.  

Fyrir margar staðsetningar fer úthlutunin fram á vörustigi hverrar samsetningar staðsetningar. Ef, til dæmis, sölupöntun hefur verið búin til á aðeins einum stað, úthlutar forritið vörunni á þeim tiltekna stað fyrir áætlanagerð.  

Ástæðan fyrir að velja vörur fyrir áætlun grundvallast á afköstum kerfisins. Ef engin breyting hefur orðið á framboðs- og eftirspurnarmynstri vörunnar leggur áætlanakerfið ekki til neinar ráðstafanir. Ef áætlun væri ekki úthlutað yrði kerfið að gera útreikninga fyrir allar vörur til að finna út hvernig á að áætla og það myndi ganga um of á kerfið.  

Taflan **Áætlunarmat** Fylgist með tilvikum eftirspurnar og framboðs og úthlutar viðeigandi vörum til að gera áætlun. Fylgst er með eftirfarandi tilvikum:  

* Ný sölupöntun, spá, íhlutur, innkaupapöntun, framleiðslupöntun, samsetningarpöntun eða flutningspöntun.  
* Breyting vöru, magns, staðsetningar, afbrigðis eða dagsetningu á sölupöntun, spá, íhlutur, innkaupapöntun, framleiðslupöntun, samsetningarpöntun eða flutningspöntun.  
* Afturköllun sölupöntunar , spá, íhlutur, innkaupapöntun, framleiðslupöntunar, samsetningarpöntunar eða flutningspöntunar.  
* Notkun á vöru annarri en áætlaðri.  
* Frálag annarra vara en áætlaðra.  
* Óáætlaðar breytingar á birgðum.  

Yfir þessar beinu tilfærslur á framboði/eftirspurn halda pöntunarrakningar- og aðgerðaboðakerfið áætlunarúthlutunartöflu og tilgreinir áætlunarástæðu sem aðgerðaboð.  

Eftirfarandi breytingar í aðalgögnum geta einnig valdið ójafnvægi í áætlanagerð:  

* Breyting á stöðu í vottað í framleiðsluuppskrift haus (fyrir öll atriði með því haus).  
* Eyddar línur (undireining).  
* Breyting á stöðu við vottað í leiðarhaus (fyrir öll atriði með því haus).  
* Breytingar á eftirfarandi birgðaspjaldsreitum.  
* Öryggisbirgðamagn eða öryggis afhendingartími.  
* Útreikn. afhendingartíma  
* Endurpöntunarmark.  
* Framleiðsluuppskrift nr. (og allar undireiningar gamalla uppskriftatilvísana).  
* Leiðarnr.  
* Endurpöntunarstefna.  

Í þessum tilvikum, nýr eiginleiki, Úthlutunarstjórnun Áætlunar, heldur töflunni og segir áætlanagerðarástæðu sem nettóbreyting.  

Eftirfarandi breytingar valda ekki úthlutun áætlanagerðar:  

* Dagbækur  
* Aðrar áætlunarfæribreytur á birgðaspjaldinu  

Við útreikning á MPS eða MRP, gilda eftirfarandi takmarkanir:  

* MPS: Áætlunarkerfið athugar hvort varan er með eftirspurnarspá eða sölupöntun. Ef ekki er varan ekki tekin með í áætluninni.  
* MRP: Ef áætlanakerfið greinir að verið sé að fylla á vöruna með MPS-áætlunarlínu eða MPS-framboðspötnun verður varan ekki höfð með í áætlun. Hins vegar verða allar eftirspurnir frá viðkomandi íhlutum innifaldar.  

## <a name="see-also" />Sjá einnig
[Hönnunarupplýsingar: Jöfnun eftirspurnar og framboðs](design-details-balancing-demand-and-supply.md)   
[Hönnunarupplýsingar: Meðhöndlun endurpöntunarstefna](design-details-handling-reordering-policies.md)   
[Hönnunarupplýsingar: Flutningur í áætlun](design-details-transfers-in-planning.md)   
[Hönnunarupplýsingar: áætlunarfæribreyta](design-details-planning-parameters.md)  


[!INCLUDE[footer-include](includes/footer-banner.md)]
