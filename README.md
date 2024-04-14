# Trafficoptimizer
# YOLOv8 Object Detection with DeepSORT Tracking

## Features
This project utilizes YOLOv8 for object detection combined with DeepSORT for tracking and identification of objects, providing trails for each identified object.

## Getting Started

Follow these steps to run the code:

### 1. Clone the Repository
Clone this repository to your local machine:
```bash
git clone https://github.com/noorkhokhar99/YOLOv8-Object-Detection-with-DeepSORT-Tracking.git
2. Navigate to the Cloned Directory
Change your current working directory to the cloned repository:

cd YOLOv8-Object-Detection-with-DeepSORT-Tracking

3. Install the Ultralytics Package
Install the required ultralytics package using pip:

pip install ultralytics==8.0.0

4. Set the Directory
Navigate to the detect directory inside the yolo/v8 directory:

cd yolo/v8/detect

5. Copy the Deep Sort PyTorch Folder
Ensure the deep_sort_pytorch folder is placed inside the yolo/v8/detect directory.

5. Copy the ckpt.t7 File
Ensure the ckpt.t7 File is placed inside the \YOLOv8-Object-Detection-with-DeepSORT-Tracking\deep_sort_pytorch\deep_sort\deep\checkpoint directory.


5. Copy the ckpt.t7 File
Ensure the ckpt.t7 File is placed inside the \YOLOv8-Object-Detection-with-DeepSORT-Tracking\yolo\v8\detect\deep_sort_pytorch\deep_sort\deep\checkpoint

5. Copy the yolov8l.pt File
Ensure the yolov8l.pt File  is placed inside the YOLOv8-Object-Detection-with-DeepSORT-Tracking\yolo\v8\detect directory.

6. Run the Tracking Script
Execute the following command to start tracking:

python tracking_vehicle_counting.py model=yolov8l.pt source="test.mp4" show=True

