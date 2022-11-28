# Inlamning1

 Vad är skillnaden mellan monolitisk och mikrotjänst-arkitektur innebär. Redogör kort
  för hur varje del fungerar
  
  ![image](https://user-images.githubusercontent.com/89379222/204225077-934247d0-8563-4be4-8022-bdd289dfcc42.png)
  
  Detta är en bild som förklarar vad microtjänser innebär. Det är när man bryter ut backenden till små delar. Så tex Users, om man skulle gå in och ändra hur den funkar och råkar förstöra något så Users inte funkar längre så kan man fortfarande kolla på produkter och skapa ordrar.Fördelen när man delar upp backenden är att man kan jobbar på mindre delar utan att man behöver vara "rädd" för att hela sidan ska gå ner.  Nackdelen med detta sättet är att det kan bli sjukt många filer samt väldigt rörigt om man sitter själv med det. 
  
  ![image](https://user-images.githubusercontent.com/89379222/204226112-3a82ab5d-846d-426e-af96-53f4c1e85ed2.png)
  
  Monolitisk arkitektur innebär att man har sin backend på samma ställe som om man går in och råkar förstöra något så kommer inget funka. Fördelen med monolitisk är att det är lättare om man är en eller få kodare för det är inte så mycket filer. Nackdelden är att det är lättare att råka förstöra något och då kommer inget funka.
