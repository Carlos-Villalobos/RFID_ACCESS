# RFID Access
## Description
This project its based on an access with an RFID made for a school project. Before of all you'll need to buy the following:
- MFRC522 RFID Reader
- 16x2 LCD
- 2 resistors of 220 Ω
- 1 resistor of 1k Ω
- 1 resistor of 10k Ω
- 1 Servo motor
- 1 Proximity Sensor - CNY70
- 1 Arduino Nano

---

## Installation
To install this repository correctly follow the next steps.

First of all, in the terminal put the next code:

```sh
 git clone https://github.com/Carlos-Villalobos/RFID_ACCESS.git
 cd RFID_ACCESS
```
---
## Using the project
- After finishing doing the circuit and running the code on the Arduino
- You need to scan either a card or a tag to set it as the "Master Key", then you should scan it again so you can access to the part for you to add the tags/cards that will be scanned for the access.
- When the access key have been set for you to access, the tag/card needs to be readed again, so the servo can open the door.
- After closing the door, the proximity sensor will close the door when it detects something close enough.

---

## Developed by:
 Carlos Manuel Villalobos García
