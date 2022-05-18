# Project-Lama

A fun little project to make a spitting lama.
The lama will listen to 'lama' and get annoyed. When it hears it again it will spit (pump).
The lama will also listen to the teams sound and act allerted.

Annoyed :
- red eyes (leds) and ears (servos) back

Alerted :
- eyes blue (leds) and ears (servos) upright


Hardware items used :
- Arduino nano 33 ble sense https://docs.arduino.cc/hardware/nano-33-ble-sense
- rgb leds SK6812 
- servos sg90 180 degrees
- water pump 6v

Software platforms used :
- Arduino IDE	https://www.arduino.cc/en/software
- Edge impulse 	https://www.edgeimpulse.com

Libraries used :
- Adafruit_neopixel for the rgb leds
- Arduino_LSM9DS1  for the IMU
- edge impulse for inference

Pins, use the GPIO number in the code:
- D12 GPIO p1.08 for the leds
- D9 GPIO p0.27 PWM left servo
- D7 GPIO p0.23 PWM right servo
- D5 GPIO p1.13 Digital out for pump 

Modifications :
- SJ1 should be closed to USB power can be utilized on VUSB

Edge impulse project :
- https://studio.edgeimpulse.com/public/86244/latest


Installation :
- the edge impule library should be imported in the Arduino IDE
- the ino file will use the library for inference but contains changes to control the leds, servo's and pump


