# Line-Follower-Bot

This is a bot that follows a line which acts as the path, preferably black in color. 

**MATERIALS USED:**

IR Sensor
Arduino UNO
Motors 
Motor Shield(L293D)
Robot Chassis 
Jumper wires
Battery
4 Wheels



**CONNECTIONS:**

sensor connections

![connections](https://user-images.githubusercontent.com/82402242/221546919-07ca1e90-dd14-4198-88ab-41de3e7dd2f1.jpg)

motor shield connections to arduino

<img width="282" alt="image" src="https://user-images.githubusercontent.com/82402242/221548447-bc4fb3ad-4081-4538-a293-716b59ebdda5.png">


**WORKING:**

We connect two sensors to the front of the bot, which are used the detect obstacles. 

When the two sensors encounter white surface, our bot moves forward.

If the left sensor detects a black surface i.e, the tape or the path we created, it is understood that the path turns left there and hence we program our wheels in such a way that the bot turns left.

Similarly, if the right sensor detects the path tape, the bot is programmed to turn right.

If both the sensors detect a black surface, the bot stops indicating the end of the path.
