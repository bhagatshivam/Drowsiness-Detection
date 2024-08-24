# Drowsiness Detection System

## Overview
This project is a real-time drowsiness detection system using YOLOv5. It monitors the user's drowsiness by analyzing webcam feed and alerts them if drowsiness is detected for more than 8 seconds. The system is designed to help improve safety by preventing drowsy driving or similar activities.

## Features
* Real-time drowsiness detection using a webcam.
* Alerts the user with a sound if drowsiness is detected for more than 8 seconds.
* Customizable class indices and alert thresholds.

## Installation

### Prerequisites

  * Python 3.6 or higher

### Required Python libraries:
  * pytorch
  * opencv-python
  * numpy
  * playsound
  * matplotlib
  * scikit-learn

You can install the required libraries using the following command:
```bash
pip install -r requirements.txt
```

## Files
* drowsiness_detection_notebook.ipynb: Jupyter Notebook containing the drowsiness detection code.
* alert.wav: Audio file played as an alert.
* yolov5/: Directory containing YOLOv5 implementation and configuration files.
* dataset/: Directory containing your YAML configuration.

## Dataset

The dataset used for training this model was created personally, consisting of 50 images for the "awake" state and 50 images for the "drowsy" state. Due to privacy concerns, the dataset is not included in this repository. If you wish to train the model, you will need to create your own dataset or use an alternative one.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request to contribute.

## Acknowledgements
* YOLOv5 for object detection.
* OpenCV for computer vision tasks.
* Playsound for audio playback.

## Note
This project does not include the dataset or images used for training the model due to privacy concerns. To run the project, you will need to create your own dataset of images and labels.

