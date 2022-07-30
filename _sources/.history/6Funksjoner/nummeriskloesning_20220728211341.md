# Nummerisk løsning av likninger med Python I

De fleste likninger kan være vanskelige å løse algebraisk. Her skal du lære hvordan du kan løse slike ved å bruke numeriske metoder. 

Du skal kunne 

* forstå en algoritme som finner nullpunktene til en funksjon i et gitt intervall
* lage et program som utfører algoritmen
* kunne formatere svaret på en fornuftig måte

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

```

```