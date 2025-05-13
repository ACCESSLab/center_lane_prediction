## Lane Center Detection for Autonomous Vehicle Local Path Planning
Local path planning in autonomous vehicles often
relies on lane center information from High Definition (HD) maps as a basis for generating safe trajectories. However,
reference path priors may not be available in vision-based systems that rely on less detailed sources, such as navigation
maps, making it challenging to sample and generate potential paths or trajectories. This paper proposes a vision-based
center line estimation method for multilane roads that can be used as a reference by a local path planner to generate
feasible paths or trajectories. The proposed method employs a semantic segmentation model to predict the center lines for
the ego-lane and adjacent lanes, if present, providing available references at all times. The segmentation output is further
processed to remove outliers, and each prediction is fitted with a cubic spline to obtain a compact representation. The
proposed method demonstrated promising performance on the TuSimple test dataset. Additionally, the approach is deployed
on a real autonomous vehicle platform, integrated with a Model Predictive Controller (MPC) for lane-keeping applications in a
rural setting to demonstrate reliability and real-time operation performance. The system achieved an inference speed of over
85 FPS, meeting real-time operational requirements.


## Practical Demonstration
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/QUAs-sD0vJs.jpg)](https://youtu.be/QUAs-sD0vJs)

<a href="https://youtu.be/QUAs-sD0vJs"> Rural road driving, Gateway Research Park (North Campus), NC </a>

## Videos

<a href="https://youtu.be/dKMmFGmO6DQ">![til](https://github.com/ACCESSLab/center_lane_prediction/blob/main/images/Lane_Centerline_Prediction.gif)</a>


<a href="https://youtu.be/D7gnvfqeM84">![til](https://github.com/ACCESSLab/center_lane_prediction/blob/main/images/Lane_Centerline_Prediction_Highway.gif)</a>

## Pre-trained Model 
> Coming soon ...
## Dataset
> Coming soon ...
