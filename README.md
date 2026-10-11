# Ambient-ARGB
Making a DIY TV ambient lighting system that synchronizes addressable RGB LEDs with on-screen content using an ESP32-S3, WLED, and Hyperion.NG.


#Hardware

ESP32-S3 development board

WS2812B LED strip (5V, 30 LEDs/m)

5V DC, 2A power supply

74AHCT125 logic level shifter


#Software

WLED — LED control firmware

Hyperion.NG — screen capture and LED synchronization


#LED Layout

Designed for a 32-inch TV, with LEDs along the left, top, and right edges.

Strip length: approximately 1.52 m

LED count: approximately 46


#Setup

Flash WLED onto the ESP32-S3.

Configure the LED count and data GPIO.

Connect the ESP32-S3 and PC to the same network.

Configure Hyperion.NG to capture the PC screen and output to WLED.
