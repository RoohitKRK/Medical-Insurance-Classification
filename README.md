# Medical Insurance Charges Classification

This repository contains a machine learning project that classifies individuals into categories of **High** or **Low** medical insurance charges based on personal data. The project uses a Support Vector Classifier (SVC) to make these predictions.

## Project Structure
* `MedicalInsurance.ipynb`: The main Jupyter/Colab notebook containing all the code for data loading, exploratory data analysis (EDA), data preprocessing, model training, and evaluation.
* `requirements.txt`: A list of all necessary Python libraries to run the notebook.
* `LICENSE`: The text of the MIT License.
* *Note: The dataset (`Insurance (1).csv`) is expected to be uploaded or placed in the working directory to run the notebook.*

## Methodology

1.  **Data Loading & EDA**: The project uses a dataset with features including age, sex, BMI, number of children, smoker status, and region, along with the target variable, `charges`.
2.  **Preprocessing**: Categorical features (`sex`, `smoker`, `region`) are encoded for model consumption. The continuous `charges` column is converted into a binary classification target (High/Low Charges).
3.  **Model Training**: A **Support Vector Classifier (SVC)** with a `linear` kernel is trained on the processed data.
4.  **Evaluation**: Model performance is assessed using an accuracy score, a confusion matrix, and a classification report.

## Model Performance Summary

The notebook shows the following results for the trained SVC model:

* **Accuracy:** ~90%
* **Classification Report Metrics (Example Snippet from Notebook):**
    * High Charges (Class 0) Precision: 0.91, Recall: 0.98, F1-Score: 0.95
    * Low Charges (Class 1) Precision: 0.95, Recall: 0.77, F1-Score: 0.85

## Dependencies

The project relies on the libraries listed in the `requirements.txt` file.
