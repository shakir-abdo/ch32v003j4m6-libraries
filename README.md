# CH32V003J4M6 Libraries

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform: CH32V003](https://img.shields.io/badge/Platform-CH32V003-blue.svg)](http://www.wch-ic.com/products/CH32V003.html)

Over the past few weeks, I've been experimenting with the CH32V003J4M6 microcontroller and have written some basic yet useful libraries. These libraries are thoughtfully created to make your life easier by providing straightforward functions for various peripherals and sensors.

## Motivation

The CH32V003J4M6 microcontroller is a powerful and cost-effective solution for a wide range of applications. However, developing software for this microcontroller can be challenging due to the lack of comprehensive libraries and documentation. This repository aims to bridge that gap by providing well-documented and easy-to-use libraries that simplify the development process and help you get the most out of the CH32V003J4M6 microcontroller.

## Microcontroller Overview

![CH32V003J4M6 Microcontroller](https://github.com/shakir-abdo/ch32v003j4m6-libraries/blob/main/CH32V003J4M6.png)

## Pin Mapping

![CH32V003J4M6 Pin Mapping](https://github.com/shakir-abdo/ch32v003j4m6-libraries/blob/main/ch32v003j4m6_pins.png)

## Libraries

### UART Library

A simple and efficient UART library for the CH32V003J4M6 microcontroller.

- **Features**: Configurable baud rate, TX/RX control, single character and string transmission, buffer management, error checking.
- **GitHub**: [CH32V003J4M6 UART Library](https://github.com/shakir-abdo/CH32V003J4M6-uart)

### Servo Library

A lightweight servo motor control library specifically designed for the CH32V003J4M6 microcontroller.

- **Features**: Simple initialization and control interface, support for standard RC servo motors, angle control from 0° to 180°, automatic pulse width calculation.
- **GitHub**: [CH32V003J4M6 Servo Library](https://github.com/shakir-abdo/CH32V003J4M6-servo)

### Rotary Encoder Library

A simple and efficient rotary encoder library for the CH32V003J4M6 microcontroller.

- **Features**: Reliable position tracking, direction detection, button press detection with debouncing, minimal CPU usage.
- **GitHub**: [CH32V003J4M6 Rotary Encoder Library](https://github.com/shakir-abdo/CH32V003J4M6-rotary-encoder)

### MPU6050 Library

A complete interface for the MPU-6050 6-axis motion tracking device using the CH32V003J4M6 microcontroller.

- **Features**: 6-axis motion sensing, temperature sensor readings, configurable measurement ranges, digital low-pass filter configuration, power management functions.
- **GitHub**: [CH32V003J4M6 MPU6050 Library](https://github.com/shakir-abdo/CH32V003J4M6-MPU6050)

### MLX90614 Library

A library for interfacing the MLX90614 infrared temperature sensor with the CH32V003J4M6 microcontroller.

- **Features**: Read ambient and object temperature, I2C bus monitoring and recovery, configurable I2C speed.
- **GitHub**: [CH32V003J4M6 MLX90614 Library](https://github.com/shakir-abdo/CH32V003J4M6-mlx90614)

### Deep Sleep Library

A simple and efficient deep sleep management library for the CH32V003J4M6 microcontroller.

- **Features**: Timer-based wake-up, external interrupt wake-up, combined timer and interrupt wake-up, configurable sleep duration, wake-up source detection.
- **GitHub**: [CH32V003J4M6 Deep Sleep Library](https://github.com/shakir-abdo/CH32V003J4M6-sleep)


### AHT10 Library

A lightweight and efficient library for the AHT10 temperature and humidity sensor, specifically designed for the CH32V003J4M6 microcontroller.

- **Features**: Simple API, fixed-point arithmetic, I2C communication at 400kHz, one decimal place precision, timeout protection for I2C operations.
- **GitHub**: [CH32V003J4M6 AHT10 Library](https://github.com/shakir-abdo/CH32V003J4M6-AHT10)

### ADXL345 Library

A library for the ADXL345 accelerometer using the CH32V003J4M6 microcontroller.

- **Features**: Easy initialization, configurable measurement range, raw and converted acceleration readings, power management functions.
- **GitHub**: [CH32V003J4M6 ADXL345 Library](https://github.com/shakir-abdo/CH32V003J4M6-ADXL345)

### EEPROM Library

Simple and reliable EEPROM emulation for the CH32V003 microcontroller..

- **Features**: Simple API, Data Integrity, Compact Storage, Flash Management.
- **GitHub**: [CH32V003 EEPROM Library](https://github.com/shakir-abdo/ch32v003-eeprom)

### WS2812B RGB LED Library

A WS2812B RGB LED control library for CH32V003J4M6 microcontroller..

- **Features**: Simple API, Global brightness control, RGB and HSV support, Direct bit-banging implementation.
- **GitHub**: [CH32V003 WS2812B Library](https://github.com/shakir-abdo/CH32V003J4M6-WS2812B)

## Author

**Shakir Abdo**

- GitHub: [@shakir-abdo](https://github.com/shakir-abdo)

## License

All libraries are released under the MIT License.
