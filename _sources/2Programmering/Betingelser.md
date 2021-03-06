# Programmering med betingelser 

Her skal du lære å bruke betingelser i Python. Vi bruker slike betingelser daglig. Hvis det er pent og varmt vær ute kan du gå i sommerklær. Hvis det regner må du bruke paraply. Hvis den totale vekten til personer i en heis er mer enn 700 kg, så skal en varsellampe lyse og heisen ikke gå. 
I Python bruker vi «if» til å teste om visse betingelser er oppfylt.

![](/bilder/roman-synkevych-vXInUOv1n84-unsplash.jpg "Foto Roman Synkevych på Unsplash")

Når vi skal lage et program, får vi ofte behov for å teste om visse variable tilfredsstiller ulike betingelser.

* Du vil at en bil skal rygge så lenge avstanden til en hindring er større enn 50 cm
* Du lurer på hvor lenge du må spare penger for å få råd til en bil som koster 200 000 kroner. Da vil du spare så lenge beløpet på kontoen er mindre enn det ønskede beløpet. 
* Du vil primtallsfaktorisere et naturlig tall. Da kan du dele tallet på de ulike primtallene som er mindre enn tallet, helt til du sitter igjen med tallet 1. 

![](bilder/faktorisering.png)

Bilder ovenfor: _En algoritme som faktoriserer et naturlig tall._

## Binære relasjoner
Når vi skal lage programmer som gjør slike tester, har vi ofte bruk for det vi ofte kaller for binære relasjoner.

| | |
|--|--|
|Rekasjon| Betydning|
|a == b| tester om a er lik b|
|a != b| tester om a er ulik b|
|a < b| tester om a er mindre enn b|
|a <= b| tester om a er mindre eller lik b|
|a > b| tester om a er større enn b|
|a >= b| tester om a er større eller lik b|

Vi kan bruke if-kommando når vi skal teste om en betingelse er oppfylt. Denne brukes slik: 

```{code}
if betingelse 1 er sann:
   kode som skal kjøres om betingelse 1 er sann (True)
elif betingelse 2 er sann: 
   kode som skal kjøres om betingelse 2 er sann 
else:
   kode som kjøres om ingen av betingelsene er sanne
```
Legg merke til at vi på linje tre har skrivet elif. Dette er en forkortelse for «else if». Det betyr at dersom betingelse 1 ikke er sann og betingelse 2 er sanne, så skal koden som kommer på linjen (eller linje) etter linjen med elif kjøres. 

Legg også merke til at vi har innrykk når vi skriver inn kodene som skal kjøres dersom du ulike betingelsene er oppfylt. 

## Eksempel

I filmen nedenfor lager vi et program som ber brukeren om alderen. Programmet skal så printe en tekst som forteller brukeren at han eller hun er

* et barn om alderen er mindre enn 14 år
* en ungdom om alderen er 14 år eller mer og lavere enn 18 år
* voksen om alderen er 18 år eller mer. 

<div style="padding:56.15% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/435753947?h=a59cca4d08&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


```{admonition} Oppgave 1
: class: note

Lag et program som ber brukeren om å oppgi et helt tall. Programmet skal printe ut en tekst som forteller om tallet er et oddetall eller et partall. Skriver brukeren for eksempel inn tallet 54, skal programmet printe ut:&nbsp;</p>
<div class="editor-indent"
    style="margin-left: 30px;">
    <p>Tallet 54 er et partall</p>

</div>
```

Du kan lage programmet her:<br><br>
<iframe src="https://trinket.io/embed/python3/22420215c8" width="100%" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen=""></iframe>


I filmen nedenfor viser vi en måte å løse oppgaven der vi skulle teste om et tall var oddetall eller partall. 

<div style="padding:56.15% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/435768167?h=408859a7cf&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>



