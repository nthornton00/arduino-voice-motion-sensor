# arduino-voice-motion-sensor
This project is a motion light sensor using the Arduino Nano BLE sense board. This project takes advantage of Cyberon's voice recognition framework to turn an LED on and off via voice commands and not solely by motion detection.
When the proximity sensor is initialized, any motion detected  (must be less than or equal to 245 mm from the sensor) will automatically turn on the LED. The light will shut off if the sensor detects another motion before the idle phase threshold (10 seconds for demo purposes, but can be changed). Additionally, the board’s voice recognition can be activated at any time by the trigger phrase “Hey Cyberon.” The user must then say one of four commands the project recognizes: “Turn on lights,” “Turn off Lights,” “Turn On Sensor,” and “Turn off Sensor.” If increased activity is expected in front of the motion light, the proximity sensor can be turned off. The sensor can also be turned back on when the user sees fit. Additionally, the commands “Turn on lights” and “Turn off Lights” allow the user to adjust the lights when the sensor is off.

This project was written and compiled using the Arduino IDE. You must include both license and header files as well as the arduino ino file, which contains the program code.

Works Cited

The Arduino Team. “Blink without Delay.” Arduino, 2018, www.arduino.cc/en/Tutorial/BuiltInExamples/BlinkWithoutDelay. 

Marquínez, Pablo. “Voice Commands with the Arduino Speech Recognition Engine.” Arduino Documentation, 2023, docs.arduino.cc/tutorials/nano-33-ble-sense/speech-recognition-engine. 

Will Work For Liberty. “How to Blink an LED with an Arduino Nano.” YouTube, 29 Jan. 2017, www.youtube.com/watch?v=dRAAIrpI1hg. 
