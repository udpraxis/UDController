# UDController
Ultime Device Controller
This is the intern project to create an App in ios to control Robot and Remote Control car using the Raspberry pi as
the server side and the arduino as the controller 

Ipad
- The client is managed by the swift programming using the SwiftSocket library 
- Gui is created to simplify the setting of the client side 


Raspberry Pi 
- The Server side is managed by the python using the Twisted Library to initiate TCP communication

Arduino
-The arduino will recieve the command from the Raspberry using the SerialCommunication Protocol
-The arduino and the the Raspberry Pi will be connected using USB Port( in future try to eliminate the Arduino)
