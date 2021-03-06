# Lineære likningssystem med og uten digitale verktøy

![](/bilder/sportsutstyr.png)

Du kan bruke opplysningene på bildet til ovenefor til å finne ut hva én fotball koster, og hva én hockeykølle koster. I dette tilfellet kan det være at du klarer å løse dette problemet uten å sette opp noen likninger. Likevel vil vi bruke dette eksempelet til å vise prinsippene bak likningssystem. 

I et likningssystem er der to eller flere ukjente som vi ønsker å bestemme ut fra to eller flere likninger. 

Dersom vi lar prisen for en ball være $x$ kroner og prisen for en kølle være $y$ kroner, så får vi følgende likninger: 

$$\left[\begin{array}{c} x + y = 500\\ 3x + 2y = 1200 \end{array}\right]$$

En løsning av et slikt likningssystem er de $x$ og $y$ som er slik at de tilfredsstiller begge likningene samtidig. 

Det fins flere måter å løse slike likningssystem på. 

* Innsettingsmetoden
* Addisjonsmetoden
* Grafisk løsning
* Løsning ved å bruke et digitalt verktøy

Her skal du lære disse metodene.  

## Innsettingsmetoden

I eksempelet med ishockeykøllene og ballene fikk du følgende likningssystem:

$$\left[\begin{array}{c} x + y = 500\\ 3x + 2y = 1200 \end{array}\right]$$

Innsettingsmetoden går ut på å bruke den ene likningen til finne et uttrykk for den ene variabelen og så sette dette uttrykket inn i den andre likningen. 

Den øverste likningen gir at $ x=500-y$. Erstatter du nå $x$ med $500-y$ i den andre likningen får du en likning i kun $y$:

$$ 3(500-y)+2y=1200 $$

$$1500-y=1200$$

$$ y=300$$

Du kan nå sette dette inn i uttrykket du fant for $x$ og få $x=500-300=200$.

Altså er $x=200$ og $y=300$ .

$x$ sto for prisen til ballen og $y$ prisen til køllen. Det vil si at en ball koster 200 kr og en kølle koster 300 kr.

```{admonition} Oppgave 1
: class: note

Bruk innsettingsmetoden til å løse likningssystemet: 

$$\left[ \begin{array}{c} 2x + y = 9\\ 4x + 3y = 19 \end{array} \right]$$
```
 
 ## Addisjonsmetoden

 I videoen nedenfor får du se hvordan du kan løse likningssytem ved å bruke det som kalles for addisjonsmetoden. Denne metoden går ut på at du kan addere høyresiden av en likning til høyresiden av en annen likning så lenge du gjør det samme med venstresidene. Dette fungerer siden høyresiden og venstresiden av en likning skal være like. 

 <div style="padding:56.6% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/291457083?h=d38bee2759&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

I filmen så du at du kan addere et multiplum av en likning til en annen likning. Her ser du ett til eksempel som illustrerer dette. 

Løs likingssystemet

$$
\begin{align*}
3x + 2y & = 19 \\
2x  -  3y & = 4 
\end{align*}
$$

Dersom du ønsker å «bli kvitt» y-en fra denne likningen, så kan du multiplisere den øverste likningen med 3 og den nederste med 2. Da får du

$$
\begin{align*}
9x  + 6y  &= 57 \\
4x  -  6y  &= 8 
\end{align*}
$$

Addere du nå disse to likningene sammen får du

$$ 13 x = 65  \    \Leftrightarrow \ x=\dfrac{65}{13}=5.$$

Setter du dette inn i den øverste likningen, får du $ 3\cdot 5+2y=19$. Dette gir deg $ y=2$.

Løsningen på likningssettet blir da $ x= 5$ og $y=2$.

## Grafisk løsning

Alle $ (x, y) $ som passer inn i en lineær likning med to ukjente vil ligge langs en linje. Du vil lære mer om dette når vi skal jobbe med funksjoner. 

I videoen nedenfor får du se hvordan du kan løse likningssystemet 

$$
\begin{align*}
(I):& \ \ 2x + y  = 5 \\
(II):& \ \ x -  y  = -2 \\
\end{align*}
$$

ved å tegne inn de to linje som de to likningene representerer og så finne skjæringspunktet mellom disse linjene. 


![](/bilder/grafiskloening.png)



Dette er noe du må kunne gjøre både med «papir og blyant» og ved hjelp av digitale hjelpemidler.

## Å løse likninger med GeoGebra

Du skal nå lære å løse likninger med programmet GeoGebra. Om du ikke allerede har installert dette programmet kan du laste det ned fra nettsiden 

* http://www.geogebra.org/

I filmen nedenfor kan du lære litt om hvilke versjon du skal bruke og litt om selve programmet. 

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/320946963?h=628603a3d0&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


I videoen nedenfor viser vi hvordan du kan løse likninger ved å bruke GeoGebra CAS. 

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/284919386?h=7e3f28645b&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

I videoen nedenfor får du se hvordan du kan løse et system av likninger med GeoGebra CAS.

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/284922872?h=3ae9971d39&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

```{admonition} Oppgave 
: class: note

Bruk GeoGebra CAS til å løs likningssystemet:

$$
\begin{align*}
 4x + 2y  = 5 \\
 x -  3y  = -2 \\
\end{align*}
$$


```

<iframe src="https://www.geogebra.org/classic/nk6brket?embed" width="800" height="400" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>



