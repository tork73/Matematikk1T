# Faktorisering av  rasjonale uttrykk

Etter leksjonen skal du være i stand til å faktorisere og forenkle uttrykk av typen 

$$\dfrac{9x^2-16y^2}{9x^2-24xy+16y^2}$$

## Faktoriser uttrykket

Vi starter med litt repetisjon. Ta fram papir og blyant og løs denne oppgaven før du går videre.

```{admonition} Oppgave 1
: class: note

Faktoriser uttrykkene 

$x^2-x-6$

$x^2-4$



```

```{admonition} Løsning
: class: dropdown
<b></b>
$x^2-x-6 = (x-1)(x+2)$

$x^2-4 = (x-2)(x+2)$


```

Bruk det du har lært til å løse følgende oppgave: 

```{admonition} Oppgave 2
: class: note

Skriv uttrykket så enkelt som mulig

$$\dfrac{x^2-x-6}{x^2-4}$$

Gjør oppgaven og noter svaret før du leser løsningsforslaget. 
```

```{admonition} Oppgave 3
: class: dropdown

I denne oppgaven fikk du bruk for faktoriseringene du gjorde tidligere. Da fant du at 

$$x^2-x-6=(x+2)(x-3)$$

og

$$x^2-4=(x+2)(x-2)$$

Da kan du skrive om det rasjonale uttrykket slik:

$$ \dfrac{x^2-x-6}{x^2-4}=\dfrac{(x+2)(x-3)}{(x+2)(x-2)}$$

Her har du en brøk med samme faktor i både teller og nevner. Da kan du forkorte og få at

$$ \dfrac{x^2-x-6}{x^2-4}=\dfrac{(x+2)(x-3)}{(x+2)(x-2)}=\dfrac{(x-3)}{(x-2)}$$

Du har løst oppgaven og forenklet det opprinnelige uttrykket.

```

## Faktorisering med GeoGebra 

Digitale verktøy kan også benyttes til faktorisering. Nå kan du få se hvordan vi gjør det med Geogebra.

<div style="padding:56.34% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/285494236?h=1b8370a7f9&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

```{admonition} Oppgave 4
: class: note

Bruk GeoGebra til å faktorisere uttrykkene: 

$ x^2+7x-44$

$x^3-4x^2-3x+18$

<iframe src="https://www.geogebra.org/classic/g6ecrxv8?embed" width="100%" height="300" allowfullscreen style="border: 2px solid #e4e4e4;border-radius: 8px;" frameborder="0"></iframe>

```

Når du kan faktorisere større algebrauttrykk, så kan du bruke dette til å forkorte brøkuttrykk med større algebrauttrykk.

```{admonition} Oppgave 5 
: class: note

Prøv å faktorisere teller og nevner i brøken under, og deretter forenkle den.

$$\dfrac{9x^2-16y^2}{9x^2-24xy+16y^2}$$

```

```{admonition} Løsning
: class: dropdown

<b></b>

$$\dfrac{9x^2 - 16y^2}{9x^2 - 24xy + 16y^2} =\dfrac{(3x)^2-(4y)^2}{(3x)^2 - 2\cdot 3x \cdot 4y + (4y)^2} = \dfrac{(3x - 4y)(3x + 4y)}{(3x - 4y)^2}=\underline{\underline{\dfrac{3x+4y}{3x-4y}}}$$

```

## Trekke sammen of forkorte


Enkelte ganger må man summere to eller flere brøker før man kan begynne å faktorisere og forkorte. La oss se på en oppgave som ble gitt på eksamen høsten 2017 som eksempel.

Skriv så enkelt som mulig

$$ \frac{x}{x-2}+\frac{2x}{x-3}-\frac{2x}{x^2-5x+6}$$

Her der det lurt å begynne med å faktorisere nevneren i den tredje brøken: 

$$ x^2-5x+6 = (x-2)(x-3)$$

Vi ser da at fellesnevneren er $(x-2)(x-3)$ og vi kan a utvide den første og den andre brøken. Utregningene blir slik: 

$$
\begin{align*}
     \frac{x}{x-2}+\frac{2x}{x-3}-&\frac{2x}{(x-2)(x-3)}  \\
     = \frac{x\cdot (x-3)}{(x-2)(x-3)}+\frac{2x\cdot (x-2)}{(x-2)(x-3)}-\frac{2x}{(x-2)(x-3)}\\
     &= \frac{x^2-3x+2x^2-4x-2x}{(x-2)(x-3)} \\
     & = \frac{3x^2-9x}{(x-2)(x-3)}\\
\end{align*}