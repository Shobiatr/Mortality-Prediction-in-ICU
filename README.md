# **Mortality Prediction in ICU - TCN and BiGRU Deep Learning Framework**

## **Project Overview**
This project presents a deep learning framework for predicting ICU mortality using multivariate time series classification. The framework leverages **Temporal Convolutional Networks (TCNs)** and **Bidirectional Gated Recurrent Units (BiGRUs)** to capture complex temporal dependencies in ICU patient data, while addressing challenges such as missing values using **Generative Adversarial Networks (GANs)** for imputation.

## **Key Features**
- **Missing Value Imputation**: Uses GANs to handle missing data in the Electronic Health Records (EHR) dataset.
- **Time-Series Classification**: Utilizes TCNs and BiGRUs to model temporal dependencies.
- **Dataset Used**: MIMIC-III, a publicly available dataset containing ICU patient records.

## **Installation**

### **Dependencies:**
- Python 3.x
- TensorFlow
- Pandas
- NumPy
- scikit-learn
- tcn (custom library for Temporal Convolutional Networks)

Install the required libraries using the following command:

```bash
pip install tensorflow pandas numpy scikit-learn tcn
