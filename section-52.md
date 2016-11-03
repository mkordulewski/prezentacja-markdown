## Notatki prelegenta
_Speaker's notes_


## Przykład notatek
* Notatki pokazywane są w dolnym pasku - warunkowo tylko jeśli globalny parametr konfiguracyjny `showNotes` ustawiony jest na `true`.
* Notatki pokazywane są też w ekranie prelegenta dostępnym przez skrót klawiaturowy `s`.
Notes:
Notatki dotyczące slajdu


## Kod notatki
```
Notes: 
Notatki dotyczące slajdu
```
* UWAGA: notatki błędnie współpracują z kodem blokowym i notatka umieszczona w kodzie, a więc przeznaczona do prezentacji kodu a nie działania, jest interpretowana jako właściwe, produkcyjne użycie notatki. Konwerter Markdown -> HTML został "oszukany" przez wstawienie dodatkowego białego znaku na końcu wiersza `Notes: ` co nie odpowiada wyrażeniu regularnemu `^Notes:$`.