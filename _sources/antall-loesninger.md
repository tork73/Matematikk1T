# Antall løsninger til andregradslikninger


Du har så langt lært å løse andregradslikninger ved å bruke abc-formelen. Du har kanskje oppdaget at andregradslikninger kan ha to, én eller ingen løsning. 

Målet nå er at du skal

* kunne drøfte antall løsninger til en likning
* kunne avgjøre betingelser på tallene $a$, $b$ og $c$ som gjør at likningen

$$ a x^2+ b x + c = 0 $$

har to, én eller ingen løsning

* kunne lage et program i Python som gir riktige antall løsninger (og løsningene)

![](/bilder/nullpunktantall.jpg)

```{admonition} Oppgave  1
: class: note

Løs likningene ved regning

1) $x^2+2x+1=0$
2) $x^2+2x+2=0$

```

Greide du å løse oppgavene? Begge likninger var litt spesielle. I denne videoen ser vi mer på dem og forklarer hvorfor. 

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/82221954?h=6f3872102d&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

<br>

```{admonition} Oppgave 2
: class: note

Vi skal nå se på følgende likning:

$$ x^2 + kx +4 = 0 $$

Her er $k$ et tall. 

Dersom $k = 0$ ser vi at likningen ikke har noen løsning, siden vi da får $x^2 = -4$. 

For hvilke verdier av $k$ har likningen

* to løsninger
* nøyaktig én løsning
* ingen løsninger


```

På forrige side laget vi følgende program for å løse en andregradslikning:

```python
from math import sqrt 
a = 2
b = 1
c = +6

x1 = (-b+sqrt(b**2-4*a*c))/(2*a)
x2 = (-b-sqrt(b**2-4*a*c))/(2*a)

print("Løsningene er x =", x1, "og x =", x2)
```

Vi så at programmet ikke fungerte dersom det som står under rottegnet er negativt.  I filmen nedenfor viser vi hvordan vi kan løse dette ved å bruke betingelser. 

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/478833247?h=eb9890412a&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

Her er koden vi laget i filmen:

```python
from math import sqrt
k = float(input("Skriv inn verdien for k: "))

D = k**2-16

if D > 0:
  x1 = (-k+sqrt(D))/2
  x2 = (-k-sqrt(D))/2
  print("To løsninger:")
  print("x=", x1)
  print("x=", x2)
elif D < 0:
  print("Likningen har ingen løsning")
else:
  x1 = -k/2
  print("Det er én løsning:")
  print("x=", x1)
```

```{admonition} Oppgave 3
: class:  note

På forrige side laget vi et program som gav riktig antall løsninger til likningen $x^2+ kx+4=0$

Kan du modifisere programmet nedenfor slik at vi får riktig antall løsninger (sammen med løsningene) til likningen

$$x^2 +3x+r = 0 $$

Input skal være tallet $r$ (ikke $k$). 
```

<iframe src="https://trinket.io/embed/python3/77f4ad31d6" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen=""></iframe>

<br>


**Oppsummering**

Vi har sett at likninger på formen $a x^2+bx+c=0$ har

* ingen løsning dersom uttrykket under rottegnet er negativt
* én løsning dersom uttrykket under rottegnet er null
* to løsninger dersom uttrykket under rottegnet er positivt


