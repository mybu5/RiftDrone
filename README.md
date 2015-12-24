RiftDrone
====================

A plugin to AR-Webflight that allows you to view and control the quadcopter with an oculus rift.

This is a plugin that allows you to control your ARdrone with a Oculus Rift. This was created at VThacks, 4/2014: http://challengepost.com/software/riftdrone

Heavily referenced ardrone-webflight: https://github.com/eschnou/ardrone-webflight

I've borrowed his instructions as well.


git clone https://github.com/eschnou/ardrone-webflight.git
cd ardrone-webflight
npm install
bower install

Copy over our repository's hud, pilot, and video stream folders.

Copy the config.js.sample to config.js and edit to select your plugins
Connect to the drone's wifi
Run node app.js
Point your browser to http://localhost:3000/


Controls are the same as the pilot plugin, only controls are overwritten by headmotions. 


Taking off, landing, rising and falling are the same as the pilot commands.



Oculus's default position is set when you launch the program. That position is what the helicopter will believe is a "neutral position". No actions will be performed if the
the OR is in this position.



Forwards/Backwards is similar to the quadcopter movements:


Forward is tilting your head forward.


Back is tilting your head backwards.


Turn left/right to turn in those respective directions.


Tilt left/right to strafe in those directions.



If you wish to use this code, by all means feel free to. This was made during VTHacks and was built upon a reference to another project born similarly.



I am not responsible for damages caused by using this plugin. It is difficult to control, and I suggest you test in a soft place and possibly tie a tether to the drone.


The controls are sensitive, so if you do try this, please attempt any movements very slowly at first to get a feel for them.

