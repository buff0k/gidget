# gidget

A hexapod robot based on the project by markwtech on Instructables

## Attributions:

[markwtech on Instructables](https://www.instructables.com/member/markwtech/)

[markwtech Hexapod Robot on Instructables](https://www.instructables.com/Hexapod-Robot/)

[markwtech Hexapod Robot on Thingiverse](https://www.thingiverse.com/thing:3463845)

The goal for this project is to make use of the work already done by markwtech as a basis for a fully autonamous hexapod with adaptive inverse kinematics, collision avoidance, and cliff awareness. As a starting point, markwtech (whose website no longer exists) created a Hexapod Robot that is controlled via a PS2 Wireless Controller, his design work, schematics and code has been adapted to the needs of my own project.

## The project phases are as follows:

1. Initial Construction and control using an ESP32 instead of Arduino, abandoning the PS2 Controller (mini http server for control), and using 2x PCA9685 Servo Driver Boards instead of the homemade method markwtech used.
2. Addition of LiDAR sensors for obstacle avoidance, cliff awareness and adaptive inverse kinematics.
3. Migration to on-board power (Batteries) instead of Bench Power.
4. Addition of additional "Main Brain" for adaptive inverse kinematcs, voice- and facial recognition.
5. Addition of auto-home (Charging) function and patrol- and personality features.

## Print Settings and Materials:

I am adding the STL files (as I found them initially) to this repo, but will make necessary modifications in due course, I have ommitted the SBEC Holder and Receiver Holders from the original project as they will not be used. Will modify the Body Top Plate in due course.

### The following parts are printed in PLA at 30% infill, no support material is needed:

1 Body Bottom Plate

6 Body Risers

1 Body Top Plate

12 Femur Bracket End Caps

12 Femur Brackets

18 Servo Bearing Centers

6 Tibia Base Plates

6 Tibia Bracket End Caps

6 Tibia Brackets

6 Tibia Foot Plates

6 Tibia Sides 1

6 Tibia Sides 2 (Note: the tibia sides are identical, they are just printed with opposing sides down)

6 Tibia Spacer Tubes

### The following parts are printed in PLA at 30% infill with support:

18 Servo Mounts

6 Wire Guides

###The following parts are printed in TPU at 10% infill, no support needed

6 Tibia Foot Bumpers

## Parts List

This parts list is modified from the original to work in line with our goals.

18 MG996R Servos

1 ESP32

2 PCA9685 Servo Drivers

18 624ZZ Bearings

210 M3 10mm Machine Screws
96 M3 13mm Machine Screws
12 M3 16mm Machine Screws
84 M2.5 6mm Machien Screws
54 M3 Machien Screw Nuts

