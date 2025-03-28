# Car-Black-Box
Car Black Box using PIC18F4580 Microcontroller

This project implements a Car Black Box System using a PIC microcontroller to log and monitor critical driving events. The system records over-speeding incidents, gear shifts (GN, GR, G1-G4), and real-time vehicle data into an external EEPROM.

Key Features:
Real-time Monitoring: Displays current speed, event status, and time on an LCD using an RTC module.

Event Logging: Captures and stores critical driving data for later analysis.

EEPROM Storage: Utilizes I2C communication to log and retrieve event data.

User Interface: Interactive menu with options to view log, download log, clear log, and set time.

UART Interface: Enables data retrieval and debugging through serial communication.

Interrupt-driven System: Efficiently handles peripherals, including speed monitoring via a potentiometer.

This embedded system acts as a data recorder for vehicles, similar to an aircraft black box, enhancing accident analysis and vehicle diagnostics. 🚗💾
