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
* Do kolorowania składni w Reveal.JS jest używana w formie wtyczki biblioteka _highlight.js_.
* Wspierane są języki i składnia: Apache (składnia plików konfiguracyjnych), Bash, CoffeeScript, C++, C#, CSS, Diff, HTTP (składnia żądań i odpowiedzi), Ini, Java, Javascript, JSON, Makefile, Markdown, Nginx (składnia plików konfiguracyjnych), Objective-C, Perl, PHP, Python, Ruby, SQL, HTML, XML.


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