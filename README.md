# Tuberculosis Prediction Using Machine Learning

**Author:** Owoeye Gabriel Oluwakayode  
**Degree:** B.Sc. Statistics, Osun State University  
**Project:** Undergraduate research project

## Project overview

This project explores the use of supervised machine-learning classification methods to model tuberculosis diagnosis using a patient dataset. The work was completed as an undergraduate Statistics research project.

The notebook includes data inspection and cleaning, exploratory data analysis, correlation analysis, construction of a binary TB diagnosis target, class-imbalance handling with SMOTE, model fitting, and classification evaluation.

## Models explored

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest

## Methods and tools

- Python
- pandas and NumPy
- Matplotlib and Seaborn
- scikit-learn
- imbalanced-learn (SMOTE)
- Excel dataset as the original data source

## Evaluation

The notebook explores confusion matrices, accuracy, precision, recall, F1-score, specificity, error rate, false acceptance/rejection rates, and ROC-AUC.

The original dataset is highly imbalanced (the saved notebook output recorded 2,348 positive and 9 negative observations). Consequently, accuracy alone is not a sufficient measure of model performance. Results should be interpreted using class-specific metrics and the confusion matrix. The modelling workflow and evaluation code require further validation before the findings are treated as reliable.

## Repository structure

```text
tuberculosis-prediction-ml/
├── README.md
├── requirements.txt
├── .gitignore
├── data/
│   └── (approved, anonymised dataset goes here; not included)
└── notebooks/
    └── tuberculosis_prediction.ipynb
```

## How to run

1. Clone or download this repository.
2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Put an approved, anonymised copy of the Excel dataset in `data/` and name it `tuberculosis_data.xlsx`.
4. Open `notebooks/tuberculosis_prediction.ipynb` in Jupyter Notebook or JupyterLab.
5. Run the cells in order.

## Data privacy and responsible use

The dataset is not included in this repository. Do not upload patient names, contact details, hospital identifiers, or any other personally identifiable or confidential health information. Only share data when you have permission and it has been appropriately anonymised.

## Important disclaimer

This is an academic machine-learning project. It is not a clinically validated diagnostic system and must not be used to diagnose, treat, or make medical decisions about any person.
