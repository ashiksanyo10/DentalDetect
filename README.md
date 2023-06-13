
Using YoloV5 model to detect the dental disorder in the Panoramic X-Ray 

NoteBook : [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashiksanyo10/DentalDetect/blob/master/DentalYoloV5Final.ipynb)

# Dental Diseases Detection using YOLOv5

This project aims to detect dental diseases in dental radiographic images using YOLOv5 object detection framework.

## Overview

The detection model is built on the YOLOv5 architecture, which is a state-of-the-art object detection algorithm. It has been trained on a custom dataset consisting of annotated dental radiographic images.

## Dataset (Drop a mail - @ashiksanyo@gmail.com)

The dataset used for training and evaluation is a collection of dental radiographic images (Panoramic X-Ray). It contains various types of dental diseases and normal cases. The images are annotated with bounding boxes around the dental diseases regions.

## Getting Started

### Prerequisites

- Python 3.x
- PyTorch
- OpenCV
- YOLOv5

### Installation

1. Clone this repository:
    
         git clone https://github.com/username/dental-diseases-detection.git
         cd dental-diseases-detectionInstall the required dependencies:

2.Install the required dependencies:

      pip install -r requirements.txt

3.Download the pre-trained YOLOv5 weights:
  
     wget https://github.com/ultralytics/yolov5/releases/download/v4.0/yolov5s.pt

4.Run the detection script on sample images:
  
    python detect.py --weights yolov5s.pt --images data/sample_images

5.Usage
    
    Place the dental radiographic images in the data directory.
    Run the detection script with the desired command-line arguments:
    
    python detect.py --weights <path_to_weights> --images <path_to_images> --output <path_to_output>

    path_to_weights: Path to the YOLOv5 weights file.
    path_to_images: Path to the directory containing the dental radiographic images.
    path_to_output: Path to the directory where the detection results will be saved.
    
 6.Results
    
    The detection script will generate the detection results as images with bounding boxes around the detected dental diseases regions. The results will be saved in the specified output directory.

7.License
    
    This project is licensed under the MIT License.

8.Acknowledgments
    
    YOLOv5 - YOLOv5 object detection framework.
