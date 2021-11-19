# Quadrotor-Motion-Planning-for-Autonomous-Navigation-based-on-Deep-Reinforcement-Learning
----

## Environment Setting
- AirSim

## Training quadrotor by Reinforcement Learning 
<img src="https://github.com/Zong-Xi/Quadrotor-Motion-Planning-for-Autonomous-Navigation-based-on-Deep-Reinforcement-Learning/blob/main/picture/rl_env_agent1.png" width="300" alt="RL_graph"/>

- Get data(observation) from sensor 
- Data preprocess for training
- Optimize the policy network by Deep Reinforcement Learning
- Agent output action command for quadrotor depend on current policy network
- Controller transform the reference action into control signal for actuator  
- Quadrotor take action and get new data from sensor 

<br>

## System Design
<img src="https://github.com/Zong-Xi/Quadrotor-Motion-Planning-for-Autonomous-Navigation-based-on-Deep-Reinforcement-Learning/blob/main/picture/system_design.png" width="300" alt="System_Design"/>

<br>

## Evaluation with Non-Convex Obstacle

<br>

## Evaluation with Blind Alley

<br>

## Evaluation with Moving Doors (Dynamic Environment)

<br>

## HITL Test (using PX4 )
