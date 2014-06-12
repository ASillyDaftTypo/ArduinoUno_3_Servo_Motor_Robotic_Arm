ArduinoUno_3_Servo_Motor_Robotic_Arm
====================================

C++ Code for Arduino Uno &amp; 3 servo motors.

This is a small program that I compiled a couple of years ago as a part of my mech engineering degree individual project.
My original idea was to see if a Raspberry Pi was a suitable replacement in the manufacturing industry in place of larger custom systems for controlling robotic arms, however the base model lacked the micro-controller needed for any degree of accuracy for a servo motor, hence the usage of an Arduino Uno instead. I constructed the arm out of Mechano and a few cheap servos, so the code should be compatible with anyone else using any servo setup, so long as the pulsewidth of the code is changed to match the new motor range.

Simple enough program, interact with it through the Arduino IDE typing a b c d for the relevant commands, calibrate initially to gain coordinates for each voltage level in the servo, then record the movement you want to record back, then finally play back the last thing that was recorded to memory.

What I did note however was that due to the limited memory in the device, only a certain amount could be recorded at once - I even had to cut back on the accuracy of it just to get a decent length movement out of the setup, i.e. grab box with claw, lift box with boom, rotate with box on base, release & drop box with claw.
