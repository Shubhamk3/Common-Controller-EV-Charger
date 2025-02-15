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
Schematic files(Altium) - [EVSE_SCH_V01.zip](https://github.com/user-attachments/files/18811699/EVSE_SCH_V01.zip)

PCB file(Altium) - [EVSE_PCB_V01.zip](https://github.com/user-attachments/files/18811701/EVSE_PCB_V01.zip)

Pinout - ![R6M3 PINMAP](https://github.com/user-attachments/assets/f7321385-fa85-4e28-bdb1-4ce601d19742)

Photos - ![3D_FRONT_TILT](https://github.com/user-attachments/assets/18112390-a0a0-4e17-93d5-39290c5d74f0)
          ![3D_TOP](https://github.com/user-attachments/assets/13ad9cd8-ec1c-4a33-a5a6-714f78d5707b)
         <img width="687" alt="top layer_SS" src="https://github.com/user-attachments/assets/960eb9d4-a8ab-4454-a921-9f8a11b5f5b5" />
          <img width="495" alt="Top legend SS" src="https://github.com/user-attachments/assets/f07d0c6c-56d0-40ae-8db4-0ab95ed42cf1" />
          ![3D_BACK_TILT](https://github.com/user-attachments/assets/90539273-2068-4ef2-bf72-f63ae5cd1154)

Documentations - [AC_DC CHARGER_PCB_DESIGN PDF.pdf](https://github.com/user-attachments/files/18811703/AC_DC.CHARGER_PCB_DESIGN.PDF.pdf)

Wiring Diagram
