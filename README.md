The name of the Project-IR sensor alaram system
Objective of the Circuit

The main objective of this setup is to create an obstacle detection system using a RISC-V development board, an IR sensor module, and a buzzer.

Working Principle:

1. The IR sensor detects an obstacle by emitting infrared light and receiving the reflected signal.


2. If an obstacle is detected, the sensor outputs a HIGH or LOW signal (depending on module type) to the RISC-V board.


3. The RISC-V board processes this signal and activates the buzzer to produce an alert sound.


4. The system can be extended to display obstacle detection messages on a 16x2 LCD display
5. Pin Connections (Point-wise)

IR Sensor Module → RISC-V Board

1. VCC → 5V (Power supply from RISC-V board)


2. GND → GND (Ground connection)


3. OUT → Digital Input Pin (e.g., D2) (For obstacle detection signal)



Buzzer → RISC-V Board

4. Positive (+) → Digital Output Pin (e.g., D3) (To control buzzer activation)


5. Negative (-) → GND (Ground connection)



This setup ensures that the RISC-V board reads the IR sensor and activates the buzzer when an obstacle is detected.



