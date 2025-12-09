# ESP32 Bluetooth LED & Buzzer Control

Control a Red LED, Green LED, and Buzzer using Bluetooth commands from a mobile app or Bluetooth terminal.

---

## 🚀 Features
- Wireless Bluetooth control
- Single-character commands
- Control:
  - Red LED
  - Green LED
  - Buzzer

---

## 📡 Bluetooth Commands

| Command | Action        |
|---------|---------------|
| R       | Red LED ON    |
| r       | Red LED OFF   |
| G       | Green LED ON  |
| g       | Green LED OFF |
| B       | Buzzer ON     |
| b       | Buzzer OFF    |

---

## 🔌 Pin Connections

| Device | ESP32 Pin |
|--------|-----------|
| Red LED | GPIO 5   |
| Green LED | GPIO 18 |
| Buzzer | GPIO 19   |

---

## 📱 How to Use
1. Upload the code from `main.cpp` / `.ino` file.  
2. Connect via Bluetooth to **ESP32_LED_Buzzer**.  
3. Use any Bluetooth terminal app.  
4. Send commands (R, r, G, g, B, b).  

---

## 📁 Files
- **main.cpp / sketch.ino** → Contains full project code
