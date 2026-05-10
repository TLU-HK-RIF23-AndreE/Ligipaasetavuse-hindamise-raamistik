# Tööriistade võrdlus

Tabelis võrreldakse valitud ligipääsetavuse hindamise tööriistu WCAG 2.1 A- ja AA-taseme edukriteeriumitega seotud testjuhtude põhjal.

Tähised:
- **J** – tööriist tuvastas nõuet rikkuva näite.
- **E** – tööriist ei tuvastanud nõuet rikkuvat näidet.
- **O** – tööriist tuvastas mõne tehnilise tunnuse, kuid lõplik hindamine vajab manuaalset kontrolli.

| Kriteerium | Testjuhtumi eesmärk | WAVE | Lighthouse | Silktide | Insights | Tähelepanek | Soovitus |
|---|---|---|---|---|---|---|---|
| 1.1.1 Mittetekstiline sisu | Alt-teksti olemasolu ja puudumise tuvastamine | J | J | J | J | Kõik tööriistad tuvastasid alt-teksti olemasolu või puudumise. Alternatiivteksti sisuline sobivus vajab manuaalset hindamist. | WAVE |
| 1.3.1 Teave ja seosed | Vormisiltide, seotud andmeväljade ja tabelistruktuuri kontroll | J | J | J | J | Tööriistad tuvastasid mitu struktuuriprobleemi, kuid puuduvat tabelipäist ei tuvastatud. | WAVE |
| 1.3.2 Tähenduslik järjestus | Lehe struktuuri ja navigeerimisjärjestuse visualiseerimine | J | E | J | J | WAVE, Silktide ja Insights aitavad struktuuri visualiseerida, kuid järjestuse loogilisus vajab manuaalset hindamist. | Insights |
| 1.3.5 Sisestuse eesmärgi tuvastamine | `autocomplete` atribuudi olemasolu või puudumise kontroll | E | E | E | E | Ükski tööriist ei tuvastanud `autocomplete` atribuudi olemasolu ega puudumist. | Puudub |