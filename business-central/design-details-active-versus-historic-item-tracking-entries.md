---
title: 'Hönnunarupplýsingar: Virk móti sögulegum vörurakningarfærslum'
description: Þegar hlutar skjalslínumagns eru bókaðir er aðeins þetta magn flutt í birgðahöfuðbókarfærslur og vörurakningarnúmer þess.
author: SorenGP
ms.topic: conceptual
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: null
ms.date: 06/15/2021
ms.author: edupont
---
# <a name="design-details-active-versus-historic-item-tracking-entries" />Hönnunarupplýsingar: Virk móti sögulegum vörurakningarfærslum
Þegar hlutar skjalslínumagns eru bókaðir eraðeins þessi tiltekna magn flutt í birgðahöfuðbókarfærslur og vörurakningarnúmer þess. Hins vegar viltu fá aðgang að öllum viðeigandi vörurakningarupplýsingum beint úr virku skjalalínunni. Það er, ekki aðeins verður þú vilt sjá færslur sem tengjast eftirstandandi magni, þú munt einnig vilja upplýsingar um einingar sem hafa verið bókaðar. Þegar þú skoðar eða breytir síðunni **Vörurakningarlínur** er samtals innihald töflunnar **Vörurakningarlýsing** (T336) og töflunnar **Frátekningarfærsla** (T337) eru sett fram í tímabundinni útgáfu af T336. Þetta tryggir heildaraðgang að fyrri og virkum vörurakningargögnum.  

 Eftirfarandi tafla sýnir hvernig T336 og T337 eru notuð í kaupatburðarás. Feitletruðu tölurnar tákna gildi sem notandinn færir handvirkt á síðunni **Vörurakningarlínur**.  

 Skref 1: Búa innkaupapöntunarlínu með sjö stykkjum með  vörurakningarnúmerum.  

||**Magn (stofn)**|**Magn til afgreiðslu**|**Magn til reikningsf. (stofn)**|**Afgreitt magn (stofn)**|**Reikningsfært magn (stofn)**|  
|-|----------------------------------------------|--------------------------------------------|------------------------------------------------------|-------------------------------------------------------|--------------------------------------------------------|  
|**T337**|7|0|0|0|0|  
|**T336**|0|0|0|0|0|  

 Skref 2: Fá fjögur stykki.  

||**Magn (stofn)**|**Magn til afgreiðslu**|**Magn til reikningsf. (stofn)**|**Afgreitt magn (stofn)**|**Reikningsfært magn (stofn)**|  
|-|----------------------------------------------|--------------------------------------------|------------------------------------------------------|-------------------------------------------------------|--------------------------------------------------------|  
|**Vörurakningarlínur** síðan|7|**4**|**0**|0|0|  
|**T337**|3|0|0|0|0|  
|**T336**|4|0|0|4|0|  

 Skref 3: Fá tvö stykki og reikningsfæra tvö stykki.  

||**Magn (stofn)**|**Magn til afgreiðslu**|**Magn til reikningsf. (stofn)**|**Afgreitt magn (stofn)**|**Reikningsfært magn (stofn)**|  
|-|----------------------------------------------|--------------------------------------------|------------------------------------------------------|-------------------------------------------------------|--------------------------------------------------------|  
|**Vörurakningarlínur** síðan|7|**2**|**2**|4|0|  
|**T337**|1|0|0|0|0|  
|**T336**|6|0|0|6|2|  

 Skref 4: Fá eitt stykki.  

||**Magn (grunnur)**|**Magn til afgreiðslu**|**Magn til reikningsf. (stofn)**|**Afgreitt magn (stofn)**|**Reikningsfært magn (stofn)**|  
|-|----------------------------------------------|--------------------------------------------|------------------------------------------------------|-------------------------------------------------------|--------------------------------------------------------|  
|**Vörurakningarlínur** síðan|7|**1**|**0**|6|2|  
|**T336**|7|0|0|7|2|  

 Reikningsfæra 5 stykki.  

||**Magn (grunnur)**|**Magn til afgreiðslu**|**Magn til reikningsf. (stofn)**|**Afgreitt magn (stofn)**|**Reikningsfært magn (stofn)**|  
|-|----------------------------------------------|--------------------------------------------|------------------------------------------------------|-------------------------------------------------------|--------------------------------------------------------|  
|**Vörurakningarlínur** síðan|7|0|**5**|7|2|  
|**T336**|7|0|0|7|7|  

## <a name="see-also" />Sjá einnig
 [Hönnunarupplýsingar: vörurakning](design-details-item-tracking.md)   
 [Hönnunarupplýsingar: síða vörurakningarlína](design-details-item-tracking-lines-window.md)


[!INCLUDE[footer-include](includes/footer-banner.md)]
