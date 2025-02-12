---
title: Færa gögn inn í Business Central
description: Margir almennir eiginleikar auðvelda þér að færa inn gögn með fljótlegri hætti og af meiri nákvæmni. Grunnreglum og ítarlegum eiginleikum er lýst hér.
author: jswymer
ms.topic: conceptual
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 'decimal separator, data entry, focus'
ms.search.form: '9020, 9022, 9026, 9027, 9030, 9000, 9009, 9004, 9005, 9024, 9006, 9007, 9010, 9016, 9017'
ms.date: 03/23/2022
ms.author: jswymer
---
# <a name="entering-data" />Gagnainnfærsla

Margir almennir eiginleikar auðvelda þér að færa inn gögn með fljótlegri hætti og af meiri nákvæmni. Helstu meginreglum og ítarlegum eiginleikum fyrir innslátt gagna er lýst í þessari grein.  

[!INCLUDE [about-ui-learn](includes/about-ui-learn.md)]

Í dæmunum í þessu efnisatriði er notast við sýnigögn.

## <a name="work-with-editable-fields" />Vinna með breytanlega reiti

Reitirnir í [!INCLUDE[prod_short](includes/prod_short.md)] gætu innihaldið mismunandi breytanleg gögn, eins og texta eða gjaldmiðilsupphæðir. Breytanlegir reitir sýna yfirleitt innsláttarreit þar sem hægt er að slá inn gildi eða velja það. Óbreytanlegir reitir birtast yfirleitt með gráum bakgrunni.   

Sumir breytanlegir reitir bjóða upp á val til að auðvelda þér að tilgreina gildi.  

<!-- TODO: Add illustrations or images of each picker -->
|**Tínslumaður**        |**Hvernig það hjálpar að tilgreina gildi.**|
|------------------|------------------------------------|
|Dagsetningarval       |Þetta val birtir dagatal sem byggir á virkum svæðisstillingum. Það hjálpar þér að velja staka dagsetningu.|
|Fellilisti          |Fellilistar gefa þér kost á föstum gildum eða tilvísunarfærslum úr annarri töflu|
|Rofi eða gátreitur|Sumir reitir bjóða upp á einfalt val, *Já* eða *Nei*. Rofinn er notaður til að tilgreina þetta gildi og birtist alltaf sem gátreitur í listum|
|Breytingahjálp       |Sumir reitir bjóða upp á sérsniðna glugga sem henta til að fletta upp og velja besta gildið fyrir viðkomandi reit, eins og sprettigluggi|

### <a name="modifying-a-field-value" />Reitargildi breytt

Til að breyta gildi reits verður fyrst að velja þann reit. Þú stillir fókus með því að framkvæma eftirfarandi aðgerðir:

-  <kbd>Nota dálklykilinn</kbd> . Aðgerðin velur allt gildið.
- Vinstrismelltu á músinni eða svipuðu inntakstæki. Þessi aðgerð mun aðeins velja gildi reitsins í heild sinni ef reiturinn er í listanum.  

Þegar þú átt í samskiptum við reiti í notandaviðmótinu velur [!INCLUDE[prod_short](includes/prod_short.md)] yfirleitt allt reitargildið til að auðvelda þér að skipta út því gildi.

Þegar gildi svæðisins í heild sinni er valið:
- Skiptu um gildi með því að slá inn nýtt gildi. Ef reiturinn býður upp á tiltekt er hægt að virkja hann með  <kbd>Örvaflýtileið</kbd>+<kbd>Alt</kbd>  frá.
-  <kbd>Notaðu lykilinn eyða</kbd>  eða  <kbd>bakrými</kbd>  til að hreinsa gildið.

Velja skal  <kbd>F2</kbd>  lykil til að víxla á milli þess að velja allt svæðisgildið eða bendilinn eftir gildi svæðisins. Ef bendillinn er settur í lok gildisins er auðveldara að bæta við gildið sem fyrir er.

Þegar bendillinn er sýndur við lok reitargildis:
- Bæta við gildið með því að slá einfaldlega inn.
-  <kbd>Notaðu heim</kbd>,  <kbd>lok</kbd>,  <kbd>vinstri ör</kbd> og  <kbd>hægri örvalykla</kbd>  til að færa bendilinn innan úr gildinu. Ef verið er að breyta svæði í lista er vinstri örvarlykill  <kbd>valinn</kbd>  aftur þegar bendillinn er við upphaf gildistillis þess að stilla áherslu á fyrra svæðið. Á sama hátt skal velja  <kbd>hægri örvalykil</kbd>  aftur þegar bendillinn er í lok þess að gildið verði stillt í næsta svæði.

> [!NOTE]
> Eftir að þú hefur tilgreint gildi mun Business Central aðeins athuga að það sé gilt eftir að þú smellir utan reitsins eða stillir áhersluna á aðra einingu, eins og á næsta reit.  

[!INCLUDE [background_doc_journal_check](includes/background_doc_journal_check.md)]

## <a name="keyboard-shortcuts" />Flýtivísanir

Nokkrir flýtilyklar gera þér kleift að vinna án músar og flýta fyrir skráningu gagna. Þessir flýtilyklar eru sérstaklega gagnlegir fyrir margar færslur og endurtekin innsláttarverk.

Frekari upplýsingar er að finna í [Flýtilyklar á lyklaborði](keyboard-shortcuts.md). Í þessari grein er fjallað um nokkra af flýtilyklunum.

## <a name="a-namequickentryaaccelerating-data-entry-using-quick-entry" /><a name="QuickEntry"></a>Hraða gagnaskráningu með flýtifærslu

Flýtifærsla er eiginleiki sem er hannaður fyrir gagnaskráningu þegar lyklaborð er notað. Flýtifærsla virkar á reiti (t.d. í spjaldsíðum) og í listum (röðum og dálkum). Það er gagnlegt þegar verið er að framkvæma endurtekin innsláttarverk sem krefjast þess að stofnaðar séu margar færslur í röðinni. Dæmi eru sölupantanakeyrsla eða skráning nýrra vara.

Hægt er að nota dálkalykilinn til að fletta úr einum reit á síðu yfir í næsta breytanlega reit. Ókostur við að nota Tab er að hann fer alltaf yfir á næsta reit. <!-- even if the field is non-editable or seldom filled it in.-->Flýtifærsla gerir þér kleift að breyta þessari leið. Með flýtifærslu notar  <kbd>þú Enter</kbd>  takkann til að vafra um aðeins þau svæði sem þú hefur áhuga á. Flýtifærsla sleppir skrifvörðum reitum og reitum sem þú fyllir yfirleitt ekki út. Þú gætir hafa tekið eftir þessari hegðun á sumum síðum. Þessi hegðun er vegna þess að reitirnir sem eiga að fylgja með þegar ýtt er á færslulykilinn og þeir sem á að sleppa hafa verið forskilgreindir. Hægt er að sérstilla flýtifærslu með því að sérstilla vinnusvæðið þitt og fínstilla hvernig þú færir inn gögn á hverri síðu.

### <a name="how-quick-entry-works" />Hvernig flýtifærsla virkar

Hægt er að merkja sérhvern reit sem annaðhvort *hafa með í flýtifærslu* eða *ekki hafa með í flýtifærslu*. Reitir sem eru teknir með í flýtifærslu verða hafðir með í slóðinni þegar valið  <kbd>er fært inn</kbd>. Reitir sem eru undanskildir flýtifærslu verða það ekki.

Þegar lokið er við að færa gögn inn í reit er valið  <kbd>einfaldlega Enter</kbd>  til að staðfesta breytingarnar og fara í næsta reit. Ef þú vilt snúa stefnu við og fara í fyrri reitinn skaltu velja  <kbd>Shift</kbd>+<kbd>Enter</kbd>. Frekari upplýsingar um flýtileiðir er að finna í [Flýtileiðir flýtifærslu fyrir reiti](keyboard-shortcuts.md#QuickEntry).

#### <a name="tips-and-tricks" />Ábendingar og góð ráð

Eftirfarandi listi veitir gagnlegar upplýsingar um notkun á flýtifærslu.

- Hann er í boði fyrir alla breytanlega reiti.
- Hún virkar einnig fyrir bæði dálka og línur.
- Hann kemur ekki í veg fyrir aðgang annarra að öðrum einingum á síðu, svo sem aðgerðum. Þessi stök eru enn aðgengileg með  <kbd>flipa flipans</kbd>  <kbd>og</kbd>+<kbd>vaktar</kbd>.  
- Ekki þarf að víkka flýtiflipa til að Snögg færsla virki. Ef næsti reitur flýtifærslu er staðsettur í samandregnum flýtiflipa mun sá flýtiflipi sjálfkrafa stækka og setja fókus á tiltekinn reit. [!INCLUDE[prod_short](includes/prod_short.md)] man að flýtiflipinn ætti að víkka næst þegar þú opnar síðuna.  
- Flýtifærsla virkar hvort sem reitir eru áskildir eða ekki. Því er góð hugmynd að tryggja að áskilin svæði séu höfð með í flýtiskráningu.
- Sjálfgefið er að flestir reitir eru sjálfkrafa með í flýtifærslu. Í upphafi verður það líklega þitt verk að útiloka reiti úr flýtifærslu.

### <a name="to-change-quick-entry-fields" />Til að breyta reitum flýtifærslu

Til að setja upp flýtifærslu á reitum skaltu nota sérstillingu.

1. Byrjaðu sérstillingu með því að velja táknið ![Stillingar.](media/ui-experience/settings_icon_small.png "Stillingatákn fyrir hlutverkamiðstöð") og síðan aðgerðina **Sérstilla**.
2. Veldu reit sem þú vilt breyta. Í listum skaltu velja samsvarandi dálkahaus. Veldu síðan annaðhvort **Hafa með í flýtifærslu** eða **Útiloka frá flýtifærslu**.

Frekari upplýsingar um sérstillingu er að finna í [Sérstilling verksvæðis](ui-personalization-user.md).

## <a name="mandatory-fields" />Áskildir reitir

Þegar þú slærð inn gögn á síðum, eru tilteknir reitir merktir með rauðri stjörnu. Rauða stjarnan merkir að fylla verður reitinn út til að ljúka tilteknu ferli sem notar reitinn. Dæmi um þetta er bókun færslu sem notar gildið í reitnum.  

Þótt reitur sé áskilinn er ekki nauðsynlegt að fylla hann út áður en farið er áfram í aðra reiti eða síðunni er lokað. Rauða stjarnan er eingöngu áminning um að þú verðir útilokuð/útilokaður frá tilteknu ferli.  

## <a name="finding-data-as-you-type" />Finna gögn um leið og ritað er

 Þegar byrjað er að slá inn stafi í reit birtist fellilisti með mögulegum gildum. Listinn breytist eftir því sem fleiri stafir eru slegnir inn og hægt er að velja rétt gildi þegar það birtist.  

 Margir af reitunum eru með örvahnapp niður sem hægt er að velja. Örin er valin til að fá lista yfir gögn sem tiltæk eru til að færa inn í reitinn. Hnappurinn hefur tvær aðgerðir, eftir því hver tegund reitsins er:  

- Uppfletting - Birtir upplýsingar úr annarri töflu sem færa má inn í reitinn. Hægt er að velja eina gagnaeiningu í einu.  

- Fellival - Birtir safn valkosta sem í boði eru fyrir reitinn. Aðeins er hægt að velja einn kost.  

## <a name="copying-and-pasting-faq-fields-and-lines" />Afrita og líma reiti og línur

Hægt er að afrita eina eða fleiri línur af listanum eða staka reiti á síðu. Límdu svo það sem þú afritaðir á sömu síðu, aðra síðu eða ytra skjal. Þú gætir til dæmis límt í Microsoft Excel eða Outlook-tölvupóst. Í stuttu máli, til afritunar, velurðu  <kbd>CTRL</kbd>+<kbd>C</kbd>  (cmd + C í MacOS) á lyklaborðinu. Til að líma skaltu velja  <kbd>CTRL</kbd>+<kbd>V</kbd>  eða  <kbd>cmd + V</kbd>  í MacOS.

Í lista, til að afrita svæðið í sama dálk af línunni hér að ofan og líma það inn í gildandi röð, veljið  <kbd>þá aðeins F8</kbd>.

Frekari upplýsingar er að finna í [Afrita og líma algengar spurningar](faq-copy-paste.yml).

## <a name="filtering-line-items" />Síun á línuatriðum

Til að hefja síuvalið, veljið  ![þá afmörkunarteikn](media/open-filter-pane-icon.png "Afmörkunarsvæðistákn")  efst á listanum eða veljið  <kbd>Shift</kbd>+<kbd>F3</kbd>  til að opna síurúðuna. Þú vinnur með afmörkunarsvæðið eins og þú gerir í öllum öðrum listum. Frekari upplýsingar er að finna í [Síun](ui-enter-criteria-filters.md#filtering).

Síun er sérstaklega hjálpleg þegar lengri skjöl eru skoðuð og greind. Ímyndaðu þér að þú opnir bókaðan sölureikning. Síðan eru línuatriði síuð til að birta öll línuatriði sem eru með einstakan afslátt yfir 5%. Einnig er hægt að sía til að sýna eingöngu fylgihluti reiðhjóls með „pro“ í heitinu.

## <a name="a-namefocusafocusing-on-line-items" /><a name="Focus"></a>Fókus settur á línuatriði

Þegar unnið er á skjölum sem innihalda vörulínuhluta reikningssíðu, er hægt að skipta yfirlitinu til að einbeita sér eingöngu að vörulínunum. Dæmaskjöl eru sölupöntun eða reikningssíða. Línuatriðahlutinn stækkar þannig að hann nær yfir nánast allt vinnusvæðið. Það felur aðra hluta síðunnar fyrir utan aðgerðasvæðið efst. Þetta veitir þér betri yfirsýn yfir línuatriðin og gefur meira rými til að vinna í þeim.

Þú hefur gagn af því sérstaklega þegar þú vinnur með stórum línuatriðinu og þú vilt færa gögnin hratt inn. Þessi eiginleiki býður einnig upp á ítarlega síugetu. Eins og á öðrum listum verður vefskoðun og leit í gegnum línuatriði enn auðveldari.

### <a name="switching-the-focus-on-and-off" />Kveikja eða slökkva á fókus

Til að leggja áherslu á línuatriði skal velja hvar sem er í hluta línuatriðis og síðan velja táknið ![Fókusstilling.](media/focus-mode.png "Fókusstillingartákn") Efst í hægra horninu eða velja  <kbd>CTRL</kbd>+<kbd>Shift</kbd>+<kbd>F12</kbd>.

Til að skipta yfir í venjulegt yfirlit skal velja ![Fókusstillingartákn.](media/focus-mode.png "Fókusstillingartákn") Eða velja  <kbd>CTRL</kbd>+<kbd>Shift</kbd>+<kbd>F12</kbd>  aftur.

## <a name="multitasking-across-multiple-pages" />Fjölvinnsla þvert á margar síður

Þú getur opnað spjald eða síðu skjals í nýjum glugga. Með því að opna nýjan glugga geturðu:

- Unnið að mörgum verkum á sama tíma
- Stjórnað rofi á yfirstandandi verki, eins og að svara símtali.
- Haltu glugga opnum í yfirstandandi verki á meðan þú ræsir eða lýkur öðru verki í gluggum.

Til að opna núverandi spjald eða skjal í nýjum glugga skal velja ![Opna nýjan glugga.](media/open-new-window-icon.png "Táknið „Opna nýjan glugga“") Efst í hægra horninu eða velja  <kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>W</kbd>.

<!--
When working on multiple tasks at a time or when managing interruptions to the current task, such as taking an incoming call, you can open a card or document page in a new window. This allows you to keep a window open for an ongoing task while you start or complete another task in one or more other windows.
-->

> [!NOTE]
> Þegar opnaðar eru aðrar síður úr spjaldi eða skjali sem opnast í nýjum glugga opnast þær síður í nýjum glugga þó að ekki sé valið  ![að opna nýja glugga.](media/open-new-window-icon.png "Táknið „Opna nýjan glugga“").

> [!NOTE]
> Ef unnið er í Safari-vafranum gæti sprettigluggavörn valdið því að nýi glugginn opnist ekki. Ef þetta er tilfellið skal tilgreina vefslóð afurðarinnar sem heimilaða vefsvæði. Frekari upplýsingar er að finna í [Breyta sérstillingum í Safari](https://go.microsoft.com/fwlink/?LinkId=2102965).<br /><br />
> Sama kann að gerast í öðrum vöfrum, svo sem Firefox. Frekari upplýsingar er að finna í [Stillingar sprettigluggavarnar í Firefox](https://go.microsoft.com/fwlink/?LinkId=2116400).  

Önnur leið til að gera margt í einu er að opna [!INCLUDE[prod_short](includes/prod_short.md)] í tveimur eða fleiri vafragluggum. Þegar þetta er gert ætti að búa til nýjan flipa og síðan afrita/líma vefslóð upprunalega flipans í nýja flipann. Þetta býr til nýja lotu.   

> [!NOTE]
> Ekki skal nota aðgerðina **Tvítekning** í vafranum til að búa til nýjan flipa því að það getur leitt til þess að aðgerðir í einum flipa útiloki aðgerðir í öðrum flipa vegna þess að þeir tilheyra sömu lotunni.

## <a name="entering-quantities-by-calculation" />Magn slegið inn eftir útreikningum

Þegar tölur eru færðar inn í magnreiti, svo sem reitinn **Magn** í birgðabókarlínu, er hægt að færa inn reikniregluna í stað heiltölumagns.  

### <a name="examples" />Dæmi

- Ef tölurnar 19+19 eru slegnar inn er niðurstaðan í reitnum 38.  

- Ef tölurnar 41-9 eru slegnar inn er niðurstaðan í reitnum 32.  

- Ef tölurnar 12*4 eru slegnar inn er niðurstaðan í reitnum 48.  

- Ef tölurnar 12/4 eru slegnar inn er niðurstaðan í reitnum 3.  

## <a name="entering-negative-numbers" />Neikvæðar tölur er færðar inn

Hægt er að færa inn neikvæðar tölur eftir tveimur leiðum. Númerið -20.5 má færa inn sem:  

- -20.5  

  Eða
- 20.5-  

Í báðum tilfellum verður upphæðin skráð í sem -20.5.  

Ef síðasti stafur segðarinnar er **+** eða **-**, mun öll segðin verða skráð með því formerki. Dæmi: **10-20+** mun gefa niðurstöðuna 10 en ekki -10.  

## <a name="entering-dates-and-times" />Dagsetning og tími færð inn

Færa má inn dagsetningar og tíma í alla þá reiti sem ætlaðir eru fyrir dagsetningar (dagsetningarreitir). Hægt er að færa inn dagsetningar með eða án skiltákna.

> [!NOTE]  
> Hvernig skal Færa inn dagsetningu og tíma fer eftir **Svæði** stillingunum þínum. Frekari upplýsingar eru í [Breyta grundvallarstillingum](ui-change-basic-settings.md).  

### <a name="entering-dates" />Dagsetningar færðar inn

Þú getur annaðhvort notað gagnaval til að velja dagsetningu úr dagbók eða fært inn dagsetningar handvirkt. Þessi hluti veitir stutt yfirlit yfir hvernig skuli slá inn dagsetningar. Frekari upplýsingar er að finna á [Vinna með dagsetningar og tíma í dagatali](ui-enter-date-ranges.md).

Fyrir handvirka færslu á dagsetningu er hægt að færa inn tvær, fjórar, sex eða átta tölur:  

- Tveir tölustafir eru túlkaðir sem dagur. Það mun bæta við mánuði og ári vinnudagsetningar.  

- Fjórir tölustafir eru túlkaðir sem dagur og mánuður. Það mun bæta við ári vinnudagsetningarinnar.  

- Ef sú dagsetning sem færa á inn er á bilinu 01/01/1950 til 31/12/2049 skaltu slá inn árið með tveimur tölustöfum. Annars skaltu slá inn ártal með fjórum tölustöfum.

  > [!NOTE]
  > Ef þú notar [!INCLUDE[prod_short](includes/prod_short.md)] á staðnum getur tveggja stafa árabilið verið mismunandi. Stjórnendur geta breytt bilinu með því að breyta stillingunni **CalendarTwoDigitYearMax** á [!INCLUDE[prod_short](includes/prod_short.md)] þjóninum. Frekari upplýsingar er að finna í [Skilgreining Business Central Server](/dynamics365/business-central/dev-itpro/administration/configure-server-instance#General).

Einnig er hægt að færa inn dagsetningu sem vikudag með vikunúmeri. Einnig er hægt að færa inn ártal. Til dæmis þýðir Mán25 eða mán25 mánudagur í viku 25.  

Hægt er að færa inn einn af þessum kóðum í stað sérstakrar dagsetningar.  

|Kóti|Niðurstaða|  
|--------------|----------------|  
|d|Þetta er dagurinn í dag (kerfisdagsetning tölvunnar).|  
|t|Þetta tilgreinir reikningstímabil þar sem t þýðir fyrsta reikningstímabilið, t2 þýðir annað reikningstímabilið og svo framvegis. |
|v|Tilgreinir vinnudagsetninguna sem er sett upp í forritinu. Vinnudagsetningunni breytt úr valmyndinni [Breyta grunnstillingum](ui-change-basic-settings.md) Handhægt gæti verið að nota vinnudagsetningar ef verið er að nota margar færslur með aðra dagsetningu en dagsins í dag.|
|n|Þetta tilgreinir að dagsetningin l eftir er lokunardagsetning, t.d. N123101.|  

## <a name="entering-times" />Tími færður inn

Þegar tímasetningar eru ritaðar er hægt að setja inn hvaða skiltákn sem er milli eininga en það er ekki nauðsynlegt. Ekki þarf að tilgreina mínútur, sekúndur eða FH/EH.  

Í eftirfarandi töflu birtast mismunandi leiðir til að færa inn tímasetningar og hvernig þær eru túlkaðar:  

|Færsla|Túlkun|  
|---------------|------------------------|  
|5|05:00:00|  
|5:30|05:30:00|  
|0530|05:30:00|  
|5:30:5|05:30:05|  
|053005|05:30:05|  
|5:30:5,50|05:30:05.5|  
|053005050|05:30:05.05|  

 Rita þarf tvær tölur fyrir hverja tímaeiningu ef skiltákn er ekki notað.  

## <a name="entering-combined-datetimes" />Sláðu inn sameinaða dagsetningar og tíma

[!INCLUDE [datetimes](includes/datetimes.md)]

## <a name="entering-duration" />Færið inn tímalengd

Hægt er að færa inn tímalengd sem tölu og mælieiningu.  

Hér eru nokkur dæmi.  

|Lengd|Mælieining**|  
|------------------|-------------------------|  
|2t|2 klst|  
|6t 30 m|6 klst 30 mín|  
|6,5t|6 klst 30 mín|  
|90m|1 klst 30 mín|  
|2d 6t 30m|2 dagar 6 klst 30 mín|  
|2d 6t 30m 56s 600ms|2 dagar 6 klst 30 mín 56 sek 600 millis|  

 Einnig er hægt að færa inn tölu og þá er henni sjálfkrafa breytt í tímalengd. Tölunni sem færð er inn er breytt samkvæmt sjálfgefnu mælieiningunni sem hefur verið tilgreind fyrir reitinn tímalengd.  

 Hægt er að sjá hvaða mælieining er notuð í reitnum tímalengd með því að færa inn tölu og sjá í hvaða mælieiningu kerfið færir hana í.  

 Tölunni 5 er breytt í 5 klst. ef mælieiningin er klukkustundir.  

## <a name="a-namedecimalasetting-the-decimal-separator-used-by-numeric-keyboards" /><a name="decimal"></a>Að stilla skiltákn tugabrots sem á að nota með talnalyklaborðum

Þegar aðgreiningarlykill  <kbd>með aukastöfum er notaður</kbd>  á talnaborði til að færa inn gögn eru raunveruleg tugabrot sem færð eru inn í svæðið ákvörðuð af svæðisstillingu þinni í Business Central. Flest svæði nota punkt (.) eða kommu (,) sem skiltákn fyrir tugabrot, eins og þú myndir yfirleitt sjá í upphæðum gjaldmiðla. Tugabrotslykillinn á talnaborðinu aðlagast að svæðinu þínu. Hann er oft ólíkur punkta- eða kommulykli á hinum hluta lyklaborðsins. Þú stillir svæðið í Business Central á síðunni **Mínar stillingar**.

Segjum til dæmis að þú sért að nota Talnalykil sem notar tímabil (.) sem  <kbd>skilalykil</kbd>  aukastafa. En gögn eru slegin inn fyrir svæðistungumál sem notar kommu (**,**) fyrir skiltákn tugabrotsins, eins og í frönsku (Frakklandi). Þú vilt því að skiltákn eins og „1.23“ sé slegið inn sem „1,23“. Í þessu tilfelli er hægt að fara á síðuna **Mínar stillingar** og stilla **Svæðið** á það svæðistungumál sem á að nota, eins og **Franska (Frakkland)**. Frekari upplýsingar eru í [Breyta grundvallarstillingum](ui-change-basic-settings.md#region).

> [!TIP]
> Það geta komið upp tilfelli þar sem þú vilt nota skiltákn tugabrots til að færa inn punkt (.). Gefum okkur til dæmis að þú hafir slegið inn dagsetningabil í síu, t.d. `01/01/2022..04/01/2022`, eða eitthvað sem krefst punkts. Til að móta þetta mál þarf að velja  <kbd>Aðgreiningarlykla</kbd>+<kbd>Alt</kbd>  á talnalyklaborinu. Þessi lyklasamsetning skiptir skiltákni tugabrots sem kemur með punkt og skiltákni tugabrots sem ákvarðast af **Svæðisstillingunni**.

## <a name="see-related-microsoft-trainingtrainingmodulesexplore-modify-info-dynamics-365-business-central" />Sjá tengda [Microsoft þjálfun](/training/modules/explore-modify-info-dynamics-365-business-central/)

## <a name="see-also" />Sjá einnig .

[Röðun, leit og síun í listum](ui-enter-criteria-filters.md)  
[Vinna með [!INCLUDE[prod_short](includes/prod_short.md)]](ui-work-product.md)


[!INCLUDE[footer-include](includes/footer-banner.md)]
