# Medical Insurance Cost Prediction using Linear Regression

## Project Overview

This project predicts **medical insurance charges** based on demographic and lifestyle factors using Machine Learning. The objective is to estimate insurance costs by analyzing features such as age, gender, BMI, number of children, smoking status, and region.

The project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model building, evaluation, model improvement, and business insights.

---

## Dataset

- **Dataset:** Medical Cost Personal Dataset
- **Source:** Kaggle
- **Problem Type:** Regression
- **Target Variable:** Charges

### Features

- Age
- Sex
- BMI
- Children
- Smoker
- Region
- Charges (Target Variable)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Algorithms

- Linear Regression
- Ridge Regression (Model Improvement)

---

## Data Preprocessing

The following preprocessing steps were performed:

- Checked for missing values
- Encoded categorical variables
- Standardized numerical features using StandardScaler
- Split the dataset into Training (80%) and Testing (20%)

---

## Model Evaluation

### Linear Regression

- **R² Score:** 0.7836
- **Adjusted R² Score:** 0.7769
- **MAE:** 4181.19
- **RMSE:** 5796.28

### Ridge Regression

- **R² Score:** 0.7898
- **Adjusted R² Score:** 0.7833
- **MAE:** 3962.82
- **RMSE:** 5712.17

The Ridge Regression model slightly improved prediction accuracy and reduced prediction errors compared to the baseline Linear Regression model.

---

## Business Insights

The analysis revealed that:

- Smoking status is the strongest factor influencing insurance charges.
- Insurance costs generally increase with age.
- Higher BMI is associated with higher medical expenses.
- Predictive analytics can help insurance companies estimate premiums more accurately and improve risk assessment.

---

## Project Structure

```
Medical-Insurance-Cost-Prediction/
│
├── Medical_Insurance_Prediction.ipynb
├── Medical_Insurance_Report.pdf
├── README.md
└── insurance.csv
```

---

## How to Run

1. Install the required Python libraries.
2. Open the Jupyter Notebook.
3. Run all cells sequentially.
4. View the evaluation metrics, visualizations, and business insights.

---

## Conclusion

This project demonstrates how **Linear Regression** can be used to predict medical insurance charges with good accuracy. The comparison with **Ridge Regression** shows that regularization can further improve model performance by reducing prediction errors and enhancing generalization.

---

## Author

**Name:** *Your Name*  
**Course:** B.Tech (Computer Science Engineering – AI & ML)  
**Subject:** Machine Learning