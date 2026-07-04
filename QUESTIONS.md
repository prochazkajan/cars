# Autová matematika — přehled úloh (v0.2)

Dokument pro rodiče. Popisuje oba herní režimy, rozsahy čísel a pravidla.
Hra je pro **6leté dítě**; cílem je klid a radost ze sbírky aut, ne rychlost.
Žádné časovače, hvězdičky ani pořadí.

Vizuál a chování vychází z předlohy **„Cars Math"** (klidný zelený design,
maskot **Racer**).

---

## Společná pravidla

- **Čekací pauza (2–3 s):** po zadání úlohy je obrazovka zklidněná a tlačítka
  „odpočívají"; maskot napovídá *„přemýšlej…"*. Pak se rozsvítí a lze odpovídat.
  Dítě se učí chvíli přemýšlet, ne mačkat naslepo.
- **Správná odpověď** = do garáže přijedou autíčka (počet = výsledek úlohy) a
  sbírka **Garáž** naroste.
- **Chyba se netrestá:** *„Skoro! Zkus to ještě jednou — máš na to čas."*
  Stejná úloha zůstane, dítě zkusí znovu. Nic se neodečítá.
- **Po správné odpovědi** se hra ptá *„Chceš, aby byl další příklad těžší?"*:
  **Ano, těžší** / **Další** / **Dost na dnešek →** (ukončí den).
- **Konec dne:** noční obrazovka *„Garáž se zavírá. Dnes k nám přijelo N autíček!"*
  a tlačítko **Zpět do garáže**.
- **Sbírka aut se ukládá** a roste napříč hraními (localStorage).

---

## Režim 1 — ➕ Příklady (sčítání a odčítání)

Příklad `a + b = ?` nebo `a − b = ?`, dítě vybírá ze **4 velkých tlačítek**.
Odčítání je vždy nezáporné (větší číslo první). Výsledek je nejméně 2.

| Obtížnost | Rozsah | Výsledek |
|-----------|--------|----------|
| **Lehčí** (výchozí) | `a`, `b` do 9 | do 20 |
| **Těžší** | jedno číslo **10–19**, druhé 2–9 | do 30 |

Tlačítko **Spočítat autíčka** kdykoli zobrazí obě čísla znázorněná autíčky
(pro názornou kontrolu). Obtížnost volí dítě přes „Ano, těžší".

---

## Režim 2 — 🚗 Autíčka (počítání)

Na obrazovce je skupina autíček různých barev; dítě vybere jejich **počet**
ze 4 tlačítek.

| Obtížnost | Počet aut |
|-----------|-----------|
| **Lehčí** (výchozí) | 3–6 |
| **Těžší** | 7–12 |

---

## Maskot Racer

Zelené závodní autíčko s obličejem. Nálady: **normal** (na úvod a při přemýšlení),
**smile** / **cool** (radost ze správné odpovědi — někdy si nasadí brýle),
**sleepy** (noční obrazovka, „z z z").

---

## Rodičovský panel

Ikona ozubeného kola → zadej **17**. Zobrazí počet nasbíraných autíček a nabídne
**Vymazat garáž** (vynuluje sbírku).

*Verze: v0.2*
