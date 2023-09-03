
# Grundläggande -- CSV parser

Filen thrones.csv innehåller data baserad på romanen Storm of Swords av George R.R. Martin. Datan visar interaktioner mellan romanens många olika karaktärer. Kolumnerna "source" och "target" innehåller namnet på karaktärer som har scener med varandra, där "source" är den som talar eller utför en annan signifikant handling och "target" är den som är lyssnaren eller mottagaren av handlingen. Den tredje kolumnen "weight" räknar hur många gånger en handling mellan de här två karaktärerna har inträffat. Det kan också ses på ett mått på hur starkt förknippade dessa karaktärer är med varandra. Från den första raden kan vi t. ex. se att Aemon har talat till Grenn vid 5 separata tillfällen.

Uppgiften är att skriva ett program som parsar CSV filen och sedan ger användaren följande alternativ:

 1. (L)ist: visa en lista på alla karaktärer i alfabetisk ordning
 2. (R)elationships: visa alla relationer för en viss karaktär
    med det starkaste överst och det svagaste sist.
 3. (Q)uit: avsluta programmet

# Fördjupning -- JSON data

Om ni är klara med det grundläggande programmet och har tid över kan ni försöka er på en svårare fördjupningsuppgift. Filen hard-mode/advanced.json innehåller en JSON data om alla vapen från From Software spelet Dark Souls. Programmet ska kunna visa en lista på alla vapen och ge djupare information om varje vapen om man väljer att inspektera det närmare. Eftersom de är en fördjupningsuppgift väljer du själv hur mycket av datan du vill tolka och visa. Good luck, traveller!