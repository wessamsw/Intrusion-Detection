# Intrusion-Detection

This project focuses on intrusion detection using machine learning techniques on the NSL-KDD dataset. The dataset used for this project is the NSL-KDD dataset, which can be found [here](https://www.kaggle.com/datasets/airadix/nslkdd).

## Project Overview

- Exploratory Data Analysis (EDA): Perform a comprehensive analysis of the dataset to understand the distribution, relationships, and characteristics of the features. This step helps in gaining insights into the data and identifying potential patterns.

- Data Preprocessing: Preprocess the data by handling missing values, scaling features, and encoding categorical variables. This step is crucial for preparing the data for model training.

- Model Building: Develop four Support Vector Machine (SVM) models with different kernel functions for intrusion detection. These models have achieved an accuracy of 93% on the NSL-KDD dataset. The SVM models will leverage the preprocessed data to make accurate predictions.

## Repository Structure

- `data/`: Contains the dataset files used for the project.

- `notebooks/`: Contains Jupyter notebooks documenting the EDA, data preprocessing, and model building steps.

- `models/`: Contains the saved trained SVM models.

- `src/`: Contains any additional source code or utility functions used in the project.
