---
title: Setja upp vaxtaskilmála
description: Frekari upplýsingar um uppsetningu Business Central þannig að hægt sé að upplýsa viðskiptavini um viðbótargjöld með því að senda vaxtareikninga.
author: edupont04
ms.topic: conceptual
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 'payment due, debt, overdue, fee, charge'
ms.search.form: '6, 494'
ms.date: 04/01/2021
ms.author: edupont
---
# <a name="set-up-finance-charge-terms" />Setja upp vaxtaskilmála

Þegar viðskiptamaður greiðir ekki á gjalddaga er hægt að láta reikna út vexti sjálfvirkt og bæta þeim við gjaldföllnu upphæðina á reikningi viðskiptamannsins. Hægt er að láta viðskiptamenn vita af viðbótargjöldunum með því að senda vaxtareikninga. Fyrst verður að setja upp kóða fyrir hvern vaxtaútreikning. Síðan er hægt að færa þennan kóða inn í reitinn Kóði skilmála innheimtubréfa á viðskiptavinaspjöldum.  

## <a name="finance-charge-terms" />Vaxtaskilmálar

Nauðsynlegt er að setja upp vaxtaskilmála fyrir hvern vaxtaútreikning og úthluta svo skilmálunum til viðskiptamannsins í reitnum **Vaxtaskilmálakóði** á síðunni **Viðskiptavinur**.

Hægt er að reikna vexti með því að nota annaðhvort regluna um meðaltal daglegs jafnaðar eða reglur um gjaldfallna stöðu.

* Dagleg meðaltalsstaða  
  
  Fjöldi daga sem greiðslan er komin fram yfir gjalddaga er tekin með í reikninginn:  
  *Regla um daglega meðaltalsstöðu* - *Vaxtareikningur* = *Gjaldfallin upphæð* x *(Fjöldi daga fram yfir gjalddaga / Vaxtatímabil)* x *(Vextir/100)*

* Gjaldfallin staða  
  
  Vaxtareikningurinn er prósentuhluti af gjaldföllnu upphæðinni:  
  *Regla fyrir gjaldfallna stöðu* - *Vaxtareikningur* = *Gjaldfallin upphæð* x *(Vextir / 100)*

Að auki er sérhver skilgreining í töflunni Vaxtaskilmálar tengdur undirtöflunni Vaxtatexti. Fyrir hvern vaxtagjalddaga er hægt að skilgreina byrjunar- og/eða lokatexta sem verður á vaxtareikningnum.

### <a name="to-set-up-finance-charge-terms" />Setja upp vaxtaskilmála

1. Veldu ![Ljósapera sem opnar eiginleika Viðmótsleitar.](media/ui-search/search_small.png "Segðu mér hvað þú vilt gera") táknið, fara í **Vaxtaskilmálar** og velja síðan viðkomandi tengil.  
2. Fyllið inn í reitina eftir þörfum.
3. Eigi að nota fleiri en eina samsetningu vaxtaskilmálar þarf að setja upp kóta fyrir hverja þeirra.

    Fyrir hvern vaxtaskilmála er hægt að skilgreina sérstök skilyrði sem í geta falist viðbótargjöld, bæði í SGM og erlendum gjaldmiðli. Hægt er að skilgreina viðbótargjöld í erlendum gjaldmiðlum fyrir hverja skilmála á síðunni **Vaxtaskilmálar**.
4. Velja aðgerðina **gjaldmiðlar**.
5. Á síðunni **Gjaldmiðlar fyrir vaxtaskilmála**, skal skilgreina gjaldmiðilskóða fyrir hvern skilmála og viðbótargjald.

    > [!NOTE]  
    > Þegar vextir eru stofnaðir í erlendum gjaldmiðli tekur kerfið mið af þeim skilyrðum sem sett eru um erlendan gjaldmiðil hér til að stofna vaxtareikningur. Ef engin vaxtaskilyrði fyrir erlenda gjaldmiðla eru sett upp notar kerfið SGM-vaxtaskilyrðin sem eru tilgreind á síðunni **Vaxtaskilmálar** og breytir þeim í viðeigandi gjaldmiðil.

    Fyrir hvern kóða vaxtaskilmála er hægt að tilgreina texta sem á að prenta á undan (**Byrjunartexti**) eða á eftir (**Endatexti**) færslunum á vaxtareikningnum.  
6. Veljið **Byrjunartexti** eða **Lokatexti** aðgerðirnar eftir því sem við á, og fyllið út síðuna **Vaxtatexti**.
7. Til að setja viðeigandi gildi sjálfvirkt inn í vaxtatexta, skal fara inn í eftirfarandi staðgengla í reitnum **Texti**.

|Frátaka|Gildi:|  
|-----------------|-----------|  
|%1|Innihald reitsins **Dagsetning skjals** á bréfshaus vaxtareiknings|  
|%2|Innihald reitsins **gjalddagi** á bréfshaus vaxtareiknings|  
|%3|Innihald reitsins **Vextir** í viðeigandi vaxtaskilmálum|  
|%4|Innihald reitsins **eftirstöðvar** á bréfshaus vaxtareiknings|  
|%5|Innihald reitsins **vextir upphæð** á bréfshaus vaxtareiknings|  
|%6|Innihald reitsins **Viðbótargjald** á bréfshaus vaxtareiknings|  
|%7|Heildarupphæð innheimtubréfsins|  
|%8|Innihald reitsins **gjaldmiðilskóði** á bréfshaus vaxtareiknings|  
|%9|Innihald reitsins **bókunardagsetning** á bréfshaus vaxtareiknings|  

## <a name="see-related-microsoft-trainingtrainingmodulessend-memos-dynamics-365-business-central" />Sjá tengda [Microsoft þjálfun](/training/modules/send-memos-dynamics-365-business-central/)

## <a name="see-also" />Sjá einnig .

[Innheimta útistandandi skuldir](receivables-collect-outstanding-balances.md)  
[Setja upp skilmála og stig innheimtubréfa](finance-setup-reminders.md)  
[Uppsetning Fjármála](finance-setup-finance.md)  


[!INCLUDE[footer-include](includes/footer-banner.md)]
