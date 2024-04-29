## UDP-Server:

# Vraag 1:

UDP SOCKETS correct : het aanmaken, verbinden en opruimen van sockets

Waar


# Vraag 2:

CLIENT to SERVER COMMUNICATION correct : UDP-client stuurt correcte integers in ASCII en worden juist ontvangen door UDP-server en vergeleken worden het het te raden getal dat de eerste keer genereert wordt (tussen 0 en 99)

Waar


# Vraag 3:

TIME-OUT correct : UDP-server maakt gebruik van een time-out om alle gokken te ontvangen en pas bij time-out de mogelijke winnaar aanduidt, UDP-client maakt gebruik van een time-out om te bepalen of het mogelijks gewonnen of verloren heeft.

Waar


# Vraag 4:

DYNAMIC TIME-OUT correct : UDP-server halveert de time-out per gok dat binnenkomt.

Waar


# Vraag 5:

SERVER to CLIENT COMMUNICATION correct : enkel de dichtste gok en gokker worden genomineerd voor te winnen door het bericht "You Won ?", bij het wegblijven van een bericht, print de UDP-client "You lost ?"

Waar
Niet waar

# Vraag 6:

LATE MESSAGES correct : UDP-server stuurt "You lost !" op elk bericht dat binnenkomt gedurende bepaalde tijd (inclusief time-out) nadat de mogelijke winnaar is geselecteerd. Indien dit dezelfde client is die genomineerd is, zal deze toch niet winnen.

Waar


# Vraag 7:

WINNER correct : UDP-server stuurt correcte moment en naar juiste UDP-client "You won !" die enkel binnen tijd en als eerste de dichtste gok heeft gedaan.

Waar


# Vraag 8:

CONTINOUS correct : UDP-server en UDP-client moeten niet herstarten om een volgende ronde te kunnen spelen en er wordt een nieuw random nummer gekozen.

Waar
Niet waar

# Vraag 9:

CLEAN CODE : (Eens alles juist werkt) UDP-server en UDP-client code zijn volgens industriestandaard geschreven in handelbare functies en geen globale variabelen.

Waar
Niet waar

# Vraag 10:

EXTRA : (Eens alles juist werkt) bijvoorbeeld : high-score met IP en poort, logging to files met IP en poort, gaming AI-client, ...

Waar
Niet waar

## TCP-Server:

# Vraag 1:

TCP SOCKETS correct : het aanmaken, verbinden en opruimen van sockets

Waar


# Vraag 2:

CLIENT to SERVER COMMUNICATION correct : TCP-client stuurt correcte integers in network-byte-order en worden juist ontvangen door TCP-server en vergeleken met het te raden getal dat genereert wordt tijdens connectie (tussen 0 en 1 000 000)

Waar


# Vraag 3:

SERVER to CLIENT COMMUNICATION correct : elke gok wordt beantwoord met "Hoger", "Lager" of "Correct" afhankelijk van het te raden getal en de gok.

Waar


# Vraag 4:

CLOSING CONNECTION correct : de TCP-server sluit de connectie als eerste indien de gok "Correct" was, maar ook de TCP-client kan elk moment de connectie sluiten om te stoppen met spelen. Alle handlers en geheugen wordt proper opgeruimd.

Waar


# Vraag 5:

CONTINOUS correct : TCP-server en TCP-client moeten niet herstarten om een volgende ronde te kunnen spelen en er wordt een nieuw random nummer gekozen.

Waar
Niet waar

# Vraag 6:

MULTIPLE CLIENTS correct : TCP-server kan meerdere simultane TCP-clients tegelijk bedienen met elk hun getal.

Waar
Niet waar

# Vraag 7:

MULTIPLE CLIENTS clean & correct : er is geen nutteloze overhead bij meerdere clients, er wordt gewerkt met Synchronous I/O Multiplexing, i.e. poll() of select()

Waar
Niet waar

# Vraag 8:

CLEAN CODE : (Eens alles juist werkt) TCP-server en TCP-client code zijn volgens industriestandaard geschreven in handelbare functies en geen globale variabelen.

Waar
Niet waar

# Vraag 9:

EXTRA : (Eens alles juist werkt) bijvoorbeeld : high-score met IP en poort, logging to files met IP en poort, gaming AI-client, ...

Waar
Niet waar


# Vraag 10:
PROFESSIONAL : Code staat op GitHub, i.e. enkel juiste bestanden, meerdere nuttige commits en uitleg


Waar
