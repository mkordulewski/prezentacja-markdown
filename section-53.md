## Nadawanie stylów i klas CSS


### Przykład nadania klasy CSS
* W poniższym przykładzie drugiemu elementowi listy została nadana klasa CSS `blue`.
* Klasa CSS musi jednak być zadeklarowana w używanych arkuszach stylów CSS.
---
- Item 1
- Item 2<!-- .element: class="blue" -->
---
```markdown
- Item 1
- Item 2<!-- .element: class="blue" -->
```


### Przykład nadania stylów CSS
* W poniższym przykładzie elementom listy zostały nadane style CSS nadające im kolory.
* Sposób ten nie wymaga ingerencji w arkusze stylów CSS jednak jest gorszym sposobem ze względu na:
    * brak jednolitości stylów.
    * brak możliwości zmiany zewnętrznego arkusza stylów - arkusz można zmienić, jednak nie on decyduje o nadanych stylach, style tak użyte pozostaną pomimo zmiany zewnętrznego pliku CSS.
    * brak możliwości użycia różnych skórek, które są nadpisywane stylami tak nadanymi.
* Jest to odpowiednik stylów inline-owych z HTML-a, które są złą praktyką.
---
- Item 1
- Item 2 <!-- .element: style="color: red" -->
- Item 3 <!-- .element: style="color: green" -->
- Item 4 <!-- .element: style="color: yellow" -->
- Item 5 <!-- .element: style="color: brown" -->
---
```markdown
- Item 1 <!-- .element: style="color: blue" -->
- Item 2 <!-- .element: style="color: red" -->
- Item 3 <!-- .element: style="color: green" -->
- Item 4 <!-- .element: style="color: yellow" -->
- Item 5 <!-- .element: style="color: brown" -->
```


### Ograniczenia stylów i klas
* Style i klasy CSS można nadawać tylko elementom nadrzędnym - wierszom, akapitom, listom, itp.
* Nie można nadawać stylów ani klas:
    * pojedynczym słowom,
    * frazom.