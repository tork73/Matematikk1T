# Andregradslikninger: en generell Løsning

Du har sett på hvordan du kan finne nullpunkt og skjæringspunkt både grafisk, med fullstendige kvadraters metode og med digitale verktøy. Nå skal du se hvordan du kan benytte en formel for å gjøre det samme.

Nå er målet at du skal: 

* kunne gjengi abc-formelen
* kunne benytte abc-formelen til å løse andregradslikninger
* kunne faktorisere et andregradsuttrykk ved å benytte nullpunktene
* kunne finne skjæringspunkt ved regning og grafisk

![](/bilder/neven-krcmarek-145603-unsplash.jpg)

## abc-formelen

```{admonition} abc-formelen
: class: important

Alle andregradslikninger kan du skrive som 

$$a \cdot x^2+ b \cdot x + c =0 $$ 

hvor $a$, $b$ og $c$ er reelle tall.

Løsningene av denne andregradslikningen (dvs de $x$-verdiene som gjør at uttrykket blir lik null) kan du finne med denne formelen:

$$x=\dfrac{-b \pm \sqrt{b^2-4ac}}{2a}$$

```

Bevis for denne formelen kommer senere. Kanskje du klarer det selv?

**Eksempel**

Gitt likningen 

$$2x^2 +x =6$$

Denne kan skrives slik at det står null på den ene siden og du får:

$$2x^2+x-6 = 0$$

I likningen over er $ a=2$, $ b=1$ og $ c=-6$. 

Er det vanskelig å se hva tallene $a$, $b$ og $c$ blir, kan det være lurt å skrive uttrykket slik: 

$$ 2 \cdot x^2+ 1 \cdot x+( -6) =0 $$

Skal du løse denne likningen setter du inn verdiene for $a$, $b$ og $c$ inn i "abc-formelen" og du får løsningene:

$$x=\dfrac{-1 \pm \sqrt{1^2-4 \cdot 2 \cdot (-6)}}{2 \cdot 2} = \dfrac{-1\pm 7}{4}$$

Det vil si at $ x= -2$ eller $ x= \dfrac{3}{2}$. 

Nå skal du se mer på denne formelen og hvordan du kan bruke den.

 I filmen nedenfor viser vi hvordan vi kan bruke den generelle løsningen til andregradslikninger med noen eksempler. 

 <div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/82217854?h=57f6aa0caa&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

 ```{admonition} Oppgave 1 
: class: note

Gitt funksjonen $f(x)=2x^2+2x-4$.

Finn eventuelle nullpunkt til funksjonen ved regning.

Klarer du å løse oppgaven på ulike måter?
```

## Faktorisering med nullpunkt

Anta at en funksjon $g\) kan skrives på faktorisert for som 

  $ g(x)= 2(x-3)(x+1) \)

Da ser vi at det er to nullpunkt til $g\), nemlig $x=3\) og $x=-1\). For dersom vi skal løse likningen

    $ 2(x-3)(x+1)=0\)

så må enten $x-3=0\) eller $ x+1=0\). 

Motsatt gjelder også. Anta at en funksjon  $ f(x)= ax^2 + bx + c\) har nullpunkt $x_1\) og $x_2\). Da kan funksjonen skrives på faktorisert form slik:

          $f(x)= a \cdot x^2+ b \cdot x +c = a(x-x_1)(x-x_2)\)