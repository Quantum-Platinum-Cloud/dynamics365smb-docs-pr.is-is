---
title: Unnið með Power BI Skýrslur í Business Central| Microsoft Docs
description: 'Fáðu innsýn, viðskiptaupplýsingar og afkastavísi (KPI) úr Business Central gögnum með Power BI.'
author: jswymer
ms.topic: get-started-article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 'account schedule, analysis, reporting, financial report, business intelligence, KPI'
ms.date: 04/01/2021
ms.author: jswymer
---
# <a name="work-with-power-bi-reports-in-include-prodshortincludesprodshortmd" />Vinna með Power BI Skýrslur í [!INCLUDE [prod_short](includes/prod_short.md)]

Í þessari grein lærir þú nokkur grunnatriði við að skoða Power BI -skýrslur í [!INCLUDE [prod_short](includes/prod_short.md)].

## <a name="overview" />Yfirlit

Power BI skýrslur veita innsýn inn í [!INCLUDE[prod_short](includes/prod_short.md)]. Ýmsar síður í [!INCLUDE [prod_short](includes/prod_short.md)] innihalda Power BI-skýrsluhluta sem getur birt Power BI skýrslur. Hlutverkamiðstöð er dæmigerð síða þar sem þú sérð Power BI skýrsluhluta. Sumar listasíður, eins og **Vörur**, innihalda einnig Power BI hluta.

[!INCLUDE [prod_short](includes/prod_short.md)] vinnur með Power BI þjónustunni. Skýrslur fyrir birtingu í [!INCLUDE [prod_short](includes/prod_short.md)] eru geymdar í Power BI-þjónustu. Í [!INCLUDE [prod_short](includes/prod_short.md)] er hægt að skipta skýrslunni sem birtist í Power BI hlutanum til allra Power BI-skýrslna sem eru í boði í Power BI þjónustunni. Í fyrsta skipti sem þú skráir þig inn á [!INCLUDE [prod_short](includes/prod_short.md)], og þar til þú tengist Power BI-þjónustu, eru hlutar auðir, eins og sýnt er hér:

![Power BI hluti í Business Central.](./media/power-bi-part.png)

## <a name="get-started" />Hefjast handa

### <a name="prerequisites" />Frumskilyrði

Ef verið er að nota [!INCLUDE[prod_short](includes/prod_short.md)] á staðnum verður að gera það virkt fyrir samþættingu Power BI. Þetta verk er vanalega framkvæmt af stjórnanda. Frekari upplýsingar eru í [Setja upp [!INCLUDE[prod_short](includes/prod_short.md)] á staðnum fyrir Power BI samþættingu](admin-powerbi-setup.md#setup).

> [!NOTE]
> [!INCLUDE[prod_short](includes/prod_short.md)] á netinu hefur þegar verið sett upp til að samþætta við Power BI.

### <a name="sign-up-power-bi" />Skráning Power BI

Áður en hægt er að nota Power BI með [!INCLUDE[prod_short](includes/prod_short.md)] þarf að skrá sig fyrir Power BI-þjónustunni. Ef þú hefur ekki þegar skráð þig skaltu fara á [https://powerbi.microsoft.com](https://powerbi.microsoft.com). Þegar þú skráir þig skaltu nota vinnunetfang og aðgangsorð.

## <a name="a-nameconnectaconnect-to-power-bi---one-time-only" /><a name="connect"></a>Tengjast við Power BI - aðeins einu sinni

Þegar þú skráir þig inn í [!INCLUDE [prod_short](includes/prod_short.md)] í fyrsta skipti sérðu líklega auðan Power BI hluta (eins og sýnt er á fyrri mynd) á ýmsum síðum. Það fyrsta sem þú skalt gera er að tengjast Power BI -reikningnum þínum. Eftir tengingu er hægt að skoða skýrslur. Þú þarft aðeins að gera þetta einu sinni.

1. Veljið tengilinn **Hefjast handa með Power BI** í hlutanum **Power BI Skýrslur**.
2. Uppsetningarleiðbeiningin **Setja upp Power BI skýrslur í Business Central** hefst. Veldu **Næst** til að halda áfram.
3. Á síðunni **Athugaðu Power BI-leyfið þitt**. Framkvæmdu eitt af eftirfarandi skrefum:

    - Ef þú hefur ekki enn skráð þig fyrir Power BI skaltu velja [Fara á Power BI heimasíðu](https://powerbi.microsoft.com). Skráðu þig fyrir reikningi, farðu síðan aftur á [!INCLUDE[prod_short](includes/prod_short.md)] og kláraðu uppsetninguna.

    - Ef þú ert þegar með leyfi skaltu velja **Næst**.
4. Á næstu síðu mun [!INCLUDE[prod_short](includes/prod_short.md)] nú hlaða upp sýniútgáfu af skýrslu í Power BI. Þetta tekur nokkrar mínútur, svo það er gert í bakgrunni. Til að ljúka uppsetningunni skal velja **Næst** og síðan **Ljúka**.

Tengingarferlið hefst. Við ferlið hefur [!INCLUDE [prod_short](includes/prod_short.md)] samskipti við Power BI-þjónustuna til að komast að því hvort þú sért með gildan Power BI-reikning og leyfi. Þegar leyfið þitt hefur verið staðfest birtast sjálfgefna Power BI-skýrslan á heimasíðunni þinni. Ef engin skýrsla birtist er hægt að velja skýrslu úr hlutanum.

> [!TIP]
> Með [!INCLUDE [prod_short](includes/prod_short.md)] á netinu mun þetta skref hlaða sjálfkrafa upp sjálfgefnum Power BI skýrslum sem notaðar eru í [!INCLUDE [prod_short](includes/prod_short.md)] á Power BI vinnusvæði þitt.

#### <a name="from-include-prodshortincludesprodshortmd-on-premises" />Fyrir [!INCLUDE [prod_short](includes/prod_short.md)] á staðnum

Tenging við Power BI frá [!INCLUDE [prod_short](includes/prod_short.md)] er svipað og á netinu. Hins vegar kann að vera beðið um heimildir á **ÞJÓNUSTUHEIMILDIR AZURE ACTIVE DIRECTORY** síðunni til að veita aðgang að Power BI þjónustum. Til að veita aðgang skal velja **Heimila Azure Services** og síðan **samþykkja**.

Eftir tengingu er hægt að velja skýrslu úr Power BI-hlutanum á síðum.

## <a name="work-with-power-bi-reports" />Vinna með Power BI skýrslur

### <a name="show-reports-on-list-pages" />Sýna skýrslur á listasíðum

[!INCLUDE[prod_long](includes/prod_long.md)] inniheldur Power BI upplýsingareit á nokkrum lyklalistasíðum. Þessi upplýsingareitur veitir frekari innsýn í gögnin á listanum. Þegar farið er milli lína í listanum er skýrslan uppfærð og síuð fyrir valda færslu.

Frekari upplýsingar um hvernig á að búa til skýrslur fyrir listasíður er að finna í [Stofna Power BI skýrslur til að birta listagögn í [!INCLUDE[prod_short](includes/prod_short.md)]](across-how-use-powerbi-reports-factbox.md).

> [!TIP]
> Ef þú sérð ekki Power BI upplýsingareitinn gæti hann verið falinn á vinnusvæðinu þínu vegna sérstillingar. Veldu ![Stillingar.](media/ui-experience/settings_icon_small.png "Stillingatákn fyrir hlutverkamiðstöð") táknið og veldu síðan aðgerðina **Sérsníða**. Frekari upplýsingar eru í [Sérstilling verksvæðis](ui-personalization-user.md).
>
> Eða ef þú ert með eldri útgáfu af Business Central skaltu fara á aðgerðastikuna, velja **Aðgerðir** > **Birta** > **Sýna/fela Power BI skýrslur**.

### <a name="switch-reports" />Skipta í aðra skýrslu

Power BI hluti á síðu getur birt allar Power BI skýrslur sem þú hefur aðgang að. Til að skipta yfir í aðra skýrslu skal velja **Velja skýrslu** aðgerðina úr fellilista sem er efst í hlutanum.  

**Power BI Síða skýrsluvals** sýnir lista yfir allar Power BI-skýrslur sem þú hefur aðgang að. Þessi listi er sóttur úr vinnusvæðum þínum eða vinnusvæðum sem deilt hefur verið með þér í Power BI þjónustunni. Veldu **Virkja** fyrir allar þær skýrslur sem þú vilt birta á heimasíðunni og veldu síðan **Í lagi**. Þú munt fara aftur á síðuna og síðasta skýrsla sem þú virkjaðir birtist. Í fellilistanum með skipunum skaltu nota skipanirnar **Fyrri** og **Næsta** til að fletta á milli skýrsla.  

### <a name="get-more-reports" />Fá fleiri skýrslur

Ef þú sérð engar skýrslur á síðunni **Power BI Skýrsluval** eða sérð ekki skýrsluna sem þú vilt skaltu velja **Fá skýrslur**. Þessi aðgerð gerir þér kleift að leita að skýrslum frá tveimur staðsetningum: *Fyrirtækið mitt* eða *Þjónusta*.

- Veldu **Fyrirtækið mitt** til að fara í Power BI þjónustuna. Hér að neðan er hægt að skoða skýrslurnar innan fyrirtækisins sem þú hefur fengið heimild til að skoða. Síðan er hægt að bæta þeim við vinnusvæðið.
- Veldu **Þjónustur** til að fara í Microsoft AppSource þar sem þú getur sett upp Power BI-forrit.  

> [!TIP]
> Ef þú ert með Power BI Desktop geturðu einnig búið til nýjar Power BI skýrslur. Þegar þessar skýrslur eru gefna út á Power BI-vinnusvæðið þitt, birtast þær á síðunni **Power BI Skýrsluval**.  

### <a name="manage-and-modify-reports" />Stjórna og breyta skýrslum

Hægt er að gera breytingar á skýrslu í Power BI hlutanum. Breytingarnar sem þú gerir verða síðan birtar í Power BI-þjónustunni. Ef verið er að deila skýrslum með öðrum notendum sjá þeir einnig breytingarnar, nema breytingar séu vistaðar í nýja skýrslu.

Til að breyta skýrslu skal velja aðgerðina **Stjórna skýrslu** úr fellilista í Power BI hlutanum. Byrjaðu svo að gera breytingar. Þegar þú hefur lokið við að gera breytingar skaltu velja **Skrá** > **Vista**. Ef þetta er samnýtt skýrsla og þú vilt koma í veg fyrir að gera þessa breytingu fyrir alla notendur skaltu velja **Vista sem**.

Þegar þú ferð aftur í Mitt hlutverk mun uppfærða skýrslan birtast þar. Ef **Vista sem** r notað þarf að velja **Velja skýrslu** og virkja svo nýja skýrslu til að sjá hana.

> [!NOTE]
> Þessi eiginleiki er ekki í boði með [!INCLUDE [prod_short](includes/prod_short.md)] á staðnum.

### <a name="a-nameuploadaupload-reports" /><a name="upload"></a>Hlaða upp skýrslum

Hægt er að dreifa Power BI skýrslum á meðal notenda sem. pbix-skrám. Ef þú ert með .pbix-skrár er hægt að hlaða þeim upp og deila þeim með öllum notendum [!INCLUDE [prod_short](includes/prod_short.md)]. Skýrslunum er deilt innan hvers fyrirtækis í [!INCLUDE [prod_short](includes/prod_short.md)].  

Til að hlaða upp skýrslu skaltu velja aðgerðina **Hlaða upp skýrslu** úr fellilistanum yfir skipanir á hlutanum **Power BI Skýrslur**. Síðan skaltu finna .pbix-skrá sem skilgreinir skýrsluna sem þú vilt deila. Þá er hægt að breyta sjálfgefnu skráarinnar.  

Þegar skýrslunni hefur verið hlaðið upp á Power BI-vinnusvæðið þitt hleðst hún sjálfkrafa upp á Power BI-vinnusvæði annarra.

> [!NOTE]
> Til að hlaða upp skrá þarftu að vera með SUPER aðgangsheimildir í [!INCLUDE[prod_short](includes/prod_short.md)]. Einnig er ekki hægt að hlaða upp skýrslum með [!INCLUDE [prod_short](includes/prod_short.md)] innanhúss. Á staðnum hleðurðu skýrslum beint á Power BI vinnusvæðið þitt. Frekari upplýsingar er að finna í [Vinna með [!INCLUDE [prod_short](includes/prod_short.md)] gögn í Power BI](across-working-with-business-central-in-powerbi.md).

## <a name="fixing-problems" />Vandamál lagfærð

Hins vegar, ef eitthvað fer úrskeiðis, þessi kafli gefur lausn fyrir dæmigerður vandamál.  

### <a name="you-dont-have-a-power-bi-account" />Þú ert ekki með Power BI reikning

Power BI-Reikningur hefur ekki verið settur upp. Til að fá gildan Power BI reikning verður þú að vera með leyfi og þú þarf að hafa skráð þig inn í Power BI til að stofna Power BI vinnusvæði.

### <a name="message-there-are-no-enabled-reports-choose-select-report-to-see-a-list-of-reports-that-you-can-display" />Skilaboð: Engar skýrslur eru virkar. Veljið Velja skýrslu til að sjá hvaða skýrslur er hægt að birta.

Þessi skilaboð birtast ef ekki tókst að virkja sjálfgefna skýrslu á Power BI vinnusvæði. Eða það var virkjað en uppfærðist ekki. Farðu í skýrsluna á Power BI vinnusvæðinu, velja **Gagnasafn**, **Stillingar** og uppfæra svo skilríkin handvirkt. Þegar gagnasafnið hefur verið endurnýjað er farið aftur í [!INCLUDE[prod_short](includes/prod_short.md)] og valið skýrslu handvirkt af **Velja skýrslur** síðunni.

#### <a name="you-cant-see-a-report-on-the-select-report-page-on-a-list-page" />Ekki er hægt að sjá skýrslur á síðu skýrsluvals á listasíðunni

Það er líklega vegna þess að heiti skýrslunnar inniheldur ekki heiti listasíðunnar. Hreinsaðu síuna til að birta heildarlista yfir skýrslur sem eru tiltækar í Power BI.

## <a name="see-related-microsoft-trainingtrainingmodulesconfigure-powerbi-excel-dynamics-365-business-centralindex" />Sjá tengda [Microsoft þjálfun](/training/modules/configure-powerbi-excel-dynamics-365-business-central/index)

## <a name="see-also" />Sjá einnig

[Business Central og Power BI](admin-powerbi.md)  
[Búa til Power BI skýrslur til að birta [!INCLUDE [prod_long](includes/prod_long.md)]-gögn](across-how-use-financials-data-source-powerbi.md)  
[Power BI Samþættingaríhlutur og hönnunaryfirlit fyrir [!INCLUDE[prod_short](includes/prod_short.md)]](admin-powerbi-overview.md)  
[Vinna með [!INCLUDE [prod_short](includes/prod_short.md)] gögn í Power BI](across-working-with-business-central-in-powerbi.md)  
[Power BI fyrir neytendur](/power-bi/consumer/end-user-consumer)  
[„Nýtt útlit“ Power BI þjónustunnar](/power-bi/service-new-look)  
[Stutt leiðbeining: Tengjast við gögn í Power BI Desktop](/power-bi/desktop-quickstart-connect-to-data)  
[Power BI fylgiskjöl](/power-bi/)  
[Viðskiptaupplýsingar](bi.md)  
[Undirbúðu þig fyrir að gera viðskipti](ui-get-ready-business.md)  
[Innflutningur viðskiptagagna úr öðrum fjárhagskerfum](across-import-data-configuration-packages.md)  
[Uppsetning [!INCLUDE[prod_short](includes/prod_short.md)]](setup.md)  
[Nota [!INCLUDE[prod_short](includes/prod_short.md)] sem Power Apps gagnaveitu](across-how-use-financials-data-source-powerapps.md)  
[Nota [!INCLUDE[prod_short](includes/prod_short.md)] í Power Automate](across-how-use-financials-data-source-flow.md)  




[!INCLUDE[footer-include](includes/footer-banner.md)]
