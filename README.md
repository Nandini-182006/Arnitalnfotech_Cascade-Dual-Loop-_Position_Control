# Cascade Position Control of DC Motor

## Description

This task focuses on developing a cascade (dual-loop) control system for accurate position control of a DC motor. The system consists of an outer position control loop and an inner speed control loop. This control strategy improves position accuracy, enhances system stability, and provides better dynamic performance compared to a single-loop controller.

## Objective

To design and implement a cascade control system for precise position control of a DC motor.

## Features

Dual-loop cascade control

Position and speed regulation

Improved stability and accuracy

Reduced oscillations

Enhanced dynamic response


## Software Used

MATLAB / Octave

Control System Toolbox


## Block Diagram

Position Step Input → Sum → Position PID → Sum → Speed PID → DC Motor → Integrator → Scope
                        ↑_______________________________________________________________|
                                         Position Feedback



## How to Run

1. Open MATLAB or Octave.


2. Load the file task3_cascade_position_control.m.


3. Run the script.


4. Observe the position response graph.


5. Analyze the performance of the cascade control system.



## Expected Output

Accurate position tracking

Improved stability

Reduced overshoot and oscillations

Faster settling time


## Applications

Robotic arms

CNC machines

Servo motor systems

Industrial automation

Motion control applications


## Conclusion

The cascade control system was successfully implemented for DC motor position control. The dual-loop structure improved tracking accuracy, reduced oscillations, and enhanced overall system performance.
