# Handwritten Character Recognition

A MATLAB-based handwritten character recognition system developed as part of my undergraduate senior-year project (2017–2018). This project explores computer vision and machine learning techniques to recognize handwritten English alphanumeric characters using image preprocessing, HOG (Histogram of Oriented Gradients) feature extraction, and neural network classification.

---

## Overview

The system accepts a handwritten text image, preprocesses it to isolate individual characters, extracts HOG features, and classifies each character using a trained neural network. A MATLAB GUI is included for loading or capturing images and displaying the recognized text.

The repository also includes an experimental convolutional neural network (CNN) training script that was explored during the project.

---

## Why This Project Matters

Handwritten character recognition is a fundamental computer vision problem that combines image processing, feature engineering, and machine learning. This project demonstrates the complete workflow of building a recognition system, from preprocessing raw handwritten images to extracting meaningful features and training a classifier.

Although developed as an undergraduate project, it provided hands-on experience with concepts that underpin modern OCR systems and machine learning pipelines.

---

## Applications

Handwritten character recognition has applications across a wide range of domains, including:

* Digitization of handwritten documents and historical archives
* Automated form and document processing
* Postal mail and address recognition
* Bank cheque processing
* Educational assessment and exam evaluation
* Assistive technologies for digitizing handwritten notes
* Data entry automation and document management systems

---

## Features

* Handwritten English alphanumeric character recognition
* Image preprocessing and noise removal
* Character segmentation
* HOG (Histogram of Oriented Gradients) feature extraction
* Neural network-based character classification
* MATLAB GUI for image upload and webcam capture
* Automatic reconstruction of recognized text
* Experimental CNN training implementation

---

## Project Workflow

```text
Input Image
      │
      ▼
Image Preprocessing
      │
      ▼
Noise Removal
      │
      ▼
Character Segmentation
      │
      ▼
HOG Feature Extraction
      │
      ▼
Neural Network Classification
      │
      ▼
Recognized Text Output
```

---

## Repository Structure

```text
MainProgram.m                 # MATLAB GUI application
Feature_Extraction.m          # Extracts HOG features from training images
make_NN_Target_Matrix.m       # Generates target labels for training
Create_Neural_Network.m       # Trains the neural network classifier
Change_Folder_Labels.m        # Processes dataset labels
nnclassify.m                  # Character prediction function
Training_Deep_NN.m            # Experimental CNN training implementation
lines.m                       # Line segmentation utility
Procedure.txt                 # Training workflow
```

---

## Technologies Used

* MATLAB
* MATLAB Image Processing Toolbox
* MATLAB Neural Network Toolbox
* Computer Vision
* Histogram of Oriented Gradients (HOG)
* Pattern Recognition Neural Networks
* Image Processing Techniques

  * Thresholding
  * Morphological Operations
  * Connected Component Analysis
  * Character Segmentation

---

## How It Works

1. Load or capture a handwritten text image.
2. Convert the image to grayscale and binary format.
3. Remove noise and perform morphological processing.
4. Segment the image into individual handwritten characters.
5. Extract HOG descriptors from each character.
6. Classify each character using a trained neural network.
7. Reconstruct the recognized text and save the output.

---

## Repository Notes

* This project was developed during my undergraduate senior year (2017–2018) as an academic project.
* The original handwritten dataset and pretrained model files are not included in this repository.
* The source code is shared for educational purposes and as part of my professional software engineering portfolio.

---

## Skills Demonstrated

* Computer Vision
* Optical Character Recognition (OCR)
* Machine Learning
* Image Processing
* Feature Engineering
* Neural Networks
* MATLAB Application Development
* Algorithm Design

---

## Author

**Sugandha Gupta**

Software Engineer with experience building scalable software systems, cloud-native applications, and data-driven solutions. This repository is part of my professional portfolio and showcases earlier work in machine learning and Optical Character Recognition.
