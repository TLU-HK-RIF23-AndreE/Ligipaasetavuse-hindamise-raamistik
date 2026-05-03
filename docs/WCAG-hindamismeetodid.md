# WCAG edukriteeriumite hindamismeetodite tabel

Tabelis on WCAG 2.1 A ja AA taseme edukriteeriumid seostatud EN 301 549 nõuetega ning määratud soovituslik hindamismeetod.

**Hindamise tähised:** `A` – automaatne, `M` – manuaalne, `H` – hübriidne.

## Tajutavus

| WCAG | EN 301 549 | Nimetus | Tase | Hindamine | Põhjendus |
|---|---|---|---|---|---|
| 1.1.1 | 9.1.1.1 | Non-text Content | A | H | Automaatselt tuvastatakse puuduvad `alt`-atribuudid. Manuaalselt kontrollitakse, kas tekst kirjeldab pildi eesmärki (mitte lihtsalt "pilt1.jpg") ja kas dekoratiivsed pildid on märgitud tühja alt-tekstiga (`alt=""`). |
| 1.2.1 | 9.1.2.1 | Audio-only and Video-only (Prerecorded) | A | H | Automaatselt leitakse meediaelemendid. Manuaalselt tuleb kontrollida, et helifailil on täpne tekstiline transkriptsioon ja ainult videopõhisel sisul on kirjeldus, mis annab edasi kogu visuaalse info. |
| 1.2.2 | 9.1.2.2 | Captions (Prerecorded) | A | H | Automaatselt saab kontrollida subtiitrifaili (`<track>`) olemasolu. Manuaalselt tuleb hinnata, kas subtiitrid on sünkroonis ja sisaldavad peale kõne ka olulisi heliefekte ning kõnelejate nimesid. |
| 1.2.3 | 9.1.2.3 | Audio Description or Media Alternative (Prerecorded) | A | H | Automaatselt saab kontrollida kirjelduse märgendite olemasolu. Manuaalselt tuleb veenduda, et kas heliline kirjeldus või täispikk transkriptsioon selgitab kõike visuaalselt olulist, mis helis ei kajastu. |
| 1.2.4 | 9.1.2.4 | Captions (Live) | AA | H | Automaatselt saab tuvastada videomängija võimekus subtiitreid näidata. Manuaalselt tuleb kontrollida ülekande ajal, kas reaalajas tekkiv tekst on piisavalt täpne, loetava viivitusega ja sisaldab olulist helilist infot. |
| 1.2.5 | 9.1.2.5 | Audio Description (Prerecorded) | AA | H | Automaatika saab tuvastada täiendava helirea olemasolu. Manuaalselt tuleb hinnata, kas audiokirjeldus on piisavalt detailne ja sisustatud pauside ajal nii, et see ei segaks peamist dialoogi. |
| 1.3.1 | 9.1.3.1 | Info and Relationships | A | H | Automaatselt saab kontrollida pealkirjade hierarhiat ja vormiväljade seoseid siltidega. Manuaalselt tuleb veenduda, et visuaalne struktuur (nt paks tekst pealkirjana) vastaks semantilisele koodile. |
| 1.3.2 | 9.1.3.2 | Meaningful Sequence | A | H | Automaatselt saab kontrollida DOM-elementide järjekorda. Manuaalselt tuleb (nt CSS-i väljalülitamisega) veenduda, et sisu on loogiliselt loetav ka ilma kujunduseta. |
| 1.3.3 | 9.1.3.3 | Sensory Characteristics | A | M | Manuaalselt tuleb üle vaadata kõik juhised, et need ei toetuks ainult visuaalsetele tunnustele nagu kuju, suurus või asukoht (nt "vajuta paremal asuvat nuppu"). |
| 1.3.4 | 9.1.3.4 | Orientation | AA | H | Automaatselt saab tuvastada koodipõhised vaatepiirangud. Manuaalselt tuleb kontrollida seadet pöörates, et sisu ei lukustuks ühte asendisse ja jääks mõlemas suunas täielikult kasutatavaks. |
| 1.3.5 | 9.1.3.5 | Identify Input Purpose | AA | H | Automaatselt saab tuvastada puuduvad või valed `autocomplete` atribuudid. Manuaalselt tuleb kontrollida, kas need on lisatud kõikidele asjakohastele sisendväljadele ning kas need vastavad välja tegelikule otstarbele, et toetada automaattäitmist ja abitehnoloogiate kasutamist. |
| 1.4.1 | 9.1.4.1 | Use of Color | A | H | Automaatselt on võimalik tuvastada värvikasutusega seotud võimalikke probleeme. Manuaalselt tuleb kontrollida, et värv ei oleks ainus viis teabe edastamiseks. |
| 1.4.2 | 9.1.4.2 | Audio Control | A | H | Automaatselt on võimalik tuvastada automaatselt käivituvat heli. Manuaalselt tuleb kontrollida, kas üle kolme sekundi kestvat heli on võimalik peatada, vaigistada või selle helitugevust reguleerida ilma süsteemi helitugevust muutmata. |
| 1.4.3 | 9.1.4.3 | Contrast (Minimum) | AA | H | Automaatselt on võimalik mõõta teksti ja tausta vahelist värvikontrasti. Kõigi kasutusolukordade ja visuaalsete esituste vastavuse hindamine eeldab manuaalset kontrolli. |
| 1.4.4 | 9.1.4.4 | Resize Text | AA | H | Automaatselt on võimalik tuvastada teksti suurendamist piiravaid tehnilisi tegureid. Manuaalselt tuleb kontrollida, kas teksti on võimalik suurendada kuni 200% ilma sisu või funktsionaalsuse kadumiseta. |
| 1.4.5 | 9.1.4.5 | Images of Text | AA | H | Automaatselt on võimalik tuvastada pildielemente. Manuaalselt tuleb hinnatata, kas pildina esitatud tekstiline info on vajalik või tuleks see esitada tekstina, et tagada parem loetavus ja kohandatavus. |
| 1.4.10 | 9.1.4.10 | Reflow | AA | H | Automaatselt on võimalik tuvastada paigutusega seotud võimalikke piiranguid. Manuaalselt kontrollitakse, kas sisu kohandub ilma horisontaalse kerimiseta ka väiksematel ekraanisuurustel (nt 320 CSS pikslit). |
| 1.4.11 | 9.1.4.11 | Non-text Contrast | AA | H | Automaatselt on võimalik mõõta mitte-tekstiliste elementide kontrasti. Manuaalselt tuleb hinnata nende visuaalset eristatavust ning vastavust nõudele (kontrastsuhe vähemalt 3:1). |
| 1.4.12 | 9.1.4.12 | Text Spacing | AA | H | Automaatselt on võimalik tuvastada tekstivahedega seotud stiilipiiranguid. Manuaalselt tuleb kontrollida, kas sisu jääb loetavaks ja kasutatavaks, kui tekstivahed (nt reavahe, tähevahe) suurenevad vastavalt nõuetele. |
| 1.4.13 | 9.1.4.13 | Content on Hover or Focus | AA | H | Automaatselt on võimalik tuvastada hover- või fookusolekuga seotud elemente, kuid nende käitumise ja kasutatavuse hindamine eeldab manuaalset kontrolli. |

## Kasutatavus

| WCAG | EN 301 549 | Nimetus | Tase | Hindamine | Põhjendus |
|---|---|---|---|---|---|
| 2.1.1 | 9.2.1.1 | Keyboard | A | H | Automaatselt on võimalik tuvastada klaviatuurikasutusega seotud võimalikke probleeme. Manuaalselt tuleb kontrollida, kas kõik interaktiivsed elemendid ja funktsioonid on kasutatavad ainult klaviatuuri abil. |
| 2.1.2 | 9.2.1.2 | No Keyboard Trap | A | M | Klaviatuurilõksu olemasolu ja sellest väljumise võimaluse hindamine eeldab manuaalset kontrolli. |
| 2.1.4 | 9.2.1.4 | Character Key Shortcuts | A | H | Automaatselt on võimalik tuvastada võimalikke ühe märgiga kiirklahve. Manuaalselt tuleb kontrollida, kas neid on võimalik välja lülitada, ümber määrata või kas need toimivad ainult fookuse olemasolul. |
| 2.2.1 | 9.2.2.1 | Timing Adjustable | A | H | Automaatselt on võimalik tuvastada ajapiirangute olemasolu. Manuaalselt tuleb kontrollida, kas kasutajal on võimalik ajapiirangut pikendada, kohandada või see eemaldada. |
| 2.2.2 | 9.2.2.2 | Pause, Stop, Hide | A | H | Automaatselt saab tuvastada liikuvat või automaatselt uuenevat sisu. Manuaalselt tuleb kontrollida, kas kasutajal on võimalik selline sisu peatada, katkestada või peita. |
| 2.3.1 | 9.2.3.1 | Three Flashes or Below Threshold | A | M | Vilkuva sisu olemasolu ja selle mõju kasutajale eeldab manuaalset kontrolli. |
| 2.4.1 | 9.2.4.1 | Bypass Blocks | A | H | Automaatselt saab tuvastada navigeerimis- ja ankruelementide olemasolu, kuid nende toimivuse ja kasutatavuse hindamine eeldab manuaalset kontrolli. |
| 2.4.2 | 9.2.4.2 | Page Titled | A | H | Automaatselt saab tuvastada lehe pealkirja olemasolu, kuid selle asjakohasuse ja kirjeldavuse hindamine eeldab manuaalset kontrolli. |
| 2.4.3 | 9.2.4.3 | Focus Order | A | H | Automaatselt on võimalik tuvastada elementide järjestus koodis. Manuaalselt tuleb hinnata, kas fookus liigub elementide vahel loogilises ja kasutajale arusaadavas järjekorras. |
| 2.4.4 | 9.2.4.4 | Link Purpose (In Context) | A | H | Automaatselt on võimalik tuvastada linkide tehnilisi puudusi. Manuaalselt tuleb hinnata, kas lingi eesmärk on koos kontekstiga kasutajale arusaadav. |
| 2.4.5 | 9.2.4.5 | Multiple Ways | AA | M | Mitme ligipääsutee olemasolu ja nende piisavuse hindamine eeldab manuaalset kontrolli. |
| 2.4.6 | 9.2.4.6 | Headings and Labels | AA | H | Automaatselt on võimalik tuvastada pealkirjade ja siltide olemasolu. Nende kirjeldavuse ja arusaadavuse hindamine eeldab manuaalset kontrolli. |
| 2.4.7 | 9.2.4.7 | Focus Visible | AA | M | Fookuse nähtavuse ja selle piisavuse hindamine eeldab manuaalset kontrolli. |
| 2.5.1 | 9.2.5.1 | Pointer Gestures | A | M | Keerukate puutežestide kasutamise ja nende alternatiivide hindamine eeldab manuaalset kontrolli. |
| 2.5.2 | 9.2.5.2 | Pointer Cancellation | A | M | Puutesisendiga toimingute käivitumise ja tühistamise hindamine eeldab manuaalset kontrolli. |
| 2.5.3 | 9.2.5.3 | Label in Name | A | H | Automaatselt saab võrrelda nähtavat silti ja programmset nime, kuid nende vastavuse ja arusaadavuse hindamine eeldab manuaalset kontrolli. |
| 2.5.4 | 9.2.5.4 | Motion Actuation | A | M | Liikumisel põhinevate toimingute ja nende alternatiivide olemasolu hindamine eeldab manuaalset kontrolli. |

## Mõistetatavus

| WCAG | EN 301 549 | Nimetus | Tase | Hindamine | Põhjendus |
|---|---|---|---|---|---|
| 3.1.1 | 9.3.1.1 | Language of Page | A | H | Automaatselt saab tuvastada lehe keele atribuudi olemasolu, kuid selle õigsuse hindamine eeldab manuaalset kontrolli. |
| 3.1.2 | 9.3.1.2 | Language of Parts | AA | H | Automaatselt saab tuvastada keeleatribuutide kasutuse, kuid keelevahetuste korrektsuse hindamine eeldab manuaalset kontrolli. |
| 3.2.1 | 9.3.2.1 | On Focus | A | M | Fookuse muutumisel toimuvate ootamatute muudatuste hindamine eeldab manuaalset kontrolli. |
| 3.2.2 | 9.3.2.2 | On Input | A | M | Sisendi muutmisel toimuvate ootamatute tegevuste hindamine eeldab manuaalset kontrolli. |
| 3.2.3 | 9.3.2.3 | Consistent Navigation | AA | M | Navigeerimise järjepidevuse hindamine erinevatel lehtedel eeldab manuaalset kontrolli. |
| 3.2.4 | 9.3.2.4 | Consistent Identification | AA | M | Sama funktsiooniga elementide järjepideva tähistuse hindamine eeldab manuaalset kontrolli. |
| 3.3.1 | 9.3.3.1 | Error Identification | A | H | Automaatselt saab tuvastada veateadete olemasolu, kuid nende selguse ja arusaadavuse hindamine eeldab manuaalset kontrolli. |
| 3.3.2 | 9.3.3.2 | Labels or Instructions | A | H | Automaatselt saab tuvastada siltide ja juhiste olemasolu, kuid nende selguse ja piisavuse hindamine eeldab manuaalset kontrolli. |
| 3.3.3 | 9.3.3.3 | Error Suggestion | AA | H | Veaparanduste pakkumise selguse ja asjakohasuse hindamine eeldab manuaalset kontrolli. |
| 3.3.4 | 9.3.3.4 | Error Prevention (Legal, Financial, Data) | AA | M | Vigade ennetamise mehhanismide olemasolu ja toimivuse hindamine eeldab manuaalset kontrolli. |

## Töökindlus

| WCAG | EN 301 549 | Nimetus | Tase | Hindamine | Põhjendus |
|---|---|---|---|---|---|
| 4.1.1 | 9.4.1.1 | Parsing | A | A | Märgistusvigade ja süntaksi korrektsuse kontroll on automatiseeritav. |
| 4.1.2 | 9.4.1.2 | Name, Role, Value | A | H | Automaatselt saab tuvastada elementide nime, rolli ja väärtuse olemasolu, kuid nende korrektsuse ja kasutatavuse hindamine eeldab manuaalset kontrolli. |
| 4.1.3 | 9.4.1.3 | Status Messages | AA | H | Automaatselt saab tuvastada staatusteavituste märgistuse, kuid nende edastamise ja arusaadavuse hindamine eeldab manuaalset kontrolli. |
