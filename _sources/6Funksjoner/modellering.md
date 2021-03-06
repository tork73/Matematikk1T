# Modellering med funksjoner



Nå skal vi se nærmere på modellering og hvordan matematiske modeller kan hjelpe oss til ta avgjørelser.

Du skal kunne

* vite hva modellering er
* kjenne til hvordan vi kan finne modeller ved regresjon (funksjonstilpassing)
* vurdere modellene

![](/bilder/modellering_1.png)

## Hva er modellering?

Her er en video som prøver å forklare det og gir en introduksjon til hvordan vi kan bruke GeoGebra til hjelp. Senere skal vi se i mer detalj på hvordan vi får lagt inn data og finner de riktige kommandoene i GeoGebra.

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/479025997?h=397146abfd&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

## Lineær regresjon

Når vi skal finne en modell ønsker vi ofte å finne sammenhenger mellom to størrelser. I tabellen nedenfor ser du folketallet i en kommune for noen utvalgte år.


|     År    |  1990  |  1995  |  2000  |  2005  |  2010  |
|:---------:|:------:|:------:|:------:|:------:|:------:|
| Folketall | 211 826 | 221 717 | 229 496 | 239 209 | 256 600 |

Dersom vi plotter tallene i tabellen i et koordinatsystem, med antall år etter 1990 på x-aksen og folketallet langs y-aksen, får vi følgende:

![](/bilder/folketallBergen.png)

Vi ser at punkta ligger tilnærmet på en rett linje. I denne leksjonen skal du lære hvordan du kan bestemme en slik linje som passer bra med slike punkt. Vi sier at vi finner en lineær modell for folketallet i dette tilfellet.

**Aktivitet**

Nedenfor er det tegnet inn fire blå punkt i et koordinatsystem. Disse gir en tilnærmet lineær sammenheng $y=f(x)$. Flytt på punkta $E$ og $F$ slik at denne tilnærmingen blir bra.


<iframe scrolling="no" src="https://www.geogebratube.org/material/iframe/id/juqtwqax/width/702/height/448/border/888888/rc/false/ai/false/sdz/true/smb/false/stb/false/stbh/true/ld/false/sri/false/at/preferhtml5" width="702px" height="448px" style="border: 0px;"> </iframe>

## Hva mener vi med «beste tilpasning»?

Du  fant kanskje ut at $ f(x)=-0,6x+5,7$ passet bra med de fire punkta. Men hva gjør en linje bedre enn en annen? I videoen nedenfor lærer du mer om akkurat dette!


<div style="padding:56.21% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/339099261?h=8005a21e66&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


## Regresjon med GeoGebra

Nå skal vi se mer på hvordan vi kan finne lineære regresjoner med GeoGebra og hvordan vi kan benytte funksjonsuttrykket.

<div style="padding:56.34% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/339099903?h=a40168a037&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


```{admonition} Oppgave 1
: class: note

Tabellen nedenfor viser folketallet i Stord kommune for noen utvalgte år.

| Årstall     |  1990 |  1993 |  1996 |  1999 |  2002 |  2005 |  2008 | 20011 |  2012 |
|-------------|------:|------:|------:|------:|------:|------:|------:|------:|------:|
| Folkemengde | 14483 | 15293 | 15741 | 16071 | 16219 | 16516 | 17092 | 17804 | 17957 |

Bestemme en lineær funksjon 
$f(x)$ som passer bra med tallene i tabellen. La $x$ være antall år etter 1990.

Hva kan vi forvente at folketallet blir i 2020 i følge denne modellen? 

```


<iframe src="https://www.geogebra.org/classic/zpygu7qr?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>
<p>

I filmen nedenfor kan du se hvordan oppgaven kan løses. 

<br>

<iframe src="https://player.vimeo.com/video/82904129?title=0&amp;byline=0&amp;portrait=0" webkitallowfullscreen="" mozallowfullscreen="" allowfullscreen="" frameborder="0" height="449" width="800"></iframe>

<br>



Nedenfor ser du en tabell som viser folketallet i Trondheim kommune. Tidligere har vi sett på hvordan vi kan finne lineære funksjoner ved regresjon i GeoGebra. Nå skal vi prøve å finne andre funksjonsuttrykk som måtte passe. Det gjør vi på samme måte, men nå skal du bruke menyen for å se om andre funksjonstyper kan være bedre modeller.

|           År | Antall |
|--------------|--------|
| 2000         | 153734 |
| 2001         | 155162 |
| 2002         | 156455 |
| 2003         | 157887 |
| 2004         | 159612 |
| 2005         | 161440 |
| 2006         | 163966 |
| 2007         | 167204 |
| 2008         | 170749 |
| 2009         | 173891 |
| 2010         | 176737 |
| 2011         | 179380 |
| 2012         | 182278 |
| 2013         | 185631 |
| 2014         | 188005 |
| 2015         | 190955 |
| 2016         | 193420 |
| 2017         | 196514 |
| 2018         | 199595 |
| 2019         | 202235 |


Vi må legge inn dataene i regnearket i GeoGebra og følge samme framgangsmåte som tidligere. Etter å ha markert området vi ønsker å benytte for å finne et funksjonsuttrykk velger du regresjonsanalyse (klikk på ikonet med søylediagram). Da kommer menyen hvor vi tidligere valgte lineær regresjon opp. 

![](/bilder/regresjon.png)

Nå skal du prøve de forskjellige valgene og se om du kan finne funksjonstyper som passer. Etter at du har prøvd på det vil du på neste side se en video hvor framgangsmåten forklares og modellene diskuteres.

<p>Her er tabellen i et regneark i GeoGebra. Du kan bruke det for å gjøre oppgaven</p>
<iframe src="https://www.geogebra.org/classic/z6b44ukm?embed" width="100%" height="600" allowfullscreen="" style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

## Befolkningen i Trondheim

Her er en video hvor GeoGebra benyttes for å finne modeller som kan beskrive antall innbyggere i Trondheim ut fra den gitte tabellen. Vi ser også på prognosene kommunen har laget.

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/480692936?h=b8c22c0e34&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


## Oppsummering

Ved å benytte GeoGebra har vi funnet funksjonsuttrykk som passer til de dataene vi har lagt inn. Det har vi gjort ved regresjon. Det kalles også funksjonstilpassing. Vi har sett at vi kan velge mellom flere funksjonstyper. Hvilken som passer best må vi avgjøre selv ved å vurdere resultatet opp mot de dataene vil har.

Dette kan være nyttig når vi skal løse ulike praktiske problem der vi har målte verdier.