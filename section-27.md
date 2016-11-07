## Tabele


### Przykład tabeli
---
| Kolumna 1 | Kolumna 2  | Kolumna 3 | Kolumna 4 |
|-----------|------------|-----------|-----------|
| A         | B          | C         | D         |
---
```
| Kolumna 1 | Kolumna 2  | Kolumna 3 | Kolumna 4 |
|-----------|------------|-----------|-----------|
| A         | B          | C         | D         |
```


### Równanie poziome w tabelach
* Równanie w tabelach uzyskiwane jest za pomocą znaku `:` (dwukropek).
* **Nie** ma w Markdown możliwości **justowania** zawartości komórki w tabeli.

---
| domyślnie | do lewej  | do środka | do prawej |
|-----------|:----------|:---------:|----------:|
| A         | B         | C         | D         |
| A A A     | B B B     | C C C     | D D D     |
---
```
| domyślnie | do lewej  | do środka | do prawej |
|-----------|:----------|:---------:|----------:|
| A         | B         | C         | D         |
| A A A     | B B B     | C C C     | D D D     |
```


### Ograniczenia tabel
* W Markdown tabela **nie** może zawierać:
    * wielowierszowego nagłówka,
    * tabel zagnieżdzonych,
    * komórek połączonych.


### Tabele szarpane
* Możliwe są tabele szarpane, czyli takie o nierównej licznie komórek w każdym wierszu.

---
Przykład tabeli szarpanej:

| Państwo          | Język                |
|:-----------------|:---------------------|
| Polska           | polski               |
| USA              | angielski            | nie wszystkie stany posiadają język urzędowy de iure | niektóre stany posiadają dodatkowo języki lokalne, np. hawajski na Hawajach
| Kanada           | angielski, francuski | prowincje oba lub tylko jeden język urzędowy spośród wymienionych