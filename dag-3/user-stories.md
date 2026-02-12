User Stories – Random Zinnen & WPM Website
1. Random zin genereren
User story:
Als gebruiker wil ik een willekeurige zin kunnen genereren, zodat ik meteen kan beginnen met typen.
Prioriteit: must
Acceptatiecriteria:
Er wordt automatisch een random zin getoond bij het laden van de pagina.
De gebruiker kan op een knop klikken om een nieuwe zin te genereren.
De zin bestaat uit minimaal 5 woorden.
Elke gegenereerde zin is anders dan de vorige (indien mogelijk).
2. WPM berekenen
User story:
Als gebruiker wil ik dat mijn woorden per minuut (WPM) automatisch worden berekend, zodat ik mijn typesnelheid kan meten.
Prioriteit: must
Acceptatiecriteria:
De timer start zodra de gebruiker begint met typen.
De timer stopt wanneer de zin volledig correct is ingevoerd.
De WPM wordt correct berekend volgens de standaardformule (aantal woorden / tijd in minuten).
De WPM-score wordt direct zichtbaar na voltooiing.
3. Foutenfeedback tijdens typen
User story:
Als gebruiker wil ik zien welke letters of woorden ik fout typ, zodat ik mijn nauwkeurigheid kan verbeteren.
Prioriteit: must
Acceptatiecriteria:
Fout getypte letters worden visueel gemarkeerd (bijv. rood).
Correct getypte letters worden visueel gemarkeerd (bijv. groen).
De gebruiker kan niet verder zonder de fout te corrigeren (of fouten worden apart geteld, afhankelijk van ontwerp).
De feedback wordt realtime bijgewerkt.
4. Nauwkeurigheid (accuracy) tonen
User story:
Als gebruiker wil ik mijn nauwkeurigheidspercentage zien, zodat ik weet hoe correct ik heb getypt.
Prioriteit: must
Acceptatiecriteria:
Het systeem berekent het percentage correct getypte tekens.
De accuracy wordt weergegeven samen met de WPM-score.
De berekening houdt rekening met fouten en verbeteringen.
De waarde wordt afgerond op maximaal 2 decimalen.
5. Opnieuw proberen (reset functie)
User story:
Als gebruiker wil ik de test opnieuw kunnen starten, zodat ik meerdere pogingen kan doen.
Prioriteit: must
Acceptatiecriteria:
Er is een duidelijke "Reset" of "Opnieuw" knop zichtbaar.
Bij reset wordt de timer teruggezet naar 0.
De invoer wordt leeggemaakt.
Er wordt een nieuwe random zin gegenereerd.
6. Moeilijkheidsniveau kiezen
User story:
Als gebruiker wil ik een moeilijkheidsniveau kunnen kiezen, zodat ik mezelf kan uitdagen.
Prioriteit: nice
Acceptatiecriteria:
De gebruiker kan kiezen tussen minimaal 2 niveaus (bijv. makkelijk / moeilijk).
Makkelijk: korte en eenvoudige zinnen.
Moeilijk: langere zinnen met complexere woorden.
Het gekozen niveau beïnvloedt de gegenereerde zinnen.
Het geselecteerde niveau blijft actief tot de gebruiker het wijzigt.
7. Scoregeschiedenis bekijken
User story:
Als gebruiker wil ik mijn vorige scores kunnen zien, zodat ik mijn vooruitgang kan volgen.
Prioriteit: nice
Acceptatiecriteria:
De laatste 5 scores worden opgeslagen.
Elke score toont WPM en accuracy.
Scores blijven bewaard tijdens de sessie (of via localStorage).
De lijst wordt automatisch bijgewerkt na elke voltooide test.