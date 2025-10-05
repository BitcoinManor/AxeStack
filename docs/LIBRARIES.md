# Libraries (AxeStack — Spark)

> Purpose: single source of truth for required Arduino libs and versions.
> We’ll fill the VERSION fields as we lock builds on the VAIO.

## Arduino Core
- **ESP32 by Espressif** — VERSION: _TBD_  
  Notes: ESP32-S3 support. Board manager URL already installed on VAIO.

## Display / UI
- **LVGL** — VERSION: _TBD_  
- **Waveshare ST7262 display stack** (driver you used previously) — VERSION: _TBD_  
  Notes: 800×480, RGB panel, GT911 touch (future, keep disabled for v0.1).

## Networking / JSON
- **ArduinoJson** — VERSION: _TBD_  
- **WiFi** (from ESP32 core) — VERSION: core  
- **HTTPClient** (from ESP32 core) — VERSION: core

## Optional (later)
- **NimBLE-Arduino** (if we add BLE setup helper) — VERSION: _TBD_
- **LittleFS / SPIFFS** (if we cache assets) — VERSION: core

---

## Install Notes (VAIO)
- Arduino IDE 2.x
- Board: ESP32 → ESP32S3 [Spark target]
- Library install: Library Manager preferred; pin VERSIONs once confirmed working.

