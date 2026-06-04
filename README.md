# CIFAR-10 Object Recognition using ResNet50

Transfer learning model for image classification on the CIFAR-10 dataset using a pre-trained ResNet50 backbone.

---

## Overview

- Uses ResNet50 pre-trained on ImageNet as a feature extractor
- Fine-tunes top layers on CIFAR-10 (60,000 images, 10 classes)
- Applies data augmentation: random flips, rotations, zoom
- Achieves strong classification accuracy across all 10 object categories

## Classes

airplane · automobile · bird · cat · deer · dog · frog · horse · ship · truck

## Tech Stack

Python, TensorFlow / Keras, NumPy, Matplotlib

## Run

```bash
pip install -r requirements.txt
jupyter notebook cifar10_resnet50.ipynb
```
