# Erika Fashion · Podzim 2026 — co naskladnit

**Live:** https://patrikpilous-dev.github.io/erikafashion-podzim/

Nákupní a SEO analýza pro sezónu září–listopad 2026.

## Zdroje dat
- **Shoptet objednávky** — 15 měsíců (2025-05-03 → 2026-08-05), 130 540 objednávek,
  včetně celého podzimu 2025 jako baseline
- **Katalog** — productsComplete.xml (produkty, kategorie, 16 filtrových atributů)
- **Ahrefs CZ** — 385 keywordů podzimních kategorií (brand-clean, dámské: 314 kw / 320 910 volume)
- **Módní magazíny** — Vogue, Elle, Who What Wear, Marie Claire, W Magazine, WWD, Pantone,
  FashionUnited + české zdroje (22 trendů AW26)

## 10 sekcí
1. **TOP 25 doporučení** — nákup, parametry, barvy, atributy, timing, objem, nové segmenty
2. Podzim 2025 baseline — kategorie + sezónní index + vrátkovost
3. Nástup sezóny — týdenní křivky + kdy naskladnit
4. Atributy s nejvyšším podzimním indexem
5. **Parametry podle kategorie** — „Šaty → dlouhé → dlouhý rukáv"
6. Gap analýza: hledanost vs. sortiment
7. Projekce podzimu 2026 (růstový faktor z YoY)
8. Meziroční růst kategorií
9. Trendy AW26 z magazínů
10. Nové segmenty — kam expandovat

## Generování
```bash
cd "C:\Users\patri\Claude Code ukládané soubory"
python erikafashion_prepare.py            # jen při novém exportu objednávek
python erikafashion_podzim_dashboard.py
```
