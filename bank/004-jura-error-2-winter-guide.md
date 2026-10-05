---
title: Jura Error 2 vintertid – när den kalla maskinen låser värmaren
description: Jura Error 2 beror ofta inte på en trasig del. Under ca 10 °C låser värmaren sig. Här är uppvärmningsprotokollet — och när det ändå är givaren.
---

Error 2 är den vanligaste koden på Juras automatmaskiner — serierna E, ENA, S, J, Z och GIGA delar samma nummerserie — och koden har två mycket olika ansikten. Antingen har kaffetermoblockets temperaturgivarkrets gått i öppet läge, eller också är maskinen helt enkelt för kall för att värma. Under vintern lurar den andra varianten ett förvånansvärt antal ägare som inte gjort det minsta fel, och det är just den orsaken som felmeddelandet självt aldrig antyder. Den fullständiga referensen finns på [sidan om Jura Error 2](https://sv.codefixcoffee.com/jura/automatic-machines/error-2/) — den här artikeln gräver i den kalla halvan av historien.

## Vad maskinen egentligen försöker säga

Juras Error 1 till 5 rör alla termoblockens värmare och deras givare. När elektroniken ser en temperaturavläsning som inte går att förena med den uppvärmning den har beordrat stänger den av värmaren och vägrar göra ett nytt försök — det är en skyddslåsning, inte nödvändigtvis ett haveri. Under ungefär 10 °C hamnar ett kallt termoblock vida utanför det intervall kortet väntar sig, och maskinen hanterar det precis som den skulle hantera en trasig NTC-givare. Ingenting är trasigt. Maskinen är kall.

Scenariot är ett klassiskt: en maskin som levererats vintertid efter en färd i ett ouppvärmt skåp, en Jura i ett kallt kök, uterum, garagekontor eller fritidshus, eller en som plockats ur kartongen och startats på direkten. Mönstret är alltid detsamma — den fungerade fint dagen innan, Error 2 dyker upp redan vid första starten, och ingen knapp du trycker på gör den borta.

Kaffemaskiner i allmänhet ogillar att starta kalla. Hos Philips och Saeco finns en motsvarande kod: Error 11 eller 19 betyder att maskinen behöver anpassa sig till rumstemperatur efter kall transport — se [Philips Error 11 eller 19](https://sv.codefixcoffee.com/philips-saeco/espresso-machines/error-11-or-19/) för den varianten.

## Uppvämningsprotokollet

Kör igenom det här innan du drar någon slutsats om trasigt. Det kostar ingenting och är alltid första steget på en kall maskin.

1. Flytta maskinen till ett uppvärmt rum och ge den tid — flera timmar, för att nå verklig rumstemperatur och inte bara tills skalet känns mindre kallt. Ett chassi som verkar okej kan fortfarande gömma ett termoblock väl under 10 °C.

2. Vill du skynda på processen blåser du med en hårtork på lägsta styrka in i vattentankens hålrum i cirka fem minuter, eller fyller tanken med ljummet — inte hett — kranvatten.

3. Starta om maskinen.

4. Försvinner Error 2 efter uppvärmningen har ingenting varit trasigt. Ställ maskinen varmare framöver, så kommer koden inte tillbaka.

Två varningar till sist. Ljummet betyder ljummet, inte hett — tanken, dess ventiler och packningar är i plast. Och rikt aldrig koncentrerad värme mot maskinens kropp eller elektronik, för målet är att få bort kylan ur termoblocket, inte att koka kablaget runt omkring.

## När det ändå är NTC-givaren eller termosäkringskablarna

Har maskinen verkligen hunnit bli varm — den har stått i timmar i ett uppvärmt rum — och Error 2 fortfarande visas, då är den harmliga förklaringen borta: givarkretsen är öppen. Inne i en Jura betyder det ett av två fynd:

- NTC-givaren på kaffetermoblocket har slutat fungera, eller dess kontakt har tappat förbindelsen. Syskonkoden heter [Jura Error 1](https://sv.codefixcoffee.com/jura/automatic-machines/error-1/), själva givarfelet på kaffetermoblocket, och de två felen delar både delar och symptom.

- De två termosäkringskablarna (smältledningarna) som skyddar termoblocket har gått i öppet läge — de blåser efter en överhettning eller helt enkelt med åldern. En utblåst säkringskabel visar öppet på en multimeter.

Reparationen är oftast värd pengarna. En äkta Jura NTC-givare kostar cirka €25 till €40 och ett säkringskabelpaket €15 till €30, och tekniker byter normalt båda samtidigt eftersom arbetet är detsamma. Till och med ett helt termoblock, på €90 till €180, kan motivera sig på de dyrare maskinerna. Har din Jura varit varm hela tiden är det här — inte vädret — som är din Error 2.

## Varningstecknet efter reparationen

En fälla förtjänar ett eget stycke. En termosäkringskabel som har blåst en gång kommer att blåsa igen om kraftkortet låser värmaren i på-läge. Går en nymonterad säkringskabel sönder inom några dagar ska du sluta byta säkringar — då är kraftkortet själva felet. Ett kort landar typiskt på €120 till €250 plus arbete, vilket på en äldre maskin hör hemma i en diskussion om offert mot ersättning snarare än i en reservdelsorder.

## Säkerhet — och att känna sina gränser

Att öppna en Jura är inte som att öppna en vattenkokare. Huven sitter med säkerhetsskruvar i Torx-Plus-format med ovala huvuden, och termoblocken för nätspänning. Saknar du rätt bits, en mätare och rutin vid arbete nära nätspänning är det här momentet ett verkstadsjobb — [Juras officiella support](https://www.jura.com/) hjälper dig vidare till auktoriserad service. Uppvämningsprotokollet är användarhalvan av Error 2-historien; givaren och säkringskablarna är verkstadshalvan.

Ekonomin förblir i stort sett vänlig oavsett väg. Uppvärmning kostar ingenting alls, och den realistiska delräkningen för byte av givare och säkringskablar ligger under cirka €50. För resten av märkets koder — ventil-, bryggenhets- och värmekoderna genom alla modellserier — börjar du bäst på [Jura-översikten](https://sv.codefixcoffee.com/jura/). Finns det andra kaffemaskiner i huset använder Mieles CM- och CVA-system en F-nummerkodning indexerad under [Miele](https://sv.codefixcoffee.com/miele/), och [miele.com](https://www.miele.com/) publicerar manualerna på svenska.

### Sverige: vinterförvaring och el

I Sverige stänger vi gärna av värmen helt i stugor, garage och uterum under vintern, och en Jura som övervintrar där möter dig med Error 2 på första koppen. Ta in maskinen i god tid — gärna ett helt dygn i rumstemperatur — så hinner termoblocket upp över 10 °C och du slipper förväxla kyla med ett givarfel. Och oavsett att svenska uttag är 230 V och jordade Schuko är det sladden, inte bara strömbrytaren, du ska dra ur innan du öppnar maskinen.
