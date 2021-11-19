# Quadrotor-Motion-Planning-for-Autonomous-Navigation-based-on-Deep-Reinforcement-Learning
----

## Training the Quadrotor for Obstacle Avoidance

### Using Different Sensor
<table>
    <center>
    <tr>
        <td><center>Cumulative Reward (using depth image)</center></td>
        <td><center>Cumulative Reward (using laser)</center></td>
    </tr>
    </center>
    <tr>
        <td align="center"><img src="https://github.com/Zong-Xi/Quadrotor-Motion-Planning-for-Autonomous-Navigation-based-on-Deep-Reinforcement-Learning/blob/main/result/result_image.png" ></td>
        <td align="center"><img src="https://github.com/Zong-Xi/Quadrotor-Motion-Planning-for-Autonomous-Navigation-based-on-Deep-Reinforcement-Learning/blob/main/result/result_laser.png" ></td>
    </tr>
</table>

### Improvement for Depth Image
<table>
    <center>
    <tr>
        <td><center>Depth Image + Recurrent Network</center></td>
        <td><center>Transfer Learning: Pre-trained Depth Network + Pre-trained Laser Network</center></td>
    </tr>
    </center>
    <tr>
        <td align="center"><img src="https://github.com/Zong-Xi/Quadrotor-Motion-Planning-for-Autonomous-Navigation-based-on-Deep-Reinforcement-Learning/blob/main/result/result_recurrent.png" ></td>
        <td align="center"><img src="https://github.com/Zong-Xi/Quadrotor-Motion-Planning-for-Autonomous-Navigation-based-on-Deep-Reinforcement-Learning/blob/main/result/result_transfer.png" ></td>
    </tr>
</table>

<br>

## Training the Quadrotor for Autonomous Navigation
<table>
    <center>
    <tr>
        <td><center>Benchmark Reward Function</center></td>
        <td><center>Reward Function with Penalty</center></td>
    </tr>
    </center>
    <tr>
        <td align="center"><img src="https://github.com/Zong-Xi/Quadrotor-Motion-Planning-for-Autonomous-Navigation-based-on-Deep-Reinforcement-Learning/blob/main/result/nop.png" ></td>
        <td align="center"><img src="https://github.com/Zong-Xi/Quadrotor-Motion-Planning-for-Autonomous-Navigation-based-on-Deep-Reinforcement-Learning/blob/main/result/p.png" ></td>
    </tr>
</table>

<br>

## Conclusion
- Proposes a curriculum based reward function and a penalty based reward
function, solve the inefficiency in training and get better convergence
- Solve the lack of observation in DRL(solve the limitation of camera FOV in this project), and improves the estimation of Q-function

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
