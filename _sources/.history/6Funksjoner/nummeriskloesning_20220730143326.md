# Nummerisk løsning av likninger med Python 

De fleste likninger kan være vanskelige å løse algebraisk. Her skal du lære hvordan du kan løse slike ved å bruke numeriske metoder. 

Du skal kunne 

* forstå en algoritme som finner nullpunktene til en funksjon i et gitt intervall
* lage et program som utfører algoritmen
* kunne formatere svaret på en fornuftig måte
* forstå hvordan halveringsmetoden virker
* kunne lage et program som gjennomfører denne
* vurdere hvordan du kan tilpasse algoritmen slik at du får kontroll * på antall riktige desimaler i svaret. 

![](/bilder/nullpunkt-num.png)

## Introduksjon til numerisk løsning av likninger

I filmen nedenfor viser vi hvorfor det er viktig å kunne løse likninger numerisk. Vi viser hvordan vi kan løse likningen 

$$ 2^x + 3^{-x}=3$$

ved å bruke GeoGebra. Vi skal senere lage program i Python som gjør noe tilsvarende det som GeoGebra gjør.

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/484465523?h=1b5aae633b&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

## Nummerisk løsning; vi finner et nullpunkt

I filmen nedenfor viser vi en enkel algoritme som finner et nullpunkt til en funksjon. Vi starter med en startverdi og sjekker funksjonsverdien i de ulike punkta. Vi vet at dersom grafen krysser x-aksen i et intervall, så må det være et nullpunkt i dette intervallet. Dette gjelder i hvert fall når grafen er sammenhengende. 

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/484373483?h=790e1d7f6f&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

I forrige film fant vi en løsning til likningen $2^x-3x=0$. Vi fant at $x\approx 0.458$. Vi brukte da følgende kode:

```python
def f(x):
  return 2**x-3*x
s = 0
while f(s)>0:
  s = s + 0.001
print("Nullpunkter er x = ", s)
```

![](/bilder/trinket_plot1.png)

Vi har tegnet grafen til $f(x)=2^x-3x$ ovenfor. Vi ser at likningen $2^x-3x=0$ har to løsninger. 

```{admonition} Oppgave 1
: class: note

Gjør modifikasjoner av koden over og finn det andre nullpunktet. Skriv inn tallet med to desimalers nøyaktighet. 

<iframe src="https://trinket.io/embed/python3/9021e6434a" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

```

## Vi finner nullpuntkene i et intervall

I filmen nedenfor finner vi de to nullpunktene til funksjonen $f(x)=2^x+3^{-x}-3$ ved å bruke en numerisk algoritme. 

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/484526773?h=5d23b65641&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

I filmen på forrige side laget vi følgende program: 

```python

def f(x):
  return 2**x+3**(-x)-3
  
start = -2
slutt = 2

x = start
d = 0.0001

while x+d < slutt:
  if f(x)*f(x+d)<=0:
    print("Nullpunkt i x=", x)
  x = x + d

```
```{admonition} Oppgave 2
: class: note

Nå skal du lage et tilsvarende program som finner nullpunktene til funksjonen $g(x)=2^{-x^2+5}-1$ i intervallet $[-3, 3] $. 
Du kan lage programmet her: 



<iframe src="https://trinket.io/embed/python3/0462eaeb5d" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen=""></iframe>

```

## Formatering av print-funksjonen

Når vi skal printe desimaltall, kan det være hensiktsmessig å kunne formatere tallet slik at vi får ønsket antall desimaler med. Når vi løste likningen $2^x+3^{-x}-3=0$  fikk vi for eksempel at den ene løsningen var $x=-0.8078000000001313$. En fin måte å gjøre dette på er å bruke det som kalles for f-strenger. Det vil si formaterte strenger. I filmen nedenfor viser vi hvordan vi kan gjøre dette. 


<div style="padding:56.31% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/484789057?h=895609d8cd&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

Vi bruker f-strenger på følgende måte: 

```python
print(f"<Det vi vil printe>")
```
Mellom anførselstegnene kan du skrive vanlig tekst og du kan hente størrelsen til de ulike variablene du har laget i programmet. Har du for eksempel et en variabel a som er et desimaltall kan du formatere antall desimaler på følgende måte: 

```python
print(f"Her er a: {a:0.3f}")
```

Da vil vi få skrevet ut for eksempel «Her er a: 2.323» (om a for eksempel har verdien 2.323443434342). 

Prøv selv nedenfor. Se om du kan skrive ut tallet π med 5 desimaler. Husk at må importere π. Det kan du gjøre ved å skrive

```python
from math import pi
```

<iframe src="https://trinket.io/embed/python3/4cdd795fa2" width="100%" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen=""></iframe>

%## Oppsummering


Vi har jobbet med to algoritmer som løser likninger nummerisk. Begge algoritmene søkte etter x-verdier der funksjonsverdien skifter fortegn. Vi brukte at en funksjon $f$ har ulikt fortegn i to punkt $a$ og $ b$ dersom

$$f(a)\cdot f(b) < 0 $$ 

Dersom dette gjelder (eller vi får lik 0), så vet vi at det er et nullpunkt i intervallet $[a, b] $. Dette gjelder dersom grafen til $ f$ er sammenhengende. 

Vi har også sett at vi kan formatere print ved å bruke f-formatering. Her er et eksempel på en slik formatering: 

```python
print(f"Løsningen er x= {x}")
```
Vi kan også gjøre utregninger inne i krøllparentesene:
```python
a = 2
b = 3
print(f"Summen av {a} og {b} er {a+b}")
```
% Dette må jeg se på senere... 

<p>Før vi skal programmere i Python, har vi en oppgave til deg.&nbsp;</p>
<p>Vi har valgt et tall mellom 1 og 100. Kan du gjette hvilket tall det er? Hvor mange forsøk trenger du?
</p> 

%% javascript

<script type="text/javascript">
    // random value generated 
    var y = Math.floor(Math.random() * 100 + 1);

    // counting the number of guesses 
    // made for correct Guess 
    var guess = 1;

    document.getElementById("submitguess").onclick = function() {

        // number guessed by user      
        var x = document.getElementById("guessField").value;

        if (x == y) {
            alert("Gratulerer! " +
                guess + " forsøk ");
        } else if (x > y)
        /* if guessed number is greater 
                          than actual number*/
        {
            guess++;
            alert("Tallet er dessverre for stort. Prøv et mindre tall! ");
        } else {
            guess++;
            alert("Tallet er dessverre for lite. Prøv med et større tall! ")
        }
    }
</script>

<p><br></p>
<p>Kan du forklare hvorfor du alltid kan klare å komme fram til riktig tall etter høyst 7 forsøk?</p> 

