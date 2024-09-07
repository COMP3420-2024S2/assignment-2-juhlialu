[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/ChErOjJH)


# Assignment 2 - Deep Learning for Image Classification

## Overview

This notebook will focus on deep learning techniques and their application for image classification tasks.

---

## Table of Contents
1. [Dataset](#dataset)
2. [Model Architecture](#model-architecture)
3. [Usage](#usage)
4. [Dependencies](#dependencies)

---

## Dataset
The dataset used for this assignment is the [Intel Image Classification dataset](https://www.kaggle.com/datasets/puneet6060/intel-image-classification) by Puneet Bansal from Kaggle. It consists of image data of natural scenes around the world, categorized into six classes:
- `buildings`
- `forest`
- `glacier`
- `mountain`
- `sea`
- `street`

The train, test, and prediction data have already been separated in folders. There are around 14,000 images in the train set, 3,000 images in the test set, and 7,000 in the prediction set, which will not be used in this notebook.

---

## Model Architecture
### Task 2.1: Simple Image Classifier
Basic *Neural Network* model with a single flatten layer and a single dense (output) layer, using basic evaluation and accuracy as the performance metric

### Task 2.2: More Complex Image Classifier
A more complex *Neural Network* model with tuned hidden layers, tuned dropout layer, and a single dense (output) layer. This will be tuned with `Hyperband` from `keras`.

### Task 3.1: Convnet Model
A *Convolutional Neural Network* model with three Conv2D layers, each followed by a MaxPooling2D layer and a final dense (output) layer.

### Task 3.2: MoblileNet Model
A *MobileNet* model pre-trained on *ImageNet* with frozen pre-trained layers and a LearningRateScheduler.

---

## Usage

1. Clone the repository.
2. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/puneet6060/intel-image-classification) and place the unzipped foler into the local directory of the repository.
3. Install dependencies.
4. Run the Jupyter notebook.
   
--- 

## Dependencies
- **TensorFlow 2.17x**
- **Keras**
- **Matplotlib**
- **NumPy**
- **Seaborn**

Install the dependencies with:
```bash
pip install tensorflow keras matplotlib numpy seaborn
```

--- 

## Acknowledgements

This Jupyter notebook is my submission for the COMP3420 course. The models were created, fine-tuned, and implemented based on lecture materials and unit practical exercises, as well as online resources and documentation referenced throughout the notebook. The dataset is sourced from the [Intel Image Classification dataset on Kaggle](https://www.kaggle.com/datasets/puneet6060/intel-image-classification).

All work presented in this submission is entirely my own. 

Jahn Juhlia Lu 🐰
Student ID 47677759