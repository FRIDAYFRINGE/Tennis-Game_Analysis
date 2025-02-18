## Requirements
* opencv
* python3.8
* ultralytics
* pytroch
* pandas
* numpy 
 
## Introduction
This project analyzes Tennis players in a video to measure their speed, ball shot speed and number of shots.
## Output Videos
Here is a screenshot from one of the output videos:

![Screenshot](output_videos/screenshot.jpeg)


## Court detection
It was used neural network for detection 14 points of tennis court. For more information you can check this repository: https://github.com/yastrebksv/TennisCourtDetector. There you can find pretrained weights to check the model.


## Training
* Tennis ball detetcor with YOLO: training/tennis_ball_detector_training.ipynb
* Tennis court keypoint with Pytorch: training/tennis_court_keypoints_training.ipynb


## Trained model and court key points:
"https://drive.google.com/drive/folders/1b9mrVv_Xg91bxEJx1cmGqQp_o7hjfW6W?usp=sharing"
## weights:
"https://drive.google.com/drive/folders/1HSgsJT-2eXPoBv0PY5qRhsuzTDK3LNQo?usp=sharing"
