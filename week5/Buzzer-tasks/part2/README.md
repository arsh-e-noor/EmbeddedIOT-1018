
**Name:** Arsh-e-noor
**Roll No:** 23-NTU-CS-1018

## Week 4 Part 2 - OLED Display Text

### Description

This project demonstrates how to interface an SSD1306 OLED display with an ESP32 using the I2C protocol. It covers initializing the display, drawing graphics, and displaying text messages using the Adafruit GFX and SSD1306 libraries.

### Components

* ESP32 Development Board
* 0.96" or 1.3" OLED Display (SSD1306, 128x64)
* I2C Connection (SDA = GPIO 21, SCL = GPIO 22)

### Working

1. The OLED display is initialized with I2C address `0x3C`.
2. Two diagonal lines are drawn to form an “X” on the screen.
3. The display is cleared, then two text messages are displayed:

   * `"Hello"` in small font at the top.
   * `"CS-A"` in larger font at the center.
4. The display alternates between graphics and text every 2 seconds.

### Learning Outcomes

* Interfacing an SSD1306 OLED with the ESP32
* Using Adafruit GFX and SSD1306 libraries
* Drawing graphics and rendering text on the OLED
* Managing display buffers and refresh cycles

### Code Author

**Arsh-e-noor**
**Roll No:** 23-NTU-CS-1018
