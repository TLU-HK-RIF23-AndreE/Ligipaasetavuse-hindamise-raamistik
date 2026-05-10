# Veebilehe ligipääsetavuse hindamise töövoog

See repositoorium sisaldab lõputöö "Veebilehe ligipääsetavuse hindamise töövoo väljatöötamine" käigus koostatud materjale. Töö eesmärk on toetada veebilehe ligipääsetavuse süsteemset hindamist WCAG 2.1 A- ja AA-taseme edukriteeriumite alusel, kombineerides automaatseid tööriistu ja manuaalset hindamist.

## Repositooriumi sisu

- `docs/WCAG-hindamismeetodid.md` – WCAG 2.1 A- ja AA-taseme edukriteeriumite klassifitseerimine automaatse, manuaalse ja hübriidse hindamise alusel.
- `docs/Tooriistade-vordlus.md` – valitud ligipääsetavuse hindamise tööriistade võrdlustabel.
- `docs/Toovoog.md` – veebilehe ligipääsetavuse hindamise töövoog ja praktiline hindamistabel.
- `index.html` – HTML-näidisleht, mida kasutati tööriistade testimiseks.

## Kuidas töövoogu kasutada?

Töövoog on mõeldud veebilehe esmaseks ja süsteemseks ligipääsetavuse hindamiseks. Hindamisel tuleks liikuda järjest järgmiste etappide kaudu.

### 1. Tee automaatne esmane kontroll

Alusta hindamist automaatsete tööriistadega, näiteks WAVE, Lighthouse, Silktide Inspector või Accessibility Insights for Web. Automaatne kontroll aitab kiiresti tuvastada tehnilisi probleeme, näiteks puuduvad alternatiivtekstid, ebapiisav kontrastsus, puuduvad vormiväljade sildid või probleemid ARIA atribuutidega.

Automaatsete tööriistade tulemusi tuleb käsitleda esmase sisendina, mitte lõpliku hinnanguna.

### 2. Kontrolli hübriidsed edukriteeriumid manuaalselt üle

Hübriidsete edukriteeriumite puhul saab automaatne tööriist tuvastada ainult osa probleemist. Näiteks võib tööriist leida, kas pildil on `alt`-atribuut olemas, kuid inimene peab hindama, kas alternatiivtekst annab edasi pildi tähenduse ja eesmärgi.

Seetõttu tuleb automaatse kontrolli tulemus hübriidsete kriteeriumite puhul alati manuaalselt üle vaadata.

### 3. Hinda manuaalset kontrolli vajavad edukriteeriumid

Manuaalsete edukriteeriumite puhul tuleb veebilehte kontrollida tegeliku kasutamise kaudu. Näiteks tuleb testida klaviatuuriga navigeerimist, fookuse nähtavust, fookusjärjestuse loogilisust, juhiste arusaadavust, veateadete selgust ning audio- ja videosisu alternatiivide kvaliteeti.

Manuaalne hindamine võib hõlmata ka ekraanilugeja või muu tugitehnoloogia kasutamist.

## Märkus

Tööriistasoovitusi ei tule käsitleda ainsa võimaliku lahendusena. Hindaja võib vajaduse korral kasutada ka teisi tööriistu. Automaatsete tööriistade tulemusi tuleb tõlgendada vastava WCAG edukriteeriumi kontekstis ning vajaduse korral täiendada manuaalse kontrolliga.

## Töövoo kasutamine praktikas

Töövoogu saab kasutada veebilehe ligipääsetavuse esmaseks hindamiseks või olemasoleva hindamisprotsessi täiendamiseks. Hindamist on soovitatav alustada automaatsetest kontrollidest ning seejärel liikuda hübriidsete ja manuaalsete kontrollide juurde.

### Automaatne esmane kontroll

Automaatsete tööriistade abil saab kiiresti tuvastada tehnilisi probleeme, näiteks:

- puuduvad alternatiivtekstid;
- ebapiisav kontrastsus;
- puuduvad vormiväljade sildid;
- vigane HTML- või ARIA-märgistus.

Automaatse kontrolli tulemus ei ole lõplik hinnang. Tööriista tulemust tuleb kontrollida vastava WCAG edukriteeriumi sisust lähtudes.

### Hübriidsete kriteeriumite kontroll

Hübriidsete kriteeriumite puhul saab tööriist kontrolli toetada, kuid lõplik hinnang vajab inimese otsust.

Näiteks WCAG 1.1.1 „Mittetekstiline sisu” puhul saab tööriist tuvastada, kas pildil on `alt`-atribuut olemas. Sellest üksi ei piisa, sest inimene peab hindama, kas alternatiivtekst annab edasi pildi tähenduse ja eesmärgi.

Samuti võib tööriist kontrollida, kas lehel on määratud keeleatribuut, näiteks `lang="et"`, kuid hindaja peab kontrollima, kas määratud keel vastab tegelikule sisule.

### Manuaalne kontroll

Manuaalset kontrolli vajavate kriteeriumite puhul tuleb veebilehte kontrollida tegeliku kasutamise kaudu.

Näiteks klaviatuuriga navigeerimise puhul tuleb kontrollida, kas:

- kõik olulised funktsioonid on kasutatavad ilma hiireta;
- fookus liigub loogilises järjekorras;
- fookuses olev element on visuaalselt nähtav;
- kasutaja ei jää klaviatuuriga liikudes lõksu.

Manuaalset hindamist vajavad sageli ka juhiste arusaadavus, veateadete selgus, fookusjärjestuse loogilisus ning audio- ja videosisu alternatiivide kvaliteet.

### Kohaldatavuse hindamine

Kõik WCAG edukriteeriumid ei pruugi iga veebilehe puhul kohalduda. Näiteks kui veebilehel puudub audio- või videosisu, ei ole vaja hinnata neid edukriteeriume, mis puudutavad subtiitreid, transkriptsioone või helikirjeldust.

### Tööriistasoovituste kasutamine

Tööriistasoovitusi ei tule käsitleda ainsa võimaliku lahendusena. Hindaja võib vajaduse korral kasutada ka teisi tööriistu. Automaatsete tööriistade tulemusi tuleb tõlgendada vastava WCAG edukriteeriumi kontekstis ning vajaduse korral täiendada manuaalse kontrolliga.

## Kasutatud tähised

Hindamistabelis kasutatakse järgmisi hindamismeetodi tähiseid:

- **A** – automaatne hindamine;
- **M** – manuaalne hindamine;
- **H** – hübriidne hindamine.

Tööriistade võrdlustabelis kasutatakse järgmisi tähiseid:

- **J** – tööriist tuvastas nõuet rikkuva näite;
- **E** – tööriist ei tuvastanud nõuet rikkuvat näidet;
- **O** – tööriist tuvastas probleemi osaliselt või toetas kontrolli, kuid lõplik hinnang vajab manuaalset kontrolli.