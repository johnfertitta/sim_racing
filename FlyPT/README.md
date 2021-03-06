# fertitta's FlyPT Stuff

I've decided to start archiving my FlyPT mover profiles to github so that I can freely make changes and still be able to revert to previous versions of the profiles if needed.  Also I believe it helps facilitate sharing.

It's probably best to just merge the motion pose module(s) into your own default profile with your defined rig and outputs.  As a baseline you can use the profile in it's entirety to see what modules I am currently using, I tend to only experiment with gear shift and suspension poses and don't use them. They exists in these profiles just for experimentation currently.


[@johnfertitta on Twitter](https://twitter.com/johnfertitta)

[@fertitta on Discord](https://discordapp.com/users/fertitta#3709)

# My Rig #

I am using a linear 3 DOF rig with a Traction Loss platform and seat belt tension system.  My actuators are PT Actuator Mega Monsters with 150mm stroke, the belt tension design is from flag ghost.  The system is controlled via a Thanos controller with axis1-4 being my linear actuators, 5 is the TL actuator, and 6 controls the seat belts.

![Picture of my rig](/rig_picture.jpg?raw=true)
