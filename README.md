# Projekt č.2 - Jiří Kejda

## Úvod
Účelem tohoto projektu je vytvoření vizuálního přehledu dat o kriminalitě v České republice a srovnání s kriminalitou v Evropské unii (EU).

## Přehled použitých dat
- **Zdroj dat:** [Český statistický úřad](https://csu.gov.cz/kriminalita?pocet=10&start=0&podskupiny=081&razeni=-datumVydani#regionalni-data).
- **Časové rozmezí:**
  - Česká republika: **2013–2023**.
  - Evropská unie: **2013–2022**.
- **Obsah dat:**
  - Data o celkové kriminalitě v jednotlivých krajích ČR.
  - Data o konkrétních trestných činech.
  - Pro srovnání v rámci EU jsou použita data přepočítaná na **100 000 obyvatel**.
- **Poznámka k metodice:**
  - Před rokem **2016** byla stíhaným osobám započítávána pouze nejzávažnější trestná činnost (např. při vraždě a krádeži byla osoba započítána jen jako vrah, nikoliv jako zloděj).
  - Od roku **2016** je započítávána veškerá trestná činnost.
  - Při porovnávání časových řad je třeba brát v úvahu tyto změny v metodice.

## Cíle projektu
- Vytvořit vizuální přehled kriminality v ČR podle krajů a porovnat jej s daty z EU.
- Analyzovat trendy v kriminalitě v čase s ohledem na změny v metodice od roku 2016.
- Nabídnout interaktivní dashboard pro lepší pochopení dat.

## Nástroje a technologie
- **Power BI Desktop:** Hlavní nástroj pro analýzu a vizualizaci dat.
- **Excel/CSV:** Pro přípravu a export dat z ČSÚ.
- **DAX:** Pro vytváření vypočítaných měr (např. přepočet na 100 000 obyvatel).

## Instalace a spuštění
1. Stáhněte si Power BI Desktop z [oficiálního webu](https://powerbi.microsoft.com/desktop/).
2. Naklonujte tento repozitář: