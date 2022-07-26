# Eksponentialfunksjoner

## Hva er en ekspoentialfunksjon? 


Nå er det eksponentialfunksjoner som står for tur. 

Målet nå er at du skal 

* vite hva en eksponentialfunksjon er
* vite hvordan grafen til en eksponentialfunksjon ser ut
* vite hva en vekstfaktor er
* kunne sette opp en eksponentialfunksjon ut fra praktiske situsjoner

![](/bilder/eksponentiell.jpg)


Har du hørt historien om sjakkbrettet og risen?

Her er det flere historier, hvor land, navn og korntype varierer. Et sammendrag er slik:

Historien vil ha det til at da oppfinneren av sjakkbrettet viste det fram for herskeren i landet, ble herskeren så fornøyd at han ba oppfinneren om å fortelle hvordan han kunne belønnes. Oppfinneren sa at han ønsket et riskorn for den første ruta på sjakkbrettet, to for den andre, fire for den tredje, åtte for den fjerde osv.

For hver rute ønsket han en fordobling. Herskeren i landet mente at det var en beskjeden belønning og aksepterte ønsket. Det skulle vise seg at han tok feil.

Hvor mange riskorn vil det være i rute nummer 11?

![](/bilder/sjakk1.png)

Det viser seg at det etter hvert blir mange riskorn i rutene på sjakkbrettet. Nå skal du prøve å finne funksjonsuttrykket til en funksjon som har nummeret på ruta som innverdi og antall riskorn som utverdi.

Et tips er at du får bruk for potenser.

Funksjonsuttrykket til funksjonen som har rutenummer som innverdi og antall riskorn i ruta som utverdi er:

$$a \left(n \right) =2^{n-1}$$

Her er $n$ nummeret på ruta og $ a\left(n \right) $ gir antall riskorn.

Det er 64 ruter på et sjakkbrett. I den siste ruta blir det

$$2^{63}=9223372036854775808$$

riskorn. Det er mye ris, det! Funksjonen er et eksempel på en eksponentialfunksjon.

Her kommer en oppgave som er en oppvarming til videoen nedenfor.

```{admonition} Oppgave 1
: class: note

Emil setter inn 2000 kr i banken på en konto som gir 2 prosent rente hvert år.

Hvor mye penger har han i banken etter

a) 1 år?

b) 2 år? 

Klarer du å finne hvor mye penger han har i banken etter

c) 12 år?
```

I denne videoen vil du se hva en eksponentialfunksjon er og noen praktiske eksempler på slike funksjoner.

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/339850500?h=025fb09836&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

## Eksponentialfunksjoner med Python 

I filmen nedenfor viser vi hvordan vi kan løse oppgaven med Karis sparebeløp ved å bruke Python. 


<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/481636748?h=5fc87b38a5&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


I eksempelet med Kari fant vi at hun hadde over 2000 kroner på konto etter 21 år. Vi brukte da følgende kode: 

```python
def B(x):
  return 1000*1.0345**x
t = 0
while B(t)<2000:
  t = t + 1

print(t)
print(B(t))
```

```{admonition} Oppgave 1
: class: note

Da vi løste oppgaven grafisk i GeoGebra fant vi at beløpet passerte 2000 kroner etter ca 20,4 år. 

Se om du kan modifisere koden over slik at du finner dette ved tallet. Du kan programmere her: 

<iframe src="https://trinket.io/embed/python3/ee7f7eb914" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen=""></iframe>
```

I filmen nedenfor viser vi hvordan vi kan finne mer nøyaktig når beløpet til Kari passerer 2000 kroner. 

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/481649055?h=6c6f9da791&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


**Undersøk**

Nedenfor ser du grafen til funksjonen $f(x)=a\cdot k^x$. Undersøk hvordan tallene $a$ og $k$ påvirker grafens plassering og form ved å teste ut ulike verdier for $a$ og $k$ for ulike plasseringer av punktene $A$ og $B$. 

<iframe scrolling="no" src="https://www.geogebratube.org/material/iframe/id/gqahvt9h/width/793/height/518/border/888888/rc/false/ai/false/sdz/false/smb/false/stb/false/stbh/true/ld/false/sri/false/at/preferhtml5" style="border: 0px;" width="793px" height="518px"> </iframe>








```{admonition} Eksponentialfunksjon 
: class: important

En eksponentialfunksjon skrives på formen

$$f(x)= a \cdot b^x, \ \ \ \ \ b > 0$$

hvor $a$ er startverdien og $b$ er vekstfaktoren. Figuren under viser hvordan ulike verdier for $b$ påvirker grafen.
```

![](/bilder/eksponentiell_vekst.png)


```{admonition} Vekstfaktor
: class: important

Dersom vi har en prosentvis vekst (eller reduksjon) vil vi få en eksponentialfunksjon. Grunntallet kaller vi for vekstfaktoren. 

$p$ prosent økning gir vekstfaktor $ k=1+ \dfrac{p}{100}$

$p$ prosent nedgang gir vekstfaktor $k= 1- \dfrac{p}{100}$

```

