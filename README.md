# 🍷 Red Wine Quality Prediction Project

## Overview
This project is a Machine Learning classification model designed to predict the quality of red wine (score 5-8) based on its physicochemical properties. The goal is to classify a given wine sample as "Good Quality" or "Bad Quality".

## Key Technologies
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn (`RandomForestClassifier`)
* **Tool:** Jupyter Notebook

## Data
The analysis uses the public **Wine Quality Dataset** (specifically, the red wine variant).
The dataset includes 11 features:
`fixed acidity`, `volatile acidity`, `citric acid`, `residual sugar`, `chlorides`, `free sulfur dioxide`, `total sulfur dioxide`, `density`, `pH`, `sulphates`, and `alcohol`. The target variable is `quality`.

## Model Performance
* **Model Used:** Random Forest Classifier
* **Achieved Accuracy:** 92.5% (Note: This is an example, replace with your actual score if different).

## Files in this Repository
* `Project_7_Wine_Quality_Prediction.ipynb`: The main Jupyter Notebook containing the data analysis, pre-processing, model training, evaluation, and predictive system implementation.
* `README.md`: This file, providing an overview and instructions.
* `.gitignore`: Specifies files and folders that Git should ignore (e.g., local environment files).

## How to Run the Notebook
1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YOUR_GITHUB_USERNAME/Wine_Quality_Prediction_Project.git](https://github.com/YOUR_GITHUB_USERNAME/Wine_Quality_Prediction_Project.git)
    ```
2.  **Install Dependencies:** Make sure you have Python, Jupyter, and the required libraries installed.
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
3.  **Open the Notebook:** Navigate to the cloned folder and run:
    ```bash
    jupyter notebook Project_7_Wine_Quality_Prediction.ipynb
    ```
4.  Run all cells in the notebook.
---
