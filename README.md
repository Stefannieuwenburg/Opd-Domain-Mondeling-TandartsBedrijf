Het is gelukt, je bent als programmeur aan de slag gegaan. En als freelancer nog wel! En je hebt ook al een eerste klant: Tandartspraktijk B.V.T.!



Zij willen dat jij een systeem bouwt waarmee de assistenten en tandartsen kunnen werken om afspraken te beheren. De focus van deze opdracht ligt op het correct "modelleren" van de verschillende "entiteiten" (dingen) en operaties (veranderingen) in dit systeem. Je richt je bij deze opdracht dus met name op de state van je applicatie.



Om het rekenen met dagen makkelijker te maken kun je doen alsof maandag dag 1 is, dinsdag dag 2 is etc, er zijn precies 4 weken in elke maand en elke maand is (dus) 28 dagen. Alle afspraken vallen binnen deze maand. We zitten nu vóór die maand (dus alle afspraken kunnen nog gewijzigd worden).



Om het rekenen met tijd makkelijker te maken duurt elke afspraak een uur en valt elke afspraak op het hele uur, dus 9:00u, 14:00u etc.



Je mag zelf namen, telefoonnummers, emailadressen verzinnen voor de mensen in het systeem. Je kan met behulp van https://www.mockaroo.com zelf een 'mock' API maken, die je kunt gebruiken om random persoonsdata te genereren en op te halen. Je mag ook een andere (mock) API gebruiken.

Implementeer de volgende functionaliteiten:

de praktijk heeft tandartsen
de praktijk heeft assistenten
elke tandarts en assistent heeft een voornaam, een achternaam, een telefoonnummer en een emailadres dat eindigt op "tandartspraktijkbvt.nl"
tandartsen en assistenten kunnen ziek worden, ze kunnen dan niet werken
patiënten kunnen ziek worden, de afspraak moet dan verwijderd worden
de praktijk heeft patiënten
elke patiënt heeft een voornaam, een achternaam, een telefoonnummer, een emailadres en een geboortejaar (geen datum)
een afspraak is altijd met één patiënt
een afspraak is altijd met één tandarts
een afspraak is soms ook met een assistent erbij
een afspraak heeft een datum (dat is het dagnummer) en een tijdstip in hele uren
in het weekend is de praktijk gesloten
een tandarts of assistent kan niet twee afspraken op hetzelfde moment hebben


Als je de React applicatie opstart moeten alle entiteiten aanwezig zijn in je systeem:

4 tandartsen
2 assistenten
50 patiënten
150 afspraken in de komende maand


Gebruik één JavaScript object hebt met daarin alle state van deze applicatie, zoals je dat bij een simpele React applicatie zou hebben.


Views
De views krijg je van ons, je hoeft de HTML en CSS dus niet te verzinnen maar wel genereren op basis van de state van je systeem.

in het voorbeeld-kalendaroverzicht zijn de afspraken niet gesorteerd op tijd, dat moet wel
in het voorbeeld-dagoverzicht zijn de afspraken niet gesorteerd op tijd, dat moet wel
als een afspraak géén tandarts heeft (vanwege ziekte bijvoorbeeld), geef die dan een rode achtergrondkleur
