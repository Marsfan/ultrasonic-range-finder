# ultrasonic-range-finder

This arduino library has support for two types of ultrasonic sensors: three pin sensors, like like the parallax Ping))) sensor, or four pin sensors, like the HC-SR04 sensor. 

The main difference between these two types of sensors is the ping))) uses one pin as both the trigger and the signal pin, educate pin count but requiring the arduino to change the pin state between digitalWrite and digitalRead, while the HC-SR04 uses one pin for signal and one for trigger, making code a little bit simpler and the PCB wiring simpler. 
 See the issues page at https://github.com/marsfan/ultrasonic-range-finder for a road map.
