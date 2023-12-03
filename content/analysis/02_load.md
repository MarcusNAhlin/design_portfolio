---
Title: Loadtimes
Description: This is my loadtimes page.
---

Webbsidors Laddningstider: En Analys Om Webbisidors Inladdningstider 
=======================

Uppgiften syfte är att undersöka webbsidors laddningstider.

Urval
-----------------------

Urvalet föll på de tre mest besökta tidningarna enligt Orvesto[1]. Dessa är <a href="https://www.aftonbladet.se" target="_blank">Aftonbladet</a>, <a href="https://www.expressen.se" target="_blank">Expressen</a> och <a href="https://www.dn.se" target="_blank">Dagens Nyheter</a> (DN).

Metod
-----------------------

Googles PageSpeed[2] tjänst användes för att avgöra webbplatsens prestanda genom dess egna verktyg och tester. 

Webbläsarens "devtools" flik användes för att mäta av sidornas laddningstider och resurser.

Testerna gjordes på tre olika undersidor på alla de tre utvalda webbplatserna (nio tester total). Resultaten från testerna visas i tabellerna nedan.


Resultat
-----------------------

Länk till alla resultat: <a href="https://docs.google.com/spreadsheets/d/1hmZBRc3F8Cf-VjZi0SJDc93-w_48gSnU1ERRVxA6fYw" target="_blank">Google Kalkyl</a>

<div class="embed-container analysis-chart" style="padding-bottom: 30%;">
    <iframe class="analysis-chart" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTttdn0qDFjBcjQwvs6zkmeOr260WVqJrqqGhhKkfDO38uqDMkWubL0vCcSAVjKUCoSmP2BGZfEqapm/pubchart?oid=915261659&amp;format=interactive">
    </iframe>
</div>

### Aftonbladet 

<a href=" %base_url%/image/aftonbladet.png" target="_blank">
<picture>
    <source media="(min-width: 668px)" srcset="%base_url%/image/aftonbladet.png?w=1000&save-as=jpg">
    <img src="%base_url%/image/aftonbladet.png?w=766&save-as=jpg" alt="Aftonbladet">
</picture>
</a>

<div class="embed-container analysis-data" style="padding-bottom: 15%;">
    <iframe class="analysis-data"   src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTttdn0qDFjBcjQwvs6zkmeOr260WVqJrqqGhhKkfDO38uqDMkWubL0vCcSAVjKUCoSmP2BGZfEqapm/pubchart?oid=21972345&amp;format=interactive">
    </iframe>
</div>

### Expressen

<a href=" %base_url%/image/expressen.png" target="_blank">
<picture>
    <source media="(min-width: 668px)" srcset="%base_url%/image/expressen.png?w=1000&save-as=jpg">
    <img src="%base_url%/image/expressen.png?w=766&save-as=jpg" alt="Expressen">
</picture>
</a>

<div class="embed-container analysis-data" style="padding-bottom: 15%;">
    <iframe class="analysis-data"   src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTttdn0qDFjBcjQwvs6zkmeOr260WVqJrqqGhhKkfDO38uqDMkWubL0vCcSAVjKUCoSmP2BGZfEqapm/pubchart?oid=724277960&amp;format=interactive">
    </iframe>
</div>

### Dagens Nyheter (DN)

<a href=" %base_url%/image/dn.png" target="_blank">
<picture>
    <source media="(min-width: 668px)" srcset="%base_url%/image/dn.png?w=1000&save-as=jpg">
    <img src="%base_url%/image/dn.png?w=766&save-as=jpg" alt="Dagens Nyheter">
</picture>
</a>

<div class="embed-container analysis-data" style="padding-bottom: 15%;">
    <iframe class="analysis-data" scrolling="auto" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTttdn0qDFjBcjQwvs6zkmeOr260WVqJrqqGhhKkfDO38uqDMkWubL0vCcSAVjKUCoSmP2BGZfEqapm/pubchart?oid=866226205&amp;format=interactive">
    </iframe>
</div>


Analys
-----------------------

Aftonbladets webbplats, som fick sämst resultat i undersökningen, verkar använda sig av framför allt png bilder istället för exempelvis jpg eller WebP. Detta kan vara en bidragande faktor till att sidan laddar långsammare än de andra två. Även fast bilderna inte är särskilt stora så tar det längre tid att ladda in png bilder än det hade gjort med ett mer optimerat format.
JavaScript filerna är väldigt stora vilket kan vara en av de mest bidragande faktorerna till de långa laddningstiderna. Enligt Googles PageSpeed[2] tjänst är dessutom en del av denna kod oanvänd på själva sidan och enligt deras verktyg kan laddningstiden gå ner med hela 0,41 sekunder om detta tas bort.

Expressens webbplats, fick något bättre resutlat än Aftonbladet vilket kan bero på att Expressen i stor utsträckning gör om sina bilder till WebP formatet. Däremot är bilderna i relativt hög upplösning vilket jag tror skulle kunna reduceras lite mer för att minska laddningstiderna ytterligare. Google PageSpeed[2] klagar återigen på oanvänd JavaScript kod som enligt dem kan reducera laddningstiden med 0,6 sekunder om den tas bort, vilket jag kanske skulle ta med en nypa salt. 

Dagens Nyheter (DN) fick bra resultat i undersökningen, en kombination av rätt bildformat och väldigt små JavaScript filer gör att sidan laddar in på strax över en halv sekund. Googles PageSpeed[2] verktyg klagar på den oanvända JavaScript-koden slöar ned laddningstiden med över 1 hel sekund på mobila enheter samt 0,2 sekunder på stationära datorer. 

### Rangordning

1. Dagens Nyheter (DN)
2. Expressen
3. Aftonbladet


Min rangordning av de tre webbplatserna följer laddningstiderna vilket i sin tur beror på hur bra webbplatserna är optimerade vilket är anledningen till min rangordning.


Om jag skulle bestämma en gräns för var en snabb webbplats börjar så skulle jag säga att en webbplats som laddar in på under 1 sekund kan räknas som snabb.


Referenser
-----------------------

[1] Ocast. (u.d). Ocast [Online]. Tillgänglig: https://ocast.com/se/toplists/orvesto-konsument-api . Hämtad: 1 December 2023

[2] Google PageSpeed. (u.d). Google [Online]. Tillgänglig: https://pagespeed.web.dev . Hämtad: 1 December 2023

Övrigt
-----------------------

Skriven av Marcus Nilsson Ahlin