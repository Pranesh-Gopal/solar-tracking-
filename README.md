🔆 Solar Tracker Using PIC16F877A
This project implements an automatic solar tracking system using the PIC16F877A microcontroller. It features two LDR sensors to detect sunlight intensity differences and a servo motor to adjust the solar panel’s position accordingly. The 16x2 LCD displays real-time LDR sensor values, and LED indicators provide status feedback. This system helps maximize solar energy capture by dynamically adjusting the panel’s orientation. 🌞🔋

🛠️ How It Works & Setup
The LDR sensors (LDR1 & LDR2) are placed at different positions on the solar panel.
The LCD displays the real-time values of both LDRs.
The servo motor adjusts the panel’s position based on the difference between LDR1 and LDR2.
A threshold of 50 is used to determine when the panel should move.
If LDR1 > LDR2, the panel moves right (increasing the servo pulse width).
If LDR2 > LDR1, the panel moves left (decreasing the servo pulse width).
If the difference is below the threshold, the panel remains stationary.
A Green LED indicates the panel is adjusting, while a Red LED indicates no movement.
🔧 Components Used
🏷️ Hardware:
⚡ PIC16F877A Microcontroller
📟 16x2 LCD Display
🌞 Two LDR Sensors
🔄 Servo Motor
🔴🟢 Red & Green LED Indicators
💻 Software:
🖥️ CCS C Compiler
🛠️ Proteus (for simulation)
📌 Future Enhancements & Contributions
Future improvements could include tracking along two axes (horizontal and vertical), EEPROM-based calibration, and wireless data monitoring. This project is a great learning tool for embedded systems and renewable energy applications.
