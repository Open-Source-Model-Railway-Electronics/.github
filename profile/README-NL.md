> 🌐 **Taal:** &nbsp; [🇬🇧 English](README.md) &nbsp;|&nbsp; [🇩🇪 Deutsch](README-DE.md) &nbsp;|&nbsp; [🇫🇷 Français](README-FR.md) &nbsp;|&nbsp; 🇳🇱 Nederlands &nbsp;|&nbsp; [🇪🇸 Español](README-ES.md) &nbsp;|&nbsp; [🇮🇹 Italiano](README-IT.md) &nbsp;|&nbsp; [🇵🇱 Polski](README-PL.md) &nbsp;|&nbsp; [🇨🇿 Čeština](README-CS.md) &nbsp;|&nbsp; [🇩🇰 Dansk](README-DA.md) &nbsp;|&nbsp; [🇳🇴 Norsk](README-NO.md) &nbsp;|&nbsp; [🇸🇪 Svenska](README-SV.md) &nbsp;|&nbsp; [🇭🇺 Magyar](README-HU.md) &nbsp;|&nbsp; [🇵🇹 Português](README-PT.md)

---

# 🚂 Open Source Model Railway Electronics

Welkom! Deze organisatie bevat open-source PCB's en decoder­modules voor modelbaan­automatisering.  
Alles hier is volledig reproduceerbaar — alle ontwerpen, firmware en documentatie zijn vrij beschikbaar.

Hieronder vindt u PCB-ontwerpen en software voor wisselaandrijvingen, DCC-magneet­decoders, DCC-servo­decoders, S88n-bezettings­terugmeld­modules, LED-verlichtingsstrips, relais­modules, analoge baan­besturings­panelen en meer.

---

# 📘 Handleidingen & Uitleg

Achtergrondinformatie om de elektronica en concepten die in deze projecten worden gebruikt te begrijpen:

- [Wissels & Hartpunten](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Points_and_frogs/points_and_frogs-EN.md)
- [Het Keerlus­probleem](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/turning_loop_problem/turning_loop_problem-EN.md)
- [Een Baan Automatiseren](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/automize_a_layout/automize_a_layout-EN.md)

<br>

---

# 🛠️ Bouw & Bestel Uw Eigen PCB's

Stap-voor-stap handleidingen voor het downloaden van bestanden, het plaatsen van bestellingen bij JLCPCB en het flashen van firmware:

- [Bestel een Kale PCB](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_bare_PCB/Ordering_bare_PCB-EN.md)
- [Bestel een SMT-gemonteerde PCB](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_SMT_ASSEMBLED_PCB/Ordering_Assembled_PCBs_JLCPCB-EN.md)
- [Programmeer Uw OS DCC Decoder](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Program_OS-DCC-Decoder/Program_OS-DCC-Decoder-EN.md)

<br>

---

# 💡 Maak Uw Eigen PCB-tutorials

- [Maak Uw Eigen Aangepaste LED-strip](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_custom_LED_strip/makeYourOwnCustomLedStrip-EN.md)
- [Maak Uw Eigen Draad­splitter](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_split/make_your_own_wire_split-EN.md)
- *(binnenkort)* Maak Uw Eigen Soldeer­dwarsligger
- *(binnenkort)* Maak Uw Eigen Bedieningspaneel

<br>

---

# 🔀 DCC-accessoire­decoders

---

## OS-Duplex

De OS-Duplex is een dubbele DCC-accessoire­decoder ontworpen voor alle soorten wisselaandrijvingen — van traditionele twee­spoels­magneten tot motor­gestuurde wisselaandrijvingen en relais­modules voor hartpunt­polarisering.

Elk van de twee kanten (A en B) kan onafhankelijk werken of aan elkaar worden gekoppeld. Elke kant kan fungeren als twee onafhankelijke enkele uitgangen (elk met een eigen DCC-adres), of als één gecombineerde dubbele uitgang voor een twee­spoels- of motoraandrijving.

Optionele relais­sockets staan hartpunt­polarisering toe of het aansturen van extra spoelen en motoren. De Duplex kan ook een 4-lampen­sein aansturen met elk mogelijk aspect.

![Voorbeeld](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/hardware/OS-Duplex.png?raw=true)

📖 [Handleiding (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/docs/Manual-NL.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex) &nbsp;|&nbsp; 📦 [Laatste release](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/releases/latest)

<br>

---

## OS-Duplex-Servo

De OS-Duplex-Servo is een variant van de OS-Duplex met toegevoegde ondersteuning voor **servo­motor­uitgangen** (standaard 3-polige PWM). Hij is ideaal voor servo­gestuurde wisselaandrijvingen en behoudt dezelfde dubbel­kanaal­architectuur, relais­uitbreidings­opties en seinbe­sturings­mogelijkheden als de basis OS-Duplex.

![Voorbeeld](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/hardware/OS-Duplex.png?raw=true)

📖 [Handleiding (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/docs/Manual-NL.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo) &nbsp;|&nbsp; 📦 [Laatste release](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/releases/latest)

<br>

---

## OS-Servo-Decoder-8

De OS-Servo-Decoder-8 is een eenvoudige en robuuste DCC-accessoire­decoder ontworpen voor het aansturen van maximaal 8 servo­motoren. Hij ondersteunt flexibele configuratie via DCC-commando's of fysieke knoppen, optionele relais­uitbreidings­modules voor hartpunt­polarisering, en directe besturing via DCC-accessoire­commando's of locomotief­functies (F1–F8) — geen computer of CV-programmeur vereist.

![Voorbeeld](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/hardware/OS-Servo-Decoder-8.png?raw=true)

📖 [Handleiding (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/docs/Manual-NL.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8) &nbsp;|&nbsp; 📦 [Laatste release](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/releases/latest)

<br>

---

## OS-Solenoid-Decoder

De OS-Solenoid-Decoder is een krachtige DCC-accessoire­decoder voor het schakelen van wissels (wisselaandrijvingen), relais, ontkoppelaars en andere magneet­aangedreven apparaten. Hij kan tot 5 A aan en ondersteunt vrijwel elk type wisselaandrijving. Hij is ook compatibel met OS-relais­modules voor volledige electrofrog- en unifrog-hartpunt­polarisering.

Belangrijkste kenmerken:

- Tot 8 dubbele uitgangen voor twee­spoels­wisselaandrijvingen
- Meerdere uitgangs­modi: Dubbele puls, Enkele puls, Dubbel continu, Enkel continu, Electrofrog
- Configureerbaar via DCC-accessoire­commando's — geen computer nodig
- Optionele CDU-module­ondersteuning
- Uitbreidbaar met relais- en transistor­kaarten

![Voorbeeld](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/hardware/OS-Solenoid-Decoder.png?raw=true)

📖 [Handleiding (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/docs/Manual-NL.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder) &nbsp;|&nbsp; 📦 [Laatste release](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/releases/latest)

<br>

---

# 📡 Terugmelding & Bezettings­detectie

---

## OS-S88n (CS / GND / OPTO)

De OS-S88n-modules bieden S88n-terugmelding voor DCC-modelbanen, waarmee bezetting van blokken en baan­gebeurtenissen in real time kunnen worden bewaakt. Gegevens worden verstuurd naar uw centrale of pc-gestuurd programma (iTrain, Rocrail, Windigipet en andere).

Er zijn drie varianten beschikbaar:

- **OS-S88n GND** — massa­contact­detectie, ideaal voor 3-rail (Märklin-stijl) banen
- **OS-S88n CS** — stroom­detectie, geschikt voor 2-rail en 3-rail banen
- **OS-S88n OPTO** — optisch geïsoleerde ingangen voor IR-detectoren, Hall-sensoren en andere externe sensoren

Alle versies zijn doorlus­schakelbaar via RJ-45 en ondersteunen tot 31 modules in één keten.

![Voorbeeld](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/all.png?raw=true)

📖 [Handleiding (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/Manual-NL.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n) &nbsp;|&nbsp; 📦 [Laatste release](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/releases/latest)

<br>

---

# 🔌 Relais­modules

---

## OS-relays

De OS-relais­modules zijn insteek­bare relais­kaarten ontworpen voor gebruik naast OS DCC-decoders. Er zijn twee typen beschikbaar:

- **OS-General-Purpose-Relay** — dubbel mono­stabiel relais met COM/NO/NC-contacten; geschikt voor hartpunt­polarisering (electrofrog en unifrog) en algemene accessoire­schakeling
- **OS-Latching-Relay** — enkel bistabiel relais dat zijn stand behoudt zonder continue voeding; ideaal voor unifrog-polarisering parallel geschakeld aan de magneet

Beide typen zijn beschikbaar in THT en SMD versies en kunnen als losbreekbare panelen worden besteld.

![Voorbeeld](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/all.png?raw=true)

📖 [Handleiding (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/Manual-NL.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays) &nbsp;|&nbsp; 📦 [Laatste release](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/releases/latest)

<br>

---

# 💡 Verlichting

---

## OS-Lux-One

De OS-Lux-One is een modulaire LED-verlichtingsstrip voor digitaal modelbaan­rijtuig­materieel. Het vervangt meerdere verlichtingsstrips met vaste lengte door één universele versie die op maat kan worden gesneden en hergebruikt. Elk onderdeel heeft zijn eigen ingebouwde stroom­regelaar voor stabiele helderheid ongeacht de baan­spanning, en de strip werkt rechtstreeks op DCC-, MM- of mfx-baan­spanning. Geschikt voor zowel H0 als N schaal.

![Voorbeeld](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/hardware/OS-Lux-One/OS-Lux-One.pdf?raw=true)

📖 [Handleiding (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/docs/Manual-NL.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One) &nbsp;|&nbsp; 📦 [Laatste release](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/releases/latest)

<br>

---

# 🎛️ Analoge baan­besturing

---

## Analog-Layout-Control

Een reeks analoge baan­besturings­modules ontworpen als modulaire bouw­stenen voor aangepaste bedienings­panelen. Alle modules gebruiken standaard JST-aansluitingen voor eenvoudige bedrading en uitwisselbaarheid. Combineer ze om alles te bouwen van eenvoudige rijstroom­besturings­schakeling tot volledige route-instelling via diodematrices.

Modules in dit assortiment zijn:

- CAB-besturingsschakelaar — wijst baansecties toe aan Cab A of Cab B, met LED-terugmelding
- Wisselmotor­schakelaar — keert polariteit om voor 2-draads wisselaandrijvingen
- Magneetschakelaar met terugmelding — impulsbediening voor twee­spoels­aandrijvingen
- Bistabiel relais — bistabiel relais voor hartpunt­polarisering of sectie­schakeling
- Diodematrix — route-instelkaart voor het activeren van meerdere wissels met één knop

![Voorbeeld](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/hardware/Analog-Layout-Control.png?raw=true)

📖 [Handleiding (EN)](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/docs/Manual-NL.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control) &nbsp;|&nbsp; 📦 [Laatste release](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/releases/latest)

<br>

---

## Keerlus­modules

De keerlus­modules verwerken automatisch de polariteits­omkering die nodig is wanneer een trein een keerlus binnenrijdt of verlaat (driehoek, ballonlus of draaischijf). De module detecteert de kortsluiting veroorzaakt door een omgekeerde locomotief en corrigeert de polariteit automatisch, zonder handmatige tussenkomst.

![Voorbeeld](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/blob/main/hardware/turning-loop-modules.png?raw=true)

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules) &nbsp;|&nbsp; 📦 [Laatste release](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/releases/latest)

<br>

---

# 🔩 Passieve componenten & bedrading

---

## Wire-Splits

Wire-Split PCB's zijn compacte passieve verdeel­kaarten voor het netjes opsplitsen van één invoer­draad naar meerdere uitgangen. Ze maken het eenvoudig om DCC-baan­spanning of gemeenschappelijke draden te verdelen naar vele punten op uw baan zonder rommelige draad­bundels.

![Voorbeeld](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/blob/main/hardware/Wire-Splits.png?raw=true)

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits) &nbsp;|&nbsp; 📦 [Laatste release](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/releases/latest)

<br>

---

## Solder Sleepers

Solder Sleepers zijn PCB-gebaseerde spoor­dwarsliggers ontworpen om in het baan­bed te worden gelijmd. De PCB-dwarsligger maakt het mogelijk de rail rechtstreeks op de kaart te solderen voor een betrouwbare elektrische en mechanische verbinding — ideaal voor zelf­gebouwd spoor, diorama­werk, of overal waar een solide soleer­verbinding de voorkeur heeft boven klemmen.

![Voorbeeld](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/blob/main/docs/Solder-sleepers.png?raw=true)

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers) &nbsp;|&nbsp; 📦 [Laatste release](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/releases/latest)

<br>

---

# 🖥️ Software

---

## OS-Software-Tool

De OS-Software-Tool is een pc-hulp­programma voor het configureren en testen van OS DCC-decoders. Het biedt een grafische interface voor taken waarvoor anders handmatige DCC-commando­reeksen nodig zouden zijn.

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-software-tool)

<br>

---
