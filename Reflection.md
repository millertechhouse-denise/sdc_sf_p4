# CarND-Controls-PID
Self-Driving Car Engineer Nanodegree Program

---

## Reflections

[video1]: ./PID.mov "Video"

The PID parameters were set to:

Proportional: 0.2
There is a positional offset in the steering angle, and this is less than 1 to avoid overshoot.
Integral: 0.005
This is exptected to be small because there is no significant steady disturbance.
Derivative: 5
This is expected to be large because the error for the steering angle is large and can cause overshoot which this attempts to correct.

[Video][video1]

