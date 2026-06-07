# 4. Transceiver

The transceiver implements all UWT transmission and receiving functions, including the MMI (man machine interface). 

The transceiver dimensions are 540 mm width by 460 mm depth by 340 mm height with a weight of 48 kg. From the user’s viewpoint, the transceiver is the heart of DSIT’s White Pointer UWT.

## 4.1 Transceiver User Devices
The transceiver includes several user devices, including a headset with microphone, a microphone with PTT (push to talk switch) and a Morse key. 

The front panel is a PC (personal computer) and includes a touch screen, called a panel PC (PPC). Behind the PPC there is a chassis with electronic cards mounted on a backplane.

### Table 1: White Pointer (transceiver) front controls and connectors
| # | Type | Tag | Location and function |
| :--- | :--- | :--- | :--- |
| 1 | Button | PWR | The power button on the top left is red when off. When turned on, it flashes orange, then turns green. |
| 2 | Connector | Headset | The headset connector on the bottom right connects to the headphones. |
| 3 | Device | PTT | The PTT (push to talk) switch is located between the headphone and headset connector. |
| 4 | Connector | Morse | The Morse connector, on the left of headset, connects to the Morse keyer. |
| 5 | Connector | PTT MIC Tangent | Allows two full voice and listening devices to be connected simultaneously. |
| 6 | Connector | USB | Allows USB devices to be connected such as a mouse or keyboard. |
| 7 | Knob | Rotary | On the front right side; used to adjust parameters. |
| 8 | Knob | Speaker | The speaker volume control knob adjusts the speaker sound level. |
| 9 | Knob | Headphones| The headphones volume adjusts the headphones sound level. |

---

## 4.2 Connectors (Rear Panel)
The transceiver connectors are mounted on the front and rear panels. For transmission, a high voltage with weak current is used at UWT to reduce the transmission loss (TL). At the distribution box, this high voltage is reduced to the required value.

### Table 2: Transceiver (White Pointer) rear features and connectors
| # | Type | Tag | Location and function |
| :--- | :--- | :--- | :--- |
| 1 | Feature | Air Filters | At the rear, top and bottom, are rows of air filters for dust protection. |
| 2 | Switch | CB | The circuit breaker (CB) at the top right-hand side is a type of fuse. |
| 3 | Connector | J1 230VAC | J1 is for a power cable providing 230 VAC power. |
| 4 | Connector | J8 BAT | J8 is for connecting an emergency battery. |
| 5 | Connector | GND | Earth grounding connector located under J8. |
| 6 | Connector | J2 HMS MUTE | Connects UWT with HMS sonar to ensure they do not work simultaneously. |
| 7 | Connector | J5 OPR LAN | Operative LAN connector for external system communication over Ethernet. |
| 8 | Connector | J9 DPM MUTE | Connects UWT with depth measurement equipment (DPM). |
| 9 | Connector | J4 ACOUSTIC RX| Receives signal data from the UWT external hydrophone via the distribution box. |
| 10| Connector | J7 ACOUSTIC TX| Transmits signals to the UWT external transducer via the distribution box. |
| 11| Connector | J3 AUDIO | Allows earphones and amplified microphones from outside sources. |
| 12| Connector | J10 NMEA | National Marine Electronics Association Connector (RS232 + RS422). |
| 13| Connector | J6 MNT LAN | Used by the technician for maintenance and Ethernet connection. |

---

## 4.3 Electric Power Supplies
### AC Power Supply
The 230 VAC is connected to connector J1. It goes through a circuit breaker and an EMI (electromagnetic interference) filter. It is input to an AC/DC power supply that outputs **24 VDC** to all transceiver modules via connector P10. The 230 VAC is also connected to a heater used to control humidity via two contactors.

### DC Power Supply and Cooling
*   The system can operate with a 24 VDC supply instead of AC (connected via J8).
*   **Fans:** Three 12 VDC fans circulate air. Cold air is pumped in from the lower rear filtered openings; hot air is pushed out through the top. Fans are switched on/off based on internal air temperature.

---

## 4.4 Electronic Modules
The backplane is located on the rear side of the transceiver and mechanically holds all rear panel connectors. It contains the wiring to interconnect modules using Ethernet and supply 24 VDC power.

| Function / Element | Description |
| :--- | :--- |
| **Internal Ethernet** | Interconnected by 1 Mbps Ethernet switch in the backplane and PPC. |
| **Transmit (TX) path** |
