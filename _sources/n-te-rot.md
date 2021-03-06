# Rasjonale eksponenter

Her skal du lære om

* n-te røtter
* potenser med rasjonale eksponenter

Dette vil vise seg å være to sider av samme sak. 

Du skal også lære hvordan man kan forenkle uttrykk med kvadratrøtter.

```{admonition} Oppgave 1
: class: important

Et kvadrat har areal lik 36. Hvor lange er da sidene i kvadratet? 
```

## N-te-roten av et tall

Dersom du skal regne ut arealet av et kvadrat med side 3 kan du regne ut $3\cdot 3=3^2$ og får $9$ som svar. Men hva skal du gjøre om du vet hva arealet er, men ikke hvor lange sidene er? La oss si at arealet er 16 m². For å finne sidene må du altså finne et tall $a$ slik at $a^2=16$. I dette tilfellet ser du at $a=4$ passer bra. Vi kaller tallet $a$ som er slik at $a^2=b$ for kvadratroten av $b$: 

$$a=\sqrt{b} \ \  \text{ dersom  }  \ \  a^2=b$$

Å ta kvadratroten av et tall svarer til å opphøye tallet i $\frac 1 2$. Dette kommer at vi ønsker at potensregelen 

$$\left(a^n\right)^m=a^{n\cdot m}$$

skal gjelde også når vi har eksponenter som ikke nødvendigvis er heltall.  Vi får nemlig at 

$$\left(a^2\right)^\frac{1}{2} = a^{2\cdot \frac{1}{2}} = a^1=a$$

```{admonition} Definisjon
: class: Note

Generelt definerer vi n-te-roten av et positivt tall $a$ til å være det positive tallet $b$ som er slik at $b^n=a$. Det vil si at 

$$b=a^\frac{1}{n}  \  \text{dersom} \ b^n=a$$


```

I videoen nedenfor vil du lære mer om dette.  

<div style="padding:56.6% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/291454520?h=15b5e6bad2&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

## Rotregning

Ofte så ønsker vi å skrive matematiske uttrykk så enkelt som mulig. Nå skal vi se på hvordan vi kan forenkle rotuttrykk som for eksempel: $\sqrt{32}-\sqrt{50}+\sqrt{8}$.

Vi kan bruke at $\sqrt{a\cdot b}=\sqrt{a}\cdot \sqrt{b}$ (hvorfor gjelder denne regelen egentlig?) 

La oss prøve å løse oppgaven over:

$$
\begin{align*}
\sqrt{32}-\sqrt{50}+\sqrt{8} & = \sqrt{16\cdot 2}-\sqrt{25\cdot 2}+\sqrt{4\cdot 2}\\
& = \sqrt{16}\cdot \sqrt{2}-  \sqrt{25} \cdot \sqrt{2}+\sqrt{4}\cdot \sqrt{2} \\
&= 4\cdot  \sqrt{2}-5\cdot \sqrt{2}+2\cdot \sqrt{2} \\
& = \sqrt 2
\end{align*}
$$

Legg merke til at det første vi gjorde var å faktorisere tallene inne i rottegnene. Dersom den ene faktoren blir et kvadrattall, så har vi mulighet til å forenkle uttrykket.

Nå kan du prøve deg på denne oppgaven:

```{admonition} Oppgave 1
: class: important

Forenkle $\sqrt{27}-\sqrt{12}$. 
```

```{admonition} To potensregler
: class: Note

Vi har potensreglene

$$(a \cdot b )^n =a^n\cdot b^n $$

$$\left(\dfrac{a}{b}\right)^n = \dfrac{a^n}{b^n}$$

Spesielt har vi at 

$$\sqrt{a\cdot b} = \sqrt{a} \cdot \sqrt{b}$$

$$ \sqrt{\frac a b} = \frac{\sqrt a}{\sqrt b}$$
```


## Oppsummering potensreglene
Her er regnereglene for potenser

> $ a^n \cdot a^m = a^{n+m}$
>
> $\dfrac{a^n}{a^m}= a^{n-m}$
> 
>$ (a^n)^m = a^{n \cdot m} $
>
> $(a \cdot b )^n = a^n\cdot b^n $
> 
> $\left(\dfrac{a}{b}\right)^n = \dfrac{a^n}{b^n}$

To definisjoner fra tidligere

> $ a^0=1 $
> $ a^{-n}=\dfrac{1}{a^n}$

En ny definisjon

> $ \sqrt[n]{a}=a^{\frac{1}{n}} $

Det betyr at
> $$a^{\frac{m}{n}}=\sqrt[n]{a^m}=\left( \sqrt[n]{a} \right)^m$$

