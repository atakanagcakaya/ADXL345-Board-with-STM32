# ADXL345 Sensor Board with STM32F103C8

This project is a custom-designed embedded sensor hub built around the STM32F103C8 microcontroller. 
It reads analog signals from an ADXL325 3-axis accelerometer via the MCP3208 SPI-based ADC and visualizes 
the sensor data on an OLED display using the I2C interface.

The design also includes:
A regulated 3.3V power supply,
A USB debug interface,
Pinouts for external motor driver control (to later control motor speed based on sensor input),
PCB layout optimized for signal integrity (with care taken around SPI traces, crystal placement, etc.).

The aim of the project is to create a modular and reusable embedded system platform capable of:
Reading analog sensor data,
Processing it via STM32,
Controlling actuators accordingly,
And visualizing the real-time data on a compact display.

It is intended as both a learning platform and a base design for future sensor-based embedded control systems.

