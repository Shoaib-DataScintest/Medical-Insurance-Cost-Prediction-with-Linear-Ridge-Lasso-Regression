#  Insurance Claim Amount Prediction using Regression Models

##  Project Overview

This project develops a **machine learning regression model** to predict medical insurance charges based on demographic and lifestyle factors.

The objective is to estimate healthcare costs accurately, enabling insurance companies to improve pricing strategies, manage risk, and enhance decision-making.

---

##  Business Problem

Accurate estimation of insurance claim amounts is essential for:

* Risk-based premium pricing
* Financial planning and cost management
* Identifying high-risk individuals

Mispricing insurance policies can lead to significant financial losses, making predictive modeling a critical tool.

---

##  Dataset Description

The dataset includes customer demographic and health-related attributes.

### Key Features:

* `age` — Age of the individual
* `sex` — Gender
* `bmi` — Body Mass Index
* `children` — Number of dependents
* `smoker` — Smoking status
* `region` — Residential region

### Target Variable:

* `charges` — Medical insurance cost

---

##  Data Preprocessing

* Standardized column names for consistency
* Applied one-hot encoding to categorical variables
* Performed feature scaling to normalize input features
* Prepared data for regression modeling

---

##  Exploratory Data Analysis (EDA)

Key analyses performed:

* Distribution of insurance charges
* Relationship between age, BMI, and charges
* Impact of smoking on insurance costs
* Correlation analysis among features

### Key Observations:

* Charges are highly right-skewed with significant outliers
* Smoking status has a strong impact on costs
* Age and BMI positively influence medical expenses

---

## ⚙️ Machine Learning Models

The following models were implemented:

* **Linear Regression** — Baseline model
* **Ridge Regression** — Reduces overfitting using L2 regularization
* **Lasso Regression** — Performs feature selection using L1 regularization

---

##  Model Training

* Train-test split (80/20)
* Hyperparameter tuning using GridSearchCV
* Feature scaling using StandardScaler

---

##  Model Evaluation

Models were evaluated using:

* **MAE (Mean Absolute Error)** — Measures average error
* **RMSE (Root Mean Squared Error)** — Penalizes large errors

### Results:

* Ridge regression improved model stability
* Lasso regression simplified the model by selecting important features
* Regularization enhanced generalization performance

---

##  Feature Importance

Feature importance analysis shows:

* **Smoking status** — Most significant predictor
* **Age** — Strong influence on costs
* **BMI** — Important health-related factor

---

##  Key Insights

* Smoking is the strongest driver of insurance costs
* Age and BMI significantly influence medical expenses
* High-cost outliers contribute disproportionately to total claims
* Regularization confirms consistency of important features

---

##  Business Recommendations

* Implement risk-based premium pricing for high-risk individuals
* Promote wellness and preventive healthcare programs
* Use predictive models for better underwriting decisions
* Focus on managing high-cost customers effectively

---

##  Risk Considerations

* Outliers may affect prediction accuracy
* Linear assumptions may not capture complex relationships
* Underestimating high-risk customers can lead to financial loss

---

##  Limitations

* Limited dataset features (no medical history or genetics)
* Assumes linear relationships between variables
* Model performance may vary in real-world deployment

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Scikit-learn

---

##  How to Run

```bash
pip install -r requirements.txt
```

```bash
jupyter notebook
```

Run all cells sequentially.

---

##  Project Structure

```
insurance-claim-prediction/
│
├── insurance_analysis.ipynb
├── README.md
└── requirements.txt
```
---
## Screen Shots
<img width="877" height="687" alt="image" src="https://github.com/user-attachments/assets/083a3258-b196-445d-9c1b-8626fb8f9ef7" />
<img width="962" height="669" alt="image" src="https://github.com/user-attachments/assets/44763c72-247e-4b9e-b35c-7fe5d75d6cc1" />
<img width="1004" height="686" alt="image" src="https://github.com/user-attachments/assets/ffe8ae0d-fcf4-4e9e-bfe3-c91377478feb" />

---
---

##  Conclusion

This project demonstrates a complete **regression modeling workflow**, combining data analysis, predictive modeling, and business insights.

The results highlight how lifestyle and demographic factors influence healthcare costs, enabling organizations to make **data-driven financial decisions**.

---

##  Author

Muhammad Shoaib Inksar 
Data Analyst | Machine Learning Enthusiast
