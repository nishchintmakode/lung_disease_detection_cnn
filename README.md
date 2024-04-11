# Lung Disease Diagnosis using Deep Learning

## Overview
Lung diseases are becoming increasingly prevalent worldwide, encompassing a range of conditions such as chronic obstructive pulmonary disease (COPD), pneumonia, asthma, tuberculosis, and fibrosis. In response to this growing health challenge, various image processing and machine learning models have been developed for accurate diagnosis.

This project focuses on leveraging deep learning techniques for the automated detection of lung diseases from chest X-ray images. Specifically, convolutional neural networks (CNNs) are employed due to their effectiveness in image classification tasks.

## Implementation
### Technologies Used
- Jupyter Notebook
- TensorFlow
- OpenCV
- Keras

### Dataset
The National Institutes of Health (NIH) chest X-ray image dataset, available on Kaggle, serves as the primary dataset for model training and evaluation. Both complete and sample editions of the dataset are considered.

### Model Performance
- **CNN Architecture**: The proposed CNN framework achieves a validation accuracy of 90% when trained on the full dataset.
- **Training Time**: Utilizing the sample dataset significantly reduces training time while sacrificing a slight decrease in validation accuracy.

## Usage
1. Clone the repository:
    ```bash
    git clone https://github.com/your_username/lung-disease-diagnosis.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Open and run the Jupyter Notebooks to train and evaluate the CNN model.

## Conclusion
The implementation of deep learning techniques, particularly CNNs, facilitates the automated diagnosis of lung diseases from chest X-ray images. By leveraging state-of-the-art technologies and datasets, this project aims to assist medical practitioners and experts in accurately identifying and managing lung conditions, ultimately improving patient outcomes.
