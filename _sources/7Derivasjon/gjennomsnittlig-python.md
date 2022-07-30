# Gjennomsnittlig vekstfart med Python

Her skal du lære hvordan vi kan bruke Python til å 

* regne ut gjennomsnitlig vekstfart i et intervall
* regne ut gjennomsnitlig vekstfart i mange intervall
* illustrere grafisk gjennomsnitlig vekstfart når vi deler opp et intervall i mange små delintervall. 

![](/bilder/python1-stigning.jpg)

## Vi regner ut den gjennomsnittlige vekstfarten

I filmen nedenfor viser vi hvordan vi kan bruke regne ut gjennomsnittlig vekstfart i et intervall ved å lage et lite program i Python. 

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/509221433?h=02a290efd1&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

```{admonition} Oppgave 1
: class: note

Funksjonen $ g$ er gitt ved 

$$g(x)=4\cdot 1,21^x$$

Hva er den gjennomsnittlige vekstfarten til $ g$ i intervallet $[-1, 3]$? 

Bruk Python til å regne det ut: 

<iframe src="https://trinket.io/embed/python3/878d7681c1" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen=""></iframe>

```

```{admonition} Eksempel på løsning
: class: dropdown

Vi kan løse oppgave 1 ved å bruke følgende kode:

```python
def g(x):
  return 4*1.21**x
  
m = (g(3)-g(-1))/(3-(-1))

print(m)
```

## Momentan vekstfart

Vi har så langt brukt Python til å regnet ut gjennomsnittlig vekstfart i et intervall. Vi har tidligere sett at den momentane vekstfarten i et punkt er stigningstallet til tangenten i punktet. Dette tallet kan vi nå beregne med Python ved å regne ut gjennomsnitlig vektfart i et veldig lite intervall. Vi lar med andre ord $ \Delta x = h$ være veldig liten. 

Skal vi for eksempel finne stigningstallet til tangenten i $ x = 2$ til funksjonen $f(x)=x^2+x$, så regner vi ut $ \dfrac{f(2+h)-f(2)}{h}$ når $ h$ er vedlig nær 0. Vi kan for eksempel bruke $ h = 0.0000001 $. I dette tilfellet blir det 

$$ \dfrac{f(2.0000001)-f(2)}{0.0000001} = 5.000000094 $$

Vi kan si at den momentane vekstfarten er 5 i $ x= 2$. 

![](/bilder/momentan1.png)

Merk: Det kunne være fristede å bruke $h = 0.0000000000000000000001$ for å få et mer nøyaktig svar. Men bruker vi så mange desimaler, så vil måten Python lagrer tall på i minnet spille oss et lite puss. 

```{admonition} Oppgave 2
: class: note

Ole har deltatt på et skirenn. Funksjonen $ P$ gitt ved 

$$ P(x)=0.001x^3-0.09x^2+2.4x+74 ,  \ \ x\in\left[0, 50\right] $$

viser pulsen hans som prosent av makspuls $ x $ minutt etter starten av skirennet. 

Bestem den momentane vekstfarten til funksjonen $ P$  når $x=5$. 

Gi en praktisk tolkning av dette svaret. 

<iframe src="https://trinket.io/embed/python3/6009d88912" width="100%" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen=""></iframe>
```

Her kan du se et eksempel på hvordan oppgaven med pulsen til Ole kan løses. 

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/512885669?h=63dce5d64c&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

## Plotte stigningstallfunksjonen 

I filmen nedenfor viser vi hvordan vi kan bruke Python til å tegne grafen til funksjonen som beskriver stigningstallet til en funksjon. 

<div style="padding:56.31% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/509249039?h=0850bdc075&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

<br>

I filmen ovenfor brukte vi følgende kode for å tegne grafen til stigningstallfunksjonen. Vi brukte da følgende kode: 

```python
import matplotlib.pyplot as plt 
import numpy as np

h = 0.01

def f(x):
  return x**3-3*x+4
  
def G(x):
  return (f(x+h)-f(x))/h
  
X = np.linspace(-1, 4, 500)
plt.plot(X, f(X), label="f")
plt.plot(X, G(X), label="G")
plt.legend()
plt.grid()
plt.show()
```

Nå vil vi at du skal prøve selv.  

```{admonition} Oppgave 3
: class: note

Tegn stigningstallfunksjonen til $f$ når $f(x)=x^4-x^2$. Bruk x-verdier mellom -1 og 1. Ser du hvor grafen til $ f$ er brattest? 

<iframe src="https://trinket.io/embed/python3/a63fc1837d" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen=""></iframe>
```


## Oppsummering

Vi kan bruke Python til å regne ut gjennomsnittlig vekstfart i intervaller. Om bredden $h$ på intervallet er nær 0, så vil vi få at gjennomsnittlig vekstfart i intervallet $[x, x+h] $ er tilnæret lik stigningstallet til tangenten i $ (x, f(x))$. 

Dersom vi lar $ h $ være  nær 0, får vi en god tilnærmet verdi for den momentane vekstfarten til $f$. Denne tilnærmingen blir bedre jo nærmere $h$ er 0. 

Vi kan plotte grafen til stigningstallfunksjonen. Vi kaller denne funksjonen for den deriverte funksjonen til $f$. Denne funksjonen er nyttig til å utforske når grafen til $f$ stiger og når den synker. Vi kan også bruke den til å finn topp- og bunnpunkt. Dette kommer vi tilbake til senere. 