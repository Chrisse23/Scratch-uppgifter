**I denna uppgift kommer du få göra en egen hemsida med Mozilla Thimble som är ett verktyg att göra just hemsidor i.  Du kommer sedan kunna publicera denna sida och visa för familj och vänner!**

Ett exempel på en sida kan du hitta [här](https://thimbleprojects.org/christoffer/408964/ "Exempeluppgift").

En hemsida är uppbyggd av tre byggstenar HTML, CSS och Javascript. HTML är sidans struktur och som byggblock använder man HTML-taggar. Exempel på en HTML-tagg kan vara ```<h1>``` för att skapa en rubrik eller ```<img>``` för att lägga in en bild. CSS används för att bestämma hur sidan ska se ut gällande färg och form. Exempelvis om en knapp ska vara grön eller röd, vilken bakgrundsfärg sidan ska ha. Javascript används för interaktion på hemsidan, till exempel vad som ska hända när man trycker på en viss knapp. I denna uppgift kommer vi främst att fokusera på HTML när vi ska bygga vår hemsida.

## 1:  Uppgift

Nu ska du få göra din egen hemsida. 


1. Starta med att klicka på denna [länk](https://thimble.mozilla.org/sv-SE/) 
2. Klicka sedan på Starta ett projekt från grunden.

Såhär ser din startvy ut. Där det står “Redigerare” är där vi kommer att skriva vår kod. Vi kommer enbart att skriva kod innanför ```<body>```-taggarna.

![image alt text](uppgift-start.png)

Dessa två knappar växlar mellan hur hemsidan ser ut på en dator och på en mobil.

![image alt text](mozilla-thimble-desktop-mobile.png)

Det första vi ska ändra är rubriken på vår hemsida. 

1. Innanför ```<h1>```-taggarna ersätt texten med något du själv vill att det ska stå. Ser du hur texten i förhandsgranskningen ändras på en gång?

![image alt text](uppgift-h1-tagg.png)

2.  Ta nu bort texten innanför ```<p>```-taggarna på samma sätt som innan och skriv något du själv vill att det ska stå.

Nu har du gjort de första ändringarna på din egen hemsida. Nu ska vi lägga till en bild med hjälp av en ```<img>```-tagg. Denna tagg används för att visa en bild från en annan hemsida. Du kan exempelvis gå in på Google och googla fram en bild och sedan kopierar du länken till den bilden. Kopiera sedan in länken efter **src=**.  Det går också att ladda upp en bild från sin dator och använda den. 


1. Börja nu med att gå in på Google och sök upp en bild du vill ha, kopiera sedan url:en till bilden. 
2. Gå till ditt projekt i Mozilla Thimble och under din ```<p>```-tagg skriv in nedanstående men ersätt url:en efter **src=** med din url.
3. Efter url:en i img-taggen gör ett mellanslag och skriv **width=”500px”**. Detta är för att göra bilden mindre.

    ```<img src="https://d2btg9txypwkc4.cloudfront.net/media/catalog/category/Artiklar_katt.jpg" />```

Nu borde din sida se ut som på bilden:

![image alt text](uppgift-img-tagg.png)

Nu ska vi lägga till en länk på sidan. Detta gör vi med en HTML-tagg som heter ```<a>```.
Denna tagg används för att länka till en annan hemsida. Länken placeras inom **href=**. Sedan skriver du vad länktexten ska vara och då visas bara den texten och inte själva länken.

    <a href="www.kodboken.se">Tryck här för att komma till kodboken.se</a>


![image alt text](uppgift-a-tagg.png)

Tycker du att det ser lite trångt ut mellan bilden och länken? Det kan vi ordna med en HTML-tagg som heter <br />.  För att ge ett radbryt mellan exempelvis en rubrik och textstycke.

1. Gör en ny rad under din ```<img>```-tagg och skriv in ```<br />```  och tryck sedan enter och skriv in ```<br />``` igen.
2. Nu borde du ha lite mer mellanrum mellan din bild och din länk. Koden borde se ut som på bilden nedan.
![image alt text](uppgift-br-tagg.png)


Nu har du gjort det första på din egen hemsida! Du har i denna uppgift lagt in följande HTML-taggar:

- En ```<h1>``` - tagg
- En ```<p>``` - tagg
- En ```<i>``` - tagg
- En ```<img>``` - tagg
- En ```<a>``` - tagg

Det finns såklart många fler HTML-taggar, du kan nu fortsätta och bygga på din hemsida med mer innehåll, lite längre ner finns det information om lite olika HTML-taggar du kan använda. Dessa kan du ha som ett stöd när du jobbar med din sida.

För att publicera din hemsida så att du kan visa den för familj och vänner, skapa ett konto och sedan tryck på publicera-knappen längst upp till höger.

## 2: Använda HTML-taggar

De finns väldigt många HTML-taggar men i denna uppgift är det tänkt att ni kan använda följande:


- ```<img />``` - För att visa en bild
- ```<h1></h1>``` - Stor rubrik
- ```<h2></h2>``` - Mellan rubrik
- ```<h3></h3>``` - Liten rubrik
- ```<p></p>``` - Vanlig text
- ```<i></i>``` - Kursiv text
- ```<b></b>``` - Fet text
- ```<br />``` - Radbryt
- ```<a></a>``` - Länk till en annan hemsida

En HTML-tagg har oftast en starttagg och en sluttagg ```<h1>``` (starttagg) ```</h2>```(sluttagg.)

### ```<img>```

Denna tagg används för att visa en bild från en annan hemsida. Du kan exempelvis gå in på Google och googla fram en bild och sedan kopierar du länken till den bilden. Kopiera sedan in länken efter src=.

    <img src="https://d2btg9txypwkc4.cloudfront.net/media/catalog/category/Artiklar_katt.jpg" />
### ```<h1>```

Denna tagg används för att visa en stor rubrik, den text man vill visa skrivs mellan starttaggen och sluttagen.

    <h1>En stor rubrik</h1>
### ```<h2>```

Som ```<h1>``` men ger en mellan rubrik.

    <h2>En stor rubrik</h2>

### ```<h3>```

Som ```<h1>``` men ger en liten rubrik.

    <h3>En stor rubrik</h3>
### ```<p>```

Används för vanlig text på en hemsida.

    <p>Hej</p>
### ```<i>```

Denna tagg används för att göra en text kursiv. Sätt taggarna runt den text du önskar bli kursiv. Används vanligtvis inom en annan text exempelvis en ```<p>``` - tagg.

    <p>Hej på <i>dig</i></p>

I ovanstående exempel skulle “dig” bli kursivt.

### ```<b>```

Används på samma sätt som en ```<i>``` - tagg men ger fet text istället.

    <p>Hej på <b>dig</b></p>

I ovanstående exempel skulle “dig” bli i fet text.

### ```<br />```

För att ge ett radbryt mellan exempelvis en rubrik och textstycke.

    <h1>Rubrik</h1>
    <br />
    <p>Här kommer lite text.</p>

### ```<a>```

Används för att länka till en annan hemsida. Länken placeras inom href=. Sedan skriver du vad länktexten ska vara. Då visas bara den texten och inte själva länken.

    <a href="www.kodboken.se">Tryck här för att komma till kodboken.se</a>
