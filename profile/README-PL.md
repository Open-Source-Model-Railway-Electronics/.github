> 🌐 **Język:** &nbsp; [🇬🇧 English](README.md) &nbsp;|&nbsp; [🇩🇪 Deutsch](README-DE.md) &nbsp;|&nbsp; [🇫🇷 Français](README-FR.md) &nbsp;|&nbsp; [🇳🇱 Nederlands](README-NL.md) &nbsp;|&nbsp; [🇪🇸 Español](README-ES.md) &nbsp;|&nbsp; [🇮🇹 Italiano](README-IT.md) &nbsp;|&nbsp; 🇵🇱 Polski &nbsp;|&nbsp; [🇨🇿 Čeština](README-CS.md) &nbsp;|&nbsp; [🇩🇰 Dansk](README-DA.md) &nbsp;|&nbsp; [🇳🇴 Norsk](README-NO.md) &nbsp;|&nbsp; [🇸🇪 Svenska](README-SV.md) &nbsp;|&nbsp; [🇭🇺 Magyar](README-HU.md) &nbsp;|&nbsp; [🇵🇹 Português](README-PT.md)

---

# 🚂 Open Source Model Railway Electronics

Witaj! Ta organizacja zawiera otwartoźródłowe PCB i moduły dekoderów do automatyzacji kolejek modelowych.  
Wszystko tutaj jest w pełni odtwarzalne — wszystkie projekty, oprogramowanie układowe i dokumentacja są dostępne bezpłatnie.

Poniżej znajdziesz projekty PCB i oprogramowanie do silników zwrotnicowych, dekoderów solenoidowych DCC, dekoderów serwomechanizmów DCC, modułów zwrotnych zajętości S88n, pasków oświetlenia LED, modułów przekaźnikowych, analogowych paneli sterowania makietą i nie tylko.

---

# 📘 Przewodniki i wyjaśnienia

Materiały podstawowe do zrozumienia elektroniki i koncepcji stosowanych w tych projektach:

- [Zwrotnice i sercówki](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Points_and_frogs/points_and_frogs-EN.md)
- [Problem pętli zwrotnej](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/turning_loop_problem/turning_loop_problem-EN.md)
- [Automatyzacja makiety](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/automize_a_layout/automize_a_layout-EN.md)

<br>

---

# 🛠️ Buduj i zamawiaj własne PCB

Przewodniki krok po kroku do pobierania plików, składania zamówień w JLCPCB i wgrywania oprogramowania układowego:

- [Zamów nagie PCB](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_bare_PCB/Ordering_bare_PCB-EN.md)
- [Zamów PCB zmontowane metodą SMT](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Ordering_SMT_ASSEMBLED_PCB/Ordering_Assembled_PCBs_JLCPCB-EN.md)
- [Zaprogramuj dekoder OS DCC](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/Program_OS-DCC-Decoder/Program_OS-DCC-Decoder-EN.md)

<br>

---

# 💡 Samouczki: twórz własne PCB

- [Zrób własny pasek LED](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_custom_LED_strip/makeYourOwnCustomLedStrip-EN.md)
- [Zrób własny rozdzielacz przewodów](https://github.com/Open-Source-Model-Railway-Electronics/docs/blob/master/make_your_own_split/make_your_own_wire_split-EN.md)
- *(wkrótce)* Zrób własny podkład lutowniczy
- *(wkrótce)* Zrób własny panel sterowania

<br>

---

# 🔀 Dekodery akcesoriów DCC

---

## OS-Duplex

OS-Duplex to dwukanałowy dekoder akcesoriów DCC zaprojektowany do wszystkich typów napędów zwrotnicowych — od tradycyjnych solenoidów z podwójną cewką po silnikowe napędy zwrotnicowe i moduły przekaźnikowe do polaryzacji sercówek.

Każda z dwóch stron (A i B) może pracować niezależnie lub być ze sobą połączona. Każda strona może działać jako dwa niezależne pojedyncze wyjścia (każde z własnym adresem DCC) lub jako jedno połączone podwójne wyjście dla zwrotnicy z podwójną cewką lub napędem silnikowym.

Opcjonalne gniazda przekaźnikowe umożliwiają polaryzację sercówek lub napędzanie dodatkowych cewek i silników. OS-Duplex może również sterować semaforem 4-lampowym z każdym możliwym aspektem.

![Podgląd](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/docs/image.png?raw=true)

📖 [Instrukcja](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/blob/master/docs/Manual-PL.md) &nbsp;|&nbsp; 🔗 [Repozytorium](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex) &nbsp;|&nbsp; 📦 [Najnowsze wydanie](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex/releases/latest)

<br>

---

## OS-Duplex-Servo

OS-Duplex-Servo to wariant OS-Duplex z dodaną obsługą **wyjść serwomechanizmów** (standardowe 3-pinowe PWM). Idealny do serwomechanizmów zwrotnicowych przy zachowaniu tej samej dwukanałowej architektury, opcji rozszerzenia przekaźnikami i możliwości sterowania semaforami co podstawowy OS-Duplex.

![Podgląd](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/hardware/OS-Duplex.png?raw=true)

📖 [Instrukcja](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/blob/master/docs/Manual-PL.md) &nbsp;|&nbsp; 🔗 [Repozytorium](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo) &nbsp;|&nbsp; 📦 [Najnowsze wydanie](https://github.com/Open-Source-Model-Railway-Electronics/OS-Duplex-Servo/releases/latest)

<br>

---

## OS-Servo-Decoder-8

OS-Servo-Decoder-8 to prosty i niezawodny dekoder akcesoriów DCC zaprojektowany do sterowania nawet 8 serwomechanizmami. Obsługuje elastyczną konfigurację przez polecenia DCC lub fizyczne przyciski, opcjonalne moduły rozszerzenia przekaźnikowego do polaryzacji sercówek oraz bezpośrednie sterowanie za pomocą poleceń akcesoriów DCC lub funkcji lokomotywy (F1–F8) — bez potrzeby komputera ani programatora CV.

![Podgląd](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/hardware/OS-Servo-Decoder-8.png?raw=true)

📖 [Instrukcja](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/blob/main/docs/Manual-PL.md) &nbsp;|&nbsp; 🔗 [Repozytorium](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8) &nbsp;|&nbsp; 📦 [Najnowsze wydanie](https://github.com/Open-Source-Model-Railway-Electronics/OS-Servo-Decoder-8/releases/latest)

<br>

---

## OS-Solenoid-Decoder

OS-Solenoid-Decoder to wydajny dekoder akcesoriów DCC do przełączania zwrotnic (silników zwrotnicowych), przekaźników, odsprzęglaczy i innych urządzeń napędzanych solenoidem. Obsługuje do 5 A i współpracuje niemal z każdym typem silnika zwrotnicy. Kompatybilny jest również z modułami przekaźnikowymi OS do pełnej polaryzacji sercówek electrofrog i unifrog.

Główne cechy:

- Do 8 podwójnych wyjść dla silników zwrotnicowych z podwójną cewką
- Wiele trybów wyjściowych: Double Pulse, Single Pulse, Double Steady, Single Steady, Electrofrog
- Konfiguracja przez polecenia akcesoriów DCC — bez komputera
- Opcjonalna obsługa modułu CDU
- Rozszerzalne o płytki przekaźnikowe i tranzystorowe

![Podgląd](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/hardware/OS-Solenoid-Decoder.png?raw=true)

📖 [Instrukcja](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/blob/main/docs/Manual-PL.md) &nbsp;|&nbsp; 🔗 [Repozytorium](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder) &nbsp;|&nbsp; 📦 [Najnowsze wydanie](https://github.com/Open-Source-Model-Railway-Electronics/OS-Solenoid-Decoder/releases/latest)

<br>

---

# 📡 Sygnały zwrotne i detekcja zajętości

---

## OS-S88n (CS / GND / OPTO)

Moduły OS-S88n zapewniają sygnał zwrotny S88n dla makiet kolejowych DCC, umożliwiając monitorowanie w czasie rzeczywistym zajętości blokad i zdarzeń na makiecie. Dane są wysyłane do stacji sterującej lub oprogramowania na PC (iTrain, Rocrail, Windigipet i inne).

Dostępne są trzy warianty:

- **OS-S88n GND** — detekcja kontaktu z masą, idealna dla makiet 3-szynowych (w stylu Märklin)
- **OS-S88n CS** — detekcja prądu, odpowiednia dla makiet 2-szynowych i 3-szynowych
- **OS-S88n OPTO** — optoizolowane wejścia dla czujników IR, czujników Halla i innych zewnętrznych czujników

Wszystkie wersje można łączyć łańcuchowo przez RJ-45 i obsługują do 31 modułów w jednym łańcuchu.

![Podgląd](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/all.png?raw=true)

📖 [Instrukcja](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/blob/master/docs/Manual-PL.md) &nbsp;|&nbsp; 🔗 [Repozytorium](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n) &nbsp;|&nbsp; 📦 [Najnowsze wydanie](https://github.com/Open-Source-Model-Railway-Electronics/OS-S88n/releases/latest)

<br>

---

# 🔌 Moduły przekaźnikowe

---

## OS-relays

Moduły OS-relay to wtykowe płytki przekaźnikowe zaprojektowane do współpracy z dekoderami OS DCC. Dostępne są dwa typy:

- **OS-General-Purpose-Relay** — podwójny przekaźnik monostabilny ze stykami COM/NO/NC; odpowiedni do polaryzacji sercówek (electrofrog i unifrog) i ogólnego przełączania akcesoriów
- **OS-Latching-Relay** — pojedynczy przekaźnik bistabilny utrzymujący pozycję bez ciągłego zasilania; idealny do polaryzacji unifrog podłączonej równolegle z solenoidem

Oba typy są dostępne w wersjach THT i SMD i mogą być zamawiane jako panele do odrywania.

![Podgląd](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/all.png?raw=true)

📖 [Instrukcja](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/blob/main/docs/Manual-PL.md) &nbsp;|&nbsp; 🔗 [Repozytorium](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays) &nbsp;|&nbsp; 📦 [Najnowsze wydanie](https://github.com/Open-Source-Model-Railway-Electronics/OS-relays/releases/latest)

<br>

---

# 💡 Oświetlenie

---

## OS-Lux-One

OS-Lux-One to modułowy pasek oświetlenia LED do cyfrowego taboru kolejek modelowych. Zastępuje wiele pasków wagonowych o stałej długości jedną uniwersalną wersją, którą można przycinać na miarę i ponownie używać. Każda sekcja ma własny wbudowany regulator prądu zapewniający stabilną jasność niezależnie od napięcia torowego, a pasek zasilany jest bezpośrednio z napięcia torowego DCC, MM lub mfx. Odpowiedni dla skali H0 i N.

![Podgląd](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/hardware/OS-Lux-One/OS-Lux-One.pdf?raw=true)

📖 [Instrukcja](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/blob/main/docs/Manual-PL.md) &nbsp;|&nbsp; 🔗 [Repozytorium](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One) &nbsp;|&nbsp; 📦 [Najnowsze wydanie](https://github.com/Open-Source-Model-Railway-Electronics/OS-Lux-One/releases/latest)

<br>

---

# 🎛️ Analogowe sterowanie makietą

---

## Analog-Layout-Control

Szereg modułowych elementów składowych do analogowych paneli sterowania makietą. Wszystkie moduły używają standardowych złączy JST do łatwego okablowania i wzajemnej współpracy. Łącz je, aby zbudować wszystko — od prostego przełączania sterowników do pełnego ustawiania tras za pomocą matryc diodowych.

Moduły w tej serii to:

- CAB Control Switch — przypisuje odcinki torów do Cab A lub Cab B z sygnalizacją LED
- Point Motor Switch — odwraca biegunowość dla 2-przewodowych silników zwrotnicowych
- Solenoid Point Switch z sygnalizacją zwrotną — chwilowe sterowanie napędami z podwójną cewką
- Latching Relay — przekaźnik bistabilny do polaryzacji sercówek lub przełączania sekcji
- Diode Matrix — płytka do ustawiania tras umożliwiająca aktywację wielu zwrotnic jednym przyciskiem

![Podgląd](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/hardware/Analog-Layout-Control.png?raw=true)

📖 [Instrukcja](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/blob/main/docs/Manual-PL.md) &nbsp;|&nbsp; 🔗 [Repozytorium](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control) &nbsp;|&nbsp; 📦 [Najnowsze wydanie](https://github.com/Open-Source-Model-Railway-Electronics/Analog-Layout-Control/releases/latest)

<br>

---

## Moduły pętli zwrotnej

Moduły pętli zwrotnej automatycznie obsługują odwrócenie biegunowości wymagane, gdy pociąg wjeżdża lub wyjeżdża z pętli odwrotnej (wye, pętla balonowa lub obrotnica). Moduł wykrywa zwarcie spowodowane odwróconą lokomotywą i automatycznie koryguje biegunowość bez jakiejkolwiek ręcznej interwencji.

![Podgląd](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/blob/main/hardware/turning-loop-modules.png?raw=true)

🔗 [Repozytorium](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules) &nbsp;|&nbsp; 📦 [Najnowsze wydanie](https://github.com/Open-Source-Model-Railway-Electronics/turning-loop-modules/releases/latest)

<br>

---

# 🔩 Elementy bierne i okablowanie

---

## Wire-Splits

Wire-Split PCB to kompaktowe pasywne płytki dystrybucyjne do czystego podziału jednego przewodu wejściowego na wiele wyjść. Ułatwiają dystrybucję zasilania torowego DCC lub wspólnych przewodów do wielu punktów na makiecie bez nieporządnych wiązek połączeń.

![Podgląd](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/blob/main/hardware/Wire-Splits.png?raw=true)

🔗 [Repozytorium](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits) &nbsp;|&nbsp; 📦 [Najnowsze wydanie](https://github.com/Open-Source-Model-Railway-Electronics/Wire-Splits/releases/latest)

<br>

---

## Solder Sleepers

Solder Sleepers to oparte na PCB podkłady torowe (sleepery), zaprojektowane do wklejania w podsypkę torową. Podkład PCB umożliwia bezpośrednie przylutowanie szyny na płytce, zapewniając niezawodne połączenie elektryczne i mechaniczne — idealne do torów budowanych od podstaw, makiet dioramowych lub wszędzie tam, gdzie mocne połączenie lutowane jest preferowane zamiast klipsów.

![Podgląd](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/blob/main/docs/Solder-sleepers.png?raw=true)

🔗 [Repozytorium](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers) &nbsp;|&nbsp; 📦 [Najnowsze wydanie](https://github.com/Open-Source-Model-Railway-Electronics/Solder-sleepers/releases/latest)

<br>

---

# 🖥️ Oprogramowanie

---

## OS-Software-Tool

OS-Software-Tool to narzędzie PC do konfigurowania i testowania dekoderów OS DCC. Zapewnia graficzny interfejs do zadań, które w innym przypadku wymagałyby ręcznych sekwencji poleceń DCC.

🔗 [Repozytorium](https://github.com/Open-Source-Model-Railway-Electronics/OS-software-tool)

<br>

---
