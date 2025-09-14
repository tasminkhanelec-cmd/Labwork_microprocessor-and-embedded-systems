# EEE416 Microprocessor & Embedded Systems 

> Advanced ARM Cortex-M development, peripheral interfacing, and processor architecture simulation

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![ARM Cortex-M](https://img.shields.io/badge/ARM-Cortex--M4-blue.svg)](https://developer.arm.com/Processors/Cortex-M4)
[![STM32](https://img.shields.io/badge/STM32-F446RE-orange.svg)](https://www.st.com/en/microcontrollers-microprocessors/stm32f446re.html)

## About

This repository contains advanced laboratory exercises exploring ARM Cortex-M microcontroller programming, real-time embedded systems development, and processor architecture simulation. Projects span from bare-metal programming to hardware abstraction layer implementation and digital signal processing applications.

## Architecture & Toolchain

| Component | Technology | Purpose |
|-----------|------------|---------|
| **Target MCU** | STM32F446RE (ARM Cortex-M4F) | 180MHz, FPU, DSP instructions |
| **Development IDE** | Keil µVision 5/6 | Professional ARM development environment |
| **Configuration** | STM32CubeMX | Hardware abstraction and code generation |
| **Simulation** | ModelSim | Verilog HDL processor simulation |
| **Debug Interface** | ST-Link v2.1 | On-chip debugging and programming |

## Technical Scope

### Low-Level Programming
- **Bare-metal ARM assembly** - Direct register manipulation, instruction pipelining
- **Memory-mapped I/O** - Peripheral control without HAL abstractions  
- **Interrupt service routines** - Vector table configuration, NVIC programming
- **DMA operations** - Zero-copy data transfers, circular buffering

### Signal Processing & Control
- **Timer peripherals** - Advanced PWM generation, encoder interfacing
- **ADC/DAC operations** - Multi-channel sampling, DMA-based acquisition
- **Motor control algorithms** - Stepper motor microstepping

### System Architecture
- **Single-cycle ARM processor** - Verilog HDL implementation and verification
- **Custom instruction sets** - Processor extension and validation

## Key Concepts

- **GPIO Control**: Interfacing LEDs, push buttons, and stepper motors with STM32 microcontrollers using GPIO pins.
- **PWM & ADC**: Generating PWM signals for controlling the brightness of LEDs and using ADC to read analog sensor data.
- **Assembly Programming**: Writing low-level assembly code for ARM processors to perform specific tasks like conditionals, loops, and function calls.
- **Timer Interrupts**: Using timers and interrupts for periodic events like blinking LEDs and measuring time intervals.
- **Analog to Digital & Digital to Analog Conversion**: Working with ADC to read analog inputs and DAC to generate analog outputs like sine waves.
- **Verilog HDL**: Designing and simulating a single-cycle ARM processor in Verilog for understanding processor architecture and instruction execution.


## Lab Experiments

### 1. Familiarization with Keil MDK v5
Installation and setup of Keil MDK v5, followed by creating a project and compiling an example program on an STM32 microcontroller.

### 2. GPIO Interfacing
Interfacing and controlling LEDs, push buttons, and stepper motors using the STM32 GPIO pins, including basic input/output operations.

### 3. Timer and Interrupt Programming
Utilizing timers and external interrupts to control an LED with a push button and measure time intervals.

### 4. PWM for LED Control
Generating PWM signals to adjust the brightness of LEDs and fading effects using timers.

### 5. Analog Interfacing
Using ADC for reading values from a potentiometer and generating analog waveforms with a DAC, including the application of low-pass filters.

### 6. Assembly Language Programming for ARM
Writing assembly code for ARM microcontrollers, including conditionals, loops, stack operations, and function calls.

### 7. Simulating ARM Processor in Verilog
Simulating and testing a single-cycle ARM processor in Verilog HDL, modifying the processor's functionality to add new instructions.


## License

MIT License - See [LICENSE](LICENSE) for details.
