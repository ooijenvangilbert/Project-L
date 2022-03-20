# Project-L

Hardware items used :
- Arduino nano rp2040 connect
- rgb leds SK6812 
- servos sg90 360 degrees
- water pump 6v

Software platforms used :
- Arduino IDE
- Edge impulse

Libraries used :
- Adafruit_neopixel for the rgb leds
- Arduino_LSM6DS0X  for the IMU
- edge impulse for inference

Pins, use the GPIO number in the code:
- D6 GPIO18 use the GPIO numbering in the code (ie 18)
- A0 D14 GPIO26 PWM left servo
- A1 D15 GPIO27 PWM right servo
- D4 GPIO16 Digital out for pump (16)

Modifications :
- SJ1 should be closed to USB power can be utilized on VUSB


