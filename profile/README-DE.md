> 🌐 **Sprache:** &nbsp; [🇬🇧 English](README.md) &nbsp;|&nbsp; 🇩🇪 Deutsch &nbsp;|&nbsp; [🇫🇷 Français](README-FR.md) &nbsp;|&nbsp; [🇳🇱 Nederlands](README-NL.md) &nbsp;|&nbsp; [🇪🇸 Español](README-ES.md) &nbsp;|&nbsp; [🇮🇹 Italiano](README-IT.md) &nbsp;|&nbsp; [🇵🇱 Polski](README-PL.md) &nbsp;|&nbsp; [🇨🇿 Čeština](README-CS.md) &nbsp;|&nbsp; [🇩🇰 Dansk](README-DA.md) &nbsp;|&nbsp; [🇳🇴 Norsk](README-NO.md) &nbsp;|&nbsp; [🇸🇪 Svenska](README-SV.md) &nbsp;|&nbsp; [🇭🇺 Magyar](README-HU.md) &nbsp;|&nbsp; [🇵🇹 Português](README-PT.md)

---

# 🚂 Open Source Modellbahn-Elektronik

Willkommen! Diese Organisation enthält Open-Source-Platinen und Decoder-Module zur Automatisierung von Modelleisenbahnanlagen.  
Alles hier ist vollständig nachbaubar — alle Designs, Firmware und Dokumentation sind frei verfügbar.

Hier findest du Platinen und Software für Weichenantriebe, DCC-Magnetdecoder, DCC-Servodecoder, S88n-Rückmeldemodule, LED-Beleuchtungsstreifen, Relaismodule, analoge Anlagensteuerungen und mehr.

---

# 📘 Anleitungen & Erklärungen

Hintergrundwissen zu den verwendeten Elektronikkonzepten:

- [Weichen & Herzstücke](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Points_and_frogs/points_and_frogs-EN.md)
- [Das Kehrschleifenproblem](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/turning_loop_problem/turning_loop_problem-EN.md)
- [Eine Anlage automatisieren](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/automize_a_layout/automize_a_layout-DE.md)

<br>

---

# 🛠️ Eigene Platinen bauen & bestellen

Schritt-für-Schritt-Anleitungen zum Herunterladen der Dateien, Bestellen bei JLCPCB und Flashen der Firmware:

- [Bare PCB bestellen](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_bare_PCB/Ordering_bare_PCB-EN.md)
- [SMT-bestückte Platine bestellen](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_SMT_ASSEMBLED_PCB/Ordering_Assembled_PCBs_JLCPCB-EN.md)
- [OS-DCC-Decoder programmieren](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Program_OS-DCC-Decoder/Program_OS-DCC-Decoder-DE.md)

<br>

---

# 💡 Eigene Platinen-Tutorials

- [Eigenen LED-Streifen bauen](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_custom_LED_strip/makeYourOwnCustomLedStrip-EN.md)
- [Eigenen Wire Split bauen](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_split/make_your_own_wire_split-EN.md)
- *(demnächst)* Eigene Lötbare Schwellen bauen
- *(demnächst)* Eigenes Steuerpult bauen

<br>

---

# 🔀 DCC-Zubehördecoder

---

## OS-Duplex

Der OS-Duplex ist ein Doppel-DCC-Zubehördecoder für alle Arten von Weichenantrieben — von klassischen Doppelspulen-Magneten über Motorantriebe bis hin zu Relaismodulen zur Herzstückpolarisierung.

Jede der beiden Seiten (A und B) kann unabhängig oder miteinander gekoppelt betrieben werden. Jede Seite kann entweder als zwei separate Einzelausgänge (jeder mit eigener DCC-Adresse) oder als ein kombinierter Doppelausgang für einen Doppelspulenantrieb oder Motorantrieb fungieren.

Optionale Relais-Steckplätze ermöglichen die Herzstückpolarisierung oder das Ansteuern zusätzlicher Spulen und Motoren. Der Duplex kann außerdem ein 4-Licht-Signal mit allen möglichen Signalbildern ansteuern.

![Vorschau](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/hardware/OS-Duplex.png?raw=true)

📖 [Handbuch (DE)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/docs/Manual-DE.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex) &nbsp;|&nbsp; 📦 [Neueste Version](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/releases/latest)

<br>

---

## OS-Duplex-Servo

Der OS-Duplex-Servo ist eine Variante des OS-Duplex mit zusätzlicher Unterstützung für **Servo-Motorausgänge** (Standard-3-Pin-PWM). Er eignet sich ideal für servo-gesteuerte Weichenantriebe und behält dabei die gleiche Doppelkanal-Architektur, Relais-Erweiterungsoptionen und Signalsteuerungsmöglichkeiten des Basis-OS-Duplex.

![Vorschau](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/hardware/OS-Duplex.png?raw=true)

📖 [Handbuch (DE)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/docs/Manual-DE.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo) &nbsp;|&nbsp; 📦 [Neueste Version](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/releases/latest)

<br>

---

## OS-Servo-Decoder-8

Der OS-Servo-Decoder-8 ist ein einfacher und robuster DCC-Zubehördecoder zum Ansteuern von bis zu 8 Servomotoren. Er unterstützt flexible Konfiguration über DCC-Befehle oder physische Tasten, optionale Relais-Erweiterungsmodule zur Herzstückpolarisierung und direkte Steuerung über DCC-Zubehörbefehle oder Lokomotivfunktionen (F1–F8) — kein Computer oder CV-Programmer erforderlich.

![Vorschau](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/hardware/OS-Servo-Decoder-8.png?raw=true)

📖 [Handbuch (DE)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/docs/Manual-DE.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8) &nbsp;|&nbsp; 📦 [Neueste Version](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/releases/latest)

<br>

---

## OS-Solenoid-Decoder

Der OS-Solenoid-Decoder ist ein leistungsfähiger DCC-Zubehördecoder zum Schalten von Weichenantrieben, Relais, Entkupplern und anderen magnetisch betriebenen Geräten. Er verarbeitet bis zu 5 A und unterstützt nahezu jeden Weichenantriebstyp. Er ist außerdem mit OS-Relaismodulen für die vollständige Herzstückpolarisierung bei Electrofrog- und Unifrog-Weichen kompatibel.

Wesentliche Merkmale:

- Bis zu 8 Doppelausgänge für Doppelspulen-Weichenantriebe
- Mehrere Ausgangsmodi: Doppelimpuls, Einzelimpuls, Dauerein, Einzeldauerein, Electrofrog
- Konfiguration über DCC-Zubehörbefehle — kein Computer erforderlich
- Optionale CDU-Modulunterstützung
- Erweiterbar mit Relais- und Transistorplatinen

![Vorschau](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/hardware/OS-Solenoid-Decoder.png?raw=true)

📖 [Handbuch (DE)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/docs/Manual-DE.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder) &nbsp;|&nbsp; 📦 [Neueste Version](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/releases/latest)

<br>

---

# 📡 Rückmeldung & Gleisbelegtmelder

---

## OS-S88n (CS / GND / OPTO)

Die OS-S88n-Module bieten S88n-Rückmeldung für DCC-Modelleisenbahnen und ermöglichen die Echtzeit-Überwachung von Blockbelegungen und Anlagenereignissen. Die Daten werden an die Zentrale oder PC-basierte Software gesendet (iTrain, Rocrail, Windigipet u. a.).

Drei Varianten stehen zur Verfügung:

- **OS-S88n GND** — Massekontakt-Erkennung, ideal für 3-Leiter-Anlagen (Märklin-Stil)
- **OS-S88n CS** — Stromerkennungs-Modul, geeignet für 2- und 3-Leiter-Anlagen
- **OS-S88n OPTO** — optisch isolierte Eingänge für IR-Detektoren, Hall-Sensoren und andere externe Sensoren

Alle Versionen sind über RJ-45 verkettbar und unterstützen bis zu 31 Module in einer Kette.

![Vorschau](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/all.png?raw=true)

📖 [Handbuch (DE)](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/Manual-DE.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n) &nbsp;|&nbsp; 📦 [Neueste Version](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/releases/latest)

<br>

---

# 🔌 Relaismodule

---

## OS-relays

Die OS-Relaismodule sind einsteckbare Relaisplatinen für den Einsatz mit OS-DCC-Decodern. Zwei Typen sind verfügbar:

- **OS-General-Purpose-Relay** — Doppel-Monostabiles-Relais mit COM/NO/NC-Kontakten; geeignet für Herzstückpolarisierung (Electrofrog und Unifrog) und allgemeine Zubehörschaltungen
- **OS-Latching-Relay** — Einzelnes bistabiles Relais, das seine Position ohne dauerhafte Stromversorgung hält; ideal für Unifrog-Polarisierung parallel zum Magnetantrieb

Beide Typen sind in THT- und SMD-Ausführung erhältlich und können als abzubrechende Panels bestellt werden.

![Vorschau](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/all.png?raw=true)

📖 [Handbuch (DE)](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/Manual-DE.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays) &nbsp;|&nbsp; 📦 [Neueste Version](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/releases/latest)

<br>

---

# 💡 Beleuchtung

---

## OS-Lux-One

Der OS-Lux-One ist ein modularer LED-Beleuchtungsstreifen für digitales Modellbahnrollmaterial. Er ersetzt mehrere Beleuchtungsstreifen fixer Länge durch eine universelle Version, die auf Maß geschnitten und wiederverwendet werden kann. Jeder Abschnitt verfügt über einen eigenen eingebauten Stromregler für gleichmäßige Helligkeit unabhängig von der Gleisspannung. Funktioniert direkt mit DCC-, MM- oder mfx-Gleisspannung. Geeignet für H0 und N.

![Vorschau](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/hardware/OS-Lux-One/OS-Lux-One.pdf?raw=true)

📖 [Handbuch (DE)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/docs/Manual-DE.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One) &nbsp;|&nbsp; 📦 [Neueste Version](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/releases/latest)

<br>

---

# 🎛️ Analoge Anlagensteuerung

---

## Analog-Layout-Control

Eine Reihe analoger Anlagensteuerungsmodule als modulare Bausteine für individuelle Steuerpulte. Alle Module verwenden Standard-JST-Stecker für einfache Verdrahtung und Kompatibilität untereinander. Kombiniert lassen sich damit Steuerpulte von der einfachen Fahrsteller-Umschaltung bis hin zur vollständigen Fahrstraßensteuerung über Diodenmatrizen aufbauen.

Module in dieser Reihe:

- CAB-Control-Schalter — weist Gleisabschnitte Fahrsteller A oder B zu, mit LED-Rückmeldung
- Weichenmotor-Schalter — kehrt die Polarität für 2-Draht-Weichenantriebe um
- Magnetweichen-Schalter mit Rückmeldung — Momentkontakt für Doppelspulenantriebe
- Bistabiles Relais — für Herzstückpolarisierung oder Abschnittsschaltung
- Diodenmatrix — Fahrstraßen-Platine zum Stellen mehrerer Weichen mit einem Tastendruck

![Vorschau](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/hardware/Analog-Layout-Control.png?raw=true)

📖 [Handbuch (DE)](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/docs/Manual-DE.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control) &nbsp;|&nbsp; 📦 [Neueste Version](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/releases/latest)

<br>

---

## Kehrschleifenmodule

Die Kehrschleifenmodule übernehmen automatisch die erforderliche Polaritätsumkehr, wenn ein Zug in eine Kehrschleife (Wendegleis, Balloon-Loop oder Drehscheibe) einfährt oder sie verlässt. Das Modul erkennt den durch die umgekehrte Lokomotive verursachten Kurzschluss und korrigiert die Polarität automatisch — ohne manuellen Eingriff.

![Vorschau](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/blob/main/hardware/turning-loop-modules.png?raw=true)

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules) &nbsp;|&nbsp; 📦 [Neueste Version](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/releases/latest)

<br>

---

# 🔩 Passive Bauteile & Verdrahtung

---

## Wire-Splits

Wire-Split-Platinen sind kompakte passive Verteilerplatinen zum sauberen Aufteilen eines Eingangsdrahts auf mehrere Ausgänge. Sie vereinfachen die Verteilung von DCC-Gleisspannung oder gemeinsamen Leitungen zu vielen Punkten der Anlage — ohne unordentliche Lötverbindungen.

![Vorschau](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/blob/main/hardware/Wire-Splits.png?raw=true)

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits) &nbsp;|&nbsp; 📦 [Neueste Version](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/releases/latest)

<br>

---

## Lötschwellen

Lötschwellen sind PCB-basierte Gleisschwellen zum Einkleben in das Gleisbett. Die PCB-Schwelle ermöglicht das direkte Auflöten der Schiene auf die Platine — für eine zuverlässige elektrische und mechanische Verbindung. Ideal für selbst gebaute Gleise, Diorama-Arbeiten oder überall dort, wo eine feste Lötverbindung bevorzugt wird.

![Vorschau](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/blob/main/docs/Solder-sleepers.png?raw=true)

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers) &nbsp;|&nbsp; 📦 [Neueste Version](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/releases/latest)

<br>

---

# 🖥️ Software

---

## OS-Software-Tool

Das OS-Software-Tool ist ein PC-Hilfsprogramm zur Konfiguration und zum Testen von OS-DCC-Decodern. Es bietet eine grafische Oberfläche für Aufgaben, die sonst manuelle DCC-Befehlssequenzen erfordern würden.

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-software-tool)

<br>

---
