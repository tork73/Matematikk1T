# Bruk av den deriverte

Målet nå er at du skal 
* vite hva terrasse-, topp- og bunnpunkt er
* kunne finne topp- og bunnpunkt ved den deriverte
* kunne analysere funksjoner
* kunne løse praktiske funksjonsoppgaver

![](/bilder/tangenter.png)

## Når den deriverte er null

I videoen nedenfor skal vi drøfte hva det vil si at $ f'(x)=0$.

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/299173827?h=0cb0bb820d&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


```{admonition} Oppgave 1
: class: note

Figuren under viser grafen til to funksjoner.

![](/bilder/tografer.png)

Hvilken av de to funksjonene har denne fortegnslinja for den deriverte?

![](/bilder/frotegn1.png)
```

```{admonition} Fasit
: class: dropdown

Det er $g$ fordi i intervallene $x<0 \vee  2< x$ synker $ g$ og det er det samme som at $g' < 0$. I området $ 0 < x < 2 $ øker funksjonsverdiene mot høyre og $g'>0$. 

```


Funksjonen $f$ er gitt ved $f(x)=-2x^3 + 6x-4$

I videoen nedenfor ser du en løsning på hvordan du kan bestemme eventuelle topp- og bunnpunkter på grafen til $f$ ved regning.

Prøv selv, før du ser videoen!

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/86110624?h=430df53303&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


## Areal og omkrets av to kvadrater

Nå er vi klare til å se på praktisk bruk av derivasjon. Vi starter med å se på følgende problem. 

![](/bilder/kvadrater.png)

Figuren ovenfor er satt sammen av to kvadrater. Omkretsen av figuren er 16.

Hvor lange må sidene i hvert kvadrat være for at arealet av figuren skal bli minst mulig?

Bruk litt tid på å sette deg inn i problemet og tenk på hvordan du vil løse den før du går videre. Kanskje kan figuren under være til hjelp?

<iframe src="https://www.geogebra.org/classic/bkhmbb4a?embed" width="800" height="600" allowfullscreen="" style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

## Hva varierer?

I starten virker slike problem ganske uoversiktlig. Vi må tenke oss godt om og prøve å se for oss hvordan figuren kan variere. Tenker vi oss om kan vi komme til at det er de to sidelengdene som vil endre seg. I og med at omkretsen skal være 16, vil de to sidelengdene være avhengige av hverandre.

Da får vi bruk for variabler. Jeg velger å kalle de to sidelengdene for $x$ og $y$ og får denne figuren:

![](/bilder/kvadrater2.png)



Oppgaven gir at omkretsen skal være lik 16. Etter at jeg har innført variablene kan det uttrykkes matematisk og vi kan finne sammenhengen mellom de to sidelengdene 

$$O = 4 \cdot x + 4 \cdot y = 16 \implies y = \frac{16-4 \cdot x}{4} = 4 - x$$

Ut fra den virkelige situasjonen ser vi at vi må begrense verdiene. Sidelengdene kan ikke bli negative. Det betyr at $x \in \lbrack 0, 4 \rbrack$. Det samme vil da gjelde for $y$.

Da har vi funnet en sammenheng mellom de to sidelengdene og vi kan finne et funksjonsuttrykk for arealet av de to kvadratene 

$$
\begin{align*}
A(x) &= x^2 + y^2 \\
&= x^2 + (4 - x)^2 \\
&= x^2 + 16 - 2 \cdot 4 \cdot x + x^2 \\
&= 2x^2 -8x + 16
\end{align*}
$$

Nå vet vi hvordan hele arealet varierer med den ene sidelengden. Vi er klare for å undersøke når dette arealet er minst. Det kan vi gjøre med det vi har lært tidligere.

```{admonition} Oppgave 1
: class: note

Prøv å finne det minste arealet ved å skrive et program i Python som løser oppgaven.

Tenk også på hvordan du kan kontrollere svaret ditt med den deriverte.

På neste side vil du se en video som går gjennom en løsning.

Du kan skrive programmet her:

<iframe src="https://trinket.io/embed/python3/5e5f7bdf65" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen=""></iframe>
```

Her er en forklaring på hvordan oppgaven kan løses ved å benytte Python.

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/512444644?h=005026dd65&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

<br>

La oss også se hvordan vi kan finne et uttrykk for den deriverte når vi kjenner det opprinnelige funksjonsuttrykket.

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/512445346?h=dc7fed242a&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

## Oppsummering av løsning

Da har vi løst oppgaven hvor vi skulle finne det minste arealet de to kvadratene kan ha.

![](/bilder/kvadrater2.png)

Vi laget et program i Python som fant den gjennomsnittlige vekstfarten til mange x-verdier og tegnet punktene opp i koordinatsystemet. I programmet under er det funnet stigningstallet til sekanter i svært små intervall. De er bestemt av verdien til variabelen h. Grafen vi får tegnet er en tilnærming av grafen til den deriverte funksjonen.

```python
import matplotlib.pyplot as plt
import numpy as np

h = 0.001

def a(x):
    return 2*x**2-8*x+16

def Da(x):
    return (a(x+h)-a(x))/h

X = np.linspace(0,4,100)
plt.plot(X,a(X))
plt.plot(X, Da(X))
plt.grid()
plt.show()
```

Vi fant ut at den deriverte var $A'(x)=4x-8$ både ved å se på grafen, ved å bruke derivasjonsregler og benytte GeoGebra. Ved å finne når den deriverte er lik null kan vi slå fast den minste verdien funksjonen kan ha. I dette tilfellet er det når 
$x=2$. Arealet blir da $A(2)=8$.

## Størst overflate

Nå skal vi se på et nytt problem. 

Ei eske skal romme 100 liter og ha en kvadratisk bunn. Hva må høyden være for at overflaterarealet skal være minst mulig?

![](/bilder/eske1.png)

Videoen under gir en løsning på oppgaven. Prøv å løs oppgaven før du ser videoen. 

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/512829341?h=4ee63f2622&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


## Oppsummering

Da har vi brukt den deriverte til å løse noen oppgaver på flere måter. I alle har vi vært ute etter å finne ut når den deriverte er lik null. Finner vi et nullpunkt kan det gi viktige opplysninger. Her er en oppsummering

For en funksjon $f$ gjelder dette:

**Stasjonært punkt**

I et stasjonært punkt er $ f'(x)=0$.

**Bunnpunkt**

Hvis $f'(c)=0$ og $f'(x) $ skifter fortegn fra negativ til positiv i $x=c$, er $ (c,f(c) ) $ et bunnpunkt på grafen til $f(x)$.

**Toppunkt**

Hvis $f'(c)=0$ og $f'(x) $ skifter fortegn fra positiv til negativ i $x=c$, er $ (c,f(c)) $ et topppunkt på grafen til $f(x)$.

**Ekstremalpunkt**

Et ekstremalpunkt er $x$-verdien til et topp-/bunnpunkt.

**Terrassepunkt**

Grafen til $f(x)$ har et terrassepunkt der $f'(x)=0$ uten at $f'(x)$ skifter fortegn i punktet.

**Øker og avtar**

$f$ øker i et område $ \Leftrightarrow $ $f'(x)>0$ i området

$f$ avtar i et område $ \Leftrightarrow $ $f'(x)<0$ i området

