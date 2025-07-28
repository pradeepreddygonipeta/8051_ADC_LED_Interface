# 8051 ADC0804 + LED Interface Project

This project demonstrates how to interface the ADC0804 analog-to-digital converter with the 8051 microcontroller and control 8 LEDs connected to Port 2 based on the ADC input.

## 🔧 Hardware Used
- AT89C51 Microcontroller (8051 core)
- ADC0804
- 8 LEDs (P2.0–P2.7)
- Potentiometer (as analog input)
- Resistors (1kΩ, 10kΩ)
- Capacitors (10µF, 100nF)
- Breadboard & jumper wires
- 5V Power Supply

## 💡 Features
- Reads analog voltage via ADC0804
- Displays result on Port 2 LEDs
- Turns on LED (P2.0) if voltage > 2.5V

## 🧠 Code Overview

```c
#include <reg51.h>
// [your main.c code here]
