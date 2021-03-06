# Figurer og variable størrelser


I matematikk er det viktig å kunne utforske og oppdage mønster og sammenhenger. I denne leksjonen skal du først se etter mønster i figurtall. Dette kan hjelpe deg å forstå hvordan bokstavregning kan være nyttig i generaliseringer og problemløsing. Du skal lære at vi kan regne med variabler på samme måte som vi regner med vanlige tall.



### Eksempel 1

Nedenfor ser du de tre første figurene som er laget av fyrstikker. 

%![Bilde av fyrstikker laget som kvadrater](/bilder/fyrstikker.png "Hvor mange fyrstikker % er det i figur 50??") 

![](/bilder/fyrstikker.png)

Hvor mange fyrstikker er det i figur nummer 50? 
 

**Løsning:**

I figur 50 er det 151 fyrstikker. Det er flere måter å finne det på. En er å stille opp antall fyrstikker og figurnummer i en tabell</span><br></p>
<table>
    <thead>
        <tr>
            <th scope="col">Figurnummer&nbsp;&nbsp;&nbsp;&nbsp; <br></th>
            <th scope="col">Antall fyrstikker</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="text-align: center;">1</td>
            <td style="text-align: center;">4</td>
        </tr>
        <tr>
            <td style="text-align: center;">2</td>
            <td style="text-align: center;">7</td>
        </tr>
        <tr>
            <td style="text-align: center;">3</td>
            <td style="text-align: center;">10</td>
        </tr>
        <tr>
            <td style="text-align: center;">4</td>
            <td style="text-align: center;">13</td>
        </tr>
        <tr>
            <td style="text-align: center;">5</td>
            <td style="text-align: center;">16</td>
        </tr>
        <tr>
            <td style="text-align: center;">6</td>
            <td style="text-align: center;">19</td>
        </tr>
        <tr>
            <td style="text-align: center;">7</td>
            <td style="text-align: center;">22</td>
        </tr>
        <tr>
            <td style="text-align: center;">8</td>
            <td style="text-align: center;">25</td>
        </tr>
        <tr>
            <td style="text-align: center;">9</td>
            <td style="text-align: center;">28</td>
        </tr>
        <tr>
            <td style="text-align: center;">10</td>
            <td style="text-align: center;">31</td>
        </tr>
    </tbody>
</table>
<br><br>
<p>Med utgangspunkt i det som står i tabellen kan vi observere noen egenskaper som kan hjelpe oss til å finne svaret.</p>
<p>Når ved en fordobling av figurummeret vil antall fyrstikker være en mindre enn dobbelt så mye. Figur 2 har 7 fyrstikker. Figur 4 har 7·2-1=13 fyrstikker.</p>
<p>Figur 20 får da 2·31-1=61 fyrstikker.</p>
<p>Slik kan vi tenke oss fram til svaret.</p>
<p>En annen måte er å se at antallet øker med 3 per figur slik at tabellen blir slik</p>
<p><br>
</p>
<table>
    <thead>
        <tr>
            <th scope="col">Figurnummer&nbsp;&nbsp;</th>
            <th scope="col">&nbsp; Antall fyrstikker</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="text-align: center;">1</td>
            <td style="text-align: center;">4<br></td>
        </tr>
        <tr>
            <td style="text-align: center;">2</td>
            <td style="text-align: center;">4+3·1</td>
        </tr>
        <tr>
            <td style="text-align: center;">3</td>
            <td style="text-align: center;">4+3·2</td>
        </tr>
        <tr>
            <td style="text-align: center;">4</td>
            <td style="text-align: center;">4+3·3</td>
        </tr>
        <tr>
            <td style="text-align: center;">5</td>
            <td style="text-align: center;">4+3·4</td>
        </tr>
        <tr>
            <td style="text-align: center;">6</td>
            <td style="text-align: center;">4+3·5</td>
        </tr>
        <tr>
            <td style="text-align: center;">7</td>
            <td style="text-align: center;">4+3·6</td>
        </tr>
        <tr>
            <td style="text-align: center;">8</td>
            <td style="text-align: center;">4+3·7</td>
        </tr>
        <tr>
            <td style="text-align: center;">9</td>
            <td style="text-align: center;">4+3·8</td>
        </tr>
        <tr>
            <td style="text-align: center;">10</td>
            <td style="text-align: center;">4+3·9</td>
        </tr>
    </tbody>
</table>
<br><span style="font-size: 0.9375rem; font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Roboto, &quot;Helvetica Neue&quot;, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;;">Da kan vi finne antall fyrstikker i figur nummer 50 som: 4+3·49=151</span><br>
<p>Det fins sikkert flere framgangsmåter som alle er like riktige. Svaret skal uansett bli det samme: 151</p>

```{admonition} Oppgave 1
: class: note

I forrige eksempel fant vi ut hvor mange fyrstikker det var i figur nummer 50. Kan du finne et matematisk uttrykk som viser hvor mange fystikker det er i figurnummer $n$?
```



```{admonition} Klikk på knappen til høyre for å vise løsning!
:class: dropdown

![](/bilder/fyrstikker2.png "Ser du mønsteret") 


Antall fyrstikker i figur nummer $n$ kan vi skrive som:

$$F_n=1+3 \cdot n$$

Bildet ovenfor viser en måte å komme fram til dette uttrykket. Hver figur består av én fyrstikk som er merket med grønt. Den første figuren har én samling med tre fyrstikker i tillegg. Den andre har to samlinger med tre fyrstikker. Den tredje har tre
    slike samlinger, og så videre. Hver av disse samlingene er markert med et oransje rektangel.

<p>Kanskje kom du fram til denne formelen:</p>

$$F_n=4+3 \cdot (n-1)$$

For å komme fram til den gjelder samme tankegang, men da starter vi med fire fyrstikker i den første og legger til samlinger med tre fyrstikker fra og med den andre figuren. Begge formlene er naturligvis riktige og ved litt regning kan vi se at de er like.

```

![](/bilder/trekanttall.PNG)

```{admonition} Oppgave 2
: class: note

Figurene over viser noen trekanttall. De har fått navnet sitt etter mønsteret som dannes når vi tegner figurene. Som du ser blir det trekanter!

Her ser du de fire første trekanttallene. Du ser at det første trekanttallet er 1, det andre 3, det tredje 6 og det fjerde 10. 

Hva blir trekanttall nummer 7?
```





```{admonition} Klikk på knappen til høyre for et hint!
:class: dropdown

Når du skal jobbe med firgurtall er det to framgangsmåter som kan være lure. Den ene er å se etter mønster direkte i tallene. Legg merke til at det tredje trekanttallet kan skrives som 

$$ 1+2+3$$

 og det fjerde kan skrives som 

$$1+2+3+4$$

Hva blir da det syvende trekanttallet? Den andre framgangsmåten er å se etter mønstre i figurene. Kanskje kan du se akkurat det samme i prikkmønsteret?

```
Kan du finne en formel for trekanttall nummer $n$? 

```{admonition} Klikk på knappen til høyre for en løsning!
:class: dropdown

Det som bestemmer et trekanttall, er hvilket nummer det er i rekken. Når du skal lage en variabel for nummer, brukes ofte bokstaven $n$.

Trekanttall nr $n$  kan skrives generelt som 

$$T(n)=\frac{n⋅(n+1)}{2}$$
```

I filmen nedenfor viser vi hvordan vi kan komme fram til formelen i løsningen ovenfor. 

<div style="padding:56.6% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/291449702?h=cb9445762a&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

### Eksempel 2

I filmen nedenfor viser vi hvordan vi kan regne ut 

$$1+2+3+\cdots +100$$

 ved å bruke et smart triks. 

 <div style="padding:56.6% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/291449893?h=4077438629&title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

```{admonition} Oppgave 3
: class: note

 Fra tidligere vet vi at trekanttall nr 
$n$ kan skrives generelt som 

$$T(n)=\frac{n⋅(n+1)}{2}$$

Tallet 1326 er et trekanttall. Hvilket figurnummer gir dette tallet?
```



```{admonition} Klikk på knappen til høyre for et hint!
:class: dropdown

Her må vi prøve oss fram. Se på formelen. Kan du finne et produkt 
$n\cdot(n+1)$ som blir to ganger 1326 ?
```

