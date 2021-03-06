## Linki


### Przykładowe linki
* Linki tworzymy za pomocą składni:
```
[OPIS](URL)
```
* Do linku można także dodać "dymek", który pojawia się po najechaniu na link:
```
[OPIS](URL "DYMEK")
```
* Poprawne URL-e umieszczone wprost w tekście także są zamieniane na klikalne linki.

---
* [przykładowy link z zamianą na tekst](http://przyklad.pl/)
* [przykładowy link z zamianą na tekst](http://przyklad.pl/ "Treść 'dymka' - element title") - link z "dymkiem" (atrybutem "title"), najedź na niego kursorem
* adres URL automatycznie zamieniony na klikalny link:
  http://przyklad.pl/

---
```
* [przykładowy link z zamianą na tekst](http://przyklad.pl/)
* [przykładowy link z zamianą na tekst](http://przyklad.pl/ "Treść 'dymka' - element title") - link z "dymkiem" (atrybutem "title"), najedź na niego kursorem
* adres URL automatycznie zamieniony na klikalny link:
  http://przyklad.pl/
```


### Linki jako przypisy
Wyszukiwarki: [Google][1], [Bing][2], [Yahoo][3].
[1]: http://google.com/ "Google"
[2]: http://bing.com/   "Bing"
[3]: http://yahoo.com/  "Yahoo"
```txt
Wyszukiwarki: [Google][1], [Bing][2], [Yahoo][3].
[1]: http://google.com/ "Google"
[2]: http://bing.com/   "Bing"
[3]: http://yahoo.com/  "Yahoo"
```


### Linki jako przypisy (c.d.)
Wyszukiwarki: [Google][g], [Bing][b], [Yahoo][y].
[g]: http://google.com/ "Google"
[b]: http://bing.com/   "Bing"
[y]: http://yahoo.com/  "Yahoo"
```txt
Wyszukiwarki: [Google][g], [Bing][b], [Yahoo][y].
[g]: http://google.com/ "Google"
[b]: http://bing.com/   "Bing"
[y]: http://yahoo.com/  "Yahoo"
```


### Link jako podelement
* Link zawsze staje się podelementem elementu nadrzędnego blokowego, np. akapitu, (elementu) listy, zawartością komórki tabeli.
* Domyślnie samodzielny link (w osobnym wierszu) jest podelementem akapitu.