# ESP32-S3 Door Sensor

A low-power smart door sensor using a Seeed Studio XIAO ESP32-S3, reed switch, and CR2032 battery[cite: 1, 2].

## 🛠️ Components
* **MCU:** Seeed Studio XIAO ESP32-S3[cite: 1, 2]
* **Sensor:** Reed Switch (`SW1`) on pin `D0`[cite: 1, 2]
* **Power:** CR2032 Battery (`BT1`)[cite: 1, 2]
* **Capacitors:** `C1` (filtering) and `C2` (decoupling)[cite: 1, 2]
* **Test Points:** `TP1` (Signal), `TP2` (`BAT_VIN`), `TP3` (`GND`)[cite: 1, 2]

## 🚀 Quick Setup
1. Open `Door.kicad_sch` in KiCad[cite: 3].
2. Run **ERC** to verify 0 errors[cite: 5].
3. Press **`F8`** to update the PCB layout[cite: 8].
