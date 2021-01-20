# antitheft-floor-detection-system

Anti-Theft flooring system. This IoT based Anti-theft flooring System is done using Raspberry Pi. This system will is designed to monitor the entire floor for movement. One single step anywhere on the floor is tracked and the user is alarmed over IoT.

This system will be a secure flooring tile with Iot connectivity. When the owner leaves the house, the system is to be turned on. If there’s unexpected detection after the owner leaves  the house the device passes the information over.

This system is powered by Raspberry pi , the device will also inculde two tiles for demonstration purpose, Piezo sensor, camera, wifi modem.

Whenever an intruder enters in the house and steps on the floor, the movement is sensed by the sensor which will pass on a signal to the raspberry pi controller. The controller in turn will process the signal to be valid signal and then moves the camera to the area where movement was detected and then it will transmit it over the Internet for the home owner to check the image. I will here use IOTGecko for the web based GUI of IOT system which sounds an alert and shows the image captured to user.
