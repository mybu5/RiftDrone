RiftDrone
====================

A plugin to AR-Webflight that allows you to view and control the quadcopter with an oculus rift.

This is a plugin that allows you to control your ARdrone with a Oculus Rift. This was created at VThacks, 4/2014: http://challengepost.com/software/riftdrone

Heavily referenced Oculus-drone by Diego Araos.

I've borrowed his instructions as well.
0.replace pilot and video-stream folders in your plugin folder with mine. You can use my HUD folder too, which is slightly better for Oculus use.
I don't know how to rename them, and I no longer have access to a drone so I can't test, so this is finished until I someday buy one. 
1. npm install
2. bower install
3. coffee -wc -o . .
4. Download and run oculus-rest server (https://github.com/possan/oculus-rest)
5. node .
6. Go to your browser http://localhost:3000/
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