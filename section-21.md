## Formatowanie tekstu


### Akapity
* wiersze tekstu rozdzielony pustymi wierszami, które pełnią rolę separatorów akapitów.
* nie wymagają żadnej dodatkowej składni.
* UWAGA: pojedynczy znak końca linii, nie powoduje utworzenia nowego akapitu. Musi to być podwójny znak końca linii.


### Przykłady akapitów
---
Lorem ipsum dolor sit amet, consectetur adipiscing elit.

Nam turpis ex, laoreet sed rutrum sit amet, mattis nec risus. Suspendisse libero est, consequat eu venenatis quis, auctor ut velit.

---
```markdown
Lorem ipsum dolor sit amet, consectetur adipiscing elit.

Nam turpis ex, laoreet sed rutrum sit amet, mattis nec risus. Suspendisse libero est, consequat eu venenatis quis, auctor ut velit.
```


### Formatowanie tekstu
---
Tekst może być **wytłuszczony** lub _pochylony_.

---
```
Tekst może być **wytłuszczony** lub _pochylony_.
```


### Formatowanie tekstu (2)
---
Tekst może być _**wytłuszczony i pochylony**_.

Tekst może być **_wytłuszczony i pochylony_**.

Tekst może być *__wytłuszczony i pochylony__*.

Tekst może być __*wytłuszczony i pochylony*__.

---
```
Tekst może być _**wytłuszczony i pochylony**_.

Tekst może być **_wytłuszczony i pochylony_**.

Tekst może być *__wytłuszczony i pochylony__*.

Tekst może być __*wytłuszczony i pochylony*__.
```


### Formatowanie tekstu (3)
UWAGA: w składni wytłuszczania i pochylania liczy się liczba znaków a nie który znak użyjemy. Oba znaki (* i _) można stotoswać zamiennie, za to znaczące jest wystąpienie pojedyncze lub podwójne znaku.<!-- .element: style="text-align: justify" -->

---
Tekst może być __wytłuszczony__ lub _pochylony_.

Tekst może być **wytłuszczony** lub *pochylony*.

---
```
Tekst może być __wytłuszczony__ lub _pochylony_.
Tekst może być **wytłuszczony** lub *pochylony*.
```



### Równanie tekstu
#### Składnia dodana przez _reveal.js_
---
DOMYŚLNIE: Lorem ipsum dolor sit amet, consectetur adipis ipsum dolor sit amet, consectetur adipis ax ipsum dolor sit amet, consectetur adipis ax.

JUSTOWANIE: Lorem ipsum dolor sit amet, consectetur adipis ipsum dolor sit amet, consectetur adipis ax ipsum dolor sit amet, consectetur adipis ax.<!-- .element: style="text-align: justify" -->

DO LEWEJ: Lorem ipsum dolor sit amet, consectetur adipis ipsum dolor sit amet, consectetur adipis ax ipsum dolor sit amet, consectetur adipis ax.<!-- .element: style="text-align: left" -->

CENTROWANIE: Lorem ipsum dolor sit amet, consectetur adipis ipsum dolor sit amet, consectetur adipis ax ipsum dolor sit amet, consectetur adipis ax.<!-- .element: style="text-align: center" -->

DO PRAWEJ: Lorem ipsum dolor sit amet, consectetur adipis ipsum dolor sit amet, consectetur adipis ax ipsum dolor sit amet, consectetur adipis ax.<!-- .element: style="text-align: right" -->


### Równanie tekstu
#### Składnia dodana przez _reveal.js_
Równanie tekstu zadeklarowane jest po prawej stronie linii w postaci komentarza HTML. Jeśli deklaracje są niewidoczne proszę przewinąć kod źródłowy w oknie.

---
```
DOMYŚLNIE: Lorem ipsum dolor sit amet, consectetur adipis ipsum dolor sit amet, consectetur adipis ax ipsum dolor sit amet, consectetur adipis ax.

JUSTOWANIE: Lorem ipsum ...<!-- .element: style="text-align: justify" -->

DO LEWEJ: Lorem ipsum ...<!-- .element: style="text-align: left" -->

CENTROWANIE: Lorem ipsum ...<!-- .element: style="text-align: center" -->

DO PRAWEJ: Lorem ipsum ...<!-- .element: style="text-align: right" -->
```


### Łamanie linii akapitu
* Linie akapitu mogą być łamane - pojedynczy znak końca wiersza pozwala podzielić tekst źródłowy na wygodnej długości
linie a wyświetlony będzie jako jeden spójny akapiy, który automatycznie dostosowuje się do szerokości ekranu.
* Należy pamiętać, że podwójny znak końca wiersza, czyli jeden pusty wiersz pomiędzy akapitami, tworzy już odrębny akapit.

---
Lorem ipsum dolor sit amet, consectetur adipiscing elit.
Donec vitae massa rhoncus, accumsan metus quis, accumsan magna.
Pellentesque nec odio non dolor iaculis sodales vitae sed odio.
Etiam in urna aliquam ante sodales eleifend.
Cras vitae risus fermentum ipsum facilisis scelerisque ut eu nulla.<!-- .element: style="text-align: justify" -->

---
```
Lorem ipsum dolor sit amet, consectetur adipiscing elit.
Donec vitae massa rhoncus, accumsan metus quis, accumsan magna.
Pellentesque nec odio non dolor iaculis sodales vitae sed odio.
Etiam in urna aliquam ante sodales eleifend.
Cras vitae risus fermentum ipsum facilisis scelerisque ut eu nulla.<!-- .element: style="text-align: justify" -->
```


### Domyślna postać tekstu
* Każdy tekst domyślnie jest akapitem jeśli nie jest nagłówkiem, listą, cytatem lub tekstem w komórce tabeli.
* Czyli akapitem są m.in. "samodzielne" linki, grafiki, kod liniowy. Ale kod blokowy już nie znajduje się w akapicie lecz w blokowym elemencie `pre`.