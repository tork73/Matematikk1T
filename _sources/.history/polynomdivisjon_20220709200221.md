# Nullpunktsetningen og polynomdivisjon


Her sjal vi se på polynomdivisjon og hvordan vi kan dividere et polynom med et annet. 

Målet er at du skal kunne

* utføre polynomdivisjon
* kjenne til algoritmen for polynomdivisjon
* vite hva nullpunktsetningen er
* kunne finne en faktor til et polynom

___


## Dividere to tall

Tidligere har du nok gjennomført flere delingsoppgaver. Kanskje er det lenge siden og du har glemt hvordan du gjør det?

Nå når vi skal dividere polynomer vil du få bruk for samme tankegang som ved divisjon av to tall. Her kan du se hvordan en elev har gjennomført en divisjon og funnet to forskjellige måter å skrive svaret

![](/bilder/langdivisjon.jpg)

Bruk litt tid og repeter hva denne eleven har gjort. 

* Hvorfor fungerer denne framgangsmåten?
* Hvordan fant eleven svaret skrevet som et blandet tall?

Etter at du har tenkt på det kan du fortsette.

## Introduksjon til polynomdivisjon

Nå skal du se en film som gir en introduksjon til polynomdivisjon. Filmen vil også vise sammenhengen mellom polynomdivisjon og den typen divisjon du tidligere har gjort.

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/399087249?h=50c11646c1&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

```{admonition} Oppgave 1
: class: note

Nå kan du prøve deg på en enkel polynomdivisjon. Løs oppgaven 

$$(x^2-3x+2):(x-1)$$

```

```{admonition} Løsning
: class: dropdown

$$\begin{array}{l}
\,(\,\,{x^2} - 3x + 2)\,\,:\,\,(x - 1) = x - 2\\
\underline { - {x^2} - x} \\
\,\,\,\,\,\,\,\,\,\, - 2x + 2\\
\,\,\,\,\,\,\,\,\underline {\,\,\,\,\,\,\,2x - 1} \\
\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,0
\end{array}$$

Her kan vi se at divisjonen gikk opp. Det ble ingen rest!

Legg også merke til at vi nå kan faktorisere slik at polynomet kan skrives som

$$x^2-3x+2 = (x-1)(x-2)$$

En slik faktorisering er et nyttig resultat av polynomdivisjon.
```

## Forklaring av polynomdivisjon

Da har du prøvd deg på en polynomdivisjon og sett noen eksempler på framgangsmåten. Hvorfor fungerer metoden?

I filmen under får du en forklaring på hvorfor algoritmen vi brukte for å utføre polynomdivisjon fungerer.

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/399087302?h=9819b1b648&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

<br>

Snart skal du få se en film som viser flere eksempler på polynomdivisjon. Før du ser filmen kan det være lurt om du prøver på de samme eksemplene. 

Disse oppgavene vil du få en forklaring på

$$(x^3-2x^2+4x+9):(x+1)$$

$$(4x^3-2x^2+3):(2-x^2)$$

Nå kan du prøve deg på disse oppgavene.

Tips: Det kan være lurt å skrive om den siste oppgaven som 

$$(4x^3-2x^2+3):(-x^2+2)$$

## Flere eksempker

Her kommer en film med flere eksempler på polynomdivisjon

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/399087356?h=4e988c5687&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

## Nullpunkt gir faktorisere

Når vi skal utføre en polynomdivisjon er det nyttig å vite om divisjonen går opp. I denne filmen skal du se at hvis vi kan finne nullpunkt til et polynom så vet vi også en faktor i polynomet. Det betyr at vi vet at divisjonen må gå opp.

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/399087389?h=1ad39b0861&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

## Nullpunktsetningen

Resultatet vi kom fram til i filmen kalles nullpunktsetningen