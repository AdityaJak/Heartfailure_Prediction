# Heart Failure Prediction Using Linear Models

This repository contains Python code and resources for a project focused on predicting heart failure in patients based on clinical features using various linear models and their variants. We will explore the relationship between key clinical features and the likelihood of heart failure in patients.

## Dataset

We use the "Heart Failure Clinical Records" dataset from the UCI Machine Learning Repository. This dataset contains medical records of 299 patients who had heart failure, with each patient profile having 13 clinical features. For our project, we will focus on the following subset of features:

1. Age
2. Creatinine Phosphokinase (CPK)
3. Serum Creatinine
4. Serum Sodium
5. Platelets
6. Target: Death Event (indicating whether the patient deceased during the follow-up period)

You can access the dataset [here](https://archive.ics.uci.edu/ml/datasets/Heart+failure+clinical+records).

## Project Overview

The project aims to build and evaluate various linear models to understand the relationships between the selected clinical features and the occurrence of heart failure in patients. We will explore linear regression models and their variants to predict the likelihood of death events based on these clinical factors.

## Getting Started

Follow these steps to get started with the project:

### Prerequisites

Before running the code, make sure you have the required Python libraries installed. You can install them using `pip`:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

### Code

Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/Heartfailure_Prediction.git
```

Navigate to the project directory:

```bash
cd Heartfailure_Prediction
```

### Usage

1. Open the Jupyter Notebook file `heart_failure_prediction.ipynb`.

2. Execute the code cells in the notebook to perform the following tasks:
   - Data loading and preprocessing.
   - Exploratory data analysis (EDA) to understand the dataset.
   - Feature selection and engineering.
   - Building and training various linear models and their variants.
   - Model evaluation and performance metrics.

3. Customize the notebook to fit your specific requirements or experiment with different linear models.

## Results and Evaluation

The project evaluates the predictive models using metrics such as mean squared error (MSE), root mean squared error (RMSE), and R-squared to assess their accuracy in predicting heart failure events.

## Acknowledgments

- This project is for educational purposes and should not be used for medical diagnosis or treatment decisions.
- Always consult with healthcare professionals for accurate medical assessments.

## Author

[Adithya Jakkaraju]

Feel free to reach out with any questions or suggestions!

I hope this project contributes to a better understanding of the relationship between clinical features and heart failure in patients. Thank you for your interest and support!
