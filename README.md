# PervasiveComputing_Group-1
This project will create a simple security and traffic monitor system for a shop, could be a small shop or even a mall.
Scenario:
  Raspberry pi is connected to a pir sensor and a camera.
  During work hours, the system will capture movement using the pir sensor and capturing the picture if a motion is detected. Everytime
  a movement is captured, the system will add to a counter which will be inside a text file and the images taken are captured in a separate
  folder. At the end of the day, the system will email the data to the store owner/person in charge to report the number of visitors.
  After work hours, the system will switch to night mode. During night mode the system will capture a video for a few seconds then emailing
  the store owner that a movement is detected during the night. 
