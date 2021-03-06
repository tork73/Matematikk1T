# While-løkker

Nå skal du lære å bruke while-løkker. Det er løkker der Python gjør ulike beregninger så lenge en betingelse er oppfylt.  

```{code}
a = 1
sum  = 0
Så lenge a er mindre enn 10:
    adder a til sum
    øk a med 1
skriv ut sum
```

Her ser du at det setter opp en betingelse i tredje linje: så lenge a er mindre enn 10. Siden a i utgangspunktet er 1, så er dette sant. Sum vil derfor få en ny verdi 0+1=1 og a øker til 2. Da er fremdeles a  mindre enn 10, så vi addere a til sum og får sum = 1+2=3 og a blir lik 3. Slik fortsetter vi så lenge a er mindre enn 10. Resultatet blir at sum får verdien sum = 1+2+3+4+5+6+7+8+9 = 45.

![](/bilder/everyone.jpg "Foto: Adi Goldstein på Unsplash")

Vi har tidligere sett på løkker av typen

```{code}
for i in range(1, 11):
   s = s + i
```
I slike løkker gjennomløper tallet «i» alle tallene som er spesifisert av range-kommandoen. En annen type løkke som er nyttig å bruke er såkalte while-løkker. I en while-løkke vil en kode gjentas så lenge en betingelse er sann:

```{code}
while betingelse:
   kode som kjøres så lenge betingelsen er sann.
```

## Eksempel 1
I filmen nedenfor viser vi hvordan vi kan bruke en slik løkke til å printe ut alle kvadrattallene mindre enn 200.

<div style="padding:56.15% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/435784038?h=9b72504762&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

```{admonition} Oppgave 1
: class: note

Bruk Python til å bestemme hvor mange kubikktall som er mindre enn 1000. Husk at kubikktallene er tallene $1^3, 2^3, 3^3, \ldots$.
```

Du kan lage programmet her:

<iframe src="https://trinket.io/embed/python3/07fd44e51b" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen=""></iframe>

**Løsning:**

<div style="padding:56.15% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/435795131?h=93a4339a43&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

## Eksempel 2

Anna vil spare penger og skal hvert år sette 1000 kroner inn på en konto med fast rentefot lik 2,0 prosent. 

Hvor mange år vil det gå fra hun setter det første beløpet inn på kontoen til hun har mer enn 30000 kroner på kontoen? 

<div style="padding:56.15% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/435805090?h=20ddd07f26&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

## Eksempel 3

I filmen nedenfor viser vi hvordan vi kan bruke Python til å løse følgende problem: 

Anna skal spare penger på en konto med fast årlig rentefot lik 2,1 prosent. Hun ønsker at det skal være 200 000 kroner på kontoen like etter at hun setter inn det tiende beløpet. Hvor mye må hun spare hvert år for å oppnå dette? 


<div style="padding:56.15% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/436438878?h=a369279968&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


