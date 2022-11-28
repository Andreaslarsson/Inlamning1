# Inlamning1

 Vad är skillnaden mellan monolitisk och mikrotjänst-arkitektur innebär. Redogör kort
  för hur varje del fungerar
  
  ![image](https://user-images.githubusercontent.com/89379222/204225077-934247d0-8563-4be4-8022-bdd289dfcc42.png)
  
  Detta är en bild som förklarar vad microtjänser innebär. Det är när man bryter ut backenden till små delar. Så tex Users, om man skulle gå in och ändra hur den funkar och råkar förstöra något så Users inte funkar längre så kan man fortfarande kolla på produkter och skapa ordrar.Fördelen när man delar upp backenden är att man kan jobbar på mindre delar utan att man behöver vara "rädd" för att hela sidan ska gå ner.  Nackdelen med detta sättet är att det kan bli sjukt många filer samt väldigt rörigt om man sitter själv med det. 
  
  ![image](https://user-images.githubusercontent.com/89379222/204226112-3a82ab5d-846d-426e-af96-53f4c1e85ed2.png)
  
  Monolitisk arkitektur innebär att man har sin backend på samma ställe som om man går in och råkar förstöra något så kommer inget funka. Fördelen med monolitisk är att det är lättare om man är en eller få kodare för det är inte så mycket filer. Nackdelden är att det är lättare att råka förstöra något och då kommer inget funka.


 Nämn två tekniker som fristående tjänster kan använda för att kommunicera med
 varandra.


Varför använder vi Docker, och hur kan det hjälpa oss?

Docker är en virtuell dator vi skapar för att köra ett program eller en Images som det heter i Docker. Detta gör man då men inte behöver förlita sig på att om man ska köra programet på en annan dator så kanske det inte funkar för man kanske inte har rätt nugets/packets instrallerat på den nya dator och då kommer inte programmet fungera. Om man ska göra en liten backend till ett litet företag så vill man inte åka ut och koda på deras dator. Och då skapar man en ny container via docker. Laddar upp det. Och då kan kunden bara ladda ner docker och hämta filen så kan kunden köra det direkt utan att tänka på om han har rätt variationer på programmen. Docker är ett smidigt sätt att alltid få koden att köra i samma miljö även fast man byter dator. 
