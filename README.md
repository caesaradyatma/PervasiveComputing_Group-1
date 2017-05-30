# PervasiveComputing_Group-1
PROJECT DESCRIPTIONS 
In this project, we are going to make a surveillance camera that will interact with user’s phone through email. Raspberry pi is going to be used as the main hardware and Ubuntu MATE is installed in the raspberry pi as the operating system. The surveillance camera will also use the Raspberry PI camera module as the main feature to take pictures and it will collaborate with PIR sensor that will be used for identifying movement and the movement detection will provide trigger for the camera to operate.
 
The scenario will take a simple security and traffic monitor system for a shop , could be a small shop or even a mall, as a background. Raspberry pi is connected to a pir sensor and a camera. During work hours, the system will capture movement using the pir sensor and capturing the picture if a motion is detected. Each time a movement is captured, the system will add to a counter which will be inside a text file and the images taken are captured in a separate folder. For every certain amount of time, the sensor will notify the shop owner through email. The email will show the how many time the camera triggered and the timestamp of when the last picture taken. 

The problem encountered with this system is, the system will keep taking picture each time someone or something triggered the sensor. While this will create a good amount of detail towards a certain event, it uses a great amount of memory space.

COMPONENTS REQUIRED 
The components required for this project are as follows
Raspberry Pi (using Ubuntu MATE OS)
1x Raspberry Pi Camera Module
1x PIR Sensor
1x Resistor
1x LED light
Connecting wires
Breadboard

HOW DOES IT WORK? 
The Surveillance camera accepts information from trigger caused by moving objects in front of the PIR sensor. The sensor itself operates by comparing the two sides of right and left of the sensor to determine if any changes occurred between the two side. When someone moves in front of the sensor, it will trigger a “motion detected” text on the screen and the LED light attached is turned on, however if there is no movement, “no movement” will be printed on the screen and the LED light will stay off. 
 
Each time the sensor detected a motion, besides printing a “motion detected” text, the camera will take a picture and save that picture to a directory in the raspberry pi. The picture itself has the date and time as its file name. This will be the necessary data needed to record at what time and date when a motion is detected so that in case something happened and this device records it, there is a legit proof of it.
 
The system will keep on monitoring the area during its operation time. For each 6 pictures taken or 6 “motion detected” triggered,  the system  will send an email containing the status of current amount of time the sensor has been triggered and the time of last picture taken. There is a 3 second interval of each detection to reduce the amount of picture taken by this device since PIR sensor has a very wide angle of reach and also very sensitive. 




