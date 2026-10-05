---
title: "C-koder i Samsung-ugnar: temperaturfamiljen i smartspisen"
description: "Samsung C-21, C-24 och C-F2: överhettningstopp, snabb temperaturstegring vid ventilationsområdet och kylfläktåterkoppling på NE- och NX-spisar."
---

Samsungs spisar och inbyggnadsugnar — NE- och NX-serierna tillsammans med syskonen NV och NZ — talar två olika felkodsdialekter. Koder i två delar, som E-08 och E-27, rapporterar om ugnens värmedelar, medan korta koder som SE och tE handlar om kontrollpanelen. Mitt emellan ligger C-familjen: C-21, C-24 och C-F2, temperatur- och fläktövervakningen som samlas i [registret över Samsung-ugnens felkoder](https://sv.codefixcoffee.com/samsung-oven-error-codes/). Ta de här kodarna på största allvar — minst en av dem betyder att ugnen verkligen blev för varm.

## Ingen fellogg att läsa ut

Samsung-ugnar saknar fellogg som användaren kommer åt. Koden står kvar på displayen tills orsaken är åtgärdad eller du bryter strömmen — vid C-koderna räknar procedurerna med fem till tio minuter i säkringsskåpet. Kommer koden tillbaka efter återställningen ska du tolka den som verklig i stället för att återställa igen och hoppas på det bästa.

## C-21: nödstopp vid överhettning

[C-21](https://sv.codefixcoffee.com/samsung/range-wall-oven/c-21/) betyder att säkerhetsövervakningen har sett ugnens inre temperatur klättra över det säkra fönstret, varvid styrkortet stängt av värmen. Användare har beskrivit spisar som blivit farligt heta innan koden dyker upp — det här är alltså en signal att avbryta tillagningen, inte ett irritationsmoment. Den vanligaste boven är ugnens temperaturgivare eller dess kabel; huvudkortet är misstänkt nummer två.

1. Bryt strömmen i fem till tio minuter och testa en gång. Kommer C-21 tillbaka vid nästa uppvärmning är felet verkligt.
2. Koppla ifrån spisen, skruva loss de två skruvarna som håller givarspetsen på ugnens bakvägg och dra försiktigt fram kabeln tills den lossnar.
3. Mät givaren med en multimätare: omkring 1 080 ohm vid rumstemperatur är friskt. Öppen krets eller ett helt galet värde betyder byte.
4. Granska kontakten efter värmeskador där kabeln passerar nära värmeelementet — en smält kontakt ger exakt samma kod.
5. Är givaren frisk men felet kvarstår reglerar kortet elementen fel, och då är det ett ärende för service.

## C-24: kontrollen av snabb temperaturstegring

[C-24](https://sv.codefixcoffee.com/samsung/range-wall-oven/c-24/) upptäcks kring ventilations- och elektronikområdet: utrymmet med kretskorten värms upp snabbare än styrkortet räknat med. Samsung dokumenterar C-24/C-25-familjen som en övertemperatur knuten till ventilationsområdet. I praktiken delar sig felet tre vägar: en kylfläkt som aldrig börjar snurra, blockerad luft runt spisen eller en åldrande övertemperaturtermistor som läser ett friskt område som hett.

Diagnosen handlar mest om att lyssna och titta. Återställ i säkringsskåpet, starta ett bakprogram och lyssna efter konvektions- och kylfläkten när ugnen värms upp — tystnad är ditt svar. Kontrollera installationsutrymmet och att inga luftöppningar under eller bakom spisen skärmas av snickerier, folie eller damm. Med strömmen av kan övertemperaturtermistorn mätas i sin kontakt; den ligger i samma klass strax över 1 000 ohm som ugnsgivaren, och en som är öppen eller driver byts ut. Är fläkten död byter du den innan styrkortet steker sig — värmen är orsaken och kortet är offret.

### Sverige: fast anslutning och inbyggnadsdjup

I svenska kök är ugnen ofta fast ansluten, och fasta elinstallationer ska enligt de svenska elsäkerhetsreglerna utföras av en behörig elinstallatör — bryt strömmen i gruppsäkringen i stället för att leta efter ett uttag. Bygger du in ugnen i ett högt skåp, kontrollera spaltmåtten mot installationsanvisningen: trång inbyggnad skärmar av kyluften, vilket är precis det C-24 reagerar på. Har du tappat bort anvisningen finns den att hämta hos [Samsungs svenska support](https://www.samsung.com/se/support/).

## C-F2: kylfläktens återkoppling

[C-F2](https://sv.codefixcoffee.com/samsung/range-wall-oven/c-f2/) ser ut som en överhettungskod men är det oftast inte. C-F-familjen betyder att kontrollsystemet inte får svar från en bevakad komponent, och i C-F2:s fall är det kylfläktkretsen: displaykortet väntar på en återkopplingssignal som aldrig kommer. Antingen står fläkten still ändå, sitter dess kontakt löst eller är värmskadad, eller så har återkopplingsledningen till kortet fallerat.

Arbeta i ordning. Efter en återställning värmer du ugnen och kontrollerar att fläkten verkligen snurrar. Snurrar den medan koden kvarstår pekar det på återkopplingsvägen: lossa och sätt tillbaka fläktkontakten på kortet och leta efter missfärgade stift. Håller fläkten tyst letar du efter ett fastkilat blad — damm eller en tappad skruv bakom panelen — och mäter sedan lindningen efter öppen krets. Fläkt och kontakt är billiga åtgärder; en C-F2 som överlever båda kontrollerna pekar mot huvudkortets ingång.

## Vad delarna kostar

Ugnstemperaturgivare kostar €15–€40 och är ett tiominutersjobb med skruvmejsel — den vanligaste lösningen i hela familjen. Kylfläktar ligger på €40–€90 och kabelsatser på €10–€20. Den dyrare posten är huvudkortet på €150–€300, och det ska du inte börja handla förrän givare och fläkt är avprovade. Ett teknikerbesök kostar cirka €120–€250 för diagnos plus del; på en garantilös spis med kortfel är offerten ett första steg, inte det sista.

En regel gäller hela familjen: återställ inte en C-21 gång på gång och fortsätt laga mat. Koden betyder att kortet redan registrerat en temperatur det inte gillade, och nästa utlösning kan ligga högre upp på skalan.
