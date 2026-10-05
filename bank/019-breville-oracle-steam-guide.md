---
title: Breville/Sage Oracle – ångfel och felkoder att kolla först
description: Ångfel på Breville/Sage Oracle – vad ångsidans Error- och ER-koder betyder, rengöring av ångröret först, och när kalk är den verkliga orsaken.
---

Ångsidan är den plats där en Breville Oracle jobbar hårdast: rostfri ångpanna, automatiskt skummande ångrör, nivåsonder och en påfyllnadspump, allt varmt dagligen. Där skapas också en stor andel av maskinens felkoder. Oracle-familjen använder en servicetabell på 32 poster som Breville inte publicerar, och samma hårdvara bär **Sage**-logon i Storbritannien och Sverige – koderna är identiska. Innan du utgår från en trasig del bör du jobba igenom de billiga kontrollerna: de flesta stopp på ångsidan orsakas av en igenproppad ångrörsspets, en utebliven spolning eller kalk på en sond, och de åtgärderna är i princip gratis.

## Var ångkoderna sitter i Oracletabellen

Oracle (BES980) och Oracle Touch (BES990) delar en tabell; BES980 visar posterna som "Error 1" till "Error 32" medan BES990 skriver ER framför. De ångrelaterade posterna samlas på fem ställen:

- **Error 1 till 4** – ångpannans temperaturgivare: avbrott vid uppstart, försvinner under drift och kortslutning i båda lägena. En enda givare, fyra sätt att rapportera.
- **Error 13 till 16** – samma kvartett för ångrörets egen temperaturgivare, sonden som avslutar autoskumningen vid rätt mjölktemperatur. Den sitter på maskinens blötaste ställe.
- **Error 18** – ångpannan värms inte upp som den ska.
- **Error 20 och 21** – vattennivån eller påfyllnadspumpen i ångpannan, respektive en nivåsond som inte stämmer med vad styrkortet väntar sig.
- **Error 26** – ångpannan överhettade över målvärdet; **Error 32** är ångpanneläcka eller misslyckad påfyllnad.

Inte allt nära röret är ångsidans: koderna 5 till 8 tillhör kaffepannans givare, där [Error 8](https://sv.codefixcoffee.com/breville/oracle-bes980/error-8/) är posten för kortslutning under drift. Att läsa den lagrade loggen hjälper dig att skilja familjerna åt – på BES980 håller du in 1 CUP, 2 CUP och POWER samtidigt med maskinen avstängd för att öppna Error Storage och stega igenom alla 32 koder med räknare.

## Börja med att rengöra ångröret

Svag eller spottande ånga, eller en kod direkt efter en mjölkdryck, pekar oftare på rörspetsen än på pannan:

1. Dra ur kontakten och låt röret svalna.
2. Skruva av ångspetsen och lägg den i hett vatten med lite avkalkningsmedel; rensa varenda hål med nålen på rengöringsverktyget.
3. Kör spolningen: cirka tio sekunder ånga rakt ner i droppbrickan utan spetsen på, och sedan igen med spetsen påskruvad.
4. Spola ur röret efter varje mjölkpass hädanefter; inorkad mjölk i spetsen är det som startar de flesta av de här stoppen.

Övervakar maskinen ångtrycket, som Oracle Jet gör med sin E16-kod, kan en igenkakad spets slå ut en kod innan du ens har märkt att ångan blivit svag.

## Hårdhet, kalk och nivåsonderna

Där vattnet är hårt skriver kalken sina egna felkoder. Ångpannans nivåsonder står jämt i hett vatten, och en kalkbeläggning isolerar sonden så att kortet läser "inget vatten" fast pannan är full – det är den klassiska vägen till Error 20 eller 21 och till misslyckad påfyllnad vid Error 32. Kalk avsätts också i ångrörets kanaler och vid påfyllnadspumpens insug. En fullständig avkalkning, ångpannecykeln inkluderad, är den billigaste diagnostik du kan köra, och den löser förvånansvärt många koder helt på egen hand.

Syskonet i sortimentet bevisar samma poäng: Dual Boiler håller sina koder 00 till 12 dolda i en självtestmeny, och [kod 00](https://sv.codefixcoffee.com/breville/dual-boiler-bes920/00/) – ångpannans givare hittas inte – ligger i toppen av en tabell vars nivå- och påfyllnadskoder beter sig likadant under hårt vatten.

## När avkalkning räcker – och när den inte gör det

Avkalka först och plocka isär sen – men vet var avkalkningen slutar hjälpa:

- **Avkalka först** vid nivå-, sond- och påfyllnadskoder (20, 21, 32), vid svag ånga utan kod och på varje maskin vars senaste cykel är mer än tre månader gammal. Kostnaden: en flaska avkalkningsmedel.
- **Avkalkning hjälper inte** mot en givarkod som återkommer direkt på en nyligen avkalkad, varm maskin – oavsett om det är en ångpannepost från 1 till 4 eller [Error 8](https://sv.codefixcoffee.com/breville/oracle-bes980/error-8/) på kaffesidan. En kod som överlever en avkalkning pekar på givaren, dess kabel eller en kontakt.
- **Stanna och kolla packningarna** om Error 26 återkommer: en läckande o-ring kring ångsonden låter ånga värma givarkabeln och härma en okontrollerad panna. Nya o-rings till sonden är billiga; ett triackort som inte stänger av värmaren är det inte.
- **Error 18** på en maskin som har slutat ånga helt är oftast ett fel på värmarsidan – termisk säkring, värmeelement eller kort – inte kalk, så behandla det som en reparation i stället för en städning.

Ska du ändå öppna maskinen finns demonteringsguider för flera espressomaskiner på [iFixit](https://www.ifixit.com/) – bra när du vill lokalisera givare och kontakter innan du beställer delar.

## Vad delarna kostar

Temperaturgivare i original ligger på cirka €25 till €95 beroende på vilken givare det gäller; ångrörsenheter, som har sin givare inkluderad, kostar runt €60 till €95; ett kit med sond och o-rings omkring €85 och en påfyllnadspump €30 till €60. Ställ det mot tillverkarens offerter för interna fel utanför garantin, som ofta landar på €300 till €500 – en avkalkningsflaska först och en givarbyte sedan är nästan alltid den bättre kalkylen. Den Sage-märkta täckningen av samma tabeller finns på engelska i [UK-upplagan av sajten](https://sv.codefixcoffee.com/uk/).

### Sverige – hur hårt är ditt vatten?

I större delen av Sverige är kranvattnet mjukt, vilket gör rena kalkfel som Error 20, 21 och 32 ovanligare här än i till exempel sydöstra England – men i Skåne, på Öland och Gotland är vattnet betydligt hårdare och kalken ett reellt problem. Din kommun publicerar dricksvattenanalyser med uppgift om vattenhårdhet, så slå upp ditt värde och låt det styra avkalkningsintervallet i stället för manualens maxtid.
