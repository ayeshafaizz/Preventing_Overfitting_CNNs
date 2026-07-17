# Preventing Overfitting in CNNs using CIFAR-10

## Project Overview

This project explores several techniques used to reduce overfitting in Convolutional Neural Networks (CNNs). Using the CIFAR-10 image classification dataset, multiple CNN architectures were trained and compared to evaluate their ability to generalize to unseen data.

The project focuses on understanding how regularization techniques affect validation performance and training stability.

---

## Objectives

* Build a baseline CNN model.
* Apply Dropout regularization.
* Apply Batch Normalization.
* Apply L2 Regularization.
* Implement image data augmentation.
* Compare validation accuracy across all models.
* Identify the most effective overfitting prevention technique.

---

## Dataset

### CIFAR-10

The CIFAR-10 dataset contains 60,000 color images belonging to 10 classes:

* Airplane
* Automobile
* Bird
* Cat
* Deer
* Dog
* Frog
* Horse
* Ship
* Truck

Dataset Split:

* Training Images: 50,000
* Test Images: 10,000

Image Size:

* 32 × 32 RGB Images

---

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Jupyter Notebook

---

## Models Implemented

### Baseline CNN

A standard CNN architecture consisting of:

* Convolution Layers
* Max Pooling Layers
* Dense Layers
* Softmax Output Layer

### CNN with Dropout

Introduced Dropout layers to randomly deactivate neurons during training and reduce overfitting.

### CNN with Batch Normalization

Applied Batch Normalization to improve training stability and accelerate convergence.

### CNN with L2 Regularization

Added L2 weight penalties to discourage overly complex models and improve generalization.

---

## Data Augmentation

The following augmentation techniques were applied:

* Random Horizontal Flip
* Random Rotation
* Random Zoom

These transformations increase data diversity and help reduce overfitting.

---

## Experiments Performed

1. Train Baseline CNN
2. Train CNN with Dropout
3. Train CNN with Batch Normalization
4. Train CNN with L2 Regularization
5. Generate augmented image samples
6. Compare validation accuracy curves
7. Identify the best-performing regularization technique

---

## Results

| Model                   | Best Validation Accuracy |
| ----------------------- | ------------------------ |
| Baseline CNN            | 89.23%                   |
| Dropout CNN             | 72.05%                   |
| Batch Normalization CNN | 97.02%                   |
| L2 Regularization CNN   | 76.96%                   |

---

## Key Learnings

* Understanding overfitting in deep learning models.
* Applying multiple regularization techniques.
* Using Batch Normalization effectively.
* Building image augmentation pipelines.
* Comparing model performance experimentally.
* Evaluating CNN generalization using validation accuracy.

---

## Conclusion

This project demonstrates how different regularization techniques impact CNN performance on the CIFAR-10 dataset. By comparing Baseline, Dropout, Batch Normalization, and L2 Regularization models, we gain practical experience in improving model generalization and reducing overfitting in deep learning applications.
