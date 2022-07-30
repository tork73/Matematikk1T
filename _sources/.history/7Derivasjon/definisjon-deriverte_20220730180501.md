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


## Oppsummering

Tidligere har vi sett på stigningstallfunksjonen. Der så du at tangenten til en funksjon har ulike verdier for ulike verdier av $x$ og du fant tangentfunksjonen til $f(x)=x^2$ som $2x$.

I videoen tidligere i denne leksjonen så du at den deriverte av en funksjon er stigningstallet til tangenten til grafen som funksjon av  $x$, dvs tangentfunksjonen til $f$ eller den momentane vekstfarten til $f$. Den deriverte av funksjonen $f(x)$ skrives $f'(x)$.

Det vil si at når $f(x)=x^2$ er $f'(x)=2x$. Fin sammenheng?


Deriver $f(x)=x^2$ ved hjelp av definisjonen

I en video på neste side får du se hvordan du kan bruke definisjonen til å derivere $f(x)=x^2$. Du bør prøve selv før du ser videoen.

Uttrykket $ \lim $ betyr en grense og da blir $\displaystyle{ \lim_{\Delta x \to 0} }$ grensen når $\Delta x$ nærmer seg $0$.

Når du skal derivere $f(x)=x^2$ ved bruk av derivasjonen, skal du undersøke hva uttrykket $ \frac{f(x+\Delta x)-f(x)}{\Delta x}$ går mot når $ \Delta x$ går mot null. Først må du bruke dine kunnskaper og skrive uttrykket enklere for du undersøker grensen. 