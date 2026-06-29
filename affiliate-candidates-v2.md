# Affiliate-kandidater för 3D Twin-pilot — v2 (direktkontakt-prioriterad)

Omgjort urval enligt nytt direktiv från ledningen: **annonsörer som vi har en direkt kontaktväg till (namngiven person, e-post, gärna telefon) prioriteras högst.** Den signalen finns inte i den stora annonsörsfilen ([advertiser-directory.csv](advertiser-directory.csv), 8 315 annonsörer, inga kontaktfält) — den finns bara i [Awin list of advertisers.xlsx](Awin%20list%20of%20advertisers.xlsx), som är en kurerad lista på **27 företag med kontaktuppgifter** (`Company, Item, Name, Email, Telephone` + provision/konv/godkännande/EPC).

Därför är urvalsuniversumet i v2 dessa 27 kontaktförsedda företag. CSV-filen används för att berika dem med `awinIndex`, region, betalningsstatus och konvertering per marknad.

> Skillnad mot [v1](affiliate-candidates.md): v1 silade hela Awin-listan på fysik och kommersiellt och fick fram bl.a. Helly Hansen, Salomon, Allbirds, DB Journey, Xero Shoes — **men inget av dem finns i kontaktlistan**, så de faller bort i v2. v2 är alltså en helt annan lista, byggd på vilka vi faktiskt kan nå.

## Urvalsmetodik (v2)

Samma fysiska och kommersiella kriterier som v1, men med ett nytt, tungt vägande första kriterium: **kontaktkvalitet.**

### Steg 0, kontaktkvalitet (nytt — tungt vägande)

Alla 27 har *någon* kontaktväg. Vi rangordnar kvaliteten:

- **A — direkt varumärkesanställd**, namngiven, e-post på varumärkets egen domän, ofta telefon. (Bäst: vi pratar med någon på företaget.)
- **B — namngiven via byrå/konsult** som sköter deras affiliate. (Bra: en människa svarar, men ett led bort.)
- **C — Awin-account manager** (`@awin.com`). (OK: managed program, semi-direkt.)
- **D — generisk inkorg** (`affiliate@`, `press@`, `info@`), ingen namngiven person. (Svagast.)

### Steg 0b, fysisk capture-passning (hård filtrering — oförändrad från v1)

Riggen sätter tre villkor: (1) storlek mellan golfboll och klänning, (2) matt slår reflekterande, (3) stelhet är bonus för icke-kläder; plagg draperas på skyltdocka och straffas inte. Företag utan en fysisk produkt att 3D-scanna stryks helt.

### Steg 1–3 (oförändrade)

Prestige kontra uppnåbarhet (`awinIndex` som proxy), lönsamhet (`epc` + konvertering + godkännande, provisionskolumnen opålitlig), och geografi (nordisk-först: SE/DK/NO/FI > DACH/Benelux > övriga EU > GB > US).

### Förbehåll om datan

- **EPC i xlsx är i blandade valutor** (SEK/GBP/EUR/USD) och kan inte jämföras rakt av. SEK 10,14 (Craft) och GBP 0,44 är inte samma skala. Jag rangordnar inom valuta och lutar mig på konvertering + godkännande där valutorna skiljer sig.
- **xlsx- och CSV-EPC skiljer sig ibland** (olika period/marknad). T.ex. Craft visar SEK 10,14 i xlsx men 4,48 (SE) i CSV. Behandla som riktning, inte exakt.
- **Två företag stryks** för att de inte har någon fysisk produkt: **Java Whiskers** (kattkafé/upplevelse) och **Minicabit** (taxijämförelsetjänst).

---

## Tier 1: börja här (A/B-kontakt + bra fysik + kommersiellt + geo)

| Varumärke | Kontakt (kvalitet) | Region | Kategori | Varför det passar | Signal |
|---|---|---|---|---|---|
| **Craft** | Daniel Magnusson, daniel.magnusson@craft.se, +46 70 492 61 32 (**A, direkt**) | SE/FI | Teknisk sportklädsel | Nordiskt, draperas på docka, matt textil. Direkt varumärkeskontakt — bästa kombon i hela listan. | EPC SEK **10,14** (xlsx) / 4,48 (SE CSV), konv **15,6 %**, **100 %** godkännande, 12 % provision |
| **Holdit SE** | Sasha Eliasson, sasha.eliasson@kaishin.agency, +46 76 213 42 30 (**B, byrå**) | SE/NO/DK/FI | Mobilskal/tillbehör | Hårda matta skal = stelt, matt, perfekt storlek. Svenskt, hela Norden. Perfekt rigg-fysik. | awin 74–79, EPC 2,47 (SE), konv 12,2 %, 100 % godkännande |
| **Sisterly Tribe** | Kristin Hars, kristin.hars@sisterlytribe.com, +46 72 146 87 86 (**A, direkt**) | SE | Designdriven lifestyle/mode | Minimalistiskt premiummärke = exakt "sweet spot"-prestigen v1 efterlyste. Plagg/accessoarer på docka, matt. Direkt grundar-/varumärkeskontakt. | EPC SEK 2,60, godkännande 98,9 %, 10 % provision (konv låg 0,75 %) |
| **Harman Kardon** | Srod Fathulla, srod.fathulla@harman.com (**A, direkt**); Nick Sangers, nick.sangers@iodigital.com (byrå) | DE/FR | Portabla högtalare | Igenkännbart premium-audio = stark prestige-avsmittning. Direkt varumärkeskontakt. **Välj tygklädda matta modeller, ej högglans.** | awin 60 (FR), godkännande 92 %, 5 % (konv låg 1,1 %) |

## Tier 2: starka, rätt fysik, något svagare kontakt eller signal

| Varumärke | Kontakt (kvalitet) | Region | Kategori | Not |
|---|---|---|---|---|
| **Didriksons** | Bianca Beneke / Tineal de Wet, @roardigitalconsulting.com (**B, byrå**) | SE | Ytterkläder/regnkläder | Skandinaviskt arv, plagg på docka, matt. Bra fysik + geo, men publicerade siffror n/a och bara 1 % provision i datan. |
| **Lekmer** | affiliate@babyshop.se (**D, generisk**) | SE | Barn/leksaker | Leksaker = stelt + matt + rätt storlek, idealisk icke-kläd-fysik. Svenskt, awin 75, EPC 3,70, 100 % godkännande. Svag kontaktväg. |
| **The Shirt Company** | Hannah Scrivener, hannah@sunnysidedigital.co.uk, +44 7710 655578 (**B, byrå**) | GB | Designad damkonfektion (skjortor) | London-designat, draperas på docka, matt. EPC GBP 0,44, konv 12,2 %, 100 % godkännande, 6 %. |
| **Kippy** | Anne-Charlotte Genesteix, anne-charlotte.genesteix@datamars.com (**A/B, moderbolag**) | IT | Smart GPS-pet-tracker | Liten stel matt pryl. awin 85, godkännande 98,8 %, 0–20 %. **Verifiera att enheten är > golfboll** innan capture. |
| **Vevor** | Lionel Wu, xinqian.wu@vevor.com + Chloe Zhang, chloezhang@vevor.com (**A, direkt ×2**) | DE/UK/NL/m.fl. | Verktyg/kök/industri/hem | Stark direktkontakt, bred EU-täckning (awin 66–75). Men bred katalog + svag prestige → **fånga bara handverktyg/köksvaror i rätt storlek, matt; hoppa över maskiner/överstort.** |
| **Tennis Point** | affiliate@tennis-point.de (**D, generisk**) | SE/DE | Tennisutrustning | Mycket hög konv (32,5 % SE), EPC 4,98. **Fånga skor och bollar, inte överstora/långa racketar.** Generisk kontakt. |

## Tier 3: kontakt finns, men svag på fysik, prestige eller 3D-värde

- **Pretty Little Thing** (Aimee McDonnell, @prettylittlething.com — **A**): direkt kontakt och plagg på docka, men fast fashion (låg prestige) och EPC EUR 0,11. Modellera selektivt.
- **NLY Man / Nelly** (press@nelly.com — **D**) och **Afound** (Leke, @secretsales.com — **B**): modemarknadsplatser/outlets, plagg fungerar fysiskt men diffus prestige; Afound har svag EPC (0,13) och 64 % godkännande.
- **Lentiamo** (Jaroslav, affiliate@lentiamo.com — **C/D**): bra siffror (EPC 2,64 SE, konv 11,9 %), men **dålig rigg-fysik** — linser för små, solglasögon reflekterande.
- **Joom Nordics** (Viviana Viale, @joom-contractors — **B**) och **AliExpress** (Ariel Lu, @awin.com — **C**): marknadsplatser med starka tal (Joom EPC 6,59, awin 87; AliExpress konv 41 %) men ingen varumärkesprestige och okända SKU:er. Samma invändning som i v1.
- **Zooplus** (Jesper Garpenhag, @zooplus.com — **A**) och **Tassboxen** (Lina Blomberg, info@tassboxen.se — **D**): zoohandel/konsumtionsvaror, lågt visuellt 3D-värde; Tassboxen har dessutom bara 14 % godkännande.
- **Tirendo** (Claudia Raduta, @netex.ro — **B**): däck. Lågt 3D-shoppingvärde (commodity), storlek på gränsen.
- **Cult Beauty** (Frankie Haworth, @awin.com — **C**): liten, ofta reflekterande kosmetikförpackning, lågt 3D-värde.
- **INSERIF** (press@inserif.com — **D**): personaliserade plagg/accessoarer, fungerar fysiskt men generisk kontakt + US-geo.

## Strukna (ingen fysisk produkt att 3D-scanna)

- **Java Whiskers** — kattkafé, en upplevelse/bokning, ingen produkt.
- **Minicabit** — taxijämförelsetjänst, ingen produkt.

## Genomgående varningar vid val av SKU (oförändrade från v1)

- **Reflektivitet:** välj alltid matt variant — tygklädda högtalare (Harman), ej högglans; matta skal (Holdit); matt textil (Craft, Didriksons, Sisterly Tribe). Kläder är matta och oproblematiska.
- **Storlek:** Vevor — bara handverktygs-/köksstorlek, ej maskiner. Tennis Point — skor och bollar, ej långa racketar. Kippy — bekräfta att trackern är större än en golfboll.

## Rekommenderat första steg (v2)

Börja med **Craft** — det är den enda kandidaten som kombinerar **direkt varumärkeskontakt (A)**, toppsignal (EPC, 100 % godkännande, 12 % provision), nordisk prestige och ren docka-fysik. Som första icke-kläd-case, ta **Holdit SE** (perfekt rigg-fysik, hela Norden, namngiven byråkontakt). Tillsammans testar de båda capture-flödena (plagg på docka + stelt matt objekt) *och* ger oss en levande kontaktväg in hos båda — vilket är hela poängen med det nya direktivet.
