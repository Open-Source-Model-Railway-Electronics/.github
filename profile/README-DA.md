> 🌐 **Sprog:** &nbsp; [🇬🇧 English](README.md) &nbsp;|&nbsp; [🇩🇪 Deutsch](README-DE.md) &nbsp;|&nbsp; [🇫🇷 Français](README-FR.md) &nbsp;|&nbsp; [🇳🇱 Nederlands](README-NL.md) &nbsp;|&nbsp; [🇪🇸 Español](README-ES.md) &nbsp;|&nbsp; [🇮🇹 Italiano](README-IT.md) &nbsp;|&nbsp; [🇵🇱 Polski](README-PL.md) &nbsp;|&nbsp; [🇨🇿 Čeština](README-CS.md) &nbsp;|&nbsp; 🇩🇰 Dansk &nbsp;|&nbsp; [🇳🇴 Norsk](README-NO.md) &nbsp;|&nbsp; [🇸🇪 Svenska](README-SV.md) &nbsp;|&nbsp; [🇭🇺 Magyar](README-HU.md) &nbsp;|&nbsp; [🇵🇹 Português](README-PT.md)

---

# 🚂 Open Source Model Railway Electronics

Velkommen! Denne organisation indeholder open source PCB'er og dekodermoduler til automatisering af modeljernbaner.  
Alt hér er fuldt reproducerbart — alle designs, firmware og dokumentation er frit tilgængeligt.

Nedenfor finder du PCB-designs og software til sporskiftemotorer, DCC-solenoid-dekodere, DCC-servo-dekodere, S88n-blokmeldermoduler, LED-belysningsstrimler, relæmoduler, analoge layoutstyrepaneler og meget mere.

---

# 📘 Vejledninger og forklaringer

Baggrundslæsning til forståelse af elektronik og koncepter brugt på tværs af disse projekter:

- [Sporskifter og hjertestykker](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Points_and_frogs/points_and_frogs-EN.md)
- [Venderingsproblematikken](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/turning_loop_problem/turning_loop_problem-EN.md)
- [Automatisering af et anlæg](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/automize_a_layout/automize_a_layout-EN.md)

<br>

---

# 🛠️ Byg og bestil dine egne PCB'er

Trin-for-trin-vejledninger til download af filer, afgivelse af bestillinger hos JLCPCB og flashing af firmware:

- [Bestil et bare PCB](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_bare_PCB/Ordering_bare_PCB-EN.md)
- [Bestil et SMT-monteret PCB](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_SMT_ASSEMBLED_PCB/Ordering_Assembled_PCBs_JLCPCB-EN.md)
- [Programmer din OS DCC-dekoder](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Program_OS-DCC-Decoder/Program_OS-DCC-Decoder-EN.md)

<br>

---

# 💡 Selvbyg PCB-vejledninger

- [Lav din egen tilpassede LED-strimmel](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_custom_LED_strip/makeYourOwnCustomLedStrip-EN.md)
- [Lav din egen Wire-Split](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_split/make_your_own_wire_split-EN.md)
- *(kommer snart)* Lav din egen Solder-sleeper
- *(kommer snart)* Lav dit eget betjeningspanel

<br>

---

# 🔀 DCC-tilbehørsdekodere

---

## OS-Duplex

OS-Duplex er en dobbelt DCC-tilbehørsdekoder designet til alle typer sporskiftedrev — fra traditionelle toviklings-solenoider til motordrevne sporskiftemotorer og relæmoduler til hjertestykke-polarisering.

Hver af de to sider (A og B) kan fungere uafhængigt eller være koblet sammen. Hver side kan fungere som to uafhængige enkeltudgange (hver med sin egen DCC-adresse) eller som én kombineret dobbeltudgang til et toviklings- eller motordrevssporskifte.

Valgfrie relæstik muliggør hjertestykke-polarisering eller drift af ekstra spoler og motorer. OS-Duplex kan også drive et 4-lampe-signal med ethvert muligt aspekt.

![Forhåndsvisning](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/docs/image.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/docs/Manual-DA.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex) &nbsp;|&nbsp; 📦 [Seneste udgivelse](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/releases/latest)

<br>

---

## OS-Duplex-Servo

OS-Duplex-Servo er en variant af OS-Duplex med tilføjet understøttelse af **servomotorudgange** (standard 3-pin PWM). Den er ideel til servodrevne sporskiftemotorer, mens den bevarer den samme to-kanals-arkitektur, relæudvidelsesmuligheder og signalstyringsfunktioner som basis-OS-Duplex.

![Forhåndsvisning](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/hardware/OS-Duplex.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/docs/Manual-DA.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo) &nbsp;|&nbsp; 📦 [Seneste udgivelse](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/releases/latest)

<br>

---

## OS-Servo-Decoder-8

OS-Servo-Decoder-8 er en enkel og robust DCC-tilbehørsdekoder designet til at drive op til 8 servomotorer. Den understøtter fleksibel konfiguration via DCC-kommandoer eller fysiske knapper, valgfrie relæudvidelsesmoduler til hjertestykke-polarisering og direkte styring ved hjælp af DCC-tilbehørskommandoer eller lokomotivfunktioner (F1–F8) — ingen computer eller CV-programmer påkrævet.

![Forhåndsvisning](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/hardware/OS-Servo-Decoder-8.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/docs/Manual-DA.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8) &nbsp;|&nbsp; 📦 [Seneste udgivelse](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/releases/latest)

<br>

---

## OS-Solenoid-Decoder

OS-Solenoid-Decoder er en kraftfuld DCC-tilbehørsdekoder til skift af sporskifter (sporskiftemotorer), relæer, afkoblere og andre solenoid-drevne enheder. Den håndterer op til 5 A og understøtter næsten enhver type sporskiftemotor. Den er også kompatibel med OS-relæmoduler til fuld Electrofrog- og Unifrog-hjertestykke-polarisering.

Nøgleegenskaber:

- Op til 8 dobbeltudgange til toviklings-sporskiftemotorer
- Flere udgangstyper: Dobbelt puls, Enkelt puls, Dobbelt stabil, Enkelt stabil, Electrofrog
- Konfigurerbar via DCC-tilbehørskommandoer — ingen computer nødvendig
- Valgfri CDU-modulunderstøttelse
- Udvidelig med relæ- og transistorkort

![Forhåndsvisning](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/hardware/OS-Solenoid-Decoder.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/docs/Manual-DA.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder) &nbsp;|&nbsp; 📦 [Seneste udgivelse](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/releases/latest)

<br>

---

# 📡 Tilbagemelding og blokdetektion

---

## OS-S88n (CS / GND / OPTO)

OS-S88n-modulerne leverer S88n-tilbagemelding til DCC-modeljernbaner, hvilket muliggør realtidsovervågning af blokokkupering og anlægshændelser. Data sendes til din kommandostation eller PC-baserede software (iTrain, Rocrail, Windigipet m.fl.).

Tre varianter er tilgængelige:

- **OS-S88n GND** — jordkontaktdetektion, ideel til 3-skinne (Märklin-stil) anlæg
- **OS-S88n CS** — strømmålingsdetektion, velegnet til 2-skinne og 3-skinne anlæg
- **OS-S88n OPTO** — optoisolerede indgange til IR-detektorer, Hall-sensorer og andre eksterne sensorer

Alle versioner kan sammenkædes via RJ-45 og understøtter op til 31 moduler i en enkelt kæde.

![Forhåndsvisning](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/all.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/Manual-DA.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n) &nbsp;|&nbsp; 📦 [Seneste udgivelse](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/releases/latest)

<br>

---

# 🔌 Relæmoduler

---

## OS-relays

OS-relæmodulerne er plug-in relækort designet til at fungere sammen med OS DCC-dekodere. To typer er tilgængelige:

- **OS-General-Purpose-Relay** — dobbelt monostabilt relæ med COM/NO/NC-kontakter; velegnet til hjertestykke-polarisering (Electrofrog og Unifrog) og generel tilbehørsskift
- **OS-Latching-Relay** — enkelt bistabilt relæ, der holder sin position uden konstant strøm; ideelt til Unifrog-polarisering kabelforbundet parallelt med solenoiden

Begge typer fås i THT- og SMD-versioner og kan bestilles som adskillelige paneler.

![Forhåndsvisning](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/all.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/Manual-DA.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays) &nbsp;|&nbsp; 📦 [Seneste udgivelse](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/releases/latest)

<br>

---

# 💡 Belysning

---

## OS-Lux-One

OS-Lux-One er et modulært LED-belysningsstrimmel til digitalt modeljernbanerullende materiel. Det erstatter flere belysningsstrimler i fast længde med én universel version, der kan klippes til størrelse og genbruges. Hvert segment har sin egen indbyggede strømregulator for stabil lysstyrke uanset skinnesænkning, og strimlen fungerer direkte fra DCC-, MM- eller mfx-skinnestrøm. Velegnet til både H0 og N skala.

![Forhåndsvisning](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/hardware/OS-Lux-One/OS-Lux-One.pdf?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/docs/Manual-DA.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One) &nbsp;|&nbsp; 📦 [Seneste udgivelse](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/releases/latest)

<br>

---

# 🎛️ Analog layoutstyring

---

## Analog-Layout-Control

Et sortiment af analoge layoutstyremodulere designet som modulære byggeklodser til tilpassede betjeningspaneler. Alle moduler bruger standard JST-stik til nem kabeltrækning og indbyrdes kompatibilitet. Kombiner dem til at bygge alt fra simpel cab-styringsafbrydning til fuld rutesætning via diodematricer.

Moduler i dette sortiment inkluderer:

- CAB Control Switch — tildeler sporstrækninger til Cab A eller Cab B med LED-tilbagemelding
- Point Motor Switch — vender polariteten til 2-trådede sporskiftemotorer
- Solenoid Point Switch med tilbagemelding — momentan styring til toviklingsmotor-drev
- Latching Relay — bistabilt relæ til hjertestykke-polarisering eller sektionsskift
- Diodematrix — rutesætningskort til aktivering af flere sporskifter med et enkelt knaptryk

![Forhåndsvisning](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/hardware/Analog-Layout-Control.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/docs/Manual-DA.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control) &nbsp;|&nbsp; 📦 [Seneste udgivelse](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/releases/latest)

<br>

---

## Venderingsmoduler

Venderingsmodulerne håndterer automatisk den polaritetsomvending, der er nødvendig, når et tog kører ind i eller ud af en venderingssløjfe (Y-spor, ballonsløjfe eller drejeskive). Modulet registrerer kortslutningen forårsaget af et vendt lokomotiv og korrigerer polariteten automatisk uden manuel indgriben.

![Forhåndsvisning](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/blob/main/hardware/turning-loop-modules.png?raw=true)

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules) &nbsp;|&nbsp; 📦 [Seneste udgivelse](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/releases/latest)

<br>

---

# 🔩 Passive komponenter og kabeltrækning

---

## Wire-Splits

Wire-Split PCB'er er kompakte passive fordelingskort til ren opdeling af én indgangsledning i flere udgange. De gør det nemt at distribuere DCC-skinnestrøm eller fælles ledninger til mange punkter på dit anlæg uden rodet samlingsbundter.

![Forhåndsvisning](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/blob/main/hardware/Wire-Splits.png?raw=true)

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits) &nbsp;|&nbsp; 📦 [Seneste udgivelse](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/releases/latest)

<br>

---

## Solder Sleepers

Solder Sleepers er PCB-baserede skinneslæbere (sveller) designet til at blive klæbet fast i sporlejet. PCB-svelleren giver dig mulighed for at lodde skinnen direkte på kortet for en pålidelig elektrisk og mekanisk forbindelse — ideel til hjemmebygget spor, dioramaarbejde eller overalt, hvor en fast loddeskinneforbindelse foretrækkes frem for klemmer.

![Forhåndsvisning](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/blob/main/docs/Solder-sleepers.png?raw=true)

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers) &nbsp;|&nbsp; 📦 [Seneste udgivelse](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/releases/latest)

<br>

---

# 🖥️ Software

---

## OS-Software-Tool

OS-Software-Tool er et PC-værktøj til konfiguration og test af OS DCC-dekodere. Det leverer en grafisk grænseflade til opgaver, der ellers ville kræve manuelle DCC-kommandosekvenser.

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-software-tool)

<br>

---
