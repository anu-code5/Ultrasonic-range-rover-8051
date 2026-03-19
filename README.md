# Ultrasonic-range-rover-8051
This project implements a real-time ultrasonic distance measuring system using the 8051 microcontroller, HC-SR04 ultrasonic sensor, and an LCD display. The system measures the distance of an object and displays it in centimeters using Assembly-level programming.

Hardware Components:

8051 Microcontroller (Development Board),
HC-SR04 Ultrasonic Sensor,
16x2 LCD Display,
Arduino Uno (Power Supply),
Breadboard & Connecting Wires,
Robotic Chassis (for mounting)

Working Principle:

The system uses the time-of-flight principle:

1. The 8051 sends a 10µs trigger pulse to the HC-SR04 sensor.
2. The sensor emits an ultrasonic wave (40 kHz).
3. The wave reflects off an object and returns as an echo.
4. The echo duration is measured using Timer0.
5. Distance is calculated using:
  Distance (cm) = Time (µs) / 58
6. The result is displayed on the LCD.

References:

8051 Microcontroller – Mazidi,
HC-SR04 Datasheet,
Embedded Systems Assembly Programming
