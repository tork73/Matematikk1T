# Nullpunkt og likninger

Nå skal du se på hva som menes med nullpunktene til en funksjon og hvordan du skal finne de.
Målet er at du skal 

* vite hva et nullpunkt er
* kunne finne nullpunkt grafisk og ved regning
* kunne skrive nullpunkt med riktig notasjon
* kunne finne skjæringspunkt med digitale verktøy

![](/bilder/matthew-henry-HeVd38MWnw4-unsplash%20(1).jpg)


## Hva er et nullpunkt? 

Vi finner nullpunkt når vi løser likningen 
$f(x)=0$. Nullpunktene er x-verdiene som gjør at funksjonsverdien, det vil si utverdien, er lik null.

```{admonition} Oppgave 1
: class: note

I  koordinatsystemet nedenfor er grafen til funksjonen $f$ tegnet. Hva er nullpunktet til $f$?

![](/bilder/nullpunkt1.png)
```

```{admonition} Løsning
: class: dropdown

Fant du ut at nullpunktet var $x=1$ ?
På figuren under ser vi skjæringspunktet mellom grafen og x-aksen. Her er funksjonsverdien er lik null: $ f(x)=0 $.

x-verdien som bestemmer skjæringspunktet er $x=1$. Da har vi at nullpunktet er $x=1$.

![](/bilder/nullpunkt2.png)
```

```{admonition} Oppgave 2
: class: note

Bestem nullpunktene til funksjonen som har følgende graf: 

![](/bilder/nullpunkt3.png)

```

```{admonition} Løsning
: class: dropdown

Fant du disse nullpunktene? $x=-2$, $x=0$ og $x=2$. 

![](/bilder/nullpunkt4.png)

```

## Nullpunkt med GeoGebra


I filmen nedenfor viser vi hvordan vi finner nullpunkt med GeoGebra.


<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/320947509?h=10bc4933cf&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


```{admonition} Oppgave 3
: class: note

Funksjonen $f$ er gitt ved 

$$f(x)=x^2+x-2$$

Finn nullpunktene til $f$ med GeoGebra. 

<iframe src="https://www.geogebra.org/classic/fkcyv7sh?embed" width="100%" height="400" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

Klarer du å finne nullpunktene uten bruk av digitale verktøy?


```


## Nullpunkt ved regning og grafisk Løsning

Her er en video som forklarer mer om hva nullpunkt er og hvordan du kan finne noen nullpunkt ved regning.

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/321048760?h=6d4522b0f9&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

Tidligere skulle du finne nullpunktene til $f(x)=x^2+x-2$ ved å bruke et digitalt verktøy. Fant du nullpunktene?
Vi kan også benytte fullstendige kvadraters metode for å regne ut nullpunkt. 

$$
\begin{align*}
    x^2+x-2 &= 0 \\
      & \Updownarrow \\
    x^2+2\cdot x\cdot \frac{1}{2}-2&=0\\
      & \Updownarrow \\
    x^2+2+\cdot x\cdot \frac{1}{2}+\left(\frac{1}{2}\right)^2-\left(\frac{1}{2}\right)^2-2&=0\\
      & \Updownarrow \\
    \left(x+\frac{1}{2}\right)^2-\frac{1}{4}-\frac{8}{4}&=0\\
      & \Updownarrow \\
    \left(x+\frac{1}{2}\right)^2-\left(\frac{3}{2}\right)^2 &=0\\
      & \Updownarrow \\
     \left(x+\frac 1 2 + \frac 3 2 \right) \left( x+ \frac 1 2 -\frac 3 2 \right) & = 0\\
       & \Updownarrow \\
    (x+2)(x-1) & = 0
\end{align*}
$$

Vi ser at $x=1$ eller $x=-2$. 

La du merke til at vi faktoriserte da vi fant nullpunktene ovenfor? Ved å benytte fullstendige kvadraters metode fant vi at 

$$
\begin{align*}
x^2+x-2 &=0\\
  & \Updownarrow \\
    (x+2)(x-1)&=0
\end{align*}
$$

Vi fant nullpunktene ut fra hvilke x-verdier som gjorde at det faktoriserte uttrykket ble lik null.

$$ x=1 \quad  \vee \quad  x=-2$$
 Legg også merke til at: 

$$x^2+x-2 =(x+2)(x-1)$$

$$x^2+x-2 =(x-(-2))(x-1)$$

Det betyr at hvis vi vet nullpunktene kan vi faktorisere andregradsuttrykket. 
Kaller vi nullpunktene $x_1$ og $x_2 $ har vi at 

$$ax^2+bx+c=a(x-x_1)(x-x_2)$$

![](/bilder/faktorisering-nullpunkt.png)


```{admonition} Oppgave 4
: class: note

Bruk både fullstendig kvadraters metode og nullpunktmedtoden til å faktorisere $2x^2-5x+2$.

```

## Skjæringspunkt


Grafisk har du sett at nullpunkt er skjæringspunkt mellom en graf og $x$-aksen. To grafer kan også ha ett eller flere skjæringspunkt.

![](/bilder/skjaeringpunkt1.png)

Nå skal du se på hvordan du kan finne skjæringspunkt med digitale verktøy

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/339112176?h=26688f379e&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


```{admonition} Oppgave 5
: class: note

Gitt funksjonene:

$$f(x)=x^2+2x+2$$

$$g(x)=x+4$$

Finn skjæringspunktene til $f$ og $g$.

<iframe src="https://www.geogebra.org/classic/zjj4caux?embed" width="100%" height="600" allowfullscreen="" style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>
```

## Oppsummering


**Nullpunkt**

Nullpunktene til en funksjon $f$ finner du ved

* å løse likningen $f(x)=0$
* å lese av x-verdiene til skjæringspunktene mellom $f$ og $x$-aksen.


**Skjæringspunkt**

Skjæringspunktene mellom to funksjon er $f$ og $g$ finner du ved                                   

* å løse likningen $f(x)=g(x)$.
* å lese av skjæringspunktene grafisk.



**Faktorisering av andregradsuttrykk**

En andregradsfunksjon $f(x)=ax^2 + bx +c$ med nullpunkt $x_1$ og $x_2$ kan faktoriseres.

Da er $f(x)=ax^2+bx+c=a(x-x_1)(x-x_2)$


