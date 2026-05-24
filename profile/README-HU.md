> 🌐 **Nyelv:** &nbsp; [🇬🇧 English](README.md) &nbsp;|&nbsp; [🇩🇪 Deutsch](README-DE.md) &nbsp;|&nbsp; [🇫🇷 Français](README-FR.md) &nbsp;|&nbsp; [🇳🇱 Nederlands](README-NL.md) &nbsp;|&nbsp; [🇪🇸 Español](README-ES.md) &nbsp;|&nbsp; [🇮🇹 Italiano](README-IT.md) &nbsp;|&nbsp; [🇵🇱 Polski](README-PL.md) &nbsp;|&nbsp; [🇨🇿 Čeština](README-CS.md) &nbsp;|&nbsp; [🇩🇰 Dansk](README-DA.md) &nbsp;|&nbsp; [🇳🇴 Norsk](README-NO.md) &nbsp;|&nbsp; [🇸🇪 Svenska](README-SV.md) &nbsp;|&nbsp; 🇭🇺 Magyar &nbsp;|&nbsp; [🇵🇹 Português](README-PT.md)

---

# 🚂 Open Source Model Railway Electronics

Üdvözlünk! Ez a szervezet nyílt forráskódú PCB-ket és dekóder modulokat tartalmaz a modellvasút-automatizáláshoz.  
Minden itt megtalálható teljes mértékben reprodukálható — az összes terv, firmware és dokumentáció szabadon elérhető.

Az alábbiakban PCB-terveket és szoftvereket találsz kitérőmotorokhoz, DCC szolonoid dekóderekhez, DCC szervódekóderekhez, S88n foglaltság-visszajelző modulokhoz, LED világítószalagokhoz, relés modulokhoz, analóg pályairányító panelekhez és egyebekhez.

---

# 📘 Útmutatók és Magyarázatok

Háttérolvasmányok a projektekben használt elektronika és fogalmak megértéséhez:

- [Kitérők és száruk](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Points_and_frogs/points_and_frogs-EN.md)
- [A fordítókör problémája](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/turning_loop_problem/turning_loop_problem-EN.md)
- [Pálya automatizálása](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/automize_a_layout/automize_a_layout-EN.md)

<br>

---

# 🛠️ Saját PCB-k Építése és Rendelése

Lépésről lépésre szóló útmutatók a fájlok letöltéséhez, JLCPCB-rendelések leadásához és a firmware feltöltéséhez:

- [Csupasz PCB rendelése](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_bare_PCB/Ordering_bare_PCB-EN.md)
- [SMT összeszereléssel rendelendő PCB](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_SMT_ASSEMBLED_PCB/Ordering_Assembled_PCBs_JLCPCB-EN.md)
- [OS DCC Dekóder programozása](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Program_OS-DCC-Decoder/Program_OS-DCC-Decoder-EN.md)

<br>

---

# 💡 Saját PCB Készítési Oktatóanyagok

- [Saját egyedi LED szalag készítése](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_custom_LED_strip/makeYourOwnCustomLedStrip-EN.md)
- [Saját Wire Split készítése](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_split/make_your_own_wire_split-EN.md)
- *(hamarosan)* Saját Solder Sleeper készítése
- *(hamarosan)* Saját vezérlőpult készítése

<br>

---

# 🔀 DCC Kiegészítő Dekóderek

---

## OS-Duplex

Az OS-Duplex egy kettős DCC kiegészítő dekóder, amelyet minden típusú kitérőmeghajtóhoz terveztek — a hagyományos ikertekercsű szolonoidoktól a motoros kitérőmotorokon át a szárpolarizáló relés modulokig.

Mindkét oldal (A és B) önállóan működhet, vagy összekapcsolható egymással. Mindkét oldal működhet két független egyes kimenetként (mindegyik saját DCC-címmel), vagy egy kombinált dupla kimenetként ikertekercsű vagy motoros kitérőhöz.

Opcionális relés foglalatokkal szárpolarizálás adható hozzá, vagy plusz tekercsek és motorok hajthatók meg. A Duplex minden lehetséges aspektussal 4 lámpás jelzőt is tud vezérelni.

![Előnézet](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/hardware/OS-Duplex.png?raw=true)

📖 [Kézikönyv (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/docs/Manual-HU.md) &nbsp;|&nbsp; 🔗 [Tároló](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex) &nbsp;|&nbsp; 📦 [Legújabb kiadás](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/releases/latest)

<br>

---

## OS-Duplex-Servo

Az OS-Duplex-Servo az OS-Duplex egyik változata, kiegészítve **szervómotor kimenetekkel** (szabványos 3 tűs PWM). Ideális szervóvezérelt kitérőmotorokhoz, miközben megtartja az alap OS-Duplex kettős csatornás felépítését, relébővítési lehetőségeit és jelzővezérlési képességeit.

![Előnézet](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/hardware/OS-Duplex.png?raw=true)

📖 [Kézikönyv (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/docs/Manual-HU.md) &nbsp;|&nbsp; 🔗 [Tároló](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo) &nbsp;|&nbsp; 📦 [Legújabb kiadás](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/releases/latest)

<br>

---

## OS-Servo-Decoder-8

Az OS-Servo-Decoder-8 egy egyszerű és megbízható DCC kiegészítő dekóder, amelyet legfeljebb 8 szervómotor meghajtására terveztek. Rugalmas konfigurációt támogat DCC parancsokon vagy fizikai gombokon keresztül, opcionális relébővítő modulokat a szárpolarizáláshoz, és közvetlen vezérlést DCC kiegészítő parancsokkal vagy mozdony funkciókkal (F1–F8) — számítógép vagy CV programozó nélkül.

![Előnézet](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/hardware/OS-Servo-Decoder-8.png?raw=true)

📖 [Kézikönyv (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/docs/Manual-HU.md) &nbsp;|&nbsp; 🔗 [Tároló](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8) &nbsp;|&nbsp; 📦 [Legújabb kiadás](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/releases/latest)

<br>

---

## OS-Solenoid-Decoder

Az OS-Solenoid-Decoder egy erőteljes DCC kiegészítő dekóder kitérők (kitérőmotorok), relék, lekapcsolók és egyéb szolonoid vezérelt eszközök kapcsolásához. Legfeljebb 5 A-t kezel, és szinte bármilyen típusú kitérőmotort támogat. Kompatibilis az OS relés modulokkal is a teljes electrofrog és unifrog szárpolarizáláshoz.

Főbb jellemzők:

- Legfeljebb 8 dupla kimenet ikertekercsű kitérőmotorokhoz
- Többféle kimeneti mód: Dupla Impulzus, Egyes Impulzus, Dupla Folyamatos, Egyes Folyamatos, Electrofrog
- DCC kiegészítő parancsokkal konfigurálható — nincs szükség számítógépre
- Opcionális CDU modul támogatás
- Relés és tranzisztoros lapokkal bővíthető

![Előnézet](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/hardware/OS-Solenoid-Decoder.png?raw=true)

📖 [Kézikönyv (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/docs/Manual-HU.md) &nbsp;|&nbsp; 🔗 [Tároló](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder) &nbsp;|&nbsp; 📦 [Legújabb kiadás](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/releases/latest)

<br>

---

# 📡 Visszajelzés és Foglaltság-Érzékelés

---

## OS-S88n (CS / GND / OPTO)

Az OS-S88n modulok S88n visszajelzést biztosítanak DCC modellvasutak számára, lehetővé téve a blokk-foglaltság és pályaesemények valós idejű figyelését. Az adatok a parancsvezérlőhöz vagy PC-alapú szoftverhez kerülnek (iTrain, Rocrail, Windigipet és mások).

Három változat elérhető:

- **OS-S88n GND** — földkontaktusos érzékelés, 3 sínes (Märklin-stílusú) pályákhoz ideális
- **OS-S88n CS** — áramfigyeléses érzékelés, 2 sínes és 3 sínes pályákhoz alkalmas
- **OS-S88n OPTO** — optoizolált bemenetek IR detektorokhoz, Hall-érzékelőkhöz és egyéb külső érzékelőkhöz

Minden változat láncolható RJ-45 csatlakozón keresztül, és egyetlen láncban legfeljebb 31 modul támogatott.

![Előnézet](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/all.png?raw=true)

📖 [Kézikönyv (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/Manual-HU.md) &nbsp;|&nbsp; 🔗 [Tároló](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n) &nbsp;|&nbsp; 📦 [Legújabb kiadás](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/releases/latest)

<br>

---

# 🔌 Relés Modulok

---

## OS-relays

Az OS-relays modulok bedugható relés lapok, amelyek OS DCC dekóderekkel együtt működnek. Két típus elérhető:

- **OS-General-Purpose-Relay** — dupla monostabil relé COM/NO/NC érintkezőkkel; szárpolarizáláshoz (electrofrog és unifrog) és általános kiegészítő kapcsoláshoz alkalmas
- **OS-Latching-Relay** — egyes bisztabil relé, amely folyamatos tápellátás nélkül tartja az állását; ideális unifrog polarizáláshoz a szolonoidhoz párhuzamosan bekötve

Mindkét típus THT és SMD kivitelben elérhető, és szétcsattogtható paneleken rendelhető.

![Előnézet](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/all.png?raw=true)

📖 [Kézikönyv (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/Manual-HU.md) &nbsp;|&nbsp; 🔗 [Tároló](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays) &nbsp;|&nbsp; 📦 [Legújabb kiadás](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/releases/latest)

<br>

---

# 💡 Világítás

---

## OS-Lux-One

Az OS-Lux-One moduláris LED világítószalag digitális modellvasúti járművekhez. Több rögzített hosszúságú kocsi-szalagot vált ki egyetlen univerzális verzióval, amely tetszőleges méretre vágható és újra felhasználható. Minden szekció saját beépített áramszabályozóval rendelkezik a stabil fényerőhöz a sínfeszültségtől függetlenül, és a szalag közvetlenül DCC, MM vagy mfx sínáramból működik. Alkalmas H0 és N méretarányhoz egyaránt.

![Előnézet](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/hardware/OS-Lux-One/OS-Lux-One.pdf?raw=true)

📖 [Kézikönyv (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/docs/Manual-HU.md) &nbsp;|&nbsp; 🔗 [Tároló](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One) &nbsp;|&nbsp; 📦 [Legújabb kiadás](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/releases/latest)

<br>

---

# 🎛️ Analóg Pályairányítás

---

## Analog-Layout-Control

Analóg pályairányító modulok sorozata, amelyek moduláris építőelemekként egyedi vezérlőpultokhoz lettek tervezve. Minden modul szabványos JST csatlakozókat használ az egyszerű bekötéshez és az együttműködéshez. Kombináld őket az egyszerű mozdonyvezérlő kapcsolástól a dióda-mátrixon keresztüli teljes útvonalbeállításig.

A sorozat moduljai:

- CAB Vezérlőkapcsoló — pályaszakaszokat rendel Cab A-hoz vagy Cab B-hez, LED visszajelzéssel
- Kitérőmotor-kapcsoló — polaritást fordít kétvezetékes kitérőmotorokhoz
- Szolonoid Kitérőkapcsoló visszajelzéssel — impulzusos vezérlés ikertekercsű meghajtókhoz
- Reteszelő Relé — bisztabil relé szárpolarizáláshoz vagy szakaszkapcsoláshoz
- Dióda-Mátrix — útvonalbeállító lap egyetlen gombbal több kitérő aktiválásához

![Előnézet](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/hardware/Analog-Layout-Control.png?raw=true)

📖 [Kézikönyv (EN)](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/docs/Manual-HU.md) &nbsp;|&nbsp; 🔗 [Tároló](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control) &nbsp;|&nbsp; 📦 [Legújabb kiadás](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/releases/latest)

<br>

---

## Fordítókör Modulok

A Fordítókör Modulok automatikusan kezelik a polaritásváltást, amelyre szükség van, amikor egy vonat belép vagy kilép egy fordítókörből (Y-vágány, hurokpálya vagy fordítókorong). A modul érzékeli a fordított mozdonytól eredő rövidzárlatot, és automatikusan korrigálja a polaritást — kézi beavatkozás nélkül.

![Előnézet](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/blob/main/hardware/turning-loop-modules.png?raw=true)

🔗 [Tároló](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules) &nbsp;|&nbsp; 📦 [Legújabb kiadás](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/releases/latest)

<br>

---

# 🔩 Passzív Alkatrészek és Huzalozás

---

## Wire-Splits

A Wire-Splits lapok kompakt passzív elosztó lapok, amelyek egy bemeneti vezetéket tisztán több kimenetre osztanak szét. Segítségükkel könnyen elosztható a DCC sínáram vagy közös vezéték a pálya sok pontjára zavaros kötegek nélkül.

![Előnézet](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/blob/main/hardware/Wire-Splits.png?raw=true)

🔗 [Tároló](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits) &nbsp;|&nbsp; 📦 [Legújabb kiadás](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/releases/latest)

<br>

---

## Solder Sleepers

A Solder Sleepers PCB alapú sínfenékfa (keresztalj) elemek, amelyek a pályaágyba ragaszthatók. A PCB keresztalj lehetővé teszi a sín közvetlen ráforrasztását a lapra a megbízható elektromos és mechanikai csatlakozáshoz — ideális kézzel épített pályákhoz, dióráma munkákhoz, vagy ahol a szilárd forrasztott kötés előnyt jelent a kapcsokkal szemben.

![Előnézet](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/blob/main/docs/Solder-sleepers.png?raw=true)

🔗 [Tároló](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers) &nbsp;|&nbsp; 📦 [Legújabb kiadás](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/releases/latest)

<br>

---

# 🖥️ Szoftver

---

## OS-Software-Tool

Az OS-Software-Tool egy PC-s segédprogram OS DCC dekóderek konfigurálásához és teszteléséhez. Grafikus felületet biztosít olyan feladatokhoz, amelyek egyébként manuális DCC parancssorozatokat igényelnének.

🔗 [Tároló](https://github.com/Open-Source-Model-Railway-Electronics/OS-software-tool)

<br>

---
