> 🌐 **Språk:** &nbsp; [🇬🇧 English](README.md) &nbsp;|&nbsp; [🇩🇪 Deutsch](README-DE.md) &nbsp;|&nbsp; [🇫🇷 Français](README-FR.md) &nbsp;|&nbsp; [🇳🇱 Nederlands](README-NL.md) &nbsp;|&nbsp; [🇪🇸 Español](README-ES.md) &nbsp;|&nbsp; [🇮🇹 Italiano](README-IT.md) &nbsp;|&nbsp; [🇵🇱 Polski](README-PL.md) &nbsp;|&nbsp; [🇨🇿 Čeština](README-CS.md) &nbsp;|&nbsp; [🇩🇰 Dansk](README-DA.md) &nbsp;|&nbsp; [🇳🇴 Norsk](README-NO.md) &nbsp;|&nbsp; 🇸🇪 Svenska &nbsp;|&nbsp; [🇭🇺 Magyar](README-HU.md) &nbsp;|&nbsp; [🇵🇹 Português](README-PT.md)

---

# 🚂 Open Source Model Railway Electronics

Välkommen! Den här organisationen innehåller öppen källkod-PCB:er och decodermoduler för modellbaneautomation.  
Allt här är fullt reproducerbart — alla designer, firmware och dokumentation är fritt tillgängliga.

Nedan hittar du PCB-designer och programvara för växelmotorer, DCC-solenoid-decoders, DCC-servo-decoders, S88n-spårbeläggningsmoduler, LED-belysningslist, relämoduler, analoga banstyrningspaneler och mer.

---

# 📘 Guider och förklaringar

Bakgrundsläsning för att förstå elektroniken och koncepten som används i dessa projekt:

- [Växlar och hjärtpunkter](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Points_and_frogs/points_and_frogs-EN.md)
- [Vändslingsproblemet](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/turning_loop_problem/turning_loop_problem-EN.md)
- [Automatisera en bana](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/automize_a_layout/automize_a_layout-EN.md)

<br>

---

# 🛠️ Bygg och beställ dina egna PCB:er

Steg-för-steg-guider för att ladda ned filer, lägga beställningar hos JLCPCB och flasha firmware:

- [Beställ ett naket PCB](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_bare_PCB/Ordering_bare_PCB-EN.md)
- [Beställ ett SMT-monterat PCB](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_SMT_ASSEMBLED_PCB/Ordering_Assembled_PCBs_JLCPCB-EN.md)
- [Programmera din OS DCC-decoder](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Program_OS-DCC-Decoder/Program_OS-DCC-Decoder-EN.md)

<br>

---

# 💡 Handledningar för att skapa egna PCB:er

- [Gör din egen anpassade LED-list](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_custom_LED_strip/makeYourOwnCustomLedStrip-EN.md)
- [Gör din egen kabelsplitter](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_split/make_your_own_wire_split-EN.md)
- *(kommer snart)* Gör din egen lödsömssyl
- *(kommer snart)* Gör din egen manöverpanel

<br>

---

# 🔀 DCC-tillbehörsdecoders

---

## OS-Duplex

OS-Duplex är en dubbel DCC-tillbehörsdecoder utformad för alla typer av växelmotorer — från traditionella tvillingspol-solenoider till motordrivna växelmotorer och relämoduler för hjärtpunktspolarisering.

Var och en av de två sidorna (A och B) kan arbeta oberoende eller länkas samman. Varje sida kan fungera som två oberoende enkelutgångar (varje med sin egen DCC-adress), eller som en kombinerad dubbelutgång för ett tvillingspol- eller motordrivet växeldon.

Optionella reläsocketar möjliggör hjärtpunktspolarisering eller drivning av extra spoler och motorer. OS-Duplex kan också driva en 4-lampssignal med alla möjliga aspekter.

![Förhandsgranskning](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/hardware/OS-Duplex.png?raw=true)

📖 [Manual (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/docs/Manual-SV.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex) &nbsp;|&nbsp; 📦 [Senaste release](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/releases/latest)

<br>

---

## OS-Duplex-Servo

OS-Duplex-Servo är en variant av OS-Duplex med utökat stöd för **servomotoroutputs** (standard 3-stifts PWM). Den är idealisk för servostyrda växelmotorer och behåller samma tvåkanalarkitektur, reläutvidgningsalternativ och signalstyrningsfunktioner som bas-OS-Duplex.

![Förhandsgranskning](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/hardware/OS-Duplex.png?raw=true)

📖 [Manual (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/docs/Manual-SV.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo) &nbsp;|&nbsp; 📦 [Senaste release](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/releases/latest)

<br>

---

## OS-Servo-Decoder-8

OS-Servo-Decoder-8 är en enkel och robust DCC-tillbehörsdecoder utformad för att driva upp till 8 servomotorer. Den stöder flexibel konfiguration via DCC-kommandon eller fysiska knappar, valfria reläutvidgningsmoduler för hjärtpunktspolarisering och direktstyrning med DCC-tillbehörskommandon eller lokfunktioner (F1–F8) — ingen dator eller CV-programmerare krävs.

![Förhandsgranskning](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/hardware/OS-Servo-Decoder-8.png?raw=true)

📖 [Manual (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/docs/Manual-SV.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8) &nbsp;|&nbsp; 📦 [Senaste release](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/releases/latest)

<br>

---

## OS-Solenoid-Decoder

OS-Solenoid-Decoder är en kraftfull DCC-tillbehörsdecoder för koppling av växlar (växelmotorer), reläer, avkopplare och andra solenoidstyrda enheter. Den hanterar upp till 5 A och stöder nästan alla typer av växelmotorer. Den är också kompatibel med OS-relämoduler för fullständig Electrofrog- och Unifrog-hjärtpunktspolarisering.

Viktiga funktioner:

- Upp till 8 dubbla utgångar för tvillingspol-växelmotorer
- Flera utgångslägen: Dubbel puls, Enkel puls, Dubbel kontinuerlig, Enkel kontinuerlig, Electrofrog
- Konfigurerbar via DCC-tillbehörskommandon — ingen dator behövs
- Valfritt CDU-modulstöd
- Utvidgningsbar med relä- och transistorkort

![Förhandsgranskning](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/hardware/OS-Solenoid-Decoder.png?raw=true)

📖 [Manual (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/docs/Manual-SV.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder) &nbsp;|&nbsp; 📦 [Senaste release](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/releases/latest)

<br>

---

# 📡 Återkoppling och spårbeläggningsdetektering

---

## OS-S88n (CS / GND / OPTO)

OS-S88n-modulerna tillhandahåller S88n-återkoppling för DCC-modelljärnvägar och möjliggör realtidsövervakning av spårbeläggning och banor. Data skickas till din kommandostation eller PC-baserade program (iTrain, Rocrail, Windigipet och andra).

Tre varianter finns tillgängliga:

- **OS-S88n GND** — jordkontaktdetektering, idealisk för 3-skena-banor (Märklin-stil)
- **OS-S88n CS** — strömavkänningsdetektering, lämplig för 2-skena- och 3-skena-banor
- **OS-S88n OPTO** — optoelektriskt isolerade ingångar för IR-detektorer, Hall-sensorer och andra externa sensorer

Alla versioner kan seriekopplas via RJ-45 och stöder upp till 31 moduler i en enda kedja.

![Förhandsgranskning](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/all.png?raw=true)

📖 [Manual (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/Manual-SV.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n) &nbsp;|&nbsp; 📦 [Senaste release](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/releases/latest)

<br>

---

# 🔌 Relämoduler

---

## OS-relays

OS-relämodulerna är inkopplningsbara reläkort utformade för att fungera tillsammans med OS DCC-decoders. Två typer finns tillgängliga:

- **OS-General-Purpose-Relay** — dubbelt monostabilt relä med COM/NO/NC-kontakter; lämplig för hjärtpunktspolarisering (Electrofrog och Unifrog) och allmän tillbehörskoppling
- **OS-Latching-Relay** — enda bistabilt relä som håller sin position utan kontinuerlig ström; idealisk för Unifrog-polarisering kopplad parallellt med solenoiden

Båda typerna finns i THT- och SMD-versioner och kan beställas som löstagbara paneler.

![Förhandsgranskning](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/all.png?raw=true)

📖 [Manual (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/Manual-SV.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays) &nbsp;|&nbsp; 📦 [Senaste release](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/releases/latest)

<br>

---

# 💡 Belysning

---

## OS-Lux-One

OS-Lux-One är ett modulärt LED-belysningslist för digitalt modelljärnvägens rullande materiel. Det ersätter flera fasta vagnbelysningslister med en universell version som kan klippas till önskad storlek och återanvändas. Varje sektion har sin egen inbyggda strömregulator för stabil ljusstyrka oavsett spårspänning, och listan drivs direkt från DCC, MM eller mfx spårström. Lämplig för både H0- och N-skala.

![Förhandsgranskning](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/hardware/OS-Lux-One/OS-Lux-One.pdf?raw=true)

📖 [Manual (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/docs/Manual-SV.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One) &nbsp;|&nbsp; 📦 [Senaste release](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/releases/latest)

<br>

---

# 🎛️ Analog banstyrning

---

## Analog-Layout-Control

Ett sortiment av analoga banstyrningsmoduler utformade som modulära byggstenar för anpassade manöverpaneler. Alla moduler använder standard JST-kontakter för enkel kabeldragning och kompatibilitet. Kombinera dem för att bygga allt från enkel hyttstyrningskoppling till fullständig spårvägsuppläggning via diodmatriser.

Moduler i detta sortiment inkluderar:

- CAB Control Switch — tilldelar spåravsnitt till Cab A eller Cab B, med LED-återkoppling
- Point Motor Switch — inverterar polaritet för 2-tråds växelmotorer
- Solenoid Point Switch med återkoppling — momentan styrning för tvillingspoldrivningar
- Latching Relay — bistabilt relä för hjärtpunktspolarisering eller avsnittskoppling
- Diodmatris — spårvägsuppläggningskort för aktivering av flera växlar med en enda knapp

![Förhandsgranskning](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/hardware/Analog-Layout-Control.png?raw=true)

📖 [Manual (EN)](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/docs/Manual-SV.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control) &nbsp;|&nbsp; 📦 [Senaste release](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/releases/latest)

<br>

---

## Vändslingsmoduler

Vändslingsmodulerna hanterar automatiskt den polaritetsomvändning som behövs när ett tåg kör in i eller ut ur en vändslinga (Y-koppling, ballongslinga eller vändskiva). Modulen detekterar kortslutningen som orsakas av ett omvänt lok och korrigerar polariteten automatiskt, utan någon manuell åtgärd.

![Förhandsgranskning](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/blob/main/hardware/turning-loop-modules.png?raw=true)

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules) &nbsp;|&nbsp; 📦 [Senaste release](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/releases/latest)

<br>

---

# 🔩 Passiva komponenter och kabeldragning

---

## Wire-Splits

Wire-Split PCB:er är kompakta passiva fördelningskort för att dela upp en ingångskabel rent i flera utgångar. De gör det enkelt att distribuera DCC-spårström eller gemensamma kablar till många punkter på din bana utan röriga knippebuntar.

![Förhandsgranskning](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/blob/main/hardware/Wire-Splits.png?raw=true)

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits) &nbsp;|&nbsp; 📦 [Senaste release](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/releases/latest)

<br>

---

## Solder Sleepers

Solder Sleepers är PCB-baserade spårsliprar utformade för att klistras fast i spårbädden. PCB-slipern låter dig löda räls direkt på kortet för en tillförlitlig elektrisk och mekanisk anslutning — idealisk för byggt-från-grunden-spår, dioramaarbete eller överallt där ett fast lödfogar föredras framför klämmor.

![Förhandsgranskning](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/blob/main/docs/Solder-sleepers.png?raw=true)

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers) &nbsp;|&nbsp; 📦 [Senaste release](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/releases/latest)

<br>

---

# 🖥️ Programvara

---

## OS-Software-Tool

OS-Software-Tool är ett PC-verktyg för konfigurering och testning av OS DCC-decoders. Det tillhandahåller ett grafiskt gränssnitt för uppgifter som annars skulle kräva manuella DCC-kommandonsekvenser.

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-software-tool)

<br>

---
