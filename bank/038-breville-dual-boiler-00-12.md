---
title: Breville Dual Boiler 00–12: de tvåsiffriga koderna
description: Breville Dual Boiler BES920 visar koderna 00–12 i en dold självtestmeny: vad kodfamiljerna betyder, ångsidan mot bryggsidan — och åtgärderna.
---

Brevilles espressomaskiner meddelar sina fel direkt på displayen: Barista Touch visar ER-koder, Oracle "Error"-koder och Oracle Jet E-nummer. **Dual Boiler BES920** går sin egen väg. Dess feltabell är en rad enkla tvåsiffriga koder, **00 till och med 12**, och de ligger i en dold självtestmeny — inte på skärmen du ser varje dag. Du hittar dem inte genom att hålla ögon på frontpanelen; du måste känna till knappkombinationen.

Numreringen är värd att lära sig, för den är snyggt ordnad: vilket block en kod hamnar i avslöjar felets slag, och inom blocket pekar koden ut exakt vilken detalj som klagar.

## Så läser du felloggen

1. Stäng av maskinen vid väggen.
2. Håll in **EXIT** och **MANUAL** samtidigt som du slår på strömmen igen — självtestmenyn dyker upp.
3. Tryck **MENU** fram till post 3, felloggen. Post 4 visar nivåstatusen i pannan, angiven som LLL (lågt) eller HHH (högt).
4. I felloggen stegar **MENU** dig genom koderna 00–12, var och en med ett lagrat antal.
5. Står det "ErSt": håll in **MANUAL** tills maskinen piper — då raderas de lagrade koderna. Koppmätaren nollställs inte.

Räkna lika mycket på antalen som på koderna. Ett fel med antalet ett, inskrivet för ett år sedan, är historia. En kod vars antal växer varje vecka är ett pågående problem som håller på att växa till.

## Vad 00-familjen täcker

Koderna **00–05** utgör temperaturgivarblocket, ordnat i tre par. I varje par betyder det lägre numret att givaren **upptäcks inte** — kortet läser den som ett avbrott — och det högre att den rapporterar **kortslutning**:

- **00 och 01** — temperaturgivaren i ångpannan, först ej upptäckt, sedan kortsluten.
- **02 och 03** — temperaturgivaren i kaffepannan, först ej upptäckt, sedan kortsluten.
- **04 och 05** — temperaturgivaren i brygggruppens värmare, först ej upptäckt, sedan kortsluten.

BES920 har två rostfria pannor plus en uppvärmd brygggrupp, så de tre givarna bevakar maskinens tre uppvärmda zoner. [Kod 00-sidan](https://sv.codefixcoffee.com/breville/dual-boiler-bes920/00/) tar upp ångpannans givare, men råden gäller alla sex: sätt tillbaka och inspektera givarpluggen innan du beställer delar, och leta efter fukt — vatten som lägger sig över en kontakt läses som avbrott eller kortslutning beroende på hur det ligger. Ett äkta NTC-givarpaket kostar cirka 25–90 € beroende på vilken av de tre det gäller; O-ringsatser ligger på 10–20 € och är ofta den egentlige boven.

## Ångsidan mot bryggsidan

Resten av tabellen delar sig längs samma linje som givarparen:

- **Ångpannan:** 06 (pumpfel vid start), 07 (vattenstånds- eller pumpfel) och 11 (överhettning upptäckt).
- **Kaffepannan — bryggsidan:** 08 (pump- eller flödesfel), 09 (vattenståndsfel) och 10 (överhettning upptäckt).
- **Brygggruppen:** 12 (överhettning upptäckt).

### Koderna som följs åt

De här felen hänger ihop, och därför slår det hela loggen att läsa en enda kod. Kod 08 betyder att pumpen arbetade utan att flödesmätaren registrerade något — oftast kalk på flödesmätarens skovel eller en liten pump som surrar utan att flytta vattnet. Avkalkning är första steget i båda fallen. Kod 11, övertemperatur i ångpannan, följer vanligtvis en panna som inte fylls på igen — kontrollera om också 07 eller 08 räknat upp — eftersom elementet fortsätter värma en panna med lågt vattenstånd; den andra orsaken är en läckande tätning kring nivåsonden. Innan du beställer något: läs post 4 i självtestmenyn. Ett nivåläge som inte stämmer med ljudet när maskinen fyller avslöjar vilken sida felet verkligen sitter på.

Kod 12, överhettning av brygggruppen, är tabellens ovanliga ände — och den där återkomsten väger tyngst. En överhettning som ständigt kommer tillbaka pekar på ett effektkort som låser ett värmeelement i påslaget läge, snarare än på en givare som driver. [Kod 12-sidan](https://sv.codefixcoffee.com/breville/dual-boiler-bes920/12/) går igenom fallet.

### Ström och uttag i svenska kök

BES920 drar omkring 2 200 W, och svenska köksuttag ligger ofta på 10 A-säkringar. Koppla maskinen direkt i vägguttaget, aldrig via grenkontakt tillsammans med vattenkokare eller mikrovågsugn — annars löser säkringen ut när apparaterna startar samtidigt. Upprepade "slumpmässiga" avbrott hos just din maskin kan alltså lika gärna sitta i elinstallationen som i maskinen.

## Vad delarna kostar

- Avkalkningsmedel mot flödes- och nivåkoderna: cirka 10 € — och det räcker för en oväntat stor andel av dem.
- Påfyllnadspump: 30–60 €.
- Nivåsond med O-ringsats till ångpannan: cirka 85 €; bara O-ringsatsen 10–20 €.
- Termosäkring: 10–20 € — men ta reda på varför den löste ut.
- Triac eller effektkort: 80–150 €.

Servicecitat utanför garanti för interna fel landar oftast på 300–500 € och uppåt. En pump eller en givare lönar sig att byta själv; ett kort i en äldre maskin förtjänar en offert först. Vatten och nätspänning delar utrymme uppe på pannan — dra ur kontakten innan du rör vid sonder.

Hur övriga maskiner i serien formulerar sina fel ser du i [Breville-avdelningen](https://sv.codefixcoffee.com/breville/): ER-familjen delar diagnosidéer men inte numrering. I Storbritannien och övriga Europa säljs märket som Sage — manualer och support finns hos [Sage Appliances](https://www.sageappliances.co.uk). Demonteringstips och guider finns även på [iFixit](https://www.ifixit.com).
