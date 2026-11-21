<!--
Suggested repo name: Smart-Poultry-Water-Subsystem
GitHub "About" line: ESP32 automatic water monitoring and dispensing subsystem for a smart poultry enclosure (load cell, HX711, relay pump).
Topics: esp32, embedded-c, iot, automation, hx711, load-cell, agritech, embedded-systems
-->

# Smart Poultry Enclosure: Automatic Water Monitoring and Dispensing Subsystem

An ESP32-based subsystem that monitors the water level in a poultry enclosure and refills it automatically. It was developed as one part of a group project, a smart poultry enclosure monitoring and control system. This repository covers the water monitoring and dispensing subsystem only.

Durban University of Technology, 2026.

## Features

- Automatic water refilling using a relay-controlled pump
- Water level monitoring with a water level sensor
- Weight-based measurement using a load cell and HX711 amplifier
- Low-water alerts through a buzzer and LCD display
- Dry-running protection for the pump
- Tested to confirm reliable operation

<!-- TODO: add one measurable result (e.g. load cell calibration accuracy, refill threshold, test duration) if you have it. -->

## Hardware

| Component | Purpose |
|---|---|
| ESP32 | Main controller |
| Water level sensor | Level detection |
| Load cell + HX711 | Weight measurement and signal conditioning |
| Relay + pump | Water dispensing |
| Buzzer | Low-water alert |
| LCD | Status display |

<!-- TODO: add wiring diagram / pin table and a photo of the build. -->

## Software

Written in Embedded C for the ESP32.

<!-- TODO: add a short description of the control logic (thresholds, how dry-run protection works) and upload the source code. -->

## My contribution

Designed and developed the automatic water monitoring and dispensing subsystem.

<!-- TODO: list which parts of the wider group project were done by teammates, if you want to credit them. -->

## Repository contents

<!-- TODO: list the files, e.g. /src, /docs, /images. -->

## Author

Nontsikelelo Fundiswa Linda, BEng Tech Electronic and Computer Engineering, Durban University of Technology.
