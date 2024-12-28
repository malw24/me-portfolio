---
Title: Kmom05
Description: This is my colors page.
---

Kmom05
=======================



## Urval

Den första hemsidan jag har valt är Aftonbladet, en webbplats för inrikes- och utrikesnyheter.
<picture>
    <source media="(min-width: 668px)" srcset="%base_url%/image/aftonbladet.png?save-as=jpg">
    <source media="(min-width: 376px)" srcset="%base_url%/image/aftonbladet.png?save-as=jpg&w=350&q=80&crop-to-fit">
    <img src="%base_url%/image/aftonbladet.jpg" alt="Aftonbladet">
</picture>

Den andra hemsidan är Pepsi, vald för att undersöka hur en stor företagshemsida presterar.
<picture>
    <source media="(min-width: 668px)" srcset="%base_url%/image/pepsi.png?save-as=jpg">
    <source media="(min-width: 376px)" srcset="%base_url%/image/pepsi.png?save-as=jpg&w=350&q=80&crop-to-fit">
    <img src="%base_url%/image/pepsi.jpg" alt="Pepsi">
</picture>

Den tredje hemsidan jag har valt är Apotekets hemsida, främst för att det är en "shoppinghemsida" med hög trafik.
<picture>
    <source media="(min-width: 668px)" srcset="%base_url%/image/apoteket.png?save-as=jpg">
    <source media="(min-width: 376px)" srcset="%base_url%/image/apoteket.png?save-as=jpg&w=350&q=80&crop-to-fit">
    <img src="%base_url%/image/apoteket.jpg" alt="Apoteket">
</picture>

## Metod
Jag använder Google Chrome för att jämföra laddningstiderna för de olika hemsidorna. Den information jag behöver finns främst under fliken "Network" i Chrome DevTools. PageSpeed Insights, som jag fick reda på via föreläsningen, kommer också att användas.


## Resultat

<iframe class="spreadsheet" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTjSS-ciYFZ1fZBmW_Ga86646fxeSrA1LUcTbGsVgvtAba20NEp3NVm9dWJN3iR3nvTuMAOjVSIa09f/pubhtml?widget=true&amp;headers=false" title="spreadsheet"></iframe>



## Analys

Resultatet visar att apotekets hemsida överlag är den långsammaste. Resultatet för apotekets startsida påvisar att den är betydligt långsammare än både Aftonbladet och Pepsi. Pagespeed Insights bedömer till och med apotekets startsida som ett misslyckande: "Core Web Vitals assessment: Failed", där de främsta problemen verkar vara Largest Contentful Paint (orange), Interaction to Next Paint (orange) och Cumulative Layout Shift (rött). Resurserna för apotekets hemsida är dessutom nästan tre gånger så många som för Aftonbladets sportsida, som hade näst störst mängd resurser att ladda in. Jag skulle bedöma apotekets hemsida, särskilt startsidan men även kategorisidan och varumärkessidan, som inte alls optimerad – varken för mobil eller desktop.

Om man tittar på antalet förfrågningar som görs ser man tydligt att apotekets totala antal är mycket större: 481 förfrågningar i snitt. Aftonbladet ligger på 175 i snitt och Pepsi på 92 förfrågningar. Det är nästan tre gånger fler förfrågningar än vad Aftonbladet gör. Här ligger förmodligen en del av problemet – apotekets hemsida gör väldigt många fler förfrågningar, och den överförda datan (transferred data) är minst två gånger större.

Vinnaren i detta sammanhang är enligt min mening Aftonbladet. De är, trots fler förfrågningar och ungefär samma mängd överförd data från servern som Pepsi, snabbare än både Pepsi och apoteket.

På andraplats kommer Pepsis hemsida, som är hyfsat väloptimerad. Dock innehåller den inte särskilt mycket innehåll, vilket innebär att färre förfrågningar görs.

På tredje plats kommer apotekets hemsida, av de anledningar jag angivit ovan. Man skulle kunna argumentera att apoteket har en stor mängd produkter och annat material som måste hämtas, och att detta är orsaken till att hemsidan är långsammast. Samtidigt har Aftonbladet också en stor mängd artiklar och videor som laddas in – och de gör detta med färre förfrågningar och snabbare än apoteket.

Jag tycker generellt att allt över tre sekunder i laddningstid känns lite väl långsamt. Det påverkar visserligen sällan användaren negativt om laddningstiden ligger runt 4–5 sekunder, men för hemsidor som förser den här typen av innehåll borde det inte behöva ta längre tid än så.
Jag tittade på YouTube och såg att deras laddningstid ibland kan ligga på över 10 sekunder. Det känns dock mer rimligt, eftersom det förmodligen är fler bilder, i form av thumbnails och liknande, som måste laddas in jämfört med den rena text som till exempel Aftonbladet främst visar.
Utifrån vad jag kan se så hanterar Youtube större datamängder vilket kan förklara den längre laddningstiden. Samtidigt är användarna förmodligen mer benägna att acceptera detta eftersom de förstår att det är större innehåll som behöver laddas in.


## Övrigt

Den här rapporten för kursmoment 5 har skrivits endast av mig Max Lindgren.


