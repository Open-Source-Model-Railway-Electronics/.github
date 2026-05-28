> 🌐 **Langue :** &nbsp; [🇬🇧 English](README.md) &nbsp;|&nbsp; [🇩🇪 Deutsch](README-DE.md) &nbsp;|&nbsp; 🇫🇷 Français &nbsp;|&nbsp; [🇳🇱 Nederlands](README-NL.md) &nbsp;|&nbsp; [🇪🇸 Español](README-ES.md) &nbsp;|&nbsp; [🇮🇹 Italiano](README-IT.md) &nbsp;|&nbsp; [🇵🇱 Polski](README-PL.md) &nbsp;|&nbsp; [🇨🇿 Čeština](README-CS.md) &nbsp;|&nbsp; [🇩🇰 Dansk](README-DA.md) &nbsp;|&nbsp; [🇳🇴 Norsk](README-NO.md) &nbsp;|&nbsp; [🇸🇪 Svenska](README-SV.md) &nbsp;|&nbsp; [🇭🇺 Magyar](README-HU.md) &nbsp;|&nbsp; [🇵🇹 Português](README-PT.md)

---

# 🚂 Électronique Open Source pour Trains Miniatures

Bienvenue ! Cette organisation regroupe des PCB et modules décodeurs open source pour l'automatisation des réseaux de trains miniatures.  
Tout est librement reproductible — designs, firmware et documentation sont entièrement disponibles.

Vous trouverez ici des circuits imprimés et logiciels pour moteurs d'aiguille, décodeurs DCC solénoïde, décodeurs DCC servo, modules de rétrosignalisation S88n, rubans LED, modules relais, commandes analogiques et bien plus.

---

# 📘 Guides & Explications

Lecture de fond pour comprendre l'électronique et les concepts utilisés dans ces projets :

- [Aiguillages & Cœurs d'aiguille](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Points_and_frogs/points_and_frogs-EN.md)
- [Le problème de la boucle de retournement](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/turning_loop_problem/turning_loop_problem-EN.md)
- [Automatiser un réseau](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/automize_a_layout/automize_a_layout-EN.md)

<br>

---

# 🛠️ Construire & Commander vos propres PCB

Guides pas à pas pour télécharger les fichiers, passer commande chez JLCPCB et flasher le firmware :

- [Commander un PCB nu](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_bare_PCB/Ordering_bare_PCB-EN.md)
- [Commander un PCB assemblé SMT](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_SMT_ASSEMBLED_PCB/Ordering_Assembled_PCBs_JLCPCB-EN.md)
- [Programmer votre décodeur OS DCC](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Program_OS-DCC-Decoder/Program_OS-DCC-Decoder-FR.md)

<br>

---

# 💡 Tutoriels — Créez vos propres PCB

- [Créer son propre ruban LED personnalisé](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_custom_LED_strip/makeYourOwnCustomLedStrip-EN.md)
- [Créer son propre répartiteur de fils](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_split/make_your_own_wire_split-EN.md)
- *(à venir)* Créer ses propres traverses à souder
- *(à venir)* Créer son propre pupitre de commande

<br>

---

# 🔀 Décodeurs DCC Accessoires

---

## OS-Duplex

L'OS-Duplex est un décodeur DCC accessoire double canal conçu pour tous les types de moteurs d'aiguille — des solénoïdes à double bobine classiques aux moteurs électriques et modules relais pour la polarisation du cœur d'aiguille.

Chacun des deux côtés (A et B) peut fonctionner indépendamment ou être couplé. Chaque côté peut être configuré comme deux sorties indépendantes (chacune avec sa propre adresse DCC) ou comme une sortie double combinée pour un solénoïde à double bobine ou un moteur d'aiguille.

Des prises relais optionnelles permettent la polarisation du cœur ou le pilotage de bobines et moteurs supplémentaires. Le Duplex peut également piloter un signal à 4 feux avec tous les aspects possibles.

![Aperçu](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/docs/image.png?raw=true)

📖 [Manuel (FR)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/docs/Manual-FR.md) &nbsp;|&nbsp; 🔗 [Dépôt](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex) &nbsp;|&nbsp; 📦 [Dernière version](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/releases/latest)

<br>

---

## OS-Duplex-Servo

L'OS-Duplex-Servo est une variante de l'OS-Duplex avec prise en charge ajoutée des **sorties moteur servo** (PWM 3 broches standard). Il est idéal pour les moteurs d'aiguille à commande servo, tout en conservant la même architecture double canal, les options d'extension relais et les capacités de commande de signaux que l'OS-Duplex de base.

![Aperçu](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/hardware/OS-Duplex.png?raw=true)

📖 [Manuel (FR)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/docs/Manual-FR.md) &nbsp;|&nbsp; 🔗 [Dépôt](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo) &nbsp;|&nbsp; 📦 [Dernière version](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/releases/latest)

<br>

---

## OS-Servo-Decoder-8

L'OS-Servo-Decoder-8 est un décodeur DCC accessoire simple et robuste conçu pour piloter jusqu'à 8 servomoteurs. Il supporte une configuration flexible via commandes DCC ou boutons physiques, des modules d'extension relais optionnels pour la polarisation du cœur, et un contrôle direct par commandes DCC accessoire ou fonctions locomotive (F1–F8) — sans ordinateur ni programmateur CV.

![Aperçu](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/hardware/OS-Servo-Decoder-8.png?raw=true)

📖 [Manuel (FR)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/docs/Manual-FR.md) &nbsp;|&nbsp; 🔗 [Dépôt](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8) &nbsp;|&nbsp; 📦 [Dernière version](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/releases/latest)

<br>

---

## OS-Solenoid-Decoder

L'OS-Solenoid-Decoder est un décodeur DCC accessoire puissant pour la commutation des moteurs d'aiguille, relais, dételeurs et autres appareils à solénoïde. Il gère jusqu'à 5 A et supporte presque tous les types de moteurs d'aiguille. Il est également compatible avec les modules relais OS pour la polarisation complète des cœurs Electrofrog et Unifrog.

Caractéristiques principales :

- Jusqu'à 8 sorties doubles pour moteurs d'aiguille à double bobine
- Plusieurs modes de sortie : Double impulsion, Impulsion simple, Continu double, Continu simple, Electrofrog
- Configuration par commandes DCC accessoire — aucun ordinateur requis
- Prise en charge optionnelle de module CDU
- Extensible avec des cartes relais et transistors

![Aperçu](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/hardware/OS-Solenoid-Decoder.png?raw=true)

📖 [Manuel (FR)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/docs/Manual-FR.md) &nbsp;|&nbsp; 🔗 [Dépôt](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder) &nbsp;|&nbsp; 📦 [Dernière version](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/releases/latest)

<br>

---

# 📡 Rétrosignalisation & Détection d'occupation

---

## OS-S88n (CS / GND / OPTO)

Les modules OS-S88n assurent la rétrosignalisation S88n pour les réseaux DCC, permettant la surveillance en temps réel de l'occupation des cantons et des événements sur le réseau. Les données sont envoyées à la centrale ou au logiciel PC (iTrain, Rocrail, Windigipet, etc.).

Trois variantes sont disponibles :

- **OS-S88n GND** — détection par contact à la masse, idéal pour les réseaux 3 rails (style Märklin)
- **OS-S88n CS** — détection par capteur de courant, adapté aux réseaux 2 et 3 rails
- **OS-S88n OPTO** — entrées opto-isolées pour détecteurs IR, capteurs Hall et autres capteurs externes

Toutes les versions sont chaînables via RJ-45 et supportent jusqu'à 31 modules dans une chaîne.

![Aperçu](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/all.png?raw=true)

📖 [Manuel (FR)](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/Manual-FR.md) &nbsp;|&nbsp; 🔗 [Dépôt](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n) &nbsp;|&nbsp; 📦 [Dernière version](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/releases/latest)

<br>

---

# 🔌 Modules Relais

---

## OS-relays

Les modules relais OS sont des cartes relais enfichables conçues pour fonctionner avec les décodeurs DCC OS. Deux types sont disponibles :

- **OS-General-Purpose-Relay** — relais monostable double avec contacts COM/NO/NC ; adapté à la polarisation du cœur (Electrofrog et Unifrog) et à la commutation d'accessoires
- **OS-Latching-Relay** — relais bistable simple qui maintient sa position sans alimentation continue ; idéal pour la polarisation Unifrog câblé en parallèle sur le solénoïde

Les deux types sont disponibles en versions THT et SMD et peuvent être commandés en panneaux sécables.

![Aperçu](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/all.png?raw=true)

📖 [Manuel (FR)](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/Manual-FR.md) &nbsp;|&nbsp; 🔗 [Dépôt](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays) &nbsp;|&nbsp; 📦 [Dernière version](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/releases/latest)

<br>

---

# 💡 Éclairage

---

## OS-Lux-One

L'OS-Lux-One est un ruban LED modulaire pour le matériel roulant de trains miniatures numériques. Il remplace plusieurs rubans de longueur fixe par une version universelle qui peut être coupée sur mesure et réutilisée. Chaque section dispose de son propre régulateur de courant intégré pour une luminosité stable quelle que soit la tension de voie. Fonctionne directement avec la tension DCC, MM ou mfx. Compatible H0 et N.

![Aperçu](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/hardware/OS-Lux-One/OS-Lux-One.pdf?raw=true)

📖 [Manuel (FR)](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/docs/Manual-FR.md) &nbsp;|&nbsp; 🔗 [Dépôt](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One) &nbsp;|&nbsp; 📦 [Dernière version](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/releases/latest)

<br>

---

# 🎛️ Commande Analogique du Réseau

---

## Analog-Layout-Control

Une gamme de modules de commande analogique conçus comme éléments modulaires pour des pupitres de commande personnalisés. Tous les modules utilisent des connecteurs JST standard pour un câblage facile et une interopérabilité totale. Combinés, ils permettent de construire des pupitres allant de la simple commutation de cab à la mise en route complète via matrices à diodes.

Modules disponibles dans cette gamme :

- Commutateur CAB — assigne des sections de voie au Cab A ou B, avec retour visuel LED
- Commutateur moteur d'aiguille — inverse la polarité pour les moteurs 2 fils
- Commutateur solénoïde avec retour — commande momentanée pour les moteurs à double bobine
- Relais bistable — pour la polarisation du cœur ou la commutation de sections
- Matrice à diodes — carte de mise en route pour actionner plusieurs aiguilles d'un seul bouton

![Aperçu](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/hardware/Analog-Layout-Control.png?raw=true)

📖 [Manuel (FR)](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/docs/Manual-FR.md) &nbsp;|&nbsp; 🔗 [Dépôt](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control) &nbsp;|&nbsp; 📦 [Dernière version](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/releases/latest)

<br>

---

## Modules de Boucle de Retournement

Les modules de boucle de retournement gèrent automatiquement l'inversion de polarité nécessaire lorsqu'un train entre dans ou sort d'une boucle de retournement (triangle, ballon ou plaque tournante). Le module détecte le court-circuit provoqué par la locomotive inversée et corrige automatiquement la polarité — sans intervention manuelle.

![Aperçu](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/blob/main/hardware/turning-loop-modules.png?raw=true)

🔗 [Dépôt](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules) &nbsp;|&nbsp; 📦 [Dernière version](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/releases/latest)

<br>

---

# 🔩 Composants Passifs & Câblage

---

## Wire-Splits

Les Wire-Split sont des PCB de distribution passifs compacts permettant de diviser proprement un fil d'entrée en plusieurs sorties. Ils facilitent la distribution de l'alimentation DCC ou des fils communs vers de nombreux points du réseau, sans jonctions désordonnées.

![Aperçu](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/blob/main/hardware/Wire-Splits.png?raw=true)

🔗 [Dépôt](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits) &nbsp;|&nbsp; 📦 [Dernière version](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/releases/latest)

<br>

---

## Traverses à Souder

Les traverses à souder sont des traverses de voie à base de PCB conçues pour être collées dans le ballast. La traverse PCB permet de souder directement le rail sur la carte pour une connexion électrique et mécanique fiable — idéale pour la pose de voie artisanale, les dioramas ou partout où une jonction soudée ferme est préférable aux clips.

![Aperçu](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/blob/main/docs/Solder-sleepers.png?raw=true)

🔗 [Dépôt](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers) &nbsp;|&nbsp; 📦 [Dernière version](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/releases/latest)

<br>

---

# 🖥️ Logiciel

---

## OS-Software-Tool

L'OS-Software-Tool est un utilitaire PC pour configurer et tester les décodeurs OS DCC. Il fournit une interface graphique pour les tâches qui nécessiteraient autrement des séquences de commandes DCC manuelles.

🔗 [Dépôt](https://github.com/Open-Source-Model-Railway-Electronics/OS-software-tool)

<br>

---
