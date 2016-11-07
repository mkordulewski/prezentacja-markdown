## Listy


### Typy list w Markdown
* listy punktowane
* listy numerowane


### Lista punktowana
* Punktorami mogą być znaki: `-`, `+`, `*`.
* Po punktorze musi nastąpić co najmniej jedna spacja.
* Kolejne elementy listy wymieniane są w kolejnych wierszach.

---
- element 1
- element 2
+ element 3
+ element 4
* element 5
* element 6
---
```
- element 1
- element 2
+ element 3
+ element 4
* element 5
* element 6
```


### Lista punktowana zagnieżdzona
* Elementy zagnieżdzone muszą być wcięte (2 lub 4 spacje).
* Zagnieżdzanie może być na wielu poziomach.

---
- element 1
  - element 1.1
    - element 1.1.1
        - element 1.1.1.1
  - element 1.2
- element 2
  - element 2.1
---
```
- element 1
  - element 1.1
    - element 1.1.1
        - element 1.1.1.1
  - element 1.2
- element 2
  - element 2.1
```


### Lista numerowana
* Analogicznie jak w liście punktowanej.
* Punktorami są liczby (np.: `1.`, `2.`, `3.`, ...).
* Po liczbie musi nastąpić kropka i co najmniej jedna spacja.

---
1. element 1
2. element 2
3. element 3
4. element 4
---
```
1. element 1
2. element 2
3. element 3
4. element 4
```


### Lista numerowana (2)
* Użyta w punktorze liczba nie jest istotna.
* Liczba w pierwszym punktorze nie musi być jedynką.
* Liczba w kolejnym punktorze nie musi być liczbą o jeden większą.

---
2. element 1
5. element 2
1. element 3
---
```
2. element 1
5. element 2
1. element 3
```


### Lista numerowana (3)
* Punktory mogą mieć dowolne liczby, w tym przypadku `1.`
* Użyta w punktorze liczba nie jest istotna.

---
1. element 1
1. element 2
1. element 3
1. element 4
1. element 5
1. element 6
---
```
1. element 1
1. element 2
1. element 3
1. element 4
1. element 5
1. element 6
```


### Dobre praktyki list numerowanych
* Punktory w postaci kolejnych liczb pozwalają na lepszą orientację w tekście źródłowym, ale są trudniejsze w utrzymaniu - wstawianiu i usuwaniu elementów listy.
* Punktory w postaci przypadkowych liczb nie mają zalet, powodują chaos. Są poprawne ale lepiej ich unikać.
* Punktory w postaci jednakowej liczby (np. `1` - poprzedni slajd) pozwalają na łatwe utrzymanie listy, proste wstawianie i usuwanie elementów. Liczbę elementów na liście i ich numery poznamy jednak dopiero po wyświetleniu a nie w tekście źródłowym.


### Lista numerowana zagnieżdzona
---
1. element 1
   1. element 1.1
   1. element 1.2
1. element 2
   1. element 2.1
   1. element 2.2
---
```
1. element 1
   1. element 1.1
   1. element 1.2
1. element 2
   1. element 2.1
   1. element 2.2
```


### Element listy z akapitem
* Element listy może zawierać cały akapit tekstu lub nawet kilka akapitów.
* Akapit taki musi być od poprzedzającego wiersza odseparowany pustym wierszem (tak jak każdy akapit).
* Akapit taki musi być wciety na ten sam poziom co element, który go zawiera.


### Przykład elementów listy z akapitami
---
1. element 1

   Akapit w ramach punktu 1

   Kolejny akapit w ramach punktu 1
   1. element 1.1

      Akapit w ramach punktu 1.1

      Kolejny akapit w ramach punktu 1.1

   Trzeci akapit w ramach punktu 1


### Tekst źródłowy elementów listy z akapitami
```
1. element 1

   Akapit w ramach punktu 1

   Kolejny akapit w ramach punktu 1
   1. element 1.1

      Akapit w ramach punktu 1.1

      Kolejny akapit w ramach punktu 1.1

   Trzeci akapit w ramach punktu 1
```
Tekst źródłowy do poprzedniego slajdu
