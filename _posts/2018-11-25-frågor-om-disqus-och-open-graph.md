---
layout: post
title:  "Frågor om Disqus och Open Graph"
date:   2018-11-25 11:10:12 +0100
comments: true
# categories: jekyll update
---

Nu är det dom två sista frågorna för ex1 i kursen 1DV022.


* How did you implements comments to blog posts

    Jekyll hade en någorlunda fungerande tillägg för kommentarer. Den använde sig av tjänsten Disqus och då slapp man hantera den i själva servern där sidan är upplagt.

    Man var tvungen att skapa ett konto och sida i Disqus och sen editera lite koden i själva jekyll. Man är tvungen att ha lite tålamod för det tar ett tag innan den syns i sidan. Så efter man har satt upp den i sidan så ska man kanske vänta 30 minuter innan kommentarsfältet syns i sidan. Jag ville bara ha kommentars funktionen i blogg delen av sidan. Och detta kan lätt ändras med att ändra comments: true till false i Front Matter delen av md filen. Och då syns det inte kommentarerna i den specefika posten. Front Matter är det lilla text snutten som innehåller viktigt information i md filen. Som vilken layout, tid för publicering, titel, mm. Den hittas högst upp i md filen mellan två rader med tre bindesstreck (---).

* What is Open Graph and how do you make use of it?

    Open Graph skapades av Facebook för att lättare integrera externa object med Facebook. Nu används den Open Graph protokollet av fler sidor än Facebook. Den funkar så här, när du sätter upp en länk till en nyhetsartikel i din Facebook, eller andra sociala platform, så kommer artikeln visas som den var en del av själva sociala platformen. Du kommer kunna gilla, kommentera och dela den vidare. 

    Om du vill veta mer kan du läsa här: [OGP.ME](http://ogp.me){:target="_blank"} eller en video från Facebook: [YouTube](https://www.youtube.com/watch?v=4Q207Z-HkUo){:target="_blank"}

    Det fanns en väldigt bekväm plugin i Jekyll. Det var bara att lägga till den i _config.yml och sen sa instruktionerna att man skulle lägga upp en seo tagg i headern. Men den fanns där redan. Så det var inte svårt att komma igång.