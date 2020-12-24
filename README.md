# YoloV3 Algorithm
* YOLO(You Only Live Once) is an Object Detection Algorithm
* A single neural network is applied to the full image. This network divides the image into regions and predicts bounding boxes and probabilities for each region. These bounding boxes are weighted by the predicted probabilities.
* High Accuracy and extremely Fast

## Working on Yolov3
You will need to download these files
* [yolov3.cfg](https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg) -> model configuration file
* [yolov3.weights](https://pjreddie.com/media/files/yolov3.weights) -> Pretrained model
* [Class Names](https://github.com/pjreddie/darknet/blob/master/data/coco.names) -> List of objects it can detect

### I've worked on human detection file where human's got detected walking on field in a recorded video and the detected output is shown below.

![Output](https://github.com/Shreyansh-Gupta/Yolov3/blob/main/output.gif)
