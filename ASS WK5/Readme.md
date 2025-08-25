# 📱 OOP Device Demo – Polymorphism & Inheritance in Python

This project demonstrates the core principles of **Object-Oriented Programming** using a real-world scenario involving **devices** like smartphones and smartwatches.

The code showcases:
- ✅ Inheritance
- ✅ Polymorphism
- ✅ Encapsulation

---

## 📦 Contents

- `devices_demo.py`: Main Python file containing the class hierarchy and demo
- `README.md`: Project overview and instructions

---

## 🚀 How It Works

### Base Class: `Device`

A general class that represents any electronic device.  
It defines common behaviors like turning on/off and stores basic info like brand and model.

### Subclasses:
#### 📱 `Smartphone`
Inherits from `Device` and adds:
- Storage capacity
- Battery level
- Installed apps
- Mobile data usage
- App installation & photo-taking

#### ⌚ `SmartWatch`
Inherits from `Device` and adds:
- Step tracking
- Heart rate monitoring

---

## 🎯 OOP Concepts Demonstrated

| Concept        | Description |
|----------------|-------------|
| **Inheritance** | Both `Smartphone` and `SmartWatch` inherit from `Device` |
| **Polymorphism** | All devices implement their own version of `get_status()` |
| **Encapsulation** | Attributes like `_is_on` are protected, accessed via methods |

---

## 🛠️ How to Run

### ✅ Prerequisites
- Python 3.x installed
- VS Code or any Python IDE

### ▶️ Steps
1. Clone or download the project
2. Open `devices_demo.py` in VS Code
3. Run the script:
   - Right-click > "Run Python File in Terminal"
   - OR use `python devices_demo.py` in your terminal

---

## 📌 Sample Output

🔁 Powering on all devices...

iPhone 15 is now ON.
Vivoactive 5 is now ON.
Galaxy S25 is now ON.
Sense 2 is now ON.

🔍 Getting status of all devices...

📱 Smartphone: Apple iPhone 15
🔋 Battery: 100%
💾 Storage: 0/256 GB
🌐 Data Left: 20 GB
🔌 Power: ON

⌚ SmartWatch: Garmin Vivoactive 5
🚶 Steps: 0
❤️ Heart Rate: 70 bpm
🔌 Power: ON