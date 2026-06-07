# Transceiver Unit Hardware

The transceiver is the heart of the DSIT White Pointer UWT. It implements all transmission and receiving functions, including the Man-Machine Interface (MMI).

## 4.1 Transceiver User Devices (Front Panel)
The front panel is a **Panel PC (PPC)** that includes a resistive touch screen and several physical activation devices:

### MMI Controls
*   **Power Button (SW1):** Switches the transceiver on/off. Features color LEDs (Red/Orange/Green) for status.
*   **Rotary Control Knob:** Used to adjust parameters. Pressing the knob saves selections.
*   **Speaker & Headphones Volume:** Dedicated knobs for adjusting audio output levels.

### Physical Connectors
*   **Headset Connector:** Bottom right; connects to headphones/mic.
*   **Morse Key Connector:** Connects to the Morse keyer.
*   **PTT MIC Tangent:** Allows two voice/listening devices to be connected simultaneously.
*   **USB Port:** Used for software downloads and connecting a mouse/keyboard.

---

## 4.2 Rear Panel Connectors
The rear panel handles all power and external sensor data. Key connectors include:

*   **J1 (230VAC):** Main power input.
*   **J8 (BAT):** For connecting an emergency battery.
*   **J4 (Acoustic RX):** Connects to the external hydrophone via the distribution box.
*   **J7 (Acoustic TX):** Connects to the external transducer via the distribution box.
*   **J5 (OPR LAN):** Operative LAN for communication with external systems.
*   **J2 (HMS MUTE):** Ensures the UWT and HMS sonar do not operate simultaneously.

---

## 4.4 Electronic Modules (Internal)
Inside the chassis, the system is divided into specific modular cards:

### 4.4.1 Backplane & Controller
The backplane contains the **Ethernet Switch (1 Mbps)** and the **Microcontroller**. It manages:
*   Sequential power distribution to minimize "rush in" current.
*   Climate control (monitoring temperature and humidity sensors).
*   Fan activation (12 VDC).

### 4.5 DPGA Card (Receive)
The Dynamically Programmable Gate Array card has two simultaneous receive channels:
*   **Channel 1:** Covers system bandwidth (1 – 60 kHz).
*   **Channel 2:** Distress frequency band (8 – 12 kHz) with Upper Side SSB.

### 4.6 Power Amplifier (PA) Card
A Class D amplifier with >90% efficiency. It contains two amplifiers: one for the LF projector and one for the HF projector.

### 4.7 High Voltage Power Supply (HVPS)
A DC-DC converter that steps up the 24 VDC input to a **240 VDC output** to power the PA card.

---

## 4.8 Panel PC (PPC) Specifications
The PPC is a rugged computer meeting military standards:
*   **CPU:** Intel 11th Gen Quad Core i7.
*   **OS:** Windows 11.
*   **Memory/Disk:** 16 GB RAM / 1 TB SSD.
*   **Display:** 10.4" resistive touch screen (1024 x 768 resolution).

