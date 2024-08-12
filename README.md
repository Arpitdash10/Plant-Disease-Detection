
# Plant Disease Detection
This project focuses on the detection of plant diseases using machine learning techniques. The goal is to help farmers and agriculturists identify plant diseases early, ensuring timely intervention and reducing crop loss.

## Table of Contents
- Overview
- Dataset
- Model Architecture
- Training
- Evaluation
- Results
- Installation
- Usage
- Contributing
## Overview
The Plant Disease Detection project leverages deep learning models to classify and detect diseases in plant leaves. The model is trained on a dataset containing images of healthy and diseased leaves and is capable of predicting the type of disease affecting the plant.

## Dataset
The dataset used for this project consists of thousands of labeled images of plant leaves, each categorized into different classes such as healthy or diseased. The dataset can be accessed from Kaggle or other open-source platforms.

## Model Architecture
The model is based on a convolutional neural network (CNN) architecture, which is well-suited for image classification tasks. The architecture includes several convolutional layers, followed by max-pooling layers, and fully connected layers leading to the output.

## Training
The model was trained using the following configuration:

- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Batch Size: 32
- Epochs: 50
- Learning Rate: 0.001
Data augmentation techniques such as rotation, flipping, and zooming were applied to enhance the model's robustness.

## Evaluation
The model was evaluated on a separate test set, achieving an accuracy of over 90%. The evaluation metrics include precision, recall, F1-score, and a confusion matrix to visualize the performance across different classes.

## Results
The model demonstrates high accuracy in detecting and classifying plant diseases. Below are the key results:

- Accuracy: 92%
- Precision: 91%
- Recall: 90%
- F1-Score: 90%
These results indicate the model's effectiveness in real-world scenarios.

## Installation
To run this project locally, follow these steps:

1 Clone the repository:
```bash
git clone https://github.com/your-username/Plant-Disease-Detection.git
```
2 Navigate to the project directory:
```bash
cd Plant-Disease-Detection
```
3 Install the required dependencies:
```bash
pip install -r requirements.txt
```
## Usage
To use the model for plant disease detection:

1 Prepare your input images in the input_images directory.

2 Run the detection script:
```bash
python detect_disease.py
```
3 The results will be saved in the output directory, showing the disease classification for each image.
## Contributing
Contributions are welcome! Please follow the contribution guidelines if you wish to contribute to this project.