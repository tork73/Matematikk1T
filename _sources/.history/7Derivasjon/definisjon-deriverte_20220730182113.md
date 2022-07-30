# Algebraisk finisjon av den deriverte


Her skal du lære deg definisjonen av den deriverte og bruke den til å utlede derivasjonsregler.

![](/bilder/defderiverte.jpg)

I tidligere leksjoner har du jobbet med både momentan og gjennomsnittlig vekstfart. Nå skal du se hvordan man binder disse sammen og blir til et av de kraftigste verktøyene som er i matematikken. I videoen under skal du få se definisjonen av den deriverte.

<iframe src="https://players.brightcove.net/4806596774001/BkLm8fT_default/index.html?videoId=6091703611001" height="360" width="640" allowfullscreen="" frameborder="0"></iframe>

I forrige video så du at definisjonen av den deriverte er på formen:

>
>$$f'(x)= \lim_{\Delta x \to 0} \frac{f(x+\Delta x)-f(x)}{\Delta x}$$
>

For mange er det uvant å sette inn annet enn tall i en funksjon.

Hvis $f(x)=x^2-3x$ så husker du sikkert hvordan du regner ut funksjonsverdier som:

$f(1)=1^2-3\cdot 1=-2$

 $f(3)=3^2-3\cdot 3=0$

Men hva om man skal sette inn $(x+\Delta x)$ eller andre uttrykk? Her kommer noen eksempler:

Hvis $f(x)=x^2-3x$ så er

$f(a)=a^2-3a$

$f(x+1)=(x+1)^2-3\cdot(x+1)=x^2+2x+1-3x-3=x^2-x-2$

Legg merke til at vi satte inn $(x+1)$ alle steder hvor det sto $x$ i funksjonsuttrykket.

$f(a+b)=(a+b)^2-3(a+b)=a^2+2ab+b^2-3a-3b$

$f(x+\Delta x)=(x+\Delta x)^2-3(x+\Delta x)=x^2+2x\Delta x+\Delta x^2-3x-3\Delta x$

Nå kan du prøve deg på noen tilsvarende oppgaver.

```{admonition} Oppgave 1
: class: note

Vi har gitt funksjonen $g(x)=2x^2-4x+1$


Regn ut


a) $g(x+1)$

b) $g(x+\Delta x)$
```

```{admonition} Løsning
: class: dropdown

a) 

$$
\begin{align*}
g(x+1) &= 2(x+1)^2-4(x+1)+1 \\ &=2(x^2+2x+1)-4x-4+1 \\ 
    &= 2x^2+4x+2-4x-3 \\
    &=2x^2-1
\end{align*}
$$

b) 

$$
\begin{align*}
g(x+\Delta x) &=2(x+\Delta x)^2-4(x+\Delta x)+1\\
&=2(x^2+2x\Delta x+(\Delta x)^2)-4x-4\Delta x+1\\
&=2x^2+4x\Delta x+2(\Delta x)^2-4x-4\Delta x+1
\end{align*}
$$

```


## Grenser

Uttrykket $ \lim $ betyr en grense og da blir $\displaystyle{ \lim_{\Delta x \to 0} }$ grensen når $\Delta x$ nærmer seg $0$.

Når du skal derivere $f(x)=x^2$ ved bruk av derivasjonen, skal du undersøke hva uttrykket $ \frac{f(x+\Delta x)-f(x)}{\Delta x}$ går mot når $ \Delta x$ går mot null. Først må du bruke dine kunnskaper og skrive uttrykket enklere for du undersøker grensen. 

```{admonition} Den deriverte
: class: important

Den deriverte $f'$ til en funksjon er definert ved 

$$ f'(x)=\lim_{\Delta x \to 0} \frac{f(x+\Delta x)-f(x)}{\Delta x}$$

```

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/299173872?h=660cc20fe2&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


Nå er det din tur til å bruke definisjonen til å finne den deriverte til en funksjon.

```{admonition} Oppgave 2
: class: note

Bruk definisjonen til å bestemme den deriverte av $f(x)=3x-2$.
```

```{admonition} Tips 1 
: class: dropdown

Finn først et uttrykk for $f(x+\Delta x) = 3(x+\Delta x) - 2$

```

```{admonition} Tips 2
: class: dropdown

Vis at $f(x+\Delta x)-f(x)= 3\Delta x$

```

```{admonition} Tips 3
: class: dropdown

Vis at $\dfrac{f(x+\Delta x)-f(x)}{\Delta x}= \dfrac{3 \Delta x}{\Delta x}= 3$

```

```{admonition} Løsning:
: class: dropdown

I tips 3  fant du at $\dfrac{f(x+\Delta x)-f(x)}{\Delta x}= 3$. Siden brøen blir tallet 3 og ikke har noen $\Delta x$ i uttrykket, blir den deriverte

$$\displaystyle{f'(x) = \lim_{\Delta x \to 0} \frac{f(x+\Delta x)-f(x)}{\Delta x}} = \lim_{\Delta x \to 0} 3 = 3$$

```

```{admonition} Oppgave 3
: class: note

Vi har funksjonen $g(x)=x^2-2x+3$.

a) Bruk definisjonen av den deriverte til å finne den deriverte funksjonen $g'(x)$.

b) Finn $g'(2)$.

c) Hva er den momentane vekstfarten for $g(x)$ når $x=0$?
```

```{admonition} Løsning
: class: dropdown

a) Vi bruker definisjonen til den deriverte og deriverer funksjonen: $g(x) = x^2 - 2x +3$

$$
\begin{align*}
g'(x) & = \lim_{\Delta x \to 0}\frac{g(x+\Delta x)-g(x)}{\Delta x} \\
& = \lim_{\Delta x \to 0}\frac{(x+\Delta x)^2-2(x+\Delta x)+3-(x^2-2x+3)}{\Delta x} \\
&= \lim_{\Delta x \to 0}\frac{x^2+2x\Delta x+(\Delta x)^2-2x-2\Delta x +3-x^2+2x-3}{\Delta x} \\
&= \lim_{\Delta x \to 0}\frac{2x\Dl}{}
\end{align*}
$$

Vi har nå funnet den deriverte funksjonen: `g´(x)=2x-2`

b) `g´(2) = 2*2-2=2`

c) Momentan vekstfart er det samme som den deriverte i et punkt: `g´(0)=-2` 

Den momentane vekstfarten til `g(x)` når `x=0` er altså `-2`.
```