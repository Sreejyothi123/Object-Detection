# Object-Detection

This project focuses on two key objectives:

1. Object Detection using deep learning (YOLOv8) to detect and classify vehicles in images.
2. Exploratory Data Analysis (EDA) on Tesla autopilot accident data to derive safety-related insights.

## Part 1: Object Detection using YOLOv8
Train an object detection model to identify and localize vehicles in real-time using YOLOv8.

### Methodology
1. Created folder structure and converted annotations to YOLO format.
2. Used YOLOv8n model from Ultralytics with the following hyperparameters:
   Epochs: 25
   Image Size: 672
   Batch Size: 16
Trained on 4,500 randomly selected images.

Results
Successfully detected and localized multiple types of vehicles in test images.
Model showed high precision in bounding box predictions.

## Part 2: Tesla Autopilot Accident EDA
Analyze Tesla accident data (2013–2023) to understand trends and derive insights on autopilot safety.

### Key Insights
Geography: Most accidents occurred in the USA; California reported the highest cases.
Time Trends: Accidents increased over the years, with a drop in 2020 due to COVID-19.
Seasonality: Spikes in Nov–Dec (holiday season), weekends had higher incidents.
Severity: Explored distribution of verified Tesla deaths, pedestrian/cyclist involvement, and multi-vehicle crashes.

### Key libraries used:
ultralytics (for YOLOv8)
pandas, numpy
matplotlib, seaborn
opencv-python
