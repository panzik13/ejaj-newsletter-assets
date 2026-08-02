# CLAUDE.md

## POVINNÉ: shrnutí na konci každého delšího běhu (trvalé pravidlo Petra, 2. 8. 2026)
Po každém delším běhu — a po JAKÉKOLI změně kódu, dat, konfigurace, nasazení
nebo externí služby — zakonči odpověď blokem vizuálně jasně odděleným od zbytku
textu. Vždy na KONCI odpovědi. Prázdné sekce vynech (kromě „Co jsem udělal").

```
---
## 📋 SHRNUTÍ BĚHU

**❌ Nepovedlo se:** co selhalo nebo jakou část zadání jsem vůbec nešáhl a proč.
Stojí PRVNÍ, když existuje. Nikdy nezamlčet ani neschovat mezi rizika.

**Co jsem udělal:** 2–5 odrážek, celé věty, konkrétně.

**Co se změnilo:** soubory, data, konfigurace.

**⚠️ Šlo ven:** push, deploy, odeslaný e-mail, zápis do produkční DB, změna cronu,
volání externího API — cokoli nevratného nebo viditelného mimo tenhle stroj.
Samostatný řádek, ať to nemůže zapadnout. Když nic ven nešlo, sekci vynech.

**Ověřeno:** čím konkrétně (test, běh, screenshot, log) — a co ověřeno NENÍ.

**Nedodělané / rizika:** co zbývá, co může selhat.

**Co potřebuju od tebe:** rozhodnutí, přístup, klik — nebo sekci vynech.
---
```

- **Délka roste s rozsahem.** Krátký běh tři řádky, velký klidně patnáct. Měřítko
  není počet řádků, ale jestli Petr po přečtení ví, co má zkontrolovat.
- **Identifikátory jen u věcí, které šly ven** — čísla PR, ID běhů workflow, jména
  cronů, hashe pushnutých commitů. Lokální úpravy stačí popsat slovy.
- **Pravdivost před vyzněním.** Co není ověřené, se tak napíše. Žádné „hotovo"
  bez důkazu z téhle session.
- U triviálních jednokrokových odpovědí (dotaz, oprava překlepu) shrnutí NEDĚLAT.
