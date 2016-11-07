## Znaki specjalne


### Ucieczka znaków - _Escaping_
* W Markdown _nie_ występują klasyczne znaki specjalne, które zawsze mają znaczenie specjalne i które trzeba zapisywać w specjalny sposób (ang. _escaping_) by wyświetlić jako zwykły znak.
* Tak więc w Markdown nie występuje klasyczne "ucieczkowanie" (_escaping_) znaków.
* Znaki, które mają znaczenie w składni Markdown, mają je tylko określonym kontekście, w określonej sytuacji - w określonym towarzystwie innych znaków.


### Znaki znaczące w składni
* W Markdown występują m.in. następujące znaki, które mają znaczenie dla składni: `#`, `*`, `_`, `-`, `+`, `=`, `|`, `:`, ` ` `, `>` oraz znak końca wiersza.
* Nie są to wszystkie znaki a tylko te, które mogą mieć znaczenie samodzielne lub "prawie samodzielne".
* Pominięta zostały takie złożone kontrukcje jak np.:
    * listy numerowane (za pomocą składni: cyfra + kropka + spacja)
    * linki (za pomocą składni: `[OPIS](URL)` lub `[OPIS](URL "DYMEK")`),
    * osadzanie obrazków (za pomocą składni: `![OPIS](URL)`),
    * HTML.


### Wyświetlanie apostrofu odwrotnego
ang. backtick `
* Znak ten służy do osadzania kodu źródłowego w tekście Markdown.
* By użyć tego znaku normalnie wystarczy użyć go niezgodnie ze składnią, np. umieścić pojedynczo lub podwójnie bez zawartości kodu - rezultat: `, ``.
* By użyć tego znaku wewnątrz liniowo (_inline_) wystarczy zawartość otoczyć spacjami - rezultat: ` ` `
* By użyć tego znaku blokowo wystarczy znak apostrofu otoczyć inną liczbą - rezultat blokowo:

`````
```
kod blokowy
```
`````
---
```````
normalnie:         `, ``
w kodzie liniowym: ` ` `
w kodzie blokowym:
`````
```
kod blokowy
```
`````
```````