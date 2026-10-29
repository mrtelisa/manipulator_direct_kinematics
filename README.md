# Manipulator Direct Kinematics

Geometric model and Jacobian of a generic serial manipulator in MATLAB, applied to a 7-DoF industrial manipulator with revolute and prismatic joints.

> Second assignment of the Modelling and Control of Manipulators course (1st year, 1st semester), MSc Robotics Engineering, University of Genoa.

## Content

- **`BuildTree.m`:** transformation matrices between consecutive link frames in the zero configuration, defined from the CAD model of the robot.
- **`geometricModel.m`:** direct geometry as a function of the joint positions *q*, and transformation from the base to any frame (e.g. base → end-effector, frame 3 → frame 5).
- **`kinematicModel.m`:** end-effector Jacobian, for any number and type (revolute or prismatic) of joints.

`MCM_lab2_2024_25.pdf` contains the assignment text.

## Usage

In MATLAB, from the `src/` folder:

```matlab
main
```
