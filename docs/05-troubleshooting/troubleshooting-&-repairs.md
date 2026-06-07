# Troubleshooting and Repairs

Failures in the UWT system are detected via the Panel PC (PPC) or by monitoring the DPGA/PA card telemetry displays.

## 7.1 Failure Detected by the User

The user can typically detect three main faults during operation:

### 1. Transceiver does not switch on
**Action:**
1. Check if **230 VAC** is connected to the transceiver unit **J1 connector** in the rear panel.
2. Verify the **circuit breaker** in the rear panel is not tripped (pushed down). If it is, push it up.
3. If the circuit breaker trips again, the AC-DC power supply is likely faulty and must be replaced (Section 8.3.2.1).
4. If 230 VAC is present but the unit remains off, check for **24 VDC** output from the power supply using a DVM.

### 2. The display is blank
**Action:**
* If the system is powered on but the screen is dark, the **PPC is faulty**. 
* **Replacement:** Follow instructions in Section 8.3.1 for PPC replacement.

### 3. No audio is heard
If no audio is heard in the headset/speaker and there is no noise display, check the following LRUs in order of priority:
1. **DPGA Card** (First Priority)
2. **PPC** (Second Priority)
3. **Hydrophone** (Third Priority)

---

## 7.2 Telemetry Failures

### DPGA Telemetry (Section 7.2)
If any item in the **DPGA telemetry display** is **RED**, the DPGA card has failed and must be replaced.

### PA Telemetry (Section 7.3)
Refer to the table below for Power Amplifier status:

| Condition | Meaning | Action |
| :--- | :--- | :--- |
| **HVPS entry is red** | HVPS card failure | Replace HVPS card |
| **Any PA telemetry is red** | PA card failure | Replace PA card |
| **LF entries red (during TX)** | LF projector failure | Replace LF Projector |
| **HF entries red (during TX)** | HF projector failure | Replace HF Projector |

---

> **WARNING:** Before disassembling any Line Replaceable Unit (LRU), switch the system OFF and disconnect the input electric power cable (AC or DC).
