# Autová matematika 🚗

Klidná matematická hra pro **6letého předškoláka / prvňáčka**, který má rád
**auta a počítání**. Za každou správnou odpověď přijedou do garáže autíčka —
sbírka roste. Žádné časovače, žádné blikání, žádné odměny za rychlost.

Vizuální styl a chování vychází z předlohy **„Cars Math"** (klidný zelený
„zahradní/garážový" design, maskot **Racer** — usměvavé zelené závodní autíčko).

## Dva režimy (výběr na úvodní obrazovce)

- **➕ Příklady** — sčítání a odčítání. Po každém vyřešeném příkladu se hra ptá
  *„Chceš, aby byl další příklad těžší?"* → **Lehčí** (čísla do 9, výsledek do 20)
  nebo **Těžší** (jedno číslo 10–19). Tlačítko **Spočítat autíčka** kdykoli
  ukáže příklad znázorněný autíčky.
- **🚗 Autíčka** — počítání: na obrazovce je 3–12 autíček, dítě vybere správný
  počet. **Lehčí** = 3–6 aut, **Těžší** = 7–12 aut.

Obě hry mají stejný klid: **2–3 s pauza** („přemýšlej…", obrazovka i tlačítka
odpočívají), pak se rozsvítí. Chyba se netrestá — *„Skoro! Zkus to ještě jednou
— máš na to čas."* a stejný úkol zůstane. Konec kdykoli přes **Dost na dnešek →**;
následuje klidná noční obrazovka *„Garáž se zavírá."*

## Spuštění

Jediný soubor [`index.html`](index.html) — otevři v prohlížeči (ideálně tablet).
Sbírka aut se ukládá do prohlížeče (`localStorage`) a **roste napříč hraními**;
bez `localStorage` hra funguje také, jen se postup neuloží. Fonty (Baloo 2,
Nunito) se načítají z Google Fonts; offline se použije systémové zaoblené písmo.

Hostování přes **GitHub Pages** (Settings → Pages → větev `main`, kořen):
`https://prochazkajan.github.io/cars/`.

## Rodičovský panel

Ikona ozubeného kola vpravo nahoře → zadej **17**. Ukáže počet nasbíraných
autíček a umožní **Vymazat garáž**.

Přehled typů úloh: [`QUESTIONS.md`](QUESTIONS.md).

---
*v0.2 — touch-first, český UI, min. velikost tlačítek 56 px.*
