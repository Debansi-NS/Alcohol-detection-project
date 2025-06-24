# Alcohol Detector with Engine Locking System

This project is a **smart safety system** that prevents **drivers and bike riders** from starting their vehicles if their blood alcohol content (BAC) is above a safe limit.

## How It Works

- **Alcohol Detection:** A breathalyzer checks the BAC before allowing engine start.
- **For Cars:** The sensor measures BAC when starting the car. If BAC is above the limit (e.g., 0.08%), the system displays **“Don’t Drive”**, locks the ignition using a relay, and may trigger an alert.
- **For Bikes:** The sensor is mounted inside the helmet. A micro/magnetic switch detects if the helmet is worn, and a Bluetooth link connects the helmet to the bike’s engine control. If BAC is high, the bike’s ignition is locked.
- **Recheck Mechanism:** The system periodically rechecks the BAC and unlocks the engine once the BAC is safe.

## Components

- **ESP32 / Arduino**
- **MQ-3 Alcohol Sensor**
- **Micro/Magnetic Switch** (for helmet detection)
- **Bluetooth Module** (for bike communication)
- **Relay Module** (for engine lock)
- **Arduino IDE**

---

✅ **Prevents drunk driving.**  
✅ **Works for cars and bikes.**  
✅ **Enhances road safety.**

