# License Plate Detection using YOLO, Deskew, and EasyOCR

## Project Overview

* [YOLOv5](https://pypi.org/project/yolov5/)
* [Deskew](https://github.com/sbrunner/deskew)
* [easyOCR](https://pypi.org/project/easyocr/)


Demonstrates a method for detecting and reading license plates from vehicle images using Python and several powerful libraries. The approach involves the following steps:

1. **Loading the Image**: Uploading a photo of a vehicle.
2. **Detecting License Plate**: Using YOLO (You Only Look Once) for identifying the position of the registration plate.
3. **Enhancing the Plate Image**: Applying deskew techniques to correct the orientation of the plate.
4. **Running OCR**: Using EasyOCR to extract text from the license plate.

## Features

- **YOLO for Object Detection**: Efficiently detects the location of the license plate in the image.
- **Deskewing**: Corrects the angle of the detected license plate for better OCR results.
- **EasyOCR for Text Recognition**: Reads the characters from the enhanced license plate image.

## Getting Started

### Prerequisites

Ensure you have the following libraries installed in your Python environment:
- torch
- pillow