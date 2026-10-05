---
title: GE-diskmaskinens C-koder – tömning, påfyllnad och värme
description: GE-diskmaskinens C-koder C1–C8 täcker tömning, påfyllnad och värme, plus felkod 888 och CFE för styrkort – och service-menyn som visar senaste felet.
---

GE-diskmaskiner rapporterar fel som C-koder på displayen: C1 till och med C8, plus H2O för påfyllnadsproblem och 888 eller CFE när själva korten krånglar. Till skillnad från de flesta tillverkare publicerar GE ingen officiell lista över vad koderna betyder, så ägaren får själv matcha en teckenkombination mot ett symtom. Vår [avdelning för GE-diskmaskiner](https://sv.codefixcoffee.com/ge/dishwasher/) går igenom alla koder; det här inlägget tar familjerna i den ordning du sannolikt möter dem och avslutar med tricket i service-menyn som visar vad maskinen senast lagrade.

## Tömningsfamiljen – C1 till C3

Tre koder, ett system. C1 betyder att avloppspumpen körde i mer än två minuter utan att tömma tråget (på vissa äldre modeller flaggar koden i stället en fastkilad knapp); C2 att pumpen inte startade alls eller att slangen var totalt stoppad; C3 är den generella posten "tömmer inte som den ska". Misstänkta är alltid desamma – ett filter och en sump full av smuts, en hopklämd tömningsslang, en nyligen monterad avfallskvarn där proppen för slanganlutningen fortfarande sitter kvar, eller en defekt avloppspump. Börja med det kostnadsfria enligt [C1-sidan](https://sv.codefixcoffee.com/ge/dishwasher/c1/): dra ut underkorgen, rensa filtret och sumpen, och följ slangen under vasken. En avloppspump kostar €40 till €80 om den visar sig bara surra eller vara helt tyst.

## Påfyllnadsfel – C4, C5 och H2O

- **C4** – överfyllnad, eller att maskinen fyllde två gånger efter ett strömavbrott. Påfyllnadsventilen stänger inte tätt, eller flottörbrytaren som ska stoppa påfyllnaden har fastnat i skräp. Se [C4-sidan](https://sv.codefixcoffee.com/ge/dishwasher/c4/) för flottörkontrollen; fylls tråget med strömmen avslagen läcker ventilen igenom och måste bytas (€25 till €50).
- **C5** – för lite vatten: inte tillräckligt mycket vatten nådde tråget på utsatt tid. En påfyllnadskran på glid, ett igenproppat insugsfilter eller en svag ventil.
- **H2O** – inget vatten alls. Kontrollera att påfyllnadskranen under vasken är öppen och att slangen inte är klämd innan du rör något annat.

## Värmefel – C6 till C8

C6 betyder att vattnet aldrig nådde cirka 50 °C ens efter den förlängda uppvärmningen. Låt kranen rinna tills vattnet är hett innan du startar programmet – kommer kallt vatten in hinner värmeelementet kanske aldrig ikapp. Kommer disken ut kall och blöt, mät värmeelementets kontinuitet; element ligger på €30 till €60 och säkerhetstermostaten på €10 till €20. C7 gäller vattnets temperaturgivare (termistorn) och dess krets: ofta en lös plugg eller en billig givare, även om koden på vissa modeller i stället täcker grumlighetssensorn. C8 är oftast mekaniskt snarare än termiskt – doseringsluckan kunde inte öppnas för att en disk stod i vägen eller torkat diskmedel kilat fast spärren.

## 888 och CFE – kortkoderna

När felet är elektroniskt i stället för hydrauliskt säger GE det rakt ut. [888](https://sv.codefixcoffee.com/ge/dishwasher/888/) betyder att huvudstyrkortet inte klarade sitt eget självtest – ofta efter att en spänningsstöt från ett åskväder skrivit fel i ett minnesregister, och ibland för att en läcka fuktat ner kortet. [CFE](https://sv.codefixcoffee.com/ge/dishwasher/cfe/) betyder att den dörrmonterade användarpanelen och huvudkortet slutat kommunicera, oftast en nött kabelhärvla i gångjärnsområdet eller en fuktig kontakt. Båda koderna börjar med att du slår av och på strömmen; båda slutar med ett kortbyte om koden återkommer, till €90 till €200 för huvudkortet eller €60 till €120 för panelen. I [GE Appliances supportsidor](https://www.geappliances.com/) finns manualer per modell om du vill dubbelkolla displayens symboler.

## Service-menyn – läs det senaste felet

En diskmaskin som har stannat av och till i veckor visar ofta ingenting när du står framför den. Kortet minns däremot, och på de flesta GE-diskmaskiner kan du fråga det:

1. Öppna dörren helt.
2. Håll Start-knappen intryckt i fem sekunder för att öppna service-menyn.
3. På modeller där displayen sitter dold bakom dörrlisten trycker du i stället på Select Cycle och Start samtidigt i fem sekunder.
4. Läs av det senast lagrade felet på displayen och stäng sedan dörren.
5. För att återställa kortet bryter du strömmen i proppskåpet i 60 sekunder.

Anteckna koden, nollställ och kör ett program: en lagrad C3 från tre veckor sedan plus en färsk C3 idag är ett riktigt tömningsfel, inte en tillfällighet.

## Vad reparationerna kostar

Nästan varje C-kodslösning är en pump, en ventil, en givare eller en doseringsenhet – delar mellan €10 och €80 – plus eget arbete om du känner dig bekväm med att bryta strömmen och lossa en panel. Styrkorten är undantaget på €90 till €200. Ett hembesök av en vitvarutekniker ligger på €120 till €250 för diagnos plus del, vilket är väl spenderade pengar för kortkoderna och sällan nödvändigt för ett igenproppat filter.

### Sverige – importmaskiner och svenska avlopp

GE-diskmaskiner säljs sällan nya i Sverige, så reservdelar beställs oftast från USA – räkna med längre leveranstider och tillkommande moms och frakt. En maskin byggd för den amerikanska marknaden är dessutom konstruerad för 120 V, medan det svenska elnätet ger 230 V, så en USA-import behöver transformsator för att överhuvudtaget fungera. Eftersom avfallskvarnar är ovanliga i svenska kök ansluts tömningsslangen här oftast mot en sifon under vasken – det är där du letar efter klämda eller avglidda slangar i stället för bakom en kvarn.
