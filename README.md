# Water Level Indicator PCB Design

## 📋 Abstract

A simple yet effective water level detection circuit built using basic transistor logic and LED indicators. The system monitors water levels across four distinct levels and provides visual feedback through color-coded LEDs (Aqua, White, Yellow, Red). An active buzzer provides audible alerts when water reaches critical levels.

This circuit is cost-effective, easy to build, and ideal for tanks, reservoirs, and water storage applications in residential and industrial settings.

---

## 🎯 How It Works

The circuit uses **four BC547 NPN transistors** as switches controlled by a **capacitive or resistive water sensor probe (J1)**. As water level rises:

1. **Sensor signal increases** → Transistor base voltage increases
2. **Transistors turn ON sequentially** → LEDs light up in order
3. **At critical level (Red LED)** → Buzzer activates for alarm
