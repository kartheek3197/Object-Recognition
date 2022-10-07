# Object-Recognition

## Introduction:
Object Detection is one of the most famous and extensively researched topics in the field of Computer Vision.

To understand Object Detection in simplistic terms, it deals with identifying and localizing some of the classes such as person, car, bus, spoon, etc. from the image. This can be achieved by drawing a bounding box around the given specific target class.

## Prerequisites:
This post assumes familiarity with deep learning concepts and transfer learning. Here we will be using a pretrained model called YOLOv3. 
## YOLOv3:
YOLO is also known as You Only Look Once. It is state of the art object detection model because it is very fast than other models. For this  project we are usig YOLOv3 pretrained model which can detect 80 objects. You can find the 80 classes <a href="https://github.com/pjreddie/darknet/blob/master/data/coco.names" target="_blank">here</a>. 

The reason we are using pretrained model is because training of these vast models require a lot of compute power and resources. So training these models would be very expensive. Some of the big companies and universities train these models on huge data and release them. We can do transfer learning based on our requirement/usecase.

## Applications:
1) Object Detection in Retail
2) Autonomous Driving
3) People detection in Security
4) Medical feature detection in Healthcare

