# HAOS-MEOW
# Heated Meow - Automated Heated Cat Bed Control

This Home Assistant blueprint automates the control of heated cat beds based on **seasonal changes** and **outdoor temperature thresholds**. It integrates with **Z-Wave, Zigbee, Thread, and Matter** smart plugs to optimize power usage while keeping your pets comfortable during colder months.

## 🛠 Features
- **Automatically Turns On/Off**: Activates heated cat beds when:
  - The **season is winter** OR
  - The **temperature falls below 45°F (7°C)**
- **Multi-Plug Support**: Add multiple smart plugs for different cat beds.
- **Optional Presence Detection**: (Future feature) Use smart pet collars (Samsung SmartThings, etc.) to trigger heating based on proximity.

## 📥 Installation

1. Click the button below to **import** this blueprint into Home Assistant:

   [![Import Blueprint to Home Assistant](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://github.com/necrose99/HAOS-MEOW/blob/main/heated-meow.yaml)

2. Open **Home Assistant** and navigate to:
   - `Settings` → `Automations & Scenes` → `Blueprints`
   - Click **"Import Blueprint"** and paste the **URL** above.

3. Create a new automation using the imported blueprint.

## ⚙️ Configuration
- **Smart Plug**: Select the smart plug(s) controlling the heated cat bed.
- **Temperature Sensor**: Choose an outdoor temperature sensor (e.g., Home Assistant weather integration).
- **Threshold**: Default is **45°F (7°C)**; customize as needed.
- **Season Sensor**: Ensure you have the **Season** integration enabled.

## 🐾 Future Enhancements
- **Smart pet collar integration** for multi-floor homes (optional).
- **Customizable temperature range** for different climates.

---

### 📝 Notes
- The blueprint supports multiple smart home protocols (**Z-Wave, Zigbee, Thread, Matter**).
- Designed to help manage **energy efficiency** while ensuring pet comfort.

📌 **Contribute & Feedback**  
Feel free to submit **issues, improvements, or feature requests** via [GitHub Issues](https://github.com/necrose99/HAOS-MEOW/issues).

---
💡 *Made with love for our furry overlords!* 🐱🔥

