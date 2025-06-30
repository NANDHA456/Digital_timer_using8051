Digital Timer using 8051 Microcontroller (AT89C51)
🔧 Project Overview
This project demonstrates a simple digital timer built using the 8051 microcontroller (AT89C51). 
The timer displays minutes and seconds on a 16x2 LCD, with features like start, pause, and reset. 
It serves as a foundational embedded systems project that showcases basic use of timers, LCD interfacing, and button controls using Embedded C.

⚙️ Hardware Used
Microcontroller: AT89C51 / AT89S51 (8051 core)
Display: 16x2 Alphanumeric LCD
Buttons: Start, Pause, Reset
Crystal Oscillator: 11.0592 MHz
Capacitors: 33pF (for crystal), 10µF (for reset)
Resistors: 10KΩ (pull-up and reset)
Power Supply: 5V regulated (7805-based or USB)
Optional: Buzzer (for alerts), LED indicators

🧠 Project Features
Count time in MM:SS format
Use of Timer 0 in Mode 1 (16-bit timer)
Start, Pause, and Reset button functionality
LCD interfacing in 8-bit mode
Accurate delay using internal timer

💻 Software Tools
Keil µVision – Code development and HEX generation
Proteus 8/ISIS – Circuit simulation and testing

🧾 How It Works
Timer 0 is configured to generate 1-second delay using internal crystal.
LCD is initialized to display current time in MM:SS.
Button inputs are scanned to control the timer:
Start: Starts or resumes the timer
Pause: Stops counting
Reset: Sets timer back to 00:00
Timer interrupt (or polling-based delay) updates seconds and minutes.
Time is displayed and updated in real time on the LCD.
