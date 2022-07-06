# Enkle kvadratiske likninger

Et uttrykk som kan skrives på formen $q^2$ kalles et fullstendig kvadrat. Tenk på det som et kvadrat som har lengde $q$ og arealet er $q^2$.

I denne leksjonen skal du lære å kunne omforme uttrykk til slike fullstendige kvadrater og utnytte det til å løse likninger. Uttrykket $x^2+6x+9$ er et eksempel på et slikt uttrykk. Dette er et fullstendig kvadrat siden 

$$x^2+6x+9 = (x+3)^2 $$

Å skrive slike uttrykk som fullstendige kvadrat vil bli nyttig når vi skal 

* løse likninger
* omforme uttrykk

Nå skal vi mest jobbe med å omforme uttrykk, men avslutningsvis skal vi få løse noen likninger.

## Fullstendig kvadrat

I videoen under forklarer vi hva fullstendige kvadrat er. Før du ser videoen, faktoriser disse to uttrykkene:

$$ x^2+4x+4$$

$$ x^2-14x+49$$


<div style="padding:56.6% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/291467805?h=96bb3e1f4e&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


```{admonition} Oppgave 1
: class: note

Hvilke av uttrykkene under kan skrives som et fullstendig kvadrat?

a) $x^2 + 4x + 4$

b) $x^2+8x$

c) $ 1-2x+x^2$

d) $4x^2 + 8x + 4$

e) $x^2$

f) $ (x+4)^2-4^2$

```

```{admonition} Løsning 
: class: dropdown

a) Dette er et fullstendig kvadrat fordi $x^2 + 4x + 4 = x^2 + 2\cdot 2 \cdot x + 2^2 = (x+2)^2$

b) Dette er ikke et fullstendig kvadrat fordi det kan ikke skrives på formen $q^2$.

c) Dette er et fullstendig kvadrat fordi $ 1-2x+x^2 = 1^2 -2 \cdot 1 \cdot x + x^2 = (1-x)^2$

d) Dette er et fullstendig kvadrat fordi 

$$4x^2 + 8x + 4 = ((2x)^2 + 2 \cdot 2x \cdot 2+ 2^2) = (2x+2)^2 = 4(x+1)^2$$

e) Dette er allerede skrevet som et kvadrat med sider x.

f) Dette kan ikke skrives som et kvadrat, $q^2$. 
 Regner du dette ut ser du at 
 
$$ (x+4)^2-4^2 = x^2 +8x = x(x+8)$$

```

```{admonition} Oppgave  2
: class: note

Løs likningen

$$x^2=4$$

Tenk etter hva oppgaven går ut på og hvordan du løser den før du går videre.
```

I videoen under skal du se nærmere på likningen $x^2=4$, hvordan du kan løse den og hva som egentlig står der.

<div style="padding:56.6% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/291467998?h=3cc6353528&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

<br>

![](/bilder/null.jpg)

## Produktregelen

Når produktet av to tall er null, vet vi at minst ett av tallene må være null. Denne sammenhengen  brukes ofte når vi løser likninger og kalles gjerne for produktregelen.

```{margin}
Tegnet $\vee$ betyr «eller». 
```
```{admonition} Produktregelen
: class: important

<br>

$$a \cdot b = 0 \ \Leftrightarrow \  a=0  \quad \vee \quad b=0$$
```





```{admonition} Oppgave  3
: class: note

Gitt denne likningen:

$$(x+2)(x-1)=0$$

Hva må $x$  være?
```

```{admonition} Løsning
: class: dropdown

Her må enten $x+2=0$ eller $x-1=0$. Det vil si at det er to løsninger: $\mathcal L = \{ -2, 1\}$.

```

```{admonition} Oppgave 4
: class: note

Hvordan kan du bruke produktregelen til å løse følgende likning? 

$$ 15x^2-3x=0$$
```

```{admonition} Løsning 
: class: dropdown

 Siden $3x$ er felles faktor i de to leddene, får du

$$ 15x^2-3x=3x(5x-1)=0$$

Faktorisering og produktregelen gir et kraftig verktøy når du løser likninger. Du får dermed at 

$$\begin{align*}15x^2-3x&=0\\3x(5x-1)&=0\\3x=0& \quad \vee \quad 5x-1=0\\x= 0 & \quad \vee \quad  x=\frac{1}{5} \end{align*}$$

```

## Enkle kvadratiske likninger

Tidligere  har du sett at $x^2 = 4$ er et eksempel på en kvadratisk likning. Det er et eksempel på den enkleste formen for kvadratisk likning.

Kvadratiske likninger finnes i mange varianter, alle har som fellestrekk at den siden av likningen som inneholder $x$ kan skrives på formen $q^2$. Noen eksempler er

$$3x^2-6=15$$

$$(x+2)^2=25$$

$$x^2-8x+16=9$$

```{admonition} Oppgave 5
: class: note

Hvordan kan det siste uttrykket skrives om slik at venstre siden blir på kvadratisk form? Forklar.

Hvordan kan du skrive om det første uttrykket slik det også blir på kvadratisk form.
```

```{admonition} Løsning
: class: dropdown

Ved andre kvadratsetning får du at

$$ x^2-8x+16= (x-4)^2$$

Bruker du dette, kan du løse den siste likningen slik:

$$
\begin{align*}
x^2-8x+16&=9\\
  & \Updownarrow \\
    (x-4)^2&=9\\
  & \Updownarrow \\
    x-4&=\pm\sqrt{9}\\
x-4&=\pm3\\
 x-4 = 3 \ \  & \vee  \ \  x-4 = -3\\
  x=7 \ \  &\vee  \ \ x= 1
\end{align*}$$


```
