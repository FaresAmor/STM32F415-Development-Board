# STM32F415 Development Board (Altium Designer)

## Overview  
This project presents a **custom PCB design** for a **STM32F415-based development board** .
The board provides a **complete standalone STM32 development platform**, similar to ST’s official **NUCLEO series**, allowing **USB programming, debugging, and serial communication** without the need for an external ST-Link programmer.

It integrates an **onboard ST-Link V2.1** interface using an **STM32F103CBT6**, which enables programming, debugging, and virtual COM port communication directly via USB.  
> ⚠️ Note: The STM32F103CBT6 must be the **128 KB flash** version to support the latest ST-Link firmware (the 64 KB variant is not compatible).

Designed entirely with **Altium Designer**, this board provides a **powerful and versatile platform** for STM32 firmware development and educational purposes.

---

## Components Used  
- **Main Controller:** STM32F415  
- **Programmer/Debugger:** STM32F103CBT6 (ST-Link V2.1)  
- **LEDs:** 8 × user-controllable LEDs  
- **Analog Inputs:** 2 × potentiometers  
- **RGB LED:** Connected to timer channels  
- **DAC Outputs:** 2 × DAC channels  
- **CAN Interfaces:** 2 × CAN buses (1 Master, 1 Slave)  
- **USB Interface:** Micro USB for power, programming, and communication  
- **Passive Components:** Resistors, capacitors, and decoupling/filtering components  

---

## Features  
- Fully integrated **ST-Link V2.1** (no external programmer required)  
- **USB programming, debugging, and virtual COM port**  
- **8 user LEDs** for GPIO testing and feedback  
- **2 potentiometers** for analog signal input  
- **1 RGB LED** controlled by hardware timers  
- **2 DAC outputs** for analog waveform generation  
- **Dual CAN interface** for communication testing (Master/Slave)  
- **Compact and educational PCB layout**  
- **Designed with Altium Designer** (schematic + PCB)  
- Ideal for **embedded systems training**, **STM32 firmware development**, and **peripheral interface experiments**  

---

## Files Included  
- Altium Designer project files (`.SchDoc`, `.PcbDoc`)  
- Gerber files for PCB fabrication  
- Bill of Materials (BOM)  
- PDF schematics and PCB layout drawings  

---

## TOP VIEW  
![TOP View](https://github.com/FaresAmor/STM32F415-Development-Board/blob/main/TOP.png)

## BOTTOM VIEW  
![BOTTOM View](https://github.com/FaresAmor/STM32F415-Development-Board/blob/main/BOTTOM.png)

---

## Demo  
Below is a preview of the PCB design in Altium Designer:

![Demo](https://github.com/FaresAmor/STM32F415-Development-Board/blob/main/gif.gif)

---

## Contribution  
Feel free to **explore, modify, and contribute** to this project!  
If you discover any issues or would like to suggest improvements, don’t hesitate to open a **pull request** or **raise an issue**. 🚀

---

> 💡 **Tip:** This board is perfect for learning STM32 programming, experimenting with embedded peripherals, or developing standalone firmware without an external ST-Link programmer.
