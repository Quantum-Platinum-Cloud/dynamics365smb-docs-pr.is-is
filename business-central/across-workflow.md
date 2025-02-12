---
title: Verkflæði í Dynamics 365 Business Central
description: Notaðu innbyggða möguleika verkflæðis til að setja upp samþykktarverkflæði til að bæta við sjálfvirk verkflæði sem byggja á Power Automate. Hægt er að setja upp skref til að úthluta verkum á mismunandi fólk sem hluti af mismunandi verkum viðskiptaferla.
author: jswymer
ms.author: jswymer
ms.reviewer: jswymer
ms.service: dynamics365-business-central
ms.topic: conceptual
ms.date: 10/10/2022
ms.custom: bap-template
---
# <a name="workflows-in-dynamics-365-business-central" />Verkflæði í Dynamics 365 Business Central

Hægt er að setja upp og nota verkflæði til að tengja verk viðskiptaferla sem framkvæmd eru af ólíkum notendum. Kerfisverk, s.s. sjálfvirk bókun, er hægt að hafa með sem skref í verkflæðum. Á undan eða eftir kerfisverkum geta komið verk notanda. Að óska eftir samþykki eða samþykkja nýjar færslur eru dæmigerð skref í verkflæði.

Sjálfgefin útgáfa af [!INCLUDE [prod_short](includes/prod_short.md)] styður þrjár gerðir af verkflæðum:
  
* Power Automate flæði

  * Sjálfvirk flæði sem fara af stað vegna tilviks (t.d. stofnun, breyting eða eyðing færslu eða skjals) í [!INCLUDE[prod_short](includes/prod_short.md)]. Einnig fylgir með samþykktarflæði sem búin eru til í Power Automate sem fara af stað þegar óskað er eftir samþykki í [!INCLUDE[prod_short](includes/prod_short.md)].
  * Skyndiflæði sem eru ræst handvirkt af aðgerðinni **Sjálfvirkni** af síðum lista, spjalda og skjala.

    Búðu til og ræstu handvirkt Power Automate flæði í [!INCLUDE[prod_short](includes/prod_short.md)] færslu, eins og viðskiptamanni, vöru eða sölupöntun, með valkostum til að hafa áhrif á upplýsingar bæði innan og utan (með samþættingarverkfæri).

* Samþykktarflæði sem byggja á innbyggðum verkflæðissniðmátum

  Á síðunni **Verkflæðissniðmát** geturðu séð öll tiltæk verkflæði. Prufuútgáfan af [!INCLUDE[prod_short](includes/prod_short.md)] inniheldur mörg forskilgreind verkflæði sem koma fram í verkflæðissniðmátum sem hægt er að afrita til að búa til ný. Þegar sniðmát er opnað á síðunni **Verkflæðissniðmát** og heiti verkflæðis hefst á *MS-*, þá var sniðmátinu bætt við af Microsoft.

## <a name="power-automate-flows" />Power Automate flæði

Með [!INCLUDE [prod_short](includes/prod_short.md)] á netinu geturðu skráð þig fyrir Power Automate til að búa til öflug sjálfvirk verkflæði. Þessi verkflæði eru keyrð í [!INCLUDE [prod_short](includes/prod_short.md)]. Flæðin geta tengt saman innri og ytri gagnagjafi og verkfæri án þess að reynslu í kóðun.

|**Til að** |**Sjá**|
|-------|-------|
|Hefjast handa með Power Automate og flæði búin til, keyrir skyndiflæði|[Nota Power Automate flæði í [!INCLUDE[prod_short](includes/prod_short.md)]](across-how-use-financials-data-source-flow.md)|
|Kynntu þér hvernig á að stofna, breyta og stjórna flæðum|[Setja upp sjálfvirkt flæði](/dynamics365/business-central/dev-itpro/powerplatform/automate-workflows) og [Setja upp skyndiflæði](/dynamics365/business-central/dev-itpro/powerplatform/instant-flows)|
|Setja upp Power Automate samþættingu við[!INCLUDE[prod_short](includes/prod_short.md)] fyrir notendur sem stjórnandi|[Setja upp Power Automate samþættingu](/dynamics365/business-central/dev-itpro/powerplatform/power-automate-setup)|

## <a name="approval-workflows" />Samþykktarflæði

Búðu til samþykktarverkflæði með því að skilgreina hvað byrjar verkflæðið og hvað gerist næst á eftirfarandi hátt:

* Verkflæðistilvik, sem er breytt af skilyrðum tilviks.
* Verkflæðissvar, sem er breytt af valkostum svars.

Til að skilgreina verkflæðisskref skal fylla út reitina í verkflæðislínum með gildum tilviks og svars sem stendur fyrir studdar aðstæður.

Dæmi um tilvik samþykktarverkflæðis eru t.d. stofnun sölu- eða innkaupapantana/tilboða/reikninga, verðbreytingar, breytingar á lánardrottni eða viðskiptamanni og fleira.

[!INCLUDE[workflow](includes/workflow.md)]

| **Til að** | **Sjá** |
|--|--|
| Settu upp notendur samþykktarverkflæðis, skilgreindu hvernig notendur fá tilkynningu og búðu til ný verkflæði. (Til að búa til ný verkflæði fyrir óstuddar aðstæður skal innleiða nauðsynlegar verkflæðiseiningar með því að sérsníða kóða forrits.) | [Setja upp Verkflæði samþykktar](across-set-up-workflows.md) |
| Virkjaðu samþykktarverkflæði, svaraðu tilkynningum verkflæðis, þar á meðal beiðni um og samþykkt verkflæðisskrefs. Setja verkflæði í skjalasafn eða eyða. | [Nota Samþykktarverkflæði](across-use-workflows.md) |

<!--
| Integrate company data with Power Automate workflows, using both internal and external sources and events to create and automate tasks or workflows. | [Use Power Automate Flows in [!INCLUDE[prod_short](includes/prod_short.md)]](across-how-use-financials-data-source-flow.md) |-->

## <a name="see-related-microsoft-trainingtrainingmodulescreate-workflows" />Sjá tengda [Microsoft þjálfun](/training/modules/create-workflows/)

## <a name="see-also" />Sjá einnig .

[Sala](sales-manage-sales.md)  
[Innkaup](purchasing-manage-purchasing.md)  
[Stjórna verkum](projects-manage-projects.md)  
[Vinna með [!INCLUDE[prod_short](includes/prod_short.md)]](ui-work-product.md)  
[Úrræðaleitaðu sjálfvirku [!INCLUDE[prod_short](includes/prod_short.md)] verkflæðin þín](across-flow-troubleshoot.md)  


[!INCLUDE[footer-include](includes/footer-banner.md)]
