> 🌐 **Språk:** &nbsp; [🇬🇧 English](README.md) &nbsp;|&nbsp; [🇩🇪 Deutsch](README-DE.md) &nbsp;|&nbsp; [🇫🇷 Français](README-FR.md) &nbsp;|&nbsp; [🇳🇱 Nederlands](README-NL.md) &nbsp;|&nbsp; [🇪🇸 Español](README-ES.md) &nbsp;|&nbsp; [🇮🇹 Italiano](README-IT.md) &nbsp;|&nbsp; [🇵🇱 Polski](README-PL.md) &nbsp;|&nbsp; [🇨🇿 Čeština](README-CS.md) &nbsp;|&nbsp; [🇩🇰 Dansk](README-DA.md) &nbsp;|&nbsp; 🇳🇴 Norsk &nbsp;|&nbsp; [🇸🇪 Svenska](README-SV.md) &nbsp;|&nbsp; [🇭🇺 Magyar](README-HU.md) &nbsp;|&nbsp; [🇵🇹 Português](README-PT.md)

---

# 🚂 Open Source Model Railway Electronics

Velkommen! Denne organisasjonen inneholder åpen kildekode PCB-er og dekodermoduler for automatisering av modelljernbane.  
Alt her er fullt reproduserbart — alle design, firmware og dokumentasjon er fritt tilgjengelig.

Nedenfor finner du PCB-design og programvare for sporskiftemotorer, DCC solenoid-dekodere, DCC servo-dekodere, S88n beleggstilbakemeldingsmoduler, LED-belysningsstriper, relé-moduler, analoge anleggsstyrings-paneler og mer.

---

# 📘 Guider og forklaringer

Bakgrunnsstoff for å forstå elektronikken og konseptene som brukes i disse prosjektene:

- [Sporskifter og froger](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Points_and_frogs/points_and_frogs-EN.md)
- [Vendeslyngeproblemet](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/turning_loop_problem/turning_loop_problem-EN.md)
- [Automatisering av et anlegg](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/automize_a_layout/automize_a_layout-EN.md)

<br>

---

# 🛠️ Bygg og bestill dine egne PCB-er

Trinn-for-trinn-guider for nedlasting av filer, plassering av bestillinger hos JLCPCB og flashings av firmware:

- [Bestill et nakent PCB](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_bare_PCB/Ordering_bare_PCB-EN.md)
- [Bestill et SMT-montert PCB](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_SMT_ASSEMBLED_PCB/Ordering_Assembled_PCBs_JLCPCB-EN.md)
- [Programmer din OS DCC-dekoder](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Program_OS-DCC-Decoder/Program_OS-DCC-Decoder-EN.md)

<br>

---

# 💡 Lag dine egne PCB-veiledninger

- [Lag din egen tilpassede LED-stripe](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_custom_LED_strip/makeYourOwnCustomLedStrip-EN.md)
- [Lag din egen Wire Split](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_split/make_your_own_wire_split-EN.md)
- *(kommer snart)* Lag din egen Solder Sleeper
- *(kommer snart)* Lag ditt eget betjeningspanel

<br>

---

# 🔀 DCC-tilbehørsdekodere

---

## OS-Duplex

OS-Duplex er en dobbel DCC-tilbehørsdekoder utviklet for alle typer sporskiftedrev — fra tradisjonelle dobbeltspolesolenoider til motordrevne sporskiftemotorer og relé-moduler for frog-polarisering.

Hver av de to sidene (A og B) kan operere uavhengig eller kobles sammen. Hver side kan fungere som to uavhengige enkelutganger (hver med sin egen DCC-adresse), eller som én kombinert dobbeltutgang for et dobbeltspoleanlegg eller motordrevet sporskifte.

Valgfrie reléfester muliggjør frog-polarisering eller drift av ekstra spoler og motorer. Duplex kan også drive et 4-lampe signal med ethvert mulig aspekt.

![Forhåndsvisning]((https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/docs/image.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/docs/Manual-NO.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex) &nbsp;|&nbsp; 📦 [Siste utgivelse](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/releases/latest)

<br>

---

## OS-Duplex-Servo

OS-Duplex-Servo er en variant av OS-Duplex med lagt til støtte for **servomotorutganger** (standard 3-pins PWM). Den er ideell for servodrevne sporskiftemotorer, og beholder den samme tokanals-arkitekturen, relé-utvidelsesalternativer og signalstyringskapasiteter som basis OS-Duplex.

![Forhåndsvisning](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/hardware/OS-Duplex.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/docs/Manual-NO.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo) &nbsp;|&nbsp; 📦 [Siste utgivelse](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/releases/latest)

<br>

---

## OS-Servo-Decoder-8

OS-Servo-Decoder-8 er en enkel og robust DCC-tilbehørsdekoder utviklet for å drive opptil 8 servomotorer. Den støtter fleksibel konfigurasjon via DCC-kommandoer eller fysiske knapper, valgfrie relé-utvidelsesmoduler for frog-polarisering, og direkte styring ved hjelp av DCC-tilbehørskommandoer eller lokomotivfunksjoner (F1–F8) — ingen datamaskin eller CV-programmerer nødvendig.

![Forhåndsvisning](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/hardware/OS-Servo-Decoder-8.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/docs/Manual-NO.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8) &nbsp;|&nbsp; 📦 [Siste utgivelse](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/releases/latest)

<br>

---

## OS-Solenoid-Decoder

OS-Solenoid-Decoder er en kraftig DCC-tilbehørsdekoder for kobling av sporskifter (sporskiftemotorer), reléer, avkoplere og andre solenoidbaserte enheter. Den håndterer opptil 5 A og støtter nesten alle typer sporskiftemotorer. Den er også kompatibel med OS relé-moduler for fullstendig electrofrog- og unifrog-frog-polarisering.

Viktige egenskaper:

- Opptil 8 duale utganger for dobbeltspolesporskiftemotorer
- Flere utgangsmoduser: Dobbel puls, Enkel puls, Dobbel stasjonær, Enkel stasjonær, Electrofrog
- Konfigurerbar via DCC-tilbehørskommandoer — ingen datamaskin nødvendig
- Valgfri CDU-modul-støtte
- Utvidbar med relé- og transistorkort

![Forhåndsvisning](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/hardware/OS-Solenoid-Decoder.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/docs/Manual-NO.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder) &nbsp;|&nbsp; 📦 [Siste utgivelse](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/releases/latest)

<br>

---

# 📡 Tilbakemelding og beleggdeteksjon

---

## OS-S88n (CS / GND / OPTO)

OS-S88n-modulene gir S88n-tilbakemelding for DCC-modelljernbaner, og muliggjør sanntidsovervåking av blokkbelegg og anleggshendelser. Data sendes til sentralstasjonen din eller PC-basert programvare (iTrain, Rocrail, Windigipet og andre).

Tre varianter er tilgjengelige:

- **OS-S88n GND** — jordkontakt-deteksjon, ideelt for 3-skinne-anlegg (Märklin-stil)
- **OS-S88n CS** — strømsansedeteksjon, egnet for 2-skinne- og 3-skinne-anlegg
- **OS-S88n OPTO** — optoisolerte innganger for IR-detektorer, Hall-sensorer og andre eksterne sensorer

Alle versjoner kan knyttes i kjede via RJ-45 og støtter opptil 31 moduler i én enkelt kjede.

![Forhåndsvisning](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/all.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/Manual-NO.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n) &nbsp;|&nbsp; 📦 [Siste utgivelse](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/releases/latest)

<br>

---

# 🔌 Relé-moduler

---

## OS-relays

OS-relays-modulene er inntrekkbare relé-kort utviklet for å fungere side om side med OS DCC-dekodere. To typer er tilgjengelige:

- **OS-General-Purpose-Relay** — dobbelt monostabilt relé med COM/NO/NC-kontakter; egnet for frog-polarisering (electrofrog og unifrog) og generell tilbehørskobling
- **OS-Latching-Relay** — enkelt bistabilt relé som holder posisjonen uten kontinuerlig strøm; ideelt for unifrog-polarisering koblet parallelt med solenoiden

Begge typer er tilgjengelige i THT- og SMD-versjoner og kan bestilles som avbryterbare paneler.

![Forhåndsvisning](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/all.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/Manual-NO.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays) &nbsp;|&nbsp; 📦 [Siste utgivelse](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/releases/latest)

<br>

---

# 💡 Belysning

---

## OS-Lux-One

OS-Lux-One er et modulært LED-belysningsstrimmel for digitalt rullende materiell til modelljernbane. Det erstatter flere vognstriper i faste lengder med én universell versjon som kan klippes til riktig størrelse og gjenbrukes. Hvert avsnitt har sin egen innebygde strømregulator for stabil lysstyrke uavhengig av sporsspenning, og stripen fungerer direkte fra DCC, MM eller mfx sporstrøm. Egnet for både H0 og N-skala.

![Forhåndsvisning](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/hardware/OS-Lux-One/OS-Lux-One.pdf?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/docs/Manual-NO.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One) &nbsp;|&nbsp; 📦 [Siste utgivelse](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/releases/latest)

<br>

---

# 🎛️ Analog anleggsstyring

---

## Analog-Layout-Control

En rekke analoge anleggsstyringsmoduler utviklet som modulære byggesteiner for egendefinerte betjeningspaneler. Alle moduler bruker standard JST-koblinger for enkel kabling og samvirke. Kombiner dem for å bygge alt fra enkel togfører-kontrolskobling til fullstendig ruteinnstilling via diodematriser.

Moduler i dette sortimentet inkluderer:

- CAB-kontrolbryter — tildeler sporpartier til Cab A eller Cab B, med LED-tilbakemelding
- Sporskiftemotorbryter — snur polaritet for 2-leder sporskiftemotorer
- Solenoidbryter med tilbakemelding — momentan styring for dobbeltspoledrev
- Selvholdende relé — bistabilt relé for frog-polarisering eller partikoblling
- Diodematrise — ruteinnstillingskort for aktivering av flere sporskifter med én enkelt knapp

![Forhåndsvisning](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/hardware/Analog-Layout-Control.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/docs/Manual-NO.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control) &nbsp;|&nbsp; 📦 [Siste utgivelse](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/releases/latest)

<br>

---

## Vendeslyngemodulene

Vendeslyngemodulene håndterer automatisk polaritetsomvenningen som trengs når et tog kjører inn i eller ut av en vendeslynge (wye, ballongspor eller svingskive). Modulen oppdager kortslutningen forårsaket av et omvendt lokomotiv og korrigerer polariteten automatisk, uten manuell inngripen.

![Forhåndsvisning](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/blob/main/hardware/turning-loop-modules.png?raw=true)

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules) &nbsp;|&nbsp; 📦 [Siste utgivelse](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/releases/latest)

<br>

---

# 🔩 Passive komponenter og kabling

---

## Wire-Splits

Wire-Split PCB-er er kompakte passive fordelingskort for å dele én inngangsledning ryddig opp i flere utganger. De gjør det enkelt å fordele DCC sporstrøm eller felles ledninger til mange punkter på anlegget ditt uten rotete kablingspakker.

![Forhåndsvisning](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/blob/main/hardware/Wire-Splits.png?raw=true)

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits) &nbsp;|&nbsp; 📦 [Siste utgivelse](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/releases/latest)

<br>

---

## Solder-sleepers

Solder Sleepers er PCB-baserte svellerunder (ties) utviklet for å limes inn i sporsengen. PCB-svelleren lar deg lodde skinnene direkte på kortet for en pålitelig elektrisk og mekanisk tilkobling — ideelt for egenbygde spor, dioramaarbeid eller overalt der et fast loddepunkt er å foretrekke fremfor klemmer.

![Forhåndsvisning](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/blob/main/docs/Solder-sleepers.png?raw=true)

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers) &nbsp;|&nbsp; 📦 [Siste utgivelse](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/releases/latest)

<br>

---

# 🖥️ Programvare

---

## OS-Software-Tool

OS-software-tool er et PC-verktøy for konfigurering og testing av OS DCC-dekodere. Det gir et grafisk grensesnitt for oppgaver som ellers ville kreve manuelle DCC-kommandosekvenser.

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-software-tool)

<br>

---
