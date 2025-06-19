# Wokwi Embedded Projects – 30 Day Self-Internship

This repository contains all my embedded system mini 
projects built using the Wokwi simulator. Each day introduces a new concept
 starting from basics and moving to advanced applications.
 
 # day 01-Blinking LED
platform : Wokwi simulator 
component: Arduino UNO , LED 

##Description :
 This project blinks the built-in LED on Arduino UNO with a delay pf 1 second .
 It helps to understand basic digital output and delay functions in Arduino.
 ## circuit diagram 
 [view here](https://wokwi.com/projects/433730590277051393)

 ## Skills Used:
  - pinMode()
  - digitalWrite()
  - delay()


  # 🚦 Day 02 – Traffic Light Controller using LEDs

## 📅 Project Overview
This project simulates a basic traffic light controller using three LEDs (Red, Yellow, Green). The lights turn on in a timed sequence just like a real-world traffic signal. This is part of a 30-day embedded systems self-internship.

---
## 🛠 Components Used
| Component      | Quantity |
|----------------|----------|
| Arduino UNO    | 1        |
| Red LED        | 1        |
| Yellow LED     | 1        |
| Green LED      | 1        |
| 220Ω Resistors | 3        |
| Jumper Wires   | As needed |
| Breadboard     | 1        |

---
## ⚙ Circuit Connections

| LED Color | Arduino Pin |
|-----------|-------------|
| Red       | D2          |
| Yellow    | D3          |
| Green     | D4          |

Each LED is connected in series with a 220Ω resistor to ground.

> 🔗 [View Circuit Diagram Here](# 🚦 Day 02 – Traffic Light Controller using LEDs

## 📅 Project Overview
This project simulates a basic traffic light controller using three LEDs (Red, Yellow, Green). The lights turn on in a timed sequence just like a real-world traffic signal. This is part of a 30-day embedded systems self-internship.

---

## 🛠 Components Used
| Component      | Quantity |
|----------------|----------|
| Arduino UNO    | 1        |
| Red LED        | 1        |
| Yellow LED     | 1        |
| Green LED      | 1        |
| 220Ω Resistors | 3        |
| Jumper Wires   | As needed |
| Breadboard     | 1        |

---

## ⚙ Circuit Connections

| LED Color | Arduino Pin |
|-----------|-------------|
| Red       | D2          |
| Yellow    | D3          |
| Green     | D4          |

Each LED is connected in series with a 220Ω resistor to ground.

> 🔗 [View Circuit Diagram Here](./traffic_light_diagram.png)  

## 💡 Working Principle
The Arduino runs a continuous loop:
1. Green light turns ON for 5 seconds (vehicles can go)
2. Yellow light turns ON for 2 seconds (prepare to stop)
3. Red light turns ON for 5 seconds (vehicles stop)

This cycle repeats indefinitely.

-## 🧠 Concepts Practiced
- Digital output control using digitalWrite()
- Pin configuration using pinMode()
- Timing control with delay()
- Real-time system simulation

## Day 03 – Button Controlled LED

**Platform:** Wokwi Simulator  
**Components:** Arduino UNO, LED, Push Button, Resistors

### 🔍 Description:
This project demonstrates how a push button can be used to control an LED.  
The LED lights up when the button is pressed and turns off when released.  
It introduces digital input using `digitalRead()` and basic condition checking.

🔗 [View Circuit Diagram on Wokwi](https://wokwi.com/projects/434182444161851393)

### 💡 Skills Used:
- `pinMode()`
- `digitalWrite()`
- `digitalRead()`
- `if` conditional statement
