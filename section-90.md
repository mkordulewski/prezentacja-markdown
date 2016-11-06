## Dobre i złe praktyki


### Dobra praktyka: pliki zewnętrzne
* Tekst sformatowany w markdown użyty we frameworku _reveal.js_ może być wstawiony w kod HTML, ale jest to z pewnością złą praktyką, którą można nazwać _spaghetti code_.
* Dobrą praktyką jest za to umieszczenie tekstu w markdown w odrębnych plikach, tak by nie kolidował z kodem HTML.


### Zła praktyka: style CSS
* Używanie stylów CSS w tekście Markdown z pewnością jest złym rozwiązaniem, gdyż:
    * Trwale nadaje tekstowi style.
    * Utrudnia używanie zewnętrznych arkuszy stylów.
    * Utrudnia używanie skórek.
* Jest to odpowiednik stylów osadzonych (_inline styles_) z HTML.
* Zamiast nadawania stylów powinny być nadawane klasy CSS.


### Dobra praktyka: klasy CSS
* W przeciwieństwie do nadawania tekstowi wprost stylów CSS lepiej jest nadawać mu klasy CSS.
* Wymaga to zdefiniowania klas CSS.
* Zalety:
    * Możliwość używania zewnętrznych arkuszy stylów i separacji kodu CSS i HTML oraz tekstu Markdown.
    * Możliwość używania skórek.
