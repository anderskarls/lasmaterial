# Läsmaterial

Elevriktat material som behöver läsas i en webbläsare, publicerat via GitHub Pages.

**Adress:** https://anderskarls.github.io/lasmaterial/

## Vad som får ligga här

Repot är **publikt**. Bara sådant som är avsett för elevernas ögon läggs in:

- bearbetat läsmaterial med lässtöd
- momentöversikter
- fristående elevverktyg i HTML

## Vad som aldrig får läggas här

- `elevdata/` i någon form, inklusive pseudonymiserad
- `raw/` - elevinlämningar, personliga anteckningar, lektionsreflektioner
- lärarmaterial: lektionsplaner, talarnoter, bedömningsunderlag
- allt som är märkt `[VERIFIERA]` och ännu inte kontrollerat

Filerna genereras i vaultet (`C:\Brain`) och kopieras hit. **Vaultet självt ska aldrig pushas till det här repot.** Redigera inte HTML-filerna här - ändra i källan och kopiera om, annars glider versionerna isär.

## Källor

| Sida | Byggs ur | Med |
|---|---|---|
| `israel-palestina/tidslinjen.html` | `output/lessons/Samhällskunskap/Israel och Palestina/lasmaterial-tidslinjen.md` | `.claude/skills/hamta-dn-artikel-win/bygg-html.py` |
| `israel-palestina/ir-teorier.html` | `output/lessons/Samhällskunskap/Israel och Palestina/lasmaterial-ir-teorier.md` | `.claude/skills/hamta-dn-artikel-win/bygg-html.py` (genre: forfattad) |
| `israel-palestina/osloavtalen.html` | `output/lessons/Samhällskunskap/Israel och Palestina/lasmaterial-osloavtalen.md` | `.claude/skills/hamta-dn-artikel-win/bygg-html.py` (genre: primarkalla) |
| `statsskicket/magdalena-andersson-c-och-v.html` | `output/lasmaterial/2026-09-18-sa-kan-magdalena-andersson-makla-fred-mellan-c-och-v.md` | `.claude/skills/hamta-dn-artikel-win/bygg-html.py` |
| `statsskicket/magdalena-andersson-c-och-v-lattlast.html` | `output/lasmaterial/2026-09-18-sa-kan-magdalena-andersson-makla-fred-mellan-c-och-v-lattlast.md` | `.claude/skills/hamta-dn-artikel-win/bygg-html.py` |
| `israel-palestina/vem-styr-gaza.html` | `output/lasmaterial/2026-09-24-hamas-regering-i-gaza-avgar-men-ministrarna-sitter-kvar.md` | `.claude/skills/hamta-dn-artikel-win/bygg-html.py` |
| `israel-palestina/dodlaget-i-gaza.html` | `output/lasmaterial/2026-09-24-expert-dodlage-i-gaza-riskerar-att-vara-i-tio-ar.md` | `.claude/skills/hamta-dn-artikel-win/bygg-html.py` |
| `israel-palestina/tabut-mot-hamas.html` | `output/lasmaterial/2026-10-01-nathan-shachar-usas-tabu-mot-hamas-kontakter-brutet.md` | `.claude/skills/hamta-dn-artikel-win/bygg-html.py` |
| `israel-palestina/trump-och-iran.html` | `output/lasmaterial/2026-09-24-trump-och-iran-fast-i-ett-lagintensivt-krig.md` | `.claude/skills/hamta-dn-artikel-win/bygg-html.py` |
| `antiken/fyra-roster-ur-aten.html` | `output/lessons/Historia/Antiken - framsteg för vem/lasmaterial-fyra-roster-ur-aten.md` | `.claude/skills/hamta-dn-artikel-win/bygg-html.py` (genre: forfattad) |
| `antiken/fyra-roster-ur-rom.html` | `output/lessons/Historia/Antiken - framsteg för vem/kallmaterial-lektion-4-bearbetad.md` | `resources/lasmaterial-stationer/bygg-stationshafte.py` |
