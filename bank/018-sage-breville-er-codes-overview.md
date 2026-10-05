---
title: Sage/Breville ER-koder – så läser du den dolda servicetabellen
description: Sage- och Breville-espressomaskiner visar ER-koder från en intern servicetabell som aldrig publicerats. Så fungerar ER01–ER18 och Oracles nummer.
---

När en Breville-espressomaskin stannar tvärt och visar ER05 på panelen får du ingen förklaring i manualen. Det är ingen glömska från tillverkaren: Brevilles felkoder kommer från interna servicetabeller som företaget använder vid reparationer och aldrig har publicerat för ägarna. Samma hårdvara säljs i Storbritannien och övriga Europa under märket **Sage** – identiska maskiner, bara en annan logo – så en ER-kod på en Sage Barista Touch betyder exakt samma sak som på en Breville. Vår [Breville/Sage-avdelning](https://sv.codefixcoffee.com/breville/) täcker hela sortimentet; det här inlägget förklarar hur numreringen är uppbyggd, så att även en kod du aldrig sett förut kan berätta något användbart.

## Varför koderna aldrig hamnar i manualen

Användarmanualen handlar om rengöring och avkalkning, inte om diagnostik. De fullständiga kodtabellerna lever i varje maskins serviceläge: lösenordsskyddade skärmar avsedda för tekniker, med lagrade felräknare och livevärden från givarna. Eftersom koderna är ett reparationsverktyg snarare än en konsumentfunktion har Breville aldrig gett ut dem offentligt, och de flesta ägare ser bara den enda kod som orsakade avstängningen. [Sages brittiska supportsidor](https://www.sageappliances.co.uk/) är duktiga på skötselråd men tiger om felkoderna. Kontrasten mot Miele är slående: där står F-kodernas betydelser tryckta i bruksanvisningen, vilket är anledningen till att [Miele-sidorna](https://sv.codefixcoffee.com/miele/) kan citera manualen rakt av.

## Barista Touch-tabellen – ER01 till ER18

Barista Touch (BES880) och Barista Touch Impress (BES881) delar styrkortsfamilj och kodtabell på 18 poster. När du väl ser strukturen läser den sig lätt: givarkoderna kommer i **grupper om fyra**, en grupp per givare, som roterar genom avbrott vid uppstart, avbrott under drift, kortslutning vid uppstart och kortslutning under drift.

- **ER01 till ER04** – ThermoJet-värmarens temperaturgivare i sina fyra varianter. [ER01](https://sv.codefixcoffee.com/breville/barista-touch-bes880/er01/) är posten för avbrott vid uppstart.
- **ER05 till ER08** – temperaturgivaren för mjölkkannan, den lilla sonden vid droppbrickan som läser kannan medan röret skumar mjölken. ER05, avbrott vid uppstart, är den allra mest rapporterade Barista Touch-koden, och alla fyra poster delar samma åtgärd.
- **ER09 till ER12** – temperaturgivaren i bryggvattnets led, samma mönster med fyra varianter.
- **ER13 och ER14** – flödesmätarfel, vid uppstart respektive under drift: pumpen körde, men maskinen kunde inte räkna det vatten som passerade.
- **ER15** – kommunikationsfel mellan interna elektronikmoduler; ofta en lossnad flatkabel eller en fuktig kontakt snarare än ett havererat kort.
- **ER16 och ER17** – kvarnen: motorn överhettade och stängde av sig själv i skyddsläge, respektive motorn som inte hann bli klar inom utsatt tid.
- **ER18** – ett elektriskt eller säkerhetsbetingat fel, till exempel läckström; koden som också kan lösa ut jordfelsbrytaren i uttaget.

## Oracle-familjen numrerar annorlunda

Köper du en Oracle blir tabellen längre. Oracle (BES980) och Oracle Touch (BES990) delar en lista på 32 poster, men BES980 visar dem som "Error 1" till "Error 32" medan BES990 skriver ER framför numret. De första sexton följer kvartettlogiken över fyra givare: ångpanneposter 1 till 4, kaffepanneposter 5 till 8 (där [Error 8](https://sv.codefixcoffee.com/breville/oracle-bes980/error-8/) är kaffepannans givare som kortsluter under drift), uppvärmt bryggparti 9 till 12 och ångrör 13 till 16. Resten täcker pannor som inte värmer (17 till 19), ångpannans nivå- och påfyllnadsfel (20 och 21), flödesmätare (22 och 23), nivåsonder och överhettning (24 till 27), ett kortkommunikationsfel vid 28, kvarnen vid 29 och 30, packmotorn vid 31 samt ångpanneläcka eller misslyckad påfyllnad vid 32.

Två mindre tabeller kompletterar familjen. Oracle Jet (BES985) använder en egen, kortare tabell från E1 till E19, och Dual Boiler (BES920) håller tvåsiffriga koder 00 till 12 dolda i en självtestmeny i stället för på displayen – en Dual Boiler kan alltså bära på ett fel du aldrig sett på skärmen.

## Läs den dolda felloggen själv

Eftersom tabellerna är servicedata går vägen till maskinens historik genom samma serviceskärmar. Ingångarna är teknikervänliga men väldokumenterade av reparatörer:

- **Barista Touch och Oracle Touch** – stäng av på väggen, håll frontens Power-knapp intryckt medan du slår på strömmen igen, släpp när logotypen dyker upp, ange servicelösenordet 00000 och öppna Error Counter för lagrade fel eller Live Debug för temperaturer och vattennivåer i realtid.
- **Barista Touch Impress** – samma knappsekvens, men servicelösenordet är 02015.
- **Oracle BES980** – med maskinen inkopplad men avstängd: håll 1 CUP, 2 CUP och POWER samtidigt i minst en sekund; efter den långa signalen trycker du på SELECT-ratten för att öppna Error Storage och stega dig genom fel 1 till 32 med deras lagrade räknare.

Behandla skärmarna som skrivskyddade: anteckna vad som finns lagrat, rör inga inställningar och töm loggen först när en reparation är gjord – då ser du om koden kommer tillbaka.

## Vad reparationerna brukar kosta

Trots den hemliga tabellen är ekonomin förutsägbar. Temperaturgivare kostar cirka €25 till €95 beroende på vilken det gäller (ångrörets och mjölkkannans givare är de dyra), och o-rings-kit €10 till €20; ett reparationskit för mjölkgivaren ligger runt €30 till €50 mot €80 till €95 för originaldel. Tillverkarens offerter på interna fel utanför garantin landar ofta på €300 till €500, så en givarbyte hos en oberoende reparatör är oftast den klokare vägen. Samma tabeller för Sage-märkta maskiner finns beskrivna på engelska i [UK-upplagan av sajten](https://sv.codefixcoffee.com/uk/).

### Sverige – garanti, spänning och reservdelar

Sage-maskiner säljs i Sverige av flera espressobutiker och större kökhandlare, och ett fel som ER05 inom tre år från köpet kan omfattas av din reklamationsrätt – reklamera hos säljaren med kvittot i handen. Beställer du reservdelar direkt från Storbritannien kan brexit lägga på tull och moms, så leta först hos europeiska återförsäljare. Och ser du en Breville-märkt maskin på andrahandsmarknaden som importerats från USA: den är byggd för 120 V och kan inte kopplas rakt in i ett svenskt uttag.
