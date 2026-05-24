> 🌐 **Idioma:** &nbsp; [🇬🇧 English](README.md) &nbsp;|&nbsp; [🇩🇪 Deutsch](README-DE.md) &nbsp;|&nbsp; [🇫🇷 Français](README-FR.md) &nbsp;|&nbsp; [🇳🇱 Nederlands](README-NL.md) &nbsp;|&nbsp; 🇪🇸 Español &nbsp;|&nbsp; [🇮🇹 Italiano](README-IT.md) &nbsp;|&nbsp; [🇵🇱 Polski](README-PL.md) &nbsp;|&nbsp; [🇨🇿 Čeština](README-CS.md) &nbsp;|&nbsp; [🇩🇰 Dansk](README-DA.md) &nbsp;|&nbsp; [🇳🇴 Norsk](README-NO.md) &nbsp;|&nbsp; [🇸🇪 Svenska](README-SV.md) &nbsp;|&nbsp; [🇭🇺 Magyar](README-HU.md) &nbsp;|&nbsp; [🇵🇹 Português](README-PT.md)

---

# 🚂 Open Source Model Railway Electronics

¡Bienvenido! Esta organización contiene PCB y módulos de decodificador de código abierto para la automatización de maquetas de ferrocarril.  
Todo lo que encontrará aquí es totalmente reproducible — todos los diseños, el firmware y la documentación están disponibles libremente.

A continuación encontrará diseños de PCB y software para motores de aguja, decodificadores de solenoide DCC, decodificadores de servo DCC, módulos de retroalimentación de ocupación S88n, tiras de iluminación LED, módulos de relé, paneles de control analógico y mucho más.

---

# 📘 Guías y Explicaciones

Lecturas de referencia para comprender la electrónica y los conceptos utilizados en estos proyectos:

- [Agujas y Frogs](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Points_and_frogs/points_and_frogs-EN.md)
- [Problema del Bucle de Inversión](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/turning_loop_problem/turning_loop_problem-EN.md)
- [Automatización de una Maqueta](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/automize_a_layout/automize_a_layout-EN.md)

<br>

---

# 🛠️ Construya y Encargue sus Propios PCB

Guías paso a paso para descargar archivos, realizar pedidos en JLCPCB y programar el firmware:

- [Pedir un PCB sin componentes](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_bare_PCB/Ordering_bare_PCB-EN.md)
- [Pedir un PCB ensamblado SMT](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_SMT_ASSEMBLED_PCB/Ordering_Assembled_PCBs_JLCPCB-EN.md)
- [Programar su Decodificador DCC OS](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Program_OS-DCC-Decoder/Program_OS-DCC-Decoder-EN.md)

<br>

---

# 💡 Tutoriales para Crear sus Propios PCB

- [Cree su Propia Tira LED Personalizada](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_custom_LED_strip/makeYourOwnCustomLedStrip-EN.md)
- [Cree su Propio Distribuidor de Cables](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_split/make_your_own_wire_split-EN.md)
- *(próximamente)* Cree su Propia Traviesa de Soldadura
- *(próximamente)* Cree su Propio Panel de Control

<br>

---

# 🔀 Decodificadores de Accesorios DCC

---

## OS-Duplex

El OS-Duplex es un decodificador de accesorios DCC dual diseñado para todo tipo de accionamientos de agujas: desde solenoides tradicionales de doble bobina hasta motores de aguja accionados por motor y módulos de relé para polarización de frog.

Cada uno de los dos lados (A y B) puede funcionar de forma independiente o estar vinculado entre sí. Cada lado puede actuar como dos salidas individuales independientes (cada una con su propia dirección DCC), o como una salida doble combinada para una aguja de doble bobina o accionamiento por motor.

Las tomas de relé opcionales permiten la polarización de frog o el accionamiento de bobinas y motores adicionales. El Duplex también puede accionar una señal de 4 luces con todos los aspectos posibles.

![Vista previa](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/hardware/OS-Duplex.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/docs/Manual-ES.md) &nbsp;|&nbsp; 🔗 [Repositorio](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex) &nbsp;|&nbsp; 📦 [Última versión](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/releases/latest)

<br>

---

## OS-Duplex-Servo

El OS-Duplex-Servo es una variante del OS-Duplex con soporte añadido para **salidas de servomotor** (PWM estándar de 3 pines). Es ideal para motores de aguja accionados por servo, manteniendo la misma arquitectura de doble canal, opciones de expansión de relé y capacidades de control de señales que el OS-Duplex base.

![Vista previa](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/hardware/OS-Duplex.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/docs/Manual-ES.md) &nbsp;|&nbsp; 🔗 [Repositorio](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo) &nbsp;|&nbsp; 📦 [Última versión](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/releases/latest)

<br>

---

## OS-Servo-Decoder-8

El OS-Servo-Decoder-8 es un decodificador de accesorios DCC sencillo y robusto diseñado para accionar hasta 8 servomotores. Admite configuración flexible mediante comandos DCC o botones físicos, módulos de extensión de relé opcionales para polarización de frog, y control directo mediante comandos de accesorio DCC o funciones de locomotora (F1–F8) — sin necesidad de ordenador ni programador de CV.

![Vista previa](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/hardware/OS-Servo-Decoder-8.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/docs/Manual-ES.md) &nbsp;|&nbsp; 🔗 [Repositorio](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8) &nbsp;|&nbsp; 📦 [Última versión](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/releases/latest)

<br>

---

## OS-Solenoid-Decoder

El OS-Solenoid-Decoder es un potente decodificador de accesorios DCC para conmutar agujas (motores de aguja), relés, desenganchadores y otros dispositivos accionados por solenoide. Gestiona hasta 5 A y es compatible con casi cualquier tipo de motor de aguja. También es compatible con los módulos de relé OS para polarización completa de frog tanto electrofrog como unifrog.

Características principales:

- Hasta 8 salidas duales para motores de aguja de doble bobina
- Múltiples modos de salida: Impulso Doble, Impulso Simple, Continuo Doble, Continuo Simple, Electrofrog
- Configurable mediante comandos de accesorio DCC — sin necesidad de ordenador
- Compatible con módulo CDU opcional
- Ampliable con placas de relé y transistor

![Vista previa](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/hardware/OS-Solenoid-Decoder.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/docs/Manual-ES.md) &nbsp;|&nbsp; 🔗 [Repositorio](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder) &nbsp;|&nbsp; 📦 [Última versión](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/releases/latest)

<br>

---

# 📡 Retroalimentación y Detección de Ocupación

---

## OS-S88n (CS / GND / OPTO)

Los módulos OS-S88n proporcionan retroalimentación S88n para maquetas de ferrocarril DCC, permitiendo la monitorización en tiempo real de la ocupación de bloques y los eventos de la maqueta. Los datos se envían a su central de mando o software basado en PC (iTrain, Rocrail, Windigipet y otros).

Hay tres variantes disponibles:

- **OS-S88n GND** — detección por contacto a masa, ideal para maquetas de 3 carriles (estilo Märklin)
- **OS-S88n CS** — detección por sensor de corriente, adecuada para maquetas de 2 y 3 carriles
- **OS-S88n OPTO** — entradas optoacopladas para detectores IR, sensores Hall y otros sensores externos

Todas las versiones son encadenables mediante RJ-45 y admiten hasta 31 módulos en una sola cadena.

![Vista previa](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/all.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/Manual-ES.md) &nbsp;|&nbsp; 🔗 [Repositorio](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n) &nbsp;|&nbsp; 📦 [Última versión](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/releases/latest)

<br>

---

# 🔌 Módulos de Relé

---

## OS-relays

Los módulos OS-relay son placas de relé enchufables diseñadas para funcionar junto con los decodificadores DCC OS. Hay dos tipos disponibles:

- **OS-General-Purpose-Relay** — relé monoestable dual con contactos COM/NO/NC; adecuado para polarización de frog (electrofrog y unifrog) y conmutación general de accesorios
- **OS-Latching-Relay** — relé biestable simple que mantiene su posición sin alimentación continua; ideal para polarización unifrog cableado en paralelo con el solenoide

Ambos tipos están disponibles en versiones THT y SMD y pueden pedirse en paneles separables.

![Vista previa](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/all.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/Manual-ES.md) &nbsp;|&nbsp; 🔗 [Repositorio](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays) &nbsp;|&nbsp; 📦 [Última versión](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/releases/latest)

<br>

---

# 💡 Iluminación

---

## OS-Lux-One

El OS-Lux-One es una tira de iluminación LED modular para material rodante de ferrocarril en miniatura digital. Sustituye múltiples tiras de coche de longitud fija por una versión universal que puede cortarse a medida y reutilizarse. Cada sección tiene su propio regulador de corriente integrado para un brillo estable independientemente de la tensión de vía, y la tira funciona directamente con alimentación de vía DCC, MM o mfx. Adecuada tanto para escala H0 como N.

![Vista previa](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/hardware/OS-Lux-One/OS-Lux-One.pdf?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/docs/Manual-ES.md) &nbsp;|&nbsp; 🔗 [Repositorio](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One) &nbsp;|&nbsp; 📦 [Última versión](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/releases/latest)

<br>

---

# 🎛️ Control de Maqueta Analógica

---

## Analog-Layout-Control

Una gama de módulos de control de maqueta analógica diseñados como bloques de construcción modulares para paneles de control personalizados. Todos los módulos utilizan conectores JST estándar para un cableado sencillo e interoperabilidad. Combínelos para construir desde una simple conmutación de control de cabina hasta la selección completa de rutas mediante matrices de diodos.

Los módulos de esta gama incluyen:

- CAB Control Switch — asigna secciones de vía a la Cabina A o B, con indicación LED
- Point Motor Switch — invierte la polaridad para motores de aguja de 2 hilos
- Interruptor de aguja de solenoide con retroalimentación — control momentáneo para accionamientos de doble bobina
- Latching Relay — relé biestable para polarización de frog o conmutación de sección
- Diode Matrix — placa de selección de rutas para activar múltiples agujas con un solo botón

![Vista previa](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/hardware/Analog-Layout-Control.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/docs/Manual-ES.md) &nbsp;|&nbsp; 🔗 [Repositorio](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control) &nbsp;|&nbsp; 📦 [Última versión](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/releases/latest)

<br>

---

## Módulos de Bucle de Inversión (Turning Loop Modules)

Los Turning Loop Modules gestionan automáticamente la inversión de polaridad necesaria cuando un tren entra o sale de un bucle de inversión (lazo en Y, bucle de retorno o placa giratoria). El módulo detecta el cortocircuito causado por una locomotora con polaridad invertida y corrige la polaridad automáticamente, sin ninguna intervención manual.

![Vista previa](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/blob/main/hardware/turning-loop-modules.png?raw=true)

🔗 [Repositorio](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules) &nbsp;|&nbsp; 📦 [Última versión](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/releases/latest)

<br>

---

# 🔩 Componentes Pasivos y Cableado

---

## Wire-Splits

Las PCB Wire-Split son placas de distribución pasiva compactas para dividir un cable de entrada limpiamente en múltiples salidas. Facilitan la distribución de la alimentación de vía DCC o los cables comunes a muchos puntos de su maqueta sin nudos de empalmes desordenados.

![Vista previa](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/blob/main/hardware/Wire-Splits.png?raw=true)

🔗 [Repositorio](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits) &nbsp;|&nbsp; 📦 [Última versión](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/releases/latest)

<br>

---

## Solder Sleepers

Las Solder Sleepers son traviesas de vía basadas en PCB diseñadas para pegarse en el lecho de balasto. La traviesa de PCB permite soldar el carril directamente sobre la placa para una conexión eléctrica y mecánica fiable — ideal para vía construida artesanalmente, trabajos de diorama o en cualquier lugar donde se prefiera una junta de soldadura firme a los clips.

![Vista previa](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/blob/main/docs/Solder-sleepers.png?raw=true)

🔗 [Repositorio](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers) &nbsp;|&nbsp; 📦 [Última versión](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/releases/latest)

<br>

---

# 🖥️ Software

---

## OS-Software-Tool

El OS-Software-Tool es una utilidad de PC para configurar y probar decodificadores DCC OS. Proporciona una interfaz gráfica para tareas que de otro modo requerirían secuencias de comandos DCC manuales.

🔗 [Repositorio](https://github.com/Open-Source-Model-Railway-Electronics/OS-software-tool)

<br>

---
