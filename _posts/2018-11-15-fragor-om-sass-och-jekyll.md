---
layout: post
title:  "Frågor om SASS och Jekyll"
date:   2018-11-15 11:10:12 +0100
comments: true
# categories: jekyll update
---

I denna post kommer jag svara på några frågor om Sass och Jekyll. En del av Examinations uppgift 1 i kursen Klientbaserad webbprogramering (1DV022)

Nu kommer vi till frågorna.

* What do you think of pre-compiling your CSS?

    Det är underbart. Borde ha lärt mig det tidigare. Har stött på den innan men har inte tagit mig tiden att förstå den. 

    * Compare to regular CSS: 

    Kod mässigt så gör det lättare att förstå och att koda som den stödjer nestad kod. Blir också lättare att hitta för nästa utvecklare som tar över.
    
    * Which techniques did you use?

    Använde mig av den inbyggda jekyll minima theme. Och den använder sig av SCSS eller Sassy CSS.

    * Pros and cons?

     (+) Nested CSS +++ Blir mindre kod

     (+) Man kan ha förinställda variabler. +++ Som att ha egna döpta färger. Eller mått. Som man senare kan använda som dom är eller editera ex: $size: 10px och sen när man ska använda den margin: $size / 2.Då får man ut 5px bara. Mycket andvändbart.

     (+) Som man har kan ha egna förinställda variabler så kan man utföra ändringar snabbare.

     (-) Det stora minuset är att den funkar inte bara som den är. Den måste Kompileras om (översättas, konverteras) till CSS innan den kan användas. Och det kan man göra med en vanlig CSS fil.

     (-) Som det är en konverterad fil uppe i webbläsaren så har du svårare att felsöka i webbläsaren också. 



* What do you think of static site generators?
    Det kan vara en enkel lösning för en utvecklare för att få ut sin sida. 
    
    * What type of projects are they suitable for?

    Sidor som möjligtvis inte har behov av databas. Onepage sidor är det perfekt för, eller sidor med en ensam utveklare som jobbar på den.

    * Mina egna tankar.

    Det är inte en fråga som ställdes i av läraren men något jag ville ta upp. Som jag ser static site generator jämfört med CMS och dynamiska sidor. Dom som publicerar sidan måste lita på varann. Till skillnad från en CMS ex. Joomla där jag kan begränsa en persons access till en viss sida eller skriva till en viss sida. Eller jag kan också bara ge personen access till att skriva och inte radera post eller publicera dom. Utan det måste skötas av en tredje person som huvudadmin har bestämt. Men här i jekyll så finns det ingen ACL och då måste det tyvärr finns en större förtoende mellan personerna som administrerar sidan.

    Men detta kan säkert fixas med en utomstående webguia admin. Där webguian har en ACL funktion, gör så att personerna kan bara skriva till sin del och editera sina poster. För att sen laddas upp i sidan som HTML. Och det gör så att webguian behöver en form av databas, men inte själva sidan som visas för besökarna. 
    
    Eller där man har en publisher som tittar efter alla filer innan dom laddas upp. Men det är nog inte gjort för stora orginisationer med flera författare.

    Men det stora plusset med en statisk sida är att det kräver mycket mindre av webbservern och antingen kan du ta emot fler besökare eller som webbhost så kan du ha fler sidor per server.

    Så detta med Statisk Site Generator är något jag kommer undersöka vidare på.
    Det finns säkert en klok person där ute som har sett samma begränsningar som jag och har kommit på en lösning.

