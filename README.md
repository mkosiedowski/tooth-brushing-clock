# tooth-brushing-clock
Code for Arduino Tooth Brushing clock with SSD1306 0,96'' OLED display

This project runs on both ATmega328 and ATmega168 boards thanks to using only text mode for it's basic graphic display. This means that it can run with cheap 2$ Aruino Nano boards

Wiring: https://www.instructables.com/id/Monochrome-096-i2c-OLED-display-with-arduino-SSD13/ 
Or: https://www.youtube.com/watch?v=PrIAnDZ9dp8

With ATmega 168 based Arduino Nano you will most probably need a pull-up resistor on SCL & SDA inputs of your OLED screen. Just connect them to proper A4/A5 output ports of your Arduino board and also connect them through 10kΩ resistor to 5V output of your board

Demo mode: https://www.youtube.com/watch?v=eoeQTuzwTkY
