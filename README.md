# Analýza kriminality v ČR v Power BI

Tento projekt jsem vytvořila v rámci kurzu ENGETO Data Academy. Pro svůj Power BI projekt jsem si vybrala statistiky kriminality v České republice za roky 2025 a 2026.

Chtěla jsem zjistit, jak se kriminalita v průběhu roku vyvíjí, které druhy trestné činnosti jsou nejčastější a jak se jednotlivé kategorie liší z hlediska objasněnosti.

Výsledkem je interaktivní report v Power BI, který obsahuje čtyři stránky.

## Použitá data

Pracovala jsem s veřejně dostupnými statistikami Policie ČR:

- 2026: leden až září
- 2025: celý kalendářní rok

Hlavní část analýzy se věnuje roku 2026. Data za rok 2025 jsem přidala pro širší kontext, ale vzhledem k rozdílné délce sledovaných období je přímo neporovnávám.

## Použité nástroje

- Power BI Desktop
- Power Query
- DAX
- GitHub

## Co v reportu najdete

### 1. Kriminalita v číslech

Základní přehled kriminality za leden až září 2026. Celkový počet registrovaných trestných činů, měsíční maximum a minimum, rozdělení podle druhů kriminality a možnost filtrování podle měsíce.

### 2. Struktura kriminality

Porovnání pěti hlavních kategorií kriminality podle počtu registrovaných trestných činů a objasněnosti. Grafy jsou interaktivní a umožňují výběr jednotlivých kategorií.

### 3. Kriminalita v čase

Vývoj kriminality v jednotlivých měsících roku 2026. Spojnicový graf ukazuje vývoj vybraných druhů kriminality, sloupcový graf celkové měsíční počty.

### 4. Rok 2025 v číslech

Přehled za celý rok 2025 s prstencovým grafem pěti vybraných kategorií a možností filtrování.

## Co jsem zjistila

- Za leden až září 2026 bylo registrováno 132 297 trestných činů.
- Nejvíce případů bylo v lednu (15 915), nejméně v září (13 710).
- Největší zastoupení měla majetková kriminalita.
- Majetková kriminalita měla zároveň nejnižší objasněnost (28 %).
- Nejvyšší objasněnost měla ostatní kriminalita (63,3 %).
- Za celý rok 2025 bylo registrováno 170 051 trestných činů.

## Co jsem si na projektu vyzkoušela

Během práce jsem si procvičila úpravu dat v Power Query, vytváření vztahů mezi tabulkami, práci s DAX a tvorbu interaktivních vizualizací.

Nejvíce času mi zabralo nastavení datového modelu, filtrování a interakcí mezi grafy. Záleželo mi také na tom, aby byl report přehledný a vizuálně jednotný.

## Soubor projektu

`Kriminalita_CR_2025_2026.pbix`
