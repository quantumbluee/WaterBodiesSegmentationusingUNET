# WaterBodiesSegmentationusingUNET
This repository contains code for a U-Net model implemented in TensorFlow/Keras for segmenting water bodies in satellite images. The project involves:

## Overview:
* Data Loading: Loaded satellite images and corresponding masks for water bodies.
* Exploratory Data Analysis: Identified rotation-related issues, discrepancies in ground truths, and potential preprocessing steps.
* Preprocessing: Resized images, handled masks, and standardized values.
* Model Architecture: Implemented a modified U-Net architecture tailored for binary image segmentation.
* Training: Trained the model and tracked performance metrics.
## Highlights:
* Data Preprocessing: Addressed rotation artifacts, normalized image values, and managed large image sizes.
* Model Architecture: Customized U-Net with reduced channels due to memory constraints.
* Training and Evaluation: Achieved promising results in segmenting water bodies.
## Usage:
* Requirements: TensorFlow, NumPy, Matplotlib, Pandas.
* Usage Guide: Check code comments for step-by-step usage instructions.
* Model Testing: Code includes a testing section to visualize model predictions.
## Results:
Model Performance: Achieved mean Intersection over Union (mIoU) of XX% on the test dataset.
