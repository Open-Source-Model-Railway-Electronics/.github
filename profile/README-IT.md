> 🌐 **Lingua:** &nbsp; [🇬🇧 English](README.md) &nbsp;|&nbsp; [🇩🇪 Deutsch](README-DE.md) &nbsp;|&nbsp; [🇫🇷 Français](README-FR.md) &nbsp;|&nbsp; [🇳🇱 Nederlands](README-NL.md) &nbsp;|&nbsp; [🇪🇸 Español](README-ES.md) &nbsp;|&nbsp; 🇮🇹 Italiano &nbsp;|&nbsp; [🇵🇱 Polski](README-PL.md) &nbsp;|&nbsp; [🇨🇿 Čeština](README-CS.md) &nbsp;|&nbsp; [🇩🇰 Dansk](README-DA.md) &nbsp;|&nbsp; [🇳🇴 Norsk](README-NO.md) &nbsp;|&nbsp; [🇸🇪 Svenska](README-SV.md) &nbsp;|&nbsp; [🇭🇺 Magyar](README-HU.md) &nbsp;|&nbsp; [🇵🇹 Português](README-PT.md)

---

# 🚂 Open Source Model Railway Electronics

Benvenuto! Questa organizzazione contiene PCB open-source e moduli decoder per l'automazione del modellismo ferroviario.  
Tutto ciò che si trova qui è completamente riproducibile — tutti i progetti, il firmware e la documentazione sono liberamente disponibili.

Di seguito troverai progetti PCB e software per motori di scambio, decoder DCC per solenoidi, decoder DCC per servo, moduli di feedback di occupazione S88n, strisce LED, moduli relè, pannelli di controllo per plastici analogici e molto altro.

---

# 📘 Guide e Spiegazioni

Materiale di approfondimento per comprendere l'elettronica e i concetti utilizzati in questi progetti:

- [Scambi e Frog](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Points_and_frogs/points_and_frogs-EN.md)
- [Il Problema del Binario di Inversione](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/turning_loop_problem/turning_loop_problem-EN.md)
- [Automatizzare un Plastico](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/automize_a_layout/automize_a_layout-EN.md)

<br>

---

# 🛠️ Costruisci e Ordina i Tuoi PCB

Guide passo-passo per scaricare i file, effettuare ordini su JLCPCB e caricare il firmware:

- [Ordinare un PCB Nudo](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_bare_PCB/Ordering_bare_PCB-EN.md)
- [Ordinare un PCB Assemblato SMT](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_SMT_ASSEMBLED_PCB/Ordering_Assembled_PCBs_JLCPCB-EN.md)
- [Programmare il Tuo Decoder OS DCC](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Program_OS-DCC-Decoder/Program_OS-DCC-Decoder-EN.md)

<br>

---

# 💡 Tutorial: Crea il Tuo PCB

- [Crea la Tua Striscia LED Personalizzata](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_custom_LED_strip/makeYourOwnCustomLedStrip-EN.md)
- [Crea il Tuo Wire-Split](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_split/make_your_own_wire_split-EN.md)
- *(prossimamente)* Crea il Tuo Solder-Sleeper
- *(prossimamente)* Crea il Tuo Pannello di Controllo

<br>

---

# 🔀 Decoder DCC per Accessori

---

## OS-Duplex

L'OS-Duplex è un decoder DCC per accessori a doppio canale progettato per tutti i tipi di azionamento degli scambi — dai tradizionali solenoidi a doppia bobina ai motori di scambio e ai moduli relè per la polarizzazione del frog.

Ognuno dei due canali (A e B) può funzionare in modo indipendente o essere collegato all'altro. Ogni canale può operare come due uscite singole indipendenti (ciascuna con il proprio indirizzo DCC), oppure come un'unica uscita doppia combinata per uno scambio a doppia bobina o a motore.

I connettori relè opzionali consentono la polarizzazione del frog o l'azionamento di bobine e motori aggiuntivi. Il Duplex può anche pilotare un segnale a 4 luci con tutti i possibili aspetti.

![Anteprima](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/docs/image.png?raw=true)

📖 [Manuale](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/docs/Manual-IT.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex) &nbsp;|&nbsp; 📦 [Ultima Release](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/releases/latest)

<br>

---

## OS-Duplex-Servo

L'OS-Duplex-Servo è una variante dell'OS-Duplex con supporto aggiuntivo per **uscite a servomotore** (PWM standard a 3 pin). È ideale per motori di scambio a servo mantenendo la stessa architettura a doppio canale, le opzioni di espansione con relè e le capacità di controllo dei segnali dell'OS-Duplex base.

![Anteprima](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/hardware/OS-Duplex.png?raw=true)

📖 [Manuale](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/docs/Manual-IT.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo) &nbsp;|&nbsp; 📦 [Ultima Release](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/releases/latest)

<br>

---

## OS-Servo-Decoder-8

L'OS-Servo-Decoder-8 è un decoder DCC per accessori semplice e robusto progettato per pilotare fino a 8 servomotori. Supporta una configurazione flessibile tramite comandi DCC o pulsanti fisici, moduli relè di estensione opzionali per la polarizzazione del frog e controllo diretto tramite comandi DCC per accessori o funzioni locomotiva (F1–F8) — senza necessità di computer o programmatore CV.

![Anteprima](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/hardware/OS-Servo-Decoder-8.png?raw=true)

📖 [Manuale](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/docs/Manual-IT.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8) &nbsp;|&nbsp; 📦 [Ultima Release](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/releases/latest)

<br>

---

## OS-Solenoid-Decoder

L'OS-Solenoid-Decoder è un potente decoder DCC per accessori per la commutazione di scambi (motori di scambio), relè, disaccoppiatori e altri dispositivi a solenoide. Gestisce fino a 5 A e supporta quasi tutti i tipi di motori di scambio. È inoltre compatibile con i moduli relè OS per la completa polarizzazione del frog Electrofrog e Unifrog.

Caratteristiche principali:

- Fino a 8 uscite doppie per motori di scambio a doppia bobina
- Modalità di uscita multiple: Doppio Impulso, Impulso Singolo, Doppio Stabile, Singolo Stabile, Electrofrog
- Configurabile tramite comandi DCC — senza necessità di computer
- Supporto opzionale modulo CDU
- Espandibile con schede relè e transistor

![Anteprima](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/hardware/OS-Solenoid-Decoder.png?raw=true)

📖 [Manuale](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/docs/Manual-IT.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder) &nbsp;|&nbsp; 📦 [Ultima Release](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/releases/latest)

<br>

---

# 📡 Feedback e Rilevamento Occupazione

---

## OS-S88n (CS / GND / OPTO)

I moduli OS-S88n forniscono feedback S88n per plastici ferroviari DCC, consentendo il monitoraggio in tempo reale dell'occupazione dei blocchi e degli eventi del plastico. I dati vengono inviati alla centrale di comando o al software su PC (iTrain, Rocrail, Windigipet e altri).

Sono disponibili tre varianti:

- **OS-S88n GND** — rilevamento a contatto con la massa, ideale per plastici a 3 rotaie (stile Märklin)
- **OS-S88n CS** — rilevamento a sensore di corrente, adatto per plastici a 2 e 3 rotaie
- **OS-S88n OPTO** — ingressi optoisolati per rilevatori IR, sensori Hall e altri sensori esterni

Tutte le versioni sono collegabili a cascata tramite RJ-45 e supportano fino a 31 moduli in una singola catena.

![Anteprima](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/all.png?raw=true)

📖 [Manuale](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/Manual-IT.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n) &nbsp;|&nbsp; 📦 [Ultima Release](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/releases/latest)

<br>

---

# 🔌 Moduli Relè

---

## OS-relays

I moduli OS-relays sono schede relè a innesto progettate per funzionare insieme ai decoder OS DCC. Sono disponibili due tipi:

- **OS-General-Purpose-Relay** — relè monostabile doppio con contatti COM/NO/NC; adatto per la polarizzazione del frog (Electrofrog e Unifrog) e la commutazione generale di accessori
- **OS-Latching-Relay** — relè bistabile singolo che mantiene la posizione senza alimentazione continua; ideale per la polarizzazione Unifrog cablato in parallelo con il solenoide

Entrambi i tipi sono disponibili in versione THT e SMD e possono essere ordinati come pannelli separabili.

![Anteprima](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/all.png?raw=true)

📖 [Manuale](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/Manual-IT.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays) &nbsp;|&nbsp; 📦 [Ultima Release](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/releases/latest)

<br>

---

# 💡 Illuminazione

---

## OS-Lux-One

L'OS-Lux-One è una striscia LED modulare per materiale rotabile di plastici ferroviari digitali. Sostituisce numerose strisce per carrozze a lunghezza fissa con un'unica versione universale che può essere tagliata su misura e riutilizzata. Ogni sezione ha il proprio regolatore di corrente integrato per una luminosità stabile indipendentemente dalla tensione del binario, e la striscia funziona direttamente con l'alimentazione del binario DCC, MM o mfx. Adatta sia per la scala H0 che N.

![Anteprima](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/hardware/OS-Lux-One/OS-Lux-One.pdf?raw=true)

📖 [Manuale](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/docs/Manual-IT.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One) &nbsp;|&nbsp; 📦 [Ultima Release](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/releases/latest)

<br>

---

# 🎛️ Controllo Analogico del Plastico

---

## Analog-Layout-Control

Una gamma di moduli di controllo analogici per plastico progettati come elementi costitutivi modulari per pannelli di controllo personalizzati. Tutti i moduli utilizzano connettori JST standard per un cablaggio semplice e l'interoperabilità. Combinali per costruire qualsiasi cosa, dalla semplice commutazione cab-control alla configurazione completa degli itinerari tramite matrici a diodi.

I moduli di questa gamma includono:

- CAB Control Switch — assegna le sezioni di binario al Cab A o Cab B, con segnalazione LED
- Point Motor Switch — inverte la polarità per motori di scambio a 2 fili
- Solenoid Point Switch con feedback — controllo a impulso per azionamenti a doppia bobina
- Relè di Mantenimento — relè bistabile per la polarizzazione del frog o la sezionatura del binario
- Matrice a Diodi — scheda per l'impostazione degli itinerari per attivare più scambi con un singolo pulsante

![Anteprima](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/hardware/Analog-Layout-Control.png?raw=true)

📖 [Manuale](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/docs/Manual-IT.md) &nbsp;|&nbsp; 🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control) &nbsp;|&nbsp; 📦 [Ultima Release](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/releases/latest)

<br>

---

## Moduli per Binari di Inversione

I Moduli per Binari di Inversione gestiscono automaticamente l'inversione di polarità necessaria quando un treno entra o esce da un binario di inversione (binario a Y, anello di ritorno o piattaforma girevole). Il modulo rileva il cortocircuito causato da una locomotiva in inversione e corregge automaticamente la polarità, senza alcun intervento manuale.

![Anteprima](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/blob/main/hardware/turning-loop-modules.png?raw=true)

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules) &nbsp;|&nbsp; 📦 [Ultima Release](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/releases/latest)

<br>

---

# 🔩 Componenti Passivi e Cablaggio

---

## Wire-Splits

Le Wire-Split PCB sono schede di distribuzione passiva compatte per suddividere un singolo filo di ingresso in più uscite in modo ordinato. Semplificano la distribuzione dell'alimentazione del binario DCC o dei fili comuni a molti punti del plastico senza ingombranti giunzioni multiple.

![Anteprima](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/blob/main/hardware/Wire-Splits.png?raw=true)

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits) &nbsp;|&nbsp; 📦 [Ultima Release](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/releases/latest)

<br>

---

## Solder-Sleepers

I Solder-Sleepers sono traversine (dormenti) per binari basate su PCB, progettate per essere incollate nel piano di posa del binario. La traversina PCB consente di saldare direttamente la rotaia sulla scheda per una connessione elettrica e meccanica affidabile — ideale per binari costruiti a mano, lavori di diorama o ovunque si preferisca un giunto saldato fermo rispetto alle clips.

![Anteprima](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/blob/main/docs/Solder-sleepers.png?raw=true)

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers) &nbsp;|&nbsp; 📦 [Ultima Release](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/releases/latest)

<br>

---

# 🖥️ Software

---

## OS-software-tool

L'OS-software-tool è un'utilità PC per la configurazione e il test dei decoder OS DCC. Fornisce un'interfaccia grafica per operazioni che altrimenti richiederebbero sequenze manuali di comandi DCC.

🔗 [Repository](https://github.com/Open-Source-Model-Railway-Electronics/OS-software-tool)

<br>

---
