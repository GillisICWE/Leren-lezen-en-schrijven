Alvorens je een computerprogramma programmeert in Python, is het belangrijk dat je goed weet hoe je in Python gegevens aan de gebruiker van je programma vraagt en tijdelijk opslaat in een variabele. Uiteraard is het de bedoeling om het resultaat van je programma mee te delen aan de gebruiker.

## Invoer
Gegevens vragen doe je met de input()-opdracht. Wil je een nette boodschap tonen dan schrijf je tussen de haken een boodschap. Omdat de boodschap een stukje tekst is, schrijf je ze tussen quotes.

input('Hoe heet je? ')
Bij het uitvoeren van een input()-opdracht, wacht het programma op invoer van de gebruiker. Van zodra je een waarde opgeeft en op [Enter] klikt, wordt de uitvoering van het programma hervat.

Tijdens de uitvoering van je programma op het Dodona-platform, speelt Dodona de gebruiker: jij hoeft geen waarden op te geven, dat doet Dodona zelf. Meer nog, je zal die nette vraag naar je naam nooit te zien krijgen. Het is dus belangrijk dat je de waarde die Dodona opgeeft bijhoudt. Zo kan je programma dan bv. berekeningen maken met de opgegeven waarden.

## Variabele
Een waarde bijhouden doe je in een variabele. Het is een plaatsje in het geheugen van je computer die je met programmeercode een naam geeft. In onderstaande voorbeeld heet de variabele naam. De waarde die de variabele bijhoudt bijhoudt, is 010010110110100101101101, wat je via de ASCII-tabel vertaalt naar Kim.

Geheugen van een computer
Geheugen van een computer
In Python wordt dit:

naam = input('Hoe heet je? ')

Let erop dat namen van een variabele steeds bestaan uit kleine letters. Bestaat de naam van de variabele uit meerder woorden, gebruik dan underscores om de leesbaarheid te verhogen. Voorbeelden:

leeftijd
max_temperatuur
## Uitvoer
Wil je het resultaat van een berekening tonen, gebruik dan de print()-opdracht. Tussen de haken schrijf je wat je precies wil printen. Dit kan de waarde van een variabele zijn of een stukje letterlijke tekst. Je kan ook meerdere waarden opgeven aan een print()-opdracht, maar dan moet je ze aan elkaar lijmen met een plus-tekens.

```console?lang=python&prompt=>>>
print(naam)
print('15')
```
## Opgave
Schrijf een programma die je naam vraag en dan een mooie welkomstboodschap uitschrijft.

Voorbeelden
---
Invoer:
```console?lang=python&prompt=>>>
Marijke
```
Uitvoer:
```console?lang=python
Dag Marijke, welkom op het Dodona-platform!
```



Invoer:
```
Marc
```
Uitvoer:
```
Dag Marc, welkom op het Dodona-platform!
```