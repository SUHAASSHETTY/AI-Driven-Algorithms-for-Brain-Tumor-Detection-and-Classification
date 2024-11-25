# AI-Driven Algorithms for Brain Tumor Detection and Classification

This repository contains the project *AI-Driven Algorithms for Brain Tumor Detection and Classification*, developed as part of a study to explore machine learning techniques for identifying and classifying brain tumors using MRI images.

## Overview

Detecting brain tumors in their early stages is crucial for patient survival. This project explores machine learning and deep learning algorithms to classify brain MRI images as either tumor-positive or tumor-negative. The models evaluated include Support Vector Classifier (SVC), k-Nearest Neighbours (kNN), Neural Networks, and Random Forest.

## Dataset

The dataset comprises 3,000 MRI images, equally balanced between tumor and non-tumor cases. It includes images of:
- Glioma
- Meningioma
- Pituitary gland tumors
- Healthy brains

### Data Preparation
Preprocessing steps include:
- Image augmentation with geometric and color transformations
- Splitting data into training and testing sets

## Models and Performance

| Model           | Accuracy | Precision | Recall | F1-Score | AUC  |
|------------------|----------|-----------|--------|----------|-------|
| SVC              | 94%      | 0.94      | 0.94   | 0.94     | 0.94  |
| kNN              | 90%      | 0.85      | 0.97   | 0.91     | 0.89  |
| Neural Networks  | 95%      | 0.94      | 0.97   | 0.96     | 0.95  |
| Random Forest    | 96%      | 0.98      | 0.94   | 0.96     | 0.96  |

### Key Insights
- Random Forest achieved the highest overall performance.
- Neural Networks also performed well, particularly for precision and recall metrics.
- SVC and kNN showed respectable performance, with accuracy above 90%.

## Project Structure

- **Data**: Contains MRI images and metadata.
- **Code**: Includes Python scripts for data preprocessing, training, and evaluation of models.
- **Results**: Stores evaluation metrics, graphs, and summary tables.

## Getting Started

### Prerequisites
- Python 3.x
- Libraries: `numpy`, `pandas`, `matplotlib`, `scikit-learn`, `tensorflow`, `keras`

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/SUHAASSHETTY/AI-Driven-Algorithms-for-Brain-Tumor-Detection-and-Classification.git
   ```
2. Navigate to the repository:
   ```bash
   cd AI-Driven-Algorithms-for-Brain-Tumor-Detection-and-Classification
   ```
3. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

### Run
1. Preprocess the data:
   ```bash
   python preprocess.py
   ```
2. Train models:
   ```bash
   python train_models.py
   ```
3. Evaluate performance:
   ```bash
   python evaluate.py
   ```

## References

- [Complete Guide to Data Augmentation](https://www.datacamp.com/tutorial/complete-guide-data-augmentation)
- [Brain Tumor Segmentation Methods](https://link.springer.com/article/10.1007/s10044-017-0597-8#Sec2)
- [Brain Tumor Detection Project - Kaggle](https://www.kaggle.com/code/adilababayeva13/brain-tumor-detection-project/edit)

## Authors

- **Raghu Vamshi**
- **Sathvik**
- **Raj Kumar**
- **Suhaas S.**
