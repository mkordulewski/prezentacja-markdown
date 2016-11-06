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


### Kolorowanie składni
* Do kolorowania składni w _reveal.js_ jest używana w formie wtyczki biblioteka _highlight.js_.
* Wspierane są języki i składnia: _Apache_ (składnia plików konfiguracyjnych), _Bash_, _CoffeeScript_, _C++_, _C#_, _CSS_, _Diff_, _HTTP_ (składnia żądań i odpowiedzi), _Ini_, _Java_, _Javascript_, _JSON_, _Makefile_, _Markdown_, _Nginx_ (składnia plików konfiguracyjnych), _Objective-C_, _Perl_, _PHP_, _Python_, _Ruby_, _SQL_, _HTML_, _XML_.


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


### Przykład kodu blokowego
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