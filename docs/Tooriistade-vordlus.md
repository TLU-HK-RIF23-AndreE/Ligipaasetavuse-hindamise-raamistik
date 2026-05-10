## Tööriistade võrdlustabel

Tabelis on esitatud, millised testitud tööriistad tuvastasid WCAG 2.1 edukriteeriumitega seotud nõuet rikkuvad näited. Linnuke tähistab, et tööriist tuvastas vastava testjuhtumi rikkumise. Tühi lahter tähendab, et tööriist rikkumist ei tuvastanud või ei andnud selle kohta piisavalt selget tulemust.

Tabelis kasutatakse järgmisi tööriistade lühendeid:

- **W** – WAVE
- **LH** – Lighthouse
- **ST** – Silktide Inspector Extension
- **AI** – Accessibility Insights for Web

| Kriteerium | W | LH | ST | AI | Tulemuse kirjeldus | Soovitus |
|---|---|---|---|---|---|---|
| 1.1.1 Mittetekstiline sisu | ✅ | ✅ | ✅ | ✅ | Kõik tööriistad tuvastasid alt-teksti olemasolu või puudumise. Alternatiivteksti sisuline sobivus vajab manuaalset hindamist. | WAVE |
| 1.3.5 Sisestuse eesmärgi tuvastamine |  |  |  |  | Ükski tööriist ei tuvastanud `autocomplete` atribuudi olemasolu ega puudumist. | Puudub |
| 1.4.11 Mittetekstilise sisu kontrastsus | ✅ |  |  |  | WAVE tuvastas CSS-iga tehtud ikooni madala kontrastsuse, kuid kriteerium vajab siiski manuaalset hindamist. | WAVE |