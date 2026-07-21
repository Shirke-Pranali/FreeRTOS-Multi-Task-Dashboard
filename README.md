# FreeRTOS-Multi-Task-Dashboard
A FreeRTOS-based multitasking dashboard on STM32F446RE demonstrating priority-based task scheduling, LED control, temperature &amp; humidity monitoring, and serial output using PuTTY.

## Overview

This project demonstrates a real-time embedded application built on the STM32F446RE microcontroller using FreeRTOS. It showcases multitasking concepts by executing multiple tasks concurrently with priority-based scheduling while monitoring environmental data and controlling peripherals.

## Features

- Priority-based task scheduling using FreeRTOS
- Multi-task execution
- LED control task
- Temperature monitoring
- Humidity monitoring
- 1-second counter
- Serial communication through PuTTY
- Real-time task management

## Hardware

- STM32F446RE Development Board

## Software

- STM32CubeIDE
- FreeRTOS
- Embedded C
- PuTTY

## Task Architecture

### Task 1
LED Blinking

### Task 2
Temperature Monitoring

### Task 3
Humidity Monitoring

### Task 4
One-Second Counter

### Task 5
Serial Output to PuTTY

## Working

The scheduler initializes multiple tasks with different priorities. FreeRTOS allocates CPU time according to task priority while ensuring concurrent execution. Sensor data and counter values are transmitted to PuTTY over UART, while LEDs provide visual task indication.

## Learning Outcomes

- FreeRTOS Task Creation
- Task Scheduling
- Task Priorities
- UART Communication
- Real-Time Operating Systems
- Embedded C Programming

## Technologies

- STM32F446RE
- FreeRTOS
- Embedded C
- STM32CubeIDE
- UART
- PuTTY
