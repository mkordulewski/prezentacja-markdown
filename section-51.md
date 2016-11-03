## Fragmenty


### Cechy fragmentów
* Fragmenty to elementy dostępne na jednym slajdzie, które pojawiają się sekwencyjnie a nie równocześnie.
W ten sposób można wprowadzić stopniowy opis pewnego zjawiska.
* Fragment jest deklarowany przez nadanie klasy "fragment", stąd też nazwa mechanizmu.
* Fragmenty domyślnie pojawiają się na stronie w kolejności zadeklarowanej w tekście lub kodzie źródłowym.
* Można zmienić kolejność wyświetlania fragmentów za pomocą atrybutu "data-fragment-index".

Przykłady na kolejnych slajdach


## Przykład fragmentów
* elementom listy nadana została klasa `fragment`

[naciśnij strzałkę w dół lub spację]

---
- Element 1 <!-- .element: class="fragment" -->
- Element 2 <!-- .element: class="fragment" -->
- Element 3 <!-- .element: class="fragment" -->

---
```
- Element 1 <!-- .element: class="fragment" -->
- Element 2 <!-- .element: class="fragment" -->
- Element 3 <!-- .element: class="fragment" -->
```


## Przykład fragmentów z ustaloną kolejnością
* elementom listy nadany został atrybut `data-fragment-index` z wartością wskazującą na kolejność wyświetlania.

[naciśnij strzałkę w dół lub spację]

---
- Element 1 <!-- .element: class="fragment" data-fragment-index="3" -->
- Element 2 <!-- .element: class="fragment" data-fragment-index="2" -->
- Element 3 <!-- .element: class="fragment" data-fragment-index="1" -->

---
```
- Element 1 <!-- .element: class="fragment" data-fragment-index="3" -->
- Element 2 <!-- .element: class="fragment" data-fragment-index="2" -->
- Element 3 <!-- .element: class="fragment" data-fragment-index="1" -->
```