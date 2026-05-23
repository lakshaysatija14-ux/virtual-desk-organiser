# 🚀 Virtual Desk Organiser

Smart desk organiser built using an ESP32-S3 and e-paper display to create a distraction-free, low-power productivity companion. The system displays useful daily information such as weather, calendar events, motivational quotes, alarms, and tasks through a clean web dashboard and energy-efficient e-paper interface.

---

## ✨ Features

- 🌤️ Real-time weather updates
- 📅 Calendar synchronization
- 💬 Daily motivational quotes
- ✅ To-do list management
- ⏰ Alarm and reminder system
- 🌐 Web dashboard for remote control
- 🔋 Low power consumption using e-paper display
- ☀️ Solar panel powered support
- 🚶 PIR motion sensor for smart wake/sleep mode
- 🤖 AI-inspired smart productivity desk companion

---

## 🛠️ Hardware Components

| Component | Description |
|------------|-------------|
| ESP32-S3 Pico | Main microcontroller with Wi-Fi & Bluetooth |
| DESPI-C02 | E-paper display driver board |
| E-paper Display | Low-power display for always-on information |
| PIR Sensor | Detects human presence and motion |
| Solar Panel | Optional renewable power source |

---

## 💻 Software & Technologies

- Arduino IDE
- ESP32 Board Package
- HTML, CSS, JavaScript
- REST APIs
- Wi-Fi Connectivity
- JSON Parsing

---

## 📷 System Overview

The Virtual Desk Organiser connects to Wi-Fi and fetches live information from APIs. Data is processed by the ESP32-S3 and displayed on the e-paper screen. A web dashboard allows users to manage tasks, alarms, reminders, and settings remotely.

---

## 🔄 Working Principle

1. ESP32 connects to Wi-Fi.
2. APIs fetch weather, quotes, and calendar data.
3. User tasks and alarms are managed through the web dashboard.
4. E-paper display updates important information.
5. PIR sensor detects activity and controls power-saving modes.
6. Solar panel provides sustainable low-power operation.

---

## 🌍 Applications

- Smart workspace assistant
- Productivity desk organiser
- Low-power IoT dashboard
- Personal reminder system
- Smart home information display

---

## 🚀 Future Improvements

- Voice assistant integration
- AI-based schedule suggestions
- Mobile application support
- Smart notifications
- Battery management system
- Touch controls

---

## 📡 Web Dashboard

The project includes a responsive web dashboard for:

- Managing tasks
- Setting alarms
- Updating reminders
- Viewing live desk data
- Monitoring system status

---

## ⚡ Advantages

- Energy efficient
- Portable and compact
- Clean and minimal interface
- Real-time information access
- Eco-friendly solar support

---

## 📂 Project Structure

```bash
Virtual-Desk-Organiser/
│
├── frontend/
├── backend/
├── firmware/
├── hardware/
├── images/
├── docs/
└── README.md
```

---

## 🔧 Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/Virtual-Desk-Organiser.git
```

### 2️⃣ Open Firmware

- Open Arduino IDE
- Install ESP32 board package
- Select ESP32-S3 board

### 3️⃣ Install Required Libraries

```bash
WiFi.h
HTTPClient.h
GxEPD2.h
ArduinoJson.h
```

### 4️⃣ Upload Code

- Connect ESP32-S3
- Select correct COM port
- Upload firmware

---

## 📶 APIs Used

- Weather API
- Quote API
- Calendar API

---

## 📸 Screenshots

Add your project screenshots here.

```bash
/images/dashboard.png
/images/hardware.jpg
/images/display.jpg
```

---

## 👨‍💻 Author

### Lakshay Satija  
Electronics & Communication Engineering  
Chitkara University

---

## 📜 License

This project is open-source and available under the MIT License.

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
