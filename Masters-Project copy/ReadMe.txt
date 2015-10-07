JSRPLocations/JSRPController 
------------------------------------------

Compatible with iOS 7.0
iPhone / iPod touch

by JSRP

Disclaimer:
----------
At the time of writing the development of the application means the user must download all the individual parts of the application and put it together. 

The next part of development for this project will be putting everything into one application.

Prerequisites:
--------------
. 1x iPhone 4s or newer
. 4 or more Estimote Beacons
. 1x Estimote Account (This is not essential because I will put the details up of mine)
. TouchOSc
. JSRPLocations
. MAX/MSP
. Unity


How to use:
-----------
1. Open TouchOSc and go to options and enable the Accelerometer (/xyz) tab. After this go to settings, in the connections tab enable CoreMIDI: - This will allow the app to send information after being closed.

2. Open JSRP Locations and log into the Estimote portal, use a .JSON file or calibrate your room following the in app instructions. You will need at least 4 Estimote beacons to do this. Once this is done you should see data being shown at the bottom of the screen.

3. Open Max/MSP, the OSC ports should already match up (it’s worth checking). The data from both applications should be being sent into Max/MSP and manipulating the ‘binaural’ and the grid with the impulse responses on. 

4. Open Unity and open OSUni and match the incoming ports to the Max/MSP outputs. The Unity file should then become responsive. 









