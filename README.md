<p align="center"><img width=100% src="https://github.com/noorainf18/noorainf18/blob/main/Noorain%20Fathima%20-%20Banner.png"></p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Python](https://img.shields.io/badge/python-v3.11+-blue.svg)
![Dependencies](https://img.shields.io/badge/dependencies-up%20to%20date-brightgreen.svg)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)


# DRONE DETECTION

The main objective of this project is to develop a robust drone detection system that utilizes YOLOv8 technology. Drones, while offering numerous benefits, also pose potential security risks and privacy concerns. By accurately detecting drones in various environments, we aim to enhance safety, security, and privacy measures.


### Table of Contents

1. Data Description
2. YOLOv8
3. Model Training
4. Results
5. License


## Data Description

- Type of data: 1359 photos of drones.
- Data format: JPG.
- Annotation: Using RoboFlow


## YOLOv8

YOLOv8, or You Only Look Once version 8, is a state-of-the-art object detection algorithm renowned for its speed and accuracy. It belongs to the YOLO family of object detection models, known for their real-time performance on various platforms.

The key idea behind YOLOv8 is its single-stage architecture, where a single neural network is trained end-to-end to predict bounding boxes and class probabilities directly from full images in one evaluation. This approach contrasts with traditional two-stage detectors, which involve region proposal networks followed by object classification.

YOLOv8 employs a deep convolutional neural network (CNN) to extract features from the entire input image. It then uses these features to predict bounding boxes and class probabilities for all objects in the image simultaneously. This results in significantly faster inference times compared to two-stage detectors.

One of the notable features of YOLOv8 is its versatility and scalability. It can detect a wide range of object classes with high accuracy, making it suitable for various applications, including pedestrian detection, vehicle detection, drone detection, and more. Moreover, YOLOv8 can be optimized for different hardware platforms, enabling real-time performance on both CPUs and GPUs.


## Model Training

The model is being trained with YOLOv8 architecture using training parameters
- 50 epochs,
- 0.001 learning rate factor (lrf),
- 32 batch size, and
- 256 image size. Additionally, plots will be generated during training to visualize the model's performance. 


## Results

- Precision: 0.93
- Recall: 0.9
- mAP50: 0.947
- mAP50-95: 0.823


## License

MIT License

Copyright (c) 2024 Noorain Fathima

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
