# Semi-Supervised Robot Pose Estimation

## Overview

This project presents a semi-supervised deep learning approach for estimating the orientation (pose) of a robotic object from images.

The main challenge was to accurately estimate the robot's orientation while using only a limited number of labeled images together with a significantly larger collection of unlabeled images.

To address this challenge, a semi-supervised framework was developed by combining supervised learning with unsupervised representation learning, allowing the model to leverage information from both labeled and unlabeled data.

---

## Project Objectives

- Develop a robust robot pose estimation model
- Reduce dependency on large labeled datasets
- Improve generalization using unlabeled data
- Compare supervised and semi-supervised learning approaches

---

## Technologies

- Python
- PyTorch
- OpenCV
- NumPy
- Matplotlib

---

## Methodology

### Supervised Learning

A deep learning model was trained using labeled robot images to predict the object's orientation.

### Semi-Supervised Learning

The supervised model was enhanced by incorporating unlabeled images into the training process, improving feature representation and increasing robustness when labeled data is limited.

---

## Results

The project demonstrates how semi-supervised learning can improve model robustness and representation quality when only a small labeled dataset is available.

This approach is especially valuable in real-world computer vision applications where collecting labeled data is expensive and time-consuming.

---

## Skills Demonstrated

- Machine Learning
- Deep Learning
- Semi-Supervised Learning
- Computer Vision
- Pose Estimation
- PyTorch
- Python
- Model Training
- Image Processing

---

## Future Improvements

- Self-supervised pretraining
- Vision Transformers (ViT)
- Larger and more diverse datasets
- Domain adaptation techniques
- Real-time pose estimation
