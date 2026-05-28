> 🌐 **Jazyk:** &nbsp; [🇬🇧 English](README.md) &nbsp;|&nbsp; [🇩🇪 Deutsch](README-DE.md) &nbsp;|&nbsp; [🇫🇷 Français](README-FR.md) &nbsp;|&nbsp; [🇳🇱 Nederlands](README-NL.md) &nbsp;|&nbsp; [🇪🇸 Español](README-ES.md) &nbsp;|&nbsp; [🇮🇹 Italiano](README-IT.md) &nbsp;|&nbsp; [🇵🇱 Polski](README-PL.md) &nbsp;|&nbsp; 🇨🇿 Čeština &nbsp;|&nbsp; [🇩🇰 Dansk](README-DA.md) &nbsp;|&nbsp; [🇳🇴 Norsk](README-NO.md) &nbsp;|&nbsp; [🇸🇪 Svenska](README-SV.md) &nbsp;|&nbsp; [🇭🇺 Magyar](README-HU.md) &nbsp;|&nbsp; [🇵🇹 Português](README-PT.md)

---

# 🚂 Open Source Model Railway Electronics

Vítejte! Tato organizace obsahuje open-source PCB a dekodér moduly pro automatizaci modelové železnice.  
Vše zde je plně reprodukovatelné — všechny návrhy, firmware a dokumentace jsou volně dostupné.

Níže najdete návrhy PCB a software pro pohony výhybek, DCC solenoidové dekodéry, DCC servo dekodéry, S88n moduly pro zpětnou vazbu obsazenosti, LED osvětlovací pásky, relé moduly, analogové ovládací panely kolejiště a další.

---

# 📘 Průvodci a vysvětlení

Podkladové čtení pro pochopení elektroniky a konceptů používaných v těchto projektech:

- [Výhybky a srdcovky](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Points_and_frogs/points_and_frogs-EN.md)
- [Problém otočné smyčky](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/turning_loop_problem/turning_loop_problem-EN.md)
- [Automatizace kolejiště](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/automize_a_layout/automize_a_layout-EN.md)

<br>

---

# 🛠️ Sestavte a objednejte si vlastní PCB

Podrobné návody pro stahování souborů, zadávání objednávek u JLCPCB a nahrávání firmware:

- [Objednat holou PCB](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_bare_PCB/Ordering_bare_PCB-EN.md)
- [Objednat PCB osazenou SMT](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_SMT_ASSEMBLED_PCB/Ordering_Assembled_PCBs_JLCPCB-EN.md)
- [Naprogramovat OS DCC dekodér](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Program_OS-DCC-Decoder/Program_OS-DCC-Decoder-EN.md)

<br>

---

# 💡 Tutoriály pro vlastní PCB

- [Vyrobte si vlastní vlastní LED pásek](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_custom_LED_strip/makeYourOwnCustomLedStrip-EN.md)
- [Vyrobte si vlastní rozbočovač vodičů](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_split/make_your_own_wire_split-EN.md)
- *(připravuje se)* Vyrobte si vlastní Solder Sleeper
- *(připravuje se)* Vyrobte si vlastní ovládací panel

<br>

---

# 🔀 DCC příslušenské dekodéry

---

## OS-Duplex

OS-Duplex je dvojitý DCC příslušenský dekodér navržený pro všechny typy pohonů výhybek — od tradičních dvousmyčkových solenoidů po motoricky poháněné pohony výhybek a relé moduly pro polarizaci srdcovky.

Každá ze dvou stran (A a B) může pracovat samostatně nebo být propojena dohromady. Každá strana může fungovat jako dva nezávislé samostatné výstupy (každý s vlastní DCC adresou), nebo jako jeden kombinovaný dvojitý výstup pro výhybku s dvousmyčkovým nebo motorickým pohonem.

Volitelné zásuvky pro relé umožňují polarizaci srdcovky nebo pohon dalších cívek a motorů. OS-Duplex může také pohánět 4-lampové návěstidlo se všemi možnými aspekty.

![Náhled](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/docs/image.png?raw=true)

📖 [Manuál](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/docs/Manual-CS.md) &nbsp;|&nbsp; 🔗 [Repozitář](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex) &nbsp;|&nbsp; 📦 [Nejnovější vydání](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/releases/latest)

<br>

---

## OS-Duplex-Servo

OS-Duplex-Servo je varianta OS-Duplex s přidanou podporou **výstupů pro servomotory** (standardní 3-pinový PWM). Je ideální pro servem poháněné pohony výhybek při zachování stejné dvoukanálové architektury, možností rozšíření relé a schopností ovládání návěstidel jako základní OS-Duplex.

![Náhled](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/hardware/OS-Duplex.png?raw=true)

📖 [Manuál](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/docs/Manual-CS.md) &nbsp;|&nbsp; 🔗 [Repozitář](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo) &nbsp;|&nbsp; 📦 [Nejnovější vydání](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/releases/latest)

<br>

---

## OS-Servo-Decoder-8

OS-Servo-Decoder-8 je jednoduchý a robustní DCC příslušenský dekodér navržený pro pohon až 8 servomotorů. Podporuje flexibilní konfiguraci prostřednictvím DCC příkazů nebo fyzických tlačítek, volitelné rozšiřující relé moduly pro polarizaci srdcovky a přímé ovládání pomocí DCC příslušenských příkazů nebo lokomotivních funkcí (F1–F8) — není potřeba počítač ani programátor CV.

![Náhled](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/hardware/OS-Servo-Decoder-8.png?raw=true)

📖 [Manuál](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/docs/Manual-CS.md) &nbsp;|&nbsp; 🔗 [Repozitář](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8) &nbsp;|&nbsp; 📦 [Nejnovější vydání](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/releases/latest)

<br>

---

## OS-Solenoid-Decoder

OS-Solenoid-Decoder je výkonný DCC příslušenský dekodér pro přepínání výhybek (pohony výhybek), relé, odpojovačů a dalších solenoidem řízených zařízení. Zvládá až 5 A a podporuje téměř jakýkoli typ pohonu výhybky. Je také kompatibilní s OS relé moduly pro plnou polarizaci srdcovky electrofrog i unifrog.

Klíčové vlastnosti:

- Až 8 dvojitých výstupů pro dvousmyčkové pohony výhybek
- Více výstupních režimů: Dvojitý impulz, Jednoduchý impulz, Dvojitý trvalý, Jednoduchý trvalý, Electrofrog
- Konfigurovatelný prostřednictvím DCC příslušenských příkazů — není potřeba počítač
- Volitelná podpora modulu CDU
- Rozšiřitelné relé a tranzistorovými deskami

![Náhled](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/hardware/OS-Solenoid-Decoder.png?raw=true)

📖 [Manuál](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/docs/Manual-CS.md) &nbsp;|&nbsp; 🔗 [Repozitář](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder) &nbsp;|&nbsp; 📦 [Nejnovější vydání](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/releases/latest)

<br>

---

# 📡 Zpětná vazba a detekce obsazenosti

---

## OS-S88n (CS / GND / OPTO)

Moduly OS-S88n poskytují S88n zpětnou vazbu pro DCC modelové železnice, umožňují sledování obsazení bloků a událostí na kolejišti v reálném čase. Data jsou odesílána do vaší příkazové stanice nebo počítačového softwaru (iTrain, Rocrail, Windigipet a další).

K dispozici jsou tři varianty:

- **OS-S88n GND** — detekce uzemnění, ideální pro kolejiště se 3 kolejnicemi (ve stylu Märklin)
- **OS-S88n CS** — detekce proudu, vhodná pro kolejiště se 2 i 3 kolejnicemi
- **OS-S88n OPTO** — opticky izolované vstupy pro IR detektory, Hallovy senzory a další externí senzory

Všechny verze jsou řetězitelné přes RJ-45 a podporují až 31 modulů v jednom řetězci.

![Náhled](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/all.png?raw=true)

📖 [Manuál](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/Manual-CS.md) &nbsp;|&nbsp; 🔗 [Repozitář](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n) &nbsp;|&nbsp; 📦 [Nejnovější vydání](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/releases/latest)

<br>

---

# 🔌 Relé moduly

---

## OS-relays

OS-relay moduly jsou zásuvné relé desky navržené pro spolupráci s OS DCC dekodéry. Jsou dostupné dva typy:

- **OS-General-Purpose-Relay** — dvojité monostabilní relé s kontakty COM/NO/NC; vhodné pro polarizaci srdcovky (electrofrog i unifrog) a obecné přepínání příslušenství
- **OS-Latching-Relay** — jednoduché bistabilní relé, které drží svou polohu bez trvalého napájení; ideální pro polarizaci unifrog zapojenou paralelně se solenoidem

Oba typy jsou dostupné ve verzích THT a SMD a lze je objednávat jako lomitelné panely.

![Náhled](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/all.png?raw=true)

📖 [Manuál](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/Manual-CS.md) &nbsp;|&nbsp; 🔗 [Repozitář](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays) &nbsp;|&nbsp; 📦 [Nejnovější vydání](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/releases/latest)

<br>

---

# 💡 Osvětlení

---

## OS-Lux-One

OS-Lux-One je modulární LED osvětlovací pásek pro digitální kolejová vozidla modelové železnice. Nahrazuje více osvětlovacích sad pevné délky pro vozy jednou univerzální verzí, kterou lze přizpůsobit střihem a znovu použít. Každá sekce má vlastní vestavěný regulátor proudu pro stálý jas bez ohledu na kolejové napětí a pásek pracuje přímo z kolejového napájení DCC, MM nebo mfx. Vhodný pro měřítka H0 i N.

![Náhled](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/hardware/OS-Lux-One/OS-Lux-One.pdf?raw=true)

📖 [Manuál](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/docs/Manual-CS.md) &nbsp;|&nbsp; 🔗 [Repozitář](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One) &nbsp;|&nbsp; 📦 [Nejnovější vydání](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/releases/latest)

<br>

---

# 🎛️ Analogové řízení kolejiště

---

## Analog-Layout-Control

Řada modulů pro analogové řízení kolejiště navržených jako modulární stavební bloky pro vlastní ovládací panely. Všechny moduly používají standardní JST konektory pro snadné zapojení a vzájemnou kompatibilitu. Kombinujte je k vytvoření čehokoli od jednoduchého přepínání kabin až po plné nastavení tras pomocí diodových matic.

Moduly v této řadě zahrnují:

- CAB Control Switch — přiřazuje kolejové úseky k Cab A nebo Cab B, s LED zpětnou vazbou
- Point Motor Switch — obrací polaritu pro dvouvodičové pohony výhybek
- Solenoid Point Switch se zpětnou vazbou — momentální ovládání pro dvousmyčkové pohony
- Latching Relay — bistabilní relé pro polarizaci srdcovky nebo přepínání úseků
- Diodová matice — deska pro nastavení tras pro aktivaci více výhybek jediným tlačítkem

![Náhled](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/hardware/Analog-Layout-Control.png?raw=true)

📖 [Manuál](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/docs/Manual-CS.md) &nbsp;|&nbsp; 🔗 [Repozitář](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control) &nbsp;|&nbsp; 📦 [Nejnovější vydání](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/releases/latest)

<br>

---

## Moduly otočné smyčky

Moduly otočné smyčky automaticky řeší obrácení polarity potřebné při vjezdu nebo výjezdu vlaku z otočné smyčky (výhybkový trojúhelník, balónová smyčka nebo točna). Modul detekuje zkrat způsobený otočenou lokomotivou a automaticky opraví polaritu bez jakéhokoli ručního zásahu.

![Náhled](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/blob/main/hardware/turning-loop-modules.png?raw=true)

🔗 [Repozitář](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules) &nbsp;|&nbsp; 📦 [Nejnovější vydání](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/releases/latest)

<br>

---

# 🔩 Pasivní součástky a kabeláž

---

## Wire-Splits

Wire-Split PCB jsou kompaktní pasivní distribuční desky pro čisté rozdělení jednoho vstupního vodiče do více výstupů. Usnadňují distribuci kolejového napájení DCC nebo společných vodičů do mnoha míst na kolejišti bez nepořádných svazků spojů.

![Náhled](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/blob/main/hardware/Wire-Splits.png?raw=true)

🔗 [Repozitář](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits) &nbsp;|&nbsp; 📦 [Nejnovější vydání](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/releases/latest)

<br>

---

## Solder Sleepers

Solder Sleepers jsou PCB pražce navržené k přilepení do kolejového lože. PCB pražec umožňuje přímé přípájení kolejnice na desku pro spolehlivé elektrické a mechanické spojení — ideální pro ručně stavěnou trať, dioráma nebo kdekoli, kde je pevný pájecí spoj upřednostňován před sponami.

![Náhled](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/blob/main/docs/Solder-sleepers.png?raw=true)

🔗 [Repozitář](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers) &nbsp;|&nbsp; 📦 [Nejnovější vydání](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/releases/latest)

<br>

---

# 🖥️ Software

---

## OS-Software-Tool

OS-Software-Tool je PC nástroj pro konfiguraci a testování OS DCC dekodérů. Poskytuje grafické rozhraní pro úkoly, které by jinak vyžadovaly ruční sekvence DCC příkazů.

🔗 [Repozitář](https://github.com/Open-Source-Model-Railway-Electronics/OS-software-tool)

<br>

---
