# CraneStage2
This is a Simulink®-based model of CRANE by [CraneAero](https://craneaero.co.uk/) developed for Stage 2 of the [GoAero Competition](https://www.goaeroprize.com/). It is adapted from the Parrot® series of mini-drone simulations provided by MathWorks®.

This example shows how to use Simulink® to model a quadcopter, based on the Parrot® series of mini-drones. 
To manage the model and source files, it uses [Project Management](https://uk.mathworks.com/help/simulink/project-management.html). 
To show the quadcopter in a three-dimensional environment, it uses Simulink® 3D Animation™.
For the collaborative development of a flight simulation application, it provides an implementation of the Flight Simulation application template.
This example works with the [Simulink Support Package for Parrot Minidrones](https://uk.mathworks.com/hardware-support/parrot-minidrones.html).

**Note**: To successfully run this example you must have a C/C++ compiler installed.

# Disclaimer
Original codes are from The MathWorks, Inc. (Ref: https://uk.mathworks.com/help/aeroblks/quadcopter-modeling-based-on-parrot-minidrone.html)

Full Tutorials: https://uk.mathworks.com/videos/series/drone-simulation-and-control.html

# Open the Project
With MATLAB, open `CraneQuadcopter\Quadcopter.prj` 

<img width="423" height="234" alt="image" src="https://github.com/user-attachments/assets/455547fb-a978-4f61-b126-80e2d441d74e" />


Upon opening, two key scripts will run automatically:
- `utilities/startVars.m` Initializes model variables and bus objects.
- `mainModels/asbQuadcopter.slx` Launches the core Simulink model of the quadcopter.

<img width="2262" height="1139" alt="image" src="https://github.com/user-attachments/assets/a0b8640a-d245-4d45-90fb-f93ec0b5e441" />

---
# Vehicle-specific parameters: `tasks\vehicleVars.m`

https://github.com/komxun/CraneStage2/blob/24e7c2b3a0cd5435308e502655355debf9bb1ace/CraneQuadcopter/tasks/vehicleVars.m#L17-L64

# Sensors-related parameters: `tasks\sensorsVars.m`

https://github.com/komxun/CraneStage2/blob/24e7c2b3a0cd5435308e502655355debf9bb1ace/CraneQuadcopter/tasks/sensorsVars.m#L7-L65

# Simulation-related parameters: `startVars.m`

https://github.com/komxun/CraneStage2/blob/24e7c2b3a0cd5435308e502655355debf9bb1ace/CraneQuadcopter/utilities/startVars.m#L26-L77







