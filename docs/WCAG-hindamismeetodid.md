# WCAG edukriteeriumite hindamismeetodite tabel

Tabelis on WCAG 2.1 A ja AA taseme edukriteeriumid seostatud EN 301 549 nõuetega ning määratud soovituslik hindamismeetod.

**Hindamise tähised:** `A` – automaatne, `M` – manuaalne, `H` – hübriidne.

## Tajutavus

| WCAG | EN 301 549 | Nimetus | Tase | Hindamine | Põhjendus |
|---|---|---|---|---|---|
| 1.1.1 | 9.1.1.1 | Non-text Content | A | H | Näiteks alt atribuudi olemasolu saab kontrollida automaatselt, aga sisus tuleb hinnata manuaalselt. |
| 1.2.1 | 9.1.2.1 | Audio-only and Video-only (Prerecorded) | A | H | Automaatselt saab tuvastada struktuurielementide olemasolu, manuaalselt tuleb hinnata sisu kvaliteeti ja tähendust. |
| 1.2.2 | 9.1.2.2 | Captions (Prerecorded) | A | H | Automaatselt saab tuvastada subtiitrite olemasolu, manuaalselt tuleb hinnata vastavust ja kasutatavust. |
| 1.2.3 | 9.1.2.3 | Audio Description or Media Alternative (Prerecorded) | A | H | Automaatselt saab tuvastada struktuuri või alternatiivide olemasolu, manuaalselt sisulist vastavust. |
| 1.2.4 | 9.1.2.4 | Captions (Live) | AA | H | Automaatselt saab tuvastada subtiitrite olemasolu, manuaalselt tuleb hinnata vastavust ja kasutatavust. |
| 1.2.5 | 9.1.2.5 | Audio Description (Prerecorded) | AA | H | Automaatselt saab tuvastada audiokirjelduse olemasolu, manuaalselt tuleb hinnata sisulist vastavust. |
| 1.3.1 | 9.1.3.1 | Info and Relationships | A | H | Automaatselt saab tuvastada struktuurielementide olemasolu, manuaalselt tuleb hinnata semantilist korrektsust ja sisu tähendust. |
| 1.3.2 | 9.1.3.2 | Meaningful Sequence | A | H | Automaatselt saab tuvastada DOM-järjestuse, manuaalselt tuleb hinnata selle loogilisust. |
| 1.3.3 | 9.1.3.3 | Sensory Characteristics | A | M | Sensoorsele tajule tugimenise tuvastamine ja selle arusaadavuse hindamine eeldab manuaalset kontrolli. |
| 1.3.4 | 9.1.3.4 | Orientation | AA | H | Automaatselt saab tuvastada orientatsiooni piiranguid, erinevate seadmete kasutusolukordade hindamine eeldab manuaalset kontrolli. |
| 1.3.5 | 9.1.3.5 | Identify Input Purpose | AA | H | Automaatselt saab tuvastada sisendväljade atribuutide olemasolu, korrektne kasutus ja eesmärgile vastavus eeldab manuaalset kontrolli. |
| 1.4.1 | 9.1.4.1 | Use of Color | A | M | Automaatselt saab tuvastada värvikasutust ja kontraste, selle tähenduse ja sõltuvuse hindamine eeldab manuaalset kontrolli. |
| 1.4.2 | 9.1.4.2 | Audio Control | A | H | Automaatselt saab tuvastada automaatselt käivituvat heli, selle peatamise või reguleerimise võimaluse hindamine eeldab manuaalset kontrolli. |
| 1.4.3 | 9.1.4.3 | Contrast (Minimum) | AA | H | Automaatselt saab mõõta värvikontrasti, kuid kõigi kasutuskordade ja visuaalse esituse vastasuse hindamine eeldab manuaalset kontrolli. |
| 1.4.4 | 9.1.4.4 | Resize Text | AA | H | Automaatselt saab tuvastada teksti suurendamisega seotud tehnilisi piiranguid, selle toimivuse hindamine eeldab manuaalset kontrolli. |
| 1.4.5 | 9.1.4.5 | Images of Text | AA | H | Automaatselt saab tuvastada pildielemente, kuid tekstina esitatud info vajalikkuse ja sobivuse hindamine eeldab manuaalset kontrolli. |
| 1.4.10 | 9.1.4.10 | Reflow | AA | H | Automaatselt saab tuvastada võimalikke paigutuse piiranguid, kuid sisu kohandumise ja kasutatavuse hindamine erinevate ekraanisuuruste korral eeldab manuaalset kontrolli. |
| 1.4.11 | 9.1.4.11 | Non-text Contrast | AA | H | Automaatselt saab mõõta mitte-tekstiliste elementide kontrasti, kuid nende tähenduse ja visuaalse eristatavuse hindamine eeldab manuaalset kontrolli. |
| 1.4.12 | 9.1.4.12 | Text Spacing | AA | H | Automaatselt saab tuvastada tekstivahedega seotud stiilipiiranguid, kuid sisu loetavuse ja toimivuse hindamine muudetud vahede korral eeldab manuaalset kontrolli. |
| 1.4.13 | 9.1.4.13 | Content on Hover or Focus | AA | H | Automaatselt saab tuvastada hover- või fookusolekuga seotud elemente, kuid nende käitumise ja kasutatavuse hindamine eeldab manuaalset kontrolli. |

## Kasutatavus

| WCAG | EN 301 549 | Nimetus | Tase | Hindamine | Põhjendus |
|---|---|---|---|---|---|
| 2.1.1 | 9.2.1.1 | Keyboard | A | H | Klaviatuuriga navigeerimise ja funktsionaalsuse toimivuse hindamine eeldab manuaalset kontrolli. |
| 2.1.2 | 9.2.1.2 | No Keyboard Trap | A | M | Klaviatuurilõksu olemasolu ja sellest väljumise võimaluse hindamine eeldab manuaalset kontrolli. |
| 2.1.4 | 9.2.1.4 | Character Key Shortcuts | A | H | Automaatselt saab tuvastada võimalikke kiirklahve, kuid nende konflikti, väljalülitamise või ümbermääramise võimaluse hindamine eeldab manuaalset kontrolli. |
| 2.2.1 | 9.2.2.1 | Timing Adjustable | A | H | Automaatselt saab tuvastada ajapiirangute olemasolu, kuid nende kohandamise ja kasutatavuse hindamine eeldab manuaalset kontrolli. |
| 2.2.2 | 9.2.2.2 | Pause, Stop, Hide | A | H | Automaatselt saab tuvastada liikuvat või automaatselt uuenevat sisu, kuid selle peatamise, peatamise toimivuse ja kasutatavuse hindamine eeldab manuaalset kontrolli. |
| 2.3.1 | 9.2.3.1 | Three Flashes or Below Threshold | A | H | Automaatselt saab tuvastada vilkumise sagedust, kuid selle visuaalse mõju ja kasutaja ohutuse hindamine eeldab manuaalset kontrolli. |
| 2.4.1 | 9.2.4.1 | Bypass Blocks | A | H | Automaatselt saab tuvastada navigeerimis- ja ankruelementide olemasolu, kuid nende toimivuse ja kasutatavuse hindamine eeldab manuaalset kontrolli. |
| 2.4.2 | 9.2.4.2 | Page Titled | A | H | Automaatselt saab tuvastada lehe pealkirja olemasolu, kuid selle asjakohasuse ja kirjeldavuse hindamine eeldab manuaalset kontrolli. |
| 2.4.3 | 9.2.4.3 | Focus Order | A | H | Automaatselt saab tuvastada fookusjärjestuse DOM-is, kuid selle loogilisuse ja kasutatavuse hindamine eeldab manuaalset kontrolli. |
| 2.4.4 | 9.2.4.4 | Link Purpose (In Context) | A | H | Lingi eesmärgi arusaadavuse hindamine kontekstis eeldab manuaalset kontrolli. |
| 2.4.5 | 9.2.4.5 | Multiple Ways | AA | M | Mitme ligipääsutee olemasolu ja nende piisavuse hindamine eeldab manuaalset kontrolli. |
| 2.4.6 | 9.2.4.6 | Headings and Labels | AA | H | Automaatselt saab tuvastada pealkirjade ja siltide olemasolu, kuid nende kirjeldavuse ja arusaadavuse hindamine eeldab manuaalset kontrolli. |
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
| 4.1.2 | 9.4.1.2 | Name, Role, Value | A | H | Automaatselt saab tuvastada nime, rolli ja väärtuse olemasolu, kuid nende korrektsuse ja kasutatavuse hindamine eeldab manuaalset kontrolli. |
| 4.1.3 | 9.4.1.3 | Status Messages | AA | H | Automaatselt saab tuvastada staatusteavituste märgistuse, kuid nende edastamise ja arusaadavuse hindamine eeldab manuaalset kontrolli. |
