---
title: Grunnstilla API-sniðmát
description: Lýsir skrefunum sem þú verður að taka til að grunnstilla API sniðmát fyrir Dynamics 365 Business Central.
author: SusanneWindfeldPedersen
ms.topic: conceptual
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 'API templates, configuring templates'
ms.search.form: 5469
ms.date: 06/07/2022
ms.author: solsen
---

# <a name="configure-api-templates" />Grunnstilla API-sniðmát

API-safnið fyrir [!INCLUDE[prod_short_md](includes/prod_short.md)] gefur einfaldaða framsetningu á undirliggjandi einingum. Allir eiginleikarnir í forritinu fara ekki í gegnum tengt API. Síðan **API-uppsetning** gerir þér kleift að skilgreina sniðmát sem eru notuð til að fylla í tóma eiginleika í einingu þegar þú býrð til POST-aðgerð í gegnum API. 

Til dæmis, ef grunnstillingarsniðmát er skilgreint fyrir vörueininguna, þegar ný vörufærsla er stofnuð í gegnum vörur API, verður fyllt í alla eiginleika nýju vörunnar sem ekki eru skilgreindir í API-kallinu út frá valda sniðmátinu. Ef til dæmis ekkert gildi er skilgreint fyrir reitinn **Alm. vörubókunarflokkur** í gegnum API, en gildi er skilgreint í valda sniðmátinu, þá verður gildi bókunarflokksins sem er skilgreint í sniðmátinu notað fyrir nýju vöruna. 

## <a name="setting-up-the-entity-template" />Uppsetning sniðmátseiningar

Til að nota sniðmát með API-safninu verður þú fyrst að setja upp og skilgreina eiginleika fyrir sniðmátið. Hægt er að setja upp þessi sniðmát á síðunni **Grunnstillingarsniðmát**. Frekari upplýsingar er að finna í [Flytja inn innanhússgögn í Business Central Online](/dynamics365/business-central/dev-itpro/administration/migrate-data) (aðeins á ensku) í efni stjórnanda.  

## <a name="assign-the-template-to-an-api" />Úthluta sniðmátinu á API

Til að úthluta API sniðmáti verður þú að fara í gegnum eftirfarandi skref.

> [!NOTE]  
> Aðeins er hægt að setja upp API-sniðmát með eftirfarandi API-síðum: countriesRegions, gjaldmiðlum, viðskiptamönnum, starfsmönnum, itemCategories, paymentMethods, paymentTerms, shipmentMethods, unitsOfMeasure og lánardrottnum.

1. Veldu ![Ljósapera sem opnar eiginleika Viðmótsleitar.](media/ui-search/search_small.png "Segðu mér hvað þú vilt gera") táknið, sláðu inn **API-uppsetning** og veldu tengda tengilinn.
2. Veljið **Nýtt** og veljið síðan gildið á **Röðun** fyrir færsluna.  

    Ef fleiri en eitt sniðmát er valið fyrir API (síðukenni) eru sniðmátin notuð í þeirri röð sem er skilgreind í dálknum **Röðun**.  

    Þegar hvert sniðmát er notað eru reitargildum sem eru skilgreind í sniðmátinu aðeins beitt á reiti sem hafa ekki enn fengið gildi skilgreint, annaðhvort sérstaklega í API eða í sniðmáti sem notað var áður í röðinni.  
3. Veljið gildi fyrir **Síðukenni**.  

    Þetta er síðan fyrir API sem sniðmátið verður beitt á. Uppflettingin **Síðukenni** býður upp á lista af öllum API sem eru í boði í safninu.
4. Veljið gildi í reitnum **Sniðmátskóði**.  

    Sniðmátskóðinn er kóðinn fyrir sniðmátið sem var skilgreint á síðunni **Grunnstillingarsniðmát**. Skilgreindum sniðmátsgildum er beitt á API.  
5. Í reitnum **Skilyrði** skal tilgreina hvaða sniðmátum eigi að beita.  

    Skilgreindu sniðmáti er beitt á nýja færslu sem er stofnuð í gegnum API, en eingöngu ef skilyrðin sem eru skilgreind í reitnum **Skilyrði** eru uppfyllt af gildunum sem þegar eru skilgreind fyrir nýja tilvikið af einingunni.

## <a name="see-also" />Sjá einnig

[Fylgiskjöl API](/dynamics-nav/fin-graph)  
[Þróun á Connect Apps fyrir [!INCLUDE[prod_short_md](includes/prod_short.md)]](/dynamics365/business-central/dev-itpro/developer/devenv-develop-connect-apps)  
[Virkja API](/dynamics-nav/enabling-apis-for-dynamics-nav)  
[Endastöðvar fyrir API](/dynamics-nav/endpoints-apis-for-dynamics)  
[Stjórnun](admin-setup-and-administration.md)

[!INCLUDE[footer-include](includes/footer-banner.md)]
