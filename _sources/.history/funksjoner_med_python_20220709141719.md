# Funksjoner med Python

## Definere funksjoner i Python

I programmeringsspråk som Python kan en definere funksjoner. Det kan være greit å vite at funksjoner i programmering skiller seg noe fra funksjoner slik vi er vant med å bruke dem i matematikken. Her skal vi bruke funksjoner i Python på samme måte som i matematikken.

Filmen gir en introduksjon til hvordan det kan gjøres.

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/407928584?h=4e723e44ec&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


I filmen har vi sett hvordan vi kan definere funksjoner i Python og hvordan vi seinere kan benytte funksjonene i programmet. Et av eksemplene var

```python
def f(x):
    return x**2+3

def g(x):
    return x*4

print(g(3) - f(1))
```

Vi kan se at funksjonene defineres med kommandoen **def**
Så følger navnet på funksjonen, som i dette eksemplet er **f** og **g**. 

Parentesen forteller hva som skal sendes over til funksjonen og navnet på variabelen som benyttes. I eksemplet har vi valgt å kalle variabelen for x.

Til slutt kommer kommandoen **return**, som forteller hva som skal returneres når funksjonen kalles.

I hovedprogrammet er det bare ei linje hvor vi ønsker å få skrevet ut differensen mellom de to verdiene vi får returnert når funksjonene kalles.
___

```{admonition} Oppgave  1
: class: note

Tidligere i kurset er det gitt en oppgave hvor du skulle regne om fra grader Celcius \(C\) til grader Fahrenheit \( F\) . 

Formelen for omregning er \( F = \dfrac{9}{5}\cdot C+32\)

Nå skal du lage en en funksjon i Python som regner om. Funksjonen kan du kalle C_til_F

Det skal være mulig å skrive inn temperaturen i grader Celsius og så få skrevet ut temperaturen i grader Fahrenheit. 
```
 

Du kan lage programmet her: 