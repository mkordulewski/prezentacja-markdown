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
Tekst może być **wytłuszczony** lub _pochylony_.

Składnia:
```
Tekst może być **wytłuszczony** lub _pochylony_.
```


### Formatowanie tekstu (2)
Tekst może być _**wytłuszczony i pochylony**_.

Tekst może być **_wytłuszczony i pochylony_**.

Tekst może być *__wytłuszczony i pochylony__*.

Tekst może być __*wytłuszczony i pochylony*__.

Składnia:
```
Tekst może być _**wytłuszczony i pochylony**_.

Tekst może być **_wytłuszczony i pochylony_**.

Tekst może być *__wytłuszczony i pochylony__*.

Tekst może być __*wytłuszczony i pochylony*__.
```


### Formatowanie tekstu (3)
UWAGA: w składni wytłuszczania i pochylania liczy się liczba znaków a nie który znak użyjemy. Oba znaki (* i _) można stotoswać zamiennie, za to znaczące jest wystąpienie pojedyncze lub podwójne znaku.<!-- .element: style="text-align: justify" -->

Składnia:
```
Tekst może być __wytłuszczony__ lub _pochylony_.
Tekst może być **wytłuszczony** lub *pochylony*.
```
Wynik:

Tekst może być __wytłuszczony__ lub _pochylony_.

Tekst może być **wytłuszczony** lub *pochylony*.



### Równanie tekstu
#### Składnia dodana przez Reveal.JS
DOMYŚLNIE: Lorem ipsum dolor sit amet, consectetur adipis ipsum dolor sit amet, consectetur adipis ax ipsum dolor sit amet, consectetur adipis ax.

JUSTOWANIE: Lorem ipsum dolor sit amet, consectetur adipis ipsum dolor sit amet, consectetur adipis ax ipsum dolor sit amet, consectetur adipis ax.<!-- .element: style="text-align: justify" -->

DO LEWEJ: Lorem ipsum dolor sit amet, consectetur adipis ipsum dolor sit amet, consectetur adipis ax ipsum dolor sit amet, consectetur adipis ax.<!-- .element: style="text-align: left" -->

CENTROWANIE: Lorem ipsum dolor sit amet, consectetur adipis ipsum dolor sit amet, consectetur adipis ax ipsum dolor sit amet, consectetur adipis ax.<!-- .element: style="text-align: center" -->

DO PRAWEJ: Lorem ipsum dolor sit amet, consectetur adipis ipsum dolor sit amet, consectetur adipis ax ipsum dolor sit amet, consectetur adipis ax.<!-- .element: style="text-align: right" -->


### Równanie tekstu
#### Składnia dodana przez Reveal.JS
```
DOMYŚLNIE: Lorem ipsum dolor sit amet, consectetur adipis ipsum dolor sit amet, consectetur adipis ax ipsum dolor sit amet, consectetur adipis ax.

JUSTOWANIE: Lorem ipsum ...<!-- .element: style="text-align: justify" -->

DO LEWEJ: Lorem ipsum ...<!-- .element: style="text-align: left" -->

CENTROWANIE: Lorem ipsum ...<!-- .element: style="text-align: center" -->

DO PRAWEJ: Lorem ipsum ...<!-- .element: style="text-align: right" -->
```
Równanie tekstu zadeklarowane jest po prawej stronie linii. Jeśli deklaracje są niewidoczne proszę przewinąć kod źródłowy w oknie.