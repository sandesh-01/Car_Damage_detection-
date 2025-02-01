# Car Damage Detection using Detectron2

This project leverages **Detectron2**, a state-of-the-art object detection library, to detect car damages from images. The goal is to develop a model that can automatically identify and classify car damages, such as dents, scratches, and other visible damages, which can be used for insurance claim assessments, car repair assessments, and more.

## Project Overview

The project uses **Detectron2**, a framework built by Facebook AI Research (FAIR), for object detection. The model is trained on a dataset of images containing car damage examples. By detecting specific types of damages, the system can automatically classify and assess the condition of a vehicle.

### Key Features:
- **Car Damage Detection**: Detects various types of damage on cars such as dents, scratches, and other visible imperfections.
- **Object Detection**: Uses Detectron2’s object detection algorithms to detect car parts and identify damaged regions.
- **Image Segmentation**: Classifies different areas of damage on the car’s surface for accurate damage localization.

## Dataset

The dataset used for this project consists of images of cars with labeled regions indicating the type of damage (e.g., scratches, dents). The dataset is preprocessed by resizing, normalizing, and augmenting the images to improve model performance.

### Data Augmentation:
- **Rotation**
- **Flipping**
- **Color Adjustments**
- **Cropping**

## Requirements

The following dependencies are required to run the code:

- Python 3.x
- PyTorch (compatible version with Detectron2)
- Detectron2
- OpenCV
- Matplotlib
- NumPy

You can install the required libraries using the following commands:

```bash
pip install torch torchvision torchaudio
pip install detectron2
pip install opencv-python
pip install matplotlib numpy
