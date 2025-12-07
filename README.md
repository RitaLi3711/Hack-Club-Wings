# Hack-Club-Wings
A passion project for making articulated wings. This is for the frame work. the feathers and decorations will be added afterwords.

Journal Entries 



Inspiration + Frame Decision (Dec 6)

I've always wanted to make a cosplay with wings, as it's a common character trait.
However, the key is that these wings will be articulated. Thus, they'll have to move.

Initially, I wanted to decide whether the wings should have feathers or be like bat wings.
It seems that feathers are more common and the folding will be easier as its individual wings.

Moreover, this is the planning stage as I search for information.

The wings will have to fold.
The way they fold is what differs (point of movement).
From past cosplays, there are 2 main frame types.

3 joints
https://youtu.be/Llf2Xc1FtOM?si=F14uOp8mgtAz-DmK
https://youtu.be/ioxxIeyw33Q?si=4gpekAnZgTFiVE0G

1 joint
https://youtu.be/-S2A7ioRvzg?si=h_PVrSaw3obiIKA0
https://youtube.com/shorts/ro5Fy8bAvns?si=yLVc0ShqFhmZ_Usy
For this project, I will be making wings that move at 1 joint, as that is simpler to build.



Change of Plans (Dec 6)
If I decided to do the 1-point plan, I would need to use at least 2 linear actuators.
I could not find this type of motor option on KaiCad + it is quite pricey (amazon $191 for 1)

Many individuals have done the 3-point method, but mechanically by pulling a piece of string.
To incorporate more circuits into this design, I will be connecting a motor to the pulley. Thus, I can also control when the wings go up and down by controlling how much string the pulley pulls(front, back).
20251206_223540

edit*** wait if the mobile part must be the same for both wings...can't I just use 1 linear actuator?



Created Schematic + Wired the PCB (Dec 6-7)
Ok, so turns out I can't just connect the linear actuator directly to the battery. :(

I'll also be using a fuse, motor controller and microcontroller.
I hope that the fuse and controller will prevent me from catching on fire through overheating. After I add all the feathers and cloth, it'd be a fire hazard, especially under a heavy cosplay costume.

The linear actuator has a DC motor built into it already, so I'll be representing it as a regular DC motor on both the schematic and PCB.
The PCB said that there are 0 errors, so hopefully that's a good sign....
