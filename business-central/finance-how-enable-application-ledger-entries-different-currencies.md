---
title: Jafna færslur í mismunandi gjaldmiðlum
description: Ef viðskiptamaður selur t.d. í einum gjaldmiðli og fær greitt í öðrum er hægt að jafna fjárhagsfærsluna í mismunandi gjaldmiðlum.
author: edupont04
ms.topic: conceptual
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 'multiple currencies, payment, reconcile'
ms.search.form: '148, 460, 25'
ms.date: 04/01/2021
ms.author: edupont
---
# <a name="enable-application-of-ledger-entries-in-different-currencies" />Leyfa jöfnun fjárhagsfærslna í mismunandi gjaldmiðlum

Ef keypt er af lánardrottni í einum gjaldmiðli og greitt í öðrum gjaldmiðli er hægt að jafna greiðsluna innkaupunum.

Á sama hátt, kaupi viðskiptamaður í einum gjaldmiðli og greiði í öðrum er hægt að jafna greiðsluna við sölureikninginn.

Eftirfarandi ferli sýnir hvernig á að setja þetta upp fyrir lánardrottnafærslur á síðunni **Uppsetning innkaupa og viðskiptaskulda**. Uppsetningin er svipuð og færslur viðskiptamannabókar á síðunni **Uppsetning sölu og viðskiptakrafna**.

## <a name="to-enable-application-of-vendor-ledger-entries-in-different-currencies" />Til að virkja jöfnun lánardrottnafærslna í mismunandi gjaldmiðlum

1. Veldu ![Ljósapera sem opnar eiginleika Viðmótsleitar.](media/ui-search/search_small.png "Segðu mér hvað þú vilt gera") táknið, slá inn **Uppsetning innkaupa og viðskiptaskulda** og velja svo viðeigandi tengil.
2. Í reitnum **Jöfnun milli gjaldmiðla** skal velja einn eftirtalinna valkosta.

| Valkostur | Lýsing |
| --- | --- |
| Engin |Jöfnun milli gjaldmiðla er ekki leyfð. |
| EMU |Jöfnun milli EMU-gjaldmiðla er leyfð. |
| Allt |Jöfnun milli allra gjaldmiðla er leyfð. |

## <a name="to-set-up-gl-accounts-for-currency-application-rounding-differences" />Uppsetning fjárhagsreikninga fyrir gjaldmiðilsaðgerð sléttunarmismunar

Eigi að jafna færslur í mismunandi gjaldmiðlum þarf að setja upp fjárhagsreikninga þar sem á að bóka sléttunarmismun.  

> [!NOTE]  
> Setja verður upp fjárhagsreikningana áður en lokið er við verkið. Frekari upplýsingar er að finna í [Að skilja fjárhag og bókhaldslykla](finance-general-ledger.md).

1. Veldu ![Ljósapera sem opnar eiginleika Viðmótsleitar.](media/ui-search/search_small.png "Segðu mér hvað þú vilt gera") táknið, fara í **Bókunarflokkar viðskiptavinar** og velja síðan viðkomandi tengil.  
2. Í reitunum **Debet gjaldm.jöfn.slétt.reikn** og **Kreditreikn. gjaldeyrisjöfn.** er fært inn viðkomandi fjárhagsreikningsnúmer til að bóka sléttunarmismun.  
3. Veldu ![Ljósapera sem opnar eiginleika Viðmótsleitar.](media/ui-search/search_small.png "Segðu mér hvað þú vilt gera") táknið, fara í **Bókunarflokkar lánardrottna** og velja síðan viðkomandi tengil.  
4. Í reitunum **Debet gjaldm.jöfn.slétt.reikn** og **Kreditreikn. gjaldeyrisjöfn.** er fært inn viðkomandi fjárhagsreikningsnúmer til að bóka sléttunarmismun.  

## <a name="see-related-microsoft-trainingtrainingmodulesprocess-foreign-currency-payments-dynamics-365-business-central" />Sjá tengda [Microsoft þjálfun](/training/modules/process-foreign-currency-payments-dynamics-365-business-central/)

## <a name="see-also" />Sjá einnig .

[Stjórna skuldum](payables-manage-payables.md)  
[Stjórnun skulda](receivables-manage-receivables.md)  
[Vinna með [!INCLUDE[prod_short](includes/prod_short.md)]](ui-work-product.md)


[!INCLUDE[footer-include](includes/footer-banner.md)]
