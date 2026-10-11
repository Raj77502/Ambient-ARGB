## Specs

We will be using 

ESP32 Mini Type C Port Controller Board and WS2812B Led Strips

This Ambient Light Setup is Designed for Three Sided Lighting of TV or Moniter 

Top
Right
Left

We will be using 5v 2A Adapter for power

## Connections

Wiring Connections
1. ESP32-S3 to 74AHCT125
ESP32-S3	74AHCT125
Suitable GPIO (example: GPIO16)	1A (pin 2)
GND	GND (pin 7)
—	VCC (pin 14) → +5V supply
—	1Y (pin 3) → LED strip DIN
—	/1OE (pin 1) → GND

Verify the pinout against the datasheet for your specific IC or module before wiring.

2. Power Supply to LED Strip
5V Power Supply	WS2812B Strip
+5V	+5V
GND / Negative	GND
3. Common Ground

Connect these grounds together:

ESP32-S3 GND
74AHCT125 GND
LED power supply GND
LED strip GND

Important: Power the ESP32-S3 via USB-C during setup. Power the LED strip directly from the regulated 5V supply. Do not connect the external supply's +5V rail to the ESP32 board's USB 5V rail.


