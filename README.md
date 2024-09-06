# STM32 Tutorials

Welcome to the STM32 Tutorials repository! This repository contains a series of projects designed to help you learn and master various aspects of STM32 microcontroller programming. Each project focuses on a specific concept or peripheral, providing hands-on examples and detailed explanations.

## Table of Contents

1. [GPIO LED Control](#1-gpio-led-control)
2. [Interrupt-Driven LED Control](#2-interrupt-driven-led-control)
3. [ADC with Potentiometer](#3-adc-with-potentiometer)
4. [DMA with ADC](#4-dma-with-adc)
5. [PWM LED Brightness Control](#5-pwm-led-brightness-control)
6. [Timers for LED Control](#6-timers-for-led-control)
7. [UART Serial Communication](#7-uart-serial-communication)
8. [I2C Communication](#8-i2c-communication)
9. [SPI Communication](#9-spi-communication)
10. [RTOS with FreeRTOS](#10-rtos-with-freertos)

## 1. GPIO LED Control

Learn the basics of GPIO by toggling an LED on and off. This project introduces basic digital output control and is the foundation for more complex tasks.

- **Project Name:** `LED_Toggle_Button_Control`
- **Description:** Control LEDs using basic GPIO operations, including toggling and button-based control.

## 2. Interrupt-Driven LED Control

Explore the use of interrupts to handle button presses for LED control. This project teaches how to handle external interrupts efficiently.

- **Project Name:** `LED_Button_Interrupt`
- **Description:** Use interrupts to control LEDs based on button inputs.

## 3. ADC with Potentiometer

Use the Analog-to-Digital Converter (ADC) to read values from a potentiometer. This project is essential for understanding how to interface analog sensors with the STM32.

- **Project Name:** `Potentiometer_ADC_Reader`
- **Description:** Read potentiometer values using the ADC and convert them into digital signals.

## 4. DMA with ADC

Learn how to use Direct Memory Access (DMA) to transfer ADC data directly to memory, reducing CPU load and improving performance.

- **Project Name:** `DMA_ADC_Data_Transfer`
- **Description:** Implement DMA to handle ADC data transfer efficiently.

## 5. PWM LED Brightness Control

Master Pulse Width Modulation (PWM) by adjusting the brightness of an LED. This project also applies to motor control and other PWM-based applications.

- **Project Name:** `PWM_LED_Brightness_Control`
- **Description:** Control LED brightness using PWM.

## 6. Timers for LED Control

Use timers to control the blinking of an LED at precise intervals. This project helps you understand hardware timers and their applications.

- **Project Name:** `LED_Timer_Control`
- **Description:** Implement timers to control LED blinking intervals.

## 7. UART Serial Communication

Explore UART communication by sending and receiving data between the STM32 and a PC or another microcontroller.

- **Project Name:** `UART_Serial_Communication`
- **Description:** Implement UART for serial communication with external devices.

## 8. I2C Communication

Learn how to communicate with I2C-compatible devices such as sensors or displays. This project covers both master and slave configurations.

- **Project Name:** `I2C_Sensor_Reading`
- **Description:** Interface with I2C devices to read sensor data.

## 9. SPI Communication

Delve into SPI communication to exchange data with SPI peripherals like sensors, memory modules, or displays.

- **Project Name:** `SPI_Sensor_Reading`
- **Description:** Implement SPI communication to interact with external devices.

## 10. RTOS with FreeRTOS

Get started with Real-Time Operating Systems (RTOS) by using FreeRTOS to manage multiple tasks on the STM32. This project is ideal for building more complex, real-time applications.

- **Project Name:** `FreeRTOS_LED_Tasks`
- **Description:** Manage tasks using FreeRTOS to control multiple operations in real-time.

## Getting Started

To run the projects in this repository, you will need:

- STM32CubeIDE or another compatible IDE
- STM32 Nucleo or similar development board
- Basic knowledge of C/C++ programming
- Familiarity with microcontroller basics

Each project includes source code and explanations to help you understand the underlying concepts. Feel free to explore, modify, and experiment with the projects.
