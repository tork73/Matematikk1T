# Den deriverte

Målet nå er at du skal kunne

* gjøre greie for hva den deriverte er
* bestemme et uttrykk for $f'(x)$ for polynomfunksjoner og for potensfunksjoner
* bruke den derivert til å finne stigningstall til tangenter til grafer. 

![](/bilder/deriverte.png)

Vi har så langt sett på en del eksempler der vi for en gitt funksjon 
$f$ får laget en ny funksjon som forteller oss noe om hva stigningstallet til grafen til $f$ er i de ulike punkta. Denne stigningstallfunksjonen kaller vi for den deriverte til $f$, og vi noterer den som $f'$.

```{admonition} Den deriverte
: class: alert

For en funksjon $f$ er $f'(x)$ lik stigningstallet til tangenten til grafen til $f$ i punktet $ (x, f(x))$.
```
![](/bilder/tangent-i-punkt.png)

Vi skal nå utforske og lete etter en mønster som gjør av vi lett kan finne et uttrykk for $f'(x)$ for en del funksjoner. 

```{admonition} Oppgave 1
: class: note

Bruk Python til å tegne den deriverte til følgende funksjoner: 

* $ f(x)=x^2$
* $p(x) = x^3$
* $ g(x)=x^4$ 

Se om du klarer å finne et uttrykk for 

* $ f'(x)$
* $ p'(x)$
* $ g'(x)$

Du kan programmere her: 


<iframe src="https://trinket.io/embed/python3/890d40e954" width="100%" height="500" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen=""></iframe>
```


## Den deriverte til noen funksjoner

I oppgave 1 fikk du i oppgave å finne et uttrykk for den deriverte til tre  funksjoner. Her ser du en måte å løse oppgaven på. 

<div style="padding:56.31% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/511147881?h=fa69016fa4&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

## En derivasjonsregel


I filmen nedenfor viser vi et par eksempler på vår første derivasjonsregel

```{admonition} Derivasjonsregel 1
: class: important

Dersom $ f(x)=x^r$, der $ r$ er et reelt tall, så er $ f'(x)=rx^{r-1}$
```


<div style="padding:56.31% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/512917424?h=d3a0216765&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

## Flere derivasjonsregler

For noen funksjoner kan vi klare å finne et uttrykk for den deriverte nok så greit. Dette gjelder spesielt for polynomfunksjoner.  Vi kan da bruke ulike regler for å finne den deriverte. I filmen nedenfor tar vi for oss to slike regler. 

<div style="padding:56.31% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/512954023?h=d8376f5aa9&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

```{admonition} Derivasjonsregler
: class: important

* $(ax+b)' = a $
* $(x^n)' = n x^{n-1} $
* $(k \cdot f(x))' = k \cdot f'(x) $
* $ (f(x) + g(x) )' = f'(x) + g'(x) $
```
```{admonition} Oppgave 2
: class: note

Bruk derivasjonsreglene og deriver funksjonene.

A: $f(x)=4x^5 + 2x-2$

B: $g(x)=2x+3x^2$

C: $h(x)= 3x^2-4$

D: $k(x)= 6.3x^2-x-\frac{5}{4}$
```

```{admonition} Oppgave 3
: class: note

Prøv å finne likningen for tangenten til grafen til $f(x)=x^2-x-2$ i punktet $(3, f(3))$ 
```

```{admonition} Løsning
: class: dropdown

Fant du at likningen til tangenten til $f(x)=x^2 -x-2$ i punktet $x=3$ er lik $y=5x-11$? 

**Fremgangsmåte ved bruk av ettpunktsformelen:**

En måte å gjøre dette på er å bruke ettpunktsformelen $ y-y_1 = a(x-x_1)$, hvor $(x_1, y_1) $ er tangeringspunktet og $ a $ stigningstallet til tangenten.

For å bruke ettpunktsformelen trenger du tangeringspunktet og stigningstallet.

**Tangeringspunkt**

$ x=3$ gir $y= f(3) = 3^2-3-2 = 4$ , dvs tangeringspuntet er $ (3,4) $

Vi vet at den deriverte i ett punkt er lik stigningstallet til tangenten i dette punktet, dvs $ a = f'(3)$. Vi har $f'(x) = 2x-1$.  Da blir $a=f'(3)= 2 \cdot 3-1=5$, dvs $a=5$.

**Likningen til tangenten:**

Bruker vi ettpunktsformelen med $x_1 = 3, y_1 =4$ og $a=5$:

$ y-4 = 5(x-3) \Leftrightarrow y-4 = 5x-15 \Leftrightarrow y=5x-11$

![](/bilder/tangentxer3.png)

```




