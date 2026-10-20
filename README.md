# ESP32 Power Meter

[![ESP32](https://img.shields.io/badge/MCU-ESP32-E7352C)](https://www.espressif.com/)

An ESP32 meter that measures RMS voltage and current of an AC load with EmonLib, shows averaged readings on an I²C LCD, and pushes them to the cloud through IFTTT webhooks. College IoT project, 2023.

## Files

`voltage_and_current.ino` measurement and LCD · `sendDataon.ino` / `sendDataoff.ino` cloud reporting

Before flashing, copy `secrets.h.example` to `secrets.h` and fill in your Wi-Fi name, password and IFTTT key; `secrets.h` is git-ignored.

## Related

[ESP32 smart dustbin](https://github.com/Curious-Utkarsh/esp32-smart-dustbin)

---
[Kumar Utkarsh](https://github.com/Curious-Utkarsh) · [LinkedIn](https://www.linkedin.com/in/kumar-utkarsh-124aab227/) · [Portfolio of builds](https://www.mechamindlabs.com/projects)
