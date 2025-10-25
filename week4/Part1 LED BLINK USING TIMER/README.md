
**Name:** Arsh-e-noor
**Roll No:** 23-NTU-CS-1018

## Week 4 Part 1 - Hardware Timer LED

### Description

This project illustrates the use of an ESP32 hardware timer to toggle an LED every 1 second. The LED blinking is fully controlled through timer interrupts, eliminating the need for `delay()` functions and allowing the main loop to remain available for other operations.

### Components

* ESP32 Development Board
* On-board or External LED (GPIO 2)

### Working

1. A hardware timer on the ESP32 is configured to run at 1 MHz using a prescaler of 80.
2. An interrupt service routine (ISR) executes every 1,000,000 microseconds (1 second) to toggle the LED state.
3. The main `loop()` function stays empty, ensuring non-blocking behavior.
4. This technique allows precise LED control without interrupting other tasks running on the ESP32.

### Learning Outcomes

* Setting up and configuring hardware timers on the ESP32
* Understanding timer prescalers and microsecond-level timing
* Writing ISR-based LED control logic
* Implementing accurate, non-blocking timing using interrupts

### Code Author

**Arsh-e-noor**
**Roll No:** 23-NTU-CS-1018