## Description
Project focused on brain tumor detection and classification through magnetic resonance imaging (MRI) analysis. Using advanced convolutional neural network (CNN) models in PyTorch, this project seeks to improve accuracy and efficiency in brain tumor identification.

## Motivation
Early and accurate detection of brain tumors is crucial for treatment and patient survival. The application of deep learning techniques to analyze medical images represents a significant opportunity to improve diagnoses and patient outcomes.

## Features
- **Tumor classification**: Classifies MRI images into different tumor categories such as glioma, meningioma, non-tumor and pituitary.
- **Tumor segmentation**: Accurate localization and delineation of tumors in MRI images.
- **Deep Learning Models**: Use of pre-trained and customized CNN architectures.
- **User-friendly interface**: Visualization and analysis tools for easy interpretation of results.

## Data
The project uses the "[Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)" dataset available in Kaggle, which contains 7023 MRI images classified into 4 categories.

## Technologies Used
- **PyTorch**: construction and training of deep learning models.
- **OpenCV**: image processing and manipulation.
- **Matplotlib**: data and image visualization.

## Installation and Use

``` 
python3 -m venv <venv_name>
source <venv_name>/bin/activate
pip install -r requirements.txt
```

