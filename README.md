# Metro-Crowd-Detection

A project to detect and monitor crowd levels in metro coaches / stations using computer vision and deep learning.

 Overview  
This project uses video/camera inputs from metro coaches or platforms, applies person-detection models to estimate crowd density and helps commuters or transport operators identify less crowded segments or bottlenecks.

 Features  
- Real-time detection of people through video feed.  
- Crowd level estimation (e.g., low / medium / high) based on thresholds.  
- Visual indicators (bounding boxes, colored overlays) showing crowd density.  
- Coach-wise / compartment-wise monitoring (if multiple camera feeds).  
- Optional alerts or logs when crowd level goes above a set threshold.

 Tech Stack  
- Language: Python  
- Deep Learning / Detection Model: (e.g., YOLOv8 or other)  
- Computer Vision: OpenCV  
- Video / Camera Processing: etc.  
- (Optional) GPU acceleration / Torch / CUDA  
- Dependencies: e.g., `ultralytics`, `opencv-python`, `numpy`, etc.

 How to Run  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/gaurikathakur/Metro-crowd-detection.git  
   cd Metro-crowd-detection  
