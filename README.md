# Pose Detection

This is an Exercise reps utilizing the TensorflowJs counter for repetition counting for various exercises.

Currently supported exercises:
- Bicep curls
- Push-ups (Side view)
- Sit-ups
- Squats

Currently, we provide 3 model options:

#### MoveNet
[Demo](https://storage.googleapis.com/tfjs-models/demos/pose-detection/index.html?model=movenet)

MoveNet is an ultra fast and accurate model that detects 17 keypoints of a body.
It can run at 50+ fps on modern laptops and phones.

#### BlazePose:
[Demo](https://storage.googleapis.com/tfjs-models/demos/pose-detection/index.html?model=blazepose)

MediaPipe BlazePose can detect 33 keypoints, in addition to the 17 COCO keypoints,
it provides additional keypoints for face, hands and feet.

#### PoseNet
[Demo](https://storage.googleapis.com/tfjs-models/demos/pose-detection/index.html?model=posenet)

PoseNet can detect multiple poses, each pose contains 17 keypoints.

-------------------------------------------------------------------------------
## Table of Contents
1. [How to Run It](#how-to-run-it)
2. [Keypoint Diagram](#keypoint-diagram)

-------------------------------------------------------------------------------
## How to Run It
In general there are two steps:

You first create a detector by choosing one of the models from `SupportedModels`,
including `MoveNet`, `BlazePose` and `PoseNet`.

 
