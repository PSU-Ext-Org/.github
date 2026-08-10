# PSU-EXT

Programmable control, telemetry, and protection for the bench PSU you already own — no replacement instrument required.

PSU-EXT is an inline hardware module and software stack: it sits between a manual bench PSU and the load, adds isolated voltage/current measurement, relay-controlled output switching, OVP/OCP protection, and exposes SCPI over USB and Wi-Fi. A browser dashboard and a built-in scripting IDE handle telemetry, control, and test automation.

Backed on [Crowd Supply](https://www.crowdsupply.com/maxeelabs/psu-ext) · [Project site](https://psu-ext-org.github.io) · [Demo video](https://www.youtube.com/watch?v=-SMOoRix2fA&list=PL6ckvcoRaXGZk9XdToRmbwaO-lrsME2fA&index=6)

## Repositories

| Repo | What it is |
|---|---|
| [`psu-ext-hardware`](https://github.com/PSU-Ext-Org/psu-ext-hardware) | KiCad schematics, PCB layout, enclosure |
| [`psu-ext-firmware`](https://github.com/PSU-Ext-Org/psu-ext-firmware) | ESP-IDF firmware (ESP32-S3) — SCPI over USB CDC & TCP, measurement, protection |
| [`psu-ext-software`](https://github.com/PSU-Ext-Org/psu-ext-software) | Backend proxy + scripting task runner, and the React operator dashboard |
| [`psu-ext`](https://github.com/PSU-Ext-Org/psu-ext) | Shared definitions and resources used across the project |

