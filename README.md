🔧 Automated Bottle Filling System – PLC Ladder Logic Project

This project represents the design and simulation of an automated bottle filling system using PLC ladder logic. The system controls a conveyor-driven process that detects bottles, manages timed filling operations, and counts completed cycles using structured industrial logic.

🏗 System Overview:

🔴 Idle Mode: Red indicator lamp ON before system start

🟢 Run Mode: Green lamp and motor activated after pressing START

👀 Object Detection: Sensor detects bottle presence on conveyor

⏱ Detection Delay: 3-second validation timer before stopping conveyor

🛑 Filling Stage: Motor stops for 3 seconds to simulate filling process

🔢 Production Counter: Down counter initialized at 3 cycles

🏁 Completion Logic: System stops automatically when counter reaches zero or STOP is pressed

🚨 Emergency Stop Integration: Immediate shutdown logic for safety override

⚙ Technical Features:

Latching RUN control logic

Timer ON-delay (TON) for detection and filling stages

Down counter (CTD) for production cycle control

Sensor edge-trigger behavior

Safety interlock structure

Clear state-based operational sequencing
<!-- Previous content from README.md will be preserved below this line -->
