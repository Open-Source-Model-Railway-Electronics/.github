> 🌐 **Language:** &nbsp; 🇬🇧 English &nbsp;|&nbsp; [🇩🇪 Deutsch](README-DE.md) &nbsp;|&nbsp; [🇫🇷 Français](README-FR.md) &nbsp;|&nbsp; [🇳🇱 Nederlands](README-NL.md) &nbsp;|&nbsp; [🇪🇸 Español](README-ES.md) &nbsp;|&nbsp; [🇮🇹 Italiano](README-IT.md) &nbsp;|&nbsp; [🇵🇱 Polski](README-PL.md) &nbsp;|&nbsp; [🇨🇿 Čeština](README-CS.md) &nbsp;|&nbsp; [🇩🇰 Dansk](README-DA.md) &nbsp;|&nbsp; [🇳🇴 Norsk](README-NO.md) &nbsp;|&nbsp; [🇸🇪 Svenska](README-SV.md) &nbsp;|&nbsp; [🇭🇺 Magyar](README-HU.md) &nbsp;|&nbsp; [🇵🇹 Português](README-PT.md)

---

# 🚂 Open Source Model Railway Electronics

Welcome! This organisation contains open-source PCBs and decoder modules for model railway automation.  
Everything here is fully reproducible — all designs, firmware and documentation are freely available.

Below you will find PCB designs and software for point motors, DCC solenoid decoders, DCC servo decoders, S88n occupancy feedback modules, LED lighting strips, relay modules, analog layout control panels and more.

---

# 📘 Guides & Explanations

Background reading to understand the electronics and concepts used across these projects:

- [Points & Frogs](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Points_and_frogs/points_and_frogs-EN.md)
- [Turning Loop Problem](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/turning_loop_problem/turning_loop_problem-EN.md)
- [Automating a Layout](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/automize_a_layout/automize_a_layout-EN.md)

<br>

---

# 🛠️ Build & Order Your Own PCBs

Step-by-step guides for downloading files, placing orders at JLCPCB, and flashing firmware:

- [Order a Bare PCB](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_bare_PCB/Ordering_bare_PCB-EN.md)
- [Order an SMT Assembled PCB](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_SMT_ASSEMBLED_PCB/Ordering_Assembled_PCBs_JLCPCB-EN.md)
- [Program Your OS DCC Decoder](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Program_OS-DCC-Decoder/Program_OS-DCC-Decoder-EN.md)

<br>

---

# 💡 Create Your Own PCB Tutorials

- [Make Your Own Custom LED Strip](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_custom_LED_strip/makeYourOwnCustomLedStrip-EN.md)
- [Make Your Own Wire Split](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_split/make_your_own_wire_split-EN.md)
- *(coming soon)* Make Your Own Solder Sleeper
- *(coming soon)* Make Your Own Control Panel

<br>

---

# 🔀 DCC Accessory Decoders

---

## OS-Duplex

The OS-Duplex is a dual DCC accessory decoder designed for all types of turnout drives — from traditional twin-coil solenoids to motor-driven point motors and relay modules for frog polarization.

Each of the two sides (A and B) can operate independently or be linked together. Every side can act as two independent single outputs (each with its own DCC address), or as one combined double output for a twin-coil or motor-drive turnout.

Optional relay sockets allow frog polarization or driving extra coils and motors. The Duplex can also drive a 4-lamp signal with every possible aspect.

![Preview](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/hardware/OS-Duplex.png?raw=true)

📖 [Manual (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/docs/Manual-EN.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex) &nbsp;|&nbsp; 📦 [Latest Release](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/releases/latest)

<br>

---

## OS-Duplex-Servo

The OS-Duplex-Servo is a variant of the OS-Duplex with added support for **servo motor outputs** (standard 3-pin PWM). It is ideal for servo-driven point motors while retaining the same dual-channel architecture, relay expansion options, and signal control capabilities as the base OS-Duplex.

![Preview](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/hardware/OS-Duplex.png?raw=true)

📖 [Manual (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/docs/Manual-EN.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo) &nbsp;|&nbsp; 📦 [Latest Release](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/releases/latest)

<br>

---

## OS-Servo-Decoder-8

The OS-Servo-Decoder-8 is a simple and robust DCC accessory decoder designed to drive up to 8 servo motors. It supports flexible configuration via DCC commands or physical buttons, optional relay extension modules for frog polarization, and direct control using DCC accessory commands or locomotive functions (F1–F8) — no computer or CV programmer required.

![Preview](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/hardware/OS-Servo-Decoder-8.png?raw=true)

📖 [Manual (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/docs/Manual-EN.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8) &nbsp;|&nbsp; 📦 [Latest Release](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/releases/latest)

<br>

---

## OS-Solenoid-Decoder

The OS-Solenoid-Decoder is a powerful DCC accessory decoder for switching turnouts (point motors), relays, uncouplers, and other solenoid-driven devices. It handles up to 5 A and supports almost any type of point motor. It is also compatible with OS relay modules for full electrofrog and unifrog frog polarization.

Key features:

- Up to 8 dual outputs for twin-coil point motors
- Multiple output modes: Double Pulse, Single Pulse, Double Steady, Single Steady, Electrofrog
- Configurable via DCC accessory commands — no computer needed
- Optional CDU module support
- Expandable with relay and transistor boards

![Preview](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/hardware/OS-Solenoid-Decoder.png?raw=true)

📖 [Manual (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/docs/Manual-EN.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder) &nbsp;|&nbsp; 📦 [Latest Release](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/releases/latest)

<br>

---

# 📡 Feedback & Occupancy Detection

---

## OS-S88n (CS / GND / OPTO)

The OS-S88n modules provide S88n feedback for DCC model railroads, allowing real-time monitoring of block occupancy and layout events. Data is sent to your command station or PC-based software (iTrain, Rocrail, Windigipet, and others).

Three variants are available:

- **OS-S88n GND** — ground-contact detection, ideal for 3-rail (Märklin-style) layouts
- **OS-S88n CS** — current-sensing detection, suitable for 2-rail and 3-rail layouts
- **OS-S88n OPTO** — opto-isolated inputs for IR detectors, Hall sensors, and other external sensors

All versions are daisy-chainable via RJ-45 and support up to 31 modules in a single chain.

![Preview](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/all.png?raw=true)

📖 [Manual (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/Manual-EN.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n) &nbsp;|&nbsp; 📦 [Latest Release](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/releases/latest)

<br>

---

# 🔌 Relay Modules

---

## OS-relays

The OS-relay modules are plug-in relay boards designed to work alongside OS DCC decoders. Two types are available:

- **OS-General-Purpose-Relay** — dual monostable relay with COM/NO/NC contacts; suitable for frog polarization (electrofrog and unifrog) and general accessory switching
- **OS-Latching-Relay** — single bistable relay that holds its position without continuous power; ideal for unifrog polarization wired in parallel with the solenoid

Both types are available in THT and SMD versions and can be ordered as snap-apart panels.

![Preview](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/all.png?raw=true)

📖 [Manual (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/Manual-EN.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays) &nbsp;|&nbsp; 📦 [Latest Release](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/releases/latest)

<br>

---

# 💡 Lighting

---

## OS-Lux-One

The OS-Lux-One is a modular LED lighting strip for digital model railway rolling stock. It replaces multiple fixed-length coach strips with one universal version that can be cut to size and reused. Each section has its own built-in current regulator for stable brightness regardless of track voltage, and the strip works directly from DCC, MM, or mfx track power. Suitable for both H0 and N scale.

![Preview](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/hardware/OS-Lux-One/OS-Lux-One.pdf?raw=true)

📖 [Manual (EN)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/docs/Manual-EN.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One) &nbsp;|&nbsp; 📦 [Latest Release](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/releases/latest)

<br>

---

# 🎛️ Analog Layout Control

---

## Analog-Layout-Control

A range of analog layout control modules designed as modular building blocks for custom control panels. All modules use standard JST connectors for easy wiring and interoperability. Combine them to build anything from simple cab-control switching to full route setting via diode matrices.

Modules in this range include:

- CAB Control Switch — assigns track sections to Cab A or Cab B, with LED feedback
- Point Motor Switch — reverses polarity for 2-wire point motors
- Solenoid Point Switch with feedback — momentary control for twin-coil drives
- Latching Relay — bistable relay for frog polarization or section switching
- Diode Matrix — route-setting board for activating multiple turnouts with a single button

![Preview](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/hardware/Analog-Layout-Control.png?raw=true)

📖 [Manual (EN)](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/docs/Manual-EN.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control) &nbsp;|&nbsp; 📦 [Latest Release](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/releases/latest)

<br>

---

## Turning Loop Modules

The Turning Loop Modules automatically handle the polarity reversal needed when a train enters or exits a reversing loop (wye, balloon loop, or turntable). The module detects the short circuit caused by a reversed locomotive and corrects the polarity automatically, without any manual intervention.

![Preview](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/blob/main/hardware/turning-loop-modules.png?raw=true)

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules) &nbsp;|&nbsp; 📦 [Latest Release](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/releases/latest)

<br>

---

# 🔩 Passive Components & Wiring

---

## Wire-Splits

Wire-Split PCBs are compact passive distribution boards for splitting one input wire cleanly into multiple outputs. They make it easy to distribute DCC track power or common wires to many points on your layout without messy joint bundles.

![Preview](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/blob/main/hardware/Wire-Splits.png?raw=true)

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits) &nbsp;|&nbsp; 📦 [Latest Release](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/releases/latest)

<br>

---

## Solder Sleepers

Solder Sleepers are PCB-based track sleepers (ties) designed to be glued into the track bed. The PCB sleeper allows you to solder the rail directly onto the board for a reliable electrical and mechanical connection — ideal for scratch-built track, diorama work, or anywhere that a firm solder joint is preferred over clips.

![Preview](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/blob/main/docs/Solder-sleepers.png?raw=true)

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers) &nbsp;|&nbsp; 📦 [Latest Release](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/releases/latest)

<br>

---

# 🖥️ Software

---

## OS-Software-Tool

The OS-Software-Tool is a PC utility for configuring and testing OS DCC decoders. It provides a graphical interface for tasks that would otherwise require manual DCC command sequences.

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-software-tool)

<br>

---
