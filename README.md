# PID controller Project
Self-Driving Car Engineer Nanodegree Program

In this project I implemented a PID Controller to maneuver the vehicle around the track. The simulator provides the cross track error (CTE) and the velocity (mph) as a result PID Controller computes the appropriate steering angle.

## Parameters of PID controller

> A proportional–integral–derivative controller is a control loop feedback mechanism widely used in industrial control systems and a variety of other applications requiring continuously modulated control. A PID controller continuously calculates an error value e(t) as the difference between a desired setpoint (SP) and a measured process variable (PV) and applies a correction based on *proportional*, *integral*, and *derivative* terms (denoted P, I, and D respectively) which give the controller its name.

[Wikipedia](https://en.wikipedia.org/wiki/PID_controller)


## Tunning

Firstly I set up environment based on David's video. After that I tunned paramenters manually and by using Twiddle algorithm. 

My **Final paramenters = [P:0.12, P:0.002, P:2.9]** allow the car to successfully drive around the track and steer pretty smoothly. 


## Improvement

I'm planning to improve this project by adding second PID Controller to adjust a throttle.

[//]: # (Image References)
[image1]: ./pid_track.png

![alt text][image1]


