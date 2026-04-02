# DevelopersHub — Data Science & Analytics Internship

This repository contains Jupyter notebooks for the **DevelopersHub Corporation** Data Science & Analytics internship tasks (due **3 April 2026**). At least **three** of five tasks were required; this project includes **all five**.

**Suggested repository name (for GitHub):** `developershub-ds-internship-tasks` or `ds-analytics-internship-2026` (pick one that is clear to you and your mentors).

## Contents

| Notebook | Topic | Dataset (local file / source) |
|----------|--------|-------------------------------|
| `Task_1.ipynb` | Iris exploration & visualization | `seaborn.load_dataset("iris")` |
| `Task_2.ipynb` | Loan **approval** prediction (classification) | `loan_data_set.csv` (Kaggle-style Loan Prediction) |
| `Task_3.ipynb` | Customer churn prediction | `Churn_Modelling.csv` |
| `Task_4.ipynb` | Insurance **charges** regression | `insurance.csv` (Medical Cost / personal) |
| `Task_5.ipynb` | Bank marketing — **term deposit** subscription | `bank.csv` (UCI Bank Marketing) |

## Approach (high level)

- **Task 1:** Load and inspect data with pandas; visualize with matplotlib and seaborn (scatter, histogram, box plot).
- **Task 2:** Impute missing values, EDA on loan amount / income / education, train Logistic Regression and Decision Tree, report accuracy and confusion matrix.
- **Task 3:** Drop identifiers, encode Geography and Gender, train a classifier (Random Forest), analyze feature importance.
- **Task 4:** Encode categoricals, Linear Regression for `charges`, visualize age / BMI / smoker vs charges, report MAE and RMSE.
- **Task 5:** Explore age, job, marital status and related features; Logistic Regression and Decision Tree; interpret segments and metrics.

## Results & insights (summary)

- **Task 1:** Species separate well on petal measures; box plots highlight spread and outliers in sepal width.
- **Task 2:** Credit history and income-related patterns drive approval; Logistic Regression often competes well with a single Decision Tree on this split.
- **Task 3:** Churn is explained strongly by tenure, balance, and product usage patterns; encoded geography/gender contribute as expected.
- **Task 4:** Smoking and BMI relate strongly to charges; linear model gives interpretable baseline errors (MAE / RMSE reported in notebook).
- **Task 5:** Duration, balance, and age matter for **term deposit** subscription; models support segment-level campaign insights.

See each notebook’s **Conclusion** for task-specific takeaways.

## How to run

1. Python **3.10+** recommended.
2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

3. From this folder:

```bash
jupyter notebook
```

Open any `Task_*.ipynb` and run all cells. CSV files must sit **in the same directory** as the notebooks (as already arranged in this project).

## Submission checklist (internship PDF)

- [x] Jupyter notebooks with intro, data description, preparation, EDA, modeling, metrics, conclusion  
- [x] Clean structure and commented steps (within notebooks)  
- [x] This `README.md`  
- [ ] Create a **GitHub** repository with a clear name, push this project, then submit the **repository URL** on **Google Classroom** (manual step)

---

*Internship brief: “Data Science & Analytics Interns” (DevelopersHub Corporation).*
