---
title: Tryggja eignir
description: Þú getur úthlutað einni eða fleirum eignum á eitt tryggingaskírteini með því að bóka í fjárhagsbók vátryggingar af síðunni **Vátryggingabók**.
author: edupont04
ms.topic: conceptual
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 'policy, coverage'
ms.search.form: '5647, 5644, 5653, 5651, 5655, 5652, 5645, 5656, 5646, 5648, 9275'
ms.date: 06/29/2021
ms.author: edupont
---
# <a name="insure-fixed-assets" />Tryggja eignir
Vátryggingarskírteini fyrir eign er sýnt með vátryggingarspjaldi. Hægt er að úthluta einni eign á eina vátryggingarskírteini eða margar eignir á eitt vátryggingarskírteini.

Þú úthlutar eign á vátryggingarskírteini með því að bóka í vátryggingasviðsbók á síðunni **Vátryggingabók** .

Þar að auki er hægt að úthluta eign á vátryggingarskírteini og stofna vátryggingasviðsfærslur þegar þú bókar kaupverð hennar. Þú gerir þetta með því að bóka kaupverð úr eignabók með útfylltum reitnum **vátryggingarnúmer**. **Sjálfvirk Vátryggingarbókun** gátreiturinn á síðunni **Uppsetning eigna** þarf að vera valinn. Nánari upplýsingar eru í [Bókun eignakaupa handvirkt með fjárhagsbók eigna](fa-how-acquire.md#to-post-a-fixed-asset-acquisition-manually-with-the-fixed-asset-gl-journal).

Ef **Sjálfvirk Vátryggingarbókun** gátreiturinn á **uppsetning eigna** síðunni er ekki valinn, þá mun bókun eignakaupa úr eignabók stofna línur á síðunni **Vátryggingabók** sem síðan verður að bóka handvirkt.

> [!WARNING]  
>   Ef þú velur ekki **Sjálfvirk vátryggingarbókun** gátreitinn í **Uppsetning eigna** síðunni, þá ætti vátryggingabókin þín að vera byggð á færslubókarsniðmáti án númeraröð. Þetta er af því að innsett fylgiskjalsnúmerum úr eignabókarlínum munu annars skarast við númeraröðina í vátryggingabók. Nánari upplýsingar um sniðmát færslubókar og keyrsla sjá [Setja upp almennar upplýsingar um eignir](fa-how-setup-general.md).

Þegar eign hefur verið úthlutað á vátryggingarskírteini, er valinn gátreitur **Tryggt** á eignaspjaldi. Þegar þú selur eignina, er sjálfkrafa hakað úr gátreitnum.

## <a name="to-create-or-modify-an-insurance-card" />Stofna eða Breyting á vátryggingaspjöldum:
Vátryggingarskírteini fyrir eign verður að vera sýnt með vátryggingarspjaldi.

Þegar upplýsingar um breytingar á tryggingarupphæð berast verður að færa nýju upplýsingarnar inn á síðuna **Vátryggingarspjald** til að tryggja að greining vátryggingasviðs sé rétt.  

1. Veldu ![Ljósapera sem opnar eiginleika Viðmótsleitar.](media/ui-search/search_small.png "Segðu mér hvað þú vilt gera") táknið, fara í **Trygging** og velja síðan viðkomandi tengil.
2. Veljið aðgerðina **Nýtt** til að Búa til nýtt kort fyrir vátryggingarskírteini. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. Einnig geturðu valið vátryggingarskírteini sem þú vilt breyta og veldu svo aðgerðina **Breyta**.

## <a name="to-assign-a-fixed-asset-to-an-insurance-policy-by-posting-from-the-insurance-journal" />Til að Tengja eign við vátryggingarskírteini með því að bóka úr vátryggingabók.
Þú úthlutar eign á vátryggingarskírteini með því að bóka í vátryggingasviðsbók.  

Eftirfarandi ferli útskýrir hvernig stofna vátryggingarbókarlínu handvirkt. Ef **Sjálfvirk Vátryggingarbókun** gátreitinn er valinn á síðunni **uppsetning eigna** þá eru línur í vátryggingabók sjálfkrafa stofnaðar þegar kaupverð er bókað. Í því tilfelli er allt sem þarf að gera er að bóka færslubókina.  

1. Veldu ![Ljósapera sem opnar eiginleika Viðmótsleitar.](media/ui-search/search_small.png "Segðu mér hvað þú vilt gera") í reitnum Leit skal færa inn **Vátryggingabók** og velja síðan viðkomandi tengil.  
2. Opna skal viðeigandi færslubók og fylla færslubókarlínurnar út eftir þörfum.  
3. Til að úthluta mörgum eignum á eina vátryggingarskírteini, skal stofna færslubókarlínur með sömu gildum og í **Vátryggingarnr.** reitnum og öðrum gildum í **Eignanr.** reitnum.  
4. Valið er **Bóka** aðgerðin.  

    > [!NOTE]  
    >   Færslurnar í vátryggingabók eru aðeins bókaðir í vátryggingasviðshöfuðbókina.  

## <a name="to-update-the-insurance-value-of-a-fixed-asset" />Uppfæra tryggingarvirði eignar
Í eftirfarandi dæmi er sýnt hvernig hægt er að nota keyrsluna **Endurmat vátrygginga** til að uppfæra verðmæti eigna sem eru tryggðar.  

1. Veldu ![Ljósapera sem opnar eiginleika Viðmótsleitar.](media/ui-search/search_small.png "Segðu mér hvað þú vilt gera") táknið, fara í **Endurmat vátryggingar** og velja síðan viðkomandi tengil.
2. Fyllið inn í reitina eftir þörfum.

    > [!NOTE]  
    >   Í reitnum **Vísitala** skráir þú lækkun uppá 5%, til dæmis, sem 95, en þú skráir aukningu uppá 2% sem 102.  
3. Velja hnappinn **Í lagi**.  

   Keyrslan reiknar þessa nýju tölu sem hlutfall af vátryggðu heildarvirði eins og kemur fram á síðunni **Vátryggingaupplýsingar** og býr til línu í vátryggingabókinni.  
4. Veldu ![Ljósapera sem opnar eiginleika Viðmótsleitar.](media/ui-search/search_small.png "Segðu mér hvað þú vilt gera") í reitnum Leit skal færa inn **Vátryggingabók** og velja síðan viðkomandi tengil.  
5. Opnaðu viðeigandi Vátryggingabók, endurskoðaðu stofnuð gildi og bókaðu þau síðan í vátryggingasviðshöfuðbókina.  

## <a name="to-monitor-insurance-coverage" />Eftirlit með vátryggingasviði
[!INCLUDE[prod_short](includes/prod_short.md)] veitir sérhæfðar skýrslu- og tölfræðisíður til að greina vátryggingarskilmála, og hvort eignir þínar eru oftryggðar eða vantryggðar.  

### <a name="overview-of-insurance-policies" />Yfirlit yfir vátryggingaskírteini
Til að fá yfirlit yfir vátryggingarskilmála þína skaltu forskoða eða prenta **Vátrygging - Listi** skýrsluna. Skýrslan sýnir alla skilmálana og mikilvægustu reitina af vátryggingarspjöldunum.  

### <a name="insurance-coverage" />Vátryggingasvið
Ef skoða á hvaða eignir eru vátryggðar eða hvaða vátryggingar gilda fyrir hverja eign er hægt að prenta eða forskoða skýrsluna **Vátrygging - Tryggt heildarv.**.  

### <a name="overunder-coverage" />Of-/Vantrygging
Hægt er að athuga hvort eignir eru oftryggðar eða vantryggðar á eftirfarandi hátt:  

* Síðan **Vátryggingaupplýsingar**. Plústala í reitnum **Yfir-/undirtryggt** merkir að eignin sé yfirtryggð. Mínustala merkir að hún sé undirtryggð.  
* Síðan **Eignaupplýsingar** . Veldu reitinn **Vátryggt heildarvirði** til að skoða síðuna **Vátryggingasviðsfærslur**.  
* **Yfir-/undir Vátryggingasvið** skýrslu.  
* **Tryggingagreining** skýrslan  

### <a name="uninsured-fixed-assets" />Ótryggðar eignir
Ef ganga á úr skugga um hvort gleymst hafi að tengja eign við vátryggingu er hægt að prenta eða forskoða skýrsluna **Vátrygging - Ótryggðar eignir**. Þessi skýrsla sýnir eignir með upphæðir sem hafa ekki verið bókaðar á vátryggingasviðsbókina.  

## <a name="to-view-insurance-coverage-ledger-entries" />Skoðun vátryggingasviðsfærslna:
Hægt er að skoða færslurnar sem færðar hafa verið í vátryggingasviðsbókina.  

1. Veldu ![Ljósapera sem opnar eiginleika Viðmótsleitar.](media/ui-search/search_small.png "Segðu mér hvað þú vilt gera") táknið, fara í **Trygging** og velja síðan viðkomandi tengil.  
2. Valin er viðeigandi vátryggingarskírteini og veldu svo **vátryggingasviðsfærslur** aðgerðina.  

## <a name="to-view-the-total-insurance-value-of-fixed-assets" />Skoðun á vátryggðu heildarvirði eigna:
Sérhæfð fylkissíða sýnir upphæð skráðrar tryggingar við hverja tryggingarstefnu fyrir hverja eign. Þetta eru vátryggingatengdar upphæðir sem bókaðar voru.  

1. Veldu ![Ljósapera sem opnar eiginleika Viðmótsleitar.](media/ui-search/search_small.png "Segðu mér hvað þú vilt gera") táknið, fara í **Trygging** og velja síðan viðkomandi tengil.  
2. Valin er viðeigandi vátryggingarskírteini og veldu svo **heildarvirði tryggingar á eign** aðgerðina.  
3. Fyllið inn í svæðin eftir þörfum.  
4. Veljið aðgerðina **Sýna fylki**.  
5. Til að skoða undirliggjandi vátryggingasviðsfærslur, velja gildi í fylkinu.  

## <a name="to-correct-insurance-coverage-entries" />Leiðrétting á vátryggingarsviðsfærslum
Ef eign hefur verið tengd við rangt vátryggingarskírteini er hægt að leiðrétta það með því stofna tvær endurflokkunarfærslur úr vátryggingabókinni.  

1. Veldu ![Ljósapera sem opnar eiginleika Viðmótsleitar.](media/ui-search/search_small.png "Segðu mér hvað þú vilt gera") í reitnum Leit skal færa inn **Vátryggingabók** og velja síðan viðkomandi tengil.  
2. Stofna eina færslubókarlínu fyrir hverja eign og rétt vátryggingarskírteini þar sem gildið í reitnum **Upphæð** er jákvæð.  
3. Stofna aðra færslubókarlínu fyrir hverja eign og rangt vátryggingarskírteini þar sem gildið í reitnum **Upphæð** er neikvæð.  
4. Valið er **Bóka** aðgerðin.  

Eignin er losuð frá ranga vátryggingarskírteininu, á annarri línunni, og hengt við rétta vátryggingarskírteinið, á fyrstu línunni.  

## <a name="see-also" />Sjá einnig
[Eignir](fa-manage.md)  
[Uppsetning eigna](fa-setup.md)  
[Fjármál](finance.md)  
[Vinna með [!INCLUDE[prod_short](includes/prod_short.md)]](ui-work-product.md)  


[!INCLUDE[footer-include](includes/footer-banner.md)]
