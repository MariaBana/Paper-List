# optimization-based
## locomotion 
### Paper
- arxiv 2022.12, Optimization-Based Control for Dynamic Legged Robots, [arxiv](https://arxiv.org/abs/2211.11644)  
    - A nice review of optimal control methods for legged robots.  

- arxiv 2022.08, Perceptive Locomotion through Nonlinear Model Predictive Control, [arxiv](https://arxiv.org/abs/2208.08373)
    - Encode perceptive information through a sequence of geometric primitives that capture local foothold constraints and a signed distance field(SDF) used for collision avoidance.
    - Divide the foothold area into polygons as constraints for NMPC.
    - Instead of using hierarchical optimization(HO) to solve the WBC problem, only a QP problem is used to solve it

- IROS 2018, Dynamic Locomotion in the MIT Cheetah 3 Through Convex Model-Predictive Control, [paper](https://ieeexplore.ieee.org/document/8594448)
    - Model the quadruped robot as a single rigid body dynamic model(SRBD)
    - Use QP to solve the desired foot reaction force.

- IROS 2018, MIT Cheetah 3: Design and Control of a Robust, Dynamic Quadruped Robot, [paper](https://ieeexplore.ieee.org/document/8594448)
    - Model the quadruped robot as a single rigid body dynamic model(SRBD)
    - Use Convex-MPC to solve the desired foot reaction force.
    - Use the Kalman filter to estimate the robot state.

- Humanoids 2016, Perception-less Terrain Adaptation through Whole Body Control and Hierarchical Optimization, [paper](https://ieeexplore.ieee.org/abstract/document/7803330)
    - Dynamic modeling of a floating base for a quadruped robot
    - A hierarchical optimization(HO) solution to solve WBC problem


### Code
- [Cheetah-Software](https://github.com/mit-biomimetics/Cheetah-Software)
    - ConvexMPC-WBC
    - The amount of code is large and the structure is complex.
- [A1-QP-MPC-Controller](https://github.com/ShuoYangRobotics/A1-QP-MPC-Controller)
    - QP&MPC
    - Higher code readability
- [legged_control](https://github.com/qiayuanliao/legged_control)
    - NonlinearMPC-WBC

## state-estimation