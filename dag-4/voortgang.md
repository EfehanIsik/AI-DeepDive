Voortgang – Type Master

Welke user story ben je gestart?
Ik ben gestart met de volgende must-have user stories:
Random zin genereren
WPM berekenen
Foutenfeedback tijdens typen
Accuracy tonen
Opnieuw proberen (reset functie)


Wat is (deels) af?

De basisfunctionaliteit van de applicatie is grotendeels af:
✅ Random zinnen worden gegenereerd uit een array.
✅ De zin wordt automatisch weergegeven bij het laden van de pagina.
✅ Start-knop initialiseert een nieuwe test.
✅ Timer start bij de eerste toetsaanslag.
✅ WPM wordt realtime berekend.
✅ Accuracy wordt realtime berekend.
✅ Letters worden per karakter gemarkeerd (correct / incorrect / current).
✅ Test stopt automatisch wanneer de zin volledig correct is getypt.
✅ Eindscore wordt getoond met WPM, accuracy en tijd.
✅ “New Sentence” knop start een nieuwe test.

Wat nog verbeterd kan worden:
⏳ Scoregeschiedenis opslaan (bijv. via localStorage).
⏳ Moeilijkheidsniveau toevoegen.
⏳ Verbeterde accuracy-berekening bij gebruik van backspace.
⏳ Voorkomen dat dezelfde zin direct opnieuw verschijnt.


Wat werkt al?

De volgende onderdelen functioneren correct:

1. Random zin generatie
Elke test toont een willekeurige zin uit de array.
De zin wordt opgesplitst in losse <span> elementen voor realtime feedback.
2. Realtime typing feedback
Correcte letters worden groen weergegeven.
Foute letters worden rood gemarkeerd.
De huidige positie wordt visueel aangegeven.
Feedback wordt direct bijgewerkt bij elke input.
3. Timer
Start automatisch bij eerste invoer.
Wordt elke 100ms geüpdatet.
Stopt wanneer de zin volledig correct is ingevoerd.
4. WPM berekening
Gebaseerd op standaardformule (5 karakters = 1 woord).
Wordt realtime geüpdatet.
Wordt opnieuw berekend bij afronding.
5. Accuracy berekening
Wordt berekend op basis van aantal fouten en totaal getypte karakters.
Wordt realtime geüpdatet.
Wordt weergegeven in procenten.
6. Reset functionaliteit
Nieuwe zin wordt gegenereerd.
Inputveld wordt geleegd.
Timer wordt gereset.
Statistieken worden teruggezet naar beginwaarden.