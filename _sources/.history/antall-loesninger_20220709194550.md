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

