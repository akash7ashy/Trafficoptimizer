# Trafficoptimizer
# YOLOv8 Object Detection with DeepSORT Tracking
Traffic Signal Timer

Adaptive Traffic Signal Timer

This Adaptive Traffic Signal Timer uses live images from the cameras at traffic junctions for traffic density calculation using YOLO object detection and sets the signal timers accordingly, thus reducing the traffic congestion on roads, providing faster transit to people, and reducing fuel consumption.
Inspiration
Traffic congestion is becoming one of the critical issues with the increasing population and automobiles in cities. Traffic jams not only cause extra delay and stress for the drivers but also increase fuel consumption and air pollution.

According to the TomTom Traffic Index, 3 of the top 10 countries facing the most traffic congestion are in India viz. Mumbai, Bengaluru, and New Delhi. People are compelled to spend hours stuck in traffic jams, wasting away their precious time commuting. Current traffic light controllers use a fixed timer and do not adapt according to the real-time traffic on the road.

In an attempt to reduce traffic congestion, we developed an improved traffic management system in the form of a Computer Vision-based traffic light controller that can autonomously adapt to the traffic situation at the traffic signal. The proposed system sets the green signal time adaptively according to the traffic density at the signal and ensures that the direction with more traffic is allotted a green signal for a longer duration of time as compared to the direction with lesser traffic.



## Features
This project utilizes YOLOv8 for object detection combined with DeepSORT for tracking and identification of objects, providing trails for each identified object.

## Getting Started

Follow these steps to run the code:

### 1. Clone the Repository
Clone this repository to your local machine:
```bash
git clone https://github.com/akash7ashy/Trafficoptimizer.git
2. Navigate to the Cloned Directory
Change your current working directory to the cloned repository:

cd YOLOv8-Object-Detection-with-DeepSORT-Tracking

3. Install the Ultralytics Package
Install the required ultralytics package using pip:

pip install ultralytics==8.0.0

4. Set the Directory
Navigate to the detect directory inside the yolo/v8 directory:

cd yolo/v8/detect

5. Copy the ckpt.t7 File
Ensure the ckpt.t7 File is placed inside the \YOLOv8-Object-Detection-with-DeepSORT-Tracking\deep_sort_pytorch\deep_sort\deep\checkpoint directory.


6. Copy the ckpt.t7 File
Ensure the ckpt.t7 File is placed inside the \YOLOv8-Object-Detection-with-DeepSORT-Tracking\yolo\v8\detect\deep_sort_pytorch\deep_sort\deep\checkpoint

7. Copy the yolov8l.pt File
Ensure the yolov8l.pt File  is placed inside the YOLOv8-Object-Detection-with-DeepSORT-Tracking\yolo\v8\detect directory.

8. Run the Tracking Script
Execute the following command to start tracking:

python tracking_vehicle_counting.py model=yolov8l.pt source="test.mp4" show=True


