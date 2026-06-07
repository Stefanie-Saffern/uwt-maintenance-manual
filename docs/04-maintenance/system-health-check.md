# System Health Checks

No routine preventive maintenance is required for the UWT system. However, it is highly recommended to perform regular system health checks to ensure operational readiness.

---

## 6.1 System Health Check in the Harbor

**Frequency:** Three hours before sailing or every two months (whichever is earlier).  
**Personnel:** Level 1 maintainer (e.g., Sonar Operator or Onboard Technician).

### Procedure Checklist:
1. [ ] **System Power:** Switch on the system and confirm initialization.
2. [ ] **Noise Mode:** Open **Noise Mode** and verify that a typical noise spectrum is displayed on the PPC.
3. [ ] **Audio Verification:** Listen to the headphones and speaker; verify that typical acoustic noise audio is audible.
4. [ ] **DPGA Telemetry Check:** 
    *   Open the telemetry **DPGA display** format. 
    *   Verify that all health status indicators are **GREEN (OK)**.
5. [ ] **PA Telemetry (8 kHz):** 
    *   Open the telemetry **PA display** format. 
    *   Send an audio message at **8 kHz**, speaking into the microphone for 10 seconds. 
    *   Verify all health status data remains **GREEN**.
6. [ ] **PA Telemetry (37 kHz):** 
    *   Open the telemetry **PA display** format. 
    *   Send an audio message at **37 kHz**, speaking into the microphone for 10 seconds. 
    *   Verify all health status data remains **GREEN**.

---

## 6.2 System Health Checks at Sea

Health checks at sea are required to ensure the transducers are performing correctly under operational conditions.

**Frequency:** Every 24 hours while at sea.  
**Operational Condition:** Must be performed in water depths greater than **50 meters**.  
**Personnel:** Level 1 maintainer.

### Procedure:
The task steps are identical to the **Harbor Health Check** (Steps 1–6 above). 

> **Note:** A Level 1 Maintainer (Sonar Operator or Onboard Technician) must perform this task continually every 24 hours while the vessel is at sea.

---

## Maintenance Summary Table

| Check Type | Frequency | Water Depth | Requirement |
| :--- | :--- | :--- | :--- |
| **Harbor Check** | 3hrs before sail / 2 Months | Any | All Telemetry GREEN |
| **At-Sea Check** | Every 24 Hours | > 50 Meters | All Telemetry GREEN |
