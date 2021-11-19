# Quadrotor-Motion-Planning-for-Autonomous-Navigation-based-on-Deep-Reinforcement-Learning
----

## Environment Setting
- AirSim

## Training quadrotor by Reinforcement Learning 
<img src="https://github.com/Zong-Xi/Quadrotor-Motion-Planning-for-Autonomous-Navigation-based-on-Deep-Reinforcement-Learning/blob/main/picture/rl_env_agent1.png" width="400" alt="RL_graph"/>

- Get data(observation) from sensor 
- Data preprocess for training
- Optimize the policy network by Deep Reinforcement Learning
- Agent output action command for quadrotor depend on current policy network
- Controller transform the reference action into control signal for actuator  
- Quadrotor take action and get new data from sensor 

<br>

## System Design
<img src="https://github.com/Zong-Xi/Quadrotor-Motion-Planning-for-Autonomous-Navigation-based-on-Deep-Reinforcement-Learning/blob/main/picture/system_design.png" width="400" alt="System_Design"/>

<br>

## Evaluation with Non-Convex Obstacle
<img src="https://github.com/Zong-Xi/Quadrotor-Motion-Planning-for-Autonomous-Navigation-based-on-Deep-Reinforcement-Learning/blob/main/picture/convex1.png" width="400" alt="Convex"/>

#### Video

[![Watch the video nonconvex](https://github.com/Zong-Xi/Quadrotor-Motion-Planning-for-Autonomous-Navigation-based-on-Deep-Reinforcement-Learning/blob/main/picture/co.png)](https://youtu.be/4TPvgdnOK-U)

<br>

## Evaluation with Blind Alley
<img src="https://github.com/Zong-Xi/Quadrotor-Motion-Planning-for-Autonomous-Navigation-based-on-Deep-Reinforcement-Learning/blob/main/picture/blindalley.png" width="400" alt="Alley"/>

#### Video

[![Watch the video alley](https://github.com/Zong-Xi/Quadrotor-Motion-Planning-for-Autonomous-Navigation-based-on-Deep-Reinforcement-Learning/blob/main/picture/ba.png)](https://youtu.be/DjY7rzvJA9A)

<br>

## Evaluation with Moving Doors (Dynamic Environment)
<img src="https://github.com/Zong-Xi/Quadrotor-Motion-Planning-for-Autonomous-Navigation-based-on-Deep-Reinforcement-Learning/blob/main/picture/dynamic.png" width="400" alt="Dynamic"/>

#### Video

[![Watch the video nonconvex](https://github.com/Zong-Xi/Quadrotor-Motion-Planning-for-Autonomous-Navigation-based-on-Deep-Reinforcement-Learning/blob/main/picture/dy.png)](https://youtu.be/VTwn2tqv_2I)

<br>

## HITL Test (using PX4 )
