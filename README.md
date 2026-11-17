# Real-Time Sensor Monitoring Using Periodic Task Scheduling

## Description
This project implements a real-time sensor monitoring system using the ARM7 LPC2129 microcontroller. It uses Timer Interrupts for periodic task scheduling to monitor multiple sensors and displays their readings through UART communication.

## Hardware Requirements
- ARM7 LPC2129 Development Board
- Temperature Sensor
- Potentiometer
- LDR Sensor
- Flame Sensor
- PIR Sensor
- LED

## Peripherals Used
- ADC
- UART
- Timer Interrupt
- GPIO

## Features
- Temperature monitoring with LED indication.
- Potentiometer voltage monitoring.
- LDR light intensity monitoring.
- Flame detection.
- PIR sensor detection.
- Periodic task scheduling using Timer 1 interrupts.
- UART communication for displaying sensor data.

## Project Files
- `adc_driver.c` – ADC configuration and reading.
- `delay.c` – Delay functions.
- `header.h` – Header file.
- `timer_int.c` – Timer interrupt and task scheduling.
- `uart0_driver.c` – UART communication.
- `sensor_station.c` – Main application.

## Software Requirements
- Embedded C
- Keil µVision IDE
- ARM7 LPC2129

## Conclusion
This project demonstrates sensor interfacing, interrupt handling, UART communication, and periodic task scheduling in an embedded system using ARM7 LPC2129.
