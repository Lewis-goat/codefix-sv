---
title: GE-diskmaskin 888 och CFE: när felet sitter i styrkortet
description: Visar din GE-diskmaskin 888 eller CFE? Vad displayövertagandet betyder, hur du letar vatten på styrkortet och vad ett kortbyte faktiskt innebär.
---

De flesta koderna på en GE-diskmaskin pekar på något vått: C1 är en tömnings-timeout, C6 är vatten som aldrig blev varmt, H2O är inget vatten alls. Sedan finns de två koderna som pekar på något torrt och elektroniskt. [888](https://sv.codefixcoffee.com/ge/dishwasher/888/) betyder att huvudstyrkortet fälldes i sitt eget självtest, och [CFE](https://sv.codefixcoffee.com/ge/dishwasher/cfe/) att användarpanelen i dörren och huvudkortet har slutat kommunicera. Ingen av dem är en igensatt filtermask i förklädnad. Här går vi igenom vad övertagandet på displayen faktiskt betyder, vattenkontrollerna som är värda tio minuter innan du beställer ett kort — och hur ett byte verkligen går till.

## Vad 888-övertagandet på displayen betyder

På ett segmentdisplay är 888 det du ser när alla sifferpositioner lyser samtidigt. Det är inte ett felnummer i C-kodernas mening — det är kortet som tänder allt för att det inte klarade sitt eget test och inte kan köra sitt normala program. Där [C1](https://sv.codefixcoffee.com/ge/dishwasher/c1/) betyder "pumpen gick i två minuter och trumman var fortfarande full", betyder 888 att datorn som skulle ha registrerat felet själv är den trasiga delen.

Utlösningsorsaken är oftast elektrisk, inte mekanisk: en spänningstransient från åska eller ett aggregat skriver fel i ett minnesregister på kortet, och därefter faller självtestet vid varje start. Därför är det klassiska rådet — bryt strömmen i 60 sekunder och starta om — värt exakt ett försök. En återställning rensar en tillfällig störning; den lagar inte ett skadat minne. Kommer 888 tillbaka efter den reseten är skadan ett faktum och kortet måste utbytas. Ibland ligger en läcka bakom i stället för en spänningstopp — vatten som fuktat kortet — och då kommer kontrollerna nedan in i bilden.

## CFE: den andra kortkoden

CFE är ett kommunikationsfel: användarpanelen i dörren och huvudstyrkortet har tappat kontakten sinsemellan. Vanliga orsaker är en lös eller nött kabelstränga där ledningarna passerar gångjärnsområdet, en kontakt som blivit våt, eller att ett av de två korten har gett upp. Diagnosordningen spelar roll eftersom korten kostar olika mycket: börja med reseten vid säkringen, inspektera sedan — strömlöst — och säkra tillbaka kontaktorna i båda ändar, med extra uppmärksamhet på nötningar där dörren böjs i varje cykel. Först när strängan är frisk går du vidare till korten, och användarpanelen är oftast det billigare bytet. Manualen och kodlistorna för just din modell hittar du hos [GE Appliances](https://www.geappliances.com).

## Kontrollerna: vatten på kortet

Innan du beställer någon del, ägna tio minuter åt att utesluta läckvägen — ett nytt kort som monteras i en våt maskin dör nämligen med:

1. Dra ut diskmaskinen så långt att du ser under den, och leta efter vatten eller avlagringsringar på golvet.
2. Lossa sockelpanelen framtill och lys med ficklampa i bassängen. Stående vatten i pannan betyder att en läcka har nått fram till kortets grannskap.
3. Gå igenom de uppenbara läckkällorna: skum från fel typ av diskmedel, skadad dörrtätning, sprucken slang eller en pumppackning som svettas.
4. Är något vått, torka det ordentligt och åtgärda läckan först — resetta och testkör därefter. Ett kort som stänkt en gång och fått torka återhämtar sig ibland; ett kort i stående vatten gör det aldrig.

Är allt genomtorrt och 888 eller CFE ändå kommer tillbaka efter 60-sekundersreseten är det dags att beställa kortet.

## Verkligheten bakom ett styrkortsbyte

Här kommer den goda nyheten som orden "styrkort" döljer: i GE-diskmaskiner är kortet en insticksbar modul, inte fastlött. Det sitter bakom sockelpanelen eller inne i dörren beroende på modell, och jobbet är i grunden det här:

1. Bryt strömmen vid säkringen — inte bara med avstängningsknappen — innan du lossar någon panel.
2. Öppna sockeln eller dörrens framsida så att kortet blottläggs.
3. Fotografera alla kontakter innan du rör något.
4. Koppla ur varje kontakt från det gamla kortet, montera det nya och återanslut allt på samma platser.

Ingen lödning och ingen omkabeldragning — men kontaktorna är många och omärkta, och det är precis därför fotot förtjänar sin plats. Ett huvudstyrkort kostar 90–200 € och en användarpanel 60–120 €, så bytet är en genuin avvägning: rimligt på en diskmaskin under sex–sju år, och på en äldre maskin värt att jämföra med priset på en ny. Skulle du hellre lämna över jobbet tillkommer 120–250 € för ett teknikerbesök och diagnos, utöver delen.

### Jordfelsbrytaren som varning

I svenska hem sitter en jordfelsbrytare på 30 mA framför uttagen, och fukt som letar sig ner mot styrkortet löser ofta ut den först. En jordfelsbrytare som löser ut i takt med att diskmaskinen körs är därför en tydlig signal på fukt i maskinen — inte ett fel på brytaren. Återställ den inte gång på gång utan att först ha hittat orsaken.

## Den korta versionen

[Indexet över GE-diskmaskinens koder](https://sv.codefixcoffee.com/ge/dishwasher/) täcker allt, men beslutsträdet för kortkoderna är kort: en reset vid säkringen, tio minuters läckkontroll, därefter antingen en återsatt kontakt (CFE) eller ett kortbyte. Vad det aldrig handlar om: ett filterproblem, ett diskmedelsproblem eller något som en tredje reset skulle råda bot på.
