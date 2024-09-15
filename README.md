# Indledende-LCAbyg-KS V1

Excel arket kan bruges til, at finde indledende fejl i sin LCAbyg beregning. Arket er bygget op til at behandle resultat fra LCAbyg version 5.4.0.3, og sammenligne sit resultat med Ingeniørfimaet SWECO’s offentlig tilgængelige LCA database. På denne måde, er der chance for at kunne fange f.eks. indtastningsfejl, hvis udledningen for en bygningsdel stikker meget ud, i forhold til SWECO’s referencer. 

Det er dog vigtigt at have for øje, at resultaterne fra Swecos LCA-database er baseret på beregninger der følger forskellige beregningsmetoder, LCAbyg versioner mm. Dermed kan der også indgå fejlkilder i de bagvedliggende beregninger for resultaterne. Derfor anbefales det kun at bruge databasens resultater som en reference, til at fange de indledende fejl ved f.eks. manuel indtastning af mængder osv. Brug arket, såvel som databasen, med omtanke. 

Referenceværdierne for SWECO's database er nedskrevet d. 16-06-2024 og kan ændre sig ved yderligere opdateringer af databasen. 

SWECO’s LCA database kan finde her: https://www.sweco.dk/baeredygtighed/lca-database/ 

Arket kan ikke nødvendigvis behandle tidligere eller ældre versioner, da teamet bag LCAbyg indimellem ændre opbygning af excel resultat eksportet. Hvis det skulle ske at LCAbyg ændrer sit resultat eksport skal mappens celle ’links’ opdateres. Dette burde ikke have betydning for makroen der indhenter data. Dog er der risiko for, at arkets navn i resultat eksportet ændres. Hvis dette er tilfældet, skal arkets navn ændres i makroen. Dette er dog kun gældende, HVIS LCAbyg teamet ændret resultat eksportet. 

#### Guide til import af LCAbyg resultat ark: 

![Resultat ark](https://github.com/LHFriis/Indledende-LCAbyg-KS/assets/166735139/f837b471-da9b-4ccd-aab4-33fb494616e1)



# Indledende-LCAbyg-KS V2
#### Ny funktionalitet til analyse af bygningsdele og konstruktioners udledning

Med version 2 af Excel-arket Indledende-LCAbyg-KS er der nu tilføjet en udvidet funktionalitet, som gør det muligt at analysere udledningen fra specifikke bygningsdele og konstruktioner. Denne nye funktion bygger videre på de eksisterende muligheder for at identificere indledende fejl i LCAbyg-beregninger. Arket er stadig optimeret til at behandle resultater fra LCAbyg version 5.4.0.3 og sammenligne dem med Ingeniørfirmaet SWECO’s LCA-database.

![Resultat ark](https://github.com/user-attachments/assets/82416c66-d0c2-44e2-beda-8ce23a771197)

#### Vigtig information om SWECO’s LCA-database:

Referenceværdierne fra databasen er fra d. 16-06-2024, men kan ændre sig ved fremtidige opdateringer. Det anbefales derfor, at brugeren kontrollerer for opdateringer af SWECO’s database for at sikre, at sammenligningen forbliver relevant. Du kan finde databasen her: SWECO LCA-database
Teknisk information:
Excel-arket er fortsat designet til at behandle LCAbyg's eksportresultater i version 5.4.0.3, men kan potentielt kræve opdateringer, hvis LCAbyg-teamet ændrer formatet af deres resultateksporter. Hvis der sker ændringer, kan det være nødvendigt at opdatere links og arkets navn i makroen, men dette vil ikke påvirke den overordnede funktionalitet.

Brug værktøjet som en hjælp til at kvalitetssikre dine LCAbyg-beregninger, og husk, at både arket og databasen skal anvendes med omhu.

![Resultat ark2](https://github.com/user-attachments/assets/253d02b0-547f-4b34-8fc5-8efa35086815)
