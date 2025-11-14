# 🚂 Open Source Model Railway Electronics

Welcome! This organization contains open-source PCBs and decoder modules for model railway automation.  
Each module below includes a visual preview and links to the corresponding repository and release section.

<br>
<br>

# 📘 Documentation Index
---
Welcome to the technical documentation of **Open Source Model Railway Electronics**.  
Each chapter explains, builds, or programs part of your layout — all fully open-source and reproducible.

Below you will find PCB designs and software for all kind of things. Point motor, DCC solenoid decoders, DCC servo decoders, S88 Occupancy decoders, LED strips and Wire splits.

<br>
<br>

# 🧭 Understanding Model Railway Electronics — Explanations & Guides
---
- [Points & Frogs](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Points_and_frogs/points_and_frogs-EN.md)
- [Turning Loop Problem](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/turning_loop_problem/turning_loop_problem-EN.md)
- [Wiring Guide](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/main/wiring_guide/wiring_guide.md)  
- [Automize a Layout](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/automize_a_layout/automize_a_layout-EN.md)

<br>
<br>

# 🛠️ Build Your Own Electronics

---
These manuals explain in great detail how you can download the needed files, how to place orders at JLCPCB and how to flash the firmware on a DCC decoder.

- [Order Bare PCB](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_bare_PCB/Ordering_bare_PCB-EN.md)
- [Order SMT Assembled PCB](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_SMT_ASSEMBLED_PCB/Ordering_Assembled_PCBs_JLCPCB-EN.md)
- [Program Your OS Decoder](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Program_OS-DCC-Decoder/Program_OS-DCC-Decoder-EN.md)

<br>
<br>

# 💡 Create Your Own PCB Tutorial
---
- [Make Your Own Custom LED Strip](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_custom_LED_strip/makeYourOwnCustomLedStrip-EN.md)
- [Make Your Own Wire split ]( https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_split/make_your_own_wire_split-EN.md)
- TODO  make your own solder sleeper
- TODO  make your own control panel

<br>
<br>

# OS-Duplex 

The OS-Duplex is a dual DCC accessory decoder designed for all types of turnout drives — from traditional solenoids to motor drives and relay modules for frog polarization.

Each side (A and B) can operate independently or be linked together.

Every side can act as either:

🅰️ / 🅱️ two independent single outputs (each with its own DCC address), or

⚙️ one combined double output for a twin-coil or motor drive turnout.

Optional relay sockets allow you to add point frog polarization, or use the same outputs to drive extra coils or motors.

The Duplex can also be used to drive an 4 light signal, with every possible aspect.

---
![Preview](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/hardware/OS-Duplex.png?raw=true)  
📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/docs/Manual-EN.md)  
🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex)  
📦 [Latest release](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/releases/latest)

<br>
<br>

# OS-Vector
---
![Preview](https://github.com/Open-Source-Model-Railway-Electronics/OS-Vector/blob/master/hardware/OS-Vector.png?raw=true)  
📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-Vector/blob/master/docs/Manual-EN.md)  
🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Vector)  
📦 [Latest release](https://github.com/Open-Source-Model-Railway-Electronics/OS-Vector/releases/latest)

<br>
<br>

# OS-Servo-Decoder-8

The OS-Servo-Decoder is a simple and robust DCC accessory decoder designed for driving up to 8 servo motors. It supports modern model railroads with flexible configuration options, external relay modules for polarity switching (optional) and direct control using both input switches, DCC accessory commands and locomotive functions (F1–F8).

---
![Preview](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/hardware/OS-Servo-Decoder-8.png?raw=true)  
📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/docs/Manual-EN.md)  
🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8)  
📦 [Latest release](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/releases/latest)


<br>
<br>

# OS-Solenoid-Decoder  

The OS-Solenoid-Decoder is a simple, powerful DCC accessory decoder for switching:

• Turnouts (point motors),
• Relays,
• Uncouplers,
• And other solenoid-driven devices.

It can handle loads of up to 5 amps and supports almost any type of point motor.
It can also be used in combination with OS-relays to handle frog polarisation for electrofrog and unifrog points.

---
![Preview](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/hardware/OS-Solenoid-Decoder.png?raw=true)  
📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/docs/Manual-EN.md)  
🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder)  
📦 [Latest release](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/releases/latest)

<br>
<br>

# OS-Relay  
---
![Preview](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/all.png?raw=true")
📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/Manual-EN.md)  
🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays)  
📦 [Latest release](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/releases/latest)

<br>
<br>

# OS-S88n (CS/GND/OTPO)

The OS-S88n modules provide feedback functionality for DCC model railroads using the standardized S88n protocol. These modules allow real-time monitoring of block occupancy and layout events by sending data to your command station or PC-based software.

Models:
    • OS-S88n GND — Standard input module using ground-contact detection  
    • OS-S88n CS — current-sensing module  
    • OS-S88n OPTO — Opto-isolated module.

All versions include:
    • Daisy-chainable S88n connectors (RJ-45)  
    • Screw terminals for simple input wiring  
    • Compatibility with all major command stations and software (iTrain, Rocrail, Windigipet, etc.)

---
![Preview](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/all.png?raw=true")
📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/Manual-EN.md)  
🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n)  
📦 [Latest release](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/releases/latest)  

<br>
<br>

# OS-Lux-One
The OS-Lux-One is an open-source modular LED lighting strip for digital model railway systems It replaces multiple fixed-length coach strips with one universal version that can be shortened and reused for different coach types. Each strip section contains its own current control to keep the light level steady, even when the track voltage changes. The design is suitable for both H0 and N scale rolling stock.

---
![Preview](https://github.com/Open-Source-Model-Railway-Electronics/OS-led-strips/blob/main/hardware/led-strips.png?raw=true)  
📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-led-strips/blob/main/docs/Manual-EN.md)  
🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-led-strips)  
📦 [Latest release](https://github.com/Open-Source-Model-Railway-Electronics/OS-led-strips/releases/latest)

<br>
<br>

# Wire-Splits
---
![Preview](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/blob/main/hardware/Wire-Splits.png?raw=true)  
🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits)  
📦 [Latest release](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/releases/latest)

<br>
<br>

# Analog-Layout-Control  

A range of analog layout control modules designed for intuitive, modular, and open-source model railway control. Designed as building blocks that one can use to make his own control panel with. All modules use standard connectors for easy wiring and interoperability, and can be combined to create a complete control panel — from simple cab control and turnout buttons to route settings via diode matrices.

---
![Preview](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/hardware/Analog-Layout-Control.png?raw=true)
📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/docs/Manual-EN.md)  
🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control)  
📦 [Latest release](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/releases/latest)

<br>
<br>

# Solder-sleepers  
---
![Preview](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/blob/main/docs/Solder-sleepers.png?raw=true)  
🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers)  
📦 [Latest release](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/releases/latest)

<br>
<br>

# turning-loop-modules  
---
![Preview](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/blob/main/hardware/turning-loop-modules.png?raw=true)  
📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/blob/main/docs/Manual-EN.md)  TODO
🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules)  
📦 [Latest release](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/releases/latest)

---
