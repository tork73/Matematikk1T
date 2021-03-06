# Tall og tallbehandling

På denne siden skal du lære å

* kunne regne ut sammensatte regneuttrykk med heltall, potenser og parenteser
* kunne bruke parenteser, de fire regneartene og potenser
finne svaret på oppgaver som denne: $\text{-}2^2+2 \cdot (2-3)^2 -(3-6)+(1-2) \cdot (\text{-}2)$ 
* kjenne til de ulike tallmengdene vi bruker (naturlige tall, hele tall, rasjonale tall, reelle tall.) 
* kunne gjøre enkle utregninger i Python

Når du skal skrive matematikk, kan du benytte matematiske symboler. I denne introduksjonsvideoen vil du møte noen av symbolene og en introduksjon til hvordan du kan bruke dem. På den neste siden vil du få vite mer om det matematiske språket.

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/448593800?h=665099a6be&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

## Ledd, sum, faktor og produkt 

Fra ungdomsskolen er du kjent med de fire regningsartene: addisjon, subtraksjon, multiplikasjon og divisjon. Her følger en liten repetisjon.

Når vi adderer, får vi en sum. Tallene før og etter addisjonstegnene kalles ledd.  

$$\underbrace{3x}_{\text{ledd}} + \underbrace{x}_{\text{ledd}} + \underbrace{2}_{\text{ledd}} = \underbrace{4x+2}_{\text{sum}}$$

Når vi subtraherer, får vi en differanse. Tallene før og etter subtraksjonstegnene kalles ledd.

$$\underbrace{30}_{\text{ledd}} - \underbrace{10}_{\text{ledd}} = \underbrace{20}_{\text{differanse}} $$

Når vi multipliserer, får vi et produkt. Tallene før og etter multiplikasjonstegnene kalles faktorer.


$$\underbrace{2}_{\text{faktor}} \ \cdot \ \underbrace{3}_{\text{faktor}} \ \cdot \ \underbrace{x}_{\text{faktor}} \ = \ \underbrace{6x}_{\text{produkt}} $$

Når vi dividerer, får vi en kvotient. Divisjonstegnet kan også skrives som brøkstrek. Tallene over og under brøkstreken kalles henholdsvis for teller og nevner. 

$$ \underbrace{4}_{\text{dividend}} \ : \ \underbrace{2}_{\text{divisor}} = \ \dfrac{\overbrace{4}^{\text{teller}}}{\underbrace{2}_{\text{nevner}}} \ = \ \underbrace{2}_{\text{kvotient}} $$

(Hentet fra NDLA)

```{admonition} Oppgave 1
: class: note



Hvilken kalkulator regner riktig?

Tomasz og Kari fikk denne oppgaven: 

$$3+2\cdot 4$$


Begge tar fram kalkulatoren og skriver inn uttrykket, ved å trykke tastene, som det står. Kalkulatoren til Tomasz viser 11. Kalkulatoren til Kari viser 20.

Hvorfor blir det to forskjellige svar? De har trykket på de samme tastene...
```

```{admonition} Oppgave 2
: class: note

Vi har sett at 20 er en annen måte å skrive 
$(3+2)\cdot4$.

Nå skal du prøve å skrive 24 som et regnestykke. Gjør det gjerne så vanskelig som mulig.
```

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/393901548?h=0c012f82c0&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

<p>Du har følgende regneoperasjoner i Python:</p>
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

<p>Regn ut følgende oppgaver i konsollen nedenfor:&nbsp;</p>

 $ 34+5\cdot 32-1$

 $ 2^5-2^3$ 

Hva er klokken om 1000 timer til, når den er 10.00 nå?

<iframe src="https://trinket.io/embed/python3/bf133cd102?outputOnly=true&amp;runOption=console&amp;showInstructions=true" width="100%" height="200" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen=""></iframe>
<br> Hvis du får meldingen «Connection to server timed out...» må du klikke på &gt;_Console i menyen til trinket. &nbsp;

## Hva er forskjellen på $\text{-}2^2$ og $(\text{-}2)^2$ ?

Kanskje er den siste potensen mest åpenbar siden hele grunntallet er inne i en parentes?

$$(-2)^2=(-2) \cdot (-2) = 4$$

Parentesene benyttes til å vise hva grunntallet i potensen er.
I det andre tilfellet er det ikke like åpenbart. «$-2^2$» betyr «det negative tallet $2^2$». Altså «$-4$».

Dette kan også skrives ved hjelp av parenteser: 

$$-2^2 = - (2 \cdot 2)$$

Denne skrivemåten brukes ikke, siden det står akkurat det samme med eller uten parenteser. I matematikken er man opptatt av å skrive så få symboler som mulig. Samtidig er det viktig at vi bruker tilstrekkelig med symboler, slik at det vi skriver blir riktig.

Parentesene utgjør ofte en stor forskjell:
            
$$-2^2=-2 \cdot 2= -4 $$
            
$$(-2)^2=(-2) \cdot (-2)= 4$$

```{admonition} Oppgave 3
: class: note

Regn ut $-3^2$. 
```


## Negative tall
Negative tall. Positive tall. Navnene avslører noe om opprinnelsen. De negative tallene ble ikke godt mottatt da de kom. Negative tall ble brukt både i Kina og India i flere tusen år før de kom til Europa. Her møtte de negative tallene motstand. Det kan skyldes matematikernes utgangspunkt i geometrien. Det vil si at tallene ble sett på som lengder til linjestykker og andre geometriske objekter (som omkrets til en sirkel). Det gav ikke mening å snakke om negative lengder. Rundt 1600-tallet ble de negative tallene gradvis akseptert i Europa.

Negative tall er greie å ha i alle tilfeller hvor vi skal beskrive noe som er mindre enn null. Det kan være temperaturer, kapital, saldoen på bankkontoen og i mange andre sammenhenger.


Et negativt tall er et tall som er mindre enn null. Et eksempel er −2.

Da har vi at $2+(−2)=0$.

$−2$ er det tallet som gjør at summen med tallet 2 blir null. Slik kan vi definere de negative tallene.

Videoen under gir en innføring i hva negative tall er, hvorfor vi benytter negative tall, og litt om regning med negative tall.

<div style="padding:56.6% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/289850693?h=96b5a39ee8&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

Når vi regner med negative tall kan det oppstå forvirring og reglene kan være vanskelige å forstå.

Hvorfor blir produktet av et positivt og et negativt tall negativt?

Videoen under gir en forklaring

<div style="padding:56.6% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/289850677?h=9c6780c28d&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

Hvorfor blir produktet av to negative tall positivt?
Her er en video som forklarer det.

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/310180795?h=c04b6b1441&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


```{admonition} Oppgave 4
: class: note

Regn ut $(1−2)\cdot(3−5)$ på to måter. 
```



<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/448598725?h=a5da98b45a&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

Så langt har vi kun sett på to tallmengder, nemlig de naturlige tall $\mathbb N$ og de hele tall $ \mathbb Z$:

$$ \mathbb N = \{1, 2, 3, 4, \cdots \}$$

$$\mathbb Z = \{\cdots, -3, -2, -1, 0, 1, 2, 3, \cdots \}$$

Men hva skjer når vi dividerer to tall?  Vi kan dividere 8 med 4 og få 2, som er et helt tall. Men dersom vi for eksempel dividerer 1 med 2, blir resultatet ikke et helt tall. Vi får brøken $\dfrac{1}{2}$. For å kunne dividere hele tall, må vi på ny utvide tallmengden vår. Vi må inkludere alle tall som består av brøker med hele tall i teller og nevner.

Tall som kan skrives som brøker med hele tall i teller og nevner, kalles rasjonale tall. Disse symboliseres med $\mathbb{Q}$.

Vi kan anvende regneoperasjonene addisjon, subtraksjon, multiplikasjon og divisjon på rasjonale tall og få et rasjonalt tall som resultat.