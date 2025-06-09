# Task 5 – Exploratory Data Analysis (EDA) on Titanic Dataset

## Project Overview

This project was completed as part of Task 5 in the Data Analyst Internship Program. The objective was to perform Exploratory Data Analysis (EDA) using Python libraries such as Pandas, Matplotlib, and Seaborn. The analysis was conducted on the Titanic dataset to identify patterns, distributions, and relationships between features that may influence passenger survival.

The Titanic dataset provides detailed information on passengers, including demographics, ticket class, fare, port of embarkation, and survival status.

---

## Tools Used

- Python (via Anaconda Distribution)
- Jupyter Notebook
- Pandas for data manipulation
- Seaborn for statistical visualization
- Matplotlib for plotting

---

## Dataset Summary

- File: `train (1).csv`
- Rows: 891
- Columns: 12

Key columns include:

| Column        | Description                                |
|---------------|--------------------------------------------|
| PassengerId   | Unique identifier for each passenger       |
| Survived      | Survival status (0 = No, 1 = Yes)          |
| Pclass        | Ticket class (1st, 2nd, 3rd)               |
| Name          | Full name of the passenger                 |
| Sex           | Gender                                     |
| Age           | Age in years                               |
| SibSp         | Number of siblings/spouses aboard          |
| Parch         | Number of parents/children aboard          |
| Ticket        | Ticket number                              |
| Fare          | Fare paid for the ticket                   |
| Cabin         | Cabin number (many missing values)         |
| Embarked      | Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton) |

---

## EDA Process

1. **Initial Data Exploration**
   - Inspected dataset shape, column types, and missing values
   - Reviewed summary statistics using `describe()`

2. **Univariate Analysis**
   - Plotted distributions of Age and Fare
   - Examined categorical variable distributions: Sex, Survived, Pclass

3. **Bivariate Analysis**
   - Analyzed survival by Sex and Pclass
   - Explored relationships between Age, Fare, and Survived

4. **Multivariate Correlation**
   - Generated a correlation matrix and heatmap for numerical variables

5. **Handling Missing Values**
   - Filled missing Age values with median
   - Filled missing Embarked values with mode
   - Optional binary feature created to indicate missing Cabin info

6. **Summary of Observations**
   - Documented observations after each visualization and analysis step

---

## Key Insights

- Females had significantly higher survival rates than males.
- Passengers in 1st class had a higher survival rate than those in 2nd or 3rd class.
- Younger passengers, especially children, were more likely to survive.
- Fare had a moderate positive relationship with survival.
- Most missing data was found in the Cabin column and was excluded from analysis.

---

## Project Files

| File Name            | Description                              |
|----------------------|------------------------------------------|
| `task5_eda.ipynb`    | Jupyter Notebook with full EDA           |
| `task5_eda.pdf`      | Exported PDF report                      |
| `train (1).csv`      | Titanic dataset used                     |
| `README.md`          | Project summary and documentation        |

---

## How to Run

1. Install Anaconda and open Jupyter Notebook.
2. Load `task5_eda.ipynb` from your local folder.
3. Run all cells to generate outputs and visualizations.
4. Use `File > Print Preview` to export the notebook as a PDF.

---

## Author

Name: Adithya nandan

Email: 10226adithya.pn@gmail.com

---

## License

This project is submitted as part of the Data Analyst Internship Program. It is intended for educational and evaluation purposes only.
