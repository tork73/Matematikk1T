# Python som kalkulator

Her skal du lære hvordan du kan sette inn i formler i Python. Du skal blant annet lære hvordan du 

* lagrer tall og andre typer objekter i Python
* hvordan du kan sette inn i formler
* bruke løkker til å gjenta utregninger flere ganger.

Du skal også lære litt om ulike datatyper.

![](/bilder/hund-maskin.jpg " Foto: Cookie the Pom på Unsplash")

Før vi kommer igang og skal lære mer om programmering, kan du se filmen nedenfor. I den forklarer vi litt om hvordan vi skriver og kjører  programmer som vi har laget.

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/585432330?h=c06659d317&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

Her er lenkene som er nevnt i filmen: 

* Anaconda: https://www.anaconda.com/products/individual 
* Thonny: https://thonny.org/ 

___

Vi har følgende regneoperasjoner i Python:

<table style="width:400px">
    <thead>
        <tr>
            <th scope="col" style="text-align: center;">Symbol</th>
            <th scope="col" style="text-align: center;">Operasjon</th>
            <th scope="col" style="text-align: center;">Eksempel</th>
            <th scope="col" style="text-align: center;">Resultat</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="text-align: center;">+</td>
            <td style="text-align: center;">Addisjon</td>
            <td style="text-align: center;">1+2</td>
            <td style="text-align: center;">3</td>
        </tr>
        <tr>
            <td style="text-align: center;">&nbsp;-&nbsp;</td>
            <td style="text-align: center;">Subtraksjon</td>
            <td style="text-align: center;">23-11</td>
            <td style="text-align: center;">12</td>
        </tr>
        <tr>
            <td style="text-align: center;">*</td>
            <td style="text-align: center;">Multiplikasjon</td>
            <td style="text-align: center;">4.3*5.5</td>
            <td style="text-align: center;">23.65</td>
        </tr>
        <tr>
            <td style="text-align: center;">**</td>
            <td style="text-align: center;">Potens</td>
            <td style="text-align: center;">2**3</td>
            <td style="text-align: center;">8</td>
        </tr>
        <tr>
            <td style="text-align: center;">//</td>
            <td style="text-align: center;">Heltallsdivisjon</td>
            <td style="text-align: center;">10//4</td>
            <td style="text-align: center;">2</td>
        </tr>
        <tr>
            <td style="text-align: center;">%</td>
            <td style="text-align: center;">Modulo (restledd)</td>
            <td style="text-align: center;">28 % 12</td>
            <td style="text-align: center;">4</td>
        </tr>
    </tbody>
</table>
<br>Merk at du må bruke punktum som desimalskilletegn i Python.<br><br>
<p></p>


<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/393901548?h=0c012f82c0&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


<p>Regn ut følgende oppgaver i konsollen nedenfor:&nbsp;</p>

 $ 34+5\cdot 32-1$

 $ 2^5-2^3$ 

Hva er klokken om 1000 timer til, når den er 10.00 nå?

<iframe src="https://trinket.io/embed/python3/bf133cd102?outputOnly=true&amp;runOption=console&amp;showInstructions=true" width="100%" height="200" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen=""></iframe>
<br> Hvis du får meldingen «Connection to server timed out...» må du klikke på &gt;_Console i menyen til trinket. &nbsp;


## Eksempel 1

I filmen nedenfor får du se hvordan vi kan skrive inne ulike størrelser som vi ønsker å sette inn i en formel. Vi skal først se hva

$$ T_n = \dfrac{n\cdot (n+1)}{2}$$

blir når $n = 100$. Deretter skal vi regne ut verdien til 

$$ s = v\cdot t + 0.5\cdot a \cdot t^2$$

 når $v = 10$, $t=1.5$ og $a = -9.81$.

<div style="padding:56.31% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/394405430?title=0&amp;byline=0&amp;portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen" allowfullscreen=""></iframe></div>
<script src="https://player.vimeo.com/api/player.js"></script>

```{admonition} Oppgave 1
: class: note   



Formelen for arealet \(A\) til et trapes er gitt formelen

$$ A = \dfrac{a+b}{2}\cdot h $$

![](/bilder/trapes.png "Et trapes")

Lag et program som regner ut arealet til trapeset når $a = 4.3$, $b = 3.2$ og $h = 2.0$. 
```

<iframe src="https://trinket.io/embed/python3/a973537f95" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen=""></iframe>

## Å be brukeren om input

I filmen nedenfor viser vi hvordan vi kan bruke kommandoen input til å be om informasjon fra brukeren av programmet. 

I filmen har vi skrivet inn følgende kode: 

```{code} ipython3
navn = input("Skriv inn navnet ditt: ")
print("Hei", navn, "Håper du får en fin dag!")
```

Når programmet kjøres, vil brukeren bli bedt om å skrive inn navnet sitt. Dette blir da lagret i variabelen navn. Denne kan vi så bruke videre. På den andre linjen har vi printet den til skjermen sammen med tekstene "Hei" og "Håper du får en fin dag". 


<div style="padding:56.31% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/435695906?h=979d4e7cfb&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


## Datatyper

De ulike objektene vi bruker når vi programmerer i Python er av det som vi kaller ulike datatyper. I første omgang er det tre datatyper som er viktig å kjenne til. Disse er int (heltall), float (desimaltall) og str (tekst-strenger). I filmen nedenfor viser vi hvorfor det er viktig å være bevisst dette når vi programmerer.

<div style="padding:56.31% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/394447529?h=e23dcaf237&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


Det er mange flere typer datatyper enn strenger og desimaltall i Python. Tabellen nedenfor viser fem slike datatyper som du vil møte etter hvert som du jobber med Python:&nbsp;</p>

<table border="0" cellspacing="0" cellpadding="3">
    <tbody>
                    <tr>
                        <td width="150" valign="top">
                            <p><b>Kode</b></p>
                        </td>
                        <td width="150" valign="top">
                            <p><b>Datatype</b></p>
                        </td>
                        <td width="150" valign="top">
                            <p><b>Eksempel</b></p>
                        </td>
                    </tr>
                    <tr>
                        <td width="150" valign="top">
                            <p>int</p>
                        </td>
                        <td width="150" valign="top">
                            <p>Heltall</p>
                        </td>
                        <td width="150" valign="top">
                            <p>434342</p>
                        </td>
                    </tr>
                    <tr>
                        <td width="150" valign="top">
                            <p>float</p>
                        </td>
                        <td width="150" valign="top">
                            <p>Desimaltall</p>
                        </td>
                        <td width="150" valign="top">
                            <p>3.14159</p>
                        </td>
                    </tr>
                    <tr>
                        <td width="150" valign="top">
                            <p>str</p>
                        </td>
                        <td width="150" valign="top">
                            <p>Streng (tekst)</p>
                        </td>
                        <td width="150" valign="top">
                            <p>"Her er en tekst"</p>
                        </td>
                    </tr>
                    <tr>
                        <td width="150" valign="top">
                            <p>bool</p>
                        </td>
                        <td width="150" valign="top">
                            <p>Boolsk verdi</p>
                        </td>
                        <td width="150" valign="top">
                            <p>False</p>
                        </td>
                    </tr>
                    <tr>
                        <td width="150" valign="top">
                            <p>list</p>
                        </td>
                        <td width="150" valign="top">
                            <p>Liste</p>
                        </td>
                        <td width="150" valign="top">
                            <p>[2, 4, "Sko", False]</p>
                        </td>
                    </tr>
    </tbody>
</table><br>

## Vi regner ut en sum i Python 


Vi har tidligere brukt blokkprogrammering til å regne ut summer. I filmen nedenfor skal vi regne ut summen 
      
$$1+2+3+\cdots+100$$
 
ved å lage et lite program. 

Vi skal da lage en for-løkke og vi skal bruke range-kommandoen. Dette svarer til nøyaktig det vi gjorde tidligere når vi brukte blokker. 

Se på følgende kode:

```{code}
s = 0 
for i in range(1, 101): 
   s = s + i**2 
print(s)
```

Kommandoen range(1, 101) gir oss altså tallene 1, 2, 3, ..., 100. Her har vi også brukt innrykk i linjen der det står s = s + i**2. Dette må vi gjøre for å fortelle programmet hva som skal være med i løkken vi lager. Siden print(s) ikke har et innrykk, så skal ikke s printes ut i hvert steg i løkken. 


<div style="padding:56.31% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/394422844?h=78cfd3e533&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


```{admonition} Oppgave 2
%: class: note



Se om du kan lage et program som regner ut summen 

$$ 1^2+2^2+3^2 +\cdots + 99^2 + 100^2$$
```

<iframe src="https://trinket.io/embed/python3/9f43d63965" width="100%" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen=""></iframe>

I filmen nedenfor ser du en løsning av oppgaven på ovenfor. 

<div style="padding:56.31% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/394432647?h=6fd00d9431&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

```{admonition} Oppgave 3
: class: note

Lag et program som ber brukeren om et helt tall $n$ og som deretter regner ut summen av de $n$ første oddetallene.

Du kan starte programmet ved å skrive n = int(input("Skriv inn et naturlig tall:" )
```



<iframe src="https://trinket.io/embed/python3/f6a79ae9bd" width="100%" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen=""></iframe>