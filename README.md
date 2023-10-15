# Object-Detection-on-Custom-(Data-Bikes-Detection)
# What is custom object detection?
Object detection is the task of detecting where in an image an object is located and classifying every object of interest in a given image.
To solve this problem Iam using YOLOv8 Model.
# This is a initial version of custom trianing with YOLOv8. Currently YOLOv8 is the newest state-of-the-art YOLO model that can be used for object detection, image classification, and instance segmentation tasks.

# Training Custom Face Mask Detection Model:
I have used Yolov8m for custom training with Bikes data. I did training in Google colab by reading data from Google drive. The notebook explains the below steps:

1.Setting Up Google Colab
2.YOLOV8 Installation
3.Mounting Google Drive
4.Create face_mask_detetcion.yaml (dataset config file) (YOLOV8 format)
5.Training Our Custom Face Mask Detetcion Model
6.Metrics
7.Run Inference With Custom YOLOv8 Object Detector Trained Weights.

# Conclusion:
Based on the inference results, the trained model is doing a great job. We can still imrpove it by using large yolov8 models, additional data and hyperparameter changes. Model file is also available for any type of testing. 

# References:
1.https://github.com/ultralytics/ultralytics
2.https://docs.ultralytics.com/tasks/detection/
