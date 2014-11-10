PiPhone-Project
===============

CS207-University of Regina Semester Project - A cellphone built from a raspberry pi running raspbian 
====================================================================================================
This project was created during the Fall Semester of 2014 for my Computer Science 207 class. In my search for a project I stumbled upon David Hunt's Raspberry Pi Phone, and was inspired to do my take on it and learn about cellular communication in the process. 

The concept for the phone was simple, take a small low power computer and transform it into a phone unburdened by all the arguably unnecessary addons that exist in today's modern phones. While the Arduino is a solid choice for this project, the amount of shields that would have to be stacked on one another would create issues with size, so a Raspberry Pi was chosen instead. 

The Pi will be equipped with a 2.8"TFT Touch Screen that will act as the interface for the phone. From there hooking up a battery and a GSM module will be needed in order to make the phone mobile and allow cellular communication. Using David Hunt's PiPhone software developed in python and found on GitHub at https://github.com/climberhunt/PiPhone which creates a GUI for the serial communication of the GSM module and the Pi. 
