# INX Future Inc - Employee Performance Analysis

This project analyzes employee performance using machine learning and data visualization techniques. It aims to identify key factors affecting performance and build a predictive model to assist HR teams in making informed decisions.

---

##  Objective

- Analyze employee performance based on features such as experience, department, salary hike, work-life balance, etc.
- Identify top factors influencing performance.
- Develop a machine learning model to predict employee performance ratings.
- Provide actionable insights to improve HR decision-making.

---

##  Dataset Overview

- **Source**: INX Future Inc (simulated corporate HR dataset)
- **Records**: 1200 employees
- **Features**: 28 columns (numerical, categorical, and ordinal)
- **Target**: `EmpPerformanceRating` (Employee performance rating)

---

##  Key Features Analyzed

- `EmpDepartment`, `Gender`, `EmpJobRole`
- `TotalWorkExperienceInYears`
- `ExperienceYearsInCurrentRole`
- `EmpLastSalaryHikePercent`
- `EmpJobSatisfaction`, `EmpWorkLifeBalance`, `TrainingTimesLastYear`

---

##  Technologies Used

- **Python** (pandas, numpy, seaborn, matplotlib)
- **Scikit-learn** (RandomForestClassifier, SMOTE)
- **Jupyter Notebook**

---

##  ML Modeling

| Model                    | Accuracy   |
|-------------------------|------------|
| RandomForestClassifier  | **92.08%** |
| DecisionTreeClassifier  | 89.17%     |
| SVC                     | 83.75%     |
| ANN                     | 83.33%     |
| Logistic Regression     | 72.92%     |
| Naive Bayes             | 70.83%     |
| KNN                     | 66.25%     |

- **Best Model**: `RandomForestClassifier`
- **Imbalance Handling**: Applied **SMOTE** to resolve class imbalance.
- **Encoding**: Used **Label Encoding** and **One-Hot Encoding** for categorical variables.
- **Outlier Handling**: Statistical treatment of numerical outliers.

---

##  Key Insights

- **Training & salary hikes** positively correlate with high performance.
- **Department-wise performance** trends highlight Sales and R&D as key focus areas.
- **Work-life balance and environment satisfaction** influence ratings.
- Features like `OverTime` and `HourlyRate` show **minimal direct impact** on performance.

---

##  Recommendations

- Invest in employee training for mid-level performers.
- Review salary hike policy based on performance outcomes.
- Investigate attrition causes in high-pressure departments like Sales.

---


> _This project demonstrates the use of machine learning in HR analytics to support data-driven workforce planning._

