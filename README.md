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
| `statsskicket/magdalena-andersson-c-och-v.html` | `output/lasmaterial/2026-09-18-sa-kan-magdalena-andersson-makla-fred-mellan-c-och-v.md` | `.claude/skills/hamta-dn-artikel-win/bygg-html.py` |
