---
title: Yfirlit yfir umsjónarverkhluta viðskiptakrafna
description: Þetta efnisatriði útskýrir verkhluta sem fela í sér umsjón með viðskiptakröfum og jöfnun greiðslna við fjárhagsfærslur viðskiptamanna og lánardrottna.
author: SorenGP
ms.topic: overview
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 'customer payment, debtor, balance due, AR'
ms.date: 06/23/2021
ms.author: edupont
---
# <a name="managing-receivables" />Stjórnun útistandandi reikninga

Reglulegt skref í fjárhag er að afstemma bankareikninga, sem merkir að þú þarft að jafna mótteknar greiðslur á viðskiptamann eða lánardrottnafærslur til að loka sölureikningum og innkaupakreditreikningum sem greiddum.

Á meðan flestir viðskiptavinir í B2B umhverfi greiða einhvern tímann eftir afhendingu, bókaður sölureikningur er þá skilinn eftir opinn sem viðskiptakröfudeildin lokar (jafnar) þegar greiðsla berst, er hægt að greiða suma sölureikninga strax, til dæmis með PayPal. Slíkir reikningar eru strax settir sem greiddir þegar þeir eru bókaðir, þar af leiðandi birtast þeir ekki sem greiðslur sem þarf að vinna úr í viðskiptakröfum. Nánari upplýsingar má til dæmis finna í [Sölureikningar](sales-how-invoice-sales.md).  

Í [!INCLUDE[prod_short](includes/prod_short.md)], ein sneggsta leiðin til að skrá greiðslur er á síðunni **Greiðsluafstemmingarbók** með því að flytja inn bankayfirlitsskrá eða straum. Greiðslur eru beittar til að opna viðskiptareikninga eða söluaðilum fyrir aðalbókanir á grundvelli gagna sem passa á milli greiðslu texta og færsluupplýsingar. Þú getur skoðað og breytt samsvörununum áður en þú sendir dagbókina og lokaðu færslureikningi bankareiknings fyrir færsluskrá þegar þú sendir dagbókina. Bankareikningurinn er sáttur þegar allar greiðslur eru sóttar.

Aðrar síður eru til staðar þar sem þú getur annaðhvort jafnað greiðslur eða afstemmt bankareikninga:

* Síðan **Afstemming bankareikninga** þar sem þú afstemmir bankareikninga með því að samsvara innfluttar bankayfirlitslínur við færslur í höfuðbók bankareiknings í kerfinu þínu. Hér geturðu líka afstemmt ávísanagreiðslur. Frekari upplýsingar er að finna í [Afstemma bankareikninga](bank-how-reconcile-bank-accounts-separately.md). Hér getur þú ekki jafnað greiðslur.
* Síðan **Skráning greiðslna**, þar sem þú getur jafnað greiðslur handvirkt sem voru greiddar í reiðufé, með ávísun eða bankafærslu gegn mynduðum lista af ógreiddum söluskjölum. Athugaðu að þessi virkni er aðeins í boði fyrir söluskrá. Hér getur þú ekki jafnað greiðslur á útleið og þú getur ekki afstemmt bankareikninga.
* **Inngreiðslubók**, þar sem þú sendir handvirkt inn kvittanir til viðkomandi aðalbókar, viðskiptavina eða annan reikning með því að slá inn greiðslulínu. Þú getur annaðhvort sótt um kvittun eða endurgreiðslu í eina eða fleiri opna færslur áður en þú sendir inn kvittunarskýrslu dagbókina eða frá aðalbókarfærslunni. Hér getur þú ekki afstemmt bankareikninga.

Síðan **Greiðsluafstemmingarbók** notar sjálfvirka jöfnunarreglu sem hægt er að setja upp á síðunni **Greiðslujöfnunarreglur**. Frekari upplýsingar eru í [Setja upp reglur fyrir sjálfvirka jöfnun á greiðslum](receivables-how-set-up-payment-application-rules.md).  

Aðrir þættir við stjórnun á viðskiptakröfum felar í sér að rukka útistandandi stöður, þ.á.m. vaxtareikninga og innheimtubréfa, og að setja upp bankareikninga svo hægt sé að draga greiðslur viðskiptavinar frá reikningi hans sjálfvirkt.

Eftirfarandi tafla lýsir röð verkefna með tenglum í efnisatriði þar sem þeim er lýst.  

| Til | Sjá |
| --- | --- |
| Jafna greiðslur við opnar viðskiptavina- eða lánardrottnafærslur með því að flytja inn bankayfirlit í formi skjals eða streymis, og afstemma bankareikning þegar allar greiðslur eru jafnaðar. |[Jafna greiðslur sjálfkrafa og afstemma bankareikninga](receivables-apply-payments-auto-reconcile-bank-accounts.md) |
| Jafna greiðslur við opnar færslur viðskiptamannabókar í lista yfir ógreidd söluskjöl á síðunni **Skráning greiðslna**. |[Afstemma greiðslur viðskiptamanna handvirkt úr lista yfir ógreidd söluskjöl](receivables-how-reconcile-customer-payments-list-unpaid-sales-documents.md) |
| Bóka inngreiðslur eða endurgreiðslur fyrir viðskiptavini í ínngreiðslubók og jafna við viðskiptamannafærslur, annað hvort úr færslubók eða úr bókuðum fjárhagsfærslum. |[Afstemma greiðslur viðskiptavinar með inngreiðslubók eða úr færslum í viðskiptamannabók](receivables-how-apply-sales-transactions-manually.md) |
| Minna viðskiptamenn á upphæðir á gjalddaga, reikna vexti og álag og stjórna útistandandi kröfum. |[Innheimta útistandandi skuldir](receivables-collect-outstanding-balances.md) |
|Með samþykki viðskiptamanns er hægt að sækja greiðslur beint inn á bankareikning viðskiptamanns, í evrum eingöngu.|[Innheimta greiðslur með SEPA-beingreiðslum](finance-collect-payments-with-sepa-direct-debit.md)|
|Útiloka viðskiptamann frá því að vera færður inn á skjöl eða frá bókun, t.d. vegna gjaldþrotaskipta.|[Loka á viðskiptamenn](receivables-how-block-customers.md)|
|Hægt er að setja upp vikmörk þannig að kerfið loki reikningi jafnvel þótt greiðsla, að meðteknum afslætti, nái ekki upp í fulla upphæð á reikningnum.|[Unnið með greiðsluvikmörk og greiðsluafsláttarvikmörk](finance-payment-tolerance-and-payment-discount-tolerance.md)|
| Spá fyrir þegar greiðslur berast seint fyrir söluskjöl. | [Viðbót greiðsludráttarspár](ui-extensions-late-payment-prediction.md) |

## <a name="see-related-microsoft-trainingtrainingpathsprocess-customer-vendor-payments-dynamics-365-business-central" />Sjá tengda [Microsoft þjálfun](/training/paths/process-customer-vendor-payments-dynamics-365-business-central/)

## <a name="see-also" />Sjá einnig
[Sala](sales-manage-sales.md)  
[Stjórna skuldum](payables-manage-payables.md)  
[Vinna með [!INCLUDE[prod_short](includes/prod_short.md)]](ui-work-product.md)  
[Almenn viðskiptavirkni](ui-across-business-areas.md)

## <a name="includeprodshortincludesfreetrialmdmd" />[!INCLUDE[prod_short](includes/free_trial_md.md)]


[!INCLUDE[footer-include](includes/footer-banner.md)]
