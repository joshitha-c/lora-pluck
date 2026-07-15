# LoRa RP2040 Development Board

A custom-designed LoRa development board built in **KiCad**, combining the powerful **Raspberry Pi RP2040** microcontroller with the **Semtech SX1262 LoRa transceiver**. The board is designed for long-range wireless communication, rapid prototyping, IoT applications, and embedded systems development.
This development board is intended for long-range wireless communication and embedded IoT applications. The RP2040 acts as the main controller while the SX1262 provides LoRa connectivity for transmitting and receiving data over long distances.
---

## Features

- RP2040 dual-core ARM Cortex-M0+ microcontroller
- SX1262 LoRa transceiver (Sub-GHz communication)
- USB Type-C interface for programming and power
- External QSPI Flash memory
- 12 MHz crystal for RP2040
- 32 MHz crystal for SX1262
- RF matching network
- Antenna connector
- Reset and Boot buttons
- On-board voltage regulation
- Proper decoupling capacitors for stable operation
- Designed entirely in KiCad

---


## Main Components

| Component | Description |
|------------|-------------|
| RP2040 | Main Microcontroller |
| SX1262 | LoRa Transceiver |
| W25Q Series Flash | External QSPI Flash Memory |
| USB-C Connector | Programming & Power |
| 12 MHz Crystal | RP2040 Clock |
| 32 MHz Crystal | SX1262 Clock |
| RF Matching Network | Impedance Matching |
| Antenna Connector | RF Output |

---

## Future Improvements

- OLED display support
- GPS module
- Battery charging circuit
- Li-ion battery connector
## Tools Used

- KiCad


schematic
<img width="1917" height="948" alt="image" src="https://github.com/user-attachments/assets/57e8280d-4444-4a02-b695-9dfdfd13ff06" />
pcb
<img width="1022" height="796" alt="image" src="https://github.com/user-attachments/assets/be7e04ab-8a4c-4f74-9c2d-deab302ff9d3" />
