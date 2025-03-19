# Brain Tumor Classification

This repository contains a deep learning model for classifying brain tumors from MRI images. The model is built using TensorFlow and Keras, and it uses a convolutional neural network (CNN) architecture to achieve high accuracy in tumor classification.

The goal of this project is to classify brain tumors into four categories: 
- **Glioma tumor**  
- **Meningioma tumor**  
- **No tumor**  
- **Pituitary tumor**

## Dataset

The dataset used in this project is the Brain Tumor Classification (MRI) dataset from Kaggle.

- **Dataset Source:** [Brain Tumor Classification (MRI)](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri)
- **License:** MIT

## Data Preprocessing

The following preprocessing steps were applied to the dataset:

- **Loading and Resizing Images:**  
  All images were resized to a uniform size of **224×224** pixels.

- **Shuffling and Splitting:**  
  The dataset was shuffled and split into **training (80%)** and **testing (20%)** sets.

- **Label Encoding:**  
  Class labels were converted into numerical values and then **one-hot encoded** for compatibility with the model.

- **Data Augmentation:**  
  The following augmentation techniques were applied to the training images to enhance model generalization:
  - Rotation  
  - Shifting  
  - Shearing  
  - Zooming  
  - Horizontal flipping  
