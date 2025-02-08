# Common-Controller-EV-Charger

**About:**
I have been working on an EV charger(EVSE) V01 which can be used in both Mode 3 and Mode 4 Chargers. The Main controller contains peripheral which is supported in both the modes. Client just need to upload different firmware and connect the corresponding peripherals to the subsystems to allow it to run in specific mode.
THIS IS VERSION 1 OF THE PROJECT SO MORE ADVANCED VERSION WILL BE RELEASED SOON. SO STAY TUNED.

**Specification**
1. INPUT VOLTAGE - 12V
2. MODE - 3 AND 4
3. COMMUNICATIONS - RS485, CAN, UART, SPI, ETHERNET AND I2C
4. OPERATING TEMPERATUR - 0 TO 55 DEG C
5. STORAGE TEMPERATURE - -20 TO 65 DEG C
6. INDICATIONS - CHARGING STATUS - IDLE, CHARGING, AVAILABEL AND FAULTS
7. NETWORK - GPS, LTE, WIFI, BLE, LAN
8. PERIPHERALS - DISPLAY, TEMPERATURE SENSOR, RTC, RELAYS, PWN LED, RFID, BUZZER, NTC TEMP SENSOR, PT1000 TEMP SENSOR, DIGITAL OUTPUTS AND INPUTS.
9. REVERSE POLARITY PROTECTION, EARTH FAULT DETECTION.

1. Main Controller PCB: This has all the interfaces required for AC and DC chargers. Renesas 6M3 Family microcontroller is selected for Master controller and an ESP is provided to upload and retrieve the datas from the cloud.


Open-source project Related to the AC/DC EV charger. 

The project contains the :
Schematic
PCB
BOM
CAD
Gerber
Photos
Documentations
Wiring Diagram

Product Specs will be updated soon
