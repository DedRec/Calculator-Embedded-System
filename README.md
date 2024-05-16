# Calculator-Timer-Stopwatch Embedded Project using LCD-display

## Overview
This project involves developing embedded systems software for a microcontroller platform, specifically the TM4C123GH6PM microcontroller. The software includes tasks for controlling GPIO pins, interfacing with peripherals like LCD displays and keypads, implementing timers, and more.

## LCD Interfacing with TM4C123 Tiva LaunchPad

This program takes inputs from the user and prints that input on the LCD. 
it takes two numbers (each less than or equal 5 digits) and a sign between them. 
Uses the keypad numbers to get the numbers. 

A button: +, B button: -, C button: /, D button: =, * button: x

## Files Included

### DIO.h
Header file containing declarations for functions related to Digital Input/Output (GPIO) operations.

### bitwise_operation.h
Header file containing declarations for bitwise operations functions.

### LCD.h
Header file containing declarations for functions to control LCD displays.

### Keypad.h
Header file containing declarations for functions to interface with a keypad.

### types.h
Header file containing custom type definitions for integer and floating-point types.

### timer0_Timer.h
Header file containing declarations for timer-related functions.

### startup_ewarm.c
Startup code for the IAR Embedded Workbench, version 5, provided by Texas Instruments for the TM4C123GH6PM microcontroller.

### main.c
Main program file containing the entry point for the application, including initialization and task execution.

### Timer.c
Source file containing implementations of timer initialization and control functions.

### Timer0_Timer.c
Source file containing implementations of timer-related functions for specific tasks.

### Lab4.c
Source file containing implementations of tasks for a lab exercise, including GPIO pin control and task execution.

## Dependencies

- **Driver Library:** The project relies on the TivaWare Peripheral Driver Library provided by Texas Instruments for interacting with the microcontroller peripherals.
- **Standard Libraries:** Standard C libraries such as `stdio.h`, `stdint.h`, `stdbool.h`, and `stdlib.h` are used for standard I/O, integer types, boolean types, and memory management, respectively.

## Technologies Used

- **C Programming Language:** The software is developed using the C programming language, suitable for embedded systems programming.
- **TM4C123GH6PM Microcontroller:** The software is targeted for the TM4C123GH6PM microcontroller, featuring ARM Cortex-M4F architecture.
- **IAR Embedded Workbench:** The project is developed and compiled using the IAR Embedded Workbench IDE, version 5.
- **Peripheral Driver Library:** The TivaWare Peripheral Driver Library is utilized for abstracting low-level hardware access and providing higher-level functions for peripheral control.
- **LCD Displays:** The project includes functionalities for interfacing with and controlling LCD displays.
- **Keypads:** The project includes functionalities for interfacing with and reading inputs from keypads.
- **Timers:** Timer peripherals of the microcontroller are utilized for implementing various time-based functionalities.

## Usage

To use the project, follow these steps:

1. Clone the repository to your local machine.
2. Open the project in the IAR Embedded Workbench IDE.
3. Compile the project to generate the executable binary.
4. Flash the binary onto the TM4C123GH6PM microcontroller using suitable tools.
5. Run the application on the microcontroller.
