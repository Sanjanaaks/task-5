# task-5
# 📊 Exploratory Data Analysis (EDA) -- Titanic Dataset

## 🔹 Overview

This project is part of my **Data Analyst Internship -- Task 5**.\
The objective is to perform **Exploratory Data Analysis (EDA)** on the
Titanic dataset (or any similar dataset) to extract insights, identify
patterns, and detect trends or anomalies using **Python**.

------------------------------------------------------------------------

## 🗂️ Dataset

-   **Source:** [Kaggle Titanic
    Dataset]
-   **Description:** Contains passenger details such as name, age,
    gender, ticket class, fare, and survival status.

------------------------------------------------------------------------

## ⚙️ Tools & Libraries

-   **Language:** Python\
-   **Libraries:**
    -   `pandas` -- Data manipulation\
    -   `numpy` -- Numerical operations\
    -   `matplotlib` -- Data visualization\
    -   `seaborn` -- Statistical visualizations

------------------------------------------------------------------------

## 📌 Steps Performed

1.  **Data Loading & Inspection**
    -   Checked shape, columns, data types, and missing values.\
    -   Used `.info()`, `.describe()`, `.isnull().sum()` for summary
        statistics.
2.  **Data Cleaning**
    -   Handled missing values (e.g., filled `Age` with median).\
    -   Treated skewed data (log transform for `Fare` if needed).
3.  **Univariate Analysis**
    -   Distribution of numerical features using histograms & boxplots.\
    -   Categorical analysis using countplots (e.g., `Survived`,
        `Pclass`, `Sex`).
4.  **Bivariate Analysis**
    -   Relationship between features using scatterplots & boxplots.\
    -   Survival analysis across gender, class, and age.
5.  **Multivariate Analysis**
    -   Correlation heatmap to detect strong relationships.\
    -   Pairplots for combined feature distributions.
6.  **Insights & Summary**
    -   Documented key findings and visual evidence.\
    -   Highlighted factors influencing survival rates.

------------------------------------------------------------------------

## 💡 Key Insights

-   **Gender:** Females had a higher survival rate than males.\
-   **Class:** Passengers in 1st class survived more often compared to
    3rd class.\
-   **Fare:** Higher ticket fares correlated with better survival
    chances.\
-   **Age:** Younger passengers had slightly higher survival rates.

------------------------------------------------------------------------

## 📂 Project Structure

    📁 Task-5-EDA
    │
    ├─ 📜 EDA_Titanic.ipynb      # Jupyter notebook with code and visualizations
    ├─ 📄 EDA_Report.pdf         # PDF summary of findings
    ├─ 📜 README.md              # Project documentation (this file)
    └─ 📊 Titanic-Dataset.csv              # Dataset (if allowed by Kaggle license)

------------------------------------------------------------------------

## 🚀 How to Run

1.  Clone this repository:

``` bash
git clone <repo-link>
cd Task-5-EDA
```

2.  Install dependencies:

``` bash
pip install pandas numpy matplotlib seaborn
```

3.  Run the Jupyter Notebook:

``` bash
jupyter notebook Titanic.ipynb
```

------------------------------------------------------------------------

## 🏆 Outcome

-   Gained hands-on experience in **data cleaning, visualization, and
    pattern recognition**.\
-   Learned to generate insights from raw data to support
    decision-making.

------------------------------------------------------------------------

