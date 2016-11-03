## Notatki prelegenta
_Speaker's notes_


## Przykład notatek
* Notatki pokazywane są w dolnym pasku - warunkowo tylko jeśli globalny parametr konfiguracyjny `showNotes` ustawiony jest na `true`.
* Notatki pokazywane są też w ekranie prelegenta dostępnym przez skrót klawiaturowy `s`.
Notes:
Notatki dotyczące slajdu


## Kod notatki
* Notatki rozpoczynamy ciągiem znaków, którym skonfigurujemy w elemencie `section` w wartości atrybutu `data-separator-notes`.
* W niniejszej prezentacji użyty został ciąg `^Notes:$` gdzie znaki `^` i `$` są znakami specjalnymi z wyrażeń regularnych i oznaczają odpowiednio początek i koniec wiersza. Tak więc w tym przykładzie notatki notatki

  Plik HTML:
```html
<section data-separator-notes="^Notes:$" />
```
  Plik Markdown:
```
Notes: 
Notatki dotyczące slajdu
```
* UWAGA: notatki błędnie współpracują z kodem blokowym i notatka umieszczona w kodzie, a więc przeznaczona do prezentacji kodu a nie działania, jest interpretowana jako właściwe, produkcyjne użycie notatki. Konwerter Markdown -> HTML został "oszukany" przez wstawienie dodatkowego białego znaku na końcu wiersza `Notes: ` co nie odpowiada wyrażeniu regularnemu `^Notes:$`. Taki znak na końcu linii może jednak być automatycznie usuwany w zależności od ustawień IDE.