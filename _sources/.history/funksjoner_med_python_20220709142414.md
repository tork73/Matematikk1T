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

<iframe src="https://trinket.io/embed/python3/adeb53d690" width="100%" height="500" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen=""></iframe>

## Moduler i Python

Nå har vi allerede sett at Python inneholder en rekke kommandoer. Et eksempel som vi har brukt er print().

Ofte vil vi få bruk for kommandoer og funksjoner ut over de innebygde. Mange har allerede laget slike og de kan vi importere til programmet vårt.

Det vi importerer kaller vi moduler, pakker eller bibliotek. Forskjellen på dem er ikke så viktig, men kort sagt er en modul ei fil som inneholder pythonfunksjoner, variabler med mere. En pakke inneholder flere moduler og et bibliotek inneholder flere pakker.

Videoen under viser litt mer om hvordan vi kan importere når vi får bruk for noe som ikke allerede er innebygd i Python.

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/460441383?h=d14948ce33&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

## Plotting med Python

I Python kan vi plotte funksjoner og koordinater. Videoen under viser hvordan vi kan få tegnet et koordinatsystem med noen enkle verdier for x og y. Den viser også hvordan vi kan sette navn på aksene.

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/460841014?h=212342f838&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

## Punktplot med Python

Noen ganger vil vi plotte punkter i et koordinatsystem. På engelsk kalles det scatter plot. I Python må vi bruke kommandoen scatter for å få det til. Videoen viser deg hvordan. Under videoen kan du finne koden som ble benyttet.

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/460848904?h=85e240afd7&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

Her er koden som ble brukt


```python
import matplotlib.pyplot as plt
# legger inn x-verdier og y-verdier
x = [1,2,3,4,5]
y1 = [1,4,9,16,25]
y2 = [2,4,6,8,10]

# plotter verdiene
plt.scatter(x,y1, label = "graf 1")
plt.scatter(x,y2, label = "graf 1")

# tekst
plt.xlabel("x-verdier")
plt.ylabel("y-verdier")
plt.title("Et enkelt eksempel")
plt.legend()
plt.grid()
# viser plottet
plt.show()
```

```{admonition} Oppgave 2
: class: note

Lag et punktplott av denne tabellen:

| $x$    | $-1$ | $0$ | $1$ | $2$  | $3$ | $4$ | $5$ |
|:------:|:----:|:---:|:---:|---|---|---|---|
| $f(x)$ | $8$  | $3$ | $0$ | $-1$ | $0$ | $3$ | $8$ |



```

<iframe src="https://trinket.io/embed/python3/9d1b0382af" width="100%" height="500" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen=""></iframe>