[Domů](/README.md) / [Zhodnocení](/Zhodnocení/README.md) 

# Zhodnocení
Pro zhodnocení vhodnosti využití vybraných architektonických stylů, které byly v předchozích kapitolách zdokumentovány, byla využita následující metodika. 

## Metodika hodnocení
Pro každou ze zvolených architektur byla vytvořena hodnotící tabulka. Kritérii hodnocení jsou architektonické charakteristiky, které každý z architektonických stylů určitým způsobem splňuje. Pro každou z těchto charakteristik bylo doplněno hodnocení na ordinální škále podle toho, jaké požadavky by měl výsledný systém splňovat. Dané číselné hodnocení vyjdařuje počet hvězdiček, tj. čím vyšší hodnocení, tím lépe danou charakteristiku daná architektura splňuje. Jelikož nejsou všechny charakteristiky pro navrhovaný systém stejně důležité, byla dále zavedeno i váhové kritérium, vyjadřující, do jaké míry je daná charakteristika zásadní pro celkové hodnocení vhodnosti použití daného architektonického stylu pro návrh daného systému. 

Podle celkového hodnocení, které jednotlivé architektonické styly získali bylo vyhodnoceno, který z nich je pro návrh systému pro správu konferencí dle zadání vhodnější.

## Hodnotové škály

### Škála hodnocení

| **Slovní hodnocení** | **Počet hvězdiček** |
|----------------------|---------------------|
| Výborné              | 5                   |
| Velmi dobré          | 4                   |
| Dobré                | 3                   |
| Slabé                | 2                   |
| Spatné               | 1                   |

### Váhy

| **Váha**       | **Výzanm** |
|----------------|------------|
| Velmi důležité | 4          |
| Důležité       | 3          |
| Nedůležité     | 2          |
| Nepodstatné    | 1          |


## Hodnocení

### Architektura orientovaná na služby

| **Charakteristika**  | **Hodnocení** | **Váha** | **Výsledek** |
|----------------------|---------------|----------|--------------|
| Nasaditelnost        | 3             | 1,00     | 4,00         |
| Elasticita           | 3             | 0,75     | 1,50         |
| Škálovatelnost       | 5             | 0,75     | 2,25         |
| Odolnost vůči chybám | 5             | 0,25     | 1,00         |
| Modularita           | 4             | 0,25     | 1,00         |
| Cena                 | 3             | 0,75     | 3,00         |
| Výkon                | 5             | 1,00     | 3,00         |
| Spolehlivost         | 3             | 0,5      | 2,00         |
| Jednoduchost         | 1             | 1,00     | 3,00         |
| Testovatelnost       | 2             | 0,50     | 2,00         |
| **Celkové hodnocení**| **22,75**                               |

### Událostmi řízená architektura

| **Charakteristika**  | **Hodnocení** | **Váha** | **Výsledek** |
|----------------------|---------------|----------|--------------|
| Nasaditelnost        | 3             | 1,00     | 3,00         |
| Elasticita           | 3             | 0,75     | 2,25         |
| Škálovatelnost       | 5             | 0,75     | 3,75         |
| Odolnost vůči chybám | 5             | 0,25     | 1,25         |
| Modularita           | 4             | 0,25     | 1,00         |
| Cena                 | 3             | 0,75     | 2,25         |
| Výkon                | 5             | 1,00     | 5,00         |
| Spolehlivost         | 3             | 0,5      | 1,5          |
| Jednoduchost         | 1             | 1,00     | 1,00         |
| Testovatelnost       | 2             | 0,50     | 1,00         |
| **Celkové hodnocení**| **22,00**                               |

## Závěr

Z hodnocení vybraných architektonických stylů vychází, že vhodnost obou z nich pro využití k návrhu systému pro správu konferencí dle zadání, je na téměř shodné úrovni. Jelikož ze zadání vychází, že navrhovaný systém by měl být především jednoduchý, výkonný, dobře škálovatelný a jednoduše nasaditelný, vychází jako mírně upřednostňovaná architektura orientovaná na služby (SOA). Tento architektonický styl byl námi zvolen v rámci architektonického rozhodnutí o celkové architektuře systému. Naopak výrazně vyšší složitost, horší testovatelnost a lehce horší nasaditelnost (i přes vyšší výkonnost) zapříčinila, že událostmi řízená architektura (EDA) vyšla pro návrh tohoto systému jako méně vhodná. 

Rozdíly v hodnocení jsou však velmi malé. Nelze tedy jednoznačně konstatovat, že událostmi řízená architektura je pro návrh systému pro správu konferencí dle zadání naprosto nevhodná. Výhody, které tento architektonický styl nabízí jsou v souvislosti s tímto navrhovaným systémem naprosto relevantní. Avšak na základě námi identifikovaných charakteristik, které jsou pro takový systém klíčové, vyšla jako vhodnější architektura orientovaná na služby.
