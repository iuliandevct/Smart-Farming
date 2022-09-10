#This is The First Iteration on Smart Farming

The first project is about a smart system capable of measuring the wetness level in a small pot. Without any calibration, we will use it as analog input
for readings from a capacitive wetness sensor. The microcontroller of choice is Arduino Mega, no special reason after all. 

The sensor is connected to A5 pin and powered from board's internal 5V. Power consumption around 200 mA. After each reading, the uController sends it as 
it is, over the ethernet, to a MQTT broker Server. 

Features & Specifications
1. Supports 3-Pin Sensor interface
2. Analog output
3. Operating Voltage: DC 3.3-5.5V
4. Output Voltage: DC 0-3.0V
5. Interface: PH2.0-3P
6. Size: 99x16mm/3.9x0.63″
