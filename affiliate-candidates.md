# Affiliate-kandidater för 3D Twin-pilot

Urval av varumärken från Awins annonsörslista ([advertiser-directory.csv](advertiser-directory.csv), 8 315 annonsörer) för pilotprojektet där vi bygger 3D Twins av produkter och använder affiliatelänkar för att mäta hur 3D påverkar CTR, konvertering och marknadsföring.

> **Omgjort urval (v3).** Listan är omarbetad efter våra fysiska capture-begränsningar. Viktig justering: stelhetskravet gäller bara icke-kläder. Plagg draperas på skyltdocka och straffas alltså inte för att vara mjuka, vilket tar tillbaka starka nordiska klädmärken i toppen.

## Urvalsmetodik

Varje annonsör bedömdes mot våra tre kommersiella huvudkriterier, men allt filtrerades först genom capture-riggens fysiska begränsningar, som väger tyngst.

### Steg 0a, fysisk capture-passning (hård filtrering)

Riggen sätter tre villkor:

1. **Storlek:** inget större än en klänning, inget mindre än en golfboll. Sorterar bort möbler, vitvaror och stora apparater (för stora) samt smycken som ringar, örhängen och berlocker (för små).
2. **Reflekterande ytor missgynnas.** Drar ned klockor (glas + metall), polerade smycken, glasögonglas, högglansplast, krom och glas.
3. **Stelhet är en bonus, men bara för icke-kläder** (de står på vridbord). Plagg draperas på skyltdocka och har ingen stelhets-nackdel. Stelheten premierar alltså hårda föremål som inte är kläder (leksaker, skal, skor, sportutrustning, flaskor); den straffar inte mjuka plagg.

Fysisk poäng per sektor = storlek x (0,55 x matthet + 0,45 x stelhet), där klädsektorer får full stelhetspoäng (skyltdocka). Sektorer som tydligt faller utanför (möbler, vitvaror, smycken) ströks helt.

### Steg 0b, produktpassning för 3D

En 3D Twin gör skillnad bara för visuellt drivna, returkänsliga produkter. Det överlappar starkt med det fysiska filtret.

### Steg 1, prestige kontra uppnåbarhet (tyngst kommersiellt)

Vilket varumärke ger bäst referenscase senare, där en del av deras prestige kan smitta av sig på oss. `awinIndex` som proxy för skala och popularitet.

> De stora globala loggorna (adidas, Nike, Puma, Samsung) finns i listan men är fel referenspartner: runt 0 % publicerad provision och inget reellt samarbete för ett startup. Sweet spoten är igenkännbara, designdrivna varumärken i mellanskiktet som redan söker affiliatepartners, gärna nordiska.

### Steg 2, lönsamhet

Blandning av `epc` (mest verklighetsnära signalen), konverteringsgrad, godkännandegrad, provision, cookielängd och betalningsstatus.

### Steg 3, geografi (minst viktig)

Nordisk-först-kurva: SE/DK/NO/FI högst, sedan DACH och Benelux, sedan övriga EU, sedan Storbritannien, sedan USA.

### Förbehåll om datan

- **Provisionskolumnen är opålitlig.** Många `commissionMax = 0` betyder "ej publicerad / förhandlas per publisher", inte noll. Vi lutar oss mot EPC och konvertering som verklig lönsamhetssignal.
- **Största EPC-utstickarna ligger i Brasilien** och nedprioriteras på geo.
- **De högst rankade klädmärkena rent algoritmiskt** (Joom, Fashion Addict, Brahmaki) är okända marknadsplatser/återförsäljare. Höga siffror men svaga på prestige-kriteriet, så de är inte med bland prestige-valen nedan.

## Tier 1: börja här (bäst fysisk passning + kommersiellt + geo)

| Varumärke | Region | Kategori | Varför det passar | Signal |
|---|---|---|---|---|
| **Holdit** | SE/NO/DK/FI | Mobilskal/tillbehör | Hårda matta skal = stelt, matt, perfekt storlek. Svenskt, finns i hela Norden. | awin 74 till 79, EPC 2,47 (SE), konv 12 till 14 %, 100 % godkännande |
| **Craft Sportswear** | SE/FI | Teknisk sportklädsel | Nordiskt, draperas på docka, matt textil. Stark igenkänning inom uthållighetssport. | awin **94** (FI), EPC **4,48** (SE), konv 26 % (FI), 100 % godkännande |
| **Helly Hansen** | NO/SE | Ytterkläder | Norskt arv och stark prestige, nordisk geo, plagg på docka. | EPC **6,75** (NO) / 4,08 (SE) |
| **Allbirds** | GB | Skor (ull) | Matt ull, inga reflexer, halvstyv form, rätt storlek. Hög konvertering, hållbarhetsvinkel som passar vår färre-returer-berättelse. | **7 %** provision, konv **13,1 %** |
| **DB Journey** | NO/SE | Väskor/bagage (mindre SKU) | Skandinaviskt, styv matt hardshell. Fånga kabinväskor, ryggsäckar och duffels; hoppa över stora incheckningsväskor. | EPC **13,68** (NO), 99 % godkännande |
| **Salomon** | DE/FR | Outdoor-skor | Matt mesh, styv sula, rätt storlek. Igenkännbart premium. | awin 69, 100 % godkännande |

## Tier 2: starka, uppnåbara, rätt fysik

| Varumärke | Region | Kategori | Not |
|---|---|---|---|
| Xero Shoes | GB | Skor | Matt, styv, DTC, uppnåbart, awin 84 |
| JBL | SE/NO/DK | Portabla högtalare | Tygklädda matta högtalare = stelt + matt + rätt storlek (välj tygmodeller, ej högglans) |
| Lacoste | DE/FR/GB | Premium-casual kläder | Igenkännbart, 5 % provision, plagg på docka |
| Polarn O Pyret | GB (svenskt) | Barnkläder | Svenskt, 10 % provision |
| Hugo Boss | FR | Premiumkläder | 8 % provision |
| Björn Borg | DE | Kläder/underkläder | Svenskt arv, EPC 0,81 |
| Gilbert Rugby | GB | Rugbybollar | Styvt, matt, perfekt storlek, awin 87 |
| Net World Sports | GB | Sportutrustning | awin 90, konv 13,2 % |
| Hydro Flask / SIGG | GB / DE | Flaskor | Styva, rätt storlek; välj matt/pulverlackad kropp, ej blankt stål. SIGG 12 % provision |
| Decathlon | DE/ES | Bred sportutrustning + kläder | Uppnåbart, grön betalning |
| Samsonite | BE/NL | Hardshell-bagage | Välj matta finisher i kabinstorlek |
| Lekmer | SE | Barn/leksaker | Svenskt, awin 75, EPC 3,70 |

## Tier 3: prestigeloggor, hantera förväntan

- **adidas, Nike, Puma, Under Armour, Calvin Klein:** kända, passar fysiskt (plagg på docka), men runt 0 % provision och ingen reell partnerskapschans för ett startup. Modellera selektivt enbart för logga på case-vägg.
- **Lego** (BR): styva, ikoniska, enorm prestige-avsmittning, men bara BR i listan (svag geo) och plasten har viss lyster.
- **New Balance / Hoka / Clarks / UGG:** igenkännbara skor som passar fysiskt, men lägre awin och svagare godkännandegrad i den här listan.

## Genomgående varningar vid val av SKU

- **Reflektivitet:** välj alltid matt variant. Pulverlackade flaskor (ej blankt stål), tygklädda högtalare (ej högglans), matt/texturerat bagage (ej blank polykarbonat), ull/mesh/mocka-skor (ej lackläder). Kläder är matta och oproblematiska.
- **Storlek:** för väskmärken, fånga kabin- och ryggsäcksstorlekar, inte stora incheckningsväskor. För sport, undvik överstora föremål (studsmattor, kajaker, långa racketar).

## Rekommenderat första steg

**Holdit** för en snabb icke-kläder-vinst (hårt matt skal, perfekt fysik, stark konvertering, svenskt och uppnåbart), och **Craft Sportswear** eller **Helly Hansen** som det första klädcaset (nordisk prestige, draperas på docka, starka EPC-siffror). Den kombinationen testar både en stel produkt och ett plagg tidigt, vilket är de två capture-flödena vi vill validera.
