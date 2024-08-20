# Intrusion Detection System using Machine Learning

This repository contains the implementation of an Intrusion Detection System (IDS) using Machine Learning algorithms on two datasets: KDD99 and NSL-KDD. The project involves preprocessing, feature selection, and model training using Random Forest and Naive Bayes classifiers.

## Repository Structure

The repository is organized into two main folders: `Model training for KDD99 dataset` and `Model training for NSL-KDD dataset `. Each folder contains scripts for preprocessing, feature selection, and model training.

### KDD99 Folder

1. **Preprocessing**:
    - `preprocessing.ipynb`: Handles data cleaning by removing null values and checking for duplicates.
    - `SMOTE_imbalance_learning.ipynb`: Uses the SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset.

2. **Feature Selection**:
    - `chi2_feature_selection_5.ipynb`: Selects the top 5 features using the Chi-squared test.
    - `chi2_feature_selection_10.ipynb`: Selects the top 10 features using the Chi-squared test.
    - `chi2_feature_selection_15.ipynb`: Selects the top 15 features using the Chi-squared test.

3. **Model Training with Random Forest**:
    - `random_forest_5_features.ipynb`: Trains a Random Forest model using the top 5 selected features.
    - `random_forest_10_features.ipynb`: Trains a Random Forest model using the top 10 selected features.
    - `random_forest_15_features.ipynb`: Trains a Random Forest model using the top 15 selected features.

4. **Model Training with Naive Bayes**:
    - `naive_bayes_5_features.ipynb`: Trains a Naive Bayes model using the top 5 selected features.
    - `naive_bayes_10_features.ipynb`: Trains a Naive Bayes model using the top 10 selected features.
    - `naive_bayes_15_features.ipynb`: Trains a Naive Bayes model using the top 15 selected features.

### NSL-KDD Folder

1. **Preprocessing**:
    - `preprocessing.ipynb`: Handles data cleaning by removing null values and checking for duplicates.

2. **Feature Selection**:
    - `chi2_feature_selection_5.ipynb`: Selects the top 5 features using the Chi-squared test.
    - `chi2_feature_selection_10.ipynb`: Selects the top 10 features using the Chi-squared test.
    - `chi2_feature_selection_15.ipynb`: Selects the top 15 features using the Chi-squared test.

3. **Model Training with Random Forest**:
    - `random_forest_5_features.ipynb`: Trains a Random Forest model using the top 5 selected features.
    - `random_forest_10_features.ipynb`: Trains a Random Forest model using the top 10 selected features.
    - `random_forest_15_features.ipynb`: Trains a Random Forest model using the top 15 selected features.

4. **Model Training with Naive Bayes**:
    - `naive_bayes_5_features.ipynb`: Trains a Naive Bayes model using the top 5 selected features.
    - `naive_bayes_10_features.ipynb`: Trains a Naive Bayes model using the top 10 selected features.
    - `naive_bayes_15_features.ipynb`: Trains a Naive Bayes model using the top 15 selected features.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/MalikTayyabTanveer/Intrusion-detection-system-using-ML.git
    cd Intrusion-detection-system-using-ML
    ```

## Results

### KDD99 Dataset

- **Random Forest**:
    - Precision: 1.00
    - Recall: 1.00
    - F1-score: 1.00
    - Accuracy: 1.00

- **Naive Bayes**:
    - Precision: 0.94
    - Recall: 0.93
    - F1-score: 0.93
    - Accuracy: 0.93

### NSL-KDD Dataset

- **Random Forest**:
    - Precision: 0.99
    - Recall: 0.99
    - F1-score: 0.99
    - Accuracy: 0.99

- **Naive Bayes**:
    - Precision: 0.55
    - Recall: 0.50
    - F1-score: 0.36
    - Accuracy: 0.52

## Contributors
- **[Tayyab Tanveer](https://www.linkedin.com/in/tayyab-tanveer-b000282b3)** - Lead Developer
- **[Syed Ashar Riaz](https://www.linkedin.com/in/ashar-riaz-46596123b)** - Lead Developer

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
