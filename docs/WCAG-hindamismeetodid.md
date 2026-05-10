# WCAG edukriteeriumite hindamismeetodite tabel

Tabelis on WCAG 2.1 A ja AA taseme edukriteeriumid seostatud EN 301 549 nõuetega ning määratud soovituslik hindamismeetod.

**Hindamise tähised:** `A` – automaatne, `M` – manuaalne, `H` – hübriidne.

## Tajutavus

| WCAG | EN 301 549 | Nimetus | Tase | Hindamine | Põhjendus |
|---|---|---|---|---|---|
| 1.1.1 | 9.1.1.1 | Mittetekstiline sisu | A | H | Automaatselt tuvastatakse puuduvad `alt`-atribuudid. Manuaalselt kontrollitakse, kas tekst kirjeldab pildi eesmärki (mitte lihtsalt "pilt1.jpg") ja kas dekoratiivsed pildid on märgitud tühja alt-tekstiga (`alt=""`). |
| 1.2.1 | 9.1.2.1 | Ainult heliline ja ainult videopõhine sisuesitus (eelsalvestatud sisu puhul) | A | M | Manuaalselt tuleb kontrollida, et helifailil on täpne tekstiline transkriptsioon ja ainult videopõhisel sisul on kirjeldus, mis annab edasi kogu visuaalse info. |
| 1.2.2 | 9.1.2.2 | Subtiitrid (eelsalvestatud sisu puhul) | M | H | Manuaalselt tuleb hinnata, kas subtiitrid on sünkroonis ja sisaldavad peale kõne ka olulisi heliefekte ning kõnelejate nimesid. |
| 1.2.3 | 9.1.2.3 | Helikirjeldus või alternatiivmeedium (eelsalvestatud sisu puhul) | A | M | Manuaalselt tuleb kontrollida, kas heliline kirjeldus või täispikk transkriptsioon selgitab kõike visuaalselt olulist, mis helis ei kajastu. |
| 1.2.4 | 9.1.2.4 | Subtiitrid (reaalajas edastatava sisu puhul) | AA | M | Manuaalselt tuleb kontrollida ülekande ajal, kas reaalajas tekkiv tekst on piisavalt täpne, loetava viivitusega ja sisaldab olulist helilist infot. |
| 1.2.5 | 9.1.2.5 | Helikirjeldus (eelsalvestatud sisu puhul) | AA | M | Manuaalselt tuleb hinnata, kas audiokirjeldus on piisavalt detailne ja sisustatud pauside ajal nii, et see ei segaks peamist dialoogi. |
| 1.3.1 | 9.1.3.1 | Teave ja seosed | A | H | Automaatselt saab kontrollida pealkirjade hierarhiat ja vormiväljade seoseid siltidega. Manuaalselt tuleb veenduda, et visuaalne struktuur (nt paks tekst pealkirjana) vastaks semantilisele koodile. |
| 1.3.2 | 9.1.3.2 | Tähenduslik järjestus | A | H | Automaatselt saab kontrollida DOM-elementide järjekorda. Manuaalselt tuleb (nt CSS-i väljalülitamisega) veenduda, et sisu on loogiliselt loetav ka ilma kujunduseta. |
| 1.3.3 | 9.1.3.3 | Aistingulised omadused | A | M | Manuaalselt tuleb üle vaadata kõik juhised, et need ei toetuks ainult visuaalsetele tunnustele nagu kuju, suurus või asukoht (nt "vajuta paremal asuvat nuppu"). |
| 1.3.4 | 9.1.3.4 | Ekraani suund | AA | M | Manuaalselt tuleb kontrollida seadet pöörates, et sisu ei lukustuks ühte asendisse ja jääks mõlemas suunas täielikult kasutatavaks. |
| 1.3.5 | 9.1.3.5 | Sisestuse eesmärgi tuvastamine | AA | H | Automaatselt saab tuvastada puuduvad või valed `autocomplete` atribuudid. Manuaalselt tuleb kontrollida, kas need on lisatud kõikidele asjakohastele sisendväljadele ning kas need vastavad välja tegelikule otstarbele, et toetada automaattäitmist ja abitehnoloogiate kasutamist. |
| 1.4.1 | 9.1.4.1 | Värvikasutus | A | M | Manuaalselt tuleb kontrollida, et värv ei oleks ainus viis teabe edastamiseks. |
| 1.4.2 | 9.1.4.2 | Helitugevuse kontrollimine | A | H | Automaatselt on võimalik tuvastada automaatselt käivituvat heli. Manuaalselt tuleb kontrollida, kas üle kolme sekundi kestvat heli on võimalik peatada, vaigistada või selle helitugevust reguleerida ilma süsteemi helitugevust muutmata. |
| 1.4.3 | 9.1.4.3 | Kontrastsus (miinimumnõue) | AA | H | Automaatselt on võimalik mõõta teksti ja tausta vahelist värvikontrasti. Kõigi kasutusolukordade ja visuaalsete esituste vastavuse hindamine eeldab manuaalset kontrolli. |
| 1.4.4 | 9.1.4.4 | Teksti suuruse muutmine | AA | H | Automaatselt on võimalik tuvastada teksti suurendamist piiravaid tehnilisi tegureid. Manuaalselt tuleb kontrollida, kas teksti on võimalik suurendada kuni 200% ilma sisu või funktsionaalsuse kadumiseta. |
| 1.4.5 | 9.1.4.5 | Pildivormingus tekst | AA | H | Automaatselt on võimalik tuvastada pildielemente. Manuaalselt tuleb hinnatata, kas pildina esitatud tekstiline info on vajalik või tuleks see esitada tekstina, et tagada parem loetavus ja kohandatavus. |
| 1.4.10 | 9.1.4.10 | Ümberpaigutus | AA | H | Automaatselt on võimalik tuvastada paigutusega seotud võimalikke piiranguid. Manuaalselt kontrollitakse, kas sisu kohandub ilma horisontaalse kerimiseta ka väiksematel ekraanisuurustel (nt 320 CSS pikslit). |
| 1.4.11 | 9.1.4.11 | Mittetekstilise sisu kontrastsus | AA | H | Automaatselt on võimalik mõõta mitte-tekstiliste elementide kontrasti. Manuaalselt tuleb hinnata nende visuaalset eristatavust ning vastavust nõudele (kontrastsuhe vähemalt 3:1). |
| 1.4.12 | 9.1.4.12 | Teksti vahekaugus | AA | H | Automaatselt on võimalik tuvastada tekstivahedega seotud stiilipiiranguid. Manuaalselt tuleb kontrollida, kas sisu jääb loetavaks ja kasutatavaks, kui tekstivahed (nt reavahe, tähevahe) suurenevad vastavalt nõuetele. |
| 1.4.13 | 9.1.4.13 | Sisu hiirega peale liikumisel või fookuse korral | AA | M | Fookusolekuga seotud elementide käitumise ja kasutatavuse hindamine eeldab manuaalset kontrolli. |

## Kasutatavus

| WCAG | EN 301 549 | Nimetus | Tase | Hindamine | Põhjendus |
|---|---|---|---|---|---|
| 2.1.1 | 9.2.1.1 | Klaviatuur | A | H | Automaatselt on võimalik tuvastada klaviatuurikasutusega seotud võimalikke probleeme. Manuaalselt tuleb kontrollida, kas kõik interaktiivsed elemendid ja funktsioonid on kasutatavad ainult klaviatuuri abil. |
| 2.1.2 | 9.2.1.2 | Klaviatuurilõksu puudumine | A | M | Klaviatuurilõksu olemasolu ja sellest väljumise võimaluse hindamine eeldab manuaalset kontrolli. |
| 2.1.4 | 9.2.1.4 | Märgipõhised kiirklahvid | A | H | Automaatselt on võimalik tuvastada võimalikke ühe märgiga kiirklahve. Manuaalselt tuleb kontrollida, kas neid on võimalik välja lülitada, ümber määrata või kas need toimivad ainult fookuse olemasolul. |
| 2.2.1 | 9.2.2.1 | Ajalimiidi muudetavus | A | H | Automaatselt on võimalik tuvastada ajapiirangute olemasolu. Manuaalselt tuleb kontrollida, kas kasutajal on võimalik ajapiirangut pikendada, kohandada või see eemaldada. |
| 2.2.2 | 9.2.2.2 | Ajutine katkestamine, peatamine, peitmine | A | H | Automaatselt saab tuvastada liikuvat või automaatselt uuenevat sisu. Manuaalselt tuleb kontrollida, kas kasutajal on võimalik selline sisu peatada, katkestada või peita. |
| 2.3.1 | 9.2.3.1 | Kolm välgatust või kolm sähvatust või ohutu vilkumine | A | M | Vilkuva sisu olemasolu ja selle mõju kasutajale eeldab manuaalset kontrolli. |
| 2.4.1 | 9.2.4.1 | Sisuplokkide vahelejätmine | A | H | Automaatselt saab tuvastada navigeerimis- ja ankruelementide olemasolu, kuid nende toimivuse ja kasutatavuse hindamine eeldab manuaalset kontrolli. |
| 2.4.2 | 9.2.4.2 | Lehe tiitel | A | H | Automaatselt saab tuvastada lehe pealkirja olemasolu, kuid selle asjakohasuse ja kirjeldavuse hindamine eeldab manuaalset kontrolli. |
| 2.4.3 | 9.2.4.3 | Fookustamise järjekord | A | H | Automaatselt on võimalik tuvastada elementide järjestus koodis. Manuaalselt tuleb hinnata, kas fookus liigub elementide vahel loogilises ja kasutajale arusaadavas järjekorras. |
| 2.4.4 | 9.2.4.4 | Lingi otstarve (kontekstis) | A | H | Automaatselt on võimalik tuvastada linkide tehnilisi puudusi. Manuaalselt tuleb hinnata, kas lingi eesmärk on koos kontekstiga kasutajale arusaadav. |
| 2.4.5 | 9.2.4.5 | Mitu võimalust | AA | M | Mitme ligipääsutee olemasolu ja nende piisavuse hindamine eeldab manuaalset kontrolli. |
| 2.4.6 | 9.2.4.6 | Pealkirjad ja sildid | AA | H | Automaatselt on võimalik tuvastada pealkirjade ja siltide olemasolu. Nende kirjeldavuse ja arusaadavuse hindamine eeldab manuaalset kontrolli. |
| 2.4.7 | 9.2.4.7 | Nähtav fookus | AA | M | Fookuse nähtavuse ja selle piisavuse hindamine eeldab manuaalset kontrolli. |
| 2.5.1 | 9.2.5.1 | Osutusžestid | A | M | Keerukate puutežestide kasutamise ja nende alternatiivide hindamine eeldab manuaalset kontrolli. |
| 2.5.2 | 9.2.5.2 | Osutustoimingu tühistamine | A | M | Puutesisendiga toimingute käivitumise ja tühistamise hindamine eeldab manuaalset kontrolli. |
| 2.5.3 | 9.2.5.3 | Silt nimes | A | H | Automaatselt saab võrrelda nähtavat silti ja programmset nime, kuid nende vastavuse ja arusaadavuse hindamine eeldab manuaalset kontrolli. |
| 2.5.4 | 9.2.5.4 | Liigutusega aktiveerimine | A | M | Liikumisel põhinevate toimingute ja nende alternatiivide olemasolu hindamine eeldab manuaalset kontrolli. |

## Mõistetatavus

| WCAG | EN 301 549 | Nimetus | Tase | Hindamine | Põhjendus |
|---|---|---|---|---|---|
| 3.1.1 | 9.3.1.1 | Lehekülje keel | A | H | Automaatselt saab tuvastada lehe keele atribuudi olemasolu, kuid selle õigsuse hindamine eeldab manuaalset kontrolli. |
| 3.1.2 | 9.3.1.2 | Tekstiosade keel | AA | H | Automaatselt saab tuvastada keeleatribuutide kasutuse, kuid keelevahetuste korrektsuse hindamine eeldab manuaalset kontrolli. |
| 3.2.1 | 9.3.2.1 | Fookustamine | A | M | Fookuse muutumisel toimuvate ootamatute muudatuste hindamine eeldab manuaalset kontrolli. |
| 3.2.2 | 9.3.2.2 | Sisestamine | A | M | Sisendi muutmisel toimuvate ootamatute tegevuste hindamine eeldab manuaalset kontrolli. |
| 3.2.3 | 9.3.2.3 | Läbivalt ühtne navigeerimine | AA | M | Navigeerimise järjepidevuse hindamine erinevatel lehtedel eeldab manuaalset kontrolli. |
| 3.2.4 | 9.3.2.4 | Läbivalt ühtne määratlus | AA | M | Sama funktsiooniga elementide järjepideva tähistuse hindamine eeldab manuaalset kontrolli. |
| 3.3.1 | 9.3.3.1 | Vea tuvastamine | A | H | Automaatselt saab tuvastada veateadete olemasolu, kuid nende selguse ja arusaadavuse hindamine eeldab manuaalset kontrolli. |
| 3.3.2 | 9.3.3.2 | Sildid või instruktsioonid | A | H | Automaatselt saab tuvastada siltide ja juhiste olemasolu, kuid nende selguse ja piisavuse hindamine eeldab manuaalset kontrolli. |
| 3.3.3 | 9.3.3.3 | Soovitus vea korral | AA | M | Veaparanduste pakkumise selguse ja asjakohasuse hindamine eeldab manuaalset kontrolli. |
| 3.3.4 | 9.3.3.4 | Vigade ennetamine (juriidika, rahandus, andmestikud) | AA | M | Vigade ennetamise mehhanismide olemasolu ja toimivuse hindamine eeldab manuaalset kontrolli. |

## Töökindlus

| WCAG | EN 301 549 | Nimetus | Tase | Hindamine | Põhjendus |
|---|---|---|---|---|---|
| 4.1.1 | 9.4.1.1 | Korrektne märgistus | A | A | Märgistusvigade ja süntaksi korrektsuse kontroll on automatiseeritav. |
| 4.1.2 | 9.4.1.2 | Nimi, roll, väärtus | A | H | Automaatselt saab tuvastada elementide nime, rolli ja väärtuse olemasolu, kuid nende korrektsuse ja kasutatavuse hindamine eeldab manuaalset kontrolli. |
| 4.1.3 | 9.4.1.3 | Olekuteated | AA | H | Automaatselt saab tuvastada staatusteavituste märgistuse, kuid nende edastamise ja arusaadavuse hindamine eeldab manuaalset kontrolli. |
