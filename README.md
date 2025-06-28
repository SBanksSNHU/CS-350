# CS-350

## Thermostat Controller 

A Python-based thermostat controller for Raspberry Pi that demonstrates state management, hardware interfacing, and real-time communication. 

## 📌 Summary 

This project simulates a basic smart thermostat with three operational states: off, heat, and cool. It features: 

  State machine design  to manage transitions between modes.
  Physical button control  for cycling through states and adjusting the temperature setpoint.
  LED feedback  indicating current state and system behavior (on/slow pulse).
  LCD display  showing time, temperature, and thermostat status.
  Serial communication  with an external server for status updates every 30 seconds.
  Threaded execution  for smooth UI and background operation.
     

Built using GPIOZero, Adafruit sensors, and a character LCD, this project runs on a Raspberry Pi and serves as a foundation for embedded systems learning. 

## ✅ What Went Well 

  Successfully implemented a functional solution using a clean state machine architecture.
  Integrated hardware components (buttons, LEDs, sensor, LCD) effectively.
  Improved maintainability and clarity by following Python coding standards.
  Used threading to keep the display responsive while managing background tasks.
   

## 🔧 Learning Focus 

I've been deepening my understanding of low-level electronics and programming, particularly through: 

  Ben Eater :  For hands-on understanding of how computers and circuits work at a fundamental level.
  The Engineering Mindset :  For practical explanations of electrical systems and components.
     

These resources have greatly enhanced my ability to understand and debug hardware-software interactions. 

## 💻 Why Low-Level Coding Matters 

Low-level programming remains my favorite area because it gives direct control over hardware and system behavior. This project was a great opportunity to apply that knowledge in a real-world context—managing GPIO pins, I2C communication, and timing-sensitive operations from Python. 

## 🧱 Code Standards & Maintainability 

The code is structured to be readable, modular, and extensible: 

  Clear class-based design (TemperatureMachine, ManagedDisplay)
  Separation of concerns
  Use of constants and debug flags for flexibility
  PEP8-compliant formatting
  TODOs clearly marking areas for future improvement
   
