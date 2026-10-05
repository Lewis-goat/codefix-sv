---
title: "Miele F-koder: en grundguide för ägare av CM och CVA"
description: "Så fungerar F-koder på Mielens CM- och CVA-maskiner, vilka vattenfel du kan fixa själv — och varför F77 och interna fel kräver service."
---

## Så fungerar Mielens självdiagnos

Mielens bänkmaskiner i CM-serien och inbyggnadssystemen CVA övervakar hela tiden sina fyllnadscyklar, ventiler och bryggenhet, och när en självkontroll fallerar rapporteras det som en F-kod. Logiken bakom tabellen är ovanligt tydlig när man väl ser den: koderna delas upp i fel på saker du kan nå fysiskt — vattenbehållaren, tillloppsslangen, filtret — och fel inne i maskinen, där manualens svar är en strömavbrottscykel följt av [Miele-service](https://www.miele.com/).

Den gränsen är satt, inte på skämt. Miele är explicit med att ytterhöljet inte får öppnas: maskinerna innehåller interna spänningar och ett trycksatt system. En Miele-ägares verkliga skicklighet ligger därför inte i komponentdiagnos utan i triage — att veta vilka koder som är dina att fixa och vilka som tillhör servicedisken. Modeller skiljer sig inuti (en CM 5510 eller 6150 på bänken är en annan maskin än en inbyggd CVA 6401 eller 6805), men F-kodssystemet är gemensamt, vilket gör en grundguide användbar genom hela serien. Börja i vår [Miele-avdelning](https://sv.codefixcoffee.com/miele/) för den fullständiga listan.

## Den vänliga änden: vattenfelen F10 och F17

F10 och F17 delar manualpost, och formuleringen är värd att lägga på minnet: inget eller mycket lite vatten dras in. Maskinen försökte fylla och misslyckades antingen helt eller fick bara ett svatt. Det här är den vänligaste fel-familjen i Mielens tabell, eftersom manualens fix i praktiken är hela fixen nästan varje gång.

Var du letar först beror på maskintyp:

- **Bänkmaskiner i CM-serien:** orsaken är nästan alltid den lösa vattenbehållaren — tom, felaktigt påsatt eller med en ventil som kärvar.
- **Inbyggda CVA-maskiner med vattenanslutning:** misstanken flyttas uppströms, till avstängningsventilen och det föremonterade filtret som matar maskinen.

Fixsekvensen för båda är kort:

1. Ta ut vattenbehållaren, fyll den med friskt kallt kranvatten (inte destillerat) och sätt tillbaka den tills den låser — manualens fix, nästan ordagrant.
2. Kontrollera behållarens ventilsäte efter en fastkittad eller smutsig tätning, och skölj den under rinnande vatten.
3. På anslutna maskiner: bekräfta att avstängningsventilen står helt öppen och att filtret inte är igenkalkat.
4. Återkommer felet, avkalka vattenintaget — kalk i ventilen är det som gör felet intermittent i stället för konstant.
5. Rapporterar maskinen fortfarande koden trots en verifierad vattentillförsel behöver intagsventilen eller pumpen ses över av Miele-service.

Kostnaderna här är små: oftast €0, med en intagsventil på ungefär €30–60 om den faktiskt har gått sönder. Vår [detaljsida om F10 och F17](https://sv.codefixcoffee.com/miele/cm-cva-machines/f10-f17/) går igenom behållar- och rörgenomgångarna fullständigt.

### Vattenhårdheten hemma i Sverige

CM- och CVA-maskiner har en inställning för vattenhårdhet, och den är värd att ställa in rätt: i större delen av Sverige är det kommunala dricksvattnet mjukt, vilket ger liten kalkbildning och långa avkalkningsintervall. I Skåne och på Gotland, där vattnet passerar kalksten, är hårdheten betydligt högre — ställ om maskinen och avkalka oftare där. Din kommun redovisar kalciumhalten i sitt dricksvattenmaterial, så det tar en minut att kolla ditt exakta läge.

## Servicegränsen: F77 och interna fel

På andra sidan tabellen sitter F77, Mielens samlingskod för ett internt fel som upptäcks vid uppstart — i praktiken oftast ventilsystemet som inte initieras. Manualens råd är ärligt om gränserna för egna åtgärder:

1. Stäng av med på/av-sensorn och koppla ur maskinen ur väggen.
2. Låt den stå avstängd i flera minuter; har F77 tidigare kommit tillbaka efter en kort avstängning, ge den upp till en timme.
3. Koppla in igen och slå på, och observera om felet dyker upp direkt vid initieringen eller först när en dryck beställs.

Ett F77 som återkommer efter strömcykeln är ett komponentfel — ventil, pump eller styrkort — och hör entydigt hemma hos Miele-service. Skriv ned modellbeteckningen innan du ringer, eftersom CM- och CVA-maskiner skiljer sig inuti och servicedisken kommer att fråga. Vår [F77-referenssida](https://sv.codefixcoffee.com/miele/cm-cva-machines/f77/) sammanfattar vad du ska kontrollera och vad du kan vänta dig.

## En sorteringsregel du kan komma ihåg

Den större F-familjen sträcker sig bortom de här posterna, med ventil- och bryggenhetsfel som ligger på samma sida om servicegränsen som F77. I stället för att memorera tabellen, använd en enda regel: handlar fixen om vatten du kan se — behållaren, tillförselventilen, filtret — är den din, och manualens steg löser den. Skulle fixen innebära att öppna maskinen, eller kommer en kod tillbaka efter en full strömcykel, tillhör den Miele.

Reparationsekonomin stödjer uppdelningen. Ett ventilbyte på de här maskinerna ligger på ungefär €50–120 och ett styrkort kostar mer, men CM- och CVA-system är dyra nog för att reparation oftast slår byte — och strömcykeln är gratis, så ett försök är alltid värt innan du ringer. Själva koderna: ha [sidan om F10 och F17](https://sv.codefixcoffee.com/miele/cm-cva-machines/f10-f17/) och [F77-sidan](https://sv.codefixcoffee.com/miele/cm-cva-machines/f77/) bokmärkta — mellan sig täcker de felen du faktiskt kommer att möta som ägare.
