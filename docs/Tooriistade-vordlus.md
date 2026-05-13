# Tööriistade võrdlus

Tabelis võrreldakse valitud ligipääsetavuse hindamise tööriistu nende WCAG 2.1 A- ja AA-taseme edukriteeriumite põhjal, mille hindamist on võimalik automaatsete tööriistadega täielikult või osaliselt toetada.

Linnuke tähendab, et tööriist tuvastas nõuet rikkuva testjuhtumi. Tühi lahter tähendab, et tööriist rikkumist ei tuvastanud või tulemus ei olnud piisavalt selge.

## Tööriistade lühendid

- **W** – WAVE
- **LH** – Lighthouse
- **ST** – Silktide Inspector Extension
- **AI** – Accessibility Insights for Web

**Tabel on täiendamisel**

| Kriteerium | W | LH | ST | AI | Tulemuse kirjeldus | Soovitus |
|---|---|---|---|---|---|---|
| 1.1.1 Mittetekstiline sisu | ✓ | ✓ | ✓ | ✓ | Kõik tööriistad tuvastasid alt-teksti olemasolu või puudumise. Alternatiivteksti sisuline sobivus vajab manuaalset hindamist. | WAVE |
| 1.3.1 Teave ja seosed | ✓ | ✓ | ✓ |  | WAWE, Silktide ja Lighthouse tuvastasid, et vormil on silt, et seotud andmeväljad on grupeeritud, et tabel on õige struktuuriga. Samuti tuvastasid kui nendega oli probleeme. | WAVE |
| 1.3.2 Tähenduslik järjestus | ✓ |  | ✓ | ✓ | WAVE, Silktide ja Insights toetasid struktuuri või navigeerimisjärjestuse visualiseerimist. Silktide’i sisseehitatud ekraanilugeja võimaldas kontrollida ka mitteinteraktiivsete elementide esitamise järjekorda. | Silktide |
| 1.3.5 Sisestuse eesmärgi tuvastamine |  |  |  |  | Ükski valitud tööriist ei tuvastanud `autocomplete` elemendi olemasolu ega puudumist. Manuaalselt tuleb kontrollida nii atribuudi olemasolu kui ka seda, kas selle väärtus vastab sisendvälja tegelikule otstarbele. | Puudub |
| 1.4.3 Kontrastsus (miinimumnõue) | ✓ | ✓ | ✓ | ✓ | Kõik tööriistad tuvastasid teksti ja tausta ebapiisava kontrastsuse. | WAVE |
| 1.4.4 Teksti suuruse muutmine |  |  |  |  |  |  |
| 1.4.5 Pildivormingus tekst |  |  |  |  |  |  |
| 1.4.10 Ümberpaigutus |  |  |  |  |  |  |
| 1.4.11 Mittetekstilise sisu kontrastsus | ✓ |  |  |  | WAVE tuvastas kontrastsuse probleemi. Teised tööriistad mitte. | WAVE |
| 1.4.12 Teksti vahekaugus |  |  |  |  |  |  |
| 2.1.1 Klaviatuur | ✓ |  |  |  | WAVE tuvastas, et halva näite nupp ei pruugi olla ligipääsetav. Lighthouse andis üldise info manuaalse kontrolli vajaduse kohta, aga automaatselt probleemi ei tuvastanud. | WAVE |
| 2.2.1 Ajalimiidi muudetavus |  |  |  |  | Valitud tööriistad ei tuvastanud automaatselt ajapiiranguid. |  |
| 2.2.2 Ajutine katkestamine, peatamine, peitmine |  |  | ✓ |  | Silktide tuvastas liikuva sisu. | Silktide |
| 2.4.1 Sisuplokkide vahelejätmine | ✓ |  | ✓ |  | WAVE ja Silktide tuvastasid "Liigi põhisisu juurde" lingi ning erinevad maamärgid (`landmark`). Silktide tuvastas ka halva näite `iframe`'i sees oleva antud edukriteeriumi rikkumise. Lighthouse tuvastas `main` maamärgi olemasolu ja mitteolemasolu, aga põhisisu juurde lingi olemasolu kontroll anti standardse soovitusena.  | Silktide |
| 2.4.2 Lehe tiitel | ✓ | ✓ | ✓ | ✓ | Kõik valitud tööriistad tuvastasid tiitli puudumise. | WAVE |
| 2.4.3 Fookustamise järjekord | ✓ | ✓ | ✓ | ✓ | Kõik valitud tööriistad tuvastasid positiivse `tabindex`i olemasolu. WAVE, Silktide ja Insights näitavad fookustamise järjekorda visuaalselt | WAVE |
| 2.4.4 Lingi otstarve (kontekstis) | ✓ |  | ✓ |  | WAVE ja Silktide tuvastasid kahtlase nimega lingi, aga vaid ingliskeelse. | WAVE |
| 2.4.6 Pealkirjad ja sildid | ✓ | ✓ |  |  | WAVE tuvastas siltide ja pealkirjade olemasolu ja mitteolemasolu. Lighthouse tuvastas siltide puudumise. Silktide puudumist ei tuvastanud, andis vaid soovituse käsitsi pealkirjade ja siltide sobivust kontrollida. | WAVE |
| 2.5.3 Silt nimes | ✓ |  |  |  | WAVE kuvas nupu juures selle ligipääsetava nimetuse, mistõttu oli nähtava sildi ja ligipääsetava nime võrdlemine lihtne. Teised valitud tööriistad ei andnud selle kontrollimiseks sama selget indikatsiooni. | WAVE |
| 3.1.1 Lehekülje keel | ✓ | ✓ | ✓ | ✓ | Kõik valitud tööriistad tuvastasid `lang`-atribuudi puudumise. WAVE, Silktide ja Insights tuvastasid ka ebakorrektse keeleparameetri. | WAVE |
| 3.1.2 Tekstiosade keel | ✓ |  |  |  | WAVE tuvastas teksisisese `lang`-atribuudi. | WAVE |
| 3.3.1 Vea tuvastamine | ✓ |  |  |  | WAVE tuvastas veateate märgistuse olemasolu, mis aitab kontrollida, kas vigane väli on programmiliselt eristatav. | WAVE |
| 3.3.2 Sildid või instruktsioonid | ✓ |  | ✓ |  | WAVE ja Silktide tuvastasid veateate sildi puudumise. | WAVE |
| 4.1.1 Korrektne märgistus |  |  |  |  |  |  |
| 4.1.2 Nimi, roll, väärtus |  |  |  |  |  |  |
| 4.1.3 Olekuteated |  |  |  |  |  |  |