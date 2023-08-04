## Tumour Cellularity Estimation using Watershed Algorithm with Ki-67 Patches Dataset

This project was developed during my internship at NETR AI PVT. LTD., Indian Institute of Technology (IIT), Bhilai.

## Table of Contents

- [Overview](#Overview)
- [Dataset](#Dataset)
- [Installation](#installation)
- [Usage](#usage)

## Overview
This project focuses on estimating tumour cellularity using the Watershed algorithm. The dataset used in this project is the Ki-67 Patches dataset, which contains high-resolution images of tissue samples labeled with three classes: tumour, non-tumour, and background. The segmentation model used for cell segmentation is U-Net, a popular deep learning architecture for image segmentation tasks

## Dataset

The Ki-67 Patches dataset can be accessed from zip file {images.zip}. It contains images of cell nuclei, and each image is paired with corresponding segmentation masks {segmentation.zip} that outline the boundaries of the nuclei. Preprocessing steps, including data  normalization, have been applied to enhance model performance.

## Installation

To run this project, follow these steps:

1. Clone this repository to your local machine.
2. Set up a Python environment (e.g., using virtualenv or conda).
3. Download the Ki-67 Patches dataset and place it in the appropriate directory (if not done already).

## Usage

1. Open the Jupyter Notebook provided in the repository: TumorCellularityWatershed.ipynb.
2. Follow the step-by-step instructions in the notebook to load the dataset, preprocess the data, and train the U-Net model.
3. Experiment with hyperparameters, data augmentation settings, or model architecture to improve performance.
4. Monitor the training process and evaluate the model on test data.
5. Visualize the segmentation results and analyze the model's performance.
6. Implement the Watershed algorithm to segment the tumour cells.
7. Visualize and analyze the results.






