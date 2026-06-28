# Semi-Supervised Robot Pose Estimation

## Overview

This project explores a semi-supervised deep learning approach for estimating the orientation of a robotic object from images.

The main challenge was to achieve accurate pose estimation while having access to only a small number of labeled images and a much larger collection of unlabeled images.

To address this challenge, the project combines supervised and unsupervised learning techniques into a unified semi-supervised framework.

---

## Project Objectives

- Improve robot angle estimation
- Utilize large-scale unlabeled datasets
- Reduce dependency on manual annotations
- Compare supervised and semi-supervised approaches

---

## Technologies

- Python
- PyTorch
- NumPy
- OpenCV
- Matplotlib

---

## Methodology

The project consists of two complementary stages:

### Supervised Learning

A supervised deep learning model was trained using the available labeled robot images.

### Unsupervised Learning

Unlabeled images were leveraged to improve the learned feature representation and enhance pose estimation performance.

Together, these stages create a semi-supervised learning pipeline.

---

## Repository Structure

```
notebooks/
    supervised_model.ipynb
    unsupervised_model.ipynb

images/

README.md
requirements.txt
```

---

## Future Improvements

- Self-supervised pretraining
- Vision Transformers (ViT)
- Larger datasets
- Domain adaptation
