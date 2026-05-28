> 🌐 **Idioma:** &nbsp; [🇬🇧 English](README.md) &nbsp;|&nbsp; [🇩🇪 Deutsch](README-DE.md) &nbsp;|&nbsp; [🇫🇷 Français](README-FR.md) &nbsp;|&nbsp; [🇳🇱 Nederlands](README-NL.md) &nbsp;|&nbsp; [🇪🇸 Español](README-ES.md) &nbsp;|&nbsp; [🇮🇹 Italiano](README-IT.md) &nbsp;|&nbsp; [🇵🇱 Polski](README-PL.md) &nbsp;|&nbsp; [🇨🇿 Čeština](README-CS.md) &nbsp;|&nbsp; [🇩🇰 Dansk](README-DA.md) &nbsp;|&nbsp; [🇳🇴 Norsk](README-NO.md) &nbsp;|&nbsp; [🇸🇪 Svenska](README-SV.md) &nbsp;|&nbsp; [🇭🇺 Magyar](README-HU.md) &nbsp;|&nbsp; 🇵🇹 Português

---

# 🚂 Open Source Model Railway Electronics

Bem-vindo! Esta organização contém PCBs e módulos decoder de código aberto para automação de ferrovias em miniatura.  
Tudo aqui é totalmente reproduzível — todos os desenhos, firmware e documentação estão disponíveis livremente.

Abaixo encontrará desenhos de PCB e software para motores de agulha, decoders solenóide DCC, decoders servo DCC, módulos de retorno de ocupação S88n, tiras de iluminação LED, módulos de relé, painéis de controlo analógico e muito mais.

---

# 📘 Guias e Explicações

Leitura de fundo para compreender a electrónica e os conceitos utilizados nestes projectos:

- [Agulhas e Frogs](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Points_and_frogs/points_and_frogs-EN.md)
- [O Problema do Laço de Inversão](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/turning_loop_problem/turning_loop_problem-EN.md)
- [Automatizar uma Maquete](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/automize_a_layout/automize_a_layout-EN.md)

<br>

---

# 🛠️ Construa e Encomende as Suas Próprias PCBs

Guias passo a passo para descarregar ficheiros, fazer encomendas na JLCPCB e gravar firmware:

- [Encomendar uma PCB Nua](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_bare_PCB/Ordering_bare_PCB-EN.md)
- [Encomendar uma PCB com Montagem SMT](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_SMT_ASSEMBLED_PCB/Ordering_Assembled_PCBs_JLCPCB-EN.md)
- [Programar o Seu Decoder OS DCC](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Program_OS-DCC-Decoder/Program_OS-DCC-Decoder-EN.md)

<br>

---

# 💡 Tutoriais para Criar as Suas Próprias PCBs

- [Criar a Sua Própria Tira LED Personalizada](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_custom_LED_strip/makeYourOwnCustomLedStrip-EN.md)
- [Criar o Seu Próprio Wire-Split](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_split/make_your_own_wire_split-EN.md)
- *(em breve)* Criar os Seus Próprios Solder-sleepers
- *(em breve)* Criar o Seu Próprio Painel de Controlo

<br>

---

# 🔀 Decoders de Acessórios DCC

---

## OS-Duplex

O OS-Duplex é um decoder de acessórios DCC duplo concebido para todos os tipos de accionamento de agulhas — desde solenóides de bobine dupla tradicionais a motores de agulha por motor e módulos de relé para polarização de frog.

Cada um dos dois lados (A e B) pode funcionar de forma independente ou estar ligado ao outro. Cada lado pode actuar como duas saídas simples independentes (cada uma com o seu próprio endereço DCC), ou como uma saída dupla combinada para uma agulha de bobine dupla ou accionamento por motor.

Os sockets de relé opcionais permitem a polarização de frog ou o accionamento de bobines e motores adicionais. O Duplex também pode accionar um sinal de 4 lâmpadas com todos os aspectos possíveis.

![Pré-visualização](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/docs/image.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/docs/Manual-PT.md) &nbsp;|&nbsp; 🔗 [Repositório](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex) &nbsp;|&nbsp; 📦 [Última Versão](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/releases/latest)

<br>

---

## OS-Duplex-Servo

O OS-Duplex-Servo é uma variante do OS-Duplex com suporte adicionado para **saídas de servomotor** (PWM de 3 pinos padrão). É ideal para motores de agulha accionados por servo, mantendo a mesma arquitectura de canal duplo, opções de expansão de relé e capacidades de controlo de sinal do OS-Duplex base.

![Pré-visualização](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/hardware/OS-Duplex.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/docs/Manual-PT.md) &nbsp;|&nbsp; 🔗 [Repositório](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo) &nbsp;|&nbsp; 📦 [Última Versão](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/releases/latest)

<br>

---

## OS-Servo-Decoder-8

O OS-Servo-Decoder-8 é um decoder de acessórios DCC simples e robusto concebido para accionar até 8 servomotores. Suporta configuração flexível por comandos DCC ou botões físicos, módulos de extensão de relé opcionais para polarização de frog e controlo directo por comandos de acessório DCC ou funções de locomotiva (F1–F8) — sem necessidade de computador ou programador de CV.

![Pré-visualização](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/hardware/OS-Servo-Decoder-8.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/docs/Manual-PT.md) &nbsp;|&nbsp; 🔗 [Repositório](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8) &nbsp;|&nbsp; 📦 [Última Versão](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/releases/latest)

<br>

---

## OS-Solenoid-Decoder

O OS-Solenoid-Decoder é um decoder de acessórios DCC potente para comutar agulhas (motores de agulha), relés, desacopladores e outros dispositivos accionados por solenóide. Suporta até 5 A e é compatível com praticamente qualquer tipo de motor de agulha. É também compatível com módulos de relé OS para polarização completa de frog electrofrog e unifrog.

Características principais:

- Até 8 saídas duplas para motores de agulha de bobine dupla
- Múltiplos modos de saída: Impulso Duplo, Impulso Simples, Contínuo Duplo, Contínuo Simples, Electrofrog
- Configurável por comandos de acessório DCC — sem necessidade de computador
- Suporte opcional de módulo CDU
- Expansível com placas de relé e transístor

![Pré-visualização](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/hardware/OS-Solenoid-Decoder.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/docs/Manual-PT.md) &nbsp;|&nbsp; 🔗 [Repositório](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder) &nbsp;|&nbsp; 📦 [Última Versão](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/releases/latest)

<br>

---

# 📡 Retorno e Detecção de Ocupação

---

## OS-S88n (CS / GND / OPTO)

Os módulos OS-S88n fornecem retorno S88n para ferrovias em miniatura DCC, permitindo a monitorização em tempo real da ocupação de blocos e eventos da maquete. Os dados são enviados para a sua central de comando ou software em PC (iTrain, Rocrail, Windigipet e outros).

Estão disponíveis três variantes:

- **OS-S88n GND** — detecção por contacto com massa, ideal para maquetes de 3 carris (tipo Märklin)
- **OS-S88n CS** — detecção por detecção de corrente, adequada para maquetes de 2 e 3 carris
- **OS-S88n OPTO** — entradas com isolamento óptico para detectores IR, sensores Hall e outros sensores externos

Todas as versões são encadeáveis por RJ-45 e suportam até 31 módulos numa única cadeia.

![Pré-visualização](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/all.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/Manual-PT.md) &nbsp;|&nbsp; 🔗 [Repositório](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n) &nbsp;|&nbsp; 📦 [Última Versão](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/releases/latest)

<br>

---

# 🔌 Módulos de Relé

---

## OS-relays

Os módulos OS-relays são placas de relé de encaixe concebidas para trabalhar em conjunto com decoders OS DCC. Estão disponíveis dois tipos:

- **OS-General-Purpose-Relay** — relé monostável duplo com contactos COM/NO/NC; adequado para polarização de frog (electrofrog e unifrog) e comutação geral de acessórios
- **OS-Latching-Relay** — relé bistável simples que mantém a sua posição sem alimentação contínua; ideal para polarização unifrog ligado em paralelo com o solenóide

Ambos os tipos estão disponíveis em versões THT e SMD e podem ser encomendados em painéis separáveis.

![Pré-visualização](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/all.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/Manual-PT.md) &nbsp;|&nbsp; 🔗 [Repositório](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays) &nbsp;|&nbsp; 📦 [Última Versão](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/releases/latest)

<br>

---

# 💡 Iluminação

---

## OS-Lux-One

O OS-Lux-One é uma tira de iluminação LED modular para material circulante de ferrovia em miniatura digital. Substitui múltiplas tiras de carruagem de comprimento fixo por uma versão universal que pode ser cortada ao tamanho certo e reutilizada. Cada secção tem o seu próprio regulador de corrente integrado para brilho estável independentemente da tensão de via, e a tira funciona directamente com alimentação de via DCC, MM ou mfx. Adequada para as escalas H0 e N.

![Pré-visualização](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/hardware/OS-Lux-One/OS-Lux-One.pdf?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/docs/Manual-PT.md) &nbsp;|&nbsp; 🔗 [Repositório](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One) &nbsp;|&nbsp; 📦 [Última Versão](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/releases/latest)

<br>

---

# 🎛️ Controlo Analógico de Maquete

---

## Analog-Layout-Control

Um conjunto de módulos de controlo analógico de maquete concebidos como blocos de construção modulares para painéis de controlo personalizados. Todos os módulos utilizam conectores JST normalizados para facilitar a cablagem e a interoperabilidade. Combine-os para construir desde simples comutação por manípulo até à definição completa de itinerários por matrizes de díodos.

Os módulos nesta gama incluem:

- CAB Control Switch — atribui secções de via ao Manípulo A ou B, com indicação por LED
- Point Motor Switch — inverte a polaridade para motores de agulha de 2 fios
- Solenoid Point Switch com retorno — controlo momentâneo para accionamentos de bobine dupla
- Latching Relay — relé bistável para polarização de frog ou comutação de secções
- Diode Matrix — placa de definição de itinerários para activar múltiplas agulhas com um único botão

![Pré-visualização](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/hardware/Analog-Layout-Control.png?raw=true)

📖 [Manual](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/docs/Manual-PT.md) &nbsp;|&nbsp; 🔗 [Repositório](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control) &nbsp;|&nbsp; 📦 [Última Versão](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/releases/latest)

<br>

---

## Módulos de Laço de Inversão

Os Módulos de Laço de Inversão tratam automaticamente a inversão de polaridade necessária quando um comboio entra ou sai de um laço de inversão (triângulo de reversão, laço ou placa giratória). O módulo detecta o curto-circuito causado por uma locomotiva invertida e corrige a polaridade automaticamente, sem qualquer intervenção manual.

![Pré-visualização](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/blob/main/hardware/turning-loop-modules.png?raw=true)

🔗 [Repositório](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules) &nbsp;|&nbsp; 📦 [Última Versão](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/releases/latest)

<br>

---

# 🔩 Componentes Passivos e Cablagem

---

## Wire-Splits

As PCBs Wire-Split são placas de distribuição passiva compactas para dividir um fio de entrada de forma limpa em múltiplas saídas. Facilitam a distribuição de alimentação de via DCC ou fios comuns a muitos pontos da sua maquete sem feixes de junções desordenados.

![Pré-visualização](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/blob/main/hardware/Wire-Splits.png?raw=true)

🔗 [Repositório](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits) &nbsp;|&nbsp; 📦 [Última Versão](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/releases/latest)

<br>

---

## Solder Sleepers

Os Solder Sleepers são travessas de via baseadas em PCB concebidas para serem coladas no leito de via. A travessa PCB permite-lhe soldar o carril directamente na placa para uma ligação eléctrica e mecânica fiável — ideal para via construída de raiz, dioramas ou em qualquer situação onde uma junta soldada firme seja preferível a grampos.

![Pré-visualização](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/blob/main/docs/Solder-sleepers.png?raw=true)

🔗 [Repositório](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers) &nbsp;|&nbsp; 📦 [Última Versão](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/releases/latest)

<br>

---

# 🖥️ Software

---

## OS-Software-Tool

O OS-Software-Tool é um utilitário de PC para configurar e testar decoders OS DCC. Fornece uma interface gráfica para tarefas que de outra forma exigiriam sequências manuais de comandos DCC.

🔗 [Repositório](https://github.com/Open-Source-Model-Railway-Electronics/OS-software-tool)

<br>

---
