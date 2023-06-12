# optimization-based
## locomotion 

- arxiv 2022.08, Perceptive Locomotion through Nonlinear Model Predictive Control, [arxiv](https://arxiv.org/abs/2208.08373)
    - Encode perceptive information through a sequence of geometric primitives that capture local foothold constraints and a signed distance field(SDF) used for collision avoidance.
    - Divide the foothold area into polygons as constraints for NMPC.
    - Instead of using hierarchical optimization(HO) to solve the WBC problem, only a QP problem is used to solve it
- IROS 2018, Dynamic Locomotion in the MIT Cheetah 3 Through Convex Model-Predictive Control, [paper](https://ieeexplore.ieee.org/document/8594448)
    - Model the quadruped robot as a single rigid body dynamic model(SRBD)
    - Use QP to solve the desired foot reaction force.

- IROS 2018, Dynamic Locomotion in the MIT Cheetah 3 Through Convex Model-Predictive Control, [paper](https://ieeexplore.ieee.org/document/8594448)
    - Model the quadruped robot as a single rigid body dynamic model(SRBD)
    - Use Convex-MPC to solve the desired foot reaction force.
    - Use the Kalman filter to estimate the robot state.

- Humanoids 2016, Perception-less Terrain Adaptation through Whole Body Control and Hierarchical Optimization, [paper](https://ieeexplore.ieee.org/abstract/document/7803330)
    - Dynamic modeling of a floating base for a quadruped robot
    - A hierarchical optimization(HO) solution to solve WBC problem

## state-estimation