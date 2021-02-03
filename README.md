# Graftak-server-commands

Overzicht commands en uitleg functies Graftak
Op de server, onder de spawn is dit nog in/game beschreven. Typ /spawn, draai je om en loop naar beneden.
SCROLL NAAR BENEDEN OVER UITLEG VERSCHILLENDE PLUGINS
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Eerst een lijst met beschikbare commands:
/kit tools - Stone tools om mooi te beginnen.
/help (pagina nummer) - Ingame lijst met commands
/motd - Startbericht
/rules - Regels
/seen (speler) - Laatst online 
/time - In game tijd
/helpop - Stuur een bericht naar Bennie
/suicide - R.I.P
/list - Lijst met personen online
/clearinventory - Leeg je inventory
/ping - Pang!
/ignore (persoon) - negeer iemand totdat je opnieuw inlogd.
/book - Bewerk een vasthoudend boek ookal is het al gesigneerd.
/afk - Stel jezelf afwezig, je hebt dan god mode tot de tijd dat je weer beweegt. Na 3min afwezig is dit automatisch.
/enderchest /ec - Portable enderchest
/depth - Diepte t.o.v 63 blocks

Chat:
/mail - algemeen command mail
/mail read - Lees je mail		
/mail clear - Leeg je mail
/mail send (persoon) (bericht) - Stuur een E-mail naar een persoon
/msg (persoon) (bericht) - Stuur een instant privébericht
/reply - reageer op privébericht


Economie:
/itemdb - Info over blok in hand
/balance /bal - Jouw huidige saldo
/balancetop - Servertop qua geld
/pay (persoon) - Betaal iemand

Teleporteren:
/warp - Lijst met warps
/warp (locatie) - Warp naar locatie
/compass - Toon je looprichting
/tpa (persoon) - Stuur teleport verzoek naar persoon
/tpahere - Stuur teleport verzoek naar jouw
/tpaccept - Accepteer teleport verzoek	
/tpdeny - Weiger teleport verzoek
/back - Ga terug naar vorige locatie
/home - Ga naar je eerste huis
/home (naam) - Ga naar je diverse huizen
/sethome (naam)- Zet een privé teleport (max 8)
/delhome (naam) - Verwijder privé teleport	

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Hoe bescherm ik mijn kisten en deuren? -LWC

LET OP: Eerst werd er automatisch protectie toegevoegd. Nu moet je zelf een bescherming aanbrengen.
Deze server heeft een speciale plugin om blokken die spullen kunnen bevatten (denk aan chests, hoppers,...) en deuren (doors/trapdoors) te beschermen.
Via deze plugin kunnen de volgende items beschermd worden: banner, fence gate,(trap)door, composter, barrel, hopper en dropper, dispenser, smoker, (blast)furnace, (trapped)chest.
Typ /lwc in de chat voor een lijst aan commands.
Uitgelegd in het Nederlands:

Basic commands:
/cprivate /lock - Maak een item privé, alleen jij kan het bedienen.
/cpublic - Maak een publiekelijks, mensen kunnen het bedienen maar niet slopen.
/cdonation - Zet een donatiekist. Mensen kunnen spullen er in doen maar niet er uit halen.
/cdisplay - Zet een protectie voor een itemframe.
/cpassword (wachtwoord) - Zet een item met een wachtwoord, alleen mensen met een wachtwoord kunnen dit bedienen.
/cunlock (wachtwoord) - Geef jezelf toegang tot een item met een gegeven wachtwoord.
/cmodify (speler) - Geef een speler toegang tot een beschermd item van jouw.
/cmodify -(speler) - Minus teken (-) voor de naam, haal toegang van een speler bij jouw bescherming weg.
/cremove -  Haal complete protectie van een blok af
/cremoveall - Haal al jouw geregistreede protectie weg (PAS OP HIERMEE.)
/cinfo - Informatie over beschermd item.
/climits - Limiet aan protectie, is toch oneindig dus boeit niet zoveel.

Advanced commands: GEBRUIK ALLEEN WANNEER JE ER VERSTAND VAN HEB.
/lwc flag (flag) (on/off) - Opties tot aanvullende bescherming, typ |/lwc flag| voor een complete lijst.
/lwc mode - Zou ik maar gewoon niet gebruiken, word ook in de toekomst weggehaald.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Chestshop - ECONOMIE
In dit item vind je de basisuitleg hoe je jouw eigen winkel kan opstellen en bij iemand kan kopen/verkopen.
Rondom de spawn is de centrale locatie voor shops. Ook kun je daar jouw eigen shop bouwen! Hou het wel een beetje netjes.

Een chestshop ziet er uit als een chest, met daarop een bordje. Op dit bordje staat het volgende beschreven (boven naar beneden):
1. Naam
2. Hoeveelheid te (ver)kopen item
3. Prijs, B betekent dat iemand iets wil kopen van jouw, S betekent dat iemand iets wil verkopen aan jouw
4. Itemnaam (gebruik /itemdb voor informatie van de item in hand)

De algemene regel voor het kopen en verkopen: 
Klik met de linkermuisknop om te verkopen. Klik met de rechtermuisknop om te kopen.

Hoe maak ik een eigen shop?
Het is handig om je shop bij spawn te maken. Hierdoor is de markt gecentraliseerd en kunnen spelers makkelijker bij jouw shop komen.
Wat heb ik nodig?
- Een chest
- Een sign

Om een sell shop te maken (items te verkopen):
Zet een chest neer en plaats aan de voorkant een sign. Op de sign zet je op de vier lijnen de volgende informatie:
1. Jouw in game naam (NIET JE NICKNAME)
2. Hoeveelheid die je tegelijkertijd wil verkopen
3. Prijs, te noteren met| S (prijs) |
4. De itemnaam (gebruik /itemdb voor informatie van de item in hand)
Nu staat er in de chat dat er een shop succesvol is aangemaakt. Plaats je te verkopen item in de chest. Mensen kunnen nu door middel van rechter muisknop op de sign het item bij je kopen.


Om een buy shop te maken (items te kopen):
Zet een chest neer en plaats aan de voorkant een sign. Op de sign zet je op de vier lijnen de volgende informatie:
1. Jouw in game naam (NIET JE NICKNAME)
2. Hoeveelheid die je tegelijkertijd wil verkopen
3. Prijs, te noteren met| B (prijs) |
4. De itemnaam (gebruik /itemdb voor informatie van de item in hand)
Nu staat er in de chat dat er een shop succesvol is aangemaakt. Mensen kunnen nu het geselecteerde item aan jouw verkopen.

Om een buy en sell shop tegelijkertijd te maken (items te kopen en verkopen)
Zet een chest neer en plaats aan de voorkant een sign. Op de sign zet je op de vier lijnen de volgende informatie:
1. Jouw in game naam (NIET JE NICKNAME)
2. Hoeveelheid die je tegelijkertijd wil verkopen
3. Prijs te noteren als volgt: B (prijs) S (prijs)
4. De itemnaam (gebruik /itemdb voor informatie van de item in hand)
Nu staat er in de chat dat er een shop succesvol is aangemaakt. Mensen kunnen nu het geselecteerde item aan jouw kopen maar ook verkopen.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

MINIGAMES (3-02-2021):
SPLEEF - Gebruik | /warp spleef | om naar de spleef te gaan. Rechtermuisknop op de sign om te joinen.
