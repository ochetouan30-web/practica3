# Pràctica 3 – Sistema de Monitorització Ambiental amb micro:bit i ESP32

---

## 🎯 Objectiu

L’objectiu d’aquesta pràctica és desenvolupar un sistema intel·ligent capaç de monitoritzar variables ambientals (temperatura, humitat i llum) utilitzant una micro:bit i una ESP32, i reaccionar en temps real mitjançant un LED RGB.

A més, es busca integrar diferents tecnologies (Robolot, microcontroladors i sensors) i aplicar bones pràctiques d’organització i documentació en un projecte GitHub.

---

## 🧠 Descripció del sistema

El sistema implementat combina diversos dispositius electrònics per obtenir informació de l’entorn i actuar de forma automàtica.

Els sensors recullen dades ambientals que són processades pel microcontrolador. En funció dels valors obtinguts, el sistema activa diferents respostes visuals mitjançant un LED RGB.

Aquest tipus de sistema és aplicable a entorns reals com:

* Domòtica
* Control ambiental en habitacions
* Sistemes d’alerta bàsics

---

## 🏗️ Arquitectura del projecte

El projecte està estructurat en tres blocs principals:

### 🔹 Entrada (Sensors)

* Sensor de temperatura i humitat
* Sensor de llum

### 🔹 Processament

* micro:bit
* ESP32
* Programació amb Robolot

### 🔹 Sortida (Actuadors)

* LED RGB (indicació visual de l’estat)

---

## ⚙️ Funcionament detallat

El sistema funciona en un bucle continu seguint aquests passos:

1. **Inicialització**

   * Configuració dels pins d’entrada i sortida
   * Inicialització dels sensors
   * Configuració del LED RGB

2. **Lectura de dades**

   * Temperatura i humitat
   * Intensitat de llum

3. **Processament**

   * Comparació amb valors llindar predefinits
   * Interpretació de les condicions ambientals

4. **Resposta del sistema**

   * LED VERD → condicions normals
   * LED VERMELL → temperatura elevada
   * LED BLAU → baixa lluminositat

5. **Execució contínua**

   * El sistema repeteix el procés constantment en temps real

---

## 🧰 Materials utilitzats

* micro:bit
* ESP32 (kit de desenvolupament)
* Plataforma Robolot
* Sensor de temperatura i humitat
* Sensor de llum
* LED RGB
* Resistències
* Protoboard
* Cables de connexió (jumpers)
* Ordinador

---

## 🔌 Connexions (IMPORTANT per nota alta)

*(Aquí pots afegir una imatge dins la carpeta `doc/`)*

Exemple:

* Sensor temperatura → pin X
* Sensor llum → pin Y
* LED RGB:

  * Vermell → pin X
  * Verd → pin Y
  * Blau → pin Z

---

## ▶️ Execució del projecte

Per posar en funcionament el sistema:

1. Connectar la micro:bit i/o la ESP32 a l’ordinador
2. Obrir el projecte a Robolot
3. Verificar les connexions del circuit
4. Carregar el programa al dispositiu
5. Executar el sistema
6. Observar el comportament del LED RGB segons les condicions ambientals

---

## 📁 Estructura del repositori

```
practica3/
├── README.md
├── src/
│   └── main.ino
└── doc/
    ├── esquema.png
    ├── fotos/
    └── documentacio.pdf
```

---

## 📸 Documentació gràfica

Es poden trobar imatges i esquemes del muntatge a la carpeta `doc/`.

---

## 🚀 Possibles millores

* Afegir pantalla per mostrar dades en temps real
* Enviar dades via WiFi amb ESP32
* Crear una app o dashboard web
* Afegir més sensors

---

## 👥 Autors

* Nom Alumne 1
* Nom Alumne 2
* Nom Alumne 3

---

