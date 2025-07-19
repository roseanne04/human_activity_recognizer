# Human Activity Recognition (HAR) using PCA and Machine Learning

This repository contains the code for a small project. The aim of this project is to create a **Principal Component Analysis (PCA)** based **Human Activity Recognition (HAR)** system using multiple machine learning classifiers. This system uses sensor data (from a CSV file containing accelerometer/gyroscope features) and recognizes the activity of the user, e.g. Walking, Sitting, Laying, etc.

---

## Files

The repository contains the following files:

- `mlp_pca.py`: Python script file containing the implementation of the PCA-based HAR system and multiple classifiers like Softmax Regression, OvR, and Voting Classifier.
- `HAR.csv`: CSV file containing the dataset used in this experiment (assumed to have sensor features and activity labels).
- `README.md`: This documentation file.
- `modelbit_deployments`: Snippet in the script showing how to deploy the trained model using Modelbit.

---

## Tools Required

The code in this repository is created using **Python 3.6+**. Furthermore, the following libraries are required to run the code provided in this repository:

- `numpy`
- `pandas`
- `scikit-learn`
- `modelbit`
- `requests`

To install dependencies, run:

```bash
pip install numpy pandas scikit-learn modelbit requests
