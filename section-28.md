## Kod


### Składnia kodu
* Kod zamieszczamy w znakach ` ` `
* Liczba użytych znaków jest dowolna.
* Liczba znaków otwierających i zamykających musi być zgodna.
* Składnia taka jest konwertowana na HTML-owy element `code`.
* Kod może być:
    * liniowy (_inline_),
    * blokowy.
* Kod blokowy może być dodatkowo oznaczony nazwą języka, co zostanie użyte do kolorowania składni.


### Składnia kodu (2)
* Kod liniowy zamieszczany jest bezpośrednio w tekście, np. w treści akapitu, w cytatatch, w elementach list, itp.
* Kod blokowy musi być umieszczony samodzielnie w odrębnych wierszach - znacznik otwierający musi być poprzedzony znakiem przejścia do nowego wiersza. Po znaczniku otwierającym może wystąpić tylko deklaracja języka lub znak przejścia do kolejnego wiersza.


### Kolorowanie składni
* Do kolorowania składni w _reveal.js_ jest używana w formie wtyczki biblioteka _highlight.js_.
* Wspierane są języki i składnia: _Apache_ (składnia plików konfiguracyjnych), _Bash_, _CoffeeScript_, _C++_, _C#_, _CSS_, _Diff_, _HTTP_ (składnia żądań i odpowiedzi), _Ini_, _Java_, _Javascript_, _JSON_, _Makefile_, _Markdown_, _Nginx_ (składnia plików konfiguracyjnych), _Objective-C_, _Perl_, _PHP_, _Python_, _Ruby_, _SQL_, _HTML_, _XML_.
* Możliwe jest także zadeklarowanie kodu jako `text`, co wyłącza kolorowanie składni.


### Przykład kodu inline
---
Fragment kodu: `git clone ...`

Fragment kodu: ``git clone ...``

Fragment kodu: ```git clone ...```

Fragment kodu: ````git clone ...````

---
`````
Fragment kodu: `git clone ...`

Fragment kodu: ``git branch ...``

Fragment kodu: ```git checkout ...```

Fragment kodu: ````git merge ...````
`````


### Przykład kodu blokowego z deklaracją języka
* niniejszy przykład deklaruje język, według którego kolorowana jest składnia.

---
```sh
git clone https://github.com/mkordulewski/prezentacja-markdown.git
```
---
`````
```sh
git clone https://github.com/mkordulewski/prezentacja-markdown.git
```
`````


### Przykład kodu blokowego bez deklaracji języka
* Niniejszy przykład pomija deklarację języka, według którego kolorowana jest składnia.
* Przykład jest analogiczny jak w poprzednim slajdzie z pominięciem w/w deklaracji.
* Warto zwrócić uwagę na kolorowanie składni, które także zostało wykonane lecz z nieco odmiennym skutkiem - został wykorzystany mechanizm automatycznego wykrycia języka z odmiennym rezultatem.

---
```
git clone https://github.com/mkordulewski/prezentacja-markdown.git
```
---
`````
```
git clone https://github.com/mkordulewski/prezentacja-markdown.git
```
`````


### Wpływ deklaracji języka na kolorowanie
* różne deklaracje języka wpływają na kolorowanie.

---
Brak deklaracji (automatyczna detekcja języka):
```
CREATE TABLE "topic" ("id" serial NOT NULL PRIMARY KEY, "subject" varchar(255) NOT NULL);
```
---
Deklaracja SQL:
```sql
CREATE TABLE "topic" ("id" serial NOT NULL PRIMARY KEY, "subject" varchar(255) NOT NULL);
```
---
Deklaracja TEXT:
```text
CREATE TABLE "topic" ("id" serial NOT NULL PRIMARY KEY, "subject" varchar(255) NOT NULL);
```
---
Deklaracja HTML, a więc niezgodna z rzeczywistością:
```html
CREATE TABLE "topic" ("id" serial NOT NULL PRIMARY KEY, "subject" varchar(255) NOT NULL);
```


### Zagnieżdzanie znaczników kodu
* Niekiedy, jak w niniejszej prezentacji, może być niezbędna konieczność zagnieżdzania znaczników kodu, co ma na celu pokazania tekstu źródłowego ze znacznikami kodu... jako kodu właśnie.
* Wykorzystamy do tego mechanizm opisany wcześniej - konieczność użycia w znaczniku otwierającym i zamykającym kod jednakowej liczby znaków ` ` `
* Pozwoli to na wyświetlenie kodu umieszczonego jako kod wraz ze znacznikami kodu.
---
`````
````
```
git clone https://github.com/mkordulewski/prezentacja-markdown.git
```
````
`````


### Przykład kodu zadeklarowanego jako `text`
* Kod może być zadeklarowany jako `text` co wyłącza kolorowanie składni.

---
Rezutat:
```text
Postępek męski -
Uśmiechem witać klęski.
(Jan Sztaudynger)
```
---
Tekst źródłowy:
````text
```text
Postępek męski -
Uśmiechem witać klęski.
(Jan Sztaudynger)
```
````


### Przykład kodu JSON
Rezutat:
```json
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  }
]
```
---
Tekst źródłowy:
````json
```json
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  }
]
```
````


### Przykład kodu YAML
Rezutat:
```css
@font-face {
  font-family: Chunkfive; src: url('Chunkfive.otf');
}
@import url(print.css);
@media print {
  a[href^=http]::after {
    content: attr(href)
  }
}
```
---
Tekst źródłowy:
````css
```css
@font-face {
  font-family: Chunkfive; src: url('Chunkfive.otf');
}
@import url(print.css);
@media print {
  a[href^=http]::after {
    content: attr(href)
  }
}
```
````


### Przykład kodu Java
Rezutat:
```java
/**
 * @author Michael Kordulewski <michael@kordulewski.com>
*/
package com.kordulewski;
public abstract class Calculator extends ICalc {
  public static final Short ERROR = 0x0001;
  public void add(int x, int y) {
    return x+y;
  }
}
```
---
Tekst źródłowy:
````java
```java
/**
 * @author Michael Kordulewski <michael@kordulewski.com>
*/
package com.kordulewski;
public abstract class Calculator extends ICalc {
  public static final Short ERROR = 0x0001;
  public void add(int x, int y) {
    return x+y;
  }
}
```
````