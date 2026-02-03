# ESP32 LED Toggle Example

This repository contains a **simple ESP32 project using ESP-IDF** that toggles an LED on and off every second. It's designed to be beginner-friendly and runs directly on most ESP32 boards.

---

## Features
- Toggle LED using GPIO
- Uses FreeRTOS tasks
- Logs LED state to serial monitor
- No extra configuration needed

---

## Hardware Required
- ESP32 development board
- USB cable
- Optional: External LED + resistor if you want to test on a GPIO other than the onboard LED

---

## Software Required
- [ESP-IDF](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/get-started/)
- VS Code with ESP-IDF Extension (optional)
- Python 3.7+ for ESP-IDF tooling

---

## Pin Configuration
- Default LED pin: GPIO 2
- Change pin in `main.c` if needed:

```c
#define LED_GPIO GPIO_NUM_2
