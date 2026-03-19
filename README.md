# ESP32COMPASSAVR

## 🚧 Work in Progress

## 📌 Overview
A custom PCB designed for:
- 🔋 Lithium Polymer battery operation & charging  
- 📡 WiFi + MQTT (ESP32-S3)  
- 💻 USB-C programming  
- 🖥️ OLED display output  

---

## 📦 Bill of Materials (BOM)

### 🔩 Passive Components

| Component              | Qty | Price (ea) | Total | Link |
|------------------------|-----|------------|-------|------|
| 10kΩ 0805              | 1   | $0.24      | $0.24 | https://www.digikey.com/en/products/detail/vishay/MCU08050D1002BP500/2607941 |
| 100Ω 0805              | 1   | $0.10      | $0.10 | https://www.digikey.com/en/products/detail/yageo/RE0805FRE07100RL/19911790 |
| 5.1kΩ 0805             | 2   | $0.73      | $1.46 | https://www.digikey.com/en/products/detail/vishay-dale-thin-film/PNM0805E5001BST5/2120390 |
| 47kΩ 0805              | 1   | $0.10      | $0.10 | https://www.digikey.com/en/products/detail/te-connectivity-passive-product/CRG0805F47K/3477712 |
| 1kΩ 0805               | 2   | $0.10      | $0.20 | https://www.digikey.com/en/products/detail/te-connectivity-passive-product/CRG0805F1K0/3477699 |
| 2kΩ 0805               | 1   | $0.24      | $0.24 | https://www.digikey.com/en/products/detail/vishay/MCU08050D2001BP500/7348046 |
| 1.5kΩ 0805             | 1   | $0.10      | $0.10 | https://www.digikey.com/en/products/detail/te-connectivity-passive-product/CRG0805F1K5/3477701 |
| 1MΩ 0805               | 1   | $0.14      | $0.14 | https://www.digikey.com/en/products/detail/vishay-dale/RCG08051M00FKEA/4172585 |
| 180kΩ 0805             | 1   | $0.19      | $0.19 | https://www.digikey.com/en/products/detail/vishay-dale/RCS0805180KFKEA/12445764 |
| 100kΩ 0805             | 2   | $0.10      | $0.20 | https://www.digikey.com/en/products/detail/te-connectivity-passive-product/CRGCQ0805F100K/8577605 |
| 22µF 0805 Capacitor    | 6   | $0.31      | $1.86 | https://www.digikey.com/en/products/detail/murata-electronics/GRM21BC81A226ME44L/6606263 |
| 100nF 0805 Capacitor   | 4   | $0.02      | $0.08 | https://us.rs-online.com/product/rs-pro/1805103/72072237/ |
| 1µF 0805 Capacitor     | 2   | $0.23      | $0.46 | https://www.digikey.com/en/products/detail/tdk-corporation/C2012X5R1H105K085AB/3947716 |
| 10µF 0805 Capacitor    | 3   | $0.05      | $0.15 | https://us.rs-online.com/product/kemet/c0805c106k8pactu/70095566/ |
| 1.5µH 2520 Inductor    | 1   | $0.26      | $0.26 | https://www.digikey.com/en/products/detail/bourns-inc/SRN2512-1R5M/4867683 |

---

### 💡 Indicators & Switches

| Component              | Qty | Price (ea) | Total | Link |
|------------------------|-----|------------|-------|------|
| 0805 White LED         | 1   | $0.50      | $0.50 | https://us.rs-online.com/product/bivar-inc-/sm0805uwc/70536355 |
| SMD Tactile Switch     | 10  | $0.051     | $0.51 | https://www.lcsc.com/product-detail/C720477.html |
| Slide Switch (MK-12D18)| 1   | $0.15      | $0.15 | https://jlcpcb.com/partdetail/GSwitch-MK_12D18G040/C963202 |

---

### 🔌 Connectors & Modules

| Component              | Qty | Price (ea) | Total | Link |
|------------------------|-----|------------|-------|------|
| USB-C Connector        | 1   | $0.78      | $0.78 | https://www.digikey.com/en/products/detail/gct/USB4105-GF-A/11198441 |
| Battery Connector      | 1   | $0.47      | $0.47 | https://www.digikey.com/en/products/detail/jst-sales-america-inc/S2B-ZR-SM4A-TF/926600 |
| SSD1306 128x64 OLED    | 1   | $0.98      | $0.98 | https://www.aliexpress.us/item/3256808426200900.html |

---

### 🧠 ICs & Power

| Component              | Qty | Price (ea) | Total | Link |
|------------------------|-----|------------|-------|------|
| ESP32-S3-WROOM-1       | 1   | $5.71      | $5.71 | https://www.digikey.com/en/products/detail/espressif-systems/ESP32-S3-WROOM-1-N8R2/15202953 |
| AMS1117-3.3 Regulator  | 1   | $0.29      | $0.29 | https://www.digikey.com/en/products/detail/umw/AMS1117-3-3/17635254 |
| TPS63020DSJT           | 1   | $4.45      | $4.45 | https://www.digikey.com/en/products/detail/texas-instruments/TPS63020DSJT/2263063 |
| BQ24090DGQ             | 1   | $1.25      | $1.25 | https://www.digikey.com/en/products/detail/texas-instruments/BQ24090DGQR/2353309 |

---

## 💰 Total Estimated Cost

**$22.31**

## Schematic

<img width="1919" height="1032" alt="AVRCOMPASSschematic" src="https://github.com/user-attachments/assets/46c85bd1-f654-4314-bd7d-db372d6e21b1" />

## PCB

<img width="933" height="808" alt="AVRCOMPASSPCB" src="https://github.com/user-attachments/assets/bb1eb5fa-f95f-42ed-bec9-1a422653f76d" />

## 3d Model

<img width="1378" height="753" alt="AVRCOMPASS3dmodel" src="https://github.com/user-attachments/assets/317e4b6b-69ea-48b2-9236-2ba46d89a8fe" />

<img width="1255" height="704" alt="image" src="https://github.com/user-attachments/assets/6bbd2230-08d4-4990-9871-02f4de8e7793" />

