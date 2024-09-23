# BraTS 2020 - Brain Tumor Segmentation

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Project Overview
This project, developed as part of the **Master in Computer Science** program at the [**Hellenic Open University (HOU)**](https://www.eap.gr/en/postgraduate-specialization-in-information-systems/), for my Diploma Thesis with title **'Implementation of a medical image classification system using deep learning techniques'**. The project focuses on the segmentation of brain tumors using the **BraTS 2020 dataset**. The goal is to develop and evaluate machine learning models, specifically convolutional neural networks (CNNs), to automate the detection and segmentation of brain tumors from multimodal MRI scans. The dataset which we used is [BraTS 2020](https://www.med.upenn.edu/cbica/brats2020/) from **Kaggle**. This code is a Jupyter Notebook which is used for training and evaluating the model. Also, we developed a Web Application with [**Streamlit**](https://streamlit.io/) which you can find in my repository [Brats ML Predictor](https://github.com/jimsnns/brats_ml_predictor).

### Key Features:
- Preprocessing and handling of MRI scans (NIfTI files).
- Implementation of 2D and 3D convolutional neural networks (CNNs) for segmentation.
- Evaluation of model performance using standard metrics like Dice Score, Sensitivity, and Specificity.

## Dataset
The dataset used for this project is part of the BraTS 2020 challenge, which includes MRI scans in the following modalities:
- **T1**: T1-weighted images.
- **T1c**: T1-weighted contrast-enhanced images.
- **T2**: T2-weighted images.
- **FLAIR**: T2-weighted FLAIR images.

Each MRI scan is provided in NIfTI format (`.nii.gz`) and is associated with a ground truth segmentation.

## Requirements
To run this project, you need to have the following installed:
- Python 3.8
- NumPy 1.24.4
- TensorFlow 2.5.0
- nibabel 5.2.0 (for handling NIfTI files)
- scikit-learn 1.3.2
- matplotlib 3.6.0 (for visualizations)

You can install the dependencies by running:
```bash
pip install -r requirements.txt
```

## Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/jimsnns/MSc_ML_Project.git
    ```
2. Navigate into the project directory:
    ```bash
    cd your_local_dir\MSc_ML_Project
    ```
3. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
To run the Jupyter Notebook, open the file brats2020_training.ipynb from repository MSc_ML_Project, and run the code cell by cell by following the instructions.

## Contributing
Contributions to this project are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.
