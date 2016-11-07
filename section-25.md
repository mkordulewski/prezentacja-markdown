## Grafiki


### Przykłady użycia grafik
---
![Opis](resources/markdown.svg)
![Opis](resources/markdown.svg "Tytuł 1")
![Opis][id]
[id]: resources/markdown.svg "Tytuł 2"

---
```
![Opis](resources/markdown.svg)
![Opis](resources/markdown.svg "Tytuł 1")
![Opis][id]
[id]: resources/markdown.svg "Tytuł 2"
```


### Grafiki każda w nowym wierszu
---
![Opis](resources/markdown.svg)

![Opis](resources/markdown.svg "Tytuł 1")

![Opis][id]
[id]: resources/markdown.svg "Tytuł 2"

---
```
![Opis](resources/markdown.svg)

![Opis](resources/markdown.svg "Tytuł 1")

![Opis][id]
[id]: resources/markdown.svg "Tytuł 2"
```


### Grafika z linkiem
---
[![Atrybut <alt/> elementu <img/>](resources/markdown.svg)](https://pl.wikipedia.org/wiki/Markdown "Atrybut <title/> elementu <a/>")

---
```
[![Atrybut <alt/> elementu <img/>](resources/markdown.svg)](https://pl.wikipedia.org/wiki/Markdown "Atrybut <title/> elementu <a/>")
```


### Grafika jako podelement
* Grafika zawsze staje się podelementem elementu nadrzędnego blokowego, np. akapitu, (elementu) listy, zawartością komórki tabeli.
* Domyślnie samodzielna grafika (w osobnym wierszu) jest podelementem akapitu.