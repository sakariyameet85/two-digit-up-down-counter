# Mod Two-Digit Up-Down Counter

## 📘 Project Overview
This project demonstrates the design and implementation of a **2-digit up-down counter** that counts between 00 and 99 with user-controlled direction. It is a fundamental circuit in digital electronics, widely applied in **clocks, timers, event counters, industrial automation, and consumer electronics**.

The counter was designed using **basic digital ICs** such as:
- **CD4511** – BCD to 7-segment latch/decoder/driver  
- **74HC283** – 4-bit binary adder  
- **74HC86** – XOR gate for direction control  
- **74HC93** – 4-bit binary counter  
- **7805 Voltage Regulator** – Stable 5V supply  
- **7-Segment Displays** – To show the count  

Power was supplied using a **9V battery**, making the circuit simple and portable.  

## 🔧 Methodology
1. **Circuit Design & Simulation**  
   - Designed the counter in **Tinkercad** and tested logic in **Modelsim**.  
   - Verified accuracy, direction control, and stability.  

2. **Hardware Implementation**  
   - Assembled the circuit on a breadboard.  
   - Tested counting operation in both directions.  

3. **FPGA Implementation**  
   - Assigned I/O pins and tested the design on FPGA.  
   - Verified correct RTL and technology mapping.  

## 📊 Results
- **Simulations** confirmed accuracy, proper direction control, and glitch-free operation.  
- **Hardware implementation** displayed stable counting between 00–99.  
- **FPGA testing** validated the adaptability of the design.  

## 🎯 Learning Outcomes
- Hands-on experience in digital logic circuit design.  
- Understanding of binary counting and control logic.  
- Debugging and validation of digital systems.  

## 🚀 Future Scope
- Extend to multi-digit counters.  
- Add programmable count limits.  
- Integrate variable clock sources for speed control.  
- Apply in real-world systems like scoreboards and timers.  

## 📄 Project Report
The full project details, including diagrams, flowcharts, Verilog code, and simulations, are available in the report:


## 👥 Contributors
- **Heer Sadiwala (23BEC168)**  
- **Meet Sakariya (23BEC169)**  
Department of Electronics and Communication Engineering,  
Nirma University, Ahmedabad (November 2024)  
