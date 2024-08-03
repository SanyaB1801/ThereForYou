# Thyroid-Disease-Prediction

## Objective:
The primary goal of this project is to build a machine learning model capable of predicting thyroid disease based on patient data. Accurate prediction of thyroid disorders is essential for timely diagnosis and effective treatment.

## Key Features:
Model Development: Developed a machine learning model to predict thyroid disease with high accuracy using the HistGradientBoostingClassifier.
Data Preprocessing: Utilized Pandas for data handling and Scikit-learn for preprocessing tasks such as handling missing values, splitting data, and scaling features.
Feature Extraction: Processed and standardized data to ensure optimal model performance.
Classification Model: Trained a HistGradientBoostingClassifier to classify thyroid conditions.
Performance Evaluation: Assessed model performance using classification metrics and heatmap.
Model Management: Saved the trained model using Joblib for future predictions.

## Project Components:

1. **Dataset**:
    - Dataset Source: [UCI Machine Learning Repository - Thyroid Disease Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/thyroid-disease/new-thyroid.data)

2. **Notebook**:
    - thyroid_prediction.ipynb: A Jupyter notebook containing the entire workflow for data preprocessing, model training, evaluation, and saving the model.
    
3. **Models**:
    - thyroid_model.pkl: The trained thyroid disease prediction model.

4. **Documentation**:
    - README.md: Project overview, setup instructions, and usage guide.

## Workflow:

1. **Data Loading and Preprocessing**:
    - Load patient data from thyroid-disease.data.
    - Preprocess data using standard techniques including handling missing values, splitting into training and testing sets, and feature scaling.
2. **Model Training**:
    - Train a HistGradientBoostingClassifier on the processed patient data to classify thyroid conditions.
3. **Model Evaluation**:
    - Evaluate the model's performance using classification metrics (precision, recall, F1-score).
    - Visualize performance with a confusion matrix heatmap.
4. **Model Saving**:
    - Save the trained model using Joblib for future use and deployment.

## Setup

1. Clone the repository.
2. Download the dataset from the provided source.
3. Run the Jupyter notebook:
    ```bash
    jupyter notebook thyroid_prediction.ipynb
    ```

## Usage
- Execute the notebook to run the complete workflow.
- Use the trained model (thyroid_model.pkl) to make predictions on new patient data.

## Screenshots
![image](https://github.com/user-attachments/assets/8cce27b4-5dad-43d5-8b79-34bcbfea783c)

![image](https://github.com/user-attachments/assets/c1320a76-dd32-48f1-adac-eb21ea003645)

