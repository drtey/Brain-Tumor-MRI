# Brain Tumor MRI Classification

## Description

This project leverages Convolutional Neural Networks (CNN) to classify MRI images into categories indicating the presence or absence of a brain tumor. Designed to assist in the preliminary screening process, this model aims to speed up diagnosis and aid in treatment planning by utilizing advanced deep learning techniques on MRI image data.

## Features

- **Automated MRI Analysis:** Classifies MRI images into 'tumor' or 'no tumor' categories automatically.
- **High Accuracy:** Uses advanced CNN architectures for high classification accuracy.
- **Data Augmentation:** Employs data augmentation to improve model robustness and generalization.
- **Easy Integration:** Can be easily integrated into existing medical imaging analysis workflows.

## Data

The dataset includes MRI images categorized into 'with tumor' and 'without tumor'. These images are preprocessed to meet the model's input requirements. The dataset is divided into training, validation, and test sets to ensure accurate performance evaluation.

## Technologies Used

- **Python:** The primary programming language.
- **PyTorch:** The deep learning framework for model building and training.
- **NumPy:** For numerical operations.
- **Matplotlib:** For data and results visualization.
- **Jupyter Notebook:** For development, documentation, and execution.

## CNN Model Overview

The CNN model processes MRI images to classify them based on tumor presence. It includes:

1. **Convolutional Layers:** Extract features from images using filters.
2. **Activation Functions:** ReLU introduces non-linearity, allowing for complex pattern learning.
3. **Pooling Layers:** Reduce feature map dimensions to decrease computation and prevent overfitting.
4. **Fully Connected Layers:** Perform classification based on extracted and downsampled features, with a softmax function outputting class probabilities.

## How to Run

1. Clone the repository: `git clone https://github.com/YourRepo/Brain-Tumor-MRI.git`
2. Create and activate virtual
   `environment python3 -m venv <venv_name>
    source <venv_name>/bin/activate`
4. Install required libraries: `pip install -r requirements.txt`
5. Run the notebook: `jupyter notebook model.ipynb`


