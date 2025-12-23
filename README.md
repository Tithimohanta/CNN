# CNN Image Classification with CIFAR-10 using PyTorch

## 📌 Project Overview
This project implements a complete **Convolutional Neural Network (CNN)** pipeline using **PyTorch** for image classification.  
The model is trained on the **CIFAR-10 dataset** and evaluated both on the standard test set and on **real-world images captured using a smartphone**, which are automatically loaded from a **GitHub repository**.

The entire workflow is **fully automated** and reproducible. Running the notebook using **Run All** will:
- Clone the GitHub repository
- Download the CIFAR-10 dataset automatically
- Train (or load) the CNN model
- Evaluate performance
- Predict classes for custom phone images
- Generate all required visualizations

---

## 📂 Dataset Details

### Standard Dataset: CIFAR-10
- 60,000 RGB images (32 × 32)
- 10 classes:
  - Airplane
  - Automobile
  - Bird
  - Cat
  - Deer
  - Dog
  - Frog
  - Horse
  - Ship
  - Truck

The dataset is downloaded automatically using:
```python
torchvision.datasets.CIFAR10



Custom Dataset (Phone Images)

Custom real-world images are:

Captured using a smartphone

Stored inside the GitHub repository

Automatically loaded after cloning the repo

Example objects used:

Car

Dog

Cat

Bird

These images are resized and normalized using the same preprocessing pipeline as the CIFAR-10 dataset to ensure consistency.
