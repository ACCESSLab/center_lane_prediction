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
<a href="https://ncaandt-my.sharepoint.com/:v:/g/personal/tagetahun_ncat_edu/Eak7ovJ-gXxPqFZW2kWWG0kBISOyknpeVSHvrqNKyqNeCg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=fQjIgy"> Rural road driving, Gateway Research Park (North Campus), NC </a>

## Videos

<a href="https://ncaandt-my.sharepoint.com/:v:/g/personal/tagetahun_ncat_edu/EYwiGapNv3tEts0OGxtszzwBlsPwvisqSgIPJGJXtunHSg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=YmCXP3">![til](https://github.com/ACCESSLab/center_lane_prediction/blob/main/images/Lane_Centerline_Prediction.gif)</a>

<a href="https://ncaandt-my.sharepoint.com/:v:/g/personal/tagetahun_ncat_edu/EYwiGapNv3tEts0OGxtszzwBlsPwvisqSgIPJGJXtunHSg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=YmCXP3"> All American Road, Ohio </a>

<a href="https://ncaandt-my.sharepoint.com/:v:/g/personal/tagetahun_ncat_edu/EfbC7L15QqdAmGGsJmOGkf4BmW8Iy9bROKPo2acqWFnqNg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=Y4fgW9">![til](https://github.com/ACCESSLab/center_lane_prediction/blob/main/images/Lane_Centerline_Prediction_Highway.gif)</a>

<a href="https://ncaandt-my.sharepoint.com/:v:/g/personal/tagetahun_ncat_edu/EfbC7L15QqdAmGGsJmOGkf4BmW8Iy9bROKPo2acqWFnqNg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=Y4fgW9"> Highway, I-40 Greensboro, NC</a>
## Pre-trained Model 
> Coming soon ...
## Dataset
> Coming soon ...
