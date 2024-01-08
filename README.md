# Smart Street Lighting System
The project brings together different skillsets,technologies,sensors and Micro controllers; to set up a basic smart system whose goal is to determine and control the energy used in different conditions.Many possibilities remain as potential ground for research but for a start; distance,weather conditions and  time of day are investigated.
## LOGIC
A Smart Street Lighting System would,as the name suggests, try to work with little or no human intervention,and mine is no different.3 key sensors implement that.
1.RTC and Light sensors ensure a correct time for the lights to go on,taking into consideration winter,summer times.
2.Temperature & Humidity sensors ensure the correct conditions are met to regulate lighting i.e; misty conditions would trigger maximum brightness.
3.Proximity sensors(PIR,ULtrasonic) ensure maximum brightness is utilized especially when objects are at predetermined distances at the vicinity.
A combination of these 3 form a robust system,but unfortunately for my project,I implemented the Light (LDR) and ULtrasonic sensors,as they provide much more varied and volatile data.
## Components
1. Sensors-PIR/Ultrasonic,Light,Current,Voltage ,Temperature and Humidity 
1. MCUs-Arduino R3 and ESP8266
1. Power supply-battery and/or AC supply
1. Breadboards
1. Load-LEDs,Resistors etc
1. Real Time Clock
1. Software-Arduino IDE
## Block Diagram
![image](https://github.com/Donnybroke/smart_street_lighting/assets/92339420/dd358934-1703-4ef7-a38d-70352f04fbc3)



