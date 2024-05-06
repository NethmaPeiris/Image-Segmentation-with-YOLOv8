##Image-Segmentation-with-YOLOv8
#Project Overview
Image segmentation is crucial for self-driving cars to understand their environment. It allows the car to identify and distinguish various objects on the road, such as pedestrians, traffic signals, and other vehicles.

This project utilizes YOLOv8 to perform image segmentation on a dataset of traffic scenes for self-driving perception.

#Dataset
The dataset used in this project contains 1395 images and is available on Roboflow: [Instance Segmentation | Roboflow Universe] (https://universe.roboflow.com/search?q=instance%2520segmentation&p=3).

#The dataset includes various object classes relevant to self-driving cars, including:

*Pedestrians (person)
*Vehicles (car, motorcycle, bicycle)
*Traffic infrastructure (road, traffic light, pole)
*Other elements (sidewalk, greenway)

#Model and Training
The YOLOv8 model, specifically the yolov8l configuration, was trained for 15 epochs on the Roboflow dataset.


Prerequisites:

*Python 3.x
*PyTorch
*YOLOv8 (refer to Ultralytics documentation for installation)
*Roboflow account (to download the dataset)
