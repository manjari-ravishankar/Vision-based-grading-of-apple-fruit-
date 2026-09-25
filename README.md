# Vision based grading of apple fruit 

## Project Overview

This project focuses on detecting the quality of apples from images using image processing and machine learning techniques.

The system classifies apples into two categories:

- Defected
- Non-Defected

## Methodology

The main steps of the project are:

1. Image preprocessing
2. Feature extraction
3. Feature selection using Recursive Feature Elimination (RFE)
4. Classification using Random Forest
5. Single-image prediction

### Feature Extraction

The extracted features include:

- GLCM
- LBP
- Tamura
- Color
- DWT

A total of 34 features are extracted from each image. RFE is then used to select the most relevant 15 features.

### Classification

A Random Forest classifier is trained using the selected features.

The trained model can predict the quality of a new apple image and provide:

- Predicted class
- Prediction confidence

## Hardware

The overall system uses:

- **Raspberry Pi** for image processing and classification
- **Camera** for capturing apple images
- **Arduino** for controlling the sorting mechanism
- **Conveyor mechanism** for moving the apples

## Technologies Used

- Python
- OpenCV
- NumPy
- Pandas
- Scikit-learn
- Scikit-image
- PyWavelets
- Matplotlib
- Random Forest
- Google Colab

## Repository Contents

- `Apple_quality_checker_final__one.ipynb` — Main project notebook
- `README.md` — Project documentation

## Project Status

The machine learning implementation and single-image prediction workflow are included in this repository.
