# PongClock_Temp
Adaption of Nick’s Pong Clock & Brett Oliver's Adaption

https://123led.wordpress.com/about/

&

http://home.btconnect.com/brettoliver1/Pong_Clock/Pong_Clock.htm

My Adaption is to display Temperature with a DHT22 attached

Plan is to build an Uno Shield (PCB) to share and simplify the design onto one circuit to plug
the Display, PIR and Thermostat into.

Code is there, need to document the Sensor connection details

If you cant wait to use it, build as per Brett's instructions (although for memory reasons have had to remove some functionality)
and also, I found I outgrew a standard UNO so its running on a LEANARDO.  If anyone can help me with that please do!

// Connect pin 1 (on the left) of the sensor to +5V
// NOTE: If using a board with 3.3V logic like an Arduino Due connect pin 1
// to 3.3V instead of 5V!
// Connect pin 2 of the sensor to whatever your DHTPIN is
// Connect pin 4 (on the right) of the sensor to GROUND
// Connect a 4.7K resistor from pin 2 (data) to pin 1 (power) of the sensor

I've tried to document the code!

A couple of bugs! Like the toggle between Tmp & Date is not right!

And only a certain DHT Library worked!  Tried a few.

Would love some help on tidying this up.

Example :

![Animated gif](/docs/PongClock_Temp.gif "Animation that shows auto completion")
