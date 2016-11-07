## Cytaty
> Wszystka wiedza pochodzi z doświadczenia.

_Immanuel Kant_


### Przykład cytatu
* Cytat jest akapitem poprzedzonym znakiem `>`.

---
> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec vitae massa rhoncus, accumsan metus quis, accumsan magna. Pellentesque nec odio non dolor iaculis sodales vitae sed odio.

---
```
> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec vitae massa rhoncus, accumsan metus quis, accumsan magna. Pellentesque nec odio non dolor iaculis sodales vitae sed odio.
```


### Łamanie linii cytatu
* Dla łatwości edycji linie cytatu można łamać.

---
> Lorem ipsum dolor sit amet, consectetur adipiscing elit.
Donec vitae massa rhoncus, accumsan metus quis, accumsan magna.
Pellentesque nec odio non dolor iaculis sodales vitae sed odio.

---
```
> Lorem ipsum dolor sit amet, consectetur adipiscing elit.
Donec vitae massa rhoncus, accumsan metus quis, accumsan magna.
Pellentesque nec odio non dolor iaculis sodales vitae sed odio.
```


### Cytat wielowierszowy
---
> Lorem ipsum dolor sit amet, consectetur adipiscing elit.
>
> Donec vitae massa rhoncus, accumsan metus quis, accumsan magna.

---
```
> Lorem ipsum dolor sit amet, consectetur adipiscing elit.
>
> Donec vitae massa rhoncus, accumsan metus quis, accumsan magna.
```


### Cytat zagnieżdzony
---
> Lorem ipsum dolor sit amet, consectetur adipiscing elit.
>
> > Donec vitae massa rhoncus, accumsan metus quis, accumsan magna.

---
```
> Lorem ipsum dolor sit amet, consectetur adipiscing elit.
>
> > Donec vitae massa rhoncus, accumsan metus quis, accumsan magna.
```


### Cytat sformatowany
---
> cytat
>
> _kursywa_
>
> **wytłuszczenie**

---
```
> cytat
>
> _kursywa_
>
> **wytłuszczenie**
```


### Cytat sformatowany (2)
---
> # Nagłówek 1
> ## Nagłówek 2
> ### Nagłówek 3
> #### Nagłówek 4
> ##### Nagłówek 5
> ###### Nagłówek 6

---
```
> # Nagłówek 1
> ## Nagłówek 2
> ### Nagłówek 3
> #### Nagłówek 4
> ##### Nagłówek 5
> ###### Nagłówek 6
```


### Cytat z listą punktowaną
---
> * Element 1
>   * Element 1.1
> * Element 2
>   * Element 2.1
> * Element 3

---
```
> * Element 1
>   * Element 1.1
> * Element 2
>   * Element 2.1
> * Element 3
```


### Cytat z listą numerowaną
---
> 1. Element 1
>   1. Element 1.1
> 1. Element 2
>   1. Element 2.1
> 1. Element 3

---
```
> 1. Element 1
>   1. Element 1.1
> 1. Element 2
>   1. Element 2.1
> 1. Element 3
```


## Połączenie akapitów i cytatów
* naturalne, wynika z wcześniej zaprezentowanej składni

---
Albert Einstein:
> Wyobraźnia jest ważniejsza od wiedzy, ponieważ wiedza jest ograniczona.

Arystoteles:
> Prawdziwa wiedza to znajomość przyczyn.

---
```
Albert Einstein:
> Wyobraźnia jest ważniejsza od wiedzy, ponieważ wiedza jest ograniczona.

Arystoteles:
> Prawdziwa wiedza to znajomość przyczyn.
```


### Cytat liniowy
* Cytat domyślnie jest elementem blokowym.
* W Markdown nie ma cytatu liniowego jako odrębnego elementu.
* Jako cytatu liniowego można użyć italików (pochylenia tekstu), np.: _"cytat liniowy"_.
* Nie staje się on jednak semantycznym cytatem w HTML (`cite`) lecz elementem `em`, więc semantycznie nadal tekstem pochylonym.
* Takiego cytatu liniowego można użyć w akapicie, liście, tabeli.
---
Tekst źródłowy:
```
_"cytat liniowy"_
```